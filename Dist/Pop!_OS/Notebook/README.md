Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 7322

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| HP            | Notebook                    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| Acer          | Swift SF314-512             | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| System76      | Lemur Pro                   | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| Avell High... | A70 HYB                     | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| Dell          | Latitude E7470              | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Acer          | Aspire 7750                 | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| Dell          | Latitude E7240              | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Machcreato... | 14                          | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Machcreato... | 14                          | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Apple         | MacBookPro9,2               | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| Toshiba       | Satellite P755              | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| System76      | Adder WS                    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | X502CA                      | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| HP            | Spectre Pro x360 G1         | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Reliance C... | R141TL5                     | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| Dell          | Inspiron 5559               | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Google        | Blorb                       | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | Inspiron 3583               | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| System76      | Oryx Pro                    | [4b3677634e](https://linux-hardware.org/?probe=4b3677634e) | May 13, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| System76      | Galago Pro                  | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| System76      | Gazelle                     | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| Dell          | Inspiron 5566               | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| Acer          | Aspire A715-72G             | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Dell          | XPS 15 9510                 | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Positivo      | N4350                       | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| ASUSTek       | ZenBook UX431FN             | [3194ab7fa2](https://linux-hardware.org/?probe=3194ab7fa2) | May 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [eaf28f6af4](https://linux-hardware.org/?probe=eaf28f6af4) | May 05, 2023 |
| Toshiba       | TECRA R850                  | [bb41171733](https://linux-hardware.org/?probe=bb41171733) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [5022c3993a](https://linux-hardware.org/?probe=5022c3993a) | May 04, 2023 |
| Dell          | Latitude 7370               | [6beab237df](https://linux-hardware.org/?probe=6beab237df) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| HP            | Unknown                     | [311e275897](https://linux-hardware.org/?probe=311e275897) | May 04, 2023 |
| MSI           | GV62 7RE                    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HP            | Unknown                     | [122c1783c0](https://linux-hardware.org/?probe=122c1783c0) | May 03, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [9322206a7d](https://linux-hardware.org/?probe=9322206a7d) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| System76      | Oryx Pro                    | [8bd4f39eaa](https://linux-hardware.org/?probe=8bd4f39eaa) | May 02, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| System76      | Gazelle                     | [8a8de3e027](https://linux-hardware.org/?probe=8a8de3e027) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| Dell          | Precision 5530              | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| Apple         | MacBookPro11,3              | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| System76      | Gazelle                     | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Alienware     | 13 R3                       | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| HP            | ZBook 15                    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| System76      | Pangolin                    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Samsung       | 760XDA                      | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Razer         | Blade                       | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| Dell          | Latitude E7240              | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| MSI           | GL63 8RC                    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| HP            | 650                         | [bcb4e8d60a](https://linux-hardware.org/?probe=bcb4e8d60a) | Apr 03, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| System76      | Kudu                        | [2baafe374c](https://linux-hardware.org/?probe=2baafe374c) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Sony          | VPCSC1AFM                   | [854b8bfa02](https://linux-hardware.org/?probe=854b8bfa02) | Apr 01, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Lenovo        | Slim 7 16ARH7 82UX          | [cca7093e15](https://linux-hardware.org/?probe=cca7093e15) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Razer         | Blade                       | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| Dell          | Latitude E7240              | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | 17 R4                       | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| MSI           | PS42 8M                     | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Positivo      | N1250                       | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| System76      | Pangolin                    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| Apple         | MacBookPro9,1               | [f85095c103](https://linux-hardware.org/?probe=f85095c103) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Dell          | Inspiron 16 7610            | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | 3115m                       | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [0c4050d1ef](https://linux-hardware.org/?probe=0c4050d1ef) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Dell          | Latitude 5420               | [ea5ac72a44](https://linux-hardware.org/?probe=ea5ac72a44) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [ca5a019457](https://linux-hardware.org/?probe=ca5a019457) | Mar 04, 2023 |
| Apple         | MacBookPro9,2               | [ba908d3339](https://linux-hardware.org/?probe=ba908d3339) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Dell          | System XPS L321X            | [24d0d12eca](https://linux-hardware.org/?probe=24d0d12eca) | Mar 04, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ccda7b2155](https://linux-hardware.org/?probe=ccda7b2155) | Mar 04, 2023 |
| Gigabyte      | AORUS 17 XE4                | [6f6750ee73](https://linux-hardware.org/?probe=6f6750ee73) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [db92a5f137](https://linux-hardware.org/?probe=db92a5f137) | Mar 03, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| System76      | Lemur Pro                   | [e7ed83aaf7](https://linux-hardware.org/?probe=e7ed83aaf7) | Mar 01, 2023 |
| HP            | 15                          | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Dell          | Precision 3571              | [40348190de](https://linux-hardware.org/?probe=40348190de) | Mar 01, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [571d426262](https://linux-hardware.org/?probe=571d426262) | Mar 01, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [78ee2e145b](https://linux-hardware.org/?probe=78ee2e145b) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| GPU Compan... | GWTN141-10                  | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | Latitude E7240              | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [75f9e575b3](https://linux-hardware.org/?probe=75f9e575b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f120e182a1](https://linux-hardware.org/?probe=f120e182a1) | Feb 17, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| Dell          | Latitude E4200              | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [91c566ccc9](https://linux-hardware.org/?probe=91c566ccc9) | Feb 16, 2023 |
| Apple         | MacBookPro9,2               | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| Lenovo        | G50-80 80E5                 | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| OriginPC      | Voyager a1600               | [9608c5afd5](https://linux-hardware.org/?probe=9608c5afd5) | Feb 16, 2023 |
| Google        | Blorb                       | [286353731c](https://linux-hardware.org/?probe=286353731c) | Feb 16, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [1b89c43b58](https://linux-hardware.org/?probe=1b89c43b58) | Feb 16, 2023 |
| HP            | EliteBook 850 G2            | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [5c4a26ada0](https://linux-hardware.org/?probe=5c4a26ada0) | Feb 14, 2023 |
| Dell          | Precision M3800             | [98b54858cb](https://linux-hardware.org/?probe=98b54858cb) | Feb 14, 2023 |
| Dell          | Inspiron 15 3511            | [1028ef9686](https://linux-hardware.org/?probe=1028ef9686) | Feb 14, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| Lenovo        | ThinkPad T410 2522G76       | [b15d4051cd](https://linux-hardware.org/?probe=b15d4051cd) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [d38212ee96](https://linux-hardware.org/?probe=d38212ee96) | Feb 13, 2023 |
| Apple         | MacBookPro11,2              | [2314b98760](https://linux-hardware.org/?probe=2314b98760) | Feb 12, 2023 |
| Apple         | MacBookPro12,1              | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Haier         | GG1500A                     | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Dell          | Latitude XT2                | [9b98bf4722](https://linux-hardware.org/?probe=9b98bf4722) | Feb 12, 2023 |
| Dell          | Precision M4700             | [1a44cb5ef9](https://linux-hardware.org/?probe=1a44cb5ef9) | Feb 11, 2023 |
| Apple         | MacBookPro11,1              | [fb407bfc13](https://linux-hardware.org/?probe=fb407bfc13) | Feb 11, 2023 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [322a9d340e](https://linux-hardware.org/?probe=322a9d340e) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [ab07f075d8](https://linux-hardware.org/?probe=ab07f075d8) | Feb 11, 2023 |
| Apple         | MacBook8,1                  | [2f1c5b90a8](https://linux-hardware.org/?probe=2f1c5b90a8) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [24cb179c5a](https://linux-hardware.org/?probe=24cb179c5a) | Feb 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [9cbcfdd748](https://linux-hardware.org/?probe=9cbcfdd748) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [d0cc5f80fc](https://linux-hardware.org/?probe=d0cc5f80fc) | Feb 09, 2023 |
| HP            | EliteBook 840 G5            | [39dbdb0fa9](https://linux-hardware.org/?probe=39dbdb0fa9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [74dd2176ff](https://linux-hardware.org/?probe=74dd2176ff) | Feb 09, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [93afe9ddeb](https://linux-hardware.org/?probe=93afe9ddeb) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | [edc6b0a3af](https://linux-hardware.org/?probe=edc6b0a3af) | Feb 09, 2023 |
| Dell          | XPS 13 9360                 | [db7e89340f](https://linux-hardware.org/?probe=db7e89340f) | Feb 09, 2023 |
| System76      | Lemur Pro                   | [94cf78a9d9](https://linux-hardware.org/?probe=94cf78a9d9) | Feb 08, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | UX430UNR                    | [96d7a1938a](https://linux-hardware.org/?probe=96d7a1938a) | Feb 06, 2023 |
| Acer          | Swift SF114-34              | [28aad1fae5](https://linux-hardware.org/?probe=28aad1fae5) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| Acer          | Swift SF114-34              | [ea8a0e0617](https://linux-hardware.org/?probe=ea8a0e0617) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Alienware     | 17 R5                       | [7f5f8bdb1f](https://linux-hardware.org/?probe=7f5f8bdb1f) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK T902               | [9c92a1772d](https://linux-hardware.org/?probe=9c92a1772d) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [a705eb3101](https://linux-hardware.org/?probe=a705eb3101) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [7a80b2d6d7](https://linux-hardware.org/?probe=7a80b2d6d7) | Feb 05, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [e5e8537cef](https://linux-hardware.org/?probe=e5e8537cef) | Feb 05, 2023 |
| HP            | Laptop 15-bw0xx             | [0cb9ba3cf9](https://linux-hardware.org/?probe=0cb9ba3cf9) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| HP            | Notebook                    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Dell          | G15 5515                    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Dell          | Latitude 3520               | [ce594f431c](https://linux-hardware.org/?probe=ce594f431c) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [448d3800ac](https://linux-hardware.org/?probe=448d3800ac) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| Dell          | Latitude E7240              | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Haier         | GG1500A                     | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| Acer          | Aspire A315-59              | [704c6e370c](https://linux-hardware.org/?probe=704c6e370c) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Apple         | MacBookPro8,1               | [c441c159c1](https://linux-hardware.org/?probe=c441c159c1) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Acer          | Swift SF114-32              | [96b48bebd2](https://linux-hardware.org/?probe=96b48bebd2) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| Dell          | Precision 3571              | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [8db619716a](https://linux-hardware.org/?probe=8db619716a) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7019bd88e0](https://linux-hardware.org/?probe=7019bd88e0) | Feb 01, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | Latitude E7240              | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| System76      | Lemur Pro                   | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| Dell          | Latitude E7240              | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| HP            | ProBook 6550b               | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [f201c986f0](https://linux-hardware.org/?probe=f201c986f0) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| HP            | Notebook                    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [641654df50](https://linux-hardware.org/?probe=641654df50) | Jan 19, 2023 |
| Dell          | Latitude E7240              | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| Razer         | Blade                       | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Framework     | Laptop                      | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| Acer          | Aspire 5625G                | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| Apple         | MacBook8,1                  | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Dell          | Latitude E7240              | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| Dell          | Latitude E7240              | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| System76      | Bonobo WS                   | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [1178b43f82](https://linux-hardware.org/?probe=1178b43f82) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Dell          | Latitude E7240              | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| System76      | Lemur Pro                   | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 1660      | 31.48%  |
| Pop!_OS 20.04 | 1150      | 21.81%  |
| Pop!_OS 21.04 | 960       | 18.21%  |
| Pop!_OS 20.10 | 856       | 16.23%  |
| Pop!_OS 21.10 | 600       | 11.38%  |
| Pop!_OS 19.10 | 30        | 0.57%   |
| Pop!_OS 18.04 | 7         | 0.13%   |
| Pop!_OS 19.04 | 6         | 0.11%   |
| Pop!_OS 18.10 | 4         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 5020      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 442       | 7.84%   |
| 5.8.0-7630-generic       | 381       | 6.75%   |
| 5.4.0-7634-generic       | 346       | 6.13%   |
| 6.2.6-76060206-generic   | 314       | 5.57%   |
| 5.19.0-76051900-generic  | 272       | 4.82%   |
| 6.0.12-76060006-generic  | 262       | 4.64%   |
| 5.13.0-7614-generic      | 262       | 4.64%   |
| 5.4.0-7642-generic       | 256       | 4.54%   |
| 5.17.5-76051705-generic  | 250       | 4.43%   |
| 5.8.0-7642-generic       | 242       | 4.29%   |
| 5.11.0-7614-generic      | 227       | 4.02%   |
| 5.13.0-7620-generic      | 218       | 3.86%   |
| 6.0.6-76060006-generic   | 162       | 2.87%   |
| 5.15.15-76051515-generic | 154       | 2.73%   |
| 5.16.11-76051611-generic | 138       | 2.45%   |
| 5.11.0-7612-generic      | 128       | 2.27%   |
| 5.15.5-76051505-generic  | 123       | 2.18%   |
| 5.18.10-76051810-generic | 122       | 2.16%   |
| 5.8.0-7625-generic       | 105       | 1.86%   |
| 5.17.15-76051715-generic | 105       | 1.86%   |
| 5.11.0-7633-generic      | 99        | 1.76%   |
| 5.15.8-76051508-generic  | 98        | 1.74%   |
| 5.16.19-76051619-generic | 96        | 1.7%    |
| 5.16.15-76051615-generic | 92        | 1.63%   |
| 5.4.0-7626-generic       | 84        | 1.49%   |
| 6.2.0-76060200-generic   | 75        | 1.33%   |
| 5.15.11-76051511-generic | 63        | 1.12%   |
| 6.0.2-76060002-generic   | 59        | 1.05%   |
| 5.15.23-76051523-generic | 56        | 0.99%   |
| 6.1.11-76060111-generic  | 54        | 0.96%   |
| 5.4.0-7625-generic       | 44        | 0.78%   |
| 5.4.0-7629-generic       | 35        | 0.62%   |
| 6.0.3-76060003-generic   | 23        | 0.41%   |
| 5.19.16-76051916-generic | 21        | 0.37%   |
| 5.3.0-7625-generic       | 10        | 0.18%   |
| 5.3.0-7648-generic       | 6         | 0.11%   |
| 5.11.0-051100-generic    | 6         | 0.11%   |
| 5.3.0-7642-generic       | 4         | 0.07%   |
| 5.3.0-7629-generic       | 4         | 0.07%   |
| 5.3.0-20-generic         | 4         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 874       | 15.78%  |
| 5.4.0   | 744       | 13.44%  |
| 5.8.0   | 698       | 12.61%  |
| 5.13.0  | 467       | 8.43%   |
| 6.2.6   | 315       | 5.69%   |
| 5.19.0  | 275       | 4.97%   |
| 6.0.12  | 263       | 4.75%   |
| 5.17.5  | 253       | 4.57%   |
| 6.0.6   | 162       | 2.93%   |
| 5.15.15 | 154       | 2.78%   |
| 5.16.11 | 138       | 2.49%   |
| 5.15.5  | 123       | 2.22%   |
| 5.18.10 | 122       | 2.2%    |
| 5.17.15 | 105       | 1.9%    |
| 5.15.8  | 98        | 1.77%   |
| 5.16.19 | 96        | 1.73%   |
| 5.16.15 | 92        | 1.66%   |
| 6.2.0   | 75        | 1.35%   |
| 5.15.11 | 63        | 1.14%   |
| 6.0.2   | 60        | 1.08%   |
| 5.15.23 | 56        | 1.01%   |
| 6.1.11  | 54        | 0.98%   |
| 5.3.0   | 32        | 0.58%   |
| 6.0.3   | 23        | 0.42%   |
| 5.19.16 | 21        | 0.38%   |
| 5.0.0   | 6         | 0.11%   |
| 4.18.0  | 6         | 0.11%   |
| 5.7.0   | 4         | 0.07%   |
| 5.15.0  | 4         | 0.07%   |
| 5.8.6   | 3         | 0.05%   |
| 5.8.11  | 3         | 0.05%   |
| 5.7.1   | 3         | 0.05%   |
| 5.14.0  | 3         | 0.05%   |
| 5.12.14 | 3         | 0.05%   |
| 5.10.0  | 3         | 0.05%   |
| 6.2.11  | 2         | 0.04%   |
| 6.1.9   | 2         | 0.04%   |
| 6.1.0   | 2         | 0.04%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 880       | 16.05%  |
| 5.4     | 745       | 13.59%  |
| 5.8     | 712       | 12.99%  |
| 6.0     | 494       | 9.01%   |
| 5.15    | 494       | 9.01%   |
| 5.13    | 478       | 8.72%   |
| 6.2     | 392       | 7.15%   |
| 5.17    | 358       | 6.53%   |
| 5.16    | 324       | 5.91%   |
| 5.19    | 298       | 5.43%   |
| 5.18    | 126       | 2.3%    |
| 6.1     | 61        | 1.11%   |
| 5.3     | 32        | 0.58%   |
| 5.10    | 18        | 0.33%   |
| 5.12    | 13        | 0.24%   |
| 5.7     | 11        | 0.2%    |
| 5.14    | 11        | 0.2%    |
| 5.9     | 9         | 0.16%   |
| 5.6     | 7         | 0.13%   |
| 4.18    | 7         | 0.13%   |
| 5.0     | 6         | 0.11%   |
| 6.3     | 4         | 0.07%   |
| 4.15    | 2         | 0.04%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 5020      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4868      | 96.47%  |
| KDE5            | 43        | 0.85%   |
| Unknown         | 40        | 0.79%   |
| KDE             | 25        | 0.5%    |
| X-Cinnamon      | 16        | 0.32%   |
| GNOME Flashback | 10        | 0.2%    |
| XFCE            | 9         | 0.18%   |
| MATE            | 9         | 0.18%   |
| LXQt            | 8         | 0.16%   |
| Unity           | 6         | 0.12%   |
| Cinnamon        | 6         | 0.12%   |
| Budgie          | 4         | 0.08%   |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4853      | 96.21%  |
| Wayland | 168       | 3.33%   |
| Unknown | 16        | 0.32%   |
| Tty     | 7         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3803      | 74.94%  |
| GDM     | 774       | 15.25%  |
| GDM3    | 482       | 9.5%    |
| SDDM    | 9         | 0.18%   |
| TDM     | 5         | 0.1%    |
| LightDM | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2918      | 57.77%  |
| pt_BR   | 370       | 7.33%   |
| en_GB   | 351       | 6.95%   |
| de_DE   | 214       | 4.24%   |
| C       | 130       | 2.57%   |
| it_IT   | 104       | 2.06%   |
| en_AU   | 101       | 2%      |
| es_ES   | 99        | 1.96%   |
| fr_FR   | 98        | 1.94%   |
| en_CA   | 87        | 1.72%   |
| ru_RU   | 71        | 1.41%   |
| Unknown | 52        | 1.03%   |
| pt_PT   | 44        | 0.87%   |
| pl_PL   | 44        | 0.87%   |
| sv_SE   | 33        | 0.65%   |
| en_IN   | 31        | 0.61%   |
| nb_NO   | 23        | 0.46%   |
| nl_NL   | 22        | 0.44%   |
| en_ZA   | 20        | 0.4%    |
| es_MX   | 19        | 0.38%   |
| fi_FI   | 18        | 0.36%   |
| tr_TR   | 16        | 0.32%   |
| en_NZ   | 15        | 0.3%    |
| fr_CA   | 11        | 0.22%   |
| es_AR   | 11        | 0.22%   |
| en_IE   | 11        | 0.22%   |
| cs_CZ   | 10        | 0.2%    |
| en_DK   | 9         | 0.18%   |
| hu_HU   | 8         | 0.16%   |
| hr_HR   | 8         | 0.16%   |
| es_CL   | 8         | 0.16%   |
| de_CH   | 7         | 0.14%   |
| da_DK   | 7         | 0.14%   |
| ro_RO   | 6         | 0.12%   |
| sk_SK   | 5         | 0.1%    |
| es_CO   | 5         | 0.1%    |
| de_AT   | 5         | 0.1%    |
| zh_CN   | 4         | 0.08%   |
| nl_BE   | 4         | 0.08%   |
| en_IL   | 4         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3540      | 69.47%  |
| EFI  | 1556      | 30.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4806      | 95.43%  |
| Btrfs   | 126       | 2.5%    |
| Overlay | 77        | 1.53%   |
| Xfs     | 19        | 0.38%   |
| Unknown | 7         | 0.14%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3771      | 74.44%  |
| GPT     | 1182      | 23.33%  |
| MBR     | 113       | 2.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4911      | 97.56%  |
| Yes       | 123       | 2.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4580      | 90.84%  |
| Yes       | 462       | 9.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 993       | 19.78%  |
| Dell                   | 878       | 17.49%  |
| Hewlett-Packard        | 686       | 13.67%  |
| ASUSTek Computer       | 577       | 11.49%  |
| Acer                   | 394       | 7.85%   |
| Apple                  | 287       | 5.72%   |
| System76               | 182       | 3.63%   |
| MSI                    | 167       | 3.33%   |
| Toshiba                | 101       | 2.01%   |
| Samsung Electronics    | 90        | 1.79%   |
| HUAWEI                 | 62        | 1.24%   |
| Sony                   | 49        | 0.98%   |
| Notebook               | 45        | 0.9%    |
| Google                 | 39        | 0.78%   |
| Alienware              | 39        | 0.78%   |
| Positivo               | 29        | 0.58%   |
| Fujitsu                | 29        | 0.58%   |
| Razer                  | 25        | 0.5%    |
| Gigabyte Technology    | 19        | 0.38%   |
| Timi                   | 18        | 0.36%   |
| PC Specialist          | 16        | 0.32%   |
| TUXEDO                 | 14        | 0.28%   |
| LG Electronics         | 13        | 0.26%   |
| Unknown                | 13        | 0.26%   |
| Medion                 | 12        | 0.24%   |
| GPU Company            | 12        | 0.24%   |
| Framework              | 12        | 0.24%   |
| Packard Bell           | 11        | 0.22%   |
| Avell High Performance | 11        | 0.22%   |
| Teclast                | 7         | 0.14%   |
| Eluktronics            | 7         | 0.14%   |
| Panasonic              | 6         | 0.12%   |
| Intel                  | 6         | 0.12%   |
| HONOR                  | 6         | 0.12%   |
| Gateway                | 6         | 0.12%   |
| Clevo                  | 6         | 0.12%   |
| Chuwi                  | 5         | 0.1%    |
| SLIMBOOK               | 4         | 0.08%   |
| Schenker               | 4         | 0.08%   |
| Quanta                 | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 45        | 0.9%    |
| System76 Lemur Pro                        | 39        | 0.78%   |
| Dell XPS 15 7590                          | 30        | 0.6%    |
| Unknown                                   | 28        | 0.56%   |
| System76 Gazelle                          | 26        | 0.52%   |
| Apple MacBookPro9,2                       | 25        | 0.5%    |
| System76 Galago Pro                       | 22        | 0.44%   |
| Dell XPS 15 9500                          | 22        | 0.44%   |
| Apple MacBookPro12,1                      | 22        | 0.44%   |
| HP Notebook                               | 20        | 0.4%    |
| Apple MacBookPro8,1                       | 20        | 0.4%    |
| HP Pavilion Notebook                      | 19        | 0.38%   |
| Apple MacBookAir7,2                       | 18        | 0.36%   |
| HP Pavilion 15                            | 17        | 0.34%   |
| System76 Darter Pro                       | 16        | 0.32%   |
| HP Pavilion dv6                           | 16        | 0.32%   |
| Dell XPS 15 9560                          | 15        | 0.3%    |
| Dell XPS 15 9570                          | 14        | 0.28%   |
| Dell Latitude E6420                       | 14        | 0.28%   |
| Apple MacBookAir6,2                       | 14        | 0.28%   |
| Lenovo IdeaPad S145-15API 81V7            | 13        | 0.26%   |
| Apple MacBookPro7,1                       | 13        | 0.26%   |
| Lenovo IdeaPad 330-15IKB 81FE             | 11        | 0.22%   |
| HP Pavilion g6                            | 11        | 0.22%   |
| Dell XPS 17 9700                          | 11        | 0.22%   |
| Dell XPS 13 9380                          | 11        | 0.22%   |
| Dell Latitude E7240                       | 11        | 0.22%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 11        | 0.22%   |
| Apple MacBookPro5,5                       | 11        | 0.22%   |
| Apple MacBook5,1                          | 11        | 0.22%   |
| Acer Aspire E5-575G                       | 11        | 0.22%   |
| Samsung 340XAA/350XAA/550XAA              | 10        | 0.2%    |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 10        | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81DE             | 10        | 0.2%    |
| HP Pavilion Laptop 15-cw1xxx              | 10        | 0.2%    |
| Framework Laptop                          | 10        | 0.2%    |
| Dell XPS 13 9370                          | 10        | 0.2%    |
| Dell XPS 13 9310                          | 10        | 0.2%    |
| Dell Inspiron N5110                       | 10        | 0.2%    |
| Apple MacBookPro11,3                      | 10        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 493       | 9.82%   |
| Dell Inspiron      | 285       | 5.68%   |
| Lenovo IdeaPad     | 269       | 5.36%   |
| Acer Aspire        | 268       | 5.34%   |
| Dell Latitude      | 207       | 4.12%   |
| Dell XPS           | 190       | 3.78%   |
| HP Pavilion        | 167       | 3.33%   |
| HP EliteBook       | 106       | 2.11%   |
| HP Laptop          | 100       | 1.99%   |
| ASUS VivoBook      | 92        | 1.83%   |
| Toshiba Satellite  | 87        | 1.73%   |
| ASUS ROG           | 84        | 1.67%   |
| HP ProBook         | 76        | 1.51%   |
| Lenovo Legion      | 74        | 1.47%   |
| Dell Precision     | 62        | 1.24%   |
| Dell Vostro        | 49        | 0.98%   |
| Acer Nitro         | 47        | 0.94%   |
| ASUS ASUS          | 46        | 0.92%   |
| System76 Oryx      | 45        | 0.9%    |
| System76 Lemur     | 42        | 0.84%   |
| Acer Swift         | 39        | 0.78%   |
| HP ENVY            | 35        | 0.7%    |
| Apple MacBookPro11 | 35        | 0.7%    |
| ASUS ZenBook       | 33        | 0.66%   |
| ASUS TUF           | 32        | 0.64%   |
| Apple MacBookPro9  | 32        | 0.64%   |
| HP OMEN            | 29        | 0.58%   |
| System76 Gazelle   | 28        | 0.56%   |
| Apple MacBookPro8  | 28        | 0.56%   |
| Unknown            | 28        | 0.56%   |
| HP ZBook           | 27        | 0.54%   |
| Lenovo ThinkBook   | 26        | 0.52%   |
| System76 Galago    | 25        | 0.5%    |
| Razer Blade        | 25        | 0.5%    |
| Apple MacBookPro5  | 25        | 0.5%    |
| Fujitsu LIFEBOOK   | 22        | 0.44%   |
| Apple MacBookPro12 | 22        | 0.44%   |
| Lenovo Yoga        | 20        | 0.4%    |
| HP Notebook        | 20        | 0.4%    |
| Apple MacBookAir7  | 19        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 633       | 12.61%  |
| 2020    | 593       | 11.81%  |
| 2021    | 513       | 10.22%  |
| 2018    | 483       | 9.62%   |
| 2012    | 361       | 7.19%   |
| 2013    | 330       | 6.57%   |
| 2017    | 307       | 6.12%   |
| 2015    | 301       | 6%      |
| 2011    | 300       | 5.98%   |
| 2016    | 263       | 5.24%   |
| 2014    | 242       | 4.82%   |
| 2022    | 197       | 3.92%   |
| 2010    | 193       | 3.84%   |
| 2009    | 124       | 2.47%   |
| 2008    | 114       | 2.27%   |
| 2007    | 36        | 0.72%   |
| 2023    | 15        | 0.3%    |
| 2006    | 10        | 0.2%    |
| Unknown | 3         | 0.06%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5020      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5017      | 99.94%  |
| Enabled  | 3         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4864      | 96.89%  |
| Yes  | 156       | 3.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1485      | 29.33%  |
| 16.01-24.0  | 1143      | 22.58%  |
| 8.01-16.0   | 932       | 18.41%  |
| 3.01-4.0    | 751       | 14.83%  |
| 32.01-64.0  | 471       | 9.3%    |
| 64.01-256.0 | 102       | 2.01%   |
| 24.01-32.0  | 73        | 1.44%   |
| 1.01-2.0    | 70        | 1.38%   |
| 2.01-3.0    | 36        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1719      | 31.41%  |
| 1.01-2.0   | 1321      | 24.14%  |
| 4.01-8.0   | 1103      | 20.16%  |
| 3.01-4.0   | 1014      | 18.53%  |
| 8.01-16.0  | 261       | 4.77%   |
| 16.01-24.0 | 32        | 0.58%   |
| 0.51-1.0   | 11        | 0.2%    |
| 24.01-32.0 | 10        | 0.18%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3567      | 69.82%  |
| 2      | 1313      | 25.7%   |
| 3      | 172       | 3.37%   |
| 0      | 25        | 0.49%   |
| 4      | 23        | 0.45%   |
| 5      | 7         | 0.14%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3625      | 72%     |
| Yes       | 1410      | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3988      | 79%     |
| No        | 1060      | 21%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4959      | 98.73%  |
| No        | 64        | 1.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4244      | 83.81%  |
| No        | 820       | 16.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1358      | 26.92%  |
| Brazil       | 516       | 10.23%  |
| Germany      | 306       | 6.07%   |
| UK           | 223       | 4.42%   |
| India        | 214       | 4.24%   |
| Canada       | 173       | 3.43%   |
| Italy        | 163       | 3.23%   |
| France       | 145       | 2.87%   |
| Australia    | 117       | 2.32%   |
| Netherlands  | 101       | 2%      |
| Russia       | 93        | 1.84%   |
| Sweden       | 84        | 1.67%   |
| Spain        | 82        | 1.63%   |
| Poland       | 75        | 1.49%   |
| Mexico       | 74        | 1.47%   |
| Portugal     | 72        | 1.43%   |
| Romania      | 56        | 1.11%   |
| Norway       | 55        | 1.09%   |
| Switzerland  | 49        | 0.97%   |
| South Africa | 49        | 0.97%   |
| Turkey       | 46        | 0.91%   |
| Philippines  | 41        | 0.81%   |
| Indonesia    | 40        | 0.79%   |
| Finland      | 40        | 0.79%   |
| Greece       | 38        | 0.75%   |
| Belgium      | 37        | 0.73%   |
| Argentina    | 37        | 0.73%   |
| Austria      | 35        | 0.69%   |
| New Zealand  | 34        | 0.67%   |
| Denmark      | 34        | 0.67%   |
| Czechia      | 28        | 0.56%   |
| Chile        | 28        | 0.56%   |
| Croatia      | 24        | 0.48%   |
| Ireland      | 22        | 0.44%   |
| Hungary      | 22        | 0.44%   |
| Vietnam      | 21        | 0.42%   |
| Malaysia     | 21        | 0.42%   |
| Colombia     | 21        | 0.42%   |
| Bulgaria     | 21        | 0.42%   |
| Japan        | 20        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 55        | 1.04%   |
| Milan          | 32        | 0.61%   |
| Bengaluru      | 32        | 0.61%   |
| Brisbane       | 30        | 0.57%   |
| Sydney         | 28        | 0.53%   |
| Rio de Janeiro | 27        | 0.51%   |
| Dallas         | 26        | 0.49%   |
| Vienna         | 25        | 0.47%   |
| New York       | 25        | 0.47%   |
| Melbourne      | 25        | 0.47%   |
| Paris          | 24        | 0.46%   |
| Moscow         | 24        | 0.46%   |
| London         | 23        | 0.44%   |
| Helsinki       | 22        | 0.42%   |
| Bucharest      | 22        | 0.42%   |
| Berlin         | 22        | 0.42%   |
| Oslo           | 21        | 0.4%    |
| Istanbul       | 21        | 0.4%    |
| Athens         | 21        | 0.4%    |
| Amsterdam      | 21        | 0.4%    |
| Madrid         | 20        | 0.38%   |
| Warsaw         | 19        | 0.36%   |
| Rome           | 19        | 0.36%   |
| Chicago        | 19        | 0.36%   |
| Los Angeles    | 18        | 0.34%   |
| Johannesburg   | 18        | 0.34%   |
| Auckland       | 18        | 0.34%   |
| Zagreb         | 17        | 0.32%   |
| Toronto        | 16        | 0.3%    |
| St Petersburg  | 16        | 0.3%    |
| Mexico City    | 16        | 0.3%    |
| Fortaleza      | 16        | 0.3%    |
| Zurich         | 15        | 0.28%   |
| Stockholm      | 15        | 0.28%   |
| Sofia          | 15        | 0.28%   |
| Lisbon         | 15        | 0.28%   |
| Brasília      | 15        | 0.28%   |
| Seattle        | 14        | 0.27%   |
| Munich         | 14        | 0.27%   |
| Hyderabad      | 14        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1182      | 1595   | 18.31%  |
| WDC                            | 680       | 779    | 10.54%  |
| Seagate                        | 623       | 738    | 9.65%   |
| SanDisk                        | 464       | 607    | 7.19%   |
| Toshiba                        | 408       | 481    | 6.32%   |
| Kingston                       | 344       | 406    | 5.33%   |
| SK hynix                       | 307       | 395    | 4.76%   |
| Unknown                        | 300       | 366    | 4.65%   |
| Crucial                        | 224       | 264    | 3.47%   |
| Intel                          | 212       | 262    | 3.28%   |
| HGST                           | 187       | 216    | 2.9%    |
| Micron Technology              | 176       | 199    | 2.73%   |
| Apple                          | 141       | 151    | 2.18%   |
| Hitachi                        | 102       | 112    | 1.58%   |
| A-DATA Technology              | 94        | 114    | 1.46%   |
| Phison                         | 77        | 94     | 1.19%   |
| China                          | 54        | 62     | 0.84%   |
| PNY                            | 50        | 60     | 0.77%   |
| KIOXIA                         | 50        | 59     | 0.77%   |
| LITEON                         | 43        | 49     | 0.67%   |
| Silicon Motion                 | 42        | 52     | 0.65%   |
| Micron/Crucial Technology      | 42        | 57     | 0.65%   |
| Transcend                      | 36        | 41     | 0.56%   |
| LITEONIT                       | 31        | 43     | 0.48%   |
| ADATA Technology               | 23        | 32     | 0.36%   |
| SPCC                           | 21        | 22     | 0.33%   |
| Phison Electronics             | 19        | 21     | 0.29%   |
| JMicron Technology             | 18        | 24     | 0.28%   |
| Fujitsu                        | 18        | 19     | 0.28%   |
| Team                           | 17        | 21     | 0.26%   |
| KingSpec                       | 17        | 19     | 0.26%   |
| Solid State Storage Technology | 16        | 19     | 0.25%   |
| Union Memory (Shenzhen)        | 15        | 18     | 0.23%   |
| Patriot                        | 15        | 17     | 0.23%   |
| Kingston Technology Company    | 15        | 16     | 0.23%   |
| Unknown                        | 14        | 18     | 0.22%   |
| OCZ                            | 13        | 13     | 0.2%    |
| Netac                          | 13        | 14     | 0.2%    |
| Hewlett-Packard                | 13        | 15     | 0.2%    |
| Intenso                        | 12        | 16     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 107       | 1.58%   |
| Kingston SA400S37240G 240GB SSD                     | 93        | 1.38%   |
| Samsung NVMe SSD Drive 512GB                        | 80        | 1.18%   |
| HGST HTS721010A9E630 1TB                            | 77        | 1.14%   |
| Unknown MMC Card  64GB                              | 71        | 1.05%   |
| Samsung NVMe SSD Drive 1TB                          | 64        | 0.95%   |
| Toshiba MQ01ABD100 1TB                              | 60        | 0.89%   |
| SK hynix NVMe SSD Drive 512GB                       | 59        | 0.87%   |
| Samsung NVMe SSD Drive 256GB                        | 57        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 56        | 0.83%   |
| Unknown MMC Card  32GB                              | 53        | 0.78%   |
| SanDisk NVMe SSD Drive 512GB                        | 53        | 0.78%   |
| Samsung NVMe SSD Drive 500GB                        | 52        | 0.77%   |
| Toshiba MQ04ABF100 1TB                              | 47        | 0.7%    |
| Intel NVMe SSD Drive 512GB                          | 47        | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 45        | 0.67%   |
| WDC WD10SPZX-24Z10 1TB                              | 41        | 0.61%   |
| SanDisk NVMe SSD Drive 1TB                          | 41        | 0.61%   |
| Samsung NVMe SSD Drive 1024GB                       | 40        | 0.59%   |
| Seagate ST9500325AS 500GB                           | 37        | 0.55%   |
| Samsung SSD 860 EVO 500GB                           | 36        | 0.53%   |
| Seagate ST1000LM049-2GH172 1TB                      | 35        | 0.52%   |
| SanDisk NVMe SSD Drive 256GB                        | 35        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                     | 34        | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 33        | 0.49%   |
| Kingston SA400S37480G 480GB SSD                     | 33        | 0.49%   |
| Crucial CT240BX500SSD1 240GB                        | 32        | 0.47%   |
| Unknown MMC Card  128GB                             | 31        | 0.46%   |
| SK hynix NVMe SSD Drive 1024GB                      | 31        | 0.46%   |
| Samsung SSD 850 EVO 250GB                           | 31        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 31        | 0.46%   |
| SK hynix NVMe SSD Drive 256GB                       | 29        | 0.43%   |
| SanDisk NVMe SSD Drive 500GB                        | 29        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                     | 29        | 0.43%   |
| HGST HTS541010A9E680 1TB                            | 29        | 0.43%   |
| Toshiba NVMe SSD Drive 512GB                        | 28        | 0.41%   |
| Samsung SSD 860 EVO 1TB                             | 27        | 0.4%    |
| Apple SSD SM0128G 121GB                             | 27        | 0.4%    |
| Seagate Expansion 1TB                               | 26        | 0.38%   |
| Samsung NVMe SSD Drive 2TB                          | 26        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 596       | 695    | 35.93%  |
| WDC                 | 414       | 457    | 24.95%  |
| Toshiba             | 250       | 282    | 15.07%  |
| HGST                | 187       | 216    | 11.27%  |
| Hitachi             | 102       | 112    | 6.15%   |
| Samsung Electronics | 31        | 32     | 1.87%   |
| Unknown             | 26        | 28     | 1.57%   |
| Fujitsu             | 18        | 19     | 1.08%   |
| Apple               | 16        | 18     | 0.96%   |
| Intenso             | 3         | 6      | 0.18%   |
| ASMT                | 3         | 5      | 0.18%   |
| PHD 3.0             | 2         | 2      | 0.12%   |
| JMicron Technology  | 2         | 6      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| SABRENT             | 1         | 2      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| External            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 472       | 623    | 21.65%  |
| Kingston            | 266       | 300    | 12.2%   |
| SanDisk             | 221       | 272    | 10.14%  |
| Crucial             | 207       | 247    | 9.5%    |
| WDC                 | 138       | 169    | 6.33%   |
| Apple               | 105       | 110    | 4.82%   |
| A-DATA Technology   | 61        | 72     | 2.8%    |
| SK hynix            | 56        | 65     | 2.57%   |
| Micron Technology   | 56        | 61     | 2.57%   |
| China               | 54        | 62     | 2.48%   |
| Toshiba             | 53        | 63     | 2.43%   |
| PNY                 | 49        | 59     | 2.25%   |
| Intel               | 44        | 48     | 2.02%   |
| LITEON              | 40        | 46     | 1.83%   |
| Transcend           | 34        | 39     | 1.56%   |
| LITEONIT            | 31        | 43     | 1.42%   |
| SPCC                | 19        | 20     | 0.87%   |
| KingSpec            | 17        | 19     | 0.78%   |
| Seagate             | 14        | 15     | 0.64%   |
| Patriot             | 14        | 16     | 0.64%   |
| OCZ                 | 13        | 13     | 0.6%    |
| Team                | 11        | 15     | 0.5%    |
| Netac               | 10        | 11     | 0.46%   |
| Hewlett-Packard     | 10        | 12     | 0.46%   |
| Lexar               | 9         | 9      | 0.41%   |
| Corsair             | 9         | 10     | 0.41%   |
| Dogfish             | 8         | 11     | 0.37%   |
| KingDian            | 7         | 8      | 0.32%   |
| Intenso             | 7         | 7      | 0.32%   |
| Apacer              | 7         | 12     | 0.32%   |
| BHT                 | 6         | 6      | 0.28%   |
| TO Exter            | 5         | 5      | 0.23%   |
| Plextor             | 5         | 7      | 0.23%   |
| Mushkin             | 5         | 6      | 0.23%   |
| GOODRAM             | 5         | 6      | 0.23%   |
| ASMT                | 5         | 5      | 0.23%   |
| Teclast             | 4         | 4      | 0.18%   |
| Maxtor              | 4         | 4      | 0.18%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.18%   |
| Gigabyte Technology | 4         | 6      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2125      | 2970   | 34.94%  |
| SSD     | 2019      | 2606   | 33.2%   |
| HDD     | 1607      | 1891   | 26.42%  |
| MMC     | 249       | 302    | 4.09%   |
| Unknown | 82        | 112    | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3176      | 4326   | 55.01%  |
| NVMe | 2118      | 2948   | 36.69%  |
| MMC  | 249       | 302    | 4.31%   |
| SAS  | 230       | 305    | 3.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2285      | 2938   | 63.79%  |
| 0.51-1.0   | 1168      | 1391   | 32.61%  |
| 1.01-2.0   | 111       | 141    | 3.1%    |
| 4.01-10.0  | 12        | 19     | 0.34%   |
| 3.01-4.0   | 4         | 5      | 0.11%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |
| 10.01-20.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1731      | 33.4%   |
| 251-500        | 1469      | 28.35%  |
| 501-1000       | 964       | 18.6%   |
| 1001-2000      | 344       | 6.64%   |
| 51-100         | 257       | 4.96%   |
| 1-20           | 122       | 2.35%   |
| 21-50          | 120       | 2.32%   |
| 2001-3000      | 77        | 1.49%   |
| More than 3000 | 66        | 1.27%   |
| Unknown        | 32        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2114      | 38.9%   |
| 21-50          | 1206      | 22.19%  |
| 101-250        | 710       | 13.07%  |
| 51-100         | 705       | 12.97%  |
| 251-500        | 369       | 6.79%   |
| 501-1000       | 198       | 3.64%   |
| 1001-2000      | 64        | 1.18%   |
| Unknown        | 32        | 0.59%   |
| More than 3000 | 19        | 0.35%   |
| 2001-3000      | 17        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 5         | 5      | 4.13%   |
| HGST HTS725050A7E630 500GB               | 5         | 8      | 4.13%   |
| Seagate ST1000LX015-1U7172 1TB           | 4         | 4      | 3.31%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.31%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 3         | 3      | 2.48%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 2.48%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.48%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.48%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.48%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.65%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.65%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.65%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.65%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.83%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.83%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.83%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.83%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.83%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.83%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.83%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.83%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.83%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.83%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.83%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.83%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.83%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.83%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 1         | 1      | 0.83%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.83%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.83%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.83%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.83%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 0.83%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 0.83%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 29     | 23.14%  |
| WDC                 | 18        | 18     | 14.88%  |
| HGST                | 14        | 17     | 11.57%  |
| Toshiba             | 12        | 13     | 9.92%   |
| SK hynix            | 9         | 11     | 7.44%   |
| Samsung Electronics | 6         | 6      | 4.96%   |
| Hitachi             | 6         | 8      | 4.96%   |
| Kingston            | 5         | 5      | 4.13%   |
| Crucial             | 5         | 5      | 4.13%   |
| A-DATA Technology   | 5         | 5      | 4.13%   |
| Micron Technology   | 4         | 4      | 3.31%   |
| Intel               | 3         | 3      | 2.48%   |
| SanDisk             | 2         | 2      | 1.65%   |
| Team                | 1         | 1      | 0.83%   |
| Lexar               | 1         | 1      | 0.83%   |
| Leven               | 1         | 1      | 0.83%   |
| China               | 1         | 1      | 0.83%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 29     | 38.36%  |
| WDC     | 16        | 16     | 21.92%  |
| HGST    | 14        | 17     | 19.18%  |
| Toshiba | 9         | 9      | 12.33%  |
| Hitachi | 6         | 8      | 8.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 73        | 79     | 60.33%  |
| SSD  | 30        | 33     | 24.79%  |
| NVMe | 18        | 18     | 14.88%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3863      | 6047   | 73.52%  |
| Works    | 1269      | 1703   | 24.15%  |
| Malfunc  | 121       | 130    | 2.3%    |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3352      | 53.32%  |
| Samsung Electronics              | 787       | 12.52%  |
| AMD                              | 622       | 9.9%    |
| SanDisk                          | 361       | 5.74%   |
| SK hynix                         | 250       | 3.98%   |
| Micron Technology                | 120       | 1.91%   |
| Toshiba America Info Systems     | 117       | 1.86%   |
| Phison Electronics               | 99        | 1.57%   |
| Kingston Technology Company      | 92        | 1.46%   |
| Nvidia                           | 78        | 1.24%   |
| ADATA Technology                 | 58        | 0.92%   |
| Micron/Crucial Technology        | 55        | 0.87%   |
| Silicon Motion                   | 52        | 0.83%   |
| KIOXIA                           | 51        | 0.81%   |
| Solid State Storage Technology   | 42        | 0.67%   |
| Union Memory (Shenzhen)          | 30        | 0.48%   |
| Apple                            | 20        | 0.32%   |
| Realtek Semiconductor            | 18        | 0.29%   |
| Marvell Technology Group         | 18        | 0.29%   |
| Seagate Technology               | 12        | 0.19%   |
| Shenzhen Longsys Electronics     | 9         | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.13%   |
| Lite-On Technology               | 7         | 0.11%   |
| Lenovo                           | 6         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 5         | 0.08%   |
| JMicron Technology               | 4         | 0.06%   |
| ASMedia Technology               | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 591       | 8.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 417       | 6.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 400       | 6.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 339       | 5.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 315       | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 279       | 4.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 248       | 3.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 200       | 3.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 155       | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 154       | 2.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 150       | 2.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 129       | 1.96%   |
| Samsung NVMe SSD Controller 980                                                | 125       | 1.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 99        | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 99        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 98        | 1.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 95        | 1.44%   |
| Intel SSD 660P Series                                                          | 95        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 90        | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 89        | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 86        | 1.31%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 86        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 78        | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 66        | 1%      |
| Micron NVMe Storage Controller                                                 | 65        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 54        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 52        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 52        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 51        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 51        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 50        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 49        | 0.74%   |
| Samsung Electronics SATA controller                                            | 48        | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                   | 46        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 44        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 44        | 0.67%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 43        | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 37        | 0.56%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 36        | 0.55%   |
| Micron 2200S NVMe SSD                                                          | 34        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3525      | 55.93%  |
| NVMe | 2114      | 33.54%  |
| RAID | 500       | 7.93%   |
| IDE  | 164       | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4074      | 81.16%  |
| AMD    | 946       | 18.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 126       | 2.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 100       | 1.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 96        | 1.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 91        | 1.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 89        | 1.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 76        | 1.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 75        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 73        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 70        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 68        | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 65        | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 62        | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 61        | 1.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 1.14%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 56        | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 54        | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 54        | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 48        | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 46        | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 45        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 0.86%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 41        | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 39        | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 38        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 37        | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 36        | 0.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 35        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 35        | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 34        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 33        | 0.66%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 33        | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 33        | 0.66%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 32        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 32        | 0.64%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 31        | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 31        | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 31        | 0.62%   |
| Intel 12th Gen Core i7-12700H                 | 29        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1476      | 29.4%   |
| Intel Core i5           | 1270      | 25.3%   |
| Other                   | 436       | 8.69%   |
| Intel Core i3           | 316       | 6.29%   |
| AMD Ryzen 7             | 269       | 5.36%   |
| AMD Ryzen 5             | 264       | 5.26%   |
| Intel Core 2 Duo        | 178       | 3.55%   |
| Intel Celeron           | 165       | 3.29%   |
| AMD Ryzen 9             | 60        | 1.2%    |
| Intel Pentium           | 58        | 1.16%   |
| AMD Ryzen 3             | 57        | 1.14%   |
| AMD A6                  | 51        | 1.02%   |
| Intel Core i9           | 50        | 1%      |
| AMD Ryzen 7 PRO         | 37        | 0.74%   |
| AMD A8                  | 36        | 0.72%   |
| Intel Pentium Dual-Core | 32        | 0.64%   |
| AMD A10                 | 31        | 0.62%   |
| AMD A4                  | 24        | 0.48%   |
| Intel Atom              | 19        | 0.38%   |
| Intel Core 2            | 17        | 0.34%   |
| Intel Xeon              | 13        | 0.26%   |
| Intel Pentium Dual      | 13        | 0.26%   |
| Intel Genuine           | 13        | 0.26%   |
| Intel Core m3           | 12        | 0.24%   |
| AMD Athlon              | 12        | 0.24%   |
| AMD E1                  | 11        | 0.22%   |
| AMD Ryzen 5 PRO         | 10        | 0.2%    |
| AMD E                   | 9         | 0.18%   |
| Intel Pentium Silver    | 8         | 0.16%   |
| AMD E2                  | 7         | 0.14%   |
| Intel Core M            | 6         | 0.12%   |
| AMD Turion 64 X2 Mobile | 6         | 0.12%   |
| AMD FX                  | 6         | 0.12%   |
| AMD A12                 | 6         | 0.12%   |
| Intel Core m5           | 5         | 0.1%    |
| Intel Celeron Dual-Core | 4         | 0.08%   |
| AMD C-60                | 4         | 0.08%   |
| AMD Athlon X2           | 4         | 0.08%   |
| AMD Phenom II           | 3         | 0.06%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2147      | 42.77%  |
| 4      | 1749      | 34.84%  |
| 6      | 517       | 10.3%   |
| 8      | 471       | 9.38%   |
| 14     | 51        | 1.02%   |
| 12     | 28        | 0.56%   |
| 1      | 25        | 0.5%    |
| 10     | 23        | 0.46%   |
| 16     | 5         | 0.1%    |
| 24     | 1         | 0.02%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5020      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4216      | 83.92%  |
| 1      | 808       | 16.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5013      | 99.86%  |
| Unknown        | 7         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3316      | 64.46%  |
| 0x906ea    | 152       | 2.95%   |
| 0x806ea    | 108       | 2.1%    |
| 0x306a9    | 101       | 1.96%   |
| 0x806ec    | 98        | 1.91%   |
| 0x806c1    | 93        | 1.81%   |
| 0x206a7    | 92        | 1.79%   |
| 0x406e3    | 86        | 1.67%   |
| 0x40651    | 80        | 1.56%   |
| 0xa0652    | 75        | 1.46%   |
| 0x806e9    | 61        | 1.19%   |
| 0x306c3    | 56        | 1.09%   |
| 0x906e9    | 53        | 1.03%   |
| 0x0a50000c | 53        | 1.03%   |
| 0x08108102 | 46        | 0.89%   |
| 0x306d4    | 40        | 0.78%   |
| 0x806d1    | 37        | 0.72%   |
| 0x08600106 | 37        | 0.72%   |
| 0x1067a    | 35        | 0.68%   |
| 0x806eb    | 34        | 0.66%   |
| 0x506e3    | 34        | 0.66%   |
| 0x08108109 | 30        | 0.58%   |
| 0x906ed    | 28        | 0.54%   |
| 0x906a3    | 24        | 0.47%   |
| 0x08600104 | 24        | 0.47%   |
| 0x20655    | 22        | 0.43%   |
| 0x08608103 | 21        | 0.41%   |
| 0x706e5    | 20        | 0.39%   |
| 0x08600103 | 18        | 0.35%   |
| 0x06006705 | 17        | 0.33%   |
| 0x0810100b | 15        | 0.29%   |
| 0x706a1    | 13        | 0.25%   |
| 0x0a404101 | 12        | 0.23%   |
| 0x40661    | 11        | 0.21%   |
| 0x10676    | 11        | 0.21%   |
| 0x0a404102 | 10        | 0.19%   |
| 0x07030105 | 10        | 0.19%   |
| 0xa0660    | 9         | 0.17%   |
| 0x0a50000d | 9         | 0.17%   |
| 0x06001119 | 9         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1180      | 23.49%  |
| Haswell          | 448       | 8.92%   |
| SandyBridge      | 359       | 7.15%   |
| IvyBridge        | 342       | 6.81%   |
| Skylake          | 284       | 5.65%   |
| TigerLake        | 231       | 4.6%    |
| Unknown          | 219       | 4.36%   |
| Zen+             | 202       | 4.02%   |
| CometLake        | 193       | 3.84%   |
| Penryn           | 191       | 3.8%    |
| Zen 2            | 188       | 3.74%   |
| Broadwell        | 187       | 3.72%   |
| Zen 3            | 162       | 3.22%   |
| Westmere         | 147       | 2.93%   |
| IceLake          | 99        | 1.97%   |
| Silvermont       | 80        | 1.59%   |
| Core             | 74        | 1.47%   |
| Excavator        | 66        | 1.31%   |
| Goldmont plus    | 62        | 1.23%   |
| Zen              | 50        | 1%      |
| Alderlake Hybrid | 46        | 0.92%   |
| Puma             | 43        | 0.86%   |
| Piledriver       | 37        | 0.74%   |
| Bobcat           | 22        | 0.44%   |
| Goldmont         | 21        | 0.42%   |
| Nehalem          | 17        | 0.34%   |
| Jaguar           | 14        | 0.28%   |
| Steamroller      | 13        | 0.26%   |
| K10 Llano        | 12        | 0.24%   |
| K8 Hammer        | 11        | 0.22%   |
| K10              | 9         | 0.18%   |
| K8 & K10 hybrid  | 8         | 0.16%   |
| Bonnell          | 4         | 0.08%   |
| Tremont          | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3704      | 55.22%  |
| Nvidia                           | 1808      | 26.95%  |
| AMD                              | 1189      | 17.73%  |
| Silicon Integrated Systems [SiS] | 6         | 0.09%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 330       | 4.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 328       | 4.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 314       | 4.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 241       | 3.51%   |
| Intel UHD Graphics 620                                                                   | 222       | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 216       | 3.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 202       | 2.94%   |
| AMD Renoir                                                                               | 178       | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 175       | 2.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 159       | 2.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 152       | 2.21%   |
| Intel HD Graphics 620                                                                    | 150       | 2.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 146       | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 142       | 2.07%   |
| Intel HD Graphics 5500                                                                   | 131       | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 126       | 1.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 121       | 1.76%   |
| Intel HD Graphics 630                                                                    | 118       | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 83        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 1.18%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 81        | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 78        | 1.14%   |
| Intel HD Graphics 530                                                                    | 72        | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 72        | 1.05%   |
| AMD Lucienne                                                                             | 69        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 68        | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 60        | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 59        | 0.86%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 58        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 56        | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 54        | 0.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 54        | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 52        | 0.76%   |
| Nvidia TU117M                                                                            | 49        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47        | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 46        | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 45        | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 41        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2279      | 45.09%  |
| Intel + Nvidia     | 1241      | 24.55%  |
| 1 x AMD            | 681       | 13.47%  |
| 1 x Nvidia         | 323       | 6.39%   |
| AMD + Nvidia       | 220       | 4.35%   |
| Intel + AMD        | 191       | 3.78%   |
| 2 x AMD            | 98        | 1.94%   |
| 2 x Nvidia         | 10        | 0.2%    |
| 1 x SiS            | 6         | 0.12%   |
| Other              | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 1 x S3 Graphics    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3500      | 69.06%  |
| Proprietary | 1438      | 28.37%  |
| Unknown     | 130       | 2.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3827      | 74.91%  |
| 1.01-2.0   | 339       | 6.64%   |
| 3.01-4.0   | 314       | 6.15%   |
| 0.01-0.5   | 204       | 3.99%   |
| 5.01-6.0   | 185       | 3.62%   |
| 7.01-8.0   | 103       | 2.02%   |
| 0.51-1.0   | 95        | 1.86%   |
| 2.01-3.0   | 29        | 0.57%   |
| 8.01-16.0  | 13        | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1040      | 17.88%  |
| Chimei Innolux          | 848       | 14.58%  |
| LG Display              | 807       | 13.87%  |
| BOE                     | 761       | 13.08%  |
| Samsung Electronics     | 529       | 9.09%   |
| Apple                   | 239       | 4.11%   |
| Sharp                   | 212       | 3.64%   |
| Goldstar                | 177       | 3.04%   |
| Dell                    | 172       | 2.96%   |
| PANDA                   | 145       | 2.49%   |
| Chi Mei Optoelectronics | 90        | 1.55%   |
| Lenovo                  | 77        | 1.32%   |
| Acer                    | 61        | 1.05%   |
| AOC                     | 58        | 1%      |
| Hewlett-Packard         | 57        | 0.98%   |
| InfoVision              | 49        | 0.84%   |
| Philips                 | 48        | 0.83%   |
| BenQ                    | 43        | 0.74%   |
| Ancor Communications    | 34        | 0.58%   |
| CSO                     | 33        | 0.57%   |
| ASUSTek Computer        | 33        | 0.57%   |
| ViewSonic               | 21        | 0.36%   |
| TMX                     | 16        | 0.28%   |
| Sony                    | 14        | 0.24%   |
| LG Philips              | 14        | 0.24%   |
| Panasonic               | 12        | 0.21%   |
| Vizio                   | 11        | 0.19%   |
| InnoLux Display         | 10        | 0.17%   |
| Sceptre Tech            | 9         | 0.15%   |
| Iiyama                  | 9         | 0.15%   |
| Toshiba                 | 8         | 0.14%   |
| JDI                     | 8         | 0.14%   |
| MSI                     | 7         | 0.12%   |
| Vestel Elektronik       | 6         | 0.1%    |
| NEC Computers           | 5         | 0.09%   |
| LGD                     | 5         | 0.09%   |
| Hitachi                 | 5         | 0.09%   |
| HannStar                | 5         | 0.09%   |
| TCL                     | 4         | 0.07%   |
| Insignia                | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 56        | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 55        | 0.94%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 49        | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 48        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 46        | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 42        | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 35        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 33        | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 33        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 28        | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch              | 27        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 27        | 0.46%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch       | 26        | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 26        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 24        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 24        | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 23        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 23        | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 22        | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 21        | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 21        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 20        | 0.34%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 18        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 18        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.31%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 17        | 0.29%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 17        | 0.29%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 16        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 16        | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 16        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 16        | 0.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 16        | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 15        | 0.26%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 15        | 0.26%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 15        | 0.26%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 15        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2571      | 47.14%  |
| 1366x768 (WXGA)    | 1382      | 25.34%  |
| 3840x2160 (4K)     | 280       | 5.13%   |
| 1600x900 (HD+)     | 224       | 4.11%   |
| 2560x1440 (QHD)    | 188       | 3.45%   |
| 1280x800 (WXGA)    | 132       | 2.42%   |
| 1920x1200 (WUXGA)  | 105       | 1.93%   |
| 1440x900 (WXGA+)   | 96        | 1.76%   |
| 2560x1600          | 84        | 1.54%   |
| 2880x1800          | 65        | 1.19%   |
| 2560x1080          | 47        | 0.86%   |
| 3840x2400          | 34        | 0.62%   |
| 3440x1440          | 32        | 0.59%   |
| 1680x1050 (WSXGA+) | 31        | 0.57%   |
| 3200x1800 (QHD+)   | 19        | 0.35%   |
| 2160x1440          | 18        | 0.33%   |
| 1360x768           | 18        | 0.33%   |
| 2256x1504          | 14        | 0.26%   |
| 1280x1024 (SXGA)   | 14        | 0.26%   |
| 1920x540           | 13        | 0.24%   |
| 3000x2000          | 10        | 0.18%   |
| 3840x1080          | 9         | 0.17%   |
| 3456x2160          | 6         | 0.11%   |
| 3200x2000          | 6         | 0.11%   |
| 3072x1920          | 6         | 0.11%   |
| Unknown            | 6         | 0.11%   |
| 3840x1100          | 4         | 0.07%   |
| 2560x1700          | 3         | 0.06%   |
| 2304x1440          | 3         | 0.06%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 2240x1400          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x768 (XGA)     | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2441      | 42.01%  |
| 13      | 896       | 15.42%  |
| 14      | 663       | 11.41%  |
| 17      | 425       | 7.31%   |
| 27      | 198       | 3.41%   |
| 24      | 168       | 2.89%   |
| 23      | 143       | 2.46%   |
| 12      | 123       | 2.12%   |
| 21      | 108       | 1.86%   |
| 31      | 84        | 1.45%   |
| 16      | 83        | 1.43%   |
| 11      | 73        | 1.26%   |
| 34      | 69        | 1.19%   |
| 18      | 49        | 0.84%   |
| Unknown | 42        | 0.72%   |
| 19      | 32        | 0.55%   |
| 32      | 22        | 0.38%   |
| 84      | 21        | 0.36%   |
| 40      | 21        | 0.36%   |
| 20      | 18        | 0.31%   |
| 72      | 15        | 0.26%   |
| 22      | 15        | 0.26%   |
| 48      | 10        | 0.17%   |
| 54      | 9         | 0.15%   |
| 25      | 9         | 0.15%   |
| 52      | 6         | 0.1%    |
| 28      | 6         | 0.1%    |
| 35      | 5         | 0.09%   |
| 33      | 5         | 0.09%   |
| 26      | 5         | 0.09%   |
| 10      | 5         | 0.09%   |
| 65      | 4         | 0.07%   |
| 49      | 4         | 0.07%   |
| 47      | 4         | 0.07%   |
| 46      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |
| 37      | 3         | 0.05%   |
| 8       | 2         | 0.03%   |
| 99      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3559      | 61.71%  |
| 201-300        | 640       | 11.1%   |
| 351-400        | 510       | 8.84%   |
| 501-600        | 466       | 8.08%   |
| 401-500        | 213       | 3.69%   |
| 601-700        | 118       | 2.05%   |
| 701-800        | 97        | 1.68%   |
| 1001-1500      | 45        | 0.78%   |
| Unknown        | 42        | 0.73%   |
| 1501-2000      | 38        | 0.66%   |
| 801-900        | 31        | 0.54%   |
| 901-1000       | 3         | 0.05%   |
| 101-200        | 2         | 0.03%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4282      | 84.62%  |
| 16/10   | 569       | 11.25%  |
| 21/9    | 82        | 1.62%   |
| 3/2     | 56        | 1.11%   |
| Unknown | 23        | 0.45%   |
| 5/4     | 17        | 0.34%   |
| 32/9    | 10        | 0.2%    |
| 4/3     | 8         | 0.16%   |
| 3.40    | 4         | 0.08%   |
| 6/5     | 2         | 0.04%   |
| 3.73    | 2         | 0.04%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2429      | 41.88%  |
| 81-90          | 1256      | 21.66%  |
| 121-130        | 385       | 6.64%   |
| 201-250        | 366       | 6.31%   |
| 71-80          | 298       | 5.14%   |
| 301-350        | 202       | 3.48%   |
| 351-500        | 184       | 3.17%   |
| 61-70          | 116       | 2%      |
| 111-120        | 90        | 1.55%   |
| 51-60          | 77        | 1.33%   |
| 151-200        | 75        | 1.29%   |
| More than 1000 | 68        | 1.17%   |
| 251-300        | 55        | 0.95%   |
| 141-150        | 53        | 0.91%   |
| 501-1000       | 49        | 0.84%   |
| Unknown        | 42        | 0.72%   |
| 131-140        | 36        | 0.62%   |
| 91-100         | 10        | 0.17%   |
| 41-50          | 5         | 0.09%   |
| 1-40           | 4         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2501      | 44.01%  |
| 101-120       | 1583      | 27.86%  |
| 51-100        | 785       | 13.81%  |
| 161-240       | 443       | 7.8%    |
| More than 240 | 256       | 4.5%    |
| 1-50          | 73        | 1.28%   |
| Unknown       | 42        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3985      | 77.53%  |
| 2     | 877       | 17.06%  |
| 0     | 167       | 3.25%   |
| 3     | 104       | 2.02%   |
| 4     | 7         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2741      | 33.85%  |
| Intel                             | 2692      | 33.24%  |
| Qualcomm Atheros                  | 1106      | 13.66%  |
| Broadcom                          | 542       | 6.69%   |
| Broadcom Limited                  | 157       | 1.94%   |
| MediaTek                          | 134       | 1.65%   |
| Marvell Technology Group          | 68        | 0.84%   |
| Ralink                            | 56        | 0.69%   |
| Nvidia                            | 56        | 0.69%   |
| ASIX Electronics                  | 56        | 0.69%   |
| TP-Link                           | 50        | 0.62%   |
| Ralink Technology                 | 41        | 0.51%   |
| Samsung Electronics               | 39        | 0.48%   |
| DisplayLink                       | 31        | 0.38%   |
| Dell                              | 26        | 0.32%   |
| Lenovo                            | 25        | 0.31%   |
| Xiaomi                            | 22        | 0.27%   |
| Sierra Wireless                   | 22        | 0.27%   |
| Ericsson Business Mobile Networks | 22        | 0.27%   |
| Qualcomm                          | 21        | 0.26%   |
| JMicron Technology                | 18        | 0.22%   |
| Hewlett-Packard                   | 14        | 0.17%   |
| Google                            | 14        | 0.17%   |
| ASUSTek Computer                  | 13        | 0.16%   |
| OnePlus Technology (Shenzhen)     | 12        | 0.15%   |
| NetGear                           | 11        | 0.14%   |
| Huawei Technologies               | 10        | 0.12%   |
| D-Link                            | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.1%    |
| OPPO Electronics                  | 8         | 0.1%    |
| Motorola PCS                      | 8         | 0.1%    |
| Linksys                           | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| Fibocom                           | 5         | 0.06%   |
| Edimax Technology                 | 5         | 0.06%   |
| Microsoft                         | 4         | 0.05%   |
| Qualcomm Atheros Communications   | 3         | 0.04%   |
| U-Blox                            | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Shenzhen Goodix Technology        | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1752      | 18.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 429       | 4.5%    |
| Intel Wi-Fi 6 AX200                                               | 338       | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 240       | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 217       | 2.27%   |
| Intel Wireless 8265 / 8275                                        | 205       | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 179       | 1.88%   |
| Intel Wi-Fi 6 AX201                                               | 174       | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 170       | 1.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 167       | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 166       | 1.74%   |
| Intel Wireless 7260                                               | 166       | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 158       | 1.66%   |
| Intel Wireless 7265                                               | 148       | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 145       | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 128       | 1.34%   |
| Intel Wireless 8260                                               | 122       | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 119       | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 117       | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 105       | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 104       | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 96        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 88        | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 81        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 80        | 0.84%   |
| Intel Wireless 3165                                               | 73        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 64        | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 63        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 60        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 59        | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 59        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 59        | 0.62%   |
| Intel Wireless 3160                                               | 58        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 54        | 0.57%   |
| Intel Wireless-AC 9260                                            | 53        | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 53        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 53        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 0.54%   |
| Intel Centrino Ultimate-N 6300                                    | 50        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2597      | 49.7%   |
| Qualcomm Atheros                      | 925       | 17.7%   |
| Realtek Semiconductor                 | 716       | 13.7%   |
| Broadcom                              | 461       | 8.82%   |
| MediaTek                              | 130       | 2.49%   |
| Broadcom Limited                      | 125       | 2.39%   |
| Ralink                                | 56        | 1.07%   |
| TP-Link                               | 43        | 0.82%   |
| Ralink Technology                     | 41        | 0.78%   |
| Sierra Wireless                       | 22        | 0.42%   |
| Dell                                  | 22        | 0.42%   |
| Qualcomm                              | 18        | 0.34%   |
| ASUSTek Computer                      | 11        | 0.21%   |
| NetGear                               | 10        | 0.19%   |
| D-Link                                | 9         | 0.17%   |
| Hewlett-Packard                       | 6         | 0.11%   |
| Fibocom                               | 5         | 0.1%    |
| Edimax Technology                     | 5         | 0.1%    |
| Qualcomm Atheros Communications       | 3         | 0.06%   |
| Microsoft                             | 3         | 0.06%   |
| Linksys                               | 3         | 0.06%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 338       | 6.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 240       | 4.56%   |
| Intel Wireless 8265 / 8275                                     | 205       | 3.9%    |
| Intel Wi-Fi 6 AX201                                            | 174       | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 170       | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 167       | 3.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 166       | 3.16%   |
| Intel Wireless 7260                                            | 166       | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 158       | 3%      |
| Intel Wireless 7265                                            | 148       | 2.81%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 145       | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 128       | 2.43%   |
| Intel Wireless 8260                                            | 122       | 2.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 119       | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 117       | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 105       | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 104       | 1.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 96        | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 88        | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 81        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                  | 80        | 1.52%   |
| Intel Wireless 3165                                            | 73        | 1.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 64        | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 63        | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 59        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 59        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 59        | 1.12%   |
| Intel Wireless 3160                                            | 58        | 1.1%    |
| Intel Wireless-AC 9260                                         | 53        | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 53        | 1.01%   |
| Intel Centrino Ultimate-N 6300                                 | 50        | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 50        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 49        | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 48        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 47        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 45        | 0.86%   |
| Intel Centrino Advanced-N 6235                                 | 42        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 38        | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 33        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2468      | 59.33%  |
| Intel                            | 791       | 19.01%  |
| Qualcomm Atheros                 | 290       | 6.97%   |
| Broadcom                         | 183       | 4.4%    |
| Marvell Technology Group         | 68        | 1.63%   |
| Nvidia                           | 56        | 1.35%   |
| ASIX Electronics                 | 56        | 1.35%   |
| Broadcom Limited                 | 36        | 0.87%   |
| DisplayLink                      | 31        | 0.75%   |
| Lenovo                           | 25        | 0.6%    |
| Xiaomi                           | 22        | 0.53%   |
| Samsung Electronics              | 20        | 0.48%   |
| JMicron Technology               | 18        | 0.43%   |
| Google                           | 14        | 0.34%   |
| OnePlus Technology (Shenzhen)    | 11        | 0.26%   |
| Silicon Integrated Systems [SiS] | 8         | 0.19%   |
| OPPO Electronics                 | 8         | 0.19%   |
| TP-Link                          | 7         | 0.17%   |
| Huawei Technologies              | 7         | 0.17%   |
| Motorola PCS                     | 6         | 0.14%   |
| Apple                            | 5         | 0.12%   |
| Qualcomm                         | 3         | 0.07%   |
| MediaTek                         | 3         | 0.07%   |
| Linksys                          | 3         | 0.07%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| LSI                              | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| Research In Motion               | 1         | 0.02%   |
| NTmore                           | 1         | 0.02%   |
| NetGear                          | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |
| Cypress Semiconductor            | 1         | 0.02%   |
| Attansic Technology              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1752      | 41.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 429       | 10.19%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 217       | 5.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 179       | 4.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 1.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 60        | 1.42%   |
| Intel Ethernet Connection I218-LM                                 | 54        | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 53        | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 47        | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 43        | 1.02%   |
| Nvidia MCP79 Ethernet                                             | 42        | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 41        | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 36        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 34        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 34        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 31        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 30        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 25        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 22        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.47%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 19        | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 18        | 0.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 18        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 18        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4962      | 55.07%  |
| Ethernet | 3976      | 44.13%  |
| Modem    | 59        | 0.65%   |
| Unknown  | 13        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4227      | 79.02%  |
| Ethernet | 1121      | 20.96%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3622      | 72.11%  |
| 1     | 1329      | 26.46%  |
| 0     | 39        | 0.78%   |
| 3     | 33        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3997      | 78.57%  |
| Yes  | 1090      | 21.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2187      | 51.17%  |
| Qualcomm Atheros Communications | 414       | 9.69%   |
| Realtek Semiconductor           | 371       | 8.68%   |
| Apple                           | 258       | 6.04%   |
| IMC Networks                    | 225       | 5.26%   |
| Lite-On Technology              | 197       | 4.61%   |
| Broadcom                        | 193       | 4.52%   |
| Foxconn / Hon Hai               | 131       | 3.07%   |
| Dell                            | 65        | 1.52%   |
| Cambridge Silicon Radio         | 41        | 0.96%   |
| Realtek                         | 33        | 0.77%   |
| Toshiba                         | 30        | 0.7%    |
| Ralink                          | 28        | 0.66%   |
| Hewlett-Packard                 | 28        | 0.66%   |
| ASUSTek Computer                | 15        | 0.35%   |
| Foxconn International           | 11        | 0.26%   |
| Ralink Technology               | 8         | 0.19%   |
| Alps Electric                   | 7         | 0.16%   |
| Smart Modular Technologies      | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| USI                             | 3         | 0.07%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Qcom                            | 3         | 0.07%   |
| Opticis                         | 3         | 0.07%   |
| MediaTek                        | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.05%   |
| TP-Link                         | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 756       | 17.68%  |
| Intel AX201 Bluetooth                               | 440       | 10.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 356       | 8.33%   |
| Intel AX200 Bluetooth                               | 332       | 7.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 230       | 5.38%   |
| Realtek Bluetooth Radio                             | 225       | 5.26%   |
| Apple Bluetooth Host Controller                     | 143       | 3.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 101       | 2.36%   |
| Apple Bluetooth USB Host Controller                 | 82        | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 74        | 1.73%   |
| IMC Networks Bluetooth Radio                        | 73        | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.54%   |
| Intel Bluetooth Device                              | 61        | 1.43%   |
| IMC Networks Wireless_Device                        | 60        | 1.4%    |
| Intel AX210 Bluetooth                               | 52        | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 52        | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 51        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 48        | 1.12%   |
| IMC Networks Bluetooth Device                       | 46        | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 43        | 1.01%   |
| Lite-On Bluetooth Device                            | 43        | 1.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 41        | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 40        | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 39        | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 39        | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 36        | 0.84%   |
| Realtek Bluetooth Radio                             | 33        | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                         | 32        | 0.75%   |
| Ralink RT3290 Bluetooth                             | 28        | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.58%   |
| Dell DW375 Bluetooth Module                         | 23        | 0.54%   |
| Lite-On Wireless_Device                             | 22        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 20        | 0.47%   |
| Apple Bluetooth HCI                                 | 20        | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 18        | 0.42%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 18        | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 15        | 0.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 3978      | 60.59%  |
| Nvidia                                          | 1128      | 17.18%  |
| AMD                                             | 1027      | 15.64%  |
| C-Media Electronics                             | 52        | 0.79%   |
| Logitech                                        | 43        | 0.65%   |
| Realtek Semiconductor                           | 39        | 0.59%   |
| Lenovo                                          | 26        | 0.4%    |
| GN Netcom                                       | 22        | 0.34%   |
| JMTek                                           | 20        | 0.3%    |
| Kingston Technology                             | 16        | 0.24%   |
| Apple                                           | 15        | 0.23%   |
| Texas Instruments                               | 14        | 0.21%   |
| Generalplus Technology                          | 14        | 0.21%   |
| Sony                                            | 11        | 0.17%   |
| Razer USA                                       | 10        | 0.15%   |
| Hewlett-Packard                                 | 10        | 0.15%   |
| Corsair                                         | 10        | 0.15%   |
| SteelSeries ApS                                 | 9         | 0.14%   |
| Silicon Integrated Systems [SiS]                | 8         | 0.12%   |
| Plantronics                                     | 8         | 0.12%   |
| Focusrite-Novation                              | 7         | 0.11%   |
| Sennheiser Communications                       | 5         | 0.08%   |
| Creative Technology                             | 5         | 0.08%   |
| ASUSTek Computer                                | 5         | 0.08%   |
| FiiO Electronics Technology                     | 4         | 0.06%   |
| Tenx Technology                                 | 3         | 0.05%   |
| Samson Technologies                             | 3         | 0.05%   |
| No brand                                        | 3         | 0.05%   |
| GYROCOM C&C                                     | 3         | 0.05%   |
| DSEA A/S                                        | 3         | 0.05%   |
| Blue Microphones                                | 3         | 0.05%   |
| Yamaha                                          | 2         | 0.03%   |
| XMOS                                            | 2         | 0.03%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.03%   |
| TerraTec Electronic                             | 2         | 0.03%   |
| Pioneer DJ                                      | 2         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.03%   |
| CMX Systems                                     | 2         | 0.03%   |
| Bose                                            | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 685       | 8.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 586       | 7.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 389       | 4.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 360       | 4.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 316       | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 310       | 3.9%    |
| Intel 8 Series HD Audio Controller                                         | 243       | 3.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 241       | 3.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 231       | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 219       | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 208       | 2.61%   |
| Intel Broadwell-U Audio Controller                                         | 187       | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 179       | 2.25%   |
| Intel Comet Lake PCH cAVS                                                  | 176       | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 164       | 2.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 161       | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 154       | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 145       | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 144       | 1.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 133       | 1.67%   |
| Intel CM238 HD Audio Controller                                            | 131       | 1.65%   |
| AMD FCH Azalia Controller                                                  | 129       | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 116       | 1.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 96        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 95        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 90        | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 85        | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 82        | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 77        | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 73        | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 67        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 66        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 63        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 62        | 0.78%   |
| Nvidia Audio device                                                        | 61        | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 58        | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 55        | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 47        | 0.59%   |
| Nvidia MCP79 High Definition Audio                                         | 46        | 0.58%   |
| AMD High Definition Audio Controller                                       | 46        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 496       | 29.7%   |
| SK hynix            | 380       | 22.75%  |
| Micron Technology   | 230       | 13.77%  |
| Kingston            | 134       | 8.02%   |
| Crucial             | 92        | 5.51%   |
| Unknown             | 55        | 3.29%   |
| A-DATA Technology   | 38        | 2.28%   |
| Smart               | 32        | 1.92%   |
| Ramaxel Technology  | 24        | 1.44%   |
| Corsair             | 22        | 1.32%   |
| Goldkey             | 20        | 1.2%    |
| Neo Forza           | 19        | 1.14%   |
| Elpida              | 18        | 1.08%   |
| G.Skill             | 15        | 0.9%    |
| Unknown (ABCD)      | 11        | 0.66%   |
| Smart Brazil        | 10        | 0.6%    |
| Unknown             | 9         | 0.54%   |
| Team                | 7         | 0.42%   |
| Teikon              | 6         | 0.36%   |
| Nanya Technology    | 6         | 0.36%   |
| Apacer              | 5         | 0.3%    |
| PNY                 | 4         | 0.24%   |
| Patriot             | 3         | 0.18%   |
| High Bridge         | 3         | 0.18%   |
| GSkill              | 3         | 0.18%   |
| Avant               | 3         | 0.18%   |
| Transcend           | 2         | 0.12%   |
| Timetec             | 2         | 0.12%   |
| GOODRAM             | 2         | 0.12%   |
| Gold Key            | 2         | 0.12%   |
| CSX                 | 2         | 0.12%   |
| ChangXin Memory     | 2         | 0.12%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (898F)      | 1         | 0.06%   |
| Unknown (09B6)      | 1         | 0.06%   |
| Unknown (09A4)      | 1         | 0.06%   |
| Silicon Power       | 1         | 0.06%   |
| RZX                 | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Multilaser          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 2.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 28        | 1.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 1.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 1.09%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 18        | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.97%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.97%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.97%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.91%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.86%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.86%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.69%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 11        | 0.63%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 10        | 0.57%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 9         | 0.51%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 9         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.51%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.51%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 9         | 0.51%   |
| Unknown                                                          | 9         | 0.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.46%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 921       | 65.88%  |
| DDR3    | 273       | 19.53%  |
| LPDDR4  | 74        | 5.29%   |
| LPDDR3  | 63        | 4.51%   |
| DDR5    | 28        | 2%      |
| LPDDR5  | 21        | 1.5%    |
| DDR2    | 10        | 0.72%   |
| SDRAM   | 4         | 0.29%   |
| Unknown | 4         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1221      | 85.74%  |
| Row Of Chips | 184       | 12.92%  |
| Chip         | 12        | 0.84%   |
| DIMM         | 4         | 0.28%   |
| Unknown      | 3         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 692       | 45.29%  |
| 4096  | 371       | 24.28%  |
| 16384 | 309       | 20.22%  |
| 2048  | 76        | 4.97%   |
| 32768 | 70        | 4.58%   |
| 1024  | 10        | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 435       | 28.62%  |
| 3200    | 370       | 24.34%  |
| 1600    | 218       | 14.34%  |
| 2400    | 137       | 9.01%   |
| 2133    | 90        | 5.92%   |
| 4267    | 36        | 2.37%   |
| 1334    | 31        | 2.04%   |
| 4800    | 27        | 1.78%   |
| 3266    | 25        | 1.64%   |
| 1867    | 22        | 1.45%   |
| 6400    | 21        | 1.38%   |
| 1333    | 21        | 1.38%   |
| 8400    | 18        | 1.18%   |
| 4266    | 13        | 0.86%   |
| 1067    | 11        | 0.72%   |
| 800     | 9         | 0.59%   |
| 3733    | 7         | 0.46%   |
| 1866    | 5         | 0.33%   |
| 2933    | 4         | 0.26%   |
| 667     | 4         | 0.26%   |
| Unknown | 3         | 0.2%    |
| 4199    | 2         | 0.13%   |
| 2048    | 2         | 0.13%   |
| 1066    | 2         | 0.13%   |
| 5600    | 1         | 0.07%   |
| 3466    | 1         | 0.07%   |
| 3400    | 1         | 0.07%   |
| 3333    | 1         | 0.07%   |
| 3000    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 30.77%  |
| Seiko Epson         | 5         | 19.23%  |
| Canon               | 4         | 15.38%  |
| Brother Industries  | 4         | 15.38%  |
| Samsung Electronics | 2         | 7.69%   |
| Xerox               | 1         | 3.85%   |
| MIIIW               | 1         | 3.85%   |
| ICS Advent          | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M2020 Series            | 2         | 7.69%   |
| Xerox B215                      | 1         | 3.85%   |
| Seiko Epson WF-3520 Series      | 1         | 3.85%   |
| Seiko Epson L6160 Series        | 1         | 3.85%   |
| Seiko Epson L3110 Series        | 1         | 3.85%   |
| Seiko Epson L132 Series         | 1         | 3.85%   |
| Seiko Epson ET-2700 Series      | 1         | 3.85%   |
| MIIIW MW Keyboard Air Mini      | 1         | 3.85%   |
| ICS Advent Parallel Adapter     | 1         | 3.85%   |
| HP OfficeJet 3830 series        | 1         | 3.85%   |
| HP Ink Tank Wireless 410 series | 1         | 3.85%   |
| HP ENVY Photo 7800 series       | 1         | 3.85%   |
| HP ENVY 4520 series             | 1         | 3.85%   |
| HP Deskjet 3050 J610 series     | 1         | 3.85%   |
| HP Deskjet 2540 series          | 1         | 3.85%   |
| HP Deskjet 2050 J510            | 1         | 3.85%   |
| HP Color LaserJet CP2025dn      | 1         | 3.85%   |
| Canon PIXMA MX920 Series        | 1         | 3.85%   |
| Canon GX7000 series             | 1         | 3.85%   |
| Canon G4010 series              | 1         | 3.85%   |
| Canon E400 series               | 1         | 3.85%   |
| Brother HL-L2370DW series       | 1         | 3.85%   |
| Brother HL-L2320D series        | 1         | 3.85%   |
| Brother HL-3170CDW series       | 1         | 3.85%   |
| Brother HL-2270DW Laser Printer | 1         | 3.85%   |

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
| Chicony Electronics                    | 1067      | 23.75%  |
| IMC Networks                           | 493       | 10.98%  |
| Microdia                               | 446       | 9.93%   |
| Realtek Semiconductor                  | 372       | 8.28%   |
| Bison Electronics                      | 296       | 6.59%   |
| Sunplus Innovation Technology          | 248       | 5.52%   |
| Quanta                                 | 230       | 5.12%   |
| Apple                                  | 195       | 4.34%   |
| Acer                                   | 173       | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 158       | 3.52%   |
| Suyin                                  | 125       | 2.78%   |
| Syntek                                 | 109       | 2.43%   |
| Lite-On Technology                     | 88        | 1.96%   |
| Luxvisions Innotech Limited            | 72        | 1.6%    |
| Silicon Motion                         | 64        | 1.42%   |
| Logitech                               | 61        | 1.36%   |
| Ricoh                                  | 39        | 0.87%   |
| Alcor Micro                            | 31        | 0.69%   |
| Samsung Electronics                    | 26        | 0.58%   |
| Sonix Technology                       | 21        | 0.47%   |
| ALi                                    | 14        | 0.31%   |
| SunplusIT                              | 13        | 0.29%   |
| Primax Electronics                     | 11        | 0.24%   |
| Lenovo                                 | 11        | 0.24%   |
| Z-Star Microelectronics                | 10        | 0.22%   |
| Microsoft                              | 10        | 0.22%   |
| Importek                               | 10        | 0.22%   |
| DigiTech                               | 10        | 0.22%   |
| Intel                                  | 8         | 0.18%   |
| OmniVision Technologies                | 6         | 0.13%   |
| Generalplus Technology                 | 6         | 0.13%   |
| USB Camera                             | 5         | 0.11%   |
| Tobii Technology AB                    | 4         | 0.09%   |
| MacroSilicon                           | 4         | 0.09%   |
| Foxconn / Hon Hai                      | 4         | 0.09%   |
| AVerMedia Technologies                 | 4         | 0.09%   |
| Unknown                                | 3         | 0.07%   |
| Razer USA                              | 3         | 0.07%   |
| Alpha Imaging Technology               | 3         | 0.07%   |
| Sunplus Technology                     | 2         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 236       | 5.23%   |
| Chicony Integrated Camera                           | 205       | 4.54%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 160       | 3.55%   |
| Realtek Integrated_Webcam_HD                        | 146       | 3.24%   |
| IMC Networks Integrated Camera                      | 137       | 3.04%   |
| Chicony HD Webcam                                   | 132       | 2.92%   |
| Chicony USB2.0 Camera                               | 102       | 2.26%   |
| Bison BisonCam,NB Pro                               | 96        | 2.13%   |
| Sunplus Integrated_Webcam_HD                        | 73        | 1.62%   |
| Syntek Integrated Camera                            | 67        | 1.48%   |
| Apple Built-in iSight                               | 65        | 1.44%   |
| Apple FaceTime HD Camera                            | 61        | 1.35%   |
| Quanta HD User Facing                               | 53        | 1.17%   |
| Acer HD Webcam                                      | 51        | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 49        | 1.09%   |
| Bison Integrated Camera                             | 45        | 1%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 44        | 0.97%   |
| Acer Integrated Camera                              | 44        | 0.97%   |
| Lite-On Integrated Camera                           | 35        | 0.78%   |
| Chicony USB 2.0 Camera                              | 35        | 0.78%   |
| Chicony HD User Facing                              | 35        | 0.78%   |
| Microdia Integrated Webcam                          | 34        | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                     | 33        | 0.73%   |
| Bison SunplusIT Integrated Camera                   | 33        | 0.73%   |
| Sunplus HD WebCam                                   | 32        | 0.71%   |
| Chicony Integrated Camera (1280x720@30)             | 32        | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                        | 31        | 0.69%   |
| Chicony HP HD Camera                                | 31        | 0.69%   |
| Sunplus Asus Webcam                                 | 30        | 0.66%   |
| Quanta HD Webcam                                    | 30        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                       | 29        | 0.64%   |
| Realtek Integrated Webcam                           | 28        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD                | 28        | 0.62%   |
| Quanta HP TrueVision HD Camera                      | 27        | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 27        | 0.6%    |
| Realtek USB Camera                                  | 26        | 0.58%   |
| Quanta VGA WebCam                                   | 26        | 0.58%   |
| Chicony HP TrueVision HD Camera                     | 26        | 0.58%   |
| Chicony HP Wide Vision HD Camera                    | 25        | 0.55%   |
| Acer BisonCam, NB Pro                               | 25        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 270       | 30.72%  |
| Validity Sensors                   | 265       | 30.15%  |
| Shenzhen Goodix Technology         | 158       | 17.97%  |
| Upek                               | 50        | 5.69%   |
| Elan Microelectronics              | 50        | 5.69%   |
| LighTuning Technology              | 37        | 4.21%   |
| AuthenTec                          | 29        | 3.3%    |
| STMicroelectronics                 | 7         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.46%   |
| Focal-systems.Corp                 | 4         | 0.46%   |
| HOLTEK                             | 3         | 0.34%   |
| Samsung Electronics                | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 83        | 9.44%   |
| Shenzhen Goodix  Fingerprint Device                                        | 78        | 8.87%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 59        | 6.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 53        | 6.03%   |
| Shenzhen Goodix FingerPrint                                                | 49        | 5.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 5.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 38        | 4.32%   |
| Elan ELAN:Fingerprint                                                      | 36        | 4.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 31        | 3.53%   |
| Synaptics UWP WBDI                                                         | 28        | 3.19%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.28%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.28%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 2.16%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 19        | 2.16%   |
| Synaptics WBDI Device                                                      | 19        | 2.16%   |
| Validity Sensors VFS491                                                    | 18        | 2.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 1.93%   |
| Unknown                                                                    | 17        | 1.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.71%   |
| Elan ELAN:ARM-M4                                                           | 14        | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.14%   |
| Synaptics  WBDI                                                            | 10        | 1.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 1.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 0.91%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.91%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 0.91%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.8%    |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.8%    |
| AuthenTec AES2810                                                          | 7         | 0.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.8%    |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.57%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.57%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.46%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.46%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 155       | 47.26%  |
| Alcor Micro               | 93        | 28.35%  |
| Upek                      | 29        | 8.84%   |
| O2 Micro                  | 24        | 7.32%   |
| Lenovo                    | 18        | 5.49%   |
| Gemalto (was Gemplus)     | 2         | 0.61%   |
| Aladdin Knowledge Systems | 2         | 0.61%   |
| SCM Microsystems          | 1         | 0.3%    |
| OmniKey                   | 1         | 0.3%    |
| Giesecke & Devrient       | 1         | 0.3%    |
| Clay Logic                | 1         | 0.3%    |
| Advanced Card Systems     | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 93        | 28.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 14.33%  |
| Broadcom 5880                                                                | 42        | 12.8%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 40        | 12.2%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 8.84%   |
| Broadcom 58200                                                               | 24        | 7.32%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 6.1%    |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.49%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.61%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.61%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.3%    |
| OmniKey CardMan 4321                                                         | 1         | 0.3%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3178      | 62.19%  |
| 1     | 1523      | 29.8%   |
| 2     | 353       | 6.91%   |
| 3     | 48        | 0.94%   |
| 4     | 6         | 0.12%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 856       | 36.83%  |
| Multimedia controller    | 319       | 13.73%  |
| Chipcard                 | 318       | 13.68%  |
| Net/wireless             | 274       | 11.79%  |
| Graphics card            | 265       | 11.4%   |
| Bluetooth                | 68        | 2.93%   |
| Camera                   | 56        | 2.41%   |
| Storage                  | 39        | 1.68%   |
| Sound                    | 28        | 1.2%    |
| Net/ethernet             | 28        | 1.2%    |
| Card reader              | 19        | 0.82%   |
| Communication controller | 17        | 0.73%   |
| Network                  | 13        | 0.56%   |
| Modem                    | 10        | 0.43%   |
| Storage/ide              | 5         | 0.22%   |
| Storage/nvme             | 3         | 0.13%   |
| Flash memory             | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Unclassified device      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

