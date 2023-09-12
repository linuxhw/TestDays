Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 6468

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Clevo         | M1100M                      | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| TUXEDO        | Unknown                     | [1e6c412d84](https://linux-hardware.org/?probe=1e6c412d84) | Sep 06, 2023 |
| HP            | Notebook                    | [ad9bafda30](https://linux-hardware.org/?probe=ad9bafda30) | Sep 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [03f6b3b62b](https://linux-hardware.org/?probe=03f6b3b62b) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | [a5c77b2450](https://linux-hardware.org/?probe=a5c77b2450) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | [f864c8e44a](https://linux-hardware.org/?probe=f864c8e44a) | Sep 05, 2023 |
| Sony          | SVE1713X1EB                 | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| Notebook      | N9x0TC                      | [ea9c38200b](https://linux-hardware.org/?probe=ea9c38200b) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| Toshiba       | Satellite C850-1DZ          | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| ASUSTek       | K52JB                       | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| HP            | Notebook                    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| HP            | Laptop 15s-eq3xxx           | [399abaa799](https://linux-hardware.org/?probe=399abaa799) | Sep 02, 2023 |
| Microtech     | ebookPro                    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| Chuwi         | LapBook Pro                 | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Acer          | Aspire 5715Z                | [1cb91dff9e](https://linux-hardware.org/?probe=1cb91dff9e) | Sep 01, 2023 |
| Acer          | Extensa 5635Z               | [da70c2acd8](https://linux-hardware.org/?probe=da70c2acd8) | Sep 01, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [b52faa8776](https://linux-hardware.org/?probe=b52faa8776) | Sep 01, 2023 |
| HP            | EliteBook 6930p             | [f40d8bbc73](https://linux-hardware.org/?probe=f40d8bbc73) | Sep 01, 2023 |
| ASUSTek       | S301LP                      | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [a45654cfd8](https://linux-hardware.org/?probe=a45654cfd8) | Aug 31, 2023 |
| Notebook      | N9x0TC                      | [f37b35c8dc](https://linux-hardware.org/?probe=f37b35c8dc) | Aug 31, 2023 |
| HP            | EliteBook 840 14 inch G9... | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0PA0... | [89caf6d252](https://linux-hardware.org/?probe=89caf6d252) | Aug 31, 2023 |
| ASUSTek       | GL753VD                     | [649fb869a6](https://linux-hardware.org/?probe=649fb869a6) | Aug 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [23242fe856](https://linux-hardware.org/?probe=23242fe856) | Aug 31, 2023 |
| Acer          | Aspire 1700                 | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470 20HES0ET0R    | [65d003a7a0](https://linux-hardware.org/?probe=65d003a7a0) | Aug 30, 2023 |
| HP            | 255 G8 Notebook PC          | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| Dell          | Inspiron 7548               | [6b6a2e7632](https://linux-hardware.org/?probe=6b6a2e7632) | Aug 30, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [4ac0615cbb](https://linux-hardware.org/?probe=4ac0615cbb) | Aug 30, 2023 |
| Acer          | Swift SF314-52              | [4f6b648f42](https://linux-hardware.org/?probe=4f6b648f42) | Aug 30, 2023 |
| Dell          | Vostro 2520                 | [73ca89b4fa](https://linux-hardware.org/?probe=73ca89b4fa) | Aug 30, 2023 |
| HUAWEI        | KLVD-WXX9                   | [98262b8471](https://linux-hardware.org/?probe=98262b8471) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| Apple         | MacBookPro7,1               | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [d0453c59f5](https://linux-hardware.org/?probe=d0453c59f5) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c54b2881a](https://linux-hardware.org/?probe=6c54b2881a) | Aug 27, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [8c616e6421](https://linux-hardware.org/?probe=8c616e6421) | Aug 27, 2023 |
| HP            | 470 G8 Notebook PC          | [b725ab24df](https://linux-hardware.org/?probe=b725ab24df) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [2ee2c8dd6c](https://linux-hardware.org/?probe=2ee2c8dd6c) | Aug 26, 2023 |
| ASUSTek       | T100HAN                     | [73c5eff054](https://linux-hardware.org/?probe=73c5eff054) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| HP            | Compaq Presario CQ60        | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| Lenovo        | V15-IIL 82C5                | [fbe986e246](https://linux-hardware.org/?probe=fbe986e246) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| HP            | ENVY 15                     | [6367186102](https://linux-hardware.org/?probe=6367186102) | Aug 24, 2023 |
| Lenovo        | ThinkPad T430 2347DS4       | [cbaaad3882](https://linux-hardware.org/?probe=cbaaad3882) | Aug 24, 2023 |
| Acer          | Aspire 5750G                | [b7ab89701b](https://linux-hardware.org/?probe=b7ab89701b) | Aug 24, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [e71571b95d](https://linux-hardware.org/?probe=e71571b95d) | Aug 24, 2023 |
| HP            | 250 G4                      | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| HP            | Pavilion x2 Detachable      | [a8fb075a9a](https://linux-hardware.org/?probe=a8fb075a9a) | Aug 23, 2023 |
| Acer          | TravelMate 7730G            | [e286f4c997](https://linux-hardware.org/?probe=e286f4c997) | Aug 23, 2023 |
| Dell          | Vostro 5471                 | [342ccb8530](https://linux-hardware.org/?probe=342ccb8530) | Aug 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [f56ee94116](https://linux-hardware.org/?probe=f56ee94116) | Aug 22, 2023 |
| Acer          | Nitro AN515-56              | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| MSI           | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [285b51551c](https://linux-hardware.org/?probe=285b51551c) | Aug 22, 2023 |
| HP            | Pavilion dv6                | [10badbd20d](https://linux-hardware.org/?probe=10badbd20d) | Aug 22, 2023 |
| Acer          | Aspire A315-23              | [9b3a3cd47b](https://linux-hardware.org/?probe=9b3a3cd47b) | Aug 22, 2023 |
| HP            | 530                         | [2b631777d9](https://linux-hardware.org/?probe=2b631777d9) | Aug 22, 2023 |
| Sony          | SVE1713X1EB                 | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713IE_G713IE     | [22443858cb](https://linux-hardware.org/?probe=22443858cb) | Aug 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [359cd5a655](https://linux-hardware.org/?probe=359cd5a655) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [b6f1a58560](https://linux-hardware.org/?probe=b6f1a58560) | Aug 20, 2023 |
| Lenovo        | ThinkPad X230 2325H50       | [65dd59e7d2](https://linux-hardware.org/?probe=65dd59e7d2) | Aug 20, 2023 |
| Acer          | Nitro AN515-56              | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| ASUSTek       | X540NA                      | [2f3758945b](https://linux-hardware.org/?probe=2f3758945b) | Aug 20, 2023 |
| HP            | Pavilion 15                 | [63e1b9e62c](https://linux-hardware.org/?probe=63e1b9e62c) | Aug 20, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| PC Special... | Ionico 16                   | [96fb68dc70](https://linux-hardware.org/?probe=96fb68dc70) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [66c64c5da8](https://linux-hardware.org/?probe=66c64c5da8) | Aug 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c19ed9405c](https://linux-hardware.org/?probe=c19ed9405c) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| HP            | 250 G4 Notebook PC          | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| PC Special... | Ionico 16                   | [da33e8f1c1](https://linux-hardware.org/?probe=da33e8f1c1) | Aug 18, 2023 |
| Notebook      | NS50MU                      | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [0438f450f4](https://linux-hardware.org/?probe=0438f450f4) | Aug 17, 2023 |
| HP            | Laptop 15s-fq5xxx           | [d3926b324c](https://linux-hardware.org/?probe=d3926b324c) | Aug 16, 2023 |
| Dell          | Latitude 5414               | [74b8020613](https://linux-hardware.org/?probe=74b8020613) | Aug 16, 2023 |
| Samsung       | RC530/RC730                 | [f9ce7b0ef5](https://linux-hardware.org/?probe=f9ce7b0ef5) | Aug 15, 2023 |
| Samsung       | RC530/RC730                 | [86f3ddda0c](https://linux-hardware.org/?probe=86f3ddda0c) | Aug 15, 2023 |
| Dell          | Inspiron 7590               | [4438df6adb](https://linux-hardware.org/?probe=4438df6adb) | Aug 15, 2023 |
| HP            | 15                          | [9b9e2459a8](https://linux-hardware.org/?probe=9b9e2459a8) | Aug 15, 2023 |
| HP            | ENVY 15                     | [caa5e1d37a](https://linux-hardware.org/?probe=caa5e1d37a) | Aug 14, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [6c7c115335](https://linux-hardware.org/?probe=6c7c115335) | Aug 14, 2023 |
| ASUSTek       | X553MA                      | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Dell          | Inspiron 5584               | [9fb83333a5](https://linux-hardware.org/?probe=9fb83333a5) | Aug 13, 2023 |
| Lenovo        | V130-15IKB 81HN             | [ca2c61168c](https://linux-hardware.org/?probe=ca2c61168c) | Aug 13, 2023 |
| HP            | 250 G8 Notebook PC          | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [bb650e1dd2](https://linux-hardware.org/?probe=bb650e1dd2) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fb024a9374](https://linux-hardware.org/?probe=fb024a9374) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [398f85e94a](https://linux-hardware.org/?probe=398f85e94a) | Aug 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| Dell          | Latitude 5300               | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [9627b6d632](https://linux-hardware.org/?probe=9627b6d632) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [099d1ac0de](https://linux-hardware.org/?probe=099d1ac0de) | Aug 10, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Unknown       | Unknown                     | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| HP            | EliteBook 8470p             | [16acf13ed8](https://linux-hardware.org/?probe=16acf13ed8) | Aug 09, 2023 |
| HP            | 255 G5                      | [d4adfe0ead](https://linux-hardware.org/?probe=d4adfe0ead) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Dell          | Inspiron 5584               | [33e964d1d6](https://linux-hardware.org/?probe=33e964d1d6) | Aug 09, 2023 |
| Dell          | XPS L521X                   | [5aec7ef034](https://linux-hardware.org/?probe=5aec7ef034) | Aug 08, 2023 |
| Dell          | Latitude 7440               | [0cfa45fbd8](https://linux-hardware.org/?probe=0cfa45fbd8) | Aug 08, 2023 |
| Dell          | Latitude 7440               | [e476a3e532](https://linux-hardware.org/?probe=e476a3e532) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| Timi          | A7S                         | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Dell          | Latitude E5540              | [928c427cbc](https://linux-hardware.org/?probe=928c427cbc) | Aug 06, 2023 |
| Dell          | Precision 7730              | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | 255 G8 Notebook PC          | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| Dell          | Inspiron 5584               | [7a4e005f77](https://linux-hardware.org/?probe=7a4e005f77) | Aug 06, 2023 |
| Dell          | Latitude E6230              | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| Dell          | Inspiron 15 5510            | [6d78d72399](https://linux-hardware.org/?probe=6d78d72399) | Aug 05, 2023 |
| Mediacom      | SmartBook 130 FullHD - M... | [3aa51361ae](https://linux-hardware.org/?probe=3aa51361ae) | Aug 05, 2023 |
| Apple         | MacBookAir7,2               | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| HP            | Notebook                    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Dell          | Latitude 5530               | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| PC Special... | Lafite Pro III 17           | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| Timi          | A7S                         | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| HP            | ENVY 17                     | [ef244ad969](https://linux-hardware.org/?probe=ef244ad969) | Aug 02, 2023 |
| HP            | 255 G8 Notebook PC          | [d0e963d600](https://linux-hardware.org/?probe=d0e963d600) | Aug 02, 2023 |
| Dell          | Precision 3571              | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| MSI           | Alpha 15 B5EEK              | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [00c9fab30f](https://linux-hardware.org/?probe=00c9fab30f) | Jul 31, 2023 |
| ASUSTek       | P552LA                      | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| SiComputer    | NL40_50CU                   | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| Beelink       | Gemini X                    | [2846d152be](https://linux-hardware.org/?probe=2846d152be) | Jul 29, 2023 |
| Dell          | System XPS L702X            | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Lenovo        | V15-IGL 82C3                | [613164e308](https://linux-hardware.org/?probe=613164e308) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| ASUSTek       | P50IJ                       | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | [47d5775197](https://linux-hardware.org/?probe=47d5775197) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [f347019f85](https://linux-hardware.org/?probe=f347019f85) | Jul 24, 2023 |
| Dell          | Latitude 5420               | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| HP            | 250 G3                      | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | [2def302827](https://linux-hardware.org/?probe=2def302827) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | [2f0b072622](https://linux-hardware.org/?probe=2f0b072622) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Timi          | A7S                         | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [ff5392a180](https://linux-hardware.org/?probe=ff5392a180) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 250 G1                      | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| MSI           | GL63 8SD                    | [7705e15f5e](https://linux-hardware.org/?probe=7705e15f5e) | Jul 21, 2023 |
| Dell          | XPS 9315                    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Sony          | SVE1713X1EB                 | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| Acer          | Aspire 7750G                | [c7d69d227a](https://linux-hardware.org/?probe=c7d69d227a) | Jul 17, 2023 |
| MSI           | Creator 17 A10SE            | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [7f25599ad8](https://linux-hardware.org/?probe=7f25599ad8) | Jul 17, 2023 |
| Unknown       | Unknown                     | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8c94595be0](https://linux-hardware.org/?probe=8c94595be0) | Jul 17, 2023 |
| Olivetti      | Olipad Graphos W811         | [d303fe2826](https://linux-hardware.org/?probe=d303fe2826) | Jul 17, 2023 |
| Toshiba       | TECRA A10                   | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| ASUSTek       | K53SJ                       | [eb5e64c657](https://linux-hardware.org/?probe=eb5e64c657) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| HP            | 250 G8 Notebook PC          | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| Lenovo        | ThinkPad T450 20BUS0S902    | [34329ab49c](https://linux-hardware.org/?probe=34329ab49c) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Notebook      | PCX0DX                      | [4b7f45adc4](https://linux-hardware.org/?probe=4b7f45adc4) | Jul 15, 2023 |
| HUAWEI        | BOM-WXX9                    | [31ae047fcf](https://linux-hardware.org/?probe=31ae047fcf) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [25bd8ff761](https://linux-hardware.org/?probe=25bd8ff761) | Jul 14, 2023 |
| HUAWEI        | HN-WX9X                     | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| HP            | ENVY 15                     | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Dell          | Latitude 5501               | [b10b0e72f0](https://linux-hardware.org/?probe=b10b0e72f0) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| Toshiba       | Satellite Pro S500          | [b9b5f89f0c](https://linux-hardware.org/?probe=b9b5f89f0c) | Jul 12, 2023 |
| Acer          | Aspire A515-47              | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | [bc78a01502](https://linux-hardware.org/?probe=bc78a01502) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | [c01febb128](https://linux-hardware.org/?probe=c01febb128) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [a4f7584ee4](https://linux-hardware.org/?probe=a4f7584ee4) | Jul 12, 2023 |
| MSI           | Katana GF66 12UC            | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Panasonic     | CF-C1BD06EFG                | [3b5ab4416a](https://linux-hardware.org/?probe=3b5ab4416a) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [71329b9909](https://linux-hardware.org/?probe=71329b9909) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| Dell          | Latitude E6440              | [6265e6109a](https://linux-hardware.org/?probe=6265e6109a) | Jul 09, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [acdb08441f](https://linux-hardware.org/?probe=acdb08441f) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| Acer          | Aspire F5-573G              | [10cf2c3aa5](https://linux-hardware.org/?probe=10cf2c3aa5) | Jul 09, 2023 |
| HP            | Notebook                    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| Acer          | Aspire V3-371               | [b4f20e8bc3](https://linux-hardware.org/?probe=b4f20e8bc3) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| Acer          | Chapala                     | [6ea600326f](https://linux-hardware.org/?probe=6ea600326f) | Jul 08, 2023 |
| MSI           | Alpha 15 B5EEK              | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | Inspiron 7720               | [dde4874147](https://linux-hardware.org/?probe=dde4874147) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| Acer          | Aspire E1-570G              | [f1d3e3070e](https://linux-hardware.org/?probe=f1d3e3070e) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| Timi          | RedmiBook 16                | [dbb5eb75b8](https://linux-hardware.org/?probe=dbb5eb75b8) | Jul 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [e484073491](https://linux-hardware.org/?probe=e484073491) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | [276cdeb14d](https://linux-hardware.org/?probe=276cdeb14d) | Jul 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [e134f78b10](https://linux-hardware.org/?probe=e134f78b10) | Jul 07, 2023 |
| Dell          | Precision M6800             | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Dell          | Latitude 7440               | [2efee1eb6c](https://linux-hardware.org/?probe=2efee1eb6c) | Jul 05, 2023 |
| Sony          | VGN-NS21M_W                 | [36b9bc971f](https://linux-hardware.org/?probe=36b9bc971f) | Jul 05, 2023 |
| MSI           | Creator 15M A9SD            | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| ASUSTek       | K55VD                       | [1a3814f9d9](https://linux-hardware.org/?probe=1a3814f9d9) | Jul 03, 2023 |
| Toshiba       | Satellite C660              | [3e88dd8cd6](https://linux-hardware.org/?probe=3e88dd8cd6) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | [de620c05a9](https://linux-hardware.org/?probe=de620c05a9) | Jul 03, 2023 |
| MSI           | Katana GF66 12UC            | [b241427d10](https://linux-hardware.org/?probe=b241427d10) | Jul 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9ebec4e811](https://linux-hardware.org/?probe=9ebec4e811) | Jul 03, 2023 |
| Jumper        | EZbook                      | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [2ac145f096](https://linux-hardware.org/?probe=2ac145f096) | Jul 02, 2023 |
| HP            | Pavilion dv6                | [0840377177](https://linux-hardware.org/?probe=0840377177) | Jul 02, 2023 |
| Dell          | Latitude E6420              | [aae88e9000](https://linux-hardware.org/?probe=aae88e9000) | Jul 01, 2023 |
| Acer          | Aspire A315-55G             | [caddb7bcf7](https://linux-hardware.org/?probe=caddb7bcf7) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Acer          | Aspire 7750G                | [ec3012e08e](https://linux-hardware.org/?probe=ec3012e08e) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| Dell          | Latitude 5521               | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Acer          | Aspire 5750G                | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Dell          | Latitude 7440               | [24f85667ac](https://linux-hardware.org/?probe=24f85667ac) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | [7f0ae1c657](https://linux-hardware.org/?probe=7f0ae1c657) | Jun 27, 2023 |
| Dell          | XPS 15 9500                 | [8ea6d92813](https://linux-hardware.org/?probe=8ea6d92813) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| HP            | ENVY 15                     | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [fe7974bbc9](https://linux-hardware.org/?probe=fe7974bbc9) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [3051c4ac4e](https://linux-hardware.org/?probe=3051c4ac4e) | Jun 26, 2023 |
| Acer          | Aspire V3-772               | [12cc9ac9dc](https://linux-hardware.org/?probe=12cc9ac9dc) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Google        | Sasuke                      | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| HP            | Presario CQ56               | [5a8991a97b](https://linux-hardware.org/?probe=5a8991a97b) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | ENVY 15                     | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| HP            | Pavilion g6                 | [fa58c1a1fd](https://linux-hardware.org/?probe=fa58c1a1fd) | Jun 22, 2023 |
| Acer          | Aspire 7720G                | [a8e44a5ab1](https://linux-hardware.org/?probe=a8e44a5ab1) | Jun 22, 2023 |
| HP            | Pavilion g6                 | [a58868d782](https://linux-hardware.org/?probe=a58868d782) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| ASUSTek       | K55VD                       | [223967ea1d](https://linux-hardware.org/?probe=223967ea1d) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Sony          | VGN-NS21M_W                 | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| ASUSTek       | K55VD                       | [49f6cc6986](https://linux-hardware.org/?probe=49f6cc6986) | Jun 20, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | [42ba3d75e5](https://linux-hardware.org/?probe=42ba3d75e5) | Jun 20, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [6e2f7d8295](https://linux-hardware.org/?probe=6e2f7d8295) | Jun 20, 2023 |
| Samsung       | RC420/RC520/RC720           | [406b650f19](https://linux-hardware.org/?probe=406b650f19) | Jun 19, 2023 |
| MSI           | PS63 Modern 8RC             | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Dell          | Latitude 5520               | [09da4ee3c4](https://linux-hardware.org/?probe=09da4ee3c4) | Jun 18, 2023 |
| Dell          | Latitude 5520               | [5e70c1929c](https://linux-hardware.org/?probe=5e70c1929c) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| Sony          | SVE1713X1EB                 | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| HUAWEI        | MACH-WX9                    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| HP            | ENVY 15                     | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [bbc15bef9c](https://linux-hardware.org/?probe=bbc15bef9c) | Jun 15, 2023 |
| Acer          | Aspire 1810T                | [1b1d11f461](https://linux-hardware.org/?probe=1b1d11f461) | Jun 14, 2023 |
| Samsung       | N130                        | [3efb763643](https://linux-hardware.org/?probe=3efb763643) | Jun 14, 2023 |
| MSI           | GL73 8RE                    | [e37b06f2b0](https://linux-hardware.org/?probe=e37b06f2b0) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| Dell          | XPS 15 9560                 | [f3b25c0959](https://linux-hardware.org/?probe=f3b25c0959) | Jun 14, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Dell          | Latitude E5540              | [029d51e57f](https://linux-hardware.org/?probe=029d51e57f) | Jun 13, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [d910ebe7bb](https://linux-hardware.org/?probe=d910ebe7bb) | Jun 13, 2023 |
| Dell          | Latitude E7250              | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| HP            | ZBook 15 G6                 | [180abd0b90](https://linux-hardware.org/?probe=180abd0b90) | Jun 11, 2023 |
| Valve         | Jupiter                     | [d276b58f38](https://linux-hardware.org/?probe=d276b58f38) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bdca36306b](https://linux-hardware.org/?probe=bdca36306b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Onda TLC      | ONDA Oliver                 | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | [b88712538e](https://linux-hardware.org/?probe=b88712538e) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | [51bfdec531](https://linux-hardware.org/?probe=51bfdec531) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| ASUSTek       | X580VN                      | [8c1cf3f164](https://linux-hardware.org/?probe=8c1cf3f164) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Acer          | AO722                       | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| Dell          | Latitude 5300               | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | AO722                       | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Acer          | Aspire E5-573G              | [3ef3c9ec82](https://linux-hardware.org/?probe=3ef3c9ec82) | Jun 04, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| HP            | ZBook 15 G2                 | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HONOR         | BBR-WAX9                    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Olidata       | Tehom cw4900                | [f5b147962f](https://linux-hardware.org/?probe=f5b147962f) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Jumper        | EZbook                      | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| HP            | ENVY 15                     | [ad3cf182fe](https://linux-hardware.org/?probe=ad3cf182fe) | May 30, 2023 |
| HP            | ENVY 15                     | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bb50e13268](https://linux-hardware.org/?probe=bb50e13268) | May 30, 2023 |
| HP            | Pavilion 15                 | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Unknown       | Unknown                     | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Acer          | Aspire A515-41G             | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Apple         | MacBookAir7,2               | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| Apple         | MacBookPro7,1               | [81a267d02b](https://linux-hardware.org/?probe=81a267d02b) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| Apple         | MacBookPro6,2               | [db9c87ce89](https://linux-hardware.org/?probe=db9c87ce89) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | Pavilion x2 Detachable      | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| Acer          | Aspire 7750G                | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Lenovo        | IdeaPad Z580                | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| ASUSTek       | S551LB                      | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Sony          | SVE1513Q1ESI                | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Dell          | Precision 3571              | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Acer          | Aspire 7750G                | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Valve         | Jupiter                     | [223ab4f15c](https://linux-hardware.org/?probe=223ab4f15c) | May 23, 2023 |
| HP            | ENVY 15                     | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Sony          | SVE1513Q1ESI                | [eef57d6c26](https://linux-hardware.org/?probe=eef57d6c26) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Dell          | Latitude E6230              | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5cb11eee20](https://linux-hardware.org/?probe=5cb11eee20) | May 22, 2023 |
| HP            | ENVY 15                     | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| ASUSTek       | N53TK                       | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Acer          | Aspire 7750G                | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Acer          | Aspire V3-572G              | [8f1be2d961](https://linux-hardware.org/?probe=8f1be2d961) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| Toshiba       | Satellite Pro S500          | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Valve         | Jupiter                     | [6b5b728c7e](https://linux-hardware.org/?probe=6b5b728c7e) | May 20, 2023 |
| Unknown       | Unknown                     | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| HP            | Pavilion dv3                | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Unknown       | Unknown                     | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| ASUSTek       | X555LPB                     | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Acer          | Aspire 5920G                | [65638219a5](https://linux-hardware.org/?probe=65638219a5) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [b5aef01bc9](https://linux-hardware.org/?probe=b5aef01bc9) | May 17, 2023 |
| HP            | ENVY 15                     | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| ASUSTek       | UX305FA                     | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| HP            | Pavilion dv6                | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Acer          | Nitro AN515-45              | [62e3c494bd](https://linux-hardware.org/?probe=62e3c494bd) | May 16, 2023 |
| Valve         | Jupiter                     | [6c64da33ef](https://linux-hardware.org/?probe=6c64da33ef) | May 16, 2023 |
| Apple         | MacBook4,1                  | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| Dell          | Precision 7520              | [cbfb960bae](https://linux-hardware.org/?probe=cbfb960bae) | May 15, 2023 |
| Dell          | Precision 7520              | [a42d1a8bf5](https://linux-hardware.org/?probe=a42d1a8bf5) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [ca65ed1052](https://linux-hardware.org/?probe=ca65ed1052) | May 14, 2023 |
| HP            | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Valve         | Jupiter                     | [af70e39629](https://linux-hardware.org/?probe=af70e39629) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1bb0ed422e](https://linux-hardware.org/?probe=1bb0ed422e) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| HP            | ENVY 15                     | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Unknown       | Unknown                     | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | OMEN by Laptop              | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Unknown       | Unknown                     | [00f98129ce](https://linux-hardware.org/?probe=00f98129ce) | May 11, 2023 |
| Valve         | Jupiter                     | [ec8ac0aafd](https://linux-hardware.org/?probe=ec8ac0aafd) | May 11, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [e03da60adf](https://linux-hardware.org/?probe=e03da60adf) | May 11, 2023 |
| Acer          | Aspire 5715Z                | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Acer          | Aspire E5-553G              | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Dell          | Latitude 7420               | [4b8927333b](https://linux-hardware.org/?probe=4b8927333b) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | 255 G5                      | [4ed50eeba3](https://linux-hardware.org/?probe=4ed50eeba3) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4e95a5b88e](https://linux-hardware.org/?probe=4e95a5b88e) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire 5750G                | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Dell          | XPS 15 9570                 | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Notebook      | P750ZM                      | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| Apple         | MacBookPro3,1               | [561202c004](https://linux-hardware.org/?probe=561202c004) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Acer          | Aspire E5-551G              | [ab9ff23d88](https://linux-hardware.org/?probe=ab9ff23d88) | May 07, 2023 |
| Acer          | Aspire E5-551G              | [a21a8395d8](https://linux-hardware.org/?probe=a21a8395d8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| Dell          | XPS 13 9343                 | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Notebook                    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| HP            | EliteBook 2530p             | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| Lenovo        | IdeaPad U510 20191          | [23414f0626](https://linux-hardware.org/?probe=23414f0626) | May 06, 2023 |
| HP            | Notebook                    | [74f9f1122e](https://linux-hardware.org/?probe=74f9f1122e) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [a27c899176](https://linux-hardware.org/?probe=a27c899176) | May 04, 2023 |
| HP            | 255 G8 Notebook PC          | [af9621c92b](https://linux-hardware.org/?probe=af9621c92b) | May 04, 2023 |
| HP            | Elite x2 1012 G1            | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| HP            | Compaq Presario C700        | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Sony          | SVF1521G1EW                 | [b84b2ed08a](https://linux-hardware.org/?probe=b84b2ed08a) | May 03, 2023 |
| Acer          | Swift SF515-51T             | [80d7446f47](https://linux-hardware.org/?probe=80d7446f47) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4280750d03](https://linux-hardware.org/?probe=4280750d03) | May 03, 2023 |
| Samsung       | 750XDA                      | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [fd0dee0606](https://linux-hardware.org/?probe=fd0dee0606) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [910824ac40](https://linux-hardware.org/?probe=910824ac40) | May 03, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [56d274f769](https://linux-hardware.org/?probe=56d274f769) | May 03, 2023 |
| Lenovo        | V130-15IKB 81HN             | [8c3e5e8d50](https://linux-hardware.org/?probe=8c3e5e8d50) | May 03, 2023 |
| Dell          | Latitude E7270              | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Sony          | VPCF11C5E                   | [77f08d3d00](https://linux-hardware.org/?probe=77f08d3d00) | May 02, 2023 |
| Dell          | Latitude E7270              | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5375a4f57c](https://linux-hardware.org/?probe=5375a4f57c) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | 255 G4                      | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| Timi          | RedmiBook 16                | [01706331eb](https://linux-hardware.org/?probe=01706331eb) | May 01, 2023 |
| HP            | Compaq 8510w                | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| HP            | ENVY 15                     | [935dc183e1](https://linux-hardware.org/?probe=935dc183e1) | May 01, 2023 |
| HP            | OMEN by Laptop              | [bfbda66d8b](https://linux-hardware.org/?probe=bfbda66d8b) | May 01, 2023 |
| ASUSTek       | K52Jc                       | [ae414cf185](https://linux-hardware.org/?probe=ae414cf185) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Onda TLC      | ONDA Oliver                 | [c59dbdea18](https://linux-hardware.org/?probe=c59dbdea18) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Dell          | Inspiron MP061              | [2b25a48030](https://linux-hardware.org/?probe=2b25a48030) | Apr 23, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| Apple         | MacBook6,1                  | [47ea666f74](https://linux-hardware.org/?probe=47ea666f74) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [aace924665](https://linux-hardware.org/?probe=aace924665) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Lenovo        | G50-45 80E3                 | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| ASUSTek       | 1011PX                      | [6aa9d32dda](https://linux-hardware.org/?probe=6aa9d32dda) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9db7166b25](https://linux-hardware.org/?probe=9db7166b25) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| Apple         | MacBookPro8,1               | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| HP            | EliteBook 8570w             | [317efe55c2](https://linux-hardware.org/?probe=317efe55c2) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Medion        | E16401                      | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| Google        | Dragonair                   | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Google        | Dragonair                   | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [a51b096e12](https://linux-hardware.org/?probe=a51b096e12) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [1f524a54fc](https://linux-hardware.org/?probe=1f524a54fc) | Apr 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| Lenovo        | V15-IGL 82C3                | [3b24daf87d](https://linux-hardware.org/?probe=3b24daf87d) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Acer          | Aspire A715-42G             | [54a72d7d55](https://linux-hardware.org/?probe=54a72d7d55) | Apr 12, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| Lenovo        | ThinkPad L530 24783B3       | [9cb172cc6b](https://linux-hardware.org/?probe=9cb172cc6b) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [dae979ddc0](https://linux-hardware.org/?probe=dae979ddc0) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [e6e26b16f3](https://linux-hardware.org/?probe=e6e26b16f3) | Apr 11, 2023 |
| ASUSTek       | X541UV                      | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Apple         | MacBookPro11,5              | [2e428c73dc](https://linux-hardware.org/?probe=2e428c73dc) | Apr 10, 2023 |
| ASUSTek       | K52Jc                       | [0e6d01e44d](https://linux-hardware.org/?probe=0e6d01e44d) | Apr 09, 2023 |
| Lenovo        | V14-ADA 82C6                | [23a244aaf4](https://linux-hardware.org/?probe=23a244aaf4) | Apr 09, 2023 |
| AMI           | Intel                       | [f35d255c12](https://linux-hardware.org/?probe=f35d255c12) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | [594a8d9a89](https://linux-hardware.org/?probe=594a8d9a89) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| HP            | Pavilion dv7                | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [1e9120783f](https://linux-hardware.org/?probe=1e9120783f) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| HP            | G61                         | [8eec217a3a](https://linux-hardware.org/?probe=8eec217a3a) | Apr 07, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [bf0fc7e5d1](https://linux-hardware.org/?probe=bf0fc7e5d1) | Apr 06, 2023 |
| Dell          | XPS 9320                    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| Dell          | XPS 13 9380                 | [58e0aa6707](https://linux-hardware.org/?probe=58e0aa6707) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Fujitsu       | LIFEBOOK U759               | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| Dell          | Latitude 5591               | [aa2f4e4208](https://linux-hardware.org/?probe=aa2f4e4208) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [93fa18f474](https://linux-hardware.org/?probe=93fa18f474) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [915c34d052](https://linux-hardware.org/?probe=915c34d052) | Apr 03, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [cef60ea315](https://linux-hardware.org/?probe=cef60ea315) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| Lenovo        | B50-30 80ES                 | [a971008720](https://linux-hardware.org/?probe=a971008720) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| Unknown       | Unknown                     | [702a241ca6](https://linux-hardware.org/?probe=702a241ca6) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | [363d925d25](https://linux-hardware.org/?probe=363d925d25) | Apr 01, 2023 |
| ASUSTek       | X556UAK                     | [24f79c68f6](https://linux-hardware.org/?probe=24f79c68f6) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Valve         | Jupiter                     | [34766581f3](https://linux-hardware.org/?probe=34766581f3) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| ASUSTek       | N552VX                      | [cacf95c277](https://linux-hardware.org/?probe=cacf95c277) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| Dell          | Precision 3560              | [f6ef5c1a2c](https://linux-hardware.org/?probe=f6ef5c1a2c) | Mar 30, 2023 |
| Lenovo        | G505 20240                  | [25c5c7ee2e](https://linux-hardware.org/?probe=25c5c7ee2e) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [53bc341050](https://linux-hardware.org/?probe=53bc341050) | Mar 29, 2023 |
| Valve         | Jupiter                     | [889e4e5eef](https://linux-hardware.org/?probe=889e4e5eef) | Mar 29, 2023 |
| HP            | ProBook 640 G1              | [c9ac2eb353](https://linux-hardware.org/?probe=c9ac2eb353) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| Unknown       | Unknown                     | [26d819f9fc](https://linux-hardware.org/?probe=26d819f9fc) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Apple         | MacBookPro11,5              | [0c2be4a34c](https://linux-hardware.org/?probe=0c2be4a34c) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [3b8cd70b69](https://linux-hardware.org/?probe=3b8cd70b69) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Apple         | MacBookPro11,5              | [9fd6508caf](https://linux-hardware.org/?probe=9fd6508caf) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| ASUSTek       | K53SJ                       | [175f99ccdd](https://linux-hardware.org/?probe=175f99ccdd) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Dell          | Inspiron 1750               | [007a0b3bb7](https://linux-hardware.org/?probe=007a0b3bb7) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| Acer          | Extensa 5235                | [270cd6ed83](https://linux-hardware.org/?probe=270cd6ed83) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Notebook      | P15SM                       | [00d7786f9f](https://linux-hardware.org/?probe=00d7786f9f) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| HP            | Laptop 15-dw1xxx            | [63ecda6230](https://linux-hardware.org/?probe=63ecda6230) | Mar 18, 2023 |
| HP            | ProBook 6570b               | [f5c9cd8419](https://linux-hardware.org/?probe=f5c9cd8419) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | K61IC                       | [045474725b](https://linux-hardware.org/?probe=045474725b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Valve         | Jupiter                     | [fc387a787e](https://linux-hardware.org/?probe=fc387a787e) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b0b311216d](https://linux-hardware.org/?probe=b0b311216d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [d9f9e09a41](https://linux-hardware.org/?probe=d9f9e09a41) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [be16fd4aab](https://linux-hardware.org/?probe=be16fd4aab) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| HP            | Pavilion dv6500             | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [ee01825196](https://linux-hardware.org/?probe=ee01825196) | Mar 13, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Acer          | aspire5740                  | [d5e64f31d4](https://linux-hardware.org/?probe=d5e64f31d4) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Dell          | Latitude E6440              | [e5ba284442](https://linux-hardware.org/?probe=e5ba284442) | Mar 11, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| HP            | EliteBook 840 G1            | [1315898b67](https://linux-hardware.org/?probe=1315898b67) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [420b463f4d](https://linux-hardware.org/?probe=420b463f4d) | Mar 10, 2023 |
| ASUSTek       | X540LA                      | [de3c24e686](https://linux-hardware.org/?probe=de3c24e686) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [041ebfc8c6](https://linux-hardware.org/?probe=041ebfc8c6) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [8faa1d14ca](https://linux-hardware.org/?probe=8faa1d14ca) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| HP            | Pavilion dv6                | [a1631eb10b](https://linux-hardware.org/?probe=a1631eb10b) | Mar 07, 2023 |
| Unknown       | Unknown                     | [fdc4f4d3c6](https://linux-hardware.org/?probe=fdc4f4d3c6) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [f56dc75b4e](https://linux-hardware.org/?probe=f56dc75b4e) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| Acer          | Aspire E5-575G              | [fd8c378fda](https://linux-hardware.org/?probe=fd8c378fda) | Mar 07, 2023 |
| ASUSTek       | X556UAK                     | [51f2084195](https://linux-hardware.org/?probe=51f2084195) | Mar 06, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [745898b5de](https://linux-hardware.org/?probe=745898b5de) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [20fbc926fd](https://linux-hardware.org/?probe=20fbc926fd) | Mar 06, 2023 |
| Lenovo        | G50-45 80E3                 | [02dfdb807e](https://linux-hardware.org/?probe=02dfdb807e) | Mar 06, 2023 |
| HP            | G72                         | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Toshiba       | NB550D                      | [8ba5171640](https://linux-hardware.org/?probe=8ba5171640) | Mar 04, 2023 |
| HP            | G72                         | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4816618219](https://linux-hardware.org/?probe=4816618219) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| HP            | ENVY 15                     | [9ceefd9a22](https://linux-hardware.org/?probe=9ceefd9a22) | Mar 03, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [17f1328add](https://linux-hardware.org/?probe=17f1328add) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [f791caa732](https://linux-hardware.org/?probe=f791caa732) | Mar 03, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [0b39498d52](https://linux-hardware.org/?probe=0b39498d52) | Mar 03, 2023 |
| GMK           | NucBox2                     | [84af5a7d53](https://linux-hardware.org/?probe=84af5a7d53) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [c34c6d8786](https://linux-hardware.org/?probe=c34c6d8786) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2a1515aaa3](https://linux-hardware.org/?probe=2a1515aaa3) | Mar 02, 2023 |
| Acer          | TravelMate P253             | [aa56b7749c](https://linux-hardware.org/?probe=aa56b7749c) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Acer          | Aspire 5755G                | [c1594b1f9d](https://linux-hardware.org/?probe=c1594b1f9d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [98e86d41d1](https://linux-hardware.org/?probe=98e86d41d1) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [61fe88e268](https://linux-hardware.org/?probe=61fe88e268) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | Pavilion 15                 | [78f570552a](https://linux-hardware.org/?probe=78f570552a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [b518eb9925](https://linux-hardware.org/?probe=b518eb9925) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| Acer          | Aspire 5750G                | [34b5806bcf](https://linux-hardware.org/?probe=34b5806bcf) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| Acer          | Aspire E1-531               | [a52b94c2d5](https://linux-hardware.org/?probe=a52b94c2d5) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [2cea6ee649](https://linux-hardware.org/?probe=2cea6ee649) | Feb 26, 2023 |
| ASUSTek       | X540NA                      | [8bca0d4eb5](https://linux-hardware.org/?probe=8bca0d4eb5) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| ASUSTek       | T100HAN                     | [bde9736ffd](https://linux-hardware.org/?probe=bde9736ffd) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [84750f9d96](https://linux-hardware.org/?probe=84750f9d96) | Feb 25, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Acer          | Aspire ES1-521              | [e5f0a23afd](https://linux-hardware.org/?probe=e5f0a23afd) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| HP            | 250 G3                      | [6a3d2238ba](https://linux-hardware.org/?probe=6a3d2238ba) | Feb 25, 2023 |
| ASUSTek       | T100HAN                     | [fd75fdb59f](https://linux-hardware.org/?probe=fd75fdb59f) | Feb 25, 2023 |
| ASUSTek       | X556URK                     | [fc80e01794](https://linux-hardware.org/?probe=fc80e01794) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| BESSTAR Te... | X400                        | [e1c05e0782](https://linux-hardware.org/?probe=e1c05e0782) | Feb 25, 2023 |
| HP            | ENVY 17                     | [08db7a8be2](https://linux-hardware.org/?probe=08db7a8be2) | Feb 25, 2023 |
| HP            | ENVY 17                     | [0ad15a7e01](https://linux-hardware.org/?probe=0ad15a7e01) | Feb 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| HONOR         | HYM-WXX                     | [c6f84d1224](https://linux-hardware.org/?probe=c6f84d1224) | Feb 24, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [f24e6a55c4](https://linux-hardware.org/?probe=f24e6a55c4) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK U749               | [ba7cdc6018](https://linux-hardware.org/?probe=ba7cdc6018) | Feb 24, 2023 |
| ASUSTek       | X555LA                      | [502020fe52](https://linux-hardware.org/?probe=502020fe52) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| ASUSTek       | X510UQR                     | [075081e4ad](https://linux-hardware.org/?probe=075081e4ad) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Acer          | Aspire E1-531               | [4526585d29](https://linux-hardware.org/?probe=4526585d29) | Feb 24, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [a8fbcbec0e](https://linux-hardware.org/?probe=a8fbcbec0e) | Feb 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [cddc383ff9](https://linux-hardware.org/?probe=cddc383ff9) | Feb 23, 2023 |
| Acer          | Aspire SW3-013              | [771b90caaa](https://linux-hardware.org/?probe=771b90caaa) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [dbbcb7502c](https://linux-hardware.org/?probe=dbbcb7502c) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [d620cdcce0](https://linux-hardware.org/?probe=d620cdcce0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Acer          | TravelMate P253             | [b99414b6de](https://linux-hardware.org/?probe=b99414b6de) | Feb 23, 2023 |
| HP            | Pavilion g6                 | [c76844f9a1](https://linux-hardware.org/?probe=c76844f9a1) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [99d4f0df73](https://linux-hardware.org/?probe=99d4f0df73) | Feb 22, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [71928c5a75](https://linux-hardware.org/?probe=71928c5a75) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [57e007d035](https://linux-hardware.org/?probe=57e007d035) | Feb 22, 2023 |
| HP            | ENVY 17                     | [f705060f1e](https://linux-hardware.org/?probe=f705060f1e) | Feb 22, 2023 |
| HP            | ENVY 17                     | [bf86e7904b](https://linux-hardware.org/?probe=bf86e7904b) | Feb 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [05f20bac2d](https://linux-hardware.org/?probe=05f20bac2d) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| BESSTAR Te... | X400                        | [f7f9004058](https://linux-hardware.org/?probe=f7f9004058) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| Unknown       | Unknown                     | [46d473b3e5](https://linux-hardware.org/?probe=46d473b3e5) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [3a525ce932](https://linux-hardware.org/?probe=3a525ce932) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [f845d181ec](https://linux-hardware.org/?probe=f845d181ec) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [ec529ac1bd](https://linux-hardware.org/?probe=ec529ac1bd) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| HP            | EliteBook 8570w             | [a6fd2ffc5b](https://linux-hardware.org/?probe=a6fd2ffc5b) | Feb 20, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [51d702d217](https://linux-hardware.org/?probe=51d702d217) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Dell          | Inspiron 7520               | [1489b9779a](https://linux-hardware.org/?probe=1489b9779a) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [84e519800c](https://linux-hardware.org/?probe=84e519800c) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [2ffc7c4a96](https://linux-hardware.org/?probe=2ffc7c4a96) | Feb 19, 2023 |
| Packard Be... | EasyNote TJ65               | [2c98b99901](https://linux-hardware.org/?probe=2c98b99901) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1104c148d1](https://linux-hardware.org/?probe=1104c148d1) | Feb 19, 2023 |
| Dell          | Latitude 5480               | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [eb9f3822a0](https://linux-hardware.org/?probe=eb9f3822a0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 474       | 10.18%  |
| Ubuntu 18.04        | 295       | 6.34%   |
| Ubuntu 22.04        | 286       | 6.14%   |
| Arch Rolling        | 149       | 3.2%    |
| Debian 11           | 109       | 2.34%   |
| OpenMandriva 4.2    | 108       | 2.32%   |
| OpenMandriva 4.3    | 103       | 2.21%   |
| Fedora 36           | 93        | 2%      |
| Linux Mint 21.1     | 83        | 1.78%   |
| Pop!_OS 22.04       | 76        | 1.63%   |
| Arch                | 75        | 1.61%   |
| Fedora 37           | 73        | 1.57%   |
| Ubuntu 22.10        | 71        | 1.52%   |
| Xubuntu 18.04       | 69        | 1.48%   |
| Zorin 16            | 68        | 1.46%   |
| Ubuntu 19.10        | 68        | 1.46%   |
| Xubuntu 20.04       | 62        | 1.33%   |
| Ubuntu 20.10        | 61        | 1.31%   |
| Linux Mint 20.3     | 61        | 1.31%   |
| OpenMandriva 23.03  | 60        | 1.29%   |
| EndeavourOS Rolling | 59        | 1.27%   |
| Ubuntu 21.10        | 58        | 1.25%   |
| Ubuntu 19.04        | 56        | 1.2%    |
| KDE neon 20.04      | 54        | 1.16%   |
| Linux Mint 21       | 53        | 1.14%   |
| Zorin 15            | 49        | 1.05%   |
| Debian 10           | 46        | 0.99%   |
| Kubuntu 22.04       | 42        | 0.9%    |
| Fedora 35           | 42        | 0.9%    |
| Fedora 38           | 41        | 0.88%   |
| Ubuntu 18.10        | 40        | 0.86%   |
| Ubuntu 21.04        | 39        | 0.84%   |
| OpenMandriva 23.01  | 39        | 0.84%   |
| Linux Mint 20.1     | 36        | 0.77%   |
| Pop!_OS 20.10       | 35        | 0.75%   |
| Manjaro             | 35        | 0.75%   |
| Linux Mint 20.2     | 35        | 0.75%   |
| Linux Mint 20       | 35        | 0.75%   |
| Linux Mint 19.3     | 35        | 0.75%   |
| Kubuntu 20.04       | 35        | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1420      | 32.38%  |
| Linux Mint    | 342       | 7.8%    |
| OpenMandriva  | 338       | 7.71%   |
| Fedora        | 330       | 7.52%   |
| Arch          | 218       | 4.97%   |
| Debian        | 202       | 4.61%   |
| Xubuntu       | 189       | 4.31%   |
| Pop!_OS       | 167       | 3.81%   |
| Manjaro       | 131       | 2.99%   |
| Zorin         | 123       | 2.8%    |
| Kubuntu       | 123       | 2.8%    |
| ROSA          | 89        | 2.03%   |
| KDE neon      | 78        | 1.78%   |
| Lubuntu       | 63        | 1.44%   |
| EndeavourOS   | 61        | 1.39%   |
| openSUSE      | 54        | 1.23%   |
| Elementary    | 41        | 0.93%   |
| Ubuntu MATE   | 39        | 0.89%   |
| Endless       | 38        | 0.87%   |
| ArcoLinux     | 27        | 0.62%   |
| LMDE          | 23        | 0.52%   |
| MX            | 22        | 0.5%    |
| Gentoo        | 22        | 0.5%    |
| Ubuntu Unity  | 21        | 0.48%   |
| BlackPanther  | 20        | 0.46%   |
| Kali          | 18        | 0.41%   |
| Clear Linux   | 17        | 0.39%   |
| Ubuntu Budgie | 16        | 0.36%   |
| SteamOS       | 14        | 0.32%   |
| Garuda Linux  | 14        | 0.32%   |
| Peppermint    | 11        | 0.25%   |
| Parrot        | 11        | 0.25%   |
| Nobara        | 8         | 0.18%   |
| LinuxFX       | 7         | 0.16%   |
| Xero          | 5         | 0.11%   |
| NixOS         | 5         | 0.11%   |
| Chrome OS     | 5         | 0.11%   |
| Slackware     | 4         | 0.09%   |
| Q4OS          | 4         | 0.09%   |
| Linux Lite    | 4         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 103       | 2%      |
| 5.15.0-52-generic        | 98        | 1.9%    |
| 5.16.7-desktop-1omv4003  | 97        | 1.88%   |
| 5.4.0-42-generic         | 68        | 1.32%   |
| 5.15.0-56-generic        | 63        | 1.22%   |
| 6.2.6-desktop-1omv2390   | 59        | 1.15%   |
| 5.15.0-58-generic        | 44        | 0.86%   |
| 5.4.0-26-generic         | 41        | 0.8%    |
| 5.15.0-46-generic        | 41        | 0.8%    |
| 5.3.0-46-generic         | 40        | 0.78%   |
| 5.4.0-52-generic         | 36        | 0.7%    |
| 5.4.0-29-generic         | 36        | 0.7%    |
| 5.15.0-47-generic        | 35        | 0.68%   |
| 6.1.1-desktop-1omv2290   | 33        | 0.64%   |
| 5.4.0-58-generic         | 33        | 0.64%   |
| 5.15.0-43-generic        | 33        | 0.64%   |
| 5.3.0-40-generic         | 32        | 0.62%   |
| 5.3.0-42-generic         | 31        | 0.6%    |
| 5.4.0-48-generic         | 30        | 0.58%   |
| 5.15.0-41-generic        | 30        | 0.58%   |
| 6.0.2-arch1-1            | 28        | 0.54%   |
| 5.15.0-53-generic        | 27        | 0.52%   |
| 5.13.0-28-generic        | 27        | 0.52%   |
| 5.0.0-37-generic         | 27        | 0.52%   |
| 5.19.0-32-generic        | 26        | 0.51%   |
| 5.15.0-48-generic        | 25        | 0.49%   |
| 5.10.0-19-amd64          | 24        | 0.47%   |
| 5.3.0-51-generic         | 23        | 0.45%   |
| 5.19.0-23-generic        | 23        | 0.45%   |
| 5.19.0-21-generic        | 23        | 0.45%   |
| 5.15.0-60-generic        | 23        | 0.45%   |
| 5.10.0-21-amd64          | 23        | 0.45%   |
| 6.2.0-20-generic         | 22        | 0.43%   |
| 5.4.0-54-generic         | 22        | 0.43%   |
| 5.4.0-47-generic         | 22        | 0.43%   |
| 5.4.0-28-generic         | 22        | 0.43%   |
| 5.15.0-50-generic        | 21        | 0.41%   |
| 4.18.0-15-generic        | 21        | 0.41%   |
| 5.4.0-33-generic         | 20        | 0.39%   |
| 5.19.0-76051900-generic  | 20        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 692       | 14.38%  |
| 5.15.0  | 523       | 10.87%  |
| 4.15.0  | 244       | 5.07%   |
| 5.19.0  | 232       | 4.82%   |
| 5.3.0   | 224       | 4.66%   |
| 5.8.0   | 201       | 4.18%   |
| 5.13.0  | 199       | 4.14%   |
| 5.11.0  | 168       | 3.49%   |
| 5.10.0  | 146       | 3.03%   |
| 5.0.0   | 113       | 2.35%   |
| 5.10.14 | 103       | 2.14%   |
| 5.16.7  | 99        | 2.06%   |
| 4.18.0  | 87        | 1.81%   |
| 6.2.6   | 76        | 1.58%   |
| 6.2.0   | 59        | 1.23%   |
| 6.0.2   | 53        | 1.1%    |
| 4.19.0  | 45        | 0.94%   |
| 6.1.1   | 40        | 0.83%   |
| 6.1.0   | 33        | 0.69%   |
| 5.19.16 | 29        | 0.6%    |
| 6.0.0   | 27        | 0.56%   |
| 6.0.12  | 22        | 0.46%   |
| 5.17.5  | 20        | 0.42%   |
| 4.18.16 | 19        | 0.39%   |
| 6.0.7   | 18        | 0.37%   |
| 6.0.6   | 18        | 0.37%   |
| 4.9.60  | 18        | 0.37%   |
| 4.9.20  | 17        | 0.35%   |
| 4.4.0   | 17        | 0.35%   |
| 6.4.11  | 16        | 0.33%   |
| 5.17.1  | 14        | 0.29%   |
| 6.0.5   | 13        | 0.27%   |
| 6.2.9   | 12        | 0.25%   |
| 6.1.8   | 12        | 0.25%   |
| 6.0.9   | 12        | 0.25%   |
| 5.18.0  | 12        | 0.25%   |
| 5.14.0  | 12        | 0.25%   |
| 6.3.5   | 11        | 0.23%   |
| 6.0.10  | 11        | 0.23%   |
| 5.19.12 | 11        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 738       | 15.54%  |
| 5.15    | 612       | 12.88%  |
| 5.19    | 337       | 7.09%   |
| 5.10    | 306       | 6.44%   |
| 5.3     | 249       | 5.24%   |
| 4.15    | 245       | 5.16%   |
| 5.8     | 241       | 5.07%   |
| 5.13    | 220       | 4.63%   |
| 6.0     | 206       | 4.34%   |
| 5.11    | 205       | 4.32%   |
| 6.2     | 203       | 4.27%   |
| 6.1     | 164       | 3.45%   |
| 5.16    | 153       | 3.22%   |
| 5.0     | 116       | 2.44%   |
| 4.18    | 109       | 2.29%   |
| 5.17    | 66        | 1.39%   |
| 4.9     | 62        | 1.31%   |
| 6.4     | 60        | 1.26%   |
| 5.14    | 58        | 1.22%   |
| 4.19    | 58        | 1.22%   |
| 6.3     | 54        | 1.14%   |
| 5.18    | 54        | 1.14%   |
| 5.9     | 46        | 0.97%   |
| 5.12    | 37        | 0.78%   |
| 5.6     | 34        | 0.72%   |
| 5.5     | 34        | 0.72%   |
| 5.7     | 23        | 0.48%   |
| 4.4     | 18        | 0.38%   |
| 5.2     | 9         | 0.19%   |
| 4.13    | 6         | 0.13%   |
| 4.1     | 6         | 0.13%   |
| 5.1     | 4         | 0.08%   |
| 4.12    | 4         | 0.08%   |
| 4.20    | 3         | 0.06%   |
| 4.17    | 3         | 0.06%   |
| 4.16    | 2         | 0.04%   |
| 3.10    | 2         | 0.04%   |
| 6.5     | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3991      | 94.89%  |
| i686   | 214       | 5.09%   |
| armv7l | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1921      | 43.59%  |
| KDE5              | 856       | 19.42%  |
| Unknown           | 410       | 9.3%    |
| XFCE              | 404       | 9.17%   |
| X-Cinnamon        | 276       | 6.26%   |
| MATE              | 115       | 2.61%   |
| LXQt              | 75        | 1.7%    |
| KDE               | 69        | 1.57%   |
| KDE4              | 50        | 1.13%   |
| Pantheon          | 41        | 0.93%   |
| Cinnamon          | 30        | 0.68%   |
| LXDE              | 27        | 0.61%   |
| Unity             | 23        | 0.52%   |
| Budgie            | 23        | 0.52%   |
| i3                | 16        | 0.36%   |
| GNOME Flashback   | 16        | 0.36%   |
| GNOME Classic     | 8         | 0.18%   |
| sway              | 7         | 0.16%   |
| Deepin            | 6         | 0.14%   |
| bspwm             | 5         | 0.11%   |
| Hyprland          | 4         | 0.09%   |
| DWM               | 4         | 0.09%   |
| xubuntu           | 2         | 0.05%   |
| Trinity           | 2         | 0.05%   |
| qtile             | 2         | 0.05%   |
| openbox           | 2         | 0.05%   |
| Enlightenment     | 2         | 0.05%   |
| awesome           | 2         | 0.05%   |
| ubuntu:pika:GNOME | 1         | 0.02%   |
| ubuntu            | 1         | 0.02%   |
| pika:GNOME        | 1         | 0.02%   |
| none+i3           | 1         | 0.02%   |
| none+bspwm        | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| gamescope         | 1         | 0.02%   |
| Cutefish          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3246      | 74.5%   |
| Wayland | 859       | 19.72%  |
| Unknown | 210       | 4.82%   |
| Tty     | 42        | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1863      | 42.38%  |
| SDDM    | 801       | 18.22%  |
| GDM3    | 571       | 12.99%  |
| GDM     | 522       | 11.87%  |
| LightDM | 471       | 10.71%  |
| TDM     | 96        | 2.18%   |
| KDM     | 51        | 1.16%   |
| SLiM    | 7         | 0.16%   |
| XDM     | 6         | 0.14%   |
| LXDM    | 3         | 0.07%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| it_IT        | 2680      | 61.82%  |
| en_US        | 952       | 21.96%  |
| Unknown      | 434       | 10.01%  |
| en_GB        | 103       | 2.38%   |
| C            | 84        | 1.94%   |
| de_DE        | 16        | 0.37%   |
| fr_FR        | 9         | 0.21%   |
| de_IT        | 9         | 0.21%   |
| es_ES        | 8         | 0.18%   |
| ru_RU        | 5         | 0.12%   |
| POSIX        | 5         | 0.12%   |
| en_AG        | 4         | 0.09%   |
| it_IT@euro   | 3         | 0.07%   |
| en_AU        | 3         | 0.07%   |
| en_US.UTF8   | 2         | 0.05%   |
| en_IE        | 2         | 0.05%   |
| ro_RO        | 1         | 0.02%   |
| pt_BR        | 1         | 0.02%   |
| pl_PL        | 1         | 0.02%   |
| it_IT.UTF -8 | 1         | 0.02%   |
| it_CH        | 1         | 0.02%   |
| fur_IT       | 1         | 0.02%   |
| fr_BE        | 1         | 0.02%   |
| es_US        | 1         | 0.02%   |
| en_US@euro   | 1         | 0.02%   |
| en_US.utf-8  | 1         | 0.02%   |
| en_IN        | 1         | 0.02%   |
| en_DK        | 1         | 0.02%   |
| de_CH        | 1         | 0.02%   |
| de_AT        | 1         | 0.02%   |
| C.UTF8       | 1         | 0.02%   |
| bg_BG        | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2291      | 53.37%  |
| BIOS | 2002      | 46.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3238      | 74.76%  |
| Overlay  | 423       | 9.77%   |
| Btrfs    | 396       | 9.14%   |
| Unknown  | 103       | 2.38%   |
| Tmpfs    | 82        | 1.89%   |
| Xfs      | 34        | 0.79%   |
| Zfs      | 26        | 0.6%    |
| Ext2     | 12        | 0.28%   |
| F2fs     | 8         | 0.18%   |
| Ext3     | 5         | 0.12%   |
| XXX4     | 2         | 0.05%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2029      | 46.97%  |
| GPT     | 1831      | 42.38%  |
| MBR     | 460       | 10.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3742      | 87.39%  |
| Yes       | 540       | 12.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2846      | 66.29%  |
| Yes       | 1447      | 33.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 963       | 22.92%  |
| Lenovo              | 682       | 16.23%  |
| ASUSTek Computer    | 636       | 15.14%  |
| Acer                | 472       | 11.23%  |
| Dell                | 438       | 10.42%  |
| HUAWEI              | 107       | 2.55%   |
| Toshiba             | 106       | 2.52%   |
| Apple               | 103       | 2.45%   |
| Sony                | 92        | 2.19%   |
| MSI                 | 88        | 2.09%   |
| Samsung Electronics | 74        | 1.76%   |
| Fujitsu             | 40        | 0.95%   |
| Unknown             | 35        | 0.83%   |
| Mediacom            | 33        | 0.79%   |
| Packard Bell        | 31        | 0.74%   |
| Notebook            | 24        | 0.57%   |
| Chuwi               | 23        | 0.55%   |
| Teclast             | 21        | 0.5%    |
| Fujitsu Siemens     | 19        | 0.45%   |
| Timi                | 18        | 0.43%   |
| Microtech           | 18        | 0.43%   |
| TUXEDO              | 14        | 0.33%   |
| PC Specialist       | 14        | 0.33%   |
| Valve               | 12        | 0.29%   |
| SANTECH             | 9         | 0.21%   |
| Jumper              | 9         | 0.21%   |
| Google              | 8         | 0.19%   |
| TrekStor            | 7         | 0.17%   |
| Olivetti            | 7         | 0.17%   |
| eMachines           | 7         | 0.17%   |
| LG Electronics      | 5         | 0.12%   |
| Alienware           | 5         | 0.12%   |
| SiComputer          | 4         | 0.1%    |
| YASHI               | 3         | 0.07%   |
| TELECOMITALIA       | 3         | 0.07%   |
| System76            | 3         | 0.07%   |
| Razer               | 3         | 0.07%   |
| Onda TLC            | 3         | 0.07%   |
| Olidata             | 3         | 0.07%   |
| Intel               | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Pavilion dv6                       | 55        | 1.31%   |
| Unknown                               | 50        | 1.19%   |
| HP Notebook                           | 42        | 1%      |
| HP Pavilion 15                        | 28        | 0.67%   |
| HP Pavilion g6                        | 23        | 0.55%   |
| HP 255 G8 Notebook PC                 | 23        | 0.55%   |
| HUAWEI NBLK-WAX9X                     | 20        | 0.48%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.4%    |
| HP 15                                 | 16        | 0.38%   |
| Dell XPS 15 7590                      | 14        | 0.33%   |
| HP ENVY 15                            | 13        | 0.31%   |
| HP 255 G7 Notebook PC                 | 13        | 0.31%   |
| Valve Jupiter                         | 12        | 0.29%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 12        | 0.29%   |
| HUAWEI KLVL-WXX9                      | 12        | 0.29%   |
| HP Pavilion x2 Detachable             | 12        | 0.29%   |
| HP G62                                | 12        | 0.29%   |
| HP 250 G6 Notebook PC                 | 12        | 0.29%   |
| Apple MacBook4,1                      | 12        | 0.29%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.26%   |
| HP 255 G6 Notebook PC                 | 11        | 0.26%   |
| Dell XPS 15 9570                      | 11        | 0.26%   |
| Acer Aspire 5750G                     | 11        | 0.26%   |
| HP Pavilion dv7                       | 10        | 0.24%   |
| HP Laptop 15s-eq2xxx                  | 10        | 0.24%   |
| Dell XPS 15 9560                      | 10        | 0.24%   |
| Acer Aspire 5920G                     | 10        | 0.24%   |
| Microtech ebookPro                    | 9         | 0.21%   |
| Jumper EZbook                         | 9         | 0.21%   |
| HUAWEI BOD-WXX9                       | 9         | 0.21%   |
| HP EliteBook 8440p                    | 9         | 0.21%   |
| HP Compaq 6730s                       | 9         | 0.21%   |
| HP 250 G3                             | 9         | 0.21%   |
| Dell Inspiron 5570                    | 9         | 0.21%   |
| ASUS N53SV                            | 9         | 0.21%   |
| Acer Aspire A515-51G                  | 9         | 0.21%   |
| Acer Aspire A515-45                   | 9         | 0.21%   |
| Samsung RC530/RC730                   | 8         | 0.19%   |
| Lenovo V145-15AST 81MT                | 8         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 8         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 326       | 7.76%   |
| Acer Aspire           | 315       | 7.5%    |
| HP Pavilion           | 252       | 6%      |
| Lenovo IdeaPad        | 175       | 4.16%   |
| Dell Latitude         | 166       | 3.95%   |
| HP EliteBook          | 112       | 2.67%   |
| Dell XPS              | 101       | 2.4%    |
| ASUS VivoBook         | 97        | 2.31%   |
| HP Laptop             | 94        | 2.24%   |
| Toshiba Satellite     | 91        | 2.17%   |
| HP ProBook            | 88        | 2.09%   |
| Dell Inspiron         | 81        | 1.93%   |
| HP Compaq             | 70        | 1.67%   |
| HP 255                | 65        | 1.55%   |
| HP 250                | 58        | 1.38%   |
| Unknown               | 50        | 1.19%   |
| HP Notebook           | 42        | 1%      |
| Fujitsu LIFEBOOK      | 38        | 0.9%    |
| Acer Swift            | 37        | 0.88%   |
| Acer TravelMate       | 36        | 0.86%   |
| Dell Precision        | 35        | 0.83%   |
| Acer Extensa          | 34        | 0.81%   |
| Dell Vostro           | 33        | 0.79%   |
| Lenovo ThinkBook      | 29        | 0.69%   |
| Packard Bell EasyNote | 24        | 0.57%   |
| HP ENVY               | 24        | 0.57%   |
| Mediacom SmartBook    | 21        | 0.5%    |
| ASUS ROG              | 21        | 0.5%    |
| HUAWEI NBLK-WAX9X     | 20        | 0.48%   |
| Apple MacBookPro11    | 18        | 0.43%   |
| MSI Modern            | 16        | 0.38%   |
| HP 15                 | 16        | 0.38%   |
| HP ZBook              | 15        | 0.36%   |
| HP Presario           | 15        | 0.36%   |
| HP OMEN               | 15        | 0.36%   |
| Lenovo Legion         | 14        | 0.33%   |
| ASUS Zenbook          | 14        | 0.33%   |
| Acer Nitro            | 14        | 0.33%   |
| ASUS ASUS             | 13        | 0.31%   |
| Valve Jupiter         | 12        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 370       | 8.81%   |
| 2019    | 359       | 8.54%   |
| 2021    | 351       | 8.35%   |
| 2018    | 325       | 7.73%   |
| 2013    | 283       | 6.73%   |
| 2017    | 282       | 6.71%   |
| 2012    | 248       | 5.9%    |
| 2016    | 246       | 5.85%   |
| 2011    | 246       | 5.85%   |
| 2008    | 245       | 5.83%   |
| 2010    | 240       | 5.71%   |
| 2015    | 239       | 5.69%   |
| 2014    | 229       | 5.45%   |
| 2009    | 189       | 4.5%    |
| 2007    | 125       | 2.97%   |
| 2022    | 115       | 2.74%   |
| 2006    | 64        | 1.52%   |
| 2005    | 23        | 0.55%   |
| 2023    | 12        | 0.29%   |
| Unknown | 6         | 0.14%   |
| 2004    | 3         | 0.07%   |
| 2003    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4202      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3829      | 90.01%  |
| Enabled  | 425       | 9.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4186      | 99.62%  |
| Yes  | 16        | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1190      | 27.94%  |
| 3.01-4.0    | 1042      | 24.47%  |
| 16.01-24.0  | 686       | 16.11%  |
| 8.01-16.0   | 671       | 15.75%  |
| 1.01-2.0    | 271       | 6.36%   |
| 32.01-64.0  | 207       | 4.86%   |
| 2.01-3.0    | 90        | 2.11%   |
| 0.51-1.0    | 45        | 1.06%   |
| 24.01-32.0  | 30        | 0.7%    |
| 64.01-256.0 | 23        | 0.54%   |
| 0.01-0.5    | 4         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1777      | 37.92%  |
| 2.01-3.0   | 1145      | 24.43%  |
| 4.01-8.0   | 604       | 12.89%  |
| 3.01-4.0   | 573       | 12.23%  |
| 0.51-1.0   | 376       | 8.02%   |
| 8.01-16.0  | 149       | 3.18%   |
| 0.01-0.5   | 48        | 1.02%   |
| 16.01-24.0 | 10        | 0.21%   |
| 24.01-32.0 | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3199      | 74.71%  |
| 2      | 935       | 21.84%  |
| 3      | 98        | 2.29%   |
| 0      | 34        | 0.79%   |
| 4      | 11        | 0.26%   |
| 5      | 3         | 0.07%   |
| 6      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2454      | 58.14%  |
| Yes       | 1767      | 41.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3343      | 79.22%  |
| No        | 877       | 20.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4116      | 97.86%  |
| No        | 90        | 2.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3111      | 73.03%  |
| No        | 1149      | 26.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 4202      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 646       | 13.44%  |
| Rome                | 487       | 10.14%  |
| Turin               | 158       | 3.29%   |
| Florence            | 89        | 1.85%   |
| Naples              | 84        | 1.75%   |
| Bologna             | 82        | 1.71%   |
| Rho                 | 76        | 1.58%   |
| Genoa               | 65        | 1.35%   |
| Milano              | 61        | 1.27%   |
| Padova              | 59        | 1.23%   |
| Palermo             | 54        | 1.12%   |
| Verona              | 48        | 1%      |
| Bari                | 46        | 0.96%   |
| Catania             | 44        | 0.92%   |
| Brescia             | 35        | 0.73%   |
| Trieste             | 32        | 0.67%   |
| Parma               | 32        | 0.67%   |
| Bergamo             | 29        | 0.6%    |
| Venice              | 28        | 0.58%   |
| Pisa                | 28        | 0.58%   |
| Monza               | 22        | 0.46%   |
| Modena              | 22        | 0.46%   |
| Casalecchio di Reno | 22        | 0.46%   |
| Bolzano             | 22        | 0.46%   |
| Trento              | 20        | 0.42%   |
| Perugia             | 20        | 0.42%   |
| Reggio Emilia       | 19        | 0.4%    |
| Cagliari            | 19        | 0.4%    |
| Seregno             | 18        | 0.37%   |
| Salerno             | 18        | 0.37%   |
| Sesto San Giovanni  | 17        | 0.35%   |
| Udine               | 16        | 0.33%   |
| Taranto             | 16        | 0.33%   |
| Vicenza             | 15        | 0.31%   |
| Reggio Calabria     | 15        | 0.31%   |
| Pescara             | 15        | 0.31%   |
| Legnano             | 14        | 0.29%   |
| Mestre              | 13        | 0.27%   |
| Forlì              | 13        | 0.27%   |
| Rimini              | 12        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 931       | 1254   | 18.01%  |
| WDC                         | 500       | 631    | 9.67%   |
| Seagate                     | 471       | 574    | 9.11%   |
| Toshiba                     | 342       | 447    | 6.62%   |
| Unknown                     | 322       | 442    | 6.23%   |
| SanDisk                     | 320       | 433    | 6.19%   |
| Kingston                    | 300       | 355    | 5.8%    |
| Crucial                     | 294       | 346    | 5.69%   |
| Hitachi                     | 231       | 282    | 4.47%   |
| SK hynix                    | 200       | 247    | 3.87%   |
| HGST                        | 182       | 239    | 3.52%   |
| Micron Technology           | 138       | 172    | 2.67%   |
| Intel                       | 127       | 165    | 2.46%   |
| KIOXIA                      | 63        | 78     | 1.22%   |
| Fujitsu                     | 46        | 54     | 0.89%   |
| China                       | 44        | 50     | 0.85%   |
| Phison                      | 41        | 49     | 0.79%   |
| Apple                       | 35        | 38     | 0.68%   |
| SPCC                        | 31        | 38     | 0.6%    |
| LITEON                      | 29        | 37     | 0.56%   |
| Intenso                     | 25        | 26     | 0.48%   |
| Transcend                   | 24        | 31     | 0.46%   |
| JMicron Technology          | 24        | 27     | 0.46%   |
| Phison Electronics          | 21        | 26     | 0.41%   |
| A-DATA Technology           | 19        | 23     | 0.37%   |
| Netac                       | 18        | 19     | 0.35%   |
| Teclast                     | 17        | 22     | 0.33%   |
| Kingston Technology Company | 17        | 19     | 0.33%   |
| Unknown                     | 17        | 23     | 0.33%   |
| KingDian                    | 16        | 21     | 0.31%   |
| Micron/Crucial Technology   | 15        | 20     | 0.29%   |
| PNY                         | 13        | 15     | 0.25%   |
| SABRENT                     | 12        | 12     | 0.23%   |
| Silicon Motion              | 11        | 15     | 0.21%   |
| Drevo                       | 11        | 12     | 0.21%   |
| SSSTC                       | 9         | 9      | 0.17%   |
| Patriot                     | 9         | 13     | 0.17%   |
| LITEONIT                    | 9         | 20     | 0.17%   |
| Corsair                     | 9         | 10     | 0.17%   |
| Microtech                   | 8         | 18     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 82        | 1.53%   |
| Crucial CT500MX500SSD1 500GB                          | 74        | 1.38%   |
| Unknown MMC Card  32GB                                | 69        | 1.29%   |
| Samsung SSD 860 EVO 500GB                             | 65        | 1.21%   |
| Toshiba MQ01ABF050 500GB                              | 61        | 1.14%   |
| HGST HTS545050A7E680 500GB                            | 51        | 0.95%   |
| Seagate ST500LT012-1DG142 500GB                       | 50        | 0.93%   |
| Samsung SSD 850 EVO 250GB                             | 50        | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 48        | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB                        | 47        | 0.88%   |
| HGST HTS721010A9E630 1TB                              | 46        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 44        | 0.82%   |
| Samsung SSD 850 EVO 500GB                             | 41        | 0.76%   |
| Unknown MMC Card  64GB                                | 39        | 0.73%   |
| Crucial CT240BX500SSD1 240GB                          | 37        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                       | 35        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                          | 32        | 0.6%    |
| Toshiba MQ01ABD100 1TB                                | 30        | 0.56%   |
| Toshiba MQ04ABF100 1TB                                | 29        | 0.54%   |
| Seagate ST9500325AS 500GB                             | 28        | 0.52%   |
| SanDisk NVMe SSD Drive 512GB                          | 28        | 0.52%   |
| Crucial CT480BX500SSD1 480GB                          | 28        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                           | 26        | 0.48%   |
| SanDisk SSD PLUS 240GB                                | 25        | 0.47%   |
| Samsung SSD 860 EVO 250GB                             | 25        | 0.47%   |
| Samsung SSD 860 EVO 1TB                               | 25        | 0.47%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 22        | 0.41%   |
| Unknown MMC Card  128GB                               | 21        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB                          | 21        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                       | 21        | 0.39%   |
| Hitachi HTS545050A7E380 500GB                         | 21        | 0.39%   |
| HGST HTS541010A9E680 1TB                              | 21        | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 20        | 0.37%   |
| Unknown NCard  32GB                                   | 20        | 0.37%   |
| Unknown MMC Card  16GB                                | 19        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                         | 19        | 0.35%   |
| Seagate M3 Portable 1TB                               | 19        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 19        | 0.35%   |
| Samsung MZVLQ512HALU-000H1 512GB                      | 19        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                      | 19        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 449       | 542    | 28.27%  |
| WDC                 | 345       | 441    | 21.73%  |
| Toshiba             | 237       | 288    | 14.92%  |
| Hitachi             | 231       | 282    | 14.55%  |
| HGST                | 182       | 239    | 11.46%  |
| Fujitsu             | 46        | 54     | 2.9%    |
| Samsung Electronics | 44        | 55     | 2.77%   |
| Unknown             | 20        | 21     | 1.26%   |
| SABRENT             | 12        | 12     | 0.76%   |
| External            | 5         | 6      | 0.31%   |
| ASMT                | 3         | 3      | 0.19%   |
| SSK                 | 2         | 2      | 0.13%   |
| IBM/Hitachi         | 2         | 3      | 0.13%   |
| HGST HTS            | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.06%   |
| StoreJet            | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| Generic-            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| Apple               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 466       | 614    | 26.24%  |
| Crucial             | 274       | 325    | 15.43%  |
| Kingston            | 228       | 268    | 12.84%  |
| SanDisk             | 175       | 226    | 9.85%   |
| Micron Technology   | 58        | 75     | 3.27%   |
| WDC                 | 49        | 63     | 2.76%   |
| SK hynix            | 48        | 53     | 2.7%    |
| China               | 43        | 49     | 2.42%   |
| Toshiba             | 27        | 42     | 1.52%   |
| SPCC                | 27        | 33     | 1.52%   |
| Apple               | 27        | 29     | 1.52%   |
| LITEON              | 25        | 28     | 1.41%   |
| Transcend           | 24        | 31     | 1.35%   |
| Intel               | 24        | 31     | 1.35%   |
| Intenso             | 21        | 21     | 1.18%   |
| Teclast             | 17        | 22     | 0.96%   |
| Netac               | 17        | 18     | 0.96%   |
| KingDian            | 16        | 21     | 0.9%    |
| A-DATA Technology   | 14        | 16     | 0.79%   |
| PNY                 | 12        | 13     | 0.68%   |
| JMicron Technology  | 12        | 13     | 0.68%   |
| Drevo               | 11        | 12     | 0.62%   |
| Patriot             | 9         | 13     | 0.51%   |
| LITEONIT            | 9         | 20     | 0.51%   |
| Corsair             | 9         | 10     | 0.51%   |
| Unknown             | 9         | 15     | 0.51%   |
| Microtech           | 8         | 18     | 0.45%   |
| GOODRAM             | 7         | 8      | 0.39%   |
| Dogfish             | 7         | 8      | 0.39%   |
| Verbatim            | 5         | 10     | 0.28%   |
| TCSUNBOW            | 5         | 5      | 0.28%   |
| KingSpec            | 5         | 6      | 0.28%   |
| FORESEE             | 5         | 5      | 0.28%   |
| Emtec               | 5         | 5      | 0.28%   |
| BAITITON            | 5         | 9      | 0.28%   |
| Team                | 4         | 4      | 0.23%   |
| OCZ                 | 4         | 4      | 0.23%   |
| Leven               | 4         | 4      | 0.23%   |
| Hewlett-Packard     | 4         | 5      | 0.23%   |
| BHT                 | 4         | 4      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1673      | 2213   | 34%     |
| HDD     | 1535      | 1961   | 31.19%  |
| NVMe    | 1316      | 1846   | 26.74%  |
| MMC     | 316       | 449    | 6.42%   |
| Unknown | 81        | 96     | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2891      | 4047   | 61.35%  |
| NVMe | 1315      | 1842   | 27.91%  |
| MMC  | 316       | 449    | 6.71%   |
| SAS  | 190       | 227    | 4.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2367      | 3161   | 75.12%  |
| 0.51-1.0   | 712       | 918    | 22.6%   |
| 1.01-2.0   | 61        | 81     | 1.94%   |
| 4.01-10.0  | 6         | 9      | 0.19%   |
| 3.01-4.0   | 5         | 5      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1316      | 29.53%  |
| 251-500        | 1145      | 25.69%  |
| 501-1000       | 499       | 11.2%   |
| 1-20           | 467       | 10.48%  |
| 51-100         | 356       | 7.99%   |
| 21-50          | 227       | 5.09%   |
| 1001-2000      | 215       | 4.82%   |
| Unknown        | 101       | 2.27%   |
| More than 3000 | 66        | 1.48%   |
| 2001-3000      | 65        | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2008      | 43.3%   |
| 21-50          | 744       | 16.04%  |
| 101-250        | 631       | 13.61%  |
| 51-100         | 559       | 12.06%  |
| 251-500        | 333       | 7.18%   |
| 501-1000       | 166       | 3.58%   |
| Unknown        | 101       | 2.18%   |
| 1001-2000      | 58        | 1.25%   |
| More than 3000 | 19        | 0.41%   |
| 2001-3000      | 18        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 15        | 19     | 5.42%   |
| Seagate ST9500325AS 500GB                      | 7         | 7      | 2.53%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 9      | 2.53%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 6      | 2.17%   |
| Hitachi HTS725050A9A364 500GB                  | 6         | 7      | 2.17%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 1.81%   |
| Toshiba MQ01ABF050 500GB                       | 5         | 5      | 1.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 1.81%   |
| Hitachi HTS545050A7E380 500GB                  | 5         | 5      | 1.81%   |
| HGST HTS721010A9E630 1TB                       | 5         | 5      | 1.81%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 4         | 4      | 1.44%   |
| Hitachi HTS547550A9E384 500GB                  | 4         | 4      | 1.44%   |
| HGST HTS725050A7E630 500GB                     | 4         | 5      | 1.44%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.08%   |
| Toshiba MK5065GSX 500GB                        | 3         | 3      | 1.08%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 1.08%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.08%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 1.08%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 3         | 3      | 1.08%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 1.08%   |
| HGST HTS541075A9E680 752GB                     | 3         | 6      | 1.08%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 2         | 2      | 0.72%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 2         | 2      | 0.72%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.72%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.72%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.72%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 0.72%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.72%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.72%   |
| Samsung Electronics HM160HC 160GB              | 2         | 2      | 0.72%   |
| Kingston SA400S37240G 240GB SSD                | 2         | 2      | 0.72%   |
| Hitachi HTS547575A9E384 752GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.72%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 59        | 62     | 21.3%   |
| Hitachi                     | 48        | 50     | 17.33%  |
| WDC                         | 32        | 38     | 11.55%  |
| HGST                        | 32        | 40     | 11.55%  |
| Toshiba                     | 31        | 32     | 11.19%  |
| SK hynix                    | 12        | 14     | 4.33%   |
| Samsung Electronics         | 12        | 12     | 4.33%   |
| Crucial                     | 9         | 9      | 3.25%   |
| Micron Technology           | 7         | 7      | 2.53%   |
| Intel                       | 6         | 10     | 2.17%   |
| Kingston                    | 5         | 5      | 1.81%   |
| Fujitsu                     | 5         | 5      | 1.81%   |
| SanDisk                     | 3         | 3      | 1.08%   |
| Drevo                       | 2         | 2      | 0.72%   |
| Yangtze Memory Technologies | 1         | 1      | 0.36%   |
| WINTEC                      | 1         | 1      | 0.36%   |
| WDC WDS2                    | 1         | 1      | 0.36%   |
| Unknown                     | 1         | 1      | 0.36%   |
| Transcend                   | 1         | 2      | 0.36%   |
| Teclast                     | 1         | 1      | 0.36%   |
| TCSUNBOW                    | 1         | 1      | 0.36%   |
| SSSTC                       | 1         | 1      | 0.36%   |
| NGFF                        | 1         | 1      | 0.36%   |
| LITEON                      | 1         | 1      | 0.36%   |
| KingSpec                    | 1         | 1      | 0.36%   |
| KingDian                    | 1         | 1      | 0.36%   |
| BAITITON                    | 1         | 3      | 0.36%   |
| A-DATA Technology           | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 62     | 28.23%  |
| Hitachi             | 48        | 50     | 22.97%  |
| HGST                | 32        | 40     | 15.31%  |
| WDC                 | 31        | 37     | 14.83%  |
| Toshiba             | 29        | 30     | 13.88%  |
| Fujitsu             | 5         | 5      | 2.39%   |
| Samsung Electronics | 4         | 4      | 1.91%   |
| Unknown             | 1         | 1      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 208       | 229    | 75.36%  |
| SSD  | 58        | 63     | 21.01%  |
| NVMe | 10        | 14     | 3.62%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 11.11%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 11.11%  |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB                        | 1         | 3      | 11.11%  |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 44.44%  |
| Seagate             | 2         | 4      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2451      | 3815   | 54.78%  |
| Works    | 1739      | 2433   | 38.87%  |
| Malfunc  | 275       | 306    | 6.15%   |
| Failed   | 9         | 11     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2947      | 60.73%  |
| AMD                              | 484       | 9.97%   |
| Samsung Electronics              | 464       | 9.56%   |
| SanDisk                          | 222       | 4.57%   |
| SK hynix                         | 143       | 2.95%   |
| Kingston Technology Company      | 88        | 1.81%   |
| Micron Technology                | 82        | 1.69%   |
| Toshiba America Info Systems     | 77        | 1.59%   |
| KIOXIA                           | 69        | 1.42%   |
| Phison Electronics               | 61        | 1.26%   |
| Nvidia                           | 51        | 1.05%   |
| Micron/Crucial Technology        | 34        | 0.7%    |
| Silicon Integrated Systems [SiS] | 26        | 0.54%   |
| Union Memory (Shenzhen)          | 13        | 0.27%   |
| Solid State Storage Technology   | 13        | 0.27%   |
| Silicon Motion                   | 13        | 0.27%   |
| ADATA Technology                 | 8         | 0.16%   |
| VIA Technologies                 | 7         | 0.14%   |
| Lite-On Technology               | 7         | 0.14%   |
| Lenovo                           | 7         | 0.14%   |
| Apple                            | 7         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.12%   |
| Yangtze Memory Technologies      | 4         | 0.08%   |
| Silicon Image                    | 3         | 0.06%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| ASMedia Technology               | 3         | 0.06%   |
| Realtek Semiconductor            | 2         | 0.04%   |
| JMicron Technology               | 2         | 0.04%   |
| Solidigm                         | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Marvell Technology Group         | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 398       | 7.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 344       | 6.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 271       | 5.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 242       | 4.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 221       | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 219       | 4.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 205       | 3.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 165       | 3.14%   |
| Samsung NVMe SSD Controller 980                                                  | 136       | 2.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 128       | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                              | 125       | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 113       | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 110       | 2.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 109       | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 104       | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 101       | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 85        | 1.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 79        | 1.5%    |
| Intel Comet Lake SATA AHCI Controller                                            | 66        | 1.26%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 62        | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 58        | 1.1%    |
| Intel SSD 660P Series                                                            | 56        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 55        | 1.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 53        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 49        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 48        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 48        | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 46        | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 44        | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 43        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 42        | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 41        | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 41        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 40        | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 40        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 37        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 36        | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 34        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 32        | 0.61%   |
| Phison E12 NVMe Controller                                                       | 31        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2953      | 58.45%  |
| NVMe | 1323      | 26.19%  |
| IDE  | 404       | 8%      |
| RAID | 372       | 7.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3457      | 82.27%  |
| AMD          | 741       | 17.63%  |
| CentaurHauls | 2         | 0.05%   |
| ARM          | 1         | 0.02%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 87        | 2.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 72        | 1.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 61        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 58        | 1.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 54        | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 52        | 1.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 50        | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 49        | 1.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 48        | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 1.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 43        | 1.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 43        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 0.98%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 40        | 0.95%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 38        | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 37        | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 0.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 33        | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 30        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 29        | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 27        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 27        | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.62%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 26        | 0.62%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.62%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 25        | 0.59%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 25        | 0.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 24        | 0.57%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 24        | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 24        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1019      | 24.24%  |
| Intel Core i5           | 811       | 19.3%   |
| Other                   | 330       | 7.85%   |
| Intel Core 2 Duo        | 297       | 7.07%   |
| Intel Core i3           | 289       | 6.88%   |
| Intel Celeron           | 262       | 6.23%   |
| Intel Atom              | 174       | 4.14%   |
| AMD Ryzen 7             | 160       | 3.81%   |
| AMD Ryzen 5             | 155       | 3.69%   |
| Intel Pentium           | 51        | 1.21%   |
| AMD E1                  | 48        | 1.14%   |
| Intel Pentium Dual-Core | 45        | 1.07%   |
| Intel Pentium Dual      | 37        | 0.88%   |
| Intel Genuine           | 35        | 0.83%   |
| Intel Core 2            | 33        | 0.79%   |
| AMD A4                  | 33        | 0.79%   |
| AMD A10                 | 32        | 0.76%   |
| AMD A8                  | 30        | 0.71%   |
| AMD A6                  | 30        | 0.71%   |
| AMD Ryzen 3             | 26        | 0.62%   |
| AMD Ryzen 9             | 23        | 0.55%   |
| AMD E2                  | 23        | 0.55%   |
| Intel Core i9           | 22        | 0.52%   |
| Intel Pentium Silver    | 16        | 0.38%   |
| Intel Pentium M         | 16        | 0.38%   |
| AMD Ryzen 7 PRO         | 16        | 0.38%   |
| AMD Turion 64 X2 Mobile | 15        | 0.36%   |
| Intel Celeron M         | 14        | 0.33%   |
| AMD Sempron             | 13        | 0.31%   |
| Intel Celeron Dual-Core | 11        | 0.26%   |
| AMD Ryzen 5 PRO         | 11        | 0.26%   |
| AMD E                   | 10        | 0.24%   |
| AMD Mobile Sempron      | 9         | 0.21%   |
| AMD A12                 | 9         | 0.21%   |
| Intel Core m3           | 8         | 0.19%   |
| AMD Athlon              | 8         | 0.19%   |
| AMD Athlon II           | 7         | 0.17%   |
| Intel Core M            | 6         | 0.14%   |
| Intel Core Duo          | 5         | 0.12%   |
| AMD C-60                | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2125      | 50.52%  |
| 4       | 1382      | 32.86%  |
| 6       | 227       | 5.4%    |
| 8       | 219       | 5.21%   |
| 1       | 174       | 4.14%   |
| 14      | 35        | 0.83%   |
| 10      | 28        | 0.67%   |
| 12      | 13        | 0.31%   |
| 16      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4202      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2934      | 69.67%  |
| 1       | 1274      | 30.25%  |
| 4       | 2         | 0.05%   |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4076      | 96.89%  |
| 32-bit         | 102       | 2.42%   |
| Unknown        | 29        | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1041      | 23.74%  |
| 0x306a9    | 214       | 4.88%   |
| 0x206a7    | 211       | 4.81%   |
| 0x1067a    | 146       | 3.33%   |
| 0x40651    | 145       | 3.31%   |
| 0x806ea    | 141       | 3.22%   |
| 0x806ec    | 133       | 3.03%   |
| 0x806c1    | 133       | 3.03%   |
| 0x406e3    | 128       | 2.92%   |
| 0x806e9    | 104       | 2.37%   |
| 0x6fd      | 96        | 2.19%   |
| 0x20655    | 93        | 2.12%   |
| 0x906ea    | 91        | 2.08%   |
| 0x306c3    | 88        | 2.01%   |
| 0x306d4    | 83        | 1.89%   |
| 0x08108109 | 74        | 1.69%   |
| 0x10676    | 72        | 1.64%   |
| 0x706e5    | 58        | 1.32%   |
| 0x406c3    | 57        | 1.3%    |
| 0x806eb    | 50        | 1.14%   |
| 0x906e9    | 48        | 1.09%   |
| 0x30678    | 48        | 1.09%   |
| 0x0a50000c | 48        | 1.09%   |
| 0x20652    | 47        | 1.07%   |
| 0x08608103 | 47        | 1.07%   |
| 0xa0652    | 44        | 1%      |
| 0x06006705 | 44        | 1%      |
| 0x706a8    | 40        | 0.91%   |
| 0x406c4    | 40        | 0.91%   |
| 0x106ca    | 40        | 0.91%   |
| 0x706a1    | 38        | 0.87%   |
| 0x506e3    | 32        | 0.73%   |
| 0x506c9    | 32        | 0.73%   |
| 0x07030105 | 31        | 0.71%   |
| 0x08600106 | 30        | 0.68%   |
| 0x08600104 | 30        | 0.68%   |
| 0x906a3    | 29        | 0.66%   |
| 0x106c2    | 27        | 0.62%   |
| 0x08108102 | 27        | 0.62%   |
| 0x0700010f | 25        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 728       | 17.31%  |
| Haswell          | 311       | 7.4%    |
| IvyBridge        | 274       | 6.52%   |
| Penryn           | 272       | 6.47%   |
| SandyBridge      | 260       | 6.18%   |
| Skylake          | 210       | 4.99%   |
| Core             | 195       | 4.64%   |
| TigerLake        | 190       | 4.52%   |
| Silvermont       | 182       | 4.33%   |
| Westmere         | 165       | 3.92%   |
| Unknown          | 146       | 3.47%   |
| Zen+             | 118       | 2.81%   |
| Broadwell        | 116       | 2.76%   |
| Goldmont plus    | 105       | 2.5%    |
| Excavator        | 98        | 2.33%   |
| IceLake          | 87        | 2.07%   |
| Bonnell          | 83        | 1.97%   |
| Zen 2            | 82        | 1.95%   |
| Zen 3            | 77        | 1.83%   |
| CometLake        | 65        | 1.55%   |
| P6               | 59        | 1.4%    |
| Alderlake Hybrid | 53        | 1.26%   |
| Puma             | 43        | 1.02%   |
| Jaguar           | 42        | 1%      |
| Goldmont         | 42        | 1%      |
| K8 Hammer        | 38        | 0.9%    |
| Bobcat           | 32        | 0.76%   |
| Zen              | 26        | 0.62%   |
| K10              | 21        | 0.5%    |
| Nehalem          | 20        | 0.48%   |
| K8 & K10 hybrid  | 19        | 0.45%   |
| K10 Llano        | 15        | 0.36%   |
| Steamroller      | 13        | 0.31%   |
| Piledriver       | 9         | 0.21%   |
| Tremont          | 5         | 0.12%   |
| NetBurst         | 4         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3041      | 56.77%  |
| Nvidia                           | 1224      | 22.85%  |
| AMD                              | 1070      | 19.97%  |
| Silicon Integrated Systems [SiS] | 16        | 0.3%    |
| VIA Technologies                 | 5         | 0.09%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 256       | 4.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 228       | 4.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 182       | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 176       | 3.14%   |
| Intel UHD Graphics 620                                                                   | 175       | 3.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 153       | 2.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 148       | 2.64%   |
| Intel HD Graphics 620                                                                    | 122       | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 121       | 2.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 119       | 2.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 117       | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 116       | 2.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 110       | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 107       | 1.91%   |
| Intel HD Graphics 5500                                                                   | 97        | 1.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 96        | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 89        | 1.59%   |
| AMD Renoir                                                                               | 80        | 1.43%   |
| AMD Lucienne                                                                             | 80        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 76        | 1.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 76        | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 70        | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 66        | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 65        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 65        | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 59        | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 59        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 55        | 0.98%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 49        | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 47        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 46        | 0.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 46        | 0.82%   |
| Intel HD Graphics 630                                                                    | 46        | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 43        | 0.77%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 42        | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 41        | 0.73%   |
| Intel HD Graphics 530                                                                    | 40        | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 39        | 0.7%    |
| Nvidia GM108M [GeForce MX130]                                                            | 37        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1927      | 45.73%  |
| Intel + Nvidia  | 906       | 21.5%   |
| 1 x AMD         | 727       | 17.25%  |
| 1 x Nvidia      | 253       | 6%      |
| Intel + AMD     | 185       | 4.39%   |
| 2 x AMD         | 100       | 2.37%   |
| AMD + Nvidia    | 62        | 1.47%   |
| 2 x Intel       | 23        | 0.55%   |
| 1 x SiS         | 16        | 0.38%   |
| Other           | 5         | 0.12%   |
| 1 x VIA         | 5         | 0.12%   |
| 2 x Nvidia      | 4         | 0.09%   |
| 1 x S3 Graphics | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3606      | 84.59%  |
| Proprietary | 547       | 12.83%  |
| Unknown     | 110       | 2.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2624      | 60.64%  |
| 0.01-0.5   | 602       | 13.91%  |
| 1.01-2.0   | 560       | 12.94%  |
| 0.51-1.0   | 287       | 6.63%   |
| 3.01-4.0   | 175       | 4.04%   |
| 5.01-6.0   | 45        | 1.04%   |
| 7.01-8.0   | 24        | 0.55%   |
| 2.01-3.0   | 9         | 0.21%   |
| 8.01-16.0  | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 873       | 19.13%  |
| Chimei Innolux          | 673       | 14.75%  |
| BOE                     | 611       | 13.39%  |
| LG Display              | 601       | 13.17%  |
| Samsung Electronics     | 517       | 11.33%  |
| Chi Mei Optoelectronics | 137       | 3%      |
| Sharp                   | 115       | 2.52%   |
| Apple                   | 100       | 2.19%   |
| Goldstar                | 80        | 1.75%   |
| Hewlett-Packard         | 74        | 1.62%   |
| Philips                 | 71        | 1.56%   |
| LG Philips              | 66        | 1.45%   |
| PANDA                   | 58        | 1.27%   |
| Lenovo                  | 56        | 1.23%   |
| Dell                    | 55        | 1.21%   |
| Ancor Communications    | 49        | 1.07%   |
| Acer                    | 38        | 0.83%   |
| HannStar                | 34        | 0.74%   |
| InfoVision              | 33        | 0.72%   |
| BenQ                    | 33        | 0.72%   |
| Sony                    | 26        | 0.57%   |
| CSO                     | 24        | 0.53%   |
| CPT                     | 23        | 0.5%    |
| AOC                     | 23        | 0.5%    |
| Toshiba                 | 14        | 0.31%   |
| Quanta Display          | 13        | 0.28%   |
| LGD                     | 13        | 0.28%   |
| ASUSTek Computer        | 10        | 0.22%   |
| Valve                   | 9         | 0.2%    |
| MSI                     | 9         | 0.2%    |
| TMX                     | 8         | 0.18%   |
| Seiko/Epson             | 8         | 0.18%   |
| InnoLux Display         | 6         | 0.13%   |
| Vestel Elektronik       | 5         | 0.11%   |
| Panasonic               | 5         | 0.11%   |
| Iiyama                  | 5         | 0.11%   |
| Eizo                    | 5         | 0.11%   |
| Tianma XM               | 4         | 0.09%   |
| Nvidia                  | 4         | 0.09%   |
| Fujitsu Siemens         | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 68        | 1.48%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 35        | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 34        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.72%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 32        | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 31        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 30        | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 28        | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 25        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 24        | 0.52%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 23        | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 22        | 0.48%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 22        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.43%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.43%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 18        | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 18        | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 18        | 0.39%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 17        | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 16        | 0.35%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 15        | 0.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 15        | 0.33%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 14        | 0.3%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 14        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 13        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 13        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1730      | 39.97%  |
| 1366x768 (WXGA)    | 1432      | 33.09%  |
| 1280x800 (WXGA)    | 297       | 6.86%   |
| 1600x900 (HD+)     | 149       | 3.44%   |
| 3840x2160 (4K)     | 140       | 3.23%   |
| 1440x900 (WXGA+)   | 72        | 1.66%   |
| 2560x1440 (QHD)    | 70        | 1.62%   |
| 1920x1200 (WUXGA)  | 69        | 1.59%   |
| 1024x600           | 61        | 1.41%   |
| 2560x1600          | 36        | 0.83%   |
| 2160x1440          | 36        | 0.83%   |
| 1680x1050 (WSXGA+) | 36        | 0.83%   |
| 2880x1800          | 25        | 0.58%   |
| 1280x1024 (SXGA)   | 23        | 0.53%   |
| 3840x2400          | 16        | 0.37%   |
| 2560x1080          | 14        | 0.32%   |
| 1360x768           | 14        | 0.32%   |
| 3440x1440          | 12        | 0.28%   |
| 800x1280           | 10        | 0.23%   |
| 3200x1800 (QHD+)   | 8         | 0.18%   |
| 3000x2000          | 8         | 0.18%   |
| 1024x768 (XGA)     | 7         | 0.16%   |
| 3072x1920          | 6         | 0.14%   |
| 2520x1680          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 2240x1400          | 4         | 0.09%   |
| 1920x540           | 4         | 0.09%   |
| Unknown            | 4         | 0.09%   |
| 3840x1600          | 3         | 0.07%   |
| 3840x1080          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 3456x2160          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1600x1200          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1280x720 (HD)      | 2         | 0.05%   |
| 3840x1200          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2318      | 50.83%  |
| 13      | 554       | 12.15%  |
| 14      | 404       | 8.86%   |
| 17      | 216       | 4.74%   |
| 24      | 139       | 3.05%   |
| 27      | 126       | 2.76%   |
| 12      | 125       | 2.74%   |
| 23      | 99        | 2.17%   |
| 21      | 83        | 1.82%   |
| 11      | 69        | 1.51%   |
| 10      | 69        | 1.51%   |
| Unknown | 61        | 1.34%   |
| 16      | 57        | 1.25%   |
| 19      | 30        | 0.66%   |
| 18      | 26        | 0.57%   |
| 34      | 19        | 0.42%   |
| 22      | 18        | 0.39%   |
| 31      | 17        | 0.37%   |
| 40      | 15        | 0.33%   |
| 54      | 14        | 0.31%   |
| 20      | 14        | 0.31%   |
| 84      | 11        | 0.24%   |
| 7       | 9         | 0.2%    |
| 32      | 7         | 0.15%   |
| 26      | 7         | 0.15%   |
| 25      | 7         | 0.15%   |
| 8       | 6         | 0.13%   |
| 72      | 5         | 0.11%   |
| 65      | 5         | 0.11%   |
| 35      | 4         | 0.09%   |
| 58      | 3         | 0.07%   |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 37      | 3         | 0.07%   |
| 142     | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 36      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |
| 49      | 1         | 0.02%   |
| 42      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2972      | 65.58%  |
| 201-300        | 565       | 12.47%  |
| 501-600        | 346       | 7.63%   |
| 351-400        | 282       | 6.22%   |
| 401-500        | 155       | 3.42%   |
| Unknown        | 61        | 1.35%   |
| 601-700        | 34        | 0.75%   |
| 1001-1500      | 30        | 0.66%   |
| 701-800        | 28        | 0.62%   |
| 801-900        | 23        | 0.51%   |
| 1501-2000      | 16        | 0.35%   |
| 1-100          | 10        | 0.22%   |
| 101-200        | 7         | 0.15%   |
| More than 2000 | 2         | 0.04%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3373      | 81.81%  |
| 16/10   | 549       | 13.32%  |
| 3/2     | 65        | 1.58%   |
| Unknown | 46        | 1.12%   |
| 21/9    | 28        | 0.68%   |
| 5/4     | 25        | 0.61%   |
| 4/3     | 17        | 0.41%   |
| 0.67    | 9         | 0.22%   |
| 6/5     | 4         | 0.1%    |
| 32/9    | 4         | 0.1%    |
| 1.00    | 2         | 0.05%   |
| 2.21    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2319      | 50.96%  |
| 81-90          | 733       | 16.11%  |
| 201-250        | 281       | 6.17%   |
| 71-80          | 222       | 4.88%   |
| 121-130        | 174       | 3.82%   |
| 301-350        | 132       | 2.9%    |
| 61-70          | 120       | 2.64%   |
| 41-50          | 70        | 1.54%   |
| 51-60          | 69        | 1.52%   |
| Unknown        | 61        | 1.34%   |
| 151-200        | 59        | 1.3%    |
| 351-500        | 48        | 1.05%   |
| 251-300        | 47        | 1.03%   |
| 111-120        | 45        | 0.99%   |
| More than 1000 | 43        | 0.94%   |
| 141-150        | 37        | 0.81%   |
| 131-140        | 31        | 0.68%   |
| 501-1000       | 27        | 0.59%   |
| 91-100         | 17        | 0.37%   |
| 1-40           | 16        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1689      | 37.67%  |
| 101-120       | 1441      | 32.14%  |
| 51-100        | 859       | 19.16%  |
| 161-240       | 294       | 6.56%   |
| More than 240 | 108       | 2.41%   |
| Unknown       | 61        | 1.36%   |
| 1-50          | 32        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3557      | 82.55%  |
| 2     | 580       | 13.46%  |
| 0     | 121       | 2.81%   |
| 3     | 47        | 1.09%   |
| 4     | 4         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2275      | 33.83%  |
| Intel                             | 1979      | 29.43%  |
| Qualcomm Atheros                  | 1030      | 15.32%  |
| Broadcom                          | 498       | 7.41%   |
| Marvell Technology Group          | 125       | 1.86%   |
| Broadcom Limited                  | 111       | 1.65%   |
| MediaTek                          | 84        | 1.25%   |
| Ralink                            | 73        | 1.09%   |
| TP-Link                           | 57        | 0.85%   |
| Ralink Technology                 | 46        | 0.68%   |
| Nvidia                            | 34        | 0.51%   |
| ASIX Electronics                  | 32        | 0.48%   |
| Dell                              | 29        | 0.43%   |
| Huawei Technologies               | 26        | 0.39%   |
| Samsung Electronics               | 21        | 0.31%   |
| Ericsson Business Mobile Networks | 21        | 0.31%   |
| Xiaomi                            | 19        | 0.28%   |
| Silicon Integrated Systems [SiS]  | 19        | 0.28%   |
| JMicron Technology                | 19        | 0.28%   |
| Sierra Wireless                   | 18        | 0.27%   |
| Attansic Technology               | 17        | 0.25%   |
| Qualcomm                          | 14        | 0.21%   |
| Qualcomm Atheros Communications   | 13        | 0.19%   |
| Hewlett-Packard                   | 12        | 0.18%   |
| OPPO Electronics                  | 10        | 0.15%   |
| DisplayLink                       | 10        | 0.15%   |
| Lenovo                            | 9         | 0.13%   |
| Sitecom Europe                    | 8         | 0.12%   |
| D-Link System                     | 7         | 0.1%    |
| Apple                             | 7         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 6         | 0.09%   |
| T & A Mobile Phones               | 6         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.09%   |
| NetGear                           | 6         | 0.09%   |
| AMD                               | 6         | 0.09%   |
| ICS Advent                        | 5         | 0.07%   |
| Fibocom                           | 5         | 0.07%   |
| D-Link                            | 5         | 0.07%   |
| Belkin Components                 | 5         | 0.07%   |
| ZyDAS                             | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1360      | 17.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 416       | 5.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 188       | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 182       | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 176       | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 164       | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 161       | 2.03%   |
| Intel Wireless 8265 / 8275                                              | 157       | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 155       | 1.96%   |
| Intel Wi-Fi 6 AX200                                                     | 143       | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 133       | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 131       | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 122       | 1.54%   |
| Intel Wireless 7265                                                     | 120       | 1.51%   |
| Intel Wireless 3165                                                     | 116       | 1.46%   |
| Intel Wireless 7260                                                     | 96        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 0.9%    |
| Intel Wireless 8260                                                     | 71        | 0.9%    |
| Intel WiFi Link 5100                                                    | 70        | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 68        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                           | 65        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 60        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 55        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 53        | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 46        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 45        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 44        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                   | 43        | 0.54%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 41        | 0.52%   |
| Intel Ethernet Connection I218-LM                                       | 39        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 39        | 0.49%   |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                | 37        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1898      | 43.77%  |
| Qualcomm Atheros                      | 940       | 21.68%  |
| Realtek Semiconductor                 | 697       | 16.07%  |
| Broadcom                              | 361       | 8.33%   |
| MediaTek                              | 82        | 1.89%   |
| Broadcom Limited                      | 77        | 1.78%   |
| Ralink                                | 73        | 1.68%   |
| Ralink Technology                     | 46        | 1.06%   |
| TP-Link                               | 45        | 1.04%   |
| Sierra Wireless                       | 18        | 0.42%   |
| Dell                                  | 18        | 0.42%   |
| Qualcomm Atheros Communications       | 13        | 0.3%    |
| Sitecom Europe                        | 7         | 0.16%   |
| Ericsson Business Mobile Networks     | 7         | 0.16%   |
| D-Link System                         | 7         | 0.16%   |
| Qualcomm                              | 6         | 0.14%   |
| NetGear                               | 6         | 0.14%   |
| Fibocom                               | 5         | 0.12%   |
| Belkin Components                     | 5         | 0.12%   |
| D-Link                                | 4         | 0.09%   |
| ZyDAS                                 | 3         | 0.07%   |
| Microsoft                             | 3         | 0.07%   |
| ASUSTek Computer                      | 3         | 0.07%   |
| U.S. Robotics                         | 2         | 0.05%   |
| Qcom                                  | 2         | 0.05%   |
| Hewlett-Packard                       | 2         | 0.05%   |
| Edimax Technology                     | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| AVM                                   | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 188       | 4.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 182       | 4.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 176       | 4.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 164       | 3.76%   |
| Intel Wireless 8265 / 8275                                              | 157       | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 155       | 3.56%   |
| Intel Wi-Fi 6 AX200                                                     | 143       | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 133       | 3.05%   |
| Intel Wi-Fi 6 AX201                                                     | 131       | 3.01%   |
| Intel Wireless 7265                                                     | 120       | 2.75%   |
| Intel Wireless 3165                                                     | 116       | 2.66%   |
| Intel Wireless 7260                                                     | 96        | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 1.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 1.63%   |
| Intel Wireless 8260                                                     | 71        | 1.63%   |
| Intel WiFi Link 5100                                                    | 70        | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 68        | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 65        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 60        | 1.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 55        | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 53        | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 46        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 45        | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 1.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 41        | 0.94%   |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 35        | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 35        | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 34        | 0.78%   |
| Intel Wireless-AC 9260                                                  | 34        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 33        | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 0.73%   |
| Intel Centrino Wireless-N 2230                                          | 32        | 0.73%   |
| Intel Wireless 3160                                                     | 30        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2009      | 58.11%  |
| Intel                                  | 603       | 17.44%  |
| Qualcomm Atheros                       | 207       | 5.99%   |
| Broadcom                               | 197       | 5.7%    |
| Marvell Technology Group               | 125       | 3.62%   |
| Broadcom Limited                       | 35        | 1.01%   |
| Nvidia                                 | 33        | 0.95%   |
| ASIX Electronics                       | 32        | 0.93%   |
| Samsung Electronics                    | 20        | 0.58%   |
| Huawei Technologies                    | 20        | 0.58%   |
| Xiaomi                                 | 19        | 0.55%   |
| JMicron Technology                     | 19        | 0.55%   |
| Silicon Integrated Systems [SiS]       | 17        | 0.49%   |
| Attansic Technology                    | 17        | 0.49%   |
| TP-Link                                | 12        | 0.35%   |
| OPPO Electronics                       | 10        | 0.29%   |
| DisplayLink                            | 10        | 0.29%   |
| Lenovo                                 | 9         | 0.26%   |
| Qualcomm                               | 8         | 0.23%   |
| Apple                                  | 7         | 0.2%    |
| ZTE WCDMA Technologies MSM             | 6         | 0.17%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.17%   |
| ICS Advent                             | 5         | 0.14%   |
| T & A Mobile Phones                    | 4         | 0.12%   |
| VIA Technologies                       | 3         | 0.09%   |
| Motorola PCS                           | 3         | 0.09%   |
| HMD Global                             | 3         | 0.09%   |
| Hewlett-Packard                        | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| MediaTek                               | 2         | 0.06%   |
| LG Electronics                         | 2         | 0.06%   |
| Google                                 | 2         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Sitecom Europe                         | 1         | 0.03%   |
| MosChip Semiconductor                  | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| D-Link                                 | 1         | 0.03%   |
| ADMtek                                 | 1         | 0.03%   |
| Accton Technology                      | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1360      | 38.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 416       | 11.93%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 161       | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 122       | 3.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 44        | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                          | 43        | 1.23%   |
| Intel Ethernet Connection I218-LM                                              | 39        | 1.12%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 39        | 1.12%   |
| Intel 82567LM Gigabit Network Connection                                       | 37        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 35        | 1%      |
| Intel 82577LM Gigabit Network Connection                                       | 35        | 1%      |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 33        | 0.95%   |
| Intel Ethernet Connection I219-LM                                              | 31        | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 30        | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 28        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 28        | 0.8%    |
| Intel Ethernet Connection I217-LM                                              | 26        | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 25        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                          | 25        | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 23        | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 22        | 0.63%   |
| Intel Ethernet Connection I219-V                                               | 22        | 0.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 21        | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 20        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 19        | 0.54%   |
| Nvidia MCP79 Ethernet                                                          | 18        | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 18        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 18        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 17        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 17        | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 17        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 17        | 0.49%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 17        | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 15        | 0.43%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 0.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 15        | 0.43%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 14        | 0.4%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 14        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4116      | 54.7%   |
| Ethernet | 3332      | 44.28%  |
| Modem    | 70        | 0.93%   |
| Unknown  | 7         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3461      | 79.45%  |
| Ethernet | 892       | 20.48%  |
| Unknown  | 2         | 0.05%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3033      | 72.08%  |
| 1     | 1051      | 24.98%  |
| 0     | 99        | 2.35%   |
| 3     | 25        | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3950      | 92.83%  |
| Yes  | 305       | 7.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1400      | 44.6%   |
| Realtek Semiconductor           | 405       | 12.9%   |
| Qualcomm Atheros Communications | 221       | 7.04%   |
| IMC Networks                    | 182       | 5.8%    |
| Lite-On Technology              | 178       | 5.67%   |
| Broadcom                        | 169       | 5.38%   |
| Foxconn / Hon Hai               | 140       | 4.46%   |
| Apple                           | 91        | 2.9%    |
| Hewlett-Packard                 | 67        | 2.13%   |
| Realtek                         | 58        | 1.85%   |
| Dell                            | 44        | 1.4%    |
| Cambridge Silicon Radio         | 42        | 1.34%   |
| Toshiba                         | 35        | 1.12%   |
| Ralink                          | 35        | 1.12%   |
| ASUSTek Computer                | 18        | 0.57%   |
| Alps Electric                   | 15        | 0.48%   |
| Ralink Technology               | 7         | 0.22%   |
| MediaTek                        | 6         | 0.19%   |
| Foxconn International           | 5         | 0.16%   |
| Chicony Electronics             | 4         | 0.13%   |
| Askey Computer                  | 4         | 0.13%   |
| Taiyo Yuden                     | 3         | 0.1%    |
| Integrated System Solution      | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |
| Actions                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 591       | 18.83%  |
| Realtek Bluetooth Radio                                                             | 294       | 9.37%   |
| Intel AX201 Bluetooth                                                               | 254       | 8.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 211       | 6.72%   |
| Intel AX200 Bluetooth                                                               | 138       | 4.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 98        | 3.12%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 88        | 2.8%    |
| Intel Bluetooth Device                                                              | 80        | 2.55%   |
| IMC Networks Bluetooth Device                                                       | 73        | 2.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 61        | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 51        | 1.62%   |
| IMC Networks Bluetooth Radio                                                        | 50        | 1.59%   |
| Apple Bluetooth Host Controller                                                     | 49        | 1.56%   |
| Realtek 802.11ac WLAN Adapter                                                       | 47        | 1.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 45        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 45        | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 43        | 1.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 42        | 1.34%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 41        | 1.31%   |
| Lite-On Bluetooth Device                                                            | 41        | 1.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 37        | 1.18%   |
| Ralink RT3290 Bluetooth                                                             | 35        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 32        | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 1.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 1.02%   |
| IMC Networks Wireless_Device                                                        | 26        | 0.83%   |
| Broadcom BCM2045 Bluetooth                                                          | 25        | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 22        | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.7%    |
| Intel AX210 Bluetooth                                                               | 21        | 0.67%   |
| Apple Bluetooth HCI                                                                 | 20        | 0.64%   |
| Apple Bluetooth USB Host Controller                                                 | 18        | 0.57%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 17        | 0.54%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 17        | 0.54%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.51%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 16        | 0.51%   |
| Lite-On Wireless_Device                                                             | 15        | 0.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 15        | 0.48%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 15        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3304      | 67.18%  |
| AMD                                          | 872       | 17.73%  |
| Nvidia                                       | 481       | 9.78%   |
| C-Media Electronics                          | 28        | 0.57%   |
| Silicon Integrated Systems [SiS]             | 26        | 0.53%   |
| Logitech                                     | 20        | 0.41%   |
| GN Netcom                                    | 20        | 0.41%   |
| JMTek                                        | 15        | 0.31%   |
| Realtek Semiconductor                        | 14        | 0.28%   |
| Generalplus Technology                       | 12        | 0.24%   |
| CMX Systems                                  | 8         | 0.16%   |
| VIA Technologies                             | 7         | 0.14%   |
| Lenovo                                       | 7         | 0.14%   |
| Texas Instruments                            | 6         | 0.12%   |
| Plantronics                                  | 5         | 0.1%    |
| Hewlett-Packard                              | 5         | 0.1%    |
| Apple                                        | 5         | 0.1%    |
| M-Audio                                      | 4         | 0.08%   |
| Huawei Technologies                          | 4         | 0.08%   |
| Fujitsu                                      | 4         | 0.08%   |
| Creative Technology                          | 4         | 0.08%   |
| BEHRINGER International                      | 4         | 0.08%   |
| Sony                                         | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Focusrite-Novation                           | 3         | 0.06%   |
| Syntek                                       | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| Medeli Electronics                           | 2         | 0.04%   |
| Jieli Technology                             | 2         | 0.04%   |
| DSEA A/S                                     | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| ASUSTek Computer                             | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| Textech International                        | 1         | 0.02%   |
| TEAC                                         | 1         | 0.02%   |
| SmartlinkTechnology                          | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 470       | 7.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 388       | 6.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 307       | 5.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 242       | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 227       | 3.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 212       | 3.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 190       | 3.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 185       | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 184       | 3.08%   |
| Intel 8 Series HD Audio Controller                                                                | 184       | 3.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 145       | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 137       | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 136       | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 131       | 2.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 128       | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 123       | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 122       | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 121       | 2.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 117       | 1.96%   |
| Intel Broadwell-U Audio Controller                                                                | 116       | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 112       | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 107       | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 104       | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 97        | 1.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 68        | 1.14%   |
| AMD High Definition Audio Controller                                                              | 66        | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 65        | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 63        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 61        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 59        | 0.99%   |
| Intel CM238 HD Audio Controller                                                                   | 58        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 50        | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 46        | 0.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 46        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 39        | 0.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 36        | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 34        | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 34        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 32        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 821       | 29.49%  |
| SK hynix                     | 607       | 21.8%   |
| Micron Technology            | 356       | 12.79%  |
| Unknown                      | 247       | 8.87%   |
| Kingston                     | 230       | 8.26%   |
| Crucial                      | 126       | 4.53%   |
| Ramaxel Technology           | 69        | 2.48%   |
| Elpida                       | 65        | 2.33%   |
| Unknown (ABCD)               | 59        | 2.12%   |
| A-DATA Technology            | 42        | 1.51%   |
| Corsair                      | 38        | 1.36%   |
| Nanya Technology             | 35        | 1.26%   |
| Unknown                      | 15        | 0.54%   |
| Team                         | 11        | 0.4%    |
| Transcend                    | 9         | 0.32%   |
| ASint Technology             | 6         | 0.22%   |
| Toshiba                      | 5         | 0.18%   |
| Timetec                      | 5         | 0.18%   |
| G.Skill                      | 5         | 0.18%   |
| 48spaces                     | 5         | 0.18%   |
| Qimonda                      | 4         | 0.14%   |
| Patriot                      | 2         | 0.07%   |
| ChangXin Memory              | 2         | 0.07%   |
| Apacer                       | 2         | 0.07%   |
| Unknown (8A5D)               | 1         | 0.04%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.04%   |
| Unknown (0x5846)             | 1         | 0.04%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.04%   |
| Unigen                       | 1         | 0.04%   |
| Unifosa                      | 1         | 0.04%   |
| Smart Brazil                 | 1         | 0.04%   |
| Silicon Power                | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Sesame                       | 1         | 0.04%   |
| Neo Forza                    | 1         | 0.04%   |
| Lexar                        | 1         | 0.04%   |
| Infineon                     | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Essencore Limited            | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 54        | 1.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 44        | 1.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 1.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 38        | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 1.08%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 31        | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 30        | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 29        | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.81%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 21        | 0.71%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 17        | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.57%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 0.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 17        | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 16        | 0.54%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 16        | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.51%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 15        | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.51%   |
| Unknown                                                          | 15        | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 14        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 14        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1121      | 46.63%  |
| DDR3    | 806       | 33.53%  |
| LPDDR4  | 148       | 6.16%   |
| DDR2    | 141       | 5.87%   |
| LPDDR3  | 64        | 2.66%   |
| SDRAM   | 50        | 2.08%   |
| DDR5    | 21        | 0.87%   |
| Unknown | 19        | 0.79%   |
| LPDDR5  | 14        | 0.58%   |
| DRAM    | 12        | 0.5%    |
| DDR     | 8         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2153      | 88.78%  |
| Row Of Chips | 248       | 10.23%  |
| DIMM         | 11        | 0.45%   |
| Chip         | 10        | 0.41%   |
| Unknown      | 3         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1001      | 38.03%  |
| 4096  | 800       | 30.4%   |
| 2048  | 353       | 13.41%  |
| 16384 | 331       | 12.58%  |
| 1024  | 75        | 2.85%   |
| 32768 | 55        | 2.09%   |
| 512   | 16        | 0.61%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 525       | 20.26%  |
| 1600    | 510       | 19.68%  |
| 3200    | 457       | 17.64%  |
| 2400    | 203       | 7.83%   |
| 1334    | 143       | 5.52%   |
| 2133    | 122       | 4.71%   |
| 1333    | 88        | 3.4%    |
| Unknown | 83        | 3.2%    |
| 667     | 81        | 3.13%   |
| 4267    | 51        | 1.97%   |
| 3266    | 44        | 1.7%    |
| 1066    | 41        | 1.58%   |
| 800     | 38        | 1.47%   |
| 1867    | 26        | 1%      |
| 1067    | 26        | 1%      |
| 4800    | 23        | 0.89%   |
| 4199    | 20        | 0.77%   |
| 8400    | 17        | 0.66%   |
| 2048    | 15        | 0.58%   |
| 533     | 15        | 0.58%   |
| 6400    | 14        | 0.54%   |
| 975     | 9         | 0.35%   |
| 4266    | 8         | 0.31%   |
| 2933    | 7         | 0.27%   |
| 3733    | 4         | 0.15%   |
| 333     | 3         | 0.12%   |
| 3400    | 2         | 0.08%   |
| 1866    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 3000    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 2000    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 31.82%  |
| Samsung Electronics | 17        | 25.76%  |
| Canon               | 11        | 16.67%  |
| Brother Industries  | 7         | 10.61%  |
| Seiko Epson         | 4         | 6.06%   |
| Pantum              | 2         | 3.03%   |
| Xerox               | 1         | 1.52%   |
| Sagem               | 1         | 1.52%   |
| ICS Advent          | 1         | 1.52%   |
| Apple               | 1         | 1.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 3         | 4.48%   |
| Samsung M2070 Series                 | 3         | 4.48%   |
| Samsung M267x 287x Series            | 2         | 2.99%   |
| HP OfficeJet 3830 series             | 2         | 2.99%   |
| HP Officejet 2620 series             | 2         | 2.99%   |
| Xerox B215                           | 1         | 1.49%   |
| Seiko Epson WF-2510 Series           | 1         | 1.49%   |
| Seiko Epson Printer                  | 1         | 1.49%   |
| Seiko Epson L355 Series              | 1         | 1.49%   |
| Seiko Epson ET-2810 Series           | 1         | 1.49%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.49%   |
| Samsung SCX-4623 Series              | 1         | 1.49%   |
| Samsung SCX-4300 Series              | 1         | 1.49%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.49%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.49%   |
| Samsung ML-1865W Series              | 1         | 1.49%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.49%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.49%   |
| Samsung C3060 Series                 | 1         | 1.49%   |
| Sagem Laser Pro LL                   | 1         | 1.49%   |
| Pantum P2500W series                 | 1         | 1.49%   |
| Pantum M6500W series                 | 1         | 1.49%   |
| ICS Advent Parallel Adapter          | 1         | 1.49%   |
| HP Officejet Pro 6230                | 1         | 1.49%   |
| HP OfficeJet 6950                    | 1         | 1.49%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.49%   |
| HP LaserJet P3005                    | 1         | 1.49%   |
| HP LaserJet P2055 series             | 1         | 1.49%   |
| HP LaserJet P1102                    | 1         | 1.49%   |
| HP LaserJet 1200                     | 1         | 1.49%   |
| HP LaserJet 1020                     | 1         | 1.49%   |
| HP LaserJet 1015                     | 1         | 1.49%   |
| HP LaserJet 1010                     | 1         | 1.49%   |
| HP ENVY 5000 series                  | 1         | 1.49%   |
| HP ENVY 4520 series                  | 1         | 1.49%   |
| HP DeskJet 940c                      | 1         | 1.49%   |
| HP DeskJet 840c                      | 1         | 1.49%   |
| HP Deskjet 3520 series               | 1         | 1.49%   |
| HP DeskJet 2700 series               | 1         | 1.49%   |
| HP Deskjet 2050 J510                 | 1         | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 46.15%  |
| Seiko Epson     | 5         | 38.46%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.14%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.14%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.14%   |
| HP Scanjet G2710                                         | 1         | 7.14%   |
| HP ScanJet 3570c                                         | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.14%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.14%   |
| Canon CanoScan 4400F                                     | 1         | 7.14%   |
| Canon CanoScan 1220U                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 984       | 26.16%  |
| IMC Networks                           | 460       | 12.23%  |
| Realtek Semiconductor                  | 278       | 7.39%   |
| Microdia                               | 263       | 6.99%   |
| Bison Electronics                      | 245       | 6.51%   |
| Quanta                                 | 200       | 5.32%   |
| Suyin                                  | 184       | 4.89%   |
| Cheng Uei Precision Industry (Foxlink) | 162       | 4.31%   |
| Sunplus Innovation Technology          | 160       | 4.25%   |
| Alcor Micro                            | 104       | 2.76%   |
| Syntek                                 | 95        | 2.53%   |
| Lite-On Technology                     | 87        | 2.31%   |
| Apple                                  | 82        | 2.18%   |
| Luxvisions Innotech Limited            | 80        | 2.13%   |
| Acer                                   | 65        | 1.73%   |
| Silicon Motion                         | 47        | 1.25%   |
| Ricoh                                  | 47        | 1.25%   |
| Logitech                               | 30        | 0.8%    |
| Z-Star Microelectronics                | 20        | 0.53%   |
| ALi                                    | 17        | 0.45%   |
| Samsung Electronics                    | 15        | 0.4%    |
| Primax Electronics                     | 15        | 0.4%    |
| icSpring                               | 13        | 0.35%   |
| Lenovo                                 | 10        | 0.27%   |
| Sunplus Technology                     | 8         | 0.21%   |
| Sonix Technology                       | 8         | 0.21%   |
| Importek                               | 7         | 0.19%   |
| DigiTech                               | 7         | 0.19%   |
| ARC International                      | 6         | 0.16%   |
| SunplusIT                              | 5         | 0.13%   |
| Genesys Logic                          | 5         | 0.13%   |
| GEMBIRD                                | 5         | 0.13%   |
| Microsoft                              | 4         | 0.11%   |
| Generalplus Technology                 | 3         | 0.08%   |
| WaveRider Communications               | 2         | 0.05%   |
| USB Camera CS                          | 2         | 0.05%   |
| Unknown (3730304231385031345945)       | 2         | 0.05%   |
| Pixart Imaging                         | 2         | 0.05%   |
| OmniVision Technologies                | 2         | 0.05%   |
| Nebraska Furniture Mart                | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 152       | 4.02%   |
| Microdia Integrated_Webcam_HD                           | 111       | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 86        | 2.28%   |
| Chicony HD WebCam                                       | 81        | 2.14%   |
| IMC Networks Integrated Camera                          | 74        | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 71        | 1.88%   |
| Bison Integrated Camera                                 | 64        | 1.69%   |
| Realtek Integrated_Webcam_HD                            | 60        | 1.59%   |
| Syntek Integrated Camera                                | 52        | 1.38%   |
| Alcor Micro USB 2.0 PC cam                              | 52        | 1.38%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 47        | 1.24%   |
| Realtek USB Camera                                      | 45        | 1.19%   |
| Chicony USB2.0 VGA UVC WebCam                           | 45        | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                            | 43        | 1.14%   |
| Chicony HP TrueVision HD                                | 43        | 1.14%   |
| Sunplus Integrated_Webcam_HD                            | 42        | 1.11%   |
| Quanta HP TrueVision HD Camera                          | 38        | 1.01%   |
| Chicony HP TrueVision HD Camera                         | 38        | 1.01%   |
| IMC Networks HD Camera                                  | 37        | 0.98%   |
| Bison HD Webcam                                         | 36        | 0.95%   |
| Chicony HP Webcam                                       | 31        | 0.82%   |
| Sunplus HD WebCam                                       | 30        | 0.79%   |
| Chicony HP HD Camera                                    | 30        | 0.79%   |
| Chicony FJ Camera                                       | 30        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 29        | 0.77%   |
| Quanta HP Webcam                                        | 28        | 0.74%   |
| Chicony USB2.0 Camera                                   | 27        | 0.71%   |
| Suyin HP TrueVision HD                                  | 25        | 0.66%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 25        | 0.66%   |
| Apple Built-in iSight                                   | 25        | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 24        | 0.64%   |
| Microdia Integrated Webcam                              | 24        | 0.64%   |
| IMC Networks ov9734_azurewave_camera                    | 24        | 0.64%   |
| Chicony HP Wide Vision HD Camera                        | 24        | 0.64%   |
| Alcor Micro Asus Integrated Webcam                      | 24        | 0.64%   |
| Bison SunplusIT Integrated Camera                       | 23        | 0.61%   |
| Suyin Acer CrystalEye Webcam                            | 22        | 0.58%   |
| Lite-On HP HD Camera                                    | 22        | 0.58%   |
| IMC Networks UVC VGA Webcam                             | 22        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 209       | 28.95%  |
| Synaptics                          | 152       | 21.05%  |
| Shenzhen Goodix Technology         | 131       | 18.14%  |
| Elan Microelectronics              | 90        | 12.47%  |
| Upek                               | 43        | 5.96%   |
| AuthenTec                          | 42        | 5.82%   |
| LighTuning Technology              | 39        | 5.4%    |
| STMicroelectronics                 | 6         | 0.83%   |
| Focal-systems.Corp                 | 6         | 0.83%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.28%   |
| Microsoft                          | 1         | 0.14%   |
| HOLTEK                             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 101       | 13.99%  |
| Elan ELAN:ARM-M4                                                           | 63        | 8.73%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 5.96%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 5.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 3.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 25        | 3.46%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 2.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 2.91%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 2.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 2.49%   |
| Elan ELAN:Fingerprint                                                      | 18        | 2.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 2.22%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.94%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.66%   |
| Validity Sensors VFS491                                                    | 11        | 1.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.52%   |
| Unknown                                                                    | 10        | 1.39%   |
| Synaptics  WBDI                                                            | 9         | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 1.25%   |
| Elan WBF Fingerprint Sensor                                                | 9         | 1.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.11%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.11%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.11%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.97%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.97%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.97%   |
| AuthenTec AES2810                                                          | 7         | 0.97%   |
| AuthenTec AES1600                                                          | 7         | 0.97%   |
| Synaptics UWP WBDI                                                         | 6         | 0.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.83%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 0.83%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.69%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 118       | 41.84%  |
| Alcor Micro              | 89        | 31.56%  |
| O2 Micro                 | 28        | 9.93%   |
| Lenovo                   | 16        | 5.67%   |
| Upek                     | 12        | 4.26%   |
| Advanced Card Systems    | 5         | 1.77%   |
| Gemalto (was Gemplus)    | 4         | 1.42%   |
| BIT4ID                   | 4         | 1.42%   |
| Realtek Semiconductor    | 2         | 0.71%   |
| SCM Microsystems         | 1         | 0.35%   |
| Reiner SCT Kartensysteme | 1         | 0.35%   |
| OmniKey                  | 1         | 0.35%   |
| In Focus Systems         | 1         | 0.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 30.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 12.41%  |
| Broadcom 58200                                                               | 35        | 12.41%  |
| Broadcom 5880                                                                | 26        | 9.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 8.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 7.09%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 4.26%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.42%   |
| BIT4ID miniLector EVO                                                        | 4         | 1.42%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.06%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.06%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.06%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.71%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.71%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.71%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.35%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.35%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.35%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.35%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2618      | 60.41%  |
| 1     | 1343      | 30.99%  |
| 2     | 326       | 7.52%   |
| 3     | 32        | 0.74%   |
| 4     | 11        | 0.25%   |
| 5     | 3         | 0.07%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 714       | 34.48%  |
| Graphics card            | 527       | 25.45%  |
| Chipcard                 | 245       | 11.83%  |
| Net/wireless             | 183       | 8.84%   |
| Multimedia controller    | 102       | 4.93%   |
| Camera                   | 76        | 3.67%   |
| Bluetooth                | 60        | 2.9%    |
| Storage                  | 34        | 1.64%   |
| Communication controller | 31        | 1.5%    |
| Sound                    | 19        | 0.92%   |
| Modem                    | 19        | 0.92%   |
| Flash memory             | 18        | 0.87%   |
| Net/ethernet             | 15        | 0.72%   |
| Card reader              | 13        | 0.63%   |
| Network                  | 7         | 0.34%   |
| Dvb card                 | 3         | 0.14%   |
| Storage/ide              | 2         | 0.1%    |
| Wireless                 | 1         | 0.05%   |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |

