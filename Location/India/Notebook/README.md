Linux in India - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in India.

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

Total: 3739

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | E41-25 81FS                 | [5d9743e91d](https://linux-hardware.org/?probe=5d9743e91d) | Nov 02, 2022 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [95ddb63cb1](https://linux-hardware.org/?probe=95ddb63cb1) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| Dell          | Latitude 3420               | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6323d7e1b3](https://linux-hardware.org/?probe=6323d7e1b3) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| Acer          | Unknown                     | [284f534a6a](https://linux-hardware.org/?probe=284f534a6a) | Oct 31, 2022 |
| Acer          | Unknown                     | [27b5267fa3](https://linux-hardware.org/?probe=27b5267fa3) | Oct 31, 2022 |
| Dell          | Inspiron 3542               | [dcccad24af](https://linux-hardware.org/?probe=dcccad24af) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [dea1724953](https://linux-hardware.org/?probe=dea1724953) | Oct 31, 2022 |
| HP            | Laptop 15s-gr0xxx           | [02d23cb1b9](https://linux-hardware.org/?probe=02d23cb1b9) | Oct 30, 2022 |
| Sony          | VPCEA45FG                   | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| HP            | Laptop 15s-gr0xxx           | [f7155fd671](https://linux-hardware.org/?probe=f7155fd671) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| Dell          | Latitude E7470              | [a9274c9070](https://linux-hardware.org/?probe=a9274c9070) | Oct 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [09d3217ce4](https://linux-hardware.org/?probe=09d3217ce4) | Oct 25, 2022 |
| ASUSTek       | X550LC                      | [75c0c3e97b](https://linux-hardware.org/?probe=75c0c3e97b) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Dell          | Vostro 3491                 | [8809be3a93](https://linux-hardware.org/?probe=8809be3a93) | Oct 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9a104497e3](https://linux-hardware.org/?probe=9a104497e3) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [bea9c6b47b](https://linux-hardware.org/?probe=bea9c6b47b) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [d37b700ffb](https://linux-hardware.org/?probe=d37b700ffb) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KY00     | [657b1ee865](https://linux-hardware.org/?probe=657b1ee865) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f07691d6b1](https://linux-hardware.org/?probe=f07691d6b1) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWA0DW0... | [117e1e8e03](https://linux-hardware.org/?probe=117e1e8e03) | Oct 20, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| HP            | 255 G8 Notebook PC          | [2f69a96661](https://linux-hardware.org/?probe=2f69a96661) | Oct 18, 2022 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [96a36651bf](https://linux-hardware.org/?probe=96a36651bf) | Oct 18, 2022 |
| Lenovo        | G500 20236                  | [e38bd0cb56](https://linux-hardware.org/?probe=e38bd0cb56) | Oct 17, 2022 |
| HP            | 255 G8 Notebook PC          | [cb651a5071](https://linux-hardware.org/?probe=cb651a5071) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| HP            | InsydeH2O EFI BIOS          | [0c9c2f85b4](https://linux-hardware.org/?probe=0c9c2f85b4) | Oct 17, 2022 |
| Dell          | Inspiron 3521               | [f7b9f3cab2](https://linux-hardware.org/?probe=f7b9f3cab2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [82ab4c516a](https://linux-hardware.org/?probe=82ab4c516a) | Oct 16, 2022 |
| Timi          | Mi NoteBook Pro             | [dbdd6179c7](https://linux-hardware.org/?probe=dbdd6179c7) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [411a334a74](https://linux-hardware.org/?probe=411a334a74) | Oct 16, 2022 |
| Dell          | Inspiron 15-3567            | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | EliteBook 840 G1            | [06cda048c3](https://linux-hardware.org/?probe=06cda048c3) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| HP            | EliteBook 840 G3            | [5e4c8b36d2](https://linux-hardware.org/?probe=5e4c8b36d2) | Oct 14, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [7ca53492d5](https://linux-hardware.org/?probe=7ca53492d5) | Oct 14, 2022 |
| Dell          | Inspiron 3543               | [25556b5183](https://linux-hardware.org/?probe=25556b5183) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| Dell          | Vostro 3446                 | [da79693286](https://linux-hardware.org/?probe=da79693286) | Oct 13, 2022 |
| HP            | Laptop 14s-ef1xxx           | [4a38e7efc3](https://linux-hardware.org/?probe=4a38e7efc3) | Oct 13, 2022 |
| Dell          | G3 3500                     | [831b4e147e](https://linux-hardware.org/?probe=831b4e147e) | Oct 12, 2022 |
| AVITA         | NS14A6                      | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [36abc6f39f](https://linux-hardware.org/?probe=36abc6f39f) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [40adf0a5d8](https://linux-hardware.org/?probe=40adf0a5d8) | Oct 11, 2022 |
| AVITA         | NS14A6                      | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Dell          | Inspiron 5584               | [0800772df3](https://linux-hardware.org/?probe=0800772df3) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [f7d3139c23](https://linux-hardware.org/?probe=f7d3139c23) | Oct 08, 2022 |
| HP            | Pavilion dv6                | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| HP            | Laptop 15-bs0xx             | [6009358723](https://linux-hardware.org/?probe=6009358723) | Oct 07, 2022 |
| HP            | Laptop 15-bs0xx             | [c37715196b](https://linux-hardware.org/?probe=c37715196b) | Oct 07, 2022 |
| Dell          | Vostro 3578                 | [4fa0e607b7](https://linux-hardware.org/?probe=4fa0e607b7) | Oct 07, 2022 |
| HP            | Laptop 14s-dr1xxx           | [00d04b6a56](https://linux-hardware.org/?probe=00d04b6a56) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a431b20f04](https://linux-hardware.org/?probe=a431b20f04) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| HP            | 15                          | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| Dell          | Latitude E7440              | [8dda778da4](https://linux-hardware.org/?probe=8dda778da4) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [62b67bffae](https://linux-hardware.org/?probe=62b67bffae) | Oct 04, 2022 |
| HP            | ProBook 4540s               | [ef3e02b39c](https://linux-hardware.org/?probe=ef3e02b39c) | Oct 03, 2022 |
| HP            | EliteBook 840 G5            | [5d6a3f11e7](https://linux-hardware.org/?probe=5d6a3f11e7) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Dell          | Inspiron 3543               | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [88c05ba074](https://linux-hardware.org/?probe=88c05ba074) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [1a210b9eb5](https://linux-hardware.org/?probe=1a210b9eb5) | Oct 01, 2022 |
| Lenovo        | ThinkPad L450 20DSS00M01    | [e52e98a7e7](https://linux-hardware.org/?probe=e52e98a7e7) | Oct 01, 2022 |
| Dell          | G3 3500                     | [245ebaabe5](https://linux-hardware.org/?probe=245ebaabe5) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Acer          | Predator PH315-51           | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Google        | Relm                        | [e440e5c1cc](https://linux-hardware.org/?probe=e440e5c1cc) | Sep 30, 2022 |
| Lenovo        | G580 20157                  | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Dell          | Inspiron 5559               | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude 3410               | [82fe1556b6](https://linux-hardware.org/?probe=82fe1556b6) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3aa314d706](https://linux-hardware.org/?probe=3aa314d706) | Sep 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| Acer          | Aspire A515-57G             | [97c49cffe7](https://linux-hardware.org/?probe=97c49cffe7) | Sep 25, 2022 |
| Acer          | Aspire A515-57G             | [10813c8cb5](https://linux-hardware.org/?probe=10813c8cb5) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9c7306d91e](https://linux-hardware.org/?probe=9c7306d91e) | Sep 25, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | [5cd2d8db8c](https://linux-hardware.org/?probe=5cd2d8db8c) | Sep 24, 2022 |
| Lenovo        | ThinkPad E470 20H1004UIG    | [310337a455](https://linux-hardware.org/?probe=310337a455) | Sep 24, 2022 |
| Dell          | Precision 7510              | [11c98b608a](https://linux-hardware.org/?probe=11c98b608a) | Sep 24, 2022 |
| Dell          | Inspiron 3584               | [626c79c116](https://linux-hardware.org/?probe=626c79c116) | Sep 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ba0d37d696](https://linux-hardware.org/?probe=ba0d37d696) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | [872eafe5f7](https://linux-hardware.org/?probe=872eafe5f7) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | [68338b3080](https://linux-hardware.org/?probe=68338b3080) | Sep 23, 2022 |
| Dell          | Vostro 3558                 | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| Dell          | Latitude 3490               | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Acer          | Aspire E5-575G              | [cbbf373937](https://linux-hardware.org/?probe=cbbf373937) | Sep 21, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| Apple         | MacBookPro5,4               | [2bc992ab7e](https://linux-hardware.org/?probe=2bc992ab7e) | Sep 15, 2022 |
| Apple         | MacBookPro5,4               | [8dfb715f1e](https://linux-hardware.org/?probe=8dfb715f1e) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| HP            | Laptop 14s-dr2xxx           | [39163aba8a](https://linux-hardware.org/?probe=39163aba8a) | Sep 15, 2022 |
| HP            | Pavilion Notebook           | [578cb93789](https://linux-hardware.org/?probe=578cb93789) | Sep 14, 2022 |
| Dell          | Vostro 14-3468              | [fbe4062b6e](https://linux-hardware.org/?probe=fbe4062b6e) | Sep 14, 2022 |
| HP            | 15                          | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [423008d102](https://linux-hardware.org/?probe=423008d102) | Sep 13, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3e5c80e004](https://linux-hardware.org/?probe=3e5c80e004) | Sep 13, 2022 |
| HP            | Laptop 15-bw0xx             | [644ad9d55f](https://linux-hardware.org/?probe=644ad9d55f) | Sep 12, 2022 |
| Acer          | Aspire E5-575G              | [d5a0bdc1a9](https://linux-hardware.org/?probe=d5a0bdc1a9) | Sep 12, 2022 |
| Dell          | Precision 5560              | [3120c2b781](https://linux-hardware.org/?probe=3120c2b781) | Sep 12, 2022 |
| Acer          | Nitro AN515-58              | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Samsung       | 750XED                      | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| Samsung       | 750XED                      | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Dell          | Precision 5560              | [f70da50728](https://linux-hardware.org/?probe=f70da50728) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f752846656](https://linux-hardware.org/?probe=f752846656) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [3397f75941](https://linux-hardware.org/?probe=3397f75941) | Sep 09, 2022 |
| Acer          | Aspire A315-58              | [5af4c5d3e1](https://linux-hardware.org/?probe=5af4c5d3e1) | Sep 09, 2022 |
| Dell          | Inspiron 5537               | [871de5472c](https://linux-hardware.org/?probe=871de5472c) | Sep 08, 2022 |
| Dell          | Inspiron 5537               | [fad1689295](https://linux-hardware.org/?probe=fad1689295) | Sep 08, 2022 |
| ASUSTek       | K53U                        | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Acer          | Aspire 5745                 | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Lenovo        | G560 20042                  | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| Dell          | Vostro 3480                 | [65c846d249](https://linux-hardware.org/?probe=65c846d249) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Dell          | Inspiron 5577               | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [319d526423](https://linux-hardware.org/?probe=319d526423) | Sep 02, 2022 |
| Dell          | Inspiron 15-3567            | [5b1f25ca62](https://linux-hardware.org/?probe=5b1f25ca62) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| HP            | Notebook                    | [2ca7fbbfa9](https://linux-hardware.org/?probe=2ca7fbbfa9) | Aug 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| ASUSTek       | ZenBook UX334FAC_UX333FA... | [ae84021e13](https://linux-hardware.org/?probe=ae84021e13) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Dell          | Latitude 3440               | [3e3f5ac9ab](https://linux-hardware.org/?probe=3e3f5ac9ab) | Aug 29, 2022 |
| HP            | Notebook                    | [e00cfcb387](https://linux-hardware.org/?probe=e00cfcb387) | Aug 29, 2022 |
| Dell          | Inspiron N5010              | [1a76248bf8](https://linux-hardware.org/?probe=1a76248bf8) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [608a16dc64](https://linux-hardware.org/?probe=608a16dc64) | Aug 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [cf1b2ff13c](https://linux-hardware.org/?probe=cf1b2ff13c) | Aug 27, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [783495e971](https://linux-hardware.org/?probe=783495e971) | Aug 25, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0LF00    | [3c1287dfd2](https://linux-hardware.org/?probe=3c1287dfd2) | Aug 25, 2022 |
| Dell          | Inspiron N5010              | [f4862a3793](https://linux-hardware.org/?probe=f4862a3793) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HP            | 15                          | [832c6247b2](https://linux-hardware.org/?probe=832c6247b2) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [d988e1aeb9](https://linux-hardware.org/?probe=d988e1aeb9) | Aug 25, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [a0c40a81ec](https://linux-hardware.org/?probe=a0c40a81ec) | Aug 24, 2022 |
| Dell          | Vostro 5481                 | [749e6c3622](https://linux-hardware.org/?probe=749e6c3622) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | TravelMate P215-52G         | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Notebook                    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| eMachines     | D725                        | [34394fab35](https://linux-hardware.org/?probe=34394fab35) | Aug 21, 2022 |
| MSI           | Modern 14 B5M               | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [32e59cda1c](https://linux-hardware.org/?probe=32e59cda1c) | Aug 20, 2022 |
| Acer          | Aspire R3-131T              | [3f6370f978](https://linux-hardware.org/?probe=3f6370f978) | Aug 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ac28d2918e](https://linux-hardware.org/?probe=ac28d2918e) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| HP            | 15                          | [4d736aca15](https://linux-hardware.org/?probe=4d736aca15) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b97f13141f](https://linux-hardware.org/?probe=b97f13141f) | Aug 19, 2022 |
| HP            | Laptop 14s-fq1xxx           | [61f9640136](https://linux-hardware.org/?probe=61f9640136) | Aug 19, 2022 |
| HP            | 15                          | [166efee25e](https://linux-hardware.org/?probe=166efee25e) | Aug 19, 2022 |
| HP            | Laptop 15-da0xxx            | [7a9624c968](https://linux-hardware.org/?probe=7a9624c968) | Aug 19, 2022 |
| Lenovo        | G50-45 80E3                 | [0ed8a39444](https://linux-hardware.org/?probe=0ed8a39444) | Aug 19, 2022 |
| Apple         | MacBook2,1                  | [46208653fa](https://linux-hardware.org/?probe=46208653fa) | Aug 18, 2022 |
| Dell          | Latitude 3420               | [49300ca856](https://linux-hardware.org/?probe=49300ca856) | Aug 18, 2022 |
| ASUSTek       | X542UQR                     | [4c8af9dc73](https://linux-hardware.org/?probe=4c8af9dc73) | Aug 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | Inspiron 5559               | [ae2d8ade73](https://linux-hardware.org/?probe=ae2d8ade73) | Aug 18, 2022 |
| Acer          | Aspire E1-431               | [d4132b425f](https://linux-hardware.org/?probe=d4132b425f) | Aug 17, 2022 |
| Acer          | Nitro AN515-56              | [c62f8ea53b](https://linux-hardware.org/?probe=c62f8ea53b) | Aug 17, 2022 |
| ASUSTek       | X542UQR                     | [8236615818](https://linux-hardware.org/?probe=8236615818) | Aug 17, 2022 |
| Dell          | Inspiron 3542               | [32ccd17130](https://linux-hardware.org/?probe=32ccd17130) | Aug 17, 2022 |
| Dell          | Latitude 3420               | [33a254b0e0](https://linux-hardware.org/?probe=33a254b0e0) | Aug 17, 2022 |
| Dell          | Inspiron N5110              | [e5dbfdb922](https://linux-hardware.org/?probe=e5dbfdb922) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Toshiba       | TECRA R940                  | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| MSI           | Alpha 15 A3DD               | [fd548daf00](https://linux-hardware.org/?probe=fd548daf00) | Aug 14, 2022 |
| HP            | Presario CQ56               | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| Dell          | Latitude E6420              | [e295e29aa3](https://linux-hardware.org/?probe=e295e29aa3) | Aug 13, 2022 |
| HP            | Pavilion 15                 | [bafa6bfcb8](https://linux-hardware.org/?probe=bafa6bfcb8) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 D1 81W... | [59b3324e73](https://linux-hardware.org/?probe=59b3324e73) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f8a6209b06](https://linux-hardware.org/?probe=f8a6209b06) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Dell          | Inspiron 3584               | [3ba16dc3e1](https://linux-hardware.org/?probe=3ba16dc3e1) | Aug 11, 2022 |
| Dell          | Latitude E7450              | [3992650626](https://linux-hardware.org/?probe=3992650626) | Aug 10, 2022 |
| HP            | 245 G7 Notebook PC          | [567786673d](https://linux-hardware.org/?probe=567786673d) | Aug 10, 2022 |
| Dell          | Vostro 3480                 | [31b062c315](https://linux-hardware.org/?probe=31b062c315) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [364f2e0a23](https://linux-hardware.org/?probe=364f2e0a23) | Aug 09, 2022 |
| HP            | Pavilion g6                 | [4b6fc67f06](https://linux-hardware.org/?probe=4b6fc67f06) | Aug 09, 2022 |
| Dell          | System XPS L502X            | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Dell          | Inspiron N5010              | [dab9f235f5](https://linux-hardware.org/?probe=dab9f235f5) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| Dell          | Latitude 3510               | [5dd81ae3c1](https://linux-hardware.org/?probe=5dd81ae3c1) | Aug 08, 2022 |
| HP            | 15                          | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| Apple         | MacBook2,1                  | [d3f41ae4fb](https://linux-hardware.org/?probe=d3f41ae4fb) | Aug 08, 2022 |
| HP            | Pavilion g6                 | [aa437aea14](https://linux-hardware.org/?probe=aa437aea14) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| HP            | Pavilion g6                 | [7543f383ad](https://linux-hardware.org/?probe=7543f383ad) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [8f7ef1d997](https://linux-hardware.org/?probe=8f7ef1d997) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [ffab2b901d](https://linux-hardware.org/?probe=ffab2b901d) | Aug 07, 2022 |
| HP            | Pavilion g6                 | [955d372528](https://linux-hardware.org/?probe=955d372528) | Aug 06, 2022 |
| HP            | Laptop 15-bs0xx             | [7e9b1406b1](https://linux-hardware.org/?probe=7e9b1406b1) | Aug 06, 2022 |
| Sony          | VPCEB16FG                   | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
| HP            | 430                         | [c30f00d442](https://linux-hardware.org/?probe=c30f00d442) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e2545a7011](https://linux-hardware.org/?probe=e2545a7011) | Aug 04, 2022 |
| Dell          | Latitude E7470              | [16fd81987c](https://linux-hardware.org/?probe=16fd81987c) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [91581d4ecd](https://linux-hardware.org/?probe=91581d4ecd) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Dell          | G3 3500                     | [440b43e5e5](https://linux-hardware.org/?probe=440b43e5e5) | Aug 02, 2022 |
| Dell          | Latitude 3410               | [b2d717d59e](https://linux-hardware.org/?probe=b2d717d59e) | Aug 02, 2022 |
| HP            | Pavilion g6                 | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Acer          | Aspire 5560                 | [d5b8ae56fd](https://linux-hardware.org/?probe=d5b8ae56fd) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Lenovo        | V14-IIL 82C4                | [8707ea39a2](https://linux-hardware.org/?probe=8707ea39a2) | Jul 31, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| MSI           | Prestige 15 A10SC           | [9c161b860f](https://linux-hardware.org/?probe=9c161b860f) | Jul 31, 2022 |
| Apple         | MacBookPro7,1               | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Dell          | Inspiron 3541               | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| Intel         | IS80 V117                   | [cf45970313](https://linux-hardware.org/?probe=cf45970313) | Jul 29, 2022 |
| Acer          | Aspire A715-42G             | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| HP            | Pavilion 15                 | [512f5ada4a](https://linux-hardware.org/?probe=512f5ada4a) | Jul 28, 2022 |
| HP            | Pavilion 15                 | [b74fec46a0](https://linux-hardware.org/?probe=b74fec46a0) | Jul 28, 2022 |
| HP            | 348 G4                      | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Dell          | Inspiron 5502               | [f84c29c4b6](https://linux-hardware.org/?probe=f84c29c4b6) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| HP            | 15                          | [9177a1f411](https://linux-hardware.org/?probe=9177a1f411) | Jul 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f9203ffeed](https://linux-hardware.org/?probe=f9203ffeed) | Jul 26, 2022 |
| Dell          | Latitude 3410               | [20636bf80f](https://linux-hardware.org/?probe=20636bf80f) | Jul 26, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [c9534903a2](https://linux-hardware.org/?probe=c9534903a2) | Jul 26, 2022 |
| Dell          | Latitude 3440               | [a47121441e](https://linux-hardware.org/?probe=a47121441e) | Jul 25, 2022 |
| Dell          | Vostro 15-3568              | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| Acer          | Predator PH315-52           | [a1346acc8a](https://linux-hardware.org/?probe=a1346acc8a) | Jul 25, 2022 |
| Dell          | Vostro 3491                 | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| Dell          | Inspiron 3537               | [df25f468ef](https://linux-hardware.org/?probe=df25f468ef) | Jul 24, 2022 |
| Dell          | Inspiron 3537               | [acc1cd1dcf](https://linux-hardware.org/?probe=acc1cd1dcf) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Google        | Wolf                        | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| HP            | Laptop 14q-bu1xx            | [7fa58abd22](https://linux-hardware.org/?probe=7fa58abd22) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| Acer          | Predator PH315-54           | [e06076002a](https://linux-hardware.org/?probe=e06076002a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T490 20RYS01J00    | [415229917b](https://linux-hardware.org/?probe=415229917b) | Jul 22, 2022 |
| Sony          | SVF15318SNB                 | [176c871bf8](https://linux-hardware.org/?probe=176c871bf8) | Jul 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [b0a8b9eb01](https://linux-hardware.org/?probe=b0a8b9eb01) | Jul 21, 2022 |
| Dell          | Inspiron 5520               | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| HP            | ProBook 4441s               | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| Alienware     | 15 R2                       | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 Ua 81W... | [513e2ede59](https://linux-hardware.org/?probe=513e2ede59) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a8d726c8b2](https://linux-hardware.org/?probe=a8d726c8b2) | Jul 14, 2022 |
| HP            | Notebook -15q-bu004tu       | [b15814c3b1](https://linux-hardware.org/?probe=b15814c3b1) | Jul 14, 2022 |
| ASUSTek       | X553MA                      | [b78b735f01](https://linux-hardware.org/?probe=b78b735f01) | Jul 14, 2022 |
| Lenovo        | V15-IIL 82C5                | [fc969f7c75](https://linux-hardware.org/?probe=fc969f7c75) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 Ua 81W... | [f0a069d567](https://linux-hardware.org/?probe=f0a069d567) | Jul 13, 2022 |
| HP            | Notebook -15q-bu004tu       | [f45fde1a93](https://linux-hardware.org/?probe=f45fde1a93) | Jul 13, 2022 |
| Lenovo        | V15-IIL 82C5                | [c9842baa35](https://linux-hardware.org/?probe=c9842baa35) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [a002ac843c](https://linux-hardware.org/?probe=a002ac843c) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [79ecbebabd](https://linux-hardware.org/?probe=79ecbebabd) | Jul 12, 2022 |
| ASUSTek       | X541UJ                      | [1725714269](https://linux-hardware.org/?probe=1725714269) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | [cc10e6800a](https://linux-hardware.org/?probe=cc10e6800a) | Jul 11, 2022 |
| HP            | Pavilion 15                 | [2bfb2ba391](https://linux-hardware.org/?probe=2bfb2ba391) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [41b46c06f1](https://linux-hardware.org/?probe=41b46c06f1) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1755faf164](https://linux-hardware.org/?probe=1755faf164) | Jul 11, 2022 |
| ASUSTek       | X507UB                      | [53a07e58b8](https://linux-hardware.org/?probe=53a07e58b8) | Jul 09, 2022 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [95ff55839b](https://linux-hardware.org/?probe=95ff55839b) | Jul 09, 2022 |
| HP            | ProBook 440 G2              | [a2a01affe3](https://linux-hardware.org/?probe=a2a01affe3) | Jul 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [b3cdd2b6f6](https://linux-hardware.org/?probe=b3cdd2b6f6) | Jul 09, 2022 |
| HP            | 15                          | [a7bfa741b3](https://linux-hardware.org/?probe=a7bfa741b3) | Jul 08, 2022 |
| HP            | Laptop 15-da1xxx            | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [c9eb8f9a5f](https://linux-hardware.org/?probe=c9eb8f9a5f) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| HP            | Mini 110-3100               | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Dell          | Precision 5530              | [cbe37ac52f](https://linux-hardware.org/?probe=cbe37ac52f) | Jul 05, 2022 |
| Dell          | Latitude 3540               | [a689d5019b](https://linux-hardware.org/?probe=a689d5019b) | Jul 05, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [697729549b](https://linux-hardware.org/?probe=697729549b) | Jul 04, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [31226ebc70](https://linux-hardware.org/?probe=31226ebc70) | Jul 04, 2022 |
| HP            | Notebook                    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Dell          | Inspiron 5520               | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [dffcf6cd44](https://linux-hardware.org/?probe=dffcf6cd44) | Jul 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [54a9d6bcb3](https://linux-hardware.org/?probe=54a9d6bcb3) | Jul 02, 2022 |
| Lenovo        | Erazer Y50-70               | [c147e10488](https://linux-hardware.org/?probe=c147e10488) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [9034bf7260](https://linux-hardware.org/?probe=9034bf7260) | Jul 01, 2022 |
| Timi          | Mi NoteBook Ultra           | [0364230bc7](https://linux-hardware.org/?probe=0364230bc7) | Jul 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [430c2e6760](https://linux-hardware.org/?probe=430c2e6760) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| HP            | Laptop 15s-du2xxx           | [13e85826c2](https://linux-hardware.org/?probe=13e85826c2) | Jun 30, 2022 |
| HP            | Laptop 15s-du2xxx           | [bb4df4398e](https://linux-hardware.org/?probe=bb4df4398e) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [f29c4de6b4](https://linux-hardware.org/?probe=f29c4de6b4) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [7ecd760977](https://linux-hardware.org/?probe=7ecd760977) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [8428ba0120](https://linux-hardware.org/?probe=8428ba0120) | Jun 30, 2022 |
| HP            | 1000                        | [65ae23140e](https://linux-hardware.org/?probe=65ae23140e) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | EliteBook 840 G4            | [0244eb4fde](https://linux-hardware.org/?probe=0244eb4fde) | Jun 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Lenovo        | B41-80 80LG                 | [30f6e726bd](https://linux-hardware.org/?probe=30f6e726bd) | Jun 28, 2022 |
| HP            | Laptop 15s-du3xxx           | [404e9daae2](https://linux-hardware.org/?probe=404e9daae2) | Jun 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [569faf34f1](https://linux-hardware.org/?probe=569faf34f1) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| HP            | Laptop 15g-br1xx            | [aef95d312f](https://linux-hardware.org/?probe=aef95d312f) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| ASUSTek       | X510UNR                     | [d5f3803a24](https://linux-hardware.org/?probe=d5f3803a24) | Jun 26, 2022 |
| HP            | Pavilion 15                 | [929cd4988f](https://linux-hardware.org/?probe=929cd4988f) | Jun 26, 2022 |
| HP            | Pavilion g6                 | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| Lenovo        | G570 20079                  | [5ec853b08c](https://linux-hardware.org/?probe=5ec853b08c) | Jun 25, 2022 |
| Lenovo        | V330-14ARR 81B1             | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| Dell          | Inspiron 5459               | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Lenovo        | ThinkPad T420 4177Q5U       | [cf27027c76](https://linux-hardware.org/?probe=cf27027c76) | Jun 22, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [93f08af289](https://linux-hardware.org/?probe=93f08af289) | Jun 21, 2022 |
| Dell          | Vostro 2420                 | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| ASUSTek       | X556UQK                     | [6ce6e1d459](https://linux-hardware.org/?probe=6ce6e1d459) | Jun 20, 2022 |
| Dell          | Vostro 3490                 | [c203985c20](https://linux-hardware.org/?probe=c203985c20) | Jun 20, 2022 |
| Dell          | Vostro 3490                 | [e0968d0d2b](https://linux-hardware.org/?probe=e0968d0d2b) | Jun 20, 2022 |
| Lenovo        | G50-80 80E5                 | [d4aa7ef4a3](https://linux-hardware.org/?probe=d4aa7ef4a3) | Jun 20, 2022 |
| Dell          | Vostro 14-3468              | [1f0ee8f5fd](https://linux-hardware.org/?probe=1f0ee8f5fd) | Jun 20, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [90f4bec7db](https://linux-hardware.org/?probe=90f4bec7db) | Jun 19, 2022 |
| HP            | EliteBook 1050 G1           | [731ecfced1](https://linux-hardware.org/?probe=731ecfced1) | Jun 18, 2022 |
| Lenovo        | ThinkPad E490 20N8S01H00    | [7f96502192](https://linux-hardware.org/?probe=7f96502192) | Jun 18, 2022 |
| HP            | Unknown                     | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Dell          | Latitude 5310               | [d34d939bae](https://linux-hardware.org/?probe=d34d939bae) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| Dell          | Latitude 3450               | [f0bff3d433](https://linux-hardware.org/?probe=f0bff3d433) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| ASUSTek       | ET2040I                     | [45273f0675](https://linux-hardware.org/?probe=45273f0675) | Jun 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0ac0a212e0](https://linux-hardware.org/?probe=0ac0a212e0) | Jun 13, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | [7aaeea9280](https://linux-hardware.org/?probe=7aaeea9280) | Jun 13, 2022 |
| HP            | Laptop 15q-bu0xx            | [859d1ddbb0](https://linux-hardware.org/?probe=859d1ddbb0) | Jun 13, 2022 |
| Acer          | Aspire A315-21              | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| AVITA         | NE14A2                      | [3ac292714a](https://linux-hardware.org/?probe=3ac292714a) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| Acer          | Swift SF313-53              | [68dff2bc8e](https://linux-hardware.org/?probe=68dff2bc8e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | Laptop 15-da1xxx            | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| Flipkart I... | NKi510TL85S                 | [6e1326c27f](https://linux-hardware.org/?probe=6e1326c27f) | Jun 07, 2022 |
| Dell          | XPS 13 9305                 | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude E6420              | [b2a364340d](https://linux-hardware.org/?probe=b2a364340d) | Jun 07, 2022 |
| Dell          | Inspiron 3521               | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | 81WE                        | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| ASUSTek       | X556UQK                     | [caa9a0cf2f](https://linux-hardware.org/?probe=caa9a0cf2f) | Jun 06, 2022 |
| Acer          | Aspire A715-75G             | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| Dell          | Latitude E6420              | [01eb3f0d4b](https://linux-hardware.org/?probe=01eb3f0d4b) | Jun 05, 2022 |
| Dell          | G3 3500                     | [6734206fa0](https://linux-hardware.org/?probe=6734206fa0) | Jun 05, 2022 |
| HP            | 15                          | [3e96827fe7](https://linux-hardware.org/?probe=3e96827fe7) | Jun 04, 2022 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [41f0428c2b](https://linux-hardware.org/?probe=41f0428c2b) | Jun 04, 2022 |
| Dell          | Inspiron 3584               | [843797dc80](https://linux-hardware.org/?probe=843797dc80) | Jun 04, 2022 |
| HP            | 15                          | [b256b9e839](https://linux-hardware.org/?probe=b256b9e839) | Jun 04, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [66cc7342ec](https://linux-hardware.org/?probe=66cc7342ec) | Jun 04, 2022 |
| Lenovo        | ThinkPad T430 2349LTU       | [2c80cec3c3](https://linux-hardware.org/?probe=2c80cec3c3) | Jun 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9533388943](https://linux-hardware.org/?probe=9533388943) | Jun 03, 2022 |
| Lenovo        | IdeaPad V15-ADA             | [94971f4968](https://linux-hardware.org/?probe=94971f4968) | Jun 03, 2022 |
| Dell          | Latitude 7390               | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | [ac0d3882ca](https://linux-hardware.org/?probe=ac0d3882ca) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| Lenovo        | Erazer Y50-70               | [abb6af451d](https://linux-hardware.org/?probe=abb6af451d) | May 31, 2022 |
| Dell          | Inspiron 15 3511            | [3fbca187e7](https://linux-hardware.org/?probe=3fbca187e7) | May 31, 2022 |
| Dell          | Inspiron 5567               | [2f14b6956f](https://linux-hardware.org/?probe=2f14b6956f) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | [784e1ca4cc](https://linux-hardware.org/?probe=784e1ca4cc) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| HP            | Pavilion g6                 | [a82494e1f3](https://linux-hardware.org/?probe=a82494e1f3) | May 29, 2022 |
| Dell          | Vostro 3546                 | [3acd5d4cb0](https://linux-hardware.org/?probe=3acd5d4cb0) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9d9d577f12](https://linux-hardware.org/?probe=9d9d577f12) | May 28, 2022 |
| Dell          | Latitude 5480               | [6056df9c22](https://linux-hardware.org/?probe=6056df9c22) | May 27, 2022 |
| Dell          | Inspiron 3543               | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| Acer          | Aspire A515-46              | [e004aa3fd2](https://linux-hardware.org/?probe=e004aa3fd2) | May 25, 2022 |
| HP            | Notebook                    | [87460a83e8](https://linux-hardware.org/?probe=87460a83e8) | May 25, 2022 |
| HP            | Laptop 15s-du2xxx           | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8d8d5ff5e1](https://linux-hardware.org/?probe=8d8d5ff5e1) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Dell          | Latitude 3450               | [f788f954ec](https://linux-hardware.org/?probe=f788f954ec) | May 23, 2022 |
| Dell          | Inspiron N4010              | [872649a8b4](https://linux-hardware.org/?probe=872649a8b4) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| Lenovo        | S20-30 20421                | [58d0509bff](https://linux-hardware.org/?probe=58d0509bff) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| Acer          | Swift SF514-52T             | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| Acer          | Aspire A715-75G             | [10d158c79e](https://linux-hardware.org/?probe=10d158c79e) | May 22, 2022 |
| Acer          | Aspire A715-75G             | [4e1e3e6863](https://linux-hardware.org/?probe=4e1e3e6863) | May 22, 2022 |
| Dell          | Inspiron 5567               | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| HP            | Pavilion g6                 | [3b904a10e3](https://linux-hardware.org/?probe=3b904a10e3) | May 21, 2022 |
| HP            | Pavilion g6                 | [e165a36a31](https://linux-hardware.org/?probe=e165a36a31) | May 21, 2022 |
| HP            | Pavilion Notebook           | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Acer          | Swift SF514-54T             | [29b06de977](https://linux-hardware.org/?probe=29b06de977) | May 21, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| Alienware     | x17 R2                      | [019dbb46a4](https://linux-hardware.org/?probe=019dbb46a4) | May 20, 2022 |
| Toshiba       | Satellite U940              | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [dba5104e21](https://linux-hardware.org/?probe=dba5104e21) | May 18, 2022 |
| HP            | EliteBook 745 G3            | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| HP            | OMEN by Laptop              | [0a25740096](https://linux-hardware.org/?probe=0a25740096) | May 18, 2022 |
| Dell          | Inspiron 15 3511            | [0095bc3389](https://linux-hardware.org/?probe=0095bc3389) | May 16, 2022 |
| Acer          | Nitro AN515-45              | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| Dell          | Precision 3551              | [f134f92d00](https://linux-hardware.org/?probe=f134f92d00) | May 16, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [b4d7d75ad1](https://linux-hardware.org/?probe=b4d7d75ad1) | May 15, 2022 |
| Lenovo        | S20-30 20421                | [7436d81709](https://linux-hardware.org/?probe=7436d81709) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Sony          | VPCEA36FG                   | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HP            | 15                          | [32a7709448](https://linux-hardware.org/?probe=32a7709448) | May 13, 2022 |
| Dell          | Vostro 3558                 | [2a1cf069bc](https://linux-hardware.org/?probe=2a1cf069bc) | May 13, 2022 |
| AVITA         | NS14A8                      | [bc86f7a17e](https://linux-hardware.org/?probe=bc86f7a17e) | May 13, 2022 |
| Dell          | Precision M2800             | [266af2c2b7](https://linux-hardware.org/?probe=266af2c2b7) | May 13, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [3eaf81c13c](https://linux-hardware.org/?probe=3eaf81c13c) | May 12, 2022 |
| HP            | EliteBook 840 G3            | [4d2b2c6a3c](https://linux-hardware.org/?probe=4d2b2c6a3c) | May 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [ed11a30da0](https://linux-hardware.org/?probe=ed11a30da0) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [65fce47240](https://linux-hardware.org/?probe=65fce47240) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| Dell          | G3 3579                     | [eff2c45d12](https://linux-hardware.org/?probe=eff2c45d12) | May 11, 2022 |
| Dell          | G15 5511                    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| HP            | 15                          | [fdef27b310](https://linux-hardware.org/?probe=fdef27b310) | May 10, 2022 |
| Acer          | Nitro AN515-45              | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | 2000                        | [d0e74bfff6](https://linux-hardware.org/?probe=d0e74bfff6) | May 10, 2022 |
| HP            | Notebook                    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| HP            | Pavilion dv6                | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [3227adfd1a](https://linux-hardware.org/?probe=3227adfd1a) | May 07, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QX01    | [68fbf0cacb](https://linux-hardware.org/?probe=68fbf0cacb) | May 07, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T2S... | [70fe076856](https://linux-hardware.org/?probe=70fe076856) | May 06, 2022 |
| Google        | Lick                        | [60e52e55e1](https://linux-hardware.org/?probe=60e52e55e1) | May 06, 2022 |
| Lenovo        | ThinkPad L13 20R3S10R00     | [b173909e06](https://linux-hardware.org/?probe=b173909e06) | May 06, 2022 |
| HP            | Notebook                    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| HP            | EliteBook 8470p             | [db81dd7652](https://linux-hardware.org/?probe=db81dd7652) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | [ca91daf662](https://linux-hardware.org/?probe=ca91daf662) | May 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [329673fcbf](https://linux-hardware.org/?probe=329673fcbf) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| HP            | Laptop 15-bs1xx             | [aa3fb50ed5](https://linux-hardware.org/?probe=aa3fb50ed5) | May 03, 2022 |
| Toshiba       | Satellite U940              | [3d6bd2511e](https://linux-hardware.org/?probe=3d6bd2511e) | May 03, 2022 |
| HP            | Presario CQ42               | [93ac0fd52a](https://linux-hardware.org/?probe=93ac0fd52a) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0eb277ff80](https://linux-hardware.org/?probe=0eb277ff80) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | [549ca9da46](https://linux-hardware.org/?probe=549ca9da46) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | [ec3ccc4967](https://linux-hardware.org/?probe=ec3ccc4967) | May 01, 2022 |
| Dell          | Latitude 3490               | [ff6e81ce15](https://linux-hardware.org/?probe=ff6e81ce15) | May 01, 2022 |
| Acer          | Aspire A715-75G             | [50d37d9cf7](https://linux-hardware.org/?probe=50d37d9cf7) | May 01, 2022 |
| Acer          | Swift SF314-55G             | [1935c949a2](https://linux-hardware.org/?probe=1935c949a2) | May 01, 2022 |
| Dell          | Inspiron 7559               | [37b324ecf9](https://linux-hardware.org/?probe=37b324ecf9) | May 01, 2022 |
| Dell          | G3 3500                     | [df72f36c52](https://linux-hardware.org/?probe=df72f36c52) | Apr 30, 2022 |
| Google        | Lick                        | [33d1e6209a](https://linux-hardware.org/?probe=33d1e6209a) | Apr 30, 2022 |
| Dell          | G3 3500                     | [c9ee387b32](https://linux-hardware.org/?probe=c9ee387b32) | Apr 30, 2022 |
| eMachines     | eME730                      | [ac985950eb](https://linux-hardware.org/?probe=ac985950eb) | Apr 30, 2022 |
| Dell          | Inspiron 3542               | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BUS1MN00    | [4e2b073a5c](https://linux-hardware.org/?probe=4e2b073a5c) | Apr 29, 2022 |
| Dell          | G5 5500                     | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Dell          | Inspiron 3505               | [1f6bbce46b](https://linux-hardware.org/?probe=1f6bbce46b) | Apr 28, 2022 |
| Dell          | Inspiron 3542               | [6e00a18a0f](https://linux-hardware.org/?probe=6e00a18a0f) | Apr 28, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | [59a8e467c6](https://linux-hardware.org/?probe=59a8e467c6) | Apr 28, 2022 |
| Lenovo        | V14 G2 ITL Ua 82KA          | [f191c49754](https://linux-hardware.org/?probe=f191c49754) | Apr 28, 2022 |
| HP            | Notebook                    | [daaa31b65a](https://linux-hardware.org/?probe=daaa31b65a) | Apr 27, 2022 |
| HP            | Notebook                    | [cbac71290e](https://linux-hardware.org/?probe=cbac71290e) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a696a35961](https://linux-hardware.org/?probe=a696a35961) | Apr 27, 2022 |
| HP            | Notebook                    | [ec93418371](https://linux-hardware.org/?probe=ec93418371) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [ea3e0b8695](https://linux-hardware.org/?probe=ea3e0b8695) | Apr 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [8197ac9c77](https://linux-hardware.org/?probe=8197ac9c77) | Apr 25, 2022 |
| HP            | 348 G4                      | [54db7eb2da](https://linux-hardware.org/?probe=54db7eb2da) | Apr 25, 2022 |
| ASUSTek       | X555LF                      | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Inspiron 3501               | [99bd45c11d](https://linux-hardware.org/?probe=99bd45c11d) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [45b9330abf](https://linux-hardware.org/?probe=45b9330abf) | Apr 23, 2022 |
| Lenovo        | E41-25 81FS                 | [4880f7c2d5](https://linux-hardware.org/?probe=4880f7c2d5) | Apr 22, 2022 |
| Lenovo        | Z50-70 20354                | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Toshiba       | Satellite C850-A786         | [e57aca482e](https://linux-hardware.org/?probe=e57aca482e) | Apr 22, 2022 |
| HP            | Laptop 15s-du2xxx           | [fe39cbe3d1](https://linux-hardware.org/?probe=fe39cbe3d1) | Apr 20, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [88764ed497](https://linux-hardware.org/?probe=88764ed497) | Apr 20, 2022 |
| Toshiba       | Satellite L50-C             | [9e2b287533](https://linux-hardware.org/?probe=9e2b287533) | Apr 20, 2022 |
| Dell          | Inspiron 5559               | [6ddb878f3e](https://linux-hardware.org/?probe=6ddb878f3e) | Apr 20, 2022 |
| HP            | Notebook                    | [bec9c06e6e](https://linux-hardware.org/?probe=bec9c06e6e) | Apr 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f3d940677f](https://linux-hardware.org/?probe=f3d940677f) | Apr 19, 2022 |
| Dell          | Latitude E5520              | [1b428165cf](https://linux-hardware.org/?probe=1b428165cf) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca0b0f6a8a](https://linux-hardware.org/?probe=ca0b0f6a8a) | Apr 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cffdde259f](https://linux-hardware.org/?probe=cffdde259f) | Apr 15, 2022 |
| Timi          | Mi NoteBook 14              | [88abcd9e70](https://linux-hardware.org/?probe=88abcd9e70) | Apr 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ef76ce862d](https://linux-hardware.org/?probe=ef76ce862d) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [5f85d41ef2](https://linux-hardware.org/?probe=5f85d41ef2) | Apr 14, 2022 |
| Dynabook      | TECRA X40-F                 | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | [d06a50d75c](https://linux-hardware.org/?probe=d06a50d75c) | Apr 13, 2022 |
| Lenovo        | V14 G2 ITL Ua 82KA          | [b680349236](https://linux-hardware.org/?probe=b680349236) | Apr 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c7a9564044](https://linux-hardware.org/?probe=c7a9564044) | Apr 12, 2022 |
| Lenovo        | E41-25 81FS                 | [8d0dfa3de3](https://linux-hardware.org/?probe=8d0dfa3de3) | Apr 12, 2022 |
| HP            | Notebook                    | [de9a13770b](https://linux-hardware.org/?probe=de9a13770b) | Apr 11, 2022 |
| Toshiba       | Satellite C50D-A0386        | [31b131cc55](https://linux-hardware.org/?probe=31b131cc55) | Apr 11, 2022 |
| Acer          | Nitro AN515-45              | [4e0bcf3318](https://linux-hardware.org/?probe=4e0bcf3318) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Lenovo        | G500 20236                  | [6feb6018af](https://linux-hardware.org/?probe=6feb6018af) | Apr 10, 2022 |
| HP            | 246                         | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Acer          | One 14 Z2-485               | [57f307fa80](https://linux-hardware.org/?probe=57f307fa80) | Apr 09, 2022 |
| HP            | Pavilion Notebook           | [f76d101440](https://linux-hardware.org/?probe=f76d101440) | Apr 09, 2022 |
| Apple         | MacBookPro12,1              | [7ec2454548](https://linux-hardware.org/?probe=7ec2454548) | Apr 08, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [a8c92b8a4c](https://linux-hardware.org/?probe=a8c92b8a4c) | Apr 08, 2022 |
| HP            | Pavilion Notebook           | [94a611644c](https://linux-hardware.org/?probe=94a611644c) | Apr 07, 2022 |
| Lenovo        | G560 20042                  | [945def6907](https://linux-hardware.org/?probe=945def6907) | Apr 07, 2022 |
| HP            | Laptop 14q-cy0xxx           | [625bad986e](https://linux-hardware.org/?probe=625bad986e) | Apr 07, 2022 |
| ASUSTek       | X542UQR                     | [57c9a10617](https://linux-hardware.org/?probe=57c9a10617) | Apr 07, 2022 |
| ASUSTek       | X542UQR                     | [15c5f13718](https://linux-hardware.org/?probe=15c5f13718) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c5c24ea4c2](https://linux-hardware.org/?probe=c5c24ea4c2) | Apr 06, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [96b467ce52](https://linux-hardware.org/?probe=96b467ce52) | Apr 05, 2022 |
| Dell          | Vostro 3578                 | [8e2637c774](https://linux-hardware.org/?probe=8e2637c774) | Apr 05, 2022 |
| ASUSTek       | X550LC                      | [bc017137e8](https://linux-hardware.org/?probe=bc017137e8) | Apr 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [1d3cd04256](https://linux-hardware.org/?probe=1d3cd04256) | Apr 04, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Inspiron 3505               | [982bcd3a5b](https://linux-hardware.org/?probe=982bcd3a5b) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | [ba24b37041](https://linux-hardware.org/?probe=ba24b37041) | Apr 03, 2022 |
| Lenovo        | Erazer Y50-70               | [36d3d65801](https://linux-hardware.org/?probe=36d3d65801) | Apr 03, 2022 |
| HP            | Laptop 15s-dr1xxx           | [86ca12c772](https://linux-hardware.org/?probe=86ca12c772) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | [57a0d73ab9](https://linux-hardware.org/?probe=57a0d73ab9) | Apr 02, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [d103b2cb25](https://linux-hardware.org/?probe=d103b2cb25) | Apr 02, 2022 |
| Dell          | Inspiron 5520               | [63f818dc19](https://linux-hardware.org/?probe=63f818dc19) | Apr 02, 2022 |
| Dell          | Inspiron 14 5410            | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | G5 5500                     | [56b5d0d490](https://linux-hardware.org/?probe=56b5d0d490) | Apr 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [87dfbaa9e8](https://linux-hardware.org/?probe=87dfbaa9e8) | Apr 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [36563f3934](https://linux-hardware.org/?probe=36563f3934) | Apr 01, 2022 |
| Dell          | XPS 13 9305                 | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | [85f1411d0e](https://linux-hardware.org/?probe=85f1411d0e) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | [f8edce28d5](https://linux-hardware.org/?probe=f8edce28d5) | Mar 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Dell          | Latitude E6420              | [411b1a3a51](https://linux-hardware.org/?probe=411b1a3a51) | Mar 30, 2022 |
| HP            | Laptop 15-da1xxx            | [fcbd3df931](https://linux-hardware.org/?probe=fcbd3df931) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| Dell          | Studio 1450                 | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| HP            | Pavilion dv3                | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| HP            | Pavilion g4                 | [893eaf3bca](https://linux-hardware.org/?probe=893eaf3bca) | Mar 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2465ab5a58](https://linux-hardware.org/?probe=2465ab5a58) | Mar 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e09438b057](https://linux-hardware.org/?probe=e09438b057) | Mar 26, 2022 |
| Dell          | Inspiron 3505               | [11abcc854d](https://linux-hardware.org/?probe=11abcc854d) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4ba4683a05](https://linux-hardware.org/?probe=4ba4683a05) | Mar 24, 2022 |
| HP            | EliteBook 840 G3            | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8533e3cf0d](https://linux-hardware.org/?probe=8533e3cf0d) | Mar 23, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0M600    | [1f816ed931](https://linux-hardware.org/?probe=1f816ed931) | Mar 23, 2022 |
| Acer          | Swift SF314-52              | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| Lenovo        | ThinkPad X230 23251Q0       | [0a705ba05c](https://linux-hardware.org/?probe=0a705ba05c) | Mar 21, 2022 |
| Dell          | Latitude 3400               | [031b95db58](https://linux-hardware.org/?probe=031b95db58) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| HP            | Pavilion 14                 | [537e877606](https://linux-hardware.org/?probe=537e877606) | Mar 20, 2022 |
| HP            | Laptop 15-da0xxx            | [66de21a937](https://linux-hardware.org/?probe=66de21a937) | Mar 19, 2022 |
| HP            | Pavilion dv3                | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | [2b30c1219e](https://linux-hardware.org/?probe=2b30c1219e) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | [221de9592b](https://linux-hardware.org/?probe=221de9592b) | Mar 16, 2022 |
| Dell          | Latitude E7450              | [107065a152](https://linux-hardware.org/?probe=107065a152) | Mar 15, 2022 |
| ASUSTek       | VivoBook S14 X430UA         | [9a04e16d4a](https://linux-hardware.org/?probe=9a04e16d4a) | Mar 15, 2022 |
| Lenovo        | Erazer Y50-70               | [ae9a6ee7cb](https://linux-hardware.org/?probe=ae9a6ee7cb) | Mar 14, 2022 |
| Dell          | G5 5500                     | [12a4380cad](https://linux-hardware.org/?probe=12a4380cad) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | [89d17b56d6](https://linux-hardware.org/?probe=89d17b56d6) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | [737a2d4c61](https://linux-hardware.org/?probe=737a2d4c61) | Mar 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [11bd4e97e6](https://linux-hardware.org/?probe=11bd4e97e6) | Mar 13, 2022 |
| Alienware     | 13 R3                       | [a8b07f9c17](https://linux-hardware.org/?probe=a8b07f9c17) | Mar 12, 2022 |
| Dell          | Latitude E5410              | [8015e22264](https://linux-hardware.org/?probe=8015e22264) | Mar 12, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude 7480               | [cbff798f89](https://linux-hardware.org/?probe=cbff798f89) | Mar 11, 2022 |
| Dell          | Latitude 7480               | [02e748e3ac](https://linux-hardware.org/?probe=02e748e3ac) | Mar 11, 2022 |
| Dell          | Inspiron 5409               | [e99c4341ca](https://linux-hardware.org/?probe=e99c4341ca) | Mar 11, 2022 |
| Dell          | Inspiron 5409               | [777b585f05](https://linux-hardware.org/?probe=777b585f05) | Mar 11, 2022 |
| Dell          | Latitude 3410               | [49491fb71a](https://linux-hardware.org/?probe=49491fb71a) | Mar 11, 2022 |
| Dell          | Inspiron 3793               | [1fb19c1b23](https://linux-hardware.org/?probe=1fb19c1b23) | Mar 09, 2022 |
| Micromax      | Canvas Laptab LT777         | [7ff8a61256](https://linux-hardware.org/?probe=7ff8a61256) | Mar 08, 2022 |
| Acer          | Aspire 4752                 | [291341394c](https://linux-hardware.org/?probe=291341394c) | Mar 07, 2022 |
| Dell          | Latitude E6540              | [97de37d664](https://linux-hardware.org/?probe=97de37d664) | Mar 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [61ebab5e1f](https://linux-hardware.org/?probe=61ebab5e1f) | Mar 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [ae88c42f40](https://linux-hardware.org/?probe=ae88c42f40) | Mar 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c5bf02a4d7](https://linux-hardware.org/?probe=c5bf02a4d7) | Mar 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82C5     | [d4b6e7276e](https://linux-hardware.org/?probe=d4b6e7276e) | Mar 03, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| Lenovo        | E41-25 81FS                 | [f7cf64afde](https://linux-hardware.org/?probe=f7cf64afde) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f61c04b0a8](https://linux-hardware.org/?probe=f61c04b0a8) | Mar 01, 2022 |
| HP            | Notebook                    | [24f32b44ea](https://linux-hardware.org/?probe=24f32b44ea) | Feb 28, 2022 |
| Lenovo        | ThinkPad X230 2330A17       | [ed014e00c8](https://linux-hardware.org/?probe=ed014e00c8) | Feb 27, 2022 |
| HP            | Presario CQ42               | [de34294599](https://linux-hardware.org/?probe=de34294599) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Lenovo        | B40-70 20392                | [ab691617d6](https://linux-hardware.org/?probe=ab691617d6) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| HP            | Pavilion 15                 | [463d26d75c](https://linux-hardware.org/?probe=463d26d75c) | Feb 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ea12d27cf9](https://linux-hardware.org/?probe=ea12d27cf9) | Feb 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [ab78767b82](https://linux-hardware.org/?probe=ab78767b82) | Feb 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b3e65653c6](https://linux-hardware.org/?probe=b3e65653c6) | Feb 25, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [b3086480e5](https://linux-hardware.org/?probe=b3086480e5) | Feb 25, 2022 |
| HP            | 15                          | [7f0f38dc4d](https://linux-hardware.org/?probe=7f0f38dc4d) | Feb 24, 2022 |
| HP            | 15                          | [72f40f8b9a](https://linux-hardware.org/?probe=72f40f8b9a) | Feb 24, 2022 |
| HP            | 15                          | [9fad172623](https://linux-hardware.org/?probe=9fad172623) | Feb 24, 2022 |
| Dell          | Inspiron 5567               | [0e9130cffe](https://linux-hardware.org/?probe=0e9130cffe) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 U 81WB    | [73c7d63295](https://linux-hardware.org/?probe=73c7d63295) | Feb 23, 2022 |
| HP            | 245 G6 Notebook PC          | [4cf4344d75](https://linux-hardware.org/?probe=4cf4344d75) | Feb 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [73c98934ee](https://linux-hardware.org/?probe=73c98934ee) | Feb 23, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [c736f239ba](https://linux-hardware.org/?probe=c736f239ba) | Feb 21, 2022 |
| HP            | Notebook                    | [d8dd214532](https://linux-hardware.org/?probe=d8dd214532) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [5810a7b666](https://linux-hardware.org/?probe=5810a7b666) | Feb 20, 2022 |
| Dell          | System XPS L502X            | [110f0aa3e3](https://linux-hardware.org/?probe=110f0aa3e3) | Feb 19, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [8aaf1cdcde](https://linux-hardware.org/?probe=8aaf1cdcde) | Feb 19, 2022 |
| Dell          | Inspiron 15-3567            | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | X555LAB                     | [413a122ef8](https://linux-hardware.org/?probe=413a122ef8) | Feb 19, 2022 |
| ASUSTek       | X550LC                      | [b6e0cd1dc2](https://linux-hardware.org/?probe=b6e0cd1dc2) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [917db2bac9](https://linux-hardware.org/?probe=917db2bac9) | Feb 17, 2022 |
| Acer          | Aspire V3-472PG             | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| Lenovo        | ThinkPad X230 2330A17       | [882f7d3c8b](https://linux-hardware.org/?probe=882f7d3c8b) | Feb 16, 2022 |
| Acer          | Aspire ES1-572              | [ca8f1af83d](https://linux-hardware.org/?probe=ca8f1af83d) | Feb 15, 2022 |
| Dell          | Inspiron 7577               | [bc0d38c096](https://linux-hardware.org/?probe=bc0d38c096) | Feb 15, 2022 |
| Acer          | Aspire ES1-572              | [9d72302b5a](https://linux-hardware.org/?probe=9d72302b5a) | Feb 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [2dd964cf93](https://linux-hardware.org/?probe=2dd964cf93) | Feb 15, 2022 |
| HP            | Snappy                      | [eae991d921](https://linux-hardware.org/?probe=eae991d921) | Feb 14, 2022 |
| HP            | Laptop 15s-gr0xxx           | [db6e83a4b8](https://linux-hardware.org/?probe=db6e83a4b8) | Feb 14, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6284595dc0](https://linux-hardware.org/?probe=6284595dc0) | Feb 13, 2022 |
| Dell          | Latitude E6410              | [787eacd33c](https://linux-hardware.org/?probe=787eacd33c) | Feb 13, 2022 |
| Dell          | Latitude 3420               | [625f453d9a](https://linux-hardware.org/?probe=625f453d9a) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| Lenovo        | ThinkPad T440p 20AN00DJA... | [9209921869](https://linux-hardware.org/?probe=9209921869) | Feb 12, 2022 |
| Acer          | Aspire A515-54G             | [f8e7f688a6](https://linux-hardware.org/?probe=f8e7f688a6) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | [8abd201999](https://linux-hardware.org/?probe=8abd201999) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | [a84b20f4fd](https://linux-hardware.org/?probe=a84b20f4fd) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6df20f0f72](https://linux-hardware.org/?probe=6df20f0f72) | Feb 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| Lenovo        | G50-80 80E5                 | [5182b3bbf6](https://linux-hardware.org/?probe=5182b3bbf6) | Feb 10, 2022 |
| HP            | Notebook                    | [d90ba0e218](https://linux-hardware.org/?probe=d90ba0e218) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2d14e7f15](https://linux-hardware.org/?probe=b2d14e7f15) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2661cf0743](https://linux-hardware.org/?probe=2661cf0743) | Feb 10, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [869a837ab1](https://linux-hardware.org/?probe=869a837ab1) | Feb 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [bbedc56833](https://linux-hardware.org/?probe=bbedc56833) | Feb 08, 2022 |
| Lenovo        | G500s 20245                 | [841d62ce23](https://linux-hardware.org/?probe=841d62ce23) | Feb 08, 2022 |
| Dell          | G5 5500                     | [de24d5a5f8](https://linux-hardware.org/?probe=de24d5a5f8) | Feb 07, 2022 |
| HP            | Laptop 15q-ds0xxx           | [250ec15d99](https://linux-hardware.org/?probe=250ec15d99) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [978a3994a9](https://linux-hardware.org/?probe=978a3994a9) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [14c25ecf4d](https://linux-hardware.org/?probe=14c25ecf4d) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6f11d75bcd](https://linux-hardware.org/?probe=6f11d75bcd) | Feb 06, 2022 |
| HP            | Pavilion 15                 | [58a4d59a59](https://linux-hardware.org/?probe=58a4d59a59) | Feb 05, 2022 |
| HP            | Pavilion 15                 | [35d4cb0015](https://linux-hardware.org/?probe=35d4cb0015) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9b802670e0](https://linux-hardware.org/?probe=9b802670e0) | Feb 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d457ee5311](https://linux-hardware.org/?probe=d457ee5311) | Feb 05, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Dell          | G5 5500                     | [edd04957d8](https://linux-hardware.org/?probe=edd04957d8) | Feb 05, 2022 |
| ASUSTek       | X510UNR                     | [df6616c490](https://linux-hardware.org/?probe=df6616c490) | Feb 04, 2022 |
| Lenovo        | G560 20042                  | [642e27a7bd](https://linux-hardware.org/?probe=642e27a7bd) | Feb 04, 2022 |
| HP            | Laptop 15g-br1xx            | [092ea39c7e](https://linux-hardware.org/?probe=092ea39c7e) | Feb 03, 2022 |
| Dell          | Inspiron 5509               | [40aa956ad5](https://linux-hardware.org/?probe=40aa956ad5) | Feb 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a2876a28be](https://linux-hardware.org/?probe=a2876a28be) | Feb 01, 2022 |
| Dell          | Latitude 3520               | [7f6955e406](https://linux-hardware.org/?probe=7f6955e406) | Feb 01, 2022 |
| HP            | Laptop 15s-gr0xxx           | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Samsung       | RV409/RV509/RV709           | [535f5504f0](https://linux-hardware.org/?probe=535f5504f0) | Feb 01, 2022 |
| Dell          | Inspiron 3584               | [14630b0a02](https://linux-hardware.org/?probe=14630b0a02) | Feb 01, 2022 |
| Lenovo        | G580 20157                  | [fe6a35d3f8](https://linux-hardware.org/?probe=fe6a35d3f8) | Jan 31, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [016bea7377](https://linux-hardware.org/?probe=016bea7377) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | [712c420215](https://linux-hardware.org/?probe=712c420215) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | [0c05019294](https://linux-hardware.org/?probe=0c05019294) | Jan 31, 2022 |
| Dell          | Vostro 3558                 | [05d97f5a85](https://linux-hardware.org/?probe=05d97f5a85) | Jan 30, 2022 |
| Lenovo        | V310-15ISK 80SY             | [58781ff3be](https://linux-hardware.org/?probe=58781ff3be) | Jan 30, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| HP            | 15                          | [81961b52a9](https://linux-hardware.org/?probe=81961b52a9) | Jan 29, 2022 |
| Acer          | TravelMate P214-53G         | [b81086aa28](https://linux-hardware.org/?probe=b81086aa28) | Jan 28, 2022 |
| Dell          | Inspiron 3505               | [4a4b0e0660](https://linux-hardware.org/?probe=4a4b0e0660) | Jan 28, 2022 |
| Acer          | TravelMate P214-53          | [8b138118b8](https://linux-hardware.org/?probe=8b138118b8) | Jan 28, 2022 |
| Lenovo        | E41-25 81FS                 | [692c64fd48](https://linux-hardware.org/?probe=692c64fd48) | Jan 28, 2022 |
| Dell          | Studio 1450                 | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| Dell          | Inspiron 15-3567            | [eb4d280c2e](https://linux-hardware.org/?probe=eb4d280c2e) | Jan 28, 2022 |
| HP            | EliteBook 1050 G1           | [cf9b0bf009](https://linux-hardware.org/?probe=cf9b0bf009) | Jan 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeadbaa61e](https://linux-hardware.org/?probe=eeadbaa61e) | Jan 26, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | [e12ec125c1](https://linux-hardware.org/?probe=e12ec125c1) | Jan 26, 2022 |
| Sony          | SVE15113ENW                 | [4ed2d681e5](https://linux-hardware.org/?probe=4ed2d681e5) | Jan 26, 2022 |
| HP            | Laptop 15-bs0xx             | [17282e26a5](https://linux-hardware.org/?probe=17282e26a5) | Jan 26, 2022 |
| Dell          | Vostro 3500                 | [c9b1b53061](https://linux-hardware.org/?probe=c9b1b53061) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | [bc4d814298](https://linux-hardware.org/?probe=bc4d814298) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | [36709c59ac](https://linux-hardware.org/?probe=36709c59ac) | Jan 24, 2022 |
| Acer          | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Acer          | Nitro AN515-45              | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [086f2b17b3](https://linux-hardware.org/?probe=086f2b17b3) | Jan 23, 2022 |
| HP            | Laptop 14q-cs0xxx           | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Acer          | Predator PH315-51           | [1df9cf7c06](https://linux-hardware.org/?probe=1df9cf7c06) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [33079ee3bf](https://linux-hardware.org/?probe=33079ee3bf) | Jan 22, 2022 |
| Acer          | Predator PH315-51           | [291f22ae53](https://linux-hardware.org/?probe=291f22ae53) | Jan 21, 2022 |
| HP            | Laptop 15s-eq0xxx           | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK LH532              | [0459069843](https://linux-hardware.org/?probe=0459069843) | Jan 21, 2022 |
| Dell          | G15 5511                    | [b1a127367b](https://linux-hardware.org/?probe=b1a127367b) | Jan 20, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | [e092fc4b26](https://linux-hardware.org/?probe=e092fc4b26) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [245123d0a8](https://linux-hardware.org/?probe=245123d0a8) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK LH532              | [58be376485](https://linux-hardware.org/?probe=58be376485) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [0b07369103](https://linux-hardware.org/?probe=0b07369103) | Jan 19, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [d99cb4b767](https://linux-hardware.org/?probe=d99cb4b767) | Jan 19, 2022 |
| Dell          | Precision 5540              | [2d971f9a85](https://linux-hardware.org/?probe=2d971f9a85) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2e7e3ccc17](https://linux-hardware.org/?probe=2e7e3ccc17) | Jan 19, 2022 |
| Acer          | Nitro AN515-45              | [a30f5fabcd](https://linux-hardware.org/?probe=a30f5fabcd) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X411... | [6294ff032d](https://linux-hardware.org/?probe=6294ff032d) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8ffc80bc8d](https://linux-hardware.org/?probe=8ffc80bc8d) | Jan 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [5a6275014a](https://linux-hardware.org/?probe=5a6275014a) | Jan 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [7cc691c557](https://linux-hardware.org/?probe=7cc691c557) | Jan 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [ff8151d1c1](https://linux-hardware.org/?probe=ff8151d1c1) | Jan 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b70c5a1312](https://linux-hardware.org/?probe=b70c5a1312) | Jan 16, 2022 |
| Dell          | Latitude E6510              | [c0d3a6c31a](https://linux-hardware.org/?probe=c0d3a6c31a) | Jan 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [a1fffe7c0f](https://linux-hardware.org/?probe=a1fffe7c0f) | Jan 16, 2022 |
| Dell          | Inspiron 1545               | [a6c2013bf1](https://linux-hardware.org/?probe=a6c2013bf1) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [80f7288259](https://linux-hardware.org/?probe=80f7288259) | Jan 15, 2022 |
| Lenovo        | G580 20157                  | [67c671c04f](https://linux-hardware.org/?probe=67c671c04f) | Jan 15, 2022 |
| HP            | Laptop 15s-du2xxx           | [7ea05d0591](https://linux-hardware.org/?probe=7ea05d0591) | Jan 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [71480de13b](https://linux-hardware.org/?probe=71480de13b) | Jan 14, 2022 |
| Acer          | Swift SF314-55G             | [fc48cf8ace](https://linux-hardware.org/?probe=fc48cf8ace) | Jan 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [23160ed698](https://linux-hardware.org/?probe=23160ed698) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eee9a2ae45](https://linux-hardware.org/?probe=eee9a2ae45) | Jan 14, 2022 |
| Timi          | Mi NoteBook Ultra           | [7a5a59c6e6](https://linux-hardware.org/?probe=7a5a59c6e6) | Jan 13, 2022 |
| Dell          | Latitude 5480               | [c1f1846378](https://linux-hardware.org/?probe=c1f1846378) | Jan 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [a68454eff9](https://linux-hardware.org/?probe=a68454eff9) | Jan 13, 2022 |
| Dell          | Latitude E5470              | [f1f2897964](https://linux-hardware.org/?probe=f1f2897964) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [97274ab2da](https://linux-hardware.org/?probe=97274ab2da) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Dell          | Vostro 3405                 | [0e2887ca4f](https://linux-hardware.org/?probe=0e2887ca4f) | Jan 12, 2022 |
| ASUSTek       | X542BA                      | [d5180ebfbc](https://linux-hardware.org/?probe=d5180ebfbc) | Jan 12, 2022 |
| Dell          | Vostro 3446                 | [405aa63dc4](https://linux-hardware.org/?probe=405aa63dc4) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [34bf588c0b](https://linux-hardware.org/?probe=34bf588c0b) | Jan 11, 2022 |
| Lenovo        | ThinkPad E490 20N8S11G00    | [9db0c57d6e](https://linux-hardware.org/?probe=9db0c57d6e) | Jan 11, 2022 |
| ASUSTek       | X550LC                      | [b4de8de24e](https://linux-hardware.org/?probe=b4de8de24e) | Jan 11, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| Acer          | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04cd3cf175](https://linux-hardware.org/?probe=04cd3cf175) | Jan 10, 2022 |
| HP            | Presario CQ56               | [17e7a9c9d1](https://linux-hardware.org/?probe=17e7a9c9d1) | Jan 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [214a818f06](https://linux-hardware.org/?probe=214a818f06) | Jan 09, 2022 |
| Acer          | Aspire A514-52G             | [5f6504d850](https://linux-hardware.org/?probe=5f6504d850) | Jan 09, 2022 |
| HP            | Notebook                    | [66028752f5](https://linux-hardware.org/?probe=66028752f5) | Jan 09, 2022 |
| Dell          | Inspiron 15 3511            | [51d602d55f](https://linux-hardware.org/?probe=51d602d55f) | Jan 09, 2022 |
| Timi          | RedmiBook 15                | [7e9c17db98](https://linux-hardware.org/?probe=7e9c17db98) | Jan 08, 2022 |
| Timi          | RedmiBook 15                | [f52e0a4cf1](https://linux-hardware.org/?probe=f52e0a4cf1) | Jan 08, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | Laptop 15s-du2xxx           | [e6c704567e](https://linux-hardware.org/?probe=e6c704567e) | Jan 08, 2022 |
| Dell          | Inspiron 3501               | [804f5dab32](https://linux-hardware.org/?probe=804f5dab32) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Dell          | XPS 15 7590                 | [26bd64900c](https://linux-hardware.org/?probe=26bd64900c) | Jan 07, 2022 |
| Dell          | Inspiron 5570               | [298e22210d](https://linux-hardware.org/?probe=298e22210d) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| HP            | Laptop 15s-dr0xxx           | [be60e498db](https://linux-hardware.org/?probe=be60e498db) | Jan 06, 2022 |
| HP            | Laptop 15s-du2xxx           | [8213cb22ff](https://linux-hardware.org/?probe=8213cb22ff) | Jan 05, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [e4526aa9d8](https://linux-hardware.org/?probe=e4526aa9d8) | Jan 05, 2022 |
| Acer          | Aspire XXXX                 | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Dell          | Latitude E5440              | [15287271e2](https://linux-hardware.org/?probe=15287271e2) | Jan 02, 2022 |
| Dell          | XPS 15 7590                 | [3299ab62e8](https://linux-hardware.org/?probe=3299ab62e8) | Jan 02, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3fc1d4b98d](https://linux-hardware.org/?probe=3fc1d4b98d) | Dec 31, 2021 |
| Dell          | Inspiron 3542               | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Acer          | Aspire A515-51G             | [4d615644e4](https://linux-hardware.org/?probe=4d615644e4) | Dec 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [efa5e2c12a](https://linux-hardware.org/?probe=efa5e2c12a) | Dec 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c02c5039fb](https://linux-hardware.org/?probe=c02c5039fb) | Dec 31, 2021 |
| Dell          | Latitude 3420               | [a248c25326](https://linux-hardware.org/?probe=a248c25326) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b330382ad9](https://linux-hardware.org/?probe=b330382ad9) | Dec 31, 2021 |
| HP            | Presario CQ56               | [aacf56218d](https://linux-hardware.org/?probe=aacf56218d) | Dec 31, 2021 |
| Dell          | Inspiron 5437               | [d33def1f56](https://linux-hardware.org/?probe=d33def1f56) | Dec 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [881eb5100e](https://linux-hardware.org/?probe=881eb5100e) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| Lenovo        | B460e                       | [808fae9674](https://linux-hardware.org/?probe=808fae9674) | Dec 30, 2021 |
| Dell          | Latitude 5410               | [7d5de2cff2](https://linux-hardware.org/?probe=7d5de2cff2) | Dec 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e0bce9d433](https://linux-hardware.org/?probe=e0bce9d433) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [01d210ed18](https://linux-hardware.org/?probe=01d210ed18) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Inspiron 5537               | [f29a5f0ecb](https://linux-hardware.org/?probe=f29a5f0ecb) | Dec 28, 2021 |
| Acer          | Swift SF315-51G             | [3a5fb0d8ac](https://linux-hardware.org/?probe=3a5fb0d8ac) | Dec 28, 2021 |
| Acer          | Swift SF315-51G             | [cf31c436c0](https://linux-hardware.org/?probe=cf31c436c0) | Dec 28, 2021 |
| Dell          | Vostro 3590                 | [31338a4a85](https://linux-hardware.org/?probe=31338a4a85) | Dec 27, 2021 |
| Toshiba       | TECRA R840                  | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| MSI           | GL63 9RCX                   | [ad2628ee28](https://linux-hardware.org/?probe=ad2628ee28) | Dec 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [114ec171a7](https://linux-hardware.org/?probe=114ec171a7) | Dec 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [12c90ed760](https://linux-hardware.org/?probe=12c90ed760) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [4e4cc2bfb3](https://linux-hardware.org/?probe=4e4cc2bfb3) | Dec 26, 2021 |
| Dell          | Inspiron 5558               | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [df6e5df46d](https://linux-hardware.org/?probe=df6e5df46d) | Dec 24, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3f3fd8aa2e](https://linux-hardware.org/?probe=3f3fd8aa2e) | Dec 24, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [894fb9a205](https://linux-hardware.org/?probe=894fb9a205) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [d22c47d314](https://linux-hardware.org/?probe=d22c47d314) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1638195805](https://linux-hardware.org/?probe=1638195805) | Dec 22, 2021 |
| Dell          | Inspiron 5570               | [2d2ccb3dea](https://linux-hardware.org/?probe=2d2ccb3dea) | Dec 22, 2021 |
| Lenovo        | Legion Y7000 2019 1050 8... | [b16546ce2c](https://linux-hardware.org/?probe=b16546ce2c) | Dec 22, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [7f946b3d42](https://linux-hardware.org/?probe=7f946b3d42) | Dec 21, 2021 |
| ASUSTek       | X510UNR                     | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| HP            | ProBook 640 G3              | [be09fb6d79](https://linux-hardware.org/?probe=be09fb6d79) | Dec 21, 2021 |
| Dell          | Inspiron 1545               | [f163884100](https://linux-hardware.org/?probe=f163884100) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Dell          | Precision M4800             | [3dc8c7e96d](https://linux-hardware.org/?probe=3dc8c7e96d) | Dec 20, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ae4b7d946e](https://linux-hardware.org/?probe=ae4b7d946e) | Dec 18, 2021 |
| Lenovo        | G50-80 80E5                 | [2f8a6719a1](https://linux-hardware.org/?probe=2f8a6719a1) | Dec 18, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [45bee865bc](https://linux-hardware.org/?probe=45bee865bc) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dda5e17a21](https://linux-hardware.org/?probe=dda5e17a21) | Dec 17, 2021 |
| Lenovo        | ThinkPad T490 20RYS07R00    | [0bdc5ce080](https://linux-hardware.org/?probe=0bdc5ce080) | Dec 16, 2021 |
| Acer          | Aspire A514-54              | [186dd90bed](https://linux-hardware.org/?probe=186dd90bed) | Dec 16, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [b671826144](https://linux-hardware.org/?probe=b671826144) | Dec 16, 2021 |
| Toshiba       | Satellite C600              | [dd417ecb87](https://linux-hardware.org/?probe=dd417ecb87) | Dec 15, 2021 |
| Lenovo        | G50-80 80E5                 | [349550727a](https://linux-hardware.org/?probe=349550727a) | Dec 14, 2021 |
| HP            | 15                          | [70e648805f](https://linux-hardware.org/?probe=70e648805f) | Dec 14, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [397525b971](https://linux-hardware.org/?probe=397525b971) | Dec 14, 2021 |
| Acer          | Aspire E5-532G              | [8cbbaee4ad](https://linux-hardware.org/?probe=8cbbaee4ad) | Dec 14, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [28d196a1a0](https://linux-hardware.org/?probe=28d196a1a0) | Dec 14, 2021 |
| Lenovo        | G50-80 80E5                 | [f7678361d9](https://linux-hardware.org/?probe=f7678361d9) | Dec 14, 2021 |
| HP            | Pavilion g6                 | [a39e3fe72e](https://linux-hardware.org/?probe=a39e3fe72e) | Dec 13, 2021 |
| Lenovo        | ThinkPad X280 20KES51D00    | [65730aa825](https://linux-hardware.org/?probe=65730aa825) | Dec 13, 2021 |
| HP            | Pavilion dv6                | [24e1124f28](https://linux-hardware.org/?probe=24e1124f28) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [807bd77769](https://linux-hardware.org/?probe=807bd77769) | Dec 12, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d09c52b686](https://linux-hardware.org/?probe=d09c52b686) | Dec 11, 2021 |
| Dell          | Latitude 3420               | [ebeaeaa5c8](https://linux-hardware.org/?probe=ebeaeaa5c8) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Dell          | Inspiron 5547               | [6b6f86a9f7](https://linux-hardware.org/?probe=6b6f86a9f7) | Dec 10, 2021 |
| HP            | Laptop 15-bs0xx             | [6dcc36a8bb](https://linux-hardware.org/?probe=6dcc36a8bb) | Dec 10, 2021 |
| HP            | Laptop 15-bs0xx             | [c2e4bc90c5](https://linux-hardware.org/?probe=c2e4bc90c5) | Dec 09, 2021 |
| HP            | Laptop 15s-gr0xxx           | [b87ba06410](https://linux-hardware.org/?probe=b87ba06410) | Dec 09, 2021 |
| HP            | Laptop 15g-dx0xxx           | [1bdf2932b8](https://linux-hardware.org/?probe=1bdf2932b8) | Dec 09, 2021 |
| Dell          | Latitude E5440              | [5b77ab747a](https://linux-hardware.org/?probe=5b77ab747a) | Dec 09, 2021 |
| Dell          | Latitude 3410               | [4b84ebe353](https://linux-hardware.org/?probe=4b84ebe353) | Dec 08, 2021 |
| Lenovo        | ThinkPad L13 20R3S10R00     | [fa749fa343](https://linux-hardware.org/?probe=fa749fa343) | Dec 08, 2021 |
| Dell          | Latitude 3410               | [c2a6a9ad6b](https://linux-hardware.org/?probe=c2a6a9ad6b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [a4ef5df716](https://linux-hardware.org/?probe=a4ef5df716) | Dec 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2552e40ec2](https://linux-hardware.org/?probe=2552e40ec2) | Dec 08, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| HP            | Laptop 15g-dx0xxx           | [646587b02b](https://linux-hardware.org/?probe=646587b02b) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7d51663cb1](https://linux-hardware.org/?probe=7d51663cb1) | Dec 07, 2021 |
| Acer          | Aspire A315-42              | [c5d73b2d3a](https://linux-hardware.org/?probe=c5d73b2d3a) | Dec 07, 2021 |
| AVITA         | NS14A6                      | [0e6d32c71b](https://linux-hardware.org/?probe=0e6d32c71b) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| HP            | Laptop 15s-fq1xxx           | [aa6c695947](https://linux-hardware.org/?probe=aa6c695947) | Dec 06, 2021 |
| Acer          | Nitro AN515-45              | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| HP            | ProBook 440 G2              | [0d522a3c93](https://linux-hardware.org/?probe=0d522a3c93) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| HP            | Notebook                    | [9f7082bedb](https://linux-hardware.org/?probe=9f7082bedb) | Dec 03, 2021 |
| Sony          | SVE15123CNB                 | [f17d814746](https://linux-hardware.org/?probe=f17d814746) | Dec 03, 2021 |
| Sony          | SVE15123CNB                 | [d34798375b](https://linux-hardware.org/?probe=d34798375b) | Dec 03, 2021 |
| HP            | Laptop 15-da1xxx            | [d35f5cfc98](https://linux-hardware.org/?probe=d35f5cfc98) | Dec 03, 2021 |
| Dell          | Latitude E6520              | [3377d2b25b](https://linux-hardware.org/?probe=3377d2b25b) | Dec 03, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [3ebefe7b95](https://linux-hardware.org/?probe=3ebefe7b95) | Dec 03, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [81b2b16aab](https://linux-hardware.org/?probe=81b2b16aab) | Dec 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS4... | [fd15abec74](https://linux-hardware.org/?probe=fd15abec74) | Dec 02, 2021 |
| HP            | 15                          | [8d1ef12e0e](https://linux-hardware.org/?probe=8d1ef12e0e) | Dec 02, 2021 |
| LG Electro... | 14Z990-V.AR52A2             | [316684da39](https://linux-hardware.org/?probe=316684da39) | Dec 01, 2021 |
| ASUSTek       | X556UQK                     | [a07eddd257](https://linux-hardware.org/?probe=a07eddd257) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [e9fd574b87](https://linux-hardware.org/?probe=e9fd574b87) | Nov 30, 2021 |
| Lenovo        | G560 20042                  | [ec6397d5a2](https://linux-hardware.org/?probe=ec6397d5a2) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| Acer          | Aspire 5560                 | [db900fbb00](https://linux-hardware.org/?probe=db900fbb00) | Nov 29, 2021 |
| Dell          | Vostro 2420                 | [3135a53e32](https://linux-hardware.org/?probe=3135a53e32) | Nov 29, 2021 |
| Sony          | SVE14117GNB                 | [5af55d3525](https://linux-hardware.org/?probe=5af55d3525) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | [e4f4713ac2](https://linux-hardware.org/?probe=e4f4713ac2) | Nov 29, 2021 |
| HP            | Pavilion 15                 | [0e07acbea7](https://linux-hardware.org/?probe=0e07acbea7) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude E6520              | [805faf7481](https://linux-hardware.org/?probe=805faf7481) | Nov 28, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [94a08519cc](https://linux-hardware.org/?probe=94a08519cc) | Nov 28, 2021 |
| Dell          | Vostro 2420                 | [4dd6f799b3](https://linux-hardware.org/?probe=4dd6f799b3) | Nov 28, 2021 |
| Dell          | Latitude 3490               | [d93276d2fa](https://linux-hardware.org/?probe=d93276d2fa) | Nov 28, 2021 |
| Timi          | Mi NoteBook Pro             | [9bc4093f84](https://linux-hardware.org/?probe=9bc4093f84) | Nov 28, 2021 |
| HP            | Pavilion dm4                | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [d33f38e279](https://linux-hardware.org/?probe=d33f38e279) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| ASUSTek       | X556UQK                     | [38ca30691b](https://linux-hardware.org/?probe=38ca30691b) | Nov 26, 2021 |
| Dell          | Latitude 3450               | [216b89c0f8](https://linux-hardware.org/?probe=216b89c0f8) | Nov 26, 2021 |
| HP            | 240 G7                      | [943883dd42](https://linux-hardware.org/?probe=943883dd42) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| HP            | Compaq 15                   | [8aede4cf2d](https://linux-hardware.org/?probe=8aede4cf2d) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | [995eaf8345](https://linux-hardware.org/?probe=995eaf8345) | Nov 25, 2021 |
| HP            | Laptop 15-bs0xx             | [31dd043382](https://linux-hardware.org/?probe=31dd043382) | Nov 25, 2021 |
| Dell          | Latitude 7420               | [3a99101a33](https://linux-hardware.org/?probe=3a99101a33) | Nov 25, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [55a7f1df10](https://linux-hardware.org/?probe=55a7f1df10) | Nov 24, 2021 |
| HP            | Laptop 15s-gr0xxx           | [839f56bd09](https://linux-hardware.org/?probe=839f56bd09) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| HP            | Laptop 14q-cs0xxx           | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| Dell          | Precision 3560              | [9c4ede18f3](https://linux-hardware.org/?probe=9c4ede18f3) | Nov 23, 2021 |
| Lenovo        | G400s Touch 20262           | [e4431f506c](https://linux-hardware.org/?probe=e4431f506c) | Nov 23, 2021 |
| Acer          | One S1002                   | [8ae39c3aaf](https://linux-hardware.org/?probe=8ae39c3aaf) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| HP            | 15                          | [1753404669](https://linux-hardware.org/?probe=1753404669) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Coconics P... | CNBIC-AA01                  | [f0f3a4c995](https://linux-hardware.org/?probe=f0f3a4c995) | Nov 22, 2021 |
| Dell          | XPS 13 9300                 | [1c031d5824](https://linux-hardware.org/?probe=1c031d5824) | Nov 22, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| HP            | 15                          | [bca58eb5e0](https://linux-hardware.org/?probe=bca58eb5e0) | Nov 22, 2021 |
| Dell          | Latitude 3420               | [c55e359625](https://linux-hardware.org/?probe=c55e359625) | Nov 22, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7a91d6d644](https://linux-hardware.org/?probe=7a91d6d644) | Nov 22, 2021 |
| Acer          | Aspire A315-42              | [aa83ee865b](https://linux-hardware.org/?probe=aa83ee865b) | Nov 21, 2021 |
| Acer          | TravelMate P214-53          | [1b3974717e](https://linux-hardware.org/?probe=1b3974717e) | Nov 20, 2021 |
| HP            | ProBook 4420s               | [2e24dd8185](https://linux-hardware.org/?probe=2e24dd8185) | Nov 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [18b6969d5d](https://linux-hardware.org/?probe=18b6969d5d) | Nov 20, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1afc762c2d](https://linux-hardware.org/?probe=1afc762c2d) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | [1a1f1149c1](https://linux-hardware.org/?probe=1a1f1149c1) | Nov 18, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [656d8093b0](https://linux-hardware.org/?probe=656d8093b0) | Nov 18, 2021 |
| ASUSTek       | X540LA                      | [3c531f009d](https://linux-hardware.org/?probe=3c531f009d) | Nov 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e85f83dd93](https://linux-hardware.org/?probe=e85f83dd93) | Nov 17, 2021 |
| HP            | Laptop 15-da1xxx            | [fa80a56340](https://linux-hardware.org/?probe=fa80a56340) | Nov 17, 2021 |
| Dell          | Inspiron 5515               | [acd9469780](https://linux-hardware.org/?probe=acd9469780) | Nov 16, 2021 |
| ASUSTek       | X550LD                      | [6337158c74](https://linux-hardware.org/?probe=6337158c74) | Nov 16, 2021 |
| HP            | Laptop 15-bs0xx             | [63b0a88544](https://linux-hardware.org/?probe=63b0a88544) | Nov 16, 2021 |
| HP            | 15                          | [43b117b7a1](https://linux-hardware.org/?probe=43b117b7a1) | Nov 16, 2021 |
| Dell          | Precision M4800             | [39b69fa4c0](https://linux-hardware.org/?probe=39b69fa4c0) | Nov 15, 2021 |
| Dell          | Inspiron 14 5408            | [d484fd58e6](https://linux-hardware.org/?probe=d484fd58e6) | Nov 15, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 680       | 24.54%  |
| Ubuntu 18.04                 | 277       | 10%     |
| Ubuntu 22.04                 | 104       | 3.75%   |
| Arch                         | 80        | 2.89%   |
| KDE neon 20.04               | 56        | 2.02%   |
| Pop!_OS 20.04                | 54        | 1.95%   |
| Fedora 36                    | 49        | 1.77%   |
| Pop!_OS 21.04                | 48        | 1.73%   |
| Ubuntu 20.10                 | 46        | 1.66%   |
| Fedora 34                    | 45        | 1.62%   |
| Arch Rolling                 | 44        | 1.59%   |
| Zorin 16                     | 41        | 1.48%   |
| Ubuntu 19.10                 | 39        | 1.41%   |
| Zorin 15                     | 38        | 1.37%   |
| Ubuntu 21.04                 | 38        | 1.37%   |
| Pop!_OS 20.10                | 36        | 1.3%    |
| Pop!_OS 22.04                | 33        | 1.19%   |
| Ubuntu 19.04                 | 32        | 1.15%   |
| OpenMandriva 4.2             | 32        | 1.15%   |
| Fedora 35                    | 32        | 1.15%   |
| ArcoLinux Rolling            | 32        | 1.15%   |
| Ubuntu 21.10                 | 29        | 1.05%   |
| Manjaro                      | 28        | 1.01%   |
| Linux Mint 20.2              | 26        | 0.94%   |
| Fedora 32                    | 26        | 0.94%   |
| Ubuntu Unity 16.04           | 25        | 0.9%    |
| OpenMandriva 4.3             | 25        | 0.9%    |
| Linux Mint 20.3              | 25        | 0.9%    |
| Linux Mint 20.1              | 25        | 0.9%    |
| Fedora 33                    | 25        | 0.9%    |
| Linux Mint 20                | 23        | 0.83%   |
| Kubuntu 20.04                | 19        | 0.69%   |
| Debian 11                    | 19        | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 0.65%   |
| Elementary 6.1               | 18        | 0.65%   |
| Pop!_OS 21.10                | 16        | 0.58%   |
| Linux Mint 19.3              | 16        | 0.58%   |
| Ubuntu 16.04                 | 15        | 0.54%   |
| Fedora 31                    | 14        | 0.51%   |
| Elementary 6                 | 14        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1243      | 46.42%  |
| Fedora        | 184       | 6.87%   |
| Pop!_OS       | 180       | 6.72%   |
| Arch          | 118       | 4.41%   |
| Linux Mint    | 117       | 4.37%   |
| Manjaro       | 84        | 3.14%   |
| Zorin         | 79        | 2.95%   |
| OpenMandriva  | 68        | 2.54%   |
| KDE neon      | 64        | 2.39%   |
| Debian        | 50        | 1.87%   |
| Kali          | 49        | 1.83%   |
| Elementary    | 43        | 1.61%   |
| Ubuntu Unity  | 41        | 1.53%   |
| Kubuntu       | 41        | 1.53%   |
| ArcoLinux     | 38        | 1.42%   |
| Endless       | 35        | 1.31%   |
| Xubuntu       | 22        | 0.82%   |
| openSUSE      | 21        | 0.78%   |
| ROSA          | 16        | 0.6%    |
| RHEL          | 15        | 0.56%   |
| Garuda Linux  | 15        | 0.56%   |
| EndeavourOS   | 14        | 0.52%   |
| Clear Linux   | 13        | 0.49%   |
| Ubuntu Budgie | 12        | 0.45%   |
| Ubuntu MATE   | 9         | 0.34%   |
| Void Linux    | 8         | 0.3%    |
| Solus         | 8         | 0.3%    |
| Lubuntu       | 8         | 0.3%    |
| Xero          | 7         | 0.26%   |
| CentOS        | 7         | 0.26%   |
| Parrot        | 6         | 0.22%   |
| Gentoo        | 6         | 0.22%   |
| Artix         | 6         | 0.22%   |
| MX            | 5         | 0.19%   |
| Nobara        | 4         | 0.15%   |
| LMDE          | 4         | 0.15%   |
| UbuntuDDE     | 3         | 0.11%   |
| Feren OS      | 3         | 0.11%   |
| Slackware     | 2         | 0.07%   |
| Peppermint    | 2         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 111       | 3.74%   |
| 5.4.0-40-generic         | 54        | 1.82%   |
| 5.11.0-27-generic        | 33        | 1.11%   |
| 5.10.14-desktop-1omv4002 | 32        | 1.08%   |
| 5.4.0-48-generic         | 30        | 1.01%   |
| 5.4.0-26-generic         | 30        | 1.01%   |
| 5.4.0-47-generic         | 29        | 0.98%   |
| 5.11.0-7620-generic      | 28        | 0.94%   |
| 5.4.0-58-generic         | 27        | 0.91%   |
| 5.4.0-52-generic         | 26        | 0.88%   |
| 5.16.7-desktop-1omv4003  | 25        | 0.84%   |
| 5.4.0-29-generic         | 24        | 0.81%   |
| 5.3.0-28-generic         | 24        | 0.81%   |
| 5.11.0-40-generic        | 23        | 0.77%   |
| 5.4.0-45-generic         | 22        | 0.74%   |
| 5.11.0-43-generic        | 22        | 0.74%   |
| 5.11.0-25-generic        | 22        | 0.74%   |
| 5.8.0-53-generic         | 21        | 0.71%   |
| 5.8.0-44-generic         | 21        | 0.71%   |
| 5.8.0-43-generic         | 21        | 0.71%   |
| 5.15.0-46-generic        | 21        | 0.71%   |
| 5.11.0-38-generic        | 21        | 0.71%   |
| 5.8.0-55-generic         | 20        | 0.67%   |
| 5.8.0-48-generic         | 20        | 0.67%   |
| 5.4.0-37-generic         | 20        | 0.67%   |
| 5.3.0-40-generic         | 20        | 0.67%   |
| 5.4.0-74-generic         | 19        | 0.64%   |
| 5.11.0-37-generic        | 19        | 0.64%   |
| 5.4.0-39-generic         | 18        | 0.61%   |
| 5.13.0-30-generic        | 18        | 0.61%   |
| 4.15.0-45-generic        | 18        | 0.61%   |
| 5.8.0-7630-generic       | 17        | 0.57%   |
| 5.3.0-51-generic         | 17        | 0.57%   |
| 5.13.0-40-generic        | 17        | 0.57%   |
| 5.0.0-37-generic         | 17        | 0.57%   |
| 5.8.0-59-generic         | 15        | 0.51%   |
| 5.4.0-54-generic         | 15        | 0.51%   |
| 5.4.0-33-generic         | 15        | 0.51%   |
| 5.15.0-48-generic        | 15        | 0.51%   |
| 4.18.0-15-generic        | 15        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 644       | 22.64%  |
| 5.11.0  | 259       | 9.11%   |
| 5.8.0   | 229       | 8.05%   |
| 4.15.0  | 153       | 5.38%   |
| 5.13.0  | 147       | 5.17%   |
| 5.3.0   | 144       | 5.06%   |
| 5.15.0  | 137       | 4.82%   |
| 5.0.0   | 91        | 3.2%    |
| 4.18.0  | 63        | 2.22%   |
| 5.10.0  | 47        | 1.65%   |
| 5.10.14 | 32        | 1.13%   |
| 5.16.7  | 26        | 0.91%   |
| 5.14.0  | 19        | 0.67%   |
| 4.4.0   | 19        | 0.67%   |
| 5.17.5  | 17        | 0.6%    |
| 5.19.0  | 16        | 0.56%   |
| 4.19.0  | 14        | 0.49%   |
| 5.9.0   | 11        | 0.39%   |
| 5.7.0   | 11        | 0.39%   |
| 5.18.0  | 9         | 0.32%   |
| 5.15.11 | 9         | 0.32%   |
| 5.17.4  | 8         | 0.28%   |
| 5.16.11 | 8         | 0.28%   |
| 5.15.5  | 8         | 0.28%   |
| 5.13.9  | 8         | 0.28%   |
| 5.13.12 | 8         | 0.28%   |
| 5.6.0   | 7         | 0.25%   |
| 5.19.11 | 7         | 0.25%   |
| 5.18.6  | 7         | 0.25%   |
| 5.17.9  | 7         | 0.25%   |
| 5.15.8  | 7         | 0.25%   |
| 5.9.16  | 6         | 0.21%   |
| 5.8.6   | 6         | 0.21%   |
| 5.8.11  | 6         | 0.21%   |
| 5.6.6   | 6         | 0.21%   |
| 5.5.0   | 6         | 0.21%   |
| 5.16.19 | 6         | 0.21%   |
| 5.16.0  | 6         | 0.21%   |
| 5.15.13 | 6         | 0.21%   |
| 5.15.12 | 6         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 670       | 23.83%  |
| 5.11    | 291       | 10.35%  |
| 5.8     | 276       | 9.82%   |
| 5.15    | 225       | 8%      |
| 5.13    | 187       | 6.65%   |
| 5.3     | 164       | 5.83%   |
| 4.15    | 153       | 5.44%   |
| 5.10    | 133       | 4.73%   |
| 5.0     | 92        | 3.27%   |
| 5.16    | 73        | 2.6%    |
| 5.17    | 66        | 2.35%   |
| 4.18    | 65        | 2.31%   |
| 5.19    | 58        | 2.06%   |
| 5.14    | 51        | 1.81%   |
| 5.18    | 49        | 1.74%   |
| 5.12    | 45        | 1.6%    |
| 5.9     | 43        | 1.53%   |
| 5.7     | 40        | 1.42%   |
| 5.6     | 27        | 0.96%   |
| 5.5     | 22        | 0.78%   |
| 4.4     | 20        | 0.71%   |
| 4.19    | 20        | 0.71%   |
| 4.9     | 11        | 0.39%   |
| 6.0     | 8         | 0.28%   |
| 5.2     | 6         | 0.21%   |
| 5.1     | 3         | 0.11%   |
| 3.16    | 3         | 0.11%   |
| 4.13    | 2         | 0.07%   |
| 4.1     | 2         | 0.07%   |
| 3.10    | 2         | 0.07%   |
| 4.20    | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 4.10    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2548      | 98.57%  |
| i686   | 36        | 1.39%   |
| armv7l | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1576      | 58.76%  |
| Unknown           | 315       | 11.74%  |
| KDE5              | 258       | 9.62%   |
| XFCE              | 120       | 4.47%   |
| X-Cinnamon        | 90        | 3.36%   |
| KDE               | 74        | 2.76%   |
| Unity             | 43        | 1.6%    |
| Pantheon          | 41        | 1.53%   |
| Cinnamon          | 30        | 1.12%   |
| MATE              | 26        | 0.97%   |
| GNOME Flashback   | 20        | 0.75%   |
| Budgie            | 18        | 0.67%   |
| i3                | 13        | 0.48%   |
| Deepin            | 9         | 0.34%   |
| LXQt              | 8         | 0.3%    |
| LXDE              | 8         | 0.3%    |
| KDE4              | 6         | 0.22%   |
| awesome           | 6         | 0.22%   |
| qtile             | 4         | 0.15%   |
| bspwm             | 4         | 0.15%   |
| sway              | 3         | 0.11%   |
| openbox           | 2         | 0.07%   |
| LeftWM            | 2         | 0.07%   |
| Yaru:ubuntu:GNOME | 1         | 0.04%   |
| xmonad            | 1         | 0.04%   |
| lightdm-xsession  | 1         | 0.04%   |
| i3-with-shmlog    | 1         | 0.04%   |
| i3-gaps           | 1         | 0.04%   |
| GNOME Classic     | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2014      | 75.91%  |
| Wayland | 413       | 15.57%  |
| Unknown | 197       | 7.43%   |
| Tty     | 29        | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1427      | 53.45%  |
| GDM     | 531       | 19.89%  |
| SDDM    | 240       | 8.99%   |
| GDM3    | 217       | 8.13%   |
| LightDM | 159       | 5.96%   |
| TDM     | 79        | 2.96%   |
| KDM     | 6         | 0.22%   |
| XDM     | 4         | 0.15%   |
| LXDM    | 3         | 0.11%   |
| SLiM    | 2         | 0.07%   |
| Ly      | 2         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IN   | 1610      | 60.25%  |
| en_US   | 700       | 26.2%   |
| Unknown | 251       | 9.39%   |
| en_GB   | 48        | 1.8%    |
| C       | 39        | 1.46%   |
| en_AG   | 6         | 0.22%   |
| zh_TW   | 2         | 0.07%   |
| POSIX   | 2         | 0.07%   |
| mr_IN   | 2         | 0.07%   |
| en_IE   | 2         | 0.07%   |
| en_CA   | 2         | 0.07%   |
| en_AU   | 2         | 0.07%   |
| ks_IN   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_SG   | 1         | 0.04%   |
| en_BW   | 1         | 0.04%   |
| Default | 1         | 0.04%   |
| C.UTF8  | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1622      | 61.77%  |
| BIOS | 1004      | 38.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2213      | 84.18%  |
| Btrfs   | 209       | 7.95%   |
| Overlay | 96        | 3.65%   |
| Unknown | 58        | 2.21%   |
| Xfs     | 29        | 1.1%    |
| Zfs     | 9         | 0.34%   |
| Ext2    | 7         | 0.27%   |
| Ext3    | 5         | 0.19%   |
| Tmpfs   | 1         | 0.04%   |
| F2fs    | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1524      | 58.04%  |
| GPT     | 919       | 35%     |
| MBR     | 183       | 6.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2325      | 88.67%  |
| Yes       | 297       | 11.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1564      | 59.65%  |
| Yes       | 1058      | 40.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 635       | 24.57%  |
| Dell                     | 595       | 23.03%  |
| Hewlett-Packard          | 588       | 22.76%  |
| ASUSTek Computer         | 316       | 12.23%  |
| Acer                     | 207       | 8.01%   |
| Sony                     | 46        | 1.78%   |
| Toshiba                  | 32        | 1.24%   |
| MSI                      | 32        | 1.24%   |
| Samsung Electronics      | 22        | 0.85%   |
| Apple                    | 17        | 0.66%   |
| AVITA                    | 16        | 0.62%   |
| Timi                     | 11        | 0.43%   |
| HCL Infosystems Limited  | 7         | 0.27%   |
| Fujitsu                  | 7         | 0.27%   |
| LG Electronics           | 5         | 0.19%   |
| HUAWEI                   | 5         | 0.19%   |
| Google                   | 5         | 0.19%   |
| Intel                    | 4         | 0.15%   |
| eMachines                | 4         | 0.15%   |
| Alienware                | 4         | 0.15%   |
| realme                   | 3         | 0.12%   |
| Unknown                  | 3         | 0.12%   |
| Razer                    | 2         | 0.08%   |
| MICROMAX                 | 2         | 0.08%   |
| Gateway                  | 2         | 0.08%   |
| Coconics Private Limited | 2         | 0.08%   |
| WIPRO                    | 1         | 0.04%   |
| System76                 | 1         | 0.04%   |
| ONDA                     | 1         | 0.04%   |
| Notebook                 | 1         | 0.04%   |
| NEC Computers            | 1         | 0.04%   |
| iBall                    | 1         | 0.04%   |
| HASEE Computer           | 1         | 0.04%   |
| Flipkart India Pvt.      | 1         | 0.04%   |
| EVOO                     | 1         | 0.04%   |
| Eluktronics              | 1         | 0.04%   |
| Dynabook                 | 1         | 0.04%   |
| AMI                      | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Notebook                            | 68        | 2.63%   |
| HP 15                                  | 27        | 1.04%   |
| HP Pavilion 15                         | 26        | 1.01%   |
| Dell Inspiron 3542                     | 25        | 0.97%   |
| HP Pavilion g6                         | 23        | 0.89%   |
| HP Laptop 15-bs0xx                     | 21        | 0.81%   |
| Dell Inspiron 15-3567                  | 21        | 0.81%   |
| Dell Inspiron 5570                     | 20        | 0.77%   |
| Lenovo E41-25 81FS                     | 17        | 0.66%   |
| Dell Inspiron 3521                     | 17        | 0.66%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 16        | 0.62%   |
| HP Pavilion Notebook                   | 16        | 0.62%   |
| Acer Aspire A715-75G                   | 16        | 0.62%   |
| Unknown                                | 15        | 0.58%   |
| Dell Vostro 3480                       | 14        | 0.54%   |
| ASUS TUF Gaming FX505DT_FX505DT        | 14        | 0.54%   |
| Lenovo G50-80 80E5                     | 13        | 0.5%    |
| Dell Vostro 3578                       | 12        | 0.46%   |
| Dell Vostro 15-3568                    | 12        | 0.46%   |
| Lenovo G50-45 80E3                     | 11        | 0.43%   |
| HP Laptop 15-da0xxx                    | 11        | 0.43%   |
| HP Laptop 15-bw0xx                     | 11        | 0.43%   |
| Dell Inspiron 5559                     | 11        | 0.43%   |
| ASUS X510UNR                           | 11        | 0.43%   |
| HP Pavilion dv6                        | 10        | 0.39%   |
| Dell Vostro 3478                       | 10        | 0.39%   |
| ASUS X556UQK                           | 10        | 0.39%   |
| Lenovo ThinkBook 14-IML 20RV           | 9         | 0.35%   |
| Lenovo IdeaPad 520-15IKB 81BF          | 9         | 0.35%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 9         | 0.35%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 9         | 0.35%   |
| Dell Inspiron 5520                     | 9         | 0.35%   |
| Dell Inspiron 3541                     | 9         | 0.35%   |
| AVITA NS14A8                           | 9         | 0.35%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL | 9         | 0.35%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR   | 9         | 0.35%   |
| ASUS TUF Gaming FX505DY_FX505DY        | 9         | 0.35%   |
| Lenovo IdeaPad S540-15IWL D 81NE       | 8         | 0.31%   |
| Lenovo IdeaPad 320-15IKB 80XL          | 8         | 0.31%   |
| Lenovo G580 20157                      | 8         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 288       | 11.15%  |
| Lenovo IdeaPad    | 227       | 8.78%   |
| Lenovo ThinkPad   | 218       | 8.44%   |
| HP Pavilion       | 160       | 6.19%   |
| HP Laptop         | 135       | 5.22%   |
| ASUS VivoBook     | 124       | 4.8%    |
| Dell Latitude     | 120       | 4.64%   |
| Acer Aspire       | 118       | 4.57%   |
| Dell Vostro       | 117       | 4.53%   |
| HP Notebook       | 69        | 2.67%   |
| HP EliteBook      | 48        | 1.86%   |
| HP ProBook        | 42        | 1.63%   |
| ASUS TUF          | 36        | 1.39%   |
| ASUS ASUS         | 31        | 1.2%    |
| HP 15             | 28        | 1.08%   |
| Toshiba Satellite | 27        | 1.04%   |
| Dell XPS          | 27        | 1.04%   |
| Acer Nitro        | 27        | 1.04%   |
| Lenovo Legion     | 26        | 1.01%   |
| ASUS ROG          | 26        | 1.01%   |
| Acer Swift        | 24        | 0.93%   |
| Lenovo ThinkBook  | 19        | 0.74%   |
| Lenovo E41-25     | 17        | 0.66%   |
| Dell Precision    | 15        | 0.58%   |
| Unknown           | 15        | 0.58%   |
| HP OMEN           | 14        | 0.54%   |
| Acer Predator     | 14        | 0.54%   |
| Lenovo G50-80     | 13        | 0.5%    |
| Dell G3           | 13        | 0.5%    |
| Lenovo G50-45     | 11        | 0.43%   |
| ASUS X510UNR      | 11        | 0.43%   |
| Timi Mi           | 10        | 0.39%   |
| HP Compaq         | 10        | 0.39%   |
| HP 245            | 10        | 0.39%   |
| ASUS X556UQK      | 10        | 0.39%   |
| HP Presario       | 9         | 0.35%   |
| AVITA NS14A8      | 9         | 0.35%   |
| ASUS ZenBook      | 9         | 0.35%   |
| Lenovo G580       | 8         | 0.31%   |
| HP ENVY           | 8         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 384       | 14.86%  |
| 2018    | 356       | 13.78%  |
| 2020    | 296       | 11.46%  |
| 2017    | 234       | 9.06%   |
| 2021    | 198       | 7.66%   |
| 2016    | 174       | 6.73%   |
| 2011    | 161       | 6.23%   |
| 2013    | 158       | 6.11%   |
| 2014    | 146       | 5.65%   |
| 2012    | 146       | 5.65%   |
| 2015    | 130       | 5.03%   |
| 2010    | 98        | 3.79%   |
| 2008    | 42        | 1.63%   |
| 2009    | 30        | 1.16%   |
| 2022    | 18        | 0.7%    |
| 2007    | 8         | 0.31%   |
| 2006    | 2         | 0.08%   |
| 2005    | 1         | 0.04%   |
| 2003    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2584      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2228      | 85.43%  |
| Enabled  | 380       | 14.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2575      | 99.65%  |
| Yes  | 9         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 930       | 35.56%  |
| 3.01-4.0    | 622       | 23.79%  |
| 8.01-16.0   | 500       | 19.12%  |
| 16.01-24.0  | 375       | 14.34%  |
| 1.01-2.0    | 83        | 3.17%   |
| 32.01-64.0  | 60        | 2.29%   |
| 2.01-3.0    | 23        | 0.88%   |
| 24.01-32.0  | 12        | 0.46%   |
| 0.51-1.0    | 6         | 0.23%   |
| 64.01-256.0 | 3         | 0.11%   |
| 0.01-0.5    | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 917       | 32.52%  |
| 1.01-2.0   | 880       | 31.21%  |
| 3.01-4.0   | 430       | 15.25%  |
| 4.01-8.0   | 411       | 14.57%  |
| 0.51-1.0   | 87        | 3.09%   |
| 8.01-16.0  | 78        | 2.77%   |
| 0.01-0.5   | 12        | 0.43%   |
| 16.01-24.0 | 4         | 0.14%   |
| 24.01-32.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1958      | 74.93%  |
| 2      | 601       | 23%     |
| 3      | 31        | 1.19%   |
| 0      | 22        | 0.84%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1625      | 62.52%  |
| Yes       | 974       | 37.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2121      | 81.92%  |
| No        | 468       | 18.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2555      | 98.8%   |
| No        | 31        | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2271      | 87.08%  |
| No        | 337       | 12.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| India   | 2584      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Bengaluru     | 321       | 11.62%  |
| Mumbai        | 175       | 6.33%   |
| Chennai       | 173       | 6.26%   |
| Pune          | 137       | 4.96%   |
| New Delhi     | 135       | 4.89%   |
| Hyderabad     | 133       | 4.81%   |
| Delhi         | 117       | 4.23%   |
| Kolkata       | 111       | 4.02%   |
| Ahmedabad     | 60        | 2.17%   |
| Lucknow       | 59        | 2.14%   |
| Ernakulam     | 57        | 2.06%   |
| Patna         | 48        | 1.74%   |
| Jaipur        | 46        | 1.66%   |
| Gurgaon       | 42        | 1.52%   |
| Coimbatore    | 37        | 1.34%   |
| Indore        | 36        | 1.3%    |
| Navi Mumbai   | 35        | 1.27%   |
| Bhopal        | 32        | 1.16%   |
| Trivandrum    | 28        | 1.01%   |
| Thrissur      | 25        | 0.9%    |
| Surat         | 25        | 0.9%    |
| Malappuram    | 25        | 0.9%    |
| Ludhiana      | 25        | 0.9%    |
| Guwahati      | 23        | 0.83%   |
| Nagpur        | 21        | 0.76%   |
| Kochi         | 19        | 0.69%   |
| Bhubaneswar   | 18        | 0.65%   |
| Noida         | 17        | 0.62%   |
| Mangalore     | 15        | 0.54%   |
| Visakhapatnam | 14        | 0.51%   |
| Mohali        | 14        | 0.51%   |
| Ghaziabad     | 14        | 0.51%   |
| Thane         | 13        | 0.47%   |
| Kanpur        | 12        | 0.43%   |
| Vijayawada    | 11        | 0.4%    |
| Mysore        | 11        | 0.4%    |
| Kozhikode     | 11        | 0.4%    |
| Kannur        | 11        | 0.4%    |
| Vadodara      | 10        | 0.36%   |
| Puducherry    | 10        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 653       | 790    | 20.92%  |
| WDC                       | 563       | 662    | 18.03%  |
| Toshiba                   | 378       | 424    | 12.11%  |
| Samsung Electronics       | 308       | 372    | 9.87%   |
| HGST                      | 138       | 151    | 4.42%   |
| SK hynix                  | 133       | 149    | 4.26%   |
| SanDisk                   | 132       | 169    | 4.23%   |
| Intel                     | 127       | 166    | 4.07%   |
| Kingston                  | 117       | 138    | 3.75%   |
| Crucial                   | 108       | 128    | 3.46%   |
| Hitachi                   | 71        | 84     | 2.27%   |
| Micron Technology         | 65        | 77     | 2.08%   |
| Unknown                   | 58        | 74     | 1.86%   |
| KIOXIA                    | 46        | 53     | 1.47%   |
| A-DATA Technology         | 22        | 23     | 0.7%    |
| China                     | 15        | 15     | 0.48%   |
| Micron/Crucial Technology | 12        | 13     | 0.38%   |
| LITEON                    | 12        | 14     | 0.38%   |
| Silicon Motion            | 11        | 13     | 0.35%   |
| FORESEE                   | 11        | 12     | 0.35%   |
| UMIS                      | 10        | 12     | 0.32%   |
| Phison                    | 10        | 11     | 0.32%   |
| Apple                     | 10        | 11     | 0.32%   |
| Hewlett-Packard           | 9         | 13     | 0.29%   |
| Unknown                   | 9         | 9      | 0.29%   |
| Fujitsu                   | 7         | 7      | 0.22%   |
| Gigabyte Technology       | 5         | 6      | 0.16%   |
| TO Exter                  | 4         | 4      | 0.13%   |
| Maxtor                    | 4         | 6      | 0.13%   |
| Union Memory (Shenzhen)   | 3         | 3      | 0.1%    |
| SPCC                      | 3         | 4      | 0.1%    |
| PNY                       | 3         | 5      | 0.1%    |
| Lite-On                   | 3         | 3      | 0.1%    |
| Lenovo                    | 3         | 5      | 0.1%    |
| External                  | 3         | 5      | 0.1%    |
| XPG                       | 2         | 2      | 0.06%   |
| Union Memory              | 2         | 2      | 0.06%   |
| Transcend                 | 2         | 2      | 0.06%   |
| Team                      | 2         | 2      | 0.06%   |
| Realtek Semiconductor     | 2         | 2      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 244       | 7.62%   |
| Toshiba MQ04ABF100 1TB                 | 123       | 3.84%   |
| Toshiba MQ01ABD100 1TB                 | 99        | 3.09%   |
| Seagate ST1000LM049-2GH172 1TB         | 55        | 1.72%   |
| Seagate ST500LT012-1DG142 500GB        | 54        | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 51        | 1.59%   |
| Intel NVMe SSD Drive 512GB             | 48        | 1.5%    |
| Crucial CT240BX500SSD1 240GB           | 39        | 1.22%   |
| Toshiba MQ01ABF050 500GB               | 36        | 1.12%   |
| SanDisk NVMe SSD Drive 256GB           | 36        | 1.12%   |
| Samsung NVMe SSD Drive 512GB           | 33        | 1.03%   |
| Intel SSDPEKNW512G8 512GB              | 32        | 1%      |
| HGST HTS541010A9E680 1TB               | 32        | 1%      |
| SK hynix NVMe SSD Drive 512GB          | 29        | 0.91%   |
| SanDisk NVMe SSD Drive 512GB           | 29        | 0.91%   |
| WDC WD10SPZX-24Z10 1TB                 | 28        | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 27        | 0.84%   |
| WDC WD10JPVX-60JC3T1 1TB               | 27        | 0.84%   |
| Seagate ST9500325AS 500GB              | 27        | 0.84%   |
| Kingston SA400S37240G 240GB SSD        | 27        | 0.84%   |
| Seagate ST2000LM007-1R8174 2TB         | 26        | 0.81%   |
| Seagate ST1000LM048-2E7172 1TB         | 26        | 0.81%   |
| WDC WD10SPZX-60Z10T0 1TB               | 25        | 0.78%   |
| HGST HTS721010A9E630 1TB               | 25        | 0.78%   |
| WDC WD10SPZX-21Z10T0 1TB               | 24        | 0.75%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 23        | 0.72%   |
| HGST HTS545050A7E680 500GB             | 20        | 0.62%   |
| Seagate ST500LT012-9WS142 500GB        | 19        | 0.59%   |
| HGST HTS545050A7E380 500GB             | 19        | 0.59%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 18        | 0.56%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 18        | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB               | 17        | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB               | 15        | 0.47%   |
| Samsung SSD 860 EVO 250GB              | 15        | 0.47%   |
| Kingston NVMe SSD Drive 512GB          | 15        | 0.47%   |
| WDC WD10SPZX-24Z10T0 1TB               | 14        | 0.44%   |
| WDC WD10SPZX-08Z10 1TB                 | 14        | 0.44%   |
| Samsung NVMe SSD Drive 1024GB          | 14        | 0.44%   |
| WDC WD10JPVX-75JC3T0 1TB               | 13        | 0.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 13        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 647       | 782    | 40.09%  |
| WDC                 | 396       | 451    | 24.54%  |
| Toshiba             | 336       | 369    | 20.82%  |
| HGST                | 138       | 151    | 8.55%   |
| Hitachi             | 71        | 84     | 4.4%    |
| Unknown             | 7         | 7      | 0.43%   |
| Fujitsu             | 7         | 7      | 0.43%   |
| Samsung Electronics | 6         | 6      | 0.37%   |
| Apple               | 3         | 3      | 0.19%   |
| Hewlett-Packard     | 2         | 3      | 0.12%   |
| MARSHAL             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 120       | 136    | 19.42%  |
| Crucial             | 98        | 118    | 15.86%  |
| WDC                 | 84        | 96     | 13.59%  |
| Kingston            | 68        | 84     | 11%     |
| SanDisk             | 42        | 58     | 6.8%    |
| SK hynix            | 31        | 33     | 5.02%   |
| Micron Technology   | 20        | 24     | 3.24%   |
| A-DATA Technology   | 19        | 20     | 3.07%   |
| China               | 14        | 14     | 2.27%   |
| Intel               | 13        | 14     | 2.1%    |
| FORESEE             | 11        | 12     | 1.78%   |
| LITEON              | 10        | 12     | 1.62%   |
| Toshiba             | 9         | 9      | 1.46%   |
| Hewlett-Packard     | 6         | 9      | 0.97%   |
| Apple               | 6         | 7      | 0.97%   |
| Unknown             | 6         | 6      | 0.97%   |
| Seagate             | 5         | 5      | 0.81%   |
| Gigabyte Technology | 5         | 6      | 0.81%   |
| Unknown             | 4         | 4      | 0.65%   |
| TO Exter            | 4         | 4      | 0.65%   |
| Maxtor              | 4         | 6      | 0.65%   |
| PNY                 | 3         | 5      | 0.49%   |
| Transcend           | 2         | 2      | 0.32%   |
| Team                | 2         | 2      | 0.32%   |
| SPCC                | 2         | 3      | 0.32%   |
| Netac               | 2         | 2      | 0.32%   |
| Lexar               | 2         | 2      | 0.32%   |
| BIWIN               | 2         | 2      | 0.32%   |
| Aarvex              | 2         | 2      | 0.32%   |
| W800S               | 1         | 1      | 0.16%   |
| StoreJet            | 1         | 1      | 0.16%   |
| Secureye            | 1         | 1      | 0.16%   |
| Phison              | 1         | 1      | 0.16%   |
| OSCOO               | 1         | 3      | 0.16%   |
| OCZ                 | 1         | 1      | 0.16%   |
| NFORCE              | 1         | 1      | 0.16%   |
| LITEONIT            | 1         | 2      | 0.16%   |
| LITEON C            | 1         | 1      | 0.16%   |
| Leven               | 1         | 1      | 0.16%   |
| KLEVV               | 1         | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1593      | 1864   | 51.91%  |
| NVMe    | 817       | 1033   | 26.62%  |
| SSD     | 599       | 723    | 19.52%  |
| MMC     | 44        | 58     | 1.43%   |
| Unknown | 16        | 16     | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1967      | 2545   | 68.35%  |
| NVMe | 814       | 1028   | 28.28%  |
| SAS  | 53        | 63     | 1.84%   |
| MMC  | 44        | 58     | 1.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1080      | 1297   | 49.61%  |
| 0.51-1.0   | 1042      | 1229   | 47.86%  |
| 1.01-2.0   | 49        | 54     | 2.25%   |
| 3.01-4.0   | 4         | 5      | 0.18%   |
| 4.01-10.0  | 2         | 2      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 767       | 28.41%  |
| 101-250        | 703       | 26.04%  |
| 501-1000       | 490       | 18.15%  |
| 51-100         | 252       | 9.33%   |
| 1001-2000      | 143       | 5.3%    |
| 21-50          | 137       | 5.07%   |
| 1-20           | 128       | 4.74%   |
| Unknown        | 41        | 1.52%   |
| 2001-3000      | 20        | 0.74%   |
| More than 3000 | 19        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1064      | 38.11%  |
| 21-50          | 605       | 21.67%  |
| 101-250        | 385       | 13.79%  |
| 51-100         | 350       | 12.54%  |
| 251-500        | 212       | 7.59%   |
| 501-1000       | 110       | 3.94%   |
| Unknown        | 41        | 1.47%   |
| 1001-2000      | 19        | 0.68%   |
| 2001-3000      | 3         | 0.11%   |
| More than 3000 | 2         | 0.07%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 19        | 20     | 8.72%   |
| HGST HTS541010A9E680 1TB             | 11        | 11     | 5.05%   |
| Toshiba MQ01ABD100 1TB               | 10        | 10     | 4.59%   |
| Seagate ST1000LM049-2GH172 1TB       | 9         | 10     | 4.13%   |
| HGST HTS545050A7E680 500GB           | 9         | 11     | 4.13%   |
| Seagate ST500LT012-1DG142 500GB      | 8         | 8      | 3.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 7      | 3.21%   |
| Seagate ST9500325AS 500GB            | 5         | 5      | 2.29%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 5      | 2.29%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 2.29%   |
| Toshiba MQ04ABF100 1TB               | 4         | 5      | 1.83%   |
| Toshiba MQ01ABF050 500GB             | 4         | 4      | 1.83%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 1.83%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 1.83%   |
| HGST HTS545050A7E380 500GB           | 4         | 4      | 1.83%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 1.38%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 3      | 1.38%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 1.38%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 1.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.92%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.92%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.92%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 0.92%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 0.92%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 2         | 2      | 0.92%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 0.92%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 2      | 0.92%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 2      | 0.92%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 2      | 0.92%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 4      | 0.92%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 2      | 0.92%   |
| Hitachi HTS542516K9SA00 160GB        | 2         | 2      | 0.92%   |
| Crucial CT500P1SSD8 500GB            | 2         | 2      | 0.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1      | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1      | 0.46%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1      | 0.46%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 1      | 0.46%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 1      | 0.46%   |
| WDC WD5000BEVT-60ZAT1 500GB          | 1         | 1      | 0.46%   |
| WDC WD5000BEKT-75KA9T0 500GB         | 1         | 1      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 84     | 36.41%  |
| HGST                | 34        | 36     | 15.67%  |
| WDC                 | 31        | 32     | 14.29%  |
| Toshiba             | 27        | 29     | 12.44%  |
| Hitachi             | 21        | 24     | 9.68%   |
| SK hynix            | 6         | 7      | 2.76%   |
| Samsung Electronics | 5         | 6      | 2.3%    |
| SanDisk             | 4         | 4      | 1.84%   |
| Crucial             | 2         | 2      | 0.92%   |
| Micron Technology   | 1         | 1      | 0.46%   |
| MARSHAL             | 1         | 1      | 0.46%   |
| Leven               | 1         | 1      | 0.46%   |
| Lenovo              | 1         | 2      | 0.46%   |
| Intel               | 1         | 1      | 0.46%   |
| China               | 1         | 1      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |
| A-DATA Technology   | 1         | 1      | 0.46%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 84     | 41.15%  |
| HGST                | 34        | 36     | 17.71%  |
| WDC                 | 28        | 29     | 14.58%  |
| Toshiba             | 27        | 29     | 14.06%  |
| Hitachi             | 21        | 24     | 10.94%  |
| Samsung Electronics | 1         | 1      | 0.52%   |
| MARSHAL             | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 192       | 205    | 88.48%  |
| SSD  | 14        | 15     | 6.45%   |
| NVMe | 11        | 13     | 5.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 25%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 25%     |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 25%     |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Apple   | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1594      | 2227   | 58.86%  |
| Works    | 895       | 1230   | 33.05%  |
| Malfunc  | 215       | 233    | 7.94%   |
| Failed   | 4         | 4      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2004      | 64.35%  |
| AMD                              | 362       | 11.62%  |
| Samsung Electronics              | 195       | 6.26%   |
| SanDisk                          | 177       | 5.68%   |
| SK hynix                         | 101       | 3.24%   |
| Kingston Technology Company      | 51        | 1.64%   |
| KIOXIA                           | 49        | 1.57%   |
| Micron Technology                | 45        | 1.45%   |
| Toshiba America Info Systems     | 43        | 1.38%   |
| Micron/Crucial Technology        | 21        | 0.67%   |
| Union Memory (Shenzhen)          | 16        | 0.51%   |
| Silicon Motion                   | 14        | 0.45%   |
| Phison Electronics               | 8         | 0.26%   |
| Solid State Storage Technology   | 4         | 0.13%   |
| Realtek Semiconductor            | 4         | 0.13%   |
| Lite-On Technology               | 4         | 0.13%   |
| Yangtze Memory Technologies      | 3         | 0.1%    |
| Nvidia                           | 3         | 0.1%    |
| Lenovo                           | 3         | 0.1%    |
| ADATA Technology                 | 3         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 399       | 12.18%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 353       | 10.78%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 259       | 7.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 173       | 5.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 159       | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 111       | 3.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 105       | 3.21%   |
| Intel Volume Management Device NVMe RAID Controller                              | 92        | 2.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 92        | 2.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 88        | 2.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 84        | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 82        | 2.5%    |
| Intel SSD 660P Series                                                            | 79        | 2.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 79        | 2.41%   |
| Intel Tiger Lake-LP SATA Controller                                              | 64        | 1.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 54        | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 48        | 1.47%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 47        | 1.44%   |
| Micron Non-Volatile memory controller                                            | 45        | 1.37%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 43        | 1.31%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 40        | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 40        | 1.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 37        | 1.13%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 33        | 1.01%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 31        | 0.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 30        | 0.92%   |
| SK hynix Gold P31 SSD                                                            | 29        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 29        | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 28        | 0.85%   |
| SanDisk Non-Volatile memory controller                                           | 27        | 0.82%   |
| SK hynix BC511                                                                   | 24        | 0.73%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 21        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 21        | 0.64%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 16        | 0.49%   |
| Intel Non-Volatile memory controller                                             | 16        | 0.49%   |
| Kingston Company Company Non-Volatile memory controller                          | 15        | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 0.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 0.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 0.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1979      | 61.5%   |
| NVMe | 822       | 25.54%  |
| RAID | 356       | 11.06%  |
| IDE  | 61        | 1.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2136      | 82.66%  |
| AMD    | 447       | 17.3%   |
| ARM    | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 162       | 6.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 100       | 3.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 72        | 2.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 71        | 2.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 70        | 2.71%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 68        | 2.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 45        | 1.74%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 45        | 1.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 43        | 1.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 42        | 1.63%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 42        | 1.63%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 41        | 1.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 41        | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.43%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 35        | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 33        | 1.28%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 32        | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 1.16%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 30        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 29        | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 25        | 0.97%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 25        | 0.97%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 24        | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.89%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 23        | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 21        | 0.81%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 20        | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 0.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 20        | 0.77%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 19        | 0.74%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 19        | 0.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 19        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 18        | 0.7%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 18        | 0.7%    |
| AMD PRO A4-4350B R4, 5 COMPUTE CORES 2C+3G    | 18        | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 17        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 917       | 35.49%  |
| Intel Core i3           | 474       | 18.34%  |
| Intel Core i7           | 382       | 14.78%  |
| Other                   | 187       | 7.24%   |
| AMD Ryzen 5             | 179       | 6.93%   |
| Intel Pentium           | 74        | 2.86%   |
| AMD Ryzen 7             | 63        | 2.44%   |
| Intel Core 2 Duo        | 48        | 1.86%   |
| Intel Celeron           | 38        | 1.47%   |
| AMD A6                  | 36        | 1.39%   |
| AMD Ryzen 3             | 29        | 1.12%   |
| AMD A8                  | 24        | 0.93%   |
| AMD A4                  | 20        | 0.77%   |
| Intel Atom              | 16        | 0.62%   |
| AMD A10                 | 16        | 0.62%   |
| Intel Pentium Dual-Core | 13        | 0.5%    |
| AMD Ryzen 9             | 12        | 0.46%   |
| AMD E1                  | 10        | 0.39%   |
| AMD E2                  | 6         | 0.23%   |
| Intel Core 2            | 5         | 0.19%   |
| AMD Ryzen 7 PRO         | 5         | 0.19%   |
| Intel Pentium Dual      | 4         | 0.15%   |
| AMD Ryzen 5 PRO         | 4         | 0.15%   |
| AMD E                   | 4         | 0.15%   |
| Intel Core i9           | 3         | 0.12%   |
| AMD A12                 | 3         | 0.12%   |
| Intel Pentium Silver    | 2         | 0.08%   |
| AMD PRO A10             | 2         | 0.08%   |
| AMD C-60                | 2         | 0.08%   |
| Intel Xeon              | 1         | 0.04%   |
| Intel Pentium M         | 1         | 0.04%   |
| Intel Genuine           | 1         | 0.04%   |
| Intel Core m3           | 1         | 0.04%   |
| Intel Celeron M         | 1         | 0.04%   |
| Intel Celeron Dual-Core | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1331      | 51.49%  |
| 4      | 967       | 37.41%  |
| 6      | 170       | 6.58%   |
| 8      | 86        | 3.33%   |
| 1      | 20        | 0.77%   |
| 14     | 4         | 0.15%   |
| 12     | 3         | 0.12%   |
| 10     | 2         | 0.08%   |
| 3      | 2         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2584      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2229      | 86.26%  |
| 1      | 355       | 13.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2555      | 98.8%   |
| Unknown        | 27        | 1.04%   |
| 32-bit         | 4         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 464       | 17.56%  |
| 0x806ea    | 202       | 7.64%   |
| 0x806ec    | 189       | 7.15%   |
| 0x40651    | 138       | 5.22%   |
| 0x206a7    | 137       | 5.18%   |
| 0x306a9    | 134       | 5.07%   |
| 0x806e9    | 131       | 4.96%   |
| 0x406e3    | 127       | 4.81%   |
| 0x806c1    | 115       | 4.35%   |
| 0x906ea    | 101       | 3.82%   |
| 0x306d4    | 99        | 3.75%   |
| 0x706e5    | 62        | 2.35%   |
| 0x20655    | 49        | 1.85%   |
| 0x806eb    | 47        | 1.78%   |
| 0x08108109 | 46        | 1.74%   |
| 0x08108102 | 44        | 1.66%   |
| 0x0a50000c | 37        | 1.4%    |
| 0x1067a    | 36        | 1.36%   |
| 0x06006705 | 35        | 1.32%   |
| 0xa0652    | 32        | 1.21%   |
| 0x306c3    | 28        | 1.06%   |
| 0x07030105 | 28        | 1.06%   |
| 0x906e9    | 27        | 1.02%   |
| 0x20652    | 23        | 0.87%   |
| 0x08600104 | 22        | 0.83%   |
| 0x08600106 | 19        | 0.72%   |
| 0x08101007 | 15        | 0.57%   |
| 0x6fd      | 14        | 0.53%   |
| 0x30678    | 14        | 0.53%   |
| 0x08608103 | 14        | 0.53%   |
| 0x0810100b | 14        | 0.53%   |
| 0x906ed    | 12        | 0.45%   |
| 0x506e3    | 12        | 0.45%   |
| 0x08600103 | 12        | 0.45%   |
| 0x806d1    | 10        | 0.38%   |
| 0x06006704 | 10        | 0.38%   |
| 0x06001119 | 10        | 0.38%   |
| 0x406c4    | 9         | 0.34%   |
| 0x106ca    | 9         | 0.34%   |
| 0x0600611a | 9         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 821       | 31.77%  |
| Haswell          | 201       | 7.78%   |
| Skylake          | 170       | 6.58%   |
| SandyBridge      | 164       | 6.35%   |
| IvyBridge        | 161       | 6.23%   |
| TigerLake        | 134       | 5.19%   |
| Broadwell        | 118       | 4.57%   |
| Zen+             | 111       | 4.3%    |
| Westmere         | 86        | 3.33%   |
| IceLake          | 82        | 3.17%   |
| Zen 2            | 76        | 2.94%   |
| Excavator        | 69        | 2.67%   |
| Penryn           | 51        | 1.97%   |
| Zen 3            | 47        | 1.82%   |
| Puma             | 47        | 1.82%   |
| CometLake        | 42        | 1.63%   |
| Silvermont       | 38        | 1.47%   |
| Zen              | 32        | 1.24%   |
| Unknown          | 30        | 1.16%   |
| Core             | 22        | 0.85%   |
| Piledriver       | 15        | 0.58%   |
| K10 Llano        | 11        | 0.43%   |
| Bonnell          | 10        | 0.39%   |
| Goldmont plus    | 9         | 0.35%   |
| Goldmont         | 8         | 0.31%   |
| Bobcat           | 7         | 0.27%   |
| Alderlake Hybrid | 7         | 0.27%   |
| Nehalem          | 6         | 0.23%   |
| Jaguar           | 4         | 0.15%   |
| P6               | 3         | 0.12%   |
| Steamroller      | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2060      | 58.47%  |
| Nvidia                           | 737       | 20.92%  |
| AMD                              | 725       | 20.58%  |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 218       | 6.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 165       | 4.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 154       | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 149       | 4.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 146       | 4.05%   |
| Intel HD Graphics 620                                                                 | 137       | 3.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 132       | 3.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 130       | 3.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 124       | 3.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 112       | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 111       | 3.08%   |
| Intel HD Graphics 5500                                                                | 108       | 2.99%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 100       | 2.77%   |
| AMD Renoir                                                                            | 74        | 2.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 65        | 1.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 62        | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                   | 62        | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 61        | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 54        | 1.5%    |
| Nvidia TU117M                                                                         | 51        | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 46        | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 44        | 1.22%   |
| AMD Cezanne                                                                           | 43        | 1.19%   |
| Nvidia GP108M [GeForce MX250]                                                         | 42        | 1.16%   |
| Nvidia GP108M [GeForce MX150]                                                         | 40        | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 38        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 34        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 33        | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 33        | 0.91%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 33        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 32        | 0.89%   |
| Intel HD Graphics 630                                                                 | 30        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 27        | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                                         | 26        | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 25        | 0.69%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 25        | 0.69%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 25        | 0.69%   |
| AMD Lucienne                                                                          | 24        | 0.67%   |
| Intel Tiger Lake UHD Graphics                                                         | 22        | 0.61%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                     | 22        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1228      | 47.34%  |
| Intel + Nvidia | 586       | 22.59%  |
| 1 x AMD        | 311       | 11.99%  |
| Intel + AMD    | 251       | 9.68%   |
| AMD + Nvidia   | 101       | 3.89%   |
| 2 x AMD        | 64        | 2.47%   |
| 1 x Nvidia     | 49        | 1.89%   |
| Other          | 3         | 0.12%   |
| 1 x SiS        | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2172      | 82.96%  |
| Proprietary | 386       | 14.74%  |
| Unknown     | 60        | 2.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1593      | 60%     |
| 1.01-2.0   | 447       | 16.84%  |
| 0.01-0.5   | 227       | 8.55%   |
| 3.01-4.0   | 218       | 8.21%   |
| 0.51-1.0   | 129       | 4.86%   |
| 5.01-6.0   | 31        | 1.17%   |
| 7.01-8.0   | 6         | 0.23%   |
| 2.01-3.0   | 3         | 0.11%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 561       | 20.4%   |
| AU Optronics            | 557       | 20.25%  |
| Chimei Innolux          | 517       | 18.8%   |
| LG Display              | 441       | 16.04%  |
| Samsung Electronics     | 203       | 7.38%   |
| PANDA                   | 87        | 3.16%   |
| Dell                    | 46        | 1.67%   |
| BenQ                    | 41        | 1.49%   |
| Sharp                   | 39        | 1.42%   |
| Goldstar                | 38        | 1.38%   |
| Chi Mei Optoelectronics | 37        | 1.35%   |
| Lenovo                  | 24        | 0.87%   |
| InfoVision              | 22        | 0.8%    |
| Acer                    | 22        | 0.8%    |
| Sony                    | 16        | 0.58%   |
| Apple                   | 16        | 0.58%   |
| Hewlett-Packard         | 11        | 0.4%    |
| AOC                     | 8         | 0.29%   |
| TMX                     | 7         | 0.25%   |
| InnoLux Display         | 6         | 0.22%   |
| LG Philips              | 5         | 0.18%   |
| Toshiba                 | 4         | 0.15%   |
| Unknown                 | 3         | 0.11%   |
| LGD                     | 3         | 0.11%   |
| HKC                     | 3         | 0.11%   |
| CSO                     | 3         | 0.11%   |
| CPT                     | 3         | 0.11%   |
| ViewSonic               | 2         | 0.07%   |
| STA                     | 2         | 0.07%   |
| KDC                     | 2         | 0.07%   |
| HannStar                | 2         | 0.07%   |
| Unknown (XXX)           | 1         | 0.04%   |
| TCL                     | 1         | 0.04%   |
| Seiko/Epson             | 1         | 0.04%   |
| S2-Tek                  | 1         | 0.04%   |
| Philips                 | 1         | 0.04%   |
| Panasonic               | 1         | 0.04%   |
| LPL                     | 1         | 0.04%   |
| Lenovo Group Limited    | 1         | 0.04%   |
| JRY                     | 1         | 0.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 73        | 2.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 64        | 2.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 37        | 1.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 34        | 1.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 33        | 1.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 32        | 1.16%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 30        | 1.09%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 27        | 0.98%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.98%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 26        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 25        | 0.91%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 25        | 0.91%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 22        | 0.8%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 22        | 0.8%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 19        | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 19        | 0.69%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 19        | 0.69%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 19        | 0.69%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 17        | 0.62%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 16        | 0.58%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 16        | 0.58%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 16        | 0.58%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 15        | 0.54%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 15        | 0.54%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 14        | 0.51%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 14        | 0.51%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 13        | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 13        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 13        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 13        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 13        | 0.47%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 13        | 0.47%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 13        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch      | 12        | 0.44%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                | 12        | 0.44%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 12        | 0.44%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                | 12        | 0.44%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 12        | 0.44%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 12        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1307      | 49.26%  |
| 1366x768 (WXGA)    | 1113      | 41.95%  |
| 1600x900 (HD+)     | 44        | 1.66%   |
| 3840x2160 (4K)     | 33        | 1.24%   |
| 1280x800 (WXGA)    | 33        | 1.24%   |
| 2560x1440 (QHD)    | 28        | 1.06%   |
| 1920x1200 (WUXGA)  | 20        | 0.75%   |
| 1440x900 (WXGA+)   | 15        | 0.57%   |
| 2560x1600          | 11        | 0.41%   |
| 1024x600           | 7         | 0.26%   |
| 2560x1080          | 6         | 0.23%   |
| 1360x768           | 6         | 0.23%   |
| 1280x1024 (SXGA)   | 5         | 0.19%   |
| 3200x2000          | 4         | 0.15%   |
| 2880x1800          | 3         | 0.11%   |
| 2160x1440          | 3         | 0.11%   |
| 1680x1050 (WSXGA+) | 3         | 0.11%   |
| 3456x2160          | 2         | 0.08%   |
| 2256x1504          | 2         | 0.08%   |
| 3840x2400          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 2732x768           | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1280x720 (HD)      | 1         | 0.04%   |
| Unknown            | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1572      | 57.27%  |
| 13      | 431       | 15.7%   |
| 14      | 409       | 14.9%   |
| 21      | 58        | 2.11%   |
| 24      | 50        | 1.82%   |
| 12      | 36        | 1.31%   |
| 27      | 30        | 1.09%   |
| 17      | 25        | 0.91%   |
| 23      | 22        | 0.8%    |
| 18      | 18        | 0.66%   |
| 11      | 12        | 0.44%   |
| Unknown | 12        | 0.44%   |
| 19      | 10        | 0.36%   |
| 31      | 9         | 0.33%   |
| 20      | 8         | 0.29%   |
| 16      | 8         | 0.29%   |
| 10      | 8         | 0.29%   |
| 34      | 6         | 0.22%   |
| 72      | 4         | 0.15%   |
| 40      | 4         | 0.15%   |
| 46      | 3         | 0.11%   |
| 26      | 3         | 0.11%   |
| 54      | 2         | 0.07%   |
| 65      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |
| 25      | 1         | 0.04%   |
| 22      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2300      | 83.91%  |
| 201-300     | 142       | 5.18%   |
| 401-500     | 97        | 3.54%   |
| 501-600     | 96        | 3.5%    |
| 351-400     | 59        | 2.15%   |
| 601-700     | 13        | 0.47%   |
| Unknown     | 12        | 0.44%   |
| 701-800     | 7         | 0.26%   |
| 1001-1500   | 6         | 0.22%   |
| 801-900     | 4         | 0.15%   |
| 1501-2000   | 4         | 0.15%   |
| 901-1000    | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2429      | 95.07%  |
| 16/10   | 90        | 3.52%   |
| Unknown | 11        | 0.43%   |
| 3/2     | 7         | 0.27%   |
| 4/3     | 6         | 0.23%   |
| 21/9    | 6         | 0.23%   |
| 5/4     | 3         | 0.12%   |
| 6/5     | 2         | 0.08%   |
| 3.40    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1563      | 56.96%  |
| 81-90          | 769       | 28.02%  |
| 201-250        | 118       | 4.3%    |
| 71-80          | 69        | 2.51%   |
| 61-70          | 34        | 1.24%   |
| 301-350        | 32        | 1.17%   |
| 151-200        | 24        | 0.87%   |
| 121-130        | 24        | 0.87%   |
| 141-150        | 17        | 0.62%   |
| 351-500        | 16        | 0.58%   |
| 51-60          | 13        | 0.47%   |
| 91-100         | 13        | 0.47%   |
| Unknown        | 12        | 0.44%   |
| 41-50          | 8         | 0.29%   |
| 501-1000       | 8         | 0.29%   |
| More than 1000 | 7         | 0.26%   |
| 251-300        | 7         | 0.26%   |
| 111-120        | 7         | 0.26%   |
| 131-140        | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1253      | 46.17%  |
| 101-120       | 1081      | 39.83%  |
| 51-100        | 248       | 9.14%   |
| 161-240       | 86        | 3.17%   |
| More than 240 | 24        | 0.88%   |
| Unknown       | 12        | 0.44%   |
| 1-50          | 10        | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2342      | 89.49%  |
| 2     | 223       | 8.52%   |
| 0     | 47        | 1.8%    |
| 3     | 5         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1736      | 40.65%  |
| Intel                             | 1145      | 26.81%  |
| Qualcomm Atheros                  | 688       | 16.11%  |
| Broadcom                          | 227       | 5.31%   |
| Xiaomi                            | 63        | 1.48%   |
| Ralink                            | 53        | 1.24%   |
| MediaTek                          | 41        | 0.96%   |
| TP-Link                           | 39        | 0.91%   |
| Broadcom Limited                  | 39        | 0.91%   |
| Samsung Electronics               | 31        | 0.73%   |
| Ralink Technology                 | 28        | 0.66%   |
| Marvell Technology Group          | 28        | 0.66%   |
| OPPO Electronics                  | 26        | 0.61%   |
| Qualcomm                          | 19        | 0.44%   |
| Huawei Technologies               | 12        | 0.28%   |
| Motorola PCS                      | 11        | 0.26%   |
| OnePlus                           | 8         | 0.19%   |
| Google                            | 6         | 0.14%   |
| ASIX Electronics                  | 6         | 0.14%   |
| ICS Advent                        | 5         | 0.12%   |
| Foxconn / Hon Hai                 | 5         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.09%   |
| JMicron Technology                | 4         | 0.09%   |
| HMD Global                        | 4         | 0.09%   |
| DisplayLink                       | 4         | 0.09%   |
| D-Link                            | 4         | 0.09%   |
| Lenovo                            | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.05%   |
| vivo                              | 2         | 0.05%   |
| Sierra Wireless                   | 2         | 0.05%   |
| NTmore                            | 2         | 0.05%   |
| Ericsson Business Mobile Networks | 2         | 0.05%   |
| Edimax Technology                 | 2         | 0.05%   |
| Dell                              | 2         | 0.05%   |
| Attansic Technology               | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| Apple                             | 2         | 0.05%   |
| VIA Technologies                  | 1         | 0.02%   |
| U-Blox                            | 1         | 0.02%   |
| STMicroelectronics                | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1115      | 22.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 477       | 9.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 260       | 5.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 120       | 2.41%   |
| Intel Wi-Fi 6 AX200                                               | 113       | 2.26%   |
| Intel Wireless 8265 / 8275                                        | 105       | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 100       | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 99        | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 97        | 1.94%   |
| Intel Wi-Fi 6 AX201                                               | 97        | 1.94%   |
| Broadcom BCM43142 802.11b/g/n                                     | 92        | 1.84%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 91        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 80        | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 77        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 75        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 71        | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 70        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 67        | 1.34%   |
| Intel Wireless 7265                                               | 66        | 1.32%   |
| Intel Wireless 3165                                               | 59        | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 57        | 1.14%   |
| Intel Wireless 3160                                               | 55        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 44        | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 41        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 39        | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 36        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 31        | 0.62%   |
| Intel Wireless 8260                                               | 31        | 0.62%   |
| Intel Wireless 7260                                               | 31        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 30        | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 27        | 0.54%   |
| OPPO RMX2180                                                      | 26        | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 25        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 23        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 22        | 0.44%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1107      | 41.77%  |
| Qualcomm Atheros                | 623       | 23.51%  |
| Realtek Semiconductor           | 519       | 19.58%  |
| Broadcom                        | 203       | 7.66%   |
| Ralink                          | 53        | 2%      |
| TP-Link                         | 35        | 1.32%   |
| MediaTek                        | 35        | 1.32%   |
| Broadcom Limited                | 31        | 1.17%   |
| Ralink Technology               | 28        | 1.06%   |
| D-Link                          | 4         | 0.15%   |
| Sierra Wireless                 | 2         | 0.08%   |
| Edimax Technology               | 2         | 0.08%   |
| Dell                            | 2         | 0.08%   |
| Qualcomm Atheros Communications | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| NetGear                         | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 260       | 9.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 120       | 4.51%   |
| Intel Wi-Fi 6 AX200                                            | 113       | 4.24%   |
| Intel Wireless 8265 / 8275                                     | 105       | 3.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 100       | 3.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 99        | 3.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 97        | 3.64%   |
| Intel Wi-Fi 6 AX201                                            | 97        | 3.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 92        | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 91        | 3.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 80        | 3%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 77        | 2.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 75        | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 71        | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 70        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 67        | 2.52%   |
| Intel Wireless 7265                                            | 66        | 2.48%   |
| Intel Wireless 3165                                            | 59        | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 57        | 2.14%   |
| Intel Wireless 3160                                            | 55        | 2.07%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 44        | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 39        | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 36        | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 31        | 1.16%   |
| Intel Wireless 8260                                            | 31        | 1.16%   |
| Intel Wireless 7260                                            | 31        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 30        | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 27        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 25        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 23        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 21        | 0.79%   |
| Intel Wireless-AC 9260                                         | 21        | 0.79%   |
| Ralink MT7601U Wireless Adapter                                | 20        | 0.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 17        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 16        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 15        | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 14        | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 13        | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1625      | 70.74%  |
| Intel                            | 268       | 11.67%  |
| Qualcomm Atheros                 | 105       | 4.57%   |
| Xiaomi                           | 63        | 2.74%   |
| Broadcom                         | 41        | 1.78%   |
| Samsung Electronics              | 31        | 1.35%   |
| Marvell Technology Group         | 28        | 1.22%   |
| OPPO Electronics                 | 26        | 1.13%   |
| Qualcomm                         | 18        | 0.78%   |
| Huawei Technologies              | 10        | 0.44%   |
| OnePlus                          | 8         | 0.35%   |
| Broadcom Limited                 | 8         | 0.35%   |
| Motorola PCS                     | 7         | 0.3%    |
| MediaTek                         | 7         | 0.3%    |
| Google                           | 6         | 0.26%   |
| ASIX Electronics                 | 6         | 0.26%   |
| ICS Advent                       | 5         | 0.22%   |
| TP-Link                          | 4         | 0.17%   |
| JMicron Technology               | 4         | 0.17%   |
| HMD Global                       | 4         | 0.17%   |
| DisplayLink                      | 4         | 0.17%   |
| Lenovo                           | 3         | 0.13%   |
| Foxconn / Hon Hai                | 3         | 0.13%   |
| NTmore                           | 2         | 0.09%   |
| Attansic Technology              | 2         | 0.09%   |
| ASUSTek Computer                 | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| vivo                             | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Nvidia                           | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |
| Android                          | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1115      | 48.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 477       | 20.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 48        | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 41        | 1.78%   |
| Intel Ethernet Connection (4) I219-V                                           | 32        | 1.39%   |
| OPPO RMX2180                                                                   | 26        | 1.13%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 23        | 1%      |
| Intel Ethernet Connection I218-LM                                              | 23        | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 22        | 0.95%   |
| Intel Ethernet Connection I219-LM                                              | 22        | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 21        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 18        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                          | 18        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                          | 17        | 0.74%   |
| Qualcomm Mobile Router                                                         | 16        | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 14        | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                          | 14        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                       | 14        | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 12        | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 12        | 0.52%   |
| Intel Ethernet Connection I217-LM                                              | 12        | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 11        | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 10        | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 9         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 9         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 9         | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 8         | 0.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 8         | 0.35%   |
| OnePlus OnePlus                                                                | 8         | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 0.35%   |
| Motorola PCS moto g(6) plus                                                    | 7         | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 0.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.26%   |
| MediaTek TECNO Pouvoir 3 Air                                                   | 6         | 0.26%   |
| Huawei LYA-L09                                                                 | 6         | 0.26%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 0.22%   |
| Google Nexus/Pixel Device (tether)                                             | 5         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2555      | 54.44%  |
| Ethernet | 2117      | 45.11%  |
| Unknown  | 14        | 0.3%    |
| Modem    | 7         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2202      | 85.25%  |
| Ethernet | 380       | 14.71%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2020      | 78.05%  |
| 1     | 551       | 21.29%  |
| 0     | 11        | 0.43%   |
| 3     | 6         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2199      | 84.03%  |
| Yes  | 418       | 15.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 943       | 41.25%  |
| Qualcomm Atheros Communications | 388       | 16.97%  |
| Realtek Semiconductor           | 368       | 16.1%   |
| Broadcom                        | 131       | 5.73%   |
| IMC Networks                    | 112       | 4.9%    |
| Lite-On Technology              | 103       | 4.51%   |
| Foxconn / Hon Hai               | 73        | 3.19%   |
| Ralink                          | 44        | 1.92%   |
| Dell                            | 29        | 1.27%   |
| Cambridge Silicon Radio         | 20        | 0.87%   |
| Apple                           | 16        | 0.7%    |
| Hewlett-Packard                 | 14        | 0.61%   |
| Foxconn International           | 10        | 0.44%   |
| Toshiba                         | 7         | 0.31%   |
| Ralink Technology               | 7         | 0.31%   |
| Realtek                         | 5         | 0.22%   |
| ASUSTek Computer                | 4         | 0.17%   |
| TP-Link                         | 3         | 0.13%   |
| MediaTek                        | 2         | 0.09%   |
| Chicony Electronics             | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Alps Electric                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 340       | 14.87%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 237       | 10.37%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 225       | 9.84%   |
| Realtek Bluetooth Radio                                                             | 214       | 9.36%   |
| Intel AX201 Bluetooth                                                               | 176       | 7.7%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 112       | 4.9%    |
| Intel AX200 Bluetooth                                                               | 110       | 4.81%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 52        | 2.27%   |
| IMC Networks Bluetooth Radio                                                        | 46        | 2.01%   |
| Ralink RT3290 Bluetooth                                                             | 44        | 1.92%   |
| IMC Networks Bluetooth Device                                                       | 42        | 1.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 41        | 1.79%   |
| Lite-On Bluetooth Device                                                            | 37        | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 36        | 1.57%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 34        | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 31        | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 25        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 24        | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 23        | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 22        | 0.96%   |
| IMC Networks Wireless_Device                                                        | 21        | 0.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 20        | 0.87%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 0.66%   |
| Realtek RTL8821A Bluetooth                                                          | 14        | 0.61%   |
| Realtek RTL8723B Bluetooth                                                          | 14        | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 14        | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 13        | 0.57%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 13        | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 12        | 0.52%   |
| Dell Wireless 365 Bluetooth                                                         | 12        | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 12        | 0.52%   |
| Qualcomm Atheros Bluetooth                                                          | 11        | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 11        | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 10        | 0.44%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 10        | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 8         | 0.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2124      | 71.56%  |
| AMD                              | 481       | 16.21%  |
| Nvidia                           | 304       | 10.24%  |
| GN Netcom                        | 8         | 0.27%   |
| C-Media Electronics              | 8         | 0.27%   |
| Sennheiser Communications        | 4         | 0.13%   |
| Realtek Semiconductor            | 4         | 0.13%   |
| Plantronics                      | 3         | 0.1%    |
| Logitech                         | 3         | 0.1%    |
| Generalplus Technology           | 3         | 0.1%    |
| SteelSeries ApS                  | 2         | 0.07%   |
| Lenovo                           | 2         | 0.07%   |
| JMTek                            | 2         | 0.07%   |
| DCMT Technology                  | 2         | 0.07%   |
| Yamaha                           | 1         | 0.03%   |
| XMOS                             | 1         | 0.03%   |
| Vault                            | 1         | 0.03%   |
| Texas Instruments                | 1         | 0.03%   |
| Tenx Technology                  | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Shenzhen Rapoo Technology        | 1         | 0.03%   |
| Razer USA                        | 1         | 0.03%   |
| Panasonic (Matsushita)           | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Kingston Technology              | 1         | 0.03%   |
| Focusrite-Novation               | 1         | 0.03%   |
| FiiO Electronics Technology      | 1         | 0.03%   |
| Creative Technology              | 1         | 0.03%   |
| Corsair                          | 1         | 0.03%   |
| CMX Systems                      | 1         | 0.03%   |
| Arturia                          | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 534       | 14.57%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 292       | 7.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 197       | 5.37%   |
| Intel 8 Series HD Audio Controller                                                                | 165       | 4.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 163       | 4.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 146       | 3.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 136       | 3.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 134       | 3.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 128       | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 127       | 3.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 120       | 3.27%   |
| Intel Broadwell-U Audio Controller                                                                | 118       | 3.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 117       | 3.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 105       | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 103       | 2.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 92        | 2.51%   |
| AMD FCH Azalia Controller                                                                         | 80        | 2.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 72        | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 69        | 1.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 64        | 1.75%   |
| AMD High Definition Audio Controller                                                              | 54        | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 48        | 1.31%   |
| Intel Comet Lake PCH cAVS                                                                         | 39        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 38        | 1.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 36        | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33        | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 31        | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 0.52%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 18        | 0.49%   |
| Nvidia Audio device                                                                               | 18        | 0.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 17        | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 0.46%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 16        | 0.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 15        | 0.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 0.41%   |
| AMD Trinity HDMI Audio Controller                                                                 | 15        | 0.41%   |
| Nvidia High Definition Audio Controller                                                           | 12        | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 517       | 29.26%  |
| SK hynix            | 489       | 27.67%  |
| Micron Technology   | 227       | 12.85%  |
| Kingston            | 141       | 7.98%   |
| Crucial             | 98        | 5.55%   |
| Ramaxel Technology  | 78        | 4.41%   |
| A-DATA Technology   | 63        | 3.57%   |
| Unknown             | 50        | 2.83%   |
| Transcend           | 25        | 1.41%   |
| CSX                 | 18        | 1.02%   |
| Elpida              | 16        | 0.91%   |
| Nanya Technology    | 15        | 0.85%   |
| Corsair             | 8         | 0.45%   |
| G.Skill             | 3         | 0.17%   |
| Unknown (ABCD)      | 2         | 0.11%   |
| Avant               | 2         | 0.11%   |
| ASint Technology    | 2         | 0.11%   |
| ZION                | 1         | 0.06%   |
| Unknown (0x1007)    | 1         | 0.06%   |
| Unknown (09D5)      | 1         | 0.06%   |
| Unknown (07F7)      | 1         | 0.06%   |
| Team                | 1         | 0.06%   |
| Strontium           | 1         | 0.06%   |
| Silicon Power       | 1         | 0.06%   |
| SHARETRONIC         | 1         | 0.06%   |
| Qumo                | 1         | 0.06%   |
| Qimonda             | 1         | 0.06%   |
| Kllisre             | 1         | 0.06%   |
| Gold Key            | 1         | 0.06%   |
| Apacer              | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 58        | 3.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 53        | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 44        | 2.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 36        | 1.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 35        | 1.89%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 29        | 1.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 25        | 1.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 25        | 1.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 24        | 1.3%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 24        | 1.3%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 23        | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 23        | 1.24%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 22        | 1.19%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 22        | 1.19%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 22        | 1.19%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 22        | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 21        | 1.14%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 18        | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 17        | 0.92%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 17        | 0.92%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 16        | 0.86%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 16        | 0.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 15        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 14        | 0.76%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 14        | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 12        | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 12        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 12        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 12        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 12        | 0.65%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 12        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 12        | 0.65%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 11        | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 11        | 0.59%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 11        | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 11        | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 10        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 10        | 0.54%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 10        | 0.54%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s         | 10        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 903       | 63.64%  |
| DDR3    | 393       | 27.7%   |
| LPDDR4  | 56        | 3.95%   |
| SDRAM   | 23        | 1.62%   |
| LPDDR3  | 21        | 1.48%   |
| DDR2    | 18        | 1.27%   |
| DDR5    | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |
| DDR     | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1320      | 94.15%  |
| Row Of Chips | 78        | 5.56%   |
| Unknown      | 2         | 0.14%   |
| DIMM         | 1         | 0.07%   |
| Chip         | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 711       | 45.64%  |
| 4096  | 569       | 36.52%  |
| 16384 | 129       | 8.28%   |
| 2048  | 126       | 8.09%   |
| 1024  | 16        | 1.03%   |
| 32768 | 6         | 0.39%   |
| 512   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 502       | 32.2%   |
| 1600    | 305       | 19.56%  |
| 3200    | 277       | 17.77%  |
| 2400    | 162       | 10.39%  |
| 2133    | 60        | 3.85%   |
| 3266    | 58        | 3.72%   |
| 1334    | 51        | 3.27%   |
| 1333    | 36        | 2.31%   |
| 4199    | 18        | 1.15%   |
| 4267    | 14        | 0.9%    |
| 1067    | 13        | 0.83%   |
| 667     | 13        | 0.83%   |
| Unknown | 13        | 0.83%   |
| 1867    | 10        | 0.64%   |
| 800     | 7         | 0.45%   |
| 975     | 6         | 0.38%   |
| 8400    | 3         | 0.19%   |
| 2048    | 3         | 0.19%   |
| 4800    | 2         | 0.13%   |
| 4266    | 1         | 0.06%   |
| 3733    | 1         | 0.06%   |
| 2933    | 1         | 0.06%   |
| 2800    | 1         | 0.06%   |
| 1639    | 1         | 0.06%   |
| 533     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 7         | 41.18%  |
| Canon              | 5         | 29.41%  |
| Seiko Epson        | 2         | 11.76%  |
| STMicroelectronics | 1         | 5.88%   |
| Ricoh              | 1         | 5.88%   |
| Brother Industries | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP LaserJet 1020                   | 2         | 11.76%  |
| HP DeskJet 1110 series             | 2         | 11.76%  |
| Canon LBP2900                      | 2         | 11.76%  |
| STMicroelectronics USB Printer P   | 1         | 5.88%   |
| Seiko Epson L222 Series            | 1         | 5.88%   |
| Seiko Epson L132 Series            | 1         | 5.88%   |
| Ricoh SP 112SU                     | 1         | 5.88%   |
| HP Ink Tank 310 series             | 1         | 5.88%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 5.88%   |
| HP DeskJet 2130 series             | 1         | 5.88%   |
| Canon PIXMA MP190                  | 1         | 5.88%   |
| Canon MF4800 Series                | 1         | 5.88%   |
| Canon G2000 series                 | 1         | 5.88%   |
| Brother HL-L2320D series           | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 487       | 20.07%  |
| IMC Networks                           | 361       | 14.87%  |
| Realtek Semiconductor                  | 272       | 11.21%  |
| Microdia                               | 247       | 10.18%  |
| Acer                                   | 156       | 6.43%   |
| Quanta                                 | 149       | 6.14%   |
| Sunplus Innovation Technology          | 148       | 6.1%    |
| Cheng Uei Precision Industry (Foxlink) | 123       | 5.07%   |
| Suyin                                  | 109       | 4.49%   |
| Syntek                                 | 87        | 3.58%   |
| Luxvisions Innotech Limited            | 54        | 2.22%   |
| Lite-On Technology                     | 48        | 1.98%   |
| Alcor Micro                            | 23        | 0.95%   |
| Silicon Motion                         | 19        | 0.78%   |
| Apple                                  | 17        | 0.7%    |
| Samsung Electronics                    | 16        | 0.66%   |
| Sonix Technology                       | 15        | 0.62%   |
| Ricoh                                  | 14        | 0.58%   |
| Logitech                               | 12        | 0.49%   |
| Importek                               | 11        | 0.45%   |
| Primax Electronics                     | 9         | 0.37%   |
| OmniVision Technologies                | 8         | 0.33%   |
| Z-Star Microelectronics                | 6         | 0.25%   |
| Lenovo                                 | 5         | 0.21%   |
| SunplusIT                              | 4         | 0.16%   |
| Intel                                  | 4         | 0.16%   |
| Pixart Imaging                         | 3         | 0.12%   |
| MSD                                    | 3         | 0.12%   |
| Unknown                                | 2         | 0.08%   |
| Holitech                               | 2         | 0.08%   |
| Foxconn / Hon Hai                      | 2         | 0.08%   |
| Spreadtrum Communications              | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| Hewlett-Packard                        | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| Generalplus Technology                 | 1         | 0.04%   |
| GEMBIRD                                | 1         | 0.04%   |
| eMPIA Technology                       | 1         | 0.04%   |
| Cubeternet                             | 1         | 0.04%   |
| Arkmicro Technologies                  | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 134       | 5.51%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 115       | 4.72%   |
| Realtek Integrated_Webcam_HD                                   | 106       | 4.35%   |
| Chicony Integrated Camera                                      | 100       | 4.11%   |
| IMC Networks Integrated Camera                                 | 96        | 3.94%   |
| Sunplus Integrated_Webcam_HD                                   | 83        | 3.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 73        | 3%      |
| Realtek Integrated Webcam                                      | 55        | 2.26%   |
| Chicony HP TrueVision HD Camera                                | 48        | 1.97%   |
| Chicony HP TrueVision HD                                       | 47        | 1.93%   |
| Acer Integrated Camera                                         | 45        | 1.85%   |
| Chicony HD WebCam                                              | 43        | 1.77%   |
| Syntek Integrated Camera                                       | 42        | 1.73%   |
| Chicony EasyCamera                                             | 39        | 1.6%    |
| Suyin HP TrueVision HD                                         | 38        | 1.56%   |
| Quanta HP TrueVision HD Camera                                 | 35        | 1.44%   |
| Quanta HD User Facing                                          | 34        | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 32        | 1.31%   |
| Acer Lenovo EasyCamera                                         | 29        | 1.19%   |
| Syntek EasyCamera                                              | 27        | 1.11%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 27        | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 26        | 1.07%   |
| Acer EasyCamera                                                | 26        | 1.07%   |
| Quanta HD Webcam                                               | 25        | 1.03%   |
| Lite-On Integrated Camera                                      | 25        | 1.03%   |
| Chicony HD User Facing                                         | 25        | 1.03%   |
| Suyin Integrated_Webcam_HD                                     | 23        | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 22        | 0.9%    |
| Microdia Integrated Webcam                                     | 22        | 0.9%    |
| Realtek EasyCamera                                             | 19        | 0.78%   |
| IMC Networks HP TrueVision HD Camera                           | 19        | 0.78%   |
| Chicony Integrated Camera (1280x720@30)                        | 17        | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)                        | 16        | 0.66%   |
| IMC Networks VGA UVC WebCam                                    | 16        | 0.66%   |
| Acer SunplusIT Integrated Camera                               | 16        | 0.66%   |
| Sunplus HP TrueVision HD Camera                                | 15        | 0.62%   |
| Sonix USB2.0 HD UVC WebCam                                     | 15        | 0.62%   |
| Acer Lenovo Integrated Webcam                                  | 15        | 0.62%   |
| Syntek Lenovo EasyCamera                                       | 14        | 0.58%   |
| Realtek Lenovo EasyCamera                                      | 14        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 157       | 35.6%   |
| Synaptics                          | 87        | 19.73%  |
| Shenzhen Goodix Technology         | 87        | 19.73%  |
| Elan Microelectronics              | 61        | 13.83%  |
| LighTuning Technology              | 21        | 4.76%   |
| Upek                               | 10        | 2.27%   |
| AuthenTec                          | 10        | 2.27%   |
| Focal-systems.Corp                 | 5         | 1.13%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.45%   |
| STMicroelectronics                 | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 48        | 10.88%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 9.98%   |
| Elan ELAN:ARM-M4                                                           | 35        | 7.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 33        | 7.48%   |
| Elan ELAN:Fingerprint                                                      | 26        | 5.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 22        | 4.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 4.76%   |
| Unknown                                                                    | 21        | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 3.4%    |
| Synaptics  WBDI                                                            | 13        | 2.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 12        | 2.72%   |
| Validity Sensors VFS491                                                    | 10        | 2.27%   |
| Validity Sensors VFS Fingerprint sensor                                    | 10        | 2.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.59%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.36%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.36%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.36%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.13%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.13%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.91%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.91%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.45%   |
| AuthenTec AES1600                                                          | 2         | 0.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.23%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.23%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 45        | 62.5%   |
| Alcor Micro | 15        | 20.83%  |
| Upek        | 6         | 8.33%   |
| O2 Micro    | 3         | 4.17%   |
| Lenovo      | 3         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 23.61%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 20.83%  |
| Broadcom 5880                                                                | 11        | 15.28%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 13.89%  |
| Broadcom 58200                                                               | 7         | 9.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1690      | 63.89%  |
| 1     | 802       | 30.32%  |
| 2     | 124       | 4.69%   |
| 3     | 20        | 0.76%   |
| 4     | 4         | 0.15%   |
| 5     | 3         | 0.11%   |
| 9     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 436       | 39.03%  |
| Graphics card            | 250       | 22.38%  |
| Net/wireless             | 153       | 13.7%   |
| Chipcard                 | 70        | 6.27%   |
| Bluetooth                | 66        | 5.91%   |
| Multimedia controller    | 54        | 4.83%   |
| Camera                   | 27        | 2.42%   |
| Communication controller | 25        | 2.24%   |
| Net/ethernet             | 11        | 0.98%   |
| Sound                    | 10        | 0.9%    |
| Storage                  | 8         | 0.72%   |
| Card reader              | 3         | 0.27%   |
| Network                  | 2         | 0.18%   |
| Modem                    | 2         | 0.18%   |

