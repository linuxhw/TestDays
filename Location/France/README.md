Linux in France - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 12679

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Z77A-G43                    | Desktop     | [02c2bfee54](https://linux-hardware.org/?probe=02c2bfee54) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [3bee1a3271](https://linux-hardware.org/?probe=3bee1a3271) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [2dd85470a0](https://linux-hardware.org/?probe=2dd85470a0) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [00fbe71b59](https://linux-hardware.org/?probe=00fbe71b59) | Apr 30, 2023 |
| Samsung       | 950XED                      | Notebook    | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4c134615](https://linux-hardware.org/?probe=6f4c134615) | Apr 29, 2023 |
| Sony          | VPCF11M1E                   | Notebook    | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [244cfe88a4](https://linux-hardware.org/?probe=244cfe88a4) | Apr 29, 2023 |
| MSI           | P65 Creator 9SF             | Notebook    | [4e682b2c20](https://linux-hardware.org/?probe=4e682b2c20) | Apr 29, 2023 |
| Acer          | Aspire E5-722               | Notebook    | [d02052aeab](https://linux-hardware.org/?probe=d02052aeab) | Apr 29, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | Notebook    | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [09d6d7e570](https://linux-hardware.org/?probe=09d6d7e570) | Apr 28, 2023 |
| Lenovo        | ThinkPad L560 20F2S13L00    | Notebook    | [7695cef903](https://linux-hardware.org/?probe=7695cef903) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Dell          | Precision 3551              | Notebook    | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Dell          | Precision 3551              | Notebook    | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [dcfa7042da](https://linux-hardware.org/?probe=dcfa7042da) | Apr 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [815dd8e866](https://linux-hardware.org/?probe=815dd8e866) | Apr 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [990335263d](https://linux-hardware.org/?probe=990335263d) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| Dell          | Latitude E7270              | Notebook    | [5bacf4eea3](https://linux-hardware.org/?probe=5bacf4eea3) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [716373f59a](https://linux-hardware.org/?probe=716373f59a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e694779b17](https://linux-hardware.org/?probe=e694779b17) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1e07e42dd3](https://linux-hardware.org/?probe=1e07e42dd3) | Apr 26, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [474c43577f](https://linux-hardware.org/?probe=474c43577f) | Apr 26, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7bed835979](https://linux-hardware.org/?probe=7bed835979) | Apr 26, 2023 |
| Timi          | TM1703                      | Notebook    | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| HP            | 1825                        | Desktop     | [5a26051aec](https://linux-hardware.org/?probe=5a26051aec) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [a89604dccd](https://linux-hardware.org/?probe=a89604dccd) | Apr 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [d9decf6f0a](https://linux-hardware.org/?probe=d9decf6f0a) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| ASUSTek       | K73BR                       | Notebook    | [547b19cd2c](https://linux-hardware.org/?probe=547b19cd2c) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [75ac9d10bf](https://linux-hardware.org/?probe=75ac9d10bf) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [98c2b2c382](https://linux-hardware.org/?probe=98c2b2c382) | Apr 25, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [da35752b66](https://linux-hardware.org/?probe=da35752b66) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [290f3ebad7](https://linux-hardware.org/?probe=290f3ebad7) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| LDLC          | SPC-I                       | Notebook    | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e4c737a64d](https://linux-hardware.org/?probe=e4c737a64d) | Apr 25, 2023 |
| MSI           | H110M ECO                   | Desktop     | [bfa2b17374](https://linux-hardware.org/?probe=bfa2b17374) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a62e386eae](https://linux-hardware.org/?probe=a62e386eae) | Apr 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [e36f5e17a5](https://linux-hardware.org/?probe=e36f5e17a5) | Apr 24, 2023 |
| Samsung       | 950XED                      | Notebook    | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | Notebook    | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| G7-2011       | X79                         | Desktop     | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [6316886f98](https://linux-hardware.org/?probe=6316886f98) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| HP            | 15                          | Notebook    | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [bd9d832f72](https://linux-hardware.org/?probe=bd9d832f72) | Apr 23, 2023 |
| Sony          | VPCEH3U1E                   | Notebook    | [6fa28ef21c](https://linux-hardware.org/?probe=6fa28ef21c) | Apr 23, 2023 |
| HP            | ProBook 6570b               | Notebook    | [4e2ba781e2](https://linux-hardware.org/?probe=4e2ba781e2) | Apr 23, 2023 |
| Dell          | Latitude 5591               | Notebook    | [b4dfa57eea](https://linux-hardware.org/?probe=b4dfa57eea) | Apr 23, 2023 |
| Gigabyte      | Z97P-D3                     | Desktop     | [5da4c37f75](https://linux-hardware.org/?probe=5da4c37f75) | Apr 23, 2023 |
| Dell          | Latitude 5591               | Notebook    | [1a45f96f80](https://linux-hardware.org/?probe=1a45f96f80) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Shuttle       | DS20U                       | Desktop     | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| HP            | 845A                        | Desktop     | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [9a6f040039](https://linux-hardware.org/?probe=9a6f040039) | Apr 23, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [90f041e2a1](https://linux-hardware.org/?probe=90f041e2a1) | Apr 23, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [6d06ef4fa1](https://linux-hardware.org/?probe=6d06ef4fa1) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | Notebook    | [77a309dcf1](https://linux-hardware.org/?probe=77a309dcf1) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | Desktop     | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | Notebook    | [4c60675864](https://linux-hardware.org/?probe=4c60675864) | Apr 22, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [7a873a7baa](https://linux-hardware.org/?probe=7a873a7baa) | Apr 22, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [3e4c8bce3b](https://linux-hardware.org/?probe=3e4c8bce3b) | Apr 22, 2023 |
| Dell          | 0CRH6C A00                  | Desktop     | [cbb78e1785](https://linux-hardware.org/?probe=cbb78e1785) | Apr 22, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [f64336848a](https://linux-hardware.org/?probe=f64336848a) | Apr 22, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [c9e17ad011](https://linux-hardware.org/?probe=c9e17ad011) | Apr 22, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| Dell          | Precision 5510              | Notebook    | [94b5586a2c](https://linux-hardware.org/?probe=94b5586a2c) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f23eeda727](https://linux-hardware.org/?probe=f23eeda727) | Apr 22, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [1ffb09ff2a](https://linux-hardware.org/?probe=1ffb09ff2a) | Apr 22, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | Notebook    | [f813e87465](https://linux-hardware.org/?probe=f813e87465) | Apr 21, 2023 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [868456ca5d](https://linux-hardware.org/?probe=868456ca5d) | Apr 21, 2023 |
| Medion        | MS-7621                     | Desktop     | [efb8293786](https://linux-hardware.org/?probe=efb8293786) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | Notebook    | [53951da2d7](https://linux-hardware.org/?probe=53951da2d7) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Intel         | D54250WYK H13922-305        | Desktop     | [a7ef0d6dad](https://linux-hardware.org/?probe=a7ef0d6dad) | Apr 21, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [acbe851404](https://linux-hardware.org/?probe=acbe851404) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| PC Special... | TN1-156M                    | Notebook    | [ef6b57e807](https://linux-hardware.org/?probe=ef6b57e807) | Apr 21, 2023 |
| HP            | Notebook                    | Notebook    | [150b1d6ae7](https://linux-hardware.org/?probe=150b1d6ae7) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [985a269b26](https://linux-hardware.org/?probe=985a269b26) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| MSI           | CR61 3M                     | Notebook    | [0ee98cd841](https://linux-hardware.org/?probe=0ee98cd841) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Lenovo        | ThinkCentre M90p 3282B5G    | Desktop     | [9741f7bd1e](https://linux-hardware.org/?probe=9741f7bd1e) | Apr 20, 2023 |
| Acer          | TravelMate 5320             | Notebook    | [fa41e30258](https://linux-hardware.org/?probe=fa41e30258) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [fd6d8a7cd7](https://linux-hardware.org/?probe=fd6d8a7cd7) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6ea882bacb](https://linux-hardware.org/?probe=6ea882bacb) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [8b560b455e](https://linux-hardware.org/?probe=8b560b455e) | Apr 19, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [fc12fc0a9d](https://linux-hardware.org/?probe=fc12fc0a9d) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [64ea7a1e04](https://linux-hardware.org/?probe=64ea7a1e04) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| Intel         | D510MO AAE76523-401         | Desktop     | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | Desktop     | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| HP            | 1825                        | Desktop     | [5c637a9ef6](https://linux-hardware.org/?probe=5c637a9ef6) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| ASUSTek       | X751BP                      | Notebook    | [0bea82acba](https://linux-hardware.org/?probe=0bea82acba) | Apr 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [ec0532e3e3](https://linux-hardware.org/?probe=ec0532e3e3) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| ASUSTek       | K55A                        | Notebook    | [99fe712761](https://linux-hardware.org/?probe=99fe712761) | Apr 17, 2023 |
| ASUSTek       | UX303LB                     | Notebook    | [48c19abe8c](https://linux-hardware.org/?probe=48c19abe8c) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d12e0064fc](https://linux-hardware.org/?probe=d12e0064fc) | Apr 17, 2023 |
| HP            | Pavilion 17                 | Notebook    | [b06b49ac95](https://linux-hardware.org/?probe=b06b49ac95) | Apr 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f3a91915df](https://linux-hardware.org/?probe=f3a91915df) | Apr 17, 2023 |
| HP            | 18E7                        | Desktop     | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | P4C800-E                    | Desktop     | [4521f2b9b4](https://linux-hardware.org/?probe=4521f2b9b4) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4296a1241d](https://linux-hardware.org/?probe=4296a1241d) | Apr 17, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [64e06d7111](https://linux-hardware.org/?probe=64e06d7111) | Apr 17, 2023 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [ebd62c0513](https://linux-hardware.org/?probe=ebd62c0513) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [c31465c0a1](https://linux-hardware.org/?probe=c31465c0a1) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [fec4fc20a6](https://linux-hardware.org/?probe=fec4fc20a6) | Apr 16, 2023 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [4ac44c74a3](https://linux-hardware.org/?probe=4ac44c74a3) | Apr 16, 2023 |
| eMachines     | E945GCU                     | Desktop     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [65b2e4afa9](https://linux-hardware.org/?probe=65b2e4afa9) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| Dell          | 0TP412                      | Desktop     | [7491d6d66d](https://linux-hardware.org/?probe=7491d6d66d) | Apr 16, 2023 |
| ASUSTek       | K53BE                       | Notebook    | [f21e7219ce](https://linux-hardware.org/?probe=f21e7219ce) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Dell          | 0TP412                      | Desktop     | [c5f0ba736e](https://linux-hardware.org/?probe=c5f0ba736e) | Apr 16, 2023 |
| Dell          | Vostro 15 7510              | Notebook    | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | Desktop     | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [da62023f35](https://linux-hardware.org/?probe=da62023f35) | Apr 15, 2023 |
| Dell          | Latitude E5520              | Notebook    | [5e04eeccae](https://linux-hardware.org/?probe=5e04eeccae) | Apr 15, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [f534984150](https://linux-hardware.org/?probe=f534984150) | Apr 15, 2023 |
| HP            | 83E2                        | Desktop     | [af01123687](https://linux-hardware.org/?probe=af01123687) | Apr 15, 2023 |
| HP            | 83E2                        | Desktop     | [f5052291a4](https://linux-hardware.org/?probe=f5052291a4) | Apr 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0e89a3c19b](https://linux-hardware.org/?probe=0e89a3c19b) | Apr 15, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [8de126d84d](https://linux-hardware.org/?probe=8de126d84d) | Apr 15, 2023 |
| ASUSTek       | X302LJ                      | Notebook    | [e045b269b1](https://linux-hardware.org/?probe=e045b269b1) | Apr 14, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [c3c64a7016](https://linux-hardware.org/?probe=c3c64a7016) | Apr 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| HP            | 2B4B                        | Desktop     | [9103ce1fce](https://linux-hardware.org/?probe=9103ce1fce) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e5b11f4136](https://linux-hardware.org/?probe=e5b11f4136) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| HP            | ProBook 6570b               | Notebook    | [af45cce5b8](https://linux-hardware.org/?probe=af45cce5b8) | Apr 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [6cfca82c2f](https://linux-hardware.org/?probe=6cfca82c2f) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | Desktop     | [9ab9baf194](https://linux-hardware.org/?probe=9ab9baf194) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [30d6d32fc1](https://linux-hardware.org/?probe=30d6d32fc1) | Apr 13, 2023 |
| sunxi         | LeMaker Banana Pi           | Soc         | [7a60bb63b4](https://linux-hardware.org/?probe=7a60bb63b4) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b223f5fbf1](https://linux-hardware.org/?probe=b223f5fbf1) | Apr 13, 2023 |
| Dell          | G15 5510                    | Notebook    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [4e09a1cd3e](https://linux-hardware.org/?probe=4e09a1cd3e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| Dell          | XPS L322X                   | Notebook    | [cbf247e5a6](https://linux-hardware.org/?probe=cbf247e5a6) | Apr 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [bcb170c5f0](https://linux-hardware.org/?probe=bcb170c5f0) | Apr 13, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [527e436d2b](https://linux-hardware.org/?probe=527e436d2b) | Apr 12, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [43b322dcf3](https://linux-hardware.org/?probe=43b322dcf3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | Notebook    | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [6cbdeb350e](https://linux-hardware.org/?probe=6cbdeb350e) | Apr 12, 2023 |
| Dell          | Precision 3571              | Notebook    | [e6e8267b6a](https://linux-hardware.org/?probe=e6e8267b6a) | Apr 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [248e22982d](https://linux-hardware.org/?probe=248e22982d) | Apr 12, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [c07a4d67ca](https://linux-hardware.org/?probe=c07a4d67ca) | Apr 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [1d23894711](https://linux-hardware.org/?probe=1d23894711) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [905a2aee02](https://linux-hardware.org/?probe=905a2aee02) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| MSI           | GP72MVR 7RFX                | Notebook    | [17f60a29f5](https://linux-hardware.org/?probe=17f60a29f5) | Apr 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [32bf664d90](https://linux-hardware.org/?probe=32bf664d90) | Apr 11, 2023 |
| HP            | 2AF7                        | Desktop     | [e9621d5a9c](https://linux-hardware.org/?probe=e9621d5a9c) | Apr 11, 2023 |
| HP            | 2AF7                        | Desktop     | [b187733415](https://linux-hardware.org/?probe=b187733415) | Apr 11, 2023 |
| HP            | 8298                        | Desktop     | [ccde341ebf](https://linux-hardware.org/?probe=ccde341ebf) | Apr 11, 2023 |
| HP            | 8298                        | Desktop     | [bab1bd2943](https://linux-hardware.org/?probe=bab1bd2943) | Apr 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f4190d2c4e](https://linux-hardware.org/?probe=f4190d2c4e) | Apr 11, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| ASRock        | B85M-HDS R2.0               | Desktop     | [24bdbac13a](https://linux-hardware.org/?probe=24bdbac13a) | Apr 11, 2023 |
| Gigabyte      | X7X7                        | Notebook    | [8f58573ff3](https://linux-hardware.org/?probe=8f58573ff3) | Apr 11, 2023 |
| MSI           | Prestige 14Evo B13M         | Notebook    | [a3967e84ad](https://linux-hardware.org/?probe=a3967e84ad) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| ASUSTek       | G751JY                      | Notebook    | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [ab53417291](https://linux-hardware.org/?probe=ab53417291) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [704f5bcf78](https://linux-hardware.org/?probe=704f5bcf78) | Apr 10, 2023 |
| Sony          | VPCEB1M1E                   | Notebook    | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe939f268b](https://linux-hardware.org/?probe=fe939f268b) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [955a648772](https://linux-hardware.org/?probe=955a648772) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [7806838777](https://linux-hardware.org/?probe=7806838777) | Apr 09, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [ee2678d76f](https://linux-hardware.org/?probe=ee2678d76f) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [12faf271f6](https://linux-hardware.org/?probe=12faf271f6) | Apr 08, 2023 |
| ASUSTek       | X751LN                      | Notebook    | [8bf4f37814](https://linux-hardware.org/?probe=8bf4f37814) | Apr 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d01569c067](https://linux-hardware.org/?probe=d01569c067) | Apr 08, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [9cd5518f53](https://linux-hardware.org/?probe=9cd5518f53) | Apr 08, 2023 |
| HP            | ENVY dv6                    | Notebook    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| MSI           | B85-G43                     | Desktop     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| ASRock        | X79 Extreme6                | Desktop     | [2b3f00ac79](https://linux-hardware.org/?probe=2b3f00ac79) | Apr 08, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Dell          | G3 3500                     | Notebook    | [cae0e09f03](https://linux-hardware.org/?probe=cae0e09f03) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Dell          | G3 3500                     | Notebook    | [9f77f9158a](https://linux-hardware.org/?probe=9f77f9158a) | Apr 07, 2023 |
| Lenovo        | Aptio CRB NOK               | Mini pc     | [e4d5290d7b](https://linux-hardware.org/?probe=e4d5290d7b) | Apr 07, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [2c731aefae](https://linux-hardware.org/?probe=2c731aefae) | Apr 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [64b9978ed0](https://linux-hardware.org/?probe=64b9978ed0) | Apr 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| QTQD          | Unknown                     | Desktop     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [c134ae92fc](https://linux-hardware.org/?probe=c134ae92fc) | Apr 06, 2023 |
| HP            | Sona                        | Notebook    | [64fa63647b](https://linux-hardware.org/?probe=64fa63647b) | Apr 06, 2023 |
| Dell          | Precision 7560              | Notebook    | [b474fb4429](https://linux-hardware.org/?probe=b474fb4429) | Apr 06, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [bab2c0f0e4](https://linux-hardware.org/?probe=bab2c0f0e4) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| Dell          | Latitude E7470              | Notebook    | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [4d639304bf](https://linux-hardware.org/?probe=4d639304bf) | Apr 05, 2023 |
| HP            | 84FD                        | Desktop     | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [5d0489d439](https://linux-hardware.org/?probe=5d0489d439) | Apr 05, 2023 |
| Toshiba       | Satellite C855D-12J         | Notebook    | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [99a9d4cae5](https://linux-hardware.org/?probe=99a9d4cae5) | Apr 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | X71Q                        | Notebook    | [9a7d0f4b2b](https://linux-hardware.org/?probe=9a7d0f4b2b) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [2d32794500](https://linux-hardware.org/?probe=2d32794500) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [f04b34af52](https://linux-hardware.org/?probe=f04b34af52) | Apr 04, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [fa9fe4337a](https://linux-hardware.org/?probe=fa9fe4337a) | Apr 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [9ef9150c8c](https://linux-hardware.org/?probe=9ef9150c8c) | Apr 04, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [60633671a2](https://linux-hardware.org/?probe=60633671a2) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| MSI           | H110M ECO                   | Desktop     | [983153c81e](https://linux-hardware.org/?probe=983153c81e) | Apr 04, 2023 |
| ASRock        | A320M-DVS R3.0              | Desktop     | [518d9bcac3](https://linux-hardware.org/?probe=518d9bcac3) | Apr 04, 2023 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [ceeafa59a2](https://linux-hardware.org/?probe=ceeafa59a2) | Apr 04, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ec6a09a6ba](https://linux-hardware.org/?probe=ec6a09a6ba) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [1dbae9d685](https://linux-hardware.org/?probe=1dbae9d685) | Apr 04, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [bbb597effc](https://linux-hardware.org/?probe=bbb597effc) | Apr 04, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [1978d77ba2](https://linux-hardware.org/?probe=1978d77ba2) | Apr 03, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [e6b864d24e](https://linux-hardware.org/?probe=e6b864d24e) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [757ae6aa73](https://linux-hardware.org/?probe=757ae6aa73) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [ef04e5d464](https://linux-hardware.org/?probe=ef04e5d464) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [f9eb684250](https://linux-hardware.org/?probe=f9eb684250) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [661283d296](https://linux-hardware.org/?probe=661283d296) | Apr 03, 2023 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ecd1f451f0](https://linux-hardware.org/?probe=ecd1f451f0) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3c10c8c51a](https://linux-hardware.org/?probe=3c10c8c51a) | Apr 03, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [49b1cef736](https://linux-hardware.org/?probe=49b1cef736) | Apr 03, 2023 |
| HP            | Pavilion 17                 | Notebook    | [487bc77c07](https://linux-hardware.org/?probe=487bc77c07) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1c15668c5d](https://linux-hardware.org/?probe=1c15668c5d) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| ASRock        | G31M-S                      | Desktop     | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [ed4e86ebbb](https://linux-hardware.org/?probe=ed4e86ebbb) | Apr 03, 2023 |
| HP            | 1905                        | Desktop     | [2044e303ea](https://linux-hardware.org/?probe=2044e303ea) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [595b975199](https://linux-hardware.org/?probe=595b975199) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [e382f0f4f1](https://linux-hardware.org/?probe=e382f0f4f1) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [892ffd1727](https://linux-hardware.org/?probe=892ffd1727) | Apr 02, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6399f19b22](https://linux-hardware.org/?probe=6399f19b22) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Notebook      | P15SM                       | Notebook    | [070f808c28](https://linux-hardware.org/?probe=070f808c28) | Apr 02, 2023 |
| ASUSTek       | G71V                        | Notebook    | [6594dac071](https://linux-hardware.org/?probe=6594dac071) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [e1c055e8dc](https://linux-hardware.org/?probe=e1c055e8dc) | Apr 02, 2023 |
| Acer          | Veriton X2632G V:1.0        | Desktop     | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [0941828bd0](https://linux-hardware.org/?probe=0941828bd0) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [e014609915](https://linux-hardware.org/?probe=e014609915) | Apr 01, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Acer          | RS880M05                    | Desktop     | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| Acer          | Aspire X3400                | Desktop     | [093b0a0239](https://linux-hardware.org/?probe=093b0a0239) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [95c5f574c9](https://linux-hardware.org/?probe=95c5f574c9) | Apr 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [79ef948789](https://linux-hardware.org/?probe=79ef948789) | Apr 01, 2023 |
| Lenovo        | ThinkPad L560 20F2S1AJ00    | Notebook    | [8987605dde](https://linux-hardware.org/?probe=8987605dde) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [9ee9bc67cf](https://linux-hardware.org/?probe=9ee9bc67cf) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [f9083bca8d](https://linux-hardware.org/?probe=f9083bca8d) | Apr 01, 2023 |
| Google        | Lulu                        | Notebook    | [0183eadbc8](https://linux-hardware.org/?probe=0183eadbc8) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| ASUSTek       | N752VX                      | Notebook    | [d426499408](https://linux-hardware.org/?probe=d426499408) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| HP            | Presario CQ58               | Notebook    | [e8f8f289ac](https://linux-hardware.org/?probe=e8f8f289ac) | Apr 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [87bc2601f3](https://linux-hardware.org/?probe=87bc2601f3) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [916adbdf9f](https://linux-hardware.org/?probe=916adbdf9f) | Apr 01, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [073d49ce6b](https://linux-hardware.org/?probe=073d49ce6b) | Mar 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [9e7aa15a9f](https://linux-hardware.org/?probe=9e7aa15a9f) | Mar 31, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [498726ce78](https://linux-hardware.org/?probe=498726ce78) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Notebook      | NL40_50GU                   | Notebook    | [a46afd7246](https://linux-hardware.org/?probe=a46afd7246) | Mar 31, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [8daf4bf0a5](https://linux-hardware.org/?probe=8daf4bf0a5) | Mar 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d9cbbe0a35](https://linux-hardware.org/?probe=d9cbbe0a35) | Mar 30, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [0f8c22b288](https://linux-hardware.org/?probe=0f8c22b288) | Mar 30, 2023 |
| ASUSTek       | K55A                        | Notebook    | [cf40bdccfc](https://linux-hardware.org/?probe=cf40bdccfc) | Mar 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ad1392d8c0](https://linux-hardware.org/?probe=ad1392d8c0) | Mar 30, 2023 |
| ASUSTek       | K55A                        | Notebook    | [b6c168d185](https://linux-hardware.org/?probe=b6c168d185) | Mar 30, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [0a09299aae](https://linux-hardware.org/?probe=0a09299aae) | Mar 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [76e09994d0](https://linux-hardware.org/?probe=76e09994d0) | Mar 30, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [2082d90602](https://linux-hardware.org/?probe=2082d90602) | Mar 30, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [552ad08e05](https://linux-hardware.org/?probe=552ad08e05) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [426c2d06fd](https://linux-hardware.org/?probe=426c2d06fd) | Mar 30, 2023 |
| Sony          | SVF1521C2EW                 | Notebook    | [978ae8afac](https://linux-hardware.org/?probe=978ae8afac) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| HP            | 82B4                        | Desktop     | [0829a64947](https://linux-hardware.org/?probe=0829a64947) | Mar 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [0f273e6227](https://linux-hardware.org/?probe=0f273e6227) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [cfe80f22f8](https://linux-hardware.org/?probe=cfe80f22f8) | Mar 30, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [4d12d122e1](https://linux-hardware.org/?probe=4d12d122e1) | Mar 30, 2023 |
| Shuttle       | FH170                       | Desktop     | [0fa0f1ab72](https://linux-hardware.org/?probe=0fa0f1ab72) | Mar 30, 2023 |
| MSI           | MS-AA5E 0A                  | All in one  | [36d66ad0a2](https://linux-hardware.org/?probe=36d66ad0a2) | Mar 29, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [7580b631a9](https://linux-hardware.org/?probe=7580b631a9) | Mar 29, 2023 |
| Acer          | Veriton Z4810G              | All in one  | [c4a9881345](https://linux-hardware.org/?probe=c4a9881345) | Mar 29, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [5c65763b9d](https://linux-hardware.org/?probe=5c65763b9d) | Mar 29, 2023 |
| Lenovo        | U41-70 80JV                 | Notebook    | [975da67142](https://linux-hardware.org/?probe=975da67142) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [89a0332dfd](https://linux-hardware.org/?probe=89a0332dfd) | Mar 29, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [46a3f1d497](https://linux-hardware.org/?probe=46a3f1d497) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [11c94aa91b](https://linux-hardware.org/?probe=11c94aa91b) | Mar 29, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [c55a4d3166](https://linux-hardware.org/?probe=c55a4d3166) | Mar 29, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [2798c67b5c](https://linux-hardware.org/?probe=2798c67b5c) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [fe471635fb](https://linux-hardware.org/?probe=fe471635fb) | Mar 29, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASRock        | H61M-DG3/USB3               | Desktop     | [6e7b188568](https://linux-hardware.org/?probe=6e7b188568) | Mar 28, 2023 |
| HP            | 0A60h                       | Desktop     | [6ad65f4f2b](https://linux-hardware.org/?probe=6ad65f4f2b) | Mar 28, 2023 |
| Dell          | Vostro 5568                 | Notebook    | [0004be15a4](https://linux-hardware.org/?probe=0004be15a4) | Mar 28, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| HP            | Compaq 6510b (GR680ET)      | Notebook    | [716c4212c7](https://linux-hardware.org/?probe=716c4212c7) | Mar 28, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7fff3bb217](https://linux-hardware.org/?probe=7fff3bb217) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Acer          | Aspire E5-532G              | Notebook    | [35e076d9b5](https://linux-hardware.org/?probe=35e076d9b5) | Mar 28, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [16db0eb166](https://linux-hardware.org/?probe=16db0eb166) | Mar 28, 2023 |
| Dell          | 0DKKCF A00                  | All in one  | [bc3d41b77d](https://linux-hardware.org/?probe=bc3d41b77d) | Mar 28, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [5f0453caf8](https://linux-hardware.org/?probe=5f0453caf8) | Mar 28, 2023 |
| ASUSTek       | N61Jq                       | Notebook    | [0ca1f04770](https://linux-hardware.org/?probe=0ca1f04770) | Mar 28, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| Sony          | SVF1521C2EW                 | Notebook    | [2bafb0a0e4](https://linux-hardware.org/?probe=2bafb0a0e4) | Mar 28, 2023 |
| ASRock        | G31M-S                      | Desktop     | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| HP            | 1497                        | Desktop     | [94c6f8a63a](https://linux-hardware.org/?probe=94c6f8a63a) | Mar 27, 2023 |
| HP            | Laptop 14s-fq2xxx           | Notebook    | [8b64ddb550](https://linux-hardware.org/?probe=8b64ddb550) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | Notebook    | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| Gigabyte      | WRX80-SU8                   | Desktop     | [88c24f7e44](https://linux-hardware.org/?probe=88c24f7e44) | Mar 27, 2023 |
| Dell          | 0G919G A00                  | Desktop     | [139207e1a7](https://linux-hardware.org/?probe=139207e1a7) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [08627c5990](https://linux-hardware.org/?probe=08627c5990) | Mar 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [e634227889](https://linux-hardware.org/?probe=e634227889) | Mar 27, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [119a217e25](https://linux-hardware.org/?probe=119a217e25) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [e834f14d64](https://linux-hardware.org/?probe=e834f14d64) | Mar 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c3dbea760e](https://linux-hardware.org/?probe=c3dbea760e) | Mar 26, 2023 |
| HP            | ProLiant ML350 G5           | Desktop     | [b0000fc633](https://linux-hardware.org/?probe=b0000fc633) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [2e14ac2984](https://linux-hardware.org/?probe=2e14ac2984) | Mar 26, 2023 |
| ASUSTek       | K50IE                       | Notebook    | [bde872583b](https://linux-hardware.org/?probe=bde872583b) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [9aa3215de8](https://linux-hardware.org/?probe=9aa3215de8) | Mar 26, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [54e2f18738](https://linux-hardware.org/?probe=54e2f18738) | Mar 26, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [9997ce4485](https://linux-hardware.org/?probe=9997ce4485) | Mar 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Notebook    | [f9c5ae93de](https://linux-hardware.org/?probe=f9c5ae93de) | Mar 26, 2023 |
| Fujitsu Si... | AMILO Pi 3625               | Notebook    | [076352cb68](https://linux-hardware.org/?probe=076352cb68) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [129c2be9aa](https://linux-hardware.org/?probe=129c2be9aa) | Mar 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Notebook    | [414c36eb9d](https://linux-hardware.org/?probe=414c36eb9d) | Mar 26, 2023 |
| ZOTAC         | ZBOX-EN173080C/EN173070C... | Mini pc     | [6f53d65339](https://linux-hardware.org/?probe=6f53d65339) | Mar 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [b7c75f2713](https://linux-hardware.org/?probe=b7c75f2713) | Mar 26, 2023 |
| Dell          | Latitude 5520               | Notebook    | [47372d09fe](https://linux-hardware.org/?probe=47372d09fe) | Mar 25, 2023 |
| Dell          | Latitude 5520               | Notebook    | [0c69ef5724](https://linux-hardware.org/?probe=0c69ef5724) | Mar 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [e6219e18b1](https://linux-hardware.org/?probe=e6219e18b1) | Mar 25, 2023 |
| Packard Be... | EasyNote SB65               | Notebook    | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [22aa7f3036](https://linux-hardware.org/?probe=22aa7f3036) | Mar 25, 2023 |
| Dell          | XPS 9315                    | Notebook    | [050fede003](https://linux-hardware.org/?probe=050fede003) | Mar 25, 2023 |
| Toshiba       | KIRA                        | Notebook    | [e96de49ce8](https://linux-hardware.org/?probe=e96de49ce8) | Mar 25, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [3771b8bf2e](https://linux-hardware.org/?probe=3771b8bf2e) | Mar 25, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [623f5742ab](https://linux-hardware.org/?probe=623f5742ab) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Packard Be... | H17HV                       | Notebook    | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [5fccdb098d](https://linux-hardware.org/?probe=5fccdb098d) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7506ffb6fd](https://linux-hardware.org/?probe=7506ffb6fd) | Mar 24, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [f76bc64ee4](https://linux-hardware.org/?probe=f76bc64ee4) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8af246641b](https://linux-hardware.org/?probe=8af246641b) | Mar 24, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [479f7f7a25](https://linux-hardware.org/?probe=479f7f7a25) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| HP            | Pavilion dv7                | Notebook    | [c0cec2e941](https://linux-hardware.org/?probe=c0cec2e941) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [8cee790d83](https://linux-hardware.org/?probe=8cee790d83) | Mar 23, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [e6db3c2c26](https://linux-hardware.org/?probe=e6db3c2c26) | Mar 23, 2023 |
| HP            | 1905                        | Desktop     | [7bccc34bf4](https://linux-hardware.org/?probe=7bccc34bf4) | Mar 23, 2023 |
| Lenovo        | ThinkPad P70 20ESS2VP00     | Notebook    | [bb6fdb6236](https://linux-hardware.org/?probe=bb6fdb6236) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [9d1c01a6cd](https://linux-hardware.org/?probe=9d1c01a6cd) | Mar 23, 2023 |
| HP            | Spectre                     | Convertible | [c9181ab4f2](https://linux-hardware.org/?probe=c9181ab4f2) | Mar 22, 2023 |
| HP            | Spectre                     | Convertible | [5e07c68683](https://linux-hardware.org/?probe=5e07c68683) | Mar 22, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [662189c6fc](https://linux-hardware.org/?probe=662189c6fc) | Mar 22, 2023 |
| Toshiba       | Satellite C870-198          | Notebook    | [7969002105](https://linux-hardware.org/?probe=7969002105) | Mar 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [ba101f37d0](https://linux-hardware.org/?probe=ba101f37d0) | Mar 22, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME O... | Desktop     | [d5afcaf7a1](https://linux-hardware.org/?probe=d5afcaf7a1) | Mar 22, 2023 |
| AZW           | GK35                        | Desktop     | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b037cbd3b6](https://linux-hardware.org/?probe=b037cbd3b6) | Mar 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a87172150f](https://linux-hardware.org/?probe=a87172150f) | Mar 22, 2023 |
| Notebook      | P15SM                       | Notebook    | [082e2c3c16](https://linux-hardware.org/?probe=082e2c3c16) | Mar 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [8606a64427](https://linux-hardware.org/?probe=8606a64427) | Mar 21, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | Notebook    | [95154b40cc](https://linux-hardware.org/?probe=95154b40cc) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [45610ce6bf](https://linux-hardware.org/?probe=45610ce6bf) | Mar 21, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [579152ea57](https://linux-hardware.org/?probe=579152ea57) | Mar 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [ea7e302020](https://linux-hardware.org/?probe=ea7e302020) | Mar 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [8ed4a1e3ba](https://linux-hardware.org/?probe=8ed4a1e3ba) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a204a0f2c0](https://linux-hardware.org/?probe=a204a0f2c0) | Mar 21, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d23fb1d0f6](https://linux-hardware.org/?probe=d23fb1d0f6) | Mar 21, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [1b98d965e7](https://linux-hardware.org/?probe=1b98d965e7) | Mar 20, 2023 |
| HP            | Pavilion dm4                | Notebook    | [7983ee084c](https://linux-hardware.org/?probe=7983ee084c) | Mar 20, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [3aee61f2bb](https://linux-hardware.org/?probe=3aee61f2bb) | Mar 20, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [cb2c031349](https://linux-hardware.org/?probe=cb2c031349) | Mar 20, 2023 |
| Dell          | Latitude E5500              | Notebook    | [9c76627b98](https://linux-hardware.org/?probe=9c76627b98) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [0aa8c2bf55](https://linux-hardware.org/?probe=0aa8c2bf55) | Mar 20, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4153e72c6b](https://linux-hardware.org/?probe=4153e72c6b) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3387f1f1c8](https://linux-hardware.org/?probe=3387f1f1c8) | Mar 19, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [9d37ace881](https://linux-hardware.org/?probe=9d37ace881) | Mar 19, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [93ce0e9d73](https://linux-hardware.org/?probe=93ce0e9d73) | Mar 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1EM     | Notebook    | [a49e9997f1](https://linux-hardware.org/?probe=a49e9997f1) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [dcc37300fd](https://linux-hardware.org/?probe=dcc37300fd) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [210b2e16e3](https://linux-hardware.org/?probe=210b2e16e3) | Mar 18, 2023 |
| Dell          | Precision M4800             | Notebook    | [26912746f6](https://linux-hardware.org/?probe=26912746f6) | Mar 18, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [5a11bc39d5](https://linux-hardware.org/?probe=5a11bc39d5) | Mar 18, 2023 |
| Dell          | Inspiron 1120               | Notebook    | [d864592854](https://linux-hardware.org/?probe=d864592854) | Mar 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [bb43e46d71](https://linux-hardware.org/?probe=bb43e46d71) | Mar 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | Notebook    | [beeb327f26](https://linux-hardware.org/?probe=beeb327f26) | Mar 18, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [39d6b256fa](https://linux-hardware.org/?probe=39d6b256fa) | Mar 18, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [5e3e1f990b](https://linux-hardware.org/?probe=5e3e1f990b) | Mar 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [0e6f572d41](https://linux-hardware.org/?probe=0e6f572d41) | Mar 18, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [9a4ac88209](https://linux-hardware.org/?probe=9a4ac88209) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Acer          | Aspire 9410                 | Notebook    | [b124194b0c](https://linux-hardware.org/?probe=b124194b0c) | Mar 17, 2023 |
| Lenovo        | ThinkPad X250 20CL001LMB    | Notebook    | [d78880e600](https://linux-hardware.org/?probe=d78880e600) | Mar 17, 2023 |
| MSI           | GP62 6QE                    | Notebook    | [3db109542c](https://linux-hardware.org/?probe=3db109542c) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7cededfaa9](https://linux-hardware.org/?probe=7cededfaa9) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Dell          | Latitude E7470              | Notebook    | [f2dd0afe92](https://linux-hardware.org/?probe=f2dd0afe92) | Mar 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| HP            | 158A                        | Desktop     | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [293b961af2](https://linux-hardware.org/?probe=293b961af2) | Mar 16, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c7a98e4c15](https://linux-hardware.org/?probe=c7a98e4c15) | Mar 16, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [fac1a255b7](https://linux-hardware.org/?probe=fac1a255b7) | Mar 16, 2023 |
| Toshiba       | Satellite C55-A-1T6         | Notebook    | [71751e4045](https://linux-hardware.org/?probe=71751e4045) | Mar 16, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [2af12bdf73](https://linux-hardware.org/?probe=2af12bdf73) | Mar 16, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [a01912ff82](https://linux-hardware.org/?probe=a01912ff82) | Mar 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [06db6fa9b3](https://linux-hardware.org/?probe=06db6fa9b3) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [92c35e8f43](https://linux-hardware.org/?probe=92c35e8f43) | Mar 15, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [45533fd7eb](https://linux-hardware.org/?probe=45533fd7eb) | Mar 14, 2023 |
| HP            | Notebook                    | Notebook    | [de2e2f370b](https://linux-hardware.org/?probe=de2e2f370b) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| Dell          | 064N3D A00                  | All in one  | [4721bf0213](https://linux-hardware.org/?probe=4721bf0213) | Mar 14, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [d6106fe9e3](https://linux-hardware.org/?probe=d6106fe9e3) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [b3d9dfdb16](https://linux-hardware.org/?probe=b3d9dfdb16) | Mar 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [9eaa09faf0](https://linux-hardware.org/?probe=9eaa09faf0) | Mar 14, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [b54abceafe](https://linux-hardware.org/?probe=b54abceafe) | Mar 14, 2023 |
| HP            | 339A                        | Desktop     | [3110e1b98c](https://linux-hardware.org/?probe=3110e1b98c) | Mar 14, 2023 |
| Dell          | Precision 5570              | Notebook    | [f0d98798a2](https://linux-hardware.org/?probe=f0d98798a2) | Mar 14, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [49737df106](https://linux-hardware.org/?probe=49737df106) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [54d17115b9](https://linux-hardware.org/?probe=54d17115b9) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [79932e56ad](https://linux-hardware.org/?probe=79932e56ad) | Mar 13, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [6d5e3ffeed](https://linux-hardware.org/?probe=6d5e3ffeed) | Mar 13, 2023 |
| Dell          | Precision 7560              | Notebook    | [0b0c4e4b1c](https://linux-hardware.org/?probe=0b0c4e4b1c) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1de50d9986](https://linux-hardware.org/?probe=1de50d9986) | Mar 13, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [303f47547b](https://linux-hardware.org/?probe=303f47547b) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [4247bd6835](https://linux-hardware.org/?probe=4247bd6835) | Mar 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e259b3e70a](https://linux-hardware.org/?probe=e259b3e70a) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| HP            | 339A                        | Desktop     | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [73fe7fd06e](https://linux-hardware.org/?probe=73fe7fd06e) | Mar 11, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [c4792e57b9](https://linux-hardware.org/?probe=c4792e57b9) | Mar 11, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [239832f304](https://linux-hardware.org/?probe=239832f304) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [ef3ba694a9](https://linux-hardware.org/?probe=ef3ba694a9) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [3823c10f89](https://linux-hardware.org/?probe=3823c10f89) | Mar 11, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [682aca59d0](https://linux-hardware.org/?probe=682aca59d0) | Mar 11, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [201f4fc780](https://linux-hardware.org/?probe=201f4fc780) | Mar 11, 2023 |
| Lenovo        | ThinkPad P53 20QN0007FR     | Notebook    | [960d07f083](https://linux-hardware.org/?probe=960d07f083) | Mar 11, 2023 |
| HP            | 212B                        | Desktop     | [0ea1ad02f7](https://linux-hardware.org/?probe=0ea1ad02f7) | Mar 11, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [4d1f3745ac](https://linux-hardware.org/?probe=4d1f3745ac) | Mar 10, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [46160d5ef3](https://linux-hardware.org/?probe=46160d5ef3) | Mar 10, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [c2230a6690](https://linux-hardware.org/?probe=c2230a6690) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [54e498fb2e](https://linux-hardware.org/?probe=54e498fb2e) | Mar 10, 2023 |
| System76      | Gazelle Professional        | Notebook    | [42f5755b1d](https://linux-hardware.org/?probe=42f5755b1d) | Mar 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [335933aedb](https://linux-hardware.org/?probe=335933aedb) | Mar 10, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [da07981235](https://linux-hardware.org/?probe=da07981235) | Mar 10, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [6e55c3caff](https://linux-hardware.org/?probe=6e55c3caff) | Mar 10, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [5f85fdadf1](https://linux-hardware.org/?probe=5f85fdadf1) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [4f689d1291](https://linux-hardware.org/?probe=4f689d1291) | Mar 10, 2023 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [43c7df46f9](https://linux-hardware.org/?probe=43c7df46f9) | Mar 09, 2023 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [19abb737df](https://linux-hardware.org/?probe=19abb737df) | Mar 09, 2023 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [fdb869c840](https://linux-hardware.org/?probe=fdb869c840) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d519ac8d3e](https://linux-hardware.org/?probe=d519ac8d3e) | Mar 09, 2023 |
| Dell          | Latitude E5450              | Notebook    | [6a40dced5b](https://linux-hardware.org/?probe=6a40dced5b) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| HP            | Presario CQ61               | Notebook    | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| ASUSTek       | UX410UAR                    | Notebook    | [4fa93928b1](https://linux-hardware.org/?probe=4fa93928b1) | Mar 09, 2023 |
| Acer          | Aspire 7250                 | Notebook    | [026f2228a3](https://linux-hardware.org/?probe=026f2228a3) | Mar 08, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7e36ff0272](https://linux-hardware.org/?probe=7e36ff0272) | Mar 08, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [a4e6e8e566](https://linux-hardware.org/?probe=a4e6e8e566) | Mar 08, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [cc67f30d28](https://linux-hardware.org/?probe=cc67f30d28) | Mar 08, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [82fee79835](https://linux-hardware.org/?probe=82fee79835) | Mar 08, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [f69aaa84ed](https://linux-hardware.org/?probe=f69aaa84ed) | Mar 08, 2023 |
| ASUSTek       | X705UAR                     | Notebook    | [21ea5828e3](https://linux-hardware.org/?probe=21ea5828e3) | Mar 08, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [cea86809fd](https://linux-hardware.org/?probe=cea86809fd) | Mar 08, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [f18444c5dd](https://linux-hardware.org/?probe=f18444c5dd) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3560              | Notebook    | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [768e0fb7b6](https://linux-hardware.org/?probe=768e0fb7b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [79459b8b4b](https://linux-hardware.org/?probe=79459b8b4b) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [42e5be35d6](https://linux-hardware.org/?probe=42e5be35d6) | Mar 08, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [85e83db4dc](https://linux-hardware.org/?probe=85e83db4dc) | Mar 08, 2023 |
| Packard Be... | IXTREME M5850               | Desktop     | [60b6ba7904](https://linux-hardware.org/?probe=60b6ba7904) | Mar 07, 2023 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [cfb630c626](https://linux-hardware.org/?probe=cfb630c626) | Mar 07, 2023 |
| Acer          | Aspire ES1-732              | Notebook    | [03a5f04251](https://linux-hardware.org/?probe=03a5f04251) | Mar 07, 2023 |
| Chuwi         | LapBook Plus                | Notebook    | [55365bb7ab](https://linux-hardware.org/?probe=55365bb7ab) | Mar 07, 2023 |
| Dell          | Latitude 5590               | Notebook    | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| AZW           | GT-R                        | Notebook    | [cce9cccb8f](https://linux-hardware.org/?probe=cce9cccb8f) | Mar 07, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9e2592768b](https://linux-hardware.org/?probe=9e2592768b) | Mar 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [28dd9d3ce4](https://linux-hardware.org/?probe=28dd9d3ce4) | Mar 06, 2023 |
| ASUSTek       | UX303LB                     | Notebook    | [4137763385](https://linux-hardware.org/?probe=4137763385) | Mar 06, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [6bc7428949](https://linux-hardware.org/?probe=6bc7428949) | Mar 06, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [114bc4ee0c](https://linux-hardware.org/?probe=114bc4ee0c) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [38cb86265f](https://linux-hardware.org/?probe=38cb86265f) | Mar 06, 2023 |
| Dell          | 048DY8 A00                  | Desktop     | [2ae03ba26f](https://linux-hardware.org/?probe=2ae03ba26f) | Mar 06, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [39187f7b13](https://linux-hardware.org/?probe=39187f7b13) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b1357d5c0](https://linux-hardware.org/?probe=9b1357d5c0) | Mar 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [423b13a62d](https://linux-hardware.org/?probe=423b13a62d) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [06bb73cbaa](https://linux-hardware.org/?probe=06bb73cbaa) | Mar 05, 2023 |
| Sony          | SVE1513I4E                  | Notebook    | [76d0570787](https://linux-hardware.org/?probe=76d0570787) | Mar 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [1c1d26f569](https://linux-hardware.org/?probe=1c1d26f569) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | Notebook    | [d8535715f8](https://linux-hardware.org/?probe=d8535715f8) | Mar 05, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [1c918f0aa3](https://linux-hardware.org/?probe=1c918f0aa3) | Mar 05, 2023 |
| Packard Be... | FIH57                       | Desktop     | [06cd872d9b](https://linux-hardware.org/?probe=06cd872d9b) | Mar 05, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [6757b860c8](https://linux-hardware.org/?probe=6757b860c8) | Mar 05, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [b090a8b795](https://linux-hardware.org/?probe=b090a8b795) | Mar 05, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [6e4cec1477](https://linux-hardware.org/?probe=6e4cec1477) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Lenovo        | ThinkPad X270 20HMS4EC0D    | Notebook    | [108c90e7f7](https://linux-hardware.org/?probe=108c90e7f7) | Mar 05, 2023 |
| LG Electro... | R580-K.APC4BE1              | Notebook    | [9cac5bdcfc](https://linux-hardware.org/?probe=9cac5bdcfc) | Mar 05, 2023 |
| Medion        | MS-7800                     | Desktop     | [980dc395c7](https://linux-hardware.org/?probe=980dc395c7) | Mar 05, 2023 |
| Medion        | MS-7800                     | Desktop     | [80b8165141](https://linux-hardware.org/?probe=80b8165141) | Mar 05, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [70ee1f3c06](https://linux-hardware.org/?probe=70ee1f3c06) | Mar 04, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [e038320969](https://linux-hardware.org/?probe=e038320969) | Mar 04, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [bd65553838](https://linux-hardware.org/?probe=bd65553838) | Mar 04, 2023 |
| HP            | Pavilion g7                 | Notebook    | [1f09b36fde](https://linux-hardware.org/?probe=1f09b36fde) | Mar 04, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [f76641318f](https://linux-hardware.org/?probe=f76641318f) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fdb3bcda29](https://linux-hardware.org/?probe=fdb3bcda29) | Mar 04, 2023 |
| Quanta        | S3E-MB 31S3EMB0010          | Server      | [97d3c70fb5](https://linux-hardware.org/?probe=97d3c70fb5) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b0664e4d7](https://linux-hardware.org/?probe=9b0664e4d7) | Mar 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Dell          | Inspiron 1120               | Notebook    | [41f23e384c](https://linux-hardware.org/?probe=41f23e384c) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| Google        | Lulu                        | Notebook    | [eb4cf4fb11](https://linux-hardware.org/?probe=eb4cf4fb11) | Mar 03, 2023 |
| ASUSTek       | STRIX H270I GAMING          | Desktop     | [2ff7fe6634](https://linux-hardware.org/?probe=2ff7fe6634) | Mar 03, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [5316a545d0](https://linux-hardware.org/?probe=5316a545d0) | Mar 03, 2023 |
| HP            | Spectre                     | Convertible | [8e2fdf7f6b](https://linux-hardware.org/?probe=8e2fdf7f6b) | Mar 03, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [1cf53baf99](https://linux-hardware.org/?probe=1cf53baf99) | Mar 03, 2023 |
| HP            | Pavilion 17                 | Notebook    | [de3dcf402a](https://linux-hardware.org/?probe=de3dcf402a) | Mar 03, 2023 |
| Dell          | 0H19HD A06                  | Server      | [be1989f55d](https://linux-hardware.org/?probe=be1989f55d) | Mar 03, 2023 |
| Dell          | Latitude E7440              | Notebook    | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a553120d6e](https://linux-hardware.org/?probe=a553120d6e) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [3908191101](https://linux-hardware.org/?probe=3908191101) | Mar 03, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae34bbf69](https://linux-hardware.org/?probe=dae34bbf69) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | Notebook    | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | Notebook    | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [886538fe37](https://linux-hardware.org/?probe=886538fe37) | Mar 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [75befd2e82](https://linux-hardware.org/?probe=75befd2e82) | Mar 02, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [3a14639664](https://linux-hardware.org/?probe=3a14639664) | Mar 02, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [96a16581c6](https://linux-hardware.org/?probe=96a16581c6) | Mar 02, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [09930df16b](https://linux-hardware.org/?probe=09930df16b) | Mar 02, 2023 |
| Dell          | Latitude 3510               | Notebook    | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [f9213f29ca](https://linux-hardware.org/?probe=f9213f29ca) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [e28307db49](https://linux-hardware.org/?probe=e28307db49) | Mar 01, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [cf6ef752c9](https://linux-hardware.org/?probe=cf6ef752c9) | Mar 01, 2023 |
| ASUSTek       | X556URK                     | Notebook    | [aa7492e59a](https://linux-hardware.org/?probe=aa7492e59a) | Mar 01, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [704b0f3226](https://linux-hardware.org/?probe=704b0f3226) | Mar 01, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [2e34c2ec01](https://linux-hardware.org/?probe=2e34c2ec01) | Mar 01, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [d0ce638961](https://linux-hardware.org/?probe=d0ce638961) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [a637650ff7](https://linux-hardware.org/?probe=a637650ff7) | Mar 01, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| MSI           | MAG B365M MORTAR            | Desktop     | [26f53549dd](https://linux-hardware.org/?probe=26f53549dd) | Feb 28, 2023 |
| Acer          | Aspire X3995                | Desktop     | [eccac5b752](https://linux-hardware.org/?probe=eccac5b752) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [17605a6808](https://linux-hardware.org/?probe=17605a6808) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [2b434f0b1d](https://linux-hardware.org/?probe=2b434f0b1d) | Feb 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [00cd14a724](https://linux-hardware.org/?probe=00cd14a724) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Timi          | TM1701                      | Notebook    | [ab658664bb](https://linux-hardware.org/?probe=ab658664bb) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [e338b721af](https://linux-hardware.org/?probe=e338b721af) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [0264556bba](https://linux-hardware.org/?probe=0264556bba) | Feb 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [371a95fb3d](https://linux-hardware.org/?probe=371a95fb3d) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S23... | Notebook    | [3cd99ed8f4](https://linux-hardware.org/?probe=3cd99ed8f4) | Feb 28, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [594ff7091b](https://linux-hardware.org/?probe=594ff7091b) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| HP            | 3047h                       | Desktop     | [db6be92c4f](https://linux-hardware.org/?probe=db6be92c4f) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [05d3c9f96c](https://linux-hardware.org/?probe=05d3c9f96c) | Feb 27, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [dd74cb518b](https://linux-hardware.org/?probe=dd74cb518b) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f70d3317a2](https://linux-hardware.org/?probe=f70d3317a2) | Feb 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| HP            | Pavilion m6                 | Notebook    | [1e9d802ab6](https://linux-hardware.org/?probe=1e9d802ab6) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | Notebook    | [c49b50f583](https://linux-hardware.org/?probe=c49b50f583) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | Notebook    | [4083a9232f](https://linux-hardware.org/?probe=4083a9232f) | Feb 27, 2023 |
| HP            | Pavilion m6                 | Notebook    | [0d35b0b080](https://linux-hardware.org/?probe=0d35b0b080) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [37d2aab670](https://linux-hardware.org/?probe=37d2aab670) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [19727a16be](https://linux-hardware.org/?probe=19727a16be) | Feb 26, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [6ef23fd12a](https://linux-hardware.org/?probe=6ef23fd12a) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e763fc25e7](https://linux-hardware.org/?probe=e763fc25e7) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [4cd492ee3e](https://linux-hardware.org/?probe=4cd492ee3e) | Feb 26, 2023 |
| ASRock        | B85 Pro4                    | Desktop     | [0b4daba4fb](https://linux-hardware.org/?probe=0b4daba4fb) | Feb 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [ead0312777](https://linux-hardware.org/?probe=ead0312777) | Feb 26, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [3fe348fb3f](https://linux-hardware.org/?probe=3fe348fb3f) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Dell          | Latitude E5450              | Notebook    | [62ce48db27](https://linux-hardware.org/?probe=62ce48db27) | Feb 26, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | Notebook    | [d0b043c11b](https://linux-hardware.org/?probe=d0b043c11b) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9471b0f763](https://linux-hardware.org/?probe=9471b0f763) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [08d12e1049](https://linux-hardware.org/?probe=08d12e1049) | Feb 26, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [5634c4795c](https://linux-hardware.org/?probe=5634c4795c) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | ENVY 17                     | Notebook    | [dea1551bf3](https://linux-hardware.org/?probe=dea1551bf3) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [1b7321e88d](https://linux-hardware.org/?probe=1b7321e88d) | Feb 26, 2023 |
| HP            | ENVY 17                     | Notebook    | [0f347a1b6c](https://linux-hardware.org/?probe=0f347a1b6c) | Feb 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [887241ec59](https://linux-hardware.org/?probe=887241ec59) | Feb 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [724039adf2](https://linux-hardware.org/?probe=724039adf2) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | 3398                        | Desktop     | [5e7ae4c866](https://linux-hardware.org/?probe=5e7ae4c866) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3142c6a90c](https://linux-hardware.org/?probe=3142c6a90c) | Feb 25, 2023 |
| HP            | 18E7                        | Desktop     | [7b52dfac52](https://linux-hardware.org/?probe=7b52dfac52) | Feb 25, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9894743527](https://linux-hardware.org/?probe=9894743527) | Feb 25, 2023 |
| HP            | 3047h                       | Desktop     | [8f7d5acf1f](https://linux-hardware.org/?probe=8f7d5acf1f) | Feb 25, 2023 |
| Dell          | XPS 9315                    | Notebook    | [86fea0e08a](https://linux-hardware.org/?probe=86fea0e08a) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [c99ef001e4](https://linux-hardware.org/?probe=c99ef001e4) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [7089ab33b3](https://linux-hardware.org/?probe=7089ab33b3) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [15cf7c7cd7](https://linux-hardware.org/?probe=15cf7c7cd7) | Feb 24, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [4d45d5880b](https://linux-hardware.org/?probe=4d45d5880b) | Feb 23, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| T-bao         | MINI PC                     | Desktop     | [68ba9fc610](https://linux-hardware.org/?probe=68ba9fc610) | Feb 23, 2023 |
| Packard Be... | ONETWO L5700                | All in one  | [6ec6a6661d](https://linux-hardware.org/?probe=6ec6a6661d) | Feb 22, 2023 |
| HP            | Spectre                     | Convertible | [2366c11489](https://linux-hardware.org/?probe=2366c11489) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [8fde9cab5c](https://linux-hardware.org/?probe=8fde9cab5c) | Feb 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ce8874cff4](https://linux-hardware.org/?probe=ce8874cff4) | Feb 22, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [2b16b06c7f](https://linux-hardware.org/?probe=2b16b06c7f) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [51b83f1e27](https://linux-hardware.org/?probe=51b83f1e27) | Feb 22, 2023 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [2dffc350dd](https://linux-hardware.org/?probe=2dffc350dd) | Feb 22, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [40205862f6](https://linux-hardware.org/?probe=40205862f6) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Foxconn       | Lucknow                     | Desktop     | [3ca9a4f66e](https://linux-hardware.org/?probe=3ca9a4f66e) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| Notebook      | N8xEJEK                     | Notebook    | [1548ea7cab](https://linux-hardware.org/?probe=1548ea7cab) | Feb 21, 2023 |
| Notebook      | N8xEJEK                     | Notebook    | [a8a28d6f2b](https://linux-hardware.org/?probe=a8a28d6f2b) | Feb 21, 2023 |
| ASUSTek       | X55VD                       | Notebook    | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9978852d07](https://linux-hardware.org/?probe=9978852d07) | Feb 21, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [4fc47f45be](https://linux-hardware.org/?probe=4fc47f45be) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| Dell          | Vostro 15 7510              | Notebook    | [df764baed8](https://linux-hardware.org/?probe=df764baed8) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9aee694156](https://linux-hardware.org/?probe=9aee694156) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fafd1c2888](https://linux-hardware.org/?probe=fafd1c2888) | Feb 21, 2023 |
| ASUSTek       | K70IC                       | Notebook    | [e5aad61a1b](https://linux-hardware.org/?probe=e5aad61a1b) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| ASUSTek       | UX410UQK                    | Notebook    | [0a23974b1b](https://linux-hardware.org/?probe=0a23974b1b) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [082f5559c7](https://linux-hardware.org/?probe=082f5559c7) | Feb 20, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [e26b379150](https://linux-hardware.org/?probe=e26b379150) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [2a403bdb2b](https://linux-hardware.org/?probe=2a403bdb2b) | Feb 20, 2023 |
| Gigabyte      | 945P-S3                     | Desktop     | [2cdcb107ab](https://linux-hardware.org/?probe=2cdcb107ab) | Feb 20, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [53ba72d592](https://linux-hardware.org/?probe=53ba72d592) | Feb 20, 2023 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [32b47345a6](https://linux-hardware.org/?probe=32b47345a6) | Feb 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [a5124a64e6](https://linux-hardware.org/?probe=a5124a64e6) | Feb 19, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [7e45218236](https://linux-hardware.org/?probe=7e45218236) | Feb 19, 2023 |
| HP            | 2B56                        | All in one  | [25c4d7a993](https://linux-hardware.org/?probe=25c4d7a993) | Feb 19, 2023 |
| ASUSTek       | G10AC                       | Desktop     | [8a367bb885](https://linux-hardware.org/?probe=8a367bb885) | Feb 19, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [b999af6719](https://linux-hardware.org/?probe=b999af6719) | Feb 19, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [54807bcb6c](https://linux-hardware.org/?probe=54807bcb6c) | Feb 18, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [24e71c037b](https://linux-hardware.org/?probe=24e71c037b) | Feb 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| Sony          | VGN-NW21MF_W                | Notebook    | [e46cfcff64](https://linux-hardware.org/?probe=e46cfcff64) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| IP3 Tech      | Cherry Trail CR             | Desktop     | [0ff2dc2202](https://linux-hardware.org/?probe=0ff2dc2202) | Feb 17, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [8da7f7cbdc](https://linux-hardware.org/?probe=8da7f7cbdc) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [4a3d5fee69](https://linux-hardware.org/?probe=4a3d5fee69) | Feb 17, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | Notebook    | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [7c5f2f584e](https://linux-hardware.org/?probe=7c5f2f584e) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53055b0d6e](https://linux-hardware.org/?probe=53055b0d6e) | Feb 16, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [078d55d158](https://linux-hardware.org/?probe=078d55d158) | Feb 16, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| MSI           | H61M-E33                    | Desktop     | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| Dell          | Precision 5570              | Notebook    | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Shenzhen W... | AERO 3                      | Mini pc     | [6c8324859d](https://linux-hardware.org/?probe=6c8324859d) | Feb 16, 2023 |
| Dell          | Latitude 7330               | Notebook    | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [a9e4d33e06](https://linux-hardware.org/?probe=a9e4d33e06) | Feb 16, 2023 |
| Dell          | Precision 5750              | Notebook    | [7b814aee7c](https://linux-hardware.org/?probe=7b814aee7c) | Feb 16, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [676c244c1d](https://linux-hardware.org/?probe=676c244c1d) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Dell          | Inspiron 7405 2n1           | Convertible | [3041828966](https://linux-hardware.org/?probe=3041828966) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| Dell          | Precision 5570              | Notebook    | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| Shenzhen W... | AERO 3                      | Mini pc     | [9cbb805c11](https://linux-hardware.org/?probe=9cbb805c11) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Supermicro    | X7DCL                       | Desktop     | [49e545591c](https://linux-hardware.org/?probe=49e545591c) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e1d323e96f](https://linux-hardware.org/?probe=e1d323e96f) | Feb 15, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [4d00371a70](https://linux-hardware.org/?probe=4d00371a70) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [b9301138cc](https://linux-hardware.org/?probe=b9301138cc) | Feb 14, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [542f27e209](https://linux-hardware.org/?probe=542f27e209) | Feb 14, 2023 |
| HP            | 805D                        | Desktop     | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5d2153f4f2](https://linux-hardware.org/?probe=5d2153f4f2) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS4AN00    | Notebook    | [ec8fbb6350](https://linux-hardware.org/?probe=ec8fbb6350) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| Lenovo        | 30BE SDK0K17763 WIN 1801... | Desktop     | [837c0bcb6a](https://linux-hardware.org/?probe=837c0bcb6a) | Feb 14, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [2914a1866d](https://linux-hardware.org/?probe=2914a1866d) | Feb 14, 2023 |
| Google        | Lulu                        | Notebook    | [15fa093522](https://linux-hardware.org/?probe=15fa093522) | Feb 14, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4ccd4c2da2](https://linux-hardware.org/?probe=4ccd4c2da2) | Feb 14, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Thomson       | N17V3C4WH128                | Notebook    | [57eacd1a37](https://linux-hardware.org/?probe=57eacd1a37) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [6cf7a75c9e](https://linux-hardware.org/?probe=6cf7a75c9e) | Feb 13, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [36bf8af789](https://linux-hardware.org/?probe=36bf8af789) | Feb 13, 2023 |
| MSI           | MS-B9181                    | Desktop     | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Dell          | Latitude E6320              | Notebook    | [32ad32fb45](https://linux-hardware.org/?probe=32ad32fb45) | Feb 13, 2023 |
| ASRock        | E350M1                      | Desktop     | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5b93510482](https://linux-hardware.org/?probe=5b93510482) | Feb 13, 2023 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [24d20958ab](https://linux-hardware.org/?probe=24d20958ab) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [2032f6e202](https://linux-hardware.org/?probe=2032f6e202) | Feb 13, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [eec95070bb](https://linux-hardware.org/?probe=eec95070bb) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| ASUSTek       | G771JM                      | Notebook    | [af72d8c72f](https://linux-hardware.org/?probe=af72d8c72f) | Feb 12, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [7d57fccbf0](https://linux-hardware.org/?probe=7d57fccbf0) | Feb 12, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [68db95ee9b](https://linux-hardware.org/?probe=68db95ee9b) | Feb 12, 2023 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [3a16a28774](https://linux-hardware.org/?probe=3a16a28774) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a74e071a54](https://linux-hardware.org/?probe=a74e071a54) | Feb 12, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [861c0d497e](https://linux-hardware.org/?probe=861c0d497e) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| Acer          | Aspire E5-574G              | Notebook    | [cdbd2ad757](https://linux-hardware.org/?probe=cdbd2ad757) | Feb 12, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [121fcf8fd6](https://linux-hardware.org/?probe=121fcf8fd6) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [9e28099913](https://linux-hardware.org/?probe=9e28099913) | Feb 11, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [350850e668](https://linux-hardware.org/?probe=350850e668) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [523c719e5b](https://linux-hardware.org/?probe=523c719e5b) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [d4e29128dd](https://linux-hardware.org/?probe=d4e29128dd) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7001PF... | Notebook    | [f6d2fc27d1](https://linux-hardware.org/?probe=f6d2fc27d1) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | Notebook    | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [d9707b086e](https://linux-hardware.org/?probe=d9707b086e) | Feb 10, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [200c5bc81b](https://linux-hardware.org/?probe=200c5bc81b) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | Notebook    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [9da08e5265](https://linux-hardware.org/?probe=9da08e5265) | Feb 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [df85a15b13](https://linux-hardware.org/?probe=df85a15b13) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [756bc1fc3b](https://linux-hardware.org/?probe=756bc1fc3b) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [769b226f8e](https://linux-hardware.org/?probe=769b226f8e) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | Notebook    | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [077853b2db](https://linux-hardware.org/?probe=077853b2db) | Feb 09, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [57a1d5072b](https://linux-hardware.org/?probe=57a1d5072b) | Feb 09, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [fca49121d5](https://linux-hardware.org/?probe=fca49121d5) | Feb 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1f4b88ad7f](https://linux-hardware.org/?probe=1f4b88ad7f) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a77dd320a8](https://linux-hardware.org/?probe=a77dd320a8) | Feb 09, 2023 |
| Dell          | Precision 5570              | Notebook    | [52cd3af211](https://linux-hardware.org/?probe=52cd3af211) | Feb 09, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [546ea7c2e8](https://linux-hardware.org/?probe=546ea7c2e8) | Feb 09, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [77dafc35f5](https://linux-hardware.org/?probe=77dafc35f5) | Feb 09, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [afaaed1c36](https://linux-hardware.org/?probe=afaaed1c36) | Feb 09, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9d947022b0](https://linux-hardware.org/?probe=9d947022b0) | Feb 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1737      | 18.4%   |
| Ubuntu 22.04       | 561       | 5.94%   |
| Ubuntu 18.04       | 554       | 5.87%   |
| Debian 11          | 372       | 3.94%   |
| OpenMandriva 4.2   | 363       | 3.85%   |
| OpenMandriva 4.3   | 294       | 3.11%   |
| Xubuntu 20.04      | 196       | 2.08%   |
| Linux Mint 20.3    | 189       | 2%      |
| OpenMandriva 23.01 | 151       | 1.6%    |
| Arch Rolling       | 146       | 1.55%   |
| Debian 10          | 134       | 1.42%   |
| Arch               | 124       | 1.31%   |
| Ubuntu 21.10       | 122       | 1.29%   |
| Ubuntu 20.10       | 109       | 1.15%   |
| Linux Mint 20.2    | 107       | 1.13%   |
| Ubuntu 21.04       | 106       | 1.12%   |
| Linux Mint 20.1    | 106       | 1.12%   |
| Linux Mint 21.1    | 92        | 0.97%   |
| Zorin 16           | 91        | 0.96%   |
| Manjaro            | 91        | 0.96%   |
| Fedora 33          | 89        | 0.94%   |
| Linux Mint 19.3    | 88        | 0.93%   |
| Ubuntu 19.10       | 85        | 0.9%    |
| Kubuntu 20.04      | 83        | 0.88%   |
| Xubuntu 18.04      | 78        | 0.83%   |
| Linux Mint 21      | 77        | 0.82%   |
| Linux Mint 20      | 77        | 0.82%   |
| Fedora 34          | 75        | 0.79%   |
| Ubuntu 22.10       | 71        | 0.75%   |
| Ubuntu 19.04       | 71        | 0.75%   |
| KDE neon 20.04     | 71        | 0.75%   |
| Fedora 35          | 70        | 0.74%   |
| Pop!_OS 22.04      | 69        | 0.73%   |
| OpenMandriva 23.03 | 69        | 0.73%   |
| Fedora 32          | 69        | 0.73%   |
| Fedora 37          | 67        | 0.71%   |
| Fedora 36          | 66        | 0.7%    |
| Ubuntu MATE 20.04  | 63        | 0.67%   |
| Lubuntu 20.04      | 59        | 0.63%   |
| Kubuntu 22.04      | 55        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3342      | 37.45%  |
| OpenMandriva  | 930       | 10.42%  |
| Linux Mint    | 742       | 8.32%   |
| Debian        | 622       | 6.97%   |
| Fedora        | 416       | 4.66%   |
| Xubuntu       | 364       | 4.08%   |
| Arch          | 264       | 2.96%   |
| Manjaro       | 241       | 2.7%    |
| Pop!_OS       | 229       | 2.57%   |
| Kubuntu       | 212       | 2.38%   |
| ROSA          | 175       | 1.96%   |
| Zorin         | 136       | 1.52%   |
| Ubuntu MATE   | 126       | 1.41%   |
| Lubuntu       | 110       | 1.23%   |
| KDE neon      | 96        | 1.08%   |
| Ubuntu Unity  | 69        | 0.77%   |
| openSUSE      | 67        | 0.75%   |
| Gentoo        | 65        | 0.73%   |
| Kali          | 55        | 0.62%   |
| ArcoLinux     | 53        | 0.59%   |
| Endless       | 52        | 0.58%   |
| Elementary    | 47        | 0.53%   |
| Ubuntu Budgie | 45        | 0.5%    |
| EndeavourOS   | 35        | 0.39%   |
| LMDE          | 34        | 0.38%   |
| BlackPanther  | 33        | 0.37%   |
| CentOS        | 29        | 0.33%   |
| SteamOS       | 27        | 0.3%    |
| Ubuntu Studio | 23        | 0.26%   |
| Mageia        | 21        | 0.24%   |
| Parrot        | 20        | 0.22%   |
| Clear Linux   | 19        | 0.21%   |
| MX            | 16        | 0.18%   |
| Kaisen        | 12        | 0.13%   |
| Nobara        | 11        | 0.12%   |
| Raspbian      | 10        | 0.11%   |
| NixOS         | 10        | 0.11%   |
| Manjaro-ARM   | 10        | 0.11%   |
| LinuxFX       | 10        | 0.11%   |
| Devuan        | 10        | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 346       | 3.35%   |
| 5.16.7-desktop-1omv4003  | 273       | 2.65%   |
| 6.1.1-desktop-1omv2290   | 133       | 1.29%   |
| 5.4.0-42-generic         | 128       | 1.24%   |
| 5.15.0-56-generic        | 126       | 1.22%   |
| 5.4.0-58-generic         | 99        | 0.96%   |
| 5.15.0-58-generic        | 98        | 0.95%   |
| 5.15.0-52-generic        | 94        | 0.91%   |
| 5.4.0-52-generic         | 81        | 0.78%   |
| 5.11.0-38-generic        | 77        | 0.75%   |
| 5.11.0-27-generic        | 76        | 0.74%   |
| 5.15.0-48-generic        | 74        | 0.72%   |
| 5.4.0-26-generic         | 73        | 0.71%   |
| 5.8.0-43-generic         | 69        | 0.67%   |
| 5.4.0-48-generic         | 69        | 0.67%   |
| 5.15.0-46-generic        | 66        | 0.64%   |
| 5.11.0-37-generic        | 66        | 0.64%   |
| 5.4.0-65-generic         | 65        | 0.63%   |
| 5.8.0-50-generic         | 63        | 0.61%   |
| 5.15.0-43-generic        | 60        | 0.58%   |
| 6.2.6-desktop-1omv2390   | 59        | 0.57%   |
| 5.19.0-38-generic        | 58        | 0.56%   |
| 5.19.0-35-generic        | 58        | 0.56%   |
| 5.11.0-40-generic        | 57        | 0.55%   |
| 5.4.0-29-generic         | 55        | 0.53%   |
| 5.15.0-47-generic        | 55        | 0.53%   |
| 5.13.0-28-generic        | 55        | 0.53%   |
| 5.8.0-44-generic         | 54        | 0.52%   |
| 5.4.0-91-generic         | 54        | 0.52%   |
| 5.4.0-54-generic         | 54        | 0.52%   |
| 5.8.0-48-generic         | 53        | 0.51%   |
| 5.4.0-37-generic         | 53        | 0.51%   |
| 5.13.0-39-generic        | 52        | 0.5%    |
| 5.11.0-43-generic        | 51        | 0.49%   |
| 5.15.0-60-generic        | 50        | 0.48%   |
| 5.4.0-81-generic         | 48        | 0.47%   |
| 5.15.0-53-generic        | 48        | 0.47%   |
| 5.11.0-34-generic        | 48        | 0.47%   |
| 5.8.0-59-generic         | 46        | 0.45%   |
| 5.15.0-41-generic        | 46        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1771      | 18.25%  |
| 5.15.0  | 991       | 10.21%  |
| 5.11.0  | 632       | 6.51%   |
| 5.8.0   | 612       | 6.31%   |
| 5.13.0  | 520       | 5.36%   |
| 4.15.0  | 439       | 4.52%   |
| 5.10.0  | 392       | 4.04%   |
| 5.10.14 | 349       | 3.6%    |
| 5.3.0   | 288       | 2.97%   |
| 5.16.7  | 275       | 2.83%   |
| 5.19.0  | 270       | 2.78%   |
| 5.0.0   | 164       | 1.69%   |
| 6.1.1   | 147       | 1.51%   |
| 4.18.0  | 137       | 1.41%   |
| 4.19.0  | 128       | 1.32%   |
| 6.2.6   | 72        | 0.74%   |
| 5.14.0  | 45        | 0.46%   |
| 6.0.0   | 40        | 0.41%   |
| 4.9.20  | 35        | 0.36%   |
| 5.11.12 | 34        | 0.35%   |
| 5.18.12 | 32        | 0.33%   |
| 5.18.0  | 32        | 0.33%   |
| 5.17.5  | 31        | 0.32%   |
| 6.1.0   | 30        | 0.31%   |
| 4.18.16 | 30        | 0.31%   |
| 5.16.13 | 28        | 0.29%   |
| 5.16.0  | 28        | 0.29%   |
| 4.4.0   | 28        | 0.29%   |
| 5.9.0   | 25        | 0.26%   |
| 5.12.4  | 23        | 0.24%   |
| 4.9.60  | 23        | 0.24%   |
| 5.19.12 | 22        | 0.23%   |
| 5.13.19 | 19        | 0.2%    |
| 6.0.12  | 18        | 0.19%   |
| 5.9.16  | 18        | 0.19%   |
| 5.9.11  | 18        | 0.19%   |
| 5.7.0   | 18        | 0.19%   |
| 5.6.0   | 18        | 0.19%   |
| 4.9.0   | 18        | 0.19%   |
| 5.17.1  | 17        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1866      | 19.49%  |
| 5.15    | 1194      | 12.47%  |
| 5.10    | 884       | 9.23%   |
| 5.11    | 727       | 7.59%   |
| 5.8     | 701       | 7.32%   |
| 5.13    | 603       | 6.3%    |
| 4.15    | 440       | 4.59%   |
| 5.16    | 401       | 4.19%   |
| 5.19    | 363       | 3.79%   |
| 5.3     | 329       | 3.44%   |
| 6.1     | 269       | 2.81%   |
| 5.0     | 177       | 1.85%   |
| 4.18    | 170       | 1.78%   |
| 6.2     | 153       | 1.6%    |
| 4.19    | 145       | 1.51%   |
| 6.0     | 140       | 1.46%   |
| 5.14    | 132       | 1.38%   |
| 5.18    | 130       | 1.36%   |
| 4.9     | 120       | 1.25%   |
| 5.9     | 119       | 1.24%   |
| 5.17    | 107       | 1.12%   |
| 5.6     | 82        | 0.86%   |
| 5.7     | 73        | 0.76%   |
| 5.12    | 70        | 0.73%   |
| 5.5     | 39        | 0.41%   |
| 4.4     | 32        | 0.33%   |
| 4.1     | 24        | 0.25%   |
| 3.10    | 15        | 0.16%   |
| 5.2     | 13        | 0.14%   |
| 4.14    | 12        | 0.13%   |
| 4.12    | 9         | 0.09%   |
| 4.20    | 7         | 0.07%   |
| 4.13    | 7         | 0.07%   |
| 5.1     | 6         | 0.06%   |
| 4.10    | 4         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 4.17    | 2         | 0.02%   |
| 3.4     | 2         | 0.02%   |
| 6.3     | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8385      | 96.69%  |
| i686    | 218       | 2.51%   |
| aarch64 | 44        | 0.51%   |
| armv7l  | 19        | 0.22%   |
| armv6l  | 3         | 0.03%   |
| armv8l  | 2         | 0.02%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3967      | 44.06%  |
| KDE5              | 1606      | 17.84%  |
| Unknown           | 897       | 9.96%   |
| XFCE              | 790       | 8.77%   |
| X-Cinnamon        | 524       | 5.82%   |
| MATE              | 346       | 3.84%   |
| Cinnamon          | 131       | 1.46%   |
| LXQt              | 125       | 1.39%   |
| KDE               | 117       | 1.3%    |
| KDE4              | 115       | 1.28%   |
| Unity             | 70        | 0.78%   |
| i3                | 69        | 0.77%   |
| Budgie            | 54        | 0.6%    |
| Pantheon          | 49        | 0.54%   |
| LXDE              | 39        | 0.43%   |
| GNOME Flashback   | 26        | 0.29%   |
| GNOME Classic     | 13        | 0.14%   |
| Deepin            | 12        | 0.13%   |
| sway              | 8         | 0.09%   |
| awesome           | 7         | 0.08%   |
| qtile             | 5         | 0.06%   |
| bspwm             | 5         | 0.06%   |
| Trinity           | 3         | 0.03%   |
| ICEWM             | 3         | 0.03%   |
| i3-with-shmlog    | 3         | 0.03%   |
| Openbox           | 2         | 0.02%   |
| lightdm-xsession  | 2         | 0.02%   |
| Hyprland          | 2         | 0.02%   |
| GNUstep           | 2         | 0.02%   |
| Enlightenment     | 2         | 0.02%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| LeftWM            | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| dwm-sc            | 1         | 0.01%   |
| DWM               | 1         | 0.01%   |
| chadwm            | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6955      | 78.03%  |
| Wayland | 1264      | 14.18%  |
| Unknown | 434       | 4.87%   |
| Tty     | 260       | 2.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3396      | 37.67%  |
| SDDM    | 1597      | 17.71%  |
| GDM     | 1540      | 17.08%  |
| LightDM | 1011      | 11.21%  |
| GDM3    | 988       | 10.96%  |
| TDM     | 334       | 3.7%    |
| KDM     | 111       | 1.23%   |
| XDM     | 11        | 0.12%   |
| SLiM    | 9         | 0.1%    |
| Ly      | 8         | 0.09%   |
| LXDM    | 4         | 0.04%   |
| NODM    | 3         | 0.03%   |
| WDM     | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| fr_FR       | 6149      | 69.57%  |
| en_US       | 1481      | 16.76%  |
| Unknown     | 750       | 8.49%   |
| en_GB       | 144       | 1.63%   |
| C           | 96        | 1.09%   |
| de_DE       | 26        | 0.29%   |
| ru_RU       | 22        | 0.25%   |
| es_ES       | 15        | 0.17%   |
| it_IT       | 14        | 0.16%   |
| nl_NL       | 12        | 0.14%   |
| fr_CH       | 11        | 0.12%   |
| pl_PL       | 10        | 0.11%   |
| fr_CA       | 10        | 0.11%   |
| en_IE       | 9         | 0.1%    |
| pt_PT       | 8         | 0.09%   |
| fr_BE       | 7         | 0.08%   |
| POSIX       | 6         | 0.07%   |
| sv_SE       | 4         | 0.05%   |
| ru_UA       | 4         | 0.05%   |
| en_AU       | 4         | 0.05%   |
| C.UTF8      | 4         | 0.05%   |
| pt_BR       | 3         | 0.03%   |
| fr_FR.UTF8  | 3         | 0.03%   |
| en_IN       | 3         | 0.03%   |
| ro_RO       | 2         | 0.02%   |
| nb_NO       | 2         | 0.02%   |
| hu_HU       | 2         | 0.02%   |
| fr_LU       | 2         | 0.02%   |
| en_DK       | 2         | 0.02%   |
| en_CA       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| cs_CZ       | 2         | 0.02%   |
| zh_CN       | 1         | 0.01%   |
| UTF-8       | 1         | 0.01%   |
| tr_TR       | 1         | 0.01%   |
| sr_RS@latin | 1         | 0.01%   |
| sr_RS       | 1         | 0.01%   |
| sk_SK       | 1         | 0.01%   |
| oc_FR       | 1         | 0.01%   |
| fr_FR.utf-8 | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4577      | 51.77%  |
| BIOS | 4264      | 48.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 7069      | 79.84%  |
| Overlay  | 831       | 9.39%   |
| Btrfs    | 532       | 6.01%   |
| Unknown  | 221       | 2.5%    |
| Xfs      | 89        | 1.01%   |
| Zfs      | 51        | 0.58%   |
| Ext2     | 15        | 0.17%   |
| F2fs     | 14        | 0.16%   |
| Tmpfs    | 13        | 0.15%   |
| Ext3     | 13        | 0.15%   |
| Reiserfs | 3         | 0.03%   |
| Rootfs   | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3894      | 43.81%  |
| Unknown | 3599      | 40.49%  |
| MBR     | 1395      | 15.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7183      | 81.26%  |
| Yes       | 1657      | 18.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5946      | 67.39%  |
| Yes       | 2877      | 32.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1750      | 20.19%  |
| Dell                    | 1257      | 14.5%   |
| Hewlett-Packard         | 1111      | 12.82%  |
| Lenovo                  | 972       | 11.21%  |
| MSI                     | 731       | 8.43%   |
| Gigabyte Technology     | 505       | 5.83%   |
| Acer                    | 441       | 5.09%   |
| ASRock                  | 209       | 2.41%   |
| Toshiba                 | 160       | 1.85%   |
| Apple                   | 154       | 1.78%   |
| Intel                   | 127       | 1.47%   |
| Packard Bell            | 99        | 1.14%   |
| Notebook                | 84        | 0.97%   |
| HUAWEI                  | 75        | 0.87%   |
| Samsung Electronics     | 66        | 0.76%   |
| Unknown                 | 65        | 0.75%   |
| Sony                    | 61        | 0.7%    |
| Foxconn                 | 49        | 0.57%   |
| Pegatron                | 42        | 0.48%   |
| Fujitsu                 | 40        | 0.46%   |
| Raspberry Pi Foundation | 38        | 0.44%   |
| eMachines               | 36        | 0.42%   |
| Medion                  | 32        | 0.37%   |
| TUXEDO                  | 29        | 0.33%   |
| Supermicro              | 25        | 0.29%   |
| Valve                   | 24        | 0.28%   |
| Timi                    | 23        | 0.27%   |
| Microsoft               | 22        | 0.25%   |
| Alienware               | 22        | 0.25%   |
| Fujitsu Siemens         | 21        | 0.24%   |
| Thomson                 | 20        | 0.23%   |
| Clevo                   | 20        | 0.23%   |
| AZW                     | 20        | 0.23%   |
| UNOWHY                  | 18        | 0.21%   |
| Shuttle                 | 16        | 0.18%   |
| PC Specialist           | 15        | 0.17%   |
| Chuwi                   | 15        | 0.17%   |
| Google                  | 14        | 0.16%   |
| BESSTAR Tech            | 14        | 0.16%   |
| ECS                     | 13        | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| ASUS All Series           | 121       | 1.4%    |
| Unknown                   | 85        | 0.98%   |
| HP Notebook               | 39        | 0.45%   |
| Gigabyte B450M DS3H       | 29        | 0.33%   |
| HP Pavilion dv6           | 27        | 0.31%   |
| HP Pavilion 17            | 26        | 0.3%    |
| Valve Jupiter             | 24        | 0.28%   |
| HP Pavilion dv7           | 24        | 0.28%   |
| ASUS S551LN               | 22        | 0.25%   |
| Dell OptiPlex 390         | 21        | 0.24%   |
| Dell OptiPlex 7010        | 19        | 0.22%   |
| Dell XPS 13 9310          | 18        | 0.21%   |
| HP Pavilion g7            | 17        | 0.2%    |
| Dell OptiPlex 9020        | 17        | 0.2%    |
| ASUS PRIME A320M-K        | 17        | 0.2%    |
| MSI MS-7C91               | 16        | 0.18%   |
| MSI MS-7C02               | 15        | 0.17%   |
| HP Pavilion Notebook      | 15        | 0.17%   |
| Dell XPS 13 9380          | 15        | 0.17%   |
| Dell XPS 13 7390          | 15        | 0.17%   |
| Dell Latitude E6420       | 15        | 0.17%   |
| MSI MS-7C37               | 14        | 0.16%   |
| MSI MS-7816               | 14        | 0.16%   |
| Dell XPS 15 9570          | 14        | 0.16%   |
| MSI MS-7817               | 13        | 0.15%   |
| MSI MS-7758               | 13        | 0.15%   |
| HUAWEI HVY-WXX9           | 13        | 0.15%   |
| HP Pavilion g6            | 13        | 0.15%   |
| HP EliteBook 840 G3       | 13        | 0.15%   |
| HP EliteBook 840 G2       | 13        | 0.15%   |
| Gigabyte 970A-DS3P        | 13        | 0.15%   |
| Dell XPS 15 7590          | 13        | 0.15%   |
| Dell OptiPlex 3020        | 13        | 0.15%   |
| Dell Latitude 5420        | 13        | 0.15%   |
| MSI MS-7693               | 12        | 0.14%   |
| HP Pavilion 15            | 12        | 0.14%   |
| HP Compaq Elite 8300 SFF  | 12        | 0.14%   |
| Gigabyte B450 AORUS ELITE | 12        | 0.14%   |
| Dell XPS 15 9500          | 12        | 0.14%   |
| Dell Latitude 5400        | 12        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 469       | 5.41%   |
| Dell Latitude         | 351       | 4.05%   |
| Acer Aspire           | 292       | 3.37%   |
| HP Pavilion           | 237       | 2.73%   |
| Dell Precision        | 226       | 2.61%   |
| Dell OptiPlex         | 184       | 2.12%   |
| Dell XPS              | 179       | 2.07%   |
| Dell Inspiron         | 167       | 1.93%   |
| HP EliteBook          | 163       | 1.88%   |
| Lenovo IdeaPad        | 156       | 1.8%    |
| ASUS PRIME            | 149       | 1.72%   |
| Toshiba Satellite     | 131       | 1.51%   |
| HP ProBook            | 125       | 1.44%   |
| ASUS All              | 121       | 1.4%    |
| ASUS VivoBook         | 119       | 1.37%   |
| HP Compaq             | 116       | 1.34%   |
| ASUS ROG              | 113       | 1.3%    |
| Lenovo ThinkCentre    | 96        | 1.11%   |
| Unknown               | 85        | 0.98%   |
| ASUS TUF              | 80        | 0.92%   |
| HP Laptop             | 73        | 0.84%   |
| ASUS ZenBook          | 58        | 0.67%   |
| Dell Vostro           | 51        | 0.59%   |
| Packard Bell EasyNote | 50        | 0.58%   |
| Acer Swift            | 45        | 0.52%   |
| Lenovo Legion         | 40        | 0.46%   |
| HP Notebook           | 39        | 0.45%   |
| RPi Raspberry         | 38        | 0.44%   |
| HP ENVY               | 37        | 0.43%   |
| HP ZBook              | 35        | 0.4%    |
| Gigabyte B450M        | 35        | 0.4%    |
| Lenovo Yoga           | 34        | 0.39%   |
| Packard Bell IMEDIA   | 29        | 0.33%   |
| HP EliteDesk          | 28        | 0.32%   |
| ASUS ASUS             | 28        | 0.32%   |
| Dell PowerEdge        | 27        | 0.31%   |
| Acer Nitro            | 27        | 0.31%   |
| HP ProDesk            | 26        | 0.3%    |
| HP OMEN               | 25        | 0.29%   |
| ASUS P8Z77-V          | 25        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 820       | 9.46%   |
| 2020    | 791       | 9.13%   |
| 2019    | 768       | 8.86%   |
| 2012    | 685       | 7.9%    |
| 2013    | 649       | 7.49%   |
| 2011    | 567       | 6.54%   |
| 2021    | 542       | 6.25%   |
| 2015    | 521       | 6.01%   |
| 2014    | 507       | 5.85%   |
| 2017    | 502       | 5.79%   |
| 2010    | 466       | 5.38%   |
| 2016    | 441       | 5.09%   |
| 2009    | 383       | 4.42%   |
| 2008    | 380       | 4.38%   |
| 2022    | 211       | 2.43%   |
| 2007    | 195       | 2.25%   |
| 2006    | 102       | 1.18%   |
| Unknown | 58        | 0.67%   |
| 2005    | 47        | 0.54%   |
| 2004    | 12        | 0.14%   |
| 2023    | 10        | 0.12%   |
| 2003    | 7         | 0.08%   |
| 2002    | 2         | 0.02%   |
| 2001    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4802      | 55.4%   |
| Desktop        | 3321      | 38.31%  |
| Convertible    | 136       | 1.57%   |
| Mini pc        | 125       | 1.44%   |
| All in one     | 100       | 1.15%   |
| Server         | 69        | 0.8%    |
| System on chip | 53        | 0.61%   |
| Tablet         | 51        | 0.59%   |
| Phone          | 10        | 0.12%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7977      | 91.43%  |
| Enabled  | 748       | 8.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8646      | 99.73%  |
| Yes  | 23        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1934      | 22%     |
| 3.01-4.0        | 1884      | 21.44%  |
| 16.01-24.0      | 1816      | 20.66%  |
| 8.01-16.0       | 1499      | 17.06%  |
| 32.01-64.0      | 739       | 8.41%   |
| 1.01-2.0        | 350       | 3.98%   |
| 64.01-256.0     | 194       | 2.21%   |
| 2.01-3.0        | 148       | 1.68%   |
| 24.01-32.0      | 133       | 1.51%   |
| 0.51-1.0        | 64        | 0.73%   |
| 0.01-0.5        | 13        | 0.15%   |
| More than 256.0 | 10        | 0.11%   |
| Unknown         | 5         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3400      | 35.71%  |
| 2.01-3.0    | 2334      | 24.51%  |
| 4.01-8.0    | 1334      | 14.01%  |
| 3.01-4.0    | 1203      | 12.63%  |
| 0.51-1.0    | 637       | 6.69%   |
| 8.01-16.0   | 382       | 4.01%   |
| 0.01-0.5    | 131       | 1.38%   |
| 16.01-24.0  | 55        | 0.58%   |
| 32.01-64.0  | 18        | 0.19%   |
| 24.01-32.0  | 16        | 0.17%   |
| Unknown     | 9         | 0.09%   |
| 64.01-256.0 | 3         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5200      | 58.48%  |
| 2       | 2249      | 25.29%  |
| 3       | 725       | 8.15%   |
| 4       | 338       | 3.8%    |
| 5       | 151       | 1.7%    |
| 6       | 78        | 0.88%   |
| 0       | 76        | 0.85%   |
| 7       | 41        | 0.46%   |
| 8       | 14        | 0.16%   |
| 9       | 7         | 0.08%   |
| Unknown | 4         | 0.04%   |
| 10      | 2         | 0.02%   |
| 25      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 13      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4880      | 55.81%  |
| Yes       | 3864      | 44.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7577      | 87.18%  |
| No        | 1114      | 12.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6398      | 73.25%  |
| No        | 2337      | 26.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4906      | 55.91%  |
| No        | 3869      | 44.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 8668      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 1345      | 14.37%  |
| Lyon             | 180       | 1.92%   |
| Marseille        | 158       | 1.69%   |
| Toulouse         | 137       | 1.46%   |
| Nantes           | 110       | 1.18%   |
| Strasbourg       | 97        | 1.04%   |
| Montpellier      | 84        | 0.9%    |
| Rennes           | 76        | 0.81%   |
| Bordeaux         | 74        | 0.79%   |
| Roubaix          | 70        | 0.75%   |
| Grenoble         | 68        | 0.73%   |
| Lille            | 66        | 0.71%   |
| Nice             | 60        | 0.64%   |
| Clichy-sous-Bois | 58        | 0.62%   |
| Brest            | 45        | 0.48%   |
| Tours            | 41        | 0.44%   |
| Caen             | 38        | 0.41%   |
| La Rochelle      | 36        | 0.38%   |
| Villeurbanne     | 35        | 0.37%   |
| Toulon           | 35        | 0.37%   |
| Poitiers         | 35        | 0.37%   |
| Rouen            | 34        | 0.36%   |
| Aix-en-Provence  | 31        | 0.33%   |
| Argenteuil       | 30        | 0.32%   |
| Nîmes           | 29        | 0.31%   |
| Cergy            | 29        | 0.31%   |
| Pau              | 28        | 0.3%    |
| Metz             | 28        | 0.3%    |
| Clermont-Ferrand | 28        | 0.3%    |
| Angers           | 28        | 0.3%    |
| Versailles       | 27        | 0.29%   |
| Nancy            | 26        | 0.28%   |
| Limoges          | 26        | 0.28%   |
| Dijon            | 26        | 0.28%   |
| Besançon        | 26        | 0.28%   |
| Amiens           | 25        | 0.27%   |
| Orléans         | 24        | 0.26%   |
| Perpignan        | 23        | 0.25%   |
| Saint-Denis      | 22        | 0.24%   |
| Aubervilliers    | 22        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1999      | 3024   | 15.68%  |
| Samsung Electronics         | 1975      | 3012   | 15.49%  |
| WDC                         | 1840      | 2808   | 14.43%  |
| Crucial                     | 877       | 1215   | 6.88%   |
| Toshiba                     | 832       | 1085   | 6.53%   |
| SanDisk                     | 622       | 788    | 4.88%   |
| Kingston                    | 614       | 754    | 4.82%   |
| Unknown                     | 478       | 637    | 3.75%   |
| Hitachi                     | 395       | 499    | 3.1%    |
| SK hynix                    | 355       | 428    | 2.78%   |
| HGST                        | 335       | 439    | 2.63%   |
| Intel                       | 280       | 345    | 2.2%    |
| Micron Technology           | 222       | 265    | 1.74%   |
| PNY                         | 164       | 198    | 1.29%   |
| Maxtor                      | 105       | 135    | 0.82%   |
| KIOXIA                      | 101       | 116    | 0.79%   |
| LDLC                        | 98        | 144    | 0.77%   |
| China                       | 87        | 108    | 0.68%   |
| Phison                      | 85        | 103    | 0.67%   |
| Transcend                   | 74        | 85     | 0.58%   |
| Corsair                     | 73        | 86     | 0.57%   |
| Apple                       | 62        | 79     | 0.49%   |
| Micron/Crucial Technology   | 57        | 75     | 0.45%   |
| SPCC                        | 55        | 69     | 0.43%   |
| OCZ                         | 50        | 68     | 0.39%   |
| LITEON                      | 49        | 54     | 0.38%   |
| Fujitsu                     | 49        | 66     | 0.38%   |
| JMicron Technology          | 45        | 57     | 0.35%   |
| A-DATA Technology           | 40        | 48     | 0.31%   |
| LITEONIT                    | 32        | 34     | 0.25%   |
| Unknown                     | 30        | 35     | 0.24%   |
| Silicon Motion              | 28        | 39     | 0.22%   |
| Phison Electronics          | 25        | 31     | 0.2%    |
| Emtec                       | 25        | 30     | 0.2%    |
| Kingston Technology Company | 21        | 23     | 0.16%   |
| Gigabyte Technology         | 21        | 25     | 0.16%   |
| ASMT                        | 21        | 27     | 0.16%   |
| Intenso                     | 20        | 23     | 0.16%   |
| Netac                       | 16        | 18     | 0.13%   |
| Hewlett-Packard             | 16        | 48     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB       | 143       | 1.02%   |
| Samsung SSD 860 EVO 500GB          | 135       | 0.96%   |
| Crucial CT500MX500SSD1 500GB       | 127       | 0.91%   |
| HGST HTS721010A9E630 1TB           | 111       | 0.79%   |
| Seagate ST1000LM035-1RK172 970GB   | 107       | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 102       | 0.73%   |
| Kingston SA400S37240G 240GB SSD    | 102       | 0.73%   |
| Toshiba MQ01ABD100 1TB             | 95        | 0.68%   |
| Samsung SSD 850 EVO 250GB          | 94        | 0.67%   |
| Samsung SSD 850 EVO 500GB          | 90        | 0.64%   |
| Seagate ST500DM002-1BD142 500GB    | 88        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB     | 87        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB     | 85        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB        | 77        | 0.55%   |
| Unknown MMC Card  32GB             | 73        | 0.52%   |
| Samsung SSD 860 EVO 1TB            | 72        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB     | 67        | 0.48%   |
| Crucial CT480BX500SSD1 480GB       | 65        | 0.46%   |
| Samsung SSD 860 EVO 250GB          | 62        | 0.44%   |
| Toshiba MQ04ABF100 1TB             | 61        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB     | 61        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB     | 61        | 0.43%   |
| Unknown MMC Card  64GB             | 59        | 0.42%   |
| Kingston SA400S37120G 120GB SSD    | 59        | 0.42%   |
| Samsung SSD 870 QVO 1TB            | 57        | 0.41%   |
| Unknown SD/MMC/MS PRO 249GB        | 56        | 0.4%    |
| Toshiba DT01ACA100 1TB             | 56        | 0.4%    |
| HGST HTS541010A9E680 1TB           | 56        | 0.4%    |
| Samsung NVMe SSD Drive 512GB       | 55        | 0.39%   |
| Kingston SA400S37480G 480GB SSD    | 54        | 0.38%   |
| PNY CS900 120GB SSD                | 52        | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB     | 51        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD   | 50        | 0.36%   |
| Samsung SSD 860 QVO 1TB            | 49        | 0.35%   |
| PNY CS900 240GB SSD                | 49        | 0.35%   |
| Crucial CT120BX500SSD1 120GB       | 48        | 0.34%   |
| Samsung NVMe SSD Drive 500GB       | 47        | 0.33%   |
| Seagate ST500LT012-1DG142 500GB    | 44        | 0.31%   |
| SanDisk NVMe SSD Drive 512GB       | 44        | 0.31%   |
| Seagate ST9500325AS 500GB          | 42        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1969      | 2954   | 36.22%  |
| WDC                 | 1521      | 2374   | 27.98%  |
| Toshiba             | 637       | 814    | 11.72%  |
| Hitachi             | 395       | 499    | 7.27%   |
| HGST                | 334       | 437    | 6.14%   |
| Samsung Electronics | 250       | 370    | 4.6%    |
| Maxtor              | 105       | 135    | 1.93%   |
| Unknown             | 63        | 72     | 1.16%   |
| Fujitsu             | 48        | 65     | 0.88%   |
| JMicron Technology  | 21        | 31     | 0.39%   |
| Apple               | 18        | 20     | 0.33%   |
| ASMT                | 9         | 13     | 0.17%   |
| Hewlett-Packard     | 8         | 14     | 0.15%   |
| ASMedia             | 8         | 10     | 0.15%   |
| Magnetic Data       | 6         | 6      | 0.11%   |
| Inateck             | 6         | 6      | 0.11%   |
| IBM/Hitachi         | 5         | 6      | 0.09%   |
| USB3.0              | 4         | 4      | 0.07%   |
| LaCie               | 3         | 3      | 0.06%   |
| Intenso             | 3         | 4      | 0.06%   |
| HGST HTS            | 3         | 5      | 0.06%   |
| ASMT109x            | 3         | 4      | 0.06%   |
| RSH-319             | 2         | 3      | 0.04%   |
| PHD 3.0             | 2         | 2      | 0.04%   |
| H/W                 | 2         | 10     | 0.04%   |
| USB                 | 1         | 1      | 0.02%   |
| Storeva             | 1         | 1      | 0.02%   |
| SILICONMOTION       | 1         | 1      | 0.02%   |
| QEMU                | 1         | 1      | 0.02%   |
| MDT                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| ICY BOX             | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| APPLE HD            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1073      | 1525   | 25.08%  |
| Crucial             | 789       | 1088   | 18.44%  |
| Kingston            | 507       | 626    | 11.85%  |
| SanDisk             | 425       | 527    | 9.93%   |
| PNY                 | 149       | 179    | 3.48%   |
| WDC                 | 132       | 154    | 3.09%   |
| Intel               | 115       | 133    | 2.69%   |
| Micron Technology   | 95        | 124    | 2.22%   |
| SK hynix            | 89        | 109    | 2.08%   |
| China               | 86        | 107    | 2.01%   |
| LDLC                | 71        | 93     | 1.66%   |
| Transcend           | 70        | 81     | 1.64%   |
| Toshiba             | 54        | 69     | 1.26%   |
| SPCC                | 49        | 63     | 1.15%   |
| OCZ                 | 49        | 64     | 1.15%   |
| LITEON              | 41        | 44     | 0.96%   |
| Corsair             | 40        | 46     | 0.94%   |
| Apple               | 39        | 51     | 0.91%   |
| A-DATA Technology   | 33        | 41     | 0.77%   |
| LITEONIT            | 32        | 34     | 0.75%   |
| Emtec               | 22        | 25     | 0.51%   |
| KingSpec            | 15        | 18     | 0.35%   |
| Intenso             | 15        | 17     | 0.35%   |
| Patriot             | 14        | 19     | 0.33%   |
| Unknown             | 14        | 17     | 0.33%   |
| Netac               | 12        | 14     | 0.28%   |
| Plextor             | 11        | 15     | 0.26%   |
| Dogfish             | 11        | 18     | 0.26%   |
| ASMT                | 11        | 13     | 0.26%   |
| TEXTORM             | 10        | 11     | 0.23%   |
| JMicron Technology  | 10        | 11     | 0.23%   |
| BHT                 | 10        | 14     | 0.23%   |
| KingDian            | 9         | 14     | 0.21%   |
| Verbatim            | 8         | 8      | 0.19%   |
| Apacer              | 8         | 8      | 0.19%   |
| Seagate             | 7         | 7      | 0.16%   |
| BAITITON            | 7         | 7      | 0.16%   |
| Unknown             | 6         | 10     | 0.14%   |
| Teclast             | 6         | 8      | 0.14%   |
| TCSUNBOW            | 6         | 9      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4539      | 7872   | 39.98%  |
| SSD     | 3724      | 5569   | 32.8%   |
| NVMe    | 2490      | 3414   | 21.93%  |
| MMC     | 420       | 569    | 3.7%    |
| Unknown | 180       | 278    | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6633      | 13049  | 66.36%  |
| NVMe | 2480      | 3388   | 24.81%  |
| SAS  | 463       | 696    | 4.63%   |
| MMC  | 420       | 569    | 4.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4881      | 7718   | 56.16%  |
| 0.51-1.0   | 2611      | 3788   | 30.04%  |
| 1.01-2.0   | 708       | 1140   | 8.15%   |
| 3.01-4.0   | 239       | 371    | 2.75%   |
| 2.01-3.0   | 135       | 210    | 1.55%   |
| 4.01-10.0  | 95        | 163    | 1.09%   |
| 10.01-20.0 | 23        | 51     | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2283      | 24.98%  |
| 251-500        | 2056      | 22.49%  |
| 501-1000       | 1471      | 16.09%  |
| 1-20           | 744       | 8.14%   |
| 1001-2000      | 734       | 8.03%   |
| 51-100         | 505       | 5.53%   |
| More than 3000 | 422       | 4.62%   |
| 21-50          | 342       | 3.74%   |
| Unknown        | 305       | 3.34%   |
| 2001-3000      | 278       | 3.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3431      | 36.35%  |
| 21-50          | 1462      | 15.49%  |
| 101-250        | 1212      | 12.84%  |
| 51-100         | 1098      | 11.63%  |
| 251-500        | 772       | 8.18%   |
| 501-1000       | 592       | 6.27%   |
| 1001-2000      | 307       | 3.25%   |
| Unknown        | 305       | 3.23%   |
| More than 3000 | 139       | 1.47%   |
| 2001-3000      | 119       | 1.26%   |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB           | 21        | 25     | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 13        | 14     | 1.19%   |
| HGST HTS541010A9E680 1TB           | 13        | 14     | 1.19%   |
| Seagate ST500LM021-1KJ152 500GB    | 12        | 14     | 1.09%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 13     | 1.09%   |
| Toshiba MQ01ABD100 1TB             | 11        | 13     | 1%      |
| Seagate ST9500325AS 500GB          | 11        | 12     | 1%      |
| Seagate ST500LT012-1DG142 500GB    | 9         | 9      | 0.82%   |
| WDC WD10JPVX-22JC3T0 1TB           | 8         | 8      | 0.73%   |
| Seagate ST2000DM001-1CH164 2TB     | 8         | 9      | 0.73%   |
| Seagate ST1000LM035-1RK172 970GB   | 8         | 8      | 0.73%   |
| WDC WD10EADS-22M2B0 1TB            | 7         | 7      | 0.64%   |
| Samsung Electronics HD103SJ 1TB    | 7         | 8      | 0.64%   |
| HGST HTS725050A7E630 500GB         | 7         | 9      | 0.64%   |
| Seagate ST31000528AS 1TB           | 6         | 6      | 0.55%   |
| Seagate ST31000524AS 1TB           | 6         | 6      | 0.55%   |
| LDLC SSD 120GB                     | 6         | 8      | 0.55%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 8      | 0.55%   |
| Crucial CT525MX300SSD1 528GB       | 6         | 6      | 0.55%   |
| WDC WD6400AAKS-22A7B2 640GB        | 5         | 7      | 0.46%   |
| Toshiba MQ01ABF050 500GB           | 5         | 5      | 0.46%   |
| Toshiba MQ01ABD050 500GB           | 5         | 5      | 0.46%   |
| Toshiba DT01ACA100 1TB             | 5         | 6      | 0.46%   |
| Seagate ST3250310AS 250GB          | 5         | 5      | 0.46%   |
| Seagate ST320LT007-9ZV142 320GB    | 5         | 6      | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB     | 5         | 6      | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 5      | 0.46%   |
| Hitachi HTS727575A9E364 752GB      | 5         | 5      | 0.46%   |
| Hitachi HTS547575A9E384 752GB      | 5         | 5      | 0.46%   |
| Hitachi HTS545050B9A300 500GB      | 5         | 5      | 0.46%   |
| Hitachi HTS545050A7E380 500GB      | 5         | 5      | 0.46%   |
| HGST HTS545050A7E680 500GB         | 5         | 5      | 0.46%   |
| HGST HTS545050A7E380 500GB         | 5         | 5      | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 5      | 0.36%   |
| WDC WD3200AAKS-00L9A0 320GB        | 4         | 4      | 0.36%   |
| WDC WD10EADS-65L5B1 1TB            | 4         | 4      | 0.36%   |
| WDC WD10EADS-00M2B0 1TB            | 4         | 6      | 0.36%   |
| Toshiba MK7575GSX 752GB            | 4         | 4      | 0.36%   |
| Toshiba MK5055GSX 500GB            | 4         | 4      | 0.36%   |
| Toshiba MK3265GSX 320GB            | 4         | 5      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 260       | 302    | 24.21%  |
| WDC                 | 232       | 281    | 21.6%   |
| Hitachi             | 93        | 103    | 8.66%   |
| Toshiba             | 85        | 96     | 7.91%   |
| Samsung Electronics | 80        | 91     | 7.45%   |
| HGST                | 61        | 68     | 5.68%   |
| Crucial             | 40        | 43     | 3.72%   |
| Maxtor              | 34        | 38     | 3.17%   |
| Kingston            | 30        | 34     | 2.79%   |
| Intel               | 30        | 33     | 2.79%   |
| SK hynix            | 24        | 30     | 2.23%   |
| SanDisk             | 21        | 24     | 1.96%   |
| LDLC                | 9         | 11     | 0.84%   |
| Fujitsu             | 9         | 9      | 0.84%   |
| OCZ                 | 8         | 9      | 0.74%   |
| Micron Technology   | 8         | 10     | 0.74%   |
| LITEONIT            | 4         | 4      | 0.37%   |
| Corsair             | 4         | 5      | 0.37%   |
| China               | 4         | 4      | 0.37%   |
| A-DATA Technology   | 4         | 4      | 0.37%   |
| SPCC                | 3         | 3      | 0.28%   |
| Netac               | 3         | 3      | 0.28%   |
| Apacer              | 3         | 3      | 0.28%   |
| LITEON              | 2         | 2      | 0.19%   |
| KingSpec            | 2         | 2      | 0.19%   |
| JMicron Technology  | 2         | 2      | 0.19%   |
| Intenso             | 2         | 2      | 0.19%   |
| Hewlett-Packard     | 2         | 2      | 0.19%   |
| Dogfish             | 2         | 2      | 0.19%   |
| Apple               | 2         | 2      | 0.19%   |
| Unknown             | 1         | 1      | 0.09%   |
| TEXTORM             | 1         | 1      | 0.09%   |
| TakeMS              | 1         | 1      | 0.09%   |
| Phison              | 1         | 1      | 0.09%   |
| OCZ-VERTEX          | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| INNOVATION IT       | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |
| ASENNO              | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 260       | 302    | 31.59%  |
| WDC                 | 228       | 277    | 27.7%   |
| Hitachi             | 93        | 103    | 11.3%   |
| Toshiba             | 80        | 91     | 9.72%   |
| HGST                | 61        | 68     | 7.41%   |
| Samsung Electronics | 51        | 57     | 6.2%    |
| Maxtor              | 34        | 38     | 4.13%   |
| Fujitsu             | 9         | 9      | 1.09%   |
| Hewlett-Packard     | 2         | 2      | 0.24%   |
| Unknown             | 1         | 1      | 0.12%   |
| Magnetic Data       | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 763       | 952    | 75.47%  |
| SSD     | 224       | 254    | 22.16%  |
| NVMe    | 22        | 25     | 2.18%   |
| Unknown | 2         | 2      | 0.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                     | 2         | 3      | 6.45%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 6.45%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 6.45%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 3.23%   |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 3.23%   |
| WDC WD3200AAJS-22VWA0 320GB                      | 1         | 1      | 3.23%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 2      | 3.23%   |
| WDC WD20EARS-00J99B0 2TB                         | 1         | 2      | 3.23%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 3.23%   |
| WDC WD10EALX-759BA1 1TB                          | 1         | 1      | 3.23%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 3.23%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 3.23%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 3.23%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 2      | 3.23%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 3.23%   |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 3.23%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 3.23%   |
| Seagate ST3300657SS 304GB                        | 1         | 2      | 3.23%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 3.23%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 3.23%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 3.23%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 3.23%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 3.23%   |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 3.23%   |
| Kingston SMS200S360G 64GB SSD                    | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 3.23%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 3.23%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 14     | 35.48%  |
| Samsung Electronics | 6         | 10     | 19.35%  |
| Toshiba             | 5         | 6      | 16.13%  |
| Seagate             | 5         | 6      | 16.13%  |
| HGST                | 2         | 2      | 6.45%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4348      | 7613   | 45.39%  |
| Detected | 4219      | 8815   | 44.04%  |
| Malfunc  | 980       | 1233   | 10.23%  |
| Failed   | 31        | 40     | 0.32%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5945      | 55.1%   |
| AMD                              | 1519      | 14.08%  |
| Samsung Electronics              | 838       | 7.77%   |
| SanDisk                          | 397       | 3.68%   |
| SK hynix                         | 259       | 2.4%    |
| Nvidia                           | 199       | 1.84%   |
| Toshiba America Info Systems     | 166       | 1.54%   |
| Marvell Technology Group         | 162       | 1.5%    |
| Phison Electronics               | 161       | 1.49%   |
| Micron/Crucial Technology        | 148       | 1.37%   |
| ASMedia Technology               | 145       | 1.34%   |
| JMicron Technology               | 138       | 1.28%   |
| Micron Technology                | 135       | 1.25%   |
| Kingston Technology Company      | 133       | 1.23%   |
| KIOXIA                           | 94        | 0.87%   |
| VIA Technologies                 | 54        | 0.5%    |
| Silicon Motion                   | 40        | 0.37%   |
| Broadcom / LSI                   | 27        | 0.25%   |
| LSI Logic / Symbios Logic        | 25        | 0.23%   |
| Silicon Image                    | 22        | 0.2%    |
| Lite-On Technology               | 21        | 0.19%   |
| Union Memory (Shenzhen)          | 20        | 0.19%   |
| Silicon Integrated Systems [SiS] | 20        | 0.19%   |
| Solid State Storage Technology   | 14        | 0.13%   |
| Seagate Technology               | 12        | 0.11%   |
| ADATA Technology                 | 12        | 0.11%   |
| Adaptec                          | 11        | 0.1%    |
| Yangtze Memory Technologies      | 10        | 0.09%   |
| Realtek Semiconductor            | 9         | 0.08%   |
| Hewlett-Packard                  | 8         | 0.07%   |
| Lenovo                           | 6         | 0.06%   |
| Integrated Technology Express    | 6         | 0.06%   |
| Shenzhen Longsys Electronics     | 5         | 0.05%   |
| Apple                            | 5         | 0.05%   |
| Promise Technology               | 3         | 0.03%   |
| O2 Micro                         | 3         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |
| Tekram Technology                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1006      | 8.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 463       | 3.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 398       | 3.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 377       | 3.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 356       | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 283       | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 237       | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 236       | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 216       | 1.73%   |
| AMD 400 Series Chipset SATA Controller                                         | 215       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 207       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 202       | 1.62%   |
| Samsung NVMe SSD Controller 980                                                | 198       | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 197       | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 196       | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 183       | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 177       | 1.42%   |
| Intel SATA Controller [RAID mode]                                              | 174       | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 155       | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 150       | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 149       | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 139       | 1.12%   |
| Micron NVMe Storage Controller                                                 | 135       | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 135       | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 129       | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 128       | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 128       | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 120       | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 110       | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 109       | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 107       | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 107       | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 104       | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 103       | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 103       | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 97        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 97        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 94        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 93        | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 88        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6218      | 57.07%  |
| NVMe | 2506      | 23%     |
| IDE  | 1291      | 11.85%  |
| RAID | 825       | 7.57%   |
| SAS  | 35        | 0.32%   |
| SCSI | 21        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6697      | 77.26%  |
| AMD                   | 1901      | 21.93%  |
| ARM                   | 61        | 0.7%    |
| QUALCOMM              | 4         | 0.05%   |
| CentaurHauls          | 3         | 0.03%   |
| Marvell Semiconductor | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 119       | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 80        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 73        | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 72        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 70        | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 69        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 62        | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 62        | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 60        | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 59        | 0.68%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 55        | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 53        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 50        | 0.58%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 50        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 49        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 49        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 49        | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 48        | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 48        | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 48        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 47        | 0.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 47        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 46        | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 45        | 0.52%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 43        | 0.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 41        | 0.47%   |
| ARM Processor                                 | 41        | 0.47%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 39        | 0.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 37        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 36        | 0.41%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 36        | 0.41%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 35        | 0.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 34        | 0.39%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 34        | 0.39%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 34        | 0.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 33        | 0.38%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 33        | 0.38%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 33        | 0.38%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 32        | 0.37%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 32        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1929      | 22.22%  |
| Intel Core i7           | 1583      | 18.23%  |
| Intel Core i3           | 693       | 7.98%   |
| Other                   | 595       | 6.85%   |
| AMD Ryzen 5             | 436       | 5.02%   |
| Intel Core 2 Duo        | 389       | 4.48%   |
| Intel Celeron           | 387       | 4.46%   |
| AMD Ryzen 7             | 335       | 3.86%   |
| Intel Pentium           | 248       | 2.86%   |
| Intel Xeon              | 229       | 2.64%   |
| Intel Atom              | 170       | 1.96%   |
| Intel Pentium Dual-Core | 118       | 1.36%   |
| AMD Ryzen 9             | 95        | 1.09%   |
| AMD FX                  | 95        | 1.09%   |
| Intel Core 2 Quad       | 91        | 1.05%   |
| AMD Ryzen 3             | 76        | 0.88%   |
| Intel Pentium Dual      | 67        | 0.77%   |
| AMD A4                  | 67        | 0.77%   |
| Intel Core 2            | 62        | 0.71%   |
| AMD Athlon II X2        | 62        | 0.71%   |
| AMD E1                  | 60        | 0.69%   |
| AMD Athlon 64 X2        | 55        | 0.63%   |
| Intel Core i9           | 54        | 0.62%   |
| AMD A8                  | 52        | 0.6%    |
| AMD A6                  | 51        | 0.59%   |
| AMD E2                  | 46        | 0.53%   |
| AMD Ryzen 7 PRO         | 40        | 0.46%   |
| AMD Phenom II X4        | 40        | 0.46%   |
| AMD E                   | 40        | 0.46%   |
| Intel Pentium 4         | 33        | 0.38%   |
| Intel Genuine           | 28        | 0.32%   |
| AMD Athlon              | 28        | 0.32%   |
| Intel Pentium Silver    | 22        | 0.25%   |
| Intel Pentium D         | 21        | 0.24%   |
| AMD Ryzen 5 PRO         | 21        | 0.24%   |
| AMD A10                 | 20        | 0.23%   |
| AMD Athlon 64           | 19        | 0.22%   |
| AMD Sempron             | 17        | 0.2%    |
| AMD Ryzen Threadripper  | 17        | 0.2%    |
| Intel Pentium Gold      | 16        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3431      | 39.47%  |
| 4       | 3264      | 37.55%  |
| 6       | 835       | 9.61%   |
| 8       | 568       | 6.53%   |
| 1       | 240       | 2.76%   |
| 12      | 123       | 1.42%   |
| 3       | 48        | 0.55%   |
| 10      | 38        | 0.44%   |
| Unknown | 36        | 0.41%   |
| 14      | 35        | 0.4%    |
| 16      | 33        | 0.38%   |
| 20      | 12        | 0.14%   |
| 32      | 9         | 0.1%    |
| 24      | 9         | 0.1%    |
| 64      | 4         | 0.05%   |
| 40      | 2         | 0.02%   |
| 104     | 1         | 0.01%   |
| 48      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8578      | 98.9%   |
| 2       | 86        | 0.99%   |
| Unknown | 6         | 0.07%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5446      | 62.63%  |
| 1       | 3211      | 36.93%  |
| Unknown | 36        | 0.41%   |
| 4       | 3         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8495      | 97.81%  |
| Unknown        | 116       | 1.34%   |
| 32-bit         | 69        | 0.79%   |
| 64-bit         | 5         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1769      | 19.73%  |
| 0x306a9    | 506       | 5.64%   |
| 0x206a7    | 502       | 5.6%    |
| 0x306c3    | 501       | 5.59%   |
| 0x1067a    | 358       | 3.99%   |
| 0x906ea    | 276       | 3.08%   |
| 0x806c1    | 232       | 2.59%   |
| 0x506e3    | 230       | 2.57%   |
| 0x806ec    | 205       | 2.29%   |
| 0x806ea    | 175       | 1.95%   |
| 0x40651    | 168       | 1.87%   |
| 0x306d4    | 166       | 1.85%   |
| 0x906e9    | 162       | 1.81%   |
| 0x406e3    | 158       | 1.76%   |
| 0x806e9    | 145       | 1.62%   |
| 0x20655    | 136       | 1.52%   |
| 0x6fd      | 131       | 1.46%   |
| 0x010000c8 | 102       | 1.14%   |
| 0x08108109 | 101       | 1.13%   |
| 0x08701021 | 95        | 1.06%   |
| 0x10676    | 91        | 1.01%   |
| 0x08600106 | 87        | 0.97%   |
| 0xa0652    | 82        | 0.91%   |
| 0x30678    | 80        | 0.89%   |
| 0x0800820d | 77        | 0.86%   |
| 0x406c4    | 75        | 0.84%   |
| 0x906ed    | 70        | 0.78%   |
| 0x106e5    | 65        | 0.72%   |
| 0x0a50000c | 62        | 0.69%   |
| 0x06001119 | 59        | 0.66%   |
| 0x706e5    | 57        | 0.64%   |
| 0x06000852 | 56        | 0.62%   |
| 0x506c9    | 55        | 0.61%   |
| 0x08701013 | 53        | 0.59%   |
| 0x07030105 | 53        | 0.59%   |
| 0x906a3    | 52        | 0.58%   |
| 0x806eb    | 52        | 0.58%   |
| 0x05000119 | 51        | 0.57%   |
| 0x806d1    | 50        | 0.56%   |
| 0x6fb      | 50        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1373      | 15.82%  |
| Haswell          | 851       | 9.81%   |
| SandyBridge      | 603       | 6.95%   |
| IvyBridge        | 602       | 6.94%   |
| Penryn           | 519       | 5.98%   |
| Skylake          | 514       | 5.92%   |
| Zen 2            | 371       | 4.28%   |
| Core             | 295       | 3.4%    |
| TigerLake        | 278       | 3.2%    |
| Zen+             | 265       | 3.05%   |
| Silvermont       | 256       | 2.95%   |
| Westmere         | 238       | 2.74%   |
| Unknown          | 236       | 2.72%   |
| Broadwell        | 226       | 2.6%    |
| Zen 3            | 197       | 2.27%   |
| K10              | 197       | 2.27%   |
| CometLake        | 196       | 2.26%   |
| Piledriver       | 153       | 1.76%   |
| Zen              | 145       | 1.67%   |
| Icelake          | 138       | 1.59%   |
| K8 Hammer        | 116       | 1.34%   |
| Nehalem          | 112       | 1.29%   |
| Goldmont plus    | 107       | 1.23%   |
| Alderlake Hybrid | 90        | 1.04%   |
| Bobcat           | 87        | 1%      |
| Excavator        | 79        | 0.91%   |
| Puma             | 78        | 0.9%    |
| Bonnell          | 72        | 0.83%   |
| Goldmont         | 70        | 0.81%   |
| NetBurst         | 59        | 0.68%   |
| Jaguar           | 46        | 0.53%   |
| P6               | 25        | 0.29%   |
| K10 Llano        | 25        | 0.29%   |
| Steamroller      | 17        | 0.2%    |
| K8 & K10 hybrid  | 13        | 0.15%   |
| Bulldozer        | 12        | 0.14%   |
| Tremont          | 10        | 0.12%   |
| K6               | 5         | 0.06%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4887      | 47.44%  |
| Nvidia                                       | 3175      | 30.82%  |
| AMD                                          | 2134      | 20.72%  |
| Matrox Electronics Systems                   | 50        | 0.49%   |
| ASPEED Technology                            | 28        | 0.27%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.12%   |
| VIA Technologies                             | 9         | 0.09%   |
| ATI Technologies                             | 3         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 405       | 3.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 326       | 3.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 260       | 2.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 229       | 2.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 202       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 194       | 1.83%   |
| Intel UHD Graphics 620                                                                   | 181       | 1.71%   |
| Intel HD Graphics 530                                                                    | 174       | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 172       | 1.62%   |
| Intel HD Graphics 5500                                                                   | 170       | 1.61%   |
| AMD Renoir                                                                               | 170       | 1.61%   |
| Intel HD Graphics 620                                                                    | 164       | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 162       | 1.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 162       | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 156       | 1.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 156       | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 149       | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 140       | 1.32%   |
| Intel HD Graphics 630                                                                    | 123       | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 122       | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 112       | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 103       | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 101       | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 94        | 0.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 94        | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 89        | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 88        | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 86        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 82        | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 70        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 68        | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 68        | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 67        | 0.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 64        | 0.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 63        | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 62        | 0.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 59        | 0.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 57        | 0.54%   |
| Intel HD Graphics 500                                                                    | 55        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 53        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 3341      | 38.23%  |
| 1 x Nvidia           | 1811      | 20.72%  |
| 1 x AMD              | 1674      | 19.16%  |
| Intel + Nvidia       | 1225      | 14.02%  |
| Intel + AMD          | 213       | 2.44%   |
| 2 x AMD              | 126       | 1.44%   |
| AMD + Nvidia         | 121       | 1.38%   |
| Other                | 74        | 0.85%   |
| 1 x Matrox           | 45        | 0.51%   |
| 2 x Nvidia           | 26        | 0.3%    |
| 1 x ASPEED           | 23        | 0.26%   |
| 2 x Intel            | 20        | 0.23%   |
| 1 x SiS              | 12        | 0.14%   |
| 1 x VIA              | 9         | 0.1%    |
| Nvidia + Matrox      | 4         | 0.05%   |
| 3 x AMD              | 2         | 0.02%   |
| Nvidia + ASPEED      | 2         | 0.02%   |
| Intel + 2 x Nvidia   | 2         | 0.02%   |
| AMD + ASPEED         | 2         | 0.02%   |
| 3 x Nvidia           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.01%   |
| 2 x AMD + 1 x ASPEED | 1         | 0.01%   |
| 1 x XGI              | 1         | 0.01%   |
| 1 x S3 Graphics      | 1         | 0.01%   |
| 1 x Red Hat          | 1         | 0.01%   |
| Intel + 2 x AMD      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6924      | 78.68%  |
| Proprietary | 1487      | 16.9%   |
| Unknown     | 389       | 4.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4660      | 52.35%  |
| 0.01-0.5   | 1172      | 13.17%  |
| 1.01-2.0   | 1110      | 12.47%  |
| 0.51-1.0   | 761       | 8.55%   |
| 3.01-4.0   | 557       | 6.26%   |
| 7.01-8.0   | 274       | 3.08%   |
| 5.01-6.0   | 200       | 2.25%   |
| 8.01-16.0  | 81        | 0.91%   |
| 2.01-3.0   | 71        | 0.8%    |
| 16.01-24.0 | 11        | 0.12%   |
| 4.01-5.0   | 5         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1187      | 12.51%  |
| AU Optronics            | 1137      | 11.99%  |
| LG Display              | 759       | 8%      |
| Chimei Innolux          | 757       | 7.98%   |
| BOE                     | 672       | 7.08%   |
| Iiyama                  | 493       | 5.2%    |
| Dell                    | 487       | 5.13%   |
| Hewlett-Packard         | 374       | 3.94%   |
| Acer                    | 330       | 3.48%   |
| Goldstar                | 315       | 3.32%   |
| Ancor Communications    | 262       | 2.76%   |
| Philips                 | 250       | 2.64%   |
| AOC                     | 214       | 2.26%   |
| Sharp                   | 199       | 2.1%    |
| BenQ                    | 190       | 2%      |
| Lenovo                  | 158       | 1.67%   |
| Chi Mei Optoelectronics | 148       | 1.56%   |
| Apple                   | 139       | 1.47%   |
| ViewSonic               | 117       | 1.23%   |
| ASUSTek Computer        | 75        | 0.79%   |
| PANDA                   | 73        | 0.77%   |
| InfoVision              | 71        | 0.75%   |
| LG Philips              | 69        | 0.73%   |
| Sony                    | 55        | 0.58%   |
| Unknown                 | 49        | 0.52%   |
| HannStar                | 49        | 0.52%   |
| Idek Iiyama             | 36        | 0.38%   |
| Packard Bell            | 34        | 0.36%   |
| LG Electronics          | 33        | 0.35%   |
| Fujitsu Siemens         | 32        | 0.34%   |
| Vestel Elektronik       | 28        | 0.3%    |
| Toshiba                 | 26        | 0.27%   |
| NEC Computers           | 24        | 0.25%   |
| Eizo                    | 24        | 0.25%   |
| Medion                  | 22        | 0.23%   |
| Hitachi                 | 22        | 0.23%   |
| CSO                     | 21        | 0.22%   |
| SNC                     | 20        | 0.21%   |
| Panasonic               | 20        | 0.21%   |
| MSI                     | 20        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 46        | 0.47%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                     | 44        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 42        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 33        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 33        | 0.34%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 28        | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 28        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 27        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 27        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 26        | 0.27%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 26        | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 25        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 25        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 24        | 0.24%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 24        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 23        | 0.23%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 23        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 21        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 21        | 0.21%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 21        | 0.21%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                         | 20        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch          | 19        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 19        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 18        | 0.18%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 18        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 18        | 0.18%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 17        | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 17        | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 17        | 0.17%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.17%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                    | 16        | 0.16%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 16        | 0.16%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 16        | 0.16%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 16        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 16        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.16%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 16        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4089      | 45.47%  |
| 1366x768 (WXGA)    | 1308      | 14.54%  |
| 1600x900 (HD+)     | 570       | 6.34%   |
| 3840x2160 (4K)     | 412       | 4.58%   |
| 2560x1440 (QHD)    | 385       | 4.28%   |
| 1680x1050 (WSXGA+) | 358       | 3.98%   |
| 1280x1024 (SXGA)   | 337       | 3.75%   |
| 1440x900 (WXGA+)   | 277       | 3.08%   |
| 1920x1200 (WUXGA)  | 273       | 3.04%   |
| 1280x800 (WXGA)    | 196       | 2.18%   |
| Unknown            | 119       | 1.32%   |
| 3440x1440          | 65        | 0.72%   |
| 1360x768           | 56        | 0.62%   |
| 3840x1080          | 54        | 0.6%    |
| 2560x1080          | 51        | 0.57%   |
| 2560x1600          | 40        | 0.44%   |
| 1024x600           | 32        | 0.36%   |
| 2880x1800          | 31        | 0.34%   |
| 1600x1200          | 31        | 0.34%   |
| 2160x1440          | 27        | 0.3%    |
| 3840x2400          | 26        | 0.29%   |
| 1024x768 (XGA)     | 26        | 0.29%   |
| 800x1280           | 20        | 0.22%   |
| 1920x540           | 19        | 0.21%   |
| 3200x1800 (QHD+)   | 12        | 0.13%   |
| 2288x1287          | 12        | 0.13%   |
| 3840x1600          | 9         | 0.1%    |
| 4480x1440          | 8         | 0.09%   |
| 3000x2000          | 8         | 0.09%   |
| 2736x1824          | 8         | 0.09%   |
| 3200x1080          | 7         | 0.08%   |
| 3600x1080          | 6         | 0.07%   |
| 1680x945           | 6         | 0.07%   |
| 5760x2160          | 5         | 0.06%   |
| 5760x1080          | 5         | 0.06%   |
| 3840x1200          | 5         | 0.06%   |
| 2048x1152          | 5         | 0.06%   |
| 1280x720 (HD)      | 5         | 0.06%   |
| 1920x515           | 4         | 0.04%   |
| 1400x1050          | 4         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2084      | 22.06%  |
| 17      | 921       | 9.75%   |
| 13      | 819       | 8.67%   |
| 24      | 764       | 8.09%   |
| 23      | 760       | 8.04%   |
| 27      | 677       | 7.17%   |
| 14      | 566       | 5.99%   |
| 21      | 554       | 5.86%   |
| Unknown | 461       | 4.88%   |
| 19      | 324       | 3.43%   |
| 22      | 228       | 2.41%   |
| 12      | 168       | 1.78%   |
| 20      | 148       | 1.57%   |
| 18      | 140       | 1.48%   |
| 31      | 109       | 1.15%   |
| 34      | 93        | 0.98%   |
| 11      | 75        | 0.79%   |
| 16      | 69        | 0.73%   |
| 84      | 62        | 0.66%   |
| 10      | 48        | 0.51%   |
| 72      | 46        | 0.49%   |
| 32      | 42        | 0.44%   |
| 25      | 41        | 0.43%   |
| 40      | 38        | 0.4%    |
| 54      | 24        | 0.25%   |
| 26      | 23        | 0.24%   |
| 33      | 22        | 0.23%   |
| 46      | 12        | 0.13%   |
| 65      | 11        | 0.12%   |
| 48      | 10        | 0.11%   |
| 52      | 9         | 0.1%    |
| 29      | 9         | 0.1%    |
| 7       | 9         | 0.1%    |
| 142     | 8         | 0.08%   |
| 49      | 8         | 0.08%   |
| 36      | 7         | 0.07%   |
| 35      | 7         | 0.07%   |
| 42      | 6         | 0.06%   |
| 39      | 6         | 0.06%   |
| 38      | 6         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3138      | 33.89%  |
| 501-600        | 2027      | 21.89%  |
| 401-500        | 1198      | 12.94%  |
| 351-400        | 1043      | 11.26%  |
| 201-300        | 747       | 8.07%   |
| Unknown        | 461       | 4.98%   |
| 601-700        | 194       | 2.1%    |
| 701-800        | 164       | 1.77%   |
| 1501-2000      | 110       | 1.19%   |
| 1001-1500      | 86        | 0.93%   |
| 801-900        | 64        | 0.69%   |
| 1-100          | 9         | 0.1%    |
| More than 2000 | 8         | 0.09%   |
| 901-1000       | 8         | 0.09%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6289      | 73.94%  |
| 16/10   | 1159      | 13.63%  |
| Unknown | 374       | 4.4%    |
| 5/4     | 316       | 3.72%   |
| 21/9    | 114       | 1.34%   |
| 3/2     | 91        | 1.07%   |
| 4/3     | 83        | 0.98%   |
| 6/5     | 18        | 0.21%   |
| 32/9    | 17        | 0.2%    |
| 0.62    | 13        | 0.15%   |
| 0.67    | 9         | 0.11%   |
| 1.00    | 8         | 0.09%   |
| 3.20    | 4         | 0.05%   |
| 3.73    | 3         | 0.04%   |
| 11/10   | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2096      | 22.45%  |
| 201-250        | 1851      | 19.82%  |
| 81-90          | 996       | 10.67%  |
| 301-350        | 700       | 7.5%    |
| 151-200        | 653       | 6.99%   |
| 121-130        | 645       | 6.91%   |
| Unknown        | 461       | 4.94%   |
| 71-80          | 402       | 4.3%    |
| 351-500        | 276       | 2.96%   |
| 251-300        | 272       | 2.91%   |
| 141-150        | 245       | 2.62%   |
| More than 1000 | 174       | 1.86%   |
| 61-70          | 145       | 1.55%   |
| 131-140        | 121       | 1.3%    |
| 501-1000       | 103       | 1.1%    |
| 51-60          | 75        | 0.8%    |
| 41-50          | 49        | 0.52%   |
| 111-120        | 47        | 0.5%    |
| 91-100         | 16        | 0.17%   |
| 1-40           | 11        | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3274      | 36.01%  |
| 101-120       | 2302      | 25.32%  |
| 121-160       | 2272      | 24.99%  |
| 161-240       | 480       | 5.28%   |
| Unknown       | 461       | 5.07%   |
| More than 240 | 168       | 1.85%   |
| 1-50          | 134       | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6879      | 77.61%  |
| 2     | 1389      | 15.67%  |
| 0     | 432       | 4.87%   |
| 3     | 155       | 1.75%   |
| 4     | 7         | 0.08%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4635      | 35.94%  |
| Intel                             | 4146      | 32.14%  |
| Qualcomm Atheros                  | 1529      | 11.85%  |
| Broadcom                          | 726       | 5.63%   |
| Marvell Technology Group          | 185       | 1.43%   |
| Broadcom Limited                  | 151       | 1.17%   |
| Nvidia                            | 147       | 1.14%   |
| Ralink                            | 143       | 1.11%   |
| MediaTek                          | 127       | 0.98%   |
| TP-Link                           | 102       | 0.79%   |
| NetGear                           | 78        | 0.6%    |
| Ralink Technology                 | 75        | 0.58%   |
| ASIX Electronics                  | 69        | 0.53%   |
| Samsung Electronics               | 62        | 0.48%   |
| Dell                              | 45        | 0.35%   |
| D-Link System                     | 40        | 0.31%   |
| Xiaomi                            | 35        | 0.27%   |
| D-Link                            | 31        | 0.24%   |
| DisplayLink                       | 30        | 0.23%   |
| Sierra Wireless                   | 27        | 0.21%   |
| Huawei Technologies               | 26        | 0.2%    |
| Ericsson Business Mobile Networks | 26        | 0.2%    |
| VIA Technologies                  | 25        | 0.19%   |
| Qualcomm                          | 25        | 0.19%   |
| Aquantia                          | 25        | 0.19%   |
| Microsoft                         | 23        | 0.18%   |
| JMicron Technology                | 22        | 0.17%   |
| Belkin Components                 | 22        | 0.17%   |
| Lenovo                            | 21        | 0.16%   |
| Qualcomm Atheros Communications   | 19        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.11%   |
| Google                            | 14        | 0.11%   |
| Attansic Technology               | 14        | 0.11%   |
| ASUSTek Computer                  | 13        | 0.1%    |
| OPPO Electronics                  | 12        | 0.09%   |
| Hewlett-Packard                   | 12        | 0.09%   |
| Guillemot                         | 11        | 0.09%   |
| Microchip Technology              | 10        | 0.08%   |
| Edimax Technology                 | 10        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3183      | 21.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 461       | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 365       | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 315       | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 282       | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 231       | 1.53%   |
| Intel Wi-Fi 6 AX201                                               | 216       | 1.43%   |
| Intel Wireless 7265                                               | 214       | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 210       | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 184       | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 183       | 1.21%   |
| Intel Wireless 8260                                               | 176       | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 173       | 1.14%   |
| Intel Wireless 7260                                               | 167       | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 158       | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 153       | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 150       | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 136       | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 136       | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 131       | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 130       | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 130       | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 126       | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 120       | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 116       | 0.77%   |
| Intel Wireless 3165                                               | 113       | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 111       | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 100       | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 91        | 0.6%    |
| Intel Wireless-AC 9260                                            | 90        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 89        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 87        | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 85        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 82        | 0.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 80        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 79        | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 77        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 75        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 72        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 69        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3066      | 45.93%  |
| Qualcomm Atheros                      | 1168      | 17.5%   |
| Realtek Semiconductor                 | 1132      | 16.96%  |
| Broadcom                              | 439       | 6.58%   |
| Ralink                                | 143       | 2.14%   |
| MediaTek                              | 114       | 1.71%   |
| TP-Link                               | 96        | 1.44%   |
| Broadcom Limited                      | 90        | 1.35%   |
| Ralink Technology                     | 75        | 1.12%   |
| NetGear                               | 74        | 1.11%   |
| D-Link                                | 30        | 0.45%   |
| Microsoft                             | 23        | 0.34%   |
| Sierra Wireless                       | 22        | 0.33%   |
| Dell                                  | 22        | 0.33%   |
| D-Link System                         | 22        | 0.33%   |
| Belkin Components                     | 22        | 0.33%   |
| Qualcomm Atheros Communications       | 19        | 0.28%   |
| Marvell Technology Group              | 18        | 0.27%   |
| Qualcomm                              | 14        | 0.21%   |
| ASUSTek Computer                      | 13        | 0.19%   |
| Guillemot                             | 11        | 0.16%   |
| Edimax Technology                     | 10        | 0.15%   |
| Fibocom                               | 7         | 0.1%    |
| Hewlett-Packard                       | 6         | 0.09%   |
| Sagem                                 | 5         | 0.07%   |
| IMC Networks                          | 5         | 0.07%   |
| TRENDnet                              | 4         | 0.06%   |
| Gemtek                                | 4         | 0.06%   |
| Accton Technology                     | 3         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.04%   |
| ZyDAS                                 | 2         | 0.03%   |
| Toshiba                               | 2         | 0.03%   |
| Tenda                                 | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| Fujitsu Siemens Computers             | 2         | 0.03%   |
| Z-Com                                 | 1         | 0.01%   |
| Wilocity                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| Micro Star International              | 1         | 0.01%   |
| BUFFALO                               | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 365       | 5.44%   |
| Intel Wireless 8265 / 8275                                              | 231       | 3.44%   |
| Intel Wi-Fi 6 AX201                                                     | 216       | 3.22%   |
| Intel Wireless 7265                                                     | 214       | 3.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 210       | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 184       | 2.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 183       | 2.73%   |
| Intel Wireless 8260                                                     | 176       | 2.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 173       | 2.58%   |
| Intel Wireless 7260                                                     | 167       | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 153       | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 150       | 2.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 136       | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 130       | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 126       | 1.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 120       | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 116       | 1.73%   |
| Intel Wireless 3165                                                     | 113       | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 111       | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 100       | 1.49%   |
| Intel Wireless-AC 9260                                                  | 90        | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 89        | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 85        | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 80        | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                           | 77        | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 65        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 0.91%   |
| Intel Wireless 3160                                                     | 59        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 59        | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 58        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 58        | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 57        | 0.85%   |
| Intel WiFi Link 5100                                                    | 56        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 56        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 55        | 0.82%   |
| Intel Centrino Wireless-N 2230                                          | 52        | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 51        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 51        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 50        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4210      | 52.19%  |
| Intel                            | 2112      | 26.18%  |
| Qualcomm Atheros                 | 533       | 6.61%   |
| Broadcom                         | 356       | 4.41%   |
| Marvell Technology Group         | 167       | 2.07%   |
| Nvidia                           | 147       | 1.82%   |
| ASIX Electronics                 | 69        | 0.86%   |
| Broadcom Limited                 | 64        | 0.79%   |
| Samsung Electronics              | 49        | 0.61%   |
| Xiaomi                           | 35        | 0.43%   |
| DisplayLink                      | 30        | 0.37%   |
| Aquantia                         | 25        | 0.31%   |
| VIA Technologies                 | 22        | 0.27%   |
| JMicron Technology               | 22        | 0.27%   |
| Lenovo                           | 21        | 0.26%   |
| Huawei Technologies              | 20        | 0.25%   |
| D-Link System                    | 18        | 0.22%   |
| Google                           | 14        | 0.17%   |
| Attansic Technology              | 14        | 0.17%   |
| Silicon Integrated Systems [SiS] | 13        | 0.16%   |
| OPPO Electronics                 | 12        | 0.15%   |
| MediaTek                         | 12        | 0.15%   |
| Qualcomm                         | 11        | 0.14%   |
| OnePlus Technology (Shenzhen)    | 7         | 0.09%   |
| Microchip Technology             | 7         | 0.09%   |
| ICS Advent                       | 7         | 0.09%   |
| TP-Link                          | 6         | 0.07%   |
| Apple                            | 6         | 0.07%   |
| Sierra Wireless                  | 5         | 0.06%   |
| QLogic                           | 4         | 0.05%   |
| NetGear                          | 4         | 0.05%   |
| Motorola PCS                     | 4         | 0.05%   |
| Mellanox Technologies            | 4         | 0.05%   |
| 3Com                             | 4         | 0.05%   |
| Linksys                          | 3         | 0.04%   |
| HTC (High Tech Computer)         | 3         | 0.04%   |
| Dell                             | 2         | 0.02%   |
| Cypress Semiconductor            | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3183      | 38.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 461       | 5.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 315       | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 282       | 3.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 158       | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 136       | 1.65%   |
| Intel Ethernet Connection I217-LM                                 | 131       | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 130       | 1.57%   |
| Intel 82579V Gigabit Network Connection                           | 91        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 87        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 82        | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 79        | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 75        | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 72        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 69        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 64        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 63        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 62        | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 61        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 61        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 58        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 53        | 0.64%   |
| Intel Ethernet Controller I225-V                                  | 53        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 52        | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 49        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 48        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 45        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 44        | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 44        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 41        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 41        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 39        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 39        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38        | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 0.46%   |
| Intel 82567LM Gigabit Network Connection                          | 38        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 36        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7570      | 53.62%  |
| WiFi     | 6392      | 45.28%  |
| Modem    | 140       | 0.99%   |
| Unknown  | 15        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4745      | 52.45%  |
| Ethernet | 4300      | 47.53%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4725      | 54.25%  |
| 1     | 3617      | 41.53%  |
| 3     | 162       | 1.86%   |
| 0     | 161       | 1.85%   |
| 4     | 32        | 0.37%   |
| 5     | 6         | 0.07%   |
| 8     | 4         | 0.05%   |
| 6     | 3         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5629      | 63%     |
| Yes  | 3306      | 37%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2471      | 49.86%  |
| Realtek Semiconductor           | 392       | 7.91%   |
| IMC Networks                    | 333       | 6.72%   |
| Cambridge Silicon Radio         | 318       | 6.42%   |
| Qualcomm Atheros Communications | 283       | 5.71%   |
| Broadcom                        | 236       | 4.76%   |
| Apple                           | 152       | 3.07%   |
| Lite-On Technology              | 145       | 2.93%   |
| Foxconn / Hon Hai               | 141       | 2.85%   |
| ASUSTek Computer                | 96        | 1.94%   |
| Dell                            | 82        | 1.65%   |
| Realtek                         | 47        | 0.95%   |
| Hewlett-Packard                 | 39        | 0.79%   |
| Toshiba                         | 38        | 0.77%   |
| Ralink                          | 33        | 0.67%   |
| Ralink Technology               | 20        | 0.4%    |
| MediaTek                        | 20        | 0.4%    |
| Belkin Components               | 17        | 0.34%   |
| TP-Link                         | 14        | 0.28%   |
| Marvell Semiconductor           | 14        | 0.28%   |
| Foxconn International           | 14        | 0.28%   |
| Alps Electric                   | 13        | 0.26%   |
| Chicony Electronics             | 7         | 0.14%   |
| Integrated System Solution      | 6         | 0.12%   |
| USI                             | 5         | 0.1%    |
| HTC (High Tech Computer)        | 3         | 0.06%   |
| Fujitsu                         | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| TRENDnet                        | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 916       | 18.48%  |
| Intel AX201 Bluetooth                               | 488       | 9.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 367       | 7.4%    |
| Intel AX200 Bluetooth                               | 340       | 6.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 318       | 6.41%   |
| Realtek Bluetooth Radio                             | 257       | 5.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 156       | 3.15%   |
| IMC Networks Bluetooth Device                       | 124       | 2.5%    |
| IMC Networks Bluetooth Radio                        | 107       | 2.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 92        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 81        | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 76        | 1.53%   |
| Intel Bluetooth Device                              | 69        | 1.39%   |
| Apple Bluetooth Host Controller                     | 63        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 59        | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                    | 57        | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 52        | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 51        | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 0.95%   |
| Intel AX210 Bluetooth                               | 45        | 0.91%   |
| Lite-On Bluetooth Device                            | 39        | 0.79%   |
| Apple Bluetooth USB Host Controller                 | 39        | 0.79%   |
| Realtek 802.11ac WLAN Adapter                       | 37        | 0.75%   |
| IMC Networks Wireless_Device                        | 36        | 0.73%   |
| Dell DW375 Bluetooth Module                         | 36        | 0.73%   |
| Ralink RT3290 Bluetooth                             | 33        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 33        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 33        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 29        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 27        | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 26        | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 25        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 25        | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 24        | 0.48%   |
| Apple Bluetooth HCI                                 | 23        | 0.46%   |
| Broadcom BCM43142A0 Bluetooth Device                | 22        | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.42%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 18        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6348      | 52.12%  |
| AMD                              | 2289      | 18.79%  |
| Nvidia                           | 2273      | 18.66%  |
| C-Media Electronics              | 174       | 1.43%   |
| Logitech                         | 113       | 0.93%   |
| Creative Labs                    | 78        | 0.64%   |
| Realtek Semiconductor            | 68        | 0.56%   |
| GN Netcom                        | 68        | 0.56%   |
| Kingston Technology              | 44        | 0.36%   |
| JMTek                            | 44        | 0.36%   |
| Corsair                          | 43        | 0.35%   |
| Texas Instruments                | 42        | 0.34%   |
| Plantronics                      | 41        | 0.34%   |
| VIA Technologies                 | 38        | 0.31%   |
| Focusrite-Novation               | 33        | 0.27%   |
| SteelSeries ApS                  | 27        | 0.22%   |
| Generalplus Technology           | 26        | 0.21%   |
| Razer USA                        | 23        | 0.19%   |
| Sennheiser Communications        | 20        | 0.16%   |
| Lenovo                           | 20        | 0.16%   |
| Silicon Integrated Systems [SiS] | 19        | 0.16%   |
| Hewlett-Packard                  | 16        | 0.13%   |
| ASUSTek Computer                 | 15        | 0.12%   |
| XMOS                             | 12        | 0.1%    |
| Creative Technology              | 12        | 0.1%    |
| M-Audio                          | 11        | 0.09%   |
| Sony                             | 10        | 0.08%   |
| BEHRINGER International          | 9         | 0.07%   |
| RODE Microphones                 | 8         | 0.07%   |
| PreSonus Audio Electronics       | 8         | 0.07%   |
| GYROCOM C&C                      | 7         | 0.06%   |
| Ensoniq                          | 7         | 0.06%   |
| Dell                             | 7         | 0.06%   |
| Yamaha                           | 6         | 0.05%   |
| Turtle Beach                     | 6         | 0.05%   |
| Tenx Technology                  | 6         | 0.05%   |
| Micro Star International         | 6         | 0.05%   |
| Alesis                           | 6         | 0.05%   |
| Medeli Electronics               | 5         | 0.04%   |
| DSEA A/S                         | 5         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 597       | 4.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 572       | 4.01%   |
| Intel Sunrise Point-LP HD Audio                                            | 565       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 539       | 3.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 501       | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 394       | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 379       | 2.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 320       | 2.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 306       | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 300       | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 297       | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 278       | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 277       | 1.94%   |
| AMD FCH Azalia Controller                                                  | 272       | 1.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 267       | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 247       | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 214       | 1.5%    |
| Intel 8 Series HD Audio Controller                                         | 206       | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 206       | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 203       | 1.42%   |
| Intel Broadwell-U Audio Controller                                         | 201       | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 197       | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 187       | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 181       | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 173       | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                               | 162       | 1.14%   |
| Intel 200 Series PCH HD Audio                                              | 157       | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                   | 140       | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 134       | 0.94%   |
| Nvidia High Definition Audio Controller                                    | 133       | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 133       | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 131       | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 119       | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 111       | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 109       | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 107       | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 106       | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 104       | 0.73%   |
| Intel CM238 HD Audio Controller                                            | 101       | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 99        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1461      | 22.39%  |
| SK hynix            | 1280      | 19.62%  |
| Unknown             | 664       | 10.18%  |
| Kingston            | 663       | 10.16%  |
| Micron Technology   | 632       | 9.69%   |
| Corsair             | 433       | 6.64%   |
| Crucial             | 423       | 6.48%   |
| G.Skill             | 312       | 4.78%   |
| Elpida              | 96        | 1.47%   |
| Ramaxel Technology  | 92        | 1.41%   |
| Nanya Technology    | 90        | 1.38%   |
| A-DATA Technology   | 61        | 0.93%   |
| Unknown (ABCD)      | 58        | 0.89%   |
| Transcend           | 33        | 0.51%   |
| Unknown             | 24        | 0.37%   |
| Patriot             | 18        | 0.28%   |
| Team                | 17        | 0.26%   |
| PNY                 | 15        | 0.23%   |
| Unifosa             | 14        | 0.21%   |
| Timetec             | 10        | 0.15%   |
| ASint Technology    | 9         | 0.14%   |
| Qimonda             | 8         | 0.12%   |
| Unknown (0x0C97)    | 6         | 0.09%   |
| Toshiba             | 5         | 0.08%   |
| TEXTORM             | 5         | 0.08%   |
| Hewlett-Packard     | 5         | 0.08%   |
| Apacer              | 5         | 0.08%   |
| V-Color             | 3         | 0.05%   |
| Swissbit            | 3         | 0.05%   |
| Silicon Power       | 3         | 0.05%   |
| SHARETRONIC         | 3         | 0.05%   |
| OCZ                 | 3         | 0.05%   |
| Lexar               | 3         | 0.05%   |
| Innodisk            | 3         | 0.05%   |
| Avant               | 3         | 0.05%   |
| Unknown (F301)      | 2         | 0.03%   |
| Unknown (07FB)      | 2         | 0.03%   |
| Ramos Technology    | 2         | 0.03%   |
| Neo Forza           | 2         | 0.03%   |
| Kllisre             | 2         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 58        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 58        | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 58        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 54        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 53        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 49        | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 42        | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 41        | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 41        | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 39        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 38        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 38        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 34        | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 33        | 0.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 32        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 30        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.36%   |
| Unknown                                                          | 24        | 0.34%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.33%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 23        | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 22        | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 22        | 0.32%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 22        | 0.32%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 20        | 0.29%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 19        | 0.27%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 19        | 0.27%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 19        | 0.27%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 19        | 0.27%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.26%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.26%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 18        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2470      | 43.52%  |
| DDR3    | 2062      | 36.33%  |
| DDR2    | 336       | 5.92%   |
| SDRAM   | 194       | 3.42%   |
| LPDDR4  | 190       | 3.35%   |
| Unknown | 159       | 2.8%    |
| LPDDR3  | 122       | 2.15%   |
| DDR     | 58        | 1.02%   |
| DDR5    | 40        | 0.7%    |
| LPDDR5  | 34        | 0.6%    |
| DRAM    | 9         | 0.16%   |
| RAM     | 1         | 0.02%   |
| EEPROM  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3125      | 55.58%  |
| DIMM         | 2110      | 37.52%  |
| Row Of Chips | 339       | 6.03%   |
| Chip         | 20        | 0.36%   |
| Unknown      | 11        | 0.2%    |
| RIMM         | 9         | 0.16%   |
| FB-DIMM      | 9         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2177      | 35.3%   |
| 4096  | 1914      | 31.04%  |
| 2048  | 894       | 14.5%   |
| 16384 | 746       | 12.1%   |
| 1024  | 276       | 4.48%   |
| 32768 | 114       | 1.85%   |
| 512   | 39        | 0.63%   |
| 65536 | 3         | 0.05%   |
| 256   | 3         | 0.05%   |
| 1     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1340      | 21.88%  |
| 2667    | 832       | 13.59%  |
| 3200    | 820       | 13.39%  |
| 2400    | 424       | 6.92%   |
| 1333    | 421       | 6.87%   |
| 2133    | 311       | 5.08%   |
| 1334    | 186       | 3.04%   |
| 667     | 180       | 2.94%   |
| 800     | 159       | 2.6%    |
| 1867    | 123       | 2.01%   |
| 3600    | 116       | 1.89%   |
| Unknown | 105       | 1.71%   |
| 1066    | 84        | 1.37%   |
| 4267    | 83        | 1.36%   |
| 1067    | 72        | 1.18%   |
| 3266    | 69        | 1.13%   |
| 1866    | 50        | 0.82%   |
| 2048    | 49        | 0.8%    |
| 2933    | 47        | 0.77%   |
| 3000    | 44        | 0.72%   |
| 4800    | 42        | 0.69%   |
| 2666    | 38        | 0.62%   |
| 3400    | 36        | 0.59%   |
| 533     | 36        | 0.59%   |
| 6400    | 33        | 0.54%   |
| 4199    | 33        | 0.54%   |
| 1800    | 33        | 0.54%   |
| 3466    | 31        | 0.51%   |
| 400     | 23        | 0.38%   |
| 3733    | 22        | 0.36%   |
| 975     | 22        | 0.36%   |
| 2800    | 19        | 0.31%   |
| 4266    | 17        | 0.28%   |
| 3800    | 16        | 0.26%   |
| 333     | 15        | 0.24%   |
| 3666    | 14        | 0.23%   |
| 2465    | 12        | 0.2%    |
| 1639    | 12        | 0.2%    |
| 3866    | 10        | 0.16%   |
| 2000    | 10        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 108       | 43.55%  |
| Canon                 | 39        | 15.73%  |
| Brother Industries    | 38        | 15.32%  |
| Samsung Electronics   | 31        | 12.5%   |
| Seiko Epson           | 17        | 6.85%   |
| Prolific Technology   | 3         | 1.21%   |
| STMicroelectronics    | 2         | 0.81%   |
| Ricoh                 | 2         | 0.81%   |
| QinHeng Electronics   | 2         | 0.81%   |
| Lexmark International | 2         | 0.81%   |
| Xiaomi                | 1         | 0.4%    |
| Xerox                 | 1         | 0.4%    |
| Kyocera               | 1         | 0.4%    |
| Apple                 | 1         | 0.4%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 9         | 3.61%   |
| HP ENVY 4520 series                                       | 9         | 3.61%   |
| HP DeskJet 3630 series                                    | 9         | 3.61%   |
| HP DeskJet 2700 series                                    | 9         | 3.61%   |
| HP ENVY Photo 6200 series                                 | 6         | 2.41%   |
| Canon PIXMA MG3600 Series                                 | 6         | 2.41%   |
| HP DeskJet 2620 All-in-One Printer                        | 5         | 2.01%   |
| HP ENVY 5000 series                                       | 4         | 1.61%   |
| HP DeskJet Plus 4100 series                               | 4         | 1.61%   |
| HP DeskJet 3700 series                                    | 4         | 1.61%   |
| Brother HL-2030 Laser Printer                             | 4         | 1.61%   |
| Seiko Epson XP-243 245 247 Series                         | 3         | 1.2%    |
| Samsung M2020 Series                                      | 3         | 1.2%    |
| Prolific PL2305 Parallel Port                             | 3         | 1.2%    |
| HP OfficeJet 3830 series                                  | 3         | 1.2%    |
| HP Deskjet 3050A                                          | 3         | 1.2%    |
| Canon PIXMA MG2500 Series                                 | 3         | 1.2%    |
| Brother Printer                                           | 3         | 1.2%    |
| Brother MFC-L2710DW series                                | 3         | 1.2%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.8%    |
| Seiko Epson XP-255 257 Series                             | 2         | 0.8%    |
| Seiko Epson XP-2100 Series                                | 2         | 0.8%    |
| Seiko Epson WF-2830 Series                                | 2         | 0.8%    |
| Samsung SCX-3400 Series                                   | 2         | 0.8%    |
| Samsung SCX-3200 Series                                   | 2         | 0.8%    |
| Samsung ML-1660 Series                                    | 2         | 0.8%    |
| Samsung ML-1640 Series Laser Printer                      | 2         | 0.8%    |
| Samsung ML-1630 Series                                    | 2         | 0.8%    |
| Samsung CLX-3180 Series                                   | 2         | 0.8%    |
| Samsung CLX-3170 Series                                   | 2         | 0.8%    |
| QinHeng CH340S                                            | 2         | 0.8%    |
| HP OfficeJet Pro 69                                       | 2         | 0.8%    |
| HP ENVY Pro 6400 series                                   | 2         | 0.8%    |
| HP ENVY 5540 series                                       | 2         | 0.8%    |
| HP ENVY 4500 series                                       | 2         | 0.8%    |
| HP DeskJet F4200 series                                   | 2         | 0.8%    |
| HP DeskJet 5550                                           | 2         | 0.8%    |
| HP Deskjet 3070 B611 series                               | 2         | 0.8%    |
| HP DeskJet 2130 series                                    | 2         | 0.8%    |
| HP Deskjet 1510                                           | 2         | 0.8%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 54        | 61.36%  |
| Seiko Epson     | 22        | 25%     |
| Hewlett-Packard | 8         | 9.09%   |
| AGFA-Gevaert NV | 4         | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 9         | 10.23%  |
| Canon CanoScan N1240U/LiDE 30                                 | 9         | 10.23%  |
| Canon CanoScan LiDE 110                                       | 9         | 10.23%  |
| Canon CanoScan LIDE 25                                        | 7         | 7.95%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4         | 4.55%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3         | 3.41%   |
| Canon CanoScan LiDE 200                                       | 3         | 3.41%   |
| AGFA-Gevaert NV SnapScan e20                                  | 3         | 3.41%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2         | 2.27%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 2         | 2.27%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2         | 2.27%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2         | 2.27%   |
| HP ScanJet 3570c                                              | 2         | 2.27%   |
| Canon CanoScan N650U/N656U                                    | 2         | 2.27%   |
| Canon CanoScan LiDE 60                                        | 2         | 2.27%   |
| Canon CanoScan LiDE 220                                       | 2         | 2.27%   |
| Canon CanoScan LiDE 210                                       | 2         | 2.27%   |
| Canon CanoScan 4200F                                          | 2         | 2.27%   |
| Seiko Epson Scanner                                           | 1         | 1.14%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]              | 1         | 1.14%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 1.14%   |
| Seiko Epson GT-F700 [Perfection V350]                         | 1         | 1.14%   |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1         | 1.14%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 1.14%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 1.14%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 1         | 1.14%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 1.14%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 1.14%   |
| HP ScanJet G4010                                              | 1         | 1.14%   |
| HP ScanJet 5200c                                              | 1         | 1.14%   |
| HP ScanJet 4570c                                              | 1         | 1.14%   |
| HP ScanJet 3500c                                              | 1         | 1.14%   |
| HP ScanJet 2300c                                              | 1         | 1.14%   |
| HP PSC 1200                                                   | 1         | 1.14%   |
| Canon CanoScan LiDE 70                                        | 1         | 1.14%   |
| Canon CanoScan LiDE 120                                       | 1         | 1.14%   |
| Canon CanoScan 9000F Mark II                                  | 1         | 1.14%   |
| Canon CanoScan 4400F                                          | 1         | 1.14%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 1.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1118      | 21.71%  |
| IMC Networks                           | 522       | 10.14%  |
| Microdia                               | 477       | 9.26%   |
| Realtek Semiconductor                  | 449       | 8.72%   |
| Logitech                               | 345       | 6.7%    |
| Sunplus Innovation Technology          | 289       | 5.61%   |
| Bison Electronics                      | 203       | 3.94%   |
| Suyin                                  | 188       | 3.65%   |
| Cheng Uei Precision Industry (Foxlink) | 180       | 3.5%    |
| Quanta                                 | 172       | 3.34%   |
| Acer                                   | 172       | 3.34%   |
| Apple                                  | 142       | 2.76%   |
| Lite-On Technology                     | 115       | 2.23%   |
| Syntek                                 | 100       | 1.94%   |
| Alcor Micro                            | 61        | 1.18%   |
| Samsung Electronics                    | 56        | 1.09%   |
| Luxvisions Innotech Limited            | 53        | 1.03%   |
| Microsoft                              | 51        | 0.99%   |
| Silicon Motion                         | 45        | 0.87%   |
| Ricoh                                  | 45        | 0.87%   |
| Sonix Technology                       | 28        | 0.54%   |
| Guillemot                              | 25        | 0.49%   |
| Lenovo                                 | 21        | 0.41%   |
| Z-Star Microelectronics                | 19        | 0.37%   |
| Primax Electronics                     | 18        | 0.35%   |
| Importek                               | 15        | 0.29%   |
| GEMBIRD                                | 15        | 0.29%   |
| DigiTech                               | 14        | 0.27%   |
| Creative Technology                    | 14        | 0.27%   |
| Generalplus Technology                 | 13        | 0.25%   |
| ARC International                      | 13        | 0.25%   |
| ALi                                    | 12        | 0.23%   |
| Hewlett-Packard                        | 10        | 0.19%   |
| 2M UVC CAMERA                          | 8         | 0.16%   |
| Sunplus IT                             | 7         | 0.14%   |
| KYE Systems (Mouse Systems)            | 7         | 0.14%   |
| OmniVision Technologies                | 6         | 0.12%   |
| icSpring                               | 6         | 0.12%   |
| Cubeternet                             | 6         | 0.12%   |
| Y Media                                | 5         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 235       | 4.54%   |
| Realtek Integrated_Webcam_HD             | 192       | 3.71%   |
| Chicony Integrated Camera                | 166       | 3.21%   |
| IMC Networks USB2.0 HD UVC WebCam        | 124       | 2.4%    |
| Chicony HD WebCam                        | 106       | 2.05%   |
| IMC Networks Integrated Camera           | 95        | 1.84%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 88        | 1.7%    |
| Logitech Webcam C270                     | 76        | 1.47%   |
| Sunplus Integrated_Webcam_HD             | 75        | 1.45%   |
| Samsung Galaxy series, misc. (MTP mode)  | 56        | 1.08%   |
| Realtek USB Camera                       | 56        | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam            | 51        | 0.99%   |
| Chicony USB2.0 Camera                    | 50        | 0.97%   |
| Chicony HP HD Camera                     | 49        | 0.95%   |
| Apple Built-in iSight                    | 47        | 0.91%   |
| Syntek Integrated Camera                 | 45        | 0.87%   |
| Acer Integrated Camera                   | 45        | 0.87%   |
| Bison HD Webcam                          | 44        | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 44        | 0.85%   |
| Chicony USB2.0 HD UVC WebCam             | 43        | 0.83%   |
| Chicony TOSHIBA Web Camera - HD          | 42        | 0.81%   |
| Microdia Integrated Webcam               | 41        | 0.79%   |
| Bison Integrated Camera                  | 41        | 0.79%   |
| Sunplus Asus Webcam                      | 40        | 0.77%   |
| Chicony HP TrueVision HD                 | 39        | 0.75%   |
| Logitech HD Pro Webcam C920              | 37        | 0.72%   |
| Lite-On Integrated Camera                | 37        | 0.72%   |
| Chicony USB 2.0 Camera                   | 37        | 0.72%   |
| Chicony HP Truevision HD camera          | 36        | 0.7%    |
| Chicony HP HD Webcam                     | 36        | 0.7%    |
| Bison BisonCam,NB Pro                    | 36        | 0.7%    |
| Realtek USB2.0 HD UVC WebCam             | 35        | 0.68%   |
| Logitech HD Webcam C525                  | 31        | 0.6%    |
| Quanta HP HD Camera                      | 30        | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 29        | 0.56%   |
| Chicony VGA Webcam                       | 29        | 0.56%   |
| Sunplus HD WebCam                        | 28        | 0.54%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 28        | 0.54%   |
| Acer BisonCam, NB Pro                    | 28        | 0.54%   |
| IMC Networks UVC VGA Webcam              | 25        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 299       | 35.09%  |
| Synaptics                          | 195       | 22.89%  |
| Shenzhen Goodix Technology         | 161       | 18.9%   |
| AuthenTec                          | 65        | 7.63%   |
| Elan Microelectronics              | 46        | 5.4%    |
| LighTuning Technology              | 42        | 4.93%   |
| Upek                               | 31        | 3.64%   |
| STMicroelectronics                 | 11        | 1.29%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.12%   |
| Focal-systems.Corp                 | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 82        | 9.62%   |
| Shenzhen Goodix  FingerPrint Device                                        | 81        | 9.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 69        | 8.1%    |
| Shenzhen Goodix FingerPrint                                                | 42        | 4.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 38        | 4.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 36        | 4.23%   |
| Elan ELAN:Fingerprint                                                      | 34        | 3.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 3.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 3.17%   |
| Validity Sensors VFS491                                                    | 24        | 2.82%   |
| AuthenTec AES2810                                                          | 24        | 2.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 2.7%    |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 2%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 1.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 15        | 1.76%   |
| Synaptics UWP WBDI                                                         | 15        | 1.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.64%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 1.64%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 1.64%   |
| AuthenTec AES1600                                                          | 14        | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 1.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 1.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 1.53%   |
| AuthenTec Fingerprint Sensor                                               | 13        | 1.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.29%   |
| Synaptics  WBDI                                                            | 11        | 1.29%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.29%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.17%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 1.17%   |
| Unknown                                                                    | 7         | 0.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.59%   |
| Synaptics WBDI Device                                                      | 5         | 0.59%   |
| Synaptics WBDI                                                             | 5         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.35%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 231       | 53.47%  |
| Alcor Micro               | 88        | 20.37%  |
| O2 Micro                  | 36        | 8.33%   |
| Upek                      | 17        | 3.94%   |
| Lenovo                    | 16        | 3.7%    |
| Hewlett-Packard           | 9         | 2.08%   |
| Gemalto (was Gemplus)     | 9         | 2.08%   |
| Aladdin Knowledge Systems | 5         | 1.16%   |
| Yubico.com                | 4         | 0.93%   |
| Clay Logic                | 3         | 0.69%   |
| Chicony Electronics       | 3         | 0.69%   |
| SCM Microsystems          | 2         | 0.46%   |
| Realtek Semiconductor     | 2         | 0.46%   |
| Feitian Technologies      | 2         | 0.46%   |
| ST-Ericsson               | 1         | 0.23%   |
| SpringCard                | 1         | 0.23%   |
| OmniKey                   | 1         | 0.23%   |
| Cherry                    | 1         | 0.23%   |
| Advanced Card Systems     | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 87        | 20.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 77        | 17.82%  |
| Broadcom 58200                                                               | 72        | 16.67%  |
| Broadcom 5880                                                                | 48        | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 33        | 7.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 33        | 7.64%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 3.94%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 3.7%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 9         | 2.08%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.39%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 1.16%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 4         | 0.93%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 0.69%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.46%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.46%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.46%   |
| ST-Ericsson Chipcard Reader                                                  | 1         | 0.23%   |
| SpringCard Two                                                               | 1         | 0.23%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.23%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.23%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.23%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.23%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.23%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.23%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.23%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.23%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6301      | 70.88%  |
| 1     | 2054      | 23.1%   |
| 2     | 419       | 4.71%   |
| 3     | 81        | 0.91%   |
| 4     | 20        | 0.22%   |
| 5     | 7         | 0.08%   |
| 6     | 3         | 0.03%   |
| 8     | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 842       | 26.92%  |
| Graphics card            | 786       | 25.13%  |
| Chipcard                 | 391       | 12.5%   |
| Net/wireless             | 332       | 10.61%  |
| Multimedia controller    | 147       | 4.7%    |
| Communication controller | 122       | 3.9%    |
| Camera                   | 104       | 3.32%   |
| Bluetooth                | 83        | 2.65%   |
| Unassigned class         | 74        | 2.37%   |
| Storage                  | 57        | 1.82%   |
| Sound                    | 47        | 1.5%    |
| Card reader              | 43        | 1.37%   |
| Net/ethernet             | 29        | 0.93%   |
| Modem                    | 20        | 0.64%   |
| Network                  | 15        | 0.48%   |
| Storage/raid             | 7         | 0.22%   |
| Firewire controller      | 7         | 0.22%   |
| Storage/ide              | 5         | 0.16%   |
| Dvb card                 | 5         | 0.16%   |
| Flash memory             | 4         | 0.13%   |
| Wireless                 | 2         | 0.06%   |
| Unclassified device      | 2         | 0.06%   |
| Tv card                  | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |

