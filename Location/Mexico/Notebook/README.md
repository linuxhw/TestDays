Linux in Mexico - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

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

Total: 2372

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L735              | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| Sony          | VPCEG10EL                   | [8271942cc2](https://linux-hardware.org/?probe=8271942cc2) | Sep 30, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Acer          | Aspire E1-531               | [6b981869d7](https://linux-hardware.org/?probe=6b981869d7) | Sep 27, 2023 |
| Sony          | VPCEG10EL                   | [7bfbe9b21d](https://linux-hardware.org/?probe=7bfbe9b21d) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | [d47b59c89b](https://linux-hardware.org/?probe=d47b59c89b) | Sep 27, 2023 |
| Toshiba       | dynabook T350/46BW          | [26ffaa1c0f](https://linux-hardware.org/?probe=26ffaa1c0f) | Sep 27, 2023 |
| Acer          | Nitro AN515-44              | [0ba9157463](https://linux-hardware.org/?probe=0ba9157463) | Sep 27, 2023 |
| HP            | Pavilion 14                 | [a7589d8c93](https://linux-hardware.org/?probe=a7589d8c93) | Sep 26, 2023 |
| HP            | Pavilion 14                 | [1aed6aba04](https://linux-hardware.org/?probe=1aed6aba04) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| Dell          | Latitude E5470              | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| HP            | Laptop 14-cm0xxx            | [2af47d0dca](https://linux-hardware.org/?probe=2af47d0dca) | Sep 24, 2023 |
| GPU Compan... | GWNR71517                   | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| Dell          | Inspiron 1464               | [026e1e3391](https://linux-hardware.org/?probe=026e1e3391) | Sep 21, 2023 |
| Valve         | Jupiter                     | [2b2966eb3d](https://linux-hardware.org/?probe=2b2966eb3d) | Sep 21, 2023 |
| Dell          | Inspiron 1464               | [bdb084e4a8](https://linux-hardware.org/?probe=bdb084e4a8) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| HP            | ProBook 6475b               | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| HP            | Dragonfly Pro               | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | Inspiron 1464               | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [361c6cb056](https://linux-hardware.org/?probe=361c6cb056) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [4ff9edf944](https://linux-hardware.org/?probe=4ff9edf944) | Sep 12, 2023 |
| Dell          | XPS 15 9530                 | [26b3fd07ae](https://linux-hardware.org/?probe=26b3fd07ae) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Dell          | Precision 7520              | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| ASUSTek       | G750JW                      | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| Unknown       | W1415A                      | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Google        | Pirika                      | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Dell          | Latitude 5480               | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E5450              | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Apple         | MacBookPro13,1              | [54f48be7f6](https://linux-hardware.org/?probe=54f48be7f6) | Sep 06, 2023 |
| Google        | Pirika                      | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Acer          | Aspire E1-531               | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| HP            | 240 G3                      | [24381b91f7](https://linux-hardware.org/?probe=24381b91f7) | Sep 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [6b895a5320](https://linux-hardware.org/?probe=6b895a5320) | Sep 03, 2023 |
| Valve         | Jupiter                     | [9e037b28bc](https://linux-hardware.org/?probe=9e037b28bc) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | [88d1350771](https://linux-hardware.org/?probe=88d1350771) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [de36e26c21](https://linux-hardware.org/?probe=de36e26c21) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | [fe660fb390](https://linux-hardware.org/?probe=fe660fb390) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| HP            | ProBook 6460b               | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Dell          | Inspiron 1464               | [1020c99eec](https://linux-hardware.org/?probe=1020c99eec) | Aug 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Google        | Treeya                      | [396f71a402](https://linux-hardware.org/?probe=396f71a402) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| HP            | Laptop 15-bs0xx             | [f8a316e74c](https://linux-hardware.org/?probe=f8a316e74c) | Aug 27, 2023 |
| Acer          | Aspire V5-471P              | [fcbacf6769](https://linux-hardware.org/?probe=fcbacf6769) | Aug 26, 2023 |
| Dell          | G15 5510                    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| Google        | Pirika                      | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Unknown       | Unknown                     | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Dell          | Latitude E6430              | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| Acer          | Aspire E1-531               | [ca5348bd31](https://linux-hardware.org/?probe=ca5348bd31) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| Dell          | Latitude E6430              | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Dell          | Latitude E7440              | [edae1bc7d3](https://linux-hardware.org/?probe=edae1bc7d3) | Aug 21, 2023 |
| Dell          | Latitude E6430              | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| Lenovo        | G50-30 80G0                 | [54c2ded452](https://linux-hardware.org/?probe=54c2ded452) | Aug 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [68df495196](https://linux-hardware.org/?probe=68df495196) | Aug 19, 2023 |
| Lenovo        | Rev B 82KU                  | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| Lenovo        | S10-3                       | [d1c8fb66ec](https://linux-hardware.org/?probe=d1c8fb66ec) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| Dell          | Inspiron 3505               | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Valve         | Jupiter                     | [069bfd618c](https://linux-hardware.org/?probe=069bfd618c) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [d6f18c79f6](https://linux-hardware.org/?probe=d6f18c79f6) | Aug 10, 2023 |
| Toshiba       | Satellite L745D             | [9576dab2b0](https://linux-hardware.org/?probe=9576dab2b0) | Aug 09, 2023 |
| Dell          | Precision 3551              | [a9b776ade0](https://linux-hardware.org/?probe=a9b776ade0) | Aug 09, 2023 |
| ASUSTek       | X455LA                      | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [0c8aef568d](https://linux-hardware.org/?probe=0c8aef568d) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [597f8ddaf2](https://linux-hardware.org/?probe=597f8ddaf2) | Aug 06, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [9f813efccc](https://linux-hardware.org/?probe=9f813efccc) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [349326315f](https://linux-hardware.org/?probe=349326315f) | Aug 05, 2023 |
| Dell          | Latitude 5490               | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Dell          | Latitude E6440              | [c00884f2cd](https://linux-hardware.org/?probe=c00884f2cd) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Anbernic      | Win600                      | [6d076e4bc9](https://linux-hardware.org/?probe=6d076e4bc9) | Aug 02, 2023 |
| Dell          | Inspiron 5567               | [6f220fcf23](https://linux-hardware.org/?probe=6f220fcf23) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d6c2eae395](https://linux-hardware.org/?probe=d6c2eae395) | Aug 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [39774f9f5d](https://linux-hardware.org/?probe=39774f9f5d) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| VPU Compan... | VWNC71429-S                 | [2a21ab7b53](https://linux-hardware.org/?probe=2a21ab7b53) | Jul 31, 2023 |
| HP            | 255 G7 Notebook PC          | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| HONOR         | BMH-WCX9                    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| Lenovo        | G40-45 80E1                 | [27af99ec54](https://linux-hardware.org/?probe=27af99ec54) | Jul 28, 2023 |
| HUAWEI        | BOM-WXX9                    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| Dell          | Inspiron 5570               | [fb125d5fcb](https://linux-hardware.org/?probe=fb125d5fcb) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Apple         | MacBookPro8,1               | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| Dell          | Latitude E7450              | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [39ea43d323](https://linux-hardware.org/?probe=39ea43d323) | Jul 20, 2023 |
| Dell          | Latitude 5420               | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| HP            | ENVY Notebook               | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [666c1c0162](https://linux-hardware.org/?probe=666c1c0162) | Jul 18, 2023 |
| HP            | G42                         | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| Apple         | MacBookAir6,2               | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| MSI           | GE72MVR 7RG                 | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| HP            | Laptop 14-fq1xxx            | [2687ecdde1](https://linux-hardware.org/?probe=2687ecdde1) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| GPU Compan... | GWTC51427                   | [138ef93d27](https://linux-hardware.org/?probe=138ef93d27) | Jul 13, 2023 |
| Apple         | MacBookPro12,1              | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| HP            | Laptop 14-cm0xxx            | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| Acer          | Aspire ES1-511              | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| Dell          | Precision M6700             | [ec5b230e37](https://linux-hardware.org/?probe=ec5b230e37) | Jul 09, 2023 |
| Sony          | VPCF236FM                   | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [883185ea85](https://linux-hardware.org/?probe=883185ea85) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Acer          | Aspire V5-472               | [663adbe947](https://linux-hardware.org/?probe=663adbe947) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| Dell          | Inspiron 5555               | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| HP            | 550                         | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Lenovo        | ThinkPad L430 246634S       | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Alienware     | 17 R4                       | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | [683b7b2dc2](https://linux-hardware.org/?probe=683b7b2dc2) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | [558a5b8a7f](https://linux-hardware.org/?probe=558a5b8a7f) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [ef5eb06f90](https://linux-hardware.org/?probe=ef5eb06f90) | Jun 24, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [44b5bb5453](https://linux-hardware.org/?probe=44b5bb5453) | Jun 23, 2023 |
| Dell          | Latitude E5470              | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [696e42eaba](https://linux-hardware.org/?probe=696e42eaba) | Jun 20, 2023 |
| ASUSTek       | TP501UA                     | [e883c61561](https://linux-hardware.org/?probe=e883c61561) | Jun 19, 2023 |
| Dell          | Latitude 5531               | [bf22616526](https://linux-hardware.org/?probe=bf22616526) | Jun 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude E6320              | [f1552f3016](https://linux-hardware.org/?probe=f1552f3016) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | [1869c3f4dc](https://linux-hardware.org/?probe=1869c3f4dc) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | [2aed95c237](https://linux-hardware.org/?probe=2aed95c237) | Jun 16, 2023 |
| Dell          | Inspiron 5548               | [547ffd8db7](https://linux-hardware.org/?probe=547ffd8db7) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| Acer          | Aspire V5-472               | [58dc632831](https://linux-hardware.org/?probe=58dc632831) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| HP            | Laptop 15-db0xxx            | [ca0a511cd7](https://linux-hardware.org/?probe=ca0a511cd7) | Jun 14, 2023 |
| HP            | G61                         | [52e962e82d](https://linux-hardware.org/?probe=52e962e82d) | Jun 14, 2023 |
| Dell          | Latitude 5590               | [56f8f9bbaf](https://linux-hardware.org/?probe=56f8f9bbaf) | Jun 14, 2023 |
| HP            | Pavilion Notebook           | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Gateway       | NE572                       | [771f8d0d63](https://linux-hardware.org/?probe=771f8d0d63) | Jun 13, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| HUAWEI        | HVY-WXX9                    | [4cf431ecc8](https://linux-hardware.org/?probe=4cf431ecc8) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2c5f9d83bd](https://linux-hardware.org/?probe=2c5f9d83bd) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| Dell          | Latitude 5590               | [f6347f5d6b](https://linux-hardware.org/?probe=f6347f5d6b) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| HP            | Laptop 15-db0xxx            | [03f0e4060e](https://linux-hardware.org/?probe=03f0e4060e) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| Acer          | Nitro AN515-55              | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Latitude E6400              | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| HP            | Pavilion g4                 | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Dell          | Inspiron 5559               | [9ee7eff678](https://linux-hardware.org/?probe=9ee7eff678) | Jun 04, 2023 |
| Lanix         | AL V9                       | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| Dell          | Inspiron 5555               | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Dell          | Latitude E5470              | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| Valve         | Jupiter                     | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Acer          | AO756                       | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Acer          | Aspire E5-573               | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Dell          | Latitude E5470              | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Dell          | Inspiron 5548               | [5665ccbc0a](https://linux-hardware.org/?probe=5665ccbc0a) | May 23, 2023 |
| Toshiba       | Satellite C645D             | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| HP            | Pavilion dm4                | [81f264e4ef](https://linux-hardware.org/?probe=81f264e4ef) | May 22, 2023 |
| HP            | Pavilion dm4                | [1f1a9e3f62](https://linux-hardware.org/?probe=1f1a9e3f62) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| HP            | Pavilion dm4                | [e25186a486](https://linux-hardware.org/?probe=e25186a486) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| Apple         | MacBookPro12,1              | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| Lenovo        | G50-30 80G0                 | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HP            | Pavilion Notebook           | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| ASUSTek       | G73Sw                       | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Samsung       | R530/R730                   | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| Apple         | MacBookPro9,2               | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | Laptop 14-dk0xxx            | [e644ef3b24](https://linux-hardware.org/?probe=e644ef3b24) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| eMachines     | E625                        | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| eMachines     | E625                        | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | [82c3d7dd74](https://linux-hardware.org/?probe=82c3d7dd74) | May 09, 2023 |
| Lanix Amer... | A V19                       | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| HP            | 15                          | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| Apple         | MacBookPro9,2               | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| HP            | Pavilion g4                 | [55a4a7978e](https://linux-hardware.org/?probe=55a4a7978e) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | [fe2f2e420f](https://linux-hardware.org/?probe=fe2f2e420f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| Acer          | Aspire A315-56              | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| DERE          | X16                         | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Toshiba       | Satellite C845              | [8174d09074](https://linux-hardware.org/?probe=8174d09074) | Apr 21, 2023 |
| Dell          | G15 5510                    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| HP            | ProBook 655 G1              | [aaef8a36db](https://linux-hardware.org/?probe=aaef8a36db) | Apr 10, 2023 |
| Gateway       | M-6812M                     | [6101b79a06](https://linux-hardware.org/?probe=6101b79a06) | Apr 08, 2023 |
| Samsung       | RV415/RV515                 | [fe77afbdfa](https://linux-hardware.org/?probe=fe77afbdfa) | Apr 07, 2023 |
| HP            | ProBook 6360b               | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| Acer          | Aspire 3680                 | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Notebook      | L140PU                      | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Valve         | Jupiter                     | [7a6dcc077f](https://linux-hardware.org/?probe=7a6dcc077f) | Apr 03, 2023 |
| HP            | Unknown                     | [bd783cf180](https://linux-hardware.org/?probe=bd783cf180) | Apr 03, 2023 |
| HP            | 2000                        | [3fffec7875](https://linux-hardware.org/?probe=3fffec7875) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Dell          | System XPS L502X            | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [111eeac3b3](https://linux-hardware.org/?probe=111eeac3b3) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [2fcab6a925](https://linux-hardware.org/?probe=2fcab6a925) | Apr 01, 2023 |
| EVOO          | EVC156-1                    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [f5db7a6030](https://linux-hardware.org/?probe=f5db7a6030) | Mar 30, 2023 |
| HP            | Notebook                    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Apple         | MacBookPro8,3               | [90fadbf903](https://linux-hardware.org/?probe=90fadbf903) | Mar 28, 2023 |
| Apple         | MacBookPro9,2               | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | [5e4e7975c1](https://linux-hardware.org/?probe=5e4e7975c1) | Mar 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Toshiba       | Satellite C845D             | [32341bde2a](https://linux-hardware.org/?probe=32341bde2a) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| American M... | XA133PR110                  | [7e49d89ca8](https://linux-hardware.org/?probe=7e49d89ca8) | Mar 25, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| HP            | Unknown                     | [c27dcda931](https://linux-hardware.org/?probe=c27dcda931) | Mar 24, 2023 |
| Dell          | Inspiron 7559               | [51aab276a2](https://linux-hardware.org/?probe=51aab276a2) | Mar 23, 2023 |
| ASUSTek       | X202EP                      | [5cc1f3216b](https://linux-hardware.org/?probe=5cc1f3216b) | Mar 23, 2023 |
| HP            | Unknown                     | [913aa678bf](https://linux-hardware.org/?probe=913aa678bf) | Mar 23, 2023 |
| Lenovo        | Yoga 500-14IBD 80N4         | [f364402e8a](https://linux-hardware.org/?probe=f364402e8a) | Mar 23, 2023 |
| HONOR         | BBR-WAX9                    | [b16e6324ed](https://linux-hardware.org/?probe=b16e6324ed) | Mar 22, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | G15 5510                    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [8a70a156a4](https://linux-hardware.org/?probe=8a70a156a4) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6dc3256710](https://linux-hardware.org/?probe=6dc3256710) | Mar 21, 2023 |
| HP            | Unknown                     | [66723d18e0](https://linux-hardware.org/?probe=66723d18e0) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [56b1138062](https://linux-hardware.org/?probe=56b1138062) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [1fe782c379](https://linux-hardware.org/?probe=1fe782c379) | Mar 21, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Lenovo        | G40-80 80E4                 | [70b2fab92b](https://linux-hardware.org/?probe=70b2fab92b) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Toshiba       | Satellite P55t-B            | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Acer          | Aspire R3-131T              | [94435f58ed](https://linux-hardware.org/?probe=94435f58ed) | Mar 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| Dell          | G3 3500                     | [5cfed5bee9](https://linux-hardware.org/?probe=5cfed5bee9) | Mar 10, 2023 |
| HP            | Pavilion dv4                | [79a8c505ef](https://linux-hardware.org/?probe=79a8c505ef) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Dell          | Inspiron 5567               | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6f7e8084e5](https://linux-hardware.org/?probe=6f7e8084e5) | Mar 04, 2023 |
| HP            | ProBook 6360b               | [8b6826988f](https://linux-hardware.org/?probe=8b6826988f) | Mar 03, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [c3113c9da6](https://linux-hardware.org/?probe=c3113c9da6) | Mar 02, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [73efff8199](https://linux-hardware.org/?probe=73efff8199) | Mar 02, 2023 |
| HP            | Pavilion 14                 | [ae0e65f5d1](https://linux-hardware.org/?probe=ae0e65f5d1) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| HP            | Pavilion 14                 | [c9b9f213b5](https://linux-hardware.org/?probe=c9b9f213b5) | Feb 26, 2023 |
| Lenovo        | B40-45 20394                | [8472ed364a](https://linux-hardware.org/?probe=8472ed364a) | Feb 26, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| Valve         | Jupiter                     | [0ec37b6ef2](https://linux-hardware.org/?probe=0ec37b6ef2) | Feb 25, 2023 |
| Chuwi         | HeroBook Air                | [8daed679c2](https://linux-hardware.org/?probe=8daed679c2) | Feb 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [bfd3019210](https://linux-hardware.org/?probe=bfd3019210) | Feb 22, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Toshiba       | Satellite C50D-A            | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| HP            | Pavilion g6                 | [2b4de6efbe](https://linux-hardware.org/?probe=2b4de6efbe) | Feb 18, 2023 |
| Dell          | Studio 1558                 | [4a2f0524b9](https://linux-hardware.org/?probe=4a2f0524b9) | Feb 17, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Dell          | Latitude E7440              | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [269420c3fe](https://linux-hardware.org/?probe=269420c3fe) | Feb 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de592b6218](https://linux-hardware.org/?probe=de592b6218) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| HP            | Laptop 15-da2xxx            | [41bf5d50f8](https://linux-hardware.org/?probe=41bf5d50f8) | Feb 14, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [cfeb6479d1](https://linux-hardware.org/?probe=cfeb6479d1) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| HP            | 240 G3                      | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [f7c5e9e498](https://linux-hardware.org/?probe=f7c5e9e498) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [44aed7e81a](https://linux-hardware.org/?probe=44aed7e81a) | Feb 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [5acc007668](https://linux-hardware.org/?probe=5acc007668) | Feb 04, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 240 G3                      | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| HUAWEI        | KLVD-WXX9                   | [6546c6e279](https://linux-hardware.org/?probe=6546c6e279) | Feb 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [73230e9490](https://linux-hardware.org/?probe=73230e9490) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| ASUSTek       | N56VB                       | [d5b5c983c9](https://linux-hardware.org/?probe=d5b5c983c9) | Feb 02, 2023 |
| Apple         | MacBookPro15,2              | [7c17db143e](https://linux-hardware.org/?probe=7c17db143e) | Feb 01, 2023 |
| Apple         | MacBookPro8,1               | [13467e9e83](https://linux-hardware.org/?probe=13467e9e83) | Feb 01, 2023 |
| Dell          | Latitude 5430               | [2afa57d0fa](https://linux-hardware.org/?probe=2afa57d0fa) | Feb 01, 2023 |
| Apple         | MacBookPro15,2              | [7612aba4cb](https://linux-hardware.org/?probe=7612aba4cb) | Jan 31, 2023 |
| Lenovo        | ThinkPad T430 2349A44       | [9f8528c5da](https://linux-hardware.org/?probe=9f8528c5da) | Jan 31, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| HP            | Laptop 15-dw1xxx            | [c7d825c34c](https://linux-hardware.org/?probe=c7d825c34c) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bd58d910f7](https://linux-hardware.org/?probe=bd58d910f7) | Jan 25, 2023 |
| Dell          | Latitude E5440              | [f8e7f1785b](https://linux-hardware.org/?probe=f8e7f1785b) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [65b6391803](https://linux-hardware.org/?probe=65b6391803) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Dell          | Inspiron 5558               | [bf87467519](https://linux-hardware.org/?probe=bf87467519) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [57ed6980d4](https://linux-hardware.org/?probe=57ed6980d4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [0667ad7cee](https://linux-hardware.org/?probe=0667ad7cee) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c9279b845](https://linux-hardware.org/?probe=9c9279b845) | Jan 19, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | [7e61f98275](https://linux-hardware.org/?probe=7e61f98275) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [3709c83303](https://linux-hardware.org/?probe=3709c83303) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [6eeac14bb9](https://linux-hardware.org/?probe=6eeac14bb9) | Jan 15, 2023 |
| Dell          | Latitude E6440              | [d04d05f246](https://linux-hardware.org/?probe=d04d05f246) | Jan 14, 2023 |
| Lenovo        | B490 20205                  | [14243e79d2](https://linux-hardware.org/?probe=14243e79d2) | Jan 13, 2023 |
| HP            | ProBook 4230s               | [63a87864b9](https://linux-hardware.org/?probe=63a87864b9) | Jan 12, 2023 |
| HP            | ProBook 4230s               | [9a6505c0aa](https://linux-hardware.org/?probe=9a6505c0aa) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Lenovo        | Y50-70 20378                | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| Sony          | VPCEH1AFX                   | [3f64681bc7](https://linux-hardware.org/?probe=3f64681bc7) | Jan 11, 2023 |
| HP            | Pavilion Notebook           | [2132701432](https://linux-hardware.org/?probe=2132701432) | Jan 11, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Valve         | Jupiter                     | [57b570af42](https://linux-hardware.org/?probe=57b570af42) | Jan 09, 2023 |
| HP            | Pavilion 15                 | [2937882035](https://linux-hardware.org/?probe=2937882035) | Jan 08, 2023 |
| Notebook      | W9x0LU                      | [a81dd09b0c](https://linux-hardware.org/?probe=a81dd09b0c) | Jan 07, 2023 |
| HP            | Stream Laptop 11-y0XX       | [b40a3e32e9](https://linux-hardware.org/?probe=b40a3e32e9) | Jan 06, 2023 |
| HP            | Stream Laptop 11-y0XX       | [73db1ffcf6](https://linux-hardware.org/?probe=73db1ffcf6) | Jan 06, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| Lenovo        | G580 20157                  | [c0199fa7bf](https://linux-hardware.org/?probe=c0199fa7bf) | Jan 05, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | EliteBook 8460p             | [3365055862](https://linux-hardware.org/?probe=3365055862) | Jan 02, 2023 |
| HP            | EliteBook 8460p             | [45184e1f70](https://linux-hardware.org/?probe=45184e1f70) | Jan 02, 2023 |
| HP            | Laptop 15-dy2xxx            | [8c76b9ad8e](https://linux-hardware.org/?probe=8c76b9ad8e) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| Acer          | Aspire R7-371T              | [057e717cb7](https://linux-hardware.org/?probe=057e717cb7) | Dec 30, 2022 |
| HP            | 240 G7 Notebook PC          | [414db30bff](https://linux-hardware.org/?probe=414db30bff) | Dec 30, 2022 |
| ASUSTek       | N56VB                       | [6201ddc028](https://linux-hardware.org/?probe=6201ddc028) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Dell          | Inspiron MM061              | [34804f8a34](https://linux-hardware.org/?probe=34804f8a34) | Dec 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | Laptop 14-fq0xxx            | [e020678b51](https://linux-hardware.org/?probe=e020678b51) | Dec 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [8e2393e7b4](https://linux-hardware.org/?probe=8e2393e7b4) | Dec 26, 2022 |
| Acer          | Aspire E1-522               | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Google        | Bobba360                    | [bdad461cec](https://linux-hardware.org/?probe=bdad461cec) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Dell          | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Acer          | Aspire A515-51              | [29af4c3712](https://linux-hardware.org/?probe=29af4c3712) | Dec 20, 2022 |
| Google        | Coral                       | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [96dcb47ba1](https://linux-hardware.org/?probe=96dcb47ba1) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Valve         | Jupiter                     | [f89644c711](https://linux-hardware.org/?probe=f89644c711) | Dec 15, 2022 |
| HP            | Laptop 15-da2xxx            | [cd64f27416](https://linux-hardware.org/?probe=cd64f27416) | Dec 14, 2022 |
| MSI           | GL75 Leopard 10SDK          | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [36bd6688bb](https://linux-hardware.org/?probe=36bd6688bb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [ed5d274c1a](https://linux-hardware.org/?probe=ed5d274c1a) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Alienware     | 15 R4                       | [f365266667](https://linux-hardware.org/?probe=f365266667) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Toshiba       | Satellite L855              | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| Sony          | VPCEE27FL                   | [dd2bc8b6ff](https://linux-hardware.org/?probe=dd2bc8b6ff) | Dec 10, 2022 |
| Dell          | Latitude E6420              | [acd81c73d0](https://linux-hardware.org/?probe=acd81c73d0) | Dec 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [38d274571d](https://linux-hardware.org/?probe=38d274571d) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Acer          | TravelMate B117-M           | [00ff19b078](https://linux-hardware.org/?probe=00ff19b078) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| HP            | 15                          | [132fad5c38](https://linux-hardware.org/?probe=132fad5c38) | Dec 04, 2022 |
| Acer          | TravelMate B117-M           | [0b86a9c3b9](https://linux-hardware.org/?probe=0b86a9c3b9) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| HP            | Pavilion 14                 | [dedd30adc4](https://linux-hardware.org/?probe=dedd30adc4) | Nov 30, 2022 |
| Sony          | VGN-NS150FJ                 | [e675a19a27](https://linux-hardware.org/?probe=e675a19a27) | Nov 29, 2022 |
| Apple         | MacBookPro8,1               | [7ba1690c68](https://linux-hardware.org/?probe=7ba1690c68) | Nov 28, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [a7b7f4f100](https://linux-hardware.org/?probe=a7b7f4f100) | Nov 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AX05    | [c4a2ce46ca](https://linux-hardware.org/?probe=c4a2ce46ca) | Nov 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [240694e932](https://linux-hardware.org/?probe=240694e932) | Nov 23, 2022 |
| HP            | Notebook                    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Dell          | G3 3579                     | [7f4d27ea26](https://linux-hardware.org/?probe=7f4d27ea26) | Nov 23, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Toshiba       | Satellite L45Dt-B           | [9cdcee20dc](https://linux-hardware.org/?probe=9cdcee20dc) | Nov 22, 2022 |
| Valve         | Jupiter                     | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Dell          | Latitude E5440              | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| HP            | Laptop 15-da2xxx            | [e55a0e2ae1](https://linux-hardware.org/?probe=e55a0e2ae1) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [c08218542c](https://linux-hardware.org/?probe=c08218542c) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [4830cb0a27](https://linux-hardware.org/?probe=4830cb0a27) | Nov 17, 2022 |
| ASUSTek       | X556UQK                     | [fb33c2bdea](https://linux-hardware.org/?probe=fb33c2bdea) | Nov 16, 2022 |
| ASUSTek       | X556UQK                     | [b4f8d67230](https://linux-hardware.org/?probe=b4f8d67230) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| HP            | Laptop 15-da2xxx            | [b1ed3e6190](https://linux-hardware.org/?probe=b1ed3e6190) | Nov 16, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9d92c6041](https://linux-hardware.org/?probe=b9d92c6041) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [61b131a3ae](https://linux-hardware.org/?probe=61b131a3ae) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [3f3280fa71](https://linux-hardware.org/?probe=3f3280fa71) | Nov 13, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [416c73c293](https://linux-hardware.org/?probe=416c73c293) | Nov 09, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [eac572ee3d](https://linux-hardware.org/?probe=eac572ee3d) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| Chuwi         | GemiBook Pro                | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Google        | Treeya                      | [dc9067b4b6](https://linux-hardware.org/?probe=dc9067b4b6) | Nov 07, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [20826ec148](https://linux-hardware.org/?probe=20826ec148) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | Laptop 17-ca0xxx            | [af3aa996df](https://linux-hardware.org/?probe=af3aa996df) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [caaca6d1f1](https://linux-hardware.org/?probe=caaca6d1f1) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Toshiba       | Satellite L55-B             | [ca03715db3](https://linux-hardware.org/?probe=ca03715db3) | Nov 03, 2022 |
| Acer          | Aspire E5-522               | [32f73c64a6](https://linux-hardware.org/?probe=32f73c64a6) | Nov 02, 2022 |
| Acer          | Aspire E5-522               | [412b8c701e](https://linux-hardware.org/?probe=412b8c701e) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [95d825cd94](https://linux-hardware.org/?probe=95d825cd94) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| GPU Compan... | GWNR71517                   | [168f199ffd](https://linux-hardware.org/?probe=168f199ffd) | Oct 29, 2022 |
| Dell          | Latitude 3590               | [d1b6c7cd85](https://linux-hardware.org/?probe=d1b6c7cd85) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| GPU Compan... | GWNR71517                   | [e03f1db8e1](https://linux-hardware.org/?probe=e03f1db8e1) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Dell          | Latitude 9420               | [ab37e0d841](https://linux-hardware.org/?probe=ab37e0d841) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Dell          | Inspiron 3505               | [891f846aac](https://linux-hardware.org/?probe=891f846aac) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [914bab2302](https://linux-hardware.org/?probe=914bab2302) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [f467f29abf](https://linux-hardware.org/?probe=f467f29abf) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Lenovo        | G450 2949                   | [13c0232085](https://linux-hardware.org/?probe=13c0232085) | Oct 19, 2022 |
| Lenovo        | G450 2949                   | [1e5a91a31d](https://linux-hardware.org/?probe=1e5a91a31d) | Oct 18, 2022 |
| Dell          | Latitude 7430               | [d4d6f89390](https://linux-hardware.org/?probe=d4d6f89390) | Oct 18, 2022 |
| HP            | Unknown                     | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Vostro 14-3468              | [c0958ba47f](https://linux-hardware.org/?probe=c0958ba47f) | Oct 17, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| HP            | 245 G7 Notebook PC          | [c164c2ab59](https://linux-hardware.org/?probe=c164c2ab59) | Oct 16, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [87cf4b398b](https://linux-hardware.org/?probe=87cf4b398b) | Oct 16, 2022 |
| HUAWEI        | CREM-WXX9                   | [3edd19f985](https://linux-hardware.org/?probe=3edd19f985) | Oct 15, 2022 |
| Dell          | Latitude E5440              | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| HP            | Laptop 14-bw0xx             | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| Toshiba       | Satellite P55t-A            | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| Dell          | System XPS L502X            | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| Dell          | Inspiron 3520               | [5cf6d495ff](https://linux-hardware.org/?probe=5cf6d495ff) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [167321509c](https://linux-hardware.org/?probe=167321509c) | Oct 07, 2022 |
| Apple         | MacBookPro8,1               | [0d9e169836](https://linux-hardware.org/?probe=0d9e169836) | Oct 06, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| HP            | ProBook 6470b               | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| HP            | Unknown                     | [72a00fa1a2](https://linux-hardware.org/?probe=72a00fa1a2) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| GHIA          | LFI3H                       | [4233e4e6c5](https://linux-hardware.org/?probe=4233e4e6c5) | Sep 29, 2022 |
| GHIA          | LFI3H                       | [482e78460a](https://linux-hardware.org/?probe=482e78460a) | Sep 29, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [4f2655de78](https://linux-hardware.org/?probe=4f2655de78) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Dell          | Latitude E7440              | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Dell          | Latitude E5450              | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| HP            | Unknown                     | [63af86aa38](https://linux-hardware.org/?probe=63af86aa38) | Sep 25, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Chuwi         | CoreBook XPro               | [5ace2b3ea5](https://linux-hardware.org/?probe=5ace2b3ea5) | Sep 23, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| ASUSTek       | G750JM                      | [2e53c11312](https://linux-hardware.org/?probe=2e53c11312) | Sep 22, 2022 |
| MSI           | GT70 2OC/2OD                | [c6a0b0d987](https://linux-hardware.org/?probe=c6a0b0d987) | Sep 22, 2022 |
| Lenovo        | G40-80 80E4                 | [575b85b038](https://linux-hardware.org/?probe=575b85b038) | Sep 21, 2022 |
| Lenovo        | G40-80 80E4                 | [18a0a2158c](https://linux-hardware.org/?probe=18a0a2158c) | Sep 21, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| American M... | XA133PR110                  | [b79d35c0bd](https://linux-hardware.org/?probe=b79d35c0bd) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| HP            | EliteBook 2740p             | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| ASUSTek       | X555DG                      | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Toshiba       | Satellite L855              | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [0c6b0c35e6](https://linux-hardware.org/?probe=0c6b0c35e6) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [b4c9fcf4c3](https://linux-hardware.org/?probe=b4c9fcf4c3) | Sep 14, 2022 |
| Lanix         | AL V9                       | [03e7c7ece5](https://linux-hardware.org/?probe=03e7c7ece5) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| Chuwi         | GemiBook Pro                | [5b62dddb37](https://linux-hardware.org/?probe=5b62dddb37) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| ASUSTek       | X553MA                      | [32c5b56788](https://linux-hardware.org/?probe=32c5b56788) | Sep 11, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Gateway       | NE56R                       | [c928861fb0](https://linux-hardware.org/?probe=c928861fb0) | Sep 09, 2022 |
| Gateway       | NE56R                       | [3167a59b9b](https://linux-hardware.org/?probe=3167a59b9b) | Sep 09, 2022 |
| ASUSTek       | X553MA                      | [32edc5cfad](https://linux-hardware.org/?probe=32edc5cfad) | Sep 08, 2022 |
| Apple         | MacBook4,1                  | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| HP            | Laptop 15-bw0xx             | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| Dell          | Latitude E7450              | [de66677d3d](https://linux-hardware.org/?probe=de66677d3d) | Sep 03, 2022 |
| HP            | Pavilion 14                 | [7a2b6c5f4b](https://linux-hardware.org/?probe=7a2b6c5f4b) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [7da5af06fb](https://linux-hardware.org/?probe=7da5af06fb) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [c7b43caa52](https://linux-hardware.org/?probe=c7b43caa52) | Sep 01, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| HP            | ENVY m6 Notebook            | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| HP            | Pavilion dv7                | [81b7ddb4e9](https://linux-hardware.org/?probe=81b7ddb4e9) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [aa44fba5de](https://linux-hardware.org/?probe=aa44fba5de) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [21d9982f20](https://linux-hardware.org/?probe=21d9982f20) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| HP            | Pavilion TS 14              | [145fc8369f](https://linux-hardware.org/?probe=145fc8369f) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| Toshiba       | Satellite P200              | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Sony          | VPCYB20AL                   | [f886e2ff98](https://linux-hardware.org/?probe=f886e2ff98) | Aug 10, 2022 |
| Lenovo        | L340-15API 81LW             | [50eca7fa1e](https://linux-hardware.org/?probe=50eca7fa1e) | Aug 10, 2022 |
| HUAWEI        | WRT-WX9                     | [f9c85afff2](https://linux-hardware.org/?probe=f9c85afff2) | Aug 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Google        | Blorb                       | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Acer          | AO756                       | [4bc715a31c](https://linux-hardware.org/?probe=4bc715a31c) | Aug 05, 2022 |
| Dell          | Inspiron 5559               | [3e02305524](https://linux-hardware.org/?probe=3e02305524) | Aug 04, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| HP            | ProBook 4520s               | [8e03860e5f](https://linux-hardware.org/?probe=8e03860e5f) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [057703210a](https://linux-hardware.org/?probe=057703210a) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| HP            | ProBook 4520s               | [80024f9b67](https://linux-hardware.org/?probe=80024f9b67) | Jul 26, 2022 |
| HP            | 245 G7 Notebook PC          | [07c70033f5](https://linux-hardware.org/?probe=07c70033f5) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| Dell          | Inspiron 3505               | [5bec1168d0](https://linux-hardware.org/?probe=5bec1168d0) | Jul 22, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| Dell          | Latitude E7250              | [5fdb8cad05](https://linux-hardware.org/?probe=5fdb8cad05) | Jul 21, 2022 |
| GHIA          | Notebook                    | [2193ab1cd3](https://linux-hardware.org/?probe=2193ab1cd3) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Dell          | Inspiron 3421               | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [1cf6844d33](https://linux-hardware.org/?probe=1cf6844d33) | Jul 14, 2022 |
| Toshiba       | Satellite L55-B             | [0e0ba8274b](https://linux-hardware.org/?probe=0e0ba8274b) | Jul 13, 2022 |
| Toshiba       | Satellite L55-B             | [a7bebd622f](https://linux-hardware.org/?probe=a7bebd622f) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Dell          | Latitude E5530 non-vPro     | [0ab6a30f98](https://linux-hardware.org/?probe=0ab6a30f98) | Jul 12, 2022 |
| Sony          | VPCYB20AL                   | [c9645d6952](https://linux-hardware.org/?probe=c9645d6952) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| MSI           | GF63 Thin 11UC              | [ecfb5f39c5](https://linux-hardware.org/?probe=ecfb5f39c5) | Jul 09, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-51              | [0b57ab5b5b](https://linux-hardware.org/?probe=0b57ab5b5b) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7e53f712c5](https://linux-hardware.org/?probe=7e53f712c5) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [a5ad48eeb5](https://linux-hardware.org/?probe=a5ad48eeb5) | Jul 03, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [c364b347a5](https://linux-hardware.org/?probe=c364b347a5) | Jul 02, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| HUAWEI        | NBM-WXX9                    | [6ed674f77e](https://linux-hardware.org/?probe=6ed674f77e) | Jul 01, 2022 |
| Acer          | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Dell          | Latitude 7420               | [3730ffb739](https://linux-hardware.org/?probe=3730ffb739) | Jun 27, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| Google        | Kip                         | [d21adde488](https://linux-hardware.org/?probe=d21adde488) | Jun 24, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| Apple         | MacBookAir6,1               | [665cfa446b](https://linux-hardware.org/?probe=665cfa446b) | Jun 18, 2022 |
| HP            | Laptop 15-bs0xx             | [aa89682b09](https://linux-hardware.org/?probe=aa89682b09) | Jun 18, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkPad T540p 20BE003NU... | [e05c2e42c2](https://linux-hardware.org/?probe=e05c2e42c2) | Jun 17, 2022 |
| Gateway       | NE513                       | [c33ad72253](https://linux-hardware.org/?probe=c33ad72253) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | IdeaPad Z480                | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| Dell          | Latitude E6410              | [6194911b41](https://linux-hardware.org/?probe=6194911b41) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [005799b9bf](https://linux-hardware.org/?probe=005799b9bf) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Dell          | Studio XPS 1340             | [36f61b29b5](https://linux-hardware.org/?probe=36f61b29b5) | Jun 11, 2022 |
| HP            | Pavilion dv6                | [c8e7eea8fc](https://linux-hardware.org/?probe=c8e7eea8fc) | Jun 11, 2022 |
| Corporativ... | Neuron LT                   | [84ed262694](https://linux-hardware.org/?probe=84ed262694) | Jun 10, 2022 |
| Corporativ... | Neuron LT                   | [ad265d5197](https://linux-hardware.org/?probe=ad265d5197) | Jun 10, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [479a01b8d8](https://linux-hardware.org/?probe=479a01b8d8) | Jun 10, 2022 |
| ASUSTek       | K43E                        | [cd9e7dab5e](https://linux-hardware.org/?probe=cd9e7dab5e) | Jun 09, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Toshiba       | Satellite L55-B             | [38c0d1cebc](https://linux-hardware.org/?probe=38c0d1cebc) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| HP            | Laptop 15-dy2xxx            | [ecc580e75f](https://linux-hardware.org/?probe=ecc580e75f) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | [e737d522f2](https://linux-hardware.org/?probe=e737d522f2) | Jun 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| EVOO          | EV-C-116-7                  | [1955955afc](https://linux-hardware.org/?probe=1955955afc) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a3e63f04e7](https://linux-hardware.org/?probe=a3e63f04e7) | May 31, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Inspiron 5547               | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| Lenovo        | IdeaPad S300 20197          | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| Lenovo        | IdeaPad Z480                | [b1cf8ca505](https://linux-hardware.org/?probe=b1cf8ca505) | May 30, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [55dfdf01c6](https://linux-hardware.org/?probe=55dfdf01c6) | May 29, 2022 |
| HP            | Presario CQ62               | [fe3cac8868](https://linux-hardware.org/?probe=fe3cac8868) | May 27, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| Acer          | Swift SF113-31              | [2bdba73cfa](https://linux-hardware.org/?probe=2bdba73cfa) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| HP            | Pavilion g4                 | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| HUAWEI        | HVY-WXX9                    | [93bb32d1b2](https://linux-hardware.org/?probe=93bb32d1b2) | May 21, 2022 |
| Acer          | Aspire 5332                 | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | S10-3                       | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4316b121b1](https://linux-hardware.org/?probe=4316b121b1) | May 14, 2022 |
| Dell          | Studio 1558                 | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [2bd7babedc](https://linux-hardware.org/?probe=2bd7babedc) | May 13, 2022 |
| Toshiba       | TECRA Z50-A                 | [985d5869bf](https://linux-hardware.org/?probe=985d5869bf) | May 12, 2022 |
| Dell          | XPS 15 9550                 | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| Google        | Blooglet                    | [64b4f18c1c](https://linux-hardware.org/?probe=64b4f18c1c) | May 09, 2022 |
| Google        | Blooglet                    | [f3dc91bf66](https://linux-hardware.org/?probe=f3dc91bf66) | May 09, 2022 |
| HP            | Laptop 17z-ca300            | [c43f2b0e29](https://linux-hardware.org/?probe=c43f2b0e29) | May 08, 2022 |
| Acer          | Aspire ES1-531              | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| HP            | Notebook                    | [04f5e602de](https://linux-hardware.org/?probe=04f5e602de) | May 07, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [46d0c349d6](https://linux-hardware.org/?probe=46d0c349d6) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| HP            | Pavilion 14                 | [2bd48eeb41](https://linux-hardware.org/?probe=2bd48eeb41) | May 06, 2022 |
| Apple         | MacBookAir6,2               | [d04d5e927d](https://linux-hardware.org/?probe=d04d5e927d) | May 05, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| Dell          | Latitude 7420               | [a0bd1ee0f4](https://linux-hardware.org/?probe=a0bd1ee0f4) | May 03, 2022 |
| Sony          | VPCF236FM                   | [ec0af02205](https://linux-hardware.org/?probe=ec0af02205) | May 02, 2022 |
| Acer          | Aspire V5-561               | [e9dfda82d4](https://linux-hardware.org/?probe=e9dfda82d4) | May 02, 2022 |
| Dell          | Latitude E5550              | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [fbb6d3b97e](https://linux-hardware.org/?probe=fbb6d3b97e) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [d594f3335c](https://linux-hardware.org/?probe=d594f3335c) | May 01, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f5d70fb9d3](https://linux-hardware.org/?probe=f5d70fb9d3) | Apr 30, 2022 |
| Lenovo        | S10-3                       | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Toshiba       | Satellite L735D             | [4bd23809e6](https://linux-hardware.org/?probe=4bd23809e6) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| Dell          | Inspiron 5577               | [0925d92173](https://linux-hardware.org/?probe=0925d92173) | Apr 25, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| ASUSTek       | K46CA                       | [e762eba391](https://linux-hardware.org/?probe=e762eba391) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| Chuwi         | Unknown                     | [96105ecbb2](https://linux-hardware.org/?probe=96105ecbb2) | Apr 23, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [55186a3c2e](https://linux-hardware.org/?probe=55186a3c2e) | Apr 18, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Lenovo        | G40-45 80E1                 | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [25c2200e11](https://linux-hardware.org/?probe=25c2200e11) | Apr 14, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [5d153a1030](https://linux-hardware.org/?probe=5d153a1030) | Apr 12, 2022 |
| HP            | ZBook 15                    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| Toshiba       | Satellite L735D             | [47f0119635](https://linux-hardware.org/?probe=47f0119635) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| HP            | Laptop 15-da1xxx            | [8d9c212045](https://linux-hardware.org/?probe=8d9c212045) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| HP            | ZBook 15                    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| HP            | Pavilion dv6                | [9d37acefa0](https://linux-hardware.org/?probe=9d37acefa0) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| Toshiba       | Satellite P775              | [3acd0b8861](https://linux-hardware.org/?probe=3acd0b8861) | Apr 08, 2022 |
| Dell          | Inspiron 5570               | [801e4fdab1](https://linux-hardware.org/?probe=801e4fdab1) | Apr 07, 2022 |
| Dell          | Latitude E5440              | [18a9d37c02](https://linux-hardware.org/?probe=18a9d37c02) | Apr 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [e168714dee](https://linux-hardware.org/?probe=e168714dee) | Apr 06, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [9d26a79ca6](https://linux-hardware.org/?probe=9d26a79ca6) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [54db9ac27f](https://linux-hardware.org/?probe=54db9ac27f) | Apr 05, 2022 |
| HP            | Pavilion 14                 | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| HP            | Presario CQ56               | [7233c29381](https://linux-hardware.org/?probe=7233c29381) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Apple         | MacBookPro9,2               | [f646cb03d2](https://linux-hardware.org/?probe=f646cb03d2) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [5af7df2c2a](https://linux-hardware.org/?probe=5af7df2c2a) | Mar 30, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d346f2a1b1](https://linux-hardware.org/?probe=d346f2a1b1) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [67475db5e9](https://linux-hardware.org/?probe=67475db5e9) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [2c7227662f](https://linux-hardware.org/?probe=2c7227662f) | Mar 29, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Dell          | Latitude E6510              | [4feee8c983](https://linux-hardware.org/?probe=4feee8c983) | Mar 26, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b955479cc](https://linux-hardware.org/?probe=4b955479cc) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Acer          | Nitro AN515-54              | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| Lenovo        | Unknown                     | [661ddbd0df](https://linux-hardware.org/?probe=661ddbd0df) | Mar 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [e1f3c645b5](https://linux-hardware.org/?probe=e1f3c645b5) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [ed01dc4465](https://linux-hardware.org/?probe=ed01dc4465) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [6c0caa0de4](https://linux-hardware.org/?probe=6c0caa0de4) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [dbed1562e8](https://linux-hardware.org/?probe=dbed1562e8) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| HP            | Pavilion 15                 | [29ac5f13cd](https://linux-hardware.org/?probe=29ac5f13cd) | Mar 16, 2022 |
| Apple         | MacBookPro15,2              | [a77a1ff925](https://linux-hardware.org/?probe=a77a1ff925) | Mar 16, 2022 |
| Dell          | Latitude E6220              | [0dbd85da47](https://linux-hardware.org/?probe=0dbd85da47) | Mar 13, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | ProBook 650 G1              | [046572a251](https://linux-hardware.org/?probe=046572a251) | Mar 09, 2022 |
| Dell          | XPS 15 9570                 | [dd0ebc18ce](https://linux-hardware.org/?probe=dd0ebc18ce) | Mar 07, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Chuwi         | GemiBook                    | [60146fd918](https://linux-hardware.org/?probe=60146fd918) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| Unknown       | KN12A                       | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| Panasonic     | CF-30KTPA9NP                | [fffe3abd97](https://linux-hardware.org/?probe=fffe3abd97) | Mar 05, 2022 |
| Lenovo        | G40-70 20369                | [fd797ac0c1](https://linux-hardware.org/?probe=fd797ac0c1) | Mar 03, 2022 |
| Chuwi         | GemiBook                    | [af28b0f0d8](https://linux-hardware.org/?probe=af28b0f0d8) | Mar 02, 2022 |
| Timi          | TM1612                      | [dc1c26b3a9](https://linux-hardware.org/?probe=dc1c26b3a9) | Mar 01, 2022 |
| Sony          | VGN-Z690N                   | [d3465abe44](https://linux-hardware.org/?probe=d3465abe44) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 166       | 9.93%   |
| Ubuntu 18.04       | 114       | 6.82%   |
| Ubuntu 22.04       | 97        | 5.8%    |
| OpenMandriva 4.3   | 47        | 2.81%   |
| Debian 11          | 47        | 2.81%   |
| Zorin 16           | 45        | 2.69%   |
| OpenMandriva 4.2   | 43        | 2.57%   |
| Manjaro            | 41        | 2.45%   |
| Fedora 38          | 40        | 2.39%   |
| KDE neon 20.04     | 36        | 2.15%   |
| Fedora 36          | 31        | 1.85%   |
| Pop!_OS 22.04      | 28        | 1.67%   |
| Linux Mint 20.3    | 28        | 1.67%   |
| Pop!_OS 20.04      | 23        | 1.38%   |
| OpenMandriva 23.03 | 22        | 1.32%   |
| Fedora 37          | 21        | 1.26%   |
| Arch               | 21        | 1.26%   |
| Zorin 15           | 19        | 1.14%   |
| Linux Mint 21.1    | 19        | 1.14%   |
| Linux Mint 20      | 19        | 1.14%   |
| Ubuntu 19.10       | 18        | 1.08%   |
| Ubuntu 19.04       | 18        | 1.08%   |
| Debian 10          | 18        | 1.08%   |
| Linux Mint 19.3    | 17        | 1.02%   |
| Ubuntu 22.10       | 16        | 0.96%   |
| Ubuntu 21.10       | 16        | 0.96%   |
| ArcoLinux Rolling  | 16        | 0.96%   |
| Ubuntu 23.04       | 15        | 0.9%    |
| Pop!_OS 21.04      | 15        | 0.9%    |
| Linux Mint 21      | 15        | 0.9%    |
| Kubuntu 20.04      | 15        | 0.9%    |
| KDE neon 22.04     | 15        | 0.9%    |
| Fedora 34          | 15        | 0.9%    |
| Arch Rolling       | 15        | 0.9%    |
| Xubuntu 18.04      | 14        | 0.84%   |
| Ubuntu 20.10       | 14        | 0.84%   |
| Linux Mint 20.1    | 14        | 0.84%   |
| Fedora 35          | 14        | 0.84%   |
| Elementary 6.1     | 14        | 0.84%   |
| OpenMandriva 23.01 | 12        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 478       | 29.78%  |
| Fedora        | 146       | 9.1%    |
| OpenMandriva  | 134       | 8.35%   |
| Linux Mint    | 130       | 8.1%    |
| Pop!_OS       | 78        | 4.86%   |
| Debian        | 76        | 4.74%   |
| Manjaro       | 68        | 4.24%   |
| Zorin         | 67        | 4.17%   |
| KDE neon      | 54        | 3.36%   |
| Kubuntu       | 37        | 2.31%   |
| Arch          | 36        | 2.24%   |
| Xubuntu       | 31        | 1.93%   |
| Elementary    | 26        | 1.62%   |
| Kali          | 23        | 1.43%   |
| openSUSE      | 19        | 1.18%   |
| ROSA          | 16        | 1%      |
| ArcoLinux     | 16        | 1%      |
| Lubuntu       | 12        | 0.75%   |
| Endless       | 12        | 0.75%   |
| Clear Linux   | 12        | 0.75%   |
| LMDE          | 11        | 0.69%   |
| SteamOS       | 9         | 0.56%   |
| Ubuntu Budgie | 8         | 0.5%    |
| EndeavourOS   | 8         | 0.5%    |
| Ubuntu Unity  | 7         | 0.44%   |
| Ubuntu MATE   | 7         | 0.44%   |
| Nobara        | 7         | 0.44%   |
| Gentoo        | 7         | 0.44%   |
| MX            | 6         | 0.37%   |
| Xero          | 5         | 0.31%   |
| Garuda Linux  | 5         | 0.31%   |
| CentOS        | 5         | 0.31%   |
| Parrot        | 4         | 0.25%   |
| Archcraft     | 4         | 0.25%   |
| RHEL          | 3         | 0.19%   |
| Peppermint    | 3         | 0.19%   |
| UbuntuDDE     | 2         | 0.12%   |
| Solus         | 2         | 0.12%   |
| Reborn OS     | 2         | 0.12%   |
| Mageia        | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 47        | 2.58%   |
| 5.10.14-desktop-1omv4002 | 43        | 2.36%   |
| 5.4.0-42-generic         | 27        | 1.48%   |
| 6.2.6-desktop-1omv2390   | 19        | 1.04%   |
| 5.4.0-58-generic         | 18        | 0.99%   |
| 5.15.0-56-generic        | 18        | 0.99%   |
| 5.4.0-52-generic         | 14        | 0.77%   |
| 5.3.0-46-generic         | 14        | 0.77%   |
| 5.15.0-48-generic        | 13        | 0.71%   |
| 5.4.0-91-generic         | 12        | 0.66%   |
| 5.4.0-48-generic         | 12        | 0.66%   |
| 5.19.0-38-generic        | 12        | 0.66%   |
| 5.15.0-58-generic        | 12        | 0.66%   |
| 5.11.0-27-generic        | 12        | 0.66%   |
| 5.0.0-37-generic         | 12        | 0.66%   |
| 6.1.1-desktop-1omv2290   | 11        | 0.6%    |
| 5.3.0-40-generic         | 11        | 0.6%    |
| 5.15.0-43-generic        | 11        | 0.6%    |
| 5.3.0-42-generic         | 10        | 0.55%   |
| 5.19.0-43-generic        | 10        | 0.55%   |
| 5.19.0-35-generic        | 10        | 0.55%   |
| 5.15.0-47-generic        | 10        | 0.55%   |
| 5.13.0-39-generic        | 10        | 0.55%   |
| 5.13.0-28-generic        | 10        | 0.55%   |
| 5.11.0-43-generic        | 10        | 0.55%   |
| 5.4.0-7642-generic       | 9         | 0.49%   |
| 5.4.0-74-generic         | 9         | 0.49%   |
| 5.4.0-65-generic         | 9         | 0.49%   |
| 5.4.0-45-generic         | 9         | 0.49%   |
| 5.3.0-28-generic         | 9         | 0.49%   |
| 5.15.0-52-generic        | 9         | 0.49%   |
| 5.13.0-40-generic        | 9         | 0.49%   |
| 5.11.0-7620-generic      | 9         | 0.49%   |
| 5.11.0-37-generic        | 9         | 0.49%   |
| 6.4.11-desktop-1omv2390  | 8         | 0.44%   |
| 6.2.6-76060206-generic   | 8         | 0.44%   |
| 5.8.0-43-generic         | 8         | 0.44%   |
| 5.4.0-37-generic         | 8         | 0.44%   |
| 5.15.0-60-generic        | 8         | 0.44%   |
| 4.18.0-25-generic        | 8         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 234       | 13.59%  |
| 5.15.0  | 159       | 9.23%   |
| 5.11.0  | 85        | 4.94%   |
| 5.13.0  | 81        | 4.7%    |
| 5.8.0   | 72        | 4.18%   |
| 5.3.0   | 72        | 4.18%   |
| 5.19.0  | 69        | 4.01%   |
| 4.15.0  | 65        | 3.77%   |
| 5.0.0   | 54        | 3.14%   |
| 5.10.0  | 52        | 3.02%   |
| 5.16.7  | 48        | 2.79%   |
| 4.18.0  | 48        | 2.79%   |
| 5.10.14 | 43        | 2.5%    |
| 6.2.0   | 31        | 1.8%    |
| 4.19.0  | 28        | 1.63%   |
| 6.2.6   | 27        | 1.57%   |
| 6.1.1   | 17        | 0.99%   |
| 6.1.0   | 16        | 0.93%   |
| 6.4.11  | 13        | 0.75%   |
| 6.4.6   | 9         | 0.52%   |
| 6.2.15  | 8         | 0.46%   |
| 5.17.5  | 8         | 0.46%   |
| 6.0.12  | 7         | 0.41%   |
| 5.14.0  | 7         | 0.41%   |
| 6.2.9   | 5         | 0.29%   |
| 6.2.14  | 5         | 0.29%   |
| 6.0.11  | 5         | 0.29%   |
| 6.0.0   | 5         | 0.29%   |
| 5.9.1   | 5         | 0.29%   |
| 5.15.8  | 5         | 0.29%   |
| 6.4.12  | 4         | 0.23%   |
| 6.3.7   | 4         | 0.23%   |
| 6.3.5   | 4         | 0.23%   |
| 6.1.9   | 4         | 0.23%   |
| 5.3.18  | 4         | 0.23%   |
| 5.19.8  | 4         | 0.23%   |
| 5.17.0  | 4         | 0.23%   |
| 5.16.0  | 4         | 0.23%   |
| 5.15.13 | 4         | 0.23%   |
| 4.9.20  | 4         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 251       | 14.79%  |
| 5.15    | 209       | 12.32%  |
| 5.10    | 124       | 7.31%   |
| 5.19    | 95        | 5.6%    |
| 5.11    | 94        | 5.54%   |
| 5.13    | 93        | 5.48%   |
| 6.2     | 87        | 5.13%   |
| 5.3     | 83        | 4.89%   |
| 5.8     | 79        | 4.66%   |
| 5.16    | 70        | 4.12%   |
| 4.15    | 65        | 3.83%   |
| 6.1     | 55        | 3.24%   |
| 5.0     | 54        | 3.18%   |
| 4.18    | 49        | 2.89%   |
| 6.4     | 44        | 2.59%   |
| 6.0     | 30        | 1.77%   |
| 4.19    | 30        | 1.77%   |
| 5.17    | 27        | 1.59%   |
| 6.3     | 24        | 1.41%   |
| 5.18    | 23        | 1.36%   |
| 5.14    | 20        | 1.18%   |
| 5.9     | 16        | 0.94%   |
| 5.6     | 12        | 0.71%   |
| 4.9     | 12        | 0.71%   |
| 5.12    | 11        | 0.65%   |
| 5.7     | 10        | 0.59%   |
| 6.5     | 8         | 0.47%   |
| 5.5     | 7         | 0.41%   |
| 4.4     | 4         | 0.24%   |
| 4.13    | 3         | 0.18%   |
| 5.2     | 2         | 0.12%   |
| 4.12    | 2         | 0.12%   |
| 5.1     | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 3.2     | 1         | 0.06%   |
| 3.10    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1489      | 96.88%  |
| i686   | 48        | 3.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 734       | 45.79%  |
| KDE5              | 300       | 18.71%  |
| Unknown           | 142       | 8.86%   |
| XFCE              | 115       | 7.17%   |
| X-Cinnamon        | 100       | 6.24%   |
| KDE               | 53        | 3.31%   |
| MATE              | 43        | 2.68%   |
| Pantheon          | 26        | 1.62%   |
| LXQt              | 17        | 1.06%   |
| Cinnamon          | 16        | 1%      |
| Budgie            | 10        | 0.62%   |
| Unity             | 7         | 0.44%   |
| LXDE              | 7         | 0.44%   |
| KDE4              | 5         | 0.31%   |
| i3                | 5         | 0.31%   |
| Deepin            | 5         | 0.31%   |
| openbox           | 4         | 0.25%   |
| Enlightenment     | 3         | 0.19%   |
| trinity           | 2         | 0.12%   |
| GNOME Classic     | 2         | 0.12%   |
| Yaru:ubuntu:GNOME | 1         | 0.06%   |
| xmonad            | 1         | 0.06%   |
| qtile             | 1         | 0.06%   |
| lightdm-xsession  | 1         | 0.06%   |
| Hyprland          | 1         | 0.06%   |
| GNOME Flashback   | 1         | 0.06%   |
| bspwm             | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1187      | 74.65%  |
| Wayland | 310       | 19.5%   |
| Unknown | 84        | 5.28%   |
| Tty     | 9         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 795       | 49.72%  |
| SDDM    | 248       | 15.51%  |
| GDM     | 185       | 11.57%  |
| GDM3    | 172       | 10.76%  |
| LightDM | 149       | 9.32%   |
| TDM     | 34        | 2.13%   |
| KDM     | 5         | 0.31%   |
| XDM     | 4         | 0.25%   |
| SLiM    | 3         | 0.19%   |
| LXDM    | 2         | 0.13%   |
| MDM     | 1         | 0.06%   |
| Ly      | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_MX      | 768       | 48.85%  |
| en_US      | 496       | 31.55%  |
| Unknown    | 132       | 8.4%    |
| es_ES      | 102       | 6.49%   |
| C          | 29        | 1.84%   |
| en_GB      | 15        | 0.95%   |
| es_US      | 5         | 0.32%   |
| fr_FR      | 3         | 0.19%   |
| en_CA      | 3         | 0.19%   |
| it_IT      | 2         | 0.13%   |
| es_MX.UTF8 | 2         | 0.13%   |
| es_AR      | 2         | 0.13%   |
| en_MX      | 2         | 0.13%   |
| C.UTF8     | 2         | 0.13%   |
| uk_UA      | 1         | 0.06%   |
| ru_RU      | 1         | 0.06%   |
| pt_BR      | 1         | 0.06%   |
| POSIX      | 1         | 0.06%   |
| es_PE      | 1         | 0.06%   |
| es_CR      | 1         | 0.06%   |
| es_419     | 1         | 0.06%   |
| en_IE      | 1         | 0.06%   |
| en_DK      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 805       | 51.14%  |
| BIOS | 769       | 48.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 1165      | 73.92%  |
| Btrfs               | 159       | 10.09%  |
| Overlay             | 140       | 8.88%   |
| Unknown             | 36        | 2.28%   |
| Tmpfs               | 33        | 2.09%   |
| Xfs                 | 24        | 1.52%   |
| Zfs                 | 9         | 0.57%   |
| Ext2                | 4         | 0.25%   |
| XXXXXXX             | 2         | 0.13%   |
| Ext3                | 2         | 0.13%   |
| Fuse.fuse-overlayfs | 1         | 0.06%   |
| Aufs                | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 860       | 54.57%  |
| GPT     | 549       | 34.84%  |
| MBR     | 167       | 10.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1390      | 89.16%  |
| Yes       | 169       | 10.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1084      | 69.27%  |
| Yes       | 481       | 30.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 364       | 23.7%   |
| Lenovo              | 295       | 19.21%  |
| Dell                | 236       | 15.36%  |
| Acer                | 118       | 7.68%   |
| ASUSTek Computer    | 111       | 7.23%   |
| Toshiba             | 73        | 4.75%   |
| HUAWEI              | 64        | 4.17%   |
| Apple               | 63        | 4.1%    |
| Sony                | 41        | 2.67%   |
| MSI                 | 21        | 1.37%   |
| Samsung Electronics | 19        | 1.24%   |
| Gateway             | 18        | 1.17%   |
| Google              | 15        | 0.98%   |
| Alienware           | 11        | 0.72%   |
| Chuwi               | 8         | 0.52%   |
| Unknown             | 8         | 0.52%   |
| Valve               | 7         | 0.46%   |
| Lanix               | 7         | 0.46%   |
| GPU Company         | 6         | 0.39%   |
| A-DATA Technology   | 5         | 0.33%   |
| HONOR               | 4         | 0.26%   |
| EVOO                | 4         | 0.26%   |
| Timi                | 3         | 0.2%    |
| System76            | 3         | 0.2%    |
| Notebook            | 3         | 0.2%    |
| eMachines           | 3         | 0.2%    |
| Panasonic           | 2         | 0.13%   |
| Insyde              | 2         | 0.13%   |
| GHIA                | 2         | 0.13%   |
| Corporativo Lanix   | 2         | 0.13%   |
| American Megatrends | 2         | 0.13%   |
| VPU Company         | 1         | 0.07%   |
| TECH PAD            | 1         | 0.07%   |
| SK hynix            | 1         | 0.07%   |
| Schenker            | 1         | 0.07%   |
| Razer               | 1         | 0.07%   |
| ONE-NETBOOK         | 1         | 0.07%   |
| LG Electronics      | 1         | 0.07%   |
| Lanix America       | 1         | 0.07%   |
| Hyundai Technology  | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 27        | 1.76%   |
| Unknown                       | 22        | 1.43%   |
| HUAWEI HVY-WXX9               | 18        | 1.17%   |
| HP Pavilion Laptop 15-cw0xxx  | 17        | 1.11%   |
| HP Pavilion g4                | 15        | 0.98%   |
| HP Pavilion Notebook          | 14        | 0.91%   |
| HP Pavilion Laptop 15-cw1xxx  | 10        | 0.65%   |
| Dell Latitude E6430           | 10        | 0.65%   |
| Apple MacBookPro9,2           | 10        | 0.65%   |
| Apple MacBookPro8,1           | 10        | 0.65%   |
| HP Laptop 15-da0xxx           | 9         | 0.59%   |
| Lenovo IdeaPad 330-14AST 81D5 | 8         | 0.52%   |
| HP Laptop 15-bw0xx            | 8         | 0.52%   |
| HP EliteBook 8460p            | 8         | 0.52%   |
| Valve Jupiter                 | 7         | 0.46%   |
| HP Pavilion dv4               | 7         | 0.46%   |
| Dell Inspiron 5559            | 7         | 0.46%   |
| Apple MacBookPro12,1          | 7         | 0.46%   |
| HUAWEI NBLB-WAX9N             | 6         | 0.39%   |
| HP Pavilion dv5               | 6         | 0.39%   |
| HP Pavilion 14                | 6         | 0.39%   |
| HP Laptop 15-db0xxx           | 6         | 0.39%   |
| HP Laptop 14-cm0xxx           | 6         | 0.39%   |
| Dell Inspiron 3421            | 6         | 0.39%   |
| Acer Aspire E5-573            | 6         | 0.39%   |
| Lenovo Y720-15IKB 80VR        | 5         | 0.33%   |
| Lenovo Y50-70 20378           | 5         | 0.33%   |
| Lenovo G50-30 80G0            | 5         | 0.33%   |
| Lenovo G40-45 80E1            | 5         | 0.33%   |
| HUAWEI NBLK-WAX9X             | 5         | 0.33%   |
| HUAWEI BOHK-WAX9X             | 5         | 0.33%   |
| HP Laptop 15-da2xxx           | 5         | 0.33%   |
| HP Laptop 15-bs0xx            | 5         | 0.33%   |
| HP G42                        | 5         | 0.33%   |
| GPU Company GWNR71517         | 5         | 0.33%   |
| Dell Latitude E6400           | 5         | 0.33%   |
| Dell Latitude E5470           | 5         | 0.33%   |
| Dell Inspiron 5570            | 5         | 0.33%   |
| Apple MacBook4,1              | 5         | 0.33%   |
| Acer Aspire E3-112M           | 5         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 116       | 7.55%   |
| Lenovo ThinkPad    | 114       | 7.42%   |
| Lenovo IdeaPad     | 107       | 6.97%   |
| Dell Latitude      | 92        | 5.99%   |
| Dell Inspiron      | 88        | 5.73%   |
| Acer Aspire        | 83        | 5.4%    |
| Toshiba Satellite  | 67        | 4.36%   |
| HP Laptop          | 66        | 4.3%    |
| HP Notebook        | 27        | 1.76%   |
| HP EliteBook       | 27        | 1.76%   |
| HP ProBook         | 26        | 1.69%   |
| ASUS VivoBook      | 26        | 1.69%   |
| Unknown            | 22        | 1.43%   |
| HUAWEI HVY-WXX9    | 18        | 1.17%   |
| HP Compaq          | 13        | 0.85%   |
| Lenovo Legion      | 11        | 0.72%   |
| HP ENVY            | 11        | 0.72%   |
| HP 240             | 11        | 0.72%   |
| Dell Vostro        | 11        | 0.72%   |
| Apple MacBookPro9  | 11        | 0.72%   |
| Apple MacBookPro8  | 11        | 0.72%   |
| Dell XPS           | 10        | 0.65%   |
| Dell Studio        | 9         | 0.59%   |
| Dell Precision     | 9         | 0.59%   |
| ASUS ASUS          | 9         | 0.59%   |
| HP OMEN            | 8         | 0.52%   |
| Acer Nitro         | 8         | 0.52%   |
| Valve Jupiter      | 7         | 0.46%   |
| Apple MacBookPro12 | 7         | 0.46%   |
| HUAWEI NBLB-WAX9N  | 6         | 0.39%   |
| HP ZBook           | 6         | 0.39%   |
| Apple MacBookAir6  | 6         | 0.39%   |
| MSI GF63           | 5         | 0.33%   |
| Lenovo Yoga        | 5         | 0.33%   |
| Lenovo Y720-15IKB  | 5         | 0.33%   |
| Lenovo Y50-70      | 5         | 0.33%   |
| Lenovo G50-30      | 5         | 0.33%   |
| Lenovo G40-45      | 5         | 0.33%   |
| HUAWEI NBLK-WAX9X  | 5         | 0.33%   |
| HUAWEI BOHK-WAX9X  | 5         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 139       | 9.05%   |
| 2011    | 135       | 8.79%   |
| 2019    | 130       | 8.46%   |
| 2020    | 123       | 8.01%   |
| 2012    | 118       | 7.68%   |
| 2015    | 109       | 7.1%    |
| 2013    | 107       | 6.97%   |
| 2021    | 105       | 6.84%   |
| 2017    | 103       | 6.71%   |
| 2014    | 101       | 6.58%   |
| 2010    | 82        | 5.34%   |
| 2016    | 79        | 5.14%   |
| 2008    | 76        | 4.95%   |
| 2022    | 38        | 2.47%   |
| 2009    | 38        | 2.47%   |
| 2007    | 28        | 1.82%   |
| 2023    | 8         | 0.52%   |
| 2006    | 8         | 0.52%   |
| 2005    | 4         | 0.26%   |
| Unknown | 3         | 0.2%    |
| 2004    | 2         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1536      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1371      | 88.17%  |
| Enabled  | 184       | 11.83%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1519      | 98.89%  |
| Yes  | 17        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 465       | 29.88%  |
| 3.01-4.0    | 359       | 23.07%  |
| 8.01-16.0   | 305       | 19.6%   |
| 16.01-24.0  | 197       | 12.66%  |
| 1.01-2.0    | 98        | 6.3%    |
| 32.01-64.0  | 48        | 3.08%   |
| 2.01-3.0    | 35        | 2.25%   |
| 24.01-32.0  | 21        | 1.35%   |
| 0.51-1.0    | 17        | 1.09%   |
| 64.01-256.0 | 11        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 612       | 36.15%  |
| 2.01-3.0   | 478       | 28.23%  |
| 3.01-4.0   | 224       | 13.23%  |
| 4.01-8.0   | 196       | 11.58%  |
| 0.51-1.0   | 109       | 6.44%   |
| 8.01-16.0  | 52        | 3.07%   |
| 0.01-0.5   | 14        | 0.83%   |
| 16.01-24.0 | 6         | 0.35%   |
| 32.01-64.0 | 1         | 0.06%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1177      | 75.06%  |
| 2      | 339       | 21.62%  |
| 3      | 26        | 1.66%   |
| 0      | 19        | 1.21%   |
| 4      | 5         | 0.32%   |
| 6      | 1         | 0.06%   |
| 5      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 998       | 64.68%  |
| Yes       | 545       | 35.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1248      | 81.25%  |
| No        | 288       | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1510      | 98.24%  |
| No        | 27        | 1.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1154      | 74.12%  |
| No        | 403       | 25.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Mexico  | 1536      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 337       | 20.76%  |
| Guadalajara           | 76        | 4.68%   |
| Monterrey             | 51        | 3.14%   |
| Puebla City           | 50        | 3.08%   |
| Zapopan               | 48        | 2.96%   |
| Tijuana               | 43        | 2.65%   |
| Queretaro             | 33        | 2.03%   |
| Mérida               | 28        | 1.73%   |
| Toluca                | 26        | 1.6%    |
| Cancún               | 24        | 1.48%   |
| Xalapa                | 19        | 1.17%   |
| Veracruz              | 19        | 1.17%   |
| Mexicali              | 19        | 1.17%   |
| Ciudad Lopez Mateos   | 19        | 1.17%   |
| Ciudad Juárez        | 19        | 1.17%   |
| Hermosillo            | 18        | 1.11%   |
| Ecatepec              | 18        | 1.11%   |
| Naucalpan             | 17        | 1.05%   |
| Tlalnepantla          | 16        | 0.99%   |
| León                 | 16        | 0.99%   |
| Culiacán             | 16        | 0.99%   |
| Morelia               | 15        | 0.92%   |
| Cuernavaca            | 15        | 0.92%   |
| Apodaca               | 15        | 0.92%   |
| Villahermosa          | 14        | 0.86%   |
| Saltillo              | 13        | 0.8%    |
| Oaxaca City           | 13        | 0.8%    |
| Guadalupe             | 13        | 0.8%    |
| Chihuahua City        | 13        | 0.8%    |
| Celaya                | 13        | 0.8%    |
| Mexico                | 12        | 0.74%   |
| Iztapalapa            | 12        | 0.74%   |
| Durango               | 12        | 0.74%   |
| Ciudad Nezahualcoyotl | 12        | 0.74%   |
| San Luis Potosí City | 11        | 0.68%   |
| Ensenada              | 11        | 0.68%   |
| Cuautitlán Izcalli   | 11        | 0.68%   |
| Zacatecas City        | 10        | 0.62%   |
| Gustavo Adolfo Madero | 10        | 0.62%   |
| Azcapotzalco          | 10        | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 264       | 332    | 14.04%  |
| WDC                         | 242       | 305    | 12.87%  |
| Toshiba                     | 192       | 234    | 10.21%  |
| Kingston                    | 182       | 224    | 9.68%   |
| Samsung Electronics         | 149       | 197    | 7.93%   |
| A-DATA Technology           | 119       | 141    | 6.33%   |
| Unknown                     | 106       | 128    | 5.64%   |
| Hitachi                     | 80        | 89     | 4.26%   |
| Sandisk                     | 74        | 95     | 3.94%   |
| HGST                        | 72        | 77     | 3.83%   |
| SK hynix                    | 43        | 52     | 2.29%   |
| Intel                       | 40        | 55     | 2.13%   |
| Apple                       | 29        | 37     | 1.54%   |
| Micron Technology           | 21        | 24     | 1.12%   |
| Crucial                     | 21        | 23     | 1.12%   |
| XPG                         | 15        | 23     | 0.8%    |
| Fujitsu                     | 14        | 15     | 0.74%   |
| Silicon Motion              | 13        | 13     | 0.69%   |
| KIOXIA                      | 12        | 14     | 0.64%   |
| LITEON                      | 11        | 16     | 0.59%   |
| Realtek Semiconductor       | 10        | 11     | 0.53%   |
| Phison                      | 10        | 10     | 0.53%   |
| ADATA Technology            | 10        | 11     | 0.53%   |
| Unknown                     | 10        | 10     | 0.53%   |
| China                       | 9         | 9      | 0.48%   |
| YMTC                        | 8         | 9      | 0.43%   |
| PNY                         | 7         | 9      | 0.37%   |
| Phison Electronics          | 7         | 9      | 0.37%   |
| Netac                       | 6         | 6      | 0.32%   |
| UMIS                        | 5         | 6      | 0.27%   |
| JMicron Technology          | 5         | 5      | 0.27%   |
| AS201                       | 5         | 5      | 0.27%   |
| Wibtek                      | 4         | 4      | 0.21%   |
| Patriot                     | 4         | 7      | 0.21%   |
| LITEONIT                    | 4         | 4      | 0.21%   |
| Kingston Technology Company | 4         | 4      | 0.21%   |
| Hewlett-Packard             | 4         | 4      | 0.21%   |
| WALRAM                      | 3         | 7      | 0.16%   |
| Union Memory (Shenzhen)     | 3         | 3      | 0.16%   |
| SABRENT                     | 3         | 3      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 61        | 3.13%   |
| Kingston SA400S37240G 240GB SSD                     | 42        | 2.16%   |
| Kingston SA400S37480G 480GB SSD                     | 41        | 2.11%   |
| Toshiba MQ01ABD100 1TB                              | 38        | 1.95%   |
| Toshiba MQ04ABF100 1TB                              | 36        | 1.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 36        | 1.85%   |
| Unknown MMC Card  32GB                              | 24        | 1.23%   |
| Toshiba MQ01ABF050 500GB                            | 22        | 1.13%   |
| Seagate ST500LT012-1DG142 500GB                     | 22        | 1.13%   |
| A-DATA SU650 120GB SSD                              | 20        | 1.03%   |
| A-DATA SU630 240GB SSD                              | 18        | 0.92%   |
| Kingston SA400S37960G 960GB SSD                     | 17        | 0.87%   |
| Unknown MMC Card  64GB                              | 16        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 14        | 0.72%   |
| HGST HTS725050A7E630 500GB                          | 13        | 0.67%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 12        | 0.62%   |
| Seagate ST500LM021-1KJ152 500GB                     | 12        | 0.62%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.62%   |
| HGST HTS541010A9E680 1TB                            | 12        | 0.62%   |
| Unknown MMC Card  16GB                              | 11        | 0.56%   |
| Samsung NVMe SSD Drive 512GB                        | 11        | 0.56%   |
| A-DATA SU650 240GB SSD                              | 11        | 0.56%   |
| A-DATA SU630 480GB SSD                              | 11        | 0.56%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 10        | 0.51%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 10        | 0.51%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 10        | 0.51%   |
| Seagate ST9500325AS 500GB                           | 10        | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 10        | 0.51%   |
| Unknown                                             | 10        | 0.51%   |
| WDC WD10SPZX-08Z10 1TB                              | 9         | 0.46%   |
| Silicon Motion PCIe-8 SSD 512GB                     | 9         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB                      | 9         | 0.46%   |
| Seagate Expansion 1TB                               | 9         | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 9         | 0.46%   |
| HGST HTS541075A9E680 752GB                          | 9         | 0.46%   |
| Unknown MMC Card  128GB                             | 8         | 0.41%   |
| YMTC PC005 512GB                                    | 7         | 0.36%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 7         | 0.36%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 7         | 0.36%   |
| Seagate ST1000LM049-2GH172 1TB                      | 7         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 261       | 327    | 31.48%  |
| WDC                 | 200       | 246    | 24.13%  |
| Toshiba             | 169       | 207    | 20.39%  |
| Hitachi             | 80        | 89     | 9.65%   |
| HGST                | 72        | 77     | 8.69%   |
| Samsung Electronics | 15        | 17     | 1.81%   |
| Fujitsu             | 14        | 15     | 1.69%   |
| Unknown             | 6         | 6      | 0.72%   |
| Apple               | 4         | 5      | 0.48%   |
| Pioneer             | 2         | 3      | 0.24%   |
| Hewlett-Packard     | 2         | 2      | 0.24%   |
| SAGE                | 1         | 1      | 0.12%   |
| SABRENT             | 1         | 1      | 0.12%   |
| LaCie               | 1         | 2      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 163       | 201    | 31.05%  |
| A-DATA Technology   | 112       | 134    | 21.33%  |
| Samsung Electronics | 45        | 50     | 8.57%   |
| SanDisk             | 29        | 34     | 5.52%   |
| WDC                 | 22        | 30     | 4.19%   |
| Apple               | 20        | 22     | 3.81%   |
| Crucial             | 18        | 18     | 3.43%   |
| SK hynix            | 10        | 11     | 1.9%    |
| LITEON              | 10        | 15     | 1.9%    |
| China               | 9         | 9      | 1.71%   |
| Micron Technology   | 8         | 9      | 1.52%   |
| PNY                 | 7         | 9      | 1.33%   |
| Intel               | 7         | 9      | 1.33%   |
| Netac               | 6         | 6      | 1.14%   |
| AS201               | 5         | 5      | 0.95%   |
| LITEONIT            | 4         | 4      | 0.76%   |
| Unknown             | 4         | 4      | 0.76%   |
| Wibtek              | 3         | 3      | 0.57%   |
| Toshiba             | 3         | 3      | 0.57%   |
| Patriot             | 3         | 6      | 0.57%   |
| Gigabyte Technology | 3         | 3      | 0.57%   |
| BHT                 | 3         | 3      | 0.57%   |
| Unknown             | 2         | 2      | 0.38%   |
| OCZ                 | 2         | 4      | 0.38%   |
| JMicron Technology  | 2         | 2      | 0.38%   |
| Hewlett-Packard     | 2         | 2      | 0.38%   |
| Dogfish             | 2         | 5      | 0.38%   |
| Blackpcs            | 2         | 2      | 0.38%   |
| ZTC                 | 1         | 1      | 0.19%   |
| Zheino              | 1         | 1      | 0.19%   |
| Yeyian              | 1         | 3      | 0.19%   |
| Transcend           | 1         | 1      | 0.19%   |
| tecmiyo             | 1         | 1      | 0.19%   |
| Team                | 1         | 1      | 0.19%   |
| StoreJet            | 1         | 1      | 0.19%   |
| SSSTC               | 1         | 1      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| ShanDianZhe         | 1         | 2      | 0.19%   |
| Pioneer             | 1         | 1      | 0.19%   |
| Lexar               | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 812       | 999    | 44.79%  |
| SSD     | 491       | 632    | 27.08%  |
| NVMe    | 379       | 517    | 20.9%   |
| MMC     | 104       | 128    | 5.74%   |
| Unknown | 27        | 32     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1188      | 1592   | 68.59%  |
| NVMe | 378       | 516    | 21.82%  |
| MMC  | 104       | 128    | 6%      |
| SAS  | 62        | 72     | 3.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 821       | 1035   | 63.45%  |
| 0.51-1.0   | 440       | 546    | 34%     |
| 1.01-2.0   | 29        | 46     | 2.24%   |
| 4.01-10.0  | 2         | 2      | 0.15%   |
| 3.01-4.0   | 1         | 1      | 0.08%   |
| 10.01-20.0 | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 433       | 26.89%  |
| 251-500        | 400       | 24.84%  |
| 501-1000       | 271       | 16.83%  |
| 1-20           | 141       | 8.76%   |
| 51-100         | 133       | 8.26%   |
| 1001-2000      | 95        | 5.9%    |
| 21-50          | 75        | 4.66%   |
| More than 3000 | 25        | 1.55%   |
| 2001-3000      | 20        | 1.24%   |
| Unknown        | 17        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 716       | 42.82%  |
| 21-50          | 332       | 19.86%  |
| 101-250        | 207       | 12.38%  |
| 51-100         | 186       | 11.12%  |
| 251-500        | 116       | 6.94%   |
| 501-1000       | 65        | 3.89%   |
| 1001-2000      | 24        | 1.44%   |
| Unknown        | 17        | 1.02%   |
| More than 3000 | 6         | 0.36%   |
| 2001-3000      | 3         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 6         | 7      | 4.29%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 3.57%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 3.57%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 2.86%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 2.86%   |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 2.86%   |
| Toshiba MQ04ABF100 1TB              | 3         | 3      | 2.14%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 2.14%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 1.43%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 2      | 1.43%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 1.43%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 1.43%   |
| Seagate ST9500420AS 500GB           | 2         | 2      | 1.43%   |
| Seagate ST9320325AS 320GB           | 2         | 4      | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 1.43%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 1.43%   |
| LITEON CV8-8E128-HP 128GB SSD       | 2         | 2      | 1.43%   |
| Hitachi HTS545016B9A300 160GB       | 2         | 2      | 1.43%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 2      | 1.43%   |
| HGST HTS541010A7E630 1TB            | 2         | 2      | 1.43%   |
| China SSD 256GB                     | 2         | 2      | 1.43%   |
| A-DATA Technology SU650 240GB SSD   | 2         | 2      | 1.43%   |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 2      | 0.71%   |
| WDC WD50 00BEVT-11ZAT0 500GB        | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 1      | 0.71%   |
| WDC WD2500LPVX-22V0TT0 250GB        | 1         | 1      | 0.71%   |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 2      | 0.71%   |
| WDC WD1600BEVT-60ZCT0 160GB         | 1         | 1      | 0.71%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 0.71%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1      | 0.71%   |
| WDC WD10SPCX-60KHST0 1TB            | 1         | 1      | 0.71%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 0.71%   |
| WDC WD10JPVX-55JC3T3 1TB            | 1         | 1      | 0.71%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 0.71%   |
| Toshiba MK7559GSXP 752GB            | 1         | 8      | 0.71%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 32     | 19.42%  |
| Toshiba             | 26        | 34     | 18.71%  |
| Hitachi             | 22        | 23     | 15.83%  |
| WDC                 | 21        | 23     | 15.11%  |
| HGST                | 14        | 15     | 10.07%  |
| Kingston            | 9         | 9      | 6.47%   |
| SanDisk             | 4         | 4      | 2.88%   |
| Fujitsu             | 4         | 4      | 2.88%   |
| Samsung Electronics | 3         | 3      | 2.16%   |
| LITEON              | 2         | 2      | 1.44%   |
| China               | 2         | 2      | 1.44%   |
| A-DATA Technology   | 2         | 2      | 1.44%   |
| Micron Technology   | 1         | 1      | 0.72%   |
| Intel               | 1         | 1      | 0.72%   |
| Crucial             | 1         | 1      | 0.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 32     | 23.28%  |
| Toshiba             | 26        | 34     | 22.41%  |
| Hitachi             | 22        | 23     | 18.97%  |
| WDC                 | 21        | 23     | 18.1%   |
| HGST                | 14        | 15     | 12.07%  |
| Fujitsu             | 4         | 4      | 3.45%   |
| Samsung Electronics | 2         | 2      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 116       | 133    | 83.45%  |
| SSD  | 19        | 19     | 13.67%  |
| NVMe | 4         | 4      | 2.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB  | 1         | 1      | 33.33%  |
| Toshiba MK1234GSX 120GB       | 1         | 1      | 33.33%  |
| Hitachi HTS545016B9A300 160GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 971       | 1459   | 60.35%  |
| Works    | 498       | 690    | 30.95%  |
| Malfunc  | 137       | 156    | 8.51%   |
| Failed   | 3         | 3      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1017      | 58.96%  |
| AMD                                     | 306       | 17.74%  |
| Samsung Electronics                     | 99        | 5.74%   |
| SanDisk                                 | 64        | 3.71%   |
| SK hynix                                | 32        | 1.86%   |
| Kingston Technology Company             | 24        | 1.39%   |
| ADATA Technology                        | 24        | 1.39%   |
| Toshiba America Info Systems            | 21        | 1.22%   |
| Nvidia                                  | 19        | 1.1%    |
| Phison Electronics                      | 17        | 0.99%   |
| Realtek Semiconductor                   | 15        | 0.87%   |
| Silicon Motion                          | 13        | 0.75%   |
| Micron Technology                       | 13        | 0.75%   |
| KIOXIA                                  | 13        | 0.75%   |
| Union Memory (Shenzhen)                 | 10        | 0.58%   |
| Yangtze Memory Technologies             | 8         | 0.46%   |
| Marvell Technology Group                | 7         | 0.41%   |
| Micron/Crucial Technology               | 5         | 0.29%   |
| Apple                                   | 5         | 0.29%   |
| Solid State Storage Technology          | 2         | 0.12%   |
| Lite-On Technology                      | 2         | 0.12%   |
| Lenovo                                  | 2         | 0.12%   |
| Solidigm                                | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| Seagate Technology                      | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| Unknown                                 | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 250       | 13.48%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 117       | 6.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 116       | 6.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 87        | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 86        | 4.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 51        | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 46        | 2.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 44        | 2.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 41        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 2.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 38        | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 36        | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 36        | 1.94%   |
| Samsung NVMe SSD Controller 980                                                  | 33        | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 33        | 1.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 31        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 31        | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 28        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 1.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 22        | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 22        | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 20        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 19        | 1.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 17        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 16        | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 14        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 14        | 0.76%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 14        | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                                | 13        | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 13        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 0.65%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 12        | 0.65%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 12        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 12        | 0.65%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 0.65%   |
| Silicon Motion Non-Volatile memory controller                                    | 10        | 0.54%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 10        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1151      | 64.02%  |
| NVMe | 380       | 21.13%  |
| RAID | 148       | 8.23%   |
| IDE  | 119       | 6.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1147      | 74.67%  |
| AMD    | 389       | 25.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 1.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 1.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 1.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 22        | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 19        | 1.24%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 18        | 1.17%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 1.11%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 17        | 1.11%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 17        | 1.11%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 16        | 1.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 16        | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.98%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.91%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 0.78%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 12        | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 12        | 0.78%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 12        | 0.78%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 12        | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 0.78%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 12        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 10        | 0.65%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 10        | 0.65%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 10        | 0.65%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 10        | 0.65%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 10        | 0.65%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 10        | 0.65%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 10        | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 310       | 20.18%  |
| Intel Core i7                  | 276       | 17.97%  |
| Intel Celeron                  | 166       | 10.81%  |
| Intel Core i3                  | 138       | 8.98%   |
| Other                          | 93        | 6.05%   |
| AMD Ryzen 5                    | 84        | 5.47%   |
| Intel Core 2 Duo               | 64        | 4.17%   |
| Intel Atom                     | 44        | 2.86%   |
| AMD Ryzen 7                    | 44        | 2.86%   |
| AMD A6                         | 29        | 1.89%   |
| Intel Pentium                  | 28        | 1.82%   |
| AMD A8                         | 28        | 1.82%   |
| AMD Ryzen 3                    | 25        | 1.63%   |
| AMD A4                         | 22        | 1.43%   |
| AMD E                          | 21        | 1.37%   |
| AMD A10                        | 20        | 1.3%    |
| Intel Pentium Dual             | 16        | 1.04%   |
| AMD Turion 64 X2 Mobile        | 10        | 0.65%   |
| AMD Athlon II                  | 10        | 0.65%   |
| Intel Pentium Dual-Core        | 9         | 0.59%   |
| Intel Genuine                  | 8         | 0.52%   |
| AMD Ryzen 5 PRO                | 7         | 0.46%   |
| Intel Core 2                   | 6         | 0.39%   |
| AMD Ryzen 9                    | 6         | 0.39%   |
| AMD FX                         | 6         | 0.39%   |
| AMD E1                         | 6         | 0.39%   |
| Intel Pentium Silver           | 5         | 0.33%   |
| AMD Athlon                     | 5         | 0.33%   |
| AMD A12                        | 5         | 0.33%   |
| AMD E2                         | 4         | 0.26%   |
| AMD Athlon 64 X2               | 4         | 0.26%   |
| Intel Celeron M                | 3         | 0.2%    |
| AMD Sempron                    | 3         | 0.2%    |
| Intel Xeon                     | 2         | 0.13%   |
| Intel Pentium M                | 2         | 0.13%   |
| Intel Core Duo                 | 2         | 0.13%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.13%   |
| AMD C-60                       | 2         | 0.13%   |
| AMD Athlon X2                  | 2         | 0.13%   |
| AMD Athlon II Neo              | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 896       | 58.33%  |
| 4      | 419       | 27.28%  |
| 6      | 101       | 6.58%   |
| 1      | 66        | 4.3%    |
| 8      | 39        | 2.54%   |
| 10     | 6         | 0.39%   |
| 14     | 5         | 0.33%   |
| 12     | 3         | 0.2%    |
| 3      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1536      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1006      | 65.49%  |
| 1      | 529       | 34.44%  |
| 4      | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1499      | 97.59%  |
| 32-bit         | 18        | 1.17%   |
| Unknown        | 14        | 0.91%   |
| 64-bit         | 5         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 424       | 26.5%   |
| 0x206a7    | 92        | 5.75%   |
| 0x306a9    | 72        | 4.5%    |
| 0x40651    | 53        | 3.31%   |
| 0x806ec    | 43        | 2.69%   |
| 0x30678    | 39        | 2.44%   |
| 0x306d4    | 38        | 2.38%   |
| 0x806e9    | 36        | 2.25%   |
| 0x1067a    | 33        | 2.06%   |
| 0x806ea    | 32        | 2%      |
| 0x806c1    | 32        | 2%      |
| 0x08108109 | 32        | 2%      |
| 0x06006705 | 32        | 2%      |
| 0x906ea    | 31        | 1.94%   |
| 0x406e3    | 30        | 1.88%   |
| 0x20655    | 26        | 1.63%   |
| 0x08600106 | 25        | 1.56%   |
| 0x6fd      | 22        | 1.38%   |
| 0x406c4    | 22        | 1.38%   |
| 0x406c3    | 22        | 1.38%   |
| 0x306c3    | 22        | 1.38%   |
| 0x106ca    | 21        | 1.31%   |
| 0x506e3    | 20        | 1.25%   |
| 0x0810100b | 20        | 1.25%   |
| 0x10676    | 18        | 1.13%   |
| 0x08108102 | 18        | 1.13%   |
| 0x20652    | 17        | 1.06%   |
| 0x08608103 | 17        | 1.06%   |
| 0x07030105 | 17        | 1.06%   |
| 0xa0652    | 16        | 1%      |
| 0x706e5    | 15        | 0.94%   |
| 0x506c9    | 15        | 0.94%   |
| 0x06001119 | 15        | 0.94%   |
| 0x05000119 | 15        | 0.94%   |
| 0x906e9    | 14        | 0.88%   |
| 0x706a1    | 14        | 0.88%   |
| 0x010000c8 | 12        | 0.75%   |
| 0x706a8    | 10        | 0.63%   |
| 0x06006704 | 10        | 0.63%   |
| 0x106c2    | 9         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 218       | 14.19%  |
| SandyBridge      | 127       | 8.27%   |
| IvyBridge        | 100       | 6.51%   |
| Haswell          | 99        | 6.45%   |
| Silvermont       | 96        | 6.25%   |
| Skylake          | 71        | 4.62%   |
| Excavator        | 69        | 4.49%   |
| Zen+             | 62        | 4.04%   |
| Penryn           | 62        | 4.04%   |
| Broadwell        | 58        | 3.78%   |
| Westmere         | 50        | 3.26%   |
| Core             | 48        | 3.13%   |
| Unknown          | 46        | 2.99%   |
| Zen 2            | 42        | 2.73%   |
| TigerLake        | 40        | 2.6%    |
| Goldmont plus    | 37        | 2.41%   |
| Bonnell          | 32        | 2.08%   |
| Bobcat           | 30        | 1.95%   |
| CometLake        | 28        | 1.82%   |
| Zen              | 27        | 1.76%   |
| Puma             | 24        | 1.56%   |
| Piledriver       | 24        | 1.56%   |
| Goldmont         | 23        | 1.5%    |
| Icelake          | 20        | 1.3%    |
| K8 Hammer        | 18        | 1.17%   |
| K10              | 18        | 1.17%   |
| Zen 3            | 12        | 0.78%   |
| Alderlake Hybrid | 12        | 0.78%   |
| P6               | 10        | 0.65%   |
| K8 & K10 hybrid  | 9         | 0.59%   |
| Jaguar           | 9         | 0.59%   |
| K10 Llano        | 6         | 0.39%   |
| Tremont          | 3         | 0.2%    |
| Steamroller      | 3         | 0.2%    |
| Nehalem          | 2         | 0.13%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1086      | 60.6%   |
| AMD                              | 432       | 24.11%  |
| Nvidia                           | 273       | 15.23%  |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 119       | 6.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 93        | 4.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 68        | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 65        | 3.48%   |
| Intel HD Graphics 5500                                                                   | 50        | 2.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 50        | 2.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 2.46%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 45        | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 44        | 2.36%   |
| Intel HD Graphics 620                                                                    | 43        | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 2.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 42        | 2.25%   |
| AMD Renoir                                                                               | 41        | 2.19%   |
| Intel UHD Graphics 620                                                                   | 36        | 1.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 36        | 1.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 1.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 34        | 1.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 32        | 1.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 32        | 1.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 27        | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 1.45%   |
| Intel HD Graphics 530                                                                    | 25        | 1.34%   |
| AMD Lucienne                                                                             | 25        | 1.34%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 24        | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24        | 1.28%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21        | 1.12%   |
| Intel HD Graphics 630                                                                    | 20        | 1.07%   |
| Intel HD Graphics 500                                                                    | 20        | 1.07%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 0.96%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 18        | 0.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 0.91%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.75%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 14        | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 13        | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 11        | 0.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 845       | 54.94%  |
| 1 x AMD        | 344       | 22.37%  |
| Intel + Nvidia | 189       | 12.29%  |
| 1 x Nvidia     | 59        | 3.84%   |
| Intel + AMD    | 37        | 2.41%   |
| 2 x AMD        | 27        | 1.76%   |
| AMD + Nvidia   | 24        | 1.56%   |
| 2 x Intel      | 8         | 0.52%   |
| Other          | 4         | 0.26%   |
| 1 x SiS        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1384      | 89.46%  |
| Proprietary | 134       | 8.66%   |
| Unknown     | 29        | 1.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1036      | 65.99%  |
| 0.01-0.5   | 221       | 14.08%  |
| 1.01-2.0   | 124       | 7.9%    |
| 0.51-1.0   | 99        | 6.31%   |
| 3.01-4.0   | 53        | 3.38%   |
| 5.01-6.0   | 20        | 1.27%   |
| 7.01-8.0   | 12        | 0.76%   |
| 2.01-3.0   | 5         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 298       | 17.17%  |
| BOE                     | 290       | 16.71%  |
| Chimei Innolux          | 250       | 14.4%   |
| LG Display              | 233       | 13.42%  |
| Samsung Electronics     | 178       | 10.25%  |
| Apple                   | 66        | 3.8%    |
| Chi Mei Optoelectronics | 41        | 2.36%   |
| Goldstar                | 34        | 1.96%   |
| Hewlett-Packard         | 33        | 1.9%    |
| Lenovo                  | 32        | 1.84%   |
| Dell                    | 26        | 1.5%    |
| LG Philips              | 23        | 1.32%   |
| BenQ                    | 23        | 1.32%   |
| Sharp                   | 19        | 1.09%   |
| PANDA                   | 18        | 1.04%   |
| Acer                    | 17        | 0.98%   |
| AOC                     | 12        | 0.69%   |
| HannStar                | 11        | 0.63%   |
| Unknown                 | 10        | 0.58%   |
| InfoVision              | 8         | 0.46%   |
| Valve                   | 6         | 0.35%   |
| Sony                    | 6         | 0.35%   |
| InnoLux Display         | 5         | 0.29%   |
| CSO                     | 5         | 0.29%   |
| CPT                     | 5         | 0.29%   |
| Unknown (AAA)           | 4         | 0.23%   |
| SLD                     | 4         | 0.23%   |
| JDI                     | 4         | 0.23%   |
| HKC                     | 4         | 0.23%   |
| Gateway                 | 4         | 0.23%   |
| FOX                     | 4         | 0.23%   |
| ___                     | 3         | 0.17%   |
| Vizio                   | 3         | 0.17%   |
| ViewSonic               | 3         | 0.17%   |
| Toshiba                 | 3         | 0.17%   |
| TMX                     | 3         | 0.17%   |
| HUAWEI                  | 3         | 0.17%   |
| Hitachi                 | 3         | 0.17%   |
| ASUSTek Computer        | 3         | 0.17%   |
| Westinghouse            | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 21        | 1.2%    |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                 | 17        | 0.97%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 16        | 0.91%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 15        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 14        | 0.8%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 14        | 0.8%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 13        | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 12        | 0.69%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 12        | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 12        | 0.69%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 12        | 0.69%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 10        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch        | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 10        | 0.57%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 9         | 0.51%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 8         | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 8         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 8         | 0.46%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 8         | 0.46%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 7         | 0.4%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch      | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch        | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 7         | 0.4%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 7         | 0.4%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 6         | 0.34%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 6         | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 6         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 6         | 0.34%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 6         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 794       | 48.18%  |
| 1920x1080 (FHD)    | 472       | 28.64%  |
| 1280x800 (WXGA)    | 98        | 5.95%   |
| 1600x900 (HD+)     | 46        | 2.79%   |
| 1440x900 (WXGA+)   | 29        | 1.76%   |
| 3840x2160 (4K)     | 28        | 1.7%    |
| 1024x600           | 26        | 1.58%   |
| 2160x1440          | 16        | 0.97%   |
| 2560x1600          | 15        | 0.91%   |
| 2560x1440 (QHD)    | 15        | 0.91%   |
| 1920x1200 (WUXGA)  | 11        | 0.67%   |
| 3440x1440          | 9         | 0.55%   |
| 2560x1080          | 9         | 0.55%   |
| 1360x768           | 8         | 0.49%   |
| 1280x1024 (SXGA)   | 8         | 0.49%   |
| 800x1280           | 7         | 0.42%   |
| 2880x1800          | 7         | 0.42%   |
| 1680x1050 (WSXGA+) | 7         | 0.42%   |
| 1024x768 (XGA)     | 7         | 0.42%   |
| 3200x1800 (QHD+)   | 5         | 0.3%    |
| 3000x2000          | 5         | 0.3%    |
| Unknown            | 4         | 0.24%   |
| 2520x1680          | 3         | 0.18%   |
| 3840x2400          | 2         | 0.12%   |
| 2288x1287          | 2         | 0.12%   |
| 2240x1400          | 2         | 0.12%   |
| 1600x1200          | 2         | 0.12%   |
| 1280x768           | 2         | 0.12%   |
| 6000x1440          | 1         | 0.06%   |
| 3840x1080          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3280x1080          | 1         | 0.06%   |
| 1920x540           | 1         | 0.06%   |
| 1600x2560          | 1         | 0.06%   |
| 1400x1050          | 1         | 0.06%   |
| 1366x912           | 1         | 0.06%   |
| 1152x864           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 649       | 37.43%  |
| 13      | 342       | 19.72%  |
| 14      | 268       | 15.46%  |
| 11      | 59        | 3.4%    |
| 17      | 51        | 2.94%   |
| 21      | 45        | 2.6%    |
| 24      | 31        | 1.79%   |
| 12      | 31        | 1.79%   |
| 23      | 30        | 1.73%   |
| 16      | 26        | 1.5%    |
| 10      | 24        | 1.38%   |
| 27      | 23        | 1.33%   |
| 18      | 20        | 1.15%   |
| 34      | 17        | 0.98%   |
| Unknown | 16        | 0.92%   |
| 20      | 15        | 0.87%   |
| 31      | 12        | 0.69%   |
| 19      | 11        | 0.63%   |
| 84      | 9         | 0.52%   |
| 40      | 6         | 0.35%   |
| 22      | 6         | 0.35%   |
| 7       | 6         | 0.35%   |
| 72      | 4         | 0.23%   |
| 54      | 4         | 0.23%   |
| 32      | 4         | 0.23%   |
| 8       | 3         | 0.17%   |
| 142     | 2         | 0.12%   |
| 52      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 29      | 2         | 0.12%   |
| 25      | 2         | 0.12%   |
| 86      | 1         | 0.06%   |
| 74      | 1         | 0.06%   |
| 63      | 1         | 0.06%   |
| 57      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1130      | 65.58%  |
| 201-300        | 232       | 13.46%  |
| 401-500        | 95        | 5.51%   |
| 501-600        | 83        | 4.82%   |
| 351-400        | 81        | 4.7%    |
| 701-800        | 22        | 1.28%   |
| Unknown        | 16        | 0.93%   |
| 601-700        | 15        | 0.87%   |
| 1501-2000      | 14        | 0.81%   |
| 1001-1500      | 11        | 0.64%   |
| 801-900        | 10        | 0.58%   |
| 1-100          | 7         | 0.41%   |
| 101-200        | 3         | 0.17%   |
| More than 2000 | 2         | 0.12%   |
| 901-1000       | 2         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1285      | 82.9%   |
| 16/10   | 178       | 11.48%  |
| 3/2     | 28        | 1.81%   |
| 21/9    | 18        | 1.16%   |
| 4/3     | 11        | 0.71%   |
| Unknown | 11        | 0.71%   |
| 5/4     | 7         | 0.45%   |
| 0.67    | 6         | 0.39%   |
| 1.00    | 2         | 0.13%   |
| 0.56    | 2         | 0.13%   |
| 6/5     | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 664       | 38.36%  |
| 81-90          | 546       | 31.54%  |
| 201-250        | 94        | 5.43%   |
| 71-80          | 65        | 3.76%   |
| 51-60          | 59        | 3.41%   |
| 351-500        | 35        | 2.02%   |
| 121-130        | 34        | 1.96%   |
| 151-200        | 33        | 1.91%   |
| 61-70          | 29        | 1.68%   |
| More than 1000 | 26        | 1.5%    |
| 141-150        | 25        | 1.44%   |
| 41-50          | 24        | 1.39%   |
| 301-350        | 23        | 1.33%   |
| Unknown        | 16        | 0.92%   |
| 131-140        | 12        | 0.69%   |
| 501-1000       | 12        | 0.69%   |
| 1-40           | 10        | 0.58%   |
| 251-300        | 10        | 0.58%   |
| 111-120        | 10        | 0.58%   |
| 91-100         | 4         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 818       | 48.03%  |
| 121-160       | 493       | 28.95%  |
| 51-100        | 246       | 14.45%  |
| 161-240       | 73        | 4.29%   |
| 1-50          | 32        | 1.88%   |
| More than 240 | 25        | 1.47%   |
| Unknown       | 16        | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1271      | 80.8%   |
| 2     | 248       | 15.77%  |
| 0     | 32        | 2.03%   |
| 3     | 22        | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 875       | 37.22%  |
| Intel                                  | 602       | 25.61%  |
| Qualcomm Atheros                       | 364       | 15.48%  |
| Broadcom                               | 219       | 9.32%   |
| Broadcom Limited                       | 48        | 2.04%   |
| Ralink                                 | 39        | 1.66%   |
| Marvell Technology Group               | 37        | 1.57%   |
| MediaTek                               | 21        | 0.89%   |
| TP-Link                                | 19        | 0.81%   |
| Ralink Technology                      | 19        | 0.81%   |
| Nvidia                                 | 16        | 0.68%   |
| ASIX Electronics                       | 15        | 0.64%   |
| Huawei Technologies                    | 10        | 0.43%   |
| DisplayLink                            | 7         | 0.3%    |
| Qualcomm Atheros Communications        | 6         | 0.26%   |
| Xiaomi                                 | 5         | 0.21%   |
| Spreadtrum Communications              | 4         | 0.17%   |
| Motorola PCS                           | 4         | 0.17%   |
| ICS Advent                             | 4         | 0.17%   |
| Samsung Electronics                    | 3         | 0.13%   |
| Qualcomm                               | 3         | 0.13%   |
| Lenovo                                 | 3         | 0.13%   |
| OPPO Electronics                       | 2         | 0.09%   |
| JMicron Technology                     | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Dell                                   | 2         | 0.09%   |
| D-Link                                 | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Shenzhen Goodix Technology             | 1         | 0.04%   |
| Qualcomm Technologies                  | 1         | 0.04%   |
| OpenMoko                               | 1         | 0.04%   |
| NIIMBOT                                | 1         | 0.04%   |
| NetGear                                | 1         | 0.04%   |
| Mercucys                               | 1         | 0.04%   |
| Linksys                                | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| Lab126                                 | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 426       | 14.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 274       | 9.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 86        | 2.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 67        | 2.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 58        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 55        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 54        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 48        | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 48        | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 46        | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 45        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 41        | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 39        | 1.34%   |
| Intel Wireless 7265                                               | 38        | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 34        | 1.16%   |
| Intel Wi-Fi 6 AX201                                               | 32        | 1.1%    |
| Intel Wireless 7260                                               | 31        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 30        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 30        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 29        | 0.99%   |
| Intel Wireless 8260                                               | 26        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 23        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 22        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 20        | 0.69%   |
| Intel Wireless 3160                                               | 20        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.65%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 19        | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.62%   |
| Intel Wireless 3165                                               | 18        | 0.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 18        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 17        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 16        | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 16        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 563       | 35.68%  |
| Realtek Semiconductor                 | 373       | 23.64%  |
| Qualcomm Atheros                      | 309       | 19.58%  |
| Broadcom                              | 187       | 11.85%  |
| Ralink                                | 39        | 2.47%   |
| Broadcom Limited                      | 37        | 2.34%   |
| Ralink Technology                     | 19        | 1.2%    |
| TP-Link                               | 17        | 1.08%   |
| MediaTek                              | 17        | 1.08%   |
| Qualcomm Atheros Communications       | 6         | 0.38%   |
| Qualcomm                              | 3         | 0.19%   |
| D-Link                                | 2         | 0.13%   |
| Qualcomm Technologies                 | 1         | 0.06%   |
| NetGear                               | 1         | 0.06%   |
| Mercucys                              | 1         | 0.06%   |
| Dell                                  | 1         | 0.06%   |
| D-Link System                         | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 86        | 5.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 67        | 4.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 58        | 3.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 55        | 3.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 54        | 3.37%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 48        | 2.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 48        | 2.99%   |
| Intel Wi-Fi 6 AX200                                                     | 46        | 2.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 45        | 2.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 41        | 2.56%   |
| Intel Wireless 8265 / 8275                                              | 39        | 2.43%   |
| Intel Wireless 7265                                                     | 38        | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 37        | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 2.12%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 2%      |
| Intel Wireless 7260                                                     | 31        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 30        | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 30        | 1.87%   |
| Intel Wireless 8260                                                     | 26        | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 23        | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 22        | 1.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 22        | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 20        | 1.25%   |
| Intel Wireless 3160                                                     | 20        | 1.25%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 19        | 1.19%   |
| Intel Wireless 3165                                                     | 18        | 1.12%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 18        | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 17        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 16        | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 16        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 16        | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 0.81%   |
| Realtek 802.11ac NIC                                                    | 12        | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 12        | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 12        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 742       | 57.34%  |
| Intel                                  | 230       | 17.77%  |
| Qualcomm Atheros                       | 115       | 8.89%   |
| Broadcom                               | 71        | 5.49%   |
| Marvell Technology Group               | 37        | 2.86%   |
| Nvidia                                 | 16        | 1.24%   |
| ASIX Electronics                       | 15        | 1.16%   |
| Broadcom Limited                       | 11        | 0.85%   |
| Huawei Technologies                    | 9         | 0.7%    |
| DisplayLink                            | 7         | 0.54%   |
| Xiaomi                                 | 5         | 0.39%   |
| Spreadtrum Communications              | 4         | 0.31%   |
| MediaTek                               | 4         | 0.31%   |
| ICS Advent                             | 4         | 0.31%   |
| Samsung Electronics                    | 3         | 0.23%   |
| Lenovo                                 | 3         | 0.23%   |
| TP-Link                                | 2         | 0.15%   |
| OPPO Electronics                       | 2         | 0.15%   |
| JMicron Technology                     | 2         | 0.15%   |
| Google                                 | 2         | 0.15%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| Linksys                                | 1         | 0.08%   |
| LG Electronics                         | 1         | 0.08%   |
| Lab126                                 | 1         | 0.08%   |
| HTC (High Tech Computer)               | 1         | 0.08%   |
| Foxconn / Hon Hai                      | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 426       | 32.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 274       | 21.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 51        | 3.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 2.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 22        | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 19        | 1.46%   |
| Intel Ethernet Connection I218-LM                                              | 19        | 1.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 18        | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                          | 15        | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                                          | 15        | 1.15%   |
| Intel 82567LM Gigabit Network Connection                                       | 13        | 1%      |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 12        | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12        | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 0.84%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 11        | 0.84%   |
| Intel Ethernet Connection I217-LM                                              | 10        | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 9         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 8         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 8         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 0.61%   |
| Huawei JKM-LX1                                                                 | 8         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.54%   |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                                           | 7         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 6         | 0.46%   |
| Intel Ethernet Connection I219-V                                               | 6         | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 5         | 0.38%   |
| Nvidia MCP79 Ethernet                                                          | 5         | 0.38%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.38%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 5         | 0.38%   |
| Intel Ethernet Connection (6) I219-LM                                          | 5         | 0.38%   |
| Intel Ethernet Connection (16) I219-LM                                         | 5         | 0.38%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1510      | 54.51%  |
| Ethernet | 1246      | 44.98%  |
| Modem    | 9         | 0.32%   |
| Unknown  | 5         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1233      | 75.37%  |
| Ethernet | 402       | 24.57%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1153      | 75.07%  |
| 1     | 348       | 22.66%  |
| 0     | 29        | 1.89%   |
| 3     | 6         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1066      | 67.77%  |
| Yes  | 507       | 32.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 406       | 35.03%  |
| Realtek Semiconductor           | 219       | 18.9%   |
| Qualcomm Atheros Communications | 116       | 10.01%  |
| Broadcom                        | 83        | 7.16%   |
| Apple                           | 55        | 4.75%   |
| Lite-On Technology              | 51        | 4.4%    |
| IMC Networks                    | 47        | 4.06%   |
| Foxconn / Hon Hai               | 42        | 3.62%   |
| Realtek                         | 27        | 2.33%   |
| Dell                            | 27        | 2.33%   |
| Hewlett-Packard                 | 23        | 1.98%   |
| Toshiba                         | 19        | 1.64%   |
| Ralink                          | 16        | 1.38%   |
| Cambridge Silicon Radio         | 9         | 0.78%   |
| Ralink Technology               | 7         | 0.6%    |
| Foxconn International           | 4         | 0.35%   |
| Alps Electric                   | 4         | 0.35%   |
| USI                             | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |
| ASUSTek Computer                | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 166       | 14.3%   |
| Realtek Bluetooth Radio                                                             | 95        | 8.18%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 93        | 8.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 85        | 7.32%   |
| Intel AX201 Bluetooth                                                               | 64        | 5.51%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 57        | 4.91%   |
| Intel AX200 Bluetooth                                                               | 45        | 3.88%   |
| Realtek Bluetooth Radio                                                             | 27        | 2.33%   |
| Apple Bluetooth Host Controller                                                     | 27        | 2.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 22        | 1.89%   |
| IMC Networks Bluetooth Radio                                                        | 20        | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 1.64%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 1.55%   |
| Apple Bluetooth USB Host Controller                                                 | 18        | 1.55%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 16        | 1.38%   |
| Lite-On Bluetooth Device                                                            | 16        | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 16        | 1.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 15        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 1.29%   |
| Realtek RTL8723B Bluetooth                                                          | 13        | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 13        | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 12        | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 11        | 0.95%   |
| Realtek RTL8821A Bluetooth                                                          | 10        | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.86%   |
| IMC Networks Wireless_Device                                                        | 9         | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 0.78%   |
| IMC Networks Bluetooth Device                                                       | 8         | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.69%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 7         | 0.6%    |
| Intel Bluetooth Device                                                              | 6         | 0.52%   |
| Dell Wireless 355 Bluetooth                                                         | 6         | 0.52%   |
| Apple Bluetooth HCI                                                                 | 6         | 0.52%   |
| Toshiba Bluetooth Device                                                            | 5         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1128      | 63.26%  |
| AMD                                             | 391       | 21.93%  |
| Nvidia                                          | 175       | 9.81%   |
| Logitech                                        | 9         | 0.5%    |
| Texas Instruments                               | 7         | 0.39%   |
| C-Media Electronics                             | 7         | 0.39%   |
| Realtek Semiconductor                           | 6         | 0.34%   |
| Generalplus Technology                          | 6         | 0.34%   |
| Plantronics                                     | 5         | 0.28%   |
| Lenovo                                          | 5         | 0.28%   |
| Kingston Technology                             | 5         | 0.28%   |
| GN Netcom                                       | 5         | 0.28%   |
| Tenx Technology                                 | 4         | 0.22%   |
| JMTek                                           | 3         | 0.17%   |
| Creative Technology                             | 3         | 0.17%   |
| ASUSTek Computer                                | 3         | 0.17%   |
| Syntek                                          | 2         | 0.11%   |
| Synaptics                                       | 2         | 0.11%   |
| Samson Technologies                             | 2         | 0.11%   |
| Apple                                           | 2         | 0.11%   |
| Yamaha                                          | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.06%   |
| Sony                                            | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.06%   |
| Sennheiser Communications                       | 1         | 0.06%   |
| Samsung Electronics                             | 1         | 0.06%   |
| Razer USA                                       | 1         | 0.06%   |
| M-Audio                                         | 1         | 0.06%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.06%   |
| Focusrite-Novation                              | 1         | 0.06%   |
| DisplayLink                                     | 1         | 0.06%   |
| DCMT Technology                                 | 1         | 0.06%   |
| Cambridge Audio                                 | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 146       | 6.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 132       | 5.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 126       | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 95        | 4.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 86        | 3.83%   |
| AMD FCH Azalia Controller                                                                         | 77        | 3.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 68        | 3.03%   |
| Intel 8 Series HD Audio Controller                                                                | 68        | 3.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 68        | 3.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 65        | 2.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 58        | 2.58%   |
| Intel Broadwell-U Audio Controller                                                                | 58        | 2.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 57        | 2.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 53        | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 52        | 2.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 52        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 47        | 2.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 45        | 2%      |
| AMD High Definition Audio Controller                                                              | 45        | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 42        | 1.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 42        | 1.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 41        | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 40        | 1.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 37        | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 37        | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 32        | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 1.38%   |
| Intel Comet Lake PCH cAVS                                                                         | 27        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 27        | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26        | 1.16%   |
| AMD Trinity HDMI Audio Controller                                                                 | 24        | 1.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 23        | 1.02%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 21        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 18        | 0.8%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 15        | 0.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 264       | 28.14%  |
| SK hynix                                         | 204       | 21.75%  |
| Micron Technology                                | 127       | 13.54%  |
| Kingston                                         | 119       | 12.69%  |
| Unknown                                          | 65        | 6.93%   |
| A-DATA Technology                                | 37        | 3.94%   |
| Ramaxel Technology                               | 28        | 2.99%   |
| Elpida                                           | 19        | 2.03%   |
| Crucial                                          | 18        | 1.92%   |
| Nanya Technology                                 | 12        | 1.28%   |
| Unknown (ABCD)                                   | 11        | 1.17%   |
| Corsair                                          | 6         | 0.64%   |
| Team                                             | 3         | 0.32%   |
| Qimonda                                          | 3         | 0.32%   |
| PNY                                              | 3         | 0.32%   |
| ChangXin Memory                                  | 3         | 0.32%   |
| Unknown                                          | 3         | 0.32%   |
| Transcend                                        | 2         | 0.21%   |
| Patriot                                          | 2         | 0.21%   |
| Unknown (0x8AF1)                                 | 1         | 0.11%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.11%   |
| Timetec                                          | 1         | 0.11%   |
| SHARETRONIC                                      | 1         | 0.11%   |
| Goldkey                                          | 1         | 0.11%   |
| G.Skill                                          | 1         | 0.11%   |
| Avant                                            | 1         | 0.11%   |
| 3235CB0010E4                                     | 1         | 0.11%   |
| 0161000080AD                                     | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 2.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 17        | 1.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 1.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 1.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.19%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 11        | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.09%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 1.09%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.79%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 8         | 0.79%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 8         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.69%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 6         | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 6         | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.5%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 5         | 0.5%    |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 5         | 0.5%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 5         | 0.5%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 5         | 0.5%    |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 5         | 0.5%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 316       | 41.63%  |
| DDR3    | 307       | 40.45%  |
| DDR2    | 48        | 6.32%   |
| LPDDR4  | 30        | 3.95%   |
| LPDDR3  | 21        | 2.77%   |
| SDRAM   | 16        | 2.11%   |
| DDR     | 7         | 0.92%   |
| Unknown | 5         | 0.66%   |
| LPDDR5  | 4         | 0.53%   |
| DDR5    | 4         | 0.53%   |
| RAM     | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 671       | 88.06%  |
| Row Of Chips | 85        | 11.15%  |
| Chip         | 5         | 0.66%   |
| Unknown      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 335       | 37.77%  |
| 4096  | 307       | 34.61%  |
| 2048  | 130       | 14.66%  |
| 16384 | 64        | 7.22%   |
| 1024  | 36        | 4.06%   |
| 32768 | 11        | 1.24%   |
| 512   | 3         | 0.34%   |
| 256   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 233       | 27.71%  |
| 2667    | 157       | 18.67%  |
| 3200    | 106       | 12.6%   |
| 2400    | 52        | 6.18%   |
| 2133    | 44        | 5.23%   |
| 1334    | 42        | 4.99%   |
| 1333    | 37        | 4.4%    |
| 667     | 28        | 3.33%   |
| 3266    | 25        | 2.97%   |
| Unknown | 21        | 2.5%    |
| 4267    | 13        | 1.55%   |
| 800     | 12        | 1.43%   |
| 2048    | 10        | 1.19%   |
| 1067    | 9         | 1.07%   |
| 1867    | 8         | 0.95%   |
| 533     | 7         | 0.83%   |
| 4199    | 6         | 0.71%   |
| 975     | 6         | 0.71%   |
| 1066    | 5         | 0.59%   |
| 8400    | 4         | 0.48%   |
| 6400    | 4         | 0.48%   |
| 4800    | 3         | 0.36%   |
| 3733    | 3         | 0.36%   |
| 2933    | 2         | 0.24%   |
| 1866    | 2         | 0.24%   |
| 5600    | 1         | 0.12%   |
| 400     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 3         | 20%     |
| Brother Industries     | 3         | 20%     |
| Samsung Electronics    | 2         | 13.33%  |
| Hewlett-Packard        | 2         | 13.33%  |
| Canon                  | 2         | 13.33%  |
| TSC Auto ID Technology | 1         | 6.67%   |
| Kyocera                | 1         | 6.67%   |
| BIXOLON                | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP DeskJet 2300 series  | 2         | 13.33%  |
| TSC Auto ID Printer     | 1         | 6.67%   |
| Seiko Epson L555 Series | 1         | 6.67%   |
| Seiko Epson L210 Series | 1         | 6.67%   |
| Seiko Epson L120 Series | 1         | 6.67%   |
| Samsung ML-1660 Series  | 1         | 6.67%   |
| Samsung M2020 Series    | 1         | 6.67%   |
| Kyocera FS-1116MFP      | 1         | 6.67%   |
| Canon iP2600 series     | 1         | 6.67%   |
| Canon G2010 series      | 1         | 6.67%   |
| Brother MFC-J470DW      | 1         | 6.67%   |
| Brother DCP-1600        | 1         | 6.67%   |
| Brother DCP-1510        | 1         | 6.67%   |
| BIXOLON SRP-350plusIII  | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 318       | 22.84%  |
| IMC Networks                           | 144       | 10.34%  |
| Microdia                               | 136       | 9.77%   |
| Realtek Semiconductor                  | 98        | 7.04%   |
| Cheng Uei Precision Industry (Foxlink) | 81        | 5.82%   |
| Sunplus Innovation Technology          | 75        | 5.39%   |
| Suyin                                  | 68        | 4.89%   |
| Bison Electronics                      | 68        | 4.89%   |
| Quanta                                 | 66        | 4.74%   |
| Syntek                                 | 47        | 3.38%   |
| Apple                                  | 40        | 2.87%   |
| Lite-On Technology                     | 37        | 2.66%   |
| Acer                                   | 24        | 1.72%   |
| Ricoh                                  | 21        | 1.51%   |
| Silicon Motion                         | 19        | 1.36%   |
| Importek                               | 16        | 1.15%   |
| Alcor Micro                            | 15        | 1.08%   |
| Logitech                               | 14        | 1.01%   |
| Luxvisions Innotech Limited            | 11        | 0.79%   |
| ALi                                    | 8         | 0.57%   |
| Y Media                                | 7         | 0.5%    |
| Sonix Technology                       | 7         | 0.5%    |
| Primax Electronics                     | 6         | 0.43%   |
| OmniVision Technologies                | 6         | 0.43%   |
| HRY                                    | 5         | 0.36%   |
| Generalplus Technology                 | 5         | 0.36%   |
| Lenovo                                 | 4         | 0.29%   |
| Genesys Logic                          | 4         | 0.29%   |
| Samsung Electronics                    | 3         | 0.22%   |
| Microsoft                              | 3         | 0.22%   |
| MacroSilicon                           | 3         | 0.22%   |
| icSpring                               | 3         | 0.22%   |
| Z-Star Microelectronics                | 2         | 0.14%   |
| Tobii Technology AB                    | 2         | 0.14%   |
| Sunplus Technology                     | 2         | 0.14%   |
| Jieli Technology                       | 2         | 0.14%   |
| DigiTech                               | 2         | 0.14%   |
| Colorado                               | 2         | 0.14%   |
| Tripath Technology                     | 1         | 0.07%   |
| SunplusIT                              | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 47        | 3.36%   |
| Microdia Integrated_Webcam_HD                                              | 43        | 3.08%   |
| IMC Networks Integrated Camera                                             | 34        | 2.43%   |
| Chicony HD WebCam                                                          | 32        | 2.29%   |
| Realtek Integrated_Webcam_HD                                               | 28        | 2%      |
| IMC Networks HD Camera                                                     | 25        | 1.79%   |
| Sunplus Integrated_Webcam_HD                                               | 24        | 1.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 21        | 1.5%    |
| Chicony HP Webcam                                                          | 21        | 1.5%    |
| Bison Integrated Camera                                                    | 21        | 1.5%    |
| Apple FaceTime HD Camera                                                   | 20        | 1.43%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 18        | 1.29%   |
| Chicony HP Truevision HD camera                                            | 18        | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 17        | 1.22%   |
| Quanta HP Webcam                                                           | 16        | 1.14%   |
| Microdia Integrated Webcam                                                 | 16        | 1.14%   |
| Chicony HP Truevision HD                                                   | 16        | 1.14%   |
| Syntek Lenovo EasyCamera                                                   | 15        | 1.07%   |
| Sunplus HD WebCam                                                          | 15        | 1.07%   |
| Syntek Integrated Camera                                                   | 14        | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 14        | 1%      |
| Acer Integrated Camera                                                     | 13        | 0.93%   |
| Lite-On HP Wide Vision HD Camera                                           | 12        | 0.86%   |
| IMC Networks EasyCamera                                                    | 12        | 0.86%   |
| Chicony HP Wide Vision HD Camera                                           | 12        | 0.86%   |
| Microdia Lenovo EasyCamera                                                 | 11        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 11        | 0.79%   |
| Suyin HP Truevision HD                                                     | 10        | 0.72%   |
| Chicony USB 2.0 Camera                                                     | 10        | 0.72%   |
| Chicony HP HD Camera                                                       | 10        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 10        | 0.72%   |
| Bison Lenovo EasyCamera                                                    | 10        | 0.72%   |
| Realtek HP Truevision HD                                                   | 9         | 0.64%   |
| Quanta HP TrueVision HD Camera                                             | 9         | 0.64%   |
| Microdia Sonix USB 2.0 Camera                                              | 9         | 0.64%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 9         | 0.64%   |
| IMC Networks ov9734_azurewave_camera                                       | 9         | 0.64%   |
| Chicony Lenovo EasyCamera                                                  | 9         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 9         | 0.64%   |
| Bison EasyCamera                                                           | 9         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 87        | 34.25%  |
| Shenzhen Goodix Technology         | 61        | 24.02%  |
| Synaptics                          | 38        | 14.96%  |
| AuthenTec                          | 24        | 9.45%   |
| Upek                               | 18        | 7.09%   |
| Focal-systems.Corp                 | 7         | 2.76%   |
| Elan Microelectronics              | 7         | 2.76%   |
| STMicroelectronics                 | 5         | 1.97%   |
| LighTuning Technology              | 3         | 1.18%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.79%   |
| Suprema                            | 1         | 0.39%   |
| Samsung Electronics                | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 56        | 22.05%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 7.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 6.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 6.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 5.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 5.12%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 4.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 3.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.94%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 2.76%   |
| Validity Sensors VFS491                                                    | 6         | 2.36%   |
| AuthenTec AES2810                                                          | 6         | 2.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.97%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.97%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.97%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.57%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.18%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.18%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.18%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.18%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.18%   |
| AuthenTec AES1600                                                          | 3         | 1.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.79%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.79%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.79%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.79%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.39%   |
| Synaptics WBDI                                                             | 1         | 0.39%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.39%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.39%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.39%   |
| Samsung Fingerprint Device                                                 | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 47        | 63.51%  |
| Alcor Micro           | 12        | 16.22%  |
| Upek                  | 7         | 9.46%   |
| Lenovo                | 6         | 8.11%   |
| O2 Micro              | 1         | 1.35%   |
| Gemalto (was Gemplus) | 1         | 1.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 25.68%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 17.57%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 16.22%  |
| Broadcom 5880                                                                | 8         | 10.81%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 9.46%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 8.11%   |
| Broadcom 58200                                                               | 6         | 8.11%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.35%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 985       | 62.86%  |
| 1     | 473       | 30.19%  |
| 2     | 98        | 6.25%   |
| 3     | 7         | 0.45%   |
| 5     | 2         | 0.13%   |
| 7     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 251       | 36.06%  |
| Graphics card            | 121       | 17.39%  |
| Net/wireless             | 93        | 13.36%  |
| Chipcard                 | 71        | 10.2%   |
| Multimedia controller    | 50        | 7.18%   |
| Camera                   | 26        | 3.74%   |
| Bluetooth                | 26        | 3.74%   |
| Communication controller | 13        | 1.87%   |
| Storage                  | 10        | 1.44%   |
| Net/ethernet             | 10        | 1.44%   |
| Sound                    | 7         | 1.01%   |
| Card reader              | 7         | 1.01%   |
| Modem                    | 5         | 0.72%   |
| Network                  | 3         | 0.43%   |
| Storage/ide              | 1         | 0.14%   |
| Firewire controller      | 1         | 0.14%   |
| Dvb card                 | 1         | 0.14%   |

