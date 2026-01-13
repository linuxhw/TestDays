Ubuntu MATE - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE/Notebook/README.md).

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

Total: 3258

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | Notebook    | [518e12c3e9](https://linux-hardware.org/?probe=518e12c3e9) | Jan 03, 2026 |
| Unknown       | Unknown                     | Desktop     | [1a5e59050e](https://linux-hardware.org/?probe=1a5e59050e) | Jan 02, 2026 |
| Notebook      | NJx0MU                      | Notebook    | [37c951e36e](https://linux-hardware.org/?probe=37c951e36e) | Jan 02, 2026 |
| Notebook      | NJx0MU                      | Notebook    | [d046c32fd7](https://linux-hardware.org/?probe=d046c32fd7) | Dec 31, 2025 |
| HP            | 350 G1                      | Notebook    | [b5560a9d30](https://linux-hardware.org/?probe=b5560a9d30) | Dec 29, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [5129f79e54](https://linux-hardware.org/?probe=5129f79e54) | Dec 29, 2025 |
| Acer          | Aspire A515-57G             | Notebook    | [0f8d86dcb8](https://linux-hardware.org/?probe=0f8d86dcb8) | Dec 27, 2025 |
| Toshiba       | Satellite P755              | Notebook    | [2d532f5177](https://linux-hardware.org/?probe=2d532f5177) | Dec 27, 2025 |
| Unknown       | Unknown                     | Notebook    | [d2e0d6b442](https://linux-hardware.org/?probe=d2e0d6b442) | Dec 24, 2025 |
| ASUSTek       | G53SX                       | Notebook    | [dd6c3b82ef](https://linux-hardware.org/?probe=dd6c3b82ef) | Dec 21, 2025 |
| GPU Compan... | GWNR71517                   | Notebook    | [2af225eec9](https://linux-hardware.org/?probe=2af225eec9) | Dec 20, 2025 |
| ASUSTek       | B85M-E                      | Desktop     | [4d0f3f6dff](https://linux-hardware.org/?probe=4d0f3f6dff) | Dec 19, 2025 |
| Avell High... | A72 HYB                     | Notebook    | [4991202ec8](https://linux-hardware.org/?probe=4991202ec8) | Dec 16, 2025 |
| Avell High... | A72 HYB                     | Notebook    | [f6b91a8e3c](https://linux-hardware.org/?probe=f6b91a8e3c) | Dec 14, 2025 |
| ASUSTek       | K56CA                       | Notebook    | [2f2ee8e317](https://linux-hardware.org/?probe=2f2ee8e317) | Dec 10, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [f4c2d53286](https://linux-hardware.org/?probe=f4c2d53286) | Dec 09, 2025 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [51e30de904](https://linux-hardware.org/?probe=51e30de904) | Dec 08, 2025 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [c07d84707f](https://linux-hardware.org/?probe=c07d84707f) | Dec 08, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [90779328cf](https://linux-hardware.org/?probe=90779328cf) | Dec 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [065f057e4f](https://linux-hardware.org/?probe=065f057e4f) | Dec 07, 2025 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [0cfa2d946a](https://linux-hardware.org/?probe=0cfa2d946a) | Dec 07, 2025 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [0c1c1825e3](https://linux-hardware.org/?probe=0c1c1825e3) | Dec 06, 2025 |
| Unknown       | WZBTDT1 R110                | Desktop     | [7de02d798e](https://linux-hardware.org/?probe=7de02d798e) | Dec 05, 2025 |
| ASUSTek       | G53SX                       | Notebook    | [2e780a44f8](https://linux-hardware.org/?probe=2e780a44f8) | Dec 05, 2025 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [941313a156](https://linux-hardware.org/?probe=941313a156) | Dec 03, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fb4d126e76](https://linux-hardware.org/?probe=fb4d126e76) | Dec 03, 2025 |
| Unknown       | Unknown                     | Notebook    | [ee12208a62](https://linux-hardware.org/?probe=ee12208a62) | Nov 30, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [dec7e38f82](https://linux-hardware.org/?probe=dec7e38f82) | Nov 29, 2025 |
| Dell          | Latitude E5540              | Notebook    | [f6c018e24b](https://linux-hardware.org/?probe=f6c018e24b) | Nov 29, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [e626dd69dc](https://linux-hardware.org/?probe=e626dd69dc) | Nov 29, 2025 |
| Dell          | Latitude E5540              | Notebook    | [5d616bcf7e](https://linux-hardware.org/?probe=5d616bcf7e) | Nov 28, 2025 |
| Dell          | Latitude E5540              | Notebook    | [a646884c9f](https://linux-hardware.org/?probe=a646884c9f) | Nov 28, 2025 |
| Dell          | Latitude E5540              | Notebook    | [8e7bd4a66c](https://linux-hardware.org/?probe=8e7bd4a66c) | Nov 28, 2025 |
| HP            | Presario CQ56               | Notebook    | [94e76113ec](https://linux-hardware.org/?probe=94e76113ec) | Nov 27, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MDS... | Notebook    | [3af914e4cf](https://linux-hardware.org/?probe=3af914e4cf) | Nov 26, 2025 |
| HP            | EliteBook 8540w             | Notebook    | [097dfd1895](https://linux-hardware.org/?probe=097dfd1895) | Nov 23, 2025 |
| ASUSTek       | Z87-K                       | Desktop     | [ece2477f2d](https://linux-hardware.org/?probe=ece2477f2d) | Nov 23, 2025 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [472437717d](https://linux-hardware.org/?probe=472437717d) | Nov 23, 2025 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [afd22d278e](https://linux-hardware.org/?probe=afd22d278e) | Nov 23, 2025 |
| Acer          | Aspire V3-772               | Notebook    | [cba352e504](https://linux-hardware.org/?probe=cba352e504) | Nov 23, 2025 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [1687eaace3](https://linux-hardware.org/?probe=1687eaace3) | Nov 22, 2025 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [599cb2892f](https://linux-hardware.org/?probe=599cb2892f) | Nov 22, 2025 |
| ASUSTek       | X550LN                      | Notebook    | [dfad240177](https://linux-hardware.org/?probe=dfad240177) | Nov 21, 2025 |
| Apple         | Mac-F2218FA9                | All in one  | [d8b1e9e63a](https://linux-hardware.org/?probe=d8b1e9e63a) | Nov 20, 2025 |
| Apple         | Mac-F2218FA9                | All in one  | [3f75aabb09](https://linux-hardware.org/?probe=3f75aabb09) | Nov 20, 2025 |
| Acer          | Aspire A717-71G             | Notebook    | [54453e2354](https://linux-hardware.org/?probe=54453e2354) | Nov 19, 2025 |
| Unknown       | AX17                        | Notebook    | [c0dc8eb3c3](https://linux-hardware.org/?probe=c0dc8eb3c3) | Nov 18, 2025 |
| ASUSTek       | K56CA                       | Notebook    | [a422e24533](https://linux-hardware.org/?probe=a422e24533) | Nov 16, 2025 |
| Lenovo        | ThinkPad X240 20AMS5AN10    | Notebook    | [d1fbda801f](https://linux-hardware.org/?probe=d1fbda801f) | Nov 15, 2025 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [d902448551](https://linux-hardware.org/?probe=d902448551) | Nov 15, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [9ad15eb771](https://linux-hardware.org/?probe=9ad15eb771) | Nov 14, 2025 |
| Apple         | MacBookPro5,5               | Notebook    | [0e1531c0fa](https://linux-hardware.org/?probe=0e1531c0fa) | Nov 12, 2025 |
| Lenovo        | ThinkPad P14s Gen 6 AMD ... | Notebook    | [7318c166f2](https://linux-hardware.org/?probe=7318c166f2) | Nov 12, 2025 |
| Dell          | 08NPPY A00                  | Desktop     | [6f84a2498d](https://linux-hardware.org/?probe=6f84a2498d) | Nov 11, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [3f4a2ab487](https://linux-hardware.org/?probe=3f4a2ab487) | Nov 11, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eead43833f](https://linux-hardware.org/?probe=eead43833f) | Nov 10, 2025 |
| Jumper        | EZbook                      | Notebook    | [8d9d401c4e](https://linux-hardware.org/?probe=8d9d401c4e) | Nov 10, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6aea8346ab](https://linux-hardware.org/?probe=6aea8346ab) | Nov 09, 2025 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [194e41a8c4](https://linux-hardware.org/?probe=194e41a8c4) | Nov 09, 2025 |
| Unknown       | GB01                        | Desktop     | [286b0b27d8](https://linux-hardware.org/?probe=286b0b27d8) | Nov 08, 2025 |
| AZW           | SER V1.0                    | Mini pc     | [a6d1e64c81](https://linux-hardware.org/?probe=a6d1e64c81) | Nov 08, 2025 |
| Apple         | MacBookPro5,5               | Notebook    | [8e61cbafab](https://linux-hardware.org/?probe=8e61cbafab) | Nov 07, 2025 |
| HP            | 339A                        | Desktop     | [214f0e1da1](https://linux-hardware.org/?probe=214f0e1da1) | Nov 06, 2025 |
| GMKtec        | NucBoxG2 Plus               | Other       | [59e7db75cc](https://linux-hardware.org/?probe=59e7db75cc) | Nov 05, 2025 |
| HP            | Unknown                     | Notebook    | [4f80d79c33](https://linux-hardware.org/?probe=4f80d79c33) | Nov 04, 2025 |
| Dell          | Latitude XT2                | Notebook    | [d66c7139c7](https://linux-hardware.org/?probe=d66c7139c7) | Nov 04, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [185eeb0de5](https://linux-hardware.org/?probe=185eeb0de5) | Nov 03, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [2854b13d1e](https://linux-hardware.org/?probe=2854b13d1e) | Nov 03, 2025 |
| Dell          | Latitude 7370               | Notebook    | [809855f763](https://linux-hardware.org/?probe=809855f763) | Nov 03, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [ef1425ebb9](https://linux-hardware.org/?probe=ef1425ebb9) | Nov 02, 2025 |
| HP            | Unknown                     | Notebook    | [58f5dfa9c7](https://linux-hardware.org/?probe=58f5dfa9c7) | Nov 01, 2025 |
| MSI           | PRO B840-P WIFI             | Desktop     | [5bfe315e2e](https://linux-hardware.org/?probe=5bfe315e2e) | Nov 01, 2025 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [cc5d77b717](https://linux-hardware.org/?probe=cc5d77b717) | Oct 30, 2025 |
| HP            | Unknown                     | Notebook    | [5e58373373](https://linux-hardware.org/?probe=5e58373373) | Oct 30, 2025 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [b9baa94ec4](https://linux-hardware.org/?probe=b9baa94ec4) | Oct 30, 2025 |
| Gigabyte      | B460 HD3                    | Desktop     | [9ddbc8ad92](https://linux-hardware.org/?probe=9ddbc8ad92) | Oct 26, 2025 |
| ASUSTek       | A88XM-E                     | Desktop     | [e72af27f3c](https://linux-hardware.org/?probe=e72af27f3c) | Oct 23, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [36e092c0a7](https://linux-hardware.org/?probe=36e092c0a7) | Oct 22, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [23e525d7ec](https://linux-hardware.org/?probe=23e525d7ec) | Oct 22, 2025 |
| Dell          | 0RY007                      | Desktop     | [0ebfd19326](https://linux-hardware.org/?probe=0ebfd19326) | Oct 22, 2025 |
| ASUSTek       | A88XM-E                     | Desktop     | [88d0743f04](https://linux-hardware.org/?probe=88d0743f04) | Oct 22, 2025 |
| Dell          | 003G5R A01                  | Server      | [87742ec02e](https://linux-hardware.org/?probe=87742ec02e) | Oct 22, 2025 |
| Dell          | 003G5R A01                  | Server      | [1735e0be24](https://linux-hardware.org/?probe=1735e0be24) | Oct 22, 2025 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6b041dee18](https://linux-hardware.org/?probe=6b041dee18) | Oct 21, 2025 |
| FIRICH        | J1900                       | Desktop     | [eba97e323c](https://linux-hardware.org/?probe=eba97e323c) | Oct 21, 2025 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [83c871f441](https://linux-hardware.org/?probe=83c871f441) | Oct 20, 2025 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [7e641232ff](https://linux-hardware.org/?probe=7e641232ff) | Oct 19, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [d4788572ed](https://linux-hardware.org/?probe=d4788572ed) | Oct 19, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [f9d1fda8ed](https://linux-hardware.org/?probe=f9d1fda8ed) | Oct 18, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7e19544171](https://linux-hardware.org/?probe=7e19544171) | Oct 18, 2025 |
| HP            | 2B5B                        | Desktop     | [f972c4b68b](https://linux-hardware.org/?probe=f972c4b68b) | Oct 15, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [ff4271e356](https://linux-hardware.org/?probe=ff4271e356) | Oct 12, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [9651553719](https://linux-hardware.org/?probe=9651553719) | Oct 12, 2025 |
| Lenovo        | Unknown                     | Convertible | [dbb4964cf9](https://linux-hardware.org/?probe=dbb4964cf9) | Oct 10, 2025 |
| ASUSTek       | X751SA                      | Notebook    | [b14de4ff2e](https://linux-hardware.org/?probe=b14de4ff2e) | Oct 06, 2025 |
| MSI           | GP65 Leopard 10SFK          | Notebook    | [86cb53b0e9](https://linux-hardware.org/?probe=86cb53b0e9) | Oct 06, 2025 |
| ECS           | A320-SF110                  | Desktop     | [f40b51e354](https://linux-hardware.org/?probe=f40b51e354) | Oct 06, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | Notebook    | [914ed6021b](https://linux-hardware.org/?probe=914ed6021b) | Oct 03, 2025 |
| Gigabyte      | H81M-S1                     | Desktop     | [dc5a39fd22](https://linux-hardware.org/?probe=dc5a39fd22) | Oct 02, 2025 |
| Lenovo        | G500 20236                  | Notebook    | [ea86a4e11b](https://linux-hardware.org/?probe=ea86a4e11b) | Oct 02, 2025 |
| MSI           | PRO B840-P WIFI             | Desktop     | [a4f61a0bcb](https://linux-hardware.org/?probe=a4f61a0bcb) | Oct 01, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [dea215d503](https://linux-hardware.org/?probe=dea215d503) | Sep 30, 2025 |
| Dell          | 0XPDFK A01                  | Desktop     | [8eaa5bc00f](https://linux-hardware.org/?probe=8eaa5bc00f) | Sep 29, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [5de82098d5](https://linux-hardware.org/?probe=5de82098d5) | Sep 26, 2025 |
| Apple         | Mac-F2238AC8                | All in one  | [bcac58d3fe](https://linux-hardware.org/?probe=bcac58d3fe) | Sep 26, 2025 |
| ASUSTek       | UX32VD                      | Notebook    | [56ec858317](https://linux-hardware.org/?probe=56ec858317) | Sep 24, 2025 |
| ASUSTek       | X751SA                      | Notebook    | [e11cedc115](https://linux-hardware.org/?probe=e11cedc115) | Sep 21, 2025 |
| ASUSTek       | X751SA                      | Notebook    | [1179fa7775](https://linux-hardware.org/?probe=1179fa7775) | Sep 18, 2025 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [b31030fb66](https://linux-hardware.org/?probe=b31030fb66) | Sep 18, 2025 |
| Dell          | 0PU052                      | Desktop     | [de4016a828](https://linux-hardware.org/?probe=de4016a828) | Sep 18, 2025 |
| Dell          | 0PU052                      | Desktop     | [b8881ae961](https://linux-hardware.org/?probe=b8881ae961) | Sep 18, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [08092bbedf](https://linux-hardware.org/?probe=08092bbedf) | Sep 17, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [0ec3997c9e](https://linux-hardware.org/?probe=0ec3997c9e) | Sep 16, 2025 |
| Dell          | Vostro 3460                 | Notebook    | [43f4e1909b](https://linux-hardware.org/?probe=43f4e1909b) | Sep 13, 2025 |
| Dell          | 018D1Y A00                  | Desktop     | [f54bc30949](https://linux-hardware.org/?probe=f54bc30949) | Sep 12, 2025 |
| Acer          | Swift SF514-52T             | Notebook    | [c4f0e22ebc](https://linux-hardware.org/?probe=c4f0e22ebc) | Sep 11, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [b9d48df4ea](https://linux-hardware.org/?probe=b9d48df4ea) | Sep 11, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [c09a9a7ba0](https://linux-hardware.org/?probe=c09a9a7ba0) | Sep 10, 2025 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [754e165821](https://linux-hardware.org/?probe=754e165821) | Sep 09, 2025 |
| Lenovo        | 100w Gen 3 82J0             | Notebook    | [8949ed1313](https://linux-hardware.org/?probe=8949ed1313) | Sep 07, 2025 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [db95bf0bba](https://linux-hardware.org/?probe=db95bf0bba) | Sep 06, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [8a0af4d9af](https://linux-hardware.org/?probe=8a0af4d9af) | Sep 06, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [8164a0fcf6](https://linux-hardware.org/?probe=8164a0fcf6) | Sep 06, 2025 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [9456ad4dec](https://linux-hardware.org/?probe=9456ad4dec) | Sep 03, 2025 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [745f58144f](https://linux-hardware.org/?probe=745f58144f) | Sep 03, 2025 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [63d2601c91](https://linux-hardware.org/?probe=63d2601c91) | Sep 01, 2025 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [6e350f18cb](https://linux-hardware.org/?probe=6e350f18cb) | Sep 01, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [c7346bbd4c](https://linux-hardware.org/?probe=c7346bbd4c) | Aug 31, 2025 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [1361510abd](https://linux-hardware.org/?probe=1361510abd) | Aug 26, 2025 |
| GMKtec        | NucBoxG2 Plus               | Other       | [cf8a42df57](https://linux-hardware.org/?probe=cf8a42df57) | Aug 24, 2025 |
| Acer          | Aspire A114-33              | Notebook    | [6b4e699967](https://linux-hardware.org/?probe=6b4e699967) | Aug 23, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8e5f6f19b3](https://linux-hardware.org/?probe=8e5f6f19b3) | Aug 23, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2dd48544e3](https://linux-hardware.org/?probe=2dd48544e3) | Aug 23, 2025 |
| System76      | Pangolin                    | Notebook    | [8de53dbb47](https://linux-hardware.org/?probe=8de53dbb47) | Aug 23, 2025 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [a3ef06130a](https://linux-hardware.org/?probe=a3ef06130a) | Aug 22, 2025 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [a9b1707913](https://linux-hardware.org/?probe=a9b1707913) | Aug 22, 2025 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cdf2b58e50](https://linux-hardware.org/?probe=cdf2b58e50) | Aug 22, 2025 |
| HP            | 240 G8 Notebook PC          | Notebook    | [83ff4d021c](https://linux-hardware.org/?probe=83ff4d021c) | Aug 22, 2025 |
| HP            | 339A                        | Desktop     | [c616e58396](https://linux-hardware.org/?probe=c616e58396) | Aug 21, 2025 |
| MSI           | MS-B120                     | Mini pc     | [e916990114](https://linux-hardware.org/?probe=e916990114) | Aug 20, 2025 |
| ASRock        | X870E Nova WiFi             | Desktop     | [844cf72d7c](https://linux-hardware.org/?probe=844cf72d7c) | Aug 20, 2025 |
| Dell          | Latitude 7370               | Notebook    | [97f1e22319](https://linux-hardware.org/?probe=97f1e22319) | Aug 20, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [68b82b740f](https://linux-hardware.org/?probe=68b82b740f) | Aug 19, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [1d3600ff4d](https://linux-hardware.org/?probe=1d3600ff4d) | Aug 18, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [299e8b16f7](https://linux-hardware.org/?probe=299e8b16f7) | Aug 17, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [d4f154a368](https://linux-hardware.org/?probe=d4f154a368) | Aug 17, 2025 |
| Gigabyte      | EP45-DS3                    | Desktop     | [2e9d81959d](https://linux-hardware.org/?probe=2e9d81959d) | Aug 17, 2025 |
| Apple         | MacBookPro4,1               | Notebook    | [10be96756c](https://linux-hardware.org/?probe=10be96756c) | Aug 13, 2025 |
| Apple         | MacBookPro4,1               | Notebook    | [de63a63ae4](https://linux-hardware.org/?probe=de63a63ae4) | Aug 13, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ce9e8f6894](https://linux-hardware.org/?probe=ce9e8f6894) | Aug 12, 2025 |
| ASUSTek       | ROG Strix G733PY_G733PY_... | Notebook    | [d95da2c3eb](https://linux-hardware.org/?probe=d95da2c3eb) | Aug 12, 2025 |
| Medion        | MS-7848                     | Desktop     | [836d8912c7](https://linux-hardware.org/?probe=836d8912c7) | Aug 01, 2025 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [7a2c74f368](https://linux-hardware.org/?probe=7a2c74f368) | Jul 30, 2025 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [d9245e1b83](https://linux-hardware.org/?probe=d9245e1b83) | Jul 29, 2025 |
| ASUSTek       | H61M-K                      | Desktop     | [ee1bfb0d3f](https://linux-hardware.org/?probe=ee1bfb0d3f) | Jul 27, 2025 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e1157766a2](https://linux-hardware.org/?probe=e1157766a2) | Jul 26, 2025 |
| Dell          | Inspiron 15 3520            | Notebook    | [2e178e6c58](https://linux-hardware.org/?probe=2e178e6c58) | Jul 23, 2025 |
| Unknown       | Unknown                     | Desktop     | [1fa3a72671](https://linux-hardware.org/?probe=1fa3a72671) | Jul 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [1342ebccde](https://linux-hardware.org/?probe=1342ebccde) | Jul 20, 2025 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [360ed78f1d](https://linux-hardware.org/?probe=360ed78f1d) | Jul 20, 2025 |
| MSI           | MS-B120                     | Mini pc     | [64f706ecc9](https://linux-hardware.org/?probe=64f706ecc9) | Jul 19, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [a0cf63ce05](https://linux-hardware.org/?probe=a0cf63ce05) | Jul 18, 2025 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4013a7d975](https://linux-hardware.org/?probe=4013a7d975) | Jul 16, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [44564e9f2a](https://linux-hardware.org/?probe=44564e9f2a) | Jul 15, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [b474191ce2](https://linux-hardware.org/?probe=b474191ce2) | Jul 15, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [b636ae6ebc](https://linux-hardware.org/?probe=b636ae6ebc) | Jul 14, 2025 |
| MSI           | MS-B120                     | Mini pc     | [2fd6785237](https://linux-hardware.org/?probe=2fd6785237) | Jul 14, 2025 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [1092c5ceb7](https://linux-hardware.org/?probe=1092c5ceb7) | Jul 14, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [0093e9e1c6](https://linux-hardware.org/?probe=0093e9e1c6) | Jul 13, 2025 |
| MSI           | MS-B120                     | Mini pc     | [e056929030](https://linux-hardware.org/?probe=e056929030) | Jul 13, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [5c3ad5cb18](https://linux-hardware.org/?probe=5c3ad5cb18) | Jul 13, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3cc9186fa8](https://linux-hardware.org/?probe=3cc9186fa8) | Jul 12, 2025 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [6edaa52472](https://linux-hardware.org/?probe=6edaa52472) | Jul 11, 2025 |
| ELSKY         | QM9700/QM9600-6C            | Desktop     | [a85b8034e1](https://linux-hardware.org/?probe=a85b8034e1) | Jul 09, 2025 |
| Dell          | 0PU052                      | Desktop     | [c1a27cc2e0](https://linux-hardware.org/?probe=c1a27cc2e0) | Jul 08, 2025 |
| ASUSTek       | ProArt P16 H7606WI_H7606... | Notebook    | [63aed28924](https://linux-hardware.org/?probe=63aed28924) | Jul 08, 2025 |
| ASUSTek       | ProArt P16 H7606WI_H7606... | Notebook    | [ab4fc0c021](https://linux-hardware.org/?probe=ab4fc0c021) | Jul 08, 2025 |
| MSI           | H410M PRO                   | Desktop     | [1c0468f6e1](https://linux-hardware.org/?probe=1c0468f6e1) | Jul 06, 2025 |
| MSI           | H410M PRO                   | Desktop     | [b7cfc49afa](https://linux-hardware.org/?probe=b7cfc49afa) | Jul 06, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [bab0181e8a](https://linux-hardware.org/?probe=bab0181e8a) | Jul 04, 2025 |
| MSI           | P67A-C43                    | Desktop     | [44e78a5e1d](https://linux-hardware.org/?probe=44e78a5e1d) | Jul 03, 2025 |
| Dell          | Vostro 3580                 | Notebook    | [66f739859d](https://linux-hardware.org/?probe=66f739859d) | Jul 01, 2025 |
| ASUSTek       | H61M-K                      | Desktop     | [d84059f561](https://linux-hardware.org/?probe=d84059f561) | Jun 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [4a0570f3c1](https://linux-hardware.org/?probe=4a0570f3c1) | Jun 28, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [9b44d9b966](https://linux-hardware.org/?probe=9b44d9b966) | Jun 28, 2025 |
| HP            | Pavillion 15 Laptop PC-e... | Notebook    | [9fb48b57b8](https://linux-hardware.org/?probe=9fb48b57b8) | Jun 27, 2025 |
| HP            | Pavilion g6                 | Notebook    | [328790c061](https://linux-hardware.org/?probe=328790c061) | Jun 25, 2025 |
| HP            | Pavilion g6                 | Notebook    | [6aa01ab287](https://linux-hardware.org/?probe=6aa01ab287) | Jun 24, 2025 |
| GEEKOM        | A8                          | Desktop     | [8b825d337d](https://linux-hardware.org/?probe=8b825d337d) | Jun 21, 2025 |
| ASUSTek       | X550LN                      | Notebook    | [962e0adddc](https://linux-hardware.org/?probe=962e0adddc) | Jun 21, 2025 |
| ASUSTek       | X550LN                      | Notebook    | [00d9eb320b](https://linux-hardware.org/?probe=00d9eb320b) | Jun 21, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8682f5540c](https://linux-hardware.org/?probe=8682f5540c) | Jun 20, 2025 |
| Dell          | 018D1Y A00                  | Desktop     | [267fda63f9](https://linux-hardware.org/?probe=267fda63f9) | Jun 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [1eed5f12d6](https://linux-hardware.org/?probe=1eed5f12d6) | Jun 20, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6e43418262](https://linux-hardware.org/?probe=6e43418262) | Jun 19, 2025 |
| MSI           | Pulse 16 AI C1VFKG          | Notebook    | [bd0d3ad6fe](https://linux-hardware.org/?probe=bd0d3ad6fe) | Jun 18, 2025 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [1be7f7ed63](https://linux-hardware.org/?probe=1be7f7ed63) | Jun 17, 2025 |
| ASRock        | N68C-GS FX                  | Desktop     | [3624417095](https://linux-hardware.org/?probe=3624417095) | Jun 16, 2025 |
| HP            | 240 G8 Notebook PC          | Notebook    | [3761ac5837](https://linux-hardware.org/?probe=3761ac5837) | Jun 16, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8bef5ab75c](https://linux-hardware.org/?probe=8bef5ab75c) | Jun 15, 2025 |
| Dell          | 0PU052                      | Desktop     | [d6bb64a46e](https://linux-hardware.org/?probe=d6bb64a46e) | Jun 12, 2025 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [c6dc0c8f1c](https://linux-hardware.org/?probe=c6dc0c8f1c) | Jun 11, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db4e38f21a](https://linux-hardware.org/?probe=db4e38f21a) | Jun 11, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [dd3fca7c27](https://linux-hardware.org/?probe=dd3fca7c27) | Jun 09, 2025 |
| Biostar       | TA970                       | Desktop     | [d1a742d589](https://linux-hardware.org/?probe=d1a742d589) | Jun 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [6e07fc6b2d](https://linux-hardware.org/?probe=6e07fc6b2d) | Jun 05, 2025 |
| ASUSTek       | H110M-K                     | Desktop     | [6c7497b695](https://linux-hardware.org/?probe=6c7497b695) | Jun 05, 2025 |
| HP            | Pavilion dv6000 (RQ363EA... | Notebook    | [fc0d4f0b19](https://linux-hardware.org/?probe=fc0d4f0b19) | Jun 04, 2025 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [6e41c8cf8d](https://linux-hardware.org/?probe=6e41c8cf8d) | Jun 03, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [fb66c89f6c](https://linux-hardware.org/?probe=fb66c89f6c) | Jun 01, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [b7508dcd4c](https://linux-hardware.org/?probe=b7508dcd4c) | Jun 01, 2025 |
| HP            | Pavilion g7                 | Notebook    | [c64cbdccff](https://linux-hardware.org/?probe=c64cbdccff) | Jun 01, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [426d41cb68](https://linux-hardware.org/?probe=426d41cb68) | May 31, 2025 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [bbfedc4a2c](https://linux-hardware.org/?probe=bbfedc4a2c) | May 31, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7cb48ce939](https://linux-hardware.org/?probe=7cb48ce939) | May 31, 2025 |
| HP            | EliteBook 850 G6            | Notebook    | [2f0fd20ed5](https://linux-hardware.org/?probe=2f0fd20ed5) | May 31, 2025 |
| HP            | EliteBook 850 G6            | Notebook    | [4bc436ca7a](https://linux-hardware.org/?probe=4bc436ca7a) | May 31, 2025 |
| Dell          | Inspiron 5551               | Notebook    | [418818f15f](https://linux-hardware.org/?probe=418818f15f) | May 30, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [b779840a58](https://linux-hardware.org/?probe=b779840a58) | May 30, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [fb6bcba1ff](https://linux-hardware.org/?probe=fb6bcba1ff) | May 30, 2025 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [b423307cf4](https://linux-hardware.org/?probe=b423307cf4) | May 30, 2025 |
| MSI           | A55M-E33                    | Desktop     | [6a817db906](https://linux-hardware.org/?probe=6a817db906) | May 28, 2025 |
| Lenovo        | IdeaPad 310 80tu            | Notebook    | [68f9e2c0c6](https://linux-hardware.org/?probe=68f9e2c0c6) | May 28, 2025 |
| PC Special... | Lafite Pro V 14M            | Notebook    | [da41d430c7](https://linux-hardware.org/?probe=da41d430c7) | May 27, 2025 |
| Dell          | Precision M4800             | Notebook    | [751231c40d](https://linux-hardware.org/?probe=751231c40d) | May 27, 2025 |
| Dell          | Precision M4800             | Notebook    | [4a74abdcb3](https://linux-hardware.org/?probe=4a74abdcb3) | May 27, 2025 |
| Toshiba       | NB305                       | Notebook    | [a13b17c106](https://linux-hardware.org/?probe=a13b17c106) | May 26, 2025 |
| Unknown       | DG-3399                     | Soc         | [f1ca0223a9](https://linux-hardware.org/?probe=f1ca0223a9) | May 25, 2025 |
| Lenovo        | SDK0J40709 WIN 325959460... | All in one  | [1d30f51c2f](https://linux-hardware.org/?probe=1d30f51c2f) | May 25, 2025 |
| Unknown       | Unknown                     | Desktop     | [bfef788cc1](https://linux-hardware.org/?probe=bfef788cc1) | May 24, 2025 |
| ASRock        | A780LM-S                    | Desktop     | [7b34a92a2b](https://linux-hardware.org/?probe=7b34a92a2b) | May 24, 2025 |
| Unknown       | Unknown                     | Desktop     | [875ba22683](https://linux-hardware.org/?probe=875ba22683) | May 24, 2025 |
| Unknown       | Unknown                     | Desktop     | [d741cae585](https://linux-hardware.org/?probe=d741cae585) | May 24, 2025 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [4f55320cbb](https://linux-hardware.org/?probe=4f55320cbb) | May 23, 2025 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [3cacb260b9](https://linux-hardware.org/?probe=3cacb260b9) | May 23, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [02d4caf590](https://linux-hardware.org/?probe=02d4caf590) | May 22, 2025 |
| ASRock        | B365M-HDV                   | Desktop     | [1d78596c0f](https://linux-hardware.org/?probe=1d78596c0f) | May 21, 2025 |
| Gigabyte      | B650E AORUS STEALTH ICE     | Desktop     | [995b4713a7](https://linux-hardware.org/?probe=995b4713a7) | May 20, 2025 |
| MSI           | MS-B120                     | Mini pc     | [fbc3a19e1e](https://linux-hardware.org/?probe=fbc3a19e1e) | May 19, 2025 |
| Unknown       | Unknown                     | Notebook    | [5189d37805](https://linux-hardware.org/?probe=5189d37805) | May 18, 2025 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [27dadfe7a2](https://linux-hardware.org/?probe=27dadfe7a2) | May 18, 2025 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [b9c4f91d60](https://linux-hardware.org/?probe=b9c4f91d60) | May 18, 2025 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [1f3abaae0d](https://linux-hardware.org/?probe=1f3abaae0d) | May 17, 2025 |
| ASUSTek       | H87M-E                      | Desktop     | [fa17049212](https://linux-hardware.org/?probe=fa17049212) | May 14, 2025 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a0aaae2f](https://linux-hardware.org/?probe=56a0aaae2f) | May 14, 2025 |
| Dell          | 003G5R A01                  | Server      | [17ee959220](https://linux-hardware.org/?probe=17ee959220) | May 12, 2025 |
| ASUSTek       | H87M-E                      | Desktop     | [362090aa42](https://linux-hardware.org/?probe=362090aa42) | May 11, 2025 |
| Fujitsu Si... | AMILO PRO V2035             | Notebook    | [4c55e272b6](https://linux-hardware.org/?probe=4c55e272b6) | May 09, 2025 |
| Entroware     | Hades ED05R3                | Desktop     | [6d535b4e99](https://linux-hardware.org/?probe=6d535b4e99) | May 09, 2025 |
| Dell          | 003G5R A01                  | Server      | [ed6a5ec412](https://linux-hardware.org/?probe=ed6a5ec412) | May 08, 2025 |
| MSI           | MS-B120                     | Mini pc     | [b9027ab779](https://linux-hardware.org/?probe=b9027ab779) | May 07, 2025 |
| Hardkernel    | Odroid XU4                  | Soc         | [342997fcee](https://linux-hardware.org/?probe=342997fcee) | May 05, 2025 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [f265975f27](https://linux-hardware.org/?probe=f265975f27) | May 05, 2025 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3d8f5c66db](https://linux-hardware.org/?probe=3d8f5c66db) | May 04, 2025 |
| Intel         | H61                         | Desktop     | [317496b189](https://linux-hardware.org/?probe=317496b189) | May 04, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [4097b61e85](https://linux-hardware.org/?probe=4097b61e85) | May 03, 2025 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [a179cbdcf1](https://linux-hardware.org/?probe=a179cbdcf1) | May 02, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [6bd8b18248](https://linux-hardware.org/?probe=6bd8b18248) | May 02, 2025 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ce2ddd3f61](https://linux-hardware.org/?probe=ce2ddd3f61) | May 01, 2025 |
| Dell          | 0KWVT8 A03                  | Desktop     | [abd088df17](https://linux-hardware.org/?probe=abd088df17) | Apr 30, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [b3c7d005e1](https://linux-hardware.org/?probe=b3c7d005e1) | Apr 29, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [4751d8b691](https://linux-hardware.org/?probe=4751d8b691) | Apr 29, 2025 |
| HP            | Unknown                     | Notebook    | [a09d935302](https://linux-hardware.org/?probe=a09d935302) | Apr 28, 2025 |
| MSI           | MS-7380                     | Desktop     | [c09cd704b6](https://linux-hardware.org/?probe=c09cd704b6) | Apr 27, 2025 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [18d7206c5a](https://linux-hardware.org/?probe=18d7206c5a) | Apr 27, 2025 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ca69b477da](https://linux-hardware.org/?probe=ca69b477da) | Apr 27, 2025 |
| Lenovo        | ThinkPad T430 2349H86       | Notebook    | [7498ed4258](https://linux-hardware.org/?probe=7498ed4258) | Apr 25, 2025 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b300f54550](https://linux-hardware.org/?probe=b300f54550) | Apr 25, 2025 |
| HP            | ProBook 450 G7              | Notebook    | [e766d8fb29](https://linux-hardware.org/?probe=e766d8fb29) | Apr 22, 2025 |
| MSI           | MS-1656                     | Notebook    | [de9f5812e4](https://linux-hardware.org/?probe=de9f5812e4) | Apr 20, 2025 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [62cbfce8e5](https://linux-hardware.org/?probe=62cbfce8e5) | Apr 20, 2025 |
| ASUSTek       | H81M-K                      | Desktop     | [d3b181c3e7](https://linux-hardware.org/?probe=d3b181c3e7) | Apr 19, 2025 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [db318ace22](https://linux-hardware.org/?probe=db318ace22) | Apr 16, 2025 |
| Dell          | 0KWVT8 A03                  | Desktop     | [73cd67fdfc](https://linux-hardware.org/?probe=73cd67fdfc) | Apr 15, 2025 |
| Dell          | Inspiron 16 7610            | Notebook    | [bc0b04ebf0](https://linux-hardware.org/?probe=bc0b04ebf0) | Apr 15, 2025 |
| Dell          | 054KM3 A01                  | Desktop     | [e1f287cac8](https://linux-hardware.org/?probe=e1f287cac8) | Apr 14, 2025 |
| Dell          | 054KM3 A01                  | Desktop     | [916f3331e2](https://linux-hardware.org/?probe=916f3331e2) | Apr 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [8f136f907b](https://linux-hardware.org/?probe=8f136f907b) | Apr 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [6f7a27ad6e](https://linux-hardware.org/?probe=6f7a27ad6e) | Apr 12, 2025 |
| Pencents      | U50 Standard                | Mini pc     | [1189f08d3b](https://linux-hardware.org/?probe=1189f08d3b) | Apr 12, 2025 |
| Dell          | 0KWVT8 A03                  | Desktop     | [a0becb2a17](https://linux-hardware.org/?probe=a0becb2a17) | Apr 09, 2025 |
| Acer          | Aspire A315-41G             | Notebook    | [6eda7175e8](https://linux-hardware.org/?probe=6eda7175e8) | Apr 05, 2025 |
| Acer          | Aspire E5-571G              | Notebook    | [ebf741fba3](https://linux-hardware.org/?probe=ebf741fba3) | Apr 03, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [2e8b63681a](https://linux-hardware.org/?probe=2e8b63681a) | Mar 30, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [5b1947d1af](https://linux-hardware.org/?probe=5b1947d1af) | Mar 30, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [69761f372b](https://linux-hardware.org/?probe=69761f372b) | Mar 29, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [eb6937a508](https://linux-hardware.org/?probe=eb6937a508) | Mar 27, 2025 |
| Apple         | Mac-F22C86C8                | Mini pc     | [2b119f35aa](https://linux-hardware.org/?probe=2b119f35aa) | Mar 27, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [f5ba7ef7a3](https://linux-hardware.org/?probe=f5ba7ef7a3) | Mar 25, 2025 |
| HP            | 89B5 A                      | Desktop     | [60d5ece37f](https://linux-hardware.org/?probe=60d5ece37f) | Mar 25, 2025 |
| Lenovo        | ThinkPad L520 5015W49       | Notebook    | [c2db4be7a9](https://linux-hardware.org/?probe=c2db4be7a9) | Mar 23, 2025 |
| Dell          | Latitude E6540              | Notebook    | [9c423804b7](https://linux-hardware.org/?probe=9c423804b7) | Mar 23, 2025 |
| MSI           | MS-B120                     | Mini pc     | [eb4f339d5d](https://linux-hardware.org/?probe=eb4f339d5d) | Mar 22, 2025 |
| Dell          | Latitude E6540              | Notebook    | [00841b8b11](https://linux-hardware.org/?probe=00841b8b11) | Mar 21, 2025 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [32f8507b97](https://linux-hardware.org/?probe=32f8507b97) | Mar 21, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cbba266be1](https://linux-hardware.org/?probe=cbba266be1) | Mar 20, 2025 |
| ASUSTek       | Z97-K                       | Desktop     | [5b2bdbcc48](https://linux-hardware.org/?probe=5b2bdbcc48) | Mar 16, 2025 |
| Avell High... | A72 HYB                     | Notebook    | [fe8c38e616](https://linux-hardware.org/?probe=fe8c38e616) | Mar 16, 2025 |
| ASUSTek       | X99-E WS                    | Desktop     | [2cbf20c66a](https://linux-hardware.org/?probe=2cbf20c66a) | Mar 15, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [781e41fb0b](https://linux-hardware.org/?probe=781e41fb0b) | Mar 15, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [c1f85ac960](https://linux-hardware.org/?probe=c1f85ac960) | Mar 15, 2025 |
| Dell          | Precision M6800             | Notebook    | [050a71f771](https://linux-hardware.org/?probe=050a71f771) | Mar 13, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3b571d9e06](https://linux-hardware.org/?probe=3b571d9e06) | Mar 10, 2025 |
| Dell          | Latitude 5320               | Notebook    | [7c7d6cef4e](https://linux-hardware.org/?probe=7c7d6cef4e) | Mar 10, 2025 |
| Intel         | S2600WFT H48104-873         | Server      | [fca5339c90](https://linux-hardware.org/?probe=fca5339c90) | Mar 09, 2025 |
| MSI           | H81M-E33                    | Desktop     | [901bb986b7](https://linux-hardware.org/?probe=901bb986b7) | Mar 09, 2025 |
| HP            | 83EB                        | All in one  | [d59a2ff505](https://linux-hardware.org/?probe=d59a2ff505) | Mar 09, 2025 |
| Acer          | Aspire E5-551G              | Notebook    | [ef20fd7424](https://linux-hardware.org/?probe=ef20fd7424) | Mar 08, 2025 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [00d9e57553](https://linux-hardware.org/?probe=00d9e57553) | Mar 04, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [83f68aef8a](https://linux-hardware.org/?probe=83f68aef8a) | Mar 03, 2025 |
| Toshiba       | Satellite P50-B-10V         | Notebook    | [06c44c7b74](https://linux-hardware.org/?probe=06c44c7b74) | Mar 03, 2025 |
| Dell          | Inspiron N5010              | Notebook    | [a2d52dafaa](https://linux-hardware.org/?probe=a2d52dafaa) | Mar 02, 2025 |
| Lenovo        | 316E NOK                    | Mini pc     | [3e5e6a088d](https://linux-hardware.org/?probe=3e5e6a088d) | Feb 28, 2025 |
| HP            | 83EB                        | All in one  | [22c158d000](https://linux-hardware.org/?probe=22c158d000) | Feb 27, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [50cb965e43](https://linux-hardware.org/?probe=50cb965e43) | Feb 27, 2025 |
| HP            | 470 G7 Notebook PC          | Notebook    | [3f6a27f9d2](https://linux-hardware.org/?probe=3f6a27f9d2) | Feb 26, 2025 |
| HP            | 829E                        | Mini pc     | [40161f8772](https://linux-hardware.org/?probe=40161f8772) | Feb 26, 2025 |
| MSI           | MS-9A73                     | Notebook    | [6a0e74c7f1](https://linux-hardware.org/?probe=6a0e74c7f1) | Feb 25, 2025 |
| MSI           | MS-9A73                     | Notebook    | [5eb302b0e9](https://linux-hardware.org/?probe=5eb302b0e9) | Feb 25, 2025 |
| Lenovo        | B450 1S168003694001K        | Notebook    | [3a899614a8](https://linux-hardware.org/?probe=3a899614a8) | Feb 25, 2025 |
| Megaware      | Mega netbook IP-M10.6F.2... | Notebook    | [d9665e2fc5](https://linux-hardware.org/?probe=d9665e2fc5) | Feb 25, 2025 |
| Dell          | Inspiron N5010              | Notebook    | [096f912ecd](https://linux-hardware.org/?probe=096f912ecd) | Feb 25, 2025 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f709017cc9](https://linux-hardware.org/?probe=f709017cc9) | Feb 24, 2025 |
| AZW           | SER V1                      | Mini pc     | [1f8ec85e0c](https://linux-hardware.org/?probe=1f8ec85e0c) | Feb 24, 2025 |
| MSI           | PRO B660M-P DDR4            | Desktop     | [aae3b56ded](https://linux-hardware.org/?probe=aae3b56ded) | Feb 22, 2025 |
| MSI           | MS-B120                     | Mini pc     | [babf6f54e6](https://linux-hardware.org/?probe=babf6f54e6) | Feb 19, 2025 |
| Fujitsu Si... | LIFEBOOK E4010              | Notebook    | [7e6ba99688](https://linux-hardware.org/?probe=7e6ba99688) | Feb 17, 2025 |
| Dell          | 0TP412                      | Desktop     | [9c1075afc8](https://linux-hardware.org/?probe=9c1075afc8) | Feb 17, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [903a07579c](https://linux-hardware.org/?probe=903a07579c) | Feb 16, 2025 |
| Lenovo        | ThinkPad R60 9456HTG        | Notebook    | [ed257ec079](https://linux-hardware.org/?probe=ed257ec079) | Feb 16, 2025 |
| Dell          | Latitude D830               | Notebook    | [7f8f3005c1](https://linux-hardware.org/?probe=7f8f3005c1) | Feb 16, 2025 |
| Acer          | Aspire 6930G                | Notebook    | [1598e1c543](https://linux-hardware.org/?probe=1598e1c543) | Feb 16, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [2caac88a59](https://linux-hardware.org/?probe=2caac88a59) | Feb 15, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [5127589d66](https://linux-hardware.org/?probe=5127589d66) | Feb 14, 2025 |
| ASUSTek       | X550LN                      | Notebook    | [83bd92b78c](https://linux-hardware.org/?probe=83bd92b78c) | Feb 11, 2025 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [34f4ae5f88](https://linux-hardware.org/?probe=34f4ae5f88) | Feb 08, 2025 |
| Dell          | Inspiron N5050              | Notebook    | [a639e2742f](https://linux-hardware.org/?probe=a639e2742f) | Feb 08, 2025 |
| Dell          | Inspiron 3531               | Notebook    | [6fe6e86881](https://linux-hardware.org/?probe=6fe6e86881) | Feb 07, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [5ac102a58b](https://linux-hardware.org/?probe=5ac102a58b) | Feb 06, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [ac2e2fb88a](https://linux-hardware.org/?probe=ac2e2fb88a) | Feb 06, 2025 |
| Acer          | Aspire ES1-512              | Notebook    | [2ef5a52438](https://linux-hardware.org/?probe=2ef5a52438) | Feb 06, 2025 |
| HP            | 81BA                        | All in one  | [ddfc8efac9](https://linux-hardware.org/?probe=ddfc8efac9) | Feb 05, 2025 |
| ASRock        | B85M-HDS                    | Desktop     | [1f556e72b0](https://linux-hardware.org/?probe=1f556e72b0) | Feb 05, 2025 |
| Acer          | Extensa 2540                | Notebook    | [0699d82563](https://linux-hardware.org/?probe=0699d82563) | Feb 05, 2025 |
| HP            | 81BA                        | All in one  | [2cde17bd90](https://linux-hardware.org/?probe=2cde17bd90) | Feb 05, 2025 |
| Acer          | Aspire ES1-512              | Notebook    | [6b7b7570d3](https://linux-hardware.org/?probe=6b7b7570d3) | Feb 02, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [b6a23c8847](https://linux-hardware.org/?probe=b6a23c8847) | Feb 02, 2025 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [c16cfbe28a](https://linux-hardware.org/?probe=c16cfbe28a) | Jan 31, 2025 |
| MSI           | PH67A-C43                   | Desktop     | [473d9d109a](https://linux-hardware.org/?probe=473d9d109a) | Jan 30, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [3b338aea71](https://linux-hardware.org/?probe=3b338aea71) | Jan 29, 2025 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [96855ae761](https://linux-hardware.org/?probe=96855ae761) | Jan 28, 2025 |
| MSI           | 2A9Ch                       | Desktop     | [ff69b3b7b1](https://linux-hardware.org/?probe=ff69b3b7b1) | Jan 28, 2025 |
| MSI           | 2A9Ch                       | Desktop     | [51b6c974e3](https://linux-hardware.org/?probe=51b6c974e3) | Jan 28, 2025 |
| HP            | 8056                        | Desktop     | [a7131d19d5](https://linux-hardware.org/?probe=a7131d19d5) | Jan 27, 2025 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [e4abc8f1d2](https://linux-hardware.org/?probe=e4abc8f1d2) | Jan 27, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [5c5556d044](https://linux-hardware.org/?probe=5c5556d044) | Jan 26, 2025 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [3fd6e5505d](https://linux-hardware.org/?probe=3fd6e5505d) | Jan 26, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [0cb5559a46](https://linux-hardware.org/?probe=0cb5559a46) | Jan 25, 2025 |
| Dell          | Inspiron 5566               | Notebook    | [2d9f8cb1e0](https://linux-hardware.org/?probe=2d9f8cb1e0) | Jan 25, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [5193f69283](https://linux-hardware.org/?probe=5193f69283) | Jan 25, 2025 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | Notebook    | [15202f09f5](https://linux-hardware.org/?probe=15202f09f5) | Jan 22, 2025 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | Notebook    | [6192db5fd1](https://linux-hardware.org/?probe=6192db5fd1) | Jan 22, 2025 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [8bf2225129](https://linux-hardware.org/?probe=8bf2225129) | Jan 22, 2025 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [f3cefdb7cb](https://linux-hardware.org/?probe=f3cefdb7cb) | Jan 21, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [58dca63f00](https://linux-hardware.org/?probe=58dca63f00) | Jan 21, 2025 |
| Dell          | Latitude E5570              | Notebook    | [a8094198c6](https://linux-hardware.org/?probe=a8094198c6) | Jan 20, 2025 |
| HP            | Notebook                    | Notebook    | [960b74f3ae](https://linux-hardware.org/?probe=960b74f3ae) | Jan 19, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [8bb96e76a4](https://linux-hardware.org/?probe=8bb96e76a4) | Jan 19, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [3cdbd2fd32](https://linux-hardware.org/?probe=3cdbd2fd32) | Jan 15, 2025 |
| Acer          | Aspire ES1-311              | Notebook    | [736210755f](https://linux-hardware.org/?probe=736210755f) | Jan 14, 2025 |
| Acer          | Aspire AG14-21P             | Notebook    | [7608caebb4](https://linux-hardware.org/?probe=7608caebb4) | Jan 13, 2025 |
| Acer          | Aspire AG14-21P             | Notebook    | [902eb14e8e](https://linux-hardware.org/?probe=902eb14e8e) | Jan 13, 2025 |
| ASUSTek       | UX21E                       | Notebook    | [3e5088cd0d](https://linux-hardware.org/?probe=3e5088cd0d) | Jan 13, 2025 |
| Acer          | Nitro AN16-42               | Notebook    | [a414245f9b](https://linux-hardware.org/?probe=a414245f9b) | Jan 12, 2025 |
| HP            | ProBook x360 11 G2 EE       | Convertible | [f1d3698659](https://linux-hardware.org/?probe=f1d3698659) | Jan 11, 2025 |
| Acer          | Aspire ES1-520              | Notebook    | [4c75b8f8ac](https://linux-hardware.org/?probe=4c75b8f8ac) | Jan 10, 2025 |
| Unknown       | Unknown                     | Desktop     | [0095510bd6](https://linux-hardware.org/?probe=0095510bd6) | Jan 10, 2025 |
| Acer          | Aspire ES1-512              | Notebook    | [87e69aef4a](https://linux-hardware.org/?probe=87e69aef4a) | Jan 07, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [fbf5a4e676](https://linux-hardware.org/?probe=fbf5a4e676) | Jan 07, 2025 |
| Unknown       | Unknown                     | Desktop     | [8775ff73e6](https://linux-hardware.org/?probe=8775ff73e6) | Jan 07, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [6d0b2a7169](https://linux-hardware.org/?probe=6d0b2a7169) | Jan 07, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [1a436745ab](https://linux-hardware.org/?probe=1a436745ab) | Jan 06, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [67d6f124c9](https://linux-hardware.org/?probe=67d6f124c9) | Jan 06, 2025 |
| HP            | Pavilion g6                 | Notebook    | [909d7c69b5](https://linux-hardware.org/?probe=909d7c69b5) | Jan 05, 2025 |
| HP            | Pavilion g6                 | Notebook    | [ef9ad1fe50](https://linux-hardware.org/?probe=ef9ad1fe50) | Jan 05, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [adb5d55cf4](https://linux-hardware.org/?probe=adb5d55cf4) | Jan 04, 2025 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6239b93b09](https://linux-hardware.org/?probe=6239b93b09) | Jan 03, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [88e255ba8a](https://linux-hardware.org/?probe=88e255ba8a) | Jan 03, 2025 |
| Dell          | Inspiron 5567               | Notebook    | [786e67f683](https://linux-hardware.org/?probe=786e67f683) | Jan 02, 2025 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9829e4ea09](https://linux-hardware.org/?probe=9829e4ea09) | Jan 01, 2025 |
| Lenovo        | IdeaPad U510 4941           | Notebook    | [78a774dc27](https://linux-hardware.org/?probe=78a774dc27) | Jan 01, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [90cec85bd7](https://linux-hardware.org/?probe=90cec85bd7) | Dec 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9e7734f37f](https://linux-hardware.org/?probe=9e7734f37f) | Dec 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [65d462ae1d](https://linux-hardware.org/?probe=65d462ae1d) | Dec 30, 2024 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [fe49d94f48](https://linux-hardware.org/?probe=fe49d94f48) | Dec 30, 2024 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [0f84cbbee8](https://linux-hardware.org/?probe=0f84cbbee8) | Dec 30, 2024 |
| HP            | Pavilion dv4                | Notebook    | [e09129add9](https://linux-hardware.org/?probe=e09129add9) | Dec 30, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [8aea47fff9](https://linux-hardware.org/?probe=8aea47fff9) | Dec 29, 2024 |
| HP            | 8462                        | Desktop     | [d0e8315b62](https://linux-hardware.org/?probe=d0e8315b62) | Dec 28, 2024 |
| Dell          | Latitude 3410               | Notebook    | [d884cebf94](https://linux-hardware.org/?probe=d884cebf94) | Dec 27, 2024 |
| Dell          | 0M858N A01                  | Desktop     | [8378333655](https://linux-hardware.org/?probe=8378333655) | Dec 27, 2024 |
| MSI           | MS-6701                     | Desktop     | [d356deb17b](https://linux-hardware.org/?probe=d356deb17b) | Dec 25, 2024 |
| MSI           | MS-6701                     | Desktop     | [0ab268cc0a](https://linux-hardware.org/?probe=0ab268cc0a) | Dec 25, 2024 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [4634dcf259](https://linux-hardware.org/?probe=4634dcf259) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [362b9364dd](https://linux-hardware.org/?probe=362b9364dd) | Dec 24, 2024 |
| HP            | 8462                        | Desktop     | [4837f873a4](https://linux-hardware.org/?probe=4837f873a4) | Dec 23, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [0f16f634ba](https://linux-hardware.org/?probe=0f16f634ba) | Dec 22, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8768679ad7](https://linux-hardware.org/?probe=8768679ad7) | Dec 22, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [2dd67e963d](https://linux-hardware.org/?probe=2dd67e963d) | Dec 19, 2024 |
| Lenovo        | ThinkPad T430 23498F0       | Notebook    | [4b2306ff9f](https://linux-hardware.org/?probe=4b2306ff9f) | Dec 19, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [d711c652eb](https://linux-hardware.org/?probe=d711c652eb) | Dec 19, 2024 |
| Dell          | OptiPlex 5050               | Desktop     | [78724eea62](https://linux-hardware.org/?probe=78724eea62) | Dec 18, 2024 |
| Lenovo        | ThinkPad                    | Notebook    | [3c0105bc7f](https://linux-hardware.org/?probe=3c0105bc7f) | Dec 16, 2024 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c5dba8548d](https://linux-hardware.org/?probe=c5dba8548d) | Dec 14, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [28c96de064](https://linux-hardware.org/?probe=28c96de064) | Dec 12, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [88623ffcc4](https://linux-hardware.org/?probe=88623ffcc4) | Dec 10, 2024 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [12f7f54a9f](https://linux-hardware.org/?probe=12f7f54a9f) | Dec 09, 2024 |
| HP            | 8266                        | Desktop     | [ba5135167e](https://linux-hardware.org/?probe=ba5135167e) | Dec 09, 2024 |
| Medion        | MS-7797                     | Desktop     | [5adf732da0](https://linux-hardware.org/?probe=5adf732da0) | Dec 09, 2024 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [0f1748d404](https://linux-hardware.org/?probe=0f1748d404) | Dec 08, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [13635a905e](https://linux-hardware.org/?probe=13635a905e) | Dec 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [645f715c2f](https://linux-hardware.org/?probe=645f715c2f) | Dec 06, 2024 |
| Dell          | Latitude E6410              | Notebook    | [9e58a81f87](https://linux-hardware.org/?probe=9e58a81f87) | Dec 02, 2024 |
| HP            | 158A                        | Desktop     | [ba061366cc](https://linux-hardware.org/?probe=ba061366cc) | Dec 02, 2024 |
| Acer          | Aspire 5920G                | Notebook    | [3ac75edf3a](https://linux-hardware.org/?probe=3ac75edf3a) | Nov 30, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [9e1536f755](https://linux-hardware.org/?probe=9e1536f755) | Nov 28, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [4dd4121257](https://linux-hardware.org/?probe=4dd4121257) | Nov 28, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [b17bd0994c](https://linux-hardware.org/?probe=b17bd0994c) | Nov 28, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [3d32552ab3](https://linux-hardware.org/?probe=3d32552ab3) | Nov 28, 2024 |
| Samsung       | R530/R730                   | Notebook    | [8d57e47bb7](https://linux-hardware.org/?probe=8d57e47bb7) | Nov 25, 2024 |
| Samsung       | R530/R730                   | Notebook    | [924a6a8572](https://linux-hardware.org/?probe=924a6a8572) | Nov 25, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [20e57b7eca](https://linux-hardware.org/?probe=20e57b7eca) | Nov 24, 2024 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [8af2b2f494](https://linux-hardware.org/?probe=8af2b2f494) | Nov 24, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [76c5e79d46](https://linux-hardware.org/?probe=76c5e79d46) | Nov 23, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [99d9097a4b](https://linux-hardware.org/?probe=99d9097a4b) | Nov 23, 2024 |
| AZW           | MINI S                      | Desktop     | [0fc266941c](https://linux-hardware.org/?probe=0fc266941c) | Nov 22, 2024 |
| HP            | 8266                        | Desktop     | [59a635aa78](https://linux-hardware.org/?probe=59a635aa78) | Nov 21, 2024 |
| MSI           | MS-B120                     | Mini pc     | [3da903450a](https://linux-hardware.org/?probe=3da903450a) | Nov 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M30... | Notebook    | [70f739c61f](https://linux-hardware.org/?probe=70f739c61f) | Nov 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c995846597](https://linux-hardware.org/?probe=c995846597) | Nov 19, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [2f52802556](https://linux-hardware.org/?probe=2f52802556) | Nov 19, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [61d8a1bc22](https://linux-hardware.org/?probe=61d8a1bc22) | Nov 17, 2024 |
| Dell          | 049G3W A02                  | Desktop     | [be710ef5d4](https://linux-hardware.org/?probe=be710ef5d4) | Nov 14, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [eec78bb1ce](https://linux-hardware.org/?probe=eec78bb1ce) | Nov 13, 2024 |
| Dell          | Latitude 7370               | Notebook    | [ea82f5f399](https://linux-hardware.org/?probe=ea82f5f399) | Nov 13, 2024 |
| Acer          | Aspire 5050                 | Notebook    | [eac5cc26a2](https://linux-hardware.org/?probe=eac5cc26a2) | Nov 10, 2024 |
| Dell          | 0C4H12 A00                  | Desktop     | [53891c4e7e](https://linux-hardware.org/?probe=53891c4e7e) | Nov 10, 2024 |
| System76      | Darter Pro                  | Notebook    | [757d9cd509](https://linux-hardware.org/?probe=757d9cd509) | Nov 09, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [9088fca13d](https://linux-hardware.org/?probe=9088fca13d) | Nov 09, 2024 |
| Dell          | 0HMX8D A01                  | Desktop     | [715b506ea4](https://linux-hardware.org/?probe=715b506ea4) | Nov 08, 2024 |
| Lenovo        | ThinkPad L560 20F2S2GW00    | Notebook    | [3c7901a5c1](https://linux-hardware.org/?probe=3c7901a5c1) | Nov 06, 2024 |
| Lenovo        | ThinkPad L560 20F2S2GW00    | Notebook    | [811c3c90ef](https://linux-hardware.org/?probe=811c3c90ef) | Nov 06, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [90b574e0b2](https://linux-hardware.org/?probe=90b574e0b2) | Nov 04, 2024 |
| Sony          | VPCS13V9E                   | Notebook    | [5f8c9da2ec](https://linux-hardware.org/?probe=5f8c9da2ec) | Nov 03, 2024 |
| Sony          | VPCS13V9E                   | Notebook    | [5f8592eebb](https://linux-hardware.org/?probe=5f8592eebb) | Nov 03, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [1534dbb5c0](https://linux-hardware.org/?probe=1534dbb5c0) | Nov 02, 2024 |
| ASUSTek       | T304UA                      | Tablet      | [da6e013777](https://linux-hardware.org/?probe=da6e013777) | Nov 02, 2024 |
| Dell          | Latitude 7370               | Notebook    | [b5426b24e2](https://linux-hardware.org/?probe=b5426b24e2) | Nov 02, 2024 |
| ASUSTek       | K52F                        | Notebook    | [dd3d46e1f9](https://linux-hardware.org/?probe=dd3d46e1f9) | Oct 31, 2024 |
| ASUSTek       | K52F                        | Notebook    | [74d8af6252](https://linux-hardware.org/?probe=74d8af6252) | Oct 31, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [ad57f56740](https://linux-hardware.org/?probe=ad57f56740) | Oct 31, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8d959cb7c1](https://linux-hardware.org/?probe=8d959cb7c1) | Oct 30, 2024 |
| Dell          | 0HMX8D A01                  | Desktop     | [f1a37fae52](https://linux-hardware.org/?probe=f1a37fae52) | Oct 30, 2024 |
| Lenovo        | ThinkPad T510 4349BD8       | Notebook    | [2e8c236061](https://linux-hardware.org/?probe=2e8c236061) | Oct 30, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [d05dc21a14](https://linux-hardware.org/?probe=d05dc21a14) | Oct 26, 2024 |
| MSI           | PH67A-C43                   | Desktop     | [d67321fbb9](https://linux-hardware.org/?probe=d67321fbb9) | Oct 25, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [e106b29eab](https://linux-hardware.org/?probe=e106b29eab) | Oct 24, 2024 |
| Gigabyte      | G41MT-S2                    | Desktop     | [7705d36266](https://linux-hardware.org/?probe=7705d36266) | Oct 23, 2024 |
| HP            | Notebook                    | Notebook    | [00a772808d](https://linux-hardware.org/?probe=00a772808d) | Oct 23, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [16c95d4388](https://linux-hardware.org/?probe=16c95d4388) | Oct 22, 2024 |
| ASRock        | A780LM-S                    | Desktop     | [0f911c2c87](https://linux-hardware.org/?probe=0f911c2c87) | Oct 22, 2024 |
| MSI           | MS-B120                     | Mini pc     | [41da7e57a6](https://linux-hardware.org/?probe=41da7e57a6) | Oct 22, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [e3f6b0568c](https://linux-hardware.org/?probe=e3f6b0568c) | Oct 21, 2024 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [3dff6bbcdb](https://linux-hardware.org/?probe=3dff6bbcdb) | Oct 20, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [637e502045](https://linux-hardware.org/?probe=637e502045) | Oct 20, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [d99d978d2b](https://linux-hardware.org/?probe=d99d978d2b) | Oct 20, 2024 |
| HP            | ProLiant DL360 G7           | Server      | [c639346a52](https://linux-hardware.org/?probe=c639346a52) | Oct 19, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [957f60f34e](https://linux-hardware.org/?probe=957f60f34e) | Oct 19, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [bbf8632ea8](https://linux-hardware.org/?probe=bbf8632ea8) | Oct 18, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [b8119f542b](https://linux-hardware.org/?probe=b8119f542b) | Oct 18, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [92736b8de6](https://linux-hardware.org/?probe=92736b8de6) | Oct 18, 2024 |
| HP            | x2 210 G2                   | Tablet      | [ead38d715f](https://linux-hardware.org/?probe=ead38d715f) | Oct 17, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0bdda39e37](https://linux-hardware.org/?probe=0bdda39e37) | Oct 16, 2024 |
| HP            | 8299                        | Desktop     | [02b17bc8ce](https://linux-hardware.org/?probe=02b17bc8ce) | Oct 16, 2024 |
| ASUSTek       | M4A78-E                     | Desktop     | [2c29f9d339](https://linux-hardware.org/?probe=2c29f9d339) | Oct 15, 2024 |
| HP            | Pavilion dv8                | Notebook    | [21df937346](https://linux-hardware.org/?probe=21df937346) | Oct 14, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [78a5ceba6e](https://linux-hardware.org/?probe=78a5ceba6e) | Oct 12, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [ad611bc852](https://linux-hardware.org/?probe=ad611bc852) | Oct 12, 2024 |
| Lenovo        | ThinkPad T440p 20AWS4N90... | Notebook    | [367e64b3ed](https://linux-hardware.org/?probe=367e64b3ed) | Oct 12, 2024 |
| HP            | 8299                        | Desktop     | [7b4baeb3bb](https://linux-hardware.org/?probe=7b4baeb3bb) | Oct 11, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [4a7041c67c](https://linux-hardware.org/?probe=4a7041c67c) | Oct 11, 2024 |
| HP            | 82F1                        | Desktop     | [cb91c8b3a6](https://linux-hardware.org/?probe=cb91c8b3a6) | Oct 11, 2024 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [0e5cca17fe](https://linux-hardware.org/?probe=0e5cca17fe) | Oct 10, 2024 |
| Lenovo        | B51-80 80LM                 | Notebook    | [aa39bd173c](https://linux-hardware.org/?probe=aa39bd173c) | Oct 09, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [36203d895d](https://linux-hardware.org/?probe=36203d895d) | Oct 08, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f039fec17f](https://linux-hardware.org/?probe=f039fec17f) | Oct 08, 2024 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [031f820ae5](https://linux-hardware.org/?probe=031f820ae5) | Oct 07, 2024 |
| Dell          | XPS L322X                   | Notebook    | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| Intel         | H61                         | Desktop     | [f7d3219060](https://linux-hardware.org/?probe=f7d3219060) | Oct 07, 2024 |
| Intel         | H61                         | Desktop     | [bac391f6ce](https://linux-hardware.org/?probe=bac391f6ce) | Oct 07, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [154b1e5c1b](https://linux-hardware.org/?probe=154b1e5c1b) | Oct 07, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [6be09afc6e](https://linux-hardware.org/?probe=6be09afc6e) | Oct 05, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [61239b6939](https://linux-hardware.org/?probe=61239b6939) | Oct 03, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [aa1afeaff4](https://linux-hardware.org/?probe=aa1afeaff4) | Oct 03, 2024 |
| Acer          | EQ45M                       | Desktop     | [0d9b3aab5f](https://linux-hardware.org/?probe=0d9b3aab5f) | Oct 02, 2024 |
| Dell          | Latitude D830               | Notebook    | [f34a4dda6a](https://linux-hardware.org/?probe=f34a4dda6a) | Oct 01, 2024 |
| Dell          | Latitude E7440              | Notebook    | [e214523782](https://linux-hardware.org/?probe=e214523782) | Oct 01, 2024 |
| Intel         | X99                         | Desktop     | [02e8e3a503](https://linux-hardware.org/?probe=02e8e3a503) | Oct 01, 2024 |
| SZMZ          | X99M-G2                     | Desktop     | [382a390721](https://linux-hardware.org/?probe=382a390721) | Oct 01, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6e019fd901](https://linux-hardware.org/?probe=6e019fd901) | Sep 30, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [ef3968a3cc](https://linux-hardware.org/?probe=ef3968a3cc) | Sep 30, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [e4398bf85e](https://linux-hardware.org/?probe=e4398bf85e) | Sep 30, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [6629e094c4](https://linux-hardware.org/?probe=6629e094c4) | Sep 28, 2024 |
| MSI           | MS-B120                     | Mini pc     | [fa5df37ed3](https://linux-hardware.org/?probe=fa5df37ed3) | Sep 28, 2024 |
| ASUSTek       | UX305FA                     | Notebook    | [cab58b19a5](https://linux-hardware.org/?probe=cab58b19a5) | Sep 27, 2024 |
| HP            | 8266                        | Desktop     | [e604dee3de](https://linux-hardware.org/?probe=e604dee3de) | Sep 26, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [4422a8ed1b](https://linux-hardware.org/?probe=4422a8ed1b) | Sep 26, 2024 |
| Acer          | Aspire 8735                 | Notebook    | [1e9253098c](https://linux-hardware.org/?probe=1e9253098c) | Sep 24, 2024 |
| MSI           | H410M PRO                   | Desktop     | [6644a178d7](https://linux-hardware.org/?probe=6644a178d7) | Sep 22, 2024 |
| MouseCompu... | W110ER                      | Notebook    | [8ec07c61c5](https://linux-hardware.org/?probe=8ec07c61c5) | Sep 22, 2024 |
| Gigabyte      | H67MA-UD2H-B3               | Desktop     | [21b8f6e55c](https://linux-hardware.org/?probe=21b8f6e55c) | Sep 21, 2024 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [baed1e9059](https://linux-hardware.org/?probe=baed1e9059) | Sep 17, 2024 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4f85171760](https://linux-hardware.org/?probe=4f85171760) | Sep 17, 2024 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [9146d15a3b](https://linux-hardware.org/?probe=9146d15a3b) | Sep 16, 2024 |
| Gateway       | NV55C                       | Notebook    | [151ce02b0c](https://linux-hardware.org/?probe=151ce02b0c) | Sep 16, 2024 |
| Gateway       | NV55C                       | Notebook    | [f7170c1236](https://linux-hardware.org/?probe=f7170c1236) | Sep 16, 2024 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [0ecccff1eb](https://linux-hardware.org/?probe=0ecccff1eb) | Sep 16, 2024 |
| HP            | 8298                        | Desktop     | [33696766f2](https://linux-hardware.org/?probe=33696766f2) | Sep 15, 2024 |
| HP            | ProBook 4710s               | Notebook    | [e6ca3a8cfc](https://linux-hardware.org/?probe=e6ca3a8cfc) | Sep 13, 2024 |
| Lenovo        | ThinkPad E490 20N8005AAD    | Notebook    | [4e5ac9e97e](https://linux-hardware.org/?probe=4e5ac9e97e) | Sep 13, 2024 |
| Lenovo        | B50-70 20384                | Notebook    | [1f0591024e](https://linux-hardware.org/?probe=1f0591024e) | Sep 12, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [730aa21a44](https://linux-hardware.org/?probe=730aa21a44) | Sep 12, 2024 |
| MSI           | MS-B120                     | Mini pc     | [92b13d7a99](https://linux-hardware.org/?probe=92b13d7a99) | Sep 11, 2024 |
| Fujitsu       | D3502-A1 S26361-D3502-A1    | Desktop     | [8b9b0365cf](https://linux-hardware.org/?probe=8b9b0365cf) | Sep 10, 2024 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [72ced99036](https://linux-hardware.org/?probe=72ced99036) | Sep 10, 2024 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [846c96bd78](https://linux-hardware.org/?probe=846c96bd78) | Sep 10, 2024 |
| Lenovo        | ThinkPad P53 20QQS2Q500     | Notebook    | [f59c986142](https://linux-hardware.org/?probe=f59c986142) | Sep 08, 2024 |
| Lenovo        | ThinkPad P53 20QQS2Q500     | Notebook    | [036064fb7d](https://linux-hardware.org/?probe=036064fb7d) | Sep 08, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [759b1d1403](https://linux-hardware.org/?probe=759b1d1403) | Sep 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [7582b12cfa](https://linux-hardware.org/?probe=7582b12cfa) | Sep 07, 2024 |
| MSI           | MS-B120                     | Mini pc     | [7f4be3e611](https://linux-hardware.org/?probe=7f4be3e611) | Sep 07, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [8162d57622](https://linux-hardware.org/?probe=8162d57622) | Sep 06, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [397c9cafae](https://linux-hardware.org/?probe=397c9cafae) | Sep 06, 2024 |
| ASUSTek       | P6T SE                      | Desktop     | [42f319ff6b](https://linux-hardware.org/?probe=42f319ff6b) | Sep 05, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [ce640045ef](https://linux-hardware.org/?probe=ce640045ef) | Sep 03, 2024 |
| HP            | 0A64h                       | Desktop     | [235a192f9e](https://linux-hardware.org/?probe=235a192f9e) | Sep 03, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [873b9f8491](https://linux-hardware.org/?probe=873b9f8491) | Aug 31, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [bb66d6b606](https://linux-hardware.org/?probe=bb66d6b606) | Aug 31, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [4c3b6cd503](https://linux-hardware.org/?probe=4c3b6cd503) | Aug 30, 2024 |
| Dell          | Precision M4800             | Notebook    | [a4be7a565a](https://linux-hardware.org/?probe=a4be7a565a) | Aug 29, 2024 |
| Dell          | Precision M4800             | Notebook    | [825bca67dc](https://linux-hardware.org/?probe=825bca67dc) | Aug 29, 2024 |
| ASRock        | Z77E-ITX                    | Desktop     | [142d4baaa5](https://linux-hardware.org/?probe=142d4baaa5) | Aug 28, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d588f28882](https://linux-hardware.org/?probe=d588f28882) | Aug 28, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [90fc0ae285](https://linux-hardware.org/?probe=90fc0ae285) | Aug 28, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8c4be8ba0d](https://linux-hardware.org/?probe=8c4be8ba0d) | Aug 27, 2024 |
| ASUSTek       | K52F                        | Notebook    | [7a928c36ce](https://linux-hardware.org/?probe=7a928c36ce) | Aug 26, 2024 |
| Dell          | Latitude 7410               | Notebook    | [a7eb8d9d58](https://linux-hardware.org/?probe=a7eb8d9d58) | Aug 26, 2024 |
| MSI           | MS-B120                     | Mini pc     | [565c06e5c7](https://linux-hardware.org/?probe=565c06e5c7) | Aug 25, 2024 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [5cd382e3a4](https://linux-hardware.org/?probe=5cd382e3a4) | Aug 25, 2024 |
| Dell          | Latitude 3420               | Notebook    | [f13d050d62](https://linux-hardware.org/?probe=f13d050d62) | Aug 21, 2024 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [84c6c853c6](https://linux-hardware.org/?probe=84c6c853c6) | Aug 19, 2024 |
| HP            | 470 17 inch G10 Notebook... | Notebook    | [1b5b2201b3](https://linux-hardware.org/?probe=1b5b2201b3) | Aug 18, 2024 |
| HP            | 470 17 inch G10 Notebook... | Notebook    | [f96763850e](https://linux-hardware.org/?probe=f96763850e) | Aug 18, 2024 |
| Mini PC       | Rev ADLN62                  | Mini pc     | [2f5d9a6f7e](https://linux-hardware.org/?probe=2f5d9a6f7e) | Aug 16, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [4fd40665fe](https://linux-hardware.org/?probe=4fd40665fe) | Aug 15, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [752565b32e](https://linux-hardware.org/?probe=752565b32e) | Aug 15, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8fadf1536a](https://linux-hardware.org/?probe=8fadf1536a) | Aug 15, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [72a76100c0](https://linux-hardware.org/?probe=72a76100c0) | Aug 14, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [8c4795ad22](https://linux-hardware.org/?probe=8c4795ad22) | Aug 13, 2024 |
| Intel         | 945GCT-M                    | Desktop     | [105ce7af34](https://linux-hardware.org/?probe=105ce7af34) | Aug 10, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [58929eebee](https://linux-hardware.org/?probe=58929eebee) | Aug 09, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [b69646717f](https://linux-hardware.org/?probe=b69646717f) | Aug 07, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [1130f68b30](https://linux-hardware.org/?probe=1130f68b30) | Aug 04, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6aac77b86c](https://linux-hardware.org/?probe=6aac77b86c) | Aug 04, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [3cd7fba406](https://linux-hardware.org/?probe=3cd7fba406) | Aug 02, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [18231f879f](https://linux-hardware.org/?probe=18231f879f) | Jul 31, 2024 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [a54338842b](https://linux-hardware.org/?probe=a54338842b) | Jul 31, 2024 |
| Dell          | XPS L322X                   | Notebook    | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | Notebook    | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Lenovo        | ThinkPad L512 2597W1R       | Notebook    | [30c12bace2](https://linux-hardware.org/?probe=30c12bace2) | Jul 30, 2024 |
| ASRock        | Z690 Pro RS                 | Desktop     | [e3765bd2ff](https://linux-hardware.org/?probe=e3765bd2ff) | Jul 30, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [f223f80f64](https://linux-hardware.org/?probe=f223f80f64) | Jul 30, 2024 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [8b17202e4d](https://linux-hardware.org/?probe=8b17202e4d) | Jul 29, 2024 |
| Dell          | Precision M4800             | Notebook    | [50f7d3e735](https://linux-hardware.org/?probe=50f7d3e735) | Jul 28, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [34e2d2c812](https://linux-hardware.org/?probe=34e2d2c812) | Jul 27, 2024 |
| MSI           | MS-B120                     | Mini pc     | [cef31a325c](https://linux-hardware.org/?probe=cef31a325c) | Jul 27, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [ba43243222](https://linux-hardware.org/?probe=ba43243222) | Jul 26, 2024 |
| HP            | 2AF7                        | Desktop     | [09f9029668](https://linux-hardware.org/?probe=09f9029668) | Jul 25, 2024 |
| HP            | 2AF7                        | Desktop     | [2d3a654d52](https://linux-hardware.org/?probe=2d3a654d52) | Jul 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [7bf0973685](https://linux-hardware.org/?probe=7bf0973685) | Jul 24, 2024 |
| HP            | Presario CQ62               | Notebook    | [51d98b56a6](https://linux-hardware.org/?probe=51d98b56a6) | Jul 23, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [b1883fc0b9](https://linux-hardware.org/?probe=b1883fc0b9) | Jul 20, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [938ac7f923](https://linux-hardware.org/?probe=938ac7f923) | Jul 20, 2024 |
| Lenovo        | U310                        | Notebook    | [bc65662bc6](https://linux-hardware.org/?probe=bc65662bc6) | Jul 20, 2024 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [6f1800773c](https://linux-hardware.org/?probe=6f1800773c) | Jul 19, 2024 |
| Dell          | 040DDP A01                  | Desktop     | [bf9438a172](https://linux-hardware.org/?probe=bf9438a172) | Jul 17, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | Notebook    | [4ede9f000b](https://linux-hardware.org/?probe=4ede9f000b) | Jul 17, 2024 |
| System76      | Pangolin                    | Notebook    | [2f97d7a936](https://linux-hardware.org/?probe=2f97d7a936) | Jul 16, 2024 |
| Dell          | Latitude E6400              | Notebook    | [6902c998ab](https://linux-hardware.org/?probe=6902c998ab) | Jul 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [59c3b16f4d](https://linux-hardware.org/?probe=59c3b16f4d) | Jul 14, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [fd49810070](https://linux-hardware.org/?probe=fd49810070) | Jul 14, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [ff13f5f94f](https://linux-hardware.org/?probe=ff13f5f94f) | Jul 11, 2024 |
| Gigabyte      | B550M K                     | Desktop     | [c4a4380ddc](https://linux-hardware.org/?probe=c4a4380ddc) | Jul 11, 2024 |
| Medion        | P8610                       | Notebook    | [a39e7058a3](https://linux-hardware.org/?probe=a39e7058a3) | Jul 09, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [ee229c57c4](https://linux-hardware.org/?probe=ee229c57c4) | Jul 08, 2024 |
| MSI           | MS-B120                     | Mini pc     | [e41e11b1e0](https://linux-hardware.org/?probe=e41e11b1e0) | Jul 07, 2024 |
| Dell          | Inspiron 5566               | Notebook    | [8ccf248b6a](https://linux-hardware.org/?probe=8ccf248b6a) | Jul 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [a9ffcc9574](https://linux-hardware.org/?probe=a9ffcc9574) | Jul 07, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [ffbf7e5b14](https://linux-hardware.org/?probe=ffbf7e5b14) | Jul 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [d332637cfe](https://linux-hardware.org/?probe=d332637cfe) | Jul 07, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [bca863a045](https://linux-hardware.org/?probe=bca863a045) | Jul 05, 2024 |
| Acer          | AOD270                      | Notebook    | [ed5489a7bb](https://linux-hardware.org/?probe=ed5489a7bb) | Jul 04, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [164247c308](https://linux-hardware.org/?probe=164247c308) | Jul 04, 2024 |
| Gigabyte      | B460 HD3                    | Desktop     | [324898f64e](https://linux-hardware.org/?probe=324898f64e) | Jul 02, 2024 |
| AMI           | Intel                       | Desktop     | [5d8240cda1](https://linux-hardware.org/?probe=5d8240cda1) | Jun 26, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [febacdca60](https://linux-hardware.org/?probe=febacdca60) | Jun 25, 2024 |
| ZOTAC         | ZBOX-EN374070C              | Mini pc     | [71009c6209](https://linux-hardware.org/?probe=71009c6209) | Jun 25, 2024 |
| Dell          | Studio 1558                 | Notebook    | [42102615c5](https://linux-hardware.org/?probe=42102615c5) | Jun 23, 2024 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [db6a8b188d](https://linux-hardware.org/?probe=db6a8b188d) | Jun 23, 2024 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [09ffa0d065](https://linux-hardware.org/?probe=09ffa0d065) | Jun 23, 2024 |
| HP            | Pavilion dv4                | Notebook    | [4d8fa0dcd3](https://linux-hardware.org/?probe=4d8fa0dcd3) | Jun 23, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [75cff17c2a](https://linux-hardware.org/?probe=75cff17c2a) | Jun 22, 2024 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [d73f02434e](https://linux-hardware.org/?probe=d73f02434e) | Jun 21, 2024 |
| AMI           | Intel                       | Desktop     | [1450c0246f](https://linux-hardware.org/?probe=1450c0246f) | Jun 20, 2024 |
| HP            | Compaq 6715s (GS561AV)      | Notebook    | [858c238b03](https://linux-hardware.org/?probe=858c238b03) | Jun 19, 2024 |
| Dell          | Latitude 5531               | Notebook    | [372b0ebce1](https://linux-hardware.org/?probe=372b0ebce1) | Jun 18, 2024 |
| Dell          | XPS L322X                   | Notebook    | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | Notebook    | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Lenovo        | ThinkPad E490 20N80029GE    | Notebook    | [9ef0735764](https://linux-hardware.org/?probe=9ef0735764) | Jun 17, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [a448de0f44](https://linux-hardware.org/?probe=a448de0f44) | Jun 15, 2024 |
| Dell          | 0MWYPT A02                  | Desktop     | [0188202fa9](https://linux-hardware.org/?probe=0188202fa9) | Jun 14, 2024 |
| Dell          | 0NNNCT A01                  | Desktop     | [9cd3c023df](https://linux-hardware.org/?probe=9cd3c023df) | Jun 13, 2024 |
| HP            | EliteBook 745 G4            | Notebook    | [c317306129](https://linux-hardware.org/?probe=c317306129) | Jun 13, 2024 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [2445a991d8](https://linux-hardware.org/?probe=2445a991d8) | Jun 06, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [75f4137d21](https://linux-hardware.org/?probe=75f4137d21) | Jun 06, 2024 |
| Dell          | 032W55 A03                  | Desktop     | [0bf4dbd092](https://linux-hardware.org/?probe=0bf4dbd092) | Jun 04, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [720d7ca6cb](https://linux-hardware.org/?probe=720d7ca6cb) | May 31, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [0429104dcc](https://linux-hardware.org/?probe=0429104dcc) | May 30, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [35684afb98](https://linux-hardware.org/?probe=35684afb98) | May 28, 2024 |
| ASUSTek       | M5A78L LE                   | Desktop     | [5afe282618](https://linux-hardware.org/?probe=5afe282618) | May 27, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [6ec64c0b1c](https://linux-hardware.org/?probe=6ec64c0b1c) | May 27, 2024 |
| HP            | 355 G2                      | Notebook    | [3a458e83e5](https://linux-hardware.org/?probe=3a458e83e5) | May 26, 2024 |
| HP            | 355 G2                      | Notebook    | [8b28adff93](https://linux-hardware.org/?probe=8b28adff93) | May 26, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [134bad9ba1](https://linux-hardware.org/?probe=134bad9ba1) | May 25, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [fbfb9ee390](https://linux-hardware.org/?probe=fbfb9ee390) | May 24, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [9bc61751b1](https://linux-hardware.org/?probe=9bc61751b1) | May 24, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [5618803794](https://linux-hardware.org/?probe=5618803794) | May 21, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [36eb3289fa](https://linux-hardware.org/?probe=36eb3289fa) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [a667660a0c](https://linux-hardware.org/?probe=a667660a0c) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [146a53575b](https://linux-hardware.org/?probe=146a53575b) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1d905f7200](https://linux-hardware.org/?probe=1d905f7200) | May 15, 2024 |
| Lenovo        | ThinkStation S30 0606AD5    | Desktop     | [81204f95a0](https://linux-hardware.org/?probe=81204f95a0) | May 15, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2ddbbe35d9](https://linux-hardware.org/?probe=2ddbbe35d9) | May 14, 2024 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [2c44032705](https://linux-hardware.org/?probe=2c44032705) | May 12, 2024 |
| ASUSTek       | A6Rp                        | Notebook    | [6cf464d3ec](https://linux-hardware.org/?probe=6cf464d3ec) | May 12, 2024 |
| Acer          | Extensa 2540                | Notebook    | [f76fc7e870](https://linux-hardware.org/?probe=f76fc7e870) | May 11, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [2d829398cc](https://linux-hardware.org/?probe=2d829398cc) | May 11, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [ee086eec1f](https://linux-hardware.org/?probe=ee086eec1f) | May 09, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [58b9bbc4d6](https://linux-hardware.org/?probe=58b9bbc4d6) | May 08, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [14c3adea64](https://linux-hardware.org/?probe=14c3adea64) | May 08, 2024 |
| Intel         | STCK1A32WFC H67490-302      | Notebook    | [51c75f3848](https://linux-hardware.org/?probe=51c75f3848) | May 08, 2024 |
| MSI           | MS-B120                     | Mini pc     | [29451ebbbb](https://linux-hardware.org/?probe=29451ebbbb) | May 08, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [b139a58ea9](https://linux-hardware.org/?probe=b139a58ea9) | May 07, 2024 |
| eMachines     | WMCP61M                     | Desktop     | [54b1a18c59](https://linux-hardware.org/?probe=54b1a18c59) | May 06, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [52037a51a0](https://linux-hardware.org/?probe=52037a51a0) | May 06, 2024 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [1820a973e3](https://linux-hardware.org/?probe=1820a973e3) | May 05, 2024 |
| Lenovo        | ThinkPad X240 20ALA08VRT    | Notebook    | [b894f49df3](https://linux-hardware.org/?probe=b894f49df3) | May 05, 2024 |
| Lenovo        | ThinkPad L512 2597W1R       | Notebook    | [d7cb3b5ddd](https://linux-hardware.org/?probe=d7cb3b5ddd) | May 05, 2024 |
| ASUSTek       | E5402WHA                    | All in one  | [899d2f931f](https://linux-hardware.org/?probe=899d2f931f) | May 04, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [151ab0d8e9](https://linux-hardware.org/?probe=151ab0d8e9) | May 01, 2024 |
| HP            | ENVY m7 Notebook            | Notebook    | [4403370d84](https://linux-hardware.org/?probe=4403370d84) | Apr 28, 2024 |
| Dell          | Latitude 5420               | Notebook    | [1fa9f586bb](https://linux-hardware.org/?probe=1fa9f586bb) | Apr 27, 2024 |
| Dell          | Latitude 5420               | Notebook    | [5c878504f5](https://linux-hardware.org/?probe=5c878504f5) | Apr 27, 2024 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [1680c3ad15](https://linux-hardware.org/?probe=1680c3ad15) | Apr 27, 2024 |
| MSI           | MS-B120                     | Mini pc     | [8c52f15119](https://linux-hardware.org/?probe=8c52f15119) | Apr 23, 2024 |
| Morshow       | v1.0                        | Mini pc     | [cc244a6fc6](https://linux-hardware.org/?probe=cc244a6fc6) | Apr 22, 2024 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [3fa1ba6009](https://linux-hardware.org/?probe=3fa1ba6009) | Apr 22, 2024 |
| Morshow       | v1.0                        | Mini pc     | [e4198c0587](https://linux-hardware.org/?probe=e4198c0587) | Apr 22, 2024 |
| Lenovo        | G70-70 80HW                 | Notebook    | [73f307b60b](https://linux-hardware.org/?probe=73f307b60b) | Apr 20, 2024 |
| ASRock        | B650E Taichi                | Desktop     | [cdd2468f64](https://linux-hardware.org/?probe=cdd2468f64) | Apr 20, 2024 |
| AMI           | Unknown                     | Notebook    | [8330483e6e](https://linux-hardware.org/?probe=8330483e6e) | Apr 20, 2024 |
| Toshiba       | STI 001387                  | Desktop     | [240e193806](https://linux-hardware.org/?probe=240e193806) | Apr 20, 2024 |
| Gigabyte      | H97M-D3H                    | Desktop     | [15a0f07250](https://linux-hardware.org/?probe=15a0f07250) | Apr 20, 2024 |
| HP            | ProBook 470 G1              | Notebook    | [a400b6efad](https://linux-hardware.org/?probe=a400b6efad) | Apr 17, 2024 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d7337f7684](https://linux-hardware.org/?probe=d7337f7684) | Apr 17, 2024 |
| Dell          | Latitude 5410               | Notebook    | [700b37dcf0](https://linux-hardware.org/?probe=700b37dcf0) | Apr 16, 2024 |
| MSI           | GF75 Thin 10SC              | Notebook    | [7ab70feffe](https://linux-hardware.org/?probe=7ab70feffe) | Apr 16, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [de6f248fc2](https://linux-hardware.org/?probe=de6f248fc2) | Apr 14, 2024 |
| HP            | Pavilion 13 x2 PC           | Notebook    | [684e30a2e3](https://linux-hardware.org/?probe=684e30a2e3) | Apr 13, 2024 |
| HP            | Pavilion 13 x2 PC           | Notebook    | [60d693276a](https://linux-hardware.org/?probe=60d693276a) | Apr 13, 2024 |
| ASRock        | J4105B-ITX                  | Desktop     | [ecb84ecf2a](https://linux-hardware.org/?probe=ecb84ecf2a) | Apr 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [b6a43ddde6](https://linux-hardware.org/?probe=b6a43ddde6) | Apr 11, 2024 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [20fe73c7f9](https://linux-hardware.org/?probe=20fe73c7f9) | Apr 11, 2024 |
| ASUSTek       | H97M-E                      | Desktop     | [431b3ef7f6](https://linux-hardware.org/?probe=431b3ef7f6) | Apr 11, 2024 |
| ASUSTek       | M4A78-E                     | Desktop     | [206d758570](https://linux-hardware.org/?probe=206d758570) | Apr 10, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23e552156c](https://linux-hardware.org/?probe=23e552156c) | Apr 09, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [313d012a75](https://linux-hardware.org/?probe=313d012a75) | Apr 09, 2024 |
| HP            | EliteBook 2760p             | Notebook    | [37781c3e84](https://linux-hardware.org/?probe=37781c3e84) | Apr 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [e8546100eb](https://linux-hardware.org/?probe=e8546100eb) | Apr 07, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a130a64c11](https://linux-hardware.org/?probe=a130a64c11) | Apr 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [ac2a7ce77d](https://linux-hardware.org/?probe=ac2a7ce77d) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [1ada20ef48](https://linux-hardware.org/?probe=1ada20ef48) | Apr 06, 2024 |
| AMI           | Unknown                     | Notebook    | [e52668ee27](https://linux-hardware.org/?probe=e52668ee27) | Apr 05, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [9a68d90ab7](https://linux-hardware.org/?probe=9a68d90ab7) | Apr 05, 2024 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [64c55b79df](https://linux-hardware.org/?probe=64c55b79df) | Apr 04, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [4f2bc03aca](https://linux-hardware.org/?probe=4f2bc03aca) | Apr 04, 2024 |
| ASRock        | B650M-H/M.2+                | Desktop     | [38f4136e38](https://linux-hardware.org/?probe=38f4136e38) | Apr 03, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a7a78cd117](https://linux-hardware.org/?probe=a7a78cd117) | Apr 02, 2024 |
| Dell          | 032W55 A03                  | Desktop     | [5943c24943](https://linux-hardware.org/?probe=5943c24943) | Apr 01, 2024 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [20959b9997](https://linux-hardware.org/?probe=20959b9997) | Apr 01, 2024 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [42117baa72](https://linux-hardware.org/?probe=42117baa72) | Apr 01, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [cff197ffbf](https://linux-hardware.org/?probe=cff197ffbf) | Mar 30, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | Notebook    | [3709076728](https://linux-hardware.org/?probe=3709076728) | Mar 30, 2024 |
| Dell          | 02YRK5 A02                  | Desktop     | [4c860be642](https://linux-hardware.org/?probe=4c860be642) | Mar 29, 2024 |
| Toshiba       | Satellite C70D-A            | Notebook    | [8489c1e38c](https://linux-hardware.org/?probe=8489c1e38c) | Mar 28, 2024 |
| Dell          | Latitude 3410               | Notebook    | [3aee33bb58](https://linux-hardware.org/?probe=3aee33bb58) | Mar 27, 2024 |
| Monster       | ABRA A5 V17.4               | Notebook    | [153af2c8d9](https://linux-hardware.org/?probe=153af2c8d9) | Mar 23, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [61d0ee2736](https://linux-hardware.org/?probe=61d0ee2736) | Mar 22, 2024 |
| Gigabyte      | H87-HD3                     | Desktop     | [39e7b8c321](https://linux-hardware.org/?probe=39e7b8c321) | Mar 22, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | Notebook    | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Toshiba       | PORTEGE R500                | Notebook    | [33c598fc6e](https://linux-hardware.org/?probe=33c598fc6e) | Mar 21, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [5d5d06eab9](https://linux-hardware.org/?probe=5d5d06eab9) | Mar 20, 2024 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [624e1874e9](https://linux-hardware.org/?probe=624e1874e9) | Mar 20, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fc818b5a1b](https://linux-hardware.org/?probe=fc818b5a1b) | Mar 18, 2024 |
| Lenovo        | ThinkStation S30 0606AD5    | Desktop     | [8a703c6f02](https://linux-hardware.org/?probe=8a703c6f02) | Mar 17, 2024 |
| Lenovo        | Z710 20250                  | Notebook    | [60c82a772a](https://linux-hardware.org/?probe=60c82a772a) | Mar 17, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [e2617d5a43](https://linux-hardware.org/?probe=e2617d5a43) | Mar 17, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [5f37f98222](https://linux-hardware.org/?probe=5f37f98222) | Mar 16, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [78ad2387d5](https://linux-hardware.org/?probe=78ad2387d5) | Mar 15, 2024 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [bb52ad6052](https://linux-hardware.org/?probe=bb52ad6052) | Mar 15, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0fbeb0332d](https://linux-hardware.org/?probe=0fbeb0332d) | Mar 14, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [668f06dbdf](https://linux-hardware.org/?probe=668f06dbdf) | Mar 14, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad2e487982](https://linux-hardware.org/?probe=ad2e487982) | Mar 12, 2024 |
| Sony          | SVE1712T1EB                 | Notebook    | [a01a793d3b](https://linux-hardware.org/?probe=a01a793d3b) | Mar 12, 2024 |
| Sony          | SVE1712T1EB                 | Notebook    | [2bc7cadf31](https://linux-hardware.org/?probe=2bc7cadf31) | Mar 12, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [daec1c4210](https://linux-hardware.org/?probe=daec1c4210) | Mar 11, 2024 |
| ASUSTek       | UX31E                       | Notebook    | [94fc346288](https://linux-hardware.org/?probe=94fc346288) | Mar 10, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [c22c7f9510](https://linux-hardware.org/?probe=c22c7f9510) | Mar 10, 2024 |
| MSI           | MS-B120                     | Mini pc     | [8d182b3c8c](https://linux-hardware.org/?probe=8d182b3c8c) | Mar 09, 2024 |
| Dell          | Latitude 3410               | Notebook    | [5ea9fa7a7c](https://linux-hardware.org/?probe=5ea9fa7a7c) | Mar 07, 2024 |
| MSI           | MS-B120                     | Mini pc     | [18c75fd8f9](https://linux-hardware.org/?probe=18c75fd8f9) | Mar 05, 2024 |
| MSI           | Katana GF66 12UC            | Notebook    | [13e9499bcc](https://linux-hardware.org/?probe=13e9499bcc) | Mar 05, 2024 |
| MSI           | Katana GF66 12UC            | Notebook    | [27e54c1325](https://linux-hardware.org/?probe=27e54c1325) | Mar 05, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e053d06a2d](https://linux-hardware.org/?probe=e053d06a2d) | Mar 04, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [6cffe59389](https://linux-hardware.org/?probe=6cffe59389) | Mar 02, 2024 |
| HP            | Notebook                    | Notebook    | [9b7a8a0478](https://linux-hardware.org/?probe=9b7a8a0478) | Feb 29, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [aeee54cee7](https://linux-hardware.org/?probe=aeee54cee7) | Feb 27, 2024 |
| Dell          | Precision 5550              | Notebook    | [59677e206f](https://linux-hardware.org/?probe=59677e206f) | Feb 27, 2024 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [51dde30452](https://linux-hardware.org/?probe=51dde30452) | Feb 25, 2024 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [05c2196fd2](https://linux-hardware.org/?probe=05c2196fd2) | Feb 25, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [69ef5f3bb0](https://linux-hardware.org/?probe=69ef5f3bb0) | Feb 24, 2024 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [f193f8bd36](https://linux-hardware.org/?probe=f193f8bd36) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d4ac4dafa1](https://linux-hardware.org/?probe=d4ac4dafa1) | Feb 23, 2024 |
| Biostar       | B450MHP                     | Desktop     | [5c5906ef27](https://linux-hardware.org/?probe=5c5906ef27) | Feb 21, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [645bf6be84](https://linux-hardware.org/?probe=645bf6be84) | Feb 20, 2024 |
| Dell          | Latitude 5590               | Notebook    | [e25be34559](https://linux-hardware.org/?probe=e25be34559) | Feb 19, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [3c40fa1a9f](https://linux-hardware.org/?probe=3c40fa1a9f) | Feb 19, 2024 |
| Dell          | Latitude E5550              | Notebook    | [8f96e62eaf](https://linux-hardware.org/?probe=8f96e62eaf) | Feb 18, 2024 |
| Biostar       | B450MHP                     | Desktop     | [81eca30554](https://linux-hardware.org/?probe=81eca30554) | Feb 18, 2024 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [8bb363d9be](https://linux-hardware.org/?probe=8bb363d9be) | Feb 18, 2024 |
| Dell          | OptiPlex 980                | Desktop     | [9554536e5f](https://linux-hardware.org/?probe=9554536e5f) | Feb 18, 2024 |
| Biostar       | B450MHP                     | Desktop     | [1c50343bc4](https://linux-hardware.org/?probe=1c50343bc4) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [ff0a6068a5](https://linux-hardware.org/?probe=ff0a6068a5) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [5ad9c09f49](https://linux-hardware.org/?probe=5ad9c09f49) | Feb 16, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a90ac1ac4](https://linux-hardware.org/?probe=1a90ac1ac4) | Feb 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b4a782dfca](https://linux-hardware.org/?probe=b4a782dfca) | Feb 15, 2024 |
| Acer          | Extensa 215-22              | Notebook    | [a7faa9b520](https://linux-hardware.org/?probe=a7faa9b520) | Feb 14, 2024 |
| MSI           | MS-B120                     | Mini pc     | [ea5bf7fa17](https://linux-hardware.org/?probe=ea5bf7fa17) | Feb 11, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [953b2c870f](https://linux-hardware.org/?probe=953b2c870f) | Feb 11, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
| Dell          | Precision 7520              | Notebook    | [3ba06d2c0d](https://linux-hardware.org/?probe=3ba06d2c0d) | Feb 08, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | Notebook    | [1d5c5c6bdc](https://linux-hardware.org/?probe=1d5c5c6bdc) | Feb 07, 2024 |
| Lenovo        | ThinkCentre A58 75227MG     | Desktop     | [bf324db579](https://linux-hardware.org/?probe=bf324db579) | Feb 07, 2024 |
| MSI           | PRO H510M-B                 | Desktop     | [1d9804ffcc](https://linux-hardware.org/?probe=1d9804ffcc) | Feb 03, 2024 |
| HP            | Pavilion m6                 | Notebook    | [f12679a936](https://linux-hardware.org/?probe=f12679a936) | Feb 03, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [dbe298a22e](https://linux-hardware.org/?probe=dbe298a22e) | Feb 03, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [6259b53b1c](https://linux-hardware.org/?probe=6259b53b1c) | Feb 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [7def8ee544](https://linux-hardware.org/?probe=7def8ee544) | Feb 01, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c62ec1a167](https://linux-hardware.org/?probe=c62ec1a167) | Jan 31, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [6f8f587ec5](https://linux-hardware.org/?probe=6f8f587ec5) | Jan 30, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [091fe8d216](https://linux-hardware.org/?probe=091fe8d216) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1069da15da](https://linux-hardware.org/?probe=1069da15da) | Jan 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7a5a8be027](https://linux-hardware.org/?probe=7a5a8be027) | Jan 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6122c021d6](https://linux-hardware.org/?probe=6122c021d6) | Jan 25, 2024 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [120ebd1d10](https://linux-hardware.org/?probe=120ebd1d10) | Jan 24, 2024 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [434a85ff04](https://linux-hardware.org/?probe=434a85ff04) | Jan 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3dff9ac8f3](https://linux-hardware.org/?probe=3dff9ac8f3) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [bdf8f178f4](https://linux-hardware.org/?probe=bdf8f178f4) | Jan 18, 2024 |
| Dell          | Latitude E5550              | Notebook    | [2887bb49af](https://linux-hardware.org/?probe=2887bb49af) | Jan 17, 2024 |
| System76      | Lemur Ultra                 | Notebook    | [31f8a83abf](https://linux-hardware.org/?probe=31f8a83abf) | Jan 17, 2024 |
| Dell          | 0GDJXY A00                  | All in one  | [3ea400d76d](https://linux-hardware.org/?probe=3ea400d76d) | Jan 17, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [6d71f55994](https://linux-hardware.org/?probe=6d71f55994) | Jan 17, 2024 |
| Dell          | Latitude E5550              | Notebook    | [0755281d4f](https://linux-hardware.org/?probe=0755281d4f) | Jan 16, 2024 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [01eeec96ca](https://linux-hardware.org/?probe=01eeec96ca) | Jan 16, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [192feda06a](https://linux-hardware.org/?probe=192feda06a) | Jan 16, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [1279f6d244](https://linux-hardware.org/?probe=1279f6d244) | Jan 13, 2024 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [8a6e291933](https://linux-hardware.org/?probe=8a6e291933) | Jan 11, 2024 |
| Dell          | Vostro 7620                 | Notebook    | [433547fc16](https://linux-hardware.org/?probe=433547fc16) | Jan 11, 2024 |
| Juniper Sy... | Mesa Pro                    | Tablet      | [9c632df9a1](https://linux-hardware.org/?probe=9c632df9a1) | Jan 10, 2024 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [f46fcb5ee9](https://linux-hardware.org/?probe=f46fcb5ee9) | Jan 10, 2024 |
| Dell          | 032W55 A03                  | Desktop     | [97e3c61a8b](https://linux-hardware.org/?probe=97e3c61a8b) | Jan 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3f33c9082a](https://linux-hardware.org/?probe=3f33c9082a) | Jan 03, 2024 |
| Lenovo        | ThinkCentre M55e 9645W2C    | Desktop     | [7f8c8e496a](https://linux-hardware.org/?probe=7f8c8e496a) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [91413e5760](https://linux-hardware.org/?probe=91413e5760) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [c038b7f7e4](https://linux-hardware.org/?probe=c038b7f7e4) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [cdb97873fa](https://linux-hardware.org/?probe=cdb97873fa) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [f9d4fa4d55](https://linux-hardware.org/?probe=f9d4fa4d55) | Jan 01, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8dab3905db](https://linux-hardware.org/?probe=8dab3905db) | Jan 01, 2024 |
| Gigabyte      | H470M K                     | Desktop     | [90b6ff9ff3](https://linux-hardware.org/?probe=90b6ff9ff3) | Jan 01, 2024 |
| HP            | Laptop 17-cn3xxx            | Notebook    | [3a84122c5a](https://linux-hardware.org/?probe=3a84122c5a) | Dec 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7f2d68d77](https://linux-hardware.org/?probe=c7f2d68d77) | Dec 30, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [10d9fd3230](https://linux-hardware.org/?probe=10d9fd3230) | Dec 30, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [5bd82e2331](https://linux-hardware.org/?probe=5bd82e2331) | Dec 28, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f4820a078b](https://linux-hardware.org/?probe=f4820a078b) | Dec 26, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [d25c8e8312](https://linux-hardware.org/?probe=d25c8e8312) | Dec 26, 2023 |
| Medion        | S6445 MD61281               | Notebook    | [b7db1404b6](https://linux-hardware.org/?probe=b7db1404b6) | Dec 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [87cef435db](https://linux-hardware.org/?probe=87cef435db) | Dec 24, 2023 |
| Clevo         | W760/M770CU                 | Notebook    | [c64bdf2349](https://linux-hardware.org/?probe=c64bdf2349) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b57fdd9854](https://linux-hardware.org/?probe=b57fdd9854) | Dec 24, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [89366f9a48](https://linux-hardware.org/?probe=89366f9a48) | Dec 23, 2023 |
| GPD           | G1621-02                    | Notebook    | [eaf78f9da1](https://linux-hardware.org/?probe=eaf78f9da1) | Dec 22, 2023 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [73408e34a6](https://linux-hardware.org/?probe=73408e34a6) | Dec 21, 2023 |
| HP            | 350 G1                      | Notebook    | [c219133bce](https://linux-hardware.org/?probe=c219133bce) | Dec 20, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [80f7f9c98a](https://linux-hardware.org/?probe=80f7f9c98a) | Dec 20, 2023 |
| Clevo         | W760/M770CU                 | Notebook    | [fdde778b3c](https://linux-hardware.org/?probe=fdde778b3c) | Dec 19, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [f3149a6f22](https://linux-hardware.org/?probe=f3149a6f22) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [da34d3936d](https://linux-hardware.org/?probe=da34d3936d) | Dec 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1446130ae9](https://linux-hardware.org/?probe=1446130ae9) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [80281cb193](https://linux-hardware.org/?probe=80281cb193) | Dec 17, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [b7a7aa8d5d](https://linux-hardware.org/?probe=b7a7aa8d5d) | Dec 17, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [88312d177f](https://linux-hardware.org/?probe=88312d177f) | Dec 16, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [f58535cbfe](https://linux-hardware.org/?probe=f58535cbfe) | Dec 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4b88dcf6b3](https://linux-hardware.org/?probe=4b88dcf6b3) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1a63f79d28](https://linux-hardware.org/?probe=1a63f79d28) | Dec 13, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [cb9765df38](https://linux-hardware.org/?probe=cb9765df38) | Dec 12, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [9a0bb65e3f](https://linux-hardware.org/?probe=9a0bb65e3f) | Dec 12, 2023 |
| HP            | 82DC 1100                   | All in one  | [96f4033f37](https://linux-hardware.org/?probe=96f4033f37) | Dec 12, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [991503ccf4](https://linux-hardware.org/?probe=991503ccf4) | Dec 10, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [5451582602](https://linux-hardware.org/?probe=5451582602) | Dec 08, 2023 |
| MSI           | MS-B120                     | Mini pc     | [51a1cc9143](https://linux-hardware.org/?probe=51a1cc9143) | Dec 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [9c55ae59fe](https://linux-hardware.org/?probe=9c55ae59fe) | Dec 07, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [18a5ca0a40](https://linux-hardware.org/?probe=18a5ca0a40) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [06a0da716b](https://linux-hardware.org/?probe=06a0da716b) | Dec 05, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [3c6a041703](https://linux-hardware.org/?probe=3c6a041703) | Dec 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [3c745928bb](https://linux-hardware.org/?probe=3c745928bb) | Dec 02, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [5f4856fdab](https://linux-hardware.org/?probe=5f4856fdab) | Dec 01, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [bb8295e3fa](https://linux-hardware.org/?probe=bb8295e3fa) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [0d3ea0a6dc](https://linux-hardware.org/?probe=0d3ea0a6dc) | Nov 30, 2023 |
| Acer          | AOD260                      | Notebook    | [20594f9a03](https://linux-hardware.org/?probe=20594f9a03) | Nov 29, 2023 |
| Acer          | AOD260                      | Notebook    | [de50f2993e](https://linux-hardware.org/?probe=de50f2993e) | Nov 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [416fbc3923](https://linux-hardware.org/?probe=416fbc3923) | Nov 28, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [608d264af2](https://linux-hardware.org/?probe=608d264af2) | Nov 27, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [2ecc0c852a](https://linux-hardware.org/?probe=2ecc0c852a) | Nov 27, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [47d33f722e](https://linux-hardware.org/?probe=47d33f722e) | Nov 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5ead75f7bc](https://linux-hardware.org/?probe=5ead75f7bc) | Nov 25, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [5d2574b6cf](https://linux-hardware.org/?probe=5d2574b6cf) | Nov 24, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [5ae0c22a32](https://linux-hardware.org/?probe=5ae0c22a32) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [59444faae7](https://linux-hardware.org/?probe=59444faae7) | Nov 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [7caae1b1a0](https://linux-hardware.org/?probe=7caae1b1a0) | Nov 24, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [502e296060](https://linux-hardware.org/?probe=502e296060) | Nov 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [5c0820855b](https://linux-hardware.org/?probe=5c0820855b) | Nov 23, 2023 |
| Lenovo        | IdeaPad Y460                | Notebook    | [265198a4bc](https://linux-hardware.org/?probe=265198a4bc) | Nov 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [a4cda5b12d](https://linux-hardware.org/?probe=a4cda5b12d) | Nov 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [96d6ec7f1f](https://linux-hardware.org/?probe=96d6ec7f1f) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0a0353d6f](https://linux-hardware.org/?probe=c0a0353d6f) | Nov 20, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [acfd3b6493](https://linux-hardware.org/?probe=acfd3b6493) | Nov 19, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [6a9af286f8](https://linux-hardware.org/?probe=6a9af286f8) | Nov 19, 2023 |
| Dell          | Precision 7760              | Notebook    | [daaf99c63e](https://linux-hardware.org/?probe=daaf99c63e) | Nov 17, 2023 |
| Dell          | Precision 7760              | Notebook    | [50404f0f12](https://linux-hardware.org/?probe=50404f0f12) | Nov 17, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [dfb480c40a](https://linux-hardware.org/?probe=dfb480c40a) | Nov 17, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [9443883eaf](https://linux-hardware.org/?probe=9443883eaf) | Nov 16, 2023 |
| BANGHO        | 1025                        | Notebook    | [d1d51fc17a](https://linux-hardware.org/?probe=d1d51fc17a) | Nov 15, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [9d1c329ebb](https://linux-hardware.org/?probe=9d1c329ebb) | Nov 14, 2023 |
| Dell          | Precision M4800             | Notebook    | [9a63057a12](https://linux-hardware.org/?probe=9a63057a12) | Nov 13, 2023 |
| BANGHO        | 1025                        | Notebook    | [97b39ed05d](https://linux-hardware.org/?probe=97b39ed05d) | Nov 13, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [92930dd0d4](https://linux-hardware.org/?probe=92930dd0d4) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9dd24e5aaa](https://linux-hardware.org/?probe=9dd24e5aaa) | Nov 12, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [a206fa30d7](https://linux-hardware.org/?probe=a206fa30d7) | Nov 11, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [cb1e3547f7](https://linux-hardware.org/?probe=cb1e3547f7) | Nov 10, 2023 |
| Dell          | 0TKD84 A02                  | Server      | [accebd9648](https://linux-hardware.org/?probe=accebd9648) | Nov 10, 2023 |
| Dell          | 0VRCY5 A12                  | Server      | [1bf5a3e96c](https://linux-hardware.org/?probe=1bf5a3e96c) | Nov 08, 2023 |
| MSI           | GL62 6QF                    | Notebook    | [ac1f389364](https://linux-hardware.org/?probe=ac1f389364) | Nov 08, 2023 |
| Dell          | 032W55 A03                  | Desktop     | [8d3db7f790](https://linux-hardware.org/?probe=8d3db7f790) | Nov 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [70cdbefd00](https://linux-hardware.org/?probe=70cdbefd00) | Nov 07, 2023 |
| Lenovo        | T530-28ICB                  | Desktop     | [ba883f99a0](https://linux-hardware.org/?probe=ba883f99a0) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [254a87d641](https://linux-hardware.org/?probe=254a87d641) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [594257aca2](https://linux-hardware.org/?probe=594257aca2) | Nov 03, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [4eae8e67db](https://linux-hardware.org/?probe=4eae8e67db) | Nov 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [602a2268e2](https://linux-hardware.org/?probe=602a2268e2) | Nov 02, 2023 |
| Lenovo        | ThinkPad P53 20QN000FIX     | Notebook    | [40de43c266](https://linux-hardware.org/?probe=40de43c266) | Nov 02, 2023 |
| Google        | Galtic                      | Notebook    | [8945661ada](https://linux-hardware.org/?probe=8945661ada) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d2d21dcf50](https://linux-hardware.org/?probe=d2d21dcf50) | Nov 01, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [e8b0c2a2b5](https://linux-hardware.org/?probe=e8b0c2a2b5) | Oct 31, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ee7bce3de](https://linux-hardware.org/?probe=6ee7bce3de) | Oct 31, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| Panasonic     | CF-53SJCZYLM                | Notebook    | [94941374a2](https://linux-hardware.org/?probe=94941374a2) | Oct 30, 2023 |
| Dell          | Precision 7760              | Notebook    | [eaba0c73b0](https://linux-hardware.org/?probe=eaba0c73b0) | Oct 29, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| VIT           | P1400                       | Notebook    | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [698c3abcba](https://linux-hardware.org/?probe=698c3abcba) | Oct 27, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e9cfada6a4](https://linux-hardware.org/?probe=e9cfada6a4) | Oct 26, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [2129ab3e24](https://linux-hardware.org/?probe=2129ab3e24) | Oct 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | Notebook    | [32743a624c](https://linux-hardware.org/?probe=32743a624c) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | Notebook    | [23d64978d9](https://linux-hardware.org/?probe=23d64978d9) | Oct 24, 2023 |
| Positivo      | C4128G-15                   | Notebook    | [8d9aa2f206](https://linux-hardware.org/?probe=8d9aa2f206) | Oct 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [961c369ea4](https://linux-hardware.org/?probe=961c369ea4) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f19c18154b](https://linux-hardware.org/?probe=f19c18154b) | Oct 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2682d3f618](https://linux-hardware.org/?probe=2682d3f618) | Oct 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [8765923ff6](https://linux-hardware.org/?probe=8765923ff6) | Oct 21, 2023 |
| Acer          | Aspire E3-112M              | Notebook    | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [bc4cc061a2](https://linux-hardware.org/?probe=bc4cc061a2) | Oct 18, 2023 |
| HP            | 3646h                       | Desktop     | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| Hardkernel    | ODROID-C4                   | Soc         | [3a322cbde3](https://linux-hardware.org/?probe=3a322cbde3) | Oct 17, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [f25cb1517e](https://linux-hardware.org/?probe=f25cb1517e) | Oct 12, 2023 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [deb84129fb](https://linux-hardware.org/?probe=deb84129fb) | Oct 10, 2023 |
| ASUSTek       | K50ID                       | Notebook    | [2763bfac4e](https://linux-hardware.org/?probe=2763bfac4e) | Oct 07, 2023 |
| Lenovo        | ThinkPad A275 20KCS09T1G    | Notebook    | [1e797cb20f](https://linux-hardware.org/?probe=1e797cb20f) | Oct 07, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [5d39adb330](https://linux-hardware.org/?probe=5d39adb330) | Oct 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2a4f34aeb4](https://linux-hardware.org/?probe=2a4f34aeb4) | Oct 05, 2023 |
| Google        | Galtic                      | Notebook    | [e838b462a7](https://linux-hardware.org/?probe=e838b462a7) | Oct 04, 2023 |
| Google        | Galtic                      | Notebook    | [cae091837b](https://linux-hardware.org/?probe=cae091837b) | Oct 03, 2023 |
| ASRock        | J4105-ITX                   | Desktop     | [f4d4b23c31](https://linux-hardware.org/?probe=f4d4b23c31) | Oct 02, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [b9b34bef50](https://linux-hardware.org/?probe=b9b34bef50) | Oct 02, 2023 |
| GPD           | G1621-02                    | Notebook    | [10ca9df59f](https://linux-hardware.org/?probe=10ca9df59f) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f510af1acf](https://linux-hardware.org/?probe=f510af1acf) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [8db3bb5b34](https://linux-hardware.org/?probe=8db3bb5b34) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8487059659](https://linux-hardware.org/?probe=8487059659) | Sep 30, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [b952cdd71d](https://linux-hardware.org/?probe=b952cdd71d) | Sep 29, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [390c16a341](https://linux-hardware.org/?probe=390c16a341) | Sep 26, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [64f1cd854d](https://linux-hardware.org/?probe=64f1cd854d) | Sep 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2be1547618](https://linux-hardware.org/?probe=2be1547618) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [89d81885ff](https://linux-hardware.org/?probe=89d81885ff) | Sep 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [450edd6547](https://linux-hardware.org/?probe=450edd6547) | Sep 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [84bba5e5a7](https://linux-hardware.org/?probe=84bba5e5a7) | Sep 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [5fba7d78c6](https://linux-hardware.org/?probe=5fba7d78c6) | Sep 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [f6e9a7233c](https://linux-hardware.org/?probe=f6e9a7233c) | Sep 23, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d00cc6b535](https://linux-hardware.org/?probe=d00cc6b535) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [89cce2b6cb](https://linux-hardware.org/?probe=89cce2b6cb) | Sep 21, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [c5cda29091](https://linux-hardware.org/?probe=c5cda29091) | Sep 21, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [43e04cf99c](https://linux-hardware.org/?probe=43e04cf99c) | Sep 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [00ce48a639](https://linux-hardware.org/?probe=00ce48a639) | Sep 19, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [50023a1d3a](https://linux-hardware.org/?probe=50023a1d3a) | Sep 18, 2023 |
| ASUSTek       | N73SM                       | Notebook    | [d4ce8f336d](https://linux-hardware.org/?probe=d4ce8f336d) | Sep 17, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [670ca9e147](https://linux-hardware.org/?probe=670ca9e147) | Sep 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [103e7031fe](https://linux-hardware.org/?probe=103e7031fe) | Sep 14, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [21932b1004](https://linux-hardware.org/?probe=21932b1004) | Sep 14, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [799a135aca](https://linux-hardware.org/?probe=799a135aca) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [7cea54ec70](https://linux-hardware.org/?probe=7cea54ec70) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [22a0210f8f](https://linux-hardware.org/?probe=22a0210f8f) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [4c56913d07](https://linux-hardware.org/?probe=4c56913d07) | Sep 13, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [820eeccddf](https://linux-hardware.org/?probe=820eeccddf) | Sep 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [03b8175690](https://linux-hardware.org/?probe=03b8175690) | Sep 10, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [5bf280924d](https://linux-hardware.org/?probe=5bf280924d) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [7e478d179a](https://linux-hardware.org/?probe=7e478d179a) | Sep 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd4b5d82ed](https://linux-hardware.org/?probe=bd4b5d82ed) | Sep 09, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [6ec67cd2f1](https://linux-hardware.org/?probe=6ec67cd2f1) | Sep 08, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [55b8608662](https://linux-hardware.org/?probe=55b8608662) | Sep 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [4e54155977](https://linux-hardware.org/?probe=4e54155977) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51202f2fd7](https://linux-hardware.org/?probe=51202f2fd7) | Sep 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [7d13cd846d](https://linux-hardware.org/?probe=7d13cd846d) | Sep 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [858212c01d](https://linux-hardware.org/?probe=858212c01d) | Sep 03, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [1901f4aad9](https://linux-hardware.org/?probe=1901f4aad9) | Sep 02, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [0e82099e8f](https://linux-hardware.org/?probe=0e82099e8f) | Sep 01, 2023 |
| MSI           | Z97-G43                     | Desktop     | [74492b4424](https://linux-hardware.org/?probe=74492b4424) | Aug 30, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6f5a767b7e](https://linux-hardware.org/?probe=6f5a767b7e) | Aug 29, 2023 |
| Bluechip C... | TRAVELline TL14W4           | Notebook    | [7959987246](https://linux-hardware.org/?probe=7959987246) | Aug 28, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [1562efcaf2](https://linux-hardware.org/?probe=1562efcaf2) | Aug 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6736188e61](https://linux-hardware.org/?probe=6736188e61) | Aug 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [36e12540f3](https://linux-hardware.org/?probe=36e12540f3) | Aug 23, 2023 |
| Dell          | OptiPlex 5050               | Desktop     | [045411a33d](https://linux-hardware.org/?probe=045411a33d) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdbe8c2f04](https://linux-hardware.org/?probe=cdbe8c2f04) | Aug 21, 2023 |
| Dell          | OptiPlex 5050               | Desktop     | [e2c9cecddd](https://linux-hardware.org/?probe=e2c9cecddd) | Aug 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu MATE 20.04 | 679       | 33.06%  |
| Ubuntu MATE 22.04 | 471       | 22.93%  |
| Ubuntu MATE 18.04 | 282       | 13.73%  |
| Ubuntu MATE 24.04 | 215       | 10.47%  |
| Ubuntu MATE 20.10 | 54        | 2.63%   |
| Ubuntu MATE 19.10 | 48        | 2.34%   |
| Ubuntu MATE 21.10 | 45        | 2.19%   |
| Ubuntu MATE 21.04 | 42        | 2.04%   |
| Ubuntu MATE 23.10 | 41        | 2%      |
| Ubuntu MATE 22.10 | 39        | 1.9%    |
| Ubuntu MATE 23.04 | 33        | 1.61%   |
| Ubuntu MATE 25.04 | 28        | 1.36%   |
| Ubuntu MATE 24.10 | 26        | 1.27%   |
| Ubuntu MATE 16.04 | 25        | 1.22%   |
| Ubuntu MATE 25.10 | 13        | 0.63%   |
| Ubuntu MATE       | 4         | 0.19%   |
| Ubuntu MATE 19.04 | 2         | 0.1%    |
| Ubuntu MATE 18.10 | 2         | 0.1%    |
| Ubuntu MATE 17.04 | 2         | 0.1%    |
| Ubuntu MATE 26.04 | 1         | 0.05%   |
| Ubuntu MATE 16.10 | 1         | 0.05%   |
| Ubuntu MATE 15.04 | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Ubuntu MATE | 1935      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 57        | 2.4%    |
| 5.4.0-48-generic   | 44        | 1.85%   |
| 5.4.0-52-generic   | 35        | 1.47%   |
| 5.4.0-47-generic   | 31        | 1.31%   |
| 5.15.0-56-generic  | 31        | 1.31%   |
| 5.4.0-65-generic   | 23        | 0.97%   |
| 6.8.0-51-generic   | 22        | 0.93%   |
| 5.4.0-58-generic   | 19        | 0.8%    |
| 6.2.0-26-generic   | 18        | 0.76%   |
| 5.4.0-40-generic   | 18        | 0.76%   |
| 5.15.0-47-generic  | 18        | 0.76%   |
| 4.15.0-163-generic | 17        | 0.72%   |
| 5.8.0-48-generic   | 16        | 0.67%   |
| 5.4.0-45-generic   | 16        | 0.67%   |
| 5.3.0-46-generic   | 16        | 0.67%   |
| 5.3.0-40-generic   | 16        | 0.67%   |
| 6.8.0-45-generic   | 15        | 0.63%   |
| 5.15.0-48-generic  | 15        | 0.63%   |
| 5.15.0-46-generic  | 15        | 0.63%   |
| 6.8.0-52-generic   | 14        | 0.59%   |
| 6.8.0-40-generic   | 14        | 0.59%   |
| 6.5.0-35-generic   | 13        | 0.55%   |
| 5.4.0-94-generic   | 13        | 0.55%   |
| 5.3.0-42-generic   | 13        | 0.55%   |
| 5.15.0-60-generic  | 13        | 0.55%   |
| 5.15.0-58-generic  | 13        | 0.55%   |
| 5.15.0-52-generic  | 13        | 0.55%   |
| 5.11.0-40-generic  | 13        | 0.55%   |
| 6.2.0-32-generic   | 12        | 0.51%   |
| 5.8.0-50-generic   | 12        | 0.51%   |
| 5.4.0-81-generic   | 12        | 0.51%   |
| 5.4.0-56-generic   | 12        | 0.51%   |
| 5.15.0-67-generic  | 12        | 0.51%   |
| 5.15.0-43-generic  | 12        | 0.51%   |
| 6.5.0-14-generic   | 11        | 0.46%   |
| 6.2.0-36-generic   | 11        | 0.46%   |
| 6.14.0-33-generic  | 11        | 0.46%   |
| 5.4.0-26-generic   | 11        | 0.46%   |
| 5.15.0-40-generic  | 11        | 0.46%   |
| 5.15.0-25-generic  | 11        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 540       | 25.21%  |
| 5.15.0  | 326       | 15.22%  |
| 6.8.0   | 176       | 8.22%   |
| 5.3.0   | 118       | 5.51%   |
| 5.8.0   | 107       | 5%      |
| 4.15.0  | 107       | 5%      |
| 5.11.0  | 97        | 4.53%   |
| 6.5.0   | 94        | 4.39%   |
| 5.13.0  | 89        | 4.15%   |
| 6.2.0   | 86        | 4.01%   |
| 5.19.0  | 77        | 3.59%   |
| 6.14.0  | 65        | 3.03%   |
| 6.11.0  | 50        | 2.33%   |
| 5.0.0   | 15        | 0.7%    |
| 6.17.0  | 12        | 0.56%   |
| 4.4.0   | 11        | 0.51%   |
| 5.14.0  | 8         | 0.37%   |
| 6.12.3  | 5         | 0.23%   |
| 6.4.0   | 4         | 0.19%   |
| 5.17.0  | 4         | 0.19%   |
| 5.10.27 | 4         | 0.19%   |
| 4.9.277 | 4         | 0.19%   |
| 4.18.0  | 4         | 0.19%   |
| 6.5.7   | 3         | 0.14%   |
| 6.4.3   | 3         | 0.14%   |
| 6.3.0   | 3         | 0.14%   |
| 6.10.2  | 3         | 0.14%   |
| 5.18.0  | 3         | 0.14%   |
| 4.9.337 | 3         | 0.14%   |
| 4.10.0  | 3         | 0.14%   |
| 6.8.7   | 2         | 0.09%   |
| 6.7.3   | 2         | 0.09%   |
| 6.6.1   | 2         | 0.09%   |
| 6.3.7   | 2         | 0.09%   |
| 6.3.4   | 2         | 0.09%   |
| 6.3.1   | 2         | 0.09%   |
| 6.2.11  | 2         | 0.09%   |
| 6.15.6  | 2         | 0.09%   |
| 6.15.0  | 2         | 0.09%   |
| 6.13.2  | 2         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 545       | 25.71%  |
| 5.15    | 331       | 15.61%  |
| 6.8     | 180       | 8.49%   |
| 5.3     | 118       | 5.57%   |
| 5.8     | 109       | 5.14%   |
| 4.15    | 107       | 5.05%   |
| 6.5     | 97        | 4.58%   |
| 5.11    | 97        | 4.58%   |
| 6.2     | 89        | 4.2%    |
| 5.13    | 89        | 4.2%    |
| 5.19    | 77        | 3.63%   |
| 6.14    | 67        | 3.16%   |
| 6.11    | 51        | 2.41%   |
| 5.0     | 15        | 0.71%   |
| 4.4     | 14        | 0.66%   |
| 6.17    | 12        | 0.57%   |
| 6.4     | 8         | 0.38%   |
| 5.14    | 8         | 0.38%   |
| 5.10    | 8         | 0.38%   |
| 4.9     | 8         | 0.38%   |
| 6.10    | 7         | 0.33%   |
| 6.1     | 7         | 0.33%   |
| 6.7     | 6         | 0.28%   |
| 6.6     | 6         | 0.28%   |
| 6.3     | 6         | 0.28%   |
| 6.12    | 6         | 0.28%   |
| 6.15    | 5         | 0.24%   |
| 5.17    | 5         | 0.24%   |
| 4.18    | 4         | 0.19%   |
| 4.14    | 4         | 0.19%   |
| 6.13    | 3         | 0.14%   |
| 6.0     | 3         | 0.14%   |
| 5.9     | 3         | 0.14%   |
| 5.18    | 3         | 0.14%   |
| 4.10    | 3         | 0.14%   |
| 6.9     | 2         | 0.09%   |
| 6.16    | 2         | 0.09%   |
| 5.7     | 2         | 0.09%   |
| 5.6     | 2         | 0.09%   |
| 5.5     | 2         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1782      | 92.09%  |
| i686    | 86        | 4.44%   |
| aarch64 | 52        | 2.69%   |
| armv7l  | 13        | 0.67%   |
| ppc     | 2         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 1890      | 97.62%  |
| X-Cinnamon | 12        | 0.62%   |
| GNOME      | 11        | 0.57%   |
| Cinnamon   | 8         | 0.41%   |
| KDE5       | 7         | 0.36%   |
| XFCE       | 2         | 0.1%    |
| Trinity    | 2         | 0.1%    |
| Budgie     | 2         | 0.1%    |
| KDE6       | 1         | 0.05%   |
| i3         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1868      | 96.39%  |
| Tty     | 46        | 2.37%   |
| Wayland | 24        | 1.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 1039      | 51.92%  |
| Unknown | 508       | 25.39%  |
| TDM     | 309       | 15.44%  |
| GDM3    | 84        | 4.2%    |
| GDM     | 40        | 2%      |
| SDDM    | 11        | 0.55%   |
| LXDM    | 6         | 0.3%    |
| SLiM    | 4         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 683       | 35.03%  |
| fr_FR   | 195       | 10%     |
| de_DE   | 195       | 10%     |
| pt_BR   | 129       | 6.62%   |
| it_IT   | 89        | 4.56%   |
| en_GB   | 84        | 4.31%   |
| ru_RU   | 64        | 3.28%   |
| es_ES   | 61        | 3.13%   |
| C       | 47        | 2.41%   |
| Unknown | 38        | 1.95%   |
| en_CA   | 37        | 1.9%    |
| el_GR   | 36        | 1.85%   |
| en_AU   | 29        | 1.49%   |
| pl_PL   | 21        | 1.08%   |
| es_AR   | 17        | 0.87%   |
| hu_HU   | 16        | 0.82%   |
| sv_SE   | 13        | 0.67%   |
| fi_FI   | 13        | 0.67%   |
| en_IN   | 13        | 0.67%   |
| nl_NL   | 11        | 0.56%   |
| es_MX   | 10        | 0.51%   |
| de_CH   | 10        | 0.51%   |
| cs_CZ   | 10        | 0.51%   |
| es_PE   | 8         | 0.41%   |
| zh_TW   | 6         | 0.31%   |
| tr_TR   | 6         | 0.31%   |
| ru_UA   | 6         | 0.31%   |
| ja_JP   | 6         | 0.31%   |
| es_VE   | 6         | 0.31%   |
| es_CL   | 6         | 0.31%   |
| en_PH   | 5         | 0.26%   |
| en_IL   | 5         | 0.26%   |
| de_AT   | 5         | 0.26%   |
| pt_PT   | 4         | 0.21%   |
| nl_BE   | 4         | 0.21%   |
| fr_CA   | 4         | 0.21%   |
| da_DK   | 4         | 0.21%   |
| zh_CN   | 3         | 0.15%   |
| hr_HR   | 3         | 0.15%   |
| fr_BE   | 3         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1079      | 54.74%  |
| EFI  | 892       | 45.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1610      | 81.56%  |
| Tmpfs   | 214       | 10.84%  |
| Overlay | 66        | 3.34%   |
| Btrfs   | 32        | 1.62%   |
| Zfs     | 20        | 1.01%   |
| Xfs     | 10        | 0.51%   |
| Unknown | 9         | 0.46%   |
| Ext3    | 5         | 0.25%   |
| Aufs    | 3         | 0.15%   |
| Jfs     | 2         | 0.1%    |
| Ext2    | 2         | 0.1%    |
| ExX4    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1006      | 50.65%  |
| Unknown | 622       | 31.32%  |
| MBR     | 358       | 18.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1669      | 84.76%  |
| Yes       | 300       | 15.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1298      | 66.02%  |
| Yes       | 668       | 33.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 320       | 16.54%  |
| ASUSTek Computer        | 277       | 14.32%  |
| Dell                    | 263       | 13.59%  |
| Lenovo                  | 244       | 12.61%  |
| MSI                     | 107       | 5.53%   |
| Gigabyte Technology     | 99        | 5.12%   |
| Acer                    | 90        | 4.65%   |
| ASRock                  | 57        | 2.95%   |
| Intel                   | 47        | 2.43%   |
| Raspberry Pi Foundation | 43        | 2.22%   |
| Unknown                 | 37        | 1.91%   |
| Toshiba                 | 34        | 1.76%   |
| Apple                   | 33        | 1.71%   |
| Sony                    | 18        | 0.93%   |
| Fujitsu                 | 17        | 0.88%   |
| Samsung Electronics     | 16        | 0.83%   |
| Hardkernel              | 15        | 0.78%   |
| Medion                  | 12        | 0.62%   |
| AZW                     | 9         | 0.47%   |
| Notebook                | 8         | 0.41%   |
| Supermicro              | 7         | 0.36%   |
| Biostar                 | 7         | 0.36%   |
| Positivo                | 6         | 0.31%   |
| Packard Bell            | 6         | 0.31%   |
| Fujitsu Siemens         | 6         | 0.31%   |
| AMI                     | 6         | 0.31%   |
| System76                | 5         | 0.26%   |
| Pegatron                | 5         | 0.26%   |
| HUAWEI                  | 5         | 0.26%   |
| Google                  | 5         | 0.26%   |
| ECS                     | 5         | 0.26%   |
| Clevo                   | 5         | 0.26%   |
| TUXEDO                  | 4         | 0.21%   |
| Foxconn                 | 4         | 0.21%   |
| TrekStor                | 3         | 0.16%   |
| Semp Toshiba            | 3         | 0.16%   |
| Quanta                  | 3         | 0.16%   |
| Microsoft               | 3         | 0.16%   |
| LG Electronics          | 3         | 0.16%   |
| GPD                     | 3         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 52        | 2.69%   |
| ASUS All Series                      | 18        | 0.93%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 13        | 0.67%   |
| HP Compaq Elite 8300 SFF             | 10        | 0.52%   |
| RPi Raspberry Pi                     | 9         | 0.47%   |
| RPi Raspberry Pi 4 Model B Rev 1.2   | 8         | 0.41%   |
| HP ProDesk 600 G1 SFF                | 8         | 0.41%   |
| HP Pavilion g6                       | 8         | 0.41%   |
| HP Compaq 6005 Pro SFF PC            | 8         | 0.41%   |
| RPi Raspberry Pi 4 Model B Rev 1.1   | 7         | 0.36%   |
| Hardkernel ODROID-N2Plus             | 7         | 0.36%   |
| Dell Latitude E6410                  | 7         | 0.36%   |
| MSI MS-7817                          | 6         | 0.31%   |
| HP Notebook                          | 6         | 0.31%   |
| Dell Precision M4800                 | 6         | 0.31%   |
| HP Pavilion dv7                      | 5         | 0.26%   |
| Dell OptiPlex 755                    | 5         | 0.26%   |
| Dell OptiPlex 390                    | 5         | 0.26%   |
| Dell OptiPlex 3010                   | 5         | 0.26%   |
| Dell Latitude E6420                  | 5         | 0.26%   |
| ASUS M5A97 R2.0                      | 5         | 0.26%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 4         | 0.21%   |
| HP Compaq 8000 Elite SFF PC          | 4         | 0.21%   |
| HP Compaq 6200 Pro SFF PC            | 4         | 0.21%   |
| Hardkernel Odroid XU4                | 4         | 0.21%   |
| Dell Precision 7920 Rack             | 4         | 0.21%   |
| Dell OptiPlex GX520                  | 4         | 0.21%   |
| Dell OptiPlex 360                    | 4         | 0.21%   |
| Dell Latitude E5540                  | 4         | 0.21%   |
| ASUS PRIME B450M-A II                | 4         | 0.21%   |
| ASUS H110M-K                         | 4         | 0.21%   |
| ASRock B450M Pro4                    | 4         | 0.21%   |
| TrekStor Surfbook A13B               | 3         | 0.16%   |
| RPi Raspberry Pi 3 Model B Rev 1.2   | 3         | 0.16%   |
| MSI MS-7C94                          | 3         | 0.16%   |
| MSI MS-7C56                          | 3         | 0.16%   |
| MSI MS-7C51                          | 3         | 0.16%   |
| MSI MS-7C02                          | 3         | 0.16%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 3         | 0.16%   |
| Lenovo G500 20236                    | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 111       | 5.74%   |
| Dell Latitude            | 72        | 3.72%   |
| Acer Aspire              | 64        | 3.31%   |
| Dell OptiPlex            | 62        | 3.2%    |
| HP Pavilion              | 56        | 2.89%   |
| Unknown                  | 52        | 2.69%   |
| HP Compaq                | 51        | 2.64%   |
| Lenovo IdeaPad           | 46        | 2.38%   |
| RPi Raspberry            | 43        | 2.22%   |
| Dell Precision           | 42        | 2.17%   |
| Dell Inspiron            | 39        | 2.02%   |
| HP EliteBook             | 38        | 1.96%   |
| ASUS PRIME               | 36        | 1.86%   |
| Toshiba Satellite        | 30        | 1.55%   |
| HP ProBook               | 26        | 1.34%   |
| ASUS ROG                 | 22        | 1.14%   |
| Lenovo ThinkCentre       | 20        | 1.03%   |
| ASUS All                 | 18        | 0.93%   |
| Dell XPS                 | 15        | 0.78%   |
| Dell Vostro              | 15        | 0.78%   |
| HP Laptop                | 14        | 0.72%   |
| ASUS VivoBook            | 14        | 0.72%   |
| HP ProDesk               | 12        | 0.62%   |
| Fujitsu LIFEBOOK         | 12        | 0.62%   |
| HP EliteDesk             | 11        | 0.57%   |
| ASUS TUF                 | 11        | 0.57%   |
| HP ENVY                  | 10        | 0.52%   |
| Lenovo ThinkBook         | 9         | 0.47%   |
| HP 250                   | 8         | 0.41%   |
| HP ZBook                 | 7         | 0.36%   |
| HP ProLiant              | 7         | 0.36%   |
| Hardkernel ODROID-N2Plus | 7         | 0.36%   |
| ASUS M5A97               | 7         | 0.36%   |
| ASUS M5A78L-M            | 7         | 0.36%   |
| MSI MS-7817              | 6         | 0.31%   |
| Lenovo Legion            | 6         | 0.31%   |
| Lenovo IdeaPadFlex       | 6         | 0.31%   |
| HP Notebook              | 6         | 0.31%   |
| Acer TravelMate          | 6         | 0.31%   |
| Packard Bell EasyNote    | 5         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 164       | 8.48%   |
| 2011    | 162       | 8.37%   |
| 2012    | 161       | 8.32%   |
| 2013    | 145       | 7.49%   |
| 2018    | 134       | 6.93%   |
| 2019    | 129       | 6.67%   |
| 2021    | 119       | 6.15%   |
| 2010    | 105       | 5.43%   |
| 2014    | 100       | 5.17%   |
| 2017    | 97        | 5.01%   |
| 2009    | 95        | 4.91%   |
| 2015    | 92        | 4.75%   |
| 2008    | 88        | 4.55%   |
| 2016    | 84        | 4.34%   |
| 2022    | 60        | 3.1%    |
| 2007    | 49        | 2.53%   |
| Unknown | 44        | 2.27%   |
| 2023    | 37        | 1.91%   |
| 2006    | 29        | 1.5%    |
| 2024    | 22        | 1.14%   |
| 2005    | 14        | 0.72%   |
| 2025    | 2         | 0.1%    |
| 2004    | 1         | 0.05%   |
| 2003    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 980       | 50.65%  |
| Desktop        | 751       | 38.81%  |
| System on chip | 63        | 3.26%   |
| Mini pc        | 45        | 2.33%   |
| Convertible    | 29        | 1.5%    |
| All in one     | 27        | 1.4%    |
| Server         | 23        | 1.19%   |
| Tablet         | 16        | 0.83%   |
| Other          | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1815      | 93.32%  |
| Enabled  | 130       | 6.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1928      | 99.64%  |
| Yes  | 7         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 436       | 22.18%  |
| 3.01-4.0        | 435       | 22.13%  |
| 16.01-24.0      | 323       | 16.43%  |
| 8.01-16.0       | 299       | 15.21%  |
| 32.01-64.0      | 176       | 8.95%   |
| 1.01-2.0        | 94        | 4.78%   |
| 64.01-256.0     | 88        | 4.48%   |
| 24.01-32.0      | 43        | 2.19%   |
| 2.01-3.0        | 41        | 2.09%   |
| 0.51-1.0        | 25        | 1.27%   |
| More than 256.0 | 5         | 0.25%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 718       | 34.11%  |
| 2.01-3.0        | 497       | 23.61%  |
| 4.01-8.0        | 282       | 13.4%   |
| 3.01-4.0        | 249       | 11.83%  |
| 0.51-1.0        | 222       | 10.55%  |
| 8.01-16.0       | 81        | 3.85%   |
| 0.01-0.5        | 23        | 1.09%   |
| 24.01-32.0      | 12        | 0.57%   |
| 16.01-24.0      | 10        | 0.48%   |
| 32.01-64.0      | 7         | 0.33%   |
| 64.01-256.0     | 3         | 0.14%   |
| More than 256.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1185      | 59.43%  |
| 2      | 499       | 25.03%  |
| 3      | 152       | 7.62%   |
| 4      | 76        | 3.81%   |
| 5      | 26        | 1.3%    |
| 6      | 16        | 0.8%    |
| 0      | 13        | 0.65%   |
| 7      | 8         | 0.4%    |
| 8      | 5         | 0.25%   |
| 10     | 3         | 0.15%   |
| 9      | 3         | 0.15%   |
| 33     | 2         | 0.1%    |
| 16     | 2         | 0.1%    |
| 11     | 2         | 0.1%    |
| 20     | 1         | 0.05%   |
| 12     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1099      | 56.33%  |
| Yes       | 852       | 43.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1685      | 86.9%   |
| No        | 254       | 13.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1368      | 70.01%  |
| No        | 586       | 29.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1047      | 53.5%   |
| No        | 910       | 46.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 289       | 14.83%  |
| Germany     | 235       | 12.06%  |
| France      | 202       | 10.36%  |
| Brazil      | 159       | 8.16%   |
| Italy       | 106       | 5.44%   |
| Russia      | 90        | 4.62%   |
| UK          | 81        | 4.16%   |
| Spain       | 81        | 4.16%   |
| Canada      | 46        | 2.36%   |
| Greece      | 45        | 2.31%   |
| Poland      | 33        | 1.69%   |
| Australia   | 32        | 1.64%   |
| Argentina   | 27        | 1.39%   |
| Switzerland | 25        | 1.28%   |
| Netherlands | 25        | 1.28%   |
| Hungary     | 25        | 1.28%   |
| Finland     | 22        | 1.13%   |
| Belgium     | 22        | 1.13%   |
| Austria     | 22        | 1.13%   |
| India       | 21        | 1.08%   |
| Turkey      | 20        | 1.03%   |
| Mexico      | 20        | 1.03%   |
| Sweden      | 18        | 0.92%   |
| Ukraine     | 16        | 0.82%   |
| Indonesia   | 16        | 0.82%   |
| Czechia     | 15        | 0.77%   |
| Norway      | 13        | 0.67%   |
| Portugal    | 12        | 0.62%   |
| Estonia     | 12        | 0.62%   |
| Romania     | 11        | 0.56%   |
| Denmark     | 11        | 0.56%   |
| Taiwan      | 10        | 0.51%   |
| Peru        | 10        | 0.51%   |
| Chile       | 10        | 0.51%   |
| Japan       | 9         | 0.46%   |
| Thailand    | 8         | 0.41%   |
| Venezuela   | 7         | 0.36%   |
| Israel      | 7         | 0.36%   |
| Croatia     | 7         | 0.36%   |
| Bulgaria    | 7         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 81        | 3.91%   |
| Paris             | 36        | 1.74%   |
| Moscow            | 33        | 1.59%   |
| Berlin            | 25        | 1.21%   |
| Thessaloniki      | 19        | 0.92%   |
| Rome              | 17        | 0.82%   |
| Athens            | 17        | 0.82%   |
| Vienna            | 12        | 0.58%   |
| St Petersburg     | 11        | 0.53%   |
| Madrid            | 11        | 0.53%   |
| Hamburg           | 11        | 0.53%   |
| Warsaw            | 10        | 0.48%   |
| Los Angeles       | 10        | 0.48%   |
| Helsinki          | 10        | 0.48%   |
| Budapest          | 9         | 0.43%   |
| Melbourne         | 8         | 0.39%   |
| Manchester        | 8         | 0.39%   |
| Frankfurt am Main | 8         | 0.39%   |
| Zurich            | 7         | 0.34%   |
| Rio de Janeiro    | 7         | 0.34%   |
| Munich            | 7         | 0.34%   |
| Mannheim          | 7         | 0.34%   |
| Karlsruhe         | 7         | 0.34%   |
| Brisbane          | 7         | 0.34%   |
| Barcelona         | 7         | 0.34%   |
| Tallinn           | 6         | 0.29%   |
| Sundbyberg        | 6         | 0.29%   |
| Rochester         | 6         | 0.29%   |
| New York          | 6         | 0.29%   |
| Lisbon            | 6         | 0.29%   |
| Kyiv              | 6         | 0.29%   |
| Bengaluru         | 6         | 0.29%   |
| Amsterdam         | 6         | 0.29%   |
| Wittingen         | 5         | 0.24%   |
| Toulouse          | 5         | 0.24%   |
| Sydney            | 5         | 0.24%   |
| Stuttgart         | 5         | 0.24%   |
| Perth             | 5         | 0.24%   |
| Montpellier       | 5         | 0.24%   |
| Milan             | 5         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 435       | 710    | 15.33%  |
| WDC                         | 422       | 662    | 14.87%  |
| Samsung Electronics         | 415       | 728    | 14.62%  |
| Toshiba                     | 168       | 260    | 5.92%   |
| Unknown                     | 164       | 223    | 5.78%   |
| Kingston                    | 154       | 205    | 5.43%   |
| SanDisk                     | 132       | 168    | 4.65%   |
| Crucial                     | 119       | 159    | 4.19%   |
| Hitachi                     | 94        | 114    | 3.31%   |
| SK hynix                    | 67        | 86     | 2.36%   |
| Intel                       | 53        | 70     | 1.87%   |
| A-DATA Technology           | 43        | 50     | 1.52%   |
| China                       | 35        | 42     | 1.23%   |
| HGST                        | 34        | 112    | 1.2%    |
| Micron Technology           | 27        | 30     | 0.95%   |
| PNY                         | 22        | 23     | 0.78%   |
| KIOXIA                      | 21        | 22     | 0.74%   |
| Phison                      | 18        | 21     | 0.63%   |
| SPCC                        | 17        | 26     | 0.6%    |
| Fujitsu                     | 16        | 20     | 0.56%   |
| Intenso                     | 15        | 21     | 0.53%   |
| Silicon Motion              | 13        | 14     | 0.46%   |
| Unknown                     | 13        | 13     | 0.46%   |
| Transcend                   | 12        | 22     | 0.42%   |
| Patriot                     | 12        | 14     | 0.42%   |
| JMicron Technology          | 11        | 14     | 0.39%   |
| Hewlett-Packard             | 11        | 16     | 0.39%   |
| Netac                       | 10        | 10     | 0.35%   |
| Kingston Technology Company | 10        | 14     | 0.35%   |
| Corsair                     | 10        | 12     | 0.35%   |
| Apple                       | 10        | 11     | 0.35%   |
| Phison Electronics          | 9         | 9      | 0.32%   |
| Micron/Crucial Technology   | 9         | 15     | 0.32%   |
| LITEON                      | 9         | 10     | 0.32%   |
| Verbatim                    | 8         | 38     | 0.28%   |
| OCZ                         | 8         | 8      | 0.28%   |
| Maxtor                      | 8         | 14     | 0.28%   |
| LITEONIT                    | 8         | 9      | 0.28%   |
| Team                        | 7         | 8      | 0.25%   |
| MAXIO Technology (Hangzhou) | 7         | 9      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                             | 34        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB                    | 33        | 1.05%   |
| Unknown MMC Card  64GB                             | 28        | 0.89%   |
| Kingston SA400S37240G 240GB SSD                    | 26        | 0.82%   |
| Kingston SA400S37120G 120GB SSD                    | 24        | 0.76%   |
| Samsung SSD 860 EVO 500GB                          | 22        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 20        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                     | 18        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                     | 17        | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                     | 16        | 0.51%   |
| Kingston SA400S37480G 480GB SSD                    | 16        | 0.51%   |
| Crucial CT500MX500SSD1 500GB                       | 16        | 0.51%   |
| Toshiba MQ01ABF050 500GB                           | 15        | 0.48%   |
| Toshiba MQ01ABD100 1TB                             | 14        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                    | 14        | 0.44%   |
| Samsung SSD 850 EVO 500GB                          | 14        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                   | 14        | 0.44%   |
| Toshiba DT01ACA100 1TB                             | 13        | 0.41%   |
| Seagate ST3500418AS 500GB                          | 13        | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB                     | 13        | 0.41%   |
| Unknown                                            | 13        | 0.41%   |
| Unknown SD/MMC/MS PRO 2GB                          | 12        | 0.38%   |
| Unknown MMC Card  128GB                            | 12        | 0.38%   |
| Toshiba DT01ACA050 500GB                           | 12        | 0.38%   |
| Samsung SSD 850 EVO 250GB                          | 12        | 0.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 12        | 0.38%   |
| Crucial CT1000BX500SSD1 1TB                        | 12        | 0.38%   |
| Unknown MMC Card  16GB                             | 11        | 0.35%   |
| Seagate ST1000DM010-2EP102 1TB                     | 11        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                     | 11        | 0.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 10        | 0.32%   |
| Seagate ST9500325AS 500GB                          | 10        | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 10        | 0.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 10        | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB                     | 9         | 0.29%   |
| SanDisk NVMe SSD Drive 1TB                         | 9         | 0.29%   |
| Samsung SSD 980 PRO 1TB                            | 9         | 0.29%   |
| Samsung SSD 980 1TB                                | 9         | 0.29%   |
| Samsung HD322HJ 320GB                              | 9         | 0.29%   |
| Crucial CT1000MX500SSD1 1TB                        | 9         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 431       | 701    | 36.96%  |
| WDC                 | 353       | 557    | 30.27%  |
| Toshiba             | 132       | 202    | 11.32%  |
| Hitachi             | 94        | 114    | 8.06%   |
| Samsung Electronics | 51        | 74     | 4.37%   |
| HGST                | 34        | 112    | 2.92%   |
| Fujitsu             | 16        | 20     | 1.37%   |
| Unknown             | 14        | 17     | 1.2%    |
| Maxtor              | 7         | 11     | 0.6%    |
| Hewlett-Packard     | 6         | 10     | 0.51%   |
| JMicron Technology  | 4         | 5      | 0.34%   |
| ASMT                | 3         | 5      | 0.26%   |
| SAGE                | 2         | 3      | 0.17%   |
| IBM/Hitachi         | 2         | 2      | 0.17%   |
| ASMT109x            | 2         | 3      | 0.17%   |
| USB3.0              | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| SSK                 | 1         | 1      | 0.09%   |
| MaxDigital          | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| KESU                | 1         | 4      | 0.09%   |
| Intenso             | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| HGST HUH            | 1         | 2      | 0.09%   |
| DAS                 | 1         | 6      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |
| Apricorn            | 1         | 1      | 0.09%   |
| Apple               | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 214       | 364    | 22.79%  |
| Kingston            | 129       | 170    | 13.74%  |
| Crucial             | 102       | 141    | 10.86%  |
| SanDisk             | 92        | 118    | 9.8%    |
| WDC                 | 49        | 69     | 5.22%   |
| China               | 34        | 41     | 3.62%   |
| A-DATA Technology   | 32        | 36     | 3.41%   |
| Intel               | 28        | 38     | 2.98%   |
| PNY                 | 21        | 22     | 2.24%   |
| Toshiba             | 14        | 18     | 1.49%   |
| SPCC                | 14        | 22     | 1.49%   |
| Transcend           | 12        | 22     | 1.28%   |
| Intenso             | 12        | 17     | 1.28%   |
| SK hynix            | 10        | 15     | 1.06%   |
| Micron Technology   | 10        | 12     | 1.06%   |
| Patriot             | 9         | 11     | 0.96%   |
| Verbatim            | 8         | 38     | 0.85%   |
| OCZ                 | 8         | 8      | 0.85%   |
| Netac               | 8         | 8      | 0.85%   |
| LITEONIT            | 8         | 9      | 0.85%   |
| LITEON              | 7         | 8      | 0.75%   |
| KingSpec            | 7         | 10     | 0.75%   |
| Apacer              | 7         | 8      | 0.75%   |
| Team                | 5         | 5      | 0.53%   |
| SABRENT             | 5         | 5      | 0.53%   |
| Apple               | 5         | 5      | 0.53%   |
| FORESEE             | 4         | 4      | 0.43%   |
| Plextor             | 3         | 3      | 0.32%   |
| LDLC                | 3         | 3      | 0.32%   |
| KingFast            | 3         | 3      | 0.32%   |
| Corsair             | 3         | 3      | 0.32%   |
| ASMT                | 3         | 3      | 0.32%   |
| Argon               | 3         | 5      | 0.32%   |
| AGI                 | 3         | 4      | 0.32%   |
| Vaseky              | 2         | 2      | 0.21%   |
| T-FORCE             | 2         | 2      | 0.21%   |
| Smartbuy            | 2         | 2      | 0.21%   |
| Seagate             | 2         | 2      | 0.21%   |
| NGFF                | 2         | 2      | 0.21%   |
| Lexar               | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 981       | 1860   | 38.85%  |
| SSD     | 819       | 1318   | 32.44%  |
| NVMe    | 525       | 788    | 20.79%  |
| MMC     | 144       | 192    | 5.7%    |
| Unknown | 56        | 74     | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1478      | 3051   | 64.63%  |
| NVMe | 524       | 779    | 22.91%  |
| MMC  | 144       | 192    | 6.3%    |
| SAS  | 141       | 210    | 6.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1106      | 1766   | 57.51%  |
| 0.51-1.0   | 501       | 746    | 26.05%  |
| 1.01-2.0   | 178       | 306    | 9.26%   |
| 3.01-4.0   | 68        | 96     | 3.54%   |
| 4.01-10.0  | 40        | 207    | 2.08%   |
| 2.01-3.0   | 25        | 43     | 1.3%    |
| 10.01-20.0 | 4         | 13     | 0.21%   |
| 20.01-50.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 507       | 24.96%  |
| 251-500        | 484       | 23.83%  |
| 501-1000       | 323       | 15.9%   |
| 1001-2000      | 168       | 8.27%   |
| 51-100         | 142       | 6.99%   |
| More than 3000 | 140       | 6.89%   |
| 1-20           | 81        | 3.99%   |
| 21-50          | 79        | 3.89%   |
| 2001-3000      | 73        | 3.59%   |
| Unknown        | 34        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 624       | 29.91%  |
| 21-50          | 345       | 16.54%  |
| 101-250        | 303       | 14.53%  |
| 51-100         | 262       | 12.56%  |
| 251-500        | 186       | 8.92%   |
| 501-1000       | 137       | 6.57%   |
| 1001-2000      | 88        | 4.22%   |
| More than 3000 | 67        | 3.21%   |
| 2001-3000      | 40        | 1.92%   |
| Unknown        | 34        | 1.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 11        | 11     | 4.64%   |
| Seagate ST3500418AS 500GB             | 5         | 6      | 2.11%   |
| Seagate ST320LT007-9ZV142 320GB       | 5         | 5      | 2.11%   |
| WDC WD5000AAKX-083CA1 500GB           | 4         | 4      | 1.69%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 1.69%   |
| Seagate ST9500325AS 500GB             | 3         | 3      | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.84%   |
| WDC WD5000AAKX-003CA0 500GB           | 2         | 2      | 0.84%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 2         | 2      | 0.84%   |
| WDC WD2500BEKT-60A25T1 250GB          | 2         | 2      | 0.84%   |
| WDC WD2500AAKX-753CA1 250GB           | 2         | 2      | 0.84%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2         | 2      | 0.84%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 4      | 0.84%   |
| Unknown MM0500EANCR 500GB             | 2         | 5      | 0.84%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 0.84%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.84%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.84%   |
| Seagate ST9160821AS 160GB             | 2         | 2      | 0.84%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.84%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 3      | 0.84%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 0.84%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.84%   |
| Samsung Electronics SSD 870 EVO 1TB   | 2         | 2      | 0.84%   |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 0.84%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2      | 0.84%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.84%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 0.84%   |
| Hitachi HTS542516K9SA00 160GB         | 2         | 2      | 0.84%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.84%   |
| WDC WD7500BPVX-60JC3T0 752GB          | 1         | 2      | 0.42%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 1      | 0.42%   |
| WDC WD7500BPVT-75HXZT1 752GB          | 1         | 1      | 0.42%   |
| WDC WD7500BPVT-22A1YT0 752GB          | 1         | 1      | 0.42%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.42%   |
| WDC WD5003AZEX-00K3CA0 500GB          | 1         | 1      | 0.42%   |
| WDC WD5000LUCT-63RC2Y0 500GB          | 1         | 1      | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.42%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 2      | 0.42%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 73     | 28.88%  |
| WDC                 | 58        | 73     | 25%     |
| Samsung Electronics | 20        | 24     | 8.62%   |
| Toshiba             | 16        | 16     | 6.9%    |
| Hitachi             | 16        | 16     | 6.9%    |
| Kingston            | 8         | 9      | 3.45%   |
| Intel               | 7         | 8      | 3.02%   |
| OCZ                 | 4         | 4      | 1.72%   |
| Crucial             | 4         | 4      | 1.72%   |
| SanDisk             | 3         | 3      | 1.29%   |
| HGST                | 3         | 4      | 1.29%   |
| Unknown             | 2         | 5      | 0.86%   |
| SK hynix            | 2         | 5      | 0.86%   |
| Maxtor              | 2         | 2      | 0.86%   |
| Fujitsu             | 2         | 2      | 0.86%   |
| China               | 2         | 2      | 0.86%   |
| A-DATA Technology   | 2         | 4      | 0.86%   |
| Vaseky              | 1         | 1      | 0.43%   |
| Transcend           | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| SHAREVDI            | 1         | 1      | 0.43%   |
| NGFF                | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| LITEON              | 1         | 1      | 0.43%   |
| LDLC                | 1         | 1      | 0.43%   |
| Intenso             | 1         | 1      | 0.43%   |
| IBM/Hitachi         | 1         | 1      | 0.43%   |
| Eluktro             | 1         | 1      | 0.43%   |
| DAS                 | 1         | 3      | 0.43%   |
| ASMT                | 1         | 2      | 0.43%   |
| Apricorn            | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 73     | 38.29%  |
| WDC                 | 54        | 69     | 30.86%  |
| Toshiba             | 16        | 16     | 9.14%   |
| Hitachi             | 16        | 16     | 9.14%   |
| Samsung Electronics | 9         | 10     | 5.14%   |
| HGST                | 3         | 4      | 1.71%   |
| Unknown             | 2         | 5      | 1.14%   |
| Maxtor              | 2         | 2      | 1.14%   |
| Fujitsu             | 2         | 2      | 1.14%   |
| IBM/Hitachi         | 1         | 1      | 0.57%   |
| DAS                 | 1         | 3      | 0.57%   |
| ASMT                | 1         | 2      | 0.57%   |
| Apricorn            | 1         | 1      | 0.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 167       | 204    | 74.55%  |
| SSD  | 47        | 49     | 20.98%  |
| NVMe | 10        | 18     | 4.46%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MK6476GSXN 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 981       | 2143   | 45.61%  |
| Works    | 952       | 1817   | 44.26%  |
| Malfunc  | 217       | 271    | 10.09%  |
| Failed   | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1284      | 55.3%   |
| AMD                              | 343       | 14.77%  |
| Samsung Electronics              | 175       | 7.54%   |
| SanDisk                          | 68        | 2.93%   |
| SK hynix                         | 54        | 2.33%   |
| Phison Electronics               | 40        | 1.72%   |
| Nvidia                           | 37        | 1.59%   |
| ASMedia Technology               | 36        | 1.55%   |
| Kingston Technology Company      | 35        | 1.51%   |
| Toshiba America Info Systems     | 26        | 1.12%   |
| Silicon Motion                   | 23        | 0.99%   |
| Micron Technology                | 23        | 0.99%   |
| Marvell Technology Group         | 23        | 0.99%   |
| Micron/Crucial Technology        | 20        | 0.86%   |
| KIOXIA                           | 20        | 0.86%   |
| JMicron Technology               | 20        | 0.86%   |
| ADATA Technology                 | 15        | 0.65%   |
| LSI Logic / Symbios Logic        | 10        | 0.43%   |
| Silicon Integrated Systems [SiS] | 9         | 0.39%   |
| MAXIO Technology (Hangzhou)      | 9         | 0.39%   |
| VIA Technologies                 | 7         | 0.3%    |
| Realtek Semiconductor            | 6         | 0.26%   |
| Union Memory (Shenzhen)          | 5         | 0.22%   |
| Solidigm                         | 4         | 0.17%   |
| Shenzhen Longsys Electronics     | 4         | 0.17%   |
| Hewlett-Packard                  | 4         | 0.17%   |
| Solid State Storage Technology   | 3         | 0.13%   |
| Silicon Image                    | 2         | 0.09%   |
| Lite-On Technology               | 2         | 0.09%   |
| Broadcom / LSI                   | 2         | 0.09%   |
| Biwin Storage Technology         | 2         | 0.09%   |
| Adaptec                          | 2         | 0.09%   |
| TenaFe                           | 1         | 0.04%   |
| Seagate Technology               | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Integrated Technology Express    | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |
| Apacer Technology                | 1         | 0.04%   |
| 3ware                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 202       | 7.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 102       | 3.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 85        | 3.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 68        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 67        | 2.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 63        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 55        | 2.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54        | 1.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 54        | 1.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 50        | 1.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 46        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 46        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 44        | 1.62%   |
| AMD 400 Series Chipset SATA Controller                                                  | 38        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 36        | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 36        | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 36        | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 34        | 1.25%   |
| Intel SATA Controller [RAID mode]                                                       | 34        | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 33        | 1.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 32        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 31        | 1.14%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 31        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 31        | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 29        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 28        | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 28        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 27        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 26        | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 26        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 23        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 23        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 23        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 22        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 22        | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 21        | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 21        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 19        | 0.7%    |
| Nvidia MCP61 SATA Controller                                                            | 18        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1360      | 57.6%   |
| NVMe | 521       | 22.07%  |
| IDE  | 316       | 13.38%  |
| RAID | 150       | 6.35%   |
| SAS  | 11        | 0.47%   |
| SCSI | 3         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1443      | 74.57%  |
| AMD          | 424       | 21.91%  |
| ARM          | 65        | 3.36%   |
| PowerBook6,3 | 1         | 0.05%   |
| PowerBook5,6 | 1         | 0.05%   |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 52        | 2.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 15        | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 11        | 0.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.46%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 9         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 9         | 0.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.46%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 9         | 0.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9         | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.41%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 8         | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 0.41%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 8         | 0.41%   |
| AMD FX-6300 Six-Core Processor                | 8         | 0.41%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 7         | 0.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 7         | 0.36%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 7         | 0.36%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 7         | 0.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.36%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 7         | 0.36%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.36%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 7         | 0.36%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 0.36%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.36%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 7         | 0.36%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 7         | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 388       | 20.05%  |
| Intel Core i7           | 289       | 14.94%  |
| Other                   | 187       | 9.66%   |
| Intel Core i3           | 139       | 7.18%   |
| Intel Celeron           | 117       | 6.05%   |
| Intel Core 2 Duo        | 94        | 4.86%   |
| AMD Ryzen 5             | 90        | 4.65%   |
| Intel Pentium           | 61        | 3.15%   |
| AMD Ryzen 7             | 55        | 2.84%   |
| Intel Xeon              | 52        | 2.69%   |
| Intel Atom              | 42        | 2.17%   |
| AMD FX                  | 31        | 1.6%    |
| Intel Pentium Dual-Core | 27        | 1.4%    |
| AMD Ryzen 9             | 25        | 1.29%   |
| Intel Core 2 Quad       | 22        | 1.14%   |
| AMD Ryzen 3             | 20        | 1.03%   |
| AMD Athlon II X2        | 19        | 0.98%   |
| AMD A6                  | 15        | 0.78%   |
| Intel Genuine           | 13        | 0.67%   |
| AMD Phenom II X4        | 13        | 0.67%   |
| AMD A8                  | 13        | 0.67%   |
| Intel Pentium 4         | 11        | 0.57%   |
| AMD A4                  | 11        | 0.57%   |
| Intel Core i9           | 10        | 0.52%   |
| Intel Core 2            | 10        | 0.52%   |
| AMD A10                 | 10        | 0.52%   |
| Intel Pentium Silver    | 8         | 0.41%   |
| ARM BCM                 | 8         | 0.41%   |
| AMD Ryzen 5 PRO         | 8         | 0.41%   |
| AMD Athlon              | 8         | 0.41%   |
| Intel Pentium Dual      | 7         | 0.36%   |
| Intel Pentium D         | 7         | 0.36%   |
| AMD Turion 64 X2 Mobile | 7         | 0.36%   |
| AMD Ryzen 7 PRO         | 6         | 0.31%   |
| AMD E1                  | 6         | 0.31%   |
| AMD E                   | 6         | 0.31%   |
| AMD Athlon 64 X2        | 6         | 0.31%   |
| AMD Ryzen Threadripper  | 5         | 0.26%   |
| AMD Phenom II X6        | 5         | 0.26%   |
| AMD E2                  | 5         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 790       | 40.7%   |
| 4       | 702       | 36.17%  |
| 6       | 169       | 8.71%   |
| 8       | 103       | 5.31%   |
| 1       | 57        | 2.94%   |
| 12      | 30        | 1.55%   |
| 16      | 21        | 1.08%   |
| 10      | 15        | 0.77%   |
| 3       | 15        | 0.77%   |
| 14      | 14        | 0.72%   |
| Unknown | 7         | 0.36%   |
| 24      | 6         | 0.31%   |
| 48      | 5         | 0.26%   |
| 32      | 2         | 0.1%    |
| 20      | 2         | 0.1%    |
| 28      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1892      | 97.68%  |
| 2       | 37        | 1.91%   |
| Unknown | 6         | 0.31%   |
| 4       | 2         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1119      | 57.68%  |
| 1       | 814       | 41.96%  |
| Unknown | 7         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1861      | 96.13%  |
| Unknown        | 40        | 2.07%   |
| 32-bit         | 31        | 1.6%    |
| 64-bit         | 4         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 799       | 39.89%  |
| 0x306a9    | 94        | 4.69%   |
| 0x206a7    | 92        | 4.59%   |
| 0x306c3    | 80        | 3.99%   |
| 0x1067a    | 65        | 3.25%   |
| 0x806ec    | 32        | 1.6%    |
| 0x806c1    | 31        | 1.55%   |
| 0x6fd      | 29        | 1.45%   |
| 0x40651    | 28        | 1.4%    |
| 0x010000c8 | 27        | 1.35%   |
| 0x906e9    | 25        | 1.25%   |
| 0x506e3    | 25        | 1.25%   |
| 0x906ea    | 24        | 1.2%    |
| 0x806ea    | 24        | 1.2%    |
| 0x406c4    | 21        | 1.05%   |
| 0x20655    | 21        | 1.05%   |
| 0x806e9    | 20        | 1%      |
| 0x30678    | 20        | 1%      |
| 0x406e3    | 19        | 0.95%   |
| 0x306d4    | 18        | 0.9%    |
| 0x08108109 | 17        | 0.85%   |
| 0x10676    | 16        | 0.8%    |
| 0x0a50000c | 16        | 0.8%    |
| 0x06000852 | 16        | 0.8%    |
| 0x706e5    | 14        | 0.7%    |
| 0x706a1    | 14        | 0.7%    |
| 0x08701021 | 13        | 0.65%   |
| 0x0800820d | 12        | 0.6%    |
| 0x20652    | 11        | 0.55%   |
| 0x106e5    | 11        | 0.55%   |
| 0x106ca    | 11        | 0.55%   |
| 0xa0671    | 10        | 0.5%    |
| 0x6fb      | 10        | 0.5%    |
| 0x08600106 | 10        | 0.5%    |
| 0x06001119 | 10        | 0.5%    |
| 0x906ed    | 9         | 0.45%   |
| 0x05000119 | 9         | 0.45%   |
| 0x806d1    | 8         | 0.4%    |
| 0x706a8    | 8         | 0.4%    |
| 0x0810100b | 8         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 235       | 12.11%  |
| Haswell           | 172       | 8.86%   |
| SandyBridge       | 151       | 7.78%   |
| Unknown           | 137       | 7.06%   |
| IvyBridge         | 134       | 6.9%    |
| Penryn            | 116       | 5.98%   |
| Skylake           | 82        | 4.22%   |
| Silvermont        | 69        | 3.55%   |
| Core              | 64        | 3.3%    |
| Zen 2             | 61        | 3.14%   |
| K10               | 59        | 3.04%   |
| Westmere          | 56        | 2.89%   |
| Zen+              | 48        | 2.47%   |
| Zen 3             | 45        | 2.32%   |
| TigerLake         | 42        | 2.16%   |
| Piledriver        | 42        | 2.16%   |
| Goldmont plus     | 40        | 2.06%   |
| Broadwell         | 40        | 2.06%   |
| IceLake           | 39        | 2.01%   |
| CometLake         | 37        | 1.91%   |
| Zen               | 35        | 1.8%    |
| Alderlake Hybrid  | 29        | 1.49%   |
| Nehalem           | 25        | 1.29%   |
| K8 Hammer         | 23        | 1.18%   |
| Excavator         | 23        | 1.18%   |
| Bonnell           | 23        | 1.18%   |
| NetBurst          | 20        | 1.03%   |
| P6                | 16        | 0.82%   |
| Bobcat            | 12        | 0.62%   |
| Puma              | 11        | 0.57%   |
| Goldmont          | 11        | 0.57%   |
| Jaguar            | 10        | 0.52%   |
| Steamroller       | 8         | 0.41%   |
| Tremont           | 7         | 0.36%   |
| Bulldozer         | 7         | 0.36%   |
| K8 & K10 hybrid   | 5         | 0.26%   |
| Gracemont         | 4         | 0.21%   |
| K10 Llano         | 2         | 0.1%    |
| Meteorlake Hybrid | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1104      | 50.97%  |
| Nvidia                           | 544       | 25.12%  |
| AMD                              | 492       | 22.71%  |
| Matrox Electronics Systems       | 9         | 0.42%   |
| ASPEED Technology                | 7         | 0.32%   |
| Silicon Integrated Systems [SiS] | 6         | 0.28%   |
| VIA Technologies                 | 4         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 100       | 4.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 3.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 50        | 2.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 38        | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 34        | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 33        | 1.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 32        | 1.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32        | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.35%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 29        | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 1.3%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 29        | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 27        | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 1.21%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 26        | 1.17%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 24        | 1.08%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 24        | 1.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 20        | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 20        | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 0.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 16        | 0.72%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 16        | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 15        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.63%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 14        | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 0.58%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 13        | 0.58%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 13        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 848       | 43.62%  |
| 1 x AMD                  | 392       | 20.16%  |
| 1 x Nvidia               | 324       | 16.67%  |
| Intel + Nvidia           | 184       | 9.47%   |
| Other                    | 67        | 3.45%   |
| Intel + AMD              | 47        | 2.42%   |
| AMD + Nvidia             | 24        | 1.23%   |
| 2 x AMD                  | 23        | 1.18%   |
| 1 x SiS                  | 6         | 0.31%   |
| 1 x Matrox               | 6         | 0.31%   |
| 2 x Nvidia               | 5         | 0.26%   |
| 1 x VIA                  | 4         | 0.21%   |
| 2 x Intel                | 3         | 0.15%   |
| Nvidia + Matrox          | 3         | 0.15%   |
| 1 x ASPEED               | 3         | 0.15%   |
| Nvidia + ASPEED          | 2         | 0.1%    |
| AMD + ASPEED             | 2         | 0.1%    |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1501      | 76.54%  |
| Proprietary | 309       | 15.76%  |
| Unknown     | 151       | 7.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1192      | 60.08%  |
| 1.01-2.0   | 226       | 11.39%  |
| 0.01-0.5   | 219       | 11.04%  |
| 0.51-1.0   | 144       | 7.26%   |
| 3.01-4.0   | 99        | 4.99%   |
| 7.01-8.0   | 52        | 2.62%   |
| 5.01-6.0   | 27        | 1.36%   |
| 2.01-3.0   | 12        | 0.6%    |
| 8.01-16.0  | 7         | 0.35%   |
| 16.01-24.0 | 5         | 0.25%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 295       | 14.3%   |
| AU Optronics            | 221       | 10.71%  |
| LG Display              | 171       | 8.29%   |
| Dell                    | 160       | 7.76%   |
| Chimei Innolux          | 138       | 6.69%   |
| BOE                     | 136       | 6.59%   |
| Goldstar                | 109       | 5.28%   |
| Hewlett-Packard         | 92        | 4.46%   |
| Philips                 | 67        | 3.25%   |
| Acer                    | 61        | 2.96%   |
| BenQ                    | 44        | 2.13%   |
| AOC                     | 40        | 1.94%   |
| Ancor Communications    | 37        | 1.79%   |
| Lenovo                  | 33        | 1.6%    |
| Apple                   | 33        | 1.6%    |
| Chi Mei Optoelectronics | 29        | 1.41%   |
| Iiyama                  | 27        | 1.31%   |
| ViewSonic               | 24        | 1.16%   |
| Sharp                   | 23        | 1.11%   |
| Unknown                 | 20        | 0.97%   |
| PANDA                   | 17        | 0.82%   |
| ASUSTek Computer        | 17        | 0.82%   |
| Sony                    | 16        | 0.78%   |
| LG Philips              | 13        | 0.63%   |
| LG Electronics          | 13        | 0.63%   |
| Vizio                   | 10        | 0.48%   |
| HannStar                | 10        | 0.48%   |
| NEC Computers           | 8         | 0.39%   |
| InfoVision              | 8         | 0.39%   |
| Fujitsu Siemens         | 8         | 0.39%   |
| Eizo                    | 8         | 0.39%   |
| RTK                     | 7         | 0.34%   |
| Medion                  | 6         | 0.29%   |
| CSO                     | 6         | 0.29%   |
| Belinea                 | 6         | 0.29%   |
| Vestel Elektronik       | 5         | 0.24%   |
| Toshiba                 | 5         | 0.24%   |
| Sceptre Tech            | 5         | 0.24%   |
| Panasonic               | 5         | 0.24%   |
| Packard Bell            | 5         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                        | 31        | 1.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 11        | 0.52%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 6         | 0.28%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 6         | 0.28%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 6         | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.28%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch     | 5         | 0.23%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 5         | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 5         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.23%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 5         | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.23%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                        | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 5         | 0.23%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 5         | 0.23%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch            | 4         | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 4         | 0.19%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 4         | 0.19%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch        | 4         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 4         | 0.19%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                   | 4         | 0.19%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.19%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.19%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                     | 4         | 0.19%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 4         | 0.19%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 4         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 4         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 798       | 40.38%  |
| 1366x768 (WXGA)    | 359       | 18.17%  |
| 1280x1024 (SXGA)   | 129       | 6.53%   |
| 3840x2160 (4K)     | 99        | 5.01%   |
| 1600x900 (HD+)     | 92        | 4.66%   |
| 2560x1440 (QHD)    | 76        | 3.85%   |
| 1920x1200 (WUXGA)  | 58        | 2.94%   |
| 1680x1050 (WSXGA+) | 51        | 2.58%   |
| 1280x800 (WXGA)    | 50        | 2.53%   |
| 1440x900 (WXGA+)   | 44        | 2.23%   |
| Unknown            | 28        | 1.42%   |
| 1360x768           | 27        | 1.37%   |
| 3440x1440          | 17        | 0.86%   |
| 2560x1600          | 16        | 0.81%   |
| 1024x600           | 15        | 0.76%   |
| 3840x1080          | 11        | 0.56%   |
| 2560x1080          | 10        | 0.51%   |
| 1600x1200          | 10        | 0.51%   |
| 1024x768 (XGA)     | 9         | 0.46%   |
| 2288x1287          | 7         | 0.35%   |
| 3840x2400          | 6         | 0.3%    |
| 2880x1800          | 6         | 0.3%    |
| 1920x540           | 5         | 0.25%   |
| 1280x720 (HD)      | 5         | 0.25%   |
| 3200x1800 (QHD+)   | 4         | 0.2%    |
| 2160x1440          | 4         | 0.2%    |
| 2880x1620          | 3         | 0.15%   |
| 1920x1280          | 3         | 0.15%   |
| 3840x1600          | 2         | 0.1%    |
| 3840x1200          | 2         | 0.1%    |
| 2736x1824          | 2         | 0.1%    |
| 2520x1680          | 2         | 0.1%    |
| 1680x945           | 2         | 0.1%    |
| 1400x1050          | 2         | 0.1%    |
| 6400x1080          | 1         | 0.05%   |
| 5840x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5360x1440          | 1         | 0.05%   |
| 5040x1050          | 1         | 0.05%   |
| 4480x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 443       | 21.57%  |
| 17      | 178       | 8.67%   |
| 14      | 150       | 7.3%    |
| 24      | 148       | 7.21%   |
| 27      | 143       | 6.96%   |
| 13      | 138       | 6.72%   |
| 23      | 124       | 6.04%   |
| 21      | 120       | 5.84%   |
| Unknown | 106       | 5.16%   |
| 19      | 63        | 3.07%   |
| 31      | 58        | 2.82%   |
| 18      | 48        | 2.34%   |
| 22      | 36        | 1.75%   |
| 12      | 36        | 1.75%   |
| 11      | 30        | 1.46%   |
| 20      | 29        | 1.41%   |
| 34      | 26        | 1.27%   |
| 16      | 22        | 1.07%   |
| 10      | 22        | 1.07%   |
| 84      | 17        | 0.83%   |
| 40      | 14        | 0.68%   |
| 72      | 12        | 0.58%   |
| 32      | 12        | 0.58%   |
| 46      | 10        | 0.49%   |
| 54      | 7         | 0.34%   |
| 25      | 7         | 0.34%   |
| 142     | 6         | 0.29%   |
| 42      | 6         | 0.29%   |
| 33      | 6         | 0.29%   |
| 26      | 6         | 0.29%   |
| 36      | 5         | 0.24%   |
| 63      | 4         | 0.19%   |
| 52      | 4         | 0.19%   |
| 38      | 3         | 0.15%   |
| 28      | 3         | 0.15%   |
| 65      | 2         | 0.1%    |
| 48      | 2         | 0.1%    |
| 85      | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 745       | 36.81%  |
| 501-600        | 387       | 19.12%  |
| 401-500        | 255       | 12.6%   |
| 201-300        | 158       | 7.81%   |
| 351-400        | 154       | 7.61%   |
| Unknown        | 106       | 5.24%   |
| 601-700        | 76        | 3.75%   |
| 701-800        | 49        | 2.42%   |
| 1501-2000      | 31        | 1.53%   |
| 1001-1500      | 31        | 1.53%   |
| 801-900        | 18        | 0.89%   |
| 901-1000       | 7         | 0.35%   |
| More than 2000 | 6         | 0.3%    |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1348      | 72.16%  |
| 16/10   | 232       | 12.42%  |
| 5/4     | 116       | 6.21%   |
| Unknown | 86        | 4.6%    |
| 21/9    | 27        | 1.45%   |
| 4/3     | 23        | 1.23%   |
| 3/2     | 22        | 1.18%   |
| 1.00    | 6         | 0.32%   |
| 6/5     | 4         | 0.21%   |
| 32/9    | 2         | 0.11%   |
| 1.96    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 430       | 21.19%  |
| 201-250        | 331       | 16.31%  |
| 81-90          | 229       | 11.29%  |
| 301-350        | 145       | 7.15%   |
| 141-150        | 121       | 5.96%   |
| 151-200        | 120       | 5.91%   |
| Unknown        | 106       | 5.22%   |
| 351-500        | 104       | 5.13%   |
| 121-130        | 82        | 4.04%   |
| 251-300        | 67        | 3.3%    |
| More than 1000 | 55        | 2.71%   |
| 71-80          | 53        | 2.61%   |
| 501-1000       | 41        | 2.02%   |
| 61-70          | 36        | 1.77%   |
| 51-60          | 31        | 1.53%   |
| 111-120        | 28        | 1.38%   |
| 41-50          | 21        | 1.03%   |
| 131-140        | 17        | 0.84%   |
| 91-100         | 11        | 0.54%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 745       | 37.68%  |
| 101-120       | 505       | 25.54%  |
| 121-160       | 434       | 21.95%  |
| Unknown       | 106       | 5.36%   |
| 161-240       | 93        | 4.7%    |
| 1-50          | 65        | 3.29%   |
| More than 240 | 29        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1549      | 78.99%  |
| 2     | 289       | 14.74%  |
| 0     | 85        | 4.33%   |
| 3     | 37        | 1.89%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1026      | 35.95%  |
| Intel                             | 871       | 30.52%  |
| Qualcomm Atheros                  | 288       | 10.09%  |
| Broadcom                          | 189       | 6.62%   |
| Broadcom Limited                  | 55        | 1.93%   |
| MediaTek                          | 36        | 1.26%   |
| Ralink Technology                 | 35        | 1.23%   |
| TP-Link                           | 34        | 1.19%   |
| Marvell Technology Group          | 33        | 1.16%   |
| Nvidia                            | 31        | 1.09%   |
| Ralink                            | 28        | 0.98%   |
| ASIX Electronics                  | 21        | 0.74%   |
| Sierra Wireless                   | 12        | 0.42%   |
| Qualcomm Atheros Communications   | 12        | 0.42%   |
| D-Link                            | 10        | 0.35%   |
| Microchip Technology              | 9         | 0.32%   |
| Dell                              | 9         | 0.32%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.28%   |
| Samsung Electronics               | 8         | 0.28%   |
| NetGear                           | 8         | 0.28%   |
| ASUSTek Computer                  | 8         | 0.28%   |
| Aquantia                          | 8         | 0.28%   |
| Xiaomi                            | 7         | 0.25%   |
| Ericsson Business Mobile Networks | 7         | 0.25%   |
| Attansic Technology               | 6         | 0.21%   |
| VIA Technologies                  | 5         | 0.18%   |
| JMicron Technology                | 5         | 0.18%   |
| Hewlett-Packard                   | 5         | 0.18%   |
| Edimax Technology                 | 5         | 0.18%   |
| DisplayLink                       | 5         | 0.18%   |
| Lenovo                            | 4         | 0.14%   |
| Huawei Technologies               | 4         | 0.14%   |
| D-Link System                     | 4         | 0.14%   |
| Qualcomm Technologies             | 3         | 0.11%   |
| Microsoft                         | 3         | 0.11%   |
| Linksys                           | 3         | 0.11%   |
| Belkin Components                 | 3         | 0.11%   |
| Apple                             | 3         | 0.11%   |
| ZyDAS                             | 2         | 0.07%   |
| STMicroelectronics                | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 681       | 20.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 125       | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81        | 2.4%    |
| Intel Wi-Fi 6 AX200                                                    | 55        | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 51        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 47        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 45        | 1.33%   |
| Intel Wireless 7265                                                    | 45        | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 43        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 43        | 1.27%   |
| Intel Wireless 7260                                                    | 39        | 1.16%   |
| Intel Ethernet Connection I217-LM                                      | 38        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 36        | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 35        | 1.04%   |
| Intel Wireless 8265 / 8275                                             | 35        | 1.04%   |
| Intel Wi-Fi 6 AX201                                                    | 34        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 33        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 30        | 0.89%   |
| Intel I211 Gigabit Network Connection                                  | 29        | 0.86%   |
| Intel Ethernet Controller I225-V                                       | 29        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 29        | 0.86%   |
| Intel Wireless 3165                                                    | 28        | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 28        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 27        | 0.8%    |
| Intel Wireless 8260                                                    | 26        | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 24        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                   | 23        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 22        | 0.65%   |
| Realtek 802.11ac NIC                                                   | 22        | 0.65%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 21        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                          | 18        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17        | 0.5%    |
| Nvidia MCP61 Ethernet                                                  | 17        | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 17        | 0.5%    |
| Intel 82574L Gigabit Network Connection                                | 17        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                          | 16        | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 15        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 15        | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 15        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 617       | 42.14%  |
| Realtek Semiconductor           | 269       | 18.37%  |
| Qualcomm Atheros                | 231       | 15.78%  |
| Broadcom                        | 103       | 7.04%   |
| Ralink Technology               | 35        | 2.39%   |
| TP-Link                         | 33        | 2.25%   |
| Broadcom Limited                | 32        | 2.19%   |
| MediaTek                        | 31        | 2.12%   |
| Ralink                          | 28        | 1.91%   |
| Sierra Wireless                 | 12        | 0.82%   |
| Qualcomm Atheros Communications | 12        | 0.82%   |
| NetGear                         | 8         | 0.55%   |
| D-Link                          | 8         | 0.55%   |
| ASUSTek Computer                | 8         | 0.55%   |
| Edimax Technology               | 5         | 0.34%   |
| Dell                            | 4         | 0.27%   |
| Linksys                         | 3         | 0.2%    |
| Belkin Components               | 3         | 0.2%    |
| ZyDAS                           | 2         | 0.14%   |
| Qualcomm                        | 2         | 0.14%   |
| Microsoft                       | 2         | 0.14%   |
| Fibocom                         | 2         | 0.14%   |
| Xiaomi                          | 1         | 0.07%   |
| U.S. Robotics                   | 1         | 0.07%   |
| TRENDnet                        | 1         | 0.07%   |
| Texas Instruments               | 1         | 0.07%   |
| Tenda                           | 1         | 0.07%   |
| Sitecom Europe                  | 1         | 0.07%   |
| Realtek                         | 1         | 0.07%   |
| Quectel Wireless Solutions      | 1         | 0.07%   |
| IMC Networks                    | 1         | 0.07%   |
| Hewlett-Packard                 | 1         | 0.07%   |
| Gemtek                          | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| AVM                             | 1         | 0.07%   |
| Accton Technology               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 55        | 3.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 47        | 3.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 45        | 3.05%   |
| Intel Wireless 7265                                                     | 45        | 3.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 43        | 2.92%   |
| Intel Wireless 7260                                                     | 39        | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 36        | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 35        | 2.38%   |
| Intel Wireless 8265 / 8275                                              | 35        | 2.38%   |
| Intel Wi-Fi 6 AX201                                                     | 34        | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 2.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 1.97%   |
| Intel Wireless 3165                                                     | 28        | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 28        | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.83%   |
| Intel Wireless 8260                                                     | 26        | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 1.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 22        | 1.49%   |
| Realtek 802.11ac NIC                                                    | 22        | 1.49%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 21        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 17        | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                           | 16        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 15        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.95%   |
| Ralink MT7601U Wireless Adapter                                         | 14        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 14        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                          | 14        | 0.95%   |
| Intel Centrino Advanced-N 6235                                          | 14        | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 13        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.81%   |
| Intel Wireless 3160                                                     | 12        | 0.81%   |
| Intel WiFi Link 5100                                                    | 12        | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 12        | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 12        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 910       | 50.75%  |
| Intel                            | 490       | 27.33%  |
| Broadcom                         | 98        | 5.47%   |
| Qualcomm Atheros                 | 86        | 4.8%    |
| Marvell Technology Group         | 33        | 1.84%   |
| Nvidia                           | 31        | 1.73%   |
| Broadcom Limited                 | 24        | 1.34%   |
| ASIX Electronics                 | 21        | 1.17%   |
| Microchip Technology             | 9         | 0.5%    |
| Samsung Electronics              | 8         | 0.45%   |
| Aquantia                         | 8         | 0.45%   |
| Silicon Integrated Systems [SiS] | 7         | 0.39%   |
| Xiaomi                           | 6         | 0.33%   |
| Attansic Technology              | 6         | 0.33%   |
| VIA Technologies                 | 5         | 0.28%   |
| MediaTek                         | 5         | 0.28%   |
| JMicron Technology               | 5         | 0.28%   |
| DisplayLink                      | 5         | 0.28%   |
| Lenovo                           | 4         | 0.22%   |
| Dell                             | 4         | 0.22%   |
| Qualcomm Technologies            | 3         | 0.17%   |
| Huawei Technologies              | 3         | 0.17%   |
| D-Link System                    | 3         | 0.17%   |
| Apple                            | 3         | 0.17%   |
| QLogic                           | 2         | 0.11%   |
| D-Link                           | 2         | 0.11%   |
| TP-Link                          | 1         | 0.06%   |
| NetXen Incorporated              | 1         | 0.06%   |
| Netchip Technology               | 1         | 0.06%   |
| MYRICOM                          | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| Motorcomm Microelectronics.      | 1         | 0.06%   |
| Microsoft                        | 1         | 0.06%   |
| Mellanox Technologies            | 1         | 0.06%   |
| Insyde Software                  | 1         | 0.06%   |
| ICS Advent                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Emulex                           | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 681       | 36.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 125       | 6.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81        | 4.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 51        | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                      | 43        | 2.3%    |
| Intel Ethernet Connection I217-LM                                      | 38        | 2.04%   |
| Intel I211 Gigabit Network Connection                                  | 29        | 1.55%   |
| Intel Ethernet Controller I225-V                                       | 29        | 1.55%   |
| Intel Ethernet Connection (2) I219-V                                   | 23        | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                          | 18        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17        | 0.91%   |
| Nvidia MCP61 Ethernet                                                  | 17        | 0.91%   |
| Intel 82574L Gigabit Network Connection                                | 17        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.8%    |
| Intel 82579V Gigabit Network Connection                                | 15        | 0.8%    |
| Intel Ethernet Connection I218-LM                                      | 14        | 0.75%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14        | 0.75%   |
| Intel Ethernet Connection (7) I219-V                                   | 13        | 0.7%    |
| Intel Ethernet Connection I219-LM                                      | 12        | 0.64%   |
| Intel Ethernet Connection I217-V                                       | 12        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                   | 12        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 12        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 12        | 0.64%   |
| Intel I210 Gigabit Network Connection                                  | 11        | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 9         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 0.43%   |
| Nvidia MCP79 Ethernet                                                  | 8         | 0.43%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 8         | 0.43%   |
| Intel I350 Gigabit Network Connection                                  | 8         | 0.43%   |
| Intel Ethernet Connection I219-V                                       | 8         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                                  | 8         | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                  | 8         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.43%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 8         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 7         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1682      | 54.5%   |
| WiFi     | 1370      | 44.39%  |
| Modem    | 32        | 1.04%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1061      | 53.29%  |
| Ethernet | 930       | 46.71%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1028      | 52.8%   |
| 1     | 771       | 39.6%   |
| 0     | 88        | 4.52%   |
| 3     | 33        | 1.69%   |
| 4     | 17        | 0.87%   |
| 6     | 6         | 0.31%   |
| 5     | 3         | 0.15%   |
| 14    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1526      | 77.54%  |
| Yes     | 441       | 22.41%  |
| Unknown | 1         | 0.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 500       | 46.86%  |
| Realtek Semiconductor           | 117       | 10.97%  |
| Broadcom                        | 72        | 6.75%   |
| Qualcomm Atheros Communications | 71        | 6.65%   |
| Cambridge Silicon Radio         | 63        | 5.9%    |
| IMC Networks                    | 43        | 4.03%   |
| Foxconn / Hon Hai               | 30        | 2.81%   |
| Apple                           | 30        | 2.81%   |
| Lite-On Technology              | 27        | 2.53%   |
| Dell                            | 24        | 2.25%   |
| ASUSTek Computer                | 18        | 1.69%   |
| MediaTek                        | 14        | 1.31%   |
| Hewlett-Packard                 | 14        | 1.31%   |
| Ralink                          | 10        | 0.94%   |
| Toshiba                         | 9         | 0.84%   |
| TP-Link                         | 3         | 0.28%   |
| Integrated System Solution      | 3         | 0.28%   |
| Foxconn International           | 3         | 0.28%   |
| Belkin Components               | 3         | 0.28%   |
| Ralink Technology               | 2         | 0.19%   |
| Alps Electric                   | 2         | 0.19%   |
| Unknown                         | 2         | 0.19%   |
| USI                             | 1         | 0.09%   |
| TRENDnet                        | 1         | 0.09%   |
| Smart Modular Technologies      | 1         | 0.09%   |
| Realtek                         | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| Conwise Technology              | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 179       | 16.76%  |
| Intel AX201 Bluetooth                               | 100       | 9.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 81        | 7.58%   |
| Realtek Bluetooth Radio                             | 77        | 7.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 63        | 5.9%    |
| Intel AX200 Bluetooth                               | 54        | 5.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 27        | 2.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 2.25%   |
| Intel AX210 Bluetooth                               | 20        | 1.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.31%   |
| Intel Bluetooth Device                              | 14        | 1.31%   |
| IMC Networks Bluetooth Device                       | 14        | 1.31%   |
| Dell DW375 Bluetooth Module                         | 14        | 1.31%   |
| MediaTek Wireless_Device                            | 13        | 1.22%   |
| IMC Networks Wireless_Device                        | 12        | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 1.03%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 0.94%   |
| Apple Bluetooth Host Controller                     | 10        | 0.94%   |
| IMC Networks Bluetooth Radio                        | 9         | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 8         | 0.75%   |
| Apple Bluetooth HCI                                 | 8         | 0.75%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.66%   |
| Lite-On Bluetooth Device                            | 7         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.66%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 7         | 0.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.56%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1374      | 53.5%   |
| AMD                                          | 499       | 19.43%  |
| Nvidia                                       | 437       | 17.02%  |
| C-Media Electronics                          | 47        | 1.83%   |
| Logitech                                     | 17        | 0.66%   |
| Creative Labs                                | 13        | 0.51%   |
| Realtek Semiconductor                        | 12        | 0.47%   |
| GN Netcom                                    | 12        | 0.47%   |
| JMTek                                        | 10        | 0.39%   |
| Generalplus Technology                       | 10        | 0.39%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.35%   |
| ASUSTek Computer                             | 9         | 0.35%   |
| VIA Technologies                             | 7         | 0.27%   |
| Lenovo                                       | 6         | 0.23%   |
| Kingston Technology                          | 6         | 0.23%   |
| Corsair                                      | 6         | 0.23%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.19%   |
| Plantronics                                  | 5         | 0.19%   |
| Jieli Technology                             | 5         | 0.19%   |
| Hewlett-Packard                              | 5         | 0.19%   |
| Focusrite-Novation                           | 5         | 0.19%   |
| Creative Technology                          | 4         | 0.16%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.12%   |
| Texas Instruments                            | 3         | 0.12%   |
| Tenx Technology                              | 3         | 0.12%   |
| Razer USA                                    | 3         | 0.12%   |
| Ensoniq                                      | 3         | 0.12%   |
| DSEA A/S                                     | 3         | 0.12%   |
| Cambridge Silicon Radio                      | 3         | 0.12%   |
| Sony                                         | 2         | 0.08%   |
| Micro Star International                     | 2         | 0.08%   |
| Meizu                                        | 2         | 0.08%   |
| FiiO Electronics Technology                  | 2         | 0.08%   |
| Dell                                         | 2         | 0.08%   |
| D&M Holdings (Denon/Marantz)                 | 2         | 0.08%   |
| Conexant Systems                             | 2         | 0.08%   |
| BEHRINGER International                      | 2         | 0.08%   |
| ASRock                                       | 2         | 0.08%   |
| Alesis                                       | 2         | 0.08%   |
| XMOS                                         | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 153       | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 138       | 4.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 133       | 4.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 111       | 3.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 94        | 3.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 93        | 3.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 88        | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 83        | 2.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 66        | 2.17%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 64        | 2.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 57        | 1.87%   |
| AMD FCH Azalia Controller                                                  | 52        | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 50        | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 43        | 1.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 42        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 42        | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 41        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 41        | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 40        | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                   | 40        | 1.32%   |
| Nvidia High Definition Audio Controller                                    | 37        | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 36        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 36        | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 32        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 31        | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 30        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 30        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 29        | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 28        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 27        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 26        | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 24        | 0.79%   |
| AMD Radeon High Definition Audio Controller                                | 24        | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 23        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 22        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 280       | 19.49%  |
| SK hynix                                         | 237       | 16.49%  |
| Kingston                                         | 183       | 12.73%  |
| Unknown                                          | 155       | 10.79%  |
| Micron Technology                                | 127       | 8.84%   |
| Crucial                                          | 104       | 7.24%   |
| Corsair                                          | 75        | 5.22%   |
| G.Skill                                          | 46        | 3.2%    |
| Ramaxel Technology                               | 30        | 2.09%   |
| Elpida                                           | 24        | 1.67%   |
| Unknown (ABCD)                                   | 23        | 1.6%    |
| Nanya Technology                                 | 23        | 1.6%    |
| A-DATA Technology                                | 23        | 1.6%    |
| Smart                                            | 13        | 0.9%    |
| Unknown                                          | 13        | 0.9%    |
| Team                                             | 12        | 0.84%   |
| Patriot                                          | 9         | 0.63%   |
| Teikon                                           | 6         | 0.42%   |
| Transcend                                        | 4         | 0.28%   |
| Qimonda                                          | 4         | 0.28%   |
| GOODRAM                                          | 4         | 0.28%   |
| Neo Forza                                        | 3         | 0.21%   |
| HBS                                              | 3         | 0.21%   |
| Timetec                                          | 2         | 0.14%   |
| Silicon Power                                    | 2         | 0.14%   |
| Netlist                                          | 2         | 0.14%   |
| Hewlett-Packard                                  | 2         | 0.14%   |
| Atermiter                                        | 2         | 0.14%   |
| Unknown (9B0D)                                   | 1         | 0.07%   |
| Unknown (940A)                                   | 1         | 0.07%   |
| Unknown (0x7FFF)                                 | 1         | 0.07%   |
| Unknown (0x7F61000000000000)                     | 1         | 0.07%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.07%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.07%   |
| Unknown (0x0E9D)                                 | 1         | 0.07%   |
| Unknown (0x0E75)                                 | 1         | 0.07%   |
| Unknown (0x0C26)                                 | 1         | 0.07%   |
| Unknown (0x0B6B)                                 | 1         | 0.07%   |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.07%   |
| Unifosa                                          | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 0.85%   |
| Unknown                                                          | 13        | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 10        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 10        | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 8         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 8         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.46%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 7         | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 6         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.39%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.39%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.39%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                    | 6         | 0.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s              | 5         | 0.33%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s           | 5         | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 4         | 0.26%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.26%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.26%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 4         | 0.26%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 4         | 0.26%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 4         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 497       | 39.66%  |
| DDR3    | 452       | 36.07%  |
| DDR2    | 82        | 6.54%   |
| SDRAM   | 54        | 4.31%   |
| LPDDR4  | 43        | 3.43%   |
| DDR5    | 38        | 3.03%   |
| Unknown | 34        | 2.71%   |
| LPDDR3  | 25        | 2%      |
| DDR     | 18        | 1.44%   |
| LPDDR5  | 7         | 0.56%   |
| DRAM    | 3         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 696       | 56.27%  |
| DIMM         | 463       | 37.43%  |
| Row Of Chips | 64        | 5.17%   |
| Unknown      | 7         | 0.57%   |
| Chip         | 6         | 0.49%   |
| RIMM         | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 448       | 32.94%  |
| 4096   | 366       | 26.91%  |
| 16384  | 222       | 16.32%  |
| 2048   | 203       | 14.93%  |
| 32768  | 61        | 4.49%   |
| 1024   | 45        | 3.31%   |
| 65536  | 4         | 0.29%   |
| 512    | 4         | 0.29%   |
| 49152  | 2         | 0.15%   |
| 131072 | 1         | 0.07%   |
| 12288  | 1         | 0.07%   |
| 1536   | 1         | 0.07%   |
| 256    | 1         | 0.07%   |
| 32     | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 293       | 21.62%  |
| 3200    | 192       | 14.17%  |
| 2667    | 151       | 11.14%  |
| 1333    | 105       | 7.75%   |
| 2400    | 98        | 7.23%   |
| 2133    | 55        | 4.06%   |
| 667     | 42        | 3.1%    |
| 800     | 39        | 2.88%   |
| 1334    | 35        | 2.58%   |
| Unknown | 34        | 2.51%   |
| 3600    | 27        | 1.99%   |
| 1066    | 19        | 1.4%    |
| 4199    | 16        | 1.18%   |
| 3266    | 15        | 1.11%   |
| 1067    | 15        | 1.11%   |
| 5600    | 14        | 1.03%   |
| 4800    | 14        | 1.03%   |
| 1867    | 14        | 1.03%   |
| 3733    | 11        | 0.81%   |
| 8400    | 10        | 0.74%   |
| 2048    | 10        | 0.74%   |
| 533     | 10        | 0.74%   |
| 6400    | 9         | 0.66%   |
| 4267    | 9         | 0.66%   |
| 3800    | 9         | 0.66%   |
| 2933    | 9         | 0.66%   |
| 3000    | 7         | 0.52%   |
| 1866    | 7         | 0.52%   |
| 3466    | 6         | 0.44%   |
| 2666    | 6         | 0.44%   |
| 1800    | 6         | 0.44%   |
| 4000    | 5         | 0.37%   |
| 3400    | 5         | 0.37%   |
| 975     | 5         | 0.37%   |
| 2800    | 4         | 0.3%    |
| 1639    | 4         | 0.3%    |
| 49926   | 3         | 0.22%   |
| 400     | 3         | 0.22%   |
| 333     | 3         | 0.22%   |
| 266     | 3         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 21        | 29.17%  |
| Brother Industries     | 13        | 18.06%  |
| Canon                  | 9         | 12.5%   |
| Seiko Epson            | 8         | 11.11%  |
| Samsung Electronics    | 7         | 9.72%   |
| Dymo-CoStar            | 4         | 5.56%   |
| QinHeng Electronics    | 2         | 2.78%   |
| Xerox                  | 1         | 1.39%   |
| STMicroelectronics     | 1         | 1.39%   |
| Prolific Technology    | 1         | 1.39%   |
| Panasonic (Matsushita) | 1         | 1.39%   |
| Lexmark International  | 1         | 1.39%   |
| ICS Advent             | 1         | 1.39%   |
| Graphtec America       | 1         | 1.39%   |
| BIXOLON                | 1         | 1.39%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 3         | 4.05%   |
| Brother Printer                                           | 3         | 4.05%   |
| Samsung SCX-4200 series                                   | 2         | 2.7%    |
| Samsung M2020 Series                                      | 2         | 2.7%    |
| QinHeng CH340S                                            | 2         | 2.7%    |
| HP LaserJet Professional P1102w                           | 2         | 2.7%    |
| HP LaserJet Professional P 1102w                          | 2         | 2.7%    |
| HP Deskjet F4500 series                                   | 2         | 2.7%    |
| HP DeskJet 2700 series                                    | 2         | 2.7%    |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.7%    |
| Xerox Phaser 3020                                         | 1         | 1.35%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.35%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.35%   |
| Seiko Epson WF-2880 Series                                | 1         | 1.35%   |
| Seiko Epson L380 Series                                   | 1         | 1.35%   |
| Seiko Epson L312 Series                                   | 1         | 1.35%   |
| Seiko Epson EPSON WF-2010 Series                          | 1         | 1.35%   |
| Samsung M2070 Series                                      | 1         | 1.35%   |
| Samsung CLX-8380 Series                                   | 1         | 1.35%   |
| Samsung CLX-4190 Series                                   | 1         | 1.35%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.35%   |
| Panasonic (Matsushita) KX-MB2130RU                        | 1         | 1.35%   |
| Lexmark International InkJet Color Printer                | 1         | 1.35%   |
| ICS Advent Parallel Adapter                               | 1         | 1.35%   |
| HP Smart Tank 7300 series                                 | 1         | 1.35%   |
| HP Smart Tank 510 series                                  | 1         | 1.35%   |
| HP Officejet 4500 G510a-f                                 | 1         | 1.35%   |
| HP LaserJet 1022                                          | 1         | 1.35%   |
| HP LaserJet 1020                                          | 1         | 1.35%   |
| HP LaserJet 1005                                          | 1         | 1.35%   |
| HP ENVY Photo 7800 series                                 | 1         | 1.35%   |
| HP DeskJet F300 series                                    | 1         | 1.35%   |
| HP DeskJet 845c                                           | 1         | 1.35%   |
| HP DeskJet 3630 series                                    | 1         | 1.35%   |
| HP Deskjet 3050 J610 series                               | 1         | 1.35%   |
| HP DeskJet 2600 series                                    | 1         | 1.35%   |
| HP DeskJet 2130 series                                    | 1         | 1.35%   |
| HP color LaserJet 4650                                    | 1         | 1.35%   |
| Graphtec America Graphtec Printer                         | 1         | 1.35%   |
| Dymo-CoStar LabelWriter 310                               | 1         | 1.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 9         | 50%     |
| Seiko Epson                                    | 5         | 27.78%  |
| Hewlett-Packard                                | 2         | 11.11%  |
| Siemens Information and Communication Products | 1         | 5.56%   |
| Acer Peripherals (now BenQ)                    | 1         | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                         | 3         | 16.67%  |
| Canon CanoScan LiDE 120                                                         | 2         | 11.11%  |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 5.56%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                | 1         | 5.56%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                               | 1         | 5.56%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 1         | 5.56%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                            | 1         | 5.56%   |
| Seiko Epson ES-D400 [GT-S80]                                                    | 1         | 5.56%   |
| HP ScanJet G4010                                                                | 1         | 5.56%   |
| HP ScanJet 4370                                                                 | 1         | 5.56%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 5.56%   |
| Canon CanoScan LiDE 90                                                          | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                                          | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                                         | 1         | 5.56%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 251       | 23.52%  |
| Microdia                               | 88        | 8.25%   |
| Bison Electronics                      | 79        | 7.4%    |
| Realtek Semiconductor                  | 66        | 6.19%   |
| IMC Networks                           | 66        | 6.19%   |
| Logitech                               | 63        | 5.9%    |
| Sunplus Innovation Technology          | 54        | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 48        | 4.5%    |
| Quanta                                 | 45        | 4.22%   |
| Suyin                                  | 35        | 3.28%   |
| Apple                                  | 30        | 2.81%   |
| Syntek                                 | 28        | 2.62%   |
| Ricoh                                  | 19        | 1.78%   |
| Luxvisions Innotech Limited            | 19        | 1.78%   |
| Lite-On Technology                     | 17        | 1.59%   |
| Silicon Motion                         | 14        | 1.31%   |
| Alcor Micro                            | 14        | 1.31%   |
| Samsung Electronics                    | 10        | 0.94%   |
| Acer                                   | 8         | 0.75%   |
| Z-Star Microelectronics                | 7         | 0.66%   |
| Importek                               | 7         | 0.66%   |
| Microsoft                              | 6         | 0.56%   |
| Lenovo                                 | 6         | 0.56%   |
| Generalplus Technology                 | 6         | 0.56%   |
| KYE Systems (Mouse Systems)            | 5         | 0.47%   |
| ARC International                      | 5         | 0.47%   |
| SunplusIT                              | 4         | 0.37%   |
| Sonix Technology                       | 4         | 0.37%   |
| Razer USA                              | 3         | 0.28%   |
| Primax Electronics                     | 3         | 0.28%   |
| LG Electronics                         | 3         | 0.28%   |
| DigiTech                               | 3         | 0.28%   |
| Cubeternet                             | 3         | 0.28%   |
| Creative Technology                    | 3         | 0.28%   |
| ALi                                    | 3         | 0.28%   |
| Y Media                                | 2         | 0.19%   |
| Unknown                                | 2         | 0.19%   |
| Sunplus Technology                     | 2         | 0.19%   |
| Ruision                                | 2         | 0.19%   |
| MacroSilicon                           | 2         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 40        | 3.73%   |
| Bison Integrated Camera                                                    | 24        | 2.24%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 21        | 1.96%   |
| Realtek Integrated_Webcam_HD                                               | 20        | 1.86%   |
| Microdia Integrated_Webcam_HD                                              | 20        | 1.86%   |
| Chicony HD Webcam                                                          | 17        | 1.58%   |
| Syntek Integrated Camera                                                   | 16        | 1.49%   |
| IMC Networks Integrated Camera                                             | 16        | 1.49%   |
| Sunplus Integrated_Webcam_HD                                               | 15        | 1.4%    |
| Chicony HP HD Camera                                                       | 15        | 1.4%    |
| Microdia Integrated Webcam                                                 | 14        | 1.3%    |
| Logitech Webcam C270                                                       | 14        | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                                              | 11        | 1.03%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 10        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 10        | 0.93%   |
| Quanta HD User Facing                                                      | 9         | 0.84%   |
| Chicony VGA WebCam                                                         | 9         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 9         | 0.84%   |
| Apple Built-in iSight                                                      | 9         | 0.84%   |
| Microdia Webcam Vitade AF                                                  | 8         | 0.75%   |
| Logitech HD Pro Webcam C920                                                | 8         | 0.75%   |
| Lite-On Integrated Camera                                                  | 8         | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                                            | 8         | 0.75%   |
| Bison Lenovo Integrated Webcam                                             | 8         | 0.75%   |
| Realtek USB Camera                                                         | 7         | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 7         | 0.65%   |
| Chicony USB2.0 Camera                                                      | 7         | 0.65%   |
| Chicony USB 2.0 Camera                                                     | 7         | 0.65%   |
| Chicony HP Wide Vision HD Camera                                           | 7         | 0.65%   |
| Chicony HP HD Webcam                                                       | 7         | 0.65%   |
| Bison Lenovo EasyCamera                                                    | 7         | 0.65%   |
| Ricoh HD Webcam                                                            | 6         | 0.56%   |
| Luxvisions Innotech Limited Integrated Camera                              | 6         | 0.56%   |
| Chicony HP Webcam                                                          | 6         | 0.56%   |
| Chicony HP TrueVision HD Camera                                            | 6         | 0.56%   |
| Chicony HP Truevision HD                                                   | 6         | 0.56%   |
| Chicony Chicony USB2.0 Camera                                              | 6         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 6         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 6         | 0.56%   |
| Bison BisonCam, NB Pro                                                     | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 72        | 41.62%  |
| Synaptics                  | 39        | 22.54%  |
| Shenzhen Goodix Technology | 21        | 12.14%  |
| Upek                       | 12        | 6.94%   |
| Elan Microelectronics      | 11        | 6.36%   |
| AuthenTec                  | 7         | 4.05%   |
| STMicroelectronics         | 4         | 2.31%   |
| LighTuning Technology      | 4         | 2.31%   |
| Focal-systems.Corp         | 2         | 1.16%   |
| Samsung Electronics        | 1         | 0.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 8.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 6.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 5.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 5.2%    |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.47%   |
| Elan ELAN:ARM-M4                                                           | 6         | 3.47%   |
| Validity Sensors VFS491                                                    | 5         | 2.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.89%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.89%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.89%   |
| Elan ELAN:Fingerprint                                                      | 5         | 2.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.31%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.31%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.31%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.73%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.73%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.73%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 1.73%   |
| Synaptics  WBDI                                                            | 3         | 1.73%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 1.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.73%   |
| AuthenTec AES1600                                                          | 3         | 1.73%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.16%   |
| Synaptics WBDI                                                             | 2         | 1.16%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.16%   |
| Synaptics UWP WBDI                                                         | 2         | 1.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.16%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.16%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.58%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.58%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.58%   |
| Synaptics WBDI Device                                                      | 1         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 60        | 50%     |
| Alcor Micro           | 29        | 24.17%  |
| O2 Micro              | 10        | 8.33%   |
| Upek                  | 4         | 3.33%   |
| Lenovo                | 4         | 3.33%   |
| SCM Microsystems      | 3         | 2.5%    |
| Advanced Card Systems | 3         | 2.5%    |
| OmniKey               | 2         | 1.67%   |
| Gemalto (was Gemplus) | 2         | 1.67%   |
| Realtek Semiconductor | 1         | 0.83%   |
| Kobil Systems         | 1         | 0.83%   |
| Chicony Electronics   | 1         | 0.83%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 24.17%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 17.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 14.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 8.33%   |
| Broadcom 5880                                                                | 8         | 6.67%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 7         | 5.83%   |
| Broadcom 58200                                                               | 7         | 5.83%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.33%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 1.67%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 1.67%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.83%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.83%   |
| SCM Microsystems Identiv SmartOS Reader                                      | 1         | 0.83%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.83%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.83%   |
| OmniKey CardMan 1021                                                         | 1         | 0.83%   |
| Kobil Systems Smart Token                                                    | 1         | 0.83%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.83%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.83%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1417      | 72.04%  |
| 1     | 433       | 22.01%  |
| 2     | 89        | 4.52%   |
| 3     | 16        | 0.81%   |
| 4     | 9         | 0.46%   |
| 8     | 2         | 0.1%    |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 175       | 25.77%  |
| Fingerprint reader       | 174       | 25.63%  |
| Chipcard                 | 109       | 16.05%  |
| Net/wireless             | 57        | 8.39%   |
| Communication controller | 27        | 3.98%   |
| Camera                   | 21        | 3.09%   |
| Bluetooth                | 19        | 2.8%    |
| Unassigned class         | 18        | 2.65%   |
| Multimedia controller    | 16        | 2.36%   |
| Sound                    | 12        | 1.77%   |
| Storage                  | 11        | 1.62%   |
| Network                  | 8         | 1.18%   |
| Modem                    | 7         | 1.03%   |
| Card reader              | 7         | 1.03%   |
| Net/ethernet             | 5         | 0.74%   |
| Flash memory             | 5         | 0.74%   |
| Firewire controller      | 3         | 0.44%   |
| Dvb card                 | 2         | 0.29%   |
| Tv card                  | 1         | 0.15%   |
| Storage/raid             | 1         | 0.15%   |
| Storage/ata              | 1         | 0.15%   |

