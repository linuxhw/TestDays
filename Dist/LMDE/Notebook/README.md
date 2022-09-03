LMDE - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for LMDE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 498

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| HP            | Notebook                    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| HP            | Laptop 14-cf3xxx            | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
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
| HP            | Laptop 14-cf3xxx            | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
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
| Acer          | AOD270                      | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
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
| ASUSTek       | 901                         | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| Acer          | TravelMate 420              | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Samsung       | NC210/NC110                 | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | 901                         | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| LG Electro... | A530-T.BE76P1               | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| Advent        | Monza T100                  | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| Sony          | VPCP116KG                   | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Samsung       | 305U1A                      | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Acer          | Aspire A315-55G             | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Apple         | MacBookPro5,4               | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| Qbex          | UDPAIOQBEX01                | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| IBM           | ThinkPad T41 23737JY        | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASUSTek       | M51Sn                       | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Dell          | XPS M1330                   | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| Samsung       | R59/R60/R61                 | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | Presario R4100 (EC375UA#... | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| ASUSTek       | X550LN                      | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| HP            | Pavilion dv6                | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| Acer          | Aspire E5-571               | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| HP            | 530                         | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| Dell          | Inspiron 7520               | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| HP            | Pavilion dv7                | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| Toshiba       | NI 1403                     | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| ASUSTek       | X101CH                      | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| LG Electro... | X300-L.CR31B1               | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Unknown                     | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| Toshiba       | Satellite L750              | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | K46CA                       | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| HP            | EliteBook 8540w             | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| HP            | Compaq Presario CQ71        | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Dell          | Inspiron 5559               | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Google        | Gnawty                      | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| Dell          | Latitude E6520              | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Notebook      | WID2010                     | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| HP            | EliteBook 820 G3            | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Matsushita... | CF-19CHB23BE                | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Dell          | Inspiron 7520               | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Exper         | E10IL1                      | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| Dell          | Precision M4800             | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| Dell          | Inspiron 1010               | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| Exo           | Unknown                     | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| Acer          | Extensa 4620                | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| HP            | EliteBook 8470p             | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| ASUSTek       | X551MA                      | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| ASUSTek       | GL503VM                     | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Unknown       | Unknown                     | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Positivo      | H14CU01                     | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | GL503VM                     | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| Lenovo        | V145-15AST 81MT             | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| MSI           | FX610                       | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Acer          | Aspire A315-41              | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Positivo      | W310CZ-T                    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | ProBook 430 G5              | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| Dell          | Inspiron 3442               | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| ASUSTek       | 1005PX                      | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Sony          | VGN-AW41MF_H                | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | EliteBook 8540w             | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Acer          | Aspire 4830T                | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| Dell          | Latitude E5570              | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| HP            | Laptop 15-bs2xx             | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| HP            | Laptop 15-bs2xx             | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [5c90c49af6](https://linux-hardware.org/?probe=5c90c49af6) | Mar 29, 2020 |
| Dell          | Inspiron 3543               | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |
| HP            | EliteBook 820 G3            | [b2c3317256](https://linux-hardware.org/?probe=b2c3317256) | Mar 19, 2020 |
| HP            | EliteBook 820 G3            | [2cd8614e59](https://linux-hardware.org/?probe=2cd8614e59) | Mar 17, 2020 |
| HP            | EliteBook 820 G3            | [fcb4ff46b5](https://linux-hardware.org/?probe=fcb4ff46b5) | Mar 17, 2020 |
| Lenovo        | Y50-70 20378                | [7dbce6b0fc](https://linux-hardware.org/?probe=7dbce6b0fc) | Jan 15, 2020 |
| Lenovo        | Y50-70 20378                | [11b0d93285](https://linux-hardware.org/?probe=11b0d93285) | Jan 15, 2020 |
| Dell          | Inspiron 3593               | [9f8af004d3](https://linux-hardware.org/?probe=9f8af004d3) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [7f4ce08df9](https://linux-hardware.org/?probe=7f4ce08df9) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [a6ee735c5f](https://linux-hardware.org/?probe=a6ee735c5f) | Nov 29, 2019 |
| Acer          | Aspire V3-571G              | [9be63e6a28](https://linux-hardware.org/?probe=9be63e6a28) | Jan 09, 2019 |
| HP            | Pavilion dv7                | [4480bf8ff3](https://linux-hardware.org/?probe=4480bf8ff3) | Dec 24, 2018 |
| Acer          | Aspire V3-571               | [bb8f83433e](https://linux-hardware.org/?probe=bb8f83433e) | Nov 27, 2018 |
| Acer          | Aspire V3-571               | [1136588271](https://linux-hardware.org/?probe=1136588271) | Nov 27, 2018 |
| HP            | ProBook 4510s               | [dbc607e890](https://linux-hardware.org/?probe=dbc607e890) | Sep 08, 2018 |
| Dell          | Inspiron 11-3162            | [92dcc778ac](https://linux-hardware.org/?probe=92dcc778ac) | Mar 19, 2018 |
| Sony          | VPCEB1M1R                   | [25b5c0689e](https://linux-hardware.org/?probe=25b5c0689e) | Mar 16, 2018 |
| Sony          | VPCSB3M1R                   | [155309a9eb](https://linux-hardware.org/?probe=155309a9eb) | Aug 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| LMDE 4 | 221       | 68.21%  |
| LMDE 5 | 94        | 29.01%  |
| LMDE 3 | 6         | 1.85%   |
| LMDE 2 | 3         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| LMDE | 323       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-8-amd64       | 27        | 7.61%   |
| 4.19.0-18-amd64      | 24        | 6.76%   |
| 5.10.0-14-amd64      | 20        | 5.63%   |
| 4.19.0-17-amd64      | 20        | 5.63%   |
| 5.10.0-12-amd64      | 19        | 5.35%   |
| 4.19.0-9-amd64       | 18        | 5.07%   |
| 5.10.0-15-amd64      | 16        | 4.51%   |
| 4.19.0-16-amd64      | 16        | 4.51%   |
| 5.10.0-13-amd64      | 14        | 3.94%   |
| 4.19.0-8-686         | 14        | 3.94%   |
| 4.19.0-17-686        | 14        | 3.94%   |
| 4.19.0-14-amd64      | 13        | 3.66%   |
| 4.19.0-13-amd64      | 12        | 3.38%   |
| 4.19.0-16-686        | 11        | 3.1%    |
| 4.19.0-10-amd64      | 11        | 3.1%    |
| 5.10.0-16-amd64      | 10        | 2.82%   |
| 4.19.0-18-686        | 10        | 2.82%   |
| 4.19.0-12-amd64      | 10        | 2.82%   |
| 4.19.0-13-686        | 7         | 1.97%   |
| 4.19.0-11-amd64      | 6         | 1.69%   |
| 5.10.0-13-686        | 5         | 1.41%   |
| 4.19.0-12-686        | 5         | 1.41%   |
| 5.18.0-0.bpo.1-amd64 | 4         | 1.13%   |
| 5.10.0-17-amd64      | 4         | 1.13%   |
| 4.9.0-8-amd64        | 4         | 1.13%   |
| 5.16.0-0.bpo.4-amd64 | 3         | 0.85%   |
| 4.19.0-19-686        | 3         | 0.85%   |
| 4.19.0-14-686        | 3         | 0.85%   |
| 5.4.0-0.bpo.4-amd64  | 2         | 0.56%   |
| 5.15.59-xanmod1      | 2         | 0.56%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.56%   |
| 3.16.0-4-amd64       | 2         | 0.56%   |
| 5.9.12-davius        | 1         | 0.28%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.28%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.28%   |
| 5.6.0-2-amd64        | 1         | 0.28%   |
| 5.6.0-2-686-pae      | 1         | 0.28%   |
| 5.4.44-xanmod1       | 1         | 0.28%   |
| 5.18.0-4-amd64       | 1         | 0.28%   |
| 5.18.0-3-amd64       | 1         | 0.28%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.28%   |
| 5.15.56-xanmod1      | 1         | 0.28%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.28%   |
| 5.10.0-14-686        | 1         | 0.28%   |
| 5.10.0-0.bpo.9-amd64 | 1         | 0.28%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.28%   |
| 4.9.0-14-amd64       | 1         | 0.28%   |
| 4.9.0-11-amd64       | 1         | 0.28%   |
| 4.19.0-9-686         | 1         | 0.28%   |
| 4.19.0-20-amd64      | 1         | 0.28%   |
| 4.19.0-20-686        | 1         | 0.28%   |
| 4.19.0-14-686-pae    | 1         | 0.28%   |
| 4.19.0-12-rt-amd64   | 1         | 0.28%   |
| 4.19.0-10-686        | 1         | 0.28%   |
| 4.19.0-0.bpo.8-amd64 | 1         | 0.28%   |
| 3.16.0-5-amd64       | 1         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 210       | 64.02%  |
| 5.10.0  | 89        | 27.13%  |
| 5.18.0  | 6         | 1.83%   |
| 4.9.0   | 5         | 1.52%   |
| 5.16.0  | 3         | 0.91%   |
| 3.16.0  | 3         | 0.91%   |
| 5.6.0   | 2         | 0.61%   |
| 5.4.0   | 2         | 0.61%   |
| 5.15.59 | 2         | 0.61%   |
| 5.9.12  | 1         | 0.3%    |
| 5.9.0   | 1         | 0.3%    |
| 5.8.0   | 1         | 0.3%    |
| 5.4.44  | 1         | 0.3%    |
| 5.15.56 | 1         | 0.3%    |
| 5.15.0  | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 210       | 64.22%  |
| 5.10    | 89        | 27.22%  |
| 5.18    | 6         | 1.83%   |
| 4.9     | 5         | 1.53%   |
| 5.4     | 3         | 0.92%   |
| 5.16    | 3         | 0.92%   |
| 5.15    | 3         | 0.92%   |
| 3.16    | 3         | 0.92%   |
| 5.9     | 2         | 0.61%   |
| 5.6     | 2         | 0.61%   |
| 5.8     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 249       | 77.09%  |
| i686   | 74        | 22.91%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 290       | 88.41%  |
| Cinnamon   | 21        | 6.4%    |
| MATE       | 7         | 2.13%   |
| Unknown    | 6         | 1.83%   |
| XFCE       | 1         | 0.3%    |
| Trinity    | 1         | 0.3%    |
| LXDE       | 1         | 0.3%    |
| KDE        | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 323       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 252       | 77.54%  |
| LightDM | 55        | 16.92%  |
| TDM     | 15        | 4.62%   |
| MDM     | 3         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 101       | 30.98%  |
| de_DE   | 33        | 10.12%  |
| pt_BR   | 29        | 8.9%    |
| ru_RU   | 21        | 6.44%   |
| en_GB   | 15        | 4.6%    |
| pl_PL   | 11        | 3.37%   |
| es_ES   | 11        | 3.37%   |
| fr_FR   | 10        | 3.07%   |
| it_IT   | 8         | 2.45%   |
| es_MX   | 8         | 2.45%   |
| Unknown | 8         | 2.45%   |
| es_AR   | 6         | 1.84%   |
| en_AU   | 6         | 1.84%   |
| en_CA   | 5         | 1.53%   |
| de_CH   | 5         | 1.53%   |
| nl_NL   | 3         | 0.92%   |
| ja_JP   | 3         | 0.92%   |
| el_GR   | 3         | 0.92%   |
| pt_PT   | 2         | 0.61%   |
| fr_BE   | 2         | 0.61%   |
| es_BO   | 2         | 0.61%   |
| en_ZA   | 2         | 0.61%   |
| en_PH   | 2         | 0.61%   |
| en_IN   | 2         | 0.61%   |
| en_IE   | 2         | 0.61%   |
| de_AT   | 2         | 0.61%   |
| bg_BG   | 2         | 0.61%   |
| zh_CN   | 1         | 0.31%   |
| unm_US  | 1         | 0.31%   |
| uk_UA   | 1         | 0.31%   |
| tr_TR   | 1         | 0.31%   |
| sk_SK   | 1         | 0.31%   |
| ru_UA   | 1         | 0.31%   |
| nn_NO   | 1         | 0.31%   |
| nl_BE   | 1         | 0.31%   |
| nl_AW   | 1         | 0.31%   |
| ko_KR   | 1         | 0.31%   |
| it_CH   | 1         | 0.31%   |
| hu_HU   | 1         | 0.31%   |
| hr_HR   | 1         | 0.31%   |
| et_EE   | 1         | 0.31%   |
| es_PE   | 1         | 0.31%   |
| es_EC   | 1         | 0.31%   |
| es_CR   | 1         | 0.31%   |
| es_CL   | 1         | 0.31%   |
| en_SG   | 1         | 0.31%   |
| en_NZ   | 1         | 0.31%   |
| da_DK   | 1         | 0.31%   |
| ca_ES   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 196       | 60.31%  |
| EFI  | 129       | 39.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 304       | 94.12%  |
| Overlay | 6         | 1.86%   |
| Btrfs   | 5         | 1.55%   |
| Tmpfs   | 3         | 0.93%   |
| Unknown | 3         | 0.93%   |
| Xfs     | 1         | 0.31%   |
| Aufs    | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 248       | 76.78%  |
| GPT     | 52        | 16.1%   |
| MBR     | 23        | 7.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 305       | 94.14%  |
| Yes       | 19        | 5.86%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 302       | 93.5%   |
| Yes       | 21        | 6.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 74        | 22.91%  |
| Dell                           | 47        | 14.55%  |
| Lenovo                         | 42        | 13%     |
| Acer                           | 40        | 12.38%  |
| ASUSTek Computer               | 32        | 9.91%   |
| Toshiba                        | 11        | 3.41%   |
| Sony                           | 9         | 2.79%   |
| Samsung Electronics            | 7         | 2.17%   |
| Apple                          | 6         | 1.86%   |
| Fujitsu Siemens                | 5         | 1.55%   |
| MSI                            | 4         | 1.24%   |
| LG Electronics                 | 4         | 1.24%   |
| Positivo                       | 3         | 0.93%   |
| Packard Bell                   | 3         | 0.93%   |
| Unknown                        | 3         | 0.93%   |
| Medion                         | 2         | 0.62%   |
| Matsushita Electric Industrial | 2         | 0.62%   |
| Google                         | 2         | 0.62%   |
| Gateway                        | 2         | 0.62%   |
| Fujitsu                        | 2         | 0.62%   |
| Wortmann AG                    | 1         | 0.31%   |
| TUXEDO                         | 1         | 0.31%   |
| Semp Toshiba                   | 1         | 0.31%   |
| SAELITE                        | 1         | 0.31%   |
| Qbex                           | 1         | 0.31%   |
| Philco                         | 1         | 0.31%   |
| Notebook                       | 1         | 0.31%   |
| Multilaser                     | 1         | 0.31%   |
| Microtech                      | 1         | 0.31%   |
| Maibenben                      | 1         | 0.31%   |
| LincPlus                       | 1         | 0.31%   |
| Itautec                        | 1         | 0.31%   |
| IBM                            | 1         | 0.31%   |
| Howard Computers               | 1         | 0.31%   |
| Framework                      | 1         | 0.31%   |
| Exper                          | 1         | 0.31%   |
| Exo                            | 1         | 0.31%   |
| EVOO                           | 1         | 0.31%   |
| Dynabook                       | 1         | 0.31%   |
| Dixonsxp                       | 1         | 0.31%   |
| AMI                            | 1         | 0.31%   |
| Alienware                      | 1         | 0.31%   |
| Advent                         | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 2.48%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.93%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 3         | 0.93%   |
| HP Notebook                                 | 3         | 0.93%   |
| Dell Latitude E6400                         | 3         | 0.93%   |
| Acer AOD270                                 | 3         | 0.93%   |
| HP Pavilion dv7                             | 2         | 0.62%   |
| HP Pavilion dv6                             | 2         | 0.62%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.62%   |
| HP Laptop 15-bw0xx                          | 2         | 0.62%   |
| HP Laptop 14-df0xxx                         | 2         | 0.62%   |
| HP EliteBook 8540w                          | 2         | 0.62%   |
| HP Compaq Presario CQ71                     | 2         | 0.62%   |
| HP 255 G7 Notebook PC                       | 2         | 0.62%   |
| HP 14                                       | 2         | 0.62%   |
| Dell Latitude E5540                         | 2         | 0.62%   |
| Dell Inspiron 5566                          | 2         | 0.62%   |
| Dell Inspiron 5559                          | 2         | 0.62%   |
| ASUS X101CH                                 | 2         | 0.62%   |
| Acer Aspire 5930                            | 2         | 0.62%   |
| Acer Aspire 5735                            | 2         | 0.62%   |
| Acer Aspire 3820                            | 2         | 0.62%   |
| Acer Aspire 3000                            | 2         | 0.62%   |
| Wortmann AG TERRA_MOBILE_1713A              | 1         | 0.31%   |
| TUXEDO BC1510 1710                          | 1         | 0.31%   |
| Toshiba Satellite U300                      | 1         | 0.31%   |
| Toshiba Satellite P300                      | 1         | 0.31%   |
| Toshiba Satellite M55                       | 1         | 0.31%   |
| Toshiba Satellite M100                      | 1         | 0.31%   |
| Toshiba Satellite L855                      | 1         | 0.31%   |
| Toshiba Satellite L750                      | 1         | 0.31%   |
| Toshiba Satellite L50-C                     | 1         | 0.31%   |
| Toshiba Satellite L455                      | 1         | 0.31%   |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.31%   |
| Toshiba Satellite A200                      | 1         | 0.31%   |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.31%   |
| Sony VPCSB3M1R                              | 1         | 0.31%   |
| Sony VPCS131FM                              | 1         | 0.31%   |
| Sony VPCP116KG                              | 1         | 0.31%   |
| Sony VPCEB1M1R                              | 1         | 0.31%   |
| Sony VGN-FZ140E                             | 1         | 0.31%   |
| Sony VGN-AW41MF_H                           | 1         | 0.31%   |
| Sony SVE1713Y1RB                            | 1         | 0.31%   |
| Sony SVE1512G1RW                            | 1         | 0.31%   |
| Sony SVE1511N1ESI                           | 1         | 0.31%   |
| Semp Toshiba NI 1403                        | 1         | 0.31%   |
| Samsung RV413/RV513                         | 1         | 0.31%   |
| Samsung R59/R60/R61                         | 1         | 0.31%   |
| Samsung NC10                                | 1         | 0.31%   |
| Samsung 305U1A                              | 1         | 0.31%   |
| SAELITE ES1AU11                             | 1         | 0.31%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.31%   |
| Positivo W310CZ-T                           | 1         | 0.31%   |
| Positivo Mobile                             | 1         | 0.31%   |
| Positivo H14CU01                            | 1         | 0.31%   |
| Philco 10D                                  | 1         | 0.31%   |
| Packard Bell EasyNote_NJ66                  | 1         | 0.31%   |
| Packard Bell EasyNote TE69BM                | 1         | 0.31%   |
| Packard Bell DOT S                          | 1         | 0.31%   |
| Notebook WID2010                            | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 32        | 9.91%   |
| Lenovo ThinkPad         | 20        | 6.19%   |
| Dell Latitude           | 19        | 5.88%   |
| Dell Inspiron           | 16        | 4.95%   |
| HP Laptop               | 15        | 4.64%   |
| HP Pavilion             | 13        | 4.02%   |
| Lenovo IdeaPad          | 12        | 3.72%   |
| Toshiba Satellite       | 10        | 3.1%    |
| HP EliteBook            | 8         | 2.48%   |
| HP Compaq               | 8         | 2.48%   |
| Unknown                 | 8         | 2.48%   |
| HP ProBook              | 5         | 1.55%   |
| Dell Precision          | 5         | 1.55%   |
| ASUS VivoBook           | 4         | 1.24%   |
| Samsung RV411           | 3         | 0.93%   |
| HP Presario             | 3         | 0.93%   |
| HP Notebook             | 3         | 0.93%   |
| HP 255                  | 3         | 0.93%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.93%   |
| Acer AOD270             | 3         | 0.93%   |
| Packard Bell EasyNote   | 2         | 0.62%   |
| HP ENVY                 | 2         | 0.62%   |
| HP 14                   | 2         | 0.62%   |
| Dell XPS                | 2         | 0.62%   |
| Dell Vostro             | 2         | 0.62%   |
| Dell System             | 2         | 0.62%   |
| ASUS X101CH             | 2         | 0.62%   |
| Apple MacBookPro5       | 2         | 0.62%   |
| Acer Swift              | 2         | 0.62%   |
| Wortmann AG TERRA       | 1         | 0.31%   |
| TUXEDO BC1510           | 1         | 0.31%   |
| Toshiba dynabook        | 1         | 0.31%   |
| Sony VPCSB3M1R          | 1         | 0.31%   |
| Sony VPCS131FM          | 1         | 0.31%   |
| Sony VPCP116KG          | 1         | 0.31%   |
| Sony VPCEB1M1R          | 1         | 0.31%   |
| Sony VGN-FZ140E         | 1         | 0.31%   |
| Sony VGN-AW41MF         | 1         | 0.31%   |
| Sony SVE1713Y1RB        | 1         | 0.31%   |
| Sony SVE1512G1RW        | 1         | 0.31%   |
| Sony SVE1511N1ESI       | 1         | 0.31%   |
| Semp Toshiba NI         | 1         | 0.31%   |
| Samsung RV413           | 1         | 0.31%   |
| Samsung R59             | 1         | 0.31%   |
| Samsung NC10            | 1         | 0.31%   |
| Samsung 305U1A          | 1         | 0.31%   |
| SAELITE ES1AU11         | 1         | 0.31%   |
| Qbex UDPAIOQBEX01       | 1         | 0.31%   |
| Positivo W310CZ-T       | 1         | 0.31%   |
| Positivo Mobile         | 1         | 0.31%   |
| Positivo H14CU01        | 1         | 0.31%   |
| Philco 10D              | 1         | 0.31%   |
| Packard Bell DOT        | 1         | 0.31%   |
| Notebook WID2010        | 1         | 0.31%   |
| Multilaser PC150        | 1         | 0.31%   |
| MSI U180                | 1         | 0.31%   |
| MSI GT70                | 1         | 0.31%   |
| MSI GL73                | 1         | 0.31%   |
| MSI FX610               | 1         | 0.31%   |
| Microtech ebookPro      | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 29        | 8.98%   |
| 2009    | 27        | 8.36%   |
| 2011    | 26        | 8.05%   |
| 2010    | 25        | 7.74%   |
| 2013    | 23        | 7.12%   |
| 2007    | 22        | 6.81%   |
| 2008    | 21        | 6.5%    |
| 2018    | 20        | 6.19%   |
| 2014    | 18        | 5.57%   |
| 2021    | 17        | 5.26%   |
| 2019    | 16        | 4.95%   |
| 2020    | 15        | 4.64%   |
| 2016    | 15        | 4.64%   |
| 2017    | 13        | 4.02%   |
| 2015    | 13        | 4.02%   |
| 2006    | 11        | 3.41%   |
| 2005    | 7         | 2.17%   |
| 2022    | 1         | 0.31%   |
| 2004    | 1         | 0.31%   |
| 2003    | 1         | 0.31%   |
| 2002    | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 323       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 301       | 92.62%  |
| Enabled  | 24        | 7.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 321       | 99.38%  |
| Yes  | 2         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 98        | 30.25%  |
| 4.01-8.0    | 66        | 20.37%  |
| 2.01-3.0    | 42        | 12.96%  |
| 16.01-24.0  | 36        | 11.11%  |
| 1.01-2.0    | 36        | 11.11%  |
| 8.01-16.0   | 29        | 8.95%   |
| 0.51-1.0    | 9         | 2.78%   |
| 32.01-64.0  | 5         | 1.54%   |
| 64.01-256.0 | 2         | 0.62%   |
| 24.01-32.0  | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 168       | 48.7%   |
| 2.01-3.0   | 69        | 20%     |
| 0.51-1.0   | 62        | 17.97%  |
| 3.01-4.0   | 26        | 7.54%   |
| 4.01-8.0   | 12        | 3.48%   |
| 8.01-16.0  | 4         | 1.16%   |
| 0.01-0.5   | 3         | 0.87%   |
| 32.01-64.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 240       | 72.73%  |
| 2      | 72        | 21.82%  |
| 3      | 9         | 2.73%   |
| 0      | 4         | 1.21%   |
| 4      | 3         | 0.91%   |
| 6      | 1         | 0.3%    |
| 5      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 51.69%  |
| No        | 157       | 48.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 88.54%  |
| No        | 37        | 11.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 317       | 98.14%  |
| No        | 6         | 1.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 59.75%  |
| No        | 130       | 40.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 42        | 12.92%  |
| Germany             | 36        | 11.08%  |
| Brazil              | 31        | 9.54%   |
| Russia              | 24        | 7.38%   |
| UK                  | 17        | 5.23%   |
| Poland              | 13        | 4%      |
| France              | 12        | 3.69%   |
| Spain               | 10        | 3.08%   |
| Italy               | 10        | 3.08%   |
| Mexico              | 9         | 2.77%   |
| Canada              | 8         | 2.46%   |
| Australia           | 7         | 2.15%   |
| Ukraine             | 6         | 1.85%   |
| Switzerland         | 6         | 1.85%   |
| Netherlands         | 6         | 1.85%   |
| Bulgaria            | 6         | 1.85%   |
| Argentina           | 6         | 1.85%   |
| Austria             | 4         | 1.23%   |
| Turkey              | 3         | 0.92%   |
| Romania             | 3         | 0.92%   |
| Portugal            | 3         | 0.92%   |
| Philippines         | 3         | 0.92%   |
| Indonesia           | 3         | 0.92%   |
| India               | 3         | 0.92%   |
| Greece              | 3         | 0.92%   |
| Chile               | 3         | 0.92%   |
| Belgium             | 3         | 0.92%   |
| Belarus             | 3         | 0.92%   |
| Bahrain             | 3         | 0.92%   |
| Tunisia             | 2         | 0.62%   |
| South Africa        | 2         | 0.62%   |
| Japan               | 2         | 0.62%   |
| Ireland             | 2         | 0.62%   |
| Hungary             | 2         | 0.62%   |
| Ecuador             | 2         | 0.62%   |
| China               | 2         | 0.62%   |
| Bolivia             | 2         | 0.62%   |
| Vietnam             | 1         | 0.31%   |
| Venezuela           | 1         | 0.31%   |
| Trinidad and Tobago | 1         | 0.31%   |
| Sweden              | 1         | 0.31%   |
| South Korea         | 1         | 0.31%   |
| Singapore           | 1         | 0.31%   |
| Peru                | 1         | 0.31%   |
| Paraguay            | 1         | 0.31%   |
| Norway              | 1         | 0.31%   |
| New Zealand         | 1         | 0.31%   |
| Myanmar             | 1         | 0.31%   |
| Malaysia            | 1         | 0.31%   |
| Luxembourg          | 1         | 0.31%   |
| Lithuania           | 1         | 0.31%   |
| Kenya               | 1         | 0.31%   |
| Honduras            | 1         | 0.31%   |
| Estonia             | 1         | 0.31%   |
| Egypt               | 1         | 0.31%   |
| Dominican Republic  | 1         | 0.31%   |
| Denmark             | 1         | 0.31%   |
| Croatia             | 1         | 0.31%   |
| Costa Rica          | 1         | 0.31%   |
| Bangladesh          | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 6         | 1.8%    |
| Moscow            | 5         | 1.5%    |
| Wroclaw           | 3         | 0.9%    |
| Wohlen            | 3         | 0.9%    |
| St Petersburg     | 3         | 0.9%    |
| Seville           | 3         | 0.9%    |
| Poznan            | 3         | 0.9%    |
| Manama            | 3         | 0.9%    |
| Zurich            | 2         | 0.6%    |
| Voronezh          | 2         | 0.6%    |
| Stuttgart         | 2         | 0.6%    |
| Sofia             | 2         | 0.6%    |
| Recife            | 2         | 0.6%    |
| Perth             | 2         | 0.6%    |
| Oruro             | 2         | 0.6%    |
| Nuremberg         | 2         | 0.6%    |
| Neasden           | 2         | 0.6%    |
| Minsk             | 2         | 0.6%    |
| Mexico City       | 2         | 0.6%    |
| Mannheim          | 2         | 0.6%    |
| London            | 2         | 0.6%    |
| Lisbon            | 2         | 0.6%    |
| Krakow            | 2         | 0.6%    |
| Glasgow           | 2         | 0.6%    |
| Frankfurt am Main | 2         | 0.6%    |
| Foz do Iguaçu    | 2         | 0.6%    |
| Denver            | 2         | 0.6%    |
| Cologne           | 2         | 0.6%    |
| Chelyabinsk       | 2         | 0.6%    |
| Caroline          | 2         | 0.6%    |
| Bursa             | 2         | 0.6%    |
| Berlin            | 2         | 0.6%    |
| Athens            | 2         | 0.6%    |
| Zoetermeer        | 1         | 0.3%    |
| Zhongshan         | 1         | 0.3%    |
| Zaragoza          | 1         | 0.3%    |
| Zapopan           | 1         | 0.3%    |
| Zagreb            | 1         | 0.3%    |
| Zabrze            | 1         | 0.3%    |
| Yuzhno-Sakhalinsk | 1         | 0.3%    |
| Yokohama          | 1         | 0.3%    |
| Yevpatoriya       | 1         | 0.3%    |
| Yan’an          | 1         | 0.3%    |
| Wittichenau       | 1         | 0.3%    |
| Wilberforce       | 1         | 0.3%    |
| Whittier          | 1         | 0.3%    |
| Wellington        | 1         | 0.3%    |
| Voluntari         | 1         | 0.3%    |
| Vitebsk           | 1         | 0.3%    |
| Vilshofen         | 1         | 0.3%    |
| Vilnius           | 1         | 0.3%    |
| Vila Matias       | 1         | 0.3%    |
| Viet Tri          | 1         | 0.3%    |
| Vicosa            | 1         | 0.3%    |
| Veurne            | 1         | 0.3%    |
| Verona            | 1         | 0.3%    |
| Veghel            | 1         | 0.3%    |
| Vaslui            | 1         | 0.3%    |
| Valsoyfjord       | 1         | 0.3%    |
| Uttoxeter         | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 62        | 70     | 15.62%  |
| Samsung Electronics            | 50        | 55     | 12.59%  |
| Seagate                        | 47        | 60     | 11.84%  |
| Toshiba                        | 27        | 29     | 6.8%    |
| Hitachi                        | 25        | 25     | 6.3%    |
| Unknown                        | 24        | 29     | 6.05%   |
| SanDisk                        | 17        | 21     | 4.28%   |
| Kingston                       | 16        | 18     | 4.03%   |
| HGST                           | 12        | 13     | 3.02%   |
| Intel                          | 11        | 11     | 2.77%   |
| Fujitsu                        | 8         | 8      | 2.02%   |
| Crucial                        | 8         | 9      | 2.02%   |
| SK hynix                       | 6         | 8      | 1.51%   |
| Patriot                        | 5         | 6      | 1.26%   |
| Micron Technology              | 5         | 6      | 1.26%   |
| China                          | 5         | 6      | 1.26%   |
| PNY                            | 4         | 4      | 1.01%   |
| Phison                         | 4         | 5      | 1.01%   |
| KingSpec                       | 4         | 4      | 1.01%   |
| Apple                          | 4         | 9      | 1.01%   |
| Transcend                      | 3         | 4      | 0.76%   |
| KingDian                       | 3         | 4      | 0.76%   |
| GOODRAM                        | 3         | 3      | 0.76%   |
| A-DATA Technology              | 3         | 4      | 0.76%   |
| Team                           | 2         | 2      | 0.5%    |
| JMicron Technology             | 2         | 3      | 0.5%    |
| Intenso                        | 2         | 2      | 0.5%    |
| IBM/Hitachi                    | 2         | 2      | 0.5%    |
| Gigabyte Technology            | 2         | 3      | 0.5%    |
| FORESEE                        | 2         | 2      | 0.5%    |
| USB30                          | 1         | 2      | 0.25%   |
| SSD PHIS                       | 1         | 1      | 0.25%   |
| Solid State Storage Technology | 1         | 1      | 0.25%   |
| ShiJi                          | 1         | 1      | 0.25%   |
| SABRENT                        | 1         | 1      | 0.25%   |
| Plextor                        | 1         | 1      | 0.25%   |
| Oyen                           | 1         | 1      | 0.25%   |
| ORICO                          | 1         | 1      | 0.25%   |
| Netac                          | 1         | 1      | 0.25%   |
| Mushkin                        | 1         | 1      | 0.25%   |
| Microtech                      | 1         | 2      | 0.25%   |
| Micron/Crucial Technology      | 1         | 2      | 0.25%   |
| LITEON                         | 1         | 1      | 0.25%   |
| KIOXIA                         | 1         | 4      | 0.25%   |
| Initio                         | 1         | 1      | 0.25%   |
| HXY                            | 1         | 1      | 0.25%   |
| HUAWEI                         | 1         | 1      | 0.25%   |
| Hikvision                      | 1         | 1      | 0.25%   |
| Hewlett-Packard                | 1         | 2      | 0.25%   |
| GALAX                          | 1         | 1      | 0.25%   |
| Drevo                          | 1         | 2      | 0.25%   |
| DAS                            | 1         | 4      | 0.25%   |
| Corsair                        | 1         | 1      | 0.25%   |
| BIWIN                          | 1         | 1      | 0.25%   |
| BHT                            | 1         | 2      | 0.25%   |
| BAITITON                       | 1         | 1      | 0.25%   |
| ASUS-PHISON                    | 1         | 2      | 0.25%   |
| Acer                           | 1         | 1      | 0.25%   |
| Unknown                        | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB      | 6         | 1.48%   |
| Samsung SSD 860 EVO 500GB            | 6         | 1.48%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 5         | 1.23%   |
| Toshiba MQ01ABD100 1TB               | 5         | 1.23%   |
| SanDisk NVMe SSD Drive 256GB         | 5         | 1.23%   |
| Samsung SSD 860 EVO 1TB              | 5         | 1.23%   |
| Unknown SD/MMC/MS PRO 128GB          | 4         | 0.99%   |
| Unknown MMC Card  7GB                | 4         | 0.99%   |
| Unknown MMC Card  32GB               | 4         | 0.99%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.99%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 0.99%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 0.74%   |
| Seagate ST9500325AS 500GB            | 3         | 0.74%   |
| Seagate ST9250315AS 250GB            | 3         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.74%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.74%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.74%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.74%   |
| WDC WDBNCE5000PNC 500GB SSD          | 2         | 0.49%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 2         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.49%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 0.49%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 2         | 0.49%   |
| WDC WD1200BEVS-22UST0 120GB          | 2         | 0.49%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.49%   |
| WDC PC SN530 NVMe 256GB              | 2         | 0.49%   |
| Unknown MMC Card  64GB               | 2         | 0.49%   |
| Unknown MMC Card  4GB                | 2         | 0.49%   |
| Unknown MMC Card  16GB               | 2         | 0.49%   |
| Toshiba MQ01ABD032 320GB             | 2         | 0.49%   |
| Seagate ST9320423AS 320GB            | 2         | 0.49%   |
| Seagate ST9120821AS 120GB            | 2         | 0.49%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.49%   |
| Seagate Expansion 500GB              | 2         | 0.49%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.49%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.49%   |
| Samsung SSD 850 EVO mSATA 250GB      | 2         | 0.49%   |
| Samsung PM991a NVMe 512GB            | 2         | 0.49%   |
| Phison NVMe SSD Drive 256GB          | 2         | 0.49%   |
| Patriot Burst 240GB SSD              | 2         | 0.49%   |
| Micron NVMe SSD Drive 512GB          | 2         | 0.49%   |
| KingSpec MT-128 128GB                | 2         | 0.49%   |
| KingDian S280 120GB SSD              | 2         | 0.49%   |
| JMicron Tech 250GB                   | 2         | 0.49%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 0.49%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 0.49%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.49%   |
| Hitachi HTS543216L9A300 160GB        | 2         | 0.49%   |
| Hitachi HTS541680J9SA00 80GB         | 2         | 0.49%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.49%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.49%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.49%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.49%   |
| GOODRAM SSDPR-CL100-120-G3 120GB     | 2         | 0.49%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 2         | 0.49%   |
| Fujitsu MHV2080BH 80GB               | 2         | 0.49%   |
| China SATA SSD 120GB                 | 2         | 0.49%   |
| Apple SSD SD0128F 121GB              | 2         | 0.49%   |
| A-DATA ED600 1TB SSD                 | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 58     | 28.81%  |
| Seagate             | 46        | 58     | 25.99%  |
| Hitachi             | 25        | 25     | 14.12%  |
| Toshiba             | 23        | 25     | 12.99%  |
| HGST                | 12        | 13     | 6.78%   |
| Fujitsu             | 8         | 8      | 4.52%   |
| Unknown             | 4         | 4      | 2.26%   |
| Samsung Electronics | 4         | 4      | 2.26%   |
| IBM/Hitachi         | 2         | 2      | 1.13%   |
| SABRENT             | 1         | 1      | 0.56%   |
| DAS                 | 1         | 4      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 42     | 25.34%  |
| Kingston            | 14        | 16     | 9.59%   |
| SanDisk             | 8         | 12     | 5.48%   |
| Crucial             | 8         | 9      | 5.48%   |
| Intel               | 7         | 7      | 4.79%   |
| WDC                 | 5         | 5      | 3.42%   |
| Patriot             | 5         | 6      | 3.42%   |
| PNY                 | 4         | 4      | 2.74%   |
| China               | 4         | 5      | 2.74%   |
| Transcend           | 3         | 4      | 2.05%   |
| Toshiba             | 3         | 3      | 2.05%   |
| Micron Technology   | 3         | 4      | 2.05%   |
| KingSpec            | 3         | 3      | 2.05%   |
| KingDian            | 3         | 4      | 2.05%   |
| GOODRAM             | 3         | 3      | 2.05%   |
| Apple               | 3         | 3      | 2.05%   |
| A-DATA Technology   | 3         | 4      | 2.05%   |
| Team                | 2         | 2      | 1.37%   |
| SK hynix            | 2         | 3      | 1.37%   |
| Gigabyte Technology | 2         | 3      | 1.37%   |
| FORESEE             | 2         | 2      | 1.37%   |
| USB30               | 1         | 2      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |
| SSD PHIS            | 1         | 1      | 0.68%   |
| Plextor             | 1         | 1      | 0.68%   |
| ORICO               | 1         | 1      | 0.68%   |
| Netac               | 1         | 1      | 0.68%   |
| Mushkin             | 1         | 1      | 0.68%   |
| Microtech           | 1         | 2      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| Intenso             | 1         | 1      | 0.68%   |
| HXY                 | 1         | 1      | 0.68%   |
| Hikvision           | 1         | 1      | 0.68%   |
| Hewlett-Packard     | 1         | 2      | 0.68%   |
| GALAX               | 1         | 1      | 0.68%   |
| Drevo               | 1         | 2      | 0.68%   |
| Corsair             | 1         | 1      | 0.68%   |
| BIWIN               | 1         | 1      | 0.68%   |
| BHT                 | 1         | 2      | 0.68%   |
| BAITITON            | 1         | 1      | 0.68%   |
| ASUS-PHISON         | 1         | 2      | 0.68%   |
| Acer                | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 169       | 202    | 45.55%  |
| SSD     | 131       | 172    | 35.31%  |
| NVMe    | 41        | 56     | 11.05%  |
| MMC     | 19        | 23     | 5.12%   |
| Unknown | 11        | 14     | 2.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 279       | 353    | 77.07%  |
| NVMe | 41        | 56     | 11.33%  |
| SAS  | 23        | 35     | 6.35%   |
| MMC  | 19        | 23     | 5.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 238       | 300    | 80.13%  |
| 0.51-1.0   | 53        | 68     | 17.85%  |
| 1.01-2.0   | 2         | 2      | 0.67%   |
| 4.01-10.0  | 2         | 2      | 0.67%   |
| 3.01-4.0   | 1         | 1      | 0.34%   |
| 2.01-3.0   | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 133       | 40.43%  |
| 251-500        | 78        | 23.71%  |
| 501-1000       | 35        | 10.64%  |
| 51-100         | 35        | 10.64%  |
| 21-50          | 17        | 5.17%   |
| 1001-2000      | 13        | 3.95%   |
| More than 3000 | 7         | 2.13%   |
| 1-20           | 7         | 2.13%   |
| 2001-3000      | 3         | 0.91%   |
| Unknown        | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 166       | 48.4%   |
| 21-50          | 74        | 21.57%  |
| 101-250        | 37        | 10.79%  |
| 51-100         | 37        | 10.79%  |
| 251-500        | 10        | 2.92%   |
| 501-1000       | 9         | 2.62%   |
| 2001-3000      | 4         | 1.17%   |
| More than 3000 | 3         | 0.87%   |
| 1001-2000      | 2         | 0.58%   |
| Unknown        | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-26A23T0 320GB        | 1         | 1      | 6.67%   |
| Seagate STM9120817AS 120GB          | 1         | 1      | 6.67%   |
| Seagate ST9640423AS 640GB           | 1         | 1      | 6.67%   |
| Seagate ST9120821AS 120GB           | 1         | 1      | 6.67%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics MP0402H 40GB    | 1         | 1      | 6.67%   |
| Phison ES 512GB                     | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 6.67%   |
| Intel SSDSCKKF256G8 SATA 256GB      | 1         | 1      | 6.67%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 6.67%   |
| Fujitsu MHZ2080BJ FFS G2 80GB       | 1         | 1      | 6.67%   |
| Crucial M4-CT256M4SSD2 256GB        | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 21.43%  |
| WDC                 | 2         | 3      | 14.29%  |
| SanDisk             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Phison              | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 3      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |
| Fujitsu             | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 64.29%  |
| SSD  | 4         | 4      | 28.57%  |
| NVMe | 1         | 1      | 7.14%   |

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
| Detected | 257       | 374    | 77.41%  |
| Works    | 61        | 78     | 18.37%  |
| Malfunc  | 14        | 15     | 4.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 244       | 70.32%  |
| AMD                              | 46        | 13.26%  |
| SanDisk                          | 13        | 3.75%   |
| Samsung Electronics              | 10        | 2.88%   |
| Silicon Integrated Systems [SiS] | 6         | 1.73%   |
| Nvidia                           | 6         | 1.73%   |
| SK hynix                         | 4         | 1.15%   |
| Phison Electronics               | 4         | 1.15%   |
| Toshiba America Info Systems     | 2         | 0.58%   |
| Micron Technology                | 2         | 0.58%   |
| Marvell Technology Group         | 2         | 0.58%   |
| KIOXIA                           | 2         | 0.58%   |
| Kingston Technology Company      | 2         | 0.58%   |
| VIA Technologies                 | 1         | 0.29%   |
| Solid State Storage Technology   | 1         | 0.29%   |
| Micron/Crucial Technology        | 1         | 0.29%   |
| Apple                            | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 30        | 7.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 22        | 5.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 21        | 5.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 20        | 5.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 16        | 4.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 13        | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 13        | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 12        | 3.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 12        | 3.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 12        | 3.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 12        | 3.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 10        | 2.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 10        | 2.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 9         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 9         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 8         | 2.02%   |
| SanDisk Non-Volatile memory controller                                                 | 7         | 1.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 6         | 1.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 6         | 1.51%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.26%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 4         | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 4         | 1.01%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 4         | 1.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.01%   |
| AMD IXP SB4x0 IDE Controller                                                           | 4         | 1.01%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 0.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 0.76%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 3         | 0.76%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 3         | 0.76%   |
| AMD SB600 IDE                                                                          | 3         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 0.5%    |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 0.5%    |
| Phison E12 NVMe Controller                                                             | 2         | 0.5%    |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.5%    |
| Nvidia MCP67 IDE Controller                                                            | 2         | 0.5%    |
| Nvidia MCP67 AHCI Controller                                                           | 2         | 0.5%    |
| Micron Non-Volatile memory controller                                                  | 2         | 0.5%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 2         | 0.5%    |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 0.5%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 0.5%    |
| Intel SSD 660P Series                                                                  | 2         | 0.5%    |
| Intel SSD 600P Series                                                                  | 2         | 0.5%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 2         | 0.5%    |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 2         | 0.5%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 0.5%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.5%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 0.5%    |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 2         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 236       | 62.6%   |
| IDE  | 75        | 19.89%  |
| NVMe | 43        | 11.41%  |
| RAID | 23        | 6.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 265       | 82.04%  |
| AMD    | 58        | 17.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                | 10        | 3.1%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 1.86%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 5         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.24%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.24%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 1.24%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.24%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.24%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.93%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 3         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.93%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.93%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.93%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 0.93%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.93%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.93%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.62%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.62%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.62%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.62%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 2         | 0.62%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.62%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 2         | 0.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.62%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.62%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.62%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.62%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.62%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.62%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 0.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.62%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.62%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.62%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.62%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.62%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.62%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.62%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.62%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.62%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.62%   |
| Intel Core Duo CPU T2400 @ 1.83GHz            | 2         | 0.62%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.62%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.62%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 2         | 0.62%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 0.62%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 2         | 0.62%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 0.62%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 52        | 16.1%   |
| Intel Core i7                  | 41        | 12.69%  |
| Intel Core i3                  | 32        | 9.91%   |
| Intel Core 2 Duo               | 29        | 8.98%   |
| Intel Atom                     | 28        | 8.67%   |
| Intel Celeron                  | 21        | 6.5%    |
| Other                          | 15        | 4.64%   |
| Intel Pentium                  | 12        | 3.72%   |
| AMD Ryzen 5                    | 10        | 3.1%    |
| Intel Genuine                  | 8         | 2.48%   |
| Intel Pentium M                | 6         | 1.86%   |
| Intel Pentium Dual             | 6         | 1.86%   |
| Intel Core 2                   | 6         | 1.86%   |
| Intel Pentium Dual-Core        | 5         | 1.55%   |
| AMD Ryzen 7                    | 5         | 1.55%   |
| AMD A4                         | 5         | 1.55%   |
| AMD E2                         | 4         | 1.24%   |
| Intel Core Duo                 | 3         | 0.93%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.93%   |
| Intel Pentium 4                | 2         | 0.62%   |
| Intel Celeron M                | 2         | 0.62%   |
| AMD Sempron                    | 2         | 0.62%   |
| AMD Ryzen 3                    | 2         | 0.62%   |
| AMD Mobile Sempron             | 2         | 0.62%   |
| AMD E1                         | 2         | 0.62%   |
| AMD E                          | 2         | 0.62%   |
| AMD Athlon II                  | 2         | 0.62%   |
| AMD Athlon                     | 2         | 0.62%   |
| AMD A6                         | 2         | 0.62%   |
| Intel Pentium Silver           | 1         | 0.31%   |
| Intel Mobile Pentium 4         | 1         | 0.31%   |
| Intel Core 2 Extreme           | 1         | 0.31%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.31%   |
| AMD Turion 64 Mobile           | 1         | 0.31%   |
| AMD Ryzen 9                    | 1         | 0.31%   |
| AMD Phenom II                  | 1         | 0.31%   |
| AMD C-50                       | 1         | 0.31%   |
| AMD Athlon Neo                 | 1         | 0.31%   |
| AMD Athlon 64 X2               | 1         | 0.31%   |
| AMD A8                         | 1         | 0.31%   |
| AMD A10                        | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 212       | 65.43%  |
| 4      | 61        | 18.83%  |
| 1      | 39        | 12.04%  |
| 8      | 6         | 1.85%   |
| 6      | 6         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 323       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 184       | 56.97%  |
| 1      | 139       | 43.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 282       | 87.31%  |
| 32-bit         | 41        | 12.69%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 6.73%   |
| 0x306a9    | 20        | 6.12%   |
| 0x206a7    | 20        | 6.12%   |
| 0x1067a    | 19        | 5.81%   |
| 0x40651    | 15        | 4.59%   |
| 0x6fd      | 13        | 3.98%   |
| 0x406e3    | 12        | 3.67%   |
| 0x30661    | 12        | 3.67%   |
| 0x106c2    | 11        | 3.36%   |
| 0x20655    | 10        | 3.06%   |
| 0x06006705 | 9         | 2.75%   |
| 0x806ea    | 8         | 2.45%   |
| 0x806c1    | 8         | 2.45%   |
| 0x306c3    | 8         | 2.45%   |
| 0x6f6      | 7         | 2.14%   |
| 0x6ec      | 7         | 2.14%   |
| 0x806ec    | 6         | 1.83%   |
| 0x20652    | 6         | 1.83%   |
| 0x10676    | 6         | 1.83%   |
| 0x08608103 | 6         | 1.83%   |
| 0x806e9    | 5         | 1.53%   |
| 0x6e8      | 5         | 1.53%   |
| 0x306d4    | 5         | 1.53%   |
| 0x30678    | 5         | 1.53%   |
| 0x706a1    | 4         | 1.22%   |
| 0x6d8      | 4         | 1.22%   |
| 0x506e3    | 4         | 1.22%   |
| 0x406c4    | 4         | 1.22%   |
| 0x08108109 | 4         | 1.22%   |
| 0x08108102 | 4         | 1.22%   |
| 0x806eb    | 3         | 0.92%   |
| 0x706e5    | 3         | 0.92%   |
| 0x106e5    | 3         | 0.92%   |
| 0x106ca    | 3         | 0.92%   |
| 0x010000c8 | 3         | 0.92%   |
| 0xf29      | 2         | 0.61%   |
| 0x906ea    | 2         | 0.61%   |
| 0x406c3    | 2         | 0.61%   |
| 0x30673    | 2         | 0.61%   |
| 0x10661    | 2         | 0.61%   |
| 0x08200103 | 2         | 0.61%   |
| 0x07030106 | 2         | 0.61%   |
| 0x07030105 | 2         | 0.61%   |
| 0x05000029 | 2         | 0.61%   |
| 0x02000032 | 2         | 0.61%   |
| 0xf24      | 1         | 0.31%   |
| 0xa0652    | 1         | 0.31%   |
| 0x906ed    | 1         | 0.31%   |
| 0x906e9    | 1         | 0.31%   |
| 0x806d1    | 1         | 0.31%   |
| 0x706a8    | 1         | 0.31%   |
| 0x6fb      | 1         | 0.31%   |
| 0x6fa      | 1         | 0.31%   |
| 0x6d6      | 1         | 0.31%   |
| 0x695      | 1         | 0.31%   |
| 0x506c9    | 1         | 0.31%   |
| 0x20661    | 1         | 0.31%   |
| 0x0a50000c | 1         | 0.31%   |
| 0x08600103 | 1         | 0.31%   |
| 0x08101016 | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Penryn          | 28        | 8.64%   |
| KabyLake        | 27        | 8.33%   |
| Bonnell         | 27        | 8.33%   |
| Haswell         | 24        | 7.41%   |
| Core            | 24        | 7.41%   |
| SandyBridge     | 21        | 6.48%   |
| IvyBridge       | 20        | 6.17%   |
| P6              | 18        | 5.56%   |
| Westmere        | 16        | 4.94%   |
| Skylake         | 16        | 4.94%   |
| Silvermont      | 13        | 4.01%   |
| Excavator       | 11        | 3.4%    |
| K8 Hammer       | 9         | 2.78%   |
| Zen+            | 8         | 2.47%   |
| TigerLake       | 8         | 2.47%   |
| Unknown         | 7         | 2.16%   |
| Broadwell       | 6         | 1.85%   |
| Goldmont plus   | 5         | 1.54%   |
| Zen             | 4         | 1.23%   |
| Puma            | 4         | 1.23%   |
| K10             | 4         | 1.23%   |
| IceLake         | 4         | 1.23%   |
| NetBurst        | 3         | 0.93%   |
| Nehalem         | 3         | 0.93%   |
| Bobcat          | 3         | 0.93%   |
| Zen 3           | 2         | 0.62%   |
| K8 & K10 hybrid | 2         | 0.62%   |
| Jaguar          | 2         | 0.62%   |
| Zen 2           | 1         | 0.31%   |
| Piledriver      | 1         | 0.31%   |
| K10 Llano       | 1         | 0.31%   |
| Goldmont        | 1         | 0.31%   |
| CometLake       | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 211       | 56.87%  |
| AMD                              | 86        | 23.18%  |
| Nvidia                           | 68        | 18.33%  |
| Silicon Integrated Systems [SiS] | 5         | 1.35%   |
| VIA Technologies                 | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                           | 18        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 17        | 4.29%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 16        | 4.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 15        | 3.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 14        | 3.54%   |
| Intel Core Processor Integrated Graphics Controller                                        | 12        | 3.03%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 12        | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 11        | 2.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 10        | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 10        | 2.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 9         | 2.27%   |
| Intel UHD Graphics 620                                                                     | 8         | 2.02%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 8         | 2.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 8         | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 7         | 1.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 6         | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 6         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 6         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 6         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 6         | 1.52%   |
| AMD Lucienne                                                                               | 6         | 1.52%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 4         | 1.01%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 4         | 1.01%   |
| Intel HD Graphics 5500                                                                     | 4         | 1.01%   |
| Intel HD Graphics 530                                                                      | 4         | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 4         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                       | 4         | 1.01%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 4         | 1.01%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                   | 4         | 1.01%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 3         | 0.76%   |
| Nvidia GF108M [GeForce GT 525M]                                                            | 3         | 0.76%   |
| Nvidia G96CM [GeForce 9600M GT]                                                            | 3         | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                     | 3         | 0.76%   |
| Intel HD Graphics 620                                                                      | 3         | 0.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 3         | 0.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 3         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 3         | 0.76%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 3         | 0.76%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.51%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.51%   |
| Nvidia GP108M [GeForce MX230]                                                              | 2         | 0.51%   |
| Nvidia GP108M [GeForce MX150]                                                              | 2         | 0.51%   |
| Nvidia GM108M [GeForce 940MX]                                                              | 2         | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                               | 2         | 0.51%   |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 2         | 0.51%   |
| Nvidia GK107M [GeForce GT 750M]                                                            | 2         | 0.51%   |
| Nvidia GK106GLM [Quadro K2100M]                                                            | 2         | 0.51%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 2         | 0.51%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                       | 2         | 0.51%   |
| Nvidia GF108GLM [Quadro 1000M]                                                             | 2         | 0.51%   |
| Nvidia G98M [Quadro NVS 160M]                                                              | 2         | 0.51%   |
| Nvidia C79 [GeForce 9400M]                                                                 | 2         | 0.51%   |
| Intel Tiger Lake UHD Graphics                                                              | 2         | 0.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]      | 2         | 0.51%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                   | 2         | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                                 | 2         | 0.51%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 2         | 0.51%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                        | 2         | 0.51%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 2         | 0.51%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                    | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 164       | 50.77%  |
| 1 x AMD        | 70        | 21.67%  |
| Intel + Nvidia | 34        | 10.53%  |
| 1 x Nvidia     | 33        | 10.22%  |
| Intel + AMD    | 13        | 4.02%   |
| 1 x SiS        | 5         | 1.55%   |
| 2 x AMD        | 2         | 0.62%   |
| 1 x VIA        | 1         | 0.31%   |
| AMD + Nvidia   | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 288       | 88.62%  |
| Unknown     | 23        | 7.08%   |
| Proprietary | 14        | 4.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 207       | 63.89%  |
| 0.01-0.5   | 61        | 18.83%  |
| 1.01-2.0   | 29        | 8.95%   |
| 0.51-1.0   | 18        | 5.56%   |
| 3.01-4.0   | 5         | 1.54%   |
| 5.01-6.0   | 3         | 0.93%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 19.49%  |
| LG Display              | 45        | 14.38%  |
| BOE                     | 41        | 13.1%   |
| Samsung Electronics     | 36        | 11.5%   |
| Chimei Innolux          | 35        | 11.18%  |
| Chi Mei Optoelectronics | 12        | 3.83%   |
| LG Philips              | 11        | 3.51%   |
| HannStar                | 8         | 2.56%   |
| Goldstar                | 7         | 2.24%   |
| Apple                   | 7         | 2.24%   |
| Lenovo                  | 6         | 1.92%   |
| InfoVision              | 5         | 1.6%    |
| BenQ                    | 4         | 1.28%   |
| Sony                    | 3         | 0.96%   |
| Quanta Display          | 3         | 0.96%   |
| PANDA                   | 3         | 0.96%   |
| Dell                    | 3         | 0.96%   |
| CPT                     | 3         | 0.96%   |
| Sharp                   | 2         | 0.64%   |
| AOC                     | 2         | 0.64%   |
| Acer                    | 2         | 0.64%   |
| ViewSonic               | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| TR_                     | 1         | 0.32%   |
| Seiko/Epson             | 1         | 0.32%   |
| Planar                  | 1         | 0.32%   |
| Philips                 | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| MLT                     | 1         | 0.32%   |
| Insignia                | 1         | 0.32%   |
| InnoLux Display         | 1         | 0.32%   |
| Hewlett-Packard         | 1         | 0.32%   |
| DENON                   | 1         | 0.32%   |
| BLS                     | 1         | 0.32%   |
| Belinea                 | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 2.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.95%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.95%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.95%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 0.95%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.95%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.95%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.63%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.63%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.63%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.63%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.63%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.63%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.63%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 2         | 0.63%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 1         | 0.32%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.32%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 0.32%   |
| Sony TV SNYA301 1920x1080                                                | 1         | 0.32%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                    | 1         | 0.32%   |
| Sony AVAMP SNYF700 1920x540                                              | 1         | 0.32%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.32%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                  | 1         | 0.32%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.32%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                           | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch    | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4642 1280x800 303x190mm 14.1-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3450 1400x1050 286x214mm 14.1-inch    | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 110       | 35.71%  |
| 1920x1080 (FHD)    | 93        | 30.19%  |
| 1280x800 (WXGA)    | 30        | 9.74%   |
| 1600x900 (HD+)     | 19        | 6.17%   |
| 1024x600           | 15        | 4.87%   |
| 1440x900 (WXGA+)   | 8         | 2.6%    |
| 1920x1200 (WUXGA)  | 7         | 2.27%   |
| 3840x2160 (4K)     | 6         | 1.95%   |
| 2560x1440 (QHD)    | 2         | 0.65%   |
| 1680x1050 (WSXGA+) | 2         | 0.65%   |
| 1280x768           | 2         | 0.65%   |
| 1280x1024 (SXGA)   | 2         | 0.65%   |
| 1024x768 (XGA)     | 2         | 0.65%   |
| 3840x1080          | 1         | 0.32%   |
| 2880x1800          | 1         | 0.32%   |
| 2560x1600          | 1         | 0.32%   |
| 2560x1080          | 1         | 0.32%   |
| 2256x1504          | 1         | 0.32%   |
| 1920x540           | 1         | 0.32%   |
| 1400x1050          | 1         | 0.32%   |
| 1360x768           | 1         | 0.32%   |
| 1280x720 (HD)      | 1         | 0.32%   |
| Unknown            | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 144       | 46.01%  |
| 14      | 41        | 13.1%   |
| 13      | 38        | 12.14%  |
| 17      | 22        | 7.03%   |
| 10      | 14        | 4.47%   |
| 12      | 6         | 1.92%   |
| 11      | 6         | 1.92%   |
| 27      | 5         | 1.6%    |
| 18      | 5         | 1.6%    |
| Unknown | 5         | 1.6%    |
| 24      | 4         | 1.28%   |
| 23      | 4         | 1.28%   |
| 21      | 4         | 1.28%   |
| 72      | 3         | 0.96%   |
| 19      | 3         | 0.96%   |
| 34      | 2         | 0.64%   |
| 31      | 2         | 0.64%   |
| 8       | 2         | 0.64%   |
| 48      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 202       | 64.95%  |
| 201-300     | 42        | 13.5%   |
| 351-400     | 30        | 9.65%   |
| 501-600     | 11        | 3.54%   |
| 401-500     | 11        | 3.54%   |
| Unknown     | 5         | 1.61%   |
| 1501-2000   | 3         | 0.96%   |
| 701-800     | 2         | 0.64%   |
| 601-700     | 2         | 0.64%   |
| 101-200     | 2         | 0.64%   |
| 1001-1500   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 233       | 79.25%  |
| 16/10   | 48        | 16.33%  |
| 5/4     | 3         | 1.02%   |
| 4/3     | 3         | 1.02%   |
| Unknown | 3         | 1.02%   |
| 3/2     | 2         | 0.68%   |
| 32/9    | 1         | 0.34%   |
| 21/9    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 143       | 45.54%  |
| 81-90          | 66        | 21.02%  |
| 121-130        | 16        | 5.1%    |
| 41-50          | 14        | 4.46%   |
| 71-80          | 12        | 3.82%   |
| 201-250        | 9         | 2.87%   |
| 61-70          | 6         | 1.91%   |
| 51-60          | 6         | 1.91%   |
| 131-140        | 6         | 1.91%   |
| 301-350        | 5         | 1.59%   |
| 151-200        | 5         | 1.59%   |
| 141-150        | 5         | 1.59%   |
| Unknown        | 5         | 1.59%   |
| More than 1000 | 4         | 1.27%   |
| 91-100         | 4         | 1.27%   |
| 351-500        | 3         | 0.96%   |
| 1-40           | 2         | 0.64%   |
| 251-300        | 2         | 0.64%   |
| 501-1000       | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 137       | 44.34%  |
| 121-160       | 93        | 30.1%   |
| 51-100        | 56        | 18.12%  |
| 161-240       | 10        | 3.24%   |
| 1-50          | 5         | 1.62%   |
| Unknown       | 5         | 1.62%   |
| More than 240 | 3         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 279       | 85.32%  |
| 2     | 29        | 8.87%   |
| 0     | 18        | 5.5%    |
| 3     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 179       | 32.72%  |
| Intel                                 | 124       | 22.67%  |
| Qualcomm Atheros                      | 106       | 19.38%  |
| Broadcom                              | 51        | 9.32%   |
| Marvell Technology Group              | 13        | 2.38%   |
| Broadcom Limited                      | 12        | 2.19%   |
| Ralink                                | 7         | 1.28%   |
| Silicon Integrated Systems [SiS]      | 5         | 0.91%   |
| Samsung Electronics                   | 5         | 0.91%   |
| Nvidia                                | 5         | 0.91%   |
| Ralink Technology                     | 3         | 0.55%   |
| JMicron Technology                    | 3         | 0.55%   |
| Ericsson Business Mobile Networks     | 3         | 0.55%   |
| Xiaomi                                | 2         | 0.37%   |
| TP-Link                               | 2         | 0.37%   |
| Huawei Technologies                   | 2         | 0.37%   |
| Dell                                  | 2         | 0.37%   |
| Attansic Technology                   | 2         | 0.37%   |
| AMD                                   | 2         | 0.37%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.18%   |
| VIA Technologies                      | 1         | 0.18%   |
| ST-Ericsson                           | 1         | 0.18%   |
| Sierra Wireless                       | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.18%   |
| NetGear                               | 1         | 0.18%   |
| MediaTek                              | 1         | 0.18%   |
| Manta                                 | 1         | 0.18%   |
| Linksys                               | 1         | 0.18%   |
| Lenovo                                | 1         | 0.18%   |
| Intersil                              | 1         | 0.18%   |
| Hewlett-Packard                       | 1         | 0.18%   |
| Google                                | 1         | 0.18%   |
| Gemtek                                | 1         | 0.18%   |
| DisplayLink                           | 1         | 0.18%   |
| Davicom Semiconductor                 | 1         | 0.18%   |
| Cisco Aironet Wireless Communications | 1         | 0.18%   |
| ASUSTek Computer                      | 1         | 0.18%   |
| Askey Computer                        | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 89        | 13.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 53        | 8.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 3.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 1.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 1.37%   |
| Intel Wireless 7260                                                     | 9         | 1.37%   |
| Intel WiFi Link 5100                                                    | 9         | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.06%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.06%   |
| Intel Wireless 3165                                                     | 6         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.76%   |
| Intel Wireless 3160                                                     | 5         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.61%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 4         | 0.61%   |
| Intel Wireless 8260                                                     | 4         | 0.61%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.61%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.61%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.61%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.46%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.46%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 3         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.46%   |
| Intel Wireless 7265                                                     | 3         | 0.46%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.46%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 3         | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.46%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 3         | 0.46%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 109       | 32.73%  |
| Qualcomm Atheros                      | 94        | 28.23%  |
| Realtek Semiconductor                 | 66        | 19.82%  |
| Broadcom                              | 38        | 11.41%  |
| Ralink                                | 7         | 2.1%    |
| Broadcom Limited                      | 7         | 2.1%    |
| Ralink Technology                     | 3         | 0.9%    |
| TP-Link                               | 2         | 0.6%    |
| Sierra Wireless                       | 1         | 0.3%    |
| NetGear                               | 1         | 0.3%    |
| Linksys                               | 1         | 0.3%    |
| Ericsson Business Mobile Networks     | 1         | 0.3%    |
| Cisco Aironet Wireless Communications | 1         | 0.3%    |
| ASUSTek Computer                      | 1         | 0.3%    |
| Askey Computer                        | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 6.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 5.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 4.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 4.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 3.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 3.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 3.53%   |
| Intel Wireless 7260                                                     | 9         | 2.65%   |
| Intel WiFi Link 5100                                                    | 9         | 2.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.06%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.06%   |
| Intel Wireless 3165                                                     | 6         | 1.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.47%   |
| Intel Wireless 3160                                                     | 5         | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.18%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.18%   |
| Intel Wireless 8260                                                     | 4         | 1.18%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.18%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.18%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.88%   |
| Intel Wireless 7265                                                     | 3         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.88%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.59%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.59%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.59%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.59%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.59%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.29%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.29%   |
| Sierra Wireless MC8305                                                  | 1         | 0.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.29%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.29%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.29%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 154       | 51.33%  |
| Intel                            | 51        | 17%     |
| Qualcomm Atheros                 | 26        | 8.67%   |
| Broadcom                         | 18        | 6%      |
| Marvell Technology Group         | 13        | 4.33%   |
| Silicon Integrated Systems [SiS] | 5         | 1.67%   |
| Samsung Electronics              | 5         | 1.67%   |
| Nvidia                           | 5         | 1.67%   |
| Broadcom Limited                 | 5         | 1.67%   |
| JMicron Technology               | 3         | 1%      |
| Xiaomi                           | 2         | 0.67%   |
| Attansic Technology              | 2         | 0.67%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.33%   |
| VIA Technologies                 | 1         | 0.33%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.33%   |
| MediaTek                         | 1         | 0.33%   |
| Lenovo                           | 1         | 0.33%   |
| Huawei Technologies              | 1         | 0.33%   |
| Hewlett-Packard                  | 1         | 0.33%   |
| Google                           | 1         | 0.33%   |
| Gemtek                           | 1         | 0.33%   |
| DisplayLink                      | 1         | 0.33%   |
| Davicom Semiconductor            | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 89        | 29.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 53        | 17.67%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 3%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 2.67%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.67%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 1.33%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 4         | 1.33%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.33%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 1.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 3         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 1%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 1%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 1%      |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 1%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 3         | 1%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1%      |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.67%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.67%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.67%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 2         | 0.67%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.67%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.67%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 2         | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.67%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.67%   |
| ZTE WCDMA MSM Z6201V                                                           | 1         | 0.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.33%   |
| OnePlus (Shenzhen) OnePlus                                                     | 1         | 0.33%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.33%   |
| MediaTek Le                                                                    | 1         | 0.33%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.33%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.33%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.33%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.33%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.33%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.33%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 317       | 51.13%  |
| Ethernet | 285       | 45.97%  |
| Modem    | 15        | 2.42%   |
| Unknown  | 3         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 249       | 76.38%  |
| Ethernet | 77        | 23.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 266       | 82.35%  |
| 1     | 49        | 15.17%  |
| 0     | 5         | 1.55%   |
| 3     | 2         | 0.62%   |
| 4     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 266       | 81.6%   |
| Yes  | 60        | 18.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 29.74%  |
| Realtek Semiconductor           | 31        | 15.9%   |
| Qualcomm Atheros Communications | 21        | 10.77%  |
| Broadcom                        | 16        | 8.21%   |
| Foxconn / Hon Hai               | 14        | 7.18%   |
| Hewlett-Packard                 | 11        | 5.64%   |
| Lite-On Technology              | 8         | 4.1%    |
| Dell                            | 8         | 4.1%    |
| IMC Networks                    | 6         | 3.08%   |
| Apple                           | 5         | 2.56%   |
| Cambridge Silicon Radio         | 3         | 1.54%   |
| ASUSTek Computer                | 3         | 1.54%   |
| Toshiba                         | 2         | 1.03%   |
| Foxconn International           | 2         | 1.03%   |
| Taiyo Yuden                     | 1         | 0.51%   |
| Realtek                         | 1         | 0.51%   |
| Ralink Technology               | 1         | 0.51%   |
| Ralink                          | 1         | 0.51%   |
| Qcom                            | 1         | 0.51%   |
| Askey Computer                  | 1         | 0.51%   |
| Alps Electric                   | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 32        | 16.41%  |
| Realtek Bluetooth Radio                                                             | 17        | 8.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 12        | 6.15%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 5.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 4.1%    |
| Intel AX201 Bluetooth                                                               | 7         | 3.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 3.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 2.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 2.05%   |
| Intel AX200 Bluetooth                                                               | 4         | 2.05%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2.05%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.05%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 2.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.54%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 1.54%   |
| Foxconn / Hon Hai Acer Module                                                       | 3         | 1.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.54%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.03%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.03%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 1.03%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.03%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 1.03%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.03%   |
| Broadcom Bluetooth                                                                  | 2         | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.03%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.03%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.03%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.03%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.51%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.51%   |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.51%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.51%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.51%   |
| Ralink CSR BS8510                                                                   | 1         | 0.51%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.51%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.51%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.51%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.51%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.51%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.51%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.51%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.51%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.51%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.51%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.51%   |
| Askey Bluetooth Device                                                              | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 252       | 67.56%  |
| AMD                              | 71        | 19.03%  |
| Nvidia                           | 32        | 8.58%   |
| Silicon Integrated Systems [SiS] | 6         | 1.61%   |
| Texas Instruments                | 2         | 0.54%   |
| C-Media Electronics              | 2         | 0.54%   |
| Yamaha                           | 1         | 0.27%   |
| VIA Technologies                 | 1         | 0.27%   |
| Tenx Technology                  | 1         | 0.27%   |
| Realtek Semiconductor            | 1         | 0.27%   |
| GN Netcom                        | 1         | 0.27%   |
| Generalplus Technology           | 1         | 0.27%   |
| Dell                             | 1         | 0.27%   |
| Audioengine                      | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 36        | 8%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 27        | 6%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 4.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 3.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 2.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 2.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 2.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 11        | 2.44%   |
| AMD High Definition Audio Controller                                                              | 10        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.78%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.33%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.11%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 5         | 1.11%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.89%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.89%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 0.89%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.67%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 0.44%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.44%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.44%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.44%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.44%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2         | 0.44%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.44%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 2         | 0.44%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.44%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.22%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.22%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.22%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                                                 | 1         | 0.22%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.22%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.22%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 20        | 23.53%  |
| Samsung Electronics          | 20        | 23.53%  |
| Unknown                      | 10        | 11.76%  |
| Kingston                     | 9         | 10.59%  |
| Nanya Technology             | 4         | 4.71%   |
| Micron Technology            | 4         | 4.71%   |
| Ramaxel Technology           | 3         | 3.53%   |
| A-DATA Technology            | 3         | 3.53%   |
| Unknown (ABCD)               | 2         | 2.35%   |
| Smart                        | 2         | 2.35%   |
| Crucial                      | 2         | 2.35%   |
| Transcend                    | 1         | 1.18%   |
| Patriot Memory (PDP Systems) | 1         | 1.18%   |
| Patriot                      | 1         | 1.18%   |
| G.Skill                      | 1         | 1.18%   |
| Corsair                      | 1         | 1.18%   |
| Unknown                      | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 2.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 2.2%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.2%    |
| Unknown RAM Module SODIMM DDR                                       | 1         | 1.1%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                         | 1         | 1.1%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 1.1%    |
| Unknown RAM Module 512MB SODIMM DDR                                 | 1         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.1%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 1.1%    |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 1.1%    |
| Unknown RAM Module 1024MB SODIMM DDR3                               | 1         | 1.1%    |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                       | 1         | 1.1%    |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                   | 1         | 1.1%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                     | 1         | 1.1%    |
| SK hynix RAM Module 512MB SODIMM DDR 533MT/s                        | 1         | 1.1%    |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                       | 1         | 1.1%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 1.1%    |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s               | 1         | 1.1%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 1.1%    |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s            | 1         | 1.1%    |
| SK hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR 800MT/s             | 1         | 1.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.1%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 1.1%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 1.1%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 1.1%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 1.1%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.1%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.1%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.1%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.1%    |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s           | 1         | 1.1%    |
| Ramaxel RAM RMSA3330MJ78HBF-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 1.1%    |
| Ramaxel RAM RMSA3260MF68H9F-2666 4GB SODIMM DDR4 2400MT/s           | 1         | 1.1%    |
| Ramaxel RAM RMN1150EC48D7W-800 1024MB SODIMM DDR2 800MT/s           | 1         | 1.1%    |
| Patriot RAM PSD44G240081S 4GB SODIMM DDR4 2400MT/s                  | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 42.31%  |
| DDR3   | 29        | 37.18%  |
| DDR2   | 6         | 7.69%   |
| SDRAM  | 4         | 5.13%   |
| LPDDR4 | 3         | 3.85%   |
| DDR    | 3         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 97.4%   |
| Row Of Chips | 2         | 2.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 30        | 35.29%  |
| 4096    | 25        | 29.41%  |
| 2048    | 16        | 18.82%  |
| 1024    | 6         | 7.06%   |
| 16384   | 3         | 3.53%   |
| 32768   | 2         | 2.35%   |
| 512     | 2         | 2.35%   |
| Unknown | 1         | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 20        | 24.39%  |
| 3200    | 14        | 17.07%  |
| 2667    | 14        | 17.07%  |
| 2400    | 8         | 9.76%   |
| Unknown | 5         | 6.1%    |
| 1333    | 4         | 4.88%   |
| 800     | 3         | 3.66%   |
| 2048    | 2         | 2.44%   |
| 975     | 2         | 2.44%   |
| 533     | 2         | 2.44%   |
| 4267    | 1         | 1.22%   |
| 4199    | 1         | 1.22%   |
| 3266    | 1         | 1.22%   |
| 2267    | 1         | 1.22%   |
| 2133    | 1         | 1.22%   |
| 1334    | 1         | 1.22%   |
| 1200    | 1         | 1.22%   |
| 667     | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-3100 Series | 1         | 50%     |
| HP DeskJet 2700 series     | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 57        | 22.71%  |
| IMC Networks                           | 24        | 9.56%   |
| Suyin                                  | 23        | 9.16%   |
| Sunplus Innovation Technology          | 20        | 7.97%   |
| Microdia                               | 20        | 7.97%   |
| Acer                                   | 19        | 7.57%   |
| Quanta                                 | 17        | 6.77%   |
| Realtek Semiconductor                  | 16        | 6.37%   |
| Silicon Motion                         | 7         | 2.79%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.79%   |
| Ricoh                                  | 6         | 2.39%   |
| Apple                                  | 6         | 2.39%   |
| Syntek                                 | 4         | 1.59%   |
| Alcor Micro                            | 4         | 1.59%   |
| ALi                                    | 3         | 1.2%    |
| Z-Star Microelectronics                | 2         | 0.8%    |
| Sunplus Technology                     | 2         | 0.8%    |
| Luxvisions Innotech Limited            | 2         | 0.8%    |
| Lite-On Technology                     | 2         | 0.8%    |
| Lenovo                                 | 2         | 0.8%    |
| Importek                               | 2         | 0.8%    |
| Samsung Electronics                    | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| LG Electronics                         | 1         | 0.4%    |
| Intel                                  | 1         | 0.4%    |
| icSpring                               | 1         | 0.4%    |
| Generalplus Technology                 | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 12        | 4.76%   |
| Chicony Integrated Camera                        | 10        | 3.97%   |
| Quanta HP Webcam                                 | 6         | 2.38%   |
| Chicony HD Webcam                                | 6         | 2.38%   |
| Suyin HP TrueVision HD                           | 5         | 1.98%   |
| Quanta HP TrueVision HD Camera                   | 5         | 1.98%   |
| Chicony HP TrueVision HD Camera                  | 5         | 1.98%   |
| Acer HD Webcam                                   | 5         | 1.98%   |
| Realtek Integrated_Webcam_HD                     | 4         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 4         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 1.59%   |
| IMC Networks Integrated Camera                   | 4         | 1.59%   |
| Apple iPhone 5/5C/5S/6/SE                        | 4         | 1.59%   |
| Acer Integrated Camera                           | 4         | 1.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 3         | 1.19%   |
| Suyin 1.3M HD WebCam                             | 3         | 1.19%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 3         | 1.19%   |
| Sunplus HP TrueVision HD Camera                  | 3         | 1.19%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 1.19%   |
| Quanta VGA WebCam                                | 3         | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.19%   |
| Chicony USB 2.0 Camera                           | 3         | 1.19%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 3         | 1.19%   |
| Alcor Micro USB 2.0 Camera                       | 3         | 1.19%   |
| Acer Lenovo EasyCamera                           | 3         | 1.19%   |
| Syntek Sonix USB 2.0 Camera                      | 2         | 0.79%   |
| Suyin HP Webcam                                  | 2         | 0.79%   |
| Suyin HD WebCam                                  | 2         | 0.79%   |
| Suyin HD Video WebCam                            | 2         | 0.79%   |
| Suyin Acer CrystalEye Webcam                     | 2         | 0.79%   |
| Sunplus Laptop Integrated WebCam HD              | 2         | 0.79%   |
| Sunplus HD WebCam                                | 2         | 0.79%   |
| Silicon Motion WebCam SCB-0385N                  | 2         | 0.79%   |
| Silicon Motion WebCam SC-0311139N                | 2         | 0.79%   |
| Silicon Motion HP Webcam-101                     | 2         | 0.79%   |
| Ricoh Sony Visual Communication Camera           | 2         | 0.79%   |
| Realtek Lenovo EasyCamera                        | 2         | 0.79%   |
| Realtek HP Truevision HD integrated webcam       | 2         | 0.79%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 0.79%   |
| IMC Networks USB 2.0 UVC VGA WebCam              | 2         | 0.79%   |
| IMC Networks Integrated Webcam                   | 2         | 0.79%   |
| IMC Networks EasyCamera                          | 2         | 0.79%   |
| Chicony USB2.0 Camera                            | 2         | 0.79%   |
| Chicony TOSHIBA Web Camera - HD                  | 2         | 0.79%   |
| Chicony HD WebCam (Acer)                         | 2         | 0.79%   |
| Chicony EasyCamera                               | 2         | 0.79%   |
| Chicony 1.3M Webcam                              | 2         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.79%   |
| Apple Built-in iSight                            | 2         | 0.79%   |
| ALi Gateway Webcam                               | 2         | 0.79%   |
| Acer USB2.0 Camera                               | 2         | 0.79%   |
| Z-Star Namuga 1.3M Webcam                        | 1         | 0.4%    |
| Z-Star Lenovo EasyCamera                         | 1         | 0.4%    |
| Syntek Integrated Webcam                         | 1         | 0.4%    |
| Syntek HP Webcam                                 | 1         | 0.4%    |
| Suyin WebCam                                     | 1         | 0.4%    |
| Suyin HP Webcam-101                              | 1         | 0.4%    |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 0.4%    |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 0.4%    |
| Sunplus 1.3M WebCam                              | 1         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 44.74%  |
| AuthenTec                  | 8         | 21.05%  |
| STMicroelectronics         | 4         | 10.53%  |
| Synaptics                  | 2         | 5.26%   |
| LighTuning Technology      | 2         | 5.26%   |
| Elan Microelectronics      | 2         | 5.26%   |
| Upek                       | 1         | 2.63%   |
| Shenzhen Goodix Technology | 1         | 2.63%   |
| Focal-systems.Corp         | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 10.53%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 10.53%  |
| Validity Sensors VFS301 Fingerprint Reader             | 3         | 7.89%   |
| Validity Sensors VFS491                                | 2         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 5.26%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 5.26%   |
| Elan ELAN:Fingerprint                                  | 2         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 2         | 5.26%   |
| AuthenTec AES2810                                      | 2         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 5.26%   |
| AuthenTec AES1600                                      | 2         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 2.63%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.63%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.63%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 2.63%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.63%   |
| Unknown                                                | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 65%     |
| O2 Micro              | 3         | 15%     |
| Alcor Micro           | 2         | 10%     |
| Lenovo                | 1         | 5%      |
| Gemalto (was Gemplus) | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 35%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 10%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 5%      |
| Broadcom 5880                                                                | 1         | 5%      |
| Broadcom 58200                                                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 208       | 63.41%  |
| 1     | 91        | 27.74%  |
| 2     | 20        | 6.1%    |
| 3     | 8         | 2.44%   |
| 6     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 40        | 26.14%  |
| Fingerprint reader       | 37        | 24.18%  |
| Net/wireless             | 26        | 16.99%  |
| Chipcard                 | 18        | 11.76%  |
| Multimedia controller    | 15        | 9.8%    |
| Storage                  | 6         | 3.92%   |
| Communication controller | 4         | 2.61%   |
| Flash memory             | 2         | 1.31%   |
| Sound                    | 1         | 0.65%   |
| Network                  | 1         | 0.65%   |
| Dvb card                 | 1         | 0.65%   |
| Camera                   | 1         | 0.65%   |
| Bluetooth                | 1         | 0.65%   |

