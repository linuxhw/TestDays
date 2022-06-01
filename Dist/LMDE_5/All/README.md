LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 99

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 27        | 35.06%  |
| 5.10.0-14-amd64      | 22        | 28.57%  |
| 5.10.0-12-amd64      | 17        | 22.08%  |
| 5.10.0-13-686        | 6         | 7.79%   |
| 5.16.0-0.bpo.4-amd64 | 1         | 1.3%    |
| 5.16.0-0.bpo.3-amd64 | 1         | 1.3%    |
| 5.15.0-0.bpo.3-amd64 | 1         | 1.3%    |
| 5.10.0-14-686        | 1         | 1.3%    |
| 5.10.0-11-686        | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 71        | 95.95%  |
| 5.16.0  | 2         | 2.7%    |
| 5.15.0  | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 71        | 95.95%  |
| 5.16    | 2         | 2.7%    |
| 5.15    | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 66        | 89.19%  |
| i686   | 8         | 10.81%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 67        | 90.54%  |
| Cinnamon   | 5         | 6.76%   |
| XFCE       | 1         | 1.35%   |
| MATE       | 1         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 74        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 62.16%  |
| LightDM | 28        | 37.84%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 35        | 47.3%   |
| pt_BR | 6         | 8.11%   |
| en_GB | 6         | 8.11%   |
| ru_RU | 4         | 5.41%   |
| es_ES | 4         | 5.41%   |
| de_DE | 4         | 5.41%   |
| it_IT | 2         | 2.7%    |
| fr_CA | 2         | 2.7%    |
| en_CA | 2         | 2.7%    |
| pl_PL | 1         | 1.35%   |
| nl_AW | 1         | 1.35%   |
| ko_KR | 1         | 1.35%   |
| fr_FR | 1         | 1.35%   |
| es_PE | 1         | 1.35%   |
| es_MX | 1         | 1.35%   |
| es_EC | 1         | 1.35%   |
| en_IE | 1         | 1.35%   |
| en_AU | 1         | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 42        | 56.76%  |
| BIOS | 32        | 43.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 68        | 91.89%  |
| Overlay | 4         | 5.41%   |
| Tmpfs   | 2         | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 62.16%  |
| GPT     | 21        | 28.38%  |
| MBR     | 7         | 9.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 91.89%  |
| Yes       | 6         | 8.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 87.84%  |
| Yes       | 9         | 12.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 20.27%  |
| Dell                | 12        | 16.22%  |
| Lenovo              | 9         | 12.16%  |
| Acer                | 9         | 12.16%  |
| ASUSTek Computer    | 8         | 10.81%  |
| MSI                 | 4         | 5.41%   |
| Apple               | 3         | 4.05%   |
| Toshiba             | 2         | 2.7%    |
| Gigabyte Technology | 2         | 2.7%    |
| Samsung Electronics | 1         | 1.35%   |
| Philco              | 1         | 1.35%   |
| Panasonic           | 1         | 1.35%   |
| Packard Bell        | 1         | 1.35%   |
| Medion              | 1         | 1.35%   |
| LincPlus            | 1         | 1.35%   |
| Intel               | 1         | 1.35%   |
| Howard Computers    | 1         | 1.35%   |
| Dixonsxp            | 1         | 1.35%   |
| ASRock              | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Dell Latitude E6400                              | 2         | 2.7%    |
| Toshiba Satellite M55                            | 1         | 1.35%   |
| Toshiba Satellite L455                           | 1         | 1.35%   |
| Samsung 730QDA                                   | 1         | 1.35%   |
| Philco 10D                                       | 1         | 1.35%   |
| Panasonic CF-H2BJJHZDE                           | 1         | 1.35%   |
| Packard Bell DOT S                               | 1         | 1.35%   |
| MSI MS-7B79                                      | 1         | 1.35%   |
| MSI MS-7B17                                      | 1         | 1.35%   |
| MSI MS-7977                                      | 1         | 1.35%   |
| MSI MS-7974                                      | 1         | 1.35%   |
| Medion E6220                                     | 1         | 1.35%   |
| LincPlus LINNCPLUS P1                            | 1         | 1.35%   |
| Lenovo Yoga 7 15ITL5 82BJ                        | 1         | 1.35%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 1.35%   |
| Lenovo ThinkCentre M92p 3238E9U                  | 1         | 1.35%   |
| Lenovo ThinkCentre M720s 10SUS9KW00              | 1         | 1.35%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 1.35%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS                | 1         | 1.35%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 1.35%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 1.35%   |
| Lenovo IdeaPad 3 14ALC6 82KT                     | 1         | 1.35%   |
| Intel DQ77MK AAG39642-400                        | 1         | 1.35%   |
| Howard Computers R7X                             | 1         | 1.35%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 1.35%   |
| HP Z820 Workstation                              | 1         | 1.35%   |
| HP Z600 Workstation                              | 1         | 1.35%   |
| HP ProBook 6570b                                 | 1         | 1.35%   |
| HP ProBook 450 G8 Notebook PC                    | 1         | 1.35%   |
| HP Presario C500 (GF581UA#ABA)                   | 1         | 1.35%   |
| HP Pavilion Laptop 15-eh1xxx                     | 1         | 1.35%   |
| HP Notebook                                      | 1         | 1.35%   |
| HP Laptop 14-df0xxx                              | 1         | 1.35%   |
| HP Laptop 14-cf3xxx                              | 1         | 1.35%   |
| HP ENVY 17                                       | 1         | 1.35%   |
| HP EliteBook 840 G1                              | 1         | 1.35%   |
| HP Compaq Pro 6300 SFF                           | 1         | 1.35%   |
| HP 255 G7 Notebook PC                            | 1         | 1.35%   |
| HP 14                                            | 1         | 1.35%   |
| Gigabyte Z68A-D3H-B3                             | 1         | 1.35%   |
| Gigabyte H110M-S2H                               | 1         | 1.35%   |
| Dell XPS A2010                                   | 1         | 1.35%   |
| Dell XPS 13 9305                                 | 1         | 1.35%   |
| Dell Vostro 3500                                 | 1         | 1.35%   |
| Dell Precision M4400                             | 1         | 1.35%   |
| Dell Precision 7520                              | 1         | 1.35%   |
| Dell Latitude 5511                               | 1         | 1.35%   |
| Dell Latitude 3410                               | 1         | 1.35%   |
| Dell Inspiron 5566                               | 1         | 1.35%   |
| Dell Inspiron 5559                               | 1         | 1.35%   |
| Dell Inspiron 14 5410 2-in-1                     | 1         | 1.35%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA           | 1         | 1.35%   |
| ASUS VivoBook E14 E402YA_L402YA                  | 1         | 1.35%   |
| ASUS PRIME H610M-A D4                            | 1         | 1.35%   |
| ASUS PRIME H510M-D                               | 1         | 1.35%   |
| ASUS PRIME B350M-A                               | 1         | 1.35%   |
| ASUS P6T                                         | 1         | 1.35%   |
| ASUS P5G41T-M LX3                                | 1         | 1.35%   |
| ASUS N61Jv                                       | 1         | 1.35%   |
| ASRock A320M-DGS                                 | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 6         | 8.11%   |
| Dell Latitude          | 4         | 5.41%   |
| Lenovo IdeaPad         | 3         | 4.05%   |
| Dell Inspiron          | 3         | 4.05%   |
| ASUS PRIME             | 3         | 4.05%   |
| Toshiba Satellite      | 2         | 2.7%    |
| Lenovo ThinkCentre     | 2         | 2.7%    |
| HP ProBook             | 2         | 2.7%    |
| HP Laptop              | 2         | 2.7%    |
| Dell XPS               | 2         | 2.7%    |
| Dell Precision         | 2         | 2.7%    |
| ASUS VivoBook          | 2         | 2.7%    |
| Samsung 730QDA         | 1         | 1.35%   |
| Philco 10D             | 1         | 1.35%   |
| Panasonic CF-H2BJJHZDE | 1         | 1.35%   |
| Packard Bell DOT       | 1         | 1.35%   |
| MSI MS-7B79            | 1         | 1.35%   |
| MSI MS-7B17            | 1         | 1.35%   |
| MSI MS-7977            | 1         | 1.35%   |
| MSI MS-7974            | 1         | 1.35%   |
| Medion E6220           | 1         | 1.35%   |
| LincPlus LINNCPLUS     | 1         | 1.35%   |
| Lenovo Yoga            | 1         | 1.35%   |
| Lenovo ThinkPad        | 1         | 1.35%   |
| Lenovo Legion          | 1         | 1.35%   |
| Lenovo IdeaPadFlex     | 1         | 1.35%   |
| Intel DQ77MK           | 1         | 1.35%   |
| Howard Computers R7X   | 1         | 1.35%   |
| HP ZBook               | 1         | 1.35%   |
| HP Z820                | 1         | 1.35%   |
| HP Z600                | 1         | 1.35%   |
| HP Presario            | 1         | 1.35%   |
| HP Pavilion            | 1         | 1.35%   |
| HP Notebook            | 1         | 1.35%   |
| HP ENVY                | 1         | 1.35%   |
| HP EliteBook           | 1         | 1.35%   |
| HP Compaq              | 1         | 1.35%   |
| HP 255                 | 1         | 1.35%   |
| HP 14                  | 1         | 1.35%   |
| Gigabyte Z68A-D3H-B3   | 1         | 1.35%   |
| Gigabyte H110M-S2H     | 1         | 1.35%   |
| Dell Vostro            | 1         | 1.35%   |
| ASUS P6T               | 1         | 1.35%   |
| ASUS P5G41T-M          | 1         | 1.35%   |
| ASUS N61Jv             | 1         | 1.35%   |
| ASRock A320M-DGS       | 1         | 1.35%   |
| Apple MacBookPro14     | 1         | 1.35%   |
| Apple MacBookAir7      | 1         | 1.35%   |
| Apple iMac5            | 1         | 1.35%   |
| Acer Veriton           | 1         | 1.35%   |
| Acer AOD270            | 1         | 1.35%   |
| Acer AOA110            | 1         | 1.35%   |
| Unknown                | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 12        | 16.22%  |
| 2020 | 7         | 9.46%   |
| 2012 | 7         | 9.46%   |
| 2018 | 6         | 8.11%   |
| 2016 | 5         | 6.76%   |
| 2013 | 5         | 6.76%   |
| 2010 | 5         | 6.76%   |
| 2019 | 4         | 5.41%   |
| 2017 | 4         | 5.41%   |
| 2011 | 4         | 5.41%   |
| 2009 | 4         | 5.41%   |
| 2007 | 4         | 5.41%   |
| 2015 | 3         | 4.05%   |
| 2008 | 3         | 4.05%   |
| 2006 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 48        | 64.86%  |
| Desktop     | 21        | 28.38%  |
| Convertible | 3         | 4.05%   |
| Tablet      | 1         | 1.35%   |
| All in one  | 1         | 1.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 68        | 90.67%  |
| Enabled  | 7         | 9.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 25.33%  |
| 3.01-4.0    | 16        | 21.33%  |
| 16.01-24.0  | 12        | 16%     |
| 8.01-16.0   | 9         | 12%     |
| 32.01-64.0  | 6         | 8%      |
| 1.01-2.0    | 6         | 8%      |
| 2.01-3.0    | 4         | 5.33%   |
| 24.01-32.0  | 2         | 2.67%   |
| 64.01-256.0 | 1         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 28        | 37.33%  |
| 2.01-3.0 | 25        | 33.33%  |
| 3.01-4.0 | 12        | 16%     |
| 0.51-1.0 | 6         | 8%      |
| 4.01-8.0 | 4         | 5.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 67.57%  |
| 2      | 14        | 18.92%  |
| 3      | 5         | 6.76%   |
| 4      | 4         | 5.41%   |
| 6      | 1         | 1.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 66.22%  |
| Yes       | 25        | 33.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 83.78%  |
| No        | 12        | 16.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 82.43%  |
| No        | 13        | 17.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 55.41%  |
| No        | 33        | 44.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 24.32%  |
| UK          | 9         | 12.16%  |
| Brazil      | 6         | 8.11%   |
| Russia      | 5         | 6.76%   |
| Canada      | 5         | 6.76%   |
| Spain       | 4         | 5.41%   |
| Germany     | 4         | 5.41%   |
| France      | 3         | 4.05%   |
| Romania     | 2         | 2.7%    |
| Mexico      | 2         | 2.7%    |
| Italy       | 2         | 2.7%    |
| Australia   | 2         | 2.7%    |
| Venezuela   | 1         | 1.35%   |
| Sweden      | 1         | 1.35%   |
| South Korea | 1         | 1.35%   |
| Poland      | 1         | 1.35%   |
| Peru        | 1         | 1.35%   |
| Malaysia    | 1         | 1.35%   |
| Lithuania   | 1         | 1.35%   |
| Latvia      | 1         | 1.35%   |
| Kenya       | 1         | 1.35%   |
| Ecuador     | 1         | 1.35%   |
| Belgium     | 1         | 1.35%   |
| Austria     | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Moscow                   | 3         | 4.05%   |
| Neasden                  | 2         | 2.7%    |
| Montreal                 | 2         | 2.7%    |
| Melbourne                | 2         | 2.7%    |
| Vincennes                | 1         | 1.35%   |
| Vilnius                  | 1         | 1.35%   |
| Vicente Guerrero         | 1         | 1.35%   |
| Veurne                   | 1         | 1.35%   |
| Vaslui                   | 1         | 1.35%   |
| Uiwang                   | 1         | 1.35%   |
| Trieste                  | 1         | 1.35%   |
| Toledo                   | 1         | 1.35%   |
| Tipton                   | 1         | 1.35%   |
| Stockbridge              | 1         | 1.35%   |
| Spruce Grove             | 1         | 1.35%   |
| Spearfish                | 1         | 1.35%   |
| Scarborough              | 1         | 1.35%   |
| Saratov                  | 1         | 1.35%   |
| Sant Feliu de Llobregat  | 1         | 1.35%   |
| San Antonio de Los Altos | 1         | 1.35%   |
| Rochester                | 1         | 1.35%   |
| Riga                     | 1         | 1.35%   |
| Recife                   | 1         | 1.35%   |
| Queens                   | 1         | 1.35%   |
| Porto Alegre             | 1         | 1.35%   |
| Peterborough             | 1         | 1.35%   |
| Petaling Jaya            | 1         | 1.35%   |
| Nottingham               | 1         | 1.35%   |
| National City            | 1         | 1.35%   |
| Nairobi                  | 1         | 1.35%   |
| Murphy                   | 1         | 1.35%   |
| Monaca                   | 1         | 1.35%   |
| Mieuxce                  | 1         | 1.35%   |
| Marrero                  | 1         | 1.35%   |
| Mannheim                 | 1         | 1.35%   |
| Mammoth Lakes            | 1         | 1.35%   |
| Madrid                   | 1         | 1.35%   |
| Londonderry              | 1         | 1.35%   |
| London                   | 1         | 1.35%   |
| Limoges                  | 1         | 1.35%   |
| Lima                     | 1         | 1.35%   |
| Lebanon                  | 1         | 1.35%   |
| Lawrenceville            | 1         | 1.35%   |
| Knurow                   | 1         | 1.35%   |
| Hollister                | 1         | 1.35%   |
| Hamburg                  | 1         | 1.35%   |
| Hallwang                 | 1         | 1.35%   |
| Glasgow                  | 1         | 1.35%   |
| Everett                  | 1         | 1.35%   |
| Detroit                  | 1         | 1.35%   |
| Darlington               | 1         | 1.35%   |
| Ciudad Juárez           | 1         | 1.35%   |
| Chicago                  | 1         | 1.35%   |
| Castejon                 | 1         | 1.35%   |
| Brescia                  | 1         | 1.35%   |
| Branesti                 | 1         | 1.35%   |
| Blairsville              | 1         | 1.35%   |
| Birmingham               | 1         | 1.35%   |
| Birigui                  | 1         | 1.35%   |
| Berlin                   | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 15        | 23     | 15%     |
| Seagate                        | 13        | 15     | 13%     |
| Samsung Electronics            | 13        | 15     | 13%     |
| Hitachi                        | 7         | 8      | 7%      |
| Toshiba                        | 6         | 6      | 6%      |
| Kingston                       | 6         | 6      | 6%      |
| SanDisk                        | 4         | 4      | 4%      |
| Intel                          | 4         | 4      | 4%      |
| Unknown                        | 3         | 3      | 3%      |
| Micron Technology              | 3         | 3      | 3%      |
| Crucial                        | 3         | 3      | 3%      |
| A-DATA Technology              | 3         | 3      | 3%      |
| SK Hynix                       | 2         | 2      | 2%      |
| Apple                          | 2         | 3      | 2%      |
| Transcend                      | 1         | 2      | 1%      |
| Solid State Storage Technology | 1         | 1      | 1%      |
| SABRENT                        | 1         | 1      | 1%      |
| PNY                            | 1         | 1      | 1%      |
| Phison                         | 1         | 1      | 1%      |
| Patriot                        | 1         | 1      | 1%      |
| Oyen                           | 1         | 1      | 1%      |
| OCZ-VERTEX                     | 1         | 1      | 1%      |
| Micron/Crucial Technology      | 1         | 2      | 1%      |
| LITEON                         | 1         | 1      | 1%      |
| KIOXIA                         | 1         | 2      | 1%      |
| KingSpec                       | 1         | 1      | 1%      |
| HGST                           | 1         | 1      | 1%      |
| China                          | 1         | 2      | 1%      |
| BHT                            | 1         | 1      | 1%      |
| Acer                           | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB          | 3         | 2.8%    |
| Micron NVMe SSD Drive 512GB              | 3         | 2.8%    |
| Kingston SA400S37240G 240GB SSD          | 3         | 2.8%    |
| WDC WD3200BPVT-22JJ5T0 320GB             | 2         | 1.87%   |
| Unknown SD/MMC/MS PRO 999GB              | 2         | 1.87%   |
| Seagate ST2000DM008-2FR102 2TB           | 2         | 1.87%   |
| Samsung SSD 970 EVO Plus 1TB             | 2         | 1.87%   |
| Samsung SSD 850 EVO 250GB                | 2         | 1.87%   |
| Crucial CT480BX500SSD1 480GB             | 2         | 1.87%   |
| A-DATA SU650 120GB SSD                   | 2         | 1.87%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 0.93%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 0.93%   |
| WDC WD60EZAZ-00ZGHB0 6TB                 | 1         | 0.93%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 0.93%   |
| WDC WD3200AAJS-22B4A0 320GB              | 1         | 0.93%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 0.93%   |
| WDC WD3003FZEX-00Z4SA0 3TB               | 1         | 0.93%   |
| WDC WD30 EFRX-68EUZN0 3TB                | 1         | 0.93%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1         | 0.93%   |
| WDC WD10EFRX-68JCSN0 1TB                 | 1         | 0.93%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1         | 0.93%   |
| WDC WD10EAVS-00D7B0 1TB                  | 1         | 0.93%   |
| WDC WD1003FZEX-00MK2A0 1TB               | 1         | 0.93%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB     | 1         | 0.93%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 0.93%   |
| Unknown Biwin  64GB                      | 1         | 0.93%   |
| Transcend TS480GSSD220S 480GB            | 1         | 0.93%   |
| Transcend TS240GSSD220S 240GB            | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 0.93%   |
| Toshiba MQ01ABF032 320GB                 | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 0.93%   |
| Toshiba MK3275GSX 320GB                  | 1         | 0.93%   |
| Toshiba MK3252GSX 320GB                  | 1         | 0.93%   |
| Toshiba DT01ACA050 500GB                 | 1         | 0.93%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 0.93%   |
| SK Hynix HFS256G32MND-3310A 256GB SSD    | 1         | 0.93%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 0.93%   |
| Seagate ST9160412ASG 160GB               | 1         | 0.93%   |
| Seagate ST3250318AS 250GB                | 1         | 0.93%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 0.93%   |
| Seagate ST3160812AS Q 160GB              | 1         | 0.93%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 0.93%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 0.93%   |
| SanDisk SSD PLUS 480GB                   | 1         | 0.93%   |
| SanDisk SDSSDA240G 240GB                 | 1         | 0.93%   |
| Sandisk NVMe SSD Drive 512GB             | 1         | 0.93%   |
| SanDisk DF4064  64GB                     | 1         | 0.93%   |
| Samsung SSD 980 PRO 1TB                  | 1         | 0.93%   |
| Samsung SSD 980 1TB                      | 1         | 0.93%   |
| Samsung SSD 860 EVO 1TB                  | 1         | 0.93%   |
| Samsung SSD 850 EVO 500GB                | 1         | 0.93%   |
| Samsung SSD 850 EVO 120GB                | 1         | 0.93%   |
| Samsung PM991a NVMe 512GB                | 1         | 0.93%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 0.93%   |
| Samsung NVMe SSD Drive 1TB               | 1         | 0.93%   |
| Samsung MZMTE128HMGR-000MV 128GB SSD     | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 15     | 30.95%  |
| WDC     | 12        | 20     | 28.57%  |
| Hitachi | 7         | 8      | 16.67%  |
| Toshiba | 6         | 6      | 14.29%  |
| Unknown | 2         | 2      | 4.76%   |
| SABRENT | 1         | 1      | 2.38%   |
| HGST    | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 18.18%  |
| Samsung Electronics | 5         | 6      | 15.15%  |
| Crucial             | 3         | 3      | 9.09%   |
| A-DATA Technology   | 3         | 3      | 9.09%   |
| SanDisk             | 2         | 2      | 6.06%   |
| Intel               | 2         | 2      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| Transcend           | 1         | 2      | 3.03%   |
| SK Hynix            | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| OCZ-VERTEX          | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| China               | 1         | 2      | 3.03%   |
| BHT                 | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| Acer                | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 53     | 40.66%  |
| SSD     | 30        | 36     | 32.97%  |
| NVMe    | 21        | 26     | 23.08%  |
| MMC     | 2         | 2      | 2.2%    |
| Unknown | 1         | 1      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 84     | 68.29%  |
| NVMe | 21        | 26     | 25.61%  |
| SAS  | 3         | 6      | 3.66%   |
| MMC  | 2         | 2      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 57     | 68.66%  |
| 0.51-1.0   | 13        | 20     | 19.4%   |
| 1.01-2.0   | 4         | 5      | 5.97%   |
| 2.01-3.0   | 3         | 6      | 4.48%   |
| 4.01-10.0  | 1         | 1      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 23        | 31.08%  |
| 101-250        | 14        | 18.92%  |
| 51-100         | 10        | 13.51%  |
| 501-1000       | 8         | 10.81%  |
| 1-20           | 7         | 9.46%   |
| 1001-2000      | 5         | 6.76%   |
| More than 3000 | 3         | 4.05%   |
| 21-50          | 3         | 4.05%   |
| 2001-3000      | 1         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 41        | 53.25%  |
| 21-50     | 17        | 22.08%  |
| 101-250   | 6         | 7.79%   |
| 501-1000  | 4         | 5.19%   |
| 51-100    | 4         | 5.19%   |
| 251-500   | 3         | 3.9%    |
| 2001-3000 | 1         | 1.3%    |
| 1001-2000 | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 20%     |
| Seagate ST3250318AS 250GB       | 1         | 1      | 20%     |
| Phison ES 512GB                 | 1         | 1      | 20%     |
| Intel SSDSCKKF256G8 SATA 256GB  | 1         | 1      | 20%     |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Phison  | 1         | 1      | 20%     |
| Intel   | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 48        | 74     | 60.76%  |
| Works    | 26        | 39     | 32.91%  |
| Malfunc  | 5         | 5      | 6.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 55        | 59.14%  |
| AMD                            | 14        | 15.05%  |
| Samsung Electronics            | 9         | 9.68%   |
| Sandisk                        | 3         | 3.23%   |
| Micron Technology              | 3         | 3.23%   |
| Toshiba America Info Systems   | 1         | 1.08%   |
| Solid State Storage Technology | 1         | 1.08%   |
| SK Hynix                       | 1         | 1.08%   |
| Phison Electronics             | 1         | 1.08%   |
| Micron/Crucial Technology      | 1         | 1.08%   |
| JMicron Technology             | 1         | 1.08%   |
| Broadcom / LSI                 | 1         | 1.08%   |
| ASMedia Technology             | 1         | 1.08%   |
| Apple                          | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 9.17%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 5.5%    |
| Samsung NVMe SSD Controller 980                                                         | 4         | 3.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 3.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 3.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.75%   |
| Micron Non-Volatile memory controller                                                   | 3         | 2.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 2.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 2.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 2.75%   |
| Sandisk Non-Volatile memory controller                                                  | 2         | 1.83%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 1.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.92%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 0.92%   |
| SK Hynix BC511                                                                          | 1         | 0.92%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.92%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.92%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.92%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.92%   |
| Intel SSD 660P Series                                                                   | 1         | 0.92%   |
| Intel SSD 600P Series                                                                   | 1         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 0.92%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.92%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 0.92%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 0.92%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 0.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 0.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.92%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.92%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 0.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.92%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 0.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.92%   |
| Apple S3X NVMe Controller                                                               | 1         | 0.92%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 1         | 0.92%   |
| AMD IXP SB4x0 IDE Controller                                                            | 1         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 52        | 53.06%  |
| NVMe | 21        | 21.43%  |
| IDE  | 13        | 13.27%  |
| RAID | 11        | 11.22%  |
| SAS  | 1         | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 81.08%  |
| AMD    | 14        | 18.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                | 3         | 4.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 4.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 4.05%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 2.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 2.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 2.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 2.7%    |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 1.35%   |
| Intel Xeon CPU X5570 @ 2.93GHz                | 1         | 1.35%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz           | 1         | 1.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.35%   |
| Intel Pentium M processor 1.73GHz             | 1         | 1.35%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 1         | 1.35%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 1.35%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 1.35%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.35%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.35%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 1.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 1.35%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.35%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 1.35%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 1.35%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.35%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 1.35%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.35%   |
| Intel Core i5-3470S CPU @ 2.90GHz             | 1         | 1.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.35%   |
| Intel Core i5-2557M CPU @ 1.70GHz             | 1         | 1.35%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.35%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.35%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.35%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.35%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.35%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1.35%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 1.35%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 1.35%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.35%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz          | 1         | 1.35%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 1.35%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 1         | 1.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.35%   |
| Intel Celeron M CPU 520 @ 1.60GHz             | 1         | 1.35%   |
| Intel Celeron M CPU 440 @ 1.86GHz             | 1         | 1.35%   |
| Intel Celeron CPU N2815 @ 1.86GHz             | 1         | 1.35%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.35%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 1.35%   |
| Intel 12th Gen Core i3-12100F                 | 1         | 1.35%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 1.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 1.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.35%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 1         | 1.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.35%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 1.35%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.35%   |
| AMD FX-4300 Quad-Core Processor               | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 12        | 16.22%  |
| Other                   | 10        | 13.51%  |
| Intel Core i7           | 9         | 12.16%  |
| Intel Core i3           | 5         | 6.76%   |
| Intel Core 2 Duo        | 5         | 6.76%   |
| Intel Atom              | 4         | 5.41%   |
| AMD Ryzen 7             | 4         | 5.41%   |
| AMD Ryzen 5             | 4         | 5.41%   |
| Intel Xeon              | 3         | 4.05%   |
| Intel Celeron           | 3         | 4.05%   |
| Intel Pentium Dual-Core | 2         | 2.7%    |
| Intel Pentium           | 2         | 2.7%    |
| Intel Celeron M         | 2         | 2.7%    |
| Intel Pentium Silver    | 1         | 1.35%   |
| Intel Pentium M         | 1         | 1.35%   |
| Intel Core 2            | 1         | 1.35%   |
| AMD Ryzen 3             | 1         | 1.35%   |
| AMD FX                  | 1         | 1.35%   |
| AMD E2                  | 1         | 1.35%   |
| AMD C-50                | 1         | 1.35%   |
| AMD Athlon              | 1         | 1.35%   |
| AMD A10                 | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 48.65%  |
| 4      | 21        | 28.38%  |
| 8      | 7         | 9.46%   |
| 6      | 5         | 6.76%   |
| 1      | 4         | 5.41%   |
| 16     | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 97.3%   |
| 2      | 2         | 2.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 50        | 67.57%  |
| 1      | 24        | 32.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 70        | 94.59%  |
| 32-bit         | 4         | 5.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 8         | 10.81%  |
| 0x306a9    | 4         | 5.41%   |
| 0x1067a    | 4         | 5.41%   |
| 0x506e3    | 3         | 4.05%   |
| 0x406e3    | 3         | 4.05%   |
| 0x30661    | 3         | 4.05%   |
| 0x206a7    | 3         | 4.05%   |
| 0x08608103 | 3         | 4.05%   |
| 0x806e9    | 2         | 2.7%    |
| 0x6fd      | 2         | 2.7%    |
| 0x6f6      | 2         | 2.7%    |
| 0x40651    | 2         | 2.7%    |
| 0x20652    | 2         | 2.7%    |
| 0x08108109 | 2         | 2.7%    |
| Unknown    | 2         | 2.7%    |
| 0xa0653    | 1         | 1.35%   |
| 0xa0652    | 1         | 1.35%   |
| 0x906ed    | 1         | 1.35%   |
| 0x906ea    | 1         | 1.35%   |
| 0x90675    | 1         | 1.35%   |
| 0x806ec    | 1         | 1.35%   |
| 0x806d1    | 1         | 1.35%   |
| 0x706e5    | 1         | 1.35%   |
| 0x706a8    | 1         | 1.35%   |
| 0x706a1    | 1         | 1.35%   |
| 0x6ec      | 1         | 1.35%   |
| 0x6d8      | 1         | 1.35%   |
| 0x306d4    | 1         | 1.35%   |
| 0x306c3    | 1         | 1.35%   |
| 0x30673    | 1         | 1.35%   |
| 0x206d7    | 1         | 1.35%   |
| 0x206c2    | 1         | 1.35%   |
| 0x106e5    | 1         | 1.35%   |
| 0x106c2    | 1         | 1.35%   |
| 0x106a5    | 1         | 1.35%   |
| 0x10676    | 1         | 1.35%   |
| 0x08600103 | 1         | 1.35%   |
| 0x08108102 | 1         | 1.35%   |
| 0x0810100b | 1         | 1.35%   |
| 0x08001137 | 1         | 1.35%   |
| 0x07030106 | 1         | 1.35%   |
| 0x0600611a | 1         | 1.35%   |
| 0x06000852 | 1         | 1.35%   |
| 0x05000029 | 1         | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| TigerLake     | 8         | 10.81%  |
| Skylake       | 6         | 8.11%   |
| Penryn        | 5         | 6.76%   |
| KabyLake      | 5         | 6.76%   |
| IvyBridge     | 5         | 6.76%   |
| SandyBridge   | 4         | 5.41%   |
| Core          | 4         | 5.41%   |
| Bonnell       | 4         | 5.41%   |
| Unknown       | 4         | 5.41%   |
| Zen+          | 3         | 4.05%   |
| Westmere      | 3         | 4.05%   |
| Haswell       | 3         | 4.05%   |
| Zen           | 2         | 2.7%    |
| P6            | 2         | 2.7%    |
| Nehalem       | 2         | 2.7%    |
| IceLake       | 2         | 2.7%    |
| Goldmont plus | 2         | 2.7%    |
| CometLake     | 2         | 2.7%    |
| Zen 3         | 1         | 1.35%   |
| Zen 2         | 1         | 1.35%   |
| Silvermont    | 1         | 1.35%   |
| Puma          | 1         | 1.35%   |
| Piledriver    | 1         | 1.35%   |
| Excavator     | 1         | 1.35%   |
| Broadwell     | 1         | 1.35%   |
| Bobcat        | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 50.62%  |
| Nvidia | 23        | 28.4%   |
| AMD    | 17        | 20.99%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 7.06%   |
| Nvidia GT218 [GeForce 210]                                                            | 3         | 3.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 3.53%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                       | 3         | 3.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 3.53%   |
| AMD Lucienne                                                                          | 3         | 3.53%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 2         | 2.35%   |
| Nvidia G98M [Quadro NVS 160M]                                                         | 2         | 2.35%   |
| Intel Tiger Lake UHD Graphics                                                         | 2         | 2.35%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.35%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 2.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 2.35%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 1.18%   |
| Nvidia GT216M [GeForce GT 325M]                                                       | 1         | 1.18%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 1         | 1.18%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 1.18%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 1.18%   |
| Nvidia GM107GL [Quadro K620]                                                          | 1         | 1.18%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 1         | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.18%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                     | 1         | 1.18%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                     | 1         | 1.18%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                     | 1         | 1.18%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                     | 1         | 1.18%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 1.18%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 1.18%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                       | 1         | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 1         | 1.18%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.18%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                             | 1         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.18%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.18%   |
| Intel Iris Plus Graphics 640                                                          | 1         | 1.18%   |
| Intel HD Graphics 620                                                                 | 1         | 1.18%   |
| Intel HD Graphics 6000                                                                | 1         | 1.18%   |
| Intel HD Graphics 530                                                                 | 1         | 1.18%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.18%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.18%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 1         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.18%   |
| AMD Wrestler [Radeon HD 6250]                                                         | 1         | 1.18%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.18%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.18%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.18%   |
| AMD RV530/M56-P [Mobility Radeon X1600]                                               | 1         | 1.18%   |
| AMD Renoir                                                                            | 1         | 1.18%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                              | 1         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 1.18%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                 | 1         | 1.18%   |
| AMD Mullins [Radeon R2 Graphics]                                                      | 1         | 1.18%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 46.67%  |
| 1 x Nvidia     | 19        | 25.33%  |
| 1 x AMD        | 13        | 17.33%  |
| Intel + Nvidia | 4         | 5.33%   |
| 2 x AMD        | 2         | 2.67%   |
| Intel + AMD    | 1         | 1.33%   |
| AMD + Nvidia   | 1         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 67        | 90.54%  |
| Proprietary | 4         | 5.41%   |
| Unknown     | 3         | 4.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 51.35%  |
| 1.01-2.0   | 12        | 16.22%  |
| 0.01-0.5   | 11        | 14.86%  |
| 3.01-4.0   | 6         | 8.11%   |
| 0.51-1.0   | 6         | 8.11%   |
| 5.01-6.0   | 1         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 17.72%  |
| BOE                     | 10        | 12.66%  |
| Samsung Electronics     | 7         | 8.86%   |
| Chimei Innolux          | 7         | 8.86%   |
| LG Display              | 5         | 6.33%   |
| Philips                 | 3         | 3.8%    |
| LG Philips              | 3         | 3.8%    |
| Dell                    | 3         | 3.8%    |
| Apple                   | 3         | 3.8%    |
| Ancor Communications    | 3         | 3.8%    |
| Acer                    | 3         | 3.8%    |
| PANDA                   | 2         | 2.53%   |
| Hewlett-Packard         | 2         | 2.53%   |
| ___                     | 1         | 1.27%   |
| Unknown                 | 1         | 1.27%   |
| Sharp                   | 1         | 1.27%   |
| Quanta Display          | 1         | 1.27%   |
| Planar                  | 1         | 1.27%   |
| Medion                  | 1         | 1.27%   |
| Insignia                | 1         | 1.27%   |
| InfoVision              | 1         | 1.27%   |
| HannStar                | 1         | 1.27%   |
| Goldstar                | 1         | 1.27%   |
| DENON                   | 1         | 1.27%   |
| Chi Mei Optoelectronics | 1         | 1.27%   |
| BenQ                    | 1         | 1.27%   |
| ASUSTek Computer        | 1         | 1.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 2.44%   |
| ___ LCDTV14 ___0101 1920x1080                                            | 1         | 1.22%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                       | 1         | 1.22%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 1.22%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch     | 1         | 1.22%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 1.22%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.22%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch       | 1         | 1.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.22%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 1.22%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 1.22%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch                | 1         | 1.22%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 1         | 1.22%   |
| Philips LCD Monitor PHL 242V8 1920x1080                                  | 1         | 1.22%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 1.22%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 1.22%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                      | 1         | 1.22%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 1.22%   |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch             | 1         | 1.22%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 1         | 1.22%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch              | 1         | 1.22%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch               | 1         | 1.22%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch               | 1         | 1.22%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch               | 1         | 1.22%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 1.22%   |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                    | 1         | 1.22%   |
| DENON AVR DON005F 1920x1080                                              | 1         | 1.22%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1         | 1.22%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 1.22%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 1.22%   |
| Dell 2007WFP DELA019 1680x1050 434x270mm 20.1-inch                       | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch         | 1         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 1.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 1         | 1.22%   |
| BOE LCD Monitor BOE099E 1920x1080 344x194mm 15.5-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE08FA 1920x1080 294x165mm 13.3-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE08E8 1920x1080 340x190mm 15.3-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                     | 1         | 1.22%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                     | 1         | 1.22%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 1.22%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 1.22%   |
| BenQ GL2750H BNQ78AD 1920x1080 598x336mm 27.0-inch                       | 1         | 1.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 1.22%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 47.3%   |
| 1366x768 (WXGA)    | 13        | 17.57%  |
| 1600x900 (HD+)     | 4         | 5.41%   |
| 1440x900 (WXGA+)   | 4         | 5.41%   |
| 1920x1200 (WUXGA)  | 3         | 4.05%   |
| 1024x600           | 3         | 4.05%   |
| 2560x1440 (QHD)    | 2         | 2.7%    |
| 1680x1050 (WSXGA+) | 2         | 2.7%    |
| 1280x800 (WXGA)    | 2         | 2.7%    |
| 3840x2160 (4K)     | 1         | 1.35%   |
| 2880x1800          | 1         | 1.35%   |
| 2560x1080          | 1         | 1.35%   |
| 1280x768           | 1         | 1.35%   |
| 1280x720 (HD)      | 1         | 1.35%   |
| 1280x1024 (SXGA)   | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 28.75%  |
| 13      | 11        | 13.75%  |
| 14      | 8         | 10%     |
| 24      | 6         | 7.5%    |
| 21      | 5         | 6.25%   |
| 27      | 4         | 5%      |
| 17      | 4         | 5%      |
| 20      | 3         | 3.75%   |
| 10      | 3         | 3.75%   |
| 72      | 2         | 2.5%    |
| 23      | 2         | 2.5%    |
| Unknown | 2         | 2.5%    |
| 32      | 1         | 1.25%   |
| 31      | 1         | 1.25%   |
| 28      | 1         | 1.25%   |
| 22      | 1         | 1.25%   |
| 19      | 1         | 1.25%   |
| 16      | 1         | 1.25%   |
| 8       | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 47.44%  |
| 501-600     | 11        | 14.1%   |
| 401-500     | 8         | 10.26%  |
| 201-300     | 8         | 10.26%  |
| 351-400     | 6         | 7.69%   |
| 601-700     | 2         | 2.56%   |
| 1501-2000   | 2         | 2.56%   |
| Unknown     | 2         | 2.56%   |
| 701-800     | 1         | 1.28%   |
| 101-200     | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 56        | 78.87%  |
| 16/10   | 11        | 15.49%  |
| Unknown | 2         | 2.82%   |
| 5/4     | 1         | 1.41%   |
| 21/9    | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 29.11%  |
| 81-90          | 14        | 17.72%  |
| 201-250        | 11        | 13.92%  |
| 71-80          | 5         | 6.33%   |
| 301-350        | 4         | 5.06%   |
| 151-200        | 4         | 5.06%   |
| 41-50          | 3         | 3.8%    |
| 251-300        | 3         | 3.8%    |
| 121-130        | 3         | 3.8%    |
| More than 1000 | 2         | 2.53%   |
| 351-500        | 2         | 2.53%   |
| Unknown        | 2         | 2.53%   |
| 1-40           | 1         | 1.27%   |
| 131-140        | 1         | 1.27%   |
| 91-100         | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 32.91%  |
| 51-100        | 23        | 29.11%  |
| 101-120       | 22        | 27.85%  |
| 161-240       | 3         | 3.8%    |
| 1-50          | 2         | 2.53%   |
| Unknown       | 2         | 2.53%   |
| More than 240 | 1         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 62        | 83.78%  |
| 2     | 7         | 9.46%   |
| 3     | 3         | 4.05%   |
| 0     | 2         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 38        | 34.86%  |
| Intel                         | 35        | 32.11%  |
| Qualcomm Atheros              | 13        | 11.93%  |
| Broadcom                      | 10        | 9.17%   |
| Ralink Technology             | 3         | 2.75%   |
| Marvell Technology Group      | 2         | 1.83%   |
| Broadcom Limited              | 2         | 1.83%   |
| Samsung Electronics           | 1         | 0.92%   |
| Ralink                        | 1         | 0.92%   |
| OnePlus Technology (Shenzhen) | 1         | 0.92%   |
| Microchip Technology          | 1         | 0.92%   |
| Mercucys                      | 1         | 0.92%   |
| JMicron Technology            | 1         | 0.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 18        | 12.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 7         | 5.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6         | 4.32%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 2.16%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 2.16%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 2.16%   |
| Intel 82567LM Gigabit Network Connection                                                      | 3         | 2.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 1.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 2         | 1.44%   |
| Realtek 802.11ac NIC                                                                          | 2         | 1.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 2         | 1.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 1.44%   |
| Intel Wireless 7260                                                                           | 2         | 1.44%   |
| Intel Ultimate N WiFi Link 5300                                                               | 2         | 1.44%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2         | 1.44%   |
| Intel 82574L Gigabit Network Connection                                                       | 2         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.72%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.72%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.72%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.72%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.72%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.72%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 1         | 0.72%   |
| OnePlus (Shenzhen) OnePlus                                                                    | 1         | 0.72%   |
| Microchip LAN9500/LAN9500i                                                                    | 1         | 0.72%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 0.72%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.72%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                                          | 1         | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                        | 1         | 0.72%   |
| Intel Wireless 3165                                                                           | 1         | 0.72%   |
| Intel Wireless 3160                                                                           | 1         | 0.72%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 0.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 0.72%   |
| Intel I210 Gigabit Fiber Network Connection                                                   | 1         | 0.72%   |
| Intel Ethernet Connection I218-LM                                                             | 1         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                                         | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 35.38%  |
| Realtek Semiconductor | 19        | 29.23%  |
| Qualcomm Atheros      | 9         | 13.85%  |
| Broadcom              | 7         | 10.77%  |
| Ralink Technology     | 3         | 4.62%   |
| Broadcom Limited      | 2         | 3.08%   |
| Ralink                | 1         | 1.54%   |
| Mercucys              | 1         | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                                           | 5         | 7.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 5.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 4.35%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 2.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 2.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 2.9%    |
| Realtek 802.11ac NIC                                                                          | 2         | 2.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 2.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 2         | 2.9%    |
| Intel Wireless 7260                                                                           | 2         | 2.9%    |
| Intel Ultimate N WiFi Link 5300                                                               | 2         | 2.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 1.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.45%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 1.45%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 1.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.45%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 1.45%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.45%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 1.45%   |
| Intel Wireless 3165                                                                           | 1         | 1.45%   |
| Intel Wireless 3160                                                                           | 1         | 1.45%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 1.45%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.45%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1         | 1.45%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1         | 1.45%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.45%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 1.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 30        | 45.45%  |
| Intel                         | 21        | 31.82%  |
| Qualcomm Atheros              | 6         | 9.09%   |
| Broadcom                      | 3         | 4.55%   |
| Marvell Technology Group      | 2         | 3.03%   |
| Samsung Electronics           | 1         | 1.52%   |
| OnePlus Technology (Shenzhen) | 1         | 1.52%   |
| Microchip Technology          | 1         | 1.52%   |
| JMicron Technology            | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 26.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 10.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.7%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.9%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.9%    |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.45%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.45%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 1.45%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 1.45%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.45%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.45%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 1.45%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.45%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.45%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.45%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.45%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.45%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 1.45%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 1.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 50%     |
| WiFi     | 61        | 49.19%  |
| Modem    | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 62.34%  |
| Ethernet | 29        | 37.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 43        | 58.11%  |
| 1     | 30        | 40.54%  |
| 0     | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 73.33%  |
| Yes  | 20        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 45.24%  |
| Realtek Semiconductor           | 9         | 21.43%  |
| Dell                            | 3         | 7.14%   |
| Qualcomm Atheros Communications | 2         | 4.76%   |
| Foxconn / Hon Hai               | 2         | 4.76%   |
| Cambridge Silicon Radio         | 2         | 4.76%   |
| Apple                           | 2         | 4.76%   |
| Lite-On Technology              | 1         | 2.38%   |
| IMC Networks                    | 1         | 2.38%   |
| Broadcom                        | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 16.67%  |
| Realtek Bluetooth Radio                             | 6         | 14.29%  |
| Intel AX201 Bluetooth                               | 6         | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 7.14%   |
| Intel AX200 Bluetooth                               | 3         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.76%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.38%   |
| IMC Networks Bluetooth Device                       | 1         | 2.38%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.38%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.38%   |
| Dell BT Mini-Receiver                               | 1         | 2.38%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.38%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.38%   |
| Apple Bluetooth HCI                                 | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 57.43%  |
| Nvidia                | 19        | 18.81%  |
| AMD                   | 17        | 16.83%  |
| Texas Instruments     | 2         | 1.98%   |
| C-Media Electronics   | 2         | 1.98%   |
| Realtek Semiconductor | 1         | 0.99%   |
| GN Netcom             | 1         | 0.99%   |
| Audioengine           | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 7.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 6.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 5.93%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 4.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.39%   |
| Nvidia High Definition Audio Controller                                    | 3         | 2.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 2.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 2.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.54%   |
| Nvidia Audio device                                                        | 2         | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.69%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.85%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 0.85%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.85%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.85%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 0.85%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.85%   |
| Intel Audio device                                                         | 1         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.85%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 0.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.85%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                            | 1         | 0.85%   |
| C-Media Electronics REIYIN Audio DA-02                                     | 1         | 0.85%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 0.85%   |
| Audioengine D1 24-bit DAC                                                  | 1         | 0.85%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.85%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.85%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 0.85%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 26.67%  |
| Unknown             | 4         | 13.33%  |
| SK Hynix            | 4         | 13.33%  |
| Micron Technology   | 3         | 10%     |
| A-DATA Technology   | 3         | 10%     |
| Nanya Technology    | 2         | 6.67%   |
| Corsair             | 2         | 6.67%   |
| Unknown (ABCD)      | 1         | 3.33%   |
| Kingston            | 1         | 3.33%   |
| G.Skill             | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 2         | 6.06%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1         | 3.03%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 3.03%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 1         | 3.03%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 3.03%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 1         | 3.03%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s                  | 1         | 3.03%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 3.03%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s          | 1         | 3.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 3.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 3.03%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s           | 1         | 3.03%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR 2048MT/s            | 1         | 3.03%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s              | 1         | 3.03%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s            | 1         | 3.03%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1         | 3.03%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s            | 1         | 3.03%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s          | 1         | 3.03%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s          | 1         | 3.03%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 1         | 3.03%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s      | 1         | 3.03%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                     | 1         | 3.03%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                    | 1         | 3.03%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s        | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 51.72%  |
| DDR3    | 7         | 24.14%  |
| SDRAM   | 3         | 10.34%  |
| LPDDR4  | 2         | 6.9%    |
| DDR     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 63.33%  |
| DIMM         | 8         | 26.67%  |
| Row Of Chips | 3         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 37.5%   |
| 4096  | 7         | 21.88%  |
| 2048  | 5         | 15.63%  |
| 16384 | 3         | 9.38%   |
| 32768 | 2         | 6.25%   |
| 1024  | 2         | 6.25%   |
| 512   | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 10        | 34.48%  |
| 1600    | 6         | 20.69%  |
| 2400    | 3         | 10.34%  |
| 2667    | 2         | 6.9%    |
| 4267    | 1         | 3.45%   |
| 4199    | 1         | 3.45%   |
| 2048    | 1         | 3.45%   |
| 1866    | 1         | 3.45%   |
| 1333    | 1         | 3.45%   |
| 1200    | 1         | 3.45%   |
| 667     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Konica Minolta     | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Konica Minolta 185    | 1         | 33.33%  |
| HP OfficeJet Pro 8730 | 1         | 33.33%  |
| Brother MFC-L2685DW   | 1         | 33.33%  |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 17.39%  |
| Microdia                               | 7         | 15.22%  |
| IMC Networks                           | 5         | 10.87%  |
| Suyin                                  | 4         | 8.7%    |
| Sunplus Innovation Technology          | 3         | 6.52%   |
| Realtek Semiconductor                  | 2         | 4.35%   |
| Quanta                                 | 2         | 4.35%   |
| Luxvisions Innotech Limited            | 2         | 4.35%   |
| Logitech                               | 2         | 4.35%   |
| Acer                                   | 2         | 4.35%   |
| Unknown                                | 1         | 2.17%   |
| Syntek                                 | 1         | 2.17%   |
| OmniVision Technologies                | 1         | 2.17%   |
| Lite-On Technology                     | 1         | 2.17%   |
| Intel                                  | 1         | 2.17%   |
| Creative Technology                    | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.17%   |
| ARC International                      | 1         | 2.17%   |
| ALi                                    | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 6         | 13.04%  |
| IMC Networks Integrated Camera                       | 2         | 4.35%   |
| Chicony HP Truevision HD camera                      | 2         | 4.35%   |
| Chicony HD Webcam                                    | 2         | 4.35%   |
| Acer Integrated Camera                               | 2         | 4.35%   |
| Unknown 720p HD Camera                               | 1         | 2.17%   |
| Syntek Integrated Camera                             | 1         | 2.17%   |
| Suyin HP TrueVision HD                               | 1         | 2.17%   |
| Suyin HD WebCam                                      | 1         | 2.17%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 2.17%   |
| Suyin 1.3M HD WebCam                                 | 1         | 2.17%   |
| Sunplus HD WebCam                                    | 1         | 2.17%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 2.17%   |
| Sunplus 1.3M HD WebCam                               | 1         | 2.17%   |
| Realtek MTD camera                                   | 1         | 2.17%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 2.17%   |
| Quanta HP Webcam                                     | 1         | 2.17%   |
| Quanta HP HD Camera                                  | 1         | 2.17%   |
| OmniVision Integrated Webcam for Dell XPS 2010       | 1         | 2.17%   |
| Microdia Integrated Webcam HD                        | 1         | 2.17%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 2.17%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 2.17%   |
| Logitech Webcam C925e                                | 1         | 2.17%   |
| Logitech Webcam C210                                 | 1         | 2.17%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 2.17%   |
| Intel RealSense 3D Camera (Front F200)               | 1         | 2.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 1         | 2.17%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 2.17%   |
| Creative Live! Cam Sync HD [VF0770]                  | 1         | 2.17%   |
| Chicony Integrated HP HD Webcam                      | 1         | 2.17%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 2.17%   |
| Chicony Integrated Camera                            | 1         | 2.17%   |
| Chicony 1.3M Webcam                                  | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 2.17%   |
| ARC International Camera                             | 1         | 2.17%   |
| ALi Gateway Webcam                                   | 1         | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| Synaptics                  | 2         | 25%     |
| Shenzhen Goodix Technology | 1         | 12.5%   |
| Samsung Electronics        | 1         | 12.5%   |
| Elan Microelectronics      | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 12.5%   |
| Validity Sensors VFS491                    | 1         | 12.5%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 12.5%   |
| Samsung Fingerprint Sensor Device - 730B   | 1         | 12.5%   |
| Elan ELAN:Fingerprint                      | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 60%     |
| Broadcom 5880                                  | 1         | 20%     |
| Broadcom 58200                                 | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 67.11%  |
| 1     | 23        | 30.26%  |
| 2     | 2         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 7         | 25%     |
| Fingerprint reader    | 7         | 25%     |
| Multimedia controller | 5         | 17.86%  |
| Chipcard              | 5         | 17.86%  |
| Graphics card         | 3         | 10.71%  |
| Camera                | 1         | 3.57%   |

