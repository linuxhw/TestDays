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

Total: 185

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
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
| 5.10.0-14-amd64      | 30        | 21.13%  |
| 5.10.0-13-amd64      | 27        | 19.01%  |
| 5.10.0-12-amd64      | 26        | 18.31%  |
| 5.10.0-15-amd64      | 18        | 12.68%  |
| 5.10.0-16-amd64      | 13        | 9.15%   |
| 5.10.0-17-amd64      | 9         | 6.34%   |
| 5.10.0-13-686        | 6         | 4.23%   |
| 5.18.0-0.bpo.1-amd64 | 4         | 2.82%   |
| 5.16.0-0.bpo.4-amd64 | 3         | 2.11%   |
| 5.18.0-4-amd64       | 1         | 0.7%    |
| 5.18.0-3-amd64       | 1         | 0.7%    |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.7%    |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.7%    |
| 5.10.0-14-686        | 1         | 0.7%    |
| 5.10.0-11-686        | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 126       | 92.65%  |
| 5.18.0  | 6         | 4.41%   |
| 5.16.0  | 3         | 2.21%   |
| 5.15.0  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 126       | 92.65%  |
| 5.18    | 6         | 4.41%   |
| 5.16    | 3         | 2.21%   |
| 5.15    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 127       | 94.07%  |
| i686   | 8         | 5.93%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 122       | 90.37%  |
| Cinnamon   | 9         | 6.67%   |
| MATE       | 2         | 1.48%   |
| XFCE       | 1         | 0.74%   |
| Unknown    | 1         | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 135       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 60.74%  |
| LightDM | 53        | 39.26%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 54        | 40%     |
| de_DE | 13        | 9.63%   |
| ru_RU | 11        | 8.15%   |
| pt_BR | 8         | 5.93%   |
| en_GB | 8         | 5.93%   |
| es_ES | 6         | 4.44%   |
| fr_FR | 5         | 3.7%    |
| pl_PL | 4         | 2.96%   |
| it_IT | 3         | 2.22%   |
| es_MX | 3         | 2.22%   |
| fr_CA | 2         | 1.48%   |
| es_BO | 2         | 1.48%   |
| en_IE | 2         | 1.48%   |
| en_CA | 2         | 1.48%   |
| pt_PT | 1         | 0.74%   |
| nn_NO | 1         | 0.74%   |
| nl_AW | 1         | 0.74%   |
| ko_KR | 1         | 0.74%   |
| hu_HU | 1         | 0.74%   |
| fr_BE | 1         | 0.74%   |
| es_PE | 1         | 0.74%   |
| es_NI | 1         | 0.74%   |
| es_EC | 1         | 0.74%   |
| es_CR | 1         | 0.74%   |
| en_AU | 1         | 0.74%   |
| ar_EG | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 84        | 62.22%  |
| BIOS | 51        | 37.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 124       | 91.85%  |
| Overlay | 6         | 4.44%   |
| Tmpfs   | 4         | 2.96%   |
| Xfs     | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 60.74%  |
| GPT     | 43        | 31.85%  |
| MBR     | 10        | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 91.18%  |
| Yes       | 12        | 8.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 87.41%  |
| Yes       | 17        | 12.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 20%     |
| Dell                | 21        | 15.56%  |
| Lenovo              | 18        | 13.33%  |
| ASUSTek Computer    | 15        | 11.11%  |
| Acer                | 12        | 8.89%   |
| MSI                 | 8         | 5.93%   |
| Gigabyte Technology | 5         | 3.7%    |
| Apple               | 5         | 3.7%    |
| Toshiba             | 2         | 1.48%   |
| Sony                | 2         | 1.48%   |
| ASRock              | 2         | 1.48%   |
| Wortmann AG         | 1         | 0.74%   |
| Samsung Electronics | 1         | 0.74%   |
| Philco              | 1         | 0.74%   |
| Panasonic           | 1         | 0.74%   |
| Packard Bell        | 1         | 0.74%   |
| Multilaser          | 1         | 0.74%   |
| Microtech           | 1         | 0.74%   |
| Medion              | 1         | 0.74%   |
| LincPlus            | 1         | 0.74%   |
| Intel               | 1         | 0.74%   |
| Howard Computers    | 1         | 0.74%   |
| Google              | 1         | 0.74%   |
| Framework           | 1         | 0.74%   |
| Dynabook            | 1         | 0.74%   |
| Dixonsxp            | 1         | 0.74%   |
| AMI                 | 1         | 0.74%   |
| Alienware           | 1         | 0.74%   |
| Unknown             | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| HP Laptop 15z-ef2xxx                             | 2         | 1.48%   |
| Dell Latitude E6400                              | 2         | 1.48%   |
| Dell Latitude E5540                              | 2         | 1.48%   |
| Unknown                                          | 2         | 1.48%   |
| Wortmann AG TERRA_MOBILE_1713A                   | 1         | 0.74%   |
| Toshiba Satellite M55                            | 1         | 0.74%   |
| Toshiba Satellite L455                           | 1         | 0.74%   |
| Sony SVE1713Y1RB                                 | 1         | 0.74%   |
| Sony SVE1512G1RW                                 | 1         | 0.74%   |
| Samsung 730QDA                                   | 1         | 0.74%   |
| Philco 10D                                       | 1         | 0.74%   |
| Panasonic CF-H2BJJHZDE                           | 1         | 0.74%   |
| Packard Bell DOT S                               | 1         | 0.74%   |
| Multilaser PC150                                 | 1         | 0.74%   |
| MSI U180                                         | 1         | 0.74%   |
| MSI MS-7B79                                      | 1         | 0.74%   |
| MSI MS-7B17                                      | 1         | 0.74%   |
| MSI MS-7984                                      | 1         | 0.74%   |
| MSI MS-7977                                      | 1         | 0.74%   |
| MSI MS-7974                                      | 1         | 0.74%   |
| MSI MS-7851                                      | 1         | 0.74%   |
| MSI GL73 8SE                                     | 1         | 0.74%   |
| Microtech ebookPro                               | 1         | 0.74%   |
| Medion E6220                                     | 1         | 0.74%   |
| LincPlus LINNCPLUS P1                            | 1         | 0.74%   |
| Lenovo Z50-70 20354                              | 1         | 0.74%   |
| Lenovo Yoga 7 15ITL5 82BJ                        | 1         | 0.74%   |
| Lenovo V55t-15ARE 11KJ0036TX                     | 1         | 0.74%   |
| Lenovo ThinkPad T61 7661A16                      | 1         | 0.74%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 0.74%   |
| Lenovo ThinkPad T470s 20HF0047UK                 | 1         | 0.74%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS            | 1         | 0.74%   |
| Lenovo ThinkPad T450 20BUS0QT04                  | 1         | 0.74%   |
| Lenovo ThinkPad E14 Gen 2 20TACTO1WW             | 1         | 0.74%   |
| Lenovo ThinkCentre M92p 3238E9U                  | 1         | 0.74%   |
| Lenovo ThinkCentre M720s 10SUS9KW00              | 1         | 0.74%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 0.74%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS                | 1         | 0.74%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 0.74%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 0.74%   |
| Lenovo IdeaPad 3 15ADA05 81W1                    | 1         | 0.74%   |
| Lenovo IdeaPad 3 14ALC6 82KT                     | 1         | 0.74%   |
| Lenovo G500 20236                                | 1         | 0.74%   |
| Intel DQ77MK AAG39642-400                        | 1         | 0.74%   |
| Howard Computers R7X                             | 1         | 0.74%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 0.74%   |
| HP Z820 Workstation                              | 1         | 0.74%   |
| HP Z600 Workstation                              | 1         | 0.74%   |
| HP ProBook 6570b                                 | 1         | 0.74%   |
| HP ProBook 450 G8 Notebook PC                    | 1         | 0.74%   |
| HP Presario C500 (GF581UA#ABA)                   | 1         | 0.74%   |
| HP Pavilion Laptop 15-eh1xxx                     | 1         | 0.74%   |
| HP Pavilion Desktop 590-p0xxx                    | 1         | 0.74%   |
| HP Pavilion 17                                   | 1         | 0.74%   |
| HP Notebook                                      | 1         | 0.74%   |
| HP Laptop 15s-eq2xxx                             | 1         | 0.74%   |
| HP Laptop 15-dy2xxx                              | 1         | 0.74%   |
| HP Laptop 15-bw0xx                               | 1         | 0.74%   |
| HP Laptop 14-dk1xxx                              | 1         | 0.74%   |
| HP Laptop 14-df0xxx                              | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 9         | 6.67%   |
| HP Laptop              | 8         | 5.93%   |
| Dell Latitude          | 7         | 5.19%   |
| Lenovo ThinkPad        | 6         | 4.44%   |
| Dell Inspiron          | 6         | 4.44%   |
| Lenovo IdeaPad         | 4         | 2.96%   |
| HP Pavilion            | 3         | 2.22%   |
| HP Compaq              | 3         | 2.22%   |
| ASUS VivoBook          | 3         | 2.22%   |
| ASUS PRIME             | 3         | 2.22%   |
| Toshiba Satellite      | 2         | 1.48%   |
| Lenovo ThinkCentre     | 2         | 1.48%   |
| HP ProBook             | 2         | 1.48%   |
| HP EliteBook           | 2         | 1.48%   |
| HP 255                 | 2         | 1.48%   |
| Dell XPS               | 2         | 1.48%   |
| Dell Vostro            | 2         | 1.48%   |
| Dell Precision         | 2         | 1.48%   |
| Dell OptiPlex          | 2         | 1.48%   |
| Unknown                | 2         | 1.48%   |
| Wortmann AG TERRA      | 1         | 0.74%   |
| Sony SVE1713Y1RB       | 1         | 0.74%   |
| Sony SVE1512G1RW       | 1         | 0.74%   |
| Samsung 730QDA         | 1         | 0.74%   |
| Philco 10D             | 1         | 0.74%   |
| Panasonic CF-H2BJJHZDE | 1         | 0.74%   |
| Packard Bell DOT       | 1         | 0.74%   |
| Multilaser PC150       | 1         | 0.74%   |
| MSI U180               | 1         | 0.74%   |
| MSI MS-7B79            | 1         | 0.74%   |
| MSI MS-7B17            | 1         | 0.74%   |
| MSI MS-7984            | 1         | 0.74%   |
| MSI MS-7977            | 1         | 0.74%   |
| MSI MS-7974            | 1         | 0.74%   |
| MSI MS-7851            | 1         | 0.74%   |
| MSI GL73               | 1         | 0.74%   |
| Microtech ebookPro     | 1         | 0.74%   |
| Medion E6220           | 1         | 0.74%   |
| LincPlus LINNCPLUS     | 1         | 0.74%   |
| Lenovo Z50-70          | 1         | 0.74%   |
| Lenovo Yoga            | 1         | 0.74%   |
| Lenovo V55t-15ARE      | 1         | 0.74%   |
| Lenovo Legion          | 1         | 0.74%   |
| Lenovo IdeaPadFlex     | 1         | 0.74%   |
| Lenovo G500            | 1         | 0.74%   |
| Intel DQ77MK           | 1         | 0.74%   |
| Howard Computers R7X   | 1         | 0.74%   |
| HP ZBook               | 1         | 0.74%   |
| HP Z820                | 1         | 0.74%   |
| HP Z600                | 1         | 0.74%   |
| HP Presario            | 1         | 0.74%   |
| HP Notebook            | 1         | 0.74%   |
| HP ENVY                | 1         | 0.74%   |
| HP 14                  | 1         | 0.74%   |
| Google Akemi           | 1         | 0.74%   |
| Gigabyte Z68A-D3H-B3   | 1         | 0.74%   |
| Gigabyte H110M-S2H     | 1         | 0.74%   |
| Gigabyte B85M-DS3H-A   | 1         | 0.74%   |
| Gigabyte B450M         | 1         | 0.74%   |
| Gigabyte B450          | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 21        | 15.56%  |
| 2012 | 14        | 10.37%  |
| 2020 | 12        | 8.89%   |
| 2018 | 11        | 8.15%   |
| 2013 | 11        | 8.15%   |
| 2019 | 8         | 5.93%   |
| 2017 | 8         | 5.93%   |
| 2015 | 8         | 5.93%   |
| 2016 | 7         | 5.19%   |
| 2009 | 7         | 5.19%   |
| 2014 | 6         | 4.44%   |
| 2010 | 6         | 4.44%   |
| 2008 | 5         | 3.7%    |
| 2007 | 5         | 3.7%    |
| 2011 | 4         | 2.96%   |
| 2022 | 1         | 0.74%   |
| 2006 | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 94        | 69.63%  |
| Desktop     | 34        | 25.19%  |
| Convertible | 3         | 2.22%   |
| All in one  | 2         | 1.48%   |
| Tablet      | 1         | 0.74%   |
| Mini pc     | 1         | 0.74%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 120       | 87.59%  |
| Enabled  | 17        | 12.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 134       | 99.26%  |
| Yes  | 1         | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 36        | 26.47%  |
| 3.01-4.0    | 30        | 22.06%  |
| 16.01-24.0  | 24        | 17.65%  |
| 8.01-16.0   | 20        | 14.71%  |
| 1.01-2.0    | 10        | 7.35%   |
| 32.01-64.0  | 7         | 5.15%   |
| 2.01-3.0    | 4         | 2.94%   |
| 24.01-32.0  | 3         | 2.21%   |
| 64.01-256.0 | 2         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 54        | 38.85%  |
| 2.01-3.0   | 48        | 34.53%  |
| 3.01-4.0   | 15        | 10.79%  |
| 4.01-8.0   | 12        | 8.63%   |
| 0.51-1.0   | 8         | 5.76%   |
| 32.01-64.0 | 1         | 0.72%   |
| 8.01-16.0  | 1         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 68.38%  |
| 2      | 26        | 19.12%  |
| 3      | 12        | 8.82%   |
| 4      | 4         | 2.94%   |
| 6      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 62.96%  |
| Yes       | 50        | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 80.74%  |
| No        | 26        | 19.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 83.7%   |
| No        | 22        | 16.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 59.26%  |
| No        | 55        | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 25        | 18.25%  |
| Germany     | 13        | 9.49%   |
| Russia      | 12        | 8.76%   |
| UK          | 11        | 8.03%   |
| Brazil      | 10        | 7.3%    |
| Canada      | 7         | 5.11%   |
| Spain       | 6         | 4.38%   |
| Poland      | 6         | 4.38%   |
| France      | 6         | 4.38%   |
| Italy       | 5         | 3.65%   |
| Mexico      | 4         | 2.92%   |
| Vietnam     | 2         | 1.46%   |
| Romania     | 2         | 1.46%   |
| Hungary     | 2         | 1.46%   |
| Chile       | 2         | 1.46%   |
| Bolivia     | 2         | 1.46%   |
| Belgium     | 2         | 1.46%   |
| Australia   | 2         | 1.46%   |
| Venezuela   | 1         | 0.73%   |
| Turkey      | 1         | 0.73%   |
| Sweden      | 1         | 0.73%   |
| South Korea | 1         | 0.73%   |
| Portugal    | 1         | 0.73%   |
| Peru        | 1         | 0.73%   |
| Paraguay    | 1         | 0.73%   |
| Norway      | 1         | 0.73%   |
| Nicaragua   | 1         | 0.73%   |
| Malaysia    | 1         | 0.73%   |
| Lithuania   | 1         | 0.73%   |
| Latvia      | 1         | 0.73%   |
| Kenya       | 1         | 0.73%   |
| Ireland     | 1         | 0.73%   |
| Ecuador     | 1         | 0.73%   |
| Costa Rica  | 1         | 0.73%   |
| Belarus     | 1         | 0.73%   |
| Austria     | 1         | 0.73%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Moscow                   | 4         | 2.92%   |
| Oruro                    | 2         | 1.46%   |
| Neasden                  | 2         | 1.46%   |
| Montreal                 | 2         | 1.46%   |
| Melbourne                | 2         | 1.46%   |
| Krakow                   | 2         | 1.46%   |
| Zaragoza                 | 1         | 0.73%   |
| Wroclaw                  | 1         | 0.73%   |
| Voronezh                 | 1         | 0.73%   |
| Vitória da Conquista    | 1         | 0.73%   |
| Vincennes                | 1         | 0.73%   |
| Vilshofen                | 1         | 0.73%   |
| Vilnius                  | 1         | 0.73%   |
| Viet Tri                 | 1         | 0.73%   |
| Vicente Guerrero         | 1         | 0.73%   |
| Veurne                   | 1         | 0.73%   |
| Vaslui                   | 1         | 0.73%   |
| Vancouver                | 1         | 0.73%   |
| Valsoyfjord              | 1         | 0.73%   |
| Uiwang                   | 1         | 0.73%   |
| Tula                     | 1         | 0.73%   |
| Troisdorf                | 1         | 0.73%   |
| Trieste                  | 1         | 0.73%   |
| Toulouse                 | 1         | 0.73%   |
| Toronto                  | 1         | 0.73%   |
| Toledo                   | 1         | 0.73%   |
| Tipton                   | 1         | 0.73%   |
| Tacoma                   | 1         | 0.73%   |
| Stockbridge              | 1         | 0.73%   |
| Spruce Grove             | 1         | 0.73%   |
| Spearfish                | 1         | 0.73%   |
| Smolensk                 | 1         | 0.73%   |
| Scarborough              | 1         | 0.73%   |
| Saratov                  | 1         | 0.73%   |
| Sao Paulo                | 1         | 0.73%   |
| Santiago                 | 1         | 0.73%   |
| Sant Feliu de Llobregat  | 1         | 0.73%   |
| San Jose                 | 1         | 0.73%   |
| San Antonio de Los Altos | 1         | 0.73%   |
| San Antonio              | 1         | 0.73%   |
| Rottenburg               | 1         | 0.73%   |
| Rome                     | 1         | 0.73%   |
| Rochester                | 1         | 0.73%   |
| Riga                     | 1         | 0.73%   |
| Recife                   | 1         | 0.73%   |
| Queens                   | 1         | 0.73%   |
| Providencia              | 1         | 0.73%   |
| Prestatyn                | 1         | 0.73%   |
| Porto Uniao              | 1         | 0.73%   |
| Porto Alegre             | 1         | 0.73%   |
| Piaseczno                | 1         | 0.73%   |
| Peterborough             | 1         | 0.73%   |
| Petaling Jaya            | 1         | 0.73%   |
| Orekhovo-Zuyevo          | 1         | 0.73%   |
| Ordonnac                 | 1         | 0.73%   |
| Nuremberg                | 1         | 0.73%   |
| Nottingham               | 1         | 0.73%   |
| National City            | 1         | 0.73%   |
| Naples                   | 1         | 0.73%   |
| Nairobi                  | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 29        | 39     | 15.93%  |
| Seagate                        | 23        | 26     | 12.64%  |
| Samsung Electronics            | 21        | 25     | 11.54%  |
| SanDisk                        | 10        | 10     | 5.49%   |
| Unknown                        | 9         | 13     | 4.95%   |
| Toshiba                        | 9         | 10     | 4.95%   |
| Kingston                       | 9         | 9      | 4.95%   |
| Hitachi                        | 9         | 10     | 4.95%   |
| Intel                          | 6         | 6      | 3.3%    |
| Crucial                        | 5         | 5      | 2.75%   |
| Apple                          | 4         | 9      | 2.2%    |
| PNY                            | 3         | 3      | 1.65%   |
| Patriot                        | 3         | 3      | 1.65%   |
| Micron Technology              | 3         | 3      | 1.65%   |
| A-DATA Technology              | 3         | 3      | 1.65%   |
| Team                           | 2         | 2      | 1.1%    |
| SK hynix                       | 2         | 2      | 1.1%    |
| Phison                         | 2         | 2      | 1.1%    |
| KingSpec                       | 2         | 2      | 1.1%    |
| HGST                           | 2         | 2      | 1.1%    |
| XrayDisk                       | 1         | 2      | 0.55%   |
| Transcend                      | 1         | 2      | 0.55%   |
| SSD PHIS                       | 1         | 1      | 0.55%   |
| SPCC                           | 1         | 1      | 0.55%   |
| Solid State Storage Technology | 1         | 1      | 0.55%   |
| ShiJi                          | 1         | 1      | 0.55%   |
| SABRENT                        | 1         | 1      | 0.55%   |
| Oyen                           | 1         | 1      | 0.55%   |
| ORICO                          | 1         | 1      | 0.55%   |
| OCZ-VERTEX                     | 1         | 1      | 0.55%   |
| Netac                          | 1         | 1      | 0.55%   |
| Microtech                      | 1         | 2      | 0.55%   |
| Micron/Crucial Technology      | 1         | 2      | 0.55%   |
| LITEON                         | 1         | 1      | 0.55%   |
| KIOXIA                         | 1         | 4      | 0.55%   |
| Initio                         | 1         | 1      | 0.55%   |
| HXY                            | 1         | 1      | 0.55%   |
| Hewlett-Packard                | 1         | 1      | 0.55%   |
| GOODRAM                        | 1         | 1      | 0.55%   |
| Fujitsu                        | 1         | 1      | 0.55%   |
| FORESEE                        | 1         | 1      | 0.55%   |
| China                          | 1         | 2      | 0.55%   |
| BHT                            | 1         | 2      | 0.55%   |
| Acer                           | 1         | 1      | 0.55%   |
| 2.5''                          | 1         | 1      | 0.55%   |
| Unknown                        | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 128GB          | 3         | 1.54%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.54%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 1.54%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.54%   |
| Micron NVMe SSD Drive 512GB          | 3         | 1.54%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.54%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.54%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 1.54%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 1.03%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 1.03%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 1.03%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 1.03%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.03%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.03%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.03%   |
| SanDisk SDSSDA240G 240GB             | 2         | 1.03%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.03%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.03%   |
| Samsung PM991a NVMe 512GB            | 2         | 1.03%   |
| Patriot Burst 240GB SSD              | 2         | 1.03%   |
| Apple SSD SD0128F 121GB              | 2         | 1.03%   |
| A-DATA SU650 120GB SSD               | 2         | 1.03%   |
| XrayDisk 480GB                       | 1         | 0.51%   |
| XrayDisk 1TB                         | 1         | 0.51%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.51%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.51%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.51%   |
| WDC WD60EZAZ-00ZGHB0 6TB             | 1         | 0.51%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.51%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.51%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.51%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.51%   |
| WDC WD3200AAJS-22B4A0 320GB          | 1         | 0.51%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.51%   |
| WDC WD3003FZEX-00Z4SA0 3TB           | 1         | 0.51%   |
| WDC WD30 EFRX-68EUZN0 3TB            | 1         | 0.51%   |
| WDC WD1600HLHX-60JJPV1 160GB         | 1         | 0.51%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.51%   |
| WDC WD1600AAJS-07PSA0 160GB          | 1         | 0.51%   |
| WDC WD10SPZX-60Z10T1 1TB             | 1         | 0.51%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 0.51%   |
| WDC WD10EZEX-22BN5A0 1TB             | 1         | 0.51%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 0.51%   |
| WDC WD10EFRX-68FYTN0 1TB             | 1         | 0.51%   |
| WDC WD10EAVS-00D7B0 1TB              | 1         | 0.51%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 1         | 0.51%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.51%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.51%   |
| Unknown USB DISK 3.2 1TB             | 1         | 0.51%   |
| Unknown SP32G  32GB                  | 1         | 0.51%   |
| Unknown SC128  128GB                 | 1         | 0.51%   |
| Unknown MMC Card  64GB               | 1         | 0.51%   |
| Unknown MMC Card  32GB               | 1         | 0.51%   |
| Unknown Biwin  64GB                  | 1         | 0.51%   |
| Unknown Biwin  32GB                  | 1         | 0.51%   |
| Transcend TS480GSSD220S 480GB        | 1         | 0.51%   |
| Transcend TS240GSSD220S 240GB        | 1         | 0.51%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.51%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 32     | 32.39%  |
| Seagate             | 23        | 26     | 32.39%  |
| Hitachi             | 9         | 10     | 12.68%  |
| Toshiba             | 8         | 9      | 11.27%  |
| Unknown             | 3         | 3      | 4.23%   |
| HGST                | 2         | 2      | 2.82%   |
| Samsung Electronics | 1         | 1      | 1.41%   |
| SABRENT             | 1         | 1      | 1.41%   |
| Fujitsu             | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 14.52%  |
| Kingston            | 8         | 8      | 12.9%   |
| Crucial             | 5         | 5      | 8.06%   |
| SanDisk             | 3         | 3      | 4.84%   |
| PNY                 | 3         | 3      | 4.84%   |
| Patriot             | 3         | 3      | 4.84%   |
| Intel               | 3         | 3      | 4.84%   |
| Apple               | 3         | 3      | 4.84%   |
| A-DATA Technology   | 3         | 3      | 4.84%   |
| Team                | 2         | 2      | 3.23%   |
| KingSpec            | 2         | 2      | 3.23%   |
| WDC                 | 1         | 1      | 1.61%   |
| Transcend           | 1         | 2      | 1.61%   |
| SSD PHIS            | 1         | 1      | 1.61%   |
| SK hynix            | 1         | 1      | 1.61%   |
| ORICO               | 1         | 1      | 1.61%   |
| OCZ-VERTEX          | 1         | 1      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| Microtech           | 1         | 2      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| HXY                 | 1         | 1      | 1.61%   |
| Hewlett-Packard     | 1         | 1      | 1.61%   |
| GOODRAM             | 1         | 1      | 1.61%   |
| FORESEE             | 1         | 1      | 1.61%   |
| China               | 1         | 2      | 1.61%   |
| BHT                 | 1         | 2      | 1.61%   |
| Acer                | 1         | 1      | 1.61%   |
| 2.5''               | 1         | 1      | 1.61%   |
| Unknown             | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 63        | 85     | 37.72%  |
| SSD     | 57        | 67     | 34.13%  |
| NVMe    | 36        | 51     | 21.56%  |
| MMC     | 6         | 9      | 3.59%   |
| Unknown | 5         | 7      | 2.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 148    | 67.76%  |
| NVMe | 36        | 51     | 23.68%  |
| SAS  | 7         | 11     | 4.61%   |
| MMC  | 6         | 9      | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 102    | 67.5%   |
| 0.51-1.0   | 29        | 36     | 24.17%  |
| 1.01-2.0   | 5         | 6      | 4.17%   |
| 2.01-3.0   | 3         | 6      | 2.5%    |
| 4.01-10.0  | 2         | 2      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 43        | 31.62%  |
| 251-500        | 30        | 22.06%  |
| 501-1000       | 14        | 10.29%  |
| 1001-2000      | 12        | 8.82%   |
| 51-100         | 12        | 8.82%   |
| 1-20           | 9         | 6.62%   |
| 21-50          | 7         | 5.15%   |
| More than 3000 | 5         | 3.68%   |
| 2001-3000      | 4         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 66        | 47.14%  |
| 21-50          | 28        | 20%     |
| 51-100         | 15        | 10.71%  |
| 101-250        | 11        | 7.86%   |
| 251-500        | 7         | 5%      |
| 501-1000       | 7         | 5%      |
| 1001-2000      | 3         | 2.14%   |
| 2001-3000      | 2         | 1.43%   |
| More than 3000 | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB    | 1         | 1      | 12.5%   |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 12.5%   |
| Seagate ST3250318AS 250GB       | 1         | 1      | 12.5%   |
| Phison ES 512GB                 | 1         | 1      | 12.5%   |
| Intel SSDSCKKF256G8 SATA 256GB  | 1         | 1      | 12.5%   |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 12.5%   |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 28.57%  |
| WDC     | 1         | 2      | 14.29%  |
| Phison  | 1         | 1      | 14.29%  |
| Intel   | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 2      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 71.43%  |
| NVMe | 1         | 1      | 14.29%  |
| SSD  | 1         | 1      | 14.29%  |

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
| Detected | 90        | 140    | 61.22%  |
| Works    | 50        | 71     | 34.01%  |
| Malfunc  | 7         | 8      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 94        | 57.32%  |
| AMD                            | 26        | 15.85%  |
| Samsung Electronics            | 13        | 7.93%   |
| SanDisk                        | 10        | 6.1%    |
| Phison Electronics             | 3         | 1.83%   |
| Micron Technology              | 3         | 1.83%   |
| Marvell Technology Group       | 3         | 1.83%   |
| KIOXIA                         | 2         | 1.22%   |
| ASMedia Technology             | 2         | 1.22%   |
| Toshiba America Info Systems   | 1         | 0.61%   |
| Solid State Storage Technology | 1         | 0.61%   |
| SK hynix                       | 1         | 0.61%   |
| Micron/Crucial Technology      | 1         | 0.61%   |
| Kingston Technology Company    | 1         | 0.61%   |
| JMicron Technology             | 1         | 0.61%   |
| Broadcom / LSI                 | 1         | 0.61%   |
| Apple                          | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 11.29%  |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 3.76%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 3.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 2.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 2.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 2.69%   |
| SanDisk Non-Volatile memory controller                                                  | 4         | 2.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 2.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 2.15%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.61%   |
| Micron Non-Volatile memory controller                                                   | 3         | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.08%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 2         | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.08%   |
| Intel SSD 600P Series                                                                   | 2         | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.08%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.54%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 0.54%   |
| SK hynix BC511                                                                          | 1         | 0.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.54%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.54%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.54%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1         | 0.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.54%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.54%   |
| Intel SSD 660P Series                                                                   | 1         | 0.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.54%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1         | 0.54%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                                    | 1         | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 0.54%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 0.54%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 0.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.54%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 0.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 57.74%  |
| NVMe | 37        | 22.02%  |
| IDE  | 18        | 10.71%  |
| RAID | 15        | 8.93%   |
| SAS  | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 104       | 77.04%  |
| AMD    | 31        | 22.96%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 3.7%    |
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 2.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 2.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 2.22%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.48%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 1.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 1.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.48%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.48%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.48%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.48%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.74%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1         | 0.74%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 0.74%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.74%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.74%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.74%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.74%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.74%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.74%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.74%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.74%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.74%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.74%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.74%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.74%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.74%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 0.74%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 0.74%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.74%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.74%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.74%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.74%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.74%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 0.74%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.74%   |
| Intel Core i5-3550S CPU @ 3.00GHz           | 1         | 0.74%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1         | 0.74%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1         | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.74%   |
| Intel Core i5-2557M CPU @ 1.70GHz           | 1         | 0.74%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 0.74%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 0.74%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 0.74%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 0.74%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 0.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 20%     |
| Other                   | 14        | 10.37%  |
| Intel Core i7           | 14        | 10.37%  |
| Intel Core i3           | 10        | 7.41%   |
| AMD Ryzen 5             | 9         | 6.67%   |
| Intel Core 2 Duo        | 7         | 5.19%   |
| Intel Atom              | 7         | 5.19%   |
| Intel Pentium           | 6         | 4.44%   |
| Intel Celeron           | 6         | 4.44%   |
| AMD Ryzen 7             | 5         | 3.7%    |
| Intel Xeon              | 4         | 2.96%   |
| AMD Ryzen 3             | 4         | 2.96%   |
| Intel Pentium Dual-Core | 3         | 2.22%   |
| Intel Core 2            | 2         | 1.48%   |
| Intel Celeron M         | 2         | 1.48%   |
| AMD E2                  | 2         | 1.48%   |
| AMD E1                  | 2         | 1.48%   |
| AMD Athlon              | 2         | 1.48%   |
| Intel Pentium Silver    | 1         | 0.74%   |
| Intel Pentium M         | 1         | 0.74%   |
| Intel Core 2 Extreme    | 1         | 0.74%   |
| AMD Ryzen 9             | 1         | 0.74%   |
| AMD FX                  | 1         | 0.74%   |
| AMD C-50                | 1         | 0.74%   |
| AMD A6                  | 1         | 0.74%   |
| AMD A4                  | 1         | 0.74%   |
| AMD A10                 | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 69        | 51.11%  |
| 4      | 42        | 31.11%  |
| 8      | 9         | 6.67%   |
| 6      | 9         | 6.67%   |
| 1      | 5         | 3.7%    |
| 16     | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 133       | 98.52%  |
| 2      | 2         | 1.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 84        | 62.22%  |
| 1      | 51        | 37.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 131       | 97.04%  |
| 32-bit         | 4         | 2.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 11        | 8.09%   |
| 0x306a9    | 11        | 8.09%   |
| 0x40651    | 7         | 5.15%   |
| 0x206a7    | 6         | 4.41%   |
| 0x08608103 | 6         | 4.41%   |
| 0x08108109 | 6         | 4.41%   |
| 0x1067a    | 5         | 3.68%   |
| 0x806ec    | 4         | 2.94%   |
| 0x6fd      | 4         | 2.94%   |
| 0x506e3    | 4         | 2.94%   |
| 0x406e3    | 4         | 2.94%   |
| 0x306c3    | 4         | 2.94%   |
| 0x30661    | 4         | 2.94%   |
| Unknown    | 4         | 2.94%   |
| 0x806e9    | 3         | 2.21%   |
| 0x906ea    | 2         | 1.47%   |
| 0x706e5    | 2         | 1.47%   |
| 0x706a1    | 2         | 1.47%   |
| 0x6f6      | 2         | 1.47%   |
| 0x406c4    | 2         | 1.47%   |
| 0x20652    | 2         | 1.47%   |
| 0x10676    | 2         | 1.47%   |
| 0x08101016 | 2         | 1.47%   |
| 0x06006705 | 2         | 1.47%   |
| 0xa0653    | 1         | 0.74%   |
| 0xa0652    | 1         | 0.74%   |
| 0x906ed    | 1         | 0.74%   |
| 0x906c0    | 1         | 0.74%   |
| 0x90675    | 1         | 0.74%   |
| 0x806ea    | 1         | 0.74%   |
| 0x806d1    | 1         | 0.74%   |
| 0x706a8    | 1         | 0.74%   |
| 0x6f2      | 1         | 0.74%   |
| 0x6ec      | 1         | 0.74%   |
| 0x6d8      | 1         | 0.74%   |
| 0x506c9    | 1         | 0.74%   |
| 0x306d4    | 1         | 0.74%   |
| 0x30673    | 1         | 0.74%   |
| 0x206d7    | 1         | 0.74%   |
| 0x206c2    | 1         | 0.74%   |
| 0x20655    | 1         | 0.74%   |
| 0x106e5    | 1         | 0.74%   |
| 0x106ca    | 1         | 0.74%   |
| 0x106c2    | 1         | 0.74%   |
| 0x106a5    | 1         | 0.74%   |
| 0x0a50000c | 1         | 0.74%   |
| 0x0a50000b | 1         | 0.74%   |
| 0x08600103 | 1         | 0.74%   |
| 0x08108102 | 1         | 0.74%   |
| 0x0810100b | 1         | 0.74%   |
| 0x08001137 | 1         | 0.74%   |
| 0x07030106 | 1         | 0.74%   |
| 0x07030105 | 1         | 0.74%   |
| 0x07000110 | 1         | 0.74%   |
| 0x0700010f | 1         | 0.74%   |
| 0x06006704 | 1         | 0.74%   |
| 0x0600611a | 1         | 0.74%   |
| 0x06000852 | 1         | 0.74%   |
| 0x05000029 | 1         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 12        | 8.82%   |
| TigerLake     | 11        | 8.09%   |
| KabyLake      | 11        | 8.09%   |
| Haswell       | 11        | 8.09%   |
| Skylake       | 8         | 5.88%   |
| Unknown       | 8         | 5.88%   |
| Zen+          | 7         | 5.15%   |
| SandyBridge   | 7         | 5.15%   |
| Penryn        | 7         | 5.15%   |
| Core          | 7         | 5.15%   |
| Bonnell       | 6         | 4.41%   |
| Zen           | 4         | 2.94%   |
| Westmere      | 4         | 2.94%   |
| Excavator     | 4         | 2.94%   |
| Zen 3         | 3         | 2.21%   |
| Silvermont    | 3         | 2.21%   |
| IceLake       | 3         | 2.21%   |
| Goldmont plus | 3         | 2.21%   |
| Puma          | 2         | 1.47%   |
| P6            | 2         | 1.47%   |
| Nehalem       | 2         | 1.47%   |
| Jaguar        | 2         | 1.47%   |
| CometLake     | 2         | 1.47%   |
| Broadwell     | 2         | 1.47%   |
| Zen 2         | 1         | 0.74%   |
| Tremont       | 1         | 0.74%   |
| Piledriver    | 1         | 0.74%   |
| Goldmont      | 1         | 0.74%   |
| Bobcat        | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 78        | 51.66%  |
| Nvidia | 37        | 24.5%   |
| AMD    | 36        | 23.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 5.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 4.49%   |
| AMD Lucienne                                                                             | 6         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.21%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.56%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 2.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.56%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.92%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.28%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 1.28%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.28%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.28%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.28%   |
| Intel HD Graphics 620                                                                    | 2         | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.28%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.28%   |
| AMD Cezanne                                                                              | 2         | 1.28%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.64%   |
| Nvidia GT216M [GeForce GT 325M]                                                          | 1         | 0.64%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.64%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.64%   |
| Nvidia GM107GL [Quadro K620]                                                             | 1         | 0.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.64%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.64%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.64%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 0.64%   |
| Nvidia GF119 [NVS 310]                                                                   | 1         | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.64%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 0.64%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1         | 0.64%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.64%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.64%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                          | 1         | 0.64%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.64%   |
| Nvidia G94GLM [Quadro FX 2700M]                                                          | 1         | 0.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.64%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.64%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.64%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.64%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 48.53%  |
| 1 x AMD        | 28        | 20.59%  |
| 1 x Nvidia     | 25        | 18.38%  |
| Intel + Nvidia | 9         | 6.62%   |
| AMD + Nvidia   | 4         | 2.94%   |
| 2 x AMD        | 2         | 1.47%   |
| Intel + AMD    | 2         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 121       | 88.97%  |
| Proprietary | 10        | 7.35%   |
| Unknown     | 5         | 3.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 52.94%  |
| 0.01-0.5   | 26        | 19.12%  |
| 1.01-2.0   | 20        | 14.71%  |
| 3.01-4.0   | 9         | 6.62%   |
| 0.51-1.0   | 7         | 5.15%   |
| 5.01-6.0   | 2         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 18.52%  |
| BOE                     | 19        | 14.07%  |
| Chimei Innolux          | 15        | 11.11%  |
| LG Display              | 12        | 8.89%   |
| Samsung Electronics     | 11        | 8.15%   |
| Apple                   | 5         | 3.7%    |
| BenQ                    | 4         | 2.96%   |
| Philips                 | 3         | 2.22%   |
| LG Philips              | 3         | 2.22%   |
| InfoVision              | 3         | 2.22%   |
| Dell                    | 3         | 2.22%   |
| Ancor Communications    | 3         | 2.22%   |
| Acer                    | 3         | 2.22%   |
| Sharp                   | 2         | 1.48%   |
| PANDA                   | 2         | 1.48%   |
| Lenovo                  | 2         | 1.48%   |
| Hewlett-Packard         | 2         | 1.48%   |
| HannStar                | 2         | 1.48%   |
| Goldstar                | 2         | 1.48%   |
| AOC                     | 2         | 1.48%   |
| ___                     | 1         | 0.74%   |
| Unknown                 | 1         | 0.74%   |
| TR_                     | 1         | 0.74%   |
| Quanta Display          | 1         | 0.74%   |
| Planar                  | 1         | 0.74%   |
| MStar                   | 1         | 0.74%   |
| Medion                  | 1         | 0.74%   |
| Insignia                | 1         | 0.74%   |
| Iiyama                  | 1         | 0.74%   |
| DENON                   | 1         | 0.74%   |
| Chi Mei Optoelectronics | 1         | 0.74%   |
| ASUSTek Computer        | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.17%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 1.45%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 2         | 1.45%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1         | 0.72%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                    | 1         | 0.72%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.72%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.72%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch               | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch  | 1         | 0.72%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.72%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                     | 1         | 0.72%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 1         | 0.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 0.72%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch       | 1         | 0.72%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                 | 1         | 0.72%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.72%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.72%   |
| Philips LCD Monitor PHL 242V8 1920x1080                               | 1         | 0.72%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.72%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.72%   |
| MStar OptiPlex 9010 MST1111 1920x1080 510x286mm 23.0-inch             | 1         | 0.72%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                   | 1         | 0.72%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch           | 1         | 0.72%   |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch           | 1         | 0.72%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.72%   |
| LG Display LCD Monitor LGD0226 1600x900 382x215mm 17.3-inch           | 1         | 0.72%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 0.72%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                   | 1         | 0.72%   |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch          | 1         | 0.72%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch          | 1         | 0.72%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 1         | 0.72%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 1         | 0.72%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch            | 1         | 0.72%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1         | 0.72%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch            | 1         | 0.72%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 0.72%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch              | 1         | 0.72%   |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                 | 1         | 0.72%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 1         | 0.72%   |
| DENON AVR DON005F 1920x1080                                           | 1         | 0.72%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1         | 0.72%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                     | 1         | 0.72%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 49.22%  |
| 1366x768 (WXGA)    | 26        | 20.31%  |
| 1600x900 (HD+)     | 8         | 6.25%   |
| 1920x1200 (WUXGA)  | 6         | 4.69%   |
| 1440x900 (WXGA+)   | 5         | 3.91%   |
| 1024x600           | 4         | 3.13%   |
| 1280x800 (WXGA)    | 3         | 2.34%   |
| 3840x2160 (4K)     | 2         | 1.56%   |
| 2560x1440 (QHD)    | 2         | 1.56%   |
| 1680x1050 (WSXGA+) | 2         | 1.56%   |
| 2880x1800          | 1         | 0.78%   |
| 2560x1600          | 1         | 0.78%   |
| 2560x1080          | 1         | 0.78%   |
| 2256x1504          | 1         | 0.78%   |
| 1280x768           | 1         | 0.78%   |
| 1280x720 (HD)      | 1         | 0.78%   |
| 1280x1024 (SXGA)   | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 43        | 31.85%  |
| 13      | 20        | 14.81%  |
| 14      | 15        | 11.11%  |
| 17      | 9         | 6.67%   |
| Unknown | 8         | 5.93%   |
| 24      | 7         | 5.19%   |
| 21      | 6         | 4.44%   |
| 27      | 5         | 3.7%    |
| 23      | 4         | 2.96%   |
| 10      | 4         | 2.96%   |
| 20      | 3         | 2.22%   |
| 72      | 2         | 1.48%   |
| 32      | 1         | 0.74%   |
| 31      | 1         | 0.74%   |
| 28      | 1         | 0.74%   |
| 22      | 1         | 0.74%   |
| 19      | 1         | 0.74%   |
| 18      | 1         | 0.74%   |
| 16      | 1         | 0.74%   |
| 11      | 1         | 0.74%   |
| 8       | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 66        | 49.62%  |
| 201-300     | 16        | 12.03%  |
| 501-600     | 15        | 11.28%  |
| 351-400     | 12        | 9.02%   |
| 401-500     | 10        | 7.52%   |
| Unknown     | 8         | 6.02%   |
| 601-700     | 2         | 1.5%    |
| 1501-2000   | 2         | 1.5%    |
| 701-800     | 1         | 0.75%   |
| 101-200     | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 98        | 78.4%   |
| 16/10   | 17        | 13.6%   |
| Unknown | 7         | 5.6%    |
| 5/4     | 1         | 0.8%    |
| 3/2     | 1         | 0.8%    |
| 21/9    | 1         | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 32.09%  |
| 81-90          | 25        | 18.66%  |
| 201-250        | 14        | 10.45%  |
| 71-80          | 10        | 7.46%   |
| Unknown        | 8         | 5.97%   |
| 121-130        | 6         | 4.48%   |
| 301-350        | 5         | 3.73%   |
| 41-50          | 4         | 2.99%   |
| 251-300        | 4         | 2.99%   |
| 151-200        | 4         | 2.99%   |
| 131-140        | 3         | 2.24%   |
| More than 1000 | 2         | 1.49%   |
| 351-500        | 2         | 1.49%   |
| 51-60          | 1         | 0.75%   |
| 1-40           | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 91-100         | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 34.33%  |
| 101-120       | 39        | 29.1%   |
| 51-100        | 30        | 22.39%  |
| 161-240       | 8         | 5.97%   |
| Unknown       | 8         | 5.97%   |
| 1-50          | 2         | 1.49%   |
| More than 240 | 1         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 120       | 88.24%  |
| 2     | 9         | 6.62%   |
| 0     | 4         | 2.94%   |
| 3     | 3         | 2.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 73        | 36.87%  |
| Intel                         | 59        | 29.8%   |
| Qualcomm Atheros              | 27        | 13.64%  |
| Broadcom                      | 14        | 7.07%   |
| Ralink Technology             | 4         | 2.02%   |
| Broadcom Limited              | 4         | 2.02%   |
| Marvell Technology Group      | 3         | 1.52%   |
| Samsung Electronics           | 2         | 1.01%   |
| Xiaomi                        | 1         | 0.51%   |
| TP-Link                       | 1         | 0.51%   |
| Ralink                        | 1         | 0.51%   |
| OnePlus Technology (Shenzhen) | 1         | 0.51%   |
| NetGear                       | 1         | 0.51%   |
| Microchip Technology          | 1         | 0.51%   |
| Mercucys                      | 1         | 0.51%   |
| JMicron Technology            | 1         | 0.51%   |
| Google                        | 1         | 0.51%   |
| Dell                          | 1         | 0.51%   |
| Davicom Semiconductor         | 1         | 0.51%   |
| Belkin Components             | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 39        | 15.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 12        | 4.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 11        | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 8         | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7         | 2.87%   |
| Intel Wi-Fi 6 AX201                                                                           | 6         | 2.46%   |
| Intel Wireless 3165                                                                           | 5         | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 4         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 1.64%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                                           | 4         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 4         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                                                      | 4         | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3         | 1.23%   |
| Intel Wireless 7260                                                                           | 3         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                                               | 3         | 1.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 3         | 1.23%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2         | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 0.82%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 2         | 0.82%   |
| Realtek 802.11ac NIC                                                                          | 2         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 2         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 0.82%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 2         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 0.82%   |
| Intel WiFi Link 5100                                                                          | 2         | 0.82%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 0.82%   |
| Intel 82579V Gigabit Network Connection                                                       | 2         | 0.82%   |
| Intel 82574L Gigabit Network Connection                                                       | 2         | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 0.82%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.41%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.41%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.41%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.41%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.41%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.41%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.41%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.41%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 35.54%  |
| Realtek Semiconductor | 35        | 28.93%  |
| Qualcomm Atheros      | 19        | 15.7%   |
| Broadcom              | 11        | 9.09%   |
| Ralink Technology     | 4         | 3.31%   |
| Broadcom Limited      | 4         | 3.31%   |
| TP-Link               | 1         | 0.83%   |
| Ralink                | 1         | 0.83%   |
| NetGear               | 1         | 0.83%   |
| Mercucys              | 1         | 0.83%   |
| Belkin Components     | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 11        | 8.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7         | 5.6%    |
| Intel Wi-Fi 6 AX201                                                                           | 6         | 4.8%    |
| Intel Wireless 3165                                                                           | 5         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 4         | 3.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 3.2%    |
| Intel Wireless 8265 / 8275                                                                    | 4         | 3.2%    |
| Intel Wi-Fi 6 AX200                                                                           | 4         | 3.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 4         | 3.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3         | 2.4%    |
| Intel Wireless 7260                                                                           | 3         | 2.4%    |
| Intel Ultimate N WiFi Link 5300                                                               | 3         | 2.4%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 3         | 2.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 2         | 1.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 1.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 1.6%    |
| Realtek 802.11ac NIC                                                                          | 2         | 1.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.6%    |
| Intel WiFi Link 5100                                                                          | 2         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 1.6%    |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 1.6%    |
| Broadcom BCM43225 802.11b/g/n                                                                 | 2         | 1.6%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.8%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.8%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.8%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.8%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.8%    |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 0.8%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.8%    |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.8%    |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.8%    |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.8%    |
| NetGear A6150                                                                                 | 1         | 0.8%    |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 0.8%    |
| Intel Wireless 8260                                                                           | 1         | 0.8%    |
| Intel Wireless 7265                                                                           | 1         | 0.8%    |
| Intel Wireless 3160                                                                           | 1         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 0.8%    |
| Intel Wi-Fi 6 AX201 160MHz                                                                    | 1         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 0.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 1         | 0.8%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 0.8%    |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1         | 0.8%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 57        | 50%     |
| Intel                         | 31        | 27.19%  |
| Qualcomm Atheros              | 12        | 10.53%  |
| Marvell Technology Group      | 3         | 2.63%   |
| Broadcom                      | 3         | 2.63%   |
| Samsung Electronics           | 2         | 1.75%   |
| Xiaomi                        | 1         | 0.88%   |
| OnePlus Technology (Shenzhen) | 1         | 0.88%   |
| Microchip Technology          | 1         | 0.88%   |
| JMicron Technology            | 1         | 0.88%   |
| Google                        | 1         | 0.88%   |
| Davicom Semiconductor         | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 10.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 6.84%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.71%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.71%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.71%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.71%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.71%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.85%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.85%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 0.85%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.85%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 0.85%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 0.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.85%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.85%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.85%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.85%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.85%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.85%   |
| Davicom DM9621A USB To FastEther                                  | 1         | 0.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 50.67%  |
| Ethernet | 108       | 48.43%  |
| Modem    | 2         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 62.59%  |
| Ethernet | 52        | 37.41%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 76        | 56.3%   |
| 1     | 55        | 40.74%  |
| 0     | 4         | 2.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 73.53%  |
| Yes  | 36        | 26.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 43.21%  |
| Realtek Semiconductor           | 18        | 22.22%  |
| Qualcomm Atheros Communications | 4         | 4.94%   |
| Foxconn / Hon Hai               | 4         | 4.94%   |
| Dell                            | 4         | 4.94%   |
| Apple                           | 4         | 4.94%   |
| Cambridge Silicon Radio         | 3         | 3.7%    |
| Broadcom                        | 3         | 3.7%    |
| Lite-On Technology              | 2         | 2.47%   |
| Hewlett-Packard                 | 2         | 2.47%   |
| IMC Networks                    | 1         | 1.23%   |
| Foxconn International           | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 17.28%  |
| Realtek Bluetooth Radio                             | 11        | 13.58%  |
| Intel AX201 Bluetooth                               | 9         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 8.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 7.41%   |
| Intel AX200 Bluetooth                               | 4         | 4.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.47%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 2.47%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.47%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.23%   |
| Intel AX210 Bluetooth                               | 1         | 1.23%   |
| IMC Networks Bluetooth Device                       | 1         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.23%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.23%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.23%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 1.23%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.23%   |
| Dell BT Mini-Receiver                               | 1         | 1.23%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.23%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.23%   |
| Broadcom BCM92045B3 ROM                             | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.23%   |
| Apple Bluetooth Host Controller                     | 1         | 1.23%   |
| Apple Bluetooth HCI                                 | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 58.14%  |
| AMD                   | 36        | 20.93%  |
| Nvidia                | 28        | 16.28%  |
| Texas Instruments     | 2         | 1.16%   |
| C-Media Electronics   | 2         | 1.16%   |
| Yamaha                | 1         | 0.58%   |
| Realtek Semiconductor | 1         | 0.58%   |
| GN Netcom             | 1         | 0.58%   |
| Audioengine           | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 9.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 5.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 4.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 4.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 3.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.27%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 2.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.34%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.87%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.87%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 1.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.4%    |
| AMD High Definition Audio Controller                                                              | 3         | 1.4%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.93%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.93%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.47%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.47%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                                                 | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia Audio device                                                                               | 1         | 0.47%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.47%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.47%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.47%   |
| Intel Audio device                                                                                | 1         | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.47%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 0.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 16        | 27.59%  |
| SK hynix                     | 12        | 20.69%  |
| Unknown                      | 6         | 10.34%  |
| Micron Technology            | 5         | 8.62%   |
| Nanya Technology             | 3         | 5.17%   |
| Crucial                      | 3         | 5.17%   |
| A-DATA Technology            | 3         | 5.17%   |
| Unknown (ABCD)               | 2         | 3.45%   |
| Kingston                     | 2         | 3.45%   |
| Corsair                      | 2         | 3.45%   |
| Ramaxel Technology           | 1         | 1.72%   |
| Patriot Memory (PDP Systems) | 1         | 1.72%   |
| G.Skill                      | 1         | 1.72%   |
| Unknown                      | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s      | 2         | 3.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2         | 3.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 3.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s              | 2         | 3.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 2         | 3.28%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                              | 1         | 1.64%   |
| Unknown RAM Module 512MB SODIMM DDR                                      | 1         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                              | 1         | 1.64%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 1         | 1.64%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                     | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR                                        | 1         | 1.64%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                            | 1         | 1.64%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                             | 1         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s                     | 1         | 1.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.64%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 1.64%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                    | 1         | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 1         | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s              | 1         | 1.64%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s                  | 1         | 1.64%   |
| Ramaxel RAM RMSA3330MJ78HBF-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 1.64%   |
| Patriot Memory (PDP Systems) RAM PSD432G32002S 32GB SODIMM DDR4 3200MT/s | 1         | 1.64%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s                     | 1         | 1.64%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.64%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s                        | 1         | 1.64%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 1.64%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-2G3A1 4GB SODIMM DDR4 2400MT/s                    | 1         | 1.64%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s                      | 1         | 1.64%   |
| Micron RAM 16JTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s                  | 1         | 1.64%   |
| Kingston RAM MSI26D4S9D8ME-16 16GB SODIMM DDR4 2667MT/s                  | 1         | 1.64%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s                      | 1         | 1.64%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s                    | 1         | 1.64%   |
| Crucial RAM CT8G4SFS824A.M8FB 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.64%   |
| Crucial RAM CT8G4SFD8213.C16FBR2 8GB SODIMM DDR4 2267MT/s                | 1         | 1.64%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s                | 1         | 1.64%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                               | 1         | 1.64%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                              | 1         | 1.64%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s                  | 1         | 1.64%   |
| Unknown                                                                  | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 51.85%  |
| DDR3    | 17        | 31.48%  |
| SDRAM   | 3         | 5.56%   |
| LPDDR4  | 3         | 5.56%   |
| DDR2    | 1         | 1.85%   |
| DDR     | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 76.36%  |
| DIMM         | 10        | 18.18%  |
| Row Of Chips | 3         | 5.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 36.21%  |
| 4096  | 17        | 29.31%  |
| 2048  | 9         | 15.52%  |
| 16384 | 5         | 8.62%   |
| 32768 | 3         | 5.17%   |
| 1024  | 2         | 3.45%   |
| 512   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 17        | 30.36%  |
| 1600    | 15        | 26.79%  |
| 2400    | 6         | 10.71%  |
| 2667    | 5         | 8.93%   |
| 667     | 2         | 3.57%   |
| 4267    | 1         | 1.79%   |
| 4199    | 1         | 1.79%   |
| 3400    | 1         | 1.79%   |
| 2666    | 1         | 1.79%   |
| 2267    | 1         | 1.79%   |
| 2048    | 1         | 1.79%   |
| 1866    | 1         | 1.79%   |
| 1334    | 1         | 1.79%   |
| 1333    | 1         | 1.79%   |
| 1200    | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

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
| Chicony Electronics                    | 15        | 16.48%  |
| Microdia                               | 12        | 13.19%  |
| Suyin                                  | 8         | 8.79%   |
| IMC Networks                           | 8         | 8.79%   |
| Acer                                   | 7         | 7.69%   |
| Sunplus Innovation Technology          | 6         | 6.59%   |
| Realtek Semiconductor                  | 6         | 6.59%   |
| Quanta                                 | 6         | 6.59%   |
| Logitech                               | 3         | 3.3%    |
| Alcor Micro                            | 3         | 3.3%    |
| Luxvisions Innotech Limited            | 2         | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.2%    |
| Z-Star Microelectronics                | 1         | 1.1%    |
| Unknown                                | 1         | 1.1%    |
| Syntek                                 | 1         | 1.1%    |
| OmniVision Technologies                | 1         | 1.1%    |
| MacroSilicon                           | 1         | 1.1%    |
| Lite-On Technology                     | 1         | 1.1%    |
| Lenovo                                 | 1         | 1.1%    |
| Intel                                  | 1         | 1.1%    |
| icSpring                               | 1         | 1.1%    |
| Creative Technology                    | 1         | 1.1%    |
| ARC International                      | 1         | 1.1%    |
| Apple                                  | 1         | 1.1%    |
| ALi                                    | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 9         | 9.89%   |
| Chicony Integrated Camera                                      | 5         | 5.49%   |
| Acer Integrated Camera                                         | 4         | 4.4%    |
| Quanta HP TrueVision HD Camera                                 | 3         | 3.3%    |
| Chicony HP TrueVision HD Camera                                | 3         | 3.3%    |
| Suyin HP TrueVision HD                                         | 2         | 2.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 2         | 2.2%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 2.2%    |
| IMC Networks Integrated Camera                                 | 2         | 2.2%    |
| Chicony HD Webcam                                              | 2         | 2.2%    |
| Alcor Micro USB 2.0 Camera                                     | 2         | 2.2%    |
| Acer USB2.0 Camera                                             | 2         | 2.2%    |
| Z-Star Venus USB2.0 Camera                                     | 1         | 1.1%    |
| Unknown 720p HD Camera                                         | 1         | 1.1%    |
| Syntek Integrated Camera                                       | 1         | 1.1%    |
| Suyin HP Webcam-101                                            | 1         | 1.1%    |
| Suyin HD WebCam                                                | 1         | 1.1%    |
| Suyin HD Video WebCam                                          | 1         | 1.1%    |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 1.1%    |
| Suyin Acer CrystalEye Webcam                                   | 1         | 1.1%    |
| Suyin 1.3M HD WebCam                                           | 1         | 1.1%    |
| Sunplus MTD Camera                                             | 1         | 1.1%    |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 1.1%    |
| Sunplus HP TrueVision HD Camera                                | 1         | 1.1%    |
| Sunplus HD WebCam                                              | 1         | 1.1%    |
| Sunplus 5Mega Webcam                                           | 1         | 1.1%    |
| Sunplus 1.3M HD WebCam                                         | 1         | 1.1%    |
| Realtek USB2.0 camera                                          | 1         | 1.1%    |
| Realtek Lenovo EasyCamera                                      | 1         | 1.1%    |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.1%    |
| Realtek HP Truevision HD integrated webcam                     | 1         | 1.1%    |
| Realtek HP Truevision HD                                       | 1         | 1.1%    |
| Realtek HP "Truevision HD" laptop camera                       | 1         | 1.1%    |
| Quanta VGA WebCam                                              | 1         | 1.1%    |
| Quanta HP Webcam                                               | 1         | 1.1%    |
| Quanta HP HD Camera                                            | 1         | 1.1%    |
| OmniVision Integrated Webcam for Dell XPS 2010                 | 1         | 1.1%    |
| Microdia Lenovo EasyCamera                                     | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 1         | 1.1%    |
| MacroSilicon USB Video                                         | 1         | 1.1%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.1%    |
| Luxvisions Innotech Limited HP HD Camera                       | 1         | 1.1%    |
| Logitech Webcam C925e                                          | 1         | 1.1%    |
| Logitech Webcam C270                                           | 1         | 1.1%    |
| Logitech Webcam C210                                           | 1         | 1.1%    |
| Lite-On HP TrueVision HD Camera                                | 1         | 1.1%    |
| Lenovo Integrated Webcam                                       | 1         | 1.1%    |
| Intel RealSense 3D Camera (Front F200)                         | 1         | 1.1%    |
| IMC Networks Integrated Webcam                                 | 1         | 1.1%    |
| IMC Networks 2M Integrated Webcam                              | 1         | 1.1%    |
| icSpring camera                                                | 1         | 1.1%    |
| Creative Live! Cam Sync HD [VF0770]                            | 1         | 1.1%    |
| Chicony USB2.0 Camera                                          | 1         | 1.1%    |
| Chicony Integrated HP HD Webcam                                | 1         | 1.1%    |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 1.1%    |
| Chicony CKA7216                                                | 1         | 1.1%    |
| Chicony 1.3M Webcam                                            | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 46.15%  |
| Synaptics                  | 2         | 15.38%  |
| STMicroelectronics         | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| Samsung Electronics        | 1         | 7.69%   |
| Focal-systems.Corp         | 1         | 7.69%   |
| Elan Microelectronics      | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 15.38%  |
| Validity Sensors Synaptics WBDI            | 2         | 15.38%  |
| Unknown                                    | 2         | 15.38%  |
| Validity Sensors VFS491                    | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 7.69%   |
| STMicroelectronics Fingerprint Reader      | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 7.69%   |
| Samsung Fingerprint Sensor Device - 730B   | 1         | 7.69%   |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 7.69%   |
| Elan ELAN:Fingerprint                      | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 42.86%  |
| Lenovo Integrated Smart Card Reader            | 1         | 14.29%  |
| Broadcom 5880                                  | 1         | 14.29%  |
| Broadcom 58200                                 | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 89        | 64.49%  |
| 1     | 44        | 31.88%  |
| 2     | 4         | 2.9%    |
| 3     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 15        | 27.27%  |
| Fingerprint reader    | 12        | 21.82%  |
| Multimedia controller | 10        | 18.18%  |
| Graphics card         | 10        | 18.18%  |
| Chipcard              | 6         | 10.91%  |
| Dvb card              | 1         | 1.82%   |
| Camera                | 1         | 1.82%   |

