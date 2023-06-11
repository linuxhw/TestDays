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

Total: 292

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME B350M-A               | Desktop     | [ba4bfc1fe1](https://linux-hardware.org/?probe=ba4bfc1fe1) | Jun 08, 2023 |
| Dell     | Vostro 3525                 | Notebook    | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| Apple    | Mac-942B5BF58194151B        | All in one  | [bdad1d1d9e](https://linux-hardware.org/?probe=bdad1d1d9e) | Jun 02, 2023 |
| Acer     | Aspire A515-54G             | Notebook    | [a6c2011fb0](https://linux-hardware.org/?probe=a6c2011fb0) | May 25, 2023 |
| Acer     | Aspire A515-54G             | Notebook    | [e58d4b4aee](https://linux-hardware.org/?probe=e58d4b4aee) | May 25, 2023 |
| Sony     | VPCF13WFX                   | Notebook    | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo   | B50-30 80ES                 | Notebook    | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Toshiba  | Satellite S50-B             | Notebook    | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| ASUSTek  | ZenBook UX425IA_UM425IA     | Notebook    | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| ASUSTek  | ROG Strix G533QM_G533QM     | Notebook    | [14f30effbe](https://linux-hardware.org/?probe=14f30effbe) | Mar 17, 2023 |
| ASRock   | B250M Pro4                  | Desktop     | [98382222cd](https://linux-hardware.org/?probe=98382222cd) | Mar 14, 2023 |
| ASUSTek  | X541NC                      | Notebook    | [d7e16d4472](https://linux-hardware.org/?probe=d7e16d4472) | Mar 11, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ROSA R10            | 21        | 9.33%   |
| Ubuntu 20.04        | 15        | 6.67%   |
| Ubuntu 18.04        | 15        | 6.67%   |
| ROSA R11            | 14        | 6.22%   |
| ROSA R8             | 10        | 4.44%   |
| ROSA R11.1          | 10        | 4.44%   |
| ROSA R8.1           | 8         | 3.56%   |
| Ubuntu 22.04        | 7         | 3.11%   |
| OpenMandriva 4.2    | 6         | 2.67%   |
| OpenMandriva 4.3    | 5         | 2.22%   |
| Linux Mint 21.1     | 5         | 2.22%   |
| Linux Mint 20.1     | 5         | 2.22%   |
| KDE neon 20.04      | 5         | 2.22%   |
| Arch Rolling        | 5         | 2.22%   |
| ROSA R9             | 4         | 1.78%   |
| ROSA 12.2           | 4         | 1.78%   |
| Manjaro             | 4         | 1.78%   |
| Arch                | 4         | 1.78%   |
| Ubuntu 22.10        | 3         | 1.33%   |
| ROSA 12.3           | 3         | 1.33%   |
| Linux Mint 19.1     | 3         | 1.33%   |
| Fedora 36           | 3         | 1.33%   |
| Fedora 34           | 3         | 1.33%   |
| Zorin 16            | 2         | 0.89%   |
| Ubuntu 19.10        | 2         | 0.89%   |
| Ubuntu 16.04        | 2         | 0.89%   |
| ROSA 12.1           | 2         | 0.89%   |
| Pop!_OS 21.04       | 2         | 0.89%   |
| Pop!_OS 20.10       | 2         | 0.89%   |
| Linux Mint 20.2     | 2         | 0.89%   |
| Linux Mint 20       | 2         | 0.89%   |
| Linux Mint 19.3     | 2         | 0.89%   |
| Debian 11           | 2         | 0.89%   |
| BlackPanther 18.1   | 2         | 0.89%   |
| Ubuntu Budgie 23.04 | 1         | 0.44%   |
| Ubuntu 21.10        | 1         | 0.44%   |
| Ubuntu 21.04        | 1         | 0.44%   |
| Ubuntu 19.04        | 1         | 0.44%   |
| SteamOS 3.3.2       | 1         | 0.44%   |
| SteamOS 3.3         | 1         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 68        | 31.63%  |
| Ubuntu        | 47        | 21.86%  |
| Linux Mint    | 20        | 9.3%    |
| OpenMandriva  | 13        | 6.05%   |
| Manjaro       | 10        | 4.65%   |
| Fedora        | 10        | 4.65%   |
| Arch          | 9         | 4.19%   |
| Pop!_OS       | 6         | 2.79%   |
| KDE neon      | 5         | 2.33%   |
| Endless       | 4         | 1.86%   |
| Debian        | 4         | 1.86%   |
| Kali          | 3         | 1.4%    |
| Zorin         | 2         | 0.93%   |
| SteamOS       | 2         | 0.93%   |
| Kubuntu       | 2         | 0.93%   |
| BuildRoot     | 2         | 0.93%   |
| BlackPanther  | 2         | 0.93%   |
| Ubuntu Budgie | 1         | 0.47%   |
| Nobara        | 1         | 0.47%   |
| Lubuntu       | 1         | 0.47%   |
| EndeavourOS   | 1         | 0.47%   |
| Ctlos         | 1         | 0.47%   |
| ALT Linux     | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 10        | 4.26%   |
| 5.10.14-desktop-1omv4002            | 6         | 2.55%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 6         | 2.55%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6         | 2.55%   |
| 5.16.7-desktop-1omv4003             | 5         | 2.13%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 5         | 2.13%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 5         | 2.13%   |
| 5.15.0-41-generic                   | 4         | 1.7%    |
| 4.9.60-nrj-desktop-1rosa-i586       | 4         | 1.7%    |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 4         | 1.7%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 4         | 1.7%    |
| 5.8.0-33-generic                    | 3         | 1.28%   |
| 5.4.32-generic-2rosa-x86_64         | 2         | 0.85%   |
| 5.4.0-48-generic                    | 2         | 0.85%   |
| 5.4.0-37-generic                    | 2         | 0.85%   |
| 5.17.11-generic-2rosa2021.1-x86_64  | 2         | 0.85%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 2         | 0.85%   |
| 5.15.0-67-generic                   | 2         | 0.85%   |
| 5.15.0-58-generic                   | 2         | 0.85%   |
| 5.11.0-7614-generic                 | 2         | 0.85%   |
| 5.11.0-41-generic                   | 2         | 0.85%   |
| 5.11.0-34-generic                   | 2         | 0.85%   |
| 5.11.0-25-generic                   | 2         | 0.85%   |
| 5.10.2-2-MANJARO                    | 2         | 0.85%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 2         | 0.85%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 2         | 0.85%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 2         | 0.85%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 2         | 0.85%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 2         | 0.85%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 2         | 0.85%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 2         | 0.85%   |
| 6.2.8-arch1-1                       | 1         | 0.43%   |
| 6.2.10-arch1-1                      | 1         | 0.43%   |
| 6.2.0-20-generic                    | 1         | 0.43%   |
| 6.1.12                              | 1         | 0.43%   |
| 6.1.1-desktop-1omv2290              | 1         | 0.43%   |
| 6.1.1-arch1-1                       | 1         | 0.43%   |
| 6.1.0-7-amd64                       | 1         | 0.43%   |
| 6.0.14-201.fsync.fc36.x86_64        | 1         | 0.43%   |
| 5.9.3-1-MANJARO                     | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 27        | 11.74%  |
| 5.4.0   | 18        | 7.83%   |
| 5.15.0  | 15        | 6.52%   |
| 4.9.60  | 13        | 5.65%   |
| 5.11.0  | 12        | 5.22%   |
| 5.8.0   | 7         | 3.04%   |
| 4.1.34  | 7         | 3.04%   |
| 5.10.14 | 6         | 2.61%   |
| 4.9.20  | 6         | 2.61%   |
| 5.3.0   | 5         | 2.17%   |
| 5.16.7  | 5         | 2.17%   |
| 5.13.0  | 5         | 2.17%   |
| 5.10.74 | 5         | 2.17%   |
| 5.0.0   | 4         | 1.74%   |
| 4.9.155 | 4         | 1.74%   |
| 4.18.0  | 4         | 1.74%   |
| 5.4.32  | 3         | 1.3%    |
| 5.19.0  | 3         | 1.3%    |
| 4.9.124 | 3         | 1.3%    |
| 4.1.38  | 3         | 1.3%    |
| 6.1.1   | 2         | 0.87%   |
| 5.9.3   | 2         | 0.87%   |
| 5.8.18  | 2         | 0.87%   |
| 5.18.1  | 2         | 0.87%   |
| 5.17.11 | 2         | 0.87%   |
| 5.15.79 | 2         | 0.87%   |
| 5.10.2  | 2         | 0.87%   |
| 5.10.0  | 2         | 0.87%   |
| 4.9.95  | 2         | 0.87%   |
| 4.9.9   | 2         | 0.87%   |
| 4.9.76  | 2         | 0.87%   |
| 4.9.41  | 2         | 0.87%   |
| 4.10.0  | 2         | 0.87%   |
| 4.1.25  | 2         | 0.87%   |
| 6.2.8   | 1         | 0.43%   |
| 6.2.10  | 1         | 0.43%   |
| 6.2.0   | 1         | 0.43%   |
| 6.1.12  | 1         | 0.43%   |
| 6.1.0   | 1         | 0.43%   |
| 6.0.14  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 14.22%  |
| 4.15    | 27        | 12%     |
| 5.15    | 24        | 10.67%  |
| 5.4     | 23        | 10.22%  |
| 5.10    | 19        | 8.44%   |
| 5.11    | 13        | 5.78%   |
| 4.1     | 12        | 5.33%   |
| 5.8     | 9         | 4%      |
| 5.18    | 7         | 3.11%   |
| 5.16    | 7         | 3.11%   |
| 5.13    | 6         | 2.67%   |
| 5.3     | 5         | 2.22%   |
| 5.19    | 5         | 2.22%   |
| 5.17    | 5         | 2.22%   |
| 5.0     | 5         | 2.22%   |
| 6.1     | 4         | 1.78%   |
| 4.18    | 4         | 1.78%   |
| 6.2     | 3         | 1.33%   |
| 5.9     | 2         | 0.89%   |
| 5.14    | 2         | 0.89%   |
| 5.12    | 2         | 0.89%   |
| 4.10    | 2         | 0.89%   |
| 6.0     | 1         | 0.44%   |
| 5.6     | 1         | 0.44%   |
| 5.5     | 1         | 0.44%   |
| 5.2     | 1         | 0.44%   |
| 5.1     | 1         | 0.44%   |
| 4.19    | 1         | 0.44%   |
| 4.16    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 199       | 92.56%  |
| i686   | 16        | 7.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 56        | 25.45%  |
| KDE5            | 54        | 24.55%  |
| KDE4            | 47        | 21.36%  |
| Unknown         | 18        | 8.18%   |
| X-Cinnamon      | 15        | 6.82%   |
| XFCE            | 10        | 4.55%   |
| MATE            | 3         | 1.36%   |
| LXQt            | 3         | 1.36%   |
| KDE             | 3         | 1.36%   |
| sway            | 2         | 0.91%   |
| GNOME Flashback | 2         | 0.91%   |
| Cinnamon        | 2         | 0.91%   |
| xinitrc         | 1         | 0.45%   |
| LXDE            | 1         | 0.45%   |
| i3              | 1         | 0.45%   |
| Budgie          | 1         | 0.45%   |
| bspwm           | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 173       | 79.72%  |
| Wayland | 31        | 14.29%  |
| Unknown | 13        | 5.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 31.22%  |
| SDDM    | 49        | 22.17%  |
| KDM     | 47        | 21.27%  |
| GDM     | 23        | 10.41%  |
| LightDM | 14        | 6.33%   |
| GDM3    | 11        | 4.98%   |
| TDM     | 8         | 3.62%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 75        | 34.56%  |
| en_US   | 67        | 30.88%  |
| ru_RU   | 52        | 23.96%  |
| ro_RO   | 9         | 4.15%   |
| en_GB   | 5         | 2.3%    |
| C       | 4         | 1.84%   |
| ru_UA   | 2         | 0.92%   |
| nl_NL   | 1         | 0.46%   |
| en_150  | 1         | 0.46%   |
| de_DE   | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 124       | 57.41%  |
| EFI  | 92        | 42.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 145       | 67.44%  |
| Unknown | 37        | 17.21%  |
| Overlay | 14        | 6.51%   |
| Btrfs   | 14        | 6.51%   |
| Xfs     | 2         | 0.93%   |
| Tmpfs   | 1         | 0.47%   |
| F2fs    | 1         | 0.47%   |
| Ext2    | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 80        | 36.36%  |
| GPT     | 73        | 33.18%  |
| MBR     | 67        | 30.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 191       | 88.02%  |
| Yes       | 26        | 11.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 70.37%  |
| Yes       | 64        | 29.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 58        | 27.23%  |
| Lenovo              | 30        | 14.08%  |
| Hewlett-Packard     | 29        | 13.62%  |
| Gigabyte Technology | 17        | 7.98%   |
| Dell                | 15        | 7.04%   |
| Acer                | 12        | 5.63%   |
| Biostar             | 11        | 5.16%   |
| MSI                 | 6         | 2.82%   |
| ASRock              | 6         | 2.82%   |
| Toshiba             | 5         | 2.35%   |
| Timi                | 4         | 1.88%   |
| Samsung Electronics | 4         | 1.88%   |
| Sony                | 2         | 0.94%   |
| Apple               | 2         | 0.94%   |
| Unknown             | 2         | 0.94%   |
| Valve               | 1         | 0.47%   |
| System76            | 1         | 0.47%   |
| Jumper              | 1         | 0.47%   |
| Intel               | 1         | 0.47%   |
| HUAWEI              | 1         | 0.47%   |
| Google              | 1         | 0.47%   |
| Gateway             | 1         | 0.47%   |
| Foxconn             | 1         | 0.47%   |
| ECS                 | 1         | 0.47%   |
| Chuwi               | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Timi TM1701                                 | 3         | 1.41%   |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 1.41%   |
| Unknown                                     | 3         | 1.41%   |
| Samsung RV413/RV513                         | 2         | 0.94%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 0.94%   |
| HP ProBook 450 G7                           | 2         | 0.94%   |
| HP Compaq Presario CQ60                     | 2         | 0.94%   |
| Gigabyte H81M-S2PV                          | 2         | 0.94%   |
| ASUS VivoBook S15 X510UF                    | 2         | 0.94%   |
| ASUS H110M-R                                | 2         | 0.94%   |
| ASUS All Series                             | 2         | 0.94%   |
| Valve Jupiter                               | 1         | 0.47%   |
| Toshiba TECRA Z40-B                         | 1         | 0.47%   |
| Toshiba Satellite S50-B                     | 1         | 0.47%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.47%   |
| Toshiba Satellite C55D-A                    | 1         | 0.47%   |
| Toshiba Satellite A210                      | 1         | 0.47%   |
| Timi A35S                                   | 1         | 0.47%   |
| System76 Adder WS                           | 1         | 0.47%   |
| Sony VPCF13WFX                              | 1         | 0.47%   |
| Sony VPCEB1J8E                              | 1         | 0.47%   |
| Samsung R517/R717                           | 1         | 0.47%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.47%   |
| MSI Pro 3130 Microtower PC                  | 1         | 0.47%   |
| MSI MS-7695                                 | 1         | 0.47%   |
| MSI MS-7592                                 | 1         | 0.47%   |
| MSI MS-7529                                 | 1         | 0.47%   |
| MSI MS-7309                                 | 1         | 0.47%   |
| MSI CR610                                   | 1         | 0.47%   |
| Lenovo Yoga 730-15IKB 81CU                  | 1         | 0.47%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.47%   |
| Lenovo V580 20147                           | 1         | 0.47%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.47%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.47%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.47%   |
| Lenovo ThinkPad W520 4282BA9                | 1         | 0.47%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.47%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.47%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 11        | 5.16%   |
| Lenovo ThinkPad    | 9         | 4.23%   |
| Acer Aspire        | 9         | 4.23%   |
| ASUS VivoBook      | 8         | 3.76%   |
| HP ProBook         | 6         | 2.82%   |
| Dell Latitude      | 5         | 2.35%   |
| Dell Inspiron      | 5         | 2.35%   |
| Toshiba Satellite  | 4         | 1.88%   |
| Lenovo Legion      | 4         | 1.88%   |
| HP Pavilion        | 4         | 1.88%   |
| HP EliteBook       | 4         | 1.88%   |
| HP Compaq          | 4         | 1.88%   |
| ASUS PRIME         | 4         | 1.88%   |
| Timi TM1701        | 3         | 1.41%   |
| Unknown            | 3         | 1.41%   |
| Samsung RV413      | 2         | 0.94%   |
| HP ProDesk         | 2         | 0.94%   |
| HP Laptop          | 2         | 0.94%   |
| HP ENVY            | 2         | 0.94%   |
| Gigabyte Z690      | 2         | 0.94%   |
| Gigabyte H81M-S2PV | 2         | 0.94%   |
| Dell Vostro        | 2         | 0.94%   |
| ASUS ZenBook       | 2         | 0.94%   |
| ASUS TUF           | 2         | 0.94%   |
| ASUS P8H61-M       | 2         | 0.94%   |
| ASUS M5A78L-M      | 2         | 0.94%   |
| ASUS H110M-R       | 2         | 0.94%   |
| ASUS All           | 2         | 0.94%   |
| Valve Jupiter      | 1         | 0.47%   |
| Toshiba TECRA      | 1         | 0.47%   |
| Timi A35S          | 1         | 0.47%   |
| System76 Adder     | 1         | 0.47%   |
| Sony VPCF13WFX     | 1         | 0.47%   |
| Sony VPCEB1J8E     | 1         | 0.47%   |
| Samsung R517       | 1         | 0.47%   |
| Samsung 300E4C     | 1         | 0.47%   |
| MSI Pro            | 1         | 0.47%   |
| MSI MS-7695        | 1         | 0.47%   |
| MSI MS-7592        | 1         | 0.47%   |
| MSI MS-7529        | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 21        | 9.86%   |
| 2018 | 20        | 9.39%   |
| 2019 | 19        | 8.92%   |
| 2017 | 19        | 8.92%   |
| 2012 | 19        | 8.92%   |
| 2021 | 18        | 8.45%   |
| 2009 | 16        | 7.51%   |
| 2020 | 14        | 6.57%   |
| 2013 | 14        | 6.57%   |
| 2016 | 10        | 4.69%   |
| 2010 | 10        | 4.69%   |
| 2015 | 9         | 4.23%   |
| 2014 | 7         | 3.29%   |
| 2008 | 5         | 2.35%   |
| 2022 | 4         | 1.88%   |
| 2007 | 4         | 1.88%   |
| 2006 | 3         | 1.41%   |
| 2005 | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 130       | 61.03%  |
| Desktop     | 75        | 35.21%  |
| Mini pc     | 3         | 1.41%   |
| All in one  | 3         | 1.41%   |
| Convertible | 1         | 0.47%   |
| Server      | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 203       | 95.31%  |
| Enabled  | 10        | 4.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 212       | 99.53%  |
| Yes  | 1         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 60        | 27.91%  |
| 4.01-8.0    | 44        | 20.47%  |
| 8.01-16.0   | 41        | 19.07%  |
| 16.01-24.0  | 32        | 14.88%  |
| 32.01-64.0  | 15        | 6.98%   |
| 1.01-2.0    | 11        | 5.12%   |
| 2.01-3.0    | 8         | 3.72%   |
| 64.01-256.0 | 2         | 0.93%   |
| 24.01-32.0  | 1         | 0.47%   |
| 0.51-1.0    | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 84        | 36.68%  |
| 0.51-1.0   | 42        | 18.34%  |
| 2.01-3.0   | 41        | 17.9%   |
| 4.01-8.0   | 32        | 13.97%  |
| 3.01-4.0   | 19        | 8.3%    |
| 8.01-16.0  | 5         | 2.18%   |
| 0.01-0.5   | 3         | 1.31%   |
| 16.01-24.0 | 2         | 0.87%   |
| 24.01-32.0 | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 146       | 67.91%  |
| 2      | 47        | 21.86%  |
| 3      | 15        | 6.98%   |
| 4      | 5         | 2.33%   |
| 0      | 2         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 66.2%   |
| Yes       | 72        | 33.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 88.32%  |
| No        | 25        | 11.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 73.24%  |
| No        | 57        | 26.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 55.14%  |
| No        | 96        | 44.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Moldova | 213       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Chisinau        | 116       | 53.46%  |
| Tiraspol        | 44        | 20.28%  |
| Bălţi         | 7         | 3.23%   |
| Straseni        | 5         | 2.3%    |
| Tighina         | 4         | 1.84%   |
| Hincesti        | 3         | 1.38%   |
| Soroca          | 2         | 0.92%   |
| Orhei           | 2         | 0.92%   |
| Ialoveni        | 2         | 0.92%   |
| Căușeni       | 2         | 0.92%   |
| Cahul           | 2         | 0.92%   |
| Zaicana         | 1         | 0.46%   |
| Tvardița       | 1         | 0.46%   |
| Tintareni       | 1         | 0.46%   |
| Soldanesti      | 1         | 0.46%   |
| Sofia           | 1         | 0.46%   |
| Singera         | 1         | 0.46%   |
| Rîbniţa       | 1         | 0.46%   |
| Rezina          | 1         | 0.46%   |
| Rautel          | 1         | 0.46%   |
| Prajila         | 1         | 0.46%   |
| Pociumbeni      | 1         | 0.46%   |
| Nisporeni       | 1         | 0.46%   |
| Lapusna         | 1         | 0.46%   |
| Ilenuta         | 1         | 0.46%   |
| Gangura         | 1         | 0.46%   |
| Floresti        | 1         | 0.46%   |
| Floreni         | 1         | 0.46%   |
| Edineţ         | 1         | 0.46%   |
| Durlesti        | 1         | 0.46%   |
| Drochia         | 1         | 0.46%   |
| Donduseni       | 1         | 0.46%   |
| Criuleni        | 1         | 0.46%   |
| Crasnoarmeiscoe | 1         | 0.46%   |
| Congaz          | 1         | 0.46%   |
| Cojusna         | 1         | 0.46%   |
| Cenac           | 1         | 0.46%   |
| Cazanesti       | 1         | 0.46%   |
| Cantemir        | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 70     | 20.07%  |
| WDC                 | 37        | 39     | 12.59%  |
| Seagate             | 37        | 44     | 12.59%  |
| Toshiba             | 30        | 35     | 10.2%   |
| Hitachi             | 18        | 21     | 6.12%   |
| Kingston            | 17        | 20     | 5.78%   |
| SanDisk             | 11        | 12     | 3.74%   |
| SPCC                | 7         | 9      | 2.38%   |
| SK hynix            | 7         | 7      | 2.38%   |
| Micron Technology   | 6         | 8      | 2.04%   |
| Unknown             | 5         | 5      | 1.7%    |
| Transcend           | 5         | 5      | 1.7%    |
| Intel               | 5         | 7      | 1.7%    |
| HGST                | 4         | 4      | 1.36%   |
| Apacer              | 4         | 4      | 1.36%   |
| Netac               | 3         | 3      | 1.02%   |
| Maxtor              | 3         | 4      | 1.02%   |
| Crucial             | 3         | 4      | 1.02%   |
| Phison              | 2         | 3      | 0.68%   |
| OCZ                 | 2         | 2      | 0.68%   |
| GOODRAM             | 2         | 2      | 0.68%   |
| Fujitsu             | 2         | 2      | 0.68%   |
| China               | 2         | 2      | 0.68%   |
| A-DATA Technology   | 2         | 2      | 0.68%   |
| ZOTAC               | 1         | 3      | 0.34%   |
| XPG                 | 1         | 1      | 0.34%   |
| UMIS                | 1         | 1      | 0.34%   |
| Team                | 1         | 1      | 0.34%   |
| Solid State Storage | 1         | 1      | 0.34%   |
| PNY                 | 1         | 1      | 0.34%   |
| Patriot             | 1         | 1      | 0.34%   |
| O2 Micro            | 1         | 1      | 0.34%   |
| LITEONIT            | 1         | 1      | 0.34%   |
| Lite-On Technology  | 1         | 1      | 0.34%   |
| Leven               | 1         | 1      | 0.34%   |
| Lenovo              | 1         | 1      | 0.34%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.34%   |
| KIOXIA              | 1         | 1      | 0.34%   |
| KingDian            | 1         | 1      | 0.34%   |
| Intenso             | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SHFS37A120G 120GB SSD      | 7         | 2.31%   |
| Samsung NVMe SSD Drive 512GB        | 6         | 1.98%   |
| Toshiba MQ01ABD100 1TB              | 4         | 1.32%   |
| Toshiba DT01ACA050 500GB            | 4         | 1.32%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 1.32%   |
| Samsung SSD 860 EVO 500GB           | 4         | 1.32%   |
| Toshiba MQ04ABF100 1TB              | 3         | 0.99%   |
| Toshiba DT01ACA100 1TB              | 3         | 0.99%   |
| Seagate ST2000DM008-2FR102 2TB      | 3         | 0.99%   |
| SanDisk NVMe SSD Drive 512GB        | 3         | 0.99%   |
| Samsung MZVLW256HEHP-00000 256GB    | 3         | 0.99%   |
| Samsung HD502HJ 500GB               | 3         | 0.99%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 3         | 0.99%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 0.99%   |
| WDC WD5000AZRX-00A8LB0 500GB        | 2         | 0.66%   |
| WDC WD10SPZX-24Z10T0 1TB            | 2         | 0.66%   |
| WDC WD10SPZX-22Z10T1 1TB            | 2         | 0.66%   |
| Unknown MMC Card  64GB              | 2         | 0.66%   |
| Transcend TS64GSSD370S 64GB         | 2         | 0.66%   |
| Toshiba MQ01ACF032 320GB            | 2         | 0.66%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.66%   |
| Toshiba HDWD110 1TB                 | 2         | 0.66%   |
| SPCC Solid State Disk 128GB         | 2         | 0.66%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 0.66%   |
| Seagate ST9500325AS 500GB           | 2         | 0.66%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.66%   |
| Seagate ST4000VM000-2AF166 4TB      | 2         | 0.66%   |
| Seagate ST3160023A 160GB            | 2         | 0.66%   |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 0.66%   |
| SanDisk SD7UB3Q256G1001 256GB SSD   | 2         | 0.66%   |
| Samsung NVMe SSD Drive 256GB        | 2         | 0.66%   |
| Samsung HD251HJ 250GB               | 2         | 0.66%   |
| Samsung HD082GJ 80GB                | 2         | 0.66%   |
| Netac SSD 256GB                     | 2         | 0.66%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.66%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 0.66%   |
| Hitachi HTS542525K9SA00 250GB       | 2         | 0.66%   |
| Apacer AS340 240GB SSD              | 2         | 0.66%   |
| ZOTAC ZTSSD-S11-240G-P 240GB        | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 44     | 25.69%  |
| WDC                 | 35        | 37     | 24.31%  |
| Toshiba             | 25        | 30     | 17.36%  |
| Samsung Electronics | 19        | 22     | 13.19%  |
| Hitachi             | 18        | 21     | 12.5%   |
| HGST                | 4         | 4      | 2.78%   |
| Maxtor              | 3         | 4      | 2.08%   |
| Fujitsu             | 2         | 2      | 1.39%   |
| Unknown             | 1         | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 17     | 17.07%  |
| Kingston            | 14        | 17     | 17.07%  |
| SPCC                | 6         | 8      | 7.32%   |
| SanDisk             | 6         | 7      | 7.32%   |
| Transcend           | 5         | 5      | 6.1%    |
| Apacer              | 4         | 4      | 4.88%   |
| Micron Technology   | 3         | 3      | 3.66%   |
| Crucial             | 3         | 4      | 3.66%   |
| Toshiba             | 2         | 2      | 2.44%   |
| OCZ                 | 2         | 2      | 2.44%   |
| Netac               | 2         | 2      | 2.44%   |
| GOODRAM             | 2         | 2      | 2.44%   |
| China               | 2         | 2      | 2.44%   |
| ZOTAC               | 1         | 3      | 1.22%   |
| WDC                 | 1         | 1      | 1.22%   |
| Team                | 1         | 1      | 1.22%   |
| PNY                 | 1         | 1      | 1.22%   |
| Patriot             | 1         | 1      | 1.22%   |
| LITEONIT            | 1         | 1      | 1.22%   |
| Leven               | 1         | 1      | 1.22%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.22%   |
| KingDian            | 1         | 1      | 1.22%   |
| Intenso             | 1         | 1      | 1.22%   |
| Intel               | 1         | 1      | 1.22%   |
| Goldkey             | 1         | 1      | 1.22%   |
| Gigabyte Technology | 1         | 2      | 1.22%   |
| CHN25SATAS1         | 1         | 1      | 1.22%   |
| ASMT                | 1         | 1      | 1.22%   |
| AMD                 | 1         | 1      | 1.22%   |
| A-DATA Technology   | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 124       | 165    | 47.51%  |
| SSD  | 74        | 95     | 28.35%  |
| NVMe | 59        | 74     | 22.61%  |
| MMC  | 4         | 4      | 1.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 167       | 258    | 71.98%  |
| NVMe | 59        | 74     | 25.43%  |
| MMC  | 4         | 4      | 1.72%   |
| SAS  | 2         | 2      | 0.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 137       | 194    | 71.35%  |
| 0.51-1.0   | 41        | 52     | 21.35%  |
| 1.01-2.0   | 10        | 10     | 5.21%   |
| 3.01-4.0   | 3         | 3      | 1.56%   |
| 4.01-10.0  | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 62        | 27.68%  |
| 101-250        | 62        | 27.68%  |
| 501-1000       | 27        | 12.05%  |
| 51-100         | 25        | 11.16%  |
| 1-20           | 20        | 8.93%   |
| 1001-2000      | 9         | 4.02%   |
| 21-50          | 8         | 3.57%   |
| Unknown        | 6         | 2.68%   |
| 2001-3000      | 3         | 1.34%   |
| More than 3000 | 2         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 108       | 47.37%  |
| 21-50          | 34        | 14.91%  |
| 51-100         | 29        | 12.72%  |
| 101-250        | 22        | 9.65%   |
| 251-500        | 16        | 7.02%   |
| 501-1000       | 9         | 3.95%   |
| Unknown        | 6         | 2.63%   |
| 1001-2000      | 3         | 1.32%   |
| More than 3000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 6.25%   |
| Seagate ST3160023A 160GB          | 2         | 2      | 4.17%   |
| Samsung Electronics HD082GJ 80GB  | 2         | 2      | 4.17%   |
| Kingston SHFS37A120G 120GB SSD    | 2         | 4      | 4.17%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 4.17%   |
| WDC WD800JD-22LSA0 80GB           | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 2.08%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1         | 1      | 2.08%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1         | 1      | 2.08%   |
| WDC WD5000AADS-56S9B1 500GB       | 1         | 1      | 2.08%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 2.08%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1         | 1      | 2.08%   |
| WDC WD1600BEVS-60RST0 160GB       | 1         | 1      | 2.08%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 2.08%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 2.08%   |
| Team L5 LITE SSD 240GB            | 1         | 1      | 2.08%   |
| SPCC SSD162 120GB                 | 1         | 1      | 2.08%   |
| SPCC Solid State Disk 56GB        | 1         | 2      | 2.08%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.08%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 2.08%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1         | 1      | 2.08%   |
| Seagate ST31000340NS 1TB          | 1         | 1      | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB    | 1         | 1      | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 2.08%   |
| Seagate ST1000DL002-9TT153 1TB    | 1         | 1      | 2.08%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 2.08%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 2.08%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 2.08%   |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 2.08%   |
| Maxtor STM380215AS 80GB           | 1         | 1      | 2.08%   |
| Maxtor STM3160811AS 160GB         | 1         | 1      | 2.08%   |
| Maxtor STM3160211AS 160GB         | 1         | 1      | 2.08%   |
| Maxtor 4R120L0 122GB              | 1         | 1      | 2.08%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.08%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 2.08%   |
| Hitachi HDT721010SLA360 1TB       | 1         | 2      | 2.08%   |
| Hitachi HDP725050GLA360 500GB     | 1         | 1      | 2.08%   |
| Hitachi HDP725025GLA380 250GB     | 1         | 2      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 25.53%  |
| WDC                 | 9         | 9      | 19.15%  |
| Hitachi             | 7         | 9      | 14.89%  |
| Samsung Electronics | 5         | 5      | 10.64%  |
| Toshiba             | 3         | 3      | 6.38%   |
| Maxtor              | 3         | 4      | 6.38%   |
| SPCC                | 2         | 3      | 4.26%   |
| Kingston            | 2         | 4      | 4.26%   |
| Team                | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 30%     |
| WDC                 | 9         | 9      | 22.5%   |
| Hitachi             | 7         | 9      | 17.5%   |
| Samsung Electronics | 5         | 5      | 12.5%   |
| Toshiba             | 3         | 3      | 7.5%    |
| Maxtor              | 3         | 4      | 7.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 43     | 83.72%  |
| SSD  | 7         | 10     | 16.28%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 1      | 25%     |
| Seagate ST9250315AS 250GB         | 1         | 1      | 25%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 25%     |
| Samsung Electronics HD322GJ 320GB | 1         | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 108       | 164    | 45.96%  |
| Detected | 80        | 116    | 34.04%  |
| Malfunc  | 43        | 53     | 18.3%   |
| Failed   | 4         | 5      | 1.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 131       | 49.06%  |
| AMD                            | 56        | 20.97%  |
| Samsung Electronics            | 26        | 9.74%   |
| Nvidia                         | 10        | 3.75%   |
| SK hynix                       | 7         | 2.62%   |
| SanDisk                        | 6         | 2.25%   |
| JMicron Technology             | 5         | 1.87%   |
| Toshiba America Info Systems   | 3         | 1.12%   |
| Micron Technology              | 3         | 1.12%   |
| Kingston Technology Company    | 3         | 1.12%   |
| ASMedia Technology             | 3         | 1.12%   |
| Phison Electronics             | 2         | 0.75%   |
| ADATA Technology               | 2         | 0.75%   |
| Union Memory (Shenzhen)        | 1         | 0.37%   |
| Solid State Storage Technology | 1         | 0.37%   |
| Silicon Motion                 | 1         | 0.37%   |
| O2 Micro                       | 1         | 0.37%   |
| Netac Technology               | 1         | 0.37%   |
| Marvell Technology Group       | 1         | 0.37%   |
| Lite-On Technology             | 1         | 0.37%   |
| Lenovo                         | 1         | 0.37%   |
| KIOXIA                         | 1         | 0.37%   |
| Hewlett-Packard                | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28        | 8.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14        | 4.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 3.76%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 2.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.57%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 4         | 1.25%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.25%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 3         | 0.94%   |
| Micron NVMe Storage Controller                                                          | 3         | 0.94%   |
| JMicron JMB368 IDE controller                                                           | 3         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.94%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 0.94%   |
| AMD FCH IDE Controller                                                                  | 3         | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.63%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 159       | 56.99%  |
| NVMe | 59        | 21.15%  |
| IDE  | 51        | 18.28%  |
| RAID | 10        | 3.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 142       | 66.67%  |
| AMD    | 71        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.41%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.41%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.41%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.41%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.41%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.41%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 0.94%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.94%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.94%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 2         | 0.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.94%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.94%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.94%   |
| AMD Phenom II X6 1055T Processor              | 2         | 0.94%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.94%   |
| AMD Athlon II X2 280 Processor                | 2         | 0.94%   |
| Intel Xeon CPU E5405 @ 2.00GHz                | 1         | 0.47%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.47%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.47%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.47%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.47%   |
| Intel Pentium D CPU 2.66GHz                   | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 44        | 20.66%  |
| Intel Core i7                  | 23        | 10.8%   |
| Intel Core i3                  | 20        | 9.39%   |
| Intel Celeron                  | 17        | 7.98%   |
| Intel Pentium                  | 13        | 6.1%    |
| AMD Ryzen 5                    | 13        | 6.1%    |
| AMD Ryzen 7                    | 9         | 4.23%   |
| Other                          | 7         | 3.29%   |
| AMD Athlon II X2               | 7         | 3.29%   |
| Intel Core 2 Duo               | 5         | 2.35%   |
| AMD E                          | 5         | 2.35%   |
| AMD Athlon 64 X2               | 5         | 2.35%   |
| AMD A4                         | 4         | 1.88%   |
| Intel Pentium Silver           | 3         | 1.41%   |
| AMD Ryzen 3                    | 3         | 1.41%   |
| AMD FX                         | 3         | 1.41%   |
| AMD E1                         | 3         | 1.41%   |
| AMD A10                        | 3         | 1.41%   |
| Intel Pentium Dual-Core        | 2         | 0.94%   |
| Intel Pentium D                | 2         | 0.94%   |
| Intel Core i9                  | 2         | 0.94%   |
| AMD Sempron                    | 2         | 0.94%   |
| AMD Phenom II X6               | 2         | 0.94%   |
| AMD Athlon II X4               | 2         | 0.94%   |
| AMD Athlon                     | 2         | 0.94%   |
| Intel Xeon                     | 1         | 0.47%   |
| Intel Pentium Dual             | 1         | 0.47%   |
| Intel Pentium 4                | 1         | 0.47%   |
| Intel Core 2 Quad              | 1         | 0.47%   |
| Intel Atom                     | 1         | 0.47%   |
| AMD V140                       | 1         | 0.47%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.47%   |
| AMD Ryzen 9                    | 1         | 0.47%   |
| AMD Ryzen 5 PRO                | 1         | 0.47%   |
| AMD Phenom II X4               | 1         | 0.47%   |
| AMD A8                         | 1         | 0.47%   |
| AMD A6                         | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 98        | 45.79%  |
| 4       | 75        | 35.05%  |
| 6       | 16        | 7.48%   |
| 8       | 13        | 6.07%   |
| 1       | 5         | 2.34%   |
| Unknown | 4         | 1.87%   |
| 10      | 2         | 0.93%   |
| 12      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 212       | 99.53%  |
| 2      | 1         | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 115       | 53.74%  |
| 1       | 95        | 44.39%  |
| Unknown | 4         | 1.87%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 210       | 98.59%  |
| Unknown        | 3         | 1.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 16.82%  |
| 0x206a7    | 13        | 6.07%   |
| 0x806ea    | 11        | 5.14%   |
| 0x306c3    | 9         | 4.21%   |
| 0x05000119 | 8         | 3.74%   |
| 0x806ec    | 7         | 3.27%   |
| 0x306a9    | 7         | 3.27%   |
| 0x010000c8 | 7         | 3.27%   |
| 0x906e9    | 6         | 2.8%    |
| 0x08600106 | 5         | 2.34%   |
| 0x906ea    | 4         | 1.87%   |
| 0x706a1    | 4         | 1.87%   |
| 0x506e3    | 4         | 1.87%   |
| 0x406e3    | 4         | 1.87%   |
| 0x40651    | 4         | 1.87%   |
| 0x306d4    | 4         | 1.87%   |
| 0x1067a    | 4         | 1.87%   |
| 0x806e9    | 3         | 1.4%    |
| 0x6fd      | 3         | 1.4%    |
| 0x506c9    | 3         | 1.4%    |
| 0x0a50000c | 3         | 1.4%    |
| 0x08108109 | 3         | 1.4%    |
| 0x03000027 | 3         | 1.4%    |
| 0xf47      | 2         | 0.93%   |
| 0xa0655    | 2         | 0.93%   |
| 0xa0652    | 2         | 0.93%   |
| 0x90672    | 2         | 0.93%   |
| 0x806c1    | 2         | 0.93%   |
| 0x706e5    | 2         | 0.93%   |
| 0x706a8    | 2         | 0.93%   |
| 0x406c4    | 2         | 0.93%   |
| 0x406c3    | 2         | 0.93%   |
| 0x30678    | 2         | 0.93%   |
| 0x106e5    | 2         | 0.93%   |
| 0x10676    | 2         | 0.93%   |
| 0x08701021 | 2         | 0.93%   |
| 0x08608103 | 2         | 0.93%   |
| 0x08108102 | 2         | 0.93%   |
| 0x06001119 | 2         | 0.93%   |
| 0x06000852 | 2         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 16.9%   |
| SandyBridge      | 16        | 7.51%   |
| Haswell          | 16        | 7.51%   |
| K10              | 14        | 6.57%   |
| Zen 2            | 11        | 5.16%   |
| Skylake          | 10        | 4.69%   |
| Bobcat           | 8         | 3.76%   |
| Silvermont       | 7         | 3.29%   |
| IvyBridge        | 7         | 3.29%   |
| Goldmont plus    | 7         | 3.29%   |
| Zen+             | 6         | 2.82%   |
| Zen 3            | 6         | 2.82%   |
| Penryn           | 6         | 2.82%   |
| Piledriver       | 5         | 2.35%   |
| K8 Hammer        | 5         | 2.35%   |
| Core             | 5         | 2.35%   |
| Broadwell        | 5         | 2.35%   |
| NetBurst         | 4         | 1.88%   |
| K10 Llano        | 4         | 1.88%   |
| Icelake          | 4         | 1.88%   |
| CometLake        | 4         | 1.88%   |
| Unknown          | 4         | 1.88%   |
| Zen              | 3         | 1.41%   |
| TigerLake        | 3         | 1.41%   |
| K8 & K10 hybrid  | 3         | 1.41%   |
| Goldmont         | 3         | 1.41%   |
| Westmere         | 2         | 0.94%   |
| Nehalem          | 2         | 0.94%   |
| Alderlake Hybrid | 2         | 0.94%   |
| Tremont          | 1         | 0.47%   |
| Steamroller      | 1         | 0.47%   |
| Puma             | 1         | 0.47%   |
| Bulldozer        | 1         | 0.47%   |
| Bonnell          | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 115       | 45.45%  |
| Nvidia | 69        | 27.27%  |
| AMD    | 69        | 27.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 5.77%   |
| Intel UHD Graphics 620                                                                   | 11        | 4.23%   |
| AMD Renoir                                                                               | 8         | 3.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.92%   |
| Intel HD Graphics 630                                                                    | 5         | 1.92%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.92%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.54%   |
| Intel HD Graphics 620                                                                    | 4         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.15%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 1.15%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3         | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.15%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.15%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.15%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.15%   |
| Nvidia TU117M                                                                            | 2         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.77%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.77%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.77%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.77%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.77%   |
| Intel HD Graphics 530                                                                    | 2         | 0.77%   |
| Intel HD Graphics 500                                                                    | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 82        | 37.96%  |
| 1 x AMD        | 54        | 25%     |
| 1 x Nvidia     | 38        | 17.59%  |
| Intel + Nvidia | 26        | 12.04%  |
| 2 x AMD        | 6         | 2.78%   |
| AMD + Nvidia   | 5         | 2.31%   |
| Intel + AMD    | 4         | 1.85%   |
| Other          | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 177       | 80.09%  |
| Proprietary | 31        | 14.03%  |
| Unknown     | 13        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 44.84%  |
| 0.01-0.5   | 46        | 20.63%  |
| 1.01-2.0   | 41        | 18.39%  |
| 3.01-4.0   | 16        | 7.17%   |
| 0.51-1.0   | 13        | 5.83%   |
| 7.01-8.0   | 4         | 1.79%   |
| 5.01-6.0   | 2         | 0.9%    |
| 2.01-3.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 15.35%  |
| AU Optronics            | 33        | 14.47%  |
| Chimei Innolux          | 23        | 10.09%  |
| LG Display              | 22        | 9.65%   |
| Philips                 | 17        | 7.46%   |
| Goldstar                | 17        | 7.46%   |
| BOE                     | 14        | 6.14%   |
| Dell                    | 11        | 4.82%   |
| Acer                    | 8         | 3.51%   |
| AOC                     | 6         | 2.63%   |
| Chi Mei Optoelectronics | 5         | 2.19%   |
| InfoVision              | 4         | 1.75%   |
| Hewlett-Packard         | 4         | 1.75%   |
| Sharp                   | 3         | 1.32%   |
| PANDA                   | 3         | 1.32%   |
| Lenovo                  | 3         | 1.32%   |
| BenQ                    | 3         | 1.32%   |
| CSO                     | 2         | 0.88%   |
| Apple                   | 2         | 0.88%   |
| ViewSonic               | 1         | 0.44%   |
| Valve                   | 1         | 0.44%   |
| Toshiba                 | 1         | 0.44%   |
| Sony                    | 1         | 0.44%   |
| Plain Tree Systems      | 1         | 0.44%   |
| Medion                  | 1         | 0.44%   |
| LG Electronics          | 1         | 0.44%   |
| KTC                     | 1         | 0.44%   |
| ITE                     | 1         | 0.44%   |
| Hitachi                 | 1         | 0.44%   |
| HannStar                | 1         | 0.44%   |
| ASUSTek Computer        | 1         | 0.44%   |
| Ancor Communications    | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 1.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 4         | 1.72%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 3         | 1.29%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 3         | 1.29%   |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch | 2         | 0.86%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.86%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 2         | 0.86%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.86%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2         | 0.86%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 2         | 0.86%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 2         | 0.86%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.86%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 2         | 0.86%   |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch               | 1         | 0.43%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.43%   |
| Toshiba TV TSB0108 1920x540                                          | 1         | 0.43%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch | 1         | 0.43%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch               | 1         | 0.43%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch  | 1         | 0.43%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch    | 1         | 0.43%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch     | 1         | 0.43%   |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch    | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 91        | 41.94%  |
| 1366x768 (WXGA)    | 51        | 23.5%   |
| 1600x900 (HD+)     | 14        | 6.45%   |
| 1280x1024 (SXGA)   | 13        | 5.99%   |
| 2560x1440 (QHD)    | 12        | 5.53%   |
| 3840x2160 (4K)     | 6         | 2.76%   |
| 1680x1050 (WSXGA+) | 6         | 2.76%   |
| 1440x900 (WXGA+)   | 5         | 2.3%    |
| 1280x800 (WXGA)    | 4         | 1.84%   |
| 2560x1600          | 2         | 0.92%   |
| 2560x1080          | 2         | 0.92%   |
| 1600x1200          | 2         | 0.92%   |
| 1024x768 (XGA)     | 2         | 0.92%   |
| 800x1280           | 1         | 0.46%   |
| 3456x2160          | 1         | 0.46%   |
| 3200x1080          | 1         | 0.46%   |
| 2160x1440          | 1         | 0.46%   |
| 1920x540           | 1         | 0.46%   |
| 1360x768           | 1         | 0.46%   |
| Unknown            | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 97        | 42.17%  |
| 24      | 15        | 6.52%   |
| 23      | 15        | 6.52%   |
| 21      | 14        | 6.09%   |
| 27      | 13        | 5.65%   |
| 17      | 13        | 5.65%   |
| 19      | 11        | 4.78%   |
| 14      | 10        | 4.35%   |
| 20      | 9         | 3.91%   |
| 18      | 7         | 3.04%   |
| 13      | 7         | 3.04%   |
| 11      | 4         | 1.74%   |
| 84      | 2         | 0.87%   |
| 72      | 2         | 0.87%   |
| 34      | 2         | 0.87%   |
| 16      | 2         | 0.87%   |
| 12      | 2         | 0.87%   |
| 32      | 1         | 0.43%   |
| 31      | 1         | 0.43%   |
| 22      | 1         | 0.43%   |
| 7       | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 117       | 51.54%  |
| 501-600     | 39        | 17.18%  |
| 401-500     | 36        | 15.86%  |
| 351-400     | 14        | 6.17%   |
| 201-300     | 10        | 4.41%   |
| 1501-2000   | 4         | 1.76%   |
| 701-800     | 3         | 1.32%   |
| 601-700     | 2         | 0.88%   |
| 1-100       | 1         | 0.44%   |
| Unknown     | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 164       | 80.39%  |
| 16/10   | 15        | 7.35%   |
| 5/4     | 11        | 5.39%   |
| 4/3     | 8         | 3.92%   |
| 3/2     | 2         | 0.98%   |
| 21/9    | 2         | 0.98%   |
| 0.67    | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 40.79%  |
| 201-250        | 40        | 17.54%  |
| 151-200        | 24        | 10.53%  |
| 81-90          | 15        | 6.58%   |
| 301-350        | 13        | 5.7%    |
| 141-150        | 12        | 5.26%   |
| 111-120        | 6         | 2.63%   |
| 121-130        | 5         | 2.19%   |
| More than 1000 | 4         | 1.75%   |
| 51-60          | 4         | 1.75%   |
| 351-500        | 4         | 1.75%   |
| 71-80          | 2         | 0.88%   |
| 61-70          | 2         | 0.88%   |
| 131-140        | 2         | 0.88%   |
| 1-40           | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 78        | 34.82%  |
| 121-160       | 68        | 30.36%  |
| 101-120       | 65        | 29.02%  |
| 161-240       | 8         | 3.57%   |
| More than 240 | 2         | 0.89%   |
| 1-50          | 2         | 0.89%   |
| Unknown       | 1         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 181       | 84.19%  |
| 2     | 29        | 13.49%  |
| 0     | 5         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 138       | 44.52%  |
| Intel                             | 68        | 21.94%  |
| Qualcomm Atheros                  | 48        | 15.48%  |
| Broadcom                          | 14        | 4.52%   |
| Nvidia                            | 9         | 2.9%    |
| Xiaomi                            | 4         | 1.29%   |
| Ralink                            | 4         | 1.29%   |
| MediaTek                          | 4         | 1.29%   |
| Broadcom Limited                  | 4         | 1.29%   |
| Marvell Technology Group          | 3         | 0.97%   |
| TP-Link                           | 2         | 0.65%   |
| Sierra Wireless                   | 1         | 0.32%   |
| Qualcomm                          | 1         | 0.32%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.32%   |
| Mercucys                          | 1         | 0.32%   |
| JMicron Technology                | 1         | 0.32%   |
| ICS Advent                        | 1         | 0.32%   |
| Huawei Technologies               | 1         | 0.32%   |
| Hewlett-Packard                   | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| D-Link System                     | 1         | 0.32%   |
| D-Link                            | 1         | 0.32%   |
| ASIX Electronics                  | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 100       | 27.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 5.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.79%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.23%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.12%   |
| Nvidia MCP77 Ethernet                                                   | 4         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.84%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.84%   |
| Intel Wireless 7260                                                     | 3         | 0.84%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.84%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.84%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.56%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.56%   |
| Intel Wireless 8260                                                     | 2         | 0.56%   |
| Intel Wireless 7265                                                     | 2         | 0.56%   |
| Intel Wireless 3160                                                     | 2         | 0.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.56%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 35.22%  |
| Qualcomm Atheros      | 42        | 26.42%  |
| Realtek Semiconductor | 37        | 23.27%  |
| Broadcom              | 10        | 6.29%   |
| Ralink                | 4         | 2.52%   |
| MediaTek              | 3         | 1.89%   |
| TP-Link               | 2         | 1.26%   |
| Sierra Wireless       | 1         | 0.63%   |
| Mercucys              | 1         | 0.63%   |
| D-Link System         | 1         | 0.63%   |
| D-Link                | 1         | 0.63%   |
| Broadcom Limited      | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 6.29%   |
| Intel Wireless 8265 / 8275                                              | 10        | 6.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 5.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 5.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 5.03%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.89%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.89%   |
| Intel Wireless 7260                                                     | 3         | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.26%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.26%   |
| Intel Wireless 8260                                                     | 2         | 1.26%   |
| Intel Wireless 7265                                                     | 2         | 1.26%   |
| Intel Wireless 3160                                                     | 2         | 1.26%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.26%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.26%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.26%   |
| Sierra Wireless EM7455                                                  | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 126       | 64.62%  |
| Intel                    | 30        | 15.38%  |
| Nvidia                   | 9         | 4.62%   |
| Qualcomm Atheros         | 8         | 4.1%    |
| Broadcom                 | 5         | 2.56%   |
| Xiaomi                   | 4         | 2.05%   |
| Marvell Technology Group | 3         | 1.54%   |
| Broadcom Limited         | 3         | 1.54%   |
| Qualcomm                 | 1         | 0.51%   |
| MediaTek                 | 1         | 0.51%   |
| JMicron Technology       | 1         | 0.51%   |
| ICS Advent               | 1         | 0.51%   |
| Huawei Technologies      | 1         | 0.51%   |
| Hewlett-Packard          | 1         | 0.51%   |
| ASIX Electronics         | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 100       | 50.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 10.66%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 2.03%   |
| Nvidia MCP77 Ethernet                                                          | 4         | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.52%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.52%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.52%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.02%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.02%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.02%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.02%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.51%   |
| Qualcomm Redmi Note 9 Pro                                                      | 1         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.51%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.51%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.51%   |
| MediaTek TECNO SPARK 9T                                                        | 1         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.51%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.51%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.51%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.51%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189       | 54.47%  |
| WiFi     | 156       | 44.96%  |
| Modem    | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 53.24%  |
| Ethernet | 101       | 46.76%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 121       | 56.81%  |
| 1     | 92        | 43.19%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 205       | 96.24%  |
| Yes  | 8         | 3.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 39.83%  |
| IMC Networks                    | 16        | 13.56%  |
| Realtek Semiconductor           | 14        | 11.86%  |
| Qualcomm Atheros Communications | 13        | 11.02%  |
| Lite-On Technology              | 5         | 4.24%   |
| Broadcom                        | 5         | 4.24%   |
| Foxconn / Hon Hai               | 4         | 3.39%   |
| Cambridge Silicon Radio         | 4         | 3.39%   |
| Apple                           | 2         | 1.69%   |
| Toshiba                         | 1         | 0.85%   |
| Realtek                         | 1         | 0.85%   |
| Ralink Technology               | 1         | 0.85%   |
| ISSC                            | 1         | 0.85%   |
| Integrated System Solution      | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |
| Dell                            | 1         | 0.85%   |
| ASUSTek Computer                | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 16.1%   |
| Realtek Bluetooth Radio                                                             | 11        | 9.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 7.63%   |
| Intel AX201 Bluetooth                                                               | 9         | 7.63%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 6.78%   |
| Intel AX200 Bluetooth                                                               | 7         | 5.93%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 5.08%   |
| IMC Networks Bluetooth Device                                                       | 4         | 3.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.54%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.69%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.69%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.69%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.85%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.85%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.85%   |
| Ralink CSR BS8510                                                                   | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.85%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.85%   |
| ISSC Bluetooth Device                                                               | 1         | 0.85%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 0.85%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.85%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.85%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.85%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.85%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.85%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.85%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.85%   |
| ASUS BCM20702A0                                                                     | 1         | 0.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.85%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 139       | 50.36%  |
| AMD                       | 73        | 26.45%  |
| Nvidia                    | 47        | 17.03%  |
| Plantronics               | 3         | 1.09%   |
| Logitech                  | 2         | 0.72%   |
| Creative Labs             | 2         | 0.72%   |
| C-Media Electronics       | 2         | 0.72%   |
| Texas Instruments         | 1         | 0.36%   |
| SteelSeries ApS           | 1         | 0.36%   |
| Shenzhen Rapoo Technology | 1         | 0.36%   |
| Sennheiser Communications | 1         | 0.36%   |
| Kingston Technology       | 1         | 0.36%   |
| GN Netcom                 | 1         | 0.36%   |
| Giga-Byte Technology      | 1         | 0.36%   |
| Fifine Microphones        | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 6.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 6.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 5.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.86%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 2.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.67%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.48%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.48%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.19%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 4         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.19%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.19%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.89%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 37        | 21.64%  |
| Samsung Electronics   | 35        | 20.47%  |
| Kingston              | 22        | 12.87%  |
| SK hynix              | 20        | 11.7%   |
| Micron Technology     | 10        | 5.85%   |
| Goodram               | 7         | 4.09%   |
| Unknown (ABCD)        | 3         | 1.75%   |
| Transcend             | 3         | 1.75%   |
| G.Skill               | 3         | 1.75%   |
| Elpida                | 3         | 1.75%   |
| Crucial               | 3         | 1.75%   |
| Corsair               | 3         | 1.75%   |
| Ramaxel Technology    | 2         | 1.17%   |
| Patriot               | 2         | 1.17%   |
| Nanya Technology      | 2         | 1.17%   |
| Apacer                | 2         | 1.17%   |
| A-DATA Technology     | 2         | 1.17%   |
| Unifosa               | 1         | 0.58%   |
| Team                  | 1         | 0.58%   |
| Silicon Power         | 1         | 0.58%   |
| SGS/Thomson           | 1         | 0.58%   |
| Kingmax Semiconductor | 1         | 0.58%   |
| Hexon                 | 1         | 0.58%   |
| Goldkey               | 1         | 0.58%   |
| Axiom                 | 1         | 0.58%   |
| AVEXIR                | 1         | 0.58%   |
| Avant                 | 1         | 0.58%   |
| ASint Technology      | 1         | 0.58%   |
| Unknown               | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 3         | 1.59%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 1.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.59%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 1.06%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 2         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 2         | 1.06%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 1.06%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 1.06%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                      | 2         | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.06%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.06%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.06%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s            | 2         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.06%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 2         | 1.06%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                     | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM                                   | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 53        | 34.87%  |
| DDR4    | 51        | 33.55%  |
| DDR2    | 13        | 8.55%   |
| Unknown | 11        | 7.24%   |
| SDRAM   | 10        | 6.58%   |
| LPDDR4  | 6         | 3.95%   |
| DDR     | 3         | 1.97%   |
| LPDDR3  | 2         | 1.32%   |
| DRAM    | 2         | 1.32%   |
| DDR5    | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 51.02%  |
| DIMM         | 64        | 43.54%  |
| Row Of Chips | 7         | 4.76%   |
| FB-DIMM      | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 54        | 31.76%  |
| 2048  | 39        | 22.94%  |
| 8192  | 38        | 22.35%  |
| 16384 | 19        | 11.18%  |
| 1024  | 15        | 8.82%   |
| 32768 | 4         | 2.35%   |
| 512   | 1         | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 23.46%  |
| 2667    | 24        | 14.81%  |
| 1333    | 18        | 11.11%  |
| 3200    | 12        | 7.41%   |
| 2400    | 7         | 4.32%   |
| 2133    | 7         | 4.32%   |
| 800     | 7         | 4.32%   |
| 667     | 6         | 3.7%    |
| 1334    | 5         | 3.09%   |
| Unknown | 5         | 3.09%   |
| 400     | 4         | 2.47%   |
| 3600    | 3         | 1.85%   |
| 3266    | 3         | 1.85%   |
| 2048    | 3         | 1.85%   |
| 333     | 3         | 1.85%   |
| 4199    | 2         | 1.23%   |
| 3000    | 2         | 1.23%   |
| 2933    | 2         | 1.23%   |
| 1067    | 2         | 1.23%   |
| 6000    | 1         | 0.62%   |
| 4800    | 1         | 0.62%   |
| 3500    | 1         | 0.62%   |
| 2800    | 1         | 0.62%   |
| 2666    | 1         | 0.62%   |
| 1867    | 1         | 0.62%   |
| 1400    | 1         | 0.62%   |
| 975     | 1         | 0.62%   |
| 533     | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 19.58%  |
| IMC Networks                           | 25        | 17.48%  |
| Realtek Semiconductor                  | 12        | 8.39%   |
| Microdia                               | 11        | 7.69%   |
| Logitech                               | 8         | 5.59%   |
| Quanta                                 | 7         | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.5%    |
| Sunplus Innovation Technology          | 4         | 2.8%    |
| Bison Electronics                      | 4         | 2.8%    |
| Acer                                   | 4         | 2.8%    |
| Z-Star Microelectronics                | 3         | 2.1%    |
| Syntek                                 | 3         | 2.1%    |
| Silicon Motion                         | 3         | 2.1%    |
| Lite-On Technology                     | 3         | 2.1%    |
| Suyin                                  | 2         | 1.4%    |
| Samsung Electronics                    | 2         | 1.4%    |
| Luxvisions Innotech Limited            | 2         | 1.4%    |
| KYE Systems (Mouse Systems)            | 2         | 1.4%    |
| Apple                                  | 2         | 1.4%    |
| Alcor Micro                            | 2         | 1.4%    |
| Trust                                  | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| Pixart Imaging                         | 1         | 0.7%    |
| Microsoft                              | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| HD WEBCAM                              | 1         | 0.7%    |
| Genesys Logic                          | 1         | 0.7%    |
| GEMBIRD                                | 1         | 0.7%    |
| ezcap                                  | 1         | 0.7%    |
| Cubeternet                             | 1         | 0.7%    |
| Aveo Technology                        | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 4.2%    |
| IMC Networks USB2.0 HD UVC WebCam                            | 6         | 4.2%    |
| Chicony Integrated Camera                                    | 6         | 4.2%    |
| Logitech Webcam C270                                         | 4         | 2.8%    |
| IMC Networks Integrated Camera                               | 4         | 2.8%    |
| Realtek Integrated_Webcam_HD                                 | 3         | 2.1%    |
| Quanta HP HD Camera                                          | 3         | 2.1%    |
| Microdia Integrated_Webcam_HD                                | 3         | 2.1%    |
| Microdia Camera                                              | 3         | 2.1%    |
| Chicony HD WebCam                                            | 3         | 2.1%    |
| Z-Star Venus USB2.0 Camera                                   | 2         | 1.4%    |
| Syntek Lenovo EasyCamera                                     | 2         | 1.4%    |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.4%    |
| Realtek USB Camera                                           | 2         | 1.4%    |
| Quanta HP TrueVision HD Camera                               | 2         | 1.4%    |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.4%    |
| Lite-On HP HD Camera                                         | 2         | 1.4%    |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.4%    |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.4%    |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.4%    |
| Chicony EasyCamera                                           | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 1.4%    |
| Acer Integrated Camera                                       | 2         | 1.4%    |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.7%    |
| Trust Full HD Webcam                                         | 1         | 0.7%    |
| Syntek Integrated Camera                                     | 1         | 0.7%    |
| Suyin HP Truevision HD                                       | 1         | 0.7%    |
| Suyin HD WebCam                                              | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.7%    |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.7%    |
| Sunplus HD WebCam                                            | 1         | 0.7%    |
| Sunplus Asus Webcam                                          | 1         | 0.7%    |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)                      | 1         | 0.7%    |
| Samsung Galaxy (PTP mode)                                    | 1         | 0.7%    |
| Ricoh Sony Visual Communication Camera                       | 1         | 0.7%    |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.7%    |
| Realtek TOSHIBA Web Camera                                   | 1         | 0.7%    |
| Realtek Integrated Webcam_HD                                 | 1         | 0.7%    |
| Realtek Integrated Webcam HD                                 | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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
| Synaptics UWP WBDI                                         | 1         | 3.57%   |
| Synaptics  WBDI                                            | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.57%   |
| Elan ELAN:ARM-M4                                           | 1         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| O2 Micro              | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 165       | 74.66%  |
| 1     | 46        | 20.81%  |
| 2     | 9         | 4.07%   |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 28        | 44.44%  |
| Graphics card         | 22        | 34.92%  |
| Net/wireless          | 5         | 7.94%   |
| Multimedia controller | 2         | 3.17%   |
| Chipcard              | 2         | 3.17%   |
| Camera                | 2         | 3.17%   |
| Storage               | 1         | 1.59%   |
| Sound                 | 1         | 1.59%   |

