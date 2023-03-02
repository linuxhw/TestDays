Xubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

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

Total: 243

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| Dell          | Studio 1450                 | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Sony          | VPCEA3S1E                   | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| HP            | Laptop 17-bs0xx             | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.15.0-56-generic          | 23        | 11.22%  |
| 5.15.0-47-generic          | 19        | 9.27%   |
| 5.15.0-58-generic          | 17        | 8.29%   |
| 5.15.0-52-generic          | 16        | 7.8%    |
| 5.15.0-48-generic          | 16        | 7.8%    |
| 5.15.0-25-generic          | 13        | 6.34%   |
| 5.15.0-60-generic          | 12        | 5.85%   |
| 5.15.0-46-generic          | 8         | 3.9%    |
| 5.15.0-53-generic          | 7         | 3.41%   |
| 5.15.0-27-generic          | 7         | 3.41%   |
| 5.15.0-57-generic          | 6         | 2.93%   |
| 5.15.0-50-generic          | 5         | 2.44%   |
| 5.15.0-40-generic          | 5         | 2.44%   |
| 5.15.0-39-generic          | 5         | 2.44%   |
| 5.15.0-35-generic          | 5         | 2.44%   |
| 5.15.0-43-generic          | 4         | 1.95%   |
| 5.15.0-41-generic          | 4         | 1.95%   |
| 5.15.0-37-generic          | 3         | 1.46%   |
| 5.17.0-1020-oem            | 2         | 0.98%   |
| 5.17.0-1013-oem            | 2         | 0.98%   |
| 5.15.0-33-generic          | 2         | 0.98%   |
| 6.1.6-060106-generic       | 1         | 0.49%   |
| 6.1.0-1006-oem             | 1         | 0.49%   |
| 6.0.9-060009-generic       | 1         | 0.49%   |
| 6.0.7-x64v3-xanmod1        | 1         | 0.49%   |
| 6.0.0-1007-oem             | 1         | 0.49%   |
| 5.4.0-126-generic          | 1         | 0.49%   |
| 5.19.5-051905-generic      | 1         | 0.49%   |
| 5.19.0-32-generic          | 1         | 0.49%   |
| 5.19.0-28-generic          | 1         | 0.49%   |
| 5.19.0-051900-generic      | 1         | 0.49%   |
| 5.18.0-10.1-liquorix-amd64 | 1         | 0.49%   |
| 5.17.3-051703-generic      | 1         | 0.49%   |
| 5.17.0-ashpy3-lyesdef      | 1         | 0.49%   |
| 5.17.0-1025-oem            | 1         | 0.49%   |
| 5.17.0-1015-oem            | 1         | 0.49%   |
| 5.15.0-67-generic          | 1         | 0.49%   |
| 5.15.0-54-generic          | 1         | 0.49%   |
| 5.15.0-50-lowlatency       | 1         | 0.49%   |
| 5.15.0-48-lowlatency       | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 176       | 89.8%   |
| 5.17.0   | 7         | 3.57%   |
| 5.19.0   | 3         | 1.53%   |
| 6.1.6    | 1         | 0.51%   |
| 6.1.0    | 1         | 0.51%   |
| 6.0.9    | 1         | 0.51%   |
| 6.0.7    | 1         | 0.51%   |
| 6.0.0    | 1         | 0.51%   |
| 5.4.0    | 1         | 0.51%   |
| 5.19.5   | 1         | 0.51%   |
| 5.18.0   | 1         | 0.51%   |
| 5.17.3   | 1         | 0.51%   |
| 4.19.241 | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 176       | 89.8%   |
| 5.17    | 8         | 4.08%   |
| 5.19    | 4         | 2.04%   |
| 6.0     | 3         | 1.53%   |
| 6.1     | 2         | 1.02%   |
| 5.4     | 1         | 0.51%   |
| 5.18    | 1         | 0.51%   |
| 4.19    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 196       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 189       | 96.43%  |
| GNOME | 7         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 189       | 96.43%  |
| Wayland | 5         | 2.55%   |
| Tty     | 2         | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 175       | 89.29%  |
| GDM3    | 12        | 6.12%   |
| Unknown | 7         | 3.57%   |
| SLiM    | 1         | 0.51%   |
| SDDM    | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 83        | 42.35%  |
| de_DE | 25        | 12.76%  |
| fr_FR | 20        | 10.2%   |
| it_IT | 11        | 5.61%   |
| en_GB | 8         | 4.08%   |
| ru_RU | 6         | 3.06%   |
| es_ES | 5         | 2.55%   |
| pt_BR | 4         | 2.04%   |
| en_AU | 4         | 2.04%   |
| en_IN | 3         | 1.53%   |
| cs_CZ | 3         | 1.53%   |
| tr_TR | 2         | 1.02%   |
| nl_NL | 2         | 1.02%   |
| hu_HU | 2         | 1.02%   |
| en_CA | 2         | 1.02%   |
| ru_UA | 1         | 0.51%   |
| ro_RO | 1         | 0.51%   |
| pt_PT | 1         | 0.51%   |
| nl_BE | 1         | 0.51%   |
| ja_JP | 1         | 0.51%   |
| fr_BE | 1         | 0.51%   |
| es_VE | 1         | 0.51%   |
| es_MX | 1         | 0.51%   |
| es_CO | 1         | 0.51%   |
| es_CL | 1         | 0.51%   |
| en_IL | 1         | 0.51%   |
| en_IE | 1         | 0.51%   |
| el_GR | 1         | 0.51%   |
| de_CH | 1         | 0.51%   |
| C     | 1         | 0.51%   |
| bg_BG | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 112       | 56.57%  |
| BIOS | 86        | 43.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 176       | 89.8%   |
| Overlay | 8         | 4.08%   |
| Zfs     | 6         | 3.06%   |
| Btrfs   | 6         | 3.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 146       | 72.28%  |
| Unknown | 32        | 15.84%  |
| MBR     | 24        | 11.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 182       | 91.92%  |
| Yes       | 16        | 8.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 71.43%  |
| Yes       | 56        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 44        | 22.45%  |
| Hewlett-Packard     | 41        | 20.92%  |
| Dell                | 24        | 12.24%  |
| ASUSTek Computer    | 24        | 12.24%  |
| Acer                | 19        | 9.69%   |
| Google              | 6         | 3.06%   |
| Toshiba             | 4         | 2.04%   |
| Sony                | 4         | 2.04%   |
| HUAWEI              | 3         | 1.53%   |
| GPU Company         | 3         | 1.53%   |
| Samsung Electronics | 2         | 1.02%   |
| Notebook            | 2         | 1.02%   |
| HONOR               | 2         | 1.02%   |
| Apple               | 2         | 1.02%   |
| Unknown             | 2         | 1.02%   |
| Tactus              | 1         | 0.51%   |
| Standard            | 1         | 0.51%   |
| Schenker            | 1         | 0.51%   |
| Panasonic           | 1         | 0.51%   |
| Packard Bell        | 1         | 0.51%   |
| MSI                 | 1         | 0.51%   |
| Mediacom            | 1         | 0.51%   |
| HIGRADED            | 1         | 0.51%   |
| Fusion5             | 1         | 0.51%   |
| ECS                 | 1         | 0.51%   |
| Digma               | 1         | 0.51%   |
| Daten Tecnologia    | 1         | 0.51%   |
| Chuwi               | 1         | 0.51%   |
| AMI                 | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                                                      | 4         | 2.04%   |
| Unknown                                                                                  | 3         | 1.53%   |
| HP Pavilion Notebook                                                                     | 2         | 1.02%   |
| HP Pavilion 15                                                                           | 2         | 1.02%   |
| HP 255 G8 Notebook PC                                                                    | 2         | 1.02%   |
| GPU Company GWTN116-3                                                                    | 2         | 1.02%   |
| Dell Latitude E5450                                                                      | 2         | 1.02%   |
| Toshiba Satellite Pro R50-C                                                              | 1         | 0.51%   |
| Toshiba Satellite Pro R50-B                                                              | 1         | 0.51%   |
| Toshiba Satellite C650                                                                   | 1         | 0.51%   |
| Toshiba PT10F                                                                            | 1         | 0.51%   |
| Tactus GeoBook 140                                                                       | 1         | 0.51%   |
| Sony VPCS12V9E                                                                           | 1         | 0.51%   |
| Sony VPCEH25EN                                                                           | 1         | 0.51%   |
| Sony VPCEA3S1E                                                                           | 1         | 0.51%   |
| Sony SVE1512C6EB                                                                         | 1         | 0.51%   |
| Schenker WORK (Early 2021)                                                               | 1         | 0.51%   |
| Samsung 370E4K                                                                           | 1         | 0.51%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.51%   |
| Panasonic CF-D1DVA06F3                                                                   | 1         | 0.51%   |
| Packard Bell EasyNote MH45                                                               | 1         | 0.51%   |
| Notebook W65_67SZ                                                                        | 1         | 0.51%   |
| Notebook NJx0MU                                                                          | 1         | 0.51%   |
| MSI GF63 Thin 9RCX                                                                       | 1         | 0.51%   |
| Mediacom SmartBook 14 FullHD - SB14UC                                                    | 1         | 0.51%   |
| Lenovo V340-17IWL 81RG                                                                   | 1         | 0.51%   |
| Lenovo V330-15IKB 81AX                                                                   | 1         | 0.51%   |
| Lenovo V15 G2 ALC 82KD                                                                   | 1         | 0.51%   |
| Lenovo ThinkPad X230 23252S4                                                             | 1         | 0.51%   |
| Lenovo ThinkPad X220 42918F6                                                             | 1         | 0.51%   |
| Lenovo ThinkPad T61p 6457A24                                                             | 1         | 0.51%   |
| Lenovo ThinkPad T61 7659AB7                                                              | 1         | 0.51%   |
| Lenovo ThinkPad T470s 20HF004MMX                                                         | 1         | 0.51%   |
| Lenovo ThinkPad T460s 20FAS6JY00                                                         | 1         | 0.51%   |
| Lenovo ThinkPad T460s 20FAS30L01                                                         | 1         | 0.51%   |
| Lenovo ThinkPad T460s 20FAS0Q900                                                         | 1         | 0.51%   |
| Lenovo ThinkPad T440p 20AN0033RT                                                         | 1         | 0.51%   |
| Lenovo ThinkPad T430u 3353A11                                                            | 1         | 0.51%   |
| Lenovo ThinkPad T430 23501K1                                                             | 1         | 0.51%   |
| Lenovo ThinkPad T420 42361L0                                                             | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 27        | 13.78%  |
| Acer Aspire            | 15        | 7.65%   |
| HP Pavilion            | 12        | 6.12%   |
| Dell Latitude          | 11        | 5.61%   |
| HP EliteBook           | 8         | 4.08%   |
| Lenovo IdeaPad         | 7         | 3.57%   |
| Dell Inspiron          | 6         | 3.06%   |
| HP Laptop              | 4         | 2.04%   |
| ASUS VivoBook          | 4         | 2.04%   |
| Toshiba Satellite      | 3         | 1.53%   |
| HP Compaq              | 3         | 1.53%   |
| HP 255                 | 3         | 1.53%   |
| Dell Precision         | 3         | 1.53%   |
| Unknown                | 3         | 1.53%   |
| Lenovo ThinkBook       | 2         | 1.02%   |
| HP Stream              | 2         | 1.02%   |
| HP ProBook             | 2         | 1.02%   |
| HP 250                 | 2         | 1.02%   |
| GPU Company GWTN116-3  | 2         | 1.02%   |
| Dell XPS               | 2         | 1.02%   |
| ASUS ZenBook           | 2         | 1.02%   |
| ASUS ASUS              | 2         | 1.02%   |
| Toshiba PT10F          | 1         | 0.51%   |
| Tactus GeoBook         | 1         | 0.51%   |
| Sony VPCS12V9E         | 1         | 0.51%   |
| Sony VPCEH25EN         | 1         | 0.51%   |
| Sony VPCEA3S1E         | 1         | 0.51%   |
| Sony SVE1512C6EB       | 1         | 0.51%   |
| Schenker WORK          | 1         | 0.51%   |
| Samsung 370E4K         | 1         | 0.51%   |
| Samsung 350V5C         | 1         | 0.51%   |
| Panasonic CF-D1DVA06F3 | 1         | 0.51%   |
| Packard Bell EasyNote  | 1         | 0.51%   |
| Notebook W65           | 1         | 0.51%   |
| Notebook NJx0MU        | 1         | 0.51%   |
| MSI GF63               | 1         | 0.51%   |
| Mediacom SmartBook     | 1         | 0.51%   |
| Lenovo V340-17IWL      | 1         | 0.51%   |
| Lenovo V330-15IKB      | 1         | 0.51%   |
| Lenovo V15             | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 25        | 12.76%  |
| 2020 | 21        | 10.71%  |
| 2017 | 16        | 8.16%   |
| 2016 | 14        | 7.14%   |
| 2015 | 14        | 7.14%   |
| 2014 | 13        | 6.63%   |
| 2012 | 13        | 6.63%   |
| 2011 | 12        | 6.12%   |
| 2013 | 11        | 5.61%   |
| 2019 | 10        | 5.1%    |
| 2022 | 9         | 4.59%   |
| 2018 | 9         | 4.59%   |
| 2010 | 7         | 3.57%   |
| 2009 | 7         | 3.57%   |
| 2008 | 7         | 3.57%   |
| 2007 | 7         | 3.57%   |
| 2006 | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 196       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 177       | 90.31%  |
| Enabled  | 19        | 9.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 190       | 96.94%  |
| Yes  | 6         | 3.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 61        | 31.12%  |
| 4.01-8.0    | 60        | 30.61%  |
| 16.01-24.0  | 27        | 13.78%  |
| 8.01-16.0   | 24        | 12.24%  |
| 1.01-2.0    | 10        | 5.1%    |
| 32.01-64.0  | 7         | 3.57%   |
| 24.01-32.0  | 2         | 1.02%   |
| 2.01-3.0    | 2         | 1.02%   |
| 64.01-256.0 | 2         | 1.02%   |
| 0.51-1.0    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 93        | 46.04%  |
| 2.01-3.0  | 60        | 29.7%   |
| 0.51-1.0  | 17        | 8.42%   |
| 4.01-8.0  | 13        | 6.44%   |
| 3.01-4.0  | 13        | 6.44%   |
| 8.01-16.0 | 6         | 2.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 147       | 75%     |
| 2      | 44        | 22.45%  |
| 4      | 2         | 1.02%   |
| 3      | 2         | 1.02%   |
| 0      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 117       | 59.69%  |
| Yes       | 79        | 40.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 79.08%  |
| No        | 41        | 20.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 98.47%  |
| No        | 3         | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 79.08%  |
| No        | 41        | 20.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 30        | 15.23%  |
| Germany      | 29        | 14.72%  |
| France       | 24        | 12.18%  |
| Italy        | 14        | 7.11%   |
| Russia       | 9         | 4.57%   |
| UK           | 8         | 4.06%   |
| India        | 6         | 3.05%   |
| Netherlands  | 5         | 2.54%   |
| Mexico       | 5         | 2.54%   |
| Czechia      | 5         | 2.54%   |
| Brazil       | 5         | 2.54%   |
| Australia    | 4         | 2.03%   |
| Sweden       | 3         | 1.52%   |
| Spain        | 3         | 1.52%   |
| Poland       | 3         | 1.52%   |
| Malaysia     | 3         | 1.52%   |
| Iran         | 3         | 1.52%   |
| Belgium      | 3         | 1.52%   |
| Venezuela    | 2         | 1.02%   |
| Turkey       | 2         | 1.02%   |
| Switzerland  | 2         | 1.02%   |
| Israel       | 2         | 1.02%   |
| Indonesia    | 2         | 1.02%   |
| Hungary      | 2         | 1.02%   |
| Colombia     | 2         | 1.02%   |
| Belarus      | 2         | 1.02%   |
| Austria      | 2         | 1.02%   |
| Argentina    | 2         | 1.02%   |
| Vietnam      | 1         | 0.51%   |
| Ukraine      | 1         | 0.51%   |
| Slovenia     | 1         | 0.51%   |
| Sint Maarten | 1         | 0.51%   |
| Romania      | 1         | 0.51%   |
| Portugal     | 1         | 0.51%   |
| Madagascar   | 1         | 0.51%   |
| Japan        | 1         | 0.51%   |
| Ireland      | 1         | 0.51%   |
| Greece       | 1         | 0.51%   |
| Finland      | 1         | 0.51%   |
| Egypt        | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Paris         | 4         | 1.97%   |
| Melbourne     | 4         | 1.97%   |
| Munich        | 3         | 1.48%   |
| Milan         | 3         | 1.48%   |
| Kuala Lumpur  | 3         | 1.48%   |
| Warsaw        | 2         | 0.99%   |
| Uppsala       | 2         | 0.99%   |
| Stuttgart     | 2         | 0.99%   |
| St Petersburg | 2         | 0.99%   |
| Rochester     | 2         | 0.99%   |
| Oklahoma City | 2         | 0.99%   |
| Mumbai        | 2         | 0.99%   |
| Moscow        | 2         | 0.99%   |
| Mexico City   | 2         | 0.99%   |
| Leipzig       | 2         | 0.99%   |
| Indianapolis  | 2         | 0.99%   |
| Hamburg       | 2         | 0.99%   |
| Farmington    | 2         | 0.99%   |
| Brest         | 2         | 0.99%   |
| Berlin        | 2         | 0.99%   |
| Belfort       | 2         | 0.99%   |
| Auxerre       | 2         | 0.99%   |
| Ankara        | 2         | 0.99%   |
| Yokohama      | 1         | 0.49%   |
| Wittenborn    | 1         | 0.49%   |
| Wierden       | 1         | 0.49%   |
| Wetzlar       | 1         | 0.49%   |
| Washington    | 1         | 0.49%   |
| Villavicencio | 1         | 0.49%   |
| Villach       | 1         | 0.49%   |
| Vidin         | 1         | 0.49%   |
| Verona        | 1         | 0.49%   |
| Västerås    | 1         | 0.49%   |
| Ucel          | 1         | 0.49%   |
| Tustin        | 1         | 0.49%   |
| Treviso       | 1         | 0.49%   |
| Toulouse      | 1         | 0.49%   |
| Toamasina     | 1         | 0.49%   |
| Tehran        | 1         | 0.49%   |
| Surabaya      | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 35        | 39     | 15.02%  |
| WDC                         | 30        | 32     | 12.88%  |
| Unknown                     | 24        | 29     | 10.3%   |
| Seagate                     | 23        | 26     | 9.87%   |
| SK hynix                    | 14        | 16     | 6.01%   |
| SanDisk                     | 11        | 11     | 4.72%   |
| Kingston                    | 11        | 13     | 4.72%   |
| Intel                       | 8         | 8      | 3.43%   |
| Hitachi                     | 8         | 8      | 3.43%   |
| Toshiba                     | 6         | 6      | 2.58%   |
| Crucial                     | 6         | 6      | 2.58%   |
| HGST                        | 5         | 6      | 2.15%   |
| A-DATA Technology           | 5         | 8      | 2.15%   |
| PNY                         | 4         | 4      | 1.72%   |
| Phison                      | 4         | 4      | 1.72%   |
| Micron Technology           | 4         | 4      | 1.72%   |
| China                       | 4         | 5      | 1.72%   |
| Transcend                   | 3         | 4      | 1.29%   |
| Unknown                     | 3         | 3      | 1.29%   |
| TO Exter                    | 2         | 2      | 0.86%   |
| Silicon Motion              | 2         | 2      | 0.86%   |
| LITEON                      | 2         | 2      | 0.86%   |
| Apacer                      | 2         | 2      | 0.86%   |
| USB3.0                      | 1         | 2      | 0.43%   |
| SSSTC                       | 1         | 1      | 0.43%   |
| SSD0240S                    | 1         | 1      | 0.43%   |
| Patriot                     | 1         | 1      | 0.43%   |
| Netac                       | 1         | 1      | 0.43%   |
| LITEONIT                    | 1         | 1      | 0.43%   |
| Lenovo                      | 1         | 1      | 0.43%   |
| Kingston Technology Company | 1         | 1      | 0.43%   |
| Kimtigo                     | 1         | 1      | 0.43%   |
| JMicron Technology          | 1         | 1      | 0.43%   |
| Intenso                     | 1         | 1      | 0.43%   |
| INNOVATION IT               | 1         | 1      | 0.43%   |
| Fujitsu                     | 1         | 1      | 0.43%   |
| FORESEE                     | 1         | 1      | 0.43%   |
| EVM                         | 1         | 1      | 0.43%   |
| Apple                       | 1         | 2      | 0.43%   |
| addlink                     | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 3         | 1.25%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 1.25%   |
| Samsung SSD 860 EVO 500GB              | 3         | 1.25%   |
| Samsung SSD 850 EVO 500GB              | 3         | 1.25%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.25%   |
| HGST HTS541010A9E680 1TB               | 3         | 1.25%   |
| Unknown                                | 3         | 1.25%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 0.83%   |
| WDC PC SN530 SDBPNPZ-512G-1036 512GB   | 2         | 0.83%   |
| Unknown SD/MMC/MS PRO 16GB             | 2         | 0.83%   |
| Unknown SA08G  8GB                     | 2         | 0.83%   |
| Unknown MMC64G  64GB                   | 2         | 0.83%   |
| TO Exter nal USB 3.0 240GB             | 2         | 0.83%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.83%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.83%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.83%   |
| Seagate ST1000LM014-1EJ164 1TB         | 2         | 0.83%   |
| SanDisk DF4032  32GB                   | 2         | 0.83%   |
| Samsung SSD 980 500GB                  | 2         | 0.83%   |
| Samsung MZALQ512HALU-000L2 512GB       | 2         | 0.83%   |
| PNY CS900 120GB SSD                    | 2         | 0.83%   |
| Phison 311CD0512GB                     | 2         | 0.83%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.83%   |
| Intel SSDPEKNU512GZ 512GB              | 2         | 0.83%   |
| WDC WDS960G2G0C-00AJM0 960GB           | 1         | 0.42%   |
| WDC WDS500G2B0C 500GB                  | 1         | 0.42%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.42%   |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 1         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.42%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.42%   |
| WDC WD7500BPVT-75HXZT3 752GB           | 1         | 0.42%   |
| WDC WD7500BPVT-60HXZT3 752GB           | 1         | 0.42%   |
| WDC WD5000LPVX-08V0TT5 500GB           | 1         | 0.42%   |
| WDC WD5000LPCX-21VHAT0 500GB           | 1         | 0.42%   |
| WDC WD5000LPCX-00VHAT0 500GB           | 1         | 0.42%   |
| WDC WD5000BPKX-22HPJT0 500GB           | 1         | 0.42%   |
| WDC WD5000BEVT-22ZAT0 500GB            | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 23        | 26     | 34.85%  |
| WDC                | 20        | 21     | 30.3%   |
| Hitachi            | 8         | 8      | 12.12%  |
| Toshiba            | 5         | 5      | 7.58%   |
| HGST               | 5         | 6      | 7.58%   |
| Unknown            | 2         | 3      | 3.03%   |
| USB3.0             | 1         | 2      | 1.52%   |
| JMicron Technology | 1         | 1      | 1.52%   |
| Fujitsu            | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 20%     |
| Kingston            | 10        | 11     | 12.5%   |
| SanDisk             | 6         | 6      | 7.5%    |
| Crucial             | 5         | 5      | 6.25%   |
| A-DATA Technology   | 5         | 8      | 6.25%   |
| WDC                 | 4         | 4      | 5%      |
| PNY                 | 4         | 4      | 5%      |
| China               | 4         | 5      | 5%      |
| Transcend           | 3         | 3      | 3.75%   |
| TO Exter            | 2         | 2      | 2.5%    |
| SK hynix            | 2         | 2      | 2.5%    |
| Micron Technology   | 2         | 2      | 2.5%    |
| LITEON              | 2         | 2      | 2.5%    |
| Intel               | 2         | 2      | 2.5%    |
| Apacer              | 2         | 2      | 2.5%    |
| SSSTC               | 1         | 1      | 1.25%   |
| Patriot             | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| LITEONIT            | 1         | 1      | 1.25%   |
| Kimtigo             | 1         | 1      | 1.25%   |
| Intenso             | 1         | 1      | 1.25%   |
| INNOVATION IT       | 1         | 1      | 1.25%   |
| FORESEE             | 1         | 1      | 1.25%   |
| EVM                 | 1         | 1      | 1.25%   |
| addlink             | 1         | 1      | 1.25%   |
| Unknown             | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 74        | 88     | 32.74%  |
| NVMe    | 62        | 66     | 27.43%  |
| HDD     | 62        | 73     | 27.43%  |
| MMC     | 27        | 31     | 11.95%  |
| Unknown | 1         | 1      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 126       | 151    | 56.25%  |
| NVMe | 62        | 66     | 27.68%  |
| MMC  | 27        | 31     | 12.05%  |
| SAS  | 9         | 11     | 4.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 118    | 71.22%  |
| 0.51-1.0   | 36        | 39     | 25.9%   |
| 1.01-2.0   | 3         | 3      | 2.16%   |
| 3.01-4.0   | 1         | 1      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 65        | 32.66%  |
| 251-500        | 53        | 26.63%  |
| 501-1000       | 27        | 13.57%  |
| 51-100         | 20        | 10.05%  |
| 1-20           | 14        | 7.04%   |
| 21-50          | 10        | 5.03%   |
| 1001-2000      | 7         | 3.52%   |
| More than 3000 | 1         | 0.5%    |
| 2001-3000      | 1         | 0.5%    |
| Unknown        | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 80        | 40%     |
| 21-50     | 47        | 23.5%   |
| 51-100    | 30        | 15%     |
| 101-250   | 24        | 12%     |
| 251-500   | 9         | 4.5%    |
| 501-1000  | 7         | 3.5%    |
| 1001-2000 | 2         | 1%      |
| Unknown   | 1         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 8%      |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 4%      |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 4%      |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 4%      |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 4%      |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 4%      |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 4%      |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 4%      |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 4%      |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 4%      |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 4%      |
| JMicron Technology Generic 200GB                 | 1         | 1      | 4%      |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 4%      |
| Hitachi HTS725050A9A364 500GB                    | 1         | 1      | 4%      |
| Hitachi HTS545032A7E380 320GB                    | 1         | 1      | 4%      |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 4%      |
| Hitachi HTS541080G9SA00 80GB                     | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 4%      |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 4%      |
| Fujitsu MHW2060BH 64GB                           | 1         | 1      | 4%      |
| Unknown                                          | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 32%     |
| Hitachi             | 4         | 4      | 16%     |
| WDC                 | 2         | 2      | 8%      |
| HGST                | 2         | 2      | 8%      |
| SSSTC               | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| Kingston            | 1         | 2      | 4%      |
| JMicron Technology  | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |
| Unknown             | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 8         | 8      | 47.06%  |
| Hitachi            | 4         | 4      | 23.53%  |
| HGST               | 2         | 2      | 11.76%  |
| WDC                | 1         | 1      | 5.88%   |
| JMicron Technology | 1         | 1      | 5.88%   |
| Fujitsu            | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 66.67%  |
| SSD  | 8         | 9      | 33.33%  |

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
| Works    | 107       | 122    | 50.47%  |
| Detected | 81        | 111    | 38.21%  |
| Malfunc  | 24        | 26     | 11.32%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 133       | 61.86%  |
| AMD                          | 28        | 13.02%  |
| Samsung Electronics          | 19        | 8.84%   |
| SK hynix                     | 12        | 5.58%   |
| SanDisk                      | 9         | 4.19%   |
| Silicon Motion               | 3         | 1.4%    |
| Phison Electronics           | 3         | 1.4%    |
| Kingston Technology Company  | 3         | 1.4%    |
| Toshiba America Info Systems | 1         | 0.47%   |
| Micron/Crucial Technology    | 1         | 0.47%   |
| Micron Technology            | 1         | 0.47%   |
| Lenovo                       | 1         | 0.47%   |
| Apple                        | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 11.64%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 6.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 5.6%    |
| Samsung NVMe SSD Controller 980                                                  | 11        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 3.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 8         | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 3.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 3.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 2.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 2.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.16%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.29%   |
| Intel SSD 660P Series                                                            | 3         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.29%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.29%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.86%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.86%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.86%   |
| Intel Non-Volatile memory controller                                             | 2         | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 142       | 62.01%  |
| NVMe | 61        | 26.64%  |
| RAID | 13        | 5.68%   |
| IDE  | 13        | 5.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 157       | 80.1%   |
| AMD    | 39        | 19.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 2.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 5         | 2.55%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 2.04%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 2.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 1.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.53%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 1.53%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 1.53%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 1.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.53%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.53%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 1.53%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 1.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.02%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.02%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.02%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 2         | 1.02%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.02%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz        | 2         | 1.02%   |
| Intel Celeron 3205U @ 1.50GHz               | 2         | 1.02%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 2         | 1.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.02%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 1.02%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.02%   |
| AMD A6-7310 APU with AMD Radeon R4 Graphics | 2         | 1.02%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 21.43%  |
| Intel Celeron           | 30        | 15.31%  |
| Intel Core i7           | 23        | 11.73%  |
| Other                   | 18        | 9.18%   |
| Intel Core i3           | 16        | 8.16%   |
| Intel Core 2 Duo        | 8         | 4.08%   |
| AMD Ryzen 5             | 8         | 4.08%   |
| AMD Ryzen 7             | 6         | 3.06%   |
| Intel Atom              | 5         | 2.55%   |
| AMD A6                  | 5         | 2.55%   |
| Intel Pentium           | 3         | 1.53%   |
| Intel Core 2            | 3         | 1.53%   |
| AMD Ryzen 5 PRO         | 3         | 1.53%   |
| AMD A8                  | 3         | 1.53%   |
| Intel Pentium Dual-Core | 2         | 1.02%   |
| Intel Pentium Dual      | 2         | 1.02%   |
| Intel Genuine           | 2         | 1.02%   |
| AMD E2                  | 2         | 1.02%   |
| AMD E1                  | 2         | 1.02%   |
| AMD A4                  | 2         | 1.02%   |
| AMD A10                 | 2         | 1.02%   |
| Intel Xeon              | 1         | 0.51%   |
| Intel Pentium Silver    | 1         | 0.51%   |
| Intel Core m3           | 1         | 0.51%   |
| Intel Core 2 Extreme    | 1         | 0.51%   |
| AMD Ryzen 9             | 1         | 0.51%   |
| AMD Ryzen 7 PRO         | 1         | 0.51%   |
| AMD Ryzen 3             | 1         | 0.51%   |
| AMD FX                  | 1         | 0.51%   |
| AMD Athlon              | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 119       | 60.71%  |
| 4      | 50        | 25.51%  |
| 6      | 14        | 7.14%   |
| 8      | 10        | 5.1%    |
| 1      | 2         | 1.02%   |
| 12     | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 196       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 127       | 64.8%   |
| 1      | 69        | 35.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 30.81%  |
| 0x806c1    | 13        | 6.57%   |
| 0x406e3    | 8         | 4.04%   |
| 0x306d4    | 7         | 3.54%   |
| 0x08608103 | 7         | 3.54%   |
| 0x306a9    | 6         | 3.03%   |
| 0x806ec    | 5         | 2.53%   |
| 0x30678    | 5         | 2.53%   |
| 0xa0652    | 4         | 2.02%   |
| 0x406c3    | 4         | 2.02%   |
| 0x206a7    | 4         | 2.02%   |
| 0x806ea    | 3         | 1.52%   |
| 0x806e9    | 3         | 1.52%   |
| 0x706a8    | 3         | 1.52%   |
| 0x6fd      | 3         | 1.52%   |
| 0x6fb      | 3         | 1.52%   |
| 0x506c9    | 3         | 1.52%   |
| 0x406c4    | 3         | 1.52%   |
| 0x40651    | 3         | 1.52%   |
| 0x20655    | 3         | 1.52%   |
| 0x1067a    | 3         | 1.52%   |
| 0x906ea    | 2         | 1.01%   |
| 0x806d1    | 2         | 1.01%   |
| 0x6f6      | 2         | 1.01%   |
| 0x506ca    | 2         | 1.01%   |
| 0x20652    | 2         | 1.01%   |
| 0x0a50000c | 2         | 1.01%   |
| 0x08600104 | 2         | 1.01%   |
| 0x08108109 | 2         | 1.01%   |
| 0x07030105 | 2         | 1.01%   |
| 0x06006705 | 2         | 1.01%   |
| 0x05000119 | 2         | 1.01%   |
| 0x906e9    | 1         | 0.51%   |
| 0x906c0    | 1         | 0.51%   |
| 0x906a3    | 1         | 0.51%   |
| 0x706e5    | 1         | 0.51%   |
| 0x706a1    | 1         | 0.51%   |
| 0x6f2      | 1         | 0.51%   |
| 0x506e3    | 1         | 0.51%   |
| 0x306c3    | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 11.73%  |
| Silvermont       | 16        | 8.16%   |
| TigerLake        | 14        | 7.14%   |
| Skylake          | 14        | 7.14%   |
| SandyBridge      | 12        | 6.12%   |
| IvyBridge        | 11        | 5.61%   |
| Core             | 10        | 5.1%    |
| Unknown          | 10        | 5.1%    |
| Broadwell        | 9         | 4.59%   |
| Westmere         | 8         | 4.08%   |
| Penryn           | 8         | 4.08%   |
| Haswell          | 8         | 4.08%   |
| Goldmont         | 6         | 3.06%   |
| Puma             | 5         | 2.55%   |
| Goldmont plus    | 5         | 2.55%   |
| Excavator        | 5         | 2.55%   |
| Zen 3            | 4         | 2.04%   |
| Zen 2            | 4         | 2.04%   |
| Icelake          | 4         | 2.04%   |
| CometLake        | 4         | 2.04%   |
| Zen+             | 3         | 1.53%   |
| Bobcat           | 3         | 1.53%   |
| Piledriver       | 2         | 1.02%   |
| K10 Llano        | 2         | 1.02%   |
| Bonnell          | 2         | 1.02%   |
| Tremont          | 1         | 0.51%   |
| Steamroller      | 1         | 0.51%   |
| Nehalem          | 1         | 0.51%   |
| Alderlake Hybrid | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 141       | 61.3%   |
| AMD    | 47        | 20.43%  |
| Nvidia | 42        | 18.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 4.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 4.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 4.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.58%   |
| AMD Lucienne                                                                             | 8         | 3.33%   |
| Intel HD Graphics 620                                                                    | 7         | 2.92%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.92%   |
| Intel HD Graphics 500                                                                    | 6         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.08%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 1.67%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.67%   |
| AMD Renoir                                                                               | 4         | 1.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.67%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.25%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.25%   |
| Nvidia TU117M                                                                            | 2         | 0.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.83%   |
| Intel HD Graphics                                                                        | 2         | 0.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.83%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.83%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.83%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.83%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 110       | 56.12%  |
| 1 x AMD        | 34        | 17.35%  |
| Intel + Nvidia | 26        | 13.27%  |
| 1 x Nvidia     | 12        | 6.12%   |
| 2 x AMD        | 5         | 2.55%   |
| Intel + AMD    | 4         | 2.04%   |
| AMD + Nvidia   | 4         | 2.04%   |
| Other          | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 170       | 86.73%  |
| Proprietary | 21        | 10.71%  |
| Unknown     | 5         | 2.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 71.21%  |
| 0.01-0.5   | 29        | 14.65%  |
| 0.51-1.0   | 10        | 5.05%   |
| 1.01-2.0   | 9         | 4.55%   |
| 3.01-4.0   | 8         | 4.04%   |
| 7.01-8.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 24.77%  |
| LG Display              | 32        | 14.95%  |
| BOE                     | 30        | 14.02%  |
| Chimei Innolux          | 24        | 11.21%  |
| Samsung Electronics     | 19        | 8.88%   |
| Chi Mei Optoelectronics | 6         | 2.8%    |
| PANDA                   | 5         | 2.34%   |
| Goldstar                | 5         | 2.34%   |
| Dell                    | 5         | 2.34%   |
| Lenovo                  | 4         | 1.87%   |
| LG Philips              | 3         | 1.4%    |
| InfoVision              | 3         | 1.4%    |
| Vizio                   | 2         | 0.93%   |
| Sony                    | 2         | 0.93%   |
| Philips                 | 2         | 0.93%   |
| KDC                     | 2         | 0.93%   |
| Iiyama                  | 2         | 0.93%   |
| Apple                   | 2         | 0.93%   |
| ViewSonic               | 1         | 0.47%   |
| Toshiba                 | 1         | 0.47%   |
| Sharp                   | 1         | 0.47%   |
| Sceptre Tech            | 1         | 0.47%   |
| SAC                     | 1         | 0.47%   |
| Quanta Display          | 1         | 0.47%   |
| Panasonic               | 1         | 0.47%   |
| HannStar                | 1         | 0.47%   |
| CSO                     | 1         | 0.47%   |
| CPT                     | 1         | 0.47%   |
| BenQ                    | 1         | 0.47%   |
| AOC                     | 1         | 0.47%   |
| Acer                    | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 2         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.93%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.93%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.93%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.93%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.93%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.93%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.93%   |
| Vizio E421VO VIZ0070 1920x1080 930x523mm 42.0-inch                       | 1         | 0.47%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.47%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.47%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.47%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.47%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch     | 1         | 0.47%   |
| Samsung Electronics SMC23A550U SAM07F3 1920x1080 510x287mm 23.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4A52 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 86        | 41.95%  |
| 1366x768 (WXGA)    | 62        | 30.24%  |
| 1600x900 (HD+)     | 19        | 9.27%   |
| 1280x800 (WXGA)    | 9         | 4.39%   |
| 3840x2160 (4K)     | 6         | 2.93%   |
| 1920x1200 (WUXGA)  | 5         | 2.44%   |
| 1440x900 (WXGA+)   | 5         | 2.44%   |
| 2560x1440 (QHD)    | 3         | 1.46%   |
| 1024x600           | 2         | 0.98%   |
| 3440x1440          | 1         | 0.49%   |
| 2880x1800          | 1         | 0.49%   |
| 2160x1440          | 1         | 0.49%   |
| 1920x515           | 1         | 0.49%   |
| 1680x1050 (WSXGA+) | 1         | 0.49%   |
| 1366x912           | 1         | 0.49%   |
| 1360x768           | 1         | 0.49%   |
| 1280x1024 (SXGA)   | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 82        | 38.32%  |
| 14      | 36        | 16.82%  |
| 13      | 32        | 14.95%  |
| 17      | 18        | 8.41%   |
| 27      | 7         | 3.27%   |
| 23      | 6         | 2.8%    |
| 11      | 6         | 2.8%    |
| 12      | 5         | 2.34%   |
| 21      | 4         | 1.87%   |
| Unknown | 4         | 1.87%   |
| 26      | 2         | 0.93%   |
| 24      | 2         | 0.93%   |
| 18      | 2         | 0.93%   |
| 16      | 2         | 0.93%   |
| 10      | 2         | 0.93%   |
| 42      | 1         | 0.47%   |
| 34      | 1         | 0.47%   |
| 31      | 1         | 0.47%   |
| 20      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 140       | 65.73%  |
| 201-300     | 24        | 11.27%  |
| 351-400     | 19        | 8.92%   |
| 501-600     | 16        | 7.51%   |
| 401-500     | 7         | 3.29%   |
| Unknown     | 4         | 1.88%   |
| 701-800     | 1         | 0.47%   |
| 601-700     | 1         | 0.47%   |
| 901-1000    | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 166       | 85.57%  |
| 16/10   | 22        | 11.34%  |
| 3/2     | 2         | 1.03%   |
| 4/3     | 1         | 0.52%   |
| 3.73    | 1         | 0.52%   |
| 21/9    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 37.85%  |
| 81-90          | 59        | 27.57%  |
| 121-130        | 13        | 6.07%   |
| 71-80          | 10        | 4.67%   |
| 201-250        | 10        | 4.67%   |
| 301-350        | 8         | 3.74%   |
| 51-60          | 6         | 2.8%    |
| 131-140        | 5         | 2.34%   |
| 61-70          | 4         | 1.87%   |
| Unknown        | 4         | 1.87%   |
| 151-200        | 3         | 1.4%    |
| 351-500        | 2         | 0.93%   |
| 41-50          | 2         | 0.93%   |
| 251-300        | 2         | 0.93%   |
| 91-100         | 2         | 0.93%   |
| 141-150        | 1         | 0.47%   |
| 111-120        | 1         | 0.47%   |
| 501-1000       | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 97        | 45.75%  |
| 101-120       | 69        | 32.55%  |
| 51-100        | 33        | 15.57%  |
| 161-240       | 6         | 2.83%   |
| Unknown       | 4         | 1.89%   |
| More than 240 | 3         | 1.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 164       | 83.67%  |
| 2     | 25        | 12.76%  |
| 0     | 5         | 2.55%   |
| 3     | 2         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 101       | 33.55%  |
| Intel                             | 101       | 33.55%  |
| Qualcomm Atheros                  | 40        | 13.29%  |
| Broadcom                          | 21        | 6.98%   |
| Qualcomm                          | 4         | 1.33%   |
| MediaTek                          | 4         | 1.33%   |
| Marvell Technology Group          | 3         | 1%      |
| Dell                              | 3         | 1%      |
| TP-Link                           | 2         | 0.66%   |
| Sierra Wireless                   | 2         | 0.66%   |
| Samsung Electronics               | 2         | 0.66%   |
| Huawei Technologies               | 2         | 0.66%   |
| Hewlett-Packard                   | 2         | 0.66%   |
| Broadcom Limited                  | 2         | 0.66%   |
| Xiaomi                            | 1         | 0.33%   |
| Ralink Technology                 | 1         | 0.33%   |
| Ralink                            | 1         | 0.33%   |
| Qualcomm Atheros Communications   | 1         | 0.33%   |
| OPPO                              | 1         | 0.33%   |
| Microchip Technology              | 1         | 0.33%   |
| LG Electronics                    | 1         | 0.33%   |
| Ericsson Business Mobile Networks | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| BUFFALO                           | 1         | 0.33%   |
| Attansic Technology               | 1         | 0.33%   |
| Apple                             | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 16.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 5.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.68%   |
| Intel Wireless 8260                                               | 10        | 2.68%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 2.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.88%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.61%   |
| Intel Wireless 7260                                               | 6         | 1.61%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.34%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.34%   |
| Intel Wireless 7265                                               | 5         | 1.34%   |
| Intel Wireless 3165                                               | 5         | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 1.07%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 4         | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.8%    |
| Realtek 802.11n WLAN Adapter                                      | 3         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.8%    |
| Intel Wireless 3160                                               | 3         | 0.8%    |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.8%    |
| Sierra Wireless EM7455                                            | 2         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 48.06%  |
| Realtek Semiconductor           | 38        | 18.45%  |
| Qualcomm Atheros                | 37        | 17.96%  |
| Broadcom                        | 13        | 6.31%   |
| Qualcomm                        | 4         | 1.94%   |
| MediaTek                        | 4         | 1.94%   |
| Sierra Wireless                 | 2         | 0.97%   |
| Dell                            | 2         | 0.97%   |
| TP-Link                         | 1         | 0.49%   |
| Ralink Technology               | 1         | 0.49%   |
| Ralink                          | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| D-Link                          | 1         | 0.49%   |
| BUFFALO                         | 1         | 0.49%   |
| Broadcom Limited                | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 4.78%   |
| Intel Wireless 8260                                                     | 10        | 4.78%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 4.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.87%   |
| Intel Wireless 7260                                                     | 6         | 2.87%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.39%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.39%   |
| Intel Wireless 7265                                                     | 5         | 2.39%   |
| Intel Wireless 3165                                                     | 5         | 2.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 2.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 1.91%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 1.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.44%   |
| Realtek 802.11n WLAN Adapter                                            | 3         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.44%   |
| Intel Wireless 3160                                                     | 3         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.44%   |
| Sierra Wireless EM7455                                                  | 2         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.96%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 87        | 53.7%   |
| Intel                    | 41        | 25.31%  |
| Broadcom                 | 9         | 5.56%   |
| Qualcomm Atheros         | 8         | 4.94%   |
| Marvell Technology Group | 3         | 1.85%   |
| Samsung Electronics      | 2         | 1.23%   |
| Huawei Technologies      | 2         | 1.23%   |
| Hewlett-Packard          | 2         | 1.23%   |
| Xiaomi                   | 1         | 0.62%   |
| TP-Link                  | 1         | 0.62%   |
| OPPO                     | 1         | 0.62%   |
| Microchip Technology     | 1         | 0.62%   |
| LG Electronics           | 1         | 0.62%   |
| Broadcom Limited         | 1         | 0.62%   |
| Attansic Technology      | 1         | 0.62%   |
| Apple                    | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 61        | 37.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 13.58%  |
| Intel Ethernet Connection I219-LM                                              | 7         | 4.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 1.85%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.23%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.23%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 1.23%   |
| Huawei MLA-L11                                                                 | 2         | 1.23%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.62%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.62%   |
| OPPO CPH1923                                                                   | 1         | 0.62%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.62%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.62%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.62%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.62%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.62%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.62%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 0.62%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.62%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.62%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 193       | 55.14%  |
| Ethernet | 155       | 44.29%  |
| Modem    | 2         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 82.76%  |
| Ethernet | 35        | 17.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 146       | 74.49%  |
| 1     | 43        | 21.94%  |
| 0     | 7         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 129       | 65.15%  |
| Yes  | 69        | 34.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 47.1%   |
| Realtek Semiconductor           | 19        | 12.26%  |
| Broadcom                        | 12        | 7.74%   |
| Foxconn / Hon Hai               | 10        | 6.45%   |
| Qualcomm Atheros Communications | 9         | 5.81%   |
| Lite-On Technology              | 8         | 5.16%   |
| IMC Networks                    | 6         | 3.87%   |
| Realtek                         | 3         | 1.94%   |
| Hewlett-Packard                 | 3         | 1.94%   |
| Dell                            | 2         | 1.29%   |
| ASUSTek Computer                | 2         | 1.29%   |
| USI                             | 1         | 0.65%   |
| Toshiba                         | 1         | 0.65%   |
| Ralink                          | 1         | 0.65%   |
| Foxconn International           | 1         | 0.65%   |
| Chicony Electronics             | 1         | 0.65%   |
| Cambridge Silicon Radio         | 1         | 0.65%   |
| Apple                           | 1         | 0.65%   |
| Alps Electric                   | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 35        | 22.58%  |
| Intel AX201 Bluetooth                                                               | 15        | 9.68%   |
| Realtek Bluetooth Radio                                                             | 13        | 8.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 3.87%   |
| Intel AX200 Bluetooth                                                               | 6         | 3.87%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 3.87%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.23%   |
| Intel AX210 Bluetooth                                                               | 5         | 3.23%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.29%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.29%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.29%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.29%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.29%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.29%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.29%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.29%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 1.29%   |
| USI Bluetooth Device                                                                | 1         | 0.65%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.65%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.65%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.65%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.65%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.65%   |
| Intel Bluetooth Device                                                              | 1         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 154       | 70%     |
| AMD                    | 41        | 18.64%  |
| Nvidia                 | 15        | 6.82%   |
| Texas Instruments      | 2         | 0.91%   |
| JMTek                  | 2         | 0.91%   |
| Generalplus Technology | 2         | 0.91%   |
| C-Media Electronics    | 2         | 0.91%   |
| Tenx Technology        | 1         | 0.45%   |
| ASUSTek Computer       | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 8.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 6.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 5.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 4.78%   |
| AMD FCH Azalia Controller                                                                         | 13        | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 2.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 2.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.84%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.1%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.1%    |
| AMD High Definition Audio Controller                                                              | 3         | 1.1%    |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.74%   |
| Nvidia Audio device                                                                               | 2         | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.74%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.74%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.74%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 50        | 29.24%  |
| SK hynix                   | 29        | 16.96%  |
| Unknown                    | 24        | 14.04%  |
| Micron Technology          | 21        | 12.28%  |
| Kingston                   | 16        | 9.36%   |
| Crucial                    | 9         | 5.26%   |
| Unknown (ABCD)             | 5         | 2.92%   |
| Ramaxel Technology         | 3         | 1.75%   |
| G.Skill                    | 2         | 1.17%   |
| Elpida                     | 2         | 1.17%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.58%   |
| Transcend                  | 1         | 0.58%   |
| Smart                      | 1         | 0.58%   |
| Qimonda                    | 1         | 0.58%   |
| Nanya Technology           | 1         | 0.58%   |
| Foxline                    | 1         | 0.58%   |
| fef5                       | 1         | 0.58%   |
| Essencore                  | 1         | 0.58%   |
| Daten Tecnologia           | 1         | 0.58%   |
| A-DATA Technology          | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s            | 5         | 2.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 4         | 2.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                       | 4         | 2.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s                 | 4         | 2.27%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                                   | 3         | 1.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 3         | 1.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 1.7%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                                 | 2         | 1.14%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                                | 2         | 1.14%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                                | 2         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.14%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                      | 2         | 1.14%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.14%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.14%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                                 | 2         | 1.14%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                       | 2         | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                       | 2         | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.14%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                       | 2         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                 | 2         | 1.14%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                                  | 2         | 1.14%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                        | 2         | 1.14%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                                          | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3                                          | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                       | 1         | 0.57%   |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                            | 1         | 0.57%   |
| Unknown RAM 202020202020202020202020202020202020 4096MB SODIMM DDR2 800MT/s | 1         | 0.57%   |
| Unknown (7F7F7F7F7F7F6B00) RAM 8D7T3MN8-NATP 2GB SODIMM DDR 667MT/s         | 1         | 0.57%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.57%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 41.1%   |
| DDR3    | 50        | 34.25%  |
| LPDDR4  | 16        | 10.96%  |
| DDR2    | 10        | 6.85%   |
| LPDDR3  | 4         | 2.74%   |
| Unknown | 2         | 1.37%   |
| SDRAM   | 1         | 0.68%   |
| LPDDR5  | 1         | 0.68%   |
| DDR5    | 1         | 0.68%   |
| DDR     | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 126       | 84.56%  |
| Row Of Chips | 18        | 12.08%  |
| Chip         | 3         | 2.01%   |
| Unknown      | 2         | 1.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 33.12%  |
| 4096  | 52        | 33.12%  |
| 2048  | 27        | 17.2%   |
| 16384 | 17        | 10.83%  |
| 1024  | 5         | 3.18%   |
| 32768 | 2         | 1.27%   |
| 1536  | 1         | 0.64%   |
| 512   | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 37        | 24.18%  |
| 3200    | 34        | 22.22%  |
| 2667    | 18        | 11.76%  |
| 2400    | 12        | 7.84%   |
| 2133    | 11        | 7.19%   |
| 667     | 10        | 6.54%   |
| 4267    | 5         | 3.27%   |
| 1334    | 5         | 3.27%   |
| 1333    | 4         | 2.61%   |
| 3266    | 2         | 1.31%   |
| 1067    | 2         | 1.31%   |
| Unknown | 2         | 1.31%   |
| 6400    | 1         | 0.65%   |
| 4800    | 1         | 0.65%   |
| 4266    | 1         | 0.65%   |
| 4199    | 1         | 0.65%   |
| 3733    | 1         | 0.65%   |
| 2134    | 1         | 0.65%   |
| 1867    | 1         | 0.65%   |
| 1776    | 1         | 0.65%   |
| 1066    | 1         | 0.65%   |
| 800     | 1         | 0.65%   |
| 533     | 1         | 0.65%   |

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
| Chicony Electronics                    | 52        | 28.11%  |
| Realtek Semiconductor                  | 15        | 8.11%   |
| Quanta                                 | 15        | 8.11%   |
| IMC Networks                           | 14        | 7.57%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 7.57%   |
| Suyin                                  | 13        | 7.03%   |
| Sunplus Innovation Technology          | 11        | 5.95%   |
| Microdia                               | 11        | 5.95%   |
| Acer                                   | 6         | 3.24%   |
| Luxvisions Innotech Limited            | 3         | 1.62%   |
| Lite-On Technology                     | 3         | 1.62%   |
| Alcor Micro                            | 3         | 1.62%   |
| Z-Star Microelectronics                | 2         | 1.08%   |
| Syntek                                 | 2         | 1.08%   |
| Silicon Motion                         | 2         | 1.08%   |
| Ricoh                                  | 2         | 1.08%   |
| Logitech                               | 2         | 1.08%   |
| icSpring                               | 2         | 1.08%   |
| Xiongmai                               | 1         | 0.54%   |
| USB Camera CS                          | 1         | 0.54%   |
| SunplusIT                              | 1         | 0.54%   |
| Sonix Technology                       | 1         | 0.54%   |
| Primax Electronics                     | 1         | 0.54%   |
| OYT Tech                               | 1         | 0.54%   |
| OmniVision Technologies                | 1         | 0.54%   |
| MacroSilicon                           | 1         | 0.54%   |
| Lenovo                                 | 1         | 0.54%   |
| Importek                               | 1         | 0.54%   |
| DLEQNA19IFK6G2                         | 1         | 0.54%   |
| Bison Electronics                      | 1         | 0.54%   |
| Alpha Imaging Technology               | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 17        | 9.19%   |
| Chicony HD WebCam                                   | 5         | 2.7%    |
| Sunplus Integrated_Webcam_HD                        | 4         | 2.16%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 2.16%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 1.62%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.62%   |
| Quanta HD User Facing                               | 3         | 1.62%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.62%   |
| IMC Networks Integrated Camera                      | 3         | 1.62%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.62%   |
| Chicony EasyCamera                                  | 3         | 1.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.62%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 1.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 1.08%   |
| Sunplus Integrated_Webcam_FHD                       | 2         | 1.08%   |
| Realtek USB Camera                                  | 2         | 1.08%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.08%   |
| Realtek HP Truevision HD                            | 2         | 1.08%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 1.08%   |
| Quanta HP Webcam                                    | 2         | 1.08%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.08%   |
| Microdia Lenovo EasyCamera                          | 2         | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.08%   |
| IMC Networks ov9734_azurewave_camera                | 2         | 1.08%   |
| IMC Networks HD Camera                              | 2         | 1.08%   |
| icSpring camera                                     | 2         | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.08%   |
| Chicony USB2.0 Camera                               | 2         | 1.08%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 1.08%   |
| Chicony HP Truevision HD                            | 2         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.08%   |
| Alcor Micro USB Camera                              | 2         | 1.08%   |
| Acer SunplusIT Integrated Camera                    | 2         | 1.08%   |
| Acer Integrated Camera                              | 2         | 1.08%   |
| Z-Star Vimicro USB Camera (Altair)                  | 1         | 0.54%   |
| Z-Star Traveler TV 6500 SF Dia-scanner              | 1         | 0.54%   |
| Xiongmai web camera                                 | 1         | 0.54%   |
| USB Camera CS USB Camera CS                         | 1         | 0.54%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 35.48%  |
| Synaptics                  | 6         | 19.35%  |
| Upek                       | 5         | 16.13%  |
| Shenzhen Goodix Technology | 5         | 16.13%  |
| STMicroelectronics         | 2         | 6.45%   |
| Elan Microelectronics      | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 5         | 16.13%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 12.9%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 12.9%   |
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 9.68%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 6.45%   |
| Validity Sensors Synaptics WBDI                        | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 6.45%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 6.45%   |
| Unknown                                                | 2         | 6.45%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 3.23%   |
| Synaptics  WBDI                                        | 1         | 3.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.23%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.23%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 42.11%  |
| Alcor Micro | 7         | 36.84%  |
| O2 Micro    | 2         | 10.53%  |
| Lenovo      | 2         | 10.53%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 36.84%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 10.53%  |
| Broadcom 58200                                                               | 2         | 10.53%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 124       | 62.94%  |
| 1     | 56        | 28.43%  |
| 2     | 14        | 7.11%   |
| 3     | 3         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 32.97%  |
| Chipcard                 | 19        | 20.88%  |
| Graphics card            | 11        | 12.09%  |
| Net/wireless             | 7         | 7.69%   |
| Camera                   | 7         | 7.69%   |
| Bluetooth                | 5         | 5.49%   |
| Card reader              | 4         | 4.4%    |
| Network                  | 3         | 3.3%    |
| Communication controller | 2         | 2.2%    |
| Storage                  | 1         | 1.1%    |
| Net/ethernet             | 1         | 1.1%    |
| Multimedia controller    | 1         | 1.1%    |

