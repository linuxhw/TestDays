Linux in Algeria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Algeria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Algeria/Desktop/README.md) and [notebooks](/Location/Algeria/Notebook/README.md).

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

Total: 413

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | TBYF-1014WIN32              | Notebook    | [11ef48e0c0](https://linux-hardware.org/?probe=11ef48e0c0) | Sep 06, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| HP            | 18E9                        | Desktop     | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| MSI           | CR610M                      | Notebook    | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Dell          | Latitude 7430               | Notebook    | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| Intel         | H61                         | Desktop     | [4d6bf88f48](https://linux-hardware.org/?probe=4d6bf88f48) | Aug 21, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [439b66555d](https://linux-hardware.org/?probe=439b66555d) | Aug 17, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [e11ae0d2b7](https://linux-hardware.org/?probe=e11ae0d2b7) | Aug 17, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [e51e841817](https://linux-hardware.org/?probe=e51e841817) | Jul 31, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a79ddb19](https://linux-hardware.org/?probe=a0a79ddb19) | Jul 27, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [99dadfd3f5](https://linux-hardware.org/?probe=99dadfd3f5) | Jul 21, 2023 |
| MSI           | 2A9C                        | Desktop     | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e6c5dadeef](https://linux-hardware.org/?probe=e6c5dadeef) | Jul 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b72c043646](https://linux-hardware.org/?probe=b72c043646) | Jul 13, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c816d8f1b](https://linux-hardware.org/?probe=8c816d8f1b) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [355ccda3d5](https://linux-hardware.org/?probe=355ccda3d5) | Jul 05, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [354dd05c7f](https://linux-hardware.org/?probe=354dd05c7f) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [b465607eea](https://linux-hardware.org/?probe=b465607eea) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [0668932749](https://linux-hardware.org/?probe=0668932749) | Jun 30, 2023 |
| Lenovo        | ThinkPad W520 428425G       | Notebook    | [48d9a1b9fc](https://linux-hardware.org/?probe=48d9a1b9fc) | Jun 26, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [46ed210eb0](https://linux-hardware.org/?probe=46ed210eb0) | Jun 26, 2023 |
| Lenovo        | ThinkPad W520 428425G       | Notebook    | [813d5adfd5](https://linux-hardware.org/?probe=813d5adfd5) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| HP            | 2B34                        | Desktop     | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | Notebook    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [d1d1ef644d](https://linux-hardware.org/?probe=d1d1ef644d) | May 15, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2d5e375a3d](https://linux-hardware.org/?probe=2d5e375a3d) | May 09, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e68f2bc46e](https://linux-hardware.org/?probe=e68f2bc46e) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [98ffa037d9](https://linux-hardware.org/?probe=98ffa037d9) | Apr 24, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [0d45b24479](https://linux-hardware.org/?probe=0d45b24479) | Apr 23, 2023 |
| Toshiba       | Satellite Pro A100          | Notebook    | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [48b2d021fa](https://linux-hardware.org/?probe=48b2d021fa) | Apr 17, 2023 |
| MSI           | G41M-P26                    | Desktop     | [80c102169c](https://linux-hardware.org/?probe=80c102169c) | Apr 16, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [065b7d4c01](https://linux-hardware.org/?probe=065b7d4c01) | Apr 13, 2023 |
| MSI           | G41M-P26                    | Desktop     | [5b6831f7fc](https://linux-hardware.org/?probe=5b6831f7fc) | Apr 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a6e4c91ee0](https://linux-hardware.org/?probe=a6e4c91ee0) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [e27fc333c6](https://linux-hardware.org/?probe=e27fc333c6) | Apr 05, 2023 |
| ASUSTek       | M5401WUA                    | All in one  | [f6285d1100](https://linux-hardware.org/?probe=f6285d1100) | Apr 03, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [f4b76d1e01](https://linux-hardware.org/?probe=f4b76d1e01) | Apr 03, 2023 |
| Toshiba       | Satellite C55-B             | Notebook    | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ee66bc49a5](https://linux-hardware.org/?probe=ee66bc49a5) | Apr 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [267dad60ba](https://linux-hardware.org/?probe=267dad60ba) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f6b6b24623](https://linux-hardware.org/?probe=f6b6b24623) | Feb 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6b5f9db086](https://linux-hardware.org/?probe=6b5f9db086) | Feb 21, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [fd2b985f41](https://linux-hardware.org/?probe=fd2b985f41) | Feb 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| HP            | Notebook                    | Notebook    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [515525584c](https://linux-hardware.org/?probe=515525584c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [46981444b1](https://linux-hardware.org/?probe=46981444b1) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| ASRock        | H81M-GL                     | Desktop     | [059a818847](https://linux-hardware.org/?probe=059a818847) | Feb 09, 2023 |
| Dell          | Latitude E7470              | Notebook    | [5c8d26c4ff](https://linux-hardware.org/?probe=5c8d26c4ff) | Feb 05, 2023 |
| Dell          | Latitude E7470              | Notebook    | [d68227808b](https://linux-hardware.org/?probe=d68227808b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [1f55ca148f](https://linux-hardware.org/?probe=1f55ca148f) | Jan 30, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4042b92ee1](https://linux-hardware.org/?probe=4042b92ee1) | Jan 29, 2023 |
| HP            | 18E7                        | Desktop     | [01cbafc241](https://linux-hardware.org/?probe=01cbafc241) | Jan 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f1f0543123](https://linux-hardware.org/?probe=f1f0543123) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5169fb5013](https://linux-hardware.org/?probe=5169fb5013) | Jan 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [f0ed3b4989](https://linux-hardware.org/?probe=f0ed3b4989) | Jan 14, 2023 |
| MSI           | H270-A PRO                  | Desktop     | [f150327257](https://linux-hardware.org/?probe=f150327257) | Jan 14, 2023 |
| Acer          | Calpella                    | Notebook    | [108843a25a](https://linux-hardware.org/?probe=108843a25a) | Jan 14, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9cc37ff271](https://linux-hardware.org/?probe=9cc37ff271) | Jan 09, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Sony          | VGN-NS10J_S                 | Notebook    | [3789038010](https://linux-hardware.org/?probe=3789038010) | Jan 04, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [c2d592a9e5](https://linux-hardware.org/?probe=c2d592a9e5) | Dec 30, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [de5dc0c3ea](https://linux-hardware.org/?probe=de5dc0c3ea) | Dec 17, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [3b340e6b29](https://linux-hardware.org/?probe=3b340e6b29) | Dec 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [ca043cff45](https://linux-hardware.org/?probe=ca043cff45) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [08d7f00868](https://linux-hardware.org/?probe=08d7f00868) | Nov 24, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [da02cb82bf](https://linux-hardware.org/?probe=da02cb82bf) | Nov 23, 2022 |
| ASUSTek       | S300CA                      | Notebook    | [3efc297b44](https://linux-hardware.org/?probe=3efc297b44) | Nov 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [cae1dbbb12](https://linux-hardware.org/?probe=cae1dbbb12) | Nov 12, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [64c65685da](https://linux-hardware.org/?probe=64c65685da) | Nov 03, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5dbeb8f7dd](https://linux-hardware.org/?probe=5dbeb8f7dd) | Nov 03, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6c979bdf58](https://linux-hardware.org/?probe=6c979bdf58) | Oct 27, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4727244665](https://linux-hardware.org/?probe=4727244665) | Oct 18, 2022 |
| ECS           | G41T-M7                     | Desktop     | [3abe70653e](https://linux-hardware.org/?probe=3abe70653e) | Oct 16, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Dell          | Precision M4800             | Notebook    | [be05dcbe15](https://linux-hardware.org/?probe=be05dcbe15) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [7d65aefb93](https://linux-hardware.org/?probe=7d65aefb93) | Oct 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [719ac47bc6](https://linux-hardware.org/?probe=719ac47bc6) | Oct 06, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cd06f54882](https://linux-hardware.org/?probe=cd06f54882) | Sep 30, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [21d9eb0a71](https://linux-hardware.org/?probe=21d9eb0a71) | Sep 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | Notebook    | [b484febc13](https://linux-hardware.org/?probe=b484febc13) | Sep 17, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e61fe6932b](https://linux-hardware.org/?probe=e61fe6932b) | Sep 13, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [3b1c07d561](https://linux-hardware.org/?probe=3b1c07d561) | Sep 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [26c9be116e](https://linux-hardware.org/?probe=26c9be116e) | Aug 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1f4f742288](https://linux-hardware.org/?probe=1f4f742288) | Aug 23, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [708f9572ad](https://linux-hardware.org/?probe=708f9572ad) | Jul 26, 2022 |
| ECS           | G41T-M16                    | Desktop     | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [4eadb7ee17](https://linux-hardware.org/?probe=4eadb7ee17) | Jun 19, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [fd9f1b2ef6](https://linux-hardware.org/?probe=fd9f1b2ef6) | Jun 17, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [149eb0bab7](https://linux-hardware.org/?probe=149eb0bab7) | Jun 14, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9ff02a8c0c](https://linux-hardware.org/?probe=9ff02a8c0c) | Jun 12, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9273aa4844](https://linux-hardware.org/?probe=9273aa4844) | Jun 12, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [15532b1663](https://linux-hardware.org/?probe=15532b1663) | Jun 07, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [0dd5791ff8](https://linux-hardware.org/?probe=0dd5791ff8) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1b7a237b9b](https://linux-hardware.org/?probe=1b7a237b9b) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| HP            | ProBook 4720s               | Notebook    | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| HP            | ProBook 4720s               | Notebook    | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [95d53f5fc0](https://linux-hardware.org/?probe=95d53f5fc0) | Mar 31, 2022 |
| Dell          | 07N90W A02                  | Desktop     | [4fd59735d6](https://linux-hardware.org/?probe=4fd59735d6) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [698654a73f](https://linux-hardware.org/?probe=698654a73f) | Mar 26, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [00e72ee0ce](https://linux-hardware.org/?probe=00e72ee0ce) | Mar 04, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [eb4abb6e15](https://linux-hardware.org/?probe=eb4abb6e15) | Mar 02, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4110664747](https://linux-hardware.org/?probe=4110664747) | Mar 02, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [9d0a21adb1](https://linux-hardware.org/?probe=9d0a21adb1) | Mar 02, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [7bdf3a8998](https://linux-hardware.org/?probe=7bdf3a8998) | Feb 27, 2022 |
| HP            | 630                         | Notebook    | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [214381cf00](https://linux-hardware.org/?probe=214381cf00) | Feb 16, 2022 |
| Lenovo        | 0B98417 PRO                 | Desktop     | [6e5fa50531](https://linux-hardware.org/?probe=6e5fa50531) | Feb 13, 2022 |
| Intel         | H55                         | Desktop     | [1b1b5c3ed8](https://linux-hardware.org/?probe=1b1b5c3ed8) | Feb 12, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f5b85f478](https://linux-hardware.org/?probe=3f5b85f478) | Feb 07, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03d4a4af15](https://linux-hardware.org/?probe=03d4a4af15) | Feb 05, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| MSI           | H61M-S20                    | Desktop     | [7d0384b2d2](https://linux-hardware.org/?probe=7d0384b2d2) | Jan 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [0d6dacc5dc](https://linux-hardware.org/?probe=0d6dacc5dc) | Jan 20, 2022 |
| ECS           | H61H2-M4                    | Desktop     | [2995a79728](https://linux-hardware.org/?probe=2995a79728) | Jan 07, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Unknown       | X79                         | Desktop     | [ec1620ee82](https://linux-hardware.org/?probe=ec1620ee82) | Jan 01, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [33df9edd07](https://linux-hardware.org/?probe=33df9edd07) | Dec 25, 2021 |
| LDLC          | Mercure MH                  | Notebook    | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Sony          | VGN-AW21M_H                 | Notebook    | [b4cf74ec7d](https://linux-hardware.org/?probe=b4cf74ec7d) | Dec 23, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | X555LAB                     | Notebook    | [c07bccb6c7](https://linux-hardware.org/?probe=c07bccb6c7) | Dec 07, 2021 |
| Sony          | SVF1531GSFB                 | Notebook    | [fb251b93e9](https://linux-hardware.org/?probe=fb251b93e9) | Dec 04, 2021 |
| MSI           | H61M-S20                    | Desktop     | [5e73200702](https://linux-hardware.org/?probe=5e73200702) | Dec 02, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Foxconn       | 17A0                        | Desktop     | [0fc17817a1](https://linux-hardware.org/?probe=0fc17817a1) | Nov 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e26d674874](https://linux-hardware.org/?probe=e26d674874) | Nov 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [233d576651](https://linux-hardware.org/?probe=233d576651) | Nov 12, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [0862dc626b](https://linux-hardware.org/?probe=0862dc626b) | Oct 29, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [545b983e7c](https://linux-hardware.org/?probe=545b983e7c) | Oct 22, 2021 |
| Unknown       | G41 Series V10              | Desktop     | [ce791f779f](https://linux-hardware.org/?probe=ce791f779f) | Oct 21, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [ebd6264587](https://linux-hardware.org/?probe=ebd6264587) | Oct 19, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [9855c138d4](https://linux-hardware.org/?probe=9855c138d4) | Oct 11, 2021 |
| MSI           | H61M-S20                    | Desktop     | [9669908158](https://linux-hardware.org/?probe=9669908158) | Sep 29, 2021 |
| MSI           | H61M-S20                    | Desktop     | [481ecaa854](https://linux-hardware.org/?probe=481ecaa854) | Sep 28, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [d986a2e532](https://linux-hardware.org/?probe=d986a2e532) | Sep 26, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3b43d9b42f](https://linux-hardware.org/?probe=3b43d9b42f) | Sep 22, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [a31437072c](https://linux-hardware.org/?probe=a31437072c) | Sep 20, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [1c77028990](https://linux-hardware.org/?probe=1c77028990) | Sep 18, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [b740654686](https://linux-hardware.org/?probe=b740654686) | Sep 17, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [e817658118](https://linux-hardware.org/?probe=e817658118) | Sep 10, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [b8661880d2](https://linux-hardware.org/?probe=b8661880d2) | Sep 07, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [95d654f778](https://linux-hardware.org/?probe=95d654f778) | Sep 04, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [78886ef280](https://linux-hardware.org/?probe=78886ef280) | Aug 31, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [82aceb2458](https://linux-hardware.org/?probe=82aceb2458) | Aug 30, 2021 |
| HP            | 15                          | Notebook    | [5520042e14](https://linux-hardware.org/?probe=5520042e14) | Aug 28, 2021 |
| HP            | 15                          | Notebook    | [cc4e936b38](https://linux-hardware.org/?probe=cc4e936b38) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8a71545b54](https://linux-hardware.org/?probe=8a71545b54) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [297e2e187c](https://linux-hardware.org/?probe=297e2e187c) | Aug 25, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [b1490652d3](https://linux-hardware.org/?probe=b1490652d3) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [47ed88595b](https://linux-hardware.org/?probe=47ed88595b) | Aug 20, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [cf362e966f](https://linux-hardware.org/?probe=cf362e966f) | Aug 19, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [795edc5779](https://linux-hardware.org/?probe=795edc5779) | Aug 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [eb029acad6](https://linux-hardware.org/?probe=eb029acad6) | Aug 12, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [84199b59aa](https://linux-hardware.org/?probe=84199b59aa) | Aug 10, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [a4be1b3322](https://linux-hardware.org/?probe=a4be1b3322) | Aug 10, 2021 |
| MSI           | CR610M                      | Notebook    | [68759b0315](https://linux-hardware.org/?probe=68759b0315) | Aug 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [007cd499bf](https://linux-hardware.org/?probe=007cd499bf) | Aug 06, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [405dddebf5](https://linux-hardware.org/?probe=405dddebf5) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| Dell          | Latitude 7380               | Notebook    | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| Dell          | 0WG864                      | Desktop     | [2e28996126](https://linux-hardware.org/?probe=2e28996126) | Jul 28, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [185f27f184](https://linux-hardware.org/?probe=185f27f184) | Jul 22, 2021 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [cf7ebc455f](https://linux-hardware.org/?probe=cf7ebc455f) | Jul 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [d8fd7fe06d](https://linux-hardware.org/?probe=d8fd7fe06d) | Jul 20, 2021 |
| Intel         | H55                         | Desktop     | [47c7c454ac](https://linux-hardware.org/?probe=47c7c454ac) | Jul 09, 2021 |
| Intel         | H55                         | Desktop     | [9e4504d3a3](https://linux-hardware.org/?probe=9e4504d3a3) | Jul 09, 2021 |
| Dell          | Latitude 7480               | Notebook    | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| HP            | 2B34                        | Desktop     | [d2c91c450b](https://linux-hardware.org/?probe=d2c91c450b) | May 31, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| Toshiba       | Satellite C50-A539          | Notebook    | [c6c8ae87d9](https://linux-hardware.org/?probe=c6c8ae87d9) | May 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f54143a81d](https://linux-hardware.org/?probe=f54143a81d) | May 24, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [36b88b7391](https://linux-hardware.org/?probe=36b88b7391) | May 23, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [be3e7aa080](https://linux-hardware.org/?probe=be3e7aa080) | May 09, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0252beb838](https://linux-hardware.org/?probe=0252beb838) | May 04, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bd06d6bb56](https://linux-hardware.org/?probe=bd06d6bb56) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [861a11fe04](https://linux-hardware.org/?probe=861a11fe04) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [66faef6161](https://linux-hardware.org/?probe=66faef6161) | May 02, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [62fc21894d](https://linux-hardware.org/?probe=62fc21894d) | Apr 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [7a97f404a4](https://linux-hardware.org/?probe=7a97f404a4) | Apr 24, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [ba300d050b](https://linux-hardware.org/?probe=ba300d050b) | Apr 24, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [7a72fc45b4](https://linux-hardware.org/?probe=7a72fc45b4) | Apr 22, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [b46bb85400](https://linux-hardware.org/?probe=b46bb85400) | Apr 21, 2021 |
| Dell          | Latitude E7440              | Notebook    | [4acb0ea358](https://linux-hardware.org/?probe=4acb0ea358) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [a48b0c422f](https://linux-hardware.org/?probe=a48b0c422f) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [6fd83225c1](https://linux-hardware.org/?probe=6fd83225c1) | Apr 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [2953bef8d1](https://linux-hardware.org/?probe=2953bef8d1) | Apr 18, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [f3b2236c7a](https://linux-hardware.org/?probe=f3b2236c7a) | Apr 15, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [8e5a3a6e19](https://linux-hardware.org/?probe=8e5a3a6e19) | Apr 05, 2021 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [843dae0f43](https://linux-hardware.org/?probe=843dae0f43) | Apr 04, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [2df99824aa](https://linux-hardware.org/?probe=2df99824aa) | Apr 03, 2021 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [765ae993b9](https://linux-hardware.org/?probe=765ae993b9) | Mar 16, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [6408cdb8b2](https://linux-hardware.org/?probe=6408cdb8b2) | Mar 14, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [210d440087](https://linux-hardware.org/?probe=210d440087) | Mar 13, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [a9068d7ec4](https://linux-hardware.org/?probe=a9068d7ec4) | Mar 12, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [387b714e2f](https://linux-hardware.org/?probe=387b714e2f) | Mar 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [5f41497264](https://linux-hardware.org/?probe=5f41497264) | Mar 02, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5cf7ce91a7](https://linux-hardware.org/?probe=5cf7ce91a7) | Mar 01, 2021 |
| Acer          | Extensa 2508                | Notebook    | [7fb16dc91b](https://linux-hardware.org/?probe=7fb16dc91b) | Feb 28, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [0eb94c0487](https://linux-hardware.org/?probe=0eb94c0487) | Feb 26, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [5582abd577](https://linux-hardware.org/?probe=5582abd577) | Feb 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [7ec7f64225](https://linux-hardware.org/?probe=7ec7f64225) | Feb 20, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [35ca18e322](https://linux-hardware.org/?probe=35ca18e322) | Feb 18, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [67702a7546](https://linux-hardware.org/?probe=67702a7546) | Feb 17, 2021 |
| HP            | ProBook 4540s               | Notebook    | [f6618c225b](https://linux-hardware.org/?probe=f6618c225b) | Feb 16, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [c107fc9c40](https://linux-hardware.org/?probe=c107fc9c40) | Feb 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [74fb8b5b1d](https://linux-hardware.org/?probe=74fb8b5b1d) | Feb 14, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [da10465006](https://linux-hardware.org/?probe=da10465006) | Feb 08, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b050103b48](https://linux-hardware.org/?probe=b050103b48) | Feb 04, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [8c36c3c601](https://linux-hardware.org/?probe=8c36c3c601) | Feb 03, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [807a0ea003](https://linux-hardware.org/?probe=807a0ea003) | Jan 31, 2021 |
| Dell          | Precision M6600             | Notebook    | [3731eb952c](https://linux-hardware.org/?probe=3731eb952c) | Jan 29, 2021 |
| Acer          | Aspire V5-571               | Notebook    | [74f0d86e1e](https://linux-hardware.org/?probe=74f0d86e1e) | Jan 28, 2021 |
| Dell          | Precision M6600             | Notebook    | [105a9a66c3](https://linux-hardware.org/?probe=105a9a66c3) | Jan 23, 2021 |
| Dell          | Precision M6600             | Notebook    | [84d3a754fb](https://linux-hardware.org/?probe=84d3a754fb) | Jan 23, 2021 |
| Sony          | VPCEH2H1E                   | Notebook    | [891e9364e0](https://linux-hardware.org/?probe=891e9364e0) | Jan 14, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [9286a611a0](https://linux-hardware.org/?probe=9286a611a0) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [aae61a1ca3](https://linux-hardware.org/?probe=aae61a1ca3) | Dec 22, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ce37e65007](https://linux-hardware.org/?probe=ce37e65007) | Dec 21, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [cf12b04ead](https://linux-hardware.org/?probe=cf12b04ead) | Dec 21, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Unknown       | Unknown                     | Desktop     | [83507a1ac0](https://linux-hardware.org/?probe=83507a1ac0) | Dec 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [688a7e3a73](https://linux-hardware.org/?probe=688a7e3a73) | Dec 11, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [3bab146c4c](https://linux-hardware.org/?probe=3bab146c4c) | Dec 10, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [997a066f37](https://linux-hardware.org/?probe=997a066f37) | Dec 08, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [356e5f32f8](https://linux-hardware.org/?probe=356e5f32f8) | Dec 08, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8dec91d656](https://linux-hardware.org/?probe=8dec91d656) | Dec 01, 2020 |
| Dell          | Vostro 3500                 | Notebook    | [a76707659b](https://linux-hardware.org/?probe=a76707659b) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Gigabyte      | P61A-D3                     | Desktop     | [c547f76923](https://linux-hardware.org/?probe=c547f76923) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [cfbfec849d](https://linux-hardware.org/?probe=cfbfec849d) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [97d5763d6b](https://linux-hardware.org/?probe=97d5763d6b) | Nov 21, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [4ead657ec9](https://linux-hardware.org/?probe=4ead657ec9) | Nov 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a9f4ce29b9](https://linux-hardware.org/?probe=a9f4ce29b9) | Nov 15, 2020 |
| MSI           | G41M-P33 Combo              | Desktop     | [36ffd6debb](https://linux-hardware.org/?probe=36ffd6debb) | Nov 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [51b974180e](https://linux-hardware.org/?probe=51b974180e) | Nov 11, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [39251e283c](https://linux-hardware.org/?probe=39251e283c) | Oct 29, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [85e77f85c7](https://linux-hardware.org/?probe=85e77f85c7) | Oct 26, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [230a4dff71](https://linux-hardware.org/?probe=230a4dff71) | Oct 26, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e2bb03b7da](https://linux-hardware.org/?probe=e2bb03b7da) | Oct 23, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1425d1ebde](https://linux-hardware.org/?probe=1425d1ebde) | Oct 20, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [f1040f264c](https://linux-hardware.org/?probe=f1040f264c) | Oct 19, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [6a54c56b7a](https://linux-hardware.org/?probe=6a54c56b7a) | Oct 19, 2020 |
| HP            | ProBook 4540s               | Notebook    | [b369817417](https://linux-hardware.org/?probe=b369817417) | Oct 15, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [07077a7194](https://linux-hardware.org/?probe=07077a7194) | Oct 02, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [c35dfa149d](https://linux-hardware.org/?probe=c35dfa149d) | Sep 24, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1efd90cecb](https://linux-hardware.org/?probe=1efd90cecb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ebaa6b30e4](https://linux-hardware.org/?probe=ebaa6b30e4) | Sep 20, 2020 |
| HP            | 3397                        | Desktop     | [5232568c4a](https://linux-hardware.org/?probe=5232568c4a) | Sep 06, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [ec99eca757](https://linux-hardware.org/?probe=ec99eca757) | Sep 03, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [9ab161c8d7](https://linux-hardware.org/?probe=9ab161c8d7) | Sep 03, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [c4e5d02631](https://linux-hardware.org/?probe=c4e5d02631) | Sep 02, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Packard Be... | EasyNote LJ71               | Notebook    | [8848f3250d](https://linux-hardware.org/?probe=8848f3250d) | Aug 26, 2020 |
| HP            | 250 G4                      | Notebook    | [84bd70a658](https://linux-hardware.org/?probe=84bd70a658) | Jul 24, 2020 |
| HP            | 250 G4                      | Notebook    | [bb773c0ade](https://linux-hardware.org/?probe=bb773c0ade) | Jul 24, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [33e5e60503](https://linux-hardware.org/?probe=33e5e60503) | Jul 05, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [2273ab39c8](https://linux-hardware.org/?probe=2273ab39c8) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [734c3a7d86](https://linux-hardware.org/?probe=734c3a7d86) | Jun 22, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [9451ca4468](https://linux-hardware.org/?probe=9451ca4468) | Jun 22, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [cb406c43ec](https://linux-hardware.org/?probe=cb406c43ec) | Jun 21, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [46894e19cd](https://linux-hardware.org/?probe=46894e19cd) | Jun 21, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [81cf9fa7cf](https://linux-hardware.org/?probe=81cf9fa7cf) | Jun 11, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [b4ef87de2d](https://linux-hardware.org/?probe=b4ef87de2d) | Jun 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [c349a84934](https://linux-hardware.org/?probe=c349a84934) | Jun 02, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [0bc2465c23](https://linux-hardware.org/?probe=0bc2465c23) | May 25, 2020 |
| ASUSTek       | X541UV                      | Notebook    | [25108243d2](https://linux-hardware.org/?probe=25108243d2) | May 23, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [148b457da1](https://linux-hardware.org/?probe=148b457da1) | May 21, 2020 |
| Acer          | Extensa 2510                | Notebook    | [3c56d54986](https://linux-hardware.org/?probe=3c56d54986) | May 16, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [800fe450a7](https://linux-hardware.org/?probe=800fe450a7) | May 16, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [ad602ee170](https://linux-hardware.org/?probe=ad602ee170) | May 15, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [e1f352ee7e](https://linux-hardware.org/?probe=e1f352ee7e) | May 15, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [165c5e3446](https://linux-hardware.org/?probe=165c5e3446) | May 11, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9deb8b9d38](https://linux-hardware.org/?probe=9deb8b9d38) | May 01, 2020 |
| HP            | 15                          | Notebook    | [bc0640c653](https://linux-hardware.org/?probe=bc0640c653) | May 01, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [30806c27ea](https://linux-hardware.org/?probe=30806c27ea) | May 01, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [bc3989f5fd](https://linux-hardware.org/?probe=bc3989f5fd) | Apr 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [eb26a0a6dd](https://linux-hardware.org/?probe=eb26a0a6dd) | Apr 26, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [27139478ff](https://linux-hardware.org/?probe=27139478ff) | Apr 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1e23113365](https://linux-hardware.org/?probe=1e23113365) | Apr 19, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [a06745a31b](https://linux-hardware.org/?probe=a06745a31b) | Apr 19, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [300ccfbb68](https://linux-hardware.org/?probe=300ccfbb68) | Apr 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [32919aba44](https://linux-hardware.org/?probe=32919aba44) | Apr 08, 2020 |
| Sony          | SVE1713A6EW                 | Notebook    | [998290195d](https://linux-hardware.org/?probe=998290195d) | Mar 26, 2020 |
| Dell          | Precision M4600             | Notebook    | [995809b82f](https://linux-hardware.org/?probe=995809b82f) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [394723d5ec](https://linux-hardware.org/?probe=394723d5ec) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [9a4b04d5c6](https://linux-hardware.org/?probe=9a4b04d5c6) | Mar 10, 2020 |
| Dell          | Latitude 7490               | Notebook    | [3b7100f499](https://linux-hardware.org/?probe=3b7100f499) | Mar 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [b0b0e640c9](https://linux-hardware.org/?probe=b0b0e640c9) | Mar 01, 2020 |
| ECS           | G41T-M7                     | Desktop     | [39f9889169](https://linux-hardware.org/?probe=39f9889169) | Feb 26, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [46a39dcec8](https://linux-hardware.org/?probe=46a39dcec8) | Feb 10, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [52020faf85](https://linux-hardware.org/?probe=52020faf85) | Feb 05, 2020 |
| Dell          | 0F0TGN A00                  | Desktop     | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [ed6be60ed5](https://linux-hardware.org/?probe=ed6be60ed5) | Jan 07, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [b8f52696c7](https://linux-hardware.org/?probe=b8f52696c7) | Jan 07, 2020 |
| MSI           | H55M-E21                    | Desktop     | [a586112d3f](https://linux-hardware.org/?probe=a586112d3f) | Jan 01, 2020 |
| MSI           | H55M-E21                    | Desktop     | [71183fc4d2](https://linux-hardware.org/?probe=71183fc4d2) | Jan 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [170967f63e](https://linux-hardware.org/?probe=170967f63e) | Dec 31, 2019 |
| HP            | Pavilion 15                 | Notebook    | [e190391a64](https://linux-hardware.org/?probe=e190391a64) | Dec 10, 2019 |
| Lenovo        | ThinkPad T440 20B6S00200    | Notebook    | [8491772fe8](https://linux-hardware.org/?probe=8491772fe8) | Nov 19, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [3aed06c634](https://linux-hardware.org/?probe=3aed06c634) | Nov 05, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [80803b7502](https://linux-hardware.org/?probe=80803b7502) | Nov 05, 2019 |
| Sony          | VPCEJ2S1E                   | Notebook    | [909ce7c754](https://linux-hardware.org/?probe=909ce7c754) | Oct 25, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [742402d677](https://linux-hardware.org/?probe=742402d677) | Oct 01, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [bf938959f0](https://linux-hardware.org/?probe=bf938959f0) | Sep 30, 2019 |
| MSI           | Z77A-G45                    | Desktop     | [169e8e49d9](https://linux-hardware.org/?probe=169e8e49d9) | Sep 27, 2019 |
| HP            | 3397                        | Desktop     | [4367666d7a](https://linux-hardware.org/?probe=4367666d7a) | Sep 18, 2019 |
| HP            | 3397                        | Desktop     | [148b5948f9](https://linux-hardware.org/?probe=148b5948f9) | Sep 18, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Intel         | H55                         | Desktop     | [4529486397](https://linux-hardware.org/?probe=4529486397) | Jul 17, 2019 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [a9f20406b7](https://linux-hardware.org/?probe=a9f20406b7) | Jul 17, 2019 |
| Packard Be... | EasyNote TJ75               | Notebook    | [84742985cb](https://linux-hardware.org/?probe=84742985cb) | Apr 30, 2019 |
| Dell          | Latitude E5430 vPro         | Notebook    | [d88e664ef7](https://linux-hardware.org/?probe=d88e664ef7) | Apr 29, 2019 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [ec6b1b90c3](https://linux-hardware.org/?probe=ec6b1b90c3) | Apr 22, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5aeb26c21c](https://linux-hardware.org/?probe=5aeb26c21c) | Apr 10, 2019 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [92ce529502](https://linux-hardware.org/?probe=92ce529502) | Apr 10, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [53ac040baf](https://linux-hardware.org/?probe=53ac040baf) | Mar 28, 2019 |
| HP            | Notebook                    | Notebook    | [a94921a2ad](https://linux-hardware.org/?probe=a94921a2ad) | Dec 29, 2018 |
| WeiBu         | SIMM INT G-41D3 G1.0L       | Desktop     | [d8be685baa](https://linux-hardware.org/?probe=d8be685baa) | Dec 01, 2018 |
| Dell          | 0TP406                      | Desktop     | [620c3d413f](https://linux-hardware.org/?probe=620c3d413f) | Nov 28, 2018 |
| Dell          | 0TP406                      | Desktop     | [e33d9fb70d](https://linux-hardware.org/?probe=e33d9fb70d) | Nov 28, 2018 |
| Unknown       | Unknown                     | Desktop     | [1ee83f48b0](https://linux-hardware.org/?probe=1ee83f48b0) | Oct 14, 2018 |
| MSI           | H55-GD65                    | Desktop     | [6cbd59f0a9](https://linux-hardware.org/?probe=6cbd59f0a9) | Feb 27, 2018 |
| HP            | Pavilion Notebook           | Notebook    | [283bc29327](https://linux-hardware.org/?probe=283bc29327) | Dec 24, 2017 |
| HP            | Pavilion Notebook           | Notebook    | [af28f98e0a](https://linux-hardware.org/?probe=af28f98e0a) | Dec 07, 2017 |
| MSI           | 970A-G46                    | Desktop     | [693800273f](https://linux-hardware.org/?probe=693800273f) | Apr 01, 2017 |
| ASUSTek       | X540SA                      | Notebook    | [f76ee802c9](https://linux-hardware.org/?probe=f76ee802c9) | Mar 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 50        | 17.36%  |
| Ubuntu 18.04       | 20        | 6.94%   |
| Ubuntu 22.04       | 16        | 5.56%   |
| OpenMandriva 4.3   | 15        | 5.21%   |
| OpenMandriva 4.2   | 14        | 4.86%   |
| Linux Mint 20.1    | 7         | 2.43%   |
| OpenMandriva 23.03 | 6         | 2.08%   |
| KDE neon 20.04     | 6         | 2.08%   |
| Zorin 16           | 5         | 1.74%   |
| Pop!_OS 20.04      | 5         | 1.74%   |
| Arch               | 5         | 1.74%   |
| Ubuntu 21.04       | 4         | 1.39%   |
| Ubuntu 19.10       | 4         | 1.39%   |
| OpenMandriva 23.08 | 4         | 1.39%   |
| Manjaro            | 4         | 1.39%   |
| Fedora 37          | 4         | 1.39%   |
| Fedora 35          | 4         | 1.39%   |
| Debian 11          | 4         | 1.39%   |
| ArcoLinux Rolling  | 4         | 1.39%   |
| Xubuntu 20.04      | 3         | 1.04%   |
| Ubuntu 20.10       | 3         | 1.04%   |
| ROSA R11           | 3         | 1.04%   |
| ROSA R10           | 3         | 1.04%   |
| OpenMandriva 23.01 | 3         | 1.04%   |
| Linux Mint 20.2    | 3         | 1.04%   |
| KDE neon 22.04     | 3         | 1.04%   |
| BlackPanther 18.1  | 3         | 1.04%   |
| Xubuntu 22.04      | 2         | 0.69%   |
| Ubuntu 21.10       | 2         | 0.69%   |
| Ubuntu 19.04       | 2         | 0.69%   |
| ROSA R8.1          | 2         | 0.69%   |
| Pop!_OS 22.04      | 2         | 0.69%   |
| Parrot 5.0         | 2         | 0.69%   |
| Manjaro 20.1       | 2         | 0.69%   |
| Linux Mint 21      | 2         | 0.69%   |
| Kubuntu 20.04      | 2         | 0.69%   |
| Kali 2021.2        | 2         | 0.69%   |
| Kali 2021.1        | 2         | 0.69%   |
| Fedora 38          | 2         | 0.69%   |
| Fedora 36          | 2         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 100       | 36.23%  |
| OpenMandriva  | 40        | 14.49%  |
| Linux Mint    | 18        | 6.52%   |
| Fedora        | 15        | 5.43%   |
| Pop!_OS       | 10        | 3.62%   |
| KDE neon      | 9         | 3.26%   |
| ROSA          | 8         | 2.9%    |
| Manjaro       | 8         | 2.9%    |
| Debian        | 8         | 2.9%    |
| Kali          | 7         | 2.54%   |
| Zorin         | 6         | 2.17%   |
| Xubuntu       | 6         | 2.17%   |
| Arch          | 6         | 2.17%   |
| Parrot        | 5         | 1.81%   |
| ArcoLinux     | 4         | 1.45%   |
| Kubuntu       | 3         | 1.09%   |
| BlackPanther  | 3         | 1.09%   |
| Peppermint    | 2         | 0.72%   |
| Xero          | 1         | 0.36%   |
| UbuntuDDE     | 1         | 0.36%   |
| Ubuntu Unity  | 1         | 0.36%   |
| Ubuntu MATE   | 1         | 0.36%   |
| Ubuntu Budgie | 1         | 0.36%   |
| Skygate       | 1         | 0.36%   |
| Pear OS       | 1         | 0.36%   |
| openSUSE      | 1         | 0.36%   |
| MX            | 1         | 0.36%   |
| Gentoo        | 1         | 0.36%   |
| Garuda Linux  | 1         | 0.36%   |
| Endless       | 1         | 0.36%   |
| EndeavourOS   | 1         | 0.36%   |
| Clear Linux   | 1         | 0.36%   |
| CentOS        | 1         | 0.36%   |
| Athena        | 1         | 0.36%   |
| Artix         | 1         | 0.36%   |
| ArchLabs      | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 15        | 4.9%    |
| 5.10.14-desktop-1omv4002 | 14        | 4.58%   |
| 6.2.6-desktop-1omv2390   | 5         | 1.63%   |
| 5.4.0-42-generic         | 5         | 1.63%   |
| 5.15.0-47-generic        | 5         | 1.63%   |
| 5.8.0-50-generic         | 4         | 1.31%   |
| 5.4.0-72-generic         | 4         | 1.31%   |
| 5.4.0-54-generic         | 4         | 1.31%   |
| 5.4.0-29-generic         | 4         | 1.31%   |
| 5.0.0-37-generic         | 4         | 1.31%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.98%   |
| 5.4.0-65-generic         | 3         | 0.98%   |
| 5.4.0-56-generic         | 3         | 0.98%   |
| 5.4.0-52-generic         | 3         | 0.98%   |
| 5.3.0-46-generic         | 3         | 0.98%   |
| 5.15.0-58-generic        | 3         | 0.98%   |
| 5.15.0-56-generic        | 3         | 0.98%   |
| 5.13.0-30-generic        | 3         | 0.98%   |
| 5.11.0-38-generic        | 3         | 0.98%   |
| 5.11.0-27-generic        | 3         | 0.98%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.65%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.65%   |
| 6.0.7-301.fc37.x86_64    | 2         | 0.65%   |
| 5.8.0-44-generic         | 2         | 0.65%   |
| 5.4.0-88-generic         | 2         | 0.65%   |
| 5.4.0-81-generic         | 2         | 0.65%   |
| 5.4.0-80-generic         | 2         | 0.65%   |
| 5.4.0-7625-generic       | 2         | 0.65%   |
| 5.4.0-48-generic         | 2         | 0.65%   |
| 5.4.0-33-generic         | 2         | 0.65%   |
| 5.3.0-40-generic         | 2         | 0.65%   |
| 5.19.0-40-generic        | 2         | 0.65%   |
| 5.15.0-60-generic        | 2         | 0.65%   |
| 5.15.0-48-generic        | 2         | 0.65%   |
| 5.13.0-44-generic        | 2         | 0.65%   |
| 5.11.0-40-generic        | 2         | 0.65%   |
| 5.11.0-36-generic        | 2         | 0.65%   |
| 5.11.0-34-generic        | 2         | 0.65%   |
| 5.11.0-25-generic        | 2         | 0.65%   |
| 5.0.0-29-generic         | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 17.18%  |
| 5.15.0  | 25        | 8.59%   |
| 5.11.0  | 16        | 5.5%    |
| 5.16.7  | 15        | 5.15%   |
| 5.8.0   | 14        | 4.81%   |
| 5.10.14 | 14        | 4.81%   |
| 4.15.0  | 13        | 4.47%   |
| 5.3.0   | 10        | 3.44%   |
| 5.0.0   | 10        | 3.44%   |
| 5.13.0  | 9         | 3.09%   |
| 5.10.0  | 8         | 2.75%   |
| 6.2.6   | 6         | 2.06%   |
| 5.19.0  | 5         | 1.72%   |
| 6.1.1   | 3         | 1.03%   |
| 6.1.0   | 3         | 1.03%   |
| 4.18.16 | 3         | 1.03%   |
| 6.4.8   | 2         | 0.69%   |
| 6.4.11  | 2         | 0.69%   |
| 6.2.8   | 2         | 0.69%   |
| 6.1.12  | 2         | 0.69%   |
| 6.0.7   | 2         | 0.69%   |
| 5.18.12 | 2         | 0.69%   |
| 5.15.7  | 2         | 0.69%   |
| 5.14.0  | 2         | 0.69%   |
| 4.9.60  | 2         | 0.69%   |
| 4.4.0   | 2         | 0.69%   |
| 4.19.0  | 2         | 0.69%   |
| 6.5.0   | 1         | 0.34%   |
| 6.4.9   | 1         | 0.34%   |
| 6.4.6   | 1         | 0.34%   |
| 6.4.4   | 1         | 0.34%   |
| 6.3.4   | 1         | 0.34%   |
| 6.3.0   | 1         | 0.34%   |
| 6.2.9   | 1         | 0.34%   |
| 6.2.14  | 1         | 0.34%   |
| 6.2.11  | 1         | 0.34%   |
| 6.2.0   | 1         | 0.34%   |
| 6.1.9   | 1         | 0.34%   |
| 6.1.50  | 1         | 0.34%   |
| 6.1.4   | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 18.28%  |
| 5.15    | 35        | 12.07%  |
| 5.10    | 27        | 9.31%   |
| 5.11    | 18        | 6.21%   |
| 5.16    | 17        | 5.86%   |
| 5.8     | 15        | 5.17%   |
| 4.15    | 13        | 4.48%   |
| 6.2     | 12        | 4.14%   |
| 6.1     | 11        | 3.79%   |
| 5.3     | 10        | 3.45%   |
| 5.19    | 10        | 3.45%   |
| 5.13    | 10        | 3.45%   |
| 5.0     | 10        | 3.45%   |
| 6.4     | 7         | 2.41%   |
| 6.0     | 5         | 1.72%   |
| 5.14    | 4         | 1.38%   |
| 4.9     | 4         | 1.38%   |
| 4.19    | 4         | 1.38%   |
| 4.18    | 4         | 1.38%   |
| 5.18    | 3         | 1.03%   |
| 5.17    | 3         | 1.03%   |
| 5.12    | 3         | 1.03%   |
| 6.3     | 2         | 0.69%   |
| 5.7     | 2         | 0.69%   |
| 5.6     | 2         | 0.69%   |
| 4.4     | 2         | 0.69%   |
| 6.5     | 1         | 0.34%   |
| 5.9     | 1         | 0.34%   |
| 4.1     | 1         | 0.34%   |
| 3.10    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 245       | 96.46%  |
| i686   | 8         | 3.15%   |
| armv7l | 1         | 0.39%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 122       | 45.19%  |
| KDE5             | 62        | 22.96%  |
| Unknown          | 24        | 8.89%   |
| XFCE             | 18        | 6.67%   |
| X-Cinnamon       | 10        | 3.7%    |
| MATE             | 8         | 2.96%   |
| KDE4             | 5         | 1.85%   |
| KDE              | 5         | 1.85%   |
| Cinnamon         | 4         | 1.48%   |
| LXQt             | 2         | 0.74%   |
| i3               | 2         | 0.74%   |
| Unity            | 1         | 0.37%   |
| Peppermint       | 1         | 0.37%   |
| LXDE             | 1         | 0.37%   |
| lightdm-xsession | 1         | 0.37%   |
| GNOME Flashback  | 1         | 0.37%   |
| fvwm             | 1         | 0.37%   |
| Deepin           | 1         | 0.37%   |
| Budgie           | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 203       | 77.78%  |
| Wayland | 44        | 16.86%  |
| Unknown | 12        | 4.6%    |
| Tty     | 2         | 0.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 124       | 46.1%   |
| SDDM    | 52        | 19.33%  |
| GDM3    | 27        | 10.04%  |
| GDM     | 27        | 10.04%  |
| LightDM | 26        | 9.67%   |
| TDM     | 7         | 2.6%    |
| KDM     | 5         | 1.86%   |
| SLiM    | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 112       | 42.11%  |
| fr_FR       | 97        | 36.47%  |
| Unknown     | 26        | 9.77%   |
| en_GB       | 12        | 4.51%   |
| C           | 6         | 2.26%   |
| ar_DZ       | 6         | 2.26%   |
| fr_DZ       | 2         | 0.75%   |
| fr_BE       | 2         | 0.75%   |
| ar_EG       | 2         | 0.75%   |
| en-US-UTF-8 | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 178       | 68.46%  |
| EFI  | 82        | 31.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 192       | 71.91%  |
| Overlay | 39        | 14.61%  |
| Btrfs   | 21        | 7.87%   |
| Unknown | 9         | 3.37%   |
| Ext2    | 3         | 1.12%   |
| Xfs     | 1         | 0.37%   |
| Tmpfs   | 1         | 0.37%   |
| Ext3    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 140       | 53.44%  |
| GPT     | 67        | 25.57%  |
| MBR     | 55        | 20.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 79.17%  |
| Yes       | 55        | 20.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 53.46%  |
| Yes       | 121       | 46.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 42        | 16.54%  |
| Hewlett-Packard     | 36        | 14.17%  |
| Lenovo              | 29        | 11.42%  |
| ASUSTek Computer    | 25        | 9.84%   |
| MSI                 | 19        | 7.48%   |
| Gigabyte Technology | 15        | 5.91%   |
| Acer                | 13        | 5.12%   |
| Toshiba             | 11        | 4.33%   |
| Unknown             | 10        | 3.94%   |
| ECS                 | 8         | 3.15%   |
| Sony                | 7         | 2.76%   |
| Foxconn             | 7         | 2.76%   |
| Apple               | 5         | 1.97%   |
| Intel               | 4         | 1.57%   |
| Samsung Electronics | 3         | 1.18%   |
| Packard Bell        | 3         | 1.18%   |
| Biostar             | 3         | 1.18%   |
| ASRock              | 3         | 1.18%   |
| Fujitsu             | 2         | 0.79%   |
| Wistron             | 1         | 0.39%   |
| WeiBu               | 1         | 0.39%   |
| sunxi               | 1         | 0.39%   |
| Pegatron            | 1         | 0.39%   |
| Microsoft           | 1         | 0.39%   |
| LORD ELECTRONICS    | 1         | 0.39%   |
| LDLC                | 1         | 0.39%   |
| HUAWEI              | 1         | 0.39%   |
| eMachines           | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 10        | 3.94%   |
| Toshiba Satellite C55-B       | 4         | 1.57%   |
| Dell Inspiron 15-3567         | 4         | 1.57%   |
| Intel H55                     | 3         | 1.18%   |
| HP Notebook                   | 3         | 1.18%   |
| ECS G41T-M7                   | 3         | 1.18%   |
| Dell Inspiron N5110           | 3         | 1.18%   |
| Dell Inspiron 3542            | 3         | 1.18%   |
| MSI MS-7758                   | 2         | 0.79%   |
| MSI MS-7636                   | 2         | 0.79%   |
| MSI MS-7592                   | 2         | 0.79%   |
| Lenovo IdeaPad 300-15ISK 80Q7 | 2         | 0.79%   |
| Lenovo G560 20042             | 2         | 0.79%   |
| Lenovo G50-30 80G0            | 2         | 0.79%   |
| Lenovo B50-70 20384           | 2         | 0.79%   |
| HP ProBook 4540s              | 2         | 0.79%   |
| HP Pavilion 15                | 2         | 0.79%   |
| HP 280 G1 MT                  | 2         | 0.79%   |
| HP 15                         | 2         | 0.79%   |
| Gigabyte H61M-S2PV            | 2         | 0.79%   |
| Gigabyte B85M-DS3H-A          | 2         | 0.79%   |
| Foxconn H61MXL/H61MXL-K       | 2         | 0.79%   |
| ECS H61H2-MV                  | 2         | 0.79%   |
| Dell Latitude E7440           | 2         | 0.79%   |
| Dell Latitude E5430 vPro      | 2         | 0.79%   |
| Dell Latitude 7480            | 2         | 0.79%   |
| Biostar P4M89-M7B             | 2         | 0.79%   |
| ASUS UL80VT                   | 2         | 0.79%   |
| ASUS H61M-K                   | 2         | 0.79%   |
| ASUS All Series               | 2         | 0.79%   |
| Acer Aspire 5738              | 2         | 0.79%   |
| Wistron ProLiant ML110 G5     | 1         | 0.39%   |
| WeiBu SIMM INT G-41D3 G1.0L   | 1         | 0.39%   |
| Toshiba Satellite Pro A100    | 1         | 0.39%   |
| Toshiba Satellite C850-A979   | 1         | 0.39%   |
| Toshiba Satellite C50-A560    | 1         | 0.39%   |
| Toshiba Satellite C50-A545    | 1         | 0.39%   |
| Toshiba Satellite C50-A539    | 1         | 0.39%   |
| Toshiba PORTEGE R30-A         | 1         | 0.39%   |
| Toshiba PORTEGE M780          | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 16        | 6.3%    |
| Dell Latitude         | 14        | 5.51%   |
| Acer Aspire           | 10        | 3.94%   |
| Unknown               | 10        | 3.94%   |
| Toshiba Satellite     | 9         | 3.54%   |
| Lenovo ThinkPad       | 9         | 3.54%   |
| HP ProBook            | 9         | 3.54%   |
| Lenovo IdeaPad        | 5         | 1.97%   |
| HP Pavilion           | 5         | 1.97%   |
| HP EliteBook          | 5         | 1.97%   |
| Intel H55             | 3         | 1.18%   |
| HP Notebook           | 3         | 1.18%   |
| ECS G41T-M7           | 3         | 1.18%   |
| Dell Vostro           | 3         | 1.18%   |
| Dell Precision        | 3         | 1.18%   |
| Dell OptiPlex         | 3         | 1.18%   |
| Toshiba PORTEGE       | 2         | 0.79%   |
| Packard Bell EasyNote | 2         | 0.79%   |
| MSI MS-7758           | 2         | 0.79%   |
| MSI MS-7636           | 2         | 0.79%   |
| MSI MS-7592           | 2         | 0.79%   |
| Lenovo G580           | 2         | 0.79%   |
| Lenovo G560           | 2         | 0.79%   |
| Lenovo G50-30         | 2         | 0.79%   |
| Lenovo B50-70         | 2         | 0.79%   |
| HP ProDesk            | 2         | 0.79%   |
| HP Laptop             | 2         | 0.79%   |
| HP 280                | 2         | 0.79%   |
| HP 15                 | 2         | 0.79%   |
| Gigabyte H61M-S2PV    | 2         | 0.79%   |
| Gigabyte B85M-DS3H-A  | 2         | 0.79%   |
| Fujitsu LIFEBOOK      | 2         | 0.79%   |
| Foxconn H61MXL        | 2         | 0.79%   |
| ECS H61H2-MV          | 2         | 0.79%   |
| Biostar P4M89-M7B     | 2         | 0.79%   |
| ASUS UL80VT           | 2         | 0.79%   |
| ASUS TUF              | 2         | 0.79%   |
| ASUS PRIME            | 2         | 0.79%   |
| ASUS H61M-K           | 2         | 0.79%   |
| ASUS ASUS             | 2         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 44        | 17.32%  |
| 2013    | 31        | 12.2%   |
| 2014    | 30        | 11.81%  |
| 2011    | 24        | 9.45%   |
| 2015    | 21        | 8.27%   |
| 2016    | 17        | 6.69%   |
| 2010    | 17        | 6.69%   |
| 2017    | 16        | 6.3%    |
| 2009    | 13        | 5.12%   |
| 2018    | 12        | 4.72%   |
| 2019    | 7         | 2.76%   |
| 2008    | 5         | 1.97%   |
| 2007    | 5         | 1.97%   |
| 2021    | 4         | 1.57%   |
| 2020    | 4         | 1.57%   |
| 2006    | 2         | 0.79%   |
| 2022    | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 151       | 59.45%  |
| Desktop        | 96        | 37.8%   |
| All in one     | 3         | 1.18%   |
| Tablet         | 2         | 0.79%   |
| System on chip | 1         | 0.39%   |
| Convertible    | 1         | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 249       | 97.65%  |
| Enabled  | 6         | 2.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 254       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 93        | 35.77%  |
| 4.01-8.0    | 64        | 24.62%  |
| 8.01-16.0   | 48        | 18.46%  |
| 1.01-2.0    | 21        | 8.08%   |
| 16.01-24.0  | 15        | 5.77%   |
| 2.01-3.0    | 8         | 3.08%   |
| 32.01-64.0  | 6         | 2.31%   |
| 0.51-1.0    | 4         | 1.54%   |
| 64.01-256.0 | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 129       | 45.74%  |
| 2.01-3.0  | 77        | 27.3%   |
| 3.01-4.0  | 32        | 11.35%  |
| 0.51-1.0  | 19        | 6.74%   |
| 4.01-8.0  | 17        | 6.03%   |
| 8.01-16.0 | 5         | 1.77%   |
| 0.01-0.5  | 3         | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 171       | 66.02%  |
| 2      | 66        | 25.48%  |
| 3      | 13        | 5.02%   |
| 4      | 4         | 1.54%   |
| 0      | 3         | 1.16%   |
| 7      | 1         | 0.39%   |
| 5      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 58.91%  |
| No        | 106       | 41.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 235       | 92.52%  |
| No        | 19        | 7.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 76.36%  |
| No        | 61        | 23.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 54.83%  |
| Yes       | 117       | 45.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 254       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Algiers            | 41        | 13.99%  |
| Belcourt           | 17        | 5.8%    |
| Oran               | 12        | 4.1%    |
| Annaba             | 12        | 4.1%    |
| Constantine        | 10        | 3.41%   |
| Tlemcen            | 9         | 3.07%   |
| Skikda             | 7         | 2.39%   |
| Sétif             | 7         | 2.39%   |
| Relizane           | 6         | 2.05%   |
| Ouargla            | 6         | 2.05%   |
| Jijelli            | 6         | 2.05%   |
| Blida              | 6         | 2.05%   |
| Tizi Ouzou         | 5         | 1.71%   |
| Tipasa             | 5         | 1.71%   |
| Cheraga            | 5         | 1.71%   |
| Biskra             | 5         | 1.71%   |
| Batna City         | 5         | 1.71%   |
| Mostaganem         | 4         | 1.37%   |
| Laghouat           | 4         | 1.37%   |
| Birkhadem          | 4         | 1.37%   |
| Béjaïa           | 4         | 1.37%   |
| Tolga              | 3         | 1.02%   |
| Sidi Bel Abbes     | 3         | 1.02%   |
| Sidi Akkacha       | 3         | 1.02%   |
| Saoula             | 3         | 1.02%   |
| Kouba              | 3         | 1.02%   |
| Ben ’Aknoûn     | 3         | 1.02%   |
| Bab Ezzouar        | 3         | 1.02%   |
| ash-Shalif         | 3         | 1.02%   |
| Saida              | 2         | 0.68%   |
| Ouenza             | 2         | 0.68%   |
| Khenchela          | 2         | 0.68%   |
| El Aouinet         | 2         | 0.68%   |
| Draria             | 2         | 0.68%   |
| Djelfa             | 2         | 0.68%   |
| Boumerdes          | 2         | 0.68%   |
| Boudouaou          | 2         | 0.68%   |
| Bordj el Kiffan    | 2         | 0.68%   |
| Bordj Bou Arreridj | 2         | 0.68%   |
| Bir el Djir        | 2         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 58        | 76     | 17.31%  |
| WDC                         | 55        | 79     | 16.42%  |
| Toshiba                     | 37        | 47     | 11.04%  |
| Hitachi                     | 32        | 42     | 9.55%   |
| Samsung Electronics         | 25        | 29     | 7.46%   |
| HGST                        | 17        | 22     | 5.07%   |
| A-DATA Technology           | 17        | 21     | 5.07%   |
| Unknown                     | 8         | 12     | 2.39%   |
| SanDisk                     | 8         | 8      | 2.39%   |
| Lexar                       | 7         | 10     | 2.09%   |
| Team                        | 6         | 7      | 1.79%   |
| Maxtor                      | 6         | 8      | 1.79%   |
| SK hynix                    | 4         | 6      | 1.19%   |
| LITEON                      | 4         | 7      | 1.19%   |
| Realtek Semiconductor       | 3         | 3      | 0.9%    |
| Kingston                    | 3         | 3      | 0.9%    |
| Intel                       | 3         | 4      | 0.9%    |
| Fujitsu                     | 3         | 4      | 0.9%    |
| ZTE                         | 2         | 2      | 0.6%    |
| XPG                         | 2         | 2      | 0.6%    |
| Silicon Motion              | 2         | 2      | 0.6%    |
| Micron Technology           | 2         | 3      | 0.6%    |
| KingSpec                    | 2         | 2      | 0.6%    |
| KESU                        | 2         | 2      | 0.6%    |
| China                       | 2         | 2      | 0.6%    |
| Apple                       | 2         | 2      | 0.6%    |
| XrayDisk                    | 1         | 1      | 0.3%    |
| WD MediaMax                 | 1         | 1      | 0.3%    |
| TwinMOS                     | 1         | 1      | 0.3%    |
| tecmiyo                     | 1         | 1      | 0.3%    |
| T-FORCE                     | 1         | 1      | 0.3%    |
| Smart                       | 1         | 1      | 0.3%    |
| PNY                         | 1         | 1      | 0.3%    |
| Micron/Crucial Technology   | 1         | 1      | 0.3%    |
| MDT                         | 1         | 1      | 0.3%    |
| Magnetic Data               | 1         | 1      | 0.3%    |
| Londisk                     | 1         | 1      | 0.3%    |
| Lenovo                      | 1         | 1      | 0.3%    |
| KIOXIA                      | 1         | 1      | 0.3%    |
| Kingston Technology Company | 1         | 2      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 9         | 2.54%   |
| Toshiba DT01ACA100 1TB                 | 5         | 1.41%   |
| Seagate ST9500325AS 500GB              | 5         | 1.41%   |
| Seagate ST500LT012-1DG142 500GB        | 5         | 1.41%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 4         | 1.13%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.13%   |
| Toshiba DT01ACA050 500GB               | 4         | 1.13%   |
| Seagate ST500LT012-9WS142 500GB        | 4         | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB         | 4         | 1.13%   |
| Seagate Expansion 2TB                  | 4         | 1.13%   |
| HGST HTS545050A7E680 500GB             | 4         | 1.13%   |
| HGST HTS545050A7E380 500GB             | 4         | 1.13%   |
| A-DATA SU630 240GB SSD                 | 4         | 1.13%   |
| WDC WD10EZEX-08WN4A0 1TB               | 3         | 0.85%   |
| WDC WD10EZEX-00WN4A0 1TB               | 3         | 0.85%   |
| Lexar 512GB SSD                        | 3         | 0.85%   |
| Lexar 128GB SSD                        | 3         | 0.85%   |
| Hitachi HTS545050B9A300 500GB          | 3         | 0.85%   |
| Hitachi HTS545050A7E380 500GB          | 3         | 0.85%   |
| Hitachi HDS721616PLA380 160GB          | 3         | 0.85%   |
| HGST HTS725050A7E630 500GB             | 3         | 0.85%   |
| ZTE MMC Storage 942MB                  | 2         | 0.56%   |
| XPG SX950U 240GB                       | 2         | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.56%   |
| WDC WD5000AVVS-63M8B0 500GB            | 2         | 0.56%   |
| WDC WD5000AAKX-001CA0 500GB            | 2         | 0.56%   |
| WDC WD1600AVJS-63WNA0 160GB            | 2         | 0.56%   |
| Unknown SD/MMC 2GB                     | 2         | 0.56%   |
| Unknown MMC Card  64GB                 | 2         | 0.56%   |
| Unknown M.S./M.S.Pro/HG 16GB           | 2         | 0.56%   |
| Team T253512GB SSD                     | 2         | 0.56%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.56%   |
| Seagate ST3500413AS 500GB              | 2         | 0.56%   |
| Seagate ST3500312CS 500GB              | 2         | 0.56%   |
| Seagate ST320LT020-9YG142 320GB        | 2         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB         | 2         | 0.56%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 76     | 26.13%  |
| WDC                 | 53        | 73     | 23.87%  |
| Toshiba             | 36        | 44     | 16.22%  |
| Hitachi             | 32        | 42     | 14.41%  |
| HGST                | 17        | 22     | 7.66%   |
| Samsung Electronics | 11        | 12     | 4.95%   |
| Maxtor              | 6         | 8      | 2.7%    |
| Fujitsu             | 3         | 4      | 1.35%   |
| WD MediaMax         | 1         | 1      | 0.45%   |
| Magnetic Data       | 1         | 1      | 0.45%   |
| KESU                | 1         | 1      | 0.45%   |
| Initio              | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 13        | 16     | 18.57%  |
| SanDisk             | 6         | 6      | 8.57%   |
| Lexar               | 6         | 9      | 8.57%   |
| Team                | 5         | 6      | 7.14%   |
| Samsung Electronics | 5         | 5      | 7.14%   |
| WDC                 | 4         | 6      | 5.71%   |
| LITEON              | 4         | 7      | 5.71%   |
| SK hynix            | 3         | 5      | 4.29%   |
| Intel               | 3         | 4      | 4.29%   |
| XPG                 | 2         | 2      | 2.86%   |
| Kingston            | 2         | 2      | 2.86%   |
| KingSpec            | 2         | 2      | 2.86%   |
| China               | 2         | 2      | 2.86%   |
| XrayDisk            | 1         | 1      | 1.43%   |
| TwinMOS             | 1         | 1      | 1.43%   |
| tecmiyo             | 1         | 1      | 1.43%   |
| T-FORCE             | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Londisk             | 1         | 1      | 1.43%   |
| Lenovo              | 1         | 1      | 1.43%   |
| JMicron Technology  | 1         | 1      | 1.43%   |
| HS-SSD-C100         | 1         | 1      | 1.43%   |
| Crucial             | 1         | 1      | 1.43%   |
| Corsair             | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |
| Unknown             | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 197       | 287    | 65.23%  |
| SSD     | 64        | 85     | 21.19%  |
| NVMe    | 24        | 35     | 7.95%   |
| Unknown | 10        | 13     | 3.31%   |
| MMC     | 7         | 9      | 2.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 229       | 366    | 83.27%  |
| NVMe | 24        | 35     | 8.73%   |
| SAS  | 15        | 19     | 5.45%   |
| MMC  | 7         | 9      | 2.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 188       | 277    | 71.48%  |
| 0.51-1.0   | 64        | 82     | 24.33%  |
| 1.01-2.0   | 11        | 13     | 4.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 68        | 24.73%  |
| 101-250    | 54        | 19.64%  |
| 51-100     | 44        | 16%     |
| 1-20       | 36        | 13.09%  |
| 501-1000   | 31        | 11.27%  |
| 21-50      | 21        | 7.64%   |
| 1001-2000  | 15        | 5.45%   |
| 2001-3000  | 3         | 1.09%   |
| Unknown    | 3         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 136       | 48.23%  |
| 21-50     | 51        | 18.09%  |
| 101-250   | 35        | 12.41%  |
| 51-100    | 25        | 8.87%   |
| 251-500   | 19        | 6.74%   |
| 501-1000  | 9         | 3.19%   |
| 1001-2000 | 4         | 1.42%   |
| Unknown   | 3         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                   | 3         | 3      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB             | 3         | 3      | 5.56%   |
| Samsung Electronics HD502HI 500GB           | 2         | 2      | 3.7%    |
| HGST HTS725050A7E630 500GB                  | 2         | 4      | 3.7%    |
| WDC WD5000LUCT-62C26Y0 500GB                | 1         | 1      | 1.85%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 1.85%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 1.85%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 1.85%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 1.85%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 1.85%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 1.85%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 1.85%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 1.85%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 1.85%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 1.85%   |
| tecmiyo SATA SSD 128GB                      | 1         | 1      | 1.85%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.85%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 1.85%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.85%   |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 1.85%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 2      | 1.85%   |
| Seagate ST3500413AS 500GB                   | 1         | 1      | 1.85%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 1.85%   |
| Seagate ST1000DM010-2EP102 1TB              | 1         | 1      | 1.85%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 1.85%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 1.85%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 1.85%   |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 1.85%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 1.85%   |
| Maxtor STM3320613AS 320GB                   | 1         | 1      | 1.85%   |
| Maxtor STM3160215AS 160GB                   | 1         | 1      | 1.85%   |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 1.85%   |
| Maxtor 32049H2 20GB                         | 1         | 1      | 1.85%   |
| Magnetic Data MD07500-ALDW-RO 752GB         | 1         | 1      | 1.85%   |
| KingSpec P3-128 128GB SSD                   | 1         | 1      | 1.85%   |
| Hitachi HTS723225L9A360 250GB               | 1         | 2      | 1.85%   |
| Hitachi HTS722010K9SA00 100GB               | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 28.3%   |
| WDC                 | 9         | 10     | 16.98%  |
| Samsung Electronics | 7         | 7      | 13.21%  |
| Hitachi             | 7         | 8      | 13.21%  |
| Maxtor              | 4         | 4      | 7.55%   |
| HGST                | 3         | 5      | 5.66%   |
| Toshiba             | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 2      | 3.77%   |
| WD MediaMax         | 1         | 1      | 1.89%   |
| tecmiyo             | 1         | 1      | 1.89%   |
| Magnetic Data       | 1         | 1      | 1.89%   |
| KingSpec            | 1         | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 31.25%  |
| WDC                 | 9         | 10     | 18.75%  |
| Hitachi             | 7         | 8      | 14.58%  |
| Samsung Electronics | 6         | 6      | 12.5%   |
| Maxtor              | 4         | 4      | 8.33%   |
| HGST                | 3         | 5      | 6.25%   |
| Toshiba             | 2         | 2      | 4.17%   |
| WD MediaMax         | 1         | 1      | 2.08%   |
| Magnetic Data       | 1         | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 53     | 90%     |
| SSD  | 4         | 4      | 8%      |
| NVMe | 1         | 1      | 2%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 156       | 270    | 56.52%  |
| Works    | 70        | 99     | 25.36%  |
| Malfunc  | 48        | 58     | 17.39%  |
| Failed   | 2         | 2      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 219       | 79.64%  |
| AMD                          | 15        | 5.45%   |
| Samsung Electronics          | 9         | 3.27%   |
| Realtek Semiconductor        | 5         | 1.82%   |
| VIA Technologies             | 4         | 1.45%   |
| Nvidia                       | 4         | 1.45%   |
| Silicon Motion               | 3         | 1.09%   |
| ASMedia Technology           | 3         | 1.09%   |
| Micron Technology            | 2         | 0.73%   |
| Kingston Technology Company  | 2         | 0.73%   |
| JMicron Technology           | 2         | 0.73%   |
| Toshiba America Info Systems | 1         | 0.36%   |
| SanDisk                      | 1         | 0.36%   |
| Micron/Crucial Technology    | 1         | 0.36%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.36%   |
| Marvell Technology Group     | 1         | 0.36%   |
| KIOXIA                       | 1         | 0.36%   |
| ADATA Technology             | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 27        | 8.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 22        | 6.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19        | 5.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16        | 4.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 4.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 4.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 3.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 3.6%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10        | 3%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 2.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 2.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.5%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 4         | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.2%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.9%    |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 0.9%    |
| VIA Serial ATA Controller                                                               | 2         | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.6%    |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 2         | 0.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.6%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.6%    |
| VIA VT8237/8251 Serial ATA Controller                                                   | 1         | 0.3%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.3%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 1         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 172       | 62.55%  |
| IDE  | 60        | 21.82%  |
| NVMe | 24        | 8.73%   |
| RAID | 18        | 6.55%   |
| SAS  | 1         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 234       | 92.13%  |
| AMD    | 19        | 7.48%   |
| ARM    | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6         | 2.34%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 2.34%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 2.34%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 5         | 1.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 5         | 1.95%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 4         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 1.56%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3         | 1.17%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 3         | 1.17%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 3         | 1.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 1.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.17%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.17%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 1.17%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 1.17%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 1.17%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.17%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.17%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 1.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 1.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3         | 1.17%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2         | 0.78%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.78%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 0.78%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2         | 0.78%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 2         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 0.78%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.78%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 2         | 0.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.78%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i3           | 64        | 25%     |
| Intel Core i5           | 60        | 23.44%  |
| Intel Core i7           | 33        | 12.89%  |
| Intel Pentium           | 21        | 8.2%    |
| Intel Pentium Dual-Core | 14        | 5.47%   |
| Intel Core 2 Duo        | 14        | 5.47%   |
| Intel Celeron           | 7         | 2.73%   |
| Intel Atom              | 6         | 2.34%   |
| AMD Ryzen 5             | 5         | 1.95%   |
| Intel Xeon              | 4         | 1.56%   |
| Intel Pentium Dual      | 4         | 1.56%   |
| Intel Genuine           | 4         | 1.56%   |
| AMD Ryzen 7             | 4         | 1.56%   |
| Other                   | 2         | 0.78%   |
| Intel Pentium D         | 1         | 0.39%   |
| Intel Pentium 4         | 1         | 0.39%   |
| Intel Core 2 Quad       | 1         | 0.39%   |
| ARM Allwinner           | 1         | 0.39%   |
| AMD Ryzen 9             | 1         | 0.39%   |
| AMD Ryzen 5 PRO         | 1         | 0.39%   |
| AMD Ryzen 3             | 1         | 0.39%   |
| AMD FX                  | 1         | 0.39%   |
| AMD E2                  | 1         | 0.39%   |
| AMD E1                  | 1         | 0.39%   |
| AMD Athlon Neo X2       | 1         | 0.39%   |
| AMD Athlon II Dual-Core | 1         | 0.39%   |
| AMD Athlon 64           | 1         | 0.39%   |
| AMD A4                  | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 183       | 71.76%  |
| 4      | 52        | 20.39%  |
| 6      | 8         | 3.14%   |
| 1      | 5         | 1.96%   |
| 8      | 4         | 1.57%   |
| 16     | 1         | 0.39%   |
| 12     | 1         | 0.39%   |
| 3      | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 254       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 161       | 63.14%  |
| 1      | 93        | 36.47%  |
| 4      | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 249       | 97.65%  |
| Unknown        | 4         | 1.57%   |
| 32-bit         | 2         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 25%     |
| 0x306a9    | 33        | 12.31%  |
| 0x206a7    | 23        | 8.58%   |
| 0x1067a    | 20        | 7.46%   |
| 0x20655    | 17        | 6.34%   |
| 0x40651    | 12        | 4.48%   |
| 0x406e3    | 10        | 3.73%   |
| 0x306c3    | 9         | 3.36%   |
| 0x806e9    | 8         | 2.99%   |
| 0x306d4    | 8         | 2.99%   |
| 0x30678    | 8         | 2.99%   |
| 0x6fd      | 5         | 1.87%   |
| 0x906e9    | 4         | 1.49%   |
| 0x806ea    | 4         | 1.49%   |
| 0x20652    | 3         | 1.12%   |
| 0x806ec    | 2         | 0.75%   |
| 0x6fb      | 2         | 0.75%   |
| 0x506e3    | 2         | 0.75%   |
| 0x306e4    | 2         | 0.75%   |
| 0x30661    | 2         | 0.75%   |
| 0x10676    | 2         | 0.75%   |
| 0x0a50000d | 2         | 0.75%   |
| 0x0800820d | 2         | 0.75%   |
| 0xf65      | 1         | 0.37%   |
| 0xa0652    | 1         | 0.37%   |
| 0x906eb    | 1         | 0.37%   |
| 0x806c1    | 1         | 0.37%   |
| 0x6ec      | 1         | 0.37%   |
| 0x6e8      | 1         | 0.37%   |
| 0x506c9    | 1         | 0.37%   |
| 0x406c4    | 1         | 0.37%   |
| 0x406c3    | 1         | 0.37%   |
| 0x206d7    | 1         | 0.37%   |
| 0x0a201016 | 1         | 0.37%   |
| 0x0a201005 | 1         | 0.37%   |
| 0x08701021 | 1         | 0.37%   |
| 0x08608103 | 1         | 0.37%   |
| 0x08600106 | 1         | 0.37%   |
| 0x08108102 | 1         | 0.37%   |
| 0x0810100b | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 45        | 17.58%  |
| SandyBridge   | 34        | 13.28%  |
| Haswell       | 31        | 12.11%  |
| Penryn        | 27        | 10.55%  |
| KabyLake      | 23        | 8.98%   |
| Westmere      | 20        | 7.81%   |
| Skylake       | 15        | 5.86%   |
| Silvermont    | 12        | 4.69%   |
| Core          | 9         | 3.52%   |
| Broadwell     | 9         | 3.52%   |
| Zen 3         | 4         | 1.56%   |
| Zen+          | 3         | 1.17%   |
| Zen 2         | 3         | 1.17%   |
| Unknown       | 3         | 1.17%   |
| P6            | 2         | 0.78%   |
| NetBurst      | 2         | 0.78%   |
| K8 Hammer     | 2         | 0.78%   |
| Bonnell       | 2         | 0.78%   |
| Zen           | 1         | 0.39%   |
| TigerLake     | 1         | 0.39%   |
| K10           | 1         | 0.39%   |
| Jaguar        | 1         | 0.39%   |
| Goldmont plus | 1         | 0.39%   |
| Goldmont      | 1         | 0.39%   |
| Excavator     | 1         | 0.39%   |
| CometLake     | 1         | 0.39%   |
| Bulldozer     | 1         | 0.39%   |
| Bobcat        | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 187       | 61.92%  |
| AMD                        | 57        | 18.87%  |
| Nvidia                     | 55        | 18.21%  |
| VIA Technologies           | 2         | 0.66%   |
| Matrox Electronics Systems | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 7.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 7.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 4.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 4.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 3.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 3.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 3.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 3.29%   |
| Intel HD Graphics 620                                                                    | 9         | 2.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 2.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 9         | 2.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.3%    |
| Intel HD Graphics 5500                                                                   | 7         | 2.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.64%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.64%   |
| Intel HD Graphics 630                                                                    | 4         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.32%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.99%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.99%   |
| Nvidia GT218M [GeForce G210M]                                                            | 2         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.66%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.66%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.66%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.66%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 2         | 0.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.66%   |
| Intel HD Graphics 530                                                                    | 2         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.66%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.66%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 2         | 0.66%   |
| AMD Renoir                                                                               | 2         | 0.66%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.66%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.66%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 141       | 55.08%  |
| 1 x AMD        | 35        | 13.67%  |
| 1 x Nvidia     | 30        | 11.72%  |
| Intel + Nvidia | 24        | 9.38%   |
| Intel + AMD    | 21        | 8.2%    |
| 1 x VIA        | 2         | 0.78%   |
| Other          | 1         | 0.39%   |
| 1 x Matrox     | 1         | 0.39%   |
| AMD + Nvidia   | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 229       | 88.08%  |
| Proprietary | 21        | 8.08%   |
| Unknown     | 10        | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 61.92%  |
| 1.01-2.0   | 51        | 19.62%  |
| 0.01-0.5   | 19        | 7.31%   |
| 0.51-1.0   | 16        | 6.15%   |
| 3.01-4.0   | 9         | 3.46%   |
| 7.01-8.0   | 3         | 1.15%   |
| 2.01-3.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 49        | 19.6%   |
| LG Display              | 36        | 14.4%   |
| AU Optronics            | 28        | 11.2%   |
| BOE                     | 19        | 7.6%    |
| Chimei Innolux          | 17        | 6.8%    |
| Hewlett-Packard         | 15        | 6%      |
| AOC                     | 13        | 5.2%    |
| Chi Mei Optoelectronics | 11        | 4.4%    |
| Acer                    | 8         | 3.2%    |
| KTC                     | 5         | 2%      |
| Goldstar                | 5         | 2%      |
| Apple                   | 5         | 2%      |
| Ancor Communications    | 4         | 1.6%    |
| Unknown                 | 4         | 1.6%    |
| Sharp                   | 3         | 1.2%    |
| Lenovo                  | 3         | 1.2%    |
| Dell                    | 3         | 1.2%    |
| BenQ                    | 3         | 1.2%    |
| Unknown (XXX)           | 2         | 0.8%    |
| Unknown                 | 2         | 0.8%    |
| ___                     | 1         | 0.4%    |
| Westinghouse            | 1         | 0.4%    |
| TSN                     | 1         | 0.4%    |
| TGC                     | 1         | 0.4%    |
| SKY                     | 1         | 0.4%    |
| PTW                     | 1         | 0.4%    |
| PiLot                   | 1         | 0.4%    |
| PANDA                   | 1         | 0.4%    |
| MStar                   | 1         | 0.4%    |
| LGD                     | 1         | 0.4%    |
| ITE                     | 1         | 0.4%    |
| InnoLux Display         | 1         | 0.4%    |
| Hitachi                 | 1         | 0.4%    |
| EMP                     | 1         | 0.4%    |
| AGO                     | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 4         | 1.58%   |
| Unknown                                                                  | 4         | 1.58%   |
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 1.19%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.19%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.19%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 3         | 1.19%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.19%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 3         | 1.19%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 3         | 1.19%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 2         | 0.79%   |
| Sharp HDMI SHP10DB 1920x1080 1330x750mm 60.1-inch                        | 2         | 0.79%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch        | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.79%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.79%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.79%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO213C 1366x768 309x174mm 14.0-inch            | 2         | 0.79%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.79%   |
| Acer V193HQ ACR00F9 1366x768 410x230mm 18.5-inch                         | 2         | 0.79%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.4%    |
| Westinghouse LED-TV WET3663 1680x1050 640x384mm 29.4-inch                | 1         | 0.4%    |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.4%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.4%    |
| TSN 24 Monitor TSN2400 1360x768 510x287mm 23.0-inch                      | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 110       | 46.03%  |
| 1920x1080 (FHD)    | 68        | 28.45%  |
| 1600x900 (HD+)     | 15        | 6.28%   |
| 1440x900 (WXGA+)   | 10        | 4.18%   |
| 2560x1440 (QHD)    | 5         | 2.09%   |
| 1680x1050 (WSXGA+) | 5         | 2.09%   |
| 1360x768           | 5         | 2.09%   |
| 1280x800 (WXGA)    | 4         | 1.67%   |
| 1280x1024 (SXGA)   | 4         | 1.67%   |
| 3840x2160 (4K)     | 2         | 0.84%   |
| 1920x540           | 2         | 0.84%   |
| 1920x1200 (WUXGA)  | 2         | 0.84%   |
| 2160x1440          | 1         | 0.42%   |
| 1680x945           | 1         | 0.42%   |
| 1600x1200          | 1         | 0.42%   |
| 1280x720 (HD)      | 1         | 0.42%   |
| 1152x864           | 1         | 0.42%   |
| 1024x768 (XGA)     | 1         | 0.42%   |
| 1024x600           | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 100       | 39.84%  |
| 18      | 21        | 8.37%   |
| 13      | 15        | 5.98%   |
| 21      | 14        | 5.58%   |
| 14      | 13        | 5.18%   |
| 19      | 11        | 4.38%   |
| 23      | 9         | 3.59%   |
| 17      | 9         | 3.59%   |
| 27      | 8         | 3.19%   |
| 20      | 8         | 3.19%   |
| Unknown | 8         | 3.19%   |
| 12      | 7         | 2.79%   |
| 24      | 5         | 1.99%   |
| 52      | 4         | 1.59%   |
| 22      | 4         | 1.59%   |
| 60      | 2         | 0.8%    |
| 11      | 2         | 0.8%    |
| 10      | 2         | 0.8%    |
| 72      | 1         | 0.4%    |
| 48      | 1         | 0.4%    |
| 46      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 37      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 31      | 1         | 0.4%    |
| 29      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 121       | 48.59%  |
| 401-500     | 53        | 21.29%  |
| 501-600     | 22        | 8.84%   |
| 201-300     | 16        | 6.43%   |
| 351-400     | 15        | 6.02%   |
| 1001-1500   | 8         | 3.21%   |
| Unknown     | 8         | 3.21%   |
| 801-900     | 2         | 0.8%    |
| 601-700     | 2         | 0.8%    |
| 701-800     | 1         | 0.4%    |
| 1501-2000   | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 197       | 83.47%  |
| 16/10   | 21        | 8.9%    |
| Unknown | 6         | 2.54%   |
| 5/4     | 4         | 1.69%   |
| 4/3     | 4         | 1.69%   |
| 32/9    | 2         | 0.85%   |
| 6/5     | 1         | 0.42%   |
| 3/2     | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 98        | 39.2%   |
| 201-250        | 25        | 10%     |
| 151-200        | 25        | 10%     |
| 81-90          | 24        | 9.6%    |
| 141-150        | 22        | 8.8%    |
| More than 1000 | 8         | 3.2%    |
| 301-350        | 8         | 3.2%    |
| Unknown        | 8         | 3.2%    |
| 61-70          | 6         | 2.4%    |
| 71-80          | 5         | 2%      |
| 121-130        | 5         | 2%      |
| 351-500        | 3         | 1.2%    |
| 111-120        | 3         | 1.2%    |
| 501-1000       | 3         | 1.2%    |
| 51-60          | 2         | 0.8%    |
| 41-50          | 2         | 0.8%    |
| 131-140        | 2         | 0.8%    |
| 251-300        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 101       | 40.89%  |
| 51-100  | 84        | 34.01%  |
| 121-160 | 38        | 15.38%  |
| 1-50    | 10        | 4.05%   |
| Unknown | 8         | 3.24%   |
| 161-240 | 6         | 2.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 224       | 86.82%  |
| 2     | 22        | 8.53%   |
| 0     | 10        | 3.88%   |
| 3     | 2         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 155       | 37.99%  |
| Qualcomm Atheros                | 67        | 16.42%  |
| Intel                           | 65        | 15.93%  |
| Broadcom                        | 38        | 9.31%   |
| Ralink Technology               | 25        | 6.13%   |
| Ralink                          | 10        | 2.45%   |
| Qualcomm Atheros Communications | 7         | 1.72%   |
| MediaTek                        | 5         | 1.23%   |
| Broadcom Limited                | 5         | 1.23%   |
| Xiaomi                          | 4         | 0.98%   |
| Marvell Technology Group        | 4         | 0.98%   |
| VIA Technologies                | 3         | 0.74%   |
| Samsung Electronics             | 3         | 0.74%   |
| Nvidia                          | 3         | 0.74%   |
| D-Link System                   | 3         | 0.74%   |
| TP-Link                         | 2         | 0.49%   |
| Huawei Technologies             | 2         | 0.49%   |
| D-Link                          | 2         | 0.49%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.25%   |
| Sierra Wireless                 | 1         | 0.25%   |
| LG Electronics                  | 1         | 0.25%   |
| Hewlett-Packard                 | 1         | 0.25%   |
| AMD                             | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91        | 19.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 11.8%   |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 3.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 2.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.58%   |
| Ralink MT7601U Wireless Adapter                                   | 11        | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.93%   |
| Qualcomm Atheros AR9271 802.11n                                   | 7         | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 7         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.29%   |
| Ralink RT5370 Wireless Adapter                                    | 6         | 1.29%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5         | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.07%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 1.07%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.86%   |
| Intel Wireless 8260                                               | 4         | 0.86%   |
| Intel Wireless 7265                                               | 4         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.64%   |
| MediaTek moto g22                                                 | 3         | 0.64%   |
| Intel Wireless 7260                                               | 3         | 0.64%   |
| Intel Wireless 3160                                               | 3         | 0.64%   |
| Intel WiFi Link 5100                                              | 3         | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.43%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 25%     |
| Qualcomm Atheros                | 53        | 24.54%  |
| Broadcom                        | 29        | 13.43%  |
| Ralink Technology               | 25        | 11.57%  |
| Realtek Semiconductor           | 24        | 11.11%  |
| Ralink                          | 10        | 4.63%   |
| Qualcomm Atheros Communications | 7         | 3.24%   |
| D-Link System                   | 3         | 1.39%   |
| TP-Link                         | 2         | 0.93%   |
| MediaTek                        | 2         | 0.93%   |
| D-Link                          | 2         | 0.93%   |
| Broadcom Limited                | 2         | 0.93%   |
| Sierra Wireless                 | 1         | 0.46%   |
| Marvell Technology Group        | 1         | 0.46%   |
| Hewlett-Packard                 | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 15        | 6.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 13        | 6.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 12        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                      | 11        | 5.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 10        | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 9         | 4.17%   |
| Qualcomm Atheros AR9271 802.11n                                      | 7         | 3.24%   |
| Intel Wireless 8265 / 8275                                           | 7         | 3.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 2.78%   |
| Ralink RT5370 Wireless Adapter                                       | 6         | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 5         | 2.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 1.85%   |
| Intel Wireless 8260                                                  | 4         | 1.85%   |
| Intel Wireless 7265                                                  | 4         | 1.85%   |
| Intel Wireless 7260                                                  | 3         | 1.39%   |
| Intel Wireless 3160                                                  | 3         | 1.39%   |
| Intel WiFi Link 5100                                                 | 3         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 0.93%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 0.93%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 0.93%   |
| Intel Centrino Wireless-N 135                                        | 2         | 0.93%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 0.93%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 0.93%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 0.93%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                | 1         | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.46%   |
| Sierra Wireless EM7305                                               | 1         | 0.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 147       | 59.27%  |
| Intel                      | 42        | 16.94%  |
| Qualcomm Atheros           | 20        | 8.06%   |
| Broadcom                   | 13        | 5.24%   |
| Xiaomi                     | 4         | 1.61%   |
| VIA Technologies           | 3         | 1.21%   |
| Samsung Electronics        | 3         | 1.21%   |
| Nvidia                     | 3         | 1.21%   |
| MediaTek                   | 3         | 1.21%   |
| Marvell Technology Group   | 3         | 1.21%   |
| Broadcom Limited           | 3         | 1.21%   |
| ZTE WCDMA Technologies MSM | 1         | 0.4%    |
| LG Electronics             | 1         | 0.4%    |
| Huawei Technologies        | 1         | 0.4%    |
| AMD                        | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91        | 36.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 22.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 2.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.2%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.2%    |
| MediaTek moto g22                                                 | 3         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.8%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.8%    |
| Intel PRO/100 VE Network Connection                               | 2         | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 2         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.8%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.8%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.8%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.8%    |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.4%    |
| Nvidia MCP89 Ethernet                                             | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.4%    |
| Nvidia MCP77 Ethernet                                             | 1         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.4%    |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.4%    |
| Intel WiMAX Connection 2400m                                      | 1         | 0.4%    |
| Intel Ethernet Connection I218-V                                  | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 234       | 54.17%  |
| WiFi     | 197       | 45.6%   |
| Modem    | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 63.75%  |
| Ethernet | 91        | 36.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 154       | 59.46%  |
| 1     | 98        | 37.84%  |
| 0     | 6         | 2.32%   |
| 3     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 254       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 27.35%  |
| Qualcomm Atheros Communications | 15        | 12.82%  |
| Broadcom                        | 13        | 11.11%  |
| Realtek Semiconductor           | 9         | 7.69%   |
| Foxconn / Hon Hai               | 6         | 5.13%   |
| Lite-On Technology              | 5         | 4.27%   |
| IMC Networks                    | 5         | 4.27%   |
| Cambridge Silicon Radio         | 5         | 4.27%   |
| Apple                           | 5         | 4.27%   |
| Ralink                          | 4         | 3.42%   |
| Dell                            | 4         | 3.42%   |
| Toshiba                         | 3         | 2.56%   |
| Foxconn International           | 3         | 2.56%   |
| Ralink Technology               | 1         | 0.85%   |
| Marvell Semiconductor           | 1         | 0.85%   |
| ISSC                            | 1         | 0.85%   |
| Integrated System Solution      | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |
| Chicony Electronics             | 1         | 0.85%   |
| ASUSTek Computer                | 1         | 0.85%   |
| Alps Electric                   | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 21        | 17.95%  |
| Realtek Bluetooth Radio                               | 6         | 5.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 6         | 5.13%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 4.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5         | 4.27%   |
| Ralink RT3290 Bluetooth                               | 4         | 3.42%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 3.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3         | 2.56%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 2.56%   |
| Intel Bluetooth Device                                | 3         | 2.56%   |
| IMC Networks Bluetooth Device                         | 3         | 2.56%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 2.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3         | 2.56%   |
| Apple Bluetooth Host Controller                       | 3         | 2.56%   |
| Toshiba Bluetooth Device                              | 2         | 1.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 1.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 1.71%   |
| Dell Wireless 365 Bluetooth                           | 2         | 1.71%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.71%   |
| Toshiba BCM43142A0                                    | 1         | 0.85%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.85%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.85%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.85%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.85%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.85%   |
| Lite-On Wireless_Device                               | 1         | 0.85%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 0.85%   |
| Lite-On BCM43142A0                                    | 1         | 0.85%   |
| ISSC Bluetooth Device                                 | 1         | 0.85%   |
| Intel AX200 Bluetooth                                 | 1         | 0.85%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.85%   |
| IMC Networks Wireless_Device                          | 1         | 0.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.85%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.85%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 222       | 70.03%  |
| AMD                    | 44        | 13.88%  |
| Nvidia                 | 37        | 11.67%  |
| JMTek                  | 4         | 1.26%   |
| VIA Technologies       | 3         | 0.95%   |
| Texas Instruments      | 1         | 0.32%   |
| Medeli Electronics     | 1         | 0.32%   |
| Logitech               | 1         | 0.32%   |
| Logic3 / SpectraVideo  | 1         | 0.32%   |
| Guillemot              | 1         | 0.32%   |
| Goldvish               | 1         | 0.32%   |
| Generalplus Technology | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 40        | 10.96%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 10.14%  |
| Intel Sunrise Point-LP HD Audio                                            | 27        | 7.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20        | 5.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 5.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 4.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 4.11%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 4.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 3.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 11        | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 2.47%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 1.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.64%   |
| Nvidia High Definition Audio Controller                                    | 5         | 1.37%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 1.37%   |
| JMTek USB PnP Audio Device                                                 | 4         | 1.1%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 3         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.55%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.55%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.55%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.55%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 39        | 22.81%  |
| SK hynix            | 32        | 18.71%  |
| Samsung Electronics | 32        | 18.71%  |
| Micron Technology   | 22        | 12.87%  |
| Kingston            | 12        | 7.02%   |
| A-DATA Technology   | 10        | 5.85%   |
| Nanya Technology    | 4         | 2.34%   |
| Crucial             | 4         | 2.34%   |
| TwinMOS             | 3         | 1.75%   |
| Ramaxel Technology  | 2         | 1.17%   |
| Thermaltake         | 1         | 0.58%   |
| Team                | 1         | 0.58%   |
| SemsoTai            | 1         | 0.58%   |
| Patriot             | 1         | 0.58%   |
| GeIL                | 1         | 0.58%   |
| Elpida              | 1         | 0.58%   |
| Dynet               | 1         | 0.58%   |
| CSX                 | 1         | 0.58%   |
| Corsair             | 1         | 0.58%   |
| ASint Technology    | 1         | 0.58%   |
| Unknown             | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 6         | 3.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 5         | 2.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 2.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 2.11%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 3         | 1.58%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 1.05%   |
| Unknown RAM Module 4GB SODIMM 1066MT/s                    | 2         | 1.05%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 1.05%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 1.05%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 1.05%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.05%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 2         | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 2         | 1.05%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s      | 2         | 1.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.05%   |
| Nanya RAM Module 8GB SODIMM DDR4 2667MT/s                 | 2         | 1.05%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2         | 1.05%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s     | 2         | 1.05%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1334MT/s  | 2         | 1.05%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s               | 2         | 1.05%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR2                        | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                 | 1         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR2                     | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s             | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM SDRAM                      | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s               | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s               | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 76        | 56.3%   |
| DDR4    | 30        | 22.22%  |
| SDRAM   | 10        | 7.41%   |
| DDR2    | 9         | 6.67%   |
| Unknown | 7         | 5.19%   |
| LPDDR4  | 1         | 0.74%   |
| LPDDR3  | 1         | 0.74%   |
| DDR     | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 60.31%  |
| DIMM         | 51        | 38.93%  |
| Row Of Chips | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 70        | 46.05%  |
| 2048  | 38        | 25%     |
| 8192  | 27        | 17.76%  |
| 1024  | 8         | 5.26%   |
| 32768 | 4         | 2.63%   |
| 16384 | 3         | 1.97%   |
| 512   | 2         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 42        | 27.45%  |
| 1333    | 27        | 17.65%  |
| 2667    | 13        | 8.5%    |
| 2133    | 7         | 4.58%   |
| 1334    | 7         | 4.58%   |
| 800     | 7         | 4.58%   |
| Unknown | 7         | 4.58%   |
| 3200    | 5         | 3.27%   |
| 2400    | 4         | 2.61%   |
| 1067    | 4         | 2.61%   |
| 1066    | 4         | 2.61%   |
| 667     | 4         | 2.61%   |
| 4199    | 3         | 1.96%   |
| 3600    | 2         | 1.31%   |
| 3266    | 2         | 1.31%   |
| 533     | 2         | 1.31%   |
| 3800    | 1         | 0.65%   |
| 3066    | 1         | 0.65%   |
| 3000    | 1         | 0.65%   |
| 2666    | 1         | 0.65%   |
| 2200    | 1         | 0.65%   |
| 1867    | 1         | 0.65%   |
| 1800    | 1         | 0.65%   |
| 1648    | 1         | 0.65%   |
| 1639    | 1         | 0.65%   |
| 1400    | 1         | 0.65%   |
| 333     | 1         | 0.65%   |
| 266     | 1         | 0.65%   |
| 200     | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 10        | 62.5%   |
| Seiko Epson        | 4         | 25%     |
| Hewlett-Packard    | 1         | 6.25%   |
| Brother Industries | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Canon LBP6020                                                         | 2         | 12.5%   |
| Canon LBP6000                                                         | 2         | 12.5%   |
| Seiko Epson XP-240 Series                                             | 1         | 6.25%   |
| Seiko Epson XP-200 Series                                             | 1         | 6.25%   |
| Seiko Epson Printer                                                   | 1         | 6.25%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 6.25%   |
| HP DeskJet 5810 series                                                | 1         | 6.25%   |
| Canon MG5700 series                                                   | 1         | 6.25%   |
| Canon MF3010                                                          | 1         | 6.25%   |
| Canon LBP6030w/6018w                                                  | 1         | 6.25%   |
| Canon LBP3010/LBP3018/LBP3050                                         | 1         | 6.25%   |
| Canon LBP3000                                                         | 1         | 6.25%   |
| Canon LBP2900                                                         | 1         | 6.25%   |
| Brother MFC-J480DW                                                    | 1         | 6.25%   |

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


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 25.87%  |
| Microdia                               | 23        | 16.08%  |
| Realtek Semiconductor                  | 12        | 8.39%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 7.69%   |
| Bison Electronics                      | 9         | 6.29%   |
| Sunplus Innovation Technology          | 8         | 5.59%   |
| IMC Networks                           | 6         | 4.2%    |
| Suyin                                  | 5         | 3.5%    |
| Apple                                  | 5         | 3.5%    |
| Syntek                                 | 4         | 2.8%    |
| Silicon Motion                         | 3         | 2.1%    |
| Quanta                                 | 3         | 2.1%    |
| Samsung Electronics                    | 2         | 1.4%    |
| Lite-On Technology                     | 2         | 1.4%    |
| Alcor Micro                            | 2         | 1.4%    |
| Sonix Technology                       | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| Primax Electronics                     | 1         | 0.7%    |
| Pixart Imaging                         | 1         | 0.7%    |
| Microsoft                              | 1         | 0.7%    |
| GEMBIRD                                | 1         | 0.7%    |
| Cubeternet                             | 1         | 0.7%    |
| Aveo Technology                        | 1         | 0.7%    |
| Arkmicro Technologies                  | 1         | 0.7%    |
| ALi                                    | 1         | 0.7%    |
| Acer                                   | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 6         | 4.17%   |
| Chicony TOSHIBA Web Camera - HD                                          | 6         | 4.17%   |
| Bison Lenovo EasyCamera                                                  | 6         | 4.17%   |
| Chicony Integrated Camera                                                | 5         | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 2.08%   |
| Microdia Integrated Webcam                                               | 3         | 2.08%   |
| Chicony HD WebCam                                                        | 3         | 2.08%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 1.39%   |
| Suyin HP Truevision HD                                                   | 2         | 1.39%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.39%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 2         | 1.39%   |
| Realtek HP Truevision HD                                                 | 2         | 1.39%   |
| IMC Networks Lenovo EasyCamera                                           | 2         | 1.39%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.39%   |
| Chicony HP TrueVision HD                                                 | 2         | 1.39%   |
| Chicony HP HD Webcam [Fixed]                                             | 2         | 1.39%   |
| Chicony Asus Integrated 0.3M UVC Webcam                                  | 2         | 1.39%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.39%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 2         | 1.39%   |
| Apple Built-in iSight                                                    | 2         | 1.39%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.69%   |
| Syntek EasyCamera                                                        | 1         | 0.69%   |
| Suyin WebCam                                                             | 1         | 0.69%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.69%   |
| Sunplus Laptop Integrated Webcam HD                                      | 1         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.69%   |
| Sunplus Dell HD Webcam                                                   | 1         | 0.69%   |
| Sunplus Asus Webcam                                                      | 1         | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                                               | 1         | 0.69%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 0.69%   |
| Silicon Motion WebCam SC-10HDD12636N                                     | 1         | 0.69%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 0.69%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 0.69%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 12        | 70.59%  |
| Synaptics             | 2         | 11.76%  |
| AuthenTec             | 2         | 11.76%  |
| Elan Microelectronics | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 5         | 29.41%  |
| Validity Sensors VFS491                           | 3         | 17.65%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.76%  |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5.88%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5.88%   |
| Elan ELAN:Fingerprint                             | 1         | 5.88%   |
| AuthenTec AES2810                                 | 1         | 5.88%   |
| AuthenTec AES1600                                 | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 10        | 90.91%  |
| OmniKey  | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 36.36%  |
| Broadcom 5880                                                                | 4         | 36.36%  |
| OmniKey CardMan 4321                                                         | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 187       | 72.2%   |
| 1     | 62        | 23.94%  |
| 2     | 8         | 3.09%   |
| 3     | 2         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 22.62%  |
| Fingerprint reader       | 17        | 20.24%  |
| Net/wireless             | 13        | 15.48%  |
| Chipcard                 | 11        | 13.1%   |
| Multimedia controller    | 5         | 5.95%   |
| Communication controller | 5         | 5.95%   |
| Bluetooth                | 5         | 5.95%   |
| Storage                  | 3         | 3.57%   |
| Net/ethernet             | 2         | 2.38%   |
| Camera                   | 2         | 2.38%   |
| Sound                    | 1         | 1.19%   |
| Card reader              | 1         | 1.19%   |

