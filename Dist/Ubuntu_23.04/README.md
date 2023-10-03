Ubuntu 23.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_23.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_23.04/Notebook/README.md).

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

Total: 1851

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | G73Jh                       | Notebook    | [0b9b84be03](https://linux-hardware.org/?probe=0b9b84be03) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| NZXT          | N7 B550                     | Desktop     | [53a99b69e6](https://linux-hardware.org/?probe=53a99b69e6) | Sep 30, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [da117a4e6a](https://linux-hardware.org/?probe=da117a4e6a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [d39169bf21](https://linux-hardware.org/?probe=d39169bf21) | Sep 30, 2023 |
| ASUSTek       | CG8480                      | Desktop     | [dc174e8f73](https://linux-hardware.org/?probe=dc174e8f73) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | Desktop     | [68f162bf42](https://linux-hardware.org/?probe=68f162bf42) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b3617a1e58](https://linux-hardware.org/?probe=b3617a1e58) | Sep 30, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [7b4a0099a9](https://linux-hardware.org/?probe=7b4a0099a9) | Sep 29, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [55ea55a771](https://linux-hardware.org/?probe=55ea55a771) | Sep 29, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [3e1448c388](https://linux-hardware.org/?probe=3e1448c388) | Sep 29, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [fc5d6092da](https://linux-hardware.org/?probe=fc5d6092da) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0c29af254c](https://linux-hardware.org/?probe=0c29af254c) | Sep 29, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [26580dc672](https://linux-hardware.org/?probe=26580dc672) | Sep 29, 2023 |
| HP            | 8923 00100                  | All in one  | [31d524cec8](https://linux-hardware.org/?probe=31d524cec8) | Sep 28, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [0005d20c0d](https://linux-hardware.org/?probe=0005d20c0d) | Sep 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [27d7959e57](https://linux-hardware.org/?probe=27d7959e57) | Sep 28, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [6def421696](https://linux-hardware.org/?probe=6def421696) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [f436f21240](https://linux-hardware.org/?probe=f436f21240) | Sep 27, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [6eefb5fdd2](https://linux-hardware.org/?probe=6eefb5fdd2) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [50c8df3b79](https://linux-hardware.org/?probe=50c8df3b79) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [6cfd6e2b34](https://linux-hardware.org/?probe=6cfd6e2b34) | Sep 27, 2023 |
| HP            | 8594                        | Desktop     | [374067df48](https://linux-hardware.org/?probe=374067df48) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | Desktop     | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [af863ee3d6](https://linux-hardware.org/?probe=af863ee3d6) | Sep 27, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [919b208284](https://linux-hardware.org/?probe=919b208284) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [812b06784e](https://linux-hardware.org/?probe=812b06784e) | Sep 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ded4cabd95](https://linux-hardware.org/?probe=ded4cabd95) | Sep 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [ab5af00a13](https://linux-hardware.org/?probe=ab5af00a13) | Sep 26, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [45b934b885](https://linux-hardware.org/?probe=45b934b885) | Sep 26, 2023 |
| Infinix       | INBOOK Y1 PLUS NEO          | Notebook    | [30998449af](https://linux-hardware.org/?probe=30998449af) | Sep 26, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b5951d8a34](https://linux-hardware.org/?probe=b5951d8a34) | Sep 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ee86e0d81e](https://linux-hardware.org/?probe=ee86e0d81e) | Sep 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [1630b56fe3](https://linux-hardware.org/?probe=1630b56fe3) | Sep 26, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [fc79d63b87](https://linux-hardware.org/?probe=fc79d63b87) | Sep 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf4e6d50dd](https://linux-hardware.org/?probe=cf4e6d50dd) | Sep 26, 2023 |
| HP            | G62                         | Notebook    | [50fef7b3fa](https://linux-hardware.org/?probe=50fef7b3fa) | Sep 26, 2023 |
| AZW           | GTR V01                     | Mini pc     | [07e408ce48](https://linux-hardware.org/?probe=07e408ce48) | Sep 25, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3e5c047af](https://linux-hardware.org/?probe=f3e5c047af) | Sep 25, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [285eb8a521](https://linux-hardware.org/?probe=285eb8a521) | Sep 25, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [ec5aecc69d](https://linux-hardware.org/?probe=ec5aecc69d) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| ASUSTek       | M51AC                       | Desktop     | [b4bd7fad24](https://linux-hardware.org/?probe=b4bd7fad24) | Sep 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [8895bccd1c](https://linux-hardware.org/?probe=8895bccd1c) | Sep 25, 2023 |
| Infinix       | INBOOK X1 SLIM              | Notebook    | [bd6f358c7f](https://linux-hardware.org/?probe=bd6f358c7f) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [38b5be59cc](https://linux-hardware.org/?probe=38b5be59cc) | Sep 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [2e717c304e](https://linux-hardware.org/?probe=2e717c304e) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | Notebook    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| HP            | 3047h                       | Desktop     | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [25c109d366](https://linux-hardware.org/?probe=25c109d366) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| Acer          | Aspire 5520                 | Notebook    | [5bcc67211c](https://linux-hardware.org/?probe=5bcc67211c) | Sep 24, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [8a1af94640](https://linux-hardware.org/?probe=8a1af94640) | Sep 24, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [8d87ce31c5](https://linux-hardware.org/?probe=8d87ce31c5) | Sep 24, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [10dfbbd349](https://linux-hardware.org/?probe=10dfbbd349) | Sep 24, 2023 |
| HP            | EliteBook 6930p (KK082AV... | Notebook    | [5e61b319b6](https://linux-hardware.org/?probe=5e61b319b6) | Sep 23, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6ba017a802](https://linux-hardware.org/?probe=6ba017a802) | Sep 23, 2023 |
| Lenovo        | ThinkPad W550s 20E1S0VW0... | Notebook    | [e5c12ca1ce](https://linux-hardware.org/?probe=e5c12ca1ce) | Sep 23, 2023 |
| Dell          | Latitude 9430               | Convertible | [d9199fcb7a](https://linux-hardware.org/?probe=d9199fcb7a) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [da277c4d5a](https://linux-hardware.org/?probe=da277c4d5a) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [3b18f2e874](https://linux-hardware.org/?probe=3b18f2e874) | Sep 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [45c1c156af](https://linux-hardware.org/?probe=45c1c156af) | Sep 23, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [9b814d0254](https://linux-hardware.org/?probe=9b814d0254) | Sep 23, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | Desktop     | [41ac03cc3a](https://linux-hardware.org/?probe=41ac03cc3a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [898219c64a](https://linux-hardware.org/?probe=898219c64a) | Sep 23, 2023 |
| Google        | Asuka                       | Notebook    | [cf59aebc4c](https://linux-hardware.org/?probe=cf59aebc4c) | Sep 23, 2023 |
| Panasonic     | CF-31JHG8M1M                | Notebook    | [3dc21238c6](https://linux-hardware.org/?probe=3dc21238c6) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2a0c1d15f9](https://linux-hardware.org/?probe=2a0c1d15f9) | Sep 23, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [c601e6192f](https://linux-hardware.org/?probe=c601e6192f) | Sep 23, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [3580b7d8d6](https://linux-hardware.org/?probe=3580b7d8d6) | Sep 22, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [ce054bb837](https://linux-hardware.org/?probe=ce054bb837) | Sep 22, 2023 |
| Acer          | Aspire 5520                 | Notebook    | [8329086779](https://linux-hardware.org/?probe=8329086779) | Sep 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3bb5a0e5a0](https://linux-hardware.org/?probe=3bb5a0e5a0) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [adf0d97721](https://linux-hardware.org/?probe=adf0d97721) | Sep 22, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [be07169f5c](https://linux-hardware.org/?probe=be07169f5c) | Sep 22, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [9fbc54dcb7](https://linux-hardware.org/?probe=9fbc54dcb7) | Sep 22, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [a8c067b868](https://linux-hardware.org/?probe=a8c067b868) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [01f346ff26](https://linux-hardware.org/?probe=01f346ff26) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ba1ec3eb6d](https://linux-hardware.org/?probe=ba1ec3eb6d) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a204305d1e](https://linux-hardware.org/?probe=a204305d1e) | Sep 22, 2023 |
| AZW           | GTR V21                     | Desktop     | [c3da1f2fd5](https://linux-hardware.org/?probe=c3da1f2fd5) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [d43d654621](https://linux-hardware.org/?probe=d43d654621) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [290e0fd96b](https://linux-hardware.org/?probe=290e0fd96b) | Sep 21, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9d97540a6e](https://linux-hardware.org/?probe=9d97540a6e) | Sep 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [966f802eb6](https://linux-hardware.org/?probe=966f802eb6) | Sep 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [c933105cd8](https://linux-hardware.org/?probe=c933105cd8) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [dd328a6f1f](https://linux-hardware.org/?probe=dd328a6f1f) | Sep 21, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [895d259026](https://linux-hardware.org/?probe=895d259026) | Sep 21, 2023 |
| Dell          | Precision 5550              | Notebook    | [c5183a7443](https://linux-hardware.org/?probe=c5183a7443) | Sep 21, 2023 |
| Dell          | Precision 5550              | Notebook    | [3d927d3dee](https://linux-hardware.org/?probe=3d927d3dee) | Sep 21, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [bd096f1ae3](https://linux-hardware.org/?probe=bd096f1ae3) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e04968b0ab](https://linux-hardware.org/?probe=e04968b0ab) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f65b051dc9](https://linux-hardware.org/?probe=f65b051dc9) | Sep 20, 2023 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [f8f954cde7](https://linux-hardware.org/?probe=f8f954cde7) | Sep 20, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d630bfea5b](https://linux-hardware.org/?probe=d630bfea5b) | Sep 20, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [4dd816ef81](https://linux-hardware.org/?probe=4dd816ef81) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0c71c0240e](https://linux-hardware.org/?probe=0c71c0240e) | Sep 20, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [2d3de22b4b](https://linux-hardware.org/?probe=2d3de22b4b) | Sep 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [32cf98639a](https://linux-hardware.org/?probe=32cf98639a) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [43f5468ce8](https://linux-hardware.org/?probe=43f5468ce8) | Sep 19, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [139fc573bf](https://linux-hardware.org/?probe=139fc573bf) | Sep 19, 2023 |
| Supermicro    | X11DPi-N 123456789          | Server      | [ab60e84146](https://linux-hardware.org/?probe=ab60e84146) | Sep 19, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f832424d90](https://linux-hardware.org/?probe=f832424d90) | Sep 19, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [d8166ef941](https://linux-hardware.org/?probe=d8166ef941) | Sep 19, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [7abea387dc](https://linux-hardware.org/?probe=7abea387dc) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [5f584efb57](https://linux-hardware.org/?probe=5f584efb57) | Sep 19, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dfeb3f7ff](https://linux-hardware.org/?probe=7dfeb3f7ff) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [acd1c47b9d](https://linux-hardware.org/?probe=acd1c47b9d) | Sep 19, 2023 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [35cbc95f9e](https://linux-hardware.org/?probe=35cbc95f9e) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [bb285c7da5](https://linux-hardware.org/?probe=bb285c7da5) | Sep 18, 2023 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [bc9d2f6691](https://linux-hardware.org/?probe=bc9d2f6691) | Sep 18, 2023 |
| KUU           | Andes II                    | Notebook    | [a104ad8142](https://linux-hardware.org/?probe=a104ad8142) | Sep 18, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [f9c346c325](https://linux-hardware.org/?probe=f9c346c325) | Sep 18, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f32398315](https://linux-hardware.org/?probe=8f32398315) | Sep 18, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [11d6fae345](https://linux-hardware.org/?probe=11d6fae345) | Sep 18, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [0578825483](https://linux-hardware.org/?probe=0578825483) | Sep 18, 2023 |
| ASUSTek       | X450CA                      | Notebook    | [b43a3aa61c](https://linux-hardware.org/?probe=b43a3aa61c) | Sep 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [60e5e9a3db](https://linux-hardware.org/?probe=60e5e9a3db) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [c323f31788](https://linux-hardware.org/?probe=c323f31788) | Sep 17, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [13f3de6336](https://linux-hardware.org/?probe=13f3de6336) | Sep 17, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [1e61961aef](https://linux-hardware.org/?probe=1e61961aef) | Sep 17, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [77c0a6ded9](https://linux-hardware.org/?probe=77c0a6ded9) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [88a398f990](https://linux-hardware.org/?probe=88a398f990) | Sep 17, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cdfa321c48](https://linux-hardware.org/?probe=cdfa321c48) | Sep 17, 2023 |
| HP            | 86C6 0010                   | All in one  | [1a9df16f39](https://linux-hardware.org/?probe=1a9df16f39) | Sep 16, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [9720b79b9d](https://linux-hardware.org/?probe=9720b79b9d) | Sep 16, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1212656ddf](https://linux-hardware.org/?probe=1212656ddf) | Sep 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [0c7cb04f38](https://linux-hardware.org/?probe=0c7cb04f38) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [c47a157971](https://linux-hardware.org/?probe=c47a157971) | Sep 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [10e74a88da](https://linux-hardware.org/?probe=10e74a88da) | Sep 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bdfc48de30](https://linux-hardware.org/?probe=bdfc48de30) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [3e8e61353c](https://linux-hardware.org/?probe=3e8e61353c) | Sep 15, 2023 |
| HP            | 829A                        | Mini pc     | [d42ad3bd44](https://linux-hardware.org/?probe=d42ad3bd44) | Sep 15, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [601a3eed6e](https://linux-hardware.org/?probe=601a3eed6e) | Sep 15, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [d1ef9fa580](https://linux-hardware.org/?probe=d1ef9fa580) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [27d7589428](https://linux-hardware.org/?probe=27d7589428) | Sep 15, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [35d0557ca0](https://linux-hardware.org/?probe=35d0557ca0) | Sep 14, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [ca5dd06f20](https://linux-hardware.org/?probe=ca5dd06f20) | Sep 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3b71101d09](https://linux-hardware.org/?probe=3b71101d09) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [6d61c93aef](https://linux-hardware.org/?probe=6d61c93aef) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [dc3d71404d](https://linux-hardware.org/?probe=dc3d71404d) | Sep 14, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [e7463cdeb1](https://linux-hardware.org/?probe=e7463cdeb1) | Sep 14, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [0a5342952c](https://linux-hardware.org/?probe=0a5342952c) | Sep 14, 2023 |
| Lenovo        | ThinkPad T570 20H90011ZA    | Notebook    | [f59a257ab5](https://linux-hardware.org/?probe=f59a257ab5) | Sep 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a9cdcdc284](https://linux-hardware.org/?probe=a9cdcdc284) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [14874e9d32](https://linux-hardware.org/?probe=14874e9d32) | Sep 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3c09b49188](https://linux-hardware.org/?probe=3c09b49188) | Sep 14, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [4f9a4f7031](https://linux-hardware.org/?probe=4f9a4f7031) | Sep 14, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [7056e15dc2](https://linux-hardware.org/?probe=7056e15dc2) | Sep 14, 2023 |
| KUU           | Andes II                    | Notebook    | [6270750e1e](https://linux-hardware.org/?probe=6270750e1e) | Sep 14, 2023 |
| Notebook      | NJ5x_NJ7xLU                 | Notebook    | [7ee403f2a2](https://linux-hardware.org/?probe=7ee403f2a2) | Sep 13, 2023 |
| Lenovo        | ThinkPad E14 20RA005MMX     | Notebook    | [d9d0c012b3](https://linux-hardware.org/?probe=d9d0c012b3) | Sep 13, 2023 |
| ASRock        | H97 Anniversary             | Desktop     | [37014ea895](https://linux-hardware.org/?probe=37014ea895) | Sep 13, 2023 |
| Intel         | X99H                        | Desktop     | [e38e67a30c](https://linux-hardware.org/?probe=e38e67a30c) | Sep 13, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [6bc54e3a67](https://linux-hardware.org/?probe=6bc54e3a67) | Sep 13, 2023 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [ca3874e5b8](https://linux-hardware.org/?probe=ca3874e5b8) | Sep 13, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [138dfabe47](https://linux-hardware.org/?probe=138dfabe47) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [380736a3f4](https://linux-hardware.org/?probe=380736a3f4) | Sep 13, 2023 |
| AZW           | SER V01                     | Mini pc     | [bbbc14d0c3](https://linux-hardware.org/?probe=bbbc14d0c3) | Sep 13, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [79a3f818f2](https://linux-hardware.org/?probe=79a3f818f2) | Sep 12, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [4318e0630c](https://linux-hardware.org/?probe=4318e0630c) | Sep 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | Notebook    | [2f123cee8b](https://linux-hardware.org/?probe=2f123cee8b) | Sep 12, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| Dell          | Precision 3571              | Notebook    | [cf2bec0e5b](https://linux-hardware.org/?probe=cf2bec0e5b) | Sep 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2a15e9a8e0](https://linux-hardware.org/?probe=2a15e9a8e0) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [53961bd222](https://linux-hardware.org/?probe=53961bd222) | Sep 12, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [09ae29ce64](https://linux-hardware.org/?probe=09ae29ce64) | Sep 12, 2023 |
| HP            | 829A                        | Mini pc     | [dcb9e7ae5b](https://linux-hardware.org/?probe=dcb9e7ae5b) | Sep 11, 2023 |
| HP            | Unknown                     | Notebook    | [defc1de0cf](https://linux-hardware.org/?probe=defc1de0cf) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [4070a28418](https://linux-hardware.org/?probe=4070a28418) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [3abcd33b9c](https://linux-hardware.org/?probe=3abcd33b9c) | Sep 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [005f0b4e53](https://linux-hardware.org/?probe=005f0b4e53) | Sep 11, 2023 |
| ASRock        | B360M-HDV                   | Desktop     | [d4b0ae4d0c](https://linux-hardware.org/?probe=d4b0ae4d0c) | Sep 11, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7e57362cdc](https://linux-hardware.org/?probe=7e57362cdc) | Sep 11, 2023 |
| Login Info... | LOG-H61H2-M2                | Desktop     | [fa6e51b9bf](https://linux-hardware.org/?probe=fa6e51b9bf) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [772c3204b4](https://linux-hardware.org/?probe=772c3204b4) | Sep 10, 2023 |
| Positivo      | C464F                       | Notebook    | [e8154e06d4](https://linux-hardware.org/?probe=e8154e06d4) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [80b1b18a60](https://linux-hardware.org/?probe=80b1b18a60) | Sep 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [3b642be7da](https://linux-hardware.org/?probe=3b642be7da) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| ASRock        | H81 Pro BTC                 | Desktop     | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [5fc8984800](https://linux-hardware.org/?probe=5fc8984800) | Sep 10, 2023 |
| Dell          | Latitude 7280               | Notebook    | [fb9b253bd8](https://linux-hardware.org/?probe=fb9b253bd8) | Sep 10, 2023 |
| Dell          | Latitude 7280               | Notebook    | [936b42d3f3](https://linux-hardware.org/?probe=936b42d3f3) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [03ce2f9b74](https://linux-hardware.org/?probe=03ce2f9b74) | Sep 09, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [58e321a88b](https://linux-hardware.org/?probe=58e321a88b) | Sep 09, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [e8f4b3bf42](https://linux-hardware.org/?probe=e8f4b3bf42) | Sep 09, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [69458a43ef](https://linux-hardware.org/?probe=69458a43ef) | Sep 09, 2023 |
| Dell          | G15 5511                    | Notebook    | [c382a29576](https://linux-hardware.org/?probe=c382a29576) | Sep 09, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [198d33eff6](https://linux-hardware.org/?probe=198d33eff6) | Sep 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ae24b6af25](https://linux-hardware.org/?probe=ae24b6af25) | Sep 09, 2023 |
| ONDA          | H61V Ver:4.01               | Desktop     | [7423e0ce99](https://linux-hardware.org/?probe=7423e0ce99) | Sep 09, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4a63a68d47](https://linux-hardware.org/?probe=4a63a68d47) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [625b62078a](https://linux-hardware.org/?probe=625b62078a) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [440c9854ff](https://linux-hardware.org/?probe=440c9854ff) | Sep 09, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [af11868673](https://linux-hardware.org/?probe=af11868673) | Sep 09, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [a747d33ab9](https://linux-hardware.org/?probe=a747d33ab9) | Sep 09, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [db1e55d494](https://linux-hardware.org/?probe=db1e55d494) | Sep 08, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [1e817297bb](https://linux-hardware.org/?probe=1e817297bb) | Sep 08, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [c1dae32be6](https://linux-hardware.org/?probe=c1dae32be6) | Sep 08, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [3ab6390052](https://linux-hardware.org/?probe=3ab6390052) | Sep 08, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [b4ef54e230](https://linux-hardware.org/?probe=b4ef54e230) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | Notebook    | [cefbf3383a](https://linux-hardware.org/?probe=cefbf3383a) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | Notebook    | [73eae4d8a0](https://linux-hardware.org/?probe=73eae4d8a0) | Sep 08, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| HP            | 82B4                        | Desktop     | [e702194024](https://linux-hardware.org/?probe=e702194024) | Sep 08, 2023 |
| HP            | 82B4                        | Desktop     | [5c85d3bf3c](https://linux-hardware.org/?probe=5c85d3bf3c) | Sep 08, 2023 |
| Intel         | H61                         | Desktop     | [929cfae9af](https://linux-hardware.org/?probe=929cfae9af) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [08cdf9f2f5](https://linux-hardware.org/?probe=08cdf9f2f5) | Sep 08, 2023 |
| ASUSTek       | M51AC                       | Desktop     | [2cd8d3959a](https://linux-hardware.org/?probe=2cd8d3959a) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | Desktop     | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [996948fd3c](https://linux-hardware.org/?probe=996948fd3c) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c9f30a2b26](https://linux-hardware.org/?probe=c9f30a2b26) | Sep 06, 2023 |
| HP            | 844C                        | Desktop     | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [583006d2de](https://linux-hardware.org/?probe=583006d2de) | Sep 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | Notebook    | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [b6b2af8418](https://linux-hardware.org/?probe=b6b2af8418) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [89767db9e4](https://linux-hardware.org/?probe=89767db9e4) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7fa390fcc4](https://linux-hardware.org/?probe=7fa390fcc4) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | Precision 5570              | Notebook    | [9baca62616](https://linux-hardware.org/?probe=9baca62616) | Sep 06, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [8d550b32d9](https://linux-hardware.org/?probe=8d550b32d9) | Sep 06, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [208f21a716](https://linux-hardware.org/?probe=208f21a716) | Sep 05, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [5971b283b6](https://linux-hardware.org/?probe=5971b283b6) | Sep 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [40098c0a79](https://linux-hardware.org/?probe=40098c0a79) | Sep 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [1af9fd689a](https://linux-hardware.org/?probe=1af9fd689a) | Sep 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [acdd8a41d9](https://linux-hardware.org/?probe=acdd8a41d9) | Sep 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [606f54ecca](https://linux-hardware.org/?probe=606f54ecca) | Sep 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [9f577988e1](https://linux-hardware.org/?probe=9f577988e1) | Sep 04, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [d082fdd668](https://linux-hardware.org/?probe=d082fdd668) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9accfe317a](https://linux-hardware.org/?probe=9accfe317a) | Sep 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [daeb81e2f6](https://linux-hardware.org/?probe=daeb81e2f6) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [06571c70a0](https://linux-hardware.org/?probe=06571c70a0) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | Notebook    | [f9ae8ae2db](https://linux-hardware.org/?probe=f9ae8ae2db) | Sep 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a135074689](https://linux-hardware.org/?probe=a135074689) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| ASUSTek       | X55A                        | Notebook    | [da721dec12](https://linux-hardware.org/?probe=da721dec12) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [75c1744e6f](https://linux-hardware.org/?probe=75c1744e6f) | Sep 03, 2023 |
| HUAWEI        | FRD-WX9                     | Notebook    | [5831652a84](https://linux-hardware.org/?probe=5831652a84) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [69b91f1c46](https://linux-hardware.org/?probe=69b91f1c46) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| VENEZOLANA... | VIT P2460-02                | Notebook    | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c5787921e3](https://linux-hardware.org/?probe=c5787921e3) | Sep 03, 2023 |
| ASRock        | Z790 PG SONIC               | Desktop     | [72f1cf1ac0](https://linux-hardware.org/?probe=72f1cf1ac0) | Sep 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [762498a914](https://linux-hardware.org/?probe=762498a914) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [1283f01588](https://linux-hardware.org/?probe=1283f01588) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IAH8 83... | Notebook    | [2cfbf5b20c](https://linux-hardware.org/?probe=2cfbf5b20c) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aab4c37d85](https://linux-hardware.org/?probe=aab4c37d85) | Sep 02, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [193a173166](https://linux-hardware.org/?probe=193a173166) | Sep 02, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [bb268c3828](https://linux-hardware.org/?probe=bb268c3828) | Sep 02, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [9b802cfff6](https://linux-hardware.org/?probe=9b802cfff6) | Sep 02, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [af7d9b26da](https://linux-hardware.org/?probe=af7d9b26da) | Sep 01, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [bfb348ab81](https://linux-hardware.org/?probe=bfb348ab81) | Sep 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [cb4847f435](https://linux-hardware.org/?probe=cb4847f435) | Sep 01, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [78cb25f581](https://linux-hardware.org/?probe=78cb25f581) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d0a3fefd23](https://linux-hardware.org/?probe=d0a3fefd23) | Aug 31, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [987f4bab43](https://linux-hardware.org/?probe=987f4bab43) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [710315c4f1](https://linux-hardware.org/?probe=710315c4f1) | Aug 31, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [2ffc319636](https://linux-hardware.org/?probe=2ffc319636) | Aug 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [23242fe856](https://linux-hardware.org/?probe=23242fe856) | Aug 31, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8c1eeceddd](https://linux-hardware.org/?probe=8c1eeceddd) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f01ca37e4c](https://linux-hardware.org/?probe=f01ca37e4c) | Aug 31, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| ASUSTek       | Zenbook UX6404VV_UX6404V... | Notebook    | [b7be264a8d](https://linux-hardware.org/?probe=b7be264a8d) | Aug 30, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | Desktop     | [5de56db01e](https://linux-hardware.org/?probe=5de56db01e) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [58446213e2](https://linux-hardware.org/?probe=58446213e2) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [272508eb60](https://linux-hardware.org/?probe=272508eb60) | Aug 30, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c051ef93ac](https://linux-hardware.org/?probe=c051ef93ac) | Aug 30, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [2a5e5f7d35](https://linux-hardware.org/?probe=2a5e5f7d35) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [2b08121ea1](https://linux-hardware.org/?probe=2b08121ea1) | Aug 30, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [93fd8245ab](https://linux-hardware.org/?probe=93fd8245ab) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [fafc374d46](https://linux-hardware.org/?probe=fafc374d46) | Aug 29, 2023 |
| ASUSTek       | Zenbook UP5401ZA_UP5401Z... | Convertible | [63414c002c](https://linux-hardware.org/?probe=63414c002c) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [8a7f22304b](https://linux-hardware.org/?probe=8a7f22304b) | Aug 29, 2023 |
| Dell          | Inspiron 16 7635 2-in-1     | Convertible | [3ebe1769c0](https://linux-hardware.org/?probe=3ebe1769c0) | Aug 29, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bdaea6156d](https://linux-hardware.org/?probe=bdaea6156d) | Aug 29, 2023 |
| Dell          | Inspiron 16 7635 2-in-1     | Convertible | [2e6f42e754](https://linux-hardware.org/?probe=2e6f42e754) | Aug 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [e4b73c6be1](https://linux-hardware.org/?probe=e4b73c6be1) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [e5923577ad](https://linux-hardware.org/?probe=e5923577ad) | Aug 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ed544a4405](https://linux-hardware.org/?probe=ed544a4405) | Aug 28, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [c6e30be0e9](https://linux-hardware.org/?probe=c6e30be0e9) | Aug 27, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [cd64a75511](https://linux-hardware.org/?probe=cd64a75511) | Aug 27, 2023 |
| HP            | Compaq nx6325 (EN188UT#A... | Notebook    | [4324feffa1](https://linux-hardware.org/?probe=4324feffa1) | Aug 27, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [9dddd0c80b](https://linux-hardware.org/?probe=9dddd0c80b) | Aug 27, 2023 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [91204c1c19](https://linux-hardware.org/?probe=91204c1c19) | Aug 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [0f05e92358](https://linux-hardware.org/?probe=0f05e92358) | Aug 27, 2023 |
| Dell          | 0FGCC7 A02                  | Server      | [dc59cd86a0](https://linux-hardware.org/?probe=dc59cd86a0) | Aug 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [0fd39b7eb6](https://linux-hardware.org/?probe=0fd39b7eb6) | Aug 27, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | Notebook    | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| HP            | 843C                        | Desktop     | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [f108558763](https://linux-hardware.org/?probe=f108558763) | Aug 27, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [f153f48649](https://linux-hardware.org/?probe=f153f48649) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [623f136c0f](https://linux-hardware.org/?probe=623f136c0f) | Aug 27, 2023 |
| HP            | 2000                        | Notebook    | [a63dd6e0f1](https://linux-hardware.org/?probe=a63dd6e0f1) | Aug 26, 2023 |
| Dell          | Latitude 7380               | Notebook    | [396738805e](https://linux-hardware.org/?probe=396738805e) | Aug 26, 2023 |
| Dell          | Latitude 7380               | Notebook    | [4a0db5ad8a](https://linux-hardware.org/?probe=4a0db5ad8a) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [a8d794f4bb](https://linux-hardware.org/?probe=a8d794f4bb) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [a305956d47](https://linux-hardware.org/?probe=a305956d47) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | Desktop     | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [25c5011587](https://linux-hardware.org/?probe=25c5011587) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | Notebook    | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| Dell          | G3 3579                     | Notebook    | [843084a77c](https://linux-hardware.org/?probe=843084a77c) | Aug 25, 2023 |
| HP            | Notebook                    | Notebook    | [6404f1dc3a](https://linux-hardware.org/?probe=6404f1dc3a) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [aa3de32445](https://linux-hardware.org/?probe=aa3de32445) | Aug 25, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [cee65701f2](https://linux-hardware.org/?probe=cee65701f2) | Aug 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [de7752b138](https://linux-hardware.org/?probe=de7752b138) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [3ce0d3817d](https://linux-hardware.org/?probe=3ce0d3817d) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [e632335144](https://linux-hardware.org/?probe=e632335144) | Aug 25, 2023 |
| Dell          | Latitude E5570              | Notebook    | [2694b6c409](https://linux-hardware.org/?probe=2694b6c409) | Aug 24, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | Notebook    | [2281d96afb](https://linux-hardware.org/?probe=2281d96afb) | Aug 24, 2023 |
| HP            | ENVY 15                     | Notebook    | [6367186102](https://linux-hardware.org/?probe=6367186102) | Aug 24, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [b7ab89701b](https://linux-hardware.org/?probe=b7ab89701b) | Aug 24, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9a98c147d4](https://linux-hardware.org/?probe=9a98c147d4) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3723979edb](https://linux-hardware.org/?probe=3723979edb) | Aug 24, 2023 |
| HP            | Notebook                    | Notebook    | [1d3025a033](https://linux-hardware.org/?probe=1d3025a033) | Aug 24, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [c2e1396370](https://linux-hardware.org/?probe=c2e1396370) | Aug 23, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a5357a41b4](https://linux-hardware.org/?probe=a5357a41b4) | Aug 23, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [a8fb075a9a](https://linux-hardware.org/?probe=a8fb075a9a) | Aug 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d0505af7f](https://linux-hardware.org/?probe=1d0505af7f) | Aug 23, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [09820a2ab9](https://linux-hardware.org/?probe=09820a2ab9) | Aug 23, 2023 |
| Biostar       | B450MH                      | Desktop     | [21f8924d2c](https://linux-hardware.org/?probe=21f8924d2c) | Aug 23, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [297d07a2e3](https://linux-hardware.org/?probe=297d07a2e3) | Aug 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [7cf233eb4d](https://linux-hardware.org/?probe=7cf233eb4d) | Aug 22, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [cc07dc8140](https://linux-hardware.org/?probe=cc07dc8140) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | Notebook    | [f30e9be6d0](https://linux-hardware.org/?probe=f30e9be6d0) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [210e9d3b38](https://linux-hardware.org/?probe=210e9d3b38) | Aug 21, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [75776f43bf](https://linux-hardware.org/?probe=75776f43bf) | Aug 21, 2023 |
| Intel         | NUC7i3BNB J22859-314        | Mini pc     | [ce4752c5b7](https://linux-hardware.org/?probe=ce4752c5b7) | Aug 21, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [81bc5661ca](https://linux-hardware.org/?probe=81bc5661ca) | Aug 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a7cd220563](https://linux-hardware.org/?probe=a7cd220563) | Aug 21, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [c2ca279bdd](https://linux-hardware.org/?probe=c2ca279bdd) | Aug 21, 2023 |
| Medion        | WIM2210                     | Notebook    | [5ef8675128](https://linux-hardware.org/?probe=5ef8675128) | Aug 21, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [d59b79adfe](https://linux-hardware.org/?probe=d59b79adfe) | Aug 21, 2023 |
| HP            | EliteBook 835 13 inch G9... | Notebook    | [f973c9678d](https://linux-hardware.org/?probe=f973c9678d) | Aug 20, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [bca7b6990c](https://linux-hardware.org/?probe=bca7b6990c) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [e3f7de5c66](https://linux-hardware.org/?probe=e3f7de5c66) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [872053c50b](https://linux-hardware.org/?probe=872053c50b) | Aug 20, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fee22676ae](https://linux-hardware.org/?probe=fee22676ae) | Aug 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5ca28d9b12](https://linux-hardware.org/?probe=5ca28d9b12) | Aug 20, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a11383f5b3](https://linux-hardware.org/?probe=a11383f5b3) | Aug 19, 2023 |
| ASRock        | Q1900M                      | Desktop     | [1e1e781c93](https://linux-hardware.org/?probe=1e1e781c93) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | Desktop     | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [f56bdd302b](https://linux-hardware.org/?probe=f56bdd302b) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b52dbe962f](https://linux-hardware.org/?probe=b52dbe962f) | Aug 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [816ff5d908](https://linux-hardware.org/?probe=816ff5d908) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | Desktop     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a75b18f36c](https://linux-hardware.org/?probe=a75b18f36c) | Aug 19, 2023 |
| Lenovo        | V320-17ISK 81B6             | Notebook    | [cc96bcc8d9](https://linux-hardware.org/?probe=cc96bcc8d9) | Aug 19, 2023 |
| Acer          | Veriton M2611G v1.0         | Desktop     | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [b7347b4f7c](https://linux-hardware.org/?probe=b7347b4f7c) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [950ffc31ff](https://linux-hardware.org/?probe=950ffc31ff) | Aug 18, 2023 |
| Dell          | 0X8582                      | Desktop     | [c9661782e6](https://linux-hardware.org/?probe=c9661782e6) | Aug 18, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [c6918bacbd](https://linux-hardware.org/?probe=c6918bacbd) | Aug 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e37325dbc2](https://linux-hardware.org/?probe=e37325dbc2) | Aug 18, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79d5cb1a00](https://linux-hardware.org/?probe=79d5cb1a00) | Aug 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [0edbb9bdf1](https://linux-hardware.org/?probe=0edbb9bdf1) | Aug 17, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [ed669d11d8](https://linux-hardware.org/?probe=ed669d11d8) | Aug 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [645171b203](https://linux-hardware.org/?probe=645171b203) | Aug 17, 2023 |
| Acer          | Aspire Z5710                | All in one  | [10e9ce60c2](https://linux-hardware.org/?probe=10e9ce60c2) | Aug 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [0e1961a9b3](https://linux-hardware.org/?probe=0e1961a9b3) | Aug 17, 2023 |
| Acer          | Swift SF314-510G            | Notebook    | [11a4bc0bac](https://linux-hardware.org/?probe=11a4bc0bac) | Aug 16, 2023 |
| Dell          | Precision 7530              | Notebook    | [dfaa8829e1](https://linux-hardware.org/?probe=dfaa8829e1) | Aug 16, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [68639ddf06](https://linux-hardware.org/?probe=68639ddf06) | Aug 16, 2023 |
| ASUSTek       | X55A                        | Notebook    | [03099661ec](https://linux-hardware.org/?probe=03099661ec) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [4c4e9222ce](https://linux-hardware.org/?probe=4c4e9222ce) | Aug 16, 2023 |
| Shuttle       | NC03U                       | Notebook    | [91097c1ebf](https://linux-hardware.org/?probe=91097c1ebf) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [c4b30192fa](https://linux-hardware.org/?probe=c4b30192fa) | Aug 15, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [529613b5c7](https://linux-hardware.org/?probe=529613b5c7) | Aug 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [ea9845e55b](https://linux-hardware.org/?probe=ea9845e55b) | Aug 15, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [fd5dd48ab1](https://linux-hardware.org/?probe=fd5dd48ab1) | Aug 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [088582c57c](https://linux-hardware.org/?probe=088582c57c) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [caa5e1d37a](https://linux-hardware.org/?probe=caa5e1d37a) | Aug 14, 2023 |
| AK3V          | 1.0                         | Desktop     | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | Desktop     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0e51f02009](https://linux-hardware.org/?probe=0e51f02009) | Aug 14, 2023 |
| MSI           | Stealth 14Studio A13VG      | Notebook    | [a8035775f2](https://linux-hardware.org/?probe=a8035775f2) | Aug 14, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [9a680df78d](https://linux-hardware.org/?probe=9a680df78d) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | Desktop     | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [a501a43d37](https://linux-hardware.org/?probe=a501a43d37) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [e069c1f3d5](https://linux-hardware.org/?probe=e069c1f3d5) | Aug 13, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [c94361f09d](https://linux-hardware.org/?probe=c94361f09d) | Aug 13, 2023 |
| Acer          | Extensa 5220                | Notebook    | [fb3e613b5c](https://linux-hardware.org/?probe=fb3e613b5c) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [396327d1fa](https://linux-hardware.org/?probe=396327d1fa) | Aug 13, 2023 |
| Dell          | Inspiron 14 7435 2-in-1     | Convertible | [ee7ca4926f](https://linux-hardware.org/?probe=ee7ca4926f) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bcf7b9bd8f](https://linux-hardware.org/?probe=bcf7b9bd8f) | Aug 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [e52e8ee5df](https://linux-hardware.org/?probe=e52e8ee5df) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [fee93b31f5](https://linux-hardware.org/?probe=fee93b31f5) | Aug 13, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [2996bc5d6c](https://linux-hardware.org/?probe=2996bc5d6c) | Aug 13, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4d954b8546](https://linux-hardware.org/?probe=4d954b8546) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7d7349fef7](https://linux-hardware.org/?probe=7d7349fef7) | Aug 12, 2023 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [eb228fe415](https://linux-hardware.org/?probe=eb228fe415) | Aug 12, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [61f00a0418](https://linux-hardware.org/?probe=61f00a0418) | Aug 12, 2023 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [68175aa949](https://linux-hardware.org/?probe=68175aa949) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [4963974f47](https://linux-hardware.org/?probe=4963974f47) | Aug 12, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [d42fa686e5](https://linux-hardware.org/?probe=d42fa686e5) | Aug 12, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [45509c2727](https://linux-hardware.org/?probe=45509c2727) | Aug 12, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [756901f27f](https://linux-hardware.org/?probe=756901f27f) | Aug 12, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [a68db843ea](https://linux-hardware.org/?probe=a68db843ea) | Aug 12, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [8abafe1b65](https://linux-hardware.org/?probe=8abafe1b65) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [2939f44178](https://linux-hardware.org/?probe=2939f44178) | Aug 12, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5892469c5b](https://linux-hardware.org/?probe=5892469c5b) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [7fb2d45505](https://linux-hardware.org/?probe=7fb2d45505) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [53196a01fa](https://linux-hardware.org/?probe=53196a01fa) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [be4514c366](https://linux-hardware.org/?probe=be4514c366) | Aug 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| ASUSTek       | K55A                        | Notebook    | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [f278787ab5](https://linux-hardware.org/?probe=f278787ab5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [76078461ae](https://linux-hardware.org/?probe=76078461ae) | Aug 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ab2473ff49](https://linux-hardware.org/?probe=ab2473ff49) | Aug 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b50bdc5845](https://linux-hardware.org/?probe=b50bdc5845) | Aug 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [8a3df803a6](https://linux-hardware.org/?probe=8a3df803a6) | Aug 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7f2903e1a4](https://linux-hardware.org/?probe=7f2903e1a4) | Aug 11, 2023 |
| Dell          | Precision 5530              | Notebook    | [f74dac5dcf](https://linux-hardware.org/?probe=f74dac5dcf) | Aug 11, 2023 |
| Dell          | Latitude 5400               | Notebook    | [1ec248c607](https://linux-hardware.org/?probe=1ec248c607) | Aug 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| Lenovo        | ThinkPad Edge 03193VG       | Notebook    | [abb370836a](https://linux-hardware.org/?probe=abb370836a) | Aug 10, 2023 |
| Avell         | A70 ION                     | Notebook    | [6ab02a34e4](https://linux-hardware.org/?probe=6ab02a34e4) | Aug 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga 20FRS02... | Convertible | [ba520853af](https://linux-hardware.org/?probe=ba520853af) | Aug 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga 20FRS02... | Convertible | [534fd57945](https://linux-hardware.org/?probe=534fd57945) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4180X06       | Notebook    | [77e54b4b97](https://linux-hardware.org/?probe=77e54b4b97) | Aug 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7fe8fc7f3](https://linux-hardware.org/?probe=f7fe8fc7f3) | Aug 10, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [ab3503021a](https://linux-hardware.org/?probe=ab3503021a) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4180X06       | Notebook    | [ba950eb9e1](https://linux-hardware.org/?probe=ba950eb9e1) | Aug 10, 2023 |
| Google        | Snappy                      | Notebook    | [73ecdd5048](https://linux-hardware.org/?probe=73ecdd5048) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [ae87c6938f](https://linux-hardware.org/?probe=ae87c6938f) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [a874870955](https://linux-hardware.org/?probe=a874870955) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [de8d362cb8](https://linux-hardware.org/?probe=de8d362cb8) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [194ec12831](https://linux-hardware.org/?probe=194ec12831) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Dell          | Latitude 3350               | Notebook    | [77100b2ef6](https://linux-hardware.org/?probe=77100b2ef6) | Aug 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [773e9320a8](https://linux-hardware.org/?probe=773e9320a8) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [057ef3751d](https://linux-hardware.org/?probe=057ef3751d) | Aug 08, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [49a63e5cc4](https://linux-hardware.org/?probe=49a63e5cc4) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [60a28c22c7](https://linux-hardware.org/?probe=60a28c22c7) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [9f044dbe9e](https://linux-hardware.org/?probe=9f044dbe9e) | Aug 08, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [f9d26a8832](https://linux-hardware.org/?probe=f9d26a8832) | Aug 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [791adb121f](https://linux-hardware.org/?probe=791adb121f) | Aug 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3ec4223487](https://linux-hardware.org/?probe=3ec4223487) | Aug 07, 2023 |
| Dell          | Latitude 7300               | Notebook    | [932f04033c](https://linux-hardware.org/?probe=932f04033c) | Aug 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [783906b878](https://linux-hardware.org/?probe=783906b878) | Aug 07, 2023 |
| Intel         | NUC7i3BNB J22859-314        | Mini pc     | [36410845ea](https://linux-hardware.org/?probe=36410845ea) | Aug 07, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [ae0cada933](https://linux-hardware.org/?probe=ae0cada933) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [dbefafc94d](https://linux-hardware.org/?probe=dbefafc94d) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [d24385ceb8](https://linux-hardware.org/?probe=d24385ceb8) | Aug 07, 2023 |
| Timi          | TM1607                      | Notebook    | [c545853106](https://linux-hardware.org/?probe=c545853106) | Aug 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [9f230de889](https://linux-hardware.org/?probe=9f230de889) | Aug 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1d8737323b](https://linux-hardware.org/?probe=1d8737323b) | Aug 06, 2023 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [9d3b59de32](https://linux-hardware.org/?probe=9d3b59de32) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ebed30097f](https://linux-hardware.org/?probe=ebed30097f) | Aug 06, 2023 |
| ASUSTek       | K54L                        | Notebook    | [3ce0c0b7b2](https://linux-hardware.org/?probe=3ce0c0b7b2) | Aug 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [8a0a837f0b](https://linux-hardware.org/?probe=8a0a837f0b) | Aug 06, 2023 |
| ASUSTek       | K54L                        | Notebook    | [b28f27325f](https://linux-hardware.org/?probe=b28f27325f) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [4bd753037a](https://linux-hardware.org/?probe=4bd753037a) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cc48d8c23e](https://linux-hardware.org/?probe=cc48d8c23e) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [9c9e999e7f](https://linux-hardware.org/?probe=9c9e999e7f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [54f0bde318](https://linux-hardware.org/?probe=54f0bde318) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [52b9918d42](https://linux-hardware.org/?probe=52b9918d42) | Aug 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| Dell          | Latitude 5590               | Notebook    | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| Dell          | Latitude 5400               | Notebook    | [e788e3a534](https://linux-hardware.org/?probe=e788e3a534) | Aug 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [34fa8887dd](https://linux-hardware.org/?probe=34fa8887dd) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6c24c9f7a9](https://linux-hardware.org/?probe=6c24c9f7a9) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [24dc4f34a2](https://linux-hardware.org/?probe=24dc4f34a2) | Aug 05, 2023 |
| GMKtec        | NucBox K4                   | Desktop     | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [779c23fe06](https://linux-hardware.org/?probe=779c23fe06) | Aug 05, 2023 |
| Lenovo        | ThinkPad X131e 33671S2      | Notebook    | [3f83b5efac](https://linux-hardware.org/?probe=3f83b5efac) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [364aa911cf](https://linux-hardware.org/?probe=364aa911cf) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [08f78bf99a](https://linux-hardware.org/?probe=08f78bf99a) | Aug 05, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [fed2da6500](https://linux-hardware.org/?probe=fed2da6500) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2531b9d0db](https://linux-hardware.org/?probe=2531b9d0db) | Aug 05, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [3f7f45a94e](https://linux-hardware.org/?probe=3f7f45a94e) | Aug 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f7354ee466](https://linux-hardware.org/?probe=f7354ee466) | Aug 04, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [67cea35f6d](https://linux-hardware.org/?probe=67cea35f6d) | Aug 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [8a2dafef83](https://linux-hardware.org/?probe=8a2dafef83) | Aug 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8aad3290a7](https://linux-hardware.org/?probe=8aad3290a7) | Aug 03, 2023 |
| ASUSTek       | M3A78-T                     | Desktop     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [69b35fdf25](https://linux-hardware.org/?probe=69b35fdf25) | Aug 03, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [2d4fc6f4ce](https://linux-hardware.org/?probe=2d4fc6f4ce) | Aug 03, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| ZOTAC         | ZBOX-PI335                  | Mini pc     | [8b5204eccf](https://linux-hardware.org/?probe=8b5204eccf) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| HP            | Notebook                    | Notebook    | [0e8585ef71](https://linux-hardware.org/?probe=0e8585ef71) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [881ac0a0e0](https://linux-hardware.org/?probe=881ac0a0e0) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3beec95b8](https://linux-hardware.org/?probe=c3beec95b8) | Aug 02, 2023 |
| HP            | 8653 A                      | Desktop     | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5f2529e42b](https://linux-hardware.org/?probe=5f2529e42b) | Aug 02, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [4d0d3b78e7](https://linux-hardware.org/?probe=4d0d3b78e7) | Aug 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [41ff18df05](https://linux-hardware.org/?probe=41ff18df05) | Aug 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [eb3d428d41](https://linux-hardware.org/?probe=eb3d428d41) | Aug 02, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cbc721a89f](https://linux-hardware.org/?probe=cbc721a89f) | Aug 01, 2023 |
| HP            | Unknown                     | Notebook    | [f7ffb3c085](https://linux-hardware.org/?probe=f7ffb3c085) | Aug 01, 2023 |
| HP            | 82B5                        | All in one  | [e63af4a7b9](https://linux-hardware.org/?probe=e63af4a7b9) | Aug 01, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [53468c11bf](https://linux-hardware.org/?probe=53468c11bf) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [66000207b0](https://linux-hardware.org/?probe=66000207b0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | Desktop     | [df0702afb0](https://linux-hardware.org/?probe=df0702afb0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | Desktop     | [0ac623dd70](https://linux-hardware.org/?probe=0ac623dd70) | Aug 01, 2023 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [3775167d2f](https://linux-hardware.org/?probe=3775167d2f) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [16858eae01](https://linux-hardware.org/?probe=16858eae01) | Jul 31, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [831157a9ac](https://linux-hardware.org/?probe=831157a9ac) | Jul 31, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [45405639f5](https://linux-hardware.org/?probe=45405639f5) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [42bf6e1e48](https://linux-hardware.org/?probe=42bf6e1e48) | Jul 30, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [be9923f6d2](https://linux-hardware.org/?probe=be9923f6d2) | Jul 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [71379f70f2](https://linux-hardware.org/?probe=71379f70f2) | Jul 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [f8ebba29c6](https://linux-hardware.org/?probe=f8ebba29c6) | Jul 30, 2023 |
| HP            | ProBook 4540s               | Notebook    | [0fae07b574](https://linux-hardware.org/?probe=0fae07b574) | Jul 30, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [2672322c34](https://linux-hardware.org/?probe=2672322c34) | Jul 30, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b70677782d](https://linux-hardware.org/?probe=b70677782d) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [ae8a9f3aaf](https://linux-hardware.org/?probe=ae8a9f3aaf) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [f36740f05f](https://linux-hardware.org/?probe=f36740f05f) | Jul 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [579d4eebb8](https://linux-hardware.org/?probe=579d4eebb8) | Jul 29, 2023 |
| Dell          | Precision 5510              | Notebook    | [56b4073d3f](https://linux-hardware.org/?probe=56b4073d3f) | Jul 29, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | Notebook    | [cde4989301](https://linux-hardware.org/?probe=cde4989301) | Jul 28, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [30afe43d32](https://linux-hardware.org/?probe=30afe43d32) | Jul 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3e7b8ae52e](https://linux-hardware.org/?probe=3e7b8ae52e) | Jul 28, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [68618d14ef](https://linux-hardware.org/?probe=68618d14ef) | Jul 28, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [08990a8da3](https://linux-hardware.org/?probe=08990a8da3) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK U939X              | Convertible | [354787d766](https://linux-hardware.org/?probe=354787d766) | Jul 28, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d54574b3f8](https://linux-hardware.org/?probe=d54574b3f8) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d0d94c9be7](https://linux-hardware.org/?probe=d0d94c9be7) | Jul 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [87bb7b0b79](https://linux-hardware.org/?probe=87bb7b0b79) | Jul 26, 2023 |
| Acer          | Nitro AN17-41               | Notebook    | [7909f8c5f3](https://linux-hardware.org/?probe=7909f8c5f3) | Jul 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d6855eabe2](https://linux-hardware.org/?probe=d6855eabe2) | Jul 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1ed1c25f7e](https://linux-hardware.org/?probe=1ed1c25f7e) | Jul 26, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [863a5cb9da](https://linux-hardware.org/?probe=863a5cb9da) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| HP            | 3646h                       | Desktop     | [fbc7ac7c08](https://linux-hardware.org/?probe=fbc7ac7c08) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f41d6c4f4b](https://linux-hardware.org/?probe=f41d6c4f4b) | Jul 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2fe1d4509a](https://linux-hardware.org/?probe=2fe1d4509a) | Jul 26, 2023 |
| Sony          | VPCSB1V9R                   | Notebook    | [12b5777cff](https://linux-hardware.org/?probe=12b5777cff) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [802ba60219](https://linux-hardware.org/?probe=802ba60219) | Jul 25, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [d96478ff29](https://linux-hardware.org/?probe=d96478ff29) | Jul 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [32707549f9](https://linux-hardware.org/?probe=32707549f9) | Jul 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f8720bbd07](https://linux-hardware.org/?probe=f8720bbd07) | Jul 25, 2023 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [3f563f695c](https://linux-hardware.org/?probe=3f563f695c) | Jul 25, 2023 |
| Lenovo        | B590 62743QG                | Notebook    | [d8bd2493ec](https://linux-hardware.org/?probe=d8bd2493ec) | Jul 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [42ee46f6c4](https://linux-hardware.org/?probe=42ee46f6c4) | Jul 25, 2023 |
| MSI           | WF66 11UJ                   | Notebook    | [305e24e26d](https://linux-hardware.org/?probe=305e24e26d) | Jul 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [5c4b165cea](https://linux-hardware.org/?probe=5c4b165cea) | Jul 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [4ad8be01ca](https://linux-hardware.org/?probe=4ad8be01ca) | Jul 25, 2023 |
| Unknown       | 1.2                         | Desktop     | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [72a17a2b8f](https://linux-hardware.org/?probe=72a17a2b8f) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [02cae62d32](https://linux-hardware.org/?probe=02cae62d32) | Jul 24, 2023 |
| Google        | Treeya                      | Notebook    | [808e203694](https://linux-hardware.org/?probe=808e203694) | Jul 24, 2023 |
| Google        | Treeya                      | Notebook    | [db2b782253](https://linux-hardware.org/?probe=db2b782253) | Jul 24, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [3fd49d8f38](https://linux-hardware.org/?probe=3fd49d8f38) | Jul 24, 2023 |
| Intel         | Unknown                     | Desktop     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | Notebook    | [d25f59d64d](https://linux-hardware.org/?probe=d25f59d64d) | Jul 23, 2023 |
| ASUSTek       | X45U                        | Notebook    | [53a411cd41](https://linux-hardware.org/?probe=53a411cd41) | Jul 23, 2023 |
| Google        | Lillipup                    | Notebook    | [3915bca457](https://linux-hardware.org/?probe=3915bca457) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| Intel         | B75                         | Desktop     | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3511a9786a](https://linux-hardware.org/?probe=3511a9786a) | Jul 23, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [1705d2fd99](https://linux-hardware.org/?probe=1705d2fd99) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [383118634e](https://linux-hardware.org/?probe=383118634e) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | Desktop     | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | Notebook    | [4a5ded3dcc](https://linux-hardware.org/?probe=4a5ded3dcc) | Jul 23, 2023 |
| Lenovo        | ThinkPad P53 20QN004BCA     | Notebook    | [04a2ed4bd2](https://linux-hardware.org/?probe=04a2ed4bd2) | Jul 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [62efe51727](https://linux-hardware.org/?probe=62efe51727) | Jul 23, 2023 |
| Dell          | Latitude 3500               | Notebook    | [fcfa320897](https://linux-hardware.org/?probe=fcfa320897) | Jul 23, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [63fb3abc69](https://linux-hardware.org/?probe=63fb3abc69) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [1ee910fc1c](https://linux-hardware.org/?probe=1ee910fc1c) | Jul 22, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [d02b0e9f74](https://linux-hardware.org/?probe=d02b0e9f74) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [808ae8a334](https://linux-hardware.org/?probe=808ae8a334) | Jul 22, 2023 |
| ATOPNUC       | AG40                        | Mini pc     | [06a69f0d48](https://linux-hardware.org/?probe=06a69f0d48) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [fee4019ae0](https://linux-hardware.org/?probe=fee4019ae0) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dee00fe6af](https://linux-hardware.org/?probe=dee00fe6af) | Jul 22, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [1e0063a74a](https://linux-hardware.org/?probe=1e0063a74a) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [b754fb3410](https://linux-hardware.org/?probe=b754fb3410) | Jul 21, 2023 |
| Acer          | Aspire Z5710                | All in one  | [8d0478cf81](https://linux-hardware.org/?probe=8d0478cf81) | Jul 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| ASUSTek       | B53E                        | Notebook    | [08012052d5](https://linux-hardware.org/?probe=08012052d5) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [e35d64a41b](https://linux-hardware.org/?probe=e35d64a41b) | Jul 21, 2023 |
| Dell          | 0WXD1Y A01                  | Server      | [477343a949](https://linux-hardware.org/?probe=477343a949) | Jul 21, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [b6432541ed](https://linux-hardware.org/?probe=b6432541ed) | Jul 21, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [ce5f140a90](https://linux-hardware.org/?probe=ce5f140a90) | Jul 21, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [a07f95cdcc](https://linux-hardware.org/?probe=a07f95cdcc) | Jul 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [3bd7501f03](https://linux-hardware.org/?probe=3bd7501f03) | Jul 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4b7b13a46d](https://linux-hardware.org/?probe=4b7b13a46d) | Jul 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [64b51936ea](https://linux-hardware.org/?probe=64b51936ea) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [903099ae11](https://linux-hardware.org/?probe=903099ae11) | Jul 20, 2023 |
| Samsung       | DP500A2D-A01UB SEC_SW_RE... | All in one  | [99e81c0d0e](https://linux-hardware.org/?probe=99e81c0d0e) | Jul 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [991cab2fa3](https://linux-hardware.org/?probe=991cab2fa3) | Jul 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [f99a99e95e](https://linux-hardware.org/?probe=f99a99e95e) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | Notebook    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [5643f29431](https://linux-hardware.org/?probe=5643f29431) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b5b8d4fce2](https://linux-hardware.org/?probe=b5b8d4fce2) | Jul 19, 2023 |
| Unknown       | G41 Series                  | Desktop     | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [3a257c75fc](https://linux-hardware.org/?probe=3a257c75fc) | Jul 19, 2023 |
| Acer          | Nitro AN17-41               | Notebook    | [81c4c542a9](https://linux-hardware.org/?probe=81c4c542a9) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | Notebook    | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [7b7cf50cba](https://linux-hardware.org/?probe=7b7cf50cba) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | Notebook    | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| Dell          | Latitude 7480               | Notebook    | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | Notebook    | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| Dell          | Latitude 3500               | Notebook    | [bd6b4ea554](https://linux-hardware.org/?probe=bd6b4ea554) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | Desktop     | [e62367803c](https://linux-hardware.org/?probe=e62367803c) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | Desktop     | [41e06d3720](https://linux-hardware.org/?probe=41e06d3720) | Jul 18, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [13654f5014](https://linux-hardware.org/?probe=13654f5014) | Jul 18, 2023 |
| Sony          | VAIO                        | All in one  | [ea7a51d543](https://linux-hardware.org/?probe=ea7a51d543) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| Packard Be... | IMEDIA S2885                | Desktop     | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| Google        | Lick                        | Notebook    | [be8f8d1fd5](https://linux-hardware.org/?probe=be8f8d1fd5) | Jul 17, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60280e0708](https://linux-hardware.org/?probe=60280e0708) | Jul 17, 2023 |
| MSI           | FM2-A85XA-G65               | Desktop     | [8e6741f497](https://linux-hardware.org/?probe=8e6741f497) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| Dell          | Latitude 7420               | Notebook    | [acf0339a4c](https://linux-hardware.org/?probe=acf0339a4c) | Jul 17, 2023 |
| Dell          | Latitude E7470              | Notebook    | [a3b762c162](https://linux-hardware.org/?probe=a3b762c162) | Jul 17, 2023 |
| Dell          | Latitude E7470              | Notebook    | [69531585c0](https://linux-hardware.org/?probe=69531585c0) | Jul 17, 2023 |
| Google        | Lick                        | Notebook    | [177ed7483f](https://linux-hardware.org/?probe=177ed7483f) | Jul 16, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [5abf5fb1c3](https://linux-hardware.org/?probe=5abf5fb1c3) | Jul 16, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [c9f052e7ff](https://linux-hardware.org/?probe=c9f052e7ff) | Jul 16, 2023 |
| Dell          | G5 5587                     | Notebook    | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | Desktop     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [0059901b85](https://linux-hardware.org/?probe=0059901b85) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [45c881b739](https://linux-hardware.org/?probe=45c881b739) | Jul 16, 2023 |
| MSI           | G41M4                       | Desktop     | [b7bda60261](https://linux-hardware.org/?probe=b7bda60261) | Jul 16, 2023 |
| MSI           | G41M4                       | Desktop     | [a3e5e23a49](https://linux-hardware.org/?probe=a3e5e23a49) | Jul 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [79af0f54f4](https://linux-hardware.org/?probe=79af0f54f4) | Jul 15, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [4767e5dc31](https://linux-hardware.org/?probe=4767e5dc31) | Jul 15, 2023 |
| Gigabyte      | P65                         | Notebook    | [b46e8302f7](https://linux-hardware.org/?probe=b46e8302f7) | Jul 15, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Acer          | TravelMate Spin B118-R      | Convertible | [c0ad7a539d](https://linux-hardware.org/?probe=c0ad7a539d) | Jul 15, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ad21a4bc5e](https://linux-hardware.org/?probe=ad21a4bc5e) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [938e7cd384](https://linux-hardware.org/?probe=938e7cd384) | Jul 15, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [92bd2944cb](https://linux-hardware.org/?probe=92bd2944cb) | Jul 15, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | Notebook    | [dd92f9ce05](https://linux-hardware.org/?probe=dd92f9ce05) | Jul 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [99e796a389](https://linux-hardware.org/?probe=99e796a389) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ea96a066b6](https://linux-hardware.org/?probe=ea96a066b6) | Jul 14, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [e80cfeb390](https://linux-hardware.org/?probe=e80cfeb390) | Jul 14, 2023 |
| Notebook      | N150ZU                      | Notebook    | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [d2cef330bf](https://linux-hardware.org/?probe=d2cef330bf) | Jul 14, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5932f3d2eb](https://linux-hardware.org/?probe=5932f3d2eb) | Jul 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [b0ce3265f2](https://linux-hardware.org/?probe=b0ce3265f2) | Jul 14, 2023 |
| Lenovo        | ThinkPad Edge E535 3260C... | Notebook    | [9ff1a61e2a](https://linux-hardware.org/?probe=9ff1a61e2a) | Jul 14, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [26a95caa91](https://linux-hardware.org/?probe=26a95caa91) | Jul 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [a67315ae3e](https://linux-hardware.org/?probe=a67315ae3e) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [95a7d172c2](https://linux-hardware.org/?probe=95a7d172c2) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [876eb35009](https://linux-hardware.org/?probe=876eb35009) | Jul 13, 2023 |
| MSI           | FM2-A85XA-G65               | Desktop     | [00b4b2f7b0](https://linux-hardware.org/?probe=00b4b2f7b0) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | Notebook    | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | Notebook    | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [a93793ae9c](https://linux-hardware.org/?probe=a93793ae9c) | Jul 13, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [1412ecd811](https://linux-hardware.org/?probe=1412ecd811) | Jul 13, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [49657bd961](https://linux-hardware.org/?probe=49657bd961) | Jul 13, 2023 |
| MSI           | Z87-G43                     | Desktop     | [86d9a28ae8](https://linux-hardware.org/?probe=86d9a28ae8) | Jul 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [d5ff5f9f79](https://linux-hardware.org/?probe=d5ff5f9f79) | Jul 13, 2023 |
| Positivo      | A14CR6A                     | Notebook    | [7ad49c61bd](https://linux-hardware.org/?probe=7ad49c61bd) | Jul 13, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [15101e4f9b](https://linux-hardware.org/?probe=15101e4f9b) | Jul 13, 2023 |
| HP            | Notebook                    | Notebook    | [adbdafe73d](https://linux-hardware.org/?probe=adbdafe73d) | Jul 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0V30... | Notebook    | [174cb234d5](https://linux-hardware.org/?probe=174cb234d5) | Jul 12, 2023 |
| HP            | 83EE                        | Desktop     | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [8974860f56](https://linux-hardware.org/?probe=8974860f56) | Jul 12, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [c957ebba28](https://linux-hardware.org/?probe=c957ebba28) | Jul 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [c3b936e87a](https://linux-hardware.org/?probe=c3b936e87a) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [e594307388](https://linux-hardware.org/?probe=e594307388) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| Lenovo        | ThinkPad X230 2324DP1       | Notebook    | [5b139ff19a](https://linux-hardware.org/?probe=5b139ff19a) | Jul 12, 2023 |
| Samsung       | 950XED                      | Notebook    | [2f8f9d9277](https://linux-hardware.org/?probe=2f8f9d9277) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [5a1636d8ce](https://linux-hardware.org/?probe=5a1636d8ce) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [0fbc8ca097](https://linux-hardware.org/?probe=0fbc8ca097) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fddbab0cf6](https://linux-hardware.org/?probe=fddbab0cf6) | Jul 11, 2023 |
| HP            | 82B5                        | All in one  | [3f1fecd5c3](https://linux-hardware.org/?probe=3f1fecd5c3) | Jul 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [443e3f909c](https://linux-hardware.org/?probe=443e3f909c) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [4483ce93af](https://linux-hardware.org/?probe=4483ce93af) | Jul 11, 2023 |
| ASRock        | X79 Extreme9                | Desktop     | [bfd488feb9](https://linux-hardware.org/?probe=bfd488feb9) | Jul 10, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [52f242e136](https://linux-hardware.org/?probe=52f242e136) | Jul 10, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [6d76fdbcd6](https://linux-hardware.org/?probe=6d76fdbcd6) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [2992a0aea9](https://linux-hardware.org/?probe=2992a0aea9) | Jul 10, 2023 |
| Dell          | Latitude 3580               | Notebook    | [b1bfa37b93](https://linux-hardware.org/?probe=b1bfa37b93) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1312271ad3](https://linux-hardware.org/?probe=1312271ad3) | Jul 10, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [f60d21d84f](https://linux-hardware.org/?probe=f60d21d84f) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [49c5ec535d](https://linux-hardware.org/?probe=49c5ec535d) | Jul 09, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [8f57c74864](https://linux-hardware.org/?probe=8f57c74864) | Jul 09, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [b320d70c27](https://linux-hardware.org/?probe=b320d70c27) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | Notebook    | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | Notebook    | [e9410cf823](https://linux-hardware.org/?probe=e9410cf823) | Jul 09, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | Notebook    | [d053bea459](https://linux-hardware.org/?probe=d053bea459) | Jul 09, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | Desktop     | [d7f7dc2ef3](https://linux-hardware.org/?probe=d7f7dc2ef3) | Jul 08, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7e1543a378](https://linux-hardware.org/?probe=7e1543a378) | Jul 08, 2023 |
| Lenovo        | IdeaCentre K330A            | Desktop     | [8d98ff8f86](https://linux-hardware.org/?probe=8d98ff8f86) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [b01bdb1bd6](https://linux-hardware.org/?probe=b01bdb1bd6) | Jul 08, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [91cab30323](https://linux-hardware.org/?probe=91cab30323) | Jul 08, 2023 |
| HP            | 14                          | Notebook    | [71d49b008d](https://linux-hardware.org/?probe=71d49b008d) | Jul 08, 2023 |
| HP            | 14                          | Notebook    | [ba511c29ac](https://linux-hardware.org/?probe=ba511c29ac) | Jul 08, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [61e7b20b21](https://linux-hardware.org/?probe=61e7b20b21) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [89a1894d2a](https://linux-hardware.org/?probe=89a1894d2a) | Jul 08, 2023 |
| Toshiba       | PORTEGE X30T-E              | Tablet      | [2942c2e2d5](https://linux-hardware.org/?probe=2942c2e2d5) | Jul 07, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [88c77852f0](https://linux-hardware.org/?probe=88c77852f0) | Jul 07, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [790145611f](https://linux-hardware.org/?probe=790145611f) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7e3f6aabfb](https://linux-hardware.org/?probe=7e3f6aabfb) | Jul 06, 2023 |
| Notebook      | NJx0PU                      | Notebook    | [29ebf426d1](https://linux-hardware.org/?probe=29ebf426d1) | Jul 06, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [5e66adbc36](https://linux-hardware.org/?probe=5e66adbc36) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | Desktop     | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| Intel         | NUC7i5BNB J31144-314        | Mini pc     | [8e5fbbccbf](https://linux-hardware.org/?probe=8e5fbbccbf) | Jul 06, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [818272b52c](https://linux-hardware.org/?probe=818272b52c) | Jul 05, 2023 |
| Sony          | VPCEA1AGG                   | Notebook    | [edbc1fff31](https://linux-hardware.org/?probe=edbc1fff31) | Jul 05, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [356eae0e07](https://linux-hardware.org/?probe=356eae0e07) | Jul 05, 2023 |
| Acer          | Predator G9-591             | Notebook    | [3c20dda613](https://linux-hardware.org/?probe=3c20dda613) | Jul 05, 2023 |
| MSI           | 760GM-E51                   | Desktop     | [757eefb29d](https://linux-hardware.org/?probe=757eefb29d) | Jul 05, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ac446902dd](https://linux-hardware.org/?probe=ac446902dd) | Jul 05, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [df06d6577c](https://linux-hardware.org/?probe=df06d6577c) | Jul 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [8e16561151](https://linux-hardware.org/?probe=8e16561151) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [12e2330b5a](https://linux-hardware.org/?probe=12e2330b5a) | Jul 05, 2023 |
| HP            | 650                         | Notebook    | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [622cc306bf](https://linux-hardware.org/?probe=622cc306bf) | Jul 05, 2023 |
| Dell          | Latitude 3500               | Notebook    | [2ab8fe06f8](https://linux-hardware.org/?probe=2ab8fe06f8) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | Notebook    | [e8f0daea94](https://linux-hardware.org/?probe=e8f0daea94) | Jul 04, 2023 |
| HP            | 829A                        | Mini pc     | [b44dd014a4](https://linux-hardware.org/?probe=b44dd014a4) | Jul 04, 2023 |
| HP            | 829A                        | Mini pc     | [b44d11a69a](https://linux-hardware.org/?probe=b44d11a69a) | Jul 04, 2023 |
| Dell          | 081N4V A06                  | Server      | [a49814e5bd](https://linux-hardware.org/?probe=a49814e5bd) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [d47bc7229c](https://linux-hardware.org/?probe=d47bc7229c) | Jul 04, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [69e40b4481](https://linux-hardware.org/?probe=69e40b4481) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [39716dd662](https://linux-hardware.org/?probe=39716dd662) | Jul 03, 2023 |
| Samsung       | 950XED                      | Notebook    | [e81ef31b14](https://linux-hardware.org/?probe=e81ef31b14) | Jul 03, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4e2a9c1363](https://linux-hardware.org/?probe=4e2a9c1363) | Jul 03, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [45cdc9b462](https://linux-hardware.org/?probe=45cdc9b462) | Jul 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [275acaaa00](https://linux-hardware.org/?probe=275acaaa00) | Jul 03, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [9b1631574e](https://linux-hardware.org/?probe=9b1631574e) | Jul 03, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ce8989caa8](https://linux-hardware.org/?probe=ce8989caa8) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d17e5d7807](https://linux-hardware.org/?probe=d17e5d7807) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [29897719d5](https://linux-hardware.org/?probe=29897719d5) | Jul 03, 2023 |
| Dell          | Latitude 3500               | Notebook    | [4f287ac318](https://linux-hardware.org/?probe=4f287ac318) | Jul 03, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [eaeac1cc79](https://linux-hardware.org/?probe=eaeac1cc79) | Jul 03, 2023 |
| Sony          | VPCEA1AGG                   | Notebook    | [de28a65daa](https://linux-hardware.org/?probe=de28a65daa) | Jul 02, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [9d82f4cd8a](https://linux-hardware.org/?probe=9d82f4cd8a) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [51d003ae6a](https://linux-hardware.org/?probe=51d003ae6a) | Jul 02, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [033ce7c13d](https://linux-hardware.org/?probe=033ce7c13d) | Jul 02, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [8f6145f929](https://linux-hardware.org/?probe=8f6145f929) | Jul 02, 2023 |
| ASRock        | P67 Performance             | Desktop     | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | Desktop     | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | Desktop     | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| Intel         | H55                         | Desktop     | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d703fd9378](https://linux-hardware.org/?probe=d703fd9378) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [6ad6d2e8c6](https://linux-hardware.org/?probe=6ad6d2e8c6) | Jul 02, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [261bb38239](https://linux-hardware.org/?probe=261bb38239) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | Notebook    | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [48195d85f8](https://linux-hardware.org/?probe=48195d85f8) | Jul 02, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [079e6d2d51](https://linux-hardware.org/?probe=079e6d2d51) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [5248df0795](https://linux-hardware.org/?probe=5248df0795) | Jul 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [079de94ff1](https://linux-hardware.org/?probe=079de94ff1) | Jul 01, 2023 |
| Dell          | Latitude E6410              | Notebook    | [675794fe6e](https://linux-hardware.org/?probe=675794fe6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [c66f880677](https://linux-hardware.org/?probe=c66f880677) | Jul 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [a1a9486fc8](https://linux-hardware.org/?probe=a1a9486fc8) | Jul 01, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ef05796af7](https://linux-hardware.org/?probe=ef05796af7) | Jul 01, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| Timi          | TM1701                      | Notebook    | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ea8982e574](https://linux-hardware.org/?probe=ea8982e574) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | Notebook    | [88b4565c0b](https://linux-hardware.org/?probe=88b4565c0b) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | Notebook    | [7e1b98b585](https://linux-hardware.org/?probe=7e1b98b585) | Jul 01, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [189320a2cf](https://linux-hardware.org/?probe=189320a2cf) | Jul 01, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2ee9ffdaa0](https://linux-hardware.org/?probe=2ee9ffdaa0) | Jun 30, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [6ab7575bed](https://linux-hardware.org/?probe=6ab7575bed) | Jun 30, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [fa055ceb7c](https://linux-hardware.org/?probe=fa055ceb7c) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [951adb91cd](https://linux-hardware.org/?probe=951adb91cd) | Jun 30, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [99a03772fb](https://linux-hardware.org/?probe=99a03772fb) | Jun 30, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [2d7ee2c4a8](https://linux-hardware.org/?probe=2d7ee2c4a8) | Jun 30, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| Dell          | Latitude 5440               | Notebook    | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [35871c9acc](https://linux-hardware.org/?probe=35871c9acc) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Acer          | NC-A515-51G-59DM            | Notebook    | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | Desktop     | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | Notebook    | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [6147d58cdf](https://linux-hardware.org/?probe=6147d58cdf) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | Notebook    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [506c909e37](https://linux-hardware.org/?probe=506c909e37) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ad91997e3e](https://linux-hardware.org/?probe=ad91997e3e) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [e2ea94e083](https://linux-hardware.org/?probe=e2ea94e083) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [058c58505d](https://linux-hardware.org/?probe=058c58505d) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | Notebook    | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | Notebook    | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [742d015edb](https://linux-hardware.org/?probe=742d015edb) | Jun 26, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [6c659f8e1f](https://linux-hardware.org/?probe=6c659f8e1f) | Jun 26, 2023 |
| Daten Tecn... | ESTELAR                     | Notebook    | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [076507dc77](https://linux-hardware.org/?probe=076507dc77) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [544c014552](https://linux-hardware.org/?probe=544c014552) | Jun 26, 2023 |
| Gateway       | NV57H                       | Notebook    | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Gateway       | NV57H                       | Notebook    | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | Notebook    | [70a6547925](https://linux-hardware.org/?probe=70a6547925) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | Notebook    | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | Desktop     | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [0ab63facb3](https://linux-hardware.org/?probe=0ab63facb3) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | Notebook    | [1809b4709e](https://linux-hardware.org/?probe=1809b4709e) | Jun 25, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [2e20ab8996](https://linux-hardware.org/?probe=2e20ab8996) | Jun 25, 2023 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [94afcaf73d](https://linux-hardware.org/?probe=94afcaf73d) | Jun 25, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 545       | 37.87%  |
| 6.2.0-26-generic        | 112       | 7.78%   |
| 6.2.0-27-generic        | 107       | 7.44%   |
| 6.2.0-25-generic        | 101       | 7.02%   |
| 6.2.0-24-generic        | 99        | 6.88%   |
| 6.2.0-32-generic        | 91        | 6.32%   |
| 6.2.0-23-generic        | 81        | 5.63%   |
| 6.2.0-33-generic        | 69        | 4.79%   |
| 6.2.0-31-generic        | 48        | 3.34%   |
| 5.19.0-21-generic       | 20        | 1.39%   |
| 6.2.0-18-generic        | 13        | 0.9%    |
| 6.4.0-060400-generic    | 8         | 0.56%   |
| 5.19.0-41-generic       | 8         | 0.56%   |
| 6.3.2-060302-generic    | 6         | 0.42%   |
| 6.1.0-16-generic        | 6         | 0.42%   |
| 5.19.0-46-generic       | 6         | 0.42%   |
| 6.3.4-060304-generic    | 4         | 0.28%   |
| 6.2.0-1004-raspi        | 4         | 0.28%   |
| 6.5.0-060500-generic    | 3         | 0.21%   |
| 6.3.6-060306-generic    | 3         | 0.21%   |
| 6.2.9-060209-generic    | 3         | 0.21%   |
| 6.2.0-19-generic        | 3         | 0.21%   |
| 6.2.0-1003-lowlatency   | 3         | 0.21%   |
| 5.19.0-40-generic       | 3         | 0.21%   |
| 5.19.0-31-generic       | 3         | 0.21%   |
| 5.19.0-28-generic       | 3         | 0.21%   |
| 6.5.1-060501-generic    | 2         | 0.14%   |
| 6.5.0-060500rc5-generic | 2         | 0.14%   |
| 6.4.7-t2-lunar          | 2         | 0.14%   |
| 6.4.6-060406-generic    | 2         | 0.14%   |
| 6.3.7-060307-generic    | 2         | 0.14%   |
| 6.3.5-060305-generic    | 2         | 0.14%   |
| 6.2.12-060212-generic   | 2         | 0.14%   |
| 6.2.11-060211-generic   | 2         | 0.14%   |
| 6.2.0-1012-raspi        | 2         | 0.14%   |
| 6.2.0-1007-lowlatency   | 2         | 0.14%   |
| 6.2.0-060200-generic    | 2         | 0.14%   |
| 5.19.0-45-generic       | 2         | 0.14%   |
| 5.19.0-42-generic       | 2         | 0.14%   |
| 5.19.0-38-generic       | 2         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.2.0    | 1219      | 89.37%  |
| 5.19.0   | 57        | 4.18%   |
| 6.4.0    | 9         | 0.66%   |
| 6.1.0    | 7         | 0.51%   |
| 6.3.2    | 6         | 0.44%   |
| 6.3.0    | 5         | 0.37%   |
| 6.5.0    | 4         | 0.29%   |
| 6.3.4    | 4         | 0.29%   |
| 5.14.0   | 4         | 0.29%   |
| 6.5.1    | 3         | 0.22%   |
| 6.4.7    | 3         | 0.22%   |
| 6.3.6    | 3         | 0.22%   |
| 6.2.9    | 3         | 0.22%   |
| 6.5.3    | 2         | 0.15%   |
| 6.4.8    | 2         | 0.15%   |
| 6.4.6    | 2         | 0.15%   |
| 6.3.7    | 2         | 0.15%   |
| 6.3.5    | 2         | 0.15%   |
| 6.3.1    | 2         | 0.15%   |
| 6.2.12   | 2         | 0.15%   |
| 6.2.11   | 2         | 0.15%   |
| 5.15.0   | 2         | 0.15%   |
| 6.5.5    | 1         | 0.07%   |
| 6.5.4    | 1         | 0.07%   |
| 6.5.2    | 1         | 0.07%   |
| 6.4.5    | 1         | 0.07%   |
| 6.4.3    | 1         | 0.07%   |
| 6.4.2    | 1         | 0.07%   |
| 6.4.12   | 1         | 0.07%   |
| 6.3.8    | 1         | 0.07%   |
| 6.3.3    | 1         | 0.07%   |
| 6.2.6    | 1         | 0.07%   |
| 6.2.16   | 1         | 0.07%   |
| 6.2.10   | 1         | 0.07%   |
| 6.1.12   | 1         | 0.07%   |
| 6.0.9    | 1         | 0.07%   |
| 5.19.5   | 1         | 0.07%   |
| 5.19.17  | 1         | 0.07%   |
| 5.17.0   | 1         | 0.07%   |
| 5.15.108 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1227      | 90.29%  |
| 5.19    | 59        | 4.34%   |
| 6.3     | 26        | 1.91%   |
| 6.4     | 18        | 1.32%   |
| 6.5     | 11        | 0.81%   |
| 6.1     | 8         | 0.59%   |
| 5.14    | 4         | 0.29%   |
| 5.15    | 3         | 0.22%   |
| 6.0     | 1         | 0.07%   |
| 5.17    | 1         | 0.07%   |
| 5.11    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1339      | 99.26%  |
| aarch64 | 8         | 0.59%   |
| riscv64 | 1         | 0.07%   |
| armv7l  | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1302      | 96.44%  |
| X-Cinnamon      | 19        | 1.41%   |
| Unknown         | 19        | 1.41%   |
| GNOME Flashback | 4         | 0.3%    |
| sway            | 2         | 0.15%   |
| i3              | 2         | 0.15%   |
| mwm             | 1         | 0.07%   |
| GNOME Classic   | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 898       | 65.64%  |
| X11     | 438       | 32.02%  |
| Unknown | 17        | 1.24%   |
| Tty     | 15        | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 1192      | 88.17%  |
| Unknown | 126       | 9.32%   |
| LightDM | 27        | 2%      |
| GDM     | 5         | 0.37%   |
| SDDM    | 1         | 0.07%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 632       | 46.64%  |
| de_DE   | 159       | 11.73%  |
| fr_FR   | 76        | 5.61%   |
| C       | 60        | 4.43%   |
| pt_BR   | 53        | 3.91%   |
| es_ES   | 50        | 3.69%   |
| en_GB   | 39        | 2.88%   |
| ru_RU   | 38        | 2.8%    |
| it_IT   | 31        | 2.29%   |
| en_CA   | 23        | 1.7%    |
| pl_PL   | 19        | 1.4%    |
| en_AU   | 18        | 1.33%   |
| nl_NL   | 12        | 0.89%   |
| en_IN   | 8         | 0.59%   |
| cs_CZ   | 8         | 0.59%   |
| Unknown | 8         | 0.59%   |
| sv_SE   | 7         | 0.52%   |
| hu_HU   | 7         | 0.52%   |
| fi_FI   | 7         | 0.52%   |
| de_AT   | 7         | 0.52%   |
| fr_CA   | 6         | 0.44%   |
| es_MX   | 6         | 0.44%   |
| bg_BG   | 6         | 0.44%   |
| zh_CN   | 5         | 0.37%   |
| pt_PT   | 5         | 0.37%   |
| el_GR   | 5         | 0.37%   |
| tr_TR   | 4         | 0.3%    |
| nb_NO   | 4         | 0.3%    |
| ja_JP   | 4         | 0.3%    |
| ro_RO   | 3         | 0.22%   |
| en_ZA   | 3         | 0.22%   |
| en_NZ   | 3         | 0.22%   |
| en_IL   | 3         | 0.22%   |
| de_CH   | 3         | 0.22%   |
| ca_ES   | 3         | 0.22%   |
| zh_TW   | 2         | 0.15%   |
| lt_LT   | 2         | 0.15%   |
| ko_KR   | 2         | 0.15%   |
| es_CL   | 2         | 0.15%   |
| es_AR   | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 826       | 60.87%  |
| EFI  | 531       | 39.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Tmpfs   | 717       | 52.88%  |
| Ext4    | 584       | 43.07%  |
| Overlay | 27        | 1.99%   |
| Btrfs   | 14        | 1.03%   |
| Zfs     | 10        | 0.74%   |
| XXX4    | 2         | 0.15%   |
| Xfs     | 2         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1163      | 85.96%  |
| Unknown | 109       | 8.06%   |
| MBR     | 81        | 5.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1190      | 87.56%  |
| Yes       | 169       | 12.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 862       | 63.38%  |
| Yes       | 498       | 36.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 217       | 16.09%  |
| ASUSTek Computer                     | 214       | 15.86%  |
| Hewlett-Packard                      | 189       | 14.01%  |
| Dell                                 | 163       | 12.08%  |
| Acer                                 | 84        | 6.23%   |
| MSI                                  | 76        | 5.63%   |
| Gigabyte Technology                  | 57        | 4.23%   |
| Apple                                | 52        | 3.85%   |
| ASRock                               | 33        | 2.45%   |
| Intel                                | 27        | 2%      |
| HUAWEI                               | 27        | 2%      |
| Unknown                              | 17        | 1.26%   |
| Toshiba                              | 13        | 0.96%   |
| Samsung Electronics                  | 13        | 0.96%   |
| Fujitsu                              | 10        | 0.74%   |
| Raspberry Pi Foundation              | 9         | 0.67%   |
| Microsoft                            | 9         | 0.67%   |
| Google                               | 9         | 0.67%   |
| Sony                                 | 8         | 0.59%   |
| Notebook                             | 8         | 0.59%   |
| Timi                                 | 7         | 0.52%   |
| AZW                                  | 7         | 0.52%   |
| Razer                                | 4         | 0.3%    |
| Packard Bell                         | 4         | 0.3%    |
| Medion                               | 4         | 0.3%    |
| Infinix                              | 4         | 0.3%    |
| Biostar                              | 4         | 0.3%    |
| Shanghai Zhaoxin Semiconductor       | 3         | 0.22%   |
| Positivo                             | 3         | 0.22%   |
| Panasonic                            | 3         | 0.22%   |
| Gateway                              | 3         | 0.22%   |
| Alienware                            | 3         | 0.22%   |
| ZOTAC                                | 2         | 0.15%   |
| Supermicro                           | 2         | 0.15%   |
| Shuttle                              | 2         | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.15%   |
| Pegatron                             | 2         | 0.15%   |
| MACHINIST                            | 2         | 0.15%   |
| Huanan                               | 2         | 0.15%   |
| HONOR                                | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 21        | 1.56%   |
| ASUS All Series                    | 8         | 0.59%   |
| HP EliteBook 840 G6                | 6         | 0.44%   |
| Dell Latitude 7480                 | 5         | 0.37%   |
| HUAWEI BOM-WXX9                    | 4         | 0.3%    |
| HP Notebook                        | 4         | 0.3%    |
| Apple MacBookPro9,2                | 4         | 0.3%    |
| Apple MacBookAir7,2                | 4         | 0.3%    |
| Shanghai Zhaoxin ZXE CRB           | 3         | 0.22%   |
| RPi Raspberry Pi                   | 3         | 0.22%   |
| MSI MS-7C95                        | 3         | 0.22%   |
| MSI Modern 14 A10M                 | 3         | 0.22%   |
| Microsoft Surface Pro 7            | 3         | 0.22%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7   | 3         | 0.22%   |
| Lenovo G50-70 20351                | 3         | 0.22%   |
| HUAWEI BOHB-WAX9                   | 3         | 0.22%   |
| HP ZBook Studio G3                 | 3         | 0.22%   |
| Gigabyte B450M DS3H                | 3         | 0.22%   |
| Dell XPS 15 9500                   | 3         | 0.22%   |
| Dell Precision 5570                | 3         | 0.22%   |
| Dell Latitude E6420                | 3         | 0.22%   |
| Dell Inspiron 3442                 | 3         | 0.22%   |
| Dell G5 5590                       | 3         | 0.22%   |
| AZW SER                            | 3         | 0.22%   |
| AZW GTR                            | 3         | 0.22%   |
| ASUS ZenBook UX325EA_UX325EA       | 3         | 0.22%   |
| ASUS Zenbook UM5302TA_UM5302TA     | 3         | 0.22%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 3         | 0.22%   |
| Apple MacPro5,1                    | 3         | 0.22%   |
| Apple MacBookPro5,5                | 3         | 0.22%   |
| Acer Swift SF314-512               | 3         | 0.22%   |
| Acer Aspire E5-575G                | 3         | 0.22%   |
| Acer Aspire E1-572G                | 3         | 0.22%   |
| Toshiba Satellite Pro C70-B        | 2         | 0.15%   |
| Timi Redmi Book Pro 14 2022        | 2         | 0.15%   |
| Samsung P500A2D                    | 2         | 0.15%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 2         | 0.15%   |
| Packard Bell EasyNote ENTF71BM     | 2         | 0.15%   |
| MSI Stealth 15M B12UE              | 2         | 0.15%   |
| MSI MS-7C96                        | 2         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 98        | 7.26%   |
| Dell Latitude      | 50        | 3.71%   |
| Acer Aspire        | 47        | 3.48%   |
| Lenovo IdeaPad     | 35        | 2.59%   |
| Dell Inspiron      | 35        | 2.59%   |
| ASUS PRIME         | 35        | 2.59%   |
| HP EliteBook       | 33        | 2.45%   |
| Dell XPS           | 26        | 1.93%   |
| ASUS VivoBook      | 25        | 1.85%   |
| ASUS ROG           | 25        | 1.85%   |
| HP Pavilion        | 24        | 1.78%   |
| HP Laptop          | 24        | 1.78%   |
| ASUS Zenbook       | 22        | 1.63%   |
| Unknown            | 21        | 1.56%   |
| HP ENVY            | 20        | 1.48%   |
| ASUS TUF           | 19        | 1.41%   |
| Dell OptiPlex      | 18        | 1.33%   |
| Lenovo Yoga        | 16        | 1.19%   |
| HP ProBook         | 15        | 1.11%   |
| Dell Precision     | 15        | 1.11%   |
| Acer Swift         | 13        | 0.96%   |
| Acer Nitro         | 13        | 0.96%   |
| Lenovo ThinkCentre | 12        | 0.89%   |
| Lenovo IdeaPadFlex | 10        | 0.74%   |
| ASUS ASUS          | 10        | 0.74%   |
| RPi Raspberry      | 9         | 0.67%   |
| Microsoft Surface  | 9         | 0.67%   |
| Lenovo Legion      | 9         | 0.67%   |
| Toshiba Satellite  | 8         | 0.59%   |
| ASUS All           | 8         | 0.59%   |
| HP EliteDesk       | 7         | 0.52%   |
| HP Compaq          | 7         | 0.52%   |
| Dell Vostro        | 7         | 0.52%   |
| Lenovo ThinkBook   | 6         | 0.44%   |
| MSI Stealth        | 5         | 0.37%   |
| Lenovo IdeaCentre  | 5         | 0.37%   |
| HP ZBook           | 5         | 0.37%   |
| HP ProDesk         | 5         | 0.37%   |
| Fujitsu ESPRIMO    | 5         | 0.37%   |
| Toshiba PORTEGE    | 4         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 172       | 12.75%  |
| 2022    | 171       | 12.68%  |
| 2020    | 140       | 10.38%  |
| 2019    | 106       | 7.86%   |
| 2018    | 87        | 6.45%   |
| 2017    | 80        | 5.93%   |
| 2012    | 77        | 5.71%   |
| 2023    | 75        | 5.56%   |
| 2016    | 69        | 5.11%   |
| 2014    | 69        | 5.11%   |
| 2015    | 67        | 4.97%   |
| 2011    | 60        | 4.45%   |
| 2013    | 59        | 4.37%   |
| 2010    | 48        | 3.56%   |
| 2009    | 27        | 2%      |
| 2008    | 20        | 1.48%   |
| Unknown | 11        | 0.82%   |
| 2007    | 8         | 0.59%   |
| 2006    | 3         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 757       | 56.12%  |
| Desktop        | 411       | 30.47%  |
| Convertible    | 86        | 6.38%   |
| Mini pc        | 30        | 2.22%   |
| All in one     | 24        | 1.78%   |
| Tablet         | 23        | 1.7%    |
| System on chip | 10        | 0.74%   |
| Server         | 8         | 0.59%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1218      | 90.02%  |
| Enabled  | 135       | 9.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1338      | 99.18%  |
| Yes  | 11        | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 352       | 26.02%  |
| 16.01-24.0      | 299       | 22.1%   |
| 8.01-16.0       | 223       | 16.48%  |
| 3.01-4.0        | 171       | 12.64%  |
| 32.01-64.0      | 164       | 12.12%  |
| 64.01-256.0     | 69        | 5.1%    |
| 24.01-32.0      | 51        | 3.77%   |
| 1.01-2.0        | 13        | 0.96%   |
| 2.01-3.0        | 6         | 0.44%   |
| More than 256.0 | 3         | 0.22%   |
| 0.51-1.0        | 1         | 0.07%   |
| 0.01-0.5        | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 440       | 31.52%  |
| 1.01-2.0   | 333       | 23.85%  |
| 4.01-8.0   | 299       | 21.42%  |
| 3.01-4.0   | 242       | 17.34%  |
| 8.01-16.0  | 58        | 4.15%   |
| 16.01-24.0 | 8         | 0.57%   |
| 0.51-1.0   | 5         | 0.36%   |
| 32.01-64.0 | 4         | 0.29%   |
| 24.01-32.0 | 4         | 0.29%   |
| 0.01-0.5   | 3         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 895       | 65.71%  |
| 2      | 293       | 21.51%  |
| 3      | 87        | 6.39%   |
| 4      | 41        | 3.01%   |
| 5      | 20        | 1.47%   |
| 6      | 14        | 1.03%   |
| 0      | 4         | 0.29%   |
| 8      | 3         | 0.22%   |
| 7      | 3         | 0.22%   |
| 11     | 1         | 0.07%   |
| 9      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1014      | 75%     |
| Yes       | 338       | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1034      | 76.48%  |
| No        | 318       | 23.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1131      | 83.78%  |
| No        | 219       | 16.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 980       | 72.27%  |
| No        | 376       | 27.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 226       | 16.74%  |
| Germany      | 176       | 13.04%  |
| France       | 82        | 6.07%   |
| Brazil       | 72        | 5.33%   |
| Canada       | 62        | 4.59%   |
| UK           | 57        | 4.22%   |
| Russia       | 57        | 4.22%   |
| Italy        | 55        | 4.07%   |
| Australia    | 33        | 2.44%   |
| Spain        | 32        | 2.37%   |
| India        | 30        | 2.22%   |
| Netherlands  | 26        | 1.93%   |
| Poland       | 22        | 1.63%   |
| Switzerland  | 18        | 1.33%   |
| Sweden       | 18        | 1.33%   |
| Mexico       | 18        | 1.33%   |
| Norway       | 17        | 1.26%   |
| Finland      | 17        | 1.26%   |
| Austria      | 17        | 1.26%   |
| Czechia      | 16        | 1.19%   |
| Turkey       | 15        | 1.11%   |
| Portugal     | 14        | 1.04%   |
| Romania      | 13        | 0.96%   |
| Hungary      | 13        | 0.96%   |
| China        | 13        | 0.96%   |
| Belgium      | 13        | 0.96%   |
| Greece       | 10        | 0.74%   |
| Chile        | 10        | 0.74%   |
| Indonesia    | 9         | 0.67%   |
| South Africa | 8         | 0.59%   |
| Argentina    | 8         | 0.59%   |
| Serbia       | 7         | 0.52%   |
| Philippines  | 7         | 0.52%   |
| Pakistan     | 7         | 0.52%   |
| Japan        | 7         | 0.52%   |
| Israel       | 7         | 0.52%   |
| Ireland      | 7         | 0.52%   |
| Bulgaria     | 7         | 0.52%   |
| Malaysia     | 6         | 0.44%   |
| Colombia     | 6         | 0.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 19        | 1.38%   |
| Moscow            | 17        | 1.24%   |
| Berlin            | 14        | 1.02%   |
| Helsinki          | 12        | 0.87%   |
| Melbourne         | 11        | 0.8%    |
| Montreal          | 10        | 0.73%   |
| St Petersburg     | 9         | 0.65%   |
| Oslo              | 9         | 0.65%   |
| Prague            | 8         | 0.58%   |
| Hamburg           | 8         | 0.58%   |
| Barcelona         | 8         | 0.58%   |
| Brisbane          | 7         | 0.51%   |
| Warsaw            | 6         | 0.44%   |
| Vienna            | 6         | 0.44%   |
| Valencia          | 6         | 0.44%   |
| Oshawa            | 6         | 0.44%   |
| Munich            | 6         | 0.44%   |
| Atlanta           | 6         | 0.44%   |
| Toronto           | 5         | 0.36%   |
| Tokyo             | 5         | 0.36%   |
| Sydney            | 5         | 0.36%   |
| Rome              | 5         | 0.36%   |
| Rio de Janeiro    | 5         | 0.36%   |
| New York          | 5         | 0.36%   |
| Nairobi           | 5         | 0.36%   |
| Milan             | 5         | 0.36%   |
| Frankfurt am Main | 5         | 0.36%   |
| Essen             | 5         | 0.36%   |
| Edmonton          | 5         | 0.36%   |
| Düsseldorf       | 5         | 0.36%   |
| Denver            | 5         | 0.36%   |
| Cologne           | 5         | 0.36%   |
| Budapest          | 5         | 0.36%   |
| Brussels          | 5         | 0.36%   |
| Belgrade          | 5         | 0.36%   |
| Beijing           | 5         | 0.36%   |
| Zurich            | 4         | 0.29%   |
| Tehran            | 4         | 0.29%   |
| Sofia             | 4         | 0.29%   |
| Seattle           | 4         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 339       | 436    | 17.85%  |
| Seagate                     | 214       | 279    | 11.27%  |
| WDC                         | 191       | 254    | 10.06%  |
| SanDisk                     | 131       | 161    | 6.9%    |
| Kingston                    | 98        | 111    | 5.16%   |
| SK hynix                    | 76        | 81     | 4%      |
| Toshiba                     | 75        | 84     | 3.95%   |
| Unknown                     | 71        | 84     | 3.74%   |
| Intel                       | 67        | 79     | 3.53%   |
| Crucial                     | 64        | 71     | 3.37%   |
| Micron Technology           | 63        | 81     | 3.32%   |
| KIOXIA                      | 38        | 42     | 2%      |
| Hitachi                     | 33        | 43     | 1.74%   |
| Phison Electronics          | 27        | 33     | 1.42%   |
| Apple                       | 27        | 33     | 1.42%   |
| Kingston Technology Company | 22        | 27     | 1.16%   |
| China                       | 20        | 22     | 1.05%   |
| Micron/Crucial Technology   | 18        | 21     | 0.95%   |
| HGST                        | 17        | 19     | 0.9%    |
| A-DATA Technology           | 15        | 19     | 0.79%   |
| Phison                      | 12        | 13     | 0.63%   |
| Intenso                     | 12        | 16     | 0.63%   |
| Silicon Motion              | 11        | 11     | 0.58%   |
| Unknown                     | 11        | 14     | 0.58%   |
| ADATA Technology            | 8         | 10     | 0.42%   |
| SPCC                        | 7         | 7      | 0.37%   |
| Patriot                     | 7         | 7      | 0.37%   |
| MAXIO Technology (Hangzhou) | 7         | 7      | 0.37%   |
| FORESEE                     | 7         | 8      | 0.37%   |
| PNY                         | 6         | 8      | 0.32%   |
| LITEONIT                    | 6         | 7      | 0.32%   |
| LITEON                      | 6         | 9      | 0.32%   |
| Lexar                       | 6         | 6      | 0.32%   |
| Gigabyte Technology         | 6         | 6      | 0.32%   |
| ASMT                        | 6         | 8      | 0.32%   |
| Transcend                   | 5         | 5      | 0.26%   |
| Team                        | 5         | 5      | 0.26%   |
| Realtek Semiconductor       | 5         | 6      | 0.26%   |
| OCZ                         | 5         | 5      | 0.26%   |
| Netac                       | 5         | 5      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 46        | 2.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 26        | 1.27%   |
| Kingston SA400S37240G 240GB SSD                       | 21        | 1.03%   |
| Unknown MMC Card  64GB                                | 19        | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 17        | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                        | 16        | 0.78%   |
| Samsung SSD 850 EVO 250GB                             | 14        | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB   | 14        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                        | 13        | 0.64%   |
| Samsung SSD 980 1TB                                   | 13        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                       | 13        | 0.64%   |
| Unknown MMC Card  128GB                               | 12        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 11        | 0.54%   |
| Phison E12 NVMe Controller 2TB                        | 11        | 0.54%   |
| Unknown                                               | 11        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 10        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                          | 10        | 0.49%   |
| Samsung SSD 860 EVO 500GB                             | 10        | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 9         | 0.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 9         | 0.44%   |
| Samsung SSD 870 EVO 500GB                             | 9         | 0.44%   |
| Samsung SSD 870 EVO 1TB                               | 9         | 0.44%   |
| HGST HTS721010A9E630 1TB                              | 9         | 0.44%   |
| Crucial CT500MX500SSD1 500GB                          | 9         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 8         | 0.39%   |
| Unknown MMC Card  32GB                                | 8         | 0.39%   |
| Seagate ST3500418AS 500GB                             | 8         | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB                        | 8         | 0.39%   |
| Samsung SSD 850 EVO 500GB                             | 8         | 0.39%   |
| Micron 2450_MTFDKBA1T0TFK 1024GB                      | 8         | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                      | 8         | 0.39%   |
| Intel SSDPEKNU512GZ 512GB                             | 8         | 0.39%   |
| Intel SSD 660P Series 1024GB                          | 8         | 0.39%   |
| Toshiba XG6 NVMe SSD Controller 512GB                 | 7         | 0.34%   |
| Seagate ST2000LM007-1R8174 2TB                        | 7         | 0.34%   |
| SanDisk NVMe SSD Drive 1TB                            | 7         | 0.34%   |
| Samsung SSD 990 PRO 1TB                               | 7         | 0.34%   |
| Samsung SSD 860 EVO 250GB                             | 7         | 0.34%   |
| Samsung SSD 860 EVO 1TB                               | 7         | 0.34%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 7         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 204       | 267    | 41.21%  |
| WDC                 | 142       | 190    | 28.69%  |
| Toshiba             | 51        | 58     | 10.3%   |
| Hitachi             | 33        | 43     | 6.67%   |
| Samsung Electronics | 21        | 24     | 4.24%   |
| HGST                | 17        | 19     | 3.43%   |
| Unknown             | 6         | 7      | 1.21%   |
| Apple               | 6         | 6      | 1.21%   |
| SABRENT             | 4         | 7      | 0.81%   |
| Maxtor              | 2         | 3      | 0.4%    |
| HGST HTS            | 2         | 2      | 0.4%    |
| USB3.0              | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| Intenso             | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Fujitsu             | 1         | 1      | 0.2%    |
| ASMT                | 1         | 3      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 126       | 160    | 21.65%  |
| Kingston            | 72        | 84     | 12.37%  |
| SanDisk             | 52        | 65     | 8.93%   |
| Crucial             | 52        | 56     | 8.93%   |
| WDC                 | 32        | 38     | 5.5%    |
| China               | 20        | 22     | 3.44%   |
| Intel               | 16        | 18     | 2.75%   |
| Apple               | 14        | 15     | 2.41%   |
| SK hynix            | 13        | 13     | 2.23%   |
| Micron Technology   | 13        | 22     | 2.23%   |
| A-DATA Technology   | 11        | 15     | 1.89%   |
| Intenso             | 9         | 12     | 1.55%   |
| Patriot             | 7         | 7      | 1.2%    |
| Toshiba             | 6         | 7      | 1.03%   |
| LITEONIT            | 6         | 7      | 1.03%   |
| LITEON              | 6         | 9      | 1.03%   |
| Team                | 5         | 5      | 0.86%   |
| SPCC                | 5         | 5      | 0.86%   |
| PNY                 | 5         | 6      | 0.86%   |
| OCZ                 | 5         | 5      | 0.86%   |
| Lexar               | 5         | 5      | 0.86%   |
| KingSpec            | 5         | 6      | 0.86%   |
| ASMT                | 5         | 5      | 0.86%   |
| Apacer              | 5         | 6      | 0.86%   |
| Unknown             | 5         | 5      | 0.86%   |
| GOODRAM             | 4         | 5      | 0.69%   |
| Gigabyte Technology | 4         | 4      | 0.69%   |
| Transcend           | 3         | 3      | 0.52%   |
| OWC                 | 3         | 7      | 0.52%   |
| Netac               | 3         | 3      | 0.52%   |
| Verbatim            | 2         | 7      | 0.34%   |
| Vaseky              | 2         | 2      | 0.34%   |
| Smartbuy            | 2         | 3      | 0.34%   |
| KingDian            | 2         | 2      | 0.34%   |
| Kingchuxing         | 2         | 2      | 0.34%   |
| JMicron Technology  | 2         | 2      | 0.34%   |
| INNOVATION IT       | 2         | 2      | 0.34%   |
| Hewlett-Packard     | 2         | 2      | 0.34%   |
| Gigastone           | 2         | 2      | 0.34%   |
| FORESEE             | 2         | 2      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 694       | 882    | 40.09%  |
| SSD     | 517       | 694    | 29.87%  |
| HDD     | 431       | 635    | 24.9%   |
| MMC     | 64        | 77     | 3.7%    |
| Unknown | 25        | 29     | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 762       | 1261   | 47.63%  |
| NVMe | 694       | 878    | 43.38%  |
| SAS  | 80        | 101    | 5%      |
| MMC  | 64        | 77     | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 547       | 737    | 55.36%  |
| 0.51-1.0   | 292       | 386    | 29.55%  |
| 1.01-2.0   | 82        | 112    | 8.3%    |
| 3.01-4.0   | 24        | 36     | 2.43%   |
| 4.01-10.0  | 23        | 34     | 2.33%   |
| 2.01-3.0   | 13        | 16     | 1.32%   |
| 10.01-20.0 | 7         | 8      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 375       | 27.19%  |
| 101-250        | 373       | 27.05%  |
| 501-1000       | 238       | 17.26%  |
| 1001-2000      | 98        | 7.11%   |
| 51-100         | 72        | 5.22%   |
| More than 3000 | 65        | 4.71%   |
| 1-20           | 65        | 4.71%   |
| 21-50          | 45        | 3.26%   |
| 2001-3000      | 39        | 2.83%   |
| Unknown        | 9         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 450       | 32.23%  |
| 21-50          | 357       | 25.57%  |
| 101-250        | 168       | 12.03%  |
| 51-100         | 168       | 12.03%  |
| 251-500        | 111       | 7.95%   |
| 501-1000       | 57        | 4.08%   |
| 1001-2000      | 33        | 2.36%   |
| More than 3000 | 26        | 1.86%   |
| 2001-3000      | 17        | 1.22%   |
| Unknown        | 9         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2      | 3.28%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 2      | 3.28%   |
| WDC WD6400AACS-00G8B1 640GB             | 1         | 1      | 1.64%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1         | 1      | 1.64%   |
| WDC WD5000HHTZ-04N21V0 500GB            | 1         | 1      | 1.64%   |
| WDC WD5000AZLX-22JKKA0 500GB            | 1         | 1      | 1.64%   |
| WDC WD5000AAKX-001CA0 500GB             | 1         | 1      | 1.64%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1         | 1      | 1.64%   |
| WDC WD2500AAKX-753CA1 250GB             | 1         | 1      | 1.64%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 1      | 1.64%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1         | 1      | 1.64%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 1      | 1.64%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1         | 2      | 1.64%   |
| WDC WD10EARS-22Y5B1 1TB                 | 1         | 1      | 1.64%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1         | 1      | 1.64%   |
| WDC WD Green M.2 2280 240GB             | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.64%   |
| Toshiba MK5065GSXF 500GB                | 1         | 1      | 1.64%   |
| Toshiba MK3261GSYN 320GB                | 1         | 1      | 1.64%   |
| Toshiba MK2555GSXF 250GB                | 1         | 1      | 1.64%   |
| SSSTC CA6-8D2048-Q11 NVMe 2048GB        | 1         | 1      | 1.64%   |
| SK hynix BC711 HFM001TD3JX013N 1TB      | 1         | 1      | 1.64%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 1.64%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 1.64%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 1      | 1.64%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1      | 1.64%   |
| Seagate ST3500418AS 500GB               | 1         | 1      | 1.64%   |
| Seagate ST2000LX001-1RG174 2TB          | 1         | 1      | 1.64%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 1      | 1.64%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 1      | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1      | 1.64%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 1.64%   |
| SanDisk SDSSDX120GG25 120GB             | 1         | 1      | 1.64%   |
| SanDisk SD7SB2Q-512G-1006 512GB SSD     | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 960 EVO 250GB   | 1         | 1      | 1.64%   |
| Samsung Electronics HD502HJ 500GB       | 1         | 1      | 1.64%   |
| Samsung Electronics HD161GJ 160GB       | 1         | 1      | 1.64%   |
| Patriot P210 1TB SSD                    | 1         | 1      | 1.64%   |
| Neo Forza NFS121SA312-6007000 120GB SSD | 1         | 2      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 15     | 22.95%  |
| Seagate             | 11        | 11     | 18.03%  |
| Toshiba             | 5         | 5      | 8.2%    |
| Hitachi             | 5         | 6      | 8.2%    |
| Crucial             | 4         | 4      | 6.56%   |
| SanDisk             | 3         | 3      | 4.92%   |
| Samsung Electronics | 3         | 3      | 4.92%   |
| Kingston            | 3         | 3      | 4.92%   |
| Intel               | 2         | 2      | 3.28%   |
| HGST                | 2         | 2      | 3.28%   |
| SSSTC               | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| Patriot             | 1         | 1      | 1.64%   |
| Neo                 | 1         | 2      | 1.64%   |
| Maxtor              | 1         | 2      | 1.64%   |
| LITEONIT            | 1         | 1      | 1.64%   |
| Gigabyte Technology | 1         | 1      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |
| Unknown             | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 14     | 32.5%   |
| Seagate             | 11        | 11     | 27.5%   |
| Toshiba             | 5         | 5      | 12.5%   |
| Hitachi             | 5         | 6      | 12.5%   |
| Samsung Electronics | 2         | 2      | 5%      |
| HGST                | 2         | 2      | 5%      |
| Maxtor              | 1         | 2      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 43     | 65%     |
| SSD  | 17        | 18     | 28.33%  |
| NVMe | 4         | 4      | 6.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1         | 1      | 50%     |
| KingDian S400 120GB                 | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 1         | 1      | 50%     |
| KingDian | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 903       | 1589   | 63.5%   |
| Works    | 461       | 661    | 32.42%  |
| Malfunc  | 56        | 65     | 3.94%   |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 832       | 45.44%  |
| AMD                                     | 225       | 12.29%  |
| Samsung Electronics                     | 222       | 12.12%  |
| SanDisk                                 | 104       | 5.68%   |
| SK hynix                                | 62        | 3.39%   |
| Micron Technology                       | 50        | 2.73%   |
| Kingston Technology Company             | 47        | 2.57%   |
| Phison Electronics                      | 46        | 2.51%   |
| KIOXIA                                  | 35        | 1.91%   |
| Micron/Crucial Technology               | 32        | 1.75%   |
| Toshiba America Info Systems            | 23        | 1.26%   |
| ASMedia Technology                      | 19        | 1.04%   |
| Silicon Motion                          | 13        | 0.71%   |
| ADATA Technology                        | 12        | 0.66%   |
| Union Memory (Shenzhen)                 | 10        | 0.55%   |
| Nvidia                                  | 10        | 0.55%   |
| Shenzhen Longsys Electronics            | 9         | 0.49%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.49%   |
| Realtek Semiconductor                   | 8         | 0.44%   |
| Marvell Technology Group                | 8         | 0.44%   |
| Apple                                   | 8         | 0.44%   |
| Solid State Storage Technology          | 7         | 0.38%   |
| Seagate Technology                      | 7         | 0.38%   |
| JMicron Technology                      | 6         | 0.33%   |
| Zhaoxin                                 | 3         | 0.16%   |
| Yangtze Memory Technologies             | 3         | 0.16%   |
| Solidigm                                | 3         | 0.16%   |
| Broadcom / LSI                          | 3         | 0.16%   |
| Netac Technology                        | 2         | 0.11%   |
| LSI Logic / Symbios Logic               | 2         | 0.11%   |
| Lenovo                                  | 2         | 0.11%   |
| Hewlett-Packard                         | 2         | 0.11%   |
| VIA Technologies                        | 1         | 0.05%   |
| Transcend                               | 1         | 0.05%   |
| Silicon Image                           | 1         | 0.05%   |
| Shenzhen Unionmemory Information System | 1         | 0.05%   |
| OCZ Technology Group                    | 1         | 0.05%   |
| Lite-On Technology                      | 1         | 0.05%   |
| INNOGRIT                                | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 165       | 8.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 96        | 4.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 76        | 3.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 70        | 3.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 50        | 2.47%   |
| Samsung NVMe SSD Controller 980                                                | 43        | 2.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 43        | 2.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 40        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 39        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 34        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 27        | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 27        | 1.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 26        | 1.28%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 26        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 26        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 25        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 24        | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                         | 23        | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 21        | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 21        | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 20        | 0.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 20        | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 19        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 19        | 0.94%   |
| Intel Tiger Lake-LP SATA Controller                                            | 19        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19        | 0.94%   |
| Kingston Company Company Non-Volatile memory controller                        | 18        | 0.89%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 18        | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18        | 0.89%   |
| Intel SATA Controller [RAID mode]                                              | 17        | 0.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 17        | 0.84%   |
| Phison E12 NVMe Controller                                                     | 16        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 15        | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 0.74%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 14        | 0.69%   |
| Intel SSD 660P Series                                                          | 14        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 14        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 0.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 13        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 878       | 47.87%  |
| NVMe | 693       | 37.79%  |
| RAID | 176       | 9.6%    |
| IDE  | 85        | 4.63%   |
| SAS  | 2         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 1007      | 74.65%  |
| AMD           | 329       | 24.39%  |
| ARM           | 9         | 0.67%   |
| CentaurHauls  | 3         | 0.22%   |
| sifive,u74-mc | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 21        | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 20        | 1.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 14        | 1.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 14        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 13        | 0.96%   |
| Intel 12th Gen Core i7-12700H           | 13        | 0.96%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 12        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 11        | 0.81%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 11        | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 11        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 11        | 0.81%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 10        | 0.74%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 10        | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.67%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 9         | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor       | 9         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 8         | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 8         | 0.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 8         | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.59%   |
| Intel 12th Gen Core i7-1260P            | 8         | 0.59%   |
| Intel 12th Gen Core i5-1240P            | 8         | 0.59%   |
| ARM Processor                           | 8         | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 8         | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 8         | 0.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 7         | 0.52%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 7         | 0.52%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 7         | 0.52%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 7         | 0.52%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 7         | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 6         | 0.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 6         | 0.44%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 6         | 0.44%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 6         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 298       | 22.07%  |
| Other                   | 240       | 17.78%  |
| Intel Core i7           | 213       | 15.78%  |
| AMD Ryzen 7             | 96        | 7.11%   |
| AMD Ryzen 5             | 90        | 6.67%   |
| Intel Core i3           | 86        | 6.37%   |
| Intel Celeron           | 50        | 3.7%    |
| Intel Core 2 Duo        | 42        | 3.11%   |
| AMD Ryzen 9             | 42        | 3.11%   |
| Intel Xeon              | 32        | 2.37%   |
| Intel Pentium           | 18        | 1.33%   |
| AMD Ryzen 3             | 13        | 0.96%   |
| AMD A8                  | 11        | 0.81%   |
| Intel Pentium Silver    | 9         | 0.67%   |
| AMD Ryzen 5 PRO         | 9         | 0.67%   |
| Intel Atom              | 8         | 0.59%   |
| AMD Ryzen 7 PRO         | 8         | 0.59%   |
| AMD FX                  | 7         | 0.52%   |
| Intel Pentium Dual-Core | 6         | 0.44%   |
| AMD A4                  | 6         | 0.44%   |
| AMD A10                 | 6         | 0.44%   |
| Intel Core i9           | 5         | 0.37%   |
| Intel Core 2 Quad       | 5         | 0.37%   |
| AMD Phenom II X4        | 4         | 0.3%    |
| AMD E2                  | 4         | 0.3%    |
| AMD Athlon II X2        | 4         | 0.3%    |
| Intel Pentium Dual      | 3         | 0.22%   |
| Intel Core M            | 3         | 0.22%   |
| AMD Athlon              | 3         | 0.22%   |
| AMD A6                  | 3         | 0.22%   |
| AMD Turion 64 X2 Mobile | 2         | 0.15%   |
| AMD Ryzen Threadripper  | 2         | 0.15%   |
| AMD Athlon X4           | 2         | 0.15%   |
| Intel Xeon Silver       | 1         | 0.07%   |
| Intel Xeon Platinum     | 1         | 0.07%   |
| Intel Xeon Gold         | 1         | 0.07%   |
| Intel Pentium 4         | 1         | 0.07%   |
| Intel Genuine           | 1         | 0.07%   |
| Intel Core m7           | 1         | 0.07%   |
| Intel Core m3           | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 440       | 32.59%  |
| 2       | 425       | 31.48%  |
| 6       | 165       | 12.22%  |
| 8       | 152       | 11.26%  |
| 12      | 55        | 4.07%   |
| 14      | 37        | 2.74%   |
| 10      | 30        | 2.22%   |
| 16      | 14        | 1.04%   |
| 24      | 8         | 0.59%   |
| 1       | 6         | 0.44%   |
| 3       | 5         | 0.37%   |
| Unknown | 5         | 0.37%   |
| 32      | 2         | 0.15%   |
| 20      | 2         | 0.15%   |
| 52      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 7       | 1         | 0.07%   |
| 5       | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1331      | 98.67%  |
| 2       | 13        | 0.96%   |
| Unknown | 5         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 995       | 73.7%   |
| 1       | 350       | 25.93%  |
| Unknown | 5         | 0.37%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1345      | 99.7%   |
| 64-bit         | 2         | 0.15%   |
| Unknown        | 2         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1164      | 86.03%  |
| 0x0a50000d | 25        | 1.85%   |
| 0x0a601203 | 18        | 1.33%   |
| 0x0a50000c | 14        | 1.03%   |
| 0x08608103 | 14        | 1.03%   |
| 0x0a404102 | 13        | 0.96%   |
| 0x08600106 | 10        | 0.74%   |
| 0x906a3    | 5         | 0.37%   |
| 0x0a404101 | 5         | 0.37%   |
| 0x0a704101 | 4         | 0.3%    |
| 0x0a20120a | 4         | 0.3%    |
| 0x08701021 | 4         | 0.3%    |
| 0x08108109 | 4         | 0.3%    |
| 0x806ec    | 3         | 0.22%   |
| 0x08a00006 | 3         | 0.22%   |
| 0x08608102 | 3         | 0.22%   |
| 0x08600109 | 3         | 0.22%   |
| 0x08101016 | 3         | 0.22%   |
| 0x0800820d | 3         | 0.22%   |
| 0x010000c8 | 3         | 0.22%   |
| 0x306a9    | 2         | 0.15%   |
| 0x0a704103 | 2         | 0.15%   |
| 0x0a201025 | 2         | 0.15%   |
| 0x08701030 | 2         | 0.15%   |
| 0x08608104 | 2         | 0.15%   |
| 0x08600103 | 2         | 0.15%   |
| 0x08108102 | 2         | 0.15%   |
| 0x0810100b | 2         | 0.15%   |
| 0x06001119 | 2         | 0.15%   |
| 0xf64      | 1         | 0.07%   |
| 0x906ea    | 1         | 0.07%   |
| 0x90675    | 1         | 0.07%   |
| 0x806eb    | 1         | 0.07%   |
| 0x806d1    | 1         | 0.07%   |
| 0x806c1    | 1         | 0.07%   |
| 0x506e3    | 1         | 0.07%   |
| 0x406e3    | 1         | 0.07%   |
| 0x40651    | 1         | 0.07%   |
| 0x306d4    | 1         | 0.07%   |
| 0x306c3    | 1         | 0.07%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 209       | 15.44%  |
| Unknown          | 184       | 13.59%  |
| Haswell          | 91        | 6.72%   |
| Skylake          | 90        | 6.65%   |
| Zen 3            | 80        | 5.91%   |
| IvyBridge        | 77        | 5.69%   |
| TigerLake        | 76        | 5.61%   |
| Alderlake Hybrid | 71        | 5.24%   |
| SandyBridge      | 67        | 4.95%   |
| Zen 2            | 54        | 3.99%   |
| Penryn           | 46        | 3.4%    |
| Broadwell        | 38        | 2.81%   |
| IceLake          | 30        | 2.22%   |
| CometLake        | 28        | 2.07%   |
| Zen+             | 25        | 1.85%   |
| Goldmont plus    | 25        | 1.85%   |
| Westmere         | 24        | 1.77%   |
| Silvermont       | 21        | 1.55%   |
| Piledriver       | 18        | 1.33%   |
| Zen              | 15        | 1.11%   |
| K10              | 14        | 1.03%   |
| Core             | 13        | 0.96%   |
| Excavator        | 11        | 0.81%   |
| Goldmont         | 10        | 0.74%   |
| Nehalem          | 9         | 0.66%   |
| Puma             | 6         | 0.44%   |
| K8 Hammer        | 4         | 0.3%    |
| Tremont          | 3         | 0.22%   |
| Steamroller      | 2         | 0.15%   |
| NetBurst         | 2         | 0.15%   |
| K10 Llano        | 2         | 0.15%   |
| Jaguar           | 2         | 0.15%   |
| Gracemont        | 2         | 0.15%   |
| Bulldozer        | 2         | 0.15%   |
| Bobcat           | 2         | 0.15%   |
| Bonnell          | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 832       | 51.39%  |
| AMD                        | 391       | 24.15%  |
| Nvidia                     | 384       | 23.72%  |
| Matrox Electronics Systems | 7         | 0.43%   |
| Zhaoxin                    | 3         | 0.19%   |
| Silicon Motion             | 1         | 0.06%   |
| ASPEED Technology          | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 60        | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 54        | 3.28%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 41        | 2.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 40        | 2.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 38        | 2.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 37        | 2.25%   |
| Intel HD Graphics 620                                                       | 36        | 2.19%   |
| AMD Renoir                                                                  | 31        | 1.88%   |
| Intel UHD Graphics 620                                                      | 30        | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 30        | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 29        | 1.76%   |
| Intel HD Graphics 530                                                       | 27        | 1.64%   |
| AMD Lucienne                                                                | 27        | 1.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 26        | 1.58%   |
| AMD Rembrandt [Radeon 680M]                                                 | 26        | 1.58%   |
| Intel HD Graphics 5500                                                      | 24        | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23        | 1.4%    |
| AMD Raphael                                                                 | 23        | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 22        | 1.34%   |
| AMD Barcelo                                                                 | 22        | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 20        | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 19        | 1.16%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 19        | 1.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19        | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 17        | 1.03%   |
| Intel HD Graphics 630                                                       | 17        | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 15        | 0.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 15        | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 14        | 0.85%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 14        | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 14        | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 14        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                         | 14        | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 13        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 12        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 12        | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12        | 0.73%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 11        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 11        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 10        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| 1 x Intel           | 592       | 43.79%  |
| 1 x AMD             | 300       | 22.19%  |
| Intel + Nvidia      | 185       | 13.68%  |
| 1 x Nvidia          | 148       | 10.95%  |
| AMD + Nvidia        | 44        | 3.25%   |
| Intel + AMD         | 36        | 2.66%   |
| Other               | 12        | 0.89%   |
| 2 x AMD             | 11        | 0.81%   |
| 2 x Intel           | 7         | 0.52%   |
| 1 x Matrox          | 5         | 0.37%   |
| 1 x Zhaoxin         | 3         | 0.22%   |
| 2 x Nvidia          | 2         | 0.15%   |
| Nvidia + Matrox     | 2         | 0.15%   |
| Intel + 2 x Nvidia  | 2         | 0.15%   |
| 2 x Intel + 1 x AMD | 1         | 0.07%   |
| 1 x Silicon Motion  | 1         | 0.07%   |
| AMD + ASPEED        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1072      | 79.11%  |
| Proprietary | 237       | 17.49%  |
| Unknown     | 46        | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1098      | 80.85%  |
| 0.01-0.5   | 95        | 7%      |
| 1.01-2.0   | 56        | 4.12%   |
| 3.01-4.0   | 37        | 2.72%   |
| 0.51-1.0   | 27        | 1.99%   |
| 7.01-8.0   | 22        | 1.62%   |
| 5.01-6.0   | 9         | 0.66%   |
| 8.01-16.0  | 7         | 0.52%   |
| 16.01-24.0 | 6         | 0.44%   |
| 2.01-3.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 201       | 13.33%  |
| Samsung Electronics     | 180       | 11.94%  |
| BOE                     | 163       | 10.81%  |
| Chimei Innolux          | 127       | 8.42%   |
| LG Display              | 111       | 7.36%   |
| Goldstar                | 81        | 5.37%   |
| Dell                    | 79        | 5.24%   |
| Hewlett-Packard         | 48        | 3.18%   |
| Acer                    | 44        | 2.92%   |
| Apple                   | 41        | 2.72%   |
| Sharp                   | 35        | 2.32%   |
| Ancor Communications    | 32        | 2.12%   |
| AOC                     | 29        | 1.92%   |
| Philips                 | 28        | 1.86%   |
| Iiyama                  | 24        | 1.59%   |
| Lenovo                  | 23        | 1.53%   |
| BenQ                    | 22        | 1.46%   |
| InfoVision              | 18        | 1.19%   |
| CSO                     | 18        | 1.19%   |
| PANDA                   | 17        | 1.13%   |
| ASUSTek Computer        | 15        | 0.99%   |
| ViewSonic               | 14        | 0.93%   |
| Sony                    | 12        | 0.8%    |
| Panasonic               | 7         | 0.46%   |
| MSI                     | 7         | 0.46%   |
| Chi Mei Optoelectronics | 6         | 0.4%    |
| Vestel Elektronik       | 5         | 0.33%   |
| NEC Computers           | 5         | 0.33%   |
| HKC                     | 5         | 0.33%   |
| Hitachi                 | 5         | 0.33%   |
| Unknown                 | 4         | 0.27%   |
| Medion                  | 4         | 0.27%   |
| Fujitsu Siemens         | 4         | 0.27%   |
| Denver                  | 4         | 0.27%   |
| Wacom                   | 3         | 0.2%    |
| Unknown (XXX)           | 3         | 0.2%    |
| Sceptre Tech            | 3         | 0.2%    |
| MiTAC                   | 3         | 0.2%    |
| LG Philips              | 3         | 0.2%    |
| Gigabyte Technology     | 3         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.46%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 7         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.46%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 7         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 6         | 0.39%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 5         | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 5         | 0.33%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.26%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4         | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 4         | 0.26%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 4         | 0.26%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO5799 1920x1080 344x194mm 15.5-inch        | 4         | 0.26%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 4         | 0.26%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 3         | 0.2%    |
| PANDA LCD Monitor NCP004F 1920x1080 309x174mm 14.0-inch               | 3         | 0.2%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 3         | 0.2%    |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 656       | 45.84%  |
| 1366x768 (WXGA)    | 196       | 13.7%   |
| 3840x2160 (4K)     | 122       | 8.53%   |
| 2560x1440 (QHD)    | 85        | 5.94%   |
| 1920x1200 (WUXGA)  | 50        | 3.49%   |
| 1600x900 (HD+)     | 39        | 2.73%   |
| 2560x1600          | 35        | 2.45%   |
| 3440x1440          | 29        | 2.03%   |
| 1440x900 (WXGA+)   | 29        | 2.03%   |
| 2880x1800          | 27        | 1.89%   |
| 1280x800 (WXGA)    | 22        | 1.54%   |
| 1280x1024 (SXGA)   | 17        | 1.19%   |
| 1680x1050 (WSXGA+) | 16        | 1.12%   |
| 3840x2400          | 15        | 1.05%   |
| 2560x1080          | 11        | 0.77%   |
| 3840x1080          | 8         | 0.56%   |
| 2736x1824          | 8         | 0.56%   |
| 2160x1440          | 6         | 0.42%   |
| 3840x1600          | 5         | 0.35%   |
| 1920x540           | 5         | 0.35%   |
| Unknown            | 5         | 0.35%   |
| 2240x1400          | 4         | 0.28%   |
| 1280x720 (HD)      | 4         | 0.28%   |
| 3456x2160          | 3         | 0.21%   |
| 3200x1800 (QHD+)   | 3         | 0.21%   |
| 3000x2000          | 3         | 0.21%   |
| 2256x1504          | 3         | 0.21%   |
| 1920x1280          | 3         | 0.21%   |
| 1360x768           | 3         | 0.21%   |
| 1024x768 (XGA)     | 3         | 0.21%   |
| 3072x1920          | 2         | 0.14%   |
| 2880x1920          | 2         | 0.14%   |
| 2520x1680          | 2         | 0.14%   |
| 5760x2160          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3240x2160          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2304x1440          | 1         | 0.07%   |
| 1920x550           | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 344       | 22.84%  |
| 13      | 181       | 12.02%  |
| 14      | 158       | 10.49%  |
| 27      | 117       | 7.77%   |
| 24      | 96        | 6.37%   |
| 23      | 81        | 5.38%   |
| 17      | 76        | 5.05%   |
| 21      | 70        | 4.65%   |
| 31      | 50        | 3.32%   |
| 16      | 38        | 2.52%   |
| 34      | 31        | 2.06%   |
| 12      | 31        | 2.06%   |
| 19      | 26        | 1.73%   |
| Unknown | 25        | 1.66%   |
| 84      | 19        | 1.26%   |
| 20      | 18        | 1.2%    |
| 11      | 17        | 1.13%   |
| 18      | 16        | 1.06%   |
| 22      | 14        | 0.93%   |
| 40      | 12        | 0.8%    |
| 72      | 9         | 0.6%    |
| 35      | 8         | 0.53%   |
| 48      | 7         | 0.46%   |
| 26      | 7         | 0.46%   |
| 32      | 6         | 0.4%    |
| 65      | 5         | 0.33%   |
| 54      | 5         | 0.33%   |
| 52      | 4         | 0.27%   |
| 42      | 4         | 0.27%   |
| 37      | 4         | 0.27%   |
| 28      | 4         | 0.27%   |
| 25      | 4         | 0.27%   |
| 49      | 3         | 0.2%    |
| 46      | 2         | 0.13%   |
| 10      | 2         | 0.13%   |
| 69      | 1         | 0.07%   |
| 63      | 1         | 0.07%   |
| 61      | 1         | 0.07%   |
| 60      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 595       | 40.01%  |
| 501-600     | 279       | 18.76%  |
| 201-300     | 167       | 11.23%  |
| 401-500     | 133       | 8.94%   |
| 351-400     | 90        | 6.05%   |
| 601-700     | 68        | 4.57%   |
| 701-800     | 38        | 2.56%   |
| 1001-1500   | 30        | 2.02%   |
| 1501-2000   | 29        | 1.95%   |
| Unknown     | 25        | 1.68%   |
| 801-900     | 24        | 1.61%   |
| 901-1000    | 6         | 0.4%    |
| 101-200     | 3         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 995       | 74.03%  |
| 16/10   | 216       | 16.07%  |
| 21/9    | 45        | 3.35%   |
| 3/2     | 29        | 2.16%   |
| 5/4     | 20        | 1.49%   |
| Unknown | 16        | 1.19%   |
| 32/9    | 12        | 0.89%   |
| 4/3     | 9         | 0.67%   |
| 6/5     | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 346       | 23.07%  |
| 81-90          | 252       | 16.8%   |
| 201-250        | 196       | 13.07%  |
| 301-350        | 122       | 8.13%   |
| 351-500        | 100       | 6.67%   |
| 71-80          | 89        | 5.93%   |
| 151-200        | 69        | 4.6%    |
| 121-130        | 60        | 4%      |
| More than 1000 | 49        | 3.27%   |
| 251-300        | 48        | 3.2%    |
| 111-120        | 35        | 2.33%   |
| 501-1000       | 30        | 2%      |
| Unknown        | 25        | 1.67%   |
| 61-70          | 23        | 1.53%   |
| 141-150        | 22        | 1.47%   |
| 51-60          | 18        | 1.2%    |
| 131-140        | 6         | 0.4%    |
| 91-100         | 6         | 0.4%    |
| 41-50          | 2         | 0.13%   |
| 1-40           | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 448       | 30.56%  |
| 51-100        | 406       | 27.69%  |
| 101-120       | 320       | 21.83%  |
| 161-240       | 168       | 11.46%  |
| More than 240 | 69        | 4.71%   |
| 1-50          | 30        | 2.05%   |
| Unknown       | 25        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1047      | 76.87%  |
| 2     | 221       | 16.23%  |
| 0     | 65        | 4.77%   |
| 3     | 26        | 1.91%   |
| 4     | 3         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 710       | 35.29%  |
| Intel                             | 685       | 34.05%  |
| Qualcomm Atheros                  | 144       | 7.16%   |
| Broadcom                          | 103       | 5.12%   |
| MediaTek                          | 87        | 4.32%   |
| TP-Link                           | 32        | 1.59%   |
| Broadcom Limited                  | 20        | 0.99%   |
| ASIX Electronics                  | 20        | 0.99%   |
| Marvell Technology Group          | 16        | 0.8%    |
| Ralink Technology                 | 14        | 0.7%    |
| Ralink                            | 13        | 0.65%   |
| Lenovo                            | 12        | 0.6%    |
| DisplayLink                       | 11        | 0.55%   |
| Xiaomi                            | 9         | 0.45%   |
| Samsung Electronics               | 8         | 0.4%    |
| Nvidia                            | 8         | 0.4%    |
| NetGear                           | 8         | 0.4%    |
| Microsoft                         | 8         | 0.4%    |
| Sierra Wireless                   | 7         | 0.35%   |
| D-Link                            | 7         | 0.35%   |
| Aquantia                          | 7         | 0.35%   |
| Qualcomm                          | 6         | 0.3%    |
| Huawei Technologies               | 5         | 0.25%   |
| Dell                              | 5         | 0.25%   |
| Apple                             | 5         | 0.25%   |
| Qualcomm Atheros Communications   | 4         | 0.2%    |
| Hewlett-Packard                   | 4         | 0.2%    |
| Google                            | 4         | 0.2%    |
| D-Link System                     | 4         | 0.2%    |
| ASUSTek Computer                  | 4         | 0.2%    |
| Mellanox Technologies             | 3         | 0.15%   |
| JMicron Technology                | 3         | 0.15%   |
| Edimax Technology                 | 3         | 0.15%   |
| Dresden Elektronik                | 3         | 0.15%   |
| Motorola PCS                      | 2         | 0.1%    |
| Ericsson Business Mobile Networks | 2         | 0.1%    |
| AVM                               | 2         | 0.1%    |
| ZyXEL Communications              | 1         | 0.05%   |
| ZyDAS                             | 1         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 431       | 18.32%  |
| Intel Wi-Fi 6 AX201                                               | 61        | 2.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 57        | 2.42%   |
| Intel Wi-Fi 6 AX200                                               | 57        | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 2.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 54        | 2.29%   |
| Intel Wireless 8265 / 8275                                        | 52        | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 50        | 2.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 44        | 1.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 39        | 1.66%   |
| Intel Wireless 8260                                               | 32        | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 31        | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 29        | 1.23%   |
| Intel Wireless 7265                                               | 29        | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 26        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 23        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 21        | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 20        | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 19        | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.72%   |
| Intel I211 Gigabit Network Connection                             | 16        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 14        | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 0.55%   |
| Realtek 802.11ac NIC                                              | 12        | 0.51%   |
| Intel Wireless 3165                                               | 12        | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 562       | 47.31%  |
| Realtek Semiconductor           | 205       | 17.26%  |
| Qualcomm Atheros                | 121       | 10.19%  |
| MediaTek                        | 84        | 7.07%   |
| Broadcom                        | 74        | 6.23%   |
| TP-Link                         | 30        | 2.53%   |
| Broadcom Limited                | 15        | 1.26%   |
| Ralink Technology               | 14        | 1.18%   |
| Ralink                          | 13        | 1.09%   |
| NetGear                         | 8         | 0.67%   |
| Microsoft                       | 8         | 0.67%   |
| Sierra Wireless                 | 7         | 0.59%   |
| D-Link                          | 7         | 0.59%   |
| Qualcomm                        | 5         | 0.42%   |
| Qualcomm Atheros Communications | 4         | 0.34%   |
| ASUSTek Computer                | 4         | 0.34%   |
| Marvell Technology Group        | 3         | 0.25%   |
| Edimax Technology               | 3         | 0.25%   |
| Dell                            | 3         | 0.25%   |
| D-Link System                   | 3         | 0.25%   |
| AVM                             | 2         | 0.17%   |
| ZyXEL Communications            | 1         | 0.08%   |
| ZyDAS                           | 1         | 0.08%   |
| Z-Com                           | 1         | 0.08%   |
| TRENDnet                        | 1         | 0.08%   |
| Tenda                           | 1         | 0.08%   |
| Quectel Wireless Solutions      | 1         | 0.08%   |
| Qualcomm Technologies           | 1         | 0.08%   |
| Philips (or NXP)                | 1         | 0.08%   |
| Linksys                         | 1         | 0.08%   |
| Guillemot                       | 1         | 0.08%   |
| Fibocom                         | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| AboCom Systems                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 61        | 5.1%    |
| Intel Wi-Fi 6 AX200                                            | 57        | 4.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 53        | 4.43%   |
| Intel Wireless 8265 / 8275                                     | 52        | 4.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 50        | 4.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 39        | 3.26%   |
| Intel Wireless 8260                                            | 32        | 2.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 31        | 2.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 29        | 2.42%   |
| Intel Wireless 7265                                            | 29        | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 2.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 2.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 23        | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 21        | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 20        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 1.5%    |
| Intel Raptor Lake PCH CNVi WiFi                                | 17        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 14        | 1.17%   |
| Realtek 802.11ac NIC                                           | 12        | 1%      |
| Intel Wireless 3165                                            | 12        | 1%      |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 0.92%   |
| Intel Wireless 7260                                            | 11        | 0.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 11        | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 10        | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 0.75%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 9         | 0.75%   |
| Intel Wireless-AC 9260                                         | 8         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 610       | 54.51%  |
| Intel                      | 298       | 26.63%  |
| Broadcom                   | 45        | 4.02%   |
| Qualcomm Atheros           | 36        | 3.22%   |
| ASIX Electronics           | 20        | 1.79%   |
| Marvell Technology Group   | 13        | 1.16%   |
| Lenovo                     | 12        | 1.07%   |
| DisplayLink                | 11        | 0.98%   |
| Xiaomi                     | 9         | 0.8%    |
| Samsung Electronics        | 8         | 0.71%   |
| Nvidia                     | 8         | 0.71%   |
| Aquantia                   | 7         | 0.63%   |
| Broadcom Limited           | 6         | 0.54%   |
| Google                     | 4         | 0.36%   |
| Apple                      | 4         | 0.36%   |
| TP-Link                    | 3         | 0.27%   |
| Mellanox Technologies      | 3         | 0.27%   |
| MediaTek                   | 3         | 0.27%   |
| JMicron Technology         | 3         | 0.27%   |
| Huawei Technologies        | 3         | 0.27%   |
| Motorola PCS               | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM | 1         | 0.09%   |
| Vimtron Electronics        | 1         | 0.09%   |
| Toshiba                    | 1         | 0.09%   |
| Qualcomm                   | 1         | 0.09%   |
| OPPO Electronics           | 1         | 0.09%   |
| MosChip Semiconductor      | 1         | 0.09%   |
| Microchip Technology       | 1         | 0.09%   |
| ICS Advent                 | 1         | 0.09%   |
| Hewlett-Packard            | 1         | 0.09%   |
| D-Link System              | 1         | 0.09%   |
| 3Com                       | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 431       | 37.81%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 57        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 4.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 44        | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 2.54%   |
| Intel Ethernet Controller I225-V                                  | 26        | 2.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 2.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 1.67%   |
| Intel I211 Gigabit Network Connection                             | 16        | 1.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.7%    |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                            | 6         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 6         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.44%   |
| Intel Ethernet Controller I226-V                                  | 5         | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1130      | 51.91%  |
| Ethernet | 1031      | 47.36%  |
| Modem    | 15        | 0.69%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 864       | 61.67%  |
| Ethernet | 537       | 38.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 660       | 48.89%  |
| 1     | 629       | 46.59%  |
| 3     | 35        | 2.59%   |
| 0     | 22        | 1.63%   |
| 4     | 2         | 0.15%   |
| 6     | 1         | 0.07%   |
| 5     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 925       | 68.11%  |
| Yes  | 433       | 31.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 501       | 50.35%  |
| Realtek Semiconductor           | 120       | 12.06%  |
| IMC Networks                    | 49        | 4.92%   |
| Foxconn / Hon Hai               | 49        | 4.92%   |
| Qualcomm Atheros Communications | 48        | 4.82%   |
| Apple                           | 42        | 4.22%   |
| Cambridge Silicon Radio         | 36        | 3.62%   |
| Lite-On Technology              | 29        | 2.91%   |
| Broadcom                        | 24        | 2.41%   |
| Realtek                         | 17        | 1.71%   |
| MediaTek                        | 16        | 1.61%   |
| ASUSTek Computer                | 13        | 1.31%   |
| TP-Link                         | 8         | 0.8%    |
| Dell                            | 8         | 0.8%    |
| Hewlett-Packard                 | 6         | 0.6%    |
| Toshiba                         | 4         | 0.4%    |
| Ralink                          | 4         | 0.4%    |
| USI                             | 3         | 0.3%    |
| Marvell Semiconductor           | 3         | 0.3%    |
| Opticis                         | 2         | 0.2%    |
| Fujitsu                         | 2         | 0.2%    |
| Edimax Technology               | 2         | 0.2%    |
| Ralink Technology               | 1         | 0.1%    |
| Logitech                        | 1         | 0.1%    |
| Integrated System Solution      | 1         | 0.1%    |
| HTC (High Tech Computer)        | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |
| Actions                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 134       | 13.44%  |
| Intel AX201 Bluetooth                               | 131       | 13.14%  |
| Realtek Bluetooth Radio                             | 95        | 9.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 74        | 7.42%   |
| Intel Bluetooth Device                              | 64        | 6.42%   |
| Intel AX200 Bluetooth                               | 52        | 5.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 36        | 3.61%   |
| IMC Networks Wireless_Device                        | 25        | 2.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 25        | 2.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 2.21%   |
| Intel AX210 Bluetooth                               | 20        | 2.01%   |
| IMC Networks Bluetooth Radio                        | 20        | 2.01%   |
| Apple Bluetooth Host Controller                     | 18        | 1.81%   |
| Realtek Bluetooth Radio                             | 17        | 1.71%   |
| MediaTek Wireless_Device                            | 16        | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.5%    |
| Apple Bluetooth USB Host Controller                 | 13        | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1%      |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 0.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.9%    |
| TP-Link UB5A Adapter                                | 8         | 0.8%    |
| Lite-On Bluetooth Device                            | 8         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 7         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 5         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 0.5%    |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 5         | 0.5%    |
| ASUS ASUS USB-BT500                                 | 5         | 0.5%    |
| Ralink RT3290 Bluetooth                             | 4         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.4%    |
| Lite-On Wireless_Device                             | 4         | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.4%    |
| Apple Bluetooth HCI                                 | 4         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 975       | 52.31%  |
| AMD                                          | 391       | 20.98%  |
| Nvidia                                       | 284       | 15.24%  |
| C-Media Electronics                          | 31        | 1.66%   |
| Realtek Semiconductor                        | 17        | 0.91%   |
| Logitech                                     | 17        | 0.91%   |
| GN Netcom                                    | 15        | 0.8%    |
| ASUSTek Computer                             | 13        | 0.7%    |
| Lenovo                                       | 10        | 0.54%   |
| Plantronics                                  | 7         | 0.38%   |
| Texas Instruments                            | 6         | 0.32%   |
| Razer USA                                    | 6         | 0.32%   |
| VIA Technologies                             | 5         | 0.27%   |
| Generalplus Technology                       | 5         | 0.27%   |
| Micro Star International                     | 4         | 0.21%   |
| Kingston Technology                          | 4         | 0.21%   |
| Focusrite-Novation                           | 4         | 0.21%   |
| Apple                                        | 4         | 0.21%   |
| Zhaoxin                                      | 3         | 0.16%   |
| Sony                                         | 3         | 0.16%   |
| KORG                                         | 3         | 0.16%   |
| JMTek                                        | 3         | 0.16%   |
| Hewlett-Packard                              | 3         | 0.16%   |
| Creative Technology                          | 3         | 0.16%   |
| Creative Labs                                | 3         | 0.16%   |
| BEHRINGER International                      | 3         | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.11%   |
| SteelSeries ApS                              | 2         | 0.11%   |
| Samson Technologies                          | 2         | 0.11%   |
| Native Instruments                           | 2         | 0.11%   |
| Giga-Byte Technology                         | 2         | 0.11%   |
| DSEA A/S                                     | 2         | 0.11%   |
| Corsair                                      | 2         | 0.11%   |
| Yamaha                                       | 1         | 0.05%   |
| XMOS                                         | 1         | 0.05%   |
| USB Audio                                    | 1         | 0.05%   |
| Turtle Beach                                 | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| Tenx Technology                              | 1         | 0.05%   |
| Superlux digit                               | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 197       | 8.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 119       | 5.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 115       | 5.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 76        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 70        | 3.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 65        | 2.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 62        | 2.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 60        | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 51        | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 41        | 1.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 37        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35        | 1.56%   |
| Intel Broadwell-U Audio Controller                                         | 34        | 1.51%   |
| Nvidia Audio device                                                        | 32        | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 31        | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 31        | 1.38%   |
| AMD FCH Azalia Controller                                                  | 29        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 26        | 1.16%   |
| Intel 8 Series HD Audio Controller                                         | 26        | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25        | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 25        | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 25        | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.11%   |
| Nvidia GA106 High Definition Audio Controller                              | 24        | 1.07%   |
| Intel Alder Lake-S HD Audio Controller                                     | 22        | 0.98%   |
| Intel 200 Series PCH HD Audio                                              | 22        | 0.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 21        | 0.94%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 21        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 21        | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 19        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 18        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18        | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 0.76%   |
| Realtek Semiconductor USB Audio                                            | 15        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 183       | 24.53%  |
| SK hynix               | 126       | 16.89%  |
| Micron Technology      | 105       | 14.08%  |
| Kingston               | 75        | 10.05%  |
| Crucial                | 42        | 5.63%   |
| Unknown                | 38        | 5.09%   |
| Corsair                | 29        | 3.89%   |
| G.Skill                | 21        | 2.82%   |
| A-DATA Technology      | 17        | 2.28%   |
| Ramaxel Technology     | 14        | 1.88%   |
| Unknown (ABCD)         | 10        | 1.34%   |
| Unknown                | 8         | 1.07%   |
| Smart                  | 7         | 0.94%   |
| Elpida                 | 7         | 0.94%   |
| Transcend              | 6         | 0.8%    |
| Team                   | 6         | 0.8%    |
| Patriot                | 5         | 0.67%   |
| Nanya Technology       | 4         | 0.54%   |
| GOODRAM                | 4         | 0.54%   |
| Timetec                | 3         | 0.4%    |
| Shenzhen WODPOSIT      | 3         | 0.4%    |
| PNY                    | 3         | 0.4%    |
| Patriot Memory         | 2         | 0.27%   |
| Hewlett-Packard        | 2         | 0.27%   |
| ASint Technology       | 2         | 0.27%   |
| Wodposit               | 1         | 0.13%   |
| Unknown (AB)           | 1         | 0.13%   |
| Unknown (0x9801)       | 1         | 0.13%   |
| Unknown (0x0CDC)       | 1         | 0.13%   |
| Unknown (0x0C26)       | 1         | 0.13%   |
| Unknown (0B85)         | 1         | 0.13%   |
| Unknown (0000000080CE) | 1         | 0.13%   |
| Unifosa                | 1         | 0.13%   |
| Teikon                 | 1         | 0.13%   |
| Strontium              | 1         | 0.13%   |
| Saikano                | 1         | 0.13%   |
| PUSKILL                | 1         | 0.13%   |
| Lexar                  | 1         | 0.13%   |
| Kingmax                | 1         | 0.13%   |
| KINGBANK               | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.02%   |
| Unknown                                                          | 8         | 1.02%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 7         | 0.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.76%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 6         | 0.76%   |
| Samsung RAM K3LKBKB@BM-MGCP 2048MB Row Of Chips 6400MT/s         | 6         | 0.76%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.64%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.64%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 5         | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.64%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s           | 4         | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.51%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 4         | 0.51%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 3         | 0.38%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 3         | 0.38%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 0.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.38%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.38%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 3         | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.38%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 3         | 0.38%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 326       | 49.39%  |
| DDR3    | 117       | 17.73%  |
| DDR5    | 58        | 8.79%   |
| LPDDR4  | 56        | 8.48%   |
| LPDDR5  | 44        | 6.67%   |
| LPDDR3  | 25        | 3.79%   |
| SDRAM   | 15        | 2.27%   |
| DDR2    | 11        | 1.67%   |
| Unknown | 6         | 0.91%   |
| DDR     | 2         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 382       | 57.62%  |
| DIMM         | 155       | 23.38%  |
| Row Of Chips | 113       | 17.04%  |
| Chip         | 8         | 1.21%   |
| Unknown      | 5         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 314       | 44.23%  |
| 4096  | 150       | 21.13%  |
| 16384 | 135       | 19.01%  |
| 32768 | 49        | 6.9%    |
| 2048  | 48        | 6.76%   |
| 1024  | 11        | 1.55%   |
| 49152 | 1         | 0.14%   |
| 1536  | 1         | 0.14%   |
| 512   | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 167       | 23.89%  |
| 1600    | 92        | 13.16%  |
| 2667    | 82        | 11.73%  |
| 2400    | 46        | 6.58%   |
| 6400    | 45        | 6.44%   |
| 2133    | 34        | 4.86%   |
| 4800    | 32        | 4.58%   |
| 4267    | 30        | 4.29%   |
| 1333    | 16        | 2.29%   |
| 1867    | 15        | 2.15%   |
| 3600    | 14        | 2%      |
| 5600    | 9         | 1.29%   |
| 1334    | 9         | 1.29%   |
| 3733    | 7         | 1%      |
| 800     | 7         | 1%      |
| Unknown | 7         | 1%      |
| 6000    | 6         | 0.86%   |
| 2666    | 6         | 0.86%   |
| 667     | 6         | 0.86%   |
| 5200    | 5         | 0.72%   |
| 4266    | 5         | 0.72%   |
| 8400    | 4         | 0.57%   |
| 3866    | 4         | 0.57%   |
| 3266    | 4         | 0.57%   |
| 2933    | 4         | 0.57%   |
| 2048    | 4         | 0.57%   |
| 4199    | 3         | 0.43%   |
| 3400    | 3         | 0.43%   |
| 1067    | 3         | 0.43%   |
| 5808    | 2         | 0.29%   |
| 5500    | 2         | 0.29%   |
| 3666    | 2         | 0.29%   |
| 3466    | 2         | 0.29%   |
| 1866    | 2         | 0.29%   |
| 1800    | 2         | 0.29%   |
| 975     | 2         | 0.29%   |
| 533     | 2         | 0.29%   |
| 400     | 2         | 0.29%   |
| 6800    | 1         | 0.14%   |
| 5800    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 9         | 25.71%  |
| Hewlett-Packard       | 8         | 22.86%  |
| Samsung Electronics   | 6         | 17.14%  |
| Seiko Epson           | 5         | 14.29%  |
| Canon                 | 3         | 8.57%   |
| Pantum                | 2         | 5.71%   |
| QinHeng Electronics   | 1         | 2.86%   |
| Lexmark International | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson XP-2200 Series                   | 1         | 2.86%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 2.86%   |
| Seiko Epson ET-8550 Series                   | 1         | 2.86%   |
| Seiko Epson ET-2820 Series                   | 1         | 2.86%   |
| Seiko Epson ET-2810 Series                   | 1         | 2.86%   |
| Samsung SCX-4623 Series                      | 1         | 2.86%   |
| Samsung SCX-3400 Series                      | 1         | 2.86%   |
| Samsung ML-216x Series Laser Printer         | 1         | 2.86%   |
| Samsung M2020 Series                         | 1         | 2.86%   |
| Samsung CLX-3170 Series                      | 1         | 2.86%   |
| Samsung C1860 Series                         | 1         | 2.86%   |
| QinHeng CH340S                               | 1         | 2.86%   |
| Pantum P2200 series                          | 1         | 2.86%   |
| Pantum M6550NW series                        | 1         | 2.86%   |
| Lexmark International MC3326adwe             | 1         | 2.86%   |
| HP OfficeJet 5200 series                     | 1         | 2.86%   |
| HP LaserJet Pro M201dw                       | 1         | 2.86%   |
| HP LaserJet P2055 series                     | 1         | 2.86%   |
| HP LaserJet P2015 series                     | 1         | 2.86%   |
| HP DeskJet 960c                              | 1         | 2.86%   |
| HP DeskJet 4100 series                       | 1         | 2.86%   |
| HP ColorLaserJet M253-M254                   | 1         | 2.86%   |
| HP Color LaserJet Pro M453-4                 | 1         | 2.86%   |
| Canon TS3100 series                          | 1         | 2.86%   |
| Canon TR4500 series                          | 1         | 2.86%   |
| Canon iP7200 series                          | 1         | 2.86%   |
| Brother MFC-J6530DW                          | 1         | 2.86%   |
| Brother MFC-J1010DW                          | 1         | 2.86%   |
| Brother MFC-9330CDW                          | 1         | 2.86%   |
| Brother HL-L5000D series                     | 1         | 2.86%   |
| Brother HL-52x0 series                       | 1         | 2.86%   |
| Brother HL-2250DN Laser Printer              | 1         | 2.86%   |
| Brother HL-2030 Laser Printer                | 1         | 2.86%   |
| Brother DCP-7055W                            | 1         | 2.86%   |
| Brother DCP-1610W                            | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Canon   | 5         | 83.33%  |
| Plustek | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100            | 2         | 33.33%  |
| Plustek 600dpi USB Scanner         | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 16.67%  |
| Canon CanoScan LiDE 120            | 1         | 16.67%  |
| Canon CanoScan 8800F               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 179       | 20.02%  |
| IMC Networks                           | 82        | 9.17%   |
| Microdia                               | 80        | 8.95%   |
| Quanta                                 | 69        | 7.72%   |
| Realtek Semiconductor                  | 62        | 6.94%   |
| Logitech                               | 49        | 5.48%   |
| Bison Electronics                      | 42        | 4.7%    |
| Apple                                  | 40        | 4.47%   |
| Sunplus Innovation Technology          | 37        | 4.14%   |
| Luxvisions Innotech Limited            | 35        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 2.91%   |
| Lite-On Technology                     | 22        | 2.46%   |
| Syntek                                 | 19        | 2.13%   |
| Sonix Technology                       | 19        | 2.13%   |
| Acer                                   | 19        | 2.13%   |
| Suyin                                  | 10        | 1.12%   |
| Samsung Electronics                    | 10        | 1.12%   |
| Silicon Motion                         | 9         | 1.01%   |
| SunplusIT                              | 8         | 0.89%   |
| Microsoft                              | 8         | 0.89%   |
| Alcor Micro                            | 7         | 0.78%   |
| Importek                               | 6         | 0.67%   |
| Shinetech                              | 5         | 0.56%   |
| Ricoh                                  | 4         | 0.45%   |
| Shine-optics                           | 3         | 0.34%   |
| Razer USA                              | 3         | 0.34%   |
| icSpring                               | 3         | 0.34%   |
| ARC International                      | 3         | 0.34%   |
| Z-Star Microelectronics                | 2         | 0.22%   |
| Pixart Imaging                         | 2         | 0.22%   |
| Lenovo                                 | 2         | 0.22%   |
| Google                                 | 2         | 0.22%   |
| Generalplus Technology                 | 2         | 0.22%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.22%   |
| Unknown                                | 2         | 0.22%   |
| WCM_USB                                | 1         | 0.11%   |
| Trust                                  | 1         | 0.11%   |
| Sunplus Technology                     | 1         | 0.11%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.11%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 54        | 5.95%   |
| Microdia Integrated_Webcam_HD                       | 39        | 4.3%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 26        | 2.86%   |
| IMC Networks Integrated Camera                      | 25        | 2.75%   |
| Chicony HP HD Camera                                | 19        | 2.09%   |
| Realtek Integrated_Webcam_HD                        | 17        | 1.87%   |
| Syntek Integrated Camera                            | 15        | 1.65%   |
| Logitech HD Pro Webcam C920                         | 14        | 1.54%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 1.43%   |
| Bison Integrated Camera                             | 13        | 1.43%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 1.32%   |
| Chicony HD WebCam                                   | 12        | 1.32%   |
| Apple Built-in iSight                               | 12        | 1.32%   |
| Logitech Webcam C270                                | 11        | 1.21%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 11        | 1.21%   |
| Sonix USB2.0 HD UVC WebCam                          | 10        | 1.1%    |
| Samsung Galaxy series, misc. (MTP mode)             | 10        | 1.1%    |
| Quanta HD User Facing                               | 10        | 1.1%    |
| Lite-On Integrated Camera                           | 10        | 1.1%    |
| Chicony HP Wide Vision HD Camera                    | 10        | 1.1%    |
| Chicony HD User Facing                              | 9         | 0.99%   |
| Sonix USB2.0 FHD UVC WebCam                         | 8         | 0.88%   |
| Quanta ov9734_techfront_camera                      | 8         | 0.88%   |
| Microdia USB 2.0 Camera                             | 8         | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera       | 8         | 0.88%   |
| Chicony HP Truevision HD                            | 8         | 0.88%   |
| Apple FaceTime HD Camera (Built-in)                 | 8         | 0.88%   |
| Quanta HD Camera                                    | 7         | 0.77%   |
| Microdia Integrated_Webcam_FHD                      | 7         | 0.77%   |
| Acer Integrated Camera                              | 7         | 0.77%   |
| Realtek USB Camera                                  | 6         | 0.66%   |
| Realtek Integrated Webcam HD                        | 6         | 0.66%   |
| Quanta HP TrueVision HD Camera                      | 6         | 0.66%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 6         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 6         | 0.66%   |
| Bison SunplusIT Integrated Camera                   | 6         | 0.66%   |
| Apple FaceTime HD Camera                            | 6         | 0.66%   |
| Acer BisonCam,NB Pro                                | 6         | 0.66%   |
| Realtek Integrated Webcam_HD                        | 5         | 0.55%   |
| Quanta HP HD Camera                                 | 5         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 55        | 28.5%   |
| Shenzhen Goodix Technology         | 51        | 26.42%  |
| Synaptics                          | 50        | 25.91%  |
| Elan Microelectronics              | 13        | 6.74%   |
| LighTuning Technology              | 7         | 3.63%   |
| Upek                               | 5         | 2.59%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 2.59%   |
| AuthenTec                          | 5         | 2.59%   |
| STMicroelectronics                 | 1         | 0.52%   |
| Focal-systems.Corp                 | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 33        | 17.1%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 5.18%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 5.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 5.18%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 4.15%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 4.15%   |
| Elan ELAN:ARM-M4                                                           | 8         | 4.15%   |
| Synaptics WBDI                                                             | 7         | 3.63%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 3.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.11%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.59%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 2.59%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 2.59%   |
| Synaptics UWP WBDI Device                                                  | 4         | 2.07%   |
| Synaptics  WBDI                                                            | 4         | 2.07%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.07%   |
| Elan WBF Fingerprint Sensor                                                | 4         | 2.07%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 1.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.55%   |
| LighTuning Fingerprint Sensor                                              | 3         | 1.55%   |
| AuthenTec AES2810                                                          | 3         | 1.55%   |
| Synaptics UWP WBDI                                                         | 2         | 1.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.04%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.52%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.52%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.52%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.52%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.52%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.52%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 30        | 55.56%  |
| Alcor Micro           | 18        | 33.33%  |
| Upek                  | 3         | 5.56%   |
| Realtek Semiconductor | 1         | 1.85%   |
| Hewlett-Packard       | 1         | 1.85%   |
| Advanced Card Systems | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 33.33%  |
| Broadcom 5880                                                                | 14        | 25.93%  |
| Broadcom 58200                                                               | 8         | 14.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 12.96%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.56%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.85%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.85%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 887       | 65.03%  |
| 1     | 378       | 27.71%  |
| 2     | 78        | 5.72%   |
| 3     | 13        | 0.95%   |
| 4     | 6         | 0.44%   |
| 10    | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 193       | 34.28%  |
| Graphics card            | 126       | 22.38%  |
| Chipcard                 | 52        | 9.24%   |
| Net/wireless             | 43        | 7.64%   |
| Multimedia controller    | 40        | 7.1%    |
| Camera                   | 36        | 6.39%   |
| Unassigned class         | 18        | 3.2%    |
| Communication controller | 15        | 2.66%   |
| Sound                    | 11        | 1.95%   |
| Bluetooth                | 8         | 1.42%   |
| Storage                  | 6         | 1.07%   |
| Card reader              | 5         | 0.89%   |
| Net/ethernet             | 4         | 0.71%   |
| Network                  | 3         | 0.53%   |
| Storage/ide              | 1         | 0.18%   |
| Modem                    | 1         | 0.18%   |
| Dvb card                 | 1         | 0.18%   |

