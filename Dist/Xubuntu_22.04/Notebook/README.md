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

Total: 294

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| Dell          | XPS 13 9333                 | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| HP            | Laptop 17-cp2xxx            | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Toshiba       | Satellite L750D             | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Medion        | S321X                       | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| HP            | EliteBook 6930p             | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| Gateway       | EC14 Series                 | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| Gateway       | EC14 Series                 | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Google        | Kefka                       | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| GPU Compan... | GWTN156-5                   | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| Toshiba       | Satellite C55D-B            | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
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


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.0-56-generic      | 23        | 9.27%   |
| 5.15.0-47-generic      | 19        | 7.66%   |
| 5.15.0-58-generic      | 17        | 6.85%   |
| 5.15.0-52-generic      | 16        | 6.45%   |
| 5.15.0-48-generic      | 16        | 6.45%   |
| 5.15.0-60-generic      | 13        | 5.24%   |
| 5.15.0-25-generic      | 13        | 5.24%   |
| 5.15.0-67-generic      | 10        | 4.03%   |
| 5.19.0-38-generic      | 9         | 3.63%   |
| 5.15.0-46-generic      | 8         | 3.23%   |
| 5.19.0-35-generic      | 7         | 2.82%   |
| 5.15.0-53-generic      | 7         | 2.82%   |
| 5.15.0-27-generic      | 7         | 2.82%   |
| 5.15.0-57-generic      | 6         | 2.42%   |
| 5.15.0-69-generic      | 5         | 2.02%   |
| 5.15.0-50-generic      | 5         | 2.02%   |
| 5.15.0-40-generic      | 5         | 2.02%   |
| 5.15.0-39-generic      | 5         | 2.02%   |
| 5.15.0-35-generic      | 5         | 2.02%   |
| 5.15.0-43-generic      | 4         | 1.61%   |
| 5.15.0-41-generic      | 4         | 1.61%   |
| 5.19.0-32-generic      | 3         | 1.21%   |
| 5.17.0-1020-oem        | 3         | 1.21%   |
| 5.15.0-70-generic      | 3         | 1.21%   |
| 5.15.0-37-generic      | 3         | 1.21%   |
| 5.17.0-1013-oem        | 2         | 0.81%   |
| 5.15.0-33-generic      | 2         | 0.81%   |
| 6.1.6-060106-generic   | 1         | 0.4%    |
| 6.1.0-1008-oem         | 1         | 0.4%    |
| 6.1.0-1006-oem         | 1         | 0.4%    |
| 6.0.9-060009-generic   | 1         | 0.4%    |
| 6.0.7-x64v3-xanmod1    | 1         | 0.4%    |
| 6.0.0-1007-oem         | 1         | 0.4%    |
| 5.4.0-126-generic      | 1         | 0.4%    |
| 5.19.5-051905-generic  | 1         | 0.4%    |
| 5.19.0-41-generic      | 1         | 0.4%    |
| 5.19.0-40-generic      | 1         | 0.4%    |
| 5.19.0-28-generic      | 1         | 0.4%    |
| 5.19.0-1017-lowlatency | 1         | 0.4%    |
| 5.19.0-051900-generic  | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 195       | 81.93%  |
| 5.19.0   | 23        | 9.66%   |
| 5.17.0   | 9         | 3.78%   |
| 6.1.0    | 2         | 0.84%   |
| 6.1.6    | 1         | 0.42%   |
| 6.0.9    | 1         | 0.42%   |
| 6.0.7    | 1         | 0.42%   |
| 6.0.0    | 1         | 0.42%   |
| 5.4.0    | 1         | 0.42%   |
| 5.19.5   | 1         | 0.42%   |
| 5.18.0   | 1         | 0.42%   |
| 5.17.3   | 1         | 0.42%   |
| 4.19.241 | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 195       | 81.93%  |
| 5.19    | 24        | 10.08%  |
| 5.17    | 10        | 4.2%    |
| 6.1     | 3         | 1.26%   |
| 6.0     | 3         | 1.26%   |
| 5.4     | 1         | 0.42%   |
| 5.18    | 1         | 0.42%   |
| 4.19    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 238       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 231       | 97.06%  |
| GNOME | 7         | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 229       | 96.22%  |
| Wayland | 7         | 2.94%   |
| Tty     | 2         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 212       | 89.08%  |
| GDM3    | 14        | 5.88%   |
| Unknown | 8         | 3.36%   |
| SLiM    | 2         | 0.84%   |
| SDDM    | 2         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 104       | 43.7%   |
| de_DE | 32        | 13.45%  |
| fr_FR | 22        | 9.24%   |
| it_IT | 12        | 5.04%   |
| en_GB | 11        | 4.62%   |
| ru_RU | 6         | 2.52%   |
| es_ES | 5         | 2.1%    |
| pt_BR | 4         | 1.68%   |
| en_IN | 4         | 1.68%   |
| en_AU | 4         | 1.68%   |
| nl_NL | 3         | 1.26%   |
| en_CA | 3         | 1.26%   |
| cs_CZ | 3         | 1.26%   |
| tr_TR | 2         | 0.84%   |
| ja_JP | 2         | 0.84%   |
| hu_HU | 2         | 0.84%   |
| es_MX | 2         | 0.84%   |
| C     | 2         | 0.84%   |
| zh_CN | 1         | 0.42%   |
| ru_UA | 1         | 0.42%   |
| ro_RO | 1         | 0.42%   |
| pt_PT | 1         | 0.42%   |
| pl_PL | 1         | 0.42%   |
| nl_BE | 1         | 0.42%   |
| fr_BE | 1         | 0.42%   |
| es_VE | 1         | 0.42%   |
| es_CO | 1         | 0.42%   |
| es_CL | 1         | 0.42%   |
| en_IL | 1         | 0.42%   |
| en_IE | 1         | 0.42%   |
| el_GR | 1         | 0.42%   |
| de_CH | 1         | 0.42%   |
| bg_BG | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 130       | 54.17%  |
| BIOS | 110       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 210       | 87.87%  |
| Zfs     | 9         | 3.77%   |
| Overlay | 9         | 3.77%   |
| Btrfs   | 7         | 2.93%   |
| Tmpfs   | 4         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 177       | 72.54%  |
| MBR     | 34        | 13.93%  |
| Unknown | 33        | 13.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 91.67%  |
| Yes       | 20        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 72.27%  |
| Yes       | 66        | 27.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 55        | 23.11%  |
| Hewlett-Packard     | 49        | 20.59%  |
| Dell                | 28        | 11.76%  |
| ASUSTek Computer    | 26        | 10.92%  |
| Acer                | 22        | 9.24%   |
| Toshiba             | 7         | 2.94%   |
| Google              | 7         | 2.94%   |
| Sony                | 4         | 1.68%   |
| GPU Company         | 4         | 1.68%   |
| HUAWEI              | 3         | 1.26%   |
| Apple               | 3         | 1.26%   |
| Unknown             | 3         | 1.26%   |
| Samsung Electronics | 2         | 0.84%   |
| Notebook            | 2         | 0.84%   |
| MSI                 | 2         | 0.84%   |
| HONOR               | 2         | 0.84%   |
| Tactus              | 1         | 0.42%   |
| Standard            | 1         | 0.42%   |
| SGIN                | 1         | 0.42%   |
| Schenker            | 1         | 0.42%   |
| Panasonic           | 1         | 0.42%   |
| Packard Bell        | 1         | 0.42%   |
| Medion              | 1         | 0.42%   |
| Mediacom            | 1         | 0.42%   |
| HIGRADED            | 1         | 0.42%   |
| Gigabyte Technology | 1         | 0.42%   |
| Getac               | 1         | 0.42%   |
| Gateway             | 1         | 0.42%   |
| Fusion5             | 1         | 0.42%   |
| ECS                 | 1         | 0.42%   |
| Digma               | 1         | 0.42%   |
| Daten Tecnologia    | 1         | 0.42%   |
| Clevo               | 1         | 0.42%   |
| Chuwi               | 1         | 0.42%   |
| AMI                 | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                                                      | 4         | 1.68%   |
| Unknown                                                                                  | 4         | 1.68%   |
| HP Pavilion Notebook                                                                     | 2         | 0.84%   |
| HP Pavilion g6                                                                           | 2         | 0.84%   |
| HP Pavilion 15                                                                           | 2         | 0.84%   |
| HP Laptop 15s-fq2xxx                                                                     | 2         | 0.84%   |
| HP 255 G8 Notebook PC                                                                    | 2         | 0.84%   |
| GPU Company GWTN116-3                                                                    | 2         | 0.84%   |
| Dell Latitude E5450                                                                      | 2         | 0.84%   |
| ASUS ASUS TUF Gaming A15 FA507RE_FA507RE                                                 | 2         | 0.84%   |
| Apple MacBookPro8,1                                                                      | 2         | 0.84%   |
| Toshiba Satellite Pro R50-C                                                              | 1         | 0.42%   |
| Toshiba Satellite Pro R50-B                                                              | 1         | 0.42%   |
| Toshiba Satellite L750D                                                                  | 1         | 0.42%   |
| Toshiba Satellite C650                                                                   | 1         | 0.42%   |
| Toshiba Satellite C55D-B                                                                 | 1         | 0.42%   |
| Toshiba PT10F                                                                            | 1         | 0.42%   |
| Toshiba EQUIUM P200                                                                      | 1         | 0.42%   |
| Tactus GeoBook 140                                                                       | 1         | 0.42%   |
| Sony VPCS12V9E                                                                           | 1         | 0.42%   |
| Sony VPCEH25EN                                                                           | 1         | 0.42%   |
| Sony VPCEA3S1E                                                                           | 1         | 0.42%   |
| Sony SVE1512C6EB                                                                         | 1         | 0.42%   |
| SGIN M15                                                                                 | 1         | 0.42%   |
| Schenker WORK (Early 2021)                                                               | 1         | 0.42%   |
| Samsung 370E4K                                                                           | 1         | 0.42%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.42%   |
| Panasonic CF-D1DVA06F3                                                                   | 1         | 0.42%   |
| Packard Bell EasyNote MH45                                                               | 1         | 0.42%   |
| Notebook W65_67SZ                                                                        | 1         | 0.42%   |
| Notebook NJx0MU                                                                          | 1         | 0.42%   |
| MSI GP65 Leopard 10SDK                                                                   | 1         | 0.42%   |
| MSI GF63 Thin 9RCX                                                                       | 1         | 0.42%   |
| Medion S321X                                                                             | 1         | 0.42%   |
| Mediacom SmartBook 14 FullHD - SB14UC                                                    | 1         | 0.42%   |
| Lenovo V340-17IWL 81RG                                                                   | 1         | 0.42%   |
| Lenovo V330-15IKB 81AX                                                                   | 1         | 0.42%   |
| Lenovo V15 G2 ALC 82KD                                                                   | 1         | 0.42%   |
| Lenovo ThinkPad X270 W10DG 20K5S0B700                                                    | 1         | 0.42%   |
| Lenovo ThinkPad X230 23252S4                                                             | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 36        | 15.13%  |
| Acer Aspire            | 17        | 7.14%   |
| HP Pavilion            | 13        | 5.46%   |
| Dell Latitude          | 12        | 5.04%   |
| HP EliteBook           | 10        | 4.2%    |
| Lenovo IdeaPad         | 8         | 3.36%   |
| HP Laptop              | 6         | 2.52%   |
| Dell Inspiron          | 6         | 2.52%   |
| Toshiba Satellite      | 5         | 2.1%    |
| ASUS VivoBook          | 5         | 2.1%    |
| Dell XPS               | 4         | 1.68%   |
| Unknown                | 4         | 1.68%   |
| HP ProBook             | 3         | 1.26%   |
| HP Compaq              | 3         | 1.26%   |
| HP 255                 | 3         | 1.26%   |
| Dell Precision         | 3         | 1.26%   |
| ASUS ASUS              | 3         | 1.26%   |
| Lenovo ThinkBook       | 2         | 0.84%   |
| HP Stream              | 2         | 0.84%   |
| HP 250                 | 2         | 0.84%   |
| GPU Company GWTN116-3  | 2         | 0.84%   |
| ASUS ZenBook           | 2         | 0.84%   |
| Apple MacBookPro8      | 2         | 0.84%   |
| Toshiba PT10F          | 1         | 0.42%   |
| Toshiba EQUIUM         | 1         | 0.42%   |
| Tactus GeoBook         | 1         | 0.42%   |
| Sony VPCS12V9E         | 1         | 0.42%   |
| Sony VPCEH25EN         | 1         | 0.42%   |
| Sony VPCEA3S1E         | 1         | 0.42%   |
| Sony SVE1512C6EB       | 1         | 0.42%   |
| SGIN M15               | 1         | 0.42%   |
| Schenker WORK          | 1         | 0.42%   |
| Samsung 370E4K         | 1         | 0.42%   |
| Samsung 350V5C         | 1         | 0.42%   |
| Panasonic CF-D1DVA06F3 | 1         | 0.42%   |
| Packard Bell EasyNote  | 1         | 0.42%   |
| Notebook W65           | 1         | 0.42%   |
| Notebook NJx0MU        | 1         | 0.42%   |
| MSI GP65               | 1         | 0.42%   |
| MSI GF63               | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 28        | 11.76%  |
| 2020 | 25        | 10.5%   |
| 2022 | 18        | 7.56%   |
| 2017 | 17        | 7.14%   |
| 2016 | 17        | 7.14%   |
| 2014 | 16        | 6.72%   |
| 2011 | 16        | 6.72%   |
| 2015 | 15        | 6.3%    |
| 2012 | 14        | 5.88%   |
| 2019 | 12        | 5.04%   |
| 2013 | 12        | 5.04%   |
| 2009 | 12        | 5.04%   |
| 2018 | 10        | 4.2%    |
| 2008 | 9         | 3.78%   |
| 2007 | 8         | 3.36%   |
| 2010 | 7         | 2.94%   |
| 2023 | 1         | 0.42%   |
| 2006 | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 238       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 216       | 90.76%  |
| Enabled  | 22        | 9.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 231       | 97.06%  |
| Yes  | 7         | 2.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 74        | 31.09%  |
| 4.01-8.0    | 69        | 28.99%  |
| 8.01-16.0   | 31        | 13.03%  |
| 16.01-24.0  | 29        | 12.18%  |
| 32.01-64.0  | 12        | 5.04%   |
| 1.01-2.0    | 10        | 4.2%    |
| 64.01-256.0 | 5         | 2.1%    |
| 2.01-3.0    | 4         | 1.68%   |
| 24.01-32.0  | 3         | 1.26%   |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 109       | 44.67%  |
| 2.01-3.0   | 68        | 27.87%  |
| 3.01-4.0   | 20        | 8.2%    |
| 0.51-1.0   | 20        | 8.2%    |
| 4.01-8.0   | 16        | 6.56%   |
| 8.01-16.0  | 9         | 3.69%   |
| 24.01-32.0 | 1         | 0.41%   |
| 16.01-24.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 181       | 76.05%  |
| 2      | 49        | 20.59%  |
| 3      | 4         | 1.68%   |
| 4      | 2         | 0.84%   |
| 0      | 2         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 61.76%  |
| Yes       | 91        | 38.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 77.73%  |
| No        | 53        | 22.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 235       | 98.74%  |
| No        | 3         | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 79.41%  |
| No        | 49        | 20.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 41        | 17.15%  |
| Germany      | 39        | 16.32%  |
| France       | 28        | 11.72%  |
| Italy        | 15        | 6.28%   |
| UK           | 10        | 4.18%   |
| Russia       | 9         | 3.77%   |
| Netherlands  | 7         | 2.93%   |
| India        | 7         | 2.93%   |
| Mexico       | 6         | 2.51%   |
| Spain        | 5         | 2.09%   |
| Poland       | 5         | 2.09%   |
| Czechia      | 5         | 2.09%   |
| Brazil       | 5         | 2.09%   |
| Australia    | 4         | 1.67%   |
| Sweden       | 3         | 1.26%   |
| Malaysia     | 3         | 1.26%   |
| Iran         | 3         | 1.26%   |
| Belgium      | 3         | 1.26%   |
| Austria      | 3         | 1.26%   |
| Venezuela    | 2         | 0.84%   |
| Turkey       | 2         | 0.84%   |
| Switzerland  | 2         | 0.84%   |
| Japan        | 2         | 0.84%   |
| Israel       | 2         | 0.84%   |
| Indonesia    | 2         | 0.84%   |
| Hungary      | 2         | 0.84%   |
| Colombia     | 2         | 0.84%   |
| Canada       | 2         | 0.84%   |
| Belarus      | 2         | 0.84%   |
| Argentina    | 2         | 0.84%   |
| Vietnam      | 1         | 0.42%   |
| Ukraine      | 1         | 0.42%   |
| Slovenia     | 1         | 0.42%   |
| Sint Maarten | 1         | 0.42%   |
| Romania      | 1         | 0.42%   |
| Portugal     | 1         | 0.42%   |
| Panama       | 1         | 0.42%   |
| Madagascar   | 1         | 0.42%   |
| Ireland      | 1         | 0.42%   |
| Greece       | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Munich        | 5         | 2.04%   |
| Paris         | 4         | 1.63%   |
| Melbourne     | 4         | 1.63%   |
| Warsaw        | 3         | 1.22%   |
| North Hills   | 3         | 1.22%   |
| Milan         | 3         | 1.22%   |
| Kuala Lumpur  | 3         | 1.22%   |
| Hamburg       | 3         | 1.22%   |
| Uppsala       | 2         | 0.82%   |
| Stuttgart     | 2         | 0.82%   |
| St Petersburg | 2         | 0.82%   |
| Springfield   | 2         | 0.82%   |
| Rochester     | 2         | 0.82%   |
| Puebla City   | 2         | 0.82%   |
| Oklahoma City | 2         | 0.82%   |
| Oberhausen    | 2         | 0.82%   |
| Mumbai        | 2         | 0.82%   |
| Moscow        | 2         | 0.82%   |
| Mexico City   | 2         | 0.82%   |
| Lincoln       | 2         | 0.82%   |
| Leipzig       | 2         | 0.82%   |
| Indianapolis  | 2         | 0.82%   |
| Hanover       | 2         | 0.82%   |
| Farmington    | 2         | 0.82%   |
| Brest         | 2         | 0.82%   |
| Bordeaux      | 2         | 0.82%   |
| Berlin        | 2         | 0.82%   |
| Belfort       | 2         | 0.82%   |
| Auxerre       | 2         | 0.82%   |
| Ankara        | 2         | 0.82%   |
| Yokohama      | 1         | 0.41%   |
| Wittenborn    | 1         | 0.41%   |
| Wierden       | 1         | 0.41%   |
| Wetzlar       | 1         | 0.41%   |
| Washington    | 1         | 0.41%   |
| Villavicencio | 1         | 0.41%   |
| Villach       | 1         | 0.41%   |
| Vienna        | 1         | 0.41%   |
| Vidin         | 1         | 0.41%   |
| Verona        | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 45        | 50     | 16.07%  |
| WDC                         | 31        | 33     | 11.07%  |
| Unknown                     | 28        | 33     | 10%     |
| Seagate                     | 28        | 31     | 10%     |
| SanDisk                     | 15        | 15     | 5.36%   |
| SK hynix                    | 14        | 16     | 5%      |
| Kingston                    | 12        | 14     | 4.29%   |
| Hitachi                     | 10        | 10     | 3.57%   |
| Toshiba                     | 9         | 9      | 3.21%   |
| Intel                       | 9         | 9      | 3.21%   |
| Crucial                     | 8         | 8      | 2.86%   |
| Micron Technology           | 6         | 6      | 2.14%   |
| HGST                        | 6         | 7      | 2.14%   |
| A-DATA Technology           | 5         | 8      | 1.79%   |
| PNY                         | 4         | 4      | 1.43%   |
| Phison                      | 4         | 4      | 1.43%   |
| China                       | 4         | 5      | 1.43%   |
| Transcend                   | 3         | 4      | 1.07%   |
| SPCC                        | 3         | 3      | 1.07%   |
| Fujitsu                     | 3         | 3      | 1.07%   |
| Unknown                     | 3         | 3      | 1.07%   |
| TO Exter                    | 2         | 2      | 0.71%   |
| Silicon Motion              | 2         | 2      | 0.71%   |
| LITEON                      | 2         | 2      | 0.71%   |
| Kingston Technology Company | 2         | 2      | 0.71%   |
| FORESEE                     | 2         | 3      | 0.71%   |
| Apacer                      | 2         | 2      | 0.71%   |
| USB3.0                      | 1         | 2      | 0.36%   |
| UMIS                        | 1         | 1      | 0.36%   |
| Team                        | 1         | 2      | 0.36%   |
| SSSTC                       | 1         | 1      | 0.36%   |
| SSD0240S                    | 1         | 1      | 0.36%   |
| Realtek Semiconductor       | 1         | 1      | 0.36%   |
| Patriot                     | 1         | 1      | 0.36%   |
| Netac                       | 1         | 1      | 0.36%   |
| LITEONIT                    | 1         | 1      | 0.36%   |
| Lenovo                      | 1         | 1      | 0.36%   |
| Kimtigo                     | 1         | 1      | 0.36%   |
| JMicron Technology          | 1         | 1      | 0.36%   |
| Intenso                     | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 3         | 1.04%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.04%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.04%   |
| Samsung SSD 860 EVO 500GB            | 3         | 1.04%   |
| Samsung SSD 850 EVO 500GB            | 3         | 1.04%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 1.04%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.04%   |
| Unknown                              | 3         | 1.04%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 0.69%   |
| WDC PC SN530 SDBPNPZ-512G-1036 512GB | 2         | 0.69%   |
| Unknown SD/MMC/MS PRO 249GB          | 2         | 0.69%   |
| Unknown SA08G  8GB                   | 2         | 0.69%   |
| Unknown MMC64G  64GB                 | 2         | 0.69%   |
| Unknown MMC Card  128GB              | 2         | 0.69%   |
| TO Exter nal USB 3.0 320GB           | 2         | 0.69%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.69%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.69%   |
| Seagate ST1000LM035-1RK172 970GB     | 2         | 0.69%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.69%   |
| SanDisk DF4032  32GB                 | 2         | 0.69%   |
| Samsung SSD 980 500GB                | 2         | 0.69%   |
| Samsung SSD 870 QVO 4TB              | 2         | 0.69%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.69%   |
| PNY CS900 120GB SSD                  | 2         | 0.69%   |
| Phison 311CD0512GB                   | 2         | 0.69%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.69%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.69%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.69%   |
| FORESEE 256GB SSD                    | 2         | 0.69%   |
| WDC WDS960G2G0C-00AJM0 960GB         | 1         | 0.35%   |
| WDC WDS500G2B0C 500GB                | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.35%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.35%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 1         | 0.35%   |
| WDC WD7500BPVT-60HXZT3 752GB         | 1         | 0.35%   |
| WDC WD5000LPVX-08V0TT5 500GB         | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 28        | 31     | 35.44%  |
| WDC                | 20        | 21     | 25.32%  |
| Hitachi            | 10        | 10     | 12.66%  |
| Toshiba            | 8         | 8      | 10.13%  |
| HGST               | 6         | 7      | 7.59%   |
| Fujitsu            | 3         | 3      | 3.8%    |
| Unknown            | 2         | 3      | 2.53%   |
| USB3.0             | 1         | 2      | 1.27%   |
| JMicron Technology | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 20%     |
| Kingston            | 11        | 12     | 11.58%  |
| SanDisk             | 8         | 8      | 8.42%   |
| Crucial             | 7         | 7      | 7.37%   |
| A-DATA Technology   | 5         | 8      | 5.26%   |
| WDC                 | 4         | 4      | 4.21%   |
| PNY                 | 4         | 4      | 4.21%   |
| China               | 4         | 5      | 4.21%   |
| Transcend           | 3         | 3      | 3.16%   |
| SPCC                | 3         | 3      | 3.16%   |
| Micron Technology   | 3         | 3      | 3.16%   |
| TO Exter            | 2         | 2      | 2.11%   |
| SK hynix            | 2         | 2      | 2.11%   |
| LITEON              | 2         | 2      | 2.11%   |
| Intel               | 2         | 2      | 2.11%   |
| FORESEE             | 2         | 3      | 2.11%   |
| Apacer              | 2         | 2      | 2.11%   |
| Team                | 1         | 2      | 1.05%   |
| SSSTC               | 1         | 1      | 1.05%   |
| Patriot             | 1         | 1      | 1.05%   |
| Netac               | 1         | 1      | 1.05%   |
| LITEONIT            | 1         | 1      | 1.05%   |
| Kimtigo             | 1         | 1      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| INNOVATION IT       | 1         | 1      | 1.05%   |
| EVM                 | 1         | 1      | 1.05%   |
| ASMT                | 1         | 2      | 1.05%   |
| addlink             | 1         | 1      | 1.05%   |
| Unknown             | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 87        | 107    | 32.1%   |
| NVMe    | 77        | 81     | 28.41%  |
| HDD     | 75        | 86     | 27.68%  |
| MMC     | 31        | 35     | 11.44%  |
| Unknown | 1         | 1      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 150       | 179    | 55.56%  |
| NVMe | 77        | 81     | 28.52%  |
| MMC  | 31        | 35     | 11.48%  |
| SAS  | 12        | 15     | 4.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 134    | 67.66%  |
| 0.51-1.0   | 45        | 48     | 26.95%  |
| 1.01-2.0   | 7         | 9      | 4.19%   |
| 3.01-4.0   | 2         | 2      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 30.71%  |
| 251-500        | 66        | 27.39%  |
| 501-1000       | 31        | 12.86%  |
| 51-100         | 22        | 9.13%   |
| 1-20           | 19        | 7.88%   |
| 21-50          | 12        | 4.98%   |
| 1001-2000      | 12        | 4.98%   |
| More than 3000 | 3         | 1.24%   |
| 2001-3000      | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 102       | 42.15%  |
| 21-50          | 51        | 21.07%  |
| 101-250        | 35        | 14.46%  |
| 51-100         | 31        | 12.81%  |
| 251-500        | 11        | 4.55%   |
| 501-1000       | 7         | 2.89%   |
| 1001-2000      | 2         | 0.83%   |
| More than 3000 | 1         | 0.41%   |
| 2001-3000      | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 6.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 3.33%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 3.33%   |
| Toshiba MK1246GSX 120GB                          | 1         | 1      | 3.33%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 3.33%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 3.33%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.33%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 3.33%   |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 3.33%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 3.33%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.33%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 3.33%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 3.33%   |
| JMicron Technology Generic 1TB                   | 1         | 1      | 3.33%   |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 1      | 3.33%   |
| Hitachi HTS545032A7E380 320GB                    | 1         | 1      | 3.33%   |
| Hitachi HTS543216L9A300 160GB                    | 1         | 1      | 3.33%   |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 3.33%   |
| Hitachi HTS541080G9SA00 80GB                     | 1         | 1      | 3.33%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 3.33%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 3.33%   |
| Fujitsu MHZ2250BH G2 250GB                       | 1         | 1      | 3.33%   |
| Fujitsu MHZ2160BJ FFS G2 160GB                   | 1         | 1      | 3.33%   |
| Fujitsu MHW2060BH 64GB                           | 1         | 1      | 3.33%   |
| Unknown                                          | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 30%     |
| Hitachi             | 5         | 5      | 16.67%  |
| Fujitsu             | 3         | 3      | 10%     |
| WDC                 | 2         | 2      | 6.67%   |
| HGST                | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 3.33%   |
| SSSTC               | 1         | 1      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| Kingston            | 1         | 2      | 3.33%   |
| JMicron Technology  | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Unknown             | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 9         | 9      | 40.91%  |
| Hitachi            | 5         | 5      | 22.73%  |
| Fujitsu            | 3         | 3      | 13.64%  |
| HGST               | 2         | 2      | 9.09%   |
| WDC                | 1         | 1      | 4.55%   |
| Toshiba            | 1         | 1      | 4.55%   |
| JMicron Technology | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 22     | 72.41%  |
| SSD  | 8         | 9      | 27.59%  |

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
| Works    | 124       | 140    | 48.82%  |
| Detected | 101       | 139    | 39.76%  |
| Malfunc  | 29        | 31     | 11.42%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 158       | 60.08%  |
| AMD                          | 36        | 13.69%  |
| Samsung Electronics          | 27        | 10.27%  |
| SK hynix                     | 12        | 4.56%   |
| SanDisk                      | 12        | 4.56%   |
| Kingston Technology Company  | 4         | 1.52%   |
| Silicon Motion               | 3         | 1.14%   |
| Phison Electronics           | 3         | 1.14%   |
| Micron Technology            | 2         | 0.76%   |
| Union Memory (Shenzhen)      | 1         | 0.38%   |
| Toshiba America Info Systems | 1         | 0.38%   |
| Realtek Semiconductor        | 1         | 0.38%   |
| Micron/Crucial Technology    | 1         | 0.38%   |
| Lenovo                       | 1         | 0.38%   |
| Apple                        | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 33        | 11.66%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 6.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 5.3%    |
| Samsung NVMe SSD Controller 980                                                  | 14        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 3.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 3.53%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 3.18%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 8         | 2.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 2.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 2.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 2.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 1.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.41%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.41%   |
| Intel SSD 660P Series                                                            | 4         | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 1.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 1.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.06%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.71%   |
| Micron NVMe Storage Controller                                                   | 2         | 0.71%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.71%   |
| Intel Non-Volatile memory controller                                             | 2         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 170       | 60.93%  |
| NVMe | 77        | 27.6%   |
| RAID | 16        | 5.73%   |
| IDE  | 16        | 5.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 188       | 78.99%  |
| AMD    | 50        | 21.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics      | 6         | 2.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 2.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 2.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 1.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 1.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 1.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.68%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 1.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 1.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.26%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 1.26%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 1.26%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.26%   |
| Intel 12th Gen Core i7-1260P                | 3         | 1.26%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 1.26%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 1.26%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 3         | 1.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.84%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 0.84%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.84%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 2         | 0.84%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 0.84%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz        | 2         | 0.84%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.84%   |
| Intel Celeron 3205U @ 1.50GHz               | 2         | 0.84%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 2         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 20.17%  |
| Intel Celeron           | 35        | 14.71%  |
| Intel Core i7           | 28        | 11.76%  |
| Other                   | 24        | 10.08%  |
| Intel Core i3           | 18        | 7.56%   |
| Intel Core 2 Duo        | 12        | 5.04%   |
| AMD Ryzen 5             | 11        | 4.62%   |
| AMD Ryzen 7             | 8         | 3.36%   |
| Intel Atom              | 5         | 2.1%    |
| AMD A8                  | 5         | 2.1%    |
| AMD A6                  | 5         | 2.1%    |
| Intel Pentium           | 4         | 1.68%   |
| Intel Pentium Dual      | 3         | 1.26%   |
| Intel Genuine           | 3         | 1.26%   |
| Intel Core 2            | 3         | 1.26%   |
| AMD Ryzen 5 PRO         | 3         | 1.26%   |
| AMD E1                  | 3         | 1.26%   |
| Intel Pentium Dual-Core | 2         | 0.84%   |
| AMD Ryzen 7 PRO         | 2         | 0.84%   |
| AMD Ryzen 3             | 2         | 0.84%   |
| AMD E2                  | 2         | 0.84%   |
| AMD A4                  | 2         | 0.84%   |
| AMD A10                 | 2         | 0.84%   |
| Intel Xeon              | 1         | 0.42%   |
| Intel Pentium Silver    | 1         | 0.42%   |
| Intel Core m3           | 1         | 0.42%   |
| Intel Core 2 Extreme    | 1         | 0.42%   |
| AMD Ryzen 9             | 1         | 0.42%   |
| AMD FX                  | 1         | 0.42%   |
| AMD E                   | 1         | 0.42%   |
| AMD Athlon              | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 141       | 59.24%  |
| 4      | 58        | 24.37%  |
| 6      | 18        | 7.56%   |
| 8      | 13        | 5.46%   |
| 12     | 4         | 1.68%   |
| 1      | 3         | 1.26%   |
| 10     | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 238       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 153       | 64.29%  |
| 1      | 85        | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 238       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 33.75%  |
| 0x806c1    | 14        | 5.83%   |
| 0x406e3    | 11        | 4.58%   |
| 0x306d4    | 7         | 2.92%   |
| 0x08608103 | 7         | 2.92%   |
| 0x306a9    | 6         | 2.5%    |
| 0x806ec    | 5         | 2.08%   |
| 0x706a8    | 5         | 2.08%   |
| 0x30678    | 5         | 2.08%   |
| 0x1067a    | 5         | 2.08%   |
| 0xa0652    | 4         | 1.67%   |
| 0x6fd      | 4         | 1.67%   |
| 0x406c4    | 4         | 1.67%   |
| 0x406c3    | 4         | 1.67%   |
| 0x206a7    | 4         | 1.67%   |
| 0x20655    | 4         | 1.67%   |
| 0x07030105 | 4         | 1.67%   |
| 0x906ea    | 3         | 1.25%   |
| 0x806ea    | 3         | 1.25%   |
| 0x806e9    | 3         | 1.25%   |
| 0x6fb      | 3         | 1.25%   |
| 0x506c9    | 3         | 1.25%   |
| 0x40651    | 3         | 1.25%   |
| 0x05000119 | 3         | 1.25%   |
| 0x906a3    | 2         | 0.83%   |
| 0x806d1    | 2         | 0.83%   |
| 0x6f6      | 2         | 0.83%   |
| 0x506ca    | 2         | 0.83%   |
| 0x20652    | 2         | 0.83%   |
| 0x10676    | 2         | 0.83%   |
| 0x0a50000d | 2         | 0.83%   |
| 0x0a50000c | 2         | 0.83%   |
| 0x08608102 | 2         | 0.83%   |
| 0x08600104 | 2         | 0.83%   |
| 0x08108109 | 2         | 0.83%   |
| 0x06006705 | 2         | 0.83%   |
| 0x906e9    | 1         | 0.42%   |
| 0x906c0    | 1         | 0.42%   |
| 0x906a4    | 1         | 0.42%   |
| 0x706e5    | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 10.5%   |
| Skylake          | 19        | 7.98%   |
| Silvermont       | 17        | 7.14%   |
| TigerLake        | 16        | 6.72%   |
| SandyBridge      | 15        | 6.3%    |
| Unknown          | 15        | 6.3%    |
| Penryn           | 14        | 5.88%   |
| IvyBridge        | 12        | 5.04%   |
| Core             | 11        | 4.62%   |
| Westmere         | 9         | 3.78%   |
| Haswell          | 9         | 3.78%   |
| Broadwell        | 9         | 3.78%   |
| Goldmont plus    | 8         | 3.36%   |
| Puma             | 7         | 2.94%   |
| Zen 3            | 6         | 2.52%   |
| Goldmont         | 6         | 2.52%   |
| Zen 2            | 5         | 2.1%    |
| Excavator        | 5         | 2.1%    |
| CometLake        | 5         | 2.1%    |
| Zen+             | 4         | 1.68%   |
| IceLake          | 4         | 1.68%   |
| Bobcat           | 4         | 1.68%   |
| Alderlake Hybrid | 3         | 1.26%   |
| Steamroller      | 2         | 0.84%   |
| Piledriver       | 2         | 0.84%   |
| K10 Llano        | 2         | 0.84%   |
| Bonnell          | 2         | 0.84%   |
| Tremont          | 1         | 0.42%   |
| Nehalem          | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 170       | 61.59%  |
| AMD    | 59        | 21.38%  |
| Nvidia | 47        | 17.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 5.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 4.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 4.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 3.13%   |
| AMD Lucienne                                                                             | 9         | 3.13%   |
| Intel HD Graphics 620                                                                    | 7         | 2.43%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.43%   |
| Intel HD Graphics 500                                                                    | 6         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.74%   |
| AMD Renoir                                                                               | 5         | 1.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 1.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 1.39%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.39%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.39%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.04%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.04%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.04%   |
| Nvidia TU117M                                                                            | 2         | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.69%   |
| Intel HD Graphics 530                                                                    | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 136       | 57.14%  |
| 1 x AMD        | 44        | 18.49%  |
| Intel + Nvidia | 29        | 12.18%  |
| 1 x Nvidia     | 13        | 5.46%   |
| 2 x AMD        | 6         | 2.52%   |
| AMD + Nvidia   | 5         | 2.1%    |
| Intel + AMD    | 4         | 1.68%   |
| Other          | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 211       | 88.66%  |
| Proprietary | 22        | 9.24%   |
| Unknown     | 5         | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 174       | 72.5%   |
| 0.01-0.5   | 34        | 14.17%  |
| 0.51-1.0   | 13        | 5.42%   |
| 1.01-2.0   | 9         | 3.75%   |
| 3.01-4.0   | 8         | 3.33%   |
| 7.01-8.0   | 1         | 0.42%   |
| 5.01-6.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 23.28%  |
| BOE                     | 40        | 15.27%  |
| LG Display              | 39        | 14.89%  |
| Chimei Innolux          | 32        | 12.21%  |
| Samsung Electronics     | 21        | 8.02%   |
| Dell                    | 8         | 3.05%   |
| Chi Mei Optoelectronics | 7         | 2.67%   |
| Lenovo                  | 6         | 2.29%   |
| PANDA                   | 5         | 1.91%   |
| LG Philips              | 4         | 1.53%   |
| InfoVision              | 4         | 1.53%   |
| Goldstar                | 4         | 1.53%   |
| Apple                   | 3         | 1.15%   |
| Vizio                   | 2         | 0.76%   |
| Sony                    | 2         | 0.76%   |
| Sharp                   | 2         | 0.76%   |
| Philips                 | 2         | 0.76%   |
| KDC                     | 2         | 0.76%   |
| Iiyama                  | 2         | 0.76%   |
| Acer                    | 2         | 0.76%   |
| ViewSonic               | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| Sceptre Tech            | 1         | 0.38%   |
| SAC                     | 1         | 0.38%   |
| Quanta Display          | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| Olevia                  | 1         | 0.38%   |
| Hewlett-Packard         | 1         | 0.38%   |
| HannStar                | 1         | 0.38%   |
| CSO                     | 1         | 0.38%   |
| CPT                     | 1         | 0.38%   |
| BenQ                    | 1         | 0.38%   |
| AOC                     | 1         | 0.38%   |
| ADI                     | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.14%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 3         | 1.14%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 2         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.76%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.76%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.76%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 2         | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.76%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch         | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.76%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.76%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.76%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.76%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.38%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                       | 1         | 0.38%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.38%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.38%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                  | 1         | 0.38%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.38%   |
| Samsung Electronics U28E570 SAM0D70 3840x2160 608x345mm 27.5-inch        | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch     | 1         | 0.38%   |
| Samsung Electronics SMC23A550U SAM07F3 1920x1080 510x287mm 23.0-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch     | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 104       | 41.6%   |
| 1366x768 (WXGA)    | 76        | 30.4%   |
| 1600x900 (HD+)     | 21        | 8.4%    |
| 1280x800 (WXGA)    | 13        | 5.2%    |
| 1920x1200 (WUXGA)  | 9         | 3.6%    |
| 3840x2160 (4K)     | 7         | 2.8%    |
| 1440x900 (WXGA+)   | 6         | 2.4%    |
| 2560x1440 (QHD)    | 2         | 0.8%    |
| 1280x1024 (SXGA)   | 2         | 0.8%    |
| 1024x600           | 2         | 0.8%    |
| 3440x1440          | 1         | 0.4%    |
| 2880x1800          | 1         | 0.4%    |
| 2160x1440          | 1         | 0.4%    |
| 1920x515           | 1         | 0.4%    |
| 1680x1050 (WSXGA+) | 1         | 0.4%    |
| 1366x912           | 1         | 0.4%    |
| 1360x768           | 1         | 0.4%    |
| 1024x768 (XGA)     | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 101       | 38.55%  |
| 14      | 43        | 16.41%  |
| 13      | 37        | 14.12%  |
| 17      | 21        | 8.02%   |
| 11      | 10        | 3.82%   |
| 27      | 9         | 3.44%   |
| 12      | 8         | 3.05%   |
| 23      | 7         | 2.67%   |
| 24      | 4         | 1.53%   |
| 21      | 4         | 1.53%   |
| 16      | 4         | 1.53%   |
| Unknown | 4         | 1.53%   |
| 26      | 2         | 0.76%   |
| 18      | 2         | 0.76%   |
| 10      | 2         | 0.76%   |
| 42      | 1         | 0.38%   |
| 34      | 1         | 0.38%   |
| 31      | 1         | 0.38%   |
| 20      | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 167       | 64.23%  |
| 201-300     | 36        | 13.85%  |
| 351-400     | 22        | 8.46%   |
| 501-600     | 19        | 7.31%   |
| 401-500     | 7         | 2.69%   |
| Unknown     | 4         | 1.54%   |
| 601-700     | 3         | 1.15%   |
| 701-800     | 1         | 0.38%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 201       | 84.1%   |
| 16/10   | 29        | 12.13%  |
| 3/2     | 3         | 1.26%   |
| 4/3     | 2         | 0.84%   |
| 6/5     | 1         | 0.42%   |
| 3.73    | 1         | 0.42%   |
| 21/9    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 100       | 38.31%  |
| 81-90          | 67        | 25.67%  |
| 121-130        | 15        | 5.75%   |
| 71-80          | 13        | 4.98%   |
| 201-250        | 13        | 4.98%   |
| 51-60          | 10        | 3.83%   |
| 301-350        | 10        | 3.83%   |
| 61-70          | 7         | 2.68%   |
| 131-140        | 7         | 2.68%   |
| Unknown        | 4         | 1.53%   |
| 151-200        | 3         | 1.15%   |
| 351-500        | 2         | 0.77%   |
| 41-50          | 2         | 0.77%   |
| 251-300        | 2         | 0.77%   |
| 111-120        | 2         | 0.77%   |
| 91-100         | 2         | 0.77%   |
| 141-150        | 1         | 0.38%   |
| 501-1000       | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 119       | 46.12%  |
| 101-120       | 80        | 31.01%  |
| 51-100        | 41        | 15.89%  |
| 161-240       | 11        | 4.26%   |
| Unknown       | 4         | 1.55%   |
| More than 240 | 3         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 199       | 83.61%  |
| 2     | 31        | 13.03%  |
| 0     | 5         | 2.1%    |
| 3     | 3         | 1.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 126       | 34.62%  |
| Intel                             | 123       | 33.79%  |
| Qualcomm Atheros                  | 45        | 12.36%  |
| Broadcom                          | 24        | 6.59%   |
| MediaTek                          | 7         | 1.92%   |
| Sierra Wireless                   | 4         | 1.1%    |
| Qualcomm                          | 4         | 1.1%    |
| Dell                              | 4         | 1.1%    |
| Marvell Technology Group          | 3         | 0.82%   |
| TP-Link                           | 2         | 0.55%   |
| Samsung Electronics               | 2         | 0.55%   |
| Ralink                            | 2         | 0.55%   |
| Huawei Technologies               | 2         | 0.55%   |
| Hewlett-Packard                   | 2         | 0.55%   |
| Broadcom Limited                  | 2         | 0.55%   |
| Xiaomi                            | 1         | 0.27%   |
| Ralink Technology                 | 1         | 0.27%   |
| Qualcomm Atheros Communications   | 1         | 0.27%   |
| OPPO Electronics                  | 1         | 0.27%   |
| Microchip Technology              | 1         | 0.27%   |
| LG Electronics                    | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| BUFFALO                           | 1         | 0.27%   |
| Attansic Technology               | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |
| Apple                             | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 74        | 16.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 5.53%   |
| Intel Wireless 8260                                                     | 14        | 3.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.21%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.77%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.77%   |
| Intel Ethernet Connection I219-LM                                       | 8         | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.55%   |
| Intel Wireless 7260                                                     | 7         | 1.55%   |
| Intel Wireless 7265                                                     | 6         | 1.33%   |
| Intel Wireless 3165                                                     | 6         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.11%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                            | 4         | 0.88%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 4         | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.88%   |
| Sierra Wireless EM7455                                                  | 3         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 121       | 48.21%  |
| Realtek Semiconductor           | 48        | 19.12%  |
| Qualcomm Atheros                | 41        | 16.33%  |
| Broadcom                        | 16        | 6.37%   |
| MediaTek                        | 7         | 2.79%   |
| Sierra Wireless                 | 4         | 1.59%   |
| Qualcomm                        | 4         | 1.59%   |
| Ralink                          | 2         | 0.8%    |
| Dell                            | 2         | 0.8%    |
| TP-Link                         | 1         | 0.4%    |
| Ralink Technology               | 1         | 0.4%    |
| Qualcomm Atheros Communications | 1         | 0.4%    |
| D-Link                          | 1         | 0.4%    |
| BUFFALO                         | 1         | 0.4%    |
| Broadcom Limited                | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 14        | 5.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 4.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.91%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.73%   |
| Intel Wireless 7260                                                     | 7         | 2.73%   |
| Intel Wireless 7265                                                     | 6         | 2.34%   |
| Intel Wireless 3165                                                     | 6         | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.95%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.95%   |
| Realtek 802.11n WLAN Adapter                                            | 4         | 1.56%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 1.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.56%   |
| Sierra Wireless EM7455                                                  | 3         | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.17%   |
| Intel Wireless 3160                                                     | 3         | 1.17%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 1.17%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.17%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.17%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 104       | 54.45%  |
| Intel                    | 50        | 26.18%  |
| Qualcomm Atheros         | 10        | 5.24%   |
| Broadcom                 | 10        | 5.24%   |
| Marvell Technology Group | 3         | 1.57%   |
| Huawei Technologies      | 2         | 1.05%   |
| Hewlett-Packard          | 2         | 1.05%   |
| Xiaomi                   | 1         | 0.52%   |
| TP-Link                  | 1         | 0.52%   |
| Samsung Electronics      | 1         | 0.52%   |
| OPPO Electronics         | 1         | 0.52%   |
| Microchip Technology     | 1         | 0.52%   |
| LG Electronics           | 1         | 0.52%   |
| Broadcom Limited         | 1         | 0.52%   |
| Attansic Technology      | 1         | 0.52%   |
| ASIX Electronics         | 1         | 0.52%   |
| Apple                    | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 74        | 38.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 13.02%  |
| Intel Ethernet Connection I219-LM                                              | 8         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 2.08%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.56%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 1.56%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.56%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.04%   |
| Intel Ethernet Connection (16) I219-V                                          | 2         | 1.04%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 1.04%   |
| Huawei ATU-L21                                                                 | 2         | 1.04%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 1.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.52%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                           | 1         | 0.52%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.52%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.52%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.52%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.52%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 235       | 55.42%  |
| Ethernet | 185       | 43.63%  |
| Modem    | 4         | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 81.75%  |
| Ethernet | 46        | 18.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 174       | 73.11%  |
| 1     | 56        | 23.53%  |
| 0     | 8         | 3.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 157       | 65.42%  |
| Yes  | 83        | 34.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 46.56%  |
| Realtek Semiconductor           | 25        | 13.23%  |
| Broadcom                        | 16        | 8.47%   |
| Qualcomm Atheros Communications | 11        | 5.82%   |
| Foxconn / Hon Hai               | 11        | 5.82%   |
| Lite-On Technology              | 9         | 4.76%   |
| IMC Networks                    | 9         | 4.76%   |
| Hewlett-Packard                 | 4         | 2.12%   |
| Realtek                         | 3         | 1.59%   |
| Dell                            | 2         | 1.06%   |
| ASUSTek Computer                | 2         | 1.06%   |
| Apple                           | 2         | 1.06%   |
| USI                             | 1         | 0.53%   |
| Toshiba                         | 1         | 0.53%   |
| Ralink                          | 1         | 0.53%   |
| Foxconn International           | 1         | 0.53%   |
| Chicony Electronics             | 1         | 0.53%   |
| Cambridge Silicon Radio         | 1         | 0.53%   |
| Alps Electric                   | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 41        | 21.69%  |
| Realtek Bluetooth Radio                                                             | 18        | 9.52%   |
| Intel AX201 Bluetooth                                                               | 17        | 8.99%   |
| Intel AX200 Bluetooth                                                               | 8         | 4.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 3.17%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 3.17%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.65%   |
| Intel AX210 Bluetooth                                                               | 5         | 2.65%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.12%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.12%   |
| Intel Bluetooth Device                                                              | 4         | 2.12%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.12%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.59%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.59%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.06%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.06%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.06%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 1.06%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.06%   |
| USI Bluetooth Device                                                                | 1         | 0.53%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.53%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.53%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.53%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.53%   |
| Lite-On Wireless_Device                                                             | 1         | 0.53%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.53%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.53%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.53%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.53%   |
| IMC Networks Internal Bluetooth                                                     | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 185       | 68.52%  |
| AMD                    | 51        | 18.89%  |
| Nvidia                 | 20        | 7.41%   |
| Texas Instruments      | 3         | 1.11%   |
| JMTek                  | 2         | 0.74%   |
| Generalplus Technology | 2         | 0.74%   |
| C-Media Electronics    | 2         | 0.74%   |
| ASUSTek Computer       | 2         | 0.74%   |
| Tenx Technology        | 1         | 0.37%   |
| GN Netcom              | 1         | 0.37%   |
| Conexant Systems       | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 8.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 6.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 5.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 4.8%    |
| AMD FCH Azalia Controller                                                                         | 16        | 4.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 4.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 3%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.7%    |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.8%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.5%    |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.9%    |
| Nvidia Audio device                                                                               | 3         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 3         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.6%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.6%    |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 61        | 29.76%  |
| SK hynix                   | 36        | 17.56%  |
| Unknown                    | 26        | 12.68%  |
| Micron Technology          | 23        | 11.22%  |
| Kingston                   | 17        | 8.29%   |
| Crucial                    | 12        | 5.85%   |
| Unknown (ABCD)             | 7         | 3.41%   |
| Ramaxel Technology         | 6         | 2.93%   |
| Transcend                  | 2         | 0.98%   |
| G.Skill                    | 2         | 0.98%   |
| Elpida                     | 2         | 0.98%   |
| V-Color                    | 1         | 0.49%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.49%   |
| Smart                      | 1         | 0.49%   |
| Qimonda                    | 1         | 0.49%   |
| Nanya Technology           | 1         | 0.49%   |
| Foxline                    | 1         | 0.49%   |
| fef5                       | 1         | 0.49%   |
| Essencore                  | 1         | 0.49%   |
| Daten Tecnologia           | 1         | 0.49%   |
| Avant                      | 1         | 0.49%   |
| A-DATA Technology          | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 7         | 3.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.89%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 3         | 1.42%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.42%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.94%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.94%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 2         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.94%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.94%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.94%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.94%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.94%   |
| V-Color RAM TN416G26D819-SB 16GB SODIMM DDR4 2667MT/s            | 1         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 70        | 40%     |
| DDR3    | 55        | 31.43%  |
| LPDDR4  | 20        | 11.43%  |
| DDR2    | 13        | 7.43%   |
| LPDDR3  | 5         | 2.86%   |
| SDRAM   | 4         | 2.29%   |
| LPDDR5  | 3         | 1.71%   |
| DDR5    | 2         | 1.14%   |
| Unknown | 2         | 1.14%   |
| DDR     | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 149       | 84.66%  |
| Row Of Chips | 20        | 11.36%  |
| Unknown      | 4         | 2.27%   |
| Chip         | 3         | 1.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 61        | 32.62%  |
| 4096  | 58        | 31.02%  |
| 2048  | 34        | 18.18%  |
| 16384 | 23        | 12.3%   |
| 1024  | 7         | 3.74%   |
| 32768 | 2         | 1.07%   |
| 1536  | 1         | 0.53%   |
| 512   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 40        | 21.98%  |
| 3200    | 39        | 21.43%  |
| 2667    | 20        | 10.99%  |
| 2400    | 17        | 9.34%   |
| 2133    | 11        | 6.04%   |
| 667     | 10        | 5.49%   |
| 1334    | 7         | 3.85%   |
| 4267    | 6         | 3.3%    |
| 1333    | 4         | 2.2%    |
| 6400    | 2         | 1.1%    |
| 4800    | 2         | 1.1%    |
| 4266    | 2         | 1.1%    |
| 4199    | 2         | 1.1%    |
| 3266    | 2         | 1.1%    |
| 2048    | 2         | 1.1%    |
| 1867    | 2         | 1.1%    |
| 1067    | 2         | 1.1%    |
| 975     | 2         | 1.1%    |
| 533     | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |
| 5500    | 1         | 0.55%   |
| 3733    | 1         | 0.55%   |
| 2134    | 1         | 0.55%   |
| 1776    | 1         | 0.55%   |
| 1066    | 1         | 0.55%   |
| 800     | 1         | 0.55%   |

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
| Chicony Electronics                    | 63        | 28.51%  |
| Realtek Semiconductor                  | 17        | 7.69%   |
| Quanta                                 | 17        | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 7.24%   |
| IMC Networks                           | 15        | 6.79%   |
| Suyin                                  | 14        | 6.33%   |
| Sunplus Innovation Technology          | 14        | 6.33%   |
| Microdia                               | 13        | 5.88%   |
| Luxvisions Innotech Limited            | 5         | 2.26%   |
| Acer                                   | 5         | 2.26%   |
| Syntek                                 | 4         | 1.81%   |
| Bison Electronics                      | 4         | 1.81%   |
| Logitech                               | 3         | 1.36%   |
| Lite-On Technology                     | 3         | 1.36%   |
| Alcor Micro                            | 3         | 1.36%   |
| Z-Star Microelectronics                | 2         | 0.9%    |
| USB Camera CS                          | 2         | 0.9%    |
| Sonix Technology                       | 2         | 0.9%    |
| Silicon Motion                         | 2         | 0.9%    |
| Ricoh                                  | 2         | 0.9%    |
| Lenovo                                 | 2         | 0.9%    |
| icSpring                               | 2         | 0.9%    |
| Xiongmai                               | 1         | 0.45%   |
| ValueHD                                | 1         | 0.45%   |
| SunplusIT                              | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| OYT Tech                               | 1         | 0.45%   |
| OmniVision Technologies                | 1         | 0.45%   |
| MacroSilicon                           | 1         | 0.45%   |
| Importek                               | 1         | 0.45%   |
| Apple                                  | 1         | 0.45%   |
| Alpha Imaging Technology               | 1         | 0.45%   |
| Unknown                                | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 22        | 9.91%   |
| Chicony HD Webcam                                   | 6         | 2.7%    |
| Sunplus Integrated_Webcam_HD                        | 5         | 2.25%   |
| Quanta HD User Facing                               | 5         | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 2.25%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 1.8%    |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 1.35%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.35%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 1.35%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.35%   |
| IMC Networks Integrated Camera                      | 3         | 1.35%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.35%   |
| Chicony EasyCamera                                  | 3         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.35%   |
| USB Camera CS USB Camera CS                         | 2         | 0.9%    |
| Syntek Integrated Camera                            | 2         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.9%    |
| Sunplus Integrated_Webcam_FHD                       | 2         | 0.9%    |
| Sunplus HD WebCam                                   | 2         | 0.9%    |
| Realtek USB Camera                                  | 2         | 0.9%    |
| Realtek Lenovo EasyCamera                           | 2         | 0.9%    |
| Realtek HP Truevision HD                            | 2         | 0.9%    |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 0.9%    |
| Quanta HP Webcam                                    | 2         | 0.9%    |
| Microdia Sonix USB 2.0 Camera                       | 2         | 0.9%    |
| Microdia Lenovo EasyCamera                          | 2         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.9%    |
| Logitech C922 Pro Stream Webcam                     | 2         | 0.9%    |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.9%    |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.9%    |
| IMC Networks HD Camera                              | 2         | 0.9%    |
| icSpring camera                                     | 2         | 0.9%    |
| Chicony VGA Webcam                                  | 2         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.9%    |
| Chicony USB2.0 Camera                               | 2         | 0.9%    |
| Chicony Integrated Camera [ThinkPad]                | 2         | 0.9%    |
| Chicony HP TrueVision HD Camera                     | 2         | 0.9%    |
| Chicony HP Truevision HD                            | 2         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 33.33%  |
| Shenzhen Goodix Technology | 7         | 17.95%  |
| Upek                       | 6         | 15.38%  |
| Synaptics                  | 6         | 15.38%  |
| STMicroelectronics         | 2         | 5.13%   |
| Elan Microelectronics      | 2         | 5.13%   |
| AuthenTec                  | 2         | 5.13%   |
| Focal-systems.Corp         | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 7         | 17.95%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 5         | 12.82%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 12.82%  |
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 7.69%   |
| Validity Sensors Synaptics WBDI                        | 3         | 7.69%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 5.13%   |
| Synaptics UWP WBDI Device                              | 2         | 5.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 5.13%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 5.13%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 2.56%   |
| Synaptics  WBDI                                        | 1         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.56%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.56%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.56%   |
| Elan ELAN:ARM-M4                                       | 1         | 2.56%   |
| AuthenTec AES2810                                      | 1         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 39.13%  |
| Alcor Micro | 9         | 39.13%  |
| Lenovo      | 3         | 13.04%  |
| O2 Micro    | 2         | 8.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 39.13%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 13.04%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 13.04%  |
| Broadcom 5880                                                                | 3         | 13.04%  |
| Broadcom 58200                                                               | 2         | 8.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 150       | 62.76%  |
| 1     | 70        | 29.29%  |
| 2     | 15        | 6.28%   |
| 3     | 4         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 33.94%  |
| Chipcard                 | 22        | 20.18%  |
| Graphics card            | 13        | 11.93%  |
| Camera                   | 11        | 10.09%  |
| Net/wireless             | 8         | 7.34%   |
| Bluetooth                | 5         | 4.59%   |
| Card reader              | 4         | 3.67%   |
| Network                  | 3         | 2.75%   |
| Storage                  | 2         | 1.83%   |
| Communication controller | 2         | 1.83%   |
| Net/ethernet             | 1         | 0.92%   |
| Multimedia controller    | 1         | 0.92%   |

