Linux in Latvia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Latvia/Desktop/README.md) and [notebooks](/Location/Latvia/Notebook/README.md).

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

Total: 465

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3e3368d913](https://linux-hardware.org/?probe=3e3368d913) | Feb 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [455b0e1401](https://linux-hardware.org/?probe=455b0e1401) | Feb 23, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1a50084a52](https://linux-hardware.org/?probe=1a50084a52) | Feb 19, 2023 |
| MSI           | B75A-G43                    | Desktop     | [bf426ce3c3](https://linux-hardware.org/?probe=bf426ce3c3) | Feb 18, 2023 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [9d36ad089c](https://linux-hardware.org/?probe=9d36ad089c) | Feb 18, 2023 |
| Dell          | Latitude 5330               | Notebook    | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| HP            | ProLiant DL320 G6           | Server      | [0d3689fed9](https://linux-hardware.org/?probe=0d3689fed9) | Feb 09, 2023 |
| Gigabyte      | H55M-D2H                    | Desktop     | [652695efb0](https://linux-hardware.org/?probe=652695efb0) | Feb 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Chuwi         | Hi10 Go                     | Notebook    | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [8f81628b59](https://linux-hardware.org/?probe=8f81628b59) | Jan 27, 2023 |
| Acer          | Aspire 5532                 | Notebook    | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [e98a955b1a](https://linux-hardware.org/?probe=e98a955b1a) | Jan 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [40719006ae](https://linux-hardware.org/?probe=40719006ae) | Jan 23, 2023 |
| Wortmann      | CR700                       | Notebook    | [0d40cf0690](https://linux-hardware.org/?probe=0d40cf0690) | Jan 22, 2023 |
| MSI           | CR500                       | Notebook    | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9cb7b18b35](https://linux-hardware.org/?probe=9cb7b18b35) | Jan 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [95e7b7d833](https://linux-hardware.org/?probe=95e7b7d833) | Jan 20, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [8026c0d5b2](https://linux-hardware.org/?probe=8026c0d5b2) | Jan 17, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [4f28b4be44](https://linux-hardware.org/?probe=4f28b4be44) | Jan 15, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [4884803279](https://linux-hardware.org/?probe=4884803279) | Jan 10, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [49b7bb70f3](https://linux-hardware.org/?probe=49b7bb70f3) | Jan 10, 2023 |
| HP            | 2AED                        | All in one  | [9a324c230d](https://linux-hardware.org/?probe=9a324c230d) | Jan 09, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [625bf5665f](https://linux-hardware.org/?probe=625bf5665f) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Dell          | 0HY9JP A01                  | Desktop     | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [68bd2484a1](https://linux-hardware.org/?probe=68bd2484a1) | Jan 04, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| HP            | G62                         | Notebook    | [4d80c95e73](https://linux-hardware.org/?probe=4d80c95e73) | Dec 18, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [cc139ec3a3](https://linux-hardware.org/?probe=cc139ec3a3) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [b3c750c720](https://linux-hardware.org/?probe=b3c750c720) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [1168ac14f5](https://linux-hardware.org/?probe=1168ac14f5) | Dec 09, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| ASUSTek       | F3Sg                        | Notebook    | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d9a78cb529](https://linux-hardware.org/?probe=d9a78cb529) | Nov 30, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [3d6a965dd4](https://linux-hardware.org/?probe=3d6a965dd4) | Nov 30, 2022 |
| ASUSTek       | G751JL                      | Notebook    | [1bfbfafe68](https://linux-hardware.org/?probe=1bfbfafe68) | Nov 29, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [6c97b310fb](https://linux-hardware.org/?probe=6c97b310fb) | Nov 29, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [f30a5c4808](https://linux-hardware.org/?probe=f30a5c4808) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [585b6910fa](https://linux-hardware.org/?probe=585b6910fa) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [138231da75](https://linux-hardware.org/?probe=138231da75) | Nov 26, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [4768ab429e](https://linux-hardware.org/?probe=4768ab429e) | Nov 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [7d576ac245](https://linux-hardware.org/?probe=7d576ac245) | Oct 29, 2022 |
| Wortmann      | CR700                       | Notebook    | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | Notebook    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e267cad212](https://linux-hardware.org/?probe=e267cad212) | Oct 20, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [69adb866e0](https://linux-hardware.org/?probe=69adb866e0) | Oct 20, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [491d0c69ca](https://linux-hardware.org/?probe=491d0c69ca) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [09ee887f3a](https://linux-hardware.org/?probe=09ee887f3a) | Oct 12, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [734baf54fa](https://linux-hardware.org/?probe=734baf54fa) | Oct 04, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [5bd6c356cd](https://linux-hardware.org/?probe=5bd6c356cd) | Aug 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [0a96778f7c](https://linux-hardware.org/?probe=0a96778f7c) | Jul 30, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [b4877f21ad](https://linux-hardware.org/?probe=b4877f21ad) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [3aa2d086b9](https://linux-hardware.org/?probe=3aa2d086b9) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [27d04b5577](https://linux-hardware.org/?probe=27d04b5577) | Jul 23, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [c6c4a561e1](https://linux-hardware.org/?probe=c6c4a561e1) | Jul 17, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9aa6d6be1](https://linux-hardware.org/?probe=e9aa6d6be1) | Jul 06, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [1acedf0aa3](https://linux-hardware.org/?probe=1acedf0aa3) | Jun 26, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [949fb9a5e7](https://linux-hardware.org/?probe=949fb9a5e7) | Jun 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [fab553a2b2](https://linux-hardware.org/?probe=fab553a2b2) | Jun 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [1242ad2894](https://linux-hardware.org/?probe=1242ad2894) | Jun 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e75d068a21](https://linux-hardware.org/?probe=e75d068a21) | Jun 02, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | Notebook    | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e854926e0](https://linux-hardware.org/?probe=8e854926e0) | May 12, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [3a940a3394](https://linux-hardware.org/?probe=3a940a3394) | May 11, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| HP            | 2AAC                        | Desktop     | [1f6b08507e](https://linux-hardware.org/?probe=1f6b08507e) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [e483a6e634](https://linux-hardware.org/?probe=e483a6e634) | Apr 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| Dell          | Latitude 5590               | Notebook    | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ABIT          | IP35-E                      | Desktop     | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | Notebook    | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [83df25aace](https://linux-hardware.org/?probe=83df25aace) | Feb 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [9dfc1ac601](https://linux-hardware.org/?probe=9dfc1ac601) | Feb 12, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [0848fdb73f](https://linux-hardware.org/?probe=0848fdb73f) | Feb 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [36f709712b](https://linux-hardware.org/?probe=36f709712b) | Feb 08, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [834bc65728](https://linux-hardware.org/?probe=834bc65728) | Feb 04, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [887e40e6c7](https://linux-hardware.org/?probe=887e40e6c7) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| MSI           | P55-GD65                    | Desktop     | [37da95512b](https://linux-hardware.org/?probe=37da95512b) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [a864c07042](https://linux-hardware.org/?probe=a864c07042) | Dec 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | Notebook    | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | Notebook    | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| HP            | 304Bh                       | Desktop     | [643a84ae14](https://linux-hardware.org/?probe=643a84ae14) | Oct 26, 2021 |
| HP            | 304Bh                       | Desktop     | [b7bd300808](https://linux-hardware.org/?probe=b7bd300808) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | Notebook    | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [7e44f2ff81](https://linux-hardware.org/?probe=7e44f2ff81) | Sep 06, 2021 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [071ad478e7](https://linux-hardware.org/?probe=071ad478e7) | Aug 30, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [5b32c9197c](https://linux-hardware.org/?probe=5b32c9197c) | Aug 28, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [8cd8b7faa5](https://linux-hardware.org/?probe=8cd8b7faa5) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | Notebook    | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | Notebook    | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | Notebook    | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [13fb44b235](https://linux-hardware.org/?probe=13fb44b235) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bc618727f4](https://linux-hardware.org/?probe=bc618727f4) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | Notebook    | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | Notebook    | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [6aa52c9eb8](https://linux-hardware.org/?probe=6aa52c9eb8) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | Notebook    | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | Notebook    | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | Notebook    | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | Notebook    | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | Notebook    | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| MSI           | H310M PRO-VD                | Desktop     | [42ade7f952](https://linux-hardware.org/?probe=42ade7f952) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| Dell          | Latitude 5520               | Notebook    | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [25a9c64af7](https://linux-hardware.org/?probe=25a9c64af7) | May 29, 2021 |
| Acer          | AO725                       | Notebook    | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [2d479e2946](https://linux-hardware.org/?probe=2d479e2946) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [621d19b1f1](https://linux-hardware.org/?probe=621d19b1f1) | May 15, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [796bb8e1b8](https://linux-hardware.org/?probe=796bb8e1b8) | May 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4d87fd7e46](https://linux-hardware.org/?probe=4d87fd7e46) | Apr 13, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d2a175100f](https://linux-hardware.org/?probe=d2a175100f) | Mar 22, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | Notebook    | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [344b4339b4](https://linux-hardware.org/?probe=344b4339b4) | Mar 17, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1194a50093](https://linux-hardware.org/?probe=1194a50093) | Mar 16, 2021 |
| HP            | 18E7                        | Desktop     | [d0fb912292](https://linux-hardware.org/?probe=d0fb912292) | Mar 09, 2021 |
| Acer          | F671CR R01-C0               | Desktop     | [7a4637f10b](https://linux-hardware.org/?probe=7a4637f10b) | Mar 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [0ac539b524](https://linux-hardware.org/?probe=0ac539b524) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [dbde42fa23](https://linux-hardware.org/?probe=dbde42fa23) | Mar 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a49a1ff054](https://linux-hardware.org/?probe=a49a1ff054) | Feb 27, 2021 |
| HP            | 304Bh                       | Desktop     | [92c6653702](https://linux-hardware.org/?probe=92c6653702) | Feb 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3bc6f280d8](https://linux-hardware.org/?probe=3bc6f280d8) | Feb 19, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [0cfdd76052](https://linux-hardware.org/?probe=0cfdd76052) | Feb 08, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | Notebook    | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| ASUSTek       | P5GD1-VM                    | Desktop     | [863b2fd0bf](https://linux-hardware.org/?probe=863b2fd0bf) | Jan 22, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb2b38d97f](https://linux-hardware.org/?probe=cb2b38d97f) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5b1abefa3c](https://linux-hardware.org/?probe=5b1abefa3c) | Jan 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [e734d18206](https://linux-hardware.org/?probe=e734d18206) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [b85445cf41](https://linux-hardware.org/?probe=b85445cf41) | Jan 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [81b3dbf5fd](https://linux-hardware.org/?probe=81b3dbf5fd) | Jan 02, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c3b94fff22](https://linux-hardware.org/?probe=c3b94fff22) | Dec 31, 2020 |
| ASUSTek       | N56VM                       | Notebook    | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e50d894b93](https://linux-hardware.org/?probe=e50d894b93) | Dec 28, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [2eede62ff5](https://linux-hardware.org/?probe=2eede62ff5) | Dec 26, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8cf512e3a9](https://linux-hardware.org/?probe=8cf512e3a9) | Dec 26, 2020 |
| ASUSTek       | P5K PRO                     | Desktop     | [0e58a56cfb](https://linux-hardware.org/?probe=0e58a56cfb) | Dec 26, 2020 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [bb01071f16](https://linux-hardware.org/?probe=bb01071f16) | Dec 15, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| Acer          | Aspire E5-774G              | Notebook    | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| MSI           | B75A-G43                    | Desktop     | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| MSI           | B75A-G43                    | Desktop     | [5f68cce112](https://linux-hardware.org/?probe=5f68cce112) | Nov 16, 2020 |
| ASUSTek       | F9S                         | Notebook    | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | Notebook    | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f2ff00472b](https://linux-hardware.org/?probe=f2ff00472b) | Nov 07, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [bdb367a3b2](https://linux-hardware.org/?probe=bdb367a3b2) | Nov 03, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f36ffb293](https://linux-hardware.org/?probe=4f36ffb293) | Nov 01, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [5139c9e029](https://linux-hardware.org/?probe=5139c9e029) | Nov 01, 2020 |
| Acer          | Aspire E1-570               | Notebook    | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7ac6a6dab5](https://linux-hardware.org/?probe=7ac6a6dab5) | Oct 27, 2020 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [3ea3e1a644](https://linux-hardware.org/?probe=3ea3e1a644) | Oct 26, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [c9a44de2e0](https://linux-hardware.org/?probe=c9a44de2e0) | Oct 26, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [4e526c6262](https://linux-hardware.org/?probe=4e526c6262) | Oct 14, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [a37fe628b4](https://linux-hardware.org/?probe=a37fe628b4) | Oct 04, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [c6cf49892e](https://linux-hardware.org/?probe=c6cf49892e) | Oct 04, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [a6c2ba4977](https://linux-hardware.org/?probe=a6c2ba4977) | Oct 04, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ebefa289ab](https://linux-hardware.org/?probe=ebefa289ab) | Sep 30, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [2702ecbebe](https://linux-hardware.org/?probe=2702ecbebe) | Sep 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a53b5a24b](https://linux-hardware.org/?probe=1a53b5a24b) | Sep 21, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [177f17803c](https://linux-hardware.org/?probe=177f17803c) | Aug 24, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | Notebook    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b68bc64592](https://linux-hardware.org/?probe=b68bc64592) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d5429ba62e](https://linux-hardware.org/?probe=d5429ba62e) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | Notebook    | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [625d32881c](https://linux-hardware.org/?probe=625d32881c) | May 29, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | Notebook    | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6d6cb669e](https://linux-hardware.org/?probe=d6d6cb669e) | Apr 29, 2020 |
| Acer          | Aspire ES1-512              | Notebook    | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [31631f3ea5](https://linux-hardware.org/?probe=31631f3ea5) | Apr 23, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [8f1f828d49](https://linux-hardware.org/?probe=8f1f828d49) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [95e2b82808](https://linux-hardware.org/?probe=95e2b82808) | Mar 26, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [9fcf5501fb](https://linux-hardware.org/?probe=9fcf5501fb) | Mar 26, 2020 |
| IBM           | 8215ZCL                     | Desktop     | [8f44ceaa1e](https://linux-hardware.org/?probe=8f44ceaa1e) | Mar 26, 2020 |
| Dell          | Latitude E6230              | Notebook    | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | Notebook    | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | Notebook    | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [2d568b2e9d](https://linux-hardware.org/?probe=2d568b2e9d) | Feb 19, 2020 |
| ASUSTek       | BU401LAV                    | Notebook    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| MSI           | Z370 SLI PLUS               | Desktop     | [c76ba1a6d0](https://linux-hardware.org/?probe=c76ba1a6d0) | Feb 08, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | Notebook    | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | Notebook    | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [9deccd0d74](https://linux-hardware.org/?probe=9deccd0d74) | Jan 24, 2020 |
| Dell          | Inspiron 1720               | Notebook    | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [e005197c6c](https://linux-hardware.org/?probe=e005197c6c) | Jan 09, 2020 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5af3a0243a](https://linux-hardware.org/?probe=5af3a0243a) | Jan 06, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [70297101fe](https://linux-hardware.org/?probe=70297101fe) | Dec 31, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Dell          | 0RJ290                      | Desktop     | [21ae6dbdf0](https://linux-hardware.org/?probe=21ae6dbdf0) | Dec 16, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | Notebook    | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bab2716ff6](https://linux-hardware.org/?probe=bab2716ff6) | Dec 02, 2019 |
| Dell          | Latitude D630               | Notebook    | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | Notebook    | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | Notebook    | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | Notebook    | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | Notebook    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Dell          | Latitude E5510              | Notebook    | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | Notebook    | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a6d137277e](https://linux-hardware.org/?probe=a6d137277e) | Sep 18, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [2fc2bdd742](https://linux-hardware.org/?probe=2fc2bdd742) | Sep 14, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5110001e92](https://linux-hardware.org/?probe=5110001e92) | Sep 14, 2019 |
| Gigabyte      | Z87P-D3                     | Desktop     | [a7e732af2a](https://linux-hardware.org/?probe=a7e732af2a) | Aug 26, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [5c290c18c9](https://linux-hardware.org/?probe=5c290c18c9) | Aug 18, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | 0A60h                       | Desktop     | [b031cf2f9c](https://linux-hardware.org/?probe=b031cf2f9c) | Jul 30, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | Notebook    | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| MSI           | FM2-A55M-E33                | Desktop     | [426ae68b93](https://linux-hardware.org/?probe=426ae68b93) | Jun 29, 2019 |
| MSI           | B85-G41 PC Mate             | Desktop     | [0f3dccfe4e](https://linux-hardware.org/?probe=0f3dccfe4e) | Jun 26, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | Notebook    | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | Notebook    | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | Notebook    | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | Notebook    | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [5e414bc536](https://linux-hardware.org/?probe=5e414bc536) | Mar 14, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | Notebook    | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [3437fc1ab6](https://linux-hardware.org/?probe=3437fc1ab6) | Feb 12, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [f08ce9bd47](https://linux-hardware.org/?probe=f08ce9bd47) | Jan 09, 2019 |
| Dell          | Inspiron 1720               | Notebook    | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | Notebook    | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | Notebook    | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | Notebook    | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | Notebook    | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Dell          | 0WK833                      | Desktop     | [17e742f811](https://linux-hardware.org/?probe=17e742f811) | Jul 11, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Dell          | 0WK833                      | Desktop     | [d118bf168b](https://linux-hardware.org/?probe=d118bf168b) | Jun 28, 2018 |
| Dell          | 0WK833                      | Desktop     | [0e39368786](https://linux-hardware.org/?probe=0e39368786) | Jun 28, 2018 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [c401108ba6](https://linux-hardware.org/?probe=c401108ba6) | Jun 20, 2018 |
| Acer          | Aspire V5-552G              | Notebook    | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Gigabyte      | H55M-D2H                    | Desktop     | [e4e92393a0](https://linux-hardware.org/?probe=e4e92393a0) | Mar 08, 2018 |
| Dell          | XPS MXC062                  | Notebook    | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | Notebook    | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [f4d998043d](https://linux-hardware.org/?probe=f4d998043d) | Jan 29, 2018 |
| ASUSTek       | K73BE                       | Notebook    | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| ASUSTek       | A88XM-A                     | Desktop     | [f7b8e36550](https://linux-hardware.org/?probe=f7b8e36550) | Jan 21, 2018 |
| Acer          | F671CR R01-C0               | Desktop     | [a5b92562b9](https://linux-hardware.org/?probe=a5b92562b9) | Dec 26, 2017 |
| MSI           | MS-7519                     | Desktop     | [81563b0ef8](https://linux-hardware.org/?probe=81563b0ef8) | Nov 18, 2017 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | Notebook    | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| MSI           | MS-7519                     | Desktop     | [5e4728fda0](https://linux-hardware.org/?probe=5e4728fda0) | Sep 17, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | Notebook    | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | Notebook    | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| ASRock        | G31M-GS                     | Desktop     | [7a4eee4480](https://linux-hardware.org/?probe=7a4eee4480) | May 31, 2017 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [bfab333807](https://linux-hardware.org/?probe=bfab333807) | May 03, 2017 |
| Acer          | EG31M R01-A2                | Desktop     | [018dafc2d0](https://linux-hardware.org/?probe=018dafc2d0) | Apr 27, 2017 |
| eMachines     | Unknown                     | Notebook    | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | Notebook    | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | F9S                         | Notebook    | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | P5Q                         | Desktop     | [26e2520232](https://linux-hardware.org/?probe=26e2520232) | Nov 11, 2016 |
| ASUSTek       | K53SD                       | Notebook    | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | Notebook    | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | Notebook    | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 31        | 9.23%   |
| ROSA R11           | 19        | 5.65%   |
| Ubuntu 18.04       | 15        | 4.46%   |
| ROSA R10           | 12        | 3.57%   |
| ROSA R9            | 10        | 2.98%   |
| Ubuntu 22.04       | 9         | 2.68%   |
| Arch Rolling       | 9         | 2.68%   |
| KDE neon 20.04     | 8         | 2.38%   |
| Arch               | 8         | 2.38%   |
| ROSA R8.1          | 7         | 2.08%   |
| Debian 11          | 7         | 2.08%   |
| ROSA R11.1         | 6         | 1.79%   |
| OpenMandriva 23.01 | 6         | 1.79%   |
| Linux Mint 20.1    | 6         | 1.79%   |
| ROSA R8            | 5         | 1.49%   |
| Pop!_OS 21.04      | 5         | 1.49%   |
| Pop!_OS 20.10      | 5         | 1.49%   |
| Manjaro            | 5         | 1.49%   |
| Linux Mint 21      | 5         | 1.49%   |
| Linux Mint 20.3    | 5         | 1.49%   |
| Fedora 37          | 5         | 1.49%   |
| Xubuntu 20.04      | 4         | 1.19%   |
| Ubuntu 19.10       | 4         | 1.19%   |
| ROSA 12.3          | 4         | 1.19%   |
| ROSA 12.2          | 4         | 1.19%   |
| Pop!_OS 22.04      | 4         | 1.19%   |
| OpenMandriva 4.50  | 4         | 1.19%   |
| OpenMandriva 4.3   | 4         | 1.19%   |
| Linux Mint 19      | 4         | 1.19%   |
| Debian Testing     | 4         | 1.19%   |
| ArcoLinux Rolling  | 4         | 1.19%   |
| ROSA 12.1          | 3         | 0.89%   |
| OpenMandriva 4.2   | 3         | 0.89%   |
| Linux Mint 20.2    | 3         | 0.89%   |
| Linux Mint 20      | 3         | 0.89%   |
| Linux Mint 19.3    | 3         | 0.89%   |
| Linux Mint 18.3    | 3         | 0.89%   |
| Fedora 35          | 3         | 0.89%   |
| Fedora 30          | 3         | 0.89%   |
| Ubuntu 21.10       | 2         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 69        | 22.77%  |
| ROSA          | 53        | 17.49%  |
| Linux Mint    | 33        | 10.89%  |
| OpenMandriva  | 17        | 5.61%   |
| Arch          | 17        | 5.61%   |
| Fedora        | 16        | 5.28%   |
| Pop!_OS       | 15        | 4.95%   |
| Debian        | 12        | 3.96%   |
| Manjaro       | 10        | 3.3%    |
| KDE neon      | 10        | 3.3%    |
| Xubuntu       | 6         | 1.98%   |
| ArcoLinux     | 5         | 1.65%   |
| openSUSE      | 3         | 0.99%   |
| Kubuntu       | 3         | 0.99%   |
| Kali          | 3         | 0.99%   |
| Garuda Linux  | 3         | 0.99%   |
| Endless       | 3         | 0.99%   |
| Elementary    | 3         | 0.99%   |
| Ubuntu Unity  | 2         | 0.66%   |
| SteamOS       | 2         | 0.66%   |
| Lubuntu       | 2         | 0.66%   |
| EndeavourOS   | 2         | 0.66%   |
| Clear Linux   | 2         | 0.66%   |
| Zorin         | 1         | 0.33%   |
| Void Linux    | 1         | 0.33%   |
| Ubuntu MATE   | 1         | 0.33%   |
| Ubuntu Budgie | 1         | 0.33%   |
| Solus         | 1         | 0.33%   |
| Puppy         | 1         | 0.33%   |
| Peppermint    | 1         | 0.33%   |
| Parrot        | 1         | 0.33%   |
| NixOS         | 1         | 0.33%   |
| MX            | 1         | 0.33%   |
| LMDE          | 1         | 0.33%   |
| GNOME OS      | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 10        | 2.72%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 9         | 2.45%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 8         | 2.18%   |
| 6.1.1-desktop-1omv2290             | 6         | 1.63%   |
| 5.4.0-42-generic                   | 6         | 1.63%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 1.36%   |
| 5.4.0-58-generic                   | 4         | 1.09%   |
| 5.4.0-132-generic                  | 4         | 1.09%   |
| 5.4.0-122-generic                  | 4         | 1.09%   |
| 5.16.7-desktop-1omv4003            | 4         | 1.09%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 4         | 1.09%   |
| 5.8.0-7630-generic                 | 3         | 0.82%   |
| 5.4.83-generic-2rosa-x86_64        | 3         | 0.82%   |
| 5.4.0-80-generic                   | 3         | 0.82%   |
| 5.4.0-66-generic                   | 3         | 0.82%   |
| 5.4.0-54-generic                   | 3         | 0.82%   |
| 5.4.0-52-generic                   | 3         | 0.82%   |
| 5.15.0-58-generic                  | 3         | 0.82%   |
| 5.13.0-25-generic                  | 3         | 0.82%   |
| 5.12.4-desktop-1omv4050            | 3         | 0.82%   |
| 5.10.14-desktop-1omv4002           | 3         | 0.82%   |
| 5.0.0-37-generic                   | 3         | 0.82%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 0.82%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 0.82%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 0.82%   |
| 5.8.0-48-generic                   | 2         | 0.54%   |
| 5.8.0-25-generic                   | 2         | 0.54%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.54%   |
| 5.4.0-67-generic                   | 2         | 0.54%   |
| 5.4.0-26-generic                   | 2         | 0.54%   |
| 5.4.0-100-generic                  | 2         | 0.54%   |
| 5.3.0-23-generic                   | 2         | 0.54%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 2         | 0.54%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 2         | 0.54%   |
| 5.15.0-60-generic                  | 2         | 0.54%   |
| 5.15.0-57-generic                  | 2         | 0.54%   |
| 5.15.0-56-generic                  | 2         | 0.54%   |
| 5.15.0-53-generic                  | 2         | 0.54%   |
| 5.15.0-46-generic                  | 2         | 0.54%   |
| 5.13.6-arch1-1                     | 2         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 14.7%   |
| 4.15.0  | 32        | 9.22%   |
| 5.15.0  | 19        | 5.48%   |
| 5.13.0  | 15        | 4.32%   |
| 5.8.0   | 14        | 4.03%   |
| 5.11.0  | 14        | 4.03%   |
| 4.9.20  | 11        | 3.17%   |
| 5.3.0   | 10        | 2.88%   |
| 5.10.0  | 8         | 2.31%   |
| 4.9.60  | 8         | 2.31%   |
| 6.1.1   | 7         | 2.02%   |
| 5.0.0   | 6         | 1.73%   |
| 5.10.74 | 5         | 1.44%   |
| 4.18.0  | 5         | 1.44%   |
| 5.16.7  | 4         | 1.15%   |
| 4.9.155 | 4         | 1.15%   |
| 4.1.34  | 4         | 1.15%   |
| 5.4.83  | 3         | 0.86%   |
| 5.19.0  | 3         | 0.86%   |
| 5.17.1  | 3         | 0.86%   |
| 5.14.0  | 3         | 0.86%   |
| 5.12.4  | 3         | 0.86%   |
| 5.10.14 | 3         | 0.86%   |
| 4.9.41  | 3         | 0.86%   |
| 6.0.9   | 2         | 0.58%   |
| 5.9.0   | 2         | 0.58%   |
| 5.4.72  | 2         | 0.58%   |
| 5.4.32  | 2         | 0.58%   |
| 5.17.5  | 2         | 0.58%   |
| 5.16.15 | 2         | 0.58%   |
| 5.15.79 | 2         | 0.58%   |
| 5.15.75 | 2         | 0.58%   |
| 5.13.6  | 2         | 0.58%   |
| 5.13.12 | 2         | 0.58%   |
| 5.12.14 | 2         | 0.58%   |
| 4.9.9   | 2         | 0.58%   |
| 4.9.76  | 2         | 0.58%   |
| 4.9.124 | 2         | 0.58%   |
| 4.4.0   | 2         | 0.58%   |
| 4.10.0  | 2         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 59        | 17.51%  |
| 4.15    | 32        | 9.5%    |
| 5.15    | 31        | 9.2%    |
| 4.9     | 27        | 8.01%   |
| 5.10    | 21        | 6.23%   |
| 5.13    | 20        | 5.93%   |
| 5.8     | 18        | 5.34%   |
| 5.11    | 18        | 5.34%   |
| 6.1     | 12        | 3.56%   |
| 6.0     | 10        | 2.97%   |
| 5.3     | 10        | 2.97%   |
| 5.16    | 9         | 2.67%   |
| 5.12    | 8         | 2.37%   |
| 5.19    | 7         | 2.08%   |
| 5.17    | 6         | 1.78%   |
| 5.0     | 6         | 1.78%   |
| 5.18    | 5         | 1.48%   |
| 5.14    | 5         | 1.48%   |
| 4.18    | 5         | 1.48%   |
| 4.1     | 5         | 1.48%   |
| 5.9     | 4         | 1.19%   |
| 5.5     | 3         | 0.89%   |
| 5.2     | 3         | 0.89%   |
| 5.6     | 2         | 0.59%   |
| 4.4     | 2         | 0.59%   |
| 4.19    | 2         | 0.59%   |
| 4.10    | 2         | 0.59%   |
| 6.2     | 1         | 0.3%    |
| 5.7     | 1         | 0.3%    |
| 4.8     | 1         | 0.3%    |
| 4.20    | 1         | 0.3%    |
| 4.13    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 275       | 94.83%  |
| i686    | 13        | 4.48%   |
| aarch64 | 2         | 0.69%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 104       | 33.33%  |
| KDE5       | 63        | 20.19%  |
| KDE4       | 34        | 10.9%   |
| Unknown    | 30        | 9.62%   |
| XFCE       | 21        | 6.73%   |
| X-Cinnamon | 16        | 5.13%   |
| MATE       | 14        | 4.49%   |
| KDE        | 9         | 2.88%   |
| LXQt       | 4         | 1.28%   |
| Cinnamon   | 4         | 1.28%   |
| Budgie     | 4         | 1.28%   |
| Pantheon   | 3         | 0.96%   |
| Unity      | 2         | 0.64%   |
| Deepin     | 2         | 0.64%   |
| sway       | 1         | 0.32%   |
| LXDE       | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 237       | 79.26%  |
| Wayland | 44        | 14.72%  |
| Unknown | 12        | 4.01%   |
| Tty     | 6         | 2.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 126       | 41.04%  |
| SDDM    | 55        | 17.92%  |
| GDM     | 40        | 13.03%  |
| KDM     | 34        | 11.07%  |
| LightDM | 22        | 7.17%   |
| TDM     | 15        | 4.89%   |
| GDM3    | 12        | 3.91%   |
| SLiM    | 1         | 0.33%   |
| MDM     | 1         | 0.33%   |
| LDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 136       | 44.59%  |
| Unknown     | 65        | 21.31%  |
| lv_LV       | 40        | 13.11%  |
| ru_RU       | 33        | 10.82%  |
| en_GB       | 15        | 4.92%   |
| C           | 7         | 2.3%    |
| ru_RU.UTF_8 | 2         | 0.66%   |
| de_DE       | 2         | 0.66%   |
| POSIX       | 1         | 0.33%   |
| osa_US      | 1         | 0.33%   |
| fr_FR       | 1         | 0.33%   |
| en_AG       | 1         | 0.33%   |
| cv_RU       | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 171       | 58.36%  |
| EFI  | 122       | 41.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 220       | 73.09%  |
| Btrfs   | 28        | 9.3%    |
| Unknown | 28        | 9.3%    |
| Overlay | 21        | 6.98%   |
| Zfs     | 1         | 0.33%   |
| Xfs     | 1         | 0.33%   |
| Ext3    | 1         | 0.33%   |
| Aufs    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 139       | 45.87%  |
| GPT     | 100       | 33%     |
| MBR     | 64        | 21.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 264       | 86.84%  |
| Yes       | 40        | 13.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 219       | 73%     |
| Yes       | 81        | 27%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 57        | 19.66%  |
| Lenovo                  | 48        | 16.55%  |
| Hewlett-Packard         | 37        | 12.76%  |
| Dell                    | 33        | 11.38%  |
| Acer                    | 26        | 8.97%   |
| Gigabyte Technology     | 21        | 7.24%   |
| MSI                     | 18        | 6.21%   |
| ASRock                  | 9         | 3.1%    |
| Toshiba                 | 6         | 2.07%   |
| Samsung Electronics     | 4         | 1.38%   |
| Intel                   | 4         | 1.38%   |
| Fujitsu Siemens         | 4         | 1.38%   |
| Raspberry Pi Foundation | 2         | 0.69%   |
| HUAWEI                  | 2         | 0.69%   |
| Apple                   | 2         | 0.69%   |
| Wortmann AG             | 1         | 0.34%   |
| Valve                   | 1         | 0.34%   |
| Timi                    | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| Razer                   | 1         | 0.34%   |
| Quanta                  | 1         | 0.34%   |
| Packard Bell            | 1         | 0.34%   |
| IBM                     | 1         | 0.34%   |
| Hardkernel              | 1         | 0.34%   |
| Fujitsu                 | 1         | 0.34%   |
| Foxconn                 | 1         | 0.34%   |
| eMachines               | 1         | 0.34%   |
| Chuwi                   | 1         | 0.34%   |
| Biostar                 | 1         | 0.34%   |
| Advent                  | 1         | 0.34%   |
| Acidanthera             | 1         | 0.34%   |
| ABIT                    | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 5         | 1.72%   |
| HP EliteBook 840 G3                                   | 3         | 1.03%   |
| Toshiba Satellite C660                                | 2         | 0.69%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.69%   |
| MSI MS-7721                                           | 2         | 0.69%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.69%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.69%   |
| HP G62                                                | 2         | 0.69%   |
| HP EliteBook 8440p                                    | 2         | 0.69%   |
| HP 250 G6 Notebook PC                                 | 2         | 0.69%   |
| Gigabyte G33M-S2                                      | 2         | 0.69%   |
| Gigabyte B550 AORUS PRO V2                            | 2         | 0.69%   |
| Gigabyte 946GMX-S2                                    | 2         | 0.69%   |
| Dell OptiPlex 7020                                    | 2         | 0.69%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.69%   |
| ASUS X553MA                                           | 2         | 0.69%   |
| ASUS X551MA                                           | 2         | 0.69%   |
| Wortmann AG CR700                                     | 1         | 0.34%   |
| Valve Jupiter                                         | 1         | 0.34%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.34%   |
| Toshiba Satellite L750                                | 1         | 0.34%   |
| Toshiba Satellite L350                                | 1         | 0.34%   |
| Toshiba Satellite C50D-B                              | 1         | 0.34%   |
| Timi A35S                                             | 1         | 0.34%   |
| Sony VPCCW2S8E                                        | 1         | 0.34%   |
| Samsung R528/R728                                     | 1         | 0.34%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.34%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.34%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.34%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.34%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.34%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.34%   |
| MSI MS-7C52                                           | 1         | 0.34%   |
| MSI MS-7B46                                           | 1         | 0.34%   |
| MSI MS-7B33                                           | 1         | 0.34%   |
| MSI MS-7996                                           | 1         | 0.34%   |
| MSI MS-7850                                           | 1         | 0.34%   |
| MSI MS-7846                                           | 1         | 0.34%   |
| MSI MS-7758                                           | 1         | 0.34%   |
| MSI MS-7693                                           | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 24        | 8.28%   |
| Acer Aspire           | 16        | 5.52%   |
| HP EliteBook          | 11        | 3.79%   |
| Dell Inspiron         | 11        | 3.79%   |
| Lenovo IdeaPad        | 10        | 3.45%   |
| Dell Latitude         | 10        | 3.45%   |
| Dell OptiPlex         | 7         | 2.41%   |
| Toshiba Satellite     | 6         | 2.07%   |
| HP ProBook            | 5         | 1.72%   |
| HP Pavilion           | 5         | 1.72%   |
| ASUS PRIME            | 5         | 1.72%   |
| ASUS All              | 5         | 1.72%   |
| Lenovo Legion         | 4         | 1.38%   |
| ASUS VivoBook         | 4         | 1.38%   |
| HP 250                | 3         | 1.03%   |
| ASUS TUF              | 3         | 1.03%   |
| ASUS ROG              | 3         | 1.03%   |
| RPi Raspberry         | 2         | 0.69%   |
| MSI MS-7721           | 2         | 0.69%   |
| Lenovo Yoga           | 2         | 0.69%   |
| HP Laptop             | 2         | 0.69%   |
| HP G62                | 2         | 0.69%   |
| HP Compaq             | 2         | 0.69%   |
| Gigabyte G33M-S2      | 2         | 0.69%   |
| Gigabyte B550         | 2         | 0.69%   |
| Gigabyte 946GMX-S2    | 2         | 0.69%   |
| Fujitsu Siemens AMILO | 2         | 0.69%   |
| Dell XPS              | 2         | 0.69%   |
| ASUS ZenBook          | 2         | 0.69%   |
| ASUS X553MA           | 2         | 0.69%   |
| ASUS X551MA           | 2         | 0.69%   |
| ASUS P5Q              | 2         | 0.69%   |
| Acer Nitro            | 2         | 0.69%   |
| Acer Extensa          | 2         | 0.69%   |
| Wortmann AG CR700     | 1         | 0.34%   |
| Valve Jupiter         | 1         | 0.34%   |
| Timi A35S             | 1         | 0.34%   |
| Sony VPCCW2S8E        | 1         | 0.34%   |
| Samsung R528          | 1         | 0.34%   |
| Samsung 355V4C        | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 32        | 11.03%  |
| 2019    | 27        | 9.31%   |
| 2014    | 20        | 6.9%    |
| 2012    | 20        | 6.9%    |
| 2008    | 20        | 6.9%    |
| 2007    | 20        | 6.9%    |
| 2018    | 19        | 6.55%   |
| 2020    | 17        | 5.86%   |
| 2015    | 17        | 5.86%   |
| 2011    | 17        | 5.86%   |
| 2009    | 17        | 5.86%   |
| 2010    | 15        | 5.17%   |
| 2017    | 14        | 4.83%   |
| 2016    | 11        | 3.79%   |
| 2021    | 10        | 3.45%   |
| 2006    | 6         | 2.07%   |
| 2022    | 5         | 1.72%   |
| Unknown | 2         | 0.69%   |
| 2004    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 188       | 64.83%  |
| Desktop        | 93        | 32.07%  |
| Convertible    | 3         | 1.03%   |
| System on chip | 2         | 0.69%   |
| Mini pc        | 2         | 0.69%   |
| All in one     | 1         | 0.34%   |
| Server         | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 274       | 93.52%  |
| Enabled  | 19        | 6.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 289       | 99.66%  |
| Yes  | 1         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 78        | 26.44%  |
| 4.01-8.0    | 71        | 24.07%  |
| 8.01-16.0   | 49        | 16.61%  |
| 16.01-24.0  | 40        | 13.56%  |
| 32.01-64.0  | 23        | 7.8%    |
| 1.01-2.0    | 14        | 4.75%   |
| 2.01-3.0    | 12        | 4.07%   |
| 24.01-32.0  | 5         | 1.69%   |
| 0.51-1.0    | 2         | 0.68%   |
| 64.01-256.0 | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 111       | 33.53%  |
| 2.01-3.0   | 79        | 23.87%  |
| 0.51-1.0   | 49        | 14.8%   |
| 4.01-8.0   | 41        | 12.39%  |
| 3.01-4.0   | 34        | 10.27%  |
| 8.01-16.0  | 12        | 3.63%   |
| 16.01-24.0 | 3         | 0.91%   |
| 24.01-32.0 | 1         | 0.3%    |
| 0.01-0.5   | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 186       | 62%     |
| 2      | 74        | 24.67%  |
| 3      | 22        | 7.33%   |
| 4      | 11        | 3.67%   |
| 6      | 2         | 0.67%   |
| 5      | 2         | 0.67%   |
| 0      | 2         | 0.67%   |
| 7      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 171       | 57.58%  |
| Yes       | 126       | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 91.1%   |
| No        | 26        | 8.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 76.29%  |
| No        | 69        | 23.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 56.8%   |
| No        | 127       | 43.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Latvia  | 290       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Riga                    | 215       | 69.81%  |
| Jelgava                 | 10        | 3.25%   |
| Liepāja                | 8         | 2.6%    |
| Daugavpils              | 8         | 2.6%    |
| Ventspils               | 6         | 1.95%   |
| Jūrmala                | 5         | 1.62%   |
| Adazi                   | 5         | 1.62%   |
| Salaspils               | 3         | 0.97%   |
| Limbaži                | 3         | 0.97%   |
| Jaunmarupe              | 3         | 0.97%   |
| Valmiera                | 2         | 0.65%   |
| Talsi                   | 2         | 0.65%   |
| Saulkrasti              | 2         | 0.65%   |
| Rēzekne                | 2         | 0.65%   |
| Malpils                 | 2         | 0.65%   |
| Kuldīga                | 2         | 0.65%   |
| Jēkabpils              | 2         | 0.65%   |
| Iecava                  | 2         | 0.65%   |
| Cēsis                  | 2         | 0.65%   |
| Zvejniekciems           | 1         | 0.32%   |
| Ulbroka                 | 1         | 0.32%   |
| Tukums                  | 1         | 0.32%   |
| Tiraine                 | 1         | 0.32%   |
| Saldus                  | 1         | 0.32%   |
| Ragana                  | 1         | 0.32%   |
| Pļaviņas              | 1         | 0.32%   |
| Ogre                    | 1         | 0.32%   |
| Lizums                  | 1         | 0.32%   |
| Lielvārde              | 1         | 0.32%   |
| Ķekava                 | 1         | 0.32%   |
| Jēkabpils Municipality | 1         | 0.32%   |
| Gulbene                 | 1         | 0.32%   |
| Garkalne                | 1         | 0.32%   |
| Garciems                | 1         | 0.32%   |
| Dreilini                | 1         | 0.32%   |
| Dobele                  | 1         | 0.32%   |
| Carnikava               | 1         | 0.32%   |
| Bukulti                 | 1         | 0.32%   |
| Brankas                 | 1         | 0.32%   |
| Bauska                  | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 73        | 98     | 17.72%  |
| Samsung Electronics          | 66        | 105    | 16.02%  |
| WDC                          | 65        | 100    | 15.78%  |
| Kingston                     | 39        | 55     | 9.47%   |
| Toshiba                      | 28        | 32     | 6.8%    |
| Hitachi                      | 16        | 21     | 3.88%   |
| Crucial                      | 14        | 21     | 3.4%    |
| Unknown                      | 10        | 14     | 2.43%   |
| HGST                         | 9         | 17     | 2.18%   |
| Micron Technology            | 8         | 8      | 1.94%   |
| Intel                        | 8         | 16     | 1.94%   |
| A-DATA Technology            | 8         | 10     | 1.94%   |
| SK hynix                     | 7         | 7      | 1.7%    |
| Sandisk                      | 7         | 14     | 1.7%    |
| Patriot                      | 5         | 11     | 1.21%   |
| KIOXIA                       | 4         | 5      | 0.97%   |
| OCZ                          | 3         | 4      | 0.73%   |
| GOODRAM                      | 3         | 6      | 0.73%   |
| SPCC                         | 2         | 4      | 0.49%   |
| Phison                       | 2         | 2      | 0.49%   |
| Netac                        | 2         | 2      | 0.49%   |
| LITEON                       | 2         | 2      | 0.49%   |
| Intenso                      | 2         | 2      | 0.49%   |
| China                        | 2         | 2      | 0.49%   |
| XPG                          | 1         | 1      | 0.24%   |
| Verbatim                     | 1         | 1      | 0.24%   |
| USB                          | 1         | 1      | 0.24%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.24%   |
| Silicon Motion               | 1         | 1      | 0.24%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.24%   |
| Realtek Semiconductor        | 1         | 1      | 0.24%   |
| Realtek                      | 1         | 1      | 0.24%   |
| PNY                          | 1         | 1      | 0.24%   |
| Plextor                      | 1         | 1      | 0.24%   |
| Mushkin                      | 1         | 2      | 0.24%   |
| Maxtor                       | 1         | 1      | 0.24%   |
| LITEONIT                     | 1         | 1      | 0.24%   |
| Lite-On Technology           | 1         | 1      | 0.24%   |
| Lexar                        | 1         | 1      | 0.24%   |
| KIOXIA-EXCERIA               | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 10        | 2.23%   |
| Seagate ST500LT012-1DG142 500GB  | 6         | 1.34%   |
| Samsung SSD 850 EVO 500GB        | 6         | 1.34%   |
| Samsung SSD 860 EVO 500GB        | 5         | 1.11%   |
| Kingston SV300S37A120G 120GB SSD | 5         | 1.11%   |
| Toshiba MQ01ABF050 500GB         | 4         | 0.89%   |
| Seagate ST1000LM048-2E7172 1TB   | 4         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB   | 4         | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB   | 4         | 0.89%   |
| Samsung SSD 970 EVO Plus 500GB   | 4         | 0.89%   |
| Kingston SV300S37A240G 240GB SSD | 4         | 0.89%   |
| Crucial CT500MX500SSD1 500GB     | 4         | 0.89%   |
| Crucial CT1000MX500SSD1 1TB      | 4         | 0.89%   |
| WDC WD2000JD-00HBB0 200GB        | 3         | 0.67%   |
| Toshiba MQ04ABF100 1TB           | 3         | 0.67%   |
| Seagate ST500DM005 HD502HJ 500GB | 3         | 0.67%   |
| Seagate ST3500418AS 500GB        | 3         | 0.67%   |
| Samsung SSD 650 120GB            | 3         | 0.67%   |
| Samsung NVMe SSD Drive 500GB     | 3         | 0.67%   |
| Samsung NVMe SSD Drive 1TB       | 3         | 0.67%   |
| Patriot Burst 240GB SSD          | 3         | 0.67%   |
| Kingston SV300S37A60G 64GB SSD   | 3         | 0.67%   |
| Kingston SA400S37480G 480GB SSD  | 3         | 0.67%   |
| Hitachi HTS547575A9E384 752GB    | 3         | 0.67%   |
| Hitachi HTS545050B9A300 500GB    | 3         | 0.67%   |
| HGST HTS545050A7E680 500GB       | 3         | 0.67%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 2         | 0.45%   |
| WDC WD5002AALX-00J37A0 500GB     | 2         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 0.45%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2         | 0.45%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2         | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB      | 2         | 0.45%   |
| WDC WD20EARX-00PASB0 2TB         | 2         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB         | 2         | 0.45%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2         | 0.45%   |
| Unknown MMC Card  7GB            | 2         | 0.45%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.45%   |
| Toshiba MQ01ABD050 500GB         | 2         | 0.45%   |
| Toshiba MK8034GSX 80GB           | 2         | 0.45%   |
| Toshiba MK6465GSX 640GB          | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 98     | 37.24%  |
| WDC                 | 56        | 86     | 28.57%  |
| Toshiba             | 23        | 27     | 11.73%  |
| Hitachi             | 16        | 21     | 8.16%   |
| Samsung Electronics | 15        | 20     | 7.65%   |
| HGST                | 9         | 17     | 4.59%   |
| USB                 | 1         | 1      | 0.51%   |
| Maxtor              | 1         | 1      | 0.51%   |
| IBM/Hitachi         | 1         | 1      | 0.51%   |
| Fujitsu             | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 36        | 51     | 26.28%  |
| Samsung Electronics | 33        | 50     | 24.09%  |
| Crucial             | 14        | 21     | 10.22%  |
| A-DATA Technology   | 8         | 10     | 5.84%   |
| WDC                 | 5         | 6      | 3.65%   |
| Patriot             | 5         | 11     | 3.65%   |
| SanDisk             | 3         | 4      | 2.19%   |
| OCZ                 | 3         | 4      | 2.19%   |
| Micron Technology   | 3         | 3      | 2.19%   |
| Intel               | 3         | 8      | 2.19%   |
| GOODRAM             | 3         | 6      | 2.19%   |
| SPCC                | 2         | 4      | 1.46%   |
| LITEON              | 2         | 2      | 1.46%   |
| Intenso             | 2         | 2      | 1.46%   |
| China               | 2         | 2      | 1.46%   |
| Verbatim            | 1         | 1      | 0.73%   |
| Toshiba             | 1         | 1      | 0.73%   |
| PNY                 | 1         | 1      | 0.73%   |
| Plextor             | 1         | 1      | 0.73%   |
| Mushkin             | 1         | 2      | 0.73%   |
| LITEONIT            | 1         | 1      | 0.73%   |
| Lexar               | 1         | 1      | 0.73%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.73%   |
| KingSpec            | 1         | 1      | 0.73%   |
| KingFast            | 1         | 2      | 0.73%   |
| Integral            | 1         | 1      | 0.73%   |
| GLOWAY              | 1         | 2      | 0.73%   |
| CHN25SATAS1         | 1         | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 166       | 273    | 45.48%  |
| SSD     | 118       | 200    | 32.33%  |
| NVMe    | 70        | 100    | 19.18%  |
| MMC     | 8         | 12     | 2.19%   |
| Unknown | 3         | 8      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 236       | 469    | 72.84%  |
| NVMe | 70        | 99     | 21.6%   |
| SAS  | 10        | 13     | 3.09%   |
| MMC  | 8         | 12     | 2.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 190       | 319    | 65.74%  |
| 0.51-1.0   | 81        | 123    | 28.03%  |
| 1.01-2.0   | 12        | 24     | 4.15%   |
| 2.01-3.0   | 3         | 4      | 1.04%   |
| 4.01-10.0  | 2         | 2      | 0.69%   |
| 3.01-4.0   | 1         | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 102       | 31.88%  |
| 251-500        | 65        | 20.31%  |
| 501-1000       | 38        | 11.88%  |
| 1001-2000      | 30        | 9.38%   |
| 51-100         | 25        | 7.81%   |
| 1-20           | 24        | 7.5%    |
| 21-50          | 12        | 3.75%   |
| 2001-3000      | 10        | 3.13%   |
| More than 3000 | 7         | 2.19%   |
| Unknown        | 7         | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 137       | 41.27%  |
| 21-50          | 47        | 14.16%  |
| 101-250        | 39        | 11.75%  |
| 51-100         | 38        | 11.45%  |
| 251-500        | 28        | 8.43%   |
| 501-1000       | 21        | 6.33%   |
| 1001-2000      | 11        | 3.31%   |
| Unknown        | 7         | 2.11%   |
| 2001-3000      | 3         | 0.9%    |
| More than 3000 | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2         | 4      | 3.45%   |
| WDC WD2000JD-00HBB0 200GB             | 2         | 4      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 3.45%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 5      | 3.45%   |
| Samsung Electronics SP2504C 250GB     | 2         | 2      | 3.45%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 5      | 3.45%   |
| Kingston SV300S37A60G 64GB SSD        | 2         | 2      | 3.45%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 3.45%   |
| A-DATA Technology SU800NS38 512GB SSD | 2         | 3      | 3.45%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1         | 1      | 1.72%   |
| WDC WD800JD-60MSA1 80GB               | 1         | 1      | 1.72%   |
| WDC WD5002AALX-00J37A0 500GB          | 1         | 1      | 1.72%   |
| WDC WD5001AALS-00L3B2 500GB           | 1         | 1      | 1.72%   |
| WDC WD5001AALS-00E3A0 500GB           | 1         | 1      | 1.72%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 1.72%   |
| WDC WD3200BEVT-75ZCT0 320GB           | 1         | 4      | 1.72%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1         | 1      | 1.72%   |
| WDC WD1600BEVS-60RST0 160GB           | 1         | 1      | 1.72%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1         | 1      | 1.72%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.72%   |
| Toshiba MK8034GSX 80GB                | 1         | 1      | 1.72%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.72%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 1.72%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.72%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.72%   |
| Seagate ST9500325AS 500GB             | 1         | 3      | 1.72%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.72%   |
| Seagate ST3500820AS 500GB             | 1         | 1      | 1.72%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 1.72%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 1.72%   |
| Seagate ST340016A 40GB                | 1         | 1      | 1.72%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 1.72%   |
| Seagate ST3250312AS 250GB             | 1         | 1      | 1.72%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.72%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.72%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 1      | 1.72%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 1.72%   |
| Samsung Electronics HN-M750MBB 752GB  | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 23     | 30.36%  |
| WDC                 | 13        | 21     | 23.21%  |
| Samsung Electronics | 6         | 9      | 10.71%  |
| HGST                | 6         | 8      | 10.71%  |
| Toshiba             | 5         | 5      | 8.93%   |
| Kingston            | 3         | 3      | 5.36%   |
| Hitachi             | 3         | 3      | 5.36%   |
| A-DATA Technology   | 2         | 3      | 3.57%   |
| CHN25SATAS1         | 1         | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 23     | 35.42%  |
| WDC                 | 12        | 20     | 25%     |
| HGST                | 6         | 8      | 12.5%   |
| Toshiba             | 5         | 5      | 10.42%  |
| Samsung Electronics | 5         | 8      | 10.42%  |
| Hitachi             | 3         | 3      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 67     | 83.33%  |
| SSD  | 6         | 7      | 12.5%   |
| NVMe | 2         | 2      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 142       | 271    | 44.24%  |
| Works    | 130       | 244    | 40.5%   |
| Malfunc  | 47        | 76     | 14.64%  |
| Failed   | 2         | 2      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 215       | 60.22%  |
| AMD                              | 47        | 13.17%  |
| Samsung Electronics              | 27        | 7.56%   |
| SanDisk                          | 10        | 2.8%    |
| SK hynix                         | 7         | 1.96%   |
| Nvidia                           | 7         | 1.96%   |
| JMicron Technology               | 7         | 1.96%   |
| Micron Technology                | 5         | 1.4%    |
| Marvell Technology Group         | 5         | 1.4%    |
| KIOXIA                           | 5         | 1.4%    |
| Toshiba America Info Systems     | 3         | 0.84%   |
| Kingston Technology Company      | 3         | 0.84%   |
| ADATA Technology                 | 3         | 0.84%   |
| Union Memory (Shenzhen)          | 2         | 0.56%   |
| Silicon Motion                   | 2         | 0.56%   |
| Phison Electronics               | 2         | 0.56%   |
| ASMedia Technology               | 2         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Silicon Image                    | 1         | 0.28%   |
| Shenzhen Longsys Electronics     | 1         | 0.28%   |
| Realtek Semiconductor            | 1         | 0.28%   |
| Lite-On Technology               | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 7.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 4.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 3.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 13        | 3.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 2.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 2.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 9         | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 1.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.44%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 1.2%    |
| Micron Non-Volatile memory controller                                          | 5         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.2%    |
| JMicron JMB368 IDE controller                                                  | 5         | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 5         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.2%    |
| AMD FCH IDE Controller                                                         | 5         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.96%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 0.96%   |
| Nvidia MCP61 SATA Controller                                                   | 4         | 0.96%   |
| Nvidia MCP61 IDE                                                               | 4         | 0.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 0.96%   |
| Intel SSD 660P Series                                                          | 4         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4         | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 4         | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 220       | 60.11%  |
| NVMe | 73        | 19.95%  |
| IDE  | 59        | 16.12%  |
| RAID | 14        | 3.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 226       | 77.93%  |
| AMD    | 62        | 21.38%  |
| ARM    | 2         | 0.69%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 1.38%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.03%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.03%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 1.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.03%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 1.03%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.03%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.03%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.03%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.69%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2         | 0.69%   |
| Intel Pentium D CPU 3.40GHz                   | 2         | 0.69%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.69%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.69%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.69%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.69%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.69%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.69%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.69%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.69%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 22.41%  |
| Intel Core i7           | 42        | 14.48%  |
| Intel Core i3           | 30        | 10.34%  |
| Intel Core 2 Duo        | 23        | 7.93%   |
| Other                   | 15        | 5.17%   |
| AMD Ryzen 5             | 15        | 5.17%   |
| Intel Celeron           | 14        | 4.83%   |
| Intel Pentium           | 9         | 3.1%    |
| AMD Ryzen 7             | 9         | 3.1%    |
| AMD A8                  | 7         | 2.41%   |
| Intel Pentium Dual-Core | 6         | 2.07%   |
| Intel Pentium Dual      | 6         | 2.07%   |
| Intel Pentium D         | 5         | 1.72%   |
| Intel Core 2            | 5         | 1.72%   |
| Intel Core 2 Quad       | 4         | 1.38%   |
| Intel Genuine           | 3         | 1.03%   |
| AMD FX                  | 3         | 1.03%   |
| AMD Athlon 64 X2        | 3         | 1.03%   |
| AMD A10                 | 3         | 1.03%   |
| Intel Xeon              | 2         | 0.69%   |
| AMD Turion 64 X2 Mobile | 2         | 0.69%   |
| AMD Ryzen 9             | 2         | 0.69%   |
| AMD Ryzen 7 PRO         | 2         | 0.69%   |
| AMD Ryzen 3             | 2         | 0.69%   |
| AMD E1                  | 2         | 0.69%   |
| AMD Athlon II X2        | 2         | 0.69%   |
| Intel Pentium 4         | 1         | 0.34%   |
| Intel Atom              | 1         | 0.34%   |
| AMD Ryzen Threadripper  | 1         | 0.34%   |
| AMD Ryzen 5 PRO         | 1         | 0.34%   |
| AMD E2                  | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |
| AMD C-70                | 1         | 0.34%   |
| AMD Athlon II X3        | 1         | 0.34%   |
| AMD Athlon              | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 156       | 53.42%  |
| 4       | 88        | 30.14%  |
| 6       | 18        | 6.16%   |
| 8       | 11        | 3.77%   |
| 1       | 7         | 2.4%    |
| 3       | 4         | 1.37%   |
| 16      | 2         | 0.68%   |
| Unknown | 2         | 0.68%   |
| 24      | 1         | 0.34%   |
| 14      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 289       | 99.66%  |
| Unknown | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 174       | 59.59%  |
| 1       | 116       | 39.73%  |
| Unknown | 2         | 0.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 286       | 98.62%  |
| Unknown        | 3         | 1.03%   |
| 32-bit         | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 19.53%  |
| 0x306c3    | 16        | 5.39%   |
| 0x306a9    | 15        | 5.05%   |
| 0x1067a    | 15        | 5.05%   |
| 0x206a7    | 14        | 4.71%   |
| 0x6fd      | 12        | 4.04%   |
| 0x406e3    | 11        | 3.7%    |
| 0x906ea    | 10        | 3.37%   |
| 0x30678    | 8         | 2.69%   |
| 0x20655    | 8         | 2.69%   |
| 0x10676    | 7         | 2.36%   |
| 0x06001119 | 7         | 2.36%   |
| 0x806ec    | 6         | 2.02%   |
| 0x306d4    | 6         | 2.02%   |
| 0x806c1    | 5         | 1.68%   |
| 0x506e3    | 5         | 1.68%   |
| 0x40651    | 5         | 1.68%   |
| 0x906e9    | 4         | 1.35%   |
| 0x08701021 | 4         | 1.35%   |
| 0x08108102 | 4         | 1.35%   |
| 0xa0652    | 3         | 1.01%   |
| 0x806ea    | 3         | 1.01%   |
| 0x806e9    | 3         | 1.01%   |
| 0x6fb      | 3         | 1.01%   |
| 0x6f6      | 3         | 1.01%   |
| 0x20652    | 3         | 1.01%   |
| 0x05000119 | 3         | 1.01%   |
| 0xf65      | 2         | 0.67%   |
| 0xf47      | 2         | 0.67%   |
| 0x906ed    | 2         | 0.67%   |
| 0x706a1    | 2         | 0.67%   |
| 0x6fa      | 2         | 0.67%   |
| 0x6f2      | 2         | 0.67%   |
| 0x406c3    | 2         | 0.67%   |
| 0x106e5    | 2         | 0.67%   |
| 0x0a50000c | 2         | 0.67%   |
| 0x0a201009 | 2         | 0.67%   |
| 0x08600103 | 2         | 0.67%   |
| 0x08108109 | 2         | 0.67%   |
| 0x06003106 | 2         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 12.41%  |
| Haswell          | 27        | 9.31%   |
| Core             | 25        | 8.62%   |
| Penryn           | 22        | 7.59%   |
| Skylake          | 19        | 6.55%   |
| IvyBridge        | 19        | 6.55%   |
| SandyBridge      | 18        | 6.21%   |
| Zen 2            | 13        | 4.48%   |
| Westmere         | 13        | 4.48%   |
| Silvermont       | 12        | 4.14%   |
| Piledriver       | 9         | 3.1%    |
| Zen+             | 8         | 2.76%   |
| Zen 3            | 7         | 2.41%   |
| Unknown          | 7         | 2.41%   |
| TigerLake        | 6         | 2.07%   |
| NetBurst         | 6         | 2.07%   |
| K8 Hammer        | 6         | 2.07%   |
| Broadwell        | 6         | 2.07%   |
| Zen              | 3         | 1.03%   |
| Nehalem          | 3         | 1.03%   |
| K10              | 3         | 1.03%   |
| Goldmont plus    | 3         | 1.03%   |
| CometLake        | 3         | 1.03%   |
| Bobcat           | 3         | 1.03%   |
| Steamroller      | 2         | 0.69%   |
| Puma             | 2         | 0.69%   |
| IceLake          | 2         | 0.69%   |
| Excavator        | 2         | 0.69%   |
| P6               | 1         | 0.34%   |
| Jaguar           | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |
| Bulldozer        | 1         | 0.34%   |
| Alderlake Hybrid | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 166       | 48.4%   |
| Nvidia | 103       | 30.03%  |
| AMD    | 74        | 21.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 13        | 3.63%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 13        | 3.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 12        | 3.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 11        | 3.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 10        | 2.79%   |
| Intel Core Processor Integrated Graphics Controller                           | 9         | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 8         | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.96%   |
| AMD Renoir                                                                    | 7         | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 6         | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 1.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 5         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 5         | 1.4%    |
| Intel HD Graphics 5500                                                        | 5         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 4         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.12%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 3         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3         | 0.84%   |
| Intel UHD Graphics 620                                                        | 3         | 0.84%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 0.84%   |
| Intel HD Graphics 620                                                         | 3         | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3         | 0.84%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 3         | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 3         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 2         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 2         | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2         | 0.56%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 0.56%   |
| Nvidia GF106 [GeForce GTS 450]                                                | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 116       | 39.73%  |
| 1 x Nvidia     | 60        | 20.55%  |
| 1 x AMD        | 54        | 18.49%  |
| Intel + Nvidia | 39        | 13.36%  |
| 2 x AMD        | 8         | 2.74%   |
| Intel + AMD    | 8         | 2.74%   |
| AMD + Nvidia   | 3         | 1.03%   |
| Other          | 2         | 0.68%   |
| 2 x Nvidia     | 1         | 0.34%   |
| 2 x Intel      | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 229       | 76.59%  |
| Proprietary | 57        | 19.06%  |
| Unknown     | 13        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 46.67%  |
| 0.01-0.5   | 47        | 15.67%  |
| 1.01-2.0   | 46        | 15.33%  |
| 0.51-1.0   | 28        | 9.33%   |
| 3.01-4.0   | 20        | 6.67%   |
| 5.01-6.0   | 9         | 3%      |
| 7.01-8.0   | 7         | 2.33%   |
| 2.01-3.0   | 1         | 0.33%   |
| 16.01-24.0 | 1         | 0.33%   |
| 8.01-16.0  | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 16.45%  |
| Samsung Electronics     | 47        | 15.16%  |
| LG Display              | 34        | 10.97%  |
| BOE                     | 24        | 7.74%   |
| Dell                    | 22        | 7.1%    |
| Chimei Innolux          | 21        | 6.77%   |
| Goldstar                | 20        | 6.45%   |
| BenQ                    | 11        | 3.55%   |
| Philips                 | 9         | 2.9%    |
| Lenovo                  | 9         | 2.9%    |
| Chi Mei Optoelectronics | 7         | 2.26%   |
| Hewlett-Packard         | 6         | 1.94%   |
| Ancor Communications    | 6         | 1.94%   |
| AOC                     | 5         | 1.61%   |
| PANDA                   | 3         | 0.97%   |
| LG Electronics          | 3         | 0.97%   |
| ViewSonic               | 2         | 0.65%   |
| Unknown                 | 2         | 0.65%   |
| Sony                    | 2         | 0.65%   |
| Seiko/Epson             | 2         | 0.65%   |
| NEC Computers           | 2         | 0.65%   |
| InfoVision              | 2         | 0.65%   |
| Hitachi                 | 2         | 0.65%   |
| Arnos Instruments       | 2         | 0.65%   |
| Wacom                   | 1         | 0.32%   |
| Tianma XM               | 1         | 0.32%   |
| Sharp                   | 1         | 0.32%   |
| Quanta Display          | 1         | 0.32%   |
| Plain Tree Systems      | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| LGD                     | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| IBM                     | 1         | 0.32%   |
| HYO                     | 1         | 0.32%   |
| FUS                     | 1         | 0.32%   |
| AUS                     | 1         | 0.32%   |
| ASUSTek Computer        | 1         | 0.32%   |
| Apple                   | 1         | 0.32%   |
| ANX                     | 1         | 0.32%   |
| Acer                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.93%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.93%   |
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                     | 3         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.93%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch        | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.62%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                 | 2         | 0.62%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 2         | 0.62%   |
| LG Electronics LCD Monitor LG TV 1920x1080                               | 2         | 0.62%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                     | 2         | 0.62%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.62%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.62%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                       | 2         | 0.62%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.62%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 0.62%   |
| Dell LCD Monitor U2414H                                                  | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.62%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.62%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.62%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.62%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch                  | 2         | 0.62%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.62%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch    | 2         | 0.62%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                 | 1         | 0.31%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch            | 1         | 0.31%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch              | 1         | 0.31%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                             | 1         | 0.31%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                               | 1         | 0.31%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 101       | 34.35%  |
| 1366x768 (WXGA)    | 68        | 23.13%  |
| 1600x900 (HD+)     | 18        | 6.12%   |
| 1280x1024 (SXGA)   | 16        | 5.44%   |
| 2560x1440 (QHD)    | 14        | 4.76%   |
| 3840x2160 (4K)     | 13        | 4.42%   |
| 1280x800 (WXGA)    | 12        | 4.08%   |
| 1680x1050 (WSXGA+) | 10        | 3.4%    |
| 1440x900 (WXGA+)   | 10        | 3.4%    |
| 1920x1200 (WUXGA)  | 6         | 2.04%   |
| Unknown            | 4         | 1.36%   |
| 3440x1440          | 3         | 1.02%   |
| 2560x1080          | 3         | 1.02%   |
| 1360x768           | 3         | 1.02%   |
| 1024x768 (XGA)     | 2         | 0.68%   |
| 800x1280           | 1         | 0.34%   |
| 7680x2160          | 1         | 0.34%   |
| 4480x1440          | 1         | 0.34%   |
| 3840x1080          | 1         | 0.34%   |
| 3520x1200          | 1         | 0.34%   |
| 3456x2160          | 1         | 0.34%   |
| 3000x2000          | 1         | 0.34%   |
| 2960x1050          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 1280x960           | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 106       | 34.3%   |
| 17      | 26        | 8.41%   |
| 14      | 23        | 7.44%   |
| 24      | 21        | 6.8%    |
| 13      | 19        | 6.15%   |
| Unknown | 18        | 5.83%   |
| 27      | 17        | 5.5%    |
| 23      | 13        | 4.21%   |
| 19      | 11        | 3.56%   |
| 12      | 11        | 3.56%   |
| 22      | 6         | 1.94%   |
| 21      | 6         | 1.94%   |
| 20      | 6         | 1.94%   |
| 18      | 5         | 1.62%   |
| 34      | 4         | 1.29%   |
| 25      | 4         | 1.29%   |
| 40      | 3         | 0.97%   |
| 11      | 3         | 0.97%   |
| 35      | 2         | 0.65%   |
| 31      | 2         | 0.65%   |
| 84      | 1         | 0.32%   |
| 43      | 1         | 0.32%   |
| 33      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 144       | 47.68%  |
| 501-600     | 49        | 16.23%  |
| 351-400     | 29        | 9.6%    |
| 401-500     | 25        | 8.28%   |
| 201-300     | 22        | 7.28%   |
| Unknown     | 18        | 5.96%   |
| 801-900     | 5         | 1.66%   |
| 701-800     | 5         | 1.66%   |
| 601-700     | 3         | 0.99%   |
| 1501-2000   | 1         | 0.33%   |
| 901-1000    | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 199       | 70.57%  |
| 16/10   | 38        | 13.48%  |
| 5/4     | 17        | 6.03%   |
| Unknown | 16        | 5.67%   |
| 21/9    | 6         | 2.13%   |
| 3/2     | 3         | 1.06%   |
| 4/3     | 2         | 0.71%   |
| 0.62    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 104       | 33.88%  |
| 201-250        | 41        | 13.36%  |
| 81-90          | 37        | 12.05%  |
| 151-200        | 21        | 6.84%   |
| Unknown        | 18        | 5.86%   |
| 301-350        | 17        | 5.54%   |
| 121-130        | 15        | 4.89%   |
| 61-70          | 11        | 3.58%   |
| 141-150        | 10        | 3.26%   |
| 351-500        | 9         | 2.93%   |
| 251-300        | 7         | 2.28%   |
| 71-80          | 5         | 1.63%   |
| 501-1000       | 4         | 1.3%    |
| 51-60          | 3         | 0.98%   |
| 131-140        | 2         | 0.65%   |
| 91-100         | 2         | 0.65%   |
| More than 1000 | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 97        | 32.01%  |
| 121-160       | 86        | 28.38%  |
| 101-120       | 84        | 27.72%  |
| Unknown       | 18        | 5.94%   |
| 161-240       | 13        | 4.29%   |
| More than 240 | 3         | 0.99%   |
| 1-50          | 2         | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 248       | 84.07%  |
| 2     | 35        | 11.86%  |
| 0     | 8         | 2.71%   |
| 3     | 4         | 1.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 158       | 36.32%  |
| Intel                             | 130       | 29.89%  |
| Qualcomm Atheros                  | 54        | 12.41%  |
| Broadcom                          | 26        | 5.98%   |
| Broadcom Limited                  | 10        | 2.3%    |
| Ralink                            | 9         | 2.07%   |
| Marvell Technology Group          | 9         | 2.07%   |
| TP-Link                           | 6         | 1.38%   |
| Ralink Technology                 | 6         | 1.38%   |
| Nvidia                            | 6         | 1.38%   |
| Xiaomi                            | 2         | 0.46%   |
| Samsung Electronics               | 2         | 0.46%   |
| Qualcomm Atheros Communications   | 2         | 0.46%   |
| MediaTek                          | 2         | 0.46%   |
| Hewlett-Packard                   | 2         | 0.46%   |
| ASIX Electronics                  | 2         | 0.46%   |
| vivo                              | 1         | 0.23%   |
| U-Blox                            | 1         | 0.23%   |
| Sundance Technology Inc / IC Plus | 1         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| Lenovo                            | 1         | 0.23%   |
| Huawei Technologies               | 1         | 0.23%   |
| Aquantia                          | 1         | 0.23%   |
| 3Com                              | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 109       | 21.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 5.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.75%   |
| Intel Wireless 8260                                                     | 9         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                       | 7         | 1.36%   |
| Intel Wireless 3160                                                     | 7         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.17%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.97%   |
| Intel Wireless 8265 / 8275                                              | 5         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.78%   |
| Intel Wireless 7265                                                     | 4         | 0.78%   |
| Intel Wireless 7260                                                     | 4         | 0.78%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.58%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.58%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 47.81%  |
| Qualcomm Atheros                | 42        | 18.42%  |
| Realtek Semiconductor           | 31        | 13.6%   |
| Broadcom                        | 16        | 7.02%   |
| Ralink                          | 9         | 3.95%   |
| TP-Link                         | 6         | 2.63%   |
| Ralink Technology               | 6         | 2.63%   |
| Broadcom Limited                | 5         | 2.19%   |
| Qualcomm Atheros Communications | 2         | 0.88%   |
| Qualcomm                        | 1         | 0.44%   |
| MediaTek                        | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.93%   |
| Intel Wireless 8260                                                     | 9         | 3.93%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.49%   |
| Intel Wireless 3160                                                     | 7         | 3.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 3.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.18%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.18%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.75%   |
| Intel Wireless 7265                                                     | 4         | 1.75%   |
| Intel Wireless 7260                                                     | 4         | 1.75%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.31%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.31%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.87%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 150       | 54.15%  |
| Intel                             | 59        | 21.3%   |
| Qualcomm Atheros                  | 19        | 6.86%   |
| Broadcom                          | 14        | 5.05%   |
| Marvell Technology Group          | 9         | 3.25%   |
| Nvidia                            | 6         | 2.17%   |
| Broadcom Limited                  | 5         | 1.81%   |
| Xiaomi                            | 2         | 0.72%   |
| Samsung Electronics               | 2         | 0.72%   |
| ASIX Electronics                  | 2         | 0.72%   |
| vivo                              | 1         | 0.36%   |
| Sundance Technology Inc / IC Plus | 1         | 0.36%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.36%   |
| MediaTek                          | 1         | 0.36%   |
| Lenovo                            | 1         | 0.36%   |
| Huawei Technologies               | 1         | 0.36%   |
| Hewlett-Packard                   | 1         | 0.36%   |
| Aquantia                          | 1         | 0.36%   |
| 3Com                              | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 109       | 38.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 29        | 10.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 11        | 3.89%   |
| Realtek RTL8125 2.5GbE Controller                                          | 7         | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4         | 1.41%   |
| Intel Ethernet Connection I217-LM                                          | 4         | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                       | 4         | 1.41%   |
| Intel 82577LM Gigabit Network Connection                                   | 4         | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3         | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 3         | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3         | 1.06%   |
| Nvidia MCP61 Ethernet                                                      | 3         | 1.06%   |
| Intel I211 Gigabit Network Connection                                      | 3         | 1.06%   |
| Intel Ethernet Connection I219-V                                           | 3         | 1.06%   |
| Intel Ethernet Connection I219-LM                                          | 3         | 1.06%   |
| Intel Ethernet Connection I217-V                                           | 3         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.71%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2         | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2         | 0.71%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2         | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 2         | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.71%   |
| Intel Ethernet Connection I218-LM                                          | 2         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                       | 2         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                                       | 2         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.71%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2         | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 2         | 0.71%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                     | 2         | 0.71%   |
| ASIX AX88772B                                                              | 2         | 0.71%   |
| vivo 1806                                                                  | 1         | 0.35%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1         | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1         | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1         | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 266       | 54.29%  |
| WiFi     | 222       | 45.31%  |
| Modem    | 2         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 183       | 61.41%  |
| Ethernet | 115       | 38.59%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 187       | 64.48%  |
| 1     | 94        | 32.41%  |
| 0     | 5         | 1.72%   |
| 3     | 4         | 1.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 278       | 95.86%  |
| Yes  | 12        | 4.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 41.92%  |
| Realtek Semiconductor           | 18        | 10.78%  |
| Qualcomm Atheros Communications | 12        | 7.19%   |
| Lite-On Technology              | 12        | 7.19%   |
| IMC Networks                    | 12        | 7.19%   |
| Broadcom                        | 11        | 6.59%   |
| Cambridge Silicon Radio         | 7         | 4.19%   |
| Dell                            | 5         | 2.99%   |
| Hewlett-Packard                 | 4         | 2.4%    |
| Toshiba                         | 3         | 1.8%    |
| Apple                           | 3         | 1.8%    |
| Ralink                          | 2         | 1.2%    |
| ASUSTek Computer                | 2         | 1.2%    |
| USI                             | 1         | 0.6%    |
| Taiyo Yuden                     | 1         | 0.6%    |
| Ralink Technology               | 1         | 0.6%    |
| Qcom                            | 1         | 0.6%    |
| Foxconn / Hon Hai               | 1         | 0.6%    |
| Edimax Technology               | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 16.17%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 7.78%   |
| Realtek Bluetooth Radio                             | 10        | 5.99%   |
| Intel AX201 Bluetooth                               | 9         | 5.39%   |
| Intel AX200 Bluetooth                               | 9         | 5.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 4.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.99%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.8%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.8%    |
| Lite-On Bluetooth Device                            | 3         | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.8%    |
| Intel AX210 Bluetooth                               | 3         | 1.8%    |
| IMC Networks Bluetooth Device                       | 3         | 1.8%    |
| Realtek RTL8821A Bluetooth                          | 2         | 1.2%    |
| Realtek RTL8723B Bluetooth                          | 2         | 1.2%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.2%    |
| Intel Bluetooth Device                              | 2         | 1.2%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.2%    |
| Dell Wireless 355 Bluetooth                         | 2         | 1.2%    |
| Broadcom HP Portable SoftSailing                    | 2         | 1.2%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.2%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.2%    |
| USI Bluetooth Device                                | 1         | 0.6%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.6%    |
| Toshiba Bluetooth Device                            | 1         | 0.6%    |
| Toshiba Askey Bluetooth Module                      | 1         | 0.6%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.6%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.6%    |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 222       | 56.49%  |
| AMD                              | 72        | 18.32%  |
| Nvidia                           | 66        | 16.79%  |
| C-Media Electronics              | 8         | 2.04%   |
| Creative Technology              | 3         | 0.76%   |
| Yamaha                           | 2         | 0.51%   |
| Realtek Semiconductor            | 2         | 0.51%   |
| Logitech                         | 2         | 0.51%   |
| Creative Labs                    | 2         | 0.51%   |
| Unknown                          | 1         | 0.25%   |
| Texas Instruments                | 1         | 0.25%   |
| Syntek                           | 1         | 0.25%   |
| SteelSeries ApS                  | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| RODE Microphones                 | 1         | 0.25%   |
| Microsoft                        | 1         | 0.25%   |
| Lenovo                           | 1         | 0.25%   |
| JMTek                            | 1         | 0.25%   |
| GYROCOM C&C                      | 1         | 0.25%   |
| GN Netcom                        | 1         | 0.25%   |
| Focusrite-Novation               | 1         | 0.25%   |
| FIFINE 683 Microphone            | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 4.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 4.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 4.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 3.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 3.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 2.84%   |
| AMD FCH Azalia Controller                                                  | 13        | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 2.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 11        | 2.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 2.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.53%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 1.31%   |
| AMD Trinity HDMI Audio Controller                                          | 6         | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 4         | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 0.87%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.66%   |
| Nvidia GT216 HDMI Audio Controller                                         | 3         | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.66%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 18.96%  |
| Unknown             | 39        | 18.48%  |
| SK hynix            | 37        | 17.54%  |
| Kingston            | 36        | 17.06%  |
| Micron Technology   | 16        | 7.58%   |
| Crucial             | 11        | 5.21%   |
| Corsair             | 9         | 4.27%   |
| G.Skill             | 7         | 3.32%   |
| Elpida              | 3         | 1.42%   |
| A-DATA Technology   | 3         | 1.42%   |
| Ramaxel Technology  | 2         | 0.95%   |
| Toshiba             | 1         | 0.47%   |
| Team                | 1         | 0.47%   |
| Silicon Power       | 1         | 0.47%   |
| Ramos Technology    | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| Nanya Technology    | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 4         | 1.72%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 4         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 1.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 1.29%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.29%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 3         | 1.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2         | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 2         | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s           | 2         | 0.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2         | 0.86%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 2         | 0.86%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2         | 0.86%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.86%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s  | 2         | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 2         | 0.86%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s   | 2         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 2         | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s   | 2         | 0.86%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s   | 2         | 0.86%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 0.86%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 2         | 0.86%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s    | 2         | 0.86%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 2         | 0.86%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s  | 2         | 0.86%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s     | 2         | 0.86%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 2         | 0.86%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s | 2         | 0.86%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s             | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s             | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s              | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s           | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s           | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s             | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 70        | 40.7%   |
| DDR4    | 61        | 35.47%  |
| DDR2    | 18        | 10.47%  |
| Unknown | 8         | 4.65%   |
| SDRAM   | 7         | 4.07%   |
| LPDDR4  | 3         | 1.74%   |
| DDR     | 3         | 1.74%   |
| LPDDR5  | 1         | 0.58%   |
| DRAM    | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 118       | 69.01%  |
| DIMM         | 49        | 28.65%  |
| Row Of Chips | 3         | 1.75%   |
| Chip         | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 65        | 33.51%  |
| 8192  | 55        | 28.35%  |
| 2048  | 41        | 21.13%  |
| 16384 | 15        | 7.73%   |
| 1024  | 13        | 6.7%    |
| 32768 | 3         | 1.55%   |
| 512   | 2         | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 44        | 22.22%  |
| 2667    | 26        | 13.13%  |
| 667     | 19        | 9.6%    |
| 1333    | 17        | 8.59%   |
| 2133    | 14        | 7.07%   |
| 3200    | 13        | 6.57%   |
| 1334    | 11        | 5.56%   |
| 2400    | 8         | 4.04%   |
| 800     | 6         | 3.03%   |
| Unknown | 6         | 3.03%   |
| 1066    | 4         | 2.02%   |
| 3466    | 3         | 1.52%   |
| 1867    | 3         | 1.52%   |
| 4267    | 2         | 1.01%   |
| 3266    | 2         | 1.01%   |
| 3000    | 2         | 1.01%   |
| 1639    | 2         | 1.01%   |
| 1067    | 2         | 1.01%   |
| 533     | 2         | 1.01%   |
| 6400    | 1         | 0.51%   |
| 4199    | 1         | 0.51%   |
| 3866    | 1         | 0.51%   |
| 3800    | 1         | 0.51%   |
| 3600    | 1         | 0.51%   |
| 2448    | 1         | 0.51%   |
| 2134    | 1         | 0.51%   |
| 2048    | 1         | 0.51%   |
| 1866    | 1         | 0.51%   |
| 1800    | 1         | 0.51%   |
| 975     | 1         | 0.51%   |
| 200     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 50%     |
| Samsung Electronics | 3         | 30%     |
| Canon               | 1         | 10%     |
| Brother Industries  | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Samsung SCX-4216F Scanner | 1         | 10%     |
| Samsung SCX-4100 Scanner  | 1         | 10%     |
| Samsung SCX-3200 Series   | 1         | 10%     |
| HP Officejet 4500 G510g-m | 1         | 10%     |
| HP LaserJet P1102         | 1         | 10%     |
| HP LaserJet 1018          | 1         | 10%     |
| HP LaserJet 1010          | 1         | 10%     |
| HP DeskJet 5940           | 1         | 10%     |
| Canon PIXMA MG3000 series | 1         | 10%     |
| Brother DCP-L2510D series | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 46        | 24.73%  |
| IMC Networks                           | 20        | 10.75%  |
| Realtek Semiconductor                  | 18        | 9.68%   |
| Microdia                               | 12        | 6.45%   |
| Acer                                   | 11        | 5.91%   |
| Logitech                               | 10        | 5.38%   |
| Suyin                                  | 9         | 4.84%   |
| Sunplus Innovation Technology          | 7         | 3.76%   |
| Quanta                                 | 7         | 3.76%   |
| Lite-On Technology                     | 7         | 3.76%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.23%   |
| Syntek                                 | 5         | 2.69%   |
| Z-Star Microelectronics                | 3         | 1.61%   |
| Silicon Motion                         | 3         | 1.61%   |
| Luxvisions Innotech Limited            | 3         | 1.61%   |
| Samsung Electronics                    | 2         | 1.08%   |
| Ricoh                                  | 2         | 1.08%   |
| Genesys Logic                          | 2         | 1.08%   |
| Apple                                  | 2         | 1.08%   |
| Tobii AB                               | 1         | 0.54%   |
| Razer USA                              | 1         | 0.54%   |
| Primax Electronics                     | 1         | 0.54%   |
| Pixart Imaging                         | 1         | 0.54%   |
| OmniVision Technologies                | 1         | 0.54%   |
| Microsoft                              | 1         | 0.54%   |
| Lenovo                                 | 1         | 0.54%   |
| KYE Systems (Mouse Systems)            | 1         | 0.54%   |
| GEMBIRD                                | 1         | 0.54%   |
| DigiTech                               | 1         | 0.54%   |
| Cubeternet                             | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 4.23%   |
| IMC Networks USB2.0 HD UVC WebCam        | 6         | 3.17%   |
| Realtek Integrated_Webcam_HD             | 5         | 2.65%   |
| IMC Networks Integrated Camera           | 5         | 2.65%   |
| Realtek USB Camera                       | 4         | 2.12%   |
| Lite-On Integrated Camera                | 4         | 2.12%   |
| Chicony USB2.0 HD UVC WebCam             | 4         | 2.12%   |
| Chicony HD WebCam                        | 4         | 2.12%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 3         | 1.59%   |
| Sunplus Asus Webcam                      | 3         | 1.59%   |
| Realtek Integrated Webcam                | 3         | 1.59%   |
| Microdia Integrated_Webcam_HD            | 3         | 1.59%   |
| Logitech Webcam C270                     | 3         | 1.59%   |
| Chicony HP HD Camera                     | 3         | 1.59%   |
| Chicony HD User Facing                   | 3         | 1.59%   |
| Acer Lenovo EasyCamera                   | 3         | 1.59%   |
| Acer Integrated Camera                   | 3         | 1.59%   |
| Z-Star A4 TECH HD PC Camera              | 2         | 1.06%   |
| Suyin HD WebCam                          | 2         | 1.06%   |
| Samsung Galaxy A5 (MTP)                  | 2         | 1.06%   |
| Realtek HP Webcam                        | 2         | 1.06%   |
| Quanta HD Webcam                         | 2         | 1.06%   |
| Microdia Lenovo EasyCamera               | 2         | 1.06%   |
| Microdia Integrated Webcam               | 2         | 1.06%   |
| Logitech Webcam C170                     | 2         | 1.06%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 2         | 1.06%   |
| IMC Networks USB2.0 UVC HD Webcam        | 2         | 1.06%   |
| Genesys Logic Camera                     | 2         | 1.06%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 1.06%   |
| Chicony TOSHIBA Web Camera - HD          | 2         | 1.06%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.06%   |
| Chicony HP Truevision HD camera          | 2         | 1.06%   |
| Chicony HP HD Webcam                     | 2         | 1.06%   |
| Chicony CNF9055 Toshiba Webcam           | 2         | 1.06%   |
| Apple iPhone 5/5C/5S/6/SE                | 2         | 1.06%   |
| Acer BisonCam, NB Pro                    | 2         | 1.06%   |
| Z-Star Vega USB 2.0 Camera               | 1         | 0.53%   |
| Tobii AB EyeChip                         | 1         | 0.53%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S     | 1         | 0.53%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera    | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 43.59%  |
| Synaptics                  | 9         | 23.08%  |
| Upek                       | 3         | 7.69%   |
| AuthenTec                  | 3         | 7.69%   |
| STMicroelectronics         | 2         | 5.13%   |
| Shenzhen Goodix Technology | 2         | 5.13%   |
| Elan Microelectronics      | 2         | 5.13%   |
| LighTuning Technology      | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 10.26%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 7.69%   |
| Unknown                                                                    | 3         | 7.69%   |
| Validity Sensors VFS491                                                    | 2         | 5.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.13%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 5.13%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 5.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.56%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.56%   |
| AuthenTec AES1600                                                          | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 13        | 54.17%  |
| Broadcom         | 6         | 25%     |
| Lenovo           | 2         | 8.33%   |
| Upek             | 1         | 4.17%   |
| SCM Microsystems | 1         | 4.17%   |
| O2 Micro         | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 13        | 54.17%  |
| Broadcom 58200                                             | 5         | 20.83%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.17%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.17%   |
| Broadcom 5880                                              | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 209       | 70.13%  |
| 1     | 69        | 23.15%  |
| 2     | 16        | 5.37%   |
| 3     | 3         | 1.01%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 35.78%  |
| Graphics card            | 25        | 22.94%  |
| Chipcard                 | 19        | 17.43%  |
| Net/wireless             | 9         | 8.26%   |
| Multimedia controller    | 5         | 4.59%   |
| Communication controller | 3         | 2.75%   |
| Storage                  | 2         | 1.83%   |
| Camera                   | 2         | 1.83%   |
| Bluetooth                | 2         | 1.83%   |
| Storage/raid             | 1         | 0.92%   |
| Net/ethernet             | 1         | 0.92%   |
| Card reader              | 1         | 0.92%   |

