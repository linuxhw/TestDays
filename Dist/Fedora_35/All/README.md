Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_35/Desktop/README.md) and [notebooks](/Dist/Fedora_35/Notebook/README.md).

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

Total: 2324

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5521               | Notebook    | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5e8318b8b8](https://linux-hardware.org/?probe=5e8318b8b8) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d5c9abda1e](https://linux-hardware.org/?probe=d5c9abda1e) | Dec 15, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [172c6c1300](https://linux-hardware.org/?probe=172c6c1300) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b5c74add87](https://linux-hardware.org/?probe=b5c74add87) | Dec 04, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [8789b14e39](https://linux-hardware.org/?probe=8789b14e39) | Nov 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [8c73ebd2b9](https://linux-hardware.org/?probe=8c73ebd2b9) | Nov 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [40468e1e7f](https://linux-hardware.org/?probe=40468e1e7f) | Nov 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [695b0b0356](https://linux-hardware.org/?probe=695b0b0356) | Nov 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [c4d2b18dd8](https://linux-hardware.org/?probe=c4d2b18dd8) | Nov 10, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [af6fa726d1](https://linux-hardware.org/?probe=af6fa726d1) | Nov 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c62cbe8eb5](https://linux-hardware.org/?probe=c62cbe8eb5) | Nov 08, 2022 |
| Acer          | Aspire VN7-591G             | Notebook    | [541d3bfeca](https://linux-hardware.org/?probe=541d3bfeca) | Nov 07, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [e362ce5bdf](https://linux-hardware.org/?probe=e362ce5bdf) | Nov 07, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [bb8dbe6d52](https://linux-hardware.org/?probe=bb8dbe6d52) | Nov 04, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [f1a58eaa87](https://linux-hardware.org/?probe=f1a58eaa87) | Nov 04, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [653a03dee6](https://linux-hardware.org/?probe=653a03dee6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9bdccc90c4](https://linux-hardware.org/?probe=9bdccc90c4) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0036848bf2](https://linux-hardware.org/?probe=0036848bf2) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [6560f717c9](https://linux-hardware.org/?probe=6560f717c9) | Oct 24, 2022 |
| ASRock        | P45TS                       | Desktop     | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| HP            | Laptop 14s-dr1xxx           | Notebook    | [00d04b6a56](https://linux-hardware.org/?probe=00d04b6a56) | Oct 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [930ee68921](https://linux-hardware.org/?probe=930ee68921) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [b23a59ba48](https://linux-hardware.org/?probe=b23a59ba48) | Sep 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [46be1ea134](https://linux-hardware.org/?probe=46be1ea134) | Sep 08, 2022 |
| Biostar       | H310MHP                     | Desktop     | [6063bede72](https://linux-hardware.org/?probe=6063bede72) | Sep 07, 2022 |
| Lenovo        | 3111 NOK                    | Mini pc     | [778f8bb16e](https://linux-hardware.org/?probe=778f8bb16e) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| Notebook      | NJ5x_NJ7xLU                 | Notebook    | [1cadc455a1](https://linux-hardware.org/?probe=1cadc455a1) | Sep 05, 2022 |
| Lenovo        | 367D 31900003 STD           | Desktop     | [c145bac65a](https://linux-hardware.org/?probe=c145bac65a) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2cf13f4045](https://linux-hardware.org/?probe=2cf13f4045) | Sep 04, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [3b7dae5f40](https://linux-hardware.org/?probe=3b7dae5f40) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [5dcc9cd8c8](https://linux-hardware.org/?probe=5dcc9cd8c8) | Sep 03, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [5730a9015f](https://linux-hardware.org/?probe=5730a9015f) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b2456009ae](https://linux-hardware.org/?probe=b2456009ae) | Aug 31, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [4f026584d7](https://linux-hardware.org/?probe=4f026584d7) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [63efab9aef](https://linux-hardware.org/?probe=63efab9aef) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [eba231b7db](https://linux-hardware.org/?probe=eba231b7db) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ff55a7dbf1](https://linux-hardware.org/?probe=ff55a7dbf1) | Aug 26, 2022 |
| HP            | ENVY 15                     | Notebook    | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f80abd07f3](https://linux-hardware.org/?probe=f80abd07f3) | Aug 25, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [fd6ff49314](https://linux-hardware.org/?probe=fd6ff49314) | Aug 24, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [016c661430](https://linux-hardware.org/?probe=016c661430) | Aug 24, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [1bde57f974](https://linux-hardware.org/?probe=1bde57f974) | Aug 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3f83c9e402](https://linux-hardware.org/?probe=3f83c9e402) | Aug 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1298facab1](https://linux-hardware.org/?probe=1298facab1) | Aug 15, 2022 |
| Itautec       | Infoway W7425               | Notebook    | [64b3153e8a](https://linux-hardware.org/?probe=64b3153e8a) | Aug 15, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [03089b1469](https://linux-hardware.org/?probe=03089b1469) | Aug 13, 2022 |
| Dell          | Latitude 5511               | Notebook    | [69ebaebf95](https://linux-hardware.org/?probe=69ebaebf95) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5eec4d3ccf](https://linux-hardware.org/?probe=5eec4d3ccf) | Aug 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [91a2943c51](https://linux-hardware.org/?probe=91a2943c51) | Aug 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [244025d59e](https://linux-hardware.org/?probe=244025d59e) | Aug 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [258c7a2f71](https://linux-hardware.org/?probe=258c7a2f71) | Aug 06, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9320816ca5](https://linux-hardware.org/?probe=9320816ca5) | Aug 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b224ef1b8d](https://linux-hardware.org/?probe=b224ef1b8d) | Aug 04, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ec7e5864c2](https://linux-hardware.org/?probe=ec7e5864c2) | Aug 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [2aedd7bad4](https://linux-hardware.org/?probe=2aedd7bad4) | Aug 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [015ec264f5](https://linux-hardware.org/?probe=015ec264f5) | Aug 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| Gateway       | DX4860                      | Desktop     | [279b6793e4](https://linux-hardware.org/?probe=279b6793e4) | Jul 30, 2022 |
| Gateway       | DX4860                      | Desktop     | [fec12bcbe9](https://linux-hardware.org/?probe=fec12bcbe9) | Jul 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Gigabyte      | H61M-DS2V                   | Desktop     | [e5744803f2](https://linux-hardware.org/?probe=e5744803f2) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [e4de7eb090](https://linux-hardware.org/?probe=e4de7eb090) | Jul 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [5007f1aa43](https://linux-hardware.org/?probe=5007f1aa43) | Jul 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [38ae00936b](https://linux-hardware.org/?probe=38ae00936b) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [c269d962ea](https://linux-hardware.org/?probe=c269d962ea) | Jul 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [797f0ea7fe](https://linux-hardware.org/?probe=797f0ea7fe) | Jul 18, 2022 |
| HP            | 802E                        | Desktop     | [c86ddd647b](https://linux-hardware.org/?probe=c86ddd647b) | Jul 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e9c788dfd2](https://linux-hardware.org/?probe=e9c788dfd2) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [a002ac843c](https://linux-hardware.org/?probe=a002ac843c) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [79ecbebabd](https://linux-hardware.org/?probe=79ecbebabd) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e4f7616dee](https://linux-hardware.org/?probe=e4f7616dee) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | Notebook    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | Notebook    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [5ecc52d011](https://linux-hardware.org/?probe=5ecc52d011) | Jul 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [fec0786471](https://linux-hardware.org/?probe=fec0786471) | Jul 06, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [28b0984086](https://linux-hardware.org/?probe=28b0984086) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [e795477a20](https://linux-hardware.org/?probe=e795477a20) | Jul 05, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| Intel         | DP55KG AAE47218-404         | Desktop     | [aaa7656f44](https://linux-hardware.org/?probe=aaa7656f44) | Jul 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [f29c4de6b4](https://linux-hardware.org/?probe=f29c4de6b4) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [7ecd760977](https://linux-hardware.org/?probe=7ecd760977) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [8428ba0120](https://linux-hardware.org/?probe=8428ba0120) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| Dell          | Inspiron 7558               | Notebook    | [d34cfa83d3](https://linux-hardware.org/?probe=d34cfa83d3) | Jun 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [3b84529124](https://linux-hardware.org/?probe=3b84529124) | Jun 24, 2022 |
| HP            | ProBook 4520s               | Notebook    | [eb9033a7c1](https://linux-hardware.org/?probe=eb9033a7c1) | Jun 24, 2022 |
| Dell          | 0M877N A01                  | Server      | [107b5509e6](https://linux-hardware.org/?probe=107b5509e6) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [e2790ebf7e](https://linux-hardware.org/?probe=e2790ebf7e) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [c99aceab3b](https://linux-hardware.org/?probe=c99aceab3b) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| HP            | Notebook                    | Notebook    | [03c703cc7f](https://linux-hardware.org/?probe=03c703cc7f) | Jun 21, 2022 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [cc8224a123](https://linux-hardware.org/?probe=cc8224a123) | Jun 21, 2022 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [1d3eb4348d](https://linux-hardware.org/?probe=1d3eb4348d) | Jun 21, 2022 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [35bec2520a](https://linux-hardware.org/?probe=35bec2520a) | Jun 21, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [18f31eae70](https://linux-hardware.org/?probe=18f31eae70) | Jun 21, 2022 |
| MSI           | 2A9C                        | Desktop     | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| HP            | ProBook 4520s               | Notebook    | [b34f97ddb3](https://linux-hardware.org/?probe=b34f97ddb3) | Jun 19, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [1689773788](https://linux-hardware.org/?probe=1689773788) | Jun 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [9418d283c9](https://linux-hardware.org/?probe=9418d283c9) | Jun 15, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [fd2fb2f646](https://linux-hardware.org/?probe=fd2fb2f646) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [bc509480d2](https://linux-hardware.org/?probe=bc509480d2) | Jun 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| Acer          | Aspire 5552                 | Notebook    | [909cdd1a0e](https://linux-hardware.org/?probe=909cdd1a0e) | Jun 12, 2022 |
| Microsoft     | Surface Book 3              | Tablet      | [26c417012f](https://linux-hardware.org/?probe=26c417012f) | Jun 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [23fa842567](https://linux-hardware.org/?probe=23fa842567) | Jun 11, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fd1478145b](https://linux-hardware.org/?probe=fd1478145b) | Jun 11, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d9cffc5cc6](https://linux-hardware.org/?probe=d9cffc5cc6) | Jun 10, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [267db233fa](https://linux-hardware.org/?probe=267db233fa) | Jun 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [4a2f4f8cb1](https://linux-hardware.org/?probe=4a2f4f8cb1) | Jun 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [87fa4e032d](https://linux-hardware.org/?probe=87fa4e032d) | Jun 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [3531488e43](https://linux-hardware.org/?probe=3531488e43) | Jun 09, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2ac69cc327](https://linux-hardware.org/?probe=2ac69cc327) | Jun 08, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [34e884bb50](https://linux-hardware.org/?probe=34e884bb50) | Jun 08, 2022 |
| HP            | 872D                        | Desktop     | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a068a18649](https://linux-hardware.org/?probe=a068a18649) | Jun 08, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [9342f5c46b](https://linux-hardware.org/?probe=9342f5c46b) | Jun 08, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [fdba6d0041](https://linux-hardware.org/?probe=fdba6d0041) | Jun 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [bfa4e4ff74](https://linux-hardware.org/?probe=bfa4e4ff74) | Jun 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5a835b2aa6](https://linux-hardware.org/?probe=5a835b2aa6) | Jun 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [1608d3bbd6](https://linux-hardware.org/?probe=1608d3bbd6) | Jun 07, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [4924d1fa99](https://linux-hardware.org/?probe=4924d1fa99) | Jun 06, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [5ad950659b](https://linux-hardware.org/?probe=5ad950659b) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [838e0b8e42](https://linux-hardware.org/?probe=838e0b8e42) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [983f898115](https://linux-hardware.org/?probe=983f898115) | Jun 04, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [3806254bc2](https://linux-hardware.org/?probe=3806254bc2) | Jun 03, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6cb0b47bb4](https://linux-hardware.org/?probe=6cb0b47bb4) | Jun 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cb07ae6e24](https://linux-hardware.org/?probe=cb07ae6e24) | Jun 02, 2022 |
| HP            | 871A                        | Mini pc     | [5710666139](https://linux-hardware.org/?probe=5710666139) | Jun 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0faa61f3a9](https://linux-hardware.org/?probe=0faa61f3a9) | May 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [9f5906337b](https://linux-hardware.org/?probe=9f5906337b) | May 31, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [e7d02810c1](https://linux-hardware.org/?probe=e7d02810c1) | May 31, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [56929c3f8f](https://linux-hardware.org/?probe=56929c3f8f) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b86f47e828](https://linux-hardware.org/?probe=b86f47e828) | May 29, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [96cd8abf05](https://linux-hardware.org/?probe=96cd8abf05) | May 29, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [929e69f0ad](https://linux-hardware.org/?probe=929e69f0ad) | May 27, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ac41fb756c](https://linux-hardware.org/?probe=ac41fb756c) | May 26, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [8bacf91a6b](https://linux-hardware.org/?probe=8bacf91a6b) | May 25, 2022 |
| Toshiba       | TECRA A50-C                 | Notebook    | [60a580cb3b](https://linux-hardware.org/?probe=60a580cb3b) | May 25, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [aea91adcbf](https://linux-hardware.org/?probe=aea91adcbf) | May 25, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [c2eb6bb974](https://linux-hardware.org/?probe=c2eb6bb974) | May 25, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [89927eb8f5](https://linux-hardware.org/?probe=89927eb8f5) | May 25, 2022 |
| Dell          | Vostro 3480                 | Notebook    | [7c5c6aa985](https://linux-hardware.org/?probe=7c5c6aa985) | May 24, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [fa1c36e965](https://linux-hardware.org/?probe=fa1c36e965) | May 23, 2022 |
| Dell          | Precision M4400             | Notebook    | [681a684aa6](https://linux-hardware.org/?probe=681a684aa6) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [f9f00f46cc](https://linux-hardware.org/?probe=f9f00f46cc) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [1557d1e15f](https://linux-hardware.org/?probe=1557d1e15f) | May 21, 2022 |
| HP            | 8053                        | Desktop     | [53c0148d64](https://linux-hardware.org/?probe=53c0148d64) | May 20, 2022 |
| ECS           | P67H2-A3                    | Desktop     | [2bc21b9c81](https://linux-hardware.org/?probe=2bc21b9c81) | May 20, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [f87ba7a410](https://linux-hardware.org/?probe=f87ba7a410) | May 19, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [be383d0db4](https://linux-hardware.org/?probe=be383d0db4) | May 19, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [720ba0b788](https://linux-hardware.org/?probe=720ba0b788) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [76c661d512](https://linux-hardware.org/?probe=76c661d512) | May 18, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| Shuttle       | FZ87                        | Desktop     | [ce4198da70](https://linux-hardware.org/?probe=ce4198da70) | May 17, 2022 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [3c99b8d861](https://linux-hardware.org/?probe=3c99b8d861) | May 16, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| Lenovo        | ThinkPad L540 20AUA27UFR    | Notebook    | [4a6dd68139](https://linux-hardware.org/?probe=4a6dd68139) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4276CTO       | Notebook    | [28cbc6ab88](https://linux-hardware.org/?probe=28cbc6ab88) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4276CTO       | Notebook    | [142c2d12f7](https://linux-hardware.org/?probe=142c2d12f7) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [91730625e9](https://linux-hardware.org/?probe=91730625e9) | May 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d85be75174](https://linux-hardware.org/?probe=d85be75174) | May 14, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [78c64b498b](https://linux-hardware.org/?probe=78c64b498b) | May 13, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [9c3a386393](https://linux-hardware.org/?probe=9c3a386393) | May 13, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f20d2bc2b](https://linux-hardware.org/?probe=3f20d2bc2b) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [367b6b7bcb](https://linux-hardware.org/?probe=367b6b7bcb) | May 12, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [372742938a](https://linux-hardware.org/?probe=372742938a) | May 12, 2022 |
| Lenovo        | ThinkPad E595 20NFS05500    | Notebook    | [8656f72354](https://linux-hardware.org/?probe=8656f72354) | May 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cbced4dcff](https://linux-hardware.org/?probe=cbced4dcff) | May 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [73b4b6a015](https://linux-hardware.org/?probe=73b4b6a015) | May 11, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [3f587813b0](https://linux-hardware.org/?probe=3f587813b0) | May 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [41ee4b77ce](https://linux-hardware.org/?probe=41ee4b77ce) | May 10, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4f87a5b748](https://linux-hardware.org/?probe=4f87a5b748) | May 10, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [eaa10a050b](https://linux-hardware.org/?probe=eaa10a050b) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3e3acb2430](https://linux-hardware.org/?probe=3e3acb2430) | May 10, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3444835d49](https://linux-hardware.org/?probe=3444835d49) | May 10, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [24b8860aaf](https://linux-hardware.org/?probe=24b8860aaf) | May 10, 2022 |
| Google        | Droid                       | Notebook    | [35d0a5a944](https://linux-hardware.org/?probe=35d0a5a944) | May 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [e44c7da45a](https://linux-hardware.org/?probe=e44c7da45a) | May 09, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Ruckus Wir... | SCG-100                     | Desktop     | [781560aa15](https://linux-hardware.org/?probe=781560aa15) | May 09, 2022 |
| HP            | 212A                        | Desktop     | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| Positivo      | C41TB                       | Notebook    | [6ba90f69f3](https://linux-hardware.org/?probe=6ba90f69f3) | May 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b7bb0f72a0](https://linux-hardware.org/?probe=b7bb0f72a0) | May 09, 2022 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [ba03e5bb90](https://linux-hardware.org/?probe=ba03e5bb90) | May 08, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [c0fa8189f0](https://linux-hardware.org/?probe=c0fa8189f0) | May 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d5348dedec](https://linux-hardware.org/?probe=d5348dedec) | May 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [ddded0e6c3](https://linux-hardware.org/?probe=ddded0e6c3) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| MSI           | H55M-P33                    | Desktop     | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [34bd31c9f9](https://linux-hardware.org/?probe=34bd31c9f9) | May 07, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [2effde38b7](https://linux-hardware.org/?probe=2effde38b7) | May 07, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [d4e02db7d2](https://linux-hardware.org/?probe=d4e02db7d2) | May 07, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [08cbb5e9f7](https://linux-hardware.org/?probe=08cbb5e9f7) | May 07, 2022 |
| Lenovo        | G565 20071                  | Notebook    | [ef5983ea64](https://linux-hardware.org/?probe=ef5983ea64) | May 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [35cfe55dac](https://linux-hardware.org/?probe=35cfe55dac) | May 07, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Lenovo        | Yoga 720-15IKB              | Convertible | [badcc44923](https://linux-hardware.org/?probe=badcc44923) | May 07, 2022 |
| Dell          | Precision 5510              | Notebook    | [749eb5ff32](https://linux-hardware.org/?probe=749eb5ff32) | May 07, 2022 |
| ASUSTek       | P5N7A-VM                    | Desktop     | [44d168e79c](https://linux-hardware.org/?probe=44d168e79c) | May 07, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [7e14e0a766](https://linux-hardware.org/?probe=7e14e0a766) | May 07, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [047f75af38](https://linux-hardware.org/?probe=047f75af38) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| Google        | Droid                       | Notebook    | [422252faa5](https://linux-hardware.org/?probe=422252faa5) | May 07, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| Fujitsu       | CELSIUS H720                | Notebook    | [7c41d6fd4d](https://linux-hardware.org/?probe=7c41d6fd4d) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [5a08eb1919](https://linux-hardware.org/?probe=5a08eb1919) | May 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f3e4a840e8](https://linux-hardware.org/?probe=f3e4a840e8) | May 06, 2022 |
| Dell          | Precision M4700             | Notebook    | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [ad8ee15b6d](https://linux-hardware.org/?probe=ad8ee15b6d) | May 06, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [0ca81980a3](https://linux-hardware.org/?probe=0ca81980a3) | May 06, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8c1fedaa4b](https://linux-hardware.org/?probe=8c1fedaa4b) | May 06, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [e2b06a4a28](https://linux-hardware.org/?probe=e2b06a4a28) | May 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [7e44142aac](https://linux-hardware.org/?probe=7e44142aac) | May 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [8e99db77e1](https://linux-hardware.org/?probe=8e99db77e1) | May 05, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0021b7ff7f](https://linux-hardware.org/?probe=0021b7ff7f) | May 05, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [fcfb95470e](https://linux-hardware.org/?probe=fcfb95470e) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [428f653301](https://linux-hardware.org/?probe=428f653301) | May 05, 2022 |
| Timi          | Redmi G                     | Notebook    | [a2738a4d6e](https://linux-hardware.org/?probe=a2738a4d6e) | May 05, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8306d5b694](https://linux-hardware.org/?probe=8306d5b694) | May 05, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [6aedd4e799](https://linux-hardware.org/?probe=6aedd4e799) | May 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b0a2114a0f](https://linux-hardware.org/?probe=b0a2114a0f) | May 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [60d50d3190](https://linux-hardware.org/?probe=60d50d3190) | May 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fa5e301933](https://linux-hardware.org/?probe=fa5e301933) | May 05, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [53f05e9b8c](https://linux-hardware.org/?probe=53f05e9b8c) | May 05, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [29abb73f0b](https://linux-hardware.org/?probe=29abb73f0b) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| HP            | 635                         | Notebook    | [66305e8923](https://linux-hardware.org/?probe=66305e8923) | May 04, 2022 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [30ff3d44b0](https://linux-hardware.org/?probe=30ff3d44b0) | May 04, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [c3ae8f35f9](https://linux-hardware.org/?probe=c3ae8f35f9) | May 04, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [6e3858143b](https://linux-hardware.org/?probe=6e3858143b) | May 04, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [d1fb23854f](https://linux-hardware.org/?probe=d1fb23854f) | May 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [155ac0a54c](https://linux-hardware.org/?probe=155ac0a54c) | May 04, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [99d850c205](https://linux-hardware.org/?probe=99d850c205) | May 04, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [cf2375fae1](https://linux-hardware.org/?probe=cf2375fae1) | May 04, 2022 |
| Alienware     | m15 R4                      | Notebook    | [3b09d65e13](https://linux-hardware.org/?probe=3b09d65e13) | May 04, 2022 |
| ASUSTek       | VM65N-K                     | Desktop     | [9df63c1d99](https://linux-hardware.org/?probe=9df63c1d99) | May 04, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | Notebook    | [9da4b1ddc5](https://linux-hardware.org/?probe=9da4b1ddc5) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1d475f29ce](https://linux-hardware.org/?probe=1d475f29ce) | May 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [9fa64d179d](https://linux-hardware.org/?probe=9fa64d179d) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a134998640](https://linux-hardware.org/?probe=a134998640) | May 03, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [c3694433d0](https://linux-hardware.org/?probe=c3694433d0) | May 03, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [e4918450ce](https://linux-hardware.org/?probe=e4918450ce) | May 03, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [5c929eea1c](https://linux-hardware.org/?probe=5c929eea1c) | May 03, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [3d6bd2511e](https://linux-hardware.org/?probe=3d6bd2511e) | May 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Alienware     | m15 R4                      | Notebook    | [1f5f3048d6](https://linux-hardware.org/?probe=1f5f3048d6) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | Notebook    | [a00b8586b6](https://linux-hardware.org/?probe=a00b8586b6) | May 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d30c5337d6](https://linux-hardware.org/?probe=d30c5337d6) | May 02, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [046b01cae8](https://linux-hardware.org/?probe=046b01cae8) | May 02, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [90d0e8adb2](https://linux-hardware.org/?probe=90d0e8adb2) | May 02, 2022 |
| JINGSHA       | Unknown                     | Desktop     | [94dd890d71](https://linux-hardware.org/?probe=94dd890d71) | May 02, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [2b35f16b31](https://linux-hardware.org/?probe=2b35f16b31) | May 02, 2022 |
| Lenovo        | 3181 SDK0J40697 WIN 3305... | Mini pc     | [a717bd6ceb](https://linux-hardware.org/?probe=a717bd6ceb) | May 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b7709ed1c5](https://linux-hardware.org/?probe=b7709ed1c5) | May 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [510cfcefd5](https://linux-hardware.org/?probe=510cfcefd5) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [fac138a25c](https://linux-hardware.org/?probe=fac138a25c) | May 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d6bd192469](https://linux-hardware.org/?probe=d6bd192469) | May 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [ec8a9ceb87](https://linux-hardware.org/?probe=ec8a9ceb87) | May 01, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [73396d4b0b](https://linux-hardware.org/?probe=73396d4b0b) | May 01, 2022 |
| HP            | 8459                        | Desktop     | [21d5d92fda](https://linux-hardware.org/?probe=21d5d92fda) | May 01, 2022 |
| Acer          | Swift SF314-55G             | Notebook    | [1935c949a2](https://linux-hardware.org/?probe=1935c949a2) | May 01, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [dfc204b1b4](https://linux-hardware.org/?probe=dfc204b1b4) | May 01, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [a822b5b8e7](https://linux-hardware.org/?probe=a822b5b8e7) | May 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [589f58c857](https://linux-hardware.org/?probe=589f58c857) | Apr 30, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [76ee3be416](https://linux-hardware.org/?probe=76ee3be416) | Apr 30, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2065a3c2f3](https://linux-hardware.org/?probe=2065a3c2f3) | Apr 30, 2022 |
| ASUSTek       | A55M-E                      | Desktop     | [eed78fb5ab](https://linux-hardware.org/?probe=eed78fb5ab) | Apr 30, 2022 |
| Intel         | NUC9VXQNB K47179-403        | Mini pc     | [c99c3cdac6](https://linux-hardware.org/?probe=c99c3cdac6) | Apr 30, 2022 |
| JINGSHA       | Unknown                     | Desktop     | [e1b9c4eab0](https://linux-hardware.org/?probe=e1b9c4eab0) | Apr 30, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [70efbbb6c7](https://linux-hardware.org/?probe=70efbbb6c7) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [aadc641825](https://linux-hardware.org/?probe=aadc641825) | Apr 29, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ad8bbf54e3](https://linux-hardware.org/?probe=ad8bbf54e3) | Apr 29, 2022 |
| MSI           | Katana GF76 11SC            | Notebook    | [15dcec28fc](https://linux-hardware.org/?probe=15dcec28fc) | Apr 29, 2022 |
| Lenovo        | ThinkPad X390 20Q1SCDR00    | Notebook    | [41a3cac1f4](https://linux-hardware.org/?probe=41a3cac1f4) | Apr 29, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [6c498d2ce5](https://linux-hardware.org/?probe=6c498d2ce5) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [bdb2f1c4ad](https://linux-hardware.org/?probe=bdb2f1c4ad) | Apr 29, 2022 |
| Unknown       | X133                        | Notebook    | [b90d940d9e](https://linux-hardware.org/?probe=b90d940d9e) | Apr 29, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8c1bf73769](https://linux-hardware.org/?probe=8c1bf73769) | Apr 28, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [de4ae72708](https://linux-hardware.org/?probe=de4ae72708) | Apr 28, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [7cd94887fe](https://linux-hardware.org/?probe=7cd94887fe) | Apr 28, 2022 |
| HP            | 871A                        | Mini pc     | [2072675717](https://linux-hardware.org/?probe=2072675717) | Apr 28, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | Notebook    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Dell          | Latitude 5310               | Notebook    | [b4e7215e3b](https://linux-hardware.org/?probe=b4e7215e3b) | Apr 28, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [d52cf822df](https://linux-hardware.org/?probe=d52cf822df) | Apr 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6f26e0d7bd](https://linux-hardware.org/?probe=6f26e0d7bd) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| HP            | 829A                        | Mini pc     | [316fd2fd12](https://linux-hardware.org/?probe=316fd2fd12) | Apr 27, 2022 |
| System76      | Pangolin                    | Notebook    | [d326fc9a39](https://linux-hardware.org/?probe=d326fc9a39) | Apr 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [185c64fa0d](https://linux-hardware.org/?probe=185c64fa0d) | Apr 27, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [11a6c8f173](https://linux-hardware.org/?probe=11a6c8f173) | Apr 27, 2022 |
| Lenovo        | IdeaPad Y470 0855           | Notebook    | [ee26833b58](https://linux-hardware.org/?probe=ee26833b58) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [80792ef9d7](https://linux-hardware.org/?probe=80792ef9d7) | Apr 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f3c9dd19da](https://linux-hardware.org/?probe=f3c9dd19da) | Apr 26, 2022 |
| HP            | Notebook                    | Notebook    | [ec93418371](https://linux-hardware.org/?probe=ec93418371) | Apr 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [e4c1fa069d](https://linux-hardware.org/?probe=e4c1fa069d) | Apr 26, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [93c883ef59](https://linux-hardware.org/?probe=93c883ef59) | Apr 26, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [184c256d66](https://linux-hardware.org/?probe=184c256d66) | Apr 26, 2022 |
| Unknown       | 1.0                         | Desktop     | [7c17b2186e](https://linux-hardware.org/?probe=7c17b2186e) | Apr 26, 2022 |
| Biostar       | G31M+                       | Desktop     | [b756b9bc9f](https://linux-hardware.org/?probe=b756b9bc9f) | Apr 26, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [205ae74d07](https://linux-hardware.org/?probe=205ae74d07) | Apr 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6a34230d87](https://linux-hardware.org/?probe=6a34230d87) | Apr 26, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [a8626eb701](https://linux-hardware.org/?probe=a8626eb701) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [35975b7d55](https://linux-hardware.org/?probe=35975b7d55) | Apr 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [23747b18ed](https://linux-hardware.org/?probe=23747b18ed) | Apr 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b24ac490a1](https://linux-hardware.org/?probe=b24ac490a1) | Apr 25, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [3118a03e9b](https://linux-hardware.org/?probe=3118a03e9b) | Apr 25, 2022 |
| HP            | 212B                        | Desktop     | [f202f01728](https://linux-hardware.org/?probe=f202f01728) | Apr 25, 2022 |
| Google        | Bobba                       | Notebook    | [008afa9913](https://linux-hardware.org/?probe=008afa9913) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c0af99fa7e](https://linux-hardware.org/?probe=c0af99fa7e) | Apr 24, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [de010dfc55](https://linux-hardware.org/?probe=de010dfc55) | Apr 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [a1ff9cf092](https://linux-hardware.org/?probe=a1ff9cf092) | Apr 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| HP            | 821D                        | Desktop     | [6a70c646a5](https://linux-hardware.org/?probe=6a70c646a5) | Apr 24, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [ac10947315](https://linux-hardware.org/?probe=ac10947315) | Apr 24, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [438ad440d0](https://linux-hardware.org/?probe=438ad440d0) | Apr 24, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [e686789a94](https://linux-hardware.org/?probe=e686789a94) | Apr 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3f1d42f10f](https://linux-hardware.org/?probe=3f1d42f10f) | Apr 24, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [343a4c47a6](https://linux-hardware.org/?probe=343a4c47a6) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [36f385210f](https://linux-hardware.org/?probe=36f385210f) | Apr 23, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [73fe079eb6](https://linux-hardware.org/?probe=73fe079eb6) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | Notebook    | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Acer          | Swift SF514-51              | Notebook    | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [2bcb31328e](https://linux-hardware.org/?probe=2bcb31328e) | Apr 23, 2022 |
| Framework     | Laptop                      | Notebook    | [dbc00cbd42](https://linux-hardware.org/?probe=dbc00cbd42) | Apr 23, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [dcfad64d9d](https://linux-hardware.org/?probe=dcfad64d9d) | Apr 23, 2022 |
| HP            | 8053                        | Desktop     | [f214dbdf74](https://linux-hardware.org/?probe=f214dbdf74) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [ce0b6939ac](https://linux-hardware.org/?probe=ce0b6939ac) | Apr 22, 2022 |
| Google        | Bobba                       | Notebook    | [5ad66cbf53](https://linux-hardware.org/?probe=5ad66cbf53) | Apr 22, 2022 |
| HP            | 8768 A                      | Desktop     | [a939560d30](https://linux-hardware.org/?probe=a939560d30) | Apr 22, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30013... | Tablet      | [0e7e04c683](https://linux-hardware.org/?probe=0e7e04c683) | Apr 22, 2022 |
| AMI           | Cherry Trail Tablet         | Desktop     | [a2179e3116](https://linux-hardware.org/?probe=a2179e3116) | Apr 22, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [208e83a199](https://linux-hardware.org/?probe=208e83a199) | Apr 22, 2022 |
| Gateway       | SX2185                      | Desktop     | [d22bb794a1](https://linux-hardware.org/?probe=d22bb794a1) | Apr 22, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Dell          | 06NWYK A00                  | Desktop     | [e67d861aba](https://linux-hardware.org/?probe=e67d861aba) | Apr 22, 2022 |
| Sony          | VPCEB3PGX                   | Notebook    | [1771623608](https://linux-hardware.org/?probe=1771623608) | Apr 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [bb2195b690](https://linux-hardware.org/?probe=bb2195b690) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [074f40a67b](https://linux-hardware.org/?probe=074f40a67b) | Apr 21, 2022 |
| Timi          | TM1701                      | Notebook    | [dba97f1875](https://linux-hardware.org/?probe=dba97f1875) | Apr 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [8034b9ae8c](https://linux-hardware.org/?probe=8034b9ae8c) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [664867989b](https://linux-hardware.org/?probe=664867989b) | Apr 21, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [5f2f4d715e](https://linux-hardware.org/?probe=5f2f4d715e) | Apr 21, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [aa004d1627](https://linux-hardware.org/?probe=aa004d1627) | Apr 21, 2022 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [93a5ff0ad9](https://linux-hardware.org/?probe=93a5ff0ad9) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [84f6645ca5](https://linux-hardware.org/?probe=84f6645ca5) | Apr 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [aa8173a46a](https://linux-hardware.org/?probe=aa8173a46a) | Apr 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4daf24b44d](https://linux-hardware.org/?probe=4daf24b44d) | Apr 20, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ed27d7c06d](https://linux-hardware.org/?probe=ed27d7c06d) | Apr 20, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f32b27ae86](https://linux-hardware.org/?probe=f32b27ae86) | Apr 20, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [05daf3f64b](https://linux-hardware.org/?probe=05daf3f64b) | Apr 20, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [7969fc986b](https://linux-hardware.org/?probe=7969fc986b) | Apr 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3af8357ab9](https://linux-hardware.org/?probe=3af8357ab9) | Apr 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a9126e3886](https://linux-hardware.org/?probe=a9126e3886) | Apr 19, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [d359794b2f](https://linux-hardware.org/?probe=d359794b2f) | Apr 19, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e53d4286d](https://linux-hardware.org/?probe=0e53d4286d) | Apr 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [0f924d06d6](https://linux-hardware.org/?probe=0f924d06d6) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [4fe85803b7](https://linux-hardware.org/?probe=4fe85803b7) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | Notebook    | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [cb11a3f634](https://linux-hardware.org/?probe=cb11a3f634) | Apr 19, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [7f35172610](https://linux-hardware.org/?probe=7f35172610) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [fa995794ba](https://linux-hardware.org/?probe=fa995794ba) | Apr 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [068741773e](https://linux-hardware.org/?probe=068741773e) | Apr 18, 2022 |
| ASUSTek       | G551JW                      | Notebook    | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| ASUSTek       | WS C422 SAGE/10G            | Desktop     | [27db6c7db6](https://linux-hardware.org/?probe=27db6c7db6) | Apr 18, 2022 |
| Timi          | TM1604                      | Notebook    | [2c182df836](https://linux-hardware.org/?probe=2c182df836) | Apr 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [95744e46d1](https://linux-hardware.org/?probe=95744e46d1) | Apr 18, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [2369e789c7](https://linux-hardware.org/?probe=2369e789c7) | Apr 18, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [08f9942632](https://linux-hardware.org/?probe=08f9942632) | Apr 18, 2022 |
| Dell          | Latitude E5520              | Notebook    | [1b428165cf](https://linux-hardware.org/?probe=1b428165cf) | Apr 18, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | Notebook    | [db5f56be25](https://linux-hardware.org/?probe=db5f56be25) | Apr 18, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [f7888cc252](https://linux-hardware.org/?probe=f7888cc252) | Apr 18, 2022 |
| HP            | Spectre Notebook            | Notebook    | [42d4ceac84](https://linux-hardware.org/?probe=42d4ceac84) | Apr 18, 2022 |
| ECS           | H310H5-M2                   | Desktop     | [653fae2086](https://linux-hardware.org/?probe=653fae2086) | Apr 18, 2022 |
| ASRock        | Z87 Extreme6                | Desktop     | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cc4a1b8b6f](https://linux-hardware.org/?probe=cc4a1b8b6f) | Apr 17, 2022 |
| Intel         | DH61BE AAG14062-206         | Desktop     | [4816f51374](https://linux-hardware.org/?probe=4816f51374) | Apr 17, 2022 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [42836ca452](https://linux-hardware.org/?probe=42836ca452) | Apr 17, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [647f782e9f](https://linux-hardware.org/?probe=647f782e9f) | Apr 17, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [4dbd302f8c](https://linux-hardware.org/?probe=4dbd302f8c) | Apr 17, 2022 |
| Lenovo        | Yoga 720-15IKB              | Convertible | [42b7bd7f75](https://linux-hardware.org/?probe=42b7bd7f75) | Apr 16, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | Notebook    | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Positivo      | H14BU08                     | Notebook    | [43d44df3d2](https://linux-hardware.org/?probe=43d44df3d2) | Apr 16, 2022 |
| Alienware     | Area-51m R2                 | Notebook    | [e6a7b0ef42](https://linux-hardware.org/?probe=e6a7b0ef42) | Apr 16, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [5f7dafa5b9](https://linux-hardware.org/?probe=5f7dafa5b9) | Apr 16, 2022 |
| Lenovo        | ThinkPad T490 20N3S19L00    | Notebook    | [5812cc4868](https://linux-hardware.org/?probe=5812cc4868) | Apr 16, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [d0e37d8bc1](https://linux-hardware.org/?probe=d0e37d8bc1) | Apr 16, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [69fdb71a72](https://linux-hardware.org/?probe=69fdb71a72) | Apr 16, 2022 |
| Dell          | 0DN075                      | Desktop     | [05bd1b50f1](https://linux-hardware.org/?probe=05bd1b50f1) | Apr 16, 2022 |
| Acer          | ConceptD CC314-72           | Convertible | [07f3c16543](https://linux-hardware.org/?probe=07f3c16543) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b07e7e9974](https://linux-hardware.org/?probe=b07e7e9974) | Apr 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| Google        | Squawks                     | Notebook    | [a6dc68bba1](https://linux-hardware.org/?probe=a6dc68bba1) | Apr 15, 2022 |
| Unknown       | HX90                        | Desktop     | [a9b1d5a579](https://linux-hardware.org/?probe=a9b1d5a579) | Apr 15, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [aa36281de8](https://linux-hardware.org/?probe=aa36281de8) | Apr 15, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [a5b036d6a3](https://linux-hardware.org/?probe=a5b036d6a3) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [c14702d147](https://linux-hardware.org/?probe=c14702d147) | Apr 15, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [fc39ac9f46](https://linux-hardware.org/?probe=fc39ac9f46) | Apr 15, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e9969def2d](https://linux-hardware.org/?probe=e9969def2d) | Apr 15, 2022 |
| Biostar       | G31M+                       | Desktop     | [bbc349a405](https://linux-hardware.org/?probe=bbc349a405) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | Desktop     | [76a80df275](https://linux-hardware.org/?probe=76a80df275) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [edca3eae97](https://linux-hardware.org/?probe=edca3eae97) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | Desktop     | [74b8687993](https://linux-hardware.org/?probe=74b8687993) | Apr 15, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [dcae73146f](https://linux-hardware.org/?probe=dcae73146f) | Apr 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0646755403](https://linux-hardware.org/?probe=0646755403) | Apr 15, 2022 |
| Getac         | S410                        | Notebook    | [a0ec8cd50e](https://linux-hardware.org/?probe=a0ec8cd50e) | Apr 14, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [832620cf67](https://linux-hardware.org/?probe=832620cf67) | Apr 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d113301081](https://linux-hardware.org/?probe=d113301081) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [a5950266d1](https://linux-hardware.org/?probe=a5950266d1) | Apr 14, 2022 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [72b9c04a51](https://linux-hardware.org/?probe=72b9c04a51) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0000... | Notebook    | [50325a2b5c](https://linux-hardware.org/?probe=50325a2b5c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [cc1fade012](https://linux-hardware.org/?probe=cc1fade012) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [8734154fb6](https://linux-hardware.org/?probe=8734154fb6) | Apr 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5bdba5a921](https://linux-hardware.org/?probe=5bdba5a921) | Apr 14, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [80b368187a](https://linux-hardware.org/?probe=80b368187a) | Apr 14, 2022 |
| MSI           | B250M MORTAR                | Desktop     | [8bf9715804](https://linux-hardware.org/?probe=8bf9715804) | Apr 14, 2022 |
| ASUSTek       | ROG Strix G713QC_G713QC     | Notebook    | [c54b458c01](https://linux-hardware.org/?probe=c54b458c01) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [45b5664eb1](https://linux-hardware.org/?probe=45b5664eb1) | Apr 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2decdc1731](https://linux-hardware.org/?probe=2decdc1731) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Lenovo        | ThinkPad P52 20MAS17228     | Notebook    | [dac73320e9](https://linux-hardware.org/?probe=dac73320e9) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [0276364302](https://linux-hardware.org/?probe=0276364302) | Apr 14, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [43aa5ccd47](https://linux-hardware.org/?probe=43aa5ccd47) | Apr 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [3b66db6997](https://linux-hardware.org/?probe=3b66db6997) | Apr 14, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [84815ec94e](https://linux-hardware.org/?probe=84815ec94e) | Apr 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a5c9b7fc78](https://linux-hardware.org/?probe=a5c9b7fc78) | Apr 14, 2022 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [77d75fd5b2](https://linux-hardware.org/?probe=77d75fd5b2) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [89de41a490](https://linux-hardware.org/?probe=89de41a490) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7e080e5205](https://linux-hardware.org/?probe=7e080e5205) | Apr 14, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [8ebb61ef39](https://linux-hardware.org/?probe=8ebb61ef39) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [5ef7e630fa](https://linux-hardware.org/?probe=5ef7e630fa) | Apr 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [cf0c239670](https://linux-hardware.org/?probe=cf0c239670) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9af096ef7f](https://linux-hardware.org/?probe=9af096ef7f) | Apr 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7e6cb72711](https://linux-hardware.org/?probe=7e6cb72711) | Apr 13, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [20ed59527a](https://linux-hardware.org/?probe=20ed59527a) | Apr 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0dddcf5626](https://linux-hardware.org/?probe=0dddcf5626) | Apr 13, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [9f5a2049e3](https://linux-hardware.org/?probe=9f5a2049e3) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f365986dfc](https://linux-hardware.org/?probe=f365986dfc) | Apr 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [20f315a2e7](https://linux-hardware.org/?probe=20f315a2e7) | Apr 13, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [dcca838772](https://linux-hardware.org/?probe=dcca838772) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [332355ddfa](https://linux-hardware.org/?probe=332355ddfa) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [53ba287837](https://linux-hardware.org/?probe=53ba287837) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6ac57575d9](https://linux-hardware.org/?probe=6ac57575d9) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [70b154b039](https://linux-hardware.org/?probe=70b154b039) | Apr 13, 2022 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [6dc94a82ab](https://linux-hardware.org/?probe=6dc94a82ab) | Apr 13, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [234fd15d56](https://linux-hardware.org/?probe=234fd15d56) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| HP            | 829A                        | Mini pc     | [82d14c37b5](https://linux-hardware.org/?probe=82d14c37b5) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| Framework     | Laptop                      | Notebook    | [6de996aa1e](https://linux-hardware.org/?probe=6de996aa1e) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [dc6799506a](https://linux-hardware.org/?probe=dc6799506a) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | Notebook    | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [0c40d42b4a](https://linux-hardware.org/?probe=0c40d42b4a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | X75VCP                      | Notebook    | [21e0b65e1b](https://linux-hardware.org/?probe=21e0b65e1b) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [46ce27bfa6](https://linux-hardware.org/?probe=46ce27bfa6) | Apr 13, 2022 |
| HP            | 805D                        | Desktop     | [56634964fb](https://linux-hardware.org/?probe=56634964fb) | Apr 13, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [e79417a89e](https://linux-hardware.org/?probe=e79417a89e) | Apr 13, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [8dd3b0dfb9](https://linux-hardware.org/?probe=8dd3b0dfb9) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [3385b17dd8](https://linux-hardware.org/?probe=3385b17dd8) | Apr 13, 2022 |
| Dell          | Latitude E6530              | Notebook    | [597013072b](https://linux-hardware.org/?probe=597013072b) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [0d300b2fc3](https://linux-hardware.org/?probe=0d300b2fc3) | Apr 12, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [3656e85663](https://linux-hardware.org/?probe=3656e85663) | Apr 12, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [52828f419f](https://linux-hardware.org/?probe=52828f419f) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d7659bd74](https://linux-hardware.org/?probe=4d7659bd74) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [eccb5e26fc](https://linux-hardware.org/?probe=eccb5e26fc) | Apr 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [be0d616e99](https://linux-hardware.org/?probe=be0d616e99) | Apr 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [e43f2609cc](https://linux-hardware.org/?probe=e43f2609cc) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M91P 7034A2U    | Desktop     | [a5b9a57a64](https://linux-hardware.org/?probe=a5b9a57a64) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [8879fa758a](https://linux-hardware.org/?probe=8879fa758a) | Apr 11, 2022 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [938b601307](https://linux-hardware.org/?probe=938b601307) | Apr 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [683c394458](https://linux-hardware.org/?probe=683c394458) | Apr 11, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [285b194f70](https://linux-hardware.org/?probe=285b194f70) | Apr 11, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [153f53dadd](https://linux-hardware.org/?probe=153f53dadd) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [edebd20c8e](https://linux-hardware.org/?probe=edebd20c8e) | Apr 11, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [b6c1c28521](https://linux-hardware.org/?probe=b6c1c28521) | Apr 11, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [40dd641006](https://linux-hardware.org/?probe=40dd641006) | Apr 10, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [2e80786e39](https://linux-hardware.org/?probe=2e80786e39) | Apr 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f69f54968e](https://linux-hardware.org/?probe=f69f54968e) | Apr 10, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Dell          | 0DN075                      | Desktop     | [043e18273e](https://linux-hardware.org/?probe=043e18273e) | Apr 10, 2022 |
| Dell          | 0DN075                      | Desktop     | [250db280d3](https://linux-hardware.org/?probe=250db280d3) | Apr 10, 2022 |
| Dell          | 0DN075                      | Desktop     | [759d8d5556](https://linux-hardware.org/?probe=759d8d5556) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| ASUSTek       | X405UQ                      | Notebook    | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [1638359c7b](https://linux-hardware.org/?probe=1638359c7b) | Apr 10, 2022 |
| ASRock        | Z270 Professional Gaming... | Desktop     | [9129317f19](https://linux-hardware.org/?probe=9129317f19) | Apr 10, 2022 |
| Dell          | Latitude 7480               | Notebook    | [b235ce5f92](https://linux-hardware.org/?probe=b235ce5f92) | Apr 10, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [82db7996ff](https://linux-hardware.org/?probe=82db7996ff) | Apr 09, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [703a4e77a3](https://linux-hardware.org/?probe=703a4e77a3) | Apr 09, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f8c3b429a2](https://linux-hardware.org/?probe=f8c3b429a2) | Apr 09, 2022 |
| Dell          | Latitude 7275               | Notebook    | [fe36710853](https://linux-hardware.org/?probe=fe36710853) | Apr 09, 2022 |
| Alienware     | 0J560M A00                  | Desktop     | [a0b422480a](https://linux-hardware.org/?probe=a0b422480a) | Apr 09, 2022 |
| Dell          | Latitude 7275               | Notebook    | [e6bc45d8d9](https://linux-hardware.org/?probe=e6bc45d8d9) | Apr 09, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [487adfbcb9](https://linux-hardware.org/?probe=487adfbcb9) | Apr 09, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [7b3a49ec3c](https://linux-hardware.org/?probe=7b3a49ec3c) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [eebc86ccbe](https://linux-hardware.org/?probe=eebc86ccbe) | Apr 09, 2022 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [e6281eef7f](https://linux-hardware.org/?probe=e6281eef7f) | Apr 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [3ffa339c32](https://linux-hardware.org/?probe=3ffa339c32) | Apr 09, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [9dbe75c090](https://linux-hardware.org/?probe=9dbe75c090) | Apr 09, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [e76eb71b7f](https://linux-hardware.org/?probe=e76eb71b7f) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [919af587bb](https://linux-hardware.org/?probe=919af587bb) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [3b16991947](https://linux-hardware.org/?probe=3b16991947) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [03940a7514](https://linux-hardware.org/?probe=03940a7514) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d42f8f3535](https://linux-hardware.org/?probe=d42f8f3535) | Apr 08, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [afd87f36b2](https://linux-hardware.org/?probe=afd87f36b2) | Apr 08, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [cdf784520e](https://linux-hardware.org/?probe=cdf784520e) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7438fcdda2](https://linux-hardware.org/?probe=7438fcdda2) | Apr 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7305c4d766](https://linux-hardware.org/?probe=7305c4d766) | Apr 08, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [f812d0803f](https://linux-hardware.org/?probe=f812d0803f) | Apr 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [10458d0000](https://linux-hardware.org/?probe=10458d0000) | Apr 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| ASUSTek       | N551JB                      | Notebook    | [edbf102771](https://linux-hardware.org/?probe=edbf102771) | Apr 08, 2022 |
| HP            | ProBook 445 G7 Notebook ... | Notebook    | [0d15f8a702](https://linux-hardware.org/?probe=0d15f8a702) | Apr 07, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a99419647f](https://linux-hardware.org/?probe=a99419647f) | Apr 07, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [4a53e94722](https://linux-hardware.org/?probe=4a53e94722) | Apr 07, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| ASUSTek       | N551JB                      | Notebook    | [e1f0b15197](https://linux-hardware.org/?probe=e1f0b15197) | Apr 07, 2022 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [ef1693c88f](https://linux-hardware.org/?probe=ef1693c88f) | Apr 07, 2022 |
| ASUSTek       | GL553VW                     | Notebook    | [779c7e3858](https://linux-hardware.org/?probe=779c7e3858) | Apr 07, 2022 |
| Framework     | Laptop                      | Notebook    | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [158e261517](https://linux-hardware.org/?probe=158e261517) | Apr 07, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [6cd80e7357](https://linux-hardware.org/?probe=6cd80e7357) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [e50ab269b2](https://linux-hardware.org/?probe=e50ab269b2) | Apr 06, 2022 |
| Dell          | Latitude 3520               | Notebook    | [1ec7dedd4c](https://linux-hardware.org/?probe=1ec7dedd4c) | Apr 06, 2022 |
| Dell          | Precision 7550              | Notebook    | [89df3f1bfd](https://linux-hardware.org/?probe=89df3f1bfd) | Apr 06, 2022 |
| Intel         | Shark Bay Client platfor... | Notebook    | [8b1a97afe3](https://linux-hardware.org/?probe=8b1a97afe3) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [56244d6def](https://linux-hardware.org/?probe=56244d6def) | Apr 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [a668b151a3](https://linux-hardware.org/?probe=a668b151a3) | Apr 06, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [05e3166f60](https://linux-hardware.org/?probe=05e3166f60) | Apr 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Notebook    | [a6c37e7ee4](https://linux-hardware.org/?probe=a6c37e7ee4) | Apr 06, 2022 |
| Dell          | G3 3579                     | Notebook    | [9994b24cef](https://linux-hardware.org/?probe=9994b24cef) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [e20e2247c0](https://linux-hardware.org/?probe=e20e2247c0) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [dbb3f589ad](https://linux-hardware.org/?probe=dbb3f589ad) | Apr 06, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b1050b51ec](https://linux-hardware.org/?probe=b1050b51ec) | Apr 05, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [13aafa70b2](https://linux-hardware.org/?probe=13aafa70b2) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [a4e35bec86](https://linux-hardware.org/?probe=a4e35bec86) | Apr 05, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [a2dd193a18](https://linux-hardware.org/?probe=a2dd193a18) | Apr 05, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [219ae7c834](https://linux-hardware.org/?probe=219ae7c834) | Apr 05, 2022 |
| HP            | 1494                        | Desktop     | [5d81c1dd3c](https://linux-hardware.org/?probe=5d81c1dd3c) | Apr 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [00da75f071](https://linux-hardware.org/?probe=00da75f071) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [770088302a](https://linux-hardware.org/?probe=770088302a) | Apr 05, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [8b13f1e4ca](https://linux-hardware.org/?probe=8b13f1e4ca) | Apr 05, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [18e1fc86be](https://linux-hardware.org/?probe=18e1fc86be) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [5c28fb1391](https://linux-hardware.org/?probe=5c28fb1391) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [92130ffb61](https://linux-hardware.org/?probe=92130ffb61) | Apr 04, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [bdd5a36f62](https://linux-hardware.org/?probe=bdd5a36f62) | Apr 04, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [1c4423ca19](https://linux-hardware.org/?probe=1c4423ca19) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| ASUSTek       | UX301LAA                    | Notebook    | [1c631fdb63](https://linux-hardware.org/?probe=1c631fdb63) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| Sony          | VPCEB4L1E                   | Notebook    | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| ASUSTek       | A55BM-K                     | Desktop     | [c0832d15d0](https://linux-hardware.org/?probe=c0832d15d0) | Apr 03, 2022 |
| ASRock        | C2750D4I                    | Desktop     | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [ec65d243a5](https://linux-hardware.org/?probe=ec65d243a5) | Apr 03, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0fc592dd2c](https://linux-hardware.org/?probe=0fc592dd2c) | Apr 03, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [67b9d43387](https://linux-hardware.org/?probe=67b9d43387) | Apr 03, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e826deade2](https://linux-hardware.org/?probe=e826deade2) | Apr 03, 2022 |
| Framework     | Laptop                      | Notebook    | [a0e35b1871](https://linux-hardware.org/?probe=a0e35b1871) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | Notebook    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| Dell          | Precision 5530              | Notebook    | [96b22b6124](https://linux-hardware.org/?probe=96b22b6124) | Apr 03, 2022 |
| MSI           | H81M-E34                    | Desktop     | [fad24f9efc](https://linux-hardware.org/?probe=fad24f9efc) | Apr 03, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [d187a0de09](https://linux-hardware.org/?probe=d187a0de09) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5dcb0a1847](https://linux-hardware.org/?probe=5dcb0a1847) | Apr 02, 2022 |
| HP            | 871A                        | Mini pc     | [b71bc66f21](https://linux-hardware.org/?probe=b71bc66f21) | Apr 02, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [446d4b4c59](https://linux-hardware.org/?probe=446d4b4c59) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M91p 7033HS8    | Desktop     | [0fab8669e0](https://linux-hardware.org/?probe=0fab8669e0) | Apr 02, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [8bd2b269ff](https://linux-hardware.org/?probe=8bd2b269ff) | Apr 02, 2022 |
| Dell          | Latitude 5500               | Notebook    | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| Timi          | TM1612                      | Notebook    | [7eb83bb23a](https://linux-hardware.org/?probe=7eb83bb23a) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [3c89c6c9d8](https://linux-hardware.org/?probe=3c89c6c9d8) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3bcc5c9790](https://linux-hardware.org/?probe=3bcc5c9790) | Apr 02, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [11153fc9f1](https://linux-hardware.org/?probe=11153fc9f1) | Apr 02, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [6b2cbca4b2](https://linux-hardware.org/?probe=6b2cbca4b2) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [055b15c7a9](https://linux-hardware.org/?probe=055b15c7a9) | Apr 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4696339b4e](https://linux-hardware.org/?probe=4696339b4e) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f30982f3ac](https://linux-hardware.org/?probe=f30982f3ac) | Apr 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [03812d6355](https://linux-hardware.org/?probe=03812d6355) | Apr 01, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | Notebook    | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | Notebook    | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | Notebook    | [97505bf353](https://linux-hardware.org/?probe=97505bf353) | Apr 01, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [d18cd45522](https://linux-hardware.org/?probe=d18cd45522) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [ec162ebae4](https://linux-hardware.org/?probe=ec162ebae4) | Apr 01, 2022 |
| Gigabyte      | B460M D3H                   | Desktop     | [7c159eefd8](https://linux-hardware.org/?probe=7c159eefd8) | Apr 01, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [81e7639a72](https://linux-hardware.org/?probe=81e7639a72) | Apr 01, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b81a77ca49](https://linux-hardware.org/?probe=b81a77ca49) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [06b3aacb51](https://linux-hardware.org/?probe=06b3aacb51) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [913c396bde](https://linux-hardware.org/?probe=913c396bde) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [6774f9f9c8](https://linux-hardware.org/?probe=6774f9f9c8) | Apr 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [17eda00f3d](https://linux-hardware.org/?probe=17eda00f3d) | Apr 01, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cb4611f386](https://linux-hardware.org/?probe=cb4611f386) | Apr 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [d4691ddfac](https://linux-hardware.org/?probe=d4691ddfac) | Apr 01, 2022 |
| HP            | Laptop 17z-ca300            | Notebook    | [726d1e7b0f](https://linux-hardware.org/?probe=726d1e7b0f) | Mar 31, 2022 |
| MSI           | B85-G43 GAMING              | Desktop     | [70574c396b](https://linux-hardware.org/?probe=70574c396b) | Mar 31, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [99276b473e](https://linux-hardware.org/?probe=99276b473e) | Mar 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [c01344bd43](https://linux-hardware.org/?probe=c01344bd43) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b08e7d8589](https://linux-hardware.org/?probe=b08e7d8589) | Mar 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a18360bae8](https://linux-hardware.org/?probe=a18360bae8) | Mar 31, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [6ab27f6f88](https://linux-hardware.org/?probe=6ab27f6f88) | Mar 31, 2022 |
| ASUSTek       | M5A97 EVO                   | Desktop     | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | Notebook    | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | Notebook    | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [4ba34b9b1f](https://linux-hardware.org/?probe=4ba34b9b1f) | Mar 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [43e45df9f5](https://linux-hardware.org/?probe=43e45df9f5) | Mar 30, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [cd333e5720](https://linux-hardware.org/?probe=cd333e5720) | Mar 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3cd8bdb60c](https://linux-hardware.org/?probe=3cd8bdb60c) | Mar 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [db3d70e53a](https://linux-hardware.org/?probe=db3d70e53a) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [3a64f14cc4](https://linux-hardware.org/?probe=3a64f14cc4) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [dd51589f73](https://linux-hardware.org/?probe=dd51589f73) | Mar 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0f18e7b54b](https://linux-hardware.org/?probe=0f18e7b54b) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [2491111c9d](https://linux-hardware.org/?probe=2491111c9d) | Mar 30, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [fd1759c341](https://linux-hardware.org/?probe=fd1759c341) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [88b64a12df](https://linux-hardware.org/?probe=88b64a12df) | Mar 29, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [535acf7c14](https://linux-hardware.org/?probe=535acf7c14) | Mar 29, 2022 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | Notebook    | [ff622b910d](https://linux-hardware.org/?probe=ff622b910d) | Mar 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [18a5e10a64](https://linux-hardware.org/?probe=18a5e10a64) | Mar 28, 2022 |
| HP            | 82A2                        | Desktop     | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c1384b9063](https://linux-hardware.org/?probe=c1384b9063) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9c5efbe2a7](https://linux-hardware.org/?probe=9c5efbe2a7) | Mar 28, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ac807c9324](https://linux-hardware.org/?probe=ac807c9324) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [c5d26f3dc7](https://linux-hardware.org/?probe=c5d26f3dc7) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [53da8c0cdf](https://linux-hardware.org/?probe=53da8c0cdf) | Mar 27, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [c472ae03f6](https://linux-hardware.org/?probe=c472ae03f6) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | Desktop     | [9c0577803f](https://linux-hardware.org/?probe=9c0577803f) | Mar 27, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | Desktop     | [a296d4597c](https://linux-hardware.org/?probe=a296d4597c) | Mar 27, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [084d60ff3b](https://linux-hardware.org/?probe=084d60ff3b) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [d214df0c57](https://linux-hardware.org/?probe=d214df0c57) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8252c302e2](https://linux-hardware.org/?probe=8252c302e2) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [dc5e0a376b](https://linux-hardware.org/?probe=dc5e0a376b) | Mar 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91b7f328b1](https://linux-hardware.org/?probe=91b7f328b1) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [48ce1c3bd8](https://linux-hardware.org/?probe=48ce1c3bd8) | Mar 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [029e0a790e](https://linux-hardware.org/?probe=029e0a790e) | Mar 26, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c4b697295e](https://linux-hardware.org/?probe=c4b697295e) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b47822d246](https://linux-hardware.org/?probe=b47822d246) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [a68ce8edaf](https://linux-hardware.org/?probe=a68ce8edaf) | Mar 26, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [90299bc344](https://linux-hardware.org/?probe=90299bc344) | Mar 26, 2022 |
| Alienware     | m15 R6                      | Notebook    | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | Notebook    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [1d0229f697](https://linux-hardware.org/?probe=1d0229f697) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | Notebook    | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [da358bbf5c](https://linux-hardware.org/?probe=da358bbf5c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [4a6b3d619c](https://linux-hardware.org/?probe=4a6b3d619c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [7d1fa138d0](https://linux-hardware.org/?probe=7d1fa138d0) | Mar 25, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [911fd95d9f](https://linux-hardware.org/?probe=911fd95d9f) | Mar 25, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2424807acb](https://linux-hardware.org/?probe=2424807acb) | Mar 24, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d6d6620190](https://linux-hardware.org/?probe=d6d6620190) | Mar 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [7c80283af3](https://linux-hardware.org/?probe=7c80283af3) | Mar 24, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25d5cba9dc](https://linux-hardware.org/?probe=25d5cba9dc) | Mar 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c10b664e4e](https://linux-hardware.org/?probe=c10b664e4e) | Mar 24, 2022 |
| Intel         | DH61BE AAG14062-206         | Desktop     | [08a352b1d2](https://linux-hardware.org/?probe=08a352b1d2) | Mar 24, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [52bc15cdf9](https://linux-hardware.org/?probe=52bc15cdf9) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6136cfa920](https://linux-hardware.org/?probe=6136cfa920) | Mar 24, 2022 |
| System76      | Gazelle                     | Notebook    | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Dell          | 08NG84 A01                  | All in one  | [8e2101ed83](https://linux-hardware.org/?probe=8e2101ed83) | Mar 24, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [337b027d96](https://linux-hardware.org/?probe=337b027d96) | Mar 23, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [440e4d8b48](https://linux-hardware.org/?probe=440e4d8b48) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55730a4af8](https://linux-hardware.org/?probe=55730a4af8) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASUSTek       | X75VCP                      | Notebook    | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [86c831ce79](https://linux-hardware.org/?probe=86c831ce79) | Mar 23, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [3024cce066](https://linux-hardware.org/?probe=3024cce066) | Mar 23, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [6285900fd7](https://linux-hardware.org/?probe=6285900fd7) | Mar 22, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [f140780c32](https://linux-hardware.org/?probe=f140780c32) | Mar 22, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [6fc4d08da4](https://linux-hardware.org/?probe=6fc4d08da4) | Mar 22, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [6934e641a4](https://linux-hardware.org/?probe=6934e641a4) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a1a39d622b](https://linux-hardware.org/?probe=a1a39d622b) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | Desktop     | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [70a784f09c](https://linux-hardware.org/?probe=70a784f09c) | Mar 21, 2022 |
| Lenovo        | 3111 NOK                    | Mini pc     | [fe298dc766](https://linux-hardware.org/?probe=fe298dc766) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [0f3a8eb166](https://linux-hardware.org/?probe=0f3a8eb166) | Mar 21, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [279bb03666](https://linux-hardware.org/?probe=279bb03666) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [a5937e694a](https://linux-hardware.org/?probe=a5937e694a) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | Notebook    | [40767d2545](https://linux-hardware.org/?probe=40767d2545) | Mar 20, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [bde47f2d75](https://linux-hardware.org/?probe=bde47f2d75) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [ebc42c3206](https://linux-hardware.org/?probe=ebc42c3206) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | Notebook    | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | Notebook    | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [3c40b29b63](https://linux-hardware.org/?probe=3c40b29b63) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [baae82b163](https://linux-hardware.org/?probe=baae82b163) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [ce6b8e3716](https://linux-hardware.org/?probe=ce6b8e3716) | Mar 19, 2022 |
| HP            | 84EF 01100                  | All in one  | [be542cf367](https://linux-hardware.org/?probe=be542cf367) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Acer          | Aspire A317-51G             | Notebook    | [f2a7cadaff](https://linux-hardware.org/?probe=f2a7cadaff) | Mar 18, 2022 |
| Toshiba       | Satellite C855-12R          | Notebook    | [96554352c8](https://linux-hardware.org/?probe=96554352c8) | Mar 18, 2022 |
| Lenovo        | ThinkPad P53 20QN000HGE     | Notebook    | [db71f4d011](https://linux-hardware.org/?probe=db71f4d011) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [dc3b3ab391](https://linux-hardware.org/?probe=dc3b3ab391) | Mar 18, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c869642fe9](https://linux-hardware.org/?probe=c869642fe9) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e97e686e5e](https://linux-hardware.org/?probe=e97e686e5e) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [b928348a02](https://linux-hardware.org/?probe=b928348a02) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [c6b6cc1f1d](https://linux-hardware.org/?probe=c6b6cc1f1d) | Mar 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [b5aeb18001](https://linux-hardware.org/?probe=b5aeb18001) | Mar 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f7eb058e61](https://linux-hardware.org/?probe=f7eb058e61) | Mar 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [16ced37ed8](https://linux-hardware.org/?probe=16ced37ed8) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 428767U       | Notebook    | [380351014b](https://linux-hardware.org/?probe=380351014b) | Mar 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a3444ce232](https://linux-hardware.org/?probe=a3444ce232) | Mar 16, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [d5afbde22c](https://linux-hardware.org/?probe=d5afbde22c) | Mar 16, 2022 |
| HP            | 826A A01                    | All in one  | [e7df5fb705](https://linux-hardware.org/?probe=e7df5fb705) | Mar 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | Notebook    | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [75a7099e71](https://linux-hardware.org/?probe=75a7099e71) | Mar 15, 2022 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [66bda745cd](https://linux-hardware.org/?probe=66bda745cd) | Mar 15, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [dc4e443fca](https://linux-hardware.org/?probe=dc4e443fca) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [affad66907](https://linux-hardware.org/?probe=affad66907) | Mar 14, 2022 |
| Acer          | Calpella                    | Notebook    | [038e7b15ee](https://linux-hardware.org/?probe=038e7b15ee) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [79744a34f1](https://linux-hardware.org/?probe=79744a34f1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | ProBook 6465b               | Notebook    | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [00edfc8f9b](https://linux-hardware.org/?probe=00edfc8f9b) | Mar 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [b400e8a455](https://linux-hardware.org/?probe=b400e8a455) | Mar 14, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [5cdaea7c5a](https://linux-hardware.org/?probe=5cdaea7c5a) | Mar 14, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [72a6f7ef1b](https://linux-hardware.org/?probe=72a6f7ef1b) | Mar 13, 2022 |
| Dell          | Vostro 1014                 | Notebook    | [8df761ef60](https://linux-hardware.org/?probe=8df761ef60) | Mar 13, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [9cce5830b5](https://linux-hardware.org/?probe=9cce5830b5) | Mar 13, 2022 |
| Positivo      | N1250                       | Notebook    | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [739b74effe](https://linux-hardware.org/?probe=739b74effe) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [79211f85fd](https://linux-hardware.org/?probe=79211f85fd) | Mar 13, 2022 |
| MSI           | B85M-E45 2015-08-19         | Desktop     | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| Intel         | NUC7i3DNB J57625-513        | Mini pc     | [d23d5b7f32](https://linux-hardware.org/?probe=d23d5b7f32) | Mar 13, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5d90a423a](https://linux-hardware.org/?probe=d5d90a423a) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6e9075eebf](https://linux-hardware.org/?probe=6e9075eebf) | Mar 13, 2022 |
| Dell          | Latitude 5511               | Notebook    | [ec15afa8e7](https://linux-hardware.org/?probe=ec15afa8e7) | Mar 12, 2022 |
| Dell          | Precision 5540              | Notebook    | [99b2435d7a](https://linux-hardware.org/?probe=99b2435d7a) | Mar 12, 2022 |
| MSI           | 2A9C                        | Desktop     | [99c139f47b](https://linux-hardware.org/?probe=99c139f47b) | Mar 12, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2bb86501da](https://linux-hardware.org/?probe=2bb86501da) | Mar 12, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [276b115350](https://linux-hardware.org/?probe=276b115350) | Mar 12, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [98fd2cf2c6](https://linux-hardware.org/?probe=98fd2cf2c6) | Mar 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6eca88e86f](https://linux-hardware.org/?probe=6eca88e86f) | Mar 12, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [cbfe261386](https://linux-hardware.org/?probe=cbfe261386) | Mar 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_35/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.16.18-200.fc35.x86_64 | 162       | 8.73%   |
| 5.14.10-300.fc35.x86_64 | 127       | 6.84%   |
| 5.15.6-200.fc35.x86_64  | 78        | 4.2%    |
| 5.16.16-200.fc35.x86_64 | 74        | 3.99%   |
| 5.17.4-200.fc35.x86_64  | 71        | 3.83%   |
| 5.14.16-301.fc35.x86_64 | 68        | 3.66%   |
| 5.16.12-200.fc35.x86_64 | 63        | 3.39%   |
| 5.15.12-200.fc35.x86_64 | 62        | 3.34%   |
| 5.14.18-300.fc35.x86_64 | 62        | 3.34%   |
| 5.16.9-200.fc35.x86_64  | 57        | 3.07%   |
| 5.16.20-200.fc35.x86_64 | 49        | 2.64%   |
| 5.15.16-200.fc35.x86_64 | 49        | 2.64%   |
| 5.14.17-301.fc35.x86_64 | 48        | 2.59%   |
| 5.17.5-200.fc35.x86_64  | 46        | 2.48%   |
| 5.16.19-200.fc35.x86_64 | 41        | 2.21%   |
| 5.16.11-200.fc35.x86_64 | 41        | 2.21%   |
| 5.14.14-300.fc35.x86_64 | 37        | 1.99%   |
| 5.15.11-200.fc35.x86_64 | 36        | 1.94%   |
| 5.16.5-200.fc35.x86_64  | 34        | 1.83%   |
| 5.15.14-200.fc35.x86_64 | 32        | 1.72%   |
| 5.15.13-200.fc35.x86_64 | 31        | 1.67%   |
| 5.15.18-200.fc35.x86_64 | 30        | 1.62%   |
| 5.15.10-200.fc35.x86_64 | 29        | 1.56%   |
| 5.14.15-300.fc35.x86_64 | 29        | 1.56%   |
| 5.16.15-201.fc35.x86_64 | 28        | 1.51%   |
| 5.15.8-200.fc35.x86_64  | 28        | 1.51%   |
| 5.16.8-200.fc35.x86_64  | 25        | 1.35%   |
| 5.15.5-200.fc35.x86_64  | 21        | 1.13%   |
| 5.15.4-201.fc35.x86_64  | 21        | 1.13%   |
| 5.16.14-200.fc35.x86_64 | 19        | 1.02%   |
| 5.16.7-200.fc35.x86_64  | 17        | 0.92%   |
| 5.15.7-200.fc35.x86_64  | 17        | 0.92%   |
| 5.15.17-200.fc35.x86_64 | 16        | 0.86%   |
| 5.15.15-200.fc35.x86_64 | 15        | 0.81%   |
| 5.14.9-300.fc35.x86_64  | 15        | 0.81%   |
| 5.17.11-200.fc35.x86_64 | 10        | 0.54%   |
| 5.14.0-60.fc35.x86_64   | 10        | 0.54%   |
| 5.16.13-200.fc35.x86_64 | 9         | 0.48%   |
| 5.17.6-200.fc35.x86_64  | 8         | 0.43%   |
| 5.16.10-200.fc35.x86_64 | 8         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.18 | 164       | 8.86%   |
| 5.14.10 | 127       | 6.86%   |
| 5.15.6  | 82        | 4.43%   |
| 5.16.16 | 76        | 4.1%    |
| 5.17.4  | 73        | 3.94%   |
| 5.14.16 | 69        | 3.73%   |
| 5.16.12 | 66        | 3.56%   |
| 5.14.18 | 63        | 3.4%    |
| 5.15.12 | 62        | 3.35%   |
| 5.16.9  | 57        | 3.08%   |
| 5.17.5  | 50        | 2.7%    |
| 5.16.20 | 50        | 2.7%    |
| 5.15.16 | 49        | 2.65%   |
| 5.14.17 | 48        | 2.59%   |
| 5.16.11 | 42        | 2.27%   |
| 5.16.19 | 41        | 2.21%   |
| 5.14.14 | 38        | 2.05%   |
| 5.15.11 | 37        | 2%      |
| 5.16.5  | 34        | 1.84%   |
| 5.15.14 | 33        | 1.78%   |
| 5.15.13 | 33        | 1.78%   |
| 5.15.8  | 30        | 1.62%   |
| 5.15.18 | 30        | 1.62%   |
| 5.14.15 | 30        | 1.62%   |
| 5.15.10 | 29        | 1.57%   |
| 5.16.15 | 28        | 1.51%   |
| 5.16.8  | 26        | 1.4%    |
| 5.15.5  | 23        | 1.24%   |
| 5.15.4  | 23        | 1.24%   |
| 5.14.0  | 20        | 1.08%   |
| 5.16.14 | 19        | 1.03%   |
| 5.16.7  | 17        | 0.92%   |
| 5.15.7  | 17        | 0.92%   |
| 5.15.17 | 16        | 0.86%   |
| 5.15.15 | 16        | 0.86%   |
| 5.14.9  | 16        | 0.86%   |
| 5.17.11 | 10        | 0.54%   |
| 5.16.13 | 10        | 0.54%   |
| 5.16.10 | 10        | 0.54%   |
| 5.16.17 | 9         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 627       | 35.15%  |
| 5.15    | 466       | 26.12%  |
| 5.14    | 431       | 24.16%  |
| 5.17    | 169       | 9.47%   |
| 5.18    | 32        | 1.79%   |
| 5.19    | 18        | 1.01%   |
| 6.0     | 11        | 0.62%   |
| 5.13    | 9         | 0.5%    |
| 5.12    | 8         | 0.45%   |
| 5.11    | 4         | 0.22%   |
| 5.10    | 4         | 0.22%   |
| 5.8     | 2         | 0.11%   |
| 5.9     | 1         | 0.06%   |
| 5.6     | 1         | 0.06%   |
| 5.4     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1634      | 99.88%  |
| aarch64 | 2         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1235      | 74.53%  |
| KDE5            | 184       | 11.1%   |
| Unknown         | 69        | 4.16%   |
| X-Cinnamon      | 32        | 1.93%   |
| XFCE            | 31        | 1.87%   |
| Cinnamon        | 29        | 1.75%   |
| MATE            | 25        | 1.51%   |
| GNOME Classic   | 11        | 0.66%   |
| KDE             | 9         | 0.54%   |
| i3              | 9         | 0.54%   |
| LXDE            | 5         | 0.3%    |
| sway            | 4         | 0.24%   |
| LXQt            | 3         | 0.18%   |
| Pantheon        | 2         | 0.12%   |
| openbox         | 2         | 0.12%   |
| GNOME Flashback | 2         | 0.12%   |
| fluxbox         | 2         | 0.12%   |
| DWM             | 1         | 0.06%   |
| Deepin          | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1024      | 61.06%  |
| X11     | 580       | 34.59%  |
| Tty     | 37        | 2.21%   |
| Unknown | 34        | 2.03%   |
| Web     | 2         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 826       | 50%     |
| GDM     | 589       | 35.65%  |
| LightDM | 124       | 7.51%   |
| SDDM    | 108       | 6.54%   |
| LXDM    | 3         | 0.18%   |
| XDM     | 1         | 0.06%   |
| TDM     | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 880       | 53.46%  |
| en_GB   | 126       | 7.65%   |
| ru_RU   | 76        | 4.62%   |
| pt_BR   | 74        | 4.5%    |
| de_DE   | 59        | 3.58%   |
| fr_FR   | 54        | 3.28%   |
| it_IT   | 39        | 2.37%   |
| en_AU   | 39        | 2.37%   |
| en_CA   | 33        | 2%      |
| es_ES   | 26        | 1.58%   |
| pl_PL   | 25        | 1.52%   |
| es_MX   | 14        | 0.85%   |
| cs_CZ   | 12        | 0.73%   |
| es_CL   | 11        | 0.67%   |
| nl_NL   | 9         | 0.55%   |
| nl_BE   | 9         | 0.55%   |
| C       | 9         | 0.55%   |
| tr_TR   | 8         | 0.49%   |
| es_CO   | 8         | 0.49%   |
| en_IN   | 8         | 0.49%   |
| Unknown | 8         | 0.49%   |
| zh_CN   | 7         | 0.43%   |
| sv_SE   | 6         | 0.36%   |
| fr_CA   | 6         | 0.36%   |
| en_IE   | 6         | 0.36%   |
| de_AT   | 6         | 0.36%   |
| fr_CH   | 5         | 0.3%    |
| en_NZ   | 5         | 0.3%    |
| en_IL   | 5         | 0.3%    |
| pt_PT   | 4         | 0.24%   |
| hu_HU   | 4         | 0.24%   |
| fi_FI   | 4         | 0.24%   |
| es_AR   | 4         | 0.24%   |
| en_DK   | 4         | 0.24%   |
| ca_ES   | 4         | 0.24%   |
| uk_UA   | 3         | 0.18%   |
| ru_UA   | 3         | 0.18%   |
| ro_RO   | 3         | 0.18%   |
| nb_NO   | 3         | 0.18%   |
| fr_BE   | 3         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1302      | 78.67%  |
| BIOS | 353       | 21.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1186      | 72.05%  |
| Ext4    | 392       | 23.82%  |
| Xfs     | 56        | 3.4%    |
| Overlay | 7         | 0.43%   |
| Unknown | 3         | 0.18%   |
| F2fs    | 1         | 0.06%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 824       | 49.76%  |
| GPT     | 727       | 43.9%   |
| MBR     | 105       | 6.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1449      | 87.66%  |
| Yes       | 204       | 12.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1333      | 80.64%  |
| Yes       | 320       | 19.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 345       | 21.09%  |
| ASUSTek Computer       | 247       | 15.1%   |
| Dell                   | 218       | 13.33%  |
| Hewlett-Packard        | 196       | 11.98%  |
| Gigabyte Technology    | 114       | 6.97%   |
| MSI                    | 107       | 6.54%   |
| Acer                   | 74        | 4.52%   |
| Apple                  | 50        | 3.06%   |
| ASRock                 | 41        | 2.51%   |
| HUAWEI                 | 23        | 1.41%   |
| Intel                  | 21        | 1.28%   |
| Toshiba                | 14        | 0.86%   |
| Notebook               | 12        | 0.73%   |
| Fujitsu                | 11        | 0.67%   |
| Samsung Electronics    | 10        | 0.61%   |
| Framework              | 10        | 0.61%   |
| Sony                   | 9         | 0.55%   |
| Microsoft              | 8         | 0.49%   |
| Google                 | 8         | 0.49%   |
| System76               | 7         | 0.43%   |
| Positivo               | 6         | 0.37%   |
| Razer                  | 5         | 0.31%   |
| ECS                    | 5         | 0.31%   |
| Alienware              | 5         | 0.31%   |
| Unknown                | 5         | 0.31%   |
| TUXEDO                 | 4         | 0.24%   |
| Timi                   | 4         | 0.24%   |
| BESSTAR Tech           | 4         | 0.24%   |
| Supermicro             | 3         | 0.18%   |
| Biostar                | 3         | 0.18%   |
| AZW                    | 3         | 0.18%   |
| Avell High Performance | 3         | 0.18%   |
| AMI                    | 3         | 0.18%   |
| XFX                    | 2         | 0.12%   |
| PC Specialist          | 2         | 0.12%   |
| Panasonic              | 2         | 0.12%   |
| Medion                 | 2         | 0.12%   |
| JINGSHA                | 2         | 0.12%   |
| HONOR                  | 2         | 0.12%   |
| Hampoo                 | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUS All Series                   | 12        | 0.73%   |
| Framework Laptop                  | 10        | 0.61%   |
| Unknown                           | 9         | 0.55%   |
| MSI MS-7C37                       | 7         | 0.43%   |
| HP Notebook                       | 7         | 0.43%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2 | 6         | 0.37%   |
| Dell XPS 13 9310                  | 6         | 0.37%   |
| Dell XPS 13 7390                  | 6         | 0.37%   |
| MSI MS-7C56                       | 5         | 0.31%   |
| Lenovo ThinkBook 15 G2 ITL 20VE   | 5         | 0.31%   |
| HUAWEI KLVL-WXX9                  | 5         | 0.31%   |
| HP Pavilion Notebook              | 5         | 0.31%   |
| Gigabyte B450M DS3H               | 5         | 0.31%   |
| ASUS ROG STRIX B550-I GAMING      | 5         | 0.31%   |
| ASUS ROG STRIX B450-F GAMING      | 5         | 0.31%   |
| ASUS ROG CROSSHAIR VII HERO       | 5         | 0.31%   |
| MSI MS-7B93                       | 4         | 0.24%   |
| Gigabyte X570 I AORUS PRO WIFI    | 4         | 0.24%   |
| Gigabyte B450 AORUS M             | 4         | 0.24%   |
| Dell XPS 13 9370                  | 4         | 0.24%   |
| Dell XPS 13 9305                  | 4         | 0.24%   |
| Dell Precision 5510               | 4         | 0.24%   |
| Dell OptiPlex 7010                | 4         | 0.24%   |
| Dell Latitude E7440               | 4         | 0.24%   |
| ASUS ROG STRIX B550-F GAMING      | 4         | 0.24%   |
| Apple MacBookPro9,2               | 4         | 0.24%   |
| MSI MS-7D25                       | 3         | 0.18%   |
| MSI MS-7C91                       | 3         | 0.18%   |
| MSI MS-7C84                       | 3         | 0.18%   |
| MSI MS-7B89                       | 3         | 0.18%   |
| MSI MS-7B86                       | 3         | 0.18%   |
| MSI MS-7B79                       | 3         | 0.18%   |
| MSI MS-7A38                       | 3         | 0.18%   |
| MSI Delta 15 A5EFK                | 3         | 0.18%   |
| Lenovo Legion Y530-15ICH 81FV     | 3         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7    | 3         | 0.18%   |
| Lenovo IdeaPad 530S-14IKB 81EU    | 3         | 0.18%   |
| Lenovo IdeaPad 3 14ALC6 82KT      | 3         | 0.18%   |
| HUAWEI KLVL-WXXW                  | 3         | 0.18%   |
| HUAWEI HVY-WXX9                   | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 175       | 10.7%   |
| ASUS ROG           | 69        | 4.22%   |
| Lenovo IdeaPad     | 61        | 3.73%   |
| Dell Inspiron      | 54        | 3.3%    |
| Dell Latitude      | 51        | 3.12%   |
| Dell XPS           | 48        | 2.93%   |
| HP Pavilion        | 40        | 2.44%   |
| Acer Aspire        | 40        | 2.44%   |
| ASUS PRIME         | 31        | 1.89%   |
| HP ProBook         | 24        | 1.47%   |
| HP EliteBook       | 24        | 1.47%   |
| Dell OptiPlex      | 24        | 1.47%   |
| Lenovo ThinkCentre | 22        | 1.34%   |
| Dell Precision     | 21        | 1.28%   |
| HP Laptop          | 19        | 1.16%   |
| ASUS TUF           | 19        | 1.16%   |
| HP ENVY            | 17        | 1.04%   |
| Lenovo Yoga        | 16        | 0.98%   |
| ASUS VivoBook      | 15        | 0.92%   |
| Lenovo Legion      | 14        | 0.86%   |
| Lenovo ThinkBook   | 13        | 0.79%   |
| Lenovo IdeaPadFlex | 12        | 0.73%   |
| Gigabyte X570      | 12        | 0.73%   |
| ASUS All           | 12        | 0.73%   |
| Acer Swift         | 12        | 0.73%   |
| HP ZBook           | 11        | 0.67%   |
| Dell Vostro        | 11        | 0.67%   |
| ASUS ZenBook       | 11        | 0.67%   |
| Acer Nitro         | 11        | 0.67%   |
| Toshiba Satellite  | 10        | 0.61%   |
| Framework Laptop   | 10        | 0.61%   |
| ASUS ASUS          | 10        | 0.61%   |
| Unknown            | 9         | 0.55%   |
| Microsoft Surface  | 8         | 0.49%   |
| MSI MS-7C37        | 7         | 0.43%   |
| HP Notebook        | 7         | 0.43%   |
| HP EliteDesk       | 7         | 0.43%   |
| Gigabyte B450      | 7         | 0.43%   |
| Apple MacBookPro11 | 7         | 0.43%   |
| HP Spectre         | 6         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 292       | 17.85%  |
| 2021 | 236       | 14.43%  |
| 2019 | 211       | 12.9%   |
| 2018 | 177       | 10.82%  |
| 2017 | 120       | 7.33%   |
| 2013 | 99        | 6.05%   |
| 2014 | 89        | 5.44%   |
| 2016 | 86        | 5.26%   |
| 2015 | 77        | 4.71%   |
| 2011 | 75        | 4.58%   |
| 2012 | 72        | 4.4%    |
| 2010 | 39        | 2.38%   |
| 2009 | 23        | 1.41%   |
| 2008 | 22        | 1.34%   |
| 2022 | 8         | 0.49%   |
| 2007 | 7         | 0.43%   |
| 2006 | 3         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 955       | 58.37%  |
| Desktop        | 530       | 32.4%   |
| Convertible    | 72        | 4.4%    |
| Mini pc        | 33        | 2.02%   |
| All in one     | 21        | 1.28%   |
| Tablet         | 17        | 1.04%   |
| Server         | 7         | 0.43%   |
| System on chip | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1388      | 84.22%  |
| Enabled  | 260       | 15.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1624      | 99.27%  |
| Yes  | 12        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 420       | 25.55%  |
| 4.01-8.0        | 390       | 23.72%  |
| 8.01-16.0       | 298       | 18.13%  |
| 32.01-64.0      | 256       | 15.57%  |
| 3.01-4.0        | 149       | 9.06%   |
| 64.01-256.0     | 74        | 4.5%    |
| 24.01-32.0      | 32        | 1.95%   |
| 1.01-2.0        | 15        | 0.91%   |
| 2.01-3.0        | 9         | 0.55%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 507       | 28.47%  |
| 2.01-3.0    | 481       | 27.01%  |
| 3.01-4.0    | 354       | 19.88%  |
| 1.01-2.0    | 229       | 12.86%  |
| 8.01-16.0   | 154       | 8.65%   |
| 0.51-1.0    | 21        | 1.18%   |
| 16.01-24.0  | 18        | 1.01%   |
| 24.01-32.0  | 9         | 0.51%   |
| 32.01-64.0  | 4         | 0.22%   |
| 0.01-0.5    | 3         | 0.17%   |
| 64.01-256.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 942       | 56.71%  |
| 2      | 439       | 26.43%  |
| 3      | 136       | 8.19%   |
| 4      | 60        | 3.61%   |
| 5      | 38        | 2.29%   |
| 6      | 21        | 1.26%   |
| 7      | 12        | 0.72%   |
| 0      | 6         | 0.36%   |
| 8      | 3         | 0.18%   |
| 9      | 2         | 0.12%   |
| 14     | 1         | 0.06%   |
| 10     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1280      | 77.91%  |
| Yes       | 363       | 22.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1318      | 80.07%  |
| No        | 328       | 19.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1333      | 81.38%  |
| No        | 305       | 18.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1193      | 72.26%  |
| No        | 458       | 27.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 313       | 19.05%  |
| Russia       | 110       | 6.7%    |
| Brazil       | 108       | 6.57%   |
| Germany      | 104       | 6.33%   |
| Italy        | 68        | 4.14%   |
| Canada       | 68        | 4.14%   |
| France       | 67        | 4.08%   |
| UK           | 56        | 3.41%   |
| Spain        | 47        | 2.86%   |
| Poland       | 43        | 2.62%   |
| Australia    | 42        | 2.56%   |
| India        | 40        | 2.43%   |
| Netherlands  | 39        | 2.37%   |
| Austria      | 33        | 2.01%   |
| Sweden       | 27        | 1.64%   |
| Czechia      | 26        | 1.58%   |
| Mexico       | 25        | 1.52%   |
| Belgium      | 25        | 1.52%   |
| Turkey       | 22        | 1.34%   |
| Switzerland  | 20        | 1.22%   |
| Norway       | 20        | 1.22%   |
| Romania      | 19        | 1.16%   |
| Ukraine      | 18        | 1.1%    |
| Indonesia    | 16        | 0.97%   |
| Hungary      | 15        | 0.91%   |
| Chile        | 15        | 0.91%   |
| Greece       | 13        | 0.79%   |
| Belarus      | 12        | 0.73%   |
| Israel       | 10        | 0.61%   |
| Colombia     | 10        | 0.61%   |
| Portugal     | 9         | 0.55%   |
| China        | 9         | 0.55%   |
| Argentina    | 9         | 0.55%   |
| South Africa | 8         | 0.49%   |
| Japan        | 8         | 0.49%   |
| Finland      | 8         | 0.49%   |
| Denmark      | 8         | 0.49%   |
| Saudi Arabia | 7         | 0.43%   |
| New Zealand  | 7         | 0.43%   |
| Bulgaria     | 7         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 39        | 2.3%    |
| Vienna            | 19        | 1.12%   |
| Sydney            | 18        | 1.06%   |
| Milan             | 17        | 1%      |
| Sao Paulo         | 15        | 0.89%   |
| Berlin            | 15        | 0.89%   |
| Istanbul          | 14        | 0.83%   |
| Warsaw            | 12        | 0.71%   |
| St Petersburg     | 12        | 0.71%   |
| Athens            | 10        | 0.59%   |
| Madrid            | 9         | 0.53%   |
| Yekaterinburg     | 8         | 0.47%   |
| Rome              | 8         | 0.47%   |
| Paris             | 8         | 0.47%   |
| Oslo              | 8         | 0.47%   |
| Munich            | 8         | 0.47%   |
| Montreal          | 8         | 0.47%   |
| Melbourne         | 8         | 0.47%   |
| Amsterdam         | 8         | 0.47%   |
| Vancouver         | 7         | 0.41%   |
| Seattle           | 7         | 0.41%   |
| Santiago          | 7         | 0.41%   |
| Prague            | 7         | 0.41%   |
| Minsk             | 7         | 0.41%   |
| Kyiv              | 7         | 0.41%   |
| Bucharest         | 7         | 0.41%   |
| Brisbane          | 7         | 0.41%   |
| Zurich            | 6         | 0.35%   |
| Rio de Janeiro    | 6         | 0.35%   |
| Los Angeles       | 6         | 0.35%   |
| Launceston        | 6         | 0.35%   |
| Krakow            | 6         | 0.35%   |
| Jakarta           | 6         | 0.35%   |
| Budapest          | 6         | 0.35%   |
| Belo Horizonte    | 6         | 0.35%   |
| Antwerp           | 6         | 0.35%   |
| Wörgl            | 5         | 0.3%    |
| Mexico City       | 5         | 0.3%    |
| Hamburg           | 5         | 0.3%    |
| Frankfurt am Main | 5         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 505       | 771    | 20.49%  |
| WDC                       | 334       | 513    | 13.55%  |
| Seagate                   | 278       | 442    | 11.28%  |
| SanDisk                   | 143       | 173    | 5.8%    |
| Toshiba                   | 141       | 161    | 5.72%   |
| Kingston                  | 135       | 161    | 5.48%   |
| Crucial                   | 110       | 134    | 4.46%   |
| SK hynix                  | 101       | 121    | 4.1%    |
| Unknown                   | 93        | 114    | 3.77%   |
| Intel                     | 90        | 119    | 3.65%   |
| Micron Technology         | 46        | 56     | 1.87%   |
| A-DATA Technology         | 41        | 49     | 1.66%   |
| KIOXIA                    | 38        | 50     | 1.54%   |
| Phison                    | 36        | 47     | 1.46%   |
| Hitachi                   | 31        | 40     | 1.26%   |
| HGST                      | 23        | 32     | 0.93%   |
| Apple                     | 23        | 26     | 0.93%   |
| Silicon Motion            | 16        | 18     | 0.65%   |
| SPCC                      | 15        | 20     | 0.61%   |
| Corsair                   | 15        | 17     | 0.61%   |
| Transcend                 | 14        | 17     | 0.57%   |
| XPG                       | 13        | 19     | 0.53%   |
| LITEON                    | 13        | 14     | 0.53%   |
| Patriot                   | 12        | 16     | 0.49%   |
| China                     | 10        | 11     | 0.41%   |
| PNY                       | 9         | 11     | 0.37%   |
| Hewlett-Packard           | 8         | 7      | 0.32%   |
| Unknown                   | 8         | 9      | 0.32%   |
| Lexar                     | 7         | 9      | 0.28%   |
| UMIS                      | 6         | 10     | 0.24%   |
| Realtek Semiconductor     | 6         | 8      | 0.24%   |
| Plextor                   | 6         | 7      | 0.24%   |
| Micron/Crucial Technology | 6         | 7      | 0.24%   |
| GOODRAM                   | 6         | 6      | 0.24%   |
| Team                      | 5         | 9      | 0.2%    |
| Maxtor                    | 5         | 5      | 0.2%    |
| JMicron Technology        | 5         | 8      | 0.2%    |
| ADATA Technology          | 5         | 5      | 0.2%    |
| SSK                       | 4         | 4      | 0.16%   |
| SABRENT                   | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB           | 44        | 1.58%   |
| Samsung NVMe SSD Drive 512GB           | 34        | 1.22%   |
| Samsung NVMe SSD Drive 1TB             | 30        | 1.07%   |
| Kingston SA400S37240G 240GB SSD        | 28        | 1%      |
| Samsung SSD 860 EVO 500GB              | 25        | 0.9%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 23        | 0.82%   |
| Kingston SA400S37480G 480GB SSD        | 23        | 0.82%   |
| SK hynix NVMe SSD Drive 512GB          | 21        | 0.75%   |
| SanDisk NVMe SSD Drive 1TB             | 21        | 0.75%   |
| Samsung SSD 860 EVO 1TB                | 21        | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB         | 19        | 0.68%   |
| Samsung SSD 850 EVO 250GB              | 19        | 0.68%   |
| Crucial CT1000MX500SSD1 1TB            | 19        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB         | 18        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB           | 18        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB         | 18        | 0.64%   |
| Samsung SSD 850 EVO 500GB              | 18        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB         | 17        | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB           | 17        | 0.61%   |
| Crucial CT500MX500SSD1 500GB           | 17        | 0.61%   |
| SanDisk NVMe SSD Drive 500GB           | 16        | 0.57%   |
| Unknown MMC Card  32GB                 | 15        | 0.54%   |
| SanDisk NVMe SSD Drive 256GB           | 15        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB        | 14        | 0.5%    |
| Intel NVMe SSD Drive 512GB             | 14        | 0.5%    |
| Unknown MMC Card  64GB                 | 13        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 12        | 0.43%   |
| SK hynix NVMe SSD Drive 256GB          | 12        | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 12        | 0.43%   |
| Samsung NVMe SSD Drive 2TB             | 12        | 0.43%   |
| Samsung NVMe SSD Drive 250GB           | 12        | 0.43%   |
| Samsung NVMe SSD Drive 1024GB          | 12        | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB         | 11        | 0.39%   |
| Samsung SSD 860 EVO 250GB              | 11        | 0.39%   |
| KIOXIA NVMe SSD Drive 512GB            | 11        | 0.39%   |
| Kingston SA400S37120G 120GB SSD        | 11        | 0.39%   |
| Unknown MMC Card  128GB                | 10        | 0.36%   |
| Toshiba NVMe SSD Drive 512GB           | 10        | 0.36%   |
| Toshiba MQ01ABD100 1TB                 | 10        | 0.36%   |
| HGST HTS721010A9E630 1TB               | 10        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 270       | 428    | 41.22%  |
| WDC                 | 220       | 364    | 33.59%  |
| Toshiba             | 77        | 89     | 11.76%  |
| Hitachi             | 31        | 40     | 4.73%   |
| HGST                | 23        | 32     | 3.51%   |
| Samsung Electronics | 13        | 17     | 1.98%   |
| Unknown             | 5         | 5      | 0.76%   |
| Maxtor              | 5         | 5      | 0.76%   |
| Apple               | 3         | 3      | 0.46%   |
| ASMT                | 2         | 2      | 0.31%   |
| USB 3.0             | 1         | 2      | 0.15%   |
| MaxDigital          | 1         | 1      | 0.15%   |
| LaCie               | 1         | 2      | 0.15%   |
| JMicron Technology  | 1         | 3      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| Fujitsu             | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 206       | 311    | 25.69%  |
| Kingston            | 104       | 122    | 12.97%  |
| Crucial             | 96        | 118    | 11.97%  |
| SanDisk             | 57        | 72     | 7.11%   |
| WDC                 | 55        | 67     | 6.86%   |
| Intel               | 31        | 40     | 3.87%   |
| A-DATA Technology   | 31        | 38     | 3.87%   |
| Apple               | 16        | 16     | 2%      |
| Micron Technology   | 15        | 18     | 1.87%   |
| Toshiba             | 13        | 16     | 1.62%   |
| SPCC                | 12        | 16     | 1.5%    |
| Transcend           | 11        | 14     | 1.37%   |
| Patriot             | 11        | 14     | 1.37%   |
| SK hynix            | 10        | 12     | 1.25%   |
| LITEON              | 10        | 11     | 1.25%   |
| China               | 10        | 11     | 1.25%   |
| PNY                 | 9         | 11     | 1.12%   |
| Corsair             | 6         | 8      | 0.75%   |
| Hewlett-Packard     | 5         | 5      | 0.62%   |
| GOODRAM             | 5         | 5      | 0.62%   |
| Unknown             | 4         | 4      | 0.5%    |
| Plextor             | 4         | 5      | 0.5%    |
| OCZ                 | 4         | 4      | 0.5%    |
| Mushkin             | 4         | 4      | 0.5%    |
| LITEONIT            | 4         | 4      | 0.5%    |
| Lexar               | 4         | 5      | 0.5%    |
| KingSpec            | 4         | 4      | 0.5%    |
| Apacer              | 4         | 6      | 0.5%    |
| Unknown             | 4         | 4      | 0.5%    |
| Team                | 3         | 7      | 0.37%   |
| Netac               | 3         | 3      | 0.37%   |
| JMicron Technology  | 3         | 3      | 0.37%   |
| Intenso             | 3         | 6      | 0.37%   |
| Gigabyte Technology | 3         | 4      | 0.37%   |
| Verbatim            | 2         | 2      | 0.25%   |
| Ramsta              | 2         | 3      | 0.25%   |
| FORESEE             | 2         | 2      | 0.25%   |
| BIWIN               | 2         | 2      | 0.25%   |
| Zozt                | 1         | 1      | 0.12%   |
| Zheino              | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 858       | 1190   | 38.18%  |
| SSD     | 700       | 1031   | 31.15%  |
| HDD     | 572       | 995    | 25.46%  |
| MMC     | 82        | 106    | 3.65%   |
| Unknown | 35        | 43     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 969       | 1966   | 48.55%  |
| NVMe | 858       | 1185   | 42.99%  |
| SAS  | 87        | 108    | 4.36%   |
| MMC  | 82        | 106    | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 724       | 1054   | 53.12%  |
| 0.51-1.0   | 400       | 564    | 29.35%  |
| 1.01-2.0   | 117       | 174    | 8.58%   |
| 3.01-4.0   | 61        | 90     | 4.48%   |
| 2.01-3.0   | 27        | 67     | 1.98%   |
| 4.01-10.0  | 27        | 64     | 1.98%   |
| 10.01-20.0 | 7         | 13     | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 331       | 19.82%  |
| 251-500        | 312       | 18.68%  |
| 1001-2000      | 233       | 13.95%  |
| 101-250        | 227       | 13.59%  |
| 1-20           | 200       | 11.98%  |
| More than 3000 | 117       | 7.01%   |
| Unknown        | 115       | 6.89%   |
| 2001-3000      | 58        | 3.47%   |
| 51-100         | 57        | 3.41%   |
| 21-50          | 20        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 472       | 27.28%  |
| 21-50          | 266       | 15.38%  |
| 101-250        | 251       | 14.51%  |
| 251-500        | 184       | 10.64%  |
| 51-100         | 178       | 10.29%  |
| 501-1000       | 128       | 7.4%    |
| Unknown        | 115       | 6.65%   |
| 1001-2000      | 77        | 4.45%   |
| More than 3000 | 33        | 1.91%   |
| 2001-3000      | 26        | 1.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB         | 5         | 12     | 4.17%   |
| Seagate ST3500418AS 500GB               | 3         | 5      | 2.5%    |
| Samsung Electronics SSD 870 EVO 500GB   | 3         | 3      | 2.5%    |
| Seagate ST9500325AS 500GB               | 2         | 4      | 1.67%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 1.67%   |
| Seagate ST2000DM001-1CH164 2TB          | 2         | 2      | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 4      | 1.67%   |
| Intel SSDSC2CT120A3 120GB               | 2         | 4      | 1.67%   |
| HGST HTS721010A9E630 1TB                | 2         | 2      | 1.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 1      | 0.83%   |
| WDC WD5000LPLX-60ZNTT1 500GB            | 1         | 1      | 0.83%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1         | 1      | 0.83%   |
| WDC WD40PURZ-85TTDY0 4TB                | 1         | 1      | 0.83%   |
| WDC WD3200BEVT-24A23T0 320GB            | 1         | 1      | 0.83%   |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 1      | 0.83%   |
| WDC WD30EFRX-68AX9N0 3TB                | 1         | 1      | 0.83%   |
| WDC WD2500AAKX-753CA1 250GB             | 1         | 1      | 0.83%   |
| WDC WD1600BEVT-24A23T0 160GB            | 1         | 1      | 0.83%   |
| WDC WD1600BEVS-60RST0 160GB             | 1         | 1      | 0.83%   |
| WDC WD1600AAJS-00Z4A0 160GB             | 1         | 1      | 0.83%   |
| WDC WD15EARS-00S0XB0 1TB                | 1         | 1      | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 1      | 0.83%   |
| WDC WD10EFRX-68JCSN0 1TB                | 1         | 1      | 0.83%   |
| WDC WD10EALX-009BA0 1TB                 | 1         | 1      | 0.83%   |
| WDC WD10EADS-65P6B0 1TB                 | 1         | 1      | 0.83%   |
| WDC WD1003FBYX-01Y7B1 1TB               | 1         | 1      | 0.83%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD050V 500GB               | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 0.83%   |
| Toshiba MK6476GSX 640GB                 | 1         | 1      | 0.83%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1      | 0.83%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1      | 0.83%   |
| Teclast 360GB A850 SSD                  | 1         | 1      | 0.83%   |
| Team T2535T480G 480GB SSD               | 1         | 4      | 0.83%   |
| SK hynix SC308 SATA 256GB SSD           | 1         | 1      | 0.83%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1      | 0.83%   |
| Seagate ST9750420AS 752GB               | 1         | 1      | 0.83%   |
| Seagate ST95005620AS 500GB              | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 62     | 30.51%  |
| WDC                 | 18        | 18     | 15.25%  |
| Samsung Electronics | 12        | 15     | 10.17%  |
| Toshiba             | 7         | 7      | 5.93%   |
| Intel               | 7         | 10     | 5.93%   |
| Hitachi             | 7         | 8      | 5.93%   |
| Crucial             | 6         | 6      | 5.08%   |
| A-DATA Technology   | 4         | 4      | 3.39%   |
| SanDisk             | 3         | 3      | 2.54%   |
| HGST                | 3         | 3      | 2.54%   |
| SK hynix            | 2         | 2      | 1.69%   |
| Micron Technology   | 2         | 3      | 1.69%   |
| LITEON              | 2         | 2      | 1.69%   |
| Kingston            | 2         | 2      | 1.69%   |
| Corsair             | 2         | 2      | 1.69%   |
| Teclast             | 1         | 1      | 0.85%   |
| Team                | 1         | 4      | 0.85%   |
| PNY                 | 1         | 1      | 0.85%   |
| Plextor             | 1         | 1      | 0.85%   |
| Maxtor              | 1         | 1      | 0.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 62     | 50%     |
| WDC                 | 17        | 17     | 23.61%  |
| Hitachi             | 7         | 8      | 9.72%   |
| Toshiba             | 6         | 6      | 8.33%   |
| HGST                | 3         | 3      | 4.17%   |
| Samsung Electronics | 2         | 5      | 2.78%   |
| Maxtor              | 1         | 1      | 1.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 102    | 60%     |
| SSD  | 39        | 46     | 33.91%  |
| NVMe | 7         | 7      | 6.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 900       | 1818   | 49.97%  |
| Works    | 786       | 1391   | 43.64%  |
| Malfunc  | 114       | 155    | 6.33%   |
| Failed   | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 916       | 40.53%  |
| AMD                              | 366       | 16.19%  |
| Samsung Electronics              | 332       | 14.69%  |
| SanDisk                          | 149       | 6.59%   |
| SK hynix                         | 89        | 3.94%   |
| Toshiba America Info Systems     | 53        | 2.35%   |
| Phison Electronics               | 45        | 1.99%   |
| KIOXIA                           | 37        | 1.64%   |
| Kingston Technology Company      | 36        | 1.59%   |
| ASMedia Technology               | 35        | 1.55%   |
| Micron Technology                | 32        | 1.42%   |
| Silicon Motion                   | 23        | 1.02%   |
| Marvell Technology Group         | 23        | 1.02%   |
| ADATA Technology                 | 23        | 1.02%   |
| Micron/Crucial Technology        | 20        | 0.88%   |
| Nvidia                           | 14        | 0.62%   |
| JMicron Technology               | 13        | 0.58%   |
| Union Memory (Shenzhen)          | 8         | 0.35%   |
| Realtek Semiconductor            | 8         | 0.35%   |
| Lite-On Technology               | 5         | 0.22%   |
| Solid State Storage Technology   | 4         | 0.18%   |
| Apple                            | 4         | 0.18%   |
| Silicon Image                    | 3         | 0.13%   |
| LSI Logic / Symbios Logic        | 3         | 0.13%   |
| Broadcom / LSI                   | 3         | 0.13%   |
| Yangtze Memory Technologies      | 2         | 0.09%   |
| Seagate Technology               | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.09%   |
| Lenovo                           | 2         | 0.09%   |
| VIA Technologies                 | 1         | 0.04%   |
| ULi Electronics                  | 1         | 0.04%   |
| Transcend                        | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Hewlett-Packard                  | 1         | 0.04%   |
| Dell                             | 1         | 0.04%   |
| Beijing Starblaze Technology     | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 279       | 11.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 182       | 7.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 110       | 4.42%   |
| Samsung NVMe SSD Controller 980                                                | 69        | 2.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 64        | 2.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 62        | 2.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 61        | 2.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 58        | 2.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 47        | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 44        | 1.77%   |
| AMD 500 Series Chipset SATA Controller                                         | 44        | 1.77%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 39        | 1.57%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 36        | 1.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 36        | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 1.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 35        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 33        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 33        | 1.32%   |
| Micron Non-Volatile memory controller                                          | 32        | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 32        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 28        | 1.12%   |
| Intel SSD 660P Series                                                          | 27        | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 26        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                            | 26        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 25        | 1%      |
| SanDisk Non-Volatile memory controller                                         | 24        | 0.96%   |
| Phison E12 NVMe Controller                                                     | 23        | 0.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 22        | 0.88%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.88%   |
| SK hynix Non-Volatile memory controller                                        | 21        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 18        | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 0.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 17        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 16        | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 15        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1138      | 51.22%  |
| NVMe | 856       | 38.52%  |
| RAID | 134       | 6.03%   |
| IDE  | 83        | 3.74%   |
| SAS  | 10        | 0.45%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1158      | 70.78%  |
| AMD    | 476       | 29.1%   |
| ARM    | 2         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 44        | 2.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 43        | 2.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 30        | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 1.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 1.22%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 1.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 17        | 1.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 16        | 0.98%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 16        | 0.98%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 0.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 15        | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 15        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 0.73%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 12        | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.67%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 11        | 0.67%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 11        | 0.67%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 11        | 0.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 0.67%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 11        | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 10        | 0.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 10        | 0.61%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 10        | 0.61%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 0.61%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 10        | 0.61%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 9         | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 0.55%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 9         | 0.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 8         | 0.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 8         | 0.49%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 380       | 23.23%  |
| Intel Core i5           | 333       | 20.35%  |
| Other                   | 156       | 9.54%   |
| AMD Ryzen 5             | 141       | 8.62%   |
| AMD Ryzen 7             | 138       | 8.44%   |
| Intel Core i3           | 101       | 6.17%   |
| AMD Ryzen 9             | 57        | 3.48%   |
| Intel Xeon              | 38        | 2.32%   |
| Intel Celeron           | 33        | 2.02%   |
| Intel Core 2 Duo        | 29        | 1.77%   |
| Intel Core i9           | 25        | 1.53%   |
| AMD Ryzen 3             | 22        | 1.34%   |
| Intel Atom              | 21        | 1.28%   |
| Intel Pentium           | 18        | 1.1%    |
| AMD Ryzen 7 PRO         | 12        | 0.73%   |
| AMD FX                  | 12        | 0.73%   |
| AMD A4                  | 10        | 0.61%   |
| AMD A10                 | 10        | 0.61%   |
| AMD Athlon              | 8         | 0.49%   |
| AMD A6                  | 8         | 0.49%   |
| AMD Ryzen Threadripper  | 7         | 0.43%   |
| AMD Ryzen 5 PRO         | 7         | 0.43%   |
| AMD A8                  | 7         | 0.43%   |
| Intel Pentium Silver    | 6         | 0.37%   |
| Intel Pentium Dual-Core | 5         | 0.31%   |
| Intel Core 2 Quad       | 4         | 0.24%   |
| AMD Athlon X4           | 4         | 0.24%   |
| Intel Pentium Dual      | 3         | 0.18%   |
| AMD Ryzen 3 PRO         | 3         | 0.18%   |
| AMD Phenom              | 3         | 0.18%   |
| AMD E                   | 3         | 0.18%   |
| AMD Athlon II X2        | 3         | 0.18%   |
| Intel Core m3           | 2         | 0.12%   |
| AMD Phenom II X4        | 2         | 0.12%   |
| AMD Phenom II X2        | 2         | 0.12%   |
| AMD Phenom II           | 2         | 0.12%   |
| AMD E2                  | 2         | 0.12%   |
| AMD Athlon 64 X2        | 2         | 0.12%   |
| Intel Xeon Silver       | 1         | 0.06%   |
| Intel Pentium Gold      | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 680       | 41.56%  |
| 2       | 443       | 27.08%  |
| 6       | 215       | 13.14%  |
| 8       | 204       | 12.47%  |
| 12      | 32        | 1.96%   |
| 16      | 23        | 1.41%   |
| 10      | 12        | 0.73%   |
| 1       | 9         | 0.55%   |
| 24      | 6         | 0.37%   |
| 3       | 6         | 0.37%   |
| 14      | 3         | 0.18%   |
| 40      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1626      | 99.39%  |
| 2       | 8         | 0.49%   |
| 4       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1293      | 78.99%  |
| 1       | 343       | 20.95%  |
| Unknown | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1635      | 99.94%  |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 106       | 6.42%   |
| Unknown    | 93        | 5.64%   |
| 0x306a9    | 80        | 4.85%   |
| 0x306c3    | 79        | 4.79%   |
| 0x806ec    | 78        | 4.73%   |
| 0x806ea    | 67        | 4.06%   |
| 0x206a7    | 65        | 3.94%   |
| 0x806e9    | 54        | 3.27%   |
| 0x906ea    | 53        | 3.21%   |
| 0x0a50000c | 49        | 2.97%   |
| 0x08701021 | 49        | 2.97%   |
| 0x406e3    | 42        | 2.55%   |
| 0x40651    | 41        | 2.48%   |
| 0x08600106 | 40        | 2.42%   |
| 0xa0652    | 38        | 2.3%    |
| 0x506e3    | 38        | 2.3%    |
| 0x906e9    | 33        | 2%      |
| 0x08108109 | 31        | 1.88%   |
| 0x306d4    | 29        | 1.76%   |
| 0x906ed    | 27        | 1.64%   |
| 0x1067a    | 24        | 1.45%   |
| 0x706e5    | 23        | 1.39%   |
| 0x08600104 | 20        | 1.21%   |
| 0x0a201016 | 18        | 1.09%   |
| 0x08608103 | 18        | 1.09%   |
| 0x0a201009 | 17        | 1.03%   |
| 0x0800820d | 16        | 0.97%   |
| 0x06001119 | 16        | 0.97%   |
| 0x08108102 | 15        | 0.91%   |
| 0x806eb    | 14        | 0.85%   |
| 0x20655    | 14        | 0.85%   |
| 0x506c9    | 13        | 0.79%   |
| 0x08001138 | 13        | 0.79%   |
| 0x90672    | 12        | 0.73%   |
| 0x706a8    | 12        | 0.73%   |
| 0x08701013 | 12        | 0.73%   |
| 0x0810100b | 12        | 0.73%   |
| 0x406c4    | 11        | 0.67%   |
| 0x10676    | 11        | 0.67%   |
| 0x806d1    | 10        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 352       | 21.5%   |
| Zen 2            | 142       | 8.67%   |
| Haswell          | 137       | 8.37%   |
| TigerLake        | 119       | 7.27%   |
| Zen 3            | 100       | 6.11%   |
| Skylake          | 92        | 5.62%   |
| IvyBridge        | 88        | 5.38%   |
| Zen+             | 79        | 4.83%   |
| SandyBridge      | 76        | 4.64%   |
| CometLake        | 62        | 3.79%   |
| Zen              | 43        | 2.63%   |
| IceLake          | 39        | 2.38%   |
| Penryn           | 36        | 2.2%    |
| Unknown          | 36        | 2.2%    |
| Broadwell        | 33        | 2.02%   |
| Silvermont       | 27        | 1.65%   |
| Piledriver       | 26        | 1.59%   |
| Westmere         | 23        | 1.41%   |
| Goldmont plus    | 17        | 1.04%   |
| K10              | 15        | 0.92%   |
| Alderlake Hybrid | 15        | 0.92%   |
| Goldmont         | 14        | 0.86%   |
| Core             | 12        | 0.73%   |
| Puma             | 8         | 0.49%   |
| Nehalem          | 8         | 0.49%   |
| Excavator        | 8         | 0.49%   |
| Steamroller      | 6         | 0.37%   |
| Jaguar           | 6         | 0.37%   |
| Bobcat           | 4         | 0.24%   |
| Tremont          | 3         | 0.18%   |
| K10 Llano        | 3         | 0.18%   |
| Bulldozer        | 3         | 0.18%   |
| Bonnell          | 3         | 0.18%   |
| K8 Hammer        | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 957       | 48.24%  |
| Nvidia                           | 537       | 27.07%  |
| AMD                              | 483       | 24.34%  |
| Matrox Electronics Systems       | 3         | 0.15%   |
| ASPEED Technology                | 3         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 110       | 5.46%   |
| AMD Renoir                                                                               | 74        | 3.68%   |
| Intel UHD Graphics 620                                                                   | 68        | 3.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 54        | 2.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 54        | 2.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 2.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 49        | 2.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 2.38%   |
| Intel HD Graphics 620                                                                    | 46        | 2.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 46        | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 2.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 2.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 42        | 2.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 36        | 1.79%   |
| Intel HD Graphics 530                                                                    | 31        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 1.39%   |
| AMD Lucienne                                                                             | 28        | 1.39%   |
| Intel HD Graphics 630                                                                    | 26        | 1.29%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 1.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 0.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 20        | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 12        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 11        | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 646       | 39.41%  |
| 1 x AMD            | 393       | 23.98%  |
| 1 x Nvidia         | 249       | 15.19%  |
| Intel + Nvidia     | 247       | 15.07%  |
| AMD + Nvidia       | 35        | 2.14%   |
| Intel + AMD        | 31        | 1.89%   |
| 2 x AMD            | 22        | 1.34%   |
| Other              | 5         | 0.31%   |
| 1 x ASPEED         | 3         | 0.18%   |
| 2 x Nvidia         | 2         | 0.12%   |
| 1 x Matrox         | 2         | 0.12%   |
| 1 x SiS            | 1         | 0.06%   |
| Nvidia + Matrox    | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |
| Intel + 2 x AMD    | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1336      | 80.92%  |
| Proprietary | 288       | 17.44%  |
| Unknown     | 27        | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 918       | 55.4%   |
| 1.01-2.0   | 194       | 11.71%  |
| 0.01-0.5   | 186       | 11.23%  |
| 3.01-4.0   | 109       | 6.58%   |
| 0.51-1.0   | 90        | 5.43%   |
| 7.01-8.0   | 89        | 5.37%   |
| 8.01-16.0  | 36        | 2.17%   |
| 5.01-6.0   | 27        | 1.63%   |
| 2.01-3.0   | 8         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 215       | 10.96%  |
| Samsung Electronics     | 205       | 10.45%  |
| Chimei Innolux          | 186       | 9.48%   |
| BOE                     | 185       | 9.43%   |
| LG Display              | 167       | 8.52%   |
| Dell                    | 157       | 8.01%   |
| Goldstar                | 108       | 5.51%   |
| Sharp                   | 70        | 3.57%   |
| Acer                    | 64        | 3.26%   |
| Hewlett-Packard         | 59        | 3.01%   |
| AOC                     | 53        | 2.7%    |
| Lenovo                  | 48        | 2.45%   |
| Apple                   | 46        | 2.35%   |
| Philips                 | 45        | 2.29%   |
| BenQ                    | 45        | 2.29%   |
| Ancor Communications    | 42        | 2.14%   |
| ViewSonic               | 26        | 1.33%   |
| InfoVision              | 22        | 1.12%   |
| Iiyama                  | 21        | 1.07%   |
| PANDA                   | 19        | 0.97%   |
| ASUSTek Computer        | 19        | 0.97%   |
| CSO                     | 16        | 0.82%   |
| Chi Mei Optoelectronics | 11        | 0.56%   |
| Eizo                    | 9         | 0.46%   |
| MSI                     | 8         | 0.41%   |
| Vizio                   | 6         | 0.31%   |
| TMX                     | 6         | 0.31%   |
| Panasonic               | 6         | 0.31%   |
| HannStar                | 6         | 0.31%   |
| Gigabyte Technology     | 6         | 0.31%   |
| Sony                    | 5         | 0.25%   |
| Unknown                 | 4         | 0.2%    |
| Sceptre Tech            | 4         | 0.2%    |
| Insignia                | 4         | 0.2%    |
| ONN                     | 3         | 0.15%   |
| NEC Computers           | 3         | 0.15%   |
| InnoLux Display         | 3         | 0.15%   |
| Fujitsu Siemens         | 3         | 0.15%   |
| ___                     | 2         | 0.1%    |
| Unknown (XXX)           | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 18        | 0.89%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 12        | 0.59%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 10        | 0.49%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 9         | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch    | 9         | 0.45%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 8         | 0.4%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 8         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 8         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 7         | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch      | 7         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 7         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch  | 7         | 0.35%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch             | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch    | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 7         | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch | 6         | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch          | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch    | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 6         | 0.3%    |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                  | 6         | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch | 5         | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch           | 5         | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch      | 5         | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch      | 5         | 0.25%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 5         | 0.25%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch             | 5         | 0.25%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch             | 5         | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch             | 5         | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch              | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch    | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch     | 5         | 0.25%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                   | 5         | 0.25%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch  | 5         | 0.25%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch           | 4         | 0.2%    |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch           | 4         | 0.2%    |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch           | 4         | 0.2%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch           | 4         | 0.2%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch           | 4         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 931       | 50.99%  |
| 1366x768 (WXGA)    | 219       | 11.99%  |
| 3840x2160 (4K)     | 164       | 8.98%   |
| 2560x1440 (QHD)    | 153       | 8.38%   |
| 1920x1200 (WUXGA)  | 55        | 3.01%   |
| 1600x900 (HD+)     | 40        | 2.19%   |
| 1440x900 (WXGA+)   | 28        | 1.53%   |
| 1680x1050 (WSXGA+) | 27        | 1.48%   |
| 1280x1024 (SXGA)   | 27        | 1.48%   |
| 3440x1440          | 26        | 1.42%   |
| 2560x1080          | 18        | 0.99%   |
| 2560x1600          | 17        | 0.93%   |
| 1280x800 (WXGA)    | 16        | 0.88%   |
| 2880x1800          | 14        | 0.77%   |
| 2160x1440          | 11        | 0.6%    |
| 3840x2400          | 10        | 0.55%   |
| 2256x1504          | 10        | 0.55%   |
| 1360x768           | 6         | 0.33%   |
| 3840x1080          | 5         | 0.27%   |
| 3200x1800 (QHD+)   | 5         | 0.27%   |
| Unknown            | 5         | 0.27%   |
| 2736x1824          | 4         | 0.22%   |
| 1600x1200          | 4         | 0.22%   |
| 3000x2000          | 3         | 0.16%   |
| 2240x1400          | 3         | 0.16%   |
| 3840x1600          | 2         | 0.11%   |
| 3200x2000          | 2         | 0.11%   |
| 3072x1920          | 2         | 0.11%   |
| 2880x1920          | 2         | 0.11%   |
| 2160x1350          | 2         | 0.11%   |
| 1920x540           | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |
| 1280x720 (HD)      | 2         | 0.11%   |
| 6784x2160          | 1         | 0.05%   |
| 4480x1200          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 3840x2560          | 1         | 0.05%   |
| 2400x1600          | 1         | 0.05%   |
| 1800x1200          | 1         | 0.05%   |
| 1280x960           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 441       | 22.39%  |
| 13      | 266       | 13.5%   |
| 27      | 227       | 11.52%  |
| 14      | 180       | 9.14%   |
| 24      | 178       | 9.04%   |
| 23      | 118       | 5.99%   |
| 21      | 116       | 5.89%   |
| 17      | 59        | 2.99%   |
| 31      | 50        | 2.54%   |
| 34      | 42        | 2.13%   |
| 12      | 42        | 2.13%   |
| 19      | 29        | 1.47%   |
| 18      | 26        | 1.32%   |
| 22      | 21        | 1.07%   |
| 20      | 19        | 0.96%   |
| 11      | 17        | 0.86%   |
| Unknown | 17        | 0.86%   |
| 16      | 15        | 0.76%   |
| 84      | 11        | 0.56%   |
| 54      | 9         | 0.46%   |
| 25      | 9         | 0.46%   |
| 26      | 8         | 0.41%   |
| 42      | 7         | 0.36%   |
| 40      | 7         | 0.36%   |
| 32      | 7         | 0.36%   |
| 72      | 6         | 0.3%    |
| 28      | 6         | 0.3%    |
| 48      | 5         | 0.25%   |
| 29      | 4         | 0.2%    |
| 65      | 3         | 0.15%   |
| 49      | 3         | 0.15%   |
| 37      | 3         | 0.15%   |
| 35      | 3         | 0.15%   |
| 10      | 3         | 0.15%   |
| 74      | 2         | 0.1%    |
| 58      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 30      | 2         | 0.1%    |
| 55      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 755       | 38.96%  |
| 501-600     | 485       | 25.03%  |
| 201-300     | 210       | 10.84%  |
| 401-500     | 189       | 9.75%   |
| 601-700     | 85        | 4.39%   |
| 351-400     | 80        | 4.13%   |
| 701-800     | 49        | 2.53%   |
| 1001-1500   | 27        | 1.39%   |
| 1501-2000   | 19        | 0.98%   |
| Unknown     | 17        | 0.88%   |
| 801-900     | 14        | 0.72%   |
| 901-1000    | 8         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1368      | 80.95%  |
| 16/10   | 187       | 11.07%  |
| 21/9    | 46        | 2.72%   |
| 3/2     | 36        | 2.13%   |
| 5/4     | 28        | 1.66%   |
| Unknown | 10        | 0.59%   |
| 4/3     | 7         | 0.41%   |
| 32/9    | 6         | 0.36%   |
| 6/5     | 2         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 445       | 22.68%  |
| 201-250        | 340       | 17.33%  |
| 81-90          | 328       | 16.72%  |
| 301-350        | 232       | 11.82%  |
| 71-80          | 126       | 6.42%   |
| 351-500        | 112       | 5.71%   |
| 151-200        | 85        | 4.33%   |
| 251-300        | 64        | 3.26%   |
| 121-130        | 49        | 2.5%    |
| More than 1000 | 37        | 1.89%   |
| 61-70          | 36        | 1.83%   |
| 141-150        | 31        | 1.58%   |
| 501-1000       | 28        | 1.43%   |
| 51-60          | 17        | 0.87%   |
| Unknown        | 17        | 0.87%   |
| 111-120        | 10        | 0.51%   |
| 41-50          | 3         | 0.15%   |
| 131-140        | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 613       | 32.43%  |
| 51-100        | 550       | 29.1%   |
| 101-120       | 413       | 21.85%  |
| 161-240       | 200       | 10.58%  |
| More than 240 | 70        | 3.7%    |
| 1-50          | 27        | 1.43%   |
| Unknown       | 17        | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1221      | 73.47%  |
| 2     | 349       | 21%     |
| 3     | 45        | 2.71%   |
| 0     | 45        | 2.71%   |
| 4     | 2         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 954       | 39.29%  |
| Realtek Semiconductor             | 836       | 34.43%  |
| Qualcomm Atheros                  | 207       | 8.53%   |
| Broadcom                          | 95        | 3.91%   |
| MediaTek                          | 43        | 1.77%   |
| TP-Link                           | 29        | 1.19%   |
| Broadcom Limited                  | 21        | 0.86%   |
| Lenovo                            | 20        | 0.82%   |
| Ralink Technology                 | 18        | 0.74%   |
| Ralink                            | 15        | 0.62%   |
| Marvell Technology Group          | 15        | 0.62%   |
| ASIX Electronics                  | 13        | 0.54%   |
| Nvidia                            | 11        | 0.45%   |
| DisplayLink                       | 11        | 0.45%   |
| Sierra Wireless                   | 10        | 0.41%   |
| Dell                              | 10        | 0.41%   |
| Xiaomi                            | 9         | 0.37%   |
| Aquantia                          | 9         | 0.37%   |
| Qualcomm                          | 8         | 0.33%   |
| ASUSTek Computer                  | 8         | 0.33%   |
| Microsoft                         | 7         | 0.29%   |
| D-Link                            | 6         | 0.25%   |
| NetGear                           | 5         | 0.21%   |
| Linksys                           | 5         | 0.21%   |
| Samsung Electronics               | 4         | 0.16%   |
| Huawei Technologies               | 4         | 0.16%   |
| Google                            | 4         | 0.16%   |
| Belkin Components                 | 4         | 0.16%   |
| OPPO Electronics                  | 3         | 0.12%   |
| Hewlett-Packard                   | 3         | 0.12%   |
| Ericsson Business Mobile Networks | 3         | 0.12%   |
| AVM                               | 3         | 0.12%   |
| Wilocity                          | 2         | 0.08%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| OpenMoko                          | 2         | 0.08%   |
| MosChip Semiconductor             | 2         | 0.08%   |
| InterBiometrics                   | 2         | 0.08%   |
| ICS Advent                        | 2         | 0.08%   |
| HMD Global                        | 2         | 0.08%   |
| Fibocom                           | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 543       | 18.71%  |
| Intel Wi-Fi 6 AX200                                               | 166       | 5.72%   |
| Intel Wi-Fi 6 AX201                                               | 89        | 3.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 85        | 2.93%   |
| Intel Wireless 8265 / 8275                                        | 73        | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 67        | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 52        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 50        | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 45        | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 45        | 1.55%   |
| Intel Wireless 8260                                               | 43        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 38        | 1.31%   |
| Intel Wireless 7260                                               | 38        | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 38        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 36        | 1.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 35        | 1.21%   |
| Intel Ethernet Controller I225-V                                  | 33        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 32        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 30        | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 28        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 28        | 0.96%   |
| Intel Wireless 7265                                               | 27        | 0.93%   |
| Intel Wireless 3165                                               | 26        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 26        | 0.9%    |
| Intel Wireless-AC 9260                                            | 25        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 24        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 16        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 796       | 56.45%  |
| Realtek Semiconductor           | 185       | 13.12%  |
| Qualcomm Atheros                | 171       | 12.13%  |
| Broadcom                        | 72        | 5.11%   |
| MediaTek                        | 41        | 2.91%   |
| TP-Link                         | 27        | 1.91%   |
| Ralink Technology               | 18        | 1.28%   |
| Broadcom Limited                | 16        | 1.13%   |
| Ralink                          | 15        | 1.06%   |
| Sierra Wireless                 | 10        | 0.71%   |
| Microsoft                       | 7         | 0.5%    |
| Dell                            | 7         | 0.5%    |
| ASUSTek Computer                | 7         | 0.5%    |
| Qualcomm                        | 6         | 0.43%   |
| NetGear                         | 5         | 0.35%   |
| Marvell Technology Group        | 4         | 0.28%   |
| Linksys                         | 4         | 0.28%   |
| Belkin Components               | 4         | 0.28%   |
| D-Link                          | 3         | 0.21%   |
| AVM                             | 3         | 0.21%   |
| Wilocity                        | 2         | 0.14%   |
| Qualcomm Atheros Communications | 2         | 0.14%   |
| Fibocom                         | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 166       | 11.71%  |
| Intel Wi-Fi 6 AX201                                            | 89        | 6.28%   |
| Intel Wireless 8265 / 8275                                     | 73        | 5.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 45        | 3.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 45        | 3.18%   |
| Intel Wireless 8260                                            | 43        | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 38        | 2.68%   |
| Intel Wireless 7260                                            | 38        | 2.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 38        | 2.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 36        | 2.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 35        | 2.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 32        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 30        | 2.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 28        | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 28        | 1.98%   |
| Intel Wireless 7265                                            | 27        | 1.91%   |
| Intel Wireless 3165                                            | 26        | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 26        | 1.83%   |
| Intel Wireless-AC 9260                                         | 25        | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24        | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 19        | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 16        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 13        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 9         | 0.64%   |
| Realtek 802.11ac NIC                                           | 9         | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 9         | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 8         | 0.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 8         | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                 | 7         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 743       | 52.51%  |
| Intel                            | 453       | 32.01%  |
| Qualcomm Atheros                 | 50        | 3.53%   |
| Broadcom                         | 37        | 2.61%   |
| Lenovo                           | 20        | 1.41%   |
| ASIX Electronics                 | 13        | 0.92%   |
| Nvidia                           | 11        | 0.78%   |
| Marvell Technology Group         | 11        | 0.78%   |
| DisplayLink                      | 11        | 0.78%   |
| Xiaomi                           | 9         | 0.64%   |
| Aquantia                         | 9         | 0.64%   |
| Broadcom Limited                 | 5         | 0.35%   |
| Samsung Electronics              | 4         | 0.28%   |
| Google                           | 4         | 0.28%   |
| OPPO Electronics                 | 3         | 0.21%   |
| D-Link                           | 3         | 0.21%   |
| TP-Link                          | 2         | 0.14%   |
| Qualcomm                         | 2         | 0.14%   |
| MosChip Semiconductor            | 2         | 0.14%   |
| MediaTek                         | 2         | 0.14%   |
| ICS Advent                       | 2         | 0.14%   |
| Huawei Technologies              | 2         | 0.14%   |
| HMD Global                       | 2         | 0.14%   |
| Cypress Semiconductor            | 2         | 0.14%   |
| Apple                            | 2         | 0.14%   |
| Xilinx                           | 1         | 0.07%   |
| Spreadtrum Communications        | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| OpenMoko                         | 1         | 0.07%   |
| NetXen Incorporated              | 1         | 0.07%   |
| Motorola PCS                     | 1         | 0.07%   |
| Mellanox Technologies            | 1         | 0.07%   |
| Linksys                          | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| Ceton Technologies               | 1         | 0.07%   |
| ASUSTek Computer                 | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 543       | 37.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 85        | 5.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 4.57%   |
| Intel I211 Gigabit Network Connection                             | 67        | 4.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 52        | 3.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 50        | 3.41%   |
| Intel Ethernet Controller I225-V                                  | 33        | 2.25%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 1.3%    |
| Intel Ethernet Connection (6) I219-V                              | 18        | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.89%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 12        | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10        | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.61%   |
| Intel 82574L Gigabit Network Connection                           | 9         | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.48%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                            | 7         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.41%   |
| Intel Ethernet Connection (10) I219-LM                            | 6         | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1333      | 50%     |
| Ethernet | 1315      | 49.32%  |
| Modem    | 16        | 0.6%    |
| Unknown  | 2         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1068      | 61.66%  |
| Ethernet | 664       | 38.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 862       | 52.56%  |
| 1     | 686       | 41.83%  |
| 3     | 52        | 3.17%   |
| 0     | 27        | 1.65%   |
| 4     | 7         | 0.43%   |
| 6     | 3         | 0.18%   |
| 5     | 3         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1239      | 74.91%  |
| Yes  | 415       | 25.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 704       | 58.23%  |
| Realtek Semiconductor           | 110       | 9.1%    |
| Qualcomm Atheros Communications | 76        | 6.29%   |
| Cambridge Silicon Radio         | 55        | 4.55%   |
| Apple                           | 45        | 3.72%   |
| Lite-On Technology              | 37        | 3.06%   |
| Broadcom                        | 37        | 3.06%   |
| IMC Networks                    | 34        | 2.81%   |
| Foxconn / Hon Hai               | 33        | 2.73%   |
| ASUSTek Computer                | 24        | 1.99%   |
| Realtek                         | 15        | 1.24%   |
| Ralink                          | 11        | 0.91%   |
| Dell                            | 6         | 0.5%    |
| MediaTek                        | 4         | 0.33%   |
| Marvell Semiconductor           | 4         | 0.33%   |
| TP-Link                         | 3         | 0.25%   |
| Hewlett-Packard                 | 3         | 0.25%   |
| Foxconn International           | 2         | 0.17%   |
| Belkin Components               | 2         | 0.17%   |
| Toshiba                         | 1         | 0.08%   |
| Kensington                      | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| Alps Electric                   | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 196       | 16.21%  |
| Intel AX201 Bluetooth                               | 163       | 13.48%  |
| Intel AX200 Bluetooth                               | 161       | 13.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 88        | 7.28%   |
| Realtek Bluetooth Radio                             | 81        | 6.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 55        | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 3.31%   |
| Intel AX210 Bluetooth                               | 29        | 2.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 26        | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 24        | 1.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 1.99%   |
| Apple Bluetooth Host Controller                     | 23        | 1.9%    |
| Realtek Bluetooth Radio                             | 15        | 1.24%   |
| IMC Networks Wireless_Device                        | 15        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 1.08%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 0.91%   |
| Apple Bluetooth USB Host Controller                 | 11        | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.83%   |
| Lite-On Bluetooth Device                            | 10        | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 0.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 10        | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.74%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.66%   |
| IMC Networks Bluetooth Radio                        | 7         | 0.58%   |
| ASUS Bluetooth Device                               | 7         | 0.58%   |
| Lite-On Wireless_Device                             | 6         | 0.5%    |
| ASUS Bluetooth Radio                                | 6         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.41%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 5         | 0.41%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.33%   |
| MediaTek Wireless_Device                            | 4         | 0.33%   |
| Intel Bluetooth Device                              | 4         | 0.33%   |
| IMC Networks Bluetooth Device                       | 4         | 0.33%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.33%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1107      | 45.18%  |
| AMD                        | 543       | 22.16%  |
| Nvidia                     | 397       | 16.2%   |
| C-Media Electronics        | 44        | 1.8%    |
| Logitech                   | 23        | 0.94%   |
| Realtek Semiconductor      | 22        | 0.9%    |
| GN Netcom                  | 22        | 0.9%    |
| Lenovo                     | 20        | 0.82%   |
| SteelSeries ApS            | 17        | 0.69%   |
| Creative Labs              | 15        | 0.61%   |
| Plantronics                | 14        | 0.57%   |
| JMTek                      | 14        | 0.57%   |
| Texas Instruments          | 12        | 0.49%   |
| Kingston Technology        | 12        | 0.49%   |
| Corsair                    | 12        | 0.49%   |
| Razer USA                  | 11        | 0.45%   |
| Focusrite-Novation         | 11        | 0.45%   |
| Generalplus Technology     | 8         | 0.33%   |
| Creative Technology        | 8         | 0.33%   |
| Sony                       | 6         | 0.24%   |
| RODE Microphones           | 6         | 0.24%   |
| Blue Microphones           | 6         | 0.24%   |
| Tenx Technology            | 5         | 0.2%    |
| Hewlett-Packard            | 5         | 0.2%    |
| Sennheiser Communications  | 4         | 0.16%   |
| SAVITECH                   | 4         | 0.16%   |
| Samson Technologies        | 4         | 0.16%   |
| ASUSTek Computer           | 4         | 0.16%   |
| Apple                      | 4         | 0.16%   |
| XMOS                       | 3         | 0.12%   |
| PreSonus Audio Electronics | 3         | 0.12%   |
| GYROCOM C&C                | 3         | 0.12%   |
| Giga-Byte Technology       | 3         | 0.12%   |
| Dell                       | 3         | 0.12%   |
| CMX Systems                | 3         | 0.12%   |
| Cambridge Silicon Radio    | 3         | 0.12%   |
| Audio-Technica             | 3         | 0.12%   |
| Apogee Electronics         | 3         | 0.12%   |
| Yamaha                     | 2         | 0.08%   |
| Unknown (ABC)              | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 225       | 7.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 170       | 5.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 141       | 4.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 119       | 4.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 104       | 3.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 82        | 2.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 82        | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 72        | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 70        | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 63        | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 54        | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 52        | 1.77%   |
| Intel Comet Lake PCH cAVS                                                  | 51        | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 48        | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 46        | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 45        | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 44        | 1.5%    |
| Intel 8 Series HD Audio Controller                                         | 44        | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 43        | 1.46%   |
| AMD FCH Azalia Controller                                                  | 40        | 1.36%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 36        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 34        | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 32        | 1.09%   |
| Intel Broadwell-U Audio Controller                                         | 30        | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 28        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 0.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26        | 0.89%   |
| AMD Navi 10 HDMI Audio                                                     | 26        | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 25        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 24        | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 23        | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 20        | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 20        | 0.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 20        | 0.68%   |
| Realtek Semiconductor USB Audio                                            | 19        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 19        | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 18        | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 18        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 244       | 23.99%  |
| SK hynix            | 168       | 16.52%  |
| Micron Technology   | 123       | 12.09%  |
| Kingston            | 112       | 11.01%  |
| Crucial             | 82        | 8.06%   |
| Unknown             | 68        | 6.69%   |
| Corsair             | 65        | 6.39%   |
| G.Skill             | 39        | 3.83%   |
| A-DATA Technology   | 18        | 1.77%   |
| Ramaxel Technology  | 15        | 1.47%   |
| Team                | 13        | 1.28%   |
| Elpida              | 9         | 0.88%   |
| Unknown (ABCD)      | 6         | 0.59%   |
| Smart               | 6         | 0.59%   |
| Unknown             | 6         | 0.59%   |
| Transcend           | 4         | 0.39%   |
| Goodram             | 4         | 0.39%   |
| Smart Brazil        | 3         | 0.29%   |
| Patriot             | 3         | 0.29%   |
| Nanya Technology    | 3         | 0.29%   |
| Avant               | 3         | 0.29%   |
| Timetec             | 2         | 0.2%    |
| Goldkey             | 2         | 0.2%    |
| AMD                 | 2         | 0.2%    |
| V-GeN               | 1         | 0.1%    |
| Unknown (AB)        | 1         | 0.1%    |
| Unknown (0x7301)    | 1         | 0.1%    |
| Toshiba             | 1         | 0.1%    |
| RZX                 | 1         | 0.1%    |
| Qumo                | 1         | 0.1%    |
| Qimonda             | 1         | 0.1%    |
| PUSKILL             | 1         | 0.1%    |
| PLEXHD              | 1         | 0.1%    |
| Patriot Memory      | 1         | 0.1%    |
| OLOY                | 1         | 0.1%    |
| OCZ                 | 1         | 0.1%    |
| Miron               | 1         | 0.1%    |
| fef5                | 1         | 0.1%    |
| CSX                 | 1         | 0.1%    |
| ASint Technology    | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.92%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 9         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 7         | 0.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 7         | 0.65%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 6         | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.55%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 6         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.55%   |
| Unknown                                                          | 6         | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 5         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 5         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.46%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.46%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.46%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.46%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 5         | 0.46%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s           | 5         | 0.46%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 512       | 58.12%  |
| DDR3    | 221       | 25.09%  |
| LPDDR4  | 52        | 5.9%    |
| LPDDR3  | 50        | 5.68%   |
| DDR2    | 16        | 1.82%   |
| Unknown | 16        | 1.82%   |
| SDRAM   | 7         | 0.79%   |
| DDR5    | 5         | 0.57%   |
| DDR     | 2         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 499       | 56%     |
| DIMM         | 263       | 29.52%  |
| Row Of Chips | 119       | 13.36%  |
| Chip         | 7         | 0.79%   |
| Unknown      | 2         | 0.22%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 407       | 43.21%  |
| 4096  | 232       | 24.63%  |
| 16384 | 176       | 18.68%  |
| 2048  | 74        | 7.86%   |
| 32768 | 41        | 4.35%   |
| 1024  | 12        | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 212       | 22.51%  |
| 2667    | 152       | 16.14%  |
| 1600    | 149       | 15.82%  |
| 2400    | 66        | 7.01%   |
| 2133    | 59        | 6.26%   |
| 1333    | 43        | 4.56%   |
| 3600    | 38        | 4.03%   |
| 4267    | 31        | 3.29%   |
| 1867    | 27        | 2.87%   |
| 1067    | 14        | 1.49%   |
| 3266    | 13        | 1.38%   |
| 1334    | 13        | 1.38%   |
| 3733    | 11        | 1.17%   |
| 1066    | 11        | 1.17%   |
| 3466    | 10        | 1.06%   |
| 800     | 10        | 1.06%   |
| 667     | 9         | 0.96%   |
| 3400    | 7         | 0.74%   |
| 2933    | 7         | 0.74%   |
| 4800    | 5         | 0.53%   |
| 4266    | 5         | 0.53%   |
| 3000    | 5         | 0.53%   |
| 4199    | 4         | 0.42%   |
| 3866    | 4         | 0.42%   |
| 3800    | 4         | 0.42%   |
| 2666    | 4         | 0.42%   |
| 8400    | 3         | 0.32%   |
| 3666    | 3         | 0.32%   |
| 2800    | 3         | 0.32%   |
| 1866    | 3         | 0.32%   |
| Unknown | 3         | 0.32%   |
| 3500    | 2         | 0.21%   |
| 400     | 2         | 0.21%   |
| 5200    | 1         | 0.11%   |
| 4040    | 1         | 0.11%   |
| 4000    | 1         | 0.11%   |
| 2802    | 1         | 0.11%   |
| 2187    | 1         | 0.11%   |
| 1648    | 1         | 0.11%   |
| 1024    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 31.25%  |
| Brother Industries  | 8         | 25%     |
| Canon               | 5         | 15.63%  |
| Samsung Electronics | 3         | 9.38%   |
| Prolific Technology | 2         | 6.25%   |
| Kyocera             | 2         | 6.25%   |
| Seiko Epson         | 1         | 3.13%   |
| QinHeng Electronics | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother HL-L2340D series        | 3         | 9.38%   |
| Prolific PL2305 Parallel Port   | 2         | 6.25%   |
| HP DeskJet 2130 series          | 2         | 6.25%   |
| Canon TR4500 series             | 2         | 6.25%   |
| Seiko Epson WF-2510 Series      | 1         | 3.13%   |
| Samsung SCX-3200 Series         | 1         | 3.13%   |
| Samsung M2070 Series            | 1         | 3.13%   |
| Samsung CLX-6260 Series         | 1         | 3.13%   |
| QinHeng CH340S                  | 1         | 3.13%   |
| Kyocera TASKalfa 250ci          | 1         | 3.13%   |
| Kyocera ECOSYS M5521cdw         | 1         | 3.13%   |
| HP Officejet 6600               | 1         | 3.13%   |
| HP LaserJet CM1415fnw           | 1         | 3.13%   |
| HP LaserJet 400 colorMFP M475dw | 1         | 3.13%   |
| HP LaserJet 1018                | 1         | 3.13%   |
| HP DeskJet F300 series          | 1         | 3.13%   |
| HP DeskJet F2492 All-in-One     | 1         | 3.13%   |
| HP DeskJet 5650c                | 1         | 3.13%   |
| HP DeskJet 3700 series          | 1         | 3.13%   |
| Canon TR8500 series             | 1         | 3.13%   |
| Canon MF4010 series             | 1         | 3.13%   |
| Canon G3010 series              | 1         | 3.13%   |
| Brother Printer                 | 1         | 3.13%   |
| Brother MFC-J485DW              | 1         | 3.13%   |
| Brother HL-L2360D series        | 1         | 3.13%   |
| Brother HL-2030 Laser Printer   | 1         | 3.13%   |
| Brother HL-1440 Laser Printer   | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 50%     |
| Seiko Epson     | 3         | 37.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]       | 2         | 25%     |
| Canon CanoScan LiDE 220                     | 2         | 25%     |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1         | 12.5%   |
| HP ScanJet 5590                             | 1         | 12.5%   |
| Canon CanoScan LiDE 210                     | 1         | 12.5%   |
| Canon CanoScan LiDE 120                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 237       | 20.48%  |
| IMC Networks                           | 115       | 9.94%   |
| Logitech                               | 104       | 8.99%   |
| Acer                                   | 96        | 8.3%    |
| Realtek Semiconductor                  | 95        | 8.21%   |
| Microdia                               | 94        | 8.12%   |
| Quanta                                 | 64        | 5.53%   |
| Sunplus Innovation Technology          | 53        | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 3.72%   |
| Apple                                  | 38        | 3.28%   |
| Syntek                                 | 32        | 2.77%   |
| Lite-On Technology                     | 28        | 2.42%   |
| Luxvisions Innotech Limited            | 17        | 1.47%   |
| Suyin                                  | 15        | 1.3%    |
| Microsoft                              | 15        | 1.3%    |
| Samsung Electronics                    | 10        | 0.86%   |
| Silicon Motion                         | 9         | 0.78%   |
| Alcor Micro                            | 8         | 0.69%   |
| Generalplus Technology                 | 7         | 0.61%   |
| Lenovo                                 | 6         | 0.52%   |
| Sonix Technology                       | 5         | 0.43%   |
| ARC International                      | 5         | 0.43%   |
| Ricoh                                  | 4         | 0.35%   |
| MacroSilicon                           | 4         | 0.35%   |
| USB Camera                             | 3         | 0.26%   |
| Tobii Technology AB                    | 3         | 0.26%   |
| Primax Electronics                     | 3         | 0.26%   |
| Jieli Technology                       | 3         | 0.26%   |
| Cubeternet                             | 3         | 0.26%   |
| Creative Technology                    | 3         | 0.26%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| Trust                                  | 2         | 0.17%   |
| KYE Systems (Mouse Systems)            | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| DJJHFA1BIF5595                         | 2         | 0.17%   |
| A4Tech                                 | 2         | 0.17%   |
| WaveRider Communications               | 1         | 0.09%   |
| Unknown                                | 1         | 0.09%   |
| SunplusIT                              | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony integrated camera               | 79        | 6.76%   |
| Microdia Integrated_Webcam_HD           | 57        | 4.88%   |
| IMC Networks Integrated Camera          | 52        | 4.45%   |
| Realtek Integrated_Webcam_HD            | 41        | 3.51%   |
| Acer Integrated Camera                  | 40        | 3.42%   |
| Syntek Integrated Camera                | 26        | 2.22%   |
| Sunplus Integrated_Webcam_HD            | 24        | 2.05%   |
| Logitech Webcam C270                    | 24        | 2.05%   |
| Logitech HD Pro Webcam C920             | 23        | 1.97%   |
| IMC Networks USB2.0 HD UVC WebCam       | 23        | 1.97%   |
| Quanta HD User Facing                   | 22        | 1.88%   |
| Chicony HD WebCam                       | 21        | 1.8%    |
| Chicony Integrated Camera (1280x720@30) | 12        | 1.03%   |
| Apple Built-in iSight                   | 12        | 1.03%   |
| Quanta HP TrueVision HD Camera          | 11        | 0.94%   |
| Logitech C922 Pro Stream Webcam         | 11        | 0.94%   |
| Lite-On HP HD Camera                    | 11        | 0.94%   |
| Apple FaceTime HD Camera (Built-in)     | 11        | 0.94%   |
| Samsung Galaxy A5 (MTP)                 | 10        | 0.86%   |
| Chicony HP Wide Vision HD Camera        | 10        | 0.86%   |
| Chicony HP HD Camera                    | 10        | 0.86%   |
| Chicony HD User Facing                  | 9         | 0.77%   |
| Acer SunplusIT Integrated Camera        | 9         | 0.77%   |
| Acer HD Webcam                          | 9         | 0.77%   |
| Microdia USB 2.0 Camera                 | 8         | 0.68%   |
| Microdia Integrated Webcam              | 8         | 0.68%   |
| Lite-On Integrated Camera               | 8         | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 8         | 0.68%   |
| IMC Networks HD Camera                  | 8         | 0.68%   |
| Chicony USB2.0 Camera                   | 8         | 0.68%   |
| Acer Lenovo EasyCamera                  | 8         | 0.68%   |
| Acer BisonCam,NB Pro                    | 8         | 0.68%   |
| Realtek Integrated Webcam               | 7         | 0.6%    |
| Apple iPhone5/5C/5S/6                   | 7         | 0.6%    |
| Sunplus SPCA2650 AV Camera              | 6         | 0.51%   |
| Realtek USB Camera                      | 6         | 0.51%   |
| Realtek Laptop Camera                   | 6         | 0.51%   |
| Quanta HP HD Camera                     | 6         | 0.51%   |
| Microsoft LifeCam HD-3000               | 6         | 0.51%   |
| Microdia Webcam Vitade AF               | 6         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 115       | 42.75%  |
| Validity Sensors           | 63        | 23.42%  |
| Shenzhen Goodix Technology | 56        | 20.82%  |
| Elan Microelectronics      | 13        | 4.83%   |
| Upek                       | 9         | 3.35%   |
| LighTuning Technology      | 8         | 2.97%   |
| AuthenTec                  | 4         | 1.49%   |
| Samsung Electronics        | 1         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 19.7%   |
| Shenzhen Goodix  FingerPrint Device                                        | 32        | 11.9%   |
| Unknown                                                                    | 28        | 10.41%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 6.32%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 4.83%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 4.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.35%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 3.35%   |
| Synaptics  WBDI                                                            | 8         | 2.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.97%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.23%   |
| Validity Sensors VFS491                                                    | 5         | 1.86%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.74%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.74%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.74%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.37%   |
| Synaptics WBDI Device                                                      | 1         | 0.37%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.37%   |
| Samsung Fingerprint Device                                                 | 1         | 0.37%   |
| AuthenTec AES2810                                                          | 1         | 0.37%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 41        | 45.56%  |
| Broadcom                          | 31        | 34.44%  |
| Lenovo                            | 4         | 4.44%   |
| Yubico.com                        | 3         | 3.33%   |
| Upek                              | 3         | 3.33%   |
| O2 Micro                          | 2         | 2.22%   |
| VASCO Data Security International | 1         | 1.11%   |
| OmniKey                           | 1         | 1.11%   |
| Hewlett-Packard                   | 1         | 1.11%   |
| Gemalto (was Gemplus)             | 1         | 1.11%   |
| Clay Logic                        | 1         | 1.11%   |
| Aladdin Knowledge Systems         | 1         | 1.11%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 45.56%  |
| Broadcom 58200                                                               | 11        | 12.22%  |
| Broadcom 5880                                                                | 8         | 8.89%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 7.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.44%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.22%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.11%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.11%   |
| OmniKey CardMan 1021                                                         | 1         | 1.11%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.11%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.11%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.11%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.11%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1133      | 68.01%  |
| 1     | 433       | 25.99%  |
| 2     | 83        | 4.98%   |
| 3     | 12        | 0.72%   |
| 4     | 3         | 0.18%   |
| 5     | 2         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 262       | 41.52%  |
| Graphics card            | 135       | 21.39%  |
| Multimedia controller    | 63        | 9.98%   |
| Net/wireless             | 62        | 9.83%   |
| Camera                   | 28        | 4.44%   |
| Bluetooth                | 17        | 2.69%   |
| Chipcard                 | 14        | 2.22%   |
| Unassigned class         | 11        | 1.74%   |
| Communication controller | 11        | 1.74%   |
| Card reader              | 7         | 1.11%   |
| Storage                  | 5         | 0.79%   |
| Sound                    | 4         | 0.63%   |
| Network                  | 3         | 0.48%   |
| Net/ethernet             | 3         | 0.48%   |
| Modem                    | 3         | 0.48%   |
| Storage/raid             | 1         | 0.16%   |
| Storage/ata              | 1         | 0.16%   |
| Firewire controller      | 1         | 0.16%   |

