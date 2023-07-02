Kubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 687

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5450              | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| Dell          | G3 3590                     | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | MacBookPro12,1              | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Dell          | Latitude 3310               | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Proline       | V1165C4                     | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Samsung       | 550XCJ/550XCR               | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| PC Special... | Initia Ii 15                | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Acer          | Nitro AN515-56              | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| Acer          | Aspire A317-53              | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Dell          | Latitude E6500              | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Dell          | G15 5525                    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Acer          | Aspire A317-53              | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire A515-45              | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Acer          | Aspire V3-772               | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| Acer          | Aspire V3-772               | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Acer          | Aspire A317-53              | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Fujitsu       | LIFEBOOK U748               | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Dell          | XPS 15 7590                 | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| Dell          | Latitude E6500              | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| Dell          | G3 3590                     | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Latitude 7490               | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Dell          | Latitude 3570               | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Dell          | XPS 13 9300                 | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Razer         | Blade Pro 17 (2019)         | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| ASUSTek       | X750JB                      | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| Dell          | Inspiron 3593               | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Carbon Sys... | Iridium 14                  | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| Carbon Sys... | Iridium 14                  | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Unknown       | Unknown                     | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| HP            | Laptop 15-ef2xxx            | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| MSI           | Modern 15 A5M               | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Notebook      | NV4xPZ                      | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Carbon Sys... | Iridium 14                  | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | Latitude E6420              | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-52-generic    | 42        | 7.72%   |
| 5.15.0-56-generic    | 38        | 6.99%   |
| 5.15.0-58-generic    | 27        | 4.96%   |
| 5.15.0-53-generic    | 22        | 4.04%   |
| 5.15.0-48-generic    | 22        | 4.04%   |
| 5.15.0-60-generic    | 21        | 3.86%   |
| 5.15.0-47-generic    | 21        | 3.86%   |
| 5.15.0-46-generic    | 17        | 3.13%   |
| 5.15.0-43-generic    | 17        | 3.13%   |
| 5.15.0-41-generic    | 17        | 3.13%   |
| 5.15.0-40-generic    | 15        | 2.76%   |
| 5.15.0-25-generic    | 15        | 2.76%   |
| 5.19.0-35-generic    | 14        | 2.57%   |
| 5.19.0-32-generic    | 14        | 2.57%   |
| 5.15.0-50-generic    | 12        | 2.21%   |
| 5.15.0-27-generic    | 12        | 2.21%   |
| 5.15.0-67-generic    | 11        | 2.02%   |
| 5.19.0-41-generic    | 10        | 1.84%   |
| 5.19.0-38-generic    | 10        | 1.84%   |
| 5.15.0-33-generic    | 10        | 1.84%   |
| 5.15.0-57-generic    | 9         | 1.65%   |
| 5.19.0-42-generic    | 8         | 1.47%   |
| 5.15.0-71-generic    | 8         | 1.47%   |
| 5.19.0-43-generic    | 7         | 1.29%   |
| 5.15.0-39-generic    | 7         | 1.29%   |
| 5.15.0-69-generic    | 6         | 1.1%    |
| 5.19.0-45-generic    | 5         | 0.92%   |
| 5.15.0-72-generic    | 5         | 0.92%   |
| 5.15.0-43-lowlatency | 5         | 0.92%   |
| 5.15.0-37-generic    | 5         | 0.92%   |
| 5.15.0-73-generic    | 4         | 0.74%   |
| 5.15.0-35-generic    | 4         | 0.74%   |
| 5.15.0-30-generic    | 4         | 0.74%   |
| 5.15.0-18-generic    | 4         | 0.74%   |
| 5.19.0-46-generic    | 3         | 0.55%   |
| 5.19.0-40-generic    | 3         | 0.55%   |
| 5.17.0-1020-oem      | 3         | 0.55%   |
| 5.15.0-70-generic    | 3         | 0.55%   |
| 5.15.0-46-lowlatency | 3         | 0.55%   |
| 6.2.2-060202-generic | 2         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 392       | 76.12%  |
| 5.19.0  | 77        | 14.95%  |
| 5.17.0  | 8         | 1.55%   |
| 6.0.0   | 4         | 0.78%   |
| 6.1.0   | 3         | 0.58%   |
| 5.13.0  | 3         | 0.58%   |
| 6.2.2   | 2         | 0.39%   |
| 6.0.7   | 2         | 0.39%   |
| 5.19.5  | 2         | 0.39%   |
| 6.3.8   | 1         | 0.19%   |
| 6.3.4   | 1         | 0.19%   |
| 6.3.0   | 1         | 0.19%   |
| 6.2.8   | 1         | 0.19%   |
| 6.1.9   | 1         | 0.19%   |
| 6.1.12  | 1         | 0.19%   |
| 6.0.9   | 1         | 0.19%   |
| 6.0.6   | 1         | 0.19%   |
| 6.0.1   | 1         | 0.19%   |
| 5.19.2  | 1         | 0.19%   |
| 5.19.11 | 1         | 0.19%   |
| 5.18.6  | 1         | 0.19%   |
| 5.18.15 | 1         | 0.19%   |
| 5.18.10 | 1         | 0.19%   |
| 5.17.5  | 1         | 0.19%   |
| 5.17.4  | 1         | 0.19%   |
| 5.17.2  | 1         | 0.19%   |
| 5.16.2  | 1         | 0.19%   |
| 5.16.11 | 1         | 0.19%   |
| 5.15.65 | 1         | 0.19%   |
| 5.15.34 | 1         | 0.19%   |
| 5.14.0  | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 393       | 76.61%  |
| 5.19    | 81        | 15.79%  |
| 5.17    | 11        | 2.14%   |
| 6.0     | 8         | 1.56%   |
| 6.1     | 5         | 0.97%   |
| 6.3     | 3         | 0.58%   |
| 6.2     | 3         | 0.58%   |
| 5.18    | 3         | 0.58%   |
| 5.13    | 3         | 0.58%   |
| 5.16    | 2         | 0.39%   |
| 5.14    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 501       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 490       | 97.42%  |
| GNOME      | 4         | 0.8%    |
| KDE        | 3         | 0.6%    |
| XFCE       | 1         | 0.2%    |
| X-Cinnamon | 1         | 0.2%    |
| MATE       | 1         | 0.2%    |
| i3         | 1         | 0.2%    |
| GNUstep    | 1         | 0.2%    |
| Cinnamon   | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 476       | 94.44%  |
| Wayland | 21        | 4.17%   |
| Tty     | 7         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 380       | 75.55%  |
| Unknown | 87        | 17.3%   |
| GDM3    | 22        | 4.37%   |
| LightDM | 12        | 2.39%   |
| SLiM    | 1         | 0.2%    |
| LXDM    | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 255       | 50.7%   |
| de_DE   | 37        | 7.36%   |
| ru_RU   | 27        | 5.37%   |
| it_IT   | 27        | 5.37%   |
| en_GB   | 20        | 3.98%   |
| fr_FR   | 19        | 3.78%   |
| pl_PL   | 13        | 2.58%   |
| en_IN   | 13        | 2.58%   |
| es_ES   | 12        | 2.39%   |
| pt_BR   | 9         | 1.79%   |
| en_CA   | 7         | 1.39%   |
| en_AU   | 7         | 1.39%   |
| tr_TR   | 5         | 0.99%   |
| hu_HU   | 5         | 0.99%   |
| en_NZ   | 4         | 0.8%    |
| zh_CN   | 3         | 0.6%    |
| en_SG   | 3         | 0.6%    |
| en_PH   | 3         | 0.6%    |
| cs_CZ   | 3         | 0.6%    |
| nl_BE   | 2         | 0.4%    |
| fr_CH   | 2         | 0.4%    |
| es_MX   | 2         | 0.4%    |
| es_CL   | 2         | 0.4%    |
| en_ZA   | 2         | 0.4%    |
| Default | 2         | 0.4%    |
| zh_TW   | 1         | 0.2%    |
| sv_SE   | 1         | 0.2%    |
| sl_SI   | 1         | 0.2%    |
| pt_PT   | 1         | 0.2%    |
| lt_LT   | 1         | 0.2%    |
| ko_KR   | 1         | 0.2%    |
| fr_BE   | 1         | 0.2%    |
| fi_FI   | 1         | 0.2%    |
| et_EE   | 1         | 0.2%    |
| es_VE   | 1         | 0.2%    |
| es_EC   | 1         | 0.2%    |
| es_CR   | 1         | 0.2%    |
| es_CO   | 1         | 0.2%    |
| es_AR   | 1         | 0.2%    |
| en_DE   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 310       | 61.26%  |
| BIOS | 196       | 38.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 449       | 89.09%  |
| Btrfs   | 23        | 4.56%   |
| Overlay | 18        | 3.57%   |
| Tmpfs   | 9         | 1.79%   |
| Xfs     | 3         | 0.6%    |
| Zfs     | 1         | 0.2%    |
| Ext2    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 356       | 70.63%  |
| Unknown | 123       | 24.4%   |
| MBR     | 25        | 4.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 467       | 93.21%  |
| Yes       | 34        | 6.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 306       | 60.96%  |
| Yes       | 196       | 39.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 126       | 25.15%  |
| Hewlett-Packard                | 85        | 16.97%  |
| Dell                           | 81        | 16.17%  |
| ASUSTek Computer               | 41        | 8.18%   |
| Acer                           | 38        | 7.58%   |
| MSI                            | 18        | 3.59%   |
| HUAWEI                         | 14        | 2.79%   |
| Apple                          | 10        | 2%      |
| Samsung Electronics            | 9         | 1.8%    |
| Toshiba                        | 6         | 1.2%    |
| Google                         | 6         | 1.2%    |
| Notebook                       | 5         | 1%      |
| TUXEDO                         | 4         | 0.8%    |
| Timi                           | 4         | 0.8%    |
| Gigabyte Technology            | 4         | 0.8%    |
| Framework                      | 3         | 0.6%    |
| Alienware                      | 3         | 0.6%    |
| System76                       | 2         | 0.4%    |
| Sony                           | 2         | 0.4%    |
| Schenker                       | 2         | 0.4%    |
| Razer                          | 2         | 0.4%    |
| Panasonic                      | 2         | 0.4%    |
| HONOR                          | 2         | 0.4%    |
| Haier                          | 2         | 0.4%    |
| GPU Company                    | 2         | 0.4%    |
| Fujitsu                        | 2         | 0.4%    |
| Carbon Systems                 | 2         | 0.4%    |
| Unknown                        | 2         | 0.4%    |
| VALE                           | 1         | 0.2%    |
| TrekStor                       | 1         | 0.2%    |
| Thomson                        | 1         | 0.2%    |
| TerraQue                       | 1         | 0.2%    |
| Tactus                         | 1         | 0.2%    |
| Standard                       | 1         | 0.2%    |
| SLIMBOOK                       | 1         | 0.2%    |
| SK hynix                       | 1         | 0.2%    |
| Shanghai Zhaoxin Semiconductor | 1         | 0.2%    |
| SGIN                           | 1         | 0.2%    |
| Proline                        | 1         | 0.2%    |
| PC Specialist                  | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 1.2%    |
| HUAWEI HVY-WXX9                          | 5         | 1%      |
| HP 255 G8 Notebook PC                    | 4         | 0.8%    |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 3         | 0.6%    |
| HP ProBook 6470b                         | 3         | 0.6%    |
| HP Pavilion g6                           | 3         | 0.6%    |
| HP OMEN Laptop 15-en0xxx                 | 3         | 0.6%    |
| HP Laptop 15-ef2xxx                      | 3         | 0.6%    |
| HP EliteBook 845 G7 Notebook PC          | 3         | 0.6%    |
| Framework Laptop (12th Gen Intel Core)   | 3         | 0.6%    |
| Dell XPS 15 9560                         | 3         | 0.6%    |
| Dell Latitude 5420                       | 3         | 0.6%    |
| Dell Latitude 3420                       | 3         | 0.6%    |
| Timi TM1701                              | 2         | 0.4%    |
| Lenovo ThinkBook 15 G2 ITL 20VE          | 2         | 0.4%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 2         | 0.4%    |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7         | 2         | 0.4%    |
| Lenovo IdeaPad 3 15ADA05 81W1            | 2         | 0.4%    |
| HUAWEI CREM-WXX9                         | 2         | 0.4%    |
| HP ZBook 15 G6                           | 2         | 0.4%    |
| HP ProBook 6570b                         | 2         | 0.4%    |
| HP ProBook 440 G8 Notebook PC            | 2         | 0.4%    |
| HP Pavilion Laptop 15-eh1xxx             | 2         | 0.4%    |
| HP Pavilion Gaming Laptop 15-ec0xxx      | 2         | 0.4%    |
| HP Pavilion dv6                          | 2         | 0.4%    |
| HP Notebook                              | 2         | 0.4%    |
| HP Laptop 17-by3xxx                      | 2         | 0.4%    |
| HP Laptop 15-da0xxx                      | 2         | 0.4%    |
| HP EliteBook 8470p                       | 2         | 0.4%    |
| Haier A1420EM                            | 2         | 0.4%    |
| Dell XPS 15 9520                         | 2         | 0.4%    |
| Dell Precision 7540                      | 2         | 0.4%    |
| Dell Latitude E5450                      | 2         | 0.4%    |
| Dell G3 3590                             | 2         | 0.4%    |
| Carbon Systems Iridium 14                | 2         | 0.4%    |
| ASUS VivoBook_ASUSLaptop X3400PA_K3400PA | 2         | 0.4%    |
| Acer Swift SFX14-41G                     | 2         | 0.4%    |
| Acer Nitro AN517-51                      | 2         | 0.4%    |
| Acer Aspire E5-575G                      | 2         | 0.4%    |
| Acer Aspire A515-45                      | 2         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 62        | 12.38%  |
| Lenovo IdeaPad      | 32        | 6.39%   |
| Dell Latitude       | 27        | 5.39%   |
| Acer Aspire         | 21        | 4.19%   |
| Dell Inspiron       | 18        | 3.59%   |
| HP ProBook          | 15        | 2.99%   |
| HP Pavilion         | 15        | 2.99%   |
| HP Laptop           | 14        | 2.79%   |
| Dell XPS            | 13        | 2.59%   |
| HP EliteBook        | 12        | 2.4%    |
| ASUS VivoBook       | 10        | 2%      |
| Lenovo Legion       | 9         | 1.8%    |
| Dell Precision      | 9         | 1.8%    |
| Lenovo ThinkBook    | 8         | 1.6%    |
| Acer Nitro          | 8         | 1.6%    |
| Dell Vostro         | 6         | 1.2%    |
| Unknown             | 6         | 1.2%    |
| Toshiba Satellite   | 5         | 1%      |
| HUAWEI HVY-WXX9     | 5         | 1%      |
| HP OMEN             | 5         | 1%      |
| HP 255              | 5         | 1%      |
| HP ZBook            | 4         | 0.8%    |
| ASUS ROG            | 4         | 0.8%    |
| Acer Swift          | 4         | 0.8%    |
| Lenovo Yoga         | 3         | 0.6%    |
| HP ENVY             | 3         | 0.6%    |
| Framework Laptop    | 3         | 0.6%    |
| Dell G3             | 3         | 0.6%    |
| Dell G15            | 3         | 0.6%    |
| ASUS ASUS           | 3         | 0.6%    |
| Apple MacBookPro11  | 3         | 0.6%    |
| Acer Predator       | 3         | 0.6%    |
| TUXEDO InfinityBook | 2         | 0.4%    |
| Timi TM1701         | 2         | 0.4%    |
| Schenker XMG        | 2         | 0.4%    |
| Razer Blade         | 2         | 0.4%    |
| Notebook PD5x       | 2         | 0.4%    |
| MSI Raider          | 2         | 0.4%    |
| MSI Prestige        | 2         | 0.4%    |
| MSI Modern          | 2         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 107       | 21.36%  |
| 2020 | 75        | 14.97%  |
| 2022 | 60        | 11.98%  |
| 2019 | 47        | 9.38%   |
| 2012 | 38        | 7.58%   |
| 2018 | 25        | 4.99%   |
| 2017 | 23        | 4.59%   |
| 2016 | 23        | 4.59%   |
| 2014 | 22        | 4.39%   |
| 2013 | 22        | 4.39%   |
| 2011 | 20        | 3.99%   |
| 2015 | 15        | 2.99%   |
| 2010 | 8         | 1.6%    |
| 2023 | 5         | 1%      |
| 2008 | 5         | 1%      |
| 2007 | 4         | 0.8%    |
| 2009 | 2         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 501       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 428       | 84.75%  |
| Enabled  | 77        | 15.25%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 494       | 98.6%   |
| Yes  | 7         | 1.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 141       | 27.92%  |
| 16.01-24.0  | 132       | 26.14%  |
| 8.01-16.0   | 97        | 19.21%  |
| 32.01-64.0  | 56        | 11.09%  |
| 3.01-4.0    | 45        | 8.91%   |
| 64.01-256.0 | 17        | 3.37%   |
| 24.01-32.0  | 12        | 2.38%   |
| 2.01-3.0    | 3         | 0.59%   |
| 1.01-2.0    | 2         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 135       | 25.52%  |
| 4.01-8.0   | 126       | 23.82%  |
| 3.01-4.0   | 122       | 23.06%  |
| 1.01-2.0   | 108       | 20.42%  |
| 8.01-16.0  | 32        | 6.05%   |
| 16.01-24.0 | 3         | 0.57%   |
| 0.51-1.0   | 3         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 338       | 66.8%   |
| 2      | 140       | 27.67%  |
| 3      | 20        | 3.95%   |
| 4      | 6         | 1.19%   |
| 0      | 2         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 403       | 80.28%  |
| Yes       | 99        | 19.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 73.05%  |
| No        | 135       | 26.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 500       | 99.8%   |
| No        | 1         | 0.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 439       | 86.93%  |
| No        | 66        | 13.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 96        | 19.09%  |
| Germany     | 49        | 9.74%   |
| Italy       | 40        | 7.95%   |
| Russia      | 35        | 6.96%   |
| France      | 31        | 6.16%   |
| Poland      | 18        | 3.58%   |
| UK          | 15        | 2.98%   |
| Spain       | 15        | 2.98%   |
| Brazil      | 15        | 2.98%   |
| India       | 13        | 2.58%   |
| Hungary     | 10        | 1.99%   |
| Canada      | 9         | 1.79%   |
| Indonesia   | 8         | 1.59%   |
| Turkey      | 6         | 1.19%   |
| Switzerland | 6         | 1.19%   |
| Sweden      | 6         | 1.19%   |
| Czechia     | 6         | 1.19%   |
| Australia   | 6         | 1.19%   |
| Netherlands | 5         | 0.99%   |
| Mexico      | 5         | 0.99%   |
| Belgium     | 5         | 0.99%   |
| Slovenia    | 4         | 0.8%    |
| Portugal    | 4         | 0.8%    |
| Philippines | 4         | 0.8%    |
| New Zealand | 4         | 0.8%    |
| Greece      | 4         | 0.8%    |
| Estonia     | 4         | 0.8%    |
| Denmark     | 4         | 0.8%    |
| China       | 4         | 0.8%    |
| UAE         | 3         | 0.6%    |
| South Korea | 3         | 0.6%    |
| Singapore   | 3         | 0.6%    |
| Serbia      | 3         | 0.6%    |
| Romania     | 3         | 0.6%    |
| Lithuania   | 3         | 0.6%    |
| Finland     | 3         | 0.6%    |
| Bulgaria    | 3         | 0.6%    |
| Austria     | 3         | 0.6%    |
| Argentina   | 3         | 0.6%    |
| Thailand    | 2         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 13        | 2.51%   |
| Milan         | 11        | 2.13%   |
| Paris         | 8         | 1.55%   |
| Warsaw        | 7         | 1.35%   |
| Berlin        | 6         | 1.16%   |
| Castro Valley | 5         | 0.97%   |
| Bengaluru     | 5         | 0.97%   |
| St Petersburg | 4         | 0.77%   |
| Madrid        | 4         | 0.77%   |
| Wroclaw       | 3         | 0.58%   |
| Vladivostok   | 3         | 0.58%   |
| Vilnius       | 3         | 0.58%   |
| Turin         | 3         | 0.58%   |
| Tallinn       | 3         | 0.58%   |
| Singapore     | 3         | 0.58%   |
| Prague        | 3         | 0.58%   |
| Jakarta       | 3         | 0.58%   |
| Cologne       | 3         | 0.58%   |
| Budapest      | 3         | 0.58%   |
| Auckland      | 3         | 0.58%   |
| Adelaide      | 3         | 0.58%   |
| Zurich        | 2         | 0.39%   |
| Zagreb        | 2         | 0.39%   |
| Washington    | 2         | 0.39%   |
| Vienna        | 2         | 0.39%   |
| Taipei        | 2         | 0.39%   |
| Surabaya      | 2         | 0.39%   |
| Sundsvall     | 2         | 0.39%   |
| Sofia         | 2         | 0.39%   |
| Seattle       | 2         | 0.39%   |
| Sao Paulo     | 2         | 0.39%   |
| Samara        | 2         | 0.39%   |
| Salerno       | 2         | 0.39%   |
| Rome          | 2         | 0.39%   |
| Quito         | 2         | 0.39%   |
| Poznan        | 2         | 0.39%   |
| Porto         | 2         | 0.39%   |
| Parma         | 2         | 0.39%   |
| Nuremberg     | 2         | 0.39%   |
| Murska Sobota | 2         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 121       | 156    | 18.45%  |
| WDC                       | 66        | 78     | 10.06%  |
| SanDisk                   | 45        | 59     | 6.86%   |
| Kingston                  | 45        | 49     | 6.86%   |
| Seagate                   | 42        | 54     | 6.4%    |
| Toshiba                   | 37        | 49     | 5.64%   |
| SK hynix                  | 37        | 42     | 5.64%   |
| Unknown                   | 35        | 44     | 5.34%   |
| Intel                     | 25        | 28     | 3.81%   |
| Micron Technology         | 21        | 23     | 3.2%    |
| Crucial                   | 19        | 20     | 2.9%    |
| KIOXIA                    | 15        | 16     | 2.29%   |
| HGST                      | 13        | 14     | 1.98%   |
| Hitachi                   | 10        | 10     | 1.52%   |
| China                     | 8         | 11     | 1.22%   |
| A-DATA Technology         | 7         | 7      | 1.07%   |
| Unknown                   | 7         | 7      | 1.07%   |
| SPCC                      | 6         | 6      | 0.91%   |
| Apple                     | 6         | 7      | 0.91%   |
| SSSTC                     | 5         | 5      | 0.76%   |
| Phison Electronics        | 5         | 5      | 0.76%   |
| Phison                    | 5         | 5      | 0.76%   |
| LITEON                    | 5         | 5      | 0.76%   |
| Silicon Motion            | 4         | 4      | 0.61%   |
| Micron/Crucial Technology | 4         | 6      | 0.61%   |
| UMIS                      | 3         | 3      | 0.46%   |
| PNY                       | 3         | 3      | 0.46%   |
| Patriot                   | 3         | 3      | 0.46%   |
| Netac                     | 3         | 3      | 0.46%   |
| JMicron Technology        | 3         | 3      | 0.46%   |
| Union Memory              | 2         | 2      | 0.3%    |
| Smart                     | 2         | 2      | 0.3%    |
| SABRENT                   | 2         | 4      | 0.3%    |
| Realtek Semiconductor     | 2         | 2      | 0.3%    |
| LITEONIT                  | 2         | 2      | 0.3%    |
| GOODRAM                   | 2         | 2      | 0.3%    |
| Emtec                     | 2         | 2      | 0.3%    |
| ADATA Technology          | 2         | 3      | 0.3%    |
| YMTC                      | 1         | 1      | 0.15%   |
| VISIPRO                   | 1         | 2      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD                     | 8         | 1.15%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 1.01%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 1.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 1.01%   |
| Unknown                                             | 7         | 1.01%   |
| Unknown MMC Card  64GB                              | 6         | 0.87%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 0.87%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.87%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 0.72%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 5         | 0.72%   |
| Samsung SSD 980 PRO 1TB                             | 5         | 0.72%   |
| Samsung SSD 970 EVO Plus 250GB                      | 5         | 0.72%   |
| Samsung SSD 850 EVO 250GB                           | 5         | 0.72%   |
| Unknown MMC Card  32GB                              | 4         | 0.58%   |
| Unknown MMC Card  128GB                             | 4         | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 0.58%   |
| Seagate ST2000LM015-2E8174 2TB                      | 4         | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB                      | 4         | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.58%   |
| SanDisk NVMe SSD Drive 1TB                          | 4         | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB                        | 4         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 4         | 0.58%   |
| HGST HTS721010A9E630 1TB                            | 4         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.43%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB              | 3         | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.43%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 3         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 0.43%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.43%   |
| Samsung SSD 860 QVO 1TB                             | 3         | 0.43%   |
| Samsung PM9A1 NVMe 512GB                            | 3         | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 3         | 0.43%   |
| Samsung MZVLB1T0HBLR-000H1 1TB                      | 3         | 0.43%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 0.43%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 3         | 0.43%   |
| Micron 3400_MTFDKBA1T0TFH 1024GB                    | 3         | 0.43%   |
| Kingston SA2000M81000G 1TB                          | 3         | 0.43%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 41        | 53     | 36.61%  |
| WDC      | 26        | 27     | 23.21%  |
| Toshiba  | 17        | 24     | 15.18%  |
| HGST     | 13        | 14     | 11.61%  |
| Hitachi  | 10        | 10     | 8.93%   |
| USB3.0   | 1         | 1      | 0.89%   |
| Unknown  | 1         | 1      | 0.89%   |
| KESU     | 1         | 1      | 0.89%   |
| HGST HTS | 1         | 1      | 0.89%   |
| ASMT     | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 59     | 23.81%  |
| Kingston            | 28        | 30     | 14.81%  |
| SanDisk             | 21        | 29     | 11.11%  |
| Crucial             | 12        | 13     | 6.35%   |
| WDC                 | 11        | 17     | 5.82%   |
| China               | 7         | 10     | 3.7%    |
| LITEON              | 5         | 5      | 2.65%   |
| Intel               | 5         | 6      | 2.65%   |
| A-DATA Technology   | 5         | 5      | 2.65%   |
| Toshiba             | 4         | 7      | 2.12%   |
| SPCC                | 4         | 4      | 2.12%   |
| SK hynix            | 3         | 3      | 1.59%   |
| Patriot             | 3         | 3      | 1.59%   |
| Apple               | 3         | 3      | 1.59%   |
| Smart               | 2         | 2      | 1.06%   |
| Netac               | 2         | 2      | 1.06%   |
| Micron Technology   | 2         | 2      | 1.06%   |
| LITEONIT            | 2         | 2      | 1.06%   |
| GOODRAM             | 2         | 2      | 1.06%   |
| Emtec               | 2         | 2      | 1.06%   |
| Unknown             | 2         | 2      | 1.06%   |
| VISIPRO             | 1         | 2      | 0.53%   |
| Verbatim            | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| ShiJi               | 1         | 1      | 0.53%   |
| Ramos Technology    | 1         | 1      | 0.53%   |
| R580                | 1         | 1      | 0.53%   |
| PNY                 | 1         | 1      | 0.53%   |
| NGFF                | 1         | 1      | 0.53%   |
| HUSKY               | 1         | 2      | 0.53%   |
| HS-SSD-C100         | 1         | 1      | 0.53%   |
| HIKSEMI             | 1         | 1      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| External            | 1         | 1      | 0.53%   |
| Dogfish             | 1         | 1      | 0.53%   |
| CT1000P2            | 1         | 1      | 0.53%   |
| Corsair             | 1         | 1      | 0.53%   |
| BAITITON            | 1         | 1      | 0.53%   |
| Apacer              | 1         | 1      | 0.53%   |
| ADATA SU            | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 290       | 361    | 47.15%  |
| SSD     | 170       | 229    | 27.64%  |
| HDD     | 108       | 133    | 17.56%  |
| MMC     | 38        | 46     | 6.18%   |
| Unknown | 9         | 10     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 287       | 356    | 49.31%  |
| SATA | 231       | 335    | 39.69%  |
| MMC  | 38        | 46     | 6.53%   |
| SAS  | 26        | 42     | 4.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 167       | 228    | 61.62%  |
| 0.51-1.0   | 80        | 103    | 29.52%  |
| 1.01-2.0   | 20        | 23     | 7.38%   |
| 4.01-10.0  | 3         | 7      | 1.11%   |
| 3.01-4.0   | 1         | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 143       | 28.04%  |
| 101-250        | 120       | 23.53%  |
| 501-1000       | 100       | 19.61%  |
| 1001-2000      | 66        | 12.94%  |
| 51-100         | 29        | 5.69%   |
| 1-20           | 17        | 3.33%   |
| 2001-3000      | 15        | 2.94%   |
| More than 3000 | 12        | 2.35%   |
| 21-50          | 7         | 1.37%   |
| Unknown        | 1         | 0.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 122       | 23.6%   |
| 101-250        | 107       | 20.7%   |
| 21-50          | 75        | 14.51%  |
| 51-100         | 73        | 14.12%  |
| 251-500        | 71        | 13.73%  |
| 501-1000       | 40        | 7.74%   |
| 1001-2000      | 21        | 4.06%   |
| More than 3000 | 5         | 0.97%   |
| 2001-3000      | 2         | 0.39%   |
| Unknown        | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 5.88%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 2         | 2      | 5.88%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 2         | 2      | 5.88%   |
| Seagate ST2000LM007-1R8174 2TB                      | 2         | 2      | 5.88%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 2.94%   |
| VISIPRO SSD 256GB                                   | 1         | 2      | 2.94%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.94%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 2.94%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 2.94%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 1      | 2.94%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 2.94%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 2.94%   |
| Samsung Electronics MZVLQ512HBLU-00B00 512GB        | 1         | 1      | 2.94%   |
| R580 SSD 60GB                                       | 1         | 1      | 2.94%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 2.94%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 2.94%   |
| Hitachi HTS725050A7E630 500GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 2.94%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.94%   |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 2.94%   |
| Crucial CT1050MX300SSD1 1050GB                      | 1         | 1      | 2.94%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 2.94%   |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 2.94%   |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 2.94%   |
| A-DATA Technology FALCON 1TB                        | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 14.71%  |
| Toshiba             | 4         | 4      | 11.76%  |
| SK hynix            | 4         | 4      | 11.76%  |
| Hitachi             | 4         | 4      | 11.76%  |
| Crucial             | 3         | 3      | 8.82%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Samsung Electronics | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| A-DATA Technology   | 2         | 2      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| VISIPRO             | 1         | 2      | 2.94%   |
| R580                | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| Kingston            | 1         | 1      | 2.94%   |
| BAITITON            | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 35.71%  |
| Hitachi | 4         | 4      | 28.57%  |
| Toshiba | 3         | 3      | 21.43%  |
| HGST    | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 42.42%  |
| SSD  | 12        | 14     | 36.36%  |
| NVMe | 7         | 7      | 21.21%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 299       | 403    | 54.46%  |
| Detected | 217       | 341    | 39.53%  |
| Malfunc  | 33        | 35     | 6.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 295       | 44.97%  |
| Samsung Electronics            | 80        | 12.2%   |
| AMD                            | 64        | 9.76%   |
| SanDisk                        | 55        | 8.38%   |
| SK hynix                       | 34        | 5.18%   |
| Toshiba America Info Systems   | 19        | 2.9%    |
| Micron Technology              | 19        | 2.9%    |
| Kingston Technology Company    | 18        | 2.74%   |
| Phison Electronics             | 13        | 1.98%   |
| KIOXIA                         | 12        | 1.83%   |
| Micron/Crucial Technology      | 11        | 1.68%   |
| Solid State Storage Technology | 7         | 1.07%   |
| Union Memory (Shenzhen)        | 5         | 0.76%   |
| Silicon Motion                 | 5         | 0.76%   |
| Realtek Semiconductor          | 5         | 0.76%   |
| Apple                          | 3         | 0.46%   |
| Nvidia                         | 2         | 0.3%    |
| ADATA Technology               | 2         | 0.3%    |
| Zhaoxin                        | 1         | 0.15%   |
| Yangtze Memory Technologies    | 1         | 0.15%   |
| Shenzhen Longsys Electronics   | 1         | 0.15%   |
| Seagate Technology             | 1         | 0.15%   |
| Netac Technology               | 1         | 0.15%   |
| Marvell Technology Group       | 1         | 0.15%   |
| Unknown                        | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 60        | 8.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 42        | 5.98%   |
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 5.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 38        | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 36        | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 3.42%   |
| Samsung NVMe SSD Controller 980                                                | 21        | 2.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 21        | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 2.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 2.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 18        | 2.56%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 2.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 14        | 1.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 1.99%   |
| Micron NVMe Storage Controller                                                 | 12        | 1.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 1.57%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 10        | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 1.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.28%   |
| SanDisk Non-Volatile memory controller                                         | 9         | 1.28%   |
| Intel SSD 660P Series                                                          | 8         | 1.14%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 7         | 1%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 1%      |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6         | 0.85%   |
| Intel Non-Volatile memory controller                                           | 6         | 0.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 0.85%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 5         | 0.71%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 5         | 0.71%   |
| Realtek NVMe Controller                                                        | 5         | 0.71%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 5         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.71%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.71%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 4         | 0.57%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 0.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 4         | 0.57%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 4         | 0.57%   |
| SanDisk PC SN530 NVMe SSD                                                      | 4         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 306       | 45.95%  |
| NVMe | 286       | 42.94%  |
| RAID | 63        | 9.46%   |
| IDE  | 11        | 1.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 378       | 75.45%  |
| AMD          | 122       | 24.35%  |
| CentaurHauls | 1         | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 17        | 3.39%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 17        | 3.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 15        | 2.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 14        | 2.79%   |
| Intel 12th Gen Core i7-12700H            | 13        | 2.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 12        | 2.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics   | 11        | 2.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 9         | 1.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics   | 9         | 1.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 8         | 1.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz        | 8         | 1.6%    |
| Intel Celeron N4020 CPU @ 1.10GHz        | 8         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 7         | 1.4%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 7         | 1.4%    |
| AMD Ryzen 5 4600H with Radeon Graphics   | 7         | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 6         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz       | 6         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz        | 5         | 1%      |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 5         | 1%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 5         | 1%      |
| Intel 12th Gen Core i7-1260P             | 5         | 1%      |
| Intel 12th Gen Core i7-1255U             | 5         | 1%      |
| AMD Ryzen 9 5900HX with Radeon Graphics  | 5         | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz       | 4         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz        | 4         | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 0.8%    |
| Intel Core i5-10300H CPU @ 2.50GHz       | 4         | 0.8%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 4         | 0.8%    |
| Intel 11th Gen Core i5-11300H @ 3.10GHz  | 4         | 0.8%    |
| AMD Ryzen 7 5825U with Radeon Graphics   | 4         | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics   | 4         | 0.8%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 3         | 0.6%    |
| Intel Core i9-9980HK CPU @ 2.40GHz       | 3         | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 3         | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz        | 3         | 0.6%    |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 3         | 0.6%    |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 3         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 114       | 22.75%  |
| Other                   | 100       | 19.96%  |
| Intel Core i5           | 100       | 19.96%  |
| AMD Ryzen 7             | 44        | 8.78%   |
| AMD Ryzen 5             | 34        | 6.79%   |
| Intel Celeron           | 22        | 4.39%   |
| Intel Core i3           | 15        | 2.99%   |
| AMD Ryzen 9             | 8         | 1.6%    |
| Intel Core 2 Duo        | 7         | 1.4%    |
| AMD Ryzen 7 PRO         | 7         | 1.4%    |
| Intel Pentium           | 6         | 1.2%    |
| AMD Ryzen 3             | 6         | 1.2%    |
| Intel Pentium Silver    | 5         | 1%      |
| Intel Core i9           | 5         | 1%      |
| AMD A6                  | 4         | 0.8%    |
| AMD Ryzen 5 PRO         | 3         | 0.6%    |
| AMD Athlon              | 3         | 0.6%    |
| AMD A8                  | 3         | 0.6%    |
| Intel Core m3           | 2         | 0.4%    |
| AMD E                   | 2         | 0.4%    |
| AMD A10                 | 2         | 0.4%    |
| Intel Xeon              | 1         | 0.2%    |
| Intel Core M            | 1         | 0.2%    |
| Intel Core 2            | 1         | 0.2%    |
| Intel Celeron Dual-Core | 1         | 0.2%    |
| AMD Sempron             | 1         | 0.2%    |
| AMD PRO A10             | 1         | 0.2%    |
| AMD FX                  | 1         | 0.2%    |
| AMD Athlon II Dual-Core | 1         | 0.2%    |
| AMD A4                  | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 173       | 34.53%  |
| 2      | 161       | 32.14%  |
| 8      | 66        | 13.17%  |
| 6      | 64        | 12.77%  |
| 14     | 17        | 3.39%   |
| 12     | 8         | 1.6%    |
| 10     | 8         | 1.6%    |
| 24     | 2         | 0.4%    |
| 5      | 1         | 0.2%    |
| 1      | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 501       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 434       | 86.45%  |
| 1      | 68        | 13.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 501       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 33.86%  |
| 0x806c1    | 33        | 6.46%   |
| 0x906a3    | 24        | 4.7%    |
| 0x306a9    | 24        | 4.7%    |
| 0x0a50000c | 23        | 4.5%    |
| 0x806ea    | 19        | 3.72%   |
| 0x906ea    | 15        | 2.94%   |
| 0x08608103 | 14        | 2.74%   |
| 0x806ec    | 13        | 2.54%   |
| 0x08600106 | 13        | 2.54%   |
| 0x406e3    | 11        | 2.15%   |
| 0x306c3    | 9         | 1.76%   |
| 0x806e9    | 8         | 1.57%   |
| 0x206a7    | 8         | 1.57%   |
| 0xa0652    | 7         | 1.37%   |
| 0x906a4    | 7         | 1.37%   |
| 0x706a8    | 7         | 1.37%   |
| 0x08108109 | 7         | 1.37%   |
| 0x806d1    | 6         | 1.17%   |
| 0x806c2    | 6         | 1.17%   |
| 0x706a1    | 5         | 0.98%   |
| 0x40651    | 5         | 0.98%   |
| 0x08608102 | 5         | 0.98%   |
| 0x906e9    | 4         | 0.78%   |
| 0x706e5    | 4         | 0.78%   |
| 0x506c9    | 4         | 0.78%   |
| 0x40661    | 4         | 0.78%   |
| 0x0a50000d | 4         | 0.78%   |
| 0x906ed    | 3         | 0.59%   |
| 0x506e3    | 3         | 0.59%   |
| 0x306d4    | 3         | 0.59%   |
| 0x20652    | 3         | 0.59%   |
| 0x0a404102 | 3         | 0.59%   |
| 0x0a404101 | 3         | 0.59%   |
| 0x08600103 | 3         | 0.59%   |
| 0x08108102 | 3         | 0.59%   |
| 0x06006705 | 3         | 0.59%   |
| 0x03000027 | 3         | 0.59%   |
| 0x1067a    | 2         | 0.39%   |
| 0x0810100b | 2         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 97        | 19.32%  |
| TigerLake        | 53        | 10.56%  |
| IvyBridge        | 43        | 8.57%   |
| Unknown          | 42        | 8.37%   |
| Zen 3            | 37        | 7.37%   |
| Haswell          | 32        | 6.37%   |
| Alderlake Hybrid | 31        | 6.18%   |
| Skylake          | 22        | 4.38%   |
| Zen 2            | 20        | 3.98%   |
| Goldmont plus    | 18        | 3.59%   |
| SandyBridge      | 16        | 3.19%   |
| Zen+             | 15        | 2.99%   |
| Icelake          | 12        | 2.39%   |
| CometLake        | 11        | 2.19%   |
| Broadwell        | 8         | 1.59%   |
| Westmere         | 6         | 1.2%    |
| Silvermont       | 5         | 1%      |
| Penryn           | 5         | 1%      |
| Goldmont         | 5         | 1%      |
| Excavator        | 5         | 1%      |
| Core             | 4         | 0.8%    |
| K10 Llano        | 3         | 0.6%    |
| Zen              | 2         | 0.4%    |
| Puma             | 2         | 0.4%    |
| Piledriver       | 2         | 0.4%    |
| Bobcat           | 2         | 0.4%    |
| Steamroller      | 1         | 0.2%    |
| Nehalem          | 1         | 0.2%    |
| K8 & K10 hybrid  | 1         | 0.2%    |
| K10              | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 356       | 52.74%  |
| Nvidia  | 171       | 25.33%  |
| AMD     | 147       | 21.78%  |
| Zhaoxin | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 45        | 6.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 41        | 5.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 29        | 4.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 24        | 3.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 23        | 3.35%   |
| AMD Lucienne                                                                          | 22        | 3.2%    |
| Intel UHD Graphics 620                                                                | 20        | 2.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 20        | 2.91%   |
| AMD Renoir                                                                            | 20        | 2.91%   |
| Intel HD Graphics 620                                                                 | 17        | 2.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 16        | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 15        | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 15        | 2.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 13        | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 13        | 1.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 11        | 1.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 10        | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 1.31%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 9         | 1.31%   |
| AMD Rembrandt [Radeon 680M]                                                           | 9         | 1.31%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 8         | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 8         | 1.16%   |
| Intel HD Graphics 630                                                                 | 8         | 1.16%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 8         | 1.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 1.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 7         | 1.02%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 7         | 1.02%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 7         | 1.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 1.02%   |
| Intel HD Graphics 5500                                                                | 6         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 5         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 5         | 0.73%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 5         | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 0.73%   |
| Intel HD Graphics 500                                                                 | 5         | 0.73%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 5         | 0.73%   |
| AMD Barcelo                                                                           | 5         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 4         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 0.58%   |
| Intel HD Graphics 530                                                                 | 4         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 208       | 41.43%  |
| Intel + Nvidia | 121       | 24.1%   |
| 1 x AMD        | 86        | 17.13%  |
| AMD + Nvidia   | 28        | 5.58%   |
| Intel + AMD    | 25        | 4.98%   |
| 1 x Nvidia     | 22        | 4.38%   |
| 2 x AMD        | 8         | 1.59%   |
| Other          | 2         | 0.4%    |
| 2 x Nvidia     | 1         | 0.2%    |
| 1 x Zhaoxin    | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 375       | 74.4%   |
| Proprietary | 121       | 24.01%  |
| Unknown     | 8         | 1.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 361       | 71.2%   |
| 0.01-0.5   | 57        | 11.24%  |
| 1.01-2.0   | 37        | 7.3%    |
| 3.01-4.0   | 18        | 3.55%   |
| 0.51-1.0   | 17        | 3.35%   |
| 5.01-6.0   | 8         | 1.58%   |
| 7.01-8.0   | 7         | 1.38%   |
| 8.01-16.0  | 2         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 104       | 17.22%  |
| Chimei Innolux          | 97        | 16.06%  |
| AU Optronics            | 94        | 15.56%  |
| LG Display              | 76        | 12.58%  |
| Samsung Electronics     | 56        | 9.27%   |
| Sharp                   | 21        | 3.48%   |
| Goldstar                | 20        | 3.31%   |
| Dell                    | 17        | 2.81%   |
| Hewlett-Packard         | 14        | 2.32%   |
| Apple                   | 11        | 1.82%   |
| Lenovo                  | 9         | 1.49%   |
| CSO                     | 9         | 1.49%   |
| Philips                 | 7         | 1.16%   |
| InfoVision              | 7         | 1.16%   |
| Chi Mei Optoelectronics | 7         | 1.16%   |
| BenQ                    | 7         | 1.16%   |
| Acer                    | 7         | 1.16%   |
| ASUSTek Computer        | 5         | 0.83%   |
| PANDA                   | 3         | 0.5%    |
| Ancor Communications    | 3         | 0.5%    |
| SLD                     | 2         | 0.33%   |
| Sceptre Tech            | 2         | 0.33%   |
| IBM                     | 2         | 0.33%   |
| HKC                     | 2         | 0.33%   |
| Vizio                   | 1         | 0.17%   |
| ViewSonic               | 1         | 0.17%   |
| TMX                     | 1         | 0.17%   |
| Sony                    | 1         | 0.17%   |
| Panasonic               | 1         | 0.17%   |
| NEC Computers           | 1         | 0.17%   |
| MSI                     | 1         | 0.17%   |
| Medion                  | 1         | 0.17%   |
| LG Philips              | 1         | 0.17%   |
| Insignia                | 1         | 0.17%   |
| Iiyama                  | 1         | 0.17%   |
| HUAWEI                  | 1         | 0.17%   |
| Grundig                 | 1         | 0.17%   |
| Gigabyte Technology     | 1         | 0.17%   |
| Gateway                 | 1         | 0.17%   |
| Fujitsu Siemens         | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.81%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.65%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 4         | 0.65%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.49%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.49%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.49%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 3         | 0.49%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.49%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                 | 3         | 0.49%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.49%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.49%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch        | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch        | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.49%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 2         | 0.33%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 527x296mm 23.8-inch   | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.33%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 2         | 0.33%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 291       | 52.43%  |
| 1366x768 (WXGA)    | 106       | 19.1%   |
| 2560x1440 (QHD)    | 28        | 5.05%   |
| 3840x2160 (4K)     | 24        | 4.32%   |
| 1920x1200 (WUXGA)  | 22        | 3.96%   |
| 1600x900 (HD+)     | 19        | 3.42%   |
| 2560x1600          | 13        | 2.34%   |
| 2880x1800          | 11        | 1.98%   |
| 1680x1050 (WSXGA+) | 7         | 1.26%   |
| 2560x1080          | 5         | 0.9%    |
| 3440x1440          | 4         | 0.72%   |
| 2256x1504          | 3         | 0.54%   |
| 2160x1440          | 3         | 0.54%   |
| 1280x800 (WXGA)    | 3         | 0.54%   |
| 3840x2400          | 2         | 0.36%   |
| 2520x1680          | 2         | 0.36%   |
| 2240x1400          | 2         | 0.36%   |
| 1440x900 (WXGA+)   | 2         | 0.36%   |
| 1280x1024 (SXGA)   | 2         | 0.36%   |
| 1024x768 (XGA)     | 2         | 0.36%   |
| 3840x1080          | 1         | 0.18%   |
| 3072x1920          | 1         | 0.18%   |
| 2160x1350          | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 238       | 39.27%  |
| 14      | 83        | 13.7%   |
| 13      | 68        | 11.22%  |
| 17      | 47        | 7.76%   |
| 24      | 27        | 4.46%   |
| 16      | 26        | 4.29%   |
| 27      | 25        | 4.13%   |
| 23      | 17        | 2.81%   |
| 21      | 14        | 2.31%   |
| 34      | 9         | 1.49%   |
| 12      | 9         | 1.49%   |
| 11      | 8         | 1.32%   |
| 31      | 7         | 1.16%   |
| 22      | 5         | 0.83%   |
| 54      | 3         | 0.5%    |
| 72      | 2         | 0.33%   |
| 49      | 2         | 0.33%   |
| 25      | 2         | 0.33%   |
| 84      | 1         | 0.17%   |
| 78      | 1         | 0.17%   |
| 65      | 1         | 0.17%   |
| 63      | 1         | 0.17%   |
| 60      | 1         | 0.17%   |
| 47      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |
| 19      | 1         | 0.17%   |
| 18      | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 363       | 60.6%   |
| 501-600     | 64        | 10.68%  |
| 351-400     | 62        | 10.35%  |
| 201-300     | 54        | 9.02%   |
| 401-500     | 22        | 3.67%   |
| 601-700     | 10        | 1.67%   |
| 701-800     | 9         | 1.5%    |
| 1001-1500   | 9         | 1.5%    |
| 1501-2000   | 4         | 0.67%   |
| 901-1000    | 1         | 0.17%   |
| Unknown     | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 427       | 82.59%  |
| 16/10   | 66        | 12.77%  |
| 21/9    | 10        | 1.93%   |
| 3/2     | 8         | 1.55%   |
| 5/4     | 2         | 0.39%   |
| 4/3     | 2         | 0.39%   |
| 32/9    | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 246       | 41.07%  |
| 81-90          | 124       | 20.7%   |
| 201-250        | 51        | 8.51%   |
| 121-130        | 44        | 7.35%   |
| 71-80          | 28        | 4.67%   |
| 301-350        | 26        | 4.34%   |
| 111-120        | 17        | 2.84%   |
| 351-500        | 15        | 2.5%    |
| More than 1000 | 11        | 1.84%   |
| 61-70          | 8         | 1.34%   |
| 51-60          | 8         | 1.34%   |
| 251-300        | 7         | 1.17%   |
| 151-200        | 5         | 0.83%   |
| 501-1000       | 3         | 0.5%    |
| 141-150        | 2         | 0.33%   |
| 131-140        | 2         | 0.33%   |
| 91-100         | 1         | 0.17%   |
| Unknown        | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 283       | 48.13%  |
| 101-120       | 125       | 21.26%  |
| 51-100        | 80        | 13.61%  |
| 161-240       | 71        | 12.07%  |
| More than 240 | 19        | 3.23%   |
| 1-50          | 9         | 1.53%   |
| Unknown       | 1         | 0.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 382       | 75.35%  |
| 2     | 92        | 18.15%  |
| 3     | 20        | 3.94%   |
| 0     | 9         | 1.78%   |
| 4     | 4         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 282       | 36.06%  |
| Realtek Semiconductor             | 281       | 35.93%  |
| Qualcomm Atheros                  | 79        | 10.1%   |
| MediaTek                          | 39        | 4.99%   |
| Broadcom                          | 32        | 4.09%   |
| ASIX Electronics                  | 7         | 0.9%    |
| Sierra Wireless                   | 5         | 0.64%   |
| Samsung Electronics               | 5         | 0.64%   |
| TP-Link                           | 4         | 0.51%   |
| Ralink Technology                 | 4         | 0.51%   |
| Qualcomm                          | 4         | 0.51%   |
| Lenovo                            | 4         | 0.51%   |
| Broadcom Limited                  | 4         | 0.51%   |
| Marvell Technology Group          | 3         | 0.38%   |
| Xiaomi                            | 2         | 0.26%   |
| Ralink                            | 2         | 0.26%   |
| Nvidia                            | 2         | 0.26%   |
| Huawei Technologies               | 2         | 0.26%   |
| Hewlett-Packard                   | 2         | 0.26%   |
| Google                            | 2         | 0.26%   |
| Ericsson Business Mobile Networks | 2         | 0.26%   |
| DisplayLink                       | 2         | 0.26%   |
| Dell                              | 2         | 0.26%   |
| Apple                             | 2         | 0.26%   |
| Shenzhen Goodix Technology        | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.13%   |
| NIIMBOT                           | 1         | 0.13%   |
| Motorola PCS                      | 1         | 0.13%   |
| JMicron Technology                | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| D-Link System                     | 1         | 0.13%   |
| Belkin Components                 | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 160       | 17.04%  |
| Intel Wi-Fi 6 AX201                                               | 39        | 4.15%   |
| Intel Wi-Fi 6 AX200                                               | 36        | 3.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 31        | 3.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 29        | 3.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 28        | 2.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 2.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 1.81%   |
| Intel Wireless 8265 / 8275                                        | 17        | 1.81%   |
| Intel Wireless 7260                                               | 17        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 1.7%    |
| Intel Wireless 7265                                               | 13        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 1.28%   |
| Intel Wireless 8260                                               | 11        | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                      | 8         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.75%   |
| Intel Wireless 3165                                               | 7         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.64%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.64%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.64%   |
| Intel Centrino Advanced-N 6235                                    | 6         | 0.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 5         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 271       | 51.72%  |
| Realtek Semiconductor | 100       | 19.08%  |
| Qualcomm Atheros      | 63        | 12.02%  |
| MediaTek              | 39        | 7.44%   |
| Broadcom              | 25        | 4.77%   |
| Sierra Wireless       | 5         | 0.95%   |
| Ralink Technology     | 4         | 0.76%   |
| Qualcomm              | 4         | 0.76%   |
| Broadcom Limited      | 3         | 0.57%   |
| TP-Link               | 2         | 0.38%   |
| Ralink                | 2         | 0.38%   |
| Dell                  | 2         | 0.38%   |
| Fibocom               | 1         | 0.19%   |
| D-Link System         | 1         | 0.19%   |
| Belkin Components     | 1         | 0.19%   |
| ASUSTek Computer      | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 39        | 7.36%   |
| Intel Wi-Fi 6 AX200                                            | 36        | 6.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 31        | 5.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 28        | 5.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 4.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 22        | 4.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 3.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 3.21%   |
| Intel Wireless 8265 / 8275                                     | 17        | 3.21%   |
| Intel Wireless 7260                                            | 17        | 3.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 3.02%   |
| Intel Wireless 7265                                            | 13        | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 2.26%   |
| Intel Wireless 8260                                            | 11        | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 1.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.51%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 1.51%   |
| Intel Wireless 3165                                            | 7         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.13%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 1.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5         | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.75%   |
| Intel Wireless 3160                                            | 4         | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 0.75%   |
| Realtek 802.11ac NIC                                           | 3         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 230       | 59.59%  |
| Intel                    | 95        | 24.61%  |
| Qualcomm Atheros         | 18        | 4.66%   |
| Broadcom                 | 10        | 2.59%   |
| ASIX Electronics         | 7         | 1.81%   |
| Lenovo                   | 4         | 1.04%   |
| Samsung Electronics      | 3         | 0.78%   |
| Marvell Technology Group | 3         | 0.78%   |
| Xiaomi                   | 2         | 0.52%   |
| TP-Link                  | 2         | 0.52%   |
| Nvidia                   | 2         | 0.52%   |
| Huawei Technologies      | 2         | 0.52%   |
| Google                   | 2         | 0.52%   |
| DisplayLink              | 2         | 0.52%   |
| Apple                    | 2         | 0.52%   |
| JMicron Technology       | 1         | 0.26%   |
| Broadcom Limited         | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 160       | 40.1%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 29        | 7.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 6.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 5.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 2.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 2.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.5%    |
| Intel Ethernet Connection (13) I219-V                             | 6         | 1.5%    |
| Intel Ethernet Connection (10) I219-V                             | 6         | 1.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.75%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.75%   |
| Intel Ethernet Connection (16) I219-LM                            | 3         | 0.75%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.5%    |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.5%    |
| DisplayLink USB 3.0 Docking Station                               | 2         | 0.5%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 500       | 57.08%  |
| Ethernet | 366       | 41.78%  |
| Modem    | 7         | 0.8%    |
| Unknown  | 3         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 432       | 81.2%   |
| Ethernet | 100       | 18.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 332       | 66.27%  |
| 1     | 153       | 30.54%  |
| 0     | 13        | 2.59%   |
| 3     | 3         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 366       | 72.91%  |
| Yes  | 136       | 27.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 230       | 51.69%  |
| Realtek Semiconductor           | 59        | 13.26%  |
| Qualcomm Atheros Communications | 34        | 7.64%   |
| IMC Networks                    | 23        | 5.17%   |
| Foxconn / Hon Hai               | 23        | 5.17%   |
| Broadcom                        | 21        | 4.72%   |
| Lite-On Technology              | 18        | 4.04%   |
| Apple                           | 7         | 1.57%   |
| Realtek                         | 5         | 1.12%   |
| Dell                            | 5         | 1.12%   |
| Toshiba                         | 4         | 0.9%    |
| TP-Link                         | 2         | 0.45%   |
| Hewlett-Packard                 | 2         | 0.45%   |
| Cambridge Silicon Radio         | 2         | 0.45%   |
| ASUSTek Computer                | 2         | 0.45%   |
| USI                             | 1         | 0.22%   |
| SINO WEALTH                     | 1         | 0.22%   |
| Ralink                          | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Foxconn International           | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |
| Chicony Electronics             | 1         | 0.22%   |
| Alps Electric                   | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 63        | 14.16%  |
| Intel AX201 Bluetooth                               | 63        | 14.16%  |
| Realtek Bluetooth Radio                             | 47        | 10.56%  |
| Intel AX200 Bluetooth                               | 34        | 7.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 6.74%   |
| Intel Bluetooth Device                              | 20        | 4.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 3.6%    |
| Lite-On Wireless_Device                             | 11        | 2.47%   |
| IMC Networks Wireless_Device                        | 11        | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 2.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 2.02%   |
| Intel AX210 Bluetooth                               | 9         | 2.02%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 2.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.35%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.35%   |
| Broadcom HP Portable SoftSailing                    | 6         | 1.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.35%   |
| Apple Bluetooth Host Controller                     | 6         | 1.35%   |
| Realtek Bluetooth Radio                             | 5         | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.67%   |
| IMC Networks Bluetooth Device                       | 3         | 0.67%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 3         | 0.67%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.67%   |
| TP-Link UB500 Adapter                               | 2         | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.45%   |
| USI Bluetooth Device                                | 1         | 0.22%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.22%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.22%   |
| Toshiba Bluetooth Device                            | 1         | 0.22%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.22%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.22%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.22%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 376       | 57.4%   |
| AMD                       | 128       | 19.54%  |
| Nvidia                    | 95        | 14.5%   |
| C-Media Electronics       | 10        | 1.53%   |
| Lenovo                    | 6         | 0.92%   |
| JMTek                     | 5         | 0.76%   |
| Realtek Semiconductor     | 4         | 0.61%   |
| Razer USA                 | 3         | 0.46%   |
| Texas Instruments         | 2         | 0.31%   |
| Logitech                  | 2         | 0.31%   |
| Hewlett-Packard           | 2         | 0.31%   |
| GN Netcom                 | 2         | 0.31%   |
| Corsair                   | 2         | 0.31%   |
| Apple                     | 2         | 0.31%   |
| ZOOM                      | 1         | 0.15%   |
| Zhaoxin                   | 1         | 0.15%   |
| TerraTec Electronic       | 1         | 0.15%   |
| Sony                      | 1         | 0.15%   |
| Silicon Motion            | 1         | 0.15%   |
| Sennheiser Communications | 1         | 0.15%   |
| Scarlett                  | 1         | 0.15%   |
| Princeton Technology      | 1         | 0.15%   |
| Plantronics               | 1         | 0.15%   |
| Fujitsu                   | 1         | 0.15%   |
| Focusrite-Novation        | 1         | 0.15%   |
| DisplayLink               | 1         | 0.15%   |
| Cyber Acoustics           | 1         | 0.15%   |
| Creative Technology       | 1         | 0.15%   |
| Blue Microphones          | 1         | 0.15%   |
| Arturia                   | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 100       | 12.55%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 66        | 8.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 58        | 7.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 53        | 6.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 48        | 6.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 35        | 4.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 3.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19        | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 1.63%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 1.25%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 1.25%   |
| Nvidia Audio device                                                        | 9         | 1.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1%      |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1%      |
| Intel CM238 HD Audio Controller                                            | 8         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 8         | 1%      |
| AMD FCH Azalia Controller                                                  | 8         | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 0.88%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 0.63%   |
| Realtek Semiconductor USB Audio                                            | 4         | 0.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 0.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 0.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 138       | 31.44%  |
| SK hynix            | 83        | 18.91%  |
| Micron Technology   | 59        | 13.44%  |
| Crucial             | 41        | 9.34%   |
| Kingston            | 30        | 6.83%   |
| Unknown (ABCD)      | 13        | 2.96%   |
| Unknown             | 11        | 2.51%   |
| A-DATA Technology   | 10        | 2.28%   |
| Elpida              | 6         | 1.37%   |
| Unknown             | 6         | 1.37%   |
| Ramaxel Technology  | 5         | 1.14%   |
| Wilk                | 3         | 0.68%   |
| Nanya Technology    | 3         | 0.68%   |
| Corsair             | 3         | 0.68%   |
| Transcend           | 2         | 0.46%   |
| Smart               | 2         | 0.46%   |
| Silicon Power       | 2         | 0.46%   |
| GOODRAM             | 2         | 0.46%   |
| Unknown (8A02)      | 1         | 0.23%   |
| Teikon              | 1         | 0.23%   |
| Team                | 1         | 0.23%   |
| Super Talent        | 1         | 0.23%   |
| Shenzhen Zhongteng  | 1         | 0.23%   |
| Shenzhen WODPOSIT   | 1         | 0.23%   |
| SHARETRONIC         | 1         | 0.23%   |
| Qimonda             | 1         | 0.23%   |
| Patriot             | 1         | 0.23%   |
| Imation             | 1         | 0.23%   |
| Goldkey             | 1         | 0.23%   |
| Gold Key            | 1         | 0.23%   |
| G.Skill             | 1         | 0.23%   |
| ff                  | 1         | 0.23%   |
| Essencore Limited   | 1         | 0.23%   |
| Atermiter           | 1         | 0.23%   |
| ASint Technology    | 1         | 0.23%   |
| Apacer              | 1         | 0.23%   |
| AMD                 | 1         | 0.23%   |
| 4ea5                | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 11        | 2.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 8         | 1.76%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.32%   |
| Unknown                                                          | 6         | 1.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.88%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.88%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.66%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 0.66%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.66%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 3         | 0.66%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 3         | 0.66%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 3         | 0.66%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s             | 2         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 221       | 61.56%  |
| DDR3   | 75        | 20.89%  |
| LPDDR4 | 32        | 8.91%   |
| DDR5   | 14        | 3.9%    |
| LPDDR5 | 7         | 1.95%   |
| LPDDR3 | 4         | 1.11%   |
| DDR2   | 4         | 1.11%   |
| SDRAM  | 2         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 313       | 84.59%  |
| Row Of Chips | 48        | 12.97%  |
| Chip         | 4         | 1.08%   |
| Unknown      | 3         | 0.81%   |
| DIMM         | 2         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 185       | 47.31%  |
| 4096  | 87        | 22.25%  |
| 16384 | 82        | 20.97%  |
| 32768 | 18        | 4.6%    |
| 2048  | 15        | 3.84%   |
| 1024  | 4         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 135       | 36%     |
| 2667    | 67        | 17.87%  |
| 1600    | 57        | 15.2%   |
| 2400    | 33        | 8.8%    |
| 4800    | 14        | 3.73%   |
| 4267    | 12        | 3.2%    |
| 1333    | 11        | 2.93%   |
| 6400    | 7         | 1.87%   |
| 2133    | 7         | 1.87%   |
| 1334    | 7         | 1.87%   |
| 1867    | 6         | 1.6%    |
| 4266    | 4         | 1.07%   |
| 667     | 4         | 1.07%   |
| 3266    | 3         | 0.8%    |
| 8400    | 2         | 0.53%   |
| 4199    | 1         | 0.27%   |
| 2933    | 1         | 0.27%   |
| 2666    | 1         | 0.27%   |
| 2048    | 1         | 0.27%   |
| 1067    | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 40%     |
| Hewlett-Packard    | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L3110 Series         | 1         | 20%     |
| Seiko Epson ET-2700 Series       | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| Canon iP2600 series              | 1         | 20%     |
| Brother HL-2230 series           | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 96        | 20.08%  |
| Microdia                               | 52        | 10.88%  |
| IMC Networks                           | 52        | 10.88%  |
| Quanta                                 | 42        | 8.79%   |
| Realtek Semiconductor                  | 36        | 7.53%   |
| Bison Electronics                      | 28        | 5.86%   |
| Acer                                   | 28        | 5.86%   |
| Sunplus Innovation Technology          | 22        | 4.6%    |
| Cheng Uei Precision Industry (Foxlink) | 19        | 3.97%   |
| Luxvisions Innotech Limited            | 13        | 2.72%   |
| Logitech                               | 13        | 2.72%   |
| Syntek                                 | 11        | 2.3%    |
| Lite-On Technology                     | 10        | 2.09%   |
| Silicon Motion                         | 6         | 1.26%   |
| Apple                                  | 5         | 1.05%   |
| Y Media                                | 4         | 0.84%   |
| Samsung Electronics                    | 4         | 0.84%   |
| USB Camera                             | 3         | 0.63%   |
| Suyin                                  | 3         | 0.63%   |
| Alcor Micro                            | 3         | 0.63%   |
| Z-Star Microelectronics                | 2         | 0.42%   |
| SunplusIT                              | 2         | 0.42%   |
| Sonix Technology                       | 2         | 0.42%   |
| Lenovo                                 | 2         | 0.42%   |
| GEMBIRD                                | 2         | 0.42%   |
| YGTek                                  | 1         | 0.21%   |
| Xiaomi                                 | 1         | 0.21%   |
| USB Camera CS                          | 1         | 0.21%   |
| STEREOLABS                             | 1         | 0.21%   |
| SN0002                                 | 1         | 0.21%   |
| ShineTech                              | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| Novatek Microelectronics               | 1         | 0.21%   |
| Importek                               | 1         | 0.21%   |
| Huawei Technologies                    | 1         | 0.21%   |
| HRY                                    | 1         | 0.21%   |
| Goodong Industry                       | 1         | 0.21%   |
| Goodong                                | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| eMPIA Technology                       | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 29        | 6.05%   |
| Chicony Integrated Camera                                       | 29        | 6.05%   |
| IMC Networks Integrated Camera                                  | 21        | 4.38%   |
| Acer Integrated Camera                                          | 14        | 2.92%   |
| Realtek Integrated_Webcam_HD                                    | 13        | 2.71%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 12        | 2.51%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 2.3%    |
| Sunplus Integrated_Webcam_HD                                    | 10        | 2.09%   |
| Chicony HD Webcam                                               | 9         | 1.88%   |
| Chicony HD User Facing                                          | 9         | 1.88%   |
| Bison Integrated Camera                                         | 9         | 1.88%   |
| Syntek Integrated Camera                                        | 7         | 1.46%   |
| Quanta HD User Facing                                           | 7         | 1.46%   |
| IMC Networks HD Camera                                          | 6         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 1.25%   |
| Acer HD Webcam                                                  | 6         | 1.25%   |
| Microdia Integrated_Webcam_FHD                                  | 5         | 1.04%   |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 1.04%   |
| Chicony HP Wide Vision HD Camera                                | 5         | 1.04%   |
| Y Media USB Camera                                              | 4         | 0.84%   |
| Samsung Galaxy A5 (MTP)                                         | 4         | 0.84%   |
| Quanta HP Wide Vision HD Camera                                 | 4         | 0.84%   |
| Quanta HP HD Camera                                             | 4         | 0.84%   |
| Quanta HD Webcam                                                | 4         | 0.84%   |
| Quanta ACER HD User Facing                                      | 4         | 0.84%   |
| Microdia Webcam Vitade AF                                       | 4         | 0.84%   |
| Luxvisions Innotech Limited Integrated Camera                   | 4         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.84%   |
| Chicony USB2.0 Camera                                           | 4         | 0.84%   |
| Chicony HP TrueVision HD Camera                                 | 4         | 0.84%   |
| Chicony HP Truevision HD                                        | 4         | 0.84%   |
| Chicony HP HD Camera                                            | 4         | 0.84%   |
| USB Camera USB Camera                                           | 3         | 0.63%   |
| Sunplus HD WebCam                                               | 3         | 0.63%   |
| Realtek USB Camera                                              | 3         | 0.63%   |
| Quanta HD Camera                                                | 3         | 0.63%   |
| Microdia REDRAGON Live Camera Audio                             | 3         | 0.63%   |
| Microdia Integrated Webcam                                      | 3         | 0.63%   |
| Logitech C922 Pro Stream Webcam                                 | 3         | 0.63%   |
| Lite-On Integrated Camera                                       | 3         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 31        | 30.69%  |
| Synaptics                          | 28        | 27.72%  |
| Validity Sensors                   | 25        | 24.75%  |
| Elan Microelectronics              | 8         | 7.92%   |
| Upek                               | 3         | 2.97%   |
| AuthenTec                          | 2         | 1.98%   |
| STMicroelectronics                 | 1         | 0.99%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.99%   |
| LighTuning Technology              | 1         | 0.99%   |
| Focal-systems.Corp                 | 1         | 0.99%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 24        | 23.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 8         | 7.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 6         | 5.94%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 4.95%   |
| Shenzhen Goodix Fingerprint Reader                              | 5         | 4.95%   |
| Elan ELAN:ARM-M4                                                | 5         | 4.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 4         | 3.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 3.96%   |
| Validity Sensors VFS491                                         | 3         | 2.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 2.97%   |
| Synaptics UWP WBDI Device                                       | 3         | 2.97%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 2.97%   |
| Elan ELAN:Fingerprint                                           | 3         | 2.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 2         | 1.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 1.98%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 2         | 1.98%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 1.98%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 2         | 1.98%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 1.98%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 0.99%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 0.99%   |
| Validity Sensors Fingerprint scanner                            | 1         | 0.99%   |
| Synaptics WBDI                                                  | 1         | 0.99%   |
| Synaptics UWP WBDI                                              | 1         | 0.99%   |
| Synaptics  WBDI                                                 | 1         | 0.99%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 0.99%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 0.99%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 0.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 0.99%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 0.99%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 0.99%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 0.99%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 18        | 40.91%  |
| Alcor Micro           | 17        | 38.64%  |
| Upek                  | 4         | 9.09%   |
| O2 Micro              | 1         | 2.27%   |
| Lenovo                | 1         | 2.27%   |
| Clay Logic            | 1         | 2.27%   |
| BIT4ID                | 1         | 2.27%   |
| Advanced Card Systems | 1         | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 38.64%  |
| Broadcom 58200                                                               | 8         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 9.09%   |
| Broadcom 5880                                                                | 4         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.82%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 6.82%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.27%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.27%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 2.27%   |
| BIT4ID miniLector EVO                                                        | 1         | 2.27%   |
| Advanced Card Systems ACR39U                                                 | 1         | 2.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 315       | 61.52%  |
| 1     | 150       | 29.3%   |
| 2     | 41        | 8.01%   |
| 3     | 4         | 0.78%   |
| 9     | 1         | 0.2%    |
| 4     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 100       | 41.15%  |
| Chipcard                 | 40        | 16.46%  |
| Graphics card            | 30        | 12.35%  |
| Net/wireless             | 18        | 7.41%   |
| Camera                   | 18        | 7.41%   |
| Multimedia controller    | 15        | 6.17%   |
| Bluetooth                | 6         | 2.47%   |
| Sound                    | 5         | 2.06%   |
| Network                  | 3         | 1.23%   |
| Communication controller | 3         | 1.23%   |
| Net/ethernet             | 2         | 0.82%   |
| Storage                  | 1         | 0.41%   |
| Modem                    | 1         | 0.41%   |
| Card reader              | 1         | 0.41%   |

