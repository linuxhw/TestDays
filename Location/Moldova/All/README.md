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

Total: 340

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek  | ROG Zephyrus G14 GA401IH... | Notebook    | [e19fea8a49](https://linux-hardware.org/?probe=e19fea8a49) | May 06, 2024 |
| HP       | 250 G4                      | Notebook    | [6c2d10b0b4](https://linux-hardware.org/?probe=6c2d10b0b4) | May 05, 2024 |
| Sony     | SVF1521C5E                  | Notebook    | [9a899f2e80](https://linux-hardware.org/?probe=9a899f2e80) | Apr 28, 2024 |
| Lenovo   | Yoga Pro 7 14APH8 82Y8      | Notebook    | [e36ba9916d](https://linux-hardware.org/?probe=e36ba9916d) | Apr 22, 2024 |
| Dell     | Inspiron 3593               | Notebook    | [e1b99394fb](https://linux-hardware.org/?probe=e1b99394fb) | Apr 13, 2024 |
| Olimex   | A20-OLinuXino-LIME2-eMMC    | Soc         | [37be09f11b](https://linux-hardware.org/?probe=37be09f11b) | Apr 11, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X150... | Notebook    | [92dd6dd367](https://linux-hardware.org/?probe=92dd6dd367) | Mar 31, 2024 |
| Gigabyte | B550M K                     | Desktop     | [bfc7e96b9c](https://linux-hardware.org/?probe=bfc7e96b9c) | Mar 24, 2024 |
| Lenovo   | 0B98401 PRO                 | Desktop     | [5059aeedf0](https://linux-hardware.org/?probe=5059aeedf0) | Mar 23, 2024 |
| Lenovo   | 0B98401 PRO                 | Desktop     | [8b49c50089](https://linux-hardware.org/?probe=8b49c50089) | Mar 21, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X415... | Notebook    | [cd86953989](https://linux-hardware.org/?probe=cd86953989) | Feb 18, 2024 |
| ASRock   | X570 Phantom Gaming 4S      | Desktop     | [56e7d1d3ea](https://linux-hardware.org/?probe=56e7d1d3ea) | Feb 18, 2024 |
| ASRock   | X570 Phantom Gaming 4S      | Desktop     | [01e9c9ed92](https://linux-hardware.org/?probe=01e9c9ed92) | Feb 13, 2024 |
| HP       | EliteBook 840 G5            | Notebook    | [bdd9d20df9](https://linux-hardware.org/?probe=bdd9d20df9) | Feb 04, 2024 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ROSA R10            | 21        | 8.02%   |
| Ubuntu 20.04        | 15        | 5.73%   |
| Ubuntu 18.04        | 15        | 5.73%   |
| ROSA R11            | 14        | 5.34%   |
| Ubuntu 22.04        | 11        | 4.2%    |
| ROSA R8             | 10        | 3.82%   |
| ROSA R11.1          | 10        | 3.82%   |
| ROSA R8.1           | 8         | 3.05%   |
| Arch Rolling        | 8         | 3.05%   |
| OpenMandriva 4.2    | 6         | 2.29%   |
| OpenMandriva 4.3    | 5         | 1.91%   |
| Linux Mint 21.1     | 5         | 1.91%   |
| Linux Mint 20.1     | 5         | 1.91%   |
| KDE neon 20.04      | 5         | 1.91%   |
| Fedora 39           | 5         | 1.91%   |
| ROSA R9             | 4         | 1.53%   |
| ROSA 12.2           | 4         | 1.53%   |
| Manjaro             | 4         | 1.53%   |
| Arch                | 4         | 1.53%   |
| Ubuntu 22.10        | 3         | 1.15%   |
| ROSA 12.3           | 3         | 1.15%   |
| Linux Mint 19.1     | 3         | 1.15%   |
| Fedora 36           | 3         | 1.15%   |
| Fedora 34           | 3         | 1.15%   |
| Debian 11           | 3         | 1.15%   |
| Zorin 16            | 2         | 0.76%   |
| Ubuntu 19.10        | 2         | 0.76%   |
| Ubuntu 16.04        | 2         | 0.76%   |
| ROSA 12.1           | 2         | 0.76%   |
| Pop!_OS 21.04       | 2         | 0.76%   |
| Pop!_OS 20.10       | 2         | 0.76%   |
| OpenMandriva 23.08  | 2         | 0.76%   |
| Linux Mint 21.2     | 2         | 0.76%   |
| Linux Mint 20.2     | 2         | 0.76%   |
| Linux Mint 20       | 2         | 0.76%   |
| Linux Mint 19.3     | 2         | 0.76%   |
| KDE neon 22.04      | 2         | 0.76%   |
| EndeavourOS Rolling | 2         | 0.76%   |
| Debian 12           | 2         | 0.76%   |
| BlackPanther 18.1   | 2         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 69        | 27.49%  |
| Ubuntu        | 54        | 21.51%  |
| Linux Mint    | 23        | 9.16%   |
| Fedora        | 16        | 6.37%   |
| OpenMandriva  | 15        | 5.98%   |
| Manjaro       | 12        | 4.78%   |
| Arch          | 12        | 4.78%   |
| Pop!_OS       | 7         | 2.79%   |
| KDE neon      | 7         | 2.79%   |
| Debian        | 6         | 2.39%   |
| Kali          | 5         | 1.99%   |
| Endless       | 4         | 1.59%   |
| Zorin         | 2         | 0.8%    |
| SteamOS       | 2         | 0.8%    |
| Kubuntu       | 2         | 0.8%    |
| EndeavourOS   | 2         | 0.8%    |
| BuildRoot     | 2         | 0.8%    |
| BlackPanther  | 2         | 0.8%    |
| ArcoLinux     | 2         | 0.8%    |
| Ubuntu MATE   | 1         | 0.4%    |
| Ubuntu Budgie | 1         | 0.4%    |
| Nobara        | 1         | 0.4%    |
| Lubuntu       | 1         | 0.4%    |
| Gentoo        | 1         | 0.4%    |
| Ctlos         | 1         | 0.4%    |
| ALT Linux     | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 10        | 3.64%   |
| 5.10.14-desktop-1omv4002            | 6         | 2.18%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 6         | 2.18%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6         | 2.18%   |
| 5.16.7-desktop-1omv4003             | 5         | 1.82%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 5         | 1.82%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 5         | 1.82%   |
| 5.15.0-41-generic                   | 4         | 1.45%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 4         | 1.45%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 4         | 1.45%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 4         | 1.45%   |
| 5.8.0-33-generic                    | 3         | 1.09%   |
| 6.6.8-arch1-1                       | 2         | 0.73%   |
| 5.4.32-generic-2rosa-x86_64         | 2         | 0.73%   |
| 5.4.0-48-generic                    | 2         | 0.73%   |
| 5.4.0-37-generic                    | 2         | 0.73%   |
| 5.17.11-generic-2rosa2021.1-x86_64  | 2         | 0.73%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 2         | 0.73%   |
| 5.15.0-88-generic                   | 2         | 0.73%   |
| 5.15.0-67-generic                   | 2         | 0.73%   |
| 5.15.0-58-generic                   | 2         | 0.73%   |
| 5.11.0-7614-generic                 | 2         | 0.73%   |
| 5.11.0-41-generic                   | 2         | 0.73%   |
| 5.11.0-34-generic                   | 2         | 0.73%   |
| 5.11.0-25-generic                   | 2         | 0.73%   |
| 5.10.2-2-MANJARO                    | 2         | 0.73%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 2         | 0.73%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 2         | 0.73%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 2         | 0.73%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 2         | 0.73%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 2         | 0.73%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 2         | 0.73%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 2         | 0.73%   |
| 6.8.6-200.fc39.x86_64               | 1         | 0.36%   |
| 6.8.4-arch1-1                       | 1         | 0.36%   |
| 6.8.1-arch1-1                       | 1         | 0.36%   |
| 6.8.1-060801-generic                | 1         | 0.36%   |
| 6.8.0-31-generic                    | 1         | 0.36%   |
| 6.7.9-204.fsync.fc39.x86_64         | 1         | 0.36%   |
| 6.7.4-200.fc39.x86_64               | 1         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 27        | 10.04%  |
| 5.15.0  | 19        | 7.06%   |
| 5.4.0   | 18        | 6.69%   |
| 4.9.60  | 13        | 4.83%   |
| 5.11.0  | 12        | 4.46%   |
| 5.8.0   | 7         | 2.6%    |
| 4.1.34  | 7         | 2.6%    |
| 5.10.14 | 6         | 2.23%   |
| 4.9.20  | 6         | 2.23%   |
| 5.3.0   | 5         | 1.86%   |
| 5.19.0  | 5         | 1.86%   |
| 5.16.7  | 5         | 1.86%   |
| 5.13.0  | 5         | 1.86%   |
| 5.10.74 | 5         | 1.86%   |
| 5.0.0   | 4         | 1.49%   |
| 4.9.155 | 4         | 1.49%   |
| 4.18.0  | 4         | 1.49%   |
| 6.5.0   | 3         | 1.12%   |
| 6.2.0   | 3         | 1.12%   |
| 5.4.32  | 3         | 1.12%   |
| 4.9.124 | 3         | 1.12%   |
| 4.1.38  | 3         | 1.12%   |
| 6.8.1   | 2         | 0.74%   |
| 6.6.8   | 2         | 0.74%   |
| 6.1.1   | 2         | 0.74%   |
| 6.1.0   | 2         | 0.74%   |
| 5.9.3   | 2         | 0.74%   |
| 5.8.18  | 2         | 0.74%   |
| 5.18.1  | 2         | 0.74%   |
| 5.17.11 | 2         | 0.74%   |
| 5.15.79 | 2         | 0.74%   |
| 5.10.2  | 2         | 0.74%   |
| 5.10.0  | 2         | 0.74%   |
| 4.9.95  | 2         | 0.74%   |
| 4.9.9   | 2         | 0.74%   |
| 4.9.76  | 2         | 0.74%   |
| 4.9.41  | 2         | 0.74%   |
| 4.10.0  | 2         | 0.74%   |
| 4.1.25  | 2         | 0.74%   |
| 6.8.6   | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 12.17%  |
| 5.15    | 29        | 11.03%  |
| 4.15    | 27        | 10.27%  |
| 5.4     | 23        | 8.75%   |
| 5.10    | 20        | 7.6%    |
| 5.11    | 13        | 4.94%   |
| 4.1     | 12        | 4.56%   |
| 5.8     | 9         | 3.42%   |
| 5.19    | 7         | 2.66%   |
| 5.18    | 7         | 2.66%   |
| 5.16    | 7         | 2.66%   |
| 6.6     | 6         | 2.28%   |
| 6.2     | 6         | 2.28%   |
| 6.1     | 6         | 2.28%   |
| 5.17    | 6         | 2.28%   |
| 5.13    | 6         | 2.28%   |
| 6.8     | 5         | 1.9%    |
| 5.3     | 5         | 1.9%    |
| 5.0     | 5         | 1.9%    |
| 6.5     | 4         | 1.52%   |
| 6.4     | 4         | 1.52%   |
| 4.18    | 4         | 1.52%   |
| 6.7     | 3         | 1.14%   |
| 6.3     | 2         | 0.76%   |
| 5.9     | 2         | 0.76%   |
| 5.14    | 2         | 0.76%   |
| 5.12    | 2         | 0.76%   |
| 4.10    | 2         | 0.76%   |
| 6.0     | 1         | 0.38%   |
| 5.6     | 1         | 0.38%   |
| 5.5     | 1         | 0.38%   |
| 5.2     | 1         | 0.38%   |
| 5.1     | 1         | 0.38%   |
| 4.19    | 1         | 0.38%   |
| 4.16    | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 233       | 92.83%  |
| i686   | 17        | 6.77%   |
| armv7l | 1         | 0.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 70        | 27.24%  |
| KDE5            | 64        | 24.9%   |
| KDE4            | 47        | 18.29%  |
| Unknown         | 19        | 7.39%   |
| X-Cinnamon      | 16        | 6.23%   |
| XFCE            | 15        | 5.84%   |
| MATE            | 5         | 1.95%   |
| LXQt            | 4         | 1.56%   |
| KDE             | 3         | 1.17%   |
| sway            | 2         | 0.78%   |
| GNOME Flashback | 2         | 0.78%   |
| Cinnamon        | 2         | 0.78%   |
| xinitrc         | 1         | 0.39%   |
| LXDE            | 1         | 0.39%   |
| KDE6            | 1         | 0.39%   |
| i3              | 1         | 0.39%   |
| Hyprland        | 1         | 0.39%   |
| Deepin          | 1         | 0.39%   |
| Budgie          | 1         | 0.39%   |
| bspwm           | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 192       | 75.29%  |
| Wayland | 49        | 19.22%  |
| Unknown | 14        | 5.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 30.62%  |
| SDDM    | 56        | 21.71%  |
| KDM     | 47        | 18.22%  |
| GDM     | 29        | 11.24%  |
| LightDM | 21        | 8.14%   |
| GDM3    | 18        | 6.98%   |
| TDM     | 8         | 3.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 86        | 33.86%  |
| Unknown | 75        | 29.53%  |
| ru_RU   | 63        | 24.8%   |
| ro_RO   | 10        | 3.94%   |
| C       | 7         | 2.76%   |
| en_GB   | 5         | 1.97%   |
| ru_UA   | 3         | 1.18%   |
| uk_UA   | 1         | 0.39%   |
| nl_NL   | 1         | 0.39%   |
| en_150  | 1         | 0.39%   |
| de_DE   | 1         | 0.39%   |
| C.UTF8  | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 138       | 54.76%  |
| EFI  | 114       | 45.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 165       | 65.48%  |
| Unknown | 37        | 14.68%  |
| Btrfs   | 22        | 8.73%   |
| Overlay | 16        | 6.35%   |
| Tmpfs   | 8         | 3.17%   |
| Xfs     | 2         | 0.79%   |
| F2fs    | 1         | 0.4%    |
| Ext2    | 1         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 98        | 38.28%  |
| Unknown | 88        | 34.38%  |
| MBR     | 70        | 27.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 225       | 88.58%  |
| Yes       | 29        | 11.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 175       | 68.9%   |
| Yes       | 79        | 31.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 66        | 26.51%  |
| Lenovo              | 39        | 15.66%  |
| Hewlett-Packard     | 36        | 14.46%  |
| Gigabyte Technology | 20        | 8.03%   |
| Dell                | 18        | 7.23%   |
| Acer                | 13        | 5.22%   |
| Biostar             | 11        | 4.42%   |
| ASRock              | 7         | 2.81%   |
| MSI                 | 6         | 2.41%   |
| Toshiba             | 5         | 2.01%   |
| Timi                | 5         | 2.01%   |
| Samsung Electronics | 4         | 1.61%   |
| Sony                | 3         | 1.2%    |
| Apple               | 3         | 1.2%    |
| Unknown             | 2         | 0.8%    |
| Valve               | 1         | 0.4%    |
| System76            | 1         | 0.4%    |
| Olimex              | 1         | 0.4%    |
| Jumper              | 1         | 0.4%    |
| Intel               | 1         | 0.4%    |
| HUAWEI              | 1         | 0.4%    |
| Google              | 1         | 0.4%    |
| Gateway             | 1         | 0.4%    |
| Foxconn             | 1         | 0.4%    |
| ECS                 | 1         | 0.4%    |
| Chuwi               | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Timi TM1701                            | 3         | 1.2%    |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA | 3         | 1.2%    |
| Unknown                                | 3         | 1.2%    |
| Samsung RV413/RV513                    | 2         | 0.8%    |
| Lenovo Legion Y530-15ICH 81FV          | 2         | 0.8%    |
| HP ProBook 450 G7                      | 2         | 0.8%    |
| HP Compaq Presario CQ60                | 2         | 0.8%    |
| Gigabyte H81M-S2PV                     | 2         | 0.8%    |
| Gigabyte H61M-S1                       | 2         | 0.8%    |
| Dell Inspiron 3593                     | 2         | 0.8%    |
| ASUS VivoBook S15 X510UF               | 2         | 0.8%    |
| ASUS H110M-R                           | 2         | 0.8%    |
| ASUS All Series                        | 2         | 0.8%    |
| Valve Jupiter                          | 1         | 0.4%    |
| Toshiba TECRA Z40-B                    | 1         | 0.4%    |
| Toshiba Satellite S50-B                | 1         | 0.4%    |
| Toshiba Satellite Pro S300L            | 1         | 0.4%    |
| Toshiba Satellite C55D-A               | 1         | 0.4%    |
| Toshiba Satellite A210                 | 1         | 0.4%    |
| Timi A35S                              | 1         | 0.4%    |
| Timi A34R                              | 1         | 0.4%    |
| System76 Adder WS                      | 1         | 0.4%    |
| Sony VPCF13WFX                         | 1         | 0.4%    |
| Sony VPCEB1J8E                         | 1         | 0.4%    |
| Sony SVF1521C5E                        | 1         | 0.4%    |
| Samsung R517/R717                      | 1         | 0.4%    |
| Samsung 300E4C/300E5C/300E7C           | 1         | 0.4%    |
| Olimex A20-OLinuXino-LIME2-eMMC        | 1         | 0.4%    |
| MSI Pro 3130 Microtower PC             | 1         | 0.4%    |
| MSI MS-7695                            | 1         | 0.4%    |
| MSI MS-7592                            | 1         | 0.4%    |
| MSI MS-7529                            | 1         | 0.4%    |
| MSI MS-7309                            | 1         | 0.4%    |
| MSI CR610                              | 1         | 0.4%    |
| Lenovo Z51-70 80K6                     | 1         | 0.4%    |
| Lenovo Yoga Pro 7 14APH8 82Y8          | 1         | 0.4%    |
| Lenovo Yoga 730-15IKB 81CU             | 1         | 0.4%    |
| Lenovo Y520-15IKBN 80WK                | 1         | 0.4%    |
| Lenovo V580 20147                      | 1         | 0.4%    |
| Lenovo ThinkStation C30 113787G        | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 13        | 5.22%   |
| ASUS VivoBook      | 11        | 4.42%   |
| Lenovo ThinkPad    | 9         | 3.61%   |
| Acer Aspire        | 9         | 3.61%   |
| HP ProBook         | 7         | 2.81%   |
| Dell Inspiron      | 7         | 2.81%   |
| HP EliteBook       | 6         | 2.41%   |
| Dell Latitude      | 6         | 2.41%   |
| Toshiba Satellite  | 4         | 1.61%   |
| Lenovo Legion      | 4         | 1.61%   |
| HP Pavilion        | 4         | 1.61%   |
| HP Compaq          | 4         | 1.61%   |
| ASUS ROG           | 4         | 1.61%   |
| ASUS PRIME         | 4         | 1.61%   |
| Timi TM1701        | 3         | 1.2%    |
| ASUS TUF           | 3         | 1.2%    |
| Unknown            | 3         | 1.2%    |
| Samsung RV413      | 2         | 0.8%    |
| Lenovo Yoga        | 2         | 0.8%    |
| Lenovo ThinkBook   | 2         | 0.8%    |
| HP ProDesk         | 2         | 0.8%    |
| HP Laptop          | 2         | 0.8%    |
| HP ENVY            | 2         | 0.8%    |
| HP 250             | 2         | 0.8%    |
| Gigabyte Z690      | 2         | 0.8%    |
| Gigabyte H81M-S2PV | 2         | 0.8%    |
| Gigabyte H61M-S1   | 2         | 0.8%    |
| Dell Vostro        | 2         | 0.8%    |
| ASUS ZenBook       | 2         | 0.8%    |
| ASUS P8H61-M       | 2         | 0.8%    |
| ASUS M5A78L-M      | 2         | 0.8%    |
| ASUS H110M-R       | 2         | 0.8%    |
| ASUS All           | 2         | 0.8%    |
| Valve Jupiter      | 1         | 0.4%    |
| Toshiba TECRA      | 1         | 0.4%    |
| Timi A35S          | 1         | 0.4%    |
| Timi A34R          | 1         | 0.4%    |
| System76 Adder     | 1         | 0.4%    |
| Sony VPCF13WFX     | 1         | 0.4%    |
| Sony VPCEB1J8E     | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 23        | 9.24%   |
| 2018    | 23        | 9.24%   |
| 2019    | 22        | 8.84%   |
| 2012    | 22        | 8.84%   |
| 2011    | 22        | 8.84%   |
| 2017    | 19        | 7.63%   |
| 2020    | 16        | 6.43%   |
| 2009    | 16        | 6.43%   |
| 2013    | 15        | 6.02%   |
| 2015    | 12        | 4.82%   |
| 2010    | 12        | 4.82%   |
| 2016    | 11        | 4.42%   |
| 2022    | 9         | 3.61%   |
| 2014    | 9         | 3.61%   |
| 2008    | 5         | 2.01%   |
| 2023    | 4         | 1.61%   |
| 2007    | 4         | 1.61%   |
| 2006    | 3         | 1.2%    |
| 2005    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 156       | 62.65%  |
| Desktop        | 81        | 32.53%  |
| Mini pc        | 4         | 1.61%   |
| All in one     | 4         | 1.61%   |
| Convertible    | 2         | 0.8%    |
| System on chip | 1         | 0.4%    |
| Server         | 1         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 236       | 94.78%  |
| Enabled  | 13        | 5.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 248       | 99.6%   |
| Yes  | 1         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 63        | 25.1%   |
| 4.01-8.0    | 52        | 20.72%  |
| 8.01-16.0   | 46        | 18.33%  |
| 16.01-24.0  | 42        | 16.73%  |
| 32.01-64.0  | 19        | 7.57%   |
| 1.01-2.0    | 12        | 4.78%   |
| 2.01-3.0    | 8         | 3.19%   |
| 64.01-256.0 | 4         | 1.59%   |
| 24.01-32.0  | 3         | 1.2%    |
| 0.51-1.0    | 2         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 87        | 32.83%  |
| 2.01-3.0   | 47        | 17.74%  |
| 0.51-1.0   | 45        | 16.98%  |
| 4.01-8.0   | 42        | 15.85%  |
| 3.01-4.0   | 29        | 10.94%  |
| 8.01-16.0  | 7         | 2.64%   |
| 0.01-0.5   | 4         | 1.51%   |
| 16.01-24.0 | 3         | 1.13%   |
| 24.01-32.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 170       | 67.73%  |
| 2      | 57        | 22.71%  |
| 3      | 17        | 6.77%   |
| 4      | 5         | 1.99%   |
| 0      | 2         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 69.08%  |
| Yes       | 77        | 30.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 86.4%   |
| No        | 34        | 13.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 74.7%   |
| No        | 63        | 25.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 58.8%   |
| No        | 103       | 41.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Moldova | 249       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Chisinau        | 139       | 54.94%  |
| Tiraspol        | 46        | 18.18%  |
| Bălţi         | 10        | 3.95%   |
| Tighina         | 6         | 2.37%   |
| Straseni        | 5         | 1.98%   |
| Hincesti        | 3         | 1.19%   |
| Tintareni       | 2         | 0.79%   |
| Soroca          | 2         | 0.79%   |
| Orhei           | 2         | 0.79%   |
| Ialoveni        | 2         | 0.79%   |
| Floresti        | 2         | 0.79%   |
| Congaz          | 2         | 0.79%   |
| Căușeni       | 2         | 0.79%   |
| Cahul           | 2         | 0.79%   |
| Zaicana         | 1         | 0.4%    |
| Vişniovca      | 1         | 0.4%    |
| Tvardița       | 1         | 0.4%    |
| Soldanesti      | 1         | 0.4%    |
| Sofia           | 1         | 0.4%    |
| Singera         | 1         | 0.4%    |
| Rîbniţa       | 1         | 0.4%    |
| Rezina          | 1         | 0.4%    |
| Rautel          | 1         | 0.4%    |
| Prajila         | 1         | 0.4%    |
| Pociumbeni      | 1         | 0.4%    |
| Nisporeni       | 1         | 0.4%    |
| Mascauti        | 1         | 0.4%    |
| Lapusna         | 1         | 0.4%    |
| Ilenuta         | 1         | 0.4%    |
| Gangura         | 1         | 0.4%    |
| Floreni         | 1         | 0.4%    |
| Edineţ         | 1         | 0.4%    |
| Durlesti        | 1         | 0.4%    |
| Drochia         | 1         | 0.4%    |
| Donduseni       | 1         | 0.4%    |
| Criuleni        | 1         | 0.4%    |
| Cricova         | 1         | 0.4%    |
| Crasnoarmeiscoe | 1         | 0.4%    |
| Cojusna         | 1         | 0.4%    |
| Cenac           | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 65        | 78     | 19.06%  |
| WDC                         | 41        | 44     | 12.02%  |
| Seagate                     | 39        | 46     | 11.44%  |
| Toshiba                     | 37        | 43     | 10.85%  |
| Kingston                    | 20        | 24     | 5.87%   |
| Hitachi                     | 19        | 22     | 5.57%   |
| SanDisk                     | 13        | 14     | 3.81%   |
| SK hynix                    | 10        | 10     | 2.93%   |
| Micron Technology           | 10        | 13     | 2.93%   |
| SPCC                        | 7         | 9      | 2.05%   |
| Unknown                     | 6         | 6      | 1.76%   |
| Transcend                   | 6         | 6      | 1.76%   |
| Intel                       | 5         | 7      | 1.47%   |
| HGST                        | 4         | 4      | 1.17%   |
| Apacer                      | 4         | 4      | 1.17%   |
| Netac                       | 3         | 3      | 0.88%   |
| Maxtor                      | 3         | 4      | 0.88%   |
| Kingston Technology Company | 3         | 3      | 0.88%   |
| GOODRAM                     | 3         | 3      | 0.88%   |
| Crucial                     | 3         | 4      | 0.88%   |
| A-DATA Technology           | 3         | 3      | 0.88%   |
| UMIS                        | 2         | 2      | 0.59%   |
| Phison                      | 2         | 3      | 0.59%   |
| Patriot                     | 2         | 2      | 0.59%   |
| OCZ                         | 2         | 2      | 0.59%   |
| KIOXIA                      | 2         | 2      | 0.59%   |
| Intenso                     | 2         | 2      | 0.59%   |
| Fujitsu                     | 2         | 2      | 0.59%   |
| China                       | 2         | 2      | 0.59%   |
| ZOTAC                       | 1         | 3      | 0.29%   |
| XPG                         | 1         | 1      | 0.29%   |
| Team                        | 1         | 1      | 0.29%   |
| StoreJet                    | 1         | 1      | 0.29%   |
| Solid State Storage         | 1         | 1      | 0.29%   |
| PNY                         | 1         | 1      | 0.29%   |
| O2 Micro                    | 1         | 1      | 0.29%   |
| Micron/Crucial Technology   | 1         | 1      | 0.29%   |
| LITEONIT                    | 1         | 1      | 0.29%   |
| Lite-On Technology          | 1         | 1      | 0.29%   |
| Leven                       | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SHFS37A120G 120GB SSD                    | 7         | 1.99%   |
| Samsung NVMe SSD Drive 512GB                      | 6         | 1.71%   |
| Toshiba DT01ACA050 500GB                          | 5         | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB                    | 5         | 1.42%   |
| Toshiba MQ04ABF100 1TB                            | 4         | 1.14%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.14%   |
| Seagate ST500LT012-9WS142 500GB                   | 4         | 1.14%   |
| Samsung SSD 860 EVO 500GB                         | 4         | 1.14%   |
| Toshiba HDWD110 1TB                               | 3         | 0.85%   |
| Toshiba DT01ACA100 1TB                            | 3         | 0.85%   |
| Seagate ST2000DM008-2FR102 2TB                    | 3         | 0.85%   |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.85%   |
| Samsung MZVLW256HEHP-00000 256GB                  | 3         | 0.85%   |
| Samsung HD502HJ 500GB                             | 3         | 0.85%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 3         | 0.85%   |
| Kingston SA400S37240G 240GB SSD                   | 3         | 0.85%   |
| Hitachi HTS543232A7A384 320GB                     | 3         | 0.85%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 2         | 0.57%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.57%   |
| WDC WD10SPZX-22Z10T1 1TB                          | 2         | 0.57%   |
| Unknown MMC Card  64GB                            | 2         | 0.57%   |
| Transcend TS64GSSD370S 64GB                       | 2         | 0.57%   |
| Transcend TS120GMTS420S 120GB SSD                 | 2         | 0.57%   |
| Toshiba MQ01ACF032 320GB                          | 2         | 0.57%   |
| Toshiba MQ01ABF050 500GB                          | 2         | 0.57%   |
| Toshiba DT01ACA200 2TB                            | 2         | 0.57%   |
| SPCC Solid State Disk 128GB                       | 2         | 0.57%   |
| SK hynix NVMe SSD Drive 256GB                     | 2         | 0.57%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.57%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.57%   |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 0.57%   |
| Seagate ST4000VM000-2AF166 4TB                    | 2         | 0.57%   |
| Seagate ST3160023A 160GB                          | 2         | 0.57%   |
| Seagate ST1000DL002-9TT153 1TB                    | 2         | 0.57%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                 | 2         | 0.57%   |
| Samsung SSD 980 500GB                             | 2         | 0.57%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 2         | 0.57%   |
| Samsung HD251HJ 250GB                             | 2         | 0.57%   |
| Samsung HD082GJ 80GB                              | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 46     | 24.68%  |
| WDC                 | 38        | 41     | 24.05%  |
| Toshiba             | 30        | 36     | 18.99%  |
| Samsung Electronics | 19        | 22     | 12.03%  |
| Hitachi             | 19        | 22     | 12.03%  |
| HGST                | 4         | 4      | 2.53%   |
| Maxtor              | 3         | 4      | 1.9%    |
| Fujitsu             | 2         | 2      | 1.27%   |
| Unknown             | 1         | 1      | 0.63%   |
| StoreJet            | 1         | 1      | 0.63%   |
| Hewlett-Packard     | 1         | 1      | 0.63%   |
| ASMT                | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 21     | 18.48%  |
| Samsung Electronics | 15        | 18     | 16.3%   |
| SanDisk             | 7         | 8      | 7.61%   |
| Transcend           | 6         | 6      | 6.52%   |
| SPCC                | 6         | 8      | 6.52%   |
| Apacer              | 4         | 4      | 4.35%   |
| Toshiba             | 3         | 3      | 3.26%   |
| Micron Technology   | 3         | 3      | 3.26%   |
| GOODRAM             | 3         | 3      | 3.26%   |
| Crucial             | 3         | 4      | 3.26%   |
| WDC                 | 2         | 2      | 2.17%   |
| Patriot             | 2         | 2      | 2.17%   |
| OCZ                 | 2         | 2      | 2.17%   |
| Netac               | 2         | 2      | 2.17%   |
| Intenso             | 2         | 2      | 2.17%   |
| China               | 2         | 2      | 2.17%   |
| ZOTAC               | 1         | 3      | 1.09%   |
| Team                | 1         | 1      | 1.09%   |
| PNY                 | 1         | 1      | 1.09%   |
| LITEONIT            | 1         | 1      | 1.09%   |
| Leven               | 1         | 1      | 1.09%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.09%   |
| KingDian            | 1         | 1      | 1.09%   |
| Intel               | 1         | 1      | 1.09%   |
| Goldkey             | 1         | 1      | 1.09%   |
| Gigabyte Technology | 1         | 2      | 1.09%   |
| CHN25SATAS1         | 1         | 1      | 1.09%   |
| AMD                 | 1         | 1      | 1.09%   |
| A-DATA Technology   | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 138       | 181    | 45.25%  |
| SSD  | 83        | 106    | 27.21%  |
| NVMe | 79        | 101    | 25.9%   |
| MMC  | 5         | 5      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 185       | 283    | 67.77%  |
| NVMe | 79        | 101    | 28.94%  |
| MMC  | 5         | 5      | 1.83%   |
| SAS  | 4         | 4      | 1.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 151       | 212    | 70.23%  |
| 0.51-1.0   | 47        | 58     | 21.86%  |
| 1.01-2.0   | 13        | 13     | 6.05%   |
| 3.01-4.0   | 3         | 3      | 1.4%    |
| 4.01-10.0  | 1         | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 26.72%  |
| 251-500        | 66        | 25.19%  |
| 501-1000       | 35        | 13.36%  |
| 51-100         | 27        | 10.31%  |
| 1-20           | 24        | 9.16%   |
| 1001-2000      | 15        | 5.73%   |
| 21-50          | 10        | 3.82%   |
| Unknown        | 8         | 3.05%   |
| More than 3000 | 4         | 1.53%   |
| 2001-3000      | 3         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 118       | 44.36%  |
| 21-50          | 42        | 15.79%  |
| 51-100         | 33        | 12.41%  |
| 101-250        | 25        | 9.4%    |
| 251-500        | 21        | 7.89%   |
| 501-1000       | 11        | 4.14%   |
| Unknown        | 8         | 3.01%   |
| 1001-2000      | 7         | 2.63%   |
| More than 3000 | 1         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 5.88%   |
| Seagate ST3160023A 160GB          | 2         | 2      | 3.92%   |
| Samsung Electronics HD082GJ 80GB  | 2         | 2      | 3.92%   |
| Kingston SHFS37A120G 120GB SSD    | 2         | 4      | 3.92%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 3.92%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1         | 1      | 1.96%   |
| WDC WD800JD-22LSA0 80GB           | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 1.96%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1         | 1      | 1.96%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1         | 1      | 1.96%   |
| WDC WD5000AADS-56S9B1 500GB       | 1         | 1      | 1.96%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 1.96%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1         | 1      | 1.96%   |
| WDC WD1600BEVS-60RST0 160GB       | 1         | 1      | 1.96%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 1.96%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 1.96%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 1.96%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 1.96%   |
| Team L5 LITE SSD 240GB            | 1         | 1      | 1.96%   |
| SPCC SSD162 120GB                 | 1         | 1      | 1.96%   |
| SPCC Solid State Disk 56GB        | 1         | 2      | 1.96%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.96%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 1.96%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1         | 1      | 1.96%   |
| Seagate ST31000340NS 1TB          | 1         | 1      | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB    | 1         | 1      | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 1.96%   |
| Seagate ST1000DL002-9TT153 1TB    | 1         | 1      | 1.96%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 1.96%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 1.96%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 1.96%   |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 1.96%   |
| Maxtor STM380215AS 80GB           | 1         | 1      | 1.96%   |
| Maxtor STM3160811AS 160GB         | 1         | 1      | 1.96%   |
| Maxtor STM3160211AS 160GB         | 1         | 1      | 1.96%   |
| Maxtor 4R120L0 122GB              | 1         | 1      | 1.96%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 1.96%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 24%     |
| WDC                 | 11        | 11     | 22%     |
| Hitachi             | 7         | 9      | 14%     |
| Samsung Electronics | 5         | 5      | 10%     |
| Toshiba             | 4         | 4      | 8%      |
| Maxtor              | 3         | 4      | 6%      |
| SPCC                | 2         | 3      | 4%      |
| Kingston            | 2         | 4      | 4%      |
| Team                | 1         | 1      | 2%      |
| SanDisk             | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 28.57%  |
| WDC                 | 10        | 10     | 23.81%  |
| Hitachi             | 7         | 9      | 16.67%  |
| Samsung Electronics | 5         | 5      | 11.9%   |
| Toshiba             | 4         | 4      | 9.52%   |
| Maxtor              | 3         | 4      | 7.14%   |
| Fujitsu             | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 45     | 82.61%  |
| SSD  | 8         | 11     | 17.39%  |

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
| Works    | 125       | 191    | 45.62%  |
| Detected | 99        | 141    | 36.13%  |
| Malfunc  | 46        | 56     | 16.79%  |
| Failed   | 4         | 5      | 1.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 151       | 48.24%  |
| AMD                            | 60        | 19.17%  |
| Samsung Electronics            | 31        | 9.9%    |
| SK hynix                       | 10        | 3.19%   |
| Nvidia                         | 10        | 3.19%   |
| SanDisk                        | 7         | 2.24%   |
| Micron Technology              | 7         | 2.24%   |
| Kingston Technology Company    | 6         | 1.92%   |
| JMicron Technology             | 5         | 1.6%    |
| Toshiba America Info Systems   | 4         | 1.28%   |
| ASMedia Technology             | 3         | 0.96%   |
| ADATA Technology               | 3         | 0.96%   |
| Union Memory (Shenzhen)        | 2         | 0.64%   |
| Phison Electronics             | 2         | 0.64%   |
| KIOXIA                         | 2         | 0.64%   |
| Solid State Storage Technology | 1         | 0.32%   |
| Silicon Motion                 | 1         | 0.32%   |
| Realtek Semiconductor          | 1         | 0.32%   |
| O2 Micro                       | 1         | 0.32%   |
| Netac Technology               | 1         | 0.32%   |
| Micron/Crucial Technology      | 1         | 0.32%   |
| Marvell Technology Group       | 1         | 0.32%   |
| Lite-On Technology             | 1         | 0.32%   |
| Lenovo                         | 1         | 0.32%   |
| Hewlett-Packard                | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31        | 8.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14        | 3.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 13        | 3.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 3.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 2.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.36%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 4         | 1.08%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 4         | 1.08%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4         | 1.08%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 4         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.81%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.81%   |
| Nvidia MCP61 IDE                                                                        | 3         | 0.81%   |
| JMicron JMB368 IDE controller                                                           | 3         | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 3         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.81%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 179       | 55.08%  |
| NVMe | 79        | 24.31%  |
| IDE  | 53        | 16.31%  |
| RAID | 14        | 4.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 169       | 67.87%  |
| AMD    | 79        | 31.73%  |
| ARM    | 1         | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.2%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.2%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.2%    |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.2%    |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.2%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.8%    |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 0.8%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.8%    |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.8%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.8%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.8%    |
| Intel Core i3-5010U CPU @ 2.10GHz             | 2         | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.8%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.8%    |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.8%    |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.8%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.8%    |
| Intel 12th Gen Core i5-12450H                 | 2         | 0.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.8%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.8%    |
| AMD Ryzen 5 3600X 6-Core Processor            | 2         | 0.8%    |
| AMD Phenom II X6 1055T Processor              | 2         | 0.8%    |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.8%    |
| AMD Athlon II X2 280 Processor                | 2         | 0.8%    |
| Intel Xeon CPU E5405 @ 2.00GHz                | 1         | 0.4%    |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz            | 1         | 0.4%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.4%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 53        | 21.29%  |
| Intel Core i7                  | 27        | 10.84%  |
| Intel Core i3                  | 22        | 8.84%   |
| Intel Celeron                  | 18        | 7.23%   |
| AMD Ryzen 5                    | 17        | 6.83%   |
| Other                          | 14        | 5.62%   |
| Intel Pentium                  | 13        | 5.22%   |
| AMD Ryzen 7                    | 12        | 4.82%   |
| AMD Athlon II X2               | 7         | 2.81%   |
| Intel Core 2 Duo               | 5         | 2.01%   |
| AMD E                          | 5         | 2.01%   |
| AMD Athlon 64 X2               | 5         | 2.01%   |
| Intel Pentium Silver           | 4         | 1.61%   |
| AMD A4                         | 4         | 1.61%   |
| Intel Pentium Dual-Core        | 3         | 1.2%    |
| AMD Ryzen 3                    | 3         | 1.2%    |
| AMD FX                         | 3         | 1.2%    |
| AMD E1                         | 3         | 1.2%    |
| AMD A10                        | 3         | 1.2%    |
| Intel Xeon                     | 2         | 0.8%    |
| Intel Pentium D                | 2         | 0.8%    |
| Intel Core i9                  | 2         | 0.8%    |
| Intel Atom                     | 2         | 0.8%    |
| AMD Sempron                    | 2         | 0.8%    |
| AMD Phenom II X6               | 2         | 0.8%    |
| AMD Athlon II X4               | 2         | 0.8%    |
| AMD Athlon                     | 2         | 0.8%    |
| Intel Pentium Dual             | 1         | 0.4%    |
| Intel Pentium 4                | 1         | 0.4%    |
| Intel Core 2 Quad              | 1         | 0.4%    |
| ARM Allwinner                  | 1         | 0.4%    |
| AMD V140                       | 1         | 0.4%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.4%    |
| AMD Ryzen 9                    | 1         | 0.4%    |
| AMD Ryzen 5 PRO                | 1         | 0.4%    |
| AMD Ryzen 3 PRO                | 1         | 0.4%    |
| AMD Phenom II X4               | 1         | 0.4%    |
| AMD A8                         | 1         | 0.4%    |
| AMD A6                         | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 111       | 44.4%   |
| 4       | 84        | 33.6%   |
| 6       | 22        | 8.8%    |
| 8       | 18        | 7.2%    |
| 1       | 5         | 2%      |
| Unknown | 4         | 1.6%    |
| 10      | 3         | 1.2%    |
| 16      | 1         | 0.4%    |
| 14      | 1         | 0.4%    |
| 12      | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 247       | 99.2%   |
| 2      | 2         | 0.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 144       | 57.6%   |
| 1       | 102       | 40.8%   |
| Unknown | 4         | 1.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 245       | 98.39%  |
| Unknown        | 4         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 26.19%  |
| 0x206a7    | 13        | 5.16%   |
| 0x806ea    | 11        | 4.37%   |
| 0x306c3    | 9         | 3.57%   |
| 0x306a9    | 9         | 3.57%   |
| 0x05000119 | 8         | 3.17%   |
| 0x806ec    | 7         | 2.78%   |
| 0x010000c8 | 7         | 2.78%   |
| 0x906e9    | 6         | 2.38%   |
| 0x40651    | 5         | 1.98%   |
| 0x08600106 | 5         | 1.98%   |
| 0x906ea    | 4         | 1.59%   |
| 0x706a1    | 4         | 1.59%   |
| 0x506e3    | 4         | 1.59%   |
| 0x406e3    | 4         | 1.59%   |
| 0x306d4    | 4         | 1.59%   |
| 0x1067a    | 4         | 1.59%   |
| 0x806e9    | 3         | 1.19%   |
| 0x6fd      | 3         | 1.19%   |
| 0x506c9    | 3         | 1.19%   |
| 0x0a50000c | 3         | 1.19%   |
| 0x08108109 | 3         | 1.19%   |
| 0x03000027 | 3         | 1.19%   |
| 0xf47      | 2         | 0.79%   |
| 0xa0655    | 2         | 0.79%   |
| 0xa0652    | 2         | 0.79%   |
| 0x90672    | 2         | 0.79%   |
| 0x806c1    | 2         | 0.79%   |
| 0x706e5    | 2         | 0.79%   |
| 0x706a8    | 2         | 0.79%   |
| 0x406c4    | 2         | 0.79%   |
| 0x406c3    | 2         | 0.79%   |
| 0x30678    | 2         | 0.79%   |
| 0x20655    | 2         | 0.79%   |
| 0x106e5    | 2         | 0.79%   |
| 0x10676    | 2         | 0.79%   |
| 0x08701021 | 2         | 0.79%   |
| 0x08608103 | 2         | 0.79%   |
| 0x08108102 | 2         | 0.79%   |
| 0x06001119 | 2         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 16.06%  |
| SandyBridge      | 17        | 6.83%   |
| Haswell          | 17        | 6.83%   |
| Zen 2            | 14        | 5.62%   |
| K10              | 14        | 5.62%   |
| Skylake          | 11        | 4.42%   |
| IvyBridge        | 11        | 4.42%   |
| Zen 3            | 8         | 3.21%   |
| Silvermont       | 8         | 3.21%   |
| Goldmont plus    | 8         | 3.21%   |
| Bobcat           | 8         | 3.21%   |
| Unknown          | 8         | 3.21%   |
| Penryn           | 7         | 2.81%   |
| Zen+             | 6         | 2.41%   |
| IceLake          | 6         | 2.41%   |
| Broadwell        | 6         | 2.41%   |
| Alderlake Hybrid | 6         | 2.41%   |
| TigerLake        | 5         | 2.01%   |
| Piledriver       | 5         | 2.01%   |
| K8 Hammer        | 5         | 2.01%   |
| Core             | 5         | 2.01%   |
| CometLake        | 5         | 2.01%   |
| Zen              | 4         | 1.61%   |
| NetBurst         | 4         | 1.61%   |
| K10 Llano        | 4         | 1.61%   |
| Westmere         | 3         | 1.2%    |
| K8 & K10 hybrid  | 3         | 1.2%    |
| Goldmont         | 3         | 1.2%    |
| Nehalem          | 2         | 0.8%    |
| Bonnell          | 2         | 0.8%    |
| Tremont          | 1         | 0.4%    |
| Steamroller      | 1         | 0.4%    |
| Puma             | 1         | 0.4%    |
| Bulldozer        | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 140       | 46.98%  |
| Nvidia | 81        | 27.18%  |
| AMD    | 77        | 25.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.92%   |
| Intel UHD Graphics 620                                                                   | 13        | 4.26%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 2.95%   |
| Intel HD Graphics 630                                                                    | 6         | 1.97%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.31%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.31%   |
| Intel HD Graphics 620                                                                    | 4         | 1.31%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.31%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.98%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 0.98%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3         | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.98%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 0.98%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.98%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.66%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.66%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.66%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 99        | 39.29%  |
| 1 x AMD        | 59        | 23.41%  |
| 1 x Nvidia     | 41        | 16.27%  |
| Intel + Nvidia | 33        | 13.1%   |
| AMD + Nvidia   | 7         | 2.78%   |
| 2 x AMD        | 6         | 2.38%   |
| Intel + AMD    | 5         | 1.98%   |
| Other          | 2         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 206       | 80.16%  |
| Proprietary | 36        | 14.01%  |
| Unknown     | 15        | 5.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 48.85%  |
| 0.01-0.5   | 47        | 18.08%  |
| 1.01-2.0   | 43        | 16.54%  |
| 3.01-4.0   | 18        | 6.92%   |
| 0.51-1.0   | 15        | 5.77%   |
| 7.01-8.0   | 6         | 2.31%   |
| 5.01-6.0   | 3         | 1.15%   |
| 2.01-3.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 15.73%  |
| Samsung Electronics     | 39        | 14.61%  |
| Chimei Innolux          | 28        | 10.49%  |
| LG Display              | 22        | 8.24%   |
| BOE                     | 22        | 8.24%   |
| Philips                 | 17        | 6.37%   |
| Goldstar                | 17        | 6.37%   |
| Dell                    | 14        | 5.24%   |
| AOC                     | 8         | 3%      |
| Acer                    | 8         | 3%      |
| Chi Mei Optoelectronics | 6         | 2.25%   |
| PANDA                   | 4         | 1.5%    |
| Lenovo                  | 4         | 1.5%    |
| InfoVision              | 4         | 1.5%    |
| Hewlett-Packard         | 4         | 1.5%    |
| Sharp                   | 3         | 1.12%   |
| CSO                     | 3         | 1.12%   |
| BenQ                    | 3         | 1.12%   |
| Apple                   | 3         | 1.12%   |
| ViewSonic               | 1         | 0.37%   |
| Valve                   | 1         | 0.37%   |
| Toshiba                 | 1         | 0.37%   |
| TMX                     | 1         | 0.37%   |
| Sony                    | 1         | 0.37%   |
| SAC                     | 1         | 0.37%   |
| Plain Tree Systems      | 1         | 0.37%   |
| Medion                  | 1         | 0.37%   |
| LG Electronics          | 1         | 0.37%   |
| KTC                     | 1         | 0.37%   |
| ITE                     | 1         | 0.37%   |
| Hitachi                 | 1         | 0.37%   |
| HannStar                | 1         | 0.37%   |
| GreenWood               | 1         | 0.37%   |
| ASUSTek Computer        | 1         | 0.37%   |
| Ancor Communications    | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 6         | 2.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 1.48%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 3         | 1.11%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 1.11%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 1.11%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 3         | 1.11%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 3         | 1.11%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 2         | 0.74%   |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch | 2         | 0.74%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.74%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 2         | 0.74%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.74%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2         | 0.74%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 2         | 0.74%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.74%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 2         | 0.74%   |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch               | 1         | 0.37%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.37%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                      | 1         | 0.37%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 0.37%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch | 1         | 0.37%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.37%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.37%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch               | 1         | 0.37%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 300x230mm 14.9-inch  | 1         | 0.37%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch    | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 112       | 44.09%  |
| 1366x768 (WXGA)    | 55        | 21.65%  |
| 2560x1440 (QHD)    | 16        | 6.3%    |
| 1600x900 (HD+)     | 14        | 5.51%   |
| 1280x1024 (SXGA)   | 14        | 5.51%   |
| 3840x2160 (4K)     | 7         | 2.76%   |
| 1680x1050 (WSXGA+) | 6         | 2.36%   |
| 1440x900 (WXGA+)   | 5         | 1.97%   |
| 1280x800 (WXGA)    | 5         | 1.97%   |
| 2560x1600          | 4         | 1.57%   |
| 2560x1080          | 2         | 0.79%   |
| 1600x1200          | 2         | 0.79%   |
| 1024x768 (XGA)     | 2         | 0.79%   |
| 800x1280           | 1         | 0.39%   |
| 3456x2160          | 1         | 0.39%   |
| 3200x1080          | 1         | 0.39%   |
| 3072x1920          | 1         | 0.39%   |
| 2880x1800          | 1         | 0.39%   |
| 2160x1440          | 1         | 0.39%   |
| 1920x540           | 1         | 0.39%   |
| 1360x768           | 1         | 0.39%   |
| 1024x600           | 1         | 0.39%   |
| Unknown            | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 110       | 40.89%  |
| 24      | 18        | 6.69%   |
| 23      | 17        | 6.32%   |
| 14      | 17        | 6.32%   |
| 17      | 15        | 5.58%   |
| 27      | 14        | 5.2%    |
| 21      | 14        | 5.2%    |
| 19      | 12        | 4.46%   |
| 13      | 12        | 4.46%   |
| 20      | 10        | 3.72%   |
| 18      | 7         | 2.6%    |
| 11      | 4         | 1.49%   |
| 16      | 3         | 1.12%   |
| 84      | 2         | 0.74%   |
| 72      | 2         | 0.74%   |
| 34      | 2         | 0.74%   |
| 31      | 2         | 0.74%   |
| 12      | 2         | 0.74%   |
| 32      | 1         | 0.37%   |
| 26      | 1         | 0.37%   |
| 22      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |
| 7       | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 53.01%  |
| 501-600     | 46        | 17.29%  |
| 401-500     | 37        | 13.91%  |
| 351-400     | 17        | 6.39%   |
| 201-300     | 13        | 4.89%   |
| 1501-2000   | 4         | 1.5%    |
| 701-800     | 3         | 1.13%   |
| 601-700     | 3         | 1.13%   |
| 1-100       | 1         | 0.38%   |
| Unknown     | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 192       | 80.33%  |
| 16/10   | 21        | 8.79%   |
| 5/4     | 12        | 5.02%   |
| 4/3     | 8         | 3.35%   |
| 3/2     | 2         | 0.84%   |
| 21/9    | 2         | 0.84%   |
| 0.67    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 106       | 39.7%   |
| 201-250        | 42        | 15.73%  |
| 151-200        | 26        | 9.74%   |
| 81-90          | 25        | 9.36%   |
| 301-350        | 15        | 5.62%   |
| 141-150        | 12        | 4.49%   |
| 121-130        | 7         | 2.62%   |
| 111-120        | 7         | 2.62%   |
| 351-500        | 5         | 1.87%   |
| More than 1000 | 4         | 1.5%    |
| 51-60          | 4         | 1.5%    |
| 71-80          | 3         | 1.12%   |
| 251-300        | 3         | 1.12%   |
| 61-70          | 2         | 0.75%   |
| 131-140        | 2         | 0.75%   |
| 41-50          | 1         | 0.37%   |
| 1-40           | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |
| Unknown        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 87        | 33.08%  |
| 121-160       | 84        | 31.94%  |
| 101-120       | 72        | 27.38%  |
| 161-240       | 14        | 5.32%   |
| More than 240 | 3         | 1.14%   |
| 1-50          | 2         | 0.76%   |
| Unknown       | 1         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 212       | 84.46%  |
| 2     | 33        | 13.15%  |
| 0     | 6         | 2.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 160       | 44.2%   |
| Intel                             | 81        | 22.38%  |
| Qualcomm Atheros                  | 52        | 14.36%  |
| Broadcom                          | 18        | 4.97%   |
| Nvidia                            | 9         | 2.49%   |
| MediaTek                          | 9         | 2.49%   |
| Ralink                            | 5         | 1.38%   |
| Xiaomi                            | 4         | 1.1%    |
| Broadcom Limited                  | 4         | 1.1%    |
| TP-Link                           | 3         | 0.83%   |
| Marvell Technology Group          | 3         | 0.83%   |
| Huawei Technologies               | 2         | 0.55%   |
| Sierra Wireless                   | 1         | 0.28%   |
| Ralink Technology                 | 1         | 0.28%   |
| Qualcomm                          | 1         | 0.28%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.28%   |
| Mercucys                          | 1         | 0.28%   |
| JMicron Technology                | 1         | 0.28%   |
| ICS Advent                        | 1         | 0.28%   |
| Hewlett-Packard                   | 1         | 0.28%   |
| Ericsson Business Mobile Networks | 1         | 0.28%   |
| D-Link System                     | 1         | 0.28%   |
| D-Link                            | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 114       | 27.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 5.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 3.1%    |
| Intel Wireless 8265 / 8275                                             | 13        | 3.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 8         | 1.91%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 0.95%   |
| Nvidia MCP77 Ethernet                                                  | 4         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.95%   |
| Intel Wireless 7260                                                    | 4         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 0.95%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.72%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.72%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2         | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.48%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.48%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 34.55%  |
| Realtek Semiconductor | 45        | 23.56%  |
| Qualcomm Atheros      | 45        | 23.56%  |
| Broadcom              | 14        | 7.33%   |
| MediaTek              | 7         | 3.66%   |
| Ralink                | 5         | 2.62%   |
| TP-Link               | 3         | 1.57%   |
| Sierra Wireless       | 1         | 0.52%   |
| Ralink Technology     | 1         | 0.52%   |
| Mercucys              | 1         | 0.52%   |
| D-Link System         | 1         | 0.52%   |
| D-Link                | 1         | 0.52%   |
| Broadcom Limited      | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 6.81%   |
| Intel Wireless 8265 / 8275                                              | 13        | 6.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 5.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.19%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.09%   |
| Intel Wireless 7260                                                     | 4         | 2.09%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.05%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.05%   |
| Intel Wireless 8260                                                     | 2         | 1.05%   |
| Intel Wireless 7265                                                     | 2         | 1.05%   |
| Intel Wireless 3165                                                     | 2         | 1.05%   |
| Intel Wireless 3160                                                     | 2         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.05%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 145       | 64.73%  |
| Intel                    | 36        | 16.07%  |
| Qualcomm Atheros         | 9         | 4.02%   |
| Nvidia                   | 9         | 4.02%   |
| Broadcom                 | 6         | 2.68%   |
| Xiaomi                   | 4         | 1.79%   |
| Marvell Technology Group | 3         | 1.34%   |
| Broadcom Limited         | 3         | 1.34%   |
| MediaTek                 | 2         | 0.89%   |
| Huawei Technologies      | 2         | 0.89%   |
| Qualcomm                 | 1         | 0.45%   |
| JMicron Technology       | 1         | 0.45%   |
| ICS Advent               | 1         | 0.45%   |
| Hewlett-Packard          | 1         | 0.45%   |
| ASIX Electronics         | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 114       | 50.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 10.62%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.77%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.77%   |
| Nvidia MCP77 Ethernet                                                          | 4         | 1.77%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.33%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.33%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.88%   |
| MediaTek RMX3085                                                               | 2         | 0.88%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.88%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.88%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.88%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.88%   |
| Huawei E353/E3131                                                              | 2         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.44%   |
| Qualcomm SAMSUNG_Android                                                       | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.44%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.44%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.44%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.44%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 215       | 53.35%  |
| WiFi     | 186       | 46.15%  |
| Modem    | 1         | 0.25%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 142       | 56.35%  |
| Ethernet | 110       | 43.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 141       | 56.63%  |
| 1     | 107       | 42.97%  |
| 0     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 237       | 95.18%  |
| Yes  | 12        | 4.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 38.1%   |
| Realtek Semiconductor           | 20        | 13.61%  |
| IMC Networks                    | 20        | 13.61%  |
| Qualcomm Atheros Communications | 16        | 10.88%  |
| Foxconn / Hon Hai               | 7         | 4.76%   |
| Broadcom                        | 6         | 4.08%   |
| Lite-On Technology              | 5         | 3.4%    |
| Cambridge Silicon Radio         | 5         | 3.4%    |
| Apple                           | 3         | 2.04%   |
| Ralink Technology               | 2         | 1.36%   |
| Toshiba                         | 1         | 0.68%   |
| SiW                             | 1         | 0.68%   |
| Realtek                         | 1         | 0.68%   |
| Integrated System Solution      | 1         | 0.68%   |
| Hewlett-Packard                 | 1         | 0.68%   |
| Dell                            | 1         | 0.68%   |
| ASUSTek Computer                | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                                                             | 15        | 10.2%   |
| Intel Bluetooth Device                                                              | 13        | 8.84%   |
| Intel AX201 Bluetooth                                                               | 11        | 7.48%   |
| Intel Bluetooth wireless interface                                                  | 10        | 6.8%    |
| IMC Networks Bluetooth Radio                                                        | 10        | 6.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 6.12%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 5.44%   |
| Intel AX200 Bluetooth                                                               | 7         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.4%    |
| IMC Networks Bluetooth Device                                                       | 4         | 2.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.04%   |
| IMC Networks Wireless_Device                                                        | 3         | 2.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.36%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.36%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.36%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.36%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.68%   |
| SiW SiW                                                                             | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.68%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.68%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.68%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.68%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.68%   |
| Ralink CSR BS8510                                                                   | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.68%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.68%   |
| Intel AX211 Bluetooth                                                               | 1         | 0.68%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.68%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 0.68%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 166       | 51.71%  |
| AMD                       | 82        | 25.55%  |
| Nvidia                    | 55        | 17.13%  |
| Plantronics               | 4         | 1.25%   |
| Logitech                  | 2         | 0.62%   |
| Creative Labs             | 2         | 0.62%   |
| C-Media Electronics       | 2         | 0.62%   |
| Texas Instruments         | 1         | 0.31%   |
| SteelSeries ApS           | 1         | 0.31%   |
| Shenzhen Rapoo Technology | 1         | 0.31%   |
| Sennheiser Communications | 1         | 0.31%   |
| Kingston Technology       | 1         | 0.31%   |
| GN Netcom                 | 1         | 0.31%   |
| Giga-Byte Technology      | 1         | 0.31%   |
| fifine Microphone         | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 7.2%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 5.66%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 5.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 3.34%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 2.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.06%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.54%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.29%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.29%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 4         | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 4         | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 43        | 21.18%  |
| Unknown               | 38        | 18.72%  |
| SK hynix              | 28        | 13.79%  |
| Kingston              | 28        | 13.79%  |
| Micron Technology     | 12        | 5.91%   |
| GOODRAM               | 8         | 3.94%   |
| Transcend             | 5         | 2.46%   |
| G.Skill               | 4         | 1.97%   |
| Crucial               | 4         | 1.97%   |
| Unknown (ABCD)        | 3         | 1.48%   |
| Elpida                | 3         | 1.48%   |
| Corsair               | 3         | 1.48%   |
| Apacer                | 3         | 1.48%   |
| Ramaxel Technology    | 2         | 0.99%   |
| Patriot               | 2         | 0.99%   |
| Nanya Technology      | 2         | 0.99%   |
| A-DATA Technology     | 2         | 0.99%   |
| Wilk                  | 1         | 0.49%   |
| Unifosa               | 1         | 0.49%   |
| Team                  | 1         | 0.49%   |
| Silicon Power         | 1         | 0.49%   |
| SGS/Thomson           | 1         | 0.49%   |
| Kingmax Semiconductor | 1         | 0.49%   |
| Hexon                 | 1         | 0.49%   |
| Goldkey               | 1         | 0.49%   |
| Axiom                 | 1         | 0.49%   |
| AVEXIR                | 1         | 0.49%   |
| Avant                 | 1         | 0.49%   |
| ASint Technology      | 1         | 0.49%   |
| Unknown               | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 3         | 1.35%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.35%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 3         | 1.35%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.9%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 2         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 2         | 0.9%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.9%    |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 0.9%    |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                      | 2         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.9%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.9%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.9%    |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s            | 2         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.9%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 2         | 0.9%    |
| Wilk RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 0.45%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.45%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.45%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                     | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                       | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 37.71%  |
| DDR3    | 59        | 33.71%  |
| DDR2    | 13        | 7.43%   |
| Unknown | 11        | 6.29%   |
| SDRAM   | 10        | 5.71%   |
| LPDDR4  | 6         | 3.43%   |
| DDR5    | 3         | 1.71%   |
| DDR     | 3         | 1.71%   |
| LPDDR3  | 2         | 1.14%   |
| DRAM    | 2         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 55.56%  |
| DIMM         | 66        | 38.6%   |
| Row Of Chips | 9         | 5.26%   |
| FB-DIMM      | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 57        | 28.64%  |
| 8192  | 55        | 27.64%  |
| 2048  | 41        | 20.6%   |
| 16384 | 23        | 11.56%  |
| 1024  | 15        | 7.54%   |
| 32768 | 7         | 3.52%   |
| 512   | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 40        | 21.28%  |
| 2667    | 30        | 15.96%  |
| 3200    | 21        | 11.17%  |
| 1333    | 19        | 10.11%  |
| 2400    | 9         | 4.79%   |
| 2133    | 7         | 3.72%   |
| 800     | 7         | 3.72%   |
| 667     | 7         | 3.72%   |
| Unknown | 6         | 3.19%   |
| 1334    | 5         | 2.66%   |
| 3600    | 4         | 2.13%   |
| 400     | 4         | 2.13%   |
| 2048    | 3         | 1.6%    |
| 333     | 3         | 1.6%    |
| 4800    | 2         | 1.06%   |
| 4199    | 2         | 1.06%   |
| 3266    | 2         | 1.06%   |
| 3000    | 2         | 1.06%   |
| 2933    | 2         | 1.06%   |
| 1067    | 2         | 1.06%   |
| 6000    | 1         | 0.53%   |
| 5600    | 1         | 0.53%   |
| 4000    | 1         | 0.53%   |
| 3500    | 1         | 0.53%   |
| 2800    | 1         | 0.53%   |
| 2666    | 1         | 0.53%   |
| 1867    | 1         | 0.53%   |
| 1632    | 1         | 0.53%   |
| 1400    | 1         | 0.53%   |
| 975     | 1         | 0.53%   |
| 533     | 1         | 0.53%   |

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
| Chicony Electronics                    | 30        | 17.65%  |
| IMC Networks                           | 25        | 14.71%  |
| Realtek Semiconductor                  | 15        | 8.82%   |
| Microdia                               | 12        | 7.06%   |
| Quanta                                 | 9         | 5.29%   |
| Logitech                               | 9         | 5.29%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.12%   |
| Bison Electronics                      | 7         | 4.12%   |
| Syntek                                 | 4         | 2.35%   |
| Sunplus Innovation Technology          | 4         | 2.35%   |
| Luxvisions Innotech Limited            | 4         | 2.35%   |
| Lite-On Technology                     | 4         | 2.35%   |
| Apple                                  | 4         | 2.35%   |
| Z-Star Microelectronics                | 3         | 1.76%   |
| Suyin                                  | 3         | 1.76%   |
| Silicon Motion                         | 3         | 1.76%   |
| KYE Systems (Mouse Systems)            | 3         | 1.76%   |
| Acer                                   | 3         | 1.76%   |
| Sonix Technology                       | 2         | 1.18%   |
| Samsung Electronics                    | 2         | 1.18%   |
| Alcor Micro                            | 2         | 1.18%   |
| YGTek                                  | 1         | 0.59%   |
| Trust                                  | 1         | 0.59%   |
| SunplusIT                              | 1         | 0.59%   |
| ShineTech                              | 1         | 0.59%   |
| Ricoh                                  | 1         | 0.59%   |
| Primax Electronics                     | 1         | 0.59%   |
| Pixart Imaging                         | 1         | 0.59%   |
| Microsoft                              | 1         | 0.59%   |
| Importek                               | 1         | 0.59%   |
| Genesys Logic                          | 1         | 0.59%   |
| GEMBIRD                                | 1         | 0.59%   |
| ezcap                                  | 1         | 0.59%   |
| Cubeternet                             | 1         | 0.59%   |
| Aveo Technology                        | 1         | 0.59%   |
| ALi                                    | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 7         | 4.12%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 3.53%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 6         | 3.53%   |
| Realtek Integrated_Webcam_HD                                 | 4         | 2.35%   |
| Quanta HP HD Camera                                          | 4         | 2.35%   |
| Microdia Integrated_Webcam_HD                                | 4         | 2.35%   |
| Logitech Webcam C270                                         | 4         | 2.35%   |
| IMC Networks Integrated Camera                               | 4         | 2.35%   |
| Syntek Lenovo EasyCamera                                     | 3         | 1.76%   |
| Quanta HP TrueVision HD Camera                               | 3         | 1.76%   |
| Microdia Camera                                              | 3         | 1.76%   |
| Chicony HD WebCam                                            | 3         | 1.76%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 3         | 1.76%   |
| Z-Star Venus USB2.0 Camera                                   | 2         | 1.18%   |
| Sonix USB2.0 HD UVC WebCam                                   | 2         | 1.18%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.18%   |
| Realtek USB Camera                                           | 2         | 1.18%   |
| Realtek EasyCamera                                           | 2         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.18%   |
| Lite-On HP HD Webcam                                         | 2         | 1.18%   |
| Lite-On HP HD Camera                                         | 2         | 1.18%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.18%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.18%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.18%   |
| Chicony EasyCamera                                           | 2         | 1.18%   |
| Bison SunplusIT Integrated Camera                            | 2         | 1.18%   |
| Bison Integrated Camera                                      | 2         | 1.18%   |
| Apple FaceTime HD Camera                                     | 2         | 1.18%   |
| Acer Integrated Camera                                       | 2         | 1.18%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.59%   |
| YGTek Webcam                                                 | 1         | 0.59%   |
| Trust Full HD Webcam                                         | 1         | 0.59%   |
| Syntek Integrated Camera                                     | 1         | 0.59%   |
| Suyin HP Webcam                                              | 1         | 0.59%   |
| Suyin HP Truevision HD                                       | 1         | 0.59%   |
| Suyin HD WebCam                                              | 1         | 0.59%   |
| SunplusIT Integrated Camera                                  | 1         | 0.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.59%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.59%   |
| Sunplus HD WebCam                                            | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 33.33%  |
| O2 Micro              | 1         | 33.33%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 192       | 74.71%  |
| 1     | 54        | 21.01%  |
| 2     | 10        | 3.89%   |
| 3     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 41.67%  |
| Graphics card         | 26        | 36.11%  |
| Net/wireless          | 7         | 9.72%   |
| Sound                 | 2         | 2.78%   |
| Multimedia controller | 2         | 2.78%   |
| Chipcard              | 2         | 2.78%   |
| Camera                | 2         | 2.78%   |
| Storage               | 1         | 1.39%   |

