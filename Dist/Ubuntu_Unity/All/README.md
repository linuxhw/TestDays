Ubuntu Unity - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu Unity.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Unity/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Unity/Notebook/README.md).

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

Total: 2063

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8db7bbe19c](https://linux-hardware.org/?probe=8db7bbe19c) | Jan 03, 2026 |
| Dell          | Precision M4700             | Notebook    | [963e8404c3](https://linux-hardware.org/?probe=963e8404c3) | Jan 03, 2026 |
| Unknown       | Unknown                     | Soc         | [38287077bb](https://linux-hardware.org/?probe=38287077bb) | Jan 02, 2026 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8e17835232](https://linux-hardware.org/?probe=8e17835232) | Jan 02, 2026 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [00e52ecd2b](https://linux-hardware.org/?probe=00e52ecd2b) | Jan 01, 2026 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [fb8f69a7d9](https://linux-hardware.org/?probe=fb8f69a7d9) | Dec 31, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [16a1c3db74](https://linux-hardware.org/?probe=16a1c3db74) | Dec 30, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [60ce442816](https://linux-hardware.org/?probe=60ce442816) | Dec 29, 2025 |
| Unknown       | Nintendo Switch (OLED mo... | Soc         | [d1c0b50074](https://linux-hardware.org/?probe=d1c0b50074) | Dec 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [05fd374438](https://linux-hardware.org/?probe=05fd374438) | Dec 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [de88fac558](https://linux-hardware.org/?probe=de88fac558) | Dec 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8b6b8ad8ae](https://linux-hardware.org/?probe=8b6b8ad8ae) | Dec 26, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [84b8852842](https://linux-hardware.org/?probe=84b8852842) | Dec 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [19b197f8b5](https://linux-hardware.org/?probe=19b197f8b5) | Dec 24, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8a5187637e](https://linux-hardware.org/?probe=8a5187637e) | Dec 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [c3729a7752](https://linux-hardware.org/?probe=c3729a7752) | Dec 22, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [d4cd56d8dd](https://linux-hardware.org/?probe=d4cd56d8dd) | Dec 21, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [07062bdeec](https://linux-hardware.org/?probe=07062bdeec) | Dec 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a12eadd229](https://linux-hardware.org/?probe=a12eadd229) | Dec 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [5a01757378](https://linux-hardware.org/?probe=5a01757378) | Dec 18, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f680d8c01b](https://linux-hardware.org/?probe=f680d8c01b) | Dec 16, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1675599a28](https://linux-hardware.org/?probe=1675599a28) | Dec 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1cb48ebf1d](https://linux-hardware.org/?probe=1cb48ebf1d) | Dec 14, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [610886c77b](https://linux-hardware.org/?probe=610886c77b) | Dec 13, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4f06c09daa](https://linux-hardware.org/?probe=4f06c09daa) | Dec 12, 2025 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fc2ec893ad](https://linux-hardware.org/?probe=fc2ec893ad) | Dec 12, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [20f7fa4310](https://linux-hardware.org/?probe=20f7fa4310) | Dec 11, 2025 |
| GMKtec        | NucBox K8 Plus              | Desktop     | [cbbb102322](https://linux-hardware.org/?probe=cbbb102322) | Dec 10, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [47853119ab](https://linux-hardware.org/?probe=47853119ab) | Dec 10, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f71fe16c89](https://linux-hardware.org/?probe=f71fe16c89) | Dec 09, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [05f65480c2](https://linux-hardware.org/?probe=05f65480c2) | Dec 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1d481b28ef](https://linux-hardware.org/?probe=1d481b28ef) | Dec 07, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9ae2dfd45f](https://linux-hardware.org/?probe=9ae2dfd45f) | Dec 06, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f3cbe24179](https://linux-hardware.org/?probe=f3cbe24179) | Dec 05, 2025 |
| MSI           | Z170A PC MATE               | Desktop     | [4aa4b7b07e](https://linux-hardware.org/?probe=4aa4b7b07e) | Dec 04, 2025 |
| MSI           | Z170A PC MATE               | Desktop     | [4726fae678](https://linux-hardware.org/?probe=4726fae678) | Dec 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [e52b339314](https://linux-hardware.org/?probe=e52b339314) | Dec 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f82f767998](https://linux-hardware.org/?probe=f82f767998) | Dec 02, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [e412ceb307](https://linux-hardware.org/?probe=e412ceb307) | Dec 02, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [662e13460e](https://linux-hardware.org/?probe=662e13460e) | Dec 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [60acbd72c8](https://linux-hardware.org/?probe=60acbd72c8) | Nov 30, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [45a1b9d54c](https://linux-hardware.org/?probe=45a1b9d54c) | Nov 29, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9656c15786](https://linux-hardware.org/?probe=9656c15786) | Nov 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1100faf505](https://linux-hardware.org/?probe=1100faf505) | Nov 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [b3dfcf130a](https://linux-hardware.org/?probe=b3dfcf130a) | Nov 26, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [7c7c1f28ac](https://linux-hardware.org/?probe=7c7c1f28ac) | Nov 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [cf73e0ea11](https://linux-hardware.org/?probe=cf73e0ea11) | Nov 24, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a6077cf4ba](https://linux-hardware.org/?probe=a6077cf4ba) | Nov 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [cb02687309](https://linux-hardware.org/?probe=cb02687309) | Nov 22, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a92e7a26f6](https://linux-hardware.org/?probe=a92e7a26f6) | Nov 21, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [fa82e320a3](https://linux-hardware.org/?probe=fa82e320a3) | Nov 20, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [48cf67c6fc](https://linux-hardware.org/?probe=48cf67c6fc) | Nov 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [56901e9af9](https://linux-hardware.org/?probe=56901e9af9) | Nov 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8631853d0e](https://linux-hardware.org/?probe=8631853d0e) | Nov 18, 2025 |
| Dell          | Precision M4500             | Notebook    | [8c09335252](https://linux-hardware.org/?probe=8c09335252) | Nov 17, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0260b7556d](https://linux-hardware.org/?probe=0260b7556d) | Nov 17, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4fe5a305f2](https://linux-hardware.org/?probe=4fe5a305f2) | Nov 16, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [56b5319bcd](https://linux-hardware.org/?probe=56b5319bcd) | Nov 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0feac85b0d](https://linux-hardware.org/?probe=0feac85b0d) | Nov 14, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8d48b4e072](https://linux-hardware.org/?probe=8d48b4e072) | Nov 13, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [c364233bba](https://linux-hardware.org/?probe=c364233bba) | Nov 12, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1ba2198211](https://linux-hardware.org/?probe=1ba2198211) | Nov 11, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0a004e58e0](https://linux-hardware.org/?probe=0a004e58e0) | Nov 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0349f223aa](https://linux-hardware.org/?probe=0349f223aa) | Nov 07, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [47dc10e508](https://linux-hardware.org/?probe=47dc10e508) | Nov 06, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [fc06411722](https://linux-hardware.org/?probe=fc06411722) | Nov 05, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9af2c03eb1](https://linux-hardware.org/?probe=9af2c03eb1) | Nov 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9269ff3eec](https://linux-hardware.org/?probe=9269ff3eec) | Nov 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6f4e057e67](https://linux-hardware.org/?probe=6f4e057e67) | Nov 02, 2025 |
| Pegatron      | NARRA5                      | Desktop     | [246eb66bc0](https://linux-hardware.org/?probe=246eb66bc0) | Nov 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [558f83cd7c](https://linux-hardware.org/?probe=558f83cd7c) | Nov 01, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [7045b718ff](https://linux-hardware.org/?probe=7045b718ff) | Oct 31, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [92c6a3ceff](https://linux-hardware.org/?probe=92c6a3ceff) | Oct 30, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [b4b7b9d3c9](https://linux-hardware.org/?probe=b4b7b9d3c9) | Oct 29, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4388bceba7](https://linux-hardware.org/?probe=4388bceba7) | Oct 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [dc08949fc4](https://linux-hardware.org/?probe=dc08949fc4) | Oct 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [687815a9c4](https://linux-hardware.org/?probe=687815a9c4) | Oct 26, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [31b25ec7ac](https://linux-hardware.org/?probe=31b25ec7ac) | Oct 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ee83490d4e](https://linux-hardware.org/?probe=ee83490d4e) | Oct 24, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [06191804d4](https://linux-hardware.org/?probe=06191804d4) | Oct 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [088a558715](https://linux-hardware.org/?probe=088a558715) | Oct 22, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [768f146258](https://linux-hardware.org/?probe=768f146258) | Oct 21, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [a263411979](https://linux-hardware.org/?probe=a263411979) | Oct 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ca298cc92d](https://linux-hardware.org/?probe=ca298cc92d) | Oct 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f593ba6ace](https://linux-hardware.org/?probe=f593ba6ace) | Oct 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [243963f1b2](https://linux-hardware.org/?probe=243963f1b2) | Oct 18, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [07bf1a74ac](https://linux-hardware.org/?probe=07bf1a74ac) | Oct 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a1070fe86e](https://linux-hardware.org/?probe=a1070fe86e) | Oct 16, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [3daa47c557](https://linux-hardware.org/?probe=3daa47c557) | Oct 16, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [96745c0b5d](https://linux-hardware.org/?probe=96745c0b5d) | Oct 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9646634d45](https://linux-hardware.org/?probe=9646634d45) | Oct 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [19158c503e](https://linux-hardware.org/?probe=19158c503e) | Oct 14, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0941871acd](https://linux-hardware.org/?probe=0941871acd) | Oct 13, 2025 |
| HP            | Laptop 17-by0xxx            | Notebook    | [81de05d5d6](https://linux-hardware.org/?probe=81de05d5d6) | Oct 11, 2025 |
| HP            | Laptop 17-by0xxx            | Notebook    | [624f744c8b](https://linux-hardware.org/?probe=624f744c8b) | Oct 11, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [14f787ba25](https://linux-hardware.org/?probe=14f787ba25) | Oct 09, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [7376cded55](https://linux-hardware.org/?probe=7376cded55) | Oct 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9e2c54a20b](https://linux-hardware.org/?probe=9e2c54a20b) | Oct 07, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [95de847470](https://linux-hardware.org/?probe=95de847470) | Oct 06, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [747cca0892](https://linux-hardware.org/?probe=747cca0892) | Oct 05, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [c38172e6e7](https://linux-hardware.org/?probe=c38172e6e7) | Oct 04, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [857b3f2944](https://linux-hardware.org/?probe=857b3f2944) | Oct 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0d868ce511](https://linux-hardware.org/?probe=0d868ce511) | Oct 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [51f1a606c9](https://linux-hardware.org/?probe=51f1a606c9) | Oct 02, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a287364c1e](https://linux-hardware.org/?probe=a287364c1e) | Oct 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8ec2287fe7](https://linux-hardware.org/?probe=8ec2287fe7) | Sep 30, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [89b6e113c9](https://linux-hardware.org/?probe=89b6e113c9) | Sep 29, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1e9157f5ba](https://linux-hardware.org/?probe=1e9157f5ba) | Sep 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [b93e379428](https://linux-hardware.org/?probe=b93e379428) | Sep 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [2034e5f751](https://linux-hardware.org/?probe=2034e5f751) | Sep 26, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [864de59e7f](https://linux-hardware.org/?probe=864de59e7f) | Sep 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8333a9000c](https://linux-hardware.org/?probe=8333a9000c) | Sep 24, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f81760d2f2](https://linux-hardware.org/?probe=f81760d2f2) | Sep 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [46f292121f](https://linux-hardware.org/?probe=46f292121f) | Sep 22, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [462191b984](https://linux-hardware.org/?probe=462191b984) | Sep 21, 2025 |
| ASUSTek       | PRIME B650M-A AX6           | Desktop     | [6cad9525eb](https://linux-hardware.org/?probe=6cad9525eb) | Sep 20, 2025 |
| ASUSTek       | PRIME B650M-A AX6           | Desktop     | [c4d6e724c6](https://linux-hardware.org/?probe=c4d6e724c6) | Sep 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [c04350d7f3](https://linux-hardware.org/?probe=c04350d7f3) | Sep 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [683beb0342](https://linux-hardware.org/?probe=683beb0342) | Sep 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f0cdd3dee8](https://linux-hardware.org/?probe=f0cdd3dee8) | Sep 18, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6f79d7d98a](https://linux-hardware.org/?probe=6f79d7d98a) | Sep 17, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [17431249e8](https://linux-hardware.org/?probe=17431249e8) | Sep 16, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [184466a374](https://linux-hardware.org/?probe=184466a374) | Sep 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6f55339d6e](https://linux-hardware.org/?probe=6f55339d6e) | Sep 14, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [5ff4d6a82e](https://linux-hardware.org/?probe=5ff4d6a82e) | Sep 13, 2025 |
| ASRock        | N68-VS3 FX                  | Desktop     | [d46490c00f](https://linux-hardware.org/?probe=d46490c00f) | Sep 12, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6a0b49bd43](https://linux-hardware.org/?probe=6a0b49bd43) | Sep 12, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [911b1f1496](https://linux-hardware.org/?probe=911b1f1496) | Sep 11, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [655d5c3b14](https://linux-hardware.org/?probe=655d5c3b14) | Sep 10, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ad0f2b463c](https://linux-hardware.org/?probe=ad0f2b463c) | Sep 09, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [9141658497](https://linux-hardware.org/?probe=9141658497) | Sep 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [fb42450649](https://linux-hardware.org/?probe=fb42450649) | Sep 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [d1a27392fc](https://linux-hardware.org/?probe=d1a27392fc) | Sep 07, 2025 |
| HP            | Notebook                    | Notebook    | [d2361c3b3a](https://linux-hardware.org/?probe=d2361c3b3a) | Sep 06, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [079f4a8e59](https://linux-hardware.org/?probe=079f4a8e59) | Sep 06, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [95b65524c3](https://linux-hardware.org/?probe=95b65524c3) | Sep 05, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [128133cfe2](https://linux-hardware.org/?probe=128133cfe2) | Sep 05, 2025 |
| Dell          | Latitude 3420               | Notebook    | [ed7d979154](https://linux-hardware.org/?probe=ed7d979154) | Sep 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [3d8758e12a](https://linux-hardware.org/?probe=3d8758e12a) | Sep 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [cf5dca2f5c](https://linux-hardware.org/?probe=cf5dca2f5c) | Sep 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [7b4cfa7cb5](https://linux-hardware.org/?probe=7b4cfa7cb5) | Sep 02, 2025 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e741cb158](https://linux-hardware.org/?probe=8e741cb158) | Sep 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [03c1a47435](https://linux-hardware.org/?probe=03c1a47435) | Sep 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [327f135880](https://linux-hardware.org/?probe=327f135880) | Aug 31, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ba793d8337](https://linux-hardware.org/?probe=ba793d8337) | Aug 30, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [b3bb317a29](https://linux-hardware.org/?probe=b3bb317a29) | Aug 29, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [6ab2bfbd73](https://linux-hardware.org/?probe=6ab2bfbd73) | Aug 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6b4697fdbe](https://linux-hardware.org/?probe=6b4697fdbe) | Aug 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [3ab51e67a2](https://linux-hardware.org/?probe=3ab51e67a2) | Aug 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [728ebda7b9](https://linux-hardware.org/?probe=728ebda7b9) | Aug 26, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [44f0f7103f](https://linux-hardware.org/?probe=44f0f7103f) | Aug 24, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [5b3f0395ab](https://linux-hardware.org/?probe=5b3f0395ab) | Aug 23, 2025 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [04dd4f08e2](https://linux-hardware.org/?probe=04dd4f08e2) | Aug 22, 2025 |
| ECS           | G31T-M                      | Desktop     | [5bc8907435](https://linux-hardware.org/?probe=5bc8907435) | Aug 20, 2025 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2e70d545df](https://linux-hardware.org/?probe=2e70d545df) | Aug 17, 2025 |
| Lenovo        | ThinkPad T510 43843AU       | Notebook    | [14886f99a0](https://linux-hardware.org/?probe=14886f99a0) | Aug 17, 2025 |
| Lenovo        | ThinkPad T510 43843AU       | Notebook    | [108a25fdf3](https://linux-hardware.org/?probe=108a25fdf3) | Aug 17, 2025 |
| Dell          | Latitude 7370               | Notebook    | [f38c269e7c](https://linux-hardware.org/?probe=f38c269e7c) | Aug 14, 2025 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [d0229eef6d](https://linux-hardware.org/?probe=d0229eef6d) | Aug 12, 2025 |
| Supermicro    | H12SSL-CT                   | Server      | [921c3d673b](https://linux-hardware.org/?probe=921c3d673b) | Aug 12, 2025 |
| Apple         | Mac-F2268DAE                | All in one  | [2c7442130b](https://linux-hardware.org/?probe=2c7442130b) | Aug 08, 2025 |
| Apple         | Mac-F2268DAE                | All in one  | [62b8bc6b83](https://linux-hardware.org/?probe=62b8bc6b83) | Aug 07, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [d362cd0402](https://linux-hardware.org/?probe=d362cd0402) | Jul 29, 2025 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [49d7085340](https://linux-hardware.org/?probe=49d7085340) | Jul 23, 2025 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [7ff4e62170](https://linux-hardware.org/?probe=7ff4e62170) | Jul 22, 2025 |
| MSI           | MS-7369                     | Desktop     | [101559a840](https://linux-hardware.org/?probe=101559a840) | Jul 21, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [59f4cef8ba](https://linux-hardware.org/?probe=59f4cef8ba) | Jul 09, 2025 |
| Lenovo        | ThinkBook 16 G7 ARP 21MW    | Notebook    | [349944704f](https://linux-hardware.org/?probe=349944704f) | Jun 29, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [f0b2c77a35](https://linux-hardware.org/?probe=f0b2c77a35) | Jun 25, 2025 |
| Dell          | Precision 5520              | Notebook    | [88a161aab3](https://linux-hardware.org/?probe=88a161aab3) | Jun 17, 2025 |
| Dell          | Precision 5520              | Notebook    | [f3c8ba5c73](https://linux-hardware.org/?probe=f3c8ba5c73) | Jun 17, 2025 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [2ea90a57f1](https://linux-hardware.org/?probe=2ea90a57f1) | Jun 12, 2025 |
| Lenovo        | ThinkPad X270 20HMS5R700    | Notebook    | [1ff561893e](https://linux-hardware.org/?probe=1ff561893e) | Jun 04, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [fa10c1d61c](https://linux-hardware.org/?probe=fa10c1d61c) | Jun 03, 2025 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [56c393629e](https://linux-hardware.org/?probe=56c393629e) | Jun 02, 2025 |
| Acer          | Nitro AN515-54              | Notebook    | [f788e286da](https://linux-hardware.org/?probe=f788e286da) | May 27, 2025 |
| Lenovo        | G500 20236                  | Notebook    | [89ce8aaf13](https://linux-hardware.org/?probe=89ce8aaf13) | May 26, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [3913ae0bd9](https://linux-hardware.org/?probe=3913ae0bd9) | May 26, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [eca25c9886](https://linux-hardware.org/?probe=eca25c9886) | May 25, 2025 |
| HP            | Pavilion dv7                | Notebook    | [b64090360d](https://linux-hardware.org/?probe=b64090360d) | May 20, 2025 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [dc365c9643](https://linux-hardware.org/?probe=dc365c9643) | May 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [92f861be38](https://linux-hardware.org/?probe=92f861be38) | May 18, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [587b287c4c](https://linux-hardware.org/?probe=587b287c4c) | May 14, 2025 |
| ASRock        | H370M-HDV                   | Desktop     | [fd61ae16a6](https://linux-hardware.org/?probe=fd61ae16a6) | May 13, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [3a17b706e3](https://linux-hardware.org/?probe=3a17b706e3) | May 13, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ed44e7702e](https://linux-hardware.org/?probe=ed44e7702e) | May 12, 2025 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [0ac0e459a0](https://linux-hardware.org/?probe=0ac0e459a0) | May 11, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [92ddeacb9a](https://linux-hardware.org/?probe=92ddeacb9a) | May 11, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [b30bc4c5e8](https://linux-hardware.org/?probe=b30bc4c5e8) | May 10, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ea26cfe4e1](https://linux-hardware.org/?probe=ea26cfe4e1) | May 09, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ebafed0b40](https://linux-hardware.org/?probe=ebafed0b40) | May 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9c27fdbf4e](https://linux-hardware.org/?probe=9c27fdbf4e) | May 07, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0f85985c0c](https://linux-hardware.org/?probe=0f85985c0c) | May 06, 2025 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [214bd41aa0](https://linux-hardware.org/?probe=214bd41aa0) | May 05, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [43a9256485](https://linux-hardware.org/?probe=43a9256485) | May 05, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [b76630f131](https://linux-hardware.org/?probe=b76630f131) | May 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [b40b2f175f](https://linux-hardware.org/?probe=b40b2f175f) | May 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [703a1cbe77](https://linux-hardware.org/?probe=703a1cbe77) | May 03, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [6c13776b08](https://linux-hardware.org/?probe=6c13776b08) | May 02, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [2bbd2bbbf4](https://linux-hardware.org/?probe=2bbd2bbbf4) | May 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [797a5e6b54](https://linux-hardware.org/?probe=797a5e6b54) | May 01, 2025 |
| Unknown       | Unknown                     | Soc         | [5c2a36d024](https://linux-hardware.org/?probe=5c2a36d024) | May 01, 2025 |
| Unknown       | Unknown                     | Soc         | [7a766a66c0](https://linux-hardware.org/?probe=7a766a66c0) | May 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [99e76ebc3d](https://linux-hardware.org/?probe=99e76ebc3d) | Apr 30, 2025 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [3f5c176ce9](https://linux-hardware.org/?probe=3f5c176ce9) | Apr 29, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [47e16968cd](https://linux-hardware.org/?probe=47e16968cd) | Apr 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6a98d85ad0](https://linux-hardware.org/?probe=6a98d85ad0) | Apr 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [392f7692da](https://linux-hardware.org/?probe=392f7692da) | Apr 26, 2025 |
| HP            | 845A                        | Desktop     | [7109fb621d](https://linux-hardware.org/?probe=7109fb621d) | Apr 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f2a9377b80](https://linux-hardware.org/?probe=f2a9377b80) | Apr 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0af0914a21](https://linux-hardware.org/?probe=0af0914a21) | Apr 24, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [23722dd24b](https://linux-hardware.org/?probe=23722dd24b) | Apr 23, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f0ddec3abe](https://linux-hardware.org/?probe=f0ddec3abe) | Apr 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6aebedf546](https://linux-hardware.org/?probe=6aebedf546) | Apr 23, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [711293474d](https://linux-hardware.org/?probe=711293474d) | Apr 22, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1842c57731](https://linux-hardware.org/?probe=1842c57731) | Apr 22, 2025 |
| Dell          | XPS 9320                    | Notebook    | [62b7994ce5](https://linux-hardware.org/?probe=62b7994ce5) | Apr 21, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [79c01f91f7](https://linux-hardware.org/?probe=79c01f91f7) | Apr 21, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9cf937aa36](https://linux-hardware.org/?probe=9cf937aa36) | Apr 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4ae89da943](https://linux-hardware.org/?probe=4ae89da943) | Apr 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [fe8aee8449](https://linux-hardware.org/?probe=fe8aee8449) | Apr 18, 2025 |
| Dell          | 06JWJY A00                  | Desktop     | [78173cc97a](https://linux-hardware.org/?probe=78173cc97a) | Apr 17, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6eb2ca1a07](https://linux-hardware.org/?probe=6eb2ca1a07) | Apr 17, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [93f8d3e773](https://linux-hardware.org/?probe=93f8d3e773) | Apr 16, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB2A... | Mini pc     | [779d9f5c20](https://linux-hardware.org/?probe=779d9f5c20) | Apr 15, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB2A... | Mini pc     | [d6ecaffa85](https://linux-hardware.org/?probe=d6ecaffa85) | Apr 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f8f0483242](https://linux-hardware.org/?probe=f8f0483242) | Apr 15, 2025 |
| Dell          | XPS 13 7390                 | Notebook    | [ab5c9ae5fc](https://linux-hardware.org/?probe=ab5c9ae5fc) | Apr 13, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [471ad6ee03](https://linux-hardware.org/?probe=471ad6ee03) | Apr 13, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [05d526a7a1](https://linux-hardware.org/?probe=05d526a7a1) | Apr 12, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [cfcd205589](https://linux-hardware.org/?probe=cfcd205589) | Apr 11, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a4eafcc2d7](https://linux-hardware.org/?probe=a4eafcc2d7) | Apr 10, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [e75de7db9a](https://linux-hardware.org/?probe=e75de7db9a) | Apr 09, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [ea1c10539a](https://linux-hardware.org/?probe=ea1c10539a) | Apr 08, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [44333f941e](https://linux-hardware.org/?probe=44333f941e) | Apr 07, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [f469cb2ff2](https://linux-hardware.org/?probe=f469cb2ff2) | Apr 06, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [891bbfd15c](https://linux-hardware.org/?probe=891bbfd15c) | Apr 05, 2025 |
| ASUSTek       | UX410UAK                    | Notebook    | [645f19a833](https://linux-hardware.org/?probe=645f19a833) | Apr 04, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [7b6d195b91](https://linux-hardware.org/?probe=7b6d195b91) | Apr 04, 2025 |
| HP            | ProBook 650 G1              | Notebook    | [2767984234](https://linux-hardware.org/?probe=2767984234) | Apr 04, 2025 |
| HP            | ProBook 650 G5              | Notebook    | [fe70b77b38](https://linux-hardware.org/?probe=fe70b77b38) | Apr 03, 2025 |
| ASRock        | H97 Pro4                    | Desktop     | [8e2c2d4487](https://linux-hardware.org/?probe=8e2c2d4487) | Apr 03, 2025 |
| ASRock        | H97 Pro4                    | Desktop     | [00be998d07](https://linux-hardware.org/?probe=00be998d07) | Apr 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8dbb077608](https://linux-hardware.org/?probe=8dbb077608) | Apr 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [86ce6761e4](https://linux-hardware.org/?probe=86ce6761e4) | Apr 02, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [bdaac84721](https://linux-hardware.org/?probe=bdaac84721) | Apr 01, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a111886695](https://linux-hardware.org/?probe=a111886695) | Mar 31, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [bae8ddb959](https://linux-hardware.org/?probe=bae8ddb959) | Mar 30, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [52b72a4b8b](https://linux-hardware.org/?probe=52b72a4b8b) | Mar 29, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [7d200f0399](https://linux-hardware.org/?probe=7d200f0399) | Mar 28, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [1ec80005e0](https://linux-hardware.org/?probe=1ec80005e0) | Mar 27, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [c450fcba9f](https://linux-hardware.org/?probe=c450fcba9f) | Mar 26, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6cce0855fd](https://linux-hardware.org/?probe=6cce0855fd) | Mar 25, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [01c303e7c3](https://linux-hardware.org/?probe=01c303e7c3) | Mar 24, 2025 |
| ASRock        | H97 Pro4                    | Desktop     | [dde1635830](https://linux-hardware.org/?probe=dde1635830) | Mar 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6c80164d71](https://linux-hardware.org/?probe=6c80164d71) | Mar 23, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [17aac91b6c](https://linux-hardware.org/?probe=17aac91b6c) | Mar 22, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [a6ac70c6da](https://linux-hardware.org/?probe=a6ac70c6da) | Mar 21, 2025 |
| Unknown       | Unknown                     | Soc         | [67b64dc858](https://linux-hardware.org/?probe=67b64dc858) | Mar 21, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [76ac219750](https://linux-hardware.org/?probe=76ac219750) | Mar 20, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [060010e87d](https://linux-hardware.org/?probe=060010e87d) | Mar 19, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4362e8cdcc](https://linux-hardware.org/?probe=4362e8cdcc) | Mar 18, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [c820014f72](https://linux-hardware.org/?probe=c820014f72) | Mar 17, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [442d26b451](https://linux-hardware.org/?probe=442d26b451) | Mar 16, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [19f38ef8cc](https://linux-hardware.org/?probe=19f38ef8cc) | Mar 15, 2025 |
| Fujitsu Si... | D2817-A1 S26361-D2817-A1    | Desktop     | [ab87296ce8](https://linux-hardware.org/?probe=ab87296ce8) | Mar 15, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0105f61e9a](https://linux-hardware.org/?probe=0105f61e9a) | Mar 14, 2025 |
| Acer          | Aspire A315-24PT            | Notebook    | [6fbaa9e71d](https://linux-hardware.org/?probe=6fbaa9e71d) | Mar 13, 2025 |
| Supermicro    | X10DRL-i                    | Server      | [66b760be81](https://linux-hardware.org/?probe=66b760be81) | Mar 11, 2025 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [d2b59dda09](https://linux-hardware.org/?probe=d2b59dda09) | Mar 04, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [2649076864](https://linux-hardware.org/?probe=2649076864) | Mar 04, 2025 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4b78f70cf0](https://linux-hardware.org/?probe=4b78f70cf0) | Feb 26, 2025 |
| MSI           | Prestige 14 A10SC           | Notebook    | [a636b70a78](https://linux-hardware.org/?probe=a636b70a78) | Feb 10, 2025 |
| Lenovo        | B320-14IKB 81CC             | Notebook    | [efbf3d5892](https://linux-hardware.org/?probe=efbf3d5892) | Feb 06, 2025 |
| Lenovo        | ThinkPad T420 4236BH8       | Notebook    | [43c645f6d1](https://linux-hardware.org/?probe=43c645f6d1) | Feb 03, 2025 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [e522044a66](https://linux-hardware.org/?probe=e522044a66) | Jan 30, 2025 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [92d3e8dea0](https://linux-hardware.org/?probe=92d3e8dea0) | Jan 27, 2025 |
| Lenovo        | ThinkPad E590 20NB002BRT    | Notebook    | [58e63ffb90](https://linux-hardware.org/?probe=58e63ffb90) | Jan 14, 2025 |
| Dell          | Precision 3561              | Notebook    | [bb7b6c44bd](https://linux-hardware.org/?probe=bb7b6c44bd) | Jan 07, 2025 |
| HP            | 15                          | Notebook    | [f63355af6a](https://linux-hardware.org/?probe=f63355af6a) | Jan 07, 2025 |
| MSI           | 990XA-GD55                  | Desktop     | [5d282c8edc](https://linux-hardware.org/?probe=5d282c8edc) | Jan 04, 2025 |
| ASUSTek       | PTGD2-VX                    | Desktop     | [0f9603dd40](https://linux-hardware.org/?probe=0f9603dd40) | Jan 03, 2025 |
| ASUSTek       | PTGD2-VX                    | Desktop     | [c0ced145df](https://linux-hardware.org/?probe=c0ced145df) | Jan 03, 2025 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [fa4538a983](https://linux-hardware.org/?probe=fa4538a983) | Dec 29, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a9a7e396c0](https://linux-hardware.org/?probe=a9a7e396c0) | Dec 26, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [a2f67a9324](https://linux-hardware.org/?probe=a2f67a9324) | Dec 25, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [a81e88cd1b](https://linux-hardware.org/?probe=a81e88cd1b) | Dec 25, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [7f63df74a6](https://linux-hardware.org/?probe=7f63df74a6) | Dec 24, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [bb120a943a](https://linux-hardware.org/?probe=bb120a943a) | Dec 21, 2024 |
| Lenovo        | ThinkPad X250 20CLS64200    | Notebook    | [d92935db90](https://linux-hardware.org/?probe=d92935db90) | Dec 17, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [a8cc0ecb2b](https://linux-hardware.org/?probe=a8cc0ecb2b) | Dec 16, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [8d51a6d1e3](https://linux-hardware.org/?probe=8d51a6d1e3) | Dec 07, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [bc6e165df6](https://linux-hardware.org/?probe=bc6e165df6) | Dec 06, 2024 |
| HP            | Compaq Mini 311-1000        | Notebook    | [da25f2f11a](https://linux-hardware.org/?probe=da25f2f11a) | Dec 01, 2024 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [8c2c6856ce](https://linux-hardware.org/?probe=8c2c6856ce) | Nov 29, 2024 |
| Acer          | Veriton M275                | Desktop     | [53a3e7c867](https://linux-hardware.org/?probe=53a3e7c867) | Nov 24, 2024 |
| Dell          | Vostro 3578                 | Notebook    | [2490918f08](https://linux-hardware.org/?probe=2490918f08) | Nov 24, 2024 |
| Dell          | Latitude 7300               | Notebook    | [6371109a3f](https://linux-hardware.org/?probe=6371109a3f) | Nov 23, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [9879b0bbdb](https://linux-hardware.org/?probe=9879b0bbdb) | Nov 21, 2024 |
| ASUSTek       | 1005HA                      | Notebook    | [39603774e5](https://linux-hardware.org/?probe=39603774e5) | Nov 20, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [27cfaae835](https://linux-hardware.org/?probe=27cfaae835) | Nov 20, 2024 |
| Dell          | Latitude D630               | Notebook    | [0b5738d0df](https://linux-hardware.org/?probe=0b5738d0df) | Nov 13, 2024 |
| Toshiba       | Satellite L745              | Notebook    | [143975f623](https://linux-hardware.org/?probe=143975f623) | Nov 09, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6eaa536f2d](https://linux-hardware.org/?probe=6eaa536f2d) | Nov 08, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [ef5c1d5086](https://linux-hardware.org/?probe=ef5c1d5086) | Nov 06, 2024 |
| Toshiba       | Satellite C850-1G2          | Notebook    | [1a8e3e84b5](https://linux-hardware.org/?probe=1a8e3e84b5) | Nov 04, 2024 |
| Acer          | Extensa 7630EZ              | Notebook    | [5c48b2f063](https://linux-hardware.org/?probe=5c48b2f063) | Nov 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [5e2c531d43](https://linux-hardware.org/?probe=5e2c531d43) | Oct 28, 2024 |
| Acer          | Predator G5900              | Desktop     | [972eedb81e](https://linux-hardware.org/?probe=972eedb81e) | Oct 28, 2024 |
| Acer          | Extensa 7630EZ              | Notebook    | [65c6658e55](https://linux-hardware.org/?probe=65c6658e55) | Oct 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [98d6d0497e](https://linux-hardware.org/?probe=98d6d0497e) | Oct 24, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [b18bcaafa6](https://linux-hardware.org/?probe=b18bcaafa6) | Oct 23, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [f371a56300](https://linux-hardware.org/?probe=f371a56300) | Oct 14, 2024 |
| Supermicro    | X10DRG-OT+-CPU              | Desktop     | [d3df4c7b34](https://linux-hardware.org/?probe=d3df4c7b34) | Oct 14, 2024 |
| ASRock        | H97 Pro4                    | Desktop     | [0e47df0629](https://linux-hardware.org/?probe=0e47df0629) | Oct 13, 2024 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [d60c92d4fc](https://linux-hardware.org/?probe=d60c92d4fc) | Oct 12, 2024 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [75f40c3c5e](https://linux-hardware.org/?probe=75f40c3c5e) | Oct 12, 2024 |
| ASRock        | H97 Pro4                    | Desktop     | [92980dc6ab](https://linux-hardware.org/?probe=92980dc6ab) | Oct 12, 2024 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [048e1b5215](https://linux-hardware.org/?probe=048e1b5215) | Oct 12, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [b7320420c9](https://linux-hardware.org/?probe=b7320420c9) | Oct 12, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [e4ae88eaec](https://linux-hardware.org/?probe=e4ae88eaec) | Oct 03, 2024 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [8b11d57024](https://linux-hardware.org/?probe=8b11d57024) | Oct 02, 2024 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [984fd05d9c](https://linux-hardware.org/?probe=984fd05d9c) | Oct 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP36... | Convertible | [21f5f58e09](https://linux-hardware.org/?probe=21f5f58e09) | Oct 01, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [86a9c5b481](https://linux-hardware.org/?probe=86a9c5b481) | Sep 30, 2024 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [3ae4c69593](https://linux-hardware.org/?probe=3ae4c69593) | Sep 30, 2024 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e03382a8f7](https://linux-hardware.org/?probe=e03382a8f7) | Sep 26, 2024 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1d86f2a6ce](https://linux-hardware.org/?probe=1d86f2a6ce) | Sep 26, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [db77b134d1](https://linux-hardware.org/?probe=db77b134d1) | Sep 24, 2024 |
| Toshiba       | STI NI 1401                 | Notebook    | [3abf4867f1](https://linux-hardware.org/?probe=3abf4867f1) | Sep 22, 2024 |
| MSI           | H81M-E33                    | Desktop     | [f78dc83941](https://linux-hardware.org/?probe=f78dc83941) | Sep 21, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [6866916a20](https://linux-hardware.org/?probe=6866916a20) | Sep 21, 2024 |
| Intel         | DQ45CB AAE30148-206         | Desktop     | [85d296ee6a](https://linux-hardware.org/?probe=85d296ee6a) | Sep 20, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [3b471e0e73](https://linux-hardware.org/?probe=3b471e0e73) | Sep 15, 2024 |
| MSI           | A68HM-E33                   | Desktop     | [2baf2fb3cc](https://linux-hardware.org/?probe=2baf2fb3cc) | Sep 12, 2024 |
| Unknown       | adnasc01                    | Desktop     | [08e7fa1645](https://linux-hardware.org/?probe=08e7fa1645) | Sep 10, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [35da799420](https://linux-hardware.org/?probe=35da799420) | Sep 08, 2024 |
| Lenovo        | ThinkPad X131e 33681Q1      | Notebook    | [f3e3569ea0](https://linux-hardware.org/?probe=f3e3569ea0) | Sep 03, 2024 |
| Toshiba       | STI NI 1401                 | Notebook    | [43c42c00f4](https://linux-hardware.org/?probe=43c42c00f4) | Aug 30, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [7d0a8023b8](https://linux-hardware.org/?probe=7d0a8023b8) | Aug 30, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fa813d195b](https://linux-hardware.org/?probe=fa813d195b) | Aug 28, 2024 |
| Dell          | Latitude 5421               | Notebook    | [f1bb1223a1](https://linux-hardware.org/?probe=f1bb1223a1) | Aug 23, 2024 |
| Intel         | H510                        | Desktop     | [f19b399ce4](https://linux-hardware.org/?probe=f19b399ce4) | Aug 08, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [04284ff64d](https://linux-hardware.org/?probe=04284ff64d) | Aug 05, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [0eb684ba65](https://linux-hardware.org/?probe=0eb684ba65) | Jul 30, 2024 |
| ASUSTek       | A7N8X-E                     | Desktop     | [1ccdb4c80f](https://linux-hardware.org/?probe=1ccdb4c80f) | Jul 20, 2024 |
| Dell          | Inspiron 14 7430 2-in-1     | Convertible | [500b1e2e5d](https://linux-hardware.org/?probe=500b1e2e5d) | Jul 20, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [62354fe581](https://linux-hardware.org/?probe=62354fe581) | Jul 19, 2024 |
| ASUSTek       | A7N8X-E                     | Desktop     | [70f27bc56a](https://linux-hardware.org/?probe=70f27bc56a) | Jul 15, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [7989202548](https://linux-hardware.org/?probe=7989202548) | Jul 11, 2024 |
| Dell          | Precision 7540              | Notebook    | [54c96aa3f5](https://linux-hardware.org/?probe=54c96aa3f5) | Jul 08, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [fa8f1445c6](https://linux-hardware.org/?probe=fa8f1445c6) | Jul 07, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [de9d781d51](https://linux-hardware.org/?probe=de9d781d51) | Jul 06, 2024 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [f3ddefaa28](https://linux-hardware.org/?probe=f3ddefaa28) | Jul 04, 2024 |
| Pegatron      | 2AD5                        | Desktop     | [aa9dbd9aef](https://linux-hardware.org/?probe=aa9dbd9aef) | Jun 24, 2024 |
| ASUSTek       | A7N8X-E                     | Desktop     | [94e76f5f06](https://linux-hardware.org/?probe=94e76f5f06) | Jun 18, 2024 |
| HP            | G61                         | Notebook    | [e091151b6e](https://linux-hardware.org/?probe=e091151b6e) | Jun 13, 2024 |
| Dell          | Inspiron MM061              | Notebook    | [b154563b73](https://linux-hardware.org/?probe=b154563b73) | Jun 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [be344b10dc](https://linux-hardware.org/?probe=be344b10dc) | Jun 05, 2024 |
| Lenovo        | ThinkPad R60 9459WJF        | Notebook    | [075b8e4949](https://linux-hardware.org/?probe=075b8e4949) | May 30, 2024 |
| Nvidia        | Tegra                       | Soc         | [6cf4a3e280](https://linux-hardware.org/?probe=6cf4a3e280) | May 30, 2024 |
| Lenovo        | ThinkPad T500 20827MG       | Notebook    | [812523cb5e](https://linux-hardware.org/?probe=812523cb5e) | May 29, 2024 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [073a03beaa](https://linux-hardware.org/?probe=073a03beaa) | May 23, 2024 |
| Notebook      | W94_W95BU                   | Notebook    | [d252bada3c](https://linux-hardware.org/?probe=d252bada3c) | May 23, 2024 |
| Matsushita... | CF-19HH205NW                | Notebook    | [3671ae4823](https://linux-hardware.org/?probe=3671ae4823) | May 20, 2024 |
| ASUSTek       | PN51-E1                     | Mini pc     | [6022887806](https://linux-hardware.org/?probe=6022887806) | May 12, 2024 |
| ECS           | MCP61M-M3                   | Desktop     | [444cf4c365](https://linux-hardware.org/?probe=444cf4c365) | May 10, 2024 |
| ECS           | MCP61M-M3                   | Desktop     | [890042b3bc](https://linux-hardware.org/?probe=890042b3bc) | May 09, 2024 |
| ECS           | MCP61M-M3                   | Desktop     | [4a66244a0d](https://linux-hardware.org/?probe=4a66244a0d) | May 08, 2024 |
| Dell          | Inspiron N7010              | Notebook    | [538f6e2c91](https://linux-hardware.org/?probe=538f6e2c91) | May 06, 2024 |
| Dell          | Precision 5530              | Notebook    | [373556c210](https://linux-hardware.org/?probe=373556c210) | May 02, 2024 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [e442e79602](https://linux-hardware.org/?probe=e442e79602) | Apr 30, 2024 |
| ASUSTek       | ET2031I                     | Notebook    | [d27647c450](https://linux-hardware.org/?probe=d27647c450) | Apr 29, 2024 |
| HP            | ProBook 4510s               | Notebook    | [8de734fc37](https://linux-hardware.org/?probe=8de734fc37) | Apr 28, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [ef90289a1a](https://linux-hardware.org/?probe=ef90289a1a) | Apr 17, 2024 |
| Gigabyte      | AORUS 16X ASG               | Notebook    | [58a22b5fcc](https://linux-hardware.org/?probe=58a22b5fcc) | Apr 16, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [a00d0bb1b4](https://linux-hardware.org/?probe=a00d0bb1b4) | Apr 16, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [2cf9b070a4](https://linux-hardware.org/?probe=2cf9b070a4) | Apr 15, 2024 |
| Unknown       | Unknown                     | Soc         | [127faa9050](https://linux-hardware.org/?probe=127faa9050) | Apr 02, 2024 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [25d9669839](https://linux-hardware.org/?probe=25d9669839) | Mar 25, 2024 |
| Medion        | WIM2170                     | Notebook    | [190b555e0c](https://linux-hardware.org/?probe=190b555e0c) | Mar 23, 2024 |
| Dell          | 0PRR48 A01                  | Desktop     | [7c69b5e082](https://linux-hardware.org/?probe=7c69b5e082) | Mar 20, 2024 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [597b022119](https://linux-hardware.org/?probe=597b022119) | Feb 29, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d17f61dd3a](https://linux-hardware.org/?probe=d17f61dd3a) | Feb 24, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e990417791](https://linux-hardware.org/?probe=e990417791) | Feb 24, 2024 |
| Intel         | H61                         | Desktop     | [fc2cf214b0](https://linux-hardware.org/?probe=fc2cf214b0) | Feb 20, 2024 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [c2f80860e5](https://linux-hardware.org/?probe=c2f80860e5) | Feb 15, 2024 |
| Lenovo        | ThinkStation D30 4223AU4    | Desktop     | [bd10aa2839](https://linux-hardware.org/?probe=bd10aa2839) | Feb 13, 2024 |
| Exo           | Smart T                     | Notebook    | [6691435d42](https://linux-hardware.org/?probe=6691435d42) | Feb 10, 2024 |
| Samsung       | 730QED                      | Convertible | [eb61c8edf0](https://linux-hardware.org/?probe=eb61c8edf0) | Feb 07, 2024 |
| Positivo      | Q4128C-S                    | Notebook    | [8c01f80e79](https://linux-hardware.org/?probe=8c01f80e79) | Feb 06, 2024 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [78586dd263](https://linux-hardware.org/?probe=78586dd263) | Feb 06, 2024 |
| Dell          | Latitude D620               | Notebook    | [c0f28567a4](https://linux-hardware.org/?probe=c0f28567a4) | Jan 31, 2024 |
| ASRock        | X370 Professional Gaming    | Desktop     | [ddff1295a4](https://linux-hardware.org/?probe=ddff1295a4) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [1adb0efb30](https://linux-hardware.org/?probe=1adb0efb30) | Jan 27, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [040dbb275e](https://linux-hardware.org/?probe=040dbb275e) | Jan 26, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | Desktop     | [e114381673](https://linux-hardware.org/?probe=e114381673) | Jan 25, 2024 |
| HP            | 3048h                       | Desktop     | [ed2d54328f](https://linux-hardware.org/?probe=ed2d54328f) | Jan 25, 2024 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [ed95c81dcc](https://linux-hardware.org/?probe=ed95c81dcc) | Jan 19, 2024 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [911ffd60a5](https://linux-hardware.org/?probe=911ffd60a5) | Jan 04, 2024 |
| Dell          | Latitude 5480               | Notebook    | [cf678e4c6d](https://linux-hardware.org/?probe=cf678e4c6d) | Dec 31, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a1bc8df9e4](https://linux-hardware.org/?probe=a1bc8df9e4) | Dec 30, 2023 |
| Lenovo        | ThinkPad T450 20BUS2VK00    | Notebook    | [15de64acfb](https://linux-hardware.org/?probe=15de64acfb) | Dec 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [b1342e1524](https://linux-hardware.org/?probe=b1342e1524) | Dec 23, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [d67a62b447](https://linux-hardware.org/?probe=d67a62b447) | Dec 21, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [b847e03f71](https://linux-hardware.org/?probe=b847e03f71) | Dec 21, 2023 |
| System76      | Adder WS                    | Notebook    | [d272c23e51](https://linux-hardware.org/?probe=d272c23e51) | Dec 21, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2b49349cf8](https://linux-hardware.org/?probe=2b49349cf8) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [7aa351f4c3](https://linux-hardware.org/?probe=7aa351f4c3) | Dec 19, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [808c135dea](https://linux-hardware.org/?probe=808c135dea) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [9ed9ded2ea](https://linux-hardware.org/?probe=9ed9ded2ea) | Dec 19, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [ef50f10d1f](https://linux-hardware.org/?probe=ef50f10d1f) | Dec 17, 2023 |
| HP            | Pavilion 15                 | Notebook    | [8041cb2da6](https://linux-hardware.org/?probe=8041cb2da6) | Dec 09, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [cad7bc7542](https://linux-hardware.org/?probe=cad7bc7542) | Dec 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [69fcc32b2c](https://linux-hardware.org/?probe=69fcc32b2c) | Dec 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [3919c76efa](https://linux-hardware.org/?probe=3919c76efa) | Dec 04, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [5ab684ace6](https://linux-hardware.org/?probe=5ab684ace6) | Nov 27, 2023 |
| Intel         | NUC6i3SYB H81132-502        | Mini pc     | [0238e68d82](https://linux-hardware.org/?probe=0238e68d82) | Nov 26, 2023 |
| Toshiba       | NB205                       | Notebook    | [a3f0bef4d4](https://linux-hardware.org/?probe=a3f0bef4d4) | Nov 15, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [527e45b73b](https://linux-hardware.org/?probe=527e45b73b) | Nov 15, 2023 |
| HP            | ZHAN 66 Pro G2 Notebook ... | Notebook    | [f93402c5f5](https://linux-hardware.org/?probe=f93402c5f5) | Nov 14, 2023 |
| ECS           | H81H3-M7                    | Desktop     | [d2afbe33c7](https://linux-hardware.org/?probe=d2afbe33c7) | Nov 09, 2023 |
| ECS           | H81H3-M7                    | Desktop     | [e5ea8b4820](https://linux-hardware.org/?probe=e5ea8b4820) | Nov 09, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [a1519ee799](https://linux-hardware.org/?probe=a1519ee799) | Nov 09, 2023 |
| Dell          | Precision 3551              | Notebook    | [da2f2a5993](https://linux-hardware.org/?probe=da2f2a5993) | Nov 08, 2023 |
| ASUSTek       | GL702VMK                    | Notebook    | [4cb218a4f4](https://linux-hardware.org/?probe=4cb218a4f4) | Nov 08, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c2a37daf7d](https://linux-hardware.org/?probe=c2a37daf7d) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [1d56b84bdd](https://linux-hardware.org/?probe=1d56b84bdd) | Nov 05, 2023 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [71fd69724b](https://linux-hardware.org/?probe=71fd69724b) | Nov 03, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [0eba32de41](https://linux-hardware.org/?probe=0eba32de41) | Nov 01, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [bf7045fe69](https://linux-hardware.org/?probe=bf7045fe69) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [4bd69e46d1](https://linux-hardware.org/?probe=4bd69e46d1) | Oct 30, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6232ddb7f2](https://linux-hardware.org/?probe=6232ddb7f2) | Oct 28, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [6e2384b7ee](https://linux-hardware.org/?probe=6e2384b7ee) | Oct 27, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [bea4c3f8b4](https://linux-hardware.org/?probe=bea4c3f8b4) | Oct 26, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [0cbd6a255a](https://linux-hardware.org/?probe=0cbd6a255a) | Oct 25, 2023 |
| Dell          | Inspiron 6000               | Notebook    | [5ba1518578](https://linux-hardware.org/?probe=5ba1518578) | Oct 22, 2023 |
| Unknown       | SpringdalePE                | Desktop     | [e29427ba94](https://linux-hardware.org/?probe=e29427ba94) | Oct 10, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [358f4a0030](https://linux-hardware.org/?probe=358f4a0030) | Oct 08, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [887c13dff8](https://linux-hardware.org/?probe=887c13dff8) | Oct 06, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [5bd11bbd69](https://linux-hardware.org/?probe=5bd11bbd69) | Oct 06, 2023 |
| Notebook      | N150ZU                      | Notebook    | [cbaeef6994](https://linux-hardware.org/?probe=cbaeef6994) | Oct 05, 2023 |
| Notebook      | N150ZU                      | Notebook    | [3a555e095f](https://linux-hardware.org/?probe=3a555e095f) | Oct 05, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [48afb4262c](https://linux-hardware.org/?probe=48afb4262c) | Oct 04, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [eb48f40a27](https://linux-hardware.org/?probe=eb48f40a27) | Sep 29, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [451784974b](https://linux-hardware.org/?probe=451784974b) | Sep 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [11777b411d](https://linux-hardware.org/?probe=11777b411d) | Sep 20, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6861d58ee0](https://linux-hardware.org/?probe=6861d58ee0) | Sep 20, 2023 |
| Lenovo        | ThinkPad T460 20FN002VUS    | Notebook    | [46c6a66e5b](https://linux-hardware.org/?probe=46c6a66e5b) | Sep 19, 2023 |
| Toshiba       | Intel H81/Q87 PCH 32        | All in one  | [43275b430f](https://linux-hardware.org/?probe=43275b430f) | Sep 14, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [8d0117a5f3](https://linux-hardware.org/?probe=8d0117a5f3) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ecc13f9294](https://linux-hardware.org/?probe=ecc13f9294) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e1b135961f](https://linux-hardware.org/?probe=e1b135961f) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [f08f8e5ce8](https://linux-hardware.org/?probe=f08f8e5ce8) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [fd7e472e9b](https://linux-hardware.org/?probe=fd7e472e9b) | Sep 07, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [d630819b59](https://linux-hardware.org/?probe=d630819b59) | Sep 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [6c5351c835](https://linux-hardware.org/?probe=6c5351c835) | Sep 01, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [04492867e2](https://linux-hardware.org/?probe=04492867e2) | Aug 31, 2023 |
| HP            | 8592                        | Desktop     | [667f4402e7](https://linux-hardware.org/?probe=667f4402e7) | Aug 31, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [ca9ccf934d](https://linux-hardware.org/?probe=ca9ccf934d) | Aug 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| Dell          | Inspiron 1200               | Notebook    | [2340dcab47](https://linux-hardware.org/?probe=2340dcab47) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [a3982248d3](https://linux-hardware.org/?probe=a3982248d3) | Aug 13, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [977c66cbc0](https://linux-hardware.org/?probe=977c66cbc0) | Aug 12, 2023 |
| Dell          | Latitude D630               | Notebook    | [a57bb7cde1](https://linux-hardware.org/?probe=a57bb7cde1) | Aug 08, 2023 |
| Acer          | Aspire 1825PTZ              | Notebook    | [553d2539fa](https://linux-hardware.org/?probe=553d2539fa) | Aug 07, 2023 |
| System76      | Thelio Major                | Desktop     | [eeea316849](https://linux-hardware.org/?probe=eeea316849) | Aug 04, 2023 |
| Dell          | G5 5587                     | Notebook    | [320fffbb49](https://linux-hardware.org/?probe=320fffbb49) | Aug 04, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [6ffb3ac7e7](https://linux-hardware.org/?probe=6ffb3ac7e7) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [e6d6527380](https://linux-hardware.org/?probe=e6d6527380) | Aug 01, 2023 |
| Panasonic     | CF-20-1                     | Notebook    | [0b59968d03](https://linux-hardware.org/?probe=0b59968d03) | Jul 29, 2023 |
| OEM           | Unknown                     | Notebook    | [d0d59fb363](https://linux-hardware.org/?probe=d0d59fb363) | Jul 24, 2023 |
| ASUSTek       | A_F_K20BF                   | Desktop     | [f2ae40130e](https://linux-hardware.org/?probe=f2ae40130e) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [f81b2bedb9](https://linux-hardware.org/?probe=f81b2bedb9) | Jul 18, 2023 |
| Dell          | 0C2425 A00                  | Desktop     | [130edcd2b5](https://linux-hardware.org/?probe=130edcd2b5) | Jul 06, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [46ae665800](https://linux-hardware.org/?probe=46ae665800) | Jun 18, 2023 |
| HP            | Pavilion 17                 | Notebook    | [f0e1e5aae8](https://linux-hardware.org/?probe=f0e1e5aae8) | Jun 18, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [8c47ad5e92](https://linux-hardware.org/?probe=8c47ad5e92) | Jun 16, 2023 |
| Dell          | 06NWYK A01                  | Desktop     | [c731dec189](https://linux-hardware.org/?probe=c731dec189) | Jun 14, 2023 |
| DJI           | MANIFOLD 2-C                | Desktop     | [44edfc848e](https://linux-hardware.org/?probe=44edfc848e) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [68af03eefe](https://linux-hardware.org/?probe=68af03eefe) | Jun 10, 2023 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [7411937d5b](https://linux-hardware.org/?probe=7411937d5b) | Jun 09, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [5e1bb16065](https://linux-hardware.org/?probe=5e1bb16065) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [3067e6332a](https://linux-hardware.org/?probe=3067e6332a) | Jun 02, 2023 |
| HP            | 802E                        | Desktop     | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [544fc521be](https://linux-hardware.org/?probe=544fc521be) | May 30, 2023 |
| Nvidia        | Tegra                       | Soc         | [06b49744e2](https://linux-hardware.org/?probe=06b49744e2) | May 28, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [ccc5d73179](https://linux-hardware.org/?probe=ccc5d73179) | May 28, 2023 |
| Intel         | X58M                        | Desktop     | [912addab98](https://linux-hardware.org/?probe=912addab98) | May 27, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [e4669affdb](https://linux-hardware.org/?probe=e4669affdb) | May 24, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [00b64b43b5](https://linux-hardware.org/?probe=00b64b43b5) | May 22, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [ebe8b24fd2](https://linux-hardware.org/?probe=ebe8b24fd2) | May 20, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [bb5b5bd73c](https://linux-hardware.org/?probe=bb5b5bd73c) | May 19, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e77f91338e](https://linux-hardware.org/?probe=e77f91338e) | May 16, 2023 |
| Samsung       | 950XED                      | Notebook    | [8d4e3bcb94](https://linux-hardware.org/?probe=8d4e3bcb94) | May 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Unknown       | AG958                       | Notebook    | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Toshiba       | TECRA A11                   | Notebook    | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Acer          | Aspire 7530G                | Notebook    | [5c19c9f6e4](https://linux-hardware.org/?probe=5c19c9f6e4) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [2016e42226](https://linux-hardware.org/?probe=2016e42226) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [4a6eed684e](https://linux-hardware.org/?probe=4a6eed684e) | Apr 26, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9425800303](https://linux-hardware.org/?probe=9425800303) | Apr 25, 2023 |
| ASUSTek       | X45C                        | Notebook    | [759ed58d76](https://linux-hardware.org/?probe=759ed58d76) | Apr 23, 2023 |
| ELSKY         | M219F-6C                    | Desktop     | [5f41223856](https://linux-hardware.org/?probe=5f41223856) | Apr 21, 2023 |
| ASUSTek       | P4C800-E                    | Desktop     | [4521f2b9b4](https://linux-hardware.org/?probe=4521f2b9b4) | Apr 17, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [9a85729d53](https://linux-hardware.org/?probe=9a85729d53) | Apr 12, 2023 |
| HP            | 3396                        | Desktop     | [25eac72561](https://linux-hardware.org/?probe=25eac72561) | Apr 12, 2023 |
| HP            | 1497                        | Desktop     | [94c6f8a63a](https://linux-hardware.org/?probe=94c6f8a63a) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [85a8b8b452](https://linux-hardware.org/?probe=85a8b8b452) | Mar 26, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| Alienware     | m17 R3                      | Notebook    | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d45d6dce3b](https://linux-hardware.org/?probe=d45d6dce3b) | Mar 15, 2023 |
| Lenovo        | 313A SDK0L77767 WIN 3423... | Desktop     | [869582f7a7](https://linux-hardware.org/?probe=869582f7a7) | Mar 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [daf758d941](https://linux-hardware.org/?probe=daf758d941) | Mar 08, 2023 |
| Dell          | Latitude 7480               | Notebook    | [c4e5e8923c](https://linux-hardware.org/?probe=c4e5e8923c) | Mar 05, 2023 |
| DIEBOLD       | H55H-CM                     | Desktop     | [fadb939dd7](https://linux-hardware.org/?probe=fadb939dd7) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [f9213f29ca](https://linux-hardware.org/?probe=f9213f29ca) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [e1733fa8c9](https://linux-hardware.org/?probe=e1733fa8c9) | Mar 01, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8fb68b4ad6](https://linux-hardware.org/?probe=8fb68b4ad6) | Feb 26, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [d205de771a](https://linux-hardware.org/?probe=d205de771a) | Feb 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [b57e519074](https://linux-hardware.org/?probe=b57e519074) | Feb 25, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [bf3c4ff51d](https://linux-hardware.org/?probe=bf3c4ff51d) | Feb 25, 2023 |
| Nvidia        | Tegra                       | Soc         | [5a0d032110](https://linux-hardware.org/?probe=5a0d032110) | Feb 23, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a28282663a](https://linux-hardware.org/?probe=a28282663a) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [524153d219](https://linux-hardware.org/?probe=524153d219) | Feb 22, 2023 |
| Dell          | Latitude 7330               | Notebook    | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| HP            | 1497                        | Desktop     | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| HP            | Mini 210-1000               | Notebook    | [a97b152ab2](https://linux-hardware.org/?probe=a97b152ab2) | Feb 09, 2023 |
| HP            | Mini 210-1000               | Notebook    | [1546202e50](https://linux-hardware.org/?probe=1546202e50) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [cc92542e21](https://linux-hardware.org/?probe=cc92542e21) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [190d8c3b40](https://linux-hardware.org/?probe=190d8c3b40) | Feb 08, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [04f7bc268b](https://linux-hardware.org/?probe=04f7bc268b) | Feb 07, 2023 |
| ASUSTek       | 1101HA                      | Notebook    | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [213d0d1a6a](https://linux-hardware.org/?probe=213d0d1a6a) | Feb 01, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [d84840d5c9](https://linux-hardware.org/?probe=d84840d5c9) | Jan 29, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [4ffae2148d](https://linux-hardware.org/?probe=4ffae2148d) | Jan 26, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [f75ac14e70](https://linux-hardware.org/?probe=f75ac14e70) | Jan 23, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [7189416b97](https://linux-hardware.org/?probe=7189416b97) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | Notebook    | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c2dd87db86](https://linux-hardware.org/?probe=c2dd87db86) | Jan 17, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [674f3e9cae](https://linux-hardware.org/?probe=674f3e9cae) | Jan 17, 2023 |
| Acer          | Aspire V5-122P              | Notebook    | [c5d70f195f](https://linux-hardware.org/?probe=c5d70f195f) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d89e9dec4](https://linux-hardware.org/?probe=4d89e9dec4) | Jan 14, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [6a129c6fde](https://linux-hardware.org/?probe=6a129c6fde) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [1318c97f67](https://linux-hardware.org/?probe=1318c97f67) | Jan 13, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [79cb54f05f](https://linux-hardware.org/?probe=79cb54f05f) | Jan 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b9eb9f78d2](https://linux-hardware.org/?probe=b9eb9f78d2) | Jan 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [182a43f2b4](https://linux-hardware.org/?probe=182a43f2b4) | Jan 08, 2023 |
| HP            | 3397                        | Desktop     | [ef794d730d](https://linux-hardware.org/?probe=ef794d730d) | Jan 05, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Dell          | 0MTFWP A00                  | Desktop     | [1bec4602bb](https://linux-hardware.org/?probe=1bec4602bb) | Jan 05, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [f9833c6d79](https://linux-hardware.org/?probe=f9833c6d79) | Jan 03, 2023 |
| Dell          | 0P99M4 A01                  | Desktop     | [0b6a911c16](https://linux-hardware.org/?probe=0b6a911c16) | Jan 03, 2023 |
| ASUSTek       | G71GX                       | Notebook    | [7650c66520](https://linux-hardware.org/?probe=7650c66520) | Jan 01, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [def123de2d](https://linux-hardware.org/?probe=def123de2d) | Dec 31, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [33c4b80d0a](https://linux-hardware.org/?probe=33c4b80d0a) | Dec 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [ef194165fc](https://linux-hardware.org/?probe=ef194165fc) | Dec 24, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Acer          | ERC410M                     | Desktop     | [e25233896a](https://linux-hardware.org/?probe=e25233896a) | Dec 21, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [7fe5232b14](https://linux-hardware.org/?probe=7fe5232b14) | Dec 20, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [0f360efa8f](https://linux-hardware.org/?probe=0f360efa8f) | Dec 20, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Irbis         | NB264                       | Notebook    | [4bb5935a41](https://linux-hardware.org/?probe=4bb5935a41) | Dec 19, 2022 |
| Irbis         | NB264                       | Notebook    | [1209e6c899](https://linux-hardware.org/?probe=1209e6c899) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [a5f6a25d72](https://linux-hardware.org/?probe=a5f6a25d72) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [2b955ca3b3](https://linux-hardware.org/?probe=2b955ca3b3) | Dec 19, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| Dell          | 0MTFWP A00                  | Desktop     | [b701f65ffc](https://linux-hardware.org/?probe=b701f65ffc) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [00c328990f](https://linux-hardware.org/?probe=00c328990f) | Dec 16, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [3d5598a5eb](https://linux-hardware.org/?probe=3d5598a5eb) | Dec 16, 2022 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02067db7ad](https://linux-hardware.org/?probe=02067db7ad) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | Notebook    | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Dell          | 0593VH A00                  | Desktop     | [1cbf8ccc4a](https://linux-hardware.org/?probe=1cbf8ccc4a) | Dec 07, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [6c6d0525fc](https://linux-hardware.org/?probe=6c6d0525fc) | Dec 01, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [9f1ad78301](https://linux-hardware.org/?probe=9f1ad78301) | Nov 29, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [4aba048a46](https://linux-hardware.org/?probe=4aba048a46) | Nov 28, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [2042d30c8b](https://linux-hardware.org/?probe=2042d30c8b) | Nov 28, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [f0e76c8866](https://linux-hardware.org/?probe=f0e76c8866) | Nov 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | Notebook    | [37d3dc95f1](https://linux-hardware.org/?probe=37d3dc95f1) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [97ede0876f](https://linux-hardware.org/?probe=97ede0876f) | Nov 25, 2022 |
| Nvidia        | Tegra                       | Soc         | [770c4e4092](https://linux-hardware.org/?probe=770c4e4092) | Nov 21, 2022 |
| Acer          | E946GZ                      | Desktop     | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| HP            | ZBook 14                    | Notebook    | [27b57aad86](https://linux-hardware.org/?probe=27b57aad86) | Nov 12, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [19000343fd](https://linux-hardware.org/?probe=19000343fd) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [f4ef4d30b0](https://linux-hardware.org/?probe=f4ef4d30b0) | Nov 06, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [73ba8f75b7](https://linux-hardware.org/?probe=73ba8f75b7) | Nov 04, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [49e1be474a](https://linux-hardware.org/?probe=49e1be474a) | Nov 01, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [1b93a2f7df](https://linux-hardware.org/?probe=1b93a2f7df) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [9a01d62b1e](https://linux-hardware.org/?probe=9a01d62b1e) | Oct 28, 2022 |
| ASUSTek       | U50Vg                       | Notebook    | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | G60                         | Notebook    | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| Toshiba       | STI 005492G                 | Desktop     | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [64030c9ba3](https://linux-hardware.org/?probe=64030c9ba3) | Oct 24, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d135b32e8b](https://linux-hardware.org/?probe=d135b32e8b) | Oct 21, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [0e72f3b2e8](https://linux-hardware.org/?probe=0e72f3b2e8) | Oct 21, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [108583577e](https://linux-hardware.org/?probe=108583577e) | Oct 21, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [ec9a97a15d](https://linux-hardware.org/?probe=ec9a97a15d) | Oct 20, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | Notebook    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| Lenovo        | G580 2689H2G                | Notebook    | [1d81a2fb3b](https://linux-hardware.org/?probe=1d81a2fb3b) | Oct 18, 2022 |
| Notebook      | N15_17RD,RD2                | Notebook    | [50713b916b](https://linux-hardware.org/?probe=50713b916b) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [8a3de9dbf2](https://linux-hardware.org/?probe=8a3de9dbf2) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [3dd30d87be](https://linux-hardware.org/?probe=3dd30d87be) | Oct 18, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| HP            | Presario C300 (RM500EA#A... | Notebook    | [c35d7b0ee3](https://linux-hardware.org/?probe=c35d7b0ee3) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| IBM           | ThinkPad R51 1836Q4U        | Notebook    | [f77e633009](https://linux-hardware.org/?probe=f77e633009) | Oct 11, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [e9b6d4e613](https://linux-hardware.org/?probe=e9b6d4e613) | Oct 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| HP            | 1497                        | Desktop     | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| Acer          | AO532h                      | Notebook    | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | Notebook    | [fef4bc54eb](https://linux-hardware.org/?probe=fef4bc54eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | Notebook    | [db6bdb0dbd](https://linux-hardware.org/?probe=db6bdb0dbd) | Sep 20, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [0408dbc0cc](https://linux-hardware.org/?probe=0408dbc0cc) | Sep 19, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [55497ec8a3](https://linux-hardware.org/?probe=55497ec8a3) | Sep 19, 2022 |
| Dell          | System XPS L702X            | Notebook    | [6f7b318b6d](https://linux-hardware.org/?probe=6f7b318b6d) | Sep 17, 2022 |
| Dell          | System XPS L702X            | Notebook    | [4b812d3653](https://linux-hardware.org/?probe=4b812d3653) | Sep 17, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [3b63a75571](https://linux-hardware.org/?probe=3b63a75571) | Sep 16, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [575e8f5f81](https://linux-hardware.org/?probe=575e8f5f81) | Sep 14, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f90bed17e2](https://linux-hardware.org/?probe=f90bed17e2) | Sep 13, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [55ee4f593c](https://linux-hardware.org/?probe=55ee4f593c) | Sep 12, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [e5067297e8](https://linux-hardware.org/?probe=e5067297e8) | Sep 07, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1d387a1216](https://linux-hardware.org/?probe=1d387a1216) | Sep 07, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Dell          | Latitude E6500              | Notebook    | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [552d907afc](https://linux-hardware.org/?probe=552d907afc) | Aug 20, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Dell          | 0MWYPT A00                  | Desktop     | [9b33533a8d](https://linux-hardware.org/?probe=9b33533a8d) | Aug 09, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [06422a72b8](https://linux-hardware.org/?probe=06422a72b8) | Aug 08, 2022 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [b8b2ea30e1](https://linux-hardware.org/?probe=b8b2ea30e1) | Aug 08, 2022 |
| ASUSTek       | 1015PX                      | Notebook    | [af43595e7b](https://linux-hardware.org/?probe=af43595e7b) | Aug 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2d4b30ec72](https://linux-hardware.org/?probe=2d4b30ec72) | Aug 07, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [0ebff09d2b](https://linux-hardware.org/?probe=0ebff09d2b) | Aug 07, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [93794bf0b1](https://linux-hardware.org/?probe=93794bf0b1) | Aug 01, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [b0b9ddad28](https://linux-hardware.org/?probe=b0b9ddad28) | Jul 30, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [2de6d95c80](https://linux-hardware.org/?probe=2de6d95c80) | Jul 28, 2022 |
| Gigabyte      | Z590 D                      | Desktop     | [fe718899cb](https://linux-hardware.org/?probe=fe718899cb) | Jul 26, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| Toshiba       | EQUIUM A110                 | Notebook    | [4b6ace9122](https://linux-hardware.org/?probe=4b6ace9122) | Jul 22, 2022 |
| Huanan        | X79 VAA1                    | Desktop     | [9069c6e2ad](https://linux-hardware.org/?probe=9069c6e2ad) | Jul 19, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [f653a494f3](https://linux-hardware.org/?probe=f653a494f3) | Jul 18, 2022 |
| HP            | Presario V2000 (EC158UA#... | Notebook    | [d46bb41a18](https://linux-hardware.org/?probe=d46bb41a18) | Jul 08, 2022 |
| HP            | Presario V2000 (EC158UA#... | Notebook    | [c55a6d7cca](https://linux-hardware.org/?probe=c55a6d7cca) | Jul 08, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c09a3e0c24](https://linux-hardware.org/?probe=c09a3e0c24) | Jul 08, 2022 |
| MSI           | MS-AA71                     | All in one  | [4e7d1d05d6](https://linux-hardware.org/?probe=4e7d1d05d6) | Jul 06, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e400d050db](https://linux-hardware.org/?probe=e400d050db) | Jul 05, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [cc62a478ac](https://linux-hardware.org/?probe=cc62a478ac) | Jul 01, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [3bbee83307](https://linux-hardware.org/?probe=3bbee83307) | Jun 30, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [0b299bea1b](https://linux-hardware.org/?probe=0b299bea1b) | Jun 30, 2022 |
| Biostar       | H510MH/E                    | Desktop     | [7b28198a82](https://linux-hardware.org/?probe=7b28198a82) | Jun 30, 2022 |
| Nvidia        | Tegra                       | Soc         | [cfeb6fb78f](https://linux-hardware.org/?probe=cfeb6fb78f) | Jun 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [d08060fb50](https://linux-hardware.org/?probe=d08060fb50) | Jun 23, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [672749ef0e](https://linux-hardware.org/?probe=672749ef0e) | Jun 22, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [bbfd4f7b68](https://linux-hardware.org/?probe=bbfd4f7b68) | Jun 22, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [f395d01890](https://linux-hardware.org/?probe=f395d01890) | Jun 21, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | Notebook    | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| Nvidia        | Tegra                       | Soc         | [4d32910c65](https://linux-hardware.org/?probe=4d32910c65) | Jun 16, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [ba10f6ee4f](https://linux-hardware.org/?probe=ba10f6ee4f) | Jun 14, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [5ad081e335](https://linux-hardware.org/?probe=5ad081e335) | Jun 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [73f3d67b14](https://linux-hardware.org/?probe=73f3d67b14) | Jun 13, 2022 |
| HP            | 3398                        | Desktop     | [fe4629c354](https://linux-hardware.org/?probe=fe4629c354) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [4f9d7a297e](https://linux-hardware.org/?probe=4f9d7a297e) | Jun 05, 2022 |
| HP            | 09E8h                       | Desktop     | [9c75a338fc](https://linux-hardware.org/?probe=9c75a338fc) | May 31, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3fbca187e7](https://linux-hardware.org/?probe=3fbca187e7) | May 31, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [55e99cb697](https://linux-hardware.org/?probe=55e99cb697) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | Notebook    | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e054e02eba](https://linux-hardware.org/?probe=e054e02eba) | May 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Shuttle       | FH170                       | Desktop     | [2645369ebc](https://linux-hardware.org/?probe=2645369ebc) | May 24, 2022 |
| HP            | Compaq 6720s                | Notebook    | [b7ea743814](https://linux-hardware.org/?probe=b7ea743814) | May 22, 2022 |
| HP            | Compaq 6720s                | Notebook    | [c0b723e185](https://linux-hardware.org/?probe=c0b723e185) | May 22, 2022 |
| HP            | 3398                        | Desktop     | [d7e6c0c903](https://linux-hardware.org/?probe=d7e6c0c903) | May 22, 2022 |
| HP            | Mini 210-1000               | Notebook    | [f4d6735690](https://linux-hardware.org/?probe=f4d6735690) | May 20, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a25740096](https://linux-hardware.org/?probe=0a25740096) | May 18, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [952fd1b0ac](https://linux-hardware.org/?probe=952fd1b0ac) | May 13, 2022 |
| Shuttle       | FH170                       | Desktop     | [9a5b55b35c](https://linux-hardware.org/?probe=9a5b55b35c) | May 13, 2022 |
| ASRock        | AM1B-ITX                    | Desktop     | [622db6a0da](https://linux-hardware.org/?probe=622db6a0da) | May 12, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| HP            | Mini 110-1000               | Notebook    | [e1a5afc203](https://linux-hardware.org/?probe=e1a5afc203) | May 06, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [329673fcbf](https://linux-hardware.org/?probe=329673fcbf) | May 03, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f639c7c8f5](https://linux-hardware.org/?probe=f639c7c8f5) | Apr 29, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| Acer          | TM4750                      | Notebook    | [8254e2b47d](https://linux-hardware.org/?probe=8254e2b47d) | Apr 27, 2022 |
| HP            | 3646h                       | Desktop     | [131d2ef893](https://linux-hardware.org/?probe=131d2ef893) | Apr 23, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [75dc6c44e5](https://linux-hardware.org/?probe=75dc6c44e5) | Apr 23, 2022 |
| HP            | 3646h                       | Desktop     | [e232464dd6](https://linux-hardware.org/?probe=e232464dd6) | Apr 22, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [e0729e8375](https://linux-hardware.org/?probe=e0729e8375) | Apr 22, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0150424029](https://linux-hardware.org/?probe=0150424029) | Apr 22, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [15bba912da](https://linux-hardware.org/?probe=15bba912da) | Apr 21, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [7ef3e515d9](https://linux-hardware.org/?probe=7ef3e515d9) | Apr 15, 2022 |
| Dell          | 0N867P A01                  | Desktop     | [749dc04756](https://linux-hardware.org/?probe=749dc04756) | Apr 12, 2022 |
| Dell          | Latitude D630               | Notebook    | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| Unknown       | Unknown                     | Soc         | [99029e9661](https://linux-hardware.org/?probe=99029e9661) | Apr 08, 2022 |
| Timi          | TM1701                      | Notebook    | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| Lenovo        | ThinkPad P70 20ESS04S00     | Notebook    | [18bcdf72db](https://linux-hardware.org/?probe=18bcdf72db) | Apr 05, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e7d599e001](https://linux-hardware.org/?probe=e7d599e001) | Apr 01, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [52d7f90956](https://linux-hardware.org/?probe=52d7f90956) | Apr 01, 2022 |
| HP            | ProBook 6550b               | Notebook    | [d337221af6](https://linux-hardware.org/?probe=d337221af6) | Apr 01, 2022 |
| HP            | 0A54h                       | Desktop     | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [60b0ea7dd1](https://linux-hardware.org/?probe=60b0ea7dd1) | Mar 26, 2022 |
| eMachines     | eM350                       | Notebook    | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [f758ccfcbe](https://linux-hardware.org/?probe=f758ccfcbe) | Mar 25, 2022 |
| Panasonic     | CF-19AHUDX1M                | Notebook    | [638470e61d](https://linux-hardware.org/?probe=638470e61d) | Mar 25, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [4add06ac06](https://linux-hardware.org/?probe=4add06ac06) | Mar 17, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [1f948586ca](https://linux-hardware.org/?probe=1f948586ca) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [737a2d4c61](https://linux-hardware.org/?probe=737a2d4c61) | Mar 14, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [be2c2c791c](https://linux-hardware.org/?probe=be2c2c791c) | Mar 09, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [6563e94c95](https://linux-hardware.org/?probe=6563e94c95) | Mar 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [33ce116b8a](https://linux-hardware.org/?probe=33ce116b8a) | Mar 08, 2022 |
| Dell          | System XPS L322X            | Notebook    | [2aa0c05f64](https://linux-hardware.org/?probe=2aa0c05f64) | Mar 06, 2022 |
| Dell          | Precision WorkStation 53... | Desktop     | [0969471740](https://linux-hardware.org/?probe=0969471740) | Mar 05, 2022 |
| Nvidia        | Tegra                       | Soc         | [904f2d4f21](https://linux-hardware.org/?probe=904f2d4f21) | Feb 28, 2022 |
| Acer          | Aspire X3950                | Desktop     | [29e02ae274](https://linux-hardware.org/?probe=29e02ae274) | Feb 27, 2022 |
| Toshiba       | Satellite Pro A40-C         | Notebook    | [49766126e1](https://linux-hardware.org/?probe=49766126e1) | Feb 27, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [95b1251334](https://linux-hardware.org/?probe=95b1251334) | Feb 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [38511163be](https://linux-hardware.org/?probe=38511163be) | Feb 22, 2022 |
| HP            | 1494                        | Desktop     | [f2b67d46d0](https://linux-hardware.org/?probe=f2b67d46d0) | Feb 19, 2022 |
| MSI           | MS-AAA71 100                | Desktop     | [cf1a921cae](https://linux-hardware.org/?probe=cf1a921cae) | Feb 19, 2022 |
| Nvidia        | Tegra                       | Soc         | [7cde4a4d40](https://linux-hardware.org/?probe=7cde4a4d40) | Feb 19, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [16b6deff57](https://linux-hardware.org/?probe=16b6deff57) | Feb 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [7814d1e2f8](https://linux-hardware.org/?probe=7814d1e2f8) | Feb 18, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [ee8d1e4b48](https://linux-hardware.org/?probe=ee8d1e4b48) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [7a511b44b6](https://linux-hardware.org/?probe=7a511b44b6) | Feb 12, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a45da375c0](https://linux-hardware.org/?probe=a45da375c0) | Feb 11, 2022 |
| ASRock        | X99M Extreme4               | Desktop     | [c07bb42ff3](https://linux-hardware.org/?probe=c07bb42ff3) | Feb 08, 2022 |
| ASRock        | X99M Extreme4               | Desktop     | [eeb38fc01d](https://linux-hardware.org/?probe=eeb38fc01d) | Feb 07, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [5a471683f7](https://linux-hardware.org/?probe=5a471683f7) | Feb 05, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c55769f459](https://linux-hardware.org/?probe=c55769f459) | Feb 02, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [b685151ac1](https://linux-hardware.org/?probe=b685151ac1) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [712c420215](https://linux-hardware.org/?probe=712c420215) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0c05019294](https://linux-hardware.org/?probe=0c05019294) | Jan 31, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| Acer          | Aspire X3950                | Desktop     | [c3e1066388](https://linux-hardware.org/?probe=c3e1066388) | Jan 30, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [0cb832f85f](https://linux-hardware.org/?probe=0cb832f85f) | Jan 27, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [16d9024680](https://linux-hardware.org/?probe=16d9024680) | Jan 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e9752ad35d](https://linux-hardware.org/?probe=e9752ad35d) | Jan 24, 2022 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [5aa25aeeeb](https://linux-hardware.org/?probe=5aa25aeeeb) | Jan 21, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [90b4523b21](https://linux-hardware.org/?probe=90b4523b21) | Jan 19, 2022 |
| MSI           | H310M-S03                   | Desktop     | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [d43bc9ead0](https://linux-hardware.org/?probe=d43bc9ead0) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [5cabde7162](https://linux-hardware.org/?probe=5cabde7162) | Jan 08, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [753fcd1661](https://linux-hardware.org/?probe=753fcd1661) | Jan 08, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [c3a0a425f9](https://linux-hardware.org/?probe=c3a0a425f9) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [ea4bdf8279](https://linux-hardware.org/?probe=ea4bdf8279) | Jan 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [bc75234559](https://linux-hardware.org/?probe=bc75234559) | Jan 06, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [3d44173eda](https://linux-hardware.org/?probe=3d44173eda) | Jan 05, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [759f405820](https://linux-hardware.org/?probe=759f405820) | Jan 05, 2022 |
| Dell          | 0MM599                      | Desktop     | [82532cb19f](https://linux-hardware.org/?probe=82532cb19f) | Jan 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Lenovo        | ThinkPad T430 23426FU       | Notebook    | [53e2109383](https://linux-hardware.org/?probe=53e2109383) | Dec 30, 2021 |
| Gigabyte      | M61PME-S2                   | Desktop     | [f7fd55088e](https://linux-hardware.org/?probe=f7fd55088e) | Dec 27, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9fb08ebeb4](https://linux-hardware.org/?probe=9fb08ebeb4) | Dec 26, 2021 |
| Dell          | 0NDYHG A01                  | Desktop     | [093e7e5784](https://linux-hardware.org/?probe=093e7e5784) | Dec 20, 2021 |
| MSI           | GS66 Stealth 11UE           | Notebook    | [ab09d4463d](https://linux-hardware.org/?probe=ab09d4463d) | Dec 20, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Toshiba       | Satellite C600              | Notebook    | [dd417ecb87](https://linux-hardware.org/?probe=dd417ecb87) | Dec 15, 2021 |
| Sony          | VGN-NR430E                  | Notebook    | [305865a785](https://linux-hardware.org/?probe=305865a785) | Dec 12, 2021 |
| Sony          | VGN-NR430E                  | Notebook    | [3ca106703d](https://linux-hardware.org/?probe=3ca106703d) | Dec 11, 2021 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [cd0e6354c3](https://linux-hardware.org/?probe=cd0e6354c3) | Dec 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [4b84ebe353](https://linux-hardware.org/?probe=4b84ebe353) | Dec 08, 2021 |
| Dell          | Latitude 3410               | Notebook    | [c2a6a9ad6b](https://linux-hardware.org/?probe=c2a6a9ad6b) | Dec 08, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [5b7f08a29b](https://linux-hardware.org/?probe=5b7f08a29b) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | Desktop     | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Nvidia        | Tegra                       | Soc         | [87cf7f053c](https://linux-hardware.org/?probe=87cf7f053c) | Dec 06, 2021 |
| Nvidia        | Tegra                       | Soc         | [b62c884aec](https://linux-hardware.org/?probe=b62c884aec) | Dec 05, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [a700683a6f](https://linux-hardware.org/?probe=a700683a6f) | Dec 05, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | Notebook    | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [a9ef047f21](https://linux-hardware.org/?probe=a9ef047f21) | Dec 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c9ed75dd92](https://linux-hardware.org/?probe=c9ed75dd92) | Dec 02, 2021 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [09fd8a63b7](https://linux-hardware.org/?probe=09fd8a63b7) | Nov 30, 2021 |
| Sony          | VGN-FE31B                   | Notebook    | [9c79f90f8d](https://linux-hardware.org/?probe=9c79f90f8d) | Nov 27, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b5f54d657a](https://linux-hardware.org/?probe=b5f54d657a) | Nov 27, 2021 |
| Acer          | Aspire 6920                 | Notebook    | [ecd71d1bde](https://linux-hardware.org/?probe=ecd71d1bde) | Nov 26, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7045bece2c](https://linux-hardware.org/?probe=7045bece2c) | Nov 23, 2021 |
| Packard Be... | EasyNote TJ75               | Notebook    | [76b8b98ec9](https://linux-hardware.org/?probe=76b8b98ec9) | Nov 21, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [dc3ffc2288](https://linux-hardware.org/?probe=dc3ffc2288) | Nov 20, 2021 |
| MSI           | Boston                      | Desktop     | [6e0d850a8e](https://linux-hardware.org/?probe=6e0d850a8e) | Nov 17, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [1f5deb0f31](https://linux-hardware.org/?probe=1f5deb0f31) | Nov 16, 2021 |
| Lenovo        | IdeaPad Z460 0913           | Notebook    | [0bb3eea006](https://linux-hardware.org/?probe=0bb3eea006) | Nov 16, 2021 |
| Acer          | One S1003                   | Tablet      | [e88252db3f](https://linux-hardware.org/?probe=e88252db3f) | Nov 13, 2021 |
| Lenovo        | G580 26897JJ                | Notebook    | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [a9cf3f2b5b](https://linux-hardware.org/?probe=a9cf3f2b5b) | Nov 08, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [85d8ecd997](https://linux-hardware.org/?probe=85d8ecd997) | Nov 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0c99cea4ba](https://linux-hardware.org/?probe=0c99cea4ba) | Nov 07, 2021 |
| Notebook      | NP50DE_DB                   | Notebook    | [6ecc612580](https://linux-hardware.org/?probe=6ecc612580) | Nov 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| Dell          | 0MTFWP A00                  | Desktop     | [46f1aaf23a](https://linux-hardware.org/?probe=46f1aaf23a) | Nov 03, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5f0bcd4c39](https://linux-hardware.org/?probe=5f0bcd4c39) | Oct 30, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [e4aa5740c5](https://linux-hardware.org/?probe=e4aa5740c5) | Oct 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [338ddd258e](https://linux-hardware.org/?probe=338ddd258e) | Oct 24, 2021 |
| Dell          | Precision 3520              | Notebook    | [cf720e50db](https://linux-hardware.org/?probe=cf720e50db) | Oct 24, 2021 |
| Dell          | Latitude D620               | Notebook    | [19049fd2bd](https://linux-hardware.org/?probe=19049fd2bd) | Oct 23, 2021 |
| Dell          | Latitude D620               | Notebook    | [08fd9efc01](https://linux-hardware.org/?probe=08fd9efc01) | Oct 23, 2021 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ec418886cd](https://linux-hardware.org/?probe=ec418886cd) | Oct 22, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [17baa8dc0e](https://linux-hardware.org/?probe=17baa8dc0e) | Oct 19, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dd8ce106ae](https://linux-hardware.org/?probe=dd8ce106ae) | Oct 17, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bf52ab65ff](https://linux-hardware.org/?probe=bf52ab65ff) | Oct 17, 2021 |
| Dell          | 040DDP A00                  | Desktop     | [95249e56f5](https://linux-hardware.org/?probe=95249e56f5) | Oct 15, 2021 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [19bdd9712d](https://linux-hardware.org/?probe=19bdd9712d) | Oct 09, 2021 |
| Acer          | Aspire E5-432               | Notebook    | [ff1a22fdc4](https://linux-hardware.org/?probe=ff1a22fdc4) | Oct 08, 2021 |
| Toshiba       | dynabook R634/K             | Notebook    | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [38571fcfb9](https://linux-hardware.org/?probe=38571fcfb9) | Oct 04, 2021 |
| Lenovo        | ThinkPad E15 20RD001CGE     | Notebook    | [f7d150a85c](https://linux-hardware.org/?probe=f7d150a85c) | Oct 04, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | Notebook    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [57b3b27a47](https://linux-hardware.org/?probe=57b3b27a47) | Sep 28, 2021 |
| eMachines     | EL1352                      | Desktop     | [2d5f9a7733](https://linux-hardware.org/?probe=2d5f9a7733) | Sep 27, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [31e1740325](https://linux-hardware.org/?probe=31e1740325) | Sep 24, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [5b046ba6ee](https://linux-hardware.org/?probe=5b046ba6ee) | Sep 24, 2021 |
| Acer          | Aspire one 1-431            | Notebook    | [3ff4be2b55](https://linux-hardware.org/?probe=3ff4be2b55) | Sep 21, 2021 |
| Dell          | 0XCR8D A00                  | Desktop     | [a2d02a9a2d](https://linux-hardware.org/?probe=a2d02a9a2d) | Sep 20, 2021 |
| Acer          | AO751h                      | Notebook    | [d217a1c6b7](https://linux-hardware.org/?probe=d217a1c6b7) | Sep 18, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [aa3f685f0a](https://linux-hardware.org/?probe=aa3f685f0a) | Sep 15, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [cd630332c7](https://linux-hardware.org/?probe=cd630332c7) | Sep 15, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [1a39f562b3](https://linux-hardware.org/?probe=1a39f562b3) | Sep 13, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [271309ac53](https://linux-hardware.org/?probe=271309ac53) | Sep 12, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [db2503f46f](https://linux-hardware.org/?probe=db2503f46f) | Sep 07, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b5b00e8498](https://linux-hardware.org/?probe=b5b00e8498) | Sep 06, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [0d3b75782b](https://linux-hardware.org/?probe=0d3b75782b) | Sep 03, 2021 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [ee76fbd8e5](https://linux-hardware.org/?probe=ee76fbd8e5) | Sep 03, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [5bdbb1445f](https://linux-hardware.org/?probe=5bdbb1445f) | Sep 03, 2021 |
| Panasonic     | CF-20-1                     | Notebook    | [6f921aa428](https://linux-hardware.org/?probe=6f921aa428) | Sep 02, 2021 |
| HP            | 3032h                       | Desktop     | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6c149c6405](https://linux-hardware.org/?probe=6c149c6405) | Aug 31, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| ARCELIK       | GNB 15xx B1 Serisi          | Notebook    | [8537b57efa](https://linux-hardware.org/?probe=8537b57efa) | Aug 24, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [f0a640519a](https://linux-hardware.org/?probe=f0a640519a) | Aug 17, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [87d045fa9c](https://linux-hardware.org/?probe=87d045fa9c) | Aug 16, 2021 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [874eaab0bb](https://linux-hardware.org/?probe=874eaab0bb) | Aug 15, 2021 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [c31fdfca91](https://linux-hardware.org/?probe=c31fdfca91) | Aug 15, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [feaabd09c8](https://linux-hardware.org/?probe=feaabd09c8) | Aug 10, 2021 |
| Dell          | Latitude E7450              | Notebook    | [5e94ad6881](https://linux-hardware.org/?probe=5e94ad6881) | Aug 10, 2021 |
| Dell          | Latitude E7450              | Notebook    | [110fc3ebef](https://linux-hardware.org/?probe=110fc3ebef) | Aug 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [8227b4305d](https://linux-hardware.org/?probe=8227b4305d) | Aug 09, 2021 |
| Acer          | AO531h                      | Notebook    | [f677e6e910](https://linux-hardware.org/?probe=f677e6e910) | Aug 09, 2021 |
| Acer          | AO531h                      | Notebook    | [42bc030846](https://linux-hardware.org/?probe=42bc030846) | Aug 09, 2021 |
| Acer          | AO531h                      | Notebook    | [3475d2f343](https://linux-hardware.org/?probe=3475d2f343) | Aug 09, 2021 |
| HP            | ENVY 17                     | Notebook    | [1d6dd8440c](https://linux-hardware.org/?probe=1d6dd8440c) | Aug 05, 2021 |
| Dell          | Studio 1737                 | Notebook    | [b4f16960c4](https://linux-hardware.org/?probe=b4f16960c4) | Aug 05, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [8de53a9490](https://linux-hardware.org/?probe=8de53a9490) | Aug 04, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [ec6ce0a80c](https://linux-hardware.org/?probe=ec6ce0a80c) | Aug 04, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [955d3e4330](https://linux-hardware.org/?probe=955d3e4330) | Aug 02, 2021 |
| ASRock        | Z170 OC Formula             | Desktop     | [0d1ca849b8](https://linux-hardware.org/?probe=0d1ca849b8) | Jul 29, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [b7fec1807a](https://linux-hardware.org/?probe=b7fec1807a) | Jul 29, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [48b32724e2](https://linux-hardware.org/?probe=48b32724e2) | Jul 27, 2021 |
| Teclast       | F6 Pro                      | Notebook    | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [d7369d7eb4](https://linux-hardware.org/?probe=d7369d7eb4) | Jul 26, 2021 |
| HP            | 1494                        | Desktop     | [fe57b848c7](https://linux-hardware.org/?probe=fe57b848c7) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| Dell          | 0MTFWP A00                  | Desktop     | [bde85c8a04](https://linux-hardware.org/?probe=bde85c8a04) | Jul 21, 2021 |
| Nvidia        | Tegra                       | Soc         | [ecddedcfb7](https://linux-hardware.org/?probe=ecddedcfb7) | Jul 20, 2021 |
| HP            | 1494                        | Desktop     | [2c30dc2cf3](https://linux-hardware.org/?probe=2c30dc2cf3) | Jul 19, 2021 |
| Gateway       | NE570                       | Notebook    | [f9ccf3665f](https://linux-hardware.org/?probe=f9ccf3665f) | Jul 19, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [b221cbc463](https://linux-hardware.org/?probe=b221cbc463) | Jul 17, 2021 |
| Pegatron      | EVE                         | Desktop     | [a8fb12adae](https://linux-hardware.org/?probe=a8fb12adae) | Jul 16, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [7908947c9f](https://linux-hardware.org/?probe=7908947c9f) | Jul 14, 2021 |
| HP            | Pavilion dv6                | Notebook    | [aee9cfed82](https://linux-hardware.org/?probe=aee9cfed82) | Jul 11, 2021 |
| Acer          | Aspire 7740                 | Notebook    | [d8694dd629](https://linux-hardware.org/?probe=d8694dd629) | Jul 09, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [2e203beafd](https://linux-hardware.org/?probe=2e203beafd) | Jul 08, 2021 |
| MSI           | J1900I                      | Desktop     | [31b65c37c9](https://linux-hardware.org/?probe=31b65c37c9) | Jul 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [cac1bff4a1](https://linux-hardware.org/?probe=cac1bff4a1) | Jul 06, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [6130e48df9](https://linux-hardware.org/?probe=6130e48df9) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8fcf62f37c](https://linux-hardware.org/?probe=8fcf62f37c) | Jul 05, 2021 |
| Dell          | 0HY9JP A00                  | Desktop     | [300272bb79](https://linux-hardware.org/?probe=300272bb79) | Jul 03, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [222b34dd03](https://linux-hardware.org/?probe=222b34dd03) | Jul 01, 2021 |
| HP            | Pavilion g4                 | Notebook    | [fa58b1dd24](https://linux-hardware.org/?probe=fa58b1dd24) | Jun 30, 2021 |
| Dell          | Precision 7550              | Notebook    | [79a56a6b22](https://linux-hardware.org/?probe=79a56a6b22) | Jun 30, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [4fd63df257](https://linux-hardware.org/?probe=4fd63df257) | Jun 30, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [ab620ec059](https://linux-hardware.org/?probe=ab620ec059) | Jun 29, 2021 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| HP            | 18E7                        | Desktop     | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ada772c932](https://linux-hardware.org/?probe=ada772c932) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7MM0... | Notebook    | [4e01561e2d](https://linux-hardware.org/?probe=4e01561e2d) | Jun 25, 2021 |
| Dell          | Latitude 5591               | Notebook    | [0a888c201f](https://linux-hardware.org/?probe=0a888c201f) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7MM0... | Notebook    | [424e9fe919](https://linux-hardware.org/?probe=424e9fe919) | Jun 24, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [1f4ef21a29](https://linux-hardware.org/?probe=1f4ef21a29) | Jun 24, 2021 |
| Dell          | Precision 5550              | Notebook    | [7b9e5a1b30](https://linux-hardware.org/?probe=7b9e5a1b30) | Jun 23, 2021 |
| Dell          | Latitude 5511               | Notebook    | [6625368d80](https://linux-hardware.org/?probe=6625368d80) | Jun 21, 2021 |
| Nvidia        | Tegra                       | Soc         | [7616b8f6b7](https://linux-hardware.org/?probe=7616b8f6b7) | Jun 21, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7ddb9a5ab7](https://linux-hardware.org/?probe=7ddb9a5ab7) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [7026c20c97](https://linux-hardware.org/?probe=7026c20c97) | Jun 20, 2021 |
| Dell          | Latitude 5511               | Notebook    | [3b8bd7756c](https://linux-hardware.org/?probe=3b8bd7756c) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [f34a1bbe5a](https://linux-hardware.org/?probe=f34a1bbe5a) | Jun 20, 2021 |
| HP            | ProBook 6550b               | Notebook    | [262ede4645](https://linux-hardware.org/?probe=262ede4645) | Jun 16, 2021 |
| MSI           | 870A-G54                    | Desktop     | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [9814f75415](https://linux-hardware.org/?probe=9814f75415) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3d0b697005](https://linux-hardware.org/?probe=3d0b697005) | Jun 09, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [977558100f](https://linux-hardware.org/?probe=977558100f) | Jun 09, 2021 |
| Lenovo        | 30C1                        | Desktop     | [e6fcdd8be6](https://linux-hardware.org/?probe=e6fcdd8be6) | Jun 08, 2021 |
| HP            | Notebook                    | Notebook    | [aa603459f8](https://linux-hardware.org/?probe=aa603459f8) | Jun 06, 2021 |
| Toshiba       | Satellite Pro A40-C         | Notebook    | [a467cae210](https://linux-hardware.org/?probe=a467cae210) | Jun 03, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [6018f18645](https://linux-hardware.org/?probe=6018f18645) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [03b8f35b44](https://linux-hardware.org/?probe=03b8f35b44) | Jun 02, 2021 |
| Acer          | Aspire 4830TG               | Notebook    | [0233ed2211](https://linux-hardware.org/?probe=0233ed2211) | May 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5f8bfd5fbf](https://linux-hardware.org/?probe=5f8bfd5fbf) | May 30, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Lenovo        | ThinkPad T530 24291H4       | Notebook    | [9ecbb7a946](https://linux-hardware.org/?probe=9ecbb7a946) | May 28, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [d7e0be00c1](https://linux-hardware.org/?probe=d7e0be00c1) | May 27, 2021 |
| Hometech      | N1401A                      | Notebook    | [421dcf0a2f](https://linux-hardware.org/?probe=421dcf0a2f) | May 27, 2021 |
| ASUSTek       | P4S800-MX SE                | Desktop     | [7a323363ef](https://linux-hardware.org/?probe=7a323363ef) | May 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [4ea4310ddc](https://linux-hardware.org/?probe=4ea4310ddc) | May 22, 2021 |
| ECS           | A780GM-A                    | Desktop     | [03853132a4](https://linux-hardware.org/?probe=03853132a4) | May 20, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9b05fb9e1f](https://linux-hardware.org/?probe=9b05fb9e1f) | May 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [0d397cf104](https://linux-hardware.org/?probe=0d397cf104) | May 16, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [b5c18575bf](https://linux-hardware.org/?probe=b5c18575bf) | May 15, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [df4d80f1f9](https://linux-hardware.org/?probe=df4d80f1f9) | May 14, 2021 |
| Acer          | LuganoII                    | Notebook    | [c26e330dae](https://linux-hardware.org/?probe=c26e330dae) | May 13, 2021 |
| Nvidia        | Tegra                       | Soc         | [742be0320c](https://linux-hardware.org/?probe=742be0320c) | May 12, 2021 |
| Acer          | AOA150                      | Notebook    | [21647e22ba](https://linux-hardware.org/?probe=21647e22ba) | May 12, 2021 |
| Acer          | LuganoII                    | Notebook    | [3a87a5cef9](https://linux-hardware.org/?probe=3a87a5cef9) | May 12, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [98ad000dc7](https://linux-hardware.org/?probe=98ad000dc7) | May 11, 2021 |
| Dell          | 0DXYK6 A01                  | Desktop     | [a3183357c9](https://linux-hardware.org/?probe=a3183357c9) | May 10, 2021 |
| Lenovo        | M5400 20281                 | Notebook    | [b0b95cd759](https://linux-hardware.org/?probe=b0b95cd759) | May 09, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dce60f14e1](https://linux-hardware.org/?probe=dce60f14e1) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| HP            | 3029h                       | Desktop     | [dfcd82490e](https://linux-hardware.org/?probe=dfcd82490e) | May 08, 2021 |
| HP            | 3029h                       | Desktop     | [f54bf8eeb9](https://linux-hardware.org/?probe=f54bf8eeb9) | May 08, 2021 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [a2ec86f284](https://linux-hardware.org/?probe=a2ec86f284) | May 08, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Biostar       | IH61MF-Q5                   | Desktop     | [21134da958](https://linux-hardware.org/?probe=21134da958) | May 06, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [22cfe5b72a](https://linux-hardware.org/?probe=22cfe5b72a) | May 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [522b86dc40](https://linux-hardware.org/?probe=522b86dc40) | May 03, 2021 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [0ff4565a31](https://linux-hardware.org/?probe=0ff4565a31) | May 02, 2021 |
| Dell          | Latitude E5440              | Notebook    | [ea59351ece](https://linux-hardware.org/?probe=ea59351ece) | May 01, 2021 |
| Dell          | Latitude 7480               | Notebook    | [6b9e1797c6](https://linux-hardware.org/?probe=6b9e1797c6) | Apr 29, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [ae9a58ea22](https://linux-hardware.org/?probe=ae9a58ea22) | Apr 27, 2021 |
| Nvidia        | Tegra                       | Soc         | [6adca880a0](https://linux-hardware.org/?probe=6adca880a0) | Apr 27, 2021 |
| Nvidia        | Tegra                       | Soc         | [b7b0ca04bc](https://linux-hardware.org/?probe=b7b0ca04bc) | Apr 27, 2021 |
| ASUSTek       | Amberine M                  | Desktop     | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [34ab0fd5ed](https://linux-hardware.org/?probe=34ab0fd5ed) | Apr 24, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [bd53dff836](https://linux-hardware.org/?probe=bd53dff836) | Apr 23, 2021 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [daf737a5ba](https://linux-hardware.org/?probe=daf737a5ba) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1bcff94731](https://linux-hardware.org/?probe=1bcff94731) | Apr 20, 2021 |
| ASRock        | B550 Steel Legend           | Desktop     | [d8db6d8577](https://linux-hardware.org/?probe=d8db6d8577) | Apr 18, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [c75019619f](https://linux-hardware.org/?probe=c75019619f) | Apr 17, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [2070ae5e60](https://linux-hardware.org/?probe=2070ae5e60) | Apr 11, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [ec2915656d](https://linux-hardware.org/?probe=ec2915656d) | Apr 09, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [b5253eecf6](https://linux-hardware.org/?probe=b5253eecf6) | Apr 05, 2021 |
| Nvidia        | Tegra                       | Soc         | [3eef74187f](https://linux-hardware.org/?probe=3eef74187f) | Apr 04, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [a7a9af4a65](https://linux-hardware.org/?probe=a7a9af4a65) | Apr 04, 2021 |
| Acer          | TravelMate 5530             | Notebook    | [6b6df6431c](https://linux-hardware.org/?probe=6b6df6431c) | Apr 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Unity/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu Unity 16.04 | 605       | 44.88%  |
| Ubuntu Unity 20.04 | 250       | 18.55%  |
| Ubuntu Unity 18.04 | 244       | 18.1%   |
| Ubuntu Unity 22.04 | 89        | 6.6%    |
| Ubuntu Unity 24.04 | 60        | 4.45%   |
| Ubuntu Unity 22.10 | 16        | 1.19%   |
| Ubuntu Unity 19.10 | 13        | 0.96%   |
| Ubuntu Unity 23.04 | 12        | 0.89%   |
| Ubuntu Unity 23.10 | 10        | 0.74%   |
| Ubuntu Unity 21.10 | 10        | 0.74%   |
| Ubuntu Unity 21.04 | 9         | 0.67%   |
| Ubuntu Unity 20.10 | 8         | 0.59%   |
| Ubuntu Unity 24.10 | 7         | 0.52%   |
| Ubuntu Unity 14.04 | 6         | 0.45%   |
| Ubuntu Unity 25.04 | 5         | 0.37%   |
| Ubuntu Unity 17.04 | 2         | 0.15%   |
| Ubuntu Unity 19.04 | 1         | 0.07%   |
| Ubuntu Unity 18.10 | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu Unity | 1329      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 4.15.0-142-generic | 104       | 7.11%   |
| 4.4.0-210-generic  | 46        | 3.15%   |
| 4.15.0-112-generic | 44        | 3.01%   |
| 4.15.0-45-generic  | 35        | 2.39%   |
| 4.15.0-99-generic  | 34        | 2.33%   |
| 4.15.0-91-generic  | 31        | 2.12%   |
| 4.15.0-96-generic  | 28        | 1.92%   |
| 4.15.0-88-generic  | 26        | 1.78%   |
| 4.15.0-72-generic  | 25        | 1.71%   |
| 5.4.0-42-generic   | 20        | 1.37%   |
| 4.9.140-tegra      | 20        | 1.37%   |
| 5.4.0-48-generic   | 19        | 1.3%    |
| 4.15.0-118-generic | 18        | 1.23%   |
| 4.15.0-101-generic | 18        | 1.23%   |
| 4.15.0-213-generic | 16        | 1.09%   |
| 5.4.0-52-generic   | 15        | 1.03%   |
| 4.4.0-177-generic  | 15        | 1.03%   |
| 4.15.0-128-generic | 15        | 1.03%   |
| 5.4.0-58-generic   | 14        | 0.96%   |
| 4.15.0-122-generic | 14        | 0.96%   |
| 4.15.0-74-generic  | 13        | 0.89%   |
| 4.15.0-117-generic | 13        | 0.89%   |
| 4.15.0-76-generic  | 12        | 0.82%   |
| 4.15.0-106-generic | 12        | 0.82%   |
| 4.4.0-184-generic  | 11        | 0.75%   |
| 4.15.0-107-generic | 11        | 0.75%   |
| 5.4.0-65-generic   | 10        | 0.68%   |
| 5.15.0-56-generic  | 10        | 0.68%   |
| 4.15.0-70-generic  | 9         | 0.62%   |
| 5.4.0-66-generic   | 8         | 0.55%   |
| 5.4.0-47-generic   | 8         | 0.55%   |
| 4.9.201-tegra      | 8         | 0.55%   |
| 4.4.0-176-generic  | 8         | 0.55%   |
| 4.15.0-133-generic | 8         | 0.55%   |
| 4.4.0-186-generic  | 7         | 0.48%   |
| 4.4.0-178-generic  | 7         | 0.48%   |
| 4.4.0-174-generic  | 7         | 0.48%   |
| 4.4.0-173-generic  | 7         | 0.48%   |
| 4.4.0-148-generic  | 7         | 0.48%   |
| 6.8.0-45-generic   | 6         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 572       | 42.09%  |
| 5.4.0   | 205       | 15.08%  |
| 4.4.0   | 188       | 13.83%  |
| 5.15.0  | 61        | 4.49%   |
| 6.8.0   | 41        | 3.02%   |
| 5.19.0  | 32        | 2.35%   |
| 5.8.0   | 28        | 2.06%   |
| 5.3.0   | 25        | 1.84%   |
| 4.9.140 | 25        | 1.84%   |
| 5.13.0  | 20        | 1.47%   |
| 6.5.0   | 18        | 1.32%   |
| 6.2.0   | 18        | 1.32%   |
| 5.11.0  | 18        | 1.32%   |
| 6.14.0  | 16        | 1.18%   |
| 6.11.0  | 14        | 1.03%   |
| 5.0.0   | 8         | 0.59%   |
| 4.9.201 | 8         | 0.59%   |
| 4.13.0  | 7         | 0.52%   |
| 4.9.253 | 6         | 0.44%   |
| 4.8.0   | 4         | 0.29%   |
| 3.13.0  | 4         | 0.29%   |
| 5.14.0  | 3         | 0.22%   |
| 6.0.0   | 2         | 0.15%   |
| 4.18.0  | 2         | 0.15%   |
| 4.10.0  | 2         | 0.15%   |
| 6.9.3   | 1         | 0.07%   |
| 6.2.11  | 1         | 0.07%   |
| 6.17.3  | 1         | 0.07%   |
| 6.14.3  | 1         | 0.07%   |
| 6.13.6  | 1         | 0.07%   |
| 6.13.5  | 1         | 0.07%   |
| 6.10.9  | 1         | 0.07%   |
| 6.10.3  | 1         | 0.07%   |
| 6.1.0   | 1         | 0.07%   |
| 5.9.6   | 1         | 0.07%   |
| 5.7.2   | 1         | 0.07%   |
| 5.7.19  | 1         | 0.07%   |
| 5.7.10  | 1         | 0.07%   |
| 5.7.1   | 1         | 0.07%   |
| 5.5.11  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15    | 573       | 42.23%  |
| 5.4     | 206       | 15.18%  |
| 4.4     | 188       | 13.85%  |
| 5.15    | 61        | 4.5%    |
| 6.8     | 41        | 3.02%   |
| 4.9     | 40        | 2.95%   |
| 5.19    | 32        | 2.36%   |
| 5.8     | 28        | 2.06%   |
| 5.3     | 26        | 1.92%   |
| 5.13    | 21        | 1.55%   |
| 6.2     | 19        | 1.4%    |
| 6.5     | 18        | 1.33%   |
| 5.11    | 18        | 1.33%   |
| 6.14    | 17        | 1.25%   |
| 6.11    | 14        | 1.03%   |
| 5.0     | 9         | 0.66%   |
| 4.13    | 7         | 0.52%   |
| 5.7     | 4         | 0.29%   |
| 4.8     | 4         | 0.29%   |
| 3.13    | 4         | 0.29%   |
| 5.16    | 3         | 0.22%   |
| 5.14    | 3         | 0.22%   |
| 6.13    | 2         | 0.15%   |
| 6.0     | 2         | 0.15%   |
| 5.17    | 2         | 0.15%   |
| 5.12    | 2         | 0.15%   |
| 4.19    | 2         | 0.15%   |
| 4.18    | 2         | 0.15%   |
| 4.10    | 2         | 0.15%   |
| 6.9     | 1         | 0.07%   |
| 6.17    | 1         | 0.07%   |
| 6.10    | 1         | 0.07%   |
| 6.1     | 1         | 0.07%   |
| 5.9     | 1         | 0.07%   |
| 5.5     | 1         | 0.07%   |
| 5.18    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 957       | 71.9%   |
| i686    | 332       | 24.94%  |
| aarch64 | 42        | 3.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Unity           | 1307      | 98.27%  |
| GNOME           | 20        | 1.5%    |
| KDE5            | 1         | 0.08%   |
| GNOME Flashback | 1         | 0.08%   |
| Cinnamon        | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1214      | 91.14%  |
| Wayland | 102       | 7.66%   |
| Tty     | 15        | 1.13%   |
| Unknown | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 694       | 51.37%  |
| LightDM | 379       | 28.05%  |
| GDM     | 183       | 13.55%  |
| GDM3    | 93        | 6.88%   |
| SDDM    | 2         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 494       | 37.06%  |
| de_DE   | 120       | 9%      |
| fr_FR   | 83        | 6.23%   |
| pt_BR   | 75        | 5.63%   |
| en_GB   | 67        | 5.03%   |
| en_IN   | 58        | 4.35%   |
| ru_RU   | 44        | 3.3%    |
| it_IT   | 43        | 3.23%   |
| es_ES   | 38        | 2.85%   |
| en_CA   | 28        | 2.1%    |
| Unknown | 26        | 1.95%   |
| pl_PL   | 22        | 1.65%   |
| nl_NL   | 16        | 1.2%    |
| en_AU   | 16        | 1.2%    |
| C       | 15        | 1.13%   |
| hu_HU   | 14        | 1.05%   |
| pt_PT   | 11        | 0.83%   |
| es_AR   | 11        | 0.83%   |
| tr_TR   | 9         | 0.68%   |
| es_MX   | 9         | 0.68%   |
| en_ZA   | 9         | 0.68%   |
| zh_CN   | 8         | 0.6%    |
| cs_CZ   | 8         | 0.6%    |
| en_PH   | 6         | 0.45%   |
| el_GR   | 6         | 0.45%   |
| da_DK   | 6         | 0.45%   |
| ja_JP   | 5         | 0.38%   |
| es_CO   | 5         | 0.38%   |
| zh_TW   | 4         | 0.3%    |
| ru_UA   | 4         | 0.3%    |
| ro_RO   | 4         | 0.3%    |
| nl_BE   | 4         | 0.3%    |
| en_NZ   | 4         | 0.3%    |
| en_IE   | 4         | 0.3%    |
| de_CH   | 4         | 0.3%    |
| de_AT   | 4         | 0.3%    |
| sv_SE   | 3         | 0.23%   |
| sl_SI   | 3         | 0.23%   |
| sk_SK   | 3         | 0.23%   |
| fi_FI   | 3         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 888       | 66.42%  |
| EFI  | 449       | 33.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1217      | 91.09%  |
| Tmpfs    | 85        | 6.36%   |
| Btrfs    | 8         | 0.6%    |
| Overlay  | 7         | 0.52%   |
| Ext3     | 6         | 0.45%   |
| Zfs      | 5         | 0.37%   |
| Ext2     | 3         | 0.22%   |
| Aufs     | 3         | 0.22%   |
| SquasXfs | 1         | 0.07%   |
| Jfs      | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 857       | 63.76%  |
| GPT     | 346       | 25.74%  |
| MBR     | 141       | 10.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1178      | 87.58%  |
| Yes       | 167       | 12.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 885       | 65.95%  |
| Yes       | 457       | 34.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 207       | 15.58%  |
| Hewlett-Packard     | 182       | 13.69%  |
| ASUSTek Computer    | 174       | 13.09%  |
| Lenovo              | 150       | 11.29%  |
| Gigabyte Technology | 93        | 7%      |
| Acer                | 71        | 5.34%   |
| MSI                 | 52        | 3.91%   |
| Toshiba             | 40        | 3.01%   |
| Nvidia              | 35        | 2.63%   |
| ASRock              | 35        | 2.63%   |
| Intel               | 31        | 2.33%   |
| Apple               | 28        | 2.11%   |
| Unknown             | 23        | 1.73%   |
| Fujitsu Siemens     | 16        | 1.2%    |
| Fujitsu             | 12        | 0.9%    |
| Sony                | 11        | 0.83%   |
| Samsung Electronics | 11        | 0.83%   |
| Positivo            | 11        | 0.83%   |
| Pegatron            | 9         | 0.68%   |
| ECS                 | 9         | 0.68%   |
| Notebook            | 7         | 0.53%   |
| Medion              | 7         | 0.53%   |
| HUAWEI              | 6         | 0.45%   |
| Itautec             | 5         | 0.38%   |
| Biostar             | 5         | 0.38%   |
| Timi                | 4         | 0.3%    |
| Supermicro          | 4         | 0.3%    |
| Packard Bell        | 4         | 0.3%    |
| IBM                 | 4         | 0.3%    |
| Foxconn             | 4         | 0.3%    |
| Semp Toshiba        | 3         | 0.23%   |
| LG Electronics      | 3         | 0.23%   |
| eMachines           | 3         | 0.23%   |
| Chuwi               | 3         | 0.23%   |
| Alienware           | 3         | 0.23%   |
| System76            | 2         | 0.15%   |
| PCWare              | 2         | 0.15%   |
| Panasonic           | 2         | 0.15%   |
| OEM                 | 2         | 0.15%   |
| NEC Computers       | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia Tegra               | 35        | 2.63%   |
| Unknown                    | 27        | 2.03%   |
| ASUS All Series            | 14        | 1.05%   |
| HP Pavilion dv6            | 7         | 0.53%   |
| Dell OptiPlex 755          | 6         | 0.45%   |
| HP ProBook 6550b           | 4         | 0.3%    |
| HP Notebook                | 4         | 0.3%    |
| HP Mini 210-1000           | 4         | 0.3%    |
| Dell OptiPlex 9020         | 4         | 0.3%    |
| Dell OptiPlex 7010         | 4         | 0.3%    |
| Dell Latitude 7480         | 4         | 0.3%    |
| Toshiba Satellite L300     | 3         | 0.23%   |
| Supermicro Super Server    | 3         | 0.23%   |
| Positivo Mobile            | 3         | 0.23%   |
| Itautec Infoway            | 3         | 0.23%   |
| HP Z400 Workstation        | 3         | 0.23%   |
| HP Pavilion dv7            | 3         | 0.23%   |
| Gigabyte GA-78LMT-USB3 6.0 | 3         | 0.23%   |
| Gigabyte G31M-ES2L         | 3         | 0.23%   |
| Dell XPS 13 9370           | 3         | 0.23%   |
| Dell XPS 13 7390           | 3         | 0.23%   |
| Dell Latitude D630         | 3         | 0.23%   |
| Dell Latitude D620         | 3         | 0.23%   |
| Dell Inspiron MM061        | 3         | 0.23%   |
| Dell Inspiron 5570         | 3         | 0.23%   |
| Dell Inspiron 3521         | 3         | 0.23%   |
| Dell Inspiron 1545         | 3         | 0.23%   |
| ASUS P4C800-E              | 3         | 0.23%   |
| ASUS 1005HA                | 3         | 0.23%   |
| Toshiba Satellite L745     | 2         | 0.15%   |
| Toshiba Portable PC        | 2         | 0.15%   |
| Toshiba NB505              | 2         | 0.15%   |
| Timi TM1701                | 2         | 0.15%   |
| Samsung R530/R730          | 2         | 0.15%   |
| Positivo N1103             | 2         | 0.15%   |
| MSI MS-7B86                | 2         | 0.15%   |
| MSI MS-7996                | 2         | 0.15%   |
| MSI MS-7817                | 2         | 0.15%   |
| MSI MS-7721                | 2         | 0.15%   |
| MSI MS-7640                | 2         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 70        | 5.27%   |
| Dell Inspiron            | 59        | 4.44%   |
| Acer Aspire              | 42        | 3.16%   |
| Dell Latitude            | 41        | 3.09%   |
| HP Compaq                | 39        | 2.93%   |
| HP Pavilion              | 38        | 2.86%   |
| Nvidia Tegra             | 35        | 2.63%   |
| Dell OptiPlex            | 33        | 2.48%   |
| Toshiba Satellite        | 27        | 2.03%   |
| Unknown                  | 27        | 2.03%   |
| Dell Precision           | 24        | 1.81%   |
| Dell XPS                 | 23        | 1.73%   |
| HP ProBook               | 21        | 1.58%   |
| Lenovo IdeaPad           | 20        | 1.5%    |
| ASUS PRIME               | 17        | 1.28%   |
| HP EliteBook             | 15        | 1.13%   |
| ASUS All                 | 14        | 1.05%   |
| Dell Vostro              | 13        | 0.98%   |
| HP ZBook                 | 9         | 0.68%   |
| ASUS ROG                 | 9         | 0.68%   |
| HP ENVY                  | 8         | 0.6%    |
| ASUS VivoBook            | 8         | 0.6%    |
| HP Mini                  | 6         | 0.45%   |
| HP Laptop                | 6         | 0.45%   |
| Lenovo Yoga              | 5         | 0.38%   |
| Lenovo ThinkCentre       | 5         | 0.38%   |
| Itautec Infoway          | 5         | 0.38%   |
| Fujitsu LIFEBOOK         | 5         | 0.38%   |
| ASUS M5A78L-M            | 5         | 0.38%   |
| Acer Extensa             | 5         | 0.38%   |
| Medion Akoya             | 4         | 0.3%    |
| Lenovo ThinkBook         | 4         | 0.3%    |
| Lenovo Legion            | 4         | 0.3%    |
| HP Presario              | 4         | 0.3%    |
| HP Notebook              | 4         | 0.3%    |
| Fujitsu Siemens LIFEBOOK | 4         | 0.3%    |
| Fujitsu Siemens ESPRIMO  | 4         | 0.3%    |
| Fujitsu ESPRIMO          | 4         | 0.3%    |
| ASUS Zenbook             | 4         | 0.3%    |
| ASUS TUF                 | 4         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 104       | 7.83%   |
| 2008    | 97        | 7.3%    |
| 2012    | 94        | 7.07%   |
| 2007    | 85        | 6.4%    |
| 2011    | 84        | 6.32%   |
| 2013    | 80        | 6.02%   |
| 2018    | 79        | 5.94%   |
| 2017    | 79        | 5.94%   |
| 2010    | 78        | 5.87%   |
| 2015    | 73        | 5.49%   |
| 2019    | 69        | 5.19%   |
| 2016    | 68        | 5.12%   |
| 2014    | 62        | 4.67%   |
| 2020    | 55        | 4.14%   |
| 2006    | 54        | 4.06%   |
| Unknown | 43        | 3.24%   |
| 2021    | 38        | 2.86%   |
| 2005    | 27        | 2.03%   |
| 2022    | 26        | 1.96%   |
| 2023    | 10        | 0.75%   |
| 2004    | 9         | 0.68%   |
| 2003    | 7         | 0.53%   |
| 2024    | 6         | 0.45%   |
| 2002    | 2         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 717       | 53.95%  |
| Desktop        | 511       | 38.45%  |
| System on chip | 42        | 3.16%   |
| Mini pc        | 17        | 1.28%   |
| Convertible    | 16        | 1.2%    |
| All in one     | 14        | 1.05%   |
| Server         | 7         | 0.53%   |
| Tablet         | 5         | 0.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1261      | 94.74%  |
| Enabled  | 70        | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1329      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 283       | 21.07%  |
| 4.01-8.0    | 263       | 19.58%  |
| 16.01-24.0  | 210       | 15.64%  |
| 8.01-16.0   | 187       | 13.92%  |
| 1.01-2.0    | 147       | 10.95%  |
| 32.01-64.0  | 86        | 6.4%    |
| 2.01-3.0    | 67        | 4.99%   |
| 0.51-1.0    | 53        | 3.95%   |
| 64.01-256.0 | 28        | 2.08%   |
| 24.01-32.0  | 17        | 1.27%   |
| 0.01-0.5    | 2         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 527       | 37.54%  |
| 2.01-3.0    | 259       | 18.45%  |
| 0.51-1.0    | 201       | 14.32%  |
| 4.01-8.0    | 173       | 12.32%  |
| 3.01-4.0    | 143       | 10.19%  |
| 8.01-16.0   | 68        | 4.84%   |
| 16.01-24.0  | 13        | 0.93%   |
| 0.01-0.5    | 11        | 0.78%   |
| Unknown     | 4         | 0.28%   |
| 32.01-64.0  | 2         | 0.14%   |
| 24.01-32.0  | 2         | 0.14%   |
| 64.01-256.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 902       | 66.86%  |
| 2      | 292       | 21.65%  |
| 3      | 76        | 5.63%   |
| 4      | 35        | 2.59%   |
| 5      | 12        | 0.89%   |
| 0      | 12        | 0.89%   |
| 6      | 10        | 0.74%   |
| 9      | 3         | 0.22%   |
| 7      | 3         | 0.22%   |
| 10     | 2         | 0.15%   |
| 11     | 1         | 0.07%   |
| 8      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 673       | 50.49%  |
| No        | 660       | 49.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1203      | 90.18%  |
| No        | 131       | 9.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 991       | 74.34%  |
| No        | 342       | 25.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 748       | 55.78%  |
| Yes       | 593       | 44.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 227       | 17%     |
| Germany      | 130       | 9.74%   |
| Brazil       | 97        | 7.27%   |
| France       | 91        | 6.82%   |
| India        | 61        | 4.57%   |
| UK           | 57        | 4.27%   |
| Russia       | 57        | 4.27%   |
| Italy        | 50        | 3.75%   |
| Spain        | 46        | 3.45%   |
| Canada       | 32        | 2.4%    |
| Poland       | 27        | 2.02%   |
| Netherlands  | 25        | 1.87%   |
| Belgium      | 20        | 1.5%    |
| Turkey       | 19        | 1.42%   |
| Romania      | 16        | 1.2%    |
| Australia    | 16        | 1.2%    |
| Hungary      | 15        | 1.12%   |
| Ukraine      | 14        | 1.05%   |
| Mexico       | 14        | 1.05%   |
| Bulgaria     | 14        | 1.05%   |
| Argentina    | 14        | 1.05%   |
| Greece       | 13        | 0.97%   |
| Colombia     | 13        | 0.97%   |
| China        | 13        | 0.97%   |
| Portugal     | 11        | 0.82%   |
| Czechia      | 11        | 0.82%   |
| Switzerland  | 10        | 0.75%   |
| South Africa | 10        | 0.75%   |
| Japan        | 10        | 0.75%   |
| Indonesia    | 10        | 0.75%   |
| Denmark      | 10        | 0.75%   |
| Austria      | 10        | 0.75%   |
| Vietnam      | 9         | 0.67%   |
| Sweden       | 8         | 0.6%    |
| Slovakia     | 7         | 0.52%   |
| Philippines  | 6         | 0.45%   |
| New Zealand  | 6         | 0.45%   |
| Morocco      | 6         | 0.45%   |
| South Korea  | 5         | 0.37%   |
| Norway       | 5         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 21        | 1.52%   |
| Moscow            | 16        | 1.16%   |
| Sao Paulo         | 13        | 0.94%   |
| Paris             | 12        | 0.87%   |
| Rome              | 8         | 0.58%   |
| Rio de Janeiro    | 8         | 0.58%   |
| Hamburg           | 8         | 0.58%   |
| Bogotá           | 8         | 0.58%   |
| Barcelona         | 8         | 0.58%   |
| Athens            | 8         | 0.58%   |
| Amsterdam         | 8         | 0.58%   |
| Warsaw            | 7         | 0.51%   |
| Montreal          | 7         | 0.51%   |
| Milan             | 7         | 0.51%   |
| Madrid            | 7         | 0.51%   |
| Istanbul          | 7         | 0.51%   |
| Budapest          | 7         | 0.51%   |
| Bengaluru         | 7         | 0.51%   |
| Sydney            | 6         | 0.43%   |
| Pune              | 6         | 0.43%   |
| Munich            | 6         | 0.43%   |
| Hyderabad         | 6         | 0.43%   |
| Frankfurt am Main | 6         | 0.43%   |
| Brasília         | 6         | 0.43%   |
| Vienna            | 5         | 0.36%   |
| St Petersburg     | 5         | 0.36%   |
| Hanoi             | 5         | 0.36%   |
| Denver            | 5         | 0.36%   |
| Chicago           | 5         | 0.36%   |
| Buenos Aires      | 5         | 0.36%   |
| Yekaterinburg     | 4         | 0.29%   |
| Wuppertal         | 4         | 0.29%   |
| Viborg            | 4         | 0.29%   |
| Toronto           | 4         | 0.29%   |
| Surabaya          | 4         | 0.29%   |
| Stuttgart         | 4         | 0.29%   |
| Nizhniy Novgorod  | 4         | 0.29%   |
| New Delhi         | 4         | 0.29%   |
| Mumbai            | 4         | 0.29%   |
| Lviv              | 4         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 309       | 428    | 17.44%  |
| WDC                         | 306       | 414    | 17.27%  |
| Samsung Electronics         | 239       | 310    | 13.49%  |
| Toshiba                     | 159       | 183    | 8.97%   |
| Hitachi                     | 101       | 111    | 5.7%    |
| Kingston                    | 79        | 95     | 4.46%   |
| Unknown                     | 77        | 86     | 4.35%   |
| SanDisk                     | 69        | 94     | 3.89%   |
| Crucial                     | 50        | 61     | 2.82%   |
| HGST                        | 45        | 58     | 2.54%   |
| Intel                       | 31        | 36     | 1.75%   |
| Micron Technology           | 30        | 44     | 1.69%   |
| SK hynix                    | 19        | 19     | 1.07%   |
| Fujitsu                     | 17        | 17     | 0.96%   |
| A-DATA Technology           | 16        | 16     | 0.9%    |
| Maxtor                      | 15        | 16     | 0.85%   |
| PNY                         | 12        | 17     | 0.68%   |
| LITEON                      | 12        | 15     | 0.68%   |
| Intenso                     | 11        | 14     | 0.62%   |
| Patriot                     | 10        | 11     | 0.56%   |
| OCZ                         | 10        | 11     | 0.56%   |
| KIOXIA                      | 10        | 10     | 0.56%   |
| China                       | 10        | 10     | 0.56%   |
| Transcend                   | 9         | 9      | 0.51%   |
| Apple                       | 8         | 11     | 0.45%   |
| SPCC                        | 6         | 8      | 0.34%   |
| LITEONIT                    | 6         | 10     | 0.34%   |
| Corsair                     | 5         | 5      | 0.28%   |
| Unknown                     | 5         | 7      | 0.28%   |
| Verbatim                    | 4         | 5      | 0.23%   |
| Phison                      | 4         | 5      | 0.23%   |
| Micron/Crucial Technology   | 4         | 4      | 0.23%   |
| Lenovo                      | 4         | 4      | 0.23%   |
| Hewlett-Packard             | 4         | 5      | 0.23%   |
| Apacer                      | 4         | 4      | 0.23%   |
| XPG                         | 3         | 4      | 0.17%   |
| Team                        | 3         | 5      | 0.17%   |
| Lexar                       | 3         | 3      | 0.17%   |
| Kingston Technology Company | 3         | 3      | 0.17%   |
| KingSpec                    | 3         | 5      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 18        | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB     | 18        | 0.93%   |
| Seagate ST500DM002-1BD142 500GB    | 16        | 0.83%   |
| Kingston SA400S37240G 240GB SSD    | 15        | 0.78%   |
| Unknown MMC Card  128GB            | 14        | 0.73%   |
| Samsung SSD 850 EVO 250GB          | 14        | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB     | 13        | 0.67%   |
| Toshiba MQ01ABF050 500GB           | 11        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 0.57%   |
| HGST HTS545050A7E680 500GB         | 11        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD   | 10        | 0.52%   |
| Toshiba DT01ACA100 1TB             | 9         | 0.47%   |
| Samsung SSD 860 EVO 250GB          | 9         | 0.47%   |
| HGST HTS721010A9E630 1TB           | 9         | 0.47%   |
| Unknown MMC Card  64GB             | 8         | 0.41%   |
| Seagate ST500LT012-1DG142 500GB    | 8         | 0.41%   |
| Samsung NVMe SSD Drive 512GB       | 8         | 0.41%   |
| Toshiba MQ01ABD100 1TB             | 7         | 0.36%   |
| Samsung SSD 860 EVO 500GB          | 7         | 0.36%   |
| Kingston SA400S37480G 480GB SSD    | 7         | 0.36%   |
| Kingston SA400S37120G 120GB SSD    | 7         | 0.36%   |
| Crucial CT1000MX500SSD1 1TB        | 7         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB           | 6         | 0.31%   |
| WDC WD10EZEX-00BN5A0 1TB           | 6         | 0.31%   |
| Toshiba MQ01ACF050 500GB           | 6         | 0.31%   |
| Seagate ST380815AS 80GB            | 6         | 0.31%   |
| Seagate ST3320620AS 320GB          | 6         | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB     | 6         | 0.31%   |
| Seagate ST1000DM003-1SB102 1TB     | 6         | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB     | 6         | 0.31%   |
| Samsung SSD 850 EVO 500GB          | 6         | 0.31%   |
| Samsung SSD 840 EVO 250GB          | 6         | 0.31%   |
| Kingston SUV400S37240G 240GB SSD   | 6         | 0.31%   |
| Hitachi HTS545032B9A300 320GB      | 6         | 0.31%   |
| HGST HTS725050A7E630 500GB         | 6         | 0.31%   |
| Crucial CT240BX500SSD1 240GB       | 6         | 0.31%   |
| WDC WD5000AAKX-001CA0 500GB        | 5         | 0.26%   |
| WDC WD10EZEX-60WN4A0 1TB           | 5         | 0.26%   |
| Toshiba MQ01ABD075 752GB           | 5         | 0.26%   |
| Toshiba DT01ACA050 500GB           | 5         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 307       | 423    | 31.49%  |
| WDC                 | 275       | 377    | 28.21%  |
| Toshiba             | 128       | 146    | 13.13%  |
| Hitachi             | 101       | 111    | 10.36%  |
| Samsung Electronics | 59        | 70     | 6.05%   |
| HGST                | 45        | 58     | 4.62%   |
| Fujitsu             | 17        | 17     | 1.74%   |
| Maxtor              | 15        | 16     | 1.54%   |
| Apple               | 5         | 6      | 0.51%   |
| Unknown             | 4         | 3      | 0.41%   |
| Intenso             | 3         | 4      | 0.31%   |
| JMicron Technology  | 2         | 2      | 0.21%   |
| IBM/Hitachi         | 2         | 2      | 0.21%   |
| Hewlett-Packard     | 2         | 3      | 0.21%   |
| XrayDisk            | 1         | 1      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| USB                 | 1         | 2      | 0.1%    |
| StoreJet            | 1         | 1      | 0.1%    |
| STEC                | 1         | 1      | 0.1%    |
| SSK                 | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| LIO-ORG             | 1         | 1      | 0.1%    |
| Lenovo              | 1         | 1      | 0.1%    |
| IET                 | 1         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 106       | 146    | 23.14%  |
| Kingston            | 65        | 78     | 14.19%  |
| SanDisk             | 48        | 58     | 10.48%  |
| Crucial             | 44        | 55     | 9.61%   |
| Micron Technology   | 20        | 25     | 4.37%   |
| WDC                 | 16        | 17     | 3.49%   |
| Intel               | 16        | 18     | 3.49%   |
| PNY                 | 12        | 17     | 2.62%   |
| A-DATA Technology   | 12        | 12     | 2.62%   |
| Toshiba             | 11        | 13     | 2.4%    |
| OCZ                 | 10        | 11     | 2.18%   |
| LITEON              | 10        | 13     | 2.18%   |
| China               | 10        | 10     | 2.18%   |
| Patriot             | 9         | 10     | 1.97%   |
| Transcend           | 6         | 6      | 1.31%   |
| LITEONIT            | 6         | 10     | 1.31%   |
| Intenso             | 6         | 7      | 1.31%   |
| Verbatim            | 4         | 5      | 0.87%   |
| SPCC                | 4         | 5      | 0.87%   |
| SK hynix            | 4         | 4      | 0.87%   |
| Apacer              | 3         | 3      | 0.66%   |
| Team                | 2         | 4      | 0.44%   |
| Lexar               | 2         | 2      | 0.44%   |
| KingDian            | 2         | 2      | 0.44%   |
| Corsair             | 2         | 2      | 0.44%   |
| Apple               | 2         | 2      | 0.44%   |
| XrayDisk            | 1         | 1      | 0.22%   |
| Vaseky              | 1         | 1      | 0.22%   |
| Super Talent        | 1         | 1      | 0.22%   |
| SUNEAST             | 1         | 1      | 0.22%   |
| StoreJet            | 1         | 1      | 0.22%   |
| Smartbuy            | 1         | 1      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| SABRENT             | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| OCZ-REVODRIVE3      | 1         | 4      | 0.22%   |
| NGFF                | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| MidasForce          | 1         | 1      | 0.22%   |
| KYO                 | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 849       | 1250   | 53.46%  |
| SSD     | 402       | 566    | 25.31%  |
| NVMe    | 247       | 320    | 15.55%  |
| MMC     | 71        | 80     | 4.47%   |
| Unknown | 19        | 23     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1094      | 1776   | 74.88%  |
| NVMe | 246       | 318    | 16.84%  |
| MMC  | 71        | 80     | 4.86%   |
| SAS  | 50        | 65     | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 874       | 1182   | 65.52%  |
| 0.51-1.0   | 302       | 385    | 22.64%  |
| 1.01-2.0   | 80        | 117    | 6%      |
| 3.01-4.0   | 29        | 53     | 2.17%   |
| 2.01-3.0   | 28        | 41     | 2.1%    |
| 4.01-10.0  | 16        | 29     | 1.2%    |
| 10.01-20.0 | 5         | 9      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 440       | 32.31%  |
| 251-500        | 326       | 23.94%  |
| 501-1000       | 170       | 12.48%  |
| 51-100         | 140       | 10.28%  |
| 1001-2000      | 89        | 6.53%   |
| 21-50          | 70        | 5.14%   |
| More than 3000 | 54        | 3.96%   |
| 1-20           | 36        | 2.64%   |
| 2001-3000      | 34        | 2.5%    |
| Unknown        | 3         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 550       | 39.74%  |
| 21-50          | 195       | 14.09%  |
| 101-250        | 190       | 13.73%  |
| 51-100         | 173       | 12.5%   |
| 251-500        | 111       | 8.02%   |
| 501-1000       | 84        | 6.07%   |
| 1001-2000      | 39        | 2.82%   |
| More than 3000 | 24        | 1.73%   |
| 2001-3000      | 15        | 1.08%   |
| Unknown        | 3         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 3      | 2.63%   |
| Seagate ST3320620AS 320GB           | 2         | 2      | 2.63%   |
| HGST HTS545050A7E680 500GB          | 2         | 2      | 2.63%   |
| WDC WD5001AALS-00LWTA0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 1         | 1      | 1.32%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 1.32%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1         | 1      | 1.32%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1         | 1      | 1.32%   |
| WDC WD20EARS-22MVWB0 2TB            | 1         | 1      | 1.32%   |
| WDC WD20EARS-00MVWB0 2TB            | 1         | 1      | 1.32%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1         | 1      | 1.32%   |
| WDC WD1600JS-00NCB1 160GB           | 1         | 1      | 1.32%   |
| WDC WD10PURX-64D85Y0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10EADX-22TDHB0 1TB            | 1         | 1      | 1.32%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD100M 1TB             | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.32%   |
| Toshiba MK6475GSX 640GB             | 1         | 1      | 1.32%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 1.32%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.32%   |
| Toshiba MK3252GSX 320GB             | 1         | 2      | 1.32%   |
| Super Talent FTM28N325H 128GB SSD   | 1         | 1      | 1.32%   |
| Seagate ST9250315AS 250GB           | 1         | 5      | 1.32%   |
| Seagate ST9120822AS 120GB           | 1         | 1      | 1.32%   |
| Seagate ST500DM002-1SB10A 500GB     | 1         | 1      | 1.32%   |
| Seagate ST3750330NS 752GB           | 1         | 1      | 1.32%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 1.32%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 1.32%   |
| Seagate ST32000542AS 2TB            | 1         | 1      | 1.32%   |
| Seagate ST3160815AS 160GB           | 1         | 1      | 1.32%   |
| Seagate ST31000524NS 1TB            | 1         | 1      | 1.32%   |
| Seagate ST3000DM001-1CH166 3TB      | 1         | 2      | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 1.32%   |
| Seagate ST1000LM 035-1RK172 1TB     | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 26     | 27.03%  |
| WDC                 | 13        | 14     | 17.57%  |
| Toshiba             | 9         | 10     | 12.16%  |
| Samsung Electronics | 6         | 6      | 8.11%   |
| Micron Technology   | 4         | 4      | 5.41%   |
| Hitachi             | 4         | 4      | 5.41%   |
| HGST                | 4         | 5      | 5.41%   |
| Kingston            | 3         | 4      | 4.05%   |
| Crucial             | 3         | 3      | 4.05%   |
| China               | 2         | 2      | 2.7%    |
| Apple               | 2         | 2      | 2.7%    |
| Super Talent        | 1         | 1      | 1.35%   |
| Patriot             | 1         | 1      | 1.35%   |
| LITEON              | 1         | 1      | 1.35%   |
| A-DATA Technology   | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 26     | 36.36%  |
| WDC                 | 13        | 14     | 23.64%  |
| Toshiba             | 9         | 10     | 16.36%  |
| Samsung Electronics | 4         | 4      | 7.27%   |
| Hitachi             | 4         | 4      | 7.27%   |
| HGST                | 4         | 5      | 7.27%   |
| Apple               | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 64     | 72.86%  |
| SSD  | 19        | 20     | 27.14%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 946       | 1525   | 67.91%  |
| Works    | 378       | 629    | 27.14%  |
| Malfunc  | 68        | 84     | 4.88%   |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 965       | 62.83%  |
| AMD                              | 169       | 11%     |
| Samsung Electronics              | 85        | 5.53%   |
| Nvidia                           | 45        | 2.93%   |
| SanDisk                          | 38        | 2.47%   |
| JMicron Technology               | 23        | 1.5%    |
| Toshiba America Info Systems     | 21        | 1.37%   |
| Marvell Technology Group         | 20        | 1.3%    |
| ASMedia Technology               | 18        | 1.17%   |
| Kingston Technology Company      | 17        | 1.11%   |
| VIA Technologies                 | 15        | 0.98%   |
| SK hynix                         | 15        | 0.98%   |
| Silicon Integrated Systems [SiS] | 12        | 0.78%   |
| Silicon Motion                   | 11        | 0.72%   |
| Micron Technology                | 11        | 0.72%   |
| KIOXIA                           | 11        | 0.72%   |
| Phison Electronics               | 10        | 0.65%   |
| Micron/Crucial Technology        | 8         | 0.52%   |
| ADATA Technology                 | 8         | 0.52%   |
| Silicon Image                    | 6         | 0.39%   |
| Realtek Semiconductor            | 4         | 0.26%   |
| Promise Technology               | 3         | 0.2%    |
| LSI Logic / Symbios Logic        | 3         | 0.2%    |
| Shenzhen Longsys Electronics     | 2         | 0.13%   |
| Lite-On Technology               | 2         | 0.13%   |
| Lenovo                           | 2         | 0.13%   |
| Apple                            | 2         | 0.13%   |
| Union Memory (Shenzhen)          | 1         | 0.07%   |
| ULi Electronics                  | 1         | 0.07%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Seagate Technology               | 1         | 0.07%   |
| OCZ Technology Group             | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Broadcom / LSI                   | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 93        | 4.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 74        | 3.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 63        | 3.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 55        | 2.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 52        | 2.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 44        | 2.34%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 35        | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 34        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 34        | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 33        | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 33        | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 27        | 1.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 26        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 26        | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 26        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 25        | 1.33%   |
| Intel SATA Controller [RAID Mode]                                              | 24        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 24        | 1.28%   |
| Nvidia MCP61 SATA Controller                                                   | 23        | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 1.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 21        | 1.12%   |
| Nvidia MCP61 IDE                                                               | 20        | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 20        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 19        | 1.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                             | 15        | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 15        | 0.8%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 14        | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 0.74%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 14        | 0.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14        | 0.74%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 14        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 856       | 53.4%   |
| IDE  | 399       | 24.89%  |
| NVMe | 246       | 15.35%  |
| RAID | 94        | 5.86%   |
| SAS  | 5         | 0.31%   |
| SCSI | 3         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1061      | 79.83%  |
| AMD          | 223       | 16.78%  |
| ARM          | 30        | 2.26%   |
| Unknown      | 11        | 0.83%   |
| CentaurHauls | 3         | 0.23%   |
| Qualcomm     | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ARM Processor                               | 30        | 2.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 16        | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 15        | 1.13%   |
| Intel Atom CPU N270 @ 1.60GHz               | 14        | 1.05%   |
| Intel Pentium 4 CPU 3.00GHz                 | 13        | 0.98%   |
|                                             | 11        | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 10        | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 10        | 0.75%   |
| Intel Pentium M processor 1.73GHz           | 8         | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8         | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8         | 0.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 8         | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 8         | 0.6%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 7         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 7         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 7         | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.53%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 7         | 0.53%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 7         | 0.53%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 7         | 0.53%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 7         | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 7         | 0.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 7         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 6         | 0.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 6         | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6         | 0.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.45%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 6         | 0.45%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 6         | 0.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 0.45%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 0.45%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6         | 0.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 5         | 0.38%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 5         | 0.38%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 5         | 0.38%   |
| Intel Pentium D CPU 2.80GHz                 | 5         | 0.38%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 5         | 0.38%   |
| Intel Pentium 4 CPU 3.20GHz                 | 5         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 214       | 16.1%   |
| Intel Core i7                  | 201       | 15.12%  |
| Intel Core 2 Duo               | 105       | 7.9%    |
| Intel Core i3                  | 103       | 7.75%   |
| Other                          | 94        | 7.07%   |
| Intel Celeron                  | 56        | 4.21%   |
| Intel Atom                     | 53        | 3.99%   |
| Intel Pentium                  | 43        | 3.24%   |
| Intel Pentium Dual-Core        | 36        | 2.71%   |
| AMD Ryzen 5                    | 34        | 2.56%   |
| Intel Xeon                     | 33        | 2.48%   |
| Intel Genuine                  | 30        | 2.26%   |
| Intel Pentium 4                | 27        | 2.03%   |
| AMD Ryzen 7                    | 20        | 1.5%    |
| Intel Core 2                   | 19        | 1.43%   |
| AMD FX                         | 18        | 1.35%   |
| Intel Pentium Dual             | 17        | 1.28%   |
| Intel Pentium M                | 14        | 1.05%   |
| Intel Celeron M                | 13        | 0.98%   |
| AMD Athlon 64 X2               | 12        | 0.9%    |
| Intel Core 2 Quad              | 10        | 0.75%   |
| AMD Phenom II X4               | 10        | 0.75%   |
| AMD A4                         | 10        | 0.75%   |
| Intel Pentium D                | 9         | 0.68%   |
| Intel Core i9                  | 9         | 0.68%   |
| AMD Ryzen 9                    | 9         | 0.68%   |
| AMD Athlon II X2               | 9         | 0.68%   |
| AMD A10                        | 9         | 0.68%   |
| AMD Ryzen 3                    | 7         | 0.53%   |
| AMD A8                         | 7         | 0.53%   |
| AMD A6                         | 7         | 0.53%   |
| Intel Core Duo                 | 5         | 0.38%   |
| AMD Athlon Dual Core           | 5         | 0.38%   |
| Intel Pentium Silver           | 4         | 0.3%    |
| AMD Sempron                    | 4         | 0.3%    |
| AMD Phenom                     | 4         | 0.3%    |
| CentaurHauls VIA C7            | 3         | 0.23%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.23%   |
| AMD Ryzen 7 PRO                | 3         | 0.23%   |
| AMD Phenom II X6               | 3         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 634       | 47.67%  |
| 4       | 376       | 28.27%  |
| 1       | 125       | 9.4%    |
| 6       | 94        | 7.07%   |
| 8       | 45        | 3.38%   |
| 3       | 11        | 0.83%   |
| 16      | 10        | 0.75%   |
| 12      | 10        | 0.75%   |
| 14      | 8         | 0.6%    |
| 10      | 7         | 0.53%   |
| Unknown | 5         | 0.38%   |
| 24      | 3         | 0.23%   |
| 44      | 1         | 0.08%   |
| 32      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1300      | 97.82%  |
| 2       | 16        | 1.2%    |
| 3       | 6         | 0.45%   |
| Unknown | 5         | 0.38%   |
| 4       | 2         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 687       | 51.62%  |
| 1       | 639       | 48.01%  |
| Unknown | 5         | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1189      | 89.47%  |
| 32-bit         | 101       | 7.6%    |
| Unknown        | 35        | 2.63%   |
| 64-bit         | 4         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 297       | 22.02%  |
| 0x1067a    | 83        | 6.15%   |
| 0x206a7    | 68        | 5.04%   |
| 0x306a9    | 64        | 4.74%   |
| 0x306c3    | 50        | 3.71%   |
| 0x6fd      | 41        | 3.04%   |
| 0x906ea    | 35        | 2.59%   |
| 0x806e9    | 33        | 2.45%   |
| 0x506e3    | 32        | 2.37%   |
| 0x20655    | 25        | 1.85%   |
| 0x10676    | 25        | 1.85%   |
| 0x806ea    | 24        | 1.78%   |
| 0x6e8      | 22        | 1.63%   |
| 0x106c2    | 20        | 1.48%   |
| 0x40651    | 19        | 1.41%   |
| 0x106ca    | 19        | 1.41%   |
| 0x906e9    | 18        | 1.33%   |
| 0x806ec    | 18        | 1.33%   |
| 0x406e3    | 18        | 1.33%   |
| 0x306d4    | 18        | 1.33%   |
| 0x010000c8 | 17        | 1.26%   |
| 0x6fb      | 16        | 1.19%   |
| 0x6d8      | 16        | 1.19%   |
| 0x30678    | 15        | 1.11%   |
| 0x6f6      | 14        | 1.04%   |
| 0x6ec      | 14        | 1.04%   |
| 0x20652    | 13        | 0.96%   |
| 0x06000852 | 13        | 0.96%   |
| 0x406c4    | 11        | 0.82%   |
| 0x06001119 | 10        | 0.74%   |
| 0x6f2      | 9         | 0.67%   |
| 0x406c3    | 9         | 0.67%   |
| 0xa0652    | 8         | 0.59%   |
| 0x806c1    | 8         | 0.59%   |
| 0x106e5    | 8         | 0.59%   |
| 0x0700010f | 8         | 0.59%   |
| 0xf41      | 7         | 0.52%   |
| 0x206d7    | 7         | 0.52%   |
| 0x10661    | 7         | 0.52%   |
| 0x08108109 | 7         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 176       | 13.22%  |
| Penryn            | 119       | 8.94%   |
| Core              | 92        | 6.91%   |
| SandyBridge       | 88        | 6.61%   |
| Haswell           | 81        | 6.09%   |
| IvyBridge         | 78        | 5.86%   |
| Unknown           | 71        | 5.33%   |
| Skylake           | 66        | 4.96%   |
| P6                | 55        | 4.13%   |
| Westmere          | 47        | 3.53%   |
| Bonnell           | 43        | 3.23%   |
| Silvermont        | 42        | 3.16%   |
| K10               | 41        | 3.08%   |
| NetBurst          | 39        | 2.93%   |
| Broadwell         | 29        | 2.18%   |
| Piledriver        | 27        | 2.03%   |
| K8 Hammer         | 25        | 1.88%   |
| Zen 2             | 23        | 1.73%   |
| CometLake         | 23        | 1.73%   |
| Alderlake Hybrid  | 18        | 1.35%   |
| Zen+              | 17        | 1.28%   |
| Zen               | 16        | 1.2%    |
| TigerLake         | 14        | 1.05%   |
| Nehalem           | 12        | 0.9%    |
| Icelake           | 10        | 0.75%   |
| Excavator         | 10        | 0.75%   |
| Zen 3             | 8         | 0.6%    |
| Jaguar            | 8         | 0.6%    |
| Goldmont plus     | 8         | 0.6%    |
| Bobcat            | 8         | 0.6%    |
| Puma              | 7         | 0.53%   |
| Steamroller       | 6         | 0.45%   |
| K8 & K10 hybrid   | 6         | 0.45%   |
| Goldmont          | 6         | 0.45%   |
| K6                | 4         | 0.3%    |
| K10 Llano         | 4         | 0.3%    |
| Tremont           | 1         | 0.08%   |
| Meteorlake Hybrid | 1         | 0.08%   |
| Gracemont         | 1         | 0.08%   |
| Bulldozer         | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 803       | 54.55%  |
| Nvidia                           | 362       | 24.59%  |
| AMD                              | 278       | 18.89%  |
| Silicon Integrated Systems [SiS] | 11        | 0.75%   |
| VIA Technologies                 | 8         | 0.54%   |
| ASPEED Technology                | 6         | 0.41%   |
| Silicon Motion                   | 2         | 0.14%   |
| Matrox Electronics Systems       | 2         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 63        | 4.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 46        | 2.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 45        | 2.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 41        | 2.61%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 34        | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 2.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 28        | 1.78%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 28        | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 23        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 23        | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22        | 1.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 1.4%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 21        | 1.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 21        | 1.34%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 1.21%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 19        | 1.21%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 1.15%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 17        | 1.08%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 17        | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.02%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 15        | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 0.76%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 12        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 0.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 11        | 0.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 10        | 0.64%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 10        | 0.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.64%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 9         | 0.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.57%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 9         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 630       | 47.3%   |
| 1 x Nvidia         | 227       | 17.04%  |
| 1 x AMD            | 216       | 16.22%  |
| Intel + Nvidia     | 122       | 9.16%   |
| Other              | 43        | 3.23%   |
| Intel + AMD        | 30        | 2.25%   |
| 2 x AMD            | 22        | 1.65%   |
| 1 x SiS            | 11        | 0.83%   |
| 1 x VIA            | 8         | 0.6%    |
| AMD + Nvidia       | 7         | 0.53%   |
| 2 x Nvidia         | 5         | 0.38%   |
| 1 x ASPEED         | 3         | 0.23%   |
| 1 x Silicon Motion | 2         | 0.15%   |
| 1 x Matrox         | 2         | 0.15%   |
| AMD + ASPEED       | 2         | 0.15%   |
| 2 x Intel          | 1         | 0.08%   |
| Nvidia + ASPEED    | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1045      | 78.57%  |
| Proprietary | 153       | 11.5%   |
| Unknown     | 132       | 9.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 448       | 33.23%  |
| 0.01-0.5   | 321       | 23.81%  |
| 1.01-2.0   | 288       | 21.36%  |
| 3.01-4.0   | 145       | 10.76%  |
| 0.51-1.0   | 90        | 6.68%   |
| 7.01-8.0   | 26        | 1.93%   |
| 5.01-6.0   | 14        | 1.04%   |
| 2.01-3.0   | 8         | 0.59%   |
| 8.01-16.0  | 7         | 0.52%   |
| 4.01-5.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 178       | 13.19%  |
| AU Optronics            | 144       | 10.67%  |
| LG Display              | 106       | 7.85%   |
| Chimei Innolux          | 81        | 6%      |
| Dell                    | 78        | 5.78%   |
| BOE                     | 78        | 5.78%   |
| Goldstar                | 61        | 4.52%   |
| Acer                    | 54        | 4%      |
| Hewlett-Packard         | 45        | 3.33%   |
| Lenovo                  | 36        | 2.67%   |
| AOC                     | 35        | 2.59%   |
| Ancor Communications    | 35        | 2.59%   |
| Philips                 | 32        | 2.37%   |
| Sharp                   | 31        | 2.3%    |
| BenQ                    | 30        | 2.22%   |
| Chi Mei Optoelectronics | 29        | 2.15%   |
| Apple                   | 29        | 2.15%   |
| LG Philips              | 18        | 1.33%   |
| LG Electronics          | 15        | 1.11%   |
| HannStar                | 15        | 1.11%   |
| Iiyama                  | 14        | 1.04%   |
| Unknown                 | 13        | 0.96%   |
| Sony                    | 10        | 0.74%   |
| ViewSonic               | 9         | 0.67%   |
| InfoVision              | 8         | 0.59%   |
| InnoLux Display         | 7         | 0.52%   |
| ASUSTek Computer        | 7         | 0.52%   |
| Vestel Elektronik       | 6         | 0.44%   |
| Quanta Display          | 6         | 0.44%   |
| Fujitsu Siemens         | 6         | 0.44%   |
| Seiko/Epson             | 5         | 0.37%   |
| NEC Computers           | 5         | 0.37%   |
| Medion                  | 5         | 0.37%   |
| IBM                     | 5         | 0.37%   |
| CPT                     | 5         | 0.37%   |
| Toshiba                 | 4         | 0.3%    |
| PANDA                   | 4         | 0.3%    |
| Panasonic               | 4         | 0.3%    |
| Eizo                    | 4         | 0.3%    |
| KTC                     | 3         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 0.65%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch     | 6         | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.36%   |
| Seiko/Epson LCD Monitor 1366x768                                         | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SyncMaster                               | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.29%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.29%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                       | 4         | 0.29%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 3         | 0.22%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch        | 3         | 0.22%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor U28E570                                  | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 3         | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.22%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 3         | 0.22%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                    | 3         | 0.22%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                    | 3         | 0.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO0209 1024x600 195x113mm 8.9-inch  | 3         | 0.22%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch         | 3         | 0.22%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch   | 3         | 0.22%   |
| Unknown                                                                  | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 425       | 32.27%  |
| 1366x768 (WXGA)    | 256       | 19.44%  |
| 3840x2160 (4K)     | 67        | 5.09%   |
| 1280x800 (WXGA)    | 66        | 5.01%   |
| 1280x1024 (SXGA)   | 61        | 4.63%   |
| 1680x1050 (WSXGA+) | 56        | 4.25%   |
| 1600x900 (HD+)     | 56        | 4.25%   |
| 2560x1440 (QHD)    | 51        | 3.87%   |
| Unknown            | 50        | 3.8%    |
| 1440x900 (WXGA+)   | 45        | 3.42%   |
| 1024x600           | 30        | 2.28%   |
| 1920x1200 (WUXGA)  | 26        | 1.97%   |
| 1024x768 (XGA)     | 21        | 1.59%   |
| 1360x768           | 18        | 1.37%   |
| 3440x1440          | 9         | 0.68%   |
| 2560x1080          | 9         | 0.68%   |
| 2560x1600          | 7         | 0.53%   |
| 3200x1800 (QHD+)   | 6         | 0.46%   |
| 2880x1800          | 6         | 0.46%   |
| 1280x720 (HD)      | 6         | 0.46%   |
| 2160x1440          | 5         | 0.38%   |
| 1920x540           | 5         | 0.38%   |
| 3840x1080          | 4         | 0.3%    |
| 1600x1200          | 4         | 0.3%    |
| 3840x2400          | 2         | 0.15%   |
| 3840x1200          | 2         | 0.15%   |
| 3456x2160          | 2         | 0.15%   |
| 3072x1920          | 2         | 0.15%   |
| 2288x1287          | 2         | 0.15%   |
| 1680x945           | 2         | 0.15%   |
| 1280x960           | 2         | 0.15%   |
| 7120x1080          | 1         | 0.08%   |
| 3840x1303          | 1         | 0.08%   |
| 3360x1080          | 1         | 0.08%   |
| 3286x1080          | 1         | 0.08%   |
| 3200x1200          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2732x768           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 323       | 24.03%  |
| 14      | 112       | 8.33%   |
| Unknown | 104       | 7.74%   |
| 13      | 100       | 7.44%   |
| 27      | 79        | 5.88%   |
| 24      | 78        | 5.8%    |
| 17      | 73        | 5.43%   |
| 23      | 65        | 4.84%   |
| 21      | 62        | 4.61%   |
| 19      | 51        | 3.79%   |
| 20      | 37        | 2.75%   |
| 10      | 35        | 2.6%    |
| 18      | 30        | 2.23%   |
| 22      | 28        | 2.08%   |
| 31      | 25        | 1.86%   |
| 12      | 17        | 1.26%   |
| 34      | 14        | 1.04%   |
| 11      | 14        | 1.04%   |
| 16      | 13        | 0.97%   |
| 32      | 12        | 0.89%   |
| 84      | 9         | 0.67%   |
| 72      | 7         | 0.52%   |
| 54      | 7         | 0.52%   |
| 40      | 7         | 0.52%   |
| 25      | 7         | 0.52%   |
| 52      | 3         | 0.22%   |
| 28      | 3         | 0.22%   |
| 26      | 3         | 0.22%   |
| 8       | 3         | 0.22%   |
| 142     | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 42      | 2         | 0.15%   |
| 30      | 2         | 0.15%   |
| 7       | 2         | 0.15%   |
| 86      | 1         | 0.07%   |
| 70      | 1         | 0.07%   |
| 64      | 1         | 0.07%   |
| 60      | 1         | 0.07%   |
| 59      | 1         | 0.07%   |
| 50      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 501       | 37.67%  |
| 501-600        | 211       | 15.86%  |
| 401-500        | 179       | 13.46%  |
| 201-300        | 126       | 9.47%   |
| Unknown        | 104       | 7.82%   |
| 351-400        | 87        | 6.54%   |
| 601-700        | 40        | 3.01%   |
| 701-800        | 26        | 1.95%   |
| 1001-1500      | 18        | 1.35%   |
| 1501-2000      | 17        | 1.28%   |
| 801-900        | 10        | 0.75%   |
| 101-200        | 5         | 0.38%   |
| 901-1000       | 4         | 0.3%    |
| More than 2000 | 2         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 818       | 65.97%  |
| 16/10   | 197       | 15.89%  |
| Unknown | 93        | 7.5%    |
| 5/4     | 58        | 4.68%   |
| 4/3     | 37        | 2.98%   |
| 21/9    | 16        | 1.29%   |
| 3/2     | 13        | 1.05%   |
| 32/9    | 4         | 0.32%   |
| 1.00    | 2         | 0.16%   |
| 6/5     | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 322       | 24.07%  |
| 201-250        | 199       | 14.87%  |
| 81-90          | 161       | 12.03%  |
| Unknown        | 104       | 7.77%   |
| 151-200        | 101       | 7.55%   |
| 301-350        | 82        | 6.13%   |
| 141-150        | 56        | 4.19%   |
| 351-500        | 53        | 3.96%   |
| 71-80          | 45        | 3.36%   |
| 41-50          | 35        | 2.62%   |
| More than 1000 | 34        | 2.54%   |
| 121-130        | 33        | 2.47%   |
| 251-300        | 29        | 2.17%   |
| 501-1000       | 17        | 1.27%   |
| 61-70          | 15        | 1.12%   |
| 51-60          | 14        | 1.05%   |
| 131-140        | 13        | 0.97%   |
| 111-120        | 12        | 0.9%    |
| 91-100         | 8         | 0.6%    |
| 1-40           | 5         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 484       | 36.89%  |
| 101-120       | 360       | 27.44%  |
| 121-160       | 241       | 18.37%  |
| Unknown       | 104       | 7.93%   |
| 161-240       | 59        | 4.5%    |
| 1-50          | 35        | 2.67%   |
| More than 240 | 29        | 2.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1097      | 81.62%  |
| 2     | 149       | 11.09%  |
| 0     | 73        | 5.43%   |
| 3     | 20        | 1.49%   |
| 4     | 4         | 0.3%    |
| 6     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 686       | 33.17%  |
| Intel                             | 544       | 26.31%  |
| Qualcomm Atheros                  | 263       | 12.72%  |
| Broadcom                          | 144       | 6.96%   |
| Marvell Technology Group          | 57        | 2.76%   |
| Broadcom Limited                  | 47        | 2.27%   |
| Nvidia                            | 36        | 1.74%   |
| Ralink Technology                 | 32        | 1.55%   |
| Ralink                            | 32        | 1.55%   |
| TP-Link                           | 22        | 1.06%   |
| MediaTek                          | 19        | 0.92%   |
| Shenzhen Goodix Technology        | 13        | 0.63%   |
| NetGear                           | 13        | 0.63%   |
| VIA Technologies                  | 12        | 0.58%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.58%   |
| Samsung Electronics               | 10        | 0.48%   |
| ASIX Electronics                  | 10        | 0.48%   |
| Xiaomi                            | 7         | 0.34%   |
| Qualcomm Atheros Communications   | 7         | 0.34%   |
| Ericsson Business Mobile Networks | 7         | 0.34%   |
| D-Link System                     | 6         | 0.29%   |
| D-Link                            | 6         | 0.29%   |
| JMicron Technology                | 5         | 0.24%   |
| Qualcomm                          | 4         | 0.19%   |
| Huawei Technologies               | 4         | 0.19%   |
| DisplayLink                       | 4         | 0.19%   |
| 3Com                              | 4         | 0.19%   |
| Sierra Wireless                   | 3         | 0.15%   |
| Dell                              | 3         | 0.15%   |
| ASUSTek Computer                  | 3         | 0.15%   |
| Aquantia                          | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.1%    |
| Sitecom Europe                    | 2         | 0.1%    |
| Motorola PCS                      | 2         | 0.1%    |
| Motorola                          | 2         | 0.1%    |
| Microchip Technology              | 2         | 0.1%    |
| Linksys                           | 2         | 0.1%    |
| Lenovo                            | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| Fibocom                           | 2         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 427       | 17.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 117       | 4.88%   |
| Intel Wireless 8265 / 8275                                              | 43        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 41        | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 37        | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 33        | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 28        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 25        | 1.04%   |
| Intel Wi-Fi 6 AX200                                                     | 21        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 0.88%   |
| Intel Wireless 8260                                                     | 20        | 0.83%   |
| Intel Wireless 7265                                                     | 20        | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 0.79%   |
| Nvidia MCP61 Ethernet                                                   | 19        | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 0.63%   |
| Intel Centrino Advanced-N 6200                                          | 15        | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 14        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                                | 14        | 0.58%   |
| Shenzhen Goodix Fingerprint Reader                                      | 13        | 0.54%   |
| Intel I211 Gigabit Network Connection                                   | 13        | 0.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.5%    |
| Intel Wireless 3165                                                     | 12        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                | 12        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 12        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                            | 11        | 0.46%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.46%   |
| Intel Wireless 7260                                                     | 11        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 383       | 36.97%  |
| Qualcomm Atheros                      | 206       | 19.88%  |
| Realtek Semiconductor                 | 177       | 17.08%  |
| Broadcom                              | 88        | 8.49%   |
| Ralink Technology                     | 32        | 3.09%   |
| Ralink                                | 32        | 3.09%   |
| Broadcom Limited                      | 27        | 2.61%   |
| TP-Link                               | 21        | 2.03%   |
| MediaTek                              | 16        | 1.54%   |
| NetGear                               | 13        | 1.25%   |
| Qualcomm Atheros Communications       | 7         | 0.68%   |
| D-Link                                | 6         | 0.58%   |
| Sierra Wireless                       | 3         | 0.29%   |
| ASUSTek Computer                      | 3         | 0.29%   |
| Sitecom Europe                        | 2         | 0.19%   |
| Marvell Technology Group              | 2         | 0.19%   |
| Linksys                               | 2         | 0.19%   |
| Fibocom                               | 2         | 0.19%   |
| Edimax Technology                     | 2         | 0.19%   |
| Dell                                  | 2         | 0.19%   |
| D-Link System                         | 2         | 0.19%   |
| AVM                                   | 2         | 0.19%   |
| ZyDAS                                 | 1         | 0.1%    |
| PLANEX                                | 1         | 0.1%    |
| Microsoft                             | 1         | 0.1%    |
| Mercucys                              | 1         | 0.1%    |
| Intersil                              | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 43        | 4.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 41        | 3.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 33        | 3.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 2.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                     | 21        | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 2.02%   |
| Intel Wireless 8260                                                     | 20        | 1.92%   |
| Intel Wireless 7265                                                     | 20        | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 1.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 1.44%   |
| Intel Centrino Advanced-N 6200                                          | 15        | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.25%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 1.15%   |
| Intel Wireless 3165                                                     | 12        | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.15%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 12        | 1.15%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 1.06%   |
| Intel Wireless 7260                                                     | 11        | 1.06%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.96%   |
| Realtek 802.11ac NIC                                                    | 9         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 9         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 0.87%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 9         | 0.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 8         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 615       | 48.08%  |
| Intel                            | 304       | 23.77%  |
| Qualcomm Atheros                 | 80        | 6.25%   |
| Broadcom                         | 69        | 5.39%   |
| Marvell Technology Group         | 55        | 4.3%    |
| Nvidia                           | 36        | 2.81%   |
| Broadcom Limited                 | 20        | 1.56%   |
| VIA Technologies                 | 12        | 0.94%   |
| Silicon Integrated Systems [SiS] | 12        | 0.94%   |
| Samsung Electronics              | 10        | 0.78%   |
| ASIX Electronics                 | 10        | 0.78%   |
| Xiaomi                           | 7         | 0.55%   |
| JMicron Technology               | 5         | 0.39%   |
| Qualcomm                         | 4         | 0.31%   |
| DisplayLink                      | 4         | 0.31%   |
| D-Link System                    | 4         | 0.31%   |
| 3Com                             | 4         | 0.31%   |
| MediaTek                         | 3         | 0.23%   |
| Huawei Technologies              | 3         | 0.23%   |
| Aquantia                         | 3         | 0.23%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.16%   |
| Motorola PCS                     | 2         | 0.16%   |
| Lenovo                           | 2         | 0.16%   |
| ICS Advent                       | 2         | 0.16%   |
| vivo                             | 1         | 0.08%   |
| TP-Link                          | 1         | 0.08%   |
| Standard Microsystems [SMC]      | 1         | 0.08%   |
| Spreadtrum Communications        | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| Insyde Software                  | 1         | 0.08%   |
| HMD Global                       | 1         | 0.08%   |
| Davicom Semiconductor            | 1         | 0.08%   |
| Attansic Technology              | 1         | 0.08%   |
| Archos                           | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 427       | 32.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 117       | 9%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 37        | 2.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 28        | 2.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 25        | 1.92%   |
| Nvidia MCP61 Ethernet                                                  | 19        | 1.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 14        | 1.08%   |
| Intel 82567LM Gigabit Network Connection                               | 14        | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 1%      |
| Intel 82577LM Gigabit Network Connection                               | 12        | 0.92%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 11        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                   | 11        | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 10        | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 10        | 0.77%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 10        | 0.77%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 9         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 8         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.62%   |
| Intel I210 Gigabit Network Connection                                  | 8         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 8         | 0.62%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 8         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 7         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 7         | 0.54%   |
| Intel PRO/100 VE Network Connection                                    | 7         | 0.54%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 7         | 0.54%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 7         | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 6         | 0.46%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.46%   |
| Intel Ethernet Connection I219-V                                       | 6         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1200      | 53.52%  |
| WiFi     | 986       | 43.98%  |
| Modem    | 54        | 2.41%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 772       | 55.78%  |
| Ethernet | 612       | 44.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 744       | 55.81%  |
| 1     | 538       | 40.36%  |
| 0     | 26        | 1.95%   |
| 3     | 19        | 1.43%   |
| 4     | 3         | 0.23%   |
| 5     | 2         | 0.15%   |
| 7     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1172      | 86.81%  |
| Yes  | 178       | 13.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 247       | 40.89%  |
| Realtek Semiconductor           | 50        | 8.28%   |
| Qualcomm Atheros Communications | 50        | 8.28%   |
| Cambridge Silicon Radio         | 49        | 8.11%   |
| Broadcom                        | 45        | 7.45%   |
| IMC Networks                    | 30        | 4.97%   |
| Apple                           | 27        | 4.47%   |
| Foxconn / Hon Hai               | 18        | 2.98%   |
| Lite-On Technology              | 13        | 2.15%   |
| Hewlett-Packard                 | 13        | 2.15%   |
| Ralink                          | 9         | 1.49%   |
| MediaTek                        | 8         | 1.32%   |
| Dell                            | 8         | 1.32%   |
| ASUSTek Computer                | 7         | 1.16%   |
| Toshiba                         | 6         | 0.99%   |
| TP-Link                         | 3         | 0.5%    |
| Taiyo Yuden                     | 3         | 0.5%    |
| Alps Electric                   | 3         | 0.5%    |
| Realtek                         | 2         | 0.33%   |
| Foxconn International           | 2         | 0.33%   |
| Smart Modular Technologies      | 1         | 0.17%   |
| Qcom                            | 1         | 0.17%   |
| Micro Star International        | 1         | 0.17%   |
| Mercucys                        | 1         | 0.17%   |
| Integrated System Solution      | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |
| Dynex                           | 1         | 0.17%   |
| D-Link System                   | 1         | 0.17%   |
| Conwise Technology              | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |
| Askey Computer                  | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 109       | 18.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 49        | 8.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 37        | 6.13%   |
| Intel AX201 Bluetooth                               | 35        | 5.79%   |
| Realtek Bluetooth Radio                             | 30        | 4.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 25        | 4.14%   |
| Intel AX200 Bluetooth                               | 21        | 3.48%   |
| Intel Bluetooth Device                              | 15        | 2.48%   |
| IMC Networks Bluetooth Radio                        | 14        | 2.32%   |
| Apple Bluetooth HCI                                 | 13        | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 1.99%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.49%   |
| Apple Bluetooth Host Controller                     | 9         | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 1.32%   |
| MediaTek Wireless_Device                            | 8         | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.16%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.16%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.16%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 6         | 0.99%   |
| IMC Networks Bluetooth Device                       | 6         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.83%   |
| Intel AX210 Bluetooth                               | 5         | 0.83%   |
| IMC Networks Wireless_Device                        | 5         | 0.83%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 5         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.66%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.66%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.66%   |
| TP-Link TP-T@- UB500 Adapter                        | 3         | 0.5%    |
| Toshiba Bluetooth Device                            | 3         | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 3         | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.5%    |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 3         | 0.5%    |
| Dell Wireless 355 Bluetooth                         | 3         | 0.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 997       | 60.98%  |
| AMD                              | 245       | 14.98%  |
| Nvidia                           | 235       | 14.37%  |
| C-Media Electronics              | 19        | 1.16%   |
| VIA Technologies                 | 17        | 1.04%   |
| Silicon Integrated Systems [SiS] | 12        | 0.73%   |
| Logitech                         | 11        | 0.67%   |
| GN Netcom                        | 10        | 0.61%   |
| Creative Labs                    | 7         | 0.43%   |
| Realtek Semiconductor            | 5         | 0.31%   |
| Generalplus Technology           | 5         | 0.31%   |
| Plantronics                      | 4         | 0.24%   |
| JMTek                            | 4         | 0.24%   |
| Texas Instruments                | 3         | 0.18%   |
| Ensoniq                          | 3         | 0.18%   |
| Creative Technology              | 3         | 0.18%   |
| ASUSTek Computer                 | 3         | 0.18%   |
| Yamaha                           | 2         | 0.12%   |
| Walmart                          | 2         | 0.12%   |
| Syntek                           | 2         | 0.12%   |
| SteelSeries ApS                  | 2         | 0.12%   |
| Sennheiser Communications        | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| KORG                             | 2         | 0.12%   |
| Kingston Technology              | 2         | 0.12%   |
| DSEA A/S                         | 2         | 0.12%   |
| Corsair                          | 2         | 0.12%   |
| Blue Microphones                 | 2         | 0.12%   |
| BEHRINGER International          | 2         | 0.12%   |
| Apple                            | 2         | 0.12%   |
| Unknown                          | 2         | 0.12%   |
| ZOOM                             | 1         | 0.06%   |
| ULi Electronics                  | 1         | 0.06%   |
| TerraTec Electronic              | 1         | 0.06%   |
| Tenx Technology                  | 1         | 0.06%   |
| SAVITECH                         | 1         | 0.06%   |
| Samson Technologies              | 1         | 0.06%   |
| Razer USA                        | 1         | 0.06%   |
| Pioneer DJ                       | 1         | 0.06%   |
| Novra/IDC/Wegener                | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 133       | 7.1%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 91        | 4.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 85        | 4.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 81        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 74        | 3.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 53        | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 51        | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 50        | 2.67%   |
| AMD Ryzen HD Audio Controller                                                                     | 47        | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 44        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41        | 2.19%   |
| AMD FCH Azalia Controller                                                                         | 40        | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 38        | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 37        | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 25        | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 1.28%   |
| Nvidia High Definition Audio Controller                                                           | 23        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 1.17%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 1.17%   |
| Nvidia MCP61 High Definition Audio                                                                | 20        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 0.96%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 18        | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 17        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 17        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 16        | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 16        | 0.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 15        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 0.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 15        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 14        | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 13        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 129       | 19.43%  |
| SK hynix                     | 120       | 18.07%  |
| Kingston                     | 94        | 14.16%  |
| Unknown                      | 79        | 11.9%   |
| Micron Technology            | 65        | 9.79%   |
| Crucial                      | 30        | 4.52%   |
| Corsair                      | 27        | 4.07%   |
| G.Skill                      | 21        | 3.16%   |
| Ramaxel Technology           | 16        | 2.41%   |
| Smart                        | 11        | 1.66%   |
| A-DATA Technology            | 10        | 1.51%   |
| Nanya Technology             | 9         | 1.36%   |
| Elpida                       | 8         | 1.2%    |
| Transcend                    | 7         | 1.05%   |
| Patriot                      | 5         | 0.75%   |
| Unknown                      | 4         | 0.6%    |
| Unknown (ABCD)               | 3         | 0.45%   |
| Team                         | 2         | 0.3%    |
| Silicon Power                | 2         | 0.3%    |
| Goldkey                      | 2         | 0.3%    |
| Walton Chaintech             | 1         | 0.15%   |
| Unknown (89F7)               | 1         | 0.15%   |
| Unknown (0x7C00000000000000) | 1         | 0.15%   |
| Unknown (0x0080)             | 1         | 0.15%   |
| Unknown (07FB)               | 1         | 0.15%   |
| Unifosa                      | 1         | 0.15%   |
| Timetec                      | 1         | 0.15%   |
| SHARETRONIC                  | 1         | 0.15%   |
| Qumo                         | 1         | 0.15%   |
| PUSKILL                      | 1         | 0.15%   |
| PNY                          | 1         | 0.15%   |
| Netlist                      | 1         | 0.15%   |
| High Bridge                  | 1         | 0.15%   |
| Hewlett-Packard              | 1         | 0.15%   |
| Exceleram                    | 1         | 0.15%   |
| ASint Technology             | 1         | 0.15%   |
| Apacer                       | 1         | 0.15%   |
| Ankowall                     | 1         | 0.15%   |
| Acer                         | 1         | 0.15%   |
| A Force                      | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 1.26%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 5         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.7%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s              | 5         | 0.7%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 4         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 4         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.56%   |
| Unknown                                                          | 4         | 0.56%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 3         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.42%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.42%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 3         | 0.42%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.42%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 0.42%   |
| Samsung RAM M471A1K43BB0-CPB 8GiB SODIMM DDR4 2133MT/s           | 3         | 0.42%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.42%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.42%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 3         | 0.42%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.42%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.42%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.42%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 3         | 0.42%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 3         | 0.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s              | 3         | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 2         | 0.28%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 2         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 224       | 38.82%  |
| DDR3    | 209       | 36.22%  |
| DDR2    | 41        | 7.11%   |
| Unknown | 21        | 3.64%   |
| LPDDR3  | 19        | 3.29%   |
| SDRAM   | 16        | 2.77%   |
| DDR5    | 16        | 2.77%   |
| LPDDR4  | 15        | 2.6%    |
| LPDDR5  | 8         | 1.39%   |
| DDR     | 6         | 1.04%   |
| DRAM    | 2         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 325       | 55.94%  |
| DIMM         | 206       | 35.46%  |
| Row Of Chips | 46        | 7.92%   |
| Chip         | 3         | 0.52%   |
| FB-DIMM      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 233       | 36.64%  |
| 4096  | 160       | 25.16%  |
| 16384 | 103       | 16.19%  |
| 2048  | 83        | 13.05%  |
| 1024  | 30        | 4.72%   |
| 32768 | 20        | 3.14%   |
| 512   | 5         | 0.79%   |
| 65536 | 1         | 0.16%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 135       | 21.36%  |
| 2667    | 99        | 15.66%  |
| 3200    | 77        | 12.18%  |
| 1333    | 51        | 8.07%   |
| 2133    | 46        | 7.28%   |
| 2400    | 32        | 5.06%   |
| 667     | 22        | 3.48%   |
| Unknown | 21        | 3.32%   |
| 1334    | 18        | 2.85%   |
| 800     | 17        | 2.69%   |
| 6400    | 8         | 1.27%   |
| 4800    | 8         | 1.27%   |
| 1867    | 8         | 1.27%   |
| 1066    | 8         | 1.27%   |
| 1067    | 7         | 1.11%   |
| 5600    | 6         | 0.95%   |
| 3600    | 5         | 0.79%   |
| 533     | 5         | 0.79%   |
| 4267    | 4         | 0.63%   |
| 3266    | 4         | 0.63%   |
| 3000    | 4         | 0.63%   |
| 2666    | 4         | 0.63%   |
| 1866    | 4         | 0.63%   |
| 8400    | 3         | 0.47%   |
| 4199    | 3         | 0.47%   |
| 3733    | 3         | 0.47%   |
| 3400    | 3         | 0.47%   |
| 400     | 3         | 0.47%   |
| 4266    | 2         | 0.32%   |
| 4000    | 2         | 0.32%   |
| 2200    | 2         | 0.32%   |
| 2048    | 2         | 0.32%   |
| 2000    | 2         | 0.32%   |
| 1800    | 2         | 0.32%   |
| 8533    | 1         | 0.16%   |
| 6200    | 1         | 0.16%   |
| 6000    | 1         | 0.16%   |
| 3933    | 1         | 0.16%   |
| 3604    | 1         | 0.16%   |
| 3100    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 24        | 48.98%  |
| Canon                    | 9         | 18.37%  |
| Samsung Electronics      | 5         | 10.2%   |
| Brother Industries       | 3         | 6.12%   |
| Seiko Epson              | 2         | 4.08%   |
| Zhuhai Poskey Technology | 1         | 2.04%   |
| Xerox                    | 1         | 2.04%   |
| Ricoh                    | 1         | 2.04%   |
| QinHeng Electronics      | 1         | 2.04%   |
| Lexmark International    | 1         | 2.04%   |
| Kyocera                  | 1         | 2.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP OfficeJet 3830 series             | 2         | 4%      |
| HP LaserJet 1018                     | 2         | 4%      |
| Zhuhai Poskey Printer                | 1         | 2%      |
| Xerox Phaser 6130N                   | 1         | 2%      |
| Seiko Epson L375 Series              | 1         | 2%      |
| Seiko Epson L365 Series              | 1         | 2%      |
| Samsung SCX-472x Series              | 1         | 2%      |
| Samsung SCX-3200 Series              | 1         | 2%      |
| Samsung ML-1640 Series Laser Printer | 1         | 2%      |
| Samsung M267x 287x Series            | 1         | 2%      |
| Samsung CLX-3180 Series              | 1         | 2%      |
| Ricoh SP 150SUw                      | 1         | 2%      |
| QinHeng CH340S                       | 1         | 2%      |
| Lexmark International CS727de        | 1         | 2%      |
| Kyocera FS-1020D Printer             | 1         | 2%      |
| HP Officejet 4500 G510g-m            | 1         | 2%      |
| HP LaserJet P2055 series             | 1         | 2%      |
| HP LaserJet M14-M17                  | 1         | 2%      |
| HP LaserJet 1020                     | 1         | 2%      |
| HP HP LaserJet M101-M106             | 1         | 2%      |
| HP EWS UPD                           | 1         | 2%      |
| HP ENVY Photo 7800 series            | 1         | 2%      |
| HP ENVY Photo 6200 series            | 1         | 2%      |
| HP ENVY 4500 series                  | 1         | 2%      |
| HP Deskjet F4500 series              | 1         | 2%      |
| HP DeskJet F2100 Printer series      | 1         | 2%      |
| HP DeskJet 930c                      | 1         | 2%      |
| HP DeskJet 5650c                     | 1         | 2%      |
| HP DeskJet 2700 series               | 1         | 2%      |
| HP DeskJet 2600 series               | 1         | 2%      |
| HP Deskjet 2540 series               | 1         | 2%      |
| HP DeskJet 2130 series               | 1         | 2%      |
| HP Deskjet 1050 J410                 | 1         | 2%      |
| HP ColorLaserJet M253-M254           | 1         | 2%      |
| HP Color LaserJet 2605               | 1         | 2%      |
| Canon TR8500 series                  | 1         | 2%      |
| Canon PIXMA MX920 Series             | 1         | 2%      |
| Canon PIXMA MX720 Series             | 1         | 2%      |
| Canon PIXMA MX370 Series             | 1         | 2%      |
| Canon PIXMA MP250                    | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 37.5%   |
| Hewlett-Packard | 2         | 25%     |
| Seiko Epson     | 1         | 12.5%   |
| Mustek Systems  | 1         | 12.5%   |
| AGFA-Gevaert NV | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 2         | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 12.5%   |
| Mustek Systems ScanExpress 1200 CU Plus       | 1         | 12.5%   |
| HP ScanJet 5200c                              | 1         | 12.5%   |
| HP ScanJet 3570c                              | 1         | 12.5%   |
| Canon CanoScan LiDE 220                       | 1         | 12.5%   |
| AGFA-Gevaert NV Snapscan e40                  | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 138       | 19.63%  |
| Microdia                               | 69        | 9.82%   |
| Realtek Semiconductor                  | 67        | 9.53%   |
| IMC Networks                           | 46        | 6.54%   |
| Bison Electronics                      | 44        | 6.26%   |
| Suyin                                  | 40        | 5.69%   |
| Logitech                               | 38        | 5.41%   |
| Sunplus Innovation Technology          | 33        | 4.69%   |
| Apple                                  | 29        | 4.13%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.27%   |
| Quanta                                 | 20        | 2.84%   |
| Lite-On Technology                     | 16        | 2.28%   |
| Syntek                                 | 15        | 2.13%   |
| Lenovo                                 | 11        | 1.56%   |
| Samsung Electronics                    | 10        | 1.42%   |
| Silicon Motion                         | 9         | 1.28%   |
| Microsoft                              | 9         | 1.28%   |
| Alcor Micro                            | 7         | 1%      |
| Importek                               | 6         | 0.85%   |
| Acer                                   | 6         | 0.85%   |
| Sonix Technology                       | 5         | 0.71%   |
| Luxvisions Innotech Limited            | 5         | 0.71%   |
| Z-Star Microelectronics                | 4         | 0.57%   |
| SunplusIT                              | 4         | 0.57%   |
| GEMBIRD                                | 4         | 0.57%   |
| Ricoh                                  | 3         | 0.43%   |
| Intel                                  | 3         | 0.43%   |
| Generalplus Technology                 | 3         | 0.43%   |
| Primax Electronics                     | 2         | 0.28%   |
| Philips (or NXP)                       | 2         | 0.28%   |
| Huawei Technologies                    | 2         | 0.28%   |
| Hewlett-Packard                        | 2         | 0.28%   |
| eMPIA Technology                       | 2         | 0.28%   |
| eMeet                                  | 2         | 0.28%   |
| DigiTech                               | 2         | 0.28%   |
| Cubeternet                             | 2         | 0.28%   |
| ALi                                    | 2         | 0.28%   |
| YGTek                                  | 1         | 0.14%   |
| USB3.0 HD Audio Capture                | 1         | 0.14%   |
| USB Camera CS                          | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 26        | 3.69%   |
| Realtek Integrated_Webcam_HD             | 25        | 3.55%   |
| Chicony Integrated Camera                | 13        | 1.84%   |
| Logitech Webcam C270                     | 12        | 1.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 11        | 1.56%   |
| Sunplus Integrated_Webcam_HD             | 10        | 1.42%   |
| Chicony HP HD Camera                     | 10        | 1.42%   |
| Samsung Galaxy series, misc. (MTP mode)  | 9         | 1.28%   |
| IMC Networks Integrated Camera           | 9         | 1.28%   |
| Syntek Integrated Camera                 | 8         | 1.13%   |
| Bison Lenovo Integrated Webcam           | 8         | 1.13%   |
| Apple Built-in iSight                    | 8         | 1.13%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 7         | 0.99%   |
| Lite-On Integrated Camera                | 7         | 0.99%   |
| Lenovo Integrated Webcam [R5U877]        | 6         | 0.85%   |
| Chicony Lenovo EasyCamera                | 6         | 0.85%   |
| Chicony Camera                           | 6         | 0.85%   |
| Suyin HP Truevision HD                   | 5         | 0.71%   |
| Sunplus Asus Webcam                      | 5         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam             | 5         | 0.71%   |
| Realtek Integrated Webcam HD             | 5         | 0.71%   |
| Realtek Integrated Webcam                | 5         | 0.71%   |
| Microsoft LifeCam HD-3000                | 5         | 0.71%   |
| Microdia Webcam Vitade AF                | 5         | 0.71%   |
| IMC Networks USB2.0 HD UVC WebCam        | 5         | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam            | 5         | 0.71%   |
| Chicony USB 2.0 Camera                   | 5         | 0.71%   |
| Bison Integrated Camera                  | 5         | 0.71%   |
| Sunplus HD WebCam                        | 4         | 0.57%   |
| Microdia Sonix USB 2.0 Camera            | 4         | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD     | 4         | 0.57%   |
| Logitech HD Webcam C615                  | 4         | 0.57%   |
| Logitech HD Pro Webcam C920              | 4         | 0.57%   |
| Lite-On HP HD Camera                     | 4         | 0.57%   |
| IMC Networks USB 2.0 Camera              | 4         | 0.57%   |
| IMC Networks Lenovo EasyCamera           | 4         | 0.57%   |
| IMC Networks EasyCamera                  | 4         | 0.57%   |
| Chicony TOSHIBA Web Camera - HD          | 4         | 0.57%   |
| Chicony HP Wide Vision HD Camera         | 4         | 0.57%   |
| Chicony HP TrueVision HD                 | 4         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 59        | 42.14%  |
| Synaptics                          | 27        | 19.29%  |
| AuthenTec                          | 17        | 12.14%  |
| Shenzhen Goodix Technology         | 12        | 8.57%   |
| Upek                               | 10        | 7.14%   |
| STMicroelectronics                 | 5         | 3.57%   |
| LighTuning Technology              | 4         | 2.86%   |
| Elan Microelectronics              | 4         | 2.86%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.71%   |
| DigitalPersona                     | 1         | 0.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 8.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 6.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 4.29%   |
| AuthenTec AES2810                                                          | 6         | 4.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 3.57%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 3.57%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 2.86%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.86%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.14%   |
| Validity Sensors VFS491                                                    | 3         | 2.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.14%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 2.14%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.14%   |
| Synaptics UWP WBDI                                                         | 3         | 2.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.14%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.14%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.14%   |
| AuthenTec AES1600                                                          | 3         | 2.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.43%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.43%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.71%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.71%   |
| Synaptics WBDI                                                             | 1         | 0.71%   |
| Synaptics TouchPad                                                         | 1         | 0.71%   |
| Synaptics  WBDI                                                            | 1         | 0.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.71%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.71%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 24        | 46.15%  |
| O2 Micro         | 12        | 23.08%  |
| Alcor Micro      | 9         | 17.31%  |
| SCM Microsystems | 3         | 5.77%   |
| Lenovo           | 3         | 5.77%   |
| Yubico.com       | 1         | 1.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 16.98%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 15.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 13.21%  |
| Broadcom 5880                                                                | 6         | 11.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 9.43%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 5         | 9.43%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.66%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.89%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 1.89%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.89%   |
| SCM Microsystems Elektra331-USB SmartCard Reader                             | 1         | 1.89%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 1.89%   |
| Broadcom 58200                                                               | 1         | 1.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 888       | 66.27%  |
| 1     | 349       | 26.04%  |
| 2     | 77        | 5.75%   |
| 3     | 13        | 0.97%   |
| 4     | 8         | 0.6%    |
| 5     | 3         | 0.22%   |
| 7     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 188       | 31.86%  |
| Fingerprint reader       | 137       | 23.22%  |
| Net/wireless             | 67        | 11.36%  |
| Chipcard                 | 50        | 8.47%   |
| Communication controller | 42        | 7.12%   |
| Modem                    | 20        | 3.39%   |
| Multimedia controller    | 19        | 3.22%   |
| Bluetooth                | 14        | 2.37%   |
| Sound                    | 13        | 2.2%    |
| Storage                  | 12        | 2.03%   |
| Camera                   | 9         | 1.53%   |
| Unassigned class         | 7         | 1.19%   |
| Card reader              | 3         | 0.51%   |
| Net/ethernet             | 2         | 0.34%   |
| Flash memory             | 2         | 0.34%   |
| Dvb card                 | 2         | 0.34%   |
| Tv card                  | 1         | 0.17%   |
| Storage/raid             | 1         | 0.17%   |
| Storage/nvme             | 1         | 0.17%   |

