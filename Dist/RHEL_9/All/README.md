RHEL 9 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_9/Desktop/README.md) and [notebooks](/Dist/RHEL_9/Notebook/README.md).

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

Total: 199

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f645e7853f](https://linux-hardware.org/?probe=f645e7853f) | Dec 14, 2025 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [372612d4cb](https://linux-hardware.org/?probe=372612d4cb) | Nov 21, 2025 |
| Dell          | Pro Max 14 MC14250          | Notebook    | [e284bbe318](https://linux-hardware.org/?probe=e284bbe318) | Aug 08, 2025 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ebfb439ae8](https://linux-hardware.org/?probe=ebfb439ae8) | Jul 28, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [699e60ab98](https://linux-hardware.org/?probe=699e60ab98) | Jul 20, 2025 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [7bd3dfa8e1](https://linux-hardware.org/?probe=7bd3dfa8e1) | Jul 17, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d694fa0335](https://linux-hardware.org/?probe=d694fa0335) | Jul 13, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [03e67e85c7](https://linux-hardware.org/?probe=03e67e85c7) | Jul 07, 2025 |
| Dell          | Precision 5490              | Notebook    | [862d9564ec](https://linux-hardware.org/?probe=862d9564ec) | Jun 30, 2025 |
| Dell          | Precision 5490              | Notebook    | [aa3fe64169](https://linux-hardware.org/?probe=aa3fe64169) | Jun 02, 2025 |
| Dell          | Precision M4800             | Notebook    | [f3a2c881d4](https://linux-hardware.org/?probe=f3a2c881d4) | May 29, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [f65f1d1f72](https://linux-hardware.org/?probe=f65f1d1f72) | May 20, 2025 |
| Dell          | Precision M4800             | Notebook    | [b31e551454](https://linux-hardware.org/?probe=b31e551454) | May 14, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9cb3a733b8](https://linux-hardware.org/?probe=9cb3a733b8) | May 08, 2025 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [54677dffeb](https://linux-hardware.org/?probe=54677dffeb) | Apr 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [12adf7443f](https://linux-hardware.org/?probe=12adf7443f) | Apr 01, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [14d91dd406](https://linux-hardware.org/?probe=14d91dd406) | Mar 29, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8f0328cec8](https://linux-hardware.org/?probe=8f0328cec8) | Mar 29, 2025 |
| Acer          | Aspire AL14-31P             | Notebook    | [c1b9edd8c5](https://linux-hardware.org/?probe=c1b9edd8c5) | Mar 27, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [eb8126d017](https://linux-hardware.org/?probe=eb8126d017) | Mar 21, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [35923a2701](https://linux-hardware.org/?probe=35923a2701) | Mar 21, 2025 |
| Dell          | 0HHV7N A00                  | Desktop     | [3a50df2774](https://linux-hardware.org/?probe=3a50df2774) | Mar 14, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [58a52af839](https://linux-hardware.org/?probe=58a52af839) | Mar 13, 2025 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [38f0ab9177](https://linux-hardware.org/?probe=38f0ab9177) | Mar 01, 2025 |
| ASUSTek       | NUC14MNB2 60AS00H0-MB7A0... | Mini pc     | [0e6c6e0f24](https://linux-hardware.org/?probe=0e6c6e0f24) | Mar 01, 2025 |
| MACHINIST     | X99 PR9                     | Desktop     | [802d479447](https://linux-hardware.org/?probe=802d479447) | Feb 23, 2025 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | Notebook    | [72c5b1b57e](https://linux-hardware.org/?probe=72c5b1b57e) | Feb 22, 2025 |
| Lenovo        | ThinkPad P16v Gen 2 21KY... | Notebook    | [4c043a2d86](https://linux-hardware.org/?probe=4c043a2d86) | Feb 12, 2025 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [bd083d24c2](https://linux-hardware.org/?probe=bd083d24c2) | Jan 23, 2025 |
| HP            | ProBook 4530s               | Notebook    | [e4dbd31493](https://linux-hardware.org/?probe=e4dbd31493) | Jan 21, 2025 |
| HP            | 81C6 MVB 0C                 | Server      | [68f38e4660](https://linux-hardware.org/?probe=68f38e4660) | Jan 07, 2025 |
| GEEKOM        | A5                          | Desktop     | [3193148efc](https://linux-hardware.org/?probe=3193148efc) | Jan 07, 2025 |
| ASRock        | X570 Steel Legend           | Desktop     | [2b29fc224e](https://linux-hardware.org/?probe=2b29fc224e) | Jan 04, 2025 |
| Dell          | Latitude 7490               | Notebook    | [5781936456](https://linux-hardware.org/?probe=5781936456) | Dec 31, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8c9e4bdd75](https://linux-hardware.org/?probe=8c9e4bdd75) | Dec 26, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [eab49b95cc](https://linux-hardware.org/?probe=eab49b95cc) | Dec 24, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [ea8d4bb295](https://linux-hardware.org/?probe=ea8d4bb295) | Nov 24, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [36a5d324c6](https://linux-hardware.org/?probe=36a5d324c6) | Nov 20, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [2724eb028f](https://linux-hardware.org/?probe=2724eb028f) | Nov 20, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [5b8dc636f4](https://linux-hardware.org/?probe=5b8dc636f4) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [087f372f3b](https://linux-hardware.org/?probe=087f372f3b) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [28e20675ef](https://linux-hardware.org/?probe=28e20675ef) | Nov 16, 2024 |
| ASRock        | H310CM-HG4                  | Desktop     | [947520025d](https://linux-hardware.org/?probe=947520025d) | Nov 12, 2024 |
| ASRock        | H310CM-HG4                  | Desktop     | [11021e8d32](https://linux-hardware.org/?probe=11021e8d32) | Nov 12, 2024 |
| ASRock        | H310CM-HG4                  | Desktop     | [63b0d341db](https://linux-hardware.org/?probe=63b0d341db) | Nov 12, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [3d9365dd8e](https://linux-hardware.org/?probe=3d9365dd8e) | Nov 08, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [9f24fcf5f6](https://linux-hardware.org/?probe=9f24fcf5f6) | Nov 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1a592a4c8c](https://linux-hardware.org/?probe=1a592a4c8c) | Oct 30, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [88c68a9636](https://linux-hardware.org/?probe=88c68a9636) | Oct 19, 2024 |
| Dell          | Latitude E6520              | Notebook    | [1fccf13e1b](https://linux-hardware.org/?probe=1fccf13e1b) | Oct 14, 2024 |
| Unknown       | 01W23F A00                  | Server      | [8e73509007](https://linux-hardware.org/?probe=8e73509007) | Oct 10, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [dac9fa757b](https://linux-hardware.org/?probe=dac9fa757b) | Oct 09, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2739aa253d](https://linux-hardware.org/?probe=2739aa253d) | Oct 09, 2024 |
| HP            | 8949 11                     | Desktop     | [e10c4e5057](https://linux-hardware.org/?probe=e10c4e5057) | Oct 02, 2024 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [8b9768888f](https://linux-hardware.org/?probe=8b9768888f) | Sep 29, 2024 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [8bc1a2e515](https://linux-hardware.org/?probe=8bc1a2e515) | Sep 25, 2024 |
| Unknown       | 01W23F A00                  | Server      | [a905969722](https://linux-hardware.org/?probe=a905969722) | Sep 24, 2024 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [1984c24a25](https://linux-hardware.org/?probe=1984c24a25) | Sep 24, 2024 |
| Dell          | Precision 7730              | Notebook    | [7f0ef4c558](https://linux-hardware.org/?probe=7f0ef4c558) | Sep 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [325da6b558](https://linux-hardware.org/?probe=325da6b558) | Sep 16, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [7a1624219e](https://linux-hardware.org/?probe=7a1624219e) | Sep 07, 2024 |
| Dell          | Precision 7530              | Notebook    | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [fe4942ef99](https://linux-hardware.org/?probe=fe4942ef99) | Aug 16, 2024 |
| Dell          | 060K5C A06                  | Server      | [075693e3a5](https://linux-hardware.org/?probe=075693e3a5) | Aug 02, 2024 |
| Dell          | 060K5C A06                  | Server      | [5c5692ba57](https://linux-hardware.org/?probe=5c5692ba57) | Jul 24, 2024 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [4d550f9d4c](https://linux-hardware.org/?probe=4d550f9d4c) | Jul 22, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [d8feb4c87f](https://linux-hardware.org/?probe=d8feb4c87f) | Jul 18, 2024 |
| Unknown       | G13                         | Notebook    | [ac710043ec](https://linux-hardware.org/?probe=ac710043ec) | Jul 09, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | Notebook    | [07807f87ab](https://linux-hardware.org/?probe=07807f87ab) | Jul 04, 2024 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [70d021b045](https://linux-hardware.org/?probe=70d021b045) | Jul 02, 2024 |
| Supermicro    | X10DRH-CT                   | Desktop     | [dd4b138c6e](https://linux-hardware.org/?probe=dd4b138c6e) | Jun 27, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [cd307f9782](https://linux-hardware.org/?probe=cd307f9782) | Jun 27, 2024 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [5f79f30b85](https://linux-hardware.org/?probe=5f79f30b85) | Jun 19, 2024 |
| Dell          | Latitude 5520               | Notebook    | [c1a7e532c9](https://linux-hardware.org/?probe=c1a7e532c9) | Jun 10, 2024 |
| Dell          | Latitude 3340               | Notebook    | [0179e77195](https://linux-hardware.org/?probe=0179e77195) | Jun 10, 2024 |
| Dell          | Latitude 3340               | Notebook    | [3719b02ec1](https://linux-hardware.org/?probe=3719b02ec1) | Jun 10, 2024 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [a2f0057f55](https://linux-hardware.org/?probe=a2f0057f55) | Jun 05, 2024 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [75728b162c](https://linux-hardware.org/?probe=75728b162c) | Jun 04, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [5e9a78a9f5](https://linux-hardware.org/?probe=5e9a78a9f5) | Jun 04, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [564a4d2df9](https://linux-hardware.org/?probe=564a4d2df9) | May 27, 2024 |
| Dell          | 0RN4PJ A01                  | Server      | [d946f59098](https://linux-hardware.org/?probe=d946f59098) | May 27, 2024 |
| Dell          | 0MWYPT A01                  | Desktop     | [4e18ec8df0](https://linux-hardware.org/?probe=4e18ec8df0) | May 15, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [c5ad34b5f5](https://linux-hardware.org/?probe=c5ad34b5f5) | May 14, 2024 |
| Dell          | Precision 7540              | Notebook    | [4703617413](https://linux-hardware.org/?probe=4703617413) | May 07, 2024 |
| Dell          | Precision 7540              | Notebook    | [37638500df](https://linux-hardware.org/?probe=37638500df) | May 07, 2024 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [fba3144c06](https://linux-hardware.org/?probe=fba3144c06) | May 06, 2024 |
| MSI           | MEG Z790 ACE MAX            | Desktop     | [b10bbe2874](https://linux-hardware.org/?probe=b10bbe2874) | Apr 22, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [46e0a9d4d4](https://linux-hardware.org/?probe=46e0a9d4d4) | Apr 15, 2024 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [6ca85693a6](https://linux-hardware.org/?probe=6ca85693a6) | Apr 12, 2024 |
| ASUSTek       | G16CH                       | Desktop     | [04a245fffe](https://linux-hardware.org/?probe=04a245fffe) | Apr 11, 2024 |
| ASRock        | X570 Creator                | Desktop     | [53aae5d4cb](https://linux-hardware.org/?probe=53aae5d4cb) | Apr 07, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [c57b1d4302](https://linux-hardware.org/?probe=c57b1d4302) | Apr 04, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [0f04c10bfa](https://linux-hardware.org/?probe=0f04c10bfa) | Apr 02, 2024 |
| HP            | 212A                        | Desktop     | [4a6e30808e](https://linux-hardware.org/?probe=4a6e30808e) | Mar 12, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [23c12f49f6](https://linux-hardware.org/?probe=23c12f49f6) | Jan 27, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [6d4d5ee6c7](https://linux-hardware.org/?probe=6d4d5ee6c7) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | Notebook    | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | Notebook    | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Dell          | Precision M4800             | Notebook    | [dccdba8512](https://linux-hardware.org/?probe=dccdba8512) | Jan 21, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cb116dae9c](https://linux-hardware.org/?probe=cb116dae9c) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d4e6e0ae3e](https://linux-hardware.org/?probe=d4e6e0ae3e) | Jan 19, 2024 |
| MSI           | Katana GF76 12UC            | Notebook    | [73c3208c03](https://linux-hardware.org/?probe=73c3208c03) | Jan 10, 2024 |
| MSI           | Katana GF76 12UC            | Notebook    | [15db2ea112](https://linux-hardware.org/?probe=15db2ea112) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Dell          | Precision 3480              | Notebook    | [e81f3e856b](https://linux-hardware.org/?probe=e81f3e856b) | Jan 03, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [55f164e414](https://linux-hardware.org/?probe=55f164e414) | Dec 20, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b758a439b8](https://linux-hardware.org/?probe=b758a439b8) | Dec 20, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| Dell          | Precision 7530              | Notebook    | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | Notebook    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | Notebook    | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | Notebook    | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Intel         | NUC12WSBi7 M63355-302       | Mini pc     | [043bac31d2](https://linux-hardware.org/?probe=043bac31d2) | Sep 28, 2023 |
| Dell          | G16 7620                    | Notebook    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | Notebook    | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| Acer          | Aspire C24-865              | All in one  | [de824a4f4e](https://linux-hardware.org/?probe=de824a4f4e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | Notebook    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | Desktop     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Lenovo        | STA7B38870 02               | Server      | [80a2f3d367](https://linux-hardware.org/?probe=80a2f3d367) | Jun 18, 2023 |
| Dell          | 07T4MC A02                  | Desktop     | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Dell          | Latitude E7450              | Notebook    | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | 0RN4PJ A02                  | Server      | [84012f61ff](https://linux-hardware.org/?probe=84012f61ff) | Nov 03, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 9         | 5.92%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 5.92%   |
| 5.14.0-362.24.1.el9_3.x86_64 | 8         | 5.26%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 7         | 4.61%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 7         | 4.61%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 3.95%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 6         | 3.95%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 6         | 3.95%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 2.63%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 2.63%   |
| 5.14.0-503.26.1.el9_5.x86_64 | 4         | 2.63%   |
| 5.14.0-427.42.1.el9_4.x86_64 | 4         | 2.63%   |
| 5.14.0-427.22.1.el9_4.x86_64 | 4         | 2.63%   |
| 5.14.0-427.18.1.el9_4.x86_64 | 4         | 2.63%   |
| 5.14.0-427.13.1.el9_4.x86_64 | 4         | 2.63%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 4         | 2.63%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 4         | 2.63%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 3         | 1.97%   |
| 5.14.0-503.34.1.el9_5.x86_64 | 3         | 1.97%   |
| 5.14.0-427.37.1.el9_4.x86_64 | 3         | 1.97%   |
| 5.14.0-427.26.1.el9_4.x86_64 | 3         | 1.97%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 3         | 1.97%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 1.97%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 1.32%   |
| 5.14.0-503.31.1.el9_5.x86_64 | 2         | 1.32%   |
| 5.14.0-503.14.1.el9_5.x86_64 | 2         | 1.32%   |
| 5.14.0-427.35.1.el9_4.x86_64 | 2         | 1.32%   |
| 5.14.0-427.33.1.el9_4.x86_64 | 2         | 1.32%   |
| 5.14.0-427.20.1.el9_4.x86_64 | 2         | 1.32%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 2         | 1.32%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 1.32%   |
| 6.7.1-1.el9.elrepo.x86_64    | 1         | 0.66%   |
| 6.5.2-1.el9.elrepo.x86_64    | 1         | 0.66%   |
| 6.14.9-1.el9.elrepo.x86_64   | 1         | 0.66%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 0.66%   |
| 5.14.0-70.17.1.el9_0.aarch64 | 1         | 0.66%   |
| 5.14.0-611.13.1.el9_7.x86_64 | 1         | 0.66%   |
| 5.14.0-570.32.1.el9_6.x86_64 | 1         | 0.66%   |
| 5.14.0-570.26.1.el9_6.x86_64 | 1         | 0.66%   |
| 5.14.0-570.24.1.el9_6.x86_64 | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 139       | 97.89%  |
| 6.7.1   | 1         | 0.7%    |
| 6.5.2   | 1         | 0.7%    |
| 6.14.9  | 1         | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 139       | 97.89%  |
| 6.7     | 1         | 0.7%    |
| 6.5     | 1         | 0.7%    |
| 6.14    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 141       | 99.3%   |
| aarch64 | 1         | 0.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 124       | 85.52%  |
| KDE5            | 7         | 4.83%   |
| GNOME Classic   | 5         | 3.45%   |
| Unknown         | 3         | 2.07%   |
| XFCE            | 2         | 1.38%   |
| X-Cinnamon      | 1         | 0.69%   |
| MATE            | 1         | 0.69%   |
| GNOME Flashback | 1         | 0.69%   |
| Cinnamon        | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 105       | 72.92%  |
| X11     | 30        | 20.83%  |
| Tty     | 7         | 4.86%   |
| Unknown | 2         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 85        | 59.44%  |
| GDM     | 55        | 38.46%  |
| SDDM    | 3         | 2.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 95        | 66.9%   |
| en_GB   | 11        | 7.75%   |
| pt_BR   | 6         | 4.23%   |
| en_IN   | 4         | 2.82%   |
| pl_PL   | 2         | 1.41%   |
| en_NZ   | 2         | 1.41%   |
| en_CA   | 2         | 1.41%   |
| de_CH   | 2         | 1.41%   |
| cs_CZ   | 2         | 1.41%   |
| C       | 2         | 1.41%   |
| Unknown | 2         | 1.41%   |
| ru_RU   | 1         | 0.7%    |
| ro_RO   | 1         | 0.7%    |
| ko_KR   | 1         | 0.7%    |
| ja_JP   | 1         | 0.7%    |
| fr_FR   | 1         | 0.7%    |
| es_MX   | 1         | 0.7%    |
| es_ES   | 1         | 0.7%    |
| es_AR   | 1         | 0.7%    |
| en_ZA   | 1         | 0.7%    |
| en_IE   | 1         | 0.7%    |
| en_AU   | 1         | 0.7%    |
| de_DE   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 126       | 88.73%  |
| BIOS | 16        | 11.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Xfs   | 132       | 92.96%  |
| Ext4  | 9         | 6.34%   |
| Tmpfs | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 55.24%  |
| GPT     | 60        | 41.96%  |
| MBR     | 4         | 2.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 88.73%  |
| Yes       | 16        | 11.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 88.11%  |
| Yes       | 17        | 11.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 32        | 22.54%  |
| Lenovo                  | 28        | 19.72%  |
| Hewlett-Packard         | 17        | 11.97%  |
| ASUSTek Computer        | 16        | 11.27%  |
| MSI                     | 13        | 9.15%   |
| ASRock                  | 7         | 4.93%   |
| Gigabyte Technology     | 6         | 4.23%   |
| Unknown                 | 5         | 3.52%   |
| Intel                   | 4         | 2.82%   |
| Acer                    | 3         | 2.11%   |
| UNOWHY                  | 1         | 0.7%    |
| System76                | 1         | 0.7%    |
| Supermicro              | 1         | 0.7%    |
| Samsung Electronics     | 1         | 0.7%    |
| Razer                   | 1         | 0.7%    |
| Raspberry Pi Foundation | 1         | 0.7%    |
| Microsoft               | 1         | 0.7%    |
| MACHINIST               | 1         | 0.7%    |
| LG Electronics          | 1         | 0.7%    |
| Hardkernel              | 1         | 0.7%    |
| CX / Air Computers.     | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 5         | 3.52%   |
| Dell Precision 7920 Tower                    | 3         | 2.11%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS        | 2         | 1.41%   |
| Gigabyte B550M AORUS PRO-P                   | 2         | 1.41%   |
| Dell Precision Tower 5810                    | 2         | 1.41%   |
| Dell Precision M4800                         | 2         | 1.41%   |
| UNOWHY Y13G010S4EI                           | 1         | 0.7%    |
| System76 Galago Pro                          | 1         | 0.7%    |
| Supermicro SSG-6028R-E1CR12T                 | 1         | 0.7%    |
| Samsung 730QCJ/730QCR                        | 1         | 0.7%    |
| Razer Blade 15 Mid 2019-Base                 | 1         | 0.7%    |
| RPi Raspberry Pi 4 Model B                   | 1         | 0.7%    |
| MSI MS-7D86                                  | 1         | 0.7%    |
| MSI MS-7D54                                  | 1         | 0.7%    |
| MSI MS-7D52                                  | 1         | 0.7%    |
| MSI MS-7D25                                  | 1         | 0.7%    |
| MSI MS-7C95                                  | 1         | 0.7%    |
| MSI MS-7C56                                  | 1         | 0.7%    |
| MSI MS-7B89                                  | 1         | 0.7%    |
| MSI MS-7A71                                  | 1         | 0.7%    |
| MSI Modern 15 A5M                            | 1         | 0.7%    |
| MSI Katana GF76 12UC                         | 1         | 0.7%    |
| MSI Katana GF66 12UC                         | 1         | 0.7%    |
| MSI GP75 Leopard 9SD                         | 1         | 0.7%    |
| MSI GE72VR 7RF                               | 1         | 0.7%    |
| Microsoft Surface Go 2                       | 1         | 0.7%    |
| MACHINIST X99 PR9                            | 1         | 0.7%    |
| LG 15Z95P-GRLGL                              | 1         | 0.7%    |
| Lenovo ThinkSystem SR950 V3                  | 1         | 0.7%    |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US     | 1         | 0.7%    |
| Lenovo ThinkPad X1 Extreme Gen 5 21DFS08200  | 1         | 0.7%    |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5S08300 | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMS1V900  | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CCS4LT00  | 1         | 0.7%    |
| Lenovo ThinkPad T490 20N3S77601              | 1         | 0.7%    |
| Lenovo ThinkPad T460s 20FAS1NF00             | 1         | 0.7%    |
| Lenovo ThinkPad T16 Gen 1 21CH000JUS         | 1         | 0.7%    |
| Lenovo ThinkPad T14 Gen 4 21HES0VD0H         | 1         | 0.7%    |
| Lenovo ThinkPad S1 Yoga 12 20DK001YMC        | 1         | 0.7%    |
| Lenovo ThinkPad P16v Gen 2 21KYS0LG00        | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 19        | 13.38%  |
| Dell Precision               | 16        | 11.27%  |
| Dell Latitude                | 6         | 4.23%   |
| ASUS ROG                     | 6         | 4.23%   |
| HP EliteBook                 | 5         | 3.52%   |
| Dell Inspiron                | 5         | 3.52%   |
| Unknown                      | 5         | 3.52%   |
| Lenovo IdeaPad               | 4         | 2.82%   |
| Lenovo ThinkBook             | 3         | 2.11%   |
| ASUS TUF                     | 3         | 2.11%   |
| ASUS PRIME                   | 3         | 2.11%   |
| Acer Aspire                  | 3         | 2.11%   |
| MSI Katana                   | 2         | 1.41%   |
| HP ProBook                   | 2         | 1.41%   |
| HP Laptop                    | 2         | 1.41%   |
| Gigabyte B550M               | 2         | 1.41%   |
| ASRock X570                  | 2         | 1.41%   |
| UNOWHY Y13G010S4EI           | 1         | 0.7%    |
| System76 Galago              | 1         | 0.7%    |
| Supermicro SSG-6028R-E1CR12T | 1         | 0.7%    |
| Samsung 730QCJ               | 1         | 0.7%    |
| Razer Blade                  | 1         | 0.7%    |
| RPi Raspberry                | 1         | 0.7%    |
| MSI MS-7D86                  | 1         | 0.7%    |
| MSI MS-7D54                  | 1         | 0.7%    |
| MSI MS-7D52                  | 1         | 0.7%    |
| MSI MS-7D25                  | 1         | 0.7%    |
| MSI MS-7C95                  | 1         | 0.7%    |
| MSI MS-7C56                  | 1         | 0.7%    |
| MSI MS-7B89                  | 1         | 0.7%    |
| MSI MS-7A71                  | 1         | 0.7%    |
| MSI Modern                   | 1         | 0.7%    |
| MSI GP75                     | 1         | 0.7%    |
| MSI GE72VR                   | 1         | 0.7%    |
| Microsoft Surface            | 1         | 0.7%    |
| MACHINIST X99                | 1         | 0.7%    |
| LG 15Z95P-GRLGL              | 1         | 0.7%    |
| Lenovo ThinkSystem           | 1         | 0.7%    |
| Lenovo Legion                | 1         | 0.7%    |
| Intel NUC12WSHi7             | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 26        | 18.31%  |
| 2019 | 21        | 14.79%  |
| 2022 | 16        | 11.27%  |
| 2020 | 16        | 11.27%  |
| 2023 | 13        | 9.15%   |
| 2018 | 10        | 7.04%   |
| 2017 | 7         | 4.93%   |
| 2016 | 7         | 4.93%   |
| 2014 | 5         | 3.52%   |
| 2011 | 5         | 3.52%   |
| 2015 | 4         | 2.82%   |
| 2013 | 4         | 2.82%   |
| 2024 | 3         | 2.11%   |
| 2012 | 2         | 1.41%   |
| 2010 | 2         | 1.41%   |
| 2025 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 77        | 54.23%  |
| Desktop        | 48        | 33.8%   |
| Server         | 7         | 4.93%   |
| Convertible    | 4         | 2.82%   |
| Mini pc        | 3         | 2.11%   |
| System on chip | 1         | 0.7%    |
| Tablet         | 1         | 0.7%    |
| All in one     | 1         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 116       | 81.12%  |
| Enabled  | 27        | 18.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 99.3%   |
| Yes  | 1         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 47        | 33.1%   |
| 32.01-64.0      | 29        | 20.42%  |
| 4.01-8.0        | 23        | 16.2%   |
| 64.01-256.0     | 20        | 14.08%  |
| 3.01-4.0        | 8         | 5.63%   |
| More than 256.0 | 5         | 3.52%   |
| 24.01-32.0      | 5         | 3.52%   |
| 16.01-24.0      | 5         | 3.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 56        | 36.36%  |
| 2.01-3.0   | 43        | 27.92%  |
| 3.01-4.0   | 26        | 16.88%  |
| 8.01-16.0  | 19        | 12.34%  |
| 1.01-2.0   | 7         | 4.55%   |
| 32.01-64.0 | 1         | 0.65%   |
| 24.01-32.0 | 1         | 0.65%   |
| 16.01-24.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 47.62%  |
| 2      | 37        | 25.17%  |
| 3      | 20        | 13.61%  |
| 4      | 7         | 4.76%   |
| 5      | 6         | 4.08%   |
| 6      | 2         | 1.36%   |
| 15     | 1         | 0.68%   |
| 14     | 1         | 0.68%   |
| 10     | 1         | 0.68%   |
| 7      | 1         | 0.68%   |
| 0      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 82.39%  |
| Yes       | 25        | 17.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 84.51%  |
| No        | 22        | 15.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 75.17%  |
| No        | 36        | 24.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 70.07%  |
| No        | 44        | 29.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 48        | 33.8%   |
| India        | 12        | 8.45%   |
| Brazil       | 9         | 6.34%   |
| UK           | 7         | 4.93%   |
| Canada       | 6         | 4.23%   |
| Switzerland  | 4         | 2.82%   |
| Spain        | 4         | 2.82%   |
| Italy        | 3         | 2.11%   |
| Guatemala    | 3         | 2.11%   |
| Austria      | 3         | 2.11%   |
| Turkey       | 2         | 1.41%   |
| Sweden       | 2         | 1.41%   |
| South Korea  | 2         | 1.41%   |
| Russia       | 2         | 1.41%   |
| Romania      | 2         | 1.41%   |
| Poland       | 2         | 1.41%   |
| New Zealand  | 2         | 1.41%   |
| Mexico       | 2         | 1.41%   |
| Ireland      | 2         | 1.41%   |
| Germany      | 2         | 1.41%   |
| Czechia      | 2         | 1.41%   |
| Chile        | 2         | 1.41%   |
| Vietnam      | 1         | 0.7%    |
| Thailand     | 1         | 0.7%    |
| Sri Lanka    | 1         | 0.7%    |
| South Africa | 1         | 0.7%    |
| Slovakia     | 1         | 0.7%    |
| Saudi Arabia | 1         | 0.7%    |
| Saint Lucia  | 1         | 0.7%    |
| Pakistan     | 1         | 0.7%    |
| Norway       | 1         | 0.7%    |
| Netherlands  | 1         | 0.7%    |
| Kenya        | 1         | 0.7%    |
| Jordan       | 1         | 0.7%    |
| Japan        | 1         | 0.7%    |
| Indonesia    | 1         | 0.7%    |
| France       | 1         | 0.7%    |
| Finland      | 1         | 0.7%    |
| Egypt        | 1         | 0.7%    |
| Australia    | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Guatemala City        | 3         | 2.01%   |
| Wellington            | 2         | 1.34%   |
| Vienna                | 2         | 1.34%   |
| Sao Paulo             | 2         | 1.34%   |
| Santiago              | 2         | 1.34%   |
| Jaipur                | 2         | 1.34%   |
| Houston               | 2         | 1.34%   |
| Dublin                | 2         | 1.34%   |
| Denver                | 2         | 1.34%   |
| Brampton              | 2         | 1.34%   |
| Austin                | 2         | 1.34%   |
| Zlín                 | 1         | 0.67%   |
| Wildomar              | 1         | 0.67%   |
| Whiteley              | 1         | 0.67%   |
| Wake Forest           | 1         | 0.67%   |
| Villa María          | 1         | 0.67%   |
| Vancouver             | 1         | 0.67%   |
| Valencia              | 1         | 0.67%   |
| Valbrembo             | 1         | 0.67%   |
| Urbandale             | 1         | 0.67%   |
| Tokyo                 | 1         | 0.67%   |
| Thun                  | 1         | 0.67%   |
| Taunton               | 1         | 0.67%   |
| Sutton                | 1         | 0.67%   |
| Stratham              | 1         | 0.67%   |
| Stockholm             | 1         | 0.67%   |
| Sterling Heights      | 1         | 0.67%   |
| Stavropol             | 1         | 0.67%   |
| Spring Hill           | 1         | 0.67%   |
| Skien                 | 1         | 0.67%   |
| Sierra Vista          | 1         | 0.67%   |
| Seoul                 | 1         | 0.67%   |
| Sao Bernardo do Campo | 1         | 0.67%   |
| Sainte-Marie          | 1         | 0.67%   |
| Saint Paul            | 1         | 0.67%   |
| Sacramento            | 1         | 0.67%   |
| Roseville             | 1         | 0.67%   |
| Rosario               | 1         | 0.67%   |
| Riyadh                | 1         | 0.67%   |
| Rio de Janeiro        | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 48        | 65     | 19.51%  |
| Seagate                     | 24        | 59     | 9.76%   |
| WDC                         | 22        | 36     | 8.94%   |
| SanDisk                     | 20        | 28     | 8.13%   |
| Toshiba                     | 12        | 14     | 4.88%   |
| Unknown                     | 11        | 14     | 4.47%   |
| KIOXIA                      | 10        | 12     | 4.07%   |
| Kingston                    | 10        | 14     | 4.07%   |
| Micron/Crucial Technology   | 8         | 11     | 3.25%   |
| Micron Technology           | 8         | 8      | 3.25%   |
| SK hynix                    | 7         | 7      | 2.85%   |
| Intel                       | 7         | 14     | 2.85%   |
| HGST                        | 4         | 4      | 1.63%   |
| Phison Electronics          | 3         | 4      | 1.22%   |
| Phison                      | 3         | 3      | 1.22%   |
| MAXIO Technology (Hangzhou) | 3         | 4      | 1.22%   |
| Crucial                     | 3         | 4      | 1.22%   |
| China                       | 3         | 3      | 1.22%   |
| Silicon Motion              | 2         | 2      | 0.81%   |
| SABRENT                     | 2         | 2      | 0.81%   |
| Realtek                     | 2         | 2      | 0.81%   |
| PNY                         | 2         | 2      | 0.81%   |
| Kingston Technology Company | 2         | 2      | 0.81%   |
| KingSpec                    | 2         | 2      | 0.81%   |
| ADATA Technology            | 2         | 2      | 0.81%   |
| Unknown                     | 2         | 2      | 0.81%   |
| XUM                         | 1         | 1      | 0.41%   |
| WDC WDS                     | 1         | 1      | 0.41%   |
| Union Memory                | 1         | 1      | 0.41%   |
| SSSTC                       | 1         | 1      | 0.41%   |
| SPCC                        | 1         | 1      | 0.41%   |
| SCY                         | 1         | 1      | 0.41%   |
| Realtek Semiconductor       | 1         | 1      | 0.41%   |
| Plextor                     | 1         | 1      | 0.41%   |
| NVMe                        | 1         | 1      | 0.41%   |
| NEXDRIVE                    | 1         | 1      | 0.41%   |
| LITEON                      | 1         | 1      | 0.41%   |
| Lexar                       | 1         | 1      | 0.41%   |
| Kingmax                     | 1         | 1      | 0.41%   |
| KingFast                    | 1         | 2      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 10        | 3.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 8         | 2.85%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 4         | 1.42%   |
| Samsung SSD 980 1TB                                | 4         | 1.42%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 4         | 1.42%   |
| Unknown MMC Card  64GB                             | 3         | 1.07%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 3         | 1.07%   |
| Samsung SSD 870 EVO 1TB                            | 3         | 1.07%   |
| Phison E16 PCIe4 NVMe Controller 1TB               | 3         | 1.07%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 3         | 1.07%   |
| HGST HTS721010A9E630 1TB                           | 3         | 1.07%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 2         | 0.71%   |
| Unknown MMC Card  256GB                            | 2         | 0.71%   |
| Toshiba MQ01ABF050 500GB                           | 2         | 0.71%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 0.71%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2         | 0.71%   |
| Seagate BUP Slim BK 2TB                            | 2         | 0.71%   |
| Sandisk WD Blue SN570 500GB                        | 2         | 0.71%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB    | 2         | 0.71%   |
| Sandisk WD Black SN850 1TB                         | 2         | 0.71%   |
| Samsung SSD 990 PRO 2TB                            | 2         | 0.71%   |
| SABRENT Disk 4TB                                   | 2         | 0.71%   |
| Realtek RTL9210B-CG 500GB                          | 2         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 2         | 0.71%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 0.71%   |
| Kingston Company SNV2S250G 250GB                   | 2         | 0.71%   |
| Kingston SA400S37960G 960GB SSD                    | 2         | 0.71%   |
| Kingston SA400S37240G 240GB SSD                    | 2         | 0.71%   |
| Intel SSD 660P Series 512GB                        | 2         | 0.71%   |
| Unknown                                            | 2         | 0.71%   |
| XUM HX256GSSDSATA3 256GB                           | 1         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.36%   |
| WDC WDS 250G2B0A-00SM50 250GB SSD                  | 1         | 0.36%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1         | 0.36%   |
| WDC WD80EFAX-68KNBN0 8TB                           | 1         | 0.36%   |
| WDC WD5000AVDS-63U7B0 500GB                        | 1         | 0.36%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1         | 0.36%   |
| WDC WD5000AAKX-75U6AA0 500GB                       | 1         | 0.36%   |
| WDC WD50 00LPVX-22V0TT0 500GB                      | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 59     | 38.71%  |
| WDC                 | 19        | 32     | 30.65%  |
| Toshiba             | 11        | 12     | 17.74%  |
| HGST                | 4         | 4      | 6.45%   |
| Unknown             | 1         | 1      | 1.61%   |
| Samsung Electronics | 1         | 1      | 1.61%   |
| Hitachi             | 1         | 1      | 1.61%   |
| Fantom              | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 20     | 25%     |
| Kingston            | 7         | 11     | 11.67%  |
| WDC                 | 3         | 3      | 5%      |
| Intel               | 3         | 6      | 5%      |
| Crucial             | 3         | 3      | 5%      |
| China               | 3         | 3      | 5%      |
| SK hynix            | 2         | 2      | 3.33%   |
| SanDisk             | 2         | 2      | 3.33%   |
| SABRENT             | 2         | 2      | 3.33%   |
| PNY                 | 2         | 2      | 3.33%   |
| KingSpec            | 2         | 2      | 3.33%   |
| XUM                 | 1         | 1      | 1.67%   |
| WDC WDS             | 1         | 1      | 1.67%   |
| SPCC                | 1         | 1      | 1.67%   |
| Plextor             | 1         | 1      | 1.67%   |
| NVMe                | 1         | 1      | 1.67%   |
| NEXDRIVE            | 1         | 1      | 1.67%   |
| Micron Technology   | 1         | 1      | 1.67%   |
| LITEON              | 1         | 1      | 1.67%   |
| Lexar               | 1         | 1      | 1.67%   |
| Kingmax             | 1         | 1      | 1.67%   |
| Kimtigo             | 1         | 1      | 1.67%   |
| Inland              | 1         | 1      | 1.67%   |
| HUSKY               | 1         | 1      | 1.67%   |
| GOODRAM             | 1         | 1      | 1.67%   |
| Gigabyte Technology | 1         | 1      | 1.67%   |
| DERLAR              | 1         | 1      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 103       | 144    | 47.69%  |
| SSD     | 52        | 72     | 24.07%  |
| HDD     | 49        | 111    | 22.69%  |
| MMC     | 9         | 11     | 4.17%   |
| Unknown | 3         | 7      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 102       | 142    | 51.78%  |
| SATA | 72        | 171    | 36.55%  |
| SAS  | 14        | 21     | 7.11%   |
| MMC  | 9         | 11     | 4.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 60     | 37.39%  |
| 0.51-1.0   | 37        | 48     | 32.17%  |
| 1.01-2.0   | 12        | 18     | 10.43%  |
| 3.01-4.0   | 7         | 21     | 6.09%   |
| 4.01-10.0  | 7         | 22     | 6.09%   |
| 10.01-20.0 | 5         | 9      | 4.35%   |
| 2.01-3.0   | 4         | 5      | 3.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 26.03%  |
| 501-1000       | 31        | 21.23%  |
| 251-500        | 30        | 20.55%  |
| 1001-2000      | 19        | 13.01%  |
| More than 3000 | 11        | 7.53%   |
| 51-100         | 5         | 3.42%   |
| 21-50          | 4         | 2.74%   |
| 2001-3000      | 4         | 2.74%   |
| Unknown        | 3         | 2.05%   |
| 1-20           | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 31.13%  |
| 21-50          | 36        | 23.84%  |
| 51-100         | 20        | 13.25%  |
| 101-250        | 15        | 9.93%   |
| 251-500        | 13        | 8.61%   |
| 501-1000       | 7         | 4.64%   |
| 1001-2000      | 5         | 3.31%   |
| More than 3000 | 4         | 2.65%   |
| Unknown        | 3         | 1.99%   |
| 2001-3000      | 1         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB                       | 1         | 1      | 9.09%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 960GB | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 9.09%   |
| Seagate ST14000NM0018-2H4101 14TB                   | 1         | 1      | 9.09%   |
| Seagate ST12000VN0007-2GS116 12TB                   | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 9.09%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 9.09%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB      | 1         | 1      | 9.09%   |
| Intel SSDSC2BB480G7 480GB                           | 1         | 2      | 9.09%   |
| Intel SSDSC2BA800G4R 800GB                          | 1         | 2      | 9.09%   |
| Crucial CT1000BX500SSD1 1TB                         | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 5         | 5      | 45.45%  |
| Intel                     | 2         | 4      | 18.18%  |
| WDC                       | 1         | 1      | 9.09%   |
| Silicon Motion            | 1         | 1      | 9.09%   |
| Micron/Crucial Technology | 1         | 1      | 9.09%   |
| Crucial                   | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 50%     |
| SSD  | 3         | 5      | 30%     |
| NVMe | 2         | 2      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 91        | 205    | 57.23%  |
| Works    | 57        | 126    | 35.85%  |
| Malfunc  | 10        | 13     | 6.29%   |
| Failed   | 1         | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 89        | 39.21%  |
| Samsung Electronics              | 34        | 14.98%  |
| AMD                              | 20        | 8.81%   |
| SanDisk                          | 19        | 8.37%   |
| KIOXIA                           | 10        | 4.41%   |
| Micron/Crucial Technology        | 8         | 3.52%   |
| Micron Technology                | 7         | 3.08%   |
| Phison Electronics               | 6         | 2.64%   |
| ASMedia Technology               | 6         | 2.64%   |
| SK hynix                         | 5         | 2.2%    |
| Kingston Technology Company      | 5         | 2.2%    |
| Broadcom / LSI                   | 4         | 1.76%   |
| ADATA Technology                 | 3         | 1.32%   |
| Silicon Motion                   | 2         | 0.88%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.88%   |
| LSI Logic / Symbios Logic        | 2         | 0.88%   |
| Union Memory (Shenzhen)          | 1         | 0.44%   |
| Toshiba America Info Systems     | 1         | 0.44%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.44%   |
| Realtek Semiconductor            | 1         | 0.44%   |
| JMicron Technology               | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 4.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 4.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.94%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 3.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 2.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 2.76%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6         | 2.36%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 2.36%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 5         | 1.97%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 5         | 1.97%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.97%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 4         | 1.57%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 4         | 1.57%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.57%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 1.57%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.57%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 4         | 1.57%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 4         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.57%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 4         | 1.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.18%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.18%   |
| Intel SSD 660P Series                                                          | 3         | 1.18%   |
| Intel RST Volume Management Device Controller                                  | 3         | 1.18%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.18%   |
| Intel C620 Series Chipset Family IDE Redirection                               | 3         | 1.18%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3         | 1.18%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 1.18%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.18%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.18%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.79%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 99        | 44.59%  |
| SATA | 89        | 40.09%  |
| RAID | 28        | 12.61%  |
| IDE  | 3         | 1.35%   |
| SAS  | 2         | 0.9%    |
| SCSI | 1         | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 117       | 82.39%  |
| AMD    | 24        | 16.9%   |
| ARM    | 1         | 0.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 2.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 2.82%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4         | 2.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 2.11%   |
| Intel 12th Gen Core i7-12700H           | 3         | 2.11%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 2.11%   |
| Intel Xeon Gold 5122 CPU @ 3.60GHz      | 2         | 1.41%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 1.41%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 1.41%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 1.41%   |
| Intel Celeron N5105 @ 2.00GHz           | 2         | 1.41%   |
| Intel 12th Gen Core i9-12900K           | 2         | 1.41%   |
| Intel 12th Gen Core i7-1260P            | 2         | 1.41%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz | 2         | 1.41%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 1.41%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2         | 1.41%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.41%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 1.41%   |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 0.7%    |
| Intel Xeon Silver 4310 CPU @ 2.10GHz    | 1         | 0.7%    |
| Intel Xeon Platinum 8468H               | 1         | 0.7%    |
| Intel Xeon Platinum 8168 CPU @ 2.70GHz  | 1         | 0.7%    |
| Intel Xeon Gold 6138 CPU @ 2.00GHz      | 1         | 0.7%    |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1         | 0.7%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 1         | 0.7%    |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz      | 1         | 0.7%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 0.7%    |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz     | 1         | 0.7%    |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1         | 0.7%    |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz     | 1         | 0.7%    |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1         | 0.7%    |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1         | 0.7%    |
| Intel Pentium CPU 4425Y @ 1.70GHz       | 1         | 0.7%    |
| Intel N250                              | 1         | 0.7%    |
| Intel Core Ultra 9 185H                 | 1         | 0.7%    |
| Intel Core Ultra 7 265H                 | 1         | 0.7%    |
| Intel Core Ultra 7 165H                 | 1         | 0.7%    |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.7%    |
| Intel Core i9-14900KS                   | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 38        | 26.76%  |
| Intel Core i5          | 26        | 18.31%  |
| Intel Core i7          | 20        | 14.08%  |
| Intel Xeon             | 9         | 6.34%   |
| AMD Ryzen 9            | 8         | 5.63%   |
| AMD Ryzen 5            | 7         | 4.93%   |
| Intel Core i3          | 6         | 4.23%   |
| Intel Celeron          | 6         | 4.23%   |
| Intel Xeon Gold        | 3         | 2.11%   |
| Intel Core             | 3         | 2.11%   |
| AMD Ryzen 7            | 3         | 2.11%   |
| Intel Xeon Platinum    | 2         | 1.41%   |
| Intel Core i9          | 2         | 1.41%   |
| AMD Ryzen 7 PRO        | 2         | 1.41%   |
| Intel Xeon Silver      | 1         | 0.7%    |
| Intel Pentium Silver   | 1         | 0.7%    |
| Intel Pentium          | 1         | 0.7%    |
| AMD Ryzen Threadripper | 1         | 0.7%    |
| AMD Ryzen 3            | 1         | 0.7%    |
| AMD Athlon X4          | 1         | 0.7%    |
| AMD A4                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 48        | 33.8%   |
| 8      | 20        | 14.08%  |
| 2      | 20        | 14.08%  |
| 6      | 16        | 11.27%  |
| 12     | 13        | 9.15%   |
| 16     | 9         | 6.34%   |
| 10     | 6         | 4.23%   |
| 14     | 4         | 2.82%   |
| 24     | 2         | 1.41%   |
| 384    | 1         | 0.7%    |
| 48     | 1         | 0.7%    |
| 40     | 1         | 0.7%    |
| 1      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 135       | 95.07%  |
| 2      | 6         | 4.23%   |
| 8      | 1         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 118       | 83.1%   |
| 1      | 24        | 16.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 142       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 47.95%  |
| 0x806ec    | 6         | 4.11%   |
| 0x306a9    | 5         | 3.42%   |
| 0x906a3    | 4         | 2.74%   |
| 0x806d1    | 4         | 2.74%   |
| 0xa0671    | 3         | 2.05%   |
| 0x506e3    | 3         | 2.05%   |
| 0x08701021 | 3         | 2.05%   |
| 0x906ea    | 2         | 1.37%   |
| 0x906e9    | 2         | 1.37%   |
| 0x906c0    | 2         | 1.37%   |
| 0x90672    | 2         | 1.37%   |
| 0x806ea    | 2         | 1.37%   |
| 0x706e5    | 2         | 1.37%   |
| 0x406e3    | 2         | 1.37%   |
| 0x306c3    | 2         | 1.37%   |
| 0x0a50000f | 2         | 1.37%   |
| 0x0a20120a | 2         | 1.37%   |
| 0xb0671    | 1         | 0.68%   |
| 0x906ed    | 1         | 0.68%   |
| 0x906a4    | 1         | 0.68%   |
| 0x806f6    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x606a6    | 1         | 0.68%   |
| 0x50654    | 1         | 0.68%   |
| 0x406f1    | 1         | 0.68%   |
| 0x40651    | 1         | 0.68%   |
| 0x306d4    | 1         | 0.68%   |
| 0x20655    | 1         | 0.68%   |
| 0x106a5    | 1         | 0.68%   |
| 0x0a601206 | 1         | 0.68%   |
| 0x0a601203 | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x0a404102 | 1         | 0.68%   |
| 0x0a201204 | 1         | 0.68%   |
| 0x0a20102b | 1         | 0.68%   |
| 0x08701030 | 1         | 0.68%   |
| 0x08608103 | 1         | 0.68%   |
| 0x08600106 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 25        | 17.61%  |
| Alderlake Hybrid  | 21        | 14.79%  |
| Icelake           | 14        | 9.86%   |
| Skylake           | 11        | 7.75%   |
| Zen 3             | 9         | 6.34%   |
| TigerLake         | 7         | 4.93%   |
| IvyBridge         | 7         | 4.93%   |
| Haswell           | 7         | 4.93%   |
| Unknown           | 6         | 4.23%   |
| Zen 2             | 5         | 3.52%   |
| Broadwell         | 5         | 3.52%   |
| Tremont           | 4         | 2.82%   |
| Zen+              | 3         | 2.11%   |
| SandyBridge       | 3         | 2.11%   |
| Goldmont plus     | 3         | 2.11%   |
| Westmere          | 2         | 1.41%   |
| Meteorlake Hybrid | 2         | 1.41%   |
| Gracemont         | 2         | 1.41%   |
| Excavator         | 2         | 1.41%   |
| Zen               | 1         | 0.7%    |
| Sapphire Rapids   | 1         | 0.7%    |
| Nehalem           | 1         | 0.7%    |
| CometLake         | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 86        | 50.89%  |
| Nvidia                     | 51        | 30.18%  |
| AMD                        | 27        | 15.98%  |
| ASPEED Technology          | 3         | 1.78%   |
| Matrox Electronics Systems | 2         | 1.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 4.05%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 6         | 3.47%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 5         | 2.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 2.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 2.31%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 2.31%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 4         | 2.31%   |
| Intel JasperLake [UHD Graphics]                                           | 4         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.31%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 4         | 2.31%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 3         | 1.73%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 3         | 1.73%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.73%   |
| ASPEED Technology ASPEED Graphics Family                                  | 3         | 1.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.16%   |
| Nvidia TU117GL [T400 4GB / T400E]                                         | 2         | 1.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.16%   |
| Nvidia GP104GL [Quadro P4000]                                             | 2         | 1.16%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 2         | 1.16%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.16%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                        | 2         | 1.16%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 2         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.16%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 2         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.16%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 2         | 1.16%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 1.16%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                 | 2         | 1.16%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 1.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 1.16%   |
| AMD Raphael                                                               | 2         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 2         | 1.16%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 2         | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.16%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                        | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 61        | 42.66%  |
| 1 x Nvidia      | 32        | 22.38%  |
| 1 x AMD         | 18        | 12.59%  |
| Intel + Nvidia  | 17        | 11.89%  |
| Intel + AMD     | 5         | 3.5%    |
| 2 x AMD         | 2         | 1.4%    |
| 1 x Matrox      | 2         | 1.4%    |
| Other           | 1         | 0.7%    |
| 2 x Nvidia      | 1         | 0.7%    |
| Nvidia + ASPEED | 1         | 0.7%    |
| 1 x ASPEED      | 1         | 0.7%    |
| AMD + Nvidia    | 1         | 0.7%    |
| AMD + ASPEED    | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 119       | 83.8%   |
| Proprietary | 18        | 12.68%  |
| Unknown     | 5         | 3.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 55.94%  |
| 7.01-8.0   | 13        | 9.09%   |
| 3.01-4.0   | 11        | 7.69%   |
| 1.01-2.0   | 11        | 7.69%   |
| 5.01-6.0   | 6         | 4.2%    |
| 8.01-16.0  | 6         | 4.2%    |
| 0.51-1.0   | 6         | 4.2%    |
| 0.01-0.5   | 5         | 3.5%    |
| 16.01-24.0 | 4         | 2.8%    |
| 2.01-3.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 24        | 14.2%   |
| Samsung Electronics  | 18        | 10.65%  |
| Dell                 | 17        | 10.06%  |
| AU Optronics         | 15        | 8.88%   |
| LG Display           | 14        | 8.28%   |
| Chimei Innolux       | 10        | 5.92%   |
| Acer                 | 9         | 5.33%   |
| Goldstar             | 7         | 4.14%   |
| CSO                  | 5         | 2.96%   |
| Lenovo               | 4         | 2.37%   |
| Hewlett-Packard      | 4         | 2.37%   |
| Vizio                | 3         | 1.78%   |
| Unknown              | 3         | 1.78%   |
| Sharp                | 3         | 1.78%   |
| Philips              | 3         | 1.78%   |
| AOC                  | 3         | 1.78%   |
| ___                  | 2         | 1.18%   |
| Gigabyte Technology  | 2         | 1.18%   |
| BenQ                 | 2         | 1.18%   |
| Unknown              | 2         | 1.18%   |
| ViewSonic            | 1         | 0.59%   |
| Unknown (XXX)        | 1         | 0.59%   |
| STD                  | 1         | 0.59%   |
| Sony                 | 1         | 0.59%   |
| Sceptre Tech         | 1         | 0.59%   |
| PANDA                | 1         | 0.59%   |
| Panasonic            | 1         | 0.59%   |
| OUT                  | 1         | 0.59%   |
| KDB                  | 1         | 0.59%   |
| InfoVision           | 1         | 0.59%   |
| Iiyama               | 1         | 0.59%   |
| Haier                | 1         | 0.59%   |
| FL_                  | 1         | 0.59%   |
| Deco Gear            | 1         | 0.59%   |
| CTO                  | 1         | 0.59%   |
| CSW                  | 1         | 0.59%   |
| CEX                  | 1         | 0.59%   |
| BOE Technology Group | 1         | 0.59%   |
| ASUSTek Computer     | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 3         | 1.71%   |
| ___ LCD TV ___9000 1360x768                                             | 2         | 1.14%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                       | 2         | 1.14%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch             | 2         | 1.14%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                   | 2         | 1.14%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                      | 2         | 1.14%   |
| Unknown                                                                 | 2         | 1.14%   |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch              | 1         | 0.57%   |
| Unknown LCD Monitor SAMSUNG                                             | 1         | 0.57%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch          | 1         | 0.57%   |
| STD HDMI STD0110 1920x1080 520x310mm 23.8-inch                          | 1         | 0.57%   |
| Sony TV SNYD703 1360x768                                                | 1         | 0.57%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                 | 1         | 0.57%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                 | 1         | 0.57%   |
| Sharp LCD Monitor SHP13F9 3200x1800 350x190mm 15.7-inch                 | 1         | 0.57%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch          | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch    | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0380 1680x1050 459x296mm 21.5-inch    | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch    | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch    | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch    | 1         | 0.57%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch    | 1         | 0.57%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch       | 1         | 0.57%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1         | 0.57%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch       | 1         | 0.57%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch       | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 700x390mm 31.5-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM03D4 1280x720                        | 1         | 0.57%   |
| Samsung Electronics LCD Monitor S34J55x 7280x2160                       | 1         | 0.57%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                 | 1         | 0.57%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch                | 1         | 0.57%   |
| Philips PHL 272B7QPJ PHL0900 2560x1440 597x336mm 27.0-inch              | 1         | 0.57%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 45.81%  |
| 3840x2160 (4K)     | 15        | 9.68%   |
| 1366x768 (WXGA)    | 13        | 8.39%   |
| 2560x1440 (QHD)    | 12        | 7.74%   |
| 1920x1200 (WUXGA)  | 10        | 6.45%   |
| 2560x1600          | 5         | 3.23%   |
| 3440x1440          | 4         | 2.58%   |
| 1680x1050 (WSXGA+) | 3         | 1.94%   |
| 1360x768           | 3         | 1.94%   |
| 1280x1024 (SXGA)   | 3         | 1.94%   |
| Unknown            | 3         | 1.94%   |
| 3840x2400          | 2         | 1.29%   |
| 2560x1080          | 2         | 1.29%   |
| 1600x900 (HD+)     | 2         | 1.29%   |
| 7280x2160          | 1         | 0.65%   |
| 6400x2160          | 1         | 0.65%   |
| 5120x1440          | 1         | 0.65%   |
| 3200x1800 (QHD+)   | 1         | 0.65%   |
| 2160x1350          | 1         | 0.65%   |
| 1920x1280          | 1         | 0.65%   |
| 1280x768           | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 16.36%  |
| 13      | 19        | 11.52%  |
| 14      | 17        | 10.3%   |
| 27      | 14        | 8.48%   |
| 24      | 13        | 7.88%   |
| 23      | 11        | 6.67%   |
| Unknown | 9         | 5.45%   |
| 17      | 7         | 4.24%   |
| 16      | 7         | 4.24%   |
| 21      | 6         | 3.64%   |
| 72      | 4         | 2.42%   |
| 54      | 4         | 2.42%   |
| 34      | 4         | 2.42%   |
| 31      | 4         | 2.42%   |
| 84      | 3         | 1.82%   |
| 43      | 2         | 1.21%   |
| 35      | 2         | 1.21%   |
| 60      | 1         | 0.61%   |
| 52      | 1         | 0.61%   |
| 33      | 1         | 0.61%   |
| 29      | 1         | 0.61%   |
| 28      | 1         | 0.61%   |
| 26      | 1         | 0.61%   |
| 20      | 1         | 0.61%   |
| 19      | 1         | 0.61%   |
| 18      | 1         | 0.61%   |
| 12      | 1         | 0.61%   |
| 11      | 1         | 0.61%   |
| 10      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 40.12%  |
| 501-600     | 36        | 22.22%  |
| 201-300     | 10        | 6.17%   |
| Unknown     | 9         | 5.56%   |
| 401-500     | 8         | 4.94%   |
| 1501-2000   | 7         | 4.32%   |
| 601-700     | 6         | 3.7%    |
| 351-400     | 6         | 3.7%    |
| 1001-1500   | 6         | 3.7%    |
| 701-800     | 5         | 3.09%   |
| 801-900     | 2         | 1.23%   |
| 901-1000    | 2         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 72.86%  |
| 16/10   | 22        | 15.71%  |
| 21/9    | 6         | 4.29%   |
| Unknown | 5         | 3.57%   |
| 5/4     | 3         | 2.14%   |
| 4/3     | 1         | 0.71%   |
| 3/2     | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 29        | 17.68%  |
| 101-110        | 26        | 15.85%  |
| 201-250        | 24        | 14.63%  |
| 301-350        | 15        | 9.15%   |
| More than 1000 | 13        | 7.93%   |
| 351-500        | 13        | 7.93%   |
| Unknown        | 9         | 5.49%   |
| 71-80          | 7         | 4.27%   |
| 111-120        | 6         | 3.66%   |
| 251-300        | 5         | 3.05%   |
| 121-130        | 5         | 3.05%   |
| 141-150        | 3         | 1.83%   |
| 51-60          | 2         | 1.22%   |
| 151-200        | 2         | 1.22%   |
| 501-1000       | 2         | 1.22%   |
| 61-70          | 1         | 0.61%   |
| 131-140        | 1         | 0.61%   |
| 91-100         | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 45        | 28.3%   |
| 51-100        | 42        | 26.42%  |
| 101-120       | 30        | 18.87%  |
| 161-240       | 18        | 11.32%  |
| 1-50          | 9         | 5.66%   |
| Unknown       | 9         | 5.66%   |
| More than 240 | 6         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 104       | 70.75%  |
| 2     | 26        | 17.69%  |
| 0     | 8         | 5.44%   |
| 3     | 7         | 4.76%   |
| 5     | 1         | 0.68%   |
| 4     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 107       | 50.71%  |
| Realtek Semiconductor | 64        | 30.33%  |
| Qualcomm Atheros      | 10        | 4.74%   |
| Broadcom              | 6         | 2.84%   |
| MediaTek              | 2         | 0.95%   |
| HMD Global            | 2         | 0.95%   |
| Edimax Technology     | 2         | 0.95%   |
| DisplayLink           | 2         | 0.95%   |
| Aquantia              | 2         | 0.95%   |
| Teltonika Networks    | 1         | 0.47%   |
| Tehuti Networks       | 1         | 0.47%   |
| Sierra Wireless       | 1         | 0.47%   |
| Ralink Technology     | 1         | 0.47%   |
| Qualcomm              | 1         | 0.47%   |
| QinHeng Electronics   | 1         | 0.47%   |
| OPPO Electronics      | 1         | 0.47%   |
| Mellanox Technologies | 1         | 0.47%   |
| IBM                   | 1         | 0.47%   |
| Dell                  | 1         | 0.47%   |
| Broadcom Limited      | 1         | 0.47%   |
| ASUSTek Computer      | 1         | 0.47%   |
| ASIX Electronics      | 1         | 0.47%   |
| AMD                   | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30        | 10.87%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 3.99%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 3.62%   |
| Intel Ethernet Controller I225-V                                       | 10        | 3.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 3.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 2.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7         | 2.54%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.17%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 1.81%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.45%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.45%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 1.45%   |
| Intel Ethernet Connection (3) I219-LM                                  | 4         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.45%   |
| Intel Wireless 8260                                                    | 3         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.09%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 1.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2         | 0.72%   |
| Intel Wireless 7265                                                    | 2         | 0.72%   |
| Intel Wireless 7260                                                    | 2         | 0.72%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 2         | 0.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.72%   |
| Intel Jasper Lake PCH CNVi WiFi                                        | 2         | 0.72%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.72%   |
| Intel Ethernet Controller I225-LM                                      | 2         | 0.72%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 0.72%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.72%   |
| Intel Ethernet Connection (23) I219-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection (13) I219-LM                                 | 2         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 71.05%  |
| Realtek Semiconductor | 12        | 10.53%  |
| Qualcomm Atheros      | 8         | 7.02%   |
| Broadcom              | 4         | 3.51%   |
| MediaTek              | 2         | 1.75%   |
| Edimax Technology     | 2         | 1.75%   |
| Sierra Wireless       | 1         | 0.88%   |
| Ralink Technology     | 1         | 0.88%   |
| Qualcomm              | 1         | 0.88%   |
| Broadcom Limited      | 1         | 0.88%   |
| ASUSTek Computer      | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                             | 10        | 8.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 9         | 7.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 7         | 6.14%   |
| Intel Wi-Fi 6 AX201                                             | 6         | 5.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 5         | 4.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 4         | 3.51%   |
| Intel Wireless 8265 / 8275                                      | 4         | 3.51%   |
| Intel Raptor Lake PCH CNVi WiFi                                 | 4         | 3.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                | 4         | 3.51%   |
| Intel Wireless 8260                                             | 3         | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 3         | 2.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 2         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 2         | 1.75%   |
| Intel Wireless 7265                                             | 2         | 1.75%   |
| Intel Wireless 7260                                             | 2         | 1.75%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2 | 2         | 1.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2         | 1.75%   |
| Intel Jasper Lake PCH CNVi WiFi                                 | 2         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 2         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 2         | 1.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 2         | 1.75%   |
| Intel 700 Series Chipset CNVi WiFi                              | 2         | 1.75%   |
| Sierra Wireless EM7455                                          | 1         | 0.88%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller     | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                      | 1         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                      | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 1         | 0.88%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                      | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                    | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                 | 1         | 0.88%   |
| Qualcomm QCNFA765 Wireless Network Adapter                      | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1         | 0.88%   |
| Intel Wireless 3165                                             | 1         | 0.88%   |
| Intel Wireless 3160                                             | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 45.52%  |
| Realtek Semiconductor | 61        | 42.07%  |
| Broadcom              | 3         | 2.07%   |
| Qualcomm Atheros      | 2         | 1.38%   |
| HMD Global            | 2         | 1.38%   |
| DisplayLink           | 2         | 1.38%   |
| Aquantia              | 2         | 1.38%   |
| Teltonika Networks    | 1         | 0.69%   |
| Tehuti Networks       | 1         | 0.69%   |
| OPPO Electronics      | 1         | 0.69%   |
| Mellanox Technologies | 1         | 0.69%   |
| IBM                   | 1         | 0.69%   |
| Dell                  | 1         | 0.69%   |
| ASIX Electronics      | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 30        | 18.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 12        | 7.5%    |
| Realtek RTL8125 2.5GbE Controller                                              | 11        | 6.88%   |
| Intel Ethernet Controller I225-V                                               | 10        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 4.38%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 3.13%   |
| Intel I210 Gigabit Network Connection                                          | 5         | 3.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 5         | 3.13%   |
| Intel Ethernet Connection (3) I219-LM                                          | 4         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.5%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.88%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 1.88%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.88%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.88%   |
| Intel Ethernet Controller I226-V                                               | 2         | 1.25%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 1.25%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2         | 1.25%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.25%   |
| Intel Ethernet Connection (23) I219-LM                                         | 2         | 1.25%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 1.25%   |
| HMD Global Nokia7.2                                                            | 2         | 1.25%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 1.25%   |
| Teltonika Networks TRB16                                                       | 1         | 0.63%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter                     | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.63%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.63%   |
| OPPO Ace 3V                                                                    | 1         | 0.63%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1         | 0.63%   |
| Intel I350 Gigabit Network Connection                                          | 1         | 0.63%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 0.63%   |
| Intel Ethernet Controller X550                                                 | 1         | 0.63%   |
| Intel Ethernet Controller I226-LMvP                                            | 1         | 0.63%   |
| Intel Ethernet Controller (2) I225-LMvP                                        | 1         | 0.63%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 1         | 0.63%   |
| Intel Ethernet Connection X722                                                 | 1         | 0.63%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 52.16%  |
| WiFi     | 109       | 46.98%  |
| Modem    | 1         | 0.43%   |
| Unknown  | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 51.7%   |
| WiFi     | 71        | 48.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 55.94%  |
| 1     | 45        | 31.47%  |
| 3     | 9         | 6.29%   |
| 4     | 7         | 4.9%    |
| 5     | 1         | 0.7%    |
| 0     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 68.03%  |
| Yes  | 47        | 31.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 73.33%  |
| Realtek Semiconductor           | 7         | 6.67%   |
| Qualcomm Atheros Communications | 7         | 6.67%   |
| Broadcom                        | 4         | 3.81%   |
| MediaTek                        | 2         | 1.9%    |
| Cambridge Silicon Radio         | 2         | 1.9%    |
| USI                             | 1         | 0.95%   |
| Integrated System Solution      | 1         | 0.95%   |
| IMC Networks                    | 1         | 0.95%   |
| Foxconn / Hon Hai               | 1         | 0.95%   |
| Edimax Technology               | 1         | 0.95%   |
| ASUSTek Computer                | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                 | 19        | 18.1%   |
| Intel Bluetooth Device                                | 15        | 14.29%  |
| Intel AX200 Bluetooth                                 | 10        | 9.52%   |
| Intel AX210 Bluetooth                                 | 9         | 8.57%   |
| Intel Bluetooth wireless interface                    | 8         | 7.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 8         | 7.62%   |
| Intel Wireless-AC 3168 Bluetooth                      | 7         | 6.67%   |
| Realtek Bluetooth Radio                               | 6         | 5.71%   |
| Qualcomm Atheros  Bluetooth Device                    | 6         | 5.71%   |
| MediaTek Wireless_Device                              | 2         | 1.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 1.9%    |
| Broadcom HP Portable SoftSailing                      | 2         | 1.9%    |
| USI Bluetooth Device                                  | 1         | 0.95%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 0.95%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.95%   |
| IMC Networks Bluetooth Radio                          | 1         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1         | 0.95%   |
| Edimax Bluetooth Device                               | 1         | 0.95%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 1         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 0.95%   |
| ASUS ASUS USB-BT500                                   | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 112       | 49.56%  |
| Nvidia                                       | 45        | 19.91%  |
| AMD                                          | 30        | 13.27%  |
| Texas Instruments                            | 6         | 2.65%   |
| Realtek Semiconductor                        | 5         | 2.21%   |
| ASUSTek Computer                             | 3         | 1.33%   |
| Micro Star International                     | 2         | 0.88%   |
| Logitech                                     | 2         | 0.88%   |
| Lenovo                                       | 2         | 0.88%   |
| Creative Labs                                | 2         | 0.88%   |
| C-Media Electronics                          | 2         | 0.88%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.44%   |
| Valve Software                               | 1         | 0.44%   |
| Unknown                                      | 1         | 0.44%   |
| SteelSeries ApS                              | 1         | 0.44%   |
| Sony                                         | 1         | 0.44%   |
| Plantronics                                  | 1         | 0.44%   |
| Nordic Semiconductor ASA                     | 1         | 0.44%   |
| LG Electronics                               | 1         | 0.44%   |
| Hewlett-Packard                              | 1         | 0.44%   |
| Harman                                       | 1         | 0.44%   |
| Elgato Systems                               | 1         | 0.44%   |
| Corsair                                      | 1         | 0.44%   |
| Blue Microphones                             | 1         | 0.44%   |
| BEHRINGER International                      | 1         | 0.44%   |
| Astro Gaming                                 | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 3.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 3.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 3.95%   |
| AMD Ryzen HD Audio Controller                                              | 10        | 3.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 2.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 2.37%   |
| Texas Instruments PCM2902 Audio Codec                                      | 5         | 1.98%   |
| Realtek Semiconductor USB Audio                                            | 5         | 1.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.58%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 1.58%   |
| Intel Jasper Lake HD Audio                                                 | 4         | 1.58%   |
| Intel C62x HD Audio Controller                                             | 4         | 1.58%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 1.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.58%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 4         | 1.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.19%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.19%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.19%   |
| ASUSTek Computer USB Audio                                                 | 3         | 1.19%   |
| AMD Radeon High Definition Audio Controller                                | 3         | 1.19%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.19%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia AD102 High Definition Audio Controller                              | 2         | 0.79%   |
| Micro Star International USB Audio                                         | 2         | 0.79%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 2         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 22.06%  |
| Samsung Electronics | 13        | 19.12%  |
| Micron Technology   | 6         | 8.82%   |
| Kingston            | 6         | 8.82%   |
| G.Skill             | 6         | 8.82%   |
| Corsair             | 6         | 8.82%   |
| Crucial             | 5         | 7.35%   |
| Unknown             | 3         | 4.41%   |
| Team                | 2         | 2.94%   |
| Unknown             | 2         | 2.94%   |
| Smart               | 1         | 1.47%   |
| Nanya Technology    | 1         | 1.47%   |
| Hewlett-Packard     | 1         | 1.47%   |
| Elpida              | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3600C16-16GTZNC 16GiB DIMM DDR4 3600MT/s          | 2         | 2.74%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.74%   |
| Unknown                                                          | 2         | 2.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.37%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                        | 1         | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                        | 1         | 1.37%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s              | 1         | 1.37%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s            | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMCG94MEBRA123N 64GB DIMM DDR5 4800MT/s             | 1         | 1.37%   |
| SK hynix RAM HMCG94MEBRA121N 64GB DIMM DDR5 4800MT/s             | 1         | 1.37%   |
| SK hynix RAM HMCG94MEBRA109N 64GB DIMM DDR5 4800MT/s             | 1         | 1.37%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMAA8GL7MMR4N-UH 64GB DIMM DDR4 2400MT/s            | 1         | 1.37%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s            | 1         | 1.37%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.37%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB RIMM DDR4 2400MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA82GU7AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 1.37%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| SK hynix RAM H9CCNNNCPTALBR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.37%   |
| SK hynix RAM H5AN8G6NDJR-XNC 4GB Row Of Chips DDR4 2400MT/s      | 1         | 1.37%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.37%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s             | 1         | 1.37%   |
| Samsung RAM M393A1K43BB1-CTD 8GB DIMM DDR4 2667MT/s              | 1         | 1.37%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.37%   |
| Samsung RAM M386A8K40BMB-CRC 64GB DIMM DDR4 2400MT/s             | 1         | 1.37%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s              | 1         | 1.37%   |
| Samsung RAM K3LKBKB0BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 41        | 68.33%  |
| DDR3   | 7         | 11.67%  |
| DDR5   | 5         | 8.33%   |
| LPDDR5 | 4         | 6.67%   |
| LPDDR4 | 2         | 3.33%   |
| LPDDR3 | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| DIMM            | 27        | 44.26%  |
| SODIMM          | 24        | 39.34%  |
| Row Of Chips    | 6         | 9.84%   |
| Chip            | 2         | 3.28%   |
| RIMM            | 1         | 1.64%   |
| Proprietary Car | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 39.68%  |
| 16384 | 18        | 28.57%  |
| 32768 | 7         | 11.11%  |
| 4096  | 7         | 11.11%  |
| 65536 | 3         | 4.76%   |
| 2048  | 2         | 3.17%   |
| 49152 | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 10        | 15.87%  |
| 2667    | 10        | 15.87%  |
| 2400    | 10        | 15.87%  |
| 3600    | 5         | 7.94%   |
| 1600    | 5         | 7.94%   |
| 6400    | 4         | 6.35%   |
| 2133    | 4         | 6.35%   |
| 5600    | 2         | 3.17%   |
| 3866    | 2         | 3.17%   |
| 2933    | 2         | 3.17%   |
| 1867    | 2         | 3.17%   |
| 7500    | 1         | 1.59%   |
| 7467    | 1         | 1.59%   |
| 4800    | 1         | 1.59%   |
| 4000    | 1         | 1.59%   |
| 2666    | 1         | 1.59%   |
| 1333    | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 50%     |
| Kyocera         | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |
| Canon           | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series       | 1         | 16.67%  |
| Seiko Epson L3210 Series         | 1         | 16.67%  |
| Seiko Epson EPSON WF-3520 Series | 1         | 16.67%  |
| Kyocera FS-1030D printer         | 1         | 16.67%  |
| HP DeskJet 3700 series           | 1         | 16.67%  |
| Canon PIXMA MG2500 Series        | 1         | 16.67%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 18.95%  |
| Microdia                               | 10        | 10.53%  |
| Sunplus Innovation Technology          | 9         | 9.47%   |
| IMC Networks                           | 8         | 8.42%   |
| Bison Electronics                      | 7         | 7.37%   |
| Realtek Semiconductor                  | 5         | 5.26%   |
| Logitech                               | 5         | 5.26%   |
| Luxvisions Innotech Limited            | 4         | 4.21%   |
| Syntek                                 | 3         | 3.16%   |
| Samsung Electronics                    | 3         | 3.16%   |
| Lite-On Technology                     | 3         | 3.16%   |
| Generalplus Technology                 | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.11%   |
| Apple                                  | 2         | 2.11%   |
| vivo                                   | 1         | 1.05%   |
| Valve Software                         | 1         | 1.05%   |
| Suyin                                  | 1         | 1.05%   |
| Sonix Technology                       | 1         | 1.05%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.05%   |
| Remo Tech                              | 1         | 1.05%   |
| Quanta                                 | 1         | 1.05%   |
| Owon                                   | 1         | 1.05%   |
| Microsoft                              | 1         | 1.05%   |
| LG Electronics                         | 1         | 1.05%   |
| icSpring                               | 1         | 1.05%   |
| Hewlett-Packard                        | 1         | 1.05%   |
| Alcor Micro                            | 1         | 1.05%   |
| Acer                                   | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                          | 5         | 5.26%   |
| Microdia Integrated_Webcam_HD                         | 5         | 5.26%   |
| Chicony Integrated Camera                             | 5         | 5.26%   |
| IMC Networks Integrated Camera                        | 4         | 4.21%   |
| Syntek Integrated Camera                              | 3         | 3.16%   |
| Samsung Galaxy series, misc. (MTP mode)               | 3         | 3.16%   |
| Sunplus Integrated Camera                             | 2         | 2.11%   |
| Realtek Integrated_Webcam_HD                          | 2         | 2.11%   |
| Luxvisions Innotech Limited Integrated Camera         | 2         | 2.11%   |
| Lite-On Integrated Camera                             | 2         | 2.11%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 2         | 2.11%   |
| Chicony Integrated HP HD Webcam                       | 2         | 2.11%   |
| Chicony HP HD Camera                                  | 2         | 2.11%   |
| Bison Integrated Camera                               | 2         | 2.11%   |
| Bison HD Webcam                                       | 2         | 2.11%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 2         | 2.11%   |
| vivo V2514                                            | 1         | 1.05%   |
| Valve Software 3D Camera                              | 1         | 1.05%   |
| Suyin Integrated_Webcam_HD                            | 1         | 1.05%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.05%   |
| Sunplus Hy FHD B200 Came                              | 1         | 1.05%   |
| Sonix USB2.0 HD UVC WebCam                            | 1         | 1.05%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera       | 1         | 1.05%   |
| Remo Tech OBSBOT Tiny 4K                              | 1         | 1.05%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 1.05%   |
| Realtek Integrated Webcam_HD                          | 1         | 1.05%   |
| Realtek FULL HD 1080P Webcam                          | 1         | 1.05%   |
| Quanta HP TrueVision HD Camera                        | 1         | 1.05%   |
| Owon USB CAMERA                                       | 1         | 1.05%   |
| Microsoft LifeCam VX-2000                             | 1         | 1.05%   |
| Microdia USB 2.0 Camera                               | 1         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_0.3M                | 1         | 1.05%   |
| Microdia Integrated_Webcam_FHD                        | 1         | 1.05%   |
| Microdia Integrated Webcam                            | 1         | 1.05%   |
| Microdia 1.3 MPixel Integrated Webcam                 | 1         | 1.05%   |
| Luxvisions Innotech Limited Integrated RGB Camera     | 1         | 1.05%   |
| Luxvisions Innotech Limited HP True Vision FHD Camera | 1         | 1.05%   |
| Logitech Webcam C310                                  | 1         | 1.05%   |
| Logitech Webcam C250                                  | 1         | 1.05%   |
| Logitech HD Webcam C615                               | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 57.14%  |
| Validity Sensors           | 4         | 19.05%  |
| Shenzhen Goodix Technology | 3         | 14.29%  |
| Samsung Electronics        | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 5         | 23.81%  |
| Synaptics UWP WBDI Device                                 | 4         | 19.05%  |
| Validity Sensors VFS491                                   | 2         | 9.52%   |
| Synaptics Prometheus Fingerprint Reader                   | 2         | 9.52%   |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 9.52%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 4.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 4.76%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 4.76%   |
| Elan ELAN:ARM-M4                                          | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 13        | 76.47%  |
| Alcor Micro         | 3         | 17.65%  |
| Giesecke & Devrient | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 29.41%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 17.65%  |
| Broadcom 58200                                                               | 3         | 17.65%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 17.65%  |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.88%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 87        | 60.42%  |
| 1     | 38        | 26.39%  |
| 2     | 13        | 9.03%   |
| 3     | 4         | 2.78%   |
| 5     | 1         | 0.69%   |
| 4     | 1         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 26.25%  |
| Graphics card            | 10        | 12.5%   |
| Net/wireless             | 9         | 11.25%  |
| Chipcard                 | 9         | 11.25%  |
| Unassigned class         | 8         | 10%     |
| Multimedia controller    | 5         | 6.25%   |
| Communication controller | 4         | 5%      |
| Net/ethernet             | 3         | 3.75%   |
| Storage/ide              | 2         | 2.5%    |
| Firewire controller      | 2         | 2.5%    |
| Camera                   | 2         | 2.5%    |
| Bluetooth                | 2         | 2.5%    |
| Storage                  | 1         | 1.25%   |
| Sound                    | 1         | 1.25%   |
| Card reader              | 1         | 1.25%   |

