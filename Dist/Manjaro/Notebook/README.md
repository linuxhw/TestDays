Manjaro - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 5272

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Star Labs     | StarBook                    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| Dell          | XPS 13 9380                 | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| Dell          | Precision M6400             | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| Dell          | Vostro 15-3568              | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| realme        | CloudProXXXX                | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| HP            | 245 G8                      | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| Sony          | SVZ1311C5E                  | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| Sony          | SVF1521Q1EW                 | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Dell          | G5 5587                     | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Positivo      | Q464B                       | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Apple         | MacBookPro14,1              | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| HP            | Laptop 15-dy1xxx            | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| Dell          | Latitude 5590               | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| Google        | Delbin                      | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Dell          | Vostro 3500                 | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude E5470              | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| MSI           | GF63 Thin 9RCX              | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| Apple         | MacBookAir7,2               | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| HP            | Notebook                    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| Dell          | G3 3590                     | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Acer          | Aspire A515-51              | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| Dell          | Latitude 7490               | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| MSI           | GE60 2QE                    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Precision 3571              | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| HP            | 15 Notebook PC              | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| Timi          | A34S                        | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Acer          | Aspire A315-56              | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| HP            | Compaq 6530b                | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| realme        | CloudProXXXX                | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Toshiba       | Satellite C50-C             | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| HP            | Pavilion 15                 | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [9f06213ef6](https://linux-hardware.org/?probe=9f06213ef6) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [5b71b83435](https://linux-hardware.org/?probe=5b71b83435) | Jan 12, 2023 |
| Notebook      | L14xMU                      | [48b282b529](https://linux-hardware.org/?probe=48b282b529) | Jan 12, 2023 |
| Apple         | MacBookPro11,3              | [ede9b6da76](https://linux-hardware.org/?probe=ede9b6da76) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [5be6eaa40c](https://linux-hardware.org/?probe=5be6eaa40c) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| ASUSTek       | UX31A                       | [c618ab31a8](https://linux-hardware.org/?probe=c618ab31a8) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| ASUSTek       | UX31A                       | [2eaea530ea](https://linux-hardware.org/?probe=2eaea530ea) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| MSI           | GS63 Stealth 8RE            | [8682a08d74](https://linux-hardware.org/?probe=8682a08d74) | Jan 09, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [5feb203761](https://linux-hardware.org/?probe=5feb203761) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [da175172b3](https://linux-hardware.org/?probe=da175172b3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| IPASON        | MaxBook P1X                 | [b7d1ce416f](https://linux-hardware.org/?probe=b7d1ce416f) | Jan 07, 2023 |
| Sony          | SVS1512U1RW                 | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c298dd423d](https://linux-hardware.org/?probe=c298dd423d) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| HP            | Laptop 14-dk0xxx            | [47654afbbc](https://linux-hardware.org/?probe=47654afbbc) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [c8d9352d43](https://linux-hardware.org/?probe=c8d9352d43) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [ddadb5f34d](https://linux-hardware.org/?probe=ddadb5f34d) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Dell          | XPS 15 9570                 | [c5d2fc381a](https://linux-hardware.org/?probe=c5d2fc381a) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| HP            | ZBook 15 G5                 | [04364cac9a](https://linux-hardware.org/?probe=04364cac9a) | Jan 02, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| Unknown       | Unknown                     | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| HP            | EliteBook 845 14 inch G9... | [5b5e58e433](https://linux-hardware.org/?probe=5b5e58e433) | Dec 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c2a949b725](https://linux-hardware.org/?probe=c2a949b725) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| HP            | Laptop 15-bs0xx             | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Dell          | Precision M6600             | [00840d085c](https://linux-hardware.org/?probe=00840d085c) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | [94e5bdb2cb](https://linux-hardware.org/?probe=94e5bdb2cb) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| HP            | ENVY Laptop 16-h0xxx        | [4e38f93dd3](https://linux-hardware.org/?probe=4e38f93dd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [654a04cdc4](https://linux-hardware.org/?probe=654a04cdc4) | Dec 20, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| K.A.Techno... | TM1                         | [88e36a5d00](https://linux-hardware.org/?probe=88e36a5d00) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Dell          | XPS 13 9350                 | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| HP            | 2000                        | [6273a792ae](https://linux-hardware.org/?probe=6273a792ae) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [86fbbf1bc2](https://linux-hardware.org/?probe=86fbbf1bc2) | Dec 17, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8f50c0d881](https://linux-hardware.org/?probe=8f50c0d881) | Dec 15, 2022 |
| Dell          | Vostro 7590                 | [c758af3223](https://linux-hardware.org/?probe=c758af3223) | Dec 15, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [3878d884cb](https://linux-hardware.org/?probe=3878d884cb) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [98f6e27cac](https://linux-hardware.org/?probe=98f6e27cac) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| K.A.Techno... | TM1                         | [a27835f164](https://linux-hardware.org/?probe=a27835f164) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| Acer          | Aspire ES1-111M             | [0d527c1b1d](https://linux-hardware.org/?probe=0d527c1b1d) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Acer          | Nitro AN517-41              | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| Unknown       | X133                        | [694e264bcf](https://linux-hardware.org/?probe=694e264bcf) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Medion        | E4251                       | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| Medion        | E4251                       | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [16232a46ed](https://linux-hardware.org/?probe=16232a46ed) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| IPASON        | MaxBook P1X                 | [c699081c87](https://linux-hardware.org/?probe=c699081c87) | Dec 08, 2022 |
| BESSTAR Te... | U820                        | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | 245 G8                      | [2fbc616550](https://linux-hardware.org/?probe=2fbc616550) | Dec 07, 2022 |
| Clevo         | P150HMx                     | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| Dell          | Inspiron N5110              | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Dell          | G15 5515                    | [63fed6d448](https://linux-hardware.org/?probe=63fed6d448) | Dec 06, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [3e1e88ac7a](https://linux-hardware.org/?probe=3e1e88ac7a) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| Dell          | G5 5505                     | [c36399d764](https://linux-hardware.org/?probe=c36399d764) | Dec 06, 2022 |
| Medion        | E4251                       | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [8a91af8c9d](https://linux-hardware.org/?probe=8a91af8c9d) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| HP            | ZBook 15 G4                 | [9950cb061d](https://linux-hardware.org/?probe=9950cb061d) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Valve         | Jupiter                     | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| Toshiba       | TECRA S11                   | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Dell          | Precision 7520              | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [69a6535286](https://linux-hardware.org/?probe=69a6535286) | Nov 28, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [a1c088bc35](https://linux-hardware.org/?probe=a1c088bc35) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [0dcd2bdc50](https://linux-hardware.org/?probe=0dcd2bdc50) | Nov 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [620cab185f](https://linux-hardware.org/?probe=620cab185f) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| Alienware     | 15                          | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| MSI           | GP63 Leopard 8RE            | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| ASUSTek       | PRIME Z690-P                | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6722142846](https://linux-hardware.org/?probe=6722142846) | Nov 20, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Google        | Boten                       | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Dell          | Latitude E6220              | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ca85c59fad](https://linux-hardware.org/?probe=ca85c59fad) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| Lenovo        | G500 20236                  | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Acer          | Aspire V5-123               | [7e9ca0bb77](https://linux-hardware.org/?probe=7e9ca0bb77) | Nov 09, 2022 |
| HP            | ENVY 15                     | [716fe10a4a](https://linux-hardware.org/?probe=716fe10a4a) | Nov 09, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Lenovo        | V15-IIL 82C5                | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| Dell          | Inspiron 5379               | [f18d0b8b8a](https://linux-hardware.org/?probe=f18d0b8b8a) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | [141de7e9a7](https://linux-hardware.org/?probe=141de7e9a7) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Dell          | Inspiron 5502               | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [ca5335acd5](https://linux-hardware.org/?probe=ca5335acd5) | Nov 03, 2022 |
| Dell          | Latitude 7280               | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| Dell          | Precision 7530              | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| SANTECH       | NL5xRU                      | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Alienware     | 15 R3                       | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| Chuwi         | LapBook Pro                 | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [d5c2f29c22](https://linux-hardware.org/?probe=d5c2f29c22) | Oct 28, 2022 |
| MSI           | GP66 Leopard 11UG           | [aec6edc8a0](https://linux-hardware.org/?probe=aec6edc8a0) | Oct 28, 2022 |
| Dell          | Inspiron 11 - 3147          | [58d46fb47f](https://linux-hardware.org/?probe=58d46fb47f) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| Lenovo        | G470 20078                  | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| HUAWEI        | BOM-WXX9                    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [b9c616b406](https://linux-hardware.org/?probe=b9c616b406) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | ProBook 445 G7              | [d9f63cbff8](https://linux-hardware.org/?probe=d9f63cbff8) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ffa2d93859](https://linux-hardware.org/?probe=ffa2d93859) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [642cfbc2d7](https://linux-hardware.org/?probe=642cfbc2d7) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [bb90eb1ad1](https://linux-hardware.org/?probe=bb90eb1ad1) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [37028111aa](https://linux-hardware.org/?probe=37028111aa) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [bc30c6555a](https://linux-hardware.org/?probe=bc30c6555a) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [667d235a8f](https://linux-hardware.org/?probe=667d235a8f) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Tactus        | GeoBook_240                 | [5331bf15bd](https://linux-hardware.org/?probe=5331bf15bd) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| HP            | ZBook 17 G6                 | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Global Dis... | W11651                      | [9cf1e2df07](https://linux-hardware.org/?probe=9cf1e2df07) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | Legion 5 82B5               | [3d67f01531](https://linux-hardware.org/?probe=3d67f01531) | Oct 22, 2022 |
| HP            | ProBook 6550b               | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | Katana GF76 11UG            | [ab90111e61](https://linux-hardware.org/?probe=ab90111e61) | Oct 21, 2022 |
| Dell          | Latitude E6400              | [d899ab2ef4](https://linux-hardware.org/?probe=d899ab2ef4) | Oct 21, 2022 |
| Medion        | S15449                      | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| HP            | ProBook 6550b               | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [30bf540299](https://linux-hardware.org/?probe=30bf540299) | Oct 19, 2022 |
| MSI           | Modern 15 A11MU             | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire 4750                 | [e07159c158](https://linux-hardware.org/?probe=e07159c158) | Oct 19, 2022 |
| Dell          | Latitude E6220              | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Acer          | Aspire 4750                 | [0910d29ded](https://linux-hardware.org/?probe=0910d29ded) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [469118097a](https://linux-hardware.org/?probe=469118097a) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Acer          | Aspire V3-771               | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| HP            | ENVY 15                     | [17681478e1](https://linux-hardware.org/?probe=17681478e1) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| MSI           | Katana GF76 11UG            | [460ceb1307](https://linux-hardware.org/?probe=460ceb1307) | Oct 16, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| HP            | ProBook 455 G7              | [bb58a322f3](https://linux-hardware.org/?probe=bb58a322f3) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [705931711b](https://linux-hardware.org/?probe=705931711b) | Oct 13, 2022 |
| Dell          | Latitude E7250              | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1bbc611d89](https://linux-hardware.org/?probe=1bbc611d89) | Oct 12, 2022 |
| AVITA         | NS14A6                      | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| AVITA         | NS14A6                      | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| HUAWEI        | HVY-WXX9                    | [10ab944320](https://linux-hardware.org/?probe=10ab944320) | Oct 11, 2022 |
| HP            | Pavilion g6                 | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| Dell          | Precision 5560              | [001c5b0c94](https://linux-hardware.org/?probe=001c5b0c94) | Oct 09, 2022 |
| Dell          | Latitude 5310               | [f694e6b10e](https://linux-hardware.org/?probe=f694e6b10e) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Acer          | Extensa 215-32              | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [49802b54cd](https://linux-hardware.org/?probe=49802b54cd) | Oct 08, 2022 |
| Acer          | Extensa 215-32              | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [4afa1df235](https://linux-hardware.org/?probe=4afa1df235) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [d0584d3672](https://linux-hardware.org/?probe=d0584d3672) | Oct 08, 2022 |
| HP            | Pavilion dv6                | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| Toshiba       | Satellite P755              | [9b8147c1f7](https://linux-hardware.org/?probe=9b8147c1f7) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Toshiba       | Encore                      | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| CyberPower... | FANG Pro                    | [e8734135b0](https://linux-hardware.org/?probe=e8734135b0) | Oct 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [4ba2e11c73](https://linux-hardware.org/?probe=4ba2e11c73) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [ca89628082](https://linux-hardware.org/?probe=ca89628082) | Oct 03, 2022 |
| GPD           | G1621-02                    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [9c3f9bb60e](https://linux-hardware.org/?probe=9c3f9bb60e) | Oct 03, 2022 |
| MSI           | Katana GF76 11UG            | [d433417836](https://linux-hardware.org/?probe=d433417836) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | XPS 13 9310                 | [f58849d2c7](https://linux-hardware.org/?probe=f58849d2c7) | Oct 03, 2022 |
| HP            | Laptop 14-dk0xxx            | [4283f9a4bd](https://linux-hardware.org/?probe=4283f9a4bd) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | [831cd8e80f](https://linux-hardware.org/?probe=831cd8e80f) | Oct 02, 2022 |
| HP            | ProBook 6470b               | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | 250 G3                      | [753ef53a5a](https://linux-hardware.org/?probe=753ef53a5a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [012add7349](https://linux-hardware.org/?probe=012add7349) | Oct 01, 2022 |
| Sony          | SVF15N17CXB                 | [5082dde27d](https://linux-hardware.org/?probe=5082dde27d) | Oct 01, 2022 |
| Irbis         | NB121                       | [a2eb8c8af1](https://linux-hardware.org/?probe=a2eb8c8af1) | Sep 30, 2022 |
| HP            | EliteBook 850 G1            | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Irbis         | NB121                       | [90a0ae1cf9](https://linux-hardware.org/?probe=90a0ae1cf9) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [3ad60e2d21](https://linux-hardware.org/?probe=3ad60e2d21) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Intel Clie... | LAPQC71A                    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| HP            | Notebook                    | [e172f83238](https://linux-hardware.org/?probe=e172f83238) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [353324cbfd](https://linux-hardware.org/?probe=353324cbfd) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a1bee52021](https://linux-hardware.org/?probe=a1bee52021) | Sep 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [25d3fc37f5](https://linux-hardware.org/?probe=25d3fc37f5) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [47b22afda2](https://linux-hardware.org/?probe=47b22afda2) | Sep 29, 2022 |
| Toshiba       | Satellite C650D             | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| HP            | Laptop 14-dq1xxx            | [9b3a3858bc](https://linux-hardware.org/?probe=9b3a3858bc) | Sep 28, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [9a1e3a98ab](https://linux-hardware.org/?probe=9a1e3a98ab) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ebfbdd37b8](https://linux-hardware.org/?probe=ebfbdd37b8) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [09d154c2f2](https://linux-hardware.org/?probe=09d154c2f2) | Sep 27, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [e27e7bfd76](https://linux-hardware.org/?probe=e27e7bfd76) | Sep 27, 2022 |
| Dell          | Latitude E7440              | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Dell          | Latitude E6400              | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Lenovo        | ThinkPad T460p 20FW000EG... | [60138ee2f9](https://linux-hardware.org/?probe=60138ee2f9) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| ASUSTek       | N45SF                       | [7461bd2562](https://linux-hardware.org/?probe=7461bd2562) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [0d1b8fe301](https://linux-hardware.org/?probe=0d1b8fe301) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| Acer          | Swift SF314-71              | [321edce78d](https://linux-hardware.org/?probe=321edce78d) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Unknown       | Unknown                     | [af65739ccc](https://linux-hardware.org/?probe=af65739ccc) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | Laptop                      | [0cbc7e4f5a](https://linux-hardware.org/?probe=0cbc7e4f5a) | Sep 21, 2022 |
| HP            | ENVY 15                     | [388547d18c](https://linux-hardware.org/?probe=388547d18c) | Sep 21, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [6ffce551a0](https://linux-hardware.org/?probe=6ffce551a0) | Sep 21, 2022 |
| HP            | ProBook 4520s               | [af4a575c52](https://linux-hardware.org/?probe=af4a575c52) | Sep 20, 2022 |
| Apple         | MacBookAir7,2               | [f9f1973349](https://linux-hardware.org/?probe=f9f1973349) | Sep 20, 2022 |
| Gateway       | NV57H                       | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [75cc4fa084](https://linux-hardware.org/?probe=75cc4fa084) | Sep 19, 2022 |
| Acer          | Nitro AN515-42              | [97e2956728](https://linux-hardware.org/?probe=97e2956728) | Sep 19, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [1cbec0f70e](https://linux-hardware.org/?probe=1cbec0f70e) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Apple         | MacBookPro15,1              | [b0e746792f](https://linux-hardware.org/?probe=b0e746792f) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| Dell          | Precision M4800             | [73d00fe344](https://linux-hardware.org/?probe=73d00fe344) | Sep 19, 2022 |
| ASUSTek       | G752VT                      | [bbd1eb7810](https://linux-hardware.org/?probe=bbd1eb7810) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [13b23fabb7](https://linux-hardware.org/?probe=13b23fabb7) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| Dell          | Inspiron MP061              | [f045e1f138](https://linux-hardware.org/?probe=f045e1f138) | Sep 17, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [31c810e744](https://linux-hardware.org/?probe=31c810e744) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [00bcfb51bd](https://linux-hardware.org/?probe=00bcfb51bd) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| ASUSTek       | X550VXK                     | [df5d5b4f0d](https://linux-hardware.org/?probe=df5d5b4f0d) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c9df1f2514](https://linux-hardware.org/?probe=c9df1f2514) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b62bd233c2](https://linux-hardware.org/?probe=b62bd233c2) | Sep 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dee9d6b81f](https://linux-hardware.org/?probe=dee9d6b81f) | Sep 13, 2022 |
| ASUSTek       | X541UJ                      | [9745e99a08](https://linux-hardware.org/?probe=9745e99a08) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b7eb07ec8d](https://linux-hardware.org/?probe=b7eb07ec8d) | Sep 12, 2022 |
| HP            | Pavilion dm1                | [eec30e7c48](https://linux-hardware.org/?probe=eec30e7c48) | Sep 12, 2022 |
| HP            | ENVY 15                     | [97caacee16](https://linux-hardware.org/?probe=97caacee16) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [3d1d8301c3](https://linux-hardware.org/?probe=3d1d8301c3) | Sep 12, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| Timi          | RedmiBook Pro 15S           | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8df1767beb](https://linux-hardware.org/?probe=8df1767beb) | Sep 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [f145a7915c](https://linux-hardware.org/?probe=f145a7915c) | Sep 10, 2022 |
| Dell          | Latitude E6430              | [323203ec1c](https://linux-hardware.org/?probe=323203ec1c) | Sep 09, 2022 |
| Lenovo        | ThinkPad T540p 20BFA05FU... | [e953e3c331](https://linux-hardware.org/?probe=e953e3c331) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f752846656](https://linux-hardware.org/?probe=f752846656) | Sep 09, 2022 |
| CyberPower... | FANG Pro                    | [4bb2815c31](https://linux-hardware.org/?probe=4bb2815c31) | Sep 07, 2022 |
| ASUSTek       | X541UJ                      | [84b26ca406](https://linux-hardware.org/?probe=84b26ca406) | Sep 07, 2022 |
| HP            | EliteBook 840 G5            | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [58e55d314a](https://linux-hardware.org/?probe=58e55d314a) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [11bdade1e5](https://linux-hardware.org/?probe=11bdade1e5) | Sep 05, 2022 |
| Acer          | Nitro AN515-54              | [5b76bade7e](https://linux-hardware.org/?probe=5b76bade7e) | Sep 05, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [8d611bed12](https://linux-hardware.org/?probe=8d611bed12) | Sep 04, 2022 |
| HUAWEI        | VLT-WX0                     | [f9881e0b9b](https://linux-hardware.org/?probe=f9881e0b9b) | Sep 03, 2022 |
| Dell          | XPS 15 9510                 | [3e057c7bbb](https://linux-hardware.org/?probe=3e057c7bbb) | Sep 03, 2022 |
| Acer          | Nitro AN515-54              | [5b5cc6b013](https://linux-hardware.org/?probe=5b5cc6b013) | Sep 03, 2022 |
| ASUSTek       | X510UNR                     | [ca761f1ee7](https://linux-hardware.org/?probe=ca761f1ee7) | Sep 03, 2022 |
| Acer          | Nitro AN515-42              | [74cdbd53f7](https://linux-hardware.org/?probe=74cdbd53f7) | Sep 03, 2022 |
| Dell          | Inspiron 5566               | [3c2359f16d](https://linux-hardware.org/?probe=3c2359f16d) | Sep 03, 2022 |
| Intel Clie... | LAPQC71A                    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| MSI           | Delta 15 A5EFK              | [b7de6bff83](https://linux-hardware.org/?probe=b7de6bff83) | Sep 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| Unknown       | Unknown                     | [cba954794c](https://linux-hardware.org/?probe=cba954794c) | Aug 31, 2022 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [df1e70349c](https://linux-hardware.org/?probe=df1e70349c) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | [1d3dfbba56](https://linux-hardware.org/?probe=1d3dfbba56) | Aug 27, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [85e0bc5d57](https://linux-hardware.org/?probe=85e0bc5d57) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| Dell          | Vostro 5625                 | [741abbfe3d](https://linux-hardware.org/?probe=741abbfe3d) | Aug 26, 2022 |
| Lenovo        | ThinkPad E580 20KS003GMH    | [5cadf3c5d2](https://linux-hardware.org/?probe=5cadf3c5d2) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [d988e1aeb9](https://linux-hardware.org/?probe=d988e1aeb9) | Aug 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9e3b6f2140](https://linux-hardware.org/?probe=9e3b6f2140) | Aug 24, 2022 |
| Dell          | Inspiron 5505               | [4ea2e79611](https://linux-hardware.org/?probe=4ea2e79611) | Aug 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [15960dc164](https://linux-hardware.org/?probe=15960dc164) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [eed44ba087](https://linux-hardware.org/?probe=eed44ba087) | Aug 24, 2022 |
| ASUSTek       | X202E                       | [b814b9f427](https://linux-hardware.org/?probe=b814b9f427) | Aug 24, 2022 |
| Dell          | XPS 15 9520                 | [e4f7ce1ec7](https://linux-hardware.org/?probe=e4f7ce1ec7) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [beb772b7f1](https://linux-hardware.org/?probe=beb772b7f1) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| HP            | Laptop 14-dq1xxx            | [975461703e](https://linux-hardware.org/?probe=975461703e) | Aug 23, 2022 |
| Acer          | Aspire A515-43              | [bc23fbec2a](https://linux-hardware.org/?probe=bc23fbec2a) | Aug 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [47cae9ef99](https://linux-hardware.org/?probe=47cae9ef99) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| HP            | ENVY m6 Notebook            | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [64b9832653](https://linux-hardware.org/?probe=64b9832653) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77a2156c5a](https://linux-hardware.org/?probe=77a2156c5a) | Aug 21, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [32e59cda1c](https://linux-hardware.org/?probe=32e59cda1c) | Aug 20, 2022 |
| Acer          | Aspire R3-131T              | [3f6370f978](https://linux-hardware.org/?probe=3f6370f978) | Aug 20, 2022 |
| Dell          | Latitude 5290 2-in-1        | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| HP            | ProBook 450 G7              | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| HUAWEI        | MACHC-WAX9                  | [95a5dd6af3](https://linux-hardware.org/?probe=95a5dd6af3) | Aug 18, 2022 |
| HUAWEI        | MACHC-WAX9                  | [0a9d130f45](https://linux-hardware.org/?probe=0a9d130f45) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| HP            | Dratini                     | [134a2600be](https://linux-hardware.org/?probe=134a2600be) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [c3fee5819a](https://linux-hardware.org/?probe=c3fee5819a) | Aug 14, 2022 |
| HP            | EliteBook 2760p             | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 D1 81W... | [59b3324e73](https://linux-hardware.org/?probe=59b3324e73) | Aug 13, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6b83355dfa](https://linux-hardware.org/?probe=6b83355dfa) | Aug 13, 2022 |
| MSI           | GE75 Raider 10SF            | [0fafeaaa76](https://linux-hardware.org/?probe=0fafeaaa76) | Aug 13, 2022 |
| HP            | EliteBook 8460p             | [b7418c601b](https://linux-hardware.org/?probe=b7418c601b) | Aug 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [601732f75e](https://linux-hardware.org/?probe=601732f75e) | Aug 13, 2022 |
| Dell          | Precision M6600             | [9c860085a8](https://linux-hardware.org/?probe=9c860085a8) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [59892dec35](https://linux-hardware.org/?probe=59892dec35) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| ASUSTek       | ROG Strix G513QR            | [3b19026468](https://linux-hardware.org/?probe=3b19026468) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [49f045d747](https://linux-hardware.org/?probe=49f045d747) | Aug 09, 2022 |
| ASUSTek       | ROG Strix G513QR            | [7aa074e467](https://linux-hardware.org/?probe=7aa074e467) | Aug 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [e7a185eb28](https://linux-hardware.org/?probe=e7a185eb28) | Aug 08, 2022 |
| Razer         | Blade                       | [e2d9f80c98](https://linux-hardware.org/?probe=e2d9f80c98) | Aug 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [7d20ee4549](https://linux-hardware.org/?probe=7d20ee4549) | Aug 08, 2022 |
| Framework     | Laptop                      | [da39a41b6b](https://linux-hardware.org/?probe=da39a41b6b) | Aug 08, 2022 |
| Framework     | Laptop                      | [f754ffd1d1](https://linux-hardware.org/?probe=f754ffd1d1) | Aug 08, 2022 |
| Dell          | XPS 15 9500                 | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [c4a323d350](https://linux-hardware.org/?probe=c4a323d350) | Aug 06, 2022 |
| MSI           | GS66 Stealth 10SGS          | [24fbb2877c](https://linux-hardware.org/?probe=24fbb2877c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Google        | Blorb                       | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66c9a8d0f6](https://linux-hardware.org/?probe=66c9a8d0f6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [417c72557c](https://linux-hardware.org/?probe=417c72557c) | Aug 05, 2022 |
| GPD           | G1621-02                    | [58586a10a3](https://linux-hardware.org/?probe=58586a10a3) | Aug 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0ef9fef16d](https://linux-hardware.org/?probe=0ef9fef16d) | Aug 04, 2022 |
| Dell          | XPS 15 9500                 | [840cb1763f](https://linux-hardware.org/?probe=840cb1763f) | Aug 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8f15b50066](https://linux-hardware.org/?probe=8f15b50066) | Aug 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Daten Tecn... | DT02-M4                     | [1dfd4fe5ba](https://linux-hardware.org/?probe=1dfd4fe5ba) | Aug 03, 2022 |
| Dell          | XPS 13 7390                 | [05e8b8d782](https://linux-hardware.org/?probe=05e8b8d782) | Aug 03, 2022 |
| Dell          | Latitude 7490               | [0df5a838bf](https://linux-hardware.org/?probe=0df5a838bf) | Aug 03, 2022 |
| Timi          | RedmiBook 14                | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [c2520e642a](https://linux-hardware.org/?probe=c2520e642a) | Aug 02, 2022 |
| HP            | Unknown                     | [bd6c9221e7](https://linux-hardware.org/?probe=bd6c9221e7) | Aug 02, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [7b597ebcc8](https://linux-hardware.org/?probe=7b597ebcc8) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Dell          | G15 Special Edition 5521    | [c680e6f144](https://linux-hardware.org/?probe=c680e6f144) | Aug 01, 2022 |
| Dell          | Latitude 5290 2-in-1        | [838be3a87a](https://linux-hardware.org/?probe=838be3a87a) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Dell          | Inspiron 5520               | [a4baade53f](https://linux-hardware.org/?probe=a4baade53f) | Jul 30, 2022 |
| Dell          | Inspiron 7577               | [a2909a87b1](https://linux-hardware.org/?probe=a2909a87b1) | Jul 30, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [aa446a0409](https://linux-hardware.org/?probe=aa446a0409) | Jul 29, 2022 |
| Dell          | Latitude 5290 2-in-1        | [8d93753bc7](https://linux-hardware.org/?probe=8d93753bc7) | Jul 29, 2022 |
| Dell          | Latitude 5290 2-in-1        | [910241c92e](https://linux-hardware.org/?probe=910241c92e) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [fdb481a551](https://linux-hardware.org/?probe=fdb481a551) | Jul 28, 2022 |
| Acer          | Aspire A515-43              | [230cf1bf3d](https://linux-hardware.org/?probe=230cf1bf3d) | Jul 28, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [d73469794d](https://linux-hardware.org/?probe=d73469794d) | Jul 28, 2022 |
| Alienware     | 17                          | [6a4212d19d](https://linux-hardware.org/?probe=6a4212d19d) | Jul 27, 2022 |
| Dell          | Inspiron 5502               | [f84c29c4b6](https://linux-hardware.org/?probe=f84c29c4b6) | Jul 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4f4bdfefd](https://linux-hardware.org/?probe=f4f4bdfefd) | Jul 27, 2022 |
| MSI           | GF63 Thin 9SC               | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| Lenovo        | ThinkPad E585 20KV000YUS    | [0c8cde264e](https://linux-hardware.org/?probe=0c8cde264e) | Jul 26, 2022 |
| Acer          | Aspire A315-42              | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Predator PH315-52           | [a1346acc8a](https://linux-hardware.org/?probe=a1346acc8a) | Jul 25, 2022 |
| Dell          | Inspiron 15-5578            | [7621729bff](https://linux-hardware.org/?probe=7621729bff) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| MSI           | GF63 Thin 9SC               | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| ASUSTek       | Q504UA                      | [373dce5a6f](https://linux-hardware.org/?probe=373dce5a6f) | Jul 24, 2022 |
| System76      | Serval WS                   | [18259132ff](https://linux-hardware.org/?probe=18259132ff) | Jul 22, 2022 |
| MSI           | GS66 Stealth 10SGS          | [8d7172fe7e](https://linux-hardware.org/?probe=8d7172fe7e) | Jul 22, 2022 |
| ASUSTek       | X450LCP                     | [0617861116](https://linux-hardware.org/?probe=0617861116) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| HP            | ZBook 15 G5                 | [771428353e](https://linux-hardware.org/?probe=771428353e) | Jul 21, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | EliteBook 840 G5            | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| Dell          | Vostro 15 3510              | [8327d57f7b](https://linux-hardware.org/?probe=8327d57f7b) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [29847a6864](https://linux-hardware.org/?probe=29847a6864) | Jul 20, 2022 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | [0602b2d850](https://linux-hardware.org/?probe=0602b2d850) | Jul 19, 2022 |
| Dell          | Latitude E5530 non-vPro     | [27a607d6ba](https://linux-hardware.org/?probe=27a607d6ba) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Apple         | MacBookPro14,2              | [4f1ce227b5](https://linux-hardware.org/?probe=4f1ce227b5) | Jul 18, 2022 |
| Dell          | Inspiron 3421               | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | ThinkPad SL510 28479XU      | [092a752a62](https://linux-hardware.org/?probe=092a752a62) | Jul 18, 2022 |
| Lenovo        | ThinkPad SL510 28479XU      | [5eea2f8d37](https://linux-hardware.org/?probe=5eea2f8d37) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| Dell          | Latitude 7490               | [bed5644964](https://linux-hardware.org/?probe=bed5644964) | Jul 17, 2022 |
| HP            | Laptop 15-dy0xxx            | [cfd2b5a69c](https://linux-hardware.org/?probe=cfd2b5a69c) | Jul 17, 2022 |
| Schenker      | XMG PRO (Late 2021)         | [a59796b464](https://linux-hardware.org/?probe=a59796b464) | Jul 17, 2022 |
| Schenker      | XMG PRO (Late 2021)         | [d739731ef5](https://linux-hardware.org/?probe=d739731ef5) | Jul 17, 2022 |
| Google        | Coral                       | [ebf34e57e6](https://linux-hardware.org/?probe=ebf34e57e6) | Jul 17, 2022 |
| HP            | ProBook 4520s               | [580f66ae82](https://linux-hardware.org/?probe=580f66ae82) | Jul 16, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1bb517b788](https://linux-hardware.org/?probe=1bb517b788) | Jul 16, 2022 |
| ASUSTek       | N552VW                      | [b29b2f27df](https://linux-hardware.org/?probe=b29b2f27df) | Jul 16, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [aa025d852d](https://linux-hardware.org/?probe=aa025d852d) | Jul 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| ASUSTek       | X555LN                      | [0d6d6728ba](https://linux-hardware.org/?probe=0d6d6728ba) | Jul 15, 2022 |
| Chuwi         | HeroBook Air                | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [476ab880f4](https://linux-hardware.org/?probe=476ab880f4) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| Apple         | MacBookAir6,2               | [fe231e27cf](https://linux-hardware.org/?probe=fe231e27cf) | Jul 14, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [367adf8f50](https://linux-hardware.org/?probe=367adf8f50) | Jul 14, 2022 |
| HP            | Laptop 15-dy0xxx            | [a7eb387b79](https://linux-hardware.org/?probe=a7eb387b79) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [f764827707](https://linux-hardware.org/?probe=f764827707) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Dell          | XPS 15 9510                 | [3207d8f9e9](https://linux-hardware.org/?probe=3207d8f9e9) | Jul 12, 2022 |
| Dell          | XPS 15 9510                 | [0f3d24f508](https://linux-hardware.org/?probe=0f3d24f508) | Jul 12, 2022 |
| HUAWEI        | KLVL-WXXW                   | [ded0cc5604](https://linux-hardware.org/?probe=ded0cc5604) | Jul 12, 2022 |
| Acer          | Aspire ES1-523              | [109bec9fa8](https://linux-hardware.org/?probe=109bec9fa8) | Jul 12, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| ASUSTek       | X202E                       | [102f50d1a3](https://linux-hardware.org/?probe=102f50d1a3) | Jul 12, 2022 |
| Apple         | MacBookPro14,1              | [32cbf49371](https://linux-hardware.org/?probe=32cbf49371) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [98d0043f0e](https://linux-hardware.org/?probe=98d0043f0e) | Jul 10, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [b0f6891a0b](https://linux-hardware.org/?probe=b0f6891a0b) | Jul 10, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [5d31b181fd](https://linux-hardware.org/?probe=5d31b181fd) | Jul 10, 2022 |
| Timi          | TM1701                      | [8786fe1e91](https://linux-hardware.org/?probe=8786fe1e91) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec2174a329](https://linux-hardware.org/?probe=ec2174a329) | Jul 10, 2022 |
| HP            | EliteBook 8540p             | [b161f9e458](https://linux-hardware.org/?probe=b161f9e458) | Jul 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Dell          | XPS 13 9333                 | [e464cd5823](https://linux-hardware.org/?probe=e464cd5823) | Jul 08, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [5fa7449343](https://linux-hardware.org/?probe=5fa7449343) | Jul 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Manjaro        | 1424      | 37.07%  |
| Manjaro 22.0.0 | 188       | 4.89%   |
| Manjaro 20.2.1 | 163       | 4.24%   |
| Manjaro 20.1   | 142       | 3.7%    |
| Manjaro 20.2   | 140       | 3.64%   |
| Manjaro 20.0.3 | 125       | 3.25%   |
| Manjaro 21.2.6 | 113       | 2.94%   |
| Manjaro 21.1.0 | 89        | 2.32%   |
| Manjaro 18.1.5 | 83        | 2.16%   |
| Manjaro 21.2.0 | 72        | 1.87%   |
| Manjaro 21.0.7 | 70        | 1.82%   |
| Manjaro 21.2.5 | 65        | 1.69%   |
| Manjaro 21.1.6 | 63        | 1.64%   |
| Manjaro 19.0.2 | 55        | 1.43%   |
| Manjaro 20.0   | 52        | 1.35%   |
| Manjaro 21.2.1 | 48        | 1.25%   |
| Manjaro 18.0.4 | 47        | 1.22%   |
| Manjaro 21.0   | 46        | 1.2%    |
| Manjaro 21.0.5 | 44        | 1.15%   |
| Manjaro 20.1.1 | 41        | 1.07%   |
| Manjaro 20.1.2 | 40        | 1.04%   |
| Manjaro 22.0.4 | 37        | 0.96%   |
| Manjaro 21.2.3 | 37        | 0.96%   |
| Manjaro 20.0.1 | 36        | 0.94%   |
| Manjaro 21.3.7 | 34        | 0.89%   |
| Manjaro 21.2.2 | 31        | 0.81%   |
| Manjaro 21.0.4 | 31        | 0.81%   |
| Manjaro 21.3.6 | 29        | 0.76%   |
| Manjaro 21.2.4 | 29        | 0.76%   |
| Manjaro 21.1.2 | 25        | 0.65%   |
| Manjaro 21.1.4 | 24        | 0.62%   |
| Manjaro 22.0.5 | 22        | 0.57%   |
| Manjaro 21.0.1 | 20        | 0.52%   |
| Manjaro 18.1.4 | 20        | 0.52%   |
| Manjaro 21.3.1 | 19        | 0.49%   |
| Manjaro 21.3.0 | 19        | 0.49%   |
| Manjaro 21.1.3 | 19        | 0.49%   |
| Manjaro 21.1.1 | 19        | 0.49%   |
| Manjaro 22.0.1 | 17        | 0.44%   |
| Manjaro 21.0.2 | 17        | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Manjaro | 3521      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 161       | 3.9%    |
| 5.13.19-2-MANJARO | 95        | 2.3%    |
| 5.9.11-3-MANJARO  | 73        | 1.77%   |
| 5.8.11-1-MANJARO  | 69        | 1.67%   |
| 5.8.6-1-MANJARO   | 68        | 1.65%   |
| 5.15.32-1-MANJARO | 63        | 1.53%   |
| 5.15.28-1-MANJARO | 61        | 1.48%   |
| 5.10.42-1-MANJARO | 57        | 1.38%   |
| 5.8.18-1-MANJARO  | 55        | 1.33%   |
| 5.15.12-1-MANJARO | 52        | 1.26%   |
| 6.1.1-1-MANJARO   | 51        | 1.24%   |
| 6.1.12-1-MANJARO  | 49        | 1.19%   |
| 5.8.16-2-MANJARO  | 41        | 0.99%   |
| 5.15.65-1-MANJARO | 40        | 0.97%   |
| 5.10.2-2-MANJARO  | 40        | 0.97%   |
| 5.6.16-1-MANJARO  | 39        | 0.94%   |
| 5.15.60-1-MANJARO | 39        | 0.94%   |
| 5.10.7-3-MANJARO  | 38        | 0.92%   |
| 5.12.9-1-MANJARO  | 36        | 0.87%   |
| 5.6.19-2-MANJARO  | 33        | 0.8%    |
| 5.15.74-3-MANJARO | 31        | 0.75%   |
| 5.15.7-1-MANJARO  | 31        | 0.75%   |
| 5.7.9-1-MANJARO   | 30        | 0.73%   |
| 5.6.15-1-MANJARO  | 30        | 0.73%   |
| 5.15.81-1-MANJARO | 30        | 0.73%   |
| 5.15.78-1-MANJARO | 30        | 0.73%   |
| 5.15.41-1-MANJARO | 30        | 0.73%   |
| 5.10.36-2-MANJARO | 30        | 0.73%   |
| 5.7.17-2-MANJARO  | 29        | 0.7%    |
| 5.7.0-3-MANJARO   | 29        | 0.7%    |
| 5.8.3-2-MANJARO   | 28        | 0.68%   |
| 5.15.25-1-MANJARO | 28        | 0.68%   |
| 5.14.10-1-MANJARO | 28        | 0.68%   |
| 5.10.34-1-MANJARO | 27        | 0.65%   |
| 5.16.14-1-MANJARO | 25        | 0.61%   |
| 5.15.85-1-MANJARO | 25        | 0.61%   |
| 5.10.70-1-MANJARO | 25        | 0.61%   |
| 5.10.53-1-MANJARO | 25        | 0.61%   |
| 5.9.3-1-MANJARO   | 23        | 0.56%   |
| 5.17.1-3-MANJARO  | 23        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.16  | 161       | 3.9%    |
| 5.13.19 | 96        | 2.33%   |
| 5.9.11  | 77        | 1.87%   |
| 5.8.11  | 69        | 1.67%   |
| 5.8.6   | 68        | 1.65%   |
| 5.15.32 | 64        | 1.55%   |
| 5.15.28 | 61        | 1.48%   |
| 5.10.42 | 57        | 1.38%   |
| 5.8.18  | 55        | 1.33%   |
| 5.15.12 | 52        | 1.26%   |
| 6.1.1   | 51        | 1.24%   |
| 6.1.12  | 49        | 1.19%   |
| 5.8.16  | 42        | 1.02%   |
| 5.15.65 | 40        | 0.97%   |
| 5.10.2  | 40        | 0.97%   |
| 5.6.16  | 39        | 0.95%   |
| 5.15.60 | 39        | 0.95%   |
| 5.10.7  | 39        | 0.95%   |
| 5.7.0   | 36        | 0.87%   |
| 5.12.9  | 36        | 0.87%   |
| 5.6.19  | 35        | 0.85%   |
| 5.9.1   | 33        | 0.8%    |
| 5.15.74 | 32        | 0.78%   |
| 5.15.7  | 32        | 0.78%   |
| 5.7.9   | 30        | 0.73%   |
| 5.6.15  | 30        | 0.73%   |
| 5.17.1  | 30        | 0.73%   |
| 5.15.81 | 30        | 0.73%   |
| 5.15.78 | 30        | 0.73%   |
| 5.15.41 | 30        | 0.73%   |
| 5.10.36 | 30        | 0.73%   |
| 5.7.17  | 29        | 0.7%    |
| 5.8.3   | 28        | 0.68%   |
| 5.15.25 | 28        | 0.68%   |
| 5.14.10 | 28        | 0.68%   |
| 5.10.34 | 27        | 0.65%   |
| 5.19.0  | 26        | 0.63%   |
| 5.16.14 | 25        | 0.61%   |
| 5.15.85 | 25        | 0.61%   |
| 5.10.70 | 25        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 696       | 17.87%  |
| 5.10    | 501       | 12.86%  |
| 5.4     | 356       | 9.14%   |
| 5.9     | 322       | 8.27%   |
| 5.8     | 291       | 7.47%   |
| 5.13    | 204       | 5.24%   |
| 5.6     | 199       | 5.11%   |
| 6.1     | 189       | 4.85%   |
| 5.7     | 137       | 3.52%   |
| 4.19    | 121       | 3.11%   |
| 5.16    | 99        | 2.54%   |
| 5.12    | 94        | 2.41%   |
| 5.11    | 81        | 2.08%   |
| 6.0     | 79        | 2.03%   |
| 5.14    | 76        | 1.95%   |
| 5.19    | 74        | 1.9%    |
| 5.17    | 70        | 1.8%    |
| 5.18    | 69        | 1.77%   |
| 5.3     | 64        | 1.64%   |
| 5.5     | 62        | 1.59%   |
| 4.14    | 25        | 0.64%   |
| 5.2     | 23        | 0.59%   |
| 5.0     | 17        | 0.44%   |
| 6.2     | 14        | 0.36%   |
| 5.1     | 13        | 0.33%   |
| 4.20    | 9         | 0.23%   |
| 4.18    | 7         | 0.18%   |
| 4.9     | 2         | 0.05%   |
| 4.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3519      | 99.94%  |
| i686   | 2         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 1261      | 34.82%  |
| XFCE                 | 800       | 22.09%  |
| GNOME                | 777       | 21.45%  |
| KDE                  | 275       | 7.59%   |
| Unknown              | 194       | 5.36%   |
| X-Cinnamon           | 81        | 2.24%   |
| i3                   | 78        | 2.15%   |
| MATE                 | 36        | 0.99%   |
| Cinnamon             | 30        | 0.83%   |
| Deepin               | 25        | 0.69%   |
| Budgie               | 14        | 0.39%   |
| Awesome              | 11        | 0.3%    |
| Sway                 | 7         | 0.19%   |
| LXQt                 | 7         | 0.19%   |
| LXDE                 | 6         | 0.17%   |
| i3-with-shmlog       | 3         | 0.08%   |
| leftwm               | 2         | 0.06%   |
| GNOME Flashback      | 2         | 0.06%   |
| DWM                  | 2         | 0.06%   |
| Bspwm                | 2         | 0.06%   |
| Yaru:ubuntu:GNOME    | 1         | 0.03%   |
| xinitrc              | 1         | 0.03%   |
| Unity                | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| qtile                | 1         | 0.03%   |
| Hyprland             | 1         | 0.03%   |
| herbstluftwm         | 1         | 0.03%   |
| GNOME Classic        | 1         | 0.03%   |
| Enlightenment        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2971      | 83.24%  |
| Wayland | 476       | 13.34%  |
| Unknown | 90        | 2.52%   |
| Tty     | 32        | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1412      | 39.17%  |
| SDDM    | 919       | 25.49%  |
| LightDM | 646       | 17.92%  |
| GDM     | 492       | 13.65%  |
| TDM     | 123       | 3.41%   |
| LXDM    | 5         | 0.14%   |
| GREETD  | 3         | 0.08%   |
| Ly      | 2         | 0.06%   |
| XDM     | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1535      | 43.09%  |
| de_DE   | 250       | 7.02%   |
| ru_RU   | 248       | 6.96%   |
| Unknown | 241       | 6.77%   |
| en_GB   | 230       | 6.46%   |
| pt_BR   | 144       | 4.04%   |
| fr_FR   | 93        | 2.61%   |
| it_IT   | 72        | 2.02%   |
| es_ES   | 68        | 1.91%   |
| pl_PL   | 64        | 1.8%    |
| en_CA   | 60        | 1.68%   |
| en_IN   | 53        | 1.49%   |
| es_MX   | 40        | 1.12%   |
| en_AU   | 37        | 1.04%   |
| zh_CN   | 31        | 0.87%   |
| de_AT   | 21        | 0.59%   |
| ru_UA   | 20        | 0.56%   |
| C       | 18        | 0.51%   |
| nl_NL   | 17        | 0.48%   |
| es_AR   | 15        | 0.42%   |
| pt_PT   | 14        | 0.39%   |
| en_IE   | 14        | 0.39%   |
| tr_TR   | 13        | 0.36%   |
| en_DK   | 13        | 0.36%   |
| cs_CZ   | 13        | 0.36%   |
| es_CL   | 12        | 0.34%   |
| sv_SE   | 11        | 0.31%   |
| uk_UA   | 10        | 0.28%   |
| es_CO   | 10        | 0.28%   |
| en_ZA   | 10        | 0.28%   |
| fi_FI   | 9         | 0.25%   |
| nl_BE   | 8         | 0.22%   |
| hu_HU   | 8         | 0.22%   |
| en_NZ   | 8         | 0.22%   |
| el_GR   | 8         | 0.22%   |
| de_CH   | 8         | 0.22%   |
| zh_TW   | 7         | 0.2%    |
| en_PH   | 7         | 0.2%    |
| en_DE   | 7         | 0.2%    |
| en_IL   | 6         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1834      | 51.3%   |
| EFI  | 1741      | 48.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2984      | 84.15%  |
| Btrfs    | 325       | 9.17%   |
| Overlay  | 86        | 2.43%   |
| Unknown  | 82        | 2.31%   |
| Xfs      | 36        | 1.02%   |
| Tmpfs    | 14        | 0.39%   |
| F2fs     | 11        | 0.31%   |
| Reiserfs | 3         | 0.08%   |
| Ext3     | 3         | 0.08%   |
| Jfs      | 1         | 0.03%   |
| Ext2     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1741      | 48.6%   |
| Unknown | 1538      | 42.94%  |
| MBR     | 303       | 8.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3203      | 89.92%  |
| Yes       | 359       | 10.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2521      | 70.52%  |
| Yes       | 1054      | 29.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 893       | 25.36%  |
| Hewlett-Packard      | 598       | 16.98%  |
| Dell                 | 528       | 15%     |
| ASUSTek Computer     | 428       | 12.16%  |
| Acer                 | 282       | 8.01%   |
| MSI                  | 104       | 2.95%   |
| Apple                | 87        | 2.47%   |
| Toshiba              | 62        | 1.76%   |
| HUAWEI               | 59        | 1.68%   |
| Samsung Electronics  | 57        | 1.62%   |
| Timi                 | 38        | 1.08%   |
| Sony                 | 30        | 0.85%   |
| Notebook             | 29        | 0.82%   |
| Fujitsu              | 26        | 0.74%   |
| Google               | 24        | 0.68%   |
| Unknown              | 20        | 0.57%   |
| TUXEDO               | 17        | 0.48%   |
| Razer                | 15        | 0.43%   |
| Alienware            | 13        | 0.37%   |
| Schenker             | 11        | 0.31%   |
| Packard Bell         | 9         | 0.26%   |
| LG Electronics       | 9         | 0.26%   |
| System76             | 8         | 0.23%   |
| Medion               | 8         | 0.23%   |
| HONOR                | 8         | 0.23%   |
| Gigabyte Technology  | 8         | 0.23%   |
| Positivo             | 7         | 0.2%    |
| Panasonic            | 7         | 0.2%    |
| Clevo                | 7         | 0.2%    |
| Chuwi                | 7         | 0.2%    |
| Monster              | 6         | 0.17%   |
| Multilaser           | 5         | 0.14%   |
| GPD                  | 5         | 0.14%   |
| Star Labs            | 4         | 0.11%   |
| PC Specialist        | 4         | 0.11%   |
| Intel Client Systems | 4         | 0.11%   |
| Framework            | 4         | 0.11%   |
| TrekStor             | 3         | 0.09%   |
| MECHREVO             | 3         | 0.09%   |
| Gateway              | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 30        | 0.85%   |
| HP Notebook                          | 22        | 0.62%   |
| Lenovo Legion 5 15ARH05 82B5         | 13        | 0.37%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 13        | 0.37%   |
| Dell XPS 15 9500                     | 13        | 0.37%   |
| Dell XPS 13 9310                     | 13        | 0.37%   |
| HP Pavilion Notebook                 | 12        | 0.34%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 11        | 0.31%   |
| HP Pavilion dv7                      | 10        | 0.28%   |
| HP Laptop 15-bs0xx                   | 10        | 0.28%   |
| HP Pavilion g6                       | 9         | 0.26%   |
| HP Pavilion 15                       | 9         | 0.26%   |
| Dell XPS 15 9570                     | 9         | 0.26%   |
| Dell XPS 15 9560                     | 9         | 0.26%   |
| Dell XPS 15 7590                     | 9         | 0.26%   |
| Dell Inspiron 3542                   | 9         | 0.26%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 8         | 0.23%   |
| HP Pavilion dv6                      | 8         | 0.23%   |
| HP OMEN by Laptop                    | 8         | 0.23%   |
| HP 15                                | 8         | 0.23%   |
| Dell XPS 13 7390                     | 8         | 0.23%   |
| Dell Latitude E6430                  | 8         | 0.23%   |
| Dell Inspiron N5110                  | 8         | 0.23%   |
| Apple MacBookPro9,2                  | 8         | 0.23%   |
| Timi TM1701                          | 7         | 0.2%    |
| Lenovo Z50-70 20354                  | 7         | 0.2%    |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 7         | 0.2%    |
| Lenovo Y520-15IKBN 80WK              | 7         | 0.2%    |
| Lenovo IdeaPad 5 14ARE05 81YM        | 7         | 0.2%    |
| HP Laptop 15s-eq2xxx                 | 7         | 0.2%    |
| Dell G3 3590                         | 7         | 0.2%    |
| Apple MacBookPro15,1                 | 7         | 0.2%    |
| Acer Swift SF314-42                  | 7         | 0.2%    |
| Lenovo ThinkBook 15-IIL 20SM         | 6         | 0.17%   |
| Lenovo Legion 5 15ARH05H 82B1        | 6         | 0.17%   |
| Lenovo Legion 5 15ACH6H 82JU         | 6         | 0.17%   |
| Lenovo IdeaPad S540-14API 81NH       | 6         | 0.17%   |
| Lenovo IdeaPad S340-15API 81NC       | 6         | 0.17%   |
| Lenovo G580 20150                    | 6         | 0.17%   |
| HUAWEI KLVL-WXX9                     | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 414       | 11.76%  |
| Lenovo IdeaPad        | 242       | 6.87%   |
| Acer Aspire           | 182       | 5.17%   |
| Dell Inspiron         | 170       | 4.83%   |
| HP Pavilion           | 141       | 4%      |
| Dell Latitude         | 137       | 3.89%   |
| Dell XPS              | 101       | 2.87%   |
| HP Laptop             | 94        | 2.67%   |
| HP ProBook            | 90        | 2.56%   |
| HP EliteBook          | 85        | 2.41%   |
| ASUS VivoBook         | 68        | 1.93%   |
| Lenovo Legion         | 65        | 1.85%   |
| Toshiba Satellite     | 55        | 1.56%   |
| ASUS ROG              | 49        | 1.39%   |
| Dell Precision        | 42        | 1.19%   |
| Dell Vostro           | 37        | 1.05%   |
| Acer Swift            | 35        | 0.99%   |
| ASUS ZenBook          | 33        | 0.94%   |
| ASUS TUF              | 30        | 0.85%   |
| Unknown               | 30        | 0.85%   |
| Acer Nitro            | 27        | 0.77%   |
| Lenovo ThinkBook      | 26        | 0.74%   |
| HP OMEN               | 26        | 0.74%   |
| HP ENVY               | 24        | 0.68%   |
| ASUS ASUS             | 24        | 0.68%   |
| HP Notebook           | 22        | 0.62%   |
| Fujitsu LIFEBOOK      | 22        | 0.62%   |
| Lenovo Yoga           | 20        | 0.57%   |
| HP ZBook              | 20        | 0.57%   |
| HP 250                | 17        | 0.48%   |
| Timi RedmiBook        | 16        | 0.45%   |
| Dell G3               | 15        | 0.43%   |
| Razer Blade           | 14        | 0.4%    |
| HP Compaq             | 14        | 0.4%    |
| HP 15                 | 13        | 0.37%   |
| Apple MacBookPro11    | 13        | 0.37%   |
| Acer TravelMate       | 13        | 0.37%   |
| Acer Predator         | 12        | 0.34%   |
| HP 255                | 11        | 0.31%   |
| Packard Bell EasyNote | 9         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 475       | 13.49%  |
| 2020    | 471       | 13.38%  |
| 2018    | 371       | 10.54%  |
| 2021    | 323       | 9.17%   |
| 2017    | 280       | 7.95%   |
| 2012    | 259       | 7.36%   |
| 2015    | 207       | 5.88%   |
| 2013    | 204       | 5.79%   |
| 2014    | 200       | 5.68%   |
| 2016    | 192       | 5.45%   |
| 2011    | 190       | 5.4%    |
| 2010    | 108       | 3.07%   |
| 2022    | 80        | 2.27%   |
| 2008    | 70        | 1.99%   |
| 2009    | 52        | 1.48%   |
| 2007    | 26        | 0.74%   |
| 2006    | 7         | 0.2%    |
| Unknown | 3         | 0.09%   |
| 2023    | 2         | 0.06%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3521      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3519      | 99.89%  |
| Enabled  | 4         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3479      | 98.81%  |
| Yes  | 42        | 1.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1080      | 30.34%  |
| 16.01-24.0  | 765       | 21.49%  |
| 8.01-16.0   | 737       | 20.7%   |
| 3.01-4.0    | 509       | 14.3%   |
| 32.01-64.0  | 273       | 7.67%   |
| 1.01-2.0    | 68        | 1.91%   |
| 24.01-32.0  | 60        | 1.69%   |
| 64.01-256.0 | 40        | 1.12%   |
| 2.01-3.0    | 27        | 0.76%   |
| 0.51-1.0    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1086      | 27.97%  |
| 1.01-2.0   | 993       | 25.57%  |
| 4.01-8.0   | 760       | 19.57%  |
| 3.01-4.0   | 670       | 17.25%  |
| 8.01-16.0  | 213       | 5.49%   |
| 0.51-1.0   | 132       | 3.4%    |
| 16.01-24.0 | 16        | 0.41%   |
| 24.01-32.0 | 6         | 0.15%   |
| 0.01-0.5   | 6         | 0.15%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2430      | 67.73%  |
| 2      | 997       | 27.79%  |
| 3      | 129       | 3.6%    |
| 0      | 19        | 0.53%   |
| 4      | 11        | 0.31%   |
| 7      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2618      | 73.89%  |
| Yes       | 925       | 26.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2707      | 76.62%  |
| No        | 826       | 23.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3480      | 98.75%  |
| No        | 44        | 1.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2882      | 81.32%  |
| No        | 662       | 18.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 527       | 14.87%  |
| Germany     | 377       | 10.63%  |
| Russia      | 329       | 9.28%   |
| Brazil      | 212       | 5.98%   |
| France      | 133       | 3.75%   |
| UK          | 120       | 3.39%   |
| Italy       | 118       | 3.33%   |
| Poland      | 106       | 2.99%   |
| Spain       | 96        | 2.71%   |
| Canada      | 96        | 2.71%   |
| India       | 93        | 2.62%   |
| Ukraine     | 88        | 2.48%   |
| Netherlands | 85        | 2.4%    |
| Mexico      | 63        | 1.78%   |
| China       | 50        | 1.41%   |
| Austria     | 50        | 1.41%   |
| Turkey      | 44        | 1.24%   |
| Australia   | 43        | 1.21%   |
| Sweden      | 38        | 1.07%   |
| Indonesia   | 37        | 1.04%   |
| Romania     | 35        | 0.99%   |
| Portugal    | 33        | 0.93%   |
| Belgium     | 33        | 0.93%   |
| Switzerland | 32        | 0.9%    |
| Czechia     | 32        | 0.9%    |
| Belarus     | 28        | 0.79%   |
| Finland     | 26        | 0.73%   |
| Hungary     | 25        | 0.71%   |
| Norway      | 24        | 0.68%   |
| Greece      | 24        | 0.68%   |
| Bulgaria    | 24        | 0.68%   |
| Argentina   | 23        | 0.65%   |
| Colombia    | 21        | 0.59%   |
| Taiwan      | 20        | 0.56%   |
| Denmark     | 20        | 0.56%   |
| Iran        | 18        | 0.51%   |
| Bangladesh  | 17        | 0.48%   |
| Chile       | 16        | 0.45%   |
| Japan       | 15        | 0.42%   |
| Croatia     | 15        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 74        | 1.98%   |
| St Petersburg     | 49        | 1.31%   |
| Vienna            | 35        | 0.94%   |
| Paris             | 32        | 0.86%   |
| Berlin            | 28        | 0.75%   |
| Sao Paulo         | 26        | 0.7%    |
| Kyiv              | 25        | 0.67%   |
| Amsterdam         | 23        | 0.62%   |
| Warsaw            | 20        | 0.54%   |
| Milan             | 19        | 0.51%   |
| Munich            | 18        | 0.48%   |
| Toronto           | 17        | 0.46%   |
| Frankfurt am Main | 17        | 0.46%   |
| Bengaluru         | 17        | 0.46%   |
| Prague            | 16        | 0.43%   |
| Novosibirsk       | 16        | 0.43%   |
| Minsk             | 16        | 0.43%   |
| Istanbul          | 16        | 0.43%   |
| Helsinki          | 15        | 0.4%    |
| Madrid            | 14        | 0.37%   |
| Rome              | 13        | 0.35%   |
| Mexico City       | 13        | 0.35%   |
| London            | 13        | 0.35%   |
| Hamburg           | 13        | 0.35%   |
| Budapest          | 13        | 0.35%   |
| Bucharest         | 13        | 0.35%   |
| Barcelona         | 13        | 0.35%   |
| Sofia             | 12        | 0.32%   |
| Melbourne         | 12        | 0.32%   |
| Yekaterinburg     | 11        | 0.29%   |
| Krasnodar         | 11        | 0.29%   |
| Dhaka             | 11        | 0.29%   |
| Cologne           | 11        | 0.29%   |
| Beijing           | 11        | 0.29%   |
| Athens            | 11        | 0.29%   |
| Zagreb            | 10        | 0.27%   |
| The Hague         | 10        | 0.27%   |
| Stockholm         | 10        | 0.27%   |
| Seattle           | 10        | 0.27%   |
| San Jose          | 10        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 809       | 1072   | 17.46%  |
| WDC                            | 506       | 608    | 10.92%  |
| Seagate                        | 462       | 597    | 9.97%   |
| Toshiba                        | 353       | 410    | 7.62%   |
| SanDisk                        | 311       | 394    | 6.71%   |
| Kingston                       | 255       | 296    | 5.5%    |
| SK hynix                       | 237       | 287    | 5.11%   |
| Unknown                        | 232       | 278    | 5.01%   |
| Crucial                        | 160       | 197    | 3.45%   |
| Intel                          | 156       | 193    | 3.37%   |
| HGST                           | 140       | 168    | 3.02%   |
| Micron Technology              | 124       | 157    | 2.68%   |
| Hitachi                        | 87        | 102    | 1.88%   |
| KIOXIA                         | 58        | 67     | 1.25%   |
| A-DATA Technology              | 58        | 69     | 1.25%   |
| Apple                          | 55        | 66     | 1.19%   |
| Phison                         | 44        | 64     | 0.95%   |
| China                          | 36        | 39     | 0.78%   |
| Transcend                      | 30        | 36     | 0.65%   |
| LITEONIT                       | 26        | 32     | 0.56%   |
| GOODRAM                        | 26        | 44     | 0.56%   |
| LITEON                         | 23        | 26     | 0.5%    |
| Silicon Motion                 | 22        | 25     | 0.47%   |
| Micron/Crucial Technology      | 22        | 26     | 0.47%   |
| Phison Electronics             | 19        | 19     | 0.41%   |
| JMicron Technology             | 18        | 19     | 0.39%   |
| Plextor                        | 14        | 22     | 0.3%    |
| Union Memory (Shenzhen)        | 12        | 12     | 0.26%   |
| Patriot                        | 12        | 12     | 0.26%   |
| Intenso                        | 12        | 13     | 0.26%   |
| SPCC                           | 11        | 13     | 0.24%   |
| Solid State Storage Technology | 11        | 18     | 0.24%   |
| Kingston Technology Company    | 11        | 11     | 0.24%   |
| Fujitsu                        | 10        | 10     | 0.22%   |
| Unknown                        | 10        | 12     | 0.22%   |
| XPG                            | 9         | 15     | 0.19%   |
| Hewlett-Packard                | 9         | 13     | 0.19%   |
| PNY                            | 8         | 12     | 0.17%   |
| Netac                          | 8         | 14     | 0.17%   |
| Corsair                        | 8         | 8      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 92        | 1.91%   |
| Samsung NVMe SSD Drive 512GB                        | 65        | 1.35%   |
| Toshiba MQ01ABD100 1TB                              | 51        | 1.06%   |
| HGST HTS721010A9E630 1TB                            | 51        | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 49        | 1.01%   |
| Toshiba MQ04ABF100 1TB                              | 48        | 0.99%   |
| SK hynix NVMe SSD Drive 512GB                       | 46        | 0.95%   |
| SanDisk NVMe SSD Drive 512GB                        | 43        | 0.89%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 43        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 42        | 0.87%   |
| Kingston SA400S37240G 240GB SSD                     | 40        | 0.83%   |
| Toshiba MQ01ABF050 500GB                            | 37        | 0.77%   |
| Unknown MMC Card  32GB                              | 32        | 0.66%   |
| Intel NVMe SSD Drive 512GB                          | 30        | 0.62%   |
| Unknown MMC Card  64GB                              | 29        | 0.6%    |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.6%    |
| Unknown SD/MMC/MS PRO 64GB                          | 28        | 0.58%   |
| Crucial CT500MX500SSD1 500GB                        | 27        | 0.56%   |
| SanDisk NVMe SSD Drive 256GB                        | 26        | 0.54%   |
| Seagate ST500LT012-1DG142 500GB                     | 25        | 0.52%   |
| Seagate ST1000LM049-2GH172 1TB                      | 24        | 0.5%    |
| Kingston SA400S37120G 120GB SSD                     | 24        | 0.5%    |
| HGST HTS545050A7E680 500GB                          | 24        | 0.5%    |
| Samsung NVMe SSD Drive 1024GB                       | 23        | 0.48%   |
| SK hynix NVMe SSD Drive 256GB                       | 22        | 0.46%   |
| Seagate Expansion+ 2TB                              | 22        | 0.46%   |
| Samsung SSD 860 EVO 500GB                           | 22        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 22        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                     | 21        | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 19        | 0.39%   |
| Seagate ST9500325AS 500GB                           | 19        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 19        | 0.39%   |
| Micron NVMe SSD Drive 512GB                         | 19        | 0.39%   |
| Kingston NVMe SSD Drive 512GB                       | 19        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB                         | 19        | 0.39%   |
| WDC WD10SPZX-24Z10 1TB                              | 18        | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 18        | 0.37%   |
| Toshiba NVMe SSD Drive 512GB                        | 18        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 18        | 0.37%   |
| Intel SSDPEKNW512G8 512GB                           | 18        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 452       | 578    | 34.56%  |
| WDC                 | 328       | 384    | 25.08%  |
| Toshiba             | 223       | 257    | 17.05%  |
| HGST                | 140       | 168    | 10.7%   |
| Hitachi             | 87        | 102    | 6.65%   |
| Unknown             | 30        | 33     | 2.29%   |
| Samsung Electronics | 14        | 16     | 1.07%   |
| Fujitsu             | 10        | 10     | 0.76%   |
| Apple               | 5         | 6      | 0.38%   |
| SABRENT             | 4         | 4      | 0.31%   |
| USB3.0              | 2         | 2      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| ASMT                | 2         | 2      | 0.15%   |
| QNAP                | 1         | 1      | 0.08%   |
| Pioneer             | 1         | 3      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 1      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 329       | 412    | 22.86%  |
| Kingston            | 184       | 209    | 12.79%  |
| Crucial             | 147       | 184    | 10.22%  |
| SanDisk             | 126       | 166    | 8.76%   |
| WDC                 | 84        | 102    | 5.84%   |
| Micron Technology   | 52        | 67     | 3.61%   |
| A-DATA Technology   | 43        | 49     | 2.99%   |
| SK hynix            | 41        | 50     | 2.85%   |
| Intel               | 37        | 43     | 2.57%   |
| China               | 36        | 39     | 2.5%    |
| Apple               | 36        | 40     | 2.5%    |
| Toshiba             | 31        | 34     | 2.15%   |
| Transcend           | 28        | 33     | 1.95%   |
| LITEONIT            | 26        | 32     | 1.81%   |
| GOODRAM             | 25        | 43     | 1.74%   |
| LITEON              | 20        | 23     | 1.39%   |
| Plextor             | 13        | 21     | 0.9%    |
| Patriot             | 11        | 11     | 0.76%   |
| Intenso             | 10        | 11     | 0.69%   |
| Netac               | 8         | 14     | 0.56%   |
| JMicron Technology  | 8         | 8      | 0.56%   |
| PNY                 | 7         | 11     | 0.49%   |
| OCZ                 | 7         | 8      | 0.49%   |
| KingSpec            | 7         | 7      | 0.49%   |
| SPCC                | 6         | 7      | 0.42%   |
| Seagate             | 6         | 10     | 0.42%   |
| Hewlett-Packard     | 5         | 8      | 0.35%   |
| Corsair             | 5         | 5      | 0.35%   |
| Unknown             | 5         | 7      | 0.35%   |
| TO Exter            | 4         | 5      | 0.28%   |
| Lexar               | 4         | 4      | 0.28%   |
| FORESEE             | 4         | 4      | 0.28%   |
| Apacer              | 4         | 4      | 0.28%   |
| TwinMOS             | 3         | 5      | 0.21%   |
| Team                | 3         | 4      | 0.21%   |
| Mushkin             | 3         | 4      | 0.21%   |
| Vaseky              | 2         | 2      | 0.14%   |
| Unknown             | 2         | 3      | 0.14%   |
| OWC                 | 2         | 4      | 0.14%   |
| NGFF                | 2         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1531      | 2083   | 34.93%  |
| SSD     | 1343      | 1774   | 30.64%  |
| HDD     | 1255      | 1575   | 28.63%  |
| MMC     | 193       | 236    | 4.4%    |
| Unknown | 61        | 69     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2224      | 3197   | 53.86%  |
| NVMe | 1531      | 2072   | 37.08%  |
| MMC  | 193       | 236    | 4.67%   |
| SAS  | 181       | 232    | 4.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1583      | 2117   | 61.74%  |
| 0.51-1.0   | 862       | 1070   | 33.62%  |
| 1.01-2.0   | 96        | 119    | 3.74%   |
| 4.01-10.0  | 14        | 21     | 0.55%   |
| 3.01-4.0   | 6         | 19     | 0.23%   |
| 2.01-3.0   | 3         | 3      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 980       | 26.86%  |
| 251-500        | 949       | 26.01%  |
| 501-1000       | 575       | 15.76%  |
| 1001-2000      | 292       | 8%      |
| Unknown        | 262       | 7.18%   |
| 51-100         | 233       | 6.39%   |
| 1-20           | 131       | 3.59%   |
| 21-50          | 110       | 3.01%   |
| More than 3000 | 61        | 1.67%   |
| 2001-3000      | 56        | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 890       | 23.36%  |
| 21-50          | 726       | 19.06%  |
| 101-250        | 641       | 16.82%  |
| 51-100         | 576       | 15.12%  |
| 251-500        | 399       | 10.47%  |
| Unknown        | 262       | 6.88%   |
| 501-1000       | 215       | 5.64%   |
| 1001-2000      | 69        | 1.81%   |
| More than 3000 | 15        | 0.39%   |
| 2001-3000      | 14        | 0.37%   |
| 0              | 3         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 4.78%   |
| HGST HTS545050A7E680 500GB                          | 9         | 9      | 4.31%   |
| HGST HTS721010A9E630 1TB                            | 8         | 8      | 3.83%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 2.87%   |
| HGST HTS545050A7E380 500GB                          | 6         | 6      | 2.87%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 22     | 2.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 5      | 2.39%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 1.91%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 1.44%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 3      | 1.44%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 1.44%   |
| Seagate ST9320325AS 320GB                           | 3         | 4      | 1.44%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 1.44%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 3         | 3      | 1.44%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 1.44%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 1.44%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 1.44%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 0.96%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 0.96%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.96%   |
| Seagate ST9750420AS 752GB                           | 2         | 2      | 0.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 0.96%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 5      | 0.96%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 0.96%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.96%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 0.96%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2      | 0.96%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 0.48%   |
| WDC WD800BEVS-22RST0 80GB                           | 1         | 1      | 0.48%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 0.48%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000BPVT-60HXZT3 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000BEVT-75A0RT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1      | 0.48%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 1         | 1      | 0.48%   |
| WDC WD2500LPCX-24C6HT0 250GB                        | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 81     | 25.48%  |
| HGST                | 31        | 31     | 14.9%   |
| WDC                 | 24        | 27     | 11.54%  |
| Toshiba             | 23        | 26     | 11.06%  |
| Hitachi             | 19        | 20     | 9.13%   |
| Samsung Electronics | 10        | 11     | 4.81%   |
| Crucial             | 8         | 11     | 3.85%   |
| SK hynix            | 6         | 10     | 2.88%   |
| SanDisk             | 6         | 6      | 2.88%   |
| Intel               | 5         | 6      | 2.4%    |
| Micron Technology   | 4         | 6      | 1.92%   |
| LITEON              | 3         | 3      | 1.44%   |
| Kingston            | 3         | 3      | 1.44%   |
| A-DATA Technology   | 3         | 4      | 1.44%   |
| TwinMOS             | 1         | 1      | 0.48%   |
| Realtek             | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 1      | 0.48%   |
| IM3D                | 1         | 1      | 0.48%   |
| Faspeed             | 1         | 1      | 0.48%   |
| Corsair             | 1         | 1      | 0.48%   |
| ASMT                | 1         | 1      | 0.48%   |
| Apple               | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 81     | 36.05%  |
| HGST                | 31        | 31     | 21.09%  |
| WDC                 | 23        | 26     | 15.65%  |
| Toshiba             | 19        | 22     | 12.93%  |
| Hitachi             | 19        | 20     | 12.93%  |
| Samsung Electronics | 1         | 1      | 0.68%   |
| ASMT                | 1         | 1      | 0.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 146       | 182    | 70.87%  |
| SSD  | 52        | 64     | 25.24%  |
| NVMe | 8         | 9      | 3.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 33.33%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2199      | 3418   | 57.98%  |
| Works    | 1389      | 2061   | 36.62%  |
| Malfunc  | 202       | 255    | 5.33%   |
| Failed   | 3         | 3      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2302      | 52.35%  |
| Samsung Electronics              | 522       | 11.87%  |
| AMD                              | 516       | 11.74%  |
| SanDisk                          | 273       | 6.21%   |
| SK hynix                         | 194       | 4.41%   |
| Toshiba America Info Systems     | 94        | 2.14%   |
| Kingston Technology Company      | 81        | 1.84%   |
| Micron Technology                | 71        | 1.61%   |
| Phison Electronics               | 68        | 1.55%   |
| KIOXIA                           | 66        | 1.5%    |
| Micron/Crucial Technology        | 34        | 0.77%   |
| ADATA Technology                 | 26        | 0.59%   |
| Union Memory (Shenzhen)          | 25        | 0.57%   |
| Silicon Motion                   | 25        | 0.57%   |
| Solid State Storage Technology   | 18        | 0.41%   |
| Nvidia                           | 18        | 0.41%   |
| Apple                            | 13        | 0.3%    |
| Lite-On Technology               | 10        | 0.23%   |
| Realtek Semiconductor            | 9         | 0.2%    |
| Shenzhen Longsys Electronics     | 8         | 0.18%   |
| Marvell Technology Group         | 5         | 0.11%   |
| Lenovo                           | 4         | 0.09%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| JMicron Technology               | 3         | 0.07%   |
| Biwin Storage Technology         | 3         | 0.07%   |
| Seagate Technology               | 2         | 0.05%   |
| Transcend                        | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| ASMedia Technology               | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 477       | 10.42%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 316       | 6.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 286       | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 247       | 5.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 216       | 4.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 161       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 156       | 3.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 142       | 3.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 128       | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 118       | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 107       | 2.34%   |
| Samsung NVMe SSD Controller 980                                                | 106       | 2.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 83        | 1.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 81        | 1.77%   |
| Micron NVMe Storage Controller                                                 | 70        | 1.53%   |
| Intel SSD 660P Series                                                          | 63        | 1.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 61        | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 58        | 1.27%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 57        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 57        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 52        | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 49        | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 47        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 46        | 1.01%   |
| SK hynix BC511                                                                 | 43        | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 40        | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 40        | 0.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 38        | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 38        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 36        | 0.79%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 35        | 0.76%   |
| SK hynix Non-Volatile memory controller                                        | 33        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 32        | 0.7%    |
| Phison E12 NVMe Controller                                                     | 30        | 0.66%   |
| Intel Tiger Lake-LP SATA Controller                                            | 30        | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 30        | 0.66%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 29        | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 27        | 0.59%   |
| SanDisk NVMe Controller                                                        | 26        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2479      | 56.19%  |
| NVMe | 1536      | 34.81%  |
| RAID | 299       | 6.78%   |
| IDE  | 98        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2733      | 77.62%  |
| AMD    | 788       | 22.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 80        | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 68        | 1.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 67        | 1.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 66        | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 1.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 63        | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 62        | 1.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 62        | 1.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 60        | 1.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 51        | 1.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 48        | 1.36%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 47        | 1.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 46        | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 42        | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 1.19%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 41        | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 40        | 1.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 40        | 1.13%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 35        | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 33        | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 32        | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 32        | 0.91%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 32        | 0.91%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 30        | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 29        | 0.82%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 28        | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.79%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.77%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 27        | 0.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 27        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.77%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 26        | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 22        | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 21        | 0.6%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 21        | 0.6%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 21        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 936       | 26.55%  |
| Intel Core i5                  | 928       | 26.32%  |
| AMD Ryzen 7                    | 242       | 6.86%   |
| Intel Core i3                  | 235       | 6.66%   |
| Other                          | 234       | 6.64%   |
| AMD Ryzen 5                    | 233       | 6.61%   |
| Intel Celeron                  | 135       | 3.83%   |
| Intel Core 2 Duo               | 88        | 2.5%    |
| Intel Pentium                  | 79        | 2.24%   |
| AMD Ryzen 3                    | 49        | 1.39%   |
| AMD Ryzen 7 PRO                | 32        | 0.91%   |
| AMD Ryzen 9                    | 31        | 0.88%   |
| AMD A6                         | 27        | 0.77%   |
| Intel Core i9                  | 24        | 0.68%   |
| Intel Atom                     | 24        | 0.68%   |
| AMD A10                        | 24        | 0.68%   |
| AMD A8                         | 22        | 0.62%   |
| Intel Pentium Dual-Core        | 19        | 0.54%   |
| AMD A4                         | 19        | 0.54%   |
| AMD E1                         | 17        | 0.48%   |
| AMD E                          | 17        | 0.48%   |
| Intel Pentium Silver           | 15        | 0.43%   |
| Intel Core 2                   | 10        | 0.28%   |
| AMD E2                         | 9         | 0.26%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.2%    |
| AMD Athlon                     | 7         | 0.2%    |
| Intel Core m3                  | 6         | 0.17%   |
| AMD Ryzen 5 PRO                | 6         | 0.17%   |
| AMD A12                        | 5         | 0.14%   |
| Intel Xeon                     | 4         | 0.11%   |
| Intel Genuine                  | 4         | 0.11%   |
| AMD FX                         | 4         | 0.11%   |
| Intel Core m5                  | 3         | 0.09%   |
| AMD Athlon X2                  | 3         | 0.09%   |
| Intel Core m7                  | 2         | 0.06%   |
| Intel Core M                   | 2         | 0.06%   |
| Intel Core 2 Quad              | 2         | 0.06%   |
| Intel Celeron Dual-Core        | 2         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.06%   |
| AMD Turion II                  | 2         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1501      | 42.62%  |
| 4       | 1308      | 37.14%  |
| 6       | 347       | 9.85%   |
| 8       | 310       | 8.8%    |
| 14      | 16        | 0.45%   |
| 1       | 16        | 0.45%   |
| 12      | 14        | 0.4%    |
| 10      | 5         | 0.14%   |
| 16      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3521      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2901      | 82.34%  |
| 1       | 621       | 17.63%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3458      | 98.15%  |
| Unknown        | 65        | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1748      | 48.04%  |
| 0x306a9    | 139       | 3.82%   |
| 0x906ea    | 117       | 3.22%   |
| 0x806ea    | 115       | 3.16%   |
| 0x806ec    | 103       | 2.83%   |
| 0x806c1    | 88        | 2.42%   |
| 0x806e9    | 77        | 2.12%   |
| 0x206a7    | 76        | 2.09%   |
| 0x40651    | 71        | 1.95%   |
| 0x406e3    | 69        | 1.9%    |
| 0x08108102 | 63        | 1.73%   |
| 0x306c3    | 58        | 1.59%   |
| 0x306d4    | 55        | 1.51%   |
| 0x08600106 | 54        | 1.48%   |
| 0x906e9    | 53        | 1.46%   |
| 0x0a50000c | 52        | 1.43%   |
| 0xa0652    | 46        | 1.26%   |
| 0x08600103 | 43        | 1.18%   |
| 0x806eb    | 42        | 1.15%   |
| 0x08108109 | 41        | 1.13%   |
| 0x706e5    | 38        | 1.04%   |
| 0x08600104 | 36        | 0.99%   |
| 0x08608103 | 30        | 0.82%   |
| 0x1067a    | 29        | 0.8%    |
| 0x506e3    | 28        | 0.77%   |
| 0x20655    | 28        | 0.77%   |
| 0x30678    | 17        | 0.47%   |
| 0x806d1    | 16        | 0.44%   |
| 0x0810100b | 16        | 0.44%   |
| 0x906a3    | 15        | 0.41%   |
| 0x406c4    | 15        | 0.41%   |
| 0x06006705 | 15        | 0.41%   |
| 0x506c9    | 14        | 0.38%   |
| 0x706a1    | 13        | 0.36%   |
| 0x906ed    | 11        | 0.3%    |
| 0x08600102 | 11        | 0.3%    |
| 0x0600611a | 11        | 0.3%    |
| 0x0a50000b | 10        | 0.27%   |
| 0x06001119 | 10        | 0.27%   |
| 0x20652    | 8         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 880       | 24.98%  |
| Haswell          | 282       | 8%      |
| IvyBridge        | 259       | 7.35%   |
| Zen 2            | 209       | 5.93%   |
| Skylake          | 198       | 5.62%   |
| SandyBridge      | 198       | 5.62%   |
| Zen+             | 163       | 4.63%   |
| TigerLake        | 153       | 4.34%   |
| Broadwell        | 141       | 4%      |
| Unknown          | 117       | 3.32%   |
| Zen 3            | 115       | 3.26%   |
| Westmere         | 91        | 2.58%   |
| Penryn           | 91        | 2.58%   |
| CometLake        | 91        | 2.58%   |
| Silvermont       | 85        | 2.41%   |
| Icelake          | 80        | 2.27%   |
| Excavator        | 57        | 1.62%   |
| Goldmont plus    | 50        | 1.42%   |
| Zen              | 38        | 1.08%   |
| Core             | 35        | 0.99%   |
| Goldmont         | 30        | 0.85%   |
| Bobcat           | 27        | 0.77%   |
| Piledriver       | 24        | 0.68%   |
| Puma             | 22        | 0.62%   |
| Jaguar           | 20        | 0.57%   |
| Alderlake Hybrid | 16        | 0.45%   |
| Nehalem          | 10        | 0.28%   |
| K8 Hammer        | 9         | 0.26%   |
| K10 Llano        | 9         | 0.26%   |
| K10              | 7         | 0.2%    |
| Steamroller      | 5         | 0.14%   |
| K8 & K10 hybrid  | 5         | 0.14%   |
| Bonnell          | 5         | 0.14%   |
| Tremont          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2541      | 53.8%   |
| Nvidia | 1243      | 26.32%  |
| AMD    | 939       | 19.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 247       | 5.12%   |
| AMD Renoir                                                                               | 199       | 4.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 197       | 4.09%   |
| Intel UHD Graphics 620                                                                   | 173       | 3.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 173       | 3.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 165       | 3.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 155       | 3.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 147       | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 134       | 2.78%   |
| Intel HD Graphics 620                                                                    | 124       | 2.57%   |
| Intel HD Graphics 5500                                                                   | 121       | 2.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 109       | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 99        | 2.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 96        | 1.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 90        | 1.87%   |
| Intel HD Graphics 630                                                                    | 87        | 1.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 69        | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 68        | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 65        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 65        | 1.35%   |
| AMD Lucienne                                                                             | 61        | 1.27%   |
| Intel HD Graphics 530                                                                    | 60        | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 45        | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 43        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 42        | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 40        | 0.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 40        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 37        | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 36        | 0.75%   |
| Nvidia TU117M                                                                            | 36        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 36        | 0.75%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 35        | 0.73%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 35        | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 33        | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 33        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1486      | 42.12%  |
| Intel + Nvidia     | 935       | 26.5%   |
| 1 x AMD            | 614       | 17.4%   |
| 1 x Nvidia         | 161       | 4.56%   |
| AMD + Nvidia       | 142       | 4.02%   |
| Intel + AMD        | 115       | 3.26%   |
| 2 x AMD            | 69        | 1.96%   |
| 2 x Nvidia         | 3         | 0.09%   |
| Other              | 2         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2841      | 79.85%  |
| Proprietary | 716       | 20.12%  |
| Unknown     | 1         | 0.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2720      | 76.08%  |
| 0.01-0.5   | 291       | 8.14%   |
| 1.01-2.0   | 233       | 6.52%   |
| 0.51-1.0   | 115       | 3.22%   |
| 3.01-4.0   | 111       | 3.1%    |
| 5.01-6.0   | 56        | 1.57%   |
| 7.01-8.0   | 29        | 0.81%   |
| 2.01-3.0   | 11        | 0.31%   |
| 8.01-16.0  | 8         | 0.22%   |
| 16.01-24.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 702       | 16.89%  |
| LG Display              | 642       | 15.44%  |
| Chimei Innolux          | 619       | 14.89%  |
| BOE                     | 610       | 14.67%  |
| Samsung Electronics     | 326       | 7.84%   |
| Sharp                   | 134       | 3.22%   |
| Dell                    | 116       | 2.79%   |
| Goldstar                | 104       | 2.5%    |
| PANDA                   | 91        | 2.19%   |
| Apple                   | 88        | 2.12%   |
| Chi Mei Optoelectronics | 79        | 1.9%    |
| Lenovo                  | 67        | 1.61%   |
| Hewlett-Packard         | 47        | 1.13%   |
| Acer                    | 39        | 0.94%   |
| Philips                 | 37        | 0.89%   |
| Ancor Communications    | 37        | 0.89%   |
| BenQ                    | 35        | 0.84%   |
| AOC                     | 35        | 0.84%   |
| InfoVision              | 28        | 0.67%   |
| CSO                     | 24        | 0.58%   |
| ViewSonic               | 22        | 0.53%   |
| TMX                     | 17        | 0.41%   |
| LGD                     | 17        | 0.41%   |
| Iiyama                  | 16        | 0.38%   |
| Sony                    | 14        | 0.34%   |
| LG Philips              | 14        | 0.34%   |
| ASUSTek Computer        | 14        | 0.34%   |
| Panasonic               | 11        | 0.26%   |
| CPT                     | 10        | 0.24%   |
| Toshiba                 | 9         | 0.22%   |
| NEC Computers           | 7         | 0.17%   |
| Unknown                 | 7         | 0.17%   |
| Unknown                 | 6         | 0.14%   |
| Insignia                | 6         | 0.14%   |
| JDI                     | 5         | 0.12%   |
| HannStar                | 5         | 0.12%   |
| Sceptre Tech            | 4         | 0.1%    |
| MSI                     | 4         | 0.1%    |
| LG Electronics          | 4         | 0.1%    |
| KDC                     | 4         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 42        | 1%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 38        | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 38        | 0.9%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 31        | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 20        | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 20        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.38%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 14        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 14        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.33%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 14        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.28%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 11        | 0.26%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 11        | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 11        | 0.26%   |
| AU Optronics LCD Monitor 1920x1080                                       | 11        | 0.26%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 10        | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 344x194mm 15.5-inch         | 10        | 0.24%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1935      | 49.9%   |
| 1366x768 (WXGA)    | 958       | 24.7%   |
| 3840x2160 (4K)     | 167       | 4.31%   |
| 1600x900 (HD+)     | 138       | 3.56%   |
| 2560x1440 (QHD)    | 109       | 2.81%   |
| 1280x800 (WXGA)    | 81        | 2.09%   |
| 1920x1200 (WUXGA)  | 65        | 1.68%   |
| 1440x900 (WXGA+)   | 55        | 1.42%   |
| 2560x1600          | 45        | 1.16%   |
| 2880x1800          | 36        | 0.93%   |
| 1680x1050 (WSXGA+) | 34        | 0.88%   |
| 2560x1080          | 27        | 0.7%    |
| Unknown            | 22        | 0.57%   |
| 3840x2400          | 20        | 0.52%   |
| 2160x1440          | 19        | 0.49%   |
| 1280x1024 (SXGA)   | 19        | 0.49%   |
| 1360x768           | 17        | 0.44%   |
| 3440x1440          | 16        | 0.41%   |
| 3200x1800 (QHD+)   | 13        | 0.34%   |
| 3840x1080          | 10        | 0.26%   |
| 3456x2160          | 9         | 0.23%   |
| 3200x2000          | 9         | 0.23%   |
| 3840x1600          | 6         | 0.15%   |
| 2256x1504          | 6         | 0.15%   |
| 1920x540           | 6         | 0.15%   |
| 3000x2000          | 5         | 0.13%   |
| 1920x1280          | 5         | 0.13%   |
| 3286x1080          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 2880x1920          | 3         | 0.08%   |
| 2520x1680          | 3         | 0.08%   |
| 1600x1200          | 3         | 0.08%   |
| 1024x600           | 3         | 0.08%   |
| 3840x1200          | 2         | 0.05%   |
| 3840x1100          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2560x1700          | 2         | 0.05%   |
| 800x1280           | 1         | 0.03%   |
| 7680x1080          | 1         | 0.03%   |
| 720x1280           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1783      | 43.13%  |
| 13      | 602       | 14.56%  |
| 14      | 515       | 12.46%  |
| 17      | 254       | 6.14%   |
| 27      | 141       | 3.41%   |
| 24      | 132       | 3.19%   |
| 23      | 112       | 2.71%   |
| 12      | 87        | 2.1%    |
| 21      | 84        | 2.03%   |
| Unknown | 77        | 1.86%   |
| 11      | 50        | 1.21%   |
| 31      | 47        | 1.14%   |
| 16      | 42        | 1.02%   |
| 34      | 36        | 0.87%   |
| 18      | 22        | 0.53%   |
| 19      | 19        | 0.46%   |
| 22      | 18        | 0.44%   |
| 84      | 12        | 0.29%   |
| 20      | 12        | 0.29%   |
| 40      | 10        | 0.24%   |
| 32      | 9         | 0.22%   |
| 26      | 8         | 0.19%   |
| 72      | 7         | 0.17%   |
| 37      | 7         | 0.17%   |
| 54      | 5         | 0.12%   |
| 25      | 5         | 0.12%   |
| 52      | 4         | 0.1%    |
| 28      | 4         | 0.1%    |
| 10      | 4         | 0.1%    |
| 74      | 3         | 0.07%   |
| 49      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 42      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 8       | 2         | 0.05%   |
| 86      | 1         | 0.02%   |
| 75      | 1         | 0.02%   |
| 60      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2626      | 64.05%  |
| 201-300     | 406       | 9.9%    |
| 501-600     | 359       | 8.76%   |
| 351-400     | 301       | 7.34%   |
| 401-500     | 146       | 3.56%   |
| Unknown     | 77        | 1.88%   |
| 601-700     | 70        | 1.71%   |
| 701-800     | 48        | 1.17%   |
| 1501-2000   | 24        | 0.59%   |
| 801-900     | 20        | 0.49%   |
| 1001-1500   | 17        | 0.41%   |
| 901-1000    | 3         | 0.07%   |
| 101-200     | 2         | 0.05%   |
| 1-100       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3066      | 84.58%  |
| 16/10   | 360       | 9.93%   |
| Unknown | 63        | 1.74%   |
| 3/2     | 50        | 1.38%   |
| 21/9    | 46        | 1.27%   |
| 5/4     | 15        | 0.41%   |
| 4/3     | 11        | 0.3%    |
| 32/9    | 7         | 0.19%   |
| 3.40    | 2         | 0.06%   |
| 0.62    | 2         | 0.06%   |
| 6/5     | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1786      | 43.32%  |
| 81-90          | 905       | 21.95%  |
| 201-250        | 287       | 6.96%   |
| 121-130        | 216       | 5.24%   |
| 71-80          | 212       | 5.14%   |
| 301-350        | 146       | 3.54%   |
| 351-500        | 100       | 2.43%   |
| 61-70          | 82        | 1.99%   |
| Unknown        | 77        | 1.87%   |
| 51-60          | 52        | 1.26%   |
| 151-200        | 51        | 1.24%   |
| 251-300        | 40        | 0.97%   |
| More than 1000 | 38        | 0.92%   |
| 131-140        | 31        | 0.75%   |
| 111-120        | 29        | 0.7%    |
| 141-150        | 27        | 0.65%   |
| 501-1000       | 23        | 0.56%   |
| 91-100         | 14        | 0.34%   |
| 41-50          | 4         | 0.1%    |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1843      | 45.48%  |
| 101-120       | 1046      | 25.81%  |
| 51-100        | 585       | 14.44%  |
| 161-240       | 310       | 7.65%   |
| More than 240 | 154       | 3.8%    |
| Unknown       | 77        | 1.9%    |
| 1-50          | 37        | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2866      | 79.81%  |
| 2     | 639       | 17.79%  |
| 3     | 63        | 1.75%   |
| 0     | 16        | 0.45%   |
| 4     | 7         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1959      | 35.46%  |
| Realtek Semiconductor             | 1952      | 35.34%  |
| Qualcomm Atheros                  | 749       | 13.56%  |
| Broadcom                          | 264       | 4.78%   |
| MediaTek                          | 74        | 1.34%   |
| Broadcom Limited                  | 71        | 1.29%   |
| Ralink                            | 44        | 0.8%    |
| TP-Link                           | 33        | 0.6%    |
| Ralink Technology                 | 32        | 0.58%   |
| ASIX Electronics                  | 29        | 0.52%   |
| Marvell Technology Group          | 26        | 0.47%   |
| Sierra Wireless                   | 25        | 0.45%   |
| Xiaomi                            | 24        | 0.43%   |
| Dell                              | 22        | 0.4%    |
| Lenovo                            | 21        | 0.38%   |
| DisplayLink                       | 18        | 0.33%   |
| Hewlett-Packard                   | 15        | 0.27%   |
| Qualcomm                          | 14        | 0.25%   |
| Huawei Technologies               | 14        | 0.25%   |
| JMicron Technology                | 13        | 0.24%   |
| Samsung Electronics               | 12        | 0.22%   |
| Ericsson Business Mobile Networks | 11        | 0.2%    |
| Nvidia                            | 9         | 0.16%   |
| ASUSTek Computer                  | 9         | 0.16%   |
| Qualcomm Atheros Communications   | 7         | 0.13%   |
| Linksys                           | 7         | 0.13%   |
| Fibocom                           | 7         | 0.13%   |
| NetGear                           | 6         | 0.11%   |
| D-Link                            | 6         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.09%   |
| Google                            | 5         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.07%   |
| Edimax Technology                 | 4         | 0.07%   |
| Apple                             | 4         | 0.07%   |
| Quectel Wireless Solutions        | 3         | 0.05%   |
| ZyXEL Communications              | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |
| Motorola PCS                      | 2         | 0.04%   |
| Microsoft                         | 2         | 0.04%   |
| ICS Advent                        | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1255      | 19.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 313       | 4.75%   |
| Intel Wi-Fi 6 AX200                                               | 276       | 4.19%   |
| Intel Wireless 8265 / 8275                                        | 176       | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 169       | 2.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 142       | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 139       | 2.11%   |
| Intel Wireless 7260                                               | 126       | 1.91%   |
| Intel Wireless 7265                                               | 124       | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 121       | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 119       | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 114       | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 113       | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 112       | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 104       | 1.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 92        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 87        | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 83        | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 82        | 1.25%   |
| Intel Wireless 8260                                               | 79        | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 77        | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 72        | 1.09%   |
| Intel Wireless 3165                                               | 64        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 63        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 58        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 44        | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 43        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 42        | 0.64%   |
| Intel Wireless 3160                                               | 41        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 40        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 40        | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 39        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.59%   |
| Intel Wireless-AC 9260                                            | 38        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 38        | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 37        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 37        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 37        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 34        | 0.52%   |
| Intel Centrino Wireless-N 2230                                    | 34        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1906      | 51.98%  |
| Qualcomm Atheros                      | 629       | 17.15%  |
| Realtek Semiconductor                 | 591       | 16.12%  |
| Broadcom                              | 204       | 5.56%   |
| MediaTek                              | 67        | 1.83%   |
| Broadcom Limited                      | 54        | 1.47%   |
| Ralink                                | 44        | 1.2%    |
| Ralink Technology                     | 32        | 0.87%   |
| TP-Link                               | 28        | 0.76%   |
| Sierra Wireless                       | 25        | 0.68%   |
| Dell                                  | 16        | 0.44%   |
| Qualcomm                              | 8         | 0.22%   |
| Qualcomm Atheros Communications       | 7         | 0.19%   |
| Linksys                               | 7         | 0.19%   |
| Fibocom                               | 7         | 0.19%   |
| ASUSTek Computer                      | 7         | 0.19%   |
| NetGear                               | 6         | 0.16%   |
| D-Link                                | 6         | 0.16%   |
| Hewlett-Packard                       | 5         | 0.14%   |
| Edimax Technology                     | 4         | 0.11%   |
| Quectel Wireless Solutions            | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| Apple                                 | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 276       | 7.47%   |
| Intel Wireless 8265 / 8275                                     | 176       | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 169       | 4.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 139       | 3.76%   |
| Intel Wireless 7260                                            | 126       | 3.41%   |
| Intel Wireless 7265                                            | 124       | 3.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 119       | 3.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 114       | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 113       | 3.06%   |
| Intel Wi-Fi 6 AX201                                            | 112       | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 104       | 2.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 92        | 2.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 87        | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 83        | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 82        | 2.22%   |
| Intel Wireless 8260                                            | 79        | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 77        | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 72        | 1.95%   |
| Intel Wireless 3165                                            | 64        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 63        | 1.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 58        | 1.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 44        | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 43        | 1.16%   |
| Intel Wireless 3160                                            | 41        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 40        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 40        | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 39        | 1.06%   |
| Intel Wireless-AC 9260                                         | 38        | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 37        | 1%      |
| Broadcom BCM43142 802.11b/g/n                                  | 37        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 34        | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 34        | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 31        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 30        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                 | 27        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 23        | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 22        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 21        | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 21        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1737      | 61.73%  |
| Intel                                  | 566       | 20.11%  |
| Qualcomm Atheros                       | 187       | 6.65%   |
| Broadcom                               | 95        | 3.38%   |
| ASIX Electronics                       | 29        | 1.03%   |
| Marvell Technology Group               | 26        | 0.92%   |
| Xiaomi                                 | 23        | 0.82%   |
| Lenovo                                 | 21        | 0.75%   |
| Broadcom Limited                       | 20        | 0.71%   |
| DisplayLink                            | 18        | 0.64%   |
| JMicron Technology                     | 13        | 0.46%   |
| Samsung Electronics                    | 11        | 0.39%   |
| Nvidia                                 | 9         | 0.32%   |
| MediaTek                               | 7         | 0.25%   |
| Qualcomm                               | 6         | 0.21%   |
| Huawei Technologies                    | 6         | 0.21%   |
| TP-Link                                | 5         | 0.18%   |
| Google                                 | 5         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.14%   |
| Hewlett-Packard                        | 3         | 0.11%   |
| Apple                                  | 3         | 0.11%   |
| Spreadtrum Communications              | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| ICS Advent                             | 2         | 0.07%   |
| Attansic Technology                    | 2         | 0.07%   |
| ASUSTek Computer                       | 2         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1255      | 44%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 313       | 10.97%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 142       | 4.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 121       | 4.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 42        | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 1.37%   |
| Intel Ethernet Connection (4) I219-V                              | 37        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 23        | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 20        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19        | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 18        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 17        | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 16        | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 14        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 13        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.35%   |
| Intel Ethernet Connection I217-V                                  | 10        | 0.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3480      | 55.98%  |
| Ethernet | 2699      | 43.42%  |
| Modem    | 35        | 0.56%   |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3019      | 81.42%  |
| Ethernet | 689       | 18.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2457      | 69.72%  |
| 1     | 1003      | 28.46%  |
| 0     | 37        | 1.05%   |
| 3     | 27        | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3008      | 84.14%  |
| Yes  | 567       | 15.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1553      | 53.42%  |
| Realtek Semiconductor           | 344       | 11.83%  |
| Qualcomm Atheros Communications | 295       | 10.15%  |
| IMC Networks                    | 150       | 5.16%   |
| Lite-On Technology              | 131       | 4.51%   |
| Broadcom                        | 97        | 3.34%   |
| Foxconn / Hon Hai               | 71        | 2.44%   |
| Apple                           | 71        | 2.44%   |
| Realtek                         | 36        | 1.24%   |
| Cambridge Silicon Radio         | 31        | 1.07%   |
| Dell                            | 24        | 0.83%   |
| Ralink                          | 23        | 0.79%   |
| Hewlett-Packard                 | 17        | 0.58%   |
| Toshiba                         | 13        | 0.45%   |
| Foxconn International           | 9         | 0.31%   |
| Opticis                         | 7         | 0.24%   |
| ASUSTek Computer                | 7         | 0.24%   |
| Ralink Technology               | 6         | 0.21%   |
| Alps Electric                   | 5         | 0.17%   |
| Askey Computer                  | 4         | 0.14%   |
| MediaTek                        | 3         | 0.1%    |
| Fujitsu                         | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| USI                             | 1         | 0.03%   |
| TP-Link                         | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 565       | 19.42%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 271       | 9.31%   |
| Intel AX200 Bluetooth                               | 265       | 9.11%   |
| Intel AX201 Bluetooth                               | 249       | 8.56%   |
| Realtek Bluetooth Radio                             | 213       | 7.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 146       | 5.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 86        | 2.96%   |
| IMC Networks Bluetooth Radio                        | 60        | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 58        | 1.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 47        | 1.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.44%   |
| Intel AX210 Bluetooth                               | 41        | 1.41%   |
| Apple Bluetooth Host Controller                     | 38        | 1.31%   |
| Lite-On Bluetooth Device                            | 37        | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.27%   |
| Realtek Bluetooth Radio                             | 36        | 1.24%   |
| IMC Networks Bluetooth Device                       | 36        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 35        | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 1.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 29        | 1%      |
| Apple Bluetooth USB Host Controller                 | 27        | 0.93%   |
| IMC Networks Wireless_Device                        | 26        | 0.89%   |
| Ralink RT3290 Bluetooth                             | 23        | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 20        | 0.69%   |
| Intel Bluetooth Device                              | 20        | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 15        | 0.52%   |
| Realtek RTL8821A Bluetooth                          | 15        | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.45%   |
| Lite-On Wireless_Device                             | 12        | 0.41%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 9         | 0.31%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2689      | 62.17%  |
| AMD                                  | 848       | 19.61%  |
| Nvidia                               | 501       | 11.58%  |
| C-Media Electronics                  | 35        | 0.81%   |
| Realtek Semiconductor                | 25        | 0.58%   |
| Logitech                             | 23        | 0.53%   |
| Lenovo                               | 22        | 0.51%   |
| GN Netcom                            | 17        | 0.39%   |
| Kingston Technology                  | 13        | 0.3%    |
| JMTek                                | 12        | 0.28%   |
| Plantronics                          | 10        | 0.23%   |
| Texas Instruments                    | 9         | 0.21%   |
| SteelSeries ApS                      | 9         | 0.21%   |
| Generalplus Technology               | 8         | 0.18%   |
| Apple                                | 8         | 0.18%   |
| Focusrite-Novation                   | 6         | 0.14%   |
| Razer USA                            | 5         | 0.12%   |
| GYROCOM C&C                          | 5         | 0.12%   |
| Samson Technologies                  | 4         | 0.09%   |
| Hewlett-Packard                      | 4         | 0.09%   |
| Creative Technology                  | 4         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.07%   |
| Sennheiser Communications            | 3         | 0.07%   |
| RODE Microphones                     | 3         | 0.07%   |
| Huawei Technologies                  | 3         | 0.07%   |
| Corsair                              | 3         | 0.07%   |
| Sony                                 | 2         | 0.05%   |
| Samsung Electronics                  | 2         | 0.05%   |
| DCMT Technology                      | 2         | 0.05%   |
| Cambridge Silicon Radio              | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| ASUSTek Computer                     | 2         | 0.05%   |
| Astro Gaming                         | 2         | 0.05%   |
| Alesis                               | 2         | 0.05%   |
| Yealink Network Technology           | 1         | 0.02%   |
| Yamaha                               | 1         | 0.02%   |
| VIA Technologies                     | 1         | 0.02%   |
| Trust                                | 1         | 0.02%   |
| TC Electronic                        | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 587       | 10.87%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 443       | 8.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 297       | 5.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 291       | 5.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 212       | 3.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 182       | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 166       | 3.08%   |
| Intel 8 Series HD Audio Controller                                                                | 157       | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 156       | 2.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 153       | 2.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 152       | 2.82%   |
| Intel Broadwell-U Audio Controller                                                                | 141       | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 140       | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 124       | 2.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 105       | 1.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 101       | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 95        | 1.76%   |
| Intel CM238 HD Audio Controller                                                                   | 95        | 1.76%   |
| AMD FCH Azalia Controller                                                                         | 90        | 1.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 79        | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 71        | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 71        | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 66        | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 65        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 63        | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 56        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 54        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 47        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 41        | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 36        | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 35        | 0.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 33        | 0.61%   |
| AMD High Definition Audio Controller                                                              | 33        | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 32        | 0.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 32        | 0.59%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 31        | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 30        | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 30        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 841       | 31.89%  |
| SK hynix            | 562       | 21.31%  |
| Micron Technology   | 368       | 13.96%  |
| Kingston            | 237       | 8.99%   |
| Crucial             | 120       | 4.55%   |
| Unknown             | 97        | 3.68%   |
| Ramaxel Technology  | 62        | 2.35%   |
| A-DATA Technology   | 61        | 2.31%   |
| Elpida              | 45        | 1.71%   |
| Corsair             | 35        | 1.33%   |
| Nanya Technology    | 30        | 1.14%   |
| G.Skill             | 23        | 0.87%   |
| Smart               | 17        | 0.64%   |
| GOODRAM             | 16        | 0.61%   |
| Unknown (ABCD)      | 15        | 0.57%   |
| Transcend           | 14        | 0.53%   |
| Patriot             | 12        | 0.46%   |
| Team                | 9         | 0.34%   |
| Unknown             | 8         | 0.3%    |
| Apacer              | 7         | 0.27%   |
| ASint Technology    | 6         | 0.23%   |
| AMD                 | 5         | 0.19%   |
| Teikon              | 4         | 0.15%   |
| Goldkey             | 4         | 0.15%   |
| Smart Brazil        | 3         | 0.11%   |
| Silicon Power       | 3         | 0.11%   |
| SHARETRONIC         | 3         | 0.11%   |
| Avant               | 3         | 0.11%   |
| Atermiter           | 3         | 0.11%   |
| Timetec             | 2         | 0.08%   |
| Qumo                | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| Kllisre             | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x8AF1)    | 1         | 0.04%   |
| Unknown (0x0B6B)    | 1         | 0.04%   |
| Unknown (0x02BA)    | 1         | 0.04%   |
| Unknown (08B5)      | 1         | 0.04%   |
| Unknown (08AE)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 57        | 2.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 52        | 1.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 1.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 1.26%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 1.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 1.12%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 28        | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 26        | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 0.9%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.9%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.9%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.83%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 23        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.65%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 13        | 0.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 13        | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 12        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 12        | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.4%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1220      | 55.38%  |
| DDR3    | 670       | 30.41%  |
| LPDDR4  | 114       | 5.17%   |
| LPDDR3  | 100       | 4.54%   |
| SDRAM   | 33        | 1.5%    |
| DDR2    | 31        | 1.41%   |
| DDR5    | 18        | 0.82%   |
| LPDDR5  | 9         | 0.41%   |
| Unknown | 4         | 0.18%   |
| DRAM    | 2         | 0.09%   |
| DDR     | 2         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1911      | 86.43%  |
| Row Of Chips | 269       | 12.17%  |
| Chip         | 17        | 0.77%   |
| Unknown      | 8         | 0.36%   |
| DIMM         | 6         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1055      | 43.85%  |
| 4096  | 757       | 31.46%  |
| 16384 | 321       | 13.34%  |
| 2048  | 190       | 7.9%    |
| 32768 | 57        | 2.37%   |
| 1024  | 25        | 1.04%   |
| 512   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 609       | 25.26%  |
| 1600    | 516       | 21.4%   |
| 3200    | 446       | 18.5%   |
| 2400    | 208       | 8.63%   |
| 2133    | 152       | 6.3%    |
| 1334    | 92        | 3.82%   |
| 1333    | 56        | 2.32%   |
| 3266    | 52        | 2.16%   |
| 4267    | 48        | 1.99%   |
| 1867    | 32        | 1.33%   |
| 4199    | 25        | 1.04%   |
| 1067    | 25        | 1.04%   |
| Unknown | 21        | 0.87%   |
| 4800    | 19        | 0.79%   |
| 667     | 19        | 0.79%   |
| 4266    | 18        | 0.75%   |
| 800     | 11        | 0.46%   |
| 975     | 9         | 0.37%   |
| 6400    | 8         | 0.33%   |
| 1066    | 7         | 0.29%   |
| 8400    | 6         | 0.25%   |
| 3733    | 6         | 0.25%   |
| 2048    | 6         | 0.25%   |
| 2933    | 4         | 0.17%   |
| 1866    | 3         | 0.12%   |
| 3000    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 333     | 2         | 0.08%   |
| 65535   | 1         | 0.04%   |
| 3600    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 666     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 29.63%  |
| Seiko Epson         | 6         | 22.22%  |
| Brother Industries  | 4         | 14.81%  |
| Canon               | 3         | 11.11%  |
| Samsung Electronics | 2         | 7.41%   |
| Xiaomi              | 1         | 3.7%    |
| Sagem               | 1         | 3.7%    |
| Kyocera             | 1         | 3.7%    |
| Dymo-CoStar         | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| HP ENVY 4520 series                                    | 2         | 7.41%   |
| Brother HL-L2300D series                               | 2         | 7.41%   |
| Xiaomi MiMouse 2                                       | 1         | 3.7%    |
| Seiko Epson Printer                                    | 1         | 3.7%    |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 3.7%    |
| Seiko Epson L365 Series                                | 1         | 3.7%    |
| Seiko Epson L355 Series                                | 1         | 3.7%    |
| Seiko Epson ET-2850 Series                             | 1         | 3.7%    |
| Seiko Epson ET-2710 Series                             | 1         | 3.7%    |
| Samsung ML-1865                                        | 1         | 3.7%    |
| Samsung CLX-3180 Series                                | 1         | 3.7%    |
| Sagem Laser Pro LL                                     | 1         | 3.7%    |
| Kyocera FS-1030D printer                               | 1         | 3.7%    |
| HP Officejet 4500 G510g-m                              | 1         | 3.7%    |
| HP LaserJet P1102                                      | 1         | 3.7%    |
| HP Ink Tank Wireless 410 series                        | 1         | 3.7%    |
| HP Ink Tank 310 series                                 | 1         | 3.7%    |
| HP DeskJet 2700 series                                 | 1         | 3.7%    |
| HP DeskJet 1110 series                                 | 1         | 3.7%    |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo            | 1         | 3.7%    |
| Canon TS300 series                                     | 1         | 3.7%    |
| Canon TR4500 series                                    | 1         | 3.7%    |
| Canon G4010 series                                     | 1         | 3.7%    |
| Brother QL-500 label printer                           | 1         | 3.7%    |
| Brother MFC-L2710DW series                             | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 7         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20     | 2         | 28.57%  |
| Canon CanoScan LiDE 220                | 2         | 28.57%  |
| Canon CanoScan LiDE 500F               | 1         | 14.29%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 767       | 23.83%  |
| IMC Networks                           | 452       | 14.05%  |
| Realtek Semiconductor                  | 274       | 8.51%   |
| Microdia                               | 253       | 7.86%   |
| Acer                                   | 240       | 7.46%   |
| Quanta                                 | 185       | 5.75%   |
| Sunplus Innovation Technology          | 165       | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 125       | 3.88%   |
| Lite-On Technology                     | 102       | 3.17%   |
| Syntek                                 | 99        | 3.08%   |
| Suyin                                  | 85        | 2.64%   |
| Apple                                  | 59        | 1.83%   |
| Silicon Motion                         | 52        | 1.62%   |
| Logitech                               | 45        | 1.4%    |
| Bison Electronics                      | 44        | 1.37%   |
| Luxvisions Innotech Limited            | 42        | 1.31%   |
| Alcor Micro                            | 38        | 1.18%   |
| Samsung Electronics                    | 20        | 0.62%   |
| Ricoh                                  | 19        | 0.59%   |
| Lenovo                                 | 14        | 0.44%   |
| Sonix Technology                       | 11        | 0.34%   |
| Microsoft                              | 11        | 0.34%   |
| Primax Electronics                     | 10        | 0.31%   |
| Importek                               | 10        | 0.31%   |
| DigiTech                               | 7         | 0.22%   |
| ALi                                    | 6         | 0.19%   |
| USB Camera                             | 5         | 0.16%   |
| Intel                                  | 5         | 0.16%   |
| Denron                                 | 5         | 0.16%   |
| Z-Star Microelectronics                | 4         | 0.12%   |
| SunplusIT                              | 4         | 0.12%   |
| OmniVision Technologies                | 4         | 0.12%   |
| Genesys Logic                          | 4         | 0.12%   |
| GEMBIRD                                | 4         | 0.12%   |
| Y Media                                | 3         | 0.09%   |
| Creative Technology                    | 3         | 0.09%   |
| ARC International                      | 3         | 0.09%   |
| webcam                                 | 2         | 0.06%   |
| USB Camera CS                          | 2         | 0.06%   |
| Tobii Technology AB                    | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 207       | 6.4%    |
| IMC Networks Integrated Camera                      | 144       | 4.45%   |
| Microdia Integrated_Webcam_HD                       | 133       | 4.11%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 110       | 3.4%    |
| Realtek Integrated_Webcam_HD                        | 103       | 3.18%   |
| Chicony HD WebCam                                   | 83        | 2.57%   |
| Acer Integrated Camera                              | 67        | 2.07%   |
| Syntek Integrated Camera                            | 64        | 1.98%   |
| Sunplus Integrated_Webcam_HD                        | 53        | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 42        | 1.3%    |
| Lite-On Integrated Camera                           | 38        | 1.18%   |
| Acer HD Webcam                                      | 33        | 1.02%   |
| Quanta HP TrueVision HD Camera                      | 31        | 0.96%   |
| IMC Networks HD Camera                              | 30        | 0.93%   |
| Quanta HD User Facing                               | 29        | 0.9%    |
| Acer Lenovo EasyCamera                              | 28        | 0.87%   |
| Chicony HP HD Camera                                | 27        | 0.83%   |
| Bison Integrated Camera                             | 27        | 0.83%   |
| Lite-On HP HD Camera                                | 26        | 0.8%    |
| Chicony USB2.0 Camera                               | 26        | 0.8%    |
| Chicony HD User Facing                              | 25        | 0.77%   |
| Acer SunplusIT Integrated Camera                    | 25        | 0.77%   |
| Chicony USB2.0 HD UVC WebCam                        | 24        | 0.74%   |
| Microdia Integrated Webcam                          | 23        | 0.71%   |
| Chicony Lenovo EasyCamera                           | 22        | 0.68%   |
| Realtek USB Camera                                  | 21        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.65%   |
| Chicony HP Truevision HD                            | 21        | 0.65%   |
| Chicony EasyCamera                                  | 21        | 0.65%   |
| Syntek Lenovo EasyCamera                            | 20        | 0.62%   |
| Sunplus HD WebCam                                   | 20        | 0.62%   |
| Samsung Galaxy A5 (MTP)                             | 20        | 0.62%   |
| Realtek USB2.0 HD UVC WebCam                        | 20        | 0.62%   |
| Quanta HD Webcam                                    | 19        | 0.59%   |
| IMC Networks HP TrueVision HD Camera                | 19        | 0.59%   |
| Chicony HP Wide Vision HD Camera                    | 19        | 0.59%   |
| Acer EasyCamera                                     | 19        | 0.59%   |
| Quanta VGA WebCam                                   | 18        | 0.56%   |
| Quanta HP Wide Vision HD Camera                     | 18        | 0.56%   |
| Microdia Laptop_Integrated_Webcam_HD                | 18        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 226       | 31.26%  |
| Synaptics                          | 195       | 26.97%  |
| Shenzhen Goodix Technology         | 152       | 21.02%  |
| Elan Microelectronics              | 54        | 7.47%   |
| LighTuning Technology              | 31        | 4.29%   |
| Upek                               | 27        | 3.73%   |
| AuthenTec                          | 20        | 2.77%   |
| STMicroelectronics                 | 7         | 0.97%   |
| Focal-systems.Corp                 | 4         | 0.55%   |
| Samsung Electronics                | 3         | 0.41%   |
| DigitalPersona                     | 2         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.14%   |
| HOLTEK                             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 81        | 11.2%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 8.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 49        | 6.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 42        | 5.81%   |
| Elan ELAN:Fingerprint                                                      | 35        | 4.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 4.7%    |
| Shenzhen Goodix FingerPrint                                                | 29        | 4.01%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 3.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 2.9%    |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.77%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 19        | 2.63%   |
| Elan ELAN:ARM-M4                                                           | 18        | 2.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 16        | 2.21%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 2.07%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.94%   |
| Validity Sensors VFS491                                                    | 14        | 1.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 14        | 1.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.52%   |
| Synaptics UWP WBDI                                                         | 10        | 1.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.24%   |
| Synaptics WBDI                                                             | 9         | 1.24%   |
| Synaptics  WBDI                                                            | 9         | 1.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.24%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.97%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.97%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.97%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.69%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.69%   |
| Synaptics WBDI Device                                                      | 5         | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.69%   |
| AuthenTec AES2810                                                          | 5         | 0.69%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.55%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.55%   |
| Unknown                                                                    | 4         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 87        | 36.86%  |
| Alcor Micro               | 83        | 35.17%  |
| Upek                      | 16        | 6.78%   |
| O2 Micro                  | 16        | 6.78%   |
| Lenovo                    | 16        | 6.78%   |
| Yubico.com                | 8         | 3.39%   |
| Gemalto (was Gemplus)     | 3         | 1.27%   |
| Reiner SCT Kartensysteme  | 1         | 0.42%   |
| OmniKey                   | 1         | 0.42%   |
| Hewlett-Packard           | 1         | 0.42%   |
| Clay Logic                | 1         | 0.42%   |
| C3PO                      | 1         | 0.42%   |
| Aladdin Knowledge Systems | 1         | 0.42%   |
| Advanced Card Systems     | 1         | 0.42%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 83        | 35.17%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 14.83%  |
| Broadcom 5880                                                                | 25        | 10.59%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 6.78%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 6.36%   |
| Broadcom 58200                                                               | 15        | 6.36%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 5.08%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.97%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.85%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.42%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.42%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.42%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.42%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.42%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.42%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.42%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.42%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.42%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.42%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2124      | 59.08%  |
| 1     | 1161      | 32.29%  |
| 2     | 285       | 7.93%   |
| 3     | 22        | 0.61%   |
| 4     | 3         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 708       | 40.43%  |
| Graphics card            | 358       | 20.45%  |
| Chipcard                 | 212       | 12.11%  |
| Multimedia controller    | 140       | 8%      |
| Net/wireless             | 132       | 7.54%   |
| Camera                   | 57        | 3.26%   |
| Net/ethernet             | 47        | 2.68%   |
| Bluetooth                | 35        | 2%      |
| Storage                  | 20        | 1.14%   |
| Card reader              | 15        | 0.86%   |
| Sound                    | 9         | 0.51%   |
| Communication controller | 7         | 0.4%    |
| Modem                    | 4         | 0.23%   |
| Network                  | 3         | 0.17%   |
| Storage/nvme             | 2         | 0.11%   |
| Dvb card                 | 2         | 0.11%   |

