Xubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Xubuntu.

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

Total: 3063

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Unknown       | OA Q-ONE BRAND_V2.0         | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| Clevo         | P170EM                      | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| HP            | 8540w                       | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | K53U                        | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| HP            | Laptop 17-cp0xxx            | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Apple         | MacBookAir6,2               | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Latitude E6510              | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Toshiba       | Satellite C75D-B            | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Dell          | 500                         | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| Samsung       | NC10                        | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| MSI           | GS40 6QE Phantom            | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| HP            | 255 G1                      | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Dell          | 500                         | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| HP            | 1000                        | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Dell          | Latitude 9520               | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Acer          | Unknown                     | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Dell          | System XPS L502X            | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | K53SC                       | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| LG Electro... | LE50-5BC6H1                 | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| Toshiba       | NB205                       | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Toshiba       | NB205                       | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Dell          | 500                         | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| HP            | 15                          | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Acer          | Aspire 7720                 | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Acer          | Aspire 7720                 | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Medion        | E15407                      | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X510UA                      | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| Dell          | Latitude E6410              | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | A7K                         | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| Dell          | Latitude E6410              | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| Dell          | Latitude E6410              | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| Toshiba       | Satellite C70D-B            | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| ASUSTek       | K53SC                       | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| HP            | Compaq 6730s                | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Dell          | Latitude E6540              | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | Compaq 6730s                | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | Precision 7550              | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| ASUSTek       | K53SC                       | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | MXG061                      | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| HP            | Pavilion dv6500             | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| Wortmann      | M7x0S                       | [364f9cbe89](https://linux-hardware.org/?probe=364f9cbe89) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| HP            | Pavilion 15                 | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| HP            | Laptop 15-ef2xxx            | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| Dell          | Latitude E6400              | [49b4e17d7a](https://linux-hardware.org/?probe=49b4e17d7a) | Mar 22, 2022 |
| ASUSTek       | X501A                       | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| Samsung       | R510/P510                   | [5ec1b197a4](https://linux-hardware.org/?probe=5ec1b197a4) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| Packard Be... | EasyNote TM85               | [ec7dd9aba3](https://linux-hardware.org/?probe=ec7dd9aba3) | Mar 17, 2022 |
| Toshiba       | NB205                       | [ffef19b228](https://linux-hardware.org/?probe=ffef19b228) | Mar 17, 2022 |
| Acer          | Nitro AN515-42              | [97ebb0ca74](https://linux-hardware.org/?probe=97ebb0ca74) | Mar 16, 2022 |
| Teclast       | F15 Plus                    | [9d3b8151f2](https://linux-hardware.org/?probe=9d3b8151f2) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | [69cae65bf4](https://linux-hardware.org/?probe=69cae65bf4) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | [67a1970f50](https://linux-hardware.org/?probe=67a1970f50) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion dv7                | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Dell          | Inspiron 7520               | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Dell          | Latitude E6400              | [bcacefe427](https://linux-hardware.org/?probe=bcacefe427) | Mar 08, 2022 |
| Packard Be... | EasyNote TM85               | [10c87bed94](https://linux-hardware.org/?probe=10c87bed94) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | [2b3ba9a762](https://linux-hardware.org/?probe=2b3ba9a762) | Mar 07, 2022 |
| Dell          | Latitude E6400              | [4e626b238b](https://linux-hardware.org/?probe=4e626b238b) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| HP            | Pavilion dv7                | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X555LAB                     | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS0LW00    | [c781fc668f](https://linux-hardware.org/?probe=c781fc668f) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| HP            | 15                          | [fa8d20b53f](https://linux-hardware.org/?probe=fa8d20b53f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Gateway       | M-6307                      | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| ASUSTek       | A2D                         | [6fbba6195d](https://linux-hardware.org/?probe=6fbba6195d) | Feb 17, 2022 |
| Lenovo        | ThinkPad R500 2716A54       | [9aa87e9270](https://linux-hardware.org/?probe=9aa87e9270) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [354434e81d](https://linux-hardware.org/?probe=354434e81d) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| Sony          | VPCEB3E1E                   | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | Stream Notebook PC 13       | [33d5b7046b](https://linux-hardware.org/?probe=33d5b7046b) | Feb 13, 2022 |
| Samsung       | 900X1B                      | [c609dfc310](https://linux-hardware.org/?probe=c609dfc310) | Feb 13, 2022 |
| HP            | ProBook 655 G1              | [1c6a5c6e55](https://linux-hardware.org/?probe=1c6a5c6e55) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [935de1698b](https://linux-hardware.org/?probe=935de1698b) | Feb 08, 2022 |
| HP            | ProBook 650 G3              | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Acer          | TravelMate 8172             | [76e402e3d6](https://linux-hardware.org/?probe=76e402e3d6) | Feb 07, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| ASUSTek       | K73SV                       | [d02cd235da](https://linux-hardware.org/?probe=d02cd235da) | Feb 06, 2022 |
| Acer          | Aspire 5100                 | [191eb6224a](https://linux-hardware.org/?probe=191eb6224a) | Feb 06, 2022 |
| IBM           | ThinkPad T43 2668BU7        | [2586bf5e87](https://linux-hardware.org/?probe=2586bf5e87) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Dell          | Latitude E5450              | [84845ef09c](https://linux-hardware.org/?probe=84845ef09c) | Feb 04, 2022 |
| HP            | Pavilion 17                 | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Dell          | Latitude E5450              | [fc7d07dba8](https://linux-hardware.org/?probe=fc7d07dba8) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Fujitsu       | LIFEBOOK E734               | [28280d252b](https://linux-hardware.org/?probe=28280d252b) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| HP            | EliteBook 725 G2            | [d49dd26324](https://linux-hardware.org/?probe=d49dd26324) | Feb 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [460a295f83](https://linux-hardware.org/?probe=460a295f83) | Jan 30, 2022 |
| Gateway       | MT6831                      | [36947a389a](https://linux-hardware.org/?probe=36947a389a) | Jan 30, 2022 |
| HP            | EliteBook 745 G3            | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Acer          | AOD257                      | [4d8476adb1](https://linux-hardware.org/?probe=4d8476adb1) | Jan 29, 2022 |
| ASUSTek       | TP500LA                     | [e18b673cd3](https://linux-hardware.org/?probe=e18b673cd3) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [a571bdc501](https://linux-hardware.org/?probe=a571bdc501) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [c969e228f3](https://linux-hardware.org/?probe=c969e228f3) | Jan 28, 2022 |
| Dell          | Studio 1450                 | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Dell          | Latitude D630               | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| HP            | G42                         | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| Acer          | Aspire E5-575G              | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| HP            | G60                         | [acd0e22a1a](https://linux-hardware.org/?probe=acd0e22a1a) | Jan 23, 2022 |
| MSI           | U90/U100                    | [a87163f5ea](https://linux-hardware.org/?probe=a87163f5ea) | Jan 23, 2022 |
| Kogan         | KAL11C250SB                 | [ba3fd61313](https://linux-hardware.org/?probe=ba3fd61313) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| HP            | ProBook 440 G6              | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| MSI           | U90/U100                    | [a005adaf94](https://linux-hardware.org/?probe=a005adaf94) | Jan 23, 2022 |
| Dell          | XPS 13 9310                 | [75d4eef3ba](https://linux-hardware.org/?probe=75d4eef3ba) | Jan 22, 2022 |
| HP            | Laptop 17-ca1xxx            | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SNC... | [0b0ddf4175](https://linux-hardware.org/?probe=0b0ddf4175) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| ASUSTek       | K50IJ                       | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [3b8acf9181](https://linux-hardware.org/?probe=3b8acf9181) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [d735255913](https://linux-hardware.org/?probe=d735255913) | Jan 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [7edf924514](https://linux-hardware.org/?probe=7edf924514) | Jan 15, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [347317645d](https://linux-hardware.org/?probe=347317645d) | Jan 15, 2022 |
| Insyde        | Braswell                    | [a5bca1e5e8](https://linux-hardware.org/?probe=a5bca1e5e8) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [e293ddf5fc](https://linux-hardware.org/?probe=e293ddf5fc) | Jan 14, 2022 |
| Dell          | Latitude D620               | [a43c35d2fa](https://linux-hardware.org/?probe=a43c35d2fa) | Jan 14, 2022 |
| ASUSTek       | 1015CX                      | [e682cee335](https://linux-hardware.org/?probe=e682cee335) | Jan 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Dell          | Inspiron 7520               | [e433dbb39d](https://linux-hardware.org/?probe=e433dbb39d) | Jan 12, 2022 |
| Google        | Auron_Yuna                  | [9ccb52f9b4](https://linux-hardware.org/?probe=9ccb52f9b4) | Jan 11, 2022 |
| Lenovo        | IdeaPad S415 Touch 20319    | [d59706fc52](https://linux-hardware.org/?probe=d59706fc52) | Jan 11, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| ASUSTek       | K53SC                       | [b01004055c](https://linux-hardware.org/?probe=b01004055c) | Jan 11, 2022 |
| MOTION        | KEX00                       | [8e36590e72](https://linux-hardware.org/?probe=8e36590e72) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | [d537e0bc35](https://linux-hardware.org/?probe=d537e0bc35) | Jan 09, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | [4bfe339a98](https://linux-hardware.org/?probe=4bfe339a98) | Jan 09, 2022 |
| Alienware     | m15 R3                      | [8cff8c6d3f](https://linux-hardware.org/?probe=8cff8c6d3f) | Jan 09, 2022 |
| Acer          | Extensa 5620                | [41a1c7001c](https://linux-hardware.org/?probe=41a1c7001c) | Jan 08, 2022 |
| Sony          | SVF15A190X                  | [6d729a76af](https://linux-hardware.org/?probe=6d729a76af) | Jan 08, 2022 |
| Dell          | Latitude E6500              | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| Gateway       | NV53A                       | [2e67e3a86e](https://linux-hardware.org/?probe=2e67e3a86e) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| ASUSTek       | N550JV                      | [aefb321446](https://linux-hardware.org/?probe=aefb321446) | Jan 04, 2022 |
| Dell          | Latitude E5440              | [16fbe4c9c0](https://linux-hardware.org/?probe=16fbe4c9c0) | Jan 03, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| HP            | G60                         | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Dell          | Inspiron 5765               | [c3a91857b3](https://linux-hardware.org/?probe=c3a91857b3) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| HP            | EliteBook 8440p (VD484AV... | [ba4cf422e7](https://linux-hardware.org/?probe=ba4cf422e7) | Dec 27, 2021 |
| Toshiba       | Satellite C50-A-19U         | [6a61931dde](https://linux-hardware.org/?probe=6a61931dde) | Dec 26, 2021 |
| Acer          | Aspire A515-54G             | [00c1f1b6df](https://linux-hardware.org/?probe=00c1f1b6df) | Dec 26, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| MSI           | GP76 Leopard 11UG           | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | [2ef30c62b5](https://linux-hardware.org/?probe=2ef30c62b5) | Dec 24, 2021 |
| Google        | Swanky                      | [7c19406756](https://linux-hardware.org/?probe=7c19406756) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| HP            | Pavilion dv7                | [3b47550de1](https://linux-hardware.org/?probe=3b47550de1) | Dec 23, 2021 |
| Acer          | Swift SF114-34              | [7178bccf8f](https://linux-hardware.org/?probe=7178bccf8f) | Dec 22, 2021 |
| HP            | Laptop 17-cn1xxx            | [c26a2c5c03](https://linux-hardware.org/?probe=c26a2c5c03) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| Google        | Nami                        | [045f17f15d](https://linux-hardware.org/?probe=045f17f15d) | Dec 22, 2021 |
| HP            | Compaq Mini 311-1100        | [d1aaa6b464](https://linux-hardware.org/?probe=d1aaa6b464) | Dec 21, 2021 |
| Google        | Kefka                       | [4bd83691fd](https://linux-hardware.org/?probe=4bd83691fd) | Dec 20, 2021 |
| HP            | Laptop 17-cn1xxx            | [e3c5530718](https://linux-hardware.org/?probe=e3c5530718) | Dec 19, 2021 |
| Acer          | Swift SF314-43              | [1f0d544a85](https://linux-hardware.org/?probe=1f0d544a85) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Gateway       | MT6831                      | [3df425d68b](https://linux-hardware.org/?probe=3df425d68b) | Dec 17, 2021 |
| Lenovo        | B50-30 20382                | [7c3c9b5cdd](https://linux-hardware.org/?probe=7c3c9b5cdd) | Dec 17, 2021 |
| Dell          | System XPS L502X            | [4588c107ed](https://linux-hardware.org/?probe=4588c107ed) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| Toshiba       | Satellite A105              | [4bddc587d8](https://linux-hardware.org/?probe=4bddc587d8) | Dec 15, 2021 |
| Lenovo        | ThinkPad T530 24296JG       | [e8d6ff471a](https://linux-hardware.org/?probe=e8d6ff471a) | Dec 15, 2021 |
| Acer          | Aspire one                  | [32fd744f46](https://linux-hardware.org/?probe=32fd744f46) | Dec 14, 2021 |
| Gateway       | NV53A                       | [1912b6b8c5](https://linux-hardware.org/?probe=1912b6b8c5) | Dec 14, 2021 |
| ASUSTek       | X55U                        | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| HP            | Pavilion TS 11              | [1617abd2f4](https://linux-hardware.org/?probe=1617abd2f4) | Dec 12, 2021 |
| Dell          | Inspiron 13-5378            | [22b04adc28](https://linux-hardware.org/?probe=22b04adc28) | Dec 12, 2021 |
| Dell          | Inspiron 7501               | [25566e4f44](https://linux-hardware.org/?probe=25566e4f44) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Dell          | Inspiron 7501               | [9d9b833c3a](https://linux-hardware.org/?probe=9d9b833c3a) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | [f0c57ccd03](https://linux-hardware.org/?probe=f0c57ccd03) | Dec 10, 2021 |
| HP            | ProBook 450 G4              | [9fb3716320](https://linux-hardware.org/?probe=9fb3716320) | Dec 10, 2021 |
| HP            | EliteBook Folio 9470m       | [c505dc1521](https://linux-hardware.org/?probe=c505dc1521) | Dec 09, 2021 |
| HUAWEI        | HKD-WXX                     | [2e235ec353](https://linux-hardware.org/?probe=2e235ec353) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [269cb5f1c1](https://linux-hardware.org/?probe=269cb5f1c1) | Dec 08, 2021 |
| HP            | Pavilion dv6                | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Toshiba       | Satellite A105              | [25a235745d](https://linux-hardware.org/?probe=25a235745d) | Dec 07, 2021 |
| Toshiba       | Satellite A105              | [8b638d983f](https://linux-hardware.org/?probe=8b638d983f) | Dec 07, 2021 |
| Acer          | Aspire 5336                 | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [c4263a27a5](https://linux-hardware.org/?probe=c4263a27a5) | Dec 05, 2021 |
| Acer          | Aspire A315-34              | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Dixonsxp      | Unknown                     | [9f1502866b](https://linux-hardware.org/?probe=9f1502866b) | Dec 03, 2021 |
| Dixonsxp      | Unknown                     | [093fef7eaa](https://linux-hardware.org/?probe=093fef7eaa) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [674712f2a1](https://linux-hardware.org/?probe=674712f2a1) | Dec 03, 2021 |
| Toshiba       | Satellite L870-196          | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| HP            | 2000                        | [f16b490828](https://linux-hardware.org/?probe=f16b490828) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| ASUSTek       | E203NAS                     | [c400f4df81](https://linux-hardware.org/?probe=c400f4df81) | Nov 30, 2021 |
| MSI           | Alpha 17 A4DEK              | [6a72e44cf5](https://linux-hardware.org/?probe=6a72e44cf5) | Nov 29, 2021 |
| ASUSTek       | 1015CX                      | [d1c7a213b8](https://linux-hardware.org/?probe=d1c7a213b8) | Nov 29, 2021 |
| Samsung       | R530/R730/P590              | [0bbf67316b](https://linux-hardware.org/?probe=0bbf67316b) | Nov 28, 2021 |
| Acer          | Swift SF114-34              | [d0170808b3](https://linux-hardware.org/?probe=d0170808b3) | Nov 27, 2021 |
| HP            | ProBook 4310s               | [6d339b7843](https://linux-hardware.org/?probe=6d339b7843) | Nov 27, 2021 |
| Dell          | Inspiron N5030              | [6ddb7fee36](https://linux-hardware.org/?probe=6ddb7fee36) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [71d58a102c](https://linux-hardware.org/?probe=71d58a102c) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [d9b3bd7851](https://linux-hardware.org/?probe=d9b3bd7851) | Nov 26, 2021 |
| MSI           | MS-1034                     | [bbf051d81a](https://linux-hardware.org/?probe=bbf051d81a) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| HP            | Laptop 17-ak0xx             | [176f69ab48](https://linux-hardware.org/?probe=176f69ab48) | Nov 25, 2021 |
| HP            | ProBook 640 G1              | [311cb04cc5](https://linux-hardware.org/?probe=311cb04cc5) | Nov 25, 2021 |
| HP            | Pavilion 17                 | [43944b4f78](https://linux-hardware.org/?probe=43944b4f78) | Nov 24, 2021 |
| HP            | Pavilion dv9700             | [5a583ec569](https://linux-hardware.org/?probe=5a583ec569) | Nov 24, 2021 |
| Lenovo        | ThinkPad R61 77331CU        | [28380a5079](https://linux-hardware.org/?probe=28380a5079) | Nov 23, 2021 |
| ASUSTek       | X51RL                       | [4ec59d2453](https://linux-hardware.org/?probe=4ec59d2453) | Nov 22, 2021 |
| Dell          | XPS 13 9333                 | [faf93e292c](https://linux-hardware.org/?probe=faf93e292c) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Alienware     | M17x                        | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | [65a59cf71c](https://linux-hardware.org/?probe=65a59cf71c) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | [55d87b9d59](https://linux-hardware.org/?probe=55d87b9d59) | Nov 22, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| HP            | ProBook 640 G1              | [b75a64f96a](https://linux-hardware.org/?probe=b75a64f96a) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | ProBook 650 G3              | [def83e3614](https://linux-hardware.org/?probe=def83e3614) | Nov 19, 2021 |
| MSI           | GT75VR 7RE                  | [02a0e2b5c8](https://linux-hardware.org/?probe=02a0e2b5c8) | Nov 19, 2021 |
| ONE-NETBOO... | A1                          | [aff2f60770](https://linux-hardware.org/?probe=aff2f60770) | Nov 19, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [dfba89a8f0](https://linux-hardware.org/?probe=dfba89a8f0) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| Dell          | Latitude 7370               | [b43fadb11c](https://linux-hardware.org/?probe=b43fadb11c) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| HP            | Compaq 6710b (RM405UT#AB... | [f758717e6b](https://linux-hardware.org/?probe=f758717e6b) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| HP            | Compaq 6710b (RM405UT#AB... | [547c6f47b2](https://linux-hardware.org/?probe=547c6f47b2) | Nov 13, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| ASUSTek       | 1002HA                      | [2eb3d438b2](https://linux-hardware.org/?probe=2eb3d438b2) | Nov 12, 2021 |
| HP            | Pavilion TS 11              | [746f0808f4](https://linux-hardware.org/?probe=746f0808f4) | Nov 12, 2021 |
| Dell          | G15 5510                    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| Dell          | Inspiron N5030              | [04def67913](https://linux-hardware.org/?probe=04def67913) | Nov 12, 2021 |
| Google        | Terra                       | [d80b98949e](https://linux-hardware.org/?probe=d80b98949e) | Nov 12, 2021 |
| ASUSTek       | X501A                       | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [f168acafa4](https://linux-hardware.org/?probe=f168acafa4) | Nov 10, 2021 |
| HP            | ZBook 15 G3                 | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Lenovo        | ThinkPad T410 2537MT3       | [76965c829b](https://linux-hardware.org/?probe=76965c829b) | Nov 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [6d3d2766f2](https://linux-hardware.org/?probe=6d3d2766f2) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81237c05f7](https://linux-hardware.org/?probe=81237c05f7) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| System76      | Oryx Pro                    | [39d1d14e62](https://linux-hardware.org/?probe=39d1d14e62) | Nov 07, 2021 |
| HP            | Pavilion g6                 | [ed14748445](https://linux-hardware.org/?probe=ed14748445) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Dell          | G3 3500                     | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Dell          | Precision M4600             | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [305cca4bc8](https://linux-hardware.org/?probe=305cca4bc8) | Nov 06, 2021 |
| MAXDATA       | ECO4000IW                   | [090bbdeb4a](https://linux-hardware.org/?probe=090bbdeb4a) | Nov 06, 2021 |
| ASUSTek       | E402SA                      | [345438c3cd](https://linux-hardware.org/?probe=345438c3cd) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Nitro AN715-52              | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| Dell          | Inspiron 7501               | [3690315342](https://linux-hardware.org/?probe=3690315342) | Nov 05, 2021 |
| HP            | Pavilion dv6                | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP            | Pavilion dv6                | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Toshiba       | Satellite P745              | [59b3468fb9](https://linux-hardware.org/?probe=59b3468fb9) | Nov 04, 2021 |
| HP            | ProBook 6450b               | [603fac0b2e](https://linux-hardware.org/?probe=603fac0b2e) | Nov 04, 2021 |
| Dell          | Latitude D630               | [f212896c99](https://linux-hardware.org/?probe=f212896c99) | Nov 04, 2021 |
| Dell          | Precision M4600             | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| Toshiba       | Satellite C70D-B            | [9fd353eaff](https://linux-hardware.org/?probe=9fd353eaff) | Nov 04, 2021 |
| ASUSTek       | T100TA                      | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| HP            | Compaq Presario CQ61        | [86dd6331fc](https://linux-hardware.org/?probe=86dd6331fc) | Nov 02, 2021 |
| HP            | Pavilion TS 11              | [29af280c0e](https://linux-hardware.org/?probe=29af280c0e) | Nov 01, 2021 |
| ASUSTek       | P2540UA                     | [f10ce209c4](https://linux-hardware.org/?probe=f10ce209c4) | Nov 01, 2021 |
| ASUSTek       | GL553VE                     | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| ASUSTek       | X756UX                      | [2f027fcbc2](https://linux-hardware.org/?probe=2f027fcbc2) | Oct 30, 2021 |
| VIT           | P3400                       | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Toshiba       | Satellite P55W-C            | [8d16328dfd](https://linux-hardware.org/?probe=8d16328dfd) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| Lenovo        | ThinkPad W510 431963G       | [5ce9661292](https://linux-hardware.org/?probe=5ce9661292) | Oct 28, 2021 |
| MSI           | MS-1034                     | [f1770353a3](https://linux-hardware.org/?probe=f1770353a3) | Oct 28, 2021 |
| HP            | Compaq 6730s                | [8bc4483616](https://linux-hardware.org/?probe=8bc4483616) | Oct 27, 2021 |
| HP            | Pavilion g4                 | [90f6743fbd](https://linux-hardware.org/?probe=90f6743fbd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [406fcb6975](https://linux-hardware.org/?probe=406fcb6975) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [336d9d575f](https://linux-hardware.org/?probe=336d9d575f) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Alienware     | m17 R4                      | [5c569c3982](https://linux-hardware.org/?probe=5c569c3982) | Oct 24, 2021 |
| HP            | Compaq 6730s                | [587b440ce4](https://linux-hardware.org/?probe=587b440ce4) | Oct 24, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [68f1525bef](https://linux-hardware.org/?probe=68f1525bef) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [1146299277](https://linux-hardware.org/?probe=1146299277) | Oct 23, 2021 |
| HP            | Compaq Presario CQ61        | [cb8b850048](https://linux-hardware.org/?probe=cb8b850048) | Oct 23, 2021 |
| Sony          | VGN-NR11Z_T                 | [f76ae4b159](https://linux-hardware.org/?probe=f76ae4b159) | Oct 22, 2021 |
| HP            | kip                         | [18f48f3a5b](https://linux-hardware.org/?probe=18f48f3a5b) | Oct 22, 2021 |
| Lenovo        | ThinkPad W510 431963G       | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| HP            | Notebook                    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| Lenovo        | ThinkPad T420 4180AP3       | [6be3808b94](https://linux-hardware.org/?probe=6be3808b94) | Oct 21, 2021 |
| Lenovo        | IdeaPad U550 20034,3749     | [3bbec8b8fd](https://linux-hardware.org/?probe=3bbec8b8fd) | Oct 21, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | [8ad9f2f898](https://linux-hardware.org/?probe=8ad9f2f898) | Oct 20, 2021 |
| Apple         | MacBookPro11,1              | [7fb2681427](https://linux-hardware.org/?probe=7fb2681427) | Oct 20, 2021 |
| Lenovo        | B5400 s20278Q               | [c71ca98310](https://linux-hardware.org/?probe=c71ca98310) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| Samsung       | R530/R730/P590              | [e76e147759](https://linux-hardware.org/?probe=e76e147759) | Oct 19, 2021 |
| Lenovo        | B50-30 20382                | [235b6e8d1a](https://linux-hardware.org/?probe=235b6e8d1a) | Oct 18, 2021 |
| Acer          | Extensa 5630                | [4823b348aa](https://linux-hardware.org/?probe=4823b348aa) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Latitude E6440              | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 255 G7 Notebook PC          | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b9218a0347](https://linux-hardware.org/?probe=b9218a0347) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Dell          | XPS L521X                   | [5026df6496](https://linux-hardware.org/?probe=5026df6496) | Oct 15, 2021 |
| HP            | Mini 110-3000               | [ee2ce4e3b9](https://linux-hardware.org/?probe=ee2ce4e3b9) | Oct 14, 2021 |
| Toshiba       | Satellite A100              | [ef126ad790](https://linux-hardware.org/?probe=ef126ad790) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| Dell          | Latitude D630               | [f931dcd89d](https://linux-hardware.org/?probe=f931dcd89d) | Oct 13, 2021 |
| Dell          | Latitude D630               | [328ae0eccc](https://linux-hardware.org/?probe=328ae0eccc) | Oct 13, 2021 |
| HP            | OMEN by Laptop              | [6163de66f1](https://linux-hardware.org/?probe=6163de66f1) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| Dell          | Latitude 7370               | [348b718b2b](https://linux-hardware.org/?probe=348b718b2b) | Oct 11, 2021 |
| HP            | Notebook                    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| Lenovo        | ThinkPad T60 1952W97        | [17678957ea](https://linux-hardware.org/?probe=17678957ea) | Oct 11, 2021 |
| HP            | Compaq 6730s                | [9b21d843cd](https://linux-hardware.org/?probe=9b21d843cd) | Oct 10, 2021 |
| LG Electro... | R710-S.APSAG                | [07b311caef](https://linux-hardware.org/?probe=07b311caef) | Oct 09, 2021 |
| Sony          | VGN-N11M_W                  | [7a0e2dfd11](https://linux-hardware.org/?probe=7a0e2dfd11) | Oct 09, 2021 |
| Dell          | Precision 5540              | [b59369e8e7](https://linux-hardware.org/?probe=b59369e8e7) | Oct 08, 2021 |
| Multilaser    | UB32X                       | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| HP            | Compaq 6720s                | [36a9fc9a39](https://linux-hardware.org/?probe=36a9fc9a39) | Oct 07, 2021 |
| Lenovo        | ThinkPad T60 1952W97        | [babe5f02f0](https://linux-hardware.org/?probe=babe5f02f0) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [399430cdbe](https://linux-hardware.org/?probe=399430cdbe) | Oct 06, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9638a69b00](https://linux-hardware.org/?probe=9638a69b00) | Oct 06, 2021 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [d09fddd2b5](https://linux-hardware.org/?probe=d09fddd2b5) | Oct 06, 2021 |
| ASUSTek       | 1005HA                      | [c420fc556e](https://linux-hardware.org/?probe=c420fc556e) | Oct 05, 2021 |
| Sony          | VPCSB1V9R                   | [2d0b219a36](https://linux-hardware.org/?probe=2d0b219a36) | Oct 05, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [697843fefc](https://linux-hardware.org/?probe=697843fefc) | Oct 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [9ba5143844](https://linux-hardware.org/?probe=9ba5143844) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [564dd05308](https://linux-hardware.org/?probe=564dd05308) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [01f8341213](https://linux-hardware.org/?probe=01f8341213) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| Medion        | E14303                      | [0fa72b5193](https://linux-hardware.org/?probe=0fa72b5193) | Oct 02, 2021 |
| Sony          | VGN-NR38E_S                 | [8cb5fc39c1](https://linux-hardware.org/?probe=8cb5fc39c1) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK E752               | [5cccf30dd4](https://linux-hardware.org/?probe=5cccf30dd4) | Oct 01, 2021 |
| ASUSTek       | K53E                        | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| HP            | Compaq 6730b (GW687AV)      | [ae3ecaef4f](https://linux-hardware.org/?probe=ae3ecaef4f) | Sep 29, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [73a0747f86](https://linux-hardware.org/?probe=73a0747f86) | Sep 29, 2021 |
| HP            | Notebook                    | [bdf314b662](https://linux-hardware.org/?probe=bdf314b662) | Sep 29, 2021 |
| Toshiba       | Satellite C55-A             | [97872be09f](https://linux-hardware.org/?probe=97872be09f) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | [c79d4daf0a](https://linux-hardware.org/?probe=c79d4daf0a) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [4850590ac5](https://linux-hardware.org/?probe=4850590ac5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e7f361c688](https://linux-hardware.org/?probe=e7f361c688) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [17bef7f4cf](https://linux-hardware.org/?probe=17bef7f4cf) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [d3fcb6ade8](https://linux-hardware.org/?probe=d3fcb6ade8) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| HP            | EliteBook 850 G2            | [d4635dacdd](https://linux-hardware.org/?probe=d4635dacdd) | Sep 26, 2021 |
| Dell          | Studio 1558                 | [05f781c843](https://linux-hardware.org/?probe=05f781c843) | Sep 25, 2021 |
| HP            | Compaq 6710b (GB889ET#AB... | [2fcbe348d6](https://linux-hardware.org/?probe=2fcbe348d6) | Sep 24, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | [cc4ac84959](https://linux-hardware.org/?probe=cc4ac84959) | Sep 22, 2021 |
| HP            | Notebook                    | [0253eca654](https://linux-hardware.org/?probe=0253eca654) | Sep 22, 2021 |
| HP            | Notebook                    | [9afc140a7e](https://linux-hardware.org/?probe=9afc140a7e) | Sep 22, 2021 |
| ASUSTek       | T100HAN                     | [aabfa3e289](https://linux-hardware.org/?probe=aabfa3e289) | Sep 22, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [f770a4f41f](https://linux-hardware.org/?probe=f770a4f41f) | Sep 20, 2021 |
| HP            | Stream Notebook PC 13       | [193b294617](https://linux-hardware.org/?probe=193b294617) | Sep 20, 2021 |
| HP            | Compaq CQ45                 | [87a47d3bc8](https://linux-hardware.org/?probe=87a47d3bc8) | Sep 20, 2021 |
| Clevo         | W760SUB                     | [8ae1ea1d6b](https://linux-hardware.org/?probe=8ae1ea1d6b) | Sep 20, 2021 |
| HP            | ProBook 4510s               | [721b35cbcb](https://linux-hardware.org/?probe=721b35cbcb) | Sep 19, 2021 |
| ASUSTek       | A6JC                        | [71da82e880](https://linux-hardware.org/?probe=71da82e880) | Sep 18, 2021 |
| HP            | 550                         | [19817702a0](https://linux-hardware.org/?probe=19817702a0) | Sep 17, 2021 |
| Lenovo        | G460 0677                   | [6f23b54ef5](https://linux-hardware.org/?probe=6f23b54ef5) | Sep 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5cd5dd7086](https://linux-hardware.org/?probe=5cd5dd7086) | Sep 17, 2021 |
| Dell          | Latitude D630               | [260bb1528f](https://linux-hardware.org/?probe=260bb1528f) | Sep 15, 2021 |
| Dell          | Inspiron 3437               | [67069e48f0](https://linux-hardware.org/?probe=67069e48f0) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| HP            | 550                         | [5b79123b1c](https://linux-hardware.org/?probe=5b79123b1c) | Sep 14, 2021 |
| HP            | 620                         | [1ab2cc4e02](https://linux-hardware.org/?probe=1ab2cc4e02) | Sep 14, 2021 |
| HP            | Pavilion dv2500             | [0b9636c64b](https://linux-hardware.org/?probe=0b9636c64b) | Sep 14, 2021 |
| HP            | 15                          | [d88dbb5aa3](https://linux-hardware.org/?probe=d88dbb5aa3) | Sep 12, 2021 |
| HP            | Pavilion dm4                | [a10c76835b](https://linux-hardware.org/?probe=a10c76835b) | Sep 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [bced59049e](https://linux-hardware.org/?probe=bced59049e) | Sep 11, 2021 |
| HP            | Compaq nx8220 (PG801ET#A... | [bf69b6646d](https://linux-hardware.org/?probe=bf69b6646d) | Sep 11, 2021 |
| HP            | Compaq nx8220 (PG801ET#A... | [796e5b8b43](https://linux-hardware.org/?probe=796e5b8b43) | Sep 11, 2021 |
| HP            | Pavilion dv6                | [e2ad40d8c1](https://linux-hardware.org/?probe=e2ad40d8c1) | Sep 10, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | [3abbaccc90](https://linux-hardware.org/?probe=3abbaccc90) | Sep 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [a3e329ff30](https://linux-hardware.org/?probe=a3e329ff30) | Sep 09, 2021 |
| MSI           | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | ProBook 4510s               | [b2e4641005](https://linux-hardware.org/?probe=b2e4641005) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | [3ca698d670](https://linux-hardware.org/?probe=3ca698d670) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | [37bd4db385](https://linux-hardware.org/?probe=37bd4db385) | Sep 09, 2021 |
| Itautec       | Infoway a7420               | [282046f0c0](https://linux-hardware.org/?probe=282046f0c0) | Sep 09, 2021 |
| HP            | G60                         | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | [527f58e3a8](https://linux-hardware.org/?probe=527f58e3a8) | Sep 08, 2021 |
| ASUSTek       | K70AB                       | [09d17038e7](https://linux-hardware.org/?probe=09d17038e7) | Sep 07, 2021 |
| HP            | ProBook 4520s               | [7deeda6273](https://linux-hardware.org/?probe=7deeda6273) | Sep 07, 2021 |
| Dell          | Inspiron 5577               | [d7b97d1fff](https://linux-hardware.org/?probe=d7b97d1fff) | Sep 07, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [7ff32b60eb](https://linux-hardware.org/?probe=7ff32b60eb) | Sep 05, 2021 |
| Dell          | Latitude E4310              | [5e7233f129](https://linux-hardware.org/?probe=5e7233f129) | Sep 05, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [631ee4fd97](https://linux-hardware.org/?probe=631ee4fd97) | Sep 05, 2021 |
| Google        | Nautilus                    | [83c28c6fb1](https://linux-hardware.org/?probe=83c28c6fb1) | Sep 05, 2021 |
| ASUSTek       | 1215P                       | [dd6345e640](https://linux-hardware.org/?probe=dd6345e640) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [441840f603](https://linux-hardware.org/?probe=441840f603) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Gateway       | NV57H                       | [5ccb66dc7c](https://linux-hardware.org/?probe=5ccb66dc7c) | Sep 03, 2021 |
| Acer          | TravelMate 5310             | [ac6597929a](https://linux-hardware.org/?probe=ac6597929a) | Sep 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e47d2dc721](https://linux-hardware.org/?probe=e47d2dc721) | Sep 02, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [d6397ce0e3](https://linux-hardware.org/?probe=d6397ce0e3) | Sep 02, 2021 |
| Acer          | Aspire E1-772               | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ee916ec895](https://linux-hardware.org/?probe=ee916ec895) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| HP            | Notebook                    | [6afc243dea](https://linux-hardware.org/?probe=6afc243dea) | Sep 01, 2021 |
| Lenovo        | ThinkPad X395 20NLS0J400    | [cd2fa55d01](https://linux-hardware.org/?probe=cd2fa55d01) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | [3140742cd5](https://linux-hardware.org/?probe=3140742cd5) | Aug 31, 2021 |
| HP            | OMEN by Laptop              | [0631958800](https://linux-hardware.org/?probe=0631958800) | Aug 29, 2021 |
| Dell          | XPS L412Z                   | [e2cb7e745e](https://linux-hardware.org/?probe=e2cb7e745e) | Aug 29, 2021 |
| Lenovo        | QIWG5                       | [7287242b4c](https://linux-hardware.org/?probe=7287242b4c) | Aug 28, 2021 |
| Lenovo        | QIWG5                       | [b9edb3e2ab](https://linux-hardware.org/?probe=b9edb3e2ab) | Aug 28, 2021 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [c5bbffbd8f](https://linux-hardware.org/?probe=c5bbffbd8f) | Aug 28, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | 15                          | [8e64e4a38f](https://linux-hardware.org/?probe=8e64e4a38f) | Aug 26, 2021 |
| Toshiba       | PORTEGE R30-A               | [c639ec81b0](https://linux-hardware.org/?probe=c639ec81b0) | Aug 26, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | [932fb79537](https://linux-hardware.org/?probe=932fb79537) | Aug 26, 2021 |
| HP            | Mini 311-1000               | [50468df6ed](https://linux-hardware.org/?probe=50468df6ed) | Aug 25, 2021 |
| MSI           | PR601/VR603                 | [836a501df0](https://linux-hardware.org/?probe=836a501df0) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | [551749a1af](https://linux-hardware.org/?probe=551749a1af) | Aug 25, 2021 |
| Notebook      | W970SUW                     | [231346d40a](https://linux-hardware.org/?probe=231346d40a) | Aug 24, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | [74c2a834e7](https://linux-hardware.org/?probe=74c2a834e7) | Aug 23, 2021 |
| Toshiba       | Satellite P300              | [03ec6b77ae](https://linux-hardware.org/?probe=03ec6b77ae) | Aug 23, 2021 |
| Dell          | Studio 1569                 | [600cbb330c](https://linux-hardware.org/?probe=600cbb330c) | Aug 23, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [08e78aa61d](https://linux-hardware.org/?probe=08e78aa61d) | Aug 23, 2021 |
| ASUSTek       | X501A                       | [e9784e8db3](https://linux-hardware.org/?probe=e9784e8db3) | Aug 21, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | [fb7ab1b2d1](https://linux-hardware.org/?probe=fb7ab1b2d1) | Aug 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [df5f5f1ab4](https://linux-hardware.org/?probe=df5f5f1ab4) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | [6651af56b1](https://linux-hardware.org/?probe=6651af56b1) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | [a0e952ee9c](https://linux-hardware.org/?probe=a0e952ee9c) | Aug 19, 2021 |
| Google        | Kip                         | [11ba4592bc](https://linux-hardware.org/?probe=11ba4592bc) | Aug 19, 2021 |
| HP            | ProBook 450 G3              | [37a5e6b984](https://linux-hardware.org/?probe=37a5e6b984) | Aug 18, 2021 |
| HP            | 255 G1                      | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | [a5b305d6f5](https://linux-hardware.org/?probe=a5b305d6f5) | Aug 18, 2021 |
| HP            | EliteBook 8470p             | [ce21a853bc](https://linux-hardware.org/?probe=ce21a853bc) | Aug 18, 2021 |
| Dell          | Latitude E5520              | [9e4e9c3dea](https://linux-hardware.org/?probe=9e4e9c3dea) | Aug 17, 2021 |
| Lenovo        | B5400 s20278Q               | [24ebde0d00](https://linux-hardware.org/?probe=24ebde0d00) | Aug 17, 2021 |
| Dell          | Latitude E4310              | [489bf81791](https://linux-hardware.org/?probe=489bf81791) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Lenovo        | V130-15IKB 81HN             | [0f274985d5](https://linux-hardware.org/?probe=0f274985d5) | Aug 17, 2021 |
| Lenovo        | ThinkPad W540 20BHS0KY08    | [6ba4712f8d](https://linux-hardware.org/?probe=6ba4712f8d) | Aug 16, 2021 |
| Dell          | Vostro 3491                 | [0f23db87f7](https://linux-hardware.org/?probe=0f23db87f7) | Aug 16, 2021 |
| HP            | Unknown                     | [11a771b463](https://linux-hardware.org/?probe=11a771b463) | Aug 15, 2021 |
| HP            | ProBook 6470b               | [f42e212309](https://linux-hardware.org/?probe=f42e212309) | Aug 14, 2021 |
| HP            | Compaq 8710w                | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| Lenovo        | ThinkPad W540 20BHS1HR00    | [514e20d875](https://linux-hardware.org/?probe=514e20d875) | Aug 14, 2021 |
| HP            | Compaq CQ58                 | [23b1aab5c3](https://linux-hardware.org/?probe=23b1aab5c3) | Aug 13, 2021 |
| Acer          | Predator PH315-52           | [35a01be443](https://linux-hardware.org/?probe=35a01be443) | Aug 13, 2021 |
| Toshiba       | Satellite P205D             | [95f23ff5ec](https://linux-hardware.org/?probe=95f23ff5ec) | Aug 13, 2021 |
| Dell          | Vostro 3491                 | [125085e464](https://linux-hardware.org/?probe=125085e464) | Aug 12, 2021 |
| ASUSTek       | N550JV                      | [a0023fa7d2](https://linux-hardware.org/?probe=a0023fa7d2) | Aug 12, 2021 |
| Digibras      | NH4CU53                     | [815877fb99](https://linux-hardware.org/?probe=815877fb99) | Aug 11, 2021 |
| HP            | EliteBook 840 G3            | [4a660bcb77](https://linux-hardware.org/?probe=4a660bcb77) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| ASUSTek       | 1002HA                      | [f94a12bb94](https://linux-hardware.org/?probe=f94a12bb94) | Aug 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [adee49adad](https://linux-hardware.org/?probe=adee49adad) | Aug 10, 2021 |
| Clevo         | W240HU/W250HUQ              | [24fa19e6a1](https://linux-hardware.org/?probe=24fa19e6a1) | Aug 09, 2021 |
| Toshiba       | Satellite P205D             | [827f451413](https://linux-hardware.org/?probe=827f451413) | Aug 07, 2021 |
| Toshiba       | Satellite P205D             | [a39bd5d78b](https://linux-hardware.org/?probe=a39bd5d78b) | Aug 07, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [36bdd2c814](https://linux-hardware.org/?probe=36bdd2c814) | Aug 07, 2021 |
| Toshiba       | Satellite A100              | [7d3f237f02](https://linux-hardware.org/?probe=7d3f237f02) | Aug 07, 2021 |
| UNOWHY        | Y13G010S4EI                 | [a642818617](https://linux-hardware.org/?probe=a642818617) | Aug 06, 2021 |
| Notebook      | P65_P67RGRERA               | [07d63d9efc](https://linux-hardware.org/?probe=07d63d9efc) | Aug 06, 2021 |
| Sony          | VPCF236FM                   | [01a2971d58](https://linux-hardware.org/?probe=01a2971d58) | Aug 06, 2021 |
| Acer          | Aspire ES1-111              | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| Lenovo        | G460 0677                   | [18dd5bf1b0](https://linux-hardware.org/?probe=18dd5bf1b0) | Aug 05, 2021 |
| ASUSTek       | 1002HA                      | [3b3ec4d071](https://linux-hardware.org/?probe=3b3ec4d071) | Aug 04, 2021 |
| Lenovo        | ThinkPad T61 6468AE2        | [4dd4d240c2](https://linux-hardware.org/?probe=4dd4d240c2) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| Dell          | G5 5590                     | [946f31a6ac](https://linux-hardware.org/?probe=946f31a6ac) | Aug 04, 2021 |
| Lenovo        | ThinkPad T61 6468AE2        | [939fbd8a09](https://linux-hardware.org/?probe=939fbd8a09) | Aug 04, 2021 |
| HP            | 2000                        | [27633bfd4b](https://linux-hardware.org/?probe=27633bfd4b) | Aug 03, 2021 |
| Acer          | Swift SF314-54G             | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Toshiba       | Satellite C665D             | [d59b8d5f1d](https://linux-hardware.org/?probe=d59b8d5f1d) | Aug 03, 2021 |
| Lenovo        | G460 0677                   | [1563cdbde9](https://linux-hardware.org/?probe=1563cdbde9) | Aug 02, 2021 |
| Sony          | SVE1512C6EB                 | [e6e8da123e](https://linux-hardware.org/?probe=e6e8da123e) | Aug 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fb919a9b90](https://linux-hardware.org/?probe=fb919a9b90) | Jul 30, 2021 |
| Acer          | Aspire E5-521               | [c901cb9abb](https://linux-hardware.org/?probe=c901cb9abb) | Jul 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Xubuntu 20.04 | 993       | 47.76%  |
| Xubuntu 18.04 | 586       | 28.19%  |
| Xubuntu 22.04 | 159       | 7.65%   |
| Xubuntu 19.10 | 110       | 5.29%   |
| Xubuntu 21.10 | 57        | 2.74%   |
| Xubuntu 16.04 | 46        | 2.21%   |
| Xubuntu 20.10 | 42        | 2.02%   |
| Xubuntu 21.04 | 41        | 1.97%   |
| Xubuntu 19.04 | 13        | 0.63%   |
| Xubuntu 22.10 | 10        | 0.48%   |
| Xubuntu 18.10 | 6         | 0.29%   |
| Xubuntu 17.10 | 6         | 0.29%   |
| Xubuntu       | 4         | 0.19%   |
| Xubuntu 14.04 | 3         | 0.14%   |
| Xubuntu 17.04 | 2         | 0.1%    |
| Xubuntu 23.04 | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Xubuntu | 2025      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 87        | 3.7%    |
| 5.3.0-46-generic    | 41        | 1.74%   |
| 5.11.0-27-generic   | 39        | 1.66%   |
| 5.4.0-58-generic    | 34        | 1.45%   |
| 5.4.0-47-generic    | 31        | 1.32%   |
| 5.4.0-52-generic    | 30        | 1.28%   |
| 5.4.0-29-generic    | 30        | 1.28%   |
| 5.4.0-48-generic    | 28        | 1.19%   |
| 5.4.0-65-generic    | 27        | 1.15%   |
| 5.3.0-40-generic    | 27        | 1.15%   |
| 5.3.0-42-generic    | 26        | 1.11%   |
| 5.4.0-54-generic    | 25        | 1.06%   |
| 5.3.0-51-generic    | 22        | 0.94%   |
| 5.15.0-56-generic   | 22        | 0.94%   |
| 5.4.0-31-generic    | 21        | 0.89%   |
| 5.0.0-37-generic    | 21        | 0.89%   |
| 5.4.0-40-generic    | 20        | 0.85%   |
| 5.3.0-28-generic    | 19        | 0.81%   |
| 5.15.0-52-generic   | 19        | 0.81%   |
| 5.15.0-47-generic   | 19        | 0.81%   |
| 4.15.0-99-generic   | 19        | 0.81%   |
| 5.4.0-42-lowlatency | 18        | 0.77%   |
| 5.3.0-53-generic    | 18        | 0.77%   |
| 5.15.0-48-generic   | 18        | 0.77%   |
| 5.4.0-89-generic    | 17        | 0.72%   |
| 5.4.0-66-generic    | 17        | 0.72%   |
| 5.4.0-26-generic    | 17        | 0.72%   |
| 5.4.0-67-generic    | 16        | 0.68%   |
| 5.4.0-53-generic    | 16        | 0.68%   |
| 5.4.0-37-generic    | 16        | 0.68%   |
| 5.8.0-53-generic    | 15        | 0.64%   |
| 5.8.0-43-generic    | 15        | 0.64%   |
| 5.4.0-56-generic    | 15        | 0.64%   |
| 5.13.0-39-generic   | 15        | 0.64%   |
| 5.13.0-30-generic   | 15        | 0.64%   |
| 5.4.0-72-generic    | 14        | 0.6%    |
| 5.4.0-60-generic    | 14        | 0.6%    |
| 5.4.0-33-generic    | 14        | 0.6%    |
| 5.15.0-46-generic   | 14        | 0.6%    |
| 5.11.0-25-generic   | 14        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 811       | 38.24%  |
| 5.3.0   | 258       | 12.16%  |
| 4.15.0  | 243       | 11.46%  |
| 5.15.0  | 172       | 8.11%   |
| 5.11.0  | 166       | 7.83%   |
| 5.8.0   | 132       | 6.22%   |
| 5.13.0  | 131       | 6.18%   |
| 5.0.0   | 57        | 2.69%   |
| 4.4.0   | 24        | 1.13%   |
| 4.18.0  | 14        | 0.66%   |
| 5.19.0  | 10        | 0.47%   |
| 5.17.0  | 8         | 0.38%   |
| 4.13.0  | 7         | 0.33%   |
| 5.10.0  | 5         | 0.24%   |
| 5.14.0  | 4         | 0.19%   |
| 5.6.0   | 3         | 0.14%   |
| 5.18.0  | 3         | 0.14%   |
| 6.0.9   | 2         | 0.09%   |
| 6.0.0   | 2         | 0.09%   |
| 5.6.19  | 2         | 0.09%   |
| 5.5.19  | 2         | 0.09%   |
| 5.11.11 | 2         | 0.09%   |
| 4.8.0   | 2         | 0.09%   |
| 4.4.254 | 2         | 0.09%   |
| 4.11.0  | 2         | 0.09%   |
| 4.10.0  | 2         | 0.09%   |
| 6.1.0   | 1         | 0.05%   |
| 6.0.7   | 1         | 0.05%   |
| 5.9.6   | 1         | 0.05%   |
| 5.9.16  | 1         | 0.05%   |
| 5.9.0   | 1         | 0.05%   |
| 5.8.18  | 1         | 0.05%   |
| 5.7.7   | 1         | 0.05%   |
| 5.7.6   | 1         | 0.05%   |
| 5.7.19  | 1         | 0.05%   |
| 5.7.1   | 1         | 0.05%   |
| 5.7.0   | 1         | 0.05%   |
| 5.6.3   | 1         | 0.05%   |
| 5.4.67  | 1         | 0.05%   |
| 5.4.217 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 815       | 38.44%  |
| 5.3     | 260       | 12.26%  |
| 4.15    | 243       | 11.46%  |
| 5.15    | 174       | 8.21%   |
| 5.11    | 172       | 8.11%   |
| 5.8     | 133       | 6.27%   |
| 5.13    | 132       | 6.23%   |
| 5.0     | 58        | 2.74%   |
| 4.4     | 26        | 1.23%   |
| 4.18    | 14        | 0.66%   |
| 5.19    | 12        | 0.57%   |
| 5.10    | 11        | 0.52%   |
| 5.17    | 9         | 0.42%   |
| 5.14    | 8         | 0.38%   |
| 4.13    | 7         | 0.33%   |
| 5.6     | 6         | 0.28%   |
| 6.0     | 5         | 0.24%   |
| 5.7     | 5         | 0.24%   |
| 4.19    | 5         | 0.24%   |
| 5.12    | 4         | 0.19%   |
| 5.9     | 3         | 0.14%   |
| 5.18    | 3         | 0.14%   |
| 5.5     | 2         | 0.09%   |
| 5.16    | 2         | 0.09%   |
| 4.8     | 2         | 0.09%   |
| 4.11    | 2         | 0.09%   |
| 4.10    | 2         | 0.09%   |
| 6.1     | 1         | 0.05%   |
| 4.20    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 4.12    | 1         | 0.05%   |
| 3.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1695      | 83.62%  |
| i686   | 332       | 16.38%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 1963      | 96.79%  |
| GNOME           | 45        | 2.22%   |
| i3              | 8         | 0.39%   |
| Unity           | 3         | 0.15%   |
| KDE5            | 2         | 0.1%    |
| Cinnamon        | 2         | 0.1%    |
| xmonad          | 1         | 0.05%   |
| MATE            | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| GNOME Flashback | 1         | 0.05%   |
| awesome         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2003      | 98.91%  |
| Tty     | 12        | 0.59%   |
| Wayland | 9         | 0.44%   |
| Unknown | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1114      | 53.35%  |
| LightDM | 636       | 30.46%  |
| TDM     | 284       | 13.6%   |
| GDM3    | 25        | 1.2%    |
| GDM     | 22        | 1.05%   |
| SDDM    | 5         | 0.24%   |
| XDM     | 1         | 0.05%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 662       | 32.61%  |
| de_DE   | 211       | 10.39%  |
| fr_FR   | 171       | 8.42%   |
| it_IT   | 158       | 7.78%   |
| pt_BR   | 104       | 5.12%   |
| ru_RU   | 81        | 3.99%   |
| en_GB   | 78        | 3.84%   |
| C       | 76        | 3.74%   |
| es_ES   | 61        | 3%      |
| Unknown | 43        | 2.12%   |
| pl_PL   | 34        | 1.67%   |
| en_CA   | 30        | 1.48%   |
| en_AU   | 27        | 1.33%   |
| cs_CZ   | 21        | 1.03%   |
| hu_HU   | 18        | 0.89%   |
| es_AR   | 18        | 0.89%   |
| nl_NL   | 17        | 0.84%   |
| en_IN   | 16        | 0.79%   |
| ja_JP   | 14        | 0.69%   |
| es_MX   | 13        | 0.64%   |
| tr_TR   | 10        | 0.49%   |
| pt_PT   | 10        | 0.49%   |
| ru_UA   | 9         | 0.44%   |
| fi_FI   | 9         | 0.44%   |
| el_GR   | 9         | 0.44%   |
| sk_SK   | 8         | 0.39%   |
| fr_BE   | 8         | 0.39%   |
| en_ZA   | 8         | 0.39%   |
| sv_SE   | 7         | 0.34%   |
| nl_BE   | 6         | 0.3%    |
| es_CO   | 6         | 0.3%    |
| de_CH   | 6         | 0.3%    |
| es_VE   | 5         | 0.25%   |
| es_CL   | 5         | 0.25%   |
| ca_ES   | 5         | 0.25%   |
| bg_BG   | 5         | 0.25%   |
| zh_CN   | 4         | 0.2%    |
| uk_UA   | 4         | 0.2%    |
| nb_NO   | 4         | 0.2%    |
| es_PE   | 4         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1266      | 62.09%  |
| EFI  | 773       | 37.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1857      | 91.61%  |
| Overlay | 99        | 4.88%   |
| Btrfs   | 32        | 1.58%   |
| Zfs     | 15        | 0.74%   |
| Unknown | 12        | 0.59%   |
| Xfs     | 4         | 0.2%    |
| Ext2    | 4         | 0.2%    |
| Ext3    | 3         | 0.15%   |
| Ufs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1335      | 65.22%  |
| GPT     | 481       | 23.5%   |
| MBR     | 231       | 11.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1809      | 87.73%  |
| Yes       | 253       | 12.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1427      | 69.61%  |
| Yes       | 623       | 30.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 425       | 20.99%  |
| Lenovo              | 353       | 17.43%  |
| Dell                | 265       | 13.09%  |
| ASUSTek Computer    | 234       | 11.56%  |
| Acer                | 203       | 10.02%  |
| Toshiba             | 96        | 4.74%   |
| Samsung Electronics | 52        | 2.57%   |
| Sony                | 45        | 2.22%   |
| Apple               | 37        | 1.83%   |
| MSI                 | 31        | 1.53%   |
| Medion              | 24        | 1.19%   |
| Fujitsu Siemens     | 23        | 1.14%   |
| Packard Bell        | 18        | 0.89%   |
| Notebook            | 15        | 0.74%   |
| Google              | 14        | 0.69%   |
| Clevo               | 14        | 0.69%   |
| Fujitsu             | 13        | 0.64%   |
| HUAWEI              | 11        | 0.54%   |
| Positivo            | 10        | 0.49%   |
| Unknown             | 10        | 0.49%   |
| Intel               | 7         | 0.35%   |
| IBM                 | 7         | 0.35%   |
| GPU Company         | 6         | 0.3%    |
| Gateway             | 6         | 0.3%    |
| LG Electronics      | 5         | 0.25%   |
| eMachines           | 5         | 0.25%   |
| TUXEDO              | 4         | 0.2%    |
| Schenker            | 4         | 0.2%    |
| Dynabook            | 4         | 0.2%    |
| Alienware           | 4         | 0.2%    |
| Semp Toshiba        | 3         | 0.15%   |
| OEM                 | 3         | 0.15%   |
| Itautec             | 3         | 0.15%   |
| Dixonsxp            | 3         | 0.15%   |
| AMI                 | 3         | 0.15%   |
| System76            | 2         | 0.1%    |
| Razer               | 2         | 0.1%    |
| Quanta              | 2         | 0.1%    |
| Panasonic           | 2         | 0.1%    |
| NEC Computers       | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 28        | 1.38%   |
| HP Pavilion dv6                        | 17        | 0.84%   |
| HP Notebook                            | 17        | 0.84%   |
| Dell Latitude D630                     | 11        | 0.54%   |
| HP 15                                  | 10        | 0.49%   |
| HP Pavilion 15                         | 9         | 0.44%   |
| Dell Latitude E6430                    | 9         | 0.44%   |
| HP Pavilion dv7                        | 7         | 0.35%   |
| HP Pavilion dv6500                     | 7         | 0.35%   |
| HP Pavilion g6                         | 6         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.3%    |
| HP EliteBook 840 G3                    | 5         | 0.25%   |
| Dell Latitude E6520                    | 5         | 0.25%   |
| ASUS 1005HA                            | 5         | 0.25%   |
| Acer Aspire one                        | 5         | 0.25%   |
| Acer AO751h                            | 5         | 0.25%   |
| Positivo Mobile                        | 4         | 0.2%    |
| HP Pavilion g7                         | 4         | 0.2%    |
| HP Laptop 15-bw0xx                     | 4         | 0.2%    |
| HP G62                                 | 4         | 0.2%    |
| HP G42                                 | 4         | 0.2%    |
| HP EliteBook 8560p                     | 4         | 0.2%    |
| HP Compaq 6730s                        | 4         | 0.2%    |
| HP 255 G7 Notebook PC                  | 4         | 0.2%    |
| Dell Studio 1535                       | 4         | 0.2%    |
| Dell Latitude E6400                    | 4         | 0.2%    |
| Dell Latitude E6330                    | 4         | 0.2%    |
| Dell Inspiron 7520                     | 4         | 0.2%    |
| Dell Inspiron 1545                     | 4         | 0.2%    |
| Dell Inspiron 1525                     | 4         | 0.2%    |
| Dell Inspiron 15-3567                  | 4         | 0.2%    |
| ASUS X553MA                            | 4         | 0.2%    |
| ASUS T100HAN                           | 4         | 0.2%    |
| ASUS K53SC                             | 4         | 0.2%    |
| Acer Aspire 9300                       | 4         | 0.2%    |
| Acer Aspire 7720                       | 4         | 0.2%    |
| Toshiba Satellite C650                 | 3         | 0.15%   |
| Toshiba Satellite A100                 | 3         | 0.15%   |
| Toshiba PORTEGE R930                   | 3         | 0.15%   |
| Samsung N150P/N210P/N220P              | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 212       | 10.47%  |
| Acer Aspire             | 135       | 6.67%   |
| Dell Latitude           | 112       | 5.53%   |
| HP Pavilion             | 103       | 5.09%   |
| Dell Inspiron           | 91        | 4.49%   |
| Toshiba Satellite       | 81        | 4%      |
| Lenovo IdeaPad          | 64        | 3.16%   |
| HP EliteBook            | 54        | 2.67%   |
| HP Compaq               | 45        | 2.22%   |
| HP ProBook              | 43        | 2.12%   |
| HP Laptop               | 37        | 1.83%   |
| ASUS VivoBook           | 32        | 1.58%   |
| Unknown                 | 28        | 1.38%   |
| HP Notebook             | 18        | 0.89%   |
| Dell XPS                | 16        | 0.79%   |
| Dell Vostro             | 16        | 0.79%   |
| Fujitsu Siemens AMILO   | 15        | 0.74%   |
| Acer Extensa            | 15        | 0.74%   |
| Packard Bell EasyNote   | 14        | 0.69%   |
| Dell Precision          | 14        | 0.69%   |
| HP Mini                 | 11        | 0.54%   |
| HP 255                  | 11        | 0.54%   |
| HP 15                   | 11        | 0.54%   |
| Fujitsu LIFEBOOK        | 11        | 0.54%   |
| HP Presario             | 10        | 0.49%   |
| Acer TravelMate         | 10        | 0.49%   |
| HP Stream               | 8         | 0.4%    |
| HP 250                  | 8         | 0.4%    |
| Acer Swift              | 8         | 0.4%    |
| HP ZBook                | 7         | 0.35%   |
| HP ENVY                 | 7         | 0.35%   |
| Dell Studio             | 7         | 0.35%   |
| Acer Nitro              | 7         | 0.35%   |
| Toshiba PORTEGE         | 6         | 0.3%    |
| IBM ThinkPad            | 6         | 0.3%    |
| ASUS ASUS               | 6         | 0.3%    |
| Fujitsu Siemens ESPRIMO | 5         | 0.25%   |
| ASUS ROG                | 5         | 0.25%   |
| ASUS 1005HA             | 5         | 0.25%   |
| Acer AO751h             | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 180       | 8.89%   |
| 2012    | 174       | 8.59%   |
| 2008    | 172       | 8.49%   |
| 2010    | 160       | 7.9%    |
| 2007    | 148       | 7.31%   |
| 2013    | 140       | 6.91%   |
| 2019    | 126       | 6.22%   |
| 2009    | 118       | 5.83%   |
| 2014    | 105       | 5.19%   |
| 2020    | 104       | 5.14%   |
| 2017    | 103       | 5.09%   |
| 2018    | 98        | 4.84%   |
| 2016    | 93        | 4.59%   |
| 2015    | 84        | 4.15%   |
| 2021    | 79        | 3.9%    |
| 2006    | 79        | 3.9%    |
| 2005    | 34        | 1.68%   |
| 2022    | 10        | 0.49%   |
| 2003    | 8         | 0.4%    |
| 2004    | 7         | 0.35%   |
| Unknown | 2         | 0.1%    |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2025      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1884      | 92.58%  |
| Enabled  | 151       | 7.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2010      | 99.26%  |
| Yes  | 15        | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 600       | 29.3%   |
| 4.01-8.0    | 439       | 21.44%  |
| 1.01-2.0    | 298       | 14.55%  |
| 8.01-16.0   | 222       | 10.84%  |
| 16.01-24.0  | 187       | 9.13%   |
| 0.51-1.0    | 109       | 5.32%   |
| 2.01-3.0    | 92        | 4.49%   |
| 32.01-64.0  | 65        | 3.17%   |
| 64.01-256.0 | 15        | 0.73%   |
| 24.01-32.0  | 14        | 0.68%   |
| 0.01-0.5    | 7         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 922       | 41.7%   |
| 0.51-1.0   | 484       | 21.89%  |
| 2.01-3.0   | 406       | 18.36%  |
| 4.01-8.0   | 156       | 7.06%   |
| 3.01-4.0   | 129       | 5.83%   |
| 0.01-0.5   | 72        | 3.26%   |
| 8.01-16.0  | 37        | 1.67%   |
| 16.01-24.0 | 3         | 0.14%   |
| 24.01-32.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1560      | 75.69%  |
| 2      | 420       | 20.38%  |
| 3      | 46        | 2.23%   |
| 0      | 26        | 1.26%   |
| 4      | 6         | 0.29%   |
| 5      | 2         | 0.1%    |
| 7      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1047      | 51.6%   |
| No        | 982       | 48.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1784      | 88.01%  |
| No        | 243       | 11.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1973      | 97.24%  |
| No        | 56        | 2.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1228      | 59.87%  |
| No        | 823       | 40.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 287       | 14.08%  |
| Germany      | 261       | 12.81%  |
| France       | 187       | 9.18%   |
| Italy        | 172       | 8.44%   |
| Brazil       | 118       | 5.79%   |
| Russia       | 112       | 5.5%    |
| UK           | 79        | 3.88%   |
| Spain        | 72        | 3.53%   |
| Canada       | 66        | 3.24%   |
| Netherlands  | 47        | 2.31%   |
| Poland       | 42        | 2.06%   |
| Czechia      | 32        | 1.57%   |
| Australia    | 32        | 1.57%   |
| Mexico       | 29        | 1.42%   |
| Ukraine      | 28        | 1.37%   |
| Belgium      | 27        | 1.32%   |
| India        | 25        | 1.23%   |
| Argentina    | 25        | 1.23%   |
| Portugal     | 24        | 1.18%   |
| Finland      | 22        | 1.08%   |
| Indonesia    | 19        | 0.93%   |
| Hungary      | 19        | 0.93%   |
| Greece       | 18        | 0.88%   |
| Sweden       | 17        | 0.83%   |
| Turkey       | 16        | 0.79%   |
| Japan        | 16        | 0.79%   |
| Bulgaria     | 15        | 0.74%   |
| Romania      | 12        | 0.59%   |
| Austria      | 12        | 0.59%   |
| Slovakia     | 11        | 0.54%   |
| Norway       | 11        | 0.54%   |
| Iran         | 10        | 0.49%   |
| Colombia     | 9         | 0.44%   |
| Chile        | 9         | 0.44%   |
| Switzerland  | 8         | 0.39%   |
| Denmark      | 8         | 0.39%   |
| South Africa | 7         | 0.34%   |
| Venezuela    | 6         | 0.29%   |
| Serbia       | 6         | 0.29%   |
| Lithuania    | 6         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 30        | 1.4%    |
| Moscow            | 24        | 1.12%   |
| Berlin            | 24        | 1.12%   |
| Rome              | 20        | 0.93%   |
| Milan             | 20        | 0.93%   |
| St Petersburg     | 17        | 0.79%   |
| Québec           | 17        | 0.79%   |
| Athens            | 16        | 0.74%   |
| Warsaw            | 15        | 0.7%    |
| Munich            | 13        | 0.61%   |
| Sao Paulo         | 12        | 0.56%   |
| Prague            | 12        | 0.56%   |
| Helsinki          | 11        | 0.51%   |
| Hamburg           | 11        | 0.51%   |
| Amsterdam         | 11        | 0.51%   |
| Madrid            | 10        | 0.47%   |
| Kyiv              | 10        | 0.47%   |
| Budapest          | 10        | 0.47%   |
| Barcelona         | 10        | 0.47%   |
| Rio de Janeiro    | 9         | 0.42%   |
| Sydney            | 8         | 0.37%   |
| Leipzig           | 8         | 0.37%   |
| Karlsruhe         | 8         | 0.37%   |
| Genoa             | 8         | 0.37%   |
| Ankara            | 8         | 0.37%   |
| Yokohama          | 7         | 0.33%   |
| Turin             | 7         | 0.33%   |
| Sofia             | 7         | 0.33%   |
| Melbourne         | 7         | 0.33%   |
| Lisbon            | 7         | 0.33%   |
| Frankfurt am Main | 7         | 0.33%   |
| Vienna            | 6         | 0.28%   |
| Toronto           | 6         | 0.28%   |
| Tehran            | 6         | 0.28%   |
| Stuttgart         | 6         | 0.28%   |
| Seattle           | 6         | 0.28%   |
| Rostov-on-Don     | 6         | 0.28%   |
| Oryol             | 6         | 0.28%   |
| Clichy-sous-Bois  | 6         | 0.28%   |
| Bucharest         | 6         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 365       | 445    | 15.4%   |
| Samsung Electronics | 318       | 391    | 13.42%  |
| WDC                 | 308       | 375    | 13%     |
| Toshiba             | 225       | 256    | 9.49%   |
| Unknown             | 159       | 206    | 6.71%   |
| Hitachi             | 152       | 180    | 6.41%   |
| Kingston            | 95        | 125    | 4.01%   |
| SanDisk             | 83        | 99     | 3.5%    |
| HGST                | 80        | 91     | 3.38%   |
| SK hynix            | 61        | 73     | 2.57%   |
| Crucial             | 56        | 66     | 2.36%   |
| Fujitsu             | 55        | 70     | 2.32%   |
| Intel               | 51        | 69     | 2.15%   |
| Micron Technology   | 30        | 32     | 1.27%   |
| A-DATA Technology   | 29        | 39     | 1.22%   |
| China               | 25        | 27     | 1.05%   |
| Transcend           | 15        | 16     | 0.63%   |
| Apple               | 14        | 21     | 0.59%   |
| PNY                 | 12        | 14     | 0.51%   |
| OCZ                 | 12        | 13     | 0.51%   |
| LITEONIT            | 12        | 15     | 0.51%   |
| LITEON              | 12        | 14     | 0.51%   |
| KIOXIA              | 11        | 13     | 0.46%   |
| Phison              | 10        | 21     | 0.42%   |
| Intenso             | 9         | 9      | 0.38%   |
| Unknown             | 9         | 9      | 0.38%   |
| Apacer              | 8         | 10     | 0.34%   |
| SPCC                | 7         | 9      | 0.3%    |
| KingSpec            | 7         | 9      | 0.3%    |
| JMicron Technology  | 7         | 6      | 0.3%    |
| Patriot             | 6         | 6      | 0.25%   |
| IBM/Hitachi         | 6         | 6      | 0.25%   |
| Silicon Motion      | 5         | 5      | 0.21%   |
| Netac               | 5         | 7      | 0.21%   |
| KingDian            | 5         | 7      | 0.21%   |
| HUAWEI              | 5         | 5      | 0.21%   |
| Hewlett-Packard     | 5         | 5      | 0.21%   |
| USB3.0              | 4         | 5      | 0.17%   |
| Smartbuy            | 4         | 4      | 0.17%   |
| Pioneer             | 4         | 4      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 40        | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 28        | 1.15%   |
| Toshiba MQ01ABF050 500GB               | 23        | 0.94%   |
| Seagate ST500LT012-1DG142 500GB        | 23        | 0.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 23        | 0.94%   |
| Toshiba MQ01ABD100 1TB                 | 21        | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB         | 20        | 0.82%   |
| Kingston SA400S37480G 480GB SSD        | 20        | 0.82%   |
| HGST HTS541010A9E680 1TB               | 19        | 0.78%   |
| Unknown MMC Card  64GB                 | 18        | 0.74%   |
| HGST HTS721010A9E630 1TB               | 18        | 0.74%   |
| Seagate ST9500325AS 500GB              | 17        | 0.7%    |
| Seagate ST9320325AS 320GB              | 16        | 0.66%   |
| Seagate ST500LT012-9WS142 500GB        | 16        | 0.66%   |
| Kingston SA400S37240G 240GB SSD        | 16        | 0.66%   |
| Samsung SSD 850 EVO 250GB              | 14        | 0.57%   |
| Unknown MMC Card  128GB                | 13        | 0.53%   |
| Samsung SSD 860 EVO 500GB              | 13        | 0.53%   |
| Kingston SA400S37120G 120GB SSD        | 13        | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB               | 12        | 0.49%   |
| Unknown MMC Card  16GB                 | 12        | 0.49%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 11        | 0.45%   |
| Toshiba MQ04ABF100 1TB                 | 11        | 0.45%   |
| SK hynix NVMe SSD Drive 256GB          | 11        | 0.45%   |
| Seagate ST9250315AS 250GB              | 11        | 0.45%   |
| Seagate ST9160310AS 160GB              | 11        | 0.45%   |
| HGST HTS545050A7E680 500GB             | 11        | 0.45%   |
| Crucial CT240BX500SSD1 240GB           | 11        | 0.45%   |
| Samsung SSD 850 EVO 500GB              | 10        | 0.41%   |
| Samsung NVMe SSD Drive 512GB           | 10        | 0.41%   |
| HGST HTS725050A7E630 500GB             | 10        | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 9         | 0.37%   |
| Seagate ST9160314AS 160GB              | 9         | 0.37%   |
| Samsung SSD 860 EVO 1TB                | 9         | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 9         | 0.37%   |
| Hitachi HTS543232A7A384 320GB          | 9         | 0.37%   |
| HGST HTS545050A7E380 500GB             | 9         | 0.37%   |
| Unknown                                | 9         | 0.37%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 8         | 0.33%   |
| Unknown SD/MMC/MS PRO 64GB             | 8         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 359       | 436    | 30.95%  |
| WDC                 | 243       | 299    | 20.95%  |
| Toshiba             | 185       | 213    | 15.95%  |
| Hitachi             | 152       | 180    | 13.1%   |
| HGST                | 80        | 91     | 6.9%    |
| Samsung Electronics | 55        | 64     | 4.74%   |
| Fujitsu             | 53        | 68     | 4.57%   |
| Unknown             | 8         | 8      | 0.69%   |
| IBM/Hitachi         | 6         | 6      | 0.52%   |
| USB3.0              | 4         | 5      | 0.34%   |
| Pioneer             | 3         | 3      | 0.26%   |
| ASMT                | 3         | 5      | 0.26%   |
| HGST HTS            | 2         | 2      | 0.17%   |
| Intenso             | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| CLOVER              | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |
| Apricorn            | 1         | 2      | 0.09%   |
| ACASIS              | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 167       | 210    | 23.96%  |
| Kingston            | 85        | 113    | 12.2%   |
| SanDisk             | 59        | 72     | 8.46%   |
| Crucial             | 55        | 65     | 7.89%   |
| A-DATA Technology   | 26        | 36     | 3.73%   |
| China               | 25        | 27     | 3.59%   |
| WDC                 | 24        | 25     | 3.44%   |
| Micron Technology   | 20        | 21     | 2.87%   |
| Intel               | 20        | 29     | 2.87%   |
| Toshiba             | 17        | 18     | 2.44%   |
| SK hynix            | 16        | 16     | 2.3%    |
| Transcend           | 15        | 15     | 2.15%   |
| PNY                 | 12        | 14     | 1.72%   |
| OCZ                 | 12        | 13     | 1.72%   |
| LITEONIT            | 12        | 15     | 1.72%   |
| LITEON              | 12        | 14     | 1.72%   |
| Apple               | 9         | 13     | 1.29%   |
| Intenso             | 8         | 8      | 1.15%   |
| SPCC                | 7         | 9      | 1%      |
| Apacer              | 7         | 9      | 1%      |
| Patriot             | 6         | 6      | 0.86%   |
| KingSpec            | 6         | 8      | 0.86%   |
| Unknown             | 5         | 6      | 0.72%   |
| KingDian            | 5         | 7      | 0.72%   |
| Smartbuy            | 4         | 4      | 0.57%   |
| Netac               | 4         | 6      | 0.57%   |
| JMicron Technology  | 4         | 4      | 0.57%   |
| Hewlett-Packard     | 4         | 5      | 0.57%   |
| TO Exter            | 3         | 3      | 0.43%   |
| Plextor             | 3         | 4      | 0.43%   |
| Drevo               | 3         | 3      | 0.43%   |
| Zheino              | 2         | 2      | 0.29%   |
| TCSUNBOW            | 2         | 2      | 0.29%   |
| Mushkin             | 2         | 2      | 0.29%   |
| INNOVATION IT       | 2         | 2      | 0.29%   |
| GOODRAM             | 2         | 2      | 0.29%   |
| Dogfish             | 2         | 5      | 0.29%   |
| WANGCHU             | 1         | 1      | 0.14%   |
| Vaseky              | 1         | 2      | 0.14%   |
| Teclast             | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1124      | 1388   | 49.13%  |
| SSD     | 648       | 852    | 28.32%  |
| NVMe    | 326       | 401    | 14.25%  |
| MMC     | 158       | 203    | 6.91%   |
| Unknown | 32        | 35     | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1650      | 2176   | 74.49%  |
| NVMe | 323       | 397    | 14.58%  |
| MMC  | 158       | 203    | 7.13%   |
| SAS  | 84        | 103    | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1365      | 1750   | 77.34%  |
| 0.51-1.0   | 354       | 428    | 20.06%  |
| 1.01-2.0   | 30        | 36     | 1.7%    |
| 3.01-4.0   | 12        | 17     | 0.68%   |
| 4.01-10.0  | 3         | 8      | 0.17%   |
| 0          | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 724       | 34.56%  |
| 251-500        | 540       | 25.78%  |
| 501-1000       | 249       | 11.89%  |
| 51-100         | 210       | 10.02%  |
| 21-50          | 151       | 7.21%   |
| 1-20           | 101       | 4.82%   |
| 1001-2000      | 76        | 3.63%   |
| 2001-3000      | 18        | 0.86%   |
| More than 3000 | 14        | 0.67%   |
| Unknown        | 12        | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1014      | 46.6%   |
| 21-50          | 395       | 18.15%  |
| 101-250        | 265       | 12.18%  |
| 51-100         | 249       | 11.44%  |
| 251-500        | 134       | 6.16%   |
| 501-1000       | 76        | 3.49%   |
| 1001-2000      | 22        | 1.01%   |
| Unknown        | 12        | 0.55%   |
| 2001-3000      | 5         | 0.23%   |
| More than 3000 | 4         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 7      | 5.38%   |
| Toshiba MQ01ABD100 1TB             | 5         | 6      | 3.85%   |
| Seagate ST9500325AS 500GB          | 5         | 7      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB    | 5         | 5      | 3.85%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 2.31%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 2.31%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 2      | 1.54%   |
| Seagate ST9500423AS 500GB          | 2         | 2      | 1.54%   |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.54%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 1.54%   |
| Hitachi HTS725050A9A364 500GB      | 2         | 3      | 1.54%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.54%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 1.54%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.77%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 2      | 0.77%   |
| WDC WD7500BPVT-24HXZT1 752GB       | 1         | 2      | 0.77%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 1      | 0.77%   |
| WDC WD5000BEVT-60ZAT1 500GB        | 1         | 1      | 0.77%   |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 1      | 0.77%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 1         | 1      | 0.77%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 1      | 0.77%   |
| WDC WD3200BEKT-75PVMT0 320GB       | 1         | 1      | 0.77%   |
| WDC WD1600BJKT-75F4T0 160GB        | 1         | 1      | 0.77%   |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.77%   |
| WDC WD10SPCX-24HWST1 1TB           | 1         | 1      | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 2      | 0.77%   |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 1      | 0.77%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.77%   |
| Toshiba MQ01ACF050 500GB           | 1         | 1      | 0.77%   |
| Toshiba MQ01ABD032 320GB           | 1         | 1      | 0.77%   |
| Toshiba MK7575GSX 752GB            | 1         | 1      | 0.77%   |
| Toshiba MK7559GSXP 752GB           | 1         | 2      | 0.77%   |
| Toshiba MK5076GSX 500GB            | 1         | 1      | 0.77%   |
| Toshiba MK5065GSXN 500GB           | 1         | 3      | 0.77%   |
| Toshiba MK5065GSX 500GB            | 1         | 1      | 0.77%   |
| Toshiba MK5059GSXP 500GB           | 1         | 1      | 0.77%   |
| Toshiba MK3276GSX -63 320GB        | 1         | 2      | 0.77%   |
| Toshiba MK3259GSXP 320GB           | 1         | 1      | 0.77%   |
| Toshiba MK2552GSX 250GB            | 1         | 1      | 0.77%   |
| Toshiba MK2546GSX 250GB            | 1         | 1      | 0.77%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 42     | 29.23%  |
| Toshiba             | 18        | 23     | 13.85%  |
| WDC                 | 16        | 19     | 12.31%  |
| Hitachi             | 15        | 17     | 11.54%  |
| HGST                | 8         | 9      | 6.15%   |
| Samsung Electronics | 6         | 6      | 4.62%   |
| Fujitsu             | 4         | 5      | 3.08%   |
| SK hynix            | 3         | 3      | 2.31%   |
| SanDisk             | 2         | 2      | 1.54%   |
| OCZ                 | 2         | 2      | 1.54%   |
| Micron Technology   | 2         | 2      | 1.54%   |
| Kingston            | 2         | 4      | 1.54%   |
| Intel               | 2         | 2      | 1.54%   |
| A-DATA Technology   | 2         | 3      | 1.54%   |
| SSSTC               | 1         | 1      | 0.77%   |
| Neo Forza           | 1         | 1      | 0.77%   |
| Mushkin             | 1         | 1      | 0.77%   |
| LITEON              | 1         | 1      | 0.77%   |
| LDLC                | 1         | 1      | 0.77%   |
| KingDian            | 1         | 3      | 0.77%   |
| Drevo               | 1         | 1      | 0.77%   |
| Crucial             | 1         | 1      | 0.77%   |
| China               | 1         | 1      | 0.77%   |
| Apple               | 1         | 1      | 0.77%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 42     | 37.62%  |
| Toshiba             | 18        | 23     | 17.82%  |
| WDC                 | 15        | 18     | 14.85%  |
| Hitachi             | 15        | 17     | 14.85%  |
| HGST                | 8         | 9      | 7.92%   |
| Fujitsu             | 4         | 5      | 3.96%   |
| Samsung Electronics | 3         | 3      | 2.97%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 101       | 117    | 77.69%  |
| SSD  | 27        | 32     | 20.77%  |
| NVMe | 2         | 2      | 1.54%   |

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
| Detected | 1416      | 2019   | 67.78%  |
| Works    | 544       | 709    | 26.04%  |
| Malfunc  | 129       | 151    | 6.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1482      | 69.58%  |
| AMD                              | 259       | 12.16%  |
| Samsung Electronics              | 107       | 5.02%   |
| SanDisk                          | 63        | 2.96%   |
| SK hynix                         | 40        | 1.88%   |
| Silicon Integrated Systems [SiS] | 31        | 1.46%   |
| Nvidia                           | 30        | 1.41%   |
| Toshiba America Info Systems     | 21        | 0.99%   |
| KIOXIA                           | 14        | 0.66%   |
| VIA Technologies                 | 13        | 0.61%   |
| Phison Electronics               | 12        | 0.56%   |
| Kingston Technology Company      | 11        | 0.52%   |
| Micron Technology                | 9         | 0.42%   |
| Silicon Motion                   | 7         | 0.33%   |
| Apple                            | 5         | 0.23%   |
| ULi Electronics                  | 4         | 0.19%   |
| JMicron Technology               | 4         | 0.19%   |
| Silicon Image                    | 3         | 0.14%   |
| Realtek Semiconductor            | 3         | 0.14%   |
| Lenovo                           | 3         | 0.14%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Seagate Technology               | 2         | 0.09%   |
| Micron/Crucial Technology        | 2         | 0.09%   |
| Lite-On Technology               | 1         | 0.05%   |
| INNOGRIT                         | 1         | 0.05%   |
| ADATA Technology                 | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 174       | 7.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 161       | 6.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 119       | 4.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 114       | 4.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 112       | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 111       | 4.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 98        | 3.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 88        | 3.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 75        | 3.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 61        | 2.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 54        | 2.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 54        | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 51        | 2.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 51        | 2.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 51        | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 43        | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 42        | 1.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 40        | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 35        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 35        | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 33        | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 30        | 1.22%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 29        | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 27        | 1.1%    |
| Samsung NVMe SSD Controller 980                                                  | 26        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 25        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 23        | 0.94%   |
| AMD IXP SB4x0 IDE Controller                                                     | 22        | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 0.85%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 20        | 0.81%   |
| AMD SB600 IDE                                                                    | 20        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 19        | 0.77%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 17        | 0.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 17        | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 0.57%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 14        | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 0.57%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 14        | 0.57%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 13        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1428      | 61.45%  |
| IDE  | 459       | 19.75%  |
| NVMe | 318       | 13.68%  |
| RAID | 119       | 5.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1701      | 84%     |
| AMD          | 322       | 15.9%   |
| CentaurHauls | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 29        | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 22        | 1.08%   |
| Intel Atom CPU N450 @ 1.66GHz               | 21        | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 19        | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 19        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 18        | 0.89%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 18        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 18        | 0.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 18        | 0.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 18        | 0.89%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 17        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 16        | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 16        | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 15        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 15        | 0.74%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 15        | 0.74%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 15        | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 15        | 0.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 15        | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 14        | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 14        | 0.69%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 14        | 0.69%   |
| Intel Pentium M processor 1.73GHz           | 13        | 0.64%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 13        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 13        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 13        | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 13        | 0.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 13        | 0.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 13        | 0.64%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz        | 13        | 0.64%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 13        | 0.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 12        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 12        | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 12        | 0.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 12        | 0.59%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 12        | 0.59%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 12        | 0.59%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 12        | 0.59%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 12        | 0.59%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 11        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 377       | 18.59%  |
| Intel Core i7           | 311       | 15.34%  |
| Intel Core 2 Duo        | 190       | 9.37%   |
| Intel Core i3           | 161       | 7.94%   |
| Intel Celeron           | 157       | 7.74%   |
| Intel Atom              | 139       | 6.85%   |
| Intel Pentium           | 63        | 3.11%   |
| Other                   | 60        | 2.96%   |
| Intel Genuine           | 53        | 2.61%   |
| Intel Pentium Dual-Core | 39        | 1.92%   |
| Intel Pentium Dual      | 39        | 1.92%   |
| AMD Ryzen 5             | 37        | 1.82%   |
| Intel Core 2            | 30        | 1.48%   |
| Intel Pentium M         | 28        | 1.38%   |
| AMD Ryzen 7             | 27        | 1.33%   |
| AMD A8                  | 27        | 1.33%   |
| AMD E1                  | 26        | 1.28%   |
| Intel Celeron M         | 24        | 1.18%   |
| AMD A6                  | 23        | 1.13%   |
| AMD Turion 64 X2 Mobile | 20        | 0.99%   |
| AMD E2                  | 15        | 0.74%   |
| AMD E                   | 15        | 0.74%   |
| AMD A4                  | 14        | 0.69%   |
| AMD Ryzen 7 PRO         | 12        | 0.59%   |
| AMD Turion 64 Mobile    | 11        | 0.54%   |
| AMD Ryzen 3             | 8         | 0.39%   |
| AMD Mobile Sempron      | 8         | 0.39%   |
| AMD Athlon              | 8         | 0.39%   |
| Intel Pentium Silver    | 7         | 0.35%   |
| Intel Pentium 4         | 7         | 0.35%   |
| AMD Athlon 64 X2        | 7         | 0.35%   |
| AMD A10                 | 7         | 0.35%   |
| Intel Core Duo          | 6         | 0.3%    |
| Intel Celeron Dual-Core | 5         | 0.25%   |
| AMD C-60                | 5         | 0.25%   |
| AMD Sempron             | 4         | 0.2%    |
| AMD Ryzen 9             | 4         | 0.2%    |
| AMD Athlon X2           | 4         | 0.2%    |
| Intel Xeon              | 3         | 0.15%   |
| Intel Mobile Pentium 4  | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1239      | 61.15%  |
| 4      | 458       | 22.61%  |
| 1      | 216       | 10.66%  |
| 6      | 68        | 3.36%   |
| 8      | 43        | 2.12%   |
| 16     | 1         | 0.05%   |
| 14     | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2025      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1126      | 55.6%   |
| 1      | 899       | 44.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1864      | 92%     |
| 32-bit         | 162       | 8%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 293       | 14.2%   |
| 0x206a7    | 149       | 7.22%   |
| 0x306a9    | 136       | 6.59%   |
| 0x6fd      | 105       | 5.09%   |
| 0x1067a    | 100       | 4.84%   |
| 0x20655    | 69        | 3.34%   |
| 0x40651    | 61        | 2.96%   |
| 0x406e3    | 47        | 2.28%   |
| 0x10676    | 47        | 2.28%   |
| 0x30678    | 46        | 2.23%   |
| 0x106ca    | 43        | 2.08%   |
| 0x806ea    | 41        | 1.99%   |
| 0x306d4    | 40        | 1.94%   |
| 0x306c3    | 40        | 1.94%   |
| 0x806ec    | 39        | 1.89%   |
| 0x406c4    | 39        | 1.89%   |
| 0x20652    | 39        | 1.89%   |
| 0x106c2    | 39        | 1.89%   |
| 0x806c1    | 35        | 1.7%    |
| 0x806e9    | 34        | 1.65%   |
| 0x6d8      | 34        | 1.65%   |
| 0x6e8      | 33        | 1.6%    |
| 0x906ea    | 32        | 1.55%   |
| 0x6f6      | 28        | 1.36%   |
| 0x05000119 | 27        | 1.31%   |
| 0xa0652    | 24        | 1.16%   |
| 0x406c3    | 24        | 1.16%   |
| 0x07030105 | 23        | 1.11%   |
| 0x6fb      | 21        | 1.02%   |
| 0x6ec      | 21        | 1.02%   |
| 0x10661    | 17        | 0.82%   |
| 0x0700010f | 17        | 0.82%   |
| 0x706a1    | 16        | 0.78%   |
| 0x08108102 | 16        | 0.78%   |
| 0x08108109 | 15        | 0.73%   |
| 0x906e9    | 14        | 0.68%   |
| 0x706e5    | 14        | 0.68%   |
| 0x30661    | 13        | 0.63%   |
| 0x03000027 | 13        | 0.63%   |
| 0x506e3    | 11        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 223       | 11%     |
| Core             | 184       | 9.08%   |
| Penryn           | 161       | 7.94%   |
| SandyBridge      | 160       | 7.89%   |
| IvyBridge        | 150       | 7.4%    |
| Westmere         | 125       | 6.17%   |
| Silvermont       | 117       | 5.77%   |
| Haswell          | 112       | 5.53%   |
| Bonnell          | 105       | 5.18%   |
| P6               | 95        | 4.69%   |
| Skylake          | 72        | 3.55%   |
| K8 Hammer        | 53        | 2.61%   |
| Broadwell        | 45        | 2.22%   |
| TigerLake        | 42        | 2.07%   |
| Bobcat           | 39        | 1.92%   |
| Zen+             | 34        | 1.68%   |
| Puma             | 32        | 1.58%   |
| Goldmont plus    | 28        | 1.38%   |
| CometLake        | 26        | 1.28%   |
| Zen 2            | 25        | 1.23%   |
| IceLake          | 24        | 1.18%   |
| Excavator        | 24        | 1.18%   |
| Jaguar           | 21        | 1.04%   |
| Goldmont         | 15        | 0.74%   |
| Unknown          | 15        | 0.74%   |
| Zen 3            | 14        | 0.69%   |
| Zen              | 14        | 0.69%   |
| K10 Llano        | 14        | 0.69%   |
| Piledriver       | 12        | 0.59%   |
| K8 & K10 hybrid  | 11        | 0.54%   |
| NetBurst         | 10        | 0.49%   |
| K10              | 10        | 0.49%   |
| Steamroller      | 5         | 0.25%   |
| Nehalem          | 5         | 0.25%   |
| Tremont          | 2         | 0.1%    |
| K6               | 2         | 0.1%    |
| Alderlake Hybrid | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1441      | 60.85%  |
| AMD                              | 471       | 19.89%  |
| Nvidia                           | 423       | 17.86%  |
| Silicon Integrated Systems [SiS] | 20        | 0.84%   |
| VIA Technologies                 | 12        | 0.51%   |
| S3 Graphics                      | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 146       | 5.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 140       | 5.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 114       | 4.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 92        | 3.6%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 84        | 3.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 3.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 66        | 2.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 53        | 2.07%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 51        | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 51        | 1.99%   |
| Intel UHD Graphics 620                                                                   | 48        | 1.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 45        | 1.76%   |
| Intel HD Graphics 620                                                                    | 43        | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 41        | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 37        | 1.45%   |
| Intel HD Graphics 5500                                                                   | 36        | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 1.37%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 33        | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 0.98%   |
| AMD Renoir                                                                               | 25        | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 0.86%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 0.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.7%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 17        | 0.66%   |
| Intel HD Graphics 630                                                                    | 16        | 0.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 0.59%   |
| Intel HD Graphics 500                                                                    | 15        | 0.59%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.59%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 14        | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.55%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 14        | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 0.55%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 13        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1109      | 54.77%  |
| 1 x AMD         | 356       | 17.58%  |
| Intel + Nvidia  | 251       | 12.4%   |
| 1 x Nvidia      | 156       | 7.7%    |
| Intel + AMD     | 74        | 3.65%   |
| 2 x AMD         | 25        | 1.23%   |
| 1 x SiS         | 20        | 0.99%   |
| AMD + Nvidia    | 16        | 0.79%   |
| 1 x VIA         | 12        | 0.59%   |
| Other           | 5         | 0.25%   |
| 1 x S3 Graphics | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1761      | 86.62%  |
| Proprietary | 197       | 9.69%   |
| Unknown     | 75        | 3.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1158      | 56.54%  |
| 0.01-0.5   | 434       | 21.19%  |
| 1.01-2.0   | 216       | 10.55%  |
| 0.51-1.0   | 123       | 6.01%   |
| 3.01-4.0   | 81        | 3.96%   |
| 5.01-6.0   | 20        | 0.98%   |
| 7.01-8.0   | 8         | 0.39%   |
| 2.01-3.0   | 5         | 0.24%   |
| 8.01-16.0  | 3         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 408       | 19.3%   |
| LG Display              | 322       | 15.23%  |
| Samsung Electronics     | 300       | 14.19%  |
| Chimei Innolux          | 205       | 9.7%    |
| BOE                     | 184       | 8.7%    |
| Chi Mei Optoelectronics | 94        | 4.45%   |
| LG Philips              | 68        | 3.22%   |
| Lenovo                  | 66        | 3.12%   |
| Apple                   | 37        | 1.75%   |
| HannStar                | 34        | 1.61%   |
| Dell                    | 33        | 1.56%   |
| Goldstar                | 32        | 1.51%   |
| InfoVision              | 26        | 1.23%   |
| Sharp                   | 25        | 1.18%   |
| CPT                     | 23        | 1.09%   |
| Acer                    | 19        | 0.9%    |
| PANDA                   | 16        | 0.76%   |
| BenQ                    | 16        | 0.76%   |
| Philips                 | 15        | 0.71%   |
| Hewlett-Packard         | 15        | 0.71%   |
| Ancor Communications    | 14        | 0.66%   |
| Toshiba                 | 11        | 0.52%   |
| Sony                    | 11        | 0.52%   |
| ViewSonic               | 10        | 0.47%   |
| Quanta Display          | 10        | 0.47%   |
| Iiyama                  | 8         | 0.38%   |
| CSO                     | 8         | 0.38%   |
| Seiko/Epson             | 7         | 0.33%   |
| InnoLux Display         | 7         | 0.33%   |
| AOC                     | 7         | 0.33%   |
| Panasonic               | 5         | 0.24%   |
| Nvidia                  | 5         | 0.24%   |
| LPL                     | 5         | 0.24%   |
| LGD                     | 4         | 0.19%   |
| Fujitsu Siemens         | 4         | 0.19%   |
| Vizio                   | 3         | 0.14%   |
| Lenovo Group Limited    | 3         | 0.14%   |
| KDC                     | 3         | 0.14%   |
| IBM                     | 3         | 0.14%   |
| Eizo                    | 3         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 1.03%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 20        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.75%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.75%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.52%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.52%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.47%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.42%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.33%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 7         | 0.33%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.33%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 7         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.28%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 6         | 0.28%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 6         | 0.28%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 6         | 0.28%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 6         | 0.28%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch                  | 6         | 0.28%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 0.28%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 6         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 6         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 732       | 35.9%   |
| 1920x1080 (FHD)    | 577       | 28.3%   |
| 1280x800 (WXGA)    | 238       | 11.67%  |
| 1600x900 (HD+)     | 127       | 6.23%   |
| 1440x900 (WXGA+)   | 78        | 3.83%   |
| 1024x600           | 65        | 3.19%   |
| 3840x2160 (4K)     | 47        | 2.31%   |
| 1680x1050 (WSXGA+) | 29        | 1.42%   |
| 1280x1024 (SXGA)   | 23        | 1.13%   |
| 1920x1200 (WUXGA)  | 22        | 1.08%   |
| 2560x1440 (QHD)    | 19        | 0.93%   |
| 1024x768 (XGA)     | 16        | 0.78%   |
| 2560x1600          | 7         | 0.34%   |
| 1360x768           | 7         | 0.34%   |
| 1400x1050          | 5         | 0.25%   |
| 3840x1080          | 4         | 0.2%    |
| 3200x1800 (QHD+)   | 4         | 0.2%    |
| 2880x1800          | 4         | 0.2%    |
| Unknown            | 4         | 0.2%    |
| 2288x1287          | 3         | 0.15%   |
| 2160x1440          | 3         | 0.15%   |
| 1920x540           | 3         | 0.15%   |
| 3840x2400          | 2         | 0.1%    |
| 2560x1080          | 2         | 0.1%    |
| 1600x1200          | 2         | 0.1%    |
| 800x480            | 1         | 0.05%   |
| 3840x1600          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3440x1440          | 1         | 0.05%   |
| 3120x1050          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 2520x1680          | 1         | 0.05%   |
| 2304x1440          | 1         | 0.05%   |
| 1920x515           | 1         | 0.05%   |
| 1920x1280          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1366x912           | 1         | 0.05%   |
| 1280x768           | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 888       | 41.97%  |
| 14      | 278       | 13.14%  |
| 13      | 230       | 10.87%  |
| 17      | 177       | 8.36%   |
| 10      | 69        | 3.26%   |
| 12      | 67        | 3.17%   |
| 11      | 58        | 2.74%   |
| 24      | 48        | 2.27%   |
| Unknown | 47        | 2.22%   |
| 21      | 44        | 2.08%   |
| 27      | 39        | 1.84%   |
| 23      | 38        | 1.8%    |
| 18      | 25        | 1.18%   |
| 19      | 18        | 0.85%   |
| 22      | 12        | 0.57%   |
| 16      | 11        | 0.52%   |
| 54      | 10        | 0.47%   |
| 31      | 8         | 0.38%   |
| 20      | 8         | 0.38%   |
| 40      | 4         | 0.19%   |
| 26      | 4         | 0.19%   |
| 8       | 4         | 0.19%   |
| 84      | 3         | 0.14%   |
| 72      | 3         | 0.14%   |
| 34      | 3         | 0.14%   |
| 25      | 3         | 0.14%   |
| 52      | 2         | 0.09%   |
| 48      | 2         | 0.09%   |
| 37      | 2         | 0.09%   |
| 32      | 2         | 0.09%   |
| 74      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 47      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 38      | 1         | 0.05%   |
| 30      | 1         | 0.05%   |
| 29      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1267      | 60.28%  |
| 201-300     | 306       | 14.56%  |
| 351-400     | 215       | 10.23%  |
| 501-600     | 123       | 5.85%   |
| 401-500     | 88        | 4.19%   |
| Unknown     | 47        | 2.24%   |
| 1001-1500   | 18        | 0.86%   |
| 601-700     | 14        | 0.67%   |
| 801-900     | 7         | 0.33%   |
| 1501-2000   | 7         | 0.33%   |
| 701-800     | 5         | 0.24%   |
| 101-200     | 4         | 0.19%   |
| 901-1000    | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1463      | 75.88%  |
| 16/10   | 359       | 18.62%  |
| Unknown | 36        | 1.87%   |
| 4/3     | 25        | 1.3%    |
| 5/4     | 20        | 1.04%   |
| 3/2     | 14        | 0.73%   |
| 21/9    | 4         | 0.21%   |
| 32/9    | 2         | 0.1%    |
| 6/5     | 1         | 0.05%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 885       | 41.9%   |
| 81-90          | 414       | 19.6%   |
| 121-130        | 131       | 6.2%    |
| 201-250        | 117       | 5.54%   |
| 71-80          | 79        | 3.74%   |
| 41-50          | 69        | 3.27%   |
| 61-70          | 66        | 3.13%   |
| 51-60          | 58        | 2.75%   |
| Unknown        | 47        | 2.23%   |
| 151-200        | 45        | 2.13%   |
| 301-350        | 41        | 1.94%   |
| 131-140        | 40        | 1.89%   |
| 141-150        | 26        | 1.23%   |
| More than 1000 | 22        | 1.04%   |
| 91-100         | 20        | 0.95%   |
| 351-500        | 15        | 0.71%   |
| 251-300        | 14        | 0.66%   |
| 501-1000       | 10        | 0.47%   |
| 111-120        | 9         | 0.43%   |
| 1-40           | 4         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 830       | 40.08%  |
| 121-160       | 619       | 29.89%  |
| 51-100        | 454       | 21.92%  |
| 161-240       | 70        | 3.38%   |
| Unknown       | 47        | 2.27%   |
| More than 240 | 28        | 1.35%   |
| 1-50          | 23        | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1739      | 84.21%  |
| 2     | 240       | 11.62%  |
| 0     | 67        | 3.24%   |
| 3     | 17        | 0.82%   |
| 4     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 993       | 29.51%  |
| Intel                             | 907       | 26.95%  |
| Qualcomm Atheros                  | 576       | 17.12%  |
| Broadcom                          | 312       | 9.27%   |
| Marvell Technology Group          | 98        | 2.91%   |
| Broadcom Limited                  | 85        | 2.53%   |
| Ralink                            | 49        | 1.46%   |
| Silicon Integrated Systems [SiS]  | 28        | 0.83%   |
| Ralink Technology                 | 26        | 0.77%   |
| Nvidia                            | 26        | 0.77%   |
| TP-Link                           | 25        | 0.74%   |
| Samsung Electronics               | 21        | 0.62%   |
| JMicron Technology                | 19        | 0.56%   |
| MediaTek                          | 16        | 0.48%   |
| Huawei Technologies               | 15        | 0.45%   |
| Ericsson Business Mobile Networks | 15        | 0.45%   |
| Attansic Technology               | 15        | 0.45%   |
| Sierra Wireless                   | 14        | 0.42%   |
| VIA Technologies                  | 11        | 0.33%   |
| Qualcomm Atheros Communications   | 8         | 0.24%   |
| Xiaomi                            | 7         | 0.21%   |
| ASIX Electronics                  | 7         | 0.21%   |
| AMD                               | 7         | 0.21%   |
| Lenovo                            | 6         | 0.18%   |
| Fibocom                           | 6         | 0.18%   |
| Dell                              | 6         | 0.18%   |
| D-Link System                     | 5         | 0.15%   |
| ZyDAS                             | 4         | 0.12%   |
| ULi Electronics                   | 4         | 0.12%   |
| Hewlett-Packard                   | 4         | 0.12%   |
| DisplayLink                       | 4         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.09%   |
| Qualcomm                          | 3         | 0.09%   |
| Motorola PCS                      | 3         | 0.09%   |
| Edimax Technology                 | 3         | 0.09%   |
| ASUSTek Computer                  | 3         | 0.09%   |
| Toshiba                           | 2         | 0.06%   |
| Spreadtrum Communications         | 2         | 0.06%   |
| Sitecom Europe                    | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 514       | 12.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 267       | 6.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 100       | 2.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 91        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 91        | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 84        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 77        | 1.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 67        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 1.58%   |
| Intel Wireless 7260                                                     | 61        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 55        | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 51        | 1.26%   |
| Intel Wireless 8265 / 8275                                              | 49        | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 46        | 1.13%   |
| Intel Wireless 7265                                                     | 43        | 1.06%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 39        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 37        | 0.91%   |
| Intel Wireless 8260                                                     | 33        | 0.81%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 30        | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 30        | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 28        | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 27        | 0.67%   |
| Intel Wireless 3165                                                     | 26        | 0.64%   |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.64%   |
| Intel 82577LM Gigabit Network Connection                                | 26        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 26        | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 25        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                                | 25        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 24        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 23        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 23        | 0.57%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 23        | 0.57%   |
| Intel Ethernet Connection I219-LM                                       | 22        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 21        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 853       | 40.62%  |
| Qualcomm Atheros                      | 498       | 23.71%  |
| Realtek Semiconductor                 | 309       | 14.71%  |
| Broadcom                              | 219       | 10.43%  |
| Ralink                                | 49        | 2.33%   |
| Broadcom Limited                      | 46        | 2.19%   |
| Ralink Technology                     | 26        | 1.24%   |
| TP-Link                               | 21        | 1%      |
| Sierra Wireless                       | 14        | 0.67%   |
| MediaTek                              | 13        | 0.62%   |
| Qualcomm Atheros Communications       | 8         | 0.38%   |
| Fibocom                               | 6         | 0.29%   |
| D-Link System                         | 5         | 0.24%   |
| ZyDAS                                 | 4         | 0.19%   |
| Dell                                  | 4         | 0.19%   |
| Qualcomm                              | 3         | 0.14%   |
| Edimax Technology                     | 3         | 0.14%   |
| Sitecom Europe                        | 2         | 0.1%    |
| NetGear                               | 2         | 0.1%    |
| Linksys                               | 2         | 0.1%    |
| Hewlett-Packard                       | 2         | 0.1%    |
| D-Link                                | 2         | 0.1%    |
| ASUSTek Computer                      | 2         | 0.1%    |
| Winbond Electronics                   | 1         | 0.05%   |
| TRENDnet                              | 1         | 0.05%   |
| Texas Instruments                     | 1         | 0.05%   |
| Micro Star International              | 1         | 0.05%   |
| BUFFALO                               | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 100       | 4.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 91        | 4.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 84        | 3.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 77        | 3.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 67        | 3.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 64        | 3.01%   |
| Intel Wireless 7260                                                           | 61        | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 59        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 55        | 2.59%   |
| Intel Wireless 8265 / 8275                                                    | 49        | 2.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 46        | 2.17%   |
| Intel Wireless 7265                                                           | 43        | 2.03%   |
| Intel Wi-Fi 6 AX200                                                           | 42        | 1.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 39        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 37        | 1.74%   |
| Intel Wireless 8260                                                           | 33        | 1.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 33        | 1.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 31        | 1.46%   |
| Intel Wi-Fi 6 AX201                                                           | 31        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 30        | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 29        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 28        | 1.32%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 27        | 1.27%   |
| Intel Wireless 3165                                                           | 26        | 1.22%   |
| Intel Centrino Advanced-N 6200                                                | 26        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 26        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 24        | 1.13%   |
| Intel Centrino Ultimate-N 6300                                                | 23        | 1.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 23        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 21        | 0.99%   |
| Intel WiFi Link 5100                                                          | 21        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 21        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 21        | 0.99%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 20        | 0.94%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 20        | 0.94%   |
| Intel Centrino Advanced-N 6235                                                | 19        | 0.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 18        | 0.85%   |
| Intel Wireless-AC 9260                                                        | 17        | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 16        | 0.75%   |
| Intel Wireless 3160                                                           | 16        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 868       | 46.97%  |
| Intel                            | 382       | 20.67%  |
| Qualcomm Atheros                 | 156       | 8.44%   |
| Broadcom                         | 128       | 6.93%   |
| Marvell Technology Group         | 98        | 5.3%    |
| Broadcom Limited                 | 40        | 2.16%   |
| Silicon Integrated Systems [SiS] | 26        | 1.41%   |
| Nvidia                           | 25        | 1.35%   |
| Samsung Electronics              | 20        | 1.08%   |
| JMicron Technology               | 19        | 1.03%   |
| Attansic Technology              | 15        | 0.81%   |
| VIA Technologies                 | 11        | 0.6%    |
| Huawei Technologies              | 8         | 0.43%   |
| Xiaomi                           | 7         | 0.38%   |
| ASIX Electronics                 | 7         | 0.38%   |
| Lenovo                           | 6         | 0.32%   |
| TP-Link                          | 4         | 0.22%   |
| MediaTek                         | 4         | 0.22%   |
| DisplayLink                      | 4         | 0.22%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.11%   |
| Spreadtrum Communications        | 2         | 0.11%   |
| Motorola PCS                     | 2         | 0.11%   |
| LG Electronics                   | 2         | 0.11%   |
| Hewlett-Packard                  | 2         | 0.11%   |
| Apple                            | 2         | 0.11%   |
| ULi Electronics                  | 1         | 0.05%   |
| National Semiconductor           | 1         | 0.05%   |
| Microchip Technology             | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| Foxconn / Hon Hai                | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |
| Aquantia                         | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 514       | 27.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 267       | 14.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 91        | 4.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 51        | 2.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 30        | 1.62%   |
| Intel 82577LM Gigabit Network Connection                                       | 26        | 1.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 25        | 1.35%   |
| Intel 82567LM Gigabit Network Connection                                       | 25        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 23        | 1.24%   |
| Intel Ethernet Connection I219-LM                                              | 22        | 1.19%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 20        | 1.08%   |
| Intel Ethernet Connection I217-LM                                              | 20        | 1.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 19        | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 19        | 1.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 18        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                          | 18        | 0.97%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 0.92%   |
| Intel 82566MM Gigabit Network Connection                                       | 17        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 0.86%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 15        | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 14        | 0.76%   |
| Intel PRO/100 VE Network Connection                                            | 14        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 13        | 0.7%    |
| Broadcom BCM4401-B0 100Base-TX                                                 | 13        | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 12        | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 12        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                          | 12        | 0.65%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 12        | 0.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 11        | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 11        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.59%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 11        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 0.59%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 11        | 0.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 10        | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 10        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 10        | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 9         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 9         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1973      | 51.42%  |
| Ethernet | 1782      | 46.44%  |
| Modem    | 81        | 2.11%   |
| Unknown  | 1         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1651      | 77.99%  |
| Ethernet | 466       | 22.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1662      | 81.79%  |
| 1     | 313       | 15.4%   |
| 0     | 47        | 2.31%   |
| 3     | 10        | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1767      | 85.9%   |
| Yes  | 290       | 14.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 460       | 37.1%   |
| Broadcom                        | 134       | 10.81%  |
| Qualcomm Atheros Communications | 129       | 10.4%   |
| Realtek Semiconductor           | 115       | 9.27%   |
| Lite-On Technology              | 53        | 4.27%   |
| Foxconn / Hon Hai               | 52        | 4.19%   |
| Dell                            | 51        | 4.11%   |
| Hewlett-Packard                 | 47        | 3.79%   |
| IMC Networks                    | 43        | 3.47%   |
| Apple                           | 31        | 2.5%    |
| Cambridge Silicon Radio         | 28        | 2.26%   |
| Toshiba                         | 20        | 1.61%   |
| Ralink                          | 16        | 1.29%   |
| ASUSTek Computer                | 14        | 1.13%   |
| Alps Electric                   | 12        | 0.97%   |
| Realtek                         | 7         | 0.56%   |
| Ralink Technology               | 6         | 0.48%   |
| Foxconn International           | 6         | 0.48%   |
| Chicony Electronics             | 4         | 0.32%   |
| MediaTek                        | 3         | 0.24%   |
| Qcom                            | 2         | 0.16%   |
| Integrated System Solution      | 2         | 0.16%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Syntek                          | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| Askey Computer                  | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 215       | 17.32%  |
| Intel AX201 Bluetooth                                                               | 71        | 5.72%   |
| Realtek Bluetooth Radio                                                             | 67        | 5.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 56        | 4.51%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 54        | 4.35%   |
| Intel AX200 Bluetooth                                                               | 40        | 3.22%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 35        | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 33        | 2.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 30        | 2.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 28        | 2.26%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 2.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 21        | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 20        | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 19        | 1.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 18        | 1.45%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 16        | 1.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 15        | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 1.21%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 14        | 1.13%   |
| IMC Networks Bluetooth Device                                                       | 14        | 1.13%   |
| Lite-On Bluetooth Device                                                            | 13        | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 12        | 0.97%   |
| Broadcom BCM2045 Bluetooth                                                          | 12        | 0.97%   |
| Apple Bluetooth Host Controller                                                     | 12        | 0.97%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 11        | 0.89%   |
| Realtek RTL8723B Bluetooth                                                          | 10        | 0.81%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.81%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 10        | 0.81%   |
| Apple Bluetooth HCI                                                                 | 10        | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 0.73%   |
| Intel AX210 Bluetooth                                                               | 9         | 0.73%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 0.73%   |
| Broadcom HP Portable SoftSailing                                                    | 9         | 0.73%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1604      | 69.08%  |
| AMD                              | 359       | 15.46%  |
| Nvidia                           | 203       | 8.74%   |
| Silicon Integrated Systems [SiS] | 31        | 1.34%   |
| C-Media Electronics              | 19        | 0.82%   |
| VIA Technologies                 | 13        | 0.56%   |
| Logitech                         | 11        | 0.47%   |
| GN Netcom                        | 6         | 0.26%   |
| Plantronics                      | 5         | 0.22%   |
| Lenovo                           | 5         | 0.22%   |
| Generalplus Technology           | 5         | 0.22%   |
| ULi Electronics                  | 4         | 0.17%   |
| Texas Instruments                | 4         | 0.17%   |
| Realtek Semiconductor            | 4         | 0.17%   |
| JMTek                            | 4         | 0.17%   |
| M-Audio                          | 3         | 0.13%   |
| Focusrite-Novation               | 3         | 0.13%   |
| Textech International            | 2         | 0.09%   |
| Sennheiser Communications        | 2         | 0.09%   |
| Avid Technology                  | 2         | 0.09%   |
| Audio-Technica                   | 2         | 0.09%   |
| ASUSTek Computer                 | 2         | 0.09%   |
| Apple                            | 2         | 0.09%   |
| ZOOM                             | 1         | 0.04%   |
| XMOS                             | 1         | 0.04%   |
| Tenx Technology                  | 1         | 0.04%   |
| TEAC                             | 1         | 0.04%   |
| TC Electronic                    | 1         | 0.04%   |
| Syntek                           | 1         | 0.04%   |
| Roland                           | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Numark                           | 1         | 0.04%   |
| Native Instruments               | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| MAG Technology                   | 1         | 0.04%   |
| KORG                             | 1         | 0.04%   |
| eMPIA Technology                 | 1         | 0.04%   |
| Elite Silicon                    | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 187       | 6.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 169       | 6.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 157       | 5.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 145       | 5.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 130       | 4.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 129       | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 123       | 4.53%   |
| AMD FCH Azalia Controller                                                                         | 101       | 3.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 93        | 3.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 66        | 2.43%   |
| Intel 8 Series HD Audio Controller                                                                | 66        | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 62        | 2.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 61        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 46        | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 46        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 45        | 1.66%   |
| Intel Broadwell-U Audio Controller                                                                | 45        | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 44        | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 44        | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43        | 1.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 42        | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 41        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40        | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 31        | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 1.1%    |
| AMD Wrestler HDMI Audio                                                                           | 30        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 27        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                                         | 26        | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 23        | 0.85%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 21        | 0.77%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 21        | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 20        | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 18        | 0.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.66%   |
| AMD High Definition Audio Controller                                                              | 16        | 0.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 0.55%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 15        | 0.55%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 14        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 282       | 26.53%  |
| SK hynix                                         | 220       | 20.7%   |
| Unknown                                          | 148       | 13.92%  |
| Micron Technology                                | 112       | 10.54%  |
| Kingston                                         | 91        | 8.56%   |
| Crucial                                          | 40        | 3.76%   |
| Elpida                                           | 30        | 2.82%   |
| Ramaxel Technology                               | 22        | 2.07%   |
| Unknown (ABCD)                                   | 16        | 1.51%   |
| A-DATA Technology                                | 15        | 1.41%   |
| Nanya Technology                                 | 13        | 1.22%   |
| Smart                                            | 10        | 0.94%   |
| Corsair                                          | 10        | 0.94%   |
| G.Skill                                          | 9         | 0.85%   |
| Goodram                                          | 6         | 0.56%   |
| 48spaces                                         | 3         | 0.28%   |
| Transcend                                        | 2         | 0.19%   |
| Teikon                                           | 2         | 0.19%   |
| Team                                             | 2         | 0.19%   |
| Super Talent                                     | 2         | 0.19%   |
| Qimonda                                          | 2         | 0.19%   |
| High Bridge                                      | 2         | 0.19%   |
| Apacer                                           | 2         | 0.19%   |
| Unknown                                          | 2         | 0.19%   |
| V-GeN                                            | 1         | 0.09%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.09%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.09%   |
| Unknown (0x0043415455000000)                     | 1         | 0.09%   |
| Unifosa                                          | 1         | 0.09%   |
| Timetec                                          | 1         | 0.09%   |
| Smart Brazil                                     | 1         | 0.09%   |
| SHARETRONIC                                      | 1         | 0.09%   |
| Patriot                                          | 1         | 0.09%   |
| Neo Forza                                        | 1         | 0.09%   |
| Memox                                            | 1         | 0.09%   |
| Foxline                                          | 1         | 0.09%   |
| fef5                                             | 1         | 0.09%   |
| Essencore                                        | 1         | 0.09%   |
| ChangXin Memory                                  | 1         | 0.09%   |
| B50711390119F885                                 | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 1.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 1.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.15%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 11        | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 10        | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.71%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 8         | 0.71%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 8         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 7         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 7         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.62%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.53%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.44%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.44%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 388       | 42.13%  |
| DDR4    | 312       | 33.88%  |
| DDR2    | 98        | 10.64%  |
| LPDDR4  | 44        | 4.78%   |
| SDRAM   | 26        | 2.82%   |
| LPDDR3  | 24        | 2.61%   |
| Unknown | 11        | 1.19%   |
| DDR     | 10        | 1.09%   |
| DRAM    | 7         | 0.76%   |
| DDR5    | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 837       | 92.18%  |
| Row Of Chips | 51        | 5.62%   |
| Chip         | 9         | 0.99%   |
| DIMM         | 6         | 0.66%   |
| Unknown      | 5         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 321       | 32.13%  |
| 8192    | 294       | 29.43%  |
| 2048    | 206       | 20.62%  |
| 16384   | 88        | 8.81%   |
| 1024    | 64        | 6.41%   |
| 32768   | 18        | 1.8%    |
| 512     | 5         | 0.5%    |
| 1536    | 1         | 0.1%    |
| 256     | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 253       | 26.14%  |
| 2667    | 167       | 17.25%  |
| 3200    | 97        | 10.02%  |
| 667     | 67        | 6.92%   |
| 2400    | 65        | 6.71%   |
| 1334    | 58        | 5.99%   |
| 1333    | 52        | 5.37%   |
| Unknown | 35        | 3.62%   |
| 2133    | 33        | 3.41%   |
| 800     | 19        | 1.96%   |
| 4199    | 17        | 1.76%   |
| 1067    | 16        | 1.65%   |
| 3266    | 13        | 1.34%   |
| 4267    | 12        | 1.24%   |
| 1066    | 11        | 1.14%   |
| 533     | 9         | 0.93%   |
| 2048    | 8         | 0.83%   |
| 1867    | 8         | 0.83%   |
| 975     | 8         | 0.83%   |
| 4266    | 3         | 0.31%   |
| 3733    | 3         | 0.31%   |
| 1866    | 3         | 0.31%   |
| 4800    | 2         | 0.21%   |
| 400     | 2         | 0.21%   |
| 333     | 2         | 0.21%   |
| 8400    | 1         | 0.1%    |
| 3600    | 1         | 0.1%    |
| 2134    | 1         | 0.1%    |
| 1776    | 1         | 0.1%    |
| 133     | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 36.36%  |
| Canon                 | 6         | 27.27%  |
| Brother Industries    | 3         | 13.64%  |
| Prolific Technology   | 2         | 9.09%   |
| Seiko Epson           | 1         | 4.55%   |
| Lexmark International | 1         | 4.55%   |
| Kyocera               | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 8.7%    |
| Seiko Epson L220 Series         | 1         | 4.35%   |
| Lexmark International E360d     | 1         | 4.35%   |
| Kyocera Mita FS-920             | 1         | 4.35%   |
| HP PSC 750xi                    | 1         | 4.35%   |
| HP OfficeJet Reflash            | 1         | 4.35%   |
| HP LaserJet P1005               | 1         | 4.35%   |
| HP LaserJet 1320                | 1         | 4.35%   |
| HP LaserJet 1020                | 1         | 4.35%   |
| HP LaserJet 1015                | 1         | 4.35%   |
| HP LaserJet 1012                | 1         | 4.35%   |
| HP DeskJet F2100 Printer series | 1         | 4.35%   |
| HP DeskJet 3700 series          | 1         | 4.35%   |
| Canon TS5100 series             | 1         | 4.35%   |
| Canon TS3300 series             | 1         | 4.35%   |
| Canon PIXMA MX320 series        | 1         | 4.35%   |
| Canon MF3200 series             | 1         | 4.35%   |
| Canon LBP6230/6240              | 1         | 4.35%   |
| Canon LBP6000                   | 1         | 4.35%   |
| Brother MFC-L2710DW series      | 1         | 4.35%   |
| Brother HL-L2320D series        | 1         | 4.35%   |
| Brother HL-2140 series          | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 66.67%  |
| Seiko Epson     | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 16.67%  |
| HP ScanJet 3570c                                 | 1         | 16.67%  |
| Canon CanoScan N650U/N656U                       | 1         | 16.67%  |
| Canon CanoScan LIDE 25                           | 1         | 16.67%  |
| Canon CanoScan LiDE 220                          | 1         | 16.67%  |
| Canon CanoScan LiDE 100                          | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 463       | 28.55%  |
| Microdia                               | 128       | 7.89%   |
| IMC Networks                           | 120       | 7.4%    |
| Acer                                   | 118       | 7.27%   |
| Suyin                                  | 114       | 7.03%   |
| Realtek Semiconductor                  | 112       | 6.91%   |
| Sunplus Innovation Technology          | 78        | 4.81%   |
| Quanta                                 | 64        | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 59        | 3.64%   |
| Silicon Motion                         | 40        | 2.47%   |
| Alcor Micro                            | 40        | 2.47%   |
| Ricoh                                  | 37        | 2.28%   |
| Lite-On Technology                     | 34        | 2.1%    |
| Syntek                                 | 30        | 1.85%   |
| Apple                                  | 30        | 1.85%   |
| Samsung Electronics                    | 16        | 0.99%   |
| Logitech                               | 16        | 0.99%   |
| Lenovo                                 | 14        | 0.86%   |
| Z-Star Microelectronics                | 13        | 0.8%    |
| ALi                                    | 13        | 0.8%    |
| Importek                               | 10        | 0.62%   |
| Primax Electronics                     | 9         | 0.55%   |
| Luxvisions Innotech Limited            | 9         | 0.55%   |
| USB Camera                             | 6         | 0.37%   |
| OmniVision Technologies                | 6         | 0.37%   |
| DigiTech                               | 6         | 0.37%   |
| GEMBIRD                                | 4         | 0.25%   |
| DJJHFA1BIF5595                         | 3         | 0.18%   |
| Unknown                                | 2         | 0.12%   |
| Sunplus Technology                     | 2         | 0.12%   |
| Sonix Technology                       | 2         | 0.12%   |
| Microsoft                              | 2         | 0.12%   |
| MacroSilicon                           | 2         | 0.12%   |
| Genesys Logic                          | 2         | 0.12%   |
| YGTek                                  | 1         | 0.06%   |
| Xiongmai                               | 1         | 0.06%   |
| USB Camera CS                          | 1         | 0.06%   |
| Tobii AB                               | 1         | 0.06%   |
| SunplusIT                              | 1         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 70        | 4.3%    |
| Microdia Integrated_Webcam_HD                    | 31        | 1.91%   |
| Realtek Integrated_Webcam_HD                     | 30        | 1.84%   |
| Chicony USB 2.0 Camera                           | 29        | 1.78%   |
| Chicony HD WebCam                                | 25        | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                | 23        | 1.41%   |
| Acer Integrated Camera                           | 22        | 1.35%   |
| Sunplus Integrated_Webcam_HD                     | 20        | 1.23%   |
| Realtek USB Camera                               | 20        | 1.23%   |
| IMC Networks Integrated Camera                   | 19        | 1.17%   |
| Chicony TOSHIBA Web Camera - HD                  | 19        | 1.17%   |
| Chicony Lenovo EasyCamera                        | 18        | 1.11%   |
| Suyin HP TrueVision HD                           | 17        | 1.04%   |
| Chicony HP Truevision HD                         | 17        | 1.04%   |
| Alcor Micro USB 2.0 Camera                       | 17        | 1.04%   |
| Acer Lenovo EasyCamera                           | 17        | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 16        | 0.98%   |
| Samsung Galaxy A5 (MTP)                          | 15        | 0.92%   |
| Microdia Sonix USB 2.0 Camera                    | 15        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 15        | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.92%   |
| Lite-On Integrated Camera                        | 14        | 0.86%   |
| Microdia Integrated Webcam                       | 13        | 0.8%    |
| IMC Networks UVC VGA Webcam                      | 13        | 0.8%    |
| Syntek Lenovo EasyCamera                         | 12        | 0.74%   |
| Suyin Acer CrystalEye Webcam                     | 12        | 0.74%   |
| Sunplus HD WebCam                                | 12        | 0.74%   |
| Quanta HP Webcam                                 | 12        | 0.74%   |
| Acer SunplusIT Integrated Camera                 | 12        | 0.74%   |
| Acer BisonCam, NB Pro                            | 12        | 0.74%   |
| Lite-On HP HD Camera                             | 11        | 0.68%   |
| Chicony HP HD Camera                             | 11        | 0.68%   |
| Apple iPhone5/5C/5S/6                            | 11        | 0.68%   |
| Acer HD Webcam                                   | 11        | 0.68%   |
| Quanta HP TrueVision HD Camera                   | 10        | 0.61%   |
| Chicony WebCam                                   | 10        | 0.61%   |
| Chicony HP Truevision HD camera                  | 10        | 0.61%   |
| Chicony HP HD Webcam                             | 10        | 0.61%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 9         | 0.55%   |
| Realtek Acer 640 x 480 laptop camera             | 9         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 118       | 38.44%  |
| Synaptics                  | 56        | 18.24%  |
| AuthenTec                  | 52        | 16.94%  |
| Upek                       | 28        | 9.12%   |
| STMicroelectronics         | 18        | 5.86%   |
| Shenzhen Goodix Technology | 17        | 5.54%   |
| LighTuning Technology      | 11        | 3.58%   |
| Elan Microelectronics      | 7         | 2.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 28        | 9.12%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 8.79%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 8.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 6.84%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 5.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 4.56%   |
| AuthenTec AES2810                                                          | 14        | 4.56%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 4.23%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 3.91%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.58%   |
| Validity Sensors VFS491                                                    | 11        | 3.58%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 3.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.61%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.61%   |
| AuthenTec AES1600                                                          | 7         | 2.28%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.95%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.63%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.3%    |
| Synaptics  WBDI                                                            | 4         | 1.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.3%    |
| Unknown                                                                    | 4         | 1.3%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.98%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.98%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.98%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.65%   |
| Synaptics WBDI Device                                                      | 2         | 0.65%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.65%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.65%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.33%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 60        | 36.36%  |
| Alcor Micro              | 44        | 26.67%  |
| O2 Micro                 | 27        | 16.36%  |
| Upek                     | 15        | 9.09%   |
| Lenovo                   | 14        | 8.48%   |
| Reiner SCT Kartensysteme | 1         | 0.61%   |
| OmniKey                  | 1         | 0.61%   |
| C3PO                     | 1         | 0.61%   |
| Aktiv                    | 1         | 0.61%   |
| Advanced Card Systems    | 1         | 0.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 28        | 16.97%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 12.73%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 8.48%   |
| Broadcom 5880                                                                | 14        | 8.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.45%   |
| Broadcom 58200                                                               | 8         | 4.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 3.64%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.61%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.61%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.61%   |
| Aktiv Rutoken lite                                                           | 1         | 0.61%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1323      | 64.51%  |
| 1     | 576       | 28.08%  |
| 2     | 129       | 6.29%   |
| 3     | 14        | 0.68%   |
| 4     | 6         | 0.29%   |
| 10    | 1         | 0.05%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 306       | 34.46%  |
| Chipcard                 | 160       | 18.02%  |
| Graphics card            | 145       | 16.33%  |
| Net/wireless             | 79        | 8.9%    |
| Modem                    | 44        | 4.95%   |
| Camera                   | 26        | 2.93%   |
| Bluetooth                | 24        | 2.7%    |
| Storage                  | 22        | 2.48%   |
| Communication controller | 17        | 1.91%   |
| Flash memory             | 16        | 1.8%    |
| Card reader              | 16        | 1.8%    |
| Multimedia controller    | 12        | 1.35%   |
| Sound                    | 7         | 0.79%   |
| Network                  | 5         | 0.56%   |
| Net/ethernet             | 4         | 0.45%   |
| Unassigned class         | 2         | 0.23%   |
| Dvb card                 | 2         | 0.23%   |
| Firewire controller      | 1         | 0.11%   |

