OpenMandriva 4.2 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.2/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.2/Notebook/README.md).

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

Total: 4991

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | H81M-D2V                    | Desktop     | [aadc1a0c13](https://linux-hardware.org/?probe=aadc1a0c13) | Jan 06, 2025 |
| Dell          | Latitude E4310              | Notebook    | [68eec2c60e](https://linux-hardware.org/?probe=68eec2c60e) | Jan 04, 2025 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [69679c9a35](https://linux-hardware.org/?probe=69679c9a35) | Dec 31, 2024 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [d18eb4cf0d](https://linux-hardware.org/?probe=d18eb4cf0d) | Dec 31, 2024 |
| HP            | ProBook 6560b               | Notebook    | [c2ae1365c2](https://linux-hardware.org/?probe=c2ae1365c2) | Dec 31, 2024 |
| ASRock        | G31M-S                      | Desktop     | [983b928868](https://linux-hardware.org/?probe=983b928868) | Dec 23, 2024 |
| HP            | 304Ah                       | Desktop     | [9c4499ff99](https://linux-hardware.org/?probe=9c4499ff99) | Nov 30, 2024 |
| Panasonic     | CF-W8FWDAJS                 | Notebook    | [b07a63717b](https://linux-hardware.org/?probe=b07a63717b) | Nov 28, 2024 |
| Toshiba       | Satellite L300              | Notebook    | [5f14b73409](https://linux-hardware.org/?probe=5f14b73409) | Nov 27, 2024 |
| Panasonic     | CFXZ6-1                     | Tablet      | [0adce1d7c2](https://linux-hardware.org/?probe=0adce1d7c2) | Nov 27, 2024 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [14cef10c67](https://linux-hardware.org/?probe=14cef10c67) | Nov 22, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [781f667e83](https://linux-hardware.org/?probe=781f667e83) | Nov 13, 2024 |
| Pegatron      | Spring Peak                 | Notebook    | [a3687da9ac](https://linux-hardware.org/?probe=a3687da9ac) | Nov 10, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [170e0ba845](https://linux-hardware.org/?probe=170e0ba845) | Oct 31, 2024 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [c96eaa6d8d](https://linux-hardware.org/?probe=c96eaa6d8d) | Oct 31, 2024 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [1ad2d26ee7](https://linux-hardware.org/?probe=1ad2d26ee7) | Oct 30, 2024 |
| HP            | ProBook 6475b               | Notebook    | [afad291037](https://linux-hardware.org/?probe=afad291037) | Oct 23, 2024 |
| ASUSTek       | N751JK                      | Notebook    | [00ba90079e](https://linux-hardware.org/?probe=00ba90079e) | Oct 18, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [ecd1036622](https://linux-hardware.org/?probe=ecd1036622) | Oct 01, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2a065d3b6e](https://linux-hardware.org/?probe=2a065d3b6e) | Sep 27, 2024 |
| Dell          | 0XHYJF A00                  | All in one  | [3c594c0335](https://linux-hardware.org/?probe=3c594c0335) | Sep 25, 2024 |
| Lenovo        | ThinkPad T430 2347H2U       | Notebook    | [f708e6c732](https://linux-hardware.org/?probe=f708e6c732) | Sep 23, 2024 |
| Dell          | Latitude E6410              | Notebook    | [8ce3baea7d](https://linux-hardware.org/?probe=8ce3baea7d) | Sep 12, 2024 |
| Intel         | H61                         | Desktop     | [26ad2a6fdf](https://linux-hardware.org/?probe=26ad2a6fdf) | Sep 10, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [7c0778ad12](https://linux-hardware.org/?probe=7c0778ad12) | Sep 05, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [00fa1b948c](https://linux-hardware.org/?probe=00fa1b948c) | Sep 04, 2024 |
| Gigabyte      | B75-D3V                     | Desktop     | [8287219a10](https://linux-hardware.org/?probe=8287219a10) | Aug 23, 2024 |
| Samsung       | N100SP                      | Notebook    | [5b740218ab](https://linux-hardware.org/?probe=5b740218ab) | Aug 22, 2024 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [c6abb7cd5f](https://linux-hardware.org/?probe=c6abb7cd5f) | Aug 21, 2024 |
| Acer          | Aspire A315-31              | Notebook    | [6222616358](https://linux-hardware.org/?probe=6222616358) | Aug 11, 2024 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [0f9529c85f](https://linux-hardware.org/?probe=0f9529c85f) | Aug 06, 2024 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7825be94bd](https://linux-hardware.org/?probe=7825be94bd) | Aug 02, 2024 |
| Dell          | Studio 1537                 | Notebook    | [a912e97b90](https://linux-hardware.org/?probe=a912e97b90) | Jul 23, 2024 |
| MSI           | H410M-A PRO                 | Desktop     | [bdfd7784ad](https://linux-hardware.org/?probe=bdfd7784ad) | Jul 22, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [4118b16aa8](https://linux-hardware.org/?probe=4118b16aa8) | Jul 20, 2024 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [6b11963a37](https://linux-hardware.org/?probe=6b11963a37) | Jul 18, 2024 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [e057c66153](https://linux-hardware.org/?probe=e057c66153) | Jul 15, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [bc079fea91](https://linux-hardware.org/?probe=bc079fea91) | Jul 05, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [9313e32d5f](https://linux-hardware.org/?probe=9313e32d5f) | Jul 05, 2024 |
| MSI           | A78M-E45                    | Desktop     | [1a99381c4e](https://linux-hardware.org/?probe=1a99381c4e) | Jul 05, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fc04d131f0](https://linux-hardware.org/?probe=fc04d131f0) | Jun 30, 2024 |
| HP            | 1850                        | Desktop     | [b09fbce140](https://linux-hardware.org/?probe=b09fbce140) | Jun 29, 2024 |
| Gigabyte      | H410M S2H V2                | Desktop     | [bc3d7aa23d](https://linux-hardware.org/?probe=bc3d7aa23d) | Jun 16, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [569af375ef](https://linux-hardware.org/?probe=569af375ef) | Jun 05, 2024 |
| Dell          | 0H19HD A05                  | Server      | [9613d7043b](https://linux-hardware.org/?probe=9613d7043b) | Jun 04, 2024 |
| Intel         | DH67CF AAG10215-201         | Desktop     | [56c76e67fc](https://linux-hardware.org/?probe=56c76e67fc) | Jun 02, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [f8379977a9](https://linux-hardware.org/?probe=f8379977a9) | May 27, 2024 |
| Shuttle       | XS35V3                      | Desktop     | [85715a2083](https://linux-hardware.org/?probe=85715a2083) | May 24, 2024 |
| Acer          | Aspire F5-571               | Notebook    | [e448ae2f62](https://linux-hardware.org/?probe=e448ae2f62) | May 11, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [76e6f087bb](https://linux-hardware.org/?probe=76e6f087bb) | May 08, 2024 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [30a913526e](https://linux-hardware.org/?probe=30a913526e) | May 07, 2024 |
| ASUSTek       | M4A78T-E                    | Desktop     | [2cee8d14ab](https://linux-hardware.org/?probe=2cee8d14ab) | May 06, 2024 |
| ASUSTek       | N53SN                       | Notebook    | [4c0db81fd7](https://linux-hardware.org/?probe=4c0db81fd7) | Apr 28, 2024 |
| Acer          | Aspire ES1-533              | Notebook    | [c4059b2efa](https://linux-hardware.org/?probe=c4059b2efa) | Apr 14, 2024 |
| Dell          | Studio XPS 1340             | Notebook    | [cac8add4c8](https://linux-hardware.org/?probe=cac8add4c8) | Apr 13, 2024 |
| Packard Be... | 1.XX                        | Desktop     | [2f25beb1a1](https://linux-hardware.org/?probe=2f25beb1a1) | Apr 12, 2024 |
| ASRock        | G31M-S                      | Desktop     | [d9694d3f33](https://linux-hardware.org/?probe=d9694d3f33) | Apr 12, 2024 |
| Shuttle       | X50V6                       | Notebook    | [c6b8ac2413](https://linux-hardware.org/?probe=c6b8ac2413) | Apr 12, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [bc0f74721a](https://linux-hardware.org/?probe=bc0f74721a) | Apr 06, 2024 |
| Biostar       | A960D+V2                    | Desktop     | [1b995511d1](https://linux-hardware.org/?probe=1b995511d1) | Apr 06, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [bddda9964b](https://linux-hardware.org/?probe=bddda9964b) | Apr 03, 2024 |
| Philco        | 14H                         | Notebook    | [93e4cd1668](https://linux-hardware.org/?probe=93e4cd1668) | Apr 02, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [d9f5951310](https://linux-hardware.org/?probe=d9f5951310) | Mar 29, 2024 |
| Dell          | 0478VN A00                  | Desktop     | [7300a27a93](https://linux-hardware.org/?probe=7300a27a93) | Mar 29, 2024 |
| Dell          | 0RF705                      | Desktop     | [0af34bb0be](https://linux-hardware.org/?probe=0af34bb0be) | Mar 29, 2024 |
| Dell          | 0T10XW A01                  | Desktop     | [64d0600046](https://linux-hardware.org/?probe=64d0600046) | Mar 26, 2024 |
| Gateway       | NE56R                       | Notebook    | [4e5c0a6186](https://linux-hardware.org/?probe=4e5c0a6186) | Mar 18, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e631f0ddf7](https://linux-hardware.org/?probe=e631f0ddf7) | Mar 17, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [cd9270ccb4](https://linux-hardware.org/?probe=cd9270ccb4) | Mar 14, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [8ff31d6bc3](https://linux-hardware.org/?probe=8ff31d6bc3) | Mar 14, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [67978c3e25](https://linux-hardware.org/?probe=67978c3e25) | Mar 10, 2024 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [2835f6c70b](https://linux-hardware.org/?probe=2835f6c70b) | Mar 04, 2024 |
| Acer          | Aspire A515-54G             | Notebook    | [4a2773a633](https://linux-hardware.org/?probe=4a2773a633) | Feb 17, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [d367c2a560](https://linux-hardware.org/?probe=d367c2a560) | Feb 11, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [7bb33cf1e5](https://linux-hardware.org/?probe=7bb33cf1e5) | Feb 11, 2024 |
| ECS           | Iris8                       | Desktop     | [6fc3d3a721](https://linux-hardware.org/?probe=6fc3d3a721) | Feb 11, 2024 |
| Acer          | Aspire 6930G                | Notebook    | [f721e58007](https://linux-hardware.org/?probe=f721e58007) | Feb 10, 2024 |
| HP            | Pavilion dv9500             | Notebook    | [4745fa66f1](https://linux-hardware.org/?probe=4745fa66f1) | Feb 10, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [b708422791](https://linux-hardware.org/?probe=b708422791) | Feb 09, 2024 |
| Lenovo        | U41-70 80JV                 | Notebook    | [343e04ef36](https://linux-hardware.org/?probe=343e04ef36) | Feb 07, 2024 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [45a5318a64](https://linux-hardware.org/?probe=45a5318a64) | Jan 31, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9dab8601c1](https://linux-hardware.org/?probe=9dab8601c1) | Jan 29, 2024 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9c1f52e62f](https://linux-hardware.org/?probe=9c1f52e62f) | Jan 29, 2024 |
| Intel         | NUC5CPYB H61145-412         | Mini pc     | [920618f3ab](https://linux-hardware.org/?probe=920618f3ab) | Jan 27, 2024 |
| ECS           | Iris8                       | Desktop     | [91dd8156df](https://linux-hardware.org/?probe=91dd8156df) | Jan 24, 2024 |
| Acer          | Aspire A315-31              | Notebook    | [22135f150d](https://linux-hardware.org/?probe=22135f150d) | Jan 12, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5edf7a7923](https://linux-hardware.org/?probe=5edf7a7923) | Jan 11, 2024 |
| Acer          | Aspire E5-571               | Notebook    | [a9f2a0569a](https://linux-hardware.org/?probe=a9f2a0569a) | Jan 09, 2024 |
| HP            | ENVY Notebook               | Notebook    | [8a2c65e297](https://linux-hardware.org/?probe=8a2c65e297) | Jan 05, 2024 |
| Acer          | Aspire XC-330               | Desktop     | [1b2d301d07](https://linux-hardware.org/?probe=1b2d301d07) | Dec 29, 2023 |
| Acer          | Aspire XC-704               | Desktop     | [37410da8b1](https://linux-hardware.org/?probe=37410da8b1) | Dec 29, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [544ae58a40](https://linux-hardware.org/?probe=544ae58a40) | Dec 27, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f72b5c344b](https://linux-hardware.org/?probe=f72b5c344b) | Dec 25, 2023 |
| ASUSTek       | X550EA                      | Notebook    | [a874ac5799](https://linux-hardware.org/?probe=a874ac5799) | Dec 18, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e21d372813](https://linux-hardware.org/?probe=e21d372813) | Dec 13, 2023 |
| Dell          | Latitude E6320              | Notebook    | [dbacdcadba](https://linux-hardware.org/?probe=dbacdcadba) | Dec 12, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [0c5f882efd](https://linux-hardware.org/?probe=0c5f882efd) | Dec 10, 2023 |
| Acer          | Aspire 7730G                | Notebook    | [c98f96bcc1](https://linux-hardware.org/?probe=c98f96bcc1) | Dec 07, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [26ab67528e](https://linux-hardware.org/?probe=26ab67528e) | Dec 06, 2023 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [73890cb8c3](https://linux-hardware.org/?probe=73890cb8c3) | Dec 05, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [53e38cd006](https://linux-hardware.org/?probe=53e38cd006) | Dec 02, 2023 |
| Lenovo        | Unknown                     | Notebook    | [0324aeaf06](https://linux-hardware.org/?probe=0324aeaf06) | Nov 28, 2023 |
| Dell          | Vostro 15 5501              | Notebook    | [ebb962a4ff](https://linux-hardware.org/?probe=ebb962a4ff) | Nov 21, 2023 |
| Dell          | Latitude E5440              | Notebook    | [467d68239e](https://linux-hardware.org/?probe=467d68239e) | Nov 20, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [76cc38fcb0](https://linux-hardware.org/?probe=76cc38fcb0) | Nov 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [ffdc6b121c](https://linux-hardware.org/?probe=ffdc6b121c) | Nov 17, 2023 |
| Gigabyte      | B460M D3H                   | Desktop     | [45ff3557a5](https://linux-hardware.org/?probe=45ff3557a5) | Nov 11, 2023 |
| HP            | 2B36                        | Desktop     | [be86be4b09](https://linux-hardware.org/?probe=be86be4b09) | Nov 07, 2023 |
| Biostar       | B250MHC                     | Desktop     | [528c04a30a](https://linux-hardware.org/?probe=528c04a30a) | Nov 02, 2023 |
| AMI           | Intel                       | Desktop     | [c4587092bf](https://linux-hardware.org/?probe=c4587092bf) | Nov 01, 2023 |
| Samsung       | 370E4K                      | Notebook    | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [364be0dfae](https://linux-hardware.org/?probe=364be0dfae) | Oct 24, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [3df6a3e3e4](https://linux-hardware.org/?probe=3df6a3e3e4) | Oct 23, 2023 |
| Sony          | VGN-FZ21M                   | Notebook    | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [2a39f005cb](https://linux-hardware.org/?probe=2a39f005cb) | Oct 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [6edb73b1b7](https://linux-hardware.org/?probe=6edb73b1b7) | Oct 11, 2023 |
| HP            | Compaq Presario C768        | Notebook    | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [61b27d4d00](https://linux-hardware.org/?probe=61b27d4d00) | Oct 01, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [9c1b258088](https://linux-hardware.org/?probe=9c1b258088) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6bce0e41d9](https://linux-hardware.org/?probe=6bce0e41d9) | Sep 28, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [8913bbd459](https://linux-hardware.org/?probe=8913bbd459) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [9c9070da5f](https://linux-hardware.org/?probe=9c9070da5f) | Sep 26, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | Desktop     | [16c22d9ead](https://linux-hardware.org/?probe=16c22d9ead) | Sep 25, 2023 |
| Dell          | Latitude E7440              | Notebook    | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| HP            | Compaq 615                  | Notebook    | [f2f7659e5b](https://linux-hardware.org/?probe=f2f7659e5b) | Sep 15, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [218489cc3f](https://linux-hardware.org/?probe=218489cc3f) | Sep 09, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [4c136b6049](https://linux-hardware.org/?probe=4c136b6049) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [9bacefd984](https://linux-hardware.org/?probe=9bacefd984) | Sep 04, 2023 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [b0127b4bff](https://linux-hardware.org/?probe=b0127b4bff) | Sep 01, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| Dell          | 0HR330                      | Desktop     | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [8445b944a5](https://linux-hardware.org/?probe=8445b944a5) | Aug 25, 2023 |
| Dell          | Latitude E5420              | Notebook    | [102bee1da1](https://linux-hardware.org/?probe=102bee1da1) | Aug 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Dell          | 0200DY A00                  | Desktop     | [9b94c2313c](https://linux-hardware.org/?probe=9b94c2313c) | Aug 18, 2023 |
| Sony          | VGN-NW2SRF_S                | Notebook    | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| HP            | Pavilion g4                 | Notebook    | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| Pegatron      | EVANS                       | Desktop     | [323d6a7283](https://linux-hardware.org/?probe=323d6a7283) | Jul 29, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [ac8aab1d26](https://linux-hardware.org/?probe=ac8aab1d26) | Jul 29, 2023 |
| Chuwi         | CoreBook Pro                | Notebook    | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Biostar       | A68MDE                      | Desktop     | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Lenovo        | ThinkPad L460 20FVS01J00    | Notebook    | [96fe0142cd](https://linux-hardware.org/?probe=96fe0142cd) | Jul 23, 2023 |
| Dell          | Inspiron MP061              | Notebook    | [0a26ffe33b](https://linux-hardware.org/?probe=0a26ffe33b) | Jul 15, 2023 |
| Dell          | 048DY8 A00                  | Desktop     | [66c586dfe4](https://linux-hardware.org/?probe=66c586dfe4) | Jul 11, 2023 |
| Gigabyte      | GA-MA770-ES3                | Desktop     | [9af789d1d2](https://linux-hardware.org/?probe=9af789d1d2) | Jul 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [9934022e9b](https://linux-hardware.org/?probe=9934022e9b) | Jul 09, 2023 |
| Sony          | VPCCW2S8E                   | Notebook    | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [c997fd76cf](https://linux-hardware.org/?probe=c997fd76cf) | Jul 02, 2023 |
| Gigabyte      | B75-D3V                     | Desktop     | [a05a3f6ca0](https://linux-hardware.org/?probe=a05a3f6ca0) | Jul 01, 2023 |
| Lenovo        | ThinkCentre M90p 5450A26    | Desktop     | [78632c3242](https://linux-hardware.org/?probe=78632c3242) | Jun 26, 2023 |
| ASUSTek       | M51Vr                       | Notebook    | [16404e70f6](https://linux-hardware.org/?probe=16404e70f6) | Jun 25, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [eb8a9d675b](https://linux-hardware.org/?probe=eb8a9d675b) | Jun 25, 2023 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [d5e4ce2efa](https://linux-hardware.org/?probe=d5e4ce2efa) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [44e57dc97b](https://linux-hardware.org/?probe=44e57dc97b) | Jun 25, 2023 |
| Intel         | D34010WYK H14771-302        | Desktop     | [acda87fcd6](https://linux-hardware.org/?probe=acda87fcd6) | Jun 21, 2023 |
| HP            | Compaq Presario CQ71        | Notebook    | [d5025e2864](https://linux-hardware.org/?probe=d5025e2864) | Jun 18, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [191a3b02ac](https://linux-hardware.org/?probe=191a3b02ac) | Jun 17, 2023 |
| Lenovo        | ThinkPad L430 24655Q7       | Notebook    | [7b45c0777e](https://linux-hardware.org/?probe=7b45c0777e) | Jun 08, 2023 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [72702690e5](https://linux-hardware.org/?probe=72702690e5) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [d94ba8fb27](https://linux-hardware.org/?probe=d94ba8fb27) | Jun 01, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [ca4691fd95](https://linux-hardware.org/?probe=ca4691fd95) | May 31, 2023 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [80fa152a82](https://linux-hardware.org/?probe=80fa152a82) | May 17, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Intel         | WADE-8076-ST-WMS            | Desktop     | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| MSI           | A75A-G55                    | Desktop     | [6ecb91213c](https://linux-hardware.org/?probe=6ecb91213c) | May 05, 2023 |
| ASUSTek       | Maximus V GENE              | Desktop     | [1f49086889](https://linux-hardware.org/?probe=1f49086889) | May 03, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| ASUSTek       | PN62S                       | Mini pc     | [8b7d9ca6fd](https://linux-hardware.org/?probe=8b7d9ca6fd) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [561b87c8b4](https://linux-hardware.org/?probe=561b87c8b4) | Apr 20, 2023 |
| eMachines     | E945GCU                     | Desktop     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| Dell          | 0RF705                      | Desktop     | [32dbb3206b](https://linux-hardware.org/?probe=32dbb3206b) | Apr 16, 2023 |
| ASUSTek       | M51Vr                       | Notebook    | [27d265c73d](https://linux-hardware.org/?probe=27d265c73d) | Apr 15, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [981bad2be2](https://linux-hardware.org/?probe=981bad2be2) | Apr 14, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| Acer          | Aspire 5538                 | Notebook    | [3128c45dbc](https://linux-hardware.org/?probe=3128c45dbc) | Apr 09, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| ASUSTek       | P5K                         | Desktop     | [00a17a60bf](https://linux-hardware.org/?probe=00a17a60bf) | Apr 09, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [c76171c0a7](https://linux-hardware.org/?probe=c76171c0a7) | Apr 07, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [c6e30ff3cc](https://linux-hardware.org/?probe=c6e30ff3cc) | Apr 06, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [31d10a7e98](https://linux-hardware.org/?probe=31d10a7e98) | Apr 04, 2023 |
| Intel         | DZ87KLT75K AAG74721-304     | Desktop     | [4f97ce0a4b](https://linux-hardware.org/?probe=4f97ce0a4b) | Apr 03, 2023 |
| ASUSTek       | K54C                        | Notebook    | [a2a91e2071](https://linux-hardware.org/?probe=a2a91e2071) | Mar 30, 2023 |
| Medion        | B250H4-EM                   | Desktop     | [f569d44749](https://linux-hardware.org/?probe=f569d44749) | Mar 30, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d3ae118e3b](https://linux-hardware.org/?probe=d3ae118e3b) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [11c94aa91b](https://linux-hardware.org/?probe=11c94aa91b) | Mar 29, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [c55a4d3166](https://linux-hardware.org/?probe=c55a4d3166) | Mar 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137A2U    | Desktop     | [cc740804d7](https://linux-hardware.org/?probe=cc740804d7) | Mar 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3ce94dae13](https://linux-hardware.org/?probe=3ce94dae13) | Mar 25, 2023 |
| Lenovo        | 0x36BF SDK0J40709 WIN 32... | All in one  | [018bbef1d6](https://linux-hardware.org/?probe=018bbef1d6) | Mar 24, 2023 |
| Dell          | Precision 7720              | Notebook    | [c3ef75d6eb](https://linux-hardware.org/?probe=c3ef75d6eb) | Mar 23, 2023 |
| Dell          | 0C2KJT A00                  | Desktop     | [54bdc4bbd0](https://linux-hardware.org/?probe=54bdc4bbd0) | Mar 21, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [30e77255e4](https://linux-hardware.org/?probe=30e77255e4) | Mar 20, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [badcc52c19](https://linux-hardware.org/?probe=badcc52c19) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [d91eb1923c](https://linux-hardware.org/?probe=d91eb1923c) | Mar 17, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [c2230a6690](https://linux-hardware.org/?probe=c2230a6690) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AN0070M... | Notebook    | [0d0877faf5](https://linux-hardware.org/?probe=0d0877faf5) | Mar 10, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Chuwi         | LapBook Plus                | Notebook    | [55365bb7ab](https://linux-hardware.org/?probe=55365bb7ab) | Mar 07, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [e4e66a8215](https://linux-hardware.org/?probe=e4e66a8215) | Mar 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [3c4bf3c1bd](https://linux-hardware.org/?probe=3c4bf3c1bd) | Mar 05, 2023 |
| PCWare        | APM-A320G                   | Desktop     | [2bc24b8935](https://linux-hardware.org/?probe=2bc24b8935) | Mar 04, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [196ff8d0dc](https://linux-hardware.org/?probe=196ff8d0dc) | Mar 03, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| Acer          | Aspire X3995                | Desktop     | [eccac5b752](https://linux-hardware.org/?probe=eccac5b752) | Feb 28, 2023 |
| HP            | 3032h                       | Desktop     | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [92ac86c31b](https://linux-hardware.org/?probe=92ac86c31b) | Feb 25, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| Lenovo        | ThinkPad T520 4242NS9       | Notebook    | [6e2e5c8285](https://linux-hardware.org/?probe=6e2e5c8285) | Feb 22, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [d29d970c4a](https://linux-hardware.org/?probe=d29d970c4a) | Feb 22, 2023 |
| Timi          | TM1707                      | Notebook    | [9bc429fbd6](https://linux-hardware.org/?probe=9bc429fbd6) | Feb 22, 2023 |
| IP3 Tech      | rev1.1                      | Mini pc     | [7c4f6801f0](https://linux-hardware.org/?probe=7c4f6801f0) | Feb 20, 2023 |
| HP            | 15                          | Notebook    | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [df5351b94d](https://linux-hardware.org/?probe=df5351b94d) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Medion        | E7220                       | Notebook    | [a1b4318b54](https://linux-hardware.org/?probe=a1b4318b54) | Feb 14, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4ccd4c2da2](https://linux-hardware.org/?probe=4ccd4c2da2) | Feb 14, 2023 |
| ASUSTek       | X555DG                      | Notebook    | [3f51c3533f](https://linux-hardware.org/?probe=3f51c3533f) | Feb 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [2032f6e202](https://linux-hardware.org/?probe=2032f6e202) | Feb 13, 2023 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [f9cfe6d485](https://linux-hardware.org/?probe=f9cfe6d485) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Tablet 20GHS... | Tablet      | [6f25e83af0](https://linux-hardware.org/?probe=6f25e83af0) | Feb 10, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [afaaed1c36](https://linux-hardware.org/?probe=afaaed1c36) | Feb 09, 2023 |
| HP            | ProBook 4530s               | Notebook    | [c081fdc9be](https://linux-hardware.org/?probe=c081fdc9be) | Feb 07, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [91a070c2aa](https://linux-hardware.org/?probe=91a070c2aa) | Feb 03, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [49d8a19239](https://linux-hardware.org/?probe=49d8a19239) | Feb 03, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [f7a88d0dea](https://linux-hardware.org/?probe=f7a88d0dea) | Feb 01, 2023 |
| ASUSTek       | K43SJ                       | Notebook    | [0cff4ad069](https://linux-hardware.org/?probe=0cff4ad069) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| Acer          | Peppy                       | Notebook    | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | MAHOBAY 31900003 STD        | All in one  | [d75e472005](https://linux-hardware.org/?probe=d75e472005) | Jan 26, 2023 |
| ASUSTek       | X51L                        | Notebook    | [b482dc649b](https://linux-hardware.org/?probe=b482dc649b) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7545ee3eb0](https://linux-hardware.org/?probe=7545ee3eb0) | Jan 22, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e261893ec4](https://linux-hardware.org/?probe=e261893ec4) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| Lenovo        | ThinkPad L510 2873A17       | Notebook    | [13f5fd23e5](https://linux-hardware.org/?probe=13f5fd23e5) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [190d9b58b8](https://linux-hardware.org/?probe=190d9b58b8) | Jan 12, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0ddeecd2b8](https://linux-hardware.org/?probe=0ddeecd2b8) | Jan 11, 2023 |
| HP            | 83F2                        | Desktop     | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [c366df1d8d](https://linux-hardware.org/?probe=c366df1d8d) | Jan 09, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [952caf04f8](https://linux-hardware.org/?probe=952caf04f8) | Jan 05, 2023 |
| ASUSTek       | M2N68 Plus                  | Desktop     | [12309f8c91](https://linux-hardware.org/?probe=12309f8c91) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5ea753453b](https://linux-hardware.org/?probe=5ea753453b) | Jan 03, 2023 |
| HP            | 304Bh                       | Desktop     | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [4ab759533b](https://linux-hardware.org/?probe=4ab759533b) | Dec 25, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | M51Vr                       | Notebook    | [ffc48a52ea](https://linux-hardware.org/?probe=ffc48a52ea) | Dec 22, 2022 |
| Gigabyte      | EP43-DS3                    | Desktop     | [d0f0cd82f9](https://linux-hardware.org/?probe=d0f0cd82f9) | Dec 22, 2022 |
| HP            | Presario CQ62               | Notebook    | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| HP            | Compaq 6735s                | Notebook    | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| ASRock        | M3A770DE                    | Desktop     | [2e6b1f9c2d](https://linux-hardware.org/?probe=2e6b1f9c2d) | Dec 13, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [85794e606c](https://linux-hardware.org/?probe=85794e606c) | Dec 08, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [57e0d3651c](https://linux-hardware.org/?probe=57e0d3651c) | Dec 08, 2022 |
| Gigabyte      | GA-MA770-ES3                | Desktop     | [70c1a43352](https://linux-hardware.org/?probe=70c1a43352) | Dec 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a4a8d6dcec](https://linux-hardware.org/?probe=a4a8d6dcec) | Dec 03, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3f2ef35b32](https://linux-hardware.org/?probe=3f2ef35b32) | Nov 04, 2022 |
| MSI           | Z97-G43                     | Desktop     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [69327d2615](https://linux-hardware.org/?probe=69327d2615) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| Sony          | VPCEB1S1R                   | Notebook    | [1e64f5427a](https://linux-hardware.org/?probe=1e64f5427a) | Oct 21, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| HP            | Notebook                    | Notebook    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [69db41a0b6](https://linux-hardware.org/?probe=69db41a0b6) | Oct 06, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| HP            | 1998                        | Desktop     | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [07477a078f](https://linux-hardware.org/?probe=07477a078f) | Sep 22, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [d55d9fad24](https://linux-hardware.org/?probe=d55d9fad24) | Sep 17, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [a790b35cc1](https://linux-hardware.org/?probe=a790b35cc1) | Sep 17, 2022 |
| Intel         | H61                         | Desktop     | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| HP            | 82F2 A01                    | Desktop     | [f97faeff54](https://linux-hardware.org/?probe=f97faeff54) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [d88e0026dc](https://linux-hardware.org/?probe=d88e0026dc) | Sep 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| HP            | 3396                        | Desktop     | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| ASUSTek       | ET2040I                     | Desktop     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5ba20eb04b](https://linux-hardware.org/?probe=5ba20eb04b) | Sep 01, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| Lenovo        | ThinkCentre M58e 7408BA5    | Desktop     | [4384314f98](https://linux-hardware.org/?probe=4384314f98) | Sep 01, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [09ffe165d3](https://linux-hardware.org/?probe=09ffe165d3) | Aug 30, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| HP            | 82B4                        | Desktop     | [e3200ae579](https://linux-hardware.org/?probe=e3200ae579) | Aug 22, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [36a4120390](https://linux-hardware.org/?probe=36a4120390) | Aug 20, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [b05fac6451](https://linux-hardware.org/?probe=b05fac6451) | Aug 19, 2022 |
| Packard Be... | EasyNote TK37               | Notebook    | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Dell          | 0GM819                      | Desktop     | [f7745d3d3a](https://linux-hardware.org/?probe=f7745d3d3a) | Aug 16, 2022 |
| HP            | Notebook                    | Notebook    | [975f3e38e3](https://linux-hardware.org/?probe=975f3e38e3) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [32bf5bd8b8](https://linux-hardware.org/?probe=32bf5bd8b8) | Aug 13, 2022 |
| Intel         | NUC7JYB J67967-405          | Mini pc     | [06fdb19375](https://linux-hardware.org/?probe=06fdb19375) | Aug 08, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| MSI           | GE62VR 7RF                  | Notebook    | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [cb93c45a3a](https://linux-hardware.org/?probe=cb93c45a3a) | Jul 31, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [2c1dddeaea](https://linux-hardware.org/?probe=2c1dddeaea) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d85cd905fd](https://linux-hardware.org/?probe=d85cd905fd) | Jul 28, 2022 |
| Dell          | 0P301D A00                  | Desktop     | [48d1ed3099](https://linux-hardware.org/?probe=48d1ed3099) | Jul 28, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [ab730a80b3](https://linux-hardware.org/?probe=ab730a80b3) | Jul 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [2f0de52d8e](https://linux-hardware.org/?probe=2f0de52d8e) | Jul 08, 2022 |
| Gateway       | NE56R                       | Notebook    | [69f2805432](https://linux-hardware.org/?probe=69f2805432) | Jul 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [4160bc427a](https://linux-hardware.org/?probe=4160bc427a) | Jul 03, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [f5da6492ca](https://linux-hardware.org/?probe=f5da6492ca) | Jul 03, 2022 |
| Dell          | 0WPG9H A01                  | All in one  | [f554b4aa06](https://linux-hardware.org/?probe=f554b4aa06) | Jul 03, 2022 |
| Dell          | Latitude D630               | Notebook    | [df3001a64d](https://linux-hardware.org/?probe=df3001a64d) | Jul 02, 2022 |
| Notebook      | MIM 2200                    | Notebook    | [85748618b6](https://linux-hardware.org/?probe=85748618b6) | Jul 02, 2022 |
| Medion        | E2292                       | Convertible | [155434e3b5](https://linux-hardware.org/?probe=155434e3b5) | Jul 01, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [0924d664a1](https://linux-hardware.org/?probe=0924d664a1) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Dell          | Latitude E7250              | Notebook    | [790850da0b](https://linux-hardware.org/?probe=790850da0b) | Jun 22, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [98b2b138f4](https://linux-hardware.org/?probe=98b2b138f4) | Jun 20, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [8113862978](https://linux-hardware.org/?probe=8113862978) | Jun 18, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [6926193d76](https://linux-hardware.org/?probe=6926193d76) | Jun 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Sony          | VGN-NW310F                  | Notebook    | [318b17f951](https://linux-hardware.org/?probe=318b17f951) | Jun 17, 2022 |
| HP            | Pavilion g4                 | Notebook    | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| Gigabyte      | H61M-HD2                    | Desktop     | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [2dd49013ff](https://linux-hardware.org/?probe=2dd49013ff) | Jun 10, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [a4587cc1de](https://linux-hardware.org/?probe=a4587cc1de) | Jun 10, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [17752552c6](https://linux-hardware.org/?probe=17752552c6) | Jun 02, 2022 |
| MSI           | MS-7255                     | Desktop     | [772cf64635](https://linux-hardware.org/?probe=772cf64635) | Jun 02, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [295c085967](https://linux-hardware.org/?probe=295c085967) | Jun 01, 2022 |
| Medion        | E7220                       | Notebook    | [d4a700af57](https://linux-hardware.org/?probe=d4a700af57) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Medion        | E2292                       | Convertible | [85296d99ac](https://linux-hardware.org/?probe=85296d99ac) | Jun 01, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Clevo         | W55xEU                      | Notebook    | [c5fd2417f4](https://linux-hardware.org/?probe=c5fd2417f4) | May 25, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [bc39db0484](https://linux-hardware.org/?probe=bc39db0484) | May 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| MSI           | B150M BAZOOKA               | Desktop     | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Acer          | Aspire 5332                 | Notebook    | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [679cd1e540](https://linux-hardware.org/?probe=679cd1e540) | May 18, 2022 |
| Gigabyte      | X38-DQ6                     | Desktop     | [653ffc4014](https://linux-hardware.org/?probe=653ffc4014) | May 16, 2022 |
| Toshiba       | Satellite C670D-126         | Notebook    | [9df3447b21](https://linux-hardware.org/?probe=9df3447b21) | May 14, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [f3180b0817](https://linux-hardware.org/?probe=f3180b0817) | May 13, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [39f623cf4d](https://linux-hardware.org/?probe=39f623cf4d) | May 08, 2022 |
| Positivo      | POS-PARS760GCD              | Desktop     | [dfc00dfd71](https://linux-hardware.org/?probe=dfc00dfd71) | May 05, 2022 |
| Toshiba       | Satellite C645D             | Notebook    | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [f571b0dc6f](https://linux-hardware.org/?probe=f571b0dc6f) | May 02, 2022 |
| Medion        | E2292                       | Convertible | [6823c98493](https://linux-hardware.org/?probe=6823c98493) | May 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [53f6946eba](https://linux-hardware.org/?probe=53f6946eba) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [2e44e9228e](https://linux-hardware.org/?probe=2e44e9228e) | Apr 28, 2022 |
| PC Special... | NJ50_70CU                   | Notebook    | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0e266b4987](https://linux-hardware.org/?probe=0e266b4987) | Apr 25, 2022 |
| Foxconn       | 945 7AD Series              | Desktop     | [04346c58f5](https://linux-hardware.org/?probe=04346c58f5) | Apr 23, 2022 |
| Pegatron      | EVANS                       | Desktop     | [118f512619](https://linux-hardware.org/?probe=118f512619) | Apr 21, 2022 |
| HP            | 304Ah                       | Desktop     | [08fbf0f311](https://linux-hardware.org/?probe=08fbf0f311) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [9cabfec30b](https://linux-hardware.org/?probe=9cabfec30b) | Apr 19, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [80943ca395](https://linux-hardware.org/?probe=80943ca395) | Apr 18, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [4e70c05231](https://linux-hardware.org/?probe=4e70c05231) | Apr 17, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| HP            | Pavilion dv6                | Notebook    | [639a7422d8](https://linux-hardware.org/?probe=639a7422d8) | Apr 16, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e9a5e187ad](https://linux-hardware.org/?probe=e9a5e187ad) | Apr 15, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | 2215                        | Desktop     | [5acea5fa0a](https://linux-hardware.org/?probe=5acea5fa0a) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| HP            | ProBook 470 G3              | Notebook    | [5c65c7eedd](https://linux-hardware.org/?probe=5c65c7eedd) | Apr 10, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [94fccb48fd](https://linux-hardware.org/?probe=94fccb48fd) | Apr 10, 2022 |
| Intel         | H81                         | Desktop     | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [526a5a16bd](https://linux-hardware.org/?probe=526a5a16bd) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ECS           | Nettle2                     | Desktop     | [65cedbb00d](https://linux-hardware.org/?probe=65cedbb00d) | Apr 07, 2022 |
| HP            | Pavilion dv6                | Notebook    | [209dbfbea6](https://linux-hardware.org/?probe=209dbfbea6) | Apr 06, 2022 |
| Medion        | E2292                       | Convertible | [3302d8f658](https://linux-hardware.org/?probe=3302d8f658) | Apr 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c5c24ea4c2](https://linux-hardware.org/?probe=c5c24ea4c2) | Apr 06, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [9afad803e0](https://linux-hardware.org/?probe=9afad803e0) | Apr 05, 2022 |
| Dell          | 0CT017                      | Desktop     | [27bdeec11d](https://linux-hardware.org/?probe=27bdeec11d) | Apr 04, 2022 |
| Sony          | VGN-FZ31M                   | Notebook    | [5e1ef6c19a](https://linux-hardware.org/?probe=5e1ef6c19a) | Apr 03, 2022 |
| MSI           | X58M                        | Desktop     | [7484dce6ce](https://linux-hardware.org/?probe=7484dce6ce) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | Notebook    | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [1aff91c424](https://linux-hardware.org/?probe=1aff91c424) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | Notebook    | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| HP            | 355 G2                      | Notebook    | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [1991a3f990](https://linux-hardware.org/?probe=1991a3f990) | Mar 28, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [996a5d269c](https://linux-hardware.org/?probe=996a5d269c) | Mar 28, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3839ca9677](https://linux-hardware.org/?probe=3839ca9677) | Mar 27, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [3313178485](https://linux-hardware.org/?probe=3313178485) | Mar 25, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [0d7d21ac36](https://linux-hardware.org/?probe=0d7d21ac36) | Mar 24, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [f9fb419fef](https://linux-hardware.org/?probe=f9fb419fef) | Mar 23, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [91d5c07184](https://linux-hardware.org/?probe=91d5c07184) | Mar 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [44d6d432f9](https://linux-hardware.org/?probe=44d6d432f9) | Mar 21, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [50fd3adf1a](https://linux-hardware.org/?probe=50fd3adf1a) | Mar 21, 2022 |
| HP            | 81B3                        | Desktop     | [1924290221](https://linux-hardware.org/?probe=1924290221) | Mar 17, 2022 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [7e23b31c1b](https://linux-hardware.org/?probe=7e23b31c1b) | Mar 17, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [0480518e2e](https://linux-hardware.org/?probe=0480518e2e) | Mar 15, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [9cad95edc1](https://linux-hardware.org/?probe=9cad95edc1) | Mar 12, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [dfa0722637](https://linux-hardware.org/?probe=dfa0722637) | Mar 12, 2022 |
| HP            | ENVY Notebook               | Notebook    | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [83a319f258](https://linux-hardware.org/?probe=83a319f258) | Mar 11, 2022 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [8762e9c632](https://linux-hardware.org/?probe=8762e9c632) | Mar 10, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [1a3f77be23](https://linux-hardware.org/?probe=1a3f77be23) | Mar 09, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [9bcfd85a21](https://linux-hardware.org/?probe=9bcfd85a21) | Mar 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [74e5474a84](https://linux-hardware.org/?probe=74e5474a84) | Mar 05, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [bb9daa5ab1](https://linux-hardware.org/?probe=bb9daa5ab1) | Mar 05, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [18b982d433](https://linux-hardware.org/?probe=18b982d433) | Mar 05, 2022 |
| HP            | Pavilion dv5                | Notebook    | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [16ba341ccd](https://linux-hardware.org/?probe=16ba341ccd) | Mar 03, 2022 |
| Dell          | Inspiron 1420               | Notebook    | [30424b62be](https://linux-hardware.org/?probe=30424b62be) | Mar 03, 2022 |
| Medion        | E2292                       | Convertible | [e7fb0bbd0d](https://linux-hardware.org/?probe=e7fb0bbd0d) | Mar 01, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [fde5cc4a6c](https://linux-hardware.org/?probe=fde5cc4a6c) | Mar 01, 2022 |
| Foxconn       | 2A92                        | Desktop     | [d41fb8dda1](https://linux-hardware.org/?probe=d41fb8dda1) | Feb 28, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [a757f64435](https://linux-hardware.org/?probe=a757f64435) | Feb 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [40f6802b71](https://linux-hardware.org/?probe=40f6802b71) | Feb 27, 2022 |
| Acer          | RS880M05                    | Desktop     | [53e88a31a0](https://linux-hardware.org/?probe=53e88a31a0) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| MSI           | H410M PRO                   | Desktop     | [60cb5eed90](https://linux-hardware.org/?probe=60cb5eed90) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | Notebook    | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| MSI           | KA780G                      | Desktop     | [f6bc0eda57](https://linux-hardware.org/?probe=f6bc0eda57) | Feb 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| ASRock        | Q1900M                      | Desktop     | [428eb82cd0](https://linux-hardware.org/?probe=428eb82cd0) | Feb 23, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [99c0e6257f](https://linux-hardware.org/?probe=99c0e6257f) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [0fd5d9a994](https://linux-hardware.org/?probe=0fd5d9a994) | Feb 20, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [ceceebf84f](https://linux-hardware.org/?probe=ceceebf84f) | Feb 19, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e9d45ff571](https://linux-hardware.org/?probe=e9d45ff571) | Feb 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [e8a3ceb5a9](https://linux-hardware.org/?probe=e8a3ceb5a9) | Feb 18, 2022 |
| Acer          | One Z1402                   | Notebook    | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [87de36a11b](https://linux-hardware.org/?probe=87de36a11b) | Feb 17, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [740ff0ffcc](https://linux-hardware.org/?probe=740ff0ffcc) | Feb 17, 2022 |
| ASRock        | N68-GS                      | Desktop     | [06e4bc5238](https://linux-hardware.org/?probe=06e4bc5238) | Feb 16, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | Notebook    | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Lenovo        | ThinkCentre M58p 7630A38    | Desktop     | [5317cf122d](https://linux-hardware.org/?probe=5317cf122d) | Feb 15, 2022 |
| Huanan        | X79-ZD3 V2.3                | Desktop     | [c20523ee1f](https://linux-hardware.org/?probe=c20523ee1f) | Feb 15, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [34d933c2f3](https://linux-hardware.org/?probe=34d933c2f3) | Feb 15, 2022 |
| Dell          | 0TT708 A01                  | Desktop     | [4f615ac094](https://linux-hardware.org/?probe=4f615ac094) | Feb 15, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| Philco        | 10D                         | Desktop     | [2efb7555a1](https://linux-hardware.org/?probe=2efb7555a1) | Feb 14, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [64c37730f6](https://linux-hardware.org/?probe=64c37730f6) | Feb 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [1bade168b7](https://linux-hardware.org/?probe=1bade168b7) | Feb 13, 2022 |
| Acer          | Extensa 2519                | Notebook    | [4da8d63710](https://linux-hardware.org/?probe=4da8d63710) | Feb 13, 2022 |
| Sony          | SVF1521G6EW                 | Notebook    | [365ef21d2a](https://linux-hardware.org/?probe=365ef21d2a) | Feb 13, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [85b90b81ce](https://linux-hardware.org/?probe=85b90b81ce) | Feb 13, 2022 |
| Acer          | Aspire V5-122               | Notebook    | [d516569472](https://linux-hardware.org/?probe=d516569472) | Feb 13, 2022 |
| Acer          | Aspire E1-530               | Notebook    | [21e2a6f70a](https://linux-hardware.org/?probe=21e2a6f70a) | Feb 13, 2022 |
| HP            | 1998                        | Desktop     | [6b68df0b96](https://linux-hardware.org/?probe=6b68df0b96) | Feb 12, 2022 |
| ASUSTek       | K52F                        | Notebook    | [46e3780be8](https://linux-hardware.org/?probe=46e3780be8) | Feb 12, 2022 |
| Intel         | DG45ID AAE27729-308         | Desktop     | [91f90c2997](https://linux-hardware.org/?probe=91f90c2997) | Feb 12, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b229af38f0](https://linux-hardware.org/?probe=b229af38f0) | Feb 12, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5356027467](https://linux-hardware.org/?probe=5356027467) | Feb 12, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [d9dbe1d02f](https://linux-hardware.org/?probe=d9dbe1d02f) | Feb 11, 2022 |
| MouseCompu... | B75H2-M2                    | Desktop     | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| Dell          | 06NWYK A00                  | Desktop     | [a4654ee182](https://linux-hardware.org/?probe=a4654ee182) | Feb 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [285b0fc2fd](https://linux-hardware.org/?probe=285b0fc2fd) | Feb 11, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5182b3bbf6](https://linux-hardware.org/?probe=5182b3bbf6) | Feb 10, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bdda853706](https://linux-hardware.org/?probe=bdda853706) | Feb 09, 2022 |
| Acer          | Aspire 6935                 | Notebook    | [d0dd380298](https://linux-hardware.org/?probe=d0dd380298) | Feb 08, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bf3e4dae03](https://linux-hardware.org/?probe=bf3e4dae03) | Feb 08, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [9aa6cb1e41](https://linux-hardware.org/?probe=9aa6cb1e41) | Feb 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [6754affc30](https://linux-hardware.org/?probe=6754affc30) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b23b568543](https://linux-hardware.org/?probe=b23b568543) | Feb 08, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [485e063883](https://linux-hardware.org/?probe=485e063883) | Feb 07, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [54ebd54640](https://linux-hardware.org/?probe=54ebd54640) | Feb 07, 2022 |
| ASUSTek       | P7H55                       | Desktop     | [1ac17e6259](https://linux-hardware.org/?probe=1ac17e6259) | Feb 07, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [efb562bd96](https://linux-hardware.org/?probe=efb562bd96) | Feb 07, 2022 |
| Toshiba       | Satellite C855-22N          | Notebook    | [e8a4451a9d](https://linux-hardware.org/?probe=e8a4451a9d) | Feb 06, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2e55ebbf9f](https://linux-hardware.org/?probe=2e55ebbf9f) | Feb 06, 2022 |
| MSI           | 760GA-P43                   | Desktop     | [6212c219c8](https://linux-hardware.org/?probe=6212c219c8) | Feb 06, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [f7d707147c](https://linux-hardware.org/?probe=f7d707147c) | Feb 06, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [f6bb9b0ffd](https://linux-hardware.org/?probe=f6bb9b0ffd) | Feb 06, 2022 |
| HP            | 3397                        | Desktop     | [5e842a74ac](https://linux-hardware.org/?probe=5e842a74ac) | Feb 06, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [3c1c6e0805](https://linux-hardware.org/?probe=3c1c6e0805) | Feb 06, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [261fb2f356](https://linux-hardware.org/?probe=261fb2f356) | Feb 06, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [a5db2b8436](https://linux-hardware.org/?probe=a5db2b8436) | Feb 06, 2022 |
| Dell          | G3 3779                     | Notebook    | [c9185bcf1f](https://linux-hardware.org/?probe=c9185bcf1f) | Feb 06, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [fb82e73470](https://linux-hardware.org/?probe=fb82e73470) | Feb 06, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f00c7a8507](https://linux-hardware.org/?probe=f00c7a8507) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9c87bc4fca](https://linux-hardware.org/?probe=9c87bc4fca) | Feb 05, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [b18e761c0f](https://linux-hardware.org/?probe=b18e761c0f) | Feb 05, 2022 |
| Medion        | MS-7800                     | Desktop     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [61007dacfd](https://linux-hardware.org/?probe=61007dacfd) | Feb 05, 2022 |
| ASUSTek       | M4N68T                      | Desktop     | [5052fa9dac](https://linux-hardware.org/?probe=5052fa9dac) | Feb 05, 2022 |
| Acer          | Extensa 5620                | Notebook    | [d5048cae9a](https://linux-hardware.org/?probe=d5048cae9a) | Feb 05, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [fef25611fb](https://linux-hardware.org/?probe=fef25611fb) | Feb 05, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [10c9ca0b26](https://linux-hardware.org/?probe=10c9ca0b26) | Feb 05, 2022 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [895bbcb050](https://linux-hardware.org/?probe=895bbcb050) | Feb 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [80996b75ff](https://linux-hardware.org/?probe=80996b75ff) | Feb 04, 2022 |
| MSI           | MS-7392                     | Desktop     | [e8f489c1fc](https://linux-hardware.org/?probe=e8f489c1fc) | Feb 04, 2022 |
| HP            | Pavilion dm1                | Notebook    | [4b0fcd3df5](https://linux-hardware.org/?probe=4b0fcd3df5) | Feb 04, 2022 |
| Dell          | 09PV3R A00                  | Desktop     | [23a9613450](https://linux-hardware.org/?probe=23a9613450) | Feb 04, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [a9613de1e1](https://linux-hardware.org/?probe=a9613de1e1) | Feb 04, 2022 |
| HP            | 355 G2                      | Notebook    | [2a05eb0f1c](https://linux-hardware.org/?probe=2a05eb0f1c) | Feb 04, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [378fec89b1](https://linux-hardware.org/?probe=378fec89b1) | Feb 04, 2022 |
| Medion        | E2292                       | Convertible | [10a64531f1](https://linux-hardware.org/?probe=10a64531f1) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [5d9fd312b4](https://linux-hardware.org/?probe=5d9fd312b4) | Feb 03, 2022 |
| Clevo         | P150HMx                     | Notebook    | [8f04d16711](https://linux-hardware.org/?probe=8f04d16711) | Feb 03, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [32bbd0c80c](https://linux-hardware.org/?probe=32bbd0c80c) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | Desktop     | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [63c15e2642](https://linux-hardware.org/?probe=63c15e2642) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [67e8645c04](https://linux-hardware.org/?probe=67e8645c04) | Feb 03, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [b8645533ae](https://linux-hardware.org/?probe=b8645533ae) | Feb 02, 2022 |
| HP            | 8105                        | Desktop     | [8e49155614](https://linux-hardware.org/?probe=8e49155614) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [6075abc821](https://linux-hardware.org/?probe=6075abc821) | Feb 02, 2022 |
| Dell          | Latitude D630               | Notebook    | [f7a31d8e3e](https://linux-hardware.org/?probe=f7a31d8e3e) | Feb 02, 2022 |
| Unknown       | X99H                        | Desktop     | [29bd27d08f](https://linux-hardware.org/?probe=29bd27d08f) | Feb 02, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [71569beb05](https://linux-hardware.org/?probe=71569beb05) | Feb 02, 2022 |
| Lenovo        | ThinkPad W700 27526LG       | Notebook    | [06b01ba136](https://linux-hardware.org/?probe=06b01ba136) | Feb 02, 2022 |
| HP            | 355 G2                      | Notebook    | [96a86baab9](https://linux-hardware.org/?probe=96a86baab9) | Feb 02, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [bdb825e963](https://linux-hardware.org/?probe=bdb825e963) | Feb 02, 2022 |
| MSI           | VR201                       | Notebook    | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [5e92f5c961](https://linux-hardware.org/?probe=5e92f5c961) | Feb 01, 2022 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [6ad345c1a5](https://linux-hardware.org/?probe=6ad345c1a5) | Feb 01, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | Notebook    | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Toshiba       | Satellite Pro R850          | Notebook    | [8d5f88157a](https://linux-hardware.org/?probe=8d5f88157a) | Feb 01, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [ead4c2c3fb](https://linux-hardware.org/?probe=ead4c2c3fb) | Feb 01, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [b08503a021](https://linux-hardware.org/?probe=b08503a021) | Feb 01, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [e8c4b3dfce](https://linux-hardware.org/?probe=e8c4b3dfce) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5d06ba826f](https://linux-hardware.org/?probe=5d06ba826f) | Jan 31, 2022 |
| Teclast       | F15S                        | Notebook    | [f3161d72b0](https://linux-hardware.org/?probe=f3161d72b0) | Jan 30, 2022 |
| HP            | ProBook 6470b               | Notebook    | [86ba660bb5](https://linux-hardware.org/?probe=86ba660bb5) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [a909d3702b](https://linux-hardware.org/?probe=a909d3702b) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [b02315f2c0](https://linux-hardware.org/?probe=b02315f2c0) | Jan 30, 2022 |
| Gigabyte      | H81N                        | Desktop     | [9f53b79a7f](https://linux-hardware.org/?probe=9f53b79a7f) | Jan 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [83fbdbf54b](https://linux-hardware.org/?probe=83fbdbf54b) | Jan 29, 2022 |
| Acer          | Aspire V5-571               | Notebook    | [9c1e6c6a9e](https://linux-hardware.org/?probe=9c1e6c6a9e) | Jan 29, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ddf886b767](https://linux-hardware.org/?probe=ddf886b767) | Jan 29, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [f024dd97a0](https://linux-hardware.org/?probe=f024dd97a0) | Jan 29, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [33d0a3b270](https://linux-hardware.org/?probe=33d0a3b270) | Jan 29, 2022 |
| ASRock        | ION3D-HT                    | Desktop     | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [2edecbff69](https://linux-hardware.org/?probe=2edecbff69) | Jan 29, 2022 |
| ASUSTek       | P5G41T-M LX PLUS            | Desktop     | [f3a447ef83](https://linux-hardware.org/?probe=f3a447ef83) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| IBM           | PCI-Express Riser Card, ... | Server      | [701b89ac2e](https://linux-hardware.org/?probe=701b89ac2e) | Jan 29, 2022 |
| Acer          | Aspire 8942G                | Notebook    | [97a7a92547](https://linux-hardware.org/?probe=97a7a92547) | Jan 28, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [9770dbdaeb](https://linux-hardware.org/?probe=9770dbdaeb) | Jan 28, 2022 |
| ASUSTek       | P8H67-I PRO                 | Desktop     | [640b7e8450](https://linux-hardware.org/?probe=640b7e8450) | Jan 28, 2022 |
| Dell          | Wolf                        | Notebook    | [8fc168eba7](https://linux-hardware.org/?probe=8fc168eba7) | Jan 27, 2022 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [044e014d11](https://linux-hardware.org/?probe=044e014d11) | Jan 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e96d993823](https://linux-hardware.org/?probe=e96d993823) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [55f310b74b](https://linux-hardware.org/?probe=55f310b74b) | Jan 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [e3308423e5](https://linux-hardware.org/?probe=e3308423e5) | Jan 26, 2022 |
| HP            | ProBook 6550b               | Notebook    | [02d7f3125e](https://linux-hardware.org/?probe=02d7f3125e) | Jan 26, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4df21e66db](https://linux-hardware.org/?probe=4df21e66db) | Jan 25, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| HP            | 655                         | Notebook    | [68e37d8274](https://linux-hardware.org/?probe=68e37d8274) | Jan 25, 2022 |
| Dell          | Latitude E5410              | Notebook    | [074ed63eb9](https://linux-hardware.org/?probe=074ed63eb9) | Jan 25, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| Timi          | TM1801                      | Notebook    | [349fdb5215](https://linux-hardware.org/?probe=349fdb5215) | Jan 25, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [0210b11791](https://linux-hardware.org/?probe=0210b11791) | Jan 25, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e0eb175311](https://linux-hardware.org/?probe=e0eb175311) | Jan 25, 2022 |
| Positivo      | Mobile                      | Notebook    | [9b53719e46](https://linux-hardware.org/?probe=9b53719e46) | Jan 25, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [6210f4db07](https://linux-hardware.org/?probe=6210f4db07) | Jan 25, 2022 |
| Acer          | V5-131                      | Notebook    | [ac6664dce9](https://linux-hardware.org/?probe=ac6664dce9) | Jan 25, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [71c6779d52](https://linux-hardware.org/?probe=71c6779d52) | Jan 24, 2022 |
| Acer          | Extensa 2540                | Notebook    | [27a41f2533](https://linux-hardware.org/?probe=27a41f2533) | Jan 24, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a212372095](https://linux-hardware.org/?probe=a212372095) | Jan 24, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [154348ae3a](https://linux-hardware.org/?probe=154348ae3a) | Jan 24, 2022 |
| Lenovo        | ThinkPad T520 4242NS9       | Notebook    | [100812fcd9](https://linux-hardware.org/?probe=100812fcd9) | Jan 24, 2022 |
| ASRock        | AM1B-ITX                    | Desktop     | [5f089eb5bf](https://linux-hardware.org/?probe=5f089eb5bf) | Jan 24, 2022 |
| MSI           | X58M                        | Desktop     | [cf092b7735](https://linux-hardware.org/?probe=cf092b7735) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [20a42368f1](https://linux-hardware.org/?probe=20a42368f1) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | Notebook    | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [e018d5506c](https://linux-hardware.org/?probe=e018d5506c) | Jan 23, 2022 |
| Acer          | Extensa 4630Z               | Notebook    | [40d8b3d26c](https://linux-hardware.org/?probe=40d8b3d26c) | Jan 23, 2022 |
| Eii           | WSA116                      | Notebook    | [ecff258a89](https://linux-hardware.org/?probe=ecff258a89) | Jan 23, 2022 |
| Medion        | MS-7713                     | Desktop     | [e3eb63e81f](https://linux-hardware.org/?probe=e3eb63e81f) | Jan 22, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [c51916b063](https://linux-hardware.org/?probe=c51916b063) | Jan 22, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [5c8ac15198](https://linux-hardware.org/?probe=5c8ac15198) | Jan 22, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [93a2a7dea6](https://linux-hardware.org/?probe=93a2a7dea6) | Jan 22, 2022 |
| Foxconn       | ALOE                        | Desktop     | [a1c7a071c6](https://linux-hardware.org/?probe=a1c7a071c6) | Jan 22, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [cf464f5bce](https://linux-hardware.org/?probe=cf464f5bce) | Jan 22, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [eebb00a00f](https://linux-hardware.org/?probe=eebb00a00f) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [d2c416e76d](https://linux-hardware.org/?probe=d2c416e76d) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [963e5b822d](https://linux-hardware.org/?probe=963e5b822d) | Jan 21, 2022 |
| Foxconn       | A76GMV                      | Desktop     | [c25b49803b](https://linux-hardware.org/?probe=c25b49803b) | Jan 21, 2022 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [515ba182ff](https://linux-hardware.org/?probe=515ba182ff) | Jan 21, 2022 |
| Philco        | 14I                         | Notebook    | [5006ca52e2](https://linux-hardware.org/?probe=5006ca52e2) | Jan 21, 2022 |
| Dell          | Latitude 3540               | Notebook    | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [bac342fc0f](https://linux-hardware.org/?probe=bac342fc0f) | Jan 21, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [7023fd83fc](https://linux-hardware.org/?probe=7023fd83fc) | Jan 21, 2022 |
| Sony          | VPCEB18FD                   | Notebook    | [5fbd1a31a6](https://linux-hardware.org/?probe=5fbd1a31a6) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | 339A                        | Desktop     | [9a1c8ec615](https://linux-hardware.org/?probe=9a1c8ec615) | Jan 21, 2022 |
| Dell          | Inspiron 3482               | Notebook    | [f13427c9b0](https://linux-hardware.org/?probe=f13427c9b0) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [e94ba1d4f2](https://linux-hardware.org/?probe=e94ba1d4f2) | Jan 20, 2022 |
| Acer          | WMCP78M                     | Desktop     | [96428e77d6](https://linux-hardware.org/?probe=96428e77d6) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2a013fff75](https://linux-hardware.org/?probe=2a013fff75) | Jan 20, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [6907df60fb](https://linux-hardware.org/?probe=6907df60fb) | Jan 20, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [e47bd66b78](https://linux-hardware.org/?probe=e47bd66b78) | Jan 20, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [08e0b12a83](https://linux-hardware.org/?probe=08e0b12a83) | Jan 19, 2022 |
| Acer          | Aspire TC-390               | Desktop     | [a6a7896071](https://linux-hardware.org/?probe=a6a7896071) | Jan 19, 2022 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | Notebook    | [e9bebad8ef](https://linux-hardware.org/?probe=e9bebad8ef) | Jan 19, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [3caf7fb5f2](https://linux-hardware.org/?probe=3caf7fb5f2) | Jan 19, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [c00b17efdc](https://linux-hardware.org/?probe=c00b17efdc) | Jan 19, 2022 |
| HP            | 3029h                       | Desktop     | [21048ac4b2](https://linux-hardware.org/?probe=21048ac4b2) | Jan 19, 2022 |
| Alienware     | 2                           | Desktop     | [e149bdddfa](https://linux-hardware.org/?probe=e149bdddfa) | Jan 18, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | V-P5G31                     | Desktop     | [ab3ad44c74](https://linux-hardware.org/?probe=ab3ad44c74) | Jan 18, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [95bbde94a9](https://linux-hardware.org/?probe=95bbde94a9) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| Samsung       | R410P                       | Notebook    | [7837bc7c5f](https://linux-hardware.org/?probe=7837bc7c5f) | Jan 17, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [e88e9c2f3d](https://linux-hardware.org/?probe=e88e9c2f3d) | Jan 17, 2022 |
| ASUSTek       | P5K-VM                      | Desktop     | [8b7c021ac4](https://linux-hardware.org/?probe=8b7c021ac4) | Jan 17, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [005887e692](https://linux-hardware.org/?probe=005887e692) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [fd321a896a](https://linux-hardware.org/?probe=fd321a896a) | Jan 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [5baec4640b](https://linux-hardware.org/?probe=5baec4640b) | Jan 16, 2022 |
| ASUSTek       | K53U                        | Notebook    | [7e754deb91](https://linux-hardware.org/?probe=7e754deb91) | Jan 16, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d6d4dbbb78](https://linux-hardware.org/?probe=d6d4dbbb78) | Jan 16, 2022 |
| Lenovo        | ThinkPad T420 4236LP7       | Notebook    | [92673f1d6e](https://linux-hardware.org/?probe=92673f1d6e) | Jan 16, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [a83705b242](https://linux-hardware.org/?probe=a83705b242) | Jan 16, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [b59d482466](https://linux-hardware.org/?probe=b59d482466) | Jan 16, 2022 |
| Dell          | 0KC9NP A00                  | Desktop     | [9cc01ad5c0](https://linux-hardware.org/?probe=9cc01ad5c0) | Jan 15, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [6da7af33f8](https://linux-hardware.org/?probe=6da7af33f8) | Jan 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [671180553c](https://linux-hardware.org/?probe=671180553c) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [7ca6a7c129](https://linux-hardware.org/?probe=7ca6a7c129) | Jan 14, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [27f00874af](https://linux-hardware.org/?probe=27f00874af) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Fujitsu Si... | D2464-B1 S26361-D2464-B1    | Desktop     | [962a3a8bb0](https://linux-hardware.org/?probe=962a3a8bb0) | Jan 14, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [ccee69eba1](https://linux-hardware.org/?probe=ccee69eba1) | Jan 14, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [6b023312e7](https://linux-hardware.org/?probe=6b023312e7) | Jan 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [972630705f](https://linux-hardware.org/?probe=972630705f) | Jan 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5724c20f52](https://linux-hardware.org/?probe=5724c20f52) | Jan 14, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f6b8d075cf](https://linux-hardware.org/?probe=f6b8d075cf) | Jan 13, 2022 |
| MSI           | MS-B0961                    | All in one  | [de1e024cad](https://linux-hardware.org/?probe=de1e024cad) | Jan 13, 2022 |
| MSI           | MS-7A66                     | Desktop     | [fcddf8cda4](https://linux-hardware.org/?probe=fcddf8cda4) | Jan 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ad49cdde74](https://linux-hardware.org/?probe=ad49cdde74) | Jan 13, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [4fae921f3e](https://linux-hardware.org/?probe=4fae921f3e) | Jan 13, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [6dbf0bdf2f](https://linux-hardware.org/?probe=6dbf0bdf2f) | Jan 13, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cee1b9aefb](https://linux-hardware.org/?probe=cee1b9aefb) | Jan 13, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [59338f2a1a](https://linux-hardware.org/?probe=59338f2a1a) | Jan 12, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5f8ab9c9ce](https://linux-hardware.org/?probe=5f8ab9c9ce) | Jan 11, 2022 |
| Samsung       | N100SP                      | Notebook    | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| Sony          | VPCEH1S1E                   | Notebook    | [854163fb58](https://linux-hardware.org/?probe=854163fb58) | Jan 10, 2022 |
| MSI           | A68HM GRENADE               | Desktop     | [0f44471905](https://linux-hardware.org/?probe=0f44471905) | Jan 10, 2022 |
| Gigabyte      | M52S-S3P                    | Desktop     | [5bdd85e9b5](https://linux-hardware.org/?probe=5bdd85e9b5) | Jan 10, 2022 |
| Medion        | E2292                       | Convertible | [b3b81f7289](https://linux-hardware.org/?probe=b3b81f7289) | Jan 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [053236f8c0](https://linux-hardware.org/?probe=053236f8c0) | Jan 09, 2022 |
| System76      | Galago Pro                  | Notebook    | [1295378270](https://linux-hardware.org/?probe=1295378270) | Jan 09, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [f3ebd22f2f](https://linux-hardware.org/?probe=f3ebd22f2f) | Jan 08, 2022 |
| Wortmann      | TERRA_PC                    | Desktop     | [16239fb870](https://linux-hardware.org/?probe=16239fb870) | Jan 08, 2022 |
| ASRock        | G31M-S                      | Desktop     | [30212e6fd6](https://linux-hardware.org/?probe=30212e6fd6) | Jan 08, 2022 |
| HP            | G62                         | Notebook    | [aacfc1cff1](https://linux-hardware.org/?probe=aacfc1cff1) | Jan 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0c29e5ae78](https://linux-hardware.org/?probe=0c29e5ae78) | Jan 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| Acer          | Aspire 1510                 | Notebook    | [26c825b4a7](https://linux-hardware.org/?probe=26c825b4a7) | Jan 07, 2022 |
| MSI           | H61M-P25                    | Desktop     | [f5060a86a8](https://linux-hardware.org/?probe=f5060a86a8) | Jan 07, 2022 |
| ASUSTek       | All Series                  | Notebook    | [951c8c3ffc](https://linux-hardware.org/?probe=951c8c3ffc) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [53e9ec174a](https://linux-hardware.org/?probe=53e9ec174a) | Jan 06, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [6ef0cffa6b](https://linux-hardware.org/?probe=6ef0cffa6b) | Jan 06, 2022 |
| HP            | 8309                        | Desktop     | [3cee70d4fc](https://linux-hardware.org/?probe=3cee70d4fc) | Jan 06, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [2cb2bbbfc6](https://linux-hardware.org/?probe=2cb2bbbfc6) | Jan 06, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [42710e0964](https://linux-hardware.org/?probe=42710e0964) | Jan 06, 2022 |
| Dell          | XPS L521X                   | Notebook    | [204c990a51](https://linux-hardware.org/?probe=204c990a51) | Jan 06, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [c4aed880fb](https://linux-hardware.org/?probe=c4aed880fb) | Jan 05, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7a0e13a7c1](https://linux-hardware.org/?probe=7a0e13a7c1) | Jan 05, 2022 |
| Dell          | Latitude 3301               | Notebook    | [e00b2dbfbc](https://linux-hardware.org/?probe=e00b2dbfbc) | Jan 05, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [b34e6337ae](https://linux-hardware.org/?probe=b34e6337ae) | Jan 05, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [073f2c3d43](https://linux-hardware.org/?probe=073f2c3d43) | Jan 05, 2022 |
| HP            | ProBook 4530s               | Notebook    | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | Notebook    | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b6c0836e89](https://linux-hardware.org/?probe=b6c0836e89) | Jan 04, 2022 |
| HP            | 635                         | Notebook    | [aafd01b4db](https://linux-hardware.org/?probe=aafd01b4db) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001DPB     | Notebook    | [cb0f7db023](https://linux-hardware.org/?probe=cb0f7db023) | Jan 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [665bf5dae7](https://linux-hardware.org/?probe=665bf5dae7) | Jan 04, 2022 |
| HP            | Pavilion m6                 | Notebook    | [be191c0d05](https://linux-hardware.org/?probe=be191c0d05) | Jan 04, 2022 |
| Gateway       | DX4320                      | Desktop     | [64fc897aa2](https://linux-hardware.org/?probe=64fc897aa2) | Jan 04, 2022 |
| MSI           | 880G-E45                    | Desktop     | [b45f683278](https://linux-hardware.org/?probe=b45f683278) | Jan 04, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [95f33224e9](https://linux-hardware.org/?probe=95f33224e9) | Jan 04, 2022 |
| ASUSTek       | H81T                        | Desktop     | [fb5cc5d8e3](https://linux-hardware.org/?probe=fb5cc5d8e3) | Jan 03, 2022 |
| Sony          | VGN-NW2SRF_S                | Notebook    | [e1e99e3e88](https://linux-hardware.org/?probe=e1e99e3e88) | Jan 03, 2022 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [7b813765f3](https://linux-hardware.org/?probe=7b813765f3) | Jan 03, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [a1905b9b4a](https://linux-hardware.org/?probe=a1905b9b4a) | Jan 03, 2022 |
| ASUSTek       | CM1735                      | Desktop     | [92165700b1](https://linux-hardware.org/?probe=92165700b1) | Jan 02, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b4d1a18243](https://linux-hardware.org/?probe=b4d1a18243) | Jan 02, 2022 |
| Lenovo        | 3181 SDK0J40697 WIN 3305... | Mini pc     | [56f9a83d77](https://linux-hardware.org/?probe=56f9a83d77) | Jan 02, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [bc3cdc4e31](https://linux-hardware.org/?probe=bc3cdc4e31) | Jan 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [edfbd4eb1c](https://linux-hardware.org/?probe=edfbd4eb1c) | Jan 02, 2022 |
| HP            | Notebook                    | Notebook    | [48f175a513](https://linux-hardware.org/?probe=48f175a513) | Jan 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [393b7857f2](https://linux-hardware.org/?probe=393b7857f2) | Jan 02, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | Notebook    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b1e6f7cd7c](https://linux-hardware.org/?probe=b1e6f7cd7c) | Jan 01, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [616c133c6e](https://linux-hardware.org/?probe=616c133c6e) | Jan 01, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [2126000e67](https://linux-hardware.org/?probe=2126000e67) | Jan 01, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2a3dbdc07a](https://linux-hardware.org/?probe=2a3dbdc07a) | Jan 01, 2022 |
| eMachines     | E525                        | Notebook    | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [a073f421c1](https://linux-hardware.org/?probe=a073f421c1) | Jan 01, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [428a598475](https://linux-hardware.org/?probe=428a598475) | Dec 31, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [820456adab](https://linux-hardware.org/?probe=820456adab) | Dec 31, 2021 |
| HP            | 83E8                        | Desktop     | [c79a0cc45e](https://linux-hardware.org/?probe=c79a0cc45e) | Dec 31, 2021 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f7f99c478d](https://linux-hardware.org/?probe=f7f99c478d) | Dec 31, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [667da7e2b7](https://linux-hardware.org/?probe=667da7e2b7) | Dec 31, 2021 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| Dell          | Latitude E6230              | Notebook    | [45bd8ebfa3](https://linux-hardware.org/?probe=45bd8ebfa3) | Dec 31, 2021 |
| Toshiba       | Satellite C870D-119         | Notebook    | [2731f273f4](https://linux-hardware.org/?probe=2731f273f4) | Dec 30, 2021 |
| Samsung       | R540/SA41/E452              | Notebook    | [5e1fcfa3a5](https://linux-hardware.org/?probe=5e1fcfa3a5) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| ASRock        | 945GCM-S                    | Desktop     | [b089710f53](https://linux-hardware.org/?probe=b089710f53) | Dec 30, 2021 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [428d5b007d](https://linux-hardware.org/?probe=428d5b007d) | Dec 30, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [da7dd95049](https://linux-hardware.org/?probe=da7dd95049) | Dec 29, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b699cbc873](https://linux-hardware.org/?probe=b699cbc873) | Dec 29, 2021 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [395d599207](https://linux-hardware.org/?probe=395d599207) | Dec 29, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [8806a9db07](https://linux-hardware.org/?probe=8806a9db07) | Dec 29, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [204ffe4516](https://linux-hardware.org/?probe=204ffe4516) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | Desktop     | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [3550171788](https://linux-hardware.org/?probe=3550171788) | Dec 29, 2021 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [f87be438d3](https://linux-hardware.org/?probe=f87be438d3) | Dec 29, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [50ccc07d3e](https://linux-hardware.org/?probe=50ccc07d3e) | Dec 29, 2021 |
| Biostar       | A960D+V2                    | Desktop     | [447fc7af58](https://linux-hardware.org/?probe=447fc7af58) | Dec 29, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [aad84241ca](https://linux-hardware.org/?probe=aad84241ca) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [461677d69d](https://linux-hardware.org/?probe=461677d69d) | Dec 28, 2021 |
| ASRock        | H61MV-ITX                   | Desktop     | [be772b3f4a](https://linux-hardware.org/?probe=be772b3f4a) | Dec 28, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [509959fdd1](https://linux-hardware.org/?probe=509959fdd1) | Dec 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [0f2350ed15](https://linux-hardware.org/?probe=0f2350ed15) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | Desktop     | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [8b9308b9a4](https://linux-hardware.org/?probe=8b9308b9a4) | Dec 28, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [6587985fe7](https://linux-hardware.org/?probe=6587985fe7) | Dec 28, 2021 |
| MSI           | A68HM GRENADE               | Desktop     | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| ASUSTek       | X45U                        | Notebook    | [55d2da3313](https://linux-hardware.org/?probe=55d2da3313) | Dec 27, 2021 |
| Sony          | SVT11125CBS                 | Notebook    | [961f242a60](https://linux-hardware.org/?probe=961f242a60) | Dec 27, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [e3c3ae36a2](https://linux-hardware.org/?probe=e3c3ae36a2) | Dec 27, 2021 |
| HP            | 0AA0h                       | Desktop     | [8786bc36f4](https://linux-hardware.org/?probe=8786bc36f4) | Dec 27, 2021 |
| HP            | EliteBook 8740w             | Notebook    | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| ZOTAC         | H55                         | Desktop     | [08e8c1aff2](https://linux-hardware.org/?probe=08e8c1aff2) | Dec 27, 2021 |
| HP            | Notebook                    | Notebook    | [d496159ad3](https://linux-hardware.org/?probe=d496159ad3) | Dec 26, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [28aad352f5](https://linux-hardware.org/?probe=28aad352f5) | Dec 26, 2021 |
| Dell          | Inspiron 3451               | Notebook    | [d0340265ee](https://linux-hardware.org/?probe=d0340265ee) | Dec 26, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [24ba3bb7a0](https://linux-hardware.org/?probe=24ba3bb7a0) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | Notebook    | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [4c00491c87](https://linux-hardware.org/?probe=4c00491c87) | Dec 25, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [f06229224a](https://linux-hardware.org/?probe=f06229224a) | Dec 25, 2021 |
| LEADER        | NH5BT11                     | Notebook    | [763efa7eb2](https://linux-hardware.org/?probe=763efa7eb2) | Dec 25, 2021 |
| HP            | 650                         | Notebook    | [339ab3e2d2](https://linux-hardware.org/?probe=339ab3e2d2) | Dec 25, 2021 |
| Lenovo        | ThinkPad T500 2087A75       | Notebook    | [6a1f2d337c](https://linux-hardware.org/?probe=6a1f2d337c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [840f7b0eff](https://linux-hardware.org/?probe=840f7b0eff) | Dec 25, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| Dell          | Inspiron 3451               | Notebook    | [73576a9684](https://linux-hardware.org/?probe=73576a9684) | Dec 24, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8e6899196e](https://linux-hardware.org/?probe=8e6899196e) | Dec 24, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [bf8476146c](https://linux-hardware.org/?probe=bf8476146c) | Dec 24, 2021 |
| Acer          | Extensa 215-51K             | Notebook    | [eb7ebb463b](https://linux-hardware.org/?probe=eb7ebb463b) | Dec 23, 2021 |
| Toshiba       | Satellite L355              | Notebook    | [63c919a1ed](https://linux-hardware.org/?probe=63c919a1ed) | Dec 23, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2797b5bd37](https://linux-hardware.org/?probe=2797b5bd37) | Dec 23, 2021 |
| MSI           | 0A90                        | Desktop     | [b08d40599d](https://linux-hardware.org/?probe=b08d40599d) | Dec 23, 2021 |
| Gigabyte      | MJPLNCB-00                  | Desktop     | [fe81720eae](https://linux-hardware.org/?probe=fe81720eae) | Dec 23, 2021 |
| Fujitsu       | FMVNA7BEC                   | Notebook    | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [4b36ec9c1a](https://linux-hardware.org/?probe=4b36ec9c1a) | Dec 23, 2021 |
| ASRock        | Q1900M                      | Desktop     | [627eef9622](https://linux-hardware.org/?probe=627eef9622) | Dec 22, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [a6fc4a2adb](https://linux-hardware.org/?probe=a6fc4a2adb) | Dec 22, 2021 |
| HP            | 198E                        | Desktop     | [bb9b36a65b](https://linux-hardware.org/?probe=bb9b36a65b) | Dec 22, 2021 |
| HP            | 2B47                        | Desktop     | [64a4b36df8](https://linux-hardware.org/?probe=64a4b36df8) | Dec 22, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [2c859e7444](https://linux-hardware.org/?probe=2c859e7444) | Dec 22, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [146165d8d1](https://linux-hardware.org/?probe=146165d8d1) | Dec 22, 2021 |
| Lenovo        | M30-70 20446                | Notebook    | [127f503834](https://linux-hardware.org/?probe=127f503834) | Dec 22, 2021 |
| Biostar       | A68N-5600E                  | Desktop     | [9ed7856f41](https://linux-hardware.org/?probe=9ed7856f41) | Dec 22, 2021 |
| Dell          | Latitude E6510              | Notebook    | [e637c26490](https://linux-hardware.org/?probe=e637c26490) | Dec 21, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [729cb86592](https://linux-hardware.org/?probe=729cb86592) | Dec 21, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d9ca1d1db](https://linux-hardware.org/?probe=5d9ca1d1db) | Dec 21, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | Notebook    | [0b0d4dd23f](https://linux-hardware.org/?probe=0b0d4dd23f) | Dec 21, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [e589fbcecc](https://linux-hardware.org/?probe=e589fbcecc) | Dec 20, 2021 |
| HP            | 8158 A01                    | Mini pc     | [85ef8f7dba](https://linux-hardware.org/?probe=85ef8f7dba) | Dec 20, 2021 |
| Dell          | G5 5590                     | Notebook    | [d548c52867](https://linux-hardware.org/?probe=d548c52867) | Dec 20, 2021 |
| Itautec       | AL 2022 AL 2022 Padrao 0... | All in one  | [9defc41ed2](https://linux-hardware.org/?probe=9defc41ed2) | Dec 20, 2021 |
| eMachines     | Unknown                     | Notebook    | [6b9767faba](https://linux-hardware.org/?probe=6b9767faba) | Dec 20, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [dd3539200c](https://linux-hardware.org/?probe=dd3539200c) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [899ca3371c](https://linux-hardware.org/?probe=899ca3371c) | Dec 20, 2021 |
| Acer          | TP-W701P-53334G1            | Notebook    | [674f2996b5](https://linux-hardware.org/?probe=674f2996b5) | Dec 19, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [61993c502d](https://linux-hardware.org/?probe=61993c502d) | Dec 19, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [af2a2e4db9](https://linux-hardware.org/?probe=af2a2e4db9) | Dec 19, 2021 |
| HP            | Notebook                    | Notebook    | [5aaca3e01e](https://linux-hardware.org/?probe=5aaca3e01e) | Dec 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [90575747f7](https://linux-hardware.org/?probe=90575747f7) | Dec 18, 2021 |
| Dell          | 0478VN A00                  | Desktop     | [67955910cb](https://linux-hardware.org/?probe=67955910cb) | Dec 18, 2021 |
| ASUSTek       | P5B-MX/WiFi-AP              | Desktop     | [97a556a1b1](https://linux-hardware.org/?probe=97a556a1b1) | Dec 18, 2021 |
| Dell          | 0J468K A00                  | Desktop     | [8233d2b0d6](https://linux-hardware.org/?probe=8233d2b0d6) | Dec 18, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [19694f0921](https://linux-hardware.org/?probe=19694f0921) | Dec 18, 2021 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fda86b8b4a](https://linux-hardware.org/?probe=fda86b8b4a) | Dec 18, 2021 |
| Toshiba       | Satellite C855D             | Notebook    | [daee1ba27b](https://linux-hardware.org/?probe=daee1ba27b) | Dec 18, 2021 |
| Samsung       | 550XDA                      | Notebook    | [6b3fd04b47](https://linux-hardware.org/?probe=6b3fd04b47) | Dec 18, 2021 |
| Dell          | Inspiron 3451               | Notebook    | [bd37d8fdf8](https://linux-hardware.org/?probe=bd37d8fdf8) | Dec 18, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [3854ed74f2](https://linux-hardware.org/?probe=3854ed74f2) | Dec 17, 2021 |
| Sony          | VPCEF3E1E                   | Notebook    | [f26bff938f](https://linux-hardware.org/?probe=f26bff938f) | Dec 17, 2021 |
| HP            | 0A00h                       | Desktop     | [56585a2839](https://linux-hardware.org/?probe=56585a2839) | Dec 17, 2021 |
| MSI           | G31TM-P35                   | Desktop     | [320ad12871](https://linux-hardware.org/?probe=320ad12871) | Dec 17, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [972c765b35](https://linux-hardware.org/?probe=972c765b35) | Dec 17, 2021 |
| MSI           | 2AE0                        | Desktop     | [f40b9dbbbe](https://linux-hardware.org/?probe=f40b9dbbbe) | Dec 16, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [52dca5cabc](https://linux-hardware.org/?probe=52dca5cabc) | Dec 16, 2021 |
| ASUSTek       | K53SJ                       | Notebook    | [1ffcc2cfda](https://linux-hardware.org/?probe=1ffcc2cfda) | Dec 16, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| Positivo      | S14BW01                     | Notebook    | [94de31910c](https://linux-hardware.org/?probe=94de31910c) | Dec 16, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [64d0453982](https://linux-hardware.org/?probe=64d0453982) | Dec 15, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [061faf00df](https://linux-hardware.org/?probe=061faf00df) | Dec 15, 2021 |
| ASUSTek       | H81-GAMER                   | Desktop     | [74658e6a83](https://linux-hardware.org/?probe=74658e6a83) | Dec 15, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | Notebook    | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [81c28c074e](https://linux-hardware.org/?probe=81c28c074e) | Dec 14, 2021 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [4575aea29e](https://linux-hardware.org/?probe=4575aea29e) | Dec 14, 2021 |
| Acer          | Aspire A315-54K             | Notebook    | [56741904bd](https://linux-hardware.org/?probe=56741904bd) | Dec 13, 2021 |
| ASUSTek       | UL30A                       | Notebook    | [3f3677f6ee](https://linux-hardware.org/?probe=3f3677f6ee) | Dec 13, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| HP            | 18E9                        | Desktop     | [870f4a67a7](https://linux-hardware.org/?probe=870f4a67a7) | Dec 13, 2021 |
| MSI           | A88XM-E35 V2                | Desktop     | [ecd99b833d](https://linux-hardware.org/?probe=ecd99b833d) | Dec 13, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Dell          | 0HJ781                      | Desktop     | [acac78cc8a](https://linux-hardware.org/?probe=acac78cc8a) | Dec 12, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [3cbe6d3002](https://linux-hardware.org/?probe=3cbe6d3002) | Dec 12, 2021 |
| Pegatron      | Benicia                     | Desktop     | [500489691f](https://linux-hardware.org/?probe=500489691f) | Dec 11, 2021 |
| Lenovo        | Unknown                     | Convertible | [fac9e252e4](https://linux-hardware.org/?probe=fac9e252e4) | Dec 11, 2021 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [d533c4790e](https://linux-hardware.org/?probe=d533c4790e) | Dec 10, 2021 |
| HP            | Pavilion 15                 | Notebook    | [99645415a4](https://linux-hardware.org/?probe=99645415a4) | Dec 10, 2021 |
| Lenovo        | ThinkPad T410 2537Z7A       | Notebook    | [d6ddba3925](https://linux-hardware.org/?probe=d6ddba3925) | Dec 10, 2021 |
| Sony          | SVE1513B1EW                 | Notebook    | [094d9138e5](https://linux-hardware.org/?probe=094d9138e5) | Dec 10, 2021 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | Notebook    | [e5a940ffdf](https://linux-hardware.org/?probe=e5a940ffdf) | Dec 10, 2021 |
| HP            | 0A54h                       | Desktop     | [417e076869](https://linux-hardware.org/?probe=417e076869) | Dec 10, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3b955f362a](https://linux-hardware.org/?probe=3b955f362a) | Dec 10, 2021 |
| Toshiba       | TE5                         | Notebook    | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [bc8f942a1a](https://linux-hardware.org/?probe=bc8f942a1a) | Dec 10, 2021 |
| LG Electro... | A410-G.BC49P1               | Notebook    | [5f952dc625](https://linux-hardware.org/?probe=5f952dc625) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | Notebook    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [730046deb9](https://linux-hardware.org/?probe=730046deb9) | Dec 09, 2021 |
| eMachines     | D520 V1.04                  | Notebook    | [932e776d87](https://linux-hardware.org/?probe=932e776d87) | Dec 08, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [fe423d9f2d](https://linux-hardware.org/?probe=fe423d9f2d) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9df7c17faf](https://linux-hardware.org/?probe=9df7c17faf) | Dec 08, 2021 |
| Acer          | M945G                       | Desktop     | [5c72066083](https://linux-hardware.org/?probe=5c72066083) | Dec 08, 2021 |
| HP            | 620                         | Notebook    | [7612676b9a](https://linux-hardware.org/?probe=7612676b9a) | Dec 08, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [96f8dadd49](https://linux-hardware.org/?probe=96f8dadd49) | Dec 08, 2021 |
| Biostar       | NF520-A2 TE                 | Desktop     | [5878187120](https://linux-hardware.org/?probe=5878187120) | Dec 07, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [e96b1f7f6b](https://linux-hardware.org/?probe=e96b1f7f6b) | Dec 07, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [319b95b99d](https://linux-hardware.org/?probe=319b95b99d) | Dec 07, 2021 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [db3905e629](https://linux-hardware.org/?probe=db3905e629) | Dec 07, 2021 |
| Dell          | Inspiron 7773               | Notebook    | [2f7c3c0c0b](https://linux-hardware.org/?probe=2f7c3c0c0b) | Dec 07, 2021 |
| OEM           | B75                         | Desktop     | [d6a1e29a32](https://linux-hardware.org/?probe=d6a1e29a32) | Dec 07, 2021 |
| eMachines     | E525                        | Notebook    | [eb1ee3fb6c](https://linux-hardware.org/?probe=eb1ee3fb6c) | Dec 07, 2021 |
| MSI           | H61M-P20                    | Desktop     | [614ffcb196](https://linux-hardware.org/?probe=614ffcb196) | Dec 07, 2021 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [add6c240f9](https://linux-hardware.org/?probe=add6c240f9) | Dec 07, 2021 |
| Huanan        | B85                         | Desktop     | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Chuwi         | LapBook Pro                 | Notebook    | [ad5d162393](https://linux-hardware.org/?probe=ad5d162393) | Dec 06, 2021 |
| Gateway       | DT55                        | Desktop     | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| Positivo      | J14AL11                     | Notebook    | [2e5fd22945](https://linux-hardware.org/?probe=2e5fd22945) | Dec 06, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [5a00aff0fc](https://linux-hardware.org/?probe=5a00aff0fc) | Dec 06, 2021 |
| Unknown       | Phitronics PN73PVS-M        | Desktop     | [f64b92d5b2](https://linux-hardware.org/?probe=f64b92d5b2) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [17c270ac38](https://linux-hardware.org/?probe=17c270ac38) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Acer          | Aspire E1-421               | Notebook    | [a7c18d534d](https://linux-hardware.org/?probe=a7c18d534d) | Dec 06, 2021 |
| RM            | NOTEBOOK 320                | Notebook    | [6998aef680](https://linux-hardware.org/?probe=6998aef680) | Dec 06, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | Notebook    | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| HP            | Notebook                    | Notebook    | [d7c2bef552](https://linux-hardware.org/?probe=d7c2bef552) | Dec 05, 2021 |
| Dell          | Latitude E6430              | Notebook    | [eee07229a4](https://linux-hardware.org/?probe=eee07229a4) | Dec 05, 2021 |
| Dell          | Latitude E6410              | Notebook    | [07ca5fc75a](https://linux-hardware.org/?probe=07ca5fc75a) | Dec 05, 2021 |
| ASUSTek       | K84L                        | Notebook    | [dce2044275](https://linux-hardware.org/?probe=dce2044275) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | Notebook    | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| HP            | Pavilion g7                 | Notebook    | [795980ab4c](https://linux-hardware.org/?probe=795980ab4c) | Dec 04, 2021 |
| Gigabyte      | Z590 VISION G               | Desktop     | [51e33fc095](https://linux-hardware.org/?probe=51e33fc095) | Dec 03, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [89a5a0d5ac](https://linux-hardware.org/?probe=89a5a0d5ac) | Dec 03, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [b71a9c285d](https://linux-hardware.org/?probe=b71a9c285d) | Dec 03, 2021 |
| Medion        | E2292                       | Convertible | [956ff1bc48](https://linux-hardware.org/?probe=956ff1bc48) | Dec 03, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [5df988dd63](https://linux-hardware.org/?probe=5df988dd63) | Dec 03, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [615600f1dc](https://linux-hardware.org/?probe=615600f1dc) | Dec 03, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [bbdfd3b78e](https://linux-hardware.org/?probe=bbdfd3b78e) | Dec 02, 2021 |
| Medion        | Akoya E1317T                | Notebook    | [0d8103d7b7](https://linux-hardware.org/?probe=0d8103d7b7) | Dec 02, 2021 |
| Positivo      | H14BT58                     | Notebook    | [7e692b3a7a](https://linux-hardware.org/?probe=7e692b3a7a) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| MSI           | GE72 2QC                    | Notebook    | [db92825225](https://linux-hardware.org/?probe=db92825225) | Dec 02, 2021 |
| Philco        | 14F                         | Notebook    | [ab69e64295](https://linux-hardware.org/?probe=ab69e64295) | Dec 02, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f69fadfb4b](https://linux-hardware.org/?probe=f69fadfb4b) | Dec 01, 2021 |
| Dell          | Latitude E6510              | Notebook    | [cef6e43321](https://linux-hardware.org/?probe=cef6e43321) | Dec 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [ca8a5a1ea8](https://linux-hardware.org/?probe=ca8a5a1ea8) | Dec 01, 2021 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [13325b986f](https://linux-hardware.org/?probe=13325b986f) | Dec 01, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [ddcca3f92c](https://linux-hardware.org/?probe=ddcca3f92c) | Dec 01, 2021 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [89046e697d](https://linux-hardware.org/?probe=89046e697d) | Nov 30, 2021 |
| ASUSTek       | M2N                         | Desktop     | [8f674fd086](https://linux-hardware.org/?probe=8f674fd086) | Nov 30, 2021 |
| HP            | 2215                        | Desktop     | [a9a43dfbe0](https://linux-hardware.org/?probe=a9a43dfbe0) | Nov 30, 2021 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | Desktop     | [25d7f6e054](https://linux-hardware.org/?probe=25d7f6e054) | Nov 30, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [59da226d80](https://linux-hardware.org/?probe=59da226d80) | Nov 30, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [c935a13f9f](https://linux-hardware.org/?probe=c935a13f9f) | Nov 29, 2021 |
| Intel         | H61                         | Desktop     | [e4a2b68a1b](https://linux-hardware.org/?probe=e4a2b68a1b) | Nov 29, 2021 |
| ASRock        | FM2A78M-DG3+                | Desktop     | [72dfdf487b](https://linux-hardware.org/?probe=72dfdf487b) | Nov 29, 2021 |
| Sony          | VPCEB1E9R                   | Notebook    | [28655d3e4d](https://linux-hardware.org/?probe=28655d3e4d) | Nov 29, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | Notebook    | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [30820af902](https://linux-hardware.org/?probe=30820af902) | Nov 29, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.2/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 4584      | 94.87%  |
| 5.11.12-desktop-1omv4002       | 219       | 4.53%   |
| 5.11.0-desktop-clang-1omv4002  | 10        | 0.21%   |
| 5.10.13-desktop-1omv4002       | 4         | 0.08%   |
| 5.9.12-desktop-1omv4002        | 2         | 0.04%   |
| 5.8.13-desktop-clang-1omv4002  | 1         | 0.02%   |
| 5.8.13-desktop-1omv4002        | 1         | 0.02%   |
| 5.16.13-desktop-1omv4003       | 1         | 0.02%   |
| 5.11.1-desktop-74.1.1bomv4002  | 1         | 0.02%   |
| 5.11.0-desktop-1omv4002        | 1         | 0.02%   |
| 5.11.0-desktop-0.rc4.1omv4002  | 1         | 0.02%   |
| 5.10.9-desktop-1omv4002        | 1         | 0.02%   |
| 5.10.7-desktop-1omv4002        | 1         | 0.02%   |
| 5.10.3-desktop-2omv4002        | 1         | 0.02%   |
| 5.10.2-desktop-clang-1omv4002  | 1         | 0.02%   |
| 5.10.15-desktop-1omv4002       | 1         | 0.02%   |
| 5.10.12-desktop-clang-1omv4002 | 1         | 0.02%   |
| Unknown                        | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.14 | 4584      | 94.87%  |
| 5.11.12 | 219       | 4.53%   |
| 5.11.0  | 12        | 0.25%   |
| 5.10.13 | 4         | 0.08%   |
| 5.9.12  | 2         | 0.04%   |
| 5.8.13  | 2         | 0.04%   |
| 5.16.13 | 1         | 0.02%   |
| 5.11.1  | 1         | 0.02%   |
| 5.10.9  | 1         | 0.02%   |
| 5.10.7  | 1         | 0.02%   |
| 5.10.3  | 1         | 0.02%   |
| 5.10.2  | 1         | 0.02%   |
| 5.10.15 | 1         | 0.02%   |
| 5.10.12 | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4594      | 95.07%  |
| 5.11    | 232       | 4.8%    |
| 5.9     | 2         | 0.04%   |
| 5.8     | 2         | 0.04%   |
| 5.16    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4758      | 99.98%  |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 4751      | 99.79%  |
| LXQt     | 3         | 0.06%   |
| Unknown  | 3         | 0.06%   |
| Cinnamon | 2         | 0.04%   |
| KDE      | 1         | 0.02%   |
| GNOME    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4738      | 99.56%  |
| Wayland | 20        | 0.42%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 4757      | 99.96%  |
| Unknown | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2395      | 49.89%  |
| de_DE   | 398       | 8.29%   |
| ru_RU   | 324       | 6.75%   |
| fr_FR   | 318       | 6.62%   |
| pl_PL   | 228       | 4.75%   |
| pt_BR   | 211       | 4.39%   |
| es_ES   | 137       | 2.85%   |
| it_IT   | 134       | 2.79%   |
| cs_CZ   | 95        | 1.98%   |
| en_GB   | 81        | 1.69%   |
| es_MX   | 47        | 0.98%   |
| es_AR   | 43        | 0.9%    |
| hu_HU   | 36        | 0.75%   |
| de_AT   | 28        | 0.58%   |
| nl_NL   | 24        | 0.5%    |
| en_AU   | 24        | 0.5%    |
| ru_UA   | 18        | 0.37%   |
| fr_BE   | 17        | 0.35%   |
| fr_CA   | 16        | 0.33%   |
| es_CO   | 14        | 0.29%   |
| da_DK   | 14        | 0.29%   |
| ro_RO   | 13        | 0.27%   |
| es_CL   | 13        | 0.27%   |
| de_CH   | 13        | 0.27%   |
| pt_PT   | 12        | 0.25%   |
| en_CA   | 12        | 0.25%   |
| en_IN   | 11        | 0.23%   |
| nl_BE   | 10        | 0.21%   |
| fr_CH   | 9         | 0.19%   |
| es_VE   | 8         | 0.17%   |
| en_HK   | 8         | 0.17%   |
| it_CH   | 7         | 0.15%   |
| es_PE   | 7         | 0.15%   |
| uk_UA   | 6         | 0.12%   |
| nb_NO   | 6         | 0.12%   |
| Unknown | 6         | 0.12%   |
| en_ZA   | 5         | 0.1%    |
| en_NZ   | 5         | 0.1%    |
| en_IL   | 5         | 0.1%    |
| es_SV   | 4         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2896      | 60.69%  |
| EFI  | 1876      | 39.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 3784      | 78.04%  |
| Ext4     | 1009      | 20.81%  |
| Btrfs    | 29        | 0.6%    |
| F2fs     | 7         | 0.14%   |
| Ext3     | 6         | 0.12%   |
| Ext2     | 6         | 0.12%   |
| Xfs      | 4         | 0.08%   |
| Jfs      | 2         | 0.04%   |
| Reiserfs | 1         | 0.02%   |
| Unknown  | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2714      | 56.68%  |
| MBR     | 2058      | 42.98%  |
| Unknown | 16        | 0.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2699      | 56.15%  |
| No        | 2108      | 43.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2502      | 52.38%  |
| Yes       | 2275      | 47.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 883       | 18.55%  |
| Hewlett-Packard     | 609       | 12.8%   |
| Lenovo              | 530       | 11.14%  |
| Dell                | 527       | 11.07%  |
| Gigabyte Technology | 419       | 8.8%    |
| Acer                | 328       | 6.89%   |
| MSI                 | 276       | 5.8%    |
| ASRock              | 211       | 4.43%   |
| Toshiba             | 123       | 2.58%   |
| Intel               | 89        | 1.87%   |
| Sony                | 67        | 1.41%   |
| Apple               | 62        | 1.3%    |
| Samsung Electronics | 60        | 1.26%   |
| Medion              | 56        | 1.18%   |
| Fujitsu             | 55        | 1.16%   |
| Pegatron            | 33        | 0.69%   |
| Biostar             | 32        | 0.67%   |
| Positivo            | 28        | 0.59%   |
| Foxconn             | 28        | 0.59%   |
| Packard Bell        | 27        | 0.57%   |
| Unknown             | 27        | 0.57%   |
| ECS                 | 20        | 0.42%   |
| eMachines           | 16        | 0.34%   |
| Philco              | 13        | 0.27%   |
| Notebook            | 13        | 0.27%   |
| HUAWEI              | 13        | 0.27%   |
| Fujitsu Siemens     | 13        | 0.27%   |
| Chuwi               | 9         | 0.19%   |
| Shuttle             | 8         | 0.17%   |
| LG Electronics      | 8         | 0.17%   |
| Gateway             | 8         | 0.17%   |
| Microsoft           | 7         | 0.15%   |
| Clevo               | 7         | 0.15%   |
| Timi                | 6         | 0.13%   |
| Supermicro          | 6         | 0.13%   |
| PCWare              | 6         | 0.13%   |
| ZOTAC               | 5         | 0.11%   |
| TUXEDO              | 5         | 0.11%   |
| System76            | 5         | 0.11%   |
| Panasonic           | 5         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUS All Series             | 56        | 1.18%   |
| ASUS UX31E                  | 44        | 0.92%   |
| Unknown                     | 43        | 0.9%    |
| Dell Inspiron 3451          | 32        | 0.67%   |
| Dell OptiPlex 780           | 25        | 0.53%   |
| HP Notebook                 | 24        | 0.5%    |
| Dell OptiPlex 7010          | 16        | 0.34%   |
| ASUS PRIME A320M-K          | 14        | 0.29%   |
| Medion E2292                | 13        | 0.27%   |
| HP Pavilion g6              | 13        | 0.27%   |
| Gigabyte 970A-DS3P          | 12        | 0.25%   |
| MSI MS-7817                 | 11        | 0.23%   |
| Gigabyte A320M-S2H          | 11        | 0.23%   |
| Dell Latitude E6430         | 11        | 0.23%   |
| HP Pavilion dv6             | 10        | 0.21%   |
| Gigabyte B450M DS3H         | 10        | 0.21%   |
| Dell Latitude D630          | 10        | 0.21%   |
| ASUS PRIME B450M-A          | 10        | 0.21%   |
| Intel H61                   | 9         | 0.19%   |
| HP EliteDesk 800 G1 SFF     | 9         | 0.19%   |
| HP Compaq Pro 6300 SFF      | 9         | 0.19%   |
| Dell OptiPlex 9020          | 9         | 0.19%   |
| Dell OptiPlex 3020          | 9         | 0.19%   |
| Toshiba Satellite A300      | 8         | 0.17%   |
| MSI MS-7721                 | 8         | 0.17%   |
| MSI MS-7641                 | 8         | 0.17%   |
| HP Compaq 8200 Elite SFF PC | 8         | 0.17%   |
| Gigabyte G31M-ES2L          | 8         | 0.17%   |
| Gigabyte B75M-D3H           | 8         | 0.17%   |
| Dell Latitude E6410         | 8         | 0.17%   |
| ASRock G31M-S               | 8         | 0.17%   |
| MSI MS-7C52                 | 7         | 0.15%   |
| HP Pavilion 15              | 7         | 0.15%   |
| HP EliteBook 8440p          | 7         | 0.15%   |
| Gigabyte H61M-DS2           | 7         | 0.15%   |
| Dell OptiPlex 790           | 7         | 0.15%   |
| Dell Latitude E6420         | 7         | 0.15%   |
| Dell Inspiron 15-3567       | 7         | 0.15%   |
| ASUS TUF Gaming X570-PLUS   | 7         | 0.15%   |
| ASUS P8Z77-V LX             | 7         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 246       | 5.17%   |
| Lenovo ThinkPad       | 169       | 3.55%   |
| Dell Inspiron         | 149       | 3.13%   |
| Dell Latitude         | 141       | 2.96%   |
| Dell OptiPlex         | 138       | 2.9%    |
| Lenovo IdeaPad        | 133       | 2.79%   |
| HP Compaq             | 111       | 2.33%   |
| HP Pavilion           | 101       | 2.12%   |
| Toshiba Satellite     | 100       | 2.1%    |
| ASUS PRIME            | 92        | 1.93%   |
| HP Laptop             | 58        | 1.22%   |
| Lenovo ThinkCentre    | 57        | 1.2%    |
| ASUS All              | 56        | 1.18%   |
| HP EliteBook          | 52        | 1.09%   |
| ASUS UX31E            | 44        | 0.92%   |
| Unknown               | 43        | 0.9%    |
| HP ProBook            | 42        | 0.88%   |
| ASUS ROG              | 38        | 0.8%    |
| Dell Vostro           | 30        | 0.63%   |
| Fujitsu ESPRIMO       | 28        | 0.59%   |
| ASUS VivoBook         | 28        | 0.59%   |
| ASUS TUF              | 28        | 0.59%   |
| HP EliteDesk          | 27        | 0.57%   |
| ASUS M5A78L-M         | 27        | 0.57%   |
| HP Notebook           | 24        | 0.5%    |
| Lenovo IdeaCentre     | 23        | 0.48%   |
| Dell Precision        | 23        | 0.48%   |
| ASUS P8Z77-V          | 21        | 0.44%   |
| ASUS P8H61-M          | 21        | 0.44%   |
| HP ProDesk            | 20        | 0.42%   |
| Fujitsu LIFEBOOK      | 20        | 0.42%   |
| Gigabyte B450M        | 19        | 0.4%    |
| Acer Extensa          | 19        | 0.4%    |
| Packard Bell EasyNote | 17        | 0.36%   |
| Acer TravelMate       | 17        | 0.36%   |
| HP ENVY               | 14        | 0.29%   |
| Gigabyte B450         | 14        | 0.29%   |
| Gigabyte A320M-S2H    | 14        | 0.29%   |
| Medion E2292          | 13        | 0.27%   |
| HP 250                | 12        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 525       | 11.03%  |
| 2011    | 514       | 10.8%   |
| 2013    | 412       | 8.66%   |
| 2014    | 380       | 7.98%   |
| 2010    | 366       | 7.69%   |
| 2008    | 319       | 6.7%    |
| 2018    | 316       | 6.64%   |
| 2019    | 305       | 6.41%   |
| 2009    | 291       | 6.11%   |
| 2017    | 290       | 6.09%   |
| 2015    | 262       | 5.51%   |
| 2016    | 230       | 4.83%   |
| 2020    | 213       | 4.48%   |
| 2007    | 183       | 3.85%   |
| 2021    | 65        | 1.37%   |
| 2006    | 62        | 1.3%    |
| 2005    | 16        | 0.34%   |
| 2004    | 6         | 0.13%   |
| Unknown | 2         | 0.04%   |
| 2023    | 1         | 0.02%   |
| 2022    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 2320      | 48.75%  |
| Notebook    | 2252      | 47.32%  |
| All in one  | 74        | 1.55%   |
| Mini pc     | 50        | 1.05%   |
| Convertible | 41        | 0.86%   |
| Tablet      | 15        | 0.32%   |
| Server      | 7         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4759      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4755      | 99.92%  |
| Yes  | 4         | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1555      | 32.56%  |
| 4.01-8.0        | 1181      | 24.73%  |
| 8.01-16.0       | 883       | 18.49%  |
| 16.01-24.0      | 604       | 12.65%  |
| 1.01-2.0        | 227       | 4.75%   |
| 32.01-64.0      | 180       | 3.77%   |
| 2.01-3.0        | 73        | 1.53%   |
| 24.01-32.0      | 38        | 0.8%    |
| 64.01-256.0     | 22        | 0.46%   |
| 0.51-1.0        | 11        | 0.23%   |
| More than 256.0 | 1         | 0.02%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3722      | 77.19%  |
| 0.51-1.0  | 678       | 14.06%  |
| 2.01-3.0  | 273       | 5.66%   |
| 0.01-0.5  | 121       | 2.51%   |
| 3.01-4.0  | 15        | 0.31%   |
| 4.01-8.0  | 10        | 0.21%   |
| 8.01-16.0 | 2         | 0.04%   |
| Unknown   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2965      | 62.03%  |
| 2      | 1093      | 22.87%  |
| 3      | 360       | 7.53%   |
| 4      | 162       | 3.39%   |
| 0      | 83        | 1.74%   |
| 5      | 65        | 1.36%   |
| 6      | 21        | 0.44%   |
| 7      | 16        | 0.33%   |
| 8      | 12        | 0.25%   |
| 9      | 2         | 0.04%   |
| 18     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2977      | 62.42%  |
| No        | 1792      | 37.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4498      | 94.52%  |
| No        | 261       | 5.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3137      | 65.83%  |
| No        | 1628      | 34.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2663      | 55.85%  |
| Yes       | 2105      | 44.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 582       | 12.22%  |
| USA          | 455       | 9.56%   |
| Russia       | 416       | 8.74%   |
| France       | 389       | 8.17%   |
| Brazil       | 345       | 7.25%   |
| Poland       | 318       | 6.68%   |
| Italy        | 223       | 4.68%   |
| Spain        | 190       | 3.99%   |
| UK           | 133       | 2.79%   |
| Czechia      | 118       | 2.48%   |
| Canada       | 118       | 2.48%   |
| Mexico       | 94        | 1.97%   |
| Ukraine      | 74        | 1.55%   |
| Hungary      | 59        | 1.24%   |
| Argentina    | 58        | 1.22%   |
| India        | 57        | 1.2%    |
| Australia    | 56        | 1.18%   |
| Netherlands  | 55        | 1.16%   |
| Romania      | 45        | 0.95%   |
| Belgium      | 45        | 0.95%   |
| Japan        | 41        | 0.86%   |
| Austria      | 41        | 0.86%   |
| Sweden       | 39        | 0.82%   |
| Portugal     | 37        | 0.78%   |
| Greece       | 37        | 0.78%   |
| Finland      | 33        | 0.69%   |
| Switzerland  | 32        | 0.67%   |
| Indonesia    | 32        | 0.67%   |
| Bulgaria     | 30        | 0.63%   |
| Slovakia     | 27        | 0.57%   |
| Serbia       | 26        | 0.55%   |
| Denmark      | 25        | 0.53%   |
| Belarus      | 24        | 0.5%    |
| Chile        | 23        | 0.48%   |
| Norway       | 20        | 0.42%   |
| China        | 20        | 0.42%   |
| Colombia     | 18        | 0.38%   |
| South Africa | 17        | 0.36%   |
| Thailand     | 16        | 0.34%   |
| Israel       | 16        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 70        | 1.45%   |
| Prague           | 60        | 1.24%   |
| Warsaw           | 50        | 1.04%   |
| Paris            | 41        | 0.85%   |
| Berlin           | 40        | 0.83%   |
| Krakow           | 39        | 0.81%   |
| St Petersburg    | 36        | 0.75%   |
| Sao Paulo        | 36        | 0.75%   |
| Rome             | 29        | 0.6%    |
| Milan            | 29        | 0.6%    |
| Mexico City      | 28        | 0.58%   |
| Rio de Janeiro   | 27        | 0.56%   |
| Munich           | 21        | 0.43%   |
| Stuttgart        | 18        | 0.37%   |
| Porto Alegre     | 18        | 0.37%   |
| Krasnodar        | 18        | 0.37%   |
| Helsinki         | 18        | 0.37%   |
| Vienna           | 17        | 0.35%   |
| Madrid           | 17        | 0.35%   |
| Yekaterinburg    | 16        | 0.33%   |
| Hamburg          | 16        | 0.33%   |
| Budapest         | 15        | 0.31%   |
| Wroclaw          | 14        | 0.29%   |
| Melbourne        | 14        | 0.29%   |
| Barcelona        | 14        | 0.29%   |
| Wettringen       | 13        | 0.27%   |
| Poznan           | 13        | 0.27%   |
| Nuremberg        | 13        | 0.27%   |
| Novosibirsk      | 13        | 0.27%   |
| Athens           | 13        | 0.27%   |
| Sydney           | 12        | 0.25%   |
| Buenos Aires     | 12        | 0.25%   |
| Queens           | 11        | 0.23%   |
| Mannheim         | 11        | 0.23%   |
| Lisbon           | 11        | 0.23%   |
| Cologne          | 11        | 0.23%   |
| Nizhniy Novgorod | 10        | 0.21%   |
| Montreal         | 10        | 0.21%   |
| Minsk            | 10        | 0.21%   |
| Limoges          | 10        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1332      | 1620   | 20.2%   |
| Seagate             | 1283      | 1529   | 19.46%  |
| Samsung Electronics | 742       | 904    | 11.25%  |
| Toshiba             | 524       | 568    | 7.95%   |
| Kingston            | 384       | 425    | 5.82%   |
| Hitachi             | 309       | 332    | 4.69%   |
| SanDisk             | 248       | 261    | 3.76%   |
| Crucial             | 235       | 269    | 3.56%   |
| Unknown             | 183       | 216    | 2.78%   |
| A-DATA Technology   | 119       | 130    | 1.8%    |
| HGST                | 111       | 122    | 1.68%   |
| Intel               | 94        | 108    | 1.43%   |
| China               | 67        | 72     | 1.02%   |
| SK hynix            | 61        | 63     | 0.93%   |
| GOODRAM             | 53        | 60     | 0.8%    |
| Intenso             | 51        | 57     | 0.77%   |
| Maxtor              | 49        | 54     | 0.74%   |
| Patriot             | 45        | 49     | 0.68%   |
| PNY                 | 43        | 45     | 0.65%   |
| SPCC                | 35        | 35     | 0.53%   |
| OCZ                 | 33        | 35     | 0.5%    |
| Fujitsu             | 33        | 33     | 0.5%    |
| Apple               | 29        | 35     | 0.44%   |
| Micron Technology   | 28        | 29     | 0.42%   |
| Apacer              | 28        | 30     | 0.42%   |
| JMicron Technology  | 25        | 26     | 0.38%   |
| Transcend           | 24        | 25     | 0.36%   |
| Phison              | 22        | 24     | 0.33%   |
| Hewlett-Packard     | 21        | 23     | 0.32%   |
| Corsair             | 19        | 22     | 0.29%   |
| Plextor             | 16        | 18     | 0.24%   |
| LITEON              | 13        | 13     | 0.2%    |
| LITEONIT            | 12        | 13     | 0.18%   |
| Team                | 11        | 12     | 0.17%   |
| KingSpec            | 11        | 11     | 0.17%   |
| Netac               | 9         | 9      | 0.14%   |
| KingDian            | 8         | 8      | 0.12%   |
| Unknown             | 8         | 8      | 0.12%   |
| Verbatim            | 7         | 10     | 0.11%   |
| SABRENT             | 7         | 9      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 87        | 1.21%   |
| Kingston SA400S37240G 240GB SSD     | 84        | 1.17%   |
| Seagate ST500LT012-1DG142 500GB     | 83        | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB      | 65        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 57        | 0.79%   |
| Toshiba DT01ACA100 1TB              | 56        | 0.78%   |
| Toshiba MQ01ABF050 500GB            | 49        | 0.68%   |
| Kingston SA400S37120G 120GB SSD     | 49        | 0.68%   |
| Samsung SSD 860 EVO 500GB           | 45        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 44        | 0.61%   |
| SanDisk SSD U100 256GB              | 44        | 0.61%   |
| Seagate ST3500418AS 500GB           | 42        | 0.58%   |
| Unknown SD/MMC/MS PRO 128GB         | 41        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD    | 41        | 0.57%   |
| Toshiba DT01ACA050 500GB            | 40        | 0.56%   |
| Kingston SA400S37480G 480GB SSD     | 40        | 0.56%   |
| Toshiba MQ01ABD100 1TB              | 39        | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB            | 36        | 0.5%    |
| Seagate ST9500325AS 500GB           | 34        | 0.47%   |
| Samsung SSD 850 EVO 250GB           | 34        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 33        | 0.46%   |
| Crucial CT240BX500SSD1 240GB        | 33        | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 31        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB      | 31        | 0.43%   |
| Toshiba HDWD110 1TB                 | 30        | 0.42%   |
| Samsung SSD 850 EVO 500GB           | 30        | 0.42%   |
| Samsung SSD 860 EVO 250GB           | 29        | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB            | 28        | 0.39%   |
| HGST HTS721010A9E630 1TB            | 28        | 0.39%   |
| Crucial CT500MX500SSD1 500GB        | 28        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 26        | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB      | 26        | 0.36%   |
| Toshiba MQ04ABF100 1TB              | 25        | 0.35%   |
| Seagate ST3500413AS 500GB           | 24        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB      | 24        | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB            | 23        | 0.32%   |
| Toshiba DT01ACA200 2TB              | 22        | 0.31%   |
| Seagate ST1000DM003-1SB102 1TB      | 22        | 0.31%   |
| HGST HTS545050A7E680 500GB          | 21        | 0.29%   |
| Seagate ST500LT012-9WS142 500GB     | 20        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1272      | 1514   | 34.39%  |
| WDC                 | 1130      | 1360   | 30.55%  |
| Toshiba             | 463       | 501    | 12.52%  |
| Hitachi             | 309       | 332    | 8.35%   |
| Samsung Electronics | 206       | 228    | 5.57%   |
| HGST                | 111       | 122    | 3%      |
| Maxtor              | 48        | 53     | 1.3%    |
| Unknown             | 42        | 42     | 1.14%   |
| Fujitsu             | 33        | 33     | 0.89%   |
| JMicron Technology  | 16        | 16     | 0.43%   |
| Apple               | 15        | 16     | 0.41%   |
| SABRENT             | 6         | 8      | 0.16%   |
| Hewlett-Packard     | 6         | 6      | 0.16%   |
| ASMT                | 6         | 6      | 0.16%   |
| External            | 5         | 5      | 0.14%   |
| WD MediaMax         | 4         | 5      | 0.11%   |
| TO Exter            | 3         | 3      | 0.08%   |
| Quantum             | 3         | 3      | 0.08%   |
| IBM/Hitachi         | 3         | 3      | 0.08%   |
| MDT                 | 2         | 2      | 0.05%   |
| ExcelStor           | 2         | 2      | 0.05%   |
| ASMedia             | 2         | 2      | 0.05%   |
| USB                 | 1         | 1      | 0.03%   |
| TPH00800640GB       | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| IB                  | 1         | 2      | 0.03%   |
| HPE                 | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| FC-1307             | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| ASMT106x            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 408       | 479    | 17.89%  |
| Kingston            | 343       | 377    | 15.04%  |
| SanDisk             | 235       | 246    | 10.3%   |
| Crucial             | 210       | 241    | 9.21%   |
| WDC                 | 160       | 167    | 7.01%   |
| A-DATA Technology   | 109       | 119    | 4.78%   |
| China               | 66        | 71     | 2.89%   |
| GOODRAM             | 52        | 59     | 2.28%   |
| Intenso             | 49        | 55     | 2.15%   |
| Intel               | 49        | 54     | 2.15%   |
| Toshiba             | 46        | 48     | 2.02%   |
| Patriot             | 42        | 46     | 1.84%   |
| PNY                 | 41        | 43     | 1.8%    |
| OCZ                 | 33        | 35     | 1.45%   |
| SK hynix            | 30        | 31     | 1.32%   |
| SPCC                | 29        | 29     | 1.27%   |
| Apacer              | 26        | 28     | 1.14%   |
| Transcend           | 23        | 24     | 1.01%   |
| Unknown             | 22        | 23     | 0.96%   |
| Micron Technology   | 22        | 23     | 0.96%   |
| Plextor             | 14        | 16     | 0.61%   |
| LITEONIT            | 12        | 13     | 0.53%   |
| Hewlett-Packard     | 12        | 12     | 0.53%   |
| Corsair             | 12        | 14     | 0.53%   |
| LITEON              | 11        | 11     | 0.48%   |
| KingSpec            | 11        | 11     | 0.48%   |
| Apple               | 11        | 11     | 0.48%   |
| Team                | 10        | 11     | 0.44%   |
| Netac               | 9         | 9      | 0.39%   |
| KingDian            | 8         | 8      | 0.35%   |
| Verbatim            | 7         | 10     | 0.31%   |
| Colorful            | 7         | 7      | 0.31%   |
| Seagate             | 6         | 6      | 0.26%   |
| Unknown             | 6         | 6      | 0.26%   |
| XrayDisk            | 5         | 5      | 0.22%   |
| Teclast             | 5         | 5      | 0.22%   |
| Leven               | 5         | 5      | 0.22%   |
| KingFast            | 5         | 5      | 0.22%   |
| Gigabyte Technology | 5         | 5      | 0.22%   |
| INNOVATION IT       | 4         | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3127      | 4275   | 53.9%   |
| SSD     | 2002      | 2496   | 34.51%  |
| NVMe    | 500       | 605    | 8.62%   |
| MMC     | 124       | 136    | 2.14%   |
| Unknown | 49        | 71     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4356      | 6545   | 83.5%   |
| NVMe | 500       | 599    | 9.58%   |
| SAS  | 237       | 303    | 4.54%   |
| MMC  | 124       | 136    | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3476      | 4531   | 65.3%   |
| 0.51-1.0   | 1343      | 1609   | 25.23%  |
| 1.01-2.0   | 321       | 399    | 6.03%   |
| 2.01-3.0   | 69        | 89     | 1.3%    |
| 3.01-4.0   | 67        | 88     | 1.26%   |
| 4.01-10.0  | 39        | 47     | 0.73%   |
| 10.01-20.0 | 8         | 8      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2362      | 48.66%  |
| Unknown        | 676       | 13.93%  |
| 101-250        | 658       | 13.56%  |
| 251-500        | 460       | 9.48%   |
| 501-1000       | 220       | 4.53%   |
| 51-100         | 218       | 4.49%   |
| 21-50          | 166       | 3.42%   |
| 1001-2000      | 62        | 1.28%   |
| 2001-3000      | 20        | 0.41%   |
| More than 3000 | 12        | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3766      | 77.79%  |
| Unknown        | 676       | 13.96%  |
| 21-50          | 109       | 2.25%   |
| 101-250        | 92        | 1.9%    |
| 51-100         | 76        | 1.57%   |
| 251-500        | 59        | 1.22%   |
| 501-1000       | 37        | 0.76%   |
| 1001-2000      | 16        | 0.33%   |
| More than 3000 | 5         | 0.1%    |
| 2001-3000      | 4         | 0.08%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 44        | 44     | 2.91%   |
| Seagate ST500DM002-1BD142 500GB     | 35        | 35     | 2.32%   |
| Seagate ST9500325AS 500GB           | 28        | 30     | 1.85%   |
| Seagate ST500LT012-1DG142 500GB     | 24        | 24     | 1.59%   |
| Seagate ST3500418AS 500GB           | 21        | 23     | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 20        | 20     | 1.32%   |
| Seagate ST500LT012-9WS142 500GB     | 17        | 19     | 1.13%   |
| Toshiba MQ01ABF050 500GB            | 14        | 14     | 0.93%   |
| Toshiba DT01ACA100 1TB              | 13        | 13     | 0.86%   |
| Seagate ST9320325AS 320GB           | 12        | 12     | 0.79%   |
| Hitachi HTS545050A7E380 500GB       | 11        | 11     | 0.73%   |
| HGST HTS545050A7E680 500GB          | 11        | 11     | 0.73%   |
| Kingston SV300S37A120G 120GB SSD    | 10        | 10     | 0.66%   |
| Toshiba DT01ACA050 500GB            | 9         | 9      | 0.6%    |
| Seagate ST500LM021-1KJ152 500GB     | 9         | 9      | 0.6%    |
| Hitachi HTS547550A9E384 500GB       | 9         | 10     | 0.6%    |
| WDC WD5000AAKX-003CA0 500GB         | 8         | 8      | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB            | 8         | 8      | 0.53%   |
| Toshiba MQ01ABD100 1TB              | 8         | 8      | 0.53%   |
| Toshiba MQ01ABD050 500GB            | 8         | 8      | 0.53%   |
| Seagate ST31000528AS 1TB            | 8         | 8      | 0.53%   |
| Seagate ST31000524AS 1TB            | 8         | 8      | 0.53%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 9      | 0.53%   |
| HGST HTS721010A9E630 1TB            | 8         | 8      | 0.53%   |
| HGST HTS541010A9E680 1TB            | 8         | 8      | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB         | 7         | 8      | 0.46%   |
| Toshiba MK3265GSX 320GB             | 7         | 7      | 0.46%   |
| Seagate ST9500420AS 500GB           | 7         | 7      | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 7      | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB      | 7         | 7      | 0.46%   |
| Hitachi HTS545025B9A300 250GB       | 7         | 7      | 0.46%   |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 6      | 0.4%    |
| WDC WD10EADS-00L5B1 1TB             | 6         | 6      | 0.4%    |
| Seagate ST3250310AS 250GB           | 6         | 6      | 0.4%    |
| Seagate ST31500341AS 1TB            | 6         | 6      | 0.4%    |
| Samsung Electronics HM641JI 640GB   | 6         | 6      | 0.4%    |
| Samsung Electronics HD161HJ 160GB   | 6         | 6      | 0.4%    |
| Hitachi HTS547564A9E384 640GB       | 6         | 7      | 0.4%    |
| Hitachi HDS721050CLA362 500GB       | 6         | 8      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 417       | 450    | 28.54%  |
| WDC                 | 375       | 418    | 25.67%  |
| Hitachi             | 148       | 159    | 10.13%  |
| Toshiba             | 129       | 132    | 8.83%   |
| Samsung Electronics | 118       | 125    | 8.08%   |
| SanDisk             | 63        | 63     | 4.31%   |
| HGST                | 48        | 48     | 3.29%   |
| Kingston            | 35        | 38     | 2.4%    |
| Maxtor              | 29        | 29     | 1.98%   |
| Intel               | 12        | 13     | 0.82%   |
| Fujitsu             | 12        | 12     | 0.82%   |
| Crucial             | 12        | 12     | 0.82%   |
| China               | 7         | 7      | 0.48%   |
| A-DATA Technology   | 7         | 7      | 0.48%   |
| SK hynix            | 6         | 6      | 0.41%   |
| OCZ                 | 5         | 6      | 0.34%   |
| Intenso             | 3         | 3      | 0.21%   |
| Netac               | 2         | 2      | 0.14%   |
| Hewlett-Packard     | 2         | 2      | 0.14%   |
| Colorful            | 2         | 2      | 0.14%   |
| Apacer              | 2         | 3      | 0.14%   |
| XPG                 | 1         | 1      | 0.07%   |
| WD MediaMax         | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |
| Transcend           | 1         | 1      | 0.07%   |
| Team                | 1         | 1      | 0.07%   |
| SPCC                | 1         | 1      | 0.07%   |
| Quantum             | 1         | 1      | 0.07%   |
| QIANGHE             | 1         | 1      | 0.07%   |
| Plextor             | 1         | 1      | 0.07%   |
| Platinet            | 1         | 1      | 0.07%   |
| Neo Forza           | 1         | 1      | 0.07%   |
| Micron Technology   | 1         | 1      | 0.07%   |
| LITEONIT            | 1         | 1      | 0.07%   |
| LITEON              | 1         | 1      | 0.07%   |
| KingSpec            | 1         | 1      | 0.07%   |
| KingFast            | 1         | 1      | 0.07%   |
| KingDian            | 1         | 1      | 0.07%   |
| IBM/Hitachi         | 1         | 1      | 0.07%   |
| IB                  | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 417       | 450    | 33.33%  |
| WDC                 | 359       | 401    | 28.7%   |
| Hitachi             | 148       | 159    | 11.83%  |
| Toshiba             | 129       | 132    | 10.31%  |
| Samsung Electronics | 100       | 107    | 7.99%   |
| HGST                | 48        | 48     | 3.84%   |
| Maxtor              | 29        | 29     | 2.32%   |
| Fujitsu             | 12        | 12     | 0.96%   |
| Hewlett-Packard     | 2         | 2      | 0.16%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| Quantum             | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| IB                  | 1         | 1      | 0.08%   |
| China               | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| Apple               | 1         | 1      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1162      | 1347   | 84.63%  |
| SSD  | 203       | 209    | 14.79%  |
| NVMe | 8         | 8      | 0.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 5.71%   |
| WDC WD20EZRX-00D8PB0 2TB              | 2         | 2      | 5.71%   |
| Seagate ST3500418AS 500GB             | 2         | 4      | 5.71%   |
| Seagate ST3250318AS 250GB             | 2         | 2      | 5.71%   |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 5.71%   |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 2.86%   |
| WDC WD800JD-00LSA0 80GB               | 1         | 1      | 2.86%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 2.86%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 2.86%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 2.86%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 2.86%   |
| WDC WD10EALX-759BA1 1TB               | 1         | 1      | 2.86%   |
| TPH00800640GB 640GB                   | 1         | 1      | 2.86%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.86%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 2.86%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 2.86%   |
| Seagate STM3250318AS 250GB            | 1         | 1      | 2.86%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 2.86%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 2.86%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 2.86%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 2.86%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 2.86%   |
| Samsung Electronics HD501LJ 500GB     | 1         | 1      | 2.86%   |
| Maxtor STM3500320AS 500GB             | 1         | 1      | 2.86%   |
| Kingston SMS200S360G 64GB SSD         | 1         | 1      | 2.86%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.86%   |
| Hitachi HDS721010CLA332 1TB           | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 2.86%   |
| Apple HDD HTS541010A9E662 1TB         | 1         | 1      | 2.86%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 34.29%  |
| Seagate             | 8         | 10     | 22.86%  |
| Samsung Electronics | 3         | 3      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Hitachi             | 2         | 2      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| TPH00800640GB       | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Maxtor              | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3496      | 5260   | 64.6%   |
| Malfunc  | 1348      | 1564   | 24.91%  |
| Detected | 533       | 722    | 9.85%   |
| Failed   | 35        | 37     | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3466      | 63.5%   |
| AMD                              | 1054      | 19.31%  |
| Samsung Electronics              | 179       | 3.28%   |
| Nvidia                           | 126       | 2.31%   |
| JMicron Technology               | 90        | 1.65%   |
| SanDisk                          | 86        | 1.58%   |
| Marvell Technology Group         | 78        | 1.43%   |
| ASMedia Technology               | 78        | 1.43%   |
| Kingston Technology Company      | 46        | 0.84%   |
| Phison Electronics               | 45        | 0.82%   |
| VIA Technologies                 | 33        | 0.6%    |
| SK hynix                         | 26        | 0.48%   |
| Micron/Crucial Technology        | 26        | 0.48%   |
| Toshiba America Info Systems     | 19        | 0.35%   |
| Silicon Motion                   | 16        | 0.29%   |
| Silicon Image                    | 10        | 0.18%   |
| Micron Technology                | 8         | 0.15%   |
| ADATA Technology                 | 8         | 0.15%   |
| LSI Logic / Symbios Logic        | 7         | 0.13%   |
| KIOXIA                           | 7         | 0.13%   |
| Union Memory (Shenzhen)          | 6         | 0.11%   |
| Realtek Semiconductor            | 6         | 0.11%   |
| Seagate Technology               | 5         | 0.09%   |
| Adaptec                          | 4         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 3         | 0.05%   |
| Broadcom / LSI                   | 3         | 0.05%   |
| Apple                            | 3         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 638       | 9.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 251       | 3.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 246       | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 228       | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 218       | 3.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 193       | 2.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 192       | 2.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 175       | 2.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 175       | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 157       | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 136       | 2.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 135       | 2.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 124       | 1.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 123       | 1.83%   |
| AMD 400 Series Chipset SATA Controller                                                  | 121       | 1.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 120       | 1.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 115       | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 103       | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 101       | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 96        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 95        | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 94        | 1.4%    |
| Intel SATA Controller [RAID Mode]                                                       | 85        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 84        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 84        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 83        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 74        | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 73        | 1.08%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 71        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 70        | 1.04%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 65        | 0.97%   |
| Nvidia MCP61 SATA Controller                                                            | 56        | 0.83%   |
| Nvidia MCP61 IDE                                                                        | 55        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 52        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 51        | 0.76%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 49        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 46        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 46        | 0.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 45        | 0.67%   |
| AMD FCH IDE Controller                                                                  | 40        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3763      | 66.71%  |
| IDE  | 1103      | 19.55%  |
| NVMe | 499       | 8.85%   |
| RAID | 262       | 4.64%   |
| SCSI | 8         | 0.14%   |
| SAS  | 6         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3573      | 75.08%  |
| AMD    | 1186      | 24.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 1.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 46        | 0.97%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 44        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 39        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 39        | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 32        | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 30        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 29        | 0.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 29        | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 27        | 0.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 27        | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 27        | 0.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 27        | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 0.55%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.55%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 26        | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 26        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 25        | 0.52%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 25        | 0.52%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 25        | 0.52%   |
| AMD FX-8350 Eight-Core Processor              | 25        | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 24        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 23        | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 22        | 0.46%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 21        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 20        | 0.42%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 20        | 0.42%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 20        | 0.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 19        | 0.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.4%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 19        | 0.4%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.4%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 0.38%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 18        | 0.38%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 18        | 0.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 17        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 965       | 20.26%  |
| Intel Core i3           | 585       | 12.28%  |
| Intel Core i7           | 577       | 12.12%  |
| Intel Core 2 Duo        | 383       | 8.04%   |
| Intel Celeron           | 338       | 7.1%    |
| Intel Pentium           | 222       | 4.66%   |
| AMD Ryzen 5             | 184       | 3.86%   |
| Intel Pentium Dual-Core | 119       | 2.5%    |
| AMD FX                  | 106       | 2.23%   |
| AMD Ryzen 7             | 83        | 1.74%   |
| AMD A8                  | 74        | 1.55%   |
| Intel Core 2 Quad       | 65        | 1.36%   |
| AMD Ryzen 3             | 65        | 1.36%   |
| Intel Xeon              | 58        | 1.22%   |
| AMD A4                  | 58        | 1.22%   |
| Intel Pentium Dual      | 56        | 1.18%   |
| AMD A6                  | 51        | 1.07%   |
| AMD A10                 | 51        | 1.07%   |
| AMD Athlon II X2        | 49        | 1.03%   |
| Other                   | 47        | 0.99%   |
| Intel Core 2            | 46        | 0.97%   |
| AMD Athlon 64 X2        | 44        | 0.92%   |
| Intel Atom              | 42        | 0.88%   |
| AMD E                   | 42        | 0.88%   |
| AMD Phenom II X4        | 41        | 0.86%   |
| AMD Athlon              | 39        | 0.82%   |
| AMD E1                  | 34        | 0.71%   |
| AMD Ryzen 9             | 26        | 0.55%   |
| AMD Athlon II X4        | 25        | 0.52%   |
| AMD E2                  | 23        | 0.48%   |
| Intel Pentium 4         | 17        | 0.36%   |
| AMD Phenom II X6        | 17        | 0.36%   |
| Intel Pentium Silver    | 15        | 0.31%   |
| AMD Sempron             | 14        | 0.29%   |
| Intel Pentium Gold      | 13        | 0.27%   |
| Intel Pentium D         | 13        | 0.27%   |
| AMD Phenom              | 13        | 0.27%   |
| AMD C-60                | 11        | 0.23%   |
| AMD Athlon 64           | 11        | 0.23%   |
| Intel Celeron Dual-Core | 10        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2762      | 58.01%  |
| 4      | 1436      | 30.16%  |
| 6      | 231       | 4.85%   |
| 1      | 138       | 2.9%    |
| 8      | 115       | 2.42%   |
| 3      | 40        | 0.84%   |
| 12     | 24        | 0.5%    |
| 16     | 7         | 0.15%   |
| 10     | 5         | 0.11%   |
| 24     | 1         | 0.02%   |
| 14     | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4751      | 99.83%  |
| 2      | 8         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2447      | 51.4%   |
| 1      | 2314      | 48.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4757      | 99.96%  |
| Unknown        | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 484       | 10.14%  |
| 0x306a9    | 441       | 9.24%   |
| 0x1067a    | 380       | 7.96%   |
| 0x306c3    | 318       | 6.66%   |
| Unknown    | 152       | 3.19%   |
| 0x20655    | 137       | 2.87%   |
| 0x6fd      | 134       | 2.81%   |
| 0x40651    | 126       | 2.64%   |
| 0x406e3    | 102       | 2.14%   |
| 0x506e3    | 98        | 2.05%   |
| 0x806e9    | 90        | 1.89%   |
| 0x10676    | 87        | 1.82%   |
| 0x30678    | 85        | 1.78%   |
| 0x306d4    | 84        | 1.76%   |
| 0x906ea    | 83        | 1.74%   |
| 0x906e9    | 82        | 1.72%   |
| 0x010000c8 | 71        | 1.49%   |
| 0x06001119 | 70        | 1.47%   |
| 0x806ea    | 67        | 1.4%    |
| 0x08701021 | 66        | 1.38%   |
| 0x08108109 | 61        | 1.28%   |
| 0x706a1    | 60        | 1.26%   |
| 0x406c4    | 54        | 1.13%   |
| 0x6fb      | 49        | 1.03%   |
| 0x20652    | 46        | 0.96%   |
| 0x08101016 | 46        | 0.96%   |
| 0x806ec    | 45        | 0.94%   |
| 0x506c9    | 43        | 0.9%    |
| 0x0800820d | 43        | 0.9%    |
| 0x07030105 | 37        | 0.78%   |
| 0x06006705 | 37        | 0.78%   |
| 0x106e5    | 33        | 0.69%   |
| 0x010000b6 | 32        | 0.67%   |
| 0x706e5    | 30        | 0.63%   |
| 0x06003106 | 30        | 0.63%   |
| 0x0500010d | 30        | 0.63%   |
| 0xa0653    | 29        | 0.61%   |
| 0x08108102 | 29        | 0.61%   |
| 0x6f6      | 28        | 0.59%   |
| 0x06000822 | 27        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 498       | 10.46%  |
| Penryn          | 481       | 10.1%   |
| Haswell         | 457       | 9.6%    |
| IvyBridge       | 448       | 9.41%   |
| KabyLake        | 425       | 8.93%   |
| Core            | 252       | 5.29%   |
| Skylake         | 209       | 4.39%   |
| K10             | 194       | 4.07%   |
| Westmere        | 190       | 3.99%   |
| Silvermont      | 170       | 3.57%   |
| Piledriver      | 169       | 3.55%   |
| Zen+            | 154       | 3.23%   |
| Zen             | 118       | 2.48%   |
| Zen 2           | 117       | 2.46%   |
| Broadwell       | 88        | 1.85%   |
| Bobcat          | 82        | 1.72%   |
| Excavator       | 80        | 1.68%   |
| Goldmont plus   | 78        | 1.64%   |
| K8 Hammer       | 71        | 1.49%   |
| CometLake       | 60        | 1.26%   |
| Puma            | 59        | 1.24%   |
| Nehalem         | 50        | 1.05%   |
| Goldmont        | 46        | 0.97%   |
| Steamroller     | 38        | 0.8%    |
| NetBurst        | 34        | 0.71%   |
| Bonnell         | 33        | 0.69%   |
| IceLake         | 31        | 0.65%   |
| Jaguar          | 30        | 0.63%   |
| Bulldozer       | 27        | 0.57%   |
| K10 Llano       | 24        | 0.5%    |
| TigerLake       | 14        | 0.29%   |
| Zen 3           | 12        | 0.25%   |
| Unknown         | 11        | 0.23%   |
| K8 & K10 hybrid | 10        | 0.21%   |
| Tremont         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2598      | 49.48%  |
| Nvidia                           | 1389      | 26.45%  |
| AMD                              | 1255      | 23.9%   |
| Matrox Electronics Systems       | 4         | 0.08%   |
| VIA Technologies                 | 3         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 381       | 7.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 214       | 3.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 153       | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 136       | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 129       | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 125       | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 99        | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 96        | 1.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 92        | 1.69%   |
| Intel HD Graphics 620                                                                    | 90        | 1.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 90        | 1.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 88        | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 1.46%   |
| Intel HD Graphics 5500                                                                   | 74        | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 71        | 1.31%   |
| Nvidia GT218 [GeForce 210]                                                               | 70        | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 69        | 1.27%   |
| Intel HD Graphics 530                                                                    | 65        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 65        | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 63        | 1.16%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 55        | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 52        | 0.96%   |
| Intel HD Graphics 630                                                                    | 49        | 0.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 43        | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 41        | 0.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 39        | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 35        | 0.64%   |
| Intel HD Graphics 500                                                                    | 35        | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 33        | 0.61%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 32        | 0.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 0.57%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 31        | 0.57%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 31        | 0.57%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 29        | 0.53%   |
| AMD RS780L [Radeon 3000]                                                                 | 27        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 2141      | 44.97%  |
| 1 x AMD         | 1054      | 22.14%  |
| 1 x Nvidia      | 1006      | 21.13%  |
| Intel + Nvidia  | 343       | 7.2%    |
| 2 x AMD         | 86        | 1.81%   |
| Intel + AMD     | 84        | 1.76%   |
| AMD + Nvidia    | 31        | 0.65%   |
| 2 x Nvidia      | 8         | 0.17%   |
| 1 x VIA         | 3         | 0.06%   |
| 1 x Matrox      | 3         | 0.06%   |
| 1 x SiS         | 1         | 0.02%   |
| Nvidia + Matrox | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4668      | 98.07%  |
| Unknown     | 87        | 1.83%   |
| Proprietary | 5         | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2217      | 46.52%  |
| 0.01-0.5   | 785       | 16.47%  |
| 1.01-2.0   | 687       | 14.41%  |
| 0.51-1.0   | 650       | 13.64%  |
| 3.01-4.0   | 223       | 4.68%   |
| 7.01-8.0   | 102       | 2.14%   |
| 5.01-6.0   | 66        | 1.38%   |
| 2.01-3.0   | 29        | 0.61%   |
| 8.01-16.0  | 6         | 0.13%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 765       | 16.34%  |
| AU Optronics            | 478       | 10.21%  |
| LG Display              | 397       | 8.48%   |
| Goldstar                | 322       | 6.88%   |
| BOE                     | 305       | 6.51%   |
| Chimei Innolux          | 300       | 6.41%   |
| Hewlett-Packard         | 213       | 4.55%   |
| Dell                    | 202       | 4.31%   |
| Acer                    | 196       | 4.19%   |
| Philips                 | 146       | 3.12%   |
| BenQ                    | 119       | 2.54%   |
| AOC                     | 117       | 2.5%    |
| Chi Mei Optoelectronics | 109       | 2.33%   |
| Lenovo                  | 106       | 2.26%   |
| Ancor Communications    | 106       | 2.26%   |
| Iiyama                  | 61        | 1.3%    |
| CPT                     | 57        | 1.22%   |
| Apple                   | 57        | 1.22%   |
| ViewSonic               | 50        | 1.07%   |
| LG Philips              | 41        | 0.88%   |
| Sony                    | 32        | 0.68%   |
| Fujitsu Siemens         | 31        | 0.66%   |
| NEC Computers           | 29        | 0.62%   |
| ASUSTek Computer        | 29        | 0.62%   |
| PANDA                   | 27        | 0.58%   |
| Eizo                    | 24        | 0.51%   |
| HannStar                | 21        | 0.45%   |
| Sharp                   | 20        | 0.43%   |
| InfoVision              | 18        | 0.38%   |
| Toshiba                 | 14        | 0.3%    |
| Vestel Elektronik       | 13        | 0.28%   |
| Vizio                   | 12        | 0.26%   |
| Medion                  | 12        | 0.26%   |
| Unknown                 | 11        | 0.23%   |
| Panasonic               | 11        | 0.23%   |
| MStar                   | 10        | 0.21%   |
| Belinea                 | 10        | 0.21%   |
| RTK                     | 9         | 0.19%   |
| Packard Bell            | 9         | 0.19%   |
| InnoLux Display         | 9         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 44        | 0.93%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 34        | 0.72%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 21        | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 19        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 19        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 18        | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 18        | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.34%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 15        | 0.32%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.32%   |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch                  | 14        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 14        | 0.3%    |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.25%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 11        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 11        | 0.23%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 11        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 10        | 0.21%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 10        | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 10        | 0.21%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 10        | 0.21%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.21%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 10        | 0.21%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 10        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1711      | 37.03%  |
| 1366x768 (WXGA)    | 1235      | 26.73%  |
| 1600x900 (HD+)     | 314       | 6.8%    |
| 1280x1024 (SXGA)   | 275       | 5.95%   |
| 1680x1050 (WSXGA+) | 216       | 4.68%   |
| 1440x900 (WXGA+)   | 184       | 3.98%   |
| 1280x800 (WXGA)    | 167       | 3.61%   |
| 3840x2160 (4K)     | 157       | 3.4%    |
| 2560x1440 (QHD)    | 89        | 1.93%   |
| 1920x1200 (WUXGA)  | 78        | 1.69%   |
| 1360x768           | 45        | 0.97%   |
| 2560x1080          | 22        | 0.48%   |
| 1024x768 (XGA)     | 18        | 0.39%   |
| 1920x540           | 16        | 0.35%   |
| 1024x600           | 12        | 0.26%   |
| 2560x1600          | 10        | 0.22%   |
| 3440x1440          | 9         | 0.19%   |
| 1600x1200          | 7         | 0.15%   |
| 2160x1440          | 5         | 0.11%   |
| 1680x945           | 5         | 0.11%   |
| 1280x960           | 5         | 0.11%   |
| 2880x1800          | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 1280x720 (HD)      | 4         | 0.09%   |
| 3200x1800 (QHD+)   | 3         | 0.06%   |
| 2880x1920          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1280x768           | 3         | 0.06%   |
| 3840x1080          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1152x864           | 2         | 0.04%   |
| 3840x2400          | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 3840x1100          | 1         | 0.02%   |
| 3300x2200          | 1         | 0.02%   |
| 3000x2000          | 1         | 0.02%   |
| 2736x1824          | 1         | 0.02%   |
| 2304x1440          | 1         | 0.02%   |
| 2256x1504          | 1         | 0.02%   |
| 2048x1536          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1169      | 24.91%  |
| 23      | 401       | 8.55%   |
| 17      | 385       | 8.21%   |
| 13      | 358       | 7.63%   |
| 21      | 345       | 7.35%   |
| 24      | 285       | 6.07%   |
| 14      | 271       | 5.78%   |
| 19      | 241       | 5.14%   |
| 27      | 224       | 4.77%   |
| 18      | 187       | 3.99%   |
| 22      | 140       | 2.98%   |
| 20      | 116       | 2.47%   |
| 31      | 110       | 2.34%   |
| 12      | 70        | 1.49%   |
| 11      | 58        | 1.24%   |
| 84      | 30        | 0.64%   |
| 32      | 30        | 0.64%   |
| 54      | 28        | 0.6%    |
| 34      | 28        | 0.6%    |
| Unknown | 27        | 0.58%   |
| 72      | 24        | 0.51%   |
| 26      | 18        | 0.38%   |
| 40      | 16        | 0.34%   |
| 10      | 16        | 0.34%   |
| 25      | 15        | 0.32%   |
| 52      | 13        | 0.28%   |
| 16      | 13        | 0.28%   |
| 46      | 10        | 0.21%   |
| 28      | 8         | 0.17%   |
| 48      | 5         | 0.11%   |
| 37      | 5         | 0.11%   |
| 74      | 4         | 0.09%   |
| 65      | 4         | 0.09%   |
| 60      | 4         | 0.09%   |
| 58      | 4         | 0.09%   |
| 39      | 4         | 0.09%   |
| 29      | 4         | 0.09%   |
| 49      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 142     | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1733      | 37.28%  |
| 401-500        | 893       | 19.21%  |
| 501-600        | 880       | 18.93%  |
| 351-400        | 443       | 9.53%   |
| 201-300        | 298       | 6.41%   |
| 601-700        | 147       | 3.16%   |
| 1001-1500      | 74        | 1.59%   |
| 701-800        | 60        | 1.29%   |
| 1501-2000      | 59        | 1.27%   |
| 801-900        | 27        | 0.58%   |
| Unknown        | 27        | 0.58%   |
| 901-1000       | 5         | 0.11%   |
| More than 2000 | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3461      | 76.6%   |
| 16/10   | 656       | 14.52%  |
| 5/4     | 269       | 5.95%   |
| 4/3     | 47        | 1.04%   |
| 3/2     | 38        | 0.84%   |
| 21/9    | 28        | 0.62%   |
| 6/5     | 9         | 0.2%    |
| 32/9    | 4         | 0.09%   |
| 1.00    | 2         | 0.04%   |
| 3.40    | 1         | 0.02%   |
| 2.01    | 1         | 0.02%   |
| 0.75    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1156      | 24.78%  |
| 201-250        | 978       | 20.96%  |
| 81-90          | 497       | 10.65%  |
| 151-200        | 476       | 10.2%   |
| 141-150        | 292       | 6.26%   |
| 301-350        | 239       | 5.12%   |
| 121-130        | 193       | 4.14%   |
| 351-500        | 176       | 3.77%   |
| 71-80          | 128       | 2.74%   |
| More than 1000 | 123       | 2.64%   |
| 251-300        | 108       | 2.32%   |
| 61-70          | 67        | 1.44%   |
| 51-60          | 60        | 1.29%   |
| 131-140        | 55        | 1.18%   |
| 501-1000       | 47        | 1.01%   |
| Unknown        | 27        | 0.58%   |
| 111-120        | 16        | 0.34%   |
| 41-50          | 15        | 0.32%   |
| 91-100         | 12        | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2062      | 44.87%  |
| 101-120       | 1584      | 34.46%  |
| 121-160       | 690       | 15.01%  |
| 1-50          | 121       | 2.63%   |
| 161-240       | 92        | 2%      |
| Unknown       | 27        | 0.59%   |
| More than 240 | 20        | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4427      | 92.91%  |
| 2     | 280       | 5.88%   |
| 0     | 41        | 0.86%   |
| 3     | 12        | 0.25%   |
| 6     | 2         | 0.04%   |
| 4     | 2         | 0.04%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2816      | 39.98%  |
| Intel                             | 1682      | 23.88%  |
| Qualcomm Atheros                  | 1138      | 16.16%  |
| Broadcom                          | 369       | 5.24%   |
| Marvell Technology Group          | 111       | 1.58%   |
| Nvidia                            | 102       | 1.45%   |
| Ralink                            | 100       | 1.42%   |
| Broadcom Limited                  | 100       | 1.42%   |
| Ralink Technology                 | 93        | 1.32%   |
| Samsung Electronics               | 61        | 0.87%   |
| Huawei Technologies               | 46        | 0.65%   |
| TP-Link                           | 42        | 0.6%    |
| JMicron Technology                | 34        | 0.48%   |
| Qualcomm Atheros Communications   | 32        | 0.45%   |
| Dell                              | 22        | 0.31%   |
| D-Link                            | 20        | 0.28%   |
| Ericsson Business Mobile Networks | 18        | 0.26%   |
| D-Link System                     | 18        | 0.26%   |
| VIA Technologies                  | 15        | 0.21%   |
| MediaTek                          | 15        | 0.21%   |
| Xiaomi                            | 13        | 0.18%   |
| NetGear                           | 13        | 0.18%   |
| ZTE WCDMA Technologies MSM        | 12        | 0.17%   |
| Microsoft                         | 11        | 0.16%   |
| ASUSTek Computer                  | 11        | 0.16%   |
| ASIX Electronics                  | 11        | 0.16%   |
| Motorola PCS                      | 9         | 0.13%   |
| DisplayLink                       | 8         | 0.11%   |
| 3Com                              | 8         | 0.11%   |
| Sierra Wireless                   | 7         | 0.1%    |
| IMC Networks                      | 7         | 0.1%    |
| Edimax Technology                 | 7         | 0.1%    |
| Belkin Components                 | 7         | 0.1%    |
| Linksys                           | 6         | 0.09%   |
| Hewlett-Packard                   | 5         | 0.07%   |
| Aquantia                          | 5         | 0.07%   |
| Sitecom Europe                    | 4         | 0.06%   |
| OPPO Electronics                  | 4         | 0.06%   |
| AVM                               | 4         | 0.06%   |
| Qualcomm                          | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 2082      | 25.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 450       | 5.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 198       | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 189       | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 183       | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 157       | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 143       | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 88        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 80        | 0.99%   |
| Intel Wireless 7265                                                     | 78        | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 75        | 0.93%   |
| Intel Wi-Fi 6 AX200                                                     | 74        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 67        | 0.83%   |
| Intel Ethernet Connection I217-LM                                       | 67        | 0.83%   |
| Intel Wireless 7260                                                     | 66        | 0.82%   |
| Intel I211 Gigabit Network Connection                                   | 63        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                 | 61        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                    | 58        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 57        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 57        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 56        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 55        | 0.68%   |
| Intel WiFi Link 5100                                                    | 52        | 0.64%   |
| Nvidia MCP61 Ethernet                                                   | 50        | 0.62%   |
| Intel Wireless 8265 / 8275                                              | 49        | 0.61%   |
| Intel Wireless 8260                                                     | 47        | 0.58%   |
| Intel Wireless 3165                                                     | 47        | 0.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 47        | 0.58%   |
| Ralink MT7601U Wireless Adapter                                         | 44        | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                | 44        | 0.55%   |
| Intel 82567LM Gigabit Network Connection                                | 43        | 0.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 41        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 41        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 41        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 39        | 0.48%   |
| Huawei E353/E3131                                                       | 39        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1116      | 34.49%  |
| Qualcomm Atheros                      | 900       | 27.81%  |
| Realtek Semiconductor                 | 586       | 18.11%  |
| Broadcom                              | 197       | 6.09%   |
| Ralink                                | 100       | 3.09%   |
| Ralink Technology                     | 93        | 2.87%   |
| Broadcom Limited                      | 39        | 1.21%   |
| TP-Link                               | 38        | 1.17%   |
| Qualcomm Atheros Communications       | 32        | 0.99%   |
| D-Link                                | 17        | 0.53%   |
| NetGear                               | 11        | 0.34%   |
| Dell                                  | 11        | 0.34%   |
| ASUSTek Computer                      | 11        | 0.34%   |
| Microsoft                             | 10        | 0.31%   |
| D-Link System                         | 8         | 0.25%   |
| Sierra Wireless                       | 7         | 0.22%   |
| MediaTek                              | 7         | 0.22%   |
| IMC Networks                          | 7         | 0.22%   |
| Edimax Technology                     | 7         | 0.22%   |
| Belkin Components                     | 7         | 0.22%   |
| Linksys                               | 5         | 0.15%   |
| Marvell Technology Group              | 4         | 0.12%   |
| AVM                                   | 4         | 0.12%   |
| Sitecom Europe                        | 3         | 0.09%   |
| Mercucys                              | 3         | 0.09%   |
| Wilocity                              | 2         | 0.06%   |
| Wacom                                 | 2         | 0.06%   |
| Guillemot                             | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| ZyDAS                                 | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Fibocom                               | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 189       | 5.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 183       | 5.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 157       | 4.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 143       | 4.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 88        | 2.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 2.65%   |
| Intel Wireless 7265                                                     | 78        | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 75        | 2.31%   |
| Intel Wi-Fi 6 AX200                                                     | 74        | 2.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 67        | 2.06%   |
| Intel Wireless 7260                                                     | 66        | 2.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 56        | 1.72%   |
| Intel WiFi Link 5100                                                    | 52        | 1.6%    |
| Intel Wireless 8265 / 8275                                              | 49        | 1.51%   |
| Intel Wireless 8260                                                     | 47        | 1.45%   |
| Intel Wireless 3165                                                     | 47        | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 47        | 1.45%   |
| Ralink MT7601U Wireless Adapter                                         | 44        | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 41        | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 41        | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 41        | 1.26%   |
| Intel Wireless 3160                                                     | 38        | 1.17%   |
| Intel Centrino Advanced-N 6200                                          | 38        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 36        | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 35        | 1.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 34        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 32        | 0.99%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 32        | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 31        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 31        | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                         | 29        | 0.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 29        | 0.89%   |
| Intel Centrino Ultimate-N 6300                                          | 29        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 0.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 27        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2644      | 56.33%  |
| Intel                             | 945       | 20.13%  |
| Qualcomm Atheros                  | 354       | 7.54%   |
| Broadcom                          | 210       | 4.47%   |
| Marvell Technology Group          | 107       | 2.28%   |
| Nvidia                            | 101       | 2.15%   |
| Broadcom Limited                  | 63        | 1.34%   |
| Samsung Electronics               | 57        | 1.21%   |
| Huawei Technologies               | 44        | 0.94%   |
| JMicron Technology                | 34        | 0.72%   |
| Xiaomi                            | 13        | 0.28%   |
| VIA Technologies                  | 13        | 0.28%   |
| ASIX Electronics                  | 11        | 0.23%   |
| D-Link System                     | 10        | 0.21%   |
| Motorola PCS                      | 9         | 0.19%   |
| MediaTek                          | 8         | 0.17%   |
| DisplayLink                       | 8         | 0.17%   |
| 3Com                              | 8         | 0.17%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.11%   |
| TP-Link                           | 5         | 0.11%   |
| Aquantia                          | 5         | 0.11%   |
| OPPO Electronics                  | 4         | 0.09%   |
| Qualcomm                          | 3         | 0.06%   |
| ICS Advent                        | 3         | 0.06%   |
| D-Link                            | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| T & A Mobile Phones               | 2         | 0.04%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.04%   |
| NetGear                           | 2         | 0.04%   |
| HMD Global                        | 2         | 0.04%   |
| Davicom Semiconductor             | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Sitecom Europe                    | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| LG Electronics                    | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |
| IBM                               | 1         | 0.02%   |
| Hewlett-Packard                   | 1         | 0.02%   |
| Google                            | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2082      | 43.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 450       | 9.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 198       | 4.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 80        | 1.68%   |
| Intel Ethernet Connection I217-LM                                      | 67        | 1.41%   |
| Intel I211 Gigabit Network Connection                                  | 63        | 1.33%   |
| Intel 82579V Gigabit Network Connection                                | 61        | 1.28%   |
| Intel Ethernet Connection (2) I219-V                                   | 58        | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 57        | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 57        | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 55        | 1.16%   |
| Nvidia MCP61 Ethernet                                                  | 50        | 1.05%   |
| Intel 82577LM Gigabit Network Connection                               | 44        | 0.93%   |
| Intel 82567LM Gigabit Network Connection                               | 43        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 39        | 0.82%   |
| Huawei E353/E3131                                                      | 39        | 0.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 38        | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 37        | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 33        | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 30        | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 27        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 25        | 0.53%   |
| Intel Ethernet Connection I217-V                                       | 24        | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                      | 22        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 21        | 0.44%   |
| Intel Ethernet Connection I218-LM                                      | 21        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                   | 21        | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 21        | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 21        | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                                  | 20        | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 19        | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                  | 19        | 0.4%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 18        | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 17        | 0.36%   |
| Intel Ethernet Controller I225-V                                       | 16        | 0.34%   |
| Intel Ethernet Connection I219-LM                                      | 16        | 0.34%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 15        | 0.32%   |
| Intel 82566MM Gigabit Network Connection                               | 15        | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 15        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4496      | 58.42%  |
| WiFi     | 3137      | 40.76%  |
| Modem    | 57        | 0.74%   |
| Unknown  | 6         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2755      | 58.78%  |
| WiFi     | 1931      | 41.2%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2543      | 53.4%   |
| 1     | 2138      | 44.9%   |
| 3     | 49        | 1.03%   |
| 0     | 27        | 0.57%   |
| 4     | 3         | 0.06%   |
| 7     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3739      | 78.16%  |
| Yes     | 1044      | 21.82%  |
| Unknown | 1         | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 695       | 32.86%  |
| Qualcomm Atheros Communications | 260       | 12.29%  |
| Realtek Semiconductor           | 218       | 10.31%  |
| Cambridge Silicon Radio         | 179       | 8.46%   |
| Broadcom                        | 155       | 7.33%   |
| Lite-On Technology              | 129       | 6.1%    |
| IMC Networks                    | 81        | 3.83%   |
| Foxconn / Hon Hai               | 71        | 3.36%   |
| Apple                           | 59        | 2.79%   |
| Dell                            | 54        | 2.55%   |
| ASUSTek Computer                | 43        | 2.03%   |
| Toshiba                         | 40        | 1.89%   |
| Hewlett-Packard                 | 33        | 1.56%   |
| Ralink                          | 23        | 1.09%   |
| Realtek                         | 11        | 0.52%   |
| Foxconn International           | 10        | 0.47%   |
| Chicony Electronics             | 8         | 0.38%   |
| Alps Electric                   | 7         | 0.33%   |
| Ralink Technology               | 6         | 0.28%   |
| Marvell Semiconductor           | 6         | 0.28%   |
| Integrated System Solution      | 6         | 0.28%   |
| Belkin Components               | 4         | 0.19%   |
| Askey Computer                  | 4         | 0.19%   |
| Taiyo Yuden                     | 3         | 0.14%   |
| Micro Star International        | 3         | 0.14%   |
| Dynex                           | 2         | 0.09%   |
| Unknown                         | 1         | 0.05%   |
| SiW                             | 1         | 0.05%   |
| MediaTek                        | 1         | 0.05%   |
| i.Tech Dynamic Limited          | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 352       | 16.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 179       | 8.46%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 126       | 5.96%   |
| Realtek Bluetooth Radio                                                             | 112       | 5.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 97        | 4.59%   |
| Intel AX200 Bluetooth                                                               | 68        | 3.22%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 61        | 2.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 57        | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 52        | 2.46%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 48        | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 45        | 2.13%   |
| Intel AX201 Bluetooth                                                               | 37        | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 35        | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 34        | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 32        | 1.51%   |
| IMC Networks Bluetooth Device                                                       | 30        | 1.42%   |
| Lite-On Bluetooth Device                                                            | 28        | 1.32%   |
| IMC Networks Bluetooth Radio                                                        | 27        | 1.28%   |
| Apple Bluetooth Host Controller                                                     | 27        | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 26        | 1.23%   |
| Dell DW375 Bluetooth Module                                                         | 25        | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 24        | 1.13%   |
| Ralink RT3290 Bluetooth                                                             | 23        | 1.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 22        | 1.04%   |
| Realtek RTL8723B Bluetooth                                                          | 20        | 0.95%   |
| Apple Bluetooth USB Host Controller                                                 | 19        | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 18        | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 17        | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 17        | 0.8%    |
| Toshiba Bluetooth Device                                                            | 16        | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 16        | 0.76%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 16        | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 15        | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 14        | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 13        | 0.61%   |
| Realtek RTL8821A Bluetooth                                                          | 12        | 0.57%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.57%   |
| Broadcom BCM2045 Bluetooth                                                          | 12        | 0.57%   |
| Realtek Bluetooth Radio                                                             | 11        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 3477      | 55.57%  |
| AMD                                             | 1360      | 21.74%  |
| Nvidia                                          | 1079      | 17.24%  |
| C-Media Electronics                             | 79        | 1.26%   |
| Creative Labs                                   | 63        | 1.01%   |
| Logitech                                        | 19        | 0.3%    |
| VIA Technologies                                | 18        | 0.29%   |
| Texas Instruments                               | 17        | 0.27%   |
| JMTek                                           | 16        | 0.26%   |
| Creative Technology                             | 12        | 0.19%   |
| Generalplus Technology                          | 10        | 0.16%   |
| ASUSTek Computer                                | 9         | 0.14%   |
| Tenx Technology                                 | 6         | 0.1%    |
| Yamaha                                          | 5         | 0.08%   |
| Razer USA                                       | 4         | 0.06%   |
| M-Audio                                         | 4         | 0.06%   |
| Bose                                            | 4         | 0.06%   |
| GN Netcom                                       | 3         | 0.05%   |
| Giga-Byte Technology                            | 3         | 0.05%   |
| Focusrite-Novation                              | 3         | 0.05%   |
| Ensoniq                                         | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.03%   |
| Syntek                                          | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]                | 2         | 0.03%   |
| SAVITECH                                        | 2         | 0.03%   |
| Samson Technologies                             | 2         | 0.03%   |
| ROCCAT                                          | 2         | 0.03%   |
| Realtek Semiconductor                           | 2         | 0.03%   |
| PreSonus Audio Electronics                      | 2         | 0.03%   |
| Meizu                                           | 2         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.03%   |
| GYROCOM C&C                                     | 2         | 0.03%   |
| Dell                                            | 2         | 0.03%   |
| Corsair                                         | 2         | 0.03%   |
| XMOS                                            | 1         | 0.02%   |
| UCQ01000                                        | 1         | 0.02%   |
| Turtle Beach                                    | 1         | 0.02%   |
| TerraTec Electronic                             | 1         | 0.02%   |
| TEAC                                            | 1         | 0.02%   |
| SteelSeries ApS                                 | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 485       | 6.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 434       | 5.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 325       | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 276       | 3.7%    |
| AMD FCH Azalia Controller                                                                         | 269       | 3.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 262       | 3.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 260       | 3.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 214       | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 208       | 2.79%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 208       | 2.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 207       | 2.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 156       | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 149       | 2%      |
| Intel 8 Series HD Audio Controller                                                                | 126       | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 124       | 1.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 124       | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 123       | 1.65%   |
| Nvidia High Definition Audio Controller                                                           | 120       | 1.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 115       | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 112       | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 99        | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 98        | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 92        | 1.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 87        | 1.17%   |
| Intel Broadwell-U Audio Controller                                                                | 85        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 1.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 83        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 79        | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 78        | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 77        | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 71        | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 67        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 66        | 0.88%   |
| AMD Wrestler HDMI Audio                                                                           | 65        | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 62        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 62        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 60        | 0.8%    |
| AMD Trinity HDMI Audio Controller                                                                 | 55        | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 54        | 0.72%   |
| Nvidia MCP61 High Definition Audio                                                                | 53        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1032      | 18.46%  |
| Unknown             | 914       | 16.35%  |
| SK hynix            | 788       | 14.1%   |
| Kingston            | 774       | 13.85%  |
| Micron Technology   | 372       | 6.66%   |
| Crucial             | 268       | 4.8%    |
| Corsair             | 230       | 4.12%   |
| Elpida              | 164       | 2.93%   |
| G.Skill             | 139       | 2.49%   |
| Nanya Technology    | 122       | 2.18%   |
| A-DATA Technology   | 114       | 2.04%   |
| Ramaxel Technology  | 97        | 1.74%   |
| Smart               | 59        | 1.06%   |
| Unknown (ABCD)      | 49        | 0.88%   |
| Patriot             | 40        | 0.72%   |
| Goodram             | 32        | 0.57%   |
| Transcend           | 31        | 0.55%   |
| Team                | 29        | 0.52%   |
| Apacer              | 27        | 0.48%   |
| Unknown             | 21        | 0.38%   |
| AMD                 | 20        | 0.36%   |
| ASint Technology    | 16        | 0.29%   |
| Teikon              | 15        | 0.27%   |
| Toshiba             | 14        | 0.25%   |
| Kingmax             | 14        | 0.25%   |
| High Bridge         | 13        | 0.23%   |
| Silicon Power       | 12        | 0.21%   |
| Qimonda             | 12        | 0.21%   |
| GeIL                | 10        | 0.18%   |
| Unifosa             | 8         | 0.14%   |
| PNY                 | 8         | 0.14%   |
| Avant               | 8         | 0.14%   |
| TakeMS              | 5         | 0.09%   |
| Smart Brazil        | 5         | 0.09%   |
| Multilaser          | 5         | 0.09%   |
| Kreton              | 5         | 0.09%   |
| Unknown (AB)        | 4         | 0.07%   |
| SHARETRONIC         | 4         | 0.07%   |
| Qumo                | 4         | 0.07%   |
| H                   | 4         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 59        | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 51        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 51        | 0.84%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 46        | 0.75%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 46        | 0.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 45        | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 45        | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 43        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 41        | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 40        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 39        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.64%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 36        | 0.59%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 35        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 34        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 33        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 32        | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 30        | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 28        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 28        | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 27        | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 25        | 0.41%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 25        | 0.41%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 24        | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 23        | 0.38%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 23        | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 21        | 0.34%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 21        | 0.34%   |
| Unknown                                                          | 21        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 20        | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 20        | 0.33%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 19        | 0.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.31%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 19        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 18        | 0.3%    |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 18        | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.3%    |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 17        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 2392      | 49.76%  |
| DDR4    | 1193      | 24.82%  |
| DDR2    | 496       | 10.32%  |
| Unknown | 294       | 6.12%   |
| SDRAM   | 275       | 5.72%   |
| LPDDR4  | 78        | 1.62%   |
| DDR     | 48        | 1%      |
| LPDDR3  | 23        | 0.48%   |
| DRAM    | 7         | 0.15%   |
| DDR5    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2385      | 50.94%  |
| DIMM         | 2226      | 47.54%  |
| Row Of Chips | 55        | 1.17%   |
| Chip         | 8         | 0.17%   |
| RIMM         | 4         | 0.09%   |
| Unknown      | 3         | 0.06%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 2053      | 38.33%  |
| 8192  | 1310      | 24.46%  |
| 2048  | 1310      | 24.46%  |
| 1024  | 332       | 6.2%    |
| 16384 | 264       | 4.93%   |
| 32768 | 48        | 0.9%    |
| 512   | 35        | 0.65%   |
| 3072  | 1         | 0.02%   |
| 256   | 1         | 0.02%   |
| 64    | 1         | 0.02%   |
| 32    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1425      | 26.51%  |
| 1333    | 679       | 12.63%  |
| 2667    | 429       | 7.98%   |
| 2400    | 331       | 6.16%   |
| 1334    | 296       | 5.51%   |
| 667     | 285       | 5.3%    |
| 800     | 257       | 4.78%   |
| Unknown | 191       | 3.55%   |
| 2133    | 172       | 3.2%    |
| 3200    | 163       | 3.03%   |
| 1067    | 125       | 2.33%   |
| 1867    | 90        | 1.67%   |
| 3600    | 85        | 1.58%   |
| 1066    | 73        | 1.36%   |
| 4199    | 57        | 1.06%   |
| 3266    | 57        | 1.06%   |
| 1800    | 53        | 0.99%   |
| 1866    | 51        | 0.95%   |
| 533     | 50        | 0.93%   |
| 2048    | 49        | 0.91%   |
| 400     | 40        | 0.74%   |
| 2933    | 33        | 0.61%   |
| 975     | 32        | 0.6%    |
| 3400    | 31        | 0.58%   |
| 3000    | 24        | 0.45%   |
| 2666    | 23        | 0.43%   |
| 3733    | 18        | 0.33%   |
| 3800    | 16        | 0.3%    |
| 333     | 15        | 0.28%   |
| 3466    | 13        | 0.24%   |
| 3066    | 13        | 0.24%   |
| 4000    | 11        | 0.2%    |
| 2800    | 11        | 0.2%    |
| 1648    | 11        | 0.2%    |
| 1639    | 11        | 0.2%    |
| 2000    | 10        | 0.19%   |
| 1331    | 10        | 0.19%   |
| 2200    | 9         | 0.17%   |
| 49926   | 8         | 0.15%   |
| 3151    | 7         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 82        | 45.3%   |
| Brother Industries    | 30        | 16.57%  |
| Canon                 | 22        | 12.15%  |
| Samsung Electronics   | 21        | 11.6%   |
| Seiko Epson           | 17        | 9.39%   |
| Xerox                 | 2         | 1.1%    |
| Lexmark International | 2         | 1.1%    |
| Dymo-CoStar           | 2         | 1.1%    |
| Ricoh                 | 1         | 0.55%   |
| Prolific Technology   | 1         | 0.55%   |
| Oki Data              | 1         | 0.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP DeskJet 3630 series                                 | 6         | 3.26%   |
| Samsung ML-1640 Series Laser Printer                   | 5         | 2.72%   |
| HP DeskJet 2620 All-in-One Printer                     | 5         | 2.72%   |
| HP LaserJet P1006                                      | 4         | 2.17%   |
| Samsung M2070 Series                                   | 3         | 1.63%   |
| Samsung M2020 Series                                   | 3         | 1.63%   |
| HP LaserJet 1020                                       | 3         | 1.63%   |
| HP ENVY 4520 series                                    | 3         | 1.63%   |
| HP DeskJet 2130 series                                 | 3         | 1.63%   |
| Seiko Epson XP-243 245 247 Series                      | 2         | 1.09%   |
| Seiko Epson ET-2600 Series                             | 2         | 1.09%   |
| HP OfficeJet Pro 6960                                  | 2         | 1.09%   |
| HP LaserJet P1102                                      | 2         | 1.09%   |
| HP ENVY Photo 6200 series                              | 2         | 1.09%   |
| HP Deskjet F4500 series                                | 2         | 1.09%   |
| HP DeskJet 916C                                        | 2         | 1.09%   |
| HP DeskJet 845c                                        | 2         | 1.09%   |
| HP DeskJet 840c                                        | 2         | 1.09%   |
| HP Deskjet 3520 series                                 | 2         | 1.09%   |
| HP DeskJet 2700 series                                 | 2         | 1.09%   |
| Canon PIXMA MX920 Series                               | 2         | 1.09%   |
| Canon PIXMA MX530 Series                               | 2         | 1.09%   |
| Canon PIXMA MG3600 Series                              | 2         | 1.09%   |
| Canon PIXMA MG3500 Series                              | 2         | 1.09%   |
| Brother Printer                                        | 2         | 1.09%   |
| Brother DCP-L3550CDW                                   | 2         | 1.09%   |
| Brother DCP-1610W                                      | 2         | 1.09%   |
| Xerox Phaser 6000B                                     | 1         | 0.54%   |
| Xerox B215                                             | 1         | 0.54%   |
| Seiko Epson XP-4100 Series                             | 1         | 0.54%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.54%   |
| Seiko Epson USB2.0 Printer                             | 1         | 0.54%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.54%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series          | 1         | 0.54%   |
| Seiko Epson L375 Series                                | 1         | 0.54%   |
| Seiko Epson L365 Series                                | 1         | 0.54%   |
| Seiko Epson L360 Series                                | 1         | 0.54%   |
| Seiko Epson L312 Series                                | 1         | 0.54%   |
| Seiko Epson L210 Series                                | 1         | 0.54%   |
| Seiko Epson L120 Series                                | 1         | 0.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 22        | 47.83%  |
| Hewlett-Packard             | 11        | 23.91%  |
| Seiko Epson                 | 5         | 10.87%  |
| Mustek Systems              | 4         | 8.7%    |
| AGFA-Gevaert NV             | 2         | 4.35%   |
| Plustek                     | 1         | 2.17%   |
| KYE Systems (Mouse Systems) | 1         | 2.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 10.87%  |
| Canon CanoScan LiDE 110                                  | 3         | 6.52%   |
| Mustek Systems ScanExpress 1200 UB                       | 2         | 4.35%   |
| HP ScanJet 5590                                          | 2         | 4.35%   |
| HP ScanJet 4500C/5550C                                   | 2         | 4.35%   |
| Canon CanoScan LiDE 70                                   | 2         | 4.35%   |
| Canon CanoScan LIDE 25                                   | 2         | 4.35%   |
| Canon CanoScan LiDE 120                                  | 2         | 4.35%   |
| Canon CanoScan LiDE 100                                  | 2         | 4.35%   |
| Seiko Epson Scanner                                      | 1         | 2.17%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 2.17%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 2.17%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 2.17%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1         | 2.17%   |
| Plustek 600DPI USB Scanner                               | 1         | 2.17%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 2.17%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1         | 2.17%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 2.17%   |
| HP ScanJet G4010                                         | 1         | 2.17%   |
| HP ScanJet 4370                                          | 1         | 2.17%   |
| HP ScanJet 3800c                                         | 1         | 2.17%   |
| HP ScanJet 3670                                          | 1         | 2.17%   |
| HP ScanJet 2300c                                         | 1         | 2.17%   |
| HP ScanJet 2200c                                         | 1         | 2.17%   |
| HP PSC 1200                                              | 1         | 2.17%   |
| Canon CanoScan N650U/N656U                               | 1         | 2.17%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 2.17%   |
| Canon CanoScan LiDE 700F                                 | 1         | 2.17%   |
| Canon CanoScan LiDE 500F                                 | 1         | 2.17%   |
| Canon CanoScan LiDE 220                                  | 1         | 2.17%   |
| Canon CanoScan LiDE 200                                  | 1         | 2.17%   |
| AGFA-Gevaert NV SnapScan Touch                           | 1         | 2.17%   |
| AGFA-Gevaert NV SnapScan e20                             | 1         | 2.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 577       | 24.62%  |
| Suyin                                  | 181       | 7.72%   |
| Microdia                               | 165       | 7.04%   |
| Realtek Semiconductor                  | 159       | 6.78%   |
| IMC Networks                           | 152       | 6.48%   |
| Bison Electronics                      | 128       | 5.46%   |
| Logitech                               | 118       | 5.03%   |
| Sunplus Innovation Technology          | 104       | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 86        | 3.67%   |
| Quanta                                 | 75        | 3.2%    |
| Syntek                                 | 72        | 3.07%   |
| Alcor Micro                            | 54        | 2.3%    |
| Apple                                  | 50        | 2.13%   |
| Silicon Motion                         | 48        | 2.05%   |
| Lite-On Technology                     | 40        | 1.71%   |
| Ricoh                                  | 39        | 1.66%   |
| Microsoft                              | 28        | 1.19%   |
| Z-Star Microelectronics                | 25        | 1.07%   |
| Lenovo                                 | 23        | 0.98%   |
| Acer                                   | 22        | 0.94%   |
| Primax Electronics                     | 15        | 0.64%   |
| Importek                               | 15        | 0.64%   |
| GEMBIRD                                | 14        | 0.6%    |
| OmniVision Technologies                | 9         | 0.38%   |
| Luxvisions Innotech Limited            | 9         | 0.38%   |
| DigiTech                               | 9         | 0.38%   |
| Aveo Technology                        | 9         | 0.38%   |
| ALi                                    | 9         | 0.38%   |
| Samsung Electronics                    | 8         | 0.34%   |
| Cubeternet                             | 8         | 0.34%   |
| Creative Technology                    | 8         | 0.34%   |
| KYE Systems (Mouse Systems)            | 5         | 0.21%   |
| Huawei Technologies                    | 5         | 0.21%   |
| Genesys Logic                          | 5         | 0.21%   |
| Generalplus Technology                 | 5         | 0.21%   |
| ARC International                      | 5         | 0.21%   |
| Pixart Imaging                         | 4         | 0.17%   |
| Jieli Technology                       | 4         | 0.17%   |
| Trust                                  | 3         | 0.13%   |
| Intel                                  | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 57        | 2.43%   |
| Chicony Integrated Camera                               | 46        | 1.96%   |
| Suyin Integrated_Webcam_HD                              | 35        | 1.49%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 35        | 1.49%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 35        | 1.49%   |
| Realtek Integrated_Webcam_HD                            | 32        | 1.36%   |
| Chicony USB 2.0 Camera                                  | 29        | 1.23%   |
| Chicony USB2.0 HD UVC WebCam                            | 27        | 1.15%   |
| Microdia Integrated_Webcam_HD                           | 26        | 1.11%   |
| Logitech Webcam C270                                    | 26        | 1.11%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 26        | 1.11%   |
| Bison Integrated Camera                                 | 26        | 1.11%   |
| Chicony EasyCamera                                      | 24        | 1.02%   |
| Sunplus Integrated_Webcam_HD                            | 23        | 0.98%   |
| Chicony VGA WebCam                                      | 23        | 0.98%   |
| Syntek Integrated Camera                                | 22        | 0.94%   |
| Apple Built-in iSight                                   | 22        | 0.94%   |
| Syntek Lenovo EasyCamera                                | 21        | 0.89%   |
| Quanta HP Webcam                                        | 21        | 0.89%   |
| Microdia Integrated Webcam                              | 21        | 0.89%   |
| Chicony HP TrueVision HD                                | 21        | 0.89%   |
| Bison Lenovo EasyCamera                                 | 20        | 0.85%   |
| Sunplus HD WebCam                                       | 19        | 0.81%   |
| Realtek USB Camera                                      | 19        | 0.81%   |
| Chicony TOSHIBA Web Camera - HD                         | 19        | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 19        | 0.81%   |
| Chicony Lenovo EasyCamera                               | 18        | 0.77%   |
| Logitech Webcam C310                                    | 17        | 0.72%   |
| Logitech HD Pro Webcam C920                             | 17        | 0.72%   |
| Lite-On Integrated Camera                               | 17        | 0.72%   |
| Quanta VGA WebCam                                       | 16        | 0.68%   |
| IMC Networks Integrated Camera                          | 16        | 0.68%   |
| Suyin HP Truevision HD                                  | 15        | 0.64%   |
| IMC Networks UVC VGA Webcam                             | 15        | 0.64%   |
| Chicony Webcam                                          | 15        | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                           | 15        | 0.64%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.64%   |
| Chicony Acer CrystalEye Webcam                          | 15        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.64%   |
| Bison EasyCamera                                        | 15        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 106       | 38.97%  |
| AuthenTec                  | 50        | 18.38%  |
| Upek                       | 33        | 12.13%  |
| Synaptics                  | 20        | 7.35%   |
| Shenzhen Goodix Technology | 20        | 7.35%   |
| STMicroelectronics         | 14        | 5.15%   |
| LighTuning Technology      | 14        | 5.15%   |
| Elan Microelectronics      | 14        | 5.15%   |
| Focal-systems.Corp         | 1         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 10.66%  |
| AuthenTec AES2810                                                          | 21        | 7.72%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 5.88%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 5.51%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 5.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 4.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 4.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 4.04%   |
| Elan ELAN:Fingerprint                                                      | 10        | 3.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 3.31%   |
| Synaptics  WBDI                                                            | 9         | 3.31%   |
| Validity Sensors VFS491                                                    | 7         | 2.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 2.57%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 2.57%   |
| AuthenTec AES1600                                                          | 7         | 2.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.84%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.84%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.84%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.47%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.47%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.47%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.47%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.1%    |
| Elan WBF Fingerprint Sensor                                                | 3         | 1.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.74%   |
| Synaptics WBDI Device                                                      | 2         | 0.74%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.74%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.37%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.37%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.37%   |
| Synaptics TouchPad                                                         | 1         | 0.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.37%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.37%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.37%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 74        | 49.33%  |
| O2 Micro                          | 22        | 14.67%  |
| Alcor Micro                       | 21        | 14%     |
| Lenovo                            | 13        | 8.67%   |
| Upek                              | 8         | 5.33%   |
| OmniKey                           | 3         | 2%      |
| SCM Microsystems                  | 2         | 1.33%   |
| VASCO Data Security International | 1         | 0.67%   |
| Reiner SCT Kartensysteme          | 1         | 0.67%   |
| Microchip Technology              | 1         | 0.67%   |
| Fujitsu Siemens Computers         | 1         | 0.67%   |
| CHERRY                            | 1         | 0.67%   |
| Bit4id                            | 1         | 0.67%   |
| Advanced Card Systems             | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 31.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 14.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 12.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 12.67%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 8.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 5.33%   |
| Broadcom 5880                                                                | 8         | 5.33%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.33%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.67%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.67%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.67%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.67%   |
| OmniKey CardMan 4321                                                         | 1         | 0.67%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.67%   |
| OmniKey CardMan 1021                                                         | 1         | 0.67%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.67%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.67%   |
| CHERRY SmartTerminal ST-2xxx                                                 | 1         | 0.67%   |
| Bit4id miniLector EVO                                                        | 1         | 0.67%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3958      | 83.08%  |
| 1     | 684       | 14.36%  |
| 2     | 116       | 2.43%   |
| 3     | 6         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 272       | 29.57%  |
| Graphics card            | 265       | 28.8%   |
| Chipcard                 | 146       | 15.87%  |
| Net/wireless             | 79        | 8.59%   |
| Storage                  | 37        | 4.02%   |
| Multimedia controller    | 30        | 3.26%   |
| Bluetooth                | 26        | 2.83%   |
| Communication controller | 20        | 2.17%   |
| Camera                   | 13        | 1.41%   |
| Unassigned class         | 12        | 1.3%    |
| Card reader              | 6         | 0.65%   |
| Sound                    | 3         | 0.33%   |
| Network                  | 3         | 0.33%   |
| Modem                    | 3         | 0.33%   |
| Storage/ata              | 2         | 0.22%   |
| Unclassified device      | 1         | 0.11%   |
| Net/ethernet             | 1         | 0.11%   |
| Flash memory             | 1         | 0.11%   |

