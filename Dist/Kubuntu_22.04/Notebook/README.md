Kubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

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

Total: 469

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Unknown       | Unknown                     | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.0-52-generic       | 42        | 11.26%  |
| 5.15.0-56-generic       | 37        | 9.92%   |
| 5.15.0-48-generic       | 22        | 5.9%    |
| 5.15.0-53-generic       | 21        | 5.63%   |
| 5.15.0-47-generic       | 21        | 5.63%   |
| 5.15.0-58-generic       | 18        | 4.83%   |
| 5.15.0-46-generic       | 17        | 4.56%   |
| 5.15.0-43-generic       | 17        | 4.56%   |
| 5.15.0-41-generic       | 17        | 4.56%   |
| 5.15.0-40-generic       | 15        | 4.02%   |
| 5.15.0-25-generic       | 14        | 3.75%   |
| 5.15.0-50-generic       | 12        | 3.22%   |
| 5.15.0-27-generic       | 12        | 3.22%   |
| 5.15.0-33-generic       | 10        | 2.68%   |
| 5.15.0-57-generic       | 8         | 2.14%   |
| 5.15.0-39-generic       | 7         | 1.88%   |
| 5.15.0-43-lowlatency    | 5         | 1.34%   |
| 5.15.0-37-generic       | 5         | 1.34%   |
| 5.15.0-35-generic       | 4         | 1.07%   |
| 5.15.0-30-generic       | 4         | 1.07%   |
| 5.15.0-18-generic       | 4         | 1.07%   |
| 5.15.0-46-lowlatency    | 3         | 0.8%    |
| 6.0.7-060007-generic    | 2         | 0.54%   |
| 5.19.5-051905-generic   | 2         | 0.54%   |
| 5.17.0-1026-oem         | 2         | 0.54%   |
| 5.17.0-1020-oem         | 2         | 0.54%   |
| 5.15.0-53-lowlatency    | 2         | 0.54%   |
| 5.15.0-52-lowlatency    | 2         | 0.54%   |
| 5.15.0-48-lowlatency    | 2         | 0.54%   |
| 5.15.0-32-generic       | 2         | 0.54%   |
| 5.15.0-30-lowlatency    | 2         | 0.54%   |
| 5.15.0-23-generic       | 2         | 0.54%   |
| 5.15.0-10033-tuxedo     | 2         | 0.54%   |
| 5.13.0-19-generic       | 2         | 0.54%   |
| 6.0.9-060009-generic    | 1         | 0.27%   |
| 6.0.6-76060006-generic  | 1         | 0.27%   |
| 6.0.1-060001-generic    | 1         | 0.27%   |
| 6.0.0-t2                | 1         | 0.27%   |
| 6.0.0-1006-oem          | 1         | 0.27%   |
| 6.0.0-060000rc3-generic | 1         | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 323       | 91.24%  |
| 5.17.0  | 6         | 1.69%   |
| 6.0.0   | 3         | 0.85%   |
| 5.13.0  | 3         | 0.85%   |
| 6.0.7   | 2         | 0.56%   |
| 5.19.5  | 2         | 0.56%   |
| 6.0.9   | 1         | 0.28%   |
| 6.0.6   | 1         | 0.28%   |
| 6.0.1   | 1         | 0.28%   |
| 5.19.2  | 1         | 0.28%   |
| 5.19.11 | 1         | 0.28%   |
| 5.18.6  | 1         | 0.28%   |
| 5.18.15 | 1         | 0.28%   |
| 5.18.10 | 1         | 0.28%   |
| 5.17.5  | 1         | 0.28%   |
| 5.17.4  | 1         | 0.28%   |
| 5.17.2  | 1         | 0.28%   |
| 5.16.2  | 1         | 0.28%   |
| 5.16.11 | 1         | 0.28%   |
| 5.15.65 | 1         | 0.28%   |
| 5.15.34 | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 324       | 92.05%  |
| 5.17    | 9         | 2.56%   |
| 6.0     | 7         | 1.99%   |
| 5.19    | 4         | 1.14%   |
| 5.18    | 3         | 0.85%   |
| 5.13    | 3         | 0.85%   |
| 5.16    | 2         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 348       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 342       | 97.71%  |
| GNOME      | 3         | 0.86%   |
| X-Cinnamon | 1         | 0.29%   |
| MATE       | 1         | 0.29%   |
| KDE        | 1         | 0.29%   |
| i3         | 1         | 0.29%   |
| GNUstep    | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 331       | 94.3%   |
| Wayland | 17        | 4.84%   |
| Tty     | 3         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 261       | 74.57%  |
| Unknown | 64        | 18.29%  |
| GDM3    | 16        | 4.57%   |
| LightDM | 7         | 2%      |
| SLiM    | 1         | 0.29%   |
| LXDM    | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 178       | 50.86%  |
| it_IT   | 23        | 6.57%   |
| de_DE   | 23        | 6.57%   |
| ru_RU   | 20        | 5.71%   |
| fr_FR   | 13        | 3.71%   |
| en_GB   | 13        | 3.71%   |
| pl_PL   | 9         | 2.57%   |
| es_ES   | 9         | 2.57%   |
| en_IN   | 8         | 2.29%   |
| en_AU   | 6         | 1.71%   |
| pt_BR   | 5         | 1.43%   |
| hu_HU   | 5         | 1.43%   |
| en_NZ   | 4         | 1.14%   |
| en_CA   | 4         | 1.14%   |
| tr_TR   | 3         | 0.86%   |
| en_PH   | 3         | 0.86%   |
| es_CL   | 2         | 0.57%   |
| en_SG   | 2         | 0.57%   |
| Default | 2         | 0.57%   |
| zh_TW   | 1         | 0.29%   |
| sl_SI   | 1         | 0.29%   |
| ru_UA   | 1         | 0.29%   |
| pt_PT   | 1         | 0.29%   |
| nl_BE   | 1         | 0.29%   |
| lt_LT   | 1         | 0.29%   |
| ko_KR   | 1         | 0.29%   |
| fr_CH   | 1         | 0.29%   |
| et_EE   | 1         | 0.29%   |
| es_MX   | 1         | 0.29%   |
| es_EC   | 1         | 0.29%   |
| es_CR   | 1         | 0.29%   |
| es_AR   | 1         | 0.29%   |
| en_ZA   | 1         | 0.29%   |
| en_DE   | 1         | 0.29%   |
| el_GR   | 1         | 0.29%   |
| da_DK   | 1         | 0.29%   |
| cs_CZ   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 208       | 59.26%  |
| BIOS | 143       | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 317       | 90.57%  |
| Btrfs   | 15        | 4.29%   |
| Overlay | 14        | 4%      |
| Xfs     | 3         | 0.86%   |
| Ext2    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 229       | 65.43%  |
| Unknown | 101       | 28.86%  |
| MBR     | 20        | 5.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 326       | 93.68%  |
| Yes       | 22        | 6.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 216       | 61.89%  |
| Yes       | 133       | 38.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 81        | 23.28%  |
| Hewlett-Packard                | 64        | 18.39%  |
| Dell                           | 52        | 14.94%  |
| Acer                           | 29        | 8.33%   |
| ASUSTek Computer               | 28        | 8.05%   |
| MSI                            | 12        | 3.45%   |
| Apple                          | 9         | 2.59%   |
| HUAWEI                         | 7         | 2.01%   |
| Toshiba                        | 6         | 1.72%   |
| Samsung Electronics            | 6         | 1.72%   |
| Google                         | 5         | 1.44%   |
| TUXEDO                         | 4         | 1.15%   |
| Timi                           | 4         | 1.15%   |
| Gigabyte Technology            | 3         | 0.86%   |
| System76                       | 2         | 0.57%   |
| Sony                           | 2         | 0.57%   |
| Panasonic                      | 2         | 0.57%   |
| Notebook                       | 2         | 0.57%   |
| HONOR                          | 2         | 0.57%   |
| Haier                          | 2         | 0.57%   |
| GPU Company                    | 2         | 0.57%   |
| Framework                      | 2         | 0.57%   |
| Unknown                        | 2         | 0.57%   |
| VALE                           | 1         | 0.29%   |
| TrekStor                       | 1         | 0.29%   |
| Tactus                         | 1         | 0.29%   |
| Standard                       | 1         | 0.29%   |
| SLIMBOOK                       | 1         | 0.29%   |
| SK hynix                       | 1         | 0.29%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.29%   |
| SGIN                           | 1         | 0.29%   |
| Schenker                       | 1         | 0.29%   |
| Razer                          | 1         | 0.29%   |
| Monster                        | 1         | 0.29%   |
| LG Electronics                 | 1         | 0.29%   |
| Jumper                         | 1         | 0.29%   |
| Intel                          | 1         | 0.29%   |
| Fujitsu                        | 1         | 0.29%   |
| Dynabook                       | 1         | 0.29%   |
| Digma                          | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 6         | 1.72%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 3         | 0.86%   |
| HP ProBook 6470b                       | 3         | 0.86%   |
| HP Pavilion g6                         | 3         | 0.86%   |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.86%   |
| HP 255 G8 Notebook PC                  | 3         | 0.86%   |
| Dell XPS 15 9560                       | 3         | 0.86%   |
| Dell Latitude 3420                     | 3         | 0.86%   |
| Timi TM1701                            | 2         | 0.57%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 2         | 0.57%   |
| HUAWEI CREM-WXX9                       | 2         | 0.57%   |
| HP ProBook 6570b                       | 2         | 0.57%   |
| HP ProBook 440 G8 Notebook PC          | 2         | 0.57%   |
| HP Pavilion Laptop 15-eh1xxx           | 2         | 0.57%   |
| HP Pavilion dv6                        | 2         | 0.57%   |
| HP OMEN Laptop 15-en0xxx               | 2         | 0.57%   |
| HP Laptop 17-by3xxx                    | 2         | 0.57%   |
| HP Laptop 15-da0xxx                    | 2         | 0.57%   |
| Haier A1420EM                          | 2         | 0.57%   |
| Framework Laptop (12th Gen Intel Core) | 2         | 0.57%   |
| Acer Nitro AN517-51                    | 2         | 0.57%   |
| Acer Aspire E5-575G                    | 2         | 0.57%   |
| VALE Notebook Slim S132                | 1         | 0.29%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.29%   |
| TUXEDO Polaris 15 AMD Gen1             | 1         | 0.29%   |
| TUXEDO InfinityBook S 15 Gen6          | 1         | 0.29%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)     | 1         | 0.29%   |
| TrekStor Surfbook A13B                 | 1         | 0.29%   |
| Toshiba TECRA S11                      | 1         | 0.29%   |
| Toshiba Satellite P70-B                | 1         | 0.29%   |
| Toshiba Satellite NB10t-A-102          | 1         | 0.29%   |
| Toshiba Satellite L850                 | 1         | 0.29%   |
| Toshiba Satellite L655                 | 1         | 0.29%   |
| Toshiba Satellite C650D                | 1         | 0.29%   |
| Timi TM1703                            | 1         | 0.29%   |
| Timi Mi Laptop Air 12.5                | 1         | 0.29%   |
| Tactus GeoBook 140                     | 1         | 0.29%   |
| System76 Lemur Ultra                   | 1         | 0.29%   |
| System76 Kudu Professional             | 1         | 0.29%   |
| Sony VGN-NR11Z_T                       | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 34        | 9.77%   |
| Lenovo IdeaPad      | 22        | 6.32%   |
| Dell Latitude       | 18        | 5.17%   |
| Acer Aspire         | 16        | 4.6%    |
| HP ProBook          | 13        | 3.74%   |
| HP Pavilion         | 13        | 3.74%   |
| Dell Inspiron       | 12        | 3.45%   |
| HP Laptop           | 11        | 3.16%   |
| Dell XPS            | 9         | 2.59%   |
| HP EliteBook        | 8         | 2.3%    |
| Lenovo ThinkBook    | 6         | 1.72%   |
| Lenovo Legion       | 6         | 1.72%   |
| ASUS VivoBook       | 6         | 1.72%   |
| Acer Nitro          | 6         | 1.72%   |
| Unknown             | 6         | 1.72%   |
| Toshiba Satellite   | 5         | 1.44%   |
| Dell Vostro         | 5         | 1.44%   |
| Dell Precision      | 5         | 1.44%   |
| HP OMEN             | 4         | 1.15%   |
| ASUS ROG            | 4         | 1.15%   |
| HP 255              | 3         | 0.86%   |
| Apple MacBookPro11  | 3         | 0.86%   |
| Acer Predator       | 3         | 0.86%   |
| TUXEDO InfinityBook | 2         | 0.57%   |
| Timi TM1701         | 2         | 0.57%   |
| MSI Raider          | 2         | 0.57%   |
| MSI Prestige        | 2         | 0.57%   |
| Lenovo Yoga         | 2         | 0.57%   |
| HUAWEI CREM-WXX9    | 2         | 0.57%   |
| Haier A1420EM       | 2         | 0.57%   |
| Framework Laptop    | 2         | 0.57%   |
| ASUS ASUS           | 2         | 0.57%   |
| Acer TravelMate     | 2         | 0.57%   |
| Acer Swift          | 2         | 0.57%   |
| VALE Notebook       | 1         | 0.29%   |
| TUXEDO Stellaris    | 1         | 0.29%   |
| TUXEDO Polaris      | 1         | 0.29%   |
| TrekStor Surfbook   | 1         | 0.29%   |
| Toshiba TECRA       | 1         | 0.29%   |
| Timi TM1703         | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 77        | 22.13%  |
| 2020 | 54        | 15.52%  |
| 2022 | 36        | 10.34%  |
| 2012 | 33        | 9.48%   |
| 2019 | 27        | 7.76%   |
| 2018 | 19        | 5.46%   |
| 2014 | 17        | 4.89%   |
| 2017 | 15        | 4.31%   |
| 2016 | 15        | 4.31%   |
| 2011 | 15        | 4.31%   |
| 2013 | 14        | 4.02%   |
| 2015 | 11        | 3.16%   |
| 2010 | 6         | 1.72%   |
| 2008 | 3         | 0.86%   |
| 2007 | 3         | 0.86%   |
| 2009 | 2         | 0.57%   |
| 2023 | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 348       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 303       | 86.57%  |
| Enabled  | 47        | 13.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 342       | 98.28%  |
| Yes  | 6         | 1.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 108       | 30.68%  |
| 16.01-24.0  | 87        | 24.72%  |
| 8.01-16.0   | 66        | 18.75%  |
| 3.01-4.0    | 36        | 10.23%  |
| 32.01-64.0  | 35        | 9.94%   |
| 64.01-256.0 | 11        | 3.13%   |
| 24.01-32.0  | 6         | 1.7%    |
| 2.01-3.0    | 3         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 97        | 26.43%  |
| 3.01-4.0  | 86        | 23.43%  |
| 1.01-2.0  | 83        | 22.62%  |
| 4.01-8.0  | 80        | 21.8%   |
| 8.01-16.0 | 20        | 5.45%   |
| 0.51-1.0  | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 235       | 66.76%  |
| 2      | 100       | 28.41%  |
| 3      | 10        | 2.84%   |
| 4      | 6         | 1.7%    |
| 0      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 284       | 81.38%  |
| Yes       | 65        | 18.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 250       | 71.84%  |
| No        | 98        | 28.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 347       | 99.71%  |
| No        | 1         | 0.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 302       | 86.04%  |
| No        | 49        | 13.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 64        | 18.39%  |
| Italy       | 33        | 9.48%   |
| Germany     | 30        | 8.62%   |
| Russia      | 27        | 7.76%   |
| France      | 19        | 5.46%   |
| Poland      | 14        | 4.02%   |
| Spain       | 12        | 3.45%   |
| UK          | 10        | 2.87%   |
| India       | 8         | 2.3%    |
| Hungary     | 8         | 2.3%    |
| Brazil      | 8         | 2.3%    |
| Indonesia   | 7         | 2.01%   |
| Switzerland | 6         | 1.72%   |
| Canada      | 6         | 1.72%   |
| Australia   | 5         | 1.44%   |
| Turkey      | 4         | 1.15%   |
| Philippines | 4         | 1.15%   |
| New Zealand | 4         | 1.15%   |
| Mexico      | 4         | 1.15%   |
| Estonia     | 4         | 1.15%   |
| South Korea | 3         | 0.86%   |
| Slovenia    | 3         | 0.86%   |
| Portugal    | 3         | 0.86%   |
| Netherlands | 3         | 0.86%   |
| Lithuania   | 3         | 0.86%   |
| Denmark     | 3         | 0.86%   |
| Czechia     | 3         | 0.86%   |
| Bulgaria    | 3         | 0.86%   |
| Argentina   | 3         | 0.86%   |
| Ukraine     | 2         | 0.57%   |
| Taiwan      | 2         | 0.57%   |
| Sweden      | 2         | 0.57%   |
| Slovakia    | 2         | 0.57%   |
| Singapore   | 2         | 0.57%   |
| Serbia      | 2         | 0.57%   |
| Romania     | 2         | 0.57%   |
| Pakistan    | 2         | 0.57%   |
| Ireland     | 2         | 0.57%   |
| Greece      | 2         | 0.57%   |
| Ecuador     | 2         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 10        | 2.8%    |
| Milan                   | 9         | 2.52%   |
| Paris                   | 5         | 1.4%    |
| Berlin                  | 5         | 1.4%    |
| Warsaw                  | 4         | 1.12%   |
| St Petersburg           | 4         | 1.12%   |
| Wroclaw                 | 3         | 0.84%   |
| Vilnius                 | 3         | 0.84%   |
| Turin                   | 3         | 0.84%   |
| Tallinn                 | 3         | 0.84%   |
| Sofia                   | 3         | 0.84%   |
| Madrid                  | 3         | 0.84%   |
| Jakarta                 | 3         | 0.84%   |
| Budapest                | 3         | 0.84%   |
| Bengaluru               | 3         | 0.84%   |
| Auckland                | 3         | 0.84%   |
| Zurich                  | 2         | 0.56%   |
| Vladivostok             | 2         | 0.56%   |
| Taipei                  | 2         | 0.56%   |
| Singapore               | 2         | 0.56%   |
| Seattle                 | 2         | 0.56%   |
| Sao Paulo               | 2         | 0.56%   |
| Samara                  | 2         | 0.56%   |
| Rome                    | 2         | 0.56%   |
| Quito                   | 2         | 0.56%   |
| Porto                   | 2         | 0.56%   |
| Parma                   | 2         | 0.56%   |
| Nuremberg               | 2         | 0.56%   |
| Murska Sobota           | 2         | 0.56%   |
| Munich                  | 2         | 0.56%   |
| Minsk                   | 2         | 0.56%   |
| Minneapolis             | 2         | 0.56%   |
| Marseille               | 2         | 0.56%   |
| Katerini                | 2         | 0.56%   |
| Kassel                  | 2         | 0.56%   |
| Jacksonville            | 2         | 0.56%   |
| Granozzo con Monticello | 2         | 0.56%   |
| Dublin                  | 2         | 0.56%   |
| Cologne                 | 2         | 0.56%   |
| Castro Valley           | 2         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 77        | 97     | 16.89%  |
| WDC                       | 49        | 57     | 10.75%  |
| Kingston                  | 32        | 35     | 7.02%   |
| Toshiba                   | 28        | 36     | 6.14%   |
| SK hynix                  | 28        | 29     | 6.14%   |
| Seagate                   | 28        | 36     | 6.14%   |
| SanDisk                   | 28        | 34     | 6.14%   |
| Unknown                   | 24        | 31     | 5.26%   |
| Micron Technology         | 16        | 18     | 3.51%   |
| Intel                     | 16        | 18     | 3.51%   |
| Crucial                   | 13        | 14     | 2.85%   |
| KIOXIA                    | 12        | 12     | 2.63%   |
| HGST                      | 10        | 10     | 2.19%   |
| China                     | 8         | 8      | 1.75%   |
| Hitachi                   | 7         | 7      | 1.54%   |
| Apple                     | 6         | 7      | 1.32%   |
| SSSTC                     | 4         | 4      | 0.88%   |
| Phison                    | 4         | 4      | 0.88%   |
| LITEON                    | 4         | 4      | 0.88%   |
| A-DATA Technology         | 4         | 4      | 0.88%   |
| Silicon Motion            | 3         | 3      | 0.66%   |
| PNY                       | 3         | 3      | 0.66%   |
| Patriot                   | 3         | 3      | 0.66%   |
| Unknown                   | 3         | 3      | 0.66%   |
| Union Memory              | 2         | 2      | 0.44%   |
| SPCC                      | 2         | 2      | 0.44%   |
| Smart                     | 2         | 2      | 0.44%   |
| SABRENT                   | 2         | 4      | 0.44%   |
| Realtek Semiconductor     | 2         | 2      | 0.44%   |
| Phison Electronics        | 2         | 2      | 0.44%   |
| Netac                     | 2         | 2      | 0.44%   |
| Micron/Crucial Technology | 2         | 3      | 0.44%   |
| LITEONIT                  | 2         | 2      | 0.44%   |
| JMicron Technology        | 2         | 2      | 0.44%   |
| Emtec                     | 2         | 2      | 0.44%   |
| VISIPRO                   | 1         | 1      | 0.22%   |
| Verbatim                  | 1         | 1      | 0.22%   |
| USB3.0                    | 1         | 1      | 0.22%   |
| UMIS                      | 1         | 1      | 0.22%   |
| Team                      | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                       | 7         | 1.46%   |
| Toshiba MQ01ABD100 1TB                          | 6         | 1.26%   |
| Samsung SSD 980 PRO 1TB                         | 5         | 1.05%   |
| Kingston SA400S37480G 480GB SSD                 | 5         | 1.05%   |
| Toshiba MQ04ABF100 1TB                          | 4         | 0.84%   |
| Seagate ST500LM021-1KJ152 500GB                 | 4         | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                  | 4         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 4         | 0.84%   |
| Samsung SSD 970 EVO Plus 500GB                  | 4         | 0.84%   |
| Kingston SA400S37240G 240GB SSD                 | 4         | 0.84%   |
| Unknown MMC Card  64GB                          | 3         | 0.63%   |
| Unknown MMC Card  128GB                         | 3         | 0.63%   |
| SK hynix NVMe SSD Drive 512GB                   | 3         | 0.63%   |
| SK hynix BC711 HFM512GD3JX013N 512GB            | 3         | 0.63%   |
| Samsung SSD 860 QVO 1TB                         | 3         | 0.63%   |
| Samsung SSD 850 EVO 250GB                       | 3         | 0.63%   |
| Samsung PM9A1 NVMe 512GB                        | 3         | 0.63%   |
| Samsung NVMe SSD Drive 512GB                    | 3         | 0.63%   |
| Micron 3400_MTFDKBA1T0TFH 1TB                   | 3         | 0.63%   |
| Kingston SA2000M81000G 1TB                      | 3         | 0.63%   |
| Crucial CT500MX500SSD1 500GB                    | 3         | 0.63%   |
| China SSD 128GB                                 | 3         | 0.63%   |
| Unknown                                         | 3         | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                | 2         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB                          | 2         | 0.42%   |
| WDC PC SN730 SDBPNTY-512G                       | 2         | 0.42%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB            | 2         | 0.42%   |
| Unknown MMC64G  64GB                            | 2         | 0.42%   |
| Unknown MMC Card  7GB                           | 2         | 0.42%   |
| Unknown MMC Card  32GB                          | 2         | 0.42%   |
| Unknown MMC Card  256GB                         | 2         | 0.42%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB          | 2         | 0.42%   |
| SK hynix PC801 NVMe 1TB                         | 2         | 0.42%   |
| SK hynix HFS256G39TND-N210A 256GB SSD           | 2         | 0.42%   |
| Seagate ST9750420AS 752GB                       | 2         | 0.42%   |
| Seagate ST2000LM007-1R8174 2TB                  | 2         | 0.42%   |
| Seagate Expansion 240GB                         | 2         | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB              | 2         | 0.42%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB | 2         | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                    | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 27        | 35     | 31.76%  |
| WDC      | 21        | 21     | 24.71%  |
| Toshiba  | 14        | 18     | 16.47%  |
| HGST     | 10        | 10     | 11.76%  |
| Hitachi  | 7         | 7      | 8.24%   |
| SABRENT  | 2         | 4      | 2.35%   |
| USB3.0   | 1         | 1      | 1.18%   |
| Unknown  | 1         | 1      | 1.18%   |
| KESU     | 1         | 1      | 1.18%   |
| HGST HTS | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 40     | 22.7%   |
| Kingston            | 22        | 24     | 15.6%   |
| SanDisk             | 16        | 20     | 11.35%  |
| WDC                 | 8         | 12     | 5.67%   |
| Crucial             | 8         | 9      | 5.67%   |
| China               | 7         | 7      | 4.96%   |
| LITEON              | 4         | 4      | 2.84%   |
| Intel               | 4         | 4      | 2.84%   |
| SK hynix            | 3         | 3      | 2.13%   |
| Patriot             | 3         | 3      | 2.13%   |
| Apple               | 3         | 3      | 2.13%   |
| A-DATA Technology   | 3         | 3      | 2.13%   |
| Toshiba             | 2         | 5      | 1.42%   |
| Smart               | 2         | 2      | 1.42%   |
| Netac               | 2         | 2      | 1.42%   |
| LITEONIT            | 2         | 2      | 1.42%   |
| Emtec               | 2         | 2      | 1.42%   |
| VISIPRO             | 1         | 1      | 0.71%   |
| Verbatim            | 1         | 1      | 0.71%   |
| Team                | 1         | 1      | 0.71%   |
| SPCC                | 1         | 1      | 0.71%   |
| Ramos Technology    | 1         | 1      | 0.71%   |
| R580                | 1         | 1      | 0.71%   |
| PNY                 | 1         | 1      | 0.71%   |
| NGFF                | 1         | 1      | 0.71%   |
| Micron Technology   | 1         | 1      | 0.71%   |
| KingSpec            | 1         | 1      | 0.71%   |
| JMicron Technology  | 1         | 1      | 0.71%   |
| HS-SSD-C100         | 1         | 1      | 0.71%   |
| GOODRAM             | 1         | 1      | 0.71%   |
| Dogfish             | 1         | 1      | 0.71%   |
| Corsair             | 1         | 1      | 0.71%   |
| BAITITON            | 1         | 1      | 0.71%   |
| Apacer              | 1         | 1      | 0.71%   |
| Unknown             | 1         | 1      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 184       | 226    | 43.6%   |
| SSD     | 126       | 163    | 29.86%  |
| HDD     | 80        | 99     | 18.96%  |
| MMC     | 26        | 32     | 6.16%   |
| Unknown | 6         | 7      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 184       | 225    | 46.23%  |
| SATA | 168       | 236    | 42.21%  |
| MMC  | 26        | 32     | 6.53%   |
| SAS  | 20        | 34     | 5.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 128       | 165    | 62.75%  |
| 0.51-1.0   | 61        | 74     | 29.9%   |
| 1.01-2.0   | 9         | 11     | 4.41%   |
| 3.01-4.0   | 3         | 9      | 1.47%   |
| 4.01-10.0  | 3         | 3      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 100       | 28.33%  |
| 101-250        | 83        | 23.51%  |
| 501-1000       | 69        | 19.55%  |
| 1001-2000      | 46        | 13.03%  |
| 51-100         | 26        | 7.37%   |
| 1-20           | 12        | 3.4%    |
| More than 3000 | 7         | 1.98%   |
| 21-50          | 5         | 1.42%   |
| 2001-3000      | 5         | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 90        | 25.42%  |
| 101-250        | 73        | 20.62%  |
| 21-50          | 59        | 16.67%  |
| 251-500        | 49        | 13.84%  |
| 51-100         | 43        | 12.15%  |
| 501-1000       | 26        | 7.34%   |
| 1001-2000      | 9         | 2.54%   |
| More than 3000 | 4         | 1.13%   |
| 2001-3000      | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| SK hynix BC711 HFM512GD3JX013N 512GB                | 2         | 2      | 8.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 4.17%   |
| VISIPRO SSD 256GB                                   | 1         | 1      | 4.17%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.17%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 4.17%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 4.17%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 4.17%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 4.17%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 4.17%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 4.17%   |
| R580 SSD 60GB                                       | 1         | 1      | 4.17%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 4.17%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 4.17%   |
| Hitachi HTS725050A7E630 500GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.17%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 4.17%   |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 4.17%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 4.17%   |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 4.17%   |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SK hynix          | 3         | 3      | 12.5%   |
| Seagate           | 3         | 3      | 12.5%   |
| Hitachi           | 3         | 3      | 12.5%   |
| Toshiba           | 2         | 2      | 8.33%   |
| SanDisk           | 2         | 2      | 8.33%   |
| HGST              | 2         | 2      | 8.33%   |
| Crucial           | 2         | 2      | 8.33%   |
| WDC               | 1         | 1      | 4.17%   |
| VISIPRO           | 1         | 1      | 4.17%   |
| R580              | 1         | 1      | 4.17%   |
| Micron Technology | 1         | 1      | 4.17%   |
| Kingston          | 1         | 1      | 4.17%   |
| BAITITON          | 1         | 1      | 4.17%   |
| A-DATA Technology | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| Hitachi | 3         | 3      | 30%     |
| Toshiba | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 43.48%  |
| SSD  | 9         | 10     | 39.13%  |
| NVMe | 4         | 4      | 17.39%  |

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
| Works    | 206       | 275    | 54.64%  |
| Detected | 148       | 228    | 39.26%  |
| Malfunc  | 23        | 24     | 6.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 207       | 45.9%   |
| AMD                            | 49        | 10.86%  |
| Samsung Electronics            | 47        | 10.42%  |
| SanDisk                        | 34        | 7.54%   |
| SK hynix                       | 25        | 5.54%   |
| Micron Technology              | 15        | 3.33%   |
| Toshiba America Info Systems   | 14        | 3.1%    |
| KIOXIA                         | 10        | 2.22%   |
| Kingston Technology Company    | 10        | 2.22%   |
| Phison Electronics             | 9         | 2%      |
| Micron/Crucial Technology      | 7         | 1.55%   |
| Solid State Storage Technology | 6         | 1.33%   |
| Silicon Motion                 | 4         | 0.89%   |
| Union Memory (Shenzhen)        | 3         | 0.67%   |
| Realtek Semiconductor          | 3         | 0.67%   |
| Apple                          | 3         | 0.67%   |
| Zhaoxin                        | 1         | 0.22%   |
| Shenzhen Longsys Electronics   | 1         | 0.22%   |
| Nvidia                         | 1         | 0.22%   |
| Marvell Technology Group       | 1         | 0.22%   |
| ADATA Technology               | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 46        | 9.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 36        | 7.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 5.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 24        | 4.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 3.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 18        | 3.74%   |
| Micron Non-Volatile memory controller                                          | 15        | 3.12%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 14        | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 2.49%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 2.49%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 2.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 2.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 1.87%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 9         | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 1.87%   |
| SanDisk Non-Volatile memory controller                                         | 8         | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 8         | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 1.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.46%   |
| Solid State Storage Non-Volatile memory controller                             | 6         | 1.25%   |
| SK hynix Non-Volatile memory controller                                        | 6         | 1.25%   |
| Intel SSD 660P Series                                                          | 6         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.25%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 0.83%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.83%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4         | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.83%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 0.62%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.62%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.62%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 222       | 48.47%  |
| NVMe | 184       | 40.17%  |
| RAID | 43        | 9.39%   |
| IDE  | 9         | 1.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 266       | 76.44%  |
| AMD          | 81        | 23.28%  |
| CentaurHauls | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 4.02%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 4.02%   |
| Intel 12th Gen Core i7-12700H                 | 12        | 3.45%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 2.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 2.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 2.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.01%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 2.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.44%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 1.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.15%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.15%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.15%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.86%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.86%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 3         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.86%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.86%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.86%   |
| Intel 12th Gen Core i7-1255U                  | 3         | 0.86%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz       | 3         | 0.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.86%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.86%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.86%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.57%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.57%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 2         | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.57%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.57%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 0.57%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 78        | 22.41%  |
| Intel Core i5           | 73        | 20.98%  |
| Other                   | 67        | 19.25%  |
| AMD Ryzen 7             | 32        | 9.2%    |
| AMD Ryzen 5             | 22        | 6.32%   |
| Intel Celeron           | 17        | 4.89%   |
| Intel Core i3           | 12        | 3.45%   |
| AMD Ryzen 9             | 6         | 1.72%   |
| Intel Core 2 Duo        | 5         | 1.44%   |
| AMD Ryzen 3             | 5         | 1.44%   |
| Intel Pentium Silver    | 4         | 1.15%   |
| Intel Pentium           | 4         | 1.15%   |
| Intel Core i9           | 3         | 0.86%   |
| AMD Ryzen 5 PRO         | 3         | 0.86%   |
| AMD A8                  | 3         | 0.86%   |
| Intel Core m3           | 2         | 0.57%   |
| AMD Ryzen 7 PRO         | 2         | 0.57%   |
| AMD E                   | 2         | 0.57%   |
| AMD A6                  | 2         | 0.57%   |
| Intel Core 2            | 1         | 0.29%   |
| Intel Celeron Dual-Core | 1         | 0.29%   |
| AMD PRO A10             | 1         | 0.29%   |
| AMD FX                  | 1         | 0.29%   |
| AMD A4                  | 1         | 0.29%   |
| AMD A10                 | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 123       | 35.34%  |
| 2      | 116       | 33.33%  |
| 8      | 44        | 12.64%  |
| 6      | 42        | 12.07%  |
| 14     | 14        | 4.02%   |
| 12     | 4         | 1.15%   |
| 10     | 4         | 1.15%   |
| 5      | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 348       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 300       | 85.96%  |
| 1      | 49        | 14.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 348       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 35.59%  |
| 0x806c1    | 22        | 6.21%   |
| 0x306a9    | 20        | 5.65%   |
| 0x906a3    | 16        | 4.52%   |
| 0x0a50000c | 15        | 4.24%   |
| 0x806ea    | 14        | 3.95%   |
| 0x08608103 | 11        | 3.11%   |
| 0x08600106 | 10        | 2.82%   |
| 0x906ea    | 9         | 2.54%   |
| 0x406e3    | 8         | 2.26%   |
| 0x806ec    | 7         | 1.98%   |
| 0x806e9    | 7         | 1.98%   |
| 0x306c3    | 7         | 1.98%   |
| 0x206a7    | 7         | 1.98%   |
| 0xa0652    | 5         | 1.41%   |
| 0x806d1    | 5         | 1.41%   |
| 0x706a8    | 5         | 1.41%   |
| 0x40651    | 5         | 1.41%   |
| 0x906e9    | 4         | 1.13%   |
| 0x906a4    | 4         | 1.13%   |
| 0x706a1    | 4         | 1.13%   |
| 0x08608102 | 4         | 1.13%   |
| 0x08108109 | 4         | 1.13%   |
| 0x806c2    | 3         | 0.85%   |
| 0x506c9    | 3         | 0.85%   |
| 0x40661    | 3         | 0.85%   |
| 0x20652    | 3         | 0.85%   |
| 0x08600103 | 2         | 0.56%   |
| 0x0810100b | 2         | 0.56%   |
| 0x03000027 | 2         | 0.56%   |
| 0x806eb    | 1         | 0.28%   |
| 0x806a1    | 1         | 0.28%   |
| 0x706e5    | 1         | 0.28%   |
| 0x6fd      | 1         | 0.28%   |
| 0x6fb      | 1         | 0.28%   |
| 0x6f6      | 1         | 0.28%   |
| 0x506e3    | 1         | 0.28%   |
| 0x306d4    | 1         | 0.28%   |
| 0x30673    | 1         | 0.28%   |
| 0x1067a    | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 66        | 18.91%  |
| TigerLake        | 36        | 10.32%  |
| IvyBridge        | 36        | 10.32%  |
| Unknown          | 28        | 8.02%   |
| Zen 3            | 26        | 7.45%   |
| Haswell          | 23        | 6.59%   |
| Alderlake Hybrid | 19        | 5.44%   |
| Zen 2            | 15        | 4.3%    |
| Skylake          | 15        | 4.3%    |
| Goldmont plus    | 15        | 4.3%    |
| SandyBridge      | 13        | 3.72%   |
| Zen+             | 8         | 2.29%   |
| IceLake          | 7         | 2.01%   |
| CometLake        | 7         | 2.01%   |
| Westmere         | 5         | 1.43%   |
| Goldmont         | 4         | 1.15%   |
| Core             | 4         | 1.15%   |
| Penryn           | 3         | 0.86%   |
| Broadwell        | 3         | 0.86%   |
| Zen              | 2         | 0.57%   |
| Silvermont       | 2         | 0.57%   |
| Puma             | 2         | 0.57%   |
| Piledriver       | 2         | 0.57%   |
| K10 Llano        | 2         | 0.57%   |
| Excavator        | 2         | 0.57%   |
| Bobcat           | 2         | 0.57%   |
| Steamroller      | 1         | 0.29%   |
| Nehalem          | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 249       | 53.09%  |
| Nvidia  | 117       | 24.95%  |
| AMD     | 102       | 21.75%  |
| Zhaoxin | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 34        | 7.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 30        | 6.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 20        | 4.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 17        | 3.53%   |
| Intel UHD Graphics 620                                                                | 16        | 3.33%   |
| AMD Lucienne                                                                          | 16        | 3.33%   |
| AMD Renoir                                                                            | 15        | 3.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 13        | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 12        | 2.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 12        | 2.49%   |
| Intel HD Graphics 620                                                                 | 11        | 2.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 11        | 2.29%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 9         | 1.87%   |
| Intel HD Graphics 630                                                                 | 8         | 1.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 1.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 7         | 1.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 7         | 1.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 1.46%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 7         | 1.46%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 6         | 1.25%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 6         | 1.25%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 5         | 1.04%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 5         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 0.83%   |
| Intel HD Graphics 500                                                                 | 4         | 0.83%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 4         | 0.83%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 4         | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 4         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 3         | 0.62%   |
| Nvidia GM108M [GeForce MX130]                                                         | 3         | 0.62%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 3         | 0.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 0.62%   |
| Intel HD Graphics 5500                                                                | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 145       | 41.55%  |
| Intel + Nvidia | 82        | 23.5%   |
| 1 x AMD        | 55        | 15.76%  |
| Intel + AMD    | 21        | 6.02%   |
| AMD + Nvidia   | 18        | 5.16%   |
| 1 x Nvidia     | 17        | 4.87%   |
| 2 x AMD        | 8         | 2.29%   |
| Other          | 1         | 0.29%   |
| 2 x Nvidia     | 1         | 0.29%   |
| 1 x Zhaoxin    | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 262       | 74.64%  |
| Proprietary | 83        | 23.65%  |
| Unknown     | 6         | 1.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 254       | 72.16%  |
| 0.01-0.5   | 39        | 11.08%  |
| 1.01-2.0   | 27        | 7.67%   |
| 3.01-4.0   | 11        | 3.13%   |
| 0.51-1.0   | 10        | 2.84%   |
| 5.01-6.0   | 5         | 1.42%   |
| 7.01-8.0   | 4         | 1.14%   |
| 8.01-16.0  | 2         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 67        | 16.26%  |
| Chimei Innolux          | 66        | 16.02%  |
| AU Optronics            | 66        | 16.02%  |
| LG Display              | 53        | 12.86%  |
| Samsung Electronics     | 38        | 9.22%   |
| Sharp                   | 16        | 3.88%   |
| Goldstar                | 13        | 3.16%   |
| Dell                    | 12        | 2.91%   |
| Hewlett-Packard         | 9         | 2.18%   |
| Apple                   | 9         | 2.18%   |
| Chi Mei Optoelectronics | 7         | 1.7%    |
| Lenovo                  | 6         | 1.46%   |
| CSO                     | 6         | 1.46%   |
| BenQ                    | 6         | 1.46%   |
| Philips                 | 5         | 1.21%   |
| InfoVision              | 5         | 1.21%   |
| Acer                    | 5         | 1.21%   |
| SLD                     | 2         | 0.49%   |
| Sceptre Tech            | 2         | 0.49%   |
| PANDA                   | 2         | 0.49%   |
| IBM                     | 2         | 0.49%   |
| HKC                     | 2         | 0.49%   |
| ASUSTek Computer        | 2         | 0.49%   |
| Vizio                   | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| MSI                     | 1         | 0.24%   |
| HUAWEI                  | 1         | 0.24%   |
| Gigabyte Technology     | 1         | 0.24%   |
| Gateway                 | 1         | 0.24%   |
| CVT                     | 1         | 0.24%   |
| CPT                     | 1         | 0.24%   |
| Belinea                 | 1         | 0.24%   |
| AOC                     | 1         | 0.24%   |
| Ancor Communications    | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 7         | 1.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 4         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 4         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 4         | 0.95%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 3         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 3         | 0.71%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch              | 3         | 0.71%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 3         | 0.71%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch          | 3         | 0.71%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 3         | 0.71%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 3         | 0.71%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.71%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                      | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 2         | 0.48%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                   | 2         | 0.48%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.48%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 2         | 0.48%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 2         | 0.48%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                     | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.48%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE0931 2240x1400 302x189mm 14.0-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE0731 1366x768 256x144mm 11.6-inch                      | 2         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 199       | 52.37%  |
| 1366x768 (WXGA)    | 80        | 21.05%  |
| 2560x1440 (QHD)    | 20        | 5.26%   |
| 3840x2160 (4K)     | 13        | 3.42%   |
| 1600x900 (HD+)     | 12        | 3.16%   |
| 2560x1600          | 10        | 2.63%   |
| 1920x1200 (WUXGA)  | 10        | 2.63%   |
| 2880x1800          | 9         | 2.37%   |
| 2560x1080          | 4         | 1.05%   |
| 1680x1050 (WSXGA+) | 4         | 1.05%   |
| 3440x1440          | 2         | 0.53%   |
| 2520x1680          | 2         | 0.53%   |
| 2256x1504          | 2         | 0.53%   |
| 2240x1400          | 2         | 0.53%   |
| 1280x800 (WXGA)    | 2         | 0.53%   |
| 1024x768 (XGA)     | 2         | 0.53%   |
| 3840x1080          | 1         | 0.26%   |
| 3072x1920          | 1         | 0.26%   |
| 2160x1440          | 1         | 0.26%   |
| 2160x1350          | 1         | 0.26%   |
| 1920x540           | 1         | 0.26%   |
| 1440x900 (WXGA+)   | 1         | 0.26%   |
| 1280x1024 (SXGA)   | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 175       | 42.17%  |
| 14     | 51        | 12.29%  |
| 13     | 45        | 10.84%  |
| 17     | 33        | 7.95%   |
| 16     | 16        | 3.86%   |
| 27     | 15        | 3.61%   |
| 24     | 15        | 3.61%   |
| 23     | 13        | 3.13%   |
| 21     | 12        | 2.89%   |
| 12     | 7         | 1.69%   |
| 11     | 7         | 1.69%   |
| 34     | 5         | 1.2%    |
| 31     | 4         | 0.96%   |
| 54     | 2         | 0.48%   |
| 25     | 2         | 0.48%   |
| 22     | 2         | 0.48%   |
| 84     | 1         | 0.24%   |
| 78     | 1         | 0.24%   |
| 65     | 1         | 0.24%   |
| 60     | 1         | 0.24%   |
| 49     | 1         | 0.24%   |
| 42     | 1         | 0.24%   |
| 32     | 1         | 0.24%   |
| 28     | 1         | 0.24%   |
| 26     | 1         | 0.24%   |
| 20     | 1         | 0.24%   |
| 18     | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 253       | 61.86%  |
| 351-400     | 42        | 10.27%  |
| 501-600     | 41        | 10.02%  |
| 201-300     | 38        | 9.29%   |
| 401-500     | 16        | 3.91%   |
| 601-700     | 6         | 1.47%   |
| 701-800     | 5         | 1.22%   |
| 1001-1500   | 5         | 1.22%   |
| 1501-2000   | 2         | 0.49%   |
| 901-1000    | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 297       | 83.9%   |
| 16/10 | 42        | 11.86%  |
| 21/9  | 6         | 1.69%   |
| 3/2   | 5         | 1.41%   |
| 4/3   | 2         | 0.56%   |
| 5/4   | 1         | 0.28%   |
| 32/9  | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 179       | 43.77%  |
| 81-90          | 77        | 18.83%  |
| 201-250        | 31        | 7.58%   |
| 121-130        | 31        | 7.58%   |
| 71-80          | 20        | 4.89%   |
| 301-350        | 16        | 3.91%   |
| 111-120        | 11        | 2.69%   |
| 351-500        | 9         | 2.2%    |
| 51-60          | 7         | 1.71%   |
| More than 1000 | 6         | 1.47%   |
| 61-70          | 6         | 1.47%   |
| 251-300        | 6         | 1.47%   |
| 151-200        | 4         | 0.98%   |
| 141-150        | 2         | 0.49%   |
| 501-1000       | 2         | 0.49%   |
| 131-140        | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 197       | 48.88%  |
| 101-120       | 90        | 22.33%  |
| 51-100        | 53        | 13.15%  |
| 161-240       | 45        | 11.17%  |
| More than 240 | 12        | 2.98%   |
| 1-50          | 6         | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 272       | 77.05%  |
| 2     | 61        | 17.28%  |
| 3     | 10        | 2.83%   |
| 0     | 7         | 1.98%   |
| 4     | 3         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 203       | 36.98%  |
| Intel                             | 189       | 34.43%  |
| Qualcomm Atheros                  | 56        | 10.2%   |
| Broadcom                          | 31        | 5.65%   |
| MediaTek                          | 25        | 4.55%   |
| ASIX Electronics                  | 6         | 1.09%   |
| TP-Link                           | 4         | 0.73%   |
| Sierra Wireless                   | 4         | 0.73%   |
| Samsung Electronics               | 4         | 0.73%   |
| Ralink Technology                 | 3         | 0.55%   |
| Broadcom Limited                  | 3         | 0.55%   |
| Qualcomm                          | 2         | 0.36%   |
| Marvell Technology Group          | 2         | 0.36%   |
| Huawei Technologies               | 2         | 0.36%   |
| Google                            | 2         | 0.36%   |
| DisplayLink                       | 2         | 0.36%   |
| Apple                             | 2         | 0.36%   |
| Xiaomi                            | 1         | 0.18%   |
| Nvidia                            | 1         | 0.18%   |
| Motorola PCS                      | 1         | 0.18%   |
| Lenovo                            | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| Dell                              | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| Belkin Components                 | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 18.59%  |
| Intel Wi-Fi 6 AX201                                               | 26        | 4.06%   |
| Intel Wi-Fi 6 AX200                                               | 23        | 3.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 22        | 3.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 19        | 2.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 18        | 2.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.5%    |
| Intel Wireless 7260                                               | 13        | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12        | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.56%   |
| Intel Wireless 7265                                               | 9         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 1.09%   |
| Realtek 802.11n WLAN Adapter                                      | 7         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.09%   |
| Intel Wireless 8260                                               | 6         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.63%   |
| Intel Wireless 3165                                               | 4         | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 179       | 49.31%  |
| Realtek Semiconductor             | 72        | 19.83%  |
| Qualcomm Atheros                  | 44        | 12.12%  |
| MediaTek                          | 25        | 6.89%   |
| Broadcom                          | 25        | 6.89%   |
| Sierra Wireless                   | 4         | 1.1%    |
| Ralink Technology                 | 3         | 0.83%   |
| Broadcom Limited                  | 3         | 0.83%   |
| TP-Link                           | 2         | 0.55%   |
| Qualcomm                          | 2         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.28%   |
| Dell                              | 1         | 0.28%   |
| D-Link System                     | 1         | 0.28%   |
| Belkin Components                 | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                           | 26        | 7.12%   |
| Intel Wi-Fi 6 AX200                                           | 23        | 6.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 22        | 6.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 19        | 5.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 18        | 4.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 16        | 4.38%   |
| Intel Wireless 7260                                           | 13        | 3.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 13        | 3.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 12        | 3.29%   |
| Intel Wireless 8265 / 8275                                    | 11        | 3.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 10        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 10        | 2.74%   |
| Intel Wireless 7265                                           | 9         | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 9         | 2.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 8         | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 8         | 2.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 7         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                  | 7         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 7         | 1.92%   |
| Intel Wireless 8260                                           | 6         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5         | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 5         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                | 5         | 1.37%   |
| Intel Centrino Advanced-N 6235                                | 5         | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 4         | 1.1%    |
| Intel Wireless 3165                                           | 4         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4         | 1.1%    |
| Broadcom BCM43228 802.11a/b/g/n                               | 4         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                 | 4         | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 3         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 3         | 0.82%   |
| Realtek 802.11ac NIC                                          | 3         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 3         | 0.82%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 3         | 0.82%   |
| Sierra Wireless EM7305 Modem                                  | 2         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 2         | 0.55%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 0.55%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 2         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 165       | 62.03%  |
| Intel                    | 54        | 20.3%   |
| Qualcomm Atheros         | 13        | 4.89%   |
| Broadcom                 | 9         | 3.38%   |
| ASIX Electronics         | 6         | 2.26%   |
| Samsung Electronics      | 4         | 1.5%    |
| TP-Link                  | 2         | 0.75%   |
| Marvell Technology Group | 2         | 0.75%   |
| Huawei Technologies      | 2         | 0.75%   |
| Google                   | 2         | 0.75%   |
| DisplayLink              | 2         | 0.75%   |
| Apple                    | 2         | 0.75%   |
| Xiaomi                   | 1         | 0.38%   |
| Nvidia                   | 1         | 0.38%   |
| Lenovo                   | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 43.59%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 6.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 5.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 5.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 1.83%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.83%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.47%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.1%    |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.1%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.73%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.73%   |
| DisplayLink LAPDOCK                                               | 2         | 0.73%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.37%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.37%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.37%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.37%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.37%   |
| Lenovo Android                                                    | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 347       | 57.93%  |
| Ethernet | 250       | 41.74%  |
| Modem    | 1         | 0.17%   |
| Unknown  | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 302       | 81.4%   |
| Ethernet | 69        | 18.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 226       | 64.94%  |
| 1     | 110       | 31.61%  |
| 0     | 11        | 3.16%   |
| 3     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 263       | 75.36%  |
| Yes  | 86        | 24.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 48.85%  |
| Realtek Semiconductor           | 42        | 13.77%  |
| Qualcomm Atheros Communications | 23        | 7.54%   |
| Broadcom                        | 17        | 5.57%   |
| IMC Networks                    | 16        | 5.25%   |
| Foxconn / Hon Hai               | 16        | 5.25%   |
| Lite-On Technology              | 15        | 4.92%   |
| Apple                           | 6         | 1.97%   |
| Toshiba                         | 4         | 1.31%   |
| Realtek                         | 4         | 1.31%   |
| Dell                            | 3         | 0.98%   |
| Cambridge Silicon Radio         | 3         | 0.98%   |
| Hewlett-Packard                 | 2         | 0.66%   |
| TP-Link                         | 1         | 0.33%   |
| Foxconn International           | 1         | 0.33%   |
| Edimax Technology               | 1         | 0.33%   |
| ASUSTek Computer                | 1         | 0.33%   |
| Alps Electric                   | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 53        | 17.38%  |
| Intel Bluetooth wireless interface                  | 41        | 13.44%  |
| Realtek Bluetooth Radio                             | 33        | 10.82%  |
| Intel AX200 Bluetooth                               | 22        | 7.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 6.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 2.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 2.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 2.62%   |
| Lite-On Wireless_Device                             | 8         | 2.62%   |
| IMC Networks Wireless_Device                        | 8         | 2.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 2.3%    |
| Intel AX210 Bluetooth                               | 7         | 2.3%    |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.64%   |
| Apple Bluetooth Host Controller                     | 5         | 1.64%   |
| Realtek Bluetooth Radio                             | 4         | 1.31%   |
| Lite-On Bluetooth Device                            | 4         | 1.31%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.31%   |
| IMC Networks Bluetooth Radio                        | 3         | 0.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.98%   |
| IMC Networks Bluetooth Device                       | 2         | 0.66%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.66%   |
| TP-Link TPuLink UB500 Adapter                       | 1         | 0.33%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.33%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.33%   |
| Toshiba Bluetooth Device                            | 1         | 0.33%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.33%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.33%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.33%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.33%   |
| Lite-On BCM43142A0                                  | 1         | 0.33%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.33%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.33%   |
| IMC Networks Bluetooth                              | 1         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 264       | 59.06%  |
| AMD                   | 85        | 19.02%  |
| Nvidia                | 67        | 14.99%  |
| C-Media Electronics   | 5         | 1.12%   |
| Realtek Semiconductor | 2         | 0.45%   |
| Razer USA             | 2         | 0.45%   |
| JMTek                 | 2         | 0.45%   |
| Apple                 | 2         | 0.45%   |
| ZOOM                  | 1         | 0.22%   |
| Zhaoxin               | 1         | 0.22%   |
| TerraTec Electronic   | 1         | 0.22%   |
| Sony                  | 1         | 0.22%   |
| Silicon Motion        | 1         | 0.22%   |
| Princeton Technology  | 1         | 0.22%   |
| Plantronics           | 1         | 0.22%   |
| Logitech              | 1         | 0.22%   |
| Lenovo                | 1         | 0.22%   |
| Hewlett-Packard       | 1         | 0.22%   |
| GN Netcom             | 1         | 0.22%   |
| Focusrite-Novation    | 1         | 0.22%   |
| DisplayLink           | 1         | 0.22%   |
| Cyber Acoustics       | 1         | 0.22%   |
| Creative Technology   | 1         | 0.22%   |
| Corsair               | 1         | 0.22%   |
| Blue Microphones      | 1         | 0.22%   |
| Arturia               | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 68        | 12.55%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 8.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 42        | 7.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41        | 7.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 36        | 6.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 23        | 4.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16        | 2.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 15        | 2.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.66%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.48%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1.48%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 1.48%   |
| Intel CM238 HD Audio Controller                                            | 8         | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 1.48%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.29%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.11%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 1.11%   |
| Nvidia Audio device                                                        | 6         | 1.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.55%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.55%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.55%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.55%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 97        | 32.77%  |
| SK hynix            | 61        | 20.61%  |
| Micron Technology   | 34        | 11.49%  |
| Crucial             | 24        | 8.11%   |
| Kingston            | 19        | 6.42%   |
| Unknown (ABCD)      | 10        | 3.38%   |
| A-DATA Technology   | 7         | 2.36%   |
| Elpida              | 5         | 1.69%   |
| Unknown             | 5         | 1.69%   |
| Unknown             | 4         | 1.35%   |
| Wilk                | 3         | 1.01%   |
| Transcend           | 2         | 0.68%   |
| Ramaxel Technology  | 2         | 0.68%   |
| Nanya Technology    | 2         | 0.68%   |
| GOODRAM             | 2         | 0.68%   |
| Corsair             | 2         | 0.68%   |
| Unknown (8A02)      | 1         | 0.34%   |
| Teikon              | 1         | 0.34%   |
| Team                | 1         | 0.34%   |
| Super Talent        | 1         | 0.34%   |
| Smart               | 1         | 0.34%   |
| Silicon Power       | 1         | 0.34%   |
| Shenzhen Zhongteng  | 1         | 0.34%   |
| Shenzhen WODPOSIT   | 1         | 0.34%   |
| SHARETRONIC         | 1         | 0.34%   |
| Qimonda             | 1         | 0.34%   |
| Patriot             | 1         | 0.34%   |
| Imation             | 1         | 0.34%   |
| Goldkey             | 1         | 0.34%   |
| G.Skill             | 1         | 0.34%   |
| Essencore Limited   | 1         | 0.34%   |
| Atermiter           | 1         | 0.34%   |
| AMD                 | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 2.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.62%   |
| Unknown                                                          | 5         | 1.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.3%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 0.97%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.97%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 0.97%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.97%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s             | 2         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.65%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.65%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.65%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.65%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.65%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 146       | 59.59%  |
| DDR3   | 59        | 24.08%  |
| LPDDR4 | 22        | 8.98%   |
| DDR5   | 8         | 3.27%   |
| LPDDR5 | 3         | 1.22%   |
| LPDDR3 | 3         | 1.22%   |
| DDR2   | 3         | 1.22%   |
| SDRAM  | 1         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 214       | 84.92%  |
| Row Of Chips | 33        | 13.1%   |
| DIMM         | 2         | 0.79%   |
| Chip         | 2         | 0.79%   |
| Unknown      | 1         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 119       | 45.08%  |
| 4096  | 68        | 25.76%  |
| 16384 | 49        | 18.56%  |
| 2048  | 13        | 4.92%   |
| 32768 | 12        | 4.55%   |
| 1024  | 3         | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 87        | 33.98%  |
| 2667    | 46        | 17.97%  |
| 1600    | 45        | 17.58%  |
| 2400    | 23        | 8.98%   |
| 1333    | 9         | 3.52%   |
| 4800    | 8         | 3.13%   |
| 4267    | 8         | 3.13%   |
| 1334    | 6         | 2.34%   |
| 2133    | 5         | 1.95%   |
| 1867    | 4         | 1.56%   |
| 6400    | 3         | 1.17%   |
| 667     | 3         | 1.17%   |
| 4266    | 2         | 0.78%   |
| 8400    | 1         | 0.39%   |
| 3266    | 1         | 0.39%   |
| 2933    | 1         | 0.39%   |
| 2666    | 1         | 0.39%   |
| 2048    | 1         | 0.39%   |
| 1067    | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson L3110 Series   | 1         | 25%     |
| Seiko Epson ET-2700 Series | 1         | 25%     |
| Canon iP2600 series        | 1         | 25%     |
| Brother HL-2230 series     | 1         | 25%     |

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
| Chicony Electronics                    | 69        | 21.36%  |
| Acer                                   | 36        | 11.15%  |
| Microdia                               | 34        | 10.53%  |
| IMC Networks                           | 32        | 9.91%   |
| Quanta                                 | 30        | 9.29%   |
| Realtek Semiconductor                  | 23        | 7.12%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.33%   |
| Sunplus Innovation Technology          | 11        | 3.41%   |
| Luxvisions Innotech Limited            | 11        | 3.41%   |
| Logitech                               | 8         | 2.48%   |
| Lite-On Technology                     | 8         | 2.48%   |
| Syntek                                 | 6         | 1.86%   |
| Apple                                  | 5         | 1.55%   |
| Y Media                                | 4         | 1.24%   |
| Silicon Motion                         | 4         | 1.24%   |
| Alcor Micro                            | 3         | 0.93%   |
| Suyin                                  | 2         | 0.62%   |
| SunplusIT                              | 2         | 0.62%   |
| Samsung Electronics                    | 2         | 0.62%   |
| icSpring                               | 2         | 0.62%   |
| Z-Star Microelectronics                | 1         | 0.31%   |
| Xiaomi                                 | 1         | 0.31%   |
| USB Camera CS                          | 1         | 0.31%   |
| STEREOLABS                             | 1         | 0.31%   |
| Sonix Technology                       | 1         | 0.31%   |
| SN0002                                 | 1         | 0.31%   |
| ShineTech                              | 1         | 0.31%   |
| Novatek Microelectronics               | 1         | 0.31%   |
| Lenovo                                 | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| Huawei Technologies                    | 1         | 0.31%   |
| HRY                                    | 1         | 0.31%   |
| Goodong Industry                       | 1         | 0.31%   |
| Goodong                                | 1         | 0.31%   |
| GEMBIRD                                | 1         | 0.31%   |
| eMPIA Technology                       | 1         | 0.31%   |
| ARC International                      | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 17        | 5.25%   |
| Microdia Integrated_Webcam_HD                                   | 16        | 4.94%   |
| Acer Integrated Camera                                          | 15        | 4.63%   |
| IMC Networks Integrated Camera                                  | 13        | 4.01%   |
| Quanta HP TrueVision HD Camera                                  | 8         | 2.47%   |
| Chicony HD Webcam                                               | 8         | 2.47%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 2.16%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 2.16%   |
| Chicony HD User Facing                                          | 7         | 2.16%   |
| Realtek Integrated_Webcam_HD                                    | 6         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 1.54%   |
| Y Media USB Camera                                              | 4         | 1.23%   |
| Syntek Integrated Camera                                        | 4         | 1.23%   |
| Quanta HD User Facing                                           | 4         | 1.23%   |
| Quanta ACER HD User Facing                                      | 4         | 1.23%   |
| Microdia Integrated_Webcam_FHD                                  | 4         | 1.23%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 1.23%   |
| Chicony USB2.0 Camera                                           | 4         | 1.23%   |
| Realtek USB Camera                                              | 3         | 0.93%   |
| Quanta HP Wide Vision HD Camera                                 | 3         | 0.93%   |
| Quanta HD Webcam                                                | 3         | 0.93%   |
| Microdia Webcam Vitade AF                                       | 3         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                         | 3         | 0.93%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 0.93%   |
| Chicony HP Truevision HD                                        | 3         | 0.93%   |
| Chicony HP HD Camera                                            | 3         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 3         | 0.93%   |
| Acer ThinkPad Integrated Camera                                 | 3         | 0.93%   |
| Acer Lenovo EasyCamera                                          | 3         | 0.93%   |
| Acer HD Webcam                                                  | 3         | 0.93%   |
| Silicon Motion WebCam SC-13HDL11939N                            | 2         | 0.62%   |
| Samsung Galaxy A5 (MTP)                                         | 2         | 0.62%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 0.62%   |
| Realtek Laptop Camera                                           | 2         | 0.62%   |
| Realtek Integrated Webcam HD                                    | 2         | 0.62%   |
| Realtek HD Webcam - Realtek                                     | 2         | 0.62%   |
| Quanta USB2.0 HD UVC WebCam                                     | 2         | 0.62%   |
| Quanta ov9734_techfront_camera                                  | 2         | 0.62%   |
| Quanta HD Camera                                                | 2         | 0.62%   |
| Microdia USB 2.0 Camera                                         | 2         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 22        | 31.43%  |
| Synaptics                  | 17        | 24.29%  |
| Validity Sensors           | 16        | 22.86%  |
| Elan Microelectronics      | 8         | 11.43%  |
| Upek                       | 3         | 4.29%   |
| AuthenTec                  | 2         | 2.86%   |
| STMicroelectronics         | 1         | 1.43%   |
| Focal-systems.Corp         | 1         | 1.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 19        | 27.14%  |
| Elan ELAN:ARM-M4                                           | 5         | 7.14%   |
| Unknown                                                    | 5         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 5.71%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 5.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 5.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 4.29%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 4.29%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 4.29%   |
| Elan ELAN:Fingerprint                                      | 3         | 4.29%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 2         | 2.86%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 2.86%   |
| Validity Sensors VFS491                                    | 1         | 1.43%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.43%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 1.43%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.43%   |
| Synaptics  WBDI                                            | 1         | 1.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.43%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.43%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.43%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.43%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 11        | 44%     |
| Alcor Micro           | 7         | 28%     |
| Upek                  | 3         | 12%     |
| O2 Micro              | 1         | 4%      |
| Lenovo                | 1         | 4%      |
| BIT4ID                | 1         | 4%      |
| Advanced Card Systems | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 28%     |
| Broadcom 5880                                                                | 4         | 16%     |
| Broadcom 58200                                                               | 4         | 16%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 12%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4%      |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4%      |
| BIT4ID miniLector EVO                                                        | 1         | 4%      |
| Advanced Card Systems ACR39U                                                 | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 223       | 62.82%  |
| 1     | 102       | 28.73%  |
| 2     | 27        | 7.61%   |
| 9     | 1         | 0.28%   |
| 4     | 1         | 0.28%   |
| 3     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 69        | 42.86%  |
| Chipcard                 | 23        | 14.29%  |
| Graphics card            | 21        | 13.04%  |
| Multimedia controller    | 12        | 7.45%   |
| Camera                   | 11        | 6.83%   |
| Net/wireless             | 9         | 5.59%   |
| Sound                    | 4         | 2.48%   |
| Bluetooth                | 4         | 2.48%   |
| Communication controller | 3         | 1.86%   |
| Network                  | 2         | 1.24%   |
| Net/ethernet             | 2         | 1.24%   |
| Modem                    | 1         | 0.62%   |

