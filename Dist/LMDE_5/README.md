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

Total: 129

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [8a44001ebb](https://linux-hardware.org/?probe=8a44001ebb) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-14-amd64      | 29        | 29.29%  |
| 5.10.0-13-amd64      | 27        | 27.27%  |
| 5.10.0-12-amd64      | 19        | 19.19%  |
| 5.10.0-15-amd64      | 10        | 10.1%   |
| 5.10.0-13-686        | 6         | 6.06%   |
| 5.18.0-0.bpo.1-amd64 | 2         | 2.02%   |
| 5.16.0-0.bpo.4-amd64 | 2         | 2.02%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 1.01%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 1.01%   |
| 5.10.0-14-686        | 1         | 1.01%   |
| 5.10.0-11-686        | 1         | 1.01%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 90        | 93.75%  |
| 5.16.0  | 3         | 3.13%   |
| 5.18.0  | 2         | 2.08%   |
| 5.15.0  | 1         | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 90        | 93.75%  |
| 5.16    | 3         | 3.13%   |
| 5.18    | 2         | 2.08%   |
| 5.15    | 1         | 1.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 88        | 91.67%  |
| i686   | 8         | 8.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 86        | 89.58%  |
| Cinnamon   | 7         | 7.29%   |
| XFCE       | 1         | 1.04%   |
| MATE       | 1         | 1.04%   |
| Unknown    | 1         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 96        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 63.54%  |
| LightDM | 35        | 36.46%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 40        | 41.67%  |
| ru_RU | 7         | 7.29%   |
| pt_BR | 7         | 7.29%   |
| en_GB | 7         | 7.29%   |
| de_DE | 7         | 7.29%   |
| es_ES | 4         | 4.17%   |
| fr_FR | 3         | 3.13%   |
| pl_PL | 2         | 2.08%   |
| it_IT | 2         | 2.08%   |
| fr_CA | 2         | 2.08%   |
| es_MX | 2         | 2.08%   |
| es_BO | 2         | 2.08%   |
| en_CA | 2         | 2.08%   |
| pt_PT | 1         | 1.04%   |
| nl_AW | 1         | 1.04%   |
| ko_KR | 1         | 1.04%   |
| hu_HU | 1         | 1.04%   |
| es_PE | 1         | 1.04%   |
| es_EC | 1         | 1.04%   |
| en_IE | 1         | 1.04%   |
| en_AU | 1         | 1.04%   |
| ar_EG | 1         | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 57        | 59.38%  |
| BIOS | 39        | 40.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 89        | 92.71%  |
| Overlay | 4         | 4.17%   |
| Tmpfs   | 2         | 2.08%   |
| Xfs     | 1         | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 60        | 62.5%   |
| GPT     | 27        | 28.13%  |
| MBR     | 9         | 9.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 92.71%  |
| Yes       | 7         | 7.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 87.5%   |
| Yes       | 12        | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 22.92%  |
| Dell                | 15        | 15.63%  |
| Lenovo              | 12        | 12.5%   |
| Acer                | 10        | 10.42%  |
| ASUSTek Computer    | 9         | 9.38%   |
| MSI                 | 5         | 5.21%   |
| Apple               | 4         | 4.17%   |
| Toshiba             | 2         | 2.08%   |
| Gigabyte Technology | 2         | 2.08%   |
| Sony                | 1         | 1.04%   |
| Samsung Electronics | 1         | 1.04%   |
| Philco              | 1         | 1.04%   |
| Panasonic           | 1         | 1.04%   |
| Packard Bell        | 1         | 1.04%   |
| Multilaser          | 1         | 1.04%   |
| Medion              | 1         | 1.04%   |
| LincPlus            | 1         | 1.04%   |
| Intel               | 1         | 1.04%   |
| Howard Computers    | 1         | 1.04%   |
| Framework           | 1         | 1.04%   |
| Dixonsxp            | 1         | 1.04%   |
| ASRock              | 1         | 1.04%   |
| Alienware           | 1         | 1.04%   |
| Unknown             | 1         | 1.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| HP Laptop 15z-ef2xxx                             | 2         | 2.08%   |
| Dell Latitude E6400                              | 2         | 2.08%   |
| Unknown                                          | 2         | 2.08%   |
| Toshiba Satellite M55                            | 1         | 1.04%   |
| Toshiba Satellite L455                           | 1         | 1.04%   |
| Sony SVE1713Y1RB                                 | 1         | 1.04%   |
| Samsung 730QDA                                   | 1         | 1.04%   |
| Philco 10D                                       | 1         | 1.04%   |
| Panasonic CF-H2BJJHZDE                           | 1         | 1.04%   |
| Packard Bell DOT S                               | 1         | 1.04%   |
| Multilaser PC150                                 | 1         | 1.04%   |
| MSI U180                                         | 1         | 1.04%   |
| MSI MS-7B79                                      | 1         | 1.04%   |
| MSI MS-7B17                                      | 1         | 1.04%   |
| MSI MS-7977                                      | 1         | 1.04%   |
| MSI MS-7974                                      | 1         | 1.04%   |
| Medion E6220                                     | 1         | 1.04%   |
| LincPlus LINNCPLUS P1                            | 1         | 1.04%   |
| Lenovo Z50-70 20354                              | 1         | 1.04%   |
| Lenovo Yoga 7 15ITL5 82BJ                        | 1         | 1.04%   |
| Lenovo V55t-15ARE 11KJ0036TX                     | 1         | 1.04%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 1.04%   |
| Lenovo ThinkPad T450 20BUS0QT04                  | 1         | 1.04%   |
| Lenovo ThinkCentre M92p 3238E9U                  | 1         | 1.04%   |
| Lenovo ThinkCentre M720s 10SUS9KW00              | 1         | 1.04%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 1.04%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS                | 1         | 1.04%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 1.04%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 1.04%   |
| Lenovo IdeaPad 3 14ALC6 82KT                     | 1         | 1.04%   |
| Intel DQ77MK AAG39642-400                        | 1         | 1.04%   |
| Howard Computers R7X                             | 1         | 1.04%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 1.04%   |
| HP Z820 Workstation                              | 1         | 1.04%   |
| HP Z600 Workstation                              | 1         | 1.04%   |
| HP ProBook 6570b                                 | 1         | 1.04%   |
| HP ProBook 450 G8 Notebook PC                    | 1         | 1.04%   |
| HP Presario C500 (GF581UA#ABA)                   | 1         | 1.04%   |
| HP Pavilion Laptop 15-eh1xxx                     | 1         | 1.04%   |
| HP Pavilion 17                                   | 1         | 1.04%   |
| HP Notebook                                      | 1         | 1.04%   |
| HP Laptop 15-bw0xx                               | 1         | 1.04%   |
| HP Laptop 14-df0xxx                              | 1         | 1.04%   |
| HP Laptop 14-cf3xxx                              | 1         | 1.04%   |
| HP ENVY 17                                       | 1         | 1.04%   |
| HP EliteBook 8730w                               | 1         | 1.04%   |
| HP EliteBook 840 G1                              | 1         | 1.04%   |
| HP Compaq Pro 6300 SFF                           | 1         | 1.04%   |
| HP Compaq 15                                     | 1         | 1.04%   |
| HP 255 G7 Notebook PC                            | 1         | 1.04%   |
| HP 255 G5 Notebook PC                            | 1         | 1.04%   |
| HP 14                                            | 1         | 1.04%   |
| Gigabyte Z68A-D3H-B3                             | 1         | 1.04%   |
| Gigabyte H110M-S2H                               | 1         | 1.04%   |
| Framework Laptop                                 | 1         | 1.04%   |
| Dell XPS A2010                                   | 1         | 1.04%   |
| Dell XPS 13 9305                                 | 1         | 1.04%   |
| Dell Vostro 3500                                 | 1         | 1.04%   |
| Dell Precision M4400                             | 1         | 1.04%   |
| Dell Precision 7520                              | 1         | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 7         | 7.29%   |
| Dell Inspiron          | 6         | 6.25%   |
| HP Laptop              | 5         | 5.21%   |
| Dell Latitude          | 4         | 4.17%   |
| Lenovo IdeaPad         | 3         | 3.13%   |
| ASUS PRIME             | 3         | 3.13%   |
| Toshiba Satellite      | 2         | 2.08%   |
| Lenovo ThinkPad        | 2         | 2.08%   |
| Lenovo ThinkCentre     | 2         | 2.08%   |
| HP ProBook             | 2         | 2.08%   |
| HP Pavilion            | 2         | 2.08%   |
| HP EliteBook           | 2         | 2.08%   |
| HP Compaq              | 2         | 2.08%   |
| HP 255                 | 2         | 2.08%   |
| Dell XPS               | 2         | 2.08%   |
| Dell Precision         | 2         | 2.08%   |
| ASUS VivoBook          | 2         | 2.08%   |
| Unknown                | 2         | 2.08%   |
| Sony SVE1713Y1RB       | 1         | 1.04%   |
| Samsung 730QDA         | 1         | 1.04%   |
| Philco 10D             | 1         | 1.04%   |
| Panasonic CF-H2BJJHZDE | 1         | 1.04%   |
| Packard Bell DOT       | 1         | 1.04%   |
| Multilaser PC150       | 1         | 1.04%   |
| MSI U180               | 1         | 1.04%   |
| MSI MS-7B79            | 1         | 1.04%   |
| MSI MS-7B17            | 1         | 1.04%   |
| MSI MS-7977            | 1         | 1.04%   |
| MSI MS-7974            | 1         | 1.04%   |
| Medion E6220           | 1         | 1.04%   |
| LincPlus LINNCPLUS     | 1         | 1.04%   |
| Lenovo Z50-70          | 1         | 1.04%   |
| Lenovo Yoga            | 1         | 1.04%   |
| Lenovo V55t-15ARE      | 1         | 1.04%   |
| Lenovo Legion          | 1         | 1.04%   |
| Lenovo IdeaPadFlex     | 1         | 1.04%   |
| Intel DQ77MK           | 1         | 1.04%   |
| Howard Computers R7X   | 1         | 1.04%   |
| HP ZBook               | 1         | 1.04%   |
| HP Z820                | 1         | 1.04%   |
| HP Z600                | 1         | 1.04%   |
| HP Presario            | 1         | 1.04%   |
| HP Notebook            | 1         | 1.04%   |
| HP ENVY                | 1         | 1.04%   |
| HP 14                  | 1         | 1.04%   |
| Gigabyte Z68A-D3H-B3   | 1         | 1.04%   |
| Gigabyte H110M-S2H     | 1         | 1.04%   |
| Framework Laptop       | 1         | 1.04%   |
| Dell Vostro            | 1         | 1.04%   |
| ASUS P6T               | 1         | 1.04%   |
| ASUS P5G41T-M          | 1         | 1.04%   |
| ASUS N61Jv             | 1         | 1.04%   |
| ASUS 1005P             | 1         | 1.04%   |
| ASRock A320M-DGS       | 1         | 1.04%   |
| Apple MacBookPro14     | 1         | 1.04%   |
| Apple MacBookAir7      | 1         | 1.04%   |
| Apple MacBookAir6      | 1         | 1.04%   |
| Apple iMac5            | 1         | 1.04%   |
| Alienware 14           | 1         | 1.04%   |
| Acer Veriton           | 1         | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 16        | 16.67%  |
| 2012 | 10        | 10.42%  |
| 2020 | 9         | 9.38%   |
| 2018 | 7         | 7.29%   |
| 2013 | 7         | 7.29%   |
| 2016 | 6         | 6.25%   |
| 2019 | 5         | 5.21%   |
| 2017 | 5         | 5.21%   |
| 2010 | 5         | 5.21%   |
| 2009 | 5         | 5.21%   |
| 2008 | 5         | 5.21%   |
| 2015 | 4         | 4.17%   |
| 2011 | 4         | 4.17%   |
| 2007 | 4         | 4.17%   |
| 2014 | 3         | 3.13%   |
| 2006 | 1         | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 68        | 70.83%  |
| Desktop     | 23        | 23.96%  |
| Convertible | 3         | 3.13%   |
| Tablet      | 1         | 1.04%   |
| All in one  | 1         | 1.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 86        | 88.66%  |
| Enabled  | 11        | 11.34%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 28.87%  |
| 3.01-4.0    | 20        | 20.62%  |
| 16.01-24.0  | 14        | 14.43%  |
| 8.01-16.0   | 12        | 12.37%  |
| 1.01-2.0    | 9         | 9.28%   |
| 32.01-64.0  | 6         | 6.19%   |
| 2.01-3.0    | 4         | 4.12%   |
| 24.01-32.0  | 2         | 2.06%   |
| 64.01-256.0 | 2         | 2.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 38        | 38.78%  |
| 2.01-3.0 | 33        | 33.67%  |
| 3.01-4.0 | 14        | 14.29%  |
| 0.51-1.0 | 8         | 8.16%   |
| 4.01-8.0 | 5         | 5.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 69.79%  |
| 2      | 18        | 18.75%  |
| 3      | 6         | 6.25%   |
| 4      | 4         | 4.17%   |
| 6      | 1         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 64.58%  |
| Yes       | 34        | 35.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 82.29%  |
| No        | 17        | 17.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 86.46%  |
| No        | 13        | 13.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 55.21%  |
| No        | 43        | 44.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 19.79%  |
| UK          | 10        | 10.42%  |
| Russia      | 8         | 8.33%   |
| Germany     | 7         | 7.29%   |
| Brazil      | 7         | 7.29%   |
| Canada      | 5         | 5.21%   |
| Spain       | 4         | 4.17%   |
| Poland      | 4         | 4.17%   |
| France      | 4         | 4.17%   |
| Mexico      | 3         | 3.13%   |
| Romania     | 2         | 2.08%   |
| Italy       | 2         | 2.08%   |
| Chile       | 2         | 2.08%   |
| Bolivia     | 2         | 2.08%   |
| Australia   | 2         | 2.08%   |
| Venezuela   | 1         | 1.04%   |
| Turkey      | 1         | 1.04%   |
| Sweden      | 1         | 1.04%   |
| South Korea | 1         | 1.04%   |
| Portugal    | 1         | 1.04%   |
| Peru        | 1         | 1.04%   |
| Malaysia    | 1         | 1.04%   |
| Lithuania   | 1         | 1.04%   |
| Latvia      | 1         | 1.04%   |
| Kenya       | 1         | 1.04%   |
| Hungary     | 1         | 1.04%   |
| Ecuador     | 1         | 1.04%   |
| Belgium     | 1         | 1.04%   |
| Belarus     | 1         | 1.04%   |
| Austria     | 1         | 1.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Moscow                   | 3         | 3.13%   |
| Oruro                    | 2         | 2.08%   |
| Neasden                  | 2         | 2.08%   |
| Montreal                 | 2         | 2.08%   |
| Melbourne                | 2         | 2.08%   |
| Wroclaw                  | 1         | 1.04%   |
| Vincennes                | 1         | 1.04%   |
| Vilnius                  | 1         | 1.04%   |
| Vicente Guerrero         | 1         | 1.04%   |
| Veurne                   | 1         | 1.04%   |
| Vaslui                   | 1         | 1.04%   |
| Uiwang                   | 1         | 1.04%   |
| Tula                     | 1         | 1.04%   |
| Troisdorf                | 1         | 1.04%   |
| Trieste                  | 1         | 1.04%   |
| Toledo                   | 1         | 1.04%   |
| Tipton                   | 1         | 1.04%   |
| Stockbridge              | 1         | 1.04%   |
| Spruce Grove             | 1         | 1.04%   |
| Spearfish                | 1         | 1.04%   |
| Scarborough              | 1         | 1.04%   |
| Saratov                  | 1         | 1.04%   |
| Santiago                 | 1         | 1.04%   |
| Sant Feliu de Llobregat  | 1         | 1.04%   |
| San Antonio de Los Altos | 1         | 1.04%   |
| Rochester                | 1         | 1.04%   |
| Riga                     | 1         | 1.04%   |
| Recife                   | 1         | 1.04%   |
| Queens                   | 1         | 1.04%   |
| Providencia              | 1         | 1.04%   |
| Prestatyn                | 1         | 1.04%   |
| Porto Alegre             | 1         | 1.04%   |
| Peterborough             | 1         | 1.04%   |
| Petaling Jaya            | 1         | 1.04%   |
| Ordonnac                 | 1         | 1.04%   |
| Nuremberg                | 1         | 1.04%   |
| Nottingham               | 1         | 1.04%   |
| National City            | 1         | 1.04%   |
| Nairobi                  | 1         | 1.04%   |
| Murphy                   | 1         | 1.04%   |
| Mosonmagyaróvár        | 1         | 1.04%   |
| Monaca                   | 1         | 1.04%   |
| Minsk                    | 1         | 1.04%   |
| Mieuxce                  | 1         | 1.04%   |
| Marrero                  | 1         | 1.04%   |
| Mannheim                 | 1         | 1.04%   |
| Mammoth Lakes            | 1         | 1.04%   |
| Madrid                   | 1         | 1.04%   |
| Londonderry              | 1         | 1.04%   |
| London                   | 1         | 1.04%   |
| Lisbon                   | 1         | 1.04%   |
| Limoges                  | 1         | 1.04%   |
| Limburg an der Lahn      | 1         | 1.04%   |
| Lima                     | 1         | 1.04%   |
| Lebanon                  | 1         | 1.04%   |
| Lawrenceville            | 1         | 1.04%   |
| Krakow                   | 1         | 1.04%   |
| Knurow                   | 1         | 1.04%   |
| Katowice                 | 1         | 1.04%   |
| Ivanovo                  | 1         | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 20        | 28     | 15.87%  |
| Samsung Electronics            | 16        | 18     | 12.7%   |
| Seagate                        | 15        | 17     | 11.9%   |
| Kingston                       | 8         | 8      | 6.35%   |
| Hitachi                        | 8         | 9      | 6.35%   |
| Toshiba                        | 7         | 8      | 5.56%   |
| Unknown                        | 5         | 5      | 3.97%   |
| SanDisk                        | 5         | 5      | 3.97%   |
| Intel                          | 4         | 4      | 3.17%   |
| Micron Technology              | 3         | 3      | 2.38%   |
| Crucial                        | 3         | 3      | 2.38%   |
| Apple                          | 3         | 6      | 2.38%   |
| A-DATA Technology              | 3         | 3      | 2.38%   |
| SK hynix                       | 2         | 2      | 1.59%   |
| Phison                         | 2         | 2      | 1.59%   |
| Patriot                        | 2         | 2      | 1.59%   |
| HGST                           | 2         | 2      | 1.59%   |
| Transcend                      | 1         | 2      | 0.79%   |
| Team                           | 1         | 1      | 0.79%   |
| Solid State Storage Technology | 1         | 1      | 0.79%   |
| ShiJi                          | 1         | 1      | 0.79%   |
| SABRENT                        | 1         | 1      | 0.79%   |
| PNY                            | 1         | 1      | 0.79%   |
| Oyen                           | 1         | 1      | 0.79%   |
| ORICO                          | 1         | 1      | 0.79%   |
| OCZ-VERTEX                     | 1         | 1      | 0.79%   |
| Micron/Crucial Technology      | 1         | 2      | 0.79%   |
| LITEON                         | 1         | 1      | 0.79%   |
| KIOXIA                         | 1         | 2      | 0.79%   |
| KingSpec                       | 1         | 1      | 0.79%   |
| Initio                         | 1         | 1      | 0.79%   |
| Hewlett-Packard                | 1         | 1      | 0.79%   |
| China                          | 1         | 2      | 0.79%   |
| BHT                            | 1         | 1      | 0.79%   |
| Acer                           | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB          | 3         | 2.26%   |
| Micron NVMe SSD Drive 512GB              | 3         | 2.26%   |
| Kingston SA400S37240G 240GB SSD          | 3         | 2.26%   |
| Kingston SA400S37120G 120GB SSD          | 3         | 2.26%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 2         | 1.5%    |
| Unknown SD/MMC/MS PRO 128GB              | 2         | 1.5%    |
| Toshiba MQ01ABD100 1TB                   | 2         | 1.5%    |
| Seagate ST2000DM008-2FR102 2TB           | 2         | 1.5%    |
| Samsung SSD 970 EVO Plus 1TB             | 2         | 1.5%    |
| Samsung SSD 850 EVO 250GB                | 2         | 1.5%    |
| Samsung PM991a NVMe 512GB                | 2         | 1.5%    |
| Crucial CT480BX500SSD1 480GB             | 2         | 1.5%    |
| A-DATA SU650 120GB SSD                   | 2         | 1.5%    |
| WDC WDS100T3X0C-00SJG0 1TB               | 1         | 0.75%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 0.75%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 0.75%   |
| WDC WD60EZAZ-00ZGHB0 6TB                 | 1         | 0.75%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 1         | 0.75%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 0.75%   |
| WDC WD3200AAJS-22B4A0 320GB              | 1         | 0.75%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 0.75%   |
| WDC WD3003FZEX-00Z4SA0 3TB               | 1         | 0.75%   |
| WDC WD30 EFRX-68EUZN0 3TB                | 1         | 0.75%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 0.75%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1         | 0.75%   |
| WDC WD10EFRX-68JCSN0 1TB                 | 1         | 0.75%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1         | 0.75%   |
| WDC WD10EAVS-00D7B0 1TB                  | 1         | 0.75%   |
| WDC WD1003FZEX-00MK2A0 1TB               | 1         | 0.75%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB     | 1         | 0.75%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB     | 1         | 0.75%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 0.75%   |
| Unknown USB DISK 3.2 1TB                 | 1         | 0.75%   |
| Unknown MMC Card  32GB                   | 1         | 0.75%   |
| Unknown Biwin  64GB                      | 1         | 0.75%   |
| Transcend TS480GSSD220S 480GB            | 1         | 0.75%   |
| Transcend TS240GSSD220S 240GB            | 1         | 0.75%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 0.75%   |
| Toshiba MQ01ABF032 320GB                 | 1         | 0.75%   |
| Toshiba MK3275GSX 320GB                  | 1         | 0.75%   |
| Toshiba MK3252GSX 320GB                  | 1         | 0.75%   |
| Toshiba DT01ACA050 500GB                 | 1         | 0.75%   |
| Team T253X6512G 512GB SSD                | 1         | 0.75%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 0.75%   |
| SK hynix HFS256G32MND-3310A 256GB SSD    | 1         | 0.75%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 0.75%   |
| ShiJi 256GB                              | 1         | 0.75%   |
| Seagate ST9250315AS 250GB                | 1         | 0.75%   |
| Seagate ST9160412ASG 160GB               | 1         | 0.75%   |
| Seagate ST3500312CS 500GB                | 1         | 0.75%   |
| Seagate ST3250318AS 250GB                | 1         | 0.75%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 0.75%   |
| Seagate ST3160812AS Q 160GB              | 1         | 0.75%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 0.75%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 0.75%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 23     | 30.61%  |
| Seagate | 15        | 17     | 30.61%  |
| Hitachi | 8         | 9      | 16.33%  |
| Toshiba | 7         | 8      | 14.29%  |
| Unknown | 2         | 2      | 4.08%   |
| HGST    | 2         | 2      | 4.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 19.05%  |
| Samsung Electronics | 7         | 8      | 16.67%  |
| Crucial             | 3         | 3      | 7.14%   |
| A-DATA Technology   | 3         | 3      | 7.14%   |
| SanDisk             | 2         | 2      | 4.76%   |
| Patriot             | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| Apple               | 2         | 2      | 4.76%   |
| WDC                 | 1         | 1      | 2.38%   |
| Transcend           | 1         | 2      | 2.38%   |
| Team                | 1         | 1      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| PNY                 | 1         | 1      | 2.38%   |
| ORICO               | 1         | 1      | 2.38%   |
| OCZ-VERTEX          | 1         | 1      | 2.38%   |
| LITEON              | 1         | 1      | 2.38%   |
| KingSpec            | 1         | 1      | 2.38%   |
| Hewlett-Packard     | 1         | 1      | 2.38%   |
| China               | 1         | 2      | 2.38%   |
| BHT                 | 1         | 1      | 2.38%   |
| Acer                | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 44        | 61     | 37.93%  |
| SSD     | 38        | 45     | 32.76%  |
| NVMe    | 27        | 34     | 23.28%  |
| Unknown | 4         | 4      | 3.45%   |
| MMC     | 3         | 3      | 2.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 103    | 67.92%  |
| NVMe | 26        | 33     | 24.53%  |
| SAS  | 5         | 8      | 4.72%   |
| MMC  | 3         | 3      | 2.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 70     | 68.67%  |
| 0.51-1.0   | 17        | 23     | 20.48%  |
| 1.01-2.0   | 4         | 5      | 4.82%   |
| 2.01-3.0   | 3         | 6      | 3.61%   |
| 4.01-10.0  | 2         | 2      | 2.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 28.13%  |
| 101-250        | 24        | 25%     |
| 51-100         | 11        | 11.46%  |
| 501-1000       | 10        | 10.42%  |
| 1001-2000      | 7         | 7.29%   |
| 1-20           | 7         | 7.29%   |
| 21-50          | 5         | 5.21%   |
| More than 3000 | 3         | 3.13%   |
| 2001-3000      | 2         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 53        | 53.54%  |
| 21-50     | 21        | 21.21%  |
| 51-100    | 8         | 8.08%   |
| 101-250   | 6         | 6.06%   |
| 251-500   | 4         | 4.04%   |
| 501-1000  | 4         | 4.04%   |
| 1001-2000 | 2         | 2.02%   |
| 2001-3000 | 1         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 16.67%  |
| Seagate ST3250318AS 250GB       | 1         | 1      | 16.67%  |
| Phison ES 512GB                 | 1         | 1      | 16.67%  |
| Intel SSDSCKKF256G8 SATA 256GB  | 1         | 1      | 16.67%  |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 16.67%  |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 33.33%  |
| Phison  | 1         | 1      | 16.67%  |
| Intel   | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 66.67%  |
| NVMe | 1         | 1      | 16.67%  |
| SSD  | 1         | 1      | 16.67%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 63        | 94     | 61.76%  |
| Works    | 33        | 47     | 32.35%  |
| Malfunc  | 6         | 6      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 66        | 56.9%   |
| AMD                            | 20        | 17.24%  |
| Samsung Electronics            | 10        | 8.62%   |
| SanDisk                        | 6         | 5.17%   |
| Micron Technology              | 3         | 2.59%   |
| Phison Electronics             | 2         | 1.72%   |
| Toshiba America Info Systems   | 1         | 0.86%   |
| Solid State Storage Technology | 1         | 0.86%   |
| SK hynix                       | 1         | 0.86%   |
| Micron/Crucial Technology      | 1         | 0.86%   |
| Marvell Technology Group       | 1         | 0.86%   |
| JMicron Technology             | 1         | 0.86%   |
| Broadcom / LSI                 | 1         | 0.86%   |
| ASMedia Technology             | 1         | 0.86%   |
| Apple                          | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 12.12%  |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 4.55%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 3.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 3.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 3.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.27%   |
| Micron Non-Volatile memory controller                                                   | 3         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 2.27%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 1.52%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 1.52%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.76%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 0.76%   |
| SK hynix BC511                                                                          | 1         | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.76%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.76%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.76%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1         | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.76%   |
| Intel SSD 660P Series                                                                   | 1         | 0.76%   |
| Intel SSD 600P Series                                                                   | 1         | 0.76%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.76%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 0.76%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 0.76%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 0.76%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.76%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.76%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 69        | 57.02%  |
| NVMe | 26        | 21.49%  |
| IDE  | 14        | 11.57%  |
| RAID | 11        | 9.09%   |
| SAS  | 1         | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 76.04%  |
| AMD    | 23        | 23.96%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 4.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 4.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 4.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 3.13%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 2.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 2.08%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 2.08%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 1.04%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1         | 1.04%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 1.04%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.04%   |
| Intel Pentium M processor 1.73GHz           | 1         | 1.04%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 1.04%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 1         | 1.04%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.04%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 1.04%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.04%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.04%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.04%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.04%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.04%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 1.04%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 1.04%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 1.04%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.04%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.04%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 1.04%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.04%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.04%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1         | 1.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.04%   |
| Intel Core i5-2557M CPU @ 1.70GHz           | 1         | 1.04%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.04%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.04%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.04%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 1.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.04%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.04%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 1.04%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 1.04%   |
| Intel Core 2 Extreme CPU X9100 @ 3.06GHz    | 1         | 1.04%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.04%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 1         | 1.04%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.04%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.04%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz        | 1         | 1.04%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.04%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.04%   |
| Intel Celeron M CPU 520 @ 1.60GHz           | 1         | 1.04%   |
| Intel Celeron M CPU 440 @ 1.86GHz           | 1         | 1.04%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.04%   |
| Intel Celeron CPU N2815 @ 1.86GHz           | 1         | 1.04%   |
| Intel Celeron 2955U @ 1.40GHz               | 1         | 1.04%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 15.63%  |
| Other                   | 12        | 12.5%   |
| Intel Core i7           | 11        | 11.46%  |
| AMD Ryzen 5             | 8         | 8.33%   |
| Intel Core i3           | 6         | 6.25%   |
| Intel Core 2 Duo        | 6         | 6.25%   |
| Intel Atom              | 6         | 6.25%   |
| Intel Celeron           | 4         | 4.17%   |
| AMD Ryzen 7             | 4         | 4.17%   |
| Intel Xeon              | 3         | 3.13%   |
| Intel Pentium           | 3         | 3.13%   |
| Intel Pentium Dual-Core | 2         | 2.08%   |
| Intel Celeron M         | 2         | 2.08%   |
| AMD E2                  | 2         | 2.08%   |
| AMD E1                  | 2         | 2.08%   |
| Intel Pentium Silver    | 1         | 1.04%   |
| Intel Pentium M         | 1         | 1.04%   |
| Intel Core 2 Extreme    | 1         | 1.04%   |
| Intel Core 2            | 1         | 1.04%   |
| AMD Ryzen 3             | 1         | 1.04%   |
| AMD FX                  | 1         | 1.04%   |
| AMD C-50                | 1         | 1.04%   |
| AMD Athlon              | 1         | 1.04%   |
| AMD A4                  | 1         | 1.04%   |
| AMD A10                 | 1         | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 51.04%  |
| 4      | 27        | 28.13%  |
| 8      | 7         | 7.29%   |
| 6      | 7         | 7.29%   |
| 1      | 5         | 5.21%   |
| 16     | 1         | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 94        | 97.92%  |
| 2      | 2         | 2.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 63        | 65.63%  |
| 1      | 33        | 34.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 92        | 95.83%  |
| 32-bit         | 4         | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 9         | 9.38%   |
| 0x306a9    | 5         | 5.21%   |
| 0x08608103 | 5         | 5.21%   |
| 0x40651    | 4         | 4.17%   |
| 0x30661    | 4         | 4.17%   |
| 0x206a7    | 4         | 4.17%   |
| 0x1067a    | 4         | 4.17%   |
| 0x08108109 | 4         | 4.17%   |
| 0x6fd      | 3         | 3.13%   |
| 0x506e3    | 3         | 3.13%   |
| 0x406e3    | 3         | 3.13%   |
| Unknown    | 3         | 3.13%   |
| 0x806e9    | 2         | 2.08%   |
| 0x6f6      | 2         | 2.08%   |
| 0x306c3    | 2         | 2.08%   |
| 0x20652    | 2         | 2.08%   |
| 0x10676    | 2         | 2.08%   |
| 0xa0653    | 1         | 1.04%   |
| 0xa0652    | 1         | 1.04%   |
| 0x906ed    | 1         | 1.04%   |
| 0x906ea    | 1         | 1.04%   |
| 0x90675    | 1         | 1.04%   |
| 0x806ec    | 1         | 1.04%   |
| 0x806ea    | 1         | 1.04%   |
| 0x806d1    | 1         | 1.04%   |
| 0x706e5    | 1         | 1.04%   |
| 0x706a8    | 1         | 1.04%   |
| 0x706a1    | 1         | 1.04%   |
| 0x6ec      | 1         | 1.04%   |
| 0x6d8      | 1         | 1.04%   |
| 0x506c9    | 1         | 1.04%   |
| 0x306d4    | 1         | 1.04%   |
| 0x30673    | 1         | 1.04%   |
| 0x206d7    | 1         | 1.04%   |
| 0x206c2    | 1         | 1.04%   |
| 0x106e5    | 1         | 1.04%   |
| 0x106ca    | 1         | 1.04%   |
| 0x106c2    | 1         | 1.04%   |
| 0x106a5    | 1         | 1.04%   |
| 0x08600103 | 1         | 1.04%   |
| 0x08108102 | 1         | 1.04%   |
| 0x0810100b | 1         | 1.04%   |
| 0x08001137 | 1         | 1.04%   |
| 0x07030106 | 1         | 1.04%   |
| 0x07030105 | 1         | 1.04%   |
| 0x07000110 | 1         | 1.04%   |
| 0x0700010f | 1         | 1.04%   |
| 0x06006705 | 1         | 1.04%   |
| 0x06006704 | 1         | 1.04%   |
| 0x0600611a | 1         | 1.04%   |
| 0x06000852 | 1         | 1.04%   |
| 0x05000029 | 1         | 1.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| TigerLake     | 9         | 9.38%   |
| Skylake       | 6         | 6.25%   |
| Penryn        | 6         | 6.25%   |
| KabyLake      | 6         | 6.25%   |
| IvyBridge     | 6         | 6.25%   |
| Haswell       | 6         | 6.25%   |
| Bonnell       | 6         | 6.25%   |
| Unknown       | 6         | 6.25%   |
| Zen+          | 5         | 5.21%   |
| SandyBridge   | 5         | 5.21%   |
| Core          | 5         | 5.21%   |
| Westmere      | 3         | 3.13%   |
| Excavator     | 3         | 3.13%   |
| Zen           | 2         | 2.08%   |
| Puma          | 2         | 2.08%   |
| P6            | 2         | 2.08%   |
| Nehalem       | 2         | 2.08%   |
| Jaguar        | 2         | 2.08%   |
| Icelake       | 2         | 2.08%   |
| Goldmont plus | 2         | 2.08%   |
| CometLake     | 2         | 2.08%   |
| Broadwell     | 2         | 2.08%   |
| Zen 3         | 1         | 1.04%   |
| Zen 2         | 1         | 1.04%   |
| Silvermont    | 1         | 1.04%   |
| Piledriver    | 1         | 1.04%   |
| Goldmont      | 1         | 1.04%   |
| Bobcat        | 1         | 1.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 48.57%  |
| Nvidia | 27        | 25.71%  |
| AMD    | 27        | 25.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 6.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 4.59%   |
| AMD Lucienne                                                                  | 5         | 4.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 3.67%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 4         | 3.67%   |
| Nvidia GT218 [GeForce 210]                                                    | 3         | 2.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 2.75%   |
| Nvidia GK208B [GeForce GT 730]                                                | 2         | 1.83%   |
| Nvidia G98M [Quadro NVS 160M]                                                 | 2         | 1.83%   |
| Intel Tiger Lake UHD Graphics                                                 | 2         | 1.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.83%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 1.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.83%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 1         | 0.92%   |
| Nvidia GT216M [GeForce GT 325M]                                               | 1         | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.92%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                         | 1         | 0.92%   |
| Nvidia GM107GL [Quadro K620]                                                  | 1         | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 0.92%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 0.92%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                             | 1         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.92%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 1         | 0.92%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                             | 1         | 0.92%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                             | 1         | 0.92%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                            | 1         | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 0.92%   |
| Nvidia G96GLM [Quadro FX 1700M]                                               | 1         | 0.92%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 1         | 0.92%   |
| Nvidia G94GLM [Quadro FX 2700M]                                               | 1         | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 0.92%   |
| Intel UHD Graphics 620                                                        | 1         | 0.92%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.92%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 0.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.92%   |
| Intel Iris Plus Graphics 640                                                  | 1         | 0.92%   |
| Intel HD Graphics 620                                                         | 1         | 0.92%   |
| Intel HD Graphics 6000                                                        | 1         | 0.92%   |
| Intel HD Graphics 5500                                                        | 1         | 0.92%   |
| Intel HD Graphics 530                                                         | 1         | 0.92%   |
| Intel HD Graphics 500                                                         | 1         | 0.92%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 1         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 0.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 0.92%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 1         | 0.92%   |
| AMD Wrestler [Radeon HD 6250]                                                 | 1         | 0.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 44.33%  |
| 1 x AMD        | 23        | 23.71%  |
| 1 x Nvidia     | 21        | 21.65%  |
| Intel + Nvidia | 6         | 6.19%   |
| 2 x AMD        | 2         | 2.06%   |
| Intel + AMD    | 1         | 1.03%   |
| AMD + Nvidia   | 1         | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 89        | 92.71%  |
| Proprietary | 4         | 4.17%   |
| Unknown     | 3         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 48.96%  |
| 0.01-0.5   | 19        | 19.79%  |
| 1.01-2.0   | 16        | 16.67%  |
| 0.51-1.0   | 7         | 7.29%   |
| 3.01-4.0   | 6         | 6.25%   |
| 5.01-6.0   | 1         | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 18.18%  |
| BOE                     | 13        | 13.13%  |
| Chimei Innolux          | 10        | 10.1%   |
| LG Display              | 9         | 9.09%   |
| Samsung Electronics     | 8         | 8.08%   |
| Apple                   | 4         | 4.04%   |
| Philips                 | 3         | 3.03%   |
| LG Philips              | 3         | 3.03%   |
| Dell                    | 3         | 3.03%   |
| Ancor Communications    | 3         | 3.03%   |
| Acer                    | 3         | 3.03%   |
| PANDA                   | 2         | 2.02%   |
| InfoVision              | 2         | 2.02%   |
| Hewlett-Packard         | 2         | 2.02%   |
| HannStar                | 2         | 2.02%   |
| ___                     | 1         | 1.01%   |
| Unknown                 | 1         | 1.01%   |
| TR_                     | 1         | 1.01%   |
| Sharp                   | 1         | 1.01%   |
| Quanta Display          | 1         | 1.01%   |
| Planar                  | 1         | 1.01%   |
| Medion                  | 1         | 1.01%   |
| Lenovo                  | 1         | 1.01%   |
| Insignia                | 1         | 1.01%   |
| Goldstar                | 1         | 1.01%   |
| DENON                   | 1         | 1.01%   |
| Chi Mei Optoelectronics | 1         | 1.01%   |
| BenQ                    | 1         | 1.01%   |
| ASUSTek Computer        | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 1.96%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.96%   |
| ___ LCD TV ___0101 1360x768                                              | 1         | 0.98%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                       | 1         | 0.98%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 0.98%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch     | 1         | 0.98%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 0.98%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 0.98%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch       | 1         | 0.98%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.98%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 0.98%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 0.98%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch                | 1         | 0.98%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 1         | 0.98%   |
| Philips LCD Monitor PHL 242V8 1920x1080                                  | 1         | 0.98%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 0.98%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 0.98%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                      | 1         | 0.98%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch             | 1         | 0.98%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                      | 1         | 0.98%   |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch             | 1         | 0.98%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch              | 1         | 0.98%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch               | 1         | 0.98%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch               | 1         | 0.98%   |
| Hewlett-Packard E232 HWP3279 1920x1080 510x290mm 23.1-inch               | 1         | 0.98%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 0.98%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 0.98%   |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                    | 1         | 0.98%   |
| DENON AVR DON005F 1920x1080                                              | 1         | 0.98%   |
| Dell U2415 DELA0B8 1920x1200 520x320mm 24.0-inch                         | 1         | 0.98%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 0.98%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 0.98%   |
| Dell 2007WFP DELA019 1680x1050 434x270mm 20.1-inch                       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1375 1920x1080 293x165mm 13.2-inch         | 1         | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 1         | 0.98%   |
| BOE LCD Monitor BOE099E 1920x1080 344x194mm 15.5-inch                    | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 43        | 45.74%  |
| 1366x768 (WXGA)    | 18        | 19.15%  |
| 1600x900 (HD+)     | 6         | 6.38%   |
| 1920x1200 (WUXGA)  | 5         | 5.32%   |
| 1440x900 (WXGA+)   | 4         | 4.26%   |
| 1024x600           | 4         | 4.26%   |
| 1280x800 (WXGA)    | 3         | 3.19%   |
| 2560x1440 (QHD)    | 2         | 2.13%   |
| 1680x1050 (WSXGA+) | 2         | 2.13%   |
| 3840x2160 (4K)     | 1         | 1.06%   |
| 2880x1800          | 1         | 1.06%   |
| 2560x1080          | 1         | 1.06%   |
| 2256x1504          | 1         | 1.06%   |
| 1280x768           | 1         | 1.06%   |
| 1280x720 (HD)      | 1         | 1.06%   |
| 1280x1024 (SXGA)   | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 32%     |
| 13      | 14        | 14%     |
| 14      | 10        | 10%     |
| 24      | 7         | 7%      |
| 17      | 6         | 6%      |
| 21      | 5         | 5%      |
| 27      | 4         | 4%      |
| 10      | 4         | 4%      |
| 23      | 3         | 3%      |
| 20      | 3         | 3%      |
| 72      | 2         | 2%      |
| Unknown | 2         | 2%      |
| 32      | 1         | 1%      |
| 31      | 1         | 1%      |
| 28      | 1         | 1%      |
| 22      | 1         | 1%      |
| 19      | 1         | 1%      |
| 16      | 1         | 1%      |
| 11      | 1         | 1%      |
| 8       | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 50%     |
| 501-600     | 13        | 13.27%  |
| 201-300     | 12        | 12.24%  |
| 401-500     | 8         | 8.16%   |
| 351-400     | 8         | 8.16%   |
| 601-700     | 2         | 2.04%   |
| 1501-2000   | 2         | 2.04%   |
| Unknown     | 2         | 2.04%   |
| 701-800     | 1         | 1.02%   |
| 101-200     | 1         | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 72        | 79.12%  |
| 16/10   | 14        | 15.38%  |
| Unknown | 2         | 2.2%    |
| 5/4     | 1         | 1.1%    |
| 3/2     | 1         | 1.1%    |
| 21/9    | 1         | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 32.32%  |
| 81-90          | 18        | 18.18%  |
| 201-250        | 12        | 12.12%  |
| 71-80          | 6         | 6.06%   |
| 41-50          | 4         | 4.04%   |
| 301-350        | 4         | 4.04%   |
| 251-300        | 4         | 4.04%   |
| 151-200        | 4         | 4.04%   |
| 121-130        | 4         | 4.04%   |
| More than 1000 | 2         | 2.02%   |
| 351-500        | 2         | 2.02%   |
| 131-140        | 2         | 2.02%   |
| Unknown        | 2         | 2.02%   |
| 51-60          | 1         | 1.01%   |
| 1-40           | 1         | 1.01%   |
| 91-100         | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 34.34%  |
| 101-120       | 29        | 29.29%  |
| 51-100        | 26        | 26.26%  |
| 161-240       | 5         | 5.05%   |
| 1-50          | 2         | 2.02%   |
| Unknown       | 2         | 2.02%   |
| More than 240 | 1         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 84        | 87.5%   |
| 2     | 7         | 7.29%   |
| 3     | 3         | 3.13%   |
| 0     | 2         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 53        | 38.13%  |
| Intel                         | 41        | 29.5%   |
| Qualcomm Atheros              | 18        | 12.95%  |
| Broadcom                      | 10        | 7.19%   |
| Ralink Technology             | 3         | 2.16%   |
| Marvell Technology Group      | 3         | 2.16%   |
| Broadcom Limited              | 3         | 2.16%   |
| Xiaomi                        | 1         | 0.72%   |
| Samsung Electronics           | 1         | 0.72%   |
| Ralink                        | 1         | 0.72%   |
| OnePlus Technology (Shenzhen) | 1         | 0.72%   |
| Microchip Technology          | 1         | 0.72%   |
| Mercucys                      | 1         | 0.72%   |
| JMicron Technology            | 1         | 0.72%   |
| Belkin Components             | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 24        | 13.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 11        | 6.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 7         | 3.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6         | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 2.79%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 2.79%   |
| Intel 82567LM Gigabit Network Connection                                                      | 4         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.68%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 1.68%   |
| Intel Wireless 3165                                                                           | 3         | 1.68%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 1.68%   |
| Intel Ultimate N WiFi Link 5300                                                               | 3         | 1.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 1.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 2         | 1.12%   |
| Realtek 802.11ac NIC                                                                          | 2         | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 1.12%   |
| Intel Wireless 7260                                                                           | 2         | 1.12%   |
| Intel WiFi Link 5100                                                                          | 2         | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2         | 1.12%   |
| Intel 82574L Gigabit Network Connection                                                       | 2         | 1.12%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.56%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.56%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.56%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.56%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.56%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.56%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 0.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.56%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                                                    | 1         | 0.56%   |
| Microchip LAN9500/LAN9500i                                                                    | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 33.71%  |
| Intel                 | 29        | 32.58%  |
| Qualcomm Atheros      | 14        | 15.73%  |
| Broadcom              | 7         | 7.87%   |
| Ralink Technology     | 3         | 3.37%   |
| Broadcom Limited      | 3         | 3.37%   |
| Ralink                | 1         | 1.12%   |
| Mercucys              | 1         | 1.12%   |
| Belkin Components     | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 7         | 7.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 5.38%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.23%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 3.23%   |
| Intel Wireless 3165                                                                           | 3         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 3.23%   |
| Intel Ultimate N WiFi Link 5300                                                               | 3         | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 2.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 2.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 2.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 2.15%   |
| Realtek 802.11ac NIC                                                                          | 2         | 2.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 2.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 2.15%   |
| Intel Wireless 7260                                                                           | 2         | 2.15%   |
| Intel WiFi Link 5100                                                                          | 2         | 2.15%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 1.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.08%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.08%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 1.08%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.08%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 1.08%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 1.08%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 1.08%   |
| Intel Wireless 7265                                                                           | 1         | 1.08%   |
| Intel Wireless 3160                                                                           | 1         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 1.08%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.08%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1         | 1.08%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1         | 1.08%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.08%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 1.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.08%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 40        | 48.78%  |
| Intel                         | 23        | 28.05%  |
| Qualcomm Atheros              | 8         | 9.76%   |
| Marvell Technology Group      | 3         | 3.66%   |
| Broadcom                      | 3         | 3.66%   |
| Xiaomi                        | 1         | 1.22%   |
| Samsung Electronics           | 1         | 1.22%   |
| OnePlus Technology (Shenzhen) | 1         | 1.22%   |
| Microchip Technology          | 1         | 1.22%   |
| JMicron Technology            | 1         | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 28.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 12.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.06%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 4.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.35%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.35%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.18%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.18%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.18%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                        | 1         | 1.18%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 1.18%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.18%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.18%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.18%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.18%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.18%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.18%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.18%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.18%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.18%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 1.18%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 1.18%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.18%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 51.23%  |
| Ethernet | 78        | 48.15%  |
| Modem    | 1         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 64%     |
| Ethernet | 36        | 36%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 59.38%  |
| 1     | 36        | 37.5%   |
| 0     | 3         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 73.2%   |
| Yes  | 26        | 26.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 42.59%  |
| Realtek Semiconductor           | 14        | 25.93%  |
| Qualcomm Atheros Communications | 3         | 5.56%   |
| Dell                            | 3         | 5.56%   |
| Apple                           | 3         | 5.56%   |
| Foxconn / Hon Hai               | 2         | 3.7%    |
| Cambridge Silicon Radio         | 2         | 3.7%    |
| Lite-On Technology              | 1         | 1.85%   |
| IMC Networks                    | 1         | 1.85%   |
| Hewlett-Packard                 | 1         | 1.85%   |
| Broadcom                        | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 18.52%  |
| Realtek Bluetooth Radio                             | 9         | 16.67%  |
| Intel Bluetooth Device                              | 6         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 7.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.56%   |
| Intel AX200 Bluetooth                               | 3         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.7%    |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 2         | 3.7%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.85%   |
| Intel AX210 Bluetooth                               | 1         | 1.85%   |
| IMC Networks Bluetooth Device                       | 1         | 1.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.85%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.85%   |
| Dell BT Mini-Receiver                               | 1         | 1.85%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.85%   |
| Apple Bluetooth HCI                                 | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 56.35%  |
| AMD                   | 27        | 21.43%  |
| Nvidia                | 20        | 15.87%  |
| Texas Instruments     | 2         | 1.59%   |
| C-Media Electronics   | 2         | 1.59%   |
| Yamaha                | 1         | 0.79%   |
| Realtek Semiconductor | 1         | 0.79%   |
| GN Netcom             | 1         | 0.79%   |
| Audioengine           | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 8.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 5.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 5.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.49%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 3.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.56%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.56%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 1.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.92%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.28%   |
| Nvidia Audio device                                                        | 2         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.28%   |
| AMD High Definition Audio Controller                                       | 2         | 1.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.28%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.64%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.64%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 0.64%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.64%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.64%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 0.64%   |
| Intel Audio device                                                         | 1         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.64%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 0.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.64%   |
| GN Netcom Jabra EVOLVE 20 MS                                               | 1         | 0.64%   |
| C-Media Electronics REIYIN Audio                                           | 1         | 0.64%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 0.64%   |
| Audioengine D1 24-bit DAC                                                  | 1         | 0.64%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.64%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 11        | 28.95%  |
| SK hynix                     | 8         | 21.05%  |
| Unknown                      | 4         | 10.53%  |
| Micron Technology            | 3         | 7.89%   |
| A-DATA Technology            | 3         | 7.89%   |
| Nanya Technology             | 2         | 5.26%   |
| Corsair                      | 2         | 5.26%   |
| Unknown (ABCD)               | 1         | 2.63%   |
| Patriot Memory (PDP Systems) | 1         | 2.63%   |
| Kingston                     | 1         | 2.63%   |
| G.Skill                      | 1         | 2.63%   |
| Crucial                      | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 4.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s              | 2         | 4.88%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                              | 1         | 2.44%   |
| Unknown RAM Module 512MB SODIMM DDR                                      | 1         | 2.44%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 2.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                     | 1         | 2.44%   |
| Unknown RAM Module 1GB SODIMM DDR                                        | 1         | 2.44%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s      | 1         | 2.44%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                            | 1         | 2.44%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                             | 1         | 2.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s                | 1         | 2.44%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 2.44%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.44%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 2.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                    | 1         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s              | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s                 | 1         | 2.44%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s                     | 1         | 2.44%   |
| Patriot Memory (PDP Systems) RAM PSD432G32002S 32GB SODIMM DDR4 3200MT/s | 1         | 2.44%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2048MB SODIMM DDR2 2048MT/s                  | 1         | 2.44%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s                        | 1         | 2.44%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s                      | 1         | 2.44%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s                      | 1         | 2.44%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s                    | 1         | 2.44%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s                | 1         | 2.44%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                               | 1         | 2.44%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                              | 1         | 2.44%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s                  | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 48.65%  |
| DDR3    | 12        | 32.43%  |
| SDRAM   | 3         | 8.11%   |
| LPDDR4  | 2         | 5.41%   |
| DDR     | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 71.05%  |
| DIMM         | 8         | 21.05%  |
| Row Of Chips | 3         | 7.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 15        | 37.5%   |
| 4096  | 9         | 22.5%   |
| 2048  | 7         | 17.5%   |
| 32768 | 3         | 7.5%    |
| 16384 | 3         | 7.5%    |
| 1024  | 2         | 5%      |
| 512   | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 12        | 32.43%  |
| 1600    | 11        | 29.73%  |
| 2400    | 3         | 8.11%   |
| 2667    | 2         | 5.41%   |
| 4267    | 1         | 2.7%    |
| 4199    | 1         | 2.7%    |
| 3400    | 1         | 2.7%    |
| 2048    | 1         | 2.7%    |
| 1866    | 1         | 2.7%    |
| 1333    | 1         | 2.7%    |
| 1200    | 1         | 2.7%    |
| 667     | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Konica Minolta     | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Konica Minolta 185    | 1         | 33.33%  |
| HP OfficeJet Pro 8730 | 1         | 33.33%  |
| Brother MFC-L2685DW   | 1         | 33.33%  |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Microdia                               | 10        | 15.38%  |
| Chicony Electronics                    | 10        | 15.38%  |
| Suyin                                  | 6         | 9.23%   |
| IMC Networks                           | 6         | 9.23%   |
| Sunplus Innovation Technology          | 5         | 7.69%   |
| Realtek Semiconductor                  | 4         | 6.15%   |
| Quanta                                 | 4         | 6.15%   |
| Acer                                   | 3         | 4.62%   |
| Luxvisions Innotech Limited            | 2         | 3.08%   |
| Logitech                               | 2         | 3.08%   |
| Unknown                                | 1         | 1.54%   |
| Syntek                                 | 1         | 1.54%   |
| OmniVision Technologies                | 1         | 1.54%   |
| MacroSilicon                           | 1         | 1.54%   |
| Lite-On Technology                     | 1         | 1.54%   |
| Intel                                  | 1         | 1.54%   |
| icSpring                               | 1         | 1.54%   |
| Creative Technology                    | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.54%   |
| ARC International                      | 1         | 1.54%   |
| Apple                                  | 1         | 1.54%   |
| ALi                                    | 1         | 1.54%   |
| Alcor Micro                            | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 8         | 12.31%  |
| Suyin HP TrueVision HD                               | 2         | 3.08%   |
| Quanta HP TrueVision HD Camera                       | 2         | 3.08%   |
| IMC Networks Integrated Camera                       | 2         | 3.08%   |
| Chicony Integrated Camera                            | 2         | 3.08%   |
| Chicony HP Truevision HD camera                      | 2         | 3.08%   |
| Chicony HD Webcam                                    | 2         | 3.08%   |
| Acer Integrated Camera                               | 2         | 3.08%   |
| Unknown 720p HD Camera                               | 1         | 1.54%   |
| Syntek Integrated Camera                             | 1         | 1.54%   |
| Suyin HD WebCam                                      | 1         | 1.54%   |
| Suyin Acer HD Crystal Eye webcam                     | 1         | 1.54%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.54%   |
| Suyin 1.3M HD WebCam                                 | 1         | 1.54%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 1.54%   |
| Sunplus HP TrueVision HD Camera                      | 1         | 1.54%   |
| Sunplus HD WebCam                                    | 1         | 1.54%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 1.54%   |
| Sunplus 1.3M HD WebCam                               | 1         | 1.54%   |
| Realtek USB2.0 camera                                | 1         | 1.54%   |
| Realtek HP Truevision HD integrated webcam           | 1         | 1.54%   |
| Realtek HP Truevision HD                             | 1         | 1.54%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 1.54%   |
| Quanta HP Webcam                                     | 1         | 1.54%   |
| Quanta HP HD Camera                                  | 1         | 1.54%   |
| OmniVision Integrated Webcam for Dell XPS 2010       | 1         | 1.54%   |
| Microdia Lenovo EasyCamera                           | 1         | 1.54%   |
| Microdia Integrated Webcam HD                        | 1         | 1.54%   |
| MacroSilicon MiraBox Capture                         | 1         | 1.54%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.54%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.54%   |
| Logitech Webcam C925e                                | 1         | 1.54%   |
| Logitech Webcam C210                                 | 1         | 1.54%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.54%   |
| Intel RealSense 3D Camera (Front F200)               | 1         | 1.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 1         | 1.54%   |
| IMC Networks Integrated Webcam                       | 1         | 1.54%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 1.54%   |
| icSpring camera                                      | 1         | 1.54%   |
| Creative Live! Cam Sync HD [VF0770]                  | 1         | 1.54%   |
| Chicony Integrated HP HD Webcam                      | 1         | 1.54%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.54%   |
| Chicony CKA7216                                      | 1         | 1.54%   |
| Chicony 1.3M Webcam                                  | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 1.54%   |
| ARC International Camera                             | 1         | 1.54%   |
| Apple iPhone 5/5C/5S/6/SE                            | 1         | 1.54%   |
| ALi Gateway Webcam                                   | 1         | 1.54%   |
| Alcor Micro USB 2.0 Camera                           | 1         | 1.54%   |
| Acer USB2.0 Camera                                   | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 67        | 68.37%  |
| 1     | 27        | 27.55%  |
| 2     | 4         | 4.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 30.56%  |
| Multimedia controller | 7         | 19.44%  |
| Fingerprint reader    | 7         | 19.44%  |
| Chipcard              | 5         | 13.89%  |
| Graphics card         | 4         | 11.11%  |
| Dvb card              | 1         | 2.78%   |
| Camera                | 1         | 2.78%   |

