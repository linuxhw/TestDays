NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

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

Total: 340

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | X570-A PRO                  | Desktop     | [30416c0355](https://linux-hardware.org/?probe=30416c0355) | Nov 04, 2023 |
| HP            | 83E1                        | Desktop     | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [0e5f976d6b](https://linux-hardware.org/?probe=0e5f976d6b) | Nov 02, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b075cf8841](https://linux-hardware.org/?probe=b075cf8841) | Oct 28, 2023 |
| LattePanda    | Sigma                       | Desktop     | [d287cf2d8a](https://linux-hardware.org/?probe=d287cf2d8a) | Oct 26, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| ECS           | A55F-M3                     | Desktop     | [6da483b400](https://linux-hardware.org/?probe=6da483b400) | Oct 25, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [a80fcc753e](https://linux-hardware.org/?probe=a80fcc753e) | Oct 25, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [c0bcd133c9](https://linux-hardware.org/?probe=c0bcd133c9) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Framework     | Laptop                      | Notebook    | [e765d5da63](https://linux-hardware.org/?probe=e765d5da63) | Oct 18, 2023 |
| Unknown       | Apple Mac mini (M1, 2020... | Mini pc     | [e6566d9c7c](https://linux-hardware.org/?probe=e6566d9c7c) | Oct 18, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [da6815d760](https://linux-hardware.org/?probe=da6815d760) | Oct 18, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [11155b7b3a](https://linux-hardware.org/?probe=11155b7b3a) | Oct 13, 2023 |
| Unknown       | HX90                        | Desktop     | [f247716ab0](https://linux-hardware.org/?probe=f247716ab0) | Oct 13, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | Notebook    | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [7ff5fe9fdd](https://linux-hardware.org/?probe=7ff5fe9fdd) | Oct 11, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | Notebook    | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [fc3ea4bb32](https://linux-hardware.org/?probe=fc3ea4bb32) | Oct 08, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [89472bd2f3](https://linux-hardware.org/?probe=89472bd2f3) | Oct 07, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| Dell          | 08DM12 A01                  | Server      | [9faef398d0](https://linux-hardware.org/?probe=9faef398d0) | Oct 07, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [642a2f5a9b](https://linux-hardware.org/?probe=642a2f5a9b) | Oct 04, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a4fbd5793d](https://linux-hardware.org/?probe=a4fbd5793d) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [c67f66f5e3](https://linux-hardware.org/?probe=c67f66f5e3) | Oct 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| HP            | 3397                        | Desktop     | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| HP            | 1998                        | Desktop     | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | Notebook    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| HP            | 8767 A                      | Desktop     | [ce91ccf3a9](https://linux-hardware.org/?probe=ce91ccf3a9) | Sep 09, 2023 |
| Dell          | Precision 5680              | Notebook    | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | Notebook    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | Notebook    | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9e03b48bf3](https://linux-hardware.org/?probe=9e03b48bf3) | Aug 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [13c8b276bb](https://linux-hardware.org/?probe=13c8b276bb) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| Teclast       | F5                          | Convertible | [76fcc31a43](https://linux-hardware.org/?probe=76fcc31a43) | Aug 01, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e452f85fb8](https://linux-hardware.org/?probe=e452f85fb8) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | Notebook    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | Notebook    | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [9bb1b8fbca](https://linux-hardware.org/?probe=9bb1b8fbca) | Jul 12, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf6a7757d5](https://linux-hardware.org/?probe=cf6a7757d5) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | Notebook    | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| MACHENIKE     | F117-7P                     | Notebook    | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4396db2f33](https://linux-hardware.org/?probe=4396db2f33) | May 22, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Acer          | Spin SP514-51N              | Convertible | [6b23655b4b](https://linux-hardware.org/?probe=6b23655b4b) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [6ce8b7fb26](https://linux-hardware.org/?probe=6ce8b7fb26) | Apr 11, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [f53ad14ea5](https://linux-hardware.org/?probe=f53ad14ea5) | Mar 13, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4f3c01941d](https://linux-hardware.org/?probe=4f3c01941d) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [616e689b13](https://linux-hardware.org/?probe=616e689b13) | Feb 19, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [5f59be48e1](https://linux-hardware.org/?probe=5f59be48e1) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [68effccd60](https://linux-hardware.org/?probe=68effccd60) | Feb 16, 2023 |
| Teclast       | F5                          | Convertible | [e62bdaaa3b](https://linux-hardware.org/?probe=e62bdaaa3b) | Feb 13, 2023 |
| Teclast       | F5                          | Convertible | [30e30a5c3e](https://linux-hardware.org/?probe=30e30a5c3e) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8ac9c4b4ef](https://linux-hardware.org/?probe=8ac9c4b4ef) | Feb 09, 2023 |
| Acer          | Switch SW713-51GNP          | Tablet      | [46ecb88f1d](https://linux-hardware.org/?probe=46ecb88f1d) | Feb 08, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | Notebook    | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [226b8e5ff8](https://linux-hardware.org/?probe=226b8e5ff8) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b99e4815bc](https://linux-hardware.org/?probe=b99e4815bc) | Jan 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b721a47fa4](https://linux-hardware.org/?probe=b721a47fa4) | Jan 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d5df950832](https://linux-hardware.org/?probe=d5df950832) | Jan 03, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| Dell          | Precision M4800             | Notebook    | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ee5f96d645](https://linux-hardware.org/?probe=ee5f96d645) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [3dfa1ba4b1](https://linux-hardware.org/?probe=3dfa1ba4b1) | Dec 09, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [110e3eab7f](https://linux-hardware.org/?probe=110e3eab7f) | Dec 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [44a3785f1f](https://linux-hardware.org/?probe=44a3785f1f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [fce691523b](https://linux-hardware.org/?probe=fce691523b) | Oct 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d79322ca4a](https://linux-hardware.org/?probe=d79322ca4a) | Oct 19, 2022 |
| Dell          | Precision 5760              | Notebook    | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa5ea0c17c](https://linux-hardware.org/?probe=aa5ea0c17c) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ae775f1f89](https://linux-hardware.org/?probe=ae775f1f89) | Oct 13, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3a409e83a0](https://linux-hardware.org/?probe=3a409e83a0) | Oct 07, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [5eb1758869](https://linux-hardware.org/?probe=5eb1758869) | Oct 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| ASUSTek       | P8Q77-M                     | Desktop     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| GPD           | MicroPC                     | Notebook    | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Dell          | Latitude 7420               | Notebook    | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [e5dc04e6a5](https://linux-hardware.org/?probe=e5dc04e6a5) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| Teclast       | F5                          | Convertible | [0854310843](https://linux-hardware.org/?probe=0854310843) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | Notebook    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [66d71367c1](https://linux-hardware.org/?probe=66d71367c1) | Aug 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd919b4bd6](https://linux-hardware.org/?probe=bd919b4bd6) | Aug 22, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | Desktop     | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | Desktop     | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | Notebook    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 23.05                      | 88        | 33.72%  |
| NixOS 22.11                      | 53        | 20.31%  |
| NixOS 22.05                      | 37        | 14.18%  |
| NixOS 23.11                      | 30        | 11.49%  |
| NixOS 21.11                      | 18        | 6.9%    |
| NixOS                            | 5         | 1.92%   |
| NixOS 21.05pre-git               | 2         | 0.77%   |
| NixOS 20.09pre-git               | 2         | 0.77%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.38%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.38%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.38%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.38%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.38%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.38%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.38%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.38%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.38%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.38%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.38%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.38%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.38%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.38%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.38%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.38%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.38%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.38%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.38%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.38%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.38%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.38%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.38%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.38%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.38%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 236       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version       | Computers | Percent |
|---------------|-----------|---------|
| 6.1.55        | 9         | 3.2%    |
| 6.1.51        | 5         | 1.78%   |
| 6.1.31        | 5         | 1.78%   |
| 5.15.74       | 5         | 1.78%   |
| 6.4.0         | 4         | 1.42%   |
| 6.3.8         | 4         | 1.42%   |
| 6.3.3         | 4         | 1.42%   |
| 6.1.53        | 4         | 1.42%   |
| 6.1.38        | 4         | 1.42%   |
| 5.15.86       | 4         | 1.42%   |
| 5.15.43       | 4         | 1.42%   |
| 6.5.2         | 3         | 1.07%   |
| 6.3.1         | 3         | 1.07%   |
| 6.2.0-rc6     | 3         | 1.07%   |
| 6.1.47        | 3         | 1.07%   |
| 6.1.42        | 3         | 1.07%   |
| 6.1.37        | 3         | 1.07%   |
| 6.1.35        | 3         | 1.07%   |
| 6.1.0         | 3         | 1.07%   |
| 6.0.11        | 3         | 1.07%   |
| 6.0.10        | 3         | 1.07%   |
| 5.15.82       | 3         | 1.07%   |
| 5.15.72       | 3         | 1.07%   |
| 5.15.68       | 3         | 1.07%   |
| 5.15.47       | 3         | 1.07%   |
| 5.15.26       | 3         | 1.07%   |
| 6.5.7-xanmod1 | 2         | 0.71%   |
| 6.5.7         | 2         | 0.71%   |
| 6.5.6         | 2         | 0.71%   |
| 6.5.5         | 2         | 0.71%   |
| 6.4.7         | 2         | 0.71%   |
| 6.4.6         | 2         | 0.71%   |
| 6.1.60        | 2         | 0.71%   |
| 6.1.45        | 2         | 0.71%   |
| 6.1.41        | 2         | 0.71%   |
| 6.1.39        | 2         | 0.71%   |
| 6.1.34        | 2         | 0.71%   |
| 6.1.27        | 2         | 0.71%   |
| 6.1.24        | 2         | 0.71%   |
| 6.1.1         | 2         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.55  | 10        | 3.56%   |
| 6.4.0   | 6         | 2.14%   |
| 6.1.31  | 6         | 2.14%   |
| 6.1.51  | 5         | 1.78%   |
| 5.15.74 | 5         | 1.78%   |
| 6.5.7   | 4         | 1.42%   |
| 6.3.8   | 4         | 1.42%   |
| 6.3.3   | 4         | 1.42%   |
| 6.2.0   | 4         | 1.42%   |
| 6.1.53  | 4         | 1.42%   |
| 6.1.38  | 4         | 1.42%   |
| 6.1.0   | 4         | 1.42%   |
| 6.0.10  | 4         | 1.42%   |
| 5.15.86 | 4         | 1.42%   |
| 5.15.43 | 4         | 1.42%   |
| 6.5.2   | 3         | 1.07%   |
| 6.3.1   | 3         | 1.07%   |
| 6.1.47  | 3         | 1.07%   |
| 6.1.42  | 3         | 1.07%   |
| 6.1.37  | 3         | 1.07%   |
| 6.1.35  | 3         | 1.07%   |
| 6.0.11  | 3         | 1.07%   |
| 5.15.82 | 3         | 1.07%   |
| 5.15.72 | 3         | 1.07%   |
| 5.15.68 | 3         | 1.07%   |
| 5.15.47 | 3         | 1.07%   |
| 5.15.26 | 3         | 1.07%   |
| 6.5.6   | 2         | 0.71%   |
| 6.5.5   | 2         | 0.71%   |
| 6.4.7   | 2         | 0.71%   |
| 6.4.6   | 2         | 0.71%   |
| 6.4.4   | 2         | 0.71%   |
| 6.2.9   | 2         | 0.71%   |
| 6.2.11  | 2         | 0.71%   |
| 6.1.60  | 2         | 0.71%   |
| 6.1.45  | 2         | 0.71%   |
| 6.1.41  | 2         | 0.71%   |
| 6.1.39  | 2         | 0.71%   |
| 6.1.34  | 2         | 0.71%   |
| 6.1.27  | 2         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 71        | 26.69%  |
| 5.15    | 61        | 22.93%  |
| 6.4     | 16        | 6.02%   |
| 5.10    | 14        | 5.26%   |
| 6.3     | 13        | 4.89%   |
| 6.2     | 13        | 4.89%   |
| 6.0     | 13        | 4.89%   |
| 6.5     | 12        | 4.51%   |
| 5.16    | 8         | 3.01%   |
| 5.4     | 7         | 2.63%   |
| 5.19    | 7         | 2.63%   |
| 5.8     | 6         | 2.26%   |
| 5.18    | 5         | 1.88%   |
| 5.13    | 4         | 1.5%    |
| 5.7     | 3         | 1.13%   |
| 5.17    | 3         | 1.13%   |
| 5.12    | 3         | 1.13%   |
| 5.14    | 2         | 0.75%   |
| 5.11    | 2         | 0.75%   |
| 4.19    | 2         | 0.75%   |
| Unknown | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 229       | 97.03%  |
| aarch64 | 6         | 2.54%   |
| i686    | 1         | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 102       | 41.3%   |
| GNOME        | 39        | 15.79%  |
| KDE5         | 30        | 12.15%  |
| sway         | 24        | 9.72%   |
| Hyprland     | 11        | 4.45%   |
| none+i3      | 9         | 3.64%   |
| KDE          | 9         | 3.64%   |
| XFCE         | 8         | 3.24%   |
| none+awesome | 4         | 1.62%   |
| X-Generic    | 2         | 0.81%   |
| none+xmonad  | 2         | 0.81%   |
| xsession     | 1         | 0.4%    |
| X-Cinnamon   | 1         | 0.4%    |
| Pantheon     | 1         | 0.4%    |
| none+bspwm   | 1         | 0.4%    |
| MATE         | 1         | 0.4%    |
| LXQt         | 1         | 0.4%    |
| Budgie       | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 40.56%  |
| Wayland | 74        | 29.72%  |
| X11     | 54        | 21.69%  |
| Tty     | 20        | 8.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 121       | 50.63%  |
| GDM     | 43        | 17.99%  |
| SDDM    | 42        | 17.57%  |
| LightDM | 33        | 13.81%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 126       | 52.94%  |
| Unknown    | 60        | 25.21%  |
| en_GB      | 14        | 5.88%   |
| en_AU      | 7         | 2.94%   |
| ru_RU      | 4         | 1.68%   |
| en_DK      | 4         | 1.68%   |
| de_DE      | 4         | 1.68%   |
| fr_FR      | 3         | 1.26%   |
| pt_BR      | 2         | 0.84%   |
| it_IT      | 2         | 0.84%   |
| en_CA      | 2         | 0.84%   |
| de_CH      | 2         | 0.84%   |
| C          | 2         | 0.84%   |
| ro_RO      | 1         | 0.42%   |
| lv_LV      | 1         | 0.42%   |
| es_MX      | 1         | 0.42%   |
| en_NZ      | 1         | 0.42%   |
| en_IN      | 1         | 0.42%   |
| en_IE.UTF8 | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 208       | 87.39%  |
| BIOS | 30        | 12.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 129       | 53.53%  |
| Btrfs   | 41        | 17.01%  |
| Tmpfs   | 23        | 9.54%   |
| Zfs     | 22        | 9.13%   |
| Xfs     | 18        | 7.47%   |
| Unknown | 6         | 2.49%   |
| F2fs    | 1         | 0.41%   |
| Ext2    | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 221       | 92.47%  |
| MBR     | 10        | 4.18%   |
| Unknown | 8         | 3.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 76.86%  |
| Yes       | 56        | 23.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 73%     |
| Yes       | 64        | 27%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 55        | 23.31%  |
| ASUSTek Computer                     | 43        | 18.22%  |
| Dell                                 | 30        | 12.71%  |
| Hewlett-Packard                      | 18        | 7.63%   |
| MSI                                  | 17        | 7.2%    |
| Gigabyte Technology                  | 13        | 5.51%   |
| ASRock                               | 8         | 3.39%   |
| Acer                                 | 8         | 3.39%   |
| Apple                                | 7         | 2.97%   |
| Pine Microsystems                    | 3         | 1.27%   |
| Intel                                | 3         | 1.27%   |
| GPD                                  | 3         | 1.27%   |
| Framework                            | 3         | 1.27%   |
| Supermicro                           | 2         | 0.85%   |
| Raspberry Pi Foundation              | 2         | 0.85%   |
| MECHREVO                             | 2         | 0.85%   |
| Unknown                              | 2         | 0.85%   |
| Toshiba                              | 1         | 0.42%   |
| Teclast                              | 1         | 0.42%   |
| System76                             | 1         | 0.42%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.42%   |
| Samsung Electronics                  | 1         | 0.42%   |
| OBSIDIAN-PC                          | 1         | 0.42%   |
| Microtech                            | 1         | 0.42%   |
| MACHENIKE                            | 1         | 0.42%   |
| LattePanda                           | 1         | 0.42%   |
| HUAWEI                               | 1         | 0.42%   |
| Hardkernel                           | 1         | 0.42%   |
| EVGA                                 | 1         | 0.42%   |
| ECS                                  | 1         | 0.42%   |
| Blackview                            | 1         | 0.42%   |
| AZW                                  | 1         | 0.42%   |
| Avell High Performance               | 1         | 0.42%   |
| Alienware                            | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 3         | 1.27%   |
| MSI MS-7C37                                | 3         | 1.27%   |
| Lenovo 13w Yoga 82S1                       | 3         | 1.27%   |
| ASUS All Series                            | 3         | 1.27%   |
| MSI MS-7C56                                | 2         | 0.85%   |
| HP EliteBook 8470p                         | 2         | 0.85%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 0.85%   |
| Gigabyte B450M DS3H                        | 2         | 0.85%   |
| Framework Laptop                           | 2         | 0.85%   |
| Dell Latitude 7420                         | 2         | 0.85%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 0.85%   |
| ASUS Zenbook UN5401RA UN5401RA_UN5401RA    | 2         | 0.85%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.85%   |
| ASRock Z87 Extreme4                        | 2         | 0.85%   |
| Apple MacBookPro11,5                       | 2         | 0.85%   |
| Apple MacBookPro11,3                       | 2         | 0.85%   |
| Apple iMac17,1                             | 2         | 0.85%   |
| Unknown                                    | 2         | 0.85%   |
| Toshiba Satellite L50-B                    | 1         | 0.42%   |
| Teclast F5                                 | 1         | 0.42%   |
| System76 Pangolin                          | 1         | 0.42%   |
| Supermicro X8DT6                           | 1         | 0.42%   |
| Supermicro X10SLL-F                        | 1         | 0.42%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.42%   |
| Samsung 530U3BI/530U4BI/530U4BH            | 1         | 0.42%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.42%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.42%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.42%   |
| MSI Prestige 16Studio A13VE                | 1         | 0.42%   |
| MSI MS-7C95                                | 1         | 0.42%   |
| MSI MS-7C91                                | 1         | 0.42%   |
| MSI MS-7C84                                | 1         | 0.42%   |
| MSI MS-7C35                                | 1         | 0.42%   |
| MSI MS-7B89                                | 1         | 0.42%   |
| MSI MS-7B09                                | 1         | 0.42%   |
| MSI MS-7758                                | 1         | 0.42%   |
| MSI MS-7681                                | 1         | 0.42%   |
| MSI GE70 2PE                               | 1         | 0.42%   |
| MSI Bravo 15 B5DD                          | 1         | 0.42%   |
| MSI Alpha 15 B5EEK                         | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 32        | 13.56%  |
| ASUS ROG                 | 11        | 4.66%   |
| Dell XPS                 | 9         | 3.81%   |
| ASUS PRIME               | 8         | 3.39%   |
| Dell Latitude            | 7         | 2.97%   |
| Dell Inspiron            | 7         | 2.97%   |
| ASUS Zenbook             | 7         | 2.97%   |
| HP EliteBook             | 6         | 2.54%   |
| Lenovo Legion            | 5         | 2.12%   |
| Lenovo IdeaPad           | 5         | 2.12%   |
| Acer Aspire              | 5         | 2.12%   |
| Dell Precision           | 4         | 1.69%   |
| Apple MacBookPro11       | 4         | 1.69%   |
| Pine Microsystems Pine64 | 3         | 1.27%   |
| MSI MS-7C37              | 3         | 1.27%   |
| Lenovo Yoga              | 3         | 1.27%   |
| Lenovo ThinkBook         | 3         | 1.27%   |
| Lenovo 13w               | 3         | 1.27%   |
| HP EliteDesk             | 3         | 1.27%   |
| Gigabyte X570            | 3         | 1.27%   |
| Gigabyte B450M           | 3         | 1.27%   |
| Framework Laptop         | 3         | 1.27%   |
| ASUS All                 | 3         | 1.27%   |
| RPi Raspberry            | 2         | 0.85%   |
| MSI MS-7C56              | 2         | 0.85%   |
| Lenovo IdeaPadFlex       | 2         | 0.85%   |
| HP ZBook                 | 2         | 0.85%   |
| HP Spectre               | 2         | 0.85%   |
| HP ProBook               | 2         | 0.85%   |
| Gigabyte B550I           | 2         | 0.85%   |
| Dell PowerEdge           | 2         | 0.85%   |
| ASUS TUF                 | 2         | 0.85%   |
| ASRock Z87               | 2         | 0.85%   |
| Apple iMac17             | 2         | 0.85%   |
| Unknown                  | 2         | 0.85%   |
| Toshiba Satellite        | 1         | 0.42%   |
| Teclast F5               | 1         | 0.42%   |
| System76 Pangolin        | 1         | 0.42%   |
| Supermicro X8DT6         | 1         | 0.42%   |
| Supermicro X10SLL-F      | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 37        | 15.68%  |
| 2022    | 30        | 12.71%  |
| 2019    | 27        | 11.44%  |
| 2021    | 23        | 9.75%   |
| 2018    | 21        | 8.9%    |
| 2016    | 14        | 5.93%   |
| 2017    | 13        | 5.51%   |
| 2012    | 12        | 5.08%   |
| 2023    | 11        | 4.66%   |
| 2014    | 11        | 4.66%   |
| 2013    | 11        | 4.66%   |
| 2015    | 10        | 4.24%   |
| 2011    | 6         | 2.54%   |
| Unknown | 6         | 2.54%   |
| 2010    | 2         | 0.85%   |
| 2009    | 1         | 0.42%   |
| 2008    | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 124       | 52.54%  |
| Desktop        | 77        | 32.63%  |
| Convertible    | 19        | 8.05%   |
| Server         | 4         | 1.69%   |
| Phone          | 3         | 1.27%   |
| Mini pc        | 3         | 1.27%   |
| All in one     | 3         | 1.27%   |
| System on chip | 2         | 0.85%   |
| Tablet         | 1         | 0.42%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 233       | 97.9%   |
| Enabled  | 5         | 2.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 235       | 99.58%  |
| Yes  | 1         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 58        | 24.27%  |
| 16.01-24.0      | 54        | 22.59%  |
| 8.01-16.0       | 42        | 17.57%  |
| 64.01-256.0     | 29        | 12.13%  |
| 4.01-8.0        | 28        | 11.72%  |
| 24.01-32.0      | 14        | 5.86%   |
| 3.01-4.0        | 10        | 4.18%   |
| 0.51-1.0        | 2         | 0.84%   |
| More than 256.0 | 1         | 0.42%   |
| 1.01-2.0        | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 69        | 26.54%  |
| 8.01-16.0   | 43        | 16.54%  |
| 3.01-4.0    | 38        | 14.62%  |
| 2.01-3.0    | 36        | 13.85%  |
| 1.01-2.0    | 33        | 12.69%  |
| 16.01-24.0  | 11        | 4.23%   |
| 0.51-1.0    | 10        | 3.85%   |
| 32.01-64.0  | 8         | 3.08%   |
| 24.01-32.0  | 7         | 2.69%   |
| 0.01-0.5    | 4         | 1.54%   |
| 64.01-256.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 140       | 57.38%  |
| 2      | 60        | 24.59%  |
| 3      | 21        | 8.61%   |
| 5      | 7         | 2.87%   |
| 4      | 5         | 2.05%   |
| 6      | 4         | 1.64%   |
| 7      | 2         | 0.82%   |
| 23     | 1         | 0.41%   |
| 17     | 1         | 0.41%   |
| 11     | 1         | 0.41%   |
| 8      | 1         | 0.41%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 88.19%  |
| Yes       | 28        | 11.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 74.48%  |
| No        | 61        | 25.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 78.57%  |
| No        | 51        | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 74.48%  |
| No        | 61        | 25.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 50        | 21.19%  |
| Germany      | 24        | 10.17%  |
| UK           | 16        | 6.78%   |
| Russia       | 14        | 5.93%   |
| Italy        | 13        | 5.51%   |
| France       | 13        | 5.51%   |
| Poland       | 8         | 3.39%   |
| Ukraine      | 7         | 2.97%   |
| Canada       | 7         | 2.97%   |
| Australia    | 7         | 2.97%   |
| Czechia      | 6         | 2.54%   |
| Switzerland  | 5         | 2.12%   |
| Netherlands  | 5         | 2.12%   |
| Austria      | 5         | 2.12%   |
| Norway       | 4         | 1.69%   |
| Brazil       | 4         | 1.69%   |
| Sweden       | 3         | 1.27%   |
| India        | 3         | 1.27%   |
| Denmark      | 3         | 1.27%   |
| Belgium      | 3         | 1.27%   |
| Spain        | 2         | 0.85%   |
| South Africa | 2         | 0.85%   |
| Slovenia     | 2         | 0.85%   |
| Serbia       | 2         | 0.85%   |
| Portugal     | 2         | 0.85%   |
| New Zealand  | 2         | 0.85%   |
| Mexico       | 2         | 0.85%   |
| Japan        | 2         | 0.85%   |
| Iraq         | 2         | 0.85%   |
| Hungary      | 2         | 0.85%   |
| Uzbekistan   | 1         | 0.42%   |
| Uruguay      | 1         | 0.42%   |
| Taiwan       | 1         | 0.42%   |
| Singapore    | 1         | 0.42%   |
| Romania      | 1         | 0.42%   |
| Philippines  | 1         | 0.42%   |
| Peru         | 1         | 0.42%   |
| Latvia       | 1         | 0.42%   |
| Kyrgyzstan   | 1         | 0.42%   |
| Kuwait       | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Perth             | 5         | 2%      |
| Kharkiv           | 5         | 2%      |
| Vienna            | 4         | 1.6%    |
| Milwaukee         | 4         | 1.6%    |
| Marki             | 4         | 1.6%    |
| Frankfurt am Main | 4         | 1.6%    |
| Prague            | 3         | 1.2%    |
| Plymouth          | 3         | 1.2%    |
| Oslo              | 3         | 1.2%    |
| Lyon              | 3         | 1.2%    |
| London            | 3         | 1.2%    |
| Craigsville       | 3         | 1.2%    |
| Chelyabinsk       | 3         | 1.2%    |
| Cerami            | 3         | 1.2%    |
| Amsterdam         | 3         | 1.2%    |
| Southampton       | 2         | 0.8%    |
| South Deerfield   | 2         | 0.8%    |
| Schaafheim        | 2         | 0.8%    |
| Rochester         | 2         | 0.8%    |
| Richardson        | 2         | 0.8%    |
| Reno              | 2         | 0.8%    |
| Ramenskoye        | 2         | 0.8%    |
| Pradamano         | 2         | 0.8%    |
| Phoenix           | 2         | 0.8%    |
| Paris             | 2         | 0.8%    |
| Ottawa            | 2         | 0.8%    |
| Moscow            | 2         | 0.8%    |
| Melbourne         | 2         | 0.8%    |
| Los Angeles       | 2         | 0.8%    |
| Krasnodar         | 2         | 0.8%    |
| Hamburg           | 2         | 0.8%    |
| Halifax           | 2         | 0.8%    |
| Gdansk            | 2         | 0.8%    |
| Darmstadt         | 2         | 0.8%    |
| Catania           | 2         | 0.8%    |
| Cape Town         | 2         | 0.8%    |
| Cambridge         | 2         | 0.8%    |
| Bochum            | 2         | 0.8%    |
| Berlin            | 2         | 0.8%    |
| Benton Harbor     | 2         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 91        | 161    | 25.85%  |
| SanDisk                        | 30        | 36     | 8.52%   |
| WDC                            | 29        | 52     | 8.24%   |
| Seagate                        | 27        | 64     | 7.67%   |
| Toshiba                        | 18        | 34     | 5.11%   |
| Crucial                        | 15        | 22     | 4.26%   |
| Micron Technology              | 14        | 15     | 3.98%   |
| Kingston                       | 14        | 16     | 3.98%   |
| Intel                          | 13        | 20     | 3.69%   |
| Unknown                        | 11        | 15     | 3.13%   |
| SK hynix                       | 11        | 14     | 3.13%   |
| Apple                          | 8         | 14     | 2.27%   |
| Phison Electronics             | 7         | 10     | 1.99%   |
| KIOXIA                         | 5         | 7      | 1.42%   |
| HGST                           | 5         | 15     | 1.42%   |
| Kingston Technology Company    | 4         | 4      | 1.14%   |
| Yangtze Memory Technologies    | 3         | 4      | 0.85%   |
| Hitachi                        | 3         | 6      | 0.85%   |
| Corsair                        | 3         | 3      | 0.85%   |
| A-DATA Technology              | 3         | 3      | 0.85%   |
| Transcend                      | 2         | 2      | 0.57%   |
| SPCC                           | 2         | 2      | 0.57%   |
| Realtek Semiconductor          | 2         | 5      | 0.57%   |
| Plextor                        | 2         | 2      | 0.57%   |
| OCZ                            | 2         | 2      | 0.57%   |
| Micron/Crucial Technology      | 2         | 2      | 0.57%   |
| MAXIO Technology (Hangzhou)    | 2         | 3      | 0.57%   |
| China                          | 2         | 2      | 0.57%   |
| ADATA Technology               | 2         | 4      | 0.57%   |
| ZHITAI                         | 1         | 1      | 0.28%   |
| Teclast                        | 1         | 3      | 0.28%   |
| Team                           | 1         | 1      | 0.28%   |
| Solid State Storage Technology | 1         | 1      | 0.28%   |
| Silicon Motion                 | 1         | 1      | 0.28%   |
| S3+                            | 1         | 1      | 0.28%   |
| Realtek                        | 1         | 1      | 0.28%   |
| PNY                            | 1         | 2      | 0.28%   |
| Phison                         | 1         | 1      | 0.28%   |
| MBED                           | 1         | 1      | 0.28%   |
| LITEONIT                       | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 12        | 2.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 11        | 2.7%    |
| Samsung SSD 860 EVO 500GB                           | 6         | 1.47%   |
| Unknown MMC Card  32GB                              | 5         | 1.23%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 1.23%   |
| SanDisk SSD PLUS 240GB                              | 4         | 0.98%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 0.98%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 0.74%   |
| Samsung SSD 980 1TB                                 | 3         | 0.74%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.74%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.74%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.74%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.74%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.74%   |
| Samsung SSD 850 EVO 500GB                           | 3         | 0.74%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 0.74%   |
| Intel SSDPEKNU010TZ 1TB                             | 3         | 0.74%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.74%   |
| Unknown MMC Card  16GB                              | 2         | 0.49%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.49%   |
| SK hynix PC801 NVMe 512GB                           | 2         | 0.49%   |
| Seagate ST4000VN008-2DR166 4TB                      | 2         | 0.49%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.49%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2         | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2         | 0.49%   |
| Sandisk WD_BLACK SN770 500GB                        | 2         | 0.49%   |
| Sandisk WD Black SN850 1TB                          | 2         | 0.49%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 2         | 0.49%   |
| SanDisk Ultra II 240GB SSD                          | 2         | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.49%   |
| Samsung SSD 990 PRO 1TB                             | 2         | 0.49%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.49%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.49%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.49%   |
| Samsung SSD 860 EVO 2TB                             | 2         | 0.49%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.49%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.49%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 64     | 36.49%  |
| WDC                 | 22        | 42     | 29.73%  |
| Toshiba             | 12        | 25     | 16.22%  |
| HGST                | 5         | 15     | 6.76%   |
| Hitachi             | 3         | 6      | 4.05%   |
| Apple               | 3         | 3      | 4.05%   |
| Samsung Electronics | 2         | 2      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 78     | 32.5%   |
| Crucial             | 14        | 21     | 11.67%  |
| SanDisk             | 13        | 18     | 10.83%  |
| Kingston            | 10        | 11     | 8.33%   |
| Apple               | 6         | 8      | 5%      |
| Intel               | 5         | 7      | 4.17%   |
| WDC                 | 4         | 5      | 3.33%   |
| Corsair             | 3         | 3      | 2.5%    |
| Transcend           | 2         | 2      | 1.67%   |
| SPCC                | 2         | 2      | 1.67%   |
| OCZ                 | 2         | 2      | 1.67%   |
| Micron Technology   | 2         | 2      | 1.67%   |
| China               | 2         | 2      | 1.67%   |
| ZHITAI              | 1         | 1      | 0.83%   |
| Toshiba             | 1         | 1      | 0.83%   |
| Teclast             | 1         | 3      | 0.83%   |
| Team                | 1         | 1      | 0.83%   |
| SK hynix            | 1         | 1      | 0.83%   |
| S3+                 | 1         | 1      | 0.83%   |
| PNY                 | 1         | 2      | 0.83%   |
| Plextor             | 1         | 1      | 0.83%   |
| LITEONIT            | 1         | 1      | 0.83%   |
| LITEON              | 1         | 1      | 0.83%   |
| INNOVATION IT       | 1         | 1      | 0.83%   |
| Dogfish             | 1         | 1      | 0.83%   |
| BIWIN               | 1         | 1      | 0.83%   |
| ASMT                | 1         | 1      | 0.83%   |
| ASMedia             | 1         | 1      | 0.83%   |
| A-DATA Technology   | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 149       | 208    | 46.86%  |
| SSD     | 104       | 180    | 32.7%   |
| HDD     | 53        | 157    | 16.67%  |
| MMC     | 11        | 16     | 3.46%   |
| Unknown | 1         | 1      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 149       | 207    | 52.1%   |
| SATA | 118       | 328    | 41.26%  |
| MMC  | 11        | 16     | 3.85%   |
| SAS  | 8         | 11     | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 141    | 48.55%  |
| 0.51-1.0   | 49        | 80     | 28.32%  |
| 1.01-2.0   | 15        | 20     | 8.67%   |
| 4.01-10.0  | 11        | 55     | 6.36%   |
| 2.01-3.0   | 8         | 14     | 4.62%   |
| 3.01-4.0   | 4         | 17     | 2.31%   |
| 10.01-20.0 | 2         | 10     | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 67        | 27.57%  |
| 1-20           | 55        | 22.63%  |
| 251-500        | 30        | 12.35%  |
| 501-1000       | 25        | 10.29%  |
| 101-250        | 23        | 9.47%   |
| 1001-2000      | 16        | 6.58%   |
| More than 3000 | 14        | 5.76%   |
| 2001-3000      | 10        | 4.12%   |
| 21-50          | 2         | 0.82%   |
| 51-100         | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 29.32%  |
| Unknown        | 67        | 26.91%  |
| 101-250        | 28        | 11.24%  |
| 21-50          | 20        | 8.03%   |
| 51-100         | 19        | 7.63%   |
| 501-1000       | 16        | 6.43%   |
| 251-500        | 11        | 4.42%   |
| 1001-2000      | 6         | 2.41%   |
| More than 3000 | 5         | 2.01%   |
| 2001-3000      | 4         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Computers | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                                         | 2         | 4      | 8.33%   |
| WDC WD30EZRX-00SPEB0 3TB                                       | 1         | 1      | 4.17%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 1         | 1      | 4.17%   |
| WDC WD20EARX-008FB0 2TB                                        | 1         | 1      | 4.17%   |
| WDC WD10EZEX-60ZF5A0 1TB                                       | 1         | 1      | 4.17%   |
| WDC WD10 JPLX-00MBPT0 1TB                                      | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                                         | 1         | 1      | 4.17%   |
| Toshiba MK2565GSXV 250GB                                       | 1         | 1      | 4.17%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                           | 1         | 1      | 4.17%   |
| Seagate ST8000VN004-2M2101 8TB                                 | 1         | 3      | 4.17%   |
| Seagate ST8000VN0022-2EL112 8TB                                | 1         | 1      | 4.17%   |
| Seagate ST3500418AS 500GB                                      | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 970 EVO 1TB                            | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1         | 1      | 4.17%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1      | 4.17%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 1      | 4.17%   |
| Intel SSDSC2BW240A4 240GB                                      | 1         | 1      | 4.17%   |
| Hitachi HDS722020ALA330 2TB                                    | 1         | 1      | 4.17%   |
| HGST HTS545050A7E680 500GB                                     | 1         | 1      | 4.17%   |
| Crucial CT240M500SSD1 240GB                                    | 1         | 1      | 4.17%   |
| Corsair Neutron XT SSD 240GB                                   | 1         | 1      | 4.17%   |
| Corsair Force GS 240GB SSD                                     | 1         | 1      | 4.17%   |
| ASMT 2115 1TB                                                  | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 20.83%  |
| Seagate             | 3         | 5      | 12.5%   |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 2      | 8.33%   |
| SanDisk             | 2         | 4      | 8.33%   |
| Corsair             | 2         | 2      | 8.33%   |
| SK hynix            | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| ASMT                | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 41.67%  |
| Seagate | 3         | 5      | 25%     |
| Toshiba | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 14     | 47.83%  |
| SSD  | 9         | 11     | 39.13%  |
| NVMe | 3         | 3      | 13.04%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 25%     |
| Toshiba HDWG180 8TB                              | 1         | 4      | 25%     |
| SK hynix BC501 NVMe Solid State Drive 512GB      | 1         | 1      | 25%     |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 50%     |
| SK hynix            | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 222       | 480    | 82.22%  |
| Detected | 26        | 47     | 9.63%   |
| Malfunc  | 18        | 28     | 6.67%   |
| Failed   | 4         | 7      | 1.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 118       | 34.71%  |
| Samsung Electronics            | 64        | 18.82%  |
| AMD                            | 50        | 14.71%  |
| SanDisk                        | 22        | 6.47%   |
| Micron Technology              | 12        | 3.53%   |
| SK hynix                       | 10        | 2.94%   |
| ASMedia Technology             | 9         | 2.65%   |
| Phison Electronics             | 8         | 2.35%   |
| Kingston Technology Company    | 8         | 2.35%   |
| Toshiba America Info Systems   | 6         | 1.76%   |
| KIOXIA                         | 5         | 1.47%   |
| LSI Logic / Symbios Logic      | 4         | 1.18%   |
| ADATA Technology               | 4         | 1.18%   |
| Yangtze Memory Technologies    | 3         | 0.88%   |
| Micron/Crucial Technology      | 3         | 0.88%   |
| Broadcom / LSI                 | 3         | 0.88%   |
| Realtek Semiconductor          | 2         | 0.59%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.59%   |
| Marvell Technology Group       | 2         | 0.59%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Silicon Motion                 | 1         | 0.29%   |
| Shenzhen Longsys Electronics   | 1         | 0.29%   |
| Lite-On Technology             | 1         | 0.29%   |
| Biwin Storage Technology       | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 9.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 30        | 8.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 17        | 4.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 3.3%    |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 3.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 3.02%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 2.47%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 8         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 2.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 1.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.65%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 1.37%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 4         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.1%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.82%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.82%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3         | 0.82%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 148       | 45.26%  |
| SATA | 144       | 44.04%  |
| RAID | 23        | 7.03%   |
| SAS  | 6         | 1.83%   |
| IDE  | 6         | 1.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 150       | 63.56%  |
| AMD     | 80        | 33.9%   |
| ARM     | 5         | 2.12%   |
| Unknown | 1         | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor          | 6         | 2.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 2.12%   |
| ARM Processor                              | 5         | 2.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 1.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 1.69%   |
| Intel 12th Gen Core i7-1260P               | 4         | 1.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 4         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 4         | 1.69%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 4         | 1.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 4         | 1.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 1.69%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 4         | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 1.27%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 3         | 1.27%   |
| Intel 12th Gen Core i5-1240P               | 3         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.27%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 3         | 1.27%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 3         | 1.27%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 1.27%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 0.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 2         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 2         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 0.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 2         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 2         | 0.85%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 2         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 2         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 2         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 2         | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 2         | 0.85%   |
| Intel 12th Gen Core i7-1255U               | 2         | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 2         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 55        | 23.31%  |
| Other                  | 42        | 17.8%   |
| Intel Core i5          | 35        | 14.83%  |
| AMD Ryzen 7            | 27        | 11.44%  |
| AMD Ryzen 5            | 24        | 10.17%  |
| AMD Ryzen 9            | 16        | 6.78%   |
| Intel Xeon             | 8         | 3.39%   |
| AMD Ryzen 7 PRO        | 8         | 3.39%   |
| Intel Celeron          | 6         | 2.54%   |
| Intel Core i3          | 5         | 2.12%   |
| AMD Ryzen Threadripper | 3         | 1.27%   |
| Intel Core i9          | 2         | 0.85%   |
| Intel Pentium Gold     | 1         | 0.42%   |
| Intel Core m3          | 1         | 0.42%   |
| Intel Atom             | 1         | 0.42%   |
| AMD FX                 | 1         | 0.42%   |
| AMD Athlon II X4       | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 76        | 32.2%   |
| 8       | 47        | 19.92%  |
| 2       | 36        | 15.25%  |
| 6       | 34        | 14.41%  |
| 12      | 15        | 6.36%   |
| 16      | 8         | 3.39%   |
| 10      | 5         | 2.12%   |
| Unknown | 5         | 2.12%   |
| 24      | 4         | 1.69%   |
| 14      | 4         | 1.69%   |
| 32      | 1         | 0.42%   |
| 1       | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 228       | 96.61%  |
| Unknown | 5         | 2.12%   |
| 2       | 3         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 208       | 88.14%  |
| 1       | 23        | 9.75%   |
| Unknown | 5         | 2.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 234       | 98.73%  |
| 64-bit         | 1         | 0.42%   |
| 32-bit         | 1         | 0.42%   |
| Unknown        | 1         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 23.77%  |
| 0x306c3    | 13        | 5.33%   |
| 0x0a50000c | 13        | 5.33%   |
| 0x806c1    | 9         | 3.69%   |
| 0x306a9    | 9         | 3.69%   |
| 0x806ea    | 8         | 3.28%   |
| 0x08701021 | 8         | 3.28%   |
| 0x0a50000d | 7         | 2.87%   |
| 0x906ea    | 6         | 2.46%   |
| 0x506e3    | 6         | 2.46%   |
| 0x0a404102 | 6         | 2.46%   |
| 0x08600106 | 6         | 2.46%   |
| 0x806ec    | 4         | 1.64%   |
| 0x806eb    | 4         | 1.64%   |
| 0x806e9    | 4         | 1.64%   |
| 0x406e3    | 4         | 1.64%   |
| 0x40651    | 4         | 1.64%   |
| 0x306d4    | 4         | 1.64%   |
| 0x08701013 | 4         | 1.64%   |
| 0x906e9    | 3         | 1.23%   |
| 0x906a4    | 3         | 1.23%   |
| 0x906a3    | 3         | 1.23%   |
| 0x706a1    | 3         | 1.23%   |
| 0x40661    | 3         | 1.23%   |
| 0x0a704103 | 3         | 1.23%   |
| 0x0a601203 | 3         | 1.23%   |
| 0xa0653    | 2         | 0.82%   |
| 0x906ed    | 2         | 0.82%   |
| 0x706a8    | 2         | 0.82%   |
| 0x0a20120a | 2         | 0.82%   |
| 0x0a201204 | 2         | 0.82%   |
| 0x0a201025 | 2         | 0.82%   |
| 0x0a201016 | 2         | 0.82%   |
| 0x0a201009 | 2         | 0.82%   |
| 0x08600104 | 2         | 0.82%   |
| 0x08108109 | 2         | 0.82%   |
| 0x08001138 | 2         | 0.82%   |
| 0xb06a2    | 1         | 0.41%   |
| 0xa0652    | 1         | 0.41%   |
| 0x90672    | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 16.53%  |
| Zen 3            | 31        | 13.14%  |
| Unknown          | 25        | 10.59%  |
| Zen 2            | 23        | 9.75%   |
| Haswell          | 22        | 9.32%   |
| Alderlake Hybrid | 18        | 7.63%   |
| Skylake          | 16        | 6.78%   |
| TigerLake        | 13        | 5.51%   |
| IvyBridge        | 13        | 5.51%   |
| Goldmont plus    | 6         | 2.54%   |
| Zen+             | 5         | 2.12%   |
| Broadwell        | 5         | 2.12%   |
| Zen              | 4         | 1.69%   |
| CometLake        | 4         | 1.69%   |
| Icelake          | 3         | 1.27%   |
| Westmere         | 2         | 0.85%   |
| SandyBridge      | 2         | 0.85%   |
| Piledriver       | 1         | 0.42%   |
| Nehalem          | 1         | 0.42%   |
| K10 Llano        | 1         | 0.42%   |
| Gracemont        | 1         | 0.42%   |
| Bonnell          | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 119       | 41.9%   |
| AMD                        | 82        | 28.87%  |
| Nvidia                     | 79        | 27.82%  |
| Matrox Electronics Systems | 3         | 1.06%   |
| ASPEED Technology          | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 15        | 5.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 11        | 3.79%   |
| Intel UHD Graphics 620                                                                | 9         | 3.1%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 8         | 2.76%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 8         | 2.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 2.41%   |
| AMD Rembrandt [Radeon 680M]                                                           | 7         | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.07%   |
| Intel HD Graphics 620                                                                 | 6         | 2.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 2.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 6         | 2.07%   |
| Intel HD Graphics 530                                                                 | 5         | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 1.72%   |
| AMD Barcelo                                                                           | 5         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.38%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 1.38%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.03%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.03%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 3         | 1.03%   |
| Intel HD Graphics 630                                                                 | 3         | 1.03%   |
| Intel HD Graphics 5500                                                                | 3         | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.03%   |
| AMD Phoenix1                                                                          | 3         | 1.03%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                         | 3         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 2         | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 2         | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 2         | 0.69%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 2         | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 31.65%  |
| 1 x AMD        | 58        | 24.47%  |
| Intel + Nvidia | 34        | 14.35%  |
| 1 x Nvidia     | 33        | 13.92%  |
| AMD + Nvidia   | 12        | 5.06%   |
| Other          | 7         | 2.95%   |
| Intel + AMD    | 7         | 2.95%   |
| 2 x AMD        | 4         | 1.69%   |
| 1 x Matrox     | 3         | 1.27%   |
| 2 x Intel      | 2         | 0.84%   |
| 1 x ASPEED     | 1         | 0.42%   |
| AMD + ASPEED   | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 170       | 71.73%  |
| Proprietary | 54        | 22.78%  |
| Unknown     | 13        | 5.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 62.66%  |
| 0.01-0.5   | 28        | 11.62%  |
| 1.01-2.0   | 19        | 7.88%   |
| 7.01-8.0   | 16        | 6.64%   |
| 3.01-4.0   | 12        | 4.98%   |
| 8.01-16.0  | 7         | 2.9%    |
| 0.51-1.0   | 7         | 2.9%    |
| 16.01-24.0 | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 32        | 12.45%  |
| Dell                 | 29        | 11.28%  |
| Samsung Electronics  | 26        | 10.12%  |
| BOE                  | 24        | 9.34%   |
| Goldstar             | 18        | 7%      |
| LG Display           | 17        | 6.61%   |
| Chimei Innolux       | 17        | 6.61%   |
| Acer                 | 11        | 4.28%   |
| Sharp                | 9         | 3.5%    |
| Hewlett-Packard      | 7         | 2.72%   |
| Apple                | 7         | 2.72%   |
| PANDA                | 6         | 2.33%   |
| CSO                  | 6         | 2.33%   |
| Ancor Communications | 5         | 1.95%   |
| Philips              | 4         | 1.56%   |
| Iiyama               | 4         | 1.56%   |
| AOC                  | 4         | 1.56%   |
| ViewSonic            | 3         | 1.17%   |
| Panasonic            | 2         | 0.78%   |
| Lenovo               | 2         | 0.78%   |
| InfoVision           | 2         | 0.78%   |
| HannStar             | 2         | 0.78%   |
| Gigabyte Technology  | 2         | 0.78%   |
| Eizo                 | 2         | 0.78%   |
| BenQ                 | 2         | 0.78%   |
| ASUSTek Computer     | 2         | 0.78%   |
| WST                  | 1         | 0.39%   |
| Vizio                | 1         | 0.39%   |
| Valve                | 1         | 0.39%   |
| Unknown (AAA)        | 1         | 0.39%   |
| Toshiba              | 1         | 0.39%   |
| TMX                  | 1         | 0.39%   |
| RTK                  | 1         | 0.39%   |
| NEC Computers        | 1         | 0.39%   |
| MSI                  | 1         | 0.39%   |
| MPI                  | 1         | 0.39%   |
| JDI                  | 1         | 0.39%   |
| HVR                  | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 1.53%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 1.15%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch        | 3         | 1.15%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.76%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 0.76%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.76%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 0.76%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 0.76%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 0.76%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 0.76%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 2         | 0.76%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch        | 2         | 0.76%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                      | 2         | 0.76%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 0.76%   |
| WST KL.1350W.005 WST2C34 2256x1504 285x190mm 13.5-inch                | 1         | 0.38%   |
| Vizio E550i-B2 VIZ1004 1920x1080 477x268mm 21.5-inch                  | 1         | 0.38%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch         | 1         | 0.38%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1         | 0.38%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.38%   |
| Valve Index HMD VLV91A8                                               | 1         | 0.38%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.38%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.38%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.38%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.38%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 39.59%  |
| 3840x2160 (4K)     | 35        | 14.29%  |
| 2560x1440 (QHD)    | 23        | 9.39%   |
| 2880x1800          | 14        | 5.71%   |
| 1366x768 (WXGA)    | 14        | 5.71%   |
| 2560x1600          | 11        | 4.49%   |
| 1920x1200 (WUXGA)  | 11        | 4.49%   |
| 1280x1024 (SXGA)   | 8         | 3.27%   |
| 3440x1440          | 5         | 2.04%   |
| 1600x900 (HD+)     | 5         | 2.04%   |
| 2560x1080          | 4         | 1.63%   |
| 2256x1504          | 4         | 1.63%   |
| 1680x1050 (WSXGA+) | 3         | 1.22%   |
| 3840x2400          | 2         | 0.82%   |
| 3840x1200          | 1         | 0.41%   |
| 3000x2000          | 1         | 0.41%   |
| 2160x1200          | 1         | 0.41%   |
| 1920x1280          | 1         | 0.41%   |
| 1440x900 (WXGA+)   | 1         | 0.41%   |
| 1280x800 (WXGA)    | 1         | 0.41%   |
| 1280x720 (HD)      | 1         | 0.41%   |
| 1024x600           | 1         | 0.41%   |
| Unknown            | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 43        | 17.2%   |
| 14      | 39        | 15.6%   |
| 13      | 32        | 12.8%   |
| 27      | 29        | 11.6%   |
| 24      | 20        | 8%      |
| 23      | 15        | 6%      |
| 17      | 11        | 4.4%    |
| 34      | 9         | 3.6%    |
| 16      | 8         | 3.2%    |
| 12      | 8         | 3.2%    |
| 31      | 7         | 2.8%    |
| 21      | 5         | 2%      |
| 19      | 4         | 1.6%    |
| 20      | 3         | 1.2%    |
| 25      | 2         | 0.8%    |
| 22      | 2         | 0.8%    |
| Unknown | 2         | 0.8%    |
| 86      | 1         | 0.4%    |
| 84      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 46      | 1         | 0.4%    |
| 43      | 1         | 0.4%    |
| 39      | 1         | 0.4%    |
| 38      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 26      | 1         | 0.4%    |
| 11      | 1         | 0.4%    |
| 10      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 41.22%  |
| 501-600     | 62        | 25.31%  |
| 201-300     | 33        | 13.47%  |
| 351-400     | 12        | 4.9%    |
| 401-500     | 10        | 4.08%   |
| 701-800     | 9         | 3.67%   |
| 601-700     | 9         | 3.67%   |
| 1001-1500   | 4         | 1.63%   |
| 801-900     | 2         | 0.82%   |
| Unknown     | 2         | 0.82%   |
| 1501-2000   | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 67.56%  |
| 16/10   | 46        | 20.44%  |
| 21/9    | 9         | 4%      |
| 5/4     | 7         | 3.11%   |
| 3/2     | 6         | 2.67%   |
| 6/5     | 1         | 0.44%   |
| 3.20    | 1         | 0.44%   |
| 1.00    | 1         | 0.44%   |
| 0.56    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 55        | 22%     |
| 101-110        | 44        | 17.6%   |
| 201-250        | 32        | 12.8%   |
| 301-350        | 30        | 12%     |
| 351-500        | 17        | 6.8%    |
| 71-80          | 15        | 6%      |
| 251-300        | 10        | 4%      |
| 151-200        | 9         | 3.6%    |
| 61-70          | 8         | 3.2%    |
| 121-130        | 7         | 2.8%    |
| 111-120        | 7         | 2.8%    |
| 141-150        | 4         | 1.6%    |
| 501-1000       | 4         | 1.6%    |
| More than 1000 | 3         | 1.2%    |
| Unknown        | 2         | 0.8%    |
| 51-60          | 1         | 0.4%    |
| 41-50          | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 64        | 26.89%  |
| 51-100        | 57        | 23.95%  |
| 161-240       | 53        | 22.27%  |
| 101-120       | 37        | 15.55%  |
| More than 240 | 22        | 9.24%   |
| 1-50          | 3         | 1.26%   |
| Unknown       | 2         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 165       | 68.18%  |
| 2     | 42        | 17.36%  |
| 0     | 26        | 10.74%  |
| 3     | 9         | 3.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 152       | 44.97%  |
| Realtek Semiconductor             | 106       | 31.36%  |
| MediaTek                          | 17        | 5.03%   |
| Qualcomm Atheros                  | 16        | 4.73%   |
| Broadcom                          | 12        | 3.55%   |
| Aquantia                          | 5         | 1.48%   |
| Qualcomm                          | 4         | 1.18%   |
| TP-Link                           | 3         | 0.89%   |
| Lenovo                            | 3         | 0.89%   |
| Ralink Technology                 | 2         | 0.59%   |
| Microsoft                         | 2         | 0.59%   |
| Xiaomi                            | 1         | 0.3%    |
| Texas Instruments                 | 1         | 0.3%    |
| STMicroelectronics                | 1         | 0.3%    |
| Standard Microsystems             | 1         | 0.3%    |
| Ralink                            | 1         | 0.3%    |
| QinHeng Electronics               | 1         | 0.3%    |
| Pulse-Eight                       | 1         | 0.3%    |
| Oculus VR                         | 1         | 0.3%    |
| ICS Advent                        | 1         | 0.3%    |
| Google                            | 1         | 0.3%    |
| Fibocom                           | 1         | 0.3%    |
| Ericsson Business Mobile Networks | 1         | 0.3%    |
| Edimax Technology                 | 1         | 0.3%    |
| D-Link System                     | 1         | 0.3%    |
| D-Link                            | 1         | 0.3%    |
| ASUSTek Computer                  | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 16.87%  |
| Intel Wi-Fi 6 AX200                                               | 24        | 5.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 5.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 2.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 12        | 2.98%   |
| Intel Ethernet Controller I225-V                                  | 11        | 2.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 2.23%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 8         | 1.99%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.99%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.99%   |
| Intel Wireless 8260                                               | 7         | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.49%   |
| Intel Wireless 7265                                               | 6         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.24%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.24%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 0.99%   |
| Intel Wireless-AC 9260                                            | 4         | 0.99%   |
| Intel Wireless 7260                                               | 4         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.99%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.74%   |
| Intel Wireless 3160                                               | 3         | 0.74%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 3         | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 125       | 65.1%   |
| MediaTek                          | 17        | 8.85%   |
| Realtek Semiconductor             | 12        | 6.25%   |
| Qualcomm Atheros                  | 12        | 6.25%   |
| Broadcom                          | 9         | 4.69%   |
| TP-Link                           | 3         | 1.56%   |
| Qualcomm                          | 3         | 1.56%   |
| Ralink Technology                 | 2         | 1.04%   |
| Microsoft                         | 2         | 1.04%   |
| Ralink                            | 1         | 0.52%   |
| Fibocom                           | 1         | 0.52%   |
| Ericsson Business Mobile Networks | 1         | 0.52%   |
| Edimax Technology                 | 1         | 0.52%   |
| D-Link System                     | 1         | 0.52%   |
| D-Link                            | 1         | 0.52%   |
| ASUSTek Computer                  | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 24        | 12.5%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 12        | 6.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 9         | 4.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 8         | 4.17%   |
| Intel Wireless 8265 / 8275                                    | 8         | 4.17%   |
| Intel Wi-Fi 6 AX201                                           | 8         | 4.17%   |
| Intel Wireless 8260                                           | 7         | 3.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 6         | 3.13%   |
| Intel Wireless 7265                                           | 6         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 2.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 5         | 2.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 4         | 2.08%   |
| Intel Wireless-AC 9260                                        | 4         | 2.08%   |
| Intel Wireless 7260                                           | 4         | 2.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 2.08%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 4         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 1.56%   |
| Intel Wireless 3160                                           | 3         | 1.56%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 3         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.04%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 2         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 1.04%   |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 1.04%   |
| Intel Wireless 3165                                           | 2         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.04%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2         | 1.04%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2         | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.52%   |
| TP-Link 802.11ac NIC                                          | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 0.52%   |
| Realtek 802.11ac NIC                                          | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 97        | 49.49%  |
| Intel                 | 73        | 37.24%  |
| Broadcom              | 8         | 4.08%   |
| Qualcomm Atheros      | 5         | 2.55%   |
| Aquantia              | 5         | 2.55%   |
| Lenovo                | 3         | 1.53%   |
| Xiaomi                | 1         | 0.51%   |
| Standard Microsystems | 1         | 0.51%   |
| Qualcomm              | 1         | 0.51%   |
| ICS Advent            | 1         | 0.51%   |
| Google                | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 33.17%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 10.24%  |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 5.85%   |
| Intel Ethernet Controller I225-V                                  | 11        | 5.37%   |
| Intel I211 Gigabit Network Connection                             | 9         | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.41%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.93%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.44%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 1.46%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.46%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.46%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.98%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.98%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.98%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.49%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.49%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.49%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.49%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.49%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.49%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.49%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.49%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.49%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 49.86%  |
| Ethernet | 179       | 48.51%  |
| Modem    | 5         | 1.36%   |
| Unknown  | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 157       | 63.82%  |
| Ethernet | 89        | 36.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 112       | 47.06%  |
| 1     | 110       | 46.22%  |
| 3     | 9         | 3.78%   |
| 0     | 6         | 2.52%   |
| 4     | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 73.03%  |
| Yes  | 65        | 26.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 61.67%  |
| Realtek Semiconductor           | 12        | 6.67%   |
| MediaTek                        | 7         | 3.89%   |
| Foxconn / Hon Hai               | 7         | 3.89%   |
| Cambridge Silicon Radio         | 7         | 3.89%   |
| Broadcom                        | 7         | 3.89%   |
| Apple                           | 7         | 3.89%   |
| Qualcomm Atheros Communications | 6         | 3.33%   |
| ASUSTek Computer                | 5         | 2.78%   |
| IMC Networks                    | 4         | 2.22%   |
| USI                             | 2         | 1.11%   |
| Lite-On Technology              | 2         | 1.11%   |
| Realtek                         | 1         | 0.56%   |
| Integrated System Solution      | 1         | 0.56%   |
| HTC (High Tech Computer)        | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 26        | 14.44%  |
| Intel AX200 Bluetooth                                                | 22        | 12.22%  |
| Intel Bluetooth Device                                               | 16        | 8.89%   |
| Intel AX201 Bluetooth                                                | 16        | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 15        | 8.33%   |
| Realtek Bluetooth Radio                                              | 10        | 5.56%   |
| Intel AX210 Bluetooth                                                | 8         | 4.44%   |
| MediaTek Wireless_Device                                             | 7         | 3.89%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7         | 3.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7         | 3.89%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4         | 2.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4         | 2.22%   |
| Apple Bluetooth Host Controller                                      | 4         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 1.67%   |
| Apple Bluetooth USB Host Controller                                  | 3         | 1.67%   |
| USI Bluetooth Device                                                 | 2         | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2         | 1.11%   |
| IMC Networks Wireless_Device                                         | 2         | 1.11%   |
| Broadcom HP Portable SoftSailing                                     | 2         | 1.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 1.11%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 1         | 0.56%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 0.56%   |
| Realtek Bluetooth Radio                                              | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1         | 0.56%   |
| Integrated System Solution Bluetooth Device                          | 1         | 0.56%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.56%   |
| IMC Networks BCM20702A0                                              | 1         | 0.56%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.56%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 0.56%   |
| ASUS Bluetooth Device                                                | 1         | 0.56%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 147       | 39.84%  |
| AMD                                  | 91        | 24.66%  |
| Nvidia                               | 59        | 15.99%  |
| C-Media Electronics                  | 9         | 2.44%   |
| Lenovo                               | 5         | 1.36%   |
| Texas Instruments                    | 4         | 1.08%   |
| Kingston Technology                  | 4         | 1.08%   |
| Creative Technology                  | 4         | 1.08%   |
| Sennheiser Communications            | 3         | 0.81%   |
| Realtek Semiconductor                | 3         | 0.81%   |
| Razer USA                            | 3         | 0.81%   |
| Focusrite-Novation                   | 3         | 0.81%   |
| ASUSTek Computer                     | 3         | 0.81%   |
| Synaptics                            | 2         | 0.54%   |
| RODE Microphones                     | 2         | 0.54%   |
| Yamaha                               | 1         | 0.27%   |
| Valve Software                       | 1         | 0.27%   |
| Trust                                | 1         | 0.27%   |
| Thomann                              | 1         | 0.27%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.27%   |
| Sony                                 | 1         | 0.27%   |
| Shure                                | 1         | 0.27%   |
| Schiit Audio                         | 1         | 0.27%   |
| Satechi                              | 1         | 0.27%   |
| PreSonus Audio Electronics           | 1         | 0.27%   |
| Logitech                             | 1         | 0.27%   |
| JMTek                                | 1         | 0.27%   |
| Huawei Technologies                  | 1         | 0.27%   |
| Hewlett-Packard                      | 1         | 0.27%   |
| GYROCOM C&C                          | 1         | 0.27%   |
| GN Netcom                            | 1         | 0.27%   |
| Giga-Byte Technology                 | 1         | 0.27%   |
| Edifier Technology                   | 1         | 0.27%   |
| Dell                                 | 1         | 0.27%   |
| Creative Labs                        | 1         | 0.27%   |
| Corsair                              | 1         | 0.27%   |
| Conexant Systems                     | 1         | 0.27%   |
| Blue Microphones                     | 1         | 0.27%   |
| ASRock                               | 1         | 0.27%   |
| Apogee Electronics                   | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 44        | 9.8%    |
| AMD Renoir Radeon High Definition Audio Controller                      | 28        | 6.24%   |
| AMD Starship/Matisse HD Audio Controller                                | 24        | 5.35%   |
| Intel Sunrise Point-LP HD Audio                                         | 23        | 5.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 14        | 3.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 13        | 2.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 12        | 2.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 12        | 2.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 11        | 2.45%   |
| Intel Cannon Lake PCH cAVS                                              | 10        | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 8         | 1.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 8         | 1.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 7         | 1.56%   |
| AMD Navi 10 HDMI Audio                                                  | 7         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 6         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 6         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 6         | 1.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 6         | 1.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 6         | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 1.11%   |
| Nvidia Audio device                                                     | 5         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                           | 4         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 0.89%   |
| Nvidia GP104 High Definition Audio Controller                           | 4         | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 0.89%   |
| Nvidia GA106 High Definition Audio Controller                           | 4         | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                           | 4         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 4         | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 0.89%   |
| Intel Haswell-ULT HD Audio Controller                                   | 4         | 0.89%   |
| Intel Comet Lake PCH cAVS                                               | 4         | 0.89%   |
| Intel Broadwell-U Audio Controller                                      | 4         | 0.89%   |
| Intel 8 Series HD Audio Controller                                      | 4         | 0.89%   |
| Texas Instruments PCM2902 Audio Codec                                   | 3         | 0.67%   |
| Realtek Semiconductor USB Audio                                         | 3         | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 3         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                           | 3         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 3         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                      | 3         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                      | 3         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 59        | 21.93%  |
| SK hynix                     | 39        | 14.5%   |
| Kingston                     | 34        | 12.64%  |
| Micron Technology            | 33        | 12.27%  |
| Corsair                      | 26        | 9.67%   |
| Crucial                      | 18        | 6.69%   |
| G.Skill                      | 17        | 6.32%   |
| Unknown                      | 9         | 3.35%   |
| Team                         | 6         | 2.23%   |
| Unknown (ABCD)               | 5         | 1.86%   |
| A-DATA Technology            | 5         | 1.86%   |
| Ramaxel Technology           | 3         | 1.12%   |
| Unknown                      | 3         | 1.12%   |
| Goodram                      | 2         | 0.74%   |
| AMD                          | 2         | 0.74%   |
| Unknown (0x59B)              | 1         | 0.37%   |
| Strontium                    | 1         | 0.37%   |
| Smart Brazil                 | 1         | 0.37%   |
| Patriot Memory (PDP Systems) | 1         | 0.37%   |
| Patriot                      | 1         | 0.37%   |
| GLOWAY                       | 1         | 0.37%   |
| Avant                        | 1         | 0.37%   |
| Apacer                       | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.39%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 3         | 1.04%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.04%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 1.04%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.04%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 1.04%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 1.04%   |
| Unknown                                                          | 3         | 1.04%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.69%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.69%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.69%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.69%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 2         | 0.69%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 2         | 0.69%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 2         | 0.69%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 2         | 0.69%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.69%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 2         | 0.69%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 0.69%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 0.69%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 0.69%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 0.69%   |
| Corsair RAM Module 16GB DIMM DDR4 2133MT/s                       | 2         | 0.69%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 2         | 0.69%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.35%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.35%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.35%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.35%   |
| Unknown RAM 3733 C17 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 128       | 56.64%  |
| DDR3   | 45        | 19.91%  |
| LPDDR5 | 19        | 8.41%   |
| LPDDR4 | 17        | 7.52%   |
| DDR5   | 9         | 3.98%   |
| LPDDR3 | 6         | 2.65%   |
| SDRAM  | 1         | 0.44%   |
| DDR    | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 50.43%  |
| DIMM         | 73        | 31.47%  |
| Row Of Chips | 37        | 15.95%  |
| Chip         | 3         | 1.29%   |
| RIMM         | 1         | 0.43%   |
| Unknown      | 1         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 109       | 42.75%  |
| 16384 | 67        | 26.27%  |
| 4096  | 44        | 17.25%  |
| 32768 | 29        | 11.37%  |
| 2048  | 5         | 1.96%   |
| 1024  | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 59        | 23.41%  |
| 1600    | 34        | 13.49%  |
| 2667    | 28        | 11.11%  |
| 2400    | 19        | 7.54%   |
| 2133    | 19        | 7.54%   |
| 6400    | 18        | 7.14%   |
| 3600    | 10        | 3.97%   |
| 4267    | 8         | 3.17%   |
| 3733    | 6         | 2.38%   |
| 1867    | 6         | 2.38%   |
| 1333    | 6         | 2.38%   |
| 4800    | 4         | 1.59%   |
| 3266    | 4         | 1.59%   |
| 3000    | 4         | 1.59%   |
| 5600    | 3         | 1.19%   |
| 4266    | 3         | 1.19%   |
| 6000    | 2         | 0.79%   |
| 3400    | 2         | 0.79%   |
| 3334    | 2         | 0.79%   |
| 2933    | 2         | 0.79%   |
| 7500    | 1         | 0.4%    |
| 5200    | 1         | 0.4%    |
| 4000    | 1         | 0.4%    |
| 3866    | 1         | 0.4%    |
| 3666    | 1         | 0.4%    |
| 3534    | 1         | 0.4%    |
| 2800    | 1         | 0.4%    |
| 2134    | 1         | 0.4%    |
| 2132    | 1         | 0.4%    |
| 1866    | 1         | 0.4%    |
| 1334    | 1         | 0.4%    |
| 1066    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Xerox  | 1         | 50%     |
| Canon  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Xerox Phaser 6125N  | 1         | 50%     |
| Canon TR8500 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 16.45%  |
| IMC Networks                           | 21        | 13.82%  |
| Logitech                               | 20        | 13.16%  |
| Microdia                               | 15        | 9.87%   |
| Bison Electronics                      | 15        | 9.87%   |
| Realtek Semiconductor                  | 13        | 8.55%   |
| Sunplus Innovation Technology          | 7         | 4.61%   |
| Syntek                                 | 4         | 2.63%   |
| Apple                                  | 4         | 2.63%   |
| Quanta                                 | 3         | 1.97%   |
| MacroSilicon                           | 3         | 1.97%   |
| Lite-On Technology                     | 3         | 1.97%   |
| Acer                                   | 3         | 1.97%   |
| Primax Electronics                     | 2         | 1.32%   |
| Luxvisions Innotech Limited            | 2         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.32%   |
| Alcor Micro                            | 2         | 1.32%   |
| Valve Software                         | 1         | 0.66%   |
| SunplusIT                              | 1         | 0.66%   |
| Sonix Technology                       | 1         | 0.66%   |
| Silicon Motion                         | 1         | 0.66%   |
| Samsung Electronics                    | 1         | 0.66%   |
| OPPO Electronics                       | 1         | 0.66%   |
| Microsoft                              | 1         | 0.66%   |
| HD 2MP WEBCAM                          | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 16        | 10.39%  |
| IMC Networks USB2.0 HD UVC WebCam       | 10        | 6.49%   |
| Bison Integrated Camera                 | 9         | 5.84%   |
| IMC Networks Integrated Camera          | 8         | 5.19%   |
| Microdia Integrated_Webcam_HD           | 7         | 4.55%   |
| Realtek Integrated_Webcam_HD            | 6         | 3.9%    |
| Logitech HD Pro Webcam C920             | 5         | 3.25%   |
| Chicony HP HD Camera                    | 5         | 3.25%   |
| Syntek Integrated Camera                | 4         | 2.6%    |
| Logitech StreamCam                      | 4         | 2.6%    |
| Sunplus Integrated_Webcam_FHD           | 3         | 1.95%   |
| MacroSilicon USB Video                  | 3         | 1.95%   |
| Sunplus Integrated_Webcam_HD            | 2         | 1.3%    |
| Realtek Laptop Camera                   | 2         | 1.3%    |
| Quanta VGA WebCam                       | 2         | 1.3%    |
| Primax HP HD Webcam [Fixed]             | 2         | 1.3%    |
| Microdia Webcam Vitade AF               | 2         | 1.3%    |
| Microdia Integrated Webcam              | 2         | 1.3%    |
| Logitech Webcam C270                    | 2         | 1.3%    |
| Lite-On Integrated Camera               | 2         | 1.3%    |
| Bison Integrated IR Camera              | 2         | 1.3%    |
| Bison HD Webcam                         | 2         | 1.3%    |
| Apple FaceTime HD Camera (Built-in)     | 2         | 1.3%    |
| Alcor Micro USB 2.0 Camera              | 2         | 1.3%    |
| Valve Software 3D Camera                | 1         | 0.65%   |
| SunplusIT MTD camera                    | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD    | 1         | 0.65%   |
| Sunplus HD WebCam                       | 1         | 0.65%   |
| Sonix USB2.0 FHD UVC WebCam             | 1         | 0.65%   |
| Silicon Motion WebCam SC-13HDL11431N    | 1         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 0.65%   |
| Realtek USB Camera                      | 1         | 0.65%   |
| Realtek TV Camera                       | 1         | 0.65%   |
| Realtek Lenovo EasyCamera               | 1         | 0.65%   |
| Realtek Integrated Webcam               | 1         | 0.65%   |
| Realtek HD WebCam                       | 1         | 0.65%   |
| Realtek EasyCamera                      | 1         | 0.65%   |
| Quanta HP True Vision HD Camera         | 1         | 0.65%   |
| OPPO Oppo N1                            | 1         | 0.65%   |
| Microsoft LifeCam HD-3000               | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 38.46%  |
| Validity Sensors           | 13        | 33.33%  |
| Shenzhen Goodix Technology | 9         | 23.08%  |
| Gingytech                  | 1         | 2.56%   |
| Focal-systems.Corp         | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 6         | 15.38%  |
| Shenzhen Goodix Fingerprint Reader                       | 6         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                      | 3         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 5.13%   |
| Validity Sensors VFS491                                  | 2         | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 5.13%   |
| Validity Sensors Synaptics WBDI                          | 2         | 5.13%   |
| Synaptics UWP WBDI Device                                | 2         | 5.13%   |
| Synaptics UWP WBDI                                       | 2         | 5.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 5.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor        | 1         | 2.56%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 2.56%   |
| Gingytech Fingerprint sensor                             | 1         | 2.56%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 16        | 61.54%  |
| Broadcom    | 5         | 19.23%  |
| Yubico.com  | 3         | 11.54%  |
| Upek        | 1         | 3.85%   |
| OmniKey     | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 16        | 61.54%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 7.69%   |
| Broadcom 5880                                              | 2         | 7.69%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 3.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.85%   |
| OmniKey CardMan Smart@Link                                 | 1         | 3.85%   |
| Broadcom 58200                                             | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 139       | 56.5%   |
| 1     | 69        | 28.05%  |
| 2     | 34        | 13.82%  |
| 4     | 2         | 0.81%   |
| 3     | 2         | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 25.69%  |
| Multimedia controller    | 30        | 20.83%  |
| Graphics card            | 23        | 15.97%  |
| Chipcard                 | 21        | 14.58%  |
| Net/wireless             | 9         | 6.25%   |
| Camera                   | 6         | 4.17%   |
| Bluetooth                | 5         | 3.47%   |
| Unassigned class         | 3         | 2.08%   |
| Modem                    | 2         | 1.39%   |
| Communication controller | 2         | 1.39%   |
| Card reader              | 2         | 1.39%   |
| Storage/ata              | 1         | 0.69%   |
| Network                  | 1         | 0.69%   |
| Firewire controller      | 1         | 0.69%   |
| Dvb card                 | 1         | 0.69%   |

