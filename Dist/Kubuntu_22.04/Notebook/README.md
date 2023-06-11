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

Total: 663

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-52-generic     | 42        | 8%      |
| 5.15.0-56-generic     | 38        | 7.24%   |
| 5.15.0-58-generic     | 27        | 5.14%   |
| 5.15.0-53-generic     | 22        | 4.19%   |
| 5.15.0-48-generic     | 22        | 4.19%   |
| 5.15.0-60-generic     | 21        | 4%      |
| 5.15.0-47-generic     | 21        | 4%      |
| 5.15.0-46-generic     | 17        | 3.24%   |
| 5.15.0-43-generic     | 17        | 3.24%   |
| 5.15.0-41-generic     | 17        | 3.24%   |
| 5.15.0-40-generic     | 15        | 2.86%   |
| 5.15.0-25-generic     | 15        | 2.86%   |
| 5.19.0-35-generic     | 14        | 2.67%   |
| 5.19.0-32-generic     | 13        | 2.48%   |
| 5.15.0-50-generic     | 12        | 2.29%   |
| 5.15.0-27-generic     | 12        | 2.29%   |
| 5.15.0-67-generic     | 11        | 2.1%    |
| 5.19.0-41-generic     | 10        | 1.9%    |
| 5.19.0-38-generic     | 10        | 1.9%    |
| 5.15.0-33-generic     | 10        | 1.9%    |
| 5.15.0-57-generic     | 9         | 1.71%   |
| 5.15.0-71-generic     | 8         | 1.52%   |
| 5.19.0-42-generic     | 7         | 1.33%   |
| 5.15.0-39-generic     | 7         | 1.33%   |
| 5.15.0-69-generic     | 6         | 1.14%   |
| 5.15.0-72-generic     | 5         | 0.95%   |
| 5.15.0-43-lowlatency  | 5         | 0.95%   |
| 5.15.0-37-generic     | 5         | 0.95%   |
| 5.19.0-43-generic     | 4         | 0.76%   |
| 5.15.0-35-generic     | 4         | 0.76%   |
| 5.15.0-30-generic     | 4         | 0.76%   |
| 5.15.0-18-generic     | 4         | 0.76%   |
| 5.19.0-40-generic     | 3         | 0.57%   |
| 5.17.0-1020-oem       | 3         | 0.57%   |
| 5.15.0-70-generic     | 3         | 0.57%   |
| 5.15.0-46-lowlatency  | 3         | 0.57%   |
| 6.2.2-060202-generic  | 2         | 0.38%   |
| 6.1.0-1006-oem        | 2         | 0.38%   |
| 6.0.7-060007-generic  | 2         | 0.38%   |
| 5.19.5-051905-generic | 2         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 388       | 78.23%  |
| 5.19.0  | 62        | 12.5%   |
| 5.17.0  | 8         | 1.61%   |
| 6.0.0   | 4         | 0.81%   |
| 6.1.0   | 3         | 0.6%    |
| 5.13.0  | 3         | 0.6%    |
| 6.2.2   | 2         | 0.4%    |
| 6.0.7   | 2         | 0.4%    |
| 5.19.5  | 2         | 0.4%    |
| 6.3.5   | 1         | 0.2%    |
| 6.3.4   | 1         | 0.2%    |
| 6.3.0   | 1         | 0.2%    |
| 6.2.8   | 1         | 0.2%    |
| 6.1.9   | 1         | 0.2%    |
| 6.1.12  | 1         | 0.2%    |
| 6.0.9   | 1         | 0.2%    |
| 6.0.6   | 1         | 0.2%    |
| 6.0.1   | 1         | 0.2%    |
| 5.19.2  | 1         | 0.2%    |
| 5.19.11 | 1         | 0.2%    |
| 5.18.6  | 1         | 0.2%    |
| 5.18.15 | 1         | 0.2%    |
| 5.18.10 | 1         | 0.2%    |
| 5.17.5  | 1         | 0.2%    |
| 5.17.4  | 1         | 0.2%    |
| 5.17.2  | 1         | 0.2%    |
| 5.16.2  | 1         | 0.2%    |
| 5.16.11 | 1         | 0.2%    |
| 5.15.65 | 1         | 0.2%    |
| 5.15.34 | 1         | 0.2%    |
| 5.14.0  | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 389       | 78.74%  |
| 5.19    | 66        | 13.36%  |
| 5.17    | 11        | 2.23%   |
| 6.0     | 8         | 1.62%   |
| 6.1     | 5         | 1.01%   |
| 6.3     | 3         | 0.61%   |
| 6.2     | 3         | 0.61%   |
| 5.18    | 3         | 0.61%   |
| 5.13    | 3         | 0.61%   |
| 5.16    | 2         | 0.4%    |
| 5.14    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 481       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 471       | 97.52%  |
| GNOME      | 4         | 0.83%   |
| KDE        | 3         | 0.62%   |
| XFCE       | 1         | 0.21%   |
| X-Cinnamon | 1         | 0.21%   |
| MATE       | 1         | 0.21%   |
| i3         | 1         | 0.21%   |
| GNUstep    | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 458       | 94.43%  |
| Wayland | 21        | 4.33%   |
| Tty     | 6         | 1.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 365       | 75.41%  |
| Unknown | 85        | 17.56%  |
| GDM3    | 21        | 4.34%   |
| LightDM | 11        | 2.27%   |
| SLiM    | 1         | 0.21%   |
| LXDM    | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 246       | 50.93%  |
| de_DE   | 35        | 7.25%   |
| ru_RU   | 26        | 5.38%   |
| it_IT   | 26        | 5.38%   |
| fr_FR   | 18        | 3.73%   |
| en_GB   | 18        | 3.73%   |
| en_IN   | 13        | 2.69%   |
| pl_PL   | 12        | 2.48%   |
| es_ES   | 11        | 2.28%   |
| pt_BR   | 9         | 1.86%   |
| en_CA   | 7         | 1.45%   |
| en_AU   | 7         | 1.45%   |
| tr_TR   | 5         | 1.04%   |
| hu_HU   | 5         | 1.04%   |
| en_NZ   | 4         | 0.83%   |
| zh_CN   | 3         | 0.62%   |
| en_SG   | 3         | 0.62%   |
| en_PH   | 3         | 0.62%   |
| cs_CZ   | 3         | 0.62%   |
| nl_BE   | 2         | 0.41%   |
| fr_CH   | 2         | 0.41%   |
| es_MX   | 2         | 0.41%   |
| es_CL   | 2         | 0.41%   |
| Default | 2         | 0.41%   |
| zh_TW   | 1         | 0.21%   |
| sv_SE   | 1         | 0.21%   |
| sl_SI   | 1         | 0.21%   |
| pt_PT   | 1         | 0.21%   |
| lt_LT   | 1         | 0.21%   |
| ko_KR   | 1         | 0.21%   |
| fr_BE   | 1         | 0.21%   |
| fi_FI   | 1         | 0.21%   |
| et_EE   | 1         | 0.21%   |
| es_VE   | 1         | 0.21%   |
| es_EC   | 1         | 0.21%   |
| es_CR   | 1         | 0.21%   |
| es_AR   | 1         | 0.21%   |
| en_ZA   | 1         | 0.21%   |
| en_DE   | 1         | 0.21%   |
| el_GR   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 299       | 61.4%   |
| BIOS | 188       | 38.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 435       | 89.88%  |
| Btrfs   | 23        | 4.75%   |
| Overlay | 17        | 3.51%   |
| Tmpfs   | 5         | 1.03%   |
| Xfs     | 3         | 0.62%   |
| Ext2    | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 339       | 69.9%   |
| Unknown | 121       | 24.95%  |
| MBR     | 25        | 5.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 448       | 93.14%  |
| Yes       | 33        | 6.86%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 293       | 60.79%  |
| Yes       | 189       | 39.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 120       | 24.95%  |
| Hewlett-Packard                | 81        | 16.84%  |
| Dell                           | 78        | 16.22%  |
| ASUSTek Computer               | 40        | 8.32%   |
| Acer                           | 38        | 7.9%    |
| MSI                            | 18        | 3.74%   |
| HUAWEI                         | 12        | 2.49%   |
| Apple                          | 9         | 1.87%   |
| Samsung Electronics            | 8         | 1.66%   |
| Toshiba                        | 6         | 1.25%   |
| Google                         | 6         | 1.25%   |
| Notebook                       | 5         | 1.04%   |
| TUXEDO                         | 4         | 0.83%   |
| Timi                           | 4         | 0.83%   |
| Gigabyte Technology            | 4         | 0.83%   |
| Framework                      | 3         | 0.62%   |
| Alienware                      | 3         | 0.62%   |
| System76                       | 2         | 0.42%   |
| Sony                           | 2         | 0.42%   |
| Razer                          | 2         | 0.42%   |
| Panasonic                      | 2         | 0.42%   |
| HONOR                          | 2         | 0.42%   |
| Haier                          | 2         | 0.42%   |
| GPU Company                    | 2         | 0.42%   |
| Fujitsu                        | 2         | 0.42%   |
| Carbon Systems                 | 2         | 0.42%   |
| Unknown                        | 2         | 0.42%   |
| VALE                           | 1         | 0.21%   |
| TrekStor                       | 1         | 0.21%   |
| Thomson                        | 1         | 0.21%   |
| TerraQue                       | 1         | 0.21%   |
| Tactus                         | 1         | 0.21%   |
| Standard                       | 1         | 0.21%   |
| SLIMBOOK                       | 1         | 0.21%   |
| SK hynix                       | 1         | 0.21%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.21%   |
| SGIN                           | 1         | 0.21%   |
| Schenker                       | 1         | 0.21%   |
| PC Specialist                  | 1         | 0.21%   |
| Monster                        | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 1.25%   |
| HUAWEI HVY-WXX9                          | 5         | 1.04%   |
| HP 255 G8 Notebook PC                    | 4         | 0.83%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 3         | 0.62%   |
| HP ProBook 6470b                         | 3         | 0.62%   |
| HP Pavilion g6                           | 3         | 0.62%   |
| HP OMEN Laptop 15-en0xxx                 | 3         | 0.62%   |
| HP Laptop 15-ef2xxx                      | 3         | 0.62%   |
| HP EliteBook 845 G7 Notebook PC          | 3         | 0.62%   |
| Framework Laptop (12th Gen Intel Core)   | 3         | 0.62%   |
| Dell XPS 15 9560                         | 3         | 0.62%   |
| Dell Latitude 5420                       | 3         | 0.62%   |
| Dell Latitude 3420                       | 3         | 0.62%   |
| Timi TM1701                              | 2         | 0.42%   |
| Lenovo ThinkBook 15 G2 ITL 20VE          | 2         | 0.42%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 2         | 0.42%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7         | 2         | 0.42%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 2         | 0.42%   |
| HUAWEI CREM-WXX9                         | 2         | 0.42%   |
| HP ZBook 15 G6                           | 2         | 0.42%   |
| HP ProBook 6570b                         | 2         | 0.42%   |
| HP ProBook 440 G8 Notebook PC            | 2         | 0.42%   |
| HP Pavilion Laptop 15-eh1xxx             | 2         | 0.42%   |
| HP Pavilion Gaming Laptop 15-ec0xxx      | 2         | 0.42%   |
| HP Pavilion dv6                          | 2         | 0.42%   |
| HP Laptop 17-by3xxx                      | 2         | 0.42%   |
| HP Laptop 15-da0xxx                      | 2         | 0.42%   |
| HP EliteBook 8470p                       | 2         | 0.42%   |
| Haier A1420EM                            | 2         | 0.42%   |
| Dell XPS 15 9520                         | 2         | 0.42%   |
| Dell Precision 7540                      | 2         | 0.42%   |
| Carbon Systems Iridium 14                | 2         | 0.42%   |
| ASUS VivoBook_ASUSLaptop X3400PA_K3400PA | 2         | 0.42%   |
| Acer Swift SFX14-41G                     | 2         | 0.42%   |
| Acer Nitro AN517-51                      | 2         | 0.42%   |
| Acer Aspire E5-575G                      | 2         | 0.42%   |
| Acer Aspire A515-45                      | 2         | 0.42%   |
| VALE Notebook Slim S132                  | 1         | 0.21%   |
| TUXEDO Stellaris AMD Gen3 (CZN)          | 1         | 0.21%   |
| TUXEDO Polaris 15 AMD Gen1               | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 59        | 12.27%  |
| Lenovo IdeaPad      | 30        | 6.24%   |
| Dell Latitude       | 25        | 5.2%    |
| Acer Aspire         | 21        | 4.37%   |
| Dell Inspiron       | 18        | 3.74%   |
| HP ProBook          | 15        | 3.12%   |
| HP Pavilion         | 14        | 2.91%   |
| HP Laptop           | 14        | 2.91%   |
| Dell XPS            | 13        | 2.7%    |
| HP EliteBook        | 12        | 2.49%   |
| Dell Precision      | 9         | 1.87%   |
| ASUS VivoBook       | 9         | 1.87%   |
| Lenovo ThinkBook    | 8         | 1.66%   |
| Lenovo Legion       | 8         | 1.66%   |
| Acer Nitro          | 8         | 1.66%   |
| Dell Vostro         | 6         | 1.25%   |
| Unknown             | 6         | 1.25%   |
| Toshiba Satellite   | 5         | 1.04%   |
| HUAWEI HVY-WXX9     | 5         | 1.04%   |
| HP OMEN             | 5         | 1.04%   |
| HP ZBook            | 4         | 0.83%   |
| HP 255              | 4         | 0.83%   |
| ASUS ROG            | 4         | 0.83%   |
| Acer Swift          | 4         | 0.83%   |
| Lenovo Yoga         | 3         | 0.62%   |
| Framework Laptop    | 3         | 0.62%   |
| Dell G15            | 3         | 0.62%   |
| ASUS ASUS           | 3         | 0.62%   |
| Apple MacBookPro11  | 3         | 0.62%   |
| Acer Predator       | 3         | 0.62%   |
| TUXEDO InfinityBook | 2         | 0.42%   |
| Timi TM1701         | 2         | 0.42%   |
| Razer Blade         | 2         | 0.42%   |
| Notebook PD5x       | 2         | 0.42%   |
| MSI Raider          | 2         | 0.42%   |
| MSI Prestige        | 2         | 0.42%   |
| MSI Modern          | 2         | 0.42%   |
| Lenovo ZHAOYANG     | 2         | 0.42%   |
| HUAWEI CREM-WXX9    | 2         | 0.42%   |
| HP ENVY             | 2         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 103       | 21.41%  |
| 2020 | 72        | 14.97%  |
| 2022 | 56        | 11.64%  |
| 2019 | 45        | 9.36%   |
| 2012 | 38        | 7.9%    |
| 2018 | 25        | 5.2%    |
| 2016 | 23        | 4.78%   |
| 2013 | 21        | 4.37%   |
| 2017 | 20        | 4.16%   |
| 2014 | 20        | 4.16%   |
| 2011 | 20        | 4.16%   |
| 2015 | 15        | 3.12%   |
| 2010 | 8         | 1.66%   |
| 2008 | 5         | 1.04%   |
| 2023 | 4         | 0.83%   |
| 2007 | 4         | 0.83%   |
| 2009 | 2         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 481       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 413       | 85.15%  |
| Enabled  | 72        | 14.85%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 474       | 98.54%  |
| Yes  | 7         | 1.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 27.84%  |
| 16.01-24.0  | 125       | 25.77%  |
| 8.01-16.0   | 95        | 19.59%  |
| 32.01-64.0  | 52        | 10.72%  |
| 3.01-4.0    | 44        | 9.07%   |
| 64.01-256.0 | 17        | 3.51%   |
| 24.01-32.0  | 12        | 2.47%   |
| 2.01-3.0    | 3         | 0.62%   |
| 1.01-2.0    | 2         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 131       | 25.69%  |
| 4.01-8.0   | 121       | 23.73%  |
| 3.01-4.0   | 116       | 22.75%  |
| 1.01-2.0   | 104       | 20.39%  |
| 8.01-16.0  | 32        | 6.27%   |
| 16.01-24.0 | 3         | 0.59%   |
| 0.51-1.0   | 3         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 325       | 66.87%  |
| 2      | 135       | 27.78%  |
| 3      | 19        | 3.91%   |
| 4      | 6         | 1.23%   |
| 0      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 386       | 80.08%  |
| Yes       | 96        | 19.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 354       | 73.6%   |
| No        | 127       | 26.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 480       | 99.79%  |
| No        | 1         | 0.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 420       | 86.6%   |
| No        | 65        | 13.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 92        | 19.05%  |
| Germany     | 45        | 9.32%   |
| Italy       | 39        | 8.07%   |
| Russia      | 35        | 7.25%   |
| France      | 30        | 6.21%   |
| Poland      | 18        | 3.73%   |
| UK          | 14        | 2.9%    |
| Spain       | 14        | 2.9%    |
| Brazil      | 14        | 2.9%    |
| India       | 13        | 2.69%   |
| Hungary     | 10        | 2.07%   |
| Canada      | 9         | 1.86%   |
| Indonesia   | 8         | 1.66%   |
| Turkey      | 6         | 1.24%   |
| Switzerland | 6         | 1.24%   |
| Sweden      | 6         | 1.24%   |
| Czechia     | 6         | 1.24%   |
| Australia   | 6         | 1.24%   |
| Mexico      | 5         | 1.04%   |
| Belgium     | 5         | 1.04%   |
| Slovenia    | 4         | 0.83%   |
| Portugal    | 4         | 0.83%   |
| Philippines | 4         | 0.83%   |
| New Zealand | 4         | 0.83%   |
| Netherlands | 4         | 0.83%   |
| Estonia     | 4         | 0.83%   |
| Denmark     | 4         | 0.83%   |
| China       | 4         | 0.83%   |
| South Korea | 3         | 0.62%   |
| Singapore   | 3         | 0.62%   |
| Serbia      | 3         | 0.62%   |
| Romania     | 3         | 0.62%   |
| Lithuania   | 3         | 0.62%   |
| Greece      | 3         | 0.62%   |
| Bulgaria    | 3         | 0.62%   |
| Argentina   | 3         | 0.62%   |
| UAE         | 2         | 0.41%   |
| Thailand    | 2         | 0.41%   |
| Taiwan      | 2         | 0.41%   |
| Slovakia    | 2         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 13        | 2.61%   |
| Milan         | 11        | 2.21%   |
| Paris         | 8         | 1.61%   |
| Warsaw        | 7         | 1.41%   |
| Castro Valley | 5         | 1%      |
| Berlin        | 5         | 1%      |
| Bengaluru     | 5         | 1%      |
| St Petersburg | 4         | 0.8%    |
| Madrid        | 4         | 0.8%    |
| Wroclaw       | 3         | 0.6%    |
| Vladivostok   | 3         | 0.6%    |
| Vilnius       | 3         | 0.6%    |
| Turin         | 3         | 0.6%    |
| Tallinn       | 3         | 0.6%    |
| Singapore     | 3         | 0.6%    |
| Prague        | 3         | 0.6%    |
| Jakarta       | 3         | 0.6%    |
| Cologne       | 3         | 0.6%    |
| Budapest      | 3         | 0.6%    |
| Auckland      | 3         | 0.6%    |
| Adelaide      | 3         | 0.6%    |
| Zurich        | 2         | 0.4%    |
| Zagreb        | 2         | 0.4%    |
| Taipei        | 2         | 0.4%    |
| Surabaya      | 2         | 0.4%    |
| Sundsvall     | 2         | 0.4%    |
| Sofia         | 2         | 0.4%    |
| Seattle       | 2         | 0.4%    |
| Sao Paulo     | 2         | 0.4%    |
| Samara        | 2         | 0.4%    |
| Salerno       | 2         | 0.4%    |
| Rome          | 2         | 0.4%    |
| Quito         | 2         | 0.4%    |
| Poznan        | 2         | 0.4%    |
| Porto         | 2         | 0.4%    |
| Parma         | 2         | 0.4%    |
| Nuremberg     | 2         | 0.4%    |
| Murska Sobota | 2         | 0.4%    |
| Munich        | 2         | 0.4%    |
| Montreal      | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 116       | 152    | 18.41%  |
| WDC                       | 64        | 76     | 10.16%  |
| Kingston                  | 44        | 48     | 6.98%   |
| Seagate                   | 41        | 53     | 6.51%   |
| SanDisk                   | 41        | 55     | 6.51%   |
| SK hynix                  | 36        | 41     | 5.71%   |
| Toshiba                   | 33        | 45     | 5.24%   |
| Unknown                   | 32        | 41     | 5.08%   |
| Intel                     | 24        | 27     | 3.81%   |
| Micron Technology         | 20        | 22     | 3.17%   |
| Crucial                   | 18        | 19     | 2.86%   |
| KIOXIA                    | 15        | 16     | 2.38%   |
| HGST                      | 13        | 14     | 2.06%   |
| Hitachi                   | 10        | 10     | 1.59%   |
| China                     | 8         | 11     | 1.27%   |
| A-DATA Technology         | 7         | 7      | 1.11%   |
| Unknown                   | 7         | 7      | 1.11%   |
| SPCC                      | 6         | 6      | 0.95%   |
| Apple                     | 6         | 7      | 0.95%   |
| SSSTC                     | 5         | 5      | 0.79%   |
| Phison                    | 5         | 5      | 0.79%   |
| LITEON                    | 5         | 5      | 0.79%   |
| Silicon Motion            | 4         | 4      | 0.63%   |
| Phison Electronics        | 4         | 4      | 0.63%   |
| Micron/Crucial Technology | 4         | 6      | 0.63%   |
| UMIS                      | 3         | 3      | 0.48%   |
| PNY                       | 3         | 3      | 0.48%   |
| Patriot                   | 3         | 3      | 0.48%   |
| Netac                     | 3         | 3      | 0.48%   |
| JMicron Technology        | 3         | 3      | 0.48%   |
| Union Memory              | 2         | 2      | 0.32%   |
| Smart                     | 2         | 2      | 0.32%   |
| SABRENT                   | 2         | 4      | 0.32%   |
| Realtek Semiconductor     | 2         | 2      | 0.32%   |
| LITEONIT                  | 2         | 2      | 0.32%   |
| GOODRAM                   | 2         | 2      | 0.32%   |
| Emtec                     | 2         | 2      | 0.32%   |
| ADATA Technology          | 2         | 3      | 0.32%   |
| YMTC                      | 1         | 1      | 0.16%   |
| VISIPRO                   | 1         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD                     | 8         | 1.2%    |
| Samsung SSD 860 EVO 500GB                           | 7         | 1.05%   |
| Unknown                                             | 7         | 1.05%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 6         | 0.9%    |
| Unknown MMC Card  64GB                              | 5         | 0.75%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 0.75%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 5         | 0.75%   |
| Samsung SSD 980 PRO 1TB                             | 5         | 0.75%   |
| Samsung SSD 970 EVO Plus 250GB                      | 5         | 0.75%   |
| Samsung SSD 850 EVO 250GB                           | 5         | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 0.75%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 0.6%    |
| Seagate ST2000LM015-2E8174 2TB                      | 4         | 0.6%    |
| Seagate ST2000LM007-1R8174 2TB                      | 4         | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB                          | 4         | 0.6%    |
| HGST HTS721010A9E630 1TB                            | 4         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.45%   |
| Unknown MMC Card  32GB                              | 3         | 0.45%   |
| Unknown MMC Card  128GB                             | 3         | 0.45%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB              | 3         | 0.45%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.45%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 3         | 0.45%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.45%   |
| Samsung SSD 860 QVO 1TB                             | 3         | 0.45%   |
| Samsung PM9A1 NVMe 512GB                            | 3         | 0.45%   |
| Samsung NVMe SSD Drive 512GB                        | 3         | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 0.45%   |
| Samsung MZVLB1T0HBLR-000H1 1TB                      | 3         | 0.45%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 0.45%   |
| Micron 3400_MTFDKBA1T0TFH 1TB                       | 3         | 0.45%   |
| Kingston SA2000M81000G 1TB                          | 3         | 0.45%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.45%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.45%   |
| China SSD 128GB                                     | 3         | 0.45%   |
| WDC WDS480G2G0C-00AJM0 480GB                        | 2         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 40        | 52     | 37.04%  |
| WDC      | 25        | 26     | 23.15%  |
| Toshiba  | 15        | 22     | 13.89%  |
| HGST     | 13        | 14     | 12.04%  |
| Hitachi  | 10        | 10     | 9.26%   |
| USB3.0   | 1         | 1      | 0.93%   |
| Unknown  | 1         | 1      | 0.93%   |
| KESU     | 1         | 1      | 0.93%   |
| HGST HTS | 1         | 1      | 0.93%   |
| External | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 59     | 24.06%  |
| Kingston            | 27        | 29     | 14.44%  |
| SanDisk             | 21        | 29     | 11.23%  |
| Crucial             | 11        | 12     | 5.88%   |
| WDC                 | 10        | 16     | 5.35%   |
| China               | 7         | 10     | 3.74%   |
| LITEON              | 5         | 5      | 2.67%   |
| Intel               | 5         | 6      | 2.67%   |
| A-DATA Technology   | 5         | 5      | 2.67%   |
| SPCC                | 4         | 4      | 2.14%   |
| Toshiba             | 3         | 6      | 1.6%    |
| SK hynix            | 3         | 3      | 1.6%    |
| Patriot             | 3         | 3      | 1.6%    |
| Apple               | 3         | 3      | 1.6%    |
| Smart               | 2         | 2      | 1.07%   |
| SABRENT             | 2         | 4      | 1.07%   |
| Netac               | 2         | 2      | 1.07%   |
| Micron Technology   | 2         | 2      | 1.07%   |
| LITEONIT            | 2         | 2      | 1.07%   |
| GOODRAM             | 2         | 2      | 1.07%   |
| Emtec               | 2         | 2      | 1.07%   |
| Unknown             | 2         | 2      | 1.07%   |
| VISIPRO             | 1         | 2      | 0.53%   |
| Verbatim            | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| ShiJi               | 1         | 1      | 0.53%   |
| Ramos Technology    | 1         | 1      | 0.53%   |
| R580                | 1         | 1      | 0.53%   |
| PNY                 | 1         | 1      | 0.53%   |
| NGFF                | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| HUSKY               | 1         | 2      | 0.53%   |
| HS-SSD-C100         | 1         | 1      | 0.53%   |
| HIKSEMI             | 1         | 1      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| Dogfish             | 1         | 1      | 0.53%   |
| CT1000P2            | 1         | 1      | 0.53%   |
| Corsair             | 1         | 1      | 0.53%   |
| BAITITON            | 1         | 1      | 0.53%   |
| Apacer              | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 274       | 343    | 46.6%   |
| SSD     | 166       | 229    | 28.23%  |
| HDD     | 104       | 129    | 17.69%  |
| MMC     | 35        | 43     | 5.95%   |
| Unknown | 9         | 10     | 1.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 274       | 343    | 49.1%   |
| SATA | 224       | 327    | 40.14%  |
| MMC  | 35        | 43     | 6.27%   |
| SAS  | 25        | 41     | 4.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 164       | 225    | 61.42%  |
| 0.51-1.0   | 80        | 102    | 29.96%  |
| 1.01-2.0   | 17        | 19     | 6.37%   |
| 4.01-10.0  | 4         | 8      | 1.5%    |
| 10.01-20.0 | 2         | 4      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 137       | 27.96%  |
| 101-250        | 116       | 23.67%  |
| 501-1000       | 95        | 19.39%  |
| 1001-2000      | 65        | 13.27%  |
| 51-100         | 27        | 5.51%   |
| 1-20           | 16        | 3.27%   |
| 2001-3000      | 14        | 2.86%   |
| More than 3000 | 12        | 2.45%   |
| 21-50          | 7         | 1.43%   |
| Unknown        | 1         | 0.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 116       | 23.34%  |
| 101-250        | 102       | 20.52%  |
| 21-50          | 72        | 14.49%  |
| 51-100         | 71        | 14.29%  |
| 251-500        | 70        | 14.08%  |
| 501-1000       | 37        | 7.44%   |
| 1001-2000      | 21        | 4.23%   |
| More than 3000 | 5         | 1.01%   |
| 2001-3000      | 2         | 0.4%    |
| Unknown        | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| SK hynix BC711 HFM512GD3JX013N 512GB                | 2         | 2      | 6.45%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 2         | 2      | 6.45%   |
| Seagate ST2000LM007-1R8174 2TB                      | 2         | 2      | 6.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 3.23%   |
| VISIPRO SSD 256GB                                   | 1         | 2      | 3.23%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.23%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 3.23%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 3.23%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 1      | 3.23%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 3.23%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.23%   |
| R580 SSD 60GB                                       | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 3.23%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 3.23%   |
| Hitachi HTS725050A7E630 500GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.23%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.23%   |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 3.23%   |
| Crucial CT1050MX300SSD1 1TB                         | 1         | 1      | 3.23%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 3.23%   |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 3.23%   |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 3.23%   |
| A-DATA Technology FALCON 1TB                        | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 16.13%  |
| SK hynix            | 4         | 4      | 12.9%   |
| Hitachi             | 4         | 4      | 12.9%   |
| Crucial             | 3         | 3      | 9.68%   |
| Toshiba             | 2         | 2      | 6.45%   |
| SanDisk             | 2         | 2      | 6.45%   |
| HGST                | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| VISIPRO             | 1         | 2      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| R580                | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| BAITITON            | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 38.46%  |
| Hitachi | 4         | 4      | 30.77%  |
| Toshiba | 2         | 2      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 43.33%  |
| SSD  | 11        | 13     | 36.67%  |
| NVMe | 6         | 6      | 20%     |

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
| Works    | 292       | 396    | 55.09%  |
| Detected | 208       | 326    | 39.25%  |
| Malfunc  | 30        | 32     | 5.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 285       | 45.24%  |
| Samsung Electronics            | 75        | 11.9%   |
| AMD                            | 61        | 9.68%   |
| SanDisk                        | 51        | 8.1%    |
| SK hynix                       | 33        | 5.24%   |
| Toshiba America Info Systems   | 18        | 2.86%   |
| Micron Technology              | 18        | 2.86%   |
| Kingston Technology Company    | 18        | 2.86%   |
| Phison Electronics             | 12        | 1.9%    |
| KIOXIA                         | 12        | 1.9%    |
| Micron/Crucial Technology      | 11        | 1.75%   |
| Solid State Storage Technology | 7         | 1.11%   |
| Union Memory (Shenzhen)        | 5         | 0.79%   |
| Silicon Motion                 | 5         | 0.79%   |
| Realtek Semiconductor          | 5         | 0.79%   |
| Apple                          | 3         | 0.48%   |
| Nvidia                         | 2         | 0.32%   |
| ADATA Technology               | 2         | 0.32%   |
| Zhaoxin                        | 1         | 0.16%   |
| Yangtze Memory Technologies    | 1         | 0.16%   |
| Shenzhen Longsys Electronics   | 1         | 0.16%   |
| Seagate Technology             | 1         | 0.16%   |
| Netac Technology               | 1         | 0.16%   |
| Marvell Technology Group       | 1         | 0.16%   |
| Unknown                        | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 57        | 8.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 42        | 6.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 37        | 5.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 37        | 5.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 34        | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 3.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 2.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 2.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 19        | 2.81%   |
| Samsung NVMe SSD Controller 980                                                | 19        | 2.81%   |
| Micron NVMe Storage Controller                                                 | 18        | 2.66%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 2.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 17        | 2.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 14        | 2.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 1.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 10        | 1.48%   |
| SanDisk Non-Volatile memory controller                                         | 10        | 1.48%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 10        | 1.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 1.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.33%   |
| Intel SSD 660P Series                                                          | 8         | 1.18%   |
| Solid State Storage Non-Volatile memory controller                             | 7         | 1.04%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 7         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6         | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 0.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 0.89%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 5         | 0.74%   |
| Realtek NVMe Controller                                                        | 5         | 0.74%   |
| Intel Non-Volatile memory controller                                           | 5         | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.74%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.74%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 4         | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 0.59%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 4         | 0.59%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 4         | 0.59%   |
| SanDisk NVMe Controller                                                        | 4         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 296       | 46.18%  |
| NVMe | 273       | 42.59%  |
| RAID | 61        | 9.52%   |
| IDE  | 11        | 1.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 364       | 75.68%  |
| AMD          | 116       | 24.12%  |
| CentaurHauls | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics   | 17        | 3.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 15        | 3.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 14        | 2.91%   |
| Intel 12th Gen Core i7-12700H            | 13        | 2.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 13        | 2.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz        | 12        | 2.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 11        | 2.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 9         | 1.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 9         | 1.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 8         | 1.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 8         | 1.66%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 7         | 1.46%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 7         | 1.46%   |
| AMD Ryzen 5 4600H with Radeon Graphics   | 7         | 1.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 6         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 5         | 1.04%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 5         | 1.04%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 5         | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 5         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 5         | 1.04%   |
| Intel 12th Gen Core i7-1260P             | 5         | 1.04%   |
| Intel 12th Gen Core i7-1255U             | 5         | 1.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 4         | 0.83%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 4         | 0.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 0.83%   |
| Intel Core i5-10300H CPU @ 2.50GHz       | 4         | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 4         | 0.83%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz  | 4         | 0.83%   |
| AMD Ryzen 9 5900HX with Radeon Graphics  | 4         | 0.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 4         | 0.83%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 3         | 0.62%   |
| Intel Core i9-9980HK CPU @ 2.40GHz       | 3         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 3         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 3         | 0.62%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 3         | 0.62%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 3         | 0.62%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 3         | 0.62%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 3         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 109       | 22.66%  |
| Other                   | 96        | 19.96%  |
| Intel Core i5           | 96        | 19.96%  |
| AMD Ryzen 7             | 43        | 8.94%   |
| AMD Ryzen 5             | 33        | 6.86%   |
| Intel Celeron           | 21        | 4.37%   |
| Intel Core i3           | 15        | 3.12%   |
| Intel Core 2 Duo        | 7         | 1.46%   |
| AMD Ryzen 9             | 7         | 1.46%   |
| AMD Ryzen 7 PRO         | 7         | 1.46%   |
| Intel Pentium           | 6         | 1.25%   |
| AMD Ryzen 3             | 6         | 1.25%   |
| Intel Pentium Silver    | 5         | 1.04%   |
| Intel Core i9           | 5         | 1.04%   |
| AMD A6                  | 4         | 0.83%   |
| AMD Ryzen 5 PRO         | 3         | 0.62%   |
| AMD A8                  | 3         | 0.62%   |
| Intel Core m3           | 2         | 0.42%   |
| AMD E                   | 2         | 0.42%   |
| Intel Xeon              | 1         | 0.21%   |
| Intel Core M            | 1         | 0.21%   |
| Intel Core 2            | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| AMD Sempron             | 1         | 0.21%   |
| AMD PRO A10             | 1         | 0.21%   |
| AMD FX                  | 1         | 0.21%   |
| AMD Athlon II Dual-Core | 1         | 0.21%   |
| AMD Athlon              | 1         | 0.21%   |
| AMD A4                  | 1         | 0.21%   |
| AMD A10                 | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 166       | 34.51%  |
| 2      | 153       | 31.81%  |
| 8      | 64        | 13.31%  |
| 6      | 62        | 12.89%  |
| 14     | 17        | 3.53%   |
| 12     | 8         | 1.66%   |
| 10     | 8         | 1.66%   |
| 24     | 1         | 0.21%   |
| 5      | 1         | 0.21%   |
| 1      | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 481       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 418       | 86.72%  |
| 1      | 64        | 13.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 481       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 33.94%  |
| 0x806c1    | 30        | 6.1%    |
| 0x906a3    | 24        | 4.88%   |
| 0x306a9    | 24        | 4.88%   |
| 0x0a50000c | 21        | 4.27%   |
| 0x806ea    | 19        | 3.86%   |
| 0x906ea    | 15        | 3.05%   |
| 0x08608103 | 14        | 2.85%   |
| 0x08600106 | 13        | 2.64%   |
| 0x406e3    | 11        | 2.24%   |
| 0x806ec    | 10        | 2.03%   |
| 0x806e9    | 8         | 1.63%   |
| 0x306c3    | 8         | 1.63%   |
| 0x206a7    | 8         | 1.63%   |
| 0xa0652    | 7         | 1.42%   |
| 0x906a4    | 7         | 1.42%   |
| 0x806d1    | 6         | 1.22%   |
| 0x806c2    | 6         | 1.22%   |
| 0x706a8    | 6         | 1.22%   |
| 0x08108109 | 6         | 1.22%   |
| 0x706a1    | 5         | 1.02%   |
| 0x40651    | 5         | 1.02%   |
| 0x08608102 | 5         | 1.02%   |
| 0x906e9    | 4         | 0.81%   |
| 0x706e5    | 4         | 0.81%   |
| 0x506c9    | 4         | 0.81%   |
| 0x40661    | 4         | 0.81%   |
| 0x0a50000d | 4         | 0.81%   |
| 0x906ed    | 3         | 0.61%   |
| 0x506e3    | 3         | 0.61%   |
| 0x306d4    | 3         | 0.61%   |
| 0x20652    | 3         | 0.61%   |
| 0x0a404101 | 3         | 0.61%   |
| 0x08600103 | 3         | 0.61%   |
| 0x08108102 | 3         | 0.61%   |
| 0x06006705 | 3         | 0.61%   |
| 0x03000027 | 3         | 0.61%   |
| 0x1067a    | 2         | 0.41%   |
| 0x0a404102 | 2         | 0.41%   |
| 0x0810100b | 2         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 91        | 18.88%  |
| TigerLake        | 50        | 10.37%  |
| IvyBridge        | 43        | 8.92%   |
| Unknown          | 40        | 8.3%    |
| Zen 3            | 35        | 7.26%   |
| Haswell          | 31        | 6.43%   |
| Alderlake Hybrid | 31        | 6.43%   |
| Skylake          | 22        | 4.56%   |
| Zen 2            | 20        | 4.15%   |
| Goldmont plus    | 17        | 3.53%   |
| SandyBridge      | 16        | 3.32%   |
| Zen+             | 13        | 2.7%    |
| IceLake          | 12        | 2.49%   |
| CometLake        | 11        | 2.28%   |
| Westmere         | 6         | 1.24%   |
| Broadwell        | 6         | 1.24%   |
| Silvermont       | 5         | 1.04%   |
| Penryn           | 5         | 1.04%   |
| Goldmont         | 5         | 1.04%   |
| Excavator        | 4         | 0.83%   |
| Core             | 4         | 0.83%   |
| K10 Llano        | 3         | 0.62%   |
| Zen              | 2         | 0.41%   |
| Puma             | 2         | 0.41%   |
| Piledriver       | 2         | 0.41%   |
| Bobcat           | 2         | 0.41%   |
| Steamroller      | 1         | 0.21%   |
| Nehalem          | 1         | 0.21%   |
| K8 & K10 hybrid  | 1         | 0.21%   |
| K10              | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 342       | 52.86%  |
| Nvidia  | 163       | 25.19%  |
| AMD     | 141       | 21.79%  |
| Zhaoxin | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 42        | 6.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 41        | 6.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 28        | 4.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 23        | 3.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 23        | 3.49%   |
| AMD Lucienne                                                                          | 22        | 3.34%   |
| Intel UHD Graphics 620                                                                | 20        | 3.03%   |
| AMD Renoir                                                                            | 20        | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 19        | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 16        | 2.43%   |
| Intel HD Graphics 620                                                                 | 16        | 2.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 15        | 2.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 13        | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 12        | 1.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 10        | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 10        | 1.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 10        | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 8         | 1.21%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 8         | 1.21%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 8         | 1.21%   |
| Intel HD Graphics 630                                                                 | 8         | 1.21%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 8         | 1.21%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 1.21%   |
| AMD Rembrandt [Radeon 680M]                                                           | 8         | 1.21%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 7         | 1.06%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 7         | 1.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 1.06%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 6         | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 5         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 5         | 0.76%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 5         | 0.76%   |
| Intel HD Graphics 5500                                                                | 5         | 0.76%   |
| Intel HD Graphics 500                                                                 | 5         | 0.76%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 5         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 0.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 0.61%   |
| Intel HD Graphics 530                                                                 | 4         | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 4         | 0.61%   |
| AMD Barcelo                                                                           | 4         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 200       | 41.49%  |
| Intel + Nvidia | 115       | 23.86%  |
| 1 x AMD        | 82        | 17.01%  |
| AMD + Nvidia   | 26        | 5.39%   |
| Intel + AMD    | 25        | 5.19%   |
| 1 x Nvidia     | 22        | 4.56%   |
| 2 x AMD        | 8         | 1.66%   |
| Other          | 2         | 0.41%   |
| 2 x Nvidia     | 1         | 0.21%   |
| 1 x Zhaoxin    | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 359       | 74.17%  |
| Proprietary | 117       | 24.17%  |
| Unknown     | 8         | 1.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 349       | 71.66%  |
| 0.01-0.5   | 56        | 11.5%   |
| 1.01-2.0   | 34        | 6.98%   |
| 3.01-4.0   | 17        | 3.49%   |
| 0.51-1.0   | 16        | 3.29%   |
| 5.01-6.0   | 7         | 1.44%   |
| 7.01-8.0   | 6         | 1.23%   |
| 8.01-16.0  | 2         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 96        | 16.58%  |
| BOE                     | 94        | 16.23%  |
| AU Optronics            | 90        | 15.54%  |
| LG Display              | 74        | 12.78%  |
| Samsung Electronics     | 54        | 9.33%   |
| Sharp                   | 21        | 3.63%   |
| Goldstar                | 19        | 3.28%   |
| Dell                    | 17        | 2.94%   |
| Hewlett-Packard         | 13        | 2.25%   |
| Apple                   | 10        | 1.73%   |
| Lenovo                  | 9         | 1.55%   |
| CSO                     | 9         | 1.55%   |
| Philips                 | 7         | 1.21%   |
| InfoVision              | 7         | 1.21%   |
| Chi Mei Optoelectronics | 7         | 1.21%   |
| BenQ                    | 7         | 1.21%   |
| Acer                    | 7         | 1.21%   |
| ASUSTek Computer        | 5         | 0.86%   |
| PANDA                   | 3         | 0.52%   |
| Ancor Communications    | 3         | 0.52%   |
| SLD                     | 2         | 0.35%   |
| Sceptre Tech            | 2         | 0.35%   |
| IBM                     | 2         | 0.35%   |
| HKC                     | 2         | 0.35%   |
| Vizio                   | 1         | 0.17%   |
| ViewSonic               | 1         | 0.17%   |
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
| Envision Peripherals    | 1         | 0.17%   |
| CVT                     | 1         | 0.17%   |
| CPT                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 1.02%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 1.02%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.85%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.68%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 4         | 0.68%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.51%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.51%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.51%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 3         | 0.51%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.51%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                 | 3         | 0.51%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.51%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch        | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.51%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 2         | 0.34%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 527x296mm 23.8-inch   | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.34%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 2         | 0.34%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch          | 2         | 0.34%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 480x270mm 21.7-inch           | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 281       | 52.82%  |
| 1366x768 (WXGA)    | 102       | 19.17%  |
| 2560x1440 (QHD)    | 27        | 5.08%   |
| 3840x2160 (4K)     | 23        | 4.32%   |
| 1920x1200 (WUXGA)  | 20        | 3.76%   |
| 1600x900 (HD+)     | 18        | 3.38%   |
| 2560x1600          | 12        | 2.26%   |
| 2880x1800          | 11        | 2.07%   |
| 1680x1050 (WSXGA+) | 7         | 1.32%   |
| 2560x1080          | 5         | 0.94%   |
| 3440x1440          | 4         | 0.75%   |
| 2256x1504          | 3         | 0.56%   |
| 1280x800 (WXGA)    | 3         | 0.56%   |
| 2520x1680          | 2         | 0.38%   |
| 2240x1400          | 2         | 0.38%   |
| 2160x1440          | 2         | 0.38%   |
| 1440x900 (WXGA+)   | 2         | 0.38%   |
| 1024x768 (XGA)     | 2         | 0.38%   |
| 3840x2400          | 1         | 0.19%   |
| 3840x1080          | 1         | 0.19%   |
| 3072x1920          | 1         | 0.19%   |
| 2160x1350          | 1         | 0.19%   |
| 1920x540           | 1         | 0.19%   |
| 1280x1024 (SXGA)   | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 232       | 39.93%  |
| 14      | 77        | 13.25%  |
| 13      | 65        | 11.19%  |
| 17      | 45        | 7.75%   |
| 24      | 27        | 4.65%   |
| 27      | 25        | 4.3%    |
| 16      | 24        | 4.13%   |
| 23      | 16        | 2.75%   |
| 21      | 14        | 2.41%   |
| 34      | 9         | 1.55%   |
| 12      | 9         | 1.55%   |
| 11      | 7         | 1.2%    |
| 31      | 6         | 1.03%   |
| 22      | 5         | 0.86%   |
| 54      | 3         | 0.52%   |
| 49      | 2         | 0.34%   |
| 25      | 2         | 0.34%   |
| 84      | 1         | 0.17%   |
| 78      | 1         | 0.17%   |
| 72      | 1         | 0.17%   |
| 65      | 1         | 0.17%   |
| 63      | 1         | 0.17%   |
| 60      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |
| 18      | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 349       | 60.8%   |
| 501-600     | 63        | 10.98%  |
| 351-400     | 59        | 10.28%  |
| 201-300     | 50        | 8.71%   |
| 401-500     | 22        | 3.83%   |
| 701-800     | 9         | 1.57%   |
| 601-700     | 9         | 1.57%   |
| 1001-1500   | 8         | 1.39%   |
| 1501-2000   | 3         | 0.52%   |
| 901-1000    | 1         | 0.17%   |
| Unknown     | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 410       | 83%     |
| 16/10   | 62        | 12.55%  |
| 21/9    | 10        | 2.02%   |
| 3/2     | 7         | 1.42%   |
| 4/3     | 2         | 0.4%    |
| 5/4     | 1         | 0.2%    |
| 32/9    | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 240       | 41.81%  |
| 81-90          | 116       | 20.21%  |
| 201-250        | 50        | 8.71%   |
| 121-130        | 42        | 7.32%   |
| 71-80          | 27        | 4.7%    |
| 301-350        | 26        | 4.53%   |
| 111-120        | 15        | 2.61%   |
| 351-500        | 14        | 2.44%   |
| More than 1000 | 10        | 1.74%   |
| 61-70          | 8         | 1.39%   |
| 51-60          | 7         | 1.22%   |
| 251-300        | 7         | 1.22%   |
| 151-200        | 4         | 0.7%    |
| 141-150        | 2         | 0.35%   |
| 131-140        | 2         | 0.35%   |
| 501-1000       | 2         | 0.35%   |
| 91-100         | 1         | 0.17%   |
| Unknown        | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 271       | 48.05%  |
| 101-120       | 122       | 21.63%  |
| 51-100        | 79        | 14.01%  |
| 161-240       | 66        | 11.7%   |
| More than 240 | 18        | 3.19%   |
| 1-50          | 7         | 1.24%   |
| Unknown       | 1         | 0.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 366       | 75.15%  |
| 2     | 89        | 18.28%  |
| 3     | 19        | 3.9%    |
| 0     | 9         | 1.85%   |
| 4     | 4         | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 271       | 35.94%  |
| Intel                             | 270       | 35.81%  |
| Qualcomm Atheros                  | 78        | 10.34%  |
| MediaTek                          | 37        | 4.91%   |
| Broadcom                          | 31        | 4.11%   |
| ASIX Electronics                  | 7         | 0.93%   |
| Sierra Wireless                   | 5         | 0.66%   |
| Samsung Electronics               | 5         | 0.66%   |
| TP-Link                           | 4         | 0.53%   |
| Qualcomm                          | 4         | 0.53%   |
| Broadcom Limited                  | 4         | 0.53%   |
| Ralink Technology                 | 3         | 0.4%    |
| Marvell Technology Group          | 3         | 0.4%    |
| Lenovo                            | 3         | 0.4%    |
| Xiaomi                            | 2         | 0.27%   |
| Ralink                            | 2         | 0.27%   |
| Nvidia                            | 2         | 0.27%   |
| Huawei Technologies               | 2         | 0.27%   |
| Hewlett-Packard                   | 2         | 0.27%   |
| Google                            | 2         | 0.27%   |
| Ericsson Business Mobile Networks | 2         | 0.27%   |
| DisplayLink                       | 2         | 0.27%   |
| Dell                              | 2         | 0.27%   |
| Apple                             | 2         | 0.27%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 154       | 17.02%  |
| Intel Wi-Fi 6 AX201                                               | 36        | 3.98%   |
| Intel Wi-Fi 6 AX200                                               | 35        | 3.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 3.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 28        | 3.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 2.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 16        | 1.77%   |
| Intel Wireless 7260                                               | 16        | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 1.33%   |
| Intel Wireless 7265                                               | 12        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 1.33%   |
| Intel Wireless 8260                                               | 11        | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.77%   |
| Realtek 802.11n WLAN Adapter                                      | 7         | 0.77%   |
| Intel Wireless 3165                                               | 7         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.66%   |
| Intel Centrino Advanced-N 6235                                    | 6         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 259       | 51.49%  |
| Realtek Semiconductor | 96        | 19.09%  |
| Qualcomm Atheros      | 62        | 12.33%  |
| MediaTek              | 37        | 7.36%   |
| Broadcom              | 24        | 4.77%   |
| Sierra Wireless       | 5         | 0.99%   |
| Qualcomm              | 4         | 0.8%    |
| Ralink Technology     | 3         | 0.6%    |
| Broadcom Limited      | 3         | 0.6%    |
| TP-Link               | 2         | 0.4%    |
| Ralink                | 2         | 0.4%    |
| Dell                  | 2         | 0.4%    |
| Fibocom               | 1         | 0.2%    |
| D-Link System         | 1         | 0.2%    |
| Belkin Components     | 1         | 0.2%    |
| ASUSTek Computer      | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 36        | 7.07%   |
| Intel Wi-Fi 6 AX200                                            | 35        | 6.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 30        | 5.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 28        | 5.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 4.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 4.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 3.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 3.14%   |
| Intel Wireless 8265 / 8275                                     | 16        | 3.14%   |
| Intel Wireless 7260                                            | 16        | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 2.36%   |
| Intel Wireless 7265                                            | 12        | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 2.36%   |
| Intel Wireless 8260                                            | 11        | 2.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.38%   |
| Realtek 802.11n WLAN Adapter                                   | 7         | 1.38%   |
| Intel Wireless 3165                                            | 7         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.18%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.98%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.79%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.79%   |
| Intel Wireless 3160                                            | 4         | 0.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 0.79%   |
| Realtek 802.11ac NIC                                           | 3         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 222       | 59.36%  |
| Intel                    | 92        | 24.6%   |
| Qualcomm Atheros         | 18        | 4.81%   |
| Broadcom                 | 10        | 2.67%   |
| ASIX Electronics         | 7         | 1.87%   |
| Samsung Electronics      | 3         | 0.8%    |
| Marvell Technology Group | 3         | 0.8%    |
| Lenovo                   | 3         | 0.8%    |
| Xiaomi                   | 2         | 0.53%   |
| TP-Link                  | 2         | 0.53%   |
| Nvidia                   | 2         | 0.53%   |
| Huawei Technologies      | 2         | 0.53%   |
| Google                   | 2         | 0.53%   |
| DisplayLink              | 2         | 0.53%   |
| Apple                    | 2         | 0.53%   |
| JMicron Technology       | 1         | 0.27%   |
| Broadcom Limited         | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 154       | 39.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 7.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 6.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 5.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 2.07%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 1.81%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.81%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 1.55%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.3%    |
| Intel Ethernet Connection (10) I219-V                             | 5         | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.78%   |
| Intel Ethernet Connection (16) I219-LM                            | 3         | 0.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.52%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.52%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.52%   |
| DisplayLink StarTech USB3DOCKHDPC                                 | 2         | 0.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.26%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 480       | 56.87%  |
| Ethernet | 354       | 41.94%  |
| Modem    | 7         | 0.83%   |
| Unknown  | 3         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 414       | 80.86%  |
| Ethernet | 98        | 19.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 321       | 66.74%  |
| 1     | 145       | 30.15%  |
| 0     | 12        | 2.49%   |
| 3     | 3         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 353       | 73.08%  |
| Yes  | 130       | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 218       | 51.17%  |
| Realtek Semiconductor           | 56        | 13.15%  |
| Qualcomm Atheros Communications | 33        | 7.75%   |
| IMC Networks                    | 22        | 5.16%   |
| Foxconn / Hon Hai               | 22        | 5.16%   |
| Broadcom                        | 21        | 4.93%   |
| Lite-On Technology              | 18        | 4.23%   |
| Apple                           | 6         | 1.41%   |
| Realtek                         | 5         | 1.17%   |
| Dell                            | 5         | 1.17%   |
| Toshiba                         | 4         | 0.94%   |
| TP-Link                         | 2         | 0.47%   |
| Hewlett-Packard                 | 2         | 0.47%   |
| Cambridge Silicon Radio         | 2         | 0.47%   |
| ASUSTek Computer                | 2         | 0.47%   |
| USI                             | 1         | 0.23%   |
| SINO WEALTH                     | 1         | 0.23%   |
| Ralink                          | 1         | 0.23%   |
| MediaTek                        | 1         | 0.23%   |
| Foxconn International           | 1         | 0.23%   |
| Edimax Technology               | 1         | 0.23%   |
| Chicony Electronics             | 1         | 0.23%   |
| Alps Electric                   | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 60        | 14.08%  |
| Intel AX201 Bluetooth                               | 60        | 14.08%  |
| Realtek Bluetooth Radio                             | 45        | 10.56%  |
| Intel AX200 Bluetooth                               | 33        | 7.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 27        | 6.34%   |
| Intel Bluetooth Device                              | 20        | 4.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 3.52%   |
| Lite-On Wireless_Device                             | 11        | 2.58%   |
| IMC Networks Wireless_Device                        | 10        | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 2.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 2.11%   |
| Intel AX210 Bluetooth                               | 9         | 2.11%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 2.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.41%   |
| Broadcom HP Portable SoftSailing                    | 6         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.41%   |
| Realtek Bluetooth Radio                             | 5         | 1.17%   |
| Apple Bluetooth Host Controller                     | 5         | 1.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.7%    |
| IMC Networks Bluetooth Device                       | 3         | 0.7%    |
| Dell DW375 Bluetooth Module                         | 3         | 0.7%    |
| TP-Link UB500 Adapter                               | 2         | 0.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.47%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.47%   |
| USI Bluetooth Device                                | 1         | 0.23%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.23%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.23%   |
| Toshiba Bluetooth Device                            | 1         | 0.23%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.23%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.23%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.23%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.23%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 362       | 57.46%  |
| AMD                   | 122       | 19.37%  |
| Nvidia                | 92        | 14.6%   |
| C-Media Electronics   | 10        | 1.59%   |
| Lenovo                | 5         | 0.79%   |
| JMTek                 | 5         | 0.79%   |
| Realtek Semiconductor | 4         | 0.63%   |
| Razer USA             | 3         | 0.48%   |
| Texas Instruments     | 2         | 0.32%   |
| Hewlett-Packard       | 2         | 0.32%   |
| GN Netcom             | 2         | 0.32%   |
| Focusrite-Novation    | 2         | 0.32%   |
| Corsair               | 2         | 0.32%   |
| Apple                 | 2         | 0.32%   |
| ZOOM                  | 1         | 0.16%   |
| Zhaoxin               | 1         | 0.16%   |
| TerraTec Electronic   | 1         | 0.16%   |
| Sony                  | 1         | 0.16%   |
| Silicon Motion        | 1         | 0.16%   |
| Princeton Technology  | 1         | 0.16%   |
| Plantronics           | 1         | 0.16%   |
| Logitech              | 1         | 0.16%   |
| Fujitsu               | 1         | 0.16%   |
| DSEA A/S              | 1         | 0.16%   |
| DisplayLink           | 1         | 0.16%   |
| Cyber Acoustics       | 1         | 0.16%   |
| Creative Technology   | 1         | 0.16%   |
| Blue Microphones      | 1         | 0.16%   |
| Arturia               | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 95        | 12.45%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 64        | 8.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 57        | 7.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 50        | 6.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 48        | 6.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 35        | 4.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 27        | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24        | 3.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 2.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 17        | 2.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 1.57%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 1.31%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.31%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 1.05%   |
| Nvidia Audio device                                                        | 8         | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1.05%   |
| Intel CM238 HD Audio Controller                                            | 8         | 1.05%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 1.05%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 0.92%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 0.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 0.79%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 0.66%   |
| Realtek Semiconductor USB Audio                                            | 4         | 0.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 0.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 0.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.52%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.39%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 130       | 30.66%  |
| SK hynix            | 81        | 19.1%   |
| Micron Technology   | 57        | 13.44%  |
| Crucial             | 41        | 9.67%   |
| Kingston            | 29        | 6.84%   |
| Unknown (ABCD)      | 12        | 2.83%   |
| Unknown             | 11        | 2.59%   |
| A-DATA Technology   | 10        | 2.36%   |
| Elpida              | 6         | 1.42%   |
| Unknown             | 6         | 1.42%   |
| Ramaxel Technology  | 5         | 1.18%   |
| Wilk                | 3         | 0.71%   |
| Nanya Technology    | 3         | 0.71%   |
| Corsair             | 3         | 0.71%   |
| Transcend           | 2         | 0.47%   |
| Silicon Power       | 2         | 0.47%   |
| GOODRAM             | 2         | 0.47%   |
| Unknown (8A02)      | 1         | 0.24%   |
| Teikon              | 1         | 0.24%   |
| Team                | 1         | 0.24%   |
| Super Talent        | 1         | 0.24%   |
| Smart               | 1         | 0.24%   |
| Shenzhen Zhongteng  | 1         | 0.24%   |
| Shenzhen WODPOSIT   | 1         | 0.24%   |
| SHARETRONIC         | 1         | 0.24%   |
| Qimonda             | 1         | 0.24%   |
| Patriot             | 1         | 0.24%   |
| Imation             | 1         | 0.24%   |
| Goldkey             | 1         | 0.24%   |
| Gold Key            | 1         | 0.24%   |
| G.Skill             | 1         | 0.24%   |
| ff                  | 1         | 0.24%   |
| Essencore Limited   | 1         | 0.24%   |
| Atermiter           | 1         | 0.24%   |
| ASint Technology    | 1         | 0.24%   |
| Apacer              | 1         | 0.24%   |
| AMD                 | 1         | 0.24%   |
| 4ea5                | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 2.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 1.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.37%   |
| Unknown                                                          | 6         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.14%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 1.14%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 3         | 0.68%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s             | 2         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.46%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.46%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 211       | 60.98%  |
| DDR3   | 74        | 21.39%  |
| LPDDR4 | 31        | 8.96%   |
| DDR5   | 13        | 3.76%   |
| LPDDR5 | 7         | 2.02%   |
| LPDDR3 | 4         | 1.16%   |
| DDR2   | 4         | 1.16%   |
| SDRAM  | 2         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 303       | 85.11%  |
| Row Of Chips | 45        | 12.64%  |
| Chip         | 4         | 1.12%   |
| DIMM         | 2         | 0.56%   |
| Unknown      | 2         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 175       | 46.3%   |
| 4096  | 85        | 22.49%  |
| 16384 | 81        | 21.43%  |
| 32768 | 18        | 4.76%   |
| 2048  | 15        | 3.97%   |
| 1024  | 4         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 128       | 35.36%  |
| 2667    | 64        | 17.68%  |
| 1600    | 56        | 15.47%  |
| 2400    | 32        | 8.84%   |
| 4800    | 13        | 3.59%   |
| 4267    | 12        | 3.31%   |
| 1333    | 11        | 3.04%   |
| 6400    | 7         | 1.93%   |
| 2133    | 7         | 1.93%   |
| 1334    | 7         | 1.93%   |
| 1867    | 6         | 1.66%   |
| 4266    | 4         | 1.1%    |
| 667     | 4         | 1.1%    |
| 3266    | 3         | 0.83%   |
| 8400    | 2         | 0.55%   |
| 4199    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 2666    | 1         | 0.28%   |
| 2048    | 1         | 0.28%   |
| 1067    | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

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
| Chicony Electronics                    | 95        | 20.7%   |
| Microdia                               | 50        | 10.89%  |
| IMC Networks                           | 46        | 10.02%  |
| Quanta                                 | 41        | 8.93%   |
| Realtek Semiconductor                  | 35        | 7.63%   |
| Acer                                   | 30        | 6.54%   |
| Bison Electronics                      | 24        | 5.23%   |
| Sunplus Innovation Technology          | 21        | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.92%   |
| Luxvisions Innotech Limited            | 13        | 2.83%   |
| Logitech                               | 13        | 2.83%   |
| Syntek                                 | 10        | 2.18%   |
| Lite-On Technology                     | 10        | 2.18%   |
| Silicon Motion                         | 5         | 1.09%   |
| Apple                                  | 5         | 1.09%   |
| Y Media                                | 4         | 0.87%   |
| Samsung Electronics                    | 4         | 0.87%   |
| Suyin                                  | 3         | 0.65%   |
| Alcor Micro                            | 3         | 0.65%   |
| Z-Star Microelectronics                | 2         | 0.44%   |
| SunplusIT                              | 2         | 0.44%   |
| Sonix Technology                       | 2         | 0.44%   |
| Lenovo                                 | 2         | 0.44%   |
| icSpring                               | 2         | 0.44%   |
| GEMBIRD                                | 2         | 0.44%   |
| Xiaomi                                 | 1         | 0.22%   |
| USB Camera CS                          | 1         | 0.22%   |
| STEREOLABS                             | 1         | 0.22%   |
| SN0002                                 | 1         | 0.22%   |
| ShineTech                              | 1         | 0.22%   |
| Pixart Imaging                         | 1         | 0.22%   |
| Novatek Microelectronics               | 1         | 0.22%   |
| Importek                               | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| HRY                                    | 1         | 0.22%   |
| HD WEBCAM                              | 1         | 0.22%   |
| Goodong Industry                       | 1         | 0.22%   |
| Goodong                                | 1         | 0.22%   |
| eMPIA Technology                       | 1         | 0.22%   |
| BRS 2Mp Camera                         | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 29        | 6.3%    |
| Microdia Integrated_Webcam_HD                                   | 27        | 5.87%   |
| IMC Networks Integrated Camera                                  | 18        | 3.91%   |
| Realtek Integrated_Webcam_HD                                    | 12        | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 11        | 2.39%   |
| Bison Integrated Camera                                         | 11        | 2.39%   |
| Acer Integrated Camera                                          | 11        | 2.39%   |
| Sunplus Integrated_Webcam_HD                                    | 10        | 2.17%   |
| Quanta HP TrueVision HD Camera                                  | 10        | 2.17%   |
| Chicony HD Webcam                                               | 9         | 1.96%   |
| Chicony HD User Facing                                          | 9         | 1.96%   |
| Quanta HD User Facing                                           | 7         | 1.52%   |
| Syntek Integrated Camera                                        | 6         | 1.3%    |
| Acer HD Webcam                                                  | 6         | 1.3%    |
| Acer BisonCam,NB Pro                                            | 6         | 1.3%    |
| Microdia Integrated_Webcam_FHD                                  | 5         | 1.09%   |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 1.09%   |
| Y Media USB Camera                                              | 4         | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 4         | 0.87%   |
| Realtek USB Camera                                              | 4         | 0.87%   |
| Quanta HP Wide Vision HD Camera                                 | 4         | 0.87%   |
| Quanta HP HD Camera                                             | 4         | 0.87%   |
| Quanta HD Webcam                                                | 4         | 0.87%   |
| Quanta ACER HD User Facing                                      | 4         | 0.87%   |
| Microdia Webcam Vitade AF                                       | 4         | 0.87%   |
| Luxvisions Innotech Limited Integrated Camera                   | 4         | 0.87%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.87%   |
| Lite-On HP HD Camera                                            | 4         | 0.87%   |
| IMC Networks HD Camera                                          | 4         | 0.87%   |
| Chicony USB2.0 Camera                                           | 4         | 0.87%   |
| Chicony HP Wide Vision HD Camera                                | 4         | 0.87%   |
| Chicony HP TrueVision HD Camera                                 | 4         | 0.87%   |
| Chicony HP Truevision HD                                        | 4         | 0.87%   |
| Chicony HP HD Camera                                            | 4         | 0.87%   |
| Sunplus HD WebCam                                               | 3         | 0.65%   |
| Quanta HD Camera                                                | 3         | 0.65%   |
| Microdia Integrated Webcam                                      | 3         | 0.65%   |
| Microdia CameraA                                                | 3         | 0.65%   |
| Logitech HD Pro Webcam C920                                     | 3         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 30        | 30.61%  |
| Synaptics                          | 27        | 27.55%  |
| Validity Sensors                   | 24        | 24.49%  |
| Elan Microelectronics              | 8         | 8.16%   |
| Upek                               | 3         | 3.06%   |
| AuthenTec                          | 2         | 2.04%   |
| STMicroelectronics                 | 1         | 1.02%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.02%   |
| LighTuning Technology              | 1         | 1.02%   |
| Focal-systems.Corp                 | 1         | 1.02%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 23        | 23.47%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 8         | 8.16%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 5.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 5.1%    |
| Shenzhen Goodix Fingerprint Reader                              | 5         | 5.1%    |
| Elan ELAN:ARM-M4                                                | 5         | 5.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 4         | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 4.08%   |
| Validity Sensors VFS491                                         | 3         | 3.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 3.06%   |
| Synaptics UWP WBDI Device                                       | 3         | 3.06%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 3.06%   |
| Elan ELAN:Fingerprint                                           | 3         | 3.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 2         | 2.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 2         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 2.04%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 2         | 2.04%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 2.04%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.02%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 1.02%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.02%   |
| Synaptics UWP WBDI                                              | 1         | 1.02%   |
| Synaptics  WBDI                                                 | 1         | 1.02%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 1.02%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 1.02%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.02%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.02%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.02%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.02%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 18        | 41.86%  |
| Alcor Micro           | 16        | 37.21%  |
| Upek                  | 4         | 9.3%    |
| O2 Micro              | 1         | 2.33%   |
| Lenovo                | 1         | 2.33%   |
| Clay Logic            | 1         | 2.33%   |
| BIT4ID                | 1         | 2.33%   |
| Advanced Card Systems | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 37.21%  |
| Broadcom 58200                                                               | 8         | 18.6%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 9.3%    |
| Broadcom 5880                                                                | 4         | 9.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.98%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 6.98%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 2.33%   |
| BIT4ID miniLector EVO                                                        | 1         | 2.33%   |
| Advanced Card Systems ACR39U                                                 | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 302       | 61.38%  |
| 1     | 143       | 29.07%  |
| 2     | 42        | 8.54%   |
| 3     | 3         | 0.61%   |
| 9     | 1         | 0.2%    |
| 4     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 97        | 41.28%  |
| Chipcard                 | 39        | 16.6%   |
| Graphics card            | 30        | 12.77%  |
| Net/wireless             | 17        | 7.23%   |
| Camera                   | 17        | 7.23%   |
| Multimedia controller    | 14        | 5.96%   |
| Bluetooth                | 6         | 2.55%   |
| Sound                    | 5         | 2.13%   |
| Network                  | 3         | 1.28%   |
| Communication controller | 3         | 1.28%   |
| Net/ethernet             | 2         | 0.85%   |
| Storage                  | 1         | 0.43%   |
| Modem                    | 1         | 0.43%   |

