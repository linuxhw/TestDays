Fedora 38 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_38/Desktop/README.md) and [notebooks](/Dist/Fedora_38/Notebook/README.md).

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

Total: 1538

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | LIFEBOOK E780               | Notebook    | [12c5cd0309](https://linux-hardware.org/?probe=12c5cd0309) | Jul 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d772da19a0](https://linux-hardware.org/?probe=d772da19a0) | Jun 30, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e539937c27](https://linux-hardware.org/?probe=e539937c27) | Jun 30, 2023 |
| Acer          | Predator PO5-640            | Desktop     | [416b01c954](https://linux-hardware.org/?probe=416b01c954) | Jun 30, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [434ba90999](https://linux-hardware.org/?probe=434ba90999) | Jun 30, 2023 |
| HP            | ENVY m6                     | Notebook    | [b4f8d19895](https://linux-hardware.org/?probe=b4f8d19895) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [3749bda51b](https://linux-hardware.org/?probe=3749bda51b) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [6ee8476c0e](https://linux-hardware.org/?probe=6ee8476c0e) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [5dd37cbc97](https://linux-hardware.org/?probe=5dd37cbc97) | Jun 30, 2023 |
| Google        | Eldrid                      | Notebook    | [4e08107dd6](https://linux-hardware.org/?probe=4e08107dd6) | Jun 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [997b1fe1f8](https://linux-hardware.org/?probe=997b1fe1f8) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [394788bdc8](https://linux-hardware.org/?probe=394788bdc8) | Jun 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| AZW           | MINI S 10                   | Desktop     | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a64b48a5a2](https://linux-hardware.org/?probe=a64b48a5a2) | Jun 29, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [e21f5d35bb](https://linux-hardware.org/?probe=e21f5d35bb) | Jun 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cfbc8c8a97](https://linux-hardware.org/?probe=cfbc8c8a97) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | Notebook    | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| Dell          | Latitude 5521               | Notebook    | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [df0ca94515](https://linux-hardware.org/?probe=df0ca94515) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [95fb20193a](https://linux-hardware.org/?probe=95fb20193a) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5bb4af3f8b](https://linux-hardware.org/?probe=5bb4af3f8b) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Google        | Nami                        | Notebook    | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2a5ae27f54](https://linux-hardware.org/?probe=2a5ae27f54) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | Notebook    | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [92a71d25d7](https://linux-hardware.org/?probe=92a71d25d7) | Jun 28, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [6e6779c5d6](https://linux-hardware.org/?probe=6e6779c5d6) | Jun 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [76e11b36e9](https://linux-hardware.org/?probe=76e11b36e9) | Jun 28, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [36f9eb51e6](https://linux-hardware.org/?probe=36f9eb51e6) | Jun 28, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| Dell          | Precision M6500             | Notebook    | [1db851fd5d](https://linux-hardware.org/?probe=1db851fd5d) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [b90f532588](https://linux-hardware.org/?probe=b90f532588) | Jun 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [0294ef5e1f](https://linux-hardware.org/?probe=0294ef5e1f) | Jun 28, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| HP            | 802F                        | Desktop     | [585f9bf338](https://linux-hardware.org/?probe=585f9bf338) | Jun 27, 2023 |
| HP            | 802F                        | Desktop     | [efceba0028](https://linux-hardware.org/?probe=efceba0028) | Jun 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8c2e9b8870](https://linux-hardware.org/?probe=8c2e9b8870) | Jun 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c3ae8b2d38](https://linux-hardware.org/?probe=c3ae8b2d38) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39ec9cf6c4](https://linux-hardware.org/?probe=39ec9cf6c4) | Jun 27, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [78b698279a](https://linux-hardware.org/?probe=78b698279a) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [41e22753cc](https://linux-hardware.org/?probe=41e22753cc) | Jun 27, 2023 |
| Dell          | 0R6PCT A01                  | Desktop     | [2fd7aa28db](https://linux-hardware.org/?probe=2fd7aa28db) | Jun 27, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [7487f61ff1](https://linux-hardware.org/?probe=7487f61ff1) | Jun 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [09acdc7c4a](https://linux-hardware.org/?probe=09acdc7c4a) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Dell          | PowerEdge R720xd            | Server      | [4570023480](https://linux-hardware.org/?probe=4570023480) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [22372b435f](https://linux-hardware.org/?probe=22372b435f) | Jun 26, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ee5172b420](https://linux-hardware.org/?probe=ee5172b420) | Jun 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [03153f31b2](https://linux-hardware.org/?probe=03153f31b2) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | Notebook    | [68117675ab](https://linux-hardware.org/?probe=68117675ab) | Jun 25, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [3486e43434](https://linux-hardware.org/?probe=3486e43434) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [e6184368a0](https://linux-hardware.org/?probe=e6184368a0) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | Notebook    | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [6a01ca36af](https://linux-hardware.org/?probe=6a01ca36af) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [b5996a0d85](https://linux-hardware.org/?probe=b5996a0d85) | Jun 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [8a833d8c52](https://linux-hardware.org/?probe=8a833d8c52) | Jun 25, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2153f80362](https://linux-hardware.org/?probe=2153f80362) | Jun 25, 2023 |
| Google        | Nami                        | Notebook    | [f9f785f70d](https://linux-hardware.org/?probe=f9f785f70d) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [3d1eeda7fa](https://linux-hardware.org/?probe=3d1eeda7fa) | Jun 24, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [755d1f8c03](https://linux-hardware.org/?probe=755d1f8c03) | Jun 24, 2023 |
| Dell          | Precision 5510              | Notebook    | [38d61a4475](https://linux-hardware.org/?probe=38d61a4475) | Jun 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e80fd49ba9](https://linux-hardware.org/?probe=e80fd49ba9) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [1c0d2d86f3](https://linux-hardware.org/?probe=1c0d2d86f3) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| Xplore        | iX104C6                     | Notebook    | [23bb4c656b](https://linux-hardware.org/?probe=23bb4c656b) | Jun 24, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [bcfc1fe2de](https://linux-hardware.org/?probe=bcfc1fe2de) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [f51aeb6252](https://linux-hardware.org/?probe=f51aeb6252) | Jun 23, 2023 |
| Lenovo        | 00YJ434 SVT                 | Server      | [ba92d2c25b](https://linux-hardware.org/?probe=ba92d2c25b) | Jun 23, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [4c4335bcff](https://linux-hardware.org/?probe=4c4335bcff) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7b187eac86](https://linux-hardware.org/?probe=7b187eac86) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [ae40c874ae](https://linux-hardware.org/?probe=ae40c874ae) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [505b340648](https://linux-hardware.org/?probe=505b340648) | Jun 23, 2023 |
| Oracle        | ASM,MOTHERBOARD,1U          | Server      | [cb71d1574c](https://linux-hardware.org/?probe=cb71d1574c) | Jun 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | Notebook    | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| AZW           | SER                         | Mini pc     | [4375fcb36a](https://linux-hardware.org/?probe=4375fcb36a) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [06977283b8](https://linux-hardware.org/?probe=06977283b8) | Jun 22, 2023 |
| HP            | Compaq 6710b (GF940AT#AB... | Notebook    | [75199aaf80](https://linux-hardware.org/?probe=75199aaf80) | Jun 22, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [dfeaf221e6](https://linux-hardware.org/?probe=dfeaf221e6) | Jun 22, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [c63cf5f434](https://linux-hardware.org/?probe=c63cf5f434) | Jun 22, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [e03310c8e8](https://linux-hardware.org/?probe=e03310c8e8) | Jun 22, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | Desktop     | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| Samsung       | 750QFG                      | Convertible | [6e0e03a83e](https://linux-hardware.org/?probe=6e0e03a83e) | Jun 22, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [c9f86c15b7](https://linux-hardware.org/?probe=c9f86c15b7) | Jun 22, 2023 |
| iRU           | J231                        | All in one  | [3002ce753a](https://linux-hardware.org/?probe=3002ce753a) | Jun 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [aa0f45d3f1](https://linux-hardware.org/?probe=aa0f45d3f1) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [7782ddf809](https://linux-hardware.org/?probe=7782ddf809) | Jun 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [52bcb712ec](https://linux-hardware.org/?probe=52bcb712ec) | Jun 22, 2023 |
| Framework     | Laptop                      | Notebook    | [eb51a9a662](https://linux-hardware.org/?probe=eb51a9a662) | Jun 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [8158959dbd](https://linux-hardware.org/?probe=8158959dbd) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | Notebook    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | Notebook    | [a2e5b66940](https://linux-hardware.org/?probe=a2e5b66940) | Jun 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [71d10fdd86](https://linux-hardware.org/?probe=71d10fdd86) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [a68e387274](https://linux-hardware.org/?probe=a68e387274) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [eaa3017d03](https://linux-hardware.org/?probe=eaa3017d03) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [510604914c](https://linux-hardware.org/?probe=510604914c) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ab169bfbfd](https://linux-hardware.org/?probe=ab169bfbfd) | Jun 21, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS02V0... | Notebook    | [bed60c3010](https://linux-hardware.org/?probe=bed60c3010) | Jun 21, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [4e7d62b30a](https://linux-hardware.org/?probe=4e7d62b30a) | Jun 21, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [60babdeb16](https://linux-hardware.org/?probe=60babdeb16) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [73306c60af](https://linux-hardware.org/?probe=73306c60af) | Jun 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a5e833c54e](https://linux-hardware.org/?probe=a5e833c54e) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [0d9054df1e](https://linux-hardware.org/?probe=0d9054df1e) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | Desktop     | [52e2d1b77a](https://linux-hardware.org/?probe=52e2d1b77a) | Jun 21, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | Desktop     | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [8d35565fd3](https://linux-hardware.org/?probe=8d35565fd3) | Jun 20, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [3aa5f3f213](https://linux-hardware.org/?probe=3aa5f3f213) | Jun 20, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8550e224ec](https://linux-hardware.org/?probe=8550e224ec) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| Dell          | Latitude 5289               | Notebook    | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [e7bb42d6d4](https://linux-hardware.org/?probe=e7bb42d6d4) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [11edb8696f](https://linux-hardware.org/?probe=11edb8696f) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [2fe4bf8ad2](https://linux-hardware.org/?probe=2fe4bf8ad2) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [2df6a58651](https://linux-hardware.org/?probe=2df6a58651) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1595a5adbd](https://linux-hardware.org/?probe=1595a5adbd) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [2a1262580e](https://linux-hardware.org/?probe=2a1262580e) | Jun 20, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [06a28c4a80](https://linux-hardware.org/?probe=06a28c4a80) | Jun 20, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [82927c0cb7](https://linux-hardware.org/?probe=82927c0cb7) | Jun 20, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [063ce55dd5](https://linux-hardware.org/?probe=063ce55dd5) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [e5db90d1b4](https://linux-hardware.org/?probe=e5db90d1b4) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [058b2ea405](https://linux-hardware.org/?probe=058b2ea405) | Jun 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e1c2d99faa](https://linux-hardware.org/?probe=e1c2d99faa) | Jun 19, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [7fe527c4fa](https://linux-hardware.org/?probe=7fe527c4fa) | Jun 19, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [f38684c33d](https://linux-hardware.org/?probe=f38684c33d) | Jun 19, 2023 |
| Dell          | Latitude E7470              | Notebook    | [645538d81e](https://linux-hardware.org/?probe=645538d81e) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [27bfb2de7d](https://linux-hardware.org/?probe=27bfb2de7d) | Jun 19, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [e40e63fa5f](https://linux-hardware.org/?probe=e40e63fa5f) | Jun 19, 2023 |
| Lenovo        | Legion R7000P2021 82JW      | Notebook    | [df59b5e8b7](https://linux-hardware.org/?probe=df59b5e8b7) | Jun 19, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d196994309](https://linux-hardware.org/?probe=d196994309) | Jun 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bd1d19c56b](https://linux-hardware.org/?probe=bd1d19c56b) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | Desktop     | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [65385cc189](https://linux-hardware.org/?probe=65385cc189) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| HP            | ENVY 15                     | Notebook    | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [125b4fefa5](https://linux-hardware.org/?probe=125b4fefa5) | Jun 19, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [8a88cbb916](https://linux-hardware.org/?probe=8a88cbb916) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ce3c5bc056](https://linux-hardware.org/?probe=ce3c5bc056) | Jun 18, 2023 |
| Dell          | 0C2XKD A01                  | Desktop     | [15331b91ed](https://linux-hardware.org/?probe=15331b91ed) | Jun 18, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7dc6f3af4b](https://linux-hardware.org/?probe=7dc6f3af4b) | Jun 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [924b6e8d54](https://linux-hardware.org/?probe=924b6e8d54) | Jun 18, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [ecf90f8368](https://linux-hardware.org/?probe=ecf90f8368) | Jun 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cf19f7a582](https://linux-hardware.org/?probe=cf19f7a582) | Jun 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [8b9ddcc1d8](https://linux-hardware.org/?probe=8b9ddcc1d8) | Jun 18, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [f266551c9d](https://linux-hardware.org/?probe=f266551c9d) | Jun 18, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [231a3aeb2e](https://linux-hardware.org/?probe=231a3aeb2e) | Jun 18, 2023 |
| Google        | Kefka                       | Notebook    | [86421e3d29](https://linux-hardware.org/?probe=86421e3d29) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d5c387d28e](https://linux-hardware.org/?probe=d5c387d28e) | Jun 18, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e01ed6ab42](https://linux-hardware.org/?probe=e01ed6ab42) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cd87a6b19f](https://linux-hardware.org/?probe=cd87a6b19f) | Jun 17, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [ca656065e5](https://linux-hardware.org/?probe=ca656065e5) | Jun 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f008a78339](https://linux-hardware.org/?probe=f008a78339) | Jun 17, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [acaa27666b](https://linux-hardware.org/?probe=acaa27666b) | Jun 17, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [92ace6e5ab](https://linux-hardware.org/?probe=92ace6e5ab) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [ae4661e26f](https://linux-hardware.org/?probe=ae4661e26f) | Jun 17, 2023 |
| Sony          | SVF15213CBW                 | Notebook    | [4fcc62d3ac](https://linux-hardware.org/?probe=4fcc62d3ac) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [c555238190](https://linux-hardware.org/?probe=c555238190) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [2d5c5b2c80](https://linux-hardware.org/?probe=2d5c5b2c80) | Jun 17, 2023 |
| Framework     | Laptop                      | Notebook    | [3df2b82bc3](https://linux-hardware.org/?probe=3df2b82bc3) | Jun 17, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cb1add1b88](https://linux-hardware.org/?probe=cb1add1b88) | Jun 17, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [79c0cd0257](https://linux-hardware.org/?probe=79c0cd0257) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [46ad2c78f7](https://linux-hardware.org/?probe=46ad2c78f7) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7e135be518](https://linux-hardware.org/?probe=7e135be518) | Jun 17, 2023 |
| Google        | Cave                        | Notebook    | [31c31973e1](https://linux-hardware.org/?probe=31c31973e1) | Jun 17, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [edd82d072b](https://linux-hardware.org/?probe=edd82d072b) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [268b733c44](https://linux-hardware.org/?probe=268b733c44) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [84b103464e](https://linux-hardware.org/?probe=84b103464e) | Jun 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [3b83e2ea48](https://linux-hardware.org/?probe=3b83e2ea48) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [aad3ead710](https://linux-hardware.org/?probe=aad3ead710) | Jun 16, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [4c6361a099](https://linux-hardware.org/?probe=4c6361a099) | Jun 16, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [04329cdc14](https://linux-hardware.org/?probe=04329cdc14) | Jun 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude 3420               | Notebook    | [a0074970bf](https://linux-hardware.org/?probe=a0074970bf) | Jun 16, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [eb9232a196](https://linux-hardware.org/?probe=eb9232a196) | Jun 16, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a2426b801a](https://linux-hardware.org/?probe=a2426b801a) | Jun 16, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [9c3bb21706](https://linux-hardware.org/?probe=9c3bb21706) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [a0d460b4a3](https://linux-hardware.org/?probe=a0d460b4a3) | Jun 16, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [a6a2463b97](https://linux-hardware.org/?probe=a6a2463b97) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [89ac5ef04b](https://linux-hardware.org/?probe=89ac5ef04b) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [32eb9f5dea](https://linux-hardware.org/?probe=32eb9f5dea) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [9f9ffda2e3](https://linux-hardware.org/?probe=9f9ffda2e3) | Jun 15, 2023 |
| Intel         | NUC6i7KYB H90766-410        | Mini pc     | [b4677c0332](https://linux-hardware.org/?probe=b4677c0332) | Jun 15, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9604c6211e](https://linux-hardware.org/?probe=9604c6211e) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c488929cdc](https://linux-hardware.org/?probe=c488929cdc) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [ff98efdef7](https://linux-hardware.org/?probe=ff98efdef7) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | Notebook    | [dd5aaca858](https://linux-hardware.org/?probe=dd5aaca858) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [721dc95455](https://linux-hardware.org/?probe=721dc95455) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5a1e944af2](https://linux-hardware.org/?probe=5a1e944af2) | Jun 15, 2023 |
| Dell          | Latitude E7470              | Notebook    | [c4bd47b182](https://linux-hardware.org/?probe=c4bd47b182) | Jun 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [f3d2cd0976](https://linux-hardware.org/?probe=f3d2cd0976) | Jun 15, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [64e0ce279b](https://linux-hardware.org/?probe=64e0ce279b) | Jun 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [b9d120642c](https://linux-hardware.org/?probe=b9d120642c) | Jun 14, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| Dell          | Latitude 7430               | Notebook    | [6cf1c68c1d](https://linux-hardware.org/?probe=6cf1c68c1d) | Jun 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6f4c06d514](https://linux-hardware.org/?probe=6f4c06d514) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8ad5106aca](https://linux-hardware.org/?probe=8ad5106aca) | Jun 14, 2023 |
| Samsung       | 930QDB                      | Convertible | [f513cc35ed](https://linux-hardware.org/?probe=f513cc35ed) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e676294e36](https://linux-hardware.org/?probe=e676294e36) | Jun 13, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [6291133649](https://linux-hardware.org/?probe=6291133649) | Jun 13, 2023 |
| MSI           | H510M PRO                   | Desktop     | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [58b9a1f862](https://linux-hardware.org/?probe=58b9a1f862) | Jun 13, 2023 |
| MSI           | IONA                        | Desktop     | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| HP            | Notebook                    | Notebook    | [64232e0a08](https://linux-hardware.org/?probe=64232e0a08) | Jun 13, 2023 |
| Google        | Blooglet                    | Notebook    | [3dedc16acb](https://linux-hardware.org/?probe=3dedc16acb) | Jun 13, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9ab7a065c4](https://linux-hardware.org/?probe=9ab7a065c4) | Jun 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dc3b9443ef](https://linux-hardware.org/?probe=dc3b9443ef) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ee5c72c283](https://linux-hardware.org/?probe=ee5c72c283) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [db48a7b38d](https://linux-hardware.org/?probe=db48a7b38d) | Jun 13, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cea599b1d4](https://linux-hardware.org/?probe=cea599b1d4) | Jun 13, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [87fae7fd5c](https://linux-hardware.org/?probe=87fae7fd5c) | Jun 13, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [5eb605a720](https://linux-hardware.org/?probe=5eb605a720) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| Dell          | Latitude 7430               | Notebook    | [6a01453dfa](https://linux-hardware.org/?probe=6a01453dfa) | Jun 12, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [e6713db4c3](https://linux-hardware.org/?probe=e6713db4c3) | Jun 12, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [f31365f369](https://linux-hardware.org/?probe=f31365f369) | Jun 12, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ffd9da63dd](https://linux-hardware.org/?probe=ffd9da63dd) | Jun 12, 2023 |
| ASRock        | Z390 Pro4                   | Desktop     | [067d0e5da5](https://linux-hardware.org/?probe=067d0e5da5) | Jun 12, 2023 |
| Lenovo        | ThinkPad W541 20EGS15J0N    | Notebook    | [ba935e9d5c](https://linux-hardware.org/?probe=ba935e9d5c) | Jun 12, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [318f1f4d2a](https://linux-hardware.org/?probe=318f1f4d2a) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [d183d47822](https://linux-hardware.org/?probe=d183d47822) | Jun 12, 2023 |
| HP            | Pavilion dm4                | Notebook    | [6eb4c3d87a](https://linux-hardware.org/?probe=6eb4c3d87a) | Jun 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb6dc5143e](https://linux-hardware.org/?probe=eb6dc5143e) | Jun 12, 2023 |
| Timi          | RedmiBook Pro 14            | Notebook    | [7b2e093b24](https://linux-hardware.org/?probe=7b2e093b24) | Jun 12, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [8f43ad0e76](https://linux-hardware.org/?probe=8f43ad0e76) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [90bcfaba60](https://linux-hardware.org/?probe=90bcfaba60) | Jun 12, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [f1614bb08f](https://linux-hardware.org/?probe=f1614bb08f) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0d07b35562](https://linux-hardware.org/?probe=0d07b35562) | Jun 11, 2023 |
| Dell          | G3 3579                     | Notebook    | [c04bf46d3e](https://linux-hardware.org/?probe=c04bf46d3e) | Jun 11, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [57fcd66521](https://linux-hardware.org/?probe=57fcd66521) | Jun 11, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [238dbf7ebb](https://linux-hardware.org/?probe=238dbf7ebb) | Jun 11, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [777f28f9e8](https://linux-hardware.org/?probe=777f28f9e8) | Jun 11, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [334034fb3d](https://linux-hardware.org/?probe=334034fb3d) | Jun 11, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [66aa96212a](https://linux-hardware.org/?probe=66aa96212a) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [bdb57b974f](https://linux-hardware.org/?probe=bdb57b974f) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d08556f55b](https://linux-hardware.org/?probe=d08556f55b) | Jun 11, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [c74425abce](https://linux-hardware.org/?probe=c74425abce) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| Dell          | Latitude 3420               | Notebook    | [07061e9d7d](https://linux-hardware.org/?probe=07061e9d7d) | Jun 10, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [22a8a9d964](https://linux-hardware.org/?probe=22a8a9d964) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [96b21d42f1](https://linux-hardware.org/?probe=96b21d42f1) | Jun 10, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [abd31d2f92](https://linux-hardware.org/?probe=abd31d2f92) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | Notebook    | [ac48eeb92c](https://linux-hardware.org/?probe=ac48eeb92c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | Notebook    | [ade15528d8](https://linux-hardware.org/?probe=ade15528d8) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| Unknown       | Unknown                     | Soc         | [a61c241455](https://linux-hardware.org/?probe=a61c241455) | Jun 10, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [68c941fe5d](https://linux-hardware.org/?probe=68c941fe5d) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [392ff8bfbb](https://linux-hardware.org/?probe=392ff8bfbb) | Jun 10, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [929c318674](https://linux-hardware.org/?probe=929c318674) | Jun 10, 2023 |
| MSI           | MS-7388                     | Desktop     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [36016c0c6b](https://linux-hardware.org/?probe=36016c0c6b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [2851b41659](https://linux-hardware.org/?probe=2851b41659) | Jun 09, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [9765261d02](https://linux-hardware.org/?probe=9765261d02) | Jun 09, 2023 |
| HP            | 339B                        | Desktop     | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [8cc29c049e](https://linux-hardware.org/?probe=8cc29c049e) | Jun 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7bc800675d](https://linux-hardware.org/?probe=7bc800675d) | Jun 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [9e3dfb25be](https://linux-hardware.org/?probe=9e3dfb25be) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [8f0087d741](https://linux-hardware.org/?probe=8f0087d741) | Jun 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [e246e70bb6](https://linux-hardware.org/?probe=e246e70bb6) | Jun 09, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [27c0e57cb3](https://linux-hardware.org/?probe=27c0e57cb3) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| Dell          | Inspiron 3493               | Notebook    | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [1caf029f79](https://linux-hardware.org/?probe=1caf029f79) | Jun 09, 2023 |
| Dell          | Precision 7540              | Notebook    | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [70fea7478a](https://linux-hardware.org/?probe=70fea7478a) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| Dell          | Latitude 5175               | Notebook    | [63d6fcf641](https://linux-hardware.org/?probe=63d6fcf641) | Jun 08, 2023 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [4c8d8758b7](https://linux-hardware.org/?probe=4c8d8758b7) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0c923e1174](https://linux-hardware.org/?probe=0c923e1174) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | Desktop     | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [eda13b898c](https://linux-hardware.org/?probe=eda13b898c) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [13b0e73872](https://linux-hardware.org/?probe=13b0e73872) | Jun 08, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [e6cb646bd4](https://linux-hardware.org/?probe=e6cb646bd4) | Jun 08, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [0aea375d78](https://linux-hardware.org/?probe=0aea375d78) | Jun 08, 2023 |
| Dell          | Precision 3551              | Notebook    | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7543a0bbc1](https://linux-hardware.org/?probe=7543a0bbc1) | Jun 08, 2023 |
| Dell          | Precision 5510              | Notebook    | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| Lenovo        | ThinkPad T580 20L90047US    | Notebook    | [bee34052a3](https://linux-hardware.org/?probe=bee34052a3) | Jun 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9c9fb1b1a6](https://linux-hardware.org/?probe=9c9fb1b1a6) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [e95900bc0c](https://linux-hardware.org/?probe=e95900bc0c) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [829839a3b3](https://linux-hardware.org/?probe=829839a3b3) | Jun 07, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [98d7cb7ea7](https://linux-hardware.org/?probe=98d7cb7ea7) | Jun 07, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [91fc26029a](https://linux-hardware.org/?probe=91fc26029a) | Jun 07, 2023 |
| TYAN Compu... | S7020                       | Server      | [6b39aa397f](https://linux-hardware.org/?probe=6b39aa397f) | Jun 07, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [5f0e8ab63a](https://linux-hardware.org/?probe=5f0e8ab63a) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [06608c68d7](https://linux-hardware.org/?probe=06608c68d7) | Jun 07, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [fd156e669f](https://linux-hardware.org/?probe=fd156e669f) | Jun 07, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2a0add5b7e](https://linux-hardware.org/?probe=2a0add5b7e) | Jun 07, 2023 |
| HP            | 339B                        | Desktop     | [a1739aa36b](https://linux-hardware.org/?probe=a1739aa36b) | Jun 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [b6bb7bad1d](https://linux-hardware.org/?probe=b6bb7bad1d) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | Desktop     | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f9b3588ff3](https://linux-hardware.org/?probe=f9b3588ff3) | Jun 07, 2023 |
| Lenovo        | ThinkPad T495 20NKS10K00    | Notebook    | [f205c52b8f](https://linux-hardware.org/?probe=f205c52b8f) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [8c505b5d84](https://linux-hardware.org/?probe=8c505b5d84) | Jun 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9afe34cdd8](https://linux-hardware.org/?probe=9afe34cdd8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [eb3fbddd2c](https://linux-hardware.org/?probe=eb3fbddd2c) | Jun 06, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [16aa33fdfe](https://linux-hardware.org/?probe=16aa33fdfe) | Jun 06, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [addb15771e](https://linux-hardware.org/?probe=addb15771e) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | Notebook    | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| Lenovo        | ThinkPad T460 20FMS2292K    | Notebook    | [380ffe6574](https://linux-hardware.org/?probe=380ffe6574) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c3f02841f4](https://linux-hardware.org/?probe=c3f02841f4) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [4cec4f0517](https://linux-hardware.org/?probe=4cec4f0517) | Jun 06, 2023 |
| HP            | 83E1                        | Desktop     | [227e410c6f](https://linux-hardware.org/?probe=227e410c6f) | Jun 06, 2023 |
| Lenovo        | 30D0 NOK                    | Desktop     | [045b011b7a](https://linux-hardware.org/?probe=045b011b7a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [917b8c425f](https://linux-hardware.org/?probe=917b8c425f) | Jun 06, 2023 |
| System76      | Oryx Pro                    | Notebook    | [4f39b2d690](https://linux-hardware.org/?probe=4f39b2d690) | Jun 06, 2023 |
| realme        | CloudProXXXX                | Notebook    | [22cced9066](https://linux-hardware.org/?probe=22cced9066) | Jun 05, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [91ee57c108](https://linux-hardware.org/?probe=91ee57c108) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [9a1c9022af](https://linux-hardware.org/?probe=9a1c9022af) | Jun 05, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [bb29d15c61](https://linux-hardware.org/?probe=bb29d15c61) | Jun 05, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [5c3daec3c7](https://linux-hardware.org/?probe=5c3daec3c7) | Jun 05, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [de8a3d6dab](https://linux-hardware.org/?probe=de8a3d6dab) | Jun 05, 2023 |
| Samsung       | 950XEE                      | Notebook    | [cc47fd0df0](https://linux-hardware.org/?probe=cc47fd0df0) | Jun 05, 2023 |
| Lenovo        | ThinkPad E450 20DC003WUS    | Notebook    | [6abecb1cd3](https://linux-hardware.org/?probe=6abecb1cd3) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8e4ad66edc](https://linux-hardware.org/?probe=8e4ad66edc) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| Dell          | Precision 7540              | Notebook    | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Sony          | VPCSC1AFM                   | Notebook    | [2cf80cf628](https://linux-hardware.org/?probe=2cf80cf628) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d6befa925e](https://linux-hardware.org/?probe=d6befa925e) | Jun 04, 2023 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f254b0806d](https://linux-hardware.org/?probe=f254b0806d) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [dfb8881ffe](https://linux-hardware.org/?probe=dfb8881ffe) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [a735050ced](https://linux-hardware.org/?probe=a735050ced) | Jun 04, 2023 |
| AMI           | Intel                       | Notebook    | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | Desktop     | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [267010517a](https://linux-hardware.org/?probe=267010517a) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [fa41f1f3c2](https://linux-hardware.org/?probe=fa41f1f3c2) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Dell          | Latitude D620               | Notebook    | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [78786ec91a](https://linux-hardware.org/?probe=78786ec91a) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [f241c0cf38](https://linux-hardware.org/?probe=f241c0cf38) | Jun 03, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [aea1babfb7](https://linux-hardware.org/?probe=aea1babfb7) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [3fb87e5a0e](https://linux-hardware.org/?probe=3fb87e5a0e) | Jun 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [7ae3c54a4c](https://linux-hardware.org/?probe=7ae3c54a4c) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| Sony          | SVF1521A1EW                 | Notebook    | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [f576f54ff2](https://linux-hardware.org/?probe=f576f54ff2) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| HP            | Unknown                     | Notebook    | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | Notebook    | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [9931f8e663](https://linux-hardware.org/?probe=9931f8e663) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5562bc75b8](https://linux-hardware.org/?probe=5562bc75b8) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [714ed7283d](https://linux-hardware.org/?probe=714ed7283d) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [bb2776b990](https://linux-hardware.org/?probe=bb2776b990) | Jun 02, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [2dc3c08466](https://linux-hardware.org/?probe=2dc3c08466) | Jun 02, 2023 |
| MSI           | MS-7388                     | Desktop     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [047bfb6e8e](https://linux-hardware.org/?probe=047bfb6e8e) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | Notebook    | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [ca904474bf](https://linux-hardware.org/?probe=ca904474bf) | Jun 02, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [ea337d3d2a](https://linux-hardware.org/?probe=ea337d3d2a) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [57db123250](https://linux-hardware.org/?probe=57db123250) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| HP            | 845A                        | Desktop     | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Unknown       | Unknown                     | Tablet      | [40aebbf364](https://linux-hardware.org/?probe=40aebbf364) | Jun 01, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Timi          | A35S                        | Notebook    | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| HP            | 339A                        | Desktop     | [24ab8463bb](https://linux-hardware.org/?probe=24ab8463bb) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9afffc17a1](https://linux-hardware.org/?probe=9afffc17a1) | Jun 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8799da8513](https://linux-hardware.org/?probe=8799da8513) | Jun 01, 2023 |
| Samsung       | 750QFG                      | Convertible | [7720d51647](https://linux-hardware.org/?probe=7720d51647) | Jun 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [34dde30b90](https://linux-hardware.org/?probe=34dde30b90) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [5c9c446c66](https://linux-hardware.org/?probe=5c9c446c66) | Jun 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | Notebook    | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Dell          | Latitude 5531               | Notebook    | [5dc2ae0939](https://linux-hardware.org/?probe=5dc2ae0939) | Jun 01, 2023 |
| Timi          | TM1801                      | Notebook    | [aa1db210df](https://linux-hardware.org/?probe=aa1db210df) | Jun 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [1dfd1982d8](https://linux-hardware.org/?probe=1dfd1982d8) | May 31, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e365621d30](https://linux-hardware.org/?probe=e365621d30) | May 31, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [f1e9073b3d](https://linux-hardware.org/?probe=f1e9073b3d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| HP            | Unknown                     | Notebook    | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | Notebook    | [7e07cca977](https://linux-hardware.org/?probe=7e07cca977) | May 31, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [75f612c4db](https://linux-hardware.org/?probe=75f612c4db) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [2f61fcf47d](https://linux-hardware.org/?probe=2f61fcf47d) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS1RM02    | Notebook    | [8f39bcbb17](https://linux-hardware.org/?probe=8f39bcbb17) | May 30, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [d3ee3757e0](https://linux-hardware.org/?probe=d3ee3757e0) | May 30, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [e71d8e3bc0](https://linux-hardware.org/?probe=e71d8e3bc0) | May 30, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S09E00    | Notebook    | [894bac5d62](https://linux-hardware.org/?probe=894bac5d62) | May 30, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [c496e8a74f](https://linux-hardware.org/?probe=c496e8a74f) | May 30, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [349eb108ab](https://linux-hardware.org/?probe=349eb108ab) | May 30, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [59e9fd9749](https://linux-hardware.org/?probe=59e9fd9749) | May 30, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| HP            | Unknown                     | Notebook    | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b3966a1d81](https://linux-hardware.org/?probe=b3966a1d81) | May 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [049fbd746b](https://linux-hardware.org/?probe=049fbd746b) | May 30, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [611b47056d](https://linux-hardware.org/?probe=611b47056d) | May 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| HP            | 8307                        | Desktop     | [c8d0506eda](https://linux-hardware.org/?probe=c8d0506eda) | May 30, 2023 |
| Dell          | Precision 5540              | Notebook    | [2f3cdafe90](https://linux-hardware.org/?probe=2f3cdafe90) | May 30, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| VPU Compan... | VWNC51518                   | Notebook    | [16329bde51](https://linux-hardware.org/?probe=16329bde51) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [048a3a0f30](https://linux-hardware.org/?probe=048a3a0f30) | May 29, 2023 |
| Itautec       | ST 4265                     | Desktop     | [8814373cb4](https://linux-hardware.org/?probe=8814373cb4) | May 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3933dfe4f0](https://linux-hardware.org/?probe=3933dfe4f0) | May 29, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| Sony          | VPCSA25GB                   | Notebook    | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | Notebook    | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Itautec       | ST 4265                     | Desktop     | [b89c45a31d](https://linux-hardware.org/?probe=b89c45a31d) | May 29, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [d6f1c2bdbd](https://linux-hardware.org/?probe=d6f1c2bdbd) | May 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | Notebook    | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| HP            | 2820h                       | Desktop     | [d326b49f48](https://linux-hardware.org/?probe=d326b49f48) | May 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a430b5287c](https://linux-hardware.org/?probe=a430b5287c) | May 29, 2023 |
| HP            | Pavilion g4                 | Notebook    | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [52517395ca](https://linux-hardware.org/?probe=52517395ca) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [64c67b0919](https://linux-hardware.org/?probe=64c67b0919) | May 29, 2023 |
| Lenovo        | ThinkPad Edge 0301DCU       | Notebook    | [5b7394bc19](https://linux-hardware.org/?probe=5b7394bc19) | May 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [0c7bfc7977](https://linux-hardware.org/?probe=0c7bfc7977) | May 28, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [01d3e0d237](https://linux-hardware.org/?probe=01d3e0d237) | May 28, 2023 |
| iRU           | J231                        | All in one  | [fdc7f7219d](https://linux-hardware.org/?probe=fdc7f7219d) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [773f0d5242](https://linux-hardware.org/?probe=773f0d5242) | May 28, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [92b96250d1](https://linux-hardware.org/?probe=92b96250d1) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [f5a76aaf01](https://linux-hardware.org/?probe=f5a76aaf01) | May 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4e1ad3c652](https://linux-hardware.org/?probe=4e1ad3c652) | May 28, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [419c0c7359](https://linux-hardware.org/?probe=419c0c7359) | May 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [db3d362e28](https://linux-hardware.org/?probe=db3d362e28) | May 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [94fe283791](https://linux-hardware.org/?probe=94fe283791) | May 28, 2023 |
| Positivo      | N1250                       | Notebook    | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [6826d78921](https://linux-hardware.org/?probe=6826d78921) | May 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | Notebook    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Dell          | Latitude E6330              | Notebook    | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | Notebook    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [9d6faf76a0](https://linux-hardware.org/?probe=9d6faf76a0) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [0ff9159d89](https://linux-hardware.org/?probe=0ff9159d89) | May 27, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [906e585809](https://linux-hardware.org/?probe=906e585809) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | Desktop     | [0723379042](https://linux-hardware.org/?probe=0723379042) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | Desktop     | [ef1a056412](https://linux-hardware.org/?probe=ef1a056412) | May 27, 2023 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [ffbc308836](https://linux-hardware.org/?probe=ffbc308836) | May 27, 2023 |
| HP            | 8307                        | Desktop     | [94cad3911e](https://linux-hardware.org/?probe=94cad3911e) | May 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9a3691f3f2](https://linux-hardware.org/?probe=9a3691f3f2) | May 27, 2023 |
| Dell          | Latitude E6330              | Notebook    | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | Desktop     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [424078f376](https://linux-hardware.org/?probe=424078f376) | May 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90058G... | Notebook    | [71a2e90192](https://linux-hardware.org/?probe=71a2e90192) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| HP            | 0AECh D                     | Desktop     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [5037ec3f4a](https://linux-hardware.org/?probe=5037ec3f4a) | May 26, 2023 |
| Acer          | Aspire V3-551               | Notebook    | [9d609ccd4a](https://linux-hardware.org/?probe=9d609ccd4a) | May 26, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [2a7c9f1c06](https://linux-hardware.org/?probe=2a7c9f1c06) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| Dell          | G15 5525                    | Notebook    | [b2c8f44d8b](https://linux-hardware.org/?probe=b2c8f44d8b) | May 26, 2023 |
| Samsung       | 550XDA                      | Notebook    | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [4a59deb075](https://linux-hardware.org/?probe=4a59deb075) | May 25, 2023 |
| ASUSTek       | X705UVR                     | Notebook    | [bedbf77e16](https://linux-hardware.org/?probe=bedbf77e16) | May 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | Notebook    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Dell          | Precision 7540              | Notebook    | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [b88a90f9d3](https://linux-hardware.org/?probe=b88a90f9d3) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f0c2fede02](https://linux-hardware.org/?probe=f0c2fede02) | May 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [c2d85ba655](https://linux-hardware.org/?probe=c2d85ba655) | May 25, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [51dbf3c463](https://linux-hardware.org/?probe=51dbf3c463) | May 25, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| Lenovo        | ThinkPad T440p 20AW0045M... | Notebook    | [355e03f684](https://linux-hardware.org/?probe=355e03f684) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a167562cba](https://linux-hardware.org/?probe=a167562cba) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Google        | Voxel                       | Notebook    | [9dae4b7464](https://linux-hardware.org/?probe=9dae4b7464) | May 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [8472aba19b](https://linux-hardware.org/?probe=8472aba19b) | May 25, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [fe046d6420](https://linux-hardware.org/?probe=fe046d6420) | May 24, 2023 |
| Dell          | Precision 7540              | Notebook    | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [85202f4e41](https://linux-hardware.org/?probe=85202f4e41) | May 24, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [909becff79](https://linux-hardware.org/?probe=909becff79) | May 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [520e3d90a6](https://linux-hardware.org/?probe=520e3d90a6) | May 24, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [d7ab3b0ed3](https://linux-hardware.org/?probe=d7ab3b0ed3) | May 24, 2023 |
| ASUSTek       | X542UN                      | Notebook    | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d6ec4cc9bc](https://linux-hardware.org/?probe=d6ec4cc9bc) | May 24, 2023 |
| MSI           | 2A9C                        | Desktop     | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bcb5af2775](https://linux-hardware.org/?probe=bcb5af2775) | May 24, 2023 |
| HP            | 8307                        | Desktop     | [6797c02e08](https://linux-hardware.org/?probe=6797c02e08) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Unknown       | 0R5KP9 A09                  | Server      | [b77be6c666](https://linux-hardware.org/?probe=b77be6c666) | May 23, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [715800f05d](https://linux-hardware.org/?probe=715800f05d) | May 23, 2023 |
| Samsung       | 930QED                      | Convertible | [14f0193b6a](https://linux-hardware.org/?probe=14f0193b6a) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [402231776b](https://linux-hardware.org/?probe=402231776b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [eaa5b878d3](https://linux-hardware.org/?probe=eaa5b878d3) | May 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [90235c6d2e](https://linux-hardware.org/?probe=90235c6d2e) | May 23, 2023 |
| MSI           | B460M PRO                   | Desktop     | [94ce62125f](https://linux-hardware.org/?probe=94ce62125f) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | Notebook    | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| HP            | 3647h                       | Desktop     | [fc8cf5c799](https://linux-hardware.org/?probe=fc8cf5c799) | May 23, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| Dell          | G5 5587                     | Notebook    | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [c4040a0905](https://linux-hardware.org/?probe=c4040a0905) | May 23, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d42a4443c](https://linux-hardware.org/?probe=2d42a4443c) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | Notebook    | [56042328ac](https://linux-hardware.org/?probe=56042328ac) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | Notebook    | [0d63b518e4](https://linux-hardware.org/?probe=0d63b518e4) | May 23, 2023 |
| ASUSTek       | ET2321I                     | Notebook    | [829fe9b078](https://linux-hardware.org/?probe=829fe9b078) | May 23, 2023 |
| Dell          | Precision 7540              | Notebook    | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | Notebook    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [de335816aa](https://linux-hardware.org/?probe=de335816aa) | May 22, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [175272b7e0](https://linux-hardware.org/?probe=175272b7e0) | May 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [e110548f6e](https://linux-hardware.org/?probe=e110548f6e) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [71730fa381](https://linux-hardware.org/?probe=71730fa381) | May 22, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [c2965aff69](https://linux-hardware.org/?probe=c2965aff69) | May 22, 2023 |
| Framework     | Laptop                      | Notebook    | [7715f5f056](https://linux-hardware.org/?probe=7715f5f056) | May 22, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [c492073bac](https://linux-hardware.org/?probe=c492073bac) | May 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [63b100e342](https://linux-hardware.org/?probe=63b100e342) | May 22, 2023 |
| HP            | 1589                        | Desktop     | [a7d56849a5](https://linux-hardware.org/?probe=a7d56849a5) | May 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cc7b8d0a8](https://linux-hardware.org/?probe=9cc7b8d0a8) | May 22, 2023 |
| Dell          | Precision 5560              | Notebook    | [1fc79f4cc0](https://linux-hardware.org/?probe=1fc79f4cc0) | May 22, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [94c7ddea69](https://linux-hardware.org/?probe=94c7ddea69) | May 21, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [bc39784c46](https://linux-hardware.org/?probe=bc39784c46) | May 21, 2023 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | Desktop     | [0d2426a070](https://linux-hardware.org/?probe=0d2426a070) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [8c8c77d9a3](https://linux-hardware.org/?probe=8c8c77d9a3) | May 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [b03cb56dfa](https://linux-hardware.org/?probe=b03cb56dfa) | May 21, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [0b3265b088](https://linux-hardware.org/?probe=0b3265b088) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [b19380fb21](https://linux-hardware.org/?probe=b19380fb21) | May 21, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [bdd393edd7](https://linux-hardware.org/?probe=bdd393edd7) | May 21, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [de2fc32d08](https://linux-hardware.org/?probe=de2fc32d08) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [ef2b821a84](https://linux-hardware.org/?probe=ef2b821a84) | May 21, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [6f698f47d8](https://linux-hardware.org/?probe=6f698f47d8) | May 21, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [7063bb70eb](https://linux-hardware.org/?probe=7063bb70eb) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fc75b5ebda](https://linux-hardware.org/?probe=fc75b5ebda) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [4fff2c9c8a](https://linux-hardware.org/?probe=4fff2c9c8a) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [157b535164](https://linux-hardware.org/?probe=157b535164) | May 20, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [5f02199d8d](https://linux-hardware.org/?probe=5f02199d8d) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [b695d18b13](https://linux-hardware.org/?probe=b695d18b13) | May 20, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [50b19fc413](https://linux-hardware.org/?probe=50b19fc413) | May 20, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [36d4349090](https://linux-hardware.org/?probe=36d4349090) | May 20, 2023 |
| Google        | Akemi                       | Notebook    | [595f8b1a24](https://linux-hardware.org/?probe=595f8b1a24) | May 20, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [5c6dbc1b8a](https://linux-hardware.org/?probe=5c6dbc1b8a) | May 20, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | Notebook    | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| HP            | Laptop 17-by0061st          | Notebook    | [68e551f58a](https://linux-hardware.org/?probe=68e551f58a) | May 20, 2023 |
| ASUSTek       | P5B                         | Desktop     | [3effc437bb](https://linux-hardware.org/?probe=3effc437bb) | May 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1a05e80ee5](https://linux-hardware.org/?probe=1a05e80ee5) | May 20, 2023 |
| HP            | Pavilion dv3                | Notebook    | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4f27fb9c64](https://linux-hardware.org/?probe=4f27fb9c64) | May 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ac3d3ea87c](https://linux-hardware.org/?probe=ac3d3ea87c) | May 19, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [04dac52364](https://linux-hardware.org/?probe=04dac52364) | May 19, 2023 |
| MSI           | 2A9C                        | Desktop     | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7d7bdf142c](https://linux-hardware.org/?probe=7d7bdf142c) | May 19, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [e0a1fa9223](https://linux-hardware.org/?probe=e0a1fa9223) | May 19, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Dell          | Precision 5470              | Notebook    | [e600af2d5a](https://linux-hardware.org/?probe=e600af2d5a) | May 19, 2023 |
| Lenovo        | ThinkPad T61 6463B45        | Notebook    | [a2445821f3](https://linux-hardware.org/?probe=a2445821f3) | May 19, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [52bfbb69ee](https://linux-hardware.org/?probe=52bfbb69ee) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [6d04bdb08d](https://linux-hardware.org/?probe=6d04bdb08d) | May 19, 2023 |
| Google        | Candy                       | Notebook    | [2ed0555d82](https://linux-hardware.org/?probe=2ed0555d82) | May 19, 2023 |
| Lenovo        | ThinkPad P52 20MAS88000     | Notebook    | [f9a256566b](https://linux-hardware.org/?probe=f9a256566b) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [ebe436d0b5](https://linux-hardware.org/?probe=ebe436d0b5) | May 18, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [411344a862](https://linux-hardware.org/?probe=411344a862) | May 18, 2023 |
| Dell          | Precision 3560              | Notebook    | [f83f42ab2f](https://linux-hardware.org/?probe=f83f42ab2f) | May 18, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [868d98e4f4](https://linux-hardware.org/?probe=868d98e4f4) | May 18, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0eec4b5bbe](https://linux-hardware.org/?probe=0eec4b5bbe) | May 18, 2023 |
| MSI           | GE72 7RE                    | Notebook    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [3eb1bee421](https://linux-hardware.org/?probe=3eb1bee421) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | 630                         | Notebook    | [bd7bdf5942](https://linux-hardware.org/?probe=bd7bdf5942) | May 18, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [c15ff8f4c4](https://linux-hardware.org/?probe=c15ff8f4c4) | May 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [98727430ff](https://linux-hardware.org/?probe=98727430ff) | May 18, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [158feeb98d](https://linux-hardware.org/?probe=158feeb98d) | May 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4c72848255](https://linux-hardware.org/?probe=4c72848255) | May 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a33efd912c](https://linux-hardware.org/?probe=a33efd912c) | May 18, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [681fd36c12](https://linux-hardware.org/?probe=681fd36c12) | May 18, 2023 |
| Dell          | Precision 5520              | Notebook    | [6e4c751579](https://linux-hardware.org/?probe=6e4c751579) | May 18, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [255961cb74](https://linux-hardware.org/?probe=255961cb74) | May 18, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [09f9f2e231](https://linux-hardware.org/?probe=09f9f2e231) | May 17, 2023 |
| Dell          | Latitude 7420               | Convertible | [947b45703a](https://linux-hardware.org/?probe=947b45703a) | May 17, 2023 |
| HP            | 3048h                       | Desktop     | [9e65995057](https://linux-hardware.org/?probe=9e65995057) | May 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5d77e9825a](https://linux-hardware.org/?probe=5d77e9825a) | May 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [392cde1432](https://linux-hardware.org/?probe=392cde1432) | May 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [b22bdcc636](https://linux-hardware.org/?probe=b22bdcc636) | May 17, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [6adf226281](https://linux-hardware.org/?probe=6adf226281) | May 17, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [e4787e9b05](https://linux-hardware.org/?probe=e4787e9b05) | May 17, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c3f3d961bb](https://linux-hardware.org/?probe=c3f3d961bb) | May 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [cf08703fd3](https://linux-hardware.org/?probe=cf08703fd3) | May 17, 2023 |
| ASUSTek       | D700SC                      | Desktop     | [eab212a67d](https://linux-hardware.org/?probe=eab212a67d) | May 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [2a2712560e](https://linux-hardware.org/?probe=2a2712560e) | May 17, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [6cba75fa36](https://linux-hardware.org/?probe=6cba75fa36) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| HP            | 8055                        | Desktop     | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d4b209ad20](https://linux-hardware.org/?probe=d4b209ad20) | May 17, 2023 |
| HP            | 8055                        | Desktop     | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [f31be9149e](https://linux-hardware.org/?probe=f31be9149e) | May 17, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [51ff9a820a](https://linux-hardware.org/?probe=51ff9a820a) | May 16, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c05d5e127e](https://linux-hardware.org/?probe=c05d5e127e) | May 16, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [e98b404c17](https://linux-hardware.org/?probe=e98b404c17) | May 16, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [9b29aafd95](https://linux-hardware.org/?probe=9b29aafd95) | May 16, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [4f5efbc9fe](https://linux-hardware.org/?probe=4f5efbc9fe) | May 16, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [8041b17525](https://linux-hardware.org/?probe=8041b17525) | May 16, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4e1680877b](https://linux-hardware.org/?probe=4e1680877b) | May 16, 2023 |
| Samsung       | 550XDA                      | Notebook    | [75bc1cdfb3](https://linux-hardware.org/?probe=75bc1cdfb3) | May 16, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [5408ecb0b7](https://linux-hardware.org/?probe=5408ecb0b7) | May 16, 2023 |
| HP            | 630                         | Notebook    | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | Notebook    | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a7d169fdf8](https://linux-hardware.org/?probe=a7d169fdf8) | May 16, 2023 |
| Dell          | Latitude 7430               | Notebook    | [d137c2d73b](https://linux-hardware.org/?probe=d137c2d73b) | May 16, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c03dec75f1](https://linux-hardware.org/?probe=c03dec75f1) | May 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [055aae99b8](https://linux-hardware.org/?probe=055aae99b8) | May 16, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [2323128fd2](https://linux-hardware.org/?probe=2323128fd2) | May 16, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [a399b17822](https://linux-hardware.org/?probe=a399b17822) | May 16, 2023 |
| iRU           | A231                        | Desktop     | [0b35bba039](https://linux-hardware.org/?probe=0b35bba039) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [10c0c499c2](https://linux-hardware.org/?probe=10c0c499c2) | May 16, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [cc0f5fc70a](https://linux-hardware.org/?probe=cc0f5fc70a) | May 16, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [15b4320ae1](https://linux-hardware.org/?probe=15b4320ae1) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [294fe7853f](https://linux-hardware.org/?probe=294fe7853f) | May 15, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [2375fac142](https://linux-hardware.org/?probe=2375fac142) | May 15, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2ffc331e90](https://linux-hardware.org/?probe=2ffc331e90) | May 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [4529ae76bb](https://linux-hardware.org/?probe=4529ae76bb) | May 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [9cb65eaaf2](https://linux-hardware.org/?probe=9cb65eaaf2) | May 15, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | Notebook    | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [8f36de95ee](https://linux-hardware.org/?probe=8f36de95ee) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [975de0cf0d](https://linux-hardware.org/?probe=975de0cf0d) | May 15, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [38482c1a10](https://linux-hardware.org/?probe=38482c1a10) | May 15, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [1e7e92e7e8](https://linux-hardware.org/?probe=1e7e92e7e8) | May 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a28a0c505](https://linux-hardware.org/?probe=5a28a0c505) | May 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [14a0c32722](https://linux-hardware.org/?probe=14a0c32722) | May 15, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [58f493d242](https://linux-hardware.org/?probe=58f493d242) | May 15, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e4d8abe098](https://linux-hardware.org/?probe=e4d8abe098) | May 15, 2023 |
| AMI           | Intel                       | Desktop     | [05850f17d5](https://linux-hardware.org/?probe=05850f17d5) | May 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [0a6ee8c111](https://linux-hardware.org/?probe=0a6ee8c111) | May 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e9ce1757ae](https://linux-hardware.org/?probe=e9ce1757ae) | May 14, 2023 |
| iRU           | A231                        | Desktop     | [8c941b1457](https://linux-hardware.org/?probe=8c941b1457) | May 14, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [66e7dc292e](https://linux-hardware.org/?probe=66e7dc292e) | May 14, 2023 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | Notebook    | [8921a6d64e](https://linux-hardware.org/?probe=8921a6d64e) | May 14, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [71acd5de88](https://linux-hardware.org/?probe=71acd5de88) | May 14, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [2ab0709f22](https://linux-hardware.org/?probe=2ab0709f22) | May 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0060b3cb1c](https://linux-hardware.org/?probe=0060b3cb1c) | May 14, 2023 |
| Lenovo        | ThinkBook Plus G2 ITG 20... | Notebook    | [2881ffcb77](https://linux-hardware.org/?probe=2881ffcb77) | May 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1f657b2f59](https://linux-hardware.org/?probe=1f657b2f59) | May 14, 2023 |
| Dell          | Latitude E6520              | Notebook    | [78aaf99b7b](https://linux-hardware.org/?probe=78aaf99b7b) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [72eaf980ad](https://linux-hardware.org/?probe=72eaf980ad) | May 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f5fa402f37](https://linux-hardware.org/?probe=f5fa402f37) | May 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [9298a8529a](https://linux-hardware.org/?probe=9298a8529a) | May 14, 2023 |
| HP            | 630                         | Notebook    | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [d0a6a8e29e](https://linux-hardware.org/?probe=d0a6a8e29e) | May 14, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [fe80771d2e](https://linux-hardware.org/?probe=fe80771d2e) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [784de41090](https://linux-hardware.org/?probe=784de41090) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e3dedcbd6a](https://linux-hardware.org/?probe=e3dedcbd6a) | May 14, 2023 |
| MSI           | 990XA-GD55                  | Desktop     | [98693ec64b](https://linux-hardware.org/?probe=98693ec64b) | May 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f2d7d4ba58](https://linux-hardware.org/?probe=f2d7d4ba58) | May 14, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [22d379cd2f](https://linux-hardware.org/?probe=22d379cd2f) | May 13, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [0f3a2fae1b](https://linux-hardware.org/?probe=0f3a2fae1b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| ASUSTek       | GL502VMK                    | Notebook    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1e5caac049](https://linux-hardware.org/?probe=1e5caac049) | May 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [16cfe08da3](https://linux-hardware.org/?probe=16cfe08da3) | May 13, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [12b97cd9b6](https://linux-hardware.org/?probe=12b97cd9b6) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [804de32208](https://linux-hardware.org/?probe=804de32208) | May 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fd2bd3be00](https://linux-hardware.org/?probe=fd2bd3be00) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [e31e211aa2](https://linux-hardware.org/?probe=e31e211aa2) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [8f2f79fb45](https://linux-hardware.org/?probe=8f2f79fb45) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [60d7b5acf8](https://linux-hardware.org/?probe=60d7b5acf8) | May 13, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [68573d1b85](https://linux-hardware.org/?probe=68573d1b85) | May 13, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [efab80e399](https://linux-hardware.org/?probe=efab80e399) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [a7e9891909](https://linux-hardware.org/?probe=a7e9891909) | May 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9efa5d994b](https://linux-hardware.org/?probe=9efa5d994b) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5a39aa9b41](https://linux-hardware.org/?probe=5a39aa9b41) | May 12, 2023 |
| Dell          | Latitude E7450              | Notebook    | [cb96fcfaff](https://linux-hardware.org/?probe=cb96fcfaff) | May 12, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [e3c61280ed](https://linux-hardware.org/?probe=e3c61280ed) | May 12, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1713b94d26](https://linux-hardware.org/?probe=1713b94d26) | May 12, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [068ef24174](https://linux-hardware.org/?probe=068ef24174) | May 12, 2023 |
| Positivo      | J14GL11                     | Notebook    | [bfdf0df9b8](https://linux-hardware.org/?probe=bfdf0df9b8) | May 12, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [64353c7d87](https://linux-hardware.org/?probe=64353c7d87) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c590339049](https://linux-hardware.org/?probe=c590339049) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c9a6fca8a8](https://linux-hardware.org/?probe=c9a6fca8a8) | May 12, 2023 |
| Biostar       | A320MH                      | Desktop     | [d30baf9379](https://linux-hardware.org/?probe=d30baf9379) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [b01a016489](https://linux-hardware.org/?probe=b01a016489) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [3c8b5aefd8](https://linux-hardware.org/?probe=3c8b5aefd8) | May 11, 2023 |
| Supermicro    | X12SAE-5                    | Server      | [6481a9f2cb](https://linux-hardware.org/?probe=6481a9f2cb) | May 11, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [637d09143c](https://linux-hardware.org/?probe=637d09143c) | May 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a1cb5cae49](https://linux-hardware.org/?probe=a1cb5cae49) | May 11, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [6cd766b17e](https://linux-hardware.org/?probe=6cd766b17e) | May 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [17d57b61d7](https://linux-hardware.org/?probe=17d57b61d7) | May 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [a00d7ec568](https://linux-hardware.org/?probe=a00d7ec568) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [393b2da4bc](https://linux-hardware.org/?probe=393b2da4bc) | May 11, 2023 |
| Positivo      | J14GL11                     | Notebook    | [9594837399](https://linux-hardware.org/?probe=9594837399) | May 11, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d03175163f](https://linux-hardware.org/?probe=d03175163f) | May 11, 2023 |
| Unknown       | M-140BI3                    | Notebook    | [eb6507c151](https://linux-hardware.org/?probe=eb6507c151) | May 11, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [ceff5a622d](https://linux-hardware.org/?probe=ceff5a622d) | May 11, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [e826ca7941](https://linux-hardware.org/?probe=e826ca7941) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [d30d7d859b](https://linux-hardware.org/?probe=d30d7d859b) | May 11, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6b9e3d06b1](https://linux-hardware.org/?probe=6b9e3d06b1) | May 11, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [76f23f434d](https://linux-hardware.org/?probe=76f23f434d) | May 10, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [b93ef808c5](https://linux-hardware.org/?probe=b93ef808c5) | May 10, 2023 |
| Dell          | Latitude 5510               | Notebook    | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [cb4250603d](https://linux-hardware.org/?probe=cb4250603d) | May 10, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d9f5e85b9b](https://linux-hardware.org/?probe=d9f5e85b9b) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | Notebook    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| AOpen         | aA70Mx-VW R1.01 55DE8100... | Desktop     | [400b616f1c](https://linux-hardware.org/?probe=400b616f1c) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [036d26ffb3](https://linux-hardware.org/?probe=036d26ffb3) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ea1c5040a8](https://linux-hardware.org/?probe=ea1c5040a8) | May 10, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [64f08f10f3](https://linux-hardware.org/?probe=64f08f10f3) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [d21ef87b63](https://linux-hardware.org/?probe=d21ef87b63) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | Notebook    | [b98dfd1940](https://linux-hardware.org/?probe=b98dfd1940) | May 10, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [deecc1260f](https://linux-hardware.org/?probe=deecc1260f) | May 10, 2023 |
| Positivo      | Q432BP                      | Convertible | [dbf8652c6c](https://linux-hardware.org/?probe=dbf8652c6c) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | Notebook    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [a4a673b42a](https://linux-hardware.org/?probe=a4a673b42a) | May 09, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [deab607d5b](https://linux-hardware.org/?probe=deab607d5b) | May 09, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [9bd04974e8](https://linux-hardware.org/?probe=9bd04974e8) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [0985b52dee](https://linux-hardware.org/?probe=0985b52dee) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [b7fd2a3e2f](https://linux-hardware.org/?probe=b7fd2a3e2f) | May 09, 2023 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [2f0a5430a3](https://linux-hardware.org/?probe=2f0a5430a3) | May 09, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [378acd7874](https://linux-hardware.org/?probe=378acd7874) | May 09, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [534af3636c](https://linux-hardware.org/?probe=534af3636c) | May 09, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e63410f299](https://linux-hardware.org/?probe=e63410f299) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [96d3be3118](https://linux-hardware.org/?probe=96d3be3118) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [dfe5f362e2](https://linux-hardware.org/?probe=dfe5f362e2) | May 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [6c55bc2118](https://linux-hardware.org/?probe=6c55bc2118) | May 09, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [1f5654331d](https://linux-hardware.org/?probe=1f5654331d) | May 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [8f910a1997](https://linux-hardware.org/?probe=8f910a1997) | May 09, 2023 |
| HP            | 630                         | Notebook    | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | Notebook    | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [bae6aba4fb](https://linux-hardware.org/?probe=bae6aba4fb) | May 09, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ce04ace3b3](https://linux-hardware.org/?probe=ce04ace3b3) | May 09, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [e858474ff0](https://linux-hardware.org/?probe=e858474ff0) | May 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [dd221c51f9](https://linux-hardware.org/?probe=dd221c51f9) | May 09, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [eb9f5de2f5](https://linux-hardware.org/?probe=eb9f5de2f5) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [205b8a8ca7](https://linux-hardware.org/?probe=205b8a8ca7) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [249e9efecb](https://linux-hardware.org/?probe=249e9efecb) | May 08, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8bbe8f0a3f](https://linux-hardware.org/?probe=8bbe8f0a3f) | May 08, 2023 |
| Avell High... | A65 MOB                     | Notebook    | [d6c6781535](https://linux-hardware.org/?probe=d6c6781535) | May 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [7502ce9679](https://linux-hardware.org/?probe=7502ce9679) | May 08, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [631317f909](https://linux-hardware.org/?probe=631317f909) | May 08, 2023 |
| ASRock        | Z87 Pro4                    | Desktop     | [e3971068b6](https://linux-hardware.org/?probe=e3971068b6) | May 08, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e6ead6e953](https://linux-hardware.org/?probe=e6ead6e953) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| HP            | 86F3 00100                  | All in one  | [dc3ade850c](https://linux-hardware.org/?probe=dc3ade850c) | May 08, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [96c2411d79](https://linux-hardware.org/?probe=96c2411d79) | May 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [00df9b6bda](https://linux-hardware.org/?probe=00df9b6bda) | May 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e7f4395ed8](https://linux-hardware.org/?probe=e7f4395ed8) | May 08, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [d7b87b2b8c](https://linux-hardware.org/?probe=d7b87b2b8c) | May 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [76748da9cd](https://linux-hardware.org/?probe=76748da9cd) | May 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6097531bfc](https://linux-hardware.org/?probe=6097531bfc) | May 08, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [273bbe68d5](https://linux-hardware.org/?probe=273bbe68d5) | May 07, 2023 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [ce611516ec](https://linux-hardware.org/?probe=ce611516ec) | May 07, 2023 |
| Dell          | Precision 5510              | Notebook    | [9a4ba61d41](https://linux-hardware.org/?probe=9a4ba61d41) | May 07, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [69dfa20c09](https://linux-hardware.org/?probe=69dfa20c09) | May 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| 6.2.15-300.fc38.x86_64                                 | 222       | 18.05%  |
| 6.2.14-300.fc38.x86_64                                 | 151       | 12.28%  |
| 6.2.11-300.fc38.x86_64                                 | 132       | 10.73%  |
| 6.2.9-300.fc38.x86_64                                  | 129       | 10.49%  |
| 6.3.8-200.fc38.x86_64                                  | 117       | 9.51%   |
| 6.3.5-200.fc38.x86_64                                  | 74        | 6.02%   |
| 6.2.13-300.fc38.x86_64                                 | 72        | 5.85%   |
| 6.3.6-200.fc38.x86_64                                  | 61        | 4.96%   |
| 6.2.12-300.fc38.x86_64                                 | 57        | 4.63%   |
| 6.3.4-201.fc38.x86_64                                  | 50        | 4.07%   |
| 6.3.7-200.fc38.x86_64                                  | 47        | 3.82%   |
| 6.2.8-300.fc38.x86_64                                  | 14        | 1.14%   |
| 6.2.6-300.fc38.x86_64                                  | 11        | 0.89%   |
| 6.2.10-300.fc38.x86_64                                 | 10        | 0.81%   |
| 6.2.7-300.fc38.x86_64                                  | 7         | 0.57%   |
| 6.2.2-301.fc38.x86_64                                  | 6         | 0.49%   |
| 6.3.3-200.fc38.x86_64                                  | 5         | 0.41%   |
| 6.2.0-63.fc38.x86_64                                   | 4         | 0.33%   |
| 6.2.2-300.fc38.x86_64                                  | 3         | 0.24%   |
| 6.2.15-703.inttf.fc38.x86_64                           | 3         | 0.24%   |
| 6.4.0-0.rc4.334.vanilla.fc38.x86_64                    | 2         | 0.16%   |
| 6.2.5-300.fc38.x86_64                                  | 2         | 0.16%   |
| 6.2.11-703.inttf.fc38.x86_64                           | 2         | 0.16%   |
| 6.1.26-200.fc38.x86_64                                 | 2         | 0.16%   |
| 6.4.0-0.rc5.20230607gta4d7d701.342.vanilla.fc38.x86_64 | 1         | 0.08%   |
| 6.4.0-0.rc2.23.fc39.ppc64le                            | 1         | 0.08%   |
| 6.3.9-200.fc38.x86_64                                  | 1         | 0.08%   |
| 6.3.8-206.rog.fc38.x86_64                              | 1         | 0.08%   |
| 6.3.6-cb1.0.fc38.x86_64                                | 1         | 0.08%   |
| 6.3.3-cb1.0.fc38.x86_64                                | 1         | 0.08%   |
| 6.3.3-1.surface.fc38.x86_64                            | 1         | 0.08%   |
| 6.3.2-cbl1.0.fc38.x86_64                               | 1         | 0.08%   |
| 6.3.1-eupnea                                           | 1         | 0.08%   |
| 6.3.1-cb3.0.fc38.x86_64                                | 1         | 0.08%   |
| 6.3.1-350.vanilla.fc38.x86_64                          | 1         | 0.08%   |
| 6.3.1-200.fc38.x86_64                                  | 1         | 0.08%   |
| 6.3.0+                                                 | 1         | 0.08%   |
| 6.2.3-300.fc38.x86_64                                  | 1         | 0.08%   |
| 6.2.15-200.fc37.x86_64                                 | 1         | 0.08%   |
| 6.2.14-703.inttf.fc38.x86_64                           | 1         | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.2.15   | 226       | 18.39%  |
| 6.2.14   | 153       | 12.45%  |
| 6.2.11   | 134       | 10.9%   |
| 6.2.9    | 129       | 10.5%   |
| 6.3.8    | 118       | 9.6%    |
| 6.3.5    | 74        | 6.02%   |
| 6.2.13   | 72        | 5.86%   |
| 6.3.6    | 62        | 5.04%   |
| 6.2.12   | 57        | 4.64%   |
| 6.3.4    | 50        | 4.07%   |
| 6.3.7    | 47        | 3.82%   |
| 6.2.8    | 14        | 1.14%   |
| 6.2.10   | 12        | 0.98%   |
| 6.2.0    | 12        | 0.98%   |
| 6.2.6    | 11        | 0.9%    |
| 6.2.2    | 9         | 0.73%   |
| 6.3.3    | 7         | 0.57%   |
| 6.2.7    | 7         | 0.57%   |
| 6.1.0    | 5         | 0.41%   |
| 6.4.0    | 4         | 0.33%   |
| 6.3.1    | 4         | 0.33%   |
| 6.2.5    | 2         | 0.16%   |
| 6.1.26   | 2         | 0.16%   |
| 6.0.0    | 2         | 0.16%   |
| 6.3.9    | 1         | 0.08%   |
| 6.3.2    | 1         | 0.08%   |
| 6.3.0    | 1         | 0.08%   |
| 6.2.3    | 1         | 0.08%   |
| 6.2.1    | 1         | 0.08%   |
| 6.1.31   | 1         | 0.08%   |
| 6.1.18   | 1         | 0.08%   |
| 6.0.8    | 1         | 0.08%   |
| 6.0.7    | 1         | 0.08%   |
| 6.0.17   | 1         | 0.08%   |
| 6.0.12   | 1         | 0.08%   |
| 6.0.11   | 1         | 0.08%   |
| 5.19.7   | 1         | 0.08%   |
| 5.15.55  | 1         | 0.08%   |
| 5.11.18  | 1         | 0.08%   |
| 5.10.178 | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 805       | 67.42%  |
| 6.3     | 365       | 30.57%  |
| 6.1     | 9         | 0.75%   |
| 6.0     | 7         | 0.59%   |
| 6.4     | 4         | 0.34%   |
| 5.19    | 1         | 0.08%   |
| 5.15    | 1         | 0.08%   |
| 5.11    | 1         | 0.08%   |
| 5.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1148      | 99.74%  |
| aarch64 | 2         | 0.17%   |
| ppc64le | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 903       | 78.32%  |
| KDE5          | 162       | 14.05%  |
| Unknown       | 22        | 1.91%   |
| Cinnamon      | 17        | 1.47%   |
| XFCE          | 15        | 1.3%    |
| X-Cinnamon    | 9         | 0.78%   |
| MATE          | 5         | 0.43%   |
| GNOME Classic | 5         | 0.43%   |
| LXDE          | 3         | 0.26%   |
| sway          | 2         | 0.17%   |
| LXQt          | 2         | 0.17%   |
| i3            | 2         | 0.17%   |
| Hyprland      | 2         | 0.17%   |
| Budgie        | 2         | 0.17%   |
| KDE           | 1         | 0.09%   |
| Deepin        | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 924       | 79.72%  |
| X11     | 197       | 17%     |
| Tty     | 22        | 1.9%    |
| Unknown | 15        | 1.29%   |
| Xcb     | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 741       | 64.21%  |
| GDM     | 288       | 24.96%  |
| SDDM    | 74        | 6.41%   |
| LightDM | 47        | 4.07%   |
| LXDM    | 3         | 0.26%   |
| SLiM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 599       | 51.86%  |
| en_GB   | 71        | 6.15%   |
| pt_BR   | 63        | 5.45%   |
| ru_RU   | 56        | 4.85%   |
| de_DE   | 54        | 4.68%   |
| fr_FR   | 36        | 3.12%   |
| en_CA   | 31        | 2.68%   |
| en_AU   | 29        | 2.51%   |
| it_IT   | 20        | 1.73%   |
| pl_PL   | 18        | 1.56%   |
| es_ES   | 17        | 1.47%   |
| es_MX   | 14        | 1.21%   |
| es_CL   | 10        | 0.87%   |
| en_IN   | 10        | 0.87%   |
| es_AR   | 9         | 0.78%   |
| hu_HU   | 7         | 0.61%   |
| tr_TR   | 6         | 0.52%   |
| pt_PT   | 6         | 0.52%   |
| es_CO   | 6         | 0.52%   |
| de_AT   | 6         | 0.52%   |
| cs_CZ   | 6         | 0.52%   |
| zh_CN   | 5         | 0.43%   |
| fr_CA   | 5         | 0.43%   |
| en_DK   | 5         | 0.43%   |
| nl_NL   | 4         | 0.35%   |
| es_PE   | 4         | 0.35%   |
| en_NZ   | 4         | 0.35%   |
| de_CH   | 4         | 0.35%   |
| sk_SK   | 3         | 0.26%   |
| ru_UA   | 3         | 0.26%   |
| es_EC   | 3         | 0.26%   |
| C       | 3         | 0.26%   |
| Unknown | 3         | 0.26%   |
| zh_TW   | 2         | 0.17%   |
| sv_SE   | 2         | 0.17%   |
| nl_BE   | 2         | 0.17%   |
| id_ID   | 2         | 0.17%   |
| hr_HR   | 2         | 0.17%   |
| fi_FI   | 2         | 0.17%   |
| es_VE   | 2         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 935       | 80.95%  |
| BIOS | 220       | 19.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 965       | 83.77%  |
| Ext4    | 158       | 13.72%  |
| Xfs     | 22        | 1.91%   |
| Overlay | 4         | 0.35%   |
| Zfs     | 1         | 0.09%   |
| F2fs    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 721       | 62.48%  |
| GPT     | 405       | 35.1%   |
| MBR     | 28        | 2.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1056      | 91.67%  |
| Yes       | 96        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 982       | 85.17%  |
| Yes       | 171       | 14.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 230       | 19.98%  |
| ASUSTek Computer      | 185       | 16.07%  |
| Hewlett-Packard       | 150       | 13.03%  |
| Dell                  | 139       | 12.08%  |
| MSI                   | 72        | 6.26%   |
| Gigabyte Technology   | 69        | 5.99%   |
| Acer                  | 48        | 4.17%   |
| Apple                 | 37        | 3.21%   |
| ASRock                | 31        | 2.69%   |
| HUAWEI                | 18        | 1.56%   |
| Samsung Electronics   | 13        | 1.13%   |
| Unknown               | 13        | 1.13%   |
| Intel                 | 10        | 0.87%   |
| Google                | 10        | 0.87%   |
| Microsoft             | 8         | 0.7%    |
| Toshiba               | 7         | 0.61%   |
| Timi                  | 7         | 0.61%   |
| Sony                  | 5         | 0.43%   |
| AZW                   | 5         | 0.43%   |
| Positivo              | 4         | 0.35%   |
| Notebook              | 4         | 0.35%   |
| Itautec               | 4         | 0.35%   |
| TUXEDO                | 3         | 0.26%   |
| Razer                 | 3         | 0.26%   |
| Pegatron              | 3         | 0.26%   |
| Framework             | 3         | 0.26%   |
| AMI                   | 3         | 0.26%   |
| UNOWHY                | 2         | 0.17%   |
| Positivo Bahia - VAIO | 2         | 0.17%   |
| PC Specialist         | 2         | 0.17%   |
| Medion                | 2         | 0.17%   |
| MECHREVO              | 2         | 0.17%   |
| iRU                   | 2         | 0.17%   |
| Intel Client Systems  | 2         | 0.17%   |
| Huanan                | 2         | 0.17%   |
| HPE                   | 2         | 0.17%   |
| HONOR                 | 2         | 0.17%   |
| GPU Company           | 2         | 0.17%   |
| Fujitsu               | 2         | 0.17%   |
| Chuwi                 | 2         | 0.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 15        | 1.3%    |
| ASUS All Series                         | 5         | 0.43%   |
| Apple MacBookPro8,1                     | 5         | 0.43%   |
| MSI MS-7C37                             | 4         | 0.35%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 4         | 0.35%   |
| Dell XPS 13 9310                        | 4         | 0.35%   |
| Dell OptiPlex 7010                      | 4         | 0.35%   |
| Apple MacBookPro9,2                     | 4         | 0.35%   |
| MSI MS-7B89                             | 3         | 0.26%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS       | 3         | 0.26%   |
| Lenovo IdeaPad L340-15API 81LW          | 3         | 0.26%   |
| Lenovo IdeaPad 3 15ITL6 82H8            | 3         | 0.26%   |
| Itautec Infoway ST-4265                 | 3         | 0.26%   |
| HP Pavilion x2 Detachable               | 3         | 0.26%   |
| HP Notebook                             | 3         | 0.26%   |
| HP ENVY x360 Convertible 13-ay0xxx      | 3         | 0.26%   |
| Gigabyte X570 I AORUS PRO WIFI          | 3         | 0.26%   |
| Framework Laptop                        | 3         | 0.26%   |
| Dell XPS 13 9305                        | 3         | 0.26%   |
| Dell XPS 13 7390                        | 3         | 0.26%   |
| Dell Precision 7540                     | 3         | 0.26%   |
| Dell Latitude E7450                     | 3         | 0.26%   |
| Dell Latitude 7420                      | 3         | 0.26%   |
| Dell Latitude 5490                      | 3         | 0.26%   |
| Dell Inspiron 15 5510                   | 3         | 0.26%   |
| AZW SER                                 | 3         | 0.26%   |
| ASUS ROG Strix G513QY_G513QY            | 3         | 0.26%   |
| ASUS ROG STRIX B550-I GAMING            | 3         | 0.26%   |
| ASRock B450M Pro4                       | 3         | 0.26%   |
| Apple MacBookPro12,1                    | 3         | 0.26%   |
| Apple MacBookAir7,2                     | 3         | 0.26%   |
| Acer Nitro AN515-55                     | 3         | 0.26%   |
| Acer Nitro AN515-54                     | 3         | 0.26%   |
| Timi Redmi Book Pro 14 2022             | 2         | 0.17%   |
| Samsung 750QFG                          | 2         | 0.17%   |
| Samsung 730QCJ/730QCR                   | 2         | 0.17%   |
| Samsung 550XDA                          | 2         | 0.17%   |
| Positivo Bahia - VAIO VJFE43F11X-XXXXXX | 2         | 0.17%   |
| Notebook NV4xPZ                         | 2         | 0.17%   |
| MSI Prestige 15 A10SC                   | 2         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 109       | 9.47%   |
| Lenovo IdeaPad     | 46        | 4%      |
| ASUS ROG           | 42        | 3.65%   |
| Dell Latitude      | 36        | 3.13%   |
| HP Pavilion        | 35        | 3.04%   |
| Dell Inspiron      | 33        | 2.87%   |
| ASUS VivoBook      | 27        | 2.35%   |
| ASUS PRIME         | 27        | 2.35%   |
| Dell XPS           | 25        | 2.17%   |
| Acer Aspire        | 25        | 2.17%   |
| HP Laptop          | 18        | 1.56%   |
| ASUS TUF           | 18        | 1.56%   |
| Lenovo Legion      | 17        | 1.48%   |
| HP EliteBook       | 17        | 1.48%   |
| Dell OptiPlex      | 17        | 1.48%   |
| Lenovo Yoga        | 16        | 1.39%   |
| HP ENVY            | 15        | 1.3%    |
| Unknown            | 15        | 1.3%    |
| Dell Precision     | 14        | 1.22%   |
| Lenovo ThinkBook   | 11        | 0.96%   |
| ASUS ASUS          | 11        | 0.96%   |
| Acer Nitro         | 11        | 0.96%   |
| Lenovo IdeaPadFlex | 9         | 0.78%   |
| HP ProBook         | 9         | 0.78%   |
| Microsoft Surface  | 8         | 0.7%    |
| HP Compaq          | 8         | 0.7%    |
| Lenovo ThinkCentre | 7         | 0.61%   |
| Dell Vostro        | 7         | 0.61%   |
| ASUS Zenbook       | 7         | 0.61%   |
| HP OMEN            | 6         | 0.52%   |
| Toshiba Satellite  | 5         | 0.43%   |
| MSI Modern         | 5         | 0.43%   |
| HP ZBook           | 5         | 0.43%   |
| Gigabyte B550M     | 5         | 0.43%   |
| ASUS All           | 5         | 0.43%   |
| Apple MacBookPro9  | 5         | 0.43%   |
| Apple MacBookPro8  | 5         | 0.43%   |
| Acer Swift         | 5         | 0.43%   |
| MSI MS-7C37        | 4         | 0.35%   |
| HP Victus          | 4         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 172       | 14.94%  |
| 2020    | 150       | 13.03%  |
| 2022    | 146       | 12.68%  |
| 2019    | 125       | 10.86%  |
| 2018    | 114       | 9.9%    |
| 2017    | 72        | 6.26%   |
| 2012    | 58        | 5.04%   |
| 2013    | 48        | 4.17%   |
| 2014    | 43        | 3.74%   |
| 2015    | 42        | 3.65%   |
| 2023    | 40        | 3.48%   |
| 2016    | 40        | 3.48%   |
| 2011    | 40        | 3.48%   |
| 2010    | 29        | 2.52%   |
| 2009    | 12        | 1.04%   |
| 2008    | 9         | 0.78%   |
| 2007    | 4         | 0.35%   |
| 2006    | 4         | 0.35%   |
| Unknown | 3         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 691       | 60.03%  |
| Desktop        | 343       | 29.8%   |
| Convertible    | 60        | 5.21%   |
| Tablet         | 20        | 1.74%   |
| Mini pc        | 19        | 1.65%   |
| All in one     | 10        | 0.87%   |
| Server         | 7         | 0.61%   |
| System on chip | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 898       | 77.68%  |
| Enabled  | 258       | 22.32%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1138      | 98.87%  |
| Yes  | 13        | 1.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 295       | 25.54%  |
| 4.01-8.0        | 274       | 23.72%  |
| 8.01-16.0       | 219       | 18.96%  |
| 32.01-64.0      | 163       | 14.11%  |
| 3.01-4.0        | 91        | 7.88%   |
| 64.01-256.0     | 55        | 4.76%   |
| 24.01-32.0      | 41        | 3.55%   |
| 1.01-2.0        | 15        | 1.3%    |
| More than 256.0 | 1         | 0.09%   |
| 2.01-3.0        | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 368       | 30.72%  |
| 2.01-3.0   | 322       | 26.88%  |
| 3.01-4.0   | 293       | 24.46%  |
| 1.01-2.0   | 121       | 10.1%   |
| 8.01-16.0  | 70        | 5.84%   |
| 0.51-1.0   | 14        | 1.17%   |
| 16.01-24.0 | 7         | 0.58%   |
| 32.01-64.0 | 3         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 713       | 61.47%  |
| 2      | 297       | 25.6%   |
| 3      | 73        | 6.29%   |
| 4      | 42        | 3.62%   |
| 5      | 17        | 1.47%   |
| 6      | 9         | 0.78%   |
| 0      | 4         | 0.34%   |
| 10     | 2         | 0.17%   |
| 11     | 1         | 0.09%   |
| 8      | 1         | 0.09%   |
| 7      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 931       | 80.75%  |
| Yes       | 222       | 19.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 875       | 75.95%  |
| No        | 277       | 24.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 974       | 84.55%  |
| No        | 178       | 15.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 870       | 75.32%  |
| No        | 285       | 24.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 213       | 18.44%  |
| Brazil      | 90        | 7.79%   |
| Germany     | 81        | 7.01%   |
| Russia      | 61        | 5.28%   |
| Canada      | 48        | 4.16%   |
| France      | 41        | 3.55%   |
| Poland      | 36        | 3.12%   |
| Italy       | 35        | 3.03%   |
| India       | 35        | 3.03%   |
| Australia   | 32        | 2.77%   |
| UK          | 31        | 2.68%   |
| Netherlands | 30        | 2.6%    |
| Mexico      | 25        | 2.16%   |
| Turkey      | 19        | 1.65%   |
| Spain       | 18        | 1.56%   |
| Hungary     | 18        | 1.56%   |
| Chile       | 16        | 1.39%   |
| Switzerland | 15        | 1.3%    |
| Czechia     | 15        | 1.3%    |
| Austria     | 13        | 1.13%   |
| Finland     | 12        | 1.04%   |
| Belgium     | 12        | 1.04%   |
| Sweden      | 11        | 0.95%   |
| Romania     | 11        | 0.95%   |
| Portugal    | 11        | 0.95%   |
| Colombia    | 11        | 0.95%   |
| Belarus     | 11        | 0.95%   |
| Argentina   | 11        | 0.95%   |
| Norway      | 10        | 0.87%   |
| Thailand    | 8         | 0.69%   |
| Indonesia   | 8         | 0.69%   |
| Denmark     | 8         | 0.69%   |
| Singapore   | 7         | 0.61%   |
| Israel      | 7         | 0.61%   |
| Serbia      | 6         | 0.52%   |
| Greece      | 6         | 0.52%   |
| Croatia     | 6         | 0.52%   |
| China       | 6         | 0.52%   |
| Ukraine     | 5         | 0.43%   |
| Taiwan      | 5         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 17        | 1.45%   |
| Moscow         | 15        | 1.28%   |
| Sao Paulo      | 12        | 1.03%   |
| Helsinki       | 11        | 0.94%   |
| Berlin         | 11        | 0.94%   |
| Santiago       | 10        | 0.86%   |
| Minsk          | 9         | 0.77%   |
| Rio de Janeiro | 8         | 0.68%   |
| Mexico City    | 8         | 0.68%   |
| Budapest       | 8         | 0.68%   |
| Vienna         | 7         | 0.6%    |
| Singapore      | 7         | 0.6%    |
| Prague         | 7         | 0.6%    |
| Melbourne      | 7         | 0.6%    |
| Istanbul       | 7         | 0.6%    |
| Amsterdam      | 7         | 0.6%    |
| Warsaw         | 6         | 0.51%   |
| St Petersburg  | 6         | 0.51%   |
| Ottawa         | 6         | 0.51%   |
| Toronto        | 5         | 0.43%   |
| Seattle        | 5         | 0.43%   |
| Poznan         | 5         | 0.43%   |
| Paris          | 5         | 0.43%   |
| Palmas         | 5         | 0.43%   |
| New York       | 5         | 0.43%   |
| Montreal       | 5         | 0.43%   |
| Gdansk         | 5         | 0.43%   |
| Fortaleza      | 5         | 0.43%   |
| Delhi          | 5         | 0.43%   |
| Brussels       | 5         | 0.43%   |
| Bengaluru      | 5         | 0.43%   |
| Bangkok        | 5         | 0.43%   |
| Atlanta        | 5         | 0.43%   |
| Winnipeg       | 4         | 0.34%   |
| Sofia          | 4         | 0.34%   |
| San José      | 4         | 0.34%   |
| Porto Alegre   | 4         | 0.34%   |
| Munich         | 4         | 0.34%   |
| Milan          | 4         | 0.34%   |
| Miami          | 4         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 329       | 449    | 19.7%   |
| SanDisk                        | 158       | 175    | 9.46%   |
| WDC                            | 140       | 183    | 8.38%   |
| Seagate                        | 132       | 169    | 7.9%    |
| Kingston                       | 102       | 111    | 6.11%   |
| Toshiba                        | 87        | 95     | 5.21%   |
| Unknown                        | 68        | 82     | 4.07%   |
| SK hynix                       | 63        | 67     | 3.77%   |
| Intel                          | 61        | 75     | 3.65%   |
| Crucial                        | 58        | 70     | 3.47%   |
| Micron Technology              | 51        | 53     | 3.05%   |
| Phison Electronics             | 27        | 37     | 1.62%   |
| A-DATA Technology              | 27        | 31     | 1.62%   |
| KIOXIA                         | 26        | 29     | 1.56%   |
| China                          | 24        | 28     | 1.44%   |
| Micron/Crucial Technology      | 23        | 24     | 1.38%   |
| Apple                          | 20        | 29     | 1.2%    |
| Silicon Motion                 | 18        | 20     | 1.08%   |
| Kingston Technology Company    | 16        | 18     | 0.96%   |
| Hitachi                        | 16        | 22     | 0.96%   |
| HGST                           | 14        | 14     | 0.84%   |
| SPCC                           | 11        | 11     | 0.66%   |
| Netac                          | 11        | 12     | 0.66%   |
| ADATA Technology               | 11        | 11     | 0.66%   |
| Patriot                        | 9         | 11     | 0.54%   |
| PNY                            | 8         | 10     | 0.48%   |
| Phison                         | 7         | 8      | 0.42%   |
| JMicron Technology             | 7         | 9      | 0.42%   |
| Intenso                        | 6         | 6      | 0.36%   |
| Union Memory (Shenzhen)        | 5         | 6      | 0.3%    |
| Union Memory                   | 5         | 5      | 0.3%    |
| Solid State Storage Technology | 5         | 5      | 0.3%    |
| SABRENT                        | 5         | 5      | 0.3%    |
| Gigabyte Technology            | 5         | 7      | 0.3%    |
| Transcend                      | 4         | 4      | 0.24%   |
| Solid State Storage            | 4         | 4      | 0.24%   |
| Realtek Semiconductor          | 4         | 7      | 0.24%   |
| MAXIO Technology (Hangzhou)    | 4         | 4      | 0.24%   |
| LITEON                         | 4         | 4      | 0.24%   |
| Lexar                          | 4         | 4      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 71        | 3.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 46        | 2.56%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 22        | 1.22%   |
| Kingston SA400S37240G 240GB SSD                       | 21        | 1.17%   |
| Unknown MMC Card  64GB                                | 19        | 1.06%   |
| Kingston SA400S37480G 480GB SSD                       | 17        | 0.95%   |
| Samsung SSD 980 1TB                                   | 16        | 0.89%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 16        | 0.89%   |
| Intel SSD 660P Series 512GB                           | 16        | 0.89%   |
| Unknown MMC Card  32GB                                | 15        | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                        | 14        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 14        | 0.78%   |
| Unknown MMC Card  128GB                               | 13        | 0.72%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 13        | 0.72%   |
| Crucial CT500MX500SSD1 500GB                          | 13        | 0.72%   |
| Phison E12 NVMe Controller 1TB                        | 12        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 11        | 0.61%   |
| Samsung SSD 870 EVO 1TB                               | 11        | 0.61%   |
| Samsung SSD 860 EVO 1TB                               | 11        | 0.61%   |
| Samsung SSD 860 EVO 500GB                             | 10        | 0.56%   |
| Samsung SSD 850 EVO 250GB                             | 10        | 0.56%   |
| Kingston SA400S37120G 120GB SSD                       | 10        | 0.56%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 9         | 0.5%    |
| Toshiba XG6 NVMe SSD Controller 2TB                   | 8         | 0.45%   |
| Toshiba DT01ACA100 1TB                                | 8         | 0.45%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 500GB       | 8         | 0.45%   |
| Sandisk WD Black SN850 1TB                            | 8         | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                           | 8         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 7         | 0.39%   |
| Toshiba MQ04ABF100 1TB                                | 7         | 0.39%   |
| Toshiba MQ01ABD100 1TB                                | 7         | 0.39%   |
| SK hynix BC511 256GB                                  | 7         | 0.39%   |
| Crucial CT240BX500SSD1 240GB                          | 7         | 0.39%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                  | 6         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6         | 0.33%   |
| Seagate ST1000DM010-2EP102 1TB                        | 6         | 0.33%   |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB          | 6         | 0.33%   |
| Samsung SSD 870 EVO 500GB                             | 6         | 0.33%   |
| Samsung SSD 860 EVO 250GB                             | 6         | 0.33%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                      | 6         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 157    | 36.13%  |
| WDC                 | 104       | 140    | 30.06%  |
| Toshiba             | 57        | 61     | 16.47%  |
| Hitachi             | 16        | 22     | 4.62%   |
| HGST                | 14        | 14     | 4.05%   |
| Samsung Electronics | 12        | 12     | 3.47%   |
| Apple               | 7         | 8      | 2.02%   |
| Unknown             | 3         | 3      | 0.87%   |
| QNAP                | 2         | 2      | 0.58%   |
| USB3.0              | 1         | 1      | 0.29%   |
| USB                 | 1         | 1      | 0.29%   |
| SAGE                | 1         | 1      | 0.29%   |
| Maxtor              | 1         | 1      | 0.29%   |
| LaCie               | 1         | 1      | 0.29%   |
| ASMT                | 1         | 2      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 122       | 162    | 23.28%  |
| Kingston            | 75        | 82     | 14.31%  |
| Crucial             | 56        | 66     | 10.69%  |
| SanDisk             | 44        | 48     | 8.4%    |
| WDC                 | 29        | 30     | 5.53%   |
| China               | 24        | 28     | 4.58%   |
| A-DATA Technology   | 22        | 26     | 4.2%    |
| Intel               | 16        | 20     | 3.05%   |
| Toshiba             | 12        | 13     | 2.29%   |
| SPCC                | 11        | 11     | 2.1%    |
| Patriot             | 9         | 11     | 1.72%   |
| Micron Technology   | 9         | 9      | 1.72%   |
| PNY                 | 8         | 10     | 1.53%   |
| Apple               | 8         | 9      | 1.53%   |
| Netac               | 6         | 6      | 1.15%   |
| LITEON              | 4         | 4      | 0.76%   |
| Lexar               | 4         | 4      | 0.76%   |
| KingSpec            | 4         | 4      | 0.76%   |
| GOODRAM             | 4         | 7      | 0.76%   |
| Gigabyte Technology | 4         | 6      | 0.76%   |
| Transcend           | 3         | 3      | 0.57%   |
| Advantech           | 3         | 3      | 0.57%   |
| TO Exter            | 2         | 2      | 0.38%   |
| SK hynix            | 2         | 2      | 0.38%   |
| Ramsta              | 2         | 2      | 0.38%   |
| Kimtigo             | 2         | 2      | 0.38%   |
| Hewlett-Packard     | 2         | 2      | 0.38%   |
| Apacer              | 2         | 3      | 0.38%   |
| AMD                 | 2         | 2      | 0.38%   |
| Acer                | 2         | 4      | 0.38%   |
| XrayDisk            | 1         | 1      | 0.19%   |
| Union Memory        | 1         | 1      | 0.19%   |
| Team                | 1         | 1      | 0.19%   |
| TAMMUZ              | 1         | 1      | 0.19%   |
| SSSTC               | 1         | 1      | 0.19%   |
| Smartbuy            | 1         | 1      | 0.19%   |
| Smart               | 1         | 1      | 0.19%   |
| Seagate             | 1         | 1      | 0.19%   |
| Pichau              | 1         | 1      | 0.19%   |
| Phison              | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 672       | 869    | 44.07%  |
| SSD     | 458       | 615    | 30.03%  |
| HDD     | 304       | 426    | 19.93%  |
| MMC     | 65        | 78     | 4.26%   |
| Unknown | 26        | 30     | 1.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 667       | 856    | 47.75%  |
| SATA | 610       | 1009   | 43.66%  |
| MMC  | 65        | 78     | 4.65%   |
| SAS  | 55        | 75     | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 414       | 582    | 53.28%  |
| 0.51-1.0   | 255       | 315    | 32.82%  |
| 1.01-2.0   | 66        | 81     | 8.49%   |
| 3.01-4.0   | 20        | 24     | 2.57%   |
| 4.01-10.0  | 12        | 19     | 1.54%   |
| 2.01-3.0   | 7         | 8      | 0.9%    |
| 10.01-20.0 | 3         | 12     | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 254       | 21.8%   |
| 251-500        | 222       | 19.06%  |
| 1001-2000      | 185       | 15.88%  |
| 101-250        | 151       | 12.96%  |
| 1-20           | 90        | 7.73%   |
| Unknown        | 84        | 7.21%   |
| More than 3000 | 71        | 6.09%   |
| 2001-3000      | 47        | 4.03%   |
| 51-100         | 41        | 3.52%   |
| 21-50          | 20        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 389       | 33.11%  |
| 21-50          | 203       | 17.28%  |
| 101-250        | 134       | 11.4%   |
| 51-100         | 131       | 11.15%  |
| 251-500        | 102       | 8.68%   |
| Unknown        | 84        | 7.15%   |
| 501-1000       | 73        | 6.21%   |
| 1001-2000      | 37        | 3.15%   |
| More than 3000 | 14        | 1.19%   |
| 2001-3000      | 8         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD              | 2         | 2      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB               | 2         | 2      | 4.55%   |
| Intel SSDSC2CT120A3 120GB                     | 2         | 3      | 4.55%   |
| Crucial CT120M500SSD1 120GB                   | 2         | 5      | 4.55%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                | 1         | 1      | 2.27%   |
| WDC WD5000BPVT-75HXZT1 500GB                  | 1         | 1      | 2.27%   |
| WDC WD5000AADS-00S9B0 500GB                   | 1         | 1      | 2.27%   |
| WDC WD20EZRX-00D8PB0 2TB                      | 1         | 1      | 2.27%   |
| WDC WD10JPVT-60A1YT0 1TB                      | 1         | 1      | 2.27%   |
| WDC WD1002FAEX-00Y9A0 1TB                     | 1         | 1      | 2.27%   |
| Toshiba MQ02ABD100H 1TB                       | 1         | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 2.27%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 2.27%   |
| SSSTC CVB-8D128-HP 128GB SSD                  | 1         | 1      | 2.27%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD         | 1         | 1      | 2.27%   |
| Seagate ST9250827AS 250GB                     | 1         | 1      | 2.27%   |
| Seagate ST9160412AS 160GB                     | 1         | 1      | 2.27%   |
| Seagate ST3750528AS 752GB                     | 1         | 1      | 2.27%   |
| Seagate ST3500630NS 500GB                     | 1         | 1      | 2.27%   |
| Seagate ST3500418AS 500GB                     | 1         | 2      | 2.27%   |
| Seagate ST31000524AS 1TB                      | 1         | 1      | 2.27%   |
| Seagate ST2000VX000-1CU164 2TB                | 1         | 1      | 2.27%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 1      | 2.27%   |
| Seagate ST1000LX015-1U7172 1TB                | 1         | 1      | 2.27%   |
| Seagate ST1000DX002-2DV162 1TB                | 1         | 1      | 2.27%   |
| SanDisk SSD PLUS 480GB                        | 1         | 1      | 2.27%   |
| SanDisk SSD PLUS 120 GB                       | 1         | 1      | 2.27%   |
| SanDisk SD8SBAT256G1122 256GB SSD             | 1         | 1      | 2.27%   |
| Samsung Electronics SSD 840 PRO Series 256GB  | 1         | 1      | 2.27%   |
| Samsung Electronics SSD 840 EVO 250GB         | 1         | 1      | 2.27%   |
| Samsung Electronics HD322GJ 320GB             | 1         | 1      | 2.27%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD | 1         | 1      | 2.27%   |
| Kingston SA400S37120G 120GB SSD               | 1         | 1      | 2.27%   |
| Intenso SSD 240GB                             | 1         | 1      | 2.27%   |
| Intel SSDSC2KG019T7R 2TB                      | 1         | 1      | 2.27%   |
| Intel SSDSC2BF240A5L 240GB                    | 1         | 1      | 2.27%   |
| Hitachi HTS545025B9SA02 250GB                 | 1         | 1      | 2.27%   |
| HGST HTS541010A9E680 1TB                      | 1         | 1      | 2.27%   |
| A-DATA Technology SX900 256GB SSD             | 1         | 1      | 2.27%   |
| A-DATA Technology SU650 960GB SSD             | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 26.83%  |
| WDC                 | 6         | 8      | 14.63%  |
| Intel               | 4         | 5      | 9.76%   |
| Toshiba             | 3         | 3      | 7.32%   |
| SanDisk             | 3         | 3      | 7.32%   |
| Samsung Electronics | 3         | 3      | 7.32%   |
| Crucial             | 2         | 5      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| SSSTC               | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Intenso             | 1         | 1      | 2.44%   |
| Hitachi             | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 52.38%  |
| WDC                 | 4         | 5      | 19.05%  |
| Toshiba             | 3         | 3      | 14.29%  |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 51.22%  |
| SSD  | 20        | 25     | 48.78%  |

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
| Detected | 792       | 1364   | 65.51%  |
| Works    | 379       | 605    | 31.35%  |
| Malfunc  | 38        | 49     | 3.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 617       | 38.61%  |
| AMD                                     | 241       | 15.08%  |
| Samsung Electronics                     | 227       | 14.21%  |
| SanDisk                                 | 122       | 7.63%   |
| SK hynix                                | 61        | 3.82%   |
| Kingston Technology Company             | 44        | 2.75%   |
| Micron Technology                       | 42        | 2.63%   |
| Phison Electronics                      | 32        | 2%      |
| Micron/Crucial Technology               | 24        | 1.5%    |
| KIOXIA                                  | 23        | 1.44%   |
| Toshiba America Info Systems            | 22        | 1.38%   |
| Silicon Motion                          | 20        | 1.25%   |
| ASMedia Technology                      | 19        | 1.19%   |
| ADATA Technology                        | 16        | 1%      |
| Marvell Technology Group                | 14        | 0.88%   |
| Solid State Storage Technology          | 10        | 0.63%   |
| Union Memory (Shenzhen)                 | 9         | 0.56%   |
| Seagate Technology                      | 7         | 0.44%   |
| Netac Technology                        | 5         | 0.31%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.31%   |
| LSI Logic / Symbios Logic               | 5         | 0.31%   |
| JMicron Technology                      | 5         | 0.31%   |
| Realtek Semiconductor                   | 4         | 0.25%   |
| Apple                                   | 4         | 0.25%   |
| Solidigm                                | 3         | 0.19%   |
| Yangtze Memory Technologies             | 2         | 0.13%   |
| Silicon Image                           | 2         | 0.13%   |
| Shenzhen Longsys Electronics            | 2         | 0.13%   |
| Nvidia                                  | 2         | 0.13%   |
| Adaptec                                 | 2         | 0.13%   |
| VIA Technologies                        | 1         | 0.06%   |
| ULi Electronics                         | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| PMC-Sierra                              | 1         | 0.06%   |
| Lenovo                                  | 1         | 0.06%   |
| INNOGRIT                                | 1         | 0.06%   |
| Broadcom / LSI                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 168       | 9.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 84        | 4.83%   |
| Samsung NVMe SSD Controller 980                                                | 62        | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 60        | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 59        | 3.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 53        | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 36        | 2.07%   |
| AMD 500 Series Chipset SATA Controller                                         | 36        | 2.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 1.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 32        | 1.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 28        | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                         | 27        | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 24        | 1.38%   |
| Micron NVMe Storage Controller                                                 | 22        | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 21        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 21        | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21        | 1.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 18        | 1.04%   |
| SanDisk Non-Volatile memory controller                                         | 17        | 0.98%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 17        | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                        | 17        | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                            | 16        | 0.92%   |
| Intel SSD 660P Series                                                          | 16        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 0.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 15        | 0.86%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 14        | 0.81%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 14        | 0.81%   |
| Phison E12 NVMe Controller                                                     | 13        | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 13        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 12        | 0.69%   |
| Intel Non-Volatile memory controller                                           | 12        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 741       | 47.02%  |
| NVMe | 663       | 42.07%  |
| RAID | 120       | 7.61%   |
| IDE  | 46        | 2.92%   |
| SAS  | 4         | 0.25%   |
| SCSI | 2         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 803       | 69.77%  |
| AMD                      | 344       | 29.89%  |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.09%   |
| CentaurHauls             | 1         | 0.09%   |
| ARM                      | 1         | 0.09%   |
| Unknown                  | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 2.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 1.39%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 15        | 1.3%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 1.3%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 1.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 0.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 11        | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.87%   |
| Intel 12th Gen Core i7-12700H                 | 10        | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.78%   |
| Intel 12th Gen Core i7-1260P                  | 9         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 8         | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 8         | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.7%    |
| Intel 12th Gen Core i7-1255U                  | 8         | 0.7%    |
| AMD Ryzen 5 5600U with Radeon Graphics        | 8         | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 8         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.61%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 7         | 0.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 0.61%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 0.61%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 0.61%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 7         | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.52%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 6         | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.52%   |
| Intel 12th Gen Core i5-12500H                 | 6         | 0.52%   |
| Intel 12th Gen Core i5-1240P                  | 6         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 226       | 19.64%  |
| Intel Core i7           | 196       | 17.03%  |
| Other                   | 194       | 16.85%  |
| AMD Ryzen 5             | 123       | 10.69%  |
| AMD Ryzen 7             | 100       | 8.69%   |
| Intel Core i3           | 59        | 5.13%   |
| AMD Ryzen 9             | 42        | 3.65%   |
| Intel Celeron           | 34        | 2.95%   |
| Intel Xeon              | 22        | 1.91%   |
| Intel Atom              | 18        | 1.56%   |
| AMD Ryzen 3             | 14        | 1.22%   |
| Intel Pentium           | 12        | 1.04%   |
| Intel Core 2 Duo        | 12        | 1.04%   |
| AMD FX                  | 11        | 0.96%   |
| Intel Pentium Silver    | 10        | 0.87%   |
| Intel Core i9           | 10        | 0.87%   |
| AMD Ryzen 7 PRO         | 7         | 0.61%   |
| AMD Ryzen 5 PRO         | 7         | 0.61%   |
| Intel Core 2 Quad       | 6         | 0.52%   |
| AMD Phenom II X4        | 5         | 0.43%   |
| AMD A6                  | 5         | 0.43%   |
| AMD Ryzen Threadripper  | 4         | 0.35%   |
| AMD A8                  | 4         | 0.35%   |
| AMD A10                 | 4         | 0.35%   |
| Intel Pentium Dual-Core | 2         | 0.17%   |
| Intel Pentium Dual      | 2         | 0.17%   |
| Intel Genuine           | 2         | 0.17%   |
| Intel Core m5           | 2         | 0.17%   |
| AMD Phenom II X2        | 2         | 0.17%   |
| AMD Athlon              | 2         | 0.17%   |
| Intel Pentium Gold      | 1         | 0.09%   |
| Intel Core m3           | 1         | 0.09%   |
| Intel Core M            | 1         | 0.09%   |
| Intel Core 2 Extreme    | 1         | 0.09%   |
| Intel Core 2            | 1         | 0.09%   |
| AMD Phenom II X6        | 1         | 0.09%   |
| AMD Opteron             | 1         | 0.09%   |
| AMD E2                  | 1         | 0.09%   |
| AMD E1                  | 1         | 0.09%   |
| AMD Athlon II X2        | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 413       | 35.88%  |
| 2      | 281       | 24.41%  |
| 6      | 178       | 15.46%  |
| 8      | 157       | 13.64%  |
| 12     | 50        | 4.34%   |
| 14     | 23        | 2%      |
| 10     | 21        | 1.82%   |
| 16     | 18        | 1.56%   |
| 24     | 4         | 0.35%   |
| 3      | 4         | 0.35%   |
| 36     | 1         | 0.09%   |
| 18     | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1145      | 99.48%  |
| 2      | 6         | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 932       | 80.97%  |
| 1      | 218       | 18.94%  |
| 4      | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1148      | 99.74%  |
| 64-bit         | 2         | 0.17%   |
| Unknown        | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 813       | 70.57%  |
| 0x0a50000c | 38        | 3.3%    |
| 0x0a50000d | 25        | 2.17%   |
| 0x08108109 | 23        | 2%      |
| 0x08701021 | 20        | 1.74%   |
| 0x08608103 | 20        | 1.74%   |
| 0x0a20120a | 19        | 1.65%   |
| 0x0a404102 | 16        | 1.39%   |
| 0x08600106 | 16        | 1.39%   |
| 0x0a601203 | 14        | 1.22%   |
| 0x0800820d | 14        | 1.22%   |
| 0x08108102 | 11        | 0.95%   |
| 0x0a201016 | 8         | 0.69%   |
| 0x08600104 | 8         | 0.69%   |
| 0x0a404101 | 6         | 0.52%   |
| 0x08701030 | 6         | 0.52%   |
| 0x06000822 | 6         | 0.52%   |
| 0x010000c8 | 6         | 0.52%   |
| 0x06006705 | 5         | 0.43%   |
| 0x0a201025 | 4         | 0.35%   |
| 0x08608104 | 3         | 0.26%   |
| 0x08608102 | 3         | 0.26%   |
| 0x08600103 | 3         | 0.26%   |
| 0x0800820c | 3         | 0.26%   |
| 0x0600611a | 3         | 0.26%   |
| 0x06001116 | 3         | 0.26%   |
| 0x906ea    | 2         | 0.17%   |
| 0x806e9    | 2         | 0.17%   |
| 0x806c1    | 2         | 0.17%   |
| 0x0a50000b | 2         | 0.17%   |
| 0x0a201205 | 2         | 0.17%   |
| 0x0a201204 | 2         | 0.17%   |
| 0x0a201009 | 2         | 0.17%   |
| 0x08101016 | 2         | 0.17%   |
| 0x0810100b | 2         | 0.17%   |
| 0x08101007 | 2         | 0.17%   |
| 0x08001138 | 2         | 0.17%   |
| 0x08001137 | 2         | 0.17%   |
| 0x06001119 | 2         | 0.17%   |
| 0x06000629 | 2         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 211       | 18.33%  |
| Zen 3            | 109       | 9.47%   |
| Alderlake Hybrid | 86        | 7.47%   |
| Unknown          | 77        | 6.69%   |
| TigerLake        | 75        | 6.52%   |
| Haswell          | 69        | 5.99%   |
| IvyBridge        | 61        | 5.3%    |
| Zen 2            | 57        | 4.95%   |
| Zen+             | 51        | 4.43%   |
| Skylake          | 44        | 3.82%   |
| Icelake          | 40        | 3.48%   |
| SandyBridge      | 39        | 3.39%   |
| CometLake        | 39        | 3.39%   |
| Silvermont       | 26        | 2.26%   |
| Westmere         | 23        | 2%      |
| Goldmont plus    | 21        | 1.82%   |
| Broadwell        | 21        | 1.82%   |
| Penryn           | 16        | 1.39%   |
| Piledriver       | 14        | 1.22%   |
| Zen              | 13        | 1.13%   |
| K10              | 10        | 0.87%   |
| Excavator        | 10        | 0.87%   |
| Core             | 10        | 0.87%   |
| Tremont          | 5         | 0.43%   |
| Goldmont         | 5         | 0.43%   |
| Nehalem          | 4         | 0.35%   |
| Puma             | 3         | 0.26%   |
| Bulldozer        | 3         | 0.26%   |
| Bonnell          | 3         | 0.26%   |
| Jaguar           | 2         | 0.17%   |
| Gracemont        | 2         | 0.17%   |
| K8 Hammer        | 1         | 0.09%   |
| K10 Llano        | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 658       | 47.61%  |
| AMD                        | 362       | 26.19%  |
| Nvidia                     | 354       | 25.62%  |
| Matrox Electronics Systems | 5         | 0.36%   |
| ASPEED Technology          | 2         | 0.14%   |
| Zhaoxin                    | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 70        | 4.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47        | 3.33%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 37        | 2.62%   |
| Intel UHD Graphics 620                                                                   | 36        | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 2.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 2.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 2.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 2.05%   |
| AMD Lucienne                                                                             | 28        | 1.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.98%   |
| Intel HD Graphics 620                                                                    | 27        | 1.91%   |
| AMD Renoir                                                                               | 27        | 1.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 23        | 1.63%   |
| AMD Rembrandt [Radeon 680M]                                                              | 23        | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 1.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 21        | 1.49%   |
| Intel HD Graphics 630                                                                    | 19        | 1.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 1.06%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 15        | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.99%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 0.99%   |
| AMD Barcelo                                                                              | 14        | 0.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.92%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 13        | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 12        | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 12        | 0.85%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.85%   |
| AMD Raphael                                                                              | 12        | 0.85%   |
| Intel HD Graphics 530                                                                    | 11        | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 10        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 461       | 39.91%  |
| 1 x AMD        | 285       | 24.68%  |
| Intel + Nvidia | 162       | 14.03%  |
| 1 x Nvidia     | 150       | 12.99%  |
| AMD + Nvidia   | 39        | 3.38%   |
| Intel + AMD    | 22        | 1.9%    |
| 2 x AMD        | 16        | 1.39%   |
| 2 x Intel      | 5         | 0.43%   |
| 1 x Matrox     | 5         | 0.43%   |
| 2 x Nvidia     | 4         | 0.35%   |
| Other          | 3         | 0.26%   |
| 1 x ASPEED     | 2         | 0.17%   |
| 1 x Zhaoxin    | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 975       | 84.34%  |
| Proprietary | 149       | 12.89%  |
| Unknown     | 32        | 2.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 621       | 53.53%  |
| 0.01-0.5   | 127       | 10.95%  |
| 1.01-2.0   | 106       | 9.14%   |
| 3.01-4.0   | 91        | 7.84%   |
| 7.01-8.0   | 79        | 6.81%   |
| 0.51-1.0   | 59        | 5.09%   |
| 8.01-16.0  | 36        | 3.1%    |
| 5.01-6.0   | 27        | 2.33%   |
| 2.01-3.0   | 7         | 0.6%    |
| 16.01-24.0 | 7         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 165       | 12.55%  |
| AU Optronics            | 148       | 11.25%  |
| Samsung Electronics     | 126       | 9.58%   |
| Chimei Innolux          | 126       | 9.58%   |
| LG Display              | 98        | 7.45%   |
| Goldstar                | 95        | 7.22%   |
| Dell                    | 84        | 6.39%   |
| Sharp                   | 34        | 2.59%   |
| Apple                   | 34        | 2.59%   |
| Hewlett-Packard         | 31        | 2.36%   |
| Acer                    | 26        | 1.98%   |
| Lenovo                  | 25        | 1.9%    |
| Philips                 | 24        | 1.83%   |
| ASUSTek Computer        | 23        | 1.75%   |
| AOC                     | 23        | 1.75%   |
| PANDA                   | 22        | 1.67%   |
| Ancor Communications    | 21        | 1.6%    |
| BenQ                    | 20        | 1.52%   |
| CSO                     | 19        | 1.44%   |
| InfoVision              | 14        | 1.06%   |
| Gigabyte Technology     | 11        | 0.84%   |
| Chi Mei Optoelectronics | 10        | 0.76%   |
| Iiyama                  | 9         | 0.68%   |
| ViewSonic               | 8         | 0.61%   |
| Mi                      | 7         | 0.53%   |
| Sceptre Tech            | 6         | 0.46%   |
| MSI                     | 6         | 0.46%   |
| LG Philips              | 6         | 0.46%   |
| Unknown                 | 5         | 0.38%   |
| Fujitsu Siemens         | 5         | 0.38%   |
| Sony                    | 4         | 0.3%    |
| HUAWEI                  | 4         | 0.3%    |
| Vizio                   | 3         | 0.23%   |
| Vestel Elektronik       | 3         | 0.23%   |
| Toshiba                 | 3         | 0.23%   |
| Hitachi                 | 3         | 0.23%   |
| GDH                     | 3         | 0.23%   |
| Belinea                 | 3         | 0.23%   |
| WST                     | 2         | 0.15%   |
| Unknown (XXX)           | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.45%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 5         | 0.37%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 5         | 0.37%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 5         | 0.37%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 5         | 0.37%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.3%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.3%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 4         | 0.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4         | 0.3%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 4         | 0.3%    |
| BOE LCD Monitor BOE09DE 1920x1080 309x174mm 14.0-inch                 | 4         | 0.3%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 0.3%    |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 4         | 0.3%    |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 4         | 0.3%    |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 4         | 0.3%    |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4         | 0.3%    |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 3         | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.22%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 3         | 0.22%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4156 1920x1080 294x165mm 13.3-inch | 3         | 0.22%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 587       | 47.57%  |
| 1366x768 (WXGA)    | 134       | 10.86%  |
| 2560x1440 (QHD)    | 107       | 8.67%   |
| 3840x2160 (4K)     | 99        | 8.02%   |
| 1920x1200 (WUXGA)  | 36        | 2.92%   |
| 2560x1600          | 31        | 2.51%   |
| 1600x900 (HD+)     | 30        | 2.43%   |
| 1680x1050 (WSXGA+) | 26        | 2.11%   |
| 3440x1440          | 25        | 2.03%   |
| 1440x900 (WXGA+)   | 22        | 1.78%   |
| 1280x1024 (SXGA)   | 20        | 1.62%   |
| 1280x800 (WXGA)    | 18        | 1.46%   |
| 2560x1080          | 16        | 1.3%    |
| 2880x1800          | 13        | 1.05%   |
| 2256x1504          | 7         | 0.57%   |
| 2160x1440          | 6         | 0.49%   |
| 1360x768           | 5         | 0.41%   |
| 3840x2400          | 4         | 0.32%   |
| 3840x1600          | 3         | 0.24%   |
| 3840x1080          | 3         | 0.24%   |
| 2880x1620          | 3         | 0.24%   |
| 2736x1824          | 3         | 0.24%   |
| 2288x1287          | 3         | 0.24%   |
| 2160x1350          | 3         | 0.24%   |
| 2048x1152          | 3         | 0.24%   |
| 3840x1100          | 2         | 0.16%   |
| 3456x2160          | 2         | 0.16%   |
| 3200x2000          | 2         | 0.16%   |
| 3200x1800 (QHD+)   | 2         | 0.16%   |
| 2520x1680          | 2         | 0.16%   |
| 2240x1400          | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1600x1200          | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 800x1280           | 1         | 0.08%   |
| 3840x2560          | 1         | 0.08%   |
| 3120x2080          | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2304x1440          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 331       | 25.15%  |
| 13      | 166       | 12.61%  |
| 14      | 147       | 11.17%  |
| 27      | 132       | 10.03%  |
| 24      | 88        | 6.69%   |
| 23      | 57        | 4.33%   |
| 21      | 55        | 4.18%   |
| 31      | 46        | 3.5%    |
| 34      | 38        | 2.89%   |
| 17      | 32        | 2.43%   |
| 19      | 24        | 1.82%   |
| 16      | 24        | 1.82%   |
| 12      | 21        | 1.6%    |
| 22      | 20        | 1.52%   |
| 20      | 18        | 1.37%   |
| 18      | 18        | 1.37%   |
| 84      | 13        | 0.99%   |
| 11      | 10        | 0.76%   |
| 32      | 8         | 0.61%   |
| 72      | 6         | 0.46%   |
| 28      | 6         | 0.46%   |
| 10      | 6         | 0.46%   |
| 54      | 5         | 0.38%   |
| 48      | 5         | 0.38%   |
| 40      | 5         | 0.38%   |
| Unknown | 5         | 0.38%   |
| 35      | 4         | 0.3%    |
| 26      | 4         | 0.3%    |
| 142     | 3         | 0.23%   |
| 65      | 3         | 0.23%   |
| 37      | 3         | 0.23%   |
| 25      | 3         | 0.23%   |
| 63      | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 42      | 2         | 0.15%   |
| 49      | 1         | 0.08%   |
| 38      | 1         | 0.08%   |
| 33      | 1         | 0.08%   |
| 7       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 560       | 43.44%  |
| 501-600        | 249       | 19.32%  |
| 201-300        | 140       | 10.86%  |
| 401-500        | 117       | 9.08%   |
| 601-700        | 68        | 5.28%   |
| 701-800        | 47        | 3.65%   |
| 351-400        | 47        | 3.65%   |
| 1501-2000      | 19        | 1.47%   |
| 1001-1500      | 18        | 1.4%    |
| 801-900        | 13        | 1.01%   |
| Unknown        | 5         | 0.39%   |
| More than 2000 | 3         | 0.23%   |
| 901-1000       | 2         | 0.16%   |
| 1-100          | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 894       | 77%     |
| 16/10 | 166       | 14.3%   |
| 21/9  | 43        | 3.7%    |
| 3/2   | 23        | 1.98%   |
| 5/4   | 18        | 1.55%   |
| 4/3   | 5         | 0.43%   |
| 6/5   | 3         | 0.26%   |
| 32/9  | 3         | 0.26%   |
| 1.00  | 3         | 0.26%   |
| 3.40  | 2         | 0.17%   |
| 0.67  | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 334       | 25.54%  |
| 81-90          | 234       | 17.89%  |
| 201-250        | 173       | 13.23%  |
| 301-350        | 136       | 10.4%   |
| 351-500        | 100       | 7.65%   |
| 71-80          | 74        | 5.66%   |
| 151-200        | 63        | 4.82%   |
| More than 1000 | 37        | 2.83%   |
| 251-300        | 29        | 2.22%   |
| 121-130        | 24        | 1.83%   |
| 111-120        | 21        | 1.61%   |
| 141-150        | 20        | 1.53%   |
| 61-70          | 18        | 1.38%   |
| 501-1000       | 14        | 1.07%   |
| 51-60          | 13        | 0.99%   |
| 41-50          | 5         | 0.38%   |
| 91-100         | 5         | 0.38%   |
| Unknown        | 5         | 0.38%   |
| 131-140        | 2         | 0.15%   |
| 1-40           | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 451       | 35.6%   |
| 51-100        | 333       | 26.28%  |
| 101-120       | 255       | 20.13%  |
| 161-240       | 157       | 12.39%  |
| More than 240 | 41        | 3.24%   |
| 1-50          | 25        | 1.97%   |
| Unknown       | 5         | 0.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 882       | 76.23%  |
| 2     | 206       | 17.8%   |
| 0     | 41        | 3.54%   |
| 3     | 26        | 2.25%   |
| 4     | 2         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 640       | 37.98%  |
| Realtek Semiconductor                  | 596       | 35.37%  |
| Qualcomm Atheros                       | 98        | 5.82%   |
| Broadcom                               | 90        | 5.34%   |
| MediaTek                               | 67        | 3.98%   |
| TP-Link                                | 18        | 1.07%   |
| ASIX Electronics                       | 15        | 0.89%   |
| Broadcom Limited                       | 11        | 0.65%   |
| Ralink Technology                      | 10        | 0.59%   |
| Ralink                                 | 10        | 0.59%   |
| Microsoft                              | 10        | 0.59%   |
| Lenovo                                 | 10        | 0.59%   |
| Aquantia                               | 10        | 0.59%   |
| Samsung Electronics                    | 9         | 0.53%   |
| Marvell Technology Group               | 8         | 0.47%   |
| DisplayLink                            | 8         | 0.47%   |
| Qualcomm Atheros Communications        | 7         | 0.42%   |
| Xiaomi                                 | 6         | 0.36%   |
| Sierra Wireless                        | 6         | 0.36%   |
| Qualcomm                               | 5         | 0.3%    |
| D-Link                                 | 5         | 0.3%    |
| OPPO Electronics                       | 4         | 0.24%   |
| NetGear                                | 3         | 0.18%   |
| Mellanox Technologies                  | 3         | 0.18%   |
| ICS Advent                             | 3         | 0.18%   |
| Dell                                   | 3         | 0.18%   |
| Wilocity                               | 2         | 0.12%   |
| Nvidia                                 | 2         | 0.12%   |
| Motorola PCS                           | 2         | 0.12%   |
| Ericsson Business Mobile Networks      | 2         | 0.12%   |
| ASUSTek Computer                       | 2         | 0.12%   |
| WEMOS.CC                               | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Sitecom Europe                         | 1         | 0.06%   |
| Quectel Wireless Solutions             | 1         | 0.06%   |
| Qualcomm Technologies                  | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Microchip Technology                   | 1         | 0.06%   |
| MCS                                    | 1         | 0.06%   |
| JMicron Technology                     | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 387       | 19.32%  |
| Intel Wi-Fi 6 AX200                                               | 87        | 4.34%   |
| Intel Wi-Fi 6 AX201                                               | 64        | 3.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 48        | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 45        | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 43        | 2.15%   |
| Intel Wireless 8265 / 8275                                        | 43        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 37        | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 34        | 1.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 1.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 33        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 1.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 30        | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 29        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 24        | 1.2%    |
| Intel Wireless 7265                                               | 23        | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 22        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 21        | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 20        | 1%      |
| Intel Wireless 7260                                               | 20        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 1%      |
| Intel I211 Gigabit Network Connection                             | 19        | 0.95%   |
| Intel Wireless 8260                                               | 17        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 17        | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 16        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 16        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.75%   |
| Intel Wireless 3165                                               | 14        | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 12        | 0.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 12        | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 11        | 0.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 10        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 552       | 54.12%  |
| Realtek Semiconductor                 | 162       | 15.88%  |
| Qualcomm Atheros                      | 81        | 7.94%   |
| Broadcom                              | 71        | 6.96%   |
| MediaTek                              | 66        | 6.47%   |
| TP-Link                               | 15        | 1.47%   |
| Ralink Technology                     | 10        | 0.98%   |
| Ralink                                | 10        | 0.98%   |
| Broadcom Limited                      | 9         | 0.88%   |
| Microsoft                             | 8         | 0.78%   |
| Qualcomm Atheros Communications       | 7         | 0.69%   |
| Sierra Wireless                       | 6         | 0.59%   |
| Qualcomm                              | 3         | 0.29%   |
| NetGear                               | 3         | 0.29%   |
| Marvell Technology Group              | 3         | 0.29%   |
| Wilocity                              | 2         | 0.2%    |
| Dell                                  | 2         | 0.2%    |
| D-Link                                | 2         | 0.2%    |
| ASUSTek Computer                      | 2         | 0.2%    |
| Sitecom Europe                        | 1         | 0.1%    |
| Quectel Wireless Solutions            | 1         | 0.1%    |
| Qualcomm Technologies                 | 1         | 0.1%    |
| Belkin Components                     | 1         | 0.1%    |
| AVM                                   | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 87        | 8.5%    |
| Intel Wi-Fi 6 AX201                                            | 64        | 6.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 48        | 4.69%   |
| Intel Wireless 8265 / 8275                                     | 43        | 4.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 37        | 3.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 33        | 3.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 30        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 2.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 28        | 2.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 24        | 2.34%   |
| Intel Wireless 7265                                            | 23        | 2.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 22        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 21        | 2.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 1.95%   |
| Intel Wireless 7260                                            | 20        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 20        | 1.95%   |
| Intel Wireless 8260                                            | 17        | 1.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 17        | 1.66%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 16        | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 16        | 1.56%   |
| Intel Wireless 3165                                            | 14        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 1.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 12        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 1.07%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 10        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.98%   |
| Intel Wireless-AC 9260                                         | 8         | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 8         | 0.78%   |
| Realtek 802.11ac NIC                                           | 7         | 0.68%   |
| Intel Alder Lake-U CNVi: Wireless-AC                           | 7         | 0.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 7         | 0.68%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 6         | 0.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 0.59%   |
| Sierra Wireless EM7455                                         | 5         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 512       | 54.24%  |
| Intel                                  | 275       | 29.13%  |
| Broadcom                               | 37        | 3.92%   |
| Qualcomm Atheros                       | 24        | 2.54%   |
| ASIX Electronics                       | 15        | 1.59%   |
| Lenovo                                 | 10        | 1.06%   |
| Aquantia                               | 10        | 1.06%   |
| Samsung Electronics                    | 8         | 0.85%   |
| DisplayLink                            | 8         | 0.85%   |
| Xiaomi                                 | 6         | 0.64%   |
| Marvell Technology Group               | 5         | 0.53%   |
| OPPO Electronics                       | 4         | 0.42%   |
| TP-Link                                | 3         | 0.32%   |
| Mellanox Technologies                  | 3         | 0.32%   |
| ICS Advent                             | 3         | 0.32%   |
| D-Link                                 | 3         | 0.32%   |
| Qualcomm                               | 2         | 0.21%   |
| Nvidia                                 | 2         | 0.21%   |
| Microsoft                              | 2         | 0.21%   |
| Broadcom Limited                       | 2         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.11%   |
| Motorola PCS                           | 1         | 0.11%   |
| MediaTek                               | 1         | 0.11%   |
| JMicron Technology                     | 1         | 0.11%   |
| IBM                                    | 1         | 0.11%   |
| HMD Global                             | 1         | 0.11%   |
| Google                                 | 1         | 0.11%   |
| Apple                                  | 1         | 0.11%   |
| 3Com                                   | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 387       | 40.02%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 45        | 4.65%   |
| Realtek RTL8125 2.5GbE Controller                                   | 43        | 4.45%   |
| Intel Ethernet Controller I225-V                                    | 34        | 3.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 33        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 32        | 3.31%   |
| Intel I211 Gigabit Network Connection                               | 19        | 1.96%   |
| Intel Ethernet Connection I217-LM                                   | 16        | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                               | 15        | 1.55%   |
| ASIX AX88179 Gigabit Ethernet                                       | 14        | 1.45%   |
| Intel Ethernet Connection I219-LM                                   | 10        | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                | 10        | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 10        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                | 9         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                | 9         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 8         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                               | 8         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 8         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 7         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                               | 7         | 0.72%   |
| Intel Ethernet Connection (14) I219-V                               | 7         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 6         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                            | 6         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 5         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 5         | 0.52%   |
| Intel Ethernet Connection I217-V                                    | 5         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                | 5         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                               | 5         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                | 5         | 0.52%   |
| Intel Ethernet Connection (16) I219-V                               | 5         | 0.52%   |
| Intel Ethernet Connection (16) I219-LM                              | 5         | 0.52%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 4         | 0.41%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 4         | 0.41%   |
| Intel Ethernet Connection I218-LM                                   | 4         | 0.41%   |
| Intel Ethernet Connection (11) I219-LM                              | 4         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                               | 4         | 0.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                    | 4         | 0.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 3         | 0.31%   |
| Realtek Killer E3000 2.5GbE Controller                              | 3         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 975       | 52.5%   |
| Ethernet | 870       | 46.85%  |
| Modem    | 10        | 0.54%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 776       | 63.97%  |
| Ethernet | 437       | 36.03%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 585       | 50.78%  |
| 1     | 499       | 43.32%  |
| 3     | 32        | 2.78%   |
| 0     | 24        | 2.08%   |
| 4     | 9         | 0.78%   |
| 5     | 2         | 0.17%   |
| 6     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 823       | 71.13%  |
| Yes  | 334       | 28.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 492       | 55.72%  |
| Realtek Semiconductor           | 98        | 11.1%   |
| Foxconn / Hon Hai               | 44        | 4.98%   |
| Qualcomm Atheros Communications | 42        | 4.76%   |
| IMC Networks                    | 40        | 4.53%   |
| Broadcom                        | 35        | 3.96%   |
| Apple                           | 32        | 3.62%   |
| Cambridge Silicon Radio         | 26        | 2.94%   |
| Lite-On Technology              | 15        | 1.7%    |
| MediaTek                        | 12        | 1.36%   |
| Dell                            | 6         | 0.68%   |
| ASUSTek Computer                | 6         | 0.68%   |
| Realtek                         | 5         | 0.57%   |
| USI                             | 4         | 0.45%   |
| Hewlett-Packard                 | 4         | 0.45%   |
| TP-Link                         | 3         | 0.34%   |
| Toshiba                         | 3         | 0.34%   |
| Opticis                         | 3         | 0.34%   |
| Marvell Semiconductor           | 3         | 0.34%   |
| Foxconn International           | 3         | 0.34%   |
| Unknown                         | 2         | 0.23%   |
| Smart Modular Technologies      | 1         | 0.11%   |
| Ralink                          | 1         | 0.11%   |
| Fujitsu                         | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 127       | 14.38%  |
| Intel Bluetooth wireless interface                  | 107       | 12.12%  |
| Intel AX200 Bluetooth                               | 86        | 9.74%   |
| Realtek Bluetooth Radio                             | 81        | 9.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 65        | 7.36%   |
| Intel Bluetooth Device                              | 43        | 4.87%   |
| Intel AX210 Bluetooth                               | 30        | 3.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 3.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 2.94%   |
| IMC Networks Wireless_Device                        | 18        | 2.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 1.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 1.7%    |
| Apple Bluetooth Host Controller                     | 15        | 1.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 1.59%   |
| IMC Networks Bluetooth Radio                        | 14        | 1.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 13        | 1.47%   |
| Apple Bluetooth USB Host Controller                 | 13        | 1.47%   |
| MediaTek Wireless_Device                            | 12        | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 1.02%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.02%   |
| IMC Networks Bluetooth Device                       | 7         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.68%   |
| Realtek Bluetooth Radio                             | 5         | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.57%   |
| USI Bluetooth Device                                | 4         | 0.45%   |
| Lite-On Wireless_Device                             | 4         | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.45%   |
| TP-Link UB500 Adapter                               | 3         | 0.34%   |
| Opticis Bluetooth Radio                             | 3         | 0.34%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.34%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.34%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.34%   |
| Broadcom BCM2045A0                                  | 3         | 0.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.23%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 771       | 46.03%  |
| AMD                                          | 397       | 23.7%   |
| Nvidia                                       | 274       | 16.36%  |
| C-Media Electronics                          | 32        | 1.91%   |
| Logitech                                     | 19        | 1.13%   |
| Realtek Semiconductor                        | 14        | 0.84%   |
| ASUSTek Computer                             | 13        | 0.78%   |
| Lenovo                                       | 12        | 0.72%   |
| JMTek                                        | 10        | 0.6%    |
| Kingston Technology                          | 8         | 0.48%   |
| SteelSeries ApS                              | 6         | 0.36%   |
| Razer USA                                    | 6         | 0.36%   |
| Generalplus Technology                       | 6         | 0.36%   |
| Creative Technology                          | 6         | 0.36%   |
| Micro Star International                     | 5         | 0.3%    |
| GN Netcom                                    | 5         | 0.3%    |
| Texas Instruments                            | 4         | 0.24%   |
| Scarlett                                     | 4         | 0.24%   |
| Samson Technologies                          | 4         | 0.24%   |
| Hewlett-Packard                              | 4         | 0.24%   |
| Focusrite-Novation                           | 4         | 0.24%   |
| Creative Labs                                | 4         | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.18%   |
| RODE Microphones                             | 3         | 0.18%   |
| Microsoft                                    | 3         | 0.18%   |
| FIFINE Microphones                           | 3         | 0.18%   |
| Corsair                                      | 3         | 0.18%   |
| Yamaha                                       | 2         | 0.12%   |
| Sony                                         | 2         | 0.12%   |
| Plantronics                                  | 2         | 0.12%   |
| JBL                                          | 2         | 0.12%   |
| Dell                                         | 2         | 0.12%   |
| DCMT Technology                              | 2         | 0.12%   |
| Blue Microphones                             | 2         | 0.12%   |
| BEHRINGER International                      | 2         | 0.12%   |
| Zhaoxin                                      | 1         | 0.06%   |
| XMOS                                         | 1         | 0.06%   |
| Weltrend Semiconductor                       | 1         | 0.06%   |
| Vitana                                       | 1         | 0.06%   |
| VIA Technologies                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 195       | 9.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 111       | 5.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 94        | 4.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 75        | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 67        | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 62        | 3.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 56        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 52        | 2.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 51        | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 42        | 2.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 36        | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 1.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 31        | 1.53%   |
| Nvidia GA104 High Definition Audio Controller                              | 29        | 1.43%   |
| Intel Comet Lake PCH cAVS                                                  | 29        | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 29        | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 26        | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26        | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 26        | 1.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 1.28%   |
| Intel 200 Series PCH HD Audio                                              | 23        | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                              | 22        | 1.09%   |
| Nvidia Audio device                                                        | 22        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 22        | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22        | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 21        | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 20        | 0.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 0.99%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 0.99%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20        | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 0.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 19        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 18        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 16        | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 14        | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 13        | 0.64%   |
| Realtek Semiconductor USB Audio                                            | 12        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 125       | 24.04%  |
| SK hynix            | 86        | 16.54%  |
| Micron Technology   | 71        | 13.65%  |
| Kingston            | 46        | 8.85%   |
| Crucial             | 36        | 6.92%   |
| Corsair             | 28        | 5.38%   |
| Unknown             | 25        | 4.81%   |
| G.Skill             | 20        | 3.85%   |
| A-DATA Technology   | 14        | 2.69%   |
| Ramaxel Technology  | 12        | 2.31%   |
| Smart               | 7         | 1.35%   |
| Teikon              | 6         | 1.15%   |
| Unknown             | 5         | 0.96%   |
| Unknown (ABCD)      | 4         | 0.77%   |
| Team                | 4         | 0.77%   |
| Nanya Technology    | 3         | 0.58%   |
| Elpida              | 3         | 0.58%   |
| Qumo                | 2         | 0.38%   |
| Apacer              | 2         | 0.38%   |
| AMD                 | 2         | 0.38%   |
| 4ea5                | 2         | 0.38%   |
| V-GeN               | 1         | 0.19%   |
| Unknown (0x0E9D)    | 1         | 0.19%   |
| Transcend           | 1         | 0.19%   |
| Timetec             | 1         | 0.19%   |
| Silicon Power       | 1         | 0.19%   |
| PUSKILL             | 1         | 0.19%   |
| PNY                 | 1         | 0.19%   |
| Patriot             | 1         | 0.19%   |
| Neo Forza           | 1         | 0.19%   |
| Lexar               | 1         | 0.19%   |
| GOODRAM             | 1         | 0.19%   |
| GIGA-BYTE           | 1         | 0.19%   |
| ff                  | 1         | 0.19%   |
| EVGA                | 1         | 0.19%   |
| CSX                 | 1         | 0.19%   |
| Avant               | 1         | 0.19%   |
| 89450000830B        | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.1%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 1.1%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.92%   |
| Unknown                                                          | 5         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.73%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s              | 4         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.73%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.55%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 3         | 0.55%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.55%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.55%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 3         | 0.55%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 3         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.55%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 3         | 0.55%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 3         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.37%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.37%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.37%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s             | 2         | 0.37%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM DDR5 4800MT/s           | 2         | 0.37%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 252       | 56.88%  |
| DDR3    | 84        | 18.96%  |
| LPDDR4  | 30        | 6.77%   |
| DDR5    | 24        | 5.42%   |
| LPDDR3  | 19        | 4.29%   |
| LPDDR5  | 16        | 3.61%   |
| DDR2    | 8         | 1.81%   |
| Unknown | 5         | 1.13%   |
| SDRAM   | 4         | 0.9%    |
| DDR     | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 252       | 56.25%  |
| DIMM         | 121       | 27.01%  |
| Row Of Chips | 66        | 14.73%  |
| Unknown      | 5         | 1.12%   |
| Chip         | 4         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 203       | 42.38%  |
| 4096  | 104       | 21.71%  |
| 16384 | 92        | 19.21%  |
| 2048  | 43        | 8.98%   |
| 32768 | 28        | 5.85%   |
| 1024  | 9         | 1.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 131       | 27.35%  |
| 2667    | 65        | 13.57%  |
| 1600    | 60        | 12.53%  |
| 2400    | 32        | 6.68%   |
| 2133    | 25        | 5.22%   |
| 4267    | 19        | 3.97%   |
| 6400    | 17        | 3.55%   |
| 4800    | 17        | 3.55%   |
| 3600    | 15        | 3.13%   |
| 1333    | 13        | 2.71%   |
| 1867    | 10        | 2.09%   |
| 1334    | 8         | 1.67%   |
| 667     | 6         | 1.25%   |
| 3800    | 5         | 1.04%   |
| 3266    | 5         | 1.04%   |
| 1866    | 4         | 0.84%   |
| 1067    | 4         | 0.84%   |
| 800     | 4         | 0.84%   |
| 4266    | 3         | 0.63%   |
| 3534    | 3         | 0.63%   |
| 3400    | 3         | 0.63%   |
| 5200    | 2         | 0.42%   |
| 3000    | 2         | 0.42%   |
| 2800    | 2         | 0.42%   |
| 2666    | 2         | 0.42%   |
| 1639    | 2         | 0.42%   |
| 1400    | 2         | 0.42%   |
| 1066    | 2         | 0.42%   |
| 400     | 2         | 0.42%   |
| Unknown | 2         | 0.42%   |
| 12800   | 1         | 0.21%   |
| 8400    | 1         | 0.21%   |
| 6000    | 1         | 0.21%   |
| 5800    | 1         | 0.21%   |
| 5600    | 1         | 0.21%   |
| 3933    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 3666    | 1         | 0.21%   |
| 3334    | 1         | 0.21%   |
| 1800    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 7         | 53.85%  |
| Seiko Epson        | 3         | 23.08%  |
| Brother Industries | 2         | 15.38%  |
| Dymo-CoStar        | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2860 Series                                            | 1         | 7.69%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 7.69%   |
| Seiko Epson L120 Series                                               | 1         | 7.69%   |
| HP LaserJet Professional P1102w                                       | 1         | 7.69%   |
| HP LaserJet 1020                                                      | 1         | 7.69%   |
| HP LaserJet 1010                                                      | 1         | 7.69%   |
| HP ENVY Inspire 7200 series                                           | 1         | 7.69%   |
| HP ENVY 5000 series                                                   | 1         | 7.69%   |
| HP DeskJet 3700 series                                                | 1         | 7.69%   |
| HP Deskjet 2050 J510                                                  | 1         | 7.69%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 1         | 7.69%   |
| Brother HL-2130 series                                                | 1         | 7.69%   |
| Brother HL-1440 Laser Printer                                         | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1         | 33.33%  |
| Canon CanoScan LiDE 210               | 1         | 33.33%  |
| Canon CanoScan 4400F                  | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 130       | 16.39%  |
| IMC Networks                           | 88        | 11.1%   |
| Microdia                               | 65        | 8.2%    |
| Quanta                                 | 59        | 7.44%   |
| Logitech                               | 59        | 7.44%   |
| Realtek Semiconductor                  | 46        | 5.8%    |
| Bison Electronics                      | 46        | 5.8%    |
| Sunplus Innovation Technology          | 35        | 4.41%   |
| Acer                                   | 35        | 4.41%   |
| Apple                                  | 32        | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.28%   |
| Luxvisions Innotech Limited            | 23        | 2.9%    |
| Syntek                                 | 20        | 2.52%   |
| Sonix Technology                       | 19        | 2.4%    |
| Lite-On Technology                     | 13        | 1.64%   |
| SunplusIT                              | 11        | 1.39%   |
| Microsoft                              | 11        | 1.39%   |
| Suyin                                  | 9         | 1.13%   |
| Alcor Micro                            | 6         | 0.76%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.5%    |
| Samsung Electronics                    | 4         | 0.5%    |
| Silicon Motion                         | 3         | 0.38%   |
| USB Camera                             | 2         | 0.25%   |
| Trust                                  | 2         | 0.25%   |
| ShineTech                              | 2         | 0.25%   |
| Ricoh                                  | 2         | 0.25%   |
| Razer USA                              | 2         | 0.25%   |
| Primax Electronics                     | 2         | 0.25%   |
| LG Electronics                         | 2         | 0.25%   |
| Lenovo                                 | 2         | 0.25%   |
| KYE Systems (Mouse Systems)            | 2         | 0.25%   |
| Google                                 | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| AVerMedia Technologies                 | 2         | 0.25%   |
| ARC International                      | 2         | 0.25%   |
| 2M UVC CAMERA                          | 2         | 0.25%   |
| Unknown                                | 2         | 0.25%   |
| ZOOM                                   | 1         | 0.13%   |
| XHT-211220-ZW                          | 1         | 0.13%   |
| Unknown (3730304231385631394831)       | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 45        | 5.63%   |
| Microdia Integrated_Webcam_HD                                              | 39        | 4.88%   |
| IMC Networks Integrated Camera                                             | 32        | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                                          | 29        | 3.63%   |
| Realtek Integrated_Webcam_HD                                               | 20        | 2.5%    |
| Acer Integrated Camera                                                     | 19        | 2.38%   |
| Bison Integrated Camera                                                    | 16        | 2%      |
| Syntek Integrated Camera                                                   | 15        | 1.88%   |
| Quanta HD User Facing                                                      | 13        | 1.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 12        | 1.5%    |
| Sonix USB2.0 FHD UVC WebCam                                                | 10        | 1.25%   |
| Quanta HP Wide Vision HD Camera                                            | 10        | 1.25%   |
| Logitech HD Pro Webcam C920                                                | 10        | 1.25%   |
| Chicony HD WebCam                                                          | 10        | 1.25%   |
| Apple FaceTime HD Camera                                                   | 10        | 1.25%   |
| Chicony Integrated Camera (1280x720@30)                                    | 9         | 1.13%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 8         | 1%      |
| Sunplus Integrated_Webcam_HD                                               | 7         | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera                              | 7         | 0.88%   |
| Logitech Webcam C270                                                       | 7         | 0.88%   |
| Lite-On Integrated Camera                                                  | 7         | 0.88%   |
| Chicony HP Wide Vision HD Camera                                           | 7         | 0.88%   |
| Bison Integrated RGB Camera                                                | 7         | 0.88%   |
| Acer HD Webcam                                                             | 7         | 0.88%   |
| Logitech HD Webcam C525                                                    | 6         | 0.75%   |
| Chicony HP TrueVision HD Camera                                            | 6         | 0.75%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.63%   |
| Quanta HP HD Camera                                                        | 5         | 0.63%   |
| Quanta ACER HD User Facing                                                 | 5         | 0.63%   |
| Microdia Integrated_Webcam_FHD                                             | 5         | 0.63%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 5         | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 5         | 0.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 0.63%   |
| Chicony Integrated IR Camera                                               | 5         | 0.63%   |
| Chicony HD User Facing                                                     | 5         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 5         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 5         | 0.63%   |
| Bison SunplusIT Integrated Camera                                          | 5         | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                                        | 5         | 0.63%   |
| Apple Built-in iSight                                                      | 5         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 58        | 30.21%  |
| Shenzhen Goodix Technology         | 46        | 23.96%  |
| Validity Sensors                   | 39        | 20.31%  |
| Elan Microelectronics              | 20        | 10.42%  |
| Upek                               | 8         | 4.17%   |
| LighTuning Technology              | 7         | 3.65%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 3.13%   |
| AuthenTec                          | 4         | 2.08%   |
| Samsung Electronics                | 3         | 1.56%   |
| STMicroelectronics                 | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 30        | 15.63%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 9.9%    |
| Elan ELAN:ARM-M4                                                           | 13        | 6.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 5.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 5.73%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 4.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 3.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 3.13%   |
| Synaptics WBDI                                                             | 5         | 2.6%    |
| Synaptics UWP WBDI                                                         | 5         | 2.6%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.6%    |
| Elan ELAN:Fingerprint                                                      | 5         | 2.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.08%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 2.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 2.08%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 1.56%   |
| Validity Sensors VFS491                                                    | 3         | 1.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.56%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.04%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.04%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.04%   |
| Synaptics  WBDI                                                            | 2         | 1.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.04%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 1.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.04%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.52%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.52%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.52%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.52%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.52%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.52%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 52.54%  |
| Alcor Micro           | 15        | 25.42%  |
| Lenovo                | 4         | 6.78%   |
| Upek                  | 3         | 5.08%   |
| O2 Micro              | 2         | 3.39%   |
| Gemalto (was Gemplus) | 2         | 3.39%   |
| Yubico.com            | 1         | 1.69%   |
| BIT4ID                | 1         | 1.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 16        | 27.12%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 25.42%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 11.86%  |
| Broadcom 5880                                                                | 5         | 8.47%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.78%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.08%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 5.08%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 3.39%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.69%   |
| BIT4ID miniLector EVO                                                        | 1         | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 757       | 65.2%   |
| 1     | 325       | 27.99%  |
| 2     | 70        | 6.03%   |
| 3     | 5         | 0.43%   |
| 8     | 1         | 0.09%   |
| 6     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 189       | 38.81%  |
| Graphics card            | 122       | 25.05%  |
| Multimedia controller    | 62        | 12.73%  |
| Net/wireless             | 49        | 10.06%  |
| Camera                   | 14        | 2.87%   |
| Chipcard                 | 11        | 2.26%   |
| Communication controller | 9         | 1.85%   |
| Sound                    | 8         | 1.64%   |
| Unassigned class         | 6         | 1.23%   |
| Card reader              | 5         | 1.03%   |
| Storage                  | 4         | 0.82%   |
| Bluetooth                | 4         | 0.82%   |
| Net/ethernet             | 2         | 0.41%   |
| Storage/nvme             | 1         | 0.21%   |
| Modem                    | 1         | 0.21%   |

