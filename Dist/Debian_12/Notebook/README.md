Debian 12 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 12.

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

Total: 389

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | G3 3590                     | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| ASUSTek       | K52F                        | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| Dell          | Latitude 3500               | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| Aquarius      | NS585                       | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Aquarius      | NS585                       | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Dell          | Latitude E6430              | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASUSTek       | X45U                        | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Apple         | MacBookPro10,1              | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| HP            | EliteBook 8440p             | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude E6400              | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| Unknown       | Unknown                     | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| Dell          | XPS M1530                   | [252d777fa0](https://linux-hardware.org/?probe=252d777fa0) | Jun 14, 2023 |
| Acer          | TravelMate 5742Z            | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| HP            | Pavilion Notebook           | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Samsung       | 750XED                      | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| Dell          | Inspiron 5515               | [9ac2f1ed7e](https://linux-hardware.org/?probe=9ac2f1ed7e) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | G565 4385                   | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| Dell          | Latitude 5480               | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| HP            | G62                         | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Aquarius      | NS585                       | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| Aquarius      | NS585                       | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Aquarius      | NS585                       | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| Apple         | MacBookPro16,1              | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Acer          | Aspire A315-58              | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| HP            | EliteBook 735 G6            | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| Acer          | Aspire A515-56              | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Aquarius      | NS585                       | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| Dell          | Latitude 3520               | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| eMachines     | E725                        | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| Aquarius      | NS585                       | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| Acer          | Nitro AN515-45              | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| Terrans Fo... | AMD                         | [8087d42d0e](https://linux-hardware.org/?probe=8087d42d0e) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Acer          | Aspire 5253                 | [f28727e594](https://linux-hardware.org/?probe=f28727e594) | May 21, 2023 |
| Acer          | Aspire 5739G                | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Acer          | Aspire 5739G                | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| Acer          | Aspire 5253                 | [fa328bbd9c](https://linux-hardware.org/?probe=fa328bbd9c) | May 19, 2023 |
| Avell High... | A40 LIV                     | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Toshiba       | Satellite C855-22N          | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| Aquarius      | NS585                       | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| Acer          | TravelMate X514-51          | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| Dell          | Precision 5520              | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Dell          | XPS 15 9560                 | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| Avell High... | A40 LIV                     | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [1f874eaf6d](https://linux-hardware.org/?probe=1f874eaf6d) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Avell High... | A40 LIV                     | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| Aquarius      | NS585                       | [817d9a6b62](https://linux-hardware.org/?probe=817d9a6b62) | May 04, 2023 |
| Aquarius      | NS585                       | [c629501448](https://linux-hardware.org/?probe=c629501448) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| MSI           | Unknown                     | [917d7a7fc9](https://linux-hardware.org/?probe=917d7a7fc9) | May 03, 2023 |
| HP            | OMEN by Laptop              | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| Aquarius      | NS585                       | [e6922e974c](https://linux-hardware.org/?probe=e6922e974c) | May 02, 2023 |
| Toshiba       | Satellite X200              | [e1674b1234](https://linux-hardware.org/?probe=e1674b1234) | May 02, 2023 |
| Sony          | VPCF13WFX                   | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| Aquarius      | NS585                       | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
| Aquarius      | NS585                       | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| Aquarius      | NS585                       | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Aquarius      | NS585                       | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| HP            | ProBook 4520s               | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Dell          | G15 5520                    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [8a1e6b7f32](https://linux-hardware.org/?probe=8a1e6b7f32) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [036616c992](https://linux-hardware.org/?probe=036616c992) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [cb40e046d8](https://linux-hardware.org/?probe=cb40e046d8) | Apr 21, 2023 |
| Toshiba       | Satellite X200              | [15035835d0](https://linux-hardware.org/?probe=15035835d0) | Apr 20, 2023 |
| HP            | Notebook                    | [7174065ed3](https://linux-hardware.org/?probe=7174065ed3) | Apr 20, 2023 |
| Aquarius      | NS585                       | [753222f54f](https://linux-hardware.org/?probe=753222f54f) | Apr 20, 2023 |
| Aquarius      | NS585                       | [be0bc2be01](https://linux-hardware.org/?probe=be0bc2be01) | Apr 20, 2023 |
| HP            | EliteBook 830 G5            | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| Aquarius      | NS585                       | [f7f0464c39](https://linux-hardware.org/?probe=f7f0464c39) | Apr 20, 2023 |
| Aquarius      | NS585                       | [8393642230](https://linux-hardware.org/?probe=8393642230) | Apr 20, 2023 |
| Aquarius      | NS585                       | [a5b9a09e63](https://linux-hardware.org/?probe=a5b9a09e63) | Apr 20, 2023 |
| Medion        | P17605                      | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d669bcc680](https://linux-hardware.org/?probe=d669bcc680) | Apr 19, 2023 |
| Tactus        | GeoBook 140                 | [704da241f5](https://linux-hardware.org/?probe=704da241f5) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [7f0be1868e](https://linux-hardware.org/?probe=7f0be1868e) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| ASUSTek       | G551JW                      | [65f6143e36](https://linux-hardware.org/?probe=65f6143e36) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [180ef53338](https://linux-hardware.org/?probe=180ef53338) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [fd3b20c292](https://linux-hardware.org/?probe=fd3b20c292) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| IBM           | ThinkPad R51 1836Q4U        | [ebec8b53eb](https://linux-hardware.org/?probe=ebec8b53eb) | Apr 18, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Dell          | XPS 13 9305                 | [838519057f](https://linux-hardware.org/?probe=838519057f) | Apr 16, 2023 |
| HP            | 255 G8 Notebook PC          | [58ec498e8f](https://linux-hardware.org/?probe=58ec498e8f) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | G15 5510                    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Dell          | Latitude 5490               | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Aquarius      | NS585                       | [6f4b987640](https://linux-hardware.org/?probe=6f4b987640) | Apr 11, 2023 |
| Dell          | Latitude 3320               | [b7c2bb88b3](https://linux-hardware.org/?probe=b7c2bb88b3) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [436e7b8903](https://linux-hardware.org/?probe=436e7b8903) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |
| eMachines     | eME728                      | [aff08e7f2d](https://linux-hardware.org/?probe=aff08e7f2d) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| System76      | Lemur Pro                   | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| Framework     | Laptop                      | [5bb187865d](https://linux-hardware.org/?probe=5bb187865d) | Apr 04, 2023 |
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [50e9dee7b1](https://linux-hardware.org/?probe=50e9dee7b1) | Apr 01, 2023 |
| HP            | EliteBook 840 G5            | [3c509a7075](https://linux-hardware.org/?probe=3c509a7075) | Apr 01, 2023 |
| Tactus        | GeoBook 140                 | [0ceb5a3b7c](https://linux-hardware.org/?probe=0ceb5a3b7c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| THUNDEROBO... | 911 Plus                    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| GPD           | P3 MAX                      | [b3627909f1](https://linux-hardware.org/?probe=b3627909f1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| Dell          | Precision 5570              | [454590a1a8](https://linux-hardware.org/?probe=454590a1a8) | Mar 26, 2023 |
| Dell          | Latitude E6330              | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9b9a21b7da](https://linux-hardware.org/?probe=9b9a21b7da) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [58f8d5849a](https://linux-hardware.org/?probe=58f8d5849a) | Mar 24, 2023 |
| Toshiba       | Satellite C50-B             | [4b563f19dd](https://linux-hardware.org/?probe=4b563f19dd) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Toshiba       | Satellite C50-B             | [b9bf22cc53](https://linux-hardware.org/?probe=b9bf22cc53) | Mar 20, 2023 |
| Dell          | G3 3590                     | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Aquarius      | NS585                       | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [66f4a76724](https://linux-hardware.org/?probe=66f4a76724) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b50b834744](https://linux-hardware.org/?probe=b50b834744) | Mar 16, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f3ee556fb5](https://linux-hardware.org/?probe=f3ee556fb5) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| TUXEDO        | Aura 15 Gen2                | [15d4cdae49](https://linux-hardware.org/?probe=15d4cdae49) | Mar 14, 2023 |
| Acer          | Aspire E5-551G              | [7a992ff109](https://linux-hardware.org/?probe=7a992ff109) | Mar 14, 2023 |
| Schenker      | VIA 15 Pro                  | [ef02f8156e](https://linux-hardware.org/?probe=ef02f8156e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [55a73e2e07](https://linux-hardware.org/?probe=55a73e2e07) | Mar 12, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Dell          | Precision 5570              | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [2a58a07005](https://linux-hardware.org/?probe=2a58a07005) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [d17364c0ef](https://linux-hardware.org/?probe=d17364c0ef) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | [c528b16696](https://linux-hardware.org/?probe=c528b16696) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5bc1f5d6d8](https://linux-hardware.org/?probe=5bc1f5d6d8) | Mar 09, 2023 |
| Dell          | Precision 3560              | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Acer          | Nitro AN515-43              | [32d1af5dee](https://linux-hardware.org/?probe=32d1af5dee) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92f8093adb](https://linux-hardware.org/?probe=92f8093adb) | Mar 07, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| MSI           | Modern 15 A5M               | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [eb5b9b8cb9](https://linux-hardware.org/?probe=eb5b9b8cb9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| Dell          | XPS 15 9520                 | [1bef11c91d](https://linux-hardware.org/?probe=1bef11c91d) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| HP            | Laptop 17-bs0xx             | [e055e73b69](https://linux-hardware.org/?probe=e055e73b69) | Mar 02, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| Dell          | G3 3590                     | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Dell          | Latitude 7530               | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| HP            | Laptop 17-bs0xx             | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.1.0-9-amd64          | 128       | 40.51%  |
| 6.1.0-7-amd64          | 49        | 15.51%  |
| 6.1.0-4-amd64          | 39        | 12.34%  |
| 6.1.0-6-amd64          | 28        | 8.86%   |
| 6.1.0-5-amd64          | 21        | 6.65%   |
| 6.1.0-3-amd64          | 20        | 6.33%   |
| 6.1.0-8-amd64          | 7         | 2.22%   |
| 6.1.0-9-686-pae        | 2         | 0.63%   |
| 6.1.0-7-rt-amd64       | 2         | 0.63%   |
| 6.0.0-6-amd64          | 2         | 0.63%   |
| 6.0.0-2-amd64          | 2         | 0.63%   |
| 6.0.0-0.deb11.6-amd64  | 2         | 0.63%   |
| 6.3.9-1-liquorix-amd64 | 1         | 0.32%   |
| 6.3.8-1-liquorix-amd64 | 1         | 0.32%   |
| 6.3.0-7-amd64          | 1         | 0.32%   |
| 6.2.8                  | 1         | 0.32%   |
| 6.2.11                 | 1         | 0.32%   |
| 6.1.0-9-rt-amd64       | 1         | 0.32%   |
| 6.1.0-7-686            | 1         | 0.32%   |
| 6.1.0-2-amd64          | 1         | 0.32%   |
| 6.0.0-4-amd64          | 1         | 0.32%   |
| 5.19.0-0.deb11.2-amd64 | 1         | 0.32%   |
| 5.16.0-3-amd64         | 1         | 0.32%   |
| 5.15.95-xanmod1        | 1         | 0.32%   |
| 5.10.0-22-amd64        | 1         | 0.32%   |
| 5.10.0-20-amd64        | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 284       | 94.35%  |
| 6.0.0   | 7         | 2.33%   |
| 5.10.0  | 2         | 0.66%   |
| 6.3.9   | 1         | 0.33%   |
| 6.3.8   | 1         | 0.33%   |
| 6.3.0   | 1         | 0.33%   |
| 6.2.8   | 1         | 0.33%   |
| 6.2.11  | 1         | 0.33%   |
| 5.19.0  | 1         | 0.33%   |
| 5.16.0  | 1         | 0.33%   |
| 5.15.95 | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 284       | 94.35%  |
| 6.0     | 7         | 2.33%   |
| 6.3     | 3         | 1%      |
| 6.2     | 2         | 0.66%   |
| 5.10    | 2         | 0.66%   |
| 5.19    | 1         | 0.33%   |
| 5.16    | 1         | 0.33%   |
| 5.15    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 297       | 99%     |
| i686   | 3         | 1%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 114       | 37.87%  |
| KDE5             | 59        | 19.6%   |
| Unknown          | 58        | 19.27%  |
| XFCE             | 24        | 7.97%   |
| X-Cinnamon       | 17        | 5.65%   |
| MATE             | 8         | 2.66%   |
| i3               | 4         | 1.33%   |
| LXDE             | 3         | 1%      |
| GNOME Flashback  | 3         | 1%      |
| LXQt             | 2         | 0.66%   |
| Enlightenment    | 2         | 0.66%   |
| xmonad           | 1         | 0.33%   |
| sway             | 1         | 0.33%   |
| Pantheon         | 1         | 0.33%   |
| lightdm-xsession | 1         | 0.33%   |
| Cinnamon         | 1         | 0.33%   |
| Budgie           | 1         | 0.33%   |
| awesome          | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 126       | 41.58%  |
| Wayland | 113       | 37.29%  |
| Unknown | 50        | 16.5%   |
| Tty     | 14        | 4.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 35.2%   |
| GDM3    | 100       | 32.89%  |
| SDDM    | 49        | 16.12%  |
| LightDM | 44        | 14.47%  |
| LXDM    | 2         | 0.66%   |
| GREETD  | 2         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 88        | 29.24%  |
| ru_RU   | 51        | 16.94%  |
| de_DE   | 27        | 8.97%   |
| fr_FR   | 26        | 8.64%   |
| en_GB   | 17        | 5.65%   |
| sv_SE   | 12        | 3.99%   |
| Unknown | 11        | 3.65%   |
| pt_BR   | 7         | 2.33%   |
| zh_CN   | 6         | 1.99%   |
| it_IT   | 5         | 1.66%   |
| es_ES   | 4         | 1.33%   |
| en_CA   | 4         | 1.33%   |
| C       | 4         | 1.33%   |
| pl_PL   | 3         | 1%      |
| en_AU   | 3         | 1%      |
| tr_TR   | 2         | 0.66%   |
| nl_NL   | 2         | 0.66%   |
| en_IN   | 2         | 0.66%   |
| en_IL   | 2         | 0.66%   |
| ca_ES   | 2         | 0.66%   |
| be_BY   | 2         | 0.66%   |
| uk_UA   | 1         | 0.33%   |
| pt_PT   | 1         | 0.33%   |
| oc_FR   | 1         | 0.33%   |
| nl_BE   | 1         | 0.33%   |
| hu_HU   | 1         | 0.33%   |
| hr_HR   | 1         | 0.33%   |
| fr_BE   | 1         | 0.33%   |
| fi_FI   | 1         | 0.33%   |
| es_VE   | 1         | 0.33%   |
| es_US   | 1         | 0.33%   |
| es_PA   | 1         | 0.33%   |
| es_CL   | 1         | 0.33%   |
| es_AR   | 1         | 0.33%   |
| en_ZA   | 1         | 0.33%   |
| en_SG   | 1         | 0.33%   |
| en_NZ   | 1         | 0.33%   |
| en_IE   | 1         | 0.33%   |
| en_DK   | 1         | 0.33%   |
| de_AT   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 203       | 67.67%  |
| BIOS | 97        | 32.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 221       | 73.67%  |
| Overlay | 57        | 19%     |
| Btrfs   | 16        | 5.33%   |
| Xfs     | 3         | 1%      |
| Tmpfs   | 2         | 0.67%   |
| Zfs     | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 206       | 68.44%  |
| Unknown | 52        | 17.28%  |
| MBR     | 43        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 273       | 91%     |
| Yes       | 27        | 9%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 197       | 65.45%  |
| Yes       | 104       | 34.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 79        | 26.33%  |
| Dell                           | 43        | 14.33%  |
| Hewlett-Packard                | 36        | 12%     |
| Aquarius                       | 29        | 9.67%   |
| ASUSTek Computer               | 26        | 8.67%   |
| Acer                           | 20        | 6.67%   |
| Apple                          | 13        | 4.33%   |
| HUAWEI                         | 6         | 2%      |
| MSI                            | 5         | 1.67%   |
| Toshiba                        | 4         | 1.33%   |
| Sony                           | 3         | 1%      |
| Samsung Electronics            | 3         | 1%      |
| HONOR                          | 3         | 1%      |
| eMachines                      | 3         | 1%      |
| Schenker                       | 2         | 0.67%   |
| LG Electronics                 | 2         | 0.67%   |
| Google                         | 2         | 0.67%   |
| Avell High Performance         | 2         | 0.67%   |
| TUXEDO                         | 1         | 0.33%   |
| THUNDEROBOT                    | 1         | 0.33%   |
| Terrans Force                  | 1         | 0.33%   |
| Tactus                         | 1         | 0.33%   |
| System76                       | 1         | 0.33%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.33%   |
| Semp Toshiba                   | 1         | 0.33%   |
| PC Specialist                  | 1         | 0.33%   |
| Packard Bell                   | 1         | 0.33%   |
| Notebook                       | 1         | 0.33%   |
| NEC Computers                  | 1         | 0.33%   |
| Medion                         | 1         | 0.33%   |
| IBM                            | 1         | 0.33%   |
| Hampoo                         | 1         | 0.33%   |
| GPD                            | 1         | 0.33%   |
| Fujitsu                        | 1         | 0.33%   |
| Framework                      | 1         | 0.33%   |
| Chuwi                          | 1         | 0.33%   |
| Unknown                        | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Aquarius NS585                           | 29        | 9.67%   |
| Apple MacBookAir7,2                      | 5         | 1.67%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX     | 4         | 1.33%   |
| Dell Precision 5570                      | 4         | 1.33%   |
| HP EliteBook 840 G5                      | 3         | 1%      |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00     | 2         | 0.67%   |
| HUAWEI BOHK-WAX9X                        | 2         | 0.67%   |
| HONOR NMH-WCX9                           | 2         | 0.67%   |
| HP ProBook 640 G1                        | 2         | 0.67%   |
| HP ProBook 440 14 inch G9 Notebook PC    | 2         | 0.67%   |
| HP OMEN by Laptop                        | 2         | 0.67%   |
| HP EliteBook 845 G8 Notebook PC          | 2         | 0.67%   |
| HP 255 G8 Notebook PC                    | 2         | 0.67%   |
| Dell XPS 15 9570                         | 2         | 0.67%   |
| Dell Latitude 7480                       | 2         | 0.67%   |
| Dell Latitude 3320                       | 2         | 0.67%   |
| Dell G3 3590                             | 2         | 0.67%   |
| ASUS Zenbook UX535QE_UM535QE             | 2         | 0.67%   |
| ASUS VivoBook_ASUSLaptop M3401QA_M3401QA | 2         | 0.67%   |
| Acer Nitro AN515-45                      | 2         | 0.67%   |
| Acer Nitro AN515-43                      | 2         | 0.67%   |
| Acer Aspire A515-56                      | 2         | 0.67%   |
| Unknown                                  | 2         | 0.67%   |
| TUXEDO Aura 15 Gen2                      | 1         | 0.33%   |
| Toshiba Satellite X200                   | 1         | 0.33%   |
| Toshiba Satellite C855-22N               | 1         | 0.33%   |
| Toshiba Satellite C50-B                  | 1         | 0.33%   |
| Toshiba Satellite A200                   | 1         | 0.33%   |
| THUNDEROBOT 911 Plus                     | 1         | 0.33%   |
| Terrans Force AMD                        | 1         | 0.33%   |
| Tactus GeoBook 140                       | 1         | 0.33%   |
| System76 Lemur Pro                       | 1         | 0.33%   |
| Sony VPCF13WFX                           | 1         | 0.33%   |
| Sony SVE1512M6ESI                        | 1         | 0.33%   |
| Sony SVE11116FGW                         | 1         | 0.33%   |
| Shanghai Zhaoxin ZXE CRB                 | 1         | 0.33%   |
| Semp Toshiba IS 1413G                    | 1         | 0.33%   |
| Schenker XMG CORE (REN/M20)              | 1         | 0.33%   |
| Schenker VIA 15 Pro                      | 1         | 0.33%   |
| Samsung 750XED                           | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 56        | 18.67%  |
| Aquarius NS585       | 29        | 9.67%   |
| Dell Latitude        | 15        | 5%      |
| HP EliteBook         | 11        | 3.67%   |
| Acer Aspire          | 11        | 3.67%   |
| Lenovo IdeaPad       | 10        | 3.33%   |
| ASUS VivoBook        | 10        | 3.33%   |
| Dell XPS             | 9         | 3%      |
| HP ProBook           | 7         | 2.33%   |
| Dell Precision       | 6         | 2%      |
| Dell Inspiron        | 6         | 2%      |
| ASUS ZenBook         | 6         | 2%      |
| Apple MacBookAir7    | 6         | 2%      |
| Toshiba Satellite    | 4         | 1.33%   |
| Acer Nitro           | 4         | 1.33%   |
| MSI Prestige         | 3         | 1%      |
| Lenovo Yoga          | 3         | 1%      |
| HP Pavilion          | 3         | 1%      |
| HP OMEN              | 3         | 1%      |
| HP Laptop            | 3         | 1%      |
| Dell Vostro          | 3         | 1%      |
| Acer TravelMate      | 3         | 1%      |
| Lenovo Legion        | 2         | 0.67%   |
| HUAWEI BOHK-WAX9X    | 2         | 0.67%   |
| HONOR NMH-WCX9       | 2         | 0.67%   |
| HP ZBook             | 2         | 0.67%   |
| HP 255               | 2         | 0.67%   |
| Dell G3              | 2         | 0.67%   |
| Dell G15             | 2         | 0.67%   |
| Unknown              | 2         | 0.67%   |
| TUXEDO Aura          | 1         | 0.33%   |
| THUNDEROBOT 911      | 1         | 0.33%   |
| Terrans Force AMD    | 1         | 0.33%   |
| Tactus GeoBook       | 1         | 0.33%   |
| System76 Lemur       | 1         | 0.33%   |
| Sony VPCF13WFX       | 1         | 0.33%   |
| Sony SVE1512M6ESI    | 1         | 0.33%   |
| Sony SVE11116FGW     | 1         | 0.33%   |
| Shanghai Zhaoxin ZXE | 1         | 0.33%   |
| Semp Toshiba IS      | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 53        | 17.67%  |
| 2021 | 44        | 14.67%  |
| 2022 | 42        | 14%     |
| 2020 | 34        | 11.33%  |
| 2018 | 17        | 5.67%   |
| 2017 | 17        | 5.67%   |
| 2012 | 16        | 5.33%   |
| 2015 | 13        | 4.33%   |
| 2013 | 12        | 4%      |
| 2010 | 12        | 4%      |
| 2014 | 9         | 3%      |
| 2009 | 9         | 3%      |
| 2016 | 5         | 1.67%   |
| 2008 | 5         | 1.67%   |
| 2011 | 4         | 1.33%   |
| 2007 | 4         | 1.33%   |
| 2023 | 3         | 1%      |
| 2005 | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 300       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 257       | 85.67%  |
| Enabled  | 43        | 14.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 297       | 99%     |
| Yes  | 3         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 109       | 36.33%  |
| 8.01-16.0   | 55        | 18.33%  |
| 16.01-24.0  | 49        | 16.33%  |
| 3.01-4.0    | 37        | 12.33%  |
| 32.01-64.0  | 33        | 11%     |
| 64.01-256.0 | 6         | 2%      |
| 1.01-2.0    | 6         | 2%      |
| 2.01-3.0    | 5         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 68        | 22.01%  |
| 1.01-2.0   | 66        | 21.36%  |
| 4.01-8.0   | 65        | 21.04%  |
| 0.51-1.0   | 45        | 14.56%  |
| 3.01-4.0   | 40        | 12.94%  |
| 8.01-16.0  | 19        | 6.15%   |
| 0.01-0.5   | 4         | 1.29%   |
| 32.01-64.0 | 1         | 0.32%   |
| 16.01-24.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 245       | 81.4%   |
| 2      | 47        | 15.61%  |
| 3      | 9         | 2.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 246       | 82%     |
| Yes       | 54        | 18%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 75.33%  |
| No        | 74        | 24.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 98%     |
| No        | 6         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 87%     |
| No        | 39        | 13%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Russia       | 54        | 17.76%  |
| Germany      | 37        | 12.17%  |
| USA          | 30        | 9.87%   |
| France       | 29        | 9.54%   |
| Sweden       | 20        | 6.58%   |
| Brazil       | 16        | 5.26%   |
| UK           | 10        | 3.29%   |
| Spain        | 8         | 2.63%   |
| Poland       | 8         | 2.63%   |
| Italy        | 8         | 2.63%   |
| Canada       | 6         | 1.97%   |
| Australia    | 5         | 1.64%   |
| Netherlands  | 4         | 1.32%   |
| Czechia      | 4         | 1.32%   |
| China        | 4         | 1.32%   |
| Ukraine      | 3         | 0.99%   |
| Turkey       | 3         | 0.99%   |
| Israel       | 3         | 0.99%   |
| Belgium      | 3         | 0.99%   |
| Austria      | 3         | 0.99%   |
| Singapore    | 2         | 0.66%   |
| Romania      | 2         | 0.66%   |
| New Zealand  | 2         | 0.66%   |
| Mexico       | 2         | 0.66%   |
| Madagascar   | 2         | 0.66%   |
| India        | 2         | 0.66%   |
| Hungary      | 2         | 0.66%   |
| Georgia      | 2         | 0.66%   |
| Denmark      | 2         | 0.66%   |
| Belarus      | 2         | 0.66%   |
| Venezuela    | 1         | 0.33%   |
| Uzbekistan   | 1         | 0.33%   |
| Uruguay      | 1         | 0.33%   |
| UAE          | 1         | 0.33%   |
| Switzerland  | 1         | 0.33%   |
| Sudan        | 1         | 0.33%   |
| South Africa | 1         | 0.33%   |
| Slovakia     | 1         | 0.33%   |
| Portugal     | 1         | 0.33%   |
| Panama       | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Voronezh             | 38        | 12.38%  |
| Saltsjoe-Boo         | 13        | 4.23%   |
| Bangor               | 11        | 3.58%   |
| Moscow               | 8         | 2.61%   |
| Paris                | 7         | 2.28%   |
| Marseille            | 4         | 1.3%    |
| Munich               | 3         | 0.98%   |
| Frankfurt am Main    | 3         | 0.98%   |
| Berlin               | 3         | 0.98%   |
| Beijing              | 3         | 0.98%   |
| Wroclaw              | 2         | 0.65%   |
| Toronto              | 2         | 0.65%   |
| Tiranges             | 2         | 0.65%   |
| Tbilisi              | 2         | 0.65%   |
| St Petersburg        | 2         | 0.65%   |
| Singapore            | 2         | 0.65%   |
| Seville              | 2         | 0.65%   |
| San Francisco        | 2         | 0.65%   |
| Samara               | 2         | 0.65%   |
| Płock               | 2         | 0.65%   |
| Most                 | 2         | 0.65%   |
| Mesa                 | 2         | 0.65%   |
| Melbourne            | 2         | 0.65%   |
| Malmo                | 2         | 0.65%   |
| London               | 2         | 0.65%   |
| Istanbul             | 2         | 0.65%   |
| Indianapolis         | 2         | 0.65%   |
| Hrodna               | 2         | 0.65%   |
| Brasília            | 2         | 0.65%   |
| Barcelona            | 2         | 0.65%   |
| Amsterdam            | 2         | 0.65%   |
| Ahrensburg           | 2         | 0.65%   |
| Yangon               | 1         | 0.33%   |
| Whitby               | 1         | 0.33%   |
| Wetzlar              | 1         | 0.33%   |
| Wendlingen am Neckar | 1         | 0.33%   |
| Warsaw               | 1         | 0.33%   |
| Vouille              | 1         | 0.33%   |
| Vila Velha           | 1         | 0.33%   |
| Vienna               | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 65        | 77     | 18.52%  |
| WDC                         | 39        | 44     | 11.11%  |
| A-DATA Technology           | 34        | 46     | 9.69%   |
| SanDisk                     | 23        | 27     | 6.55%   |
| Toshiba                     | 18        | 20     | 5.13%   |
| SK hynix                    | 17        | 20     | 4.84%   |
| Micron Technology           | 17        | 17     | 4.84%   |
| Seagate                     | 15        | 16     | 4.27%   |
| Kingston                    | 14        | 16     | 3.99%   |
| Unknown                     | 12        | 14     | 3.42%   |
| Intel                       | 11        | 11     | 3.13%   |
| Crucial                     | 9         | 11     | 2.56%   |
| Apple                       | 9         | 9      | 2.56%   |
| KIOXIA                      | 6         | 7      | 1.71%   |
| HGST                        | 6         | 6      | 1.71%   |
| Kingston Technology Company | 4         | 4      | 1.14%   |
| Hitachi                     | 4         | 4      | 1.14%   |
| SSSTC                       | 3         | 3      | 0.85%   |
| JMicron Technology          | 3         | 3      | 0.85%   |
| Intenso                     | 3         | 3      | 0.85%   |
| China                       | 3         | 3      | 0.85%   |
| TO Exter                    | 2         | 3      | 0.57%   |
| Silicon Motion              | 2         | 3      | 0.57%   |
| Phison                      | 2         | 2      | 0.57%   |
| OCZ                         | 2         | 2      | 0.57%   |
| Fujitsu                     | 2         | 2      | 0.57%   |
| ADATA Technology            | 2         | 2      | 0.57%   |
| YMTC                        | 1         | 1      | 0.28%   |
| Wellcomm                    | 1         | 1      | 0.28%   |
| UMIS                        | 1         | 1      | 0.28%   |
| T-FORCE                     | 1         | 1      | 0.28%   |
| SPCC                        | 1         | 1      | 0.28%   |
| ShiJi                       | 1         | 2      | 0.28%   |
| SABRENT                     | 1         | 1      | 0.28%   |
| S3+                         | 1         | 1      | 0.28%   |
| Realtek                     | 1         | 1      | 0.28%   |
| Pioneer                     | 1         | 1      | 0.28%   |
| Phison Electronics          | 1         | 1      | 0.28%   |
| Patriot                     | 1         | 1      | 0.28%   |
| Origin                      | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| A-DATA SU800 512GB SSD                              | 29        | 8.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 8         | 2.23%   |
| Samsung PM9A1 NVMe 1024GB                           | 5         | 1.4%    |
| Apple SSD SM0128G 121GB                             | 5         | 1.4%    |
| Toshiba XG6 NVMe SSD Controller 2TB                 | 4         | 1.12%   |
| Samsung SSD 980 1TB                                 | 4         | 1.12%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 1.12%   |
| Unknown SD32G  32GB                                 | 3         | 0.84%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 0.84%   |
| Samsung SSD 980 PRO 1TB                             | 3         | 0.84%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.56%   |
| WDC PC SN730 SDBPNTY-1T00-1102 1TB                  | 2         | 0.56%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB                | 2         | 0.56%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.56%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.56%   |
| TO Exter nal USB 3.0 1TB                            | 2         | 0.56%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 0.56%   |
| SK hynix BC711 NVMe 256GB                           | 2         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.56%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 2         | 0.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 2         | 0.56%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                 | 2         | 0.56%   |
| Samsung SSD 980 500GB                               | 2         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 0.56%   |
| Samsung MZVLQ256HBJD-00BH1 256GB                    | 2         | 0.56%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                      | 2         | 0.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 2         | 0.56%   |
| Samsung MZ7PD256HCGM-000H7 256GB SSD                | 2         | 0.56%   |
| Micron MTFDKCD1T0TFK 1TB                            | 2         | 0.56%   |
| Micron 2300 NVMe 512GB                              | 2         | 0.56%   |
| KIOXIA KBG50ZNS256G NVMe 256GB                      | 2         | 0.56%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                      | 2         | 0.56%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 2         | 0.56%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.56%   |
| Kingston SA2000M81000G 1TB                          | 2         | 0.56%   |
| JMicron Generic 240GB                               | 2         | 0.56%   |
| Intel SSDPEKNW512G8 512GB                           | 2         | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 0.56%   |
| Fujitsu MHZ2160BH FFS G1 160GB                      | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 14     | 29.79%  |
| Seagate | 13        | 13     | 27.66%  |
| Toshiba | 6         | 7      | 12.77%  |
| HGST    | 6         | 6      | 12.77%  |
| Hitachi | 4         | 4      | 8.51%   |
| Fujitsu | 2         | 2      | 4.26%   |
| Unknown | 1         | 1      | 2.13%   |
| Apple   | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 30        | 42     | 25.21%  |
| Samsung Electronics | 12        | 15     | 10.08%  |
| SanDisk             | 11        | 15     | 9.24%   |
| Kingston            | 8         | 9      | 6.72%   |
| Crucial             | 8         | 9      | 6.72%   |
| WDC                 | 7         | 7      | 5.88%   |
| Apple               | 6         | 6      | 5.04%   |
| Toshiba             | 4         | 5      | 3.36%   |
| Intenso             | 3         | 3      | 2.52%   |
| Intel               | 3         | 3      | 2.52%   |
| China               | 3         | 3      | 2.52%   |
| TO Exter            | 2         | 3      | 1.68%   |
| SK hynix            | 2         | 2      | 1.68%   |
| OCZ                 | 2         | 2      | 1.68%   |
| Micron Technology   | 2         | 2      | 1.68%   |
| Wellcomm            | 1         | 1      | 0.84%   |
| SPCC                | 1         | 1      | 0.84%   |
| S3+                 | 1         | 1      | 0.84%   |
| Pioneer             | 1         | 1      | 0.84%   |
| Patriot             | 1         | 1      | 0.84%   |
| Origin              | 1         | 1      | 0.84%   |
| Netac               | 1         | 1      | 0.84%   |
| MicroFrom           | 1         | 1      | 0.84%   |
| LITEON              | 1         | 1      | 0.84%   |
| Lexar               | 1         | 1      | 0.84%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.84%   |
| INNOVATION IT       | 1         | 1      | 0.84%   |
| Haizhide            | 1         | 1      | 0.84%   |
| GOODRAM             | 1         | 1      | 0.84%   |
| AMD                 | 1         | 1      | 0.84%   |
| Acer                | 1         | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 164       | 192    | 47.81%  |
| SSD     | 116       | 142    | 33.82%  |
| HDD     | 47        | 48     | 13.7%   |
| MMC     | 12        | 14     | 3.5%    |
| Unknown | 4         | 4      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 161       | 188    | 47.63%  |
| SATA | 154       | 185    | 45.56%  |
| MMC  | 12        | 14     | 3.55%   |
| SAS  | 11        | 13     | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 113    | 61.35%  |
| 0.51-1.0   | 58        | 72     | 35.58%  |
| 1.01-2.0   | 3         | 3      | 1.84%   |
| 3.01-4.0   | 2         | 2      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 78        | 25.74%  |
| 101-250        | 70        | 23.1%   |
| Unknown        | 50        | 16.5%   |
| 501-1000       | 49        | 16.17%  |
| 1001-2000      | 25        | 8.25%   |
| 51-100         | 13        | 4.29%   |
| 1-20           | 11        | 3.63%   |
| 21-50          | 4         | 1.32%   |
| 2001-3000      | 2         | 0.66%   |
| More than 3000 | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 90        | 29.51%  |
| 101-250   | 53        | 17.38%  |
| Unknown   | 50        | 16.39%  |
| 21-50     | 39        | 12.79%  |
| 51-100    | 32        | 10.49%  |
| 251-500   | 19        | 6.23%   |
| 501-1000  | 15        | 4.92%   |
| 1001-2000 | 7         | 2.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000LPVT-08G33T1 500GB         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 5.26%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1      | 5.26%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 5.26%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 5.26%   |
| ShiJi 1TB                            | 1         | 2      | 5.26%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5.26%   |
| Seagate ST9250414ASG 250GB           | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 5.26%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 5.26%   |
| SanDisk SD7SB2Q512G1001 512GB SSD    | 1         | 1      | 5.26%   |
| Micron Technology 2300 NVMe 512GB    | 1         | 1      | 5.26%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 5.26%   |
| JMicron Technology Generic 240GB     | 1         | 1      | 5.26%   |
| Intel SSDSC2BF240A4L 240GB           | 1         | 1      | 5.26%   |
| Hitachi HTS545050B9A300 500GB        | 1         | 1      | 5.26%   |
| Hitachi HTS541616J9SA00 160GB        | 1         | 1      | 5.26%   |
| HGST HTS725032A7E630 320GB           | 1         | 1      | 5.26%   |
| HGST HTS545050A7E680 500GB           | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 3         | 3      | 15.79%  |
| Toshiba            | 2         | 2      | 10.53%  |
| SK hynix           | 2         | 2      | 10.53%  |
| SanDisk            | 2         | 2      | 10.53%  |
| Hitachi            | 2         | 2      | 10.53%  |
| HGST               | 2         | 2      | 10.53%  |
| WDC                | 1         | 1      | 5.26%   |
| ShiJi              | 1         | 2      | 5.26%   |
| Micron Technology  | 1         | 1      | 5.26%   |
| Kingston           | 1         | 1      | 5.26%   |
| JMicron Technology | 1         | 1      | 5.26%   |
| Intel              | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| Toshiba | 2         | 2      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 52.63%  |
| NVMe | 5         | 6      | 26.32%  |
| SSD  | 4         | 4      | 21.05%  |

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
| Works    | 224       | 279    | 70.22%  |
| Detected | 76        | 101    | 23.82%  |
| Malfunc  | 19        | 20     | 5.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 161       | 44.35%  |
| Samsung Electronics            | 58        | 15.98%  |
| AMD                            | 35        | 9.64%   |
| SanDisk                        | 30        | 8.26%   |
| Micron Technology              | 15        | 4.13%   |
| SK hynix                       | 14        | 3.86%   |
| Kingston Technology Company    | 10        | 2.75%   |
| Toshiba America Info Systems   | 8         | 2.2%    |
| KIOXIA                         | 6         | 1.65%   |
| ADATA Technology               | 6         | 1.65%   |
| Solid State Storage Technology | 3         | 0.83%   |
| Silicon Motion                 | 3         | 0.83%   |
| Phison Electronics             | 3         | 0.83%   |
| Nvidia                         | 2         | 0.55%   |
| Micron/Crucial Technology      | 2         | 0.55%   |
| Apple                          | 2         | 0.55%   |
| Yangtze Memory Technologies    | 1         | 0.28%   |
| Union Memory (Shenzhen)        | 1         | 0.28%   |
| Seagate Technology             | 1         | 0.28%   |
| Jiangsu Huacun Elec.           | 1         | 0.28%   |
| Biwin Storage Technology       | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 7.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29        | 7.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 4.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 17        | 4.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 4.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 3.94%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 3.15%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 3.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 2.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 2.1%    |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 2.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 2.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 1.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 1.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.84%   |
| Micron NVMe Storage Controller                                                 | 6         | 1.57%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 6         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.31%   |
| Samsung Electronics SATA controller                                            | 5         | 1.31%   |
| Intel Non-Volatile memory controller                                           | 5         | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.31%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.05%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.79%   |
| KIOXIA Non-Volatile memory controller                                          | 3         | 0.79%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.79%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.52%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 181       | 48.92%  |
| NVMe | 160       | 43.24%  |
| RAID | 19        | 5.14%   |
| IDE  | 10        | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 237       | 79%     |
| AMD          | 62        | 20.67%  |
| CentaurHauls | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-9100 CPU @ 3.60GHz              | 29        | 9.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 4.98%   |
| Intel 12th Gen Core i7-12700H                 | 7         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 2.33%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 6         | 1.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 1.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.99%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 1.66%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.33%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1%      |
| Intel 12th Gen Core i7-1265U                  | 3         | 1%      |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1%      |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1%      |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 1%      |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1%      |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1%      |
| AMD E-350 Processor                           | 3         | 1%      |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.66%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.66%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.66%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.66%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.66%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.66%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.66%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 67        | 22.26%  |
| Intel Core i5           | 57        | 18.94%  |
| Intel Core i7           | 39        | 12.96%  |
| Intel Core i3           | 39        | 12.96%  |
| AMD Ryzen 5             | 19        | 6.31%   |
| AMD Ryzen 7             | 17        | 5.65%   |
| Intel Core 2 Duo        | 13        | 4.32%   |
| Intel Pentium           | 7         | 2.33%   |
| Intel Celeron           | 6         | 1.99%   |
| AMD Ryzen 5 PRO         | 6         | 1.99%   |
| AMD Ryzen 9             | 5         | 1.66%   |
| Intel Pentium Dual-Core | 3         | 1%      |
| Intel Atom              | 3         | 1%      |
| AMD Ryzen 7 PRO         | 3         | 1%      |
| AMD E                   | 3         | 1%      |
| Intel Pentium Silver    | 2         | 0.66%   |
| Intel Core i9           | 2         | 0.66%   |
| AMD Athlon II           | 2         | 0.66%   |
| Intel Xeon              | 1         | 0.33%   |
| Intel Pentium M         | 1         | 0.33%   |
| Intel Core 2            | 1         | 0.33%   |
| AMD Ryzen 3             | 1         | 0.33%   |
| AMD E2                  | 1         | 0.33%   |
| AMD E1                  | 1         | 0.33%   |
| AMD C-60                | 1         | 0.33%   |
| AMD A6                  | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 115       | 38.33%  |
| 2      | 103       | 34.33%  |
| 8      | 26        | 8.67%   |
| 6      | 26        | 8.67%   |
| 10     | 11        | 3.67%   |
| 14     | 10        | 3.33%   |
| 12     | 7         | 2.33%   |
| 1      | 2         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 300       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 224       | 74.17%  |
| 1      | 78        | 25.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 298       | 99.33%  |
| 32-bit         | 2         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 23.18%  |
| 0x906eb    | 29        | 9.6%    |
| 0x806c1    | 27        | 8.94%   |
| 0x906a3    | 15        | 4.97%   |
| 0x906a4    | 11        | 3.64%   |
| 0x1067a    | 10        | 3.31%   |
| 0x806ea    | 9         | 2.98%   |
| 0x306d4    | 9         | 2.98%   |
| 0x0a50000c | 9         | 2.98%   |
| 0x306a9    | 8         | 2.65%   |
| 0x806ec    | 7         | 2.32%   |
| 0x806e9    | 7         | 2.32%   |
| 0x306c3    | 7         | 2.32%   |
| 0x08608103 | 7         | 2.32%   |
| 0x08108109 | 7         | 2.32%   |
| 0x406e3    | 5         | 1.66%   |
| 0x40651    | 5         | 1.66%   |
| 0x906ea    | 4         | 1.32%   |
| 0x706a8    | 4         | 1.32%   |
| 0x206a7    | 4         | 1.32%   |
| 0x20655    | 4         | 1.32%   |
| 0x0a50000d | 4         | 1.32%   |
| 0x08600106 | 4         | 1.32%   |
| 0x806d1    | 2         | 0.66%   |
| 0x6fd      | 2         | 0.66%   |
| 0x10676    | 2         | 0.66%   |
| 0x0a404102 | 2         | 0.66%   |
| 0x08600103 | 2         | 0.66%   |
| 0x08108102 | 2         | 0.66%   |
| 0x05000029 | 2         | 0.66%   |
| 0xb06a2    | 1         | 0.33%   |
| 0xa0660    | 1         | 0.33%   |
| 0xa0652    | 1         | 0.33%   |
| 0x906e9    | 1         | 0.33%   |
| 0x806eb    | 1         | 0.33%   |
| 0x806c2    | 1         | 0.33%   |
| 0x6d6      | 1         | 0.33%   |
| 0x506e3    | 1         | 0.33%   |
| 0x406c3    | 1         | 0.33%   |
| 0x30678    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 76        | 25.25%  |
| TigerLake        | 33        | 10.96%  |
| Alderlake Hybrid | 26        | 8.64%   |
| Unknown          | 19        | 6.31%   |
| Zen 3            | 18        | 5.98%   |
| Haswell          | 16        | 5.32%   |
| IvyBridge        | 15        | 4.98%   |
| Penryn           | 13        | 4.32%   |
| Zen+             | 11        | 3.65%   |
| Broadwell        | 11        | 3.65%   |
| Skylake          | 10        | 3.32%   |
| Zen 2            | 8         | 2.66%   |
| Westmere         | 8         | 2.66%   |
| Silvermont       | 5         | 1.66%   |
| Bobcat           | 5         | 1.66%   |
| SandyBridge      | 4         | 1.33%   |
| IceLake          | 4         | 1.33%   |
| Goldmont plus    | 4         | 1.33%   |
| Core             | 4         | 1.33%   |
| K10              | 2         | 0.66%   |
| Excavator        | 2         | 0.66%   |
| CometLake        | 2         | 0.66%   |
| Zen              | 1         | 0.33%   |
| P6               | 1         | 0.33%   |
| Nehalem          | 1         | 0.33%   |
| Jaguar           | 1         | 0.33%   |
| Bonnell          | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 220       | 60.11%  |
| AMD     | 74        | 20.22%  |
| Nvidia  | 71        | 19.4%   |
| Zhaoxin | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 30        | 8%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 29        | 7.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 15        | 4%      |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 14        | 3.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 13        | 3.47%   |
| Intel UHD Graphics 620                                                                | 12        | 3.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 12        | 3.2%    |
| AMD Lucienne                                                                          | 10        | 2.67%   |
| Intel HD Graphics 620                                                                 | 9         | 2.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 2.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 8         | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 8         | 2.13%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 8         | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 8         | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 1.87%   |
| AMD Renoir                                                                            | 7         | 1.87%   |
| Intel HD Graphics 6000                                                                | 6         | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                   | 6         | 1.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 1.33%   |
| AMD Barcelo                                                                           | 5         | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 1.07%   |
| Intel HD Graphics 630                                                                 | 4         | 1.07%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 1.07%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 3         | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 0.8%    |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                                | 3         | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 0.8%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 3         | 0.8%    |
| Intel HD Graphics 5500                                                                | 3         | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 0.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 0.8%    |
| AMD Wrestler [Radeon HD 6310]                                                         | 3         | 0.8%    |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 0.8%    |
| Nvidia GP108M [GeForce MX250]                                                         | 2         | 0.53%   |
| Nvidia GP108M [GeForce MX230]                                                         | 2         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 163       | 54.15%  |
| 1 x AMD        | 51        | 16.94%  |
| Intel + Nvidia | 46        | 15.28%  |
| 1 x Nvidia     | 13        | 4.32%   |
| AMD + Nvidia   | 11        | 3.65%   |
| Intel + AMD    | 7         | 2.33%   |
| 2 x AMD        | 5         | 1.66%   |
| 2 x Intel      | 4         | 1.33%   |
| 1 x Zhaoxin    | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 234       | 77.74%  |
| Unknown     | 42        | 13.95%  |
| Proprietary | 25        | 8.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 226       | 74.83%  |
| 0.01-0.5   | 30        | 9.93%   |
| 1.01-2.0   | 15        | 4.97%   |
| 0.51-1.0   | 13        | 4.3%    |
| 3.01-4.0   | 11        | 3.64%   |
| 7.01-8.0   | 5         | 1.66%   |
| 5.01-6.0   | 2         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 20.47%  |
| BOE                     | 46        | 15.44%  |
| Chimei Innolux          | 37        | 12.42%  |
| Samsung Electronics     | 28        | 9.4%    |
| LG Display              | 26        | 8.72%   |
| Sharp                   | 13        | 4.36%   |
| Apple                   | 13        | 4.36%   |
| Dell                    | 10        | 3.36%   |
| PANDA                   | 9         | 3.02%   |
| InfoVision              | 6         | 2.01%   |
| BenQ                    | 6         | 2.01%   |
| Philips                 | 5         | 1.68%   |
| Lenovo                  | 5         | 1.68%   |
| Hewlett-Packard         | 4         | 1.34%   |
| LG Philips              | 3         | 1.01%   |
| Goldstar                | 3         | 1.01%   |
| Chi Mei Optoelectronics | 3         | 1.01%   |
| ViewSonic               | 2         | 0.67%   |
| Toshiba                 | 2         | 0.67%   |
| Sony                    | 2         | 0.67%   |
| CSO                     | 2         | 0.67%   |
| Ancor Communications    | 2         | 0.67%   |
| Mi                      | 1         | 0.34%   |
| InnoLux Display         | 1         | 0.34%   |
| Iiyama                  | 1         | 0.34%   |
| IBM                     | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |
| BOE Technology Group    | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |
| AOC                     | 1         | 0.34%   |
| Acer                    | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 3.01%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 1.34%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 1.34%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 3         | 1%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 1%      |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 1%      |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2         | 0.67%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 2         | 0.67%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.67%   |
| LG Display LCD Monitor LGD06EA 2560x1600 366x229mm 17.0-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch           | 2         | 0.67%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 2         | 0.67%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 0.67%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch          | 2         | 0.67%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 2         | 0.67%   |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                 | 2         | 0.67%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2         | 0.67%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO559C 1920x1080 309x174mm 14.0-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO332C 1366x768 293x165mm 13.2-inch         | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 0.67%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 2         | 0.67%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 0.67%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1         | 0.33%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1         | 0.33%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 1         | 0.33%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 148       | 52.11%  |
| 1366x768 (WXGA)    | 48        | 16.9%   |
| 1920x1200 (WUXGA)  | 14        | 4.93%   |
| 1600x900 (HD+)     | 12        | 4.23%   |
| 3840x2160 (4K)     | 9         | 3.17%   |
| 2560x1440 (QHD)    | 9         | 3.17%   |
| 1440x900 (WXGA+)   | 9         | 3.17%   |
| 1280x800 (WXGA)    | 7         | 2.46%   |
| 3840x2400          | 5         | 1.76%   |
| 2880x1800          | 4         | 1.41%   |
| 2560x1600          | 4         | 1.41%   |
| 3440x1440          | 2         | 0.7%    |
| 3840x1100          | 1         | 0.35%   |
| 3456x2160          | 1         | 0.35%   |
| 3200x1800 (QHD+)   | 1         | 0.35%   |
| 3072x1920          | 1         | 0.35%   |
| 3000x2000          | 1         | 0.35%   |
| 2966x900           | 1         | 0.35%   |
| 2880x1620          | 1         | 0.35%   |
| 2256x1504          | 1         | 0.35%   |
| 1920x540           | 1         | 0.35%   |
| 1680x1050 (WSXGA+) | 1         | 0.35%   |
| 1280x1024 (SXGA)   | 1         | 0.35%   |
| 1024x600           | 1         | 0.35%   |
| Unknown            | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 107       | 36.03%  |
| 13      | 68        | 22.9%   |
| 14      | 47        | 15.82%  |
| 24      | 17        | 5.72%   |
| 17      | 10        | 3.37%   |
| 27      | 9         | 3.03%   |
| 12      | 6         | 2.02%   |
| 11      | 6         | 2.02%   |
| 23      | 5         | 1.68%   |
| Unknown | 4         | 1.35%   |
| 21      | 3         | 1.01%   |
| 16      | 3         | 1.01%   |
| 72      | 2         | 0.67%   |
| 34      | 2         | 0.67%   |
| 31      | 2         | 0.67%   |
| 48      | 1         | 0.34%   |
| 28      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 22      | 1         | 0.34%   |
| 20      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 185       | 62.71%  |
| 201-300     | 49        | 16.61%  |
| 501-600     | 30        | 10.17%  |
| 351-400     | 13        | 4.41%   |
| 401-500     | 5         | 1.69%   |
| 601-700     | 4         | 1.36%   |
| Unknown     | 4         | 1.36%   |
| 701-800     | 2         | 0.68%   |
| 1501-2000   | 2         | 0.68%   |
| 1001-1500   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 210       | 79.25%  |
| 16/10   | 44        | 16.6%   |
| Unknown | 4         | 1.51%   |
| 4/3     | 2         | 0.75%   |
| 3/2     | 2         | 0.75%   |
| 21/9    | 2         | 0.75%   |
| 3.40    | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 104       | 34.9%   |
| 81-90          | 88        | 29.53%  |
| 71-80          | 26        | 8.72%   |
| 201-250        | 18        | 6.04%   |
| 301-350        | 10        | 3.36%   |
| 121-130        | 9         | 3.02%   |
| 51-60          | 7         | 2.35%   |
| 61-70          | 6         | 2.01%   |
| 251-300        | 6         | 2.01%   |
| 111-120        | 6         | 2.01%   |
| 351-500        | 5         | 1.68%   |
| 151-200        | 4         | 1.34%   |
| Unknown        | 4         | 1.34%   |
| More than 1000 | 3         | 1.01%   |
| 41-50          | 1         | 0.34%   |
| 131-140        | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 153       | 52.58%  |
| 101-120       | 49        | 16.84%  |
| 51-100        | 36        | 12.37%  |
| 161-240       | 30        | 10.31%  |
| More than 240 | 16        | 5.5%    |
| Unknown       | 4         | 1.37%   |
| 1-50          | 3         | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 211       | 69.64%  |
| 2     | 47        | 15.51%  |
| 0     | 43        | 14.19%  |
| 3     | 2         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 188       | 40.17%  |
| Realtek Semiconductor             | 144       | 30.77%  |
| Qualcomm Atheros                  | 42        | 8.97%   |
| Broadcom                          | 24        | 5.13%   |
| MediaTek                          | 12        | 2.56%   |
| ASIX Electronics                  | 11        | 2.35%   |
| Broadcom Limited                  | 9         | 1.92%   |
| Qualcomm                          | 5         | 1.07%   |
| Xiaomi                            | 4         | 0.85%   |
| Marvell Technology Group          | 3         | 0.64%   |
| TP-Link                           | 2         | 0.43%   |
| Sierra Wireless                   | 2         | 0.43%   |
| Ralink                            | 2         | 0.43%   |
| Nvidia                            | 2         | 0.43%   |
| Google                            | 2         | 0.43%   |
| Ericsson Business Mobile Networks | 2         | 0.43%   |
| D-Link                            | 2         | 0.43%   |
| Wacom                             | 1         | 0.21%   |
| U-Blox                            | 1         | 0.21%   |
| Spreadtrum Communications         | 1         | 0.21%   |
| OPPO Electronics                  | 1         | 0.21%   |
| NetGear                           | 1         | 0.21%   |
| Microsoft                         | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| Fujitsu                           | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| ASUSTek Computer                  | 1         | 0.21%   |
| Apple                             | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 99        | 17.74%  |
| Intel Cannon Lake PCH CNVi WiFi                                   | 31        | 5.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 24        | 4.3%    |
| Intel Wi-Fi 6 AX201                                               | 23        | 4.12%   |
| Intel Wireless 8265 / 8275                                        | 19        | 3.41%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 3.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 2.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 1.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 1.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 1.79%   |
| Intel Wireless 7260                                               | 10        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 8         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.43%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 1.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 7         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.08%   |
| Intel Wireless 7265                                               | 6         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.08%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 6         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.9%    |
| Intel Ethernet Connection (16) I219-V                             | 5         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.9%    |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 4         | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.72%   |
| Intel Wireless 8260                                               | 4         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.54%   |
| Intel Wireless-AC 9260                                            | 3         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.54%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 176       | 57.89%  |
| Realtek Semiconductor | 38        | 12.5%   |
| Qualcomm Atheros      | 38        | 12.5%   |
| Broadcom              | 18        | 5.92%   |
| MediaTek              | 11        | 3.62%   |
| Broadcom Limited      | 8         | 2.63%   |
| Qualcomm              | 4         | 1.32%   |
| Sierra Wireless       | 2         | 0.66%   |
| Ralink                | 2         | 0.66%   |
| D-Link                | 2         | 0.66%   |
| Wacom                 | 1         | 0.33%   |
| TP-Link               | 1         | 0.33%   |
| NetGear               | 1         | 0.33%   |
| Microsoft             | 1         | 0.33%   |
| ASUSTek Computer      | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                                       | 31        | 10.13%  |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 24        | 7.84%   |
| Intel Wi-Fi 6 AX201                                                                   | 23        | 7.52%   |
| Intel Wireless 8265 / 8275                                                            | 19        | 6.21%   |
| Intel Wi-Fi 6 AX200                                                                   | 17        | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 10        | 3.27%   |
| Intel Wireless 7260                                                                   | 10        | 3.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 9         | 2.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 8         | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 8         | 2.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                           | 7         | 2.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 6         | 1.96%   |
| Intel Wireless 7265                                                                   | 6         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 6         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 1.63%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                            | 4         | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 4         | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 4         | 1.31%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 4         | 1.31%   |
| Intel Wireless 8260                                                                   | 4         | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3         | 0.98%   |
| Intel Wireless-AC 9260                                                                | 3         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 3         | 0.98%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 0.65%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 2         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 0.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 2         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 0.65%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 0.65%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 2         | 0.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 2         | 0.65%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                              | 1         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 129       | 53.09%  |
| Intel                     | 66        | 27.16%  |
| ASIX Electronics          | 11        | 4.53%   |
| Qualcomm Atheros          | 10        | 4.12%   |
| Broadcom                  | 7         | 2.88%   |
| Xiaomi                    | 4         | 1.65%   |
| Marvell Technology Group  | 3         | 1.23%   |
| Nvidia                    | 2         | 0.82%   |
| Google                    | 2         | 0.82%   |
| TP-Link                   | 1         | 0.41%   |
| Spreadtrum Communications | 1         | 0.41%   |
| Qualcomm                  | 1         | 0.41%   |
| OPPO Electronics          | 1         | 0.41%   |
| MediaTek                  | 1         | 0.41%   |
| Lenovo                    | 1         | 0.41%   |
| JMicron Technology        | 1         | 0.41%   |
| Broadcom Limited          | 1         | 0.41%   |
| Apple                     | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 99        | 40.24%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 6.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 4.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 4.47%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.25%   |
| Intel Ethernet Connection (16) I219-V                             | 5         | 2.03%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.22%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.22%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 1.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.81%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.81%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.81%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.81%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.41%   |
| Spreadtrum Spreadtrum Phone                                       | 1         | 0.41%   |
| Qualcomm Nokia G400 5G                                            | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.41%   |
| OPPO CPH2411                                                      | 1         | 0.41%   |
| MediaTek Armor X10 Pro                                            | 1         | 0.41%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 294       | 55.79%  |
| Ethernet | 227       | 43.07%  |
| Modem    | 6         | 1.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 207       | 64.69%  |
| Ethernet | 113       | 35.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 200       | 66.67%  |
| 1     | 94        | 31.33%  |
| 0     | 4         | 1.33%   |
| 3     | 2         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 207       | 68.32%  |
| Yes  | 96        | 31.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 158       | 59.62%  |
| Realtek Semiconductor           | 28        | 10.57%  |
| Qualcomm Atheros Communications | 15        | 5.66%   |
| Foxconn / Hon Hai               | 13        | 4.91%   |
| Apple                           | 12        | 4.53%   |
| Lite-On Technology              | 9         | 3.4%    |
| IMC Networks                    | 7         | 2.64%   |
| Broadcom                        | 6         | 2.26%   |
| Realtek                         | 3         | 1.13%   |
| Dell                            | 3         | 1.13%   |
| Toshiba                         | 2         | 0.75%   |
| Hewlett-Packard                 | 2         | 0.75%   |
| ASUSTek Computer                | 2         | 0.75%   |
| Ralink Technology               | 1         | 0.38%   |
| Micro Star International        | 1         | 0.38%   |
| MediaTek                        | 1         | 0.38%   |
| Foxconn International           | 1         | 0.38%   |
| Cambridge Silicon Radio         | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 44        | 16.6%   |
| Intel Bluetooth wireless interface                | 41        | 15.47%  |
| Intel AX201 Bluetooth                             | 30        | 11.32%  |
| Realtek Bluetooth Radio                           | 26        | 9.81%   |
| Intel AX200 Bluetooth                             | 17        | 6.42%   |
| Intel Bluetooth Device                            | 16        | 6.04%   |
| Qualcomm Atheros  Bluetooth Device                | 9         | 3.4%    |
| Foxconn / Hon Hai Bluetooth Device                | 7         | 2.64%   |
| Apple Bluetooth USB Host Controller               | 6         | 2.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 4         | 1.51%   |
| Foxconn / Hon Hai Wireless_Device                 | 4         | 1.51%   |
| Apple Bluetooth Host Controller                   | 4         | 1.51%   |
| Realtek Bluetooth Radio                           | 3         | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 3         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 1.13%   |
| Lite-On Wireless_Device                           | 3         | 1.13%   |
| Lite-On Bluetooth Device                          | 3         | 1.13%   |
| IMC Networks Wireless_Device                      | 3         | 1.13%   |
| Dell BCM20702A0 Bluetooth Module                  | 3         | 1.13%   |
| Realtek  Bluetooth 4.2 Adapter                    | 2         | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 0.75%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 0.75%   |
| Intel AX210 Bluetooth                             | 2         | 0.75%   |
| IMC Networks Bluetooth Radio                      | 2         | 0.75%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                       | 2         | 0.75%   |
| Toshiba RT Bluetooth Radio                        | 1         | 0.38%   |
| Toshiba Integrated Bluetooth HCI                  | 1         | 0.38%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 0.38%   |
| Micro Star International Bluetooth EDR Device     | 1         | 0.38%   |
| MediaTek Wireless_Device                          | 1         | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.38%   |
| IMC Networks Bluetooth USB Host Controller        | 1         | 0.38%   |
| IMC Networks Bluetooth module                     | 1         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 0.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 0.38%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.38%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.38%   |
| Foxconn / Hon Hai BCM2045A0                       | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 231       | 65.07%  |
| AMD                     | 66        | 18.59%  |
| Nvidia                  | 31        | 8.73%   |
| C-Media Electronics     | 4         | 1.13%   |
| Logitech                | 3         | 0.85%   |
| Lenovo                  | 3         | 0.85%   |
| Realtek Semiconductor   | 2         | 0.56%   |
| Zhaoxin                 | 1         | 0.28%   |
| Yamaha                  | 1         | 0.28%   |
| SteelSeries ApS         | 1         | 0.28%   |
| Samson Technologies     | 1         | 0.28%   |
| Plantronics             | 1         | 0.28%   |
| Kingston Technology     | 1         | 0.28%   |
| JMTek                   | 1         | 0.28%   |
| Hewlett-Packard         | 1         | 0.28%   |
| GN Netcom               | 1         | 0.28%   |
| Creative Technology     | 1         | 0.28%   |
| Cambridge Silicon Radio | 1         | 0.28%   |
| Beyerdynamic            | 1         | 0.28%   |
| Audient                 | 1         | 0.28%   |
| ASUSTek Computer        | 1         | 0.28%   |
| Apple                   | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 50        | 11.34%  |
| Intel Cannon Lake PCH cAVS                                                 | 38        | 8.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 33        | 7.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 7.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 30        | 6.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 27        | 6.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 2.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 2.49%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 2.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.81%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.13%   |
| AMD Wrestler HDMI Audio                                                    | 5         | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.91%   |
| Nvidia Audio device                                                        | 4         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.91%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.68%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.68%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.45%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 73        | 25.52%  |
| SK hynix                                | 66        | 23.08%  |
| Micron Technology                       | 37        | 12.94%  |
| Crucial                                 | 34        | 11.89%  |
| Unknown                                 | 20        | 6.99%   |
| Kingston                                | 17        | 5.94%   |
| A-DATA Technology                       | 9         | 3.15%   |
| Elpida                                  | 7         | 2.45%   |
| Corsair                                 | 5         | 1.75%   |
| Ramaxel Technology                      | 4         | 1.4%    |
| Unknown (ABCD)                          | 2         | 0.7%    |
| Nanya Technology                        | 2         | 0.7%    |
| ASint Technology                        | 2         | 0.7%    |
| Unknown                                 | 2         | 0.7%    |
| Smart                                   | 1         | 0.35%   |
| Silicon Power Computer & Communications | 1         | 0.35%   |
| PKI                                     | 1         | 0.35%   |
| Neo Forza                               | 1         | 0.35%   |
| A Force                                 | 1         | 0.35%   |
| <Invalid>                               | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 29        | 9.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.95%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.3%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.98%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 3         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.98%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.65%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.65%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 2         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.65%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.65%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.65%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.65%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.65%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.65%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.65%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 2         | 0.65%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.65%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 142       | 56.8%   |
| DDR3    | 54        | 21.6%   |
| LPDDR4  | 15        | 6%      |
| DDR5    | 11        | 4.4%    |
| LPDDR5  | 7         | 2.8%    |
| LPDDR3  | 7         | 2.8%    |
| DDR2    | 7         | 2.8%    |
| SDRAM   | 3         | 1.2%    |
| Unknown | 3         | 1.2%    |
| DDR     | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 215       | 84.98%  |
| Row Of Chips | 34        | 13.44%  |
| Chip         | 2         | 0.79%   |
| Unknown      | 2         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 125       | 45.62%  |
| 4096  | 58        | 21.17%  |
| 16384 | 38        | 13.87%  |
| 2048  | 33        | 12.04%  |
| 32768 | 11        | 4.01%   |
| 1024  | 8         | 2.92%   |
| 256   | 1         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 63        | 24.32%  |
| 3200    | 62        | 23.94%  |
| 1600    | 40        | 15.44%  |
| 2400    | 16        | 6.18%   |
| 4800    | 11        | 4.25%   |
| 4267    | 11        | 4.25%   |
| 2133    | 8         | 3.09%   |
| 6400    | 7         | 2.7%    |
| Unknown | 7         | 2.7%    |
| 1067    | 6         | 2.32%   |
| 800     | 6         | 2.32%   |
| 1334    | 4         | 1.54%   |
| 1867    | 3         | 1.16%   |
| 1066    | 3         | 1.16%   |
| 8400    | 2         | 0.77%   |
| 4266    | 2         | 0.77%   |
| 667     | 2         | 0.77%   |
| 4199    | 1         | 0.39%   |
| 3266    | 1         | 0.39%   |
| 2666    | 1         | 0.39%   |
| 2048    | 1         | 0.39%   |
| 1333    | 1         | 0.39%   |
| 975     | 1         | 0.39%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 24.54%  |
| IMC Networks                           | 36        | 13.19%  |
| Acer                                   | 35        | 12.82%  |
| Microdia                               | 20        | 7.33%   |
| Bison Electronics                      | 17        | 6.23%   |
| Realtek Semiconductor                  | 16        | 5.86%   |
| Quanta                                 | 15        | 5.49%   |
| Sunplus Innovation Technology          | 12        | 4.4%    |
| Syntek                                 | 8         | 2.93%   |
| Lite-On Technology                     | 7         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.56%   |
| Luxvisions Innotech Limited            | 5         | 1.83%   |
| Apple                                  | 5         | 1.83%   |
| Lenovo                                 | 4         | 1.47%   |
| Suyin                                  | 3         | 1.1%    |
| USB Camera                             | 2         | 0.73%   |
| SunplusIT                              | 2         | 0.73%   |
| Sonix Technology                       | 2         | 0.73%   |
| Silicon Motion                         | 2         | 0.73%   |
| Logitech                               | 2         | 0.73%   |
| Alcor Micro                            | 2         | 0.73%   |
| Ricoh                                  | 1         | 0.37%   |
| OmniVision Technologies                | 1         | 0.37%   |
| Generalplus Technology                 | 1         | 0.37%   |
| ALi                                    | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Acer BisonCam, NB Pro                               | 28        | 10.14%  |
| Chicony Integrated Camera                           | 16        | 5.8%    |
| Microdia Integrated_Webcam_HD                       | 15        | 5.43%   |
| IMC Networks Integrated Camera                      | 11        | 3.99%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 3.62%   |
| Realtek Integrated_Webcam_HD                        | 9         | 3.26%   |
| Syntek Integrated Camera                            | 7         | 2.54%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 2.54%   |
| Chicony HD Webcam                                   | 7         | 2.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.81%   |
| Chicony HP HD Camera                                | 5         | 1.81%   |
| Chicony HD User Facing                              | 5         | 1.81%   |
| Bison Integrated Camera                             | 5         | 1.81%   |
| Lite-On Integrated Camera                           | 4         | 1.45%   |
| Chicony USB2.0 Camera                               | 4         | 1.45%   |
| Quanta ov9734_techfront_camera                      | 3         | 1.09%   |
| Quanta HP HD Camera                                 | 3         | 1.09%   |
| Quanta HD User Facing                               | 3         | 1.09%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 1.09%   |
| Chicony USB 2.0 Camera                              | 3         | 1.09%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.09%   |
| Chicony HP Webcam                                   | 3         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 3         | 1.09%   |
| Bison Integrated RGB Camera                         | 3         | 1.09%   |
| Acer Integrated Camera                              | 3         | 1.09%   |
| USB Camera USB Camera                               | 2         | 0.72%   |
| Sunplus HP Wide Vision HD                           | 2         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 0.72%   |
| Realtek USB Camera                                  | 2         | 0.72%   |
| Realtek Integrated Webcam                           | 2         | 0.72%   |
| Quanta VGA WebCam                                   | 2         | 0.72%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.72%   |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 0.72%   |
| Lite-On HP HD Camera                                | 2         | 0.72%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 0.72%   |
| IMC Networks HD Camera                              | 2         | 0.72%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.72%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 0.72%   |
| Chicony 1.3M Webcam                                 | 2         | 0.72%   |
| Bison HD Camera                                     | 2         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 26        | 40%     |
| Validity Sensors                   | 18        | 27.69%  |
| Shenzhen Goodix Technology         | 9         | 13.85%  |
| Upek                               | 3         | 4.62%   |
| STMicroelectronics                 | 3         | 4.62%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 3.08%   |
| LighTuning Technology              | 2         | 3.08%   |
| Elan Microelectronics              | 1         | 1.54%   |
| AuthenTec                          | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 15.38%  |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 12.31%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 6.15%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 6.15%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 6.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.15%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 6.15%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.62%   |
| Synaptics UWP WBDI Device                                                  | 3         | 4.62%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 4.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.08%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 3.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.54%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.54%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.54%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.54%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.54%   |
| Unknown                                                                    | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 15        | 53.57%  |
| Broadcom    | 8         | 28.57%  |
| Lenovo      | 3         | 10.71%  |
| Yubico.com  | 1         | 3.57%   |
| Upek        | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 50%     |
| Lenovo Integrated Smart Card Reader                                          | 3         | 10.71%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10.71%  |
| Broadcom 58200                                                               | 3         | 10.71%  |
| Broadcom 5880                                                                | 2         | 7.14%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 3.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.57%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 137       | 45.36%  |
| 1     | 132       | 43.71%  |
| 2     | 29        | 9.6%    |
| 3     | 4         | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 64        | 33.86%  |
| Graphics card         | 59        | 31.22%  |
| Chipcard              | 23        | 12.17%  |
| Multimedia controller | 14        | 7.41%   |
| Camera                | 13        | 6.88%   |
| Net/wireless          | 10        | 5.29%   |
| Bluetooth             | 2         | 1.06%   |
| Wireless              | 1         | 0.53%   |
| Storage               | 1         | 0.53%   |
| Sound                 | 1         | 0.53%   |
| Net/ethernet          | 1         | 0.53%   |

