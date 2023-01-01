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

Total: 426

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 31        | 10.03%  |
| ROSA R11          | 19        | 6.15%   |
| Ubuntu 18.04      | 15        | 4.85%   |
| ROSA R10          | 12        | 3.88%   |
| ROSA R9           | 10        | 3.24%   |
| KDE neon 20.04    | 8         | 2.59%   |
| Arch              | 8         | 2.59%   |
| ROSA R8.1         | 7         | 2.27%   |
| Arch Rolling      | 7         | 2.27%   |
| Ubuntu 22.04      | 6         | 1.94%   |
| ROSA R11.1        | 6         | 1.94%   |
| Linux Mint 20.1   | 6         | 1.94%   |
| Debian 11         | 6         | 1.94%   |
| ROSA R8           | 5         | 1.62%   |
| Pop!_OS 21.04     | 5         | 1.62%   |
| Pop!_OS 20.10     | 5         | 1.62%   |
| Manjaro           | 5         | 1.62%   |
| Linux Mint 20.3   | 5         | 1.62%   |
| Ubuntu 19.10      | 4         | 1.29%   |
| ROSA 12.2         | 4         | 1.29%   |
| OpenMandriva 4.50 | 4         | 1.29%   |
| OpenMandriva 4.3  | 4         | 1.29%   |
| Linux Mint 21     | 4         | 1.29%   |
| Linux Mint 19     | 4         | 1.29%   |
| Debian Testing    | 4         | 1.29%   |
| ArcoLinux Rolling | 4         | 1.29%   |
| Xubuntu 20.04     | 3         | 0.97%   |
| ROSA 12.1         | 3         | 0.97%   |
| Pop!_OS 22.04     | 3         | 0.97%   |
| OpenMandriva 4.2  | 3         | 0.97%   |
| Linux Mint 20.2   | 3         | 0.97%   |
| Linux Mint 20     | 3         | 0.97%   |
| Linux Mint 19.3   | 3         | 0.97%   |
| Linux Mint 18.3   | 3         | 0.97%   |
| Fedora 35         | 3         | 0.97%   |
| Fedora 30         | 3         | 0.97%   |
| Ubuntu 21.10      | 2         | 0.65%   |
| Ubuntu 21.04      | 2         | 0.65%   |
| Ubuntu 20.10      | 2         | 0.65%   |
| Ubuntu 16.04      | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 66        | 23.74%  |
| ROSA          | 50        | 17.99%  |
| Linux Mint    | 31        | 11.15%  |
| Arch          | 15        | 5.4%    |
| Pop!_OS       | 14        | 5.04%   |
| Fedora        | 13        | 4.68%   |
| OpenMandriva  | 11        | 3.96%   |
| Debian        | 11        | 3.96%   |
| Manjaro       | 10        | 3.6%    |
| KDE neon      | 10        | 3.6%    |
| Xubuntu       | 5         | 1.8%    |
| ArcoLinux     | 5         | 1.8%    |
| openSUSE      | 3         | 1.08%   |
| Kali          | 3         | 1.08%   |
| Garuda Linux  | 3         | 1.08%   |
| Endless       | 3         | 1.08%   |
| Elementary    | 3         | 1.08%   |
| Ubuntu Unity  | 2         | 0.72%   |
| SteamOS       | 2         | 0.72%   |
| Kubuntu       | 2         | 0.72%   |
| EndeavourOS   | 2         | 0.72%   |
| Clear Linux   | 2         | 0.72%   |
| Zorin         | 1         | 0.36%   |
| Void Linux    | 1         | 0.36%   |
| Ubuntu MATE   | 1         | 0.36%   |
| Ubuntu Budgie | 1         | 0.36%   |
| Solus         | 1         | 0.36%   |
| Puppy         | 1         | 0.36%   |
| Peppermint    | 1         | 0.36%   |
| Parrot        | 1         | 0.36%   |
| MX            | 1         | 0.36%   |
| Lubuntu       | 1         | 0.36%   |
| LMDE          | 1         | 0.36%   |
| GNOME OS      | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 10        | 2.96%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 9         | 2.66%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 8         | 2.37%   |
| 5.4.0-42-generic                   | 6         | 1.78%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 1.48%   |
| 5.4.0-58-generic                   | 4         | 1.18%   |
| 5.4.0-132-generic                  | 4         | 1.18%   |
| 5.4.0-122-generic                  | 4         | 1.18%   |
| 5.16.7-desktop-1omv4003            | 4         | 1.18%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 4         | 1.18%   |
| 5.8.0-7630-generic                 | 3         | 0.89%   |
| 5.4.83-generic-2rosa-x86_64        | 3         | 0.89%   |
| 5.4.0-80-generic                   | 3         | 0.89%   |
| 5.4.0-66-generic                   | 3         | 0.89%   |
| 5.4.0-54-generic                   | 3         | 0.89%   |
| 5.4.0-52-generic                   | 3         | 0.89%   |
| 5.13.0-25-generic                  | 3         | 0.89%   |
| 5.12.4-desktop-1omv4050            | 3         | 0.89%   |
| 5.10.14-desktop-1omv4002           | 3         | 0.89%   |
| 5.0.0-37-generic                   | 3         | 0.89%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 0.89%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 0.89%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 0.89%   |
| 5.8.0-48-generic                   | 2         | 0.59%   |
| 5.8.0-25-generic                   | 2         | 0.59%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.59%   |
| 5.4.0-67-generic                   | 2         | 0.59%   |
| 5.4.0-26-generic                   | 2         | 0.59%   |
| 5.4.0-100-generic                  | 2         | 0.59%   |
| 5.3.0-23-generic                   | 2         | 0.59%   |
| 5.15.0-56-generic                  | 2         | 0.59%   |
| 5.15.0-53-generic                  | 2         | 0.59%   |
| 5.15.0-46-generic                  | 2         | 0.59%   |
| 5.13.6-arch1-1                     | 2         | 0.59%   |
| 5.13.0-39-generic                  | 2         | 0.59%   |
| 5.13.0-28-generic                  | 2         | 0.59%   |
| 5.11.0-7620-generic                | 2         | 0.59%   |
| 5.11.0-43-generic                  | 2         | 0.59%   |
| 5.11.0-38-generic                  | 2         | 0.59%   |
| 5.10.0-8-amd64                     | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 15.63%  |
| 4.15.0  | 32        | 10%     |
| 5.13.0  | 15        | 4.69%   |
| 5.8.0   | 14        | 4.38%   |
| 5.15.0  | 14        | 4.38%   |
| 5.11.0  | 14        | 4.38%   |
| 4.9.20  | 11        | 3.44%   |
| 5.3.0   | 10        | 3.13%   |
| 4.9.60  | 8         | 2.5%    |
| 5.10.0  | 7         | 2.19%   |
| 5.0.0   | 6         | 1.88%   |
| 5.10.74 | 5         | 1.56%   |
| 4.18.0  | 5         | 1.56%   |
| 5.16.7  | 4         | 1.25%   |
| 4.9.155 | 4         | 1.25%   |
| 4.1.34  | 4         | 1.25%   |
| 5.4.83  | 3         | 0.94%   |
| 5.17.1  | 3         | 0.94%   |
| 5.14.0  | 3         | 0.94%   |
| 5.12.4  | 3         | 0.94%   |
| 5.10.14 | 3         | 0.94%   |
| 4.9.41  | 3         | 0.94%   |
| 5.9.0   | 2         | 0.63%   |
| 5.4.72  | 2         | 0.63%   |
| 5.4.32  | 2         | 0.63%   |
| 5.19.0  | 2         | 0.63%   |
| 5.17.5  | 2         | 0.63%   |
| 5.16.15 | 2         | 0.63%   |
| 5.13.6  | 2         | 0.63%   |
| 5.13.12 | 2         | 0.63%   |
| 5.12.14 | 2         | 0.63%   |
| 4.9.9   | 2         | 0.63%   |
| 4.9.76  | 2         | 0.63%   |
| 4.9.124 | 2         | 0.63%   |
| 4.4.0   | 2         | 0.63%   |
| 4.10.0  | 2         | 0.63%   |
| 4.1.38  | 2         | 0.63%   |
| 6.0.9   | 1         | 0.31%   |
| 6.0.8   | 1         | 0.31%   |
| 6.0.7   | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 58        | 18.71%  |
| 4.15    | 32        | 10.32%  |
| 4.9     | 27        | 8.71%   |
| 5.15    | 22        | 7.1%    |
| 5.13    | 20        | 6.45%   |
| 5.10    | 20        | 6.45%   |
| 5.8     | 18        | 5.81%   |
| 5.11    | 18        | 5.81%   |
| 5.3     | 10        | 3.23%   |
| 5.16    | 9         | 2.9%    |
| 6.0     | 8         | 2.58%   |
| 5.12    | 8         | 2.58%   |
| 5.19    | 6         | 1.94%   |
| 5.17    | 6         | 1.94%   |
| 5.0     | 6         | 1.94%   |
| 5.18    | 5         | 1.61%   |
| 5.14    | 5         | 1.61%   |
| 4.18    | 5         | 1.61%   |
| 4.1     | 5         | 1.61%   |
| 5.9     | 4         | 1.29%   |
| 5.5     | 3         | 0.97%   |
| 5.2     | 3         | 0.97%   |
| 5.6     | 2         | 0.65%   |
| 4.4     | 2         | 0.65%   |
| 4.19    | 2         | 0.65%   |
| 4.10    | 2         | 0.65%   |
| 5.7     | 1         | 0.32%   |
| 4.8     | 1         | 0.32%   |
| 4.20    | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 252       | 94.38%  |
| i686    | 13        | 4.87%   |
| aarch64 | 2         | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 98        | 34.03%  |
| KDE5       | 54        | 18.75%  |
| KDE4       | 34        | 11.81%  |
| Unknown    | 28        | 9.72%   |
| XFCE       | 19        | 6.6%    |
| MATE       | 14        | 4.86%   |
| X-Cinnamon | 13        | 4.51%   |
| KDE        | 9         | 3.13%   |
| Cinnamon   | 4         | 1.39%   |
| Budgie     | 4         | 1.39%   |
| Pantheon   | 3         | 1.04%   |
| LXQt       | 3         | 1.04%   |
| Unity      | 2         | 0.69%   |
| Deepin     | 2         | 0.69%   |
| LXDE       | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 223       | 81.09%  |
| Wayland | 36        | 13.09%  |
| Unknown | 11        | 4%      |
| Tty     | 5         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 118       | 41.7%   |
| SDDM    | 46        | 16.25%  |
| GDM     | 38        | 13.43%  |
| KDM     | 34        | 12.01%  |
| LightDM | 18        | 6.36%   |
| TDM     | 15        | 5.3%    |
| GDM3    | 11        | 3.89%   |
| SLiM    | 1         | 0.35%   |
| MDM     | 1         | 0.35%   |
| LDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 122       | 43.57%  |
| Unknown     | 65        | 23.21%  |
| lv_LV       | 34        | 12.14%  |
| ru_RU       | 30        | 10.71%  |
| en_GB       | 15        | 5.36%   |
| C           | 7         | 2.5%    |
| ru_RU.UTF_8 | 2         | 0.71%   |
| de_DE       | 2         | 0.71%   |
| POSIX       | 1         | 0.36%   |
| osa_US      | 1         | 0.36%   |
| cv_RU       | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 156       | 57.78%  |
| EFI  | 114       | 42.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 205       | 74.01%  |
| Unknown | 28        | 10.11%  |
| Btrfs   | 26        | 9.39%   |
| Overlay | 14        | 5.05%   |
| Zfs     | 1         | 0.36%   |
| Xfs     | 1         | 0.36%   |
| Ext3    | 1         | 0.36%   |
| Aufs    | 1         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 132       | 47.65%  |
| GPT     | 88        | 31.77%  |
| MBR     | 57        | 20.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 246       | 87.86%  |
| Yes       | 34        | 12.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 199       | 72.36%  |
| Yes       | 76        | 27.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 51        | 19.1%   |
| Lenovo                  | 43        | 16.1%   |
| Hewlett-Packard         | 34        | 12.73%  |
| Dell                    | 31        | 11.61%  |
| Acer                    | 24        | 8.99%   |
| Gigabyte Technology     | 20        | 7.49%   |
| MSI                     | 17        | 6.37%   |
| ASRock                  | 8         | 3%      |
| Toshiba                 | 6         | 2.25%   |
| Samsung Electronics     | 4         | 1.5%    |
| Intel                   | 4         | 1.5%    |
| Fujitsu Siemens         | 3         | 1.12%   |
| Raspberry Pi Foundation | 2         | 0.75%   |
| HUAWEI                  | 2         | 0.75%   |
| Apple                   | 2         | 0.75%   |
| Wortmann AG             | 1         | 0.37%   |
| Valve                   | 1         | 0.37%   |
| Timi                    | 1         | 0.37%   |
| Sony                    | 1         | 0.37%   |
| Razer                   | 1         | 0.37%   |
| Quanta                  | 1         | 0.37%   |
| Packard Bell            | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| Hardkernel              | 1         | 0.37%   |
| Fujitsu                 | 1         | 0.37%   |
| Foxconn                 | 1         | 0.37%   |
| eMachines               | 1         | 0.37%   |
| Biostar                 | 1         | 0.37%   |
| Advent                  | 1         | 0.37%   |
| Acidanthera             | 1         | 0.37%   |
| ABIT                    | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 5         | 1.87%   |
| HP EliteBook 840 G3                                   | 3         | 1.12%   |
| Toshiba Satellite C660                                | 2         | 0.75%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.75%   |
| MSI MS-7721                                           | 2         | 0.75%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.75%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.75%   |
| HP G62                                                | 2         | 0.75%   |
| HP EliteBook 8440p                                    | 2         | 0.75%   |
| HP 250 G6 Notebook PC                                 | 2         | 0.75%   |
| Gigabyte G33M-S2                                      | 2         | 0.75%   |
| Gigabyte B550 AORUS PRO V2                            | 2         | 0.75%   |
| Gigabyte 946GMX-S2                                    | 2         | 0.75%   |
| Dell OptiPlex 7020                                    | 2         | 0.75%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.75%   |
| ASUS X553MA                                           | 2         | 0.75%   |
| ASUS X551MA                                           | 2         | 0.75%   |
| Wortmann AG CR700                                     | 1         | 0.37%   |
| Valve Jupiter                                         | 1         | 0.37%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.37%   |
| Toshiba Satellite L750                                | 1         | 0.37%   |
| Toshiba Satellite L350                                | 1         | 0.37%   |
| Toshiba Satellite C50D-B                              | 1         | 0.37%   |
| Timi A35S                                             | 1         | 0.37%   |
| Sony VPCCW2S8E                                        | 1         | 0.37%   |
| Samsung R528/R728                                     | 1         | 0.37%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.37%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.37%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.37%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.37%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.37%   |
| MSI MS-7C52                                           | 1         | 0.37%   |
| MSI MS-7B46                                           | 1         | 0.37%   |
| MSI MS-7B33                                           | 1         | 0.37%   |
| MSI MS-7996                                           | 1         | 0.37%   |
| MSI MS-7850                                           | 1         | 0.37%   |
| MSI MS-7846                                           | 1         | 0.37%   |
| MSI MS-7758                                           | 1         | 0.37%   |
| MSI MS-7693                                           | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 22        | 8.24%   |
| Acer Aspire        | 15        | 5.62%   |
| HP EliteBook       | 11        | 4.12%   |
| Dell Inspiron      | 11        | 4.12%   |
| Lenovo IdeaPad     | 9         | 3.37%   |
| Dell Latitude      | 9         | 3.37%   |
| Toshiba Satellite  | 6         | 2.25%   |
| Dell OptiPlex      | 6         | 2.25%   |
| HP ProBook         | 5         | 1.87%   |
| ASUS All           | 5         | 1.87%   |
| HP Pavilion        | 4         | 1.5%    |
| ASUS VivoBook      | 4         | 1.5%    |
| ASUS PRIME         | 4         | 1.5%    |
| Lenovo Legion      | 3         | 1.12%   |
| HP 250             | 3         | 1.12%   |
| RPi Raspberry      | 2         | 0.75%   |
| MSI MS-7721        | 2         | 0.75%   |
| Lenovo Yoga        | 2         | 0.75%   |
| HP Laptop          | 2         | 0.75%   |
| HP G62             | 2         | 0.75%   |
| HP Compaq          | 2         | 0.75%   |
| Gigabyte G33M-S2   | 2         | 0.75%   |
| Gigabyte B550      | 2         | 0.75%   |
| Gigabyte 946GMX-S2 | 2         | 0.75%   |
| Dell XPS           | 2         | 0.75%   |
| ASUS ZenBook       | 2         | 0.75%   |
| ASUS X553MA        | 2         | 0.75%   |
| ASUS X551MA        | 2         | 0.75%   |
| ASUS TUF           | 2         | 0.75%   |
| ASUS ROG           | 2         | 0.75%   |
| ASUS P5Q           | 2         | 0.75%   |
| Acer Nitro         | 2         | 0.75%   |
| Wortmann AG CR700  | 1         | 0.37%   |
| Valve Jupiter      | 1         | 0.37%   |
| Timi A35S          | 1         | 0.37%   |
| Sony VPCCW2S8E     | 1         | 0.37%   |
| Samsung R528       | 1         | 0.37%   |
| Samsung 355V4C     | 1         | 0.37%   |
| Samsung 350V5C     | 1         | 0.37%   |
| Samsung 300V3A     | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 29        | 10.86%  |
| 2019    | 25        | 9.36%   |
| 2007    | 20        | 7.49%   |
| 2014    | 19        | 7.12%   |
| 2018    | 18        | 6.74%   |
| 2008    | 18        | 6.74%   |
| 2015    | 17        | 6.37%   |
| 2012    | 17        | 6.37%   |
| 2020    | 16        | 5.99%   |
| 2011    | 16        | 5.99%   |
| 2010    | 15        | 5.62%   |
| 2017    | 13        | 4.87%   |
| 2009    | 13        | 4.87%   |
| 2016    | 11        | 4.12%   |
| 2021    | 9         | 3.37%   |
| 2006    | 6         | 2.25%   |
| 2022    | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 2004    | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 175       | 65.54%  |
| Desktop        | 85        | 31.84%  |
| Convertible    | 3         | 1.12%   |
| System on chip | 2         | 0.75%   |
| Mini pc        | 2         | 0.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 252       | 93.33%  |
| Enabled  | 18        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 266       | 99.63%  |
| Yes  | 1         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 76        | 27.94%  |
| 4.01-8.0    | 64        | 23.53%  |
| 8.01-16.0   | 45        | 16.54%  |
| 16.01-24.0  | 35        | 12.87%  |
| 32.01-64.0  | 21        | 7.72%   |
| 1.01-2.0    | 13        | 4.78%   |
| 2.01-3.0    | 10        | 3.68%   |
| 24.01-32.0  | 5         | 1.84%   |
| 0.51-1.0    | 2         | 0.74%   |
| 64.01-256.0 | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 99        | 32.46%  |
| 2.01-3.0   | 75        | 24.59%  |
| 0.51-1.0   | 46        | 15.08%  |
| 4.01-8.0   | 37        | 12.13%  |
| 3.01-4.0   | 32        | 10.49%  |
| 8.01-16.0  | 11        | 3.61%   |
| 16.01-24.0 | 3         | 0.98%   |
| 24.01-32.0 | 1         | 0.33%   |
| 0.01-0.5   | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 171       | 61.73%  |
| 2      | 70        | 25.27%  |
| 3      | 20        | 7.22%   |
| 4      | 10        | 3.61%   |
| 6      | 2         | 0.72%   |
| 0      | 2         | 0.72%   |
| 7      | 1         | 0.36%   |
| 5      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 156       | 57.35%  |
| Yes       | 116       | 42.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 247       | 91.82%  |
| No        | 22        | 8.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 76.49%  |
| No        | 63        | 23.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 56.46%  |
| No        | 118       | 43.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Latvia  | 267       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Riga                    | 198       | 69.96%  |
| Jelgava                 | 10        | 3.53%   |
| Liepāja                | 8         | 2.83%   |
| Daugavpils              | 8         | 2.83%   |
| Ventspils               | 5         | 1.77%   |
| Jūrmala                | 5         | 1.77%   |
| Adazi                   | 5         | 1.77%   |
| Salaspils               | 3         | 1.06%   |
| Limbaži                | 3         | 1.06%   |
| Valmiera                | 2         | 0.71%   |
| Talsi                   | 2         | 0.71%   |
| Saulkrasti              | 2         | 0.71%   |
| Malpils                 | 2         | 0.71%   |
| Kuldīga                | 2         | 0.71%   |
| Jaunmarupe              | 2         | 0.71%   |
| Iecava                  | 2         | 0.71%   |
| Cēsis                  | 2         | 0.71%   |
| Zvejniekciems           | 1         | 0.35%   |
| Ulbroka                 | 1         | 0.35%   |
| Tukums                  | 1         | 0.35%   |
| Tiraine                 | 1         | 0.35%   |
| Saldus                  | 1         | 0.35%   |
| Ragana                  | 1         | 0.35%   |
| Pļaviņas              | 1         | 0.35%   |
| Ogre                    | 1         | 0.35%   |
| Lizums                  | 1         | 0.35%   |
| Lielvārde              | 1         | 0.35%   |
| Jēkabpils Municipality | 1         | 0.35%   |
| Jēkabpils              | 1         | 0.35%   |
| Gulbene                 | 1         | 0.35%   |
| Garkalne                | 1         | 0.35%   |
| Garciems                | 1         | 0.35%   |
| Dreilini                | 1         | 0.35%   |
| Dobele                  | 1         | 0.35%   |
| Carnikava               | 1         | 0.35%   |
| Brankas                 | 1         | 0.35%   |
| Bauska                  | 1         | 0.35%   |
| Aizpute                 | 1         | 0.35%   |
| Aizkraukle              | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 66        | 90     | 17.46%  |
| Samsung Electronics     | 62        | 95     | 16.4%   |
| WDC                     | 58        | 89     | 15.34%  |
| Kingston                | 37        | 50     | 9.79%   |
| Toshiba                 | 28        | 32     | 7.41%   |
| Hitachi                 | 16        | 21     | 4.23%   |
| Crucial                 | 13        | 20     | 3.44%   |
| Unknown                 | 8         | 12     | 2.12%   |
| Intel                   | 8         | 14     | 2.12%   |
| SK hynix                | 7         | 7      | 1.85%   |
| SanDisk                 | 7         | 14     | 1.85%   |
| HGST                    | 7         | 15     | 1.85%   |
| A-DATA Technology       | 7         | 9      | 1.85%   |
| Micron Technology       | 6         | 6      | 1.59%   |
| Patriot                 | 5         | 9      | 1.32%   |
| OCZ                     | 3         | 4      | 0.79%   |
| KIOXIA                  | 3         | 4      | 0.79%   |
| GOODRAM                 | 3         | 6      | 0.79%   |
| SPCC                    | 2         | 3      | 0.53%   |
| Phison                  | 2         | 2      | 0.53%   |
| Netac                   | 2         | 2      | 0.53%   |
| LITEON                  | 2         | 2      | 0.53%   |
| China                   | 2         | 2      | 0.53%   |
| XPG                     | 1         | 1      | 0.26%   |
| Verbatim                | 1         | 1      | 0.26%   |
| USB                     | 1         | 1      | 0.26%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.26%   |
| Silicon Motion          | 1         | 1      | 0.26%   |
| Realtek Semiconductor   | 1         | 1      | 0.26%   |
| Realtek                 | 1         | 1      | 0.26%   |
| PNY                     | 1         | 1      | 0.26%   |
| Plextor                 | 1         | 1      | 0.26%   |
| Mushkin                 | 1         | 2      | 0.26%   |
| Maxtor                  | 1         | 1      | 0.26%   |
| LITEONIT                | 1         | 1      | 0.26%   |
| Lexar                   | 1         | 1      | 0.26%   |
| KingSpec                | 1         | 1      | 0.26%   |
| KingFast                | 1         | 2      | 0.26%   |
| Kingchuxing             | 1         | 2      | 0.26%   |
| Intenso                 | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD   | 10        | 2.42%   |
| Seagate ST500LT012-1DG142 500GB   | 6         | 1.45%   |
| Samsung SSD 860 EVO 500GB         | 5         | 1.21%   |
| Samsung SSD 850 EVO 500GB         | 5         | 1.21%   |
| Kingston SV300S37A120G 120GB SSD  | 5         | 1.21%   |
| Toshiba MQ01ABF050 500GB          | 4         | 0.97%   |
| Seagate ST1000LM048-2E7172 1TB    | 4         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB    | 4         | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB    | 4         | 0.97%   |
| Samsung SSD 970 EVO Plus 500GB    | 4         | 0.97%   |
| Crucial CT500MX500SSD1 500GB      | 4         | 0.97%   |
| WDC WD2000JD-00HBB0 200GB         | 3         | 0.73%   |
| Toshiba MQ04ABF100 1TB            | 3         | 0.73%   |
| Seagate ST500DM005 HD502HJ 500GB  | 3         | 0.73%   |
| Samsung SSD 650 120GB             | 3         | 0.73%   |
| Samsung NVMe SSD Drive 500GB      | 3         | 0.73%   |
| Samsung NVMe SSD Drive 1TB        | 3         | 0.73%   |
| Patriot Burst 240GB SSD           | 3         | 0.73%   |
| Kingston SV300S37A60G 64GB SSD    | 3         | 0.73%   |
| Kingston SV300S37A240G 240GB SSD  | 3         | 0.73%   |
| Hitachi HTS547575A9E384 752GB     | 3         | 0.73%   |
| Hitachi HTS545050B9A300 500GB     | 3         | 0.73%   |
| Crucial CT1000MX500SSD1 1TB       | 3         | 0.73%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 2         | 0.48%   |
| WDC WD5002AALX-00J37A0 500GB      | 2         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 2         | 0.48%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 2         | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 2         | 0.48%   |
| WDC WD5000AAKX-001CA0 500GB       | 2         | 0.48%   |
| WDC WD20EARX-00PASB0 2TB          | 2         | 0.48%   |
| WDC WD10SPZX-21Z10T0 1TB          | 2         | 0.48%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2         | 0.48%   |
| Toshiba MQ01ABD100 1TB            | 2         | 0.48%   |
| Toshiba MQ01ABD050 500GB          | 2         | 0.48%   |
| Toshiba MK8034GSX 80GB            | 2         | 0.48%   |
| Toshiba MK6465GSX 640GB           | 2         | 0.48%   |
| SK hynix HFM512GDJTNG-8310A 512GB | 2         | 0.48%   |
| SK hynix BC511 NVMe 256GB         | 2         | 0.48%   |
| Seagate ST9160821AS 160GB         | 2         | 0.48%   |
| Seagate ST3500418AS 500GB         | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 90     | 36.67%  |
| WDC                 | 49        | 75     | 27.22%  |
| Toshiba             | 23        | 27     | 12.78%  |
| Hitachi             | 16        | 21     | 8.89%   |
| Samsung Electronics | 15        | 20     | 8.33%   |
| HGST                | 7         | 15     | 3.89%   |
| USB                 | 1         | 1      | 0.56%   |
| Maxtor              | 1         | 1      | 0.56%   |
| IBM/Hitachi         | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 34        | 46     | 26.56%  |
| Samsung Electronics | 31        | 43     | 24.22%  |
| Crucial             | 13        | 20     | 10.16%  |
| A-DATA Technology   | 7         | 9      | 5.47%   |
| WDC                 | 5         | 6      | 3.91%   |
| Patriot             | 5         | 9      | 3.91%   |
| SanDisk             | 3         | 4      | 2.34%   |
| OCZ                 | 3         | 4      | 2.34%   |
| Micron Technology   | 3         | 3      | 2.34%   |
| Intel               | 3         | 6      | 2.34%   |
| GOODRAM             | 3         | 6      | 2.34%   |
| SPCC                | 2         | 3      | 1.56%   |
| LITEON              | 2         | 2      | 1.56%   |
| China               | 2         | 2      | 1.56%   |
| Verbatim            | 1         | 1      | 0.78%   |
| Toshiba             | 1         | 1      | 0.78%   |
| PNY                 | 1         | 1      | 0.78%   |
| Plextor             | 1         | 1      | 0.78%   |
| Mushkin             | 1         | 2      | 0.78%   |
| LITEONIT            | 1         | 1      | 0.78%   |
| Lexar               | 1         | 1      | 0.78%   |
| KingSpec            | 1         | 1      | 0.78%   |
| KingFast            | 1         | 2      | 0.78%   |
| Intenso             | 1         | 1      | 0.78%   |
| Integral            | 1         | 1      | 0.78%   |
| GLOWAY              | 1         | 1      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 154       | 252    | 45.7%   |
| SSD     | 111       | 177    | 32.94%  |
| NVMe    | 63        | 92     | 18.69%  |
| MMC     | 6         | 10     | 1.78%   |
| Unknown | 3         | 6      | 0.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 220       | 425    | 73.83%  |
| NVMe | 63        | 91     | 21.14%  |
| SAS  | 9         | 11     | 3.02%   |
| MMC  | 6         | 10     | 2.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 174       | 289    | 64.21%  |
| 0.51-1.0   | 77        | 111    | 28.41%  |
| 1.01-2.0   | 13        | 21     | 4.8%    |
| 2.01-3.0   | 3         | 4      | 1.11%   |
| 3.01-4.0   | 2         | 2      | 0.74%   |
| 4.01-10.0  | 2         | 2      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 30.98%  |
| 251-500        | 62        | 20.88%  |
| 501-1000       | 37        | 12.46%  |
| 1001-2000      | 27        | 9.09%   |
| 51-100         | 24        | 8.08%   |
| 1-20           | 19        | 6.4%    |
| 21-50          | 12        | 4.04%   |
| 2001-3000      | 10        | 3.37%   |
| More than 3000 | 7         | 2.36%   |
| Unknown        | 7         | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 124       | 40.79%  |
| 21-50          | 42        | 13.82%  |
| 101-250        | 38        | 12.5%   |
| 51-100         | 35        | 11.51%  |
| 251-500        | 26        | 8.55%   |
| 501-1000       | 18        | 5.92%   |
| 1001-2000      | 10        | 3.29%   |
| Unknown        | 7         | 2.3%    |
| 2001-3000      | 3         | 0.99%   |
| More than 3000 | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2         | 4      | 3.85%   |
| WDC WD2000JD-00HBB0 200GB             | 2         | 4      | 3.85%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 5      | 3.85%   |
| Samsung Electronics SP2504C 250GB     | 2         | 2      | 3.85%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 5      | 3.85%   |
| Kingston SV300S37A60G 64GB SSD        | 2         | 2      | 3.85%   |
| A-DATA Technology SU800NS38 512GB SSD | 2         | 3      | 3.85%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1         | 1      | 1.92%   |
| WDC WD800JD-60MSA1 80GB               | 1         | 1      | 1.92%   |
| WDC WD5002AALX-00J37A0 500GB          | 1         | 1      | 1.92%   |
| WDC WD5001AALS-00E3A0 500GB           | 1         | 1      | 1.92%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 1.92%   |
| WDC WD3200BEVT-75ZCT0 320GB           | 1         | 4      | 1.92%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1         | 1      | 1.92%   |
| WDC WD1600BEVS-60RST0 160GB           | 1         | 1      | 1.92%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.92%   |
| Toshiba MK8034GSX 80GB                | 1         | 1      | 1.92%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.92%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 1.92%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.92%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.92%   |
| Seagate ST9500325AS 500GB             | 1         | 3      | 1.92%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.92%   |
| Seagate ST3500820AS 500GB             | 1         | 1      | 1.92%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 1.92%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 1.92%   |
| Seagate ST340016A 40GB                | 1         | 1      | 1.92%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 1.92%   |
| Seagate ST3250312AS 250GB             | 1         | 1      | 1.92%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.92%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.92%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 1      | 1.92%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 1.92%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 1.92%   |
| Samsung Electronics HN-M750MBB 752GB  | 1         | 1      | 1.92%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 1.92%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 1.92%   |
| Hitachi HTS542525K9A300 250GB         | 1         | 1      | 1.92%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 20     | 28%     |
| WDC                 | 12        | 20     | 24%     |
| Samsung Electronics | 6         | 9      | 12%     |
| Toshiba             | 5         | 5      | 10%     |
| HGST                | 5         | 7      | 10%     |
| Kingston            | 3         | 3      | 6%      |
| Hitachi             | 3         | 3      | 6%      |
| A-DATA Technology   | 2         | 3      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 20     | 32.56%  |
| WDC                 | 11        | 19     | 25.58%  |
| Toshiba             | 5         | 5      | 11.63%  |
| Samsung Electronics | 5         | 8      | 11.63%  |
| HGST                | 5         | 7      | 11.63%  |
| Hitachi             | 3         | 3      | 6.98%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 62     | 83.33%  |
| SSD  | 5         | 6      | 11.9%   |
| NVMe | 2         | 2      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 130       | 240    | 43.77%  |
| Works    | 124       | 225    | 41.75%  |
| Malfunc  | 41        | 70     | 13.8%   |
| Failed   | 2         | 2      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 201       | 61.47%  |
| AMD                              | 42        | 12.84%  |
| Samsung Electronics              | 25        | 7.65%   |
| SanDisk                          | 10        | 3.06%   |
| SK hynix                         | 7         | 2.14%   |
| JMicron Technology               | 7         | 2.14%   |
| Nvidia                           | 6         | 1.83%   |
| Marvell Technology Group         | 5         | 1.53%   |
| KIOXIA                           | 4         | 1.22%   |
| Toshiba America Info Systems     | 3         | 0.92%   |
| Micron Technology                | 3         | 0.92%   |
| Kingston Technology Company      | 3         | 0.92%   |
| ADATA Technology                 | 3         | 0.92%   |
| Union Memory (Shenzhen)          | 2         | 0.61%   |
| Silicon Motion                   | 2         | 0.61%   |
| Phison Electronics               | 2         | 0.61%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Realtek Semiconductor            | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 7.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 4.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 4.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 4.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 2.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9         | 2.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 9         | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9         | 2.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 8         | 2.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.57%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 1.31%   |
| JMicron JMB368 IDE controller                                                  | 5         | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.04%   |
| Nvidia MCP61 SATA Controller                                                   | 4         | 1.04%   |
| Nvidia MCP61 IDE                                                               | 4         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.04%   |
| Intel SSD 660P Series                                                          | 4         | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4         | 1.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 4         | 1.04%   |
| AMD FCH IDE Controller                                                         | 4         | 1.04%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 0.78%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 0.78%   |
| Micron Non-Volatile memory controller                                          | 3         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 201       | 60%     |
| NVMe | 66        | 19.7%   |
| IDE  | 55        | 16.42%  |
| RAID | 13        | 3.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 209       | 78.28%  |
| AMD    | 56        | 20.97%  |
| ARM    | 2         | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.5%    |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 1.5%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.12%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 1.12%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.12%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.12%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.12%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.12%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.75%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2         | 0.75%   |
| Intel Pentium D CPU 3.40GHz                   | 2         | 0.75%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.75%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.75%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.75%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.75%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.75%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.75%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.75%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2         | 0.75%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.75%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.75%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 61        | 22.85%  |
| Intel Core i7           | 42        | 15.73%  |
| Intel Core i3           | 26        | 9.74%   |
| Intel Core 2 Duo        | 19        | 7.12%   |
| AMD Ryzen 5             | 15        | 5.62%   |
| Intel Celeron           | 13        | 4.87%   |
| Other                   | 12        | 4.49%   |
| Intel Pentium           | 9         | 3.37%   |
| AMD Ryzen 7             | 8         | 3%      |
| AMD A8                  | 7         | 2.62%   |
| Intel Pentium Dual-Core | 6         | 2.25%   |
| Intel Pentium Dual      | 6         | 2.25%   |
| Intel Pentium D         | 5         | 1.87%   |
| Intel Core 2            | 5         | 1.87%   |
| Intel Core 2 Quad       | 4         | 1.5%    |
| Intel Genuine           | 3         | 1.12%   |
| AMD Athlon 64 X2        | 3         | 1.12%   |
| AMD Ryzen 3             | 2         | 0.75%   |
| AMD FX                  | 2         | 0.75%   |
| AMD E1                  | 2         | 0.75%   |
| AMD Athlon II X2        | 2         | 0.75%   |
| AMD A10                 | 2         | 0.75%   |
| Intel Xeon              | 1         | 0.37%   |
| Intel Pentium 4         | 1         | 0.37%   |
| Intel Atom              | 1         | 0.37%   |
| AMD Turion 64 X2 Mobile | 1         | 0.37%   |
| AMD Ryzen Threadripper  | 1         | 0.37%   |
| AMD Ryzen 9             | 1         | 0.37%   |
| AMD Ryzen 7 PRO         | 1         | 0.37%   |
| AMD Ryzen 5 PRO         | 1         | 0.37%   |
| AMD E2                  | 1         | 0.37%   |
| AMD E                   | 1         | 0.37%   |
| AMD C-70                | 1         | 0.37%   |
| AMD Athlon II X3        | 1         | 0.37%   |
| AMD Athlon              | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 145       | 53.9%   |
| 4       | 81        | 30.11%  |
| 6       | 18        | 6.69%   |
| 8       | 9         | 3.35%   |
| 1       | 7         | 2.6%    |
| 3       | 4         | 1.49%   |
| Unknown | 2         | 0.74%   |
| 24      | 1         | 0.37%   |
| 14      | 1         | 0.37%   |
| 12      | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 266       | 99.63%  |
| Unknown | 1         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 160       | 59.48%  |
| 1       | 107       | 39.78%  |
| Unknown | 2         | 0.74%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 263       | 98.5%   |
| Unknown        | 3         | 1.12%   |
| 32-bit         | 1         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 18.32%  |
| 0x306c3    | 16        | 5.86%   |
| 0x306a9    | 13        | 4.76%   |
| 0x206a7    | 13        | 4.76%   |
| 0x1067a    | 13        | 4.76%   |
| 0x406e3    | 11        | 4.03%   |
| 0x6fd      | 10        | 3.66%   |
| 0x906ea    | 9         | 3.3%    |
| 0x30678    | 8         | 2.93%   |
| 0x20655    | 8         | 2.93%   |
| 0x10676    | 7         | 2.56%   |
| 0x806ec    | 6         | 2.2%    |
| 0x306d4    | 6         | 2.2%    |
| 0x06001119 | 6         | 2.2%    |
| 0x806c1    | 5         | 1.83%   |
| 0x506e3    | 5         | 1.83%   |
| 0x906e9    | 4         | 1.47%   |
| 0x40651    | 4         | 1.47%   |
| 0x08701021 | 4         | 1.47%   |
| 0x08108102 | 4         | 1.47%   |
| 0xa0652    | 3         | 1.1%    |
| 0x806ea    | 3         | 1.1%    |
| 0x806e9    | 3         | 1.1%    |
| 0x6fb      | 3         | 1.1%    |
| 0x6f6      | 3         | 1.1%    |
| 0x20652    | 3         | 1.1%    |
| 0x05000119 | 3         | 1.1%    |
| 0xf65      | 2         | 0.73%   |
| 0xf47      | 2         | 0.73%   |
| 0x906ed    | 2         | 0.73%   |
| 0x706a1    | 2         | 0.73%   |
| 0x6fa      | 2         | 0.73%   |
| 0x6f2      | 2         | 0.73%   |
| 0x406c3    | 2         | 0.73%   |
| 0x106e5    | 2         | 0.73%   |
| 0x0a50000c | 2         | 0.73%   |
| 0x0a201009 | 2         | 0.73%   |
| 0x08600103 | 2         | 0.73%   |
| 0x08108109 | 2         | 0.73%   |
| 0x06003106 | 2         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 34        | 12.73%  |
| Haswell       | 26        | 9.74%   |
| Core          | 23        | 8.61%   |
| Penryn        | 20        | 7.49%   |
| Skylake       | 19        | 7.12%   |
| SandyBridge   | 16        | 5.99%   |
| IvyBridge     | 16        | 5.99%   |
| Zen 2         | 13        | 4.87%   |
| Westmere      | 13        | 4.87%   |
| Silvermont    | 12        | 4.49%   |
| Zen+          | 8         | 3%      |
| Piledriver    | 7         | 2.62%   |
| Zen 3         | 6         | 2.25%   |
| NetBurst      | 6         | 2.25%   |
| Broadwell     | 6         | 2.25%   |
| TigerLake     | 5         | 1.87%   |
| K8 Hammer     | 5         | 1.87%   |
| Unknown       | 4         | 1.5%    |
| K10           | 3         | 1.12%   |
| Goldmont plus | 3         | 1.12%   |
| CometLake     | 3         | 1.12%   |
| Bobcat        | 3         | 1.12%   |
| Zen           | 2         | 0.75%   |
| Steamroller   | 2         | 0.75%   |
| Puma          | 2         | 0.75%   |
| Nehalem       | 2         | 0.75%   |
| IceLake       | 2         | 0.75%   |
| Excavator     | 2         | 0.75%   |
| P6            | 1         | 0.37%   |
| Jaguar        | 1         | 0.37%   |
| Goldmont      | 1         | 0.37%   |
| Bulldozer     | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 153       | 48.26%  |
| Nvidia | 97        | 30.6%   |
| AMD    | 67        | 21.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 13        | 3.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 11        | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 11        | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 10        | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                           | 9         | 2.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 8         | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 8         | 2.42%   |
| AMD Renoir                                                                    | 7         | 2.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 6         | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 6         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 5         | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 1.52%   |
| Intel HD Graphics 5500                                                        | 5         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 4         | 1.21%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 4         | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 3         | 0.91%   |
| Intel UHD Graphics 620                                                        | 3         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 0.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 0.91%   |
| Intel HD Graphics 620                                                         | 3         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 3         | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 2         | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 2         | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2         | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 0.61%   |
| Nvidia GF106 [GeForce GTS 450]                                                | 2         | 0.61%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 0.61%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 2         | 0.61%   |
| Nvidia G84 [GeForce 8600 GT]                                                  | 2         | 0.61%   |
| Nvidia G72 [GeForce 7300 GS]                                                  | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 106       | 39.41%  |
| 1 x Nvidia     | 57        | 21.19%  |
| 1 x AMD        | 48        | 17.84%  |
| Intel + Nvidia | 36        | 13.38%  |
| Intel + AMD    | 8         | 2.97%   |
| 2 x AMD        | 7         | 2.6%    |
| AMD + Nvidia   | 3         | 1.12%   |
| Other          | 2         | 0.74%   |
| 2 x Nvidia     | 1         | 0.37%   |
| 2 x Intel      | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 211       | 76.45%  |
| Proprietary | 53        | 19.2%   |
| Unknown     | 12        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 45.85%  |
| 1.01-2.0   | 45        | 16.25%  |
| 0.01-0.5   | 44        | 15.88%  |
| 0.51-1.0   | 25        | 9.03%   |
| 3.01-4.0   | 18        | 6.5%    |
| 5.01-6.0   | 9         | 3.25%   |
| 7.01-8.0   | 6         | 2.17%   |
| 2.01-3.0   | 1         | 0.36%   |
| 16.01-24.0 | 1         | 0.36%   |
| 8.01-16.0  | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 16.78%  |
| Samsung Electronics     | 42        | 14.69%  |
| LG Display              | 34        | 11.89%  |
| BOE                     | 22        | 7.69%   |
| Goldstar                | 19        | 6.64%   |
| Dell                    | 19        | 6.64%   |
| Chimei Innolux          | 19        | 6.64%   |
| BenQ                    | 11        | 3.85%   |
| Philips                 | 9         | 3.15%   |
| Lenovo                  | 6         | 2.1%    |
| Ancor Communications    | 6         | 2.1%    |
| Hewlett-Packard         | 5         | 1.75%   |
| Chi Mei Optoelectronics | 5         | 1.75%   |
| AOC                     | 5         | 1.75%   |
| PANDA                   | 3         | 1.05%   |
| LG Electronics          | 3         | 1.05%   |
| ViewSonic               | 2         | 0.7%    |
| Unknown                 | 2         | 0.7%    |
| Sony                    | 2         | 0.7%    |
| Seiko/Epson             | 2         | 0.7%    |
| NEC Computers           | 2         | 0.7%    |
| InfoVision              | 2         | 0.7%    |
| Hitachi                 | 2         | 0.7%    |
| Arnos Instruments       | 2         | 0.7%    |
| Wacom                   | 1         | 0.35%   |
| Tianma XM               | 1         | 0.35%   |
| Sharp                   | 1         | 0.35%   |
| Quanta Display          | 1         | 0.35%   |
| Plain Tree Systems      | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| LGD                     | 1         | 0.35%   |
| LG Philips              | 1         | 0.35%   |
| IBM                     | 1         | 0.35%   |
| HYO                     | 1         | 0.35%   |
| FUS                     | 1         | 0.35%   |
| Apple                   | 1         | 0.35%   |
| ANX                     | 1         | 0.35%   |
| Acer                    | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 3         | 1%      |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 3         | 1%      |
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                     | 3         | 1%      |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1%      |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1%      |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch        | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.67%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                 | 2         | 0.67%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.67%   |
| LG Electronics LCD Monitor LG TV 1920x1080                               | 2         | 0.67%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.67%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.67%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 0.67%   |
| Dell LCD Monitor U2414H                                                  | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.67%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.67%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.67%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                       | 2         | 0.67%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.67%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch    | 2         | 0.67%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                 | 1         | 0.33%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch            | 1         | 0.33%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch              | 1         | 0.33%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                             | 1         | 0.33%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                               | 1         | 0.33%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.33%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                    | 1         | 0.33%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.33%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 0.33%   |
| Seiko/Epson LCD Monitor 1366x768                                         | 1         | 0.33%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 95        | 34.93%  |
| 1366x768 (WXGA)    | 64        | 23.53%  |
| 1600x900 (HD+)     | 16        | 5.88%   |
| 1280x1024 (SXGA)   | 15        | 5.51%   |
| 3840x2160 (4K)     | 12        | 4.41%   |
| 2560x1440 (QHD)    | 12        | 4.41%   |
| 1680x1050 (WSXGA+) | 10        | 3.68%   |
| 1440x900 (WXGA+)   | 10        | 3.68%   |
| 1280x800 (WXGA)    | 10        | 3.68%   |
| 1920x1200 (WUXGA)  | 5         | 1.84%   |
| Unknown            | 4         | 1.47%   |
| 3440x1440          | 3         | 1.1%    |
| 2560x1080          | 2         | 0.74%   |
| 1024x768 (XGA)     | 2         | 0.74%   |
| 800x1280           | 1         | 0.37%   |
| 7680x2160          | 1         | 0.37%   |
| 4480x1440          | 1         | 0.37%   |
| 3840x1080          | 1         | 0.37%   |
| 3520x1200          | 1         | 0.37%   |
| 3456x2160          | 1         | 0.37%   |
| 3000x2000          | 1         | 0.37%   |
| 2960x1050          | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 1360x768           | 1         | 0.37%   |
| 1280x960           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 101       | 35.31%  |
| 17      | 25        | 8.74%   |
| 14      | 20        | 6.99%   |
| 27      | 18        | 6.29%   |
| 24      | 18        | 6.29%   |
| 13      | 17        | 5.94%   |
| Unknown | 17        | 5.94%   |
| 23      | 11        | 3.85%   |
| 12      | 11        | 3.85%   |
| 19      | 9         | 3.15%   |
| 22      | 6         | 2.1%    |
| 21      | 6         | 2.1%    |
| 20      | 5         | 1.75%   |
| 18      | 4         | 1.4%    |
| 34      | 3         | 1.05%   |
| 25      | 3         | 1.05%   |
| 11      | 3         | 1.05%   |
| 40      | 2         | 0.7%    |
| 35      | 2         | 0.7%    |
| 84      | 1         | 0.35%   |
| 43      | 1         | 0.35%   |
| 33      | 1         | 0.35%   |
| 31      | 1         | 0.35%   |
| 26      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 135       | 48.56%  |
| 501-600     | 44        | 15.83%  |
| 351-400     | 27        | 9.71%   |
| 401-500     | 22        | 7.91%   |
| 201-300     | 21        | 7.55%   |
| Unknown     | 17        | 6.12%   |
| 801-900     | 4         | 1.44%   |
| 701-800     | 4         | 1.44%   |
| 601-700     | 2         | 0.72%   |
| 1501-2000   | 1         | 0.36%   |
| 901-1000    | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 184       | 71.04%  |
| 16/10   | 33        | 12.74%  |
| 5/4     | 16        | 6.18%   |
| Unknown | 15        | 5.79%   |
| 21/9    | 5         | 1.93%   |
| 3/2     | 3         | 1.16%   |
| 4/3     | 2         | 0.77%   |
| 0.62    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 34.98%  |
| 201-250        | 37        | 13.07%  |
| 81-90          | 33        | 11.66%  |
| 301-350        | 18        | 6.36%   |
| 151-200        | 18        | 6.36%   |
| Unknown        | 17        | 6.01%   |
| 121-130        | 14        | 4.95%   |
| 61-70          | 11        | 3.89%   |
| 141-150        | 9         | 3.18%   |
| 351-500        | 7         | 2.47%   |
| 251-300        | 5         | 1.77%   |
| 71-80          | 4         | 1.41%   |
| 51-60          | 3         | 1.06%   |
| 501-1000       | 3         | 1.06%   |
| 131-140        | 2         | 0.71%   |
| 91-100         | 2         | 0.71%   |
| More than 1000 | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 86        | 30.82%  |
| 121-160       | 82        | 29.39%  |
| 101-120       | 78        | 27.96%  |
| Unknown       | 17        | 6.09%   |
| 161-240       | 11        | 3.94%   |
| More than 240 | 3         | 1.08%   |
| 1-50          | 2         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 227       | 83.46%  |
| 2     | 34        | 12.5%   |
| 0     | 7         | 2.57%   |
| 3     | 4         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 146       | 36.41%  |
| Intel                             | 119       | 29.68%  |
| Qualcomm Atheros                  | 50        | 12.47%  |
| Broadcom                          | 24        | 5.99%   |
| Broadcom Limited                  | 9         | 2.24%   |
| Ralink                            | 8         | 2%      |
| Marvell Technology Group          | 8         | 2%      |
| TP-Link                           | 6         | 1.5%    |
| Ralink Technology                 | 6         | 1.5%    |
| Nvidia                            | 5         | 1.25%   |
| Xiaomi                            | 2         | 0.5%    |
| Samsung Electronics               | 2         | 0.5%    |
| Qualcomm Atheros Communications   | 2         | 0.5%    |
| MediaTek                          | 2         | 0.5%    |
| Hewlett-Packard                   | 2         | 0.5%    |
| ASIX Electronics                  | 2         | 0.5%    |
| vivo                              | 1         | 0.25%   |
| U-Blox                            | 1         | 0.25%   |
| Sundance Technology Inc / IC Plus | 1         | 0.25%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.25%   |
| Lenovo                            | 1         | 0.25%   |
| Huawei Technologies               | 1         | 0.25%   |
| Aquantia                          | 1         | 0.25%   |
| 3Com                              | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 99        | 20.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 28        | 5.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.88%   |
| Intel Wireless 8260                                                     | 9         | 1.88%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.67%   |
| Intel Wireless 3160                                                     | 7         | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.05%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.84%   |
| Intel Wireless 7265                                                     | 4         | 0.84%   |
| Intel Wireless 7260                                                     | 4         | 0.84%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.84%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.84%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.63%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.63%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 0.63%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.63%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.63%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 46.92%  |
| Qualcomm Atheros                | 39        | 18.48%  |
| Realtek Semiconductor           | 30        | 14.22%  |
| Broadcom                        | 16        | 7.58%   |
| Ralink                          | 8         | 3.79%   |
| TP-Link                         | 6         | 2.84%   |
| Ralink Technology               | 6         | 2.84%   |
| Broadcom Limited                | 4         | 1.9%    |
| Qualcomm Atheros Communications | 2         | 0.95%   |
| MediaTek                        | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 4.25%   |
| Intel Wireless 8260                                                     | 9         | 4.25%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 4.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.77%   |
| Intel Wireless 3160                                                     | 7         | 3.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.36%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 2.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.36%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.89%   |
| Intel Wireless 7265                                                     | 4         | 1.89%   |
| Intel Wireless 7260                                                     | 4         | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.89%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.94%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 138       | 53.49%  |
| Intel                             | 57        | 22.09%  |
| Qualcomm Atheros                  | 18        | 6.98%   |
| Broadcom                          | 12        | 4.65%   |
| Marvell Technology Group          | 8         | 3.1%    |
| Nvidia                            | 5         | 1.94%   |
| Broadcom Limited                  | 5         | 1.94%   |
| Xiaomi                            | 2         | 0.78%   |
| Samsung Electronics               | 2         | 0.78%   |
| ASIX Electronics                  | 2         | 0.78%   |
| vivo                              | 1         | 0.39%   |
| Sundance Technology Inc / IC Plus | 1         | 0.39%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.39%   |
| MediaTek                          | 1         | 0.39%   |
| Lenovo                            | 1         | 0.39%   |
| Huawei Technologies               | 1         | 0.39%   |
| Hewlett-Packard                   | 1         | 0.39%   |
| Aquantia                          | 1         | 0.39%   |
| 3Com                              | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 99        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 28        | 10.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10        | 3.79%   |
| Realtek RTL8125 2.5GbE Controller                                          | 6         | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4         | 1.52%   |
| Intel Ethernet Connection I217-LM                                          | 4         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                       | 4         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                                   | 4         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3         | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 3         | 1.14%   |
| Nvidia MCP61 Ethernet                                                      | 3         | 1.14%   |
| Intel I211 Gigabit Network Connection                                      | 3         | 1.14%   |
| Intel Ethernet Connection I219-V                                           | 3         | 1.14%   |
| Intel Ethernet Connection I219-LM                                          | 3         | 1.14%   |
| Intel Ethernet Connection I217-V                                           | 3         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.76%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2         | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.76%   |
| Intel Ethernet Connection I218-LM                                          | 2         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                       | 2         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.76%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 2         | 0.76%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                     | 2         | 0.76%   |
| ASIX AX88772B                                                              | 2         | 0.76%   |
| vivo 1806                                                                  | 1         | 0.38%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1         | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1         | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 247       | 54.41%  |
| WiFi     | 205       | 45.15%  |
| Modem    | 2         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 62.41%  |
| Ethernet | 103       | 37.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 173       | 64.79%  |
| 1     | 85        | 31.84%  |
| 0     | 5         | 1.87%   |
| 3     | 4         | 1.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 256       | 95.88%  |
| Yes  | 11        | 4.12%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 41.18%  |
| Realtek Semiconductor           | 17        | 11.11%  |
| Lite-On Technology              | 12        | 7.84%   |
| IMC Networks                    | 12        | 7.84%   |
| Qualcomm Atheros Communications | 10        | 6.54%   |
| Broadcom                        | 9         | 5.88%   |
| Cambridge Silicon Radio         | 7         | 4.58%   |
| Dell                            | 5         | 3.27%   |
| Hewlett-Packard                 | 4         | 2.61%   |
| Toshiba                         | 3         | 1.96%   |
| Apple                           | 3         | 1.96%   |
| Ralink                          | 2         | 1.31%   |
| ASUSTek Computer                | 2         | 1.31%   |
| Taiyo Yuden                     | 1         | 0.65%   |
| Ralink Technology               | 1         | 0.65%   |
| Qcom                            | 1         | 0.65%   |
| Foxconn / Hon Hai               | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 26        | 16.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 7.19%   |
| Realtek Bluetooth Radio                             | 10        | 6.54%   |
| Intel AX200 Bluetooth                               | 9         | 5.88%   |
| Intel AX201 Bluetooth                               | 8         | 5.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 4.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.27%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.96%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.96%   |
| Lite-On Bluetooth Device                            | 3         | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.96%   |
| IMC Networks Bluetooth Device                       | 3         | 1.96%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.31%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.31%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.31%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.31%   |
| Intel AX210 Bluetooth                               | 2         | 1.31%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.31%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.31%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.31%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.31%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.31%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.65%   |
| Toshiba Bluetooth Device                            | 1         | 0.65%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.65%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.65%   |
| Lite-On BCM43142A0                                  | 1         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.65%   |
| Intel Bluetooth Device                              | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 207       | 57.02%  |
| AMD                              | 66        | 18.18%  |
| Nvidia                           | 61        | 16.8%   |
| C-Media Electronics              | 8         | 2.2%    |
| Yamaha                           | 2         | 0.55%   |
| Realtek Semiconductor            | 2         | 0.55%   |
| Logitech                         | 2         | 0.55%   |
| Creative Technology              | 2         | 0.55%   |
| Creative Labs                    | 2         | 0.55%   |
| Unknown                          | 1         | 0.28%   |
| Syntek                           | 1         | 0.28%   |
| SteelSeries ApS                  | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Microsoft                        | 1         | 0.28%   |
| Lenovo                           | 1         | 0.28%   |
| JMTek                            | 1         | 0.28%   |
| GYROCOM C&C                      | 1         | 0.28%   |
| GN Netcom                        | 1         | 0.28%   |
| FIFINE 683 Microphone            | 1         | 0.28%   |
| Apple                            | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 4.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 4.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 4.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 3.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 3.32%   |
| AMD FCH Azalia Controller                                                  | 12        | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 2.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 10        | 2.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 2.37%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.42%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 1.42%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.18%   |
| AMD Trinity HDMI Audio Controller                                          | 5         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.95%   |
| Nvidia MCP61 High Definition Audio                                         | 4         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 0.95%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                         | 3         | 0.71%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.71%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 19.59%  |
| Kingston            | 36        | 18.56%  |
| Unknown             | 35        | 18.04%  |
| SK hynix            | 35        | 18.04%  |
| Micron Technology   | 14        | 7.22%   |
| Crucial             | 10        | 5.15%   |
| Corsair             | 8         | 4.12%   |
| G.Skill             | 6         | 3.09%   |
| Elpida              | 3         | 1.55%   |
| Ramaxel Technology  | 2         | 1.03%   |
| A-DATA Technology   | 2         | 1.03%   |
| Toshiba             | 1         | 0.52%   |
| Team                | 1         | 0.52%   |
| Ramos Technology    | 1         | 0.52%   |
| PNY                 | 1         | 0.52%   |
| Goodram             | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 4         | 1.87%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 4         | 1.87%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s | 3         | 1.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s    | 3         | 1.4%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 2         | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 2         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 2         | 0.93%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2         | 0.93%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 2         | 0.93%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 2         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.93%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 2         | 0.93%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s    | 2         | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 0.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 0.93%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 0.93%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s    | 2         | 0.93%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s   | 2         | 0.93%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 2         | 0.93%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s  | 2         | 0.93%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s  | 2         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s              | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s               | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s            | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s            | 1         | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s              | 1         | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1         | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1         | 0.47%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s             | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s            | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DRAM                       | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                       | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 64        | 40.76%  |
| DDR4    | 59        | 37.58%  |
| DDR2    | 14        | 8.92%   |
| Unknown | 8         | 5.1%    |
| SDRAM   | 5         | 3.18%   |
| LPDDR4  | 3         | 1.91%   |
| DDR     | 3         | 1.91%   |
| DRAM    | 1         | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 109       | 69.43%  |
| DIMM         | 44        | 28.03%  |
| Row Of Chips | 3         | 1.91%   |
| Chip         | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 60        | 33.71%  |
| 8192  | 52        | 29.21%  |
| 2048  | 36        | 20.22%  |
| 16384 | 14        | 7.87%   |
| 1024  | 11        | 6.18%   |
| 32768 | 3         | 1.69%   |
| 512   | 2         | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 21.43%  |
| 2667    | 25        | 13.74%  |
| 667     | 16        | 8.79%   |
| 1333    | 15        | 8.24%   |
| 2133    | 14        | 7.69%   |
| 3200    | 12        | 6.59%   |
| 1334    | 11        | 6.04%   |
| 2400    | 8         | 4.4%    |
| Unknown | 6         | 3.3%    |
| 800     | 5         | 2.75%   |
| 1066    | 4         | 2.2%    |
| 3466    | 3         | 1.65%   |
| 1867    | 3         | 1.65%   |
| 4267    | 2         | 1.1%    |
| 3266    | 2         | 1.1%    |
| 3000    | 2         | 1.1%    |
| 1067    | 2         | 1.1%    |
| 533     | 2         | 1.1%    |
| 4199    | 1         | 0.55%   |
| 3866    | 1         | 0.55%   |
| 3800    | 1         | 0.55%   |
| 3600    | 1         | 0.55%   |
| 2448    | 1         | 0.55%   |
| 2134    | 1         | 0.55%   |
| 1866    | 1         | 0.55%   |
| 1800    | 1         | 0.55%   |
| 1639    | 1         | 0.55%   |
| 975     | 1         | 0.55%   |
| 200     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Samsung Electronics | 3         | 33.33%  |
| Canon               | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Samsung SCX-4216F Scanner | 1         | 11.11%  |
| Samsung SCX-4100 Scanner  | 1         | 11.11%  |
| Samsung SCX-3200 Series   | 1         | 11.11%  |
| HP Officejet 4500 G510g-m | 1         | 11.11%  |
| HP LaserJet 1018          | 1         | 11.11%  |
| HP LaserJet 1010          | 1         | 11.11%  |
| HP DeskJet 5940           | 1         | 11.11%  |
| Canon PIXMA MG3000 series | 1         | 11.11%  |
| Brother DCP-L2510D series | 1         | 11.11%  |

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


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 23.7%   |
| IMC Networks                           | 20        | 11.56%  |
| Realtek Semiconductor                  | 17        | 9.83%   |
| Microdia                               | 10        | 5.78%   |
| Acer                                   | 10        | 5.78%   |
| Logitech                               | 9         | 5.2%    |
| Suyin                                  | 8         | 4.62%   |
| Sunplus Innovation Technology          | 7         | 4.05%   |
| Quanta                                 | 7         | 4.05%   |
| Lite-On Technology                     | 6         | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.47%   |
| Syntek                                 | 5         | 2.89%   |
| Z-Star Microelectronics                | 3         | 1.73%   |
| Silicon Motion                         | 3         | 1.73%   |
| Luxvisions Innotech Limited            | 3         | 1.73%   |
| Samsung Electronics                    | 2         | 1.16%   |
| Ricoh                                  | 2         | 1.16%   |
| Genesys Logic                          | 2         | 1.16%   |
| Apple                                  | 2         | 1.16%   |
| Tobii Technology AB                    | 1         | 0.58%   |
| Primax Electronics                     | 1         | 0.58%   |
| Pixart Imaging                         | 1         | 0.58%   |
| OmniVision Technologies                | 1         | 0.58%   |
| Microsoft                              | 1         | 0.58%   |
| Lenovo                                 | 1         | 0.58%   |
| KYE Systems (Mouse Systems)            | 1         | 0.58%   |
| GEMBIRD                                | 1         | 0.58%   |
| DigiTech                               | 1         | 0.58%   |
| Cubeternet                             | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam        | 6         | 3.43%   |
| Chicony Integrated Camera                | 6         | 3.43%   |
| Realtek Integrated_Webcam_HD             | 5         | 2.86%   |
| IMC Networks Integrated Camera           | 5         | 2.86%   |
| Realtek USB Camera                       | 4         | 2.29%   |
| Chicony HD WebCam                        | 4         | 2.29%   |
| Acer Lenovo EasyCamera                   | 4         | 2.29%   |
| Sunplus Asus Webcam                      | 3         | 1.71%   |
| Realtek Integrated Webcam                | 3         | 1.71%   |
| Lite-On Integrated Camera                | 3         | 1.71%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 1.71%   |
| Chicony HP HD Camera                     | 3         | 1.71%   |
| Chicony HD User Facing                   | 3         | 1.71%   |
| Acer Integrated Camera                   | 3         | 1.71%   |
| Z-Star A4 TECH HD PC Camera              | 2         | 1.14%   |
| Suyin HD WebCam                          | 2         | 1.14%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.14%   |
| Samsung Galaxy A5 (MTP)                  | 2         | 1.14%   |
| Realtek HP Webcam                        | 2         | 1.14%   |
| Quanta HD Webcam                         | 2         | 1.14%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.14%   |
| Microdia Integrated Webcam               | 2         | 1.14%   |
| Logitech Webcam C270                     | 2         | 1.14%   |
| Logitech Webcam C170                     | 2         | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 2         | 1.14%   |
| IMC Networks USB2.0 UVC HD Webcam        | 2         | 1.14%   |
| Genesys Logic Camera                     | 2         | 1.14%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 1.14%   |
| Chicony TOSHIBA Web Camera - HD          | 2         | 1.14%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.14%   |
| Chicony HP HD Webcam                     | 2         | 1.14%   |
| Chicony CNF9055 Toshiba Webcam           | 2         | 1.14%   |
| Apple iPhone5/5C/5S/6                    | 2         | 1.14%   |
| Z-Star Vega USB 2.0 Camera               | 1         | 0.57%   |
| Tobii AB EyeChip                         | 1         | 0.57%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S     | 1         | 0.57%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera    | 1         | 0.57%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.57%   |
| Syntek Integrated Camera                 | 1         | 0.57%   |
| Syntek EasyCamera                        | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 44.44%  |
| Synaptics                  | 8         | 22.22%  |
| AuthenTec                  | 3         | 8.33%   |
| Upek                       | 2         | 5.56%   |
| STMicroelectronics         | 2         | 5.56%   |
| Shenzhen Goodix Technology | 2         | 5.56%   |
| Elan Microelectronics      | 2         | 5.56%   |
| LighTuning Technology      | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 8.33%   |
| Validity Sensors VFS491                                                    | 2         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.56%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 5.56%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 5.56%   |
| Unknown                                                                    | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.78%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.78%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.78%   |
| AuthenTec AES1600                                                          | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 12        | 57.14%  |
| Broadcom    | 5         | 23.81%  |
| Lenovo      | 2         | 9.52%   |
| Upek        | 1         | 4.76%   |
| O2 Micro    | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 12        | 57.14%  |
| Broadcom 58200                                             | 4         | 19.05%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 9.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.76%   |
| Broadcom 5880                                              | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 196       | 71.27%  |
| 1     | 61        | 22.18%  |
| 2     | 16        | 5.82%   |
| 3     | 2         | 0.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 37.89%  |
| Graphics card            | 21        | 22.11%  |
| Chipcard                 | 16        | 16.84%  |
| Net/wireless             | 7         | 7.37%   |
| Multimedia controller    | 4         | 4.21%   |
| Communication controller | 3         | 3.16%   |
| Camera                   | 2         | 2.11%   |
| Bluetooth                | 2         | 2.11%   |
| Storage/raid             | 1         | 1.05%   |
| Storage                  | 1         | 1.05%   |
| Net/ethernet             | 1         | 1.05%   |
| Card reader              | 1         | 1.05%   |

