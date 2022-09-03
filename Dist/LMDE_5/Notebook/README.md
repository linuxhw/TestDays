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

Total: 128

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
| 5.10.0-14-amd64      | 20        | 20%     |
| 5.10.0-12-amd64      | 19        | 19%     |
| 5.10.0-15-amd64      | 16        | 16%     |
| 5.10.0-13-amd64      | 14        | 14%     |
| 5.10.0-16-amd64      | 10        | 10%     |
| 5.10.0-13-686        | 5         | 5%      |
| 5.18.0-0.bpo.1-amd64 | 4         | 4%      |
| 5.10.0-17-amd64      | 4         | 4%      |
| 5.16.0-0.bpo.4-amd64 | 3         | 3%      |
| 5.18.0-4-amd64       | 1         | 1%      |
| 5.18.0-3-amd64       | 1         | 1%      |
| 5.16.0-0.bpo.3-amd64 | 1         | 1%      |
| 5.15.0-0.bpo.3-amd64 | 1         | 1%      |
| 5.10.0-14-686        | 1         | 1%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 85        | 89.47%  |
| 5.18.0  | 6         | 6.32%   |
| 5.16.0  | 3         | 3.16%   |
| 5.15.0  | 1         | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 85        | 89.47%  |
| 5.18    | 6         | 6.32%   |
| 5.16    | 3         | 3.16%   |
| 5.15    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 88        | 93.62%  |
| i686   | 6         | 6.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 84        | 89.36%  |
| Cinnamon   | 8         | 8.51%   |
| MATE       | 1         | 1.06%   |
| Unknown    | 1         | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 94        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 57.45%  |
| LightDM | 40        | 42.55%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 37        | 39.36%  |
| de_DE | 11        | 11.7%   |
| ru_RU | 7         | 7.45%   |
| pt_BR | 6         | 6.38%   |
| fr_FR | 5         | 5.32%   |
| en_GB | 5         | 5.32%   |
| es_MX | 3         | 3.19%   |
| es_ES | 3         | 3.19%   |
| pl_PL | 2         | 2.13%   |
| es_BO | 2         | 2.13%   |
| en_IE | 2         | 2.13%   |
| pt_PT | 1         | 1.06%   |
| nn_NO | 1         | 1.06%   |
| nl_AW | 1         | 1.06%   |
| ko_KR | 1         | 1.06%   |
| it_IT | 1         | 1.06%   |
| hu_HU | 1         | 1.06%   |
| fr_BE | 1         | 1.06%   |
| es_PE | 1         | 1.06%   |
| es_EC | 1         | 1.06%   |
| es_CR | 1         | 1.06%   |
| en_CA | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 64        | 68.09%  |
| BIOS | 30        | 31.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 92.55%  |
| Overlay | 5         | 5.32%   |
| Xfs     | 1         | 1.06%   |
| Tmpfs   | 1         | 1.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 56.38%  |
| GPT     | 35        | 37.23%  |
| MBR     | 6         | 6.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 91.58%  |
| Yes       | 8         | 8.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 88.3%   |
| Yes       | 11        | 11.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 23        | 24.47%  |
| Dell             | 17        | 18.09%  |
| Lenovo           | 13        | 13.83%  |
| Acer             | 10        | 10.64%  |
| ASUSTek Computer | 6         | 6.38%   |
| Apple            | 4         | 4.26%   |
| Toshiba          | 2         | 2.13%   |
| Sony             | 2         | 2.13%   |
| MSI              | 2         | 2.13%   |
| Wortmann AG      | 1         | 1.06%   |
| Philco           | 1         | 1.06%   |
| Packard Bell     | 1         | 1.06%   |
| Multilaser       | 1         | 1.06%   |
| Microtech        | 1         | 1.06%   |
| Medion           | 1         | 1.06%   |
| LincPlus         | 1         | 1.06%   |
| Howard Computers | 1         | 1.06%   |
| Google           | 1         | 1.06%   |
| Framework        | 1         | 1.06%   |
| Dynabook         | 1         | 1.06%   |
| Dixonsxp         | 1         | 1.06%   |
| AMI              | 1         | 1.06%   |
| Alienware        | 1         | 1.06%   |
| Unknown          | 1         | 1.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| HP Laptop 15z-ef2xxx                             | 2         | 2.13%   |
| Dell Latitude E6400                              | 2         | 2.13%   |
| Dell Latitude E5540                              | 2         | 2.13%   |
| Unknown                                          | 2         | 2.13%   |
| Wortmann AG TERRA_MOBILE_1713A                   | 1         | 1.06%   |
| Toshiba Satellite M55                            | 1         | 1.06%   |
| Toshiba Satellite L455                           | 1         | 1.06%   |
| Sony SVE1713Y1RB                                 | 1         | 1.06%   |
| Sony SVE1512G1RW                                 | 1         | 1.06%   |
| Philco 10D                                       | 1         | 1.06%   |
| Packard Bell DOT S                               | 1         | 1.06%   |
| Multilaser PC150                                 | 1         | 1.06%   |
| MSI U180                                         | 1         | 1.06%   |
| MSI GL73 8SE                                     | 1         | 1.06%   |
| Microtech ebookPro                               | 1         | 1.06%   |
| Medion E6220                                     | 1         | 1.06%   |
| LincPlus LINNCPLUS P1                            | 1         | 1.06%   |
| Lenovo Z50-70 20354                              | 1         | 1.06%   |
| Lenovo ThinkPad T61 7661A16                      | 1         | 1.06%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 1.06%   |
| Lenovo ThinkPad T470s 20HF0047UK                 | 1         | 1.06%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS            | 1         | 1.06%   |
| Lenovo ThinkPad T450 20BUS0QT04                  | 1         | 1.06%   |
| Lenovo ThinkPad E14 Gen 2 20TACTO1WW             | 1         | 1.06%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 1.06%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 1.06%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 1.06%   |
| Lenovo IdeaPad 3 15ADA05 81W1                    | 1         | 1.06%   |
| Lenovo IdeaPad 3 14ALC6 82KT                     | 1         | 1.06%   |
| Lenovo G500 20236                                | 1         | 1.06%   |
| Howard Computers R7X                             | 1         | 1.06%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 1.06%   |
| HP ProBook 6570b                                 | 1         | 1.06%   |
| HP ProBook 450 G8 Notebook PC                    | 1         | 1.06%   |
| HP Presario C500 (GF581UA#ABA)                   | 1         | 1.06%   |
| HP Pavilion Laptop 15-eh1xxx                     | 1         | 1.06%   |
| HP Pavilion 17                                   | 1         | 1.06%   |
| HP Notebook                                      | 1         | 1.06%   |
| HP Laptop 15s-eq2xxx                             | 1         | 1.06%   |
| HP Laptop 15-dy2xxx                              | 1         | 1.06%   |
| HP Laptop 15-bw0xx                               | 1         | 1.06%   |
| HP Laptop 14-dk1xxx                              | 1         | 1.06%   |
| HP Laptop 14-df0xxx                              | 1         | 1.06%   |
| HP Laptop 14-cf3xxx                              | 1         | 1.06%   |
| HP ENVY 17                                       | 1         | 1.06%   |
| HP EliteBook 8730w                               | 1         | 1.06%   |
| HP EliteBook 840 G1                              | 1         | 1.06%   |
| HP Compaq Presario CQ71                          | 1         | 1.06%   |
| HP Compaq 15                                     | 1         | 1.06%   |
| HP 255 G7 Notebook PC                            | 1         | 1.06%   |
| HP 255 G5 Notebook PC                            | 1         | 1.06%   |
| HP 14                                            | 1         | 1.06%   |
| Google Akemi                                     | 1         | 1.06%   |
| Framework Laptop                                 | 1         | 1.06%   |
| Dynabook Satellite Pro C50-G                     | 1         | 1.06%   |
| Dell XPS 13 9305                                 | 1         | 1.06%   |
| Dell Vostro 5490                                 | 1         | 1.06%   |
| Dell Vostro 3500                                 | 1         | 1.06%   |
| Dell Precision M4400                             | 1         | 1.06%   |
| Dell Precision 7520                              | 1         | 1.06%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| HP Laptop            | 8         | 8.51%   |
| Acer Aspire          | 8         | 8.51%   |
| Dell Latitude        | 7         | 7.45%   |
| Lenovo ThinkPad      | 6         | 6.38%   |
| Dell Inspiron        | 5         | 5.32%   |
| Lenovo IdeaPad       | 4         | 4.26%   |
| ASUS VivoBook        | 3         | 3.19%   |
| Toshiba Satellite    | 2         | 2.13%   |
| HP ProBook           | 2         | 2.13%   |
| HP Pavilion          | 2         | 2.13%   |
| HP EliteBook         | 2         | 2.13%   |
| HP Compaq            | 2         | 2.13%   |
| HP 255               | 2         | 2.13%   |
| Dell Vostro          | 2         | 2.13%   |
| Dell Precision       | 2         | 2.13%   |
| Unknown              | 2         | 2.13%   |
| Wortmann AG TERRA    | 1         | 1.06%   |
| Sony SVE1713Y1RB     | 1         | 1.06%   |
| Sony SVE1512G1RW     | 1         | 1.06%   |
| Philco 10D           | 1         | 1.06%   |
| Packard Bell DOT     | 1         | 1.06%   |
| Multilaser PC150     | 1         | 1.06%   |
| MSI U180             | 1         | 1.06%   |
| MSI GL73             | 1         | 1.06%   |
| Microtech ebookPro   | 1         | 1.06%   |
| Medion E6220         | 1         | 1.06%   |
| LincPlus LINNCPLUS   | 1         | 1.06%   |
| Lenovo Z50-70        | 1         | 1.06%   |
| Lenovo Legion        | 1         | 1.06%   |
| Lenovo G500          | 1         | 1.06%   |
| Howard Computers R7X | 1         | 1.06%   |
| HP ZBook             | 1         | 1.06%   |
| HP Presario          | 1         | 1.06%   |
| HP Notebook          | 1         | 1.06%   |
| HP ENVY              | 1         | 1.06%   |
| HP 14                | 1         | 1.06%   |
| Google Akemi         | 1         | 1.06%   |
| Framework Laptop     | 1         | 1.06%   |
| Dynabook Satellite   | 1         | 1.06%   |
| Dell XPS             | 1         | 1.06%   |
| ASUS ROG             | 1         | 1.06%   |
| ASUS N61Jv           | 1         | 1.06%   |
| ASUS 1005P           | 1         | 1.06%   |
| Apple MacBookPro14   | 1         | 1.06%   |
| Apple MacBookPro11   | 1         | 1.06%   |
| Apple MacBookAir7    | 1         | 1.06%   |
| Apple MacBookAir6    | 1         | 1.06%   |
| AMI T3               | 1         | 1.06%   |
| Alienware 14         | 1         | 1.06%   |
| Acer AOD270          | 1         | 1.06%   |
| Acer AOA110          | 1         | 1.06%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 18.09%  |
| 2020 | 9         | 9.57%   |
| 2013 | 8         | 8.51%   |
| 2012 | 8         | 8.51%   |
| 2019 | 6         | 6.38%   |
| 2017 | 6         | 6.38%   |
| 2016 | 6         | 6.38%   |
| 2014 | 6         | 6.38%   |
| 2018 | 5         | 5.32%   |
| 2010 | 5         | 5.32%   |
| 2009 | 4         | 4.26%   |
| 2008 | 4         | 4.26%   |
| 2015 | 3         | 3.19%   |
| 2007 | 3         | 3.19%   |
| 2011 | 2         | 2.13%   |
| 2022 | 1         | 1.06%   |
| 2006 | 1         | 1.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 94        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 82        | 86.32%  |
| Enabled  | 13        | 13.68%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 98.94%  |
| Yes  | 1         | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 26        | 27.66%  |
| 3.01-4.0    | 26        | 27.66%  |
| 8.01-16.0   | 14        | 14.89%  |
| 16.01-24.0  | 13        | 13.83%  |
| 1.01-2.0    | 7         | 7.45%   |
| 32.01-64.0  | 3         | 3.19%   |
| 2.01-3.0    | 3         | 3.19%   |
| 64.01-256.0 | 2         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 43        | 43.88%  |
| 2.01-3.0   | 33        | 33.67%  |
| 3.01-4.0   | 9         | 9.18%   |
| 4.01-8.0   | 6         | 6.12%   |
| 0.51-1.0   | 5         | 5.1%    |
| 32.01-64.0 | 1         | 1.02%   |
| 8.01-16.0  | 1         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 74.74%  |
| 2      | 20        | 21.05%  |
| 3      | 3         | 3.16%   |
| 4      | 1         | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 69.15%  |
| Yes       | 29        | 30.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 75.53%  |
| No        | 23        | 24.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 97.87%  |
| No        | 2         | 2.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 71.28%  |
| No        | 27        | 28.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 16.67%  |
| Germany     | 12        | 12.5%   |
| Russia      | 9         | 9.38%   |
| UK          | 8         | 8.33%   |
| Brazil      | 7         | 7.29%   |
| France      | 5         | 5.21%   |
| Poland      | 4         | 4.17%   |
| Spain       | 3         | 3.13%   |
| Mexico      | 3         | 3.13%   |
| Canada      | 3         | 3.13%   |
| Romania     | 2         | 2.08%   |
| Italy       | 2         | 2.08%   |
| Hungary     | 2         | 2.08%   |
| Chile       | 2         | 2.08%   |
| Bolivia     | 2         | 2.08%   |
| Belgium     | 2         | 2.08%   |
| Vietnam     | 1         | 1.04%   |
| South Korea | 1         | 1.04%   |
| Portugal    | 1         | 1.04%   |
| Peru        | 1         | 1.04%   |
| Paraguay    | 1         | 1.04%   |
| Norway      | 1         | 1.04%   |
| Malaysia    | 1         | 1.04%   |
| Lithuania   | 1         | 1.04%   |
| Kenya       | 1         | 1.04%   |
| Ireland     | 1         | 1.04%   |
| Ecuador     | 1         | 1.04%   |
| Costa Rica  | 1         | 1.04%   |
| Belarus     | 1         | 1.04%   |
| Austria     | 1         | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Moscow              | 3         | 3.13%   |
| Oruro               | 2         | 2.08%   |
| Neasden             | 2         | 2.08%   |
| Zaragoza            | 1         | 1.04%   |
| Wroclaw             | 1         | 1.04%   |
| Voronezh            | 1         | 1.04%   |
| Vilshofen           | 1         | 1.04%   |
| Vilnius             | 1         | 1.04%   |
| Viet Tri            | 1         | 1.04%   |
| Veurne              | 1         | 1.04%   |
| Vaslui              | 1         | 1.04%   |
| Valsoyfjord         | 1         | 1.04%   |
| Uiwang              | 1         | 1.04%   |
| Tula                | 1         | 1.04%   |
| Troisdorf           | 1         | 1.04%   |
| Toulouse            | 1         | 1.04%   |
| Toronto             | 1         | 1.04%   |
| Tipton              | 1         | 1.04%   |
| Spearfish           | 1         | 1.04%   |
| Smolensk            | 1         | 1.04%   |
| Scarborough         | 1         | 1.04%   |
| Saratov             | 1         | 1.04%   |
| Sao Paulo           | 1         | 1.04%   |
| Santiago            | 1         | 1.04%   |
| San Jose            | 1         | 1.04%   |
| Rottenburg          | 1         | 1.04%   |
| Rochester           | 1         | 1.04%   |
| Recife              | 1         | 1.04%   |
| Providencia         | 1         | 1.04%   |
| Petaling Jaya       | 1         | 1.04%   |
| Ordonnac            | 1         | 1.04%   |
| Nuremberg           | 1         | 1.04%   |
| Nairobi             | 1         | 1.04%   |
| Murphy              | 1         | 1.04%   |
| Mosonmagyaróvár   | 1         | 1.04%   |
| Monaca              | 1         | 1.04%   |
| Minsk               | 1         | 1.04%   |
| Mieuxce             | 1         | 1.04%   |
| Mexico City         | 1         | 1.04%   |
| Marrero             | 1         | 1.04%   |
| Mannheim            | 1         | 1.04%   |
| Mammoth Lakes       | 1         | 1.04%   |
| Málaga             | 1         | 1.04%   |
| Londonderry         | 1         | 1.04%   |
| London              | 1         | 1.04%   |
| Lisbon              | 1         | 1.04%   |
| Limoges             | 1         | 1.04%   |
| Limburg an der Lahn | 1         | 1.04%   |
| Lima                | 1         | 1.04%   |
| Lebanon             | 1         | 1.04%   |
| Lawrenceville       | 1         | 1.04%   |
| La Flotte           | 1         | 1.04%   |
| Krefeld             | 1         | 1.04%   |
| Krakow              | 1         | 1.04%   |
| Knurow              | 1         | 1.04%   |
| Katowice            | 1         | 1.04%   |
| Kansas City         | 1         | 1.04%   |
| Ivanovo             | 1         | 1.04%   |
| Huntingdon          | 1         | 1.04%   |
| Hollister           | 1         | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 16        | 18     | 13.56%  |
| Samsung Electronics            | 12        | 13     | 10.17%  |
| Unknown                        | 9         | 13     | 7.63%   |
| Seagate                        | 9         | 9      | 7.63%   |
| SanDisk                        | 8         | 8      | 6.78%   |
| Toshiba                        | 6         | 7      | 5.08%   |
| Hitachi                        | 6         | 6      | 5.08%   |
| Kingston                       | 5         | 5      | 4.24%   |
| Intel                          | 5         | 5      | 4.24%   |
| Apple                          | 4         | 9      | 3.39%   |
| PNY                            | 3         | 3      | 2.54%   |
| Patriot                        | 3         | 3      | 2.54%   |
| Team                           | 2         | 2      | 1.69%   |
| Phison                         | 2         | 2      | 1.69%   |
| Micron Technology              | 2         | 2      | 1.69%   |
| KingSpec                       | 2         | 2      | 1.69%   |
| HGST                           | 2         | 2      | 1.69%   |
| A-DATA Technology              | 2         | 2      | 1.69%   |
| SSD PHIS                       | 1         | 1      | 0.85%   |
| Solid State Storage Technology | 1         | 1      | 0.85%   |
| SK hynix                       | 1         | 1      | 0.85%   |
| ShiJi                          | 1         | 1      | 0.85%   |
| SABRENT                        | 1         | 1      | 0.85%   |
| Oyen                           | 1         | 1      | 0.85%   |
| ORICO                          | 1         | 1      | 0.85%   |
| Microtech                      | 1         | 2      | 0.85%   |
| Micron/Crucial Technology      | 1         | 2      | 0.85%   |
| LITEON                         | 1         | 1      | 0.85%   |
| KIOXIA                         | 1         | 4      | 0.85%   |
| Initio                         | 1         | 1      | 0.85%   |
| HXY                            | 1         | 1      | 0.85%   |
| Fujitsu                        | 1         | 1      | 0.85%   |
| FORESEE                        | 1         | 1      | 0.85%   |
| Crucial                        | 1         | 1      | 0.85%   |
| China                          | 1         | 2      | 0.85%   |
| BHT                            | 1         | 2      | 0.85%   |
| Acer                           | 1         | 1      | 0.85%   |
| Unknown                        | 1         | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 128GB              | 3         | 2.46%   |
| SanDisk NVMe SSD Drive 256GB             | 3         | 2.46%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 2         | 1.64%   |
| WDC WD3200BEVT-60ZCT1 320GB              | 2         | 1.64%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB     | 2         | 1.64%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 1.64%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 1.64%   |
| Samsung PM991a NVMe 512GB                | 2         | 1.64%   |
| Patriot Burst 240GB SSD                  | 2         | 1.64%   |
| Micron NVMe SSD Drive 512GB              | 2         | 1.64%   |
| Kingston SA400S37120G 120GB SSD          | 2         | 1.64%   |
| Apple SSD SD0128F 121GB                  | 2         | 1.64%   |
| WDC WDS100T3X0C-00SJG0 1TB               | 1         | 0.82%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 0.82%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 0.82%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 0.82%   |
| WDC WD5000BEVT-22A0RT0 500GB             | 1         | 0.82%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 0.82%   |
| WDC WD30 EFRX-68EUZN0 3TB                | 1         | 0.82%   |
| WDC WD10SPZX-60Z10T1 1TB                 | 1         | 0.82%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 0.82%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB     | 1         | 0.82%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 0.82%   |
| Unknown USB DISK 3.2 1TB                 | 1         | 0.82%   |
| Unknown SP32G  32GB                      | 1         | 0.82%   |
| Unknown SC128  128GB                     | 1         | 0.82%   |
| Unknown MMC Card  64GB                   | 1         | 0.82%   |
| Unknown MMC Card  32GB                   | 1         | 0.82%   |
| Unknown Biwin  64GB                      | 1         | 0.82%   |
| Unknown Biwin  32GB                      | 1         | 0.82%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 0.82%   |
| Toshiba MQ01ABF032 320GB                 | 1         | 0.82%   |
| Toshiba MK3252GSX 320GB                  | 1         | 0.82%   |
| Toshiba KBG40ZNT256G MEMORY 256GB        | 1         | 0.82%   |
| Team TM8PS7256G 256GB SSD                | 1         | 0.82%   |
| Team T253X6512G 512GB SSD                | 1         | 0.82%   |
| SSD PHIS ON 256GB PS3110 SSD             | 1         | 0.82%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 0.82%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 0.82%   |
| ShiJi 256GB                              | 1         | 0.82%   |
| Seagate ST9250315AS 250GB                | 1         | 0.82%   |
| Seagate ST9160412ASG 160GB               | 1         | 0.82%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 0.82%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 0.82%   |
| SanDisk SSD PLUS 480GB                   | 1         | 0.82%   |
| SanDisk SDSSDA240G 240GB                 | 1         | 0.82%   |
| SanDisk NVMe SSD Drive 2TB               | 1         | 0.82%   |
| SanDisk NVMe SSD Drive 1024GB            | 1         | 0.82%   |
| SanDisk DF4064  64GB                     | 1         | 0.82%   |
| Samsung SSD 980 PRO 1TB                  | 1         | 0.82%   |
| Samsung SSD 980 1TB                      | 1         | 0.82%   |
| Samsung SSD 970 EVO Plus 1TB             | 1         | 0.82%   |
| Samsung SSD 870 QVO 8TB                  | 1         | 0.82%   |
| Samsung SSD 860 EVO 1TB                  | 1         | 0.82%   |
| Samsung SSD 850 EVO 500GB                | 1         | 0.82%   |
| Samsung SSD 850 EVO 120GB                | 1         | 0.82%   |
| Samsung SSD 840 EVO 250GB                | 1         | 0.82%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 11     | 27.03%  |
| Seagate | 9         | 9      | 24.32%  |
| Hitachi | 6         | 6      | 16.22%  |
| Toshiba | 5         | 6      | 13.51%  |
| Unknown | 3         | 3      | 8.11%   |
| HGST    | 2         | 2      | 5.41%   |
| SABRENT | 1         | 1      | 2.7%    |
| Fujitsu | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 12.2%   |
| Kingston            | 4         | 4      | 9.76%   |
| PNY                 | 3         | 3      | 7.32%   |
| Patriot             | 3         | 3      | 7.32%   |
| Intel               | 3         | 3      | 7.32%   |
| Apple               | 3         | 3      | 7.32%   |
| Team                | 2         | 2      | 4.88%   |
| SanDisk             | 2         | 2      | 4.88%   |
| KingSpec            | 2         | 2      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| WDC                 | 1         | 1      | 2.44%   |
| SSD PHIS            | 1         | 1      | 2.44%   |
| ORICO               | 1         | 1      | 2.44%   |
| Microtech           | 1         | 2      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| HXY                 | 1         | 1      | 2.44%   |
| FORESEE             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| China               | 1         | 2      | 2.44%   |
| BHT                 | 1         | 2      | 2.44%   |
| Acer                | 1         | 1      | 2.44%   |
| Unknown             | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 38        | 45     | 34.86%  |
| HDD     | 34        | 39     | 31.19%  |
| NVMe    | 27        | 40     | 24.77%  |
| MMC     | 6         | 9      | 5.5%    |
| Unknown | 4         | 5      | 3.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 65        | 78     | 61.9%   |
| NVMe | 27        | 40     | 25.71%  |
| SAS  | 7         | 11     | 6.67%   |
| MMC  | 6         | 9      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 61     | 69.86%  |
| 0.51-1.0   | 19        | 20     | 26.03%  |
| 2.01-3.0   | 1         | 1      | 1.37%   |
| 1.01-2.0   | 1         | 1      | 1.37%   |
| 4.01-10.0  | 1         | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 35.79%  |
| 251-500        | 22        | 23.16%  |
| 501-1000       | 11        | 11.58%  |
| 51-100         | 8         | 8.42%   |
| 21-50          | 7         | 7.37%   |
| 1001-2000      | 6         | 6.32%   |
| 1-20           | 5         | 5.26%   |
| More than 3000 | 1         | 1.05%   |
| 2001-3000      | 1         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 50        | 51.02%  |
| 21-50     | 19        | 19.39%  |
| 51-100    | 12        | 12.24%  |
| 101-250   | 8         | 8.16%   |
| 251-500   | 5         | 5.1%    |
| 501-1000  | 3         | 3.06%   |
| 2001-3000 | 1         | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB   | 1         | 1      | 16.67%  |
| WDC WD3200BEVT-60ZCT1 320GB    | 1         | 1      | 16.67%  |
| Phison ES 512GB                | 1         | 1      | 16.67%  |
| Intel SSDSCKKF256G8 SATA 256GB | 1         | 1      | 16.67%  |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 16.67%  |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 20%     |
| Phison  | 1         | 1      | 20%     |
| Intel   | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 60%     |
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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 60        | 84     | 58.25%  |
| Works    | 38        | 48     | 36.89%  |
| Malfunc  | 5         | 6      | 4.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 62        | 55.86%  |
| AMD                            | 18        | 16.22%  |
| SanDisk                        | 9         | 8.11%   |
| Samsung Electronics            | 8         | 7.21%   |
| Phison Electronics             | 2         | 1.8%    |
| Micron Technology              | 2         | 1.8%    |
| Marvell Technology Group       | 2         | 1.8%    |
| KIOXIA                         | 2         | 1.8%    |
| Toshiba America Info Systems   | 1         | 0.9%    |
| Solid State Storage Technology | 1         | 0.9%    |
| SK hynix                       | 1         | 0.9%    |
| Micron/Crucial Technology      | 1         | 0.9%    |
| Kingston Technology Company    | 1         | 0.9%    |
| Apple                          | 1         | 0.9%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 13.68%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 5.13%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 4.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 4.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 4.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 3.42%   |
| SanDisk Non-Volatile memory controller                                           | 4         | 3.42%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 3.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 3.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 3.42%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.56%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 1.71%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.71%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 1.71%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.85%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.85%   |
| SK hynix BC511                                                                   | 1         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.85%   |
| Samsung Electronics SATA controller                                              | 1         | 0.85%   |
| Micron/Crucial NVMe Controller                                                   | 1         | 0.85%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.85%   |
| Intel SSD 660P Series                                                            | 1         | 0.85%   |
| Intel SSD 600P Series                                                            | 1         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.85%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.85%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.85%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.85%   |
| Apple S3X NVMe Controller                                                        | 1         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.85%   |
| AMD IXP SB4x0 Serial ATA Controller                                              | 1         | 0.85%   |
| AMD IXP SB4x0 IDE Controller                                                     | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 67        | 58.77%  |
| NVMe | 28        | 24.56%  |
| RAID | 12        | 10.53%  |
| IDE  | 7         | 6.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 75.53%  |
| AMD    | 23        | 24.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 4.26%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 4.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 3.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 3.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 2.13%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 2.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 2.13%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 2.13%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.06%   |
| Intel Pentium M processor 1.73GHz           | 1         | 1.06%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.06%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 1.06%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.06%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 1.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.06%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.06%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.06%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.06%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.06%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.06%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 1.06%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.06%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.06%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.06%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 1.06%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.06%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.06%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 1.06%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.06%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.06%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 1.06%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.06%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 1.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.06%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.06%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.06%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.06%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 1.06%   |
| Intel Core 2 Extreme CPU X9100 @ 3.06GHz    | 1         | 1.06%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.06%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz        | 1         | 1.06%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 1         | 1.06%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.06%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.06%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz        | 1         | 1.06%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.06%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.06%   |
| Intel Celeron M CPU 520 @ 1.60GHz           | 1         | 1.06%   |
| Intel Celeron M CPU 440 @ 1.86GHz           | 1         | 1.06%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.06%   |
| Intel Celeron CPU N2815 @ 1.86GHz           | 1         | 1.06%   |
| Intel Celeron 2955U @ 1.40GHz               | 1         | 1.06%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.06%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 18.09%  |
| Other                   | 10        | 10.64%  |
| Intel Core i7           | 9         | 9.57%   |
| Intel Core i3           | 9         | 9.57%   |
| Intel Atom              | 7         | 7.45%   |
| Intel Core 2 Duo        | 6         | 6.38%   |
| AMD Ryzen 5             | 6         | 6.38%   |
| Intel Celeron           | 5         | 5.32%   |
| AMD Ryzen 7             | 4         | 4.26%   |
| Intel Pentium           | 3         | 3.19%   |
| Intel Celeron M         | 2         | 2.13%   |
| AMD Ryzen 3             | 2         | 2.13%   |
| AMD E2                  | 2         | 2.13%   |
| AMD E1                  | 2         | 2.13%   |
| Intel Pentium Silver    | 1         | 1.06%   |
| Intel Pentium M         | 1         | 1.06%   |
| Intel Pentium Dual-Core | 1         | 1.06%   |
| Intel Core 2 Extreme    | 1         | 1.06%   |
| AMD Ryzen 9             | 1         | 1.06%   |
| AMD C-50                | 1         | 1.06%   |
| AMD Athlon              | 1         | 1.06%   |
| AMD A6                  | 1         | 1.06%   |
| AMD A4                  | 1         | 1.06%   |
| AMD A10                 | 1         | 1.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 60.64%  |
| 4      | 21        | 22.34%  |
| 8      | 6         | 6.38%   |
| 6      | 5         | 5.32%   |
| 1      | 5         | 5.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 68.09%  |
| 1      | 30        | 31.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 90        | 95.74%  |
| 32-bit         | 4         | 4.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 8         | 8.42%   |
| 0x40651    | 7         | 7.37%   |
| 0x08608103 | 6         | 6.32%   |
| 0x306a9    | 5         | 5.26%   |
| 0x806ec    | 4         | 4.21%   |
| 0x406e3    | 4         | 4.21%   |
| 0x30661    | 4         | 4.21%   |
| 0x08108109 | 4         | 4.21%   |
| 0x806e9    | 3         | 3.16%   |
| 0x6fd      | 3         | 3.16%   |
| 0x1067a    | 3         | 3.16%   |
| Unknown    | 3         | 3.16%   |
| 0x706e5    | 2         | 2.11%   |
| 0x706a1    | 2         | 2.11%   |
| 0x406c4    | 2         | 2.11%   |
| 0x306c3    | 2         | 2.11%   |
| 0x20652    | 2         | 2.11%   |
| 0x10676    | 2         | 2.11%   |
| 0x06006705 | 2         | 2.11%   |
| 0xa0652    | 1         | 1.05%   |
| 0x906ea    | 1         | 1.05%   |
| 0x806ea    | 1         | 1.05%   |
| 0x806d1    | 1         | 1.05%   |
| 0x706a8    | 1         | 1.05%   |
| 0x6f6      | 1         | 1.05%   |
| 0x6ec      | 1         | 1.05%   |
| 0x6d8      | 1         | 1.05%   |
| 0x506e3    | 1         | 1.05%   |
| 0x506c9    | 1         | 1.05%   |
| 0x306d4    | 1         | 1.05%   |
| 0x30673    | 1         | 1.05%   |
| 0x206a7    | 1         | 1.05%   |
| 0x20655    | 1         | 1.05%   |
| 0x106e5    | 1         | 1.05%   |
| 0x106ca    | 1         | 1.05%   |
| 0x106c2    | 1         | 1.05%   |
| 0x0a50000c | 1         | 1.05%   |
| 0x08600103 | 1         | 1.05%   |
| 0x08108102 | 1         | 1.05%   |
| 0x07030106 | 1         | 1.05%   |
| 0x07030105 | 1         | 1.05%   |
| 0x07000110 | 1         | 1.05%   |
| 0x0700010f | 1         | 1.05%   |
| 0x06006704 | 1         | 1.05%   |
| 0x0600611a | 1         | 1.05%   |
| 0x05000029 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 9.47%   |
| Haswell       | 9         | 9.47%   |
| TigerLake     | 8         | 8.42%   |
| Unknown       | 7         | 7.37%   |
| Bonnell       | 6         | 6.32%   |
| Zen+          | 5         | 5.26%   |
| Skylake       | 5         | 5.26%   |
| Penryn        | 5         | 5.26%   |
| IvyBridge     | 5         | 5.26%   |
| Excavator     | 4         | 4.21%   |
| Core          | 4         | 4.21%   |
| Westmere      | 3         | 3.16%   |
| Silvermont    | 3         | 3.16%   |
| IceLake       | 3         | 3.16%   |
| Goldmont plus | 3         | 3.16%   |
| Zen 3         | 2         | 2.11%   |
| Puma          | 2         | 2.11%   |
| P6            | 2         | 2.11%   |
| Jaguar        | 2         | 2.11%   |
| Broadwell     | 2         | 2.11%   |
| Zen 2         | 1         | 1.05%   |
| SandyBridge   | 1         | 1.05%   |
| Nehalem       | 1         | 1.05%   |
| Goldmont      | 1         | 1.05%   |
| CometLake     | 1         | 1.05%   |
| Bobcat        | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 59.05%  |
| AMD    | 27        | 25.71%  |
| Nvidia | 16        | 15.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 6.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 5.5%    |
| AMD Lucienne                                                                             | 6         | 5.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 4.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 3.67%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 3.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.75%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 1.83%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.83%   |
| Intel HD Graphics 620                                                                    | 2         | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.83%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.92%   |
| Nvidia GT216M [GeForce GT 325M]                                                          | 1         | 0.92%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.92%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.92%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.92%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.92%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.92%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                          | 1         | 0.92%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.92%   |
| Nvidia G94GLM [Quadro FX 2700M]                                                          | 1         | 0.92%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.92%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.92%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.92%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.92%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.92%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.92%   |
| Intel HD Graphics 530                                                                    | 1         | 0.92%   |
| Intel HD Graphics 500                                                                    | 1         | 0.92%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.92%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 0.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.92%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.92%   |
| AMD Renoir                                                                               | 1         | 0.92%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 1         | 0.92%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 0.92%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 55.32%  |
| 1 x AMD        | 23        | 24.47%  |
| Intel + Nvidia | 8         | 8.51%   |
| 1 x Nvidia     | 7         | 7.45%   |
| Intel + AMD    | 2         | 2.13%   |
| 2 x AMD        | 1         | 1.06%   |
| AMD + Nvidia   | 1         | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 95.79%  |
| Proprietary | 3         | 3.16%   |
| Unknown     | 1         | 1.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 57.89%  |
| 0.01-0.5   | 21        | 22.11%  |
| 1.01-2.0   | 10        | 10.53%  |
| 0.51-1.0   | 4         | 4.21%   |
| 3.01-4.0   | 3         | 3.16%   |
| 5.01-6.0   | 2         | 2.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 24.24%  |
| BOE                     | 17        | 17.17%  |
| Chimei Innolux          | 15        | 15.15%  |
| LG Display              | 12        | 12.12%  |
| Samsung Electronics     | 5         | 5.05%   |
| Apple                   | 4         | 4.04%   |
| LG Philips              | 3         | 3.03%   |
| InfoVision              | 3         | 3.03%   |
| Sharp                   | 2         | 2.02%   |
| PANDA                   | 2         | 2.02%   |
| HannStar                | 2         | 2.02%   |
| Dell                    | 2         | 2.02%   |
| TR_                     | 1         | 1.01%   |
| Quanta Display          | 1         | 1.01%   |
| Planar                  | 1         | 1.01%   |
| Lenovo                  | 1         | 1.01%   |
| Insignia                | 1         | 1.01%   |
| Goldstar                | 1         | 1.01%   |
| DENON                   | 1         | 1.01%   |
| Chi Mei Optoelectronics | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 3%      |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 2%      |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 2%      |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 2%      |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 2%      |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 1%      |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 1%      |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                  | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 1%      |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 1%      |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 1%      |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 1%      |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 1%      |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 1%      |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD0226 1600x900 382x215mm 17.3-inch              | 1         | 1%      |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch                  | 1         | 1%      |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch             | 1         | 1%      |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch             | 1         | 1%      |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1%      |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 1%      |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                    | 1         | 1%      |
| DENON AVR DON005F 1920x1080                                              | 1         | 1%      |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1         | 1%      |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 1%      |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN1731 1600x900 382x215mm 17.3-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch         | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1%      |
| Chimei Innolux LCD Monitor CMN1375 1920x1080 293x165mm 13.2-inch         | 1         | 1%      |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 1         | 1%      |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1%      |
| BOE LCD Monitor BOE08E8 1920x1080 340x190mm 15.3-inch                    | 1         | 1%      |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                     | 1         | 1%      |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 1         | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 42.71%  |
| 1366x768 (WXGA)   | 25        | 26.04%  |
| 1920x1200 (WUXGA) | 6         | 6.25%   |
| 1600x900 (HD+)    | 5         | 5.21%   |
| 1440x900 (WXGA+)  | 4         | 4.17%   |
| 1024x600          | 4         | 4.17%   |
| 1280x800 (WXGA)   | 3         | 3.13%   |
| 3840x2160 (4K)    | 2         | 2.08%   |
| 2880x1800         | 1         | 1.04%   |
| 2560x1600         | 1         | 1.04%   |
| 2560x1440 (QHD)   | 1         | 1.04%   |
| 2256x1504         | 1         | 1.04%   |
| 1280x768          | 1         | 1.04%   |
| 1280x720 (HD)     | 1         | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 42        | 42%     |
| 13      | 19        | 19%     |
| 14      | 14        | 14%     |
| 17      | 8         | 8%      |
| 10      | 4         | 4%      |
| 27      | 3         | 3%      |
| 24      | 2         | 2%      |
| 21      | 2         | 2%      |
| 72      | 1         | 1%      |
| 31      | 1         | 1%      |
| 16      | 1         | 1%      |
| 11      | 1         | 1%      |
| 8       | 1         | 1%      |
| Unknown | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 64.65%  |
| 201-300     | 15        | 15.15%  |
| 351-400     | 10        | 10.1%   |
| 501-600     | 4         | 4.04%   |
| 401-500     | 2         | 2.02%   |
| 601-700     | 1         | 1.01%   |
| 1501-2000   | 1         | 1.01%   |
| 101-200     | 1         | 1.01%   |
| Unknown     | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 77        | 82.8%   |
| 16/10   | 14        | 15.05%  |
| 3/2     | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 42%     |
| 81-90          | 24        | 24%     |
| 71-80          | 9         | 9%      |
| 121-130        | 5         | 5%      |
| 41-50          | 4         | 4%      |
| 301-350        | 3         | 3%      |
| 131-140        | 3         | 3%      |
| 251-300        | 2         | 2%      |
| 201-250        | 2         | 2%      |
| More than 1000 | 1         | 1%      |
| 51-60          | 1         | 1%      |
| 351-500        | 1         | 1%      |
| 1-40           | 1         | 1%      |
| 91-100         | 1         | 1%      |
| Unknown        | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 44%     |
| 101-120       | 36        | 36%     |
| 51-100        | 10        | 10%     |
| 161-240       | 7         | 7%      |
| More than 240 | 1         | 1%      |
| 1-50          | 1         | 1%      |
| Unknown       | 1         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 87        | 91.58%  |
| 2     | 6         | 6.32%   |
| 3     | 1         | 1.05%   |
| 0     | 1         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 52        | 37.14%  |
| Intel                         | 39        | 27.86%  |
| Qualcomm Atheros              | 23        | 16.43%  |
| Broadcom                      | 11        | 7.86%   |
| Broadcom Limited              | 3         | 2.14%   |
| Ralink Technology             | 2         | 1.43%   |
| Marvell Technology Group      | 2         | 1.43%   |
| Xiaomi                        | 1         | 0.71%   |
| TP-Link                       | 1         | 0.71%   |
| Ralink                        | 1         | 0.71%   |
| OnePlus Technology (Shenzhen) | 1         | 0.71%   |
| JMicron Technology            | 1         | 0.71%   |
| Google                        | 1         | 0.71%   |
| Dell                          | 1         | 0.71%   |
| Davicom Semiconductor         | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 12.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 6.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 3.43%   |
| Intel Wireless 3165                                               | 5         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 2.29%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 2.29%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.29%   |
| Intel Wireless 7260                                               | 3         | 1.71%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.71%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.71%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 1.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.14%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.14%   |
| Intel WiFi Link 5100                                              | 2         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.14%   |
| Broadcom BCM43225 802.11b/g/n                                     | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.57%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.57%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.57%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.57%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.57%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.57%   |
| Realtek 802.11ac NIC                                              | 1         | 0.57%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.57%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1         | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.57%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.57%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.57%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.57%   |
| Intel Wireless 8260                                               | 1         | 0.57%   |
| Intel Wireless 7265                                               | 1         | 0.57%   |
| Intel Wireless 3160                                               | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 38.14%  |
| Realtek Semiconductor | 26        | 26.8%   |
| Qualcomm Atheros      | 18        | 18.56%  |
| Broadcom              | 9         | 9.28%   |
| Broadcom Limited      | 3         | 3.09%   |
| Ralink Technology     | 2         | 2.06%   |
| TP-Link               | 1         | 1.03%   |
| Ralink                | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 10%     |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 6%      |
| Intel Wireless 3165                                            | 5         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 4%      |
| Intel Wireless 8265 / 8275                                     | 4         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 4%      |
| Intel Wireless 7260                                            | 3         | 3%      |
| Intel Wi-Fi 6 AX201                                            | 3         | 3%      |
| Intel Wi-Fi 6 AX200                                            | 3         | 3%      |
| Intel Ultimate N WiFi Link 5300                                | 3         | 3%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 3%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 2%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 2%      |
| Intel WiFi Link 5100                                           | 2         | 2%      |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 2%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1%      |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1%      |
| Realtek RTL8187B Wireless Adapter                              | 1         | 1%      |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1%      |
| Realtek 802.11ac NIC                                           | 1         | 1%      |
| Ralink RT5372 Wireless Adapter                                 | 1         | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1%      |
| Ralink RT2561/RT61 rev B 802.11g                               | 1         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1%      |
| Intel Wireless 8260                                            | 1         | 1%      |
| Intel Wireless 7265                                            | 1         | 1%      |
| Intel Wireless 3160                                            | 1         | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 1         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1%      |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 1%      |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1%      |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 39        | 53.42%  |
| Intel                         | 16        | 21.92%  |
| Qualcomm Atheros              | 9         | 12.33%  |
| Marvell Technology Group      | 2         | 2.74%   |
| Broadcom                      | 2         | 2.74%   |
| Xiaomi                        | 1         | 1.37%   |
| OnePlus Technology (Shenzhen) | 1         | 1.37%   |
| JMicron Technology            | 1         | 1.37%   |
| Google                        | 1         | 1.37%   |
| Davicom Semiconductor         | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 30.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 16.44%  |
| Intel 82567LM Gigabit Network Connection                          | 4         | 5.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.74%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 2.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.74%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.37%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 1.37%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.37%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.37%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.37%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.37%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.37%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.37%   |
| Davicom DM9621A USB To FastEther                                  | 1         | 1.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 56.1%   |
| Ethernet | 70        | 42.68%  |
| Modem    | 2         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 77.89%  |
| Ethernet | 21        | 22.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 64        | 68.09%  |
| 1     | 26        | 27.66%  |
| 0     | 4         | 4.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 69.15%  |
| Yes  | 29        | 30.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 43.28%  |
| Realtek Semiconductor           | 16        | 23.88%  |
| Qualcomm Atheros Communications | 4         | 5.97%   |
| Foxconn / Hon Hai               | 4         | 5.97%   |
| Dell                            | 3         | 4.48%   |
| Apple                           | 3         | 4.48%   |
| Lite-On Technology              | 2         | 2.99%   |
| Hewlett-Packard                 | 2         | 2.99%   |
| Broadcom                        | 2         | 2.99%   |
| IMC Networks                    | 1         | 1.49%   |
| Foxconn International           | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 14        | 20.9%   |
| Realtek Bluetooth Radio                           | 10        | 14.93%  |
| Intel AX201 Bluetooth                             | 7         | 10.45%  |
| Realtek  Bluetooth 4.2 Adapter                    | 5         | 7.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 5.97%   |
| Intel AX200 Bluetooth                             | 3         | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                | 2         | 2.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 2.99%   |
| Dell Wireless 370 Bluetooth Mini-card             | 2         | 2.99%   |
| Apple Bluetooth USB Host Controller               | 2         | 2.99%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.49%   |
| Intel AX210 Bluetooth                             | 1         | 1.49%   |
| IMC Networks Bluetooth Device                     | 1         | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.49%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 1.49%   |
| Foxconn / Hon Hai Acer Module                     | 1         | 1.49%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 1         | 1.49%   |
| Dell BCM20702A0 Bluetooth Module                  | 1         | 1.49%   |
| Broadcom HP Portable SoftSailing                  | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]  | 1         | 1.49%   |
| Apple Bluetooth Host Controller                   | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 69        | 63.3%   |
| AMD                   | 27        | 24.77%  |
| Nvidia                | 7         | 6.42%   |
| Texas Instruments     | 2         | 1.83%   |
| Yamaha                | 1         | 0.92%   |
| Realtek Semiconductor | 1         | 0.92%   |
| GN Netcom             | 1         | 0.92%   |
| Audioengine           | 1         | 0.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 9.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 5.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 5.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 4.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 4.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.93%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 4.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 3.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.82%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.11%   |
| AMD High Definition Audio Controller                                                              | 3         | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.41%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.41%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.7%    |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.7%    |
| Texas Instruments PCM2702 16-bit stereo audio DAC                                                 | 1         | 0.7%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.7%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia Audio device                                                                               | 1         | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.7%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.7%    |
| GN Netcom Jabra EVOLVE 20 MS                                                                      | 1         | 0.7%    |
| Audioengine D1 24-bit DAC                                                                         | 1         | 0.7%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.7%    |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 13        | 30.23%  |
| SK hynix                     | 10        | 23.26%  |
| Unknown                      | 4         | 9.3%    |
| Micron Technology            | 3         | 6.98%   |
| Unknown (ABCD)               | 2         | 4.65%   |
| Nanya Technology             | 2         | 4.65%   |
| Kingston                     | 2         | 4.65%   |
| A-DATA Technology            | 2         | 4.65%   |
| Ramaxel Technology           | 1         | 2.33%   |
| Patriot Memory (PDP Systems) | 1         | 2.33%   |
| Crucial                      | 1         | 2.33%   |
| Corsair                      | 1         | 2.33%   |
| Unknown                      | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s      | 2         | 4.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 4.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 2         | 4.44%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                              | 1         | 2.22%   |
| Unknown RAM Module 512MB SODIMM DDR                                      | 1         | 2.22%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                              | 1         | 2.22%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR                                        | 1         | 2.22%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                            | 1         | 2.22%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                             | 1         | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                   | 1         | 2.22%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 2.22%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                    | 1         | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.22%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                    | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s              | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 1         | 2.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.22%   |
| Ramaxel RAM RMSA3330MJ78HBF-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 2.22%   |
| Patriot Memory (PDP Systems) RAM PSD432G32002S 32GB SODIMM DDR4 3200MT/s | 1         | 2.22%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s                     | 1         | 2.22%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s                     | 1         | 2.22%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.22%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G3A1 4GB SODIMM DDR4 2400MT/s                    | 1         | 2.22%   |
| Kingston RAM MSI26D4S9D8ME-16 16GB SODIMM DDR4 2667MT/s                  | 1         | 2.22%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s                      | 1         | 2.22%   |
| Crucial RAM CT8G4SFD8213.C16FBR2 8GB SODIMM DDR4 2267MT/s                | 1         | 2.22%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s                | 1         | 2.22%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                               | 1         | 2.22%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s                  | 1         | 2.22%   |
| Unknown                                                                  | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 53.66%  |
| DDR3   | 13        | 31.71%  |
| LPDDR4 | 3         | 7.32%   |
| SDRAM  | 2         | 4.88%   |
| DDR    | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 95.24%  |
| Row Of Chips | 2         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 36.36%  |
| 4096  | 14        | 31.82%  |
| 2048  | 7         | 15.91%  |
| 16384 | 3         | 6.82%   |
| 32768 | 2         | 4.55%   |
| 1024  | 1         | 2.27%   |
| 512   | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 14        | 33.33%  |
| 1600    | 12        | 28.57%  |
| 2400    | 5         | 11.9%   |
| 2667    | 4         | 9.52%   |
| 4267    | 1         | 2.38%   |
| 4199    | 1         | 2.38%   |
| 2267    | 1         | 2.38%   |
| 2048    | 1         | 2.38%   |
| 1334    | 1         | 2.38%   |
| 1200    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

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
| Chicony Electronics                    | 15        | 18.99%  |
| Microdia                               | 11        | 13.92%  |
| Suyin                                  | 8         | 10.13%  |
| IMC Networks                           | 8         | 10.13%  |
| Sunplus Innovation Technology          | 6         | 7.59%   |
| Realtek Semiconductor                  | 6         | 7.59%   |
| Quanta                                 | 6         | 7.59%   |
| Acer                                   | 6         | 7.59%   |
| Alcor Micro                            | 3         | 3.8%    |
| Luxvisions Innotech Limited            | 2         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.53%   |
| Lite-On Technology                     | 1         | 1.27%   |
| Lenovo                                 | 1         | 1.27%   |
| Intel                                  | 1         | 1.27%   |
| icSpring                               | 1         | 1.27%   |
| Apple                                  | 1         | 1.27%   |
| ALi                                    | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 9         | 11.39%  |
| Chicony Integrated Camera                                      | 5         | 6.33%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 3.8%    |
| Chicony HP TrueVision HD Camera                                | 3         | 3.8%    |
| Acer Integrated Camera                                         | 3         | 3.8%    |
| Suyin HP TrueVision HD                                         | 2         | 2.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 2         | 2.53%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 2.53%   |
| IMC Networks Integrated Camera                                 | 2         | 2.53%   |
| Chicony HD Webcam                                              | 2         | 2.53%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 2.53%   |
| Acer USB2.0 Camera                                             | 2         | 2.53%   |
| Suyin HP Webcam-101                                            | 1         | 1.27%   |
| Suyin HD WebCam                                                | 1         | 1.27%   |
| Suyin HD Video WebCam                                          | 1         | 1.27%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 1.27%   |
| Suyin Acer CrystalEye Webcam                                   | 1         | 1.27%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.27%   |
| Sunplus MTD Camera                                             | 1         | 1.27%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 1.27%   |
| Sunplus HP TrueVision HD Camera                                | 1         | 1.27%   |
| Sunplus HD WebCam                                              | 1         | 1.27%   |
| Sunplus 5Mega Webcam                                           | 1         | 1.27%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 1.27%   |
| Realtek USB2.0 camera                                          | 1         | 1.27%   |
| Realtek Lenovo EasyCamera                                      | 1         | 1.27%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.27%   |
| Realtek HP Truevision HD integrated webcam                     | 1         | 1.27%   |
| Realtek HP Truevision HD                                       | 1         | 1.27%   |
| Realtek HP "Truevision HD" laptop camera                       | 1         | 1.27%   |
| Quanta VGA WebCam                                              | 1         | 1.27%   |
| Quanta HP Webcam                                               | 1         | 1.27%   |
| Quanta HP HD Camera                                            | 1         | 1.27%   |
| Microdia Lenovo EasyCamera                                     | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 1         | 1.27%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.27%   |
| Luxvisions Innotech Limited HP HD Camera                       | 1         | 1.27%   |
| Lite-On HP TrueVision HD Camera                                | 1         | 1.27%   |
| Lenovo Integrated Webcam                                       | 1         | 1.27%   |
| Intel RealSense 3D Camera (Front F200)                         | 1         | 1.27%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.27%   |
| IMC Networks 2M Integrated Webcam                              | 1         | 1.27%   |
| icSpring camera                                                | 1         | 1.27%   |
| Chicony USB2.0 Camera                                          | 1         | 1.27%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.27%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 1.27%   |
| Chicony CKA7216                                                | 1         | 1.27%   |
| Chicony 1.3M Webcam                                            | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 1         | 1.27%   |
| ALi Gateway Webcam                                             | 1         | 1.27%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 1.27%   |
| Acer HD Webcam                                                 | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 54.55%  |
| Synaptics                  | 1         | 9.09%   |
| STMicroelectronics         | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Focal-systems.Corp         | 1         | 9.09%   |
| Elan Microelectronics      | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 18.18%  |
| Validity Sensors Synaptics WBDI            | 2         | 18.18%  |
| Validity Sensors VFS491                    | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader      | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 9.09%   |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 9.09%   |
| Elan ELAN:Fingerprint                      | 1         | 9.09%   |
| Unknown                                    | 1         | 9.09%   |

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
| 0     | 61        | 63.54%  |
| 1     | 31        | 32.29%  |
| 2     | 3         | 3.13%   |
| 3     | 1         | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 25%     |
| Net/wireless          | 9         | 22.5%   |
| Multimedia controller | 9         | 22.5%   |
| Chipcard              | 6         | 15%     |
| Graphics card         | 5         | 12.5%   |
| Dvb card              | 1         | 2.5%    |

