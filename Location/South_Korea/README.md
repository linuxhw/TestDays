Linux in South Korea - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/South_Korea/Desktop/README.md) and [notebooks](/Location/South_Korea/Notebook/README.md).

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

Total: 643

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | Z370 Extreme4               | Desktop     | [0f126ade53](https://linux-hardware.org/?probe=0f126ade53) | Apr 29, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [dca43563dd](https://linux-hardware.org/?probe=dca43563dd) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bab80153bf](https://linux-hardware.org/?probe=bab80153bf) | Apr 22, 2023 |
| Lenovo        | E520-15IKB 80WA             | Notebook    | [abd1d98b9b](https://linux-hardware.org/?probe=abd1d98b9b) | Apr 20, 2023 |
| Dell          | 0MR5MV A00                  | Desktop     | [ed13b58a51](https://linux-hardware.org/?probe=ed13b58a51) | Apr 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [62399bace9](https://linux-hardware.org/?probe=62399bace9) | Apr 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [1f3ed1329d](https://linux-hardware.org/?probe=1f3ed1329d) | Apr 16, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [30fdc58d69](https://linux-hardware.org/?probe=30fdc58d69) | Apr 12, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [9b39bc4979](https://linux-hardware.org/?probe=9b39bc4979) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [9ddd50e0ed](https://linux-hardware.org/?probe=9ddd50e0ed) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [36338ecf6e](https://linux-hardware.org/?probe=36338ecf6e) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f4343acc49](https://linux-hardware.org/?probe=f4343acc49) | Apr 03, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3e558165a4](https://linux-hardware.org/?probe=3e558165a4) | Apr 02, 2023 |
| Gigabyte      | GA-6LXSG 01234567           | Server      | [92bff0d0ac](https://linux-hardware.org/?probe=92bff0d0ac) | Apr 01, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [758bb2556e](https://linux-hardware.org/?probe=758bb2556e) | Apr 01, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [dfd9900ccf](https://linux-hardware.org/?probe=dfd9900ccf) | Mar 30, 2023 |
| Notebook      | N650DU                      | Notebook    | [e8ec3c6462](https://linux-hardware.org/?probe=e8ec3c6462) | Mar 30, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| Apple         | MacBook9,1                  | Notebook    | [9639f02d57](https://linux-hardware.org/?probe=9639f02d57) | Mar 25, 2023 |
| WEIPAI        | S15                         | Notebook    | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [9404efe255](https://linux-hardware.org/?probe=9404efe255) | Mar 18, 2023 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [5a9b5297c2](https://linux-hardware.org/?probe=5a9b5297c2) | Mar 16, 2023 |
| ECS2          | EASTWOOD2 V1.0              | Desktop     | [822e4fa621](https://linux-hardware.org/?probe=822e4fa621) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [0d12931010](https://linux-hardware.org/?probe=0d12931010) | Mar 11, 2023 |
| Dell          | 0TNXNR A01                  | Desktop     | [30fa0c9cb7](https://linux-hardware.org/?probe=30fa0c9cb7) | Mar 09, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [09ce898081](https://linux-hardware.org/?probe=09ce898081) | Mar 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [25cf039ffd](https://linux-hardware.org/?probe=25cf039ffd) | Feb 27, 2023 |
| Dell          | Latitude E5440              | Notebook    | [5546f00169](https://linux-hardware.org/?probe=5546f00169) | Feb 26, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [484e0755de](https://linux-hardware.org/?probe=484e0755de) | Feb 26, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [51e3518d50](https://linux-hardware.org/?probe=51e3518d50) | Feb 24, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Samsung       | 760XDA                      | Notebook    | [efa040a93f](https://linux-hardware.org/?probe=efa040a93f) | Feb 22, 2023 |
| Samsung       | 760XDA                      | Notebook    | [1ba36d420d](https://linux-hardware.org/?probe=1ba36d420d) | Feb 22, 2023 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [6ec55330a7](https://linux-hardware.org/?probe=6ec55330a7) | Feb 21, 2023 |
| Samsung       | DB400T7Y-Z202C SGL9325A0... | Desktop     | [b75c596e7f](https://linux-hardware.org/?probe=b75c596e7f) | Feb 21, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [c03dee89f6](https://linux-hardware.org/?probe=c03dee89f6) | Feb 17, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [a9d6ae7b72](https://linux-hardware.org/?probe=a9d6ae7b72) | Feb 17, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| Samsung       | 940XFG                      | Notebook    | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| ASRock        | Z790 Pro RS WiFi            | Desktop     | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| Samsung       | 900X5N                      | Notebook    | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [d1da7498da](https://linux-hardware.org/?probe=d1da7498da) | Feb 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b9fb1c5111](https://linux-hardware.org/?probe=b9fb1c5111) | Feb 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9b17a7541e](https://linux-hardware.org/?probe=9b17a7541e) | Jan 30, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [bb5e9ccd98](https://linux-hardware.org/?probe=bb5e9ccd98) | Jan 27, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [d54e25d6fb](https://linux-hardware.org/?probe=d54e25d6fb) | Jan 27, 2023 |
| HP            | Notebook                    | Notebook    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| ASUSTek       | X540UA                      | Notebook    | [39f992a141](https://linux-hardware.org/?probe=39f992a141) | Jan 22, 2023 |
| ASUSTek       | X540UA                      | Notebook    | [dda62597f7](https://linux-hardware.org/?probe=dda62597f7) | Jan 21, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [2ddc21d71f](https://linux-hardware.org/?probe=2ddc21d71f) | Jan 16, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [8975ee2ce6](https://linux-hardware.org/?probe=8975ee2ce6) | Jan 14, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [2f6c800e41](https://linux-hardware.org/?probe=2f6c800e41) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfca68067c](https://linux-hardware.org/?probe=dfca68067c) | Jan 10, 2023 |
| Samsung       | 760XDA                      | Notebook    | [06a850e558](https://linux-hardware.org/?probe=06a850e558) | Jan 10, 2023 |
| Samsung       | 760XDA                      | Notebook    | [180727ef64](https://linux-hardware.org/?probe=180727ef64) | Jan 10, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [37818477e0](https://linux-hardware.org/?probe=37818477e0) | Jan 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [a56af08eb5](https://linux-hardware.org/?probe=a56af08eb5) | Jan 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [e47684954b](https://linux-hardware.org/?probe=e47684954b) | Jan 04, 2023 |
| ELSKY         | M219FN-6C                   | Desktop     | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda96539d7](https://linux-hardware.org/?probe=eda96539d7) | Dec 26, 2022 |
| Lenovo        | ThinkPad E585 20KVS06F00    | Notebook    | [8c3bdcc48c](https://linux-hardware.org/?probe=8c3bdcc48c) | Dec 25, 2022 |
| Jooyon Tec... | J6BF                        | Notebook    | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [f244715ee3](https://linux-hardware.org/?probe=f244715ee3) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | Desktop     | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [2ebd48d256](https://linux-hardware.org/?probe=2ebd48d256) | Dec 22, 2022 |
| Gigabyte      | AERO 15 YC                  | Notebook    | [24e48000be](https://linux-hardware.org/?probe=24e48000be) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [d6f3d14b20](https://linux-hardware.org/?probe=d6f3d14b20) | Dec 22, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | Desktop     | [7020686bc7](https://linux-hardware.org/?probe=7020686bc7) | Dec 19, 2022 |
| LG Electro... | 15UD480-GX50K               | Notebook    | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [24182862cd](https://linux-hardware.org/?probe=24182862cd) | Dec 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [cfe8d55199](https://linux-hardware.org/?probe=cfe8d55199) | Dec 14, 2022 |
| Samsung       | 550XED                      | Notebook    | [8e5bdc1eab](https://linux-hardware.org/?probe=8e5bdc1eab) | Dec 14, 2022 |
| Samsung       | 550XED                      | Notebook    | [3165e8b2df](https://linux-hardware.org/?probe=3165e8b2df) | Dec 14, 2022 |
| ASUSTek       | Zenbook UP6502ZA_UP6502Z... | Convertible | [85c2b907d7](https://linux-hardware.org/?probe=85c2b907d7) | Dec 14, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | Notebook    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [a2f1af21a0](https://linux-hardware.org/?probe=a2f1af21a0) | Dec 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [a505c76dfa](https://linux-hardware.org/?probe=a505c76dfa) | Dec 13, 2022 |
| LG Electro... | 15ND530-GX3FK               | Notebook    | [47b90cbe2a](https://linux-hardware.org/?probe=47b90cbe2a) | Dec 12, 2022 |
| Google        | Peppy                       | Notebook    | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| Huanan        | X58-RX3.0 V110              | Desktop     | [32e6a4d219](https://linux-hardware.org/?probe=32e6a4d219) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | Notebook    | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [5254612ca4](https://linux-hardware.org/?probe=5254612ca4) | Dec 09, 2022 |
| Samsung       | 550XED                      | Notebook    | [705495532e](https://linux-hardware.org/?probe=705495532e) | Dec 09, 2022 |
| Samsung       | 550XED                      | Notebook    | [0df3845885](https://linux-hardware.org/?probe=0df3845885) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | Notebook    | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | Notebook    | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Samsung       | 550XED                      | Notebook    | [0ce3bd481f](https://linux-hardware.org/?probe=0ce3bd481f) | Dec 07, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | Notebook    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | 370A NOK                    | Desktop     | [b06728a8bf](https://linux-hardware.org/?probe=b06728a8bf) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | Desktop     | [6047fbcb06](https://linux-hardware.org/?probe=6047fbcb06) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | Desktop     | [9aebb424cc](https://linux-hardware.org/?probe=9aebb424cc) | Dec 05, 2022 |
| Samsung       | 550XED                      | Notebook    | [fee55cdb61](https://linux-hardware.org/?probe=fee55cdb61) | Dec 02, 2022 |
| Samsung       | 550XED                      | Notebook    | [d8894f602a](https://linux-hardware.org/?probe=d8894f602a) | Dec 01, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | Desktop     | [6d4f229020](https://linux-hardware.org/?probe=6d4f229020) | Nov 29, 2022 |
| Dell          | Latitude E5440              | Notebook    | [90d18073d6](https://linux-hardware.org/?probe=90d18073d6) | Nov 29, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Samsung       | 550XED                      | Notebook    | [143518e596](https://linux-hardware.org/?probe=143518e596) | Nov 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [d96c2be612](https://linux-hardware.org/?probe=d96c2be612) | Nov 23, 2022 |
| Samsung       | 950XED                      | Notebook    | [48213c8f60](https://linux-hardware.org/?probe=48213c8f60) | Nov 23, 2022 |
| TMAX          | TM101W638L                  | Tablet      | [ac8adad039](https://linux-hardware.org/?probe=ac8adad039) | Nov 22, 2022 |
| Samsung       | 950XED                      | Notebook    | [0c91469d8f](https://linux-hardware.org/?probe=0c91469d8f) | Nov 21, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6d90726959](https://linux-hardware.org/?probe=6d90726959) | Nov 21, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2bc3a22052](https://linux-hardware.org/?probe=2bc3a22052) | Nov 20, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [d5c76baafa](https://linux-hardware.org/?probe=d5c76baafa) | Nov 18, 2022 |
| Samsung       | 550XED                      | Notebook    | [06722b1fee](https://linux-hardware.org/?probe=06722b1fee) | Nov 16, 2022 |
| Samsung       | 950XED                      | Notebook    | [2558d99814](https://linux-hardware.org/?probe=2558d99814) | Nov 16, 2022 |
| Samsung       | 950XED                      | Notebook    | [ddcb4e15c7](https://linux-hardware.org/?probe=ddcb4e15c7) | Nov 14, 2022 |
| Samsung       | 550XED                      | Notebook    | [bbebe45363](https://linux-hardware.org/?probe=bbebe45363) | Nov 13, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [9d91de9f87](https://linux-hardware.org/?probe=9d91de9f87) | Nov 12, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [da754cf27a](https://linux-hardware.org/?probe=da754cf27a) | Nov 11, 2022 |
| Samsung       | 550XED                      | Notebook    | [60c1aa4cc9](https://linux-hardware.org/?probe=60c1aa4cc9) | Nov 10, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [0ccbbf67e8](https://linux-hardware.org/?probe=0ccbbf67e8) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [9cdaa4c88b](https://linux-hardware.org/?probe=9cdaa4c88b) | Nov 09, 2022 |
| Samsung       | 550XED                      | Notebook    | [fc6d96f9fe](https://linux-hardware.org/?probe=fc6d96f9fe) | Nov 06, 2022 |
| Samsung       | 550XED                      | Notebook    | [6db345f53d](https://linux-hardware.org/?probe=6db345f53d) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Samsung       | 550XED                      | Notebook    | [6992db47be](https://linux-hardware.org/?probe=6992db47be) | Nov 02, 2022 |
| Samsung       | 950XED                      | Notebook    | [821bc59c17](https://linux-hardware.org/?probe=821bc59c17) | Nov 02, 2022 |
| Samsung       | 550XED                      | Notebook    | [3b04d21991](https://linux-hardware.org/?probe=3b04d21991) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| MS            | MPGIO                       | Notebook    | [4fc8637bf3](https://linux-hardware.org/?probe=4fc8637bf3) | Nov 01, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| WTM           | W-N95 B0                    | Desktop     | [56611d3c8f](https://linux-hardware.org/?probe=56611d3c8f) | Oct 31, 2022 |
| LG Electro... | 15Z980-HA76K                | Notebook    | [914156672d](https://linux-hardware.org/?probe=914156672d) | Oct 30, 2022 |
| Samsung       | 950XED                      | Notebook    | [350a0f9d44](https://linux-hardware.org/?probe=350a0f9d44) | Oct 28, 2022 |
| Samsung       | 550XED                      | Notebook    | [1ebb9be92b](https://linux-hardware.org/?probe=1ebb9be92b) | Oct 28, 2022 |
| Samsung       | 550XED                      | Notebook    | [110d85c2e0](https://linux-hardware.org/?probe=110d85c2e0) | Oct 27, 2022 |
| Samsung       | 950XED                      | Notebook    | [a636a02096](https://linux-hardware.org/?probe=a636a02096) | Oct 27, 2022 |
| HP            | 8425                        | Desktop     | [6d26af6597](https://linux-hardware.org/?probe=6d26af6597) | Oct 27, 2022 |
| LG Electro... | 15Z90N-HA76K                | Notebook    | [7805c272fb](https://linux-hardware.org/?probe=7805c272fb) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Dell          | Precision 7520              | Notebook    | [366eed3b66](https://linux-hardware.org/?probe=366eed3b66) | Oct 20, 2022 |
| Dell          | Precision 7520              | Notebook    | [8c2829bbb2](https://linux-hardware.org/?probe=8c2829bbb2) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ad1d808caa](https://linux-hardware.org/?probe=ad1d808caa) | Oct 14, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [40dd630e96](https://linux-hardware.org/?probe=40dd630e96) | Oct 05, 2022 |
| Lenovo        | 3135 NOK                    | Mini pc     | [bffdecaf8f](https://linux-hardware.org/?probe=bffdecaf8f) | Oct 04, 2022 |
| Lenovo        | 3135 NOK                    | Mini pc     | [4b13ced18f](https://linux-hardware.org/?probe=4b13ced18f) | Oct 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [2fccc9ec66](https://linux-hardware.org/?probe=2fccc9ec66) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [5c2eac6d83](https://linux-hardware.org/?probe=5c2eac6d83) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [ea7d5b0424](https://linux-hardware.org/?probe=ea7d5b0424) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [156da35e98](https://linux-hardware.org/?probe=156da35e98) | Aug 24, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | Notebook    | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| Samsung       | 950QDA                      | Convertible | [e03a1c1a0d](https://linux-hardware.org/?probe=e03a1c1a0d) | Aug 16, 2022 |
| MSI           | MAG B660M MORTAR WIFI       | Desktop     | [4e1b75908c](https://linux-hardware.org/?probe=4e1b75908c) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASRock        | B250M Pro4                  | Desktop     | [59704c823a](https://linux-hardware.org/?probe=59704c823a) | Jul 29, 2022 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJC... | Notebook    | [ce2df1e866](https://linux-hardware.org/?probe=ce2df1e866) | Jul 18, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [87edfcaadf](https://linux-hardware.org/?probe=87edfcaadf) | Jul 09, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [8971b67abc](https://linux-hardware.org/?probe=8971b67abc) | Jul 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [251bc4d58d](https://linux-hardware.org/?probe=251bc4d58d) | Jul 04, 2022 |
| Gigabyte      | C621-SD8 M18802             | Server      | [52aeaedd47](https://linux-hardware.org/?probe=52aeaedd47) | Jun 30, 2022 |
| Gigabyte      | MQLP5AP-00                  | Desktop     | [8014a14842](https://linux-hardware.org/?probe=8014a14842) | Jun 30, 2022 |
| LG Electro... | 14T90N-VR56K                | Convertible | [22f978c26c](https://linux-hardware.org/?probe=22f978c26c) | Jun 26, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | Notebook    | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |
| LG Electro... | 14Z90N-VA76K                | Notebook    | [9e606a176f](https://linux-hardware.org/?probe=9e606a176f) | Jun 24, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [b93d65dd64](https://linux-hardware.org/?probe=b93d65dd64) | Jun 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3e3fb0129e](https://linux-hardware.org/?probe=3e3fb0129e) | Jun 18, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [95ec23c2e9](https://linux-hardware.org/?probe=95ec23c2e9) | Jun 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [014c9a184e](https://linux-hardware.org/?probe=014c9a184e) | Jun 06, 2022 |
| LG Electro... | Z360-GH6SK                  | Notebook    | [cb91c2c2bd](https://linux-hardware.org/?probe=cb91c2c2bd) | Jun 02, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [9b67243691](https://linux-hardware.org/?probe=9b67243691) | May 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f941ba9fe](https://linux-hardware.org/?probe=4f941ba9fe) | May 24, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [617edab20c](https://linux-hardware.org/?probe=617edab20c) | May 20, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [6aea229376](https://linux-hardware.org/?probe=6aea229376) | May 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [feb7ce77bf](https://linux-hardware.org/?probe=feb7ce77bf) | May 18, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [2d23125cd0](https://linux-hardware.org/?probe=2d23125cd0) | May 15, 2022 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [e5cf57d2f4](https://linux-hardware.org/?probe=e5cf57d2f4) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [7286fd4e36](https://linux-hardware.org/?probe=7286fd4e36) | May 11, 2022 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [55f1cc4480](https://linux-hardware.org/?probe=55f1cc4480) | May 10, 2022 |
| Lenovo        | ThinkPad 8 20BN0002KR       | Tablet      | [8e59716f95](https://linux-hardware.org/?probe=8e59716f95) | May 07, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [80bdc044eb](https://linux-hardware.org/?probe=80bdc044eb) | May 01, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [6df44e9098](https://linux-hardware.org/?probe=6df44e9098) | Apr 29, 2022 |
| Teclast       | tPAD                        | Notebook    | [2b86292373](https://linux-hardware.org/?probe=2b86292373) | Apr 20, 2022 |
| Samsung       | Galaxy Book 12              | Tablet      | [a4d7160eb9](https://linux-hardware.org/?probe=a4d7160eb9) | Apr 17, 2022 |
| Samsung       | Galaxy Book 12              | Tablet      | [71624fff28](https://linux-hardware.org/?probe=71624fff28) | Apr 17, 2022 |
| Wolfnfox      | WF-TBAT                     | Notebook    | [7d04cc8361](https://linux-hardware.org/?probe=7d04cc8361) | Apr 13, 2022 |
| Teclast       | tPAD                        | Notebook    | [a9f93e289b](https://linux-hardware.org/?probe=a9f93e289b) | Apr 13, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9a15614b1e](https://linux-hardware.org/?probe=9a15614b1e) | Apr 13, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [ed880374c4](https://linux-hardware.org/?probe=ed880374c4) | Apr 10, 2022 |
| MECHREVO      | Taitan Series GM7TG0M       | Notebook    | [948d29a218](https://linux-hardware.org/?probe=948d29a218) | Apr 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ccbdd7504c](https://linux-hardware.org/?probe=ccbdd7504c) | Apr 08, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [14b7f50736](https://linux-hardware.org/?probe=14b7f50736) | Apr 08, 2022 |
| Teclast       | tPAD                        | Notebook    | [5eddc816df](https://linux-hardware.org/?probe=5eddc816df) | Apr 07, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [1874ac7edf](https://linux-hardware.org/?probe=1874ac7edf) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [f22fa67906](https://linux-hardware.org/?probe=f22fa67906) | Apr 01, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [8fc09857a6](https://linux-hardware.org/?probe=8fc09857a6) | Apr 01, 2022 |
| Intel         | powered classmate PC        | Notebook    | [8ce4fa1757](https://linux-hardware.org/?probe=8ce4fa1757) | Apr 01, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [90aa422ea2](https://linux-hardware.org/?probe=90aa422ea2) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6c36c54313](https://linux-hardware.org/?probe=6c36c54313) | Mar 31, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a8cacc7845](https://linux-hardware.org/?probe=a8cacc7845) | Mar 27, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [fa4526e9f3](https://linux-hardware.org/?probe=fa4526e9f3) | Mar 24, 2022 |
| MSI           | GF75 Thin 9SCXR             | Notebook    | [df19241968](https://linux-hardware.org/?probe=df19241968) | Mar 20, 2022 |
| ECS           | PB02CF                      | Server      | [0600880dba](https://linux-hardware.org/?probe=0600880dba) | Mar 19, 2022 |
| MSI           | GF75 Thin 9SCXR             | Notebook    | [b3458eda8f](https://linux-hardware.org/?probe=b3458eda8f) | Mar 14, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [4d5412852b](https://linux-hardware.org/?probe=4d5412852b) | Mar 13, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [05cdb119e9](https://linux-hardware.org/?probe=05cdb119e9) | Mar 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [95ff70277e](https://linux-hardware.org/?probe=95ff70277e) | Feb 24, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [bb04a03420](https://linux-hardware.org/?probe=bb04a03420) | Feb 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [38ad42c186](https://linux-hardware.org/?probe=38ad42c186) | Feb 22, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [968b189e38](https://linux-hardware.org/?probe=968b189e38) | Feb 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [d8f6d95994](https://linux-hardware.org/?probe=d8f6d95994) | Feb 14, 2022 |
| HANSUNG CO... | EX58                        | Notebook    | [7c2a023530](https://linux-hardware.org/?probe=7c2a023530) | Feb 10, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [ed95e4c1c7](https://linux-hardware.org/?probe=ed95e4c1c7) | Feb 09, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [a597b083c9](https://linux-hardware.org/?probe=a597b083c9) | Feb 08, 2022 |
| Google        | Ampton                      | Notebook    | [0f1564bb4a](https://linux-hardware.org/?probe=0f1564bb4a) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65a6ca3880](https://linux-hardware.org/?probe=65a6ca3880) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [144717a1f1](https://linux-hardware.org/?probe=144717a1f1) | Feb 04, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [14f8855baa](https://linux-hardware.org/?probe=14f8855baa) | Feb 03, 2022 |
| ECS           | PB02CF                      | Server      | [9f7f807004](https://linux-hardware.org/?probe=9f7f807004) | Jan 30, 2022 |
| ECS           | PB02CF                      | Server      | [594030dfa1](https://linux-hardware.org/?probe=594030dfa1) | Jan 30, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [7f9793a709](https://linux-hardware.org/?probe=7f9793a709) | Jan 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [2c22ac6a5f](https://linux-hardware.org/?probe=2c22ac6a5f) | Jan 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [882dab7b0e](https://linux-hardware.org/?probe=882dab7b0e) | Jan 22, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [c081d60b2a](https://linux-hardware.org/?probe=c081d60b2a) | Jan 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [11d1870f98](https://linux-hardware.org/?probe=11d1870f98) | Jan 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [d0d21d2892](https://linux-hardware.org/?probe=d0d21d2892) | Jan 18, 2022 |
| LG Electro... | 16ZD90P-GX7LK               | Notebook    | [0870fd8772](https://linux-hardware.org/?probe=0870fd8772) | Dec 29, 2021 |
| Lenovo        | G480 20149                  | Notebook    | [08a0d07d28](https://linux-hardware.org/?probe=08a0d07d28) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [23e536f087](https://linux-hardware.org/?probe=23e536f087) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [1f4a9c160f](https://linux-hardware.org/?probe=1f4a9c160f) | Dec 28, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [a8fbe33d19](https://linux-hardware.org/?probe=a8fbe33d19) | Dec 26, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7843ddc3fb](https://linux-hardware.org/?probe=7843ddc3fb) | Dec 24, 2021 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [151434ab61](https://linux-hardware.org/?probe=151434ab61) | Dec 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [ff620ffdcd](https://linux-hardware.org/?probe=ff620ffdcd) | Dec 07, 2021 |
| ECS           | PB02CF                      | Server      | [ac300533fe](https://linux-hardware.org/?probe=ac300533fe) | Dec 04, 2021 |
| Jooyontech... | J3GP Pro                    | Notebook    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | Notebook    | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | Notebook    | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | Desktop     | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [4d11bd6b59](https://linux-hardware.org/?probe=4d11bd6b59) | Nov 20, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [b4c7522ea3](https://linux-hardware.org/?probe=b4c7522ea3) | Nov 15, 2021 |
| Samsung       | 950QDA                      | Convertible | [45d49f2001](https://linux-hardware.org/?probe=45d49f2001) | Nov 13, 2021 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [6f5255e0f2](https://linux-hardware.org/?probe=6f5255e0f2) | Nov 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [70074ebee1](https://linux-hardware.org/?probe=70074ebee1) | Nov 01, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| LG Electro... | 17ZD90P-GX7LK               | Notebook    | [23aa2c83ae](https://linux-hardware.org/?probe=23aa2c83ae) | Oct 27, 2021 |
| Intel         | NUC11PABi7 K90104-303       | Mini pc     | [0279a35638](https://linux-hardware.org/?probe=0279a35638) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2f6634b953](https://linux-hardware.org/?probe=2f6634b953) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fb8b55960a](https://linux-hardware.org/?probe=fb8b55960a) | Oct 20, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | Notebook    | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [e93b95fc3c](https://linux-hardware.org/?probe=e93b95fc3c) | Sep 30, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| HANSUNG CO... | TFX4150H                    | Notebook    | [11f2fbef85](https://linux-hardware.org/?probe=11f2fbef85) | Sep 29, 2021 |
| ASUSTek       | U36JC                       | Notebook    | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [54cd6887df](https://linux-hardware.org/?probe=54cd6887df) | Sep 21, 2021 |
| Clevo         | M740T/M760T                 | Notebook    | [7731b8340f](https://linux-hardware.org/?probe=7731b8340f) | Sep 17, 2021 |
| Samsung       | 400B4C/400B5C/200B4C/200... | Notebook    | [581ab7ecde](https://linux-hardware.org/?probe=581ab7ecde) | Sep 17, 2021 |
| LG Electro... | 16TD90P-GX56K               | Convertible | [448fe0cf6a](https://linux-hardware.org/?probe=448fe0cf6a) | Sep 11, 2021 |
| ECS           | PB02CF                      | Server      | [6aeb74b9f1](https://linux-hardware.org/?probe=6aeb74b9f1) | Sep 03, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [24de612862](https://linux-hardware.org/?probe=24de612862) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| LG Electro... | 14Z90N-VA76K                | Notebook    | [df36a7a61c](https://linux-hardware.org/?probe=df36a7a61c) | Aug 22, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [3abd60af90](https://linux-hardware.org/?probe=3abd60af90) | Aug 22, 2021 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | Notebook    | [e68dfe0824](https://linux-hardware.org/?probe=e68dfe0824) | Aug 19, 2021 |
| Apple         | MacBookPro15,2              | Notebook    | [c722c00c56](https://linux-hardware.org/?probe=c722c00c56) | Aug 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e47beb0587](https://linux-hardware.org/?probe=e47beb0587) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e7997203d4](https://linux-hardware.org/?probe=e7997203d4) | Aug 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [3147760301](https://linux-hardware.org/?probe=3147760301) | Aug 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [e523ad86d2](https://linux-hardware.org/?probe=e523ad86d2) | Aug 02, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [1e96b02bf3](https://linux-hardware.org/?probe=1e96b02bf3) | Jul 28, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [dc6d809e73](https://linux-hardware.org/?probe=dc6d809e73) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [c0869b1919](https://linux-hardware.org/?probe=c0869b1919) | Jul 23, 2021 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [972c061d3c](https://linux-hardware.org/?probe=972c061d3c) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4c15433f48](https://linux-hardware.org/?probe=4c15433f48) | Jul 21, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [2392366002](https://linux-hardware.org/?probe=2392366002) | Jul 16, 2021 |
| Dell          | 0J1C3P A00                  | Desktop     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | 3397                        | Desktop     | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae45f90535](https://linux-hardware.org/?probe=ae45f90535) | Jul 05, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| Lenovo        | 14ARE05 81X2                | Convertible | [3cd1b703c4](https://linux-hardware.org/?probe=3cd1b703c4) | Jun 28, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| ASRockRack    | WC621D8A-2T                 | Desktop     | [d9c47162dc](https://linux-hardware.org/?probe=d9c47162dc) | Jun 25, 2021 |
| ASRockRack    | WC621D8A-2T                 | Desktop     | [b568edaa5e](https://linux-hardware.org/?probe=b568edaa5e) | Jun 25, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [9c2b77b3c6](https://linux-hardware.org/?probe=9c2b77b3c6) | Jun 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [99b25335b3](https://linux-hardware.org/?probe=99b25335b3) | Jun 22, 2021 |
| WB            | J3160                       | All in one  | [88c472d69e](https://linux-hardware.org/?probe=88c472d69e) | Jun 18, 2021 |
| WB            | J3160                       | All in one  | [b889890a54](https://linux-hardware.org/?probe=b889890a54) | Jun 11, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [98faadcfa3](https://linux-hardware.org/?probe=98faadcfa3) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a19b25100c](https://linux-hardware.org/?probe=a19b25100c) | Jun 08, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [9aaad9b2d4](https://linux-hardware.org/?probe=9aaad9b2d4) | Jun 07, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [be07a70b2e](https://linux-hardware.org/?probe=be07a70b2e) | May 27, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [2aca6cd805](https://linux-hardware.org/?probe=2aca6cd805) | May 27, 2021 |
| Dell          | Latitude E6400              | Notebook    | [2a4c5f6eec](https://linux-hardware.org/?probe=2a4c5f6eec) | May 25, 2021 |
| Samsung       | R440/R480                   | Notebook    | [777c05d80b](https://linux-hardware.org/?probe=777c05d80b) | May 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f3cb68f8cf](https://linux-hardware.org/?probe=f3cb68f8cf) | May 13, 2021 |
| HP            | EliteBook 8540p (WQ983PA... | Notebook    | [28b1df49ae](https://linux-hardware.org/?probe=28b1df49ae) | May 11, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [3d6a52dd8e](https://linux-hardware.org/?probe=3d6a52dd8e) | May 11, 2021 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [a9245eb585](https://linux-hardware.org/?probe=a9245eb585) | May 11, 2021 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [965bc51c8d](https://linux-hardware.org/?probe=965bc51c8d) | May 06, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| ASRock        | A75M-ITX                    | Desktop     | [1ad3e30eec](https://linux-hardware.org/?probe=1ad3e30eec) | May 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [473f17b0f1](https://linux-hardware.org/?probe=473f17b0f1) | May 01, 2021 |
| LG Electro... | 15ND530-GX30K               | Notebook    | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [84f31a5fd7](https://linux-hardware.org/?probe=84f31a5fd7) | Apr 28, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [167aa11de4](https://linux-hardware.org/?probe=167aa11de4) | Apr 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [72d14b2ed7](https://linux-hardware.org/?probe=72d14b2ed7) | Apr 23, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [410e4fd232](https://linux-hardware.org/?probe=410e4fd232) | Apr 22, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2300013263](https://linux-hardware.org/?probe=2300013263) | Apr 18, 2021 |
| HP            | Stream Notebook PC 13       | Notebook    | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [fdac2fa1fd](https://linux-hardware.org/?probe=fdac2fa1fd) | Apr 14, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [b17bb9b31a](https://linux-hardware.org/?probe=b17bb9b31a) | Apr 12, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [c5e7a3d16e](https://linux-hardware.org/?probe=c5e7a3d16e) | Apr 09, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [7cac175bde](https://linux-hardware.org/?probe=7cac175bde) | Apr 07, 2021 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [d4399ab9d0](https://linux-hardware.org/?probe=d4399ab9d0) | Apr 06, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [51931e3821](https://linux-hardware.org/?probe=51931e3821) | Apr 05, 2021 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [b36716f462](https://linux-hardware.org/?probe=b36716f462) | Apr 02, 2021 |
| Samsung       | 400B4B/400B5B/200B4B/200... | Notebook    | [af785987c5](https://linux-hardware.org/?probe=af785987c5) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | Notebook    | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo        | ThinkPad 10 20C1001VKR      | Tablet      | [9b7a2a3d3b](https://linux-hardware.org/?probe=9b7a2a3d3b) | Mar 25, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [b55dc75624](https://linux-hardware.org/?probe=b55dc75624) | Mar 20, 2021 |
| Gigabyte      | B360M DS3H                  | Desktop     | [f7740321e0](https://linux-hardware.org/?probe=f7740321e0) | Mar 18, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [e459ded47c](https://linux-hardware.org/?probe=e459ded47c) | Mar 10, 2021 |
| Alienware     | m15 R4                      | Notebook    | [33977ceca8](https://linux-hardware.org/?probe=33977ceca8) | Mar 08, 2021 |
| Notebook      | W330SU2                     | Notebook    | [e5e71a4e94](https://linux-hardware.org/?probe=e5e71a4e94) | Mar 05, 2021 |
| Dell          | Inspiron 5590               | Notebook    | [94e3d38a99](https://linux-hardware.org/?probe=94e3d38a99) | Mar 04, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [15c42588c8](https://linux-hardware.org/?probe=15c42588c8) | Mar 04, 2021 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [541a436664](https://linux-hardware.org/?probe=541a436664) | Mar 02, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [8e6128682d](https://linux-hardware.org/?probe=8e6128682d) | Feb 28, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [778fcc3093](https://linux-hardware.org/?probe=778fcc3093) | Feb 28, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8dd1ebdfb8](https://linux-hardware.org/?probe=8dd1ebdfb8) | Feb 25, 2021 |
| Notebook      | N650DU                      | Notebook    | [beef9a4540](https://linux-hardware.org/?probe=beef9a4540) | Feb 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7ffa9ae08a](https://linux-hardware.org/?probe=7ffa9ae08a) | Feb 17, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a222f11ebf](https://linux-hardware.org/?probe=a222f11ebf) | Feb 09, 2021 |
| ECS           | PB02CF                      | Server      | [598d43b1f2](https://linux-hardware.org/?probe=598d43b1f2) | Feb 08, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [0de61d3d11](https://linux-hardware.org/?probe=0de61d3d11) | Feb 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [65aa2efd23](https://linux-hardware.org/?probe=65aa2efd23) | Feb 05, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [27d324f7e1](https://linux-hardware.org/?probe=27d324f7e1) | Feb 04, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [fc703c19dd](https://linux-hardware.org/?probe=fc703c19dd) | Feb 02, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [ba5f1e074b](https://linux-hardware.org/?probe=ba5f1e074b) | Feb 02, 2021 |
| MSI           | B360M PRO-VDH               | Desktop     | [59b7bd58df](https://linux-hardware.org/?probe=59b7bd58df) | Jan 30, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [a29449d114](https://linux-hardware.org/?probe=a29449d114) | Jan 27, 2021 |
| ECS           | PB02CF                      | Server      | [4c644b0fa9](https://linux-hardware.org/?probe=4c644b0fa9) | Jan 26, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [9595d4107b](https://linux-hardware.org/?probe=9595d4107b) | Jan 26, 2021 |
| sunxi         | Unknown                     | Soc         | [49e15041c4](https://linux-hardware.org/?probe=49e15041c4) | Jan 26, 2021 |
| HP            | Pavilion dv3                | Notebook    | [d563465019](https://linux-hardware.org/?probe=d563465019) | Jan 23, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a6226b7401](https://linux-hardware.org/?probe=a6226b7401) | Jan 20, 2021 |
| HP            | Pavilion dv3                | Notebook    | [7140d63f79](https://linux-hardware.org/?probe=7140d63f79) | Jan 16, 2021 |
| LG Electro... | 13Z940-MF6BL                | Notebook    | [ee9f312333](https://linux-hardware.org/?probe=ee9f312333) | Jan 16, 2021 |
| ECS           | PB02CF                      | Server      | [79ed88ad12](https://linux-hardware.org/?probe=79ed88ad12) | Jan 13, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [ffa2d06213](https://linux-hardware.org/?probe=ffa2d06213) | Jan 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [28d2ddf944](https://linux-hardware.org/?probe=28d2ddf944) | Jan 04, 2021 |
| HP            | 18E7                        | Desktop     | [e9590ba71a](https://linux-hardware.org/?probe=e9590ba71a) | Jan 01, 2021 |
| LG Electro... | 10T370-L860K                | Tablet      | [a6ab074bb5](https://linux-hardware.org/?probe=a6ab074bb5) | Jan 01, 2021 |
| LG Electro... | 10T370-L860K                | Tablet      | [7a21765d3b](https://linux-hardware.org/?probe=7a21765d3b) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA706II_FA706... | Notebook    | [cbc872e471](https://linux-hardware.org/?probe=cbc872e471) | Dec 29, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [4f038027ac](https://linux-hardware.org/?probe=4f038027ac) | Dec 27, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [659c45927e](https://linux-hardware.org/?probe=659c45927e) | Dec 26, 2020 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [deb549d3e1](https://linux-hardware.org/?probe=deb549d3e1) | Dec 21, 2020 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4245e53af4](https://linux-hardware.org/?probe=4245e53af4) | Dec 20, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [77ad294d93](https://linux-hardware.org/?probe=77ad294d93) | Dec 20, 2020 |
| HP            | Pavilion g6                 | Notebook    | [9b2e1ccb17](https://linux-hardware.org/?probe=9b2e1ccb17) | Dec 15, 2020 |
| HP            | Pavilion g6                 | Notebook    | [01bd113f0d](https://linux-hardware.org/?probe=01bd113f0d) | Dec 15, 2020 |
| MSI           | PS42 Modern 8MO             | Notebook    | [c469679bd0](https://linux-hardware.org/?probe=c469679bd0) | Dec 14, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [ae9a14bb34](https://linux-hardware.org/?probe=ae9a14bb34) | Dec 11, 2020 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [9ff7890a24](https://linux-hardware.org/?probe=9ff7890a24) | Dec 11, 2020 |
| Gigabyte      | C621-SU8 M18818             | Server      | [7e93e1b694](https://linux-hardware.org/?probe=7e93e1b694) | Dec 11, 2020 |
| Gigabyte      | C621-SU8 M18818             | Server      | [6343846b09](https://linux-hardware.org/?probe=6343846b09) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [b1476b4c51](https://linux-hardware.org/?probe=b1476b4c51) | Dec 09, 2020 |
| Samsung       | 760XBE                      | Notebook    | [7b117d1e93](https://linux-hardware.org/?probe=7b117d1e93) | Dec 08, 2020 |
| Samsung       | R440/R480                   | Notebook    | [2c57659a41](https://linux-hardware.org/?probe=2c57659a41) | Dec 06, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [a706242b44](https://linux-hardware.org/?probe=a706242b44) | Dec 05, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [f16f5d30de](https://linux-hardware.org/?probe=f16f5d30de) | Dec 05, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [425fda9034](https://linux-hardware.org/?probe=425fda9034) | Dec 04, 2020 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [e6f9b2cf07](https://linux-hardware.org/?probe=e6f9b2cf07) | Dec 04, 2020 |
| Acer          | Swift SF314-54              | Notebook    | [e387afac15](https://linux-hardware.org/?probe=e387afac15) | Nov 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [ecfaa7232b](https://linux-hardware.org/?probe=ecfaa7232b) | Nov 28, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [eb842cd3c4](https://linux-hardware.org/?probe=eb842cd3c4) | Nov 25, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [2a9cc167d3](https://linux-hardware.org/?probe=2a9cc167d3) | Nov 25, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [0354f4d9bc](https://linux-hardware.org/?probe=0354f4d9bc) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [8dcc7ce213](https://linux-hardware.org/?probe=8dcc7ce213) | Nov 22, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f9b97f5918](https://linux-hardware.org/?probe=f9b97f5918) | Nov 22, 2020 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [e4a465ff4c](https://linux-hardware.org/?probe=e4a465ff4c) | Nov 15, 2020 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [8a39cadb17](https://linux-hardware.org/?probe=8a39cadb17) | Nov 14, 2020 |
| ECS           | G31T-M7                     | Desktop     | [f93ce4415e](https://linux-hardware.org/?probe=f93ce4415e) | Nov 12, 2020 |
| PC Partner... | A236 0A                     | Desktop     | [14030da2e5](https://linux-hardware.org/?probe=14030da2e5) | Nov 10, 2020 |
| PC Partner... | A236 0A                     | Desktop     | [fc118d784c](https://linux-hardware.org/?probe=fc118d784c) | Nov 10, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [11e315efbd](https://linux-hardware.org/?probe=11e315efbd) | Nov 07, 2020 |
| Samsung       | SX11S                       | Notebook    | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [9b33944102](https://linux-hardware.org/?probe=9b33944102) | Nov 04, 2020 |
| Samsung       | 930QAA                      | Convertible | [ed50ef80ea](https://linux-hardware.org/?probe=ed50ef80ea) | Nov 01, 2020 |
| Lenovo        | ThinkPad T580 20L9S06H00    | Notebook    | [4cda554e60](https://linux-hardware.org/?probe=4cda554e60) | Oct 31, 2020 |
| Samsung       | 930QAA                      | Convertible | [e0defd416b](https://linux-hardware.org/?probe=e0defd416b) | Oct 31, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [7a0c7ef25d](https://linux-hardware.org/?probe=7a0c7ef25d) | Oct 22, 2020 |
| ECS           | PB02CF                      | Server      | [d2a218790a](https://linux-hardware.org/?probe=d2a218790a) | Oct 18, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [39cc53a5e3](https://linux-hardware.org/?probe=39cc53a5e3) | Oct 13, 2020 |
| ECS           | PB02CF                      | Server      | [872240bfee](https://linux-hardware.org/?probe=872240bfee) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [57c9a2fdbb](https://linux-hardware.org/?probe=57c9a2fdbb) | Oct 12, 2020 |
| Acer          | Aspire A514-52              | Notebook    | [151c57e477](https://linux-hardware.org/?probe=151c57e477) | Oct 11, 2020 |
| ECS           | PB02CF                      | Server      | [ee5e0d54ac](https://linux-hardware.org/?probe=ee5e0d54ac) | Oct 10, 2020 |
| ECS           | PB02CF                      | Server      | [2584572329](https://linux-hardware.org/?probe=2584572329) | Oct 10, 2020 |
| ECS           | PB02CF                      | Server      | [9ff606fe05](https://linux-hardware.org/?probe=9ff606fe05) | Oct 09, 2020 |
| Lenovo        | ThinkPad E595 20NFS01P00    | Notebook    | [5cce7e56d5](https://linux-hardware.org/?probe=5cce7e56d5) | Oct 02, 2020 |
| MSI           | MS-16F1                     | Notebook    | [94a744ecb7](https://linux-hardware.org/?probe=94a744ecb7) | Oct 01, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [3aba059c2c](https://linux-hardware.org/?probe=3aba059c2c) | Sep 24, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [c535500f86](https://linux-hardware.org/?probe=c535500f86) | Sep 24, 2020 |
| ASRock        | H310M-STX/COM               | Desktop     | [5b22b538ee](https://linux-hardware.org/?probe=5b22b538ee) | Sep 23, 2020 |
| MSI           | GE75 Raider 10SF            | Notebook    | [c5f31d8ff8](https://linux-hardware.org/?probe=c5f31d8ff8) | Sep 21, 2020 |
| MSI           | GE75 Raider 10SF            | Notebook    | [80b54a584c](https://linux-hardware.org/?probe=80b54a584c) | Sep 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [335490808b](https://linux-hardware.org/?probe=335490808b) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [611b4d4515](https://linux-hardware.org/?probe=611b4d4515) | Sep 12, 2020 |
| Samsung       | SX11S                       | Notebook    | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [56efa94b22](https://linux-hardware.org/?probe=56efa94b22) | Sep 09, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [00f5eba2ea](https://linux-hardware.org/?probe=00f5eba2ea) | Sep 09, 2020 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e9eb75e83c](https://linux-hardware.org/?probe=e9eb75e83c) | Sep 09, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [934bb9c2ef](https://linux-hardware.org/?probe=934bb9c2ef) | Sep 09, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [7acf41575b](https://linux-hardware.org/?probe=7acf41575b) | Sep 09, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [8b55873fbd](https://linux-hardware.org/?probe=8b55873fbd) | Sep 07, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [0ed21172b2](https://linux-hardware.org/?probe=0ed21172b2) | Sep 07, 2020 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [56e8c74784](https://linux-hardware.org/?probe=56e8c74784) | Sep 05, 2020 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [5b29fd8262](https://linux-hardware.org/?probe=5b29fd8262) | Sep 05, 2020 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [226702f09a](https://linux-hardware.org/?probe=226702f09a) | Sep 05, 2020 |
| LG Electro... | 15ND530-GX30K               | Notebook    | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Foxconn       | H61MXE                      | Desktop     | [7a31014e98](https://linux-hardware.org/?probe=7a31014e98) | Sep 04, 2020 |
| ECS           | PB02CF                      | Server      | [4d441244a7](https://linux-hardware.org/?probe=4d441244a7) | Sep 03, 2020 |
| Lenovo        | ThinkPad X390 20SCCTO1WW    | Notebook    | [765a0cde4c](https://linux-hardware.org/?probe=765a0cde4c) | Sep 03, 2020 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2ef3a6b6c8](https://linux-hardware.org/?probe=2ef3a6b6c8) | Sep 03, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [c57a2c8249](https://linux-hardware.org/?probe=c57a2c8249) | Aug 26, 2020 |
| LG Electro... | A520-DEHRK                  | Notebook    | [33e6f6950c](https://linux-hardware.org/?probe=33e6f6950c) | Aug 20, 2020 |
| LG Electro... | ZD360-GD30K                 | Notebook    | [5f695a5cfd](https://linux-hardware.org/?probe=5f695a5cfd) | Aug 19, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | Notebook    | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| ASUSTek       | UX31E                       | Notebook    | [107d53bd73](https://linux-hardware.org/?probe=107d53bd73) | Aug 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | Notebook    | [e2a554e507](https://linux-hardware.org/?probe=e2a554e507) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [4657a3e758](https://linux-hardware.org/?probe=4657a3e758) | Aug 11, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | Notebook    | [a0cc9e062e](https://linux-hardware.org/?probe=a0cc9e062e) | Aug 09, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [dabfcf887e](https://linux-hardware.org/?probe=dabfcf887e) | Aug 05, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [806b0f6ffc](https://linux-hardware.org/?probe=806b0f6ffc) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [03dcb81800](https://linux-hardware.org/?probe=03dcb81800) | Aug 04, 2020 |
| Nvidia        | Tegra                       | Soc         | [db3eb249a1](https://linux-hardware.org/?probe=db3eb249a1) | Aug 02, 2020 |
| Nvidia        | Tegra                       | Soc         | [ce759d1ef8](https://linux-hardware.org/?probe=ce759d1ef8) | Aug 02, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [953e68f29d](https://linux-hardware.org/?probe=953e68f29d) | Jul 29, 2020 |
| ASRock        | H61M-HVGS                   | Desktop     | [36c19012ed](https://linux-hardware.org/?probe=36c19012ed) | Jul 25, 2020 |
| ASRock        | H61M-HVGS                   | Desktop     | [ea9287adc1](https://linux-hardware.org/?probe=ea9287adc1) | Jul 25, 2020 |
| Samsung       | X120/X170/X171              | Notebook    | [d52c424e0f](https://linux-hardware.org/?probe=d52c424e0f) | Jul 12, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [1f2f8bb2cf](https://linux-hardware.org/?probe=1f2f8bb2cf) | Jul 06, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ed2dc1f4eb](https://linux-hardware.org/?probe=ed2dc1f4eb) | Jul 05, 2020 |
| Sony          | SVF1421ESGW                 | Notebook    | [025b1a05fe](https://linux-hardware.org/?probe=025b1a05fe) | Jun 29, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [ce94a11d8b](https://linux-hardware.org/?probe=ce94a11d8b) | Jun 26, 2020 |
| Huanan        | X99-F8                      | Desktop     | [74f9976527](https://linux-hardware.org/?probe=74f9976527) | Jun 25, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [cbd4390e56](https://linux-hardware.org/?probe=cbd4390e56) | Jun 23, 2020 |
| ASUSTek       | X553SA                      | Notebook    | [de56d8fe26](https://linux-hardware.org/?probe=de56d8fe26) | Jun 23, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [6989759d9c](https://linux-hardware.org/?probe=6989759d9c) | Jun 21, 2020 |
| ASRock        | Z390M Pro4                  | Desktop     | [eb53bb80ea](https://linux-hardware.org/?probe=eb53bb80ea) | Jun 20, 2020 |
| ECS           | H81H3-MV                    | Desktop     | [d39e7a605d](https://linux-hardware.org/?probe=d39e7a605d) | Jun 20, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [c05f965fec](https://linux-hardware.org/?probe=c05f965fec) | Jun 17, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [835aa152dd](https://linux-hardware.org/?probe=835aa152dd) | Jun 16, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [41702d8f8c](https://linux-hardware.org/?probe=41702d8f8c) | Jun 14, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [16345ce4e3](https://linux-hardware.org/?probe=16345ce4e3) | Jun 14, 2020 |
| TG            | NXI-A7000 Series            | Notebook    | [20018e6c2a](https://linux-hardware.org/?probe=20018e6c2a) | Jun 07, 2020 |
| Dell          | G3 3579                     | Notebook    | [f21ec2528f](https://linux-hardware.org/?probe=f21ec2528f) | Jun 06, 2020 |
| ECS           | PB02CF                      | Server      | [e4fe65609d](https://linux-hardware.org/?probe=e4fe65609d) | May 28, 2020 |
| ECS           | PB02CF                      | Server      | [277941a55d](https://linux-hardware.org/?probe=277941a55d) | May 27, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | Notebook    | [bd7072c5e9](https://linux-hardware.org/?probe=bd7072c5e9) | May 27, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [229612b5fa](https://linux-hardware.org/?probe=229612b5fa) | May 26, 2020 |
| LG Electro... | 17UD790-PX76K               | Notebook    | [ac4f8e9cc6](https://linux-hardware.org/?probe=ac4f8e9cc6) | May 24, 2020 |
| LG Electro... | 17UD790-PX76K               | Notebook    | [9bb4fea940](https://linux-hardware.org/?probe=9bb4fea940) | May 24, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [65f85ef8e9](https://linux-hardware.org/?probe=65f85ef8e9) | May 20, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b3a561d5db](https://linux-hardware.org/?probe=b3a561d5db) | May 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [e6e0a356a2](https://linux-hardware.org/?probe=e6e0a356a2) | May 19, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [69c9f3bce6](https://linux-hardware.org/?probe=69c9f3bce6) | May 17, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [e526204afd](https://linux-hardware.org/?probe=e526204afd) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | Notebook    | [435579b481](https://linux-hardware.org/?probe=435579b481) | May 16, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [24ce1a41e9](https://linux-hardware.org/?probe=24ce1a41e9) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | Notebook    | [5e2ed0ac77](https://linux-hardware.org/?probe=5e2ed0ac77) | May 16, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [dc05f2344d](https://linux-hardware.org/?probe=dc05f2344d) | May 16, 2020 |
| Lenovo        | ThinkPad 8 20BNA00GKR       | Tablet      | [344a9c1bfa](https://linux-hardware.org/?probe=344a9c1bfa) | May 14, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [5919a15425](https://linux-hardware.org/?probe=5919a15425) | May 11, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [d5b8f91a79](https://linux-hardware.org/?probe=d5b8f91a79) | May 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c259824b35](https://linux-hardware.org/?probe=c259824b35) | May 09, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [261241bb2f](https://linux-hardware.org/?probe=261241bb2f) | May 07, 2020 |
| Biostar       | H61MH                       | Desktop     | [aacc6bcb68](https://linux-hardware.org/?probe=aacc6bcb68) | May 07, 2020 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [36cbf906a0](https://linux-hardware.org/?probe=36cbf906a0) | May 07, 2020 |
| Lenovo        | ThinkPad X220 4290P39       | Notebook    | [1b5c469306](https://linux-hardware.org/?probe=1b5c469306) | May 02, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [a4130d0549](https://linux-hardware.org/?probe=a4130d0549) | Apr 29, 2020 |
| ASRock        | G31M-S                      | Desktop     | [6a55997759](https://linux-hardware.org/?probe=6a55997759) | Apr 28, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [0bbf773840](https://linux-hardware.org/?probe=0bbf773840) | Apr 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [5348bea534](https://linux-hardware.org/?probe=5348bea534) | Apr 27, 2020 |
| Lenovo        | ThinkPad X230 2325KZ5       | Notebook    | [150d9801f0](https://linux-hardware.org/?probe=150d9801f0) | Apr 21, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5d58ef4cec](https://linux-hardware.org/?probe=5d58ef4cec) | Apr 19, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | Notebook    | [fb49bbe9f1](https://linux-hardware.org/?probe=fb49bbe9f1) | Apr 18, 2020 |
| Lenovo        | ThinkPad 8 20BNA00GKR       | Tablet      | [aa72454483](https://linux-hardware.org/?probe=aa72454483) | Apr 16, 2020 |
| Dell          | Latitude D630               | Notebook    | [0540c0a191](https://linux-hardware.org/?probe=0540c0a191) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [4d5a5a3a34](https://linux-hardware.org/?probe=4d5a5a3a34) | Apr 14, 2020 |
| MSI           | B250M PRO-VD                | Desktop     | [d797379451](https://linux-hardware.org/?probe=d797379451) | Apr 13, 2020 |
| LG Electro... | 15U340-LT1FK                | Tablet      | [b78bd157c9](https://linux-hardware.org/?probe=b78bd157c9) | Apr 12, 2020 |
| LG Electro... | 15U340-LT1FK                | Tablet      | [29cad9bafb](https://linux-hardware.org/?probe=29cad9bafb) | Apr 12, 2020 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [0f078bd16f](https://linux-hardware.org/?probe=0f078bd16f) | Apr 11, 2020 |
| Dell          | 0Y2MRG A01                  | Desktop     | [053b33bcbc](https://linux-hardware.org/?probe=053b33bcbc) | Apr 05, 2020 |
| ASUSTek       | P5K                         | Desktop     | [8ec1f94a9f](https://linux-hardware.org/?probe=8ec1f94a9f) | Apr 05, 2020 |
| ASUSTek       | H110M-F                     | Desktop     | [c5861fb518](https://linux-hardware.org/?probe=c5861fb518) | Mar 31, 2020 |
| LG Electro... | R490-KR6WK                  | Notebook    | [b0c23e23f7](https://linux-hardware.org/?probe=b0c23e23f7) | Mar 21, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [c54c1dcc2f](https://linux-hardware.org/?probe=c54c1dcc2f) | Mar 18, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [de7d898371](https://linux-hardware.org/?probe=de7d898371) | Mar 16, 2020 |
| Hanis         | Rugged86H                   | Tablet      | [f85527148f](https://linux-hardware.org/?probe=f85527148f) | Mar 16, 2020 |
| Hanis         | Rugged86H                   | Tablet      | [9526ed2d93](https://linux-hardware.org/?probe=9526ed2d93) | Mar 16, 2020 |
| ECS           | PB02CF                      | Server      | [68979eba8f](https://linux-hardware.org/?probe=68979eba8f) | Mar 15, 2020 |
| ECS           | PB02CF                      | Server      | [351516c86f](https://linux-hardware.org/?probe=351516c86f) | Mar 14, 2020 |
| ECS           | PB02CF                      | Server      | [fc1afc7ed7](https://linux-hardware.org/?probe=fc1afc7ed7) | Mar 12, 2020 |
| HP            | Pavilion dv7                | Notebook    | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| ECS           | PB02CF                      | Server      | [9d62420812](https://linux-hardware.org/?probe=9d62420812) | Mar 09, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [b5def2acfb](https://linux-hardware.org/?probe=b5def2acfb) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [ca363a8ddc](https://linux-hardware.org/?probe=ca363a8ddc) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [2b56d27ead](https://linux-hardware.org/?probe=2b56d27ead) | Mar 02, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [8b42886c6f](https://linux-hardware.org/?probe=8b42886c6f) | Mar 02, 2020 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [fd4e08618e](https://linux-hardware.org/?probe=fd4e08618e) | Feb 28, 2020 |
| ECS           | PB02CF                      | Server      | [8553d515a9](https://linux-hardware.org/?probe=8553d515a9) | Feb 27, 2020 |
| LG Electro... | A505-K.AFC4L                | Notebook    | [33b72b423b](https://linux-hardware.org/?probe=33b72b423b) | Feb 26, 2020 |
| ECS           | PB02CF                      | Server      | [7b029b9193](https://linux-hardware.org/?probe=7b029b9193) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [82e1b966c4](https://linux-hardware.org/?probe=82e1b966c4) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [c81fd255b8](https://linux-hardware.org/?probe=c81fd255b8) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [855276d27c](https://linux-hardware.org/?probe=855276d27c) | Feb 22, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [8212e2eb65](https://linux-hardware.org/?probe=8212e2eb65) | Feb 13, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [00af81dd32](https://linux-hardware.org/?probe=00af81dd32) | Feb 12, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [dac2e1709e](https://linux-hardware.org/?probe=dac2e1709e) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| LattePanda    | Alpha                       | Desktop     | [eb27db2005](https://linux-hardware.org/?probe=eb27db2005) | Feb 01, 2020 |
| LattePanda    | Alpha                       | Desktop     | [72a1cd44a0](https://linux-hardware.org/?probe=72a1cd44a0) | Feb 01, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [47b9bc192c](https://linux-hardware.org/?probe=47b9bc192c) | Jan 29, 2020 |
| Nvidia        | Tegra                       | Soc         | [7d929b52dc](https://linux-hardware.org/?probe=7d929b52dc) | Jan 29, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [21dbcd5aca](https://linux-hardware.org/?probe=21dbcd5aca) | Jan 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [6515ce1c97](https://linux-hardware.org/?probe=6515ce1c97) | Jan 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f4a3ca42f](https://linux-hardware.org/?probe=3f4a3ca42f) | Jan 19, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | Desktop     | [b0a90d8478](https://linux-hardware.org/?probe=b0a90d8478) | Jan 02, 2020 |
| HP            | ProBook 453                 | Notebook    | [ad3d1ff0fc](https://linux-hardware.org/?probe=ad3d1ff0fc) | Dec 27, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2fb35125e3](https://linux-hardware.org/?probe=2fb35125e3) | Dec 22, 2019 |
| Lenovo        | ThinkPad E565 20EYA007KD    | Notebook    | [c1c9dd614a](https://linux-hardware.org/?probe=c1c9dd614a) | Dec 17, 2019 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [61765ee913](https://linux-hardware.org/?probe=61765ee913) | Dec 11, 2019 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [fa008b24fc](https://linux-hardware.org/?probe=fa008b24fc) | Dec 11, 2019 |
| Gigabyte      | 945GM-S2                    | Desktop     | [c6b23ec021](https://linux-hardware.org/?probe=c6b23ec021) | Dec 07, 2019 |
| HP            | Pavilion 15                 | Notebook    | [5f9b510e87](https://linux-hardware.org/?probe=5f9b510e87) | Oct 28, 2019 |
| ECS           | H81H3-M4                    | Desktop     | [2a11653db0](https://linux-hardware.org/?probe=2a11653db0) | Oct 05, 2019 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [37c348afcc](https://linux-hardware.org/?probe=37c348afcc) | Sep 11, 2019 |
| MSI           | MS-1675                     | Notebook    | [c5bf6f209a](https://linux-hardware.org/?probe=c5bf6f209a) | Sep 07, 2019 |
| MSI           | MS-1675                     | Notebook    | [be1db420ea](https://linux-hardware.org/?probe=be1db420ea) | Sep 07, 2019 |
| Hanis         | RuggedPadY16                | Tablet      | [70f839c5cb](https://linux-hardware.org/?probe=70f839c5cb) | Sep 04, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [caaebe3071](https://linux-hardware.org/?probe=caaebe3071) | Sep 01, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [5637a7d5ca](https://linux-hardware.org/?probe=5637a7d5ca) | Sep 01, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [b08e9c4371](https://linux-hardware.org/?probe=b08e9c4371) | Aug 31, 2019 |
| Lenovo        | U41-70 80JV                 | Notebook    | [0af65c15a0](https://linux-hardware.org/?probe=0af65c15a0) | Aug 30, 2019 |
| ECS           | G41T-M6                     | Desktop     | [91cafa3b5b](https://linux-hardware.org/?probe=91cafa3b5b) | Aug 30, 2019 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [68069aeff1](https://linux-hardware.org/?probe=68069aeff1) | Aug 21, 2019 |
| IMUZ          | StormBook 15                | Notebook    | [daf3b9ea48](https://linux-hardware.org/?probe=daf3b9ea48) | Aug 07, 2019 |
| Supermicro    | X11DPG-OT-CPU               | Server      | [8e73f804f5](https://linux-hardware.org/?probe=8e73f804f5) | Jul 16, 2019 |
| ASRock        | Z390 Extreme4               | Desktop     | [8c8af8b557](https://linux-hardware.org/?probe=8c8af8b557) | Jul 13, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [88354e515f](https://linux-hardware.org/?probe=88354e515f) | Jul 08, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [7506cb2993](https://linux-hardware.org/?probe=7506cb2993) | Jul 08, 2019 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [727b2b7099](https://linux-hardware.org/?probe=727b2b7099) | Jun 27, 2019 |
| AMD           | R690A-M2T                   | Desktop     | [da36474b90](https://linux-hardware.org/?probe=da36474b90) | Jun 18, 2019 |
| Gigabyte      | AB350M-DS2-CF               | Desktop     | [553908ddb3](https://linux-hardware.org/?probe=553908ddb3) | Jun 09, 2019 |
| ASUSTek       | PRIME X399-A                | Desktop     | [ae94045380](https://linux-hardware.org/?probe=ae94045380) | May 29, 2019 |
| Lenovo        | NO DPK                      | Desktop     | [b89b8c9364](https://linux-hardware.org/?probe=b89b8c9364) | May 27, 2019 |
| Samsung       | 800G5M/800G5W               | Notebook    | [01cb2e9401](https://linux-hardware.org/?probe=01cb2e9401) | May 22, 2019 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e318a9dac5](https://linux-hardware.org/?probe=e318a9dac5) | May 10, 2019 |
| ASRock        | H61M-DGS                    | Desktop     | [6dc8ccd0f6](https://linux-hardware.org/?probe=6dc8ccd0f6) | May 08, 2019 |
| Sony          | VPCEA36FK                   | Notebook    | [6c4b2a047b](https://linux-hardware.org/?probe=6c4b2a047b) | May 01, 2019 |
| Foxconn       | P35A01                      | Desktop     | [f2685edfa8](https://linux-hardware.org/?probe=f2685edfa8) | Apr 21, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [fb5730a29c](https://linux-hardware.org/?probe=fb5730a29c) | Apr 17, 2019 |
| Apple         | MacBookPro14,1              | Notebook    | [606c70c0db](https://linux-hardware.org/?probe=606c70c0db) | Apr 15, 2019 |
| Dell          | Inspiron 7570               | Notebook    | [f46c9c93f9](https://linux-hardware.org/?probe=f46c9c93f9) | Apr 12, 2019 |
| Dell          | Inspiron 7570               | Notebook    | [e1c522656b](https://linux-hardware.org/?probe=e1c522656b) | Apr 12, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [322d76fe62](https://linux-hardware.org/?probe=322d76fe62) | Apr 04, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [0fa2f9b10a](https://linux-hardware.org/?probe=0fa2f9b10a) | Apr 04, 2019 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [8e21d7bf0c](https://linux-hardware.org/?probe=8e21d7bf0c) | Mar 30, 2019 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [45f363040f](https://linux-hardware.org/?probe=45f363040f) | Mar 30, 2019 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | Notebook    | [ed9f709e73](https://linux-hardware.org/?probe=ed9f709e73) | Feb 20, 2019 |
| HP            | ProLiant DL380 Gen9         | Server      | [c9d389b2a3](https://linux-hardware.org/?probe=c9d389b2a3) | Jan 26, 2019 |
| ASRock        | P55 Pro                     | Desktop     | [041e899a1b](https://linux-hardware.org/?probe=041e899a1b) | Jan 15, 2019 |
| Gigabyte      | H55M-S2V                    | Desktop     | [36d1703d67](https://linux-hardware.org/?probe=36d1703d67) | Dec 23, 2018 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [4a0abda7de](https://linux-hardware.org/?probe=4a0abda7de) | Dec 14, 2018 |
| LattePanda    | Alpha                       | Desktop     | [287f0d8110](https://linux-hardware.org/?probe=287f0d8110) | Nov 27, 2018 |
| LattePanda    | Alpha                       | Desktop     | [37c9db1d31](https://linux-hardware.org/?probe=37c9db1d31) | Nov 27, 2018 |
| AVERATEC      | 6600                        | Notebook    | [a55a983b35](https://linux-hardware.org/?probe=a55a983b35) | Nov 11, 2018 |
| AVERATEC      | 6600                        | Notebook    | [8ca54d992c](https://linux-hardware.org/?probe=8ca54d992c) | Nov 11, 2018 |
| Dell          | XPS 15 9560                 | Notebook    | [d5d9e2cef1](https://linux-hardware.org/?probe=d5d9e2cef1) | Nov 04, 2018 |
| LG Electro... | R510                        | Notebook    | [f7b3f1d4a5](https://linux-hardware.org/?probe=f7b3f1d4a5) | Oct 13, 2018 |
| Gigabyte      | P55-US3L                    | Desktop     | [e216d60f26](https://linux-hardware.org/?probe=e216d60f26) | Sep 19, 2018 |
| Gigabyte      | B75M-D3H                    | Desktop     | [08f9437e06](https://linux-hardware.org/?probe=08f9437e06) | Jul 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [16f456428f](https://linux-hardware.org/?probe=16f456428f) | May 10, 2018 |
| ECS           | A55F2-M3                    | Desktop     | [e4af897158](https://linux-hardware.org/?probe=e4af897158) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [f3036847e4](https://linux-hardware.org/?probe=f3036847e4) | May 10, 2018 |
| ECS           | A55F2-M3                    | Desktop     | [eb58cea516](https://linux-hardware.org/?probe=eb58cea516) | May 10, 2018 |
| ASRock        | G41M-VS3                    | Desktop     | [18d59d7ea8](https://linux-hardware.org/?probe=18d59d7ea8) | Apr 13, 2018 |
| ASUSTek       | N56JR                       | Notebook    | [27253306bc](https://linux-hardware.org/?probe=27253306bc) | Dec 28, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/South_Korea/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 98        | 20.9%   |
| Ubuntu 18.04                 | 47        | 10.02%  |
| Ubuntu 22.04                 | 36        | 7.68%   |
| Arch                         | 11        | 2.35%   |
| Debian 11                    | 10        | 2.13%   |
| Ubuntu 21.10                 | 9         | 1.92%   |
| Ubuntu 19.10                 | 9         | 1.92%   |
| Gooroom                      | 9         | 1.92%   |
| Ubuntu 20.10                 | 8         | 1.71%   |
| Arch Rolling                 | 8         | 1.71%   |
| Fedora 37                    | 7         | 1.49%   |
| Fedora 32                    | 7         | 1.49%   |
| Ubuntu 19.04                 | 6         | 1.28%   |
| Linux Mint 20.1              | 6         | 1.28%   |
| Fedora 36                    | 6         | 1.28%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.07%   |
| HamoniKR 4.0                 | 5         | 1.07%   |
| Fedora 34                    | 5         | 1.07%   |
| Debian 10                    | 5         | 1.07%   |
| Zorin 16                     | 4         | 0.85%   |
| Zorin 15                     | 4         | 0.85%   |
| Ubuntu 16.04                 | 4         | 0.85%   |
| OpenMandriva 4.2             | 4         | 0.85%   |
| OpenMandriva 23.01           | 4         | 0.85%   |
| Linux Mint 20.3              | 4         | 0.85%   |
| Linux Mint 20                | 4         | 0.85%   |
| CentOS 8                     | 4         | 0.85%   |
| CentOS 7                     | 4         | 0.85%   |
| Ubuntu Unity 16.04           | 3         | 0.64%   |
| Ubuntu 22.10                 | 3         | 0.64%   |
| ROSA R11                     | 3         | 0.64%   |
| ROSA R10                     | 3         | 0.64%   |
| Pop!_OS 22.04                | 3         | 0.64%   |
| OpenMandriva 4.3             | 3         | 0.64%   |
| OpenMandriva 23.03           | 3         | 0.64%   |
| No1 2022 kde plasma te       | 3         | 0.64%   |
| No1 2020 te                  | 3         | 0.64%   |
| No1 2018                     | 3         | 0.64%   |
| Linux Mint 20.2              | 3         | 0.64%   |
| Linux Mint 19.3              | 3         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 220       | 48.67%  |
| Fedora       | 31        | 6.86%   |
| Linux Mint   | 22        | 4.87%   |
| Arch         | 17        | 3.76%   |
| OpenMandriva | 16        | 3.54%   |
| Debian       | 16        | 3.54%   |
| Manjaro      | 11        | 2.43%   |
| Gooroom      | 10        | 2.21%   |
| CentOS       | 10        | 2.21%   |
| No1          | 9         | 1.99%   |
| HamoniKR     | 9         | 1.99%   |
| Zorin        | 8         | 1.77%   |
| Kubuntu      | 8         | 1.77%   |
| Endless      | 8         | 1.77%   |
| Pop!_OS      | 7         | 1.55%   |
| ROSA         | 6         | 1.33%   |
| Ubuntu Unity | 5         | 1.11%   |
| openSUSE     | 5         | 1.11%   |
| KDE neon     | 4         | 0.88%   |
| SteamOS      | 3         | 0.66%   |
| EndeavourOS  | 3         | 0.66%   |
| Xubuntu      | 2         | 0.44%   |
| Ubuntu MATE  | 2         | 0.44%   |
| TmaxOS       | 2         | 0.44%   |
| Rocky Linux  | 2         | 0.44%   |
| RHEL         | 2         | 0.44%   |
| Lubuntu      | 2         | 0.44%   |
| LMDE         | 2         | 0.44%   |
| Gentoo       | 2         | 0.44%   |
| Chrome OS    | 2         | 0.44%   |
| Nobara       | 1         | 0.22%   |
| Garuda Linux | 1         | 0.22%   |
| Devuan       | 1         | 0.22%   |
| BlackPanther | 1         | 0.22%   |
| ArcoLinux    | 1         | 0.22%   |
| Alpine       | 1         | 0.22%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.3.0-40-generic                | 8         | 1.59%   |
| 5.4.0-42-generic                | 7         | 1.39%   |
| 5.15.0-53-generic               | 7         | 1.39%   |
| 5.4.0-29-generic                | 6         | 1.19%   |
| 5.4.0-26-generic                | 6         | 1.19%   |
| 5.15.0-58-generic               | 6         | 1.19%   |
| 5.4.0-58-generic                | 5         | 0.99%   |
| 5.4.0-56-generic                | 5         | 0.99%   |
| 5.10.0-19-amd64                 | 5         | 0.99%   |
| 6.1.1-desktop-1omv2290          | 4         | 0.8%    |
| 5.15.0-56-generic               | 4         | 0.8%    |
| 5.15.0-52-generic               | 4         | 0.8%    |
| 5.15.0-43-generic               | 4         | 0.8%    |
| 5.15.0-41-generic               | 4         | 0.8%    |
| 5.10.0-17-amd64                 | 4         | 0.8%    |
| 5.0.0-25-generic                | 4         | 0.8%    |
| 6.2.6-desktop-1omv2390          | 3         | 0.6%    |
| 5.8.0-59-generic                | 3         | 0.6%    |
| 5.8.0-50-generic                | 3         | 0.6%    |
| 5.8.0-43-generic                | 3         | 0.6%    |
| 5.8.0-38-generic                | 3         | 0.6%    |
| 5.4.0-91-generic                | 3         | 0.6%    |
| 5.4.0-81-generic                | 3         | 0.6%    |
| 5.4.0-54-generic                | 3         | 0.6%    |
| 5.4.0-52-generic                | 3         | 0.6%    |
| 5.4.0-47-generic                | 3         | 0.6%    |
| 5.4.0-37-generic                | 3         | 0.6%    |
| 5.4.0-33-generic                | 3         | 0.6%    |
| 5.3.0-46-generic                | 3         | 0.6%    |
| 5.19.15-201.fc36.x86_64         | 3         | 0.6%    |
| 5.19.0-35-generic               | 3         | 0.6%    |
| 5.16.7-desktop-1omv4003         | 3         | 0.6%    |
| 5.15.0-60-generic               | 3         | 0.6%    |
| 5.15.0-48-generic               | 3         | 0.6%    |
| 5.13.0-39-generic               | 3         | 0.6%    |
| 5.13.0-28-generic               | 3         | 0.6%    |
| 5.11.0-37-generic               | 3         | 0.6%    |
| 5.10.14-desktop-1omv4002        | 3         | 0.6%    |
| 5.0.0-27-generic                | 3         | 0.6%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 93        | 19.46%  |
| 5.15.0  | 50        | 10.46%  |
| 5.8.0   | 31        | 6.49%   |
| 4.15.0  | 28        | 5.86%   |
| 5.3.0   | 23        | 4.81%   |
| 5.13.0  | 23        | 4.81%   |
| 4.18.0  | 18        | 3.77%   |
| 5.10.0  | 15        | 3.14%   |
| 5.11.0  | 13        | 2.72%   |
| 5.0.0   | 12        | 2.51%   |
| 4.19.0  | 10        | 2.09%   |
| 5.19.0  | 6         | 1.26%   |
| 5.14.0  | 6         | 1.26%   |
| 5.16.19 | 5         | 1.05%   |
| 6.1.1   | 4         | 0.84%   |
| 6.2.6   | 3         | 0.63%   |
| 6.1.11  | 3         | 0.63%   |
| 6.0.0   | 3         | 0.63%   |
| 5.19.15 | 3         | 0.63%   |
| 5.18.5  | 3         | 0.63%   |
| 5.16.7  | 3         | 0.63%   |
| 5.10.14 | 3         | 0.63%   |
| 4.9.60  | 3         | 0.63%   |
| 3.10.0  | 3         | 0.63%   |
| 6.2.8   | 2         | 0.42%   |
| 6.2.2   | 2         | 0.42%   |
| 6.1.10  | 2         | 0.42%   |
| 6.0.9   | 2         | 0.42%   |
| 6.0.12  | 2         | 0.42%   |
| 5.8.4   | 2         | 0.42%   |
| 5.8.16  | 2         | 0.42%   |
| 5.15.8  | 2         | 0.42%   |
| 5.15.11 | 2         | 0.42%   |
| 5.14.6  | 2         | 0.42%   |
| 5.12.4  | 2         | 0.42%   |
| 5.11.12 | 2         | 0.42%   |
| 5.10.4  | 2         | 0.42%   |
| 4.9.140 | 2         | 0.42%   |
| 4.18.16 | 2         | 0.42%   |
| 4.15.8  | 2         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 98        | 20.59%  |
| 5.15    | 60        | 12.61%  |
| 5.8     | 40        | 8.4%    |
| 4.15    | 30        | 6.3%    |
| 5.3     | 24        | 5.04%   |
| 5.13    | 24        | 5.04%   |
| 5.10    | 24        | 5.04%   |
| 5.11    | 20        | 4.2%    |
| 4.18    | 20        | 4.2%    |
| 6.1     | 14        | 2.94%   |
| 6.0     | 13        | 2.73%   |
| 5.0     | 13        | 2.73%   |
| 5.19    | 12        | 2.52%   |
| 4.19    | 12        | 2.52%   |
| 5.16    | 11        | 2.31%   |
| 5.14    | 11        | 2.31%   |
| 6.2     | 10        | 2.1%    |
| 5.18    | 7         | 1.47%   |
| 5.12    | 6         | 1.26%   |
| 4.9     | 6         | 1.26%   |
| 5.6     | 4         | 0.84%   |
| 3.10    | 3         | 0.63%   |
| 5.9     | 2         | 0.42%   |
| 5.7     | 2         | 0.42%   |
| 4.13    | 2         | 0.42%   |
| 2.6     | 2         | 0.42%   |
| 5.5     | 1         | 0.21%   |
| 5.2     | 1         | 0.21%   |
| 5.17    | 1         | 0.21%   |
| 4.4     | 1         | 0.21%   |
| 4.17    | 1         | 0.21%   |
| 4.16    | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 429       | 96.84%  |
| aarch64 | 8         | 1.81%   |
| i686    | 5         | 1.13%   |
| armv7l  | 1         | 0.23%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 236       | 52.21%  |
| Unknown         | 67        | 14.82%  |
| KDE5            | 60        | 13.27%  |
| X-Cinnamon      | 23        | 5.09%   |
| XFCE            | 16        | 3.54%   |
| GNOME Flashback | 10        | 2.21%   |
| LXDE            | 9         | 1.99%   |
| Cinnamon        | 8         | 1.77%   |
| Unity           | 5         | 1.11%   |
| KDE             | 5         | 1.11%   |
| KDE4            | 4         | 0.88%   |
| i3              | 3         | 0.66%   |
| TOS:GNOME       | 2         | 0.44%   |
| MATE            | 2         | 0.44%   |
| sway            | 1         | 0.22%   |
| GNOME Classic   | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 306       | 68.46%  |
| Wayland | 76        | 17%     |
| Unknown | 46        | 10.29%  |
| Tty     | 19        | 4.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 238       | 52.42%  |
| GDM     | 75        | 16.52%  |
| SDDM    | 47        | 10.35%  |
| GDM3    | 47        | 10.35%  |
| LightDM | 26        | 5.73%   |
| TDM     | 16        | 3.52%   |
| KDM     | 3         | 0.66%   |
| XDM     | 1         | 0.22%   |
| SLiM    | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ko_KR       | 197       | 43.68%  |
| en_US       | 159       | 35.25%  |
| Unknown     | 62        | 13.75%  |
| C           | 8         | 1.77%   |
| en_CA       | 5         | 1.11%   |
| zh_CN       | 3         | 0.67%   |
| id_ID       | 3         | 0.67%   |
| pt_BR       | 2         | 0.44%   |
| fr_FR       | 2         | 0.44%   |
| en_GB       | 2         | 0.44%   |
| vi_VN       | 1         | 0.22%   |
| ru_RU       | 1         | 0.22%   |
| ko_KR.euckr | 1         | 0.22%   |
| en_NZ       | 1         | 0.22%   |
| en_AU       | 1         | 0.22%   |
| el_GR       | 1         | 0.22%   |
| ba_RU       | 1         | 0.22%   |
| ar_EG       | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 277       | 61.97%  |
| BIOS | 170       | 38.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 364       | 81.07%  |
| Btrfs   | 34        | 7.57%   |
| Unknown | 17        | 3.79%   |
| Xfs     | 13        | 2.9%    |
| Overlay | 13        | 2.9%    |
| Zfs     | 6         | 1.34%   |
| Rootfs  | 2         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 229       | 51%     |
| GPT     | 188       | 41.87%  |
| MBR     | 32        | 7.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 398       | 89.24%  |
| Yes       | 48        | 10.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 312       | 69.49%  |
| Yes       | 137       | 30.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 67        | 15.12%  |
| ASUSTek Computer        | 63        | 14.22%  |
| Gigabyte Technology     | 41        | 9.26%   |
| Samsung Electronics     | 38        | 8.58%   |
| Hewlett-Packard         | 33        | 7.45%   |
| ASRock                  | 31        | 7%      |
| MSI                     | 26        | 5.87%   |
| LG Electronics          | 25        | 5.64%   |
| Dell                    | 20        | 4.51%   |
| Apple                   | 11        | 2.48%   |
| ECS                     | 10        | 2.26%   |
| Notebook                | 4         | 0.9%    |
| HANSUNG COMPUTER        | 4         | 0.9%    |
| Valve                   | 3         | 0.68%   |
| Raspberry Pi Foundation | 3         | 0.68%   |
| Intel                   | 3         | 0.68%   |
| Foxconn                 | 3         | 0.68%   |
| Acer                    | 3         | 0.68%   |
| Unknown                 | 3         | 0.68%   |
| Toshiba                 | 2         | 0.45%   |
| Razer                   | 2         | 0.45%   |
| Quanta                  | 2         | 0.45%   |
| Nvidia                  | 2         | 0.45%   |
| Microsoft               | 2         | 0.45%   |
| LattePanda              | 2         | 0.45%   |
| Huanan                  | 2         | 0.45%   |
| Hanis                   | 2         | 0.45%   |
| Google                  | 2         | 0.45%   |
| Alienware               | 2         | 0.45%   |
| WTM                     | 1         | 0.23%   |
| Wolfnfox                | 1         | 0.23%   |
| WEIPAI                  | 1         | 0.23%   |
| WB                      | 1         | 0.23%   |
| TMAX                    | 1         | 0.23%   |
| TG                      | 1         | 0.23%   |
| Teclast                 | 1         | 0.23%   |
| Supermicro              | 1         | 0.23%   |
| sunxi                   | 1         | 0.23%   |
| Sony                    | 1         | 0.23%   |
| SLIMBOOK                | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung DeskTop System               | 4         | 0.9%    |
| Unknown                              | 4         | 0.9%    |
| Valve Jupiter                        | 3         | 0.68%   |
| Samsung 950XED                       | 3         | 0.68%   |
| Samsung 950XCJ/951XCJ/950XCR         | 3         | 0.68%   |
| ECS LIVA Q2                          | 3         | 0.68%   |
| ASUS PRIME B350M-A                   | 3         | 0.68%   |
| Samsung 760XDA                       | 2         | 0.45%   |
| Razer Blade 17 (2022) - RZ09-0423    | 2         | 0.45%   |
| Quanta QSSC-98J_C2                   | 2         | 0.45%   |
| Nvidia Tegra                         | 2         | 0.45%   |
| Notebook N650DU                      | 2         | 0.45%   |
| MSI MS-7D42                          | 2         | 0.45%   |
| MSI MS-7B89                          | 2         | 0.45%   |
| Lenovo Yoga 6 13ARE05 82FN           | 2         | 0.45%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00 | 2         | 0.45%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2    | 2         | 0.45%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 2         | 0.45%   |
| LattePanda Alpha                     | 2         | 0.45%   |
| HP Stream Notebook PC 13             | 2         | 0.45%   |
| HP Laptop 15-db1xxx                  | 2         | 0.45%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.45%   |
| HANSUNG COMPUTER TFX5470H            | 2         | 0.45%   |
| Gigabyte TRX40 AORUS XTREME          | 2         | 0.45%   |
| Gigabyte H81M-DS2V                   | 2         | 0.45%   |
| Gigabyte B75M-D3V                    | 2         | 0.45%   |
| Gigabyte B75M-D3H                    | 2         | 0.45%   |
| Gigabyte B360M-D3H                   | 2         | 0.45%   |
| Dell XPS 15 7590                     | 2         | 0.45%   |
| Dell Inspiron 15 5510                | 2         | 0.45%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 2         | 0.45%   |
| ASUS PRIME A320M-K                   | 2         | 0.45%   |
| ASUS EX-A320M-GAMING                 | 2         | 0.45%   |
| ASUS All Series                      | 2         | 0.45%   |
| ASRock H81M-DGS R2.0                 | 2         | 0.45%   |
| ASRock AB350M Pro4                   | 2         | 0.45%   |
| Apple MacBookPro16,1                 | 2         | 0.45%   |
| WTM W-N95                            | 1         | 0.23%   |
| Wolfnfox WF-TBAT                     | 1         | 0.23%   |
| WEIPAI S15                           | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 37        | 8.35%   |
| ASUS PRIME                | 13        | 2.93%   |
| Lenovo IdeaPad            | 11        | 2.48%   |
| HP Pavilion               | 8         | 1.81%   |
| ASUS VivoBook             | 8         | 1.81%   |
| ASUS ROG                  | 8         | 1.81%   |
| HP Laptop                 | 5         | 1.13%   |
| HP EliteBook              | 5         | 1.13%   |
| Dell Inspiron             | 5         | 1.13%   |
| Samsung DeskTop           | 4         | 0.9%    |
| Lenovo ThinkStation       | 4         | 0.9%    |
| Dell XPS                  | 4         | 0.9%    |
| ASUS TUF                  | 4         | 0.9%    |
| Unknown                   | 4         | 0.9%    |
| Valve Jupiter             | 3         | 0.68%   |
| Samsung 950XED            | 3         | 0.68%   |
| Samsung 950XCJ            | 3         | 0.68%   |
| RPi Raspberry             | 3         | 0.68%   |
| HP Stream                 | 3         | 0.68%   |
| ECS LIVA                  | 3         | 0.68%   |
| Dell Vostro               | 3         | 0.68%   |
| Dell Latitude             | 3         | 0.68%   |
| ASUS Zenbook              | 3         | 0.68%   |
| Toshiba Satellite         | 2         | 0.45%   |
| Samsung Galaxy            | 2         | 0.45%   |
| Samsung 760XDA            | 2         | 0.45%   |
| Razer Blade               | 2         | 0.45%   |
| Quanta QSSC-98J           | 2         | 0.45%   |
| Nvidia Tegra              | 2         | 0.45%   |
| Notebook N650DU           | 2         | 0.45%   |
| MSI Prestige              | 2         | 0.45%   |
| MSI MS-7D42               | 2         | 0.45%   |
| MSI MS-7B89               | 2         | 0.45%   |
| Microsoft Surface         | 2         | 0.45%   |
| Lenovo Yoga               | 2         | 0.45%   |
| Lenovo IdeaPadFlex        | 2         | 0.45%   |
| LattePanda Alpha          | 2         | 0.45%   |
| HP ProBook                | 2         | 0.45%   |
| HANSUNG COMPUTER TFX5470H | 2         | 0.45%   |
| Gigabyte Z390             | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 63        | 14.22%  |
| 2021    | 46        | 10.38%  |
| 2018    | 46        | 10.38%  |
| 2019    | 42        | 9.48%   |
| 2017    | 33        | 7.45%   |
| 2022    | 27        | 6.09%   |
| 2014    | 27        | 6.09%   |
| 2012    | 27        | 6.09%   |
| 2013    | 25        | 5.64%   |
| 2016    | 18        | 4.06%   |
| 2015    | 16        | 3.61%   |
| 2010    | 16        | 3.61%   |
| 2011    | 14        | 3.16%   |
| 2008    | 12        | 2.71%   |
| 2009    | 11        | 2.48%   |
| 2007    | 8         | 1.81%   |
| Unknown | 7         | 1.58%   |
| 2006    | 4         | 0.9%    |
| 2005    | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 224       | 50.56%  |
| Desktop        | 168       | 37.92%  |
| Tablet         | 14        | 3.16%   |
| Convertible    | 13        | 2.93%   |
| Server         | 11        | 2.48%   |
| System on chip | 8         | 1.81%   |
| Mini pc        | 4         | 0.9%    |
| All in one     | 1         | 0.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 413       | 92.81%  |
| Enabled  | 32        | 7.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 441       | 99.55%  |
| Yes  | 2         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 95        | 21.21%  |
| 16.01-24.0      | 81        | 18.08%  |
| 8.01-16.0       | 79        | 17.63%  |
| 3.01-4.0        | 67        | 14.96%  |
| 32.01-64.0      | 50        | 11.16%  |
| 64.01-256.0     | 35        | 7.81%   |
| 1.01-2.0        | 22        | 4.91%   |
| 24.01-32.0      | 10        | 2.23%   |
| More than 256.0 | 4         | 0.89%   |
| 2.01-3.0        | 3         | 0.67%   |
| 0.51-1.0        | 1         | 0.22%   |
| 0.01-0.5        | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 150       | 31.25%  |
| 2.01-3.0   | 109       | 22.71%  |
| 3.01-4.0   | 76        | 15.83%  |
| 4.01-8.0   | 73        | 15.21%  |
| 0.51-1.0   | 30        | 6.25%   |
| 8.01-16.0  | 23        | 4.79%   |
| 16.01-24.0 | 6         | 1.25%   |
| 0.01-0.5   | 6         | 1.25%   |
| 32.01-64.0 | 3         | 0.63%   |
| 24.01-32.0 | 2         | 0.42%   |
| Unknown    | 2         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 245       | 54.08%  |
| 2       | 139       | 30.68%  |
| 3       | 32        | 7.06%   |
| 4       | 15        | 3.31%   |
| 5       | 8         | 1.77%   |
| 6       | 6         | 1.32%   |
| 7       | 2         | 0.44%   |
| 0       | 2         | 0.44%   |
| 10      | 1         | 0.22%   |
| 9       | 1         | 0.22%   |
| 8       | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 353       | 79.5%   |
| Yes       | 91        | 20.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 351       | 78.7%   |
| No        | 95        | 21.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 311       | 69.89%  |
| No        | 134       | 30.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 288       | 64.29%  |
| No        | 160       | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| South Korea | 443       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Seoul         | 61        | 12.87%  |
| Seongnam-si   | 20        | 4.22%   |
| Suwon         | 19        | 4.01%   |
| Yongin-si     | 13        | 2.74%   |
| Seocho-gu     | 13        | 2.74%   |
| Gwanak-gu     | 13        | 2.74%   |
| Hwaseong-si   | 10        | 2.11%   |
| Busan         | 10        | 2.11%   |
| Uiwang        | 9         | 1.9%    |
| Jung-gu       | 9         | 1.9%    |
| Incheon       | 9         | 1.9%    |
| Seo-gu        | 8         | 1.69%   |
| Mapo-gu       | 8         | 1.69%   |
| Cheonan       | 8         | 1.69%   |
| Anyang-si     | 8         | 1.69%   |
| Yongsan-gu    | 7         | 1.48%   |
| Seongbuk-gu   | 7         | 1.48%   |
| Nam-gu        | 7         | 1.48%   |
| Goyang-si     | 7         | 1.48%   |
| Gangnam-gu    | 7         | 1.48%   |
| Pyeongtaek-si | 6         | 1.27%   |
| Namyangju     | 6         | 1.27%   |
| Gangseo-gu    | 6         | 1.27%   |
| Daejeon       | 6         | 1.27%   |
| Daegu         | 6         | 1.27%   |
| Bucheon-si    | 6         | 1.27%   |
| Gwangmyeong   | 5         | 1.05%   |
| Geumjeong-gu  | 5         | 1.05%   |
| Buk-gu        | 5         | 1.05%   |
| Yuseong-gu    | 4         | 0.84%   |
| Siheung-si    | 4         | 0.84%   |
| Jungnang-gu   | 4         | 0.84%   |
| Gwangju       | 4         | 0.84%   |
| Dongjak-gu    | 4         | 0.84%   |
| Cheongju-si   | 4         | 0.84%   |
| Changwon      | 4         | 0.84%   |
| Bupyeong-gu   | 4         | 0.84%   |
| Ansan-si      | 4         | 0.84%   |
| Yeonsu-gu     | 3         | 0.63%   |
| Yangp'yong    | 3         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 144       | 190    | 21.62%  |
| WDC                     | 92        | 139    | 13.81%  |
| Seagate                 | 66        | 101    | 9.91%   |
| SanDisk                 | 48        | 53     | 7.21%   |
| Unknown                 | 47        | 68     | 7.06%   |
| Toshiba                 | 34        | 54     | 5.11%   |
| Crucial                 | 33        | 38     | 4.95%   |
| SK hynix                | 30        | 40     | 4.5%    |
| Hitachi                 | 16        | 18     | 2.4%    |
| Intel                   | 14        | 21     | 2.1%    |
| Micron Technology       | 12        | 14     | 1.8%    |
| A-DATA Technology       | 11        | 11     | 1.65%   |
| Kingston                | 8         | 10     | 1.2%    |
| HGST                    | 8         | 9      | 1.2%    |
| Transcend               | 7         | 8      | 1.05%   |
| Silicon Motion          | 6         | 7      | 0.9%    |
| Phison                  | 6         | 8      | 0.9%    |
| Apple                   | 6         | 7      | 0.9%    |
| Team                    | 5         | 5      | 0.75%   |
| TAMMUZ                  | 5         | 8      | 0.75%   |
| Plextor                 | 4         | 6      | 0.6%    |
| China                   | 4         | 4      | 0.6%    |
| SPCC                    | 3         | 3      | 0.45%   |
| LITEON                  | 3         | 3      | 0.45%   |
| KIOXIA                  | 3         | 5      | 0.45%   |
| JMicron Technology      | 3         | 3      | 0.45%   |
| Fujitsu                 | 3         | 3      | 0.45%   |
| Union Memory            | 2         | 2      | 0.3%    |
| UMIS                    | 2         | 2      | 0.3%    |
| KingSpec                | 2         | 2      | 0.3%    |
| Imation                 | 2         | 3      | 0.3%    |
| Hewlett-Packard         | 2         | 2      | 0.3%    |
| ZTC                     | 1         | 1      | 0.15%   |
| ZOTAC                   | 1         | 1      | 0.15%   |
| XPG                     | 1         | 2      | 0.15%   |
| VIVA300s                | 1         | 1      | 0.15%   |
| VIEW                    | 1         | 1      | 0.15%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.15%   |
| TYPEC 1T                | 1         | 1      | 0.15%   |
| T-FORCE                 | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB                       | 8         | 1.08%   |
| Unknown MMC Card  64GB                             | 7         | 0.94%   |
| Unknown MMC Card  32GB                             | 7         | 0.94%   |
| Toshiba DT01ACA300 3TB                             | 7         | 0.94%   |
| Crucial CT240BX500SSD1 240GB                       | 7         | 0.94%   |
| Seagate ST500DM002-1BD142 500GB                    | 6         | 0.81%   |
| Samsung NVMe SSD Drive 256GB                       | 6         | 0.81%   |
| Unknown SD/MMC/MS PRO 249GB                        | 5         | 0.67%   |
| Samsung SSD 850 EVO 120GB                          | 5         | 0.67%   |
| Samsung MZVL21T0HCLR-00B00 1TB                     | 5         | 0.67%   |
| Unknown MMC Card  128GB                            | 4         | 0.54%   |
| Toshiba DT01ACA200 2TB                             | 4         | 0.54%   |
| SK hynix SHGP31-1000GM-2 1TB                       | 4         | 0.54%   |
| SK hynix SHGP31-1000GM 1TB                         | 4         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4         | 0.54%   |
| SanDisk SD8SBAT128G1122 128GB SSD                  | 4         | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                       | 4         | 0.54%   |
| Samsung SSD 860 EVO 500GB                          | 4         | 0.54%   |
| Samsung SSD 850 PRO 256GB                          | 4         | 0.54%   |
| Samsung NVMe SSD Drive 512GB                       | 4         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 4         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 3         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 3         | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB                       | 3         | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB                           | 3         | 0.4%    |
| WDC WD40EZAZ-00SF3B0 4TB                           | 3         | 0.4%    |
| WDC WD40EFRX-68WT0N0 4TB                           | 3         | 0.4%    |
| WDC WD3200AAJS-00L7A0 320GB                        | 3         | 0.4%    |
| WDC WD10EZEX-22MFCA0 1TB                           | 3         | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 3         | 0.4%    |
| Toshiba DT01ACA050 500GB                           | 3         | 0.4%    |
| TAMMUZ SSD 128GB                                   | 3         | 0.4%    |
| Seagate ST3500418AS 500GB                          | 3         | 0.4%    |
| Seagate ST2000DM008-2FR102 2TB                     | 3         | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 3         | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB                     | 3         | 0.4%    |
| SanDisk NVMe SSD Drive 512GB                       | 3         | 0.4%    |
| Samsung SSD 980 PRO 2TB                            | 3         | 0.4%    |
| Samsung SSD 860 EVO 250GB                          | 3         | 0.4%    |
| Samsung SSD 850 EVO 250GB                          | 3         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 66        | 103    | 33.17%  |
| Seagate             | 62        | 94     | 31.16%  |
| Toshiba             | 24        | 35     | 12.06%  |
| Hitachi             | 16        | 18     | 8.04%   |
| Samsung Electronics | 9         | 10     | 4.52%   |
| HGST                | 8         | 9      | 4.02%   |
| Unknown             | 5         | 6      | 2.51%   |
| Fujitsu             | 3         | 3      | 1.51%   |
| MARVELL             | 1         | 1      | 0.5%    |
| LaCie               | 1         | 1      | 0.5%    |
| JMicron Technology  | 1         | 1      | 0.5%    |
| ipTIME              | 1         | 1      | 0.5%    |
| HPE                 | 1         | 3      | 0.5%    |
| Hewlett-Packard     | 1         | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 87     | 30.64%  |
| Crucial             | 31        | 36     | 13.19%  |
| SanDisk             | 28        | 31     | 11.91%  |
| WDC                 | 16        | 21     | 6.81%   |
| Intel               | 8         | 11     | 3.4%    |
| Transcend           | 7         | 8      | 2.98%   |
| SK hynix            | 7         | 10     | 2.98%   |
| A-DATA Technology   | 7         | 7      | 2.98%   |
| TAMMUZ              | 5         | 8      | 2.13%   |
| Toshiba             | 4         | 11     | 1.7%    |
| Seagate             | 4         | 5      | 1.7%    |
| Micron Technology   | 4         | 5      | 1.7%    |
| China               | 4         | 4      | 1.7%    |
| Team                | 3         | 3      | 1.28%   |
| SPCC                | 3         | 3      | 1.28%   |
| Plextor             | 3         | 5      | 1.28%   |
| LITEON              | 3         | 3      | 1.28%   |
| Kingston            | 3         | 4      | 1.28%   |
| KingSpec            | 2         | 2      | 0.85%   |
| Apple               | 2         | 2      | 0.85%   |
| ZTC                 | 1         | 1      | 0.43%   |
| VIEW                | 1         | 1      | 0.43%   |
| TYPEC 1T            | 1         | 1      | 0.43%   |
| T-FORCE             | 1         | 1      | 0.43%   |
| RevuAhn             | 1         | 1      | 0.43%   |
| QNIX                | 1         | 1      | 0.43%   |
| PHINOCOM            | 1         | 1      | 0.43%   |
| OSCOO               | 1         | 1      | 0.43%   |
| OCZ                 | 1         | 2      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| MG                  | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| IPLEX               | 1         | 1      | 0.43%   |
| Imation             | 1         | 2      | 0.43%   |
| GLOWAY              | 1         | 1      | 0.43%   |
| FORESEE             | 1         | 1      | 0.43%   |
| Biostar             | 1         | 1      | 0.43%   |
| Apacer              | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 209       | 287    | 34.89%  |
| NVMe    | 177       | 242    | 29.55%  |
| HDD     | 164       | 286    | 27.38%  |
| MMC     | 41        | 62     | 6.84%   |
| Unknown | 8         | 9      | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 282       | 550    | 53.51%  |
| NVMe | 177       | 240    | 33.59%  |
| MMC  | 41        | 62     | 7.78%   |
| SAS  | 27        | 34     | 5.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 226       | 324    | 57.51%  |
| 0.51-1.0   | 85        | 114    | 21.63%  |
| 1.01-2.0   | 36        | 50     | 9.16%   |
| 3.01-4.0   | 20        | 39     | 5.09%   |
| 4.01-10.0  | 13        | 22     | 3.31%   |
| 2.01-3.0   | 10        | 15     | 2.54%   |
| 10.01-20.0 | 3         | 9      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 142       | 30.87%  |
| 251-500        | 89        | 19.35%  |
| 501-1000       | 57        | 12.39%  |
| 1001-2000      | 40        | 8.7%    |
| 51-100         | 40        | 8.7%    |
| More than 3000 | 26        | 5.65%   |
| 21-50          | 24        | 5.22%   |
| 2001-3000      | 18        | 3.91%   |
| 1-20           | 17        | 3.7%    |
| Unknown        | 7         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 193       | 40.89%  |
| 21-50          | 85        | 18.01%  |
| 101-250        | 58        | 12.29%  |
| 51-100         | 40        | 8.47%   |
| 251-500        | 38        | 8.05%   |
| 501-1000       | 25        | 5.3%    |
| 2001-3000      | 9         | 1.91%   |
| 1001-2000      | 9         | 1.91%   |
| More than 3000 | 8         | 1.69%   |
| Unknown        | 7         | 1.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                                  | 1         | 1      | 3.45%   |
| WDC WD7500AACS-00D6B0 752GB                                   | 1         | 1      | 3.45%   |
| WDC WD5000AAKX-75U6AA0 500GB                                  | 1         | 1      | 3.45%   |
| WDC WD40EZRZ-00WN9B0 4TB                                      | 1         | 1      | 3.45%   |
| WDC WD3200AAJS-00L7A0 320GB                                   | 1         | 2      | 3.45%   |
| WDC WD1600BEVT-22A23T0 160GB                                  | 1         | 1      | 3.45%   |
| WDC WD10JPVX-75JC3T0 1TB                                      | 1         | 1      | 3.45%   |
| WDC WD1001FALS-00J7B1 1TB                                     | 1         | 1      | 3.45%   |
| Toshiba MK5061GSYN 500GB                                      | 1         | 1      | 3.45%   |
| Toshiba MK2565GSX 250GB                                       | 1         | 1      | 3.45%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                         | 1         | 1      | 3.45%   |
| SK hynix HFS128G3AMNM-1010A 128GB SSD                         | 1         | 1      | 3.45%   |
| Seagate ST500DM009-2F110A 500GB                               | 1         | 1      | 3.45%   |
| Seagate ST4000DM000-1F2168 4TB                                | 1         | 1      | 3.45%   |
| Seagate ST3500418AS 500GB                                     | 1         | 1      | 3.45%   |
| Seagate ST1000DM003-1CH162 1TB                                | 1         | 1      | 3.45%   |
| SanDisk SD9SN8W256G1009 256GB SSD                             | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 830 Series 512GB                      | 1         | 1      | 3.45%   |
| Samsung Electronics SM961 NVMe 1024GB                         | 1         | 1      | 3.45%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1      | 3.45%   |
| Phison ES 512GB                                               | 1         | 1      | 3.45%   |
| LITEONIT LMT-256M3M 256GB SSD                                 | 1         | 1      | 3.45%   |
| LITEON LMH-128V2M 128GB SSD                                   | 1         | 1      | 3.45%   |
| Kingston SHFS37A120G 120GB SSD                                | 1         | 1      | 3.45%   |
| Intel SSDSA2CW120G3 120GB                                     | 1         | 1      | 3.45%   |
| Hitachi HTS541616J9SA00 160GB                                 | 1         | 1      | 3.45%   |
| HGST HTS721010A9E630 1TB                                      | 1         | 1      | 3.45%   |
| HGST HDN726060ALE610 6TB                                      | 1         | 1      | 3.45%   |
| A-DATA Technology SU650 240GB SSD                             | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 27.59%  |
| Seagate             | 4         | 4      | 13.79%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| SK hynix            | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| SanDisk             | 1         | 1      | 3.45%   |
| Phison              | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |
| LITEON              | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 9      | 47.06%  |
| Seagate | 4         | 4      | 23.53%  |
| Toshiba | 2         | 2      | 11.76%  |
| HGST    | 2         | 2      | 11.76%  |
| Hitachi | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 55.56%  |
| SSD  | 9         | 9      | 33.33%  |
| NVMe | 3         | 3      | 11.11%  |

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
| Detected | 270       | 531    | 56.37%  |
| Works    | 182       | 325    | 38%     |
| Malfunc  | 27        | 30     | 5.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 261       | 46.03%  |
| AMD                              | 75        | 13.23%  |
| Samsung Electronics              | 72        | 12.7%   |
| SanDisk                          | 30        | 5.29%   |
| SK hynix                         | 22        | 3.88%   |
| ASMedia Technology               | 15        | 2.65%   |
| Phison Electronics               | 11        | 1.94%   |
| JMicron Technology               | 11        | 1.94%   |
| Silicon Motion                   | 9         | 1.59%   |
| Micron Technology                | 8         | 1.41%   |
| Toshiba America Info Systems     | 6         | 1.06%   |
| Union Memory (Shenzhen)          | 5         | 0.88%   |
| Marvell Technology Group         | 5         | 0.88%   |
| Kingston Technology Company      | 5         | 0.88%   |
| Apple                            | 4         | 0.71%   |
| ADATA Technology                 | 4         | 0.71%   |
| Micron/Crucial Technology        | 3         | 0.53%   |
| KIOXIA                           | 3         | 0.53%   |
| Broadcom / LSI                   | 3         | 0.53%   |
| Seagate Technology               | 2         | 0.35%   |
| Nvidia                           | 2         | 0.35%   |
| VIA Technologies                 | 1         | 0.18%   |
| Solid State Storage Technology   | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Realtek Semiconductor            | 1         | 0.18%   |
| O2 Micro                         | 1         | 0.18%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.18%   |
| Lite-On Technology               | 1         | 0.18%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.18%   |
| Hewlett-Packard                  | 1         | 0.18%   |
| Biwin Storage Technology         | 1         | 0.18%   |
| Adaptec                          | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 60        | 9.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 31        | 4.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23        | 3.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 18        | 2.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 17        | 2.62%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14        | 2.15%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 13        | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 2%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 2%      |
| Samsung NVMe SSD Controller 980                                                         | 12        | 1.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 1.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 1.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9         | 1.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8         | 1.23%   |
| Micron NVMe Storage Controller                                                          | 8         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8         | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.23%   |
| AMD FCH SATA Controller D                                                               | 8         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 1.08%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7         | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 0.92%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6         | 0.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 0.92%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 5         | 0.77%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5         | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.77%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 5         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 294       | 54.04%  |
| NVMe | 179       | 32.9%   |
| IDE  | 44        | 8.09%   |
| RAID | 23        | 4.23%   |
| SAS  | 2         | 0.37%   |
| SCSI | 2         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 335       | 75.62%  |
| AMD    | 99        | 22.35%  |
| ARM    | 9         | 2.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz              | 8         | 1.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.58%   |
| ARM Processor                                 | 7         | 1.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 1.35%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 5         | 1.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 1.13%   |
| Intel 12th Gen Core i5-1240P                  | 5         | 1.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.13%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 1.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz              | 4         | 0.9%    |
| AMD Ryzen 5 5625U with Radeon Graphics        | 4         | 0.9%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 4         | 0.9%    |
| Intel Pentium CPU G4400 @ 3.30GHz             | 3         | 0.68%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.68%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 0.68%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.68%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.68%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 0.68%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 0.68%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 3         | 0.68%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.68%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.68%   |
| AMD Custom APU 0405                           | 3         | 0.68%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 2         | 0.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.45%   |
| Intel Pentium 4 CPU 3.00GHz                   | 2         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 85        | 19.19%  |
| Intel Core i7           | 68        | 15.35%  |
| Other                   | 56        | 12.64%  |
| AMD Ryzen 5             | 29        | 6.55%   |
| Intel Core i3           | 24        | 5.42%   |
| AMD Ryzen 7             | 21        | 4.74%   |
| Intel Celeron           | 19        | 4.29%   |
| Intel Xeon              | 17        | 3.84%   |
| Intel Pentium           | 15        | 3.39%   |
| Intel Atom              | 12        | 2.71%   |
| Intel Core i9           | 11        | 2.48%   |
| Intel Core 2 Duo        | 10        | 2.26%   |
| AMD Ryzen 3             | 10        | 2.26%   |
| Intel Core 2 Quad       | 6         | 1.35%   |
| AMD Ryzen Threadripper  | 5         | 1.13%   |
| AMD Ryzen 9             | 5         | 1.13%   |
| AMD Ryzen 7 PRO         | 5         | 1.13%   |
| Intel Xeon Silver       | 4         | 0.9%    |
| Intel Core m3           | 4         | 0.9%    |
| AMD Ryzen 5 PRO         | 4         | 0.9%    |
| AMD A10                 | 4         | 0.9%    |
| Intel Core 2            | 3         | 0.68%   |
| Intel Pentium Silver    | 2         | 0.45%   |
| Intel Pentium Gold      | 2         | 0.45%   |
| Intel Pentium Dual-Core | 2         | 0.45%   |
| Intel Pentium 4         | 2         | 0.45%   |
| Intel Genuine           | 2         | 0.45%   |
| AMD A8                  | 2         | 0.45%   |
| AMD A4                  | 2         | 0.45%   |
| Intel Xeon Gold         | 1         | 0.23%   |
| Intel Pentium Dual      | 1         | 0.23%   |
| ARM AArch64             | 1         | 0.23%   |
| AMD Ryzen Embedded      | 1         | 0.23%   |
| AMD Quad-Core           | 1         | 0.23%   |
| AMD Phenom II X6        | 1         | 0.23%   |
| AMD Phenom              | 1         | 0.23%   |
| AMD FX                  | 1         | 0.23%   |
| AMD Athlon II X2        | 1         | 0.23%   |
| AMD Athlon II           | 1         | 0.23%   |
| AMD Athlon 64 X2        | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 164       | 37.02%  |
| 2       | 131       | 29.57%  |
| 6       | 56        | 12.64%  |
| 8       | 46        | 10.38%  |
| 12      | 14        | 3.16%   |
| 16      | 6         | 1.35%   |
| 14      | 5         | 1.13%   |
| 10      | 5         | 1.13%   |
| 32      | 3         | 0.68%   |
| 20      | 3         | 0.68%   |
| 1       | 3         | 0.68%   |
| 24      | 2         | 0.45%   |
| 64      | 1         | 0.23%   |
| 28      | 1         | 0.23%   |
| 22      | 1         | 0.23%   |
| 18      | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 433       | 97.74%  |
| 2      | 10        | 2.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 301       | 67.95%  |
| 1       | 141       | 31.83%  |
| Unknown | 1         | 0.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 432       | 97.3%   |
| Unknown        | 10        | 2.25%   |
| 64-bit         | 1         | 0.23%   |
| 32-bit         | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 19.47%  |
| 0x306a9    | 27        | 5.97%   |
| 0x306c3    | 20        | 4.42%   |
| 0x806c1    | 17        | 3.76%   |
| 0x806ec    | 14        | 3.1%    |
| 0x906e9    | 13        | 2.88%   |
| 0x206a7    | 13        | 2.88%   |
| 0x08600106 | 13        | 2.88%   |
| 0x906ea    | 12        | 2.65%   |
| 0x906a3    | 10        | 2.21%   |
| 0x806ea    | 10        | 2.21%   |
| 0x806e9    | 10        | 2.21%   |
| 0x0a50000c | 10        | 2.21%   |
| 0x906ed    | 8         | 1.77%   |
| 0x20655    | 8         | 1.77%   |
| 0x1067a    | 8         | 1.77%   |
| 0x706a1    | 7         | 1.55%   |
| 0x806eb    | 6         | 1.33%   |
| 0x40651    | 6         | 1.33%   |
| 0x30678    | 6         | 1.33%   |
| 0x706e5    | 5         | 1.11%   |
| 0x506e3    | 5         | 1.11%   |
| 0x406c4    | 5         | 1.11%   |
| 0x306f2    | 5         | 1.11%   |
| 0x306d4    | 5         | 1.11%   |
| 0x106e5    | 5         | 1.11%   |
| 0x08108102 | 5         | 1.11%   |
| 0xa0652    | 4         | 0.88%   |
| 0x6fb      | 4         | 0.88%   |
| 0x0800820d | 4         | 0.88%   |
| 0x08001138 | 4         | 0.88%   |
| 0x08001137 | 4         | 0.88%   |
| 0xa0655    | 3         | 0.66%   |
| 0x806d1    | 3         | 0.66%   |
| 0x6fd      | 3         | 0.66%   |
| 0x50654    | 3         | 0.66%   |
| 0x406e3    | 3         | 0.66%   |
| 0x30673    | 3         | 0.66%   |
| 0x08101016 | 3         | 0.66%   |
| 0x0810100b | 3         | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 85        | 19.19%  |
| Haswell          | 40        | 9.03%   |
| IvyBridge        | 30        | 6.77%   |
| Unknown          | 27        | 6.09%   |
| Zen 2            | 26        | 5.87%   |
| Skylake          | 21        | 4.74%   |
| Zen 3            | 19        | 4.29%   |
| Zen              | 19        | 4.29%   |
| Silvermont       | 19        | 4.29%   |
| TigerLake        | 18        | 4.06%   |
| Westmere         | 14        | 3.16%   |
| SandyBridge      | 14        | 3.16%   |
| Penryn           | 14        | 3.16%   |
| Zen+             | 13        | 2.93%   |
| CometLake        | 12        | 2.71%   |
| Alderlake Hybrid | 12        | 2.71%   |
| IceLake          | 10        | 2.26%   |
| Core             | 10        | 2.26%   |
| Goldmont plus    | 9         | 2.03%   |
| Broadwell        | 6         | 1.35%   |
| Nehalem          | 5         | 1.13%   |
| Piledriver       | 4         | 0.9%    |
| K10              | 4         | 0.9%    |
| Jaguar           | 3         | 0.68%   |
| Steamroller      | 2         | 0.45%   |
| NetBurst         | 2         | 0.45%   |
| P6               | 1         | 0.23%   |
| K8 Hammer        | 1         | 0.23%   |
| K10 Llano        | 1         | 0.23%   |
| Excavator        | 1         | 0.23%   |
| Bonnell          | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 251       | 48.83%  |
| Nvidia                           | 154       | 29.96%  |
| AMD                              | 99        | 19.26%  |
| ASPEED Technology                | 6         | 1.17%   |
| Matrox Electronics Systems       | 3         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 21        | 3.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 3.04%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 13        | 2.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 2.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 2.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 2.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.9%    |
| Intel UHD Graphics 620                                                                   | 10        | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 6         | 1.14%   |
| Intel HD Graphics 630                                                                    | 6         | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.14%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6         | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.14%   |
| AMD Barcelo                                                                              | 6         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.95%   |
| Intel HD Graphics 620                                                                    | 5         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.95%   |
| Nvidia TU117M [GeForce MX450]                                                            | 4         | 0.76%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.76%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4         | 0.76%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.76%   |
| Intel HD Graphics 530                                                                    | 4         | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.57%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 3         | 0.57%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 182       | 40.9%   |
| 1 x Nvidia      | 93        | 20.9%   |
| 1 x AMD         | 81        | 18.2%   |
| Intel + Nvidia  | 50        | 11.24%  |
| Other           | 9         | 2.02%   |
| Intel + AMD     | 7         | 1.57%   |
| AMD + Nvidia    | 6         | 1.35%   |
| 2 x AMD         | 5         | 1.12%   |
| 1 x ASPEED      | 4         | 0.9%    |
| 2 x Nvidia      | 2         | 0.45%   |
| Nvidia + ASPEED | 2         | 0.45%   |
| 1 x Matrox      | 2         | 0.45%   |
| 1 x SiS         | 1         | 0.22%   |
| Nvidia + Matrox | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 328       | 73.38%  |
| Proprietary | 88        | 19.69%  |
| Unknown     | 31        | 6.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 255       | 56.67%  |
| 1.01-2.0   | 43        | 9.56%   |
| 0.01-0.5   | 43        | 9.56%   |
| 0.51-1.0   | 36        | 8%      |
| 3.01-4.0   | 31        | 6.89%   |
| 7.01-8.0   | 14        | 3.11%   |
| 8.01-16.0  | 10        | 2.22%   |
| 5.01-6.0   | 9         | 2%      |
| 2.01-3.0   | 4         | 0.89%   |
| 16.01-24.0 | 4         | 0.89%   |
| 4.01-5.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 69        | 15.33%  |
| LG Display              | 51        | 11.33%  |
| Goldstar                | 50        | 11.11%  |
| AU Optronics            | 45        | 10%     |
| BOE                     | 34        | 7.56%   |
| Chimei Innolux          | 29        | 6.44%   |
| Dell                    | 18        | 4%      |
| Unknown                 | 10        | 2.22%   |
| Apple                   | 10        | 2.22%   |
| Philips                 | 9         | 2%      |
| Sharp                   | 8         | 1.78%   |
| LG Electronics          | 7         | 1.56%   |
| Lenovo                  | 7         | 1.56%   |
| Hewlett-Packard         | 6         | 1.33%   |
| AOC                     | 6         | 1.33%   |
| PRISM+                  | 5         | 1.11%   |
| PANDA                   | 5         | 1.11%   |
| OUT                     | 5         | 1.11%   |
| BenQ                    | 5         | 1.11%   |
| ALP                     | 5         | 1.11%   |
| JCH                     | 4         | 0.89%   |
| Valve                   | 3         | 0.67%   |
| CPT                     | 3         | 0.67%   |
| Ancor Communications    | 3         | 0.67%   |
| Unknown (ADE)           | 2         | 0.44%   |
| RTK                     | 2         | 0.44%   |
| OOO                     | 2         | 0.44%   |
| MStar                   | 2         | 0.44%   |
| JRY                     | 2         | 0.44%   |
| InfoVision              | 2         | 0.44%   |
| Denver                  | 2         | 0.44%   |
| CSO                     | 2         | 0.44%   |
| Chi Mei Optoelectronics | 2         | 0.44%   |
| Yamaha                  | 1         | 0.22%   |
| VMO                     | 1         | 0.22%   |
| UPV                     | 1         | 0.22%   |
| TopView                 | 1         | 0.22%   |
| TMX                     | 1         | 0.22%   |
| TGL                     | 1         | 0.22%   |
| Sony                    | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 8         | 1.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 1.51%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 5         | 1.08%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch | 4         | 0.86%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.86%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 0.65%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                        | 3         | 0.65%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 3         | 0.65%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.65%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.65%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.43%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 2         | 0.43%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 890x500mm 40.2-inch | 2         | 0.43%   |
| PRISM+ ULTRON 3547UC INN0035 2560x1080 820x345mm 35.0-inch            | 2         | 0.43%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 2         | 0.43%   |
| OOO 15.6' monitor OOO0001 1920x1080 409x230mm 18.5-inch               | 2         | 0.43%   |
| LG Display LCD Monitor LGD0644 1920x1080 309x174mm 14.0-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD0421 1920x1080 345x194mm 15.6-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.43%   |
| JRY Digital JRY0215 1920x1080 368x207mm 16.6-inch                     | 2         | 0.43%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 2         | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.43%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 0.43%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 2         | 0.43%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 223       | 50.8%   |
| 3840x2160 (4K)     | 40        | 9.11%   |
| 1366x768 (WXGA)    | 38        | 8.66%   |
| 2560x1440 (QHD)    | 24        | 5.47%   |
| 1920x1200 (WUXGA)  | 14        | 3.19%   |
| 1280x1024 (SXGA)   | 13        | 2.96%   |
| 2560x1600          | 12        | 2.73%   |
| 1600x900 (HD+)     | 9         | 2.05%   |
| 1680x1050 (WSXGA+) | 8         | 1.82%   |
| 1280x800 (WXGA)    | 8         | 1.82%   |
| 3440x1440          | 7         | 1.59%   |
| 2880x1800          | 6         | 1.37%   |
| 2560x1080          | 6         | 1.37%   |
| 1440x900 (WXGA+)   | 5         | 1.14%   |
| Unknown            | 5         | 1.14%   |
| 800x1280           | 3         | 0.68%   |
| 3840x1080          | 2         | 0.46%   |
| 3072x1920          | 2         | 0.46%   |
| 4880x2560          | 1         | 0.23%   |
| 3840x2400          | 1         | 0.23%   |
| 3840x1600          | 1         | 0.23%   |
| 3286x1080          | 1         | 0.23%   |
| 3200x1080          | 1         | 0.23%   |
| 2880x1620          | 1         | 0.23%   |
| 2160x1440          | 1         | 0.23%   |
| 2160x1350          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1920x1280          | 1         | 0.23%   |
| 1680x945           | 1         | 0.23%   |
| 1600x1200          | 1         | 0.23%   |
| 1400x1050          | 1         | 0.23%   |
| 1024x768 (XGA)     | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 25.06%  |
| 13      | 44        | 9.76%   |
| 27      | 37        | 8.2%    |
| Unknown | 37        | 8.2%    |
| 14      | 32        | 7.1%    |
| 24      | 27        | 5.99%   |
| 21      | 27        | 5.99%   |
| 23      | 23        | 5.1%    |
| 16      | 18        | 3.99%   |
| 17      | 14        | 3.1%    |
| 31      | 10        | 2.22%   |
| 34      | 8         | 1.77%   |
| 19      | 8         | 1.77%   |
| 20      | 7         | 1.55%   |
| 12      | 5         | 1.11%   |
| 18      | 4         | 0.89%   |
| 84      | 3         | 0.67%   |
| 40      | 3         | 0.67%   |
| 25      | 3         | 0.67%   |
| 11      | 3         | 0.67%   |
| 10      | 3         | 0.67%   |
| 7       | 3         | 0.67%   |
| 42      | 2         | 0.44%   |
| 35      | 2         | 0.44%   |
| 29      | 2         | 0.44%   |
| 22      | 2         | 0.44%   |
| 74      | 1         | 0.22%   |
| 54      | 1         | 0.22%   |
| 52      | 1         | 0.22%   |
| 49      | 1         | 0.22%   |
| 48      | 1         | 0.22%   |
| 46      | 1         | 0.22%   |
| 43      | 1         | 0.22%   |
| 39      | 1         | 0.22%   |
| 37      | 1         | 0.22%   |
| 33      | 1         | 0.22%   |
| 28      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 173       | 38.79%  |
| 501-600     | 83        | 18.61%  |
| 401-500     | 41        | 9.19%   |
| 201-300     | 41        | 9.19%   |
| Unknown     | 37        | 8.3%    |
| 351-400     | 25        | 5.61%   |
| 601-700     | 15        | 3.36%   |
| 701-800     | 9         | 2.02%   |
| 801-900     | 7         | 1.57%   |
| 1001-1500   | 5         | 1.12%   |
| 1501-2000   | 4         | 0.9%    |
| 901-1000    | 3         | 0.67%   |
| 1-100       | 3         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 283       | 69.02%  |
| 16/10   | 50        | 12.2%   |
| Unknown | 34        | 8.29%   |
| 21/9    | 12        | 2.93%   |
| 5/4     | 10        | 2.44%   |
| 4/3     | 10        | 2.44%   |
| 3/2     | 4         | 0.98%   |
| 32/9    | 3         | 0.73%   |
| 0.67    | 3         | 0.73%   |
| 6/5     | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 25.06%  |
| 201-250        | 65        | 14.54%  |
| 81-90          | 49        | 10.96%  |
| 301-350        | 38        | 8.5%    |
| Unknown        | 37        | 8.28%   |
| 71-80          | 25        | 5.59%   |
| 351-500        | 24        | 5.37%   |
| 151-200        | 18        | 4.03%   |
| 251-300        | 12        | 2.68%   |
| 121-130        | 11        | 2.46%   |
| 111-120        | 11        | 2.46%   |
| 501-1000       | 10        | 2.24%   |
| More than 1000 | 6         | 1.34%   |
| 131-140        | 6         | 1.34%   |
| 61-70          | 5         | 1.12%   |
| 141-150        | 5         | 1.12%   |
| 51-60          | 4         | 0.89%   |
| 91-100         | 4         | 0.89%   |
| 1-40           | 3         | 0.67%   |
| 41-50          | 2         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 131       | 29.71%  |
| 51-100        | 114       | 25.85%  |
| 101-120       | 88        | 19.95%  |
| 161-240       | 49        | 11.11%  |
| Unknown       | 37        | 8.39%   |
| More than 240 | 17        | 3.85%   |
| 1-50          | 5         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 347       | 76.77%  |
| 2     | 65        | 14.38%  |
| 0     | 36        | 7.96%   |
| 3     | 4         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 250       | 40.06%  |
| Intel                             | 234       | 37.5%   |
| Qualcomm Atheros                  | 41        | 6.57%   |
| Broadcom                          | 28        | 4.49%   |
| ASIX Electronics                  | 10        | 1.6%    |
| Ralink Technology                 | 7         | 1.12%   |
| MediaTek                          | 7         | 1.12%   |
| Marvell Technology Group          | 6         | 0.96%   |
| Samsung Electronics               | 4         | 0.64%   |
| Ralink                            | 4         | 0.64%   |
| U-Blox                            | 3         | 0.48%   |
| Broadcom Limited                  | 3         | 0.48%   |
| Apple                             | 3         | 0.48%   |
| TP-Link                           | 2         | 0.32%   |
| Nvidia                            | 2         | 0.32%   |
| Lenovo                            | 2         | 0.32%   |
| Exar                              | 2         | 0.32%   |
| D-Link                            | 2         | 0.32%   |
| Arduino SA                        | 2         | 0.32%   |
| Wilocity                          | 1         | 0.16%   |
| Van Ooijen Technische Informatica | 1         | 0.16%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.16%   |
| Quectel Wireless Solutions        | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| PEAK-System Technik               | 1         | 0.16%   |
| Microsoft                         | 1         | 0.16%   |
| Microchip Technology              | 1         | 0.16%   |
| Kinesis                           | 1         | 0.16%   |
| Comneon                           | 1         | 0.16%   |
| Aquantia                          | 1         | 0.16%   |
| American Megatrends               | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 184       | 25.24%  |
| Intel Wi-Fi 6 AX200                                               | 36        | 4.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 3.16%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.78%   |
| Intel Wireless 3165                                               | 13        | 1.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 13        | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.51%   |
| Intel Wireless 8265 / 8275                                        | 10        | 1.37%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 9         | 1.23%   |
| Intel Wireless 7260                                               | 8         | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 8         | 1.1%    |
| Intel Ethernet Controller I225-V                                  | 7         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.69%   |
| Intel Wireless 3160                                               | 5         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.55%   |
| Intel Wireless 7265                                               | 4         | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 190       | 58.46%  |
| Realtek Semiconductor      | 55        | 16.92%  |
| Qualcomm Atheros           | 30        | 9.23%   |
| Broadcom                   | 21        | 6.46%   |
| Ralink Technology          | 7         | 2.15%   |
| MediaTek                   | 7         | 2.15%   |
| Ralink                     | 4         | 1.23%   |
| TP-Link                    | 2         | 0.62%   |
| D-Link                     | 2         | 0.62%   |
| Broadcom Limited           | 2         | 0.62%   |
| Wilocity                   | 1         | 0.31%   |
| Quectel Wireless Solutions | 1         | 0.31%   |
| Qualcomm                   | 1         | 0.31%   |
| Marvell Technology Group   | 1         | 0.31%   |
| Arduino SA                 | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 36        | 10.98%  |
| Intel Wi-Fi 6 AX201                                           | 16        | 4.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 13        | 3.96%   |
| Intel Wireless 3165                                           | 13        | 3.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 13        | 3.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 11        | 3.35%   |
| Intel Wireless 8265 / 8275                                    | 10        | 3.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 9         | 2.74%   |
| Intel Wireless 7260                                           | 8         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 7         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 7         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 6         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 6         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5         | 1.52%   |
| Intel Wireless 3160                                           | 5         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 1.52%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 5         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 4         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 4         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 4         | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 4         | 1.22%   |
| Intel Wireless 7265                                           | 4         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 4         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 3         | 0.91%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 3         | 0.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3         | 0.91%   |
| Realtek 802.11ac NIC                                          | 3         | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 0.91%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 0.91%   |
| Intel Centrino Wireless-N 2230                                | 3         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                | 3         | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 3         | 0.91%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 3         | 0.91%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 234       | 63.07%  |
| Intel                            | 83        | 22.37%  |
| Qualcomm Atheros                 | 13        | 3.5%    |
| ASIX Electronics                 | 10        | 2.7%    |
| Broadcom                         | 9         | 2.43%   |
| Marvell Technology Group         | 5         | 1.35%   |
| Samsung Electronics              | 4         | 1.08%   |
| Apple                            | 3         | 0.81%   |
| Nvidia                           | 2         | 0.54%   |
| Lenovo                           | 2         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Microsoft                        | 1         | 0.27%   |
| Microchip Technology             | 1         | 0.27%   |
| Broadcom Limited                 | 1         | 0.27%   |
| Aquantia                         | 1         | 0.27%   |
| American Megatrends              | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 184       | 47.06%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 3.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.05%   |
| Intel Ethernet Controller I225-V                                  | 7         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.79%   |
| Intel I210 Gigabit Network Connection                             | 6         | 1.53%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.53%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.02%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.02%   |
| Intel Ethernet Controller X550                                    | 3         | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.77%   |
| Intel 82576 Gigabit Network Connection                            | 3         | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.51%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.51%   |
| Apple iBridge                                                     | 2         | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.26%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.26%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 350       | 52.24%  |
| WiFi     | 311       | 46.42%  |
| Modem    | 8         | 1.19%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 235       | 50.87%  |
| WiFi     | 227       | 49.13%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 223       | 50.23%  |
| 2     | 192       | 43.24%  |
| 0     | 13        | 2.93%   |
| 3     | 11        | 2.48%   |
| 4     | 4         | 0.9%    |
| 5     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 441       | 99.55%  |
| Yes  | 2         | 0.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 166       | 57.64%  |
| Cambridge Silicon Radio         | 26        | 9.03%   |
| Realtek Semiconductor           | 25        | 8.68%   |
| IMC Networks                    | 17        | 5.9%    |
| Broadcom                        | 17        | 5.9%    |
| Qualcomm Atheros Communications | 14        | 4.86%   |
| Foxconn / Hon Hai               | 6         | 2.08%   |
| Apple                           | 6         | 2.08%   |
| Lite-On Technology              | 4         | 1.39%   |
| ASUSTek Computer                | 3         | 1.04%   |
| TP-Link                         | 1         | 0.35%   |
| Qcom                            | 1         | 0.35%   |
| Micro Star International        | 1         | 0.35%   |
| Marvell Semiconductor           | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 44        | 15.28%  |
| Intel AX200 Bluetooth                                                               | 35        | 12.15%  |
| Intel AX201 Bluetooth                                                               | 33        | 11.46%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 26        | 9.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 7.99%   |
| Realtek Bluetooth Radio                                                             | 19        | 6.6%    |
| Intel Bluetooth Device                                                              | 17        | 5.9%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 3.82%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 2.43%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.74%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.74%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.39%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.04%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.04%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.04%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 1.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.69%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.69%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.69%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.69%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.35%   |
| Realtek CSR BS8510                                                                  | 1         | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.35%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.35%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.35%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.35%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.35%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth                                         | 1         | 0.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.35%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 309       | 53.28%  |
| AMD                                  | 118       | 20.34%  |
| Nvidia                               | 115       | 19.83%  |
| C-Media Electronics                  | 6         | 1.03%   |
| JMTek                                | 4         | 0.69%   |
| Texas Instruments                    | 3         | 0.52%   |
| Apple                                | 3         | 0.52%   |
| Lenovo                               | 2         | 0.34%   |
| Giga-Byte Technology                 | 2         | 0.34%   |
| Generalplus Technology               | 2         | 0.34%   |
| ASUSTek Computer                     | 2         | 0.34%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.17%   |
| Sony                                 | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.17%   |
| Razer USA                            | 1         | 0.17%   |
| No brand                             | 1         | 0.17%   |
| Native Instruments                   | 1         | 0.17%   |
| Micro Star International             | 1         | 0.17%   |
| Medeli Electronics                   | 1         | 0.17%   |
| Fry's Electronics                    | 1         | 0.17%   |
| EGO SYStems                          | 1         | 0.17%   |
| DigiTech                             | 1         | 0.17%   |
| Dell                                 | 1         | 0.17%   |
| BEHRINGER International              | 1         | 0.17%   |
| Unknown                              | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 53        | 7.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 35        | 5.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 26        | 3.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 3.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 2.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15        | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 2.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 1.89%   |
| Intel 200 Series PCH HD Audio                                              | 13        | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12        | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.31%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.31%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.31%   |
| Nvidia High Definition Audio Controller                                    | 8         | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 7         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.02%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6         | 0.87%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.87%   |
| Nvidia TU102 High Definition Audio Controller                              | 5         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5         | 0.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 0.73%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 149       | 56.44%  |
| SK hynix            | 41        | 15.53%  |
| Micron Technology   | 18        | 6.82%   |
| Unknown             | 13        | 4.92%   |
| Kingston            | 7         | 2.65%   |
| Unknown             | 5         | 1.89%   |
| Team                | 4         | 1.52%   |
| A-DATA Technology   | 4         | 1.52%   |
| KLEVV               | 3         | 1.14%   |
| Unknown (ABCD)      | 2         | 0.76%   |
| Ramaxel Technology  | 2         | 0.76%   |
| NOT SUPPORT         | 2         | 0.76%   |
| Imation             | 2         | 0.76%   |
| G.Skill             | 2         | 0.76%   |
| Unknown (899D)      | 1         | 0.38%   |
| Unknown (09D5)      | 1         | 0.38%   |
| Transcend           | 1         | 0.38%   |
| Silicon Power       | 1         | 0.38%   |
| Hewlett-Packard     | 1         | 0.38%   |
| GeIL                | 1         | 0.38%   |
| Essencore           | 1         | 0.38%   |
| Elpida              | 1         | 0.38%   |
| Crucial             | 1         | 0.38%   |
| Corsair             | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.73%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 7         | 2.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.71%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s             | 5         | 1.71%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s             | 5         | 1.71%   |
| Unknown                                                          | 5         | 1.71%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.37%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s              | 4         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.02%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.02%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 1.02%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 1.02%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 3         | 1.02%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 3         | 1.02%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.02%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.02%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 3         | 1.02%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s              | 3         | 1.02%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 3         | 1.02%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 3         | 1.02%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.02%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.68%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 2         | 0.68%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 2         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 139       | 59.4%   |
| DDR3    | 53        | 22.65%  |
| LPDDR4  | 13        | 5.56%   |
| LPDDR3  | 8         | 3.42%   |
| Unknown | 6         | 2.56%   |
| SDRAM   | 4         | 1.71%   |
| LPDDR5  | 4         | 1.71%   |
| DDR5    | 4         | 1.71%   |
| DDR2    | 3         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 48.31%  |
| DIMM         | 86        | 36.44%  |
| Row Of Chips | 30        | 12.71%  |
| Unknown      | 5         | 2.12%   |
| Chip         | 1         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 99        | 39.13%  |
| 4096  | 63        | 24.9%   |
| 16384 | 48        | 18.97%  |
| 32768 | 19        | 7.51%   |
| 2048  | 19        | 7.51%   |
| 1024  | 4         | 1.58%   |
| 65536 | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 59        | 23.05%  |
| 2667    | 41        | 16.02%  |
| 1600    | 34        | 13.28%  |
| 2400    | 19        | 7.42%   |
| 2133    | 17        | 6.64%   |
| 4267    | 8         | 3.13%   |
| 3500    | 7         | 2.73%   |
| 3266    | 7         | 2.73%   |
| 4800    | 6         | 2.34%   |
| 1333    | 6         | 2.34%   |
| 1334    | 5         | 1.95%   |
| 6400    | 4         | 1.56%   |
| 3066    | 4         | 1.56%   |
| 1867    | 4         | 1.56%   |
| 8400    | 3         | 1.17%   |
| 3466    | 3         | 1.17%   |
| 2933    | 3         | 1.17%   |
| 2666    | 3         | 1.17%   |
| 1866    | 3         | 1.17%   |
| 1800    | 3         | 1.17%   |
| Unknown | 3         | 1.17%   |
| 3400    | 2         | 0.78%   |
| 1067    | 2         | 0.78%   |
| 1066    | 2         | 0.78%   |
| 4802    | 1         | 0.39%   |
| 4266    | 1         | 0.39%   |
| 4199    | 1         | 0.39%   |
| 3866    | 1         | 0.39%   |
| 3000    | 1         | 0.39%   |
| 2048    | 1         | 0.39%   |
| 800     | 1         | 0.39%   |
| 667     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 4         | 50%     |
| Seiko Epson         | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Hewlett-Packard     | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L222 Series  | 1         | 12.5%   |
| Samsung CLX-3180 Series  | 1         | 12.5%   |
| HP OfficeJet 4650 series | 1         | 12.5%   |
| Canon PIXMA MP280        | 1         | 12.5%   |
| Canon MF4800 Series      | 1         | 12.5%   |
| Canon G4010 series       | 1         | 12.5%   |
| Canon E560 series        | 1         | 12.5%   |
| Brother DCP-T310         | 1         | 12.5%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 17.41%  |
| IMC Networks                           | 33        | 14.73%  |
| Realtek Semiconductor                  | 13        | 5.8%    |
| Microdia                               | 13        | 5.8%    |
| Silicon Motion                         | 12        | 5.36%   |
| Acer                                   | 12        | 5.36%   |
| Quanta                                 | 10        | 4.46%   |
| Bison Electronics                      | 10        | 4.46%   |
| Syntek                                 | 9         | 4.02%   |
| Apple                                  | 8         | 3.57%   |
| Sunplus Innovation Technology          | 7         | 3.13%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.68%   |
| Suyin                                  | 5         | 2.23%   |
| SunplusIT                              | 5         | 2.23%   |
| Logitech                               | 5         | 2.23%   |
| Luxvisions Innotech Limited            | 4         | 1.79%   |
| Z-Star Microelectronics                | 3         | 1.34%   |
| Sony                                   | 2         | 0.89%   |
| Samsung Electronics                    | 2         | 0.89%   |
| Microsoft                              | 2         | 0.89%   |
| lihappe8                               | 2         | 0.89%   |
| LG Electronics                         | 2         | 0.89%   |
| Lenovo                                 | 2         | 0.89%   |
| Canon                                  | 2         | 0.89%   |
| Telmax Communications                  | 1         | 0.45%   |
| Sunplus IT                             | 1         | 0.45%   |
| Sonix Technology                       | 1         | 0.45%   |
| Goodong Industry                       | 1         | 0.45%   |
| GEMBIRD                                | 1         | 0.45%   |
| DigiTech                               | 1         | 0.45%   |
| Cubeternet                             | 1         | 0.45%   |
| ARC International                      | 1         | 0.45%   |
| Alcor Micro                            | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                  | 12        | 5.31%   |
| IMC Networks USB2.0 HD UVC WebCam               | 10        | 4.42%   |
| Chicony Integrated Camera                       | 10        | 4.42%   |
| Syntek Integrated Camera                        | 7         | 3.1%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera | 7         | 3.1%    |
| Microdia Integrated_Webcam_HD                   | 7         | 3.1%    |
| Chicony HD WebCam                               | 6         | 2.65%   |
| Realtek LG Camera                               | 5         | 2.21%   |
| Silicon Motion LG HD WebCam                     | 4         | 1.77%   |
| IMC Networks USB2.0 VGA UVC WebCam              | 4         | 1.77%   |
| Bison HD Webcam                                 | 4         | 1.77%   |
| Suyin HP Truevision HD                          | 3         | 1.33%   |
| SunplusIT 1080p FHD Camera                      | 3         | 1.33%   |
| Quanta HP TrueVision HD Camera                  | 3         | 1.33%   |
| Chicony USB 2.0 Camera                          | 3         | 1.33%   |
| Chicony LG HD WebCam                            | 3         | 1.33%   |
| Chicony LG Camera                               | 3         | 1.33%   |
| Apple FaceTime HD Camera (Built-in)             | 3         | 1.33%   |
| Acer Lenovo EasyCamera                          | 3         | 1.33%   |
| Acer Integrated Camera                          | 3         | 1.33%   |
| Z-Star Webcam                                   | 2         | 0.88%   |
| SunplusIT 720p HD Camera                        | 2         | 0.88%   |
| Sunplus FHD Camera Microphone                   | 2         | 0.88%   |
| Sony ILCE-7S                                    | 2         | 0.88%   |
| Silicon Motion WebCam SC-10HDP12631N            | 2         | 0.88%   |
| Samsung Galaxy series, misc. (MTP mode)         | 2         | 0.88%   |
| Realtek USB2.0 HD UVC WebCam                    | 2         | 0.88%   |
| Realtek Integrated_Webcam_HD                    | 2         | 0.88%   |
| Quanta USB HD Webcam                            | 2         | 0.88%   |
| Quanta LG Webcam                                | 2         | 0.88%   |
| Quanta HP HD Camera                             | 2         | 0.88%   |
| Microdia USB 2.0 Camera                         | 2         | 0.88%   |
| Luxvisions Innotech Limited HP HD Camera        | 2         | 0.88%   |
| Logitech Webcam C110                            | 2         | 0.88%   |
| Logitech C922 Pro Stream Webcam                 | 2         | 0.88%   |
| lihappe8 USB 2.0 Camera                         | 2         | 0.88%   |
| IMC Networks USB HD Webcam                      | 2         | 0.88%   |
| IMC Networks Integrated RGB Camera              | 2         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)         | 2         | 0.88%   |
| Chicony HP TrueVision HD Camera                 | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 21        | 36.21%  |
| Validity Sensors                   | 9         | 15.52%  |
| Samsung Electronics                | 8         | 13.79%  |
| Shenzhen Goodix Technology         | 6         | 10.34%  |
| Upek                               | 4         | 6.9%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 5.17%   |
| STMicroelectronics                 | 2         | 3.45%   |
| LighTuning Technology              | 2         | 3.45%   |
| Elan Microelectronics              | 2         | 3.45%   |
| AuthenTec                          | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung Fingerprint Sensor Device - 730B                        | 5         | 8.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 6.9%    |
| Synaptics WBDI Fingerprint Reader USB 086                       | 4         | 6.9%    |
| Synaptics WBDI                                                  | 4         | 6.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 6.9%    |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 6.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 5.17%   |
| Samsung Fingerprint Device                                      | 3         | 5.17%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 5.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 3.45%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 3.45%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 3.45%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 3.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 1.72%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.72%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.72%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.72%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.72%   |
| Synaptics WBDI Device                                           | 1         | 1.72%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.72%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.72%   |
| Elan ELAN:ARM-M4                                                | 1         | 1.72%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 28.57%  |
| Alcor Micro      | 2         | 28.57%  |
| Upek             | 1         | 14.29%  |
| SCM Microsystems | 1         | 14.29%  |
| O2 Micro         | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 301       | 66.59%  |
| 1     | 118       | 26.11%  |
| 2     | 20        | 4.42%   |
| 3     | 7         | 1.55%   |
| 5     | 4         | 0.88%   |
| 4     | 2         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 30.53%  |
| Graphics card            | 43        | 22.63%  |
| Net/wireless             | 27        | 14.21%  |
| Unassigned class         | 13        | 6.84%   |
| Multimedia controller    | 13        | 6.84%   |
| Communication controller | 9         | 4.74%   |
| Chipcard                 | 7         | 3.68%   |
| Sound                    | 5         | 2.63%   |
| Net/ethernet             | 5         | 2.63%   |
| Camera                   | 5         | 2.63%   |
| Bluetooth                | 4         | 2.11%   |
| Network                  | 1         | 0.53%   |

