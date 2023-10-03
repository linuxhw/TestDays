Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 11416

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 9500                 | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Acer          | Predator PH16-71            | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| Dell          | Latitude 5520               | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Apple         | MacBookPro9,2               | [124425b8b3](https://linux-hardware.org/?probe=124425b8b3) | Oct 01, 2023 |
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| HUAWEI        | VLT-WX0                     | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| Dell          | Latitude 7280               | [dbe9d3e4be](https://linux-hardware.org/?probe=dbe9d3e4be) | Sep 30, 2023 |
| Toshiba       | PORTEGE R30-D               | [04ef694f1d](https://linux-hardware.org/?probe=04ef694f1d) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Lenovo        | ThinkPad T420 4180BV1       | [e81749053b](https://linux-hardware.org/?probe=e81749053b) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [95dc405a73](https://linux-hardware.org/?probe=95dc405a73) | Sep 29, 2023 |
| HP            | Laptop 17-cn1xxx            | [051a233121](https://linux-hardware.org/?probe=051a233121) | Sep 29, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e51fd2a8e9](https://linux-hardware.org/?probe=e51fd2a8e9) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| Dell          | Latitude 7490               | [a22e4e9304](https://linux-hardware.org/?probe=a22e4e9304) | Sep 29, 2023 |
| HP            | EliteBook 840 G6            | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| HP            | ProBook 430 G5              | [9e68b6e2be](https://linux-hardware.org/?probe=9e68b6e2be) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| HP            | Notebook                    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Zebra Tech... | 10-WLAN-1                   | [9959efdb76](https://linux-hardware.org/?probe=9959efdb76) | Sep 27, 2023 |
| Dell          | Latitude 7490               | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Framework     | Laptop                      | [2a65b0dff2](https://linux-hardware.org/?probe=2a65b0dff2) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Samsung       | 550XDA                      | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| Chuwi         | CoreBook X                  | [0c31a47880](https://linux-hardware.org/?probe=0c31a47880) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| Dell          | Latitude E7450              | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| HUAWEI        | RLEF-XX                     | [156140f867](https://linux-hardware.org/?probe=156140f867) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| Dell          | Latitude 7490               | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Dell          | G15 5520                    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Latitude 5420               | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [424e7e3d87](https://linux-hardware.org/?probe=424e7e3d87) | Sep 26, 2023 |
| HP            | EliteBook 745 G6            | [bb5a7f8b2c](https://linux-hardware.org/?probe=bb5a7f8b2c) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| Dell          | Inspiron 7577               | [a90c8128d1](https://linux-hardware.org/?probe=a90c8128d1) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [b22a584cea](https://linux-hardware.org/?probe=b22a584cea) | Sep 26, 2023 |
| Juana Mans... | SF20GM7                     | [355aaa1b07](https://linux-hardware.org/?probe=355aaa1b07) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [37fdb062e1](https://linux-hardware.org/?probe=37fdb062e1) | Sep 26, 2023 |
| Apple         | MacBookPro10,1              | [1c1268d4e0](https://linux-hardware.org/?probe=1c1268d4e0) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | [4fbb517b71](https://linux-hardware.org/?probe=4fbb517b71) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [4e0f83e1fe](https://linux-hardware.org/?probe=4e0f83e1fe) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [60ff167d14](https://linux-hardware.org/?probe=60ff167d14) | Sep 25, 2023 |
| System76      | Pangolin                    | [3c56c50463](https://linux-hardware.org/?probe=3c56c50463) | Sep 25, 2023 |
| Acer          | Aspire V3-571G              | [6b5dcea023](https://linux-hardware.org/?probe=6b5dcea023) | Sep 25, 2023 |
| Dell          | Latitude E7270              | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | [91c3333a18](https://linux-hardware.org/?probe=91c3333a18) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| HP            | ProBook 6570b               | [a67981aa91](https://linux-hardware.org/?probe=a67981aa91) | Sep 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [88385cbacc](https://linux-hardware.org/?probe=88385cbacc) | Sep 25, 2023 |
| Dell          | XPS 13 9310                 | [4233a2e5e3](https://linux-hardware.org/?probe=4233a2e5e3) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| MSI           | GL65 Leopard 10SER          | [e97a8fa2c7](https://linux-hardware.org/?probe=e97a8fa2c7) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| MSI           | GL65 Leopard 10SER          | [fac92f385c](https://linux-hardware.org/?probe=fac92f385c) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Acer          | TravelMate P259-MG          | [26ca7317b2](https://linux-hardware.org/?probe=26ca7317b2) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| Apple         | MacBookPro8,2               | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| Lenovo        | V14-ARE 82DQ                | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [f728eb13bd](https://linux-hardware.org/?probe=f728eb13bd) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| HP            | 350 G2                      | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| HP            | 255 15.6 inch G10           | [9f02426c5d](https://linux-hardware.org/?probe=9f02426c5d) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | [18b2a7026b](https://linux-hardware.org/?probe=18b2a7026b) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | [60f81eeb50](https://linux-hardware.org/?probe=60f81eeb50) | Sep 23, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| HP            | Pavilion dv6                | [bd8ae0385b](https://linux-hardware.org/?probe=bd8ae0385b) | Sep 23, 2023 |
| Dell          | Latitude 7280               | [1d032535e1](https://linux-hardware.org/?probe=1d032535e1) | Sep 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| Casper        | NIRVANA NB F500             | [1f66f22544](https://linux-hardware.org/?probe=1f66f22544) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [11ce4105e1](https://linux-hardware.org/?probe=11ce4105e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [904a43b77e](https://linux-hardware.org/?probe=904a43b77e) | Sep 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [6a6fde2ca9](https://linux-hardware.org/?probe=6a6fde2ca9) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [eedf248084](https://linux-hardware.org/?probe=eedf248084) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire A715-51G             | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| Apple         | MacBookPro11,1              | [169fe58269](https://linux-hardware.org/?probe=169fe58269) | Sep 22, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [c933242918](https://linux-hardware.org/?probe=c933242918) | Sep 22, 2023 |
| Dell          | Inspiron N5110              | [e98b118b85](https://linux-hardware.org/?probe=e98b118b85) | Sep 22, 2023 |
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [909efbf81b](https://linux-hardware.org/?probe=909efbf81b) | Sep 22, 2023 |
| Dell          | Latitude 5420               | [d9c1c1537f](https://linux-hardware.org/?probe=d9c1c1537f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7c5cc5e0ab](https://linux-hardware.org/?probe=7c5cc5e0ab) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [74fa7aed8b](https://linux-hardware.org/?probe=74fa7aed8b) | Sep 22, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [0e85445e8e](https://linux-hardware.org/?probe=0e85445e8e) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [3a372bed63](https://linux-hardware.org/?probe=3a372bed63) | Sep 21, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| HP            | Pavilion dv6                | [270b0c0878](https://linux-hardware.org/?probe=270b0c0878) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3cd9b7841a](https://linux-hardware.org/?probe=3cd9b7841a) | Sep 21, 2023 |
| Timi          | A35S                        | [ae2a6acf26](https://linux-hardware.org/?probe=ae2a6acf26) | Sep 21, 2023 |
| Timi          | RedmiBook 15                | [af7ac2b917](https://linux-hardware.org/?probe=af7ac2b917) | Sep 21, 2023 |
| Lenovo        | Mullins-LarneML             | [56157a1cff](https://linux-hardware.org/?probe=56157a1cff) | Sep 21, 2023 |
| Samsung       | R530/R730/R540              | [658ca13022](https://linux-hardware.org/?probe=658ca13022) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| HP            | Pavilion g6                 | [11c60c8645](https://linux-hardware.org/?probe=11c60c8645) | Sep 21, 2023 |
| Dell          | Vostro 1310                 | [bc0c23c23c](https://linux-hardware.org/?probe=bc0c23c23c) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | [a2a2bc81e9](https://linux-hardware.org/?probe=a2a2bc81e9) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [b4f1770e14](https://linux-hardware.org/?probe=b4f1770e14) | Sep 20, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [ddf1d6a712](https://linux-hardware.org/?probe=ddf1d6a712) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [79111191a0](https://linux-hardware.org/?probe=79111191a0) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | [97bae35595](https://linux-hardware.org/?probe=97bae35595) | Sep 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | [0aefa5e3c6](https://linux-hardware.org/?probe=0aefa5e3c6) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| Samsung       | NC210/NC110                 | [1e194a2568](https://linux-hardware.org/?probe=1e194a2568) | Sep 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [27002ca3a9](https://linux-hardware.org/?probe=27002ca3a9) | Sep 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| Acer          | Aspire A515-56              | [bb52b1ddc5](https://linux-hardware.org/?probe=bb52b1ddc5) | Sep 20, 2023 |
| Samsung       | 960XFH                      | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Maibenben     | MaiBook M Series            | [dc2eb7a7d7](https://linux-hardware.org/?probe=dc2eb7a7d7) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| MSI           | Summit E15 A11SCST          | [aa908f1cea](https://linux-hardware.org/?probe=aa908f1cea) | Sep 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ca0ad87f0b](https://linux-hardware.org/?probe=ca0ad87f0b) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | ProBook 6475b               | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f9e5656f54](https://linux-hardware.org/?probe=f9e5656f54) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMS1WN0A    | [858aed6617](https://linux-hardware.org/?probe=858aed6617) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Acer          | Aspire A315-59              | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [4d986c5384](https://linux-hardware.org/?probe=4d986c5384) | Sep 18, 2023 |
| Dell          | Latitude 5490               | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| MSI           | Katana GF76 11UD            | [f797b137a3](https://linux-hardware.org/?probe=f797b137a3) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [f58cf1f72d](https://linux-hardware.org/?probe=f58cf1f72d) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [68cef2242a](https://linux-hardware.org/?probe=68cef2242a) | Sep 18, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [a4964c1b7a](https://linux-hardware.org/?probe=a4964c1b7a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| Dell          | Inspiron N5110              | [6903c7fc50](https://linux-hardware.org/?probe=6903c7fc50) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [1e40d8e0b9](https://linux-hardware.org/?probe=1e40d8e0b9) | Sep 18, 2023 |
| Lenovo        | G50-30 80G0                 | [fa9bd484cd](https://linux-hardware.org/?probe=fa9bd484cd) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [bd7a7a6f22](https://linux-hardware.org/?probe=bd7a7a6f22) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [c8ecd1e0c9](https://linux-hardware.org/?probe=c8ecd1e0c9) | Sep 17, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [290f6c66d1](https://linux-hardware.org/?probe=290f6c66d1) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [dd1ade8736](https://linux-hardware.org/?probe=dd1ade8736) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [21b0d9faff](https://linux-hardware.org/?probe=21b0d9faff) | Sep 17, 2023 |
| MSI           | Modern 14 B4MW              | [83a224edea](https://linux-hardware.org/?probe=83a224edea) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [77a72808f7](https://linux-hardware.org/?probe=77a72808f7) | Sep 17, 2023 |
| HP            | 250 G1                      | [0e052c1de2](https://linux-hardware.org/?probe=0e052c1de2) | Sep 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bf532ab6ec](https://linux-hardware.org/?probe=bf532ab6ec) | Sep 16, 2023 |
| HP            | EliteBook 820 G4            | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | Modern 14 B4MW              | [06e45359c0](https://linux-hardware.org/?probe=06e45359c0) | Sep 16, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [1b2e11b609](https://linux-hardware.org/?probe=1b2e11b609) | Sep 16, 2023 |
| Lenovo        | IdeaPad Z500 5931           | [0986123aac](https://linux-hardware.org/?probe=0986123aac) | Sep 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [12456f4694](https://linux-hardware.org/?probe=12456f4694) | Sep 16, 2023 |
| Dell          | XPS 9320                    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a5c073ca7a](https://linux-hardware.org/?probe=a5c073ca7a) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [2085bafc62](https://linux-hardware.org/?probe=2085bafc62) | Sep 16, 2023 |
| Acer          | TravelMate 5335             | [d440c12063](https://linux-hardware.org/?probe=d440c12063) | Sep 16, 2023 |
| Dell          | XPS L501X                   | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ec3d359099](https://linux-hardware.org/?probe=ec3d359099) | Sep 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [fa207e873a](https://linux-hardware.org/?probe=fa207e873a) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [054463900e](https://linux-hardware.org/?probe=054463900e) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [cdc9163353](https://linux-hardware.org/?probe=cdc9163353) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [032cd70e81](https://linux-hardware.org/?probe=032cd70e81) | Sep 15, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [951dc3d5b0](https://linux-hardware.org/?probe=951dc3d5b0) | Sep 15, 2023 |
| HP            | EliteBook Folio 9470m       | [4a598eb0b3](https://linux-hardware.org/?probe=4a598eb0b3) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a02233b901](https://linux-hardware.org/?probe=a02233b901) | Sep 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [934dc9c297](https://linux-hardware.org/?probe=934dc9c297) | Sep 14, 2023 |
| Apple         | MacBookPro9,2               | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| Acer          | Swift SF314-42              | [d907642716](https://linux-hardware.org/?probe=d907642716) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| Lenovo        | G505 20240                  | [db2962124c](https://linux-hardware.org/?probe=db2962124c) | Sep 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [756eff685a](https://linux-hardware.org/?probe=756eff685a) | Sep 14, 2023 |
| System76      | Darter Pro                  | [78c45153a3](https://linux-hardware.org/?probe=78c45153a3) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Pavilion 13 x360 PC         | [58de71a548](https://linux-hardware.org/?probe=58de71a548) | Sep 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aea796bbd9](https://linux-hardware.org/?probe=aea796bbd9) | Sep 14, 2023 |
| Toshiba       | PORTEGE M750                | [1c3442d87f](https://linux-hardware.org/?probe=1c3442d87f) | Sep 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [9ace0dfae8](https://linux-hardware.org/?probe=9ace0dfae8) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [d61823257e](https://linux-hardware.org/?probe=d61823257e) | Sep 13, 2023 |
| Dell          | Latitude 5421               | [6942c0131d](https://linux-hardware.org/?probe=6942c0131d) | Sep 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [cb29d8cb77](https://linux-hardware.org/?probe=cb29d8cb77) | Sep 13, 2023 |
| Dell          | Latitude 7390               | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| Fujitsu       | LIFEBOOK UH554              | [92f2e6135e](https://linux-hardware.org/?probe=92f2e6135e) | Sep 13, 2023 |
| Dell          | Inspiron 5566               | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| Dell          | Inspiron 5558               | [046d28d32d](https://linux-hardware.org/?probe=046d28d32d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0317b3bcf6](https://linux-hardware.org/?probe=0317b3bcf6) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [37f8406bab](https://linux-hardware.org/?probe=37f8406bab) | Sep 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [52a1dc1e19](https://linux-hardware.org/?probe=52a1dc1e19) | Sep 12, 2023 |
| ASUSTek       | K53SK                       | [5dcbdaa6d7](https://linux-hardware.org/?probe=5dcbdaa6d7) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [0965a776b0](https://linux-hardware.org/?probe=0965a776b0) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [d1d5edf95c](https://linux-hardware.org/?probe=d1d5edf95c) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b11bc1c28f](https://linux-hardware.org/?probe=b11bc1c28f) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [00a34c8719](https://linux-hardware.org/?probe=00a34c8719) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [3ef24a5b48](https://linux-hardware.org/?probe=3ef24a5b48) | Sep 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [4715a2425e](https://linux-hardware.org/?probe=4715a2425e) | Sep 12, 2023 |
| Apple         | MacBookPro9,2               | [77db8877eb](https://linux-hardware.org/?probe=77db8877eb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [564a2ea72e](https://linux-hardware.org/?probe=564a2ea72e) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f018495b81](https://linux-hardware.org/?probe=f018495b81) | Sep 12, 2023 |
| HP            | Laptop 15-dy5xxx            | [20ff9ece53](https://linux-hardware.org/?probe=20ff9ece53) | Sep 12, 2023 |
| Lenovo        | G770 20089                  | [39c8088b09](https://linux-hardware.org/?probe=39c8088b09) | Sep 12, 2023 |
| Apple         | MacBookAir6,2               | [e71b5644ea](https://linux-hardware.org/?probe=e71b5644ea) | Sep 12, 2023 |
| Dell          | XPS L521X                   | [d9e9a65142](https://linux-hardware.org/?probe=d9e9a65142) | Sep 12, 2023 |
| Positivo      | S14CT01                     | [57ed555d4b](https://linux-hardware.org/?probe=57ed555d4b) | Sep 11, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3cafef18bf](https://linux-hardware.org/?probe=3cafef18bf) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d4178bc91c](https://linux-hardware.org/?probe=d4178bc91c) | Sep 11, 2023 |
| HP            | ProBook 645 G1              | [ced1631b20](https://linux-hardware.org/?probe=ced1631b20) | Sep 11, 2023 |
| ASUSTek       | X505BA                      | [cbb45a815f](https://linux-hardware.org/?probe=cbb45a815f) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| HP            | EliteBook 2570p             | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Samsung       | 530XBB                      | [f6039477c2](https://linux-hardware.org/?probe=f6039477c2) | Sep 11, 2023 |
| Dell          | Inspiron 7548               | [0259762efc](https://linux-hardware.org/?probe=0259762efc) | Sep 11, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| HP            | ProBook 645 G1              | [e78c297114](https://linux-hardware.org/?probe=e78c297114) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6RF0... | [6c62d111db](https://linux-hardware.org/?probe=6c62d111db) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [8dc4477486](https://linux-hardware.org/?probe=8dc4477486) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [e737851117](https://linux-hardware.org/?probe=e737851117) | Sep 10, 2023 |
| Apple         | MacBookPro8,1               | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | [c78162f5fd](https://linux-hardware.org/?probe=c78162f5fd) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [30fd7bf070](https://linux-hardware.org/?probe=30fd7bf070) | Sep 10, 2023 |
| Dell          | Latitude E6400              | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [45261be082](https://linux-hardware.org/?probe=45261be082) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8b6b039242](https://linux-hardware.org/?probe=8b6b039242) | Sep 10, 2023 |
| Apple         | MacBookPro13,3              | [225a9ae1c5](https://linux-hardware.org/?probe=225a9ae1c5) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [4dfd50fada](https://linux-hardware.org/?probe=4dfd50fada) | Sep 10, 2023 |
| Apple         | MacBookPro8,1               | [69a1a556e0](https://linux-hardware.org/?probe=69a1a556e0) | Sep 09, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [64ea9bc56d](https://linux-hardware.org/?probe=64ea9bc56d) | Sep 09, 2023 |
| Dell          | XPS 13 9310                 | [f898a390e2](https://linux-hardware.org/?probe=f898a390e2) | Sep 09, 2023 |
| Acer          | Aspire 5745G                | [0528523e15](https://linux-hardware.org/?probe=0528523e15) | Sep 09, 2023 |
| Acer          | Aspire A715-51G             | [25649c8a92](https://linux-hardware.org/?probe=25649c8a92) | Sep 09, 2023 |
| Dell          | Inspiron 15-3552            | [eaf6dbaf3e](https://linux-hardware.org/?probe=eaf6dbaf3e) | Sep 09, 2023 |
| Acer          | Predator PH16-71            | [f0b0cc7736](https://linux-hardware.org/?probe=f0b0cc7736) | Sep 09, 2023 |
| Apple         | MacBookPro11,1              | [bc1887667f](https://linux-hardware.org/?probe=bc1887667f) | Sep 09, 2023 |
| Apple         | MacBookPro11,1              | [2da701e211](https://linux-hardware.org/?probe=2da701e211) | Sep 09, 2023 |
| Dell          | Inspiron 1545               | [95d13f26f0](https://linux-hardware.org/?probe=95d13f26f0) | Sep 09, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [ec08aee6ff](https://linux-hardware.org/?probe=ec08aee6ff) | Sep 09, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [aa6e5c75fc](https://linux-hardware.org/?probe=aa6e5c75fc) | Sep 09, 2023 |
| Lenovo        | Flex 2-14 20404             | [139a93ab8b](https://linux-hardware.org/?probe=139a93ab8b) | Sep 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [a7026388f3](https://linux-hardware.org/?probe=a7026388f3) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7c5a19bc69](https://linux-hardware.org/?probe=7c5a19bc69) | Sep 08, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6ea0b6ed9f](https://linux-hardware.org/?probe=6ea0b6ed9f) | Sep 08, 2023 |
| HP            | 630                         | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [74e5f6b8a5](https://linux-hardware.org/?probe=74e5f6b8a5) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [d4df00af33](https://linux-hardware.org/?probe=d4df00af33) | Sep 08, 2023 |
| Unknown       | W1415A                      | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [9646f55c7d](https://linux-hardware.org/?probe=9646f55c7d) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [3f8a5dcaaf](https://linux-hardware.org/?probe=3f8a5dcaaf) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [89772ef854](https://linux-hardware.org/?probe=89772ef854) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9ea6ff204](https://linux-hardware.org/?probe=c9ea6ff204) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [69fc5aab82](https://linux-hardware.org/?probe=69fc5aab82) | Sep 07, 2023 |
| Lenovo        | V580c 20160                 | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [384d2074ad](https://linux-hardware.org/?probe=384d2074ad) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [63fd300645](https://linux-hardware.org/?probe=63fd300645) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| MSI           | Bravo 17 A4DDR              | [2592f883ef](https://linux-hardware.org/?probe=2592f883ef) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E6500              | [b4b035c4f7](https://linux-hardware.org/?probe=b4b035c4f7) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| GPU Compan... | GWNR71517                   | [b6a521128f](https://linux-hardware.org/?probe=b6a521128f) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Dell          | XPS 13 9310                 | [7e81f7531b](https://linux-hardware.org/?probe=7e81f7531b) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| Dell          | Inspiron 3542               | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [f946665a24](https://linux-hardware.org/?probe=f946665a24) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [25ec8e4a16](https://linux-hardware.org/?probe=25ec8e4a16) | Sep 05, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| ASUSTek       | E402SA                      | [efad2958a0](https://linux-hardware.org/?probe=efad2958a0) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| Dell          | Latitude 7490               | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| Unknown       | Unknown                     | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| Apple         | MacBookPro9,2               | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [ea1d0861a1](https://linux-hardware.org/?probe=ea1d0861a1) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Acer          | Aspire 4738Z                | [88b34596c0](https://linux-hardware.org/?probe=88b34596c0) | Sep 05, 2023 |
| Dell          | XPS 13 7390                 | [5154be8883](https://linux-hardware.org/?probe=5154be8883) | Sep 05, 2023 |
| Dell          | G15 5530                    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | [3a5b200954](https://linux-hardware.org/?probe=3a5b200954) | Sep 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [da42098f81](https://linux-hardware.org/?probe=da42098f81) | Sep 04, 2023 |
| Dell          | XPS 13 9380                 | [94e7b43fe2](https://linux-hardware.org/?probe=94e7b43fe2) | Sep 04, 2023 |
| HP            | Laptop 15-dw2xxx            | [fff758a5d9](https://linux-hardware.org/?probe=fff758a5d9) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Dell          | Latitude 5285               | [9ddc47c6a9](https://linux-hardware.org/?probe=9ddc47c6a9) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| Framework     | Laptop                      | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Dell          | Latitude 3540               | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [8f29742c47](https://linux-hardware.org/?probe=8f29742c47) | Sep 02, 2023 |
| ASUSTek       | X540NA                      | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Dell          | Latitude 5400               | [aac8791780](https://linux-hardware.org/?probe=aac8791780) | Sep 02, 2023 |
| Lenovo        | 14w Gen 2 82N9              | [87c8a118b5](https://linux-hardware.org/?probe=87c8a118b5) | Sep 02, 2023 |
| Prestigio     | Multipad Visconte V         | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | [24d0eafc15](https://linux-hardware.org/?probe=24d0eafc15) | Sep 01, 2023 |
| Apple         | MacBookAir5,2               | [bda3b1837c](https://linux-hardware.org/?probe=bda3b1837c) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Apple         | MacBookAir4,1               | [61da3436a8](https://linux-hardware.org/?probe=61da3436a8) | Sep 01, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [239b46961f](https://linux-hardware.org/?probe=239b46961f) | Sep 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | [e111bad271](https://linux-hardware.org/?probe=e111bad271) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| Dell          | Latitude 5290 2-in-1        | [3a4c0e0930](https://linux-hardware.org/?probe=3a4c0e0930) | Aug 31, 2023 |
| Apple         | MacBook9,1                  | [b6a28c1e1a](https://linux-hardware.org/?probe=b6a28c1e1a) | Aug 31, 2023 |
| Dell          | Latitude 5290 2-in-1        | [5b632410e7](https://linux-hardware.org/?probe=5b632410e7) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| Lenovo        | ThinkPad L470 20J40010GE    | [53adc42d66](https://linux-hardware.org/?probe=53adc42d66) | Aug 31, 2023 |
| Dell          | Latitude 5590               | [59d99ec581](https://linux-hardware.org/?probe=59d99ec581) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| System76      | Lemur Pro                   | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Apple         | MacBookPro15,2              | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [b37cf7f8cf](https://linux-hardware.org/?probe=b37cf7f8cf) | Aug 30, 2023 |
| HP            | EliteBook 845 14 inch G9... | [4c595a576a](https://linux-hardware.org/?probe=4c595a576a) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| Dell          | Latitude 5430               | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Dell          | Vostro 2520                 | [73ca89b4fa](https://linux-hardware.org/?probe=73ca89b4fa) | Aug 30, 2023 |
| HP            | Laptop 17-by0xxx            | [4617fe766a](https://linux-hardware.org/?probe=4617fe766a) | Aug 29, 2023 |
| Dell          | Latitude 5480               | [88c6621b31](https://linux-hardware.org/?probe=88c6621b31) | Aug 29, 2023 |
| Dell          | Precision 5480              | [5fd5bf187d](https://linux-hardware.org/?probe=5fd5bf187d) | Aug 29, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [0eeb1276f0](https://linux-hardware.org/?probe=0eeb1276f0) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Timi          | A34S                        | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d627b8c625](https://linux-hardware.org/?probe=d627b8c625) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| Dell          | Latitude E6400              | [2af0a423ef](https://linux-hardware.org/?probe=2af0a423ef) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Nitro AN515-57              | [7608fab281](https://linux-hardware.org/?probe=7608fab281) | Aug 28, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [90e0cad295](https://linux-hardware.org/?probe=90e0cad295) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Framework     | Laptop                      | [b3e9d2d48d](https://linux-hardware.org/?probe=b3e9d2d48d) | Aug 27, 2023 |
| Corsair       | Voyager a1600               | [405bce7897](https://linux-hardware.org/?probe=405bce7897) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | T100TA                      | [69d14b429e](https://linux-hardware.org/?probe=69d14b429e) | Aug 27, 2023 |
| Dell          | Latitude E6400              | [fdcbc50452](https://linux-hardware.org/?probe=fdcbc50452) | Aug 27, 2023 |
| ASUSTek       | GL753VD                     | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Timi          | TM1701                      | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| HP            | Pavilion 15                 | [1731ba4ae5](https://linux-hardware.org/?probe=1731ba4ae5) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| HP            | Pavilion 15                 | [0f51268684](https://linux-hardware.org/?probe=0f51268684) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a8600db157](https://linux-hardware.org/?probe=a8600db157) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | [7bdfc94045](https://linux-hardware.org/?probe=7bdfc94045) | Aug 27, 2023 |
| Lenovo        | IdeaPad Z570 1024DCU        | [8a11757d37](https://linux-hardware.org/?probe=8a11757d37) | Aug 26, 2023 |
| Corsair       | Voyager a1600               | [97a1c576f7](https://linux-hardware.org/?probe=97a1c576f7) | Aug 26, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| HP            | OMEN by Laptop              | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| Acer          | Aspire A715-72G             | [cbbaecabb1](https://linux-hardware.org/?probe=cbbaecabb1) | Aug 26, 2023 |
| ASUSTek       | X542BP                      | [58cc535a58](https://linux-hardware.org/?probe=58cc535a58) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| Acer          | Predator PH16-71            | [ef267bc627](https://linux-hardware.org/?probe=ef267bc627) | Aug 26, 2023 |
| Apple         | MacBookPro13,2              | [b910d52198](https://linux-hardware.org/?probe=b910d52198) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6e84e686ec](https://linux-hardware.org/?probe=6e84e686ec) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [810ccd6f4f](https://linux-hardware.org/?probe=810ccd6f4f) | Aug 25, 2023 |
| Dell          | Inspiron 5585               | [49a9e7dbf0](https://linux-hardware.org/?probe=49a9e7dbf0) | Aug 25, 2023 |
| Dell          | Latitude 3490               | [05705b1834](https://linux-hardware.org/?probe=05705b1834) | Aug 25, 2023 |
| ASUSTek       | T100TA                      | [ef7b263d48](https://linux-hardware.org/?probe=ef7b263d48) | Aug 25, 2023 |
| Toshiba       | Satellite C70-B             | [2647e2edd8](https://linux-hardware.org/?probe=2647e2edd8) | Aug 24, 2023 |
| Dell          | G15 5510                    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Sony          | SVF15A1M2ES                 | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Dell          | Inspiron 5759               | [bf7413fc5f](https://linux-hardware.org/?probe=bf7413fc5f) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| LDLC          | SPC-I                       | [bb114215e6](https://linux-hardware.org/?probe=bb114215e6) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [5f18850003](https://linux-hardware.org/?probe=5f18850003) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [de37c3c7eb](https://linux-hardware.org/?probe=de37c3c7eb) | Aug 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ce5f964a0c](https://linux-hardware.org/?probe=ce5f964a0c) | Aug 24, 2023 |
| Dell          | Latitude 3490               | [148d4806cb](https://linux-hardware.org/?probe=148d4806cb) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Xplore        | iX104C6                     | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [17525a9aef](https://linux-hardware.org/?probe=17525a9aef) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| ASUSTek       | X540UP                      | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | Predator PT715-51           | [e187e199c9](https://linux-hardware.org/?probe=e187e199c9) | Aug 23, 2023 |
| Dell          | XPS 15 7590                 | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| Google        | Nami                        | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| Toshiba       | Satellite L515              | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [f429d18938](https://linux-hardware.org/?probe=f429d18938) | Aug 23, 2023 |
| Dell          | Inspiron 5559               | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Google        | Nami                        | [69d8c7bfb8](https://linux-hardware.org/?probe=69d8c7bfb8) | Aug 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [9ad109a4df](https://linux-hardware.org/?probe=9ad109a4df) | Aug 22, 2023 |
| HP            | Pavilion 11 x360 PC         | [bf401f98a7](https://linux-hardware.org/?probe=bf401f98a7) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Dell          | Latitude 7430               | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| Dell          | Inspiron 5567               | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| HP            | Laptop 15-fc0xxx            | [d2378787ac](https://linux-hardware.org/?probe=d2378787ac) | Aug 21, 2023 |
| Dell          | Latitude 3301               | [69389fff09](https://linux-hardware.org/?probe=69389fff09) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [63b37fd7f7](https://linux-hardware.org/?probe=63b37fd7f7) | Aug 21, 2023 |
| Lenovo        | ThinkPad T430 2347C32       | [6956f76011](https://linux-hardware.org/?probe=6956f76011) | Aug 21, 2023 |
| Dell          | Inspiron 5547               | [b5b7a6d8f8](https://linux-hardware.org/?probe=b5b7a6d8f8) | Aug 21, 2023 |
| MSI           | GE63 Raider RGB 8RF         | [dd12e382c8](https://linux-hardware.org/?probe=dd12e382c8) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713IE_G713IE     | [22443858cb](https://linux-hardware.org/?probe=22443858cb) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [359cd5a655](https://linux-hardware.org/?probe=359cd5a655) | Aug 21, 2023 |
| Dell          | Latitude 7490               | [90685f1b4d](https://linux-hardware.org/?probe=90685f1b4d) | Aug 21, 2023 |
| Lenovo        | Legion 5 82B5               | [6047cef31c](https://linux-hardware.org/?probe=6047cef31c) | Aug 21, 2023 |
| Lenovo        | Legion 5 82B5               | [986599dc77](https://linux-hardware.org/?probe=986599dc77) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| ASUSTek       | X510URR                     | [d1ee285db9](https://linux-hardware.org/?probe=d1ee285db9) | Aug 21, 2023 |
| HP            | ProBook 640 G1              | [f38ba797d9](https://linux-hardware.org/?probe=f38ba797d9) | Aug 21, 2023 |
| HP            | EliteBook 840 G6            | [9fa60a1eba](https://linux-hardware.org/?probe=9fa60a1eba) | Aug 21, 2023 |
| Toshiba       | Satellite C70-B             | [d4f90e5eff](https://linux-hardware.org/?probe=d4f90e5eff) | Aug 21, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| HP            | ProBook 430 G1              | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [448603376e](https://linux-hardware.org/?probe=448603376e) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| PC Special... | Ionico 16                   | [96fb68dc70](https://linux-hardware.org/?probe=96fb68dc70) | Aug 20, 2023 |
| Sony          | SVF1521USTW                 | [ce7fbec260](https://linux-hardware.org/?probe=ce7fbec260) | Aug 20, 2023 |
| Sony          | SVF1521USTW                 | [e92fad444f](https://linux-hardware.org/?probe=e92fad444f) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [36417c2601](https://linux-hardware.org/?probe=36417c2601) | Aug 19, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [ed572b9b04](https://linux-hardware.org/?probe=ed572b9b04) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [81dd9b9a7a](https://linux-hardware.org/?probe=81dd9b9a7a) | Aug 19, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [651f263a9d](https://linux-hardware.org/?probe=651f263a9d) | Aug 19, 2023 |
| HUAWEI        | NBM-WXX9                    | [ac85dd7bb4](https://linux-hardware.org/?probe=ac85dd7bb4) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | [c6f3f044c9](https://linux-hardware.org/?probe=c6f3f044c9) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | [9734816ff1](https://linux-hardware.org/?probe=9734816ff1) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [80b304814d](https://linux-hardware.org/?probe=80b304814d) | Aug 19, 2023 |
| HP            | Pavilion dv4                | [5f1e0c4484](https://linux-hardware.org/?probe=5f1e0c4484) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [98ebe4bf9a](https://linux-hardware.org/?probe=98ebe4bf9a) | Aug 19, 2023 |
| Dell          | Inspiron 7520               | [3cdfdae368](https://linux-hardware.org/?probe=3cdfdae368) | Aug 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dee14abe77](https://linux-hardware.org/?probe=dee14abe77) | Aug 18, 2023 |
| Acer          | Aspire A514-55              | [cace7d6efb](https://linux-hardware.org/?probe=cace7d6efb) | Aug 18, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [12c6ae9006](https://linux-hardware.org/?probe=12c6ae9006) | Aug 18, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [f7d0bbc3d9](https://linux-hardware.org/?probe=f7d0bbc3d9) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Dell          | Latitude 7320               | [a51289d9dd](https://linux-hardware.org/?probe=a51289d9dd) | Aug 18, 2023 |
| System76      | Pangolin                    | [5191e3a345](https://linux-hardware.org/?probe=5191e3a345) | Aug 18, 2023 |
| Schenker      | MEDIA (M22)                 | [463903cc03](https://linux-hardware.org/?probe=463903cc03) | Aug 18, 2023 |
| PC Special... | Ionico 16                   | [da33e8f1c1](https://linux-hardware.org/?probe=da33e8f1c1) | Aug 18, 2023 |
| MSI           | MS-1057                     | [081ae63942](https://linux-hardware.org/?probe=081ae63942) | Aug 18, 2023 |
| MSI           | MS-1057                     | [615f03f3b8](https://linux-hardware.org/?probe=615f03f3b8) | Aug 18, 2023 |
| Acer          | Aspire E5-575               | [cfbf5747b3](https://linux-hardware.org/?probe=cfbf5747b3) | Aug 18, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [df194863d1](https://linux-hardware.org/?probe=df194863d1) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [87a6bd39ae](https://linux-hardware.org/?probe=87a6bd39ae) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| HP            | ProBook 640 G1              | [e688e27904](https://linux-hardware.org/?probe=e688e27904) | Aug 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [2cd51b6fce](https://linux-hardware.org/?probe=2cd51b6fce) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [e56c46e8fe](https://linux-hardware.org/?probe=e56c46e8fe) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [c753cfdb08](https://linux-hardware.org/?probe=c753cfdb08) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [82c579f8a7](https://linux-hardware.org/?probe=82c579f8a7) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | [b0b2f8a7e1](https://linux-hardware.org/?probe=b0b2f8a7e1) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | [07b5827382](https://linux-hardware.org/?probe=07b5827382) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| ASUSTek       | X541NA                      | [8e3f72e46d](https://linux-hardware.org/?probe=8e3f72e46d) | Aug 16, 2023 |
| HP            | Laptop 17-ca0xxx            | [bbf606d6e8](https://linux-hardware.org/?probe=bbf606d6e8) | Aug 16, 2023 |
| Dell          | Latitude E5400              | [7d861c3812](https://linux-hardware.org/?probe=7d861c3812) | Aug 16, 2023 |
| Dell          | Latitude 5420               | [12d46be852](https://linux-hardware.org/?probe=12d46be852) | Aug 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | [24cd5deaa3](https://linux-hardware.org/?probe=24cd5deaa3) | Aug 16, 2023 |
| Dell          | Latitude 7490               | [efb4abea09](https://linux-hardware.org/?probe=efb4abea09) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [ff958dc821](https://linux-hardware.org/?probe=ff958dc821) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | [b42d5dec8e](https://linux-hardware.org/?probe=b42d5dec8e) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [da5582d4bf](https://linux-hardware.org/?probe=da5582d4bf) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [63f2bc3a80](https://linux-hardware.org/?probe=63f2bc3a80) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8733f22b33](https://linux-hardware.org/?probe=8733f22b33) | Aug 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS03V0... | [f50a83684f](https://linux-hardware.org/?probe=f50a83684f) | Aug 16, 2023 |
| Lenovo        | ThinkPad T550 20CJS1JT00    | [78cd2292c2](https://linux-hardware.org/?probe=78cd2292c2) | Aug 16, 2023 |
| Dell          | Latitude 3301               | [8cbe049a08](https://linux-hardware.org/?probe=8cbe049a08) | Aug 15, 2023 |
| Samsung       | 550XDA                      | [5e5606074a](https://linux-hardware.org/?probe=5e5606074a) | Aug 15, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [cfa082df13](https://linux-hardware.org/?probe=cfa082df13) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6c933602ca](https://linux-hardware.org/?probe=6c933602ca) | Aug 15, 2023 |
| Topstar       | Cantiga & ICH9M Chipset     | [5102056c71](https://linux-hardware.org/?probe=5102056c71) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [618b4d5598](https://linux-hardware.org/?probe=618b4d5598) | Aug 15, 2023 |
| Dell          | Latitude E6530              | [9cbe752127](https://linux-hardware.org/?probe=9cbe752127) | Aug 15, 2023 |
| Toshiba       | Satellite C55D-A            | [5a86eae963](https://linux-hardware.org/?probe=5a86eae963) | Aug 15, 2023 |
| Google        | Bobba360                    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [52bd9574d8](https://linux-hardware.org/?probe=52bd9574d8) | Aug 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [f99741ec7f](https://linux-hardware.org/?probe=f99741ec7f) | Aug 14, 2023 |
| Google        | Bobba360                    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| HP            | Notebook                    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [74eb1759e1](https://linux-hardware.org/?probe=74eb1759e1) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [24b85b3417](https://linux-hardware.org/?probe=24b85b3417) | Aug 14, 2023 |
| Dell          | Latitude E7470              | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| Google        | Blorb                       | [d1abf19439](https://linux-hardware.org/?probe=d1abf19439) | Aug 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| HP            | ProBook 6450b               | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| Acer          | Aspire E5-721               | [9a7018c6cb](https://linux-hardware.org/?probe=9a7018c6cb) | Aug 13, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0650746552](https://linux-hardware.org/?probe=0650746552) | Aug 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [8ef1bbdcec](https://linux-hardware.org/?probe=8ef1bbdcec) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| HP            | Pavilion Laptop 15z-eh00... | [6f54d654ac](https://linux-hardware.org/?probe=6f54d654ac) | Aug 13, 2023 |
| Toshiba       | Satellite C55D-A            | [136ac6835c](https://linux-hardware.org/?probe=136ac6835c) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| MSI           | GT62VR 7RE                  | [105839bee0](https://linux-hardware.org/?probe=105839bee0) | Aug 13, 2023 |
| Framework     | Laptop                      | [8ac155813e](https://linux-hardware.org/?probe=8ac155813e) | Aug 13, 2023 |
| Apple         | MacBookPro14,3              | [05a4c5e1ec](https://linux-hardware.org/?probe=05a4c5e1ec) | Aug 13, 2023 |
| Dell          | XPS 13 9300                 | [ed549bc47c](https://linux-hardware.org/?probe=ed549bc47c) | Aug 12, 2023 |
| HONOR         | NMH-WCX9                    | [788c2c9e31](https://linux-hardware.org/?probe=788c2c9e31) | Aug 12, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f2f4f8a844](https://linux-hardware.org/?probe=f2f4f8a844) | Aug 12, 2023 |
| HP            | Laptop 15-db0xxx            | [3d875407fc](https://linux-hardware.org/?probe=3d875407fc) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| Dell          | G15 5510                    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| Toshiba       | Satellite C55-A             | [d1bf5ba3c3](https://linux-hardware.org/?probe=d1bf5ba3c3) | Aug 12, 2023 |
| Dell          | Latitude E7270              | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [7574e6b53a](https://linux-hardware.org/?probe=7574e6b53a) | Aug 11, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [c352abad93](https://linux-hardware.org/?probe=c352abad93) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| Dell          | XPS 15 9560                 | [471e3c5077](https://linux-hardware.org/?probe=471e3c5077) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| Dell          | Latitude 5300               | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| Lenovo        | ThinkPad X220 4291SEN       | [b62026890a](https://linux-hardware.org/?probe=b62026890a) | Aug 10, 2023 |
| HP            | 250 G3                      | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| Apple         | MacBookPro5,1               | [23fc9401d3](https://linux-hardware.org/?probe=23fc9401d3) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| HP            | 14                          | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | [bb40aa6fd9](https://linux-hardware.org/?probe=bb40aa6fd9) | Aug 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0f34656484](https://linux-hardware.org/?probe=0f34656484) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Fujitsu       | UH-X                        | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Notebook                    | [bac7155006](https://linux-hardware.org/?probe=bac7155006) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Latitude 7320               | [6db1867722](https://linux-hardware.org/?probe=6db1867722) | Aug 09, 2023 |
| Acer          | Aspire E5-721               | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| Dell          | Latitude 5511               | [e9ea435e85](https://linux-hardware.org/?probe=e9ea435e85) | Aug 08, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [d989868a6b](https://linux-hardware.org/?probe=d989868a6b) | Aug 07, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [8b5e74e190](https://linux-hardware.org/?probe=8b5e74e190) | Aug 07, 2023 |
| Apple         | MacBookPro11,1              | [0a1b8d0627](https://linux-hardware.org/?probe=0a1b8d0627) | Aug 07, 2023 |
| Timi          | A7S                         | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Dell          | XPS 13 9310                 | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [eed6ad702b](https://linux-hardware.org/?probe=eed6ad702b) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [8a3ba73fae](https://linux-hardware.org/?probe=8a3ba73fae) | Aug 06, 2023 |
| Dell          | Inspiron N5110              | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [e71ac5ca78](https://linux-hardware.org/?probe=e71ac5ca78) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | [61c1a104d2](https://linux-hardware.org/?probe=61c1a104d2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | [fe15934abe](https://linux-hardware.org/?probe=fe15934abe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1b9794e2e3](https://linux-hardware.org/?probe=1b9794e2e3) | Aug 06, 2023 |
| COMPUMAX C... | MOBIL                       | [60293c1ac3](https://linux-hardware.org/?probe=60293c1ac3) | Aug 06, 2023 |
| Acer          | Aspire A715-72G             | [4afe306798](https://linux-hardware.org/?probe=4afe306798) | Aug 05, 2023 |
| Dell          | Venue 8 Pro 5855            | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude E6230              | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| Multilaser    | PC13X                       | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| Dell          | Latitude E6220              | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| System76      | Darter Pro                  | [55a328cd9a](https://linux-hardware.org/?probe=55a328cd9a) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Apple         | MacBookPro5,5               | [ccbf514dc7](https://linux-hardware.org/?probe=ccbf514dc7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq1xxx           | [e6e6cc7b2e](https://linux-hardware.org/?probe=e6e6cc7b2e) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7bc7a7e01c](https://linux-hardware.org/?probe=7bc7a7e01c) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b8fa3962ed](https://linux-hardware.org/?probe=b8fa3962ed) | Aug 04, 2023 |
| Acer          | Swift SF114-34              | [2af2b0aecb](https://linux-hardware.org/?probe=2af2b0aecb) | Aug 04, 2023 |
| Dell          | Latitude 7400               | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Dell          | Latitude 3420               | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | Latitude 5480               | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| HP            | ENVY Notebook               | [90325282da](https://linux-hardware.org/?probe=90325282da) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Latitude E6510              | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [ca0d3636a5](https://linux-hardware.org/?probe=ca0d3636a5) | Aug 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [3552dd7642](https://linux-hardware.org/?probe=3552dd7642) | Aug 03, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [620397fdc9](https://linux-hardware.org/?probe=620397fdc9) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [882d963e19](https://linux-hardware.org/?probe=882d963e19) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [38d0bcf5d1](https://linux-hardware.org/?probe=38d0bcf5d1) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| Lenovo        | Z50-70 20354                | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7df997ee08](https://linux-hardware.org/?probe=7df997ee08) | Aug 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS1RR0D    | [dcf2bedb58](https://linux-hardware.org/?probe=dcf2bedb58) | Aug 03, 2023 |
| ASUSTek       | K55VD                       | [6478fd4e76](https://linux-hardware.org/?probe=6478fd4e76) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| Dell          | Latitude E7470              | [7c8c07214a](https://linux-hardware.org/?probe=7c8c07214a) | Aug 03, 2023 |
| Toshiba       | Satellite C70-B             | [877d855f27](https://linux-hardware.org/?probe=877d855f27) | Aug 02, 2023 |
| Dell          | Inspiron 1525               | [fa53c99b17](https://linux-hardware.org/?probe=fa53c99b17) | Aug 02, 2023 |
| Dell          | Latitude E7470              | [b672c65f9b](https://linux-hardware.org/?probe=b672c65f9b) | Aug 02, 2023 |
| Acer          | Aspire A715-72G             | [d0bad7993f](https://linux-hardware.org/?probe=d0bad7993f) | Aug 02, 2023 |
| Dell          | System XPS L322X            | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| ASUSTek       | X750JN                      | [6f7dc2198b](https://linux-hardware.org/?probe=6f7dc2198b) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [517b498a25](https://linux-hardware.org/?probe=517b498a25) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Dell          | XPS 9320                    | [3abc4aaf82](https://linux-hardware.org/?probe=3abc4aaf82) | Aug 02, 2023 |
| HP            | Dragonfly Pro               | [630670f052](https://linux-hardware.org/?probe=630670f052) | Aug 01, 2023 |
| Dell          | Precision 7550              | [ab0d21bb4e](https://linux-hardware.org/?probe=ab0d21bb4e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Dell          | Inspiron 15-3573            | [e29b3656ee](https://linux-hardware.org/?probe=e29b3656ee) | Aug 01, 2023 |
| HP            | ProBook 6475b               | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| HP            | 255 G8 Notebook PC          | [b42946849e](https://linux-hardware.org/?probe=b42946849e) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| MSI           | GE75 Raider 10SE            | [995b9ae73e](https://linux-hardware.org/?probe=995b9ae73e) | Jul 31, 2023 |
| HP            | Laptop 15-dw0xxx            | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS20D00     | [4ef8aa09c6](https://linux-hardware.org/?probe=4ef8aa09c6) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Apple         | MacBookAir3,1               | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| HP            | Pavilion 15                 | [7dcc58cdf2](https://linux-hardware.org/?probe=7dcc58cdf2) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| ASUSTek       | P552LA                      | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| Dell          | XPS 13 9370                 | [529bf65ac4](https://linux-hardware.org/?probe=529bf65ac4) | Jul 30, 2023 |
| HP            | ENVY Laptop 17-cg1xxx       | [16545b3964](https://linux-hardware.org/?probe=16545b3964) | Jul 30, 2023 |
| Lenovo        | ThinkPad T490 20N3S5XF01    | [942cb3149b](https://linux-hardware.org/?probe=942cb3149b) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| Dell          | Inspiron 5577               | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| HP            | Beats 15                    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| Lenovo        | ThinkPad T490 20N20031US    | [64e178e433](https://linux-hardware.org/?probe=64e178e433) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Lenovo        | Unknown                     | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [32ad81bc5d](https://linux-hardware.org/?probe=32ad81bc5d) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| HP            | ProBook 4530s               | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| Samsung       | 550XDA                      | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| GPD           | G1621-02                    | [1710e0f480](https://linux-hardware.org/?probe=1710e0f480) | Jul 29, 2023 |
| Dell          | XPS 9320                    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Dell          | Latitude 5400               | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [75e93aaa88](https://linux-hardware.org/?probe=75e93aaa88) | Jul 28, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [730caebd96](https://linux-hardware.org/?probe=730caebd96) | Jul 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [1c3edafdf4](https://linux-hardware.org/?probe=1c3edafdf4) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | [2e6ab71954](https://linux-hardware.org/?probe=2e6ab71954) | Jul 28, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [4439f26a90](https://linux-hardware.org/?probe=4439f26a90) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | [058f75de84](https://linux-hardware.org/?probe=058f75de84) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | [c26daef72c](https://linux-hardware.org/?probe=c26daef72c) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| Acer          | Aspire A515-45              | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| Apple         | MacBookAir5,1               | [da2904da80](https://linux-hardware.org/?probe=da2904da80) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [2c2dfaa670](https://linux-hardware.org/?probe=2c2dfaa670) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| Toshiba       | Satellite C70-B             | [56489a32b2](https://linux-hardware.org/?probe=56489a32b2) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| Dell          | Latitude E6400              | [a9333607eb](https://linux-hardware.org/?probe=a9333607eb) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Dell          | Latitude E7440              | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| Dell          | Inspiron 13 5310            | [5f44d0b1d8](https://linux-hardware.org/?probe=5f44d0b1d8) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | [30cb22d368](https://linux-hardware.org/?probe=30cb22d368) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| HUAWEI        | NBM-WXX9                    | [b28bc4ba91](https://linux-hardware.org/?probe=b28bc4ba91) | Jul 25, 2023 |
| Dell          | Inspiron 3501               | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bd31324aeb](https://linux-hardware.org/?probe=bd31324aeb) | Jul 25, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [53de15710b](https://linux-hardware.org/?probe=53de15710b) | Jul 24, 2023 |
| Fujitsu       | CELSIUS H700                | [8a23e1d76a](https://linux-hardware.org/?probe=8a23e1d76a) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| MSI           | Summit E16Flip A12UCT       | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [4f06d87bd5](https://linux-hardware.org/?probe=4f06d87bd5) | Jul 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| ASUSTek       | H170M-PLUS                  | [f17fd3bbe1](https://linux-hardware.org/?probe=f17fd3bbe1) | Jul 23, 2023 |
| HP            | 250 G1                      | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| Dell          | Inspiron 5566               | [6323d6b43c](https://linux-hardware.org/?probe=6323d6b43c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [49cc99fa7e](https://linux-hardware.org/?probe=49cc99fa7e) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [994ae7ffec](https://linux-hardware.org/?probe=994ae7ffec) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9c92b34677](https://linux-hardware.org/?probe=9c92b34677) | Jul 23, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | [f12c3b23e5](https://linux-hardware.org/?probe=f12c3b23e5) | Jul 22, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| Dell          | Precision M4700             | [0a5346a25d](https://linux-hardware.org/?probe=0a5346a25d) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ba42ca5ace](https://linux-hardware.org/?probe=ba42ca5ace) | Jul 22, 2023 |
| HP            | 240 G6 Notebook PC          | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| HP            | Notebook                    | [fde29b5a32](https://linux-hardware.org/?probe=fde29b5a32) | Jul 22, 2023 |
| Notebook      | PE60RNE_RND_RNC             | [5f2993b629](https://linux-hardware.org/?probe=5f2993b629) | Jul 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Toshiba       | TECRA A50-A                 | [e96ff00334](https://linux-hardware.org/?probe=e96ff00334) | Jul 21, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Avell High... | B.ON                        | [8269a683ef](https://linux-hardware.org/?probe=8269a683ef) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Toshiba       | Satellite C70-B             | [cf2d22469b](https://linux-hardware.org/?probe=cf2d22469b) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Inspiron 15 5510            | [df2bfbf3e1](https://linux-hardware.org/?probe=df2bfbf3e1) | Jul 20, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [6bc352838a](https://linux-hardware.org/?probe=6bc352838a) | Jul 20, 2023 |
| Apple         | MacBookAir6,1               | [dd441dfa0d](https://linux-hardware.org/?probe=dd441dfa0d) | Jul 20, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [c7e1f17f9e](https://linux-hardware.org/?probe=c7e1f17f9e) | Jul 20, 2023 |
| Apple         | MacBookPro5,5               | [af457a5412](https://linux-hardware.org/?probe=af457a5412) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Dell          | Latitude 5420               | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [fc26baabc9](https://linux-hardware.org/?probe=fc26baabc9) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | [fd2864f7e1](https://linux-hardware.org/?probe=fd2864f7e1) | Jul 19, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [360ee7202f](https://linux-hardware.org/?probe=360ee7202f) | Jul 18, 2023 |
| HP            | Laptop 15-dw0xxx            | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| HP            | Notebook                    | [4498c757a7](https://linux-hardware.org/?probe=4498c757a7) | Jul 18, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [96585144ab](https://linux-hardware.org/?probe=96585144ab) | Jul 18, 2023 |
| Dell          | XPS 13 9370                 | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [fe1ab04658](https://linux-hardware.org/?probe=fe1ab04658) | Jul 18, 2023 |
| MSI           | Creator 17 A10SE            | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Unknown       | Unknown                     | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [3de307450d](https://linux-hardware.org/?probe=3de307450d) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [5633b6ed54](https://linux-hardware.org/?probe=5633b6ed54) | Jul 17, 2023 |
| HP            | Laptop 14-cf2xxx            | [04dce054f4](https://linux-hardware.org/?probe=04dce054f4) | Jul 17, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [9c1cb1fd39](https://linux-hardware.org/?probe=9c1cb1fd39) | Jul 16, 2023 |
| Gigabyte      | AORUS 17 YE5                | [9c17ae5e55](https://linux-hardware.org/?probe=9c17ae5e55) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | [999de9eeb2](https://linux-hardware.org/?probe=999de9eeb2) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6b4e2c6a3e](https://linux-hardware.org/?probe=6b4e2c6a3e) | Jul 16, 2023 |
| Compaq        | 420                         | [e5b8695df7](https://linux-hardware.org/?probe=e5b8695df7) | Jul 16, 2023 |
| MSI           | GE72MVR 7RG                 | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8c3486fa69](https://linux-hardware.org/?probe=8c3486fa69) | Jul 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | [f4bcea4686](https://linux-hardware.org/?probe=f4bcea4686) | Jul 15, 2023 |
| HP            | ZBook Power 15.6 inch G1... | [c2042a2e0e](https://linux-hardware.org/?probe=c2042a2e0e) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | [d2b32f5512](https://linux-hardware.org/?probe=d2b32f5512) | Jul 15, 2023 |
| HP            | ProBook 640 G1              | [d7512ceea8](https://linux-hardware.org/?probe=d7512ceea8) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| Dell          | G5 5505                     | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9cc25539e](https://linux-hardware.org/?probe=c9cc25539e) | Jul 15, 2023 |
| Acer          | Aspire V5-571G              | [e49b457f5b](https://linux-hardware.org/?probe=e49b457f5b) | Jul 15, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [d39c88d40a](https://linux-hardware.org/?probe=d39c88d40a) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [5fe3ea6d25](https://linux-hardware.org/?probe=5fe3ea6d25) | Jul 15, 2023 |
| Toshiba       | Satellite C70-B             | [9727ab2451](https://linux-hardware.org/?probe=9727ab2451) | Jul 14, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [62a4efa95d](https://linux-hardware.org/?probe=62a4efa95d) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d3c3cdb439](https://linux-hardware.org/?probe=d3c3cdb439) | Jul 14, 2023 |
| Acer          | Aspire V5-571G              | [e606ef8f63](https://linux-hardware.org/?probe=e606ef8f63) | Jul 14, 2023 |
| Dell          | Precision 7540              | [c862752535](https://linux-hardware.org/?probe=c862752535) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | [4c8fc2482e](https://linux-hardware.org/?probe=4c8fc2482e) | Jul 14, 2023 |
| Dell          | Latitude 7490               | [3ea6ad0e30](https://linux-hardware.org/?probe=3ea6ad0e30) | Jul 14, 2023 |
| Google        | Droid                       | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Apple         | MacBookPro8,1               | [d2d9d84e27](https://linux-hardware.org/?probe=d2d9d84e27) | Jul 13, 2023 |
| Alienware     | x15 R1                      | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | [46d98ecf9a](https://linux-hardware.org/?probe=46d98ecf9a) | Jul 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Apple         | MacBookPro10,1              | [adad96c487](https://linux-hardware.org/?probe=adad96c487) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | [d605371dc3](https://linux-hardware.org/?probe=d605371dc3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | [63f31c01af](https://linux-hardware.org/?probe=63f31c01af) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | [e84be6ee7e](https://linux-hardware.org/?probe=e84be6ee7e) | Jul 12, 2023 |
| HP            | Laptop 15t-dy200            | [ef2fb33b01](https://linux-hardware.org/?probe=ef2fb33b01) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| MSI           | Alpha 15 A4DEK              | [cbae5fed49](https://linux-hardware.org/?probe=cbae5fed49) | Jul 12, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [779f922cbb](https://linux-hardware.org/?probe=779f922cbb) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | [835e924f6d](https://linux-hardware.org/?probe=835e924f6d) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | [7bf81133fc](https://linux-hardware.org/?probe=7bf81133fc) | Jul 12, 2023 |
| MSI           | GF65 Thin 10UE              | [414c5bc2c0](https://linux-hardware.org/?probe=414c5bc2c0) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [27df8fc0e5](https://linux-hardware.org/?probe=27df8fc0e5) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eccd385af4](https://linux-hardware.org/?probe=eccd385af4) | Jul 11, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| MSI           | Katana GF66 12UC            | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Dell          | Precision 5680              | [e1363522ee](https://linux-hardware.org/?probe=e1363522ee) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| Dell          | Latitude E5540              | [cdad6cb751](https://linux-hardware.org/?probe=cdad6cb751) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9cc59dffca](https://linux-hardware.org/?probe=9cc59dffca) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| MSI           | GE66 Raider 10SFS           | [de2112a82f](https://linux-hardware.org/?probe=de2112a82f) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4e02ec47c0](https://linux-hardware.org/?probe=4e02ec47c0) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [d73ac20739](https://linux-hardware.org/?probe=d73ac20739) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [beef3128c2](https://linux-hardware.org/?probe=beef3128c2) | Jul 10, 2023 |
| HP            | EliteBook 840 G6            | [52fafabf05](https://linux-hardware.org/?probe=52fafabf05) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [cf25605b3a](https://linux-hardware.org/?probe=cf25605b3a) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [3c3c2ac038](https://linux-hardware.org/?probe=3c3c2ac038) | Jul 10, 2023 |
| Apple         | MacBookPro9,2               | [55896d87cf](https://linux-hardware.org/?probe=55896d87cf) | Jul 10, 2023 |
| Dell          | Inspiron 5515               | [0060a91b79](https://linux-hardware.org/?probe=0060a91b79) | Jul 10, 2023 |
| Dell          | Precision M4800             | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | [5e41313f45](https://linux-hardware.org/?probe=5e41313f45) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f79821f2eb](https://linux-hardware.org/?probe=f79821f2eb) | Jul 09, 2023 |
| Dell          | Latitude E6230              | [dd453671f3](https://linux-hardware.org/?probe=dd453671f3) | Jul 09, 2023 |
| Dell          | Latitude 5400               | [e8b701bf4e](https://linux-hardware.org/?probe=e8b701bf4e) | Jul 09, 2023 |
| Dell          | Latitude 5320               | [55d5b4447a](https://linux-hardware.org/?probe=55d5b4447a) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| Dell          | Latitude 7490               | [2a7f6b974b](https://linux-hardware.org/?probe=2a7f6b974b) | Jul 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| HP            | G42                         | [e215b464bf](https://linux-hardware.org/?probe=e215b464bf) | Jul 09, 2023 |
| Dell          | Latitude 3500               | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 38 | 1418      | 17.29%  |
| Fedora 36 | 1234      | 15.04%  |
| Fedora 37 | 1222      | 14.9%   |
| Fedora 35 | 969       | 11.81%  |
| Fedora 34 | 938       | 11.43%  |
| Fedora 33 | 855       | 10.42%  |
| Fedora 32 | 746       | 9.09%   |
| Fedora 31 | 503       | 6.13%   |
| Fedora 30 | 163       | 1.99%   |
| Fedora 29 | 90        | 1.1%    |
| Fedora 39 | 22        | 0.27%   |
| Fedora 28 | 22        | 0.27%   |
| Fedora 27 | 8         | 0.1%    |
| Fedora 24 | 4         | 0.05%   |
| Fedora 21 | 4         | 0.05%   |
| Fedora 40 | 3         | 0.04%   |
| Fedora 25 | 2         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 7352      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64   | 178       | 1.95%   |
| 6.2.15-300.fc38.x86_64  | 141       | 1.55%   |
| 6.3.8-200.fc38.x86_64   | 114       | 1.25%   |
| 5.17.5-300.fc36.x86_64  | 113       | 1.24%   |
| 6.4.15-200.fc38.x86_64  | 96        | 1.05%   |
| 6.0.7-301.fc37.x86_64   | 92        | 1.01%   |
| 5.16.18-200.fc35.x86_64 | 92        | 1.01%   |
| 6.2.14-300.fc38.x86_64  | 90        | 0.99%   |
| 5.9.16-200.fc33.x86_64  | 90        | 0.99%   |
| 6.2.11-300.fc38.x86_64  | 87        | 0.95%   |
| 5.11.12-300.fc34.x86_64 | 77        | 0.84%   |
| 6.0.15-300.fc37.x86_64  | 76        | 0.83%   |
| 5.14.10-300.fc35.x86_64 | 70        | 0.77%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.76%   |
| 6.3.12-200.fc38.x86_64  | 66        | 0.72%   |
| 5.8.16-300.fc33.x86_64  | 64        | 0.7%    |
| 6.1.14-200.fc37.x86_64  | 61        | 0.67%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.67%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.66%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.62%   |
| 6.1.7-200.fc37.x86_64   | 56        | 0.61%   |
| 6.4.6-200.fc38.x86_64   | 55        | 0.6%    |
| 6.0.8-300.fc37.x86_64   | 55        | 0.6%    |
| 5.13.12-200.fc34.x86_64 | 54        | 0.59%   |
| 6.0.9-300.fc37.x86_64   | 52        | 0.57%   |
| 6.1.18-200.fc37.x86_64  | 51        | 0.56%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.56%   |
| 6.4.14-200.fc38.x86_64  | 50        | 0.55%   |
| 6.3.11-200.fc38.x86_64  | 50        | 0.55%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.55%   |
| 5.19.16-200.fc36.x86_64 | 47        | 0.52%   |
| 6.4.7-200.fc38.x86_64   | 46        | 0.5%    |
| 6.3.5-200.fc38.x86_64   | 46        | 0.5%    |
| 6.2.8-200.fc37.x86_64   | 46        | 0.5%    |
| 6.2.13-300.fc38.x86_64  | 46        | 0.5%    |
| 5.8.18-300.fc33.x86_64  | 46        | 0.5%    |
| 5.17.11-300.fc36.x86_64 | 46        | 0.5%    |
| 5.14.16-301.fc35.x86_64 | 46        | 0.5%    |
| 6.4.11-200.fc38.x86_64  | 45        | 0.49%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.9   | 218       | 2.39%   |
| 6.2.15  | 172       | 1.89%   |
| 5.17.5  | 147       | 1.61%   |
| 6.3.8   | 125       | 1.37%   |
| 6.2.14  | 104       | 1.14%   |
| 6.0.7   | 102       | 1.12%   |
| 6.2.11  | 99        | 1.09%   |
| 6.4.15  | 98        | 1.08%   |
| 5.9.16  | 96        | 1.05%   |
| 5.16.18 | 95        | 1.04%   |
| 5.8.15  | 87        | 0.95%   |
| 6.0.15  | 86        | 0.94%   |
| 5.11.12 | 84        | 0.92%   |
| 5.8.16  | 81        | 0.89%   |
| 5.14.10 | 79        | 0.87%   |
| 6.0.5   | 75        | 0.82%   |
| 5.19.16 | 75        | 0.82%   |
| 6.3.12  | 69        | 0.76%   |
| 6.0.9   | 67        | 0.73%   |
| 6.0.8   | 67        | 0.73%   |
| 5.11.11 | 66        | 0.72%   |
| 6.0.12  | 65        | 0.71%   |
| 5.18.13 | 65        | 0.71%   |
| 6.1.14  | 64        | 0.7%    |
| 5.8.18  | 64        | 0.7%    |
| 6.1.7   | 61        | 0.67%   |
| 6.2.8   | 57        | 0.63%   |
| 5.8.4   | 57        | 0.63%   |
| 5.13.12 | 57        | 0.63%   |
| 6.4.6   | 56        | 0.61%   |
| 5.14.18 | 56        | 0.61%   |
| 5.18.11 | 53        | 0.58%   |
| 6.1.18  | 52        | 0.57%   |
| 5.14.16 | 52        | 0.57%   |
| 6.4.7   | 51        | 0.56%   |
| 5.9.8   | 51        | 0.56%   |
| 5.19.8  | 51        | 0.56%   |
| 6.4.14  | 50        | 0.55%   |
| 6.3.11  | 50        | 0.55%   |
| 5.17.11 | 50        | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 792       | 9.08%   |
| 6.0     | 651       | 7.46%   |
| 5.17    | 516       | 5.92%   |
| 6.4     | 491       | 5.63%   |
| 6.1     | 481       | 5.52%   |
| 5.8     | 464       | 5.32%   |
| 5.19    | 449       | 5.15%   |
| 5.11    | 449       | 5.15%   |
| 5.18    | 410       | 4.7%    |
| 6.3     | 400       | 4.59%   |
| 5.14    | 393       | 4.51%   |
| 5.16    | 384       | 4.4%    |
| 5.15    | 310       | 3.55%   |
| 5.9     | 304       | 3.49%   |
| 5.13    | 303       | 3.47%   |
| 5.10    | 294       | 3.37%   |
| 5.6     | 286       | 3.28%   |
| 5.12    | 282       | 3.23%   |
| 5.7     | 221       | 2.53%   |
| 5.3     | 194       | 2.22%   |
| 5.5     | 183       | 2.1%    |
| 5.4     | 168       | 1.93%   |
| 5.0     | 62        | 0.71%   |
| 5.2     | 47        | 0.54%   |
| 6.5     | 45        | 0.52%   |
| 5.1     | 43        | 0.49%   |
| 4.19    | 30        | 0.34%   |
| 4.18    | 27        | 0.31%   |
| 4.20    | 18        | 0.21%   |
| 6.6     | 3         | 0.03%   |
| 4.16    | 3         | 0.03%   |
| 4.15    | 3         | 0.03%   |
| 4.11    | 3         | 0.03%   |
| 4.1     | 3         | 0.03%   |
| 4.8     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.17    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7342      | 99.85%  |
| i686    | 5         | 0.07%   |
| aarch64 | 5         | 0.07%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 5605      | 74.19%  |
| KDE5            | 875       | 11.58%  |
| Unknown         | 328       | 4.34%   |
| XFCE            | 156       | 2.06%   |
| KDE             | 136       | 1.8%    |
| X-Cinnamon      | 105       | 1.39%   |
| MATE            | 89        | 1.18%   |
| Cinnamon        | 79        | 1.05%   |
| i3              | 35        | 0.46%   |
| GNOME Classic   | 26        | 0.34%   |
| LXQt            | 23        | 0.3%    |
| LXDE            | 19        | 0.25%   |
| sway            | 18        | 0.24%   |
| Deepin          | 13        | 0.17%   |
| Budgie          | 8         | 0.11%   |
| Pantheon        | 5         | 0.07%   |
| KDE4            | 4         | 0.05%   |
| Hyprland        | 4         | 0.05%   |
| fluxbox         | 4         | 0.05%   |
| awesome         | 4         | 0.05%   |
| openbox         | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| xinit-compat    | 2         | 0.03%   |
| GNOME-Classic   | 2         | 0.03%   |
| dwm             | 2         | 0.03%   |
| bspwm           | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Unity           | 1         | 0.01%   |
| qtile           | 1         | 0.01%   |
| KDE:old         | 1         | 0.01%   |
| custom          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 5140      | 67.44%  |
| X11     | 2215      | 29.06%  |
| Unknown | 211       | 2.77%   |
| Tty     | 55        | 0.72%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3916      | 51.79%  |
| GDM     | 2703      | 35.74%  |
| SDDM    | 527       | 6.97%   |
| LightDM | 299       | 3.95%   |
| TDM     | 87        | 1.15%   |
| XDM     | 10        | 0.13%   |
| LXDM    | 9         | 0.12%   |
| KDM     | 8         | 0.11%   |
| SLiM    | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3833      | 51.22%  |
| en_GB   | 524       | 7%      |
| Unknown | 371       | 4.96%   |
| ru_RU   | 356       | 4.76%   |
| pt_BR   | 351       | 4.69%   |
| de_DE   | 262       | 3.5%    |
| fr_FR   | 223       | 2.98%   |
| it_IT   | 191       | 2.55%   |
| pl_PL   | 119       | 1.59%   |
| es_ES   | 116       | 1.55%   |
| en_CA   | 104       | 1.39%   |
| en_AU   | 97        | 1.3%    |
| en_IN   | 93        | 1.24%   |
| es_MX   | 78        | 1.04%   |
| es_CL   | 52        | 0.69%   |
| cs_CZ   | 47        | 0.63%   |
| zh_CN   | 41        | 0.55%   |
| tr_TR   | 36        | 0.48%   |
| es_AR   | 35        | 0.47%   |
| es_CO   | 31        | 0.41%   |
| pt_PT   | 29        | 0.39%   |
| hu_HU   | 27        | 0.36%   |
| nl_NL   | 26        | 0.35%   |
| de_AT   | 26        | 0.35%   |
| en_DK   | 25        | 0.33%   |
| sv_SE   | 24        | 0.32%   |
| en_NZ   | 23        | 0.31%   |
| C       | 21        | 0.28%   |
| en_IE   | 18        | 0.24%   |
| ru_UA   | 17        | 0.23%   |
| en_ZA   | 17        | 0.23%   |
| fr_CA   | 16        | 0.21%   |
| es_PE   | 13        | 0.17%   |
| sk_SK   | 12        | 0.16%   |
| fr_BE   | 12        | 0.16%   |
| fi_FI   | 12        | 0.16%   |
| de_CH   | 11        | 0.15%   |
| uk_UA   | 10        | 0.13%   |
| nb_NO   | 10        | 0.13%   |
| da_DK   | 10        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 5992      | 80.42%  |
| BIOS | 1459      | 19.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 4729      | 62.91%  |
| Ext4                | 2393      | 31.83%  |
| Unknown             | 196       | 2.61%   |
| Xfs                 | 176       | 2.34%   |
| Overlay             | 12        | 0.16%   |
| Zfs                 | 3         | 0.04%   |
| F2fs                | 3         | 0.04%   |
| Ext3                | 3         | 0.04%   |
| Fuse.fuse-overlayfs | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3886      | 51.63%  |
| GPT     | 3229      | 42.9%   |
| MBR     | 411       | 5.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6769      | 91.07%  |
| Yes       | 664       | 8.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6101      | 81.98%  |
| Yes       | 1341      | 18.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 2161      | 29.39%  |
| Dell                   | 1308      | 17.79%  |
| Hewlett-Packard        | 1098      | 14.93%  |
| ASUSTek Computer       | 764       | 10.39%  |
| Acer                   | 472       | 6.42%   |
| Apple                  | 211       | 2.87%   |
| MSI                    | 172       | 2.34%   |
| HUAWEI                 | 163       | 2.22%   |
| Samsung Electronics    | 101       | 1.37%   |
| Toshiba                | 99        | 1.35%   |
| Sony                   | 58        | 0.79%   |
| Timi                   | 56        | 0.76%   |
| Notebook               | 56        | 0.76%   |
| Google                 | 39        | 0.53%   |
| Framework              | 37        | 0.5%    |
| Unknown                | 37        | 0.5%    |
| Fujitsu                | 32        | 0.44%   |
| Alienware              | 27        | 0.37%   |
| Positivo               | 25        | 0.34%   |
| System76               | 23        | 0.31%   |
| TUXEDO                 | 20        | 0.27%   |
| Razer                  | 19        | 0.26%   |
| LG Electronics         | 16        | 0.22%   |
| Gigabyte Technology    | 15        | 0.2%    |
| Chuwi                  | 15        | 0.2%    |
| HONOR                  | 14        | 0.19%   |
| Avell High Performance | 12        | 0.16%   |
| PC Specialist          | 11        | 0.15%   |
| GPU Company            | 10        | 0.14%   |
| Schenker               | 9         | 0.12%   |
| Panasonic              | 8         | 0.11%   |
| Packard Bell           | 8         | 0.11%   |
| GPD                    | 8         | 0.11%   |
| Fujitsu Siemens        | 8         | 0.11%   |
| SLIMBOOK               | 7         | 0.1%    |
| Intel Client Systems   | 6         | 0.08%   |
| Insyde                 | 6         | 0.08%   |
| Hampoo                 | 6         | 0.08%   |
| Clevo                  | 6         | 0.08%   |
| UNOWHY                 | 5         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 61        | 0.83%   |
| HP Notebook                                | 36        | 0.49%   |
| Framework Laptop                           | 29        | 0.39%   |
| Dell Latitude 7490                         | 27        | 0.37%   |
| Dell XPS 15 9570                           | 25        | 0.34%   |
| Dell XPS 13 9370                           | 25        | 0.34%   |
| Dell XPS 15 7590                           | 24        | 0.33%   |
| Apple MacBookPro9,2                        | 24        | 0.33%   |
| Dell XPS 15 9560                           | 23        | 0.31%   |
| Dell XPS 13 9310                           | 22        | 0.3%    |
| HP EliteBook 840 G6                        | 21        | 0.29%   |
| Dell XPS 15 9500                           | 19        | 0.26%   |
| Dell XPS 13 9360                           | 19        | 0.26%   |
| Dell XPS 13 7390                           | 19        | 0.26%   |
| Dell Latitude E7450                        | 19        | 0.26%   |
| HP Pavilion dv6                            | 18        | 0.24%   |
| HP Pavilion 15                             | 17        | 0.23%   |
| Dell XPS 15 9550                           | 17        | 0.23%   |
| Apple MacBookPro12,1                       | 16        | 0.22%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 15        | 0.2%    |
| HP Laptop 15-da0xxx                        | 15        | 0.2%    |
| Dell XPS 13 9300                           | 15        | 0.2%    |
| Dell Latitude E6420                        | 15        | 0.2%    |
| Apple MacBookPro8,1                        | 15        | 0.2%    |
| HUAWEI KLVL-WXX9                           | 14        | 0.19%   |
| HP Pavilion Notebook                       | 14        | 0.19%   |
| HP EliteBook 840 G3                        | 14        | 0.19%   |
| Dell XPS 13 9380                           | 14        | 0.19%   |
| Dell Latitude 5480                         | 14        | 0.19%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.18%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 13        | 0.18%   |
| HUAWEI NBLK-WAX9X                          | 13        | 0.18%   |
| Dell XPS 15 9510                           | 13        | 0.18%   |
| Dell Latitude E7440                        | 13        | 0.18%   |
| Dell Inspiron 15 7000 Gaming               | 13        | 0.18%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 13        | 0.18%   |
| Acer Nitro AN515-54                        | 13        | 0.18%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.16%   |
| HUAWEI HVY-WXX9                            | 12        | 0.16%   |
| Dell XPS 13 9350                           | 12        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1290      | 17.55%  |
| Lenovo IdeaPad     | 443       | 6.03%   |
| Dell Latitude      | 403       | 5.48%   |
| Dell Inspiron      | 364       | 4.95%   |
| Acer Aspire        | 302       | 4.11%   |
| Dell XPS           | 297       | 4.04%   |
| HP Pavilion        | 234       | 3.18%   |
| HP EliteBook       | 210       | 2.86%   |
| HP ProBook         | 167       | 2.27%   |
| ASUS VivoBook      | 165       | 2.24%   |
| HP Laptop          | 159       | 2.16%   |
| ASUS ROG           | 129       | 1.75%   |
| Dell Precision     | 105       | 1.43%   |
| Lenovo Legion      | 94        | 1.28%   |
| Lenovo ThinkBook   | 84        | 1.14%   |
| Toshiba Satellite  | 80        | 1.09%   |
| ASUS ASUS          | 71        | 0.97%   |
| Lenovo Yoga        | 66        | 0.9%    |
| Acer Nitro         | 66        | 0.9%    |
| Dell Vostro        | 62        | 0.84%   |
| ASUS Zenbook       | 61        | 0.83%   |
| Unknown            | 61        | 0.83%   |
| HP ZBook           | 55        | 0.75%   |
| HP ENVY            | 46        | 0.63%   |
| Acer Swift         | 43        | 0.58%   |
| HP OMEN            | 39        | 0.53%   |
| Apple MacBookPro11 | 38        | 0.52%   |
| Framework Laptop   | 37        | 0.5%    |
| HP Notebook        | 36        | 0.49%   |
| ASUS TUF           | 34        | 0.46%   |
| MSI Modern         | 29        | 0.39%   |
| Apple MacBookPro9  | 28        | 0.38%   |
| Fujitsu LIFEBOOK   | 26        | 0.35%   |
| Dell G5            | 23        | 0.31%   |
| Acer Predator      | 23        | 0.31%   |
| Apple MacBookPro8  | 21        | 0.29%   |
| HP 250             | 19        | 0.26%   |
| Razer Blade        | 18        | 0.24%   |
| HP 255             | 16        | 0.22%   |
| Apple MacBookPro12 | 16        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 976       | 13.28%  |
| 2019    | 914       | 12.43%  |
| 2021    | 913       | 12.42%  |
| 2018    | 762       | 10.36%  |
| 2017    | 544       | 7.4%    |
| 2022    | 436       | 5.93%   |
| 2012    | 431       | 5.86%   |
| 2015    | 422       | 5.74%   |
| 2016    | 404       | 5.5%    |
| 2013    | 392       | 5.33%   |
| 2014    | 385       | 5.24%   |
| 2011    | 311       | 4.23%   |
| 2010    | 163       | 2.22%   |
| 2008    | 100       | 1.36%   |
| 2023    | 87        | 1.18%   |
| 2009    | 77        | 1.05%   |
| 2007    | 23        | 0.31%   |
| 2006    | 6         | 0.08%   |
| Unknown | 5         | 0.07%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7352      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5860      | 78.26%  |
| Enabled  | 1628      | 21.74%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7290      | 99.16%  |
| Yes  | 62        | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2179      | 29.19%  |
| 16.01-24.0  | 1772      | 23.73%  |
| 8.01-16.0   | 1480      | 19.82%  |
| 32.01-64.0  | 844       | 11.3%   |
| 3.01-4.0    | 737       | 9.87%   |
| 24.01-32.0  | 142       | 1.9%    |
| 1.01-2.0    | 138       | 1.85%   |
| 64.01-256.0 | 132       | 1.77%   |
| 2.01-3.0    | 29        | 0.39%   |
| 0.51-1.0    | 11        | 0.15%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 2288      | 27.72%  |
| 4.01-8.0   | 2275      | 27.56%  |
| 3.01-4.0   | 1865      | 22.6%   |
| 1.01-2.0   | 1048      | 12.7%   |
| 8.01-16.0  | 602       | 7.29%   |
| 0.51-1.0   | 82        | 0.99%   |
| 16.01-24.0 | 64        | 0.78%   |
| 24.01-32.0 | 17        | 0.21%   |
| 32.01-64.0 | 7         | 0.08%   |
| 0.01-0.5   | 4         | 0.05%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5429      | 72.59%  |
| 2      | 1756      | 23.48%  |
| 3      | 207       | 2.77%   |
| 0      | 39        | 0.52%   |
| 4      | 32        | 0.43%   |
| 5      | 9         | 0.12%   |
| 6      | 6         | 0.08%   |
| 8      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5868      | 79.5%   |
| Yes       | 1513      | 20.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5447      | 73.62%  |
| No        | 1952      | 26.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7211      | 98%     |
| No        | 147       | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6221      | 83.64%  |
| No        | 1217      | 16.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1228      | 16.52%  |
| Brazil      | 535       | 7.2%    |
| Germany     | 513       | 6.9%    |
| Russia      | 489       | 6.58%   |
| Italy       | 339       | 4.56%   |
| France      | 299       | 4.02%   |
| India       | 292       | 3.93%   |
| UK          | 262       | 3.52%   |
| Poland      | 217       | 2.92%   |
| Netherlands | 210       | 2.82%   |
| Canada      | 205       | 2.76%   |
| Spain       | 180       | 2.42%   |
| Mexico      | 146       | 1.96%   |
| Turkey      | 124       | 1.67%   |
| Czechia     | 124       | 1.67%   |
| Australia   | 116       | 1.56%   |
| Austria     | 93        | 1.25%   |
| Sweden      | 92        | 1.24%   |
| Switzerland | 80        | 1.08%   |
| Portugal    | 75        | 1.01%   |
| Chile       | 69        | 0.93%   |
| Belgium     | 69        | 0.93%   |
| Indonesia   | 66        | 0.89%   |
| Hungary     | 66        | 0.89%   |
| Argentina   | 66        | 0.89%   |
| Ukraine     | 65        | 0.87%   |
| Romania     | 61        | 0.82%   |
| Norway      | 60        | 0.81%   |
| Finland     | 59        | 0.79%   |
| Colombia    | 54        | 0.73%   |
| Denmark     | 51        | 0.69%   |
| China       | 48        | 0.65%   |
| Iran        | 45        | 0.61%   |
| Bulgaria    | 40        | 0.54%   |
| Israel      | 39        | 0.52%   |
| Belarus     | 37        | 0.5%    |
| Greece      | 36        | 0.48%   |
| Slovakia    | 35        | 0.47%   |
| Philippines | 32        | 0.43%   |
| Japan       | 32        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 158       | 1.99%   |
| Sao Paulo         | 73        | 0.92%   |
| St Petersburg     | 67        | 0.84%   |
| Berlin            | 62        | 0.78%   |
| Vienna            | 60        | 0.76%   |
| Paris             | 58        | 0.73%   |
| Istanbul          | 51        | 0.64%   |
| Warsaw            | 50        | 0.63%   |
| Prague            | 50        | 0.63%   |
| Milan             | 50        | 0.63%   |
| Amsterdam         | 50        | 0.63%   |
| Madrid            | 44        | 0.55%   |
| Mexico City       | 40        | 0.5%    |
| Bengaluru         | 39        | 0.49%   |
| Munich            | 38        | 0.48%   |
| Helsinki          | 36        | 0.45%   |
| Melbourne         | 35        | 0.44%   |
| Sydney            | 33        | 0.42%   |
| Oslo              | 33        | 0.42%   |
| Budapest          | 33        | 0.42%   |
| Santiago          | 31        | 0.39%   |
| Frankfurt am Main | 30        | 0.38%   |
| Lisbon            | 29        | 0.37%   |
| Rio de Janeiro    | 28        | 0.35%   |
| Hamburg           | 27        | 0.34%   |
| Delft             | 27        | 0.34%   |
| Zurich            | 26        | 0.33%   |
| Sofia             | 26        | 0.33%   |
| Jakarta           | 26        | 0.33%   |
| Tehran            | 25        | 0.32%   |
| Montreal          | 25        | 0.32%   |
| Bucharest         | 25        | 0.32%   |
| Brasília         | 25        | 0.32%   |
| Singapore         | 24        | 0.3%    |
| Kyiv              | 24        | 0.3%    |
| Brisbane          | 24        | 0.3%    |
| Minsk             | 23        | 0.29%   |
| Pune              | 22        | 0.28%   |
| Portland          | 22        | 0.28%   |
| Delhi             | 22        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1966      | 2814   | 21.09%  |
| WDC                         | 882       | 1112   | 9.46%   |
| SanDisk                     | 718       | 928    | 7.7%    |
| Seagate                     | 659       | 863    | 7.07%   |
| Toshiba                     | 612       | 769    | 6.57%   |
| SK hynix                    | 552       | 678    | 5.92%   |
| Unknown                     | 482       | 625    | 5.17%   |
| Kingston                    | 458       | 561    | 4.91%   |
| Intel                       | 395       | 548    | 4.24%   |
| Micron Technology           | 326       | 417    | 3.5%    |
| Crucial                     | 267       | 353    | 2.86%   |
| HGST                        | 180       | 247    | 1.93%   |
| KIOXIA                      | 146       | 202    | 1.57%   |
| A-DATA Technology           | 133       | 154    | 1.43%   |
| Apple                       | 116       | 157    | 1.24%   |
| Hitachi                     | 89        | 102    | 0.95%   |
| LITEON                      | 77        | 83     | 0.83%   |
| China                       | 65        | 78     | 0.7%    |
| Phison                      | 64        | 72     | 0.69%   |
| Silicon Motion              | 63        | 80     | 0.68%   |
| Micron/Crucial Technology   | 49        | 52     | 0.53%   |
| Phison Electronics          | 42        | 44     | 0.45%   |
| ADATA Technology            | 40        | 42     | 0.43%   |
| PNY                         | 39        | 52     | 0.42%   |
| Transcend                   | 38        | 55     | 0.41%   |
| SPCC                        | 36        | 46     | 0.39%   |
| Kingston Technology Company | 34        | 37     | 0.36%   |
| LITEONIT                    | 31        | 37     | 0.33%   |
| Lenovo                      | 28        | 31     | 0.3%    |
| JMicron Technology          | 28        | 34     | 0.3%    |
| Unknown                     | 25        | 30     | 0.27%   |
| Realtek Semiconductor       | 22        | 27     | 0.24%   |
| Corsair                     | 22        | 27     | 0.24%   |
| Netac                       | 21        | 27     | 0.23%   |
| XPG                         | 18        | 27     | 0.19%   |
| Union Memory (Shenzhen)     | 18        | 29     | 0.19%   |
| Team                        | 18        | 21     | 0.19%   |
| Patriot                     | 18        | 24     | 0.19%   |
| Intenso                     | 18        | 21     | 0.19%   |
| Hewlett-Packard             | 18        | 17     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 161       | 1.65%   |
| Seagate ST1000LM035-1RK172 1TB                      | 141       | 1.44%   |
| Samsung NVMe SSD Drive 512GB                        | 113       | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 92        | 0.94%   |
| Kingston SA400S37240G 240GB SSD                     | 90        | 0.92%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 83        | 0.85%   |
| SanDisk NVMe SSD Drive 512GB                        | 81        | 0.83%   |
| HGST HTS721010A9E630 1TB                            | 77        | 0.79%   |
| Unknown MMC Card  64GB                              | 75        | 0.77%   |
| Unknown MMC Card  32GB                              | 75        | 0.77%   |
| Toshiba MQ04ABF100 1TB                              | 75        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 75        | 0.77%   |
| Kingston SA400S37480G 480GB SSD                     | 66        | 0.67%   |
| Toshiba MQ01ABD100 1TB                              | 61        | 0.62%   |
| Samsung SSD 860 EVO 500GB                           | 60        | 0.61%   |
| SK hynix NVMe SSD Drive 512GB                       | 51        | 0.52%   |
| Samsung NVMe SSD Drive 1024GB                       | 51        | 0.52%   |
| Unknown MMC Card  128GB                             | 49        | 0.5%    |
| SanDisk NVMe SSD Drive 256GB                        | 48        | 0.49%   |
| Intel NVMe SSD Drive 512GB                          | 46        | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 43        | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 43        | 0.44%   |
| Samsung SSD 850 EVO 250GB                           | 43        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                     | 42        | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 41        | 0.42%   |
| Intel SSDPEKNU512GZ 512GB                           | 41        | 0.42%   |
| Toshiba NVMe SSD Drive 512GB                        | 38        | 0.39%   |
| Seagate Expansion 1TB                               | 35        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                        | 35        | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 34        | 0.35%   |
| Samsung SSD 980 1TB                                 | 34        | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 34        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                         | 34        | 0.35%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 33        | 0.34%   |
| Samsung SSD 860 EVO 1TB                             | 33        | 0.34%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.34%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 32        | 0.33%   |
| Toshiba MQ01ABF050 500GB                            | 31        | 0.32%   |
| HGST HTS541010A9E680 1TB                            | 31        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 633       | 825    | 35.9%   |
| WDC                 | 456       | 583    | 25.87%  |
| Toshiba             | 301       | 368    | 17.07%  |
| HGST                | 180       | 247    | 10.21%  |
| Hitachi             | 89        | 102    | 5.05%   |
| Unknown             | 24        | 35     | 1.36%   |
| Samsung Electronics | 17        | 20     | 0.96%   |
| SABRENT             | 14        | 14     | 0.79%   |
| Fujitsu             | 13        | 13     | 0.74%   |
| Apple               | 13        | 14     | 0.74%   |
| External            | 4         | 6      | 0.23%   |
| USB3.0              | 2         | 2      | 0.11%   |
| LIO-ORG             | 2         | 8      | 0.11%   |
| LaCie               | 2         | 3      | 0.11%   |
| HGST HTS            | 2         | 2      | 0.11%   |
| ASMT                | 2         | 3      | 0.11%   |
| SSK                 | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QNAP                | 1         | 4      | 0.06%   |
| Phison              | 1         | 2      | 0.06%   |
| JMicron Technology  | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| IB-AC703            | 1         | 1      | 0.06%   |
| IB                  | 1         | 2      | 0.06%   |
| ACASIS              | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 690       | 978    | 24.55%  |
| Kingston            | 330       | 401    | 11.74%  |
| SanDisk             | 288       | 390    | 10.25%  |
| Crucial             | 239       | 322    | 8.5%    |
| WDC                 | 151       | 190    | 5.37%   |
| Intel               | 98        | 153    | 3.49%   |
| Micron Technology   | 92        | 112    | 3.27%   |
| A-DATA Technology   | 85        | 100    | 3.02%   |
| Apple               | 79        | 89     | 2.81%   |
| SK hynix            | 70        | 84     | 2.49%   |
| China               | 64        | 77     | 2.28%   |
| LITEON              | 62        | 68     | 2.21%   |
| Toshiba             | 60        | 77     | 2.13%   |
| PNY                 | 37        | 49     | 1.32%   |
| Transcend           | 32        | 45     | 1.14%   |
| LITEONIT            | 31        | 37     | 1.1%    |
| SPCC                | 29        | 39     | 1.03%   |
| JMicron Technology  | 20        | 25     | 0.71%   |
| Patriot             | 16        | 21     | 0.57%   |
| Netac               | 16        | 20     | 0.57%   |
| OCZ                 | 15        | 17     | 0.53%   |
| Intenso             | 15        | 17     | 0.53%   |
| Gigabyte Technology | 15        | 21     | 0.53%   |
| KingSpec            | 14        | 16     | 0.5%    |
| Corsair             | 14        | 16     | 0.5%    |
| Team                | 12        | 15     | 0.43%   |
| Lexar               | 12        | 20     | 0.43%   |
| GOODRAM             | 12        | 21     | 0.43%   |
| Apacer              | 11        | 14     | 0.39%   |
| Hewlett-Packard     | 10        | 10     | 0.36%   |
| Seagate             | 9         | 9      | 0.32%   |
| Plextor             | 7         | 11     | 0.25%   |
| Unknown             | 6         | 6      | 0.21%   |
| TO Exter            | 5         | 5      | 0.18%   |
| Ramsta              | 5         | 6      | 0.18%   |
| FORESEE             | 5         | 6      | 0.18%   |
| Unknown             | 5         | 6      | 0.18%   |
| Mushkin             | 4         | 13     | 0.14%   |
| MidasForce          | 4         | 4      | 0.14%   |
| Leven               | 4         | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3898      | 5479   | 44.41%  |
| SSD     | 2603      | 3674   | 29.66%  |
| HDD     | 1700      | 2259   | 19.37%  |
| MMC     | 455       | 597    | 5.18%   |
| Unknown | 121       | 135    | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 3896      | 5472   | 46.27%  |
| SATA | 3757      | 5661   | 44.61%  |
| MMC  | 455       | 597    | 5.4%    |
| SAS  | 313       | 414    | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2680      | 3759   | 62.5%   |
| 0.51-1.0   | 1443      | 1940   | 33.65%  |
| 1.01-2.0   | 135       | 201    | 3.15%   |
| 4.01-10.0  | 14        | 15     | 0.33%   |
| 3.01-4.0   | 11        | 12     | 0.26%   |
| 10.01-20.0 | 3         | 3      | 0.07%   |
| 2.01-3.0   | 1         | 1      | 0.02%   |
| 0          | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1699      | 22.01%  |
| 501-1000       | 1660      | 21.51%  |
| 101-250        | 1348      | 17.46%  |
| 1001-2000      | 866       | 11.22%  |
| 1-20           | 813       | 10.53%  |
| Unknown        | 560       | 7.25%   |
| 51-100         | 301       | 3.9%    |
| 21-50          | 171       | 2.22%   |
| More than 3000 | 157       | 2.03%   |
| 2001-3000      | 144       | 1.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2469      | 30.49%  |
| 21-50          | 1416      | 17.49%  |
| 101-250        | 1242      | 15.34%  |
| 51-100         | 1040      | 12.84%  |
| 251-500        | 756       | 9.34%   |
| Unknown        | 560       | 6.92%   |
| 501-1000       | 430       | 5.31%   |
| 1001-2000      | 139       | 1.72%   |
| More than 3000 | 24        | 0.3%    |
| 2001-3000      | 21        | 0.26%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 12        | 12     | 3.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 2.82%   |
| HGST HTS721010A9E630 1TB                       | 8         | 10     | 2.51%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.19%   |
| HGST HTS541010A9E680 1TB                       | 7         | 7      | 2.19%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 1.88%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 1.88%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 1.88%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 1.88%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.25%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.25%   |
| HGST HTS725050A7E630 500GB                     | 4         | 4      | 1.25%   |
| Toshiba MQ01ABF050 500GB                       | 3         | 3      | 0.94%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 0.94%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.94%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 0.94%   |
| Seagate ST1000LM049-2GH172 1TB                 | 3         | 4      | 0.94%   |
| Samsung Electronics SSD 980 1TB                | 3         | 3      | 0.94%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 0.94%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 0.94%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 0.94%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 0.63%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.63%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.63%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.63%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.63%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.63%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.63%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.63%   |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 0.63%   |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.63%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 0.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.63%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.63%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.63%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 2         | 2      | 0.63%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.63%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 83     | 20.75%  |
| Toshiba             | 34        | 35     | 10.69%  |
| WDC                 | 31        | 34     | 9.75%   |
| HGST                | 29        | 31     | 9.12%   |
| Samsung Electronics | 28        | 33     | 8.81%   |
| Hitachi             | 20        | 24     | 6.29%   |
| Micron Technology   | 15        | 18     | 4.72%   |
| Intel               | 14        | 25     | 4.4%    |
| SK hynix            | 13        | 14     | 4.09%   |
| SanDisk             | 12        | 14     | 3.77%   |
| Crucial             | 12        | 20     | 3.77%   |
| Kingston            | 9         | 11     | 2.83%   |
| A-DATA Technology   | 5         | 5      | 1.57%   |
| LITEON              | 4         | 4      | 1.26%   |
| LITEONIT            | 3         | 4      | 0.94%   |
| Fujitsu             | 3         | 3      | 0.94%   |
| SPCC                | 2         | 2      | 0.63%   |
| China               | 2         | 2      | 0.63%   |
| YS                  | 1         | 1      | 0.31%   |
| Wibtek              | 1         | 1      | 0.31%   |
| walram              | 1         | 1      | 0.31%   |
| Union Memory        | 1         | 1      | 0.31%   |
| Teclast             | 1         | 1      | 0.31%   |
| SSSTC               | 1         | 1      | 0.31%   |
| SSD                 | 1         | 1      | 0.31%   |
| PNY                 | 1         | 1      | 0.31%   |
| Plextor             | 1         | 1      | 0.31%   |
| Origin              | 1         | 1      | 0.31%   |
| OCZ-VERTEX3         | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| Lenovo              | 1         | 2      | 0.31%   |
| HGST HTS            | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 83     | 35.87%  |
| Toshiba             | 33        | 34     | 17.93%  |
| HGST                | 29        | 31     | 15.76%  |
| WDC                 | 27        | 30     | 14.67%  |
| Hitachi             | 20        | 24     | 10.87%  |
| Samsung Electronics | 4         | 4      | 2.17%   |
| Fujitsu             | 3         | 3      | 1.63%   |
| HGST HTS            | 1         | 1      | 0.54%   |
| Apple               | 1         | 1      | 0.54%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 183       | 211    | 57.91%  |
| SSD  | 107       | 139    | 33.86%  |
| NVMe | 26        | 29     | 8.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4304      | 7067   | 54.62%  |
| Works    | 3262      | 4691   | 41.4%   |
| Malfunc  | 307       | 379    | 3.9%    |
| Failed   | 7         | 7      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4452      | 48.39%  |
| Samsung Electronics                     | 1359      | 14.77%  |
| AMD                                     | 771       | 8.38%   |
| SanDisk                                 | 680       | 7.39%   |
| SK hynix                                | 468       | 5.09%   |
| Toshiba America Info Systems            | 257       | 2.79%   |
| Micron Technology                       | 236       | 2.57%   |
| Kingston Technology Company             | 163       | 1.77%   |
| KIOXIA                                  | 146       | 1.59%   |
| Phison Electronics                      | 117       | 1.27%   |
| ADATA Technology                        | 96        | 1.04%   |
| Silicon Motion                          | 81        | 0.88%   |
| Micron/Crucial Technology               | 73        | 0.79%   |
| Union Memory (Shenzhen)                 | 41        | 0.45%   |
| Solid State Storage Technology          | 34        | 0.37%   |
| Nvidia                                  | 31        | 0.34%   |
| Realtek Semiconductor                   | 29        | 0.32%   |
| Lite-On Technology                      | 29        | 0.32%   |
| Lenovo                                  | 26        | 0.28%   |
| Apple                                   | 21        | 0.23%   |
| Yangtze Memory Technologies             | 12        | 0.13%   |
| Seagate Technology                      | 11        | 0.12%   |
| MAXIO Technology (Hangzhou)             | 11        | 0.12%   |
| Marvell Technology Group                | 11        | 0.12%   |
| Shenzhen Longsys Electronics            | 10        | 0.11%   |
| Netac Technology                        | 6         | 0.07%   |
| JMicron Technology                      | 5         | 0.05%   |
| Biwin Storage Technology                | 5         | 0.05%   |
| Solidigm                                | 3         | 0.03%   |
| Shenzhen Unionmemory Information System | 3         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| INNOGRIT                                | 2         | 0.02%   |
| ASMedia Technology                      | 2         | 0.02%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 736       | 7.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 698       | 7.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 652       | 6.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 433       | 4.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 431       | 4.47%   |
| Intel Volume Management Device NVMe RAID Controller                            | 332       | 3.45%   |
| Samsung NVMe SSD Controller 980                                                | 315       | 3.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 265       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 255       | 2.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 236       | 2.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 210       | 2.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 190       | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 190       | 1.97%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 181       | 1.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 181       | 1.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 173       | 1.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 136       | 1.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 131       | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                          | 125       | 1.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 122       | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 114       | 1.18%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 109       | 1.13%   |
| Intel SSD 660P Series                                                          | 106       | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 99        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 84        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 84        | 0.87%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 82        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 80        | 0.83%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 79        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 75        | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 73        | 0.76%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 71        | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 69        | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 65        | 0.67%   |
| SK hynix BC511 NVMe SSD                                                        | 63        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 62        | 0.64%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 57        | 0.59%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 56        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 53        | 0.55%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 52        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4433      | 47.93%  |
| NVMe | 3897      | 42.13%  |
| RAID | 788       | 8.52%   |
| IDE  | 131       | 1.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 5887      | 80.07%  |
| AMD          | 1458      | 19.83%  |
| ARM          | 4         | 0.05%   |
| Unknown      | 2         | 0.03%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 183       | 2.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 168       | 2.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 153       | 2.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 150       | 2.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 120       | 1.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 119       | 1.62%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 118       | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 114       | 1.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 112       | 1.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 108       | 1.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 107       | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 101       | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 100       | 1.36%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 100       | 1.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 95        | 1.29%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 88        | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 85        | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 80        | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 74        | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 73        | 0.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 73        | 0.99%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 71        | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 70        | 0.95%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 68        | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 60        | 0.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 60        | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 56        | 0.76%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 56        | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 53        | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 51        | 0.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 50        | 0.68%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 49        | 0.67%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 49        | 0.67%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 47        | 0.64%   |
| Intel 12th Gen Core i7-12700H                 | 45        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 44        | 0.6%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 44        | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 43        | 0.58%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 43        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 43        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 2074      | 28.2%   |
| Intel Core i5                  | 1805      | 24.54%  |
| Other                          | 916       | 12.45%  |
| AMD Ryzen 5                    | 457       | 6.21%   |
| AMD Ryzen 7                    | 440       | 5.98%   |
| Intel Core i3                  | 432       | 5.87%   |
| Intel Celeron                  | 189       | 2.57%   |
| Intel Core 2 Duo               | 127       | 1.73%   |
| Intel Atom                     | 113       | 1.54%   |
| AMD Ryzen 9                    | 106       | 1.44%   |
| AMD Ryzen 7 PRO                | 101       | 1.37%   |
| Intel Pentium                  | 82        | 1.11%   |
| AMD Ryzen 3                    | 66        | 0.9%    |
| Intel Core i9                  | 60        | 0.82%   |
| AMD Ryzen 5 PRO                | 53        | 0.72%   |
| AMD A6                         | 43        | 0.58%   |
| AMD A10                        | 38        | 0.52%   |
| AMD A8                         | 31        | 0.42%   |
| Intel Pentium Silver           | 27        | 0.37%   |
| AMD A4                         | 22        | 0.3%    |
| Intel Xeon                     | 17        | 0.23%   |
| Intel Pentium Dual-Core        | 15        | 0.2%    |
| AMD E1                         | 14        | 0.19%   |
| AMD A12                        | 11        | 0.15%   |
| Intel Pentium Dual             | 10        | 0.14%   |
| Intel Core m3                  | 10        | 0.14%   |
| AMD Athlon                     | 10        | 0.14%   |
| Intel Core m5                  | 9         | 0.12%   |
| AMD E                          | 8         | 0.11%   |
| Intel Genuine                  | 7         | 0.1%    |
| Intel Core M                   | 6         | 0.08%   |
| AMD E2                         | 6         | 0.08%   |
| Intel Core m7                  | 5         | 0.07%   |
| Intel Core 2                   | 4         | 0.05%   |
| Intel Celeron Dual-Core        | 4         | 0.05%   |
| AMD PRO A10                    | 4         | 0.05%   |
| AMD Phenom II                  | 4         | 0.05%   |
| AMD Athlon II                  | 4         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.04%   |
| AMD FX                         | 3         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 2915      | 39.63%  |
| 2       | 2661      | 36.18%  |
| 8       | 738       | 10.03%  |
| 6       | 735       | 9.99%   |
| 12      | 99        | 1.35%   |
| 14      | 94        | 1.28%   |
| 10      | 74        | 1.01%   |
| 1       | 24        | 0.33%   |
| 16      | 7         | 0.1%    |
| 24      | 4         | 0.05%   |
| 3       | 2         | 0.03%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 7351      | 99.97%  |
| 2       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6453      | 87.65%  |
| 1       | 908       | 12.33%  |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7214      | 97.84%  |
| Unknown        | 151       | 2.05%   |
| 64-bit         | 4         | 0.05%   |
| 32-bit         | 4         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1610      | 21.2%   |
| 0x806ec    | 398       | 5.24%   |
| 0x806ea    | 382       | 5.03%   |
| 0x306a9    | 356       | 4.69%   |
| 0x806c1    | 349       | 4.6%    |
| 0x206a7    | 278       | 3.66%   |
| 0x906ea    | 272       | 3.58%   |
| 0x406e3    | 272       | 3.58%   |
| 0x806e9    | 269       | 3.54%   |
| 0x40651    | 221       | 2.91%   |
| 0x0a50000c | 221       | 2.91%   |
| 0x306d4    | 215       | 2.83%   |
| 0x306c3    | 168       | 2.21%   |
| 0xa0652    | 164       | 2.16%   |
| 0x08600106 | 143       | 1.88%   |
| 0x08108109 | 129       | 1.7%    |
| 0x08108102 | 122       | 1.61%   |
| 0x906e9    | 118       | 1.55%   |
| 0x506e3    | 111       | 1.46%   |
| 0x08608103 | 110       | 1.45%   |
| 0x706e5    | 104       | 1.37%   |
| 0x906a3    | 88        | 1.16%   |
| 0x08600104 | 83        | 1.09%   |
| 0x20655    | 81        | 1.07%   |
| 0x806eb    | 75        | 0.99%   |
| 0x30678    | 75        | 0.99%   |
| 0x1067a    | 70        | 0.92%   |
| 0x0a404102 | 65        | 0.86%   |
| 0x806d1    | 61        | 0.8%    |
| 0x906ed    | 56        | 0.74%   |
| 0x08600103 | 52        | 0.68%   |
| 0x0a50000d | 45        | 0.59%   |
| 0x406c4    | 42        | 0.55%   |
| 0x0810100b | 41        | 0.54%   |
| 0x0a404101 | 37        | 0.49%   |
| 0x08608102 | 35        | 0.46%   |
| 0x706a8    | 34        | 0.45%   |
| 0x06006705 | 32        | 0.42%   |
| 0x406c3    | 30        | 0.4%    |
| 0x906a4    | 29        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1927      | 26.19%  |
| TigerLake        | 519       | 7.05%   |
| Haswell          | 506       | 6.88%   |
| Skylake          | 475       | 6.45%   |
| IvyBridge        | 446       | 6.06%   |
| SandyBridge      | 341       | 4.63%   |
| Zen 2            | 327       | 4.44%   |
| Unknown          | 310       | 4.21%   |
| Zen 3            | 295       | 4.01%   |
| Alderlake Hybrid | 269       | 3.66%   |
| Zen+             | 260       | 3.53%   |
| Broadwell        | 258       | 3.51%   |
| CometLake        | 234       | 3.18%   |
| IceLake          | 220       | 2.99%   |
| Silvermont       | 201       | 2.73%   |
| Westmere         | 144       | 1.96%   |
| Penryn           | 128       | 1.74%   |
| Goldmont plus    | 85        | 1.16%   |
| Zen              | 78        | 1.06%   |
| Excavator        | 71        | 0.96%   |
| Core             | 39        | 0.53%   |
| Piledriver       | 36        | 0.49%   |
| Goldmont         | 36        | 0.49%   |
| Puma             | 34        | 0.46%   |
| Jaguar           | 22        | 0.3%    |
| Nehalem          | 19        | 0.26%   |
| Bobcat           | 16        | 0.22%   |
| Tremont          | 14        | 0.19%   |
| K10              | 12        | 0.16%   |
| Steamroller      | 9         | 0.12%   |
| K10 Llano        | 9         | 0.12%   |
| Bonnell          | 6         | 0.08%   |
| K8 & K10 hybrid  | 5         | 0.07%   |
| K8 Hammer        | 4         | 0.05%   |
| P6               | 3         | 0.04%   |
| NetBurst         | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5555      | 57.52%  |
| Nvidia                           | 2306      | 23.88%  |
| AMD                              | 1795      | 18.59%  |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 476       | 4.84%   |
| Intel UHD Graphics 620                                                                   | 455       | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 414       | 4.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 338       | 3.44%   |
| AMD Renoir                                                                               | 318       | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 315       | 3.2%    |
| Intel HD Graphics 620                                                                    | 313       | 3.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 304       | 3.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 295       | 3%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 268       | 2.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 262       | 2.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 260       | 2.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 234       | 2.38%   |
| Intel HD Graphics 5500                                                                   | 221       | 2.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 196       | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 189       | 1.92%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 161       | 1.64%   |
| AMD Lucienne                                                                             | 154       | 1.57%   |
| Intel HD Graphics 630                                                                    | 131       | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 123       | 1.25%   |
| Intel HD Graphics 530                                                                    | 112       | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 112       | 1.14%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 111       | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 110       | 1.12%   |
| AMD Rembrandt [Radeon 680M]                                                              | 106       | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 95        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 94        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 89        | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 89        | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 86        | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 83        | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 74        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 72        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 71        | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 64        | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 63        | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 63        | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 56        | 0.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 56        | 0.57%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 53        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3504      | 47.47%  |
| Intel + Nvidia     | 1761      | 23.86%  |
| 1 x AMD            | 1132      | 15.33%  |
| 1 x Nvidia         | 286       | 3.87%   |
| Intel + AMD        | 273       | 3.7%    |
| AMD + Nvidia       | 262       | 3.55%   |
| 2 x AMD            | 130       | 1.76%   |
| 2 x Intel          | 16        | 0.22%   |
| Other              | 11        | 0.15%   |
| 2 x Nvidia         | 3         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x Zhaoxin        | 1         | 0.01%   |
| 1 x SiS            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6303      | 84.66%  |
| Proprietary | 1026      | 13.78%  |
| Unknown     | 116       | 1.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4588      | 61.08%  |
| 1.01-2.0   | 954       | 12.7%   |
| 0.01-0.5   | 798       | 10.62%  |
| 3.01-4.0   | 509       | 6.78%   |
| 0.51-1.0   | 404       | 5.38%   |
| 5.01-6.0   | 112       | 1.49%   |
| 7.01-8.0   | 95        | 1.26%   |
| 8.01-16.0  | 26        | 0.35%   |
| 2.01-3.0   | 25        | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1536      | 16.99%  |
| BOE                     | 1384      | 15.31%  |
| Chimei Innolux          | 1222      | 13.52%  |
| LG Display              | 1148      | 12.7%   |
| Samsung Electronics     | 711       | 7.87%   |
| Dell                    | 420       | 4.65%   |
| Sharp                   | 374       | 4.14%   |
| Goldstar                | 274       | 3.03%   |
| Apple                   | 211       | 2.33%   |
| Lenovo                  | 187       | 2.07%   |
| PANDA                   | 168       | 1.86%   |
| Hewlett-Packard         | 145       | 1.6%    |
| CSO                     | 109       | 1.21%   |
| Chi Mei Optoelectronics | 93        | 1.03%   |
| BenQ                    | 93        | 1.03%   |
| AOC                     | 92        | 1.02%   |
| Acer                    | 92        | 1.02%   |
| Philips                 | 91        | 1.01%   |
| InfoVision              | 83        | 0.92%   |
| Ancor Communications    | 65        | 0.72%   |
| Iiyama                  | 43        | 0.48%   |
| TMX                     | 39        | 0.43%   |
| ViewSonic               | 37        | 0.41%   |
| ASUSTek Computer        | 37        | 0.41%   |
| Panasonic               | 22        | 0.24%   |
| Sony                    | 20        | 0.22%   |
| Toshiba                 | 19        | 0.21%   |
| LG Philips              | 19        | 0.21%   |
| JDI                     | 19        | 0.21%   |
| MSI                     | 17        | 0.19%   |
| Gigabyte Technology     | 12        | 0.13%   |
| Sceptre Tech            | 11        | 0.12%   |
| CPT                     | 11        | 0.12%   |
| NEC Computers           | 10        | 0.11%   |
| Vizio                   | 9         | 0.1%    |
| HannStar                | 9         | 0.1%    |
| Eizo                    | 9         | 0.1%    |
| Fujitsu Siemens         | 8         | 0.09%   |
| Vestel Elektronik       | 7         | 0.08%   |
| RTK                     | 7         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 75        | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 62        | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 57        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 55        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 54        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 51        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 46        | 0.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 43        | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 42        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 40        | 0.44%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 40        | 0.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 38        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 38        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 36        | 0.39%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 32        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 32        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 31        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 31        | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 28        | 0.3%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 28        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 26        | 0.28%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 26        | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 26        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 25        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 25        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 25        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 25        | 0.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 25        | 0.27%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 25        | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 24        | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 24        | 0.26%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 24        | 0.26%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 23        | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 23        | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 23        | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 23        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 23        | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 22        | 0.24%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 22        | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 22        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4180      | 50.36%  |
| 1366x768 (WXGA)    | 1608      | 19.37%  |
| 3840x2160 (4K)     | 481       | 5.8%    |
| 2560x1440 (QHD)    | 358       | 4.31%   |
| 1600x900 (HD+)     | 271       | 3.27%   |
| 1920x1200 (WUXGA)  | 253       | 3.05%   |
| 2560x1600          | 177       | 2.13%   |
| 1280x800 (WXGA)    | 139       | 1.67%   |
| 2880x1800          | 113       | 1.36%   |
| 2560x1080          | 81        | 0.98%   |
| 1440x900 (WXGA+)   | 80        | 0.96%   |
| 3440x1440          | 78        | 0.94%   |
| 3840x2400          | 60        | 0.72%   |
| 2160x1440          | 53        | 0.64%   |
| 1680x1050 (WSXGA+) | 49        | 0.59%   |
| 2256x1504          | 42        | 0.51%   |
| 1280x1024 (SXGA)   | 37        | 0.45%   |
| 3200x1800 (QHD+)   | 36        | 0.43%   |
| 3000x2000          | 19        | 0.23%   |
| 1360x768           | 19        | 0.23%   |
| 3200x2000          | 16        | 0.19%   |
| 2520x1680          | 14        | 0.17%   |
| 2240x1400          | 14        | 0.17%   |
| 3456x2160          | 11        | 0.13%   |
| 3072x1920          | 11        | 0.13%   |
| 1920x1280          | 11        | 0.13%   |
| 2160x1350          | 10        | 0.12%   |
| 3840x1600          | 9         | 0.11%   |
| 3840x1080          | 7         | 0.08%   |
| 2880x1620          | 7         | 0.08%   |
| 1024x768 (XGA)     | 7         | 0.08%   |
| 1920x540           | 6         | 0.07%   |
| 1024x600           | 5         | 0.06%   |
| 3840x1100          | 4         | 0.05%   |
| 2304x1440          | 3         | 0.04%   |
| 2288x1287          | 3         | 0.04%   |
| 1680x945           | 3         | 0.04%   |
| Unknown            | 3         | 0.04%   |
| 800x1280           | 2         | 0.02%   |
| 2880x1920          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3332      | 36.85%  |
| 13      | 1457      | 16.11%  |
| 14      | 1277      | 14.12%  |
| 17      | 432       | 4.78%   |
| 27      | 426       | 4.71%   |
| 24      | 408       | 4.51%   |
| 23      | 277       | 3.06%   |
| 12      | 236       | 2.61%   |
| 21      | 222       | 2.46%   |
| 16      | 172       | 1.9%    |
| 34      | 137       | 1.52%   |
| 31      | 92        | 1.02%   |
| 11      | 82        | 0.91%   |
| 18      | 80        | 0.88%   |
| 19      | 45        | 0.5%    |
| 20      | 38        | 0.42%   |
| 22      | 31        | 0.34%   |
| Unknown | 29        | 0.32%   |
| 25      | 27        | 0.3%    |
| 40      | 26        | 0.29%   |
| 84      | 23        | 0.25%   |
| 32      | 18        | 0.2%    |
| 35      | 15        | 0.17%   |
| 28      | 15        | 0.17%   |
| 54      | 14        | 0.15%   |
| 10      | 14        | 0.15%   |
| 72      | 13        | 0.14%   |
| 29      | 13        | 0.14%   |
| 26      | 13        | 0.14%   |
| 37      | 10        | 0.11%   |
| 48      | 7         | 0.08%   |
| 86      | 5         | 0.06%   |
| 42      | 5         | 0.06%   |
| 39      | 5         | 0.06%   |
| 74      | 4         | 0.04%   |
| 52      | 4         | 0.04%   |
| 33      | 4         | 0.04%   |
| 63      | 3         | 0.03%   |
| 57      | 3         | 0.03%   |
| 46      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5438      | 60.81%  |
| 201-300        | 1033      | 11.55%  |
| 501-600        | 1029      | 11.51%  |
| 351-400        | 533       | 5.96%   |
| 401-500        | 390       | 4.36%   |
| 601-700        | 166       | 1.86%   |
| 701-800        | 162       | 1.81%   |
| 801-900        | 59        | 0.66%   |
| 1001-1500      | 47        | 0.53%   |
| 1501-2000      | 43        | 0.48%   |
| Unknown        | 29        | 0.32%   |
| 901-1000       | 8         | 0.09%   |
| More than 2000 | 2         | 0.02%   |
| 1-100          | 2         | 0.02%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6276      | 81.92%  |
| 16/10   | 961       | 12.54%  |
| 21/9    | 170       | 2.22%   |
| 3/2     | 156       | 2.04%   |
| 5/4     | 39        | 0.51%   |
| 4/3     | 15        | 0.2%    |
| Unknown | 12        | 0.16%   |
| 32/9    | 11        | 0.14%   |
| 0.56    | 6         | 0.08%   |
| 3.40    | 4         | 0.05%   |
| 6/5     | 2         | 0.03%   |
| 1.00    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3335      | 36.97%  |
| 81-90          | 2191      | 24.29%  |
| 201-250        | 735       | 8.15%   |
| 71-80          | 525       | 5.82%   |
| 301-350        | 440       | 4.88%   |
| 121-130        | 388       | 4.3%    |
| 351-500        | 281       | 3.12%   |
| 61-70          | 227       | 2.52%   |
| 251-300        | 167       | 1.85%   |
| 111-120        | 165       | 1.83%   |
| 151-200        | 140       | 1.55%   |
| 51-60          | 86        | 0.95%   |
| 141-150        | 85        | 0.94%   |
| More than 1000 | 81        | 0.9%    |
| 501-1000       | 66        | 0.73%   |
| 131-140        | 36        | 0.4%    |
| Unknown        | 29        | 0.32%   |
| 91-100         | 25        | 0.28%   |
| 41-50          | 14        | 0.16%   |
| 1-40           | 4         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3960      | 44.94%  |
| 101-120       | 1968      | 22.34%  |
| 51-100        | 1356      | 15.39%  |
| 161-240       | 971       | 11.02%  |
| More than 240 | 464       | 5.27%   |
| 1-50          | 63        | 0.72%   |
| Unknown       | 29        | 0.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5566      | 73.05%  |
| 2     | 1638      | 21.5%   |
| 3     | 223       | 2.93%   |
| 0     | 174       | 2.28%   |
| 4     | 15        | 0.2%    |
| 5     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4426      | 39.71%  |
| Realtek Semiconductor             | 3674      | 32.97%  |
| Qualcomm Atheros                  | 1193      | 10.7%   |
| Broadcom                          | 511       | 4.59%   |
| MediaTek                          | 278       | 2.49%   |
| Broadcom Limited                  | 118       | 1.06%   |
| Lenovo                            | 103       | 0.92%   |
| ASIX Electronics                  | 82        | 0.74%   |
| TP-Link                           | 70        | 0.63%   |
| Sierra Wireless                   | 69        | 0.62%   |
| Qualcomm                          | 58        | 0.52%   |
| DisplayLink                       | 47        | 0.42%   |
| Dell                              | 47        | 0.42%   |
| Ralink                            | 45        | 0.4%    |
| Marvell Technology Group          | 39        | 0.35%   |
| Ralink Technology                 | 36        | 0.32%   |
| Samsung Electronics               | 34        | 0.31%   |
| Ericsson Business Mobile Networks | 31        | 0.28%   |
| Hewlett-Packard                   | 29        | 0.26%   |
| Xiaomi                            | 27        | 0.24%   |
| Nvidia                            | 23        | 0.21%   |
| Huawei Technologies               | 20        | 0.18%   |
| ASUSTek Computer                  | 16        | 0.14%   |
| Apple                             | 15        | 0.13%   |
| Google                            | 14        | 0.13%   |
| Fibocom                           | 11        | 0.1%    |
| OPPO Electronics                  | 10        | 0.09%   |
| NetGear                           | 10        | 0.09%   |
| JMicron Technology                | 10        | 0.09%   |
| Qualcomm Atheros Communications   | 9         | 0.08%   |
| D-Link                            | 7         | 0.06%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| Microsoft                         | 6         | 0.05%   |
| Linksys                           | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.04%   |
| Edimax Technology                 | 5         | 0.04%   |
| D-Link System                     | 5         | 0.04%   |
| Motorola PCS                      | 4         | 0.04%   |
| Cypress Semiconductor             | 4         | 0.04%   |
| Shenzhen Goodix Technology        | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2285      | 16.83%  |
| Intel Wi-Fi 6 AX200                                               | 509       | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 465       | 3.43%   |
| Intel Wireless 8265 / 8275                                        | 462       | 3.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 417       | 3.07%   |
| Intel Wi-Fi 6 AX201                                               | 400       | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 291       | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 261       | 1.92%   |
| Intel Wireless 8260                                               | 257       | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 253       | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 238       | 1.75%   |
| Intel Wireless 7260                                               | 234       | 1.72%   |
| Intel Wireless 7265                                               | 231       | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 216       | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 195       | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 188       | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 187       | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 187       | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 185       | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 185       | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 182       | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 174       | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 153       | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 148       | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 124       | 0.91%   |
| Intel Wireless 3165                                               | 119       | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 116       | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 100       | 0.74%   |
| Intel Wireless-AC 9260                                            | 99        | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 95        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 93        | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 89        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 86        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 83        | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 81        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 81        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 79        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 75        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 75        | 0.55%   |
| Intel Wireless 3160                                               | 74        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4303      | 56.98%  |
| Qualcomm Atheros                      | 1048      | 13.88%  |
| Realtek Semiconductor                 | 1042      | 13.8%   |
| Broadcom                              | 427       | 5.65%   |
| MediaTek                              | 271       | 3.59%   |
| Broadcom Limited                      | 93        | 1.23%   |
| Sierra Wireless                       | 69        | 0.91%   |
| TP-Link                               | 51        | 0.68%   |
| Ralink                                | 45        | 0.6%    |
| Qualcomm                              | 45        | 0.6%    |
| Ralink Technology                     | 36        | 0.48%   |
| Dell                                  | 35        | 0.46%   |
| ASUSTek Computer                      | 15        | 0.2%    |
| Fibocom                               | 11        | 0.15%   |
| Qualcomm Atheros Communications       | 9         | 0.12%   |
| NetGear                               | 9         | 0.12%   |
| Hewlett-Packard                       | 9         | 0.12%   |
| Linksys                               | 5         | 0.07%   |
| Edimax Technology                     | 5         | 0.07%   |
| D-Link System                         | 5         | 0.07%   |
| Microsoft                             | 4         | 0.05%   |
| D-Link                                | 4         | 0.05%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Belkin Components                     | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| AVM                                   | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 509       | 6.7%    |
| Intel Wireless 8265 / 8275                                     | 462       | 6.08%   |
| Intel Wi-Fi 6 AX201                                            | 400       | 5.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 291       | 3.83%   |
| Intel Wireless 8260                                            | 257       | 3.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 253       | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 238       | 3.13%   |
| Intel Wireless 7260                                            | 234       | 3.08%   |
| Intel Wireless 7265                                            | 231       | 3.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 216       | 2.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 195       | 2.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 188       | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 187       | 2.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 185       | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 185       | 2.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 185       | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 182       | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 153       | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 148       | 1.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 124       | 1.63%   |
| Intel Wireless 3165                                            | 119       | 1.57%   |
| Intel Wireless-AC 9260                                         | 99        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 95        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 93        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 89        | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 86        | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 81        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                  | 81        | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 79        | 1.04%   |
| Intel Wireless 3160                                            | 74        | 0.97%   |
| Intel Centrino Ultimate-N 6300                                 | 74        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 71        | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 62        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 58        | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 58        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 52        | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 51        | 0.67%   |
| Intel Centrino Advanced-N 6235                                 | 50        | 0.66%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 42        | 0.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 42        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3239      | 55.94%  |
| Intel                                  | 1616      | 27.91%  |
| Qualcomm Atheros                       | 247       | 4.27%   |
| Broadcom                               | 167       | 2.88%   |
| Lenovo                                 | 101       | 1.74%   |
| ASIX Electronics                       | 82        | 1.42%   |
| DisplayLink                            | 47        | 0.81%   |
| Marvell Technology Group               | 39        | 0.67%   |
| Samsung Electronics                    | 34        | 0.59%   |
| Xiaomi                                 | 27        | 0.47%   |
| Broadcom Limited                       | 25        | 0.43%   |
| Nvidia                                 | 23        | 0.4%    |
| TP-Link                                | 21        | 0.36%   |
| Apple                                  | 15        | 0.26%   |
| Google                                 | 14        | 0.24%   |
| Qualcomm                               | 13        | 0.22%   |
| Huawei Technologies                    | 12        | 0.21%   |
| OPPO Electronics                       | 10        | 0.17%   |
| JMicron Technology                     | 10        | 0.17%   |
| MediaTek                               | 7         | 0.12%   |
| Hewlett-Packard                        | 7         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.07%   |
| Cypress Semiconductor                  | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |
| ICS Advent                             | 2         | 0.03%   |
| vivo                                   | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| Foxconn / Hon Hai                      | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2285      | 38.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 465       | 7.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 417       | 7.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 261       | 4.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 174       | 2.96%   |
| Intel Ethernet Connection I219-LM                                 | 116       | 1.97%   |
| Intel Ethernet Connection (4) I219-V                              | 100       | 1.7%    |
| Intel Ethernet Connection I218-LM                                 | 83        | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 75        | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 75        | 1.27%   |
| Intel Ethernet Connection (6) I219-V                              | 74        | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 61        | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 60        | 1.02%   |
| Intel Ethernet Connection (10) I219-V                             | 58        | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 49        | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 48        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 48        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 41        | 0.7%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 40        | 0.68%   |
| Intel Ethernet Connection I219-V                                  | 40        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 38        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 36        | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 35        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 29        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 0.49%   |
| Intel Ethernet Connection (16) I219-V                             | 29        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 27        | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 25        | 0.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 25        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 23        | 0.39%   |
| Intel 82567LM Gigabit Network Connection                          | 23        | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 22        | 0.37%   |
| Nvidia MCP79 Ethernet                                             | 20        | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.34%   |
| Intel Ethernet Connection (10) I219-LM                            | 20        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7211      | 56.58%  |
| Ethernet | 5441      | 42.69%  |
| Modem    | 81        | 0.64%   |
| Unknown  | 11        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6237      | 79.72%  |
| Ethernet | 1585      | 20.26%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4844      | 65.82%  |
| 1     | 2289      | 31.1%   |
| 0     | 142       | 1.93%   |
| 3     | 84        | 1.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 5965      | 79.51%  |
| Yes     | 1534      | 20.45%  |
| Unknown | 3         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3595      | 57.29%  |
| Realtek Semiconductor           | 628       | 10.01%  |
| Qualcomm Atheros Communications | 531       | 8.46%   |
| IMC Networks                    | 271       | 4.32%   |
| Foxconn / Hon Hai               | 252       | 4.02%   |
| Broadcom                        | 249       | 3.97%   |
| Lite-On Technology              | 220       | 3.51%   |
| Apple                           | 180       | 2.87%   |
| Realtek                         | 75        | 1.2%    |
| Dell                            | 45        | 0.72%   |
| Cambridge Silicon Radio         | 44        | 0.7%    |
| Hewlett-Packard                 | 34        | 0.54%   |
| Ralink                          | 31        | 0.49%   |
| Toshiba                         | 26        | 0.41%   |
| ASUSTek Computer                | 19        | 0.3%    |
| USI                             | 14        | 0.22%   |
| Foxconn International           | 14        | 0.22%   |
| Opticis                         | 12        | 0.19%   |
| MediaTek                        | 10        | 0.16%   |
| Ralink Technology               | 4         | 0.06%   |
| Smart Modular Technologies      | 3         | 0.05%   |
| Chicony Electronics             | 3         | 0.05%   |
| Askey Computer                  | 3         | 0.05%   |
| Alps Electric                   | 3         | 0.05%   |
| Taiyo Yuden                     | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| TP-Link                         | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1259      | 20.04%  |
| Intel AX201 Bluetooth                               | 782       | 12.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 550       | 8.76%   |
| Intel AX200 Bluetooth                               | 498       | 7.93%   |
| Realtek Bluetooth Radio                             | 404       | 6.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 309       | 4.92%   |
| Intel Bluetooth Device                              | 155       | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 139       | 2.21%   |
| Intel AX210 Bluetooth                               | 119       | 1.89%   |
| Apple Bluetooth Host Controller                     | 118       | 1.88%   |
| IMC Networks Wireless_Device                        | 111       | 1.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 87        | 1.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 87        | 1.38%   |
| IMC Networks Bluetooth Radio                        | 82        | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 78        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 78        | 1.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 77        | 1.23%   |
| Realtek Bluetooth Radio                             | 75        | 1.19%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 65        | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 0.89%   |
| Lite-On Bluetooth Device                            | 51        | 0.81%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 50        | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 48        | 0.76%   |
| Apple Bluetooth USB Host Controller                 | 46        | 0.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 44        | 0.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 43        | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 42        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 40        | 0.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 0.62%   |
| IMC Networks Bluetooth Device                       | 37        | 0.59%   |
| Ralink RT3290 Bluetooth                             | 31        | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 29        | 0.46%   |
| Lite-On Wireless_Device                             | 28        | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 23        | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.37%   |
| Dell DW375 Bluetooth Module                         | 20        | 0.32%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.3%    |
| Broadcom HP Portable SoftSailing                    | 19        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 5740      | 60.52%  |
| AMD                         | 1550      | 16.34%  |
| Nvidia                      | 1273      | 13.42%  |
| Lenovo                      | 124       | 1.31%   |
| C-Media Electronics         | 94        | 0.99%   |
| Realtek Semiconductor       | 90        | 0.95%   |
| Logitech                    | 68        | 0.72%   |
| GN Netcom                   | 67        | 0.71%   |
| Plantronics                 | 41        | 0.43%   |
| JMTek                       | 31        | 0.33%   |
| Hewlett-Packard             | 31        | 0.33%   |
| Kingston Technology         | 22        | 0.23%   |
| Texas Instruments           | 19        | 0.2%    |
| Creative Technology         | 17        | 0.18%   |
| SteelSeries ApS             | 15        | 0.16%   |
| Sony                        | 14        | 0.15%   |
| Razer USA                   | 14        | 0.15%   |
| Corsair                     | 13        | 0.14%   |
| Dell                        | 12        | 0.13%   |
| ASUSTek Computer            | 12        | 0.13%   |
| Apple                       | 11        | 0.12%   |
| Sennheiser Communications   | 10        | 0.11%   |
| Generalplus Technology      | 10        | 0.11%   |
| Blue Microphones            | 10        | 0.11%   |
| Samson Technologies         | 9         | 0.09%   |
| Microsoft                   | 9         | 0.09%   |
| Focusrite-Novation          | 9         | 0.09%   |
| RODE Microphones            | 8         | 0.08%   |
| Conexant Systems            | 8         | 0.08%   |
| Samsung Electronics         | 7         | 0.07%   |
| No brand                    | 7         | 0.07%   |
| XMOS                        | 6         | 0.06%   |
| CMX Systems                 | 6         | 0.06%   |
| SAVITECH                    | 5         | 0.05%   |
| GYROCOM C&C                 | 5         | 0.05%   |
| FiiO Electronics Technology | 5         | 0.05%   |
| Yamaha                      | 4         | 0.04%   |
| Tenx Technology             | 4         | 0.04%   |
| PreSonus Audio Electronics  | 4         | 0.04%   |
| M-Audio                     | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1187      | 10.28%  |
| Intel Sunrise Point-LP HD Audio                                            | 1135      | 9.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 663       | 5.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 518       | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 492       | 4.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 385       | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 323       | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 311       | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 295       | 2.55%   |
| Intel Comet Lake PCH-LP cAVS                                               | 281       | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 272       | 2.35%   |
| Intel 8 Series HD Audio Controller                                         | 272       | 2.35%   |
| Intel Broadwell-U Audio Controller                                         | 258       | 2.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 255       | 2.21%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 241       | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 233       | 2.02%   |
| Intel Comet Lake PCH cAVS                                                  | 212       | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 190       | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 184       | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 162       | 1.4%    |
| Intel CM238 HD Audio Controller                                            | 154       | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 150       | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 135       | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 133       | 1.15%   |
| AMD FCH Azalia Controller                                                  | 119       | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 112       | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 110       | 0.95%   |
| Nvidia Audio device                                                        | 102       | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 94        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 92        | 0.8%    |
| Realtek Semiconductor USB Audio                                            | 89        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 89        | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 87        | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 85        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 76        | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 70        | 0.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 68        | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                              | 65        | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 63        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 53        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1342      | 29.68%  |
| SK hynix            | 1011      | 22.36%  |
| Micron Technology   | 660       | 14.6%   |
| Kingston            | 367       | 8.12%   |
| Crucial             | 257       | 5.68%   |
| Unknown             | 228       | 5.04%   |
| Ramaxel Technology  | 108       | 2.39%   |
| A-DATA Technology   | 101       | 2.23%   |
| Corsair             | 63        | 1.39%   |
| Elpida              | 42        | 0.93%   |
| Smart               | 32        | 0.71%   |
| G.Skill             | 28        | 0.62%   |
| Unknown (ABCD)      | 27        | 0.6%    |
| Unknown             | 27        | 0.6%    |
| Team                | 25        | 0.55%   |
| Nanya Technology    | 22        | 0.49%   |
| Patriot             | 20        | 0.44%   |
| Teikon              | 16        | 0.35%   |
| Smart Brazil        | 13        | 0.29%   |
| Transcend           | 11        | 0.24%   |
| GOODRAM             | 11        | 0.24%   |
| Avant               | 9         | 0.2%    |
| Silicon Power       | 5         | 0.11%   |
| Goldkey             | 5         | 0.11%   |
| V-GEN               | 4         | 0.09%   |
| Timetec             | 4         | 0.09%   |
| PUSKILL             | 4         | 0.09%   |
| Lexar               | 4         | 0.09%   |
| CSX                 | 4         | 0.09%   |
| Apacer              | 4         | 0.09%   |
| 4ea5                | 4         | 0.09%   |
| PNY                 | 3         | 0.07%   |
| OnBoard             | 3         | 0.07%   |
| Kllisre             | 3         | 0.07%   |
| ChangXin Memory     | 3         | 0.07%   |
| Unknown (0x0B5E)    | 2         | 0.04%   |
| SHARETRONIC         | 2         | 0.04%   |
| Sesame              | 2         | 0.04%   |
| RZX                 | 2         | 0.04%   |
| Qumo                | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 80        | 1.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 75        | 1.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 63        | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 58        | 1.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 0.91%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 42        | 0.88%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 41        | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 38        | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 37        | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 35        | 0.74%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 31        | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 30        | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 28        | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 27        | 0.57%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 27        | 0.57%   |
| Unknown                                                          | 27        | 0.57%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 26        | 0.55%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 26        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 26        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 25        | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 25        | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 23        | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.48%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 23        | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 22        | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 22        | 0.46%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2172      | 57.74%  |
| DDR3    | 933       | 24.8%   |
| LPDDR4  | 206       | 5.48%   |
| LPDDR3  | 203       | 5.4%    |
| LPDDR5  | 84        | 2.23%   |
| DDR5    | 78        | 2.07%   |
| DDR2    | 47        | 1.25%   |
| SDRAM   | 21        | 0.56%   |
| Unknown | 14        | 0.37%   |
| DDR     | 3         | 0.08%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3197      | 83.36%  |
| Row Of Chips | 546       | 14.24%  |
| Chip         | 49        | 1.28%   |
| Unknown      | 24        | 0.63%   |
| DIMM         | 19        | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1792      | 43.56%  |
| 4096  | 1025      | 24.91%  |
| 16384 | 778       | 18.91%  |
| 2048  | 301       | 7.32%   |
| 32768 | 164       | 3.99%   |
| 1024  | 49        | 1.19%   |
| 3072  | 2         | 0.05%   |
| 12288 | 1         | 0.02%   |
| 512   | 1         | 0.02%   |
| 64    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 989       | 24.42%  |
| 2667    | 951       | 23.48%  |
| 1600    | 672       | 16.59%  |
| 2400    | 285       | 7.04%   |
| 2133    | 268       | 6.62%   |
| 1333    | 116       | 2.86%   |
| 1334    | 110       | 2.72%   |
| 4267    | 101       | 2.49%   |
| 6400    | 84        | 2.07%   |
| 1867    | 84        | 2.07%   |
| 4800    | 76        | 1.88%   |
| 3266    | 58        | 1.43%   |
| 1067    | 43        | 1.06%   |
| Unknown | 30        | 0.74%   |
| 667     | 29        | 0.72%   |
| 8400    | 28        | 0.69%   |
| 4266    | 28        | 0.69%   |
| 1066    | 17        | 0.42%   |
| 3733    | 16        | 0.4%    |
| 4199    | 15        | 0.37%   |
| 800     | 15        | 0.37%   |
| 5600    | 8         | 0.2%    |
| 975     | 5         | 0.12%   |
| 2048    | 4         | 0.1%    |
| 2933    | 3         | 0.07%   |
| 5500    | 2         | 0.05%   |
| 1866    | 2         | 0.05%   |
| 533     | 2         | 0.05%   |
| 3600    | 1         | 0.02%   |
| 3400    | 1         | 0.02%   |
| 2800    | 1         | 0.02%   |
| 1777    | 1         | 0.02%   |
| 1639    | 1         | 0.02%   |
| 1200    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 333     | 1         | 0.02%   |
| 133     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 30.43%  |
| Canon               | 8         | 17.39%  |
| Samsung Electronics | 6         | 13.04%  |
| Brother Industries  | 6         | 13.04%  |
| Seiko Epson         | 5         | 10.87%  |
| Prolific Technology | 2         | 4.35%   |
| STMicroelectronics  | 1         | 2.17%   |
| Ricoh               | 1         | 2.17%   |
| Pantum              | 1         | 2.17%   |
| NXP Semiconductors  | 1         | 2.17%   |
| MiiiW               | 1         | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 4.35%   |
| Prolific PL2305 Parallel Port                                         | 2         | 4.35%   |
| HP LaserJet P1102                                                     | 2         | 4.35%   |
| Brother DCP-1600                                                      | 2         | 4.35%   |
| STMicroelectronics USB Printing Support                               | 1         | 2.17%   |
| Seiko Epson WF-2830 Series                                            | 1         | 2.17%   |
| Seiko Epson L200 Series                                               | 1         | 2.17%   |
| Seiko Epson ET-2710 Series                                            | 1         | 2.17%   |
| Samsung SCX-4200 series                                               | 1         | 2.17%   |
| Samsung SCX-3200 Series                                               | 1         | 2.17%   |
| Samsung ML-331x Series Laser Printer                                  | 1         | 2.17%   |
| Samsung M2070 Series                                                  | 1         | 2.17%   |
| Samsung CLX-6260 Series                                               | 1         | 2.17%   |
| Samsung C43x Series                                                   | 1         | 2.17%   |
| Ricoh SP 210SU                                                        | 1         | 2.17%   |
| Pantum P2500W series                                                  | 1         | 2.17%   |
| NXP Semiconductors Printer-80                                         | 1         | 2.17%   |
| MiiiW MW USB Receiver                                                 | 1         | 2.17%   |
| HP Photosmart B010 series                                             | 1         | 2.17%   |
| HP Officejet 2620 series                                              | 1         | 2.17%   |
| HP LaserJet 400 colorMFP M475dw                                       | 1         | 2.17%   |
| HP LaserJet 1010                                                      | 1         | 2.17%   |
| HP Ink Tank 310 series                                                | 1         | 2.17%   |
| HP ENVY Pro 6400 series                                               | 1         | 2.17%   |
| HP ENVY 4500 series                                                   | 1         | 2.17%   |
| HP Deskjet 3510 series                                                | 1         | 2.17%   |
| HP Deskjet 3050A                                                      | 1         | 2.17%   |
| HP DeskJet 2600 series                                                | 1         | 2.17%   |
| HP DeskJet 2300 series                                                | 1         | 2.17%   |
| HP DeskJet 2130 series                                                | 1         | 2.17%   |
| Canon TR8500 series                                                   | 1         | 2.17%   |
| Canon TR150 series                                                    | 1         | 2.17%   |
| Canon PIXMA MG3600 Series                                             | 1         | 2.17%   |
| Canon PIXMA MG3500 Series                                             | 1         | 2.17%   |
| Canon PIXMA MG3000 series                                             | 1         | 2.17%   |
| Canon MF3110                                                          | 1         | 2.17%   |
| Canon MF220 Series                                                    | 1         | 2.17%   |
| Canon iP7200 series                                                   | 1         | 2.17%   |
| Brother Printer                                                       | 1         | 2.17%   |
| Brother HL-5250DN Printer                                             | 1         | 2.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1614      | 23.46%  |
| IMC Networks                           | 849       | 12.34%  |
| Microdia                               | 614       | 8.92%   |
| Realtek Semiconductor                  | 562       | 8.17%   |
| Bison Electronics                      | 472       | 6.86%   |
| Quanta                                 | 428       | 6.22%   |
| Sunplus Innovation Technology          | 363       | 5.28%   |
| Cheng Uei Precision Industry (Foxlink) | 276       | 4.01%   |
| Syntek                                 | 193       | 2.8%    |
| Lite-On Technology                     | 188       | 2.73%   |
| Acer                                   | 183       | 2.66%   |
| Apple                                  | 166       | 2.41%   |
| Logitech                               | 162       | 2.35%   |
| Luxvisions Innotech Limited            | 138       | 2.01%   |
| Suyin                                  | 108       | 1.57%   |
| Silicon Motion                         | 80        | 1.16%   |
| Sonix Technology                       | 61        | 0.89%   |
| Alcor Micro                            | 48        | 0.7%    |
| Samsung Electronics                    | 43        | 0.62%   |
| Ricoh                                  | 39        | 0.57%   |
| Lenovo                                 | 25        | 0.36%   |
| SunplusIT                              | 21        | 0.31%   |
| Primax Electronics                     | 20        | 0.29%   |
| Importek                               | 18        | 0.26%   |
| Microsoft                              | 17        | 0.25%   |
| Z-Star Microelectronics                | 12        | 0.17%   |
| icSpring                               | 9         | 0.13%   |
| Generalplus Technology                 | 9         | 0.13%   |
| ALi                                    | 9         | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.12%   |
| ARC International                      | 8         | 0.12%   |
| MacroSilicon                           | 7         | 0.1%    |
| Shinetech                              | 6         | 0.09%   |
| KYE Systems (Mouse Systems)            | 6         | 0.09%   |
| Intel                                  | 6         | 0.09%   |
| WaveRider Communications               | 5         | 0.07%   |
| Razer USA                              | 5         | 0.07%   |
| Pixart Imaging                         | 5         | 0.07%   |
| Creative Technology                    | 5         | 0.07%   |
| 8SSC21D67422V1SR28902JL                | 5         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 558       | 8.05%   |
| Microdia Integrated_Webcam_HD                       | 358       | 5.16%   |
| IMC Networks Integrated Camera                      | 332       | 4.79%   |
| Realtek Integrated_Webcam_HD                        | 259       | 3.74%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 227       | 3.27%   |
| Sunplus Integrated_Webcam_HD                        | 165       | 2.38%   |
| Bison Integrated Camera                             | 164       | 2.37%   |
| Chicony HD Webcam                                   | 137       | 1.98%   |
| Syntek Integrated Camera                            | 132       | 1.9%    |
| Quanta HD User Facing                               | 90        | 1.3%    |
| Chicony Integrated Camera (1280x720@30)             | 90        | 1.3%    |
| Lite-On Integrated Camera                           | 89        | 1.28%   |
| Chicony HP HD Camera                                | 70        | 1.01%   |
| Bison SunplusIT Integrated Camera                   | 68        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 66        | 0.95%   |
| Quanta HP TrueVision HD Camera                      | 57        | 0.82%   |
| Bison HD Webcam                                     | 52        | 0.75%   |
| Chicony USB2.0 Camera                               | 50        | 0.72%   |
| Logitech HD Pro Webcam C920                         | 49        | 0.71%   |
| Quanta HP HD Camera                                 | 48        | 0.69%   |
| IMC Networks HD Camera                              | 48        | 0.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 48        | 0.69%   |
| Apple FaceTime HD Camera                            | 48        | 0.69%   |
| Quanta HD Webcam                                    | 47        | 0.68%   |
| Chicony HP TrueVision HD Camera                     | 47        | 0.68%   |
| Acer Integrated Camera                              | 46        | 0.66%   |
| Microdia Integrated Webcam                          | 44        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)             | 43        | 0.62%   |
| Bison Lenovo EasyCamera                             | 43        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 42        | 0.61%   |
| Quanta HP Wide Vision HD Camera                     | 40        | 0.58%   |
| Lite-On HP HD Camera                                | 40        | 0.58%   |
| Chicony Integrated IR Camera                        | 40        | 0.58%   |
| Chicony HP Wide Vision HD Camera                    | 40        | 0.58%   |
| Realtek Integrated Webcam                           | 38        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 38        | 0.55%   |
| Sunplus HD WebCam                                   | 37        | 0.53%   |
| Apple Built-in iSight                               | 37        | 0.53%   |
| IMC Networks ov9734_azurewave_camera                | 36        | 0.52%   |
| Chicony HD User Facing                              | 36        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 614       | 35.03%  |
| Validity Sensors                   | 514       | 29.32%  |
| Shenzhen Goodix Technology         | 320       | 18.25%  |
| Elan Microelectronics              | 108       | 6.16%   |
| Upek                               | 63        | 3.59%   |
| LighTuning Technology              | 56        | 3.19%   |
| AuthenTec                          | 41        | 2.34%   |
| Realtek USB2.0 Finger Print Bridge | 16        | 0.91%   |
| Samsung Electronics                | 10        | 0.57%   |
| STMicroelectronics                 | 5         | 0.29%   |
| Focal-systems.Corp                 | 5         | 0.29%   |
| Dell                               | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 291       | 16.59%  |
| Shenzhen Goodix  Fingerprint Device                                        | 203       | 11.57%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 116       | 6.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 106       | 6.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 97        | 5.53%   |
| Shenzhen Goodix FingerPrint                                                | 63        | 3.59%   |
| Validity Sensors Synaptics WBDI                                            | 60        | 3.42%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 59        | 3.36%   |
| Shenzhen Goodix Fingerprint Reader                                         | 54        | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 49        | 2.79%   |
| Elan ELAN:Fingerprint                                                      | 48        | 2.74%   |
| Elan ELAN:ARM-M4                                                           | 47        | 2.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 43        | 2.45%   |
| Synaptics Fingerprint reader [HP G6]                                       | 41        | 2.34%   |
| Validity Sensors VFS491                                                    | 30        | 1.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 28        | 1.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 28        | 1.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 27        | 1.54%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 25        | 1.43%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 23        | 1.31%   |
| Synaptics UWP WBDI Device                                                  | 23        | 1.31%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 23        | 1.31%   |
| Synaptics  WBDI                                                            | 22        | 1.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 21        | 1.2%    |
| Validity Sensors Fingerprint scanner                                       | 18        | 1.03%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 16        | 0.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 0.86%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 14        | 0.8%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 0.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 0.68%   |
| Synaptics UWP WBDI                                                         | 11        | 0.63%   |
| Elan WBF Fingerprint Sensor                                                | 11        | 0.63%   |
| Synaptics WBDI                                                             | 10        | 0.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.51%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 0.46%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.46%   |
| AuthenTec AES2810                                                          | 8         | 0.46%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.4%    |
| Unknown                                                                    | 7         | 0.4%    |
| Synaptics WBDI Device                                                      | 6         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 277       | 42.03%  |
| Alcor Micro                | 266       | 40.36%  |
| Upek                       | 40        | 6.07%   |
| Lenovo                     | 33        | 5.01%   |
| O2 Micro                   | 15        | 2.28%   |
| Gemalto (was Gemplus)      | 7         | 1.06%   |
| Yubico.com                 | 3         | 0.46%   |
| SCM Microsystems           | 3         | 0.46%   |
| Realtek Semiconductor      | 3         | 0.46%   |
| OmniKey                    | 3         | 0.46%   |
| Aladdin Knowledge Systems  | 3         | 0.46%   |
| Reiner SCT Kartensysteme   | 1         | 0.15%   |
| Purism, SPC                | 1         | 0.15%   |
| Hewlett-Packard            | 1         | 0.15%   |
| Chicony Electronics        | 1         | 0.15%   |
| Athena Smartcard Solutions | 1         | 0.15%   |
| Advanced Card Systems      | 1         | 0.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 265       | 40.21%  |
| Broadcom 5880                                                                | 89        | 13.51%  |
| Broadcom 58200                                                               | 80        | 12.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 62        | 9.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 44        | 6.68%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 40        | 6.07%   |
| Lenovo Integrated Smart Card Reader                                          | 32        | 4.86%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 1.82%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.91%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.46%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.46%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.46%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.3%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.15%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.15%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.15%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.15%   |
| Purism, SPC Librem Key                                                       | 1         | 0.15%   |
| OmniKey CardMan 4321                                                         | 1         | 0.15%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.15%   |
| OmniKey CardMan 1021                                                         | 1         | 0.15%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.15%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.15%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.15%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.15%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.15%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.15%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4378      | 57.76%  |
| 1     | 2614      | 34.49%  |
| 2     | 500       | 6.6%    |
| 3     | 61        | 0.8%    |
| 4     | 8         | 0.11%   |
| 5     | 7         | 0.09%   |
| 6     | 5         | 0.07%   |
| 7     | 4         | 0.05%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1734      | 45.9%   |
| Graphics card            | 767       | 20.3%   |
| Multimedia controller    | 375       | 9.93%   |
| Net/wireless             | 272       | 7.2%    |
| Chipcard                 | 212       | 5.61%   |
| Camera                   | 137       | 3.63%   |
| Bluetooth                | 79        | 2.09%   |
| Storage                  | 54        | 1.43%   |
| Card reader              | 51        | 1.35%   |
| Sound                    | 28        | 0.74%   |
| Net/ethernet             | 21        | 0.56%   |
| Communication controller | 18        | 0.48%   |
| Network                  | 16        | 0.42%   |
| Modem                    | 9         | 0.24%   |
| Flash memory             | 2         | 0.05%   |
| Video                    | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

