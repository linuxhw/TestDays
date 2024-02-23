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

Total: 326

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek  | ROG Strix G713RW_G713RW     | Notebook    | [20827e6f82](https://linux-hardware.org/?probe=20827e6f82) | Jan 26, 2024 |
| Gigabyte | H61M-S1                     | Desktop     | [b0ac9a9edd](https://linux-hardware.org/?probe=b0ac9a9edd) | Jan 24, 2024 |
| HP       | 83DD                        | Mini pc     | [3a9b84ded5](https://linux-hardware.org/?probe=3a9b84ded5) | Jan 21, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X415... | Notebook    | [1427f84afd](https://linux-hardware.org/?probe=1427f84afd) | Jan 18, 2024 |
| Lenovo   | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [123bf2b824](https://linux-hardware.org/?probe=123bf2b824) | Jan 17, 2024 |
| Lenovo   | IdeaPad 310-15ISK 80SM      | Notebook    | [8494044b32](https://linux-hardware.org/?probe=8494044b32) | Jan 11, 2024 |
| Lenovo   | LOQ 15IRH8 82XV             | Notebook    | [494b496889](https://linux-hardware.org/?probe=494b496889) | Jan 01, 2024 |
| ASUSTek  | UX32VD                      | Notebook    | [e073ccab15](https://linux-hardware.org/?probe=e073ccab15) | Dec 13, 2023 |
| Lenovo   | Z51-70 80K6                 | Notebook    | [2894d2f78d](https://linux-hardware.org/?probe=2894d2f78d) | Dec 06, 2023 |
| Gigabyte | G41MT-S2                    | Desktop     | [06a0da716b](https://linux-hardware.org/?probe=06a0da716b) | Dec 05, 2023 |
| Apple    | MacBookPro9,2               | Notebook    | [c120b25f0f](https://linux-hardware.org/?probe=c120b25f0f) | Nov 17, 2023 |
| HP       | 250 G8 Notebook PC          | Notebook    | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| HP       | ProBook 4320s               | Notebook    | [0da6b1026b](https://linux-hardware.org/?probe=0da6b1026b) | Nov 15, 2023 |
| ASUSTek  | ROG Strix G712LU_G712LU     | Notebook    | [50087ec971](https://linux-hardware.org/?probe=50087ec971) | Oct 08, 2023 |
| ASUSTek  | ROG Strix G712LU_G712LU     | Notebook    | [6f7b1474d0](https://linux-hardware.org/?probe=6f7b1474d0) | Oct 06, 2023 |
| Lenovo   | ThinkBook 15-IML 20RW       | Notebook    | [a8c067b868](https://linux-hardware.org/?probe=a8c067b868) | Sep 22, 2023 |
| Lenovo   | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [367454b6bc](https://linux-hardware.org/?probe=367454b6bc) | Sep 16, 2023 |
| Dell     | Latitude 7490               | Notebook    | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [ded378b5da](https://linux-hardware.org/?probe=ded378b5da) | Aug 30, 2023 |
| Timi     | A34R                        | Notebook    | [f2998bab84](https://linux-hardware.org/?probe=f2998bab84) | Aug 25, 2023 |
| Dell     | Latitude 7490               | Notebook    | [90685f1b4d](https://linux-hardware.org/?probe=90685f1b4d) | Aug 21, 2023 |
| Dell     | Inspiron 15 7000 Gaming     | Notebook    | [7da49ac1c3](https://linux-hardware.org/?probe=7da49ac1c3) | Aug 17, 2023 |
| Dell     | Latitude 7490               | Notebook    | [efb4abea09](https://linux-hardware.org/?probe=efb4abea09) | Aug 16, 2023 |
| ASUSTek  | ROG Strix G713RW_G713RW     | Notebook    | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| ASUSTek  | TUF B450-PRO GAMING         | Desktop     | [0c0067ae1b](https://linux-hardware.org/?probe=0c0067ae1b) | Jul 30, 2023 |
| Gigabyte | G41MT-S2                    | Desktop     | [d625267663](https://linux-hardware.org/?probe=d625267663) | Jul 17, 2023 |
| HP       | Spectre x360 2-in-1 Lapt... | Convertible | [c7a5d0ef6c](https://linux-hardware.org/?probe=c7a5d0ef6c) | Jun 29, 2023 |
| HP       | EliteBook 850 G1            | Notebook    | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP       | EliteBook 850 G1            | Notebook    | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP       | EliteBook 850 G1            | Notebook    | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| Dell     | Vostro 3525                 | Notebook    | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| Acer     | AOD257                      | Notebook    | [d3510be962](https://linux-hardware.org/?probe=d3510be962) | Jun 18, 2023 |
| Lenovo   | 375A No DPK                 | All in one  | [c7bf49d8e9](https://linux-hardware.org/?probe=c7bf49d8e9) | Jun 15, 2023 |
| Dell     | Vostro 3525                 | Notebook    | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
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
| ROSA R10            | 21        | 8.4%    |
| Ubuntu 20.04        | 15        | 6%      |
| Ubuntu 18.04        | 15        | 6%      |
| ROSA R11            | 14        | 5.6%    |
| Ubuntu 22.04        | 10        | 4%      |
| ROSA R8             | 10        | 4%      |
| ROSA R11.1          | 10        | 4%      |
| ROSA R8.1           | 8         | 3.2%    |
| Arch Rolling        | 7         | 2.8%    |
| OpenMandriva 4.2    | 6         | 2.4%    |
| OpenMandriva 4.3    | 5         | 2%      |
| Linux Mint 21.1     | 5         | 2%      |
| Linux Mint 20.1     | 5         | 2%      |
| KDE neon 20.04      | 5         | 2%      |
| ROSA R9             | 4         | 1.6%    |
| ROSA 12.2           | 4         | 1.6%    |
| Manjaro             | 4         | 1.6%    |
| Arch                | 4         | 1.6%    |
| Ubuntu 22.10        | 3         | 1.2%    |
| ROSA 12.3           | 3         | 1.2%    |
| Linux Mint 19.1     | 3         | 1.2%    |
| Fedora 36           | 3         | 1.2%    |
| Fedora 34           | 3         | 1.2%    |
| Zorin 16            | 2         | 0.8%    |
| Ubuntu 19.10        | 2         | 0.8%    |
| Ubuntu 16.04        | 2         | 0.8%    |
| ROSA 12.1           | 2         | 0.8%    |
| Pop!_OS 21.04       | 2         | 0.8%    |
| Pop!_OS 20.10       | 2         | 0.8%    |
| OpenMandriva 23.08  | 2         | 0.8%    |
| Linux Mint 21.2     | 2         | 0.8%    |
| Linux Mint 20.2     | 2         | 0.8%    |
| Linux Mint 20       | 2         | 0.8%    |
| Linux Mint 19.3     | 2         | 0.8%    |
| EndeavourOS Rolling | 2         | 0.8%    |
| Debian 12           | 2         | 0.8%    |
| Debian 11           | 2         | 0.8%    |
| BlackPanther 18.1   | 2         | 0.8%    |
| Ubuntu MATE 22.04   | 1         | 0.4%    |
| Ubuntu Budgie 23.04 | 1         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 69        | 28.87%  |
| Ubuntu        | 52        | 21.76%  |
| Linux Mint    | 22        | 9.21%   |
| OpenMandriva  | 15        | 6.28%   |
| Fedora        | 12        | 5.02%   |
| Manjaro       | 11        | 4.6%    |
| Arch          | 11        | 4.6%    |
| Pop!_OS       | 7         | 2.93%   |
| KDE neon      | 6         | 2.51%   |
| Kali          | 5         | 2.09%   |
| Debian        | 5         | 2.09%   |
| Endless       | 4         | 1.67%   |
| Zorin         | 2         | 0.84%   |
| SteamOS       | 2         | 0.84%   |
| Kubuntu       | 2         | 0.84%   |
| EndeavourOS   | 2         | 0.84%   |
| BuildRoot     | 2         | 0.84%   |
| BlackPanther  | 2         | 0.84%   |
| Ubuntu MATE   | 1         | 0.42%   |
| Ubuntu Budgie | 1         | 0.42%   |
| Nobara        | 1         | 0.42%   |
| Lubuntu       | 1         | 0.42%   |
| Gentoo        | 1         | 0.42%   |
| Ctlos         | 1         | 0.42%   |
| ArcoLinux     | 1         | 0.42%   |
| ALT Linux     | 1         | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 10        | 3.8%    |
| 5.10.14-desktop-1omv4002            | 6         | 2.28%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 6         | 2.28%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6         | 2.28%   |
| 5.16.7-desktop-1omv4003             | 5         | 1.9%    |
| 5.10.74-generic-2rosa2021.1-x86_64  | 5         | 1.9%    |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 5         | 1.9%    |
| 5.15.0-41-generic                   | 4         | 1.52%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 4         | 1.52%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 4         | 1.52%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 4         | 1.52%   |
| 5.8.0-33-generic                    | 3         | 1.14%   |
| 6.6.8-arch1-1                       | 2         | 0.76%   |
| 5.4.32-generic-2rosa-x86_64         | 2         | 0.76%   |
| 5.4.0-48-generic                    | 2         | 0.76%   |
| 5.4.0-37-generic                    | 2         | 0.76%   |
| 5.17.11-generic-2rosa2021.1-x86_64  | 2         | 0.76%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 2         | 0.76%   |
| 5.15.0-88-generic                   | 2         | 0.76%   |
| 5.15.0-67-generic                   | 2         | 0.76%   |
| 5.15.0-58-generic                   | 2         | 0.76%   |
| 5.11.0-7614-generic                 | 2         | 0.76%   |
| 5.11.0-41-generic                   | 2         | 0.76%   |
| 5.11.0-34-generic                   | 2         | 0.76%   |
| 5.11.0-25-generic                   | 2         | 0.76%   |
| 5.10.2-2-MANJARO                    | 2         | 0.76%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 2         | 0.76%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 2         | 0.76%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 2         | 0.76%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 2         | 0.76%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 2         | 0.76%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 2         | 0.76%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 2         | 0.76%   |
| 6.7.0-arch3-1-g14                   | 1         | 0.38%   |
| 6.6.2-desktop-1omv2390              | 1         | 0.38%   |
| 6.6.11-200.fc39.x86_64              | 1         | 0.38%   |
| 6.6.10-zen1-1-zen                   | 1         | 0.38%   |
| 6.5.0-kali3-amd64                   | 1         | 0.38%   |
| 6.5.0-kali1-amd64                   | 1         | 0.38%   |
| 6.5.0-9-generic                     | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 27        | 10.51%  |
| 5.4.0   | 18        | 7%      |
| 5.15.0  | 18        | 7%      |
| 4.9.60  | 13        | 5.06%   |
| 5.11.0  | 12        | 4.67%   |
| 5.8.0   | 7         | 2.72%   |
| 4.1.34  | 7         | 2.72%   |
| 5.10.14 | 6         | 2.33%   |
| 4.9.20  | 6         | 2.33%   |
| 5.3.0   | 5         | 1.95%   |
| 5.19.0  | 5         | 1.95%   |
| 5.16.7  | 5         | 1.95%   |
| 5.13.0  | 5         | 1.95%   |
| 5.10.74 | 5         | 1.95%   |
| 5.0.0   | 4         | 1.56%   |
| 4.9.155 | 4         | 1.56%   |
| 4.18.0  | 4         | 1.56%   |
| 6.5.0   | 3         | 1.17%   |
| 6.2.0   | 3         | 1.17%   |
| 5.4.32  | 3         | 1.17%   |
| 4.9.124 | 3         | 1.17%   |
| 4.1.38  | 3         | 1.17%   |
| 6.6.8   | 2         | 0.78%   |
| 6.1.1   | 2         | 0.78%   |
| 6.1.0   | 2         | 0.78%   |
| 5.9.3   | 2         | 0.78%   |
| 5.8.18  | 2         | 0.78%   |
| 5.18.1  | 2         | 0.78%   |
| 5.17.11 | 2         | 0.78%   |
| 5.15.79 | 2         | 0.78%   |
| 5.10.2  | 2         | 0.78%   |
| 5.10.0  | 2         | 0.78%   |
| 4.9.95  | 2         | 0.78%   |
| 4.9.9   | 2         | 0.78%   |
| 4.9.76  | 2         | 0.78%   |
| 4.9.41  | 2         | 0.78%   |
| 4.10.0  | 2         | 0.78%   |
| 4.1.25  | 2         | 0.78%   |
| 6.7.0   | 1         | 0.39%   |
| 6.6.2   | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 12.75%  |
| 5.15    | 28        | 11.16%  |
| 4.15    | 27        | 10.76%  |
| 5.4     | 23        | 9.16%   |
| 5.10    | 19        | 7.57%   |
| 5.11    | 13        | 5.18%   |
| 4.1     | 12        | 4.78%   |
| 5.8     | 9         | 3.59%   |
| 5.19    | 7         | 2.79%   |
| 5.18    | 7         | 2.79%   |
| 5.16    | 7         | 2.79%   |
| 6.2     | 6         | 2.39%   |
| 6.1     | 6         | 2.39%   |
| 5.17    | 6         | 2.39%   |
| 5.13    | 6         | 2.39%   |
| 6.6     | 5         | 1.99%   |
| 5.3     | 5         | 1.99%   |
| 5.0     | 5         | 1.99%   |
| 6.4     | 4         | 1.59%   |
| 4.18    | 4         | 1.59%   |
| 6.5     | 3         | 1.2%    |
| 5.9     | 2         | 0.8%    |
| 5.14    | 2         | 0.8%    |
| 5.12    | 2         | 0.8%    |
| 4.10    | 2         | 0.8%    |
| 6.7     | 1         | 0.4%    |
| 6.3     | 1         | 0.4%    |
| 6.0     | 1         | 0.4%    |
| 5.6     | 1         | 0.4%    |
| 5.5     | 1         | 0.4%    |
| 5.2     | 1         | 0.4%    |
| 5.1     | 1         | 0.4%    |
| 4.19    | 1         | 0.4%    |
| 4.16    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 222       | 92.89%  |
| i686   | 17        | 7.11%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 67        | 27.35%  |
| KDE5            | 62        | 25.31%  |
| KDE4            | 47        | 19.18%  |
| Unknown         | 18        | 7.35%   |
| X-Cinnamon      | 16        | 6.53%   |
| XFCE            | 13        | 5.31%   |
| MATE            | 4         | 1.63%   |
| LXQt            | 4         | 1.63%   |
| KDE             | 3         | 1.22%   |
| sway            | 2         | 0.82%   |
| GNOME Flashback | 2         | 0.82%   |
| Cinnamon        | 2         | 0.82%   |
| xinitrc         | 1         | 0.41%   |
| LXDE            | 1         | 0.41%   |
| i3              | 1         | 0.41%   |
| Budgie          | 1         | 0.41%   |
| bspwm           | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 187       | 76.95%  |
| Wayland | 42        | 17.28%  |
| Unknown | 14        | 5.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 30.08%  |
| SDDM    | 57        | 23.17%  |
| KDM     | 47        | 19.11%  |
| GDM     | 25        | 10.16%  |
| LightDM | 18        | 7.32%   |
| GDM3    | 17        | 6.91%   |
| TDM     | 8         | 3.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 79        | 32.64%  |
| Unknown | 75        | 30.99%  |
| ru_RU   | 58        | 23.97%  |
| ro_RO   | 10        | 4.13%   |
| C       | 7         | 2.89%   |
| en_GB   | 5         | 2.07%   |
| ru_UA   | 3         | 1.24%   |
| uk_UA   | 1         | 0.41%   |
| nl_NL   | 1         | 0.41%   |
| en_150  | 1         | 0.41%   |
| de_DE   | 1         | 0.41%   |
| C.UTF8  | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 132       | 55%     |
| EFI  | 108       | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 157       | 65.42%  |
| Unknown | 37        | 15.42%  |
| Btrfs   | 18        | 7.5%    |
| Overlay | 16        | 6.67%   |
| Tmpfs   | 8         | 3.33%   |
| Xfs     | 2         | 0.83%   |
| F2fs    | 1         | 0.42%   |
| Ext2    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 90        | 36.89%  |
| Unknown | 85        | 34.84%  |
| MBR     | 69        | 28.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 213       | 88.02%  |
| Yes       | 29        | 11.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 169       | 69.83%  |
| Yes       | 73        | 30.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 63        | 26.58%  |
| Lenovo              | 37        | 15.61%  |
| Hewlett-Packard     | 34        | 14.35%  |
| Gigabyte Technology | 19        | 8.02%   |
| Dell                | 17        | 7.17%   |
| Acer                | 13        | 5.49%   |
| Biostar             | 11        | 4.64%   |
| MSI                 | 6         | 2.53%   |
| ASRock              | 6         | 2.53%   |
| Toshiba             | 5         | 2.11%   |
| Timi                | 5         | 2.11%   |
| Samsung Electronics | 4         | 1.69%   |
| Apple               | 3         | 1.27%   |
| Sony                | 2         | 0.84%   |
| Unknown             | 2         | 0.84%   |
| Valve               | 1         | 0.42%   |
| System76            | 1         | 0.42%   |
| Jumper              | 1         | 0.42%   |
| Intel               | 1         | 0.42%   |
| HUAWEI              | 1         | 0.42%   |
| Google              | 1         | 0.42%   |
| Gateway             | 1         | 0.42%   |
| Foxconn             | 1         | 0.42%   |
| ECS                 | 1         | 0.42%   |
| Chuwi               | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Timi TM1701                                 | 3         | 1.27%   |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 1.27%   |
| Unknown                                     | 3         | 1.27%   |
| Samsung RV413/RV513                         | 2         | 0.84%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 0.84%   |
| HP ProBook 450 G7                           | 2         | 0.84%   |
| HP Compaq Presario CQ60                     | 2         | 0.84%   |
| Gigabyte H81M-S2PV                          | 2         | 0.84%   |
| Gigabyte H61M-S1                            | 2         | 0.84%   |
| ASUS VivoBook S15 X510UF                    | 2         | 0.84%   |
| ASUS H110M-R                                | 2         | 0.84%   |
| ASUS All Series                             | 2         | 0.84%   |
| Valve Jupiter                               | 1         | 0.42%   |
| Toshiba TECRA Z40-B                         | 1         | 0.42%   |
| Toshiba Satellite S50-B                     | 1         | 0.42%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.42%   |
| Toshiba Satellite C55D-A                    | 1         | 0.42%   |
| Toshiba Satellite A210                      | 1         | 0.42%   |
| Timi A35S                                   | 1         | 0.42%   |
| Timi A34R                                   | 1         | 0.42%   |
| System76 Adder WS                           | 1         | 0.42%   |
| Sony VPCF13WFX                              | 1         | 0.42%   |
| Sony VPCEB1J8E                              | 1         | 0.42%   |
| Samsung R517/R717                           | 1         | 0.42%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.42%   |
| MSI Pro 3130 Microtower PC                  | 1         | 0.42%   |
| MSI MS-7695                                 | 1         | 0.42%   |
| MSI MS-7592                                 | 1         | 0.42%   |
| MSI MS-7529                                 | 1         | 0.42%   |
| MSI MS-7309                                 | 1         | 0.42%   |
| MSI CR610                                   | 1         | 0.42%   |
| Lenovo Z51-70 80K6                          | 1         | 0.42%   |
| Lenovo Yoga 730-15IKB 81CU                  | 1         | 0.42%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.42%   |
| Lenovo V580 20147                           | 1         | 0.42%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.42%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.42%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.42%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.42%   |
| Lenovo ThinkPad W520 4282BA9                | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 13        | 5.49%   |
| Lenovo ThinkPad    | 9         | 3.8%    |
| ASUS VivoBook      | 9         | 3.8%    |
| Acer Aspire        | 9         | 3.8%    |
| HP ProBook         | 7         | 2.95%   |
| Dell Latitude      | 6         | 2.53%   |
| Dell Inspiron      | 6         | 2.53%   |
| HP EliteBook       | 5         | 2.11%   |
| Toshiba Satellite  | 4         | 1.69%   |
| Lenovo Legion      | 4         | 1.69%   |
| HP Pavilion        | 4         | 1.69%   |
| HP Compaq          | 4         | 1.69%   |
| ASUS PRIME         | 4         | 1.69%   |
| Timi TM1701        | 3         | 1.27%   |
| ASUS TUF           | 3         | 1.27%   |
| ASUS ROG           | 3         | 1.27%   |
| Unknown            | 3         | 1.27%   |
| Samsung RV413      | 2         | 0.84%   |
| Lenovo ThinkBook   | 2         | 0.84%   |
| HP ProDesk         | 2         | 0.84%   |
| HP Laptop          | 2         | 0.84%   |
| HP ENVY            | 2         | 0.84%   |
| Gigabyte Z690      | 2         | 0.84%   |
| Gigabyte H81M-S2PV | 2         | 0.84%   |
| Gigabyte H61M-S1   | 2         | 0.84%   |
| Dell Vostro        | 2         | 0.84%   |
| ASUS ZenBook       | 2         | 0.84%   |
| ASUS P8H61-M       | 2         | 0.84%   |
| ASUS M5A78L-M      | 2         | 0.84%   |
| ASUS H110M-R       | 2         | 0.84%   |
| ASUS All           | 2         | 0.84%   |
| Valve Jupiter      | 1         | 0.42%   |
| Toshiba TECRA      | 1         | 0.42%   |
| Timi A35S          | 1         | 0.42%   |
| Timi A34R          | 1         | 0.42%   |
| System76 Adder     | 1         | 0.42%   |
| Sony VPCF13WFX     | 1         | 0.42%   |
| Sony VPCEB1J8E     | 1         | 0.42%   |
| Samsung R517       | 1         | 0.42%   |
| Samsung 300E4C     | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 22        | 9.28%   |
| 2012 | 22        | 9.28%   |
| 2011 | 22        | 9.28%   |
| 2021 | 21        | 8.86%   |
| 2019 | 21        | 8.86%   |
| 2017 | 19        | 8.02%   |
| 2020 | 16        | 6.75%   |
| 2009 | 16        | 6.75%   |
| 2013 | 14        | 5.91%   |
| 2010 | 12        | 5.06%   |
| 2016 | 11        | 4.64%   |
| 2015 | 11        | 4.64%   |
| 2022 | 8         | 3.38%   |
| 2014 | 8         | 3.38%   |
| 2008 | 5         | 2.11%   |
| 2007 | 4         | 1.69%   |
| 2006 | 3         | 1.27%   |
| 2023 | 1         | 0.42%   |
| 2005 | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 148       | 62.45%  |
| Desktop     | 78        | 32.91%  |
| Mini pc     | 4         | 1.69%   |
| All in one  | 4         | 1.69%   |
| Convertible | 2         | 0.84%   |
| Server      | 1         | 0.42%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 224       | 94.51%  |
| Enabled  | 13        | 5.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 236       | 99.58%  |
| Yes  | 1         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 63        | 26.36%  |
| 4.01-8.0    | 47        | 19.67%  |
| 8.01-16.0   | 46        | 19.25%  |
| 16.01-24.0  | 39        | 16.32%  |
| 32.01-64.0  | 17        | 7.11%   |
| 1.01-2.0    | 12        | 5.02%   |
| 2.01-3.0    | 8         | 3.35%   |
| 64.01-256.0 | 4         | 1.67%   |
| 24.01-32.0  | 2         | 0.84%   |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 88        | 34.78%  |
| 2.01-3.0   | 45        | 17.79%  |
| 0.51-1.0   | 43        | 17%     |
| 4.01-8.0   | 38        | 15.02%  |
| 3.01-4.0   | 25        | 9.88%   |
| 8.01-16.0  | 7         | 2.77%   |
| 16.01-24.0 | 3         | 1.19%   |
| 0.01-0.5   | 3         | 1.19%   |
| 24.01-32.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 163       | 68.2%   |
| 2      | 54        | 22.59%  |
| 3      | 15        | 6.28%   |
| 4      | 5         | 2.09%   |
| 0      | 2         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 162       | 68.35%  |
| Yes       | 75        | 31.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 87.39%  |
| No        | 30        | 12.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 74.68%  |
| No        | 60        | 25.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 57.98%  |
| No        | 100       | 42.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Moldova | 237       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Chisinau        | 131       | 54.36%  |
| Tiraspol        | 44        | 18.26%  |
| Bălţi         | 8         | 3.32%   |
| Tighina         | 6         | 2.49%   |
| Straseni        | 5         | 2.07%   |
| Hincesti        | 3         | 1.24%   |
| Tintareni       | 2         | 0.83%   |
| Soroca          | 2         | 0.83%   |
| Orhei           | 2         | 0.83%   |
| Ialoveni        | 2         | 0.83%   |
| Floresti        | 2         | 0.83%   |
| Congaz          | 2         | 0.83%   |
| Căușeni       | 2         | 0.83%   |
| Cahul           | 2         | 0.83%   |
| Zaicana         | 1         | 0.41%   |
| Vişniovca      | 1         | 0.41%   |
| Tvardița       | 1         | 0.41%   |
| Soldanesti      | 1         | 0.41%   |
| Sofia           | 1         | 0.41%   |
| Singera         | 1         | 0.41%   |
| Rîbniţa       | 1         | 0.41%   |
| Rezina          | 1         | 0.41%   |
| Rautel          | 1         | 0.41%   |
| Prajila         | 1         | 0.41%   |
| Pociumbeni      | 1         | 0.41%   |
| Nisporeni       | 1         | 0.41%   |
| Mascauti        | 1         | 0.41%   |
| Lapusna         | 1         | 0.41%   |
| Ilenuta         | 1         | 0.41%   |
| Gangura         | 1         | 0.41%   |
| Floreni         | 1         | 0.41%   |
| Edineţ         | 1         | 0.41%   |
| Durlesti        | 1         | 0.41%   |
| Drochia         | 1         | 0.41%   |
| Donduseni       | 1         | 0.41%   |
| Criuleni        | 1         | 0.41%   |
| Cricova         | 1         | 0.41%   |
| Crasnoarmeiscoe | 1         | 0.41%   |
| Cojusna         | 1         | 0.41%   |
| Cenac           | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 64        | 77     | 19.75%  |
| WDC                         | 40        | 43     | 12.35%  |
| Seagate                     | 38        | 45     | 11.73%  |
| Toshiba                     | 35        | 40     | 10.8%   |
| Kingston                    | 19        | 23     | 5.86%   |
| Hitachi                     | 19        | 22     | 5.86%   |
| SanDisk                     | 13        | 14     | 4.01%   |
| Micron Technology           | 9         | 12     | 2.78%   |
| SK hynix                    | 8         | 8      | 2.47%   |
| SPCC                        | 7         | 9      | 2.16%   |
| Transcend                   | 6         | 6      | 1.85%   |
| Unknown                     | 5         | 5      | 1.54%   |
| Intel                       | 5         | 7      | 1.54%   |
| HGST                        | 4         | 4      | 1.23%   |
| Apacer                      | 4         | 4      | 1.23%   |
| Netac                       | 3         | 3      | 0.93%   |
| Maxtor                      | 3         | 4      | 0.93%   |
| Crucial                     | 3         | 4      | 0.93%   |
| A-DATA Technology           | 3         | 3      | 0.93%   |
| UMIS                        | 2         | 2      | 0.62%   |
| Phison                      | 2         | 3      | 0.62%   |
| OCZ                         | 2         | 2      | 0.62%   |
| KIOXIA                      | 2         | 2      | 0.62%   |
| Kingston Technology Company | 2         | 2      | 0.62%   |
| Intenso                     | 2         | 2      | 0.62%   |
| GOODRAM                     | 2         | 2      | 0.62%   |
| Fujitsu                     | 2         | 2      | 0.62%   |
| China                       | 2         | 2      | 0.62%   |
| ZOTAC                       | 1         | 3      | 0.31%   |
| XPG                         | 1         | 1      | 0.31%   |
| Team                        | 1         | 1      | 0.31%   |
| Solid State Storage         | 1         | 1      | 0.31%   |
| PNY                         | 1         | 1      | 0.31%   |
| Patriot                     | 1         | 1      | 0.31%   |
| O2 Micro                    | 1         | 1      | 0.31%   |
| LITEONIT                    | 1         | 1      | 0.31%   |
| Lite-On Technology          | 1         | 1      | 0.31%   |
| Leven                       | 1         | 1      | 0.31%   |
| Lenovo                      | 1         | 1      | 0.31%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SHFS37A120G 120GB SSD                    | 7         | 2.1%    |
| Samsung NVMe SSD Drive 512GB                      | 6         | 1.8%    |
| Toshiba MQ04ABF100 1TB                            | 4         | 1.2%    |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.2%    |
| Toshiba DT01ACA050 500GB                          | 4         | 1.2%    |
| Seagate ST500LT012-9WS142 500GB                   | 4         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB                    | 4         | 1.2%    |
| Samsung SSD 860 EVO 500GB                         | 4         | 1.2%    |
| Toshiba HDWD110 1TB                               | 3         | 0.9%    |
| Toshiba DT01ACA100 1TB                            | 3         | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB                    | 3         | 0.9%    |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.9%    |
| Samsung MZVLW256HEHP-00000 256GB                  | 3         | 0.9%    |
| Samsung HD502HJ 500GB                             | 3         | 0.9%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 3         | 0.9%    |
| Kingston SA400S37240G 240GB SSD                   | 3         | 0.9%    |
| Hitachi HTS543232A7A384 320GB                     | 3         | 0.9%    |
| WDC WD5000AZRX-00A8LB0 500GB                      | 2         | 0.6%    |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.6%    |
| WDC WD10SPZX-22Z10T1 1TB                          | 2         | 0.6%    |
| Unknown MMC Card  64GB                            | 2         | 0.6%    |
| Transcend TS64GSSD370S 64GB                       | 2         | 0.6%    |
| Transcend TS120GMTS420S 120GB SSD                 | 2         | 0.6%    |
| Toshiba MQ01ACF032 320GB                          | 2         | 0.6%    |
| Toshiba MQ01ABF050 500GB                          | 2         | 0.6%    |
| SPCC Solid State Disk 128GB                       | 2         | 0.6%    |
| SK hynix NVMe SSD Drive 256GB                     | 2         | 0.6%    |
| Seagate ST9500325AS 500GB                         | 2         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 0.6%    |
| Seagate ST4000VM000-2AF166 4TB                    | 2         | 0.6%    |
| Seagate ST3160023A 160GB                          | 2         | 0.6%    |
| Seagate ST1000DL002-9TT153 1TB                    | 2         | 0.6%    |
| SanDisk SD7UB3Q256G1001 256GB SSD                 | 2         | 0.6%    |
| Samsung SSD 980 500GB                             | 2         | 0.6%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 2         | 0.6%    |
| Samsung HD251HJ 250GB                             | 2         | 0.6%    |
| Samsung HD082GJ 80GB                              | 2         | 0.6%    |
| Netac SSD 256GB                                   | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 41     | 24.84%  |
| Seagate             | 38        | 45     | 24.84%  |
| Toshiba             | 28        | 33     | 18.3%   |
| Samsung Electronics | 19        | 22     | 12.42%  |
| Hitachi             | 19        | 22     | 12.42%  |
| HGST                | 4         | 4      | 2.61%   |
| Maxtor              | 3         | 4      | 1.96%   |
| Fujitsu             | 2         | 2      | 1.31%   |
| Unknown             | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 20     | 18.18%  |
| Samsung Electronics | 15        | 18     | 17.05%  |
| SanDisk             | 7         | 8      | 7.95%   |
| Transcend           | 6         | 6      | 6.82%   |
| SPCC                | 6         | 8      | 6.82%   |
| Apacer              | 4         | 4      | 4.55%   |
| Toshiba             | 3         | 3      | 3.41%   |
| Micron Technology   | 3         | 3      | 3.41%   |
| Crucial             | 3         | 4      | 3.41%   |
| OCZ                 | 2         | 2      | 2.27%   |
| Netac               | 2         | 2      | 2.27%   |
| Intenso             | 2         | 2      | 2.27%   |
| GOODRAM             | 2         | 2      | 2.27%   |
| China               | 2         | 2      | 2.27%   |
| ZOTAC               | 1         | 3      | 1.14%   |
| WDC                 | 1         | 1      | 1.14%   |
| Team                | 1         | 1      | 1.14%   |
| PNY                 | 1         | 1      | 1.14%   |
| Patriot             | 1         | 1      | 1.14%   |
| LITEONIT            | 1         | 1      | 1.14%   |
| Leven               | 1         | 1      | 1.14%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.14%   |
| KingDian            | 1         | 1      | 1.14%   |
| Intel               | 1         | 1      | 1.14%   |
| Goldkey             | 1         | 1      | 1.14%   |
| Gigabyte Technology | 1         | 2      | 1.14%   |
| CHN25SATAS1         | 1         | 1      | 1.14%   |
| AMD                 | 1         | 1      | 1.14%   |
| A-DATA Technology   | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 133       | 175    | 46.02%  |
| SSD  | 80        | 102    | 27.68%  |
| NVMe | 72        | 92     | 24.91%  |
| MMC  | 4         | 4      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 180       | 275    | 69.77%  |
| NVMe | 72        | 92     | 27.91%  |
| MMC  | 4         | 4      | 1.55%   |
| SAS  | 2         | 2      | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 205    | 70.67%  |
| 0.51-1.0   | 46        | 57     | 22.12%  |
| 1.01-2.0   | 11        | 11     | 5.29%   |
| 3.01-4.0   | 3         | 3      | 1.44%   |
| 4.01-10.0  | 1         | 1      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 66        | 26.4%   |
| 251-500        | 65        | 26%     |
| 501-1000       | 33        | 13.2%   |
| 51-100         | 26        | 10.4%   |
| 1-20           | 23        | 9.2%    |
| 21-50          | 11        | 4.4%    |
| 1001-2000      | 11        | 4.4%    |
| Unknown        | 8         | 3.2%    |
| More than 3000 | 4         | 1.6%    |
| 2001-3000      | 3         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 114       | 44.88%  |
| 21-50          | 40        | 15.75%  |
| 51-100         | 32        | 12.6%   |
| 101-250        | 25        | 9.84%   |
| 251-500        | 20        | 7.87%   |
| 501-1000       | 10        | 3.94%   |
| Unknown        | 8         | 3.15%   |
| 1001-2000      | 4         | 1.57%   |
| More than 3000 | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 6.12%   |
| Seagate ST3160023A 160GB          | 2         | 2      | 4.08%   |
| Samsung Electronics HD082GJ 80GB  | 2         | 2      | 4.08%   |
| Kingston SHFS37A120G 120GB SSD    | 2         | 4      | 4.08%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 4.08%   |
| WDC WD800JD-22LSA0 80GB           | 1         | 1      | 2.04%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 2.04%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1         | 1      | 2.04%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1         | 1      | 2.04%   |
| WDC WD5000AADS-56S9B1 500GB       | 1         | 1      | 2.04%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 2.04%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1         | 1      | 2.04%   |
| WDC WD1600BEVS-60RST0 160GB       | 1         | 1      | 2.04%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 2.04%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 2.04%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 2.04%   |
| Team L5 LITE SSD 240GB            | 1         | 1      | 2.04%   |
| SPCC SSD162 120GB                 | 1         | 1      | 2.04%   |
| SPCC Solid State Disk 56GB        | 1         | 2      | 2.04%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.04%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 2.04%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1         | 1      | 2.04%   |
| Seagate ST31000340NS 1TB          | 1         | 1      | 2.04%   |
| Seagate ST2000DM008-2FR102 2TB    | 1         | 1      | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 2.04%   |
| Seagate ST1000DL002-9TT153 1TB    | 1         | 1      | 2.04%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 2.04%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 2.04%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 2.04%   |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 2.04%   |
| Maxtor STM380215AS 80GB           | 1         | 1      | 2.04%   |
| Maxtor STM3160811AS 160GB         | 1         | 1      | 2.04%   |
| Maxtor STM3160211AS 160GB         | 1         | 1      | 2.04%   |
| Maxtor 4R120L0 122GB              | 1         | 1      | 2.04%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.04%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 2.04%   |
| Hitachi HDT721010SLA360 1TB       | 1         | 2      | 2.04%   |
| Hitachi HDP725050GLA360 500GB     | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 25%     |
| WDC                 | 10        | 10     | 20.83%  |
| Hitachi             | 7         | 9      | 14.58%  |
| Samsung Electronics | 5         | 5      | 10.42%  |
| Toshiba             | 3         | 3      | 6.25%   |
| Maxtor              | 3         | 4      | 6.25%   |
| SPCC                | 2         | 3      | 4.17%   |
| Kingston            | 2         | 4      | 4.17%   |
| Team                | 1         | 1      | 2.08%   |
| SanDisk             | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 29.27%  |
| WDC                 | 10        | 10     | 24.39%  |
| Hitachi             | 7         | 9      | 17.07%  |
| Samsung Electronics | 5         | 5      | 12.2%   |
| Toshiba             | 3         | 3      | 7.32%   |
| Maxtor              | 3         | 4      | 7.32%   |
| Fujitsu             | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 44     | 84.09%  |
| SSD  | 7         | 10     | 15.91%  |

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
| Works    | 119       | 182    | 45.95%  |
| Detected | 92        | 132    | 35.52%  |
| Malfunc  | 44        | 54     | 16.99%  |
| Failed   | 4         | 5      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 145       | 48.66%  |
| AMD                            | 58        | 19.46%  |
| Samsung Electronics            | 30        | 10.07%  |
| Nvidia                         | 10        | 3.36%   |
| SK hynix                       | 8         | 2.68%   |
| SanDisk                        | 7         | 2.35%   |
| Micron Technology              | 6         | 2.01%   |
| Kingston Technology Company    | 5         | 1.68%   |
| JMicron Technology             | 5         | 1.68%   |
| Toshiba America Info Systems   | 4         | 1.34%   |
| ASMedia Technology             | 3         | 1.01%   |
| Union Memory (Shenzhen)        | 2         | 0.67%   |
| Phison Electronics             | 2         | 0.67%   |
| KIOXIA                         | 2         | 0.67%   |
| ADATA Technology               | 2         | 0.67%   |
| Solid State Storage Technology | 1         | 0.34%   |
| Silicon Motion                 | 1         | 0.34%   |
| Realtek Semiconductor          | 1         | 0.34%   |
| O2 Micro                       | 1         | 0.34%   |
| Netac Technology               | 1         | 0.34%   |
| Marvell Technology Group       | 1         | 0.34%   |
| Lite-On Technology             | 1         | 0.34%   |
| Lenovo                         | 1         | 0.34%   |
| Hewlett-Packard                | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30        | 8.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14        | 3.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 3.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 12        | 3.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 2.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.71%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.42%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 4         | 1.14%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.85%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.85%   |
| Nvidia MCP61 IDE                                                                        | 3         | 0.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 3         | 0.85%   |
| JMicron JMB368 IDE controller                                                           | 3         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.85%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3         | 0.85%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 0.85%   |
| AMD FCH IDE Controller                                                                  | 3         | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 172       | 55.84%  |
| NVMe | 72        | 23.38%  |
| IDE  | 52        | 16.88%  |
| RAID | 12        | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 68.35%  |
| AMD    | 75        | 31.65%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.27%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.27%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.27%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.27%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.84%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 0.84%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.84%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.84%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.84%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.84%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 2         | 0.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.84%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.84%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.84%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.84%   |
| Intel 12th Gen Core i5-12450H                 | 2         | 0.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.84%   |
| AMD Phenom II X6 1055T Processor              | 2         | 0.84%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.84%   |
| AMD Athlon II X2 280 Processor                | 2         | 0.84%   |
| Intel Xeon CPU E5405 @ 2.00GHz                | 1         | 0.42%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.42%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 50        | 21.1%   |
| Intel Core i7                  | 27        | 11.39%  |
| Intel Core i3                  | 22        | 9.28%   |
| Intel Celeron                  | 17        | 7.17%   |
| AMD Ryzen 5                    | 15        | 6.33%   |
| Intel Pentium                  | 13        | 5.49%   |
| Other                          | 12        | 5.06%   |
| AMD Ryzen 7                    | 10        | 4.22%   |
| AMD Athlon II X2               | 7         | 2.95%   |
| Intel Core 2 Duo               | 5         | 2.11%   |
| AMD E                          | 5         | 2.11%   |
| AMD Athlon 64 X2               | 5         | 2.11%   |
| Intel Pentium Silver           | 4         | 1.69%   |
| AMD A4                         | 4         | 1.69%   |
| Intel Pentium Dual-Core        | 3         | 1.27%   |
| AMD Ryzen 3                    | 3         | 1.27%   |
| AMD FX                         | 3         | 1.27%   |
| AMD E1                         | 3         | 1.27%   |
| AMD A10                        | 3         | 1.27%   |
| Intel Pentium D                | 2         | 0.84%   |
| Intel Core i9                  | 2         | 0.84%   |
| Intel Atom                     | 2         | 0.84%   |
| AMD Sempron                    | 2         | 0.84%   |
| AMD Phenom II X6               | 2         | 0.84%   |
| AMD Athlon II X4               | 2         | 0.84%   |
| AMD Athlon                     | 2         | 0.84%   |
| Intel Xeon                     | 1         | 0.42%   |
| Intel Pentium Dual             | 1         | 0.42%   |
| Intel Pentium 4                | 1         | 0.42%   |
| Intel Core 2 Quad              | 1         | 0.42%   |
| AMD V140                       | 1         | 0.42%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.42%   |
| AMD Ryzen 9                    | 1         | 0.42%   |
| AMD Ryzen 5 PRO                | 1         | 0.42%   |
| AMD Ryzen 3 PRO                | 1         | 0.42%   |
| AMD Phenom II X4               | 1         | 0.42%   |
| AMD A8                         | 1         | 0.42%   |
| AMD A6                         | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 107       | 44.96%  |
| 4       | 82        | 34.45%  |
| 6       | 19        | 7.98%   |
| 8       | 16        | 6.72%   |
| 1       | 5         | 2.1%    |
| Unknown | 4         | 1.68%   |
| 10      | 3         | 1.26%   |
| 14      | 1         | 0.42%   |
| 12      | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 236       | 99.58%  |
| 2      | 1         | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 134       | 56.3%   |
| 1       | 100       | 42.02%  |
| Unknown | 4         | 1.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 234       | 98.73%  |
| Unknown        | 3         | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 22.92%  |
| 0x206a7    | 13        | 5.42%   |
| 0x806ea    | 11        | 4.58%   |
| 0x306c3    | 9         | 3.75%   |
| 0x306a9    | 8         | 3.33%   |
| 0x05000119 | 8         | 3.33%   |
| 0x806ec    | 7         | 2.92%   |
| 0x010000c8 | 7         | 2.92%   |
| 0x906e9    | 6         | 2.5%    |
| 0x40651    | 5         | 2.08%   |
| 0x08600106 | 5         | 2.08%   |
| 0x906ea    | 4         | 1.67%   |
| 0x706a1    | 4         | 1.67%   |
| 0x506e3    | 4         | 1.67%   |
| 0x406e3    | 4         | 1.67%   |
| 0x306d4    | 4         | 1.67%   |
| 0x1067a    | 4         | 1.67%   |
| 0x806e9    | 3         | 1.25%   |
| 0x6fd      | 3         | 1.25%   |
| 0x506c9    | 3         | 1.25%   |
| 0x0a50000c | 3         | 1.25%   |
| 0x08108109 | 3         | 1.25%   |
| 0x03000027 | 3         | 1.25%   |
| 0xf47      | 2         | 0.83%   |
| 0xa0655    | 2         | 0.83%   |
| 0xa0652    | 2         | 0.83%   |
| 0x90672    | 2         | 0.83%   |
| 0x806c1    | 2         | 0.83%   |
| 0x706e5    | 2         | 0.83%   |
| 0x706a8    | 2         | 0.83%   |
| 0x406c4    | 2         | 0.83%   |
| 0x406c3    | 2         | 0.83%   |
| 0x30678    | 2         | 0.83%   |
| 0x20655    | 2         | 0.83%   |
| 0x106e5    | 2         | 0.83%   |
| 0x10676    | 2         | 0.83%   |
| 0x08701021 | 2         | 0.83%   |
| 0x08608103 | 2         | 0.83%   |
| 0x08108102 | 2         | 0.83%   |
| 0x06001119 | 2         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 16.46%  |
| Haswell          | 17        | 7.17%   |
| SandyBridge      | 16        | 6.75%   |
| K10              | 14        | 5.91%   |
| Zen 2            | 12        | 5.06%   |
| Skylake          | 11        | 4.64%   |
| IvyBridge        | 10        | 4.22%   |
| Goldmont plus    | 8         | 3.38%   |
| Bobcat           | 8         | 3.38%   |
| Zen 3            | 7         | 2.95%   |
| Silvermont       | 7         | 2.95%   |
| Penryn           | 7         | 2.95%   |
| Zen+             | 6         | 2.53%   |
| Broadwell        | 6         | 2.53%   |
| Unknown          | 6         | 2.53%   |
| Piledriver       | 5         | 2.11%   |
| K8 Hammer        | 5         | 2.11%   |
| IceLake          | 5         | 2.11%   |
| Core             | 5         | 2.11%   |
| CometLake        | 5         | 2.11%   |
| Alderlake Hybrid | 5         | 2.11%   |
| Zen              | 4         | 1.69%   |
| TigerLake        | 4         | 1.69%   |
| NetBurst         | 4         | 1.69%   |
| K10 Llano        | 4         | 1.69%   |
| Westmere         | 3         | 1.27%   |
| K8 & K10 hybrid  | 3         | 1.27%   |
| Goldmont         | 3         | 1.27%   |
| Nehalem          | 2         | 0.84%   |
| Bonnell          | 2         | 0.84%   |
| Tremont          | 1         | 0.42%   |
| Steamroller      | 1         | 0.42%   |
| Puma             | 1         | 0.42%   |
| Bulldozer        | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 134       | 47.02%  |
| Nvidia | 77        | 27.02%  |
| AMD    | 74        | 25.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 5.14%   |
| Intel UHD Graphics 620                                                                   | 12        | 4.11%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 2.74%   |
| Intel HD Graphics 630                                                                    | 6         | 2.05%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.71%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.37%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.37%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.37%   |
| Intel HD Graphics 620                                                                    | 4         | 1.37%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.03%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 1.03%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.03%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.03%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.68%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.68%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.68%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 94        | 39.17%  |
| 1 x AMD        | 57        | 23.75%  |
| 1 x Nvidia     | 39        | 16.25%  |
| Intel + Nvidia | 32        | 13.33%  |
| 2 x AMD        | 6         | 2.5%    |
| AMD + Nvidia   | 6         | 2.5%    |
| Intel + AMD    | 5         | 2.08%   |
| Other          | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 198       | 80.82%  |
| Proprietary | 34        | 13.88%  |
| Unknown     | 13        | 5.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 47.58%  |
| 0.01-0.5   | 47        | 18.95%  |
| 1.01-2.0   | 43        | 17.34%  |
| 3.01-4.0   | 17        | 6.85%   |
| 0.51-1.0   | 15        | 6.05%   |
| 7.01-8.0   | 4         | 1.61%   |
| 5.01-6.0   | 3         | 1.21%   |
| 2.01-3.0   | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 39        | 15.23%  |
| AU Optronics            | 39        | 15.23%  |
| Chimei Innolux          | 26        | 10.16%  |
| LG Display              | 22        | 8.59%   |
| BOE                     | 21        | 8.2%    |
| Philips                 | 17        | 6.64%   |
| Goldstar                | 17        | 6.64%   |
| Dell                    | 13        | 5.08%   |
| Acer                    | 8         | 3.13%   |
| AOC                     | 6         | 2.34%   |
| Chi Mei Optoelectronics | 5         | 1.95%   |
| PANDA                   | 4         | 1.56%   |
| Lenovo                  | 4         | 1.56%   |
| InfoVision              | 4         | 1.56%   |
| Hewlett-Packard         | 4         | 1.56%   |
| Sharp                   | 3         | 1.17%   |
| CSO                     | 3         | 1.17%   |
| BenQ                    | 3         | 1.17%   |
| Apple                   | 3         | 1.17%   |
| ViewSonic               | 1         | 0.39%   |
| Valve                   | 1         | 0.39%   |
| Toshiba                 | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| SAC                     | 1         | 0.39%   |
| Plain Tree Systems      | 1         | 0.39%   |
| Medion                  | 1         | 0.39%   |
| LG Electronics          | 1         | 0.39%   |
| KTC                     | 1         | 0.39%   |
| ITE                     | 1         | 0.39%   |
| Hitachi                 | 1         | 0.39%   |
| HannStar                | 1         | 0.39%   |
| GreenWood               | 1         | 0.39%   |
| ASUSTek Computer        | 1         | 0.39%   |
| Ancor Communications    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 5         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 1.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.54%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 3         | 1.15%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 3         | 1.15%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch | 2         | 0.77%   |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch | 2         | 0.77%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.77%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 2         | 0.77%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.77%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2         | 0.77%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch      | 2         | 0.77%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 2         | 0.77%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.77%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 2         | 0.77%   |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch               | 1         | 0.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.38%   |
| Toshiba TV TSB0108 1920x540                                          | 1         | 0.38%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch | 1         | 0.38%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.38%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.38%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch               | 1         | 0.38%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 300x230mm 14.9-inch  | 1         | 0.38%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch    | 1         | 0.38%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch     | 1         | 0.38%   |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch    | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 107       | 44.03%  |
| 1366x768 (WXGA)    | 53        | 21.81%  |
| 2560x1440 (QHD)    | 14        | 5.76%   |
| 1600x900 (HD+)     | 14        | 5.76%   |
| 1280x1024 (SXGA)   | 14        | 5.76%   |
| 3840x2160 (4K)     | 6         | 2.47%   |
| 1680x1050 (WSXGA+) | 6         | 2.47%   |
| 1440x900 (WXGA+)   | 5         | 2.06%   |
| 1280x800 (WXGA)    | 5         | 2.06%   |
| 2560x1600          | 3         | 1.23%   |
| 2560x1080          | 2         | 0.82%   |
| 1600x1200          | 2         | 0.82%   |
| 1024x768 (XGA)     | 2         | 0.82%   |
| 800x1280           | 1         | 0.41%   |
| 3456x2160          | 1         | 0.41%   |
| 3200x1080          | 1         | 0.41%   |
| 3072x1920          | 1         | 0.41%   |
| 2880x1800          | 1         | 0.41%   |
| 2160x1440          | 1         | 0.41%   |
| 1920x540           | 1         | 0.41%   |
| 1360x768           | 1         | 0.41%   |
| 1024x600           | 1         | 0.41%   |
| Unknown            | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 106       | 41.09%  |
| 23      | 17        | 6.59%   |
| 24      | 16        | 6.2%    |
| 17      | 15        | 5.81%   |
| 14      | 15        | 5.81%   |
| 21      | 14        | 5.43%   |
| 27      | 13        | 5.04%   |
| 19      | 12        | 4.65%   |
| 20      | 10        | 3.88%   |
| 13      | 10        | 3.88%   |
| 18      | 7         | 2.71%   |
| 11      | 4         | 1.55%   |
| 16      | 3         | 1.16%   |
| 84      | 2         | 0.78%   |
| 72      | 2         | 0.78%   |
| 34      | 2         | 0.78%   |
| 31      | 2         | 0.78%   |
| 12      | 2         | 0.78%   |
| 32      | 1         | 0.39%   |
| 26      | 1         | 0.39%   |
| 22      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |
| 7       | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 52.16%  |
| 501-600     | 43        | 16.86%  |
| 401-500     | 37        | 14.51%  |
| 351-400     | 17        | 6.67%   |
| 201-300     | 13        | 5.1%    |
| 1501-2000   | 4         | 1.57%   |
| 701-800     | 3         | 1.18%   |
| 601-700     | 3         | 1.18%   |
| 1-100       | 1         | 0.39%   |
| Unknown     | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 183       | 80.26%  |
| 16/10   | 19        | 8.33%   |
| 5/4     | 12        | 5.26%   |
| 4/3     | 8         | 3.51%   |
| 3/2     | 2         | 0.88%   |
| 21/9    | 2         | 0.88%   |
| 0.67    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 39.84%  |
| 201-250        | 42        | 16.41%  |
| 151-200        | 26        | 10.16%  |
| 81-90          | 22        | 8.59%   |
| 301-350        | 14        | 5.47%   |
| 141-150        | 12        | 4.69%   |
| 121-130        | 7         | 2.73%   |
| 111-120        | 7         | 2.73%   |
| 351-500        | 5         | 1.95%   |
| More than 1000 | 4         | 1.56%   |
| 51-60          | 4         | 1.56%   |
| 71-80          | 3         | 1.17%   |
| 61-70          | 2         | 0.78%   |
| 131-140        | 2         | 0.78%   |
| 41-50          | 1         | 0.39%   |
| 1-40           | 1         | 0.39%   |
| 251-300        | 1         | 0.39%   |
| Unknown        | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 84        | 33.33%  |
| 121-160       | 80        | 31.75%  |
| 101-120       | 70        | 27.78%  |
| 161-240       | 12        | 4.76%   |
| More than 240 | 3         | 1.19%   |
| 1-50          | 2         | 0.79%   |
| Unknown       | 1         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 201       | 84.1%   |
| 2     | 33        | 13.81%  |
| 0     | 5         | 2.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 154       | 44.64%  |
| Intel                             | 78        | 22.61%  |
| Qualcomm Atheros                  | 51        | 14.78%  |
| Broadcom                          | 16        | 4.64%   |
| Nvidia                            | 9         | 2.61%   |
| Ralink                            | 5         | 1.45%   |
| MediaTek                          | 5         | 1.45%   |
| Xiaomi                            | 4         | 1.16%   |
| Broadcom Limited                  | 4         | 1.16%   |
| TP-Link                           | 3         | 0.87%   |
| Marvell Technology Group          | 3         | 0.87%   |
| Huawei Technologies               | 2         | 0.58%   |
| Sierra Wireless                   | 1         | 0.29%   |
| Qualcomm                          | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.29%   |
| Mercucys                          | 1         | 0.29%   |
| JMicron Technology                | 1         | 0.29%   |
| ICS Advent                        | 1         | 0.29%   |
| Hewlett-Packard                   | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 112       | 27.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 22        | 5.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 2.99%   |
| Intel Wireless 8265 / 8275                                              | 12        | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2%      |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 1%      |
| Nvidia MCP77 Ethernet                                                   | 4         | 1%      |
| Intel Wireless 7260                                                     | 4         | 1%      |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1%      |
| Intel Ethernet Connection I218-LM                                       | 4         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.75%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.5%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.5%    |
| Intel Wireless 8260                                                     | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 35.91%  |
| Qualcomm Atheros      | 44        | 24.31%  |
| Realtek Semiconductor | 43        | 23.76%  |
| Broadcom              | 12        | 6.63%   |
| Ralink                | 5         | 2.76%   |
| MediaTek              | 4         | 2.21%   |
| TP-Link               | 3         | 1.66%   |
| Sierra Wireless       | 1         | 0.55%   |
| Mercucys              | 1         | 0.55%   |
| D-Link System         | 1         | 0.55%   |
| D-Link                | 1         | 0.55%   |
| Broadcom Limited      | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 6.63%   |
| Intel Wireless 8265 / 8275                                              | 12        | 6.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 5.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.42%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.21%   |
| Intel Wireless 7260                                                     | 4         | 2.21%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.21%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.66%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.1%    |
| Realtek 802.11ac NIC                                                    | 2         | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| Intel Wireless 8260                                                     | 2         | 1.1%    |
| Intel Wireless 7265                                                     | 2         | 1.1%    |
| Intel Wireless 3165                                                     | 2         | 1.1%    |
| Intel Wireless 3160                                                     | 2         | 1.1%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.1%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.1%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.1%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.55%   |
| Sierra Wireless EM7455                                                  | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 141       | 65.28%  |
| Intel                    | 33        | 15.28%  |
| Qualcomm Atheros         | 9         | 4.17%   |
| Nvidia                   | 9         | 4.17%   |
| Broadcom                 | 6         | 2.78%   |
| Xiaomi                   | 4         | 1.85%   |
| Marvell Technology Group | 3         | 1.39%   |
| Broadcom Limited         | 3         | 1.39%   |
| Huawei Technologies      | 2         | 0.93%   |
| Qualcomm                 | 1         | 0.46%   |
| MediaTek                 | 1         | 0.46%   |
| JMicron Technology       | 1         | 0.46%   |
| ICS Advent               | 1         | 0.46%   |
| Hewlett-Packard          | 1         | 0.46%   |
| ASIX Electronics         | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 112       | 51.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 10.09%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.83%   |
| Nvidia MCP77 Ethernet                                                          | 4         | 1.83%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.38%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.92%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 0.92%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.92%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.92%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.92%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 0.92%   |
| Huawei E353/E3131                                                              | 2         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.46%   |
| Qualcomm Android                                                               | 1         | 0.46%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.46%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.46%   |
| MediaTek File-CD Gadget                                                        | 1         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.46%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.46%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.46%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 208       | 53.75%  |
| WiFi     | 177       | 45.74%  |
| Modem    | 1         | 0.26%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 56.2%   |
| Ethernet | 106       | 43.8%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 137       | 57.81%  |
| 1     | 100       | 42.19%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 227       | 95.78%  |
| Yes  | 10        | 4.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 39.86%  |
| Realtek Semiconductor           | 19        | 13.77%  |
| IMC Networks                    | 17        | 12.32%  |
| Qualcomm Atheros Communications | 15        | 10.87%  |
| Broadcom                        | 6         | 4.35%   |
| Lite-On Technology              | 5         | 3.62%   |
| Foxconn / Hon Hai               | 5         | 3.62%   |
| Cambridge Silicon Radio         | 5         | 3.62%   |
| Apple                           | 3         | 2.17%   |
| Ralink Technology               | 2         | 1.45%   |
| Toshiba                         | 1         | 0.72%   |
| Realtek                         | 1         | 0.72%   |
| Integrated System Solution      | 1         | 0.72%   |
| Hewlett-Packard                 | 1         | 0.72%   |
| Dell                            | 1         | 0.72%   |
| ASUSTek Computer                | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 15.94%  |
| Realtek Bluetooth Radio                                                             | 15        | 10.87%  |
| Intel AX201 Bluetooth                                                               | 11        | 7.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 6.52%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 6.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 5.07%   |
| Intel AX200 Bluetooth                                                               | 7         | 5.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.62%   |
| IMC Networks Bluetooth Device                                                       | 4         | 2.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.17%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 2.17%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.45%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.45%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.72%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.72%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.72%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.72%   |
| Ralink CSR BS8510                                                                   | 1         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.72%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.72%   |
| Intel Bluetooth Device                                                              | 1         | 0.72%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.72%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 0.72%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.72%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.72%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.72%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.72%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.72%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 159       | 51.79%  |
| AMD                       | 78        | 25.41%  |
| Nvidia                    | 52        | 16.94%  |
| Plantronics               | 4         | 1.3%    |
| Logitech                  | 2         | 0.65%   |
| Creative Labs             | 2         | 0.65%   |
| C-Media Electronics       | 2         | 0.65%   |
| Texas Instruments         | 1         | 0.33%   |
| SteelSeries ApS           | 1         | 0.33%   |
| Shenzhen Rapoo Technology | 1         | 0.33%   |
| Sennheiser Communications | 1         | 0.33%   |
| Kingston Technology       | 1         | 0.33%   |
| GN Netcom                 | 1         | 0.33%   |
| Giga-Byte Technology      | 1         | 0.33%   |
| fifine Microphone         | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 6.99%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 5.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 5.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 3.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.15%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.34%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.34%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.08%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 4         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 40        | 20.83%  |
| Unknown               | 37        | 19.27%  |
| SK hynix              | 27        | 14.06%  |
| Kingston              | 26        | 13.54%  |
| Micron Technology     | 11        | 5.73%   |
| GOODRAM               | 7         | 3.65%   |
| Transcend             | 5         | 2.6%    |
| Unknown (ABCD)        | 3         | 1.56%   |
| G.Skill               | 3         | 1.56%   |
| Elpida                | 3         | 1.56%   |
| Crucial               | 3         | 1.56%   |
| Corsair               | 3         | 1.56%   |
| Apacer                | 3         | 1.56%   |
| Ramaxel Technology    | 2         | 1.04%   |
| Patriot               | 2         | 1.04%   |
| Nanya Technology      | 2         | 1.04%   |
| A-DATA Technology     | 2         | 1.04%   |
| Wilk                  | 1         | 0.52%   |
| Unifosa               | 1         | 0.52%   |
| Team                  | 1         | 0.52%   |
| Silicon Power         | 1         | 0.52%   |
| SGS/Thomson           | 1         | 0.52%   |
| Kingmax Semiconductor | 1         | 0.52%   |
| Hexon                 | 1         | 0.52%   |
| Goldkey               | 1         | 0.52%   |
| Axiom                 | 1         | 0.52%   |
| AVEXIR                | 1         | 0.52%   |
| Avant                 | 1         | 0.52%   |
| ASint Technology      | 1         | 0.52%   |
| Unknown               | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                         | 3         | 1.43%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 3         | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.43%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                             | 2         | 0.95%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 2         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 2         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                       | 2         | 0.95%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 2         | 0.95%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 2         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                       | 2         | 0.95%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                         | 2         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.95%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.95%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.95%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s               | 2         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 0.95%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s                 | 2         | 0.95%   |
| Wilk RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s                | 1         | 0.48%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                             | 1         | 0.48%   |
| Unknown RAM Module 512MB DIMM SDRAM                                 | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM 667MT/s                                 | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                       | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                          | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                         | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 35.93%  |
| DDR3    | 57        | 34.13%  |
| DDR2    | 13        | 7.78%   |
| Unknown | 11        | 6.59%   |
| SDRAM   | 10        | 5.99%   |
| LPDDR4  | 6         | 3.59%   |
| DDR5    | 3         | 1.8%    |
| DDR     | 3         | 1.8%    |
| LPDDR3  | 2         | 1.2%    |
| DRAM    | 2         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 54.6%   |
| DIMM         | 64        | 39.26%  |
| Row Of Chips | 9         | 5.52%   |
| FB-DIMM      | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 56        | 29.63%  |
| 8192  | 47        | 24.87%  |
| 2048  | 41        | 21.69%  |
| 16384 | 22        | 11.64%  |
| 1024  | 15        | 7.94%   |
| 32768 | 7         | 3.7%    |
| 512   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 21.79%  |
| 2667    | 29        | 16.2%   |
| 3200    | 18        | 10.06%  |
| 1333    | 18        | 10.06%  |
| 2400    | 8         | 4.47%   |
| 2133    | 7         | 3.91%   |
| 800     | 7         | 3.91%   |
| 667     | 7         | 3.91%   |
| 1334    | 5         | 2.79%   |
| Unknown | 5         | 2.79%   |
| 3600    | 4         | 2.23%   |
| 400     | 4         | 2.23%   |
| 2048    | 3         | 1.68%   |
| 333     | 3         | 1.68%   |
| 4800    | 2         | 1.12%   |
| 4199    | 2         | 1.12%   |
| 3266    | 2         | 1.12%   |
| 3000    | 2         | 1.12%   |
| 2933    | 2         | 1.12%   |
| 1067    | 2         | 1.12%   |
| 6000    | 1         | 0.56%   |
| 5600    | 1         | 0.56%   |
| 3500    | 1         | 0.56%   |
| 2800    | 1         | 0.56%   |
| 2666    | 1         | 0.56%   |
| 1867    | 1         | 0.56%   |
| 1632    | 1         | 0.56%   |
| 1400    | 1         | 0.56%   |
| 975     | 1         | 0.56%   |
| 533     | 1         | 0.56%   |

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


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer       | 1         | 20%     |
| HP LaserJet 1020                 | 1         | 20%     |
| HP HP LaserJet M14-M17           | 1         | 20%     |
| Canon LaserShot LBP-1120 Printer | 1         | 20%     |
| Canon iP7200 series              | 1         | 20%     |

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
| Chicony Electronics                    | 30        | 18.75%  |
| IMC Networks                           | 25        | 15.63%  |
| Realtek Semiconductor                  | 15        | 9.38%   |
| Microdia                               | 11        | 6.88%   |
| Quanta                                 | 9         | 5.63%   |
| Logitech                               | 8         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.38%   |
| Bison Electronics                      | 6         | 3.75%   |
| Syntek                                 | 4         | 2.5%    |
| Sunplus Innovation Technology          | 4         | 2.5%    |
| Z-Star Microelectronics                | 3         | 1.88%   |
| Silicon Motion                         | 3         | 1.88%   |
| Luxvisions Innotech Limited            | 3         | 1.88%   |
| Lite-On Technology                     | 3         | 1.88%   |
| Apple                                  | 3         | 1.88%   |
| Acer                                   | 3         | 1.88%   |
| Suyin                                  | 2         | 1.25%   |
| Samsung Electronics                    | 2         | 1.25%   |
| KYE Systems (Mouse Systems)            | 2         | 1.25%   |
| Alcor Micro                            | 2         | 1.25%   |
| YGTek                                  | 1         | 0.63%   |
| Trust                                  | 1         | 0.63%   |
| SunplusIT                              | 1         | 0.63%   |
| Sonix Technology                       | 1         | 0.63%   |
| Ricoh                                  | 1         | 0.63%   |
| Primax Electronics                     | 1         | 0.63%   |
| Pixart Imaging                         | 1         | 0.63%   |
| Microsoft                              | 1         | 0.63%   |
| Importek                               | 1         | 0.63%   |
| Genesys Logic                          | 1         | 0.63%   |
| GEMBIRD                                | 1         | 0.63%   |
| ezcap                                  | 1         | 0.63%   |
| Cubeternet                             | 1         | 0.63%   |
| Aveo Technology                        | 1         | 0.63%   |
| ALi                                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 7         | 4.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 3.75%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 6         | 3.75%   |
| Realtek Integrated_Webcam_HD                                 | 5         | 3.13%   |
| Quanta HP HD Camera                                          | 4         | 2.5%    |
| Logitech Webcam C270                                         | 4         | 2.5%    |
| IMC Networks Integrated Camera                               | 4         | 2.5%    |
| Syntek Lenovo EasyCamera                                     | 3         | 1.88%   |
| Quanta HP TrueVision HD Camera                               | 3         | 1.88%   |
| Microdia Integrated_Webcam_HD                                | 3         | 1.88%   |
| Microdia Camera                                              | 3         | 1.88%   |
| Chicony HD WebCam                                            | 3         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 3         | 1.88%   |
| Z-Star Venus USB2.0 Camera                                   | 2         | 1.25%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.25%   |
| Realtek USB Camera                                           | 2         | 1.25%   |
| Realtek EasyCamera                                           | 2         | 1.25%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.25%   |
| Lite-On HP HD Webcam                                         | 2         | 1.25%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.25%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.25%   |
| Chicony EasyCamera                                           | 2         | 1.25%   |
| Bison Integrated Camera                                      | 2         | 1.25%   |
| Apple FaceTime HD Camera                                     | 2         | 1.25%   |
| Acer SunplusIT Integrated Camera                             | 2         | 1.25%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.63%   |
| YGTek Webcam                                                 | 1         | 0.63%   |
| Trust Full HD Webcam                                         | 1         | 0.63%   |
| Syntek Integrated Camera                                     | 1         | 0.63%   |
| Suyin HP Truevision HD                                       | 1         | 0.63%   |
| Suyin HD WebCam                                              | 1         | 0.63%   |
| SunplusIT Integrated Camera                                  | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.63%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.63%   |
| Sunplus HD WebCam                                            | 1         | 0.63%   |
| Sunplus Asus Webcam                                          | 1         | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 0.63%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 33.33%  |
| Synaptics                  | 8         | 26.67%  |
| Shenzhen Goodix Technology | 4         | 13.33%  |
| Elan Microelectronics      | 4         | 13.33%  |
| Upek                       | 2         | 6.67%   |
| LighTuning Technology      | 1         | 3.33%   |
| AuthenTec                  | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 13.33%  |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 10%     |
| Elan ELAN:Fingerprint                                     | 3         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 6.67%   |
| Validity Sensors Fingerprint scanner                      | 2         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 6.67%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 6.67%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 3.33%   |
| Validity Sensors Synaptics WBDI                           | 1         | 3.33%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 3.33%   |
| Synaptics TouchPad                                        | 1         | 3.33%   |
| Synaptics  WBDI                                           | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 3.33%   |
| Elan ELAN:ARM-M4                                          | 1         | 3.33%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 33.33%  |
| O2 Micro              | 1         | 33.33%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 33.33%  |
| Broadcom 5880                                     | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 183       | 74.69%  |
| 1     | 50        | 20.41%  |
| 2     | 11        | 4.49%   |
| 3     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 44.12%  |
| Graphics card         | 24        | 35.29%  |
| Net/wireless          | 5         | 7.35%   |
| Sound                 | 2         | 2.94%   |
| Multimedia controller | 2         | 2.94%   |
| Chipcard              | 2         | 2.94%   |
| Camera                | 2         | 2.94%   |
| Storage               | 1         | 1.47%   |

