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

Total: 160

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| Dell          | XPS L701X                   | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| HP            | Laptop 14-cf3xxx            | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
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
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| AMI           | T3 MRD                      | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
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
| 5.10.0-12-amd64      | 22        | 17.05%  |
| 5.10.0-14-amd64      | 20        | 15.5%   |
| 5.10.0-15-amd64      | 16        | 12.4%   |
| 5.10.0-13-amd64      | 14        | 10.85%  |
| 5.10.0-18-amd64      | 13        | 10.08%  |
| 5.10.0-16-amd64      | 10        | 7.75%   |
| 5.10.0-17-amd64      | 8         | 6.2%    |
| 5.10.0-19-amd64      | 6         | 4.65%   |
| 5.10.0-13-686        | 5         | 3.88%   |
| 5.18.0-0.bpo.1-amd64 | 4         | 3.1%    |
| 5.16.0-0.bpo.4-amd64 | 3         | 2.33%   |
| 5.19.10-xanmod1      | 1         | 0.78%   |
| 5.18.0-4-amd64       | 1         | 0.78%   |
| 5.18.0-3-amd64       | 1         | 0.78%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.78%   |
| 5.15.70-xanmod1      | 1         | 0.78%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.78%   |
| 5.10.0-17-686        | 1         | 0.78%   |
| 5.10.0-14-686        | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 111       | 90.24%  |
| 5.18.0  | 6         | 4.88%   |
| 5.16.0  | 3         | 2.44%   |
| 5.19.10 | 1         | 0.81%   |
| 5.15.70 | 1         | 0.81%   |
| 5.15.0  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 111       | 90.24%  |
| 5.18    | 6         | 4.88%   |
| 5.16    | 3         | 2.44%   |
| 5.15    | 2         | 1.63%   |
| 5.19    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 94.17%  |
| i686   | 7         | 5.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 108       | 90%     |
| Cinnamon   | 9         | 7.5%    |
| XFCE       | 1         | 0.83%   |
| MATE       | 1         | 0.83%   |
| Unknown    | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 120       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 59.17%  |
| LightDM | 49        | 40.83%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 43        | 35.54%  |
| de_DE | 16        | 13.22%  |
| ru_RU | 12        | 9.92%   |
| pt_BR | 7         | 5.79%   |
| en_GB | 7         | 5.79%   |
| fr_FR | 5         | 4.13%   |
| es_ES | 4         | 3.31%   |
| it_IT | 3         | 2.48%   |
| es_MX | 3         | 2.48%   |
| pl_PL | 2         | 1.65%   |
| ko_KR | 2         | 1.65%   |
| es_BO | 2         | 1.65%   |
| en_IE | 2         | 1.65%   |
| pt_PT | 1         | 0.83%   |
| nn_NO | 1         | 0.83%   |
| nl_AW | 1         | 0.83%   |
| hu_HU | 1         | 0.83%   |
| fr_BE | 1         | 0.83%   |
| es_PE | 1         | 0.83%   |
| es_EC | 1         | 0.83%   |
| es_CR | 1         | 0.83%   |
| en_NZ | 1         | 0.83%   |
| en_IN | 1         | 0.83%   |
| en_CA | 1         | 0.83%   |
| da_DK | 1         | 0.83%   |
| cs_CZ | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 82        | 67.77%  |
| BIOS | 39        | 32.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 110       | 91.67%  |
| Overlay | 5         | 4.17%   |
| Tmpfs   | 2         | 1.67%   |
| Btrfs   | 2         | 1.67%   |
| Xfs     | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 58.33%  |
| GPT     | 43        | 35.83%  |
| MBR     | 7         | 5.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 113       | 93.39%  |
| Yes       | 8         | 6.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 90%     |
| Yes       | 12        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 22.5%   |
| Lenovo              | 20        | 16.67%  |
| Dell                | 20        | 16.67%  |
| Acer                | 12        | 10%     |
| ASUSTek Computer    | 11        | 9.17%   |
| Apple               | 4         | 3.33%   |
| Toshiba             | 3         | 2.5%    |
| Sony                | 3         | 2.5%    |
| MSI                 | 2         | 1.67%   |
| Medion              | 2         | 1.67%   |
| Unknown             | 2         | 1.67%   |
| Wortmann AG         | 1         | 0.83%   |
| Samsung Electronics | 1         | 0.83%   |
| Philco              | 1         | 0.83%   |
| Packard Bell        | 1         | 0.83%   |
| Multilaser          | 1         | 0.83%   |
| Microtech           | 1         | 0.83%   |
| LincPlus            | 1         | 0.83%   |
| Howard Computers    | 1         | 0.83%   |
| Google              | 1         | 0.83%   |
| Framework           | 1         | 0.83%   |
| Dynabook            | 1         | 0.83%   |
| Dixonsxp            | 1         | 0.83%   |
| AMI                 | 1         | 0.83%   |
| Alienware           | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 3         | 2.5%    |
| Lenovo IdeaPad 3 15ADA05 81W1         | 2         | 1.67%   |
| HP Laptop 15z-ef2xxx                  | 2         | 1.67%   |
| Dell Latitude E6400                   | 2         | 1.67%   |
| Dell Latitude E5540                   | 2         | 1.67%   |
| Acer Aspire 5930                      | 2         | 1.67%   |
| Wortmann AG TERRA_MOBILE_1713A        | 1         | 0.83%   |
| Toshiba Satellite M55                 | 1         | 0.83%   |
| Toshiba Satellite L855D               | 1         | 0.83%   |
| Toshiba Satellite L455                | 1         | 0.83%   |
| Sony SVF1532W4E                       | 1         | 0.83%   |
| Sony SVE1713Y1RB                      | 1         | 0.83%   |
| Sony SVE1512G1RW                      | 1         | 0.83%   |
| Samsung 355V4C/356V4C/3445VC/3545VC   | 1         | 0.83%   |
| Philco 10D                            | 1         | 0.83%   |
| Packard Bell DOT S                    | 1         | 0.83%   |
| Multilaser PC150                      | 1         | 0.83%   |
| MSI U180                              | 1         | 0.83%   |
| MSI GL73 8SE                          | 1         | 0.83%   |
| Microtech ebookPro                    | 1         | 0.83%   |
| Medion P15648                         | 1         | 0.83%   |
| Medion E6220                          | 1         | 0.83%   |
| LincPlus LINNCPLUS P1                 | 1         | 0.83%   |
| Lenovo Z50-70 20354                   | 1         | 0.83%   |
| Lenovo Yoga 2 11 20332                | 1         | 0.83%   |
| Lenovo ThinkPad X270 W10DG 20K5S3HG00 | 1         | 0.83%   |
| Lenovo ThinkPad T61 7661A16           | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L6S1RN00       | 1         | 0.83%   |
| Lenovo ThinkPad T470s 20HF0047UK      | 1         | 0.83%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS | 1         | 0.83%   |
| Lenovo ThinkPad T450 20BUS0QT04       | 1         | 0.83%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100  | 1         | 0.83%   |
| Lenovo ThinkPad E14 Gen 2 20TACTO1WW  | 1         | 0.83%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ      | 1         | 0.83%   |
| Lenovo Legion 5 15ACH6H 82JU          | 1         | 0.83%   |
| Lenovo IdeaPad S340-15APITouch 81QG   | 1         | 0.83%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 1         | 0.83%   |
| Lenovo IdeaPad 320-15IKB 80XL         | 1         | 0.83%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 1         | 0.83%   |
| Lenovo IdeaPad 3 14ALC6 82KT          | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 10        | 8.33%   |
| HP Laptop            | 9         | 7.5%    |
| Lenovo ThinkPad      | 8         | 6.67%   |
| Dell Latitude        | 8         | 6.67%   |
| Lenovo IdeaPad       | 7         | 5.83%   |
| Dell Inspiron        | 6         | 5%      |
| ASUS VivoBook        | 5         | 4.17%   |
| Toshiba Satellite    | 3         | 2.5%    |
| HP Pavilion          | 3         | 2.5%    |
| HP EliteBook         | 3         | 2.5%    |
| Unknown              | 3         | 2.5%    |
| Lenovo Legion        | 2         | 1.67%   |
| HP ProBook           | 2         | 1.67%   |
| HP Compaq            | 2         | 1.67%   |
| HP 255               | 2         | 1.67%   |
| Dell XPS             | 2         | 1.67%   |
| Dell Vostro          | 2         | 1.67%   |
| Dell Precision       | 2         | 1.67%   |
| ASUS ROG             | 2         | 1.67%   |
| Wortmann AG TERRA    | 1         | 0.83%   |
| Sony SVF1532W4E      | 1         | 0.83%   |
| Sony SVE1713Y1RB     | 1         | 0.83%   |
| Sony SVE1512G1RW     | 1         | 0.83%   |
| Samsung 355V4C       | 1         | 0.83%   |
| Philco 10D           | 1         | 0.83%   |
| Packard Bell DOT     | 1         | 0.83%   |
| Multilaser PC150     | 1         | 0.83%   |
| MSI U180             | 1         | 0.83%   |
| MSI GL73             | 1         | 0.83%   |
| Microtech ebookPro   | 1         | 0.83%   |
| Medion P15648        | 1         | 0.83%   |
| Medion E6220         | 1         | 0.83%   |
| LincPlus LINNCPLUS   | 1         | 0.83%   |
| Lenovo Z50-70        | 1         | 0.83%   |
| Lenovo Yoga          | 1         | 0.83%   |
| Lenovo G500          | 1         | 0.83%   |
| Howard Computers R7X | 1         | 0.83%   |
| HP ZBook             | 1         | 0.83%   |
| HP Presario          | 1         | 0.83%   |
| HP Notebook          | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 15%     |
| 2020 | 12        | 10%     |
| 2012 | 11        | 9.17%   |
| 2019 | 10        | 8.33%   |
| 2013 | 10        | 8.33%   |
| 2017 | 9         | 7.5%    |
| 2010 | 8         | 6.67%   |
| 2016 | 7         | 5.83%   |
| 2018 | 6         | 5%      |
| 2014 | 6         | 5%      |
| 2008 | 6         | 5%      |
| 2015 | 4         | 3.33%   |
| 2009 | 4         | 3.33%   |
| 2022 | 3         | 2.5%    |
| 2007 | 3         | 2.5%    |
| 2011 | 2         | 1.67%   |
| 2006 | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 120       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 106       | 87.6%   |
| Enabled  | 15        | 12.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 99.17%  |
| Yes  | 1         | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 34        | 28.33%  |
| 3.01-4.0    | 29        | 24.17%  |
| 8.01-16.0   | 20        | 16.67%  |
| 16.01-24.0  | 19        | 15.83%  |
| 1.01-2.0    | 8         | 6.67%   |
| 32.01-64.0  | 4         | 3.33%   |
| 2.01-3.0    | 4         | 3.33%   |
| 64.01-256.0 | 2         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 52        | 41.27%  |
| 2.01-3.0   | 45        | 35.71%  |
| 3.01-4.0   | 12        | 9.52%   |
| 4.01-8.0   | 9         | 7.14%   |
| 0.51-1.0   | 6         | 4.76%   |
| 32.01-64.0 | 1         | 0.79%   |
| 8.01-16.0  | 1         | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 73.77%  |
| 2      | 28        | 22.95%  |
| 3      | 3         | 2.46%   |
| 4      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 68.33%  |
| Yes       | 38        | 31.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 77.5%   |
| No        | 27        | 22.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 98.33%  |
| No        | 2         | 1.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 73.33%  |
| No        | 32        | 26.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 18        | 14.75%  |
| Germany     | 17        | 13.93%  |
| Russia      | 14        | 11.48%  |
| UK          | 8         | 6.56%   |
| Brazil      | 8         | 6.56%   |
| Italy       | 5         | 4.1%    |
| France      | 5         | 4.1%    |
| Spain       | 4         | 3.28%   |
| Poland      | 4         | 3.28%   |
| Mexico      | 3         | 2.46%   |
| Canada      | 3         | 2.46%   |
| Belgium     | 3         | 2.46%   |
| South Korea | 2         | 1.64%   |
| Romania     | 2         | 1.64%   |
| Hungary     | 2         | 1.64%   |
| Chile       | 2         | 1.64%   |
| Bolivia     | 2         | 1.64%   |
| Vietnam     | 1         | 0.82%   |
| Sweden      | 1         | 0.82%   |
| Slovenia    | 1         | 0.82%   |
| Portugal    | 1         | 0.82%   |
| Peru        | 1         | 0.82%   |
| Paraguay    | 1         | 0.82%   |
| Norway      | 1         | 0.82%   |
| New Zealand | 1         | 0.82%   |
| Malaysia    | 1         | 0.82%   |
| Lithuania   | 1         | 0.82%   |
| Kenya       | 1         | 0.82%   |
| Ireland     | 1         | 0.82%   |
| India       | 1         | 0.82%   |
| Finland     | 1         | 0.82%   |
| Ecuador     | 1         | 0.82%   |
| Denmark     | 1         | 0.82%   |
| Czechia     | 1         | 0.82%   |
| Costa Rica  | 1         | 0.82%   |
| Belarus     | 1         | 0.82%   |
| Austria     | 1         | 0.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 5         | 4.07%   |
| St Petersburg        | 2         | 1.63%   |
| Oruro                | 2         | 1.63%   |
| Neasden              | 2         | 1.63%   |
| Freiburg im Breisgau | 2         | 1.63%   |
| Berlin               | 2         | 1.63%   |
| Zaragoza             | 1         | 0.81%   |
| Wroclaw              | 1         | 0.81%   |
| Voronezh             | 1         | 0.81%   |
| Vilshofen            | 1         | 0.81%   |
| Vilnius              | 1         | 0.81%   |
| Viggianello          | 1         | 0.81%   |
| Viet Tri             | 1         | 0.81%   |
| Veurne               | 1         | 0.81%   |
| Vaslui               | 1         | 0.81%   |
| Valsoyfjord          | 1         | 0.81%   |
| Uiwang               | 1         | 0.81%   |
| Turku                | 1         | 0.81%   |
| Tula                 | 1         | 0.81%   |
| Troisdorf            | 1         | 0.81%   |
| Toulouse             | 1         | 0.81%   |
| Toronto              | 1         | 0.81%   |
| Tipton               | 1         | 0.81%   |
| Spearfish            | 1         | 0.81%   |
| Smolensk             | 1         | 0.81%   |
| Scarborough          | 1         | 0.81%   |
| Saratov              | 1         | 0.81%   |
| Sao Paulo            | 1         | 0.81%   |
| Santiago             | 1         | 0.81%   |
| San Jose             | 1         | 0.81%   |
| Rottenburg           | 1         | 0.81%   |
| Rome                 | 1         | 0.81%   |
| Rochester            | 1         | 0.81%   |
| Recife               | 1         | 0.81%   |
| Providencia          | 1         | 0.81%   |
| Prague               | 1         | 0.81%   |
| Petaling Jaya        | 1         | 0.81%   |
| Ordonnac             | 1         | 0.81%   |
| Oberhausen           | 1         | 0.81%   |
| Nuremberg            | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 21        | 23     | 13.91%  |
| Seagate                        | 16        | 19     | 10.6%   |
| Samsung Electronics            | 14        | 15     | 9.27%   |
| SanDisk                        | 11        | 13     | 7.28%   |
| Unknown                        | 10        | 14     | 6.62%   |
| Kingston                       | 7         | 7      | 4.64%   |
| Toshiba                        | 6         | 7      | 3.97%   |
| Intel                          | 6         | 6      | 3.97%   |
| Hitachi                        | 6         | 6      | 3.97%   |
| SK hynix                       | 4         | 4      | 2.65%   |
| PNY                            | 4         | 4      | 2.65%   |
| Micron Technology              | 4         | 4      | 2.65%   |
| Crucial                        | 4         | 4      | 2.65%   |
| Apple                          | 4         | 9      | 2.65%   |
| Patriot                        | 3         | 3      | 1.99%   |
| Team                           | 2         | 2      | 1.32%   |
| Phison                         | 2         | 2      | 1.32%   |
| KingSpec                       | 2         | 2      | 1.32%   |
| HGST                           | 2         | 2      | 1.32%   |
| A-DATA Technology              | 2         | 3      | 1.32%   |
| Union Memory                   | 1         | 1      | 0.66%   |
| UMIS                           | 1         | 1      | 0.66%   |
| SSD PHIS                       | 1         | 1      | 0.66%   |
| Solid State Storage Technology | 1         | 1      | 0.66%   |
| ShiJi                          | 1         | 1      | 0.66%   |
| SABRENT                        | 1         | 1      | 0.66%   |
| Oyen                           | 1         | 1      | 0.66%   |
| ORICO                          | 1         | 1      | 0.66%   |
| Microtech                      | 1         | 2      | 0.66%   |
| Micron/Crucial Technology      | 1         | 2      | 0.66%   |
| LITEON                         | 1         | 1      | 0.66%   |
| KIOXIA                         | 1         | 4      | 0.66%   |
| Initio                         | 1         | 1      | 0.66%   |
| HXY                            | 1         | 1      | 0.66%   |
| Gigabyte Technology            | 1         | 1      | 0.66%   |
| Fujitsu                        | 1         | 1      | 0.66%   |
| FORESEE                        | 1         | 1      | 0.66%   |
| China                          | 1         | 2      | 0.66%   |
| BHT                            | 1         | 2      | 0.66%   |
| Acer                           | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 6         | 3.85%   |
| Unknown SD/MMC/MS PRO 1TB               | 3         | 1.92%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 1.92%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 1.28%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 2         | 1.28%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 2         | 1.28%   |
| Unknown SC128  128GB                    | 2         | 1.28%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.28%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 1.28%   |
| Samsung PM991a NVMe 512GB               | 2         | 1.28%   |
| Patriot Burst 240GB SSD                 | 2         | 1.28%   |
| Micron NVMe SSD Drive 512GB             | 2         | 1.28%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 1.28%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.28%   |
| Apple SSD SD0128F 121GB                 | 2         | 1.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.64%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD        | 1         | 0.64%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.64%   |
| WDC WDBNCE5000PNC 500GB SSD             | 1         | 0.64%   |
| WDC WD7500BPVT-22HXZT3 752GB            | 1         | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.64%   |
| WDC WD5000BPVX-00JC3T0 500GB            | 1         | 0.64%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 0.64%   |
| WDC WD3200BEVT-60ZCT0 320GB             | 1         | 0.64%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 0.64%   |
| WDC WD30 EFRX-68EUZN0 3TB               | 1         | 0.64%   |
| WDC WD10SPZX-60Z10T1 1TB                | 1         | 0.64%   |
| WDC WD10JPVT-55A1YT0 1TB                | 1         | 0.64%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 1         | 0.64%   |
| WDC PC SN530 NVMe 256GB                 | 1         | 0.64%   |
| WDC PC SA530 SDASN8Y1T00 1024GB         | 1         | 0.64%   |
| Unknown USB DISK 3.2 250GB              | 1         | 0.64%   |
| Unknown SP32G  32GB                     | 1         | 0.64%   |
| Unknown MMC Card  64GB                  | 1         | 0.64%   |
| Unknown MMC Card  32GB                  | 1         | 0.64%   |
| Unknown Biwin  64GB                     | 1         | 0.64%   |
| Unknown Biwin  32GB                     | 1         | 0.64%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB | 1         | 0.64%   |
| UMIS RPJTJ512MGE1QDQ 512GB              | 1         | 0.64%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 19     | 34.04%  |
| WDC     | 12        | 13     | 25.53%  |
| Hitachi | 6         | 6      | 12.77%  |
| Toshiba | 5         | 6      | 10.64%  |
| Unknown | 3         | 3      | 6.38%   |
| HGST    | 2         | 2      | 4.26%   |
| SABRENT | 1         | 1      | 2.13%   |
| Initio  | 1         | 1      | 2.13%   |
| Fujitsu | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 11.32%  |
| Samsung Electronics | 5         | 6      | 9.43%   |
| SanDisk             | 4         | 4      | 7.55%   |
| PNY                 | 4         | 4      | 7.55%   |
| Crucial             | 4         | 4      | 7.55%   |
| WDC                 | 3         | 3      | 5.66%   |
| Patriot             | 3         | 3      | 5.66%   |
| Intel               | 3         | 3      | 5.66%   |
| Apple               | 3         | 3      | 5.66%   |
| Team                | 2         | 2      | 3.77%   |
| KingSpec            | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 3      | 3.77%   |
| SSD PHIS            | 1         | 1      | 1.89%   |
| ORICO               | 1         | 1      | 1.89%   |
| Microtech           | 1         | 2      | 1.89%   |
| Micron Technology   | 1         | 1      | 1.89%   |
| LITEON              | 1         | 1      | 1.89%   |
| HXY                 | 1         | 1      | 1.89%   |
| Gigabyte Technology | 1         | 1      | 1.89%   |
| FORESEE             | 1         | 1      | 1.89%   |
| China               | 1         | 2      | 1.89%   |
| BHT                 | 1         | 2      | 1.89%   |
| Acer                | 1         | 1      | 1.89%   |
| Unknown             | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 48        | 58     | 34.53%  |
| HDD     | 44        | 52     | 31.65%  |
| NVMe    | 36        | 52     | 25.9%   |
| MMC     | 7         | 10     | 5.04%   |
| Unknown | 4         | 5      | 2.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 103    | 62.69%  |
| NVMe | 36        | 52     | 26.87%  |
| SAS  | 7         | 12     | 5.22%   |
| MMC  | 7         | 10     | 5.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 73     | 67.03%  |
| 0.51-1.0   | 27        | 34     | 29.67%  |
| 2.01-3.0   | 1         | 1      | 1.1%    |
| 1.01-2.0   | 1         | 1      | 1.1%    |
| 4.01-10.0  | 1         | 1      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 32.79%  |
| 251-500        | 32        | 26.23%  |
| 501-1000       | 17        | 13.93%  |
| 51-100         | 9         | 7.38%   |
| 1001-2000      | 8         | 6.56%   |
| 21-50          | 7         | 5.74%   |
| 1-20           | 6         | 4.92%   |
| More than 3000 | 2         | 1.64%   |
| 2001-3000      | 1         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 64        | 50.79%  |
| 21-50     | 24        | 19.05%  |
| 51-100    | 14        | 11.11%  |
| 101-250   | 12        | 9.52%   |
| 251-500   | 6         | 4.76%   |
| 501-1000  | 5         | 3.97%   |
| 2001-3000 | 1         | 0.79%   |

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
| Detected | 78        | 112    | 60%     |
| Works    | 46        | 58     | 35.38%  |
| Malfunc  | 6         | 7      | 4.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 79        | 55.63%  |
| AMD                            | 23        | 16.2%   |
| SanDisk                        | 10        | 7.04%   |
| Samsung Electronics            | 10        | 7.04%   |
| SK hynix                       | 4         | 2.82%   |
| Micron Technology              | 3         | 2.11%   |
| Union Memory (Shenzhen)        | 2         | 1.41%   |
| Phison Electronics             | 2         | 1.41%   |
| Marvell Technology Group       | 2         | 1.41%   |
| KIOXIA                         | 2         | 1.41%   |
| Toshiba America Info Systems   | 1         | 0.7%    |
| Solid State Storage Technology | 1         | 0.7%    |
| Micron/Crucial Technology      | 1         | 0.7%    |
| Kingston Technology Company    | 1         | 0.7%    |
| Apple                          | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 13.33%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 6.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 6%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 4%      |
| SanDisk Non-Volatile memory controller                                         | 5         | 3.33%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 3.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 2.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 2.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2%      |
| Micron Non-Volatile memory controller                                          | 3         | 2%      |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2%      |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2%      |
| SK hynix Gold P31 SSD                                                          | 2         | 1.33%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.33%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.33%   |
| Intel SSD 660P Series                                                          | 2         | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.33%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.67%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 1         | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.67%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.67%   |
| SK hynix BC511                                                                 | 1         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.67%   |
| Samsung Electronics SATA controller                                            | 1         | 0.67%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.67%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.67%   |
| Intel SSD 600P Series                                                          | 1         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 84        | 57.53%  |
| NVMe | 37        | 25.34%  |
| RAID | 17        | 11.64%  |
| IDE  | 8         | 5.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 89        | 74.17%  |
| AMD    | 31        | 25.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 3.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 3.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 3.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 2.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.5%    |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 1.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.67%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.67%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.67%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.67%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 2         | 1.67%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.83%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.83%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.83%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.83%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.83%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.83%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.83%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.83%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.83%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.83%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz           | 1         | 0.83%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.83%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 0.83%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.83%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 0.83%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.83%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.83%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 17.5%   |
| Intel Core i7           | 15        | 12.5%   |
| Intel Core i3           | 12        | 10%     |
| Other                   | 11        | 9.17%   |
| Intel Core 2 Duo        | 7         | 5.83%   |
| Intel Atom              | 7         | 5.83%   |
| AMD Ryzen 7             | 7         | 5.83%   |
| AMD Ryzen 5             | 7         | 5.83%   |
| Intel Celeron           | 6         | 5%      |
| Intel Pentium           | 4         | 3.33%   |
| AMD Ryzen 3             | 3         | 2.5%    |
| Intel Celeron M         | 2         | 1.67%   |
| AMD E2                  | 2         | 1.67%   |
| AMD E1                  | 2         | 1.67%   |
| AMD A10                 | 2         | 1.67%   |
| Intel Pentium Silver    | 1         | 0.83%   |
| Intel Pentium M         | 1         | 0.83%   |
| Intel Pentium Dual-Core | 1         | 0.83%   |
| Intel Core i9           | 1         | 0.83%   |
| Intel Core 2 Extreme    | 1         | 0.83%   |
| AMD Ryzen 9             | 1         | 0.83%   |
| AMD C-50                | 1         | 0.83%   |
| AMD Athlon II           | 1         | 0.83%   |
| AMD Athlon              | 1         | 0.83%   |
| AMD A8                  | 1         | 0.83%   |
| AMD A6                  | 1         | 0.83%   |
| AMD A4                  | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 57.5%   |
| 4      | 30        | 25%     |
| 8      | 9         | 7.5%    |
| 6      | 7         | 5.83%   |
| 1      | 5         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 120       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 71.67%  |
| 1      | 34        | 28.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 116       | 96.67%  |
| 32-bit         | 4         | 3.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 9         | 7.38%   |
| 0x40651    | 7         | 5.74%   |
| 0x306a9    | 7         | 5.74%   |
| 0x806ec    | 6         | 4.92%   |
| 0x08608103 | 6         | 4.92%   |
| 0x08108109 | 6         | 4.92%   |
| 0x806e9    | 5         | 4.1%    |
| 0x406e3    | 5         | 4.1%    |
| Unknown    | 5         | 4.1%    |
| 0x30661    | 4         | 3.28%   |
| 0x6fd      | 3         | 2.46%   |
| 0x20652    | 3         | 2.46%   |
| 0x1067a    | 3         | 2.46%   |
| 0x10676    | 3         | 2.46%   |
| 0x0a50000c | 3         | 2.46%   |
| 0x906ea    | 2         | 1.64%   |
| 0x806ea    | 2         | 1.64%   |
| 0x706e5    | 2         | 1.64%   |
| 0x706a1    | 2         | 1.64%   |
| 0x406c4    | 2         | 1.64%   |
| 0x306c3    | 2         | 1.64%   |
| 0x206a7    | 2         | 1.64%   |
| 0x106e5    | 2         | 1.64%   |
| 0x06006705 | 2         | 1.64%   |
| 0x06001119 | 2         | 1.64%   |
| 0xa0652    | 1         | 0.82%   |
| 0x906ed    | 1         | 0.82%   |
| 0x806eb    | 1         | 0.82%   |
| 0x806d1    | 1         | 0.82%   |
| 0x706a8    | 1         | 0.82%   |
| 0x6f6      | 1         | 0.82%   |
| 0x6ec      | 1         | 0.82%   |
| 0x6d8      | 1         | 0.82%   |
| 0x506e3    | 1         | 0.82%   |
| 0x506c9    | 1         | 0.82%   |
| 0x306d4    | 1         | 0.82%   |
| 0x30678    | 1         | 0.82%   |
| 0x30673    | 1         | 0.82%   |
| 0x20655    | 1         | 0.82%   |
| 0x106ca    | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 14.05%  |
| Haswell       | 10        | 8.26%   |
| TigerLake     | 9         | 7.44%   |
| Unknown       | 8         | 6.61%   |
| Zen+          | 7         | 5.79%   |
| IvyBridge     | 7         | 5.79%   |
| Skylake       | 6         | 4.96%   |
| Penryn        | 6         | 4.96%   |
| Bonnell       | 6         | 4.96%   |
| Zen 3         | 4         | 3.31%   |
| Westmere      | 4         | 3.31%   |
| Silvermont    | 4         | 3.31%   |
| Excavator     | 4         | 3.31%   |
| Core          | 4         | 3.31%   |
| IceLake       | 3         | 2.48%   |
| Goldmont plus | 3         | 2.48%   |
| SandyBridge   | 2         | 1.65%   |
| Puma          | 2         | 1.65%   |
| Piledriver    | 2         | 1.65%   |
| P6            | 2         | 1.65%   |
| Nehalem       | 2         | 1.65%   |
| Jaguar        | 2         | 1.65%   |
| Broadwell     | 2         | 1.65%   |
| Zen 2         | 1         | 0.83%   |
| K10           | 1         | 0.83%   |
| Goldmont      | 1         | 0.83%   |
| CometLake     | 1         | 0.83%   |
| Bobcat        | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 54.55%  |
| AMD    | 36        | 25.17%  |
| Nvidia | 29        | 20.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 5.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 4.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 4.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.03%   |
| AMD Lucienne                                                                             | 6         | 4.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.36%   |
| Intel HD Graphics 620                                                                    | 4         | 2.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.68%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 2.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 2.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.01%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 2.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.34%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.34%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.34%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.34%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.34%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.34%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.34%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.34%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.67%   |
| Nvidia GT216M [GeForce GT 325M]                                                          | 1         | 0.67%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.67%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.67%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.67%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.67%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.67%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 47.5%   |
| 1 x AMD        | 28        | 23.33%  |
| Intel + Nvidia | 18        | 15%     |
| 1 x Nvidia     | 9         | 7.5%    |
| 2 x AMD        | 3         | 2.5%    |
| Intel + AMD    | 3         | 2.5%    |
| AMD + Nvidia   | 2         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 111       | 90.98%  |
| Proprietary | 7         | 5.74%   |
| Unknown     | 4         | 3.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 54.92%  |
| 0.01-0.5   | 26        | 21.31%  |
| 1.01-2.0   | 15        | 12.3%   |
| 0.51-1.0   | 6         | 4.92%   |
| 3.01-4.0   | 5         | 4.1%    |
| 5.01-6.0   | 2         | 1.64%   |
| 2.01-3.0   | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 23.58%  |
| LG Display              | 20        | 16.26%  |
| Chimei Innolux          | 17        | 13.82%  |
| BOE                     | 17        | 13.82%  |
| Samsung Electronics     | 7         | 5.69%   |
| LG Philips              | 4         | 3.25%   |
| InfoVision              | 4         | 3.25%   |
| Apple                   | 4         | 3.25%   |
| Goldstar                | 3         | 2.44%   |
| Chi Mei Optoelectronics | 3         | 2.44%   |
| Sharp                   | 2         | 1.63%   |
| PANDA                   | 2         | 1.63%   |
| HannStar                | 2         | 1.63%   |
| Dell                    | 2         | 1.63%   |
| Vestel Elektronik       | 1         | 0.81%   |
| TR_                     | 1         | 0.81%   |
| Quanta Display          | 1         | 0.81%   |
| Planar                  | 1         | 0.81%   |
| Lenovo                  | 1         | 0.81%   |
| Insignia                | 1         | 0.81%   |
| DENON                   | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 3         | 2.42%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch            | 2         | 1.61%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 2         | 1.61%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch           | 2         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch        | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch          | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 2         | 1.61%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.81%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                   | 1         | 0.81%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.81%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch   | 1         | 0.81%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 0.81%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch        | 1         | 0.81%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 0.81%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                | 1         | 0.81%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch            | 1         | 0.81%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 51        | 42.5%   |
| 1366x768 (WXGA)   | 34        | 28.33%  |
| 1600x900 (HD+)    | 7         | 5.83%   |
| 1920x1200 (WUXGA) | 6         | 5%      |
| 1440x900 (WXGA+)  | 4         | 3.33%   |
| 1280x800 (WXGA)   | 4         | 3.33%   |
| 1024x600          | 4         | 3.33%   |
| 3840x2160 (4K)    | 3         | 2.5%    |
| 2880x1800         | 1         | 0.83%   |
| 2560x1600         | 1         | 0.83%   |
| 2560x1440 (QHD)   | 1         | 0.83%   |
| 2256x1504         | 1         | 0.83%   |
| 1280x768          | 1         | 0.83%   |
| 1280x720 (HD)     | 1         | 0.83%   |
| 1280x1024 (SXGA)  | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 56        | 45.16%  |
| 13      | 20        | 16.13%  |
| 14      | 15        | 12.1%   |
| 17      | 11        | 8.87%   |
| 10      | 4         | 3.23%   |
| 27      | 3         | 2.42%   |
| 24      | 3         | 2.42%   |
| 21      | 2         | 1.61%   |
| Unknown | 2         | 1.61%   |
| 84      | 1         | 0.81%   |
| 72      | 1         | 0.81%   |
| 31      | 1         | 0.81%   |
| 23      | 1         | 0.81%   |
| 16      | 1         | 0.81%   |
| 12      | 1         | 0.81%   |
| 11      | 1         | 0.81%   |
| 8       | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 80        | 65.57%  |
| 201-300     | 16        | 13.11%  |
| 351-400     | 12        | 9.84%   |
| 501-600     | 6         | 4.92%   |
| 401-500     | 2         | 1.64%   |
| 1501-2000   | 2         | 1.64%   |
| Unknown     | 2         | 1.64%   |
| 601-700     | 1         | 0.82%   |
| 101-200     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 97        | 83.62%  |
| 16/10   | 15        | 12.93%  |
| Unknown | 2         | 1.72%   |
| 5/4     | 1         | 0.86%   |
| 3/2     | 1         | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 45.16%  |
| 81-90          | 26        | 20.97%  |
| 71-80          | 9         | 7.26%   |
| 121-130        | 7         | 5.65%   |
| 41-50          | 4         | 3.23%   |
| 201-250        | 4         | 3.23%   |
| 301-350        | 3         | 2.42%   |
| 131-140        | 3         | 2.42%   |
| More than 1000 | 2         | 1.61%   |
| 251-300        | 2         | 1.61%   |
| Unknown        | 2         | 1.61%   |
| 61-70          | 1         | 0.81%   |
| 51-60          | 1         | 0.81%   |
| 351-500        | 1         | 0.81%   |
| 1-40           | 1         | 0.81%   |
| 141-150        | 1         | 0.81%   |
| 91-100         | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 42.74%  |
| 101-120       | 45        | 36.29%  |
| 51-100        | 15        | 12.1%   |
| 161-240       | 7         | 5.65%   |
| Unknown       | 2         | 1.61%   |
| More than 240 | 1         | 0.81%   |
| 1-50          | 1         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 108       | 89.26%  |
| 2     | 8         | 6.61%   |
| 0     | 4         | 3.31%   |
| 3     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 38.33%  |
| Intel                    | 49        | 27.22%  |
| Qualcomm Atheros         | 29        | 16.11%  |
| Broadcom                 | 15        | 8.33%   |
| Marvell Technology Group | 3         | 1.67%   |
| Broadcom Limited         | 3         | 1.67%   |
| Ralink Technology        | 2         | 1.11%   |
| Xiaomi                   | 1         | 0.56%   |
| TP-Link                  | 1         | 0.56%   |
| Ralink                   | 1         | 0.56%   |
| OnePlus                  | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| JMicron Technology       | 1         | 0.56%   |
| Google                   | 1         | 0.56%   |
| Edimax Technology        | 1         | 0.56%   |
| Dell                     | 1         | 0.56%   |
| Davicom Semiconductor    | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 15.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 4.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.22%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.22%   |
| Intel Wireless 3165                                               | 5         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 2.22%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.78%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.33%   |
| Intel Wireless 7260                                               | 3         | 1.33%   |
| Intel WiFi Link 5100                                              | 3         | 1.33%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 1.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.89%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.89%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.89%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.89%   |
| Intel Wireless 8260                                               | 2         | 0.89%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.89%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.89%   |
| Broadcom BCM43225 802.11b/g/n                                     | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.44%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 37.1%   |
| Realtek Semiconductor | 34        | 27.42%  |
| Qualcomm Atheros      | 22        | 17.74%  |
| Broadcom              | 13        | 10.48%  |
| Broadcom Limited      | 3         | 2.42%   |
| Ralink Technology     | 2         | 1.61%   |
| TP-Link               | 1         | 0.81%   |
| Ralink                | 1         | 0.81%   |
| MediaTek              | 1         | 0.81%   |
| Edimax Technology     | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 8.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 4.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.91%   |
| Intel Wireless 8265 / 8275                                     | 5         | 3.91%   |
| Intel Wireless 3165                                            | 5         | 3.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 3.91%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 2.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.34%   |
| Intel Wireless 7260                                            | 3         | 2.34%   |
| Intel WiFi Link 5100                                           | 3         | 2.34%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.34%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 2.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.34%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 1.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.56%   |
| Intel Wireless 8260                                            | 2         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.56%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.78%   |
| Realtek RTL8187B Wireless Adapter                              | 1         | 0.78%   |
| Realtek Realtek Network controller                             | 1         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.78%   |
| Realtek 802.11ac NIC                                           | 1         | 0.78%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 54        | 56.84%  |
| Intel                    | 19        | 20%     |
| Qualcomm Atheros         | 12        | 12.63%  |
| Marvell Technology Group | 3         | 3.16%   |
| Broadcom                 | 2         | 2.11%   |
| Xiaomi                   | 1         | 1.05%   |
| OnePlus                  | 1         | 1.05%   |
| JMicron Technology       | 1         | 1.05%   |
| Google                   | 1         | 1.05%   |
| Davicom Semiconductor    | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 35.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 13.68%  |
| Intel 82567LM Gigabit Network Connection                          | 4         | 4.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.11%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 2.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.11%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 2.11%   |
| Intel Ethernet Connection I219-V                                  | 2         | 2.11%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.05%   |
| OnePlus OnePlus                                                   | 1         | 1.05%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.05%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.05%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.05%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.05%   |
| Davicom DM9621A USB To FastEther                                  | 1         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 55.66%  |
| Ethernet | 92        | 43.4%   |
| Modem    | 2         | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 77.24%  |
| Ethernet | 28        | 22.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 70.83%  |
| 1     | 31        | 25.83%  |
| 0     | 4         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 86        | 71.67%  |
| Yes  | 34        | 28.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 40.45%  |
| Realtek Semiconductor           | 22        | 24.72%  |
| Foxconn / Hon Hai               | 6         | 6.74%   |
| Qualcomm Atheros Communications | 4         | 4.49%   |
| Lite-On Technology              | 4         | 4.49%   |
| Hewlett-Packard                 | 3         | 3.37%   |
| Dell                            | 3         | 3.37%   |
| Broadcom                        | 3         | 3.37%   |
| Apple                           | 3         | 3.37%   |
| IMC Networks                    | 2         | 2.25%   |
| Foxconn International           | 2         | 2.25%   |
| Cambridge Silicon Radio         | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 17.98%  |
| Realtek Bluetooth Radio                             | 14        | 15.73%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 7.87%   |
| Intel AX201 Bluetooth                               | 7         | 7.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5.62%   |
| Intel AX200 Bluetooth                               | 4         | 4.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.25%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.25%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.25%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 2.25%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.12%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.12%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.12%   |
| Lite-On Bluetooth Device                            | 1         | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.12%   |
| Intel AX210 Bluetooth                               | 1         | 1.12%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.12%   |
| IMC Networks Bluetooth Device                       | 1         | 1.12%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.12%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.12%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 1.12%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.12%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.12%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.12%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.12%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.12%   |
| Apple Bluetooth Host Controller                     | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 60.84%  |
| AMD                   | 37        | 25.87%  |
| Nvidia                | 13        | 9.09%   |
| Texas Instruments     | 2         | 1.4%    |
| Yamaha                | 1         | 0.7%    |
| Realtek Semiconductor | 1         | 0.7%    |
| GN Netcom             | 1         | 0.7%    |
| Audioengine           | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 10.38%  |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 6.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 4.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 4.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 4.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 4.37%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 4.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 3.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.28%   |
| AMD FCH Azalia Controller                                                  | 6         | 3.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 2.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 2.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.64%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.64%   |
| AMD High Definition Audio Controller                                       | 3         | 1.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.09%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.09%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.09%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.55%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.55%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 0.55%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.55%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.55%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 17        | 30.36%  |
| SK hynix                     | 15        | 26.79%  |
| Unknown                      | 8         | 14.29%  |
| Micron Technology            | 3         | 5.36%   |
| Unknown (ABCD)               | 2         | 3.57%   |
| Nanya Technology             | 2         | 3.57%   |
| Kingston                     | 2         | 3.57%   |
| A-DATA Technology            | 2         | 3.57%   |
| Ramaxel Technology           | 1         | 1.79%   |
| Patriot Memory (PDP Systems) | 1         | 1.79%   |
| Crucial                      | 1         | 1.79%   |
| Corsair                      | 1         | 1.79%   |
| Unknown                      | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 3.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.45%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 1.72%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.72%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.72%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.72%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.72%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.72%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 56.86%  |
| DDR3   | 15        | 29.41%  |
| LPDDR4 | 3         | 5.88%   |
| SDRAM  | 2         | 3.92%   |
| DDR2   | 1         | 1.96%   |
| DDR    | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 96.15%  |
| Row Of Chips | 2         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 40%     |
| 4096  | 15        | 27.27%  |
| 2048  | 9         | 16.36%  |
| 16384 | 5         | 9.09%   |
| 32768 | 2         | 3.64%   |
| 1024  | 1         | 1.82%   |
| 512   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 15        | 28.3%   |
| 1600    | 12        | 22.64%  |
| 2667    | 9         | 16.98%  |
| 2400    | 6         | 11.32%  |
| Unknown | 2         | 3.77%   |
| 4267    | 1         | 1.89%   |
| 4199    | 1         | 1.89%   |
| 3266    | 1         | 1.89%   |
| 2267    | 1         | 1.89%   |
| 2048    | 1         | 1.89%   |
| 1334    | 1         | 1.89%   |
| 1333    | 1         | 1.89%   |
| 1200    | 1         | 1.89%   |
| 667     | 1         | 1.89%   |

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
| Chicony Electronics                    | 20        | 19.42%  |
| Microdia                               | 13        | 12.62%  |
| IMC Networks                           | 13        | 12.62%  |
| Acer                                   | 11        | 10.68%  |
| Suyin                                  | 9         | 8.74%   |
| Quanta                                 | 8         | 7.77%   |
| Sunplus Innovation Technology          | 6         | 5.83%   |
| Realtek Semiconductor                  | 6         | 5.83%   |
| Luxvisions Innotech Limited            | 3         | 2.91%   |
| Alcor Micro                            | 3         | 2.91%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.94%   |
| Z-Star Microelectronics                | 1         | 0.97%   |
| Syntek                                 | 1         | 0.97%   |
| Lite-On Technology                     | 1         | 0.97%   |
| Lenovo                                 | 1         | 0.97%   |
| Intel                                  | 1         | 0.97%   |
| Importek                               | 1         | 0.97%   |
| icSpring                               | 1         | 0.97%   |
| Apple                                  | 1         | 0.97%   |
| ALi                                    | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD              | 8         | 7.77%   |
| Chicony Integrated Camera                  | 6         | 5.83%   |
| Acer Integrated Camera                     | 5         | 4.85%   |
| Quanta HP TrueVision HD Camera             | 3         | 2.91%   |
| IMC Networks USB2.0 VGA UVC WebCam         | 3         | 2.91%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 2.91%   |
| Chicony HP TrueVision HD Camera            | 3         | 2.91%   |
| Chicony HD WebCam                          | 3         | 2.91%   |
| Suyin HP TrueVision HD                     | 2         | 1.94%   |
| Suyin HD Video WebCam                      | 2         | 1.94%   |
| Quanta HP Webcam                           | 2         | 1.94%   |
| IMC Networks Integrated Camera             | 2         | 1.94%   |
| Alcor Micro USB 2.0 WebCamera              | 2         | 1.94%   |
| Acer USB2.0 Camera                         | 2         | 1.94%   |
| Z-Star WebCam SC-03FFL11739P               | 1         | 0.97%   |
| Syntek Integrated Camera                   | 1         | 0.97%   |
| Suyin HP Webcam-101                        | 1         | 0.97%   |
| Suyin HD WebCam                            | 1         | 0.97%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 0.97%   |
| Suyin Acer CrystalEye Webcam               | 1         | 0.97%   |
| Suyin 1.3M HD WebCam                       | 1         | 0.97%   |
| Sunplus MTD Camera                         | 1         | 0.97%   |
| Sunplus Laptop Integrated Webcam FHD       | 1         | 0.97%   |
| Sunplus HP TrueVision HD Camera            | 1         | 0.97%   |
| Sunplus HD WebCam                          | 1         | 0.97%   |
| Sunplus Aukey-PC-LM1E Camera               | 1         | 0.97%   |
| Sunplus 1.3M HD WebCam                     | 1         | 0.97%   |
| Realtek MTD camera                         | 1         | 0.97%   |
| Realtek Lenovo EasyCamera                  | 1         | 0.97%   |
| Realtek Integrated_Webcam_HD               | 1         | 0.97%   |
| Realtek HP Truevision HD integrated webcam | 1         | 0.97%   |
| Realtek HP Truevision HD                   | 1         | 0.97%   |
| Realtek HP "Truevision HD" laptop camera   | 1         | 0.97%   |
| Quanta VGA WebCam                          | 1         | 0.97%   |
| Quanta Laptop_Integrated_Webcam_2HDM       | 1         | 0.97%   |
| Quanta HP HD Camera                        | 1         | 0.97%   |
| Microdia Lenovo EasyCamera                 | 1         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_HD       | 1         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_E4HD     | 1         | 0.97%   |
| Microdia Integrated Webcam HD              | 1         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 53.85%  |
| Synaptics                  | 1         | 7.69%   |
| STMicroelectronics         | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| Focal-systems.Corp         | 1         | 7.69%   |
| Elan Microelectronics      | 1         | 7.69%   |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 15.38%  |
| Validity Sensors Synaptics WBDI            | 2         | 15.38%  |
| Validity Sensors VFS491                    | 1         | 7.69%   |
| Validity Sensors VFS301 Fingerprint Reader | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 7.69%   |
| STMicroelectronics Fingerprint Reader      | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 7.69%   |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 7.69%   |
| Elan ELAN:Fingerprint                      | 1         | 7.69%   |
| AuthenTec AES1600                          | 1         | 7.69%   |
| Unknown                                    | 1         | 7.69%   |

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
| 0     | 82        | 66.67%  |
| 1     | 35        | 28.46%  |
| 2     | 4         | 3.25%   |
| 4     | 1         | 0.81%   |
| 3     | 1         | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 12        | 24.49%  |
| Multimedia controller | 12        | 24.49%  |
| Fingerprint reader    | 12        | 24.49%  |
| Graphics card         | 6         | 12.24%  |
| Chipcard              | 6         | 12.24%  |
| Dvb card              | 1         | 2.04%   |

