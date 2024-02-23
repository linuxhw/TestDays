Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 5210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | E7214                       | [cb37ec8f5d](https://linux-hardware.org/?probe=cb37ec8f5d) | Feb 02, 2024 |
| HP            | ENVY m7                     | [b38e23bdbe](https://linux-hardware.org/?probe=b38e23bdbe) | Feb 02, 2024 |
| Dell          | Latitude 7420               | [5eb0b85732](https://linux-hardware.org/?probe=5eb0b85732) | Feb 02, 2024 |
| Acer          | Aspire 5738                 | [7137d60986](https://linux-hardware.org/?probe=7137d60986) | Feb 02, 2024 |
| Acer          | TravelMate 7740G            | [78bfa1b270](https://linux-hardware.org/?probe=78bfa1b270) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [98dc9736d7](https://linux-hardware.org/?probe=98dc9736d7) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [4661ceab45](https://linux-hardware.org/?probe=4661ceab45) | Feb 01, 2024 |
| HP            | 620                         | [adcf9577e4](https://linux-hardware.org/?probe=adcf9577e4) | Feb 01, 2024 |
| Dell          | Latitude E6420              | [ff73a45b61](https://linux-hardware.org/?probe=ff73a45b61) | Feb 01, 2024 |
| COM1          | E15-5A165-BM (9)            | [41d123782c](https://linux-hardware.org/?probe=41d123782c) | Feb 01, 2024 |
| HP            | EliteBook 1050 G1           | [8799a2e9ae](https://linux-hardware.org/?probe=8799a2e9ae) | Feb 01, 2024 |
| HP            | EliteBook 1050 G1           | [c95847728d](https://linux-hardware.org/?probe=c95847728d) | Feb 01, 2024 |
| HP            | 15 Notebook PC              | [b60abe5c3d](https://linux-hardware.org/?probe=b60abe5c3d) | Feb 01, 2024 |
| HP            | 15 Notebook PC              | [b2f9ce6a03](https://linux-hardware.org/?probe=b2f9ce6a03) | Feb 01, 2024 |
| Apple         | MacBookPro10,2              | [fca71d08b7](https://linux-hardware.org/?probe=fca71d08b7) | Feb 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [172f182e36](https://linux-hardware.org/?probe=172f182e36) | Feb 01, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [45207cf034](https://linux-hardware.org/?probe=45207cf034) | Jan 31, 2024 |
| HP            | Elite x2 1012 G1            | [44bbb3b748](https://linux-hardware.org/?probe=44bbb3b748) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | [061ca8b8ca](https://linux-hardware.org/?probe=061ca8b8ca) | Jan 31, 2024 |
| Lenovo        | IdeaPad Y560                | [e9a51b1fa8](https://linux-hardware.org/?probe=e9a51b1fa8) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | [0eefe2c89f](https://linux-hardware.org/?probe=0eefe2c89f) | Jan 31, 2024 |
| HP            | EliteBook 8460p             | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| ASUSTek       | GL552JX                     | [4aebfef2d8](https://linux-hardware.org/?probe=4aebfef2d8) | Jan 31, 2024 |
| HP            | ProBook 6570b               | [20537302e6](https://linux-hardware.org/?probe=20537302e6) | Jan 31, 2024 |
| ASUSTek       | N55SF                       | [03c3d9aa25](https://linux-hardware.org/?probe=03c3d9aa25) | Jan 31, 2024 |
| Dell          | Studio 1450                 | [cdeeb53e43](https://linux-hardware.org/?probe=cdeeb53e43) | Jan 31, 2024 |
| HP            | ZBook 17 G3                 | [fefc37bfa1](https://linux-hardware.org/?probe=fefc37bfa1) | Jan 30, 2024 |
| HP            | ZBook 17 G3                 | [525b120614](https://linux-hardware.org/?probe=525b120614) | Jan 30, 2024 |
| ASUSTek       | GL552JX                     | [4acec8f3e2](https://linux-hardware.org/?probe=4acec8f3e2) | Jan 30, 2024 |
| Lenovo        | IdeaPad Y560                | [a32d1d3fa7](https://linux-hardware.org/?probe=a32d1d3fa7) | Jan 30, 2024 |
| Acer          | Aspire 9420                 | [d0c7154097](https://linux-hardware.org/?probe=d0c7154097) | Jan 30, 2024 |
| HP            | Laptop 17-ak0xx             | [0b511ae973](https://linux-hardware.org/?probe=0b511ae973) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [028ce3b254](https://linux-hardware.org/?probe=028ce3b254) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| HUAWEI        | HKD-WXX                     | [7c98d9521b](https://linux-hardware.org/?probe=7c98d9521b) | Jan 29, 2024 |
| Apple         | MacBookPro10,1              | [4a9032156a](https://linux-hardware.org/?probe=4a9032156a) | Jan 29, 2024 |
| Medion        | P651x series                | [078e2924c4](https://linux-hardware.org/?probe=078e2924c4) | Jan 28, 2024 |
| Acer          | Aspire M3-581G              | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [67781b5f97](https://linux-hardware.org/?probe=67781b5f97) | Jan 28, 2024 |
| HP            | Laptop 15-bw0xx             | [118dcfd484](https://linux-hardware.org/?probe=118dcfd484) | Jan 28, 2024 |
| Dell          | Inspiron 5570               | [f8c5ba731b](https://linux-hardware.org/?probe=f8c5ba731b) | Jan 27, 2024 |
| Apple         | MacBookPro14,1              | [75f6092ef1](https://linux-hardware.org/?probe=75f6092ef1) | Jan 27, 2024 |
| Dell          | Latitude E6430              | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430s 2356GRS      | [c12736937f](https://linux-hardware.org/?probe=c12736937f) | Jan 26, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ad13a93817](https://linux-hardware.org/?probe=ad13a93817) | Jan 26, 2024 |
| HP            | Victus by Gaming Laptop ... | [510b7f5cc7](https://linux-hardware.org/?probe=510b7f5cc7) | Jan 26, 2024 |
| Acer          | Swift SF314-43              | [cdae9f5af3](https://linux-hardware.org/?probe=cdae9f5af3) | Jan 25, 2024 |
| Sony          | VPCEB3B4E                   | [afa1b50b5a](https://linux-hardware.org/?probe=afa1b50b5a) | Jan 25, 2024 |
| Fujitsu       | LIFEBOOK A531               | [647bf81332](https://linux-hardware.org/?probe=647bf81332) | Jan 25, 2024 |
| Toshiba       | Satellite R630              | [c888a8f4d5](https://linux-hardware.org/?probe=c888a8f4d5) | Jan 24, 2024 |
| Lenovo        | ThinkPad T480 20L6S3L400    | [3861071640](https://linux-hardware.org/?probe=3861071640) | Jan 24, 2024 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [0f69d36c02](https://linux-hardware.org/?probe=0f69d36c02) | Jan 24, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P3540FA_... | [a20369a079](https://linux-hardware.org/?probe=a20369a079) | Jan 24, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P3540FA_... | [9ac42c58bf](https://linux-hardware.org/?probe=9ac42c58bf) | Jan 24, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [aa8bc496ed](https://linux-hardware.org/?probe=aa8bc496ed) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | [214ebad454](https://linux-hardware.org/?probe=214ebad454) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | [f2a415adc9](https://linux-hardware.org/?probe=f2a415adc9) | Jan 24, 2024 |
| HP            | ZBook Studio G5             | [114d79aa75](https://linux-hardware.org/?probe=114d79aa75) | Jan 23, 2024 |
| Dell          | Latitude E5420              | [8347319849](https://linux-hardware.org/?probe=8347319849) | Jan 23, 2024 |
| HP            | Pavilion g4                 | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| HP            | EliteBook 840 G2            | [9ad67b6f8d](https://linux-hardware.org/?probe=9ad67b6f8d) | Jan 23, 2024 |
| HP            | EliteBook 840 G2            | [04f0c2393d](https://linux-hardware.org/?probe=04f0c2393d) | Jan 23, 2024 |
| Lenovo        | ThinkPad X201 4492W36       | [1ab7e95399](https://linux-hardware.org/?probe=1ab7e95399) | Jan 23, 2024 |
| Dell          | Inspiron 5567               | [6869d9559d](https://linux-hardware.org/?probe=6869d9559d) | Jan 22, 2024 |
| Google        | Kefka                       | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| HP            | Notebook                    | [8359e2a5dd](https://linux-hardware.org/?probe=8359e2a5dd) | Jan 22, 2024 |
| Acer          | Aspire 7736                 | [47521c1811](https://linux-hardware.org/?probe=47521c1811) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [8dacf655a4](https://linux-hardware.org/?probe=8dacf655a4) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [c3f3bb78c6](https://linux-hardware.org/?probe=c3f3bb78c6) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | [046036e7e3](https://linux-hardware.org/?probe=046036e7e3) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | [262a8552de](https://linux-hardware.org/?probe=262a8552de) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Acer          | Predator PH315-53           | [a6dd1aa2a0](https://linux-hardware.org/?probe=a6dd1aa2a0) | Jan 22, 2024 |
| Dell          | Latitude 5490               | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| Dell          | Latitude E7450              | [95b7e8d2fa](https://linux-hardware.org/?probe=95b7e8d2fa) | Jan 21, 2024 |
| Toshiba       | Satellite A350              | [bc48f2f41a](https://linux-hardware.org/?probe=bc48f2f41a) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [07f3899f3a](https://linux-hardware.org/?probe=07f3899f3a) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [7bb9b69a14](https://linux-hardware.org/?probe=7bb9b69a14) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [124da06515](https://linux-hardware.org/?probe=124da06515) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [01d1c30937](https://linux-hardware.org/?probe=01d1c30937) | Jan 21, 2024 |
| Toshiba       | Satellite L640              | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| HP            | Notebook                    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [aa2c5d9a1a](https://linux-hardware.org/?probe=aa2c5d9a1a) | Jan 20, 2024 |
| Sony          | VPCEB2JFX                   | [f648777cf1](https://linux-hardware.org/?probe=f648777cf1) | Jan 20, 2024 |
| Sony          | VPCEB2JFX                   | [bdc5adc95b](https://linux-hardware.org/?probe=bdc5adc95b) | Jan 20, 2024 |
| Toshiba       | NB550D                      | [1f743ab40e](https://linux-hardware.org/?probe=1f743ab40e) | Jan 20, 2024 |
| Sony          | VGN-NS11Z_S                 | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4257aab3ea](https://linux-hardware.org/?probe=4257aab3ea) | Jan 20, 2024 |
| Dell          | Inspiron 3531               | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| Lenovo        | Y50-70 20378                | [d146d31a02](https://linux-hardware.org/?probe=d146d31a02) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [f88694f40b](https://linux-hardware.org/?probe=f88694f40b) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [1ce9d8eb2f](https://linux-hardware.org/?probe=1ce9d8eb2f) | Jan 20, 2024 |
| HP            | EliteBook 840 G1            | [becbec6f26](https://linux-hardware.org/?probe=becbec6f26) | Jan 20, 2024 |
| Sony          | VGN-NW11S_S                 | [082d37eaf4](https://linux-hardware.org/?probe=082d37eaf4) | Jan 19, 2024 |
| Acer          | Aspire E5-551G              | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| Lenovo        | V330-15IKB 81AX             | [b1151b6885](https://linux-hardware.org/?probe=b1151b6885) | Jan 19, 2024 |
| Acer          | Aspire E5-523               | [02378722b6](https://linux-hardware.org/?probe=02378722b6) | Jan 19, 2024 |
| Dell          | Inspiron 15-3567            | [dafbbbb67c](https://linux-hardware.org/?probe=dafbbbb67c) | Jan 19, 2024 |
| Toshiba       | Satellite C55D-B            | [7f1090301b](https://linux-hardware.org/?probe=7f1090301b) | Jan 18, 2024 |
| Lenovo        | IdeaPad Z510 20287          | [ba4eb41acd](https://linux-hardware.org/?probe=ba4eb41acd) | Jan 18, 2024 |
| GPD           | MicroPC                     | [80b3061910](https://linux-hardware.org/?probe=80b3061910) | Jan 18, 2024 |
| HP            | 530 Notebook PC(GU324AA#... | [785d324acb](https://linux-hardware.org/?probe=785d324acb) | Jan 18, 2024 |
| Alienware     | 14                          | [a0109babcd](https://linux-hardware.org/?probe=a0109babcd) | Jan 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ae841d1af4](https://linux-hardware.org/?probe=ae841d1af4) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | [66c11ee330](https://linux-hardware.org/?probe=66c11ee330) | Jan 17, 2024 |
| Toshiba       | Satellite C850-B820         | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | [640deb41af](https://linux-hardware.org/?probe=640deb41af) | Jan 17, 2024 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [7b068dc524](https://linux-hardware.org/?probe=7b068dc524) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [0e05a50329](https://linux-hardware.org/?probe=0e05a50329) | Jan 16, 2024 |
| HP            | Pavilion 17                 | [3594afe0d4](https://linux-hardware.org/?probe=3594afe0d4) | Jan 16, 2024 |
| HP            | Laptop 14-cf1xxx            | [b26a65cafd](https://linux-hardware.org/?probe=b26a65cafd) | Jan 16, 2024 |
| Lenovo        | ThinkPad L412 0585A38       | [d3c2d88045](https://linux-hardware.org/?probe=d3c2d88045) | Jan 16, 2024 |
| HP            | 15                          | [c84c138cef](https://linux-hardware.org/?probe=c84c138cef) | Jan 16, 2024 |
| Toshiba       | Satellite L55-C             | [004a2ecf6b](https://linux-hardware.org/?probe=004a2ecf6b) | Jan 16, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [dddcaf6303](https://linux-hardware.org/?probe=dddcaf6303) | Jan 16, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [26452561bd](https://linux-hardware.org/?probe=26452561bd) | Jan 16, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [6c360c2400](https://linux-hardware.org/?probe=6c360c2400) | Jan 15, 2024 |
| Intel         | Unknown                     | [dfd975eff3](https://linux-hardware.org/?probe=dfd975eff3) | Jan 15, 2024 |
| Dell          | Latitude E5470              | [d9fcb7e121](https://linux-hardware.org/?probe=d9fcb7e121) | Jan 15, 2024 |
| Lenovo        | ThinkPad X240 20AL0097US    | [7c13db701b](https://linux-hardware.org/?probe=7c13db701b) | Jan 15, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [fdbb4ec35e](https://linux-hardware.org/?probe=fdbb4ec35e) | Jan 15, 2024 |
| Samsung       | 700Z3C/700Z5C               | [6055feefa2](https://linux-hardware.org/?probe=6055feefa2) | Jan 14, 2024 |
| Dell          | Latitude 7390               | [837b633afe](https://linux-hardware.org/?probe=837b633afe) | Jan 14, 2024 |
| HP            | 15                          | [c247a8a3fb](https://linux-hardware.org/?probe=c247a8a3fb) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a6d483fa69](https://linux-hardware.org/?probe=a6d483fa69) | Jan 14, 2024 |
| Sony          | VGN-NS11Z_S                 | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| Dell          | Inspiron 3501               | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| Toshiba       | Satellite R630              | [0e83a06873](https://linux-hardware.org/?probe=0e83a06873) | Jan 13, 2024 |
| Apple         | MacBookPro10,2              | [8b5e54c037](https://linux-hardware.org/?probe=8b5e54c037) | Jan 13, 2024 |
| HP            | Laptop 14s-dq0xxx           | [d8a2561e72](https://linux-hardware.org/?probe=d8a2561e72) | Jan 12, 2024 |
| Acer          | Aspire V5-573G              | [09ddfeab43](https://linux-hardware.org/?probe=09ddfeab43) | Jan 12, 2024 |
| Acer          | Nitro AN517-41              | [3f38b8085c](https://linux-hardware.org/?probe=3f38b8085c) | Jan 12, 2024 |
| SGIN          | M15                         | [022c34815c](https://linux-hardware.org/?probe=022c34815c) | Jan 12, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [e085204d13](https://linux-hardware.org/?probe=e085204d13) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [b521a115f8](https://linux-hardware.org/?probe=b521a115f8) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [7d95af598c](https://linux-hardware.org/?probe=7d95af598c) | Jan 12, 2024 |
| Chuwi         | LapBook Pro                 | [9b26a023b9](https://linux-hardware.org/?probe=9b26a023b9) | Jan 12, 2024 |
| Chuwi         | LapBook Pro                 | [efa337f154](https://linux-hardware.org/?probe=efa337f154) | Jan 12, 2024 |
| HP            | 250 G5 Notebook PC          | [8fb1c8650f](https://linux-hardware.org/?probe=8fb1c8650f) | Jan 12, 2024 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [da41d1e19b](https://linux-hardware.org/?probe=da41d1e19b) | Jan 11, 2024 |
| Dell          | Inspiron 1545               | [8740fc7c08](https://linux-hardware.org/?probe=8740fc7c08) | Jan 11, 2024 |
| Acer          | Aspire A515-58M             | [459fc30547](https://linux-hardware.org/?probe=459fc30547) | Jan 11, 2024 |
| Toshiba       | Satellite L750              | [44ec4c7459](https://linux-hardware.org/?probe=44ec4c7459) | Jan 11, 2024 |
| ASUSTek       | N56JR                       | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Medion        | E4251 MD61435               | [6a9251fa94](https://linux-hardware.org/?probe=6a9251fa94) | Jan 11, 2024 |
| Apple         | MacBookPro14,1              | [8762757dc7](https://linux-hardware.org/?probe=8762757dc7) | Jan 10, 2024 |
| HUAWEI        | HVY-WXX9                    | [2a28690851](https://linux-hardware.org/?probe=2a28690851) | Jan 10, 2024 |
| HP            | Pavilion Sleekbook 14       | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Toshiba       | STI NI 1401                 | [be4bcf5468](https://linux-hardware.org/?probe=be4bcf5468) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire E1-570G              | [2bb5dcf476](https://linux-hardware.org/?probe=2bb5dcf476) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| Toshiba       | Satellite C850              | [38fb6d3619](https://linux-hardware.org/?probe=38fb6d3619) | Jan 09, 2024 |
| Toshiba       | Satellite C850              | [c6faf796f4](https://linux-hardware.org/?probe=c6faf796f4) | Jan 09, 2024 |
| Acer          | Aspire 6530G                | [184836d752](https://linux-hardware.org/?probe=184836d752) | Jan 09, 2024 |
| HP            | ZBook 15u G5                | [6636e9d9f7](https://linux-hardware.org/?probe=6636e9d9f7) | Jan 09, 2024 |
| Dell          | Latitude E5520              | [cae81ff9aa](https://linux-hardware.org/?probe=cae81ff9aa) | Jan 09, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [2c022aaecf](https://linux-hardware.org/?probe=2c022aaecf) | Jan 09, 2024 |
| Samsung       | 550XBE/350XBE               | [40266fb2b6](https://linux-hardware.org/?probe=40266fb2b6) | Jan 08, 2024 |
| HONOR         | BBR-WAX9                    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| Toshiba       | Satellite P200              | [bda7517862](https://linux-hardware.org/?probe=bda7517862) | Jan 08, 2024 |
| HP            | EliteBook 8440p             | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| SGIN          | M15                         | [b0b7267ad7](https://linux-hardware.org/?probe=b0b7267ad7) | Jan 08, 2024 |
| ASUSTek       | X550CC                      | [b4987d6897](https://linux-hardware.org/?probe=b4987d6897) | Jan 08, 2024 |
| Lenovo        | ThinkPad W550s 20E2000PM... | [0a3bac66b1](https://linux-hardware.org/?probe=0a3bac66b1) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [a24204426f](https://linux-hardware.org/?probe=a24204426f) | Jan 08, 2024 |
| HP            | Presario CQ42               | [6addf001a5](https://linux-hardware.org/?probe=6addf001a5) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK T935               | [c3454270ef](https://linux-hardware.org/?probe=c3454270ef) | Jan 08, 2024 |
| ASUSTek       | X756UV                      | [8e9a0ad7c4](https://linux-hardware.org/?probe=8e9a0ad7c4) | Jan 08, 2024 |
| HP            | Pavilion TS 15              | [730453df05](https://linux-hardware.org/?probe=730453df05) | Jan 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [1a8316e6ab](https://linux-hardware.org/?probe=1a8316e6ab) | Jan 08, 2024 |
| ASUSTek       | UL50VT                      | [428d20a1eb](https://linux-hardware.org/?probe=428d20a1eb) | Jan 07, 2024 |
| HP            | ZBook 15 G2                 | [1db012c1ff](https://linux-hardware.org/?probe=1db012c1ff) | Jan 07, 2024 |
| ASUSTek       | K54LY                       | [58b75cfaa8](https://linux-hardware.org/?probe=58b75cfaa8) | Jan 07, 2024 |
| Acer          | Swift SF314-511             | [14eac9efff](https://linux-hardware.org/?probe=14eac9efff) | Jan 07, 2024 |
| Acer          | Aspire E1-570G              | [3c08b1958e](https://linux-hardware.org/?probe=3c08b1958e) | Jan 07, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [cc9bcb19e4](https://linux-hardware.org/?probe=cc9bcb19e4) | Jan 07, 2024 |
| Dell          | Latitude E5420              | [40835d5737](https://linux-hardware.org/?probe=40835d5737) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b02f06751f](https://linux-hardware.org/?probe=b02f06751f) | Jan 07, 2024 |
| Dell          | Latitude E5470              | [959af07fd5](https://linux-hardware.org/?probe=959af07fd5) | Jan 07, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [c372a02c46](https://linux-hardware.org/?probe=c372a02c46) | Jan 07, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [9d297cdfcb](https://linux-hardware.org/?probe=9d297cdfcb) | Jan 06, 2024 |
| Acer          | Aspire 7530G                | [412d583cbd](https://linux-hardware.org/?probe=412d583cbd) | Jan 06, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | [900bfdd9a8](https://linux-hardware.org/?probe=900bfdd9a8) | Jan 06, 2024 |
| Acer          | Aspire ES1-512              | [c24ea3ef71](https://linux-hardware.org/?probe=c24ea3ef71) | Jan 06, 2024 |
| Lenovo        | ThinkPad L412 0585A38       | [527b75e8b3](https://linux-hardware.org/?probe=527b75e8b3) | Jan 06, 2024 |
| HP            | ENVY dv6                    | [12f54bd4e0](https://linux-hardware.org/?probe=12f54bd4e0) | Jan 06, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ef882bce34](https://linux-hardware.org/?probe=ef882bce34) | Jan 05, 2024 |
| Apple         | MacBookPro9,2               | [c606f10b1d](https://linux-hardware.org/?probe=c606f10b1d) | Jan 04, 2024 |
| Apple         | MacBookPro5,5               | [5242f988d3](https://linux-hardware.org/?probe=5242f988d3) | Jan 04, 2024 |
| HP            | Pavilion Power Laptop 15... | [37ea5af9b1](https://linux-hardware.org/?probe=37ea5af9b1) | Jan 04, 2024 |
| Fujitsu       | STYLISTIC Q702              | [27863be159](https://linux-hardware.org/?probe=27863be159) | Jan 04, 2024 |
| Apple         | MacBookAir7,2               | [8e378cce52](https://linux-hardware.org/?probe=8e378cce52) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| Compal        | JHL90 REFERENCE             | [ba4b52e111](https://linux-hardware.org/?probe=ba4b52e111) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| ASUSTek       | P50IJ                       | [5a72912f2f](https://linux-hardware.org/?probe=5a72912f2f) | Jan 03, 2024 |
| Apple         | MacBookPro5,5               | [76f1cdbedb](https://linux-hardware.org/?probe=76f1cdbedb) | Jan 03, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [602ef69f04](https://linux-hardware.org/?probe=602ef69f04) | Jan 03, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2cf15e0bf0](https://linux-hardware.org/?probe=2cf15e0bf0) | Jan 02, 2024 |
| HUAWEI        | BOHL-WXX9                   | [bc70b50aec](https://linux-hardware.org/?probe=bc70b50aec) | Jan 02, 2024 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [0781004009](https://linux-hardware.org/?probe=0781004009) | Jan 02, 2024 |
| ASUSTek       | K53SV                       | [0cc0c3f5e0](https://linux-hardware.org/?probe=0cc0c3f5e0) | Jan 02, 2024 |
| iQual         | NQ4X                        | [5c66dfd710](https://linux-hardware.org/?probe=5c66dfd710) | Jan 02, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| MSI           | N6105                       | [0b934bf922](https://linux-hardware.org/?probe=0b934bf922) | Jan 01, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [9c0957293d](https://linux-hardware.org/?probe=9c0957293d) | Jan 01, 2024 |
| Sony          | VJF153                      | [9bf924f424](https://linux-hardware.org/?probe=9bf924f424) | Jan 01, 2024 |
| MSI           | N6105                       | [24f1343e04](https://linux-hardware.org/?probe=24f1343e04) | Jan 01, 2024 |
| Acer          | One 14 Z8-415               | [b022baea77](https://linux-hardware.org/?probe=b022baea77) | Jan 01, 2024 |
| Acer          | One 14 Z8-415               | [0e2bbf3d20](https://linux-hardware.org/?probe=0e2bbf3d20) | Jan 01, 2024 |
| Sony          | VJF153                      | [b3949d3670](https://linux-hardware.org/?probe=b3949d3670) | Jan 01, 2024 |
| Sony          | VGN-NW11S_S                 | [6d47430c42](https://linux-hardware.org/?probe=6d47430c42) | Jan 01, 2024 |
| Sony          | VGN-NW11S_S                 | [e898dd413e](https://linux-hardware.org/?probe=e898dd413e) | Jan 01, 2024 |
| HP            | Pavilion Gaming Notebook    | [8fdfce9fb8](https://linux-hardware.org/?probe=8fdfce9fb8) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | [92906e6c95](https://linux-hardware.org/?probe=92906e6c95) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | [e2ebd9354f](https://linux-hardware.org/?probe=e2ebd9354f) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| Sony          | VGN-CS21Z_Q                 | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| DERE          | Unknown                     | [0c27b482df](https://linux-hardware.org/?probe=0c27b482df) | Dec 30, 2023 |
| Sony          | VGN-CR21S_W                 | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9e856c326a](https://linux-hardware.org/?probe=9e856c326a) | Dec 29, 2023 |
| ASUSTek       | K54LY                       | [d2e504447e](https://linux-hardware.org/?probe=d2e504447e) | Dec 29, 2023 |
| Dell          | Inspiron 7348               | [a55c6eef41](https://linux-hardware.org/?probe=a55c6eef41) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| HP            | OMEN by Laptop              | [71d20fd45b](https://linux-hardware.org/?probe=71d20fd45b) | Dec 28, 2023 |
| Fujitsu       | LIFEBOOK E734               | [2265b1d34f](https://linux-hardware.org/?probe=2265b1d34f) | Dec 28, 2023 |
| HP            | ZBook 14u G6                | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Packard Be... | EasyNote TN36               | [2b83138160](https://linux-hardware.org/?probe=2b83138160) | Dec 28, 2023 |
| Apple         | MacBookPro8,3               | [e47426bf12](https://linux-hardware.org/?probe=e47426bf12) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [074b414446](https://linux-hardware.org/?probe=074b414446) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [283075fa43](https://linux-hardware.org/?probe=283075fa43) | Dec 28, 2023 |
| ASUSTek       | X555LB                      | [f29fe264f5](https://linux-hardware.org/?probe=f29fe264f5) | Dec 28, 2023 |
| Dell          | Latitude 3380               | [4f9660f132](https://linux-hardware.org/?probe=4f9660f132) | Dec 28, 2023 |
| HP            | Pavilion dv7                | [4b1ea284d3](https://linux-hardware.org/?probe=4b1ea284d3) | Dec 28, 2023 |
| Dell          | Latitude 3380               | [bb1422b9bd](https://linux-hardware.org/?probe=bb1422b9bd) | Dec 28, 2023 |
| Dell          | Vostro 2420                 | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| Acer          | Aspire E1-570               | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| HP            | Compaq 2510p                | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| UNOWHY        | Y13G012S4EI                 | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [cce90b21c6](https://linux-hardware.org/?probe=cce90b21c6) | Dec 27, 2023 |
| Hampoo        | L1W6_I1101_C Reserved       | [ad4de7dcab](https://linux-hardware.org/?probe=ad4de7dcab) | Dec 26, 2023 |
| Dell          | Latitude E7450              | [84dc5f09e7](https://linux-hardware.org/?probe=84dc5f09e7) | Dec 26, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [44db3755d8](https://linux-hardware.org/?probe=44db3755d8) | Dec 26, 2023 |
| Juana Mans... | SF20GM7                     | [697c873386](https://linux-hardware.org/?probe=697c873386) | Dec 26, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b35c9836e7](https://linux-hardware.org/?probe=b35c9836e7) | Dec 26, 2023 |
| Lenovo        | ThinkPad E480 20KN003XUS    | [b83c19a718](https://linux-hardware.org/?probe=b83c19a718) | Dec 26, 2023 |
| Unknown       | Unknown                     | [64873f6716](https://linux-hardware.org/?probe=64873f6716) | Dec 26, 2023 |
| HP            | Laptop 15-db1xxx            | [692cf22259](https://linux-hardware.org/?probe=692cf22259) | Dec 25, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [ae928b9cc1](https://linux-hardware.org/?probe=ae928b9cc1) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [e7d00bdca8](https://linux-hardware.org/?probe=e7d00bdca8) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [7feb95b534](https://linux-hardware.org/?probe=7feb95b534) | Dec 25, 2023 |
| Lenovo        | Unknown                     | [9faf2278bb](https://linux-hardware.org/?probe=9faf2278bb) | Dec 24, 2023 |
| Lenovo        | V110-15ISK 80TL             | [dd911fd507](https://linux-hardware.org/?probe=dd911fd507) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| Dell          | Latitude 5300               | [68336d8bc1](https://linux-hardware.org/?probe=68336d8bc1) | Dec 24, 2023 |
| Teclast       | F6 Plus                     | [a8fee53f37](https://linux-hardware.org/?probe=a8fee53f37) | Dec 24, 2023 |
| Acer          | Nitro AN517-55              | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| HP            | Victus by 15.6 inch Gami... | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Unknown       | W1415A                      | [f1fbd72c23](https://linux-hardware.org/?probe=f1fbd72c23) | Dec 23, 2023 |
| Sony          | VPCF215FX                   | [1a79c8b60f](https://linux-hardware.org/?probe=1a79c8b60f) | Dec 23, 2023 |
| Apple         | MacBookPro7,1               | [0f291ca562](https://linux-hardware.org/?probe=0f291ca562) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| HP            | EliteBook 745 G6            | [9bf64ae4b7](https://linux-hardware.org/?probe=9bf64ae4b7) | Dec 23, 2023 |
| Medion        | X682X                       | [c0deb0e748](https://linux-hardware.org/?probe=c0deb0e748) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [ae01ab2ebe](https://linux-hardware.org/?probe=ae01ab2ebe) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude 5440               | [bd5e743ebb](https://linux-hardware.org/?probe=bd5e743ebb) | Dec 21, 2023 |
| Dell          | Latitude E7270              | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| HP            | 1000                        | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Apple         | MacBookPro14,1              | [e221a6befb](https://linux-hardware.org/?probe=e221a6befb) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | [13432c28a6](https://linux-hardware.org/?probe=13432c28a6) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | [0eb55bee7d](https://linux-hardware.org/?probe=0eb55bee7d) | Dec 20, 2023 |
| Toshiba       | Satellite C850              | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [2dcde776ad](https://linux-hardware.org/?probe=2dcde776ad) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| Framework     | Laptop                      | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Medion        | E6246 MD63200               | [eda979df79](https://linux-hardware.org/?probe=eda979df79) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [07c7da687a](https://linux-hardware.org/?probe=07c7da687a) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [e6ad27a4dd](https://linux-hardware.org/?probe=e6ad27a4dd) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Irbis         | NB12                        | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| Google        | Phaser360                   | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| HP            | 15                          | [b1de66d4ed](https://linux-hardware.org/?probe=b1de66d4ed) | Dec 16, 2023 |
| HP            | Notebook                    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Medion        | P7624                       | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Dell          | Inspiron 15 5510            | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| Dell          | Inspiron 3501               | [67a35f1dd7](https://linux-hardware.org/?probe=67a35f1dd7) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| Apple         | MacBookPro8,3               | [08a4bea1d7](https://linux-hardware.org/?probe=08a4bea1d7) | Dec 09, 2023 |
| ASUSTek       | X550VC                      | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| Acer          | AOD257                      | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [45c2afd3f1](https://linux-hardware.org/?probe=45c2afd3f1) | Dec 08, 2023 |
| Dell          | Latitude E5470              | [cea78b64d4](https://linux-hardware.org/?probe=cea78b64d4) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| Dell          | Latitude 7490               | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| HP            | Pavilion dv7                | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| HP            | Pavilion dv5                | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Dell          | Latitude D830               | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| Lenovo        | Z710 20250                  | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| Samsung       | 530XBB                      | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| Acer          | Aspire One 721              | [e50838c5ff](https://linux-hardware.org/?probe=e50838c5ff) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Apple         | MacBookPro14,3              | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Lenovo        | ThinkPad X60 1707Y91        | [ac0e28ee75](https://linux-hardware.org/?probe=ac0e28ee75) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Medion        | E5214                       | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Dell          | Latitude 5490               | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| HP            | ZBook 14u G6                | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| HP            | Presario CQ62               | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Lenovo        | Z40-70 20366                | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| Acer          | Aspire E1-531               | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| Dell          | Latitude E7450              | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| Dell          | Latitude E6520              | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | ENVY 17                     | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| HP            | ENVY 17                     | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Acer          | Aspire 5738                 | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| Dell          | Precision 7530              | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| Dell          | Latitude 5490               | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| HP            | Pavilion g7                 | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| HP            | Compaq Presario CQ60        | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| HP            | 250 G8 Notebook PC          | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Alienware     | M14xR2                      | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dell          | Precision 5530              | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Dell          | G3 3579                     | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Acer          | Aspire ES1-521              | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| HP            | Pavilion dv6                | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | Notebook                    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Dell          | XPS 13 9360                 | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Apple         | MacBook4,1                  | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Lenovo        | V110-14IAP 80TF             | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Dell          | Latitude E5470              | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| Dell          | Precision M4700             | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | Pavilion g7                 | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 2162      | 62.65%  |
| Zorin 15 | 1020      | 29.56%  |
| Zorin 17 | 154       | 4.46%   |
| Zorin 12 | 115       | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 3433      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 137       | 3.48%   |
| 5.11.0-38-generic | 101       | 2.57%   |
| 5.11.0-27-generic | 94        | 2.39%   |
| 5.15.0-52-generic | 93        | 2.36%   |
| 5.15.0-58-generic | 91        | 2.31%   |
| 5.15.0-46-generic | 88        | 2.24%   |
| 6.2.0-39-generic  | 81        | 2.06%   |
| 5.15.0-91-generic | 79        | 2.01%   |
| 5.13.0-30-generic | 74        | 1.88%   |
| 5.3.0-40-generic  | 67        | 1.7%    |
| 5.15.0-78-generic | 67        | 1.7%    |
| 5.11.0-37-generic | 67        | 1.7%    |
| 5.11.0-40-generic | 65        | 1.65%   |
| 5.15.0-69-generic | 63        | 1.6%    |
| 5.15.0-67-generic | 63        | 1.6%    |
| 5.11.0-41-generic | 63        | 1.6%    |
| 5.4.0-42-generic  | 61        | 1.55%   |
| 5.13.0-39-generic | 60        | 1.52%   |
| 5.15.0-88-generic | 59        | 1.5%    |
| 5.11.0-34-generic | 57        | 1.45%   |
| 5.15.0-76-generic | 56        | 1.42%   |
| 5.15.0-60-generic | 56        | 1.42%   |
| 5.11.0-43-generic | 56        | 1.42%   |
| 5.15.0-71-generic | 55        | 1.4%    |
| 5.3.0-46-generic  | 53        | 1.35%   |
| 5.15.0-48-generic | 51        | 1.3%    |
| 5.13.0-44-generic | 48        | 1.22%   |
| 5.3.0-51-generic  | 47        | 1.19%   |
| 5.0.0-37-generic  | 47        | 1.19%   |
| 5.13.0-40-generic | 46        | 1.17%   |
| 5.15.0-86-generic | 44        | 1.12%   |
| 6.5.0-14-generic  | 43        | 1.09%   |
| 5.15.0-84-generic | 43        | 1.09%   |
| 5.15.0-53-generic | 43        | 1.09%   |
| 5.15.0-89-generic | 41        | 1.04%   |
| 5.13.0-35-generic | 40        | 1.02%   |
| 5.4.0-47-generic  | 38        | 0.97%   |
| 5.3.0-53-generic  | 37        | 0.94%   |
| 5.13.0-28-generic | 37        | 0.94%   |
| 5.4.0-45-generic  | 36        | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 1227      | 34.34%  |
| 5.4.0   | 598       | 16.74%  |
| 5.11.0  | 550       | 15.39%  |
| 5.13.0  | 406       | 11.36%  |
| 5.3.0   | 312       | 8.73%   |
| 4.15.0  | 111       | 3.11%   |
| 5.0.0   | 89        | 2.49%   |
| 6.2.0   | 84        | 2.35%   |
| 6.5.0   | 69        | 1.93%   |
| 4.18.0  | 45        | 1.26%   |
| 5.8.0   | 24        | 0.67%   |
| 5.14.0  | 8         | 0.22%   |
| 6.3.13  | 4         | 0.11%   |
| 4.4.0   | 4         | 0.11%   |
| 6.5.7   | 2         | 0.06%   |
| 6.2.16  | 2         | 0.06%   |
| 5.6.0   | 2         | 0.06%   |
| 5.19.0  | 2         | 0.06%   |
| 5.18.15 | 2         | 0.06%   |
| 5.16.0  | 2         | 0.06%   |
| 5.10.0  | 2         | 0.06%   |
| 6.7.3   | 1         | 0.03%   |
| 6.6.7   | 1         | 0.03%   |
| 6.6.13  | 1         | 0.03%   |
| 6.6.1   | 1         | 0.03%   |
| 6.3.2   | 1         | 0.03%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.22  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.9.12  | 1         | 0.03%   |
| 5.9.0   | 1         | 0.03%   |
| 5.7.1   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.4.1   | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.12 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1229      | 34.4%   |
| 5.4     | 600       | 16.79%  |
| 5.11    | 550       | 15.39%  |
| 5.13    | 407       | 11.39%  |
| 5.3     | 312       | 8.73%   |
| 4.15    | 111       | 3.11%   |
| 5.0     | 89        | 2.49%   |
| 6.2     | 87        | 2.43%   |
| 6.5     | 71        | 1.99%   |
| 4.18    | 45        | 1.26%   |
| 5.8     | 24        | 0.67%   |
| 5.14    | 8         | 0.22%   |
| 6.3     | 6         | 0.17%   |
| 5.19    | 6         | 0.17%   |
| 5.10    | 4         | 0.11%   |
| 4.4     | 4         | 0.11%   |
| 6.6     | 3         | 0.08%   |
| 6.0     | 3         | 0.08%   |
| 5.18    | 3         | 0.08%   |
| 5.16    | 3         | 0.08%   |
| 5.9     | 2         | 0.06%   |
| 5.6     | 2         | 0.06%   |
| 6.7     | 1         | 0.03%   |
| 6.1     | 1         | 0.03%   |
| 5.7     | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3151      | 91.71%  |
| i686   | 285       | 8.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 2497      | 71.9%   |
| XFCE       | 775       | 22.32%  |
| Unknown    | 173       | 4.98%   |
| X-Cinnamon | 7         | 0.2%    |
| KDE5       | 7         | 0.2%    |
| Unity      | 3         | 0.09%   |
| KDE        | 3         | 0.09%   |
| Budgie     | 3         | 0.09%   |
| i3         | 2         | 0.06%   |
| LXQt       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| Cinnamon   | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3169      | 91.35%  |
| Wayland | 190       | 5.48%   |
| Unknown | 109       | 3.14%   |
| Tty     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2706      | 77.58%  |
| GDM3    | 285       | 8.17%   |
| GDM     | 278       | 7.97%   |
| LightDM | 210       | 6.02%   |
| TDM     | 6         | 0.17%   |
| SDDM    | 2         | 0.06%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1209      | 34.93%  |
| de_DE   | 285       | 8.23%   |
| pt_BR   | 208       | 6.01%   |
| en_GB   | 203       | 5.87%   |
| it_IT   | 134       | 3.87%   |
| Unknown | 127       | 3.67%   |
| fr_FR   | 117       | 3.38%   |
| es_ES   | 116       | 3.35%   |
| en_IN   | 107       | 3.09%   |
| en_CA   | 95        | 2.74%   |
| pl_PL   | 88        | 2.54%   |
| es_MX   | 53        | 1.53%   |
| en_AU   | 51        | 1.47%   |
| nl_NL   | 49        | 1.42%   |
| pt_PT   | 48        | 1.39%   |
| ru_RU   | 41        | 1.18%   |
| cs_CZ   | 40        | 1.16%   |
| en_ZA   | 35        | 1.01%   |
| es_AR   | 34        | 0.98%   |
| tr_TR   | 26        | 0.75%   |
| sv_SE   | 26        | 0.75%   |
| de_AT   | 22        | 0.64%   |
| hu_HU   | 21        | 0.61%   |
| es_CL   | 21        | 0.61%   |
| C       | 21        | 0.61%   |
| en_NZ   | 20        | 0.58%   |
| de_CH   | 17        | 0.49%   |
| nl_BE   | 13        | 0.38%   |
| ja_JP   | 13        | 0.38%   |
| fr_CA   | 13        | 0.38%   |
| fr_BE   | 13        | 0.38%   |
| es_CO   | 12        | 0.35%   |
| el_GR   | 12        | 0.35%   |
| da_DK   | 12        | 0.35%   |
| ro_RO   | 10        | 0.29%   |
| es_PE   | 10        | 0.29%   |
| en_PH   | 9         | 0.26%   |
| bg_BG   | 9         | 0.26%   |
| ru_UA   | 7         | 0.2%    |
| hr_HR   | 7         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1802      | 51.8%   |
| EFI  | 1677      | 48.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3170      | 91.51%  |
| Tmpfs   | 104       | 3%      |
| Overlay | 71        | 2.05%   |
| Zfs     | 39        | 1.13%   |
| Btrfs   | 33        | 0.95%   |
| Ext2    | 22        | 0.64%   |
| Unknown | 17        | 0.49%   |
| Xfs     | 4         | 0.12%   |
| Ext3    | 4         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2937      | 84.49%  |
| GPT     | 415       | 11.94%  |
| MBR     | 124       | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3289      | 95.22%  |
| Yes       | 165       | 4.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2935      | 85.05%  |
| Yes       | 516       | 14.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 771       | 22.46%  |
| Lenovo              | 550       | 16.02%  |
| Dell                | 519       | 15.12%  |
| ASUSTek Computer    | 330       | 9.61%   |
| Acer                | 281       | 8.19%   |
| Toshiba             | 180       | 5.24%   |
| Apple               | 104       | 3.03%   |
| Sony                | 63        | 1.84%   |
| Samsung Electronics | 63        | 1.84%   |
| MSI                 | 47        | 1.37%   |
| Google              | 34        | 0.99%   |
| Unknown             | 34        | 0.99%   |
| HUAWEI              | 31        | 0.9%    |
| Packard Bell        | 29        | 0.84%   |
| Medion              | 24        | 0.7%    |
| Fujitsu             | 24        | 0.7%    |
| Positivo            | 23        | 0.67%   |
| Fujitsu Siemens     | 21        | 0.61%   |
| Alienware           | 14        | 0.41%   |
| Notebook            | 13        | 0.38%   |
| Chuwi               | 11        | 0.32%   |
| AMI                 | 10        | 0.29%   |
| Panasonic           | 9         | 0.26%   |
| Gateway             | 9         | 0.26%   |
| Multilaser          | 8         | 0.23%   |
| eMachines           | 8         | 0.23%   |
| Semp Toshiba        | 7         | 0.2%    |
| Itautec             | 7         | 0.2%    |
| LG Electronics      | 6         | 0.17%   |
| Intel               | 6         | 0.17%   |
| Insyde              | 6         | 0.17%   |
| GPU Company         | 6         | 0.17%   |
| Digibras            | 6         | 0.17%   |
| Thomson             | 5         | 0.15%   |
| NEC Computers       | 5         | 0.15%   |
| Ematic              | 5         | 0.15%   |
| Clevo               | 5         | 0.15%   |
| TUXEDO              | 4         | 0.12%   |
| TrekStor            | 4         | 0.12%   |
| Razer               | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 66        | 1.92%   |
| HP Notebook             | 35        | 1.02%   |
| HP 15                   | 18        | 0.52%   |
| HP Pavilion Notebook    | 17        | 0.5%    |
| HP Pavilion dv6         | 17        | 0.5%    |
| HP Pavilion dv7         | 15        | 0.44%   |
| HP Pavilion 15          | 13        | 0.38%   |
| Dell Inspiron 1545      | 12        | 0.35%   |
| Toshiba Satellite C660  | 10        | 0.29%   |
| HP Pavilion g7          | 10        | 0.29%   |
| Dell Latitude E6400     | 10        | 0.29%   |
| Dell Latitude D630      | 10        | 0.29%   |
| Dell Inspiron 15-3567   | 10        | 0.29%   |
| HP Pavilion g6          | 9         | 0.26%   |
| HP Laptop 15-bw0xx      | 9         | 0.26%   |
| Apple MacBookPro8,1     | 9         | 0.26%   |
| HP EliteBook 8460p      | 8         | 0.23%   |
| HP EliteBook 840 G1     | 8         | 0.23%   |
| Dell Latitude E6540     | 8         | 0.23%   |
| Dell Latitude E6430     | 8         | 0.23%   |
| Dell Latitude E5470     | 8         | 0.23%   |
| Dell Inspiron 1525      | 8         | 0.23%   |
| Apple MacBookPro12,1    | 8         | 0.23%   |
| HP Pavilion dv6700      | 7         | 0.2%    |
| HP Pavilion 17          | 7         | 0.2%    |
| Dell Latitude E6410     | 7         | 0.2%    |
| Dell Inspiron 3521      | 7         | 0.2%    |
| Apple MacBookPro11,1    | 7         | 0.2%    |
| Toshiba Satellite A100  | 6         | 0.17%   |
| HP ProBook 640 G1       | 6         | 0.17%   |
| HP ProBook 4540s        | 6         | 0.17%   |
| HP Pavilion dv5         | 6         | 0.17%   |
| HP Laptop 15-db0xxx     | 6         | 0.17%   |
| HP Compaq Presario CQ60 | 6         | 0.17%   |
| Dell Latitude E6520     | 6         | 0.17%   |
| Dell Latitude E6420     | 6         | 0.17%   |
| Dell Inspiron 7520      | 6         | 0.17%   |
| Apple MacBookPro9,2     | 6         | 0.17%   |
| Apple MacBookAir7,2     | 6         | 0.17%   |
| Positivo Mobile         | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 233       | 6.79%   |
| Acer Aspire           | 198       | 5.77%   |
| Dell Latitude         | 197       | 5.74%   |
| HP Pavilion           | 189       | 5.51%   |
| Dell Inspiron         | 189       | 5.51%   |
| Lenovo IdeaPad        | 168       | 4.89%   |
| Toshiba Satellite     | 153       | 4.46%   |
| HP EliteBook          | 99        | 2.88%   |
| HP ProBook            | 81        | 2.36%   |
| HP Laptop             | 75        | 2.18%   |
| Unknown               | 66        | 1.92%   |
| HP Compaq             | 57        | 1.66%   |
| ASUS VivoBook         | 46        | 1.34%   |
| Dell Vostro           | 38        | 1.11%   |
| HP Notebook           | 35        | 1.02%   |
| Packard Bell EasyNote | 27        | 0.79%   |
| Dell XPS              | 27        | 0.79%   |
| HP ENVY               | 26        | 0.76%   |
| HP Stream             | 24        | 0.7%    |
| Dell Precision        | 23        | 0.67%   |
| ASUS ZenBook          | 22        | 0.64%   |
| ASUS ROG              | 22        | 0.64%   |
| HP 15                 | 21        | 0.61%   |
| HP Presario           | 18        | 0.52%   |
| HP ZBook              | 17        | 0.5%    |
| Fujitsu LIFEBOOK      | 17        | 0.5%    |
| Lenovo Yoga           | 16        | 0.47%   |
| HP 255                | 16        | 0.47%   |
| HP OMEN               | 15        | 0.44%   |
| Lenovo Legion         | 14        | 0.41%   |
| ASUS ASUS             | 14        | 0.41%   |
| Apple MacBookPro8     | 14        | 0.41%   |
| Dell Studio           | 13        | 0.38%   |
| Acer TravelMate       | 13        | 0.38%   |
| Fujitsu Siemens AMILO | 12        | 0.35%   |
| Apple MacBookPro5     | 12        | 0.35%   |
| Apple MacBookPro11    | 12        | 0.35%   |
| Dell System           | 11        | 0.32%   |
| Acer Swift            | 11        | 0.32%   |
| Acer Nitro            | 11        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 296       | 8.62%   |
| 2012    | 284       | 8.27%   |
| 2013    | 279       | 8.13%   |
| 2010    | 240       | 6.99%   |
| 2008    | 224       | 6.52%   |
| 2018    | 211       | 6.15%   |
| 2014    | 208       | 6.06%   |
| 2017    | 205       | 5.97%   |
| 2019    | 199       | 5.8%    |
| 2021    | 195       | 5.68%   |
| 2015    | 191       | 5.56%   |
| 2020    | 182       | 5.3%    |
| 2016    | 177       | 5.16%   |
| 2007    | 163       | 4.75%   |
| 2009    | 160       | 4.66%   |
| 2022    | 75        | 2.18%   |
| 2006    | 58        | 1.69%   |
| 2023    | 41        | 1.19%   |
| 2005    | 37        | 1.08%   |
| Unknown | 5         | 0.15%   |
| 2003    | 2         | 0.06%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3433      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3043      | 87.97%  |
| Enabled  | 416       | 12.03%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3394      | 98.86%  |
| Yes  | 39        | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1031      | 29.77%  |
| 3.01-4.0    | 981       | 28.33%  |
| 8.01-16.0   | 425       | 12.27%  |
| 16.01-24.0  | 355       | 10.25%  |
| 1.01-2.0    | 344       | 9.93%   |
| 2.01-3.0    | 117       | 3.38%   |
| 32.01-64.0  | 102       | 2.95%   |
| 0.51-1.0    | 74        | 2.14%   |
| 24.01-32.0  | 17        | 0.49%   |
| 64.01-256.0 | 17        | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1515      | 40.75%  |
| 2.01-3.0   | 1103      | 29.67%  |
| 3.01-4.0   | 433       | 11.65%  |
| 4.01-8.0   | 303       | 8.15%   |
| 0.51-1.0   | 295       | 7.93%   |
| 8.01-16.0  | 38        | 1.02%   |
| 0.01-0.5   | 25        | 0.67%   |
| 24.01-32.0 | 3         | 0.08%   |
| 16.01-24.0 | 3         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2664      | 76.35%  |
| 2      | 725       | 20.78%  |
| 3      | 72        | 2.06%   |
| 0      | 12        | 0.34%   |
| 4      | 10        | 0.29%   |
| 5      | 4         | 0.11%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1827      | 52.97%  |
| Yes       | 1622      | 47.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2812      | 81.7%   |
| No        | 630       | 18.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3331      | 96.92%  |
| No        | 106       | 3.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2296      | 66.19%  |
| No        | 1173      | 33.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 676       | 19.61%  |
| Germany      | 332       | 9.63%   |
| Brazil       | 241       | 6.99%   |
| UK           | 193       | 5.6%    |
| Italy        | 142       | 4.12%   |
| Canada       | 122       | 3.54%   |
| Spain        | 120       | 3.48%   |
| India        | 114       | 3.31%   |
| France       | 114       | 3.31%   |
| Netherlands  | 89        | 2.58%   |
| Poland       | 85        | 2.47%   |
| Mexico       | 79        | 2.29%   |
| Australia    | 57        | 1.65%   |
| Portugal     | 55        | 1.6%    |
| Sweden       | 47        | 1.36%   |
| Czechia      | 45        | 1.31%   |
| Austria      | 45        | 1.31%   |
| Russia       | 44        | 1.28%   |
| Belgium      | 43        | 1.25%   |
| Argentina    | 43        | 1.25%   |
| South Africa | 41        | 1.19%   |
| Romania      | 37        | 1.07%   |
| Switzerland  | 36        | 1.04%   |
| Turkey       | 35        | 1.02%   |
| Indonesia    | 33        | 0.96%   |
| Greece       | 27        | 0.78%   |
| New Zealand  | 23        | 0.67%   |
| Hungary      | 23        | 0.67%   |
| Japan        | 21        | 0.61%   |
| Colombia     | 21        | 0.61%   |
| Chile        | 21        | 0.61%   |
| Norway       | 19        | 0.55%   |
| Egypt        | 19        | 0.55%   |
| Serbia       | 17        | 0.49%   |
| Bulgaria     | 17        | 0.49%   |
| Denmark      | 16        | 0.46%   |
| Ireland      | 15        | 0.44%   |
| Finland      | 15        | 0.44%   |
| Ukraine      | 12        | 0.35%   |
| Philippines  | 12        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Vienna         | 26        | 0.72%   |
| Sao Paulo      | 25        | 0.69%   |
| Berlin         | 24        | 0.66%   |
| Madrid         | 23        | 0.64%   |
| Sydney         | 21        | 0.58%   |
| Milan          | 19        | 0.53%   |
| Munich         | 18        | 0.5%    |
| Rome           | 17        | 0.47%   |
| Johannesburg   | 17        | 0.47%   |
| New York       | 16        | 0.44%   |
| Hamburg        | 15        | 0.41%   |
| Athens         | 15        | 0.41%   |
| Amsterdam      | 15        | 0.41%   |
| Mexico City    | 14        | 0.39%   |
| Istanbul       | 14        | 0.39%   |
| Rio de Janeiro | 13        | 0.36%   |
| Paris          | 13        | 0.36%   |
| Montreal       | 13        | 0.36%   |
| Jakarta        | 13        | 0.36%   |
| Auckland       | 13        | 0.36%   |
| Warsaw         | 12        | 0.33%   |
| Toronto        | 12        | 0.33%   |
| Prague         | 12        | 0.33%   |
| Cairo          | 12        | 0.33%   |
| Stockholm      | 11        | 0.3%    |
| Seattle        | 11        | 0.3%    |
| Moscow         | 11        | 0.3%    |
| Denver         | 11        | 0.3%    |
| Delhi          | 11        | 0.3%    |
| Dallas         | 11        | 0.3%    |
| Buenos Aires   | 11        | 0.3%    |
| Bengaluru      | 11        | 0.3%    |
| Stuttgart      | 10        | 0.28%   |
| Nairobi        | 10        | 0.28%   |
| London         | 10        | 0.28%   |
| Glasgow        | 10        | 0.28%   |
| Bucharest      | 10        | 0.28%   |
| Bogotá        | 10        | 0.28%   |
| Belgrade       | 10        | 0.28%   |
| Melbourne      | 9         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 494       | 603    | 12.23%  |
| WDC                         | 474       | 582    | 11.73%  |
| Samsung Electronics         | 474       | 638    | 11.73%  |
| Toshiba                     | 397       | 452    | 9.83%   |
| Unknown                     | 347       | 471    | 8.59%   |
| SanDisk                     | 238       | 285    | 5.89%   |
| Hitachi                     | 183       | 214    | 4.53%   |
| Kingston                    | 182       | 223    | 4.5%    |
| Crucial                     | 128       | 155    | 3.17%   |
| HGST                        | 120       | 144    | 2.97%   |
| SK hynix                    | 98        | 113    | 2.43%   |
| Intel                       | 98        | 120    | 2.43%   |
| Micron Technology           | 73        | 91     | 1.81%   |
| China                       | 51        | 63     | 1.26%   |
| A-DATA Technology           | 47        | 53     | 1.16%   |
| Apple                       | 46        | 56     | 1.14%   |
| Fujitsu                     | 45        | 48     | 1.11%   |
| Intenso                     | 33        | 34     | 0.82%   |
| KIOXIA                      | 31        | 36     | 0.77%   |
| Unknown                     | 23        | 25     | 0.57%   |
| PNY                         | 22        | 27     | 0.54%   |
| SPCC                        | 21        | 28     | 0.52%   |
| LITEONIT                    | 20        | 23     | 0.5%    |
| Phison                      | 19        | 24     | 0.47%   |
| Netac                       | 19        | 19     | 0.47%   |
| LITEON                      | 17        | 21     | 0.42%   |
| Patriot                     | 16        | 20     | 0.4%    |
| Transcend                   | 15        | 20     | 0.37%   |
| Team                        | 14        | 15     | 0.35%   |
| JMicron Technology          | 14        | 15     | 0.35%   |
| GOODRAM                     | 13        | 14     | 0.32%   |
| Silicon Motion              | 11        | 13     | 0.27%   |
| OCZ                         | 10        | 11     | 0.25%   |
| Phison Electronics          | 9         | 9      | 0.22%   |
| Kingston Technology Company | 9         | 10     | 0.22%   |
| SABRENT                     | 8         | 9      | 0.2%    |
| MAXIO Technology (Hangzhou) | 7         | 7      | 0.17%   |
| KingSpec                    | 7         | 7      | 0.17%   |
| Hewlett-Packard             | 7         | 9      | 0.17%   |
| ASMT                        | 7         | 7      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 119       | 2.84%   |
| Unknown MMC Card  64GB                              | 94        | 2.24%   |
| Seagate ST1000LM035-1RK172 1TB                      | 58        | 1.38%   |
| Toshiba MQ01ABF050 500GB                            | 55        | 1.31%   |
| Toshiba MQ01ABD100 1TB                              | 47        | 1.12%   |
| Kingston SA400S37240G 240GB SSD                     | 46        | 1.1%    |
| Seagate ST500LT012-1DG142 500GB                     | 42        | 1%      |
| Unknown MMC Card  128GB                             | 38        | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 37        | 0.88%   |
| Toshiba MQ04ABF100 1TB                              | 35        | 0.84%   |
| Seagate ST9500325AS 500GB                           | 31        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 29        | 0.69%   |
| Unknown MMC Card  16GB                              | 27        | 0.64%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                     | 24        | 0.57%   |
| Crucial CT240BX500SSD1 240GB                        | 24        | 0.57%   |
| Unknown                                             | 23        | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 22        | 0.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 22        | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 22        | 0.53%   |
| SanDisk NVMe SSD Drive 256GB                        | 20        | 0.48%   |
| HGST HTS725050A7E630 500GB                          | 20        | 0.48%   |
| HGST HTS545050A7E680 500GB                          | 20        | 0.48%   |
| HGST HTS541010A9E680 1TB                            | 20        | 0.48%   |
| Samsung SSD 850 EVO 500GB                           | 19        | 0.45%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 19        | 0.45%   |
| Hitachi HTS545032B9A300 320GB                       | 19        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                        | 18        | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 17        | 0.41%   |
| Seagate Expansion 1TB                               | 17        | 0.41%   |
| Intel NVMe SSD Drive 512GB                          | 17        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                        | 16        | 0.38%   |
| Samsung SSD 860 EVO 500GB                           | 16        | 0.38%   |
| Unknown SD/MMC/MS PRO 256GB                         | 15        | 0.36%   |
| Samsung SSD 860 EVO 250GB                           | 15        | 0.36%   |
| Samsung SSD 850 EVO 250GB                           | 14        | 0.33%   |
| Toshiba MQ01ABD075 752GB                            | 13        | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 12        | 0.29%   |
| Seagate ST500LM021-1KJ152 500GB                     | 12        | 0.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 12        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 486       | 589    | 29.33%  |
| WDC                 | 394       | 476    | 23.78%  |
| Toshiba             | 334       | 375    | 20.16%  |
| Hitachi             | 183       | 214    | 11.04%  |
| HGST                | 120       | 144    | 7.24%   |
| Samsung Electronics | 50        | 55     | 3.02%   |
| Fujitsu             | 45        | 48     | 2.72%   |
| Unknown             | 15        | 21     | 0.91%   |
| JMicron Technology  | 10        | 11     | 0.6%    |
| Apple               | 5         | 5      | 0.3%    |
| IBM/Hitachi         | 4         | 5      | 0.24%   |
| TO Exter            | 2         | 3      | 0.12%   |
| External            | 2         | 2      | 0.12%   |
| XrayDisk            | 1         | 1      | 0.06%   |
| SSK                 | 1         | 1      | 0.06%   |
| SABRENT             | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| FC-1307             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 254       | 349    | 19.26%  |
| Kingston            | 158       | 196    | 11.98%  |
| SanDisk             | 130       | 157    | 9.86%   |
| Crucial             | 125       | 150    | 9.48%   |
| WDC                 | 59        | 75     | 4.47%   |
| China               | 50        | 62     | 3.79%   |
| Intel               | 43        | 49     | 3.26%   |
| A-DATA Technology   | 40        | 46     | 3.03%   |
| Toshiba             | 34        | 38     | 2.58%   |
| Apple               | 34        | 38     | 2.58%   |
| SK hynix            | 32        | 36     | 2.43%   |
| Micron Technology   | 31        | 36     | 2.35%   |
| PNY                 | 22        | 27     | 1.67%   |
| Intenso             | 22        | 22     | 1.67%   |
| SPCC                | 20        | 27     | 1.52%   |
| LITEONIT            | 20        | 23     | 1.52%   |
| Netac               | 17        | 17     | 1.29%   |
| LITEON              | 17        | 21     | 1.29%   |
| Patriot             | 16        | 20     | 1.21%   |
| Transcend           | 15        | 20     | 1.14%   |
| Team                | 14        | 15     | 1.06%   |
| GOODRAM             | 12        | 13     | 0.91%   |
| OCZ                 | 10        | 11     | 0.76%   |
| SABRENT             | 7         | 8      | 0.53%   |
| KingSpec            | 7         | 7      | 0.53%   |
| ASMT                | 7         | 7      | 0.53%   |
| Unknown             | 7         | 9      | 0.53%   |
| Phison              | 6         | 9      | 0.45%   |
| Plextor             | 5         | 5      | 0.38%   |
| Lexar               | 5         | 5      | 0.38%   |
| Hewlett-Packard     | 5         | 7      | 0.38%   |
| Teclast             | 4         | 4      | 0.3%    |
| Gigabyte Technology | 4         | 4      | 0.3%    |
| Apacer              | 4         | 4      | 0.3%    |
| Verbatim            | 3         | 3      | 0.23%   |
| Mushkin             | 3         | 3      | 0.23%   |
| Fanxiang            | 3         | 4      | 0.23%   |
| Emtec               | 3         | 3      | 0.23%   |
| BHT                 | 3         | 4      | 0.23%   |
| Vaseky              | 2         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1619      | 1955   | 41.46%  |
| SSD     | 1254      | 1608   | 32.11%  |
| NVMe    | 614       | 813    | 15.72%  |
| MMC     | 346       | 467    | 8.86%   |
| Unknown | 72        | 81     | 1.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2693      | 3472   | 71.36%  |
| NVMe | 614       | 811    | 16.27%  |
| MMC  | 346       | 467    | 9.17%   |
| SAS  | 121       | 174    | 3.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2109      | 2635   | 73.95%  |
| 0.51-1.0   | 669       | 830    | 23.46%  |
| 1.01-2.0   | 62        | 77     | 2.17%   |
| 4.01-10.0  | 6         | 10     | 0.21%   |
| 3.01-4.0   | 5         | 10     | 0.18%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1248      | 35.29%  |
| 251-500        | 906       | 25.62%  |
| 501-1000       | 460       | 13.01%  |
| 51-100         | 383       | 10.83%  |
| 21-50          | 228       | 6.45%   |
| 1001-2000      | 112       | 3.17%   |
| 1-20           | 104       | 2.94%   |
| Unknown        | 36        | 1.02%   |
| More than 3000 | 33        | 0.93%   |
| 2001-3000      | 26        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1745      | 47.37%  |
| 21-50          | 933       | 25.33%  |
| 51-100         | 394       | 10.69%  |
| 101-250        | 330       | 8.96%   |
| 251-500        | 145       | 3.94%   |
| 501-1000       | 64        | 1.74%   |
| Unknown        | 36        | 0.98%   |
| 1001-2000      | 20        | 0.54%   |
| More than 3000 | 12        | 0.33%   |
| 2001-3000      | 5         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 3         | 3      | 3.95%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 3.95%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 2.63%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.63%   |
| Seagate ST1000LM048-2E7172 1TB                   | 2         | 2      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 2.63%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 2.63%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 2.63%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.32%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.32%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.32%   |
| WDC WD3200BPVT-55ZEST0 320GB                     | 1         | 1      | 1.32%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.32%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.32%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.32%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.32%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.32%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.32%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.32%   |
| Toshiba MK5061GSY 500GB                          | 1         | 1      | 1.32%   |
| Toshiba MK2046GSX 200GB                          | 1         | 1      | 1.32%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.32%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.32%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 1.32%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.32%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.32%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.32%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.32%   |
| Seagate ST9160314AS 160GB                        | 1         | 1      | 1.32%   |
| Seagate ST9120822AS 120GB                        | 1         | 1      | 1.32%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.32%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 1.32%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.32%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.32%   |
| SanDisk SSD PLUS 480GB                           | 1         | 1      | 1.32%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 24     | 31.58%  |
| Toshiba             | 11        | 11     | 14.47%  |
| WDC                 | 8         | 8      | 10.53%  |
| HGST                | 8         | 9      | 10.53%  |
| Hitachi             | 7         | 7      | 9.21%   |
| Samsung Electronics | 4         | 4      | 5.26%   |
| Kingston            | 3         | 3      | 3.95%   |
| SK hynix            | 2         | 2      | 2.63%   |
| Teclast             | 1         | 1      | 1.32%   |
| SanDisk             | 1         | 1      | 1.32%   |
| POLION              | 1         | 1      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| Hewlett-Packard     | 1         | 1      | 1.32%   |
| Drevo               | 1         | 1      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 24     | 41.38%  |
| Toshiba             | 9         | 9      | 15.52%  |
| WDC                 | 8         | 8      | 13.79%  |
| HGST                | 8         | 9      | 13.79%  |
| Hitachi             | 7         | 7      | 12.07%  |
| Samsung Electronics | 2         | 2      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 58        | 59     | 76.32%  |
| SSD  | 16        | 16     | 21.05%  |
| NVMe | 2         | 2      | 2.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3102      | 4451   | 88.7%   |
| Works    | 317       | 393    | 9.06%   |
| Malfunc  | 75        | 77     | 2.14%   |
| Failed   | 2         | 2      | 0.06%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2496      | 68.05%  |
| AMD                              | 427       | 11.64%  |
| Samsung Electronics              | 206       | 5.62%   |
| SanDisk                          | 120       | 3.27%   |
| SK hynix                         | 63        | 1.72%   |
| Nvidia                           | 56        | 1.53%   |
| Micron Technology                | 43        | 1.17%   |
| Kingston Technology Company      | 32        | 0.87%   |
| Toshiba America Info Systems     | 31        | 0.85%   |
| Silicon Integrated Systems [SiS] | 31        | 0.85%   |
| KIOXIA                           | 31        | 0.85%   |
| Phison Electronics               | 23        | 0.63%   |
| Silicon Motion                   | 15        | 0.41%   |
| VIA Technologies                 | 13        | 0.35%   |
| ADATA Technology                 | 11        | 0.3%    |
| Micron/Crucial Technology        | 10        | 0.27%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.22%   |
| Marvell Technology Group         | 6         | 0.16%   |
| Lite-On Technology               | 6         | 0.16%   |
| Apple                            | 6         | 0.16%   |
| Union Memory (Shenzhen)          | 5         | 0.14%   |
| Realtek Semiconductor            | 5         | 0.14%   |
| JMicron Technology               | 5         | 0.14%   |
| ASMedia Technology               | 4         | 0.11%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| Solid State Storage Technology   | 2         | 0.05%   |
| Silicon Image                    | 2         | 0.05%   |
| Netac Technology                 | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 328       | 8.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 278       | 6.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 250       | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 219       | 5.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 195       | 4.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 179       | 4.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 134       | 3.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 129       | 3.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 113       | 2.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 106       | 2.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 93        | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 80        | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 78        | 1.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 69        | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                              | 66        | 1.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 63        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 60        | 1.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 55        | 1.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 53        | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 50        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 48        | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 46        | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 44        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 39        | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 39        | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 39        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                              | 37        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 34        | 0.83%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 30        | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 29        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 29        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                            | 28        | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 27        | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 27        | 0.66%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 26        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 25        | 0.61%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 25        | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 24        | 0.59%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 21        | 0.51%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 21        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2492      | 64.41%  |
| NVMe | 616       | 15.92%  |
| IDE  | 486       | 12.56%  |
| RAID | 275       | 7.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2882      | 83.95%  |
| AMD          | 550       | 16.02%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 43        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 39        | 1.14%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 39        | 1.14%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 35        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 32        | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 31        | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 30        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 29        | 0.84%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 28        | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 26        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 24        | 0.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 24        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 23        | 0.67%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 23        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 22        | 0.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 22        | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 21        | 0.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 21        | 0.61%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 21        | 0.61%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 21        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 20        | 0.58%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 20        | 0.58%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 20        | 0.58%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 20        | 0.58%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.58%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 19        | 0.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 19        | 0.55%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.55%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.55%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 742       | 21.59%  |
| Intel Core i7           | 516       | 15.02%  |
| Intel Core i3           | 339       | 9.87%   |
| Intel Celeron           | 307       | 8.93%   |
| Intel Core 2 Duo        | 274       | 7.97%   |
| Intel Atom              | 172       | 5.01%   |
| Other                   | 166       | 4.83%   |
| Intel Pentium           | 110       | 3.2%    |
| AMD Ryzen 5             | 95        | 2.76%   |
| AMD Ryzen 7             | 62        | 1.8%    |
| AMD A6                  | 53        | 1.54%   |
| Intel Pentium Dual-Core | 49        | 1.43%   |
| Intel Genuine           | 44        | 1.28%   |
| AMD A4                  | 42        | 1.22%   |
| Intel Pentium Dual      | 34        | 0.99%   |
| AMD A8                  | 30        | 0.87%   |
| Intel Core 2            | 29        | 0.84%   |
| Intel Celeron M         | 27        | 0.79%   |
| AMD Ryzen 3             | 27        | 0.79%   |
| AMD A10                 | 27        | 0.79%   |
| Intel Pentium M         | 26        | 0.76%   |
| AMD E1                  | 22        | 0.64%   |
| AMD E                   | 20        | 0.58%   |
| AMD Turion 64 X2 Mobile | 17        | 0.49%   |
| AMD Ryzen 9             | 14        | 0.41%   |
| Intel Core M            | 13        | 0.38%   |
| Intel Pentium Silver    | 12        | 0.35%   |
| AMD E2                  | 11        | 0.32%   |
| AMD Athlon II           | 11        | 0.32%   |
| Intel Celeron Dual-Core | 10        | 0.29%   |
| AMD Turion 64 Mobile    | 9         | 0.26%   |
| AMD Athlon 64 X2        | 9         | 0.26%   |
| Intel Core Duo          | 8         | 0.23%   |
| AMD Sempron             | 7         | 0.2%    |
| AMD Mobile Sempron      | 7         | 0.2%    |
| AMD Athlon              | 7         | 0.2%    |
| Intel Core m5           | 6         | 0.17%   |
| AMD C-60                | 6         | 0.17%   |
| AMD C-50                | 6         | 0.17%   |
| AMD Athlon X2           | 6         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2148      | 62.51%  |
| 4      | 854       | 24.85%  |
| 1      | 196       | 5.7%    |
| 6      | 111       | 3.23%   |
| 8      | 86        | 2.5%    |
| 10     | 15        | 0.44%   |
| 14     | 11        | 0.32%   |
| 12     | 8         | 0.23%   |
| 16     | 3         | 0.09%   |
| 24     | 2         | 0.06%   |
| 3      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3433      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2058      | 59.95%  |
| 1      | 1375      | 40.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3310      | 96.39%  |
| 32-bit         | 122       | 3.55%   |
| Unknown        | 2         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 423       | 12.14%  |
| 0x206a7    | 282       | 8.09%   |
| 0x306a9    | 244       | 7%      |
| 0x1067a    | 175       | 5.02%   |
| 0x40651    | 145       | 4.16%   |
| 0x406e3    | 118       | 3.39%   |
| 0x20655    | 115       | 3.3%    |
| 0x306d4    | 107       | 3.07%   |
| 0x6fd      | 96        | 2.76%   |
| 0x30678    | 94        | 2.7%    |
| 0x306c3    | 89        | 2.55%   |
| 0x806e9    | 87        | 2.5%    |
| 0x806ea    | 75        | 2.15%   |
| 0x806c1    | 75        | 2.15%   |
| 0x406c4    | 69        | 1.98%   |
| 0x806ec    | 66        | 1.89%   |
| 0x10676    | 54        | 1.55%   |
| 0x706a8    | 50        | 1.44%   |
| 0x906ea    | 47        | 1.35%   |
| 0x506c9    | 45        | 1.29%   |
| 0x406c3    | 44        | 1.26%   |
| 0x20652    | 42        | 1.21%   |
| 0x706e5    | 41        | 1.18%   |
| 0x906e9    | 40        | 1.15%   |
| 0x106ca    | 36        | 1.03%   |
| 0x08108109 | 36        | 1.03%   |
| 0x06006705 | 36        | 1.03%   |
| 0x6e8      | 31        | 0.89%   |
| 0x6d8      | 31        | 0.89%   |
| 0x6f6      | 27        | 0.77%   |
| 0x07030105 | 27        | 0.77%   |
| 0x05000119 | 26        | 0.75%   |
| 0x0700010f | 25        | 0.72%   |
| 0x706a1    | 24        | 0.69%   |
| 0x106c2    | 24        | 0.69%   |
| 0x08108102 | 24        | 0.69%   |
| 0x06001119 | 24        | 0.69%   |
| 0x6fb      | 23        | 0.66%   |
| 0x0a50000c | 23        | 0.66%   |
| 0xa0652    | 21        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 385       | 11.21%  |
| SandyBridge      | 299       | 8.71%   |
| IvyBridge        | 265       | 7.72%   |
| Haswell          | 263       | 7.66%   |
| Penryn           | 253       | 7.37%   |
| Silvermont       | 239       | 6.96%   |
| Core             | 196       | 5.71%   |
| Westmere         | 171       | 4.98%   |
| Skylake          | 156       | 4.54%   |
| Broadwell        | 117       | 3.41%   |
| TigerLake        | 92        | 2.68%   |
| P6               | 87        | 2.53%   |
| Goldmont plus    | 87        | 2.53%   |
| Excavator        | 71        | 2.07%   |
| Bonnell          | 71        | 2.07%   |
| Zen+             | 68        | 1.98%   |
| Unknown          | 65        | 1.89%   |
| IceLake          | 54        | 1.57%   |
| Goldmont         | 49        | 1.43%   |
| K8 Hammer        | 48        | 1.4%    |
| Zen 3            | 45        | 1.31%   |
| Puma             | 44        | 1.28%   |
| Zen 2            | 42        | 1.22%   |
| Bobcat           | 40        | 1.17%   |
| Jaguar           | 32        | 0.93%   |
| Piledriver       | 30        | 0.87%   |
| CometLake        | 28        | 0.82%   |
| K10              | 26        | 0.76%   |
| Alderlake Hybrid | 24        | 0.7%    |
| K10 Llano        | 20        | 0.58%   |
| K8 & K10 hybrid  | 19        | 0.55%   |
| Zen              | 16        | 0.47%   |
| Nehalem          | 12        | 0.35%   |
| Steamroller      | 8         | 0.23%   |
| Tremont          | 7         | 0.2%    |
| NetBurst         | 4         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2529      | 62.32%  |
| AMD                              | 764       | 18.83%  |
| Nvidia                           | 725       | 17.87%  |
| Silicon Integrated Systems [SiS] | 28        | 0.69%   |
| VIA Technologies                 | 12        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 267       | 6.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 252       | 5.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 154       | 3.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 152       | 3.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 130       | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 120       | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 119       | 2.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 118       | 2.75%   |
| Intel HD Graphics 620                                                                    | 95        | 2.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 92        | 2.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 86        | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 86        | 2%      |
| Intel HD Graphics 5500                                                                   | 83        | 1.93%   |
| Intel UHD Graphics 620                                                                   | 79        | 1.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 79        | 1.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 78        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 72        | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 70        | 1.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 54        | 1.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 54        | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 50        | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 1.14%   |
| Intel HD Graphics 500                                                                    | 41        | 0.96%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 41        | 0.96%   |
| Intel HD Graphics 630                                                                    | 38        | 0.89%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 35        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 34        | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 32        | 0.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 32        | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 31        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 30        | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 29        | 0.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28        | 0.65%   |
| AMD Lucienne                                                                             | 27        | 0.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 25        | 0.58%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 24        | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1948      | 56.64%  |
| 1 x AMD        | 525       | 15.27%  |
| Intel + Nvidia | 440       | 12.79%  |
| 1 x Nvidia     | 229       | 6.66%   |
| Intel + AMD    | 133       | 3.87%   |
| 2 x AMD        | 58        | 1.69%   |
| AMD + Nvidia   | 49        | 1.42%   |
| 1 x SiS        | 28        | 0.81%   |
| 1 x VIA        | 12        | 0.35%   |
| Other          | 9         | 0.26%   |
| 2 x Nvidia     | 8         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2984      | 86.52%  |
| Proprietary | 353       | 10.23%  |
| Unknown     | 112       | 3.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2345      | 67.42%  |
| 0.01-0.5   | 516       | 14.84%  |
| 1.01-2.0   | 276       | 7.94%   |
| 0.51-1.0   | 198       | 5.69%   |
| 3.01-4.0   | 91        | 2.62%   |
| 5.01-6.0   | 21        | 0.6%    |
| 7.01-8.0   | 17        | 0.49%   |
| 2.01-3.0   | 12        | 0.35%   |
| 8.01-16.0  | 2         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 684       | 19.59%  |
| LG Display              | 495       | 14.18%  |
| Samsung Electronics     | 459       | 13.15%  |
| Chimei Innolux          | 448       | 12.83%  |
| BOE                     | 436       | 12.49%  |
| Chi Mei Optoelectronics | 126       | 3.61%   |
| Apple                   | 106       | 3.04%   |
| LG Philips              | 80        | 2.29%   |
| Lenovo                  | 60        | 1.72%   |
| Sharp                   | 55        | 1.58%   |
| Goldstar                | 51        | 1.46%   |
| Dell                    | 47        | 1.35%   |
| InfoVision              | 41        | 1.17%   |
| PANDA                   | 36        | 1.03%   |
| Hewlett-Packard         | 24        | 0.69%   |
| CPT                     | 23        | 0.66%   |
| HannStar                | 18        | 0.52%   |
| Toshiba                 | 17        | 0.49%   |
| Acer                    | 16        | 0.46%   |
| Sony                    | 15        | 0.43%   |
| Philips                 | 13        | 0.37%   |
| BenQ                    | 13        | 0.37%   |
| Quanta Display          | 11        | 0.32%   |
| LGD                     | 11        | 0.32%   |
| AOC                     | 11        | 0.32%   |
| Vizio                   | 10        | 0.29%   |
| InnoLux Display         | 10        | 0.29%   |
| Seiko/Epson             | 9         | 0.26%   |
| Panasonic               | 9         | 0.26%   |
| Ancor Communications    | 9         | 0.26%   |
| Eizo                    | 7         | 0.2%    |
| ASUSTek Computer        | 7         | 0.2%    |
| SLD                     | 6         | 0.17%   |
| CSO                     | 6         | 0.17%   |
| ViewSonic               | 5         | 0.14%   |
| TMX                     | 5         | 0.14%   |
| Iiyama                  | 5         | 0.14%   |
| BOE Technology Group    | 5         | 0.14%   |
| Unknown                 | 5         | 0.14%   |
| Unknown                 | 4         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 38        | 1.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 27        | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 26        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 22        | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 19        | 0.54%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 19        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.48%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 17        | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 15        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 14        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 14        | 0.4%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 13        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 11        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.31%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 10        | 0.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.28%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 0.28%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.28%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 10        | 0.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.26%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 9         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.26%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1395      | 40.98%  |
| 1920x1080 (FHD)    | 1004      | 29.49%  |
| 1280x800 (WXGA)    | 253       | 7.43%   |
| 1600x900 (HD+)     | 220       | 6.46%   |
| 1440x900 (WXGA+)   | 94        | 2.76%   |
| 3840x2160 (4K)     | 68        | 2%      |
| 1024x600           | 49        | 1.44%   |
| 1920x1200 (WUXGA)  | 40        | 1.18%   |
| 2560x1600          | 34        | 1%      |
| 1680x1050 (WSXGA+) | 33        | 0.97%   |
| 2560x1440 (QHD)    | 30        | 0.88%   |
| 2880x1800          | 17        | 0.5%    |
| 1360x768           | 15        | 0.44%   |
| 1280x1024 (SXGA)   | 15        | 0.44%   |
| 2560x1080          | 13        | 0.38%   |
| 2160x1440          | 11        | 0.32%   |
| 3200x1800 (QHD+)   | 10        | 0.29%   |
| 1024x768 (XGA)     | 10        | 0.29%   |
| Unknown            | 10        | 0.29%   |
| 2256x1504          | 8         | 0.24%   |
| 1280x768           | 8         | 0.24%   |
| 1920x540           | 7         | 0.21%   |
| 3840x2400          | 6         | 0.18%   |
| 3840x1080          | 5         | 0.15%   |
| 3440x1440          | 5         | 0.15%   |
| 1680x945           | 4         | 0.12%   |
| 1400x1050          | 4         | 0.12%   |
| 1920x515           | 3         | 0.09%   |
| 1024x576           | 3         | 0.09%   |
| 5760x1080          | 2         | 0.06%   |
| 3600x1080          | 2         | 0.06%   |
| 3072x1920          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2520x1680          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2288x1287          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1517      | 43.52%  |
| 13      | 485       | 13.91%  |
| 14      | 414       | 11.88%  |
| 17      | 290       | 8.32%   |
| 11      | 128       | 3.67%   |
| 12      | 94        | 2.7%    |
| Unknown | 75        | 2.15%   |
| 10      | 61        | 1.75%   |
| 24      | 57        | 1.64%   |
| 27      | 53        | 1.52%   |
| 16      | 39        | 1.12%   |
| 23      | 37        | 1.06%   |
| 21      | 35        | 1%      |
| 18      | 33        | 0.95%   |
| 31      | 23        | 0.66%   |
| 34      | 21        | 0.6%    |
| 19      | 16        | 0.46%   |
| 20      | 12        | 0.34%   |
| 54      | 11        | 0.32%   |
| 22      | 11        | 0.32%   |
| 72      | 10        | 0.29%   |
| 40      | 8         | 0.23%   |
| 84      | 7         | 0.2%    |
| 8       | 5         | 0.14%   |
| 32      | 4         | 0.11%   |
| 25      | 4         | 0.11%   |
| 74      | 3         | 0.09%   |
| 52      | 3         | 0.09%   |
| 49      | 3         | 0.09%   |
| 48      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 58      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 37      | 2         | 0.06%   |
| 36      | 2         | 0.06%   |
| 29      | 2         | 0.06%   |
| 86      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 63      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2171      | 62.49%  |
| 201-300     | 494       | 14.22%  |
| 351-400     | 358       | 10.31%  |
| 501-600     | 145       | 4.17%   |
| 401-500     | 104       | 2.99%   |
| Unknown     | 75        | 2.16%   |
| 601-700     | 30        | 0.86%   |
| 1001-1500   | 30        | 0.86%   |
| 701-800     | 28        | 0.81%   |
| 1501-2000   | 20        | 0.58%   |
| 801-900     | 11        | 0.32%   |
| 101-200     | 5         | 0.14%   |
| 901-1000    | 3         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2619      | 81.03%  |
| 16/10   | 466       | 14.42%  |
| Unknown | 56        | 1.73%   |
| 3/2     | 30        | 0.93%   |
| 4/3     | 19        | 0.59%   |
| 21/9    | 19        | 0.59%   |
| 5/4     | 14        | 0.43%   |
| 32/9    | 3         | 0.09%   |
| 3.73    | 3         | 0.09%   |
| 0.62    | 2         | 0.06%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1517      | 43.58%  |
| 81-90          | 748       | 21.49%  |
| 121-130        | 219       | 6.29%   |
| 71-80          | 144       | 4.14%   |
| 51-60          | 128       | 3.68%   |
| 201-250        | 116       | 3.33%   |
| 61-70          | 92        | 2.64%   |
| Unknown        | 75        | 2.15%   |
| 131-140        | 65        | 1.87%   |
| 41-50          | 61        | 1.75%   |
| 301-350        | 55        | 1.58%   |
| 351-500        | 49        | 1.41%   |
| More than 1000 | 47        | 1.35%   |
| 151-200        | 42        | 1.21%   |
| 141-150        | 42        | 1.21%   |
| 111-120        | 25        | 0.72%   |
| 501-1000       | 21        | 0.6%    |
| 91-100         | 16        | 0.46%   |
| 251-300        | 14        | 0.4%    |
| 1-40           | 5         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1459      | 42.47%  |
| 121-160       | 1061      | 30.89%  |
| 51-100        | 567       | 16.51%  |
| 161-240       | 172       | 5.01%   |
| Unknown       | 75        | 2.18%   |
| More than 240 | 52        | 1.51%   |
| 1-50          | 49        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2982      | 85.4%   |
| 2     | 363       | 10.4%   |
| 0     | 121       | 3.47%   |
| 3     | 23        | 0.66%   |
| 4     | 2         | 0.06%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1737      | 31.22%  |
| Intel                             | 1484      | 26.67%  |
| Qualcomm Atheros                  | 908       | 16.32%  |
| Broadcom                          | 536       | 9.63%   |
| Broadcom Limited                  | 171       | 3.07%   |
| Marvell Technology Group          | 103       | 1.85%   |
| Ralink                            | 68        | 1.22%   |
| Nvidia                            | 48        | 0.86%   |
| MediaTek                          | 48        | 0.86%   |
| TP-Link                           | 42        | 0.75%   |
| Samsung Electronics               | 30        | 0.54%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.52%   |
| Dell                              | 29        | 0.52%   |
| ASIX Electronics                  | 29        | 0.52%   |
| Ralink Technology                 | 27        | 0.49%   |
| JMicron Technology                | 27        | 0.49%   |
| Sierra Wireless                   | 22        | 0.4%    |
| DisplayLink                       | 18        | 0.32%   |
| Hewlett-Packard                   | 17        | 0.31%   |
| Xiaomi                            | 16        | 0.29%   |
| Huawei Technologies               | 12        | 0.22%   |
| VIA Technologies                  | 11        | 0.2%    |
| Qualcomm Atheros Communications   | 11        | 0.2%    |
| Ericsson Business Mobile Networks | 11        | 0.2%    |
| OPPO Electronics                  | 10        | 0.18%   |
| NetGear                           | 9         | 0.16%   |
| Edimax Technology                 | 9         | 0.16%   |
| ASUSTek Computer                  | 9         | 0.16%   |
| AMD                               | 8         | 0.14%   |
| Qualcomm                          | 7         | 0.13%   |
| Motorola PCS                      | 7         | 0.13%   |
| Attansic Technology               | 6         | 0.11%   |
| D-Link                            | 5         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| Linksys                           | 4         | 0.07%   |
| Google                            | 4         | 0.07%   |
| D-Link System                     | 4         | 0.07%   |
| T & A Mobile Phones               | 3         | 0.05%   |
| Belkin Components                 | 3         | 0.05%   |
| ZyDAS                             | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 874       | 13.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 465       | 7.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 160       | 2.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 149       | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 136       | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 129       | 1.95%   |
| Intel Wireless 7260                                                     | 129       | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 123       | 1.86%   |
| Intel Wireless 7265                                                     | 97        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 88        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 86        | 1.3%    |
| Intel Wireless 8265 / 8275                                              | 85        | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 84        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 74        | 1.12%   |
| Intel Wireless 8260                                                     | 69        | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 69        | 1.04%   |
| Intel Wireless 3165                                                     | 67        | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 65        | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 62        | 0.94%   |
| Intel Wi-Fi 6 AX200                                                     | 62        | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 59        | 0.89%   |
| Intel WiFi Link 5100                                                    | 59        | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 57        | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 55        | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 54        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 46        | 0.69%   |
| Intel Wireless 3160                                                     | 41        | 0.62%   |
| Intel Ethernet Connection I218-LM                                       | 41        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                          | 40        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 39        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 0.59%   |
| Intel Ethernet Connection I217-LM                                       | 39        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 38        | 0.57%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 38        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 37        | 0.56%   |
| Intel Ethernet Connection I219-LM                                       | 36        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                                | 36        | 0.54%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 36        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1390      | 38.94%  |
| Qualcomm Atheros                  | 768       | 21.51%  |
| Realtek Semiconductor             | 601       | 16.83%  |
| Broadcom                          | 414       | 11.6%   |
| Broadcom Limited                  | 118       | 3.31%   |
| Ralink                            | 68        | 1.9%    |
| MediaTek                          | 39        | 1.09%   |
| TP-Link                           | 33        | 0.92%   |
| Ralink Technology                 | 27        | 0.76%   |
| Sierra Wireless                   | 22        | 0.62%   |
| Dell                              | 16        | 0.45%   |
| Qualcomm Atheros Communications   | 11        | 0.31%   |
| NetGear                           | 9         | 0.25%   |
| Edimax Technology                 | 9         | 0.25%   |
| ASUSTek Computer                  | 8         | 0.22%   |
| D-Link                            | 5         | 0.14%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| D-Link System                     | 4         | 0.11%   |
| Linksys                           | 3         | 0.08%   |
| Belkin Components                 | 3         | 0.08%   |
| ZyDAS                             | 2         | 0.06%   |
| Micro Star International          | 2         | 0.06%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Xiaomi                            | 1         | 0.03%   |
| TRENDnet                          | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Qualcomm                          | 1         | 0.03%   |
| Qcom                              | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| Mercucys                          | 1         | 0.03%   |
| Lite-On Technology                | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| Fibocom                           | 1         | 0.03%   |
| Ericsson Business Mobile Networks | 1         | 0.03%   |
| Askey Computer                    | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 160       | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 149       | 4.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 129       | 3.58%   |
| Intel Wireless 7260                                                     | 129       | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 123       | 3.41%   |
| Intel Wireless 7265                                                     | 97        | 2.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 88        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 86        | 2.39%   |
| Intel Wireless 8265 / 8275                                              | 85        | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 84        | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 74        | 2.05%   |
| Intel Wireless 8260                                                     | 69        | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 69        | 1.92%   |
| Intel Wireless 3165                                                     | 67        | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 65        | 1.8%    |
| Intel Wi-Fi 6 AX201                                                     | 62        | 1.72%   |
| Intel Wi-Fi 6 AX200                                                     | 62        | 1.72%   |
| Intel WiFi Link 5100                                                    | 59        | 1.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 57        | 1.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 55        | 1.53%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 54        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 46        | 1.28%   |
| Intel Wireless 3160                                                     | 41        | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 40        | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 1.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 38        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 37        | 1.03%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 36        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 35        | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 32        | 0.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 30        | 0.83%   |
| Intel Centrino Advanced-N 6200                                          | 29        | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 28        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 27        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 27        | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 27        | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 27        | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 26        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1472      | 50.55%  |
| Intel                                  | 565       | 19.4%   |
| Qualcomm Atheros                       | 239       | 8.21%   |
| Broadcom                               | 189       | 6.49%   |
| Marvell Technology Group               | 103       | 3.54%   |
| Broadcom Limited                       | 58        | 1.99%   |
| Nvidia                                 | 48        | 1.65%   |
| Samsung Electronics                    | 30        | 1.03%   |
| ASIX Electronics                       | 29        | 1%      |
| Silicon Integrated Systems [SiS]       | 27        | 0.93%   |
| JMicron Technology                     | 27        | 0.93%   |
| DisplayLink                            | 18        | 0.62%   |
| Xiaomi                                 | 15        | 0.52%   |
| VIA Technologies                       | 11        | 0.38%   |
| OPPO Electronics                       | 10        | 0.34%   |
| TP-Link                                | 9         | 0.31%   |
| Huawei Technologies                    | 9         | 0.31%   |
| MediaTek                               | 8         | 0.27%   |
| Qualcomm                               | 6         | 0.21%   |
| Motorola PCS                           | 6         | 0.21%   |
| Attansic Technology                    | 6         | 0.21%   |
| Hewlett-Packard                        | 4         | 0.14%   |
| Google                                 | 4         | 0.14%   |
| T & A Mobile Phones                    | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.07%   |
| Lenovo                                 | 2         | 0.07%   |
| Davicom Semiconductor                  | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Novatel Wireless                       | 1         | 0.03%   |
| Motorola BCS                           | 1         | 0.03%   |
| Linksys                                | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |
| HTC (High Tech Computer)               | 1         | 0.03%   |
| HMD Global                             | 1         | 0.03%   |
| GoPro                                  | 1         | 0.03%   |
| ASUSTek Computer                       | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 874       | 29.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 465       | 15.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 136       | 4.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 59        | 2.02%   |
| Intel Ethernet Connection I218-LM                                      | 41        | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 39        | 1.33%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 38        | 1.3%    |
| Intel Ethernet Connection I219-LM                                      | 36        | 1.23%   |
| Intel 82577LM Gigabit Network Connection                               | 36        | 1.23%   |
| Intel 82567LM Gigabit Network Connection                               | 34        | 1.16%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 31        | 1.06%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 30        | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 27        | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 26        | 0.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 24        | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 24        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                                  | 23        | 0.79%   |
| Intel 82566MM Gigabit Network Connection                               | 23        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 23        | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 21        | 0.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 21        | 0.72%   |
| Intel Ethernet Connection I219-V                                       | 21        | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 21        | 0.72%   |
| Nvidia MCP79 Ethernet                                                  | 20        | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 19        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 19        | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 18        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 17        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 17        | 0.58%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 17        | 0.58%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 17        | 0.58%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 17        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 15        | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 15        | 0.51%   |
| Nvidia MCP67 Ethernet                                                  | 14        | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 14        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 14        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 13        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3331      | 53.45%  |
| Ethernet | 2804      | 44.99%  |
| Modem    | 91        | 1.46%   |
| Unknown  | 6         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2804      | 79.03%  |
| Ethernet | 743       | 20.94%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2581      | 75.09%  |
| 1     | 711       | 20.69%  |
| 0     | 129       | 3.75%   |
| 3     | 15        | 0.44%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2651      | 76.07%  |
| Yes  | 834       | 23.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 900       | 38.78%  |
| Qualcomm Atheros Communications | 271       | 11.68%  |
| Realtek Semiconductor           | 266       | 11.46%  |
| Broadcom                        | 168       | 7.24%   |
| IMC Networks                    | 105       | 4.52%   |
| Apple                           | 92        | 3.96%   |
| Foxconn / Hon Hai               | 82        | 3.53%   |
| Lite-On Technology              | 81        | 3.49%   |
| Dell                            | 75        | 3.23%   |
| Hewlett-Packard                 | 71        | 3.06%   |
| Toshiba                         | 50        | 2.15%   |
| Cambridge Silicon Radio         | 33        | 1.42%   |
| Ralink                          | 26        | 1.12%   |
| ASUSTek Computer                | 19        | 0.82%   |
| Realtek                         | 17        | 0.73%   |
| Alps Electric                   | 16        | 0.69%   |
| Foxconn International           | 13        | 0.56%   |
| Ralink Technology               | 7         | 0.3%    |
| Askey Computer                  | 7         | 0.3%    |
| Taiyo Yuden                     | 4         | 0.17%   |
| MediaTek                        | 3         | 0.13%   |
| Dynex                           | 3         | 0.13%   |
| Chicony Electronics             | 3         | 0.13%   |
| Qcom                            | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Unknown                         | 2         | 0.09%   |
| TP-Link                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 466       | 20.05%  |
| Realtek Bluetooth Radio                             | 175       | 7.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 120       | 5.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 119       | 5.12%   |
| Intel AX201 Bluetooth                               | 111       | 4.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 74        | 3.18%   |
| Intel AX200 Bluetooth                               | 60        | 2.58%   |
| Apple Bluetooth Host Controller                     | 54        | 2.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 49        | 2.11%   |
| Intel Bluetooth Device                              | 45        | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 1.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 42        | 1.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 38        | 1.64%   |
| IMC Networks Bluetooth Device                       | 38        | 1.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33        | 1.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 30        | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.2%    |
| Ralink RT3290 Bluetooth                             | 26        | 1.12%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 25        | 1.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.99%   |
| IMC Networks Wireless_Device                        | 22        | 0.95%   |
| IMC Networks Bluetooth Radio                        | 22        | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 22        | 0.95%   |
| Intel AX210 Bluetooth                               | 21        | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 21        | 0.9%    |
| Dell DW375 Bluetooth Module                         | 21        | 0.9%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 20        | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 18        | 0.77%   |
| Realtek Bluetooth Radio                             | 17        | 0.73%   |
| Toshiba Bluetooth Device                            | 15        | 0.65%   |
| Dell Wireless 365 Bluetooth                         | 14        | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 14        | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module   | 13        | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.52%   |
| Apple Bluetooth HCI                                 | 12        | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2715      | 69.87%  |
| AMD                                  | 614       | 15.8%   |
| Nvidia                               | 404       | 10.4%   |
| Silicon Integrated Systems [SiS]     | 31        | 0.8%    |
| C-Media Electronics                  | 14        | 0.36%   |
| VIA Technologies                     | 12        | 0.31%   |
| Generalplus Technology               | 8         | 0.21%   |
| Tenx Technology                      | 6         | 0.15%   |
| Texas Instruments                    | 5         | 0.13%   |
| Realtek Semiconductor                | 5         | 0.13%   |
| JMTek                                | 5         | 0.13%   |
| Creative Technology                  | 5         | 0.13%   |
| SteelSeries ApS                      | 4         | 0.1%    |
| Plantronics                          | 4         | 0.1%    |
| Logitech                             | 4         | 0.1%    |
| Lenovo                               | 4         | 0.1%    |
| PreSonus Audio Electronics           | 3         | 0.08%   |
| Hewlett-Packard                      | 3         | 0.08%   |
| GN Netcom                            | 3         | 0.08%   |
| Apple                                | 3         | 0.08%   |
| Yamaha                               | 2         | 0.05%   |
| Sony                                 | 2         | 0.05%   |
| KTMicro                              | 2         | 0.05%   |
| Focusrite-Novation                   | 2         | 0.05%   |
| Corsair                              | 2         | 0.05%   |
| ASUSTek Computer                     | 2         | 0.05%   |
| AKAI Professional M.I.               | 2         | 0.05%   |
| ZOOM                                 | 1         | 0.03%   |
| XMOS                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| OPPO Electronics                     | 1         | 0.03%   |
| M-Audio                              | 1         | 0.03%   |
| Kingston Technology                  | 1         | 0.03%   |
| Huawei Technologies                  | 1         | 0.03%   |
| FiiO Electronics Technology          | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 325       | 6.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 319       | 6.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 244       | 5.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 219       | 4.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 206       | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 183       | 3.89%   |
| Intel 8 Series HD Audio Controller                                                                | 156       | 3.32%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 152       | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 148       | 3.15%   |
| AMD FCH Azalia Controller                                                                         | 145       | 3.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 136       | 2.89%   |
| Intel Broadwell-U Audio Controller                                                                | 117       | 2.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 116       | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 107       | 2.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 93        | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 92        | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 92        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 88        | 1.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 87        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 82        | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 78        | 1.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 77        | 1.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 69        | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 58        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 56        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 54        | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 54        | 1.15%   |
| AMD High Definition Audio Controller                                                              | 54        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 49        | 1.04%   |
| Intel CM238 HD Audio Controller                                                                   | 44        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 41        | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 41        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 33        | 0.7%    |
| AMD Wrestler HDMI Audio                                                                           | 33        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 30        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 30        | 0.64%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 26        | 0.55%   |
| Nvidia High Definition Audio Controller                                                           | 26        | 0.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 26        | 0.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 213       | 25.57%  |
| SK hynix               | 189       | 22.69%  |
| Micron Technology      | 99        | 11.88%  |
| Unknown                | 80        | 9.6%    |
| Kingston               | 63        | 7.56%   |
| Crucial                | 25        | 3%      |
| Unknown (ABCD)         | 24        | 2.88%   |
| Elpida                 | 17        | 2.04%   |
| Ramaxel Technology     | 16        | 1.92%   |
| Nanya Technology       | 15        | 1.8%    |
| A-DATA Technology      | 15        | 1.8%    |
| Smart                  | 10        | 1.2%    |
| Corsair                | 5         | 0.6%    |
| Qimonda                | 4         | 0.48%   |
| G.Skill                | 4         | 0.48%   |
| Transcend              | 3         | 0.36%   |
| Timetec                | 3         | 0.36%   |
| Teikon                 | 3         | 0.36%   |
| Team                   | 3         | 0.36%   |
| Smart Brazil           | 3         | 0.36%   |
| Unknown                | 3         | 0.36%   |
| SHARETRONIC            | 2         | 0.24%   |
| Patriot                | 2         | 0.24%   |
| High Bridge            | 2         | 0.24%   |
| ff                     | 2         | 0.24%   |
| fef5                   | 2         | 0.24%   |
| 4ea5                   | 2         | 0.24%   |
| Walton Chaintech       | 1         | 0.12%   |
| Unknown (08B5)         | 1         | 0.12%   |
| Unknown (07F7)         | 1         | 0.12%   |
| Unknown (000080B30080) | 1         | 0.12%   |
| Toshiba                | 1         | 0.12%   |
| Strontium              | 1         | 0.12%   |
| Silicon Power          | 1         | 0.12%   |
| PUSKILL                | 1         | 0.12%   |
| ProMos/Mosel Vitelic   | 1         | 0.12%   |
| pqi                    | 1         | 0.12%   |
| PNY                    | 1         | 0.12%   |
| Netlist                | 1         | 0.12%   |
| Nayna                  | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 21        | 2.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 13        | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 12        | 1.36%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 11        | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 10        | 1.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 9         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 8         | 0.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 7         | 0.79%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 6         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 6         | 0.68%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 5         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 5         | 0.57%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 5         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 5         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 5         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 5         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 4         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 4         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 4         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 4         | 0.45%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR 975MT/s                | 4         | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.45%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.45%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 267       | 37.93%  |
| DDR4    | 245       | 34.8%   |
| DDR2    | 74        | 10.51%  |
| LPDDR4  | 44        | 6.25%   |
| SDRAM   | 24        | 3.41%   |
| LPDDR3  | 22        | 3.13%   |
| DRAM    | 6         | 0.85%   |
| DDR     | 6         | 0.85%   |
| Unknown | 6         | 0.85%   |
| LPDDR5  | 5         | 0.71%   |
| DDR5    | 5         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 609       | 86.88%  |
| Row Of Chips | 60        | 8.56%   |
| DIMM         | 14        | 2%      |
| Chip         | 10        | 1.43%   |
| Unknown      | 8         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 255       | 32.28%  |
| 4096  | 239       | 30.25%  |
| 2048  | 155       | 19.62%  |
| 16384 | 64        | 8.1%    |
| 1024  | 54        | 6.84%   |
| 512   | 12        | 1.52%   |
| 32768 | 9         | 1.14%   |
| 256   | 2         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 181       | 23.69%  |
| 2667    | 115       | 15.05%  |
| 3200    | 98        | 12.83%  |
| 2400    | 65        | 8.51%   |
| 1334    | 40        | 5.24%   |
| 667     | 38        | 4.97%   |
| 2133    | 31        | 4.06%   |
| 1333    | 31        | 4.06%   |
| Unknown | 31        | 4.06%   |
| 1066    | 16        | 2.09%   |
| 800     | 15        | 1.96%   |
| 4267    | 11        | 1.44%   |
| 975     | 11        | 1.44%   |
| 4199    | 10        | 1.31%   |
| 3266    | 10        | 1.31%   |
| 2048    | 10        | 1.31%   |
| 533     | 10        | 1.31%   |
| 1867    | 8         | 1.05%   |
| 1067    | 8         | 1.05%   |
| 6400    | 6         | 0.79%   |
| 8400    | 4         | 0.52%   |
| 4800    | 4         | 0.52%   |
| 400     | 3         | 0.39%   |
| 5600    | 2         | 0.26%   |
| 3733    | 2         | 0.26%   |
| 4266    | 1         | 0.13%   |
| 2933    | 1         | 0.13%   |
| 1866    | 1         | 0.13%   |
| 1639    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 40%     |
| Seiko Epson           | 6         | 17.14%  |
| Canon                 | 6         | 17.14%  |
| Brother Industries    | 3         | 8.57%   |
| Samsung Electronics   | 2         | 5.71%   |
| Zebra                 | 1         | 2.86%   |
| STMicroelectronics    | 1         | 2.86%   |
| Lexmark International | 1         | 2.86%   |
| Dymo-CoStar           | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 2         | 5.71%   |
| HP ENVY Photo 6200 series                                 | 2         | 5.71%   |
| HP Deskjet 1510                                           | 2         | 5.71%   |
| HP DeskJet 1110 series                                    | 2         | 5.71%   |
| Zebra ZP 450 Printer                                      | 1         | 2.86%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.86%   |
| Seiko Epson XP-235 Series                                 | 1         | 2.86%   |
| Seiko Epson WF-2010 Series                                | 1         | 2.86%   |
| Seiko Epson Printer                                       | 1         | 2.86%   |
| Seiko Epson L3250 Series                                  | 1         | 2.86%   |
| Seiko Epson L3110 Series                                  | 1         | 2.86%   |
| Seiko Epson AcuLaser C1700                                | 1         | 2.86%   |
| Samsung M2020 Series                                      | 1         | 2.86%   |
| Samsung CLX-3300 Series                                   | 1         | 2.86%   |
| Lexmark International 2400 series                         | 1         | 2.86%   |
| HP Laserjet P1505                                         | 1         | 2.86%   |
| HP LaserJet P1102                                         | 1         | 2.86%   |
| HP LaserJet 1200                                          | 1         | 2.86%   |
| HP LaserJet 1000                                          | 1         | 2.86%   |
| HP DeskJet 2700 series                                    | 1         | 2.86%   |
| HP DeskJet 2300 series                                    | 1         | 2.86%   |
| Dymo-CoStar LabelWriter 450                               | 1         | 2.86%   |
| Canon TS3100 series                                       | 1         | 2.86%   |
| Canon PIXMA MX490 Series                                  | 1         | 2.86%   |
| Canon PIXMA MX340                                         | 1         | 2.86%   |
| Canon PIXMA MG3600 Series                                 | 1         | 2.86%   |
| Canon PIXMA MG3000 series                                 | 1         | 2.86%   |
| Canon MG2100 series                                       | 1         | 2.86%   |
| Brother MFC-L2730DW series                                | 1         | 2.86%   |
| Brother MFC-J5730DW                                       | 1         | 2.86%   |
| Brother DCP-T300                                          | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 50%     |
| Canon       | 3         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 16.67%  |
| Canon CanoScan LIDE 25                      | 1         | 16.67%  |
| Canon CanoScan LiDE 200                     | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 700       | 24.85%  |
| Microdia                               | 263       | 9.34%   |
| Realtek Semiconductor                  | 234       | 8.31%   |
| IMC Networks                           | 221       | 7.85%   |
| Sunplus Innovation Technology          | 158       | 5.61%   |
| Bison Electronics                      | 149       | 5.29%   |
| Suyin                                  | 140       | 4.97%   |
| Cheng Uei Precision Industry (Foxlink) | 130       | 4.61%   |
| Quanta                                 | 126       | 4.47%   |
| Apple                                  | 82        | 2.91%   |
| Syntek                                 | 74        | 2.63%   |
| Silicon Motion                         | 60        | 2.13%   |
| Lite-On Technology                     | 60        | 2.13%   |
| Acer                                   | 53        | 1.88%   |
| Alcor Micro                            | 51        | 1.81%   |
| Ricoh                                  | 38        | 1.35%   |
| Luxvisions Innotech Limited            | 28        | 0.99%   |
| Logitech                               | 21        | 0.75%   |
| ALi                                    | 20        | 0.71%   |
| Importek                               | 18        | 0.64%   |
| Sonix Technology                       | 16        | 0.57%   |
| Samsung Electronics                    | 16        | 0.57%   |
| USB Camera                             | 15        | 0.53%   |
| Primax Electronics                     | 15        | 0.53%   |
| Z-Star Microelectronics                | 13        | 0.46%   |
| Lenovo                                 | 12        | 0.43%   |
| OmniVision Technologies                | 11        | 0.39%   |
| SunplusIT                              | 10        | 0.35%   |
| GEMBIRD                                | 9         | 0.32%   |
| Y Media                                | 6         | 0.21%   |
| Genesys Logic                          | 6         | 0.21%   |
| Microsoft                              | 5         | 0.18%   |
| Sunplus Technology                     | 4         | 0.14%   |
| Intel                                  | 4         | 0.14%   |
| Generalplus Technology                 | 3         | 0.11%   |
| ARC International                      | 3         | 0.11%   |
| Unknown                                | 3         | 0.11%   |
| YGTek                                  | 2         | 0.07%   |
| Tripath Technology                     | 2         | 0.07%   |
| LG Electronics                         | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 98        | 3.47%   |
| Microdia Integrated_Webcam_HD                    | 57        | 2.02%   |
| IMC Networks USB2.0 HD UVC WebCam                | 53        | 1.88%   |
| Realtek Integrated_Webcam_HD                     | 50        | 1.77%   |
| Chicony HD WebCam                                | 44        | 1.56%   |
| Chicony HP Truevision HD                         | 39        | 1.38%   |
| Realtek USB Camera                               | 38        | 1.35%   |
| IMC Networks Integrated Camera                   | 37        | 1.31%   |
| Syntek Integrated Camera                         | 36        | 1.27%   |
| Microdia Integrated Webcam                       | 36        | 1.27%   |
| Bison Lenovo EasyCamera                          | 34        | 1.2%    |
| Sunplus Integrated_Webcam_HD                     | 33        | 1.17%   |
| Chicony TOSHIBA Web Camera - HD                  | 32        | 1.13%   |
| Bison Integrated Camera                          | 32        | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 29        | 1.03%   |
| Chicony USB 2.0 Camera                           | 29        | 1.03%   |
| Chicony HP TrueVision HD Camera                  | 27        | 0.96%   |
| Realtek Integrated Webcam                        | 24        | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 24        | 0.85%   |
| Chicony EasyCamera                               | 23        | 0.81%   |
| Chicony VGA Webcam                               | 22        | 0.78%   |
| Chicony Lenovo EasyCamera                        | 22        | 0.78%   |
| Alcor Micro USB 2.0 Camera                       | 22        | 0.78%   |
| Sunplus HD WebCam                                | 21        | 0.74%   |
| Lite-On HP HD Camera                             | 21        | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 21        | 0.74%   |
| Apple FaceTime HD Camera                         | 21        | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 20        | 0.71%   |
| Chicony HP Webcam                                | 20        | 0.71%   |
| Apple Built-in iSight                            | 20        | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                    | 19        | 0.67%   |
| Chicony HP HD Webcam                             | 19        | 0.67%   |
| Chicony HP HD Camera                             | 19        | 0.67%   |
| Chicony CNF9055 Toshiba Webcam                   | 19        | 0.67%   |
| Suyin HP Truevision HD                           | 18        | 0.64%   |
| Quanta HP Webcam                                 | 18        | 0.64%   |
| Quanta HD User Facing                            | 18        | 0.64%   |
| Realtek HP Truevision HD                         | 17        | 0.6%    |
| Microdia Sonix USB 2.0 Camera                    | 17        | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                     | 17        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 224       | 46.86%  |
| AuthenTec                          | 68        | 14.23%  |
| Shenzhen Goodix Technology         | 47        | 9.83%   |
| Synaptics                          | 45        | 9.41%   |
| Upek                               | 37        | 7.74%   |
| Elan Microelectronics              | 22        | 4.6%    |
| STMicroelectronics                 | 19        | 3.97%   |
| LighTuning Technology              | 9         | 1.88%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.84%   |
| Samsung Electronics                | 2         | 0.42%   |
| Focal-systems.Corp                 | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 10.46%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 7.32%   |
| Shenzhen Goodix  Fingerprint Device                                        | 35        | 7.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 26        | 5.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 4.81%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 23        | 4.81%   |
| Validity Sensors VFS491                                                    | 20        | 4.18%   |
| Validity Sensors Fingerprint scanner                                       | 19        | 3.97%   |
| STMicroelectronics Fingerprint Reader                                      | 19        | 3.97%   |
| AuthenTec AES2810                                                          | 18        | 3.77%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.51%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.3%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.3%    |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 2.3%    |
| Elan ELAN:Fingerprint                                                      | 10        | 2.09%   |
| AuthenTec AES1600                                                          | 10        | 2.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 1.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 1.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.67%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 1.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 1.05%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.05%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 1.05%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.84%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.84%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.84%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.84%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.84%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.63%   |
| Synaptics  WBDI                                                            | 3         | 0.63%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.42%   |
| Synaptics WBDI                                                             | 2         | 0.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 115       | 53.99%  |
| Alcor Micro                       | 37        | 17.37%  |
| O2 Micro                          | 30        | 14.08%  |
| Lenovo                            | 10        | 4.69%   |
| Upek                              | 9         | 4.23%   |
| SCM Microsystems                  | 3         | 1.41%   |
| Yubico.com                        | 2         | 0.94%   |
| VASCO Data Security International | 2         | 0.94%   |
| Realtek Semiconductor             | 2         | 0.94%   |
| OmniKey                           | 1         | 0.47%   |
| Gemalto (was Gemplus)             | 1         | 0.47%   |
| Fujitsu Siemens Computers         | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 50        | 23.36%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 16.82%  |
| Broadcom 5880                                                                | 31        | 14.49%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 12.62%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 11.68%  |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 4.21%   |
| Broadcom 58200                                                               | 6         | 2.8%    |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.34%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 1.4%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.93%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 0.93%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.93%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.93%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.47%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.47%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2220      | 63.68%  |
| 1     | 995       | 28.54%  |
| 2     | 239       | 6.86%   |
| 3     | 29        | 0.83%   |
| 4     | 2         | 0.06%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 471       | 31.09%  |
| Graphics card            | 319       | 21.06%  |
| Chipcard                 | 203       | 13.4%   |
| Net/wireless             | 187       | 12.34%  |
| Multimedia controller    | 121       | 7.99%   |
| Storage                  | 50        | 3.3%    |
| Modem                    | 38        | 2.51%   |
| Bluetooth                | 36        | 2.38%   |
| Communication controller | 17        | 1.12%   |
| Sound                    | 16        | 1.06%   |
| Camera                   | 16        | 1.06%   |
| Flash memory             | 13        | 0.86%   |
| Net/ethernet             | 10        | 0.66%   |
| Card reader              | 6         | 0.4%    |
| Network                  | 4         | 0.26%   |
| Storage/nvme             | 2         | 0.13%   |
| Storage/ide              | 2         | 0.13%   |
| Dvb card                 | 2         | 0.13%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |

