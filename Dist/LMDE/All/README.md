LMDE - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for LMDE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

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

Total: 792

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [aca8d98967](https://linux-hardware.org/?probe=aca8d98967) | Jul 18, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Framework     | Laptop                      | Notebook    | [80ad33bb18](https://linux-hardware.org/?probe=80ad33bb18) | Jul 16, 2022 |
| Framework     | Laptop                      | Notebook    | [439e4aafa7](https://linux-hardware.org/?probe=439e4aafa7) | Jul 16, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
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
| ASUSTek       | P5QL PRO                    | Desktop     | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
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
| Dell          | 0XR1GT A00                  | Desktop     | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Acer          | AOD270                      | Notebook    | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
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
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
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
| ASUSTek       | 901                         | Notebook    | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Acer          | EG43M                       | Desktop     | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | Notebook    | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| ASUSTek       | P4P800                      | Desktop     | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Acer          | TravelMate 420              | Notebook    | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | Notebook    | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | Notebook    | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | Notebook    | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| Dell          | 0Y2K8N A01                  | Desktop     | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
| ASUSTek       | 901                         | Notebook    | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [311d594372](https://linux-hardware.org/?probe=311d594372) | Jan 13, 2022 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [4fac8e2cb1](https://linux-hardware.org/?probe=4fac8e2cb1) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [ea55ac1aab](https://linux-hardware.org/?probe=ea55ac1aab) | Jan 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [33457cde11](https://linux-hardware.org/?probe=33457cde11) | Jan 09, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | Notebook    | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| Unknown       | K7VM2                       | Desktop     | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | Desktop     | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| Wistron       | ProLiant ML110 G5           | Server      | [8526295a2f](https://linux-hardware.org/?probe=8526295a2f) | Dec 27, 2021 |
| Advent        | Monza T100                  | Notebook    | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | Notebook    | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | Notebook    | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | Desktop     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | Notebook    | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Acer          | RS880M05                    | Desktop     | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | Desktop     | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| Samsung       | 305U1A                      | Notebook    | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Intel         | H61                         | Desktop     | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| HP            | 843C                        | Desktop     | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | Notebook    | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| HUAWEI        | MateBook HZ-W19             | Tablet      | [904decfd32](https://linux-hardware.org/?probe=904decfd32) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Biostar       | G41D3C                      | Desktop     | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | Notebook    | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | Notebook    | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| ASUSTek       | UN62                        | Desktop     | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | Notebook    | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | Notebook    | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | Notebook    | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | Notebook    | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | Notebook    | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| ASUSTek       | M51Sn                       | Notebook    | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | Notebook    | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| HP            | 0AA8h                       | Desktop     | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | Desktop     | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Intel         | BTC-T37                     | Desktop     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | Desktop     | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| Dell          | XPS M1330                   | Notebook    | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | Notebook    | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | Notebook    | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | Notebook    | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| MSI           | H81M-E34                    | Desktop     | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| Samsung       | R59/R60/R61                 | Notebook    | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | Notebook    | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | Notebook    | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | 0A98h                       | Desktop     | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | 0AA8h                       | Desktop     | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | 0AA8h                       | Desktop     | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | Notebook    | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | Notebook    | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | Desktop     | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| ASUSTek       | X555UJ                      | Notebook    | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | Desktop     | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | Desktop     | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| HP            | 530                         | Notebook    | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | Notebook    | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | Notebook    | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | Notebook    | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | Notebook    | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | Desktop     | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | Desktop     | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | Desktop     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Supermicro    | X8DT3                       | Server      | [f645c4227c](https://linux-hardware.org/?probe=f645c4227c) | Apr 02, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | Notebook    | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | Notebook    | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | Notebook    | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| Intel         | H61                         | Desktop     | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| HP            | Unknown                     | Notebook    | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | Desktop     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | Notebook    | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | Notebook    | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Acer          | EG43LMK                     | Desktop     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | Notebook    | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | Notebook    | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Acer          | EG43LMK                     | Desktop     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| Google        | Gnawty                      | Notebook    | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| MSI           | MS-7267                     | Desktop     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | Desktop     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| Notebook      | WID2010                     | Notebook    | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | Notebook    | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | Notebook    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Alienware     | 06G6JW A00                  | Desktop     | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | Notebook    | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | Desktop     | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | Desktop     | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| Exper         | E10IL1                      | Notebook    | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| MSI           | MS-6570                     | Desktop     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| Dell          | Precision M4800             | Notebook    | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | Notebook    | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | Notebook    | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | Gardenia CRB                | All in one  | [53b3108cb8](https://linux-hardware.org/?probe=53b3108cb8) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [862b159eb2](https://linux-hardware.org/?probe=862b159eb2) | Dec 19, 2020 |
| Toshiba       | STI 910123                  | Desktop     | [f9f7a69232](https://linux-hardware.org/?probe=f9f7a69232) | Dec 18, 2020 |
| Toshiba       | STI 910123                  | Desktop     | [ae79e069f3](https://linux-hardware.org/?probe=ae79e069f3) | Dec 18, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [fdc26c9f6d](https://linux-hardware.org/?probe=fdc26c9f6d) | Dec 18, 2020 |
| Exo           | Unknown                     | Notebook    | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| ASUSTek       | P8B75-V                     | Desktop     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | Notebook    | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [5b78a6b7ee](https://linux-hardware.org/?probe=5b78a6b7ee) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | Desktop     | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | Notebook    | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | Notebook    | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | Notebook    | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| HP            | 1496                        | Desktop     | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Acer          | Extensa 4620                | Notebook    | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [a229c68d0e](https://linux-hardware.org/?probe=a229c68d0e) | Nov 27, 2020 |
| Gigabyte      | 945GM-S2                    | Desktop     | [1bbf0f874b](https://linux-hardware.org/?probe=1bbf0f874b) | Nov 26, 2020 |
| MSI           | B85M-G43                    | Desktop     | [dee4fcacb7](https://linux-hardware.org/?probe=dee4fcacb7) | Nov 26, 2020 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | Notebook    | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | Notebook    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | Notebook    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [c03bf04e1e](https://linux-hardware.org/?probe=c03bf04e1e) | Nov 15, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | Notebook    | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | Notebook    | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | Notebook    | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | Notebook    | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | Notebook    | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | Latitude E6220              | Notebook    | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | Notebook    | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | Desktop     | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| Positivo      | DH8BW01                     | All in one  | [b8c805b52b](https://linux-hardware.org/?probe=b8c805b52b) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Gigabyte      | G33M-S2                     | Desktop     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | Desktop     | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | Notebook    | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 304Ah                       | Desktop     | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| HP            | 304Ah                       | Desktop     | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [8ebb392ed7](https://linux-hardware.org/?probe=8ebb392ed7) | Oct 03, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [825a44fd4e](https://linux-hardware.org/?probe=825a44fd4e) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| HP            | 304Ah                       | Desktop     | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| Positivo      | H14CU01                     | Notebook    | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | Notebook    | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | Notebook    | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [b200995d98](https://linux-hardware.org/?probe=b200995d98) | Sep 08, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [afcf5f7b56](https://linux-hardware.org/?probe=afcf5f7b56) | Sep 08, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [e5260021d2](https://linux-hardware.org/?probe=e5260021d2) | Sep 06, 2020 |
| MSI           | FX610                       | Notebook    | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [4b3e5c5cf9](https://linux-hardware.org/?probe=4b3e5c5cf9) | Sep 03, 2020 |
| Dell          | 0DR845                      | Desktop     | [f9dfefaf63](https://linux-hardware.org/?probe=f9dfefaf63) | Aug 31, 2020 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | Notebook    | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | Notebook    | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| ECS           | KAM1-I                      | Desktop     | [cef51c9cd7](https://linux-hardware.org/?probe=cef51c9cd7) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| MSI           | D2414 S26361-D2414-A10      | Desktop     | [a0ea23eae8](https://linux-hardware.org/?probe=a0ea23eae8) | Aug 10, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [e632211d18](https://linux-hardware.org/?probe=e632211d18) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Intel         | DG33FB AAD81072-309         | Desktop     | [217bfd48bd](https://linux-hardware.org/?probe=217bfd48bd) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [a70d949ebc](https://linux-hardware.org/?probe=a70d949ebc) | Jul 30, 2020 |
| Lenovo        | ThinkCentre M90z 2471W18    | All in one  | [03b15c1544](https://linux-hardware.org/?probe=03b15c1544) | Jul 21, 2020 |
| Positivo      | W310CZ-T                    | Notebook    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | Notebook    | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [4af42f19bb](https://linux-hardware.org/?probe=4af42f19bb) | Jul 14, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | Notebook    | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | 3396                        | Desktop     | [53167bce1a](https://linux-hardware.org/?probe=53167bce1a) | Jul 09, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | Notebook    | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| ASUSTek       | G11DF                       | Desktop     | [73ddfc32aa](https://linux-hardware.org/?probe=73ddfc32aa) | Jun 23, 2020 |
| ASUSTek       | G11DF                       | Desktop     | [497ebd9b60](https://linux-hardware.org/?probe=497ebd9b60) | Jun 23, 2020 |
| Toshiba       | All In One PC MP            | All in one  | [b2175e7054](https://linux-hardware.org/?probe=b2175e7054) | Jun 21, 2020 |
| Biostar       | NF61S-M2A                   | Desktop     | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc82478114](https://linux-hardware.org/?probe=dc82478114) | Jun 21, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a2c192906d](https://linux-hardware.org/?probe=a2c192906d) | Jun 21, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | Notebook    | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | Notebook    | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | Notebook    | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| PCWare        | IPMH81G1                    | Desktop     | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Toshiba       | All In One PC MP            | All in one  | [7a08b12375](https://linux-hardware.org/?probe=7a08b12375) | Jun 04, 2020 |
| ASUSTek       | 1005PX                      | Notebook    | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Sony          | VGN-AW41MF_H                | Notebook    | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | 8430 1000                   | All in one  | [c05bc25888](https://linux-hardware.org/?probe=c05bc25888) | May 29, 2020 |
| HP            | 8430 1000                   | All in one  | [f7df6a95b7](https://linux-hardware.org/?probe=f7df6a95b7) | May 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | Notebook    | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Acer          | Aspire 4830T                | Notebook    | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | Notebook    | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | Notebook    | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| ASRock        | B75M R2.0                   | Desktop     | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Dell          | Latitude E5570              | Notebook    | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | Notebook    | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | Notebook    | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | Notebook    | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | Notebook    | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | Notebook    | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| ASRock        | J4205-ITX                   | Desktop     | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | Desktop     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | Notebook    | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | Notebook    | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [3cc8e9e496](https://linux-hardware.org/?probe=3cc8e9e496) | Apr 12, 2020 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [8822c3378d](https://linux-hardware.org/?probe=8822c3378d) | Apr 12, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| HP            | 8526 MVB, A                 | Desktop     | [30e90998e1](https://linux-hardware.org/?probe=30e90998e1) | Apr 08, 2020 |
| Dell          | Latitude E6510              | Notebook    | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | Notebook    | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | Notebook    | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [5c90c49af6](https://linux-hardware.org/?probe=5c90c49af6) | Mar 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [e710551f70](https://linux-hardware.org/?probe=e710551f70) | Mar 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [336b94c4dc](https://linux-hardware.org/?probe=336b94c4dc) | Mar 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b660991573](https://linux-hardware.org/?probe=b660991573) | Mar 29, 2020 |
| MSI           | G31M2                       | Desktop     | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| Acer          | Aspire TC-605               | Desktop     | [495fffaa63](https://linux-hardware.org/?probe=495fffaa63) | Mar 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [fb006f397c](https://linux-hardware.org/?probe=fb006f397c) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | Desktop     | [5c7e0a86df](https://linux-hardware.org/?probe=5c7e0a86df) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | Desktop     | [c6a5cf98ee](https://linux-hardware.org/?probe=c6a5cf98ee) | Mar 24, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [0c52aebe31](https://linux-hardware.org/?probe=0c52aebe31) | Mar 23, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [b2c3317256](https://linux-hardware.org/?probe=b2c3317256) | Mar 19, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [2cd8614e59](https://linux-hardware.org/?probe=2cd8614e59) | Mar 17, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [fcb4ff46b5](https://linux-hardware.org/?probe=fcb4ff46b5) | Mar 17, 2020 |
| Intel         | D34010WYK H14771-303        | Desktop     | [0c19bbe87a](https://linux-hardware.org/?probe=0c19bbe87a) | Feb 18, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [7dbce6b0fc](https://linux-hardware.org/?probe=7dbce6b0fc) | Jan 15, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [11b0d93285](https://linux-hardware.org/?probe=11b0d93285) | Jan 15, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [363851a935](https://linux-hardware.org/?probe=363851a935) | Dec 19, 2019 |
| HP            | ProLiant MicroServer        | Desktop     | [708dff507f](https://linux-hardware.org/?probe=708dff507f) | Dec 19, 2019 |
| Dell          | Inspiron 3593               | Notebook    | [9f8af004d3](https://linux-hardware.org/?probe=9f8af004d3) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | Notebook    | [7f4ce08df9](https://linux-hardware.org/?probe=7f4ce08df9) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | Notebook    | [a6ee735c5f](https://linux-hardware.org/?probe=a6ee735c5f) | Nov 29, 2019 |
| Dell          | OptiPlex GX620              | Desktop     | [21f221a304](https://linux-hardware.org/?probe=21f221a304) | May 17, 2019 |
| Dell          | OptiPlex GX620              | Desktop     | [3e9258a7c5](https://linux-hardware.org/?probe=3e9258a7c5) | Apr 15, 2019 |
| Dell          | OptiPlex GX620              | Desktop     | [87babb0fa3](https://linux-hardware.org/?probe=87babb0fa3) | Apr 15, 2019 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [d950de89e7](https://linux-hardware.org/?probe=d950de89e7) | Mar 26, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [9be63e6a28](https://linux-hardware.org/?probe=9be63e6a28) | Jan 09, 2019 |
| HP            | Pavilion dv7                | Notebook    | [4480bf8ff3](https://linux-hardware.org/?probe=4480bf8ff3) | Dec 24, 2018 |
| Acer          | Aspire V3-571               | Notebook    | [bb8f83433e](https://linux-hardware.org/?probe=bb8f83433e) | Nov 27, 2018 |
| Acer          | Aspire V3-571               | Notebook    | [1136588271](https://linux-hardware.org/?probe=1136588271) | Nov 27, 2018 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [d425ca175b](https://linux-hardware.org/?probe=d425ca175b) | Oct 11, 2018 |
| HP            | ProBook 4510s               | Notebook    | [dbc607e890](https://linux-hardware.org/?probe=dbc607e890) | Sep 08, 2018 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [693096a808](https://linux-hardware.org/?probe=693096a808) | Sep 06, 2018 |
| ASUSTek       | P8Z77-V                     | Desktop     | [bcdb9633d9](https://linux-hardware.org/?probe=bcdb9633d9) | Sep 05, 2018 |
| Dell          | Inspiron 11-3162            | Notebook    | [92dcc778ac](https://linux-hardware.org/?probe=92dcc778ac) | Mar 19, 2018 |
| Sony          | VPCEB1M1R                   | Notebook    | [25b5c0689e](https://linux-hardware.org/?probe=25b5c0689e) | Mar 16, 2018 |
| Foxconn       | 945 7MA Series              | Desktop     | [95d9e1dba9](https://linux-hardware.org/?probe=95d9e1dba9) | Nov 14, 2017 |
| ASUSTek       | H61M-K                      | Desktop     | [78a1c15c22](https://linux-hardware.org/?probe=78a1c15c22) | Sep 09, 2017 |
| Sony          | VPCSB3M1R                   | Notebook    | [155309a9eb](https://linux-hardware.org/?probe=155309a9eb) | Aug 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 4 | 384       | 73.7%   |
| LMDE 5 | 118       | 22.65%  |
| LMDE 3 | 14        | 2.69%   |
| LMDE 2 | 5         | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 519       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 4.19.0-8-amd64       | 45        | 7.92%   |
| 4.19.0-18-amd64      | 45        | 7.92%   |
| 4.19.0-17-amd64      | 40        | 7.04%   |
| 4.19.0-16-amd64      | 40        | 7.04%   |
| 4.19.0-14-amd64      | 31        | 5.46%   |
| 4.19.0-13-amd64      | 30        | 5.28%   |
| 5.10.0-14-amd64      | 29        | 5.11%   |
| 4.19.0-9-amd64       | 29        | 5.11%   |
| 5.10.0-13-amd64      | 27        | 4.75%   |
| 5.10.0-12-amd64      | 22        | 3.87%   |
| 4.19.0-10-amd64      | 20        | 3.52%   |
| 4.19.0-12-amd64      | 19        | 3.35%   |
| 5.10.0-15-amd64      | 18        | 3.17%   |
| 4.19.0-8-686         | 17        | 2.99%   |
| 4.19.0-17-686        | 17        | 2.99%   |
| 4.19.0-16-686        | 14        | 2.46%   |
| 4.19.0-18-686        | 12        | 2.11%   |
| 5.10.0-16-amd64      | 11        | 1.94%   |
| 4.19.0-11-amd64      | 11        | 1.94%   |
| 4.19.0-13-686        | 9         | 1.58%   |
| 4.9.0-8-amd64        | 8         | 1.41%   |
| 5.10.0-13-686        | 6         | 1.06%   |
| 4.19.0-14-686        | 6         | 1.06%   |
| 4.19.0-12-686        | 6         | 1.06%   |
| 4.19.0-19-686        | 5         | 0.88%   |
| 3.16.0-4-amd64       | 4         | 0.7%    |
| 5.4.0-0.bpo.4-amd64  | 3         | 0.53%   |
| 5.18.0-0.bpo.1-amd64 | 3         | 0.53%   |
| 5.16.0-0.bpo.4-amd64 | 3         | 0.53%   |
| 4.19.0-20-amd64      | 3         | 0.53%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.35%   |
| 4.9.0-11-amd64       | 2         | 0.35%   |
| 4.19.0-9-686         | 2         | 0.35%   |
| 5.9.12-davius        | 1         | 0.18%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.18%   |
| 5.8.0-3-amd64        | 1         | 0.18%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.18%   |
| 5.6.0-2-amd64        | 1         | 0.18%   |
| 5.6.0-2-686-pae      | 1         | 0.18%   |
| 5.6.0-0.bpo.2-amd64  | 1         | 0.18%   |
| 5.4.44-xanmod1       | 1         | 0.18%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.18%   |
| 5.15.56-xanmod1      | 1         | 0.18%   |
| 5.15.0-kali2-amd64   | 1         | 0.18%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.18%   |
| 5.10.0-7-amd64       | 1         | 0.18%   |
| 5.10.0-14-686        | 1         | 0.18%   |
| 5.10.0-11-686        | 1         | 0.18%   |
| 5.10.0-0.bpo.9-amd64 | 1         | 0.18%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.18%   |
| 4.9.0-9-amd64        | 1         | 0.18%   |
| 4.9.0-17-amd64       | 1         | 0.18%   |
| 4.9.0-14-amd64       | 1         | 0.18%   |
| 4.19.0-21-amd64      | 1         | 0.18%   |
| 4.19.0-20-686        | 1         | 0.18%   |
| 4.19.0-19-amd64      | 1         | 0.18%   |
| 4.19.0-14-686-pae    | 1         | 0.18%   |
| 4.19.0-12-rt-amd64   | 1         | 0.18%   |
| 4.19.0-10-686        | 1         | 0.18%   |
| 4.19.0-0.bpo.8-amd64 | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 369       | 70.55%  |
| 5.10.0  | 116       | 22.18%  |
| 4.9.0   | 12        | 2.29%   |
| 3.16.0  | 5         | 0.96%   |
| 5.6.0   | 3         | 0.57%   |
| 5.4.0   | 3         | 0.57%   |
| 5.18.0  | 3         | 0.57%   |
| 5.16.0  | 3         | 0.57%   |
| 5.8.0   | 2         | 0.38%   |
| 5.15.0  | 2         | 0.38%   |
| 5.9.12  | 1         | 0.19%   |
| 5.9.0   | 1         | 0.19%   |
| 5.4.44  | 1         | 0.19%   |
| 5.15.56 | 1         | 0.19%   |
| 4.17.0  | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 369       | 70.55%  |
| 5.10    | 116       | 22.18%  |
| 4.9     | 12        | 2.29%   |
| 3.16    | 5         | 0.96%   |
| 5.4     | 4         | 0.76%   |
| 5.6     | 3         | 0.57%   |
| 5.18    | 3         | 0.57%   |
| 5.16    | 3         | 0.57%   |
| 5.15    | 3         | 0.57%   |
| 5.9     | 2         | 0.38%   |
| 5.8     | 2         | 0.38%   |
| 4.17    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 423       | 81.5%   |
| i686   | 96        | 18.5%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 458       | 87.24%  |
| Cinnamon   | 37        | 7.05%   |
| MATE       | 11        | 2.1%    |
| Unknown    | 9         | 1.71%   |
| XFCE       | 3         | 0.57%   |
| LXDE       | 2         | 0.38%   |
| GNOME      | 2         | 0.38%   |
| Trinity    | 1         | 0.19%   |
| LXQt       | 1         | 0.19%   |
| KDE        | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 519       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 415       | 79.65%  |
| LightDM | 67        | 12.86%  |
| TDM     | 32        | 6.14%   |
| MDM     | 5         | 0.96%   |
| GDM3    | 1         | 0.19%   |
| GDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 158       | 30.33%  |
| de_DE   | 51        | 9.79%   |
| pt_BR   | 49        | 9.4%    |
| ru_RU   | 29        | 5.57%   |
| en_GB   | 24        | 4.61%   |
| fr_FR   | 22        | 4.22%   |
| pl_PL   | 18        | 3.45%   |
| Unknown | 17        | 3.26%   |
| it_IT   | 13        | 2.5%    |
| es_ES   | 13        | 2.5%    |
| en_CA   | 11        | 2.11%   |
| en_AU   | 10        | 1.92%   |
| es_MX   | 9         | 1.73%   |
| es_AR   | 9         | 1.73%   |
| de_CH   | 5         | 0.96%   |
| pt_PT   | 4         | 0.77%   |
| nl_BE   | 4         | 0.77%   |
| el_GR   | 4         | 0.77%   |
| sv_SE   | 3         | 0.58%   |
| nl_NL   | 3         | 0.58%   |
| ja_JP   | 3         | 0.58%   |
| hu_HU   | 3         | 0.58%   |
| fr_CA   | 3         | 0.58%   |
| en_ZA   | 3         | 0.58%   |
| de_AT   | 3         | 0.58%   |
| cs_CZ   | 3         | 0.58%   |
| bg_BG   | 3         | 0.58%   |
| unm_US  | 2         | 0.38%   |
| uk_UA   | 2         | 0.38%   |
| tr_TR   | 2         | 0.38%   |
| sk_SK   | 2         | 0.38%   |
| fr_BE   | 2         | 0.38%   |
| et_EE   | 2         | 0.38%   |
| es_EC   | 2         | 0.38%   |
| es_CL   | 2         | 0.38%   |
| es_BO   | 2         | 0.38%   |
| en_PH   | 2         | 0.38%   |
| en_IN   | 2         | 0.38%   |
| en_IE   | 2         | 0.38%   |
| ca_ES   | 2         | 0.38%   |
| ar_EG   | 2         | 0.38%   |
| zh_CN   | 1         | 0.19%   |
| ru_UA   | 1         | 0.19%   |
| ro_RO   | 1         | 0.19%   |
| nl_AW   | 1         | 0.19%   |
| nb_NO   | 1         | 0.19%   |
| ko_KR   | 1         | 0.19%   |
| it_CH   | 1         | 0.19%   |
| hr_HR   | 1         | 0.19%   |
| fi_FI   | 1         | 0.19%   |
| es_UY   | 1         | 0.19%   |
| es_PE   | 1         | 0.19%   |
| es_NI   | 1         | 0.19%   |
| es_CO   | 1         | 0.19%   |
| en_SG   | 1         | 0.19%   |
| en_NZ   | 1         | 0.19%   |
| da_DK   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 334       | 64.11%  |
| EFI  | 187       | 35.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 487       | 93.65%  |
| Btrfs   | 10        | 1.92%   |
| Unknown | 8         | 1.54%   |
| Tmpfs   | 6         | 1.15%   |
| Overlay | 6         | 1.15%   |
| Xfs     | 1         | 0.19%   |
| Ext3    | 1         | 0.19%   |
| Aufs    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 410       | 78.69%  |
| GPT     | 71        | 13.63%  |
| MBR     | 40        | 7.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 489       | 93.86%  |
| Yes       | 32        | 6.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 481       | 92.68%  |
| Yes       | 38        | 7.32%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 90        | 17.34%  |
| ASUSTek Computer               | 76        | 14.64%  |
| Dell                           | 63        | 12.14%  |
| Lenovo                         | 48        | 9.25%   |
| Acer                           | 46        | 8.86%   |
| MSI                            | 26        | 5.01%   |
| Gigabyte Technology            | 26        | 5.01%   |
| ASRock                         | 14        | 2.7%    |
| Toshiba                        | 12        | 2.31%   |
| Sony                           | 9         | 1.73%   |
| Intel                          | 9         | 1.73%   |
| Samsung Electronics            | 8         | 1.54%   |
| Apple                          | 8         | 1.54%   |
| Unknown                        | 8         | 1.54%   |
| Fujitsu Siemens                | 6         | 1.16%   |
| Positivo                       | 5         | 0.96%   |
| LG Electronics                 | 4         | 0.77%   |
| ECS                            | 4         | 0.77%   |
| Packard Bell                   | 3         | 0.58%   |
| Foxconn                        | 3         | 0.58%   |
| Semp Toshiba                   | 2         | 0.39%   |
| Pegatron                       | 2         | 0.39%   |
| OEM                            | 2         | 0.39%   |
| Medion                         | 2         | 0.39%   |
| Matsushita Electric Industrial | 2         | 0.39%   |
| Google                         | 2         | 0.39%   |
| Gateway                        | 2         | 0.39%   |
| Fujitsu                        | 2         | 0.39%   |
| EVGA                           | 2         | 0.39%   |
| Biostar                        | 2         | 0.39%   |
| Alienware                      | 2         | 0.39%   |
| Wistron                        | 1         | 0.19%   |
| TUXEDO                         | 1         | 0.19%   |
| Supermicro                     | 1         | 0.19%   |
| SAELITE                        | 1         | 0.19%   |
| Qbex                           | 1         | 0.19%   |
| Philco                         | 1         | 0.19%   |
| PCWare                         | 1         | 0.19%   |
| Panasonic                      | 1         | 0.19%   |
| Notebook                       | 1         | 0.19%   |
| NEC Computers                  | 1         | 0.19%   |
| Multilaser                     | 1         | 0.19%   |
| Microtech                      | 1         | 0.19%   |
| Microsoft                      | 1         | 0.19%   |
| Maibenben                      | 1         | 0.19%   |
| LincPlus                       | 1         | 0.19%   |
| Itautec                        | 1         | 0.19%   |
| IBM                            | 1         | 0.19%   |
| HUAWEI                         | 1         | 0.19%   |
| Howard Computers               | 1         | 0.19%   |
| Framework                      | 1         | 0.19%   |
| Exper                          | 1         | 0.19%   |
| Exo                            | 1         | 0.19%   |
| EVOO                           | 1         | 0.19%   |
| eMachines                      | 1         | 0.19%   |
| Dixonsxp                       | 1         | 0.19%   |
| Digma                          | 1         | 0.19%   |
| DFI                            | 1         | 0.19%   |
| AMI                            | 1         | 0.19%   |
| Advent                         | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 14        | 2.7%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.58%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 3         | 0.58%   |
| Dell Latitude E6400                         | 3         | 0.58%   |
| Acer AOD270                                 | 3         | 0.58%   |
| HP Pavilion dv7                             | 2         | 0.39%   |
| HP Pavilion dv6                             | 2         | 0.39%   |
| HP Pavilion Desktop 590-p0xxx               | 2         | 0.39%   |
| HP Notebook                                 | 2         | 0.39%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.39%   |
| HP Laptop 15-bw0xx                          | 2         | 0.39%   |
| HP Laptop 14-df0xxx                         | 2         | 0.39%   |
| HP EliteBook 8540w                          | 2         | 0.39%   |
| HP 255 G7 Notebook PC                       | 2         | 0.39%   |
| HP 14                                       | 2         | 0.39%   |
| Dell OptiPlex 780                           | 2         | 0.39%   |
| Dell Inspiron 5566                          | 2         | 0.39%   |
| Dell Inspiron 5559                          | 2         | 0.39%   |
| ASUS X101CH                                 | 2         | 0.39%   |
| ASUS All Series                             | 2         | 0.39%   |
| Acer Aspire 5930                            | 2         | 0.39%   |
| Acer Aspire 5735                            | 2         | 0.39%   |
| Acer Aspire 3000                            | 2         | 0.39%   |
| Wistron ProLiant ML110 G5                   | 1         | 0.19%   |
| TUXEDO BC1510 1710                          | 1         | 0.19%   |
| Toshiba Satellite U300                      | 1         | 0.19%   |
| Toshiba Satellite P300                      | 1         | 0.19%   |
| Toshiba Satellite M55                       | 1         | 0.19%   |
| Toshiba Satellite M100                      | 1         | 0.19%   |
| Toshiba Satellite L855                      | 1         | 0.19%   |
| Toshiba Satellite L750                      | 1         | 0.19%   |
| Toshiba Satellite L50-C                     | 1         | 0.19%   |
| Toshiba Satellite L455                      | 1         | 0.19%   |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.19%   |
| Toshiba Satellite A200                      | 1         | 0.19%   |
| Toshiba LX835                               | 1         | 0.19%   |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.19%   |
| Supermicro X8DT3                            | 1         | 0.19%   |
| Sony VPCSB3M1R                              | 1         | 0.19%   |
| Sony VPCS131FM                              | 1         | 0.19%   |
| Sony VPCP116KG                              | 1         | 0.19%   |
| Sony VPCEB1M1R                              | 1         | 0.19%   |
| Sony VGN-FZ140E                             | 1         | 0.19%   |
| Sony VGN-AW41MF_H                           | 1         | 0.19%   |
| Sony SVE1713Y1RB                            | 1         | 0.19%   |
| Sony SVE1512G1RW                            | 1         | 0.19%   |
| Sony SVE1511N1ESI                           | 1         | 0.19%   |
| Semp Toshiba STI                            | 1         | 0.19%   |
| Semp Toshiba NI 1403                        | 1         | 0.19%   |
| Samsung RV413/RV513                         | 1         | 0.19%   |
| Samsung R59/R60/R61                         | 1         | 0.19%   |
| Samsung NC10                                | 1         | 0.19%   |
| Samsung 730QDA                              | 1         | 0.19%   |
| Samsung 305U1A                              | 1         | 0.19%   |
| SAELITE ES1AU11                             | 1         | 0.19%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.19%   |
| Positivo W310CZ-T                           | 1         | 0.19%   |
| Positivo POS-EIH61CE                        | 1         | 0.19%   |
| Positivo Mobile                             | 1         | 0.19%   |
| Positivo H14CU01                            | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 35        | 6.74%   |
| Dell Inspiron           | 19        | 3.66%   |
| Lenovo ThinkPad         | 18        | 3.47%   |
| Dell Latitude           | 17        | 3.28%   |
| HP Pavilion             | 16        | 3.08%   |
| HP Laptop               | 15        | 2.89%   |
| Unknown                 | 14        | 2.7%    |
| HP Compaq               | 13        | 2.5%    |
| Lenovo IdeaPad          | 12        | 2.31%   |
| Dell OptiPlex           | 11        | 2.12%   |
| Toshiba Satellite       | 10        | 1.93%   |
| HP EliteBook            | 8         | 1.54%   |
| Dell Precision          | 8         | 1.54%   |
| ASUS PRIME              | 7         | 1.35%   |
| HP ProBook              | 5         | 0.96%   |
| Lenovo ThinkCentre      | 4         | 0.77%   |
| ASUS VivoBook           | 4         | 0.77%   |
| Samsung RV411           | 3         | 0.58%   |
| HP Presario             | 3         | 0.58%   |
| HP 255                  | 3         | 0.58%   |
| Gigabyte X570           | 3         | 0.58%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.58%   |
| Dell XPS                | 3         | 0.58%   |
| ASUS ROG                | 3         | 0.58%   |
| Acer Veriton            | 3         | 0.58%   |
| Acer AOD270             | 3         | 0.58%   |
| Packard Bell EasyNote   | 2         | 0.39%   |
| Lenovo Yoga             | 2         | 0.39%   |
| HP Notebook             | 2         | 0.39%   |
| HP ENVY                 | 2         | 0.39%   |
| HP 14                   | 2         | 0.39%   |
| Gigabyte Z390           | 2         | 0.39%   |
| Foxconn 945             | 2         | 0.39%   |
| Dell System             | 2         | 0.39%   |
| ASUS X101CH             | 2         | 0.39%   |
| ASUS P5KPL-AM           | 2         | 0.39%   |
| ASUS All                | 2         | 0.39%   |
| Apple MacBookPro5       | 2         | 0.39%   |
| Acer Swift              | 2         | 0.39%   |
| Wistron ProLiant        | 1         | 0.19%   |
| TUXEDO BC1510           | 1         | 0.19%   |
| Toshiba LX835           | 1         | 0.19%   |
| Toshiba dynabook        | 1         | 0.19%   |
| Supermicro X8DT3        | 1         | 0.19%   |
| Sony VPCSB3M1R          | 1         | 0.19%   |
| Sony VPCS131FM          | 1         | 0.19%   |
| Sony VPCP116KG          | 1         | 0.19%   |
| Sony VPCEB1M1R          | 1         | 0.19%   |
| Sony VGN-FZ140E         | 1         | 0.19%   |
| Sony VGN-AW41MF         | 1         | 0.19%   |
| Sony SVE1713Y1RB        | 1         | 0.19%   |
| Sony SVE1512G1RW        | 1         | 0.19%   |
| Sony SVE1511N1ESI       | 1         | 0.19%   |
| Semp Toshiba STI        | 1         | 0.19%   |
| Semp Toshiba NI         | 1         | 0.19%   |
| Samsung RV413           | 1         | 0.19%   |
| Samsung R59             | 1         | 0.19%   |
| Samsung NC10            | 1         | 0.19%   |
| Samsung 730QDA          | 1         | 0.19%   |
| Samsung 305U1A          | 1         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 54        | 10.4%   |
| 2009    | 43        | 8.29%   |
| 2010    | 40        | 7.71%   |
| 2011    | 39        | 7.51%   |
| 2007    | 39        | 7.51%   |
| 2018    | 38        | 7.32%   |
| 2008    | 35        | 6.74%   |
| 2013    | 32        | 6.17%   |
| 2014    | 30        | 5.78%   |
| 2019    | 29        | 5.59%   |
| 2020    | 22        | 4.24%   |
| 2021    | 21        | 4.05%   |
| 2016    | 21        | 4.05%   |
| 2017    | 20        | 3.85%   |
| 2015    | 18        | 3.47%   |
| 2006    | 18        | 3.47%   |
| 2005    | 10        | 1.93%   |
| 2003    | 5         | 0.96%   |
| 2004    | 2         | 0.39%   |
| 2022    | 1         | 0.19%   |
| 2002    | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 312       | 60.12%  |
| Desktop     | 185       | 35.65%  |
| All in one  | 8         | 1.54%   |
| Convertible | 6         | 1.16%   |
| Tablet      | 4         | 0.77%   |
| Server      | 3         | 0.58%   |
| Mini pc     | 1         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 496       | 94.84%  |
| Enabled  | 27        | 5.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 517       | 99.61%  |
| Yes  | 2         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 139       | 26.53%  |
| 4.01-8.0    | 96        | 18.32%  |
| 8.01-16.0   | 75        | 14.31%  |
| 16.01-24.0  | 68        | 12.98%  |
| 2.01-3.0    | 56        | 10.69%  |
| 1.01-2.0    | 46        | 8.78%   |
| 32.01-64.0  | 20        | 3.82%   |
| 0.51-1.0    | 14        | 2.67%   |
| 24.01-32.0  | 5         | 0.95%   |
| 64.01-256.0 | 5         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 257       | 46.64%  |
| 2.01-3.0   | 119       | 21.6%   |
| 0.51-1.0   | 87        | 15.79%  |
| 3.01-4.0   | 54        | 9.8%    |
| 4.01-8.0   | 26        | 4.72%   |
| 8.01-16.0  | 4         | 0.73%   |
| 0.01-0.5   | 3         | 0.54%   |
| 32.01-64.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 330       | 62.38%  |
| 2      | 132       | 24.95%  |
| 3      | 31        | 5.86%   |
| 4      | 18        | 3.4%    |
| 7      | 5         | 0.95%   |
| 0      | 5         | 0.95%   |
| 6      | 4         | 0.76%   |
| 5      | 3         | 0.57%   |
| 8      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 52.57%  |
| No        | 249       | 47.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 475       | 91.52%  |
| No        | 44        | 8.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 399       | 76.15%  |
| No        | 125       | 23.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 286       | 55%     |
| Yes       | 234       | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 73        | 14.04%  |
| Germany             | 56        | 10.77%  |
| Brazil              | 52        | 10%     |
| Russia              | 34        | 6.54%   |
| UK                  | 25        | 4.81%   |
| France              | 24        | 4.62%   |
| Canada              | 20        | 3.85%   |
| Poland              | 18        | 3.46%   |
| Italy               | 17        | 3.27%   |
| Spain               | 16        | 3.08%   |
| Australia           | 12        | 2.31%   |
| Ukraine             | 11        | 2.12%   |
| Netherlands         | 11        | 2.12%   |
| Mexico              | 11        | 2.12%   |
| Bulgaria            | 9         | 1.73%   |
| Argentina           | 9         | 1.73%   |
| Switzerland         | 6         | 1.15%   |
| Belgium             | 6         | 1.15%   |
| Austria             | 6         | 1.15%   |
| Turkey              | 5         | 0.96%   |
| Romania             | 5         | 0.96%   |
| Portugal            | 5         | 0.96%   |
| Greece              | 5         | 0.96%   |
| Sweden              | 4         | 0.77%   |
| Philippines         | 4         | 0.77%   |
| India               | 4         | 0.77%   |
| Chile               | 4         | 0.77%   |
| Belarus             | 4         | 0.77%   |
| South Africa        | 3         | 0.58%   |
| Indonesia           | 3         | 0.58%   |
| Hungary             | 3         | 0.58%   |
| Czechia             | 3         | 0.58%   |
| Bahrain             | 3         | 0.58%   |
| Venezuela           | 2         | 0.38%   |
| Tunisia             | 2         | 0.38%   |
| Puerto Rico         | 2         | 0.38%   |
| Luxembourg          | 2         | 0.38%   |
| Japan               | 2         | 0.38%   |
| Ireland             | 2         | 0.38%   |
| Finland             | 2         | 0.38%   |
| Estonia             | 2         | 0.38%   |
| Egypt               | 2         | 0.38%   |
| Ecuador             | 2         | 0.38%   |
| Croatia             | 2         | 0.38%   |
| China               | 2         | 0.38%   |
| Bolivia             | 2         | 0.38%   |
| Bangladesh          | 2         | 0.38%   |
| Uruguay             | 1         | 0.19%   |
| Trinidad and Tobago | 1         | 0.19%   |
| South Korea         | 1         | 0.19%   |
| Slovakia            | 1         | 0.19%   |
| Singapore           | 1         | 0.19%   |
| Serbia              | 1         | 0.19%   |
| Peru                | 1         | 0.19%   |
| Paraguay            | 1         | 0.19%   |
| Pakistan            | 1         | 0.19%   |
| Norway              | 1         | 0.19%   |
| Nicaragua           | 1         | 0.19%   |
| New Zealand         | 1         | 0.19%   |
| Myanmar             | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 8         | 1.48%   |
| Sao Paulo         | 5         | 0.92%   |
| Wroclaw           | 4         | 0.74%   |
| Sofia             | 4         | 0.74%   |
| Poznan            | 4         | 0.74%   |
| Perth             | 4         | 0.74%   |
| Paris             | 4         | 0.74%   |
| Montreal          | 4         | 0.74%   |
| Hamburg           | 4         | 0.74%   |
| Athens            | 4         | 0.74%   |
| Wohlen            | 3         | 0.55%   |
| Voronezh          | 3         | 0.55%   |
| St Petersburg     | 3         | 0.55%   |
| Seville           | 3         | 0.55%   |
| Rio de Janeiro    | 3         | 0.55%   |
| Melbourne         | 3         | 0.55%   |
| Manama            | 3         | 0.55%   |
| Glasgow           | 3         | 0.55%   |
| Frankfurt am Main | 3         | 0.55%   |
| Florianópolis    | 3         | 0.55%   |
| Berlin            | 3         | 0.55%   |
| Zurich            | 2         | 0.37%   |
| Warsaw            | 2         | 0.37%   |
| Victoria          | 2         | 0.37%   |
| Toronto           | 2         | 0.37%   |
| The Hague         | 2         | 0.37%   |
| Stuttgart         | 2         | 0.37%   |
| Stockholm         | 2         | 0.37%   |
| Sao Luís         | 2         | 0.37%   |
| Santa Rosa        | 2         | 0.37%   |
| Rho               | 2         | 0.37%   |
| Recife            | 2         | 0.37%   |
| Rapla             | 2         | 0.37%   |
| Porto Alegre      | 2         | 0.37%   |
| Pokrovske         | 2         | 0.37%   |
| Plovdiv           | 2         | 0.37%   |
| Oxford            | 2         | 0.37%   |
| Oruro             | 2         | 0.37%   |
| Nuremberg         | 2         | 0.37%   |
| Nottingham        | 2         | 0.37%   |
| Neasden           | 2         | 0.37%   |
| Minsk             | 2         | 0.37%   |
| Milan             | 2         | 0.37%   |
| Mexico City       | 2         | 0.37%   |
| Marseille         | 2         | 0.37%   |
| Marburg           | 2         | 0.37%   |
| Mannheim          | 2         | 0.37%   |
| Madrid            | 2         | 0.37%   |
| London            | 2         | 0.37%   |
| Lisbon            | 2         | 0.37%   |
| Krakow            | 2         | 0.37%   |
| Kazanlak          | 2         | 0.37%   |
| Karlsruhe         | 2         | 0.37%   |
| Helsinki          | 2         | 0.37%   |
| Foz do Iguaçu    | 2         | 0.37%   |
| Duisburg          | 2         | 0.37%   |
| Dhaka             | 2         | 0.37%   |
| Denver            | 2         | 0.37%   |
| Cologne           | 2         | 0.37%   |
| Chelyabinsk       | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 136       | 199    | 19.05%  |
| Seagate                        | 107       | 156    | 14.99%  |
| Samsung Electronics            | 99        | 124    | 13.87%  |
| Hitachi                        | 41        | 45     | 5.74%   |
| Toshiba                        | 40        | 47     | 5.6%    |
| Kingston                       | 34        | 39     | 4.76%   |
| Unknown                        | 30        | 35     | 4.2%    |
| SanDisk                        | 26        | 33     | 3.64%   |
| Crucial                        | 22        | 26     | 3.08%   |
| Intel                          | 17        | 18     | 2.38%   |
| HGST                           | 13        | 14     | 1.82%   |
| Phison                         | 10        | 12     | 1.4%    |
| A-DATA Technology              | 10        | 10     | 1.4%    |
| Fujitsu                        | 9         | 9      | 1.26%   |
| SK hynix                       | 8         | 10     | 1.12%   |
| Micron Technology              | 8         | 9      | 1.12%   |
| China                          | 8         | 9      | 1.12%   |
| Patriot                        | 6         | 7      | 0.84%   |
| Transcend                      | 5         | 7      | 0.7%    |
| Intenso                        | 5         | 6      | 0.7%    |
| KingSpec                       | 4         | 4      | 0.56%   |
| Apple                          | 4         | 9      | 0.56%   |
| Team                           | 3         | 4      | 0.42%   |
| PNY                            | 3         | 3      | 0.42%   |
| OCZ                            | 3         | 5      | 0.42%   |
| Maxtor                         | 3         | 5      | 0.42%   |
| KingDian                       | 3         | 4      | 0.42%   |
| Hewlett-Packard                | 3         | 4      | 0.42%   |
| GOODRAM                        | 3         | 3      | 0.42%   |
| Gigabyte Technology            | 3         | 4      | 0.42%   |
| TCSUNBOW                       | 2         | 2      | 0.28%   |
| SABRENT                        | 2         | 2      | 0.28%   |
| Plextor                        | 2         | 3      | 0.28%   |
| Mushkin                        | 2         | 2      | 0.28%   |
| JMicron Technology             | 2         | 3      | 0.28%   |
| IBM/Hitachi                    | 2         | 2      | 0.28%   |
| CT500MX5                       | 2         | 2      | 0.28%   |
| XrayDisk                       | 1         | 2      | 0.14%   |
| USB30                          | 1         | 2      | 0.14%   |
| SSD PHIS                       | 1         | 1      | 0.14%   |
| Solid State Storage Technology | 1         | 1      | 0.14%   |
| Smartbuy                       | 1         | 1      | 0.14%   |
| Silicon Motion                 | 1         | 1      | 0.14%   |
| ShiJi                          | 1         | 1      | 0.14%   |
| Oyen                           | 1         | 1      | 0.14%   |
| ORICO                          | 1         | 1      | 0.14%   |
| OCZ-VERTEX                     | 1         | 1      | 0.14%   |
| Netac                          | 1         | 1      | 0.14%   |
| Microtech                      | 1         | 1      | 0.14%   |
| Micron/Crucial Technology      | 1         | 2      | 0.14%   |
| LITEON                         | 1         | 1      | 0.14%   |
| KIOXIA                         | 1         | 2      | 0.14%   |
| Kingmax                        | 1         | 1      | 0.14%   |
| KESU                           | 1         | 2      | 0.14%   |
| Initio                         | 1         | 1      | 0.14%   |
| HUAWEI                         | 1         | 1      | 0.14%   |
| HPE                            | 1         | 4      | 0.14%   |
| Hikvision                      | 1         | 1      | 0.14%   |
| GALAX                          | 1         | 1      | 0.14%   |
| FORESEE                        | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB           | 9         | 1.16%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 1.03%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 0.9%    |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.9%    |
| Unknown MMC Card  32GB              | 6         | 0.77%   |
| Toshiba MQ01ABD100 1TB              | 6         | 0.77%   |
| Samsung SSD 850 EVO 250GB           | 6         | 0.77%   |
| Unknown SD/MMC/MS PRO 64GB          | 5         | 0.65%   |
| SanDisk NVMe SSD Drive 256GB        | 5         | 0.65%   |
| Samsung SSD 860 EVO 1TB             | 5         | 0.65%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 0.52%   |
| Unknown MMC Card  7GB               | 4         | 0.52%   |
| Toshiba MQ01ABF050 500GB            | 4         | 0.52%   |
| Toshiba DT01ACA100 1TB              | 4         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.52%   |
| Seagate Expansion 1TB               | 4         | 0.52%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 0.52%   |
| Crucial CT480BX500SSD1 480GB        | 4         | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 4         | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 3         | 0.39%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 0.39%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 3         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 0.39%   |
| Unknown MMC Card  64GB              | 3         | 0.39%   |
| Unknown MMC Card  128GB             | 3         | 0.39%   |
| Seagate ST9500325AS 500GB           | 3         | 0.39%   |
| Seagate ST9250315AS 250GB           | 3         | 0.39%   |
| Seagate ST2000LX001-1RG174 2TB      | 3         | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB      | 3         | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB      | 3         | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB        | 3         | 0.39%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.39%   |
| Samsung NVMe SSD Drive 256GB        | 3         | 0.39%   |
| Samsung HD322HJ 320GB               | 3         | 0.39%   |
| Samsung HD161HJ 160GB               | 3         | 0.39%   |
| Samsung HD103SJ 1TB                 | 3         | 0.39%   |
| Phison NVMe SSD Drive 256GB         | 3         | 0.39%   |
| Micron NVMe SSD Drive 512GB         | 3         | 0.39%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 3         | 0.39%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 0.39%   |
| Hitachi HTS545032B9A300 320GB       | 3         | 0.39%   |
| HGST HTS545050A7E680 500GB          | 3         | 0.39%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 3         | 0.39%   |
| China SATA SSD 120GB                | 3         | 0.39%   |
| A-DATA SU650 120GB SSD              | 3         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 0.26%   |
| WDC WDBNCE5000PNC 500GB SSD         | 2         | 0.26%   |
| WDC WD7500BPVT-75HXZT3 752GB        | 2         | 0.26%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.26%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2         | 0.26%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 0.26%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 0.26%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 0.26%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 2         | 0.26%   |
| WDC WD2500AAKX-753CA1 250GB         | 2         | 0.26%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 0.26%   |
| WDC WD1600AABS-00PRA0 160GB         | 2         | 0.26%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.26%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 117       | 177    | 32.14%  |
| Seagate             | 106       | 154    | 29.12%  |
| Hitachi             | 41        | 45     | 11.26%  |
| Toshiba             | 34        | 37     | 9.34%   |
| Samsung Electronics | 28        | 36     | 7.69%   |
| HGST                | 13        | 14     | 3.57%   |
| Fujitsu             | 9         | 9      | 2.47%   |
| Unknown             | 5         | 5      | 1.37%   |
| Maxtor              | 3         | 5      | 0.82%   |
| SABRENT             | 2         | 2      | 0.55%   |
| IBM/Hitachi         | 2         | 2      | 0.55%   |
| KESU                | 1         | 2      | 0.27%   |
| HPE                 | 1         | 4      | 0.27%   |
| ExcelStor           | 1         | 1      | 0.27%   |
| DAS                 | 1         | 4      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 63     | 21.6%   |
| Kingston            | 31        | 36     | 12.4%   |
| Crucial             | 22        | 26     | 8.8%    |
| SanDisk             | 17        | 24     | 6.8%    |
| WDC                 | 13        | 13     | 5.2%    |
| Intel               | 10        | 10     | 4%      |
| A-DATA Technology   | 10        | 10     | 4%      |
| China               | 7         | 8      | 2.8%    |
| Toshiba             | 6         | 10     | 2.4%    |
| Patriot             | 6         | 7      | 2.4%    |
| Transcend           | 5         | 7      | 2%      |
| Micron Technology   | 5         | 6      | 2%      |
| Intenso             | 4         | 5      | 1.6%    |
| Team                | 3         | 4      | 1.2%    |
| SK hynix            | 3         | 4      | 1.2%    |
| PNY                 | 3         | 3      | 1.2%    |
| OCZ                 | 3         | 5      | 1.2%    |
| KingSpec            | 3         | 3      | 1.2%    |
| KingDian            | 3         | 4      | 1.2%    |
| Hewlett-Packard     | 3         | 4      | 1.2%    |
| GOODRAM             | 3         | 3      | 1.2%    |
| Gigabyte Technology | 3         | 4      | 1.2%    |
| Apple               | 3         | 3      | 1.2%    |
| Unknown             | 2         | 2      | 0.8%    |
| TCSUNBOW            | 2         | 2      | 0.8%    |
| Plextor             | 2         | 3      | 0.8%    |
| CT500MX5            | 2         | 2      | 0.8%    |
| USB30               | 1         | 2      | 0.4%    |
| SSD PHIS            | 1         | 1      | 0.4%    |
| Smartbuy            | 1         | 1      | 0.4%    |
| ORICO               | 1         | 1      | 0.4%    |
| OCZ-VERTEX          | 1         | 1      | 0.4%    |
| Netac               | 1         | 1      | 0.4%    |
| Mushkin             | 1         | 1      | 0.4%    |
| Microtech           | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |
| Kingmax             | 1         | 1      | 0.4%    |
| Hikvision           | 1         | 1      | 0.4%    |
| GALAX               | 1         | 1      | 0.4%    |
| FORESEE             | 1         | 1      | 0.4%    |
| Drevo               | 1         | 2      | 0.4%    |
| Dogfish             | 1         | 1      | 0.4%    |
| Corsair             | 1         | 1      | 0.4%    |
| BIWIN               | 1         | 1      | 0.4%    |
| BHT                 | 1         | 2      | 0.4%    |
| BAITITON            | 1         | 1      | 0.4%    |
| ASUS-PHISON         | 1         | 2      | 0.4%    |
| Acer                | 1         | 1      | 0.4%    |
| 2.5''               | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 316       | 497    | 49.84%  |
| SSD     | 216       | 297    | 34.07%  |
| NVMe    | 66        | 87     | 10.41%  |
| MMC     | 24        | 27     | 3.79%   |
| Unknown | 12        | 16     | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 461       | 758    | 78.94%  |
| NVMe | 66        | 87     | 11.3%   |
| SAS  | 33        | 52     | 5.65%   |
| MMC  | 24        | 27     | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 388       | 570    | 71.45%  |
| 0.51-1.0   | 112       | 155    | 20.63%  |
| 1.01-2.0   | 25        | 35     | 4.6%    |
| 3.01-4.0   | 7         | 12     | 1.29%   |
| 2.01-3.0   | 6         | 14     | 1.1%    |
| 4.01-10.0  | 5         | 8      | 0.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 192       | 36.16%  |
| 251-500        | 121       | 22.79%  |
| 51-100         | 53        | 9.98%   |
| 501-1000       | 51        | 9.6%    |
| 1001-2000      | 38        | 7.16%   |
| More than 3000 | 27        | 5.08%   |
| 21-50          | 25        | 4.71%   |
| 2001-3000      | 13        | 2.45%   |
| 1-20           | 10        | 1.88%   |
| Unknown        | 1         | 0.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 236       | 42.75%  |
| 21-50          | 123       | 22.28%  |
| 51-100         | 59        | 10.69%  |
| 101-250        | 54        | 9.78%   |
| 251-500        | 23        | 4.17%   |
| 501-1000       | 22        | 3.99%   |
| 1001-2000      | 15        | 2.72%   |
| 2001-3000      | 10        | 1.81%   |
| More than 3000 | 9         | 1.63%   |
| Unknown        | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-26A23T0 320GB        | 1         | 1      | 5%      |
| WDC WD2500BEVT-24A23T0 250GB        | 1         | 1      | 5%      |
| Seagate STM9120817AS 120GB          | 1         | 1      | 5%      |
| Seagate ST9640423AS 640GB           | 1         | 1      | 5%      |
| Seagate ST9320325AS 320GB           | 1         | 1      | 5%      |
| Seagate ST9120821AS 120GB           | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 5%      |
| Seagate ST3250318AS 250GB           | 1         | 1      | 5%      |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 5%      |
| Samsung Electronics SP2004C 200GB   | 1         | 1      | 5%      |
| Samsung Electronics MP0402H 40GB    | 1         | 1      | 5%      |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 5%      |
| Samsung Electronics HD103SJ 1TB     | 1         | 1      | 5%      |
| Phison ES 512GB                     | 1         | 1      | 5%      |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 5%      |
| Intel SSDSCKKF256G8 SATA 256GB      | 1         | 1      | 5%      |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 5%      |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 5%      |
| Fujitsu MHZ2080BJ FFS G2 80GB       | 1         | 1      | 5%      |
| Crucial M4-CT256M4SSD2 256GB        | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 30%     |
| Samsung Electronics | 4         | 4      | 20%     |
| WDC                 | 2         | 2      | 10%     |
| SanDisk             | 1         | 1      | 5%      |
| Phison              | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| Hitachi             | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| Samsung Electronics | 4         | 4      | 26.67%  |
| WDC                 | 2         | 2      | 13.33%  |
| Hitachi             | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 75%     |
| SSD  | 4         | 4      | 20%     |
| NVMe | 1         | 1      | 5%      |

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
| Detected | 420       | 744    | 78.21%  |
| Works    | 97        | 160    | 18.06%  |
| Malfunc  | 20        | 20     | 3.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 379       | 63.06%  |
| AMD                              | 88        | 14.64%  |
| Samsung Electronics              | 22        | 3.66%   |
| Nvidia                           | 17        | 2.83%   |
| SanDisk                          | 15        | 2.5%    |
| ASMedia Technology               | 11        | 1.83%   |
| Phison Electronics               | 10        | 1.66%   |
| JMicron Technology               | 10        | 1.66%   |
| Silicon Integrated Systems [SiS] | 8         | 1.33%   |
| Marvell Technology Group         | 8         | 1.33%   |
| VIA Technologies                 | 7         | 1.16%   |
| SK hynix                         | 5         | 0.83%   |
| Micron Technology                | 3         | 0.5%    |
| Kingston Technology Company      | 3         | 0.5%    |
| Broadcom / LSI                   | 3         | 0.5%    |
| Toshiba America Info Systems     | 2         | 0.33%   |
| Silicon Motion                   | 2         | 0.33%   |
| Silicon Image                    | 2         | 0.33%   |
| Solid State Storage Technology   | 1         | 0.17%   |
| Micron/Crucial Technology        | 1         | 0.17%   |
| LSI Logic / Symbios Logic        | 1         | 0.17%   |
| KIOXIA                           | 1         | 0.17%   |
| Integrated Technology Express    | 1         | 0.17%   |
| Apple                            | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 54        | 7.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 4.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 24        | 3.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21        | 2.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 21        | 2.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 20        | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 16        | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16        | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 14        | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 1.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 12        | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 11        | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 11        | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 11        | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11        | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 1.34%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 10        | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.34%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.07%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8         | 1.07%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 7         | 0.94%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 7         | 0.94%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 0.94%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7         | 0.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 0.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 6         | 0.8%    |
| SanDisk Non-Volatile memory controller                                                  | 6         | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 6         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 0.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 0.67%   |
| Phison E12 NVMe Controller                                                              | 5         | 0.67%   |
| Nvidia MCP61 IDE                                                                        | 5         | 0.67%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.53%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 4         | 0.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 0.53%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                              | 4         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.53%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.53%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4         | 0.53%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 4         | 0.53%   |
| AMD IXP SB4x0 IDE Controller                                                            | 4         | 0.53%   |
| AMD FCH SATA Controller D                                                               | 4         | 0.53%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4         | 0.53%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3         | 0.4%    |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 362       | 57.1%   |
| IDE  | 162       | 25.55%  |
| NVMe | 68        | 10.73%  |
| RAID | 37        | 5.84%   |
| SAS  | 3         | 0.47%   |
| SCSI | 2         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 406       | 78.23%  |
| AMD    | 113       | 21.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                | 10        | 1.93%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 1.16%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 5         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.77%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.77%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 0.77%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 4         | 0.77%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 0.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 4         | 0.77%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 4         | 0.77%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.77%   |
| Intel Pentium CPU G645 @ 2.90GHz              | 3         | 0.58%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 3         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.58%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.58%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 0.58%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.58%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 3         | 0.58%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 3         | 0.58%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.58%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.58%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.39%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.39%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.39%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.39%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 2         | 0.39%   |
| Intel Pentium D CPU 3.00GHz                   | 2         | 0.39%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.39%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.39%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.39%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 0.39%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 2         | 0.39%   |
| Intel Pentium 4 CPU 2.80GHz                   | 2         | 0.39%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 2         | 0.39%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.39%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.39%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.39%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.39%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.39%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 2         | 0.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.39%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.39%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.39%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 0.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 74        | 14.26%  |
| Intel Core i7                  | 64        | 12.33%  |
| Intel Core 2 Duo               | 49        | 9.44%   |
| Intel Core i3                  | 45        | 8.67%   |
| Intel Celeron                  | 30        | 5.78%   |
| Intel Atom                     | 28        | 5.39%   |
| Intel Pentium                  | 20        | 3.85%   |
| AMD Ryzen 5                    | 20        | 3.85%   |
| Other                          | 19        | 3.66%   |
| Intel Xeon                     | 13        | 2.5%    |
| AMD Ryzen 7                    | 11        | 2.12%   |
| Intel Core 2                   | 10        | 1.93%   |
| Intel Pentium Dual-Core        | 9         | 1.73%   |
| Intel Core 2 Quad              | 9         | 1.73%   |
| Intel Pentium Dual             | 8         | 1.54%   |
| Intel Genuine                  | 8         | 1.54%   |
| Intel Pentium M                | 6         | 1.16%   |
| AMD Sempron                    | 6         | 1.16%   |
| AMD FX                         | 6         | 1.16%   |
| AMD A4                         | 6         | 1.16%   |
| Intel Pentium D                | 5         | 0.96%   |
| Intel Pentium 4                | 5         | 0.96%   |
| AMD Ryzen 3                    | 5         | 0.96%   |
| AMD Athlon 64 X2               | 5         | 0.96%   |
| AMD E2                         | 4         | 0.77%   |
| AMD Athlon                     | 4         | 0.77%   |
| Intel Core Duo                 | 3         | 0.58%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.58%   |
| AMD Phenom II X4               | 3         | 0.58%   |
| AMD E1                         | 3         | 0.58%   |
| AMD Athlon XP                  | 3         | 0.58%   |
| Intel Core i9                  | 2         | 0.39%   |
| Intel Celeron M                | 2         | 0.39%   |
| AMD Ryzen 9                    | 2         | 0.39%   |
| AMD Phenom II X6               | 2         | 0.39%   |
| AMD Mobile Sempron             | 2         | 0.39%   |
| AMD E                          | 2         | 0.39%   |
| AMD Athlon II X4               | 2         | 0.39%   |
| AMD Athlon II                  | 2         | 0.39%   |
| AMD A8                         | 2         | 0.39%   |
| AMD A6                         | 2         | 0.39%   |
| AMD A10                        | 2         | 0.39%   |
| Intel Pentium Silver           | 1         | 0.19%   |
| Intel Mobile Pentium 4         | 1         | 0.19%   |
| Intel Core m5                  | 1         | 0.19%   |
| Intel Core 2 Extreme           | 1         | 0.19%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.19%   |
| AMD Turion II Neo              | 1         | 0.19%   |
| AMD Turion 64 Mobile           | 1         | 0.19%   |
| AMD Ryzen 5 PRO                | 1         | 0.19%   |
| AMD Phenom II X2               | 1         | 0.19%   |
| AMD Phenom II                  | 1         | 0.19%   |
| AMD C-50                       | 1         | 0.19%   |
| AMD Athlon Neo                 | 1         | 0.19%   |
| AMD Athlon II X2               | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 289       | 55.58%  |
| 4      | 133       | 25.58%  |
| 1      | 51        | 9.81%   |
| 6      | 21        | 4.04%   |
| 8      | 18        | 3.46%   |
| 12     | 3         | 0.58%   |
| 16     | 2         | 0.38%   |
| 3      | 2         | 0.38%   |
| 10     | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 513       | 98.84%  |
| 2      | 6         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 261       | 50.29%  |
| 2      | 258       | 49.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 472       | 90.94%  |
| 32-bit         | 47        | 9.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 8.02%   |
| 0x206a7    | 37        | 7.06%   |
| 0x1067a    | 37        | 7.06%   |
| 0x306a9    | 34        | 6.49%   |
| 0x6fd      | 20        | 3.82%   |
| 0x306c3    | 20        | 3.82%   |
| 0x40651    | 16        | 3.05%   |
| 0x406e3    | 13        | 2.48%   |
| 0x30661    | 12        | 2.29%   |
| 0x20655    | 11        | 2.1%    |
| 0x106c2    | 11        | 2.1%    |
| 0x806c1    | 10        | 1.91%   |
| 0x08108109 | 10        | 1.91%   |
| 0x06006705 | 10        | 1.91%   |
| 0x806ea    | 9         | 1.72%   |
| 0x6f6      | 9         | 1.72%   |
| 0x506e3    | 8         | 1.53%   |
| 0x10676    | 8         | 1.53%   |
| 0x010000c8 | 8         | 1.53%   |
| 0x806e9    | 7         | 1.34%   |
| 0x6ec      | 7         | 1.34%   |
| 0x6fb      | 6         | 1.15%   |
| 0x20652    | 6         | 1.15%   |
| 0x106e5    | 6         | 1.15%   |
| 0x08608103 | 6         | 1.15%   |
| 0x906ed    | 5         | 0.95%   |
| 0x906ea    | 5         | 0.95%   |
| 0x806ec    | 5         | 0.95%   |
| 0x6e8      | 5         | 0.95%   |
| 0x30678    | 5         | 0.95%   |
| 0x10677    | 5         | 0.95%   |
| 0xf29      | 4         | 0.76%   |
| 0x906eb    | 4         | 0.76%   |
| 0x706a1    | 4         | 0.76%   |
| 0x6d8      | 4         | 0.76%   |
| 0x406c4    | 4         | 0.76%   |
| 0x306d4    | 4         | 0.76%   |
| 0x08108102 | 4         | 0.76%   |
| 0xf65      | 3         | 0.57%   |
| 0xf64      | 3         | 0.57%   |
| 0x806eb    | 3         | 0.57%   |
| 0x706e5    | 3         | 0.57%   |
| 0x506c9    | 3         | 0.57%   |
| 0x206c2    | 3         | 0.57%   |
| 0x106ca    | 3         | 0.57%   |
| 0x106a5    | 3         | 0.57%   |
| 0x10661    | 3         | 0.57%   |
| 0x08101016 | 3         | 0.57%   |
| 0x07030105 | 3         | 0.57%   |
| 0x06001119 | 3         | 0.57%   |
| 0x06000852 | 3         | 0.57%   |
| 0x706a8    | 2         | 0.38%   |
| 0x6f2      | 2         | 0.38%   |
| 0x406c3    | 2         | 0.38%   |
| 0x30673    | 2         | 0.38%   |
| 0x206d7    | 2         | 0.38%   |
| 0x0a50000c | 2         | 0.38%   |
| 0x08701021 | 2         | 0.38%   |
| 0x08701013 | 2         | 0.38%   |
| 0x08200103 | 2         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 54        | 10.4%   |
| SandyBridge     | 43        | 8.29%   |
| Core            | 42        | 8.09%   |
| KabyLake        | 41        | 7.9%    |
| Haswell         | 38        | 7.32%   |
| IvyBridge       | 35        | 6.74%   |
| Bonnell         | 27        | 5.2%    |
| Skylake         | 21        | 4.05%   |
| Westmere        | 20        | 3.85%   |
| P6              | 18        | 3.47%   |
| Zen+            | 17        | 3.28%   |
| K8 Hammer       | 16        | 3.08%   |
| K10             | 14        | 2.7%    |
| Silvermont      | 13        | 2.5%    |
| NetBurst        | 12        | 2.31%   |
| Excavator       | 12        | 2.31%   |
| Zen             | 11        | 2.12%   |
| TigerLake       | 10        | 1.93%   |
| Nehalem         | 9         | 1.73%   |
| Piledriver      | 7         | 1.35%   |
| Unknown         | 7         | 1.35%   |
| Goldmont plus   | 6         | 1.16%   |
| Broadwell       | 6         | 1.16%   |
| Zen 3           | 5         | 0.96%   |
| Zen 2           | 5         | 0.96%   |
| Puma            | 5         | 0.96%   |
| Icelake         | 4         | 0.77%   |
| Bobcat          | 4         | 0.77%   |
| K6              | 3         | 0.58%   |
| Jaguar          | 3         | 0.58%   |
| Goldmont        | 3         | 0.58%   |
| CometLake       | 3         | 0.58%   |
| K8 & K10 hybrid | 2         | 0.39%   |
| Bulldozer       | 2         | 0.39%   |
| K10 Llano       | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 277       | 47.84%  |
| Nvidia                           | 151       | 26.08%  |
| AMD                              | 135       | 23.32%  |
| VIA Technologies                 | 5         | 0.86%   |
| Silicon Integrated Systems [SiS] | 5         | 0.86%   |
| Matrox Electronics Systems       | 4         | 0.69%   |
| S3 Graphics                      | 1         | 0.17%   |
| ASPEED Technology                | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 34        | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 17        | 2.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 16        | 2.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 16        | 2.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 15        | 2.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 14        | 2.29%   |
| Intel Core Processor Integrated Graphics Controller                                        | 13        | 2.13%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 12        | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 11        | 1.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 11        | 1.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                           | 9         | 1.47%   |
| Intel UHD Graphics 620                                                                     | 9         | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 9         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 8         | 1.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 8         | 1.31%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 8         | 1.31%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 8         | 1.31%   |
| Nvidia GT218 [GeForce 210]                                                                 | 7         | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 7         | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                  | 7         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 7         | 1.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 7         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 6         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 6         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 6         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 6         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 6         | 0.98%   |
| AMD Lucienne                                                                               | 6         | 0.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                    | 6         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 5         | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 4         | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                                             | 4         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 4         | 0.65%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 4         | 0.65%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 4         | 0.65%   |
| Intel HD Graphics 620                                                                      | 4         | 0.65%   |
| Intel HD Graphics 530                                                                      | 4         | 0.65%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 4         | 0.65%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 3         | 0.49%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                          | 3         | 0.49%   |
| Nvidia GF108M [GeForce GT 525M]                                                            | 3         | 0.49%   |
| Nvidia G96CM [GeForce 9600M GT]                                                            | 3         | 0.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                     | 3         | 0.49%   |
| Intel HD Graphics 5500                                                                     | 3         | 0.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 3         | 0.49%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 3         | 0.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                     | 3         | 0.49%   |
| Intel 82945G/GZ Integrated Graphics Controller                                             | 3         | 0.49%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 3         | 0.49%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 3         | 0.49%   |
| AMD RV710 [Radeon HD 4350/4550]                                                            | 3         | 0.49%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                   | 3         | 0.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                           | 3         | 0.49%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                          | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.33%   |
| Nvidia TU106 [GeForce RTX 2070]                                                            | 2         | 0.33%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.33%   |
| Nvidia GP108M [GeForce MX150]                                                              | 2         | 0.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                                            | 2         | 0.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                        | 2         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 221       | 42.42%  |
| 1 x AMD         | 114       | 21.88%  |
| 1 x Nvidia      | 112       | 21.5%   |
| Intel + Nvidia  | 36        | 6.91%   |
| Intel + AMD     | 12        | 2.3%    |
| 2 x AMD         | 6         | 1.15%   |
| 1 x VIA         | 5         | 0.96%   |
| 1 x SiS         | 5         | 0.96%   |
| 1 x Matrox      | 4         | 0.77%   |
| AMD + Nvidia    | 3         | 0.58%   |
| 2 x Nvidia      | 1         | 0.19%   |
| 1 x S3 Graphics | 1         | 0.19%   |
| 1 x ASPEED      | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 426       | 81.61%  |
| Unknown     | 49        | 9.39%   |
| Proprietary | 47        | 9%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 293       | 56.24%  |
| 0.01-0.5   | 88        | 16.89%  |
| 1.01-2.0   | 56        | 10.75%  |
| 0.51-1.0   | 47        | 9.02%   |
| 3.01-4.0   | 20        | 3.84%   |
| 7.01-8.0   | 10        | 1.92%   |
| 5.01-6.0   | 4         | 0.77%   |
| 2.01-3.0   | 3         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 74        | 14.29%  |
| AU Optronics            | 60        | 11.58%  |
| LG Display              | 42        | 8.11%   |
| BOE                     | 42        | 8.11%   |
| Chimei Innolux          | 33        | 6.37%   |
| Goldstar                | 27        | 5.21%   |
| Acer                    | 22        | 4.25%   |
| Dell                    | 21        | 4.05%   |
| Lenovo                  | 13        | 2.51%   |
| Chi Mei Optoelectronics | 13        | 2.51%   |
| Ancor Communications    | 13        | 2.51%   |
| BenQ                    | 12        | 2.32%   |
| AOC                     | 12        | 2.32%   |
| LG Philips              | 11        | 2.12%   |
| Hewlett-Packard         | 11        | 2.12%   |
| Philips                 | 10        | 1.93%   |
| Apple                   | 9         | 1.74%   |
| Unknown                 | 8         | 1.54%   |
| HannStar                | 8         | 1.54%   |
| Sony                    | 7         | 1.35%   |
| InfoVision              | 5         | 0.97%   |
| Fujitsu Siemens         | 4         | 0.77%   |
| Quanta Display          | 3         | 0.58%   |
| PANDA                   | 3         | 0.58%   |
| Iiyama                  | 3         | 0.58%   |
| CPT                     | 3         | 0.58%   |
| ___                     | 2         | 0.39%   |
| Toshiba                 | 2         | 0.39%   |
| Sharp                   | 2         | 0.39%   |
| Sceptre Tech            | 2         | 0.39%   |
| NEC Computers           | 2         | 0.39%   |
| Medion                  | 2         | 0.39%   |
| LG Electronics          | 2         | 0.39%   |
| eMachines               | 2         | 0.39%   |
| DENON                   | 2         | 0.39%   |
| Belinea                 | 2         | 0.39%   |
| ASUSTek Computer        | 2         | 0.39%   |
| ViewSonic               | 1         | 0.19%   |
| Vestel                  | 1         | 0.19%   |
| TR_                     | 1         | 0.19%   |
| Targa Visionary         | 1         | 0.19%   |
| Seiko/Epson             | 1         | 0.19%   |
| RTK                     | 1         | 0.19%   |
| Planar                  | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| OEM                     | 1         | 0.19%   |
| NCS                     | 1         | 0.19%   |
| MStar                   | 1         | 0.19%   |
| MLT                     | 1         | 0.19%   |
| Mitsubishi              | 1         | 0.19%   |
| Microstep               | 1         | 0.19%   |
| Insignia                | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| IBM                     | 1         | 0.19%   |
| Hitachi                 | 1         | 0.19%   |
| ELSA International      | 1         | 0.19%   |
| Elo Touch               | 1         | 0.19%   |
| ELO                     | 1         | 0.19%   |
| Eizo                    | 1         | 0.19%   |
| Compal                  | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 7         | 1.32%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.57%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.57%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 0.57%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.57%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.57%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 2         | 0.38%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.38%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.38%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.38%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.38%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.38%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.38%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 2         | 0.38%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                        | 2         | 0.38%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.38%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE06F9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 2         | 0.38%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                            | 2         | 0.38%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch         | 2         | 0.38%   |
| ___ LCD TV ___0101 1360x768                                              | 1         | 0.19%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                    | 1         | 0.19%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 1         | 0.19%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                                | 1         | 0.19%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                       | 1         | 0.19%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                       | 1         | 0.19%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.19%   |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 0.19%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                        | 1         | 0.19%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                 | 1         | 0.19%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                   | 1         | 0.19%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 0.19%   |
| Toshiba LCD Monitor TV 1920x1080                                         | 1         | 0.19%   |
| Toshiba LCD Monitor TOS508F 1920x1080 476x268mm 21.5-inch                | 1         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 187       | 37.25%  |
| 1366x768 (WXGA)    | 113       | 22.51%  |
| 1280x1024 (SXGA)   | 36        | 7.17%   |
| 1280x800 (WXGA)    | 30        | 5.98%   |
| 1600x900 (HD+)     | 25        | 4.98%   |
| 1440x900 (WXGA+)   | 19        | 3.78%   |
| 1680x1050 (WSXGA+) | 16        | 3.19%   |
| 1024x600           | 15        | 2.99%   |
| 1920x1200 (WUXGA)  | 12        | 2.39%   |
| 3840x2160 (4K)     | 10        | 1.99%   |
| 1360x768           | 6         | 1.2%    |
| 1024x768 (XGA)     | 6         | 1.2%    |
| 2560x1440 (QHD)    | 5         | 1%      |
| Unknown            | 4         | 0.8%    |
| 3840x1080          | 2         | 0.4%    |
| 3440x1440          | 2         | 0.4%    |
| 2560x1080          | 2         | 0.4%    |
| 1280x768           | 2         | 0.4%    |
| 7680x2160          | 1         | 0.2%    |
| 4240x1440          | 1         | 0.2%    |
| 2880x1800          | 1         | 0.2%    |
| 2736x1824          | 1         | 0.2%    |
| 2560x1600          | 1         | 0.2%    |
| 2256x1504          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 150       | 29.18%  |
| 14      | 41        | 7.98%   |
| 13      | 39        | 7.59%   |
| 17      | 37        | 7.2%    |
| Unknown | 31        | 6.03%   |
| 21      | 29        | 5.64%   |
| 23      | 27        | 5.25%   |
| 24      | 26        | 5.06%   |
| 19      | 23        | 4.47%   |
| 18      | 19        | 3.7%    |
| 27      | 18        | 3.5%    |
| 10      | 14        | 2.72%   |
| 20      | 11        | 2.14%   |
| 22      | 8         | 1.56%   |
| 12      | 8         | 1.56%   |
| 11      | 6         | 1.17%   |
| 72      | 5         | 0.97%   |
| 31      | 5         | 0.97%   |
| 54      | 2         | 0.39%   |
| 48      | 2         | 0.39%   |
| 34      | 2         | 0.39%   |
| 32      | 2         | 0.39%   |
| 16      | 2         | 0.39%   |
| 8       | 2         | 0.39%   |
| 65      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 33      | 1         | 0.19%   |
| 28      | 1         | 0.19%   |
| 26      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 222       | 43.79%  |
| 401-500     | 73        | 14.4%   |
| 501-600     | 64        | 12.62%  |
| 201-300     | 47        | 9.27%   |
| 351-400     | 45        | 8.88%   |
| Unknown     | 31        | 6.11%   |
| 601-700     | 7         | 1.38%   |
| 1001-1500   | 6         | 1.18%   |
| 701-800     | 5         | 0.99%   |
| 1501-2000   | 5         | 0.99%   |
| 101-200     | 2         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 328       | 67.63%  |
| 16/10   | 77        | 15.88%  |
| 5/4     | 32        | 6.6%    |
| Unknown | 27        | 5.57%   |
| 4/3     | 13        | 2.68%   |
| 3/2     | 4         | 0.82%   |
| 21/9    | 3         | 0.62%   |
| 32/9    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 148       | 28.85%  |
| 201-250        | 72        | 14.04%  |
| 81-90          | 64        | 12.48%  |
| 151-200        | 45        | 8.77%   |
| Unknown        | 31        | 6.04%   |
| 141-150        | 30        | 5.85%   |
| 301-350        | 19        | 3.7%    |
| 121-130        | 16        | 3.12%   |
| 71-80          | 15        | 2.92%   |
| 41-50          | 14        | 2.73%   |
| 251-300        | 11        | 2.14%   |
| More than 1000 | 10        | 1.95%   |
| 351-500        | 9         | 1.75%   |
| 61-70          | 7         | 1.36%   |
| 51-60          | 6         | 1.17%   |
| 131-140        | 5         | 0.97%   |
| 91-100         | 4         | 0.78%   |
| 111-120        | 3         | 0.58%   |
| 1-40           | 2         | 0.39%   |
| 501-1000       | 2         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 184       | 36.87%  |
| 101-120       | 158       | 31.66%  |
| 121-160       | 96        | 19.24%  |
| Unknown       | 31        | 6.21%   |
| 161-240       | 13        | 2.61%   |
| 1-50          | 12        | 2.4%    |
| More than 240 | 5         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 442       | 84.19%  |
| 2     | 54        | 10.29%  |
| 0     | 25        | 4.76%   |
| 3     | 4         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 291       | 35.49%  |
| Intel                                 | 186       | 22.68%  |
| Qualcomm Atheros                      | 126       | 15.37%  |
| Broadcom                              | 63        | 7.68%   |
| Marvell Technology Group              | 19        | 2.32%   |
| Broadcom Limited                      | 17        | 2.07%   |
| Ralink Technology                     | 16        | 1.95%   |
| Nvidia                                | 14        | 1.71%   |
| Samsung Electronics                   | 8         | 0.98%   |
| Ralink                                | 8         | 0.98%   |
| TP-Link                               | 6         | 0.73%   |
| Silicon Integrated Systems [SiS]      | 6         | 0.73%   |
| VIA Technologies                      | 5         | 0.61%   |
| JMicron Technology                    | 4         | 0.49%   |
| Huawei Technologies                   | 3         | 0.37%   |
| Ericsson Business Mobile Networks     | 3         | 0.37%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.24%   |
| Xiaomi                                | 2         | 0.24%   |
| Sitecom Europe                        | 2         | 0.24%   |
| Microsoft                             | 2         | 0.24%   |
| MediaTek                              | 2         | 0.24%   |
| Linksys                               | 2         | 0.24%   |
| DisplayLink                           | 2         | 0.24%   |
| AVM                                   | 2         | 0.24%   |
| Attansic Technology                   | 2         | 0.24%   |
| ASUSTek Computer                      | 2         | 0.24%   |
| AMD                                   | 2         | 0.24%   |
| ST-Ericsson                           | 1         | 0.12%   |
| Sierra Wireless                       | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.12%   |
| NetGear                               | 1         | 0.12%   |
| Microchip Technology                  | 1         | 0.12%   |
| Mercucys                              | 1         | 0.12%   |
| Mellanox Technologies                 | 1         | 0.12%   |
| Manta                                 | 1         | 0.12%   |
| LSI                                   | 1         | 0.12%   |
| Lenovo                                | 1         | 0.12%   |
| Intersil                              | 1         | 0.12%   |
| Hewlett-Packard                       | 1         | 0.12%   |
| Google                                | 1         | 0.12%   |
| Gemtek                                | 1         | 0.12%   |
| Edimax Technology                     | 1         | 0.12%   |
| Dell                                  | 1         | 0.12%   |
| Davicom Semiconductor                 | 1         | 0.12%   |
| D-Link System                         | 1         | 0.12%   |
| Cisco Aironet Wireless Communications | 1         | 0.12%   |
| Belkin Components                     | 1         | 0.12%   |
| Askey Computer                        | 1         | 0.12%   |
| ADMtek                                | 1         | 0.12%   |
| 3Com                                  | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 168       | 17.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 59        | 6.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 20        | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 18        | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 14        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 1.04%   |
| Intel Wireless 8265 / 8275                                              | 9         | 0.93%   |
| Intel Wireless 7260                                                     | 9         | 0.93%   |
| Intel WiFi Link 5100                                                    | 9         | 0.93%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 7         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.73%   |
| Nvidia MCP61 Ethernet                                                   | 7         | 0.73%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.62%   |
| Intel Wireless 3160                                                     | 6         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 5         | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 5         | 0.52%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 5         | 0.52%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 5         | 0.52%   |
| Intel Wireless 3165                                                     | 5         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.52%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.52%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.52%   |
| Intel 82579V Gigabit Network Connection                                 | 5         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 4         | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 4         | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 4         | 0.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.41%   |
| Intel Wireless 8260                                                     | 4         | 0.41%   |
| Intel Wireless 7265                                                     | 4         | 0.41%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                                    | 4         | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.41%   |
| Intel 82574L Gigabit Network Connection                                 | 4         | 0.41%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 0.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.41%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 125       | 29.48%  |
| Qualcomm Atheros                      | 101       | 23.82%  |
| Realtek Semiconductor                 | 97        | 22.88%  |
| Broadcom                              | 42        | 9.91%   |
| Ralink Technology                     | 16        | 3.77%   |
| Broadcom Limited                      | 9         | 2.12%   |
| Ralink                                | 8         | 1.89%   |
| TP-Link                               | 6         | 1.42%   |
| Sitecom Europe                        | 2         | 0.47%   |
| Microsoft                             | 2         | 0.47%   |
| Linksys                               | 2         | 0.47%   |
| AVM                                   | 2         | 0.47%   |
| ASUSTek Computer                      | 2         | 0.47%   |
| Sierra Wireless                       | 1         | 0.24%   |
| NetGear                               | 1         | 0.24%   |
| Mercucys                              | 1         | 0.24%   |
| MediaTek                              | 1         | 0.24%   |
| Marvell Technology Group              | 1         | 0.24%   |
| Edimax Technology                     | 1         | 0.24%   |
| D-Link System                         | 1         | 0.24%   |
| Cisco Aironet Wireless Communications | 1         | 0.24%   |
| Belkin Components                     | 1         | 0.24%   |
| Askey Computer                        | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 23        | 5.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 20        | 4.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 16        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 15        | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 14        | 3.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 14        | 3.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 12        | 2.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 12        | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 10        | 2.31%   |
| Intel Wireless 8265 / 8275                                                                    | 9         | 2.08%   |
| Intel Wireless 7260                                                                           | 9         | 2.08%   |
| Intel WiFi Link 5100                                                                          | 9         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                                           | 9         | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 7         | 1.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 6         | 1.39%   |
| Intel Wireless 3160                                                                           | 6         | 1.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 5         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                                               | 5         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 5         | 1.16%   |
| Intel Wireless 3165                                                                           | 5         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 1.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 5         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                                                | 5         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 4         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 4         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 4         | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 4         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 4         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 0.93%   |
| Intel Wireless 8260                                                                           | 4         | 0.93%   |
| Intel Wireless 7265                                                                           | 4         | 0.93%   |
| Intel Ultimate N WiFi Link 5300                                                               | 4         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 4         | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 4         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 4         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 4         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 3         | 0.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 3         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 3         | 0.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3         | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 3         | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 3         | 0.69%   |
| Realtek 802.11ac NIC                                                                          | 3         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                                 | 3         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2         | 0.46%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 0.46%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 2         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 2         | 0.46%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 2         | 0.46%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2         | 0.46%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.46%   |
| Ralink RT5370 Wireless Adapter                                                                | 2         | 0.46%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2         | 0.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 251       | 49.7%   |
| Intel                            | 106       | 20.99%  |
| Qualcomm Atheros                 | 39        | 7.72%   |
| Broadcom                         | 26        | 5.15%   |
| Marvell Technology Group         | 18        | 3.56%   |
| Nvidia                           | 14        | 2.77%   |
| Samsung Electronics              | 8         | 1.58%   |
| Broadcom Limited                 | 8         | 1.58%   |
| Silicon Integrated Systems [SiS] | 6         | 1.19%   |
| VIA Technologies                 | 5         | 0.99%   |
| JMicron Technology               | 4         | 0.79%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.4%    |
| Xiaomi                           | 2         | 0.4%    |
| Huawei Technologies              | 2         | 0.4%    |
| DisplayLink                      | 2         | 0.4%    |
| Attansic Technology              | 2         | 0.4%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.2%    |
| Microchip Technology             | 1         | 0.2%    |
| MediaTek                         | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| Hewlett-Packard                  | 1         | 0.2%    |
| Google                           | 1         | 0.2%    |
| Gemtek                           | 1         | 0.2%    |
| Davicom Semiconductor            | 1         | 0.2%    |
| ADMtek                           | 1         | 0.2%    |
| 3Com                             | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 168       | 32.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 59        | 11.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 3.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 14        | 2.73%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 7         | 1.36%   |
| Nvidia MCP61 Ethernet                                                          | 7         | 1.36%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 6         | 1.17%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 5         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.97%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 5         | 0.97%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 0.97%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 0.78%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 4         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.78%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 0.78%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 0.78%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 3         | 0.58%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.58%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.58%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 3         | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.58%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.39%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.39%   |
| Nvidia nForce2 Ethernet Controller                                             | 2         | 0.39%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.39%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.39%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.39%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 2         | 0.39%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.39%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.39%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.39%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.39%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.39%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.39%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.39%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 2         | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.39%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 2         | 0.39%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 2         | 0.39%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2         | 0.39%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.39%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 474       | 53.08%  |
| WiFi     | 399       | 44.68%  |
| Modem    | 16        | 1.79%   |
| Unknown  | 4         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 295       | 55.98%  |
| Ethernet | 232       | 44.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 313       | 60.31%  |
| 1     | 190       | 36.61%  |
| 3     | 6         | 1.16%   |
| 0     | 6         | 1.16%   |
| 4     | 4         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 437       | 82.61%  |
| Yes  | 92        | 17.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 30.25%  |
| Realtek Semiconductor           | 38        | 15.97%  |
| Qualcomm Atheros Communications | 23        | 9.66%   |
| Broadcom                        | 20        | 8.4%    |
| Cambridge Silicon Radio         | 14        | 5.88%   |
| Foxconn / Hon Hai               | 13        | 5.46%   |
| Hewlett-Packard                 | 10        | 4.2%    |
| Lite-On Technology              | 8         | 3.36%   |
| Dell                            | 8         | 3.36%   |
| Apple                           | 8         | 3.36%   |
| IMC Networks                    | 6         | 2.52%   |
| ASUSTek Computer                | 5         | 2.1%    |
| Toshiba                         | 3         | 1.26%   |
| Taiyo Yuden                     | 1         | 0.42%   |
| Realtek                         | 1         | 0.42%   |
| Ralink Technology               | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Qcom                            | 1         | 0.42%   |
| MediaTek                        | 1         | 0.42%   |
| Marvell Semiconductor           | 1         | 0.42%   |
| Foxconn International           | 1         | 0.42%   |
| Askey Computer                  | 1         | 0.42%   |
| Alps Electric                   | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 35        | 14.71%  |
| Realtek Bluetooth Radio                                                             | 19        | 7.98%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 17        | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 14        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 5.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 4.2%    |
| Intel AX200 Bluetooth                                                               | 9         | 3.78%   |
| Intel AX201 Bluetooth                                                               | 8         | 3.36%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 2.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.68%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.68%   |
| Intel Bluetooth Device                                                              | 3         | 1.26%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.26%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.26%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 1.26%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.26%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.26%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.26%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.84%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.84%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.84%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 0.84%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.84%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.84%   |
| Broadcom Bluetooth                                                                  | 2         | 0.84%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.84%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.84%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.84%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.84%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.84%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.42%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.42%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.42%   |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.42%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.42%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.42%   |
| Ralink CSR BS8510                                                                   | 1         | 0.42%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.42%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.42%   |
| MediaTek Wireless_Device                                                            | 1         | 0.42%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.42%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.42%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.42%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.42%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.42%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.42%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.42%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.42%   |
| Dell BT Mini-Receiver                                                               | 1         | 0.42%   |
| Broadcom HP Bluethunder                                                             | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 376       | 55.7%   |
| AMD                              | 127       | 18.81%  |
| Nvidia                           | 107       | 15.85%  |
| C-Media Electronics              | 14        | 2.07%   |
| VIA Technologies                 | 9         | 1.33%   |
| Silicon Integrated Systems [SiS] | 8         | 1.19%   |
| Generalplus Technology           | 5         | 0.74%   |
| GN Netcom                        | 4         | 0.59%   |
| Creative Labs                    | 4         | 0.59%   |
| Logitech                         | 3         | 0.44%   |
| Yamaha                           | 2         | 0.3%    |
| Texas Instruments                | 2         | 0.3%    |
| Tenx Technology                  | 2         | 0.3%    |
| JMTek                            | 2         | 0.3%    |
| Xilinx                           | 1         | 0.15%   |
| Realtek Semiconductor            | 1         | 0.15%   |
| Plantronics                      | 1         | 0.15%   |
| M-Audio                          | 1         | 0.15%   |
| GYROCOM C&C                      | 1         | 0.15%   |
| Focusrite-Novation               | 1         | 0.15%   |
| Evolution Electronics            | 1         | 0.15%   |
| Dell                             | 1         | 0.15%   |
| Creative Technology              | 1         | 0.15%   |
| Audioengine                      | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 55        | 7%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 38        | 4.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 36        | 4.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 4.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 4.07%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 3.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 25        | 3.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 1.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.53%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 1.53%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 1.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11        | 1.4%    |
| AMD High Definition Audio Controller                                                              | 11        | 1.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.02%   |
| Nvidia MCP61 High Definition Audio                                                                | 7         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 7         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 7         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.64%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 5         | 0.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 0.64%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.64%   |
| Generalplus Technology USB Audio Device                                                           | 5         | 0.64%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 5         | 0.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 0.64%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.64%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 5         | 0.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 0.64%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 4         | 0.51%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 4         | 0.51%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.51%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.51%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 4         | 0.51%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 0.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.51%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.51%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 25        | 19.08%  |
| Samsung Electronics          | 25        | 19.08%  |
| SK hynix                     | 24        | 18.32%  |
| Kingston                     | 16        | 12.21%  |
| Crucial                      | 8         | 6.11%   |
| Micron Technology            | 7         | 5.34%   |
| Nanya Technology             | 4         | 3.05%   |
| A-DATA Technology            | 4         | 3.05%   |
| Unknown (ABCD)               | 3         | 2.29%   |
| G.Skill                      | 3         | 2.29%   |
| Smart                        | 2         | 1.53%   |
| Ramaxel Technology           | 2         | 1.53%   |
| Corsair                      | 2         | 1.53%   |
| Transcend                    | 1         | 0.76%   |
| PLEXHD                       | 1         | 0.76%   |
| Patriot Memory (PDP Systems) | 1         | 0.76%   |
| Patriot                      | 1         | 0.76%   |
| Kingmax                      | 1         | 0.76%   |
| Exceleram                    | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 2.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.43%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.43%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.43%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 0.71%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.71%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.71%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.71%   |
| Unknown RAM Module 512MB DIMM 667MT/s                            | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.71%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.71%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR3                            | 1         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.71%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.71%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.71%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 0.71%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s               | 1         | 0.71%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.71%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 0.71%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 0.71%   |
| SK hynix RAM Module 512MB SODIMM DDR 533MT/s                     | 1         | 0.71%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.71%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.71%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.71%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 0.71%   |
| SK hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR 800MT/s          | 1         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 38.02%  |
| DDR3    | 43        | 35.54%  |
| DDR2    | 10        | 8.26%   |
| SDRAM   | 7         | 5.79%   |
| DDR     | 6         | 4.96%   |
| Unknown | 5         | 4.13%   |
| LPDDR4  | 4         | 3.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 63.87%  |
| DIMM         | 40        | 33.61%  |
| Row Of Chips | 3         | 2.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 44        | 34.11%  |
| 4096    | 36        | 27.91%  |
| 2048    | 25        | 19.38%  |
| 1024    | 10        | 7.75%   |
| 16384   | 7         | 5.43%   |
| 32768   | 3         | 2.33%   |
| 512     | 3         | 2.33%   |
| Unknown | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 29        | 23.02%  |
| 2667    | 17        | 13.49%  |
| 3200    | 16        | 12.7%   |
| 2400    | 11        | 8.73%   |
| 1333    | 10        | 7.94%   |
| 800     | 8         | 6.35%   |
| Unknown | 7         | 5.56%   |
| 667     | 5         | 3.97%   |
| 533     | 3         | 2.38%   |
| 2666    | 2         | 1.59%   |
| 2133    | 2         | 1.59%   |
| 2048    | 2         | 1.59%   |
| 975     | 2         | 1.59%   |
| 4267    | 1         | 0.79%   |
| 4199    | 1         | 0.79%   |
| 4000    | 1         | 0.79%   |
| 3800    | 1         | 0.79%   |
| 3500    | 1         | 0.79%   |
| 3400    | 1         | 0.79%   |
| 3266    | 1         | 0.79%   |
| 2267    | 1         | 0.79%   |
| 1866    | 1         | 0.79%   |
| 1200    | 1         | 0.79%   |
| 1067    | 1         | 0.79%   |
| 400     | 1         | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 41.18%  |
| Brother Industries  | 3         | 17.65%  |
| Samsung Electronics | 2         | 11.76%  |
| Canon               | 2         | 11.76%  |
| Seiko Epson         | 1         | 5.88%   |
| Ricoh               | 1         | 5.88%   |
| Konica Minolta      | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Brother MFC-L2685DW              | 2         | 11.76%  |
| Seiko Epson XP-3100 Series       | 1         | 5.88%   |
| Samsung SCX-3400 Series          | 1         | 5.88%   |
| Samsung ML-1670 Series           | 1         | 5.88%   |
| Ricoh SP C260SFNw                | 1         | 5.88%   |
| Konica Minolta 185               | 1         | 5.88%   |
| HP OfficeJet Pro 8730            | 1         | 5.88%   |
| HP LaserJet P1006                | 1         | 5.88%   |
| HP LaserJet 3050                 | 1         | 5.88%   |
| HP DeskJet F4200 series          | 1         | 5.88%   |
| HP DeskJet 2700 series           | 1         | 5.88%   |
| HP Deskjet 2540 series           | 1         | 5.88%   |
| HP Deskjet 1050 J410             | 1         | 5.88%   |
| Canon LaserShot LBP-1120 Printer | 1         | 5.88%   |
| Canon iP4200                     | 1         | 5.88%   |
| Brother HL-L2300D series         | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| HP ScanJet 3800c                              | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 19.79%  |
| IMC Networks                           | 24        | 8.48%   |
| Suyin                                  | 21        | 7.42%   |
| Microdia                               | 21        | 7.42%   |
| Sunplus Innovation Technology          | 20        | 7.07%   |
| Acer                                   | 20        | 7.07%   |
| Quanta                                 | 18        | 6.36%   |
| Realtek Semiconductor                  | 14        | 4.95%   |
| Logitech                               | 12        | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.83%   |
| Silicon Motion                         | 7         | 2.47%   |
| Apple                                  | 7         | 2.47%   |
| Syntek                                 | 6         | 2.12%   |
| Ricoh                                  | 6         | 2.12%   |
| Z-Star Microelectronics                | 5         | 1.77%   |
| Microsoft                              | 3         | 1.06%   |
| Lite-On Technology                     | 3         | 1.06%   |
| Importek                               | 3         | 1.06%   |
| ALi                                    | 3         | 1.06%   |
| Alcor Micro                            | 3         | 1.06%   |
| Sunplus Technology                     | 2         | 0.71%   |
| OmniVision Technologies                | 2         | 0.71%   |
| Lenovo                                 | 2         | 0.71%   |
| Generalplus Technology                 | 2         | 0.71%   |
| Xiongmai                               | 1         | 0.35%   |
| WCM_USB                                | 1         | 0.35%   |
| Unknown                                | 1         | 0.35%   |
| Service & Quality Technology           | 1         | 0.35%   |
| Samsung Electronics                    | 1         | 0.35%   |
| Nintendo                               | 1         | 0.35%   |
| MacroSilicon                           | 1         | 0.35%   |
| Luxvisions Innotech Limited            | 1         | 0.35%   |
| LG Electronics                         | 1         | 0.35%   |
| KYE Systems (Mouse Systems)            | 1         | 0.35%   |
| Intel                                  | 1         | 0.35%   |
| icSpring                               | 1         | 0.35%   |
| DJJHNA29IE70D3                         | 1         | 0.35%   |
| Creative Technology                    | 1         | 0.35%   |
| ARC International                      | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 9         | 3.17%   |
| Chicony Integrated Camera                                      | 8         | 2.82%   |
| Quanta HP Webcam                                               | 6         | 2.11%   |
| Chicony HD Webcam                                              | 6         | 2.11%   |
| Suyin HP TrueVision HD                                         | 5         | 1.76%   |
| Quanta HP TrueVision HD Camera                                 | 5         | 1.76%   |
| Logitech Webcam C270                                           | 5         | 1.76%   |
| Chicony HP TrueVision HD Camera                                | 5         | 1.76%   |
| Acer Integrated Camera                                         | 5         | 1.76%   |
| Acer HD Webcam                                                 | 5         | 1.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 4         | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 4         | 1.41%   |
| IMC Networks Integrated Camera                                 | 4         | 1.41%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 1.41%   |
| Chicony USB 2.0 Camera                                         | 4         | 1.41%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 4         | 1.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 3         | 1.06%   |
| Suyin 1.3M HD WebCam                                           | 3         | 1.06%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 3         | 1.06%   |
| Sunplus HP TrueVision HD Camera                                | 3         | 1.06%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 3         | 1.06%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 1.06%   |
| Quanta VGA WebCam                                              | 3         | 1.06%   |
| Microdia Integrated Webcam HD                                  | 3         | 1.06%   |
| Chicony 2.0M UVC Webcam / CNF7129                              | 3         | 1.06%   |
| Apple Built-in iSight                                          | 3         | 1.06%   |
| Alcor Micro USB 2.0 PC cam                                     | 3         | 1.06%   |
| Acer Lenovo EasyCamera                                         | 3         | 1.06%   |
| Z-Star Venus USB2.0 Camera                                     | 2         | 0.7%    |
| Syntek Sonix USB 2.0 Camera                                    | 2         | 0.7%    |
| Syntek Integrated Camera                                       | 2         | 0.7%    |
| Suyin HP Webcam                                                | 2         | 0.7%    |
| Suyin HD WebCam                                                | 2         | 0.7%    |
| Suyin HD Video WebCam                                          | 2         | 0.7%    |
| Suyin Acer CrystalEye Webcam                                   | 2         | 0.7%    |
| Sunplus Laptop Integrated WebCam HD                            | 2         | 0.7%    |
| Sunplus HD Webcam                                              | 2         | 0.7%    |
| Silicon Motion WebCam SCB-0385N                                | 2         | 0.7%    |
| Silicon Motion WebCam SC-0311139N                              | 2         | 0.7%    |
| Silicon Motion HP Webcam-101                                   | 2         | 0.7%    |
| Ricoh Sony Visual Communication Camera                         | 2         | 0.7%    |
| Realtek HP Truevision HD integrated webcam                     | 2         | 0.7%    |
| Microsoft LifeCam HD-3000                                      | 2         | 0.7%    |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 0.7%    |
| Logitech Webcam C310                                           | 2         | 0.7%    |
| Importek TOSHIBA Web Camera - HD                               | 2         | 0.7%    |
| IMC Networks USB 2.0 UVC VGA WebCam                            | 2         | 0.7%    |
| IMC Networks Integrated Webcam                                 | 2         | 0.7%    |
| IMC Networks EasyCamera                                        | 2         | 0.7%    |
| Chicony TOSHIBA Web Camera - HD                                | 2         | 0.7%    |
| Chicony HD WebCam (Acer)                                       | 2         | 0.7%    |
| Chicony EasyCamera                                             | 2         | 0.7%    |
| Chicony 1.3M Webcam                                            | 2         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 0.7%    |
| ALi Gateway Webcam                                             | 2         | 0.7%    |
| Acer USB2.0 Camera                                             | 2         | 0.7%    |
| Z-Star Namuga 1.3M Webcam                                      | 1         | 0.35%   |
| Z-Star Lenovo ThinkCentre Web Camera                           | 1         | 0.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 38.1%   |
| AuthenTec                  | 8         | 19.05%  |
| Synaptics                  | 4         | 9.52%   |
| STMicroelectronics         | 4         | 9.52%   |
| LighTuning Technology      | 3         | 7.14%   |
| Elan Microelectronics      | 3         | 7.14%   |
| Upek                       | 1         | 2.38%   |
| Shenzhen Goodix Technology | 1         | 2.38%   |
| Samsung Electronics        | 1         | 2.38%   |
| Focal-systems.Corp         | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 9.52%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 9.52%   |
| Validity Sensors VFS301 Fingerprint Reader             | 3         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 3         | 7.14%   |
| Unknown                                                | 3         | 7.14%   |
| Validity Sensors VFS491                                | 2         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 4.76%   |
| AuthenTec Fingerprint Sensor                           | 2         | 4.76%   |
| AuthenTec AES2810                                      | 2         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.76%   |
| AuthenTec AES1600                                      | 2         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 2.38%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.38%   |
| Validity Sensors Synaptics WBDI                        | 1         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.38%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.38%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 2.38%   |
| Samsung Fingerprint Sensor Device - 730B               | 1         | 2.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.38%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 13        | 56.52%  |
| O2 Micro                          | 3         | 13.04%  |
| Alcor Micro                       | 2         | 8.7%    |
| VASCO Data Security International | 1         | 4.35%   |
| OmniKey                           | 1         | 4.35%   |
| Lenovo                            | 1         | 4.35%   |
| Jing-Mold Enterprise              | 1         | 4.35%   |
| Gemalto (was Gemplus)             | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 30.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 13.04%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.7%    |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 8.7%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 4.35%   |
| OmniKey CardMan 1021                                                         | 1         | 4.35%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.35%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 4.35%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 4.35%   |
| Broadcom 5880                                                                | 1         | 4.35%   |
| Broadcom 58200                                                               | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 343       | 65.09%  |
| 1     | 145       | 27.51%  |
| 2     | 25        | 4.74%   |
| 3     | 11        | 2.09%   |
| 4     | 2         | 0.38%   |
| 6     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 72        | 31.58%  |
| Net/wireless             | 45        | 19.74%  |
| Fingerprint reader       | 41        | 17.98%  |
| Multimedia controller    | 19        | 8.33%   |
| Chipcard                 | 19        | 8.33%   |
| Communication controller | 10        | 4.39%   |
| Storage                  | 6         | 2.63%   |
| Network                  | 3         | 1.32%   |
| Unassigned class         | 2         | 0.88%   |
| Net/ethernet             | 2         | 0.88%   |
| Flash memory             | 2         | 0.88%   |
| Camera                   | 2         | 0.88%   |
| Storage/ide              | 1         | 0.44%   |
| Sound                    | 1         | 0.44%   |
| Modem                    | 1         | 0.44%   |
| Dvb card                 | 1         | 0.44%   |
| Bluetooth                | 1         | 0.44%   |

