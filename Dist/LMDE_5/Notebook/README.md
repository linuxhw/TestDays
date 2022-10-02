LMDE 5 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

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

Total: 145

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Medion        | P15648                      | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Lenovo        | Yoga 2 11 20332             | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| Acer          | Aspire 5930                 | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | Latitude E6330              | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Lenovo        | G500 20236                  | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| Microtech     | ebookPro                    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Framework     | Laptop                      | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | Laptop 14-dk1xxx            | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Framework     | Laptop                      | [80ad33bb18](https://linux-hardware.org/?probe=80ad33bb18) | Jul 16, 2022 |
| Framework     | Laptop                      | [439e4aafa7](https://linux-hardware.org/?probe=439e4aafa7) | Jul 16, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| AMI           | T3 MRD                      | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | [8a44001ebb](https://linux-hardware.org/?probe=8a44001ebb) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| HP            | 255 G5 Notebook PC          | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Multilaser    | PC150                       | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron 5566               | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-14-amd64      | 20        | 17.54%  |
| 5.10.0-12-amd64      | 20        | 17.54%  |
| 5.10.0-15-amd64      | 16        | 14.04%  |
| 5.10.0-13-amd64      | 14        | 12.28%  |
| 5.10.0-16-amd64      | 10        | 8.77%   |
| 5.10.0-17-amd64      | 8         | 7.02%   |
| 5.10.0-18-amd64      | 7         | 6.14%   |
| 5.10.0-13-686        | 5         | 4.39%   |
| 5.18.0-0.bpo.1-amd64 | 4         | 3.51%   |
| 5.16.0-0.bpo.4-amd64 | 3         | 2.63%   |
| 5.19.10-xanmod1      | 1         | 0.88%   |
| 5.18.0-4-amd64       | 1         | 0.88%   |
| 5.18.0-3-amd64       | 1         | 0.88%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.88%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.88%   |
| 5.10.0-17-686        | 1         | 0.88%   |
| 5.10.0-14-686        | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 98        | 89.91%  |
| 5.18.0  | 6         | 5.5%    |
| 5.16.0  | 3         | 2.75%   |
| 5.19.10 | 1         | 0.92%   |
| 5.15.0  | 1         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 98        | 89.91%  |
| 5.18    | 6         | 5.5%    |
| 5.16    | 3         | 2.75%   |
| 5.19    | 1         | 0.92%   |
| 5.15    | 1         | 0.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 93.46%  |
| i686   | 7         | 6.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 97        | 90.65%  |
| Cinnamon   | 8         | 7.48%   |
| MATE       | 1         | 0.93%   |
| Unknown    | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 107       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 57.01%  |
| LightDM | 46        | 42.99%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 39        | 36.11%  |
| de_DE | 14        | 12.96%  |
| ru_RU | 9         | 8.33%   |
| pt_BR | 7         | 6.48%   |
| en_GB | 7         | 6.48%   |
| fr_FR | 5         | 4.63%   |
| es_ES | 4         | 3.7%    |
| es_MX | 3         | 2.78%   |
| pl_PL | 2         | 1.85%   |
| it_IT | 2         | 1.85%   |
| es_BO | 2         | 1.85%   |
| en_IE | 2         | 1.85%   |
| pt_PT | 1         | 0.93%   |
| nn_NO | 1         | 0.93%   |
| nl_AW | 1         | 0.93%   |
| ko_KR | 1         | 0.93%   |
| hu_HU | 1         | 0.93%   |
| fr_BE | 1         | 0.93%   |
| es_PE | 1         | 0.93%   |
| es_EC | 1         | 0.93%   |
| es_CR | 1         | 0.93%   |
| en_NZ | 1         | 0.93%   |
| en_CA | 1         | 0.93%   |
| da_DK | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 74        | 69.16%  |
| BIOS | 33        | 30.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 92.52%  |
| Overlay | 5         | 4.67%   |
| Xfs     | 1         | 0.93%   |
| Tmpfs   | 1         | 0.93%   |
| Btrfs   | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 56.07%  |
| GPT     | 40        | 37.38%  |
| MBR     | 7         | 6.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 92.59%  |
| Yes       | 8         | 7.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 88.79%  |
| Yes       | 12        | 11.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 25        | 23.36%  |
| Dell             | 19        | 17.76%  |
| Lenovo           | 17        | 15.89%  |
| Acer             | 12        | 11.21%  |
| ASUSTek Computer | 7         | 6.54%   |
| Apple            | 4         | 3.74%   |
| Toshiba          | 2         | 1.87%   |
| Sony             | 2         | 1.87%   |
| MSI              | 2         | 1.87%   |
| Medion           | 2         | 1.87%   |
| Unknown          | 2         | 1.87%   |
| Wortmann AG      | 1         | 0.93%   |
| Philco           | 1         | 0.93%   |
| Packard Bell     | 1         | 0.93%   |
| Multilaser       | 1         | 0.93%   |
| Microtech        | 1         | 0.93%   |
| LincPlus         | 1         | 0.93%   |
| Howard Computers | 1         | 0.93%   |
| Google           | 1         | 0.93%   |
| Framework        | 1         | 0.93%   |
| Dynabook         | 1         | 0.93%   |
| Dixonsxp         | 1         | 0.93%   |
| AMI              | 1         | 0.93%   |
| Alienware        | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 3         | 2.8%    |
| HP Laptop 15z-ef2xxx                             | 2         | 1.87%   |
| Dell Latitude E6400                              | 2         | 1.87%   |
| Dell Latitude E5540                              | 2         | 1.87%   |
| Acer Aspire 5930                                 | 2         | 1.87%   |
| Wortmann AG TERRA_MOBILE_1713A                   | 1         | 0.93%   |
| Toshiba Satellite M55                            | 1         | 0.93%   |
| Toshiba Satellite L455                           | 1         | 0.93%   |
| Sony SVE1713Y1RB                                 | 1         | 0.93%   |
| Sony SVE1512G1RW                                 | 1         | 0.93%   |
| Philco 10D                                       | 1         | 0.93%   |
| Packard Bell DOT S                               | 1         | 0.93%   |
| Multilaser PC150                                 | 1         | 0.93%   |
| MSI U180                                         | 1         | 0.93%   |
| MSI GL73 8SE                                     | 1         | 0.93%   |
| Microtech ebookPro                               | 1         | 0.93%   |
| Medion P15648                                    | 1         | 0.93%   |
| Medion E6220                                     | 1         | 0.93%   |
| LincPlus LINNCPLUS P1                            | 1         | 0.93%   |
| Lenovo Z50-70 20354                              | 1         | 0.93%   |
| Lenovo Yoga 2 11 20332                           | 1         | 0.93%   |
| Lenovo ThinkPad X270 W10DG 20K5S3HG00            | 1         | 0.93%   |
| Lenovo ThinkPad T61 7661A16                      | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 0.93%   |
| Lenovo ThinkPad T470s 20HF0047UK                 | 1         | 0.93%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS            | 1         | 0.93%   |
| Lenovo ThinkPad T450 20BUS0QT04                  | 1         | 0.93%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100             | 1         | 0.93%   |
| Lenovo ThinkPad E14 Gen 2 20TACTO1WW             | 1         | 0.93%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 0.93%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 0.93%   |
| Lenovo IdeaPad 320-15IKB 80XL                    | 1         | 0.93%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 0.93%   |
| Lenovo IdeaPad 3 15ADA05 81W1                    | 1         | 0.93%   |
| Lenovo IdeaPad 3 14ALC6 82KT                     | 1         | 0.93%   |
| Lenovo G500 20236                                | 1         | 0.93%   |
| Howard Computers R7X                             | 1         | 0.93%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 0.93%   |
| HP ProBook 6570b                                 | 1         | 0.93%   |
| HP ProBook 450 G8 Notebook PC                    | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 10        | 9.35%   |
| Lenovo ThinkPad      | 8         | 7.48%   |
| HP Laptop            | 8         | 7.48%   |
| Dell Latitude        | 8         | 7.48%   |
| Dell Inspiron        | 6         | 5.61%   |
| Lenovo IdeaPad       | 5         | 4.67%   |
| HP EliteBook         | 3         | 2.8%    |
| ASUS VivoBook        | 3         | 2.8%    |
| Unknown              | 3         | 2.8%    |
| Toshiba Satellite    | 2         | 1.87%   |
| HP ProBook           | 2         | 1.87%   |
| HP Pavilion          | 2         | 1.87%   |
| HP Compaq            | 2         | 1.87%   |
| HP 255               | 2         | 1.87%   |
| Dell Vostro          | 2         | 1.87%   |
| Dell Precision       | 2         | 1.87%   |
| ASUS ROG             | 2         | 1.87%   |
| Wortmann AG TERRA    | 1         | 0.93%   |
| Sony SVE1713Y1RB     | 1         | 0.93%   |
| Sony SVE1512G1RW     | 1         | 0.93%   |
| Philco 10D           | 1         | 0.93%   |
| Packard Bell DOT     | 1         | 0.93%   |
| Multilaser PC150     | 1         | 0.93%   |
| MSI U180             | 1         | 0.93%   |
| MSI GL73             | 1         | 0.93%   |
| Microtech ebookPro   | 1         | 0.93%   |
| Medion P15648        | 1         | 0.93%   |
| Medion E6220         | 1         | 0.93%   |
| LincPlus LINNCPLUS   | 1         | 0.93%   |
| Lenovo Z50-70        | 1         | 0.93%   |
| Lenovo Yoga          | 1         | 0.93%   |
| Lenovo Legion        | 1         | 0.93%   |
| Lenovo G500          | 1         | 0.93%   |
| Howard Computers R7X | 1         | 0.93%   |
| HP ZBook             | 1         | 0.93%   |
| HP Presario          | 1         | 0.93%   |
| HP Notebook          | 1         | 0.93%   |
| HP G72               | 1         | 0.93%   |
| HP ENVY              | 1         | 0.93%   |
| HP 14                | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 15.89%  |
| 2020 | 10        | 9.35%   |
| 2013 | 10        | 9.35%   |
| 2012 | 9         | 8.41%   |
| 2019 | 8         | 7.48%   |
| 2017 | 8         | 7.48%   |
| 2016 | 7         | 6.54%   |
| 2010 | 7         | 6.54%   |
| 2014 | 6         | 5.61%   |
| 2018 | 5         | 4.67%   |
| 2008 | 5         | 4.67%   |
| 2009 | 4         | 3.74%   |
| 2022 | 3         | 2.8%    |
| 2015 | 3         | 2.8%    |
| 2007 | 3         | 2.8%    |
| 2011 | 1         | 0.93%   |
| 2006 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 94        | 87.04%  |
| Enabled  | 14        | 12.96%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 106       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 28.97%  |
| 3.01-4.0    | 27        | 25.23%  |
| 8.01-16.0   | 17        | 15.89%  |
| 16.01-24.0  | 15        | 14.02%  |
| 1.01-2.0    | 7         | 6.54%   |
| 32.01-64.0  | 4         | 3.74%   |
| 2.01-3.0    | 4         | 3.74%   |
| 64.01-256.0 | 2         | 1.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 46        | 41.07%  |
| 2.01-3.0   | 42        | 37.5%   |
| 3.01-4.0   | 10        | 8.93%   |
| 4.01-8.0   | 6         | 5.36%   |
| 0.51-1.0   | 6         | 5.36%   |
| 32.01-64.0 | 1         | 0.89%   |
| 8.01-16.0  | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 75.93%  |
| 2      | 22        | 20.37%  |
| 3      | 3         | 2.78%   |
| 4      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 69.16%  |
| Yes       | 33        | 30.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 76.64%  |
| No        | 25        | 23.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 98.13%  |
| No        | 2         | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 72.9%   |
| No        | 29        | 27.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 15.6%   |
| Germany     | 15        | 13.76%  |
| Russia      | 11        | 10.09%  |
| UK          | 8         | 7.34%   |
| Brazil      | 8         | 7.34%   |
| France      | 5         | 4.59%   |
| Spain       | 4         | 3.67%   |
| Poland      | 4         | 3.67%   |
| Italy       | 4         | 3.67%   |
| Mexico      | 3         | 2.75%   |
| Canada      | 3         | 2.75%   |
| Romania     | 2         | 1.83%   |
| Hungary     | 2         | 1.83%   |
| Chile       | 2         | 1.83%   |
| Bolivia     | 2         | 1.83%   |
| Belgium     | 2         | 1.83%   |
| Vietnam     | 1         | 0.92%   |
| South Korea | 1         | 0.92%   |
| Portugal    | 1         | 0.92%   |
| Peru        | 1         | 0.92%   |
| Paraguay    | 1         | 0.92%   |
| Norway      | 1         | 0.92%   |
| New Zealand | 1         | 0.92%   |
| Malaysia    | 1         | 0.92%   |
| Lithuania   | 1         | 0.92%   |
| Kenya       | 1         | 0.92%   |
| Ireland     | 1         | 0.92%   |
| Finland     | 1         | 0.92%   |
| Ecuador     | 1         | 0.92%   |
| Denmark     | 1         | 0.92%   |
| Costa Rica  | 1         | 0.92%   |
| Belarus     | 1         | 0.92%   |
| Austria     | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 3         | 2.75%   |
| Oruro             | 2         | 1.83%   |
| Neasden           | 2         | 1.83%   |
| Berlin            | 2         | 1.83%   |
| Zaragoza          | 1         | 0.92%   |
| Wroclaw           | 1         | 0.92%   |
| Voronezh          | 1         | 0.92%   |
| Vilshofen         | 1         | 0.92%   |
| Vilnius           | 1         | 0.92%   |
| Viet Tri          | 1         | 0.92%   |
| Veurne            | 1         | 0.92%   |
| Vaslui            | 1         | 0.92%   |
| Valsoyfjord       | 1         | 0.92%   |
| Uiwang            | 1         | 0.92%   |
| Turku             | 1         | 0.92%   |
| Tula              | 1         | 0.92%   |
| Troisdorf         | 1         | 0.92%   |
| Toulouse          | 1         | 0.92%   |
| Toronto           | 1         | 0.92%   |
| Tipton            | 1         | 0.92%   |
| St Petersburg     | 1         | 0.92%   |
| Spearfish         | 1         | 0.92%   |
| Smolensk          | 1         | 0.92%   |
| Scarborough       | 1         | 0.92%   |
| Saratov           | 1         | 0.92%   |
| Sao Paulo         | 1         | 0.92%   |
| Santiago          | 1         | 0.92%   |
| San Jose          | 1         | 0.92%   |
| Rottenburg        | 1         | 0.92%   |
| Rome              | 1         | 0.92%   |
| Rochester         | 1         | 0.92%   |
| Recife            | 1         | 0.92%   |
| Providencia       | 1         | 0.92%   |
| Petaling Jaya     | 1         | 0.92%   |
| Ordonnac          | 1         | 0.92%   |
| Nuremberg         | 1         | 0.92%   |
| Nizhniy Novgorod  | 1         | 0.92%   |
| Nairobi           | 1         | 0.92%   |
| Murphy            | 1         | 0.92%   |
| Mosonmagyaróvár | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 17        | 19     | 12.69%  |
| Seagate                        | 14        | 15     | 10.45%  |
| Samsung Electronics            | 14        | 15     | 10.45%  |
| Unknown                        | 10        | 14     | 7.46%   |
| SanDisk                        | 10        | 10     | 7.46%   |
| Toshiba                        | 6         | 7      | 4.48%   |
| Kingston                       | 6         | 6      | 4.48%   |
| Intel                          | 6         | 6      | 4.48%   |
| Hitachi                        | 6         | 6      | 4.48%   |
| PNY                            | 4         | 4      | 2.99%   |
| Apple                          | 4         | 9      | 2.99%   |
| Patriot                        | 3         | 3      | 2.24%   |
| Micron Technology              | 3         | 3      | 2.24%   |
| Team                           | 2         | 2      | 1.49%   |
| Phison                         | 2         | 2      | 1.49%   |
| KingSpec                       | 2         | 2      | 1.49%   |
| HGST                           | 2         | 2      | 1.49%   |
| A-DATA Technology              | 2         | 3      | 1.49%   |
| UMIS                           | 1         | 1      | 0.75%   |
| SSD PHIS                       | 1         | 1      | 0.75%   |
| Solid State Storage Technology | 1         | 1      | 0.75%   |
| SK hynix                       | 1         | 1      | 0.75%   |
| ShiJi                          | 1         | 1      | 0.75%   |
| SABRENT                        | 1         | 1      | 0.75%   |
| Oyen                           | 1         | 1      | 0.75%   |
| ORICO                          | 1         | 1      | 0.75%   |
| Microtech                      | 1         | 2      | 0.75%   |
| Micron/Crucial Technology      | 1         | 2      | 0.75%   |
| LITEON                         | 1         | 1      | 0.75%   |
| KIOXIA                         | 1         | 4      | 0.75%   |
| Initio                         | 1         | 1      | 0.75%   |
| HXY                            | 1         | 1      | 0.75%   |
| Fujitsu                        | 1         | 1      | 0.75%   |
| FORESEE                        | 1         | 1      | 0.75%   |
| Crucial                        | 1         | 1      | 0.75%   |
| China                          | 1         | 2      | 0.75%   |
| BHT                            | 1         | 2      | 0.75%   |
| Acer                           | 1         | 1      | 0.75%   |
| Unknown                        | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.9%    |
| Unknown SD/MMC/MS PRO 2GB            | 3         | 2.17%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 2.17%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 1.45%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 1.45%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 1.45%   |
| Unknown SC128  128GB                 | 2         | 1.45%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.45%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.45%   |
| Samsung PM991a NVMe 512GB            | 2         | 1.45%   |
| Patriot Burst 240GB SSD              | 2         | 1.45%   |
| Micron NVMe SSD Drive 512GB          | 2         | 1.45%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 1.45%   |
| Apple SSD SD0128F 121GB              | 2         | 1.45%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.72%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.72%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.72%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.72%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.72%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.72%   |
| WDC WD30 EFRX-68EUZN0 3TB            | 1         | 0.72%   |
| WDC WD10SPZX-60Z10T1 1TB             | 1         | 0.72%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 0.72%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.72%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.72%   |
| WDC PC SA530 SDASN8Y1T00 1024GB      | 1         | 0.72%   |
| Unknown USB DISK 3.2 250GB           | 1         | 0.72%   |
| Unknown SP32G  32GB                  | 1         | 0.72%   |
| Unknown MMC Card  64GB               | 1         | 0.72%   |
| Unknown MMC Card  32GB               | 1         | 0.72%   |
| Unknown Biwin  64GB                  | 1         | 0.72%   |
| Unknown Biwin  32GB                  | 1         | 0.72%   |
| UMIS RPJTJ512MGE1QDQ 512GB           | 1         | 0.72%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.72%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.72%   |
| Toshiba MK3252GSX 320GB              | 1         | 0.72%   |
| Toshiba KBG40ZNT256G MEMORY 256GB    | 1         | 0.72%   |
| Team TM8PS7256G 256GB SSD            | 1         | 0.72%   |
| Team T253X6512G 512GB SSD            | 1         | 0.72%   |
| SSD PHIS ON 256GB PS3110 SSD         | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 15     | 34.15%  |
| WDC     | 10        | 11     | 24.39%  |
| Hitachi | 6         | 6      | 14.63%  |
| Toshiba | 5         | 6      | 12.2%   |
| Unknown | 3         | 3      | 7.32%   |
| HGST    | 2         | 2      | 4.88%   |
| Fujitsu | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 11.36%  |
| Kingston            | 5         | 5      | 11.36%  |
| PNY                 | 4         | 4      | 9.09%   |
| SanDisk             | 3         | 3      | 6.82%   |
| Patriot             | 3         | 3      | 6.82%   |
| Intel               | 3         | 3      | 6.82%   |
| Apple               | 3         | 3      | 6.82%   |
| Team                | 2         | 2      | 4.55%   |
| KingSpec            | 2         | 2      | 4.55%   |
| A-DATA Technology   | 2         | 3      | 4.55%   |
| WDC                 | 1         | 1      | 2.27%   |
| SSD PHIS            | 1         | 1      | 2.27%   |
| ORICO               | 1         | 1      | 2.27%   |
| Microtech           | 1         | 2      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| HXY                 | 1         | 1      | 2.27%   |
| FORESEE             | 1         | 1      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |
| China               | 1         | 2      | 2.27%   |
| BHT                 | 1         | 2      | 2.27%   |
| Acer                | 1         | 1      | 2.27%   |
| Unknown             | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 41        | 49     | 32.8%   |
| HDD     | 39        | 44     | 31.2%   |
| NVMe    | 33        | 47     | 26.4%   |
| MMC     | 7         | 10     | 5.6%    |
| Unknown | 5         | 6      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 88     | 61.67%  |
| NVMe | 32        | 46     | 26.67%  |
| SAS  | 7         | 12     | 5.83%   |
| MMC  | 7         | 10     | 5.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 66     | 70%     |
| 0.51-1.0   | 21        | 24     | 26.25%  |
| 2.01-3.0   | 1         | 1      | 1.25%   |
| 1.01-2.0   | 1         | 1      | 1.25%   |
| 4.01-10.0  | 1         | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 39        | 35.78%  |
| 251-500        | 26        | 23.85%  |
| 501-1000       | 14        | 12.84%  |
| 1001-2000      | 8         | 7.34%   |
| 51-100         | 8         | 7.34%   |
| 21-50          | 7         | 6.42%   |
| 1-20           | 5         | 4.59%   |
| More than 3000 | 1         | 0.92%   |
| 2001-3000      | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 57        | 50.89%  |
| 21-50     | 21        | 18.75%  |
| 51-100    | 14        | 12.5%   |
| 101-250   | 10        | 8.93%   |
| 251-500   | 5         | 4.46%   |
| 501-1000  | 4         | 3.57%   |
| 2001-3000 | 1         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB    | 1         | 1      | 14.29%  |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 14.29%  |
| Seagate ST500LT032-1E9142 500GB | 1         | 1      | 14.29%  |
| Phison ES 512GB                 | 1         | 1      | 14.29%  |
| Intel SSDSCKKF256G8 SATA 256GB  | 1         | 1      | 14.29%  |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 14.29%  |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 16.67%  |
| Seagate | 1         | 1      | 16.67%  |
| Phison  | 1         | 1      | 16.67%  |
| Intel   | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 25%     |
| Seagate | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 66.67%  |
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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 68        | 95     | 58.12%  |
| Works    | 43        | 54     | 36.75%  |
| Malfunc  | 6         | 7      | 5.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 72        | 57.14%  |
| AMD                            | 18        | 14.29%  |
| SanDisk                        | 10        | 7.94%   |
| Samsung Electronics            | 10        | 7.94%   |
| Micron Technology              | 3         | 2.38%   |
| Phison Electronics             | 2         | 1.59%   |
| Marvell Technology Group       | 2         | 1.59%   |
| KIOXIA                         | 2         | 1.59%   |
| Union Memory (Shenzhen)        | 1         | 0.79%   |
| Toshiba America Info Systems   | 1         | 0.79%   |
| Solid State Storage Technology | 1         | 0.79%   |
| SK hynix                       | 1         | 0.79%   |
| Micron/Crucial Technology      | 1         | 0.79%   |
| Kingston Technology Company    | 1         | 0.79%   |
| Apple                          | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 12.03%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 6.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 6.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 5.26%   |
| SanDisk Non-Volatile memory controller                                         | 5         | 3.76%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.76%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 3.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 3.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 3.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 3.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 3.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.26%   |
| Micron Non-Volatile memory controller                                          | 3         | 2.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.26%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.5%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 1.5%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.5%    |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.5%    |
| Intel SSD 660P Series                                                          | 2         | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.5%    |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 1         | 0.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.75%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.75%   |
| SK hynix BC511                                                                 | 1         | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.75%   |
| Samsung Electronics SATA controller                                            | 1         | 0.75%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.75%   |
| Intel SSD 600P Series                                                          | 1         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.75%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 0.75%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 57.36%  |
| NVMe | 33        | 25.58%  |
| RAID | 14        | 10.85%  |
| IDE  | 8         | 6.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 82        | 76.64%  |
| AMD    | 25        | 23.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 3.74%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 3.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 2.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 2.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 2.8%    |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 1.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.87%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.87%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.87%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.93%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.93%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.93%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.93%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.93%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.93%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.93%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.93%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.93%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 0.93%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.93%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.93%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 0.93%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 19.63%  |
| Intel Core i7           | 11        | 10.28%  |
| Other                   | 10        | 9.35%   |
| Intel Core i3           | 10        | 9.35%   |
| Intel Core 2 Duo        | 7         | 6.54%   |
| Intel Atom              | 7         | 6.54%   |
| Intel Celeron           | 6         | 5.61%   |
| AMD Ryzen 7             | 6         | 5.61%   |
| AMD Ryzen 5             | 6         | 5.61%   |
| Intel Pentium           | 4         | 3.74%   |
| Intel Celeron M         | 2         | 1.87%   |
| AMD Ryzen 3             | 2         | 1.87%   |
| AMD E2                  | 2         | 1.87%   |
| AMD E1                  | 2         | 1.87%   |
| Intel Pentium Silver    | 1         | 0.93%   |
| Intel Pentium M         | 1         | 0.93%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Core i9           | 1         | 0.93%   |
| Intel Core 2 Extreme    | 1         | 0.93%   |
| AMD Ryzen 9             | 1         | 0.93%   |
| AMD C-50                | 1         | 0.93%   |
| AMD Athlon              | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |
| AMD A4                  | 1         | 0.93%   |
| AMD A10                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 58.88%  |
| 4      | 25        | 23.36%  |
| 8      | 9         | 8.41%   |
| 6      | 5         | 4.67%   |
| 1      | 5         | 4.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 69.16%  |
| 1      | 33        | 30.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 96.26%  |
| 32-bit         | 4         | 3.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 8         | 7.41%   |
| 0x40651    | 7         | 6.48%   |
| 0x306a9    | 7         | 6.48%   |
| 0x806ec    | 6         | 5.56%   |
| 0x08608103 | 6         | 5.56%   |
| 0x806e9    | 5         | 4.63%   |
| 0x406e3    | 5         | 4.63%   |
| 0x30661    | 4         | 3.7%    |
| 0x08108109 | 4         | 3.7%    |
| 0x6fd      | 3         | 2.78%   |
| 0x20652    | 3         | 2.78%   |
| 0x1067a    | 3         | 2.78%   |
| 0x10676    | 3         | 2.78%   |
| Unknown    | 3         | 2.78%   |
| 0x706e5    | 2         | 1.85%   |
| 0x706a1    | 2         | 1.85%   |
| 0x406c4    | 2         | 1.85%   |
| 0x306c3    | 2         | 1.85%   |
| 0x0a50000c | 2         | 1.85%   |
| 0x06006705 | 2         | 1.85%   |
| 0xa0652    | 1         | 0.93%   |
| 0x906ed    | 1         | 0.93%   |
| 0x906ea    | 1         | 0.93%   |
| 0x806ea    | 1         | 0.93%   |
| 0x806d1    | 1         | 0.93%   |
| 0x706a8    | 1         | 0.93%   |
| 0x6f6      | 1         | 0.93%   |
| 0x6ec      | 1         | 0.93%   |
| 0x6d8      | 1         | 0.93%   |
| 0x506e3    | 1         | 0.93%   |
| 0x506c9    | 1         | 0.93%   |
| 0x306d4    | 1         | 0.93%   |
| 0x30678    | 1         | 0.93%   |
| 0x30673    | 1         | 0.93%   |
| 0x206a7    | 1         | 0.93%   |
| 0x20655    | 1         | 0.93%   |
| 0x106e5    | 1         | 0.93%   |
| 0x106ca    | 1         | 0.93%   |
| 0x106c2    | 1         | 0.93%   |
| 0x0a404101 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 12.96%  |
| Haswell       | 9         | 8.33%   |
| TigerLake     | 8         | 7.41%   |
| Unknown       | 8         | 7.41%   |
| IvyBridge     | 7         | 6.48%   |
| Skylake       | 6         | 5.56%   |
| Penryn        | 6         | 5.56%   |
| Bonnell       | 6         | 5.56%   |
| Zen+          | 5         | 4.63%   |
| Westmere      | 4         | 3.7%    |
| Silvermont    | 4         | 3.7%    |
| Excavator     | 4         | 3.7%    |
| Core          | 4         | 3.7%    |
| Zen 3         | 3         | 2.78%   |
| IceLake       | 3         | 2.78%   |
| Goldmont plus | 3         | 2.78%   |
| Puma          | 2         | 1.85%   |
| P6            | 2         | 1.85%   |
| Jaguar        | 2         | 1.85%   |
| Broadwell     | 2         | 1.85%   |
| Zen 2         | 1         | 0.93%   |
| SandyBridge   | 1         | 0.93%   |
| Nehalem       | 1         | 0.93%   |
| Goldmont      | 1         | 0.93%   |
| CometLake     | 1         | 0.93%   |
| Bobcat        | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 58.4%   |
| AMD    | 30        | 24%     |
| Nvidia | 22        | 17.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 5.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 4.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.65%   |
| AMD Lucienne                                                                             | 6         | 4.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.88%   |
| Intel HD Graphics 620                                                                    | 4         | 3.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.1%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 3.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.33%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.55%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 1.55%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.55%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.78%   |
| Nvidia GT216M [GeForce GT 325M]                                                          | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.78%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.78%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.78%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.78%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.78%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                          | 1         | 0.78%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.78%   |
| Nvidia G94GLM [Quadro FX 2700M]                                                          | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 53.27%  |
| 1 x AMD        | 24        | 22.43%  |
| Intel + Nvidia | 13        | 12.15%  |
| 1 x Nvidia     | 7         | 6.54%   |
| Intel + AMD    | 3         | 2.8%    |
| AMD + Nvidia   | 2         | 1.87%   |
| 2 x AMD        | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 94.44%  |
| Proprietary | 3         | 2.78%   |
| Unknown     | 3         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 57.41%  |
| 0.01-0.5   | 22        | 20.37%  |
| 1.01-2.0   | 12        | 11.11%  |
| 3.01-4.0   | 5         | 4.63%   |
| 0.51-1.0   | 5         | 4.63%   |
| 5.01-6.0   | 2         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 23.64%  |
| BOE                     | 17        | 15.45%  |
| Chimei Innolux          | 16        | 14.55%  |
| LG Display              | 15        | 13.64%  |
| Samsung Electronics     | 5         | 4.55%   |
| LG Philips              | 4         | 3.64%   |
| InfoVision              | 4         | 3.64%   |
| Apple                   | 4         | 3.64%   |
| Goldstar                | 3         | 2.73%   |
| Sharp                   | 2         | 1.82%   |
| PANDA                   | 2         | 1.82%   |
| HannStar                | 2         | 1.82%   |
| Dell                    | 2         | 1.82%   |
| Chi Mei Optoelectronics | 2         | 1.82%   |
| TR_                     | 1         | 0.91%   |
| Quanta Display          | 1         | 0.91%   |
| Planar                  | 1         | 0.91%   |
| Lenovo                  | 1         | 0.91%   |
| Insignia                | 1         | 0.91%   |
| DENON                   | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.7%    |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 1.8%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 1.8%    |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 2         | 1.8%    |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.9%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch               | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.9%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 0.9%    |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch       | 1         | 0.9%    |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                 | 1         | 0.9%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.9%    |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch           | 1         | 0.9%    |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0226 1600x900 382x215mm 17.3-inch           | 1         | 0.9%    |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch               | 1         | 0.9%    |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch          | 1         | 0.9%    |
| InfoVision LCD Monitor IVO3D2C 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch          | 1         | 0.9%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 0.9%    |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch              | 1         | 0.9%    |
| Goldstar W2486 GSM5729 1920x1080 531x299mm 24.0-inch                  | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 46        | 42.99%  |
| 1366x768 (WXGA)   | 29        | 27.1%   |
| 1920x1200 (WUXGA) | 6         | 5.61%   |
| 1600x900 (HD+)    | 6         | 5.61%   |
| 1440x900 (WXGA+)  | 4         | 3.74%   |
| 1280x800 (WXGA)   | 4         | 3.74%   |
| 1024x600          | 4         | 3.74%   |
| 3840x2160 (4K)    | 2         | 1.87%   |
| 2880x1800         | 1         | 0.93%   |
| 2560x1600         | 1         | 0.93%   |
| 2560x1440 (QHD)   | 1         | 0.93%   |
| 2256x1504         | 1         | 0.93%   |
| 1280x768          | 1         | 0.93%   |
| 1280x720 (HD)     | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 47        | 42.34%  |
| 13      | 20        | 18.02%  |
| 14      | 15        | 13.51%  |
| 17      | 9         | 8.11%   |
| 10      | 4         | 3.6%    |
| 27      | 3         | 2.7%    |
| 24      | 3         | 2.7%    |
| 21      | 2         | 1.8%    |
| 72      | 1         | 0.9%    |
| 31      | 1         | 0.9%    |
| 23      | 1         | 0.9%    |
| 16      | 1         | 0.9%    |
| 12      | 1         | 0.9%    |
| 11      | 1         | 0.9%    |
| 8       | 1         | 0.9%    |
| Unknown | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 64.55%  |
| 201-300     | 16        | 14.55%  |
| 351-400     | 11        | 10%     |
| 501-600     | 6         | 5.45%   |
| 401-500     | 2         | 1.82%   |
| 601-700     | 1         | 0.91%   |
| 1501-2000   | 1         | 0.91%   |
| 101-200     | 1         | 0.91%   |
| Unknown     | 1         | 0.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 86        | 83.5%   |
| 16/10   | 15        | 14.56%  |
| 3/2     | 1         | 0.97%   |
| Unknown | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 42.34%  |
| 81-90          | 26        | 23.42%  |
| 71-80          | 9         | 8.11%   |
| 121-130        | 6         | 5.41%   |
| 41-50          | 4         | 3.6%    |
| 201-250        | 4         | 3.6%    |
| 301-350        | 3         | 2.7%    |
| 131-140        | 3         | 2.7%    |
| 251-300        | 2         | 1.8%    |
| More than 1000 | 1         | 0.9%    |
| 61-70          | 1         | 0.9%    |
| 51-60          | 1         | 0.9%    |
| 351-500        | 1         | 0.9%    |
| 1-40           | 1         | 0.9%    |
| 91-100         | 1         | 0.9%    |
| Unknown        | 1         | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 43.24%  |
| 101-120       | 40        | 36.04%  |
| 51-100        | 13        | 11.71%  |
| 161-240       | 7         | 6.31%   |
| More than 240 | 1         | 0.9%    |
| 1-50          | 1         | 0.9%    |
| Unknown       | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 97        | 89.81%  |
| 2     | 7         | 6.48%   |
| 0     | 3         | 2.78%   |
| 3     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 58        | 36.25%  |
| Intel                         | 45        | 28.13%  |
| Qualcomm Atheros              | 26        | 16.25%  |
| Broadcom                      | 13        | 8.13%   |
| Marvell Technology Group      | 3         | 1.88%   |
| Broadcom Limited              | 3         | 1.88%   |
| Ralink Technology             | 2         | 1.25%   |
| Xiaomi                        | 1         | 0.63%   |
| TP-Link                       | 1         | 0.63%   |
| Ralink                        | 1         | 0.63%   |
| OnePlus Technology (Shenzhen) | 1         | 0.63%   |
| MediaTek                      | 1         | 0.63%   |
| JMicron Technology            | 1         | 0.63%   |
| Google                        | 1         | 0.63%   |
| Edimax Technology             | 1         | 0.63%   |
| Dell                          | 1         | 0.63%   |
| Davicom Semiconductor         | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 13%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 5.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.5%    |
| Intel Wireless 3165                                               | 5         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.5%    |
| Intel Wireless 8265 / 8275                                        | 4         | 2%      |
| Intel Wi-Fi 6 AX200                                               | 4         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 2%      |
| Intel Wireless 7260                                               | 3         | 1.5%    |
| Intel WiFi Link 5100                                              | 3         | 1.5%    |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.5%    |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 1.5%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1%      |
| Realtek 802.11ac NIC                                              | 2         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1%      |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1%      |
| Intel Wireless 8260                                               | 2         | 1%      |
| Intel Ethernet Connection I219-V                                  | 2         | 1%      |
| Intel Ethernet Connection I218-LM                                 | 2         | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1%      |
| Broadcom BCM43225 802.11b/g/n                                     | 2         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 37.84%  |
| Realtek Semiconductor | 29        | 26.13%  |
| Qualcomm Atheros      | 20        | 18.02%  |
| Broadcom              | 11        | 9.91%   |
| Broadcom Limited      | 3         | 2.7%    |
| Ralink Technology     | 2         | 1.8%    |
| TP-Link               | 1         | 0.9%    |
| Ralink                | 1         | 0.9%    |
| MediaTek              | 1         | 0.9%    |
| Edimax Technology     | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 9.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 4.39%   |
| Intel Wireless 3165                                            | 5         | 4.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 4.39%   |
| Intel Wireless 8265 / 8275                                     | 4         | 3.51%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 3.51%   |
| Intel Wireless 7260                                            | 3         | 2.63%   |
| Intel WiFi Link 5100                                           | 3         | 2.63%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.63%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 2.63%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.75%   |
| Realtek 802.11ac NIC                                           | 2         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.75%   |
| Intel Wireless 8260                                            | 2         | 1.75%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.88%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.88%   |
| Realtek RTL8187B Wireless Adapter                              | 1         | 0.88%   |
| Realtek Realtek Network controller                             | 1         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.88%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.88%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 45        | 53.57%  |
| Intel                         | 19        | 22.62%  |
| Qualcomm Atheros              | 10        | 11.9%   |
| Marvell Technology Group      | 3         | 3.57%   |
| Broadcom                      | 2         | 2.38%   |
| Xiaomi                        | 1         | 1.19%   |
| OnePlus Technology (Shenzhen) | 1         | 1.19%   |
| JMicron Technology            | 1         | 1.19%   |
| Google                        | 1         | 1.19%   |
| Davicom Semiconductor         | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 30.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 15.48%  |
| Intel 82567LM Gigabit Network Connection                          | 4         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 2.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 2.38%   |
| Intel Ethernet Connection I219-V                                  | 2         | 2.38%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.19%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.19%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.19%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 1.19%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.19%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.19%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.19%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.19%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.19%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.19%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.19%   |
| Davicom DM9621A USB To FastEther                                  | 1         | 1.19%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.19%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 55.85%  |
| Ethernet | 81        | 43.09%  |
| Modem    | 2         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 76.85%  |
| Ethernet | 25        | 23.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 75        | 70.09%  |
| 1     | 28        | 26.17%  |
| 0     | 4         | 3.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 70.09%  |
| Yes  | 32        | 29.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 42.31%  |
| Realtek Semiconductor           | 18        | 23.08%  |
| Foxconn / Hon Hai               | 5         | 6.41%   |
| Qualcomm Atheros Communications | 4         | 5.13%   |
| Lite-On Technology              | 3         | 3.85%   |
| Hewlett-Packard                 | 3         | 3.85%   |
| Dell                            | 3         | 3.85%   |
| Apple                           | 3         | 3.85%   |
| IMC Networks                    | 2         | 2.56%   |
| Foxconn International           | 2         | 2.56%   |
| Broadcom                        | 2         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 15        | 19.23%  |
| Realtek Bluetooth Radio                           | 12        | 15.38%  |
| Intel AX201 Bluetooth                             | 7         | 8.97%   |
| Realtek  Bluetooth 4.2 Adapter                    | 5         | 6.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 5         | 6.41%   |
| Intel AX200 Bluetooth                             | 4         | 5.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 3         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                | 2         | 2.56%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 2.56%   |
| Foxconn International BCM43142A0 Bluetooth module | 2         | 2.56%   |
| Dell Wireless 370 Bluetooth Mini-card             | 2         | 2.56%   |
| Apple Bluetooth USB Host Controller               | 2         | 2.56%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 1.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.28%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.28%   |
| Intel AX210 Bluetooth                             | 1         | 1.28%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.28%   |
| IMC Networks Bluetooth Device                     | 1         | 1.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.28%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 1.28%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 1.28%   |
| Foxconn / Hon Hai Acer Module                     | 1         | 1.28%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 1         | 1.28%   |
| Dell BCM20702A0 Bluetooth Module                  | 1         | 1.28%   |
| Broadcom HP Portable SoftSailing                  | 1         | 1.28%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]  | 1         | 1.28%   |
| Apple Bluetooth Host Controller                   | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 62.99%  |
| AMD                   | 30        | 23.62%  |
| Nvidia                | 11        | 8.66%   |
| Texas Instruments     | 2         | 1.57%   |
| Yamaha                | 1         | 0.79%   |
| Realtek Semiconductor | 1         | 0.79%   |
| GN Netcom             | 1         | 0.79%   |
| Audioengine           | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 9.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 6.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 4.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 4.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 4.35%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 4.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 3.11%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 2.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.86%   |
| AMD High Definition Audio Controller                                       | 3         | 1.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.24%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.24%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.24%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 1.24%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.62%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.62%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 0.62%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia Audio device                                                        | 1         | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.62%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.62%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 15        | 30%     |
| SK hynix                     | 14        | 28%     |
| Unknown                      | 5         | 10%     |
| Micron Technology            | 3         | 6%      |
| Unknown (ABCD)               | 2         | 4%      |
| Nanya Technology             | 2         | 4%      |
| Kingston                     | 2         | 4%      |
| A-DATA Technology            | 2         | 4%      |
| Ramaxel Technology           | 1         | 2%      |
| Patriot Memory (PDP Systems) | 1         | 2%      |
| Crucial                      | 1         | 2%      |
| Corsair                      | 1         | 2%      |
| Unknown                      | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s         | 2         | 3.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                   | 2         | 3.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 3.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 2         | 3.85%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                              | 1         | 1.92%   |
| Unknown RAM Module 512MB SODIMM DDR                                      | 1         | 1.92%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                              | 1         | 1.92%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                               | 1         | 1.92%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 1.92%   |
| Unknown RAM Module 1GB SODIMM DDR                                        | 1         | 1.92%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                            | 1         | 1.92%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                             | 1         | 1.92%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                            | 1         | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s                | 1         | 1.92%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 1.92%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                    | 1         | 1.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s              | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 1         | 1.92%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                 | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.92%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.92%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.92%   |
| Ramaxel RAM RMSA3330MJ78HBF-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 1.92%   |
| Patriot Memory (PDP Systems) RAM PSD432G32002S 32GB SODIMM DDR4 3200MT/s | 1         | 1.92%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s                     | 1         | 1.92%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.92%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 1.92%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 26        | 55.32%  |
| DDR3   | 14        | 29.79%  |
| LPDDR4 | 3         | 6.38%   |
| SDRAM  | 2         | 4.26%   |
| DDR2   | 1         | 2.13%   |
| DDR    | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 95.83%  |
| Row Of Chips | 2         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 19        | 37.25%  |
| 4096  | 14        | 27.45%  |
| 2048  | 9         | 17.65%  |
| 16384 | 5         | 9.8%    |
| 32768 | 2         | 3.92%   |
| 1024  | 1         | 1.96%   |
| 512   | 1         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 15        | 31.25%  |
| 1600    | 12        | 25%     |
| 2667    | 7         | 14.58%  |
| 2400    | 5         | 10.42%  |
| 4267    | 1         | 2.08%   |
| 4199    | 1         | 2.08%   |
| 2267    | 1         | 2.08%   |
| 2048    | 1         | 2.08%   |
| 1334    | 1         | 2.08%   |
| 1333    | 1         | 2.08%   |
| 1200    | 1         | 2.08%   |
| 667     | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 19        | 21.11%  |
| Microdia                               | 13        | 14.44%  |
| Suyin                                  | 9         | 10%     |
| IMC Networks                           | 9         | 10%     |
| Acer                                   | 9         | 10%     |
| Sunplus Innovation Technology          | 6         | 6.67%   |
| Realtek Semiconductor                  | 6         | 6.67%   |
| Quanta                                 | 6         | 6.67%   |
| Alcor Micro                            | 3         | 3.33%   |
| Luxvisions Innotech Limited            | 2         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.22%   |
| Lite-On Technology                     | 1         | 1.11%   |
| Lenovo                                 | 1         | 1.11%   |
| Intel                                  | 1         | 1.11%   |
| icSpring                               | 1         | 1.11%   |
| Apple                                  | 1         | 1.11%   |
| ALi                                    | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 9         | 10%     |
| Chicony Integrated Camera                            | 6         | 6.67%   |
| Quanta HP TrueVision HD Camera                       | 3         | 3.33%   |
| Chicony HP TrueVision HD Camera                      | 3         | 3.33%   |
| Chicony HD WebCam                                    | 3         | 3.33%   |
| Acer Integrated Camera                               | 3         | 3.33%   |
| Suyin HP TrueVision HD                               | 2         | 2.22%   |
| Suyin Acer HD Crystal Eye webcam                     | 2         | 2.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.22%   |
| IMC Networks Integrated Camera                       | 2         | 2.22%   |
| Alcor Micro SHUNCCM2MP                               | 2         | 2.22%   |
| Acer USB2.0 Camera                                   | 2         | 2.22%   |
| Suyin HP Webcam-101                                  | 1         | 1.11%   |
| Suyin HD WebCam                                      | 1         | 1.11%   |
| Suyin Acer/Lenovo Webcam [CN0316]                    | 1         | 1.11%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.11%   |
| Suyin 1.3M HD WebCam                                 | 1         | 1.11%   |
| Sunplus MTD Camera                                   | 1         | 1.11%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 1.11%   |
| Sunplus HP TrueVision HD Camera                      | 1         | 1.11%   |
| Sunplus HD WebCam                                    | 1         | 1.11%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 1.11%   |
| Sunplus 1.3M HD WebCam                               | 1         | 1.11%   |
| Realtek USB2.0 camera                                | 1         | 1.11%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.11%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.11%   |
| Realtek HP Truevision HD integrated webcam           | 1         | 1.11%   |
| Realtek HP Truevision HD                             | 1         | 1.11%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 1.11%   |
| Quanta VGA WebCam                                    | 1         | 1.11%   |
| Quanta HP Webcam                                     | 1         | 1.11%   |
| Quanta HP HD Camera                                  | 1         | 1.11%   |
| Microdia Lenovo EasyCamera                           | 1         | 1.11%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.11%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.11%   |
| Microdia Integrated Webcam                           | 1         | 1.11%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.11%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.11%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 50%     |
| Synaptics                  | 1         | 8.33%   |
| STMicroelectronics         | 1         | 8.33%   |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| Focal-systems.Corp         | 1         | 8.33%   |
| Elan Microelectronics      | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 16.67%  |
| Validity Sensors Synaptics WBDI            | 2         | 16.67%  |
| Validity Sensors VFS491                    | 1         | 8.33%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader      | 1         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 8.33%   |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 8.33%   |
| Elan ELAN:Fingerprint                      | 1         | 8.33%   |
| AuthenTec AES1600                          | 1         | 8.33%   |
| Unknown                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 71        | 65.14%  |
| 1     | 33        | 30.28%  |
| 2     | 4         | 3.67%   |
| 4     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 24.44%  |
| Fingerprint reader    | 11        | 24.44%  |
| Multimedia controller | 10        | 22.22%  |
| Graphics card         | 6         | 13.33%  |
| Chipcard              | 6         | 13.33%  |
| Dvb card              | 1         | 2.22%   |

